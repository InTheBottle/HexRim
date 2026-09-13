# HexRim
A true Skyrim remaster with deeper systems and mechanics.

![HexRim](Resources/HexRim.png)

**Links**: [Changelog](changelog.md) | [Discord](https://discord.gg/WYjj6EvdJ)

---

**Support**: Join the [HexRim Discord](https://discord.gg/WYjj6EvdJ)

**Requirements**:
- Skyrim version 1.6.1170 (latest Steam update).
- Skyrim AE with all Anniversary Edition content (paid Creation Club content).

---

## Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Playing the Game](#playing-the-game)
- [Updating](#updating)
- [Uninstalling](#uninstalling)
- [Troubleshooting](#troubleshooting)
- [Credits](#credits)

---

## Introduction
**HexRim** is a modlist that aims to be a true Skyrim remaster. It keeps the game you know and rebuilds it with deeper systems and mechanics.

Licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/).

---

## Installation

### Pre-Installation
1. **Install Dependencies**:
   - [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe). If it's already installed, use the `Repair` option.
   - [.NET Runtime 8.x.x Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.15-windows-x64-installer).
   - [.NET Runtime 6.0.0 Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer).

2. **Steam Setup**:
   - Disable [auto-updates for Skyrim AE](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
   - Run Skyrim through Steam once so it detects your graphics settings and downloads ALL Creation Club add-ons. Don't Alt-Tab during this process.
   - If Creation Club plugins are missing, do a clean install of Skyrim: uninstall it and delete the Skyrim Steam folder completely.

3. **Pagefile**:
   Large modlists use a lot of memory, and running out causes crashes. Setting up a pagefile is highly recommended.
   - Press Win + R, type `sysdm.cpl ,3` and press Enter.
   - Under Performance, click Settings, then open the Advanced tab.
   - Under Virtual Memory, click Change and uncheck "Automatically manage".
   - Select your fastest SSD, choose Custom size and set both Initial and Maximum size to `40960` MB.
   - Click Set, then OK, then restart your PC.

### Wabbajack Installation
1. **Install Wabbajack**:
   - Create a folder (e.g., `C:\Wabbajack`) at the root of a drive (not in Program Files, Desktop, etc.).
   - Download [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe) and place it in the folder.
   - Run `Wabbajack.exe` (requires version 4.0.0.0 or later).

2. **Install HexRim**:
   - Open Wabbajack, select Skyrim AE, find HexRim and click "Download and Install".
   - Set an Installation Location (e.g., `C:\HexRim`) and a Downloads Location (avoid Program Files, Desktop, etc.).
   - Click Install.
   - Nexus Premium automates downloads; without it, click "Slow Download" for each mod manually.
   - If something goes wrong, check [Troubleshooting](#troubleshooting).

### Antivirus Exceptions
- Add exceptions in Windows Defender for the HexRim folder and `ModOrganizer.exe` to avoid crashes.
- Windows Security > Virus & Threat Protection > Manage Settings > Exclusions > Add Folder > select the HexRim folder.

---

## Playing the Game
- Launch Skyrim through Mod Organizer 2 (MO2) in your HexRim folder.

---

## Updating
1. Open Wabbajack, find HexRim and click "Download and Install".
2. Use the same Installation and Downloads folders.
3. Back up any custom mods or settings first (prefix mods you added with **[NoDelete]** in MO2).
4. Check the [Changelog](changelog.md) to see whether an update is save-safe.

---

## Uninstalling
- Delete the HexRim folder.

---

## Troubleshooting
- **Installation Issues**:
  - Missing files? Download them manually and place them in the Downloads folder.
  - Game folder not found? Make sure Skyrim is installed and follow [Pre-Installation](#pre-installation).
  - Antivirus flagging files? Add exceptions or uninstall aggressive third-party antivirus (e.g., Norton).

- **Post-Installation Issues**:
  - Form 43/DLL errors? Reinstall with "Overwrite Installation" checked in Wabbajack.
  - Crashing on startup? Reinstall, or ask for help on [Discord](https://discord.gg/WYjj6EvdJ) with your crash logs.

---

## Credits
- [ElminsterAU](https://www.patreon.com/ElminsterAU) & the xEdit team for SSEEdit.
- [Noggog](https://www.nexusmods.com/skyrim/users/862590) for Mutagen and Synthesis.
- [Halgari](https://www.nexusmods.com/skyrimspecialedition/users/17252164) & the Wabbajack team.
- [Althro](https://github.com/Althro) and [Styyx](https://github.com/Styyx1) for ADT.
- [Bingus](https://github.com/bingusthecatto) for Anvil's readme, which this one is based on.
- [Sheson](https://ko-fi.com/sheson) for DynDOLOD.
- All mod authors and the Skyrim modding community.
