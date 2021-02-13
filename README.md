Hardware:
CPU: Intel Core i5 10600
RAM: HyperX Fury 32GB 2666MHz DDR4 CL16 DIMM (Kit of 2)
Motherboard: Gigabyte B460 Auros Pro AC
GPU: Gigabyte Nvidia GT 730 GDDR5
SSD: Samsung Evo plus 250GB Nvme m.2
Wifi/Bluetooth: Intel® Wi-Fi 9260 / Intel Bluetooth 5.0
Case / PSU: CASE Cooler Master Master MB511-TG-W.Power Supply Cooler Master 600W 80+ Elite V4

Bootloader:
Opencore 0.6.6 — iMac 20,1

Installation Steps:
All the required steps are from the official open core guide, please follow it if you need to get the best results, these files only to help you as a simple guide, please use your own if you faced any issues or you have any other hardware.
—

Bios Settings
Disable:
	•	Fast Boot
	•	CSM
	•	Thunderbolt(For initial install, as Thunderbolt can cause issues if not setup correctly)
	•	Intel SGX
	•	Intel Platform Trust
	•	CFG Lock
Enable:
	•	VT-x
	•	Above 4G decoding
	•	Hyper-Threading
	•	Execute Disable Bit
	•	EHCI/XHCI Hand-off
	•	OS type: (Windows 10 Feautres: Ohter)
	•	You can disable iGPU.
———
Needed Drivers:

- OpenCanCopy.efi
- OpenHfsPlus.efi
- OpenRuntime.efi

Kexts:

- Airportltlwm
- AppleAlc
- FakePCIID_Intel_I225-V
- FakePCIID
- IntelBluetoothFirmware
- IntelBluetoothInjector
- Lilu
- NVMeFix ( If you have NVME only )
- RestrictEvents
- SMCProcessor
- SMCSuperIO
- USBPorts
- VirtualSMC
- WhateverGreen

————
All of these steps are from the official open core guide, please follow it if you need to get the best results.

