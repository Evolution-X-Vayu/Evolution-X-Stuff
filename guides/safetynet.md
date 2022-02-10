### SafetyNet Fix Guide Poco X3 Pro (vayu/bhima)

### Status:
- SafetyNet passed (without Magisk or Flash any module).
- Play Store is certified by default.

### If your SafetyNet failed, follow guides here:

### Requirements:
1. Download latest [**Magisk (root)**](https://github.com/topjohnwu/Magisk/releases/)
2. Download latest [**SafetyNet fix (module)**](https://github.com/kdrag0n/safetynet-fix/releases/)
3. Download [**YASNAC -  SafetyNet Checker**](https://play.google.com/store/apps/details?id=rikka.safetynetchecker/) 

### Guides #1 (without module):
1. Flash Magisk (root) from recovery > reboot
2. Go to Magisk settings:
   - Enable Zygisk 
   - Enable Enforce Denylist
3. Tap configure Denylist > 3 buttons on top right > Show system apps
4. Choose Google Play Services
5. Enable toggle:
   - ```com.google.android.gms```
   - ```com.google.android.gms.unstable```
   - ```com.google.android.gms.snet```
6. Go to Magisk settings again
7. Hide Magisk package
8. Reboot device
9. Force Stop and Clear data you Play Store > Re-open Play Store
10. Open YASNAC > Check your SafetyNet status
11. Enjoy!

### Guides #2 (with module):
1. Flash Magisk (root) from recovery > reboot
2. Flash SafetyNet fix (module) from Magisk > reboot
3. Go to Magisk settings:
   - Enable Zygisk 
   - Enable Enforce Denylist
4. Tap configure Denylist > 3 buttons on top right > Show system apps
5. Choose Google Play Services
6. Enable ```com.google.android.gms``` toggle
7. Go to Magisk settings again
8. Hide Magisk package
9. Reboot device
10. Force Stop and Clear data you Play Store > Re-open Play Store
11. Open YASNAC > Check your SafetyNet status
12. Enjoy!

### Notes:
* Both Guides are working.
* You can try [**Guides #1**](https://github.com/elizabethangelalorenza/documentations/blob/main/guide/safetynet.md#guides-1-without-module) and if u failed try again with [**Guides #2**](https://github.com/elizabethangelalorenza/documentations/blob/main/guide/safetynet.md#guides-2-with-module).
