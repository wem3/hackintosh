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
  
### Hardware
- i7-920 intel CPU
- Gigabyte GA-X58A-UD3R mobo 

