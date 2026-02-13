# Changelog

## 2026-02-13

## Added

Add NVRAM parameters:

- NVRAM: 
	- UUID: `7C436110-AB2A-4BBB-A880-FE41995C9F82`
		- ADD: `bluetoothExternalDongleFailed DATA 00`
		- ADD: `bluetoothInternalControllerInfo DATA 0000000000000000000000000000`

### Changed

Update kexts version to the latest.

- Liu.kext 1.7.0 --> 1.7.1
- VirtualSMC.kext 1.3.6 --> 1.3.7
- SMCLightSensor.kext 1.3.6 --> 1.3.7
- SMCBatteryManager.kext 1.3.6 --> 1.3.7
- SMCSuperIO.kext 1.3.6 --> 1.3.7
- SMCProcessor.kext 1.3.6 --> 1.3.7
- AppleALC.kext 1.9.4 --> 1.9.6
- CpuTscSync.kext 1.1.1 --> 1.1.2
- ECEnabler.kext 1.0.5 --> 1.0.6
- NVMeFix.kext 1.1.2 --> 1.1.3
- RealtekRTL8111.kext 2.5.0 --> 3.0.0
- RestrictEvents.kext 1.1.5 --> 1.1.6
- WhateverGreen.kext 1.6.9 --> 1.7.0
- BlueToolFixup.kext 2.7.0 --> 2.7.1

Update OpenCore to the latest version: 1.0.4 --> 1.0.6.

OpenCore files update:

- OpenCore.efi --> OpenCore.efi
- Drivers/HfsPlus.efi --> Drivers/OpenHfsPlus.efi
- Drivers/OpenCanopy.efi --> Drivers/OpenCanopy.efi
- Drivers/OpenRuntime.efi --> Drivers/OpenRuntime.efi
- Drivers/ResetNvramEntry.efi --> Drivers/ResetNvramEntry.efi
- Tools/OpenShell.efi --> Tools/OpenShell.efi

### Removed

Remove unused kext:

- ACPIBatteryManager.kext
