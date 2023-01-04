# ncd_Ethernet

Update Firmware Instructions:
1. Download the latest NCD Config Tool from the NCD Config Tool
2. Connect your module to the same network as the computer running the NCD Config Tool
3. Power up the board that the module is attached to
4. Run the NCD Config Tool and click on the Search button until the module is displayed on the left
5. Download the latest firmware for your module
    * Revision 1 hardware will have a device type of NCDWEBI in the NCD Config Tool
    * Revision 2 hardware will have a device type of NCDWEBIV2 in the NCD Config Tool
    * If you are not seeing the device type click on the plus button next to the module's MAC address in the NCD Config tool to expand it
6. Select the module you would like to upload the firmware for on the left
7. Select Upload from the buttons along the top of the NCD Config Tool
8. Select Firmware from the submenu
9. Select the firmware .bin file downloaded earlier
10. Wait for a notification telling you that the firmware has been updated
11. Hit search until the module comes back up and obtains an IP address
12. Select Reset from the buttons along the top
12. Select Factory Reset from the submenu


## Changelog
### Hardware Rev 2 Firmware
v2.2:
* Fixed Javascript callback bug, pass-through in AT mode bug
* Fixed issue with LED not lighting when socket Connected
* Fixed issue with Device name being ignored when sent during initial connection
* More robust detection of physical disconnect to automatically resolve socket connection
* Fixed issue with Inactivity setting being ignored

### Hardware Rev 1 Firmware
v2.4
* Fixed Javascript callback bug, pass-through in AT mode bug
