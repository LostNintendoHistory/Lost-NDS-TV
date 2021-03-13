# How to apply the patch


 **IMPORTANT**: Do this at your own risk, if you do not follow the steps exactly as specified you will brick your Nintendo DS and render ir unusable. We do not take any responsibility.

The CFW you generate will be used for any Nintendo DS lite that you have 😉 so if you generate it, you just have to install it.


# Procedure
Steps:

 - (1) Install flashme v8a noauto (IMPORTANT: use v8a noauto, not other versions, otherwise your console will be a brick!)  
 - (2) Dump your firmware  
 - (3) Patch with IPS  
 - (4) Check in emulator (no$gba for example) before installing to avoid brick  
 - (5) Install CFW with fwManager


## 1. Install Flashme v8a noautoboot 
**IMPORTANT: INSTALL v8a_flashme_noauto, must be v8a and noauto (Normal version, "Stealth" (noauto_stealth) version does not work and you will get a brick with the path).**
 
 Install `v8a_flashme_noauto`, search in google, we can not and will not provide this. Don't ask us for it. The hash of `v8a_flashme_noauto.nds` should be the following (Check this to confirm that you download the correct version and correctly):
 
| Algorithm | Hash |
|--|--|
| SHA256 | 3C090BE0EFE17F011D50CF235920AF840B12381DB4F52EB7B29397E3246F8D6F |

If the hash is not the same as the file you downloaded, do not continue this tutorial.
 

## 2. Dump your firmware

After installing v8a_flashme_noauto , dump your firmware using the [DSBF Dump](http://www.ds-scene.net/?s=viewtopic&nid=2460) firmware on your flashcart.
You will obtain your firmware in the microSD of your flashcart.

## 3. Patch firmware with IPS

 - Download  [Lunar IPS](https://www.romhacking.net/utilities/240/)
 - Open Lunar IPS and click on "Apply IPS Patch"
 - Open `ndstvout-patch.ips`
 - Now select "*All files*" (in the right corner) and select your dumped firmware from step 2
 - After a window comes out that says "The file was successfully patched", your CFW with TV OUT enabled will be ready.


## 4. Check your CFW in a emulator before installing

**IMPORTANT: If you don't want to get a brick please check your CFW in the emulator**

 - Download No$Gba emulator
 - Rename your CFW to `firmware.bin`
 - Put in the folder of .exe of NO$GBA: `firmware.bin` and `biosnds7.rom` `biosnds9.rom`. (if you have a error with your bios, search on internet other bios)
 - Click on "Options->Emulation Setup"  and then search "Reset/Startup Entrypoint" and change to "GBA/NDS BIOS (Nintendo logo)".
 - Click "Save now" and then "OK"
 - Open any game
 - If the console menu starts up without any glitches or error then you have probably applied the patch correctly and it is ready to install on a real Nintendo DS lite.  **If you get a error try to download other bios (search on internet) but if the problem continues, DO NOT INSTALL the CFW, you did something wrong and you will get a brick if you install it**




## 5. Install CFW

 - Put in your flashcart the homebrew "fwmanager.nds" (Source here:https://github.com/CTurt/CFW-Suite/tree/master/fwManager)
 - Make a folder with name `firmwares` in the root of the flashcart, and put inside your CFW file
 - Open the fwmanager.nds in your flashcart and select the CFW. Short the SL1 terminal as if you were installing FlashMe.
 - After finishing, power off and power on your Nintendo DS.
 - Now enjoy your NDS in your TV with NDS TV OUT 😉
