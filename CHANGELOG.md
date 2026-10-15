# Changelog

[中文](CHANGELOG.zh.md)

All notable changes to this project are documented in this file.

## [Unreleased]

## [2.3.0] - 2026-10-01

**Version Code:** 2030007
**Update Code:** 2640
**Update Type:** Major Content Update

### Added

- the `American-HSTV-L` vehicle;
- Merkava `Mk.3B`, `Mk.3C`, `Mk.3D`, `Mk.4 LIC`, `Mk.4B`, `Mk.4M` (In Production), with all-new hull/turret images for the Merkava family (Mk.1 ~ Mk.4M);
- weapons `WEAPON_CANNON_125_ZPT98`, `WEAPON_CANNON_105_SHARIR` series, `WEAPON_CANNON_120_MG251` series, `WEAPON_CANNON_75_XM274`;
- the Israeli Mechanized Infantry Section, Sayeret Reconnaissance Team and Reserve Infantry Section (based on active IDF references), the Nahal Brigade section leader now carries a Desert Eagle;
- Polished Chooser button images (custom/sound/networking).

### Changed

- Remade the US Marine Corps: new Marine Rifle Squad / Marine Rifle Squad (LAV) / Marine Weapons Squad;
- Improved data of the `M1A1AIM`, `M1A2` series (TUSK/SEP V2~V4), `Leopard 2A4`, `M1128` and other vehicles;
- Improved data and naming of the `M242`, `MK44`, `M61`, `M320/M320A1`, `AT4`, `FGM-148`, `SSG 69`, `FN MAG`, `M2HB` and other weapons;
- all unit comments rewritten (240 units);
- vehicle image file names fully standardized (396 files aligned with the vanilla convention), Merkava unit IDs and image names unified (`Mk.1` ~ `Mk.4 LIC`);
- unit file name prefixes (`French-AMX56`, `Russian-T-90M Bophna`, etc.), long names stripped of stacked generic words, 10 short-name collisions differentiated;
- infantry section comments no longer list grenade counts (vanilla convention), section comments completed with training quality sentences;
- the Israeli faction marked as `In Production`, third-party assets of *Firefight: Gaza Ground Warfare* registered under the MIT license;
- version numbering upgraded to the 7-digit scheme (BMMSSNN), data file indentation standardized (tabs).

### Fixed

- data tag errors in `WEAPON_CANNON_25_KBA_B02`, `Russian-Mortar 2B11`, `Russian-BTR-D`;
- about 50 missing sound references;
- 27 non-standard weapon file names, 20+ spelling errors and 2 mojibake cases;
- other bugs.

## [2.2.3] - 2026-06-12

**Version Code:** 22301

### Changed

- Upgraded `Firefight` version to 12.2.0 (for Android);
- Optimized data of `American-M1A1AIM`, `American-M1A2`, `American-M1A2SEP TUSK2`, `American-M1A2SEP V2`, `American-M1A2SEP V3`, `American-M1A2SEP V4`, `American-M1A2SEP`, `American-M1A2TUSK`.

### Fixed

- the bug of missing weapon `WEAPON_TEST_CH901` of `Chinese-ZBD-100`;
- other bugs.

## [2.2.2] - 2026-05-29

**Version Code:** 22201

### Added

- `American-Infantry Squad 1 (M7)`, `American-Mortar M120`, `American-Mortar M224`, `American-Mortar M252`.

### Changed

- Upgraded `Firefight` version to 12.1.2 (for Android);
- Reset the armor of `Russian-T-14`, `Russian-T-15 2A90`, `Russian-T-15`.

### Fixed

- the turret armor problem of `Russian-BTR-90 Berezhok`;
- other bugs.

## [2.2.1] - 2026-05-22

**Version Code:** 22102

### Added

- night vision support.

### Changed

- Upgraded the game core to version 12.1.0;
- Changed background music;
- Replaced UI interface (incomplete).

## [2.2.0-2] - 2026-03-27

**Version Code:** 22003

### Added

- the ZTZ-99B Main Battle Tank.

### Changed

- Optimized Chinese units;
- Firefight has been updated to version 11.9.0.

### Fixed

- Al-Khalid tank's turret was positioned too far forward;
- several French weapons were missing.

## [2.2.0] - 2026-03-20

**Version Code:** 22000

### Added

- the "Storm" (TShRK Shturm) system;
- the U.S. Armored Multi-Purpose Vehicle (AMPV), Ground Mobility Vehicle (GMV), Joint Light Tactical Vehicle (JLTV), Joint Light Tactical Vehicle (with M230), Mine-Resistant Ambush Protected All-Terrain Vehicle (M-ATV), and the M7A3 Bradley.

### Removed

- Completely removed the U.S. overseas troops.

### Fixed

- QJZ171's images lost;
- Type 100 Tank can't be used;
- CM33's availability time;
- other bugs.

## [2.1.0] - 2026-03-13

**Version Code:** 21005

### Added

- Borrowed assets from the "Asia Pacific Storm" mod (<@1099250465771888660>)  to add a large number of vehicles and introduce four new playable factions, including Japan and India.

### Changed

- Adjusted mod settings to make anti-tank guns unavailable;
- The mod's time has been changed to 2024 to 2033, with a reset of the worldview;
- Refined the availability for some units based on realistic considerations;
- Changed the abbreviation of the M1A2 Abrams System Enhancement Package series back to "M1A2 SEP V*" instead of forms like "M1A2C";
- Revised the naming of the Type 99 main battle tank series based on realistic references, abandoning like the "ZTZ-99III" designation used in War Thunder;
- Updated Firefight version to 11.8.3;
- Deleted some units and organized unit file names in preparation for future updates;
- Polished other details.
