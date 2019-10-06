# GA-B85M-Gaming 3 Pentium G3260 CLOVER

## Specifics

- CPU : Intel® Pentium® Processor G3260 (3M Cache, 3.30 GHz)
- Mainboard : GA-B85M-Gaming 3
- Graphics : 
Intel® HD Graphics for 4th Generation Intel® Processors, GeForce GTX 950
- Sound : Realtek ALC892


## Bios/Clover Bootloader/macOS Version

- Bios : F2
- Clover Bootloader : Above v2.5k
- macOS : 10.13.X


## Bios Setup

- Load Optimized Defaults


## DSDT Patch

- [sys] Add IMEI
- [sys] Fix _WAK Arg0 v2
- [sys] Fix Mutex with non-zero SyncLevel
- [sys] Fix PNOT/PPNT
- [sys] HPET Fix
- [sys] IRQ Fix
- [sys] OS Check Fix (Windows 10)
- [sys] RTC Fix
- [sys] Shutdown Fix
- [sys] Shutdown Fix v2
- [sys] SMBUS Fix


## Drivers64UEFI

- ApfsDriverLoader-64.efi
- AptioMemoryFix-64.efi
- EmuVariableUefi.efi
- FSInject-64.efi
- VBoxHfs-64.efi
- VirtualSmc.efi


## Kexts

- AppleALC.kext
- EFICheckDisabler.kext
- IntelMausiEthernet.kext
- Lilu.kext
- NullCPUPowerManagement.kext
- SMCBatteryManager.kext
- SMCLightSensor.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBPorts.kext    -    Generated with Hackintool
- VirtualSMC.kext
- VoodooTSCSync.kext    -    Generated with VoodooTSCSync Configurator by ITzTravelInTime
- WhateverGreen.kext