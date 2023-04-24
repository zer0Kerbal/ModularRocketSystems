---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.8.1
Modular Rocket Systems (MRS)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- THIS FILE: CC BY-ND 4.0 by zer0Kerbal -->
<!-- based upon work by Lisias -->

# Modular Rocket Systems (MRS)

[Home](./index.md)

A stock-alike parts pack that fills in a variety of gaps in the stock lineup of rocketry parts.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `NecroBones` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/NecroBones/ModularRocketSystems`
* Extract the package's `NecroBones/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/NecroBones` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/NecroBones/ModularRocketSystems`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/NecroBones/ModularRocketSystems`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/NecroBones/ModularRocketSystems`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [NecroBones]
      + [ModularRocketSystems]
        + [Agencies]
          ...
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * CC-BY-NC-SA-4.0.txt
        * changelog.md
        * ManualInstallation.htm
        * ModularRocketSystems.version
        * readme.htm
      ...
    ...
    * [Module Manager /L][mml] or [Module Manager][mm]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none
