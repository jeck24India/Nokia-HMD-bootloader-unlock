# Nokia-HMD-bootloader-unlock
bootloader unlock guide for nokia and hmd devices

# Nokia Mediatek Devices
bootloader of nokia mediatek devices can be unlocked by using [mtkclient](https://github.com/bkerler/mtkclient)

# Nokia Unisoc Devices
bootloader of nokia unisoc devices can be unlocked by loading patched [splloader on fdl](https://github.com/TomKing062/CVE-2022-38694_unlock_bootloader/wiki/patch_do_cboot%E2%80%90FDL1)

# Nokia Qualcomm Devices
[Download abl](https://qlmflasherpro.com/index.php?a=downloads&b=folder&id=1413) protocols 

Connect your nokia or hmd device with jtag

read gpt

browse select and flash abl file on abl partition

connect in fastboot

send command

<code>fastboot flashing unlock</code>

**Credit:** TomKing062, bkerler, hikaricalyx
