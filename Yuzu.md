# Yuzu Guide (Not Finished Yet)

***The guide will be split into several sections, you can use the Table of Contents to easily get to the section you need to***

***If you still get a problem after following this guide and want help, please join our discord server and ask there, as it is easier to help in discord. You can join the*** [***discord by clicking here***](https://discord.gg/NF38g3ENVc)

***Important Note: You need https://www.base64decode.org to decode some of the links that look like a string of letters and numbers. Copy the string and paste it into the base64 decoder and press decode to get real link. I will not be repeating this everywhere***

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

* * * 

## Section 1: Installing the Emulator

(Optional) Go to https://yuzu-emu.org/downloads/ to download the latest mainline build. 

Get an Early Access build. Those generally work better than mainline and are more updated. You can get Early Access builds from our handy auto-updater or download them manually, if you want

**Auto Updater:** https://mostlywhat.github.io/128Bit-Yuzu-Installer/

**Github Source (for downloading manually):** https://github.com/Kryptuq/Yuzu-Early-Access-files/releases

**Note:** If you get the "msvcp140_atomic_wait.dll is missing" error when launching Yuzu from here, install this https://aka.ms/vs/16/release/vc_redist.x64.exe

Once you get either mainline or early access, just open yuzu, and you are done with this step.

## Section 2: Installing Keys and Firmware

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

## Section 3: Installing Games, Updates and DLC

Now on to installing games. Here is a list of trusted websites to get switch games, updates and DLCs from

**List of Websites to get switch games from:** `aHR0cHM6Ly9ueGJyZXcuY29tLwoKaHR0cHM6Ly9uc3cydS54eXovCgpodHRwczovL25zd2dhbWUuY29tL2NhdGVnb3J5L3N3aXRjaC8KCmh0dHBzOi8vd3d3LnppcGVydG8uY29tL25pbnRlbmRvLXN3aXRjaC1uc3Av`

**Note:** It is recommended to get an adblocker before visiting any of these websites. You can get one at https://ublockorigin.com/ 

**Note:** When downloading, you might be presented with 3 file types. NSP, XCI and NSZ. Yuzu and Ryujinx do not support NSZ, so don't download that. XCI has the update file merged into the game file so you need to download only one file. NSP has different game and update files, making it easier to update. Get whichever you like

### Loading Games into Yuzu

Once you download a switch game, place it into a folder (**Place only the game file and not the update or DLC file, and no folder either**)(Use this folder for all your switch games)

Open yuzu and double click on the middle of yuzu (or double click "Add New Directory" if that shows up). You will be prompted to select a folder. Select the folder where you placed your game file. The game should now show up in the yuzu list and you can load it by double clicking, but first let's go through the other steps

### Loading Updates and DLCs

Open yuzu. go to the top left corner and click on "File" and "Install Files to NAND". Then choose the Update/DLC files you want to install. It will start installing the Update and/or DLCs

**Note:** You can delete your Update and/or DLC files after installing them to NAND

**Note:** To check if the update or DLC has been succesfully installed, right click the game you installed the Update/DLC for, select "Properties" and the Update/DLC should show up. If it doesn't, you did something wrong.

Once you download your game and/or Updates/DLCs, you're finished with this step

## Section 4: Optimizations for best performance

Now to make optimizations to get the best performance on yuzu. Some settins need to be changed inside yuzu, some outside. For yuzu settings, click on "Emulation" on the top and then "Configure". I will be dividing this section based on which GPU you have

### Settings for all GPUs

-  Test GPU Accuracy per game, it can be changed while playing. Some benefit from High, some from Normal, avoid Extreme for now. To change GPU Accuracy, go to yuzu setting, click on "Graphics" on the left, then "Advanced" on the top and configure the GPU Accuracy as you like.
-  Set CPU accuracy to Auto. Unsafe is not faster and will break things. Go to yuzu settings, "CPU" on the left and set Accuracy to Auto
-  Change the pagefile to 10000-20000MB. Video tutorial to do that: https://www.youtube.com/watch?v=wAMT9LWtvUs
-  Install the latest GPU drivers for your GPU
-  You don't need to change anything in the "General", "System", "CPU" and "Audio" tabs in yuzu settings. Configure your controller in the "Controllers" tab

### Nvidia GPU settings

- Open yuzu settings. Go to "Graphics" tab on the left and set the API to "Vulkan" (Make sure it selects your dedicated/preferred GPU in the "Devices" option)
- If needed for better performance or rendering, set API to OpenGL.
- If using OpenGL, set Shader Backend to "GLASM" for faster shader building. Once the shaders are built, set shader backend to "GLSL"
- 
- Right click on your desktop and click "NVIDIA Control Panel". Once it opens, click on "Manage 3D Settings" on the right. Once it opens, go to "Program Settings" and click Add and select Yuzu. Then scroll down the list of settings and set the following settings like this:
Vertical Sync - Off
Threaded Optimization - On
Power Management Mode - Prefer Maximum Performance
OpenGL rendering GPU - [Select your GPU]
Then click Apply on the lower right corner.
- Smash players may want to enable Low Latency in the Nvidia Control Panel

### AMD GPU settings

- Open yuzu settings. Go to "Graphics" tab on the left and set the API to "Vulkan" (Make sure it selects your dedicated/preferred GPU in the "Devices" option)
- Add yuzu as a profile on Radeon Software, this will add a driver level cache to Vulkan
- Smash players may want to enable Anti-Lag in Radeon Software

### Intel GPU settings

- Open yuzu settings. Go to "Graphics" tab on the left and set the API to "Vulkan" (Make sure it selects your dedicated/preferred GPU in the "Devices" option)

That's pretty much it for optimizations for the best performance. Once you follow all the steps, you're done with this section

**Note:** You can pretty much just start playing now. The next sections are optional i.e. installing saves, mods, shaders and some fixes for errors.

## Section 5: Installing Mods, Saves and Shaders

### Mods

You can get some switch mods from the following sources:

**Our Collection:** https://drive.google.com/drive/folders/1dY20qH3phqoUfmAEdngTzrtMIvPFwSG4?usp=sharing

**TheBoy181's GitHub:** https://github.com/theboy181/switch-ptchtxt-mods

**Official Yuzu mods page:** https://github.com/yuzu-emu/yuzu/wiki/Switch-Mods

To install mods

- Right click the game you want to install the mod for, click "Open Mod Data Location" and paste the mod folder there. **You must place the mod ***folder*** and not just the files in the Mod Data Location**

### Shaders

You can find some shaders from our shader github

**Shaders:** https://github.com/JENOVAAbsolute/128BB-Shaders

To install shaders:

- Start the game you want the shaders for. Close it once you see the first screen that pops up. Then right click the game in yuzu, click "Open Transferable Pipeline Cache" and place the shaders in the folder you got

## Saves 

You can find some saves from here:

**Saves:** https://drive.google.com/drive/folders/1G2gHYZn7Dbx_X9iYUgpOfCBiWCixBTWU?usp=sharing

**Alternative:** https://www.homebrewgeneral.net/2020/03/switch-games-save.html

To install saves

- Right click the game you want to install the save for, click "Open Save Data Location" and put the save files there.
