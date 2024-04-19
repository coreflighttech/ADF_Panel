# ADF Radio Module

*** WARNING: SPAD BaudRate is <b>9600</b> for this firmware ***

*** Online SPAD complete device snippet is <b>#10857</b> (Core Flight Technologies 737 ADF PANEL for PMDG 737) ***

*** Internal devices features ***

- Backlight brightness level setting by pressing TFR and turning outter encoder
- Display brightness level setting by pressing TFR and turning inner encoder
- Soft reset by pressing TFR + Encoder Push
To manage ADF panel digits and backlight brightness from SPAD, search for these variables.
- DISPLAY_BRI : ADF panel digits brightness from 0 to 15 (DEVICE:1L2P/CFT737ADF/DISPLAY_BRI)
- BACKLIGHT_BRI : ADF panel backlight brightness from 0 to 255 (DEVICE:1L2P/CFT737ADF/BACKLIGHT_BRI)

*** How to upload Firmware to the Core Flight Tech. B737 ADF? ***

Please be careful while uploading. 
Uploading the wrong version can make your device totally useless.

How to install firmware -> https://github.com/coreflighttech/Uploader
	
Important Note: While uploading, never interrupt the communication of the ATC. Otherwise, there is no way to recover if damaged.

https://coreflighttech.com/product/b737-adf-radio-module-panel/

For any feedback, please leave an e-mail to info@coreflighttech.com

