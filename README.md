# BuddySystem

Compatibility bridge between [Nitrox](https://nitrox.rux.gg/) (Subnautica multiplayer) and [SubmersedVR](https://github.com/Okabintaro/SubmersedVR) so the two finally coexist — play Subnautica multiplayer in VR.

Ships as the `NitroxVrCompat` BepInEx plugin, plus a basic diver body + contextual animations bundle.

By Connor and Zach — Geeks and Me LLC.

## Download

Grab the latest release from the [Releases page](https://github.com/TheGeeks0424/BuddySystem/releases).

## Prerequisites

Install these first; this mod does not bundle them.

- **Subnautica** (tested against build 1.22.83031)
- **BepInEx 5** at the game root
- **Nitrox 1.8.1** (via Nitrox.Launcher)
- **SubmersedVR 0.2.0** (`BepInEx/plugins/SubmersedVR.dll`)

## Install

Extract the release zip into your Subnautica install root — the folder that contains `Subnautica.exe`. The directory tree inside the zip mirrors the game's, so the files land in the right places:

- `BepInEx/plugins/NitroxVrCompat/NitroxVrCompat.dll`
- `BepInEx/plugins/NitroxVrCompat/NitroxVrCompat.pdb`
- `BepInEx/plugins/NitroxVrCompat/playeravatar`
- `Subnautica_Data/Managed/Valve.Newtonsoft.Json.dll`

## Usage

Launch via Nitrox.Launcher with your VR headset connected. Press **F11** in-game to dump a diagnostic snapshot to `BepInEx/LogOutput.log`. The hotkey is configurable in `BepInEx/config/com.csore.nitroxvrcompat.cfg`, which is auto-generated on first run.
