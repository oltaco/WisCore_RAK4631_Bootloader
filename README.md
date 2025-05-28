# RAK4631 Bootloader

This is the Adafruit-based CDC/DFU/UF2 bootloader for WisCore RAK4631 based boards, modified with a fix for OTA DFU mode to make it more resilient to a bad flash.

This bootloader will reboot back to OTA DFU mode after an unsuccessful flash so that you can try again.

## Installation

There are two options to install the bootloader, the easiest way is with UF2 mode. Installing the bootloader this way will keep your app firmware intact.

### Flashing with UF2 file.
1. Boot the RAK into UF2 mode by double pressing the reset button.
2. Copy the UF2 file onto the RAK4631 drive that appears.
3. The RAK will reboot and you should be running the new bootloader.
