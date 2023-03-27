# Ryujinx Guide

***The guide will be split into several sections. You can use the Table of Contents to easily get to the section you need to be at.***

***If you want a more detailed guide, you can find Ryujinx's own guide [here](https://github.com/Ryujinx/Ryujinx/wiki/Ryujinx-Setup-&-Configuration-Guide)***

***If you still have a problem after following this guide and want help, please join our Discord server and ask there. It is easier to help there, as we have more resources and people available. You can join the*** [***server by clicking here***](https://discord.gg/87bsZWwF3X)

# Download Instructions (IMPORTANT) 

All the links in this guide are encoded in base64. Whenever you come across a link, copy that link and go to https://www.base64decode.org, then paste that link in the top box and click "Decode". The bottom box will contain your link

Most if not all the stuff you download will be in a compressed format (i.e. .7zip, .zip or .rar). You need to extract them with either [7zip](https://www.7-zip.org) or [WinRAR](https://www.win-rar.com/download.html?&L=0)

If you just want the downloads you can get them from [here](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Links.md)

* * *

### Table of Contents

- [Section 1: Installing the Emulator](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#section-1-installing-the-emulator)
- [Section 2: Installing Keys and Firmware](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#section-2-installing-keys-and-firmware)
   + [Keys](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#keys)
   + [Firmware](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#firmware)
- [Section 3: Installing Games, Updates and DLC](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#section-3-installing-games-updates-and-dlc)
   + [Loading Games into Ryujinx](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#loading-games-into-ryujinx)
   + [Loading Updates and DLCs](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#loading-updates-and-dlcs)
- [Section 4: Optimizations for best performance](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#section-4-optimizations-for-best-performance)
   + [Settings for all GPUs](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#settings-for-all-gpus)
   + [Nvidia GPU settings](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#nvidia-gpu-settings)
   + [AMD GPU settings](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#amd-gpu-settings)
   + [Intel GPU settings](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#intel-gpu-settings)
- [Section 5: Installing Mods, Saves and Shaders](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#section-5-installing-mods-saves-and-shaders)
   + [Mods](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#mods)
   + [Shaders](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#shaders)
   + [Saves](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#saves)
- [Section 6: Misc](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#section-6-misc)
   + [Fixes for errors](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md#fixes-for-errors)

* * * 

## Section 1: Installing the Emulator

**(Optional)** Go to https://ryujinx.org/download to download the latest mainline build. 

**Github Source (for building manually):** https://github.com/Ryujinx/Ryujinx

**Pine-Jinx installer for those on Linux/Steam Deck (Optional):** https://github.com/edisionnano/Pine-jinx (Faster performance than flatpak/regular ryujinx install. The repo walks you through instructions.)

Once you download the release, just extract it and run the Ryujinx executable. Optionally, you can run Ryujinx in portable mode by creating a subfolder in the downloaded Ryujinx folder called "portable". System files such as keys/saves/shader caches would be saved in that newly created folder instead.

* * *

## Section 2: Installing Keys and Firmware

### Keys

When you launch Ryujinx for the first time, an error for missing components will pop up. To fix that, you need the prod.keys.

**Keys:** `aHR0cHM6Ly9kcml2ZS5nb29nbGUuY29tL2RyaXZlL2ZvbGRlcnMvMUtBeW0tUnBHSUR1SmlTbU1MbXBDdEdWYmhMbTRWalRaP3VzcD1zaGFyaW5n`

**Note:** Older keys are included. Download only the latest, and extract the archive using 7zip or WinRAR. If what you download also contains title.keys, delete it. It is not needed.

After downloading the keys, Open Ryujinx, go to the top left corner and click on "File" and then "Open Ryujinx folder". Open the system folder and put (only) the prod.keys file in that folder.

Restart Ryujinx and you shouldn't get the error anymore. If you still do, you messed up. Repeat the previous steps.

### Firmware

**Firmware:** `aHR0cHM6Ly9kYXJ0aHN0ZXJuaWUubmV0L3N3aXRjaC1maXJtd2FyZXMv`

Open Ryujinx, go to the top left corner and click on "Tools", then under "Install Firmware" click "Install a firmware from XCI or ZIP". Navigate to the firmware zip file and click open. When prompted if you want to install firmware, click yes. **DO NOT** extract the firmware zip as it is not necessary.

Once you have keys and firmware installed, you're done with this step.

* * *

## Section 3: Installing games, updates and DLC

Now on to installing games. Here is a list of trusted websites to get switch games, updates and DLC from.

`aHR0cHM6Ly9ueGJyZXcuY29tLwoKaHR0cHM6Ly9uc3cydS54eXovIChodHRwczovL25zdzJ1LmNvbS8pCgpodHRwczovL25zd2dhbWUuY29tL2NhdGVnb3J5L3N3aXRjaC8KCmh0dHBzOi8vd3d3LnppcGVydG8uY29tL25pbnRlbmRvLXN3aXRjaC1uc3AvCgpodHRwczovL3N3aXRjaGVkdHdvLnRvLw==`

**Note:** It is recommended to get an adblocker before visiting any of these websites. You can get one at https://ublockorigin.com/ 

**Note:** It is also recommended to get an extension to bypass URL shortner sites. The recommended one can be found at https://fastforward.team/

**Note:** When downloading, you might be presented with three file types. NSP, XCI, and NSZ. Yuzu and Ryujinx do **not** support NSZ, so don't download that. XCI has the update file merged into the game file so you need to download only one file. NSP has different game and update files, making it easier to update. Get whichever you like.

### Loading games into Ryujinx

Once you download a game, place it into a folder where you wish to keep all your Switch games (**place only the game file and not the update or DLC file**).

Open Ryujinx and click on "Options", then "Settings". Under the General tab, find "Game Directories" and click the "Add" button. Navigate to where your games folder is, and click Add. Finally, click "Save" in the bottom right corner.

### Loading Updates and DLCs

Open Ryujinx. Right click on the game you would like to update or install DLC to. Click "Manage Title Updates" or "Manage DLC". Then use the "Add" button to choose the Update/DLC files you want to install. If it was correctly installed, it should show the updated version next to the game.


You're done here. Next step.

* * *

## Section 4: Optimizations for best performance

Ryujinx doesn't require many optimizations on Windows, you just go to the controls tab and set up your controller. Vulkan is the preferred option, but if a game doesn't work on Vulkan, try OpenGL instead.

If you choose to manually install Ryujinx on Steam Deck/Linux over using the pinejinx installer, it gets a bit more complicated. It is recommended to ask for the right launch options based on your hardware in the Discord server.

**Note:** You can pretty much just start playing now, as all required steps are complete. The next sections are optional i.e. installing saves, mods, shaders and some fixes for errors.


## Section 5: Installing Mods, Saves and Shaders

### Mods

You can get some Switch mods from the following sources:

**Our Collection:** https://drive.google.com/drive/folders/1dY20qH3phqoUfmAEdngTzrtMIvPFwSG4?usp=sharing

**TheBoy181's GitHub:** https://github.com/theboy181/switch-ptchtxt-mods

**Official Yuzu mods page:** https://github.com/yuzu-emu/yuzu/wiki/Switch-Mods

To install mods, right click the game you want to install the mod for, click "Open Mods Directory" and paste the mod folder there. You must place the mod ***folder*** you downloaded, and not just the files inside of it.

To install atmosphere mods made for real hardware, right click the game and instead click "Open Atmosphere Mods Directory" and paste the mod folder there.

### Shaders

You can find some shader caches from our GitHub.

**Shaders:** https://github.com/JENOVAAbsolute/128BB-Shaders

To install shaders:

- Right click a game, click "Cache Management", then "Open Shader Cache Directory" and replace it with your cache.

### Saves 

You can find saves here:

**Our collection:** https://drive.google.com/drive/folders/1G2gHYZn7Dbx_X9iYUgpOfCBiWCixBTWU?usp=sharing

**Alternative:** https://www.homebrewgeneral.net/2020/03/switch-games-save.html

To install saves:

- Right click the game you want to install the save for, click "Open User Save Directory" and put the save file(s) there.

**Backing up your save files**
If you ever need to reinstall Ryujinx, back up your saves folder by going to `%AppData%\Ryujinx\bis\user\save` and backing up that folder. Replace `%AppData%\Ryujinx` with your portable folder if using portable mode.
* * * 

## Section 6: Misc

### Fixes for errors or other issues

**BKTR Error:** You get this error when launching an update, instead of the actual game.

**Video Core Error:** Vulkan drivers are out of date.
- If you use a Nvidia GPU, install the file from https://developer.nvidia.com/vulkan-beta-45836-windows-10-dch
- For AMD GPU users, just update to latest ***optional*** drivers in the AMD Software Panel.
- If this occurs on Steam Deck, something could be very wrong with your setup. You would likely need more support than what can be offered here. 

**"NCA Header key could not be found" error:** Keys are outdated

**Crypto revision error:** Keys are outdated. Again.

**Updates or DLC failing to install:** Keys are outdated... ***Again***

**Games not appearing in your game list**
- You placed the game in a folder *inside* your game folder. Place *just* the game file.
- You placed a game update instead of the game inside the game folder. Check this by looking at the file name. You will see either [v0] or [v357534]. [v0] is *always* the game. If the number is different, it's an update.
- Your game may be in a rar/zip/7z arcive. Be sure that the game is extracted and has an xci or nsp extension.
- Your game may be in a rar/zip/7z archive. Be sure that the game is extracted and has an xci or nsp extension.
- The game is corrupt. This usually means it must be redownloaded.
