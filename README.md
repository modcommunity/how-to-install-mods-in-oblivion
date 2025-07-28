<div align="center">

![banner|800x300](./images/banner.png)

</div>

A guide on how to **install mods** in **The Elder Scrolls IV: Oblivion** on PC. 

Additionally, we've included instructions on how to use mod managers like [Wrye Bash](https://github.com/wrye-bash/wrye-bash), [Vortex](https://www.nexusmods.com/about/vortex), and trusted mod websites like [Nexus Mods](https://www.nexusmods.com/oblivion).

This guide is focused on **Windows users**, but some concepts can be adapted for Linux with tools like Steam Proton or [Wine](https://www.winehq.org/).

Oblivion is still one of the most moddable games in the Elder Scrolls series. Whether you want to overhaul the visuals, enhance combat, fix bugs, or add entirely new content, this guide will help you get started!

## Table Of Contents
* [Requirements](#requirements)
* [Game Version Notes](#game-version-notes)
    * [Steam Version](#steam-version)
    * [GOG Version](#gog-version)
    * [Retail Disc Version](#retail-disc-version)
* [Backup Your Game Files!](#backup-your-game-files)
* [Choosing A Mod Manager](#choosing-a-mod-manager)
    * [Wrye Bash](#wrye-bash)
    * [Vortex](#vortex)
* [Where To Download Mods](#where-to-download-mods)
* [Downloading & Installing Mods](#downloading--installing-mods)
    * [Using Wrye Bash](#using-wrye-bash)
    * [Using Vortex](#using-vortex)
    * [Manual Mod Installation (Advanced)](#manual-mod-installation-advanced)
* [LOOT - Load Order Optimization Tool](#loot---load-order-optimization-tool)
* [Script Extenders (OBSE)](#script-extenders-obse)
* [Conclusion](#conclusion)
* [See Also](#see-also)

## Requirements
* Oblivion (Steam, GOG, or retail copy)
* [7-Zip](https://www.7-zip.org/) or similar archive tool (for manual nod installations)
* Basic knowledge of copying/moving files on Windows

## Game Version Notes
Here are some notes regarding the game version you're using and platform you're playing on.

### Steam Version
* Works well with most mods.
* OBSE and mod managers support this version.

### GOG Version
* Fully patched and includes official DLCs.
* OBSE support is **partial**; generally requires a specific build.
* Recommended for modding thanks to DRM-free installation.

### Retail Disc Version
* May require manual patching.
* Some modern tools may not support it properly.

**TIP** - We recommend running and patching Oblivion on version **v1.2.0416** at least before modding. GOG includes this by default. Steam is usually up-to-date.

## Backup Your Game Files!
Before you start modding, we recommend **backing up** your game files and saves!

Here are common game install folder path(s).

* **Steam**: `C:\Program Files (x86)\Steam\steamapps\common\Oblivion`

Here is the common saves folder path.

```
C:\Users\<user>\Documents\My Games\Oblivion\Saves
```

This gives you a fallback in the case a mod causes your game to crash or potentially corrupts your game installation!

**WARNING** - Remember the folder locations above as you may need them later on in the guide!

## Choosing A Mod Manager
There are two primary mod managers used for Oblivion, [Wrye Bash](https://github.com/wrye-bash/wrye-bash) and [Vortex](https://www.nexusmods.com/about/vortex).

Here are basic summaries of both!

### [Wrye Bash](https://github.com/wrye-bash/wrye-bash)
* Created for Oblivion.
* Handles mod installations and load order.
* Includes Bashed Patch to resolve mod conflicts.

1. Download this mod manager from [here](https://github.com/wrye-bash/wrye-bash/releases/).
2. Run the installer and if you have issues, please refer to the install guide [here](https://github.com/wrye-bash/wrye-bash?tab=readme-ov-file#installation)!

### [Vortex](https://www.nexusmods.com/about/vortex)
* Developed by Nexus Mods and supports a wide range of games, including Oblivion.
* Easier to use for beginners with a **modern UI** and one-click mod installs.
* Keeps your game folder clean using a staging folder and **symlinks**.
* Integrates directly with [Nexus Mods](https://www.nexusmods.com/oblivion) for mod downloads.

To download and install Vortex, please follow the below steps.

1. Download Vortex from [here](https://www.nexusmods.com/site/mods/1?tab=files).
    * Unless if you're a premium user, you will need to choose the **slow download** option.
2. Run the installer.
    * **Windows**: Ensure you have [.NET Desktop Runtime 6](https://aka.ms/dotnet/6.0/windowsdesktop-runtime-win-x64.exe) installed!
    * Vortex may prompt and guide you on fixing issues.
3. Now go to the **Games**  tab.
4. Either find Oblivion from the **Unmanaged** list of games or search for it in the search box at the top.
5. Click the **Manage** button located in the middle of the Oblivion game card.
6. This will attempt to add support for the game.
    * If Vortex has issues finding the game's location, follow the below steps:
        1. Go to the **Games** tab through Vortex.
        2. Find the game card under the **Managed** list.
        3. Click the **three dots** button located to the top-right of the card.
        4. Click **Manually Set Location**.
        5. Select the location of your game install.
    * Ensure you see the game's section in the left sidebar. If not, click the **Activate** button under the game card.

Vortex should now be configured and installed for modding Oblivion!

**WARNING** - Vortex does not support building a Bashed Patch directly. If you plan on using many mods that alter gameplay, you may want to **use Wrye Bash alongside Vortex** for load order and conflict resolution.

**NOTE** - You can also use [OBMM (Oblivion Mod Manager)](https://www.nexusmods.com/oblivion/mods/2097), but it's not as popular and seems to be a bit outdated.

## Where To Download Mods
Here are websites popular for hosting Oblivion mods!

* [Nexus Mods - Oblivion](https://www.nexusmods.com/oblivion)
* [AFK Mods](https://www.afkmods.com/index.php?/files/category/65-oblivion/)
* [ModDB - Oblivion](https://www.moddb.com/games/oblivion)
* [LoversLab](https://www.loverslab.com/files/category/4-oblivion/) (**contains NSFW/adult mods!**)

**NOTE** - Remember to read mod descriptions along with user comments to make sure the mod is safe and to ensure you aren't missing any dependencies and such!

## Downloading & Installing Mods
Here are steps on how to download and install mods from the sources listed above using whatever mod manager you've chosen.

### Using Wrye Bash
1. Drag and drop mod archives into the "Installers" tab.
2. Right-click the mod and select **Install**.
3. Go to the "Mods" tab to activate the `.esp` or `.esm` file.

### Using Vortex
1. Ensure you're logged into your Nexus Mods account through Vortex.
    * You can click the **Login** button at the top-right of the application if not.
3. Go to the mod's page you want to install on Nexus Mods' website.
4. If Vortex is supported, you'll see a **Vortex** button next to the **Manual** button on the right side. Click this button.
    * If you don't see a Vortex button, it means the mod is **not supported** through Vortex and you'll need to **manually install** the mod (instructions included below).
5. Choose what download type you want (e.g., slow download).
6. The file should open in Vortex automatically and start downloading.
    * Go to the **Downloads** tab through Vortex to check the progress!
7. The mod should be automatically installed.
    * You can go to the **Mods** tab under the Oblivion section in the left sidebar to confirm if the mod is loaded.
    * You can remove mods by clicking the **Remove** button located on the right side of the mod item.

### Manual Mod Installation (Advanced)
Some users prefer manually installing mods or have issues with mod managers. In any case, you may perform the following general steps to download and install mods manually!

1. Download the mod manually through whatever website you're using (typically there is a manual download button or a list of file names).
2. Extract it with [7-Zip](https://www.7-zip.org/) or a similar tool.
3. Copy file contents from the mod to the game install folder's `Data` sub-folder (`Oblivion\Data`).
   * Plugins will have the `.esp` or `.esm` file extensions.
   * Other files may include `Meshes`, `Textures`, `Sound`, etc.
4. Launch the Oblivion Launcher and head to Data Files → Enable the mod.

Please make sure to read the mod's description on the website and make sure there aren't steps or dependencies you're missing!

## LOOT - Load Order Optimization Tool
Some mods depend on a specific load order. If you're running into this issue, you can use [LOOT](https://loot.github.io/) to auto-sort your plugins!

1. Download LOOT from [here](https://loot.github.io/) and run it.
2. Set the game to **Oblivion**.
3. Click **Sort Plugins**.
4. Review changes and apply.

LOOT helps fix game crashes, missing textures, and broken quests due to bad plugin order.

## Script Extenders (OBSE)
Some mods require the [Oblivion Script Extender](https://obse.silverlock.org/) (OBSE) to function.

1. Go to [obse.silverlock.org](http://obse.silverlock.org/).
2. Download the version that matches your game (Steam, GOG, or retail).
3. Extract and copy these files into your Oblivion's game install folder:
   * `obse_1_2_416.dll` file
   * `obse_editor_1_2.dll` file
   * `obse_loader.exe` file
   * `Data/` folder
4. Always run the game using the `obse_loader.exe` executable you copied to your Oblivion install folder.

If you have issues, refer to the `obse_readme.txt` file inside of the downloaded OBSE archive.

## Conclusion
That's it! By now you should have a basic understanding of how to download and install mods in Oblivion along with experience with mod managers like Wrye Bash and Vortex!

Modding Oblivion takes a bit of setup, but the results are absolutely worth it!

## See Also
* [Nexus Mods - Oblivion](https://www.nexusmods.com/oblivion)
* [Wrye Bash GitHub](https://github.com/wrye-bash/wrye-bash)
* [Vortex](https://www.nexusmods.com/about/vortex)
* [LOOT](https://loot.github.io/)
* [OBSE](http://obse.silverlock.org/)
* [Oblivion Subreddit](https://www.reddit.com/r/oblivion/)
* [r/OblivionMods](https://www.reddit.com/r/OblivionMods/)

This guide will be updated and improved on over time. If you see any improvements that can be made, please feel free to reach out!