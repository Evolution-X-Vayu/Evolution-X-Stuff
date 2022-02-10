### Flashing Guides Poco X3 Pro (vayu/bhima)

This guides based on my build (Evolution X) for Poco X3 Pro (vayu) device:

Clean Flash from MIUI:
1. Reboot to Recovery
2. Wipe Dalvik/ART Cache, Data, and Cache on Advanced Wipe
3. Flash ROM
4. Flash DFE (optional)
5. Format Data, type "yes" and press enter
6. Reboot to System
7. Enjoy!

Clean Flash from other Custom ROM:
1. Reboot to Recovery
2. Wipe Dalvik/ART Cache, Data, and Cache on Advanced Wipe
3. Flash ROM
4. Flash DFE (optional)
5. Format Data, type "yes" and press enter
6. Reboot to System
7. Enjoy!

Clean Flash from Android 11 Custom ROM:
1. Reboot to Recovery
2. Wipe Dalvik/ART Cache, Data, and Cache on Advanced Wipe
3. Flash ROM
4. Flash DFE (optional)
5. Format Data, type "yes" and press enter
6. Reboot to System
7. Enjoy!

Dirty Flash from Evolution X build:
1. Reboot to Recovery
2. Flash ROM
3. Flash DFE (optional)
4. Wipe Dalvik/ART Cache
5. Reboot to System
6. Enjoy!

Flashing for DFE user:
1. Reboot to Recovery
2. Flash ROM
3. Flash DFE (mandatory)
4. Wipe Dalvik/ART Cache
5. Reboot to System
6. Enjoy!

### Notes:
* OSS based.
* SELinux Enforcing.
* Play Store is certified.
* SafetyNet passed (without Magisk).
* I recommended to flash Magisk after booted up.
* Already include GApps, no need to flash GApps again.
* Need to Clean Flash if you are coming from Android 11.
* Always backup your data before flashing this ROM to avoid any cases.
* If you are DFE User, don't forget to flash DFE file .zip after flashing ROM (before reboot to system).
* Flashing firmware is not mandatory, that is "optional". No need to flash every flashing ROM.
* You can use any firmware version, 12.0.X or 12.5.X doesn't matter, it will boot. Choose your favorite firmware.
* If you ask my firmware version, I'm using V12.0.4.0.RJUMIXM currently.

### Important Link:
* Magisk:
  - [**Magisk v23.0**](https://github.com/topjohnwu/Magisk/releases/tag/v23.0)
  - [**Magisk v24.1 (Zygisk)**](https://github.com/topjohnwu/Magisk/releases/tag/v24.1)
  - [**Magisk Canary (Zygisk)**](https://raw.githubusercontent.com/topjohnwu/magisk-files/canary/app-debug.apk)
* Firmware:
  - [**12.0.X.X-RJUIDXM**](https://sourceforge.net/projects/vayu-repository/files/Firmware/ID/)
  - [**12.5.X.X-RJUMIXM**](https://xiaomifirmwareupdater.com/firmware/vayu/)
  - [**Archive all region**](https://xiaomifirmwareupdater.com/archive/firmware/vayu/)
* Recovery:
  - [**TWRP Recovery OFFICIAL**](https://dl.twrp.me/vayu/)
  - [**OrangeFox Recovery OFFICIAL**](https://orangefox.download/device/vayu)
* Disable Force Encryption (DFE) for Custom ROM AOSP (only):
  - [**dynDFE_v1.0**](https://sourceforge.net/projects/vayu-repository/files/Additional/dynDFE/dynDFE_v1.0_vayu.zip/download)
  - [**dynDFE_v2.0**](https://sourceforge.net/projects/vayu-repository/files/Additional/dynDFE/dynDFE-v2.0_vayu.zip/download)
