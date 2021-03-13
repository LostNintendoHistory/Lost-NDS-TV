# How to apply the patch


 **IMPORTANT**: Do this at your own risk , if you do not follow the steps exactly as specified you will get a brick on your Nintendo DS.

The CFW you generate will be used for any Nintendo DS lite that  you have 😉 so if you generate it, you just have to install it.


# Procedure
Steps:

 - Install flashme v8a no auto (IMPORTANT that v8a no auto, otherwise your console will be a brick!)  
 - Dump your firmware  
 - Patch with IPS  
 - Check in emulator (no$gba for example) before installing to avoid brick  
 - Install CFW with fwManager


## 1. Install Flashme v8a noautoboot 
**IMPORTANT: INSTALL v8a_flashme_noauto, must be v8a and noauto (Normal version, "Stealth" (noauto_stealth) version does not work and you will get a brick with the path).**
 
 Install `v8a_flashme_noauto`, search in google, we can not provide this.
 
 Hash of `v8a_flashme_noauto.nds` (Check this to confirm that you download the correct version and correctly)
| Algorithm | Hash |
|--|--|
| SHA256 | 3C090BE0EFE17F011D50CF235920AF840B12381DB4F52EB7B29397E3246F8D6F |

If the hash is not the same as the file you downloaded, do not continue this tutorial.
 

## 2. Dump your firmware

After install v8a_flashme_noauto dump your firmware using [DSBF Dump](http://www.ds-scene.net/?s=viewtopic&nid=2460)
## 3. Patch firmware with IPS

 - Download  [Lunar IPS](https://www.romhacking.net/utilities/240/)
 - Open Lunar IPS and click on "Apply IPS Patch"
 - Open `ndstvout-patch.ips`
 - Now select "*All files*" (in the right corner) and select your dump firmware
 - After a window comes out that says "The file was successfully patched", your CFW with TV out enable will be ready.


## 4. Check your CFW in a emulator before install

**IMPORTANT: If you don't want to get a brick please check your CFW in the emulator**

 - Download No$Gba emulator
 - Rename your CFW to `firmware.bin`
 - Put in the folder of .exe of NO$GBA: `firmware.bin` and `biosnds7.rom` `biosnds9.rom`. (if you have a error with your bios, search on internet other bios)
 - Click on "Options->Emulation Setup"  and then search "Reset/Startup Entrypoint" and change to "GBA/NDS BIOS (Nintendo logo)".
 - Click "Save now" and then "OK"
 - Open any game
 - If the console menu starts up without any glitches or error then you have probably applied the patch correctly and it is ready to install on a real Nintendo DS lite.  **If you get a error try to download other bios (search on internet) but if the problem continues, DO NOT INSTALL the CFW, you did something wrong and you will get a brick if you install it**




## 5. Install CFW

 - Put in your flashcart "fwmanager.nds" .Source:https://github.com/CTurt/CFW-Suite/tree/master/fwManager
 - Make a folder with name `firmwares` and put inside your CFW file
 - Open the fwmanager.nds in your flashcart and select the CFW. Short the SL1 terminal as if you were installing FlashMe.
 - After finish power off and power on your Nintendo DS.
 - Now enjoy your NDS in your TV  with NDS TV OUT 😉