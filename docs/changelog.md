---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- hdr-changelog.md v1.0.0.1
Modular Rocket Systems (MRS)
created: 13 May 2022
updated: 05 Nov 2022
CC BY-ND 4.0 by zer0Kerbal -->  
# Changelog

| modName    | Modular Rocket Systems (MRS) by NecroBones                        |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0+ARR                                                  |
| author     | NecroBones and zer0Kerbal                                         |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/211992-*/) |
| github     | (https://github.com/zer0Kerbal/ModularRocketSystems)              |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/ModularRocketSystems) |
| spacedock  | (https://spacedock.info/mod/86)                                   |
| ckan       | ModularRocketSystems                                              |

## Version 1.13.99.2-prerelease - `<Спасибо evanisrael+ngx-ree>` edition

* Released
  * 05 Jul 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

* 📌 Pinned
  * 67 parts total
  * This pre-release is the next in a series of updates to this addon. Each update will update some of the parts and patches so that this addon can be updated in a more manageable manner instead of one massive update.
  * search for `mrs` in the editor search bar to find parts in this pack.
  * <ghostparts.cfg> is provided for testing

### Change Summary 1.13.99.2

* Localize
  * ![Russian (Русский)](https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/RU.png) Russian (Русский)
  * Спасибо [evanisrael](https://github.com/evanisrael)
* Update
  * Cargo, Command, Control, Coupling, Electrical, Ground, Resource
  * Stack 1.25 RTG found some more cookies, now generates 6.0 EC/sec
  * only parts that have [oldName] will be ghosted
  * Swat Bug(s)
    * RCS thrusters thought they could glow, they were mistaken
    * Send decouplers back to remedial decoupling school
    * thank you to [ngx-ree](https://github.com/ngx-ree)

### Changes 1.13.99.2

#### Parts 1.13.99.2

* Update
  * Cargo, Command, Control, Coupling, Electrical, Ground, Resource
  * [mrs-battery-radial-600.cfg] v1.3.99.2
    * fix placement rotation
  * [mrs-rtg-125]
    * ElectricCharge from 4.75 --> 6.0
    * adjust attachment nodes
  * Remove [FXModuleAnimateRCS]
    * RCS thrusters thought they could glow, they were mistaken
    * [mrs-rcs-corner.cfg] v1.3.99.2
    * [mrs-rcs-5.cfg] v1.3.99.2
    * thank you to [ngx-ree](https://github.com/ngx-ree)
  * Send decouplers back to remedial decoupling school
    * [mrs-decoup-250-lp.cfg] v1.3.99.2
    * [mrs-decoup-250-slim.cfg] v1.3.99.2
    * [mrs-decoup-radial-mini.cfg] v1.3.99.2
    * thank you to [ngx-ree](https://github.com/ngx-ree)
* closes #157 - [Bug 🐞]: Some RCS parts keep throwing NullReferenceException exceptions in editor, some decouplers cannot be staged.
* updates #84 - Part Tags

#### Assets 1.13.99.2

* Remove redundant textures
  * updates #9 - Part Asset Updates

#### Compatibility 1.13.99.2

* Move [FuelSwitch.cfg] into FuelSwitchers/

#### Config 1.13.99.2

* Update [ghostParts.cfg] v1.0.1.0
  * only parts that have [oldName] will be ghosted

#### Localization 1.13.99.2

* Add
  * Russian (Русский)
    * [ru.cfg] v1.0.0.0
    * Спасибо [evanisrael](https://github.com/evanisrael)
  * Translation guides
    * [readme-ru.md] v1.0.1.0
    * [quickstart-ru.md] v1.0.0.0
    * Спасибо [evanisrael](https://github.com/evanisrael)
* Update and additional strings
  * [en-us.cfg] v1.0.1.0
  * [ru.cfg] v1.0.1.0
  * add header, give credit
* closes #73 - Russian (Русский) <ru.cfg>
* updates #65 - Localization - Master
* updates #66 - English <en-us.cfg>

#### Documentation 1.13.99.2

* Add
  * [Flags.md] v1.0.0.0
* Update
  * [readme.md] v1.13.99.2
  * [ReleaseLayout.md] v1.13.99.2
  * [_config.yml] v1.0.1.0
  * [404.md] v1.0.1.0
  * [Attributions.md] v1.0.1.0
  * [Disclaimer.md] v1.0.1.0
  * [LegalMumboJumbo.md] v1.0.1.0
  * [Localizations.md] v1.0.1.0
  * [ManualInstallation.md] v1.0.1.0
  * [Marketing.md] v1.0.1.0
  * [Notices.md] v1.0.1.0
  * [PartsCatalog.md] v1.0.1.0
  * [Why.md] v1.0.1.0

### Status 1.13.99.2

* Issues
  * closes #153 - Modular Rocket Systems (MRS) 1.13.99.2-prerelease `<Спасибо evanisrael+ngx-ree>` edition
  * closes #154 - 1.13.99.2 Additional Tasks
  * updates #152 - [REQUEST] update .craft files to use new part names

---

## Version 1.13.99.1-prerelease - `<Codingale: TweakScale'R'Us>` edition

* Released
  * 24 Apr 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 1.13.99.1

* This release is the next in a series of updates to this addon. Each update will update some of the parts and patches so that this addon can be updated in a more manageable manner instead of one massive update.
* Phase I (initial) pass
  * parts pass started
* <ghostparts.cfg> is provided for testing 
* Can now search for `mrs` in the editor search bar to find parts in this pack.
* 67 parts total
  * Initial update pass done on 22 parts, 45 left to be updated
  * Updated
    * Flingatron
    * Tank Xenon 1.25m
    * Tank Xenon 0.625m
    * Decoupler 2.50m lp
    * Decoupler 2.50m slim
    * Decoupler mini-radial
* TweakScale.cfg
  * fixed patch double patching certain parts
  * thank you to [Codingale](https://github.com/Codingale)
  * thank you to [Lisias](https://github.com/Lisias)

### Parts 1.13.99.1

* Updated
  * mrs-flingatron
  * mrs-tank-xenon-125-sp
  * mrs-tank-xenon-0625-sp
  * mrs-decoup-250-lp
  * mrs-decoup-250-slim
  * mrs-decoup-radial-mini

### Update 1.13.99.1

* Update
  * [TweakScale.cfg] v1.13.99.1
    * fixed patch double patching certain parts
    * thank you to [Codingale](https://github.com/Codingale)
    * thank you to [Lisias](https://github.com/Lisias)
  * GitHub Pages
  * HeroLogo/Cover image
* closes #147 - [BUG] TweakScale is reporting

### Status 1.13.99.1

* Issues
  * closes #150 - Modular Rocket Systems (MRS) 1.13.99.1-prerelease `<Codingale: TweakScale'R'Us>` edition
  * closes #151 - 1.13.99.1 Additional Tasks

---

## Version 1.13.99.0-adoption - `<Thank you NecroBones>` edition

* Released
  * 01 Mar 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

### Summary 1.13.99.0

* This release is the first in a series of updates to this addon. Each update will update some of the parts and patches so that this addon can be updated in a more manageable manner instead of one massive update.
* Phase I (initial) pass
  * parts pass started
* <ghostparts.cfg> is provided for testing and will not be active for v2.0.0.0-release.
* Can now search for `mrs` in the editor search bar to find parts in this pack.
* Two new parts
  * Based upon forum submission by [pejsek](https://forum.kerbalspaceprogram.com/index.php?/profile/139640-*//)
  * 1.875m Cargo Bay, long and short
* 67 total
  * Initial update pass done on 16 parts
    * Cargo Bays
      * 1.25m, 2.50m short, 2.50m long
    * Probe
      * 1.25m Cone
      * Radial 1
      * Radial 2 (advanced)
    * Control
      * RCS 5-way block
      * RCS corner block
      * SAS
        * 0.625m, 2.50m and 3.75m
    * Electrical
      * Battery 600ec Radial
      * 1.25m RTG
    * Ground
      * Landing Leg
    * Resource
      * 2.5m Drill
      * 1.25m Fuelcell
  * 49 parts renamed, yet to be updated
* TweakScale.cfg
  * mrs-rtg-125 scale was 0.625 should by 1.25
* mrs-leg-1
  * add ModuleWheelDamage
  * ?correct values

### Archival Releases 1.13.99.0

* Create

* Archival Releases
  * [x] 1.13.2.0-release `<Archival>`
  * [x] 1.13.1.0-release `<Archival>`
  * [x] 1.13.0.0-release `<Archival>`
  * [x] 1.12.8.0-release `<Archival>`
  * [x] 1.12.7.0-release `<Archival>`
  * [x] 1.12.6.0-release `<Archival>`
  * [x] 1.12.5.0-release `<Archival>`
  * [x] 1.12.4.0-release `<Archival>`
  * [x] 1.12.3.0-release `<Archival>`
  * [x] 1.12.2.0-release `<Archival>`
  * [x] 1.12.1.0-release `<Archival>`
  * [x] 1.12.0.0-release `<Archival>`
  * [x] 1.11.1.0-release `<Archival>`
  * [x] 1.11.0.0-release `<Archival>`
  * [x] 1.10.1.0-release `<Archival>`
  * [x] 1.10.0.0-release `<Archival>`
  * [x] 1.9.0.0-release `<Archival>`
  * [x] 1.8.0.0-release `<Archival>`
  * [x] 1.7.4.0-release `<Archival>`
  * [x] 1.7.3.0-release `<Archival>`
  * [x] 1.7.2.0-release `<Archival>`
  * [x] 1.7.1.0-release `<Archival>`
  * [x] 1.7.0.0-release `<Archival>`
  * [x] 1.6.6.0-release `<Archival>`
  * [x] 1.6.5.0-release `<Archival>`
  * [x] 1.6.4.0-release `<Archival>`
  * [x] 1.6.3.0-release `<Archival>`
  * [x] 1.6.2.0-release `<Archival>`
  * [x] 1.6.1.0-release `<Archival>`
  * [x] 1.6.0.0-release `<Archival>`
  * [x] 1.5.1.0-release `<Archival>`
  * [x] 1.5.0.0-release `<Archival>`
  * [x] 1.4.4.0-release `<Archival>`
  * [x] 1.4.3.0-release `<Archival>`
  * [x] 1.4.2.0-release `<Archival>`
  * [x] 1.4.1.0-release `<Archival>`
  * [x] 1.4.0.0-release `<Archival>`
  * [x] 1.3.2.0-release `<Archival>`
  * [x] 1.3.1.0-release `<Archival>`
  * [x] 1.3.0.0-release `<Archival>`
  * [x] 1.2.0.0-release `<Archival>`
  * [x] 1.1.0.0-release `<Archival>`
  * [x] 1.0.0.0-release `<Archival>`
  * [x] 0.7.0.0-release `<Archival>`
  * [x] 0.6.0.0-release `<Archival>`
  * [x] 0.5.0.0-release `<Archival>`
  * [x] 0.4.0.0-release `<Archival>`
  * [x] 0.3.0.0-release `<Archival>`
  * [x] 0.2.0.0-release `<Archival>`
  * [x] 0.1.0.0-release `<Archival>`
  * [x] 0.0.0.0-release `<Archival>`
* closes #7 - Archival Releases
* closes #89 - [BUG] Archival Releases

### Compatibility 1.13.99.0

* Split out patches from parts (started)

### Localization 1.13.99.0

* Create
  * Localization/
    * <en-us.cfg> v1.0.0.0
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* Create
  * [ModularRocketSystems.cfg] v1.0.0.0
    * adds localized tags to parts
* closes #8 - Create Localization directory and contents
* closes #10 - Create <ModularRocketSystems.cfg>
* closes #65 - Localization - Master
* closes #83 - Part Localization
* updates #84 - Part Tags
* updates #66 - English <en-us.cfg>
  
### Parts 1.13.99.0

* Add
  * <ghostParts.cfg> v2.0.0.0
* Rename
  * parts to match naming scheme
  * part files to match part names
* Fix
* Lint
* Reformat
* Errors
  * closes #147 - [BUG] TweakScale is reporting
  * closes #146 - [Bug 🐞]: Lander leg missing ModuleWheelDamage, causes IVA mods (MAS/ASET) to crash
* Patches
  * Updated
    * filenames
    * Module Manger patch headers
    * file headers
    * general linting
* Two new parts supplied by forums
  * thank you by [pejsek](https://forum.kerbalspaceprogram.com/index.php?/profile/139640-*//)

### Assets 1.13.99.0

* create Assets/ folder
* convert
  * from mesh to MODEL
* rename
  * Rename model files to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * remove duplicates textures/models
* relocate part.cfg to Parts/
* updates #9 - Part Asset Updates

### Documentation 1.13.99.0

* Add
  * GitHub Pages
    * [`_config.yml`]
    * [Attribution.md] v1.0.7.1
    * [ManualInstallation.md] v1.1.8.0
    * [404.md] v1.0.3.2
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.1.7.0
    * [Marketing.md] v1.0.1.0
    * [Notices.md] v1.0.1.0
    * [Part-Catalog.md] v1.1.4.1
    * [Why.md] v1.1.0.0
  * docs/thumbs
* closes #5 - Create GitHub Pages

### Cover image 1.13.99.0

* Create HeroLogo/Cover image
* closes #6 - Create HeroLogo.png

### Status 1.13.99.0

* Issues
  * closes #1 - Modular Rocket Systems (MRS) 1.13.99.0-adoption `<Thank you NecroBones>` edition
  * closes #2 - 1.1.99.0 Create Legal Mumbo Jumbo
  * closes #3 - 1.1.99.0 Create Documentation
  * closes #4 - 1.1.99.0 Create Social Media Presence
  * closes #85 - Create Agency
  * closes #11 - Update License

---

## Version 1.13.2.1-hotfix - `<Lisias TweakScale'R'Us>` edition

* Released
  * 14 Feb 2023
  * for Kerbal Space Program 1.4.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Summary 1.13.2.1

* Update TweakScale patch
  * add :FOR
  * use standard patch from Lisias
  * make patch stay in its lane, no patching other addons! Bad patch!
  * Thank you to [Lisias](https://github.com/Lisias)

* Issues
  * closes #142 - Modular Rocket Systems (MRS) 1.13.2.1-hotfix `<Lisias TweakScale'R'Us>` edition
  * closes #140 - [BUG] TweakScale patch out of control
  * closes #141 - duplicate
  * closes #143 - 1.13.2.1 Additional Tasks

---

## Version 1.13.2.0-release `<Archival>`

* 12 Mar 2018
* Kerbal Space Program 1.4.1

* Tweaks
* Added some missing data to the Tweakscale config.

* Issues
  * closes #7 - Archival Releases
  * closes #64 - 1.13.2.0
  * closes #89 - [BUG] Archival Releases

---

## Version 1.13.1.0-release `<Archival>`

* 21 Oct 2016
* Kerbal Space Program 1.2.0

* Fixes
* RCS sounds/effects added.
* Radial battery moved to Electrical menu tab.

* Issues
  * updates #7 - Archival Releases
  * closes #63 - 1.13.1.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.13.0.0-release `<Archival>`

* 11 Oct 2016
* Kerbal Space Program 1.2.0

* KSP 1.2 Compatibility
* Added MM "NEEDS" conditionals to RemoteTech modules in probe cores.
* Updated categories for many parts.
* Added KerbNet/transmitter modules to probe cores.
* Landing Leg updated with 1.2 variables and sounds.

* Issues
  * updates #7 - Archival Releases
  * closes #62 - 1.13.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.12.8.0-release `<Archival>`

* 12 Jul 2016
* Kerbal Space Program 1.1.3

* Tweaks
* Guidance Nose Cone balance tweaks:
  * Cost increased. Research cost increased (was erroneously left at "0").
  * Reaction Wheel torque and electrical usage reduced by 25%.
  * Moved to Flight Control tech node.
* Adjusted some tags, including adding nickname tags for engines.
* Added NearFutureElectrical support for RTG.
* Moved ModuleManager patches to Patches folder.

* Issues
  * updates #7 - Archival Releases
  * closes #61 - 1.12.8.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.12.7.0-release `<Archival>`

* 20 May 2016
* Kerbal Space Program 1.1.2

* Tweaks
* Updated the description for the inline RTG.
* Fixed a copy/paste error in the "corner" RCS configs.

* Issues
  * updates #7 - Archival Releases
  * closes #60 - 1.12.7.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.12.6.0-release `<Archival>`

* 22 Apr 2016
* Kerbal Space Program 1.1.0

* Transparency fix
* Fixed the "always transparent" problem in the VAB for cargo bays in 1.1.

* Issues
  * updates #7 - Archival Releases
  * closes #59 - 1.12.6.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.12.5.0-release `<Archival>`

* 17 Apr 2016
* Kerbal Space Program 1.1.0

* Tweaks
* Moved rocket cargo bays to Advanced Construction and Specialized Construction tech nodes.
* Tweaked leg settings.
* Moved leg wheel collider to allow for more accurate aerodynamic occlusion.

* Issues
  * updates #7 - Archival Releases
  * closes #58 - 1.12.5.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.12.4.0-release `<Archival>`

* 31 Mar 2016
* Kerbal Space Program 1.1.0

* KSP 1.1 Hotfix
* Landing legs have suspension and working feet again.

* Issues
  * updates #7 - Archival Releases
  * closes #57 - 1.12.4.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.12.3.0-release `<Archival>`

* 29 Mar 2016
* Kerbal Space Program 1.1.0

* KSP 1.1 Hotfix
* Landing legs updated to not be 100% deadly. Suspension still doesn't work, legs are rigid for now.
* Added tags for most parts.

* Issues
  * updates #7 - Archival Releases
  * closes #56 - 1.12.3.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.12.2.0-release `<Archival>`

* 20 Mar 2016
* Kerbal Space Program 1.0.5

* Hotfix
* Rotated the RCS blocks back to their original orientation, so as to not break previously created vessels.

* Issues
  * updates #7 - Archival Releases
  * closes #55 - 1.12.2.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.12.1.0-release `<Archival>`

* 17 Mar 2016
* Kerbal Space Program 1.0.5

* Nose cone hotfix
* Re-added basic stability control to the Guidance Nose Cone.
* Moved Guidance Nose Cone to "Engineering 101" tech node, so that it at least has to be unlocked before use.

* Issues
  * updates #7 - Archival Releases
  * closes #54 - 1.12.1.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.12.0.0-release `<Archival>`

* 17 Mar 2016
* Kerbal Space Program 1.0.5

* Minor Update
* Added ConnectedLivingSpace configs for slimline 2.5m docking port, and cargo bays.
* Changed attachment rules for docking helpers, to allow surface-attaching them (and in turn turned off accepting surface attachment).
* Reduced Guidance Nose-Cone's capabilities some more. Removed remaining SAS, weakened reaction wheel, lowered max temp.
* Redesigned RCS blocks to look more stock-alike, and tweaked their price and mass.
* Added RCS blocks to the "Lite" pack.

* Issues
  * updates #7 - Archival Releases
  * closes #53 - 1.12.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.11.1.0-release `<Archival>`

* Fixes
* 29 Jan 2016
* Kerbal Space Program 1.0.5

* Corrected a typo with thermalMassModifier in the LAS Shroud.
* Corrected a typo with Agency mentality.
* Added a note in the "Inline Drill" description warning against using it as a root part.

* Issues
  * updates #7 - Archival Releases
  * closes #52 - 1.11.1.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.11.0.0-release `<Archival>`

* 02 Dec 2015
* Kerbal Space Program 1.0.5

* Decoupler pass
* Increased heat tolerance of 2.5m stack decouplers by 200 degrees.
* 2.5m "low profile" stack decoupler updates:
  * Added internal "sepratron" solid motors as optional separation aids (remove propellant to not use).
  * Increased cost and base mass (to balance this against stock decoupler).
  * Added drag-cube to match stock decoupler.

* Issues
  * updates #7 - Archival Releases
  * closes #51 - 1.11.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.10.1.0-release `<Archival>`

* 13 Nov 2015
* Kerbal Space Program 1.0.5

* Tweaks/Fixes, mainline MRS only
* 0.625m air intakes have intake speed restored to match their bigger brothers.
* Corrected a variety of effects+gimbal problems with the 3.75m quad cluster engine, introduced in 1.10.

* Issues
  * updates #7 - Archival Releases
  * closes #50 - 1.10.1.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.10.0.0-release `<Archival>`

* 11 Nov 2015
* Kerbal Space Program 1.0.5

* KSP 1.0.5 update
* Adjusted inner attachment nodes on cargo bays to be offset inward like new stock settings on cargo bays.
* Cargo bays now have settings for door deployment limits.
* Flingatrons updated to use new contract constraints, and exhaust damage reducer, and other thermal settings.
* RTG updated to use new passive core temperature system.
* Inline Drill/Tank combo updated to use the stock drill's new settings.
* Fuel crossfeed toggle added to aerodynamic pylons.
* Engines (except quad-nuke) updated to use FXModuleAnimateThrottle.
* Engines, decouplers/separators, etc updated to use new stock-alike thermal settings and contract constraints.
* Jet Engines and Air Intakes rebalanced.

* Issues
  * updates #7 - Archival Releases
  * closes #49 - 1.10.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.9.0.0-release `<Archival>`

* 07 Nov 2015
* Kerbal Space Program 1.0.4

* N7-Day Update
* Added support for HullCameraVDS to the radial probe core panels.
* Adjusted MM patch filenames to be more consistent.
* Added docking lights to the docking helpers.

* Issues
  * updates #7 - Archival Releases
  * closes #48 - 1.9.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.8.0.0-release `<Archival>`

* 08 Oct 2015
* Kerbal Space Program 1.0.4

* Tweaks and RTG
* Corrected a typo in the menu category for the slimline 2.5m decoupler.
* 2.5m "three quarter" tank moved up to the Advanced Fuel Systems tech node.
* 2.5m->3.75m adapter tank moved up to Large Voluma Containment tech node.
* Corrected an issue with Flag Decals on the cargo bays not displaying correctly in the VAB/SPH editors.
* Added a 6.25x RTG unit.

* Issues
  * updates #7 - Archival Releases
  * closes #47 - 1.8.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.7.4.0-release `<Archival>`

* 06 Oct 2015
* Kerbal Space Program 1.0.4

* Tweaks
* Increased heat tolerance of the ore drill/tank combo part.
* Fuel switching config will not enable if Starlion Industries KSPI is installed, deferring to its settings.

* Issues
  * updates #7 - Archival Releases
  * closes #46 - 1.7.4.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.7.3.0-release `<Archival>`

* 07 Jul 2015
* Kerbal Space Program 1.0.4

* Tweaks
* Added ConductionFactor/convectionflux settings for cargo bays.
* Added support for Interstellar/FS Fuel Switch.

* Issues
  * updates #7 - Archival Releases
  * closes #45 - 1.7.3.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.7.2.0-release `<Archival>`

* 22 Jun 2015
* Kerbal Space Program 1.0.3

* KSP 1.0.3 balance update
* Updated thermal settings for many parts.
* Modified quad-nuke's heat generation to match stock.
* Updated 0.625m jet engine performance to match stock (defined as 0.3x stock 1m jets).

* Issues
  * updates #7 - Archival Releases
  * closes #44 - 1.7.2.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.7.1.0-release `<Archival>`

* 19 Jun 2015
* Kerbal Space Program 1.0.2

* Tweaks
* Reduced texture resolution of 2.5m "low profile" decoupler by half (75% reduction in the texture's memory requirement).
* Increased the suspension strength of landing legs.
* Tweaked thermal properties of landing legs.

* Issues
  * updates #7 - Archival Releases
  * closes #43 - 1.7.1.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.7.0.0-release `<Archival>`

* 11 Jun 2015
* Kerbal Space Program 1.0.2

* Cargo-Bay overhaul + Tweaks and fixes
* Updated Deadly Reentry config with more current data.
* Tweaked some settings on cargo bays.
* Added VAB/SPH transparency to cargo bays.
* Added "Animated Decouplers" support for LAS Shroud (to make it shield properly in stock aero, AD needs to be installed).
* Overhauled the cargobay doors, so they don't get in the way as much.

* Issues
  * updates #7 - Archival Releases
  * closes #42 - 1.7.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.6.6.0-release `<Archival>`

* 28 May 2015
* Kerbal Space Program 1.0.2

* More balancing
* N nuclear engine.  Nuke to 12, to match 4x stock LV Increased mass of Quad
* Added "inline" (stackable) drill with internal storage.
* Switched flag/agency images back to PNG format so they'll work again.

* Issues
  * updates #7 - Archival Releases
  * closes #41 - 1.6.6.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.6.5.0-release `<Archival>`

* 22 May 2015
* Kerbal Space Program 1.0.2

* Fixes & Tweak
* Corrected the HotRockets config for the 0.625m jet engines.
* Explicitly defined fuelCrossFeed=False for radial decouplers.
* Added "ModuleCrossFeed" to small radial fuel tank, for Crossfeed Enabler.
* Increased heat conductivity of flat adapters (so they don't impede heat management).
* Corrected an issue with normals on mini radial fuel tank.

* Issues
  * updates #7 - Archival Releases
  * closes #40 - 1.6.5.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.6.4.0-release `<Archival>`

* 14 May 2015
* Kerbal Space Program 1.0.2

* Tweak
* Added ground effects to several engines.
* Tweaked the LAS Shroud aerodynamics
* over in the VAB/SPH. through on mouse LAS Shroud will now be see
* Corrected TweakScale settings for "Hound" Engine.
* Re-Added a reworked stackable inline 1.25m fuel cell.
* 0 (0.625m) jet engines & intakes.  balanced the size Re
  * 20% more thrust (30% of stock 1.25m counterparts), but also more mass.
  * 20% more air through intakes, slight increase in mass.
  * Adjusted sound/visual effects to correspond to stock changes.
* Air intakes no longer qualify as contract test subjects.
* Corrected a problem with the normals on the 0.625m fuel tanks.

* Issues
  * updates #7 - Archival Releases
  * closes #39 - 1.6.4.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.6.3.0-release `<Archival>`

* 08 May 2015
* Kerbal Space Program 1.0.2

* Fixes & 1.0.2 tweak
* Fixed a configuration typo for the 2.5m flat adapter.
* Fixed a configuration typo for the long landing leg.
* Reversed the attachment node priority order for extremely thin parts (docking helpers, decouplers, reaction wheels, flat adapters) so that they attach more easily.
* Updated "Community Tech Tree" support for compatibility with CTT's new design.
* Minor tweaks to the "drag cubes" for the cargo bays.
* Reduced mass of 2.5m dome nose cone.

* Issues
  * updates #7 - Archival Releases
  * closes #38 - 1.6.3.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.6.2.0-release `<Archival>`

* 01 May 2015
* Kerbal Space Program 1.0.2

* More 1.0 tweaks + 1.0.1 compatibilit
* like. temps on engines to be more stock Adjusted max
* Fixed the "Hound" engine's description to no longer say "Terrier".
* Adjusted the Guidance Nose Cone to have slightly less torque, and increased electrical usage.
* Improved gimbal on several engines.
* Adjusted heat generation on rocket engines to correspond to KSP 1.0.1 changes.
* Adjusted all engine thrust numbers to correspond to KSP 1.0.1 changes.
* Fixed the attachment node on the 1.25m "rounded" nose cone.
* Added "drag box" settings for cargo bays.
* Converted textures to DDS format.

* Issues
  * updates #7 - Archival Releases
  * closes #37 - 1.6.2.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.6.1.0-release `<Archival>`

* 29 Apr 2015
* Kerbal Space Program 1.0.0

* Bays are back, baby
* Re-added cargo bays.

* Issues
  * updates #7 - Archival Releases
  * closes #36 - 1.6.1.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.6.0.0-release `<Archival>`

* 29 Apr 2015
* Kerbal Space Program 1.0.0

* Fixes/Balancing for KSP 1.
* Many 1.0 balance changes. Including, but not limited to:
  * Quad-Nuke: ASL ISP reduced, Mass increased, no longer uses oxidizer.
  * All engines adjusted based on stock updates.
  * Many parts had costs, masses, max temps, tech node assignments, etc adjusted.
  * Adjusted bottom attchment nodes to correspond to KSP 1.0 orientation.
* Cargo Bays (hopefully) temporarily removed, to be reworked for 1.0.
* Removed "radial booster tank".
* Removed fuel cells.
* Renamed the "Terrier" engine: "Hound"

* Issues
  * updates #7 - Archival Releases
  * closes #35 - 1.6.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.5.1.0-release `<Archival>`

* 10 Feb 2015
* Kerbal Space Program 0.90.0

* Minor adjustment
* Released "Lite" version of mod.
* >1.25m adapter cone. positioned seam on the 2.5m Corrected a badly
* Slightly improved contrast in the long landing-leg texture.
* Corrected typos that prevented the LAS tower and Flingatron from showing in the manufacturer tab.

* Issues
  * updates #7 - Archival Releases
  * closes #34 - 1.5.1.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.5.0.0-release `<Archival>`

* 16 Jan 2015
* Kerbal Space Program 0.90.0

* And so on, etc
* Corrected the name of the 0.625m basic air intake (claimed to be 1.25m).
* Increased LAS tower's fuel, thrust, and burn time.
* Added support for Connected Living Space (making the docking helpers and flat adapters passable).
* Renamed the cargo bays as "payload bays" to help FAR/NEAR identify them as aerodynamic fairings.
* Added a set of long landing legs.

* Issues
  * updates #7 - Archival Releases
  * closes #33 - 1.5.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.4.4.0-release `<Archival>`

* 29 Dec 2014
* Kerbal Space Program 0.90.0

* More 0.90 adjustments
* Removed SAS from Reaction Wheel parts, since it no longer works without being on a command pod/core.
* Added advanced form of radial probe core, later in tech tree with full SAS capability.

* Issues
  * updates #7 - Archival Releases
  * closes #32 - 1.4.4.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.4.3.0-release `<Archival>`

* 22 Dec 2014
* Kerbal Space Program 0.90.0

* More 0.90 adjustments
* Reduced reaction wheel strength in Guidance Nose Cone for career balancing.
* Reverted removal (re-added) the basic SAS capability in the Guidance Nose Cone.
* Added basic Deadly Reentry support for the nose cones and guidance cone.

* Issues
  * updates #7 - Archival Releases
  * closes #31 - 1.4.3.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.4.2.0-release `<Archival>`

* 20 Dec 2014
* Kerbal Space Program 0.90.0

* More 0.90 adjustments
* core. Control only, early in the tech tree. cone and radial probe Removed SAS from the guidance nose
* Renamed most parts, for improved name sorting in the new menus.

* Issues
  * updates #7 - Archival Releases
  * closes #30 - 1.4.2.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.4.1.0-release `<Archival>`

* 16 Dec 2014
* Kerbal Space Program 0.90.0

* Minor fix
* Fixed manufacturer icon in VAB/SPH manufacturer-sort.

* Issues
  * updates #7 - Archival Releases
  * closes #29 - 1.4.1.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.4.0.0-release `<Archival>`

* 15 Dec 2014
* Kerbal Space Program 0.90.0

* Fixes, And so on
* No changes necessary for 0.90:
  * Engine/FuelTank split is automatic
  * Leaving SAS basic capability on the reaction wheel parts for now.
* Fixed the career-mode testing requirements on the fuel cell parts, so that contracts can be completed.
* Added HotRockets support for most engines.
* Moved Fuel Cells to the "Fuel Systems" tech node.

* Issues
  * updates #7 - Archival Releases
  * closes #28 - 1.4.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.3.2.0-release `<Archival>`

* 03 Dec 2014
* Kerbal Space Program 0.25.0

* Error correction
* Fixed a texture loading problem with the "three-quarter jumbo" fuel tank.
* 2 docking helpers later into tech tree, to the nodes with the appropriate docking ports. 0 and size Moved size

* Issues
  * updates #7 - Archival Releases
  * closes #27 - 1.3.2.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.3.1.0-release `<Archival>`

* 25 Nov 2014
* Kerbal Space Program 0.25.0

* TweakScale fixed
* Moved all TweakScale configs to a file called "MRS_TweakScale.cfg", and out of the part configs.
* Change all size-adapter pieces to use the preconfigured "adapter" TweakScale types.

* Issues
  * updates #7 - Archival Releases
  * closes #26 - 1.3.1.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.3.0.0-release `<Archival>`

* 24 Nov 2014
* Kerbal Space Program 0.25.0

* Minor Update
* Added "Community Tech Tree" support, by moving the quad-nuke to "Improved Nuclear Propulsion" node, if CTT is also installed.
* Moved "Flingatron" later in tech tree, to Heavy Rocketry.
* Corrected the "Flingatron" exhaust position
* Removed TweakScale size restrictions from adapter pieces, and added support for those that needed it.
  * (reverted in 1.3.1)

* Issues
  * updates #7 - Archival Releases
  * closes #25 - 1.3.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.2.0.0-release `<Archival>`

* 13 Nov 2014
* Kerbal Space Program 0.25.0

* Minor Tweak
* Moved the "Terrier" engine to the "Very Heavy Rocketry" tech node, where the rest of the 3.75m diameter parts are.
* Tweaked the 3.75m Quad-engine
  * Reduced the external glow on the engine bells
  * Added additional framework on the engine bells
  * Tweaked the red coloring on the turbopumps

* Issues
  * updates #7 - Archival Releases
  * closes #24 - 1.2.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.1.0.0-release `<Archival>`

* 07 Nov 2014
* Kerbal Space Program 0.25.0

* Parts update
* Flag decals on cargo bay and 2.5m fuel tank should no longer cast shadows on themselves.
* Corrected the cargo bay doors to be non-attachable. Somehow this setting got lost before release.
* Moved the "radial booster tank" to an earlier node in the tech tree.
* 3 (3.75m) Quad Engine.  Ignitor support to the Size Added Engine
* like "Terrier" engine. 3 (3.75m) Poodle Added Size
* Added Size-1 (1.25m) rocket cargo bay.
* Added radially-attached probe core.

* Issues
  * updates #7 - Archival Releases
  * closes #23 - 1.1.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 1.0.0.0-release `<Archival>`

* 30 Oct 2014
* Kerbal Space Program 0.25.0

* Full release!
* No complaints or bug reports for quite a while. Let's call it 1.0.
* Added LAS (Launch Abort System) consisting of LAS tower, and pod-shroud.
* Added two lengths of 2.5m rocket cargo bays.
* Added 3.75m quad-engine

* Issues
  * updates #7 - Archival Releases
  * closes #22 - 1.0.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 0.7.0.0-beta `<Archival>`

* 07 Oct 2014
* Kerbal Space Program 0.25.0

* Beta Release
* Slimmed the radial mini-tank (particularly the framework) just a hair, to help with fitting inside fairings and cargo bays.
* Added support for the "Engine Ignitor" mod. Settings added to small LFO engine, and quad-nuke.
* Added shading to the 1.25m Xenon sphere tank.
* Tweaked Size-0 SAS module to bring it in line with 0.25
* Moved Xenon-tanks to Propulsion tab, to match 0.25
* Reduced mass of 1.25m (size-1) nose cones to match 0.25
* 1 cones (beating out 0.25) 0) nose cone to match the size Reduced mass of 0.625m (size0)

* Issues
  * updates #7 - Archival Releases
  * closes #21 - 0.7.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 0.6.0.0-beta `<Archival>`

* 24 Sep 2014

* Beta Release
* Fixed 6x symmetry under the 3.75m to 7-way 1.25m adapter
* Adjusted collision mesh on Aerodynamic Pylons to support vertical-snap in Editor Extensions
* Enabled Remote-Tech support to the Guidance Nose Cone.
* Added radial 600-unit battery
* increased size of radial fuel-cell
* Added AVC (Add-on Version Checker) support

See: http://forum.kerbalspaceprogram.com/threads/79745-*/

* Issues
  * updates #7 - Archival Releases
  * closes #20 - 0.6.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 0.5.0.0-beta `<Archival>`

* 19 Sep 2014
* Kerbal Space Program 0.24.2

* Beta Release
* Cosmetic adjustment: Quad-Nuclear engine:
  * Lightened the grey color of the reactors
  * Increased engine bell's size by 9%.
* Cosmetic adjustment: 3.75m monopropellant tank: added white stripes
* Cosmetic adjustment: Xenon sphere tanks: added nodes to support struts
* Cosmetic adjustment: 0.625m jet-fuel tanks: Changed around stripes
* Reduced texture resolution of matching 2.5m and 1.25m nose cones to be more appropriate
* Added "three-quarter jumbo" fuel tank, with flag decals
* Added size-2 ASAS module (20% higher torque/mass/cost than stock unit)
* Added three sizes of aerodynamic structural pylons
* Added 0.625m (size-0) nose cone
* Added 0.625m basic jet engine + intake (as a matching set to the turbojets from last update)
* Added 1.25m "Guidance Nose Cone" probe core + reaction wheels + small battery.
* Added Fuel-Cell electric generators: Radial, 1.25m.

* Issues
  * updates #7 - Archival Releases
  * closes #19 - 0.5.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 0.4.0.0-beta `<Archival>`

* 15 Sep 2014
* Kerbal Space Program 0.24.2

* Beta Release
* Added TweakScale support to most parts
* Added engine glow to the 0.625m tiny LFO engine.
* Adjusted surface attachment for Xenon Sphere tanks so they don't "float" off the surface
* Added "large" (1.25m) xenon sphere tanks
* Added 2.5m to 1.25m cone adapter fuel tank
* nuclear engine. N" quad Added 2.5m "4x LV
* Added 1.25m and 0.625m air intakes
* Added 0.625m Turbojet.
* Added two lengths of 0.625m jet fuel tanks

* Issues
  * updates #7 - Archival Releases
  * closes #18 - 0.4.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 0.3.0.0-beta `<Archival>`

* 11 Sep 2014
* Kerbal Space Program 0.24.2

* Beta release
* Added 2.5m to 1.25m hollow cone adapter
* Added "Flingatron" (3x Sepratron)
* Added pressurized sphere xenon container
* Added 0.625m probe fuel canister
* Added 1.25m to 4x 0.625m quad adapter
* Added 1.25m to 5x 0.625m adapter
* Added 0.625m Stackable Monopropellant engine.
* Added 0.625m Efficient LFO engine.
* Reshaped the fairings on the 2.5m to 5x 1.25m adapter

* Issues
  * updates #7 - Archival Releases
  * closes #17 - 0.3.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 0.2.0.0-beta `<Archival>`

* 06 Sep 2014
* Kerbal Space Program 0.24.2

* Initial Public Beta release.

* Issues
  * updates #7 - Archival Releases
  * closes #16 - 0.2.0.0
  * updates #89 - [BUG] Archival Releases

---

## Version 0.1.0.0-alpha `<Archival>`

* 03 Sep 2014
* Kerbal Space Program 0.24.2

* Alpha test version.
* Internal and external Alpha test version

* Issues
  * updates #7 - Archival Releases
  * closes #15 - 0.1.0.0

---

## Version 0.0.0.0-alpha `<Archival>`

* 29 Aug 2014
* Kerbal Space Program 0.24.2

* Alpha test version.
* Internal and external Alpha test version

* Issues
  * updates #7 - Archival Releases
  * closes #14 - 0.0.0.0

---