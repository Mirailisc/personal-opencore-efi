# personal-opencore-efi
OpenCore for R5-3600 and Asrock B450M Steel legend

Supported OS: Big Sur 11.3+

**Things not working**
- Apple service (iCloud services) **fixable**
- Docker (recommended to buy Intel CPU instead)

### How to use it ?
Download this repo and use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) with `iMacPro1,1` before install the os

### My PC spec
- CPU: R5-3600
- RAM: 32GB DDR4 2666
- GPU: AMD Radeon RX570 8GB Msi Armor
- SSD: 240GB Hikvision (SATA) + 250GB Samsung SSD Nvme
- **(optional)** Bluetooth USB 4.0 Adapter TP-LINK 
(make sure to remove `IntelBluetoothFirmware.kext` and `BlueToolFixup.kext` if you don't have it)
