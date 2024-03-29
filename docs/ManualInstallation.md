---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.0.0
Doupods (DUO)
created: 13 May 2023
updated:

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->

## [Doupods (DUO)][mod]

[Home](./index.md)

A stockalike parts mod that supplies up to three two occupant command pods with minimal performance impact

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `Doupods` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Doupods`
* Extract the package's `Doupods/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/Doupods` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/Doupods`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/Doupods`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/Doupods`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [Doupods]
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
      + [Plugins]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * ManualInstallation.htm
      * changelog.md
      * License.txt
      * readme.htm
      * Doupods.version
    ...
    * [ModularManagement][MM] or [Module Manager][omm]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [SimpleConstruction! (SCON)][SC]
* [ModularManagement][MM] or [Module Manager][omm]

[SC]: https://www.curseforge.com/kerbal/ksp-mods/SimpleConstruction "SimpleConstruction! (SCON)"
[MM]: https://www.curseforge.com/kerbal/ksp-mods/ModularManagement "ModularManagement (MM)"
[omm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/Doupods "Doupods (DUO)"