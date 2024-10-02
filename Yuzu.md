# Yuzu Guide (DISCONTINUED)

***The guide will be split into several sections. You can use the Table of Contents to easily get to the section you need to be at.***

***If you still have a problem after following this guide and want help, please join our discord server and ask there. It is easier to help there, as we have more resources and people available. You can join the*** [***server by clicking here***](https://discord.gg/87bsZWwF3X)

# Notice
As of March 5, 2024 the **Yuzu emulator has been shut down** due to a lawsuit filed against them by Nintendo. This guide will remain up, but the emulator will not be updated anymore. Do not expect to play games released after this date to always run flawlessly.
### As an alternative to Yuzu, we recommend you check out [Ryujinx](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Ryujinx.md)

# Download Instructions (IMPORTANT!!!) 

All the links in this guide are encoded in base64. Whenever you come across a link, copy that link and go to https://www.base64decode.org, then paste that link in the top box and click "Decode". The bottom box will contain your link

Most if not all the stuff you download will be in a compressed format (i.e. .7z, .zip or .rar). You need to extract them with either [7zip](https://www.7-zip.org) or [WinRAR](https://www.win-rar.com/download.html?&L=0)

If you just want the downloads you can get them from [here](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Links.md)

* * *

### Table of Contents

- [Section 1: Installing the Emulator](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#section-1-installing-the-emulator)
- [Section 2: Installing Keys and Firmware](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#section-2-installing-keys-and-firmware)
   + [Keys](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#keys)
   + [Firmware](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#firmware)
- [Section 3: Installing Games, Updates and DLC](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#section-3-installing-games-updates-and-dlc)
   + [Loading Games into Yuzu](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#loading-games-into-yuzu)
   + [Loading Updates and DLCs](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#loading-updates-and-dlcs)
- [Section 4: Optimizations for best performance](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#section-4-optimizations-for-best-performance)
   + [Settings for all GPUs](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#settings-for-all-gpus)
   + [Nvidia GPU settings](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#nvidia-gpu-settings)
   + [AMD GPU settings](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#amd-gpu-settings)
   + [Intel GPU settings](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#intel-gpu-settings)
- [Section 5: Installing Mods, Saves and Shaders](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#section-5-installing-mods-saves-and-shaders)
   + [Mods](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#mods)
   + [Shaders](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#shaders)
   + [Saves](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#saves)
- [Section 6: Misc](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#section-6-misc)
   + [Fixes for errors](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#fixes-for-errors)
   + [Yuzu Compatibility List](https://github.com/Abd-007/Switch-Emulators-Guide/blob/main/Yuzu.md#yuzu-compabitiblity-list)

* * * 

## Section 1: Installing the Emulator

### Universal

Unavailable.

### Linux/Steam Deck

On all major distributions (including Steam Deck), Yuzu is available in two forms:

As an AppImage in Early Access form (recommended): https://github.com/pineappleEA/pineapple-src/releases 

As a Flatpak available on Flathub (AKA Discover app on Steam Deck/KDE) (Not recommended as more unstable) 


For **Arch Linux only**, Yuzu is available as a binary in the Arch User Repository.

`yay -S yuzu-mainline-bin`


* * *

## Section 2: Installing Keys and Firmware

### Keys

When you launch Yuzu for the first time, an error for missing components will pop up. To fix that, you need the prod.keys.

**Keys:** Unavailable.

**Note:** Older keys are included. Download only the latest, and extract the archive using 7zip or WinRAR. If what you download also contains title.keys, delete it. It is not needed.

After downloading the keys, Open Yuzu, go to the top left corner and click on "File" and then "Open Yuzu folder". Open the keys folder and put (only) the prod.keys file in that folder.

Restart Yuzu and you shouldn't get the error anymore. If you still do, you messed up. Repeat the previous steps.

### Firmware

Downloading firmware for Yuzu is not a requirement. However, there are three or four games that crash at the main menu without it. It is advised to download firmware regardless.

**Firmware:** Unavailable.

Open Yuzu, go to the Yuzu folder like you did for keys, then navigate to "nand\system\Contents\registered" and paste all the firmware files in there.

Once you have keys and firmware installed, you're done with this step.

* * *

## Section 3: Installing games, updates and DLC

Now on to installing games. Here is a list of trusted websites to get switch games, updates and DLC from.

`aHR0cHM6Ly9ueGJyZXcuY29tLwoKaHR0cHM6Ly9uc3cydS54eXovIChodHRwczovL25zdzJ1LmNvbS8pCgpodHRwczovL25zd2dhbWUuY29tL2NhdGVnb3J5L3N3aXRjaC8KCmh0dHBzOi8vd3d3LnppcGVydG8uY29tL25pbnRlbmRvLXN3aXRjaC1uc3AvCgpodHRwczovL3N3aXRjaGVkdHdvLnRvLw==`

**Note:** It is recommended to get an adblocker before visiting any of these websites. You can get one at https://ublockorigin.com/ 

**Note:** It is also recommended to get an extension to bypass URL shortner sites. The recommended one can be found at https://fastforward.team/

**Note:** When downloading, you might be presented with three file types. NSP, XCI, and NSZ. Yuzu and Ryujinx **do not** support NSZ, so don't download that. XCI has the update file merged into the game file so you need to download only one file. NSP has different game and update files, making it easier to update. Get whichever you like

### Loading games into Yuzu

Once you download a game, place it into a folder where you wish to keep all your Switch games (**place only the game file and not the update or DLC file**).

Open Yuzu and double click the middle of the window (or double click "Add New Directory" if that shows up). You will be prompted to select a folder. Select the folder where you placed your game file(s). The game should now show up in the Yuzu list and you can launch it by double clicking. Before that, let's go through the other steps.

### Loading Updates and DLCs

Open Yuzu. go to the top left corner and click on "File" and "Install Files to NAND". Then choose the Update/DLC files you want to install. Wait for installation to finish.

**Note:** Installing to NAND creates an extra copy of the installed content to your C drive, so you can delete your original update and/or DLC files after installing them.

**Note:** To check if the update or DLC has been succesfully installed, right click the game you installed the Update/DLC for, select "Properties" and the Update/DLC should show up.

You're done here. Next step.

* * *

## Section 4: Optimizations for best performance

Now to make optimizations to get the best performance on Yuzu. Some settings need to be changed inside Yuzu, some outside. For Yuzu settings, click on "Emulation" at the top of the window, then "Configure". This section will be divided based on which GPU you have

**Note:** If you don't know what GPU you have, open the start menu and search for Task Manager. Then go to the performance tab at the top and look for 'GPU' on the left hand side to know what GPU you have

### Settings for all GPUs

-  GPU Accuracy should be kept on normal. Use high when attempting to fix visual bugs. It should not be kept on if not needed, because it can lower performance in some cases. Avoid Extreme. To change GPU Accuracy, open Yuzu settings, click the "Graphics" tab on the left, then "Advanced" on the top and configure the GPU Accuracy as you like.
-  Set CPU accuracy to "Auto". The Unsafe setting can break things, and is only to be used in specific circumstances. Go to Yuzu settings, "CPU" on the left pane and set Accuracy to Auto
-  Change the pagefile to 10000MB or 20000MB. Video tutorial [here](https://www.youtube.com/watch?v=wAMT9LWtvUs).
-  Install the latest drivers for your GPU
-  You don't need to change anything in the General, System, and Audio tabs in Yuzu settings. Configure your controls in the Controllers tab

### Nvidia GPU settings

- Open Yuzu settings. Go to the "Graphics" tab on the left and make sure the API is set to "Vulkan". Also make sure it selects your dedicated/preferred GPU in the Devices option.
- OpenGL should only be used if a specific game is broken or has issues on Vulkan
- If using OpenGL, set Shader Backend to "GLASM" for faster shader building. Once the shaders are built, set it back to "GLSL"

- Right click on your desktop and open the NVIDIA Control Panel. Once it opens, click on "Manage 3D Settings" on the right. Once it opens, go to "Program Settings" and click "Add". Select Yuzu, then scroll down the list of settings and set the following:
   + Vertical Sync - Off
   + Threaded Optimization - On
   + Power Management Mode - Prefer Maximum Performance
   + OpenGL rendering GPU - [Select your GPU]
   + Then click Apply on the lower right corner.
- Smash players may want to enable Low Latency in the Nvidia Control Panel

### AMD GPU settings

- Open Yuzu settings. Go to "Graphics" tab on the left and make sure the API is set to "Vulkan". Also make sure it selects your dedicated/preferred GPU in the Devices option.
- Add Yuzu as a profile on Radeon Software, this will add a driver level cache to Vulkan
- Smash players may want to enable Anti-Lag in Radeon Software

### Intel GPU settings

- Open Yuzu settings. Go to the "Graphics" tab on the left and make sure the API is set to "Vulkan". Also make sure it selects your dedicated/preferred GPU in the Devices option

**CPU Accuracy tips (regardless of what GPU you have)**
Setting CPU Accuracy to "Unsafe CPU" can cause certain bugs or crashes in games, although there have also been cases where the opposite was true. 

If your AMD CPU released in or after 2012, or your Intel CPU released in or after 2014 Uncheck the "Unfuse FMA" option that appears when you use the Unsafe CPU setting.

Note: This only affects CPUs without FMA and can be enabled for improved performance, but should be disabled if any bugs or instability are encountered

**Note:** You can pretty much just start playing now, as all required steps are complete. The next sections are optional i.e. installing saves, mods, shaders and some fixes for errors.

* * * 

## Section 5: Installing Mods, Saves and Shaders

### Mods

You can get some Switch mods from the following sources:

**Our Collection:** https://drive.google.com/drive/folders/1dY20qH3phqoUfmAEdngTzrtMIvPFwSG4?usp=sharing

**TheBoy181's GitHub:** https://github.com/theboy181/switch-ptchtxt-mods

**Official Yuzu mods page:** https://github.com/yuzu-emu/yuzu/wiki/Switch-Mods

To install mods, right click the game you want to install the mod for, click "Open Mod Data Location" and paste the mod folder there. You must place the mod ***folder*** you downloaded, and not just the files inside of it.

### Shaders

We do not provide shader caches anymore due to emulator updates constantly breaking the shader caches. You should build your own shader caches using Vulkan.

To install shaders:

- Start the game you want the shaders for. Close it once you see the first screen that pops up. Then right click the game in Yuzu, click "Open Transferable Pipeline Cache" and place the shaders in the folder that opens.

### Saves 

You can find saves here:

**Our collection:** https://drive.google.com/drive/folders/1G2gHYZn7Dbx_X9iYUgpOfCBiWCixBTWU?usp=sharing

**Alternative:** https://www.homebrewgeneral.net/2020/03/switch-games-save.html

To install saves:

- Right click the game you want to install the save for, click "Open Save Data Location" and put the save file(s) there.

**Backing up your save files**
If you ever need to reinstall Yuzu, back up the files or folders below so you don't lose game progress.

- The file below stores the user profile of the Switch. Some game saves need this to work:
`%AppData%\yuzu\nand\system\save\8000000000000010\su\avators\profiles.dat`
- The folder below contains saves for all games:
`%AppData%\yuzu\nand\user\save\0000000000000000`

* * * 

## Section 6: Misc

### Fixes for errors or other issues

**BKTR Error:** You get this error when launching an update, instead of the actual game.

**Video Core Error:** Vulkan drivers are out of date.
- If you use a Nvidia GPU, install the file from https://developer.nvidia.com/vulkan-beta-45836-windows-10-dch
- For AMD GPU users, just update to latest ***optional*** drivers in the AMD Software Panel.

**"NCA Header key could not be found" error:** Keys are outdated

**Crypto revision error:** Keys are outdated. Again.

**Updates or DLC failing to install:** Keys are outdated... ***Again***

**Games not appearing in your game list**
- You placed the game in a folder *inside* your game folder. Place *just* the game file, or enable sub-folder scanning in Yuzu.
- You placed a game update instead of the game inside the game folder. Check this by looking at the file name. You will see either [v0] or [v357534]. [v0] is *always* the game. If the number is different, it's an update.
- Your game may be in a rar/zip/7z archive. Be sure that the game is extracted and has an xci or nsp extension.
- The game is corrupt. This usually means it must be redownloaded.

### Yuzu Compabitiblity List

Since the official Yuzu compatibility list absolutely sucks and is rarely updated, here's an actual working compatibility list!

**Link**: https://docs.google.com/spreadsheets/d/1pHPpnYmtdfS2c8KZuoMj8TYJrwfp2Yukwy3LlI2K8Ro/

**Note**: While the above list is better than Yuzu's official one, it is not 100% correct. As such if you notice any inaccuracies, feel free to contact ⛧GΩD⛧#5957 on discord to suggest any improvements or feedback.

