# LSPosed Framework
[Original version](https://github.com/LSPosed/LSPosed)
## Notice

This fork is modified for XTC devices, other devices may have unknown issues.

## Supported Versions

Android 8.1 (CaremeOS)

## Install

1. Install Magisk v24+
2. Install [Riru(@huanli233 modified)](https://github.com/huanli233/Riru-XTC-8.1/releases/tag/v26.1.7.Careme) v26.1.7.r534.eeba8a88da (original version doesn't work on XTC devices)
3. [Download](#download) and install LSPosed in Magisk app
4. Reboot
5. Install LSPosed manager from zip and open it (parasitic manager will crash on XTC devices)
6. Have fun :)

## Credits 

- [Magisk](https://github.com/topjohnwu/Magisk/): makes all these possible
- [Riru](https://github.com/RikkaApps/Riru): provides a way to inject code into zygote process
- [XposedBridge](https://github.com/rovo89/XposedBridge): the OG Xposed framework APIs
- [Dobby](https://github.com/jmpews/Dobby): used for inline hooking
- [LSPlant](https://github.com/LSPosed/LSPlant): the core ART hooking framework
- [EdXposed](https://github.com/ElderDrivers/EdXposed): fork source
- ~[SandHook](https://github.com/ganyao114/SandHook/): ART hooking framework for SandHook variant~
- ~[YAHFA](https://github.com/rk700/YAHFA): previous ART hooking framework~
- ~[dexmaker](https://github.com/linkedin/dexmaker) and [dalvikdx](https://github.com/JakeWharton/dalvik-dx): to dynamically generate YAHFA hooker classes~
- ~[DexBuilder](https://github.com/LSPosed/DexBuilder): to dynamically generate YAHFA hooker classes~

## License

LSPosed is licensed under the **GNU General Public License v3 (GPL-3)** (http://www.gnu.org/copyleft/gpl.html).
