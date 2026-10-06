# Awesome 3D Printing Related [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of 3D printing resources, tools, software, models, communities, and more.

## Contents

- [3D Printer Manufacturers](#3d-printer-manufacturers)
- [3D Printer Hardware & Components](#3d-printer-hardware--components)
- [CAD & 3D Modeling Tools](#cad--3d-modeling-tools)
- [Slicers](#slicers)
- [3D Printer Firmware](#3d-printer-firmware)
- [Control & Remote Management Software](#control--remote-management-software)
- [AMS / Filament Changer Systems](#ams--filament-changer-systems)
- [3D Scanners & Scanning Software](#3d-scanners--scanning-software)
- [File Formats](#file-formats)
- [Online 3D Model Repositories](#online-3d-model-repositories)
- [Online Tools & Utilities](#online-tools--utilities)
- [AI & Generative Design Tools](#ai--generative-design-tools)
- [On-Demand 3D Printing Services](#on-demand-3d-printing-services)
- [Marketplaces & Price Comparison](#marketplaces--price-comparison)
- [Filaments & Materials](#filaments--materials)
- [Post-Processing Tools & Guides](#post-processing-tools--guides)
- [Enclosures & Ventilation](#enclosures--ventilation)
- [Calibration & Test Prints](#calibration--test-prints)
- [G-code Tools & Post-Processing](#g-code-tools--post-processing)
- [Print-in-Place & Hinge Design](#print-in-place--hinge-design)
- [Chemical Smoothing & Surface Finishing](#chemical-smoothing--surface-finishing)
- [3D Printing Safety](#3d-printing-safety)
- [Multi-Material & Soluble Supports](#multi-material--soluble-supports)
- [Klipper Installation & Management](#klipper-installation--management)
- [Remote Access & Networking](#remote-access--networking)
- [Hardware Upgrades & Sensors](#hardware-upgrades--sensors)
- [Troubleshooting Guides](#troubleshooting-guides)
- [Learning Resources & Tutorials](#learning-resources--tutorials)
- [Communities & Forums](#communities--forums)
- [YouTube Channels](#youtube-channels)
- [Books, Magazines & Publications](#books-magazines--publications)
- [Events & Conferences](#events--conferences)
- [3D Printing Technologies](#3d-printing-technologies)
- [Standards & Certification](#standards--certification)
- [Research & Academic Resources](#research--academic-resources) - removed (too specialized)

### Current Related Sections (Keep):
- Enclosures & Ventilation - relevant for print quality and safety
- Calibration & Test Prints - essential for printer setup
- G-code Tools & Post-Processing - practical utilities
- Print-in-Place & Hinge Design - specific but useful technique
- Chemical Smoothing & Surface Finishing - post-processing
- 3D Printing Safety - critical for all users
- Multi-Material & Soluble Supports - advanced printing
- Klipper Installation & Management - firmware
- Remote Access & Networking - printer connectivity
- Hardware Upgrades & Sensors - common modifications
- [Related Awesome Lists](#related-awesome-lists)

---

## 3D Printer Manufacturers

Companies producing FDM, SLA, SLS, and other 3D printing technologies. Listed alphabetically by company name.

### Consumer & Prosumer FDM

- [Anycubic](https://www.anycubic.com/) - Kobra FDM, Photon resin (Shenzhen, China, founded 2015)
- [Artillery](https://www.artillery3d.com/) - Sidewinder, Hornet (Shenzhen, China, founded 2018)
- [Bambu Lab](https://bambulab.com/) - P1P, P1S, X1C, A1 series (Shenzhen, China, founded 2018)
- [Creality](https://www.creality.com/) - Ender-3, CR-10, K1 series (Shenzhen, China, founded 2014)
- [Dremel](https://www.dremel.com/3d-printers) - 3D20, 3D40, 3D45 (Wisconsin, USA)
- [Elegoo](https://www.elegoo.com/) - Neptune FDM, Mars/Saturn resin (Shenzhen, China, founded 2016)
- [FLSun](https://flsun3d.com/) - Q5, V400 delta (Shenzhen, China, founded 2016)
- [Flashforge](https://flashforge.com/) - Adventurer, Creator, Guider (Zhejiang, China, founded 2011)
- [LulzBot](https://www.lulzbot.com/) - TAZ, mini series (Loveland, Colorado, USA, founded 2011)
- [MakerBot](https://www.makerbot.com/) - METHOD, SKETCHBOT; Stratasys subsidiary (New York, USA, founded 2009)
- [Monoprice](https://www.monoprice.com/) - MP Select Mini, Voxel (California, USA)
- [Prusa Research](https://www.prusa3d.com/) - MK4, MK3.5, XL, MINI (Prague, Czech Republic, founded 2012)
- [QIDI](https://qidi3d.com/) - X-Max, X-Plus, Q1 Pro (Zhejiang, China, founded 2017)
- [Raise3D](https://www.raise3d.com/) - Pro2, Pro3, E2 series (California, USA / Shanghai, founded 2015)
- [Snapmaker](https://snapmaker.com/) - 2.0, Artisan; 3-in-1 (print, laser, CNC) (Shenzhen, China, founded 2017)
- [Sovol](https://www.sovol3d.com/) - SV01, SV04, SV06 (Shenzhen, China, founded 2019)
- [Tiertime](https://www.tiertime.com/) - UP Mini 2, UP Plus 2 (Beijing, China, founded 2008)
- [Ultimaker](https://ultimaker.com/) - S3, S5, S7, Method (Utrecht, Netherlands, founded 2011)

### DIY & Open-Source Projects

- [Annex Engineering](https://annexengineering.xyz/) - K1, Can-Do, APEx extruder designs ([GitHub](https://github.com/Annex-Engineering))
- [HyperCube Evolution](https://github.com/RCModel/SOURCE_Code_Hypercube_Evolution) - CoreXY DIY design
- [Rat Rig](https://ratrig.com/) - V-Core, V-Minion, V-Cast CoreXY kits
- [RepRap](https://reprap.org/) - Original self-replicating printer project ([GitHub](https://github.com/reprap))
- [Voron Design](https://vorondesign.com/) - Voron 0.2 (120mm), 2.4 (350mm), Trident ([GitHub](https://github.com/VoronDesign/VoronCoreXY))

### Professional & Industrial

- [3D Systems](https://www.3dsystems.com/) - ProX SLA, SLS, DMP (South Carolina, USA, founded 1986)
- [BigRep](https://bigrep.com/) - ONE, PRO large-format (Germany, founded 2010)
- [Carbon](https://www.carbon3d.com/) - CLIP technology (California, USA, founded 2013)
- [Desktop Metal](https://www.desktopmetal.com/) - Studio, Production; Binder Jet (Massachusetts, USA, founded 2010)
- [EOS](https://www.eos.info/) - M 290 DMLS, P 396 SLS (Krailling, Germany, founded 1989)
- [Formlabs](https://formlabs.com/) - Form 3/3L SLA, Fuse 1 SLS (Massachusetts, USA, founded 2011)
- [HP](https://www.hp.com/us-en/printers/3d-printers) - Jet Fusion MJF (California, USA)
- [Intamsys](https://www.intamsys.com/) - FUNMAT HT, PRO high-temp (Shanghai, China, founded 2013)
- [Markforged](https://markforged.com/) - Metal X, Onyx CFM (Massachusetts, USA, founded 2013)
- [Sinterit](https://sinterit.com/) - LISA, Lisa X desktop SLS (Poland, founded 2014)
- [Sintratec](https://www.sintratec.com/) - S2, S3 desktop SLS (Switzerland, founded 2014)
- [Stratasys](https://www.stratasys.com/) - FDM, PolyJet (Minnesota, USA / Israel, founded 1989)

---

## 3D Printer Hardware & Components

Hardware upgrades, spare parts, and accessories for 3D printers.

### Hotends & Extruders

- [E3D Online](https://e3d-online.com/) - V6, Volcano, Revo, Hemera hotends & extruders (UK)
- [Micro Swiss](https://www.micro-swiss.com/) - All-metal hotends, NG extruders, Dual-Drive gears (USA)
- [Phaetus](https://www.phaetus.com/) - Dragonfly, Rapido, BMS hotends (China)
- [Dyze Design](https://dyzedesign.com/) - DyzEnd-X, DyzExtruder, Pulsar hotends (Canada)
- [Slice Engineering](https://www.sliceengineering.com/) - Mosquito, Mosquito Magnum, Copper Nozzles (USA)
- [Bondtech](https://www.bondtech.se/) - BMG, LGX, LGX Lite dual-drive extruders (Sweden)
- [Trianglelab](https://www.trianglelab.net/) - Volcano clones, V6, BMG clones (China)
- [Creality](https://www.creality.com/) - Spider, Sprite extruders (China)
- [BIQU](https://www.biqu.equipment/) - H2, B1, B2 extruders (China)
- [Orbiter](https://www.3dlabstore.co.uk/) - Orbiter v1.5, v2.0 extruder (UK)

### Build Plates & Surfaces

- [PEI Sheets](https://www.aliexpress.com/w/wholesale-pei-sheet-3d-printer.html) - Polyetherimide; Smooth & textured; 0.08-0.15mm thickness
- [Prusa PEI Sheets](https://www.prusa3d.com/category/pei-sheets/) - 235x255mm, 280x300mm; Smooth & textured
- [Bambu Lab PEI Plates](https://bambulab.com/en/accessories) - 256x256mm; Dual-texture (smooth/textured)
- [Wham Bam Systems](https://www.whambamsystems.com/) - PEX, PEI, FlexPlate magnetic systems (USA)
- [BuildTak](https://www.buildtak.com/) - BuildTak, BuildTak FlexPlate adhesion sheets (USA)
- [Garolite (G10)](https://www.mcmaster.com/g10/) - Fiberglass-epoxy composite; Alternative to PEI
- [Glass Beds](https://www.aliexpress.com/w/wholesale-glass-bed-3d-printer.html) - Borosilicate glass; Flat surface; 3-4mm thickness

### Control Boards & Electronics

- [BigTreeTech (BTT)](https://www.bigtreetech.com/) - SKR Mini E3, SKR Pro, Octopus, Manta boards; STM32-based (China)
- [FYSETC](https://www.fysetc.com/) - F6, Spider, E4 boards (China)
- [MKS](https://www.mks.com.cn/) - GEN L, Robin, E3 boards (China)
- [Duet3D](https://www.duet3d.com/) - Duet 2 WiFi/Ethernet, Duet 3 6HC, Maestro; RepRapFirmware (UK)
- [Lerdge](https://www.lerdge.com/) - X, S, K boards with touchscreen (China)
- [Creality](https://www.creality.com/) - 4.2.2, 4.2.7, v2.4, v2.5 Silent boards (China)
- [Prusa](https://www.prusa3d.com/) - EinsyRambo, Buddy, XLBuddy boards (Czech Republic)
- [Smoothieboard](https://smoothieware.org/) - ARM Cortex-M3; Open-source (discontinued)

### Stepper Motors & Drivers

- [StepperOnline](https://www.stepperonline.com/) - 17HS, 23HS NEMA motors; TMC drivers (China)
- [Pololu](https://www.pololu.com/) - A4988, DRV8825, TMC2130, TMC2209 stepper drivers (USA)
- [Trinamic](https://www.trinamic.com/) - TMC2208, TMC2209, TMC2130, TMC5160 silent drivers (Germany, acquired by Analog Devices)
- [Allegro](https://www.allegromicro.com/) - A4988 stepper motor drivers (USA)

### Linear Motion & Mechanical

- [HIWIN](https://www.hiwin.com/) - HGH, HGW linear guide rails (Taiwan)
- [THK](https://www.thk.com/) - HSR, SHS linear motion systems (Japan)
- [Misumi](https://www.misumi.com/) - Linear rails, bearings, fasteners, aluminum extrusion (Japan)
- [OpenBuilds](https://openbuilds.com/) - V-Slot, C-Beam aluminum extrusion (USA)
- [IGUS](https://www.igus.com/) - Drylin linear bearings, energy chains (Germany)
- [Gates](https://www.gates.com/) - GT2, 2GT, 5M timing belts (USA)
- [OpenBuilds Parts](https://openbuildspartstore.com/) - GT2 belts, pulleys, wheels

### Nozzles

- [E3D Nozzles](https://e3d-online.com/collections/nozzles) - Brass, stainless steel, 0.2-1.2mm diameters
- [Olsson Ruby](https://olssonruby.com/) - Ruby-tipped hardened steel nozzles (Sweden)
- [Micro Swiss](https://www.micro-swiss.com/) - Hardened steel, tungsten carbide nozzles (USA)
- [Copper Nozzles](https://www.sliceengineering.com/) - High thermal conductivity (Slice Engineering)
- [Diamondback Nozzles](https://www.micro-swiss.com/) - Diamond-coated wear-resistant nozzles
- [Bondtech CHT](https://www.bondtech.se/) - High-flow nozzle design

### Cooling & Fans

- [Noctua](https://noctua.at/) - NF-A4x10, NF-A4x20 5V/12V fans (Austria)
- [Sunon](https://www.sunon.com/) - MagLev fans; 4010, 4020, 5015 blowers (Taiwan)
- [Orion Fans](https://www.orionfans.com/) - OA, OD series fans (USA)
- [Sanyo Denki](https://www.sanyodenki.com/) - San Ace high-performance fans (Japan)

### Thermistors & Temperature Sensors

- [EPCOS B57560G104F](https://www.digikey.com/) - NTC thermistor 100kΩ 3950K (standard for Marlin)
- [PT100](https://www.digikey.com/) - Platinum RTD; -200 to 600°C range
- [PT1000](https://www.digikey.com/) - Higher resistance PT100 variant
- [MAX31865](https://www.adafruit.com/) - PT100/PT1000 amplifier board (Adafruit)
- [MAX6675](https://www.adafruit.com/) - K-type thermocouple amplifier (Adafruit)
- [AD595](https://www.analog.com/) - K-type thermocouple amplifier (Analog Devices)

### Power Supplies

- [Mean Well](https://www.meanwell.com/) - LRS, NES, RS series 12V/24V PSUs (Taiwan)
- [TDK Lambda](https://www.emea.lambda.tdk.com/) - Industrial power supplies (Japan)
- [CUI Inc](https://www.cui.com/) - VMS, VFK series AC-DC PSUs (USA)

### Maintenance & Cleaning Tools

- [NoClogger](https://noclogger.com/) - Nozzle cleaning tool for 1.75mm filament
- [Nozzle Cleaning Needles](https://www.amazon.com/s?k=nozzle+cleaning+needles+3d+printer) - 0.2-0.5mm brass/steel brushes
- [E3D Nozzle Touch](https://e3d-online.com/collections/nozzle-cleaning) - Brass brush cleaning tool
- [CleanMe Silicone Sock](https://www.siliconeboot.com/) - Nozzle heat insulation; Prevents ooze
- [Thermal Grizzly Kryonaut](https://www.thermal-grizzly.com/) - Thermal compound for hotend/heatsink
- [Hex Tools (Wera, Wiha)](https://www.wera.de/) - 1.5-3mm hex keys for assembly
- [Digital Calipers (Mitutoyo)](https://www.mitutoyo.com/) - 0-150mm; 0.01mm resolution; Quality measurement
- [Feeler Gauge Set](https://www.amazon.com/s?k=feeler+gauge+set) - 0.05-0.50mm; Bed leveling verification

---

## CAD & 3D Modeling Tools

Software for designing 3D models, categorized by licensing and technical approach. Version numbers indicate current stable releases as of 2025.

### Free & Open Source

- [Blender](https://www.blender.org/) - Mesh modeling, sculpting, animation; GPLv3; Windows/macOS/Linux
- [build123d](https://github.com/gumyr/build123d) - Python CAD library; LGPLv3; OpenCascade backend
- [FreeCAD](https://www.freecad.org/) - Parametric 3D CAD; LGPLv2; STEP, IGES, OBJ, STL, DXF support
- [LibreCAD](https://librecad.org/) - 2D CAD; GPLv2; DWG, DXF support
- [OpenSCAD](https://www.openscad.org/) - Script-based CAD; GPLv2; CSG modeling
- [QCAD](https://qcad.org/) - 2D CAD; GPLv3 Community Edition; DWG, DXF support
- [SolveSpace](https://solvespace.com/) - Constraint-based parametric; GPLv3; STEP, IGES, STL, OBJ
- [Tinkercad](https://www.tinkercad.com/) - Browser-based; Proprietary free tier; STL, OBJ, GLTF export

### Commercial & Professional

- [AutoCAD](https://www.autodesk.com/products/autocad/) - Autodesk; Subscription; Windows/macOS/Web; 2D/3D CAD, DWG native
- [Fusion 360](https://www.autodesk.com/products/fusion-360/) - Autodesk; Subscription/free personal; Windows/macOS; CAD/CAM/CAE
- [Onshape](https://www.onshape.com/) - PTC; Subscription; Browser/iOS/Android; Cloud-native
- [Rhinoceros 3D](https://www.rhino3d.com/) - McNeel; Perpetual; Windows/macOS; NURBS modeling
- [Shapr3D](https://www.shapr3d.com/) - Shapr3D; Subscription; iPadOS/macOS/Windows; Siemens Parasolid kernel
- [Siemens NX](https://www.sw.siemens.com/en-us/products/nx/) - Siemens; Enterprise; Windows/Unix; PLM integration
- [SolidWorks](https://www.solidworks.com/) - Dassault Systèmes; Perpetual/subscription; Windows; Parametric modeling

### Specialized & Mesh Editing

- [MeshLab](https://www.meshlab.net/) - Mesh processing; GPL; Windows/macOS/Linux
- [Meshmixer](https://www.meshmixer.com/) - Mesh editing; Proprietary; Discontinued v3.5
- [Plasticity](https://plasticity.xyz/) - Concept CAD; Trial/paid; Windows/macOS
- [SelfCAD](https://www.selfcad.com/) - CAD with integrated slicer; Subscription; Browser

---

## Slicers

Software that converts 3D models (STL/OBJ/3MF) into machine-readable instructions (G-code). Listed alphabetically.

### FDM Slicers

- [Bambu Studio](https://bambulab.com/en/software/bambu-studio) - AGPLv3; C++; Bambu Lab integration; Windows/macOS/Linux ([GitHub](https://github.com/bambulab/BambuStudio))
- [IdeaMaker](https://www.raise3d.com/ideamaker/) - Free; Raise3D integration; Windows/macOS/Linux
- [Kiri:Moto](https://grid.space/kirimoto/) - MIT; JavaScript; Browser-based 3D/laser/CNC ([GitHub](https://github.com/foxox))
- [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer) - AGPLv3; C++; Fork of Bambu Studio; Windows/macOS/Linux ([GitHub](https://github.com/OrcaSlicer/OrcaSlicer))
- [PrusaSlicer](https://github.com/prusa3d/PrusaSlicer) - AGPLv3; C++; MMU support; Windows/macOS/Linux ([GitHub](https://github.com/prusa3d/PrusaSlicer))
- [Simplify3D](https://www.simplify3d.com/) - Proprietary; Windows/macOS
- [Slic3r](https://slic3r.org/) - AGPLv3; Perl/C++; Original open-source slicer; Windows/macOS/Linux ([GitHub](https://github.com/slic3r/Slic3r))
- [Ultimaker Cura](https://ultimaker.com/software/ultimaker-cura/) - LGPLv3; Python/C++; Plugin system; Windows/macOS/Linux ([GitHub](https://github.com/Ultimaker/Cura))

### Resin (SLA/DLP/LCD) Slicers

- [Chitubox](https://www.chitubox.com/) - Proprietary; Free/basic/pro tiers; Windows/macOS/Linux
- [Formware 3D](https://formware.co/slicer) - Proprietary; Windows/macOS
- [Lychee Slicer](https://mangolychee.com/) - Proprietary; Windows/macOS/Linux
- [Photon Workshop](https://www.anycubic.com/pages/photon-workshop) - Free; Anycubic-specific; Windows/macOS
- [UVTools](https://github.com/sn4k3/UVTools) - MIT; G-code analysis; Windows/macOS/Linux

---

## 3D Printer Firmware

Firmware that runs on 3D printer control boards.

### Mainstream Firmware

- [Marlin](https://marlinfw.org/) - C++; Arduino/LPC176x/STM32; G-code interpreter; PID autotune; Linear Advance; ([GitHub](https://github.com/MarlinFirmware/Marlin)) (GPL-3.0)
- [Klipper](https://www.klipper3d.org/) - Python (host) + C (MCU); Raspberry Pi + control board architecture; Input shaping, Pressure Advance; 32-bit MCUs; [GitHub](https://github.com/Klipper3d/klipper) (GPL-3.0)
- [Repetier-Firmware](https://www.repetier.com/firmware/) - C++; Arduino/Due; EEPROM configuration; [GitHub](https://github.com/repetier/Repetier-Firmware) (GPL-3.0)
- [RepRap Firmware (RRF)](https://duet3d.com/) - C++; Duet boards only; Web interface; Object model; [GitHub](https://github.com/Duet3D/RepRapFirmware) (GPL-3.0)

### Legacy & Specialized

- [Smoothieware](http://smoothieware.org/) - ARM Cortex-M3; Config file-based; [GitHub](https://github.com/Smoothieware/Smoothieware) (MIT)
- [Sailfish](https://github.com/jesseygit/sailfish) - Fork of Sprinter; MakerBot printers
- [Teacup Firmware](https://github.com/Traumflug/Teacup_Firmware) - Lightweight; 8-bit AVRs
- [Sprinter](https://github.com/kliment/Sprinter) - Early RepRap firmware; Historical
- [Prusa Firmware](https://github.com/prusa3d/Prusa-Firmware) - Marlin fork; Prusa MK3/MK4 specific
- [Prusa-Buddy Firmware](https://github.com/prusa3d/Prusa-Firmware-Buddy) - Prusa MINI/MK4; 32-bit STM32
- [KlipperScreen](https://github.com/KlipperScreen/KlipperScreen) - Python; Touchscreen UI for Klipper

### Klipper Frontends

- [Moonraker](https://github.com/Arksine/moonraker) - Python; Web API for Klipper; WebSocket; [GitHub](https://github.com/Arksine/moonraker) (GPL-3.0)
- [Mainsail](https://docs.mainsail.xyz/) - Vue.js; Modern web UI; [GitHub](https://github.com/mainsail-crew/mainsail) (GPL-3.0)
- [Fluidd](https://docs.fluidd.xyz/) - Vue.js; Lightweight web UI; [GitHub](https://github.com/fluidd-core/fluidd) (GPL-3.0)
- [OctoPrint](https://octoprint.org/) - Python; Flask-based; Plugin ecosystem; [GitHub](https://github.com/OctoPrint/OctoPrint) (AGPL-3.0)

---

## Control & Remote Management Software

Software to monitor, manage, and remotely control 3D printers.

### Self-Hosted

- [OctoPrint](https://octoprint.org/) - Python/Flask; Plugin ecosystem; Webcam streaming; ([GitHub](https://github.com/OctoPrint/OctoPrint)) (AGPL-3.0)
- [Moonraker](https://github.com/Arksine/moonraker) - Python; Klipper API; WebSocket; Multi-printer; (GPL-3.0)
- [Mainsail](https://docs.mainsail.xyz/) - Web UI; Klipper/Moonraker; Responsive design; (GPL-3.0)
- [Fluidd](https://docs.fluidd.xyz/) - Web UI; Klipper/Moonraker; Mobile-friendly; (GPL-3.0)
- [KlipperScreen](https://github.com/KlipperScreen/KlipperScreen) - Python/GTK; Touchscreen UI; (GPL-3.0)
- [PrintRun](https://github.com/kliment/Printrun) - Python; Pronterface, Pronsole; Simple host; (GPL-3.0)
- [Repetier-Server](https://www.repetier.com/repetier-server/) - Free & Pro versions; Multi-printer; Webcam

### Cloud Services

- [OctoEverywhere](https://octoeverywhere.com/) - Free tier; AI failure detection; Real-time notifications; Cloud streaming
- [Obico](https://www.obico.io/) - Open-source core; AI failure detection (spaghetti); Telegram/Discord alerts; [GitHub](https://github.com/TheSpaghettiDetective)
- [SimplyPrint](https://simplyprint.io/) - Free & Premium; Cloud print management; Wi-Fi provisioning
- [AstroPrint](https://www.astroprint.com/) - Cloud-based; Mobile app; Design management
- [3DPrinterOS](https://3dprinteros.com/) - Enterprise; Cloud management; Slicing; Device management

### Farm Management

- [OctoFarm](https://octofarm.net/) - Open-source; Multi-printer management; (AGPL-3.0)
- [Kiln](https://github.com/kilnfi/kiln) - Python; Farm management; Analytics; (MIT)
- [Bambu Lab Farm Manager](https://bambulab.com/en/software/farm-manager) - Official; Bambu printers only
- [FlowQ](https://infinityflow3d.com/pages/flowq-3d-printer-automation-print-farm-management-software) - Commercial; Automation & dispatch
- [3DQue AutoFarm](https://3dque.com/quinly3d-products/autofarm3d) - Commercial; Auto-removal integration
- [PrintFarmHQ](https://github.com/PrintFarmHQ/PrintFarmHQ) - Open-source; Multi-printer dashboard
- [Obico Farm](https://www.obico.io/) - AI monitoring; Multi-printer

### OctoPrint Plugins (Notable)

- [Octolapse](https://plugins.octoprint.org/plugins/octolapse/) - Stabilized time-lapse; Camera positioning
- [Bed Visualizer](https://plugins.octoprint.org/plugins/bedlevelvisualizer/) - Mesh visualization; 3D graph
- [PrintTimeGenius](https://plugins.octoprint.org/plugins/PrintTimeGenius/) - ML-based time estimation
- [Cancel Objects](https://plugins.octoprint.org/plugins/cancelobjects/) - Skip defective objects mid-print
- [DisplayLayerProgress](https://plugins.octoprint.org/plugins/DisplayLayerProgress/) - LCD/OLED progress display
- [Filament Manager](https://plugins.octoprint.org/plugins/filamentmanager/) - Filament usage tracking
- [Preheat Button](https://plugins.octoprint.org/plugins/preheatbutton/) - One-click preheating
- [Telegram Bot](https://plugins.octoprint.org/plugins/telegram/) - Telegram notifications & control
- [HomeAssistant](https://plugins.octoprint.org/plugins/homeassistant/) - Home automation integration

---

## AMS / Filament Changer Systems

Automatic Material Systems for multi-color & multi-material printing.

### Commercial Systems

- [Bambu Lab AMS](https://bambulab.com/en/ams) - 4-color (16 with AMS hub); PTFE tube loading; RFID filament detection; X1C, P1S compatible
- [Prusa MMU3](https://www.prusa3d.com/category/multi-material/) - 5-color; Buffer system; Prusa MK3.5, MK4 compatible; Open-source
- [Mosaic Palette](https://www.mosaicmfg.com/collections/palette) - External splicing; Canvas software; Any printer compatible (discontinued, legacy support)

### Open-Source & DIY

- [3D Chameleon](https://www.3dchameleon.com/) - 4-16 colors; Bowden/Tubed; Multi-controller support; Commercial product
- [ERCF (Enraged Rabbit Carrot Feeder)](https://www.enragedrabbit.com/) - Open-source; 12-color; Servo-based; Voron compatible; [GitHub](https://github.com/EtteGit/EnragedRabbitProject)
- [Klipper ERCF Integration](https://github.com/EtteGit/Klippain) - Klipper configuration for ERCF
- [BoxTurtle](https://www.boxturtle.io/) - Open-source; Filament changer
- [MitPrint MITER](https://github.com/mitprintco/miter) - Open-source tool changer
- [Prusa MMU2S](https://www.prusa3d.com/original-prusa-i3-multi-material-2s/) - 5-color; Previous generation; MK3S compatible
- [Tool Changer Project](https://github.com/zachhoogenboom/Toolchanger) - Open-source IDEX/tool changer

---

## 3D Scanners & Scanning Software

Hardware and software for digitizing physical objects as 3D models.

### Desktop & Handheld Scanners

- [AnkerMake Lizard](https://www.ankermake.com/) - Structured light scanner
- [BQ Ciclop](https://github.com/bq/ciclop) - Open-source laser scanner; DIY kit
- [Creality CR-Scan](https://www.creality.com/pages/cr-scan) - Lizard, Otter, Raptor models; Structured light
- [MakerBot Digitizer](https://www.makerbot.com/digitizer) - Discontinued; Laser triangulation
- [Matter and Form](https://matterandform.com/) - MFSV2 desktop scanner; Laser line
- [Revopoint 3D](https://www.revopoint3d.com/) - MINI, POP, RANGE, INSPIRE models; Blue light
- [Shining 3D EinScan](https://www.shining3d.com/einscan-series) - SE, HX, Pro models

### Photogrammetry Software

- [Meshroom](https://github.com/alicevision/Meshroom) - Open-source; AliceVision framework; Structure-from-Motion; Windows/Linux (GPL)
- [RealityCapture](https://www.capturingreality.com/realitycapture) - Commercial; Acquired by Epic Games; Pay-per-output or subscription
- [COLMAP](https://colmap.github.io/) - Open-source; SfM & MVS pipeline; Command-line & GUI; (BSD)
- [Agisoft Metashape](https://www.agisoft.com/) - Commercial; Standard & Professional editions; Photogrammetric processing
- [3DF Zephyr](https://www.3dflow.net/3df-zephyr-free/) - Free (50 photo limit) & Pro versions; Windows only

### Mobile & LiDAR Apps

- [Polycam](https://polycam.com/) - iOS LiDAR & photogrammetry; Free & Pro; iOS/Android/Web
- [Kiri Engine](https://www.kiriengine.com/) - AI-powered; Free tier (10 exports/month); iOS/Android
- [Luma AI](https://lumalabs.ai/) - NeRF & Gaussian Splatting; Free tier; iOS/Web
- [Scandy Pro](https://www.scandy.co/) - iOS LiDAR scanning; Free; Structured output (PLY, OBJ, GLB)

### DIY Scanner Projects

- [OpenScan](https://www.openscan.eu/) - Open-source turntable scanner; BOM ~€50-150; STL files provided
- [Ciclop Scanner](https://github.com/bq/ciclop) - Open-source laser scanner; 3D printable parts
- [Photoneo DIY](https://photoneo.com/) - DIY structured light guides

---

## File Formats

File formats used in 3D printing workflows.

### 3D Model Formats

| Format | Full Name | Type | Color Support | Binary/Text | Notes |
|--------|-----------|------|---------------|-------------|-------|
| **STL** | Stereolithography | Triangulated mesh | No | Both | No units; No metadata |
| **3MF** | 3D Manufacturing Format | XML-based | Yes | ZIP-compressed | Modern; Metadata; Multi-part; Microsoft-led |
| **OBJ** | Wavefront Object | Polygonal mesh | Via MTL | Text | UV mapping |
| **AMF** | Additive Manufacturing Format | XML-based | Yes | ZIP-compressed | ASTM F42 standard; Curved triangles |
| **STEP** | Standard for Exchange of Product Data | CAD | No | Text | ISO 10303; Parametric; CAD interchange |
| **PLY** | Polygon File Format | Point cloud/mesh | Yes | Both | 3D scan output; Vertex colors |

### 2D & Vector Formats

| Format | Full Name | Use Case | Notes |
|--------|-----------|----------|-------|
| **DXF** | Drawing Exchange Format | 2D sketches, laser cutting | Autodesk format |
| **DWG** | Drawing | 2D/3D CAD | Proprietary; AutoCAD native |
| **SVG** | Scalable Vector Graphics | Lithophanes, laser cutting | XML-based; Web-compatible |

### Printer Instruction Formats

| Format | Description | Notes |
|--------|-------------|-------|
| **G-code** | Machine control language | RS-274 standard; Printer-specific variants |
| **X3G** | Binary G-code | MakerBot format; Older printers |
| **SL1** | Prusa SLA format | Resin printer instructions |
| **CXDLP** | Chitubox format | LCD resin printers |
| **PWMO** | Photon Workshop format | Anycubic resin printers |

### Other Formats

| Format | Description | Use Case |
|--------|-------------|----------|
| **IGES** | Initial Graphics Exchange Specification | Legacy CAD interchange (superseded by STEP) |

---

## Online 3D Model Repositories

Platforms to find, share, buy, and sell 3D printable models.

### Major Platforms

- [CGTrader](https://www.cgtrader.com/) - Marketplace; Free & paid models; 3D scan section
- [Cults3D](https://cults3d.com/) - Free & paid models; Designer revenue share (80%); EUR pricing
- [GrabCAD](https://grabcad.com/library) - Engineering CAD library; Free; SolidWorks, STEP, IGES formats
- [MakerWorld](https://makerworld.com/) - Bambu Lab platform; Free; Auto-slicer profiles; Multi-color focus
- [MyMiniFactory](https://www.myminifactory.com/) - Curated platform; "Guaranteed Printable"; Free & paid
- [Printables](https://www.printables.com/) - Prusa-operated; Free & paid; Contests with rewards
- [Thangs](https://thangs.com/) - Geometric search engine; Free & Premium tiers; 3D search API
- [Thingiverse](https://www.thingiverse.com/) - Free models; MakerBot-owned; Customizer app

### Additional Repositories

- [Pinshape](https://www.pinshape.com/) - Ultimaker-owned; Free & paid; MakerBot Customizer integration
- [YouMagine](https://www.youmagine.com/) - Open-source; Ultimaker-operated; CC licensing
- [MakerRepo](https://makerrepo.io/) - Community repository; Free models
- [NexPrint](https://nexprint.io/) - Elegoo platform; Integrated with printers
- [PrintPal](https://printpal.io/) - AI-assisted platform; Model generation
- [Redpah](https://redpah.com/) - Search engine; Aggregates multiple platforms
- [Repables](https://www.repables.com/) - Community-driven; Open-source focus

### Search Engines & Aggregators

- [yeggi](https://www.yeggi.com/) - 3D model search engine; Aggregates multiple sources
- [STLFinder](https://www.stlfinder.com/) - 3D model search; Multiple sources

### Self-Hosted Solutions

- [Manyfold](https://manyfold.app/) - Self-hosted library manager; Ruby on Rails; Organize & tag models; (MIT)
- [Stl-thumb](https://github.com/unlimitedbacon/stl-thumb) - CLI thumbnail generator; (MIT)

---

## Online Tools & Utilities

Web-based and desktop utilities for 3D printing workflows.

### Model Generators & Parametric Tools

- [Parametric Boxes (OpenSCAD)](https://www.openscad.org/) - Generate custom boxes; Script-based
- [Boltify](https://boltify.vercel.app/) - Online bolt & nut generator; M2-M20; Browser-based
- [Lithophane generators](https://lithophanemaker.com/) - Photo to 3D; Multiple tools available
- [Terrain2STL](https://www.jdawg.co.uk/terrain2stl/) - Map data to terrain; GPS coordinates; Global coverage
- [Calibration Models](https://github.com/all3dp/Calibration-Models) - Tolerance, temperature, retraction tests
- [AmeraLabs Town](https://ameralabs.com/) - Resin calibration test; Detailed miniature
- [Benchy](https://www.benchy.com/) - 3DBenchy; Standardized calibration model; Boat shape
- [Tolerance Test](https://www.printables.com/model/68523) - Clearance & fit testing
- [Heatset Insert Master](https://www.printables.com/model/285401) - Threaded insert sizing guide
- [Swiss Cheese Cube](https://www.printables.com/model/570510) - Extrusion & retraction calibration
- [10M Test](https://www.printables.com/model/799581) - Mini 10-minute calibration print

### G-code Viewers & Analyzers

- [gcode.ws](https://gcode.ws/) - Online G-code visualizer; Layer-by-layer analysis; Free
- [GCode Analyzer](https://github.com/machineagency/gcode-analyzer) - Python; Command-line; Open-source
- [Pronterface](https://github.com/kliment/Printrun) - G-code sender; Visualization; Part of PrintRun
- [Cura G-code Viewer](https://marketplace.ultimaker.com/app/cura/plugins/mfield/gcodeviewer) - Cura plugin

### Mesh Repair & Optimization

- [Microsoft 3D Builder](https://apps.microsoft.com/detail/9wzdncrfj3t6) - Windows only; Automatic repair; Export to STL/3MF/OBJ
- [Netfabb](https://www.autodesk.com/products/netfabb) - Professional mesh repair; Free basic version; Simulation tools
- [Admesh](https://github.com/admesh/admesh) - CLI STL repair; Open-source; STL analysis; (GPL)
- [Blender 3D Print Toolbox](https://docs.blender.org/manual/en/latest/addons/object/3d_print_toolbox.html) - Built-in addon; Non-manifold, thickness, volume checks
- [Meshmixer](https://www.meshmixer.com/) - Make Solid function; Automatic repair
- [FixMyPrint](https://fixmyprint.io/) - Web-based STL repair; Free tier

### Filament & Print Management

- [Spoolman](https://github.com/Donkie/Spoolman) - Spool inventory management; REST API; Docker; (MIT)
- [Filameter](https://github.com/nicocodori/filameter) - Filament usage tracking; ESP32-based hardware; (MIT)
- [Filwiz](https://filwiz.com/) - Filament database; Color matching
- [Filament Profiles Hub](https://filamentprofiles.io/) - Community slicer profiles

### Cost Calculators

- [3D Print Cost Calculator](https://calc3dprint.com/) - G-code parsing; Material, time, failure, depreciation, labor costs
- [Prusa Print Cost Calculator](https://blog.prusa3d.com/3d-printing-price-calculator_38905/) - Material cost estimation
- [3DSPRO Cost Calculator](https://3dspro.com/resources/blog/3d-printing-cost-calculators) - Service pricing comparison
- [Volaryx](https://volaryx.com/) - Instant quote generator for print services

### Model Conversion & Transformation

- [CADProps](https://www.cadprops.com/tools/step-to-stl/) - Proprietary browser-based STEP/STP-to-STL mesh converter; sign-in required for conversion.
- [Image to Lithophane](https://lithophanemaker.com/) - Multiple online converters
- [STL to G-code Online](https://3dconvert.online/) - Browser-based conversion
- [SVG to 3D](https://github.com/peterspackman/openscadsvgconverter) - OpenSCAD-based; Script
- [Vectiler](https://github.com/vectileshp/vectiler) - Vector map to 3D; QGIS integration; (MIT)

### Cloud Platforms

- [SelfCAD Online](https://www.selfcad.com/) - Browser CAD + slicer integrated

---

## AI & Generative Design Tools

AI/ML-powered tools for 3D model generation, optimization, and print management.

### Text/Image-to-3D AI Generators

- [Meshy AI](https://www.meshy.ai/) - Text/image to 3D; PBR textures; OBJ/FBX/GLB export; Free tier (200 credits/month)
- [Tripo AI](https://www.tripo3d.ai/) - Text/image to 3D; Print-ready export; Free tier (600 credits/month)
- [Luma AI (Genie)](https://lumalabs.ai/genie) - Text-to-3D; NeRF & Gaussian Splatting; Free tier
- [CSM AI](https://www.csm.ai/) - Image to 3D; Common Sense Machines; REST API
- [Kaedim](https://www.kaedim3d.com/) - 2D to 3D conversion; Human-in-the-loop; Paid
- [Rodin](https://hyperhuman.deemos.com/rodin) - Text/image to 3D; HyperHuman; Research preview

### Open-Source AI Models

- [Point-E](https://github.com/openai/point-e) - OpenAI; Point cloud generation; PyTorch; (MIT)
- [Shap-E](https://github.com/openai/shap-e) - OpenAI; Text/image to 3D; (MIT)
- [DreamFusion](https://dreamfusion3d.com/) - Google Research; Text-to-3D via NeRF; Research code
- [Zero-1-to-3](https://github.com/cvlab-columbia/zero-1-to-3) - Single image to 3D; Columbia University
- [Stable Diffusion 3D](https://github.com/ashawkey/stable-dreamfusion) - Community implementation

### AI-Assisted CAD & Optimization

- [Autodesk Fusion 360 Generative Design](https://www.autodesk.com/products/fusion-360/features/generative-design) - Cloud-based optimization; Manufacturing constraints; Subscription
- [nTopology (nTop)](https://www.ntopology.com/) - Implicit modeling; Lattice structures; Enterprise pricing
- [Ansys Discovery](https://www.ansys.com/products/3d-design) - Real-time simulation; Generative tools; Subscription

### AI Print Monitoring

- [Obico](https://www.obico.io/) - ML-based failure detection; 95%+ accuracy; Open-source core; Free tier
- [PrintSyst AI](https://printsyst.ai/) - Print optimization; Quality prediction
- [Canny AI](https://canny.ai/) - Print quality analysis; Defect prediction

---

## On-Demand 3D Printing Services

Professional services for outsourcing 3D prints.

### General Services

- [Shapeways](https://www.shapeways.com/) - Reopened 2024; Nylon, resin, metal; Marketplace
- [Sculpteo](https://www.sculpteo.com/) - FDM, SLA, SLS, MJF; Instant quoting; France/USA
- [Craftcloud](https://craftcloud3d.com/) - Price comparison; Multiple vendors; All3DP-operated
- [JLCPCB 3D Printing](https://3d.jlcpcb.com/) - FDM, SLA; Low-cost prototyping; China-based
- [Hubs](https://www.hubs.com/) - Formerly 3D Hubs; Distributed network; Digital manufacturing

### Industrial & Specialty

- [Beamler](https://www.beamler.com/) - Service matching; Industrial vendors
- [Materialise](https://www.materialise.com/) - i.materialise consumer; Medical & aerospace
- [Murtfeldt Additive Solutions](https://www.murtfeldt.com/) - Industrial AM; Germany
- [RapidObject](https://rapidobject.com/) - Prototyping; Low-volume production
- [Vikings](https://vikings3d.com/) - On-demand printing; Multiple technologies
- [i.materialise](https://i.materialise.com/) - Consumer-facing; Precious metals

### Local & Marketplace

- [Treatstock](https://www.treatstock.com/) - Local vendor matching; Free
- [Jiga](https://jiga.co/) - Manufacturing marketplace; RFQ system
- [Microscape](https://microscape.io/) - Micro-manufacturing; Small batches
- [iGo3D](https://igo3d.net/) - Service marketplace; Europe-focused

---

## Marketplaces & Price Comparison

- [Craftcloud](https://craftcloud3d.com/) - Instant quotes; 20+ vendors; Material & technology filter
- [3YOURMIND](https://www.3yourmind.com/) - Enterprise software; Price comparison; DFM analysis
- [Treatstock](https://www.treatstock.com/) - Local services; Price comparison; Free
- [Jiga](https://jiga.co/) - RFQ marketplace; DFM feedback; Lead time tracking
- [Xometry Instant Quote](https://www.xometry.com/) - Algorithm-based pricing; 30+ materials
- [Protolabs Quote](https://www.protolabs.com/) - Automated quoting; Design analysis

---

## Filaments & Materials

Information about filament and resin materials for 3D printing.

### Filament Manufacturers

- [3DJake](https://www.3djake.com/) - ecoPLA, technical filaments (Austria)
- [Bambu Lab](https://bambulab.com/en/filament) - PLA, PETG, TPU, PA; RFID-tagged (China)
- [ColorFabb](https://colorfabb.com/) - PLA/PHA, XT, nGen, composites (Netherlands)
- [Devil Design](https://www.devil-design.eu/) - PLA, PETG, Silk, Matte (Poland)
- [eSun](https://www.esun3d.com/) - PLA+, PETG, ABS+, PA (China)
- [Extrudr](https://www.extrudr.com/) - GreenTEC, Bio Fusion (Austria)
- [Fiberlogy](https://fiberlogy.com/) - HD PETG, Easy PETG, PA (Poland)
- [Fillamentum](https://fillamentum.com/) - PLA, PETG, TPU Flexfill (Czech Republic)
- [Hatchbox](https://www.hatchbox3d.com/) - PLA, ABS, PETG, TPU (USA)
- [MatterHackers Build](https://www.matterhackers.com/collections/build-series-filament) - PRO Series PLA, PETG (USA)
- [Overture](https://www.overture3d.com/) - PLA, PETG (USA)
- [Polymaker](https://polymaker.com/) - PolyLite, PolyTerra, PolyMax (Netherlands)
- [Proto-pasta](https://www.proto-pasta.com/) - Carbon fiber, metal, magnetic composites (USA)
- [Prusament](https://www.prusa3d.com/category/filaments/) - PLA, PETG, PC, PA (Czech Republic)
- [SUNLU](https://www.sunlu.com/) - PLA, PETG, TPU, Silk (China)

### Resin Manufacturers

- [Anycubic](https://www.anycubic.com/collections/resin) - Standard, Plant-based, ABS-like; 405nm (China)
- [Elegoo](https://www.elegoo.com/collections/resin) - Standard, ABS-like, Water-washable, Plant-based; 405nm (China)
- [Formlabs](https://formlabs.com/materials/) - Standard, Engineering, Dental, Medical, Castable; 405nm (USA)
- [LIQCREATE](https://www.liqcreate.com/) - Engineering, Biocompatible, Flexible; 385-420nm (Netherlands)
- [Phrozen](https://phrozen3d.com/collections/resin) - Dental, Mini, Castable, Tough; 405nm (Taiwan)
- [Siraya Tech](https://sirayatech.com/) - Tenacious, Fast, Blu; 405nm (USA)

### Material Properties Reference

- **PLA** - Nozzle: 190-220°C; Bed: 0-60°C; Enclosure: No; Hygroscopic: Moderate
- **PETG** - Nozzle: 230-250°C; Bed: 70-85°C; Enclosure: No; Hygroscopic: Moderate
- **ABS** - Nozzle: 230-260°C; Bed: 90-110°C; Enclosure: Yes; Hygroscopic: Low
- **ASA** - Nozzle: 230-250°C; Bed: 90-110°C; Enclosure: Yes; Hygroscopic: Low
- **TPU** - Nozzle: 220-250°C; Bed: 40-60°C; Enclosure: No; Hygroscopic: Low
- **Nylon (PA)** - Nozzle: 240-270°C; Bed: 70-90°C; Enclosure: Yes; Hygroscopic: High
- **PC (Polycarbonate)** - Nozzle: 260-310°C; Bed: 90-120°C; Enclosure: Yes; Hygroscopic: Moderate
- **PVA** - Nozzle: 180-210°C; Bed: 45-60°C; Enclosure: No; Hygroscopic: Very High (water-soluble)
- **HIPS** - Nozzle: 230-250°C; Bed: 90-100°C; Enclosure: Yes; Hygroscopic: Low (dissolves in limonene)
- **Carbon Fiber-filled** - Nozzle: 240-270°C; Bed: 70-90°C; Enclosure: Recommended; Hygroscopic: Low

### Resin Properties Reference

- **Standard** - Wavelength: 405nm; Exposure: 2-8s; Post-cure: 30-60min; Use: Prototyping, miniatures
- **ABS-like** - Wavelength: 405nm; Exposure: 1.5-6s; Post-cure: 30-60min; Use: Functional parts
- **Water-washable** - Wavelength: 405nm; Exposure: 2-8s; Post-cure: 20-30min; Use: Hobby applications
- **Flexible** - Wavelength: 405nm; Exposure: 2.5-10s; Post-cure: 60min; Use: Gaskets, seals
- **Castable** - Wavelength: 405nm; Exposure: 2.5-8s; Post-cure: 30min; Use: Jewelry, investment casting
- **Dental** - Wavelength: 405nm; Exposure: 1.5-6s; Post-cure: 30-60min; Use: Surgical guides, models
- **Engineering** - Wavelength: 385-420nm; Exposure: 2-10s; Post-cure: 60-120min; Use: High-stress parts

### Filament Storage Specifications

- **Active Drying (PLA)** - 45-55°C for 4-12 hours before printing
- **Active Drying (Nylon)** - 65-80°C for 12+ hours; Nylon absorbs moisture rapidly
- **Passive (Desiccant)** - Room temperature with silica gel; Lasts weeks to months
- **Sealed Storage** - Vacuum bags with desiccant; Lasts months to years
- **Heated Dry Box** - 40-55°C continuous; Can print during drying

---

## Post-Processing Tools & Guides

### Washing & Curing (Resin)

- [Anycubic Wash & Cure](https://www.anycubic.com/collections/wash-cure-machine) - Wash & Cure 2.0, 3 Plus
- [Elegoo Mercury](https://www.elegoo.com/collections/wash-cure) - Mercury (2L), Mercury Plus (4.5L); 405nm UV
- [Formlabs Form Cure](https://formlabs.com/accessories/form-cure/) - 405nm LEDs; N2 inerting optional
- [Formlabs Form Wash](https://formlabs.com/accessories/form-wash/) - Automated agitation; IPA recycling
- [Prusa CW1S](https://shop.prusa3d.com/accessories/720-original-prusa-curing-and-washing-machine-cw1.html) - Curing & washing machine
- [Ultrasonic Cleaner](https://www.amazon.com/s?k=ultrasonic+cleaner+resin) - 40kHz; 1-3L capacity

### Support Removal & Finishing

- **Flush Cutters** - TWP 170, Xuron 170-II, Micro Mark; Clean cuts
- **Deburring Tools** - Noga, Arc Tools; Edge cleanup
- **Files & Rasps** - Metal files; Needle files for detail
- **Dremel / Rotary Tools** - 3000, 4000, 8220 models; Sanding, grinding, polishing
- **Heat Gun** - Annealing PLA/ABS; 100-200°C; Surface hardening

### Sanding & Smoothing

- **Sandpaper** - 80, 120, 240, 400, 600, 1000, 2000 grit progression
- **Sanding Sponges** - 3M; Contoured surfaces
- **XTC-3D](https://www.smooth-on.com/products/xtc-3d) - Epoxy resin coating; 2-part mix; Smooths layer lines
- **Primer Fillers** - Rust-Oleum, Tamiya Fine Surface Primer; Spray application
- [Mr. Hobby Surfacer](https://www.mr-hobby.com/en/products2/category_1/36.html) - 500, 1000, 1200 grit; Brush/spray
- [Vallejo Plastic Putty](https://www.vallejoespain.com/) - Gap filling; Water-based

### Painting & Finishing

- **Acrylic Paints** - Vallejo Model Color, Citadel, Apple Barrel; Brush & airbrush
- **Spray Paint** - Krylon, Rust-Oleum, Tamiya; Primer, color, clear
- **Airbrush Kits** - Badger, Iwata, Master; 0.2-0.5mm nozzles
- **Clear Coat / Sealer** - Matte (Testors), Satin (Krylon), Gloss (Mr. Hobby)
- **Epoxy Resin Coating** - ArtResin, XTC-3D; Glossy smooth finish
- [Prince August](https://www.princeaugust.be/) - Airbrush paints; 17ml, 60ml bottles
- [Badger Air-Brush](https://www.badgerairbrush.com/) - Patriot, Renegade, Krome airbrushes

### Assembly & Bonding

- **CA Glue (Cyanoacrylate)** - Starbond, Bob Smith; Thin (0.002"), medium, thick (gel)
- **Epoxy** - J-B Weld, Gorilla; 5-min, 30-min cure
- **Plastic Cement** - Tamiya Extra Thin; Capillary action; ABS/PS only
- **Model Putty** - Tamiya Putty, Milliput; Gap filling
- **Acetone** - ABS welding & smoothing; Vapor smoothing applications
- [Bondic](https://www.bondic.io/) - UV-cured liquid plastic; Gap filling

### Measurement & Calibration

- [Digital Calipers](https://www.mitutoyo.com/) - Mitutoyo 500-196-30; 0-150mm; 0.01mm resolution
- [Neoteck Calipers](https://www.amazon.com/s?k=neoteck+calipers) - Digital calipers
- **Feeler Gauge** - Bed leveling; 0.05-0.20mm range
- **Dial Indicator** - Bed tramming; 0-10mm range; Magnetic base
- **IR Thermometer** - Bed & nozzle temp verification; -50 to 400°C

### Resin Safety Equipment

- [Nitrile Gloves](https://www.amazon.com/s?k=nitrile+gloves+resin) - 4-8 mil thickness; Powder-free
- [Respirator](https://www.amazon.com/s?k=respirator+organic+vapor) - 3M 6000 series; Organic vapor cartridges
- [Safety Goggles](https://www.amazon.com/s?k=safety+goggles+resin) - Splash protection; Anti-fog
- [Resin Filters](https://www.amazon.com/s?k=resin+filter+funnel) - Paper filters; Reuse uncured resin
- [Resin Traps](https://www.printables.com/model/257625-resin-trap) - Wash station catch
- [Waste Resin Containers](https://www.amazon.com/s?k=resin+waste+container) - UV-proof; Proper disposal

---

## Troubleshooting Guides

### Comprehensive Guides

- [All3DP Troubleshooting](https://all3dp.com/2/3d-printing-problems-troubleshooting-fixes/) - Visual wizard; Step-by-step
- [Cheat Sheet](https://www.matterhackers.com/articles/3d-printer-failure-fixer) - Quick-reference; Printable PDF
- [MatterHackers Troubleshooting](https://www.matterhackers.com/articles/common-3d-print-problems) - Visual identification; Solutions
- [NinjaTek Troubleshooting](https://ninjatek.com/support/troubleshooting-guide/) - Flexible material focus; General issues
- [Prusa Help Center](https://help.prusa3d.com/category/common-problems) - First layer, temperature, material-specific guides
- [Simplify3D Visual Guide](https://www.simplify3d.com/support/print-quality-troubleshooting) - Symptom-based; Print samples

### Common Issues & Technical Solutions

| Issue | Root Causes | Solutions |
|-------|-------------|-----------|
| **Bed Adhesion Failure** | Unclean bed, incorrect Z-offset, warped bed, wrong temp | Clean with IPA, re-level, adjust Z-offset (0.05-0.15mm), use adhesive (glue stick, PEI) |
| **Warping** | Rapid cooling, poor adhesion, material shrinkage | Enclose printer, use brim/raft, reduce fan speed, increase bed temp 5-10°C |
| **Stringing / Oozing** | Retraction disabled/insufficient, high temp, moist filament | Enable retraction (5-7mm Bowden, 0.5-2mm direct), lower temp 5-10°C, dry filament |
| **Under-extrusion** | Clogged nozzle, incorrect flow, wrong filament diameter, low temp | Clear nozzle (cold pull), calibrate flow (95-105%), verify diameter (1.65-1.80mm), increase temp |
| **Over-extrusion** | Wrong flow rate, incorrect E-steps, slicer error | Reduce flow (90-100%), calibrate E-steps, verify slicer filament settings |
| **Layer Shifting** | Loose belts, high speed/acceleration, mechanical binding | Tighten belts (110Hz tension), reduce speed 10-20%, check pulleys, lubricate rails |
| **Ghosting / Ringing** | Vibration, high acceleration, loose frame | Enable Input Shaping (Klipper), reduce accel (500-3000mm/s²), tighten frame |
| **Elephant Foot** | First layer squished, bed too hot, weight on print | Increase Z-offset (0.05mm), lower bed temp 5°C, add chamfer in CAD |
| **Clogged Nozzle** | Debris, heat creep, worn nozzle, carbon buildup | Cold pull (240→90°C), replace nozzle (0.4mm standard), check part cooling |
| **Layer Delamination** | Low temp, drafts, contaminated filament | Increase temp 5-10°C, enclose printer, dry filament, reduce fan |
| **Blobbing / Zits** | Retraction settings, coasting disabled, travel moves | Enable coasting (0.2-0.8mm), adjust retraction, enable "Avoid Crossed Walls" |
| **Resin Print Failures** | Wrong exposure, FEP worn, resin old, supports insufficient | Exposure test (2-8s), replace FEP (0.1-0.2mm), use fresh resin, add supports |

### Calibration Procedures

- [Teaching Tech Calibration](https://teachingtechyt.github.io/calibration.html) - Comprehensive guide; Steps, models, interpretation
- [Flow Rate Calibration](https://teachingtechyt.github.io/calibration.html#flow) - Print 20-100% blocks; Measure actual vs expected; Adjust flow multiplier
- [Retraction Calibration](https://teachingtechyt.github.io/calibration.html#retraction) - Test 0.2mm increments; 1-7mm range; Find minimum stringing
- [Temperature Tower](https://www.thingiverse.com/thing:2965178) - 5°C increments per section; Evaluate bridging, stringing, strength
- [E-Steps Calibration](https://all3dp.com/2/calibrate-e-steps-esteps) - Mark filament 120mm from extruder; Extrude 100mm; Measure actual; Calculate: `New E-steps = (100 / actual) × current E-steps`
- [Klipper Input Shaper](https://www.klipper3d.org/Resonance_Compensation.html) - ADXL345 accelerometer; Resonance test; Auto-calibration
- [Pressure Advance](https://www.klipper3d.org/Pressure_Advance.html) - Klipper-specific; Square tower test; Optimize corners
- [Linear Advance](https://marlinfw.org/docs/configuration/LinearAdvance.html) - Marlin-specific; K-factor 0-2; Pattern test
- [PID Autotune](https://marlinfw.org/docs/gcode/Gcode/M303.html) - `M303 E0 S200 C8` (hotend); `M303 E-1 C8 S60` (bed); Save with `M500`

---

## Learning Resources & Tutorials

### Beginner-Focused

- [Prusa Knowledge Base](https://help.prusa3d.com/) - 200+ articles; Assembly, first print, troubleshooting; Multi-language
- [MatterHackers Learn](https://www.matterhackers.com/learn) - 3D Printing 101; Material guides; Printer setup
- [All3DP Guides](https://all3dp.com/1/3d-printing-wiki-3d-printer-3d-printing-explained/) - Technology comparisons; Buying guides
- [Teaching Tech](https://teachingtechyt.github.io/) - Calibration models; Klipper guides; Open-source
- [Instructables 3D Printing](https://www.instructables.com/workshop/3d-printing/) - Community projects; Step-by-step; Photos
- [Reddit 3D Printing Wiki](https://www.reddit.com/r/3Dprinting/wiki/index) - Community-curated; Beginner resources
- [Maker's Muse Academy](https://makersmuse.com.au/) - Structured courses; Design for 3D printing

### Advanced & Technical

- [Klipper Documentation](https://www.klipper3d.org/Overview.html) - Configuration reference; Kinematics; Tuning procedures
- [Marlin Documentation](https://marlinfw.org/docs/) - Configuration.h reference; G-code list; Feature guides
- [CNC Cookbook 3D Printing](https://www.cnccookbook.com/3d-printing/) - Engineering analysis; Speeds & feeds; Cost calculators
- [Thomas Sanladerer Videos](https://www.youtube.com/c/ThomasSanladerer) - Scientific testing; Material analysis; Technical reviews
- [MatterHackers Advanced Guide](https://www.matterhackers.com/articles/3d-printing-101) - Multi-material; Engineering materials

### CAD & Design Tutorials

- [Tinkercad Learn](https://www.tinkercad.com/learn) - Official tutorials; 30min-2hr lessons; Progressive difficulty
- [FreeCAD Documentation](https://www.freecad.org/docs.php) - Manual; Workbench guides; Python scripting
- [Product Design Online (Fusion 360)](https://www.youtube.com/playlist?list=PLTJjA__n8n_Rm9nT0D2a2MqNN6K3D0x4Q) - 40+ lessons; Parametric design; Assemblies
- [Maker's Muse Tutorials](https://www.youtube.com/c/MakersMuse) - Design for FDM/SLA; Tolerances; Functional parts
- [OpenSCAD Manual](https://en.wikibooks.org/wiki/OpenSCAD_User_Manual) - Wikibooks; Functions; Modules; Examples
- [SolidWorks Tutorials](https://help.solidworks.com/) - Official; Part, assembly, drawing; Certification prep

---

## Communities & Forums

### Reddit

- [r/3Dprinting](https://www.reddit.com/r/3Dprinting/) - 2M+ members; General discussion; Showcase; Help
- [r/FixMyPrint](https://www.reddit.com/r/FixMyPrint/) - Troubleshooting; Photo-based diagnosis; Solutions
- [r/functionalprint](https://www.reddit.com/r/functionalprint/) - Practical applications; Engineering focus
- [r/BambuLab](https://www.reddit.com/r/BambuLab/) - Bambu printer owners; Tips, mods, troubleshooting
- [r/PrusaPrinters](https://www.reddit.com/r/PrusaPrinters/) - Prusa community; Support; Showcase
- [r/klippers](https://www.reddit.com/r/klippers/) - Klipper firmware; Configuration help; Showcase
- [r/resinprinting](https://www.reddit.com/r/resinprinting/) - SLA/DLP/LCD; Safety; Post-processing
- [r/voroncorexy](https://www.reddit.com/r/voroncorexy/) - Voron builders; Build logs; Troubleshooting
- [r/ENDER3](https://www.reddit.com/r/ENDER3/) - Ender 3 owners; Mods; Upgrades
- [r/3Dprintmyminis](https://www.reddit.com/r/3Dprintmyminis/) - Miniature printing; Painting; Tabletop
- [r/3Ddesign](https://www.reddit.com/r/3Ddesign/) - CAD discussion; Software help; Critiques
- [r/AdditiveManufacture](https://www.reddit.com/r/AdditiveManufacture/) - Industrial AM; Metal printing; Research

### Discord Servers

- [Klipper Discord](https://discord.klipper3d.org/) - 50k+ members; Configuration help; Development discussion
- [Voron Design Discord](https://discord.gg/voron) - Official Voron; Build support; Part sourcing
- [OctoPrint Discord](https://discord.octoprint.org/) - Plugin development; Troubleshooting
- [MakerWorld Discord](https://discord.gg/makerworld) - Bambu ecosystem; Model sharing
- [3D Printing General](https://discord.gg/3dprinting) - r/3Dprinting official; General help
- [OrcaSlicer Discord](https://discord.gg/orcaslicer) - OrcaSlicer development; Bug reports
- [Mainsail Discord](https://discord.gg/mainsail) - Mainsail UI support; Development

### Forums

- [RepRap Forums](https://forums.reprap.org/) - Founded 2006; Hardware, firmware, software; Historical archive
- [3D Print Board](https://3dprintboard.com/) - General discussion; Reviews; Troubleshooting
- [Facebook Groups](https://www.facebook.com/groups/3dprintingforbeginnersandpros/) - 3D Printing for Beginners (100k+); Regional groups
- [Makers Muse Community](https://makersmuse.com.au/) - Courses; Forum; Challenges

### Maker Platforms

- [Instructables](https://www.instructables.com/) - Step-by-step guides; 3D printing category; Contests

### Industry & Professional

- [3D Printing Industry Forum](https://3dprintingindustry.com/forum/) - Business & technology; Market analysis
- [AMUG Forum](https://amug.com/) - Additive Manufacturing Users Group; Best practices
- [TCT Connect](https://www.tctmagazine.com/) - Industry news; Events; Webinars

---

## YouTube Channels

Educational and technical YouTube channels focused on 3D printing.

- [3D Printing Industry](https://www.youtube.com/c/3DPrintingIndustry) - Market analysis, news
- [3D Printing Nerd](https://www.youtube.com/c/3DPrintingNerd) - Printer reviews, industry coverage
- [All3DP](https://www.youtube.com/c/All3DP) - Reviews, guides
- [Chep](https://www.youtube.com/c/CheapCheapKookyCheap) - Budget builds, Klipper configuration
- [CNC Kitchen](https://www.youtube.com/c/CNCKitchen) - Engineering analysis, material testing
- [Dylan Kossack](https://www.youtube.com/@DylanKossack) - Resin printing guides, troubleshooting
- [Maker's Muse](https://www.youtube.com/c/MakersMuse) - Design for 3D printing, tolerances, functional parts
- [Teaching Tech](https://www.youtube.com/c/TeachingTech) - Calibration guides, Klipper tutorials, firmware
- [The 3D Printing Show](https://www.youtube.com/@The3DPrintingShow) - Industry insights
- [The Miniatures Department](https://www.youtube.com/c/TheMiniaturesDepartment) - Miniature printing, painting
- [Thomas Sanladerer](https://www.youtube.com/c/ThomasSanladerer) - Scientific testing, material analysis
- [Voron Design](https://www.youtube.com/c/VoronDesign) - Voron build guides, design updates

---

## Books, Magazines & Publications

### Magazines


### Books

- [3D CAD Modeling](https://www.elsevier.com/books/3d-cad-modeling/9780128144330) - CAD theory; Parametric design; 2019
- [3D Printing for Dummies](https://www.dummies.com/book/technology/3d-printing/3d-printing-for-dummies-243748) - 3rd Edition; Beginner guide; 2023
- [Additive Manufacturing Handbook](https://www.taylorfrancis.com/books/additive-manufacturing-handbook) - 3rd Edition; Comprehensive reference; 2021
- [Practical 3D Printing](https://www.oreilly.com/library/view/practical-3d-printing/9781491976765/) - O'Reilly; Project-based; 2018
- [The 3D Printing Handbook](https://www.3dhubs.com/3d-printing-book) - Ben Redwood, et al.; Technology, design, applications; 2017

### News & Publications

- [3D Printing Industry](https://3dprintingindustry.com/) - Daily news; Market analysis; Material announcements
- [All3DP](https://all3dp.com/) - Reviews; Guides; Price comparisons; Buyer's guides
- [TCT Magazine](https://www.tctmagazine.com/) - Additive manufacturing; Industry trends; Quarterly
- [3DPMN](https://3dprintpmn.com/) - 3D Printing Media Network; News; Reviews
- [The Next Layer](https://thenextlayer.com/) - Industry insights; Technology analysis

---

## Events & Conferences

### Global Events

- [Additive Manufacturing Strategies](https://additivemanufacturingstrategies.com/) - New York, USA; February; Business focus
- [AMUG Conference](https://amug.com/) - Additive Manufacturing Users Group; April/May; USA
- [Formnext](https://www.formnext.de/) - AM trade fair; Frankfurt, Germany; November
- [RAPID + TCT](https://www.rapid3devent.com/) - AM event; Detroit, USA; May
- [TCT Asia](https://www.tctasia.com.cn/) - Shanghai, China; May
- [TCT Japan](https://www.tctjapan.com/) - Tokyo, Japan; February

### Regional Events

- [3D Printshow London](https://www.3dprintshow.com/) - London, UK
- [Advanced Engineering](https://www.advancedengineering.co.uk/) - UK engineering; AM category
- [EMO Hannover](https://www.emo-hannover.com/) - Metalworking; AM section; Biennial
- [IMTS](https://www.imts.com/) - International Manufacturing Technology Show; Chicago, USA; September
- [Southern Manufacturing Show](https://www.southernmanufacturing.co.uk/) - UK manufacturing; 3D printing section

---

## 3D Printing Technologies

ASTM F42/ISO 52900 standardized additive manufacturing categories.

### Material Extrusion

- **FDM/FFF** (Fused Deposition Modeling / Fused Filament Fabrication) - Thermoplastic filament extruded through heated nozzle; 0.05-0.4mm layer height; Hobby/prosumer technology
- **CFM** (Continuous Fiber Manufacturing) - Continuous carbon/glass fiber reinforcement; Markforged, Anisoprint; High strength-to-weight
- **BAAM** (Big Area Additive Manufacturing) - Pellet extrusion; 5-50mm layer height; Large-scale (ORNL, Cincinnati Inc)
- **Composite Extrusion** - Short fiber-filled filaments (CF, GF, Kevlar); Increased stiffness

### Vat Photopolymerization

- **SLA** (Stereolithography) - UV laser cures liquid resin point-by-point; 25-100μm layers; 3D Systems patent expired 2004
- **DLP** (Digital Light Processing) - Digital projector cures entire layer simultaneously; Texas Instruments DLP chips; 25-100μm
- **LCD/MSLA** (Masked SLA / Mono LCD) - LCD screen masks UV light; 405nm LEDs; 0.01-0.05mm XY resolution; Resin technology
- **LSA** (Laser SLA) - Galvo-based laser curing; Formlabs LFS (Low Force SLA); 25μm layers

### Powder Bed Fusion

- **SLS** (Selective Laser Sintering) - CO₂ laser sinters nylon powder; 0.1mm layers; No supports needed; Industrial ($10k-200k+)
- **MJF** (Multi Jet Fusion) - HP technology; Inkjet fusing & detailing agents; IR curing; High throughput; Industrial
- **DMLS/SLM** (Direct Metal Laser Sintering / Selective Laser Melting) - Fiber laser melts metal powder; 20-60μm layers; Inert gas chamber; $100k-1M+
- **EBM** (Electron Beam Melting) - Electron beam melts metal powder; Vacuum chamber; Arcam/GE; Titanium alloys
- **Binder Jetting (Metal)** - Liquid binder bonds metal powder; Debinding & sintering required; Desktop Metal, ExOne

### Material Jetting

- **PolyJet** - Photopolymer droplets jetted & UV cured; Stratasys; Multi-material & color; 16μm layers
- **Nano Particle Jetting** - Metal/ceramic nanoparticle suspension; XJET; High precision

### Binder Jetting

- **Binder Jetting** - Inkjet printhead deposits binder on powder bed; ExOne, Desktop Metal; Sand, metal, polymer
- **Full-Color Sandstone** - Color binder on gypsum powder; 3D Systems ProJet; CMYK colors

### Directed Energy Deposition

- **DED** (Directed Energy Deposition) - Metal wire/powder + laser/electron beam; Repair & large parts; Relativity Space, Optomec

### Sheet Lamination

- **LOM** (Laminated Object Manufacturing) - Paper/plastic sheets bonded & cut; Mcor (discontinued)
- **UAM** (Ultrasonic Additive Manufacturing) - Metal foil bonded ultrasonically; Fabrisonic

### Emerging & Research

- **CLIP** (Continuous Liquid Interface Production) - Oxygen-permeable window; Continuous curing; Carbon3D; 25-100μm
- **Volumetric 3D Printing** - Holographic light patterns; Entire part cured simultaneously; Research stage (UC Berkeley, Lawrence Livermore)
- **Bio-printing** - Living cell deposition; Hydrogel bio-ink; Medical research; Organovo, CELLINK
- **Concrete 3D Printing** - Cement extrusion; Construction scale; ICON (Vulcan), WASP (Crane)
- **Food Printing** - Edible materials; Chocolate, pasta, dough; BYFlow, Natural Machines
- [Scientific Overview](https://iopscience.iop.org/article/10.1088/1757-899X/1249/1/012001) - Comprehensive AM technologies review

---

## Standards & Certification

### ASTM International (ASTM F42)

- [ASTM F42](https://www.astm.org/COMMITTEE/F42.htm) - Committee on Additive Manufacturing
- **ASTM F2792** - Standard terminology for AM
- **ASTM F3049** - Characterizing metal AM systems
- **ASTM F3122** - Evaluating mechanical properties in metal AM
- **ASTM F3302** - Terminology for metal AM

### ISO Standards (ISO/TC 261)

- **ISO/ASTM 52900** - Additive manufacturing — General principles — Terminology
- **ISO/ASTM 52901** - Guide to purchase of AM parts
- **ISO/ASTM 52902** - Test artifacts — Geometric capability assessment
- **ISO/ASTM 52910** - Design guidelines for AM
- **ISO/ASTM 52911-1** - FDM/FFF design guidelines
- **ISO/ASTM 52911-2** - Powder bed fusion design guidelines
- **ISO/ASTM 52915** - AM file format specification (3MF, AMF)

### Certification & Quality

- [NADCAP](https://www.nadcap.org/) - Aerospace AM accreditation
- [FDA Guidelines](https://www.fda.gov/medical-devices/3d-printing-medical-devices) - Medical device AM (USA)
- [CE Marking](https://ec.europa.eu/growth/single-market/ce-marking) - European conformity
- [ISO 9001](https://www.iso.org/iso-9001-quality-management.html) - Quality management for AM production
- [AS9100](https://www.sae.org/standards/content/as9100d/) - Aerospace quality management

---

## Enclosures & Ventilation

Solutions for temperature control, VOC management, and print quality improvement.

### Commercial Enclosures & Filters

- [Alveo3D PrintCase](https://www.alveo3d.com/en/product/printcase/) - Enclosure with integrated HEPA+carbon filter (10-40 m³/h airflow)
- [Alveo3D P3D-R Filter](https://www.alveo3d.com/en/product/filter-particulates-vocs-3d-printer/) - Standalone particulate + VOC filter
- [FNATR Enclosures](https://www.fnatr.com/) - 5-stage HEPA + activated carbon filter enclosures for Bambu Lab printers

### DIY Enclosure Projects

- [IKEA Lack Enclosure](https://all3dp.com/2/ikea-3d-printer-enclosure-tutorial/) - Dual Lack table enclosure with active ventilation mods
- [Activated Carbon Filter for IKEA Lack](https://www.printables.com/model/103481-activated-carbon-filter-for-ikea-lack-enclosure) - 3D printable carbon pellet filter
- [HEPA Particle Filter for IKEA Lack](https://www.thingiverse.com/thing:7035864) - 3D printable HEPA filter mount
- [IKEA Lack Table Connectors](https://cults3d.com/en/3d-model/tool/ikea-lack-tischverbinder-fuer-3d-drucker-einhausungen) - Modular connector parts

### Chamber Heating

- [BambuSauna Chamber Heater](https://makerworld.com/en/models/539096-bambusauna-bambulab-x1c-p1p-p1s-chamber-heater) - Chamber heating for X1C/P1S
- [Creality K1 Max Active Chamber Heating Mod](https://www.amazon.co.uk/Compatible-Creality-Printers-High-Temp-Filament/dp/B0GLWQT13D) - Aftermarket chamber heater (50-70°C)

---

## Calibration & Test Prints

Standardized models and tools for printer tuning and quality assessment.

### Comprehensive Calibration Platforms

- [Teaching Tech Calibration](https://teachingtechyt.github.io/calibration.html) - Step-by-step wizard: E-steps, flow, temperature, retraction, pressure advance, max volumetric speed
- [Ellis' Print Tuning Guide](https://ellis3dp.com/Print-Tuning-Guide/) - Comprehensive Klipper/Marlin/RRF tuning with printable tests
- [All3DP 20 Free Test Print Models](https://all3dp.com/2/best-3d-printer-test-print-3d-models/) - Torture test collection
- [FacFox 15 Torture Test Models](https://facfox.com/docs/kb/3d-printer-test-print-the-top-15-free-torture-test-models) - Curated test models

### Standard Test Models

- [3DBenchy](https://www.3dbenchy.com/) - Original torture test boat (overhangs, bridging, surface finish, dimensional accuracy)
- [AmeraLabs Town](https://www.printables.com/model/237684-ameralabs-town-calibration-for-sla-3d-printers) - SLA/DLP resin calibration (10 criteria)
- [XYZ 20mm Calibration Cube](https://www.thingiverse.com/thing:1278865) - Dimensional accuracy test
- [Tolerance Test](https://www.printables.com/model/68523) - Clearance & fit testing
- [Swiss Cheese Cube](https://www.printables.com/model/570510) - Extrusion & retraction calibration
- [Temperature Tower](https://www.thingiverse.com/thing:2965178) - 5°C increments per section
- [Multi-Type Tolerance Test](https://makerworld.com/en/models/137989-multi-type-tolerance-test) - Multiple gap sizes

### Built-in Calibration Tools

- **OrcaSlicer** - Flow Rate, Pressure Advance (3 methods), Retraction, Temperature Tower, Max Volumetric Speed, Archimedean Chords
- **Klipper** - Input Shaper (ADXL345), Pressure Advance, PID Autotune
- **Marlin** - Linear Advance (K-factor), PID Autotune, Bed Leveling

---

## G-code Tools & Post-Processing

Utilities for G-code editing, optimization, and analysis.

### G-code Viewers & Editors

- [gcode.ws](https://gcode.ws/) - Online G-code visualizer; Layer-by-layer analysis
- [Zupfe GCode Viewer](https://zupfe.velor.ca/) - Online 3D G-code viewer
- [Notepad++](https://notepad-plus-plus.org/) - G-code editing with syntax highlighting
- [CIMCO Edit](https://www.cimco.com/products/cimco-edit/) - Professional editor with 3D backplot

### G-code Optimization

- [Arc Welder (Cura Plugin)](https://marketplace.ultimaker.com/app/cura/plugins/fieldofview/ArcWelderPlugin) - Converts G0/G1 to G2/G3 arcs; Reduces file size ([GitHub](https://github.com/fieldOfView/Cura-ArcWelderPlugin))
- [Arc Welder (OctoPrint Plugin)](https://plugins.octoprint.org/plugins/arc_welder/) - Same functionality for OctoPrint
- [GCODE-Arc-Converter](https://github.com/EdwardChamberlain/GCODE-Arc-Converter) - Python arc conversion script

### Python G-code Libraries

- [PythonicGcodeMachine](https://fabricesalvaire.github.io/pythonic-gcode-machine/) - Python toolkit for RS-274/ISO G-code; GPLv3
- [Gcode-Reader](https://github.com/zhangyaqi1989/Gcode-Reader) - Python G-code visualization & analysis for FDM/Stratasys/PBF
- [pyGCodeDecode](https://github.com/FAST-LB/pyGCodeDecode) - G-code analysis & decoding

### Post-Processing Scripts

- [PrusaSlicer Post-Processing Scripts](https://help.prusa3d.com/article/post-processing-scripts_283913) - Built-in script execution after slicing
- [G-code Post-Processing Scripts](https://github.com/theophile/gcode-postprocessing-scripts) - Collection for PrusaSlicer/SuperSlicer

---

## Print-in-Place & Hinge Design

Design techniques for functional 3D printed mechanisms without assembly.

### Design Guides & Resources

- [Zbotic Print-in-Place Designs Guide](https://zbotic.in/print-in-place-designs-functional-3d-prints-without-assembly/) - Clearance rules, design principles, troubleshooting
- [WhatMakeArt Print-in-Place Hinge Guide](https://whatmakeart.com/digital-fabrication/3d-printing/print-in-place-hinge/) - Bridging gaps for hinge pins
- [Product Design Online: Shapr3D Print-in-Place Tutorial](https://productdesignonline.com/learn-shapr3d-in-10-days-for-beginners-day-3-3d-printable-print-in-place-hinged-box/) - Step-by-step CAD tutorial

### Design Guidelines

- **Clearance gaps**: 0.15-0.20mm for well-tuned FDM; 0.20-0.35mm for average printers
- **Hinge pin diameter**: 0.3-0.6mm smaller than the hole
- **Flange thickness**: Minimum 2x layer height for structural integrity
- **Print orientation**: Horizontal orientation produces best results

---

## Chemical Smoothing & Surface Finishing

Chemical treatments for eliminating layer lines and improving surface quality.

### Chemical-to-Material Mapping

- **ABS + Acetone** - Vapor smoothing; 72-81% roughness reduction
- **ASA + Acetone** - Vapor smoothing; Similar to ABS
- **PLA + Ethyl Acetate** - Surface softening (NOT acetone); Controlled conditions required
- **HIPS + D-Limonene** - Support dissolution & surface treatment
- **PVA/BVOH + Water** - Support dissolution (no smoothing effect)
- **PETG** - No effective chemical smoothing; Requires mechanical finishing

### Smoothing Guides

- [Prusa Blog: Chemical Smoothing Guide](https://blog.prusa3d.com/improve-your-3d-prints-with-chemical-smoothing_36268/) - ABS/ASA + acetone, PLA + ethyl acetate
- [Smith3D: Complete Guide to 3D Print Smoothing](https://www.smith3d.com/complete-guide-to-3d-print-smoothing-acetone-vapor-bath-safety-techniques/) - Full vapor bath guide
- [Siraya Tech: ABS Vapor Smoothing](https://siraya.tech/blogs/news/abs-vapor-smoothing) - Safety-focused guide
- [How to Smooth PLA with Ethyl Acetate](https://3dtrcek.com/en/blog/post/how-to-smooth-pla-prints-for-professional-results) - PLA smoothing alternative

### Finishing Products

- [XTC-3D (Smooth-On)](https://www.smooth-on.com/products/xtc-3d) - Epoxy resin coating for layer line elimination

---

## 3D Printing Safety

Safety equipment, guidelines, and best practices.

### VOC & Particulate Safety

- [Alveo3D: Top 6 Misunderstandings About 3D Printing Emissions](https://www.alveo3d.com/en/top-6-misunderstandings-3d-printing-emissions/) - HEPA vs carbon filter clarification
- [Alveo3D: How to Safely Dispose of Used HEPA Filters](https://www.alveo3d.com/en/how-to-safely-dispose-used-hepa-filters-3d-printers/) - Filter disposal procedure

### Resin Safety & Disposal

- [PAMA Safety Guidelines](https://pama3d.org/) - Photopolymer Additive Manufacturing Alliance (joint with NIST and RadTech)
- [PAMA Resin Handling Guidelines (PDF)](https://radtech.org/archive/images/health-safety/3DPrinterSafetyPoster_revised_11x17.pdf) - UV-curable resin safety poster
- [Zbotic Resin Safety Guide](https://zbotic.in/resin-safety-guide-ventilation-ppe-and-proper-disposal/) - Chemistry, ventilation, PPE, disposal
- [3D Printer Australia: How to Dispose of Resin](https://3dprinteraustralia.com.au/owners-guides/how-to-dispose-of-resin/) - UV curing for disposal

### Fire Safety

- [JLC3DP: 3D Printer Fire Safety Guide](https://jlc3dp.com/blog/3d-printer-fire-safety) - Thermal runaway, fire extinguishers, overnight printing
- [Snapmaker: 3D Printer Fire Safety](https://www.snapmaker.com/blog/3d-printer-fire-safety-causes-prevention-best-practices/) - Causes, prevention, best practices
- [Tom's Hardware: Fix 3D Printer Thermal Runaway](https://www.tomshardware.com/3d-printing/how-to-fix-3d-printer-thermal-runaway) - Diagnostic and fix guide

### Key Safety Requirements

- **Thermal runaway protection** must be enabled in firmware (Marlin: `#define THERMAL_RUNAWAY_PROTECTION`)
- **ABS printing** produces styrene (carcinogen) -- requires ventilation + carbon filtration
- **Resin** must be fully UV-cured before disposal (sunlight exposure for several hours)
- **Used HEPA filters** from resin printers should be sealed in bags before disposal

---

## Multi-Material & Soluble Supports

Resources for multi-material printing and soluble support materials.

### Soluble Support Materials

- [Prusa: Water Soluble BVOH/PVA Guide](https://help.prusa3d.com/article/water-soluble-bvoh-pva_167012) - Printing parameters, drying, dissolution
- [FormFutura BVOH](https://www.formfutura.com/bvoh) - Water-soluble support filament
- [BCN3D BVOH](https://bcn3d.com/product/bvoh-bcn3d-filaments/) - Extended material compatibility
- [Filament2Print Soluble Support Filaments](https://filament2print.com/en/192-support-solubles) - HIPS, PVA, BVOH, chemical-soluble options

### Soluble Support Comparison

- **PVA** - Dissolves in water (room temp); Very hygroscopic; 180-210°C; Best with PLA
- **BVOH** - Dissolves in water (faster than PVA); Less hygroscopic; 200-220°C; Compatible with PETG/Nylon
- **HIPS** - Dissolves in D-Limonene; 230-250°C; Requires enclosure; Best with ABS/ASA

### Multi-Material Management

- [Happy Hare MMU](https://github.com/moggieuk/Happy-Hare) - Advanced MMU/ERCF management for Klipper
- [FilaMan](https://www.filaman.app/) - Filament management with Bambu AMS slot mapping, Spoolman compatibility
- [SpoolmanSync](https://github.com/gibz104/SpoolmanSync) - Auto filament tracking for Bambu AMS synced to Spoolman
- [Spoolman Bambu Status](https://github.com/atownsend247/spoolman-bambu-filament-status) - AMS status sync to Spoolman

---

## Klipper Installation & Management

Tools for installing and managing Klipper firmware.

- [KIAUH (Klipper Installation And Update Helper)](https://github.com/th33xitus/kiauh) - One-script install for Klipper, Moonraker, Mainsail, Fluidd, OctoPrint, KlipperScreen
- [prind](https://github.com/mkuf/prind) - Docker-compose deployment for Klipper, Moonraker, Mainsail/Fluidd
- [KAMP - Klipper Adaptive Meshing & Purging](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging) - Adaptive bed mesh and purge line

---

## Remote Access & Networking

Tools for remote printer management and network access.

- [OctoEverywhere](https://octoeverywhere.com/) - Free remote access to Klipper/OctoPrint; AI failure detection; Webcam streaming
- [Tailscale](https://tailscale.com/) - Zero-config VPN for accessing Mainsail/Fluidd/OctoPrint remotely

---

## Hardware Upgrades & Sensors

Common hardware upgrades for improved print quality.

- [BLTouch / CR Touch](https://www.antclabs.com/) - Auto bed leveling sensors
- [BTT TFT Screens](https://github.com/bigtreetech/BIGTREETECH-TouchScreenFirmware) - Touchscreen displays for standalone control
- [ADXL345 Accelerometer](https://www.bigtreetech.com/) - Input shaping calibration for Klipper
- [TMC2209 Silent Stepper Drivers](https://www.trinamic.com/) - Near-silent stepper operation

---

## Related Awesome Lists

- [awesome-3d-printing](https://github.com/ad-si/awesome-3d-printing) - Original inspiration for this list
- [awesome-fdm-printing](https://github.com/anchorhead/awesome-fdm-printing) - FDM-specific resources
- [awesome-klipper](https://github.com/fschmitt/awesome-klipper) - Klipper firmware resources
- [awesome-maker](https://github.com/digitalhackerspace/awesome-maker) - Maker movement resources
- [awesome-octoprint](https://github.com/octoprint/awesome-octoprint) - OctoPrint plugins & resources
- [awesome-openscad](https://github.com/openscad/awesome-openscad) - OpenSCAD resources
- [awesome-freecad](https://github.com/FreeCAD/FreeCAD-resources) - FreeCAD resources
- [awesome-reprap](https://github.com/mwittig/awesome-reprap) - RepRap ecosystem

---

## Contributing

Contributions are welcome. Please follow these guidelines:

- Ensure the resource is directly relevant to 3D printing
- Verify the resource is currently accessible (working URL)
- Provide a concise, factual description (avoid subjective language like "best", "awesome", "amazing")
- Include technical details where applicable (version numbers, licensing, file formats, specifications)
- Check for duplicates before submitting
- Follow alphabetical ordering within categories
- Use HTTPS links when available

To contribute:
1. Fork the repository
2. Add your resource to the appropriate section
3. Commit with a descriptive message
4. Submit a Pull Request

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This work is dedicated to the public domain under the Creative Commons Zero 1.0 Universal license.

---

*Last updated: April 2026*
