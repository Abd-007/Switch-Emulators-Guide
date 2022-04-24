# Yuzu Guide

***The guide will be split into several sections, you can use the Table of Contents to easily get to the section you need to***

***Important Note: You need https://www.base64decode.org to decode some of the links that look like a string of words and numbers. Copy the string and paste it into the base64 decoder and press decode to get real link. I will not be repeating this everywhere***

* * * 

## Section 1: Installing the Emulator

(Optional) Go to https://yuzu-emu.org/downloads/ to download the latest mainline build. 

Get an Early Access build. Those generally work better than mainline and are more updated. You can get Early Access builds from our handy auto-updater or download them manually, if you want

**Auto Updater:** https://mostlywhat.github.io/128Bit-Yuzu-Installer/

**Github Source (for downloading manually):** https://github.com/Kryptuq/Yuzu-Early-Access-files/releases

**Note:** If you get the "msvcp140_atomic_wait.dll is missing" error when launching Yuzu from here, install this https://aka.ms/vs/16/release/vc_redist.x64.exe

Once you get either mainline or early access, just open yuzu, and you are done with this step.

## Section 2: Installing keys and Firmware

### Keys

When you launch Yuzu for the first time, an error for missing components will pop up. To fix that, you need the prod.keys

**Keys:** `aHR0cHM6Ly9kcml2ZS5nb29nbGUuY29tL2RyaXZlL2ZvbGRlcnMvMUtBeW0tUnBHSUR1SmlTbU1MbXBDdEdWYmhMbTRWalRaP3VzcD1zaGFyaW5n`

**Note:** Older keys are included. Download only the latest! If what you download also contains title.keys, delete it. It is not needed

After installing the keys, put them anywhere on your PC. Open yuzu, go to the top left corner and click on "file" and then "Open yuzu folder". Open the keys folder and put (only) the prod.keys file in that folder.

Restart yuzu and you shouldn't get the error anymore. If you still do, you did a step wrong.

### Firmware

Downloading firmware for yuzu is in no way necessary. However, it is needed for some games to fix crashes. Therefore it is advised to get it nonetheless

**Firmware:** `aHR0cHM6Ly9kYXJ0aHN0ZXJuaWUubmV0L3N3aXRjaC1maXJtd2FyZXMv`

Open yuzu and go to the yuzu folder then nand\system\Contents\registered and paste all the firmware files in there.

Once you get keys and firmware, you're done with this step

## Section 3: Installing Games

Now on to installing games. Here is a list of trusted websites to get switch games from

**List of Websites to get switch games from:** `aHR0cHM6Ly9ueGJyZXcuY29tLwoKaHR0cHM6Ly9uc3cydS54eXovCgpodHRwczovL25zd2dhbWUuY29tL2NhdGVnb3J5L3N3aXRjaC8KCmh0dHBzOi8vd3d3LnppcGVydG8uY29tL25pbnRlbmRvLXN3aXRjaC1uc3Av`

**Note:** It is recommended to get an adblocker before visiting any of these websites. You can get one at https://ublockorigin.com/ 

**Note:** When downloading, you might be presented with 3 file types. NSP, XCI and NSZ. Yuzu and Ryujinx do not support NSZ, so don't download that. XCI has the update file merged into the game file so you need to download only one file. NSP has different game and update files, making it easier to update. Get whichever you lik
