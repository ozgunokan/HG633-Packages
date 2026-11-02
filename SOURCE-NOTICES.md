# Component source materials

Current native/GPL source materials are attached to the sources-opkg-20261031 Release. The archive includes corresponding helper/TLS upstream materials, the matching Linux source baseline plus reviewed module/kernel overlays and build references, and Zapret source/dependency archives. Lua, JavaScript, shell and HTML source is directly present in the IPK data archives. Component and upstream license notices remain applicable. Proprietary vendor DSP firmware and personal RF calibration are excluded.

The native source archive is 90,763,512 bytes with SHA256 `5f0a4e1b4b2a87d5c4ca973b7df4c32b37ec6f985c0c4185a2c52551b823e826`. Each new source file was checked against reviewed sources or its known upstream source; the embedded historical native-source archive was verified identical to its already-public Release asset.

The 2026-11-02 DSL range extension has an additional `hg633-dsl-target-45-sources.tar.gz` source asset on its individual DSL Release. It contains the updated PHY C source, parser/codec test and native build hash/recipe. Existing matching musl sources remain in the original source distribution. Targets above 10 have not been live-line qualified.
