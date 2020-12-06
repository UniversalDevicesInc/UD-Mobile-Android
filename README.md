# UD-Mobile-Android
Issue-only repository for tracking issues related to the UD Mobile Android App

## Reporting an Issue
Please open an [issue](https://github.com/UniversalDevicesInc/UD-Mobile-Android/issues).
Include UD Mobile version number and ISY Firmware version in report.

## Installation
Google Play [UD Mobile](https://play.google.com/store/apps/details?id=com.universaldevices.udmobile).

## Remote Connections
If not using the ISY Portal, UD Mobile supports remote connections by A) VPN and selecting "Only Use Local Connection" or B) A valid CERT. This will not work with self signed CERTs unless trusted by the Android System. Adding a self signed CERT to the Android system is beyond the scope of support for this app.
Apple and Google have given developers notice that bypassing security may result in removal from the app stores. While it is currently possible to bypass the https CERT there is no guarantee it will work on the next version or that it will not result in removal from the respective app platforms.  

# Node Servers
Please reboot the ISY if Node Server values are not formatted or are formatted incorrectly.  This is needed for all new Node Server installs and may be needed if NodeDef, Editor, or NLS files for a Node Server have been changed during an update.  After rebooting the ISY UD Mobile may need to sync with the ISY to obtain the new files. Incorrect formatting only affects clients, including UD Mobile, which read the formatted value from the ISY subscription.  Incorrect formatting does not appear to affect the Admin Conslole.
