# Firefight: World War III - the Final War

[中文](README.zh.md)

A total-conversion mod project for the 2D top-down real-time simulation *Firefight*.

## Overview

| Item | Value |
| --- | --- |
| Current version | `2.3.0` |
| Release date | `2026.10.1` (YYYY.MM.DD) |
| License | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.en) |
| Team | *Firefight: World War III Mod Development Team*, based in Mainland China |

## Repository layout

| Path | Content |
| --- | --- |
| `Assets/mod.txt` | Mod manifest: nationalities, equipment tables, unit and weapon registration |
| `Assets/Data/` | Unit, vehicle, weapon and equipment data |
| `Assets/Images/` | Unit, vehicle, hull, profile, turret and uniform artwork |
| `Assets/Sounds/` | Weapon, explosion, voice and music assets |
| `CHANGELOG.md` | Release notes and complete change history (English; Chinese in `CHANGELOG.zh.md`) |
| `CREDITS.md` | Contributors and sponsors |
| `THIRD-PARTY-NOTICES.md` | Third-party components and their licenses |
| `docs/flow.md` | Repository structure and data flow |
| `LICENSE` | CC BY-SA 4.0 legal code |

`Assets/` holds the mod payload; the repository root holds documentation and licensing files. A packaging step that uses this repository as a mod directory must place the contents of `Assets/` at the root of the packaged `Mod/` directory, because the game loads `mod.txt` from that root.

## Team

| Name | Role |
| --- | --- |
| 扁曹AwA (BC_awa) | Images, data |
| 任天 (Rosky) | Images, data |
| 荼炭 (Charery) | Images, data |
| Logic | Images, data |

Contact: [BC_awa@163.com](mailto:BC_awa@163.com)

## License and attribution

The mod content is released under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.en) license.

Within the permissions of CC BY-SA 4.0, the project adds one requirement: use of this mod must be attributed and an appropriate copyright notice must be included. One way to comply is to include the text of this `README.md` file as the copyright notice directly in the modified mod; that file may be renamed to `ABOUT_WWIII_FW.md`, or another reasonable method may be used.

Third-party components and their licenses are listed in `THIRD-PARTY-NOTICES.md`.
