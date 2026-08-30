# Linux x86-64 prebuilt

- Source commit: `c0ee517b0ec39267767f99f17ef648a2c3d77645`
- Source: https://github.com/musosoft/TickrateEnabler
- SDK: `alliedmodders/hl2sdk` CSS commit `d0ddd91faed91af581c06df28354156ae31b0bdb`
- Metamod Source: commit `2667e8e5947237c4cb7ea45cec3913ad6a44757c`
- Compiler: Clang 21.1.8, Linux x86-64
- Configuration: `--enable-optimize --symbol-files --sdks=css --targets=x86_64 --tickrate=100`
- SHA-256: `4b3a2d519a5920301e1c1f824548c51e5218e77f41a3ac89ad4a28ac6240a144`

Verified in an isolated SteamCMD CS:S AppID 232330 x64 server: the exact binary was mapped into the live server process, the server bound UDP/TCP port 27056, and the log reported `SV_ActivateServer: setting tickrate to 100.0`.
