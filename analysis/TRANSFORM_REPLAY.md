# Transform replay investigation

The research can now replay a captured callback without ADB using emulate_transform_lobby.py and callback-lobby-snapshot. No emulated writes are written back to the Android process.

Default CPU replay returned after 416 instructions. The default Unicorn CTR_EL0 is 0x8444C004 while a captured guard compared its upper bits against 0x94440000. The CP register is read-only in this emulator: cpr_write did not change it. A local instruction hook supplies the inferred value for exploratory replay. ARM64 MAX CPU model resolves the CASAH exception. A synthetic TLS record lets the mutex routine execute. The replay then returned after 697 instructions; its saved x0 was unchanged and its writes affected bookkeeping/mutex data, not the supplied transform. This is not a captured live invocation and provides no decoder validation.

The getter RVA 0x107BBB8C adds 0x210 to its input component and traverses two trampoline layers. The second trampoline is 0x77D6664C08, callback 0x7AFC7F9000. Its relocated instructions include RET at 0x77D6664D64. The continuation pointer after that RET points into the next function and must not be interpreted as another executed decoding stage. The first callback had previously been mistaken for the entire chain.

References: current-transform-trace.json, callback-offline-result.json, callback-lobby-result.json, second-getter-callback.json, second-callback-code.txt, second-getter-continuation.json.

Current limitation: runtime-dependent callbacks have not been replayed with actual invocation registers/TLS and a verified foreign transform. The experiment does not establish current player world positions. Final screen alignment remains unverified and needs match data.
