# Offline coordinate audit

The current coordinate candidates are not ready for an overlay.

## Evidence

- The last screenshot shows an ally at HUD distance 11 metres. The corresponding sequential memory capture gives that ally only 0.309 units of horizontal separation from the local Pawn.
- Two earlier same-match captures give nearby allies Z differences around -829 units; the preceding match gives differences around -1212 to -1262 units. These do not support a universal height correction.
- Foreign RootComponent.RelativeLocation contains non-FFFF handlers. The last root-minus-replicated differences are exactly [-373.9375, +373.9375, -373.9375] and [-411.9375, +411.9375, -411.9375]. This algebraic pattern does not establish either field as a correct world position.
- Camera yaw and screenshot compass do not agree in the captures. Each new memory page starts a separate adb/dd process; a cached camera page can precede the screenshot by the entire roster traversal. No acquisition timestamps were recorded per page.

## Reader review

The reader slices within 4096-byte pages and splits cross-page reads correctly. It clears its page cache per sample. Neither property makes the sample atomic: individual pages are read at different times. UObject membership validates pointer identity, not coordinate correctness. EncHandler=0xFFFF and finite floats are format checks, not spatial validation.

## Next verification requirements

Capture camera immediately before and after a screenshot and reject samples with changed pose. Capture only discovered ally pointers during this bracket, omitting class-name and full-roster traversal. Record monotonic times for every read. Separately verify the camera source and coordinate fields from runtime metadata/code; do not apply a fitted constant correction or claim boxes are ready. No further user movement is needed for this offline audit.
