# OpenCore-EFI-Lenovo-M75q1-Tiny

## Disclaimer

Use at your own risk. I take no responsiblity if your rig explodes. Create unique SMBios values for your rig. Don't copy ones shown in the config.plist!!!

## Kexts

WiFi and Bluetooth drivers are not included. Please add them your self.
https://dortania.github.io/OpenCore-Install-Guide/ktext.html#wifi-and-bluetooth

- AMDRyzenCPUPowerManagement.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- Lilu.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- SMCAMDProcessor.kext
- SMCSuperIO.kext
- USBToolBox.kext
- UTBMap_M75q.kext
- VirtualSMC.kext

## Patch

- AMD Vanilla

## Q&A

- Stuck on boot apple logo
  - [Check your UEFI configs](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/extended/kernel-issues.html#stuck-on-eb-log-exitbs-start)
  - Try NVRAM clear (Press the space key in the OpenCore boot menu and select Reset NVRAM.)

- Dock is not transparent
  - [Vega 11 is unsupported APU](https://dortania.github.io/GPU-Buyers-Guide/modern-gpus/amd-gpu.html#amd-apus-all-variants)

- SATA SSD/HDD not recognized
  - I would appreciate if you could provide me with the information!

## Thanks

- https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#starting-point
- http://www.neko.ne.jp/~freewing/hardware/lenovo_m75q_amd_ryzen_pro_3400ge_ryzentosh_osx86/

