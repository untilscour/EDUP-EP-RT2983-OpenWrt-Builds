# OpenWrt 25.12.0 for EDUP EP-RT2983
EDUP EP-RT2983 comes with a factory installed version of OpenWrt 23.05 with device name "netis,n6".

These images are OpenWrt 25.12.0 for EDUP EP-RT2983 with properly labelled and working Ethernet ports (LAN1, LAN2, LAN3, WAN), LED indicator lights and MAC addresses (LAN/WAN/Wifi 2.4G/Wifi 5G). 

# Install: 
1. Log in to LuCI
2. Go to System, Backup / Flash Firmware
3. If desired, backup the current system by saving (all) the mtdblock contents. 
4. Flash new firmware image, select Flash image. 
5. Browse and select the sysupgrade file `openwrt-25.12.0-ramips-mt7621-edup_ep-rt2983-squashfs-sysupgrade.bin` and then Upload. 
6. Unselect "Keep settings and retain the current configuration" - Note: All settings will be reset to default. Wifi is not enabled by default so a connection via Ethernet is necessary to log in and set up. 
7. Allow "Force upgrade" (tick the box if there is one), or press Continue if there is no box to tick. This is because the name is now "edup,ep-rt2983" as it should have been from the start. 
8. Proceed to flash. Wait for reboot and keep power connected. 
9. After reboot, default address to access LuCI is 192.168.1.1 with no password

# Disclaimer
No warranties whatsoever. Use at your own risk. 
