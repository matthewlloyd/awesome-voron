# Awesome Voron [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of links related to the free Voron line of printers.

![Voron Logo](https://camo.githubusercontent.com/8dee7e139a0a995eb0e8ce0e9c765875431ae8ff8da1d801ff485622c5a76a51/687474703a2f2f766f726f6e64657369676e2e636f6d2f696d616765732f766f726f6e5f64657369676e5f6c6f676f2e706e67)


## Contents

- [Official Sites](#official-sites)
- [Documentation](#documentation)
- [Mods](#mods)
- [Printer Firmware](#printer-firmware)
- [Slicers and Profiles](#slicers-and-profiles)
- [Vendors](#vendors)


## Official Sites

Official sites maintained by the Voron dev team.

- [Voron Design](https://vorondesign.com/) - Main site, with configurators to generate BOMs, and links to STEP files, manuals, sourcing guides, etc.
- [Voron Documentation](https://docs.vorondesign.com/) - Official documentation, with information sourcing, the build, configuration, tuning, and maintenance.
- [Sourcing Guide](https://vorondesign.com/sourcing_guide) - Official sourcing guide for all Voron printers.
- [Voron GitHub](https://github.com/VoronDesign) - Official Voron GitHub account. 
- [r/voroncorexy](https://www.reddit.com/r/voroncorexy/) - Reddit group, mostly serial request videos.
- [Voron Discord](https://discord.com/invite/voron) - The Discord server, where most of the communication happens.
- [Facebook Group](https://www.facebook.com/groups/voroncorexy/) - VORON CoreXY 3D Printer group on Facebook.

## Documentation

Unofficial documentation from the community.

- [Llybel's V2.4 Recommended BOM Changes](https://docs.google.com/document/d/1esZJFTO1hCzsFt1hfVwuJzQm27T4mPbXps95H8Gskyc/edit) - Community maintained list of recommended additions and changes to the V2.4 BOM.
- [V2.4 CAD Viewer](https://voron-viewer.vercel.app/voron2.4) - See the full V2.4 CAD in your browser.
- [koonweee's Color Chooser CAD Viewer (makercube.me)](https://config.makercube.me/) - Preview colors for your V0.1, Trident, or V2.4, in 3D. 
- [koonweee's Color Chooser CAD Viewer (github.io)](https://koonweee.github.io/voroncfg/) - Preview colors for your V1.8, V2.4, Switchwire, or Micron, in 3D.

## Mods

### Mod Lists and Search Engines

- [VoronUsers Repo](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods) - Official Voron mods repo on GitHub.
- [jangrewe's Voron Mod Search Engine](https://faked.org/voronmods/#) - Search the mods listed in the VoronUsers repo by keyword.

### Collections from Community Members

- [Rama's Mods](https://github.com/Ramalama2/Voron-2-Mods) - Thirteen mods and counting, including Misumi cable clips, improved front idlers Misumi RBPB5 mod, etc.

### Popular Mods

#### Air Filtration

- [Nevermore Air Filters](https://github.com/0ndsk4/VoronUsers/tree/0ndsk4/printer_mods/0ndsk4/Nevermore_Air_Filter) - Activated charcoal air filters for interior or exhaust use.
- [VEFACH](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/KevinAkaSam/VEFACH) - Voron Exhaust Filter, Activated Coal + HEPA.

#### Nozzle Cleaning

- [Purge Bucket and Nozzle Scrubber](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/Decontaminator_Purge_Bucket_%26_Nozzle_Scrubber) - edwardyeeks' mod to clean your nozzle before prints, also helps with Z offset.

#### Z Offset Correction

- [Klicky Probe](https://github.com/jlas1/Klicky-Probe) - Microswitch replacement for the stock inductive probe.
- [Automatic Z Calibration Plugin for Klipper](https://github.com/protoloft/klipper_z_calibration) - Fully automated Z offset correction, change your nozzle, hotend, temperatures, bed, or PEI plate, without adjusting any offsets manually.

#### Multimaterial Printing

- [Enraged Rabbit Carrot Feeder (ERCF)](https://github.com/EtteGit/EnragedRabbitProject) - Bring multimaterial capabilities to 3D printers using a single Direct Drive toolhead.

#### Other

- [Voron 2.4 & Trident FFC Mod Kit](https://www.schmidtproto.com/product-page/voron-2-4-ffc-mod-kit) - Reduce gantry weight and friction by replacing the drag chains with Flexible Flat Cables (FFC). Inexpensive kits available.
- [Annex Engineering's Panel Clips](https://github.com/Annex-Engineering/Annex-Engineering_Other_Printer_Mods/tree/master/All_Printers/Annex_Panel_2020_Clips_and_Hinges) - Panel clips with locking plastic keys, requiring no additional hardware, and available to suit any thickness of panel in 0.5mm increments.

## Printer Firmware

### Klipper

- [Klipper Official Site](https://www.klipper3d.org/) - High quality free open source printer firmware, used by most Voron owners.
- [Klipper Discourse](https://klipper.discourse.group/) - Discourse server for getting support on Klipper.
- [Klipper on GitHub](https://github.com/KevinOConnor/klipper) - Python and C source code for Klipper.
- [Kiauh](https://github.com/th33xitus/kiauh) - Klipper Installation And Update Helper, manages installation of Klipper, Moonraker, Mainsail, Fluidd, KlipperScreen, and more.
- [Fluidd](https://github.com/cadriel/fluidd) - Fluidd is a free and open-source Klipper web interface for managing your 3D printer.
- [Mainsail](https://github.com/meteyou/mainsail) - Mainsail a lightweight & responsive web interface for Klipper, the 3D printer firmware.
- [Mobileraker](http://www.mobileraker.com/) - Android and iOS apps to control Klipper, written using [Flutter](https://flutter.dev/).

### Example Klipper Configs

- [Tigra-Astronomy's V2.4 Configs](https://github.com/Tigra-Astronomy/voron-2-config)

### Other Firmware

- [RepRapFirmware](https://github.com/Duet3D/RepRapFirmware) - Used by the expensive but powerful [Duet3D](https://www.duet3d.com/) boards.

## Slicers and Profiles

### Slicers

- [SuperSlicer](https://github.com/supermerill/SuperSlicer) - A fork of PrusaSlicer, adding many features including built-in calibration and profiles for Voron printers.
- [Ultimaker Cura](https://ultimaker.com/software/ultimaker-cura) - Not as popular as SuperSlicer within the Voron community, but used by many.

### Slicer Profiles

- [Schnitzelslicerrepo²](https://github.com/Stephan3/Schnitzelslicerrepo) -  A collection of profiles for SuperSlicer and KissSlicer made in #landofschnitzel on the Voron Discord.

## Vendors

Vendors are listed alphabetically.

### Parts and Kits

#### Printed Parts Kits

- [Official PIF Program](https://pif.voron.dev/) - High quality ABS parts at low prices from the Voron PIF (print-it-forward) team, with a long wait.
- [Etsy](https://www.etsy.com/search?q=voron) - Parts kits from Etsy vendors, quality and price can vary.
- [Speed200%](https://speed200k.com/) - High quality printed part kits for V2.4, Trident, V0.1, and soon RatRig printers, with no waiting lists. Ships from Florida.

#### US

- [CS Hyde](https://catalog.cshyde.com/viewitems/3d-printing-materials/ultem-pei) - High quality Ultem PEI sheets. Ships from Illinois.
- [DeepFriedHero](https://deepfriedhero.in/) - Parts and kits including ERCF. Ships from Texas.
- [DigMach](https://store.digmach.com/) - Parts and kits. Ships from Washington state.
- [Fabreeko](https://www.fabreeko.com/) - Parts and kits. Ships from Florida.
- [Filastruder](https://www.filastruder.com/) - Parts, kits, and filament. Ships from Georgia.
- [KB-3D](https://kb-3d.com/store/) - Parts and kits. Ships from Ohio.
- [Mandala Roseworks](https://www.mandalaroseworks.com/) - Very flat MIC6 bed plates, panel sets, and kits. Ships from Minnesota.
- [MN Laser Cutting](https://mnlasercutting.com/) - Laser cut ABS panels.
- [Printed Solid](https://www.printedsolid.com/) - Parts, kits, and filament. Ships from Delaware.
- [TITS](https://titsurprises.com/products/peek-bed-spacers-bolts) - PEEK (thermally insulating) bed spacers and bolts.
- [ULTISTIK](https://www.ultistik.com/) - High quality textured PEI flex plates. Ships from Florida.
- [Wham Bam](https://whambamsystems.com/flexible-build-system) - Flex plate systems, including mag sheets, flex plates, and PEX. Ships from Florida.

#### UK

- [OneTwo3D](https://www.onetwo3d.co.uk/) - Parts, kits, and filament. Ships from Cambridgeshire.

#### Canada

- [Sparta3D](https://sparta3d.ca/) - Parts, kits, and filament. Ships from Ontario.

#### China

- [AliExpress](https://www.aliexpress.com/) - Source for many parts.
- [Keenovo](https://keenovo.store/) - Bed heaters preferred by most Voron builders.
- [LDO Motors](https://ldomotors.com/) - High quality stepper motors, linear rails, and kits.
- [MagicStudios](https://magicphoenix.xyz/) - Fully customizable and complete V0, V1.8, and V2.4 kits.
- [RobotDigg](https://robotdigg.com/) - High quality linear rails with very fast shipping.

### Filament

#### US

- [Amazon](https://amzn.to/2ZdDhsu) - eSun ABS+, KVP, and many other brands available with fast shipping.
- [Filastruder](https://www.filastruder.com/collections/filament) - Their Veracity brand is rebranded KVP. Ships from Georgia.
- [Fusion Filaments](https://fusionfilaments.com/collections/abs-filament) - Ships from Wisconsin.
- [Printed Solid](https://www.printedsolid.com/collections/filament) - Many brands and types of filament. Ships from Delaware.
- [KVP](https://www.villageplastics.com/) - Large variety of ABS colors, preferred by many PIF team members. Makes the signature Voron Fluorescent Red. Ships from Ohio.

#### Canada

- [Sparta3D](https://sparta3d.ca/collections/filaments) - ABS, PLA, PETG, TPU, etc. Ships from Ontario.

## Other Printers

### Open Source

- [HevORT](https://hevort.com/) - CoreXY with moving bed. CAD source provided.
- [Prusa](https://prusa3d.com/) - Popular printers including the MK3S+ and Mini+. Autodesk Inventor CAD source provided, and open source firmware.
- [Railcore](https://railcore.org/) - CoreXY 3D printer. Parametric Fusion 360 CAD with design history provided.
- [RatRig](https://www.ratrig.com/) - Various printers with full OnShape CAD provided, and commercially available kits.

### Free (but not completely open source)

- [Annex Engineering](http://annex-engineering.com/) - Many designs including K1, K2, K3, and so on. STLs only, under a proprietary license.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

[![License](https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)
