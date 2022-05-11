![Installation Guide For PixelPlusUI on Motorola One Power (chef)](https://i.imgur.com/pmZkslu.png "Installation")

# Installation Guide For PixelPlusUI on chef

### CLEAN FLASH (RECOMMENDED) :
0. Boot latest [TWRP](https://dl.twrp.me/chef/twrp-3.6.1_9-0-chef.img) using fastboot
1. Wipe - Format data - Write "yes" - Format it
2. Wipe - Advanced Wipe - System, Vendor, Cache, Dalvik/ART cache - Wipe it
3. Installation - Flash [aosp_chef-ota-retrofit-eng.rushiranpise.zip](https://drive.google.com/u/0/uc?id=1wGX4WHos0cTfoKsmdmdbnH2exsZ5hXg8&export=download) (This is required for 1st time when flashing rom)
4. Reboot - Reboot to Recovery (Rom Recovery)
5. Install Update - Adb sideload / External Sd Card
2. Installation - Flash <a href=https://ppui.site/download>ROM archive</a> (Download Latest Build & don't flash gapps!)
3. Installation - Flash <a href=https://github.com/topjohnwu/Magisk/releases>latest Magisk v24.x archive</a> (optional)
6. Reboot - Reboot to system

### DIRTY FLASH IF AN UPDATE (ONLY CLEAN FLASH FROM 4.3)
1. Wipe - Advanced Wipe - System, Vendor, Cache, Dalvik/ART cache - Wipe it
2. Installation - Flash <a href=https://ppui.site/download>ROM archive</a> (don't flash gapps!)
3. Installation - Re-Flash <a href=https://github.com/topjohnwu/Magisk/releases>latest Magisk v24.x archive</a> (optional)
4. Wipe - Advanced Wipe - Cache, Dalvik/ART cache - Wipe it
5. Reboot - Reboot to system

## Note
1. ONLY CLEAN FLASH FROM 4.3
2. Recommended to update all Google packages after first setup
