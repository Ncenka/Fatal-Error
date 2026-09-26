# Fatal Error

> A gameplay and immersion overhaul for PDAs and electronic devices in S.T.A.L.K.E.R. Anomaly.

[![Version](https://img.shields.io/badge/version-1.7.9.5-blue)](https://www.moddb.com/mods/stalker-anomaly/addons/fatal-error-by-ncenka) [![Game](https://img.shields.io/badge/game-S.T.A.L.K.E.R.%20Anomaly-orange)](https://www.moddb.com/games/stalker-anomaly)

Fatal Error turns the PDA from a reliable universal tool into a real piece of Zone electronics: it can fail, degrade, consume batteries, require maintenance, enter recovery states and expose additional functionality through BIOS. The addon also adds new PDA tiers, device upgrades, custom glitches and an optional storyline.

## Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Compatibility](#compatibility)
- [Installation](#installation)
- [FOMOD options](#fomod-options)
- [Features](#features)
- [Configuration](#configuration)
- [Storyline](#storyline)
- [Integrations](#integrations)
- [Troubleshooting](#troubleshooting)
- [Modpack guidance](#modpack-guidance)
- [Credits](#credits)
- [Links](#links)
- [Changelog](#changelog)

## Overview

Ever felt that the PDA is too useful and too reliable?

Fatal Error was built around a simple idea: the Zone should be able to punish you for relying on your electronics. PDAs and other devices are treated as actual equipment that can lose functionality, develop faults, drain batteries, react to environmental hazards and require decisions about repairs and upgrades.

## Requirements

- **S.T.A.L.K.E.R. Anomaly**
- **STALKER-Anomaly-modded-exes 2025.08.23 or newer**
- **MCM (Anomaly Mod Configuration Menu)**

After installation, **clear the shader cache from the Anomaly launcher**.

> The current repository/FOMOD version is **1.7.9.5**.

## Compatibility

### Known incompatible or problematic setups

- **2D PDA Mode**
- **PDA Reanimation / PDA Reposition addons** — use the dedicated Fatal Error adaptation if applicable.
- **Warfare Mode** — listed by the project as probably incompatible.

Fatal Error changes PDA UI, behaviour and device handling at a fairly deep level. Avoid stacking other addons that replace the same systems unless a compatibility patch is provided.

## Installation

1. Install the required dependencies.
2. Install Fatal Error with your preferred mod manager.
3. Select only the FOMOD components that match your setup.
4. Clear the shader cache in the Anomaly launcher.
5. Open MCM and review Fatal Error settings.
6. If you use a large modpack, check the compatibility and patch sections before enabling extra components.

> Back up your save before changing major Fatal Error settings on an existing playthrough.

## FOMOD options

### Main

- **FE - Main** — core scripts and configuration.

### Optional content

- **New PDA 3D Models** — new PDA models by DAR213 and Gunslinger developers.
- **Trilogy Anomaly Detector Sound** — alternate detector sound.
- **Storyline** — optional Fatal Error quest line.
- **PDA Reanimation Adaptation** — Fatal Error adaptation for PDA Reanimation. Requires New PDA 3D Models; disable the base PDA Reanimation installation. The installer warns that this option does not work with G.A.M.M.A.
- **SSS Raindrops on Screen** — restores rain drops on the PDA screen when using SSS HUD raindrops.

### Icons

**PDA icons:** 1x1, 2x1 or Vanilla.

**Battery icons:** Vanilla, Hunlight, Hunlight HD, chilichocolate or chilichocolate HD. HD variants require HD Icons Framework.

### Patches and fixes

The current installer includes options for:

- G.A.M.M.A. cumulative patch
- Devices of Anomaly Redone
- Beef's NVGs Improved
- DAR Dosimeter Enhanced
- trader item injection fix
- community/manual patches supplied in the package

> **G.A.M.M.A.:** if you select the dedicated cumulative patch, follow the installer instruction and do not select the other Fatal Error compatibility patches at the same time.

## Features

### PDA failures

Fatal Error adds failure states associated with:

- Emissions
- Psi Storms
- Electra anomalies
- Pulse anomalies
- Radiation
- Physical damage
- location-specific Fatal Errors

Depending on the failure, the PDA can display errors, glitches, BSOD/recovery behaviour or require a reboot.

### Reboot and recovery

The PDA can be rebooted through the addon interface. The default hotkey is **M** and can be changed in MCM.

Fatal Error also includes BIOS and Safe Mode recovery. A PDA can enter a BSOD state; BIOS can be used to boot it into Safe Mode when appropriate.

### PDA BIOS

BIOS is a central part of the addon. To access it, reboot the PDA and use the gear icon in the top-right corner.

Depending on the PDA model and installed upgrades, BIOS can expose:

- PDA fine-tuning
- Safe Mode Boot
- CPU information
- beeping behaviour
- debug information when Anomaly Debug mode is enabled
- PDA-specific settings and interfaces

### Overclocking

Some PDAs support **Overclocking**. It increases power consumption and the chance of the PDA breaking, so it is a risk/reward mechanic rather than a free upgrade.

### PDA tiers and upgrades

Fatal Error introduces multiple PDA generations/tiers with different capabilities. Lower-tier devices can intentionally hide information such as exact player location, direction and companion information, while higher-tier devices provide more functionality.

The addon supports:

- PDA-specific upgrades
- device-specific upgrades
- upgrade inheritance
- PDA UI upgrades
- model-specific interfaces
- behaviour that depends on PDA generation

With a compatible UI upgrade, the PDA interface can be changed through BIOS.

Fatal Error also includes military-style PDA content such as GETAC and integrates with Milspec PDA.

### Battery system

Supported electronics use defined battery types: **AAA, AA, C, D and F**. Each type has its own capacity in mAh.

| Battery | General role |
| --- | --- |
| AAA | Low-capacity electronics |
| AA | Common portable devices |
| C | Higher-capacity equipment |
| D | High-capacity equipment |
| F | Very high-capacity / rare equipment |

### Universal Power Device (UPD)

UPD is used to charge and discharge batteries. Put a battery and the UPD together in the inventory interaction and drag one item onto the other.

UPD can be obtained through crafting or from traders at the appropriate trade level. High-capacity batteries last longer but are more expensive and harder to find.

### Device damage

Other electronic devices can also be affected by Emissions, Psi Storms, Electras, Pulse anomalies and Radiation.

Recent versions introduced a more granular damaged-device state instead of treating every failure as an immediate complete break. Depending on the device, damage can cause spontaneous shutdowns, visual glitches, flashlight flickering and increased unreliability.

### Glitches and shaders

Fatal Error uses a custom glitch system. PDA models can have different visual effects and scale, while glitches can be triggered by screen damage, Electra exposure, Emissions, Psi Storms, radiation and persistent/passive glitch settings.

Many of these behaviours are configurable through MCM.

### Repairs and maintenance

**Device Repair Kit** can be crafted and used on broken electronics by dragging it onto the device. The addon also supports technician repairs for supported failure states.

PDAs and broken devices can be disassembled where supported, providing another way to handle failed electronics.

## Configuration

Most gameplay tuning is exposed through **MCM**. Depending on the installed version/components, settings can cover:

- Fatal Error frequency and behaviour
- BSOD and recovery behaviour
- reboot behaviour
- accumulated radiation
- device unreliability
- shutdown timers
- PDA glitch intensity and persistence
- PDA beeping radius
- upgrade costs
- PDA/device breaking chances
- overclocking-related behaviour

### Suggested setup philosophy

**Light-touch:** keep failure chances conservative, persistent glitches low and shutdowns short.

**Hardcore:** increase failure chances, enable device unreliability, keep battery consumption meaningful, make repairs costly and use PDA tiers as progression.

> Change major values gradually on an existing save and keep a backup.

## Storyline

Fatal Error includes an optional small quest line that starts in **Red Forest**.

The project documentation gives the starting clue as a **broken PDA in a mine in Red Forest**.

> **Spoiler:** the broken PDA is in a mine in Red Forest.

The storyline is optional in the FOMOD installer. The project also contains voiced dialogue from ReyYn, Melkumov, DЁS and Dungeon Master.

## Integrations

| Addon | Integration |
| --- | --- |
| **3D INTERACTIVE PDA** | Additional PDA interaction support |
| **iTheon's PDA Taskboard** | Taskboard integration |
| **Personal Adjustable Waypoint** | PDA behaviour / feature restrictions |
| **Autocomplete Tasks** | PDA-dependent autocomplete |
| **DAR Dosimeter Enhanced** | Compatibility patch |
| **PDA Hacking** | PDA recovery and Monolith-jammer hacking |
| **Milspec PDA** | Military PDA / tier integration |
| **Devices of Anomaly Redone** | Device-system compatibility |
| **Beef's NVGs Improved** | Device damage / glitch compatibility |
| **G.A.M.M.A.** | Dedicated cumulative patch |

### PDA Hacking

With PDA Hacking installed, Fatal Error can allow a compatible PDA to be hacked out of a BSOD state when normal recovery is unavailable. It can also allow Monolith Jammers to be hacked so a PDA can work in Monolith territory without the corresponding upgrade.

### Personal Adjustable Waypoint

Fatal Error adapts PDA behaviour to PAW restrictions. Depending on the PDA model, features such as PINs and auto-tagging can be restricted.

## Troubleshooting

### PDA stays broken

1. Try a normal PDA reboot.
2. Enter BIOS and use Safe Mode Boot when available.
3. Check whether the PDA needs a Device Repair Kit.
4. If PDA Hacking is installed, check its Fatal Error recovery integration.
5. Review MCM failure settings.
6. Remove incompatible PDA UI/reposition addons.

### PDA position is broken

Check for 2D PDA Mode and base PDA Reanimation/Reposition addons. If using the Fatal Error PDA Reanimation Adaptation, disable the base PDA Reanimation component and install New PDA 3D Models.

### Traders do not sell addon items

Enable the FOMOD option **Fix if traders don't sell addon items**, which uses trader_autoinject.script.

### Shader or visual problems

- Clear the shader cache after installation.
- Check renderer-specific compatibility.
- If using SSS and you want rain drops on the PDA, enable SSS Raindrops on Screen.
- Avoid multiple addons that replace the same PDA shader/UI system.

## Modpack guidance

The author allows Fatal Error to be included in a modpack without separate permission, but explicitly prohibits ripping the addon apart.

- **Allowed:** include Fatal Error as an addon in your modpack.
- **Not allowed:** extract its systems, scripts or assets and redistribute them as a separate modified addon.

For modpack maintainers, preserve the original addon structure when possible and document which Fatal Error patches/options are enabled.

## Credits

### Author

**Ncenka**

### Contributors

- Lexus2411
- VodoXleb
- ᛈᚴᛖᛊᚹᛊᚶⰓᛆᛋ
- SaloEater
- Flawless Sparklemoon

### Assets and contributions

- **PDA REPLACER - BTTR** — DAR213 — PDA 3D models
- **Cr3pis Icons** — PDA/item icons
- **Epilogue** — Kulon PDA model and additional ideas/contributions
- Community testers and contributors from Anomaly / G.A.M.M.A. communities

## Links

- **GitHub:** https://github.com/Ncenka/Fatal-Error
- **ModDB:** https://www.moddb.com/mods/stalker-anomaly/addons/fatal-error-by-ncenka
- **G.A.M.M.A. Discord:** https://discord.com/channels/912320241713958912/1387494277218566454
- **Anomaly Discord:** https://discord.com/channels/456765861953536020/1372913212114206870
- **Support the author:** https://boosty.to/ncenka-sdt

## Changelog

### 1.7.9.5

Current repository / FOMOD version.

### 1.7.9.4.1 — 31 May 2026

- Fixed a PDA Hacking issue where a locked PDA could shut down during hacking and become bricked.

### 1.7.9.4 — 29 May 2026

- Fixed a rare BusyHands error while crafting a new PDA.
- Improved Milspec PDA integration.
- Fixed a CPU issue related to ALife Plus.
- Added Player Group Command integration.
- MAC update.

### 1.7.9.3 — 8 March 2026

- Added deep PDA Hacking integration.
- Added a new Safe Mode Boot screen.
- Optimized UI code.
- Updated MAC integration.
- PDA can break after sufficient physical damage.
- Fixed Glowsticks upgrades.
- Fixed Milspec-related issues.

### 1.7.9.2 — 31 January 2026

- NPC PDAs now follow player PDA behaviour more closely.
- NPC PDAs can spawn broken, show BSOD, be overclocked and require reboot.
- NPC PDAs use the standard PDA slot.
- NPC PDA BIOS can display random nickname, security code and CPU information.
- Added native Milspec Progressive Mode compatibility.
- Added DAR Dosimeter Enhanced compatibility.
- Fixed storyline PDA damage display.

### 1.7.9 — 22 October 2025

- Major texture and code optimization.
- Added a more detailed damaged-device system.
- Added device unreliability and configurable shutdown timers.
- Improved BIOS stability.
- Added/adjusted PDA autocomplete behaviour.
- Adjusted PAW and Taskboard integration.

### 1.7.8.5 — 5 October 2025

- Fixed AOEngine BSOD and NVG-related crashes.
- Added an error/problem catcher.
- Improved BIOS CPU handling.
- Updated MAC integration.
- Added technician BSOD repair.

### 1.7.8.4 — 21 September 2025

- Integrated Mod App Creator (MAC).
- Added BIOS access through the MAC launcher.
- Added a new battery and updated battery icon options.
- Updated compatibility patches.
- Added Ukrainian and French localization.

### 1.7.8.1 — 28 August 2025

- Added interface upgrades for PDA 4.0, Kulon and Military.
- Improved BIOS interface.
- Fixed battery scripts and UPD duplication.
- Improved broken-PDA behaviour.
- AOEngine 0.5 compatibility.

### 1.7.8 — 23 August 2025

- Major PDA framework rewrite.
- Added PDA generations and PDA-specific UI.
- Updated MCM and community patches.
- Added/updated Beef's NVGs compatibility.
- Added storyline voice content.

### 1.7.7 — 12 July 2025

- Reworked device upgrades.
- Improved Device Repair Kit.
- Added PDA Reanimation adaptation.
- Added manual compatibility patches.
- Improved radiation glitch calculations and Gamma crafting compatibility.

### 1.7.6 — 25 June 2025

- Added PDA BIOS and Safe Mode Boot.
- Added PDA Overclocking.
- Added PDA beeping-radius setting.
- Improved compatibility patches and NPC PDA handling.

### 1.7.5 — 26 May 2025

- Improved no-map-location behaviour.
- Added additional Geiger/detector functionality and passive power drain.
- Added detector crafting.
- Expanded technician support.

### 1.7.4 — 18 May 2025

- Added the battery system.
- Added PDA proximity beeping.
- Added PDA progression restrictions.
- Reworked the main PDA script.
- Added initial boot delay and trader item injection fix.

### 1.7.3 — 8 May 2025

- Made new 3D models and icons optional.
- Improved 3D PDA compatibility and PDA positioning.

### 1.7.2 — 5 May 2025

- Added new PDA tiers.
- Added new reboot screen, PDA models and icons.
- Improved Milspec / PDA 4.0 compatibility.

### 1.7.1 — 1 May 2025

- Reworked Fatal Error detection.
- Added animated PDA reboot.
- Added the initial storyline.
- Added PDA/device disassembly.

### 1.7.0 — 16 April 2025

- Devices can break from Emissions, Psi Storms, Electras, Pulse and Radiation.
- Added Device Repair Kit and technician support.

### 1.6.4 — 3 April 2025

- Added PDA Reboot through inventory.
- Improved BSOD recovery.

### 1.6 — 27 March 2025

- Added physical PDA screen damage.
- Added BSOD MCM settings.
- Reworked underground Fatal Error behaviour.

### 1.5 — 23 March 2025

- Added BSOD / PDA Recovery System.
- Added configurable upgrade costs.
- Added accumulated-radiation MCM settings.

### 1.4 — 18 March 2025

- Added PDA radiation failure and PDA Repair Kit.

### 1.3 — 14 March 2025

- Added PDA failures caused by electrical and Pulse anomalies.

### 1.2 — 14 March 2025

- PDA models received different failure chances.
- Improved repair behaviour after Emissions and Psi Storms.

### 1.1 — 12 March 2025

- Added PDA failure during Emission / Psi Storm.
- Added white-noise effect.

### 1.0 — 11 March 2025

- Initial release.

---

## Redistribution

Fatal Error may be included in a modpack, but its individual components should not be ripped apart and redistributed as a separate modified addon.

<div align="center"><strong>Fatal Error — because a PDA should sometimes deserve a BSOD.</strong></div>