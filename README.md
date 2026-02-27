# OpenWrt 25.12.0-rc4 for EDUP EP-RT2983
EDUP EP-RT2983 comes with a factory installed version of OpenWrt 23.05 with device name "netis,n6".

These images are OpenWrt 25.12.0-rc4 for EDUP EP-RT2983 with properly labelled and working Ethernet ports (LAN1, LAN2, LAN3, WAN), LED indicator lights and MAC addresses (LAN/WAN/Wifi 2.4G/Wifi 5G). 

# Install: 
1. Log in to LuCI
2. Go to System, Backup / Flash Firmware, Flash new firmware image and then select Flash image. 
3. Browse and select the sysupgrade file `openwrt-25.12.0-rc4-ramips-mt7621-edup_ep-rt2983-squashfs-sysupgrade.bin` and then Upload. 
4. Unselect "Keep settings and retain the current configuration" - Note: All settings will be reset to default. Wifi is not enabled by default so a connection via Ethernet is necessary to log in and set up. 
5. Allow "Force upgrade" (tick the box if there is one), or press Continue if there is no box to tick. This is because the name is now "edup,ep-rt2983" as it should have been from the start. 
6. Proceed to flash. Wait for reboot and keep power connected. 
7. After reboot, default address to access LuCI is 192.168.1.1 with no password

# Disclaimer
No warranties whatsoever. Use at your own risk. 
