# Hackintosh-EFI-For-Deskmini-310-i5-9400

[中文说明](README_ZH.md)

## introduction

EFI document for my own use, citing and sorting out the achievements of many predecessors, see the list of acknowledgements for details.

## update

- 2021-02-02
  - Updated OC to version 0.6.5
  - System updated to 11.2
  - upgrade KEXT

- 2020-12-15
  - Replace with OC boot, version 0.6.4
  - System updated to 11.1

- 2020-04-21
  - Update Clover V5113

- 2020-04-11
  - Install the 10.15.4 Supplement Update for a painless upgrade.

- 2020-04-06
  - update Clover_v5108
  - Update the official version lilu_v1.4.3, whatevengreen_v1.3.8, applealc_v1.4.8
  - Update virtualsmc_v1.1.2, brcmbluetoothinjector_v2.5.2. kext, etc

- 2020-03-31
  - Update to WhatEvergreen 1.3.8- T3 Beta Driver, which resolves black screen on startup and sleep (provided by Mushizhizhi)

- 020-03-26
  - Update Clover 5107
  - Update WhatEvergreen 1.3.8
  - Update Lilu 1.4.3

## configuration

- CPU: i5-9400
- Memory: Kingston DDR4 2666MHz 8GB x 2
- Hard drive:
  - Western Digital SSD M.2 NVME 1T SN550
  - Western Digital Solid State Blue Series SATA3.0 500G
  - Western Digital Mechanical Blue Plate 1TB
- Fan: cat fan L9i
- Wireless Network Card: BCM94352_DW1560
- Display:
  - Viewsonic 23.6 "4K VX2478-4K-HD

## BIOS Settings (currently P4.4)

- Load UEFI Defaults(F9)
- Advanced
    - Onboard HD Audio: Enabled
    - USB Configuration, XHCI Hand-off, Enabled
    - Super IO Configuration, Serial Port, Disabled (Must)
- Security
    - Secure Boot, Disabled(by default)
- CSM on, UEFI only

- Enable HWP (BIOS) Settings
  - CPU chipset -> CPU C STATE SUPPORT ENABLED
  - CFG Lock -> Disabled

## Working status

### Work normally:

- 1. The sound card
- 2. The card
- 3. Bluetooth
- 4. Airdrop
- 5. Relay
- 6. App store
- 7. Sleep
- 8. USB&USB2.0 Extension &Type C
- 9. CPU frequency conversion test
- 11. Nuclear acceleration
- 12. H.264 hardware decoding, encoding, video processing
- 13. SATA SSD Trim

## Instructions for use

- Need to regenerate three codes

## Credits

- [acidanthera](https://github.com/acidanthera)
- [daliansky](https://github.com/daliansky/)
- [liminghuang](https://github.com/liminghuang/)
- [isNextJuly](https://github.com/isNextJuly/)
- [appleserial](https://github.com/appleserial/DeskMini)