# wem3 hackintosh setup 
 
straightforward, MultiBeast install using MacMan's precompiled DSDTs 

### Dependencies
*fresh OS X 10.9.2 install  
*pre-edited DSDT.aml  
[MultiBeast 6.2](http://www.multibeast.com)  
  
### MultiBeast Build: Frank
UserDSDT pre-configured choices (frank.mb):
- Quick Start -> UserDSDT - frank_mb.DSDT     
- Drivers -> Disk -> 3rd Party SATA
- Drivers -> Disk -> TRIM Enabler > 10.9.x TRIM Patch  
- Drivers -> Misc -> FakeSMC v6.0.1123  
- Drivers -> System -> AppleRTC Patch for CMOS Reset  
- Bootloaders -> Chimera v2.2.1  
- Customize -> Boot Options -> Basic Boot Options  
- Customize -> Boot Options -> Generate CPU States  
- Customize -> Boot Options -> Hibernate Mode - Desktop  
- Customize -> Boot Options -> Use KernelCache  
- Customize -> System Definition -> Mac Pro -> Mac Pro 3,1  
- Customize -> Themes -> tonymacx86 Black  
---

### MultiBeast Build: Frank  
UserDSDT pre-configured choices (carl.mb):
- Drivers > Audio > Realtek ALCxxx > With DSDT > ALC889
- Drivers > Disk > 3rd Party eSATA
- Drivers > Disk > TRIM Enabler > 10.9.x TRIM Patch
- Drivers > Misc > FakeSMC v6.0.1123
- Drivers > Network > Realtek > RealtekRTL81xx v0.0.90
- Drivers > System > Patched AppleIntelCPUPowerManagement > OS X 10.9.0 Drivers > System > AppleRTC Patch for CMOS Reset
- Bootloaders > Chimera v2.2.1
- Customize > Boot Options > Basic Boot Options
- Customize > Boot Options > DropSSDT=Yes
- Customize > Boot Options > Generate CPU States
- Customize > Boot Options > GraphicsEnabler=Yes
- Customize > Boot Options > Hibernate Mode - Desktop
- Customize > Boot Options > IGPEnabler=No
- Customize > Boot Options > Instant Menu
- Customize > Boot Options > PCI Root ID Fix
- Customize > Boot Options > Use KernelCache
- Customize > Boot Options > Verbose Boot
- Customize > System Definitions > Mac Pro > Mac Pro 3,1
- Customize > SSDT Options > Sandy Bridge Core i7
- Customize > Themes > Chameleon 2.2 Default  
---

### Hardware: Frank
- i7-920 intel CPU
- Gigabyte GA-X58A-UD3R mobo 

### Hardware: Carl
- i7 3k(?) intel CPU @ 3.5GHz
- Gigabyte GA-Z68XP-UD4 mobo
