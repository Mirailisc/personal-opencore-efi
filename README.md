# personal-opencore-efi
OpenCore for R5-3600 and Asrock B450M Steel legend

Supported MacOS: 11.3+ (BigSur or Newer)

**Things not working**
- Docker (use `docker-machine` with virtualbox instead)
- Docker Desktop (I used Portainer agent since I have my own server)
- Side car
- Universal Control (for MacOS Monterey (12) or newer)

### How to use it ?
Download this repo and use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) with `iMacPro1,1` before install the os

### My PC spec
- CPU: R5-3600
- RAM: 32GB DDR4 3200
- GPU: AMD Radeon RX570 8GB Msi Armor
- **(main)** SSD: 240GB Kingston (SATA) + 500GB WD_BLACK SN750 NVME
- **(optional)** Bluetooth USB 4.0 Adapter TP-LINK 
(make sure to remove `IntelBluetoothFirmware.kext` and `BlueToolFixup.kext` if you don't have it)
