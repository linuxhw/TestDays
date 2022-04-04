Fedora 35 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 35.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_35/Desktop/README.md) and [notebooks](/Dist/Fedora_35/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ Kernel                   ](#kernel)
  - [ Kernel Family            ](#kernel-family)
  - [ Kernel Major Ver.        ](#kernel-major-ver)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linuxbsd)
  - [ Dual Boot (Win)          ](#dual-boot-win)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Secure Boot              ](#secure-boot)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Op-Modes             ](#cpu-op-modes)
  - [ CPU Microcode            ](#cpu-microcode)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 1757

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [5c28fb1391](https://linux-hardware.org/?probe=5c28fb1391) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [92130ffb61](https://linux-hardware.org/?probe=92130ffb61) | Apr 04, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [bdd5a36f62](https://linux-hardware.org/?probe=bdd5a36f62) | Apr 04, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [1c4423ca19](https://linux-hardware.org/?probe=1c4423ca19) | Apr 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ca26fd54e1](https://linux-hardware.org/?probe=ca26fd54e1) | Apr 04, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [d479e2ae4a](https://linux-hardware.org/?probe=d479e2ae4a) | Apr 04, 2022 |
| ASUSTek       | UX301LAA                    | Notebook    | [1c631fdb63](https://linux-hardware.org/?probe=1c631fdb63) | Apr 04, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| Sony          | VPCEB4L1E                   | Notebook    | [358783a077](https://linux-hardware.org/?probe=358783a077) | Apr 03, 2022 |
| ASUSTek       | A55BM-K                     | Desktop     | [c0832d15d0](https://linux-hardware.org/?probe=c0832d15d0) | Apr 03, 2022 |
| ASRock        | C2750D4I                    | Desktop     | [b328ff82c5](https://linux-hardware.org/?probe=b328ff82c5) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [ec65d243a5](https://linux-hardware.org/?probe=ec65d243a5) | Apr 03, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3e8d03d8d6](https://linux-hardware.org/?probe=3e8d03d8d6) | Apr 03, 2022 |
| Dell          | Latitude 5520               | Notebook    | [0fc592dd2c](https://linux-hardware.org/?probe=0fc592dd2c) | Apr 03, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [67b9d43387](https://linux-hardware.org/?probe=67b9d43387) | Apr 03, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [e826deade2](https://linux-hardware.org/?probe=e826deade2) | Apr 03, 2022 |
| Framework     | Laptop                      | Notebook    | [a0e35b1871](https://linux-hardware.org/?probe=a0e35b1871) | Apr 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS2B000    | Notebook    | [869407eb01](https://linux-hardware.org/?probe=869407eb01) | Apr 03, 2022 |
| HP            | 871A                        | Mini pc     | [cd3029f6aa](https://linux-hardware.org/?probe=cd3029f6aa) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| Dell          | Precision 5530              | Notebook    | [96b22b6124](https://linux-hardware.org/?probe=96b22b6124) | Apr 03, 2022 |
| MSI           | H81M-E34                    | Desktop     | [fad24f9efc](https://linux-hardware.org/?probe=fad24f9efc) | Apr 03, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [d187a0de09](https://linux-hardware.org/?probe=d187a0de09) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [2911dea3f0](https://linux-hardware.org/?probe=2911dea3f0) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [f13dbb1e06](https://linux-hardware.org/?probe=f13dbb1e06) | Apr 02, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5dcb0a1847](https://linux-hardware.org/?probe=5dcb0a1847) | Apr 02, 2022 |
| HP            | 871A                        | Mini pc     | [b71bc66f21](https://linux-hardware.org/?probe=b71bc66f21) | Apr 02, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [446d4b4c59](https://linux-hardware.org/?probe=446d4b4c59) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M91p 7033HS8    | Desktop     | [0fab8669e0](https://linux-hardware.org/?probe=0fab8669e0) | Apr 02, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [8bd2b269ff](https://linux-hardware.org/?probe=8bd2b269ff) | Apr 02, 2022 |
| Dell          | Latitude 5500               | Notebook    | [798c0e5fa4](https://linux-hardware.org/?probe=798c0e5fa4) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [3bc3694efb](https://linux-hardware.org/?probe=3bc3694efb) | Apr 02, 2022 |
| Timi          | TM1612                      | Notebook    | [7eb83bb23a](https://linux-hardware.org/?probe=7eb83bb23a) | Apr 02, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1de292a85c](https://linux-hardware.org/?probe=1de292a85c) | Apr 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [8af8994f80](https://linux-hardware.org/?probe=8af8994f80) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [3c89c6c9d8](https://linux-hardware.org/?probe=3c89c6c9d8) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3bcc5c9790](https://linux-hardware.org/?probe=3bcc5c9790) | Apr 02, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [11153fc9f1](https://linux-hardware.org/?probe=11153fc9f1) | Apr 02, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [6b2cbca4b2](https://linux-hardware.org/?probe=6b2cbca4b2) | Apr 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [18b9815ff5](https://linux-hardware.org/?probe=18b9815ff5) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [055b15c7a9](https://linux-hardware.org/?probe=055b15c7a9) | Apr 02, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [4696339b4e](https://linux-hardware.org/?probe=4696339b4e) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [8ae9fd4940](https://linux-hardware.org/?probe=8ae9fd4940) | Apr 02, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f30982f3ac](https://linux-hardware.org/?probe=f30982f3ac) | Apr 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [03812d6355](https://linux-hardware.org/?probe=03812d6355) | Apr 01, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [c0e5b4550a](https://linux-hardware.org/?probe=c0e5b4550a) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | Notebook    | [82ec2ff5f6](https://linux-hardware.org/?probe=82ec2ff5f6) | Apr 01, 2022 |
| PC Special... | PC5x_7xHP_HR_HS             | Notebook    | [7aefa77b4b](https://linux-hardware.org/?probe=7aefa77b4b) | Apr 01, 2022 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | Notebook    | [97505bf353](https://linux-hardware.org/?probe=97505bf353) | Apr 01, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [cafa6713f0](https://linux-hardware.org/?probe=cafa6713f0) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [9ebbf23e28](https://linux-hardware.org/?probe=9ebbf23e28) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [95d2d82ede](https://linux-hardware.org/?probe=95d2d82ede) | Apr 01, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [3acec795a6](https://linux-hardware.org/?probe=3acec795a6) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [d18cd45522](https://linux-hardware.org/?probe=d18cd45522) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [ec162ebae4](https://linux-hardware.org/?probe=ec162ebae4) | Apr 01, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [beed63b0d4](https://linux-hardware.org/?probe=beed63b0d4) | Apr 01, 2022 |
| Gigabyte      | B460M D3H                   | Desktop     | [7c159eefd8](https://linux-hardware.org/?probe=7c159eefd8) | Apr 01, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [81e7639a72](https://linux-hardware.org/?probe=81e7639a72) | Apr 01, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b81a77ca49](https://linux-hardware.org/?probe=b81a77ca49) | Apr 01, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [b6da5f9629](https://linux-hardware.org/?probe=b6da5f9629) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8d0f35d0a4](https://linux-hardware.org/?probe=8d0f35d0a4) | Apr 01, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [06b3aacb51](https://linux-hardware.org/?probe=06b3aacb51) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [913c396bde](https://linux-hardware.org/?probe=913c396bde) | Apr 01, 2022 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [6774f9f9c8](https://linux-hardware.org/?probe=6774f9f9c8) | Apr 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [17eda00f3d](https://linux-hardware.org/?probe=17eda00f3d) | Apr 01, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cb4611f386](https://linux-hardware.org/?probe=cb4611f386) | Apr 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [d4691ddfac](https://linux-hardware.org/?probe=d4691ddfac) | Apr 01, 2022 |
| HP            | Laptop 17z-ca300            | Notebook    | [726d1e7b0f](https://linux-hardware.org/?probe=726d1e7b0f) | Mar 31, 2022 |
| MSI           | B85-G43 GAMING              | Desktop     | [70574c396b](https://linux-hardware.org/?probe=70574c396b) | Mar 31, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [99276b473e](https://linux-hardware.org/?probe=99276b473e) | Mar 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [c01344bd43](https://linux-hardware.org/?probe=c01344bd43) | Mar 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b08e7d8589](https://linux-hardware.org/?probe=b08e7d8589) | Mar 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a18360bae8](https://linux-hardware.org/?probe=a18360bae8) | Mar 31, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [a4ad860e3d](https://linux-hardware.org/?probe=a4ad860e3d) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [6ab27f6f88](https://linux-hardware.org/?probe=6ab27f6f88) | Mar 31, 2022 |
| ASUSTek       | M5A97 EVO                   | Desktop     | [96cd3f3a03](https://linux-hardware.org/?probe=96cd3f3a03) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [a9cf0523c2](https://linux-hardware.org/?probe=a9cf0523c2) | Mar 31, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | Notebook    | [b87a95ae1a](https://linux-hardware.org/?probe=b87a95ae1a) | Mar 31, 2022 |
| Sony          | SVF14213CLB                 | Notebook    | [fecf079b63](https://linux-hardware.org/?probe=fecf079b63) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [2ce0540229](https://linux-hardware.org/?probe=2ce0540229) | Mar 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4146e027d3](https://linux-hardware.org/?probe=4146e027d3) | Mar 31, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [4ba34b9b1f](https://linux-hardware.org/?probe=4ba34b9b1f) | Mar 31, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [cc57bcd7a9](https://linux-hardware.org/?probe=cc57bcd7a9) | Mar 31, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [f43d64639e](https://linux-hardware.org/?probe=f43d64639e) | Mar 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [43e45df9f5](https://linux-hardware.org/?probe=43e45df9f5) | Mar 30, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [c2daebfd60](https://linux-hardware.org/?probe=c2daebfd60) | Mar 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b8716e4043](https://linux-hardware.org/?probe=b8716e4043) | Mar 30, 2022 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [cd333e5720](https://linux-hardware.org/?probe=cd333e5720) | Mar 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [3cd8bdb60c](https://linux-hardware.org/?probe=3cd8bdb60c) | Mar 30, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [db3d70e53a](https://linux-hardware.org/?probe=db3d70e53a) | Mar 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [3a64f14cc4](https://linux-hardware.org/?probe=3a64f14cc4) | Mar 30, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [e205dc3177](https://linux-hardware.org/?probe=e205dc3177) | Mar 30, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [dd51589f73](https://linux-hardware.org/?probe=dd51589f73) | Mar 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d8c91051f3](https://linux-hardware.org/?probe=d8c91051f3) | Mar 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0f18e7b54b](https://linux-hardware.org/?probe=0f18e7b54b) | Mar 30, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [2491111c9d](https://linux-hardware.org/?probe=2491111c9d) | Mar 30, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [fd1759c341](https://linux-hardware.org/?probe=fd1759c341) | Mar 29, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3e3c94b9f6](https://linux-hardware.org/?probe=3e3c94b9f6) | Mar 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [670f83f6bb](https://linux-hardware.org/?probe=670f83f6bb) | Mar 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [88b64a12df](https://linux-hardware.org/?probe=88b64a12df) | Mar 29, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [535acf7c14](https://linux-hardware.org/?probe=535acf7c14) | Mar 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [cfaa52d13e](https://linux-hardware.org/?probe=cfaa52d13e) | Mar 29, 2022 |
| Hampoo        | C1W6_AP123C_6GB Reserved    | Notebook    | [ff622b910d](https://linux-hardware.org/?probe=ff622b910d) | Mar 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Gateway       | SX2185                      | Desktop     | [3d1d72a3c1](https://linux-hardware.org/?probe=3d1d72a3c1) | Mar 28, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [18a5e10a64](https://linux-hardware.org/?probe=18a5e10a64) | Mar 28, 2022 |
| HP            | 82A2                        | Desktop     | [5736762c06](https://linux-hardware.org/?probe=5736762c06) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c1384b9063](https://linux-hardware.org/?probe=c1384b9063) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9464f8c81e](https://linux-hardware.org/?probe=9464f8c81e) | Mar 28, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9c5efbe2a7](https://linux-hardware.org/?probe=9c5efbe2a7) | Mar 28, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [e4c1632bc2](https://linux-hardware.org/?probe=e4c1632bc2) | Mar 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [ac807c9324](https://linux-hardware.org/?probe=ac807c9324) | Mar 27, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [c5d26f3dc7](https://linux-hardware.org/?probe=c5d26f3dc7) | Mar 27, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [53da8c0cdf](https://linux-hardware.org/?probe=53da8c0cdf) | Mar 27, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [c472ae03f6](https://linux-hardware.org/?probe=c472ae03f6) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [51c0f63296](https://linux-hardware.org/?probe=51c0f63296) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | Desktop     | [9c0577803f](https://linux-hardware.org/?probe=9c0577803f) | Mar 27, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b8969bf34b](https://linux-hardware.org/?probe=b8969bf34b) | Mar 27, 2022 |
| AAEON         | IMBA-H110A V1.0             | Desktop     | [a296d4597c](https://linux-hardware.org/?probe=a296d4597c) | Mar 27, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [084d60ff3b](https://linux-hardware.org/?probe=084d60ff3b) | Mar 27, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e04592bee1](https://linux-hardware.org/?probe=e04592bee1) | Mar 27, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [73be67de2c](https://linux-hardware.org/?probe=73be67de2c) | Mar 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [26a2540713](https://linux-hardware.org/?probe=26a2540713) | Mar 27, 2022 |
| Dell          | 0M6C7G A00                  | Desktop     | [d214df0c57](https://linux-hardware.org/?probe=d214df0c57) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [8252c302e2](https://linux-hardware.org/?probe=8252c302e2) | Mar 27, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [b557a2005c](https://linux-hardware.org/?probe=b557a2005c) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [64606b8247](https://linux-hardware.org/?probe=64606b8247) | Mar 26, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [dc5e0a376b](https://linux-hardware.org/?probe=dc5e0a376b) | Mar 26, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ce82ab584b](https://linux-hardware.org/?probe=ce82ab584b) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [91b7f328b1](https://linux-hardware.org/?probe=91b7f328b1) | Mar 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [48ce1c3bd8](https://linux-hardware.org/?probe=48ce1c3bd8) | Mar 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [029e0a790e](https://linux-hardware.org/?probe=029e0a790e) | Mar 26, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [d1b78f5eb8](https://linux-hardware.org/?probe=d1b78f5eb8) | Mar 26, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c4b697295e](https://linux-hardware.org/?probe=c4b697295e) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [25ad4e35b9](https://linux-hardware.org/?probe=25ad4e35b9) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d5e927b59e](https://linux-hardware.org/?probe=d5e927b59e) | Mar 26, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b47822d246](https://linux-hardware.org/?probe=b47822d246) | Mar 26, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [a640b0a024](https://linux-hardware.org/?probe=a640b0a024) | Mar 26, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [a3ecefa43f](https://linux-hardware.org/?probe=a3ecefa43f) | Mar 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e1ce096233](https://linux-hardware.org/?probe=e1ce096233) | Mar 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b2d35dc269](https://linux-hardware.org/?probe=b2d35dc269) | Mar 26, 2022 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [c8acfed97a](https://linux-hardware.org/?probe=c8acfed97a) | Mar 26, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [5861c8e75a](https://linux-hardware.org/?probe=5861c8e75a) | Mar 26, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [b78f0137ba](https://linux-hardware.org/?probe=b78f0137ba) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [a68ce8edaf](https://linux-hardware.org/?probe=a68ce8edaf) | Mar 26, 2022 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [90299bc344](https://linux-hardware.org/?probe=90299bc344) | Mar 26, 2022 |
| Alienware     | m15 R6                      | Notebook    | [5505410995](https://linux-hardware.org/?probe=5505410995) | Mar 25, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | ThinkPad X250 20CLS09Y19    | Notebook    | [2602549f95](https://linux-hardware.org/?probe=2602549f95) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [1d0229f697](https://linux-hardware.org/?probe=1d0229f697) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [1ab1216e5b](https://linux-hardware.org/?probe=1ab1216e5b) | Mar 25, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [b47655a721](https://linux-hardware.org/?probe=b47655a721) | Mar 25, 2022 |
| Sony          | VGN-FW180D                  | Notebook    | [9bbcb3d0ac](https://linux-hardware.org/?probe=9bbcb3d0ac) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [da358bbf5c](https://linux-hardware.org/?probe=da358bbf5c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | Notebook    | [4a6b3d619c](https://linux-hardware.org/?probe=4a6b3d619c) | Mar 25, 2022 |
| MSI           | Stealth GS66 12UHS          | Notebook    | [7d1fa138d0](https://linux-hardware.org/?probe=7d1fa138d0) | Mar 25, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [975bcd1031](https://linux-hardware.org/?probe=975bcd1031) | Mar 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [50335ac3a2](https://linux-hardware.org/?probe=50335ac3a2) | Mar 25, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [870e407665](https://linux-hardware.org/?probe=870e407665) | Mar 25, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [911fd95d9f](https://linux-hardware.org/?probe=911fd95d9f) | Mar 25, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2424807acb](https://linux-hardware.org/?probe=2424807acb) | Mar 24, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [552956f271](https://linux-hardware.org/?probe=552956f271) | Mar 24, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [d6d6620190](https://linux-hardware.org/?probe=d6d6620190) | Mar 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1d606d499d](https://linux-hardware.org/?probe=1d606d499d) | Mar 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [7c80283af3](https://linux-hardware.org/?probe=7c80283af3) | Mar 24, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [b1ff998755](https://linux-hardware.org/?probe=b1ff998755) | Mar 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [25d5cba9dc](https://linux-hardware.org/?probe=25d5cba9dc) | Mar 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c10b664e4e](https://linux-hardware.org/?probe=c10b664e4e) | Mar 24, 2022 |
| Intel         | DH61BE AAG14062-206         | Desktop     | [08a352b1d2](https://linux-hardware.org/?probe=08a352b1d2) | Mar 24, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [52bc15cdf9](https://linux-hardware.org/?probe=52bc15cdf9) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6136cfa920](https://linux-hardware.org/?probe=6136cfa920) | Mar 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d74979a970](https://linux-hardware.org/?probe=d74979a970) | Mar 24, 2022 |
| System76      | Gazelle                     | Notebook    | [5a83198dd6](https://linux-hardware.org/?probe=5a83198dd6) | Mar 24, 2022 |
| Dell          | 08NG84 A01                  | All in one  | [8e2101ed83](https://linux-hardware.org/?probe=8e2101ed83) | Mar 24, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ef1af7bbae](https://linux-hardware.org/?probe=ef1af7bbae) | Mar 23, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [337b027d96](https://linux-hardware.org/?probe=337b027d96) | Mar 23, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [440e4d8b48](https://linux-hardware.org/?probe=440e4d8b48) | Mar 23, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [1fb70f4b83](https://linux-hardware.org/?probe=1fb70f4b83) | Mar 23, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [912cb19656](https://linux-hardware.org/?probe=912cb19656) | Mar 23, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [55730a4af8](https://linux-hardware.org/?probe=55730a4af8) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e75d387eea](https://linux-hardware.org/?probe=e75d387eea) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| ASUSTek       | X75VCP                      | Notebook    | [54e978fcca](https://linux-hardware.org/?probe=54e978fcca) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [86c831ce79](https://linux-hardware.org/?probe=86c831ce79) | Mar 23, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [3024cce066](https://linux-hardware.org/?probe=3024cce066) | Mar 23, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [6285900fd7](https://linux-hardware.org/?probe=6285900fd7) | Mar 22, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [f140780c32](https://linux-hardware.org/?probe=f140780c32) | Mar 22, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [6fc4d08da4](https://linux-hardware.org/?probe=6fc4d08da4) | Mar 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [ddf8fb6916](https://linux-hardware.org/?probe=ddf8fb6916) | Mar 22, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [6239582d24](https://linux-hardware.org/?probe=6239582d24) | Mar 22, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [6934e641a4](https://linux-hardware.org/?probe=6934e641a4) | Mar 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bea334f9c7](https://linux-hardware.org/?probe=bea334f9c7) | Mar 22, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [188fb139c3](https://linux-hardware.org/?probe=188fb139c3) | Mar 21, 2022 |
| ABIT          | IP35-E                      | Desktop     | [9d6e95572e](https://linux-hardware.org/?probe=9d6e95572e) | Mar 21, 2022 |
| ABIT          | IP35-E                      | Desktop     | [3d93ef42c9](https://linux-hardware.org/?probe=3d93ef42c9) | Mar 21, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a1a39d622b](https://linux-hardware.org/?probe=a1a39d622b) | Mar 21, 2022 |
| MSI           | A320M BAZOOKA               | Desktop     | [0c12287476](https://linux-hardware.org/?probe=0c12287476) | Mar 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| MACHINIST     | X99-G7 V1.0                 | Desktop     | [70a784f09c](https://linux-hardware.org/?probe=70a784f09c) | Mar 21, 2022 |
| Lenovo        | 3111 NOK                    | Mini pc     | [fe298dc766](https://linux-hardware.org/?probe=fe298dc766) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [c294e20164](https://linux-hardware.org/?probe=c294e20164) | Mar 21, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [5b9b7903ad](https://linux-hardware.org/?probe=5b9b7903ad) | Mar 21, 2022 |
| ASRock        | Z270 Extreme4               | Desktop     | [0f3a8eb166](https://linux-hardware.org/?probe=0f3a8eb166) | Mar 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [621ad4beae](https://linux-hardware.org/?probe=621ad4beae) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [2298f934bd](https://linux-hardware.org/?probe=2298f934bd) | Mar 21, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [279bb03666](https://linux-hardware.org/?probe=279bb03666) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [a5937e694a](https://linux-hardware.org/?probe=a5937e694a) | Mar 20, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [536bac0d6a](https://linux-hardware.org/?probe=536bac0d6a) | Mar 20, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| Dell          | Inspiron 15 5501            | Notebook    | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | Notebook    | [40767d2545](https://linux-hardware.org/?probe=40767d2545) | Mar 20, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [bde47f2d75](https://linux-hardware.org/?probe=bde47f2d75) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [2f713e8db8](https://linux-hardware.org/?probe=2f713e8db8) | Mar 19, 2022 |
| MACHINIST     | X99-G7 V1.0                 | Desktop     | [ebc42c3206](https://linux-hardware.org/?probe=ebc42c3206) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | Notebook    | [8366f92538](https://linux-hardware.org/?probe=8366f92538) | Mar 19, 2022 |
| ASUSTek       | K46CM                       | Notebook    | [8f96005683](https://linux-hardware.org/?probe=8f96005683) | Mar 19, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [3c40b29b63](https://linux-hardware.org/?probe=3c40b29b63) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [baae82b163](https://linux-hardware.org/?probe=baae82b163) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [b4a188ad90](https://linux-hardware.org/?probe=b4a188ad90) | Mar 19, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [ce6b8e3716](https://linux-hardware.org/?probe=ce6b8e3716) | Mar 19, 2022 |
| HP            | 84EF 01100                  | All in one  | [be542cf367](https://linux-hardware.org/?probe=be542cf367) | Mar 19, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [7970a8e8d2](https://linux-hardware.org/?probe=7970a8e8d2) | Mar 19, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5415b5f876](https://linux-hardware.org/?probe=5415b5f876) | Mar 18, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| Acer          | Aspire A317-51G             | Notebook    | [f2a7cadaff](https://linux-hardware.org/?probe=f2a7cadaff) | Mar 18, 2022 |
| Toshiba       | Satellite C855-12R          | Notebook    | [96554352c8](https://linux-hardware.org/?probe=96554352c8) | Mar 18, 2022 |
| Lenovo        | ThinkPad P53 20QN000HGE     | Notebook    | [db71f4d011](https://linux-hardware.org/?probe=db71f4d011) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [dc3b3ab391](https://linux-hardware.org/?probe=dc3b3ab391) | Mar 18, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c869642fe9](https://linux-hardware.org/?probe=c869642fe9) | Mar 18, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [6f4835e78d](https://linux-hardware.org/?probe=6f4835e78d) | Mar 18, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e97e686e5e](https://linux-hardware.org/?probe=e97e686e5e) | Mar 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7bc2963830](https://linux-hardware.org/?probe=7bc2963830) | Mar 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [b928348a02](https://linux-hardware.org/?probe=b928348a02) | Mar 17, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [c41639222f](https://linux-hardware.org/?probe=c41639222f) | Mar 17, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [c6b6cc1f1d](https://linux-hardware.org/?probe=c6b6cc1f1d) | Mar 17, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [b5aeb18001](https://linux-hardware.org/?probe=b5aeb18001) | Mar 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6a5b5cd15e](https://linux-hardware.org/?probe=6a5b5cd15e) | Mar 17, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [f7eb058e61](https://linux-hardware.org/?probe=f7eb058e61) | Mar 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [16ced37ed8](https://linux-hardware.org/?probe=16ced37ed8) | Mar 17, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [046115ba0a](https://linux-hardware.org/?probe=046115ba0a) | Mar 16, 2022 |
| Lenovo        | ThinkPad X220 428767U       | Notebook    | [380351014b](https://linux-hardware.org/?probe=380351014b) | Mar 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a3444ce232](https://linux-hardware.org/?probe=a3444ce232) | Mar 16, 2022 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [d5afbde22c](https://linux-hardware.org/?probe=d5afbde22c) | Mar 16, 2022 |
| HP            | 826A A01                    | All in one  | [e7df5fb705](https://linux-hardware.org/?probe=e7df5fb705) | Mar 16, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [b0d9828f83](https://linux-hardware.org/?probe=b0d9828f83) | Mar 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | Notebook    | [1ac160aea7](https://linux-hardware.org/?probe=1ac160aea7) | Mar 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [75a7099e71](https://linux-hardware.org/?probe=75a7099e71) | Mar 15, 2022 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [66bda745cd](https://linux-hardware.org/?probe=66bda745cd) | Mar 15, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [dc4e443fca](https://linux-hardware.org/?probe=dc4e443fca) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [62038e09e8](https://linux-hardware.org/?probe=62038e09e8) | Mar 15, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [cbebb0b476](https://linux-hardware.org/?probe=cbebb0b476) | Mar 15, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [affad66907](https://linux-hardware.org/?probe=affad66907) | Mar 14, 2022 |
| Acer          | Calpella                    | Notebook    | [038e7b15ee](https://linux-hardware.org/?probe=038e7b15ee) | Mar 14, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [79744a34f1](https://linux-hardware.org/?probe=79744a34f1) | Mar 14, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | ProBook 6465b               | Notebook    | [95ecc6cdbd](https://linux-hardware.org/?probe=95ecc6cdbd) | Mar 14, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [00edfc8f9b](https://linux-hardware.org/?probe=00edfc8f9b) | Mar 14, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [b400e8a455](https://linux-hardware.org/?probe=b400e8a455) | Mar 14, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [5cdaea7c5a](https://linux-hardware.org/?probe=5cdaea7c5a) | Mar 14, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [72a6f7ef1b](https://linux-hardware.org/?probe=72a6f7ef1b) | Mar 13, 2022 |
| Dell          | Vostro 1014                 | Notebook    | [8df761ef60](https://linux-hardware.org/?probe=8df761ef60) | Mar 13, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [9cce5830b5](https://linux-hardware.org/?probe=9cce5830b5) | Mar 13, 2022 |
| Positivo      | N1250                       | Notebook    | [e0ac8b69f1](https://linux-hardware.org/?probe=e0ac8b69f1) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [739b74effe](https://linux-hardware.org/?probe=739b74effe) | Mar 13, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [3dc49dc5f3](https://linux-hardware.org/?probe=3dc49dc5f3) | Mar 13, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [79211f85fd](https://linux-hardware.org/?probe=79211f85fd) | Mar 13, 2022 |
| MSI           | B85M-E45 2015-08-19         | Desktop     | [90f5d4247e](https://linux-hardware.org/?probe=90f5d4247e) | Mar 13, 2022 |
| Intel         | NUC7i3DNB J57625-513        | Mini pc     | [d23d5b7f32](https://linux-hardware.org/?probe=d23d5b7f32) | Mar 13, 2022 |
| Dell          | Latitude 7285               | Notebook    | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d5d90a423a](https://linux-hardware.org/?probe=d5d90a423a) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6e9075eebf](https://linux-hardware.org/?probe=6e9075eebf) | Mar 13, 2022 |
| Dell          | Latitude 5511               | Notebook    | [ec15afa8e7](https://linux-hardware.org/?probe=ec15afa8e7) | Mar 12, 2022 |
| Dell          | Precision 5540              | Notebook    | [99b2435d7a](https://linux-hardware.org/?probe=99b2435d7a) | Mar 12, 2022 |
| MSI           | 2A9C                        | Desktop     | [99c139f47b](https://linux-hardware.org/?probe=99c139f47b) | Mar 12, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [2bb86501da](https://linux-hardware.org/?probe=2bb86501da) | Mar 12, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [21c958ad5f](https://linux-hardware.org/?probe=21c958ad5f) | Mar 12, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [276b115350](https://linux-hardware.org/?probe=276b115350) | Mar 12, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [98fd2cf2c6](https://linux-hardware.org/?probe=98fd2cf2c6) | Mar 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6eca88e86f](https://linux-hardware.org/?probe=6eca88e86f) | Mar 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8a8cc84461](https://linux-hardware.org/?probe=8a8cc84461) | Mar 12, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [a3f9e83752](https://linux-hardware.org/?probe=a3f9e83752) | Mar 11, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2372b12d5c](https://linux-hardware.org/?probe=2372b12d5c) | Mar 11, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [cbfe261386](https://linux-hardware.org/?probe=cbfe261386) | Mar 11, 2022 |
| HP            | Notebook                    | Notebook    | [de3091d5d4](https://linux-hardware.org/?probe=de3091d5d4) | Mar 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4c71606b0a](https://linux-hardware.org/?probe=4c71606b0a) | Mar 11, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [2a4e580bd6](https://linux-hardware.org/?probe=2a4e580bd6) | Mar 11, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [889e5fe7a3](https://linux-hardware.org/?probe=889e5fe7a3) | Mar 11, 2022 |
| Dell          | G5 5505                     | Notebook    | [286d140bd5](https://linux-hardware.org/?probe=286d140bd5) | Mar 10, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [f4a2cbf25a](https://linux-hardware.org/?probe=f4a2cbf25a) | Mar 10, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [dc38e0d85a](https://linux-hardware.org/?probe=dc38e0d85a) | Mar 10, 2022 |
| HP            | ZBook 14u G4                | Notebook    | [cc637b12de](https://linux-hardware.org/?probe=cc637b12de) | Mar 10, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [68e933e6a3](https://linux-hardware.org/?probe=68e933e6a3) | Mar 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| Acer          | Aspire C22-760              | All in one  | [8952d0f7d8](https://linux-hardware.org/?probe=8952d0f7d8) | Mar 10, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [f1f2a94be9](https://linux-hardware.org/?probe=f1f2a94be9) | Mar 10, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [fc015f45ba](https://linux-hardware.org/?probe=fc015f45ba) | Mar 10, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c4d9b11074](https://linux-hardware.org/?probe=c4d9b11074) | Mar 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [e4596496cf](https://linux-hardware.org/?probe=e4596496cf) | Mar 10, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [849f4141ce](https://linux-hardware.org/?probe=849f4141ce) | Mar 09, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [49503537f5](https://linux-hardware.org/?probe=49503537f5) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| Positivo      | CHT12CP                     | Notebook    | [fa7f40245b](https://linux-hardware.org/?probe=fa7f40245b) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [0659469dbe](https://linux-hardware.org/?probe=0659469dbe) | Mar 09, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [1935867fe2](https://linux-hardware.org/?probe=1935867fe2) | Mar 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5aef9f7ccf](https://linux-hardware.org/?probe=5aef9f7ccf) | Mar 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [4378396a20](https://linux-hardware.org/?probe=4378396a20) | Mar 08, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [9be6d8c4aa](https://linux-hardware.org/?probe=9be6d8c4aa) | Mar 08, 2022 |
| HP            | Pavilion g4                 | Notebook    | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| Medion        | E3222                       | Convertible | [064457ad59](https://linux-hardware.org/?probe=064457ad59) | Mar 08, 2022 |
| Medion        | E3222                       | Convertible | [287046ff17](https://linux-hardware.org/?probe=287046ff17) | Mar 08, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [13a9aa4fb3](https://linux-hardware.org/?probe=13a9aa4fb3) | Mar 08, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c935c59d99](https://linux-hardware.org/?probe=c935c59d99) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [4eb9de0f3a](https://linux-hardware.org/?probe=4eb9de0f3a) | Mar 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [02b4ade19f](https://linux-hardware.org/?probe=02b4ade19f) | Mar 08, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [5fb0149650](https://linux-hardware.org/?probe=5fb0149650) | Mar 08, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [1260b41068](https://linux-hardware.org/?probe=1260b41068) | Mar 08, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [cec3d7b058](https://linux-hardware.org/?probe=cec3d7b058) | Mar 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bd9567c6ce](https://linux-hardware.org/?probe=bd9567c6ce) | Mar 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [96833919d2](https://linux-hardware.org/?probe=96833919d2) | Mar 08, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [16f5e2d856](https://linux-hardware.org/?probe=16f5e2d856) | Mar 08, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [f3eb9f941a](https://linux-hardware.org/?probe=f3eb9f941a) | Mar 08, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [2b8b852d07](https://linux-hardware.org/?probe=2b8b852d07) | Mar 07, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3b750cbc3f](https://linux-hardware.org/?probe=3b750cbc3f) | Mar 07, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [ec3824b685](https://linux-hardware.org/?probe=ec3824b685) | Mar 07, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ae9c8e47e2](https://linux-hardware.org/?probe=ae9c8e47e2) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [49d6176e9e](https://linux-hardware.org/?probe=49d6176e9e) | Mar 07, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f0a65362c5](https://linux-hardware.org/?probe=f0a65362c5) | Mar 07, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [267fa2ca76](https://linux-hardware.org/?probe=267fa2ca76) | Mar 06, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [2bf4890b1b](https://linux-hardware.org/?probe=2bf4890b1b) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e14e313311](https://linux-hardware.org/?probe=e14e313311) | Mar 06, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [856cb873fc](https://linux-hardware.org/?probe=856cb873fc) | Mar 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [a544689bd5](https://linux-hardware.org/?probe=a544689bd5) | Mar 06, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [fc4d2904c3](https://linux-hardware.org/?probe=fc4d2904c3) | Mar 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [94584a9a48](https://linux-hardware.org/?probe=94584a9a48) | Mar 06, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [f7739e263e](https://linux-hardware.org/?probe=f7739e263e) | Mar 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [4498ec2620](https://linux-hardware.org/?probe=4498ec2620) | Mar 06, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [e29f709958](https://linux-hardware.org/?probe=e29f709958) | Mar 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [91bb2e28fe](https://linux-hardware.org/?probe=91bb2e28fe) | Mar 05, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [1d4f09c200](https://linux-hardware.org/?probe=1d4f09c200) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | Notebook    | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| Dell          | Latitude E5470              | Notebook    | [1ef8a55ede](https://linux-hardware.org/?probe=1ef8a55ede) | Mar 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7cea2ed288](https://linux-hardware.org/?probe=7cea2ed288) | Mar 05, 2022 |
| Dell          | 0WR7PY A00                  | Desktop     | [19895058a5](https://linux-hardware.org/?probe=19895058a5) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [55d8863b7b](https://linux-hardware.org/?probe=55d8863b7b) | Mar 05, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [9b130dbcb5](https://linux-hardware.org/?probe=9b130dbcb5) | Mar 04, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [134d1cf65b](https://linux-hardware.org/?probe=134d1cf65b) | Mar 03, 2022 |
| Dell          | 01TN68 A01                  | Desktop     | [f57cafd9b1](https://linux-hardware.org/?probe=f57cafd9b1) | Mar 03, 2022 |
| Dell          | 01TN68 A01                  | Desktop     | [a93c073676](https://linux-hardware.org/?probe=a93c073676) | Mar 03, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [81e8102a40](https://linux-hardware.org/?probe=81e8102a40) | Mar 03, 2022 |
| Medion        | Akoya P6638                 | Notebook    | [102c7910e5](https://linux-hardware.org/?probe=102c7910e5) | Mar 03, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c5bf02a4d7](https://linux-hardware.org/?probe=c5bf02a4d7) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d2e96e523e](https://linux-hardware.org/?probe=d2e96e523e) | Mar 03, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| Acer          | Veriton X6620G v1.0         | Desktop     | [01922bdee0](https://linux-hardware.org/?probe=01922bdee0) | Mar 02, 2022 |
| Medion        | E3222                       | Convertible | [2efb7ef486](https://linux-hardware.org/?probe=2efb7ef486) | Mar 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [35507d8b67](https://linux-hardware.org/?probe=35507d8b67) | Mar 02, 2022 |
| Medion        | E3222                       | Convertible | [ee2111791a](https://linux-hardware.org/?probe=ee2111791a) | Mar 02, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [89e589ec6b](https://linux-hardware.org/?probe=89e589ec6b) | Mar 02, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [587195961c](https://linux-hardware.org/?probe=587195961c) | Mar 02, 2022 |
| Dell          | Latitude 5411               | Notebook    | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [eb61ea7985](https://linux-hardware.org/?probe=eb61ea7985) | Mar 02, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [476396ef7c](https://linux-hardware.org/?probe=476396ef7c) | Mar 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d40f3513ef](https://linux-hardware.org/?probe=d40f3513ef) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7c9f5c83cf](https://linux-hardware.org/?probe=7c9f5c83cf) | Mar 01, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7af526bbb7](https://linux-hardware.org/?probe=7af526bbb7) | Mar 01, 2022 |
| HP            | 212B                        | Desktop     | [c183489268](https://linux-hardware.org/?probe=c183489268) | Mar 01, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [884adfefd3](https://linux-hardware.org/?probe=884adfefd3) | Mar 01, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [f61c04b0a8](https://linux-hardware.org/?probe=f61c04b0a8) | Mar 01, 2022 |
| Dell          | Latitude 7285               | Notebook    | [8d3fe46d72](https://linux-hardware.org/?probe=8d3fe46d72) | Mar 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9d178352ca](https://linux-hardware.org/?probe=9d178352ca) | Mar 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ffc6b43ec](https://linux-hardware.org/?probe=9ffc6b43ec) | Feb 28, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [4245cd910a](https://linux-hardware.org/?probe=4245cd910a) | Feb 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [d58011c0f8](https://linux-hardware.org/?probe=d58011c0f8) | Feb 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [6925ab1f20](https://linux-hardware.org/?probe=6925ab1f20) | Feb 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [8a51a8730b](https://linux-hardware.org/?probe=8a51a8730b) | Feb 28, 2022 |
| HP            | Notebook                    | Notebook    | [c8cd62d913](https://linux-hardware.org/?probe=c8cd62d913) | Feb 28, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ffbae7cdf3](https://linux-hardware.org/?probe=ffbae7cdf3) | Feb 28, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [fa94978a0b](https://linux-hardware.org/?probe=fa94978a0b) | Feb 28, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e2bc04b6f4](https://linux-hardware.org/?probe=e2bc04b6f4) | Feb 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [592d42e16c](https://linux-hardware.org/?probe=592d42e16c) | Feb 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [78cc2173d9](https://linux-hardware.org/?probe=78cc2173d9) | Feb 27, 2022 |
| Lenovo        | G70-70 80HW007LNX           | Notebook    | [a0ba78ccea](https://linux-hardware.org/?probe=a0ba78ccea) | Feb 27, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [75cdf384b5](https://linux-hardware.org/?probe=75cdf384b5) | Feb 27, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [0a92c063a1](https://linux-hardware.org/?probe=0a92c063a1) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [24861666e2](https://linux-hardware.org/?probe=24861666e2) | Feb 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [930b650263](https://linux-hardware.org/?probe=930b650263) | Feb 27, 2022 |
| Lenovo        | IdeaPad S540-14IML Touch... | Notebook    | [22bb5f0b44](https://linux-hardware.org/?probe=22bb5f0b44) | Feb 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9cdd0eea43](https://linux-hardware.org/?probe=9cdd0eea43) | Feb 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [efd62e1ed7](https://linux-hardware.org/?probe=efd62e1ed7) | Feb 26, 2022 |
| Dell          | 0VNGWR A01                  | All in one  | [399d367f06](https://linux-hardware.org/?probe=399d367f06) | Feb 26, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [36aacb1723](https://linux-hardware.org/?probe=36aacb1723) | Feb 26, 2022 |
| HP            | Pavilion g4                 | Notebook    | [0e40990ec2](https://linux-hardware.org/?probe=0e40990ec2) | Feb 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [463d26d75c](https://linux-hardware.org/?probe=463d26d75c) | Feb 26, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [03f2fa46f2](https://linux-hardware.org/?probe=03f2fa46f2) | Feb 26, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d4a3fb2dfc](https://linux-hardware.org/?probe=d4a3fb2dfc) | Feb 26, 2022 |
| AZW           | GTR V01                     | Mini pc     | [39d215e49d](https://linux-hardware.org/?probe=39d215e49d) | Feb 25, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f0692aebbe](https://linux-hardware.org/?probe=f0692aebbe) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [d8dec986e8](https://linux-hardware.org/?probe=d8dec986e8) | Feb 25, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [194baf83e9](https://linux-hardware.org/?probe=194baf83e9) | Feb 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [eaa8067586](https://linux-hardware.org/?probe=eaa8067586) | Feb 25, 2022 |
| Dell          | Latitude 3350               | Notebook    | [093650ba06](https://linux-hardware.org/?probe=093650ba06) | Feb 25, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [7b58208c52](https://linux-hardware.org/?probe=7b58208c52) | Feb 25, 2022 |
| Lenovo        | IdeaPadFlex 5 15ALC05 82... | Convertible | [800ecfe818](https://linux-hardware.org/?probe=800ecfe818) | Feb 24, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [03a5ed6072](https://linux-hardware.org/?probe=03a5ed6072) | Feb 24, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [e1ddcb9f9a](https://linux-hardware.org/?probe=e1ddcb9f9a) | Feb 24, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b94d0c6e20](https://linux-hardware.org/?probe=b94d0c6e20) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [13b7868e73](https://linux-hardware.org/?probe=13b7868e73) | Feb 24, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0e9130cffe](https://linux-hardware.org/?probe=0e9130cffe) | Feb 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [eb017e14fa](https://linux-hardware.org/?probe=eb017e14fa) | Feb 24, 2022 |
| Google        | Snappy                      | Notebook    | [cf0b11bd65](https://linux-hardware.org/?probe=cf0b11bd65) | Feb 24, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [15df5df598](https://linux-hardware.org/?probe=15df5df598) | Feb 24, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [020df21e37](https://linux-hardware.org/?probe=020df21e37) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | Notebook    | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| Lenovo        | IdeaPad 3 15IML05 U 81WB    | Notebook    | [73c7d63295](https://linux-hardware.org/?probe=73c7d63295) | Feb 23, 2022 |
| Google        | Edgar                       | Notebook    | [46f5948f03](https://linux-hardware.org/?probe=46f5948f03) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f09566c9ee](https://linux-hardware.org/?probe=f09566c9ee) | Feb 23, 2022 |
| Samsung       | 750XDA                      | Notebook    | [ad6823c08e](https://linux-hardware.org/?probe=ad6823c08e) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | Notebook    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| MSI           | GE63VR 7RF                  | Notebook    | [68e1d81309](https://linux-hardware.org/?probe=68e1d81309) | Feb 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [88734fe9a0](https://linux-hardware.org/?probe=88734fe9a0) | Feb 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [677ffe54b5](https://linux-hardware.org/?probe=677ffe54b5) | Feb 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [9d3f01a706](https://linux-hardware.org/?probe=9d3f01a706) | Feb 23, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [228e9e9d0c](https://linux-hardware.org/?probe=228e9e9d0c) | Feb 23, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [1a4f0d32ab](https://linux-hardware.org/?probe=1a4f0d32ab) | Feb 22, 2022 |
| Lenovo        | 30D2 NOK                    | Desktop     | [108296cf9b](https://linux-hardware.org/?probe=108296cf9b) | Feb 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d32c812d2b](https://linux-hardware.org/?probe=d32c812d2b) | Feb 22, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [0d69aa634e](https://linux-hardware.org/?probe=0d69aa634e) | Feb 22, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5825d4fcaf](https://linux-hardware.org/?probe=5825d4fcaf) | Feb 22, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [b9cb7cad60](https://linux-hardware.org/?probe=b9cb7cad60) | Feb 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ee3ef301c2](https://linux-hardware.org/?probe=ee3ef301c2) | Feb 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [67deab7343](https://linux-hardware.org/?probe=67deab7343) | Feb 22, 2022 |
| Jumper        | EZbook                      | Notebook    | [9cded25245](https://linux-hardware.org/?probe=9cded25245) | Feb 22, 2022 |
| ASUSTek       | P5QL                        | Desktop     | [2714d59901](https://linux-hardware.org/?probe=2714d59901) | Feb 22, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [94c0f0f3a3](https://linux-hardware.org/?probe=94c0f0f3a3) | Feb 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [6c4ff21b02](https://linux-hardware.org/?probe=6c4ff21b02) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c8223731dc](https://linux-hardware.org/?probe=c8223731dc) | Feb 21, 2022 |
| Panasonic     | CFSV9-1                     | Notebook    | [fa3b39bca1](https://linux-hardware.org/?probe=fa3b39bca1) | Feb 21, 2022 |
| HP            | Notebook                    | Notebook    | [d8dd214532](https://linux-hardware.org/?probe=d8dd214532) | Feb 21, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [debfe75b31](https://linux-hardware.org/?probe=debfe75b31) | Feb 21, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [ebca133032](https://linux-hardware.org/?probe=ebca133032) | Feb 21, 2022 |
| HP            | Laptop 14z-dk100            | Notebook    | [65130b9760](https://linux-hardware.org/?probe=65130b9760) | Feb 21, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [5eb9d81462](https://linux-hardware.org/?probe=5eb9d81462) | Feb 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [558ef9e9d4](https://linux-hardware.org/?probe=558ef9e9d4) | Feb 20, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [388a17923c](https://linux-hardware.org/?probe=388a17923c) | Feb 20, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ad584de4c3](https://linux-hardware.org/?probe=ad584de4c3) | Feb 20, 2022 |
| ASUSTek       | G551JK                      | Notebook    | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [229a11c203](https://linux-hardware.org/?probe=229a11c203) | Feb 20, 2022 |
| Google        | Eve                         | Convertible | [5baf085bb9](https://linux-hardware.org/?probe=5baf085bb9) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [65c44b63d6](https://linux-hardware.org/?probe=65c44b63d6) | Feb 20, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [d8c4226f82](https://linux-hardware.org/?probe=d8c4226f82) | Feb 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2a934577d6](https://linux-hardware.org/?probe=2a934577d6) | Feb 20, 2022 |
| HP            | Notebook                    | Notebook    | [b2bc5693f7](https://linux-hardware.org/?probe=b2bc5693f7) | Feb 20, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | Notebook    | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [5d973743c8](https://linux-hardware.org/?probe=5d973743c8) | Feb 19, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [c73dc0aa9f](https://linux-hardware.org/?probe=c73dc0aa9f) | Feb 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [1ad67d12e0](https://linux-hardware.org/?probe=1ad67d12e0) | Feb 19, 2022 |
| Positivo      | CHT14B                      | Notebook    | [c2f39e4414](https://linux-hardware.org/?probe=c2f39e4414) | Feb 19, 2022 |
| Positivo      | CHT14B                      | Notebook    | [674256dc2a](https://linux-hardware.org/?probe=674256dc2a) | Feb 19, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [eccaa1c72e](https://linux-hardware.org/?probe=eccaa1c72e) | Feb 19, 2022 |
| Gateway       | DX4860                      | Desktop     | [d28784e189](https://linux-hardware.org/?probe=d28784e189) | Feb 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [3d816cc71a](https://linux-hardware.org/?probe=3d816cc71a) | Feb 19, 2022 |
| HP            | ZBook 17 G4                 | Notebook    | [0ac02f47be](https://linux-hardware.org/?probe=0ac02f47be) | Feb 19, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [f988c3bfdc](https://linux-hardware.org/?probe=f988c3bfdc) | Feb 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1c65c7204d](https://linux-hardware.org/?probe=1c65c7204d) | Feb 18, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [4cbc6b81bf](https://linux-hardware.org/?probe=4cbc6b81bf) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b2c662bad6](https://linux-hardware.org/?probe=b2c662bad6) | Feb 18, 2022 |
| Avell High... | B.ON                        | Notebook    | [3b3e1a7730](https://linux-hardware.org/?probe=3b3e1a7730) | Feb 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3221ab6775](https://linux-hardware.org/?probe=3221ab6775) | Feb 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| HP            | Dratini                     | Notebook    | [bb3f3445ee](https://linux-hardware.org/?probe=bb3f3445ee) | Feb 17, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [83e6228c44](https://linux-hardware.org/?probe=83e6228c44) | Feb 17, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [dbe8ddd097](https://linux-hardware.org/?probe=dbe8ddd097) | Feb 17, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [f2d47f2d8b](https://linux-hardware.org/?probe=f2d47f2d8b) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | Notebook    | [c896752de0](https://linux-hardware.org/?probe=c896752de0) | Feb 17, 2022 |
| Inspire Te... | Trio Windows OD 1.0         | Notebook    | [a0f755c28a](https://linux-hardware.org/?probe=a0f755c28a) | Feb 17, 2022 |
| Avell High... | B.ON                        | Notebook    | [26b25d67d6](https://linux-hardware.org/?probe=26b25d67d6) | Feb 17, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1467371e46](https://linux-hardware.org/?probe=1467371e46) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [a74d65bfe6](https://linux-hardware.org/?probe=a74d65bfe6) | Feb 16, 2022 |
| HP            | 82A2                        | Desktop     | [5efad9b732](https://linux-hardware.org/?probe=5efad9b732) | Feb 16, 2022 |
| Acer          | Predator G9-793             | Notebook    | [45ec93214f](https://linux-hardware.org/?probe=45ec93214f) | Feb 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [538072f18d](https://linux-hardware.org/?probe=538072f18d) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e03bf2b8a8](https://linux-hardware.org/?probe=e03bf2b8a8) | Feb 16, 2022 |
| System76      | Lemur Pro                   | Notebook    | [3a7527d1e3](https://linux-hardware.org/?probe=3a7527d1e3) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [faca13ef0b](https://linux-hardware.org/?probe=faca13ef0b) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [d2f55f9d63](https://linux-hardware.org/?probe=d2f55f9d63) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e3eee22fef](https://linux-hardware.org/?probe=e3eee22fef) | Feb 16, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [a6c76eb5f6](https://linux-hardware.org/?probe=a6c76eb5f6) | Feb 15, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [6d024608a5](https://linux-hardware.org/?probe=6d024608a5) | Feb 15, 2022 |
| HP            | Pavilion x2 Detachable      | Tablet      | [16b7c17050](https://linux-hardware.org/?probe=16b7c17050) | Feb 15, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e4220e0244](https://linux-hardware.org/?probe=e4220e0244) | Feb 15, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | Notebook    | [9a9f646438](https://linux-hardware.org/?probe=9a9f646438) | Feb 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [68f6b7dd88](https://linux-hardware.org/?probe=68f6b7dd88) | Feb 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [890fea8813](https://linux-hardware.org/?probe=890fea8813) | Feb 15, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [881b6c0f83](https://linux-hardware.org/?probe=881b6c0f83) | Feb 15, 2022 |
| Dell          | 0YM158 A00                  | Server      | [c022b50299](https://linux-hardware.org/?probe=c022b50299) | Feb 14, 2022 |
| ASUSTek       | X550WE                      | Notebook    | [beed529fc3](https://linux-hardware.org/?probe=beed529fc3) | Feb 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b1de32eb02](https://linux-hardware.org/?probe=b1de32eb02) | Feb 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [f199e025e3](https://linux-hardware.org/?probe=f199e025e3) | Feb 14, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [701eeea0ed](https://linux-hardware.org/?probe=701eeea0ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [32022a8232](https://linux-hardware.org/?probe=32022a8232) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [372c231b58](https://linux-hardware.org/?probe=372c231b58) | Feb 14, 2022 |
| RCA           | W101AS23T2                  | Tablet      | [23fbc9a6ee](https://linux-hardware.org/?probe=23fbc9a6ee) | Feb 14, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [a82c9b223f](https://linux-hardware.org/?probe=a82c9b223f) | Feb 14, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [4c61db4a18](https://linux-hardware.org/?probe=4c61db4a18) | Feb 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a8c5477e60](https://linux-hardware.org/?probe=a8c5477e60) | Feb 13, 2022 |
| Lenovo        | ThinkPad Edge E531 68851... | Notebook    | [e82c11b42e](https://linux-hardware.org/?probe=e82c11b42e) | Feb 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [a4471fe730](https://linux-hardware.org/?probe=a4471fe730) | Feb 13, 2022 |
| ECS           | A58F2P-M4                   | Desktop     | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [1f5dd04a09](https://linux-hardware.org/?probe=1f5dd04a09) | Feb 13, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [aeec085062](https://linux-hardware.org/?probe=aeec085062) | Feb 13, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [5e0b855dbf](https://linux-hardware.org/?probe=5e0b855dbf) | Feb 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [84005ca8f9](https://linux-hardware.org/?probe=84005ca8f9) | Feb 12, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [91fa01f5a6](https://linux-hardware.org/?probe=91fa01f5a6) | Feb 12, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [dc1249f2a1](https://linux-hardware.org/?probe=dc1249f2a1) | Feb 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [42674c38b2](https://linux-hardware.org/?probe=42674c38b2) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Biostar       | AM1ML                       | Desktop     | [54e50bd790](https://linux-hardware.org/?probe=54e50bd790) | Feb 12, 2022 |
| Biostar       | AM1ML                       | Desktop     | [e933dbc718](https://linux-hardware.org/?probe=e933dbc718) | Feb 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [359fac7afc](https://linux-hardware.org/?probe=359fac7afc) | Feb 12, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [f8e7f688a6](https://linux-hardware.org/?probe=f8e7f688a6) | Feb 11, 2022 |
| Intel         | NUC11TNBi7 M11895-402       | Mini pc     | [23fce48df7](https://linux-hardware.org/?probe=23fce48df7) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [4c500fd383](https://linux-hardware.org/?probe=4c500fd383) | Feb 11, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [9a8cc4cbd7](https://linux-hardware.org/?probe=9a8cc4cbd7) | Feb 11, 2022 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [2cfb1f14b9](https://linux-hardware.org/?probe=2cfb1f14b9) | Feb 10, 2022 |
| Dell          | Latitude 5511               | Notebook    | [7a45e17643](https://linux-hardware.org/?probe=7a45e17643) | Feb 10, 2022 |
| Dell          | Latitude 5511               | Notebook    | [bf3129ad00](https://linux-hardware.org/?probe=bf3129ad00) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b2d14e7f15](https://linux-hardware.org/?probe=b2d14e7f15) | Feb 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2661cf0743](https://linux-hardware.org/?probe=2661cf0743) | Feb 10, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [60ee5faa6c](https://linux-hardware.org/?probe=60ee5faa6c) | Feb 10, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [ac4b2855c6](https://linux-hardware.org/?probe=ac4b2855c6) | Feb 10, 2022 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [1b903af2df](https://linux-hardware.org/?probe=1b903af2df) | Feb 10, 2022 |
| RCA           | W101AS23T2                  | Tablet      | [c61d480ba0](https://linux-hardware.org/?probe=c61d480ba0) | Feb 09, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [4906efe7f4](https://linux-hardware.org/?probe=4906efe7f4) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [83ab33660d](https://linux-hardware.org/?probe=83ab33660d) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [52bec77385](https://linux-hardware.org/?probe=52bec77385) | Feb 09, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [52d6fa9b66](https://linux-hardware.org/?probe=52d6fa9b66) | Feb 09, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [87d3fd2916](https://linux-hardware.org/?probe=87d3fd2916) | Feb 09, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [dea0b07f08](https://linux-hardware.org/?probe=dea0b07f08) | Feb 08, 2022 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | Notebook    | [b7e0365760](https://linux-hardware.org/?probe=b7e0365760) | Feb 08, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [55fda8de04](https://linux-hardware.org/?probe=55fda8de04) | Feb 08, 2022 |
| ASUSTek       | TUF GAMING Z690-PLUS WIF... | Desktop     | [ab81e91207](https://linux-hardware.org/?probe=ab81e91207) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [29ca9095c4](https://linux-hardware.org/?probe=29ca9095c4) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [24a7621237](https://linux-hardware.org/?probe=24a7621237) | Feb 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [b4cfe297d4](https://linux-hardware.org/?probe=b4cfe297d4) | Feb 08, 2022 |
| Lenovo        | ThinkPad X230 23257R2       | Notebook    | [4fa07e0a61](https://linux-hardware.org/?probe=4fa07e0a61) | Feb 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [b400a64d30](https://linux-hardware.org/?probe=b400a64d30) | Feb 07, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [cb02bc65cc](https://linux-hardware.org/?probe=cb02bc65cc) | Feb 07, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [e7b3bb2161](https://linux-hardware.org/?probe=e7b3bb2161) | Feb 07, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [97a6c42f5f](https://linux-hardware.org/?probe=97a6c42f5f) | Feb 07, 2022 |
| HP            | Pavilion dv6                | Notebook    | [0ba10bc3bb](https://linux-hardware.org/?probe=0ba10bc3bb) | Feb 07, 2022 |
| Lenovo        | Unknown                     | Notebook    | [8f315e1abe](https://linux-hardware.org/?probe=8f315e1abe) | Feb 07, 2022 |
| Lenovo        | Unknown                     | Notebook    | [bf281646d9](https://linux-hardware.org/?probe=bf281646d9) | Feb 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5b6802c8e3](https://linux-hardware.org/?probe=5b6802c8e3) | Feb 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [61e4b1c45e](https://linux-hardware.org/?probe=61e4b1c45e) | Feb 06, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [824af874a4](https://linux-hardware.org/?probe=824af874a4) | Feb 06, 2022 |
| Lenovo        | G70-70 80HW007LNX           | Notebook    | [79e8d4895c](https://linux-hardware.org/?probe=79e8d4895c) | Feb 06, 2022 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [3364f4de6b](https://linux-hardware.org/?probe=3364f4de6b) | Feb 06, 2022 |
| HP            | Compaq 6730s                | Notebook    | [8d1fa47bb0](https://linux-hardware.org/?probe=8d1fa47bb0) | Feb 06, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [73db0d90e9](https://linux-hardware.org/?probe=73db0d90e9) | Feb 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [830c0232b6](https://linux-hardware.org/?probe=830c0232b6) | Feb 06, 2022 |
| MSI           | Z77A-GD65 GAMING            | Desktop     | [8d2cf11a20](https://linux-hardware.org/?probe=8d2cf11a20) | Feb 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [97911feaef](https://linux-hardware.org/?probe=97911feaef) | Feb 06, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [5714dfdd29](https://linux-hardware.org/?probe=5714dfdd29) | Feb 06, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [2b0f2f8139](https://linux-hardware.org/?probe=2b0f2f8139) | Feb 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [92a8bf9033](https://linux-hardware.org/?probe=92a8bf9033) | Feb 06, 2022 |
| ASUSTek       | GL702VSK                    | Notebook    | [d3eb319919](https://linux-hardware.org/?probe=d3eb319919) | Feb 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a3397b67bd](https://linux-hardware.org/?probe=a3397b67bd) | Feb 05, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Supermicro    | X9DRW                       | Desktop     | [432d4db3ea](https://linux-hardware.org/?probe=432d4db3ea) | Feb 05, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [79e02b1ade](https://linux-hardware.org/?probe=79e02b1ade) | Feb 05, 2022 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [ce23fdbead](https://linux-hardware.org/?probe=ce23fdbead) | Feb 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63a70836f3](https://linux-hardware.org/?probe=63a70836f3) | Feb 05, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [f1faf40bb4](https://linux-hardware.org/?probe=f1faf40bb4) | Feb 05, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [08962dc9f9](https://linux-hardware.org/?probe=08962dc9f9) | Feb 05, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [cd81e5ce82](https://linux-hardware.org/?probe=cd81e5ce82) | Feb 05, 2022 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [6f0d26a803](https://linux-hardware.org/?probe=6f0d26a803) | Feb 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [d457ee5311](https://linux-hardware.org/?probe=d457ee5311) | Feb 05, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [7b28e44b0e](https://linux-hardware.org/?probe=7b28e44b0e) | Feb 05, 2022 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [5256293dec](https://linux-hardware.org/?probe=5256293dec) | Feb 05, 2022 |
| Framework     | Laptop                      | Notebook    | [64e6669cbc](https://linux-hardware.org/?probe=64e6669cbc) | Feb 04, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [8d4968c10a](https://linux-hardware.org/?probe=8d4968c10a) | Feb 04, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [cab5335d99](https://linux-hardware.org/?probe=cab5335d99) | Feb 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [548f756c0e](https://linux-hardware.org/?probe=548f756c0e) | Feb 04, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [6bc39a1855](https://linux-hardware.org/?probe=6bc39a1855) | Feb 04, 2022 |
| Toshiba       | Satellite C645              | Notebook    | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e799f33b3f](https://linux-hardware.org/?probe=e799f33b3f) | Feb 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ca238c69a5](https://linux-hardware.org/?probe=ca238c69a5) | Feb 04, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [f10bee8b8f](https://linux-hardware.org/?probe=f10bee8b8f) | Feb 04, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [9a45aba28e](https://linux-hardware.org/?probe=9a45aba28e) | Feb 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [862367b523](https://linux-hardware.org/?probe=862367b523) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [4df88dcf23](https://linux-hardware.org/?probe=4df88dcf23) | Feb 03, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9da6b947f5](https://linux-hardware.org/?probe=9da6b947f5) | Feb 03, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [d9cc5f0548](https://linux-hardware.org/?probe=d9cc5f0548) | Feb 03, 2022 |
| Dell          | Latitude E6230              | Notebook    | [05d9080c0c](https://linux-hardware.org/?probe=05d9080c0c) | Feb 03, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [83678f76fc](https://linux-hardware.org/?probe=83678f76fc) | Feb 03, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [f37fe196d0](https://linux-hardware.org/?probe=f37fe196d0) | Feb 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [104c871438](https://linux-hardware.org/?probe=104c871438) | Feb 03, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [dca1097e4a](https://linux-hardware.org/?probe=dca1097e4a) | Feb 02, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [2cb72b3867](https://linux-hardware.org/?probe=2cb72b3867) | Feb 02, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [f111410eeb](https://linux-hardware.org/?probe=f111410eeb) | Feb 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [813bec5fe7](https://linux-hardware.org/?probe=813bec5fe7) | Feb 02, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [26a4917db5](https://linux-hardware.org/?probe=26a4917db5) | Feb 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7ea870fff3](https://linux-hardware.org/?probe=7ea870fff3) | Feb 02, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [978273c0aa](https://linux-hardware.org/?probe=978273c0aa) | Feb 02, 2022 |
| Sony          | SVD1121Q2EB                 | Notebook    | [8e484b15d2](https://linux-hardware.org/?probe=8e484b15d2) | Feb 02, 2022 |
| ASRock        | A320M-HD R4.0               | Desktop     | [f2dfa50076](https://linux-hardware.org/?probe=f2dfa50076) | Feb 02, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [a6321e237c](https://linux-hardware.org/?probe=a6321e237c) | Feb 01, 2022 |
| HP            | ProBook 6465b               | Notebook    | [aca95b9f2d](https://linux-hardware.org/?probe=aca95b9f2d) | Feb 01, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [c9cae610a6](https://linux-hardware.org/?probe=c9cae610a6) | Feb 01, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [6c8a746762](https://linux-hardware.org/?probe=6c8a746762) | Feb 01, 2022 |
| Samsung       | RV409/RV509/RV709           | Notebook    | [535f5504f0](https://linux-hardware.org/?probe=535f5504f0) | Feb 01, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c60e8a85c4](https://linux-hardware.org/?probe=c60e8a85c4) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fb9c5fac50](https://linux-hardware.org/?probe=fb9c5fac50) | Feb 01, 2022 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [9ba4b1306f](https://linux-hardware.org/?probe=9ba4b1306f) | Jan 31, 2022 |
| Dell          | Precision 5530              | Notebook    | [3bb85a7897](https://linux-hardware.org/?probe=3bb85a7897) | Jan 31, 2022 |
| ASUSTek       | VivoBook Flip 14_ASUS Fl... | Convertible | [fc5490ffca](https://linux-hardware.org/?probe=fc5490ffca) | Jan 31, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [b7796bb104](https://linux-hardware.org/?probe=b7796bb104) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [8efcb72970](https://linux-hardware.org/?probe=8efcb72970) | Jan 31, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [d8cbfade46](https://linux-hardware.org/?probe=d8cbfade46) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [316ea97198](https://linux-hardware.org/?probe=316ea97198) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [940c2e990d](https://linux-hardware.org/?probe=940c2e990d) | Jan 31, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [49bd28cbf5](https://linux-hardware.org/?probe=49bd28cbf5) | Jan 31, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [337397846d](https://linux-hardware.org/?probe=337397846d) | Jan 31, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [ebe757d792](https://linux-hardware.org/?probe=ebe757d792) | Jan 30, 2022 |
| Dell          | Latitude 7490               | Notebook    | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N2000LFR    | Notebook    | [0c7293a8ec](https://linux-hardware.org/?probe=0c7293a8ec) | Jan 30, 2022 |
| Lenovo        | ThinkPad T420 4180F65       | Notebook    | [23a97a1da0](https://linux-hardware.org/?probe=23a97a1da0) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [88eae6cdfb](https://linux-hardware.org/?probe=88eae6cdfb) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [d8040d8fc4](https://linux-hardware.org/?probe=d8040d8fc4) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c1494af863](https://linux-hardware.org/?probe=c1494af863) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | Notebook    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS_BR     | Desktop     | [dc652a6ac4](https://linux-hardware.org/?probe=dc652a6ac4) | Jan 30, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | Notebook    | [209156e57d](https://linux-hardware.org/?probe=209156e57d) | Jan 29, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | Notebook    | [2f9a17c907](https://linux-hardware.org/?probe=2f9a17c907) | Jan 29, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [e06431af49](https://linux-hardware.org/?probe=e06431af49) | Jan 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [2440be23b6](https://linux-hardware.org/?probe=2440be23b6) | Jan 29, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4a98af8b6c](https://linux-hardware.org/?probe=4a98af8b6c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [e6af97e09c](https://linux-hardware.org/?probe=e6af97e09c) | Jan 29, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| HP            | ProLiant DL580 G7           | Server      | [fe6b8cb2e4](https://linux-hardware.org/?probe=fe6b8cb2e4) | Jan 29, 2022 |
| Dell          | Latitude 5511               | Notebook    | [94f621a74b](https://linux-hardware.org/?probe=94f621a74b) | Jan 29, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | Notebook    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | Notebook    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c573633ba7](https://linux-hardware.org/?probe=c573633ba7) | Jan 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [bab2021d07](https://linux-hardware.org/?probe=bab2021d07) | Jan 28, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [83cdfa61a4](https://linux-hardware.org/?probe=83cdfa61a4) | Jan 28, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [64f7ad2ba1](https://linux-hardware.org/?probe=64f7ad2ba1) | Jan 27, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [ed43351639](https://linux-hardware.org/?probe=ed43351639) | Jan 27, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d112bf0361](https://linux-hardware.org/?probe=d112bf0361) | Jan 27, 2022 |
| Mediacom      | GTZS                        | Notebook    | [10a0d977b0](https://linux-hardware.org/?probe=10a0d977b0) | Jan 27, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [e422d19fb3](https://linux-hardware.org/?probe=e422d19fb3) | Jan 27, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [2d778a328d](https://linux-hardware.org/?probe=2d778a328d) | Jan 27, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [82ee6777f1](https://linux-hardware.org/?probe=82ee6777f1) | Jan 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [267ee0e693](https://linux-hardware.org/?probe=267ee0e693) | Jan 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [a72f036b05](https://linux-hardware.org/?probe=a72f036b05) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b930fcaa84](https://linux-hardware.org/?probe=b930fcaa84) | Jan 26, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [95d6e59e28](https://linux-hardware.org/?probe=95d6e59e28) | Jan 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3a25d57a74](https://linux-hardware.org/?probe=3a25d57a74) | Jan 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [dc01d09a1d](https://linux-hardware.org/?probe=dc01d09a1d) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [738074142b](https://linux-hardware.org/?probe=738074142b) | Jan 26, 2022 |
| Gigabyte      | P55A-UD7                    | Desktop     | [084f158a19](https://linux-hardware.org/?probe=084f158a19) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [1bd39d2b68](https://linux-hardware.org/?probe=1bd39d2b68) | Jan 26, 2022 |
| Intel         | S1200RP G62251-405          | Server      | [7023226f81](https://linux-hardware.org/?probe=7023226f81) | Jan 26, 2022 |
| MSI           | Z270M MORTAR                | Desktop     | [2493fd0195](https://linux-hardware.org/?probe=2493fd0195) | Jan 26, 2022 |
| Intel         | S1200RP G62251-405          | Server      | [d3e6916421](https://linux-hardware.org/?probe=d3e6916421) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [9613005856](https://linux-hardware.org/?probe=9613005856) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | Notebook    | [36a39bf7eb](https://linux-hardware.org/?probe=36a39bf7eb) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | Notebook    | [9d12ae4f9a](https://linux-hardware.org/?probe=9d12ae4f9a) | Jan 26, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [e9f06efa7a](https://linux-hardware.org/?probe=e9f06efa7a) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [041c78217d](https://linux-hardware.org/?probe=041c78217d) | Jan 26, 2022 |
| Dell          | Precision 5510              | Notebook    | [511eeac9a0](https://linux-hardware.org/?probe=511eeac9a0) | Jan 25, 2022 |
| Dell          | Latitude E7470              | Notebook    | [c47b0efb73](https://linux-hardware.org/?probe=c47b0efb73) | Jan 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5846d2031f](https://linux-hardware.org/?probe=5846d2031f) | Jan 25, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [875671a912](https://linux-hardware.org/?probe=875671a912) | Jan 25, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c7fbcbcd07](https://linux-hardware.org/?probe=c7fbcbcd07) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [6593d27252](https://linux-hardware.org/?probe=6593d27252) | Jan 24, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [b5899e206a](https://linux-hardware.org/?probe=b5899e206a) | Jan 24, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [ec67e898bd](https://linux-hardware.org/?probe=ec67e898bd) | Jan 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [d40c14312b](https://linux-hardware.org/?probe=d40c14312b) | Jan 24, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [1fabe2847b](https://linux-hardware.org/?probe=1fabe2847b) | Jan 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b812fc3ed2](https://linux-hardware.org/?probe=b812fc3ed2) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK U9311X             | Convertible | [9918c37b0c](https://linux-hardware.org/?probe=9918c37b0c) | Jan 24, 2022 |
| HP            | 1497                        | Desktop     | [7761e5755c](https://linux-hardware.org/?probe=7761e5755c) | Jan 24, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [dd33a742c9](https://linux-hardware.org/?probe=dd33a742c9) | Jan 24, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [f8afc9746e](https://linux-hardware.org/?probe=f8afc9746e) | Jan 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3ceffb0902](https://linux-hardware.org/?probe=3ceffb0902) | Jan 24, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [619b081f40](https://linux-hardware.org/?probe=619b081f40) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [79e2d3dc48](https://linux-hardware.org/?probe=79e2d3dc48) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [937ad3940c](https://linux-hardware.org/?probe=937ad3940c) | Jan 23, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2ae5feb6c8](https://linux-hardware.org/?probe=2ae5feb6c8) | Jan 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [34568da477](https://linux-hardware.org/?probe=34568da477) | Jan 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [d6ea0ad749](https://linux-hardware.org/?probe=d6ea0ad749) | Jan 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [1cb9ebbbd4](https://linux-hardware.org/?probe=1cb9ebbbd4) | Jan 23, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [10b9d78b55](https://linux-hardware.org/?probe=10b9d78b55) | Jan 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e10bf3d056](https://linux-hardware.org/?probe=e10bf3d056) | Jan 23, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [1bea66eb77](https://linux-hardware.org/?probe=1bea66eb77) | Jan 23, 2022 |
| SCHNEIDER     | SCL141CTP                   | Notebook    | [ff14e3fa97](https://linux-hardware.org/?probe=ff14e3fa97) | Jan 23, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [38c5a8b4f6](https://linux-hardware.org/?probe=38c5a8b4f6) | Jan 23, 2022 |
| Lenovo        | 3172 SDK0T08861 WIN 3305... | Mini pc     | [fa29a65816](https://linux-hardware.org/?probe=fa29a65816) | Jan 23, 2022 |
| Lenovo        | 3172 SDK0T08861 WIN 3305... | Mini pc     | [c5dbd167d2](https://linux-hardware.org/?probe=c5dbd167d2) | Jan 23, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [18ce23e783](https://linux-hardware.org/?probe=18ce23e783) | Jan 23, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [783456509a](https://linux-hardware.org/?probe=783456509a) | Jan 22, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [6610c7d6e1](https://linux-hardware.org/?probe=6610c7d6e1) | Jan 22, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| Acer          | TravelMate Spin B311R-31    | Convertible | [61aa24c314](https://linux-hardware.org/?probe=61aa24c314) | Jan 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [427ce82d40](https://linux-hardware.org/?probe=427ce82d40) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b006be0c8b](https://linux-hardware.org/?probe=b006be0c8b) | Jan 22, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [db0a0adc46](https://linux-hardware.org/?probe=db0a0adc46) | Jan 22, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [992e0c224c](https://linux-hardware.org/?probe=992e0c224c) | Jan 22, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [2c0f007811](https://linux-hardware.org/?probe=2c0f007811) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [636e98e6e5](https://linux-hardware.org/?probe=636e98e6e5) | Jan 21, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [ada27693c4](https://linux-hardware.org/?probe=ada27693c4) | Jan 21, 2022 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [cbc42a2c14](https://linux-hardware.org/?probe=cbc42a2c14) | Jan 21, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [68c71dac17](https://linux-hardware.org/?probe=68c71dac17) | Jan 21, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [485c5e0968](https://linux-hardware.org/?probe=485c5e0968) | Jan 21, 2022 |
| Notebook      | NH55RGQ                     | Notebook    | [92e8102b7d](https://linux-hardware.org/?probe=92e8102b7d) | Jan 21, 2022 |
| Dell          | Latitude E6530              | Notebook    | [bf71e70abb](https://linux-hardware.org/?probe=bf71e70abb) | Jan 21, 2022 |
| Dell          | Inspiron 7591               | Notebook    | [2f1c294587](https://linux-hardware.org/?probe=2f1c294587) | Jan 21, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [c63c055197](https://linux-hardware.org/?probe=c63c055197) | Jan 21, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [8e39cc0d01](https://linux-hardware.org/?probe=8e39cc0d01) | Jan 21, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [172a8a48ad](https://linux-hardware.org/?probe=172a8a48ad) | Jan 21, 2022 |
| BESSTAR Te... | HM50                        | Desktop     | [ddc2e44fcc](https://linux-hardware.org/?probe=ddc2e44fcc) | Jan 21, 2022 |
| HP            | ProLiant DL580 G7           | Server      | [8c817d64a7](https://linux-hardware.org/?probe=8c817d64a7) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [1b1004081a](https://linux-hardware.org/?probe=1b1004081a) | Jan 21, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5a010a60d7](https://linux-hardware.org/?probe=5a010a60d7) | Jan 20, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [03a8c77758](https://linux-hardware.org/?probe=03a8c77758) | Jan 20, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [df698a1427](https://linux-hardware.org/?probe=df698a1427) | Jan 20, 2022 |
| Lenovo        | B490 37722QP                | Notebook    | [6b32b6b8ef](https://linux-hardware.org/?probe=6b32b6b8ef) | Jan 20, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [04926d5643](https://linux-hardware.org/?probe=04926d5643) | Jan 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [af3563e3e7](https://linux-hardware.org/?probe=af3563e3e7) | Jan 20, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | Notebook    | [0ae4377d83](https://linux-hardware.org/?probe=0ae4377d83) | Jan 19, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [30829ce42e](https://linux-hardware.org/?probe=30829ce42e) | Jan 19, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | Notebook    | [1a128aada0](https://linux-hardware.org/?probe=1a128aada0) | Jan 19, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a846ee2ac3](https://linux-hardware.org/?probe=a846ee2ac3) | Jan 19, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [72415f94c8](https://linux-hardware.org/?probe=72415f94c8) | Jan 19, 2022 |
| Positivo      | H14BU08                     | Notebook    | [8fb0d7e730](https://linux-hardware.org/?probe=8fb0d7e730) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [87c1802929](https://linux-hardware.org/?probe=87c1802929) | Jan 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [a2e70fe7b1](https://linux-hardware.org/?probe=a2e70fe7b1) | Jan 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [533f74b810](https://linux-hardware.org/?probe=533f74b810) | Jan 19, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | Notebook    | [2407b5f5bb](https://linux-hardware.org/?probe=2407b5f5bb) | Jan 19, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [ab286ab82d](https://linux-hardware.org/?probe=ab286ab82d) | Jan 19, 2022 |
| Dell          | Latitude E6530              | Notebook    | [8559d4a5b0](https://linux-hardware.org/?probe=8559d4a5b0) | Jan 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ca82eeb3d3](https://linux-hardware.org/?probe=ca82eeb3d3) | Jan 19, 2022 |
| MSI           | H310M PRO-VH                | Desktop     | [844791ed3e](https://linux-hardware.org/?probe=844791ed3e) | Jan 19, 2022 |
| Dell          | 0PP150 A00                  | Desktop     | [851a920599](https://linux-hardware.org/?probe=851a920599) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c4103d5c5a](https://linux-hardware.org/?probe=c4103d5c5a) | Jan 19, 2022 |
| Lenovo        | B490 37722QP                | Notebook    | [3113fb2078](https://linux-hardware.org/?probe=3113fb2078) | Jan 18, 2022 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [3dd363739d](https://linux-hardware.org/?probe=3dd363739d) | Jan 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [01e009ebd0](https://linux-hardware.org/?probe=01e009ebd0) | Jan 18, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [e4489c39b8](https://linux-hardware.org/?probe=e4489c39b8) | Jan 18, 2022 |
| Gigabyte      | Z590 AORUS MASTER           | Desktop     | [db8f93ad4a](https://linux-hardware.org/?probe=db8f93ad4a) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | Notebook    | [a168ef0aa5](https://linux-hardware.org/?probe=a168ef0aa5) | Jan 18, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [fc51156352](https://linux-hardware.org/?probe=fc51156352) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [70537beab1](https://linux-hardware.org/?probe=70537beab1) | Jan 17, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [7451fd2f02](https://linux-hardware.org/?probe=7451fd2f02) | Jan 17, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [738f12d2e4](https://linux-hardware.org/?probe=738f12d2e4) | Jan 17, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [d6edc6139f](https://linux-hardware.org/?probe=d6edc6139f) | Jan 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [6c949f1929](https://linux-hardware.org/?probe=6c949f1929) | Jan 17, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [8d78cc6770](https://linux-hardware.org/?probe=8d78cc6770) | Jan 16, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | Notebook    | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| HP            | 1494                        | Desktop     | [c03b887753](https://linux-hardware.org/?probe=c03b887753) | Jan 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [6a024b63f0](https://linux-hardware.org/?probe=6a024b63f0) | Jan 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [01f17fdaa9](https://linux-hardware.org/?probe=01f17fdaa9) | Jan 16, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [ef86d029ff](https://linux-hardware.org/?probe=ef86d029ff) | Jan 16, 2022 |
| Notebook      | NS50MU                      | Notebook    | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [a61f1b9d56](https://linux-hardware.org/?probe=a61f1b9d56) | Jan 16, 2022 |
| Acer          | Veriton X6620G v1.0         | Desktop     | [8ef5b3632a](https://linux-hardware.org/?probe=8ef5b3632a) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [0c41cd2cd0](https://linux-hardware.org/?probe=0c41cd2cd0) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [750744f996](https://linux-hardware.org/?probe=750744f996) | Jan 16, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [d5bd08abac](https://linux-hardware.org/?probe=d5bd08abac) | Jan 16, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2098bc3881](https://linux-hardware.org/?probe=2098bc3881) | Jan 16, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [829a2b8221](https://linux-hardware.org/?probe=829a2b8221) | Jan 15, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [339d7aa470](https://linux-hardware.org/?probe=339d7aa470) | Jan 15, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [6903f0230f](https://linux-hardware.org/?probe=6903f0230f) | Jan 15, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [c458fb3c47](https://linux-hardware.org/?probe=c458fb3c47) | Jan 15, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [30309c0416](https://linux-hardware.org/?probe=30309c0416) | Jan 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [779202413e](https://linux-hardware.org/?probe=779202413e) | Jan 15, 2022 |
| Dell          | 0NDYHG A01                  | Desktop     | [cc3a8808e7](https://linux-hardware.org/?probe=cc3a8808e7) | Jan 15, 2022 |
| Dell          | Latitude 5480               | Notebook    | [6e363cb43c](https://linux-hardware.org/?probe=6e363cb43c) | Jan 15, 2022 |
| HP            | 15                          | Notebook    | [65d1bd3651](https://linux-hardware.org/?probe=65d1bd3651) | Jan 15, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [2c877954ab](https://linux-hardware.org/?probe=2c877954ab) | Jan 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [350fb6b638](https://linux-hardware.org/?probe=350fb6b638) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [4151d78b0a](https://linux-hardware.org/?probe=4151d78b0a) | Jan 14, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [322291a7b1](https://linux-hardware.org/?probe=322291a7b1) | Jan 14, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [f695de13bf](https://linux-hardware.org/?probe=f695de13bf) | Jan 14, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [7bf06ab6f0](https://linux-hardware.org/?probe=7bf06ab6f0) | Jan 14, 2022 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [7de1f8971f](https://linux-hardware.org/?probe=7de1f8971f) | Jan 14, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [e1d5a4a319](https://linux-hardware.org/?probe=e1d5a4a319) | Jan 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0f49e3c67f](https://linux-hardware.org/?probe=0f49e3c67f) | Jan 14, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [21dddfe6a8](https://linux-hardware.org/?probe=21dddfe6a8) | Jan 14, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [0fbef723d5](https://linux-hardware.org/?probe=0fbef723d5) | Jan 14, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [bef980429e](https://linux-hardware.org/?probe=bef980429e) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b2ac4f1622](https://linux-hardware.org/?probe=b2ac4f1622) | Jan 13, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [dfe91144b0](https://linux-hardware.org/?probe=dfe91144b0) | Jan 13, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [247f2934b0](https://linux-hardware.org/?probe=247f2934b0) | Jan 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [ee8a872afd](https://linux-hardware.org/?probe=ee8a872afd) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS2CH0... | Notebook    | [7f440733c2](https://linux-hardware.org/?probe=7f440733c2) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [e9f23e9f5f](https://linux-hardware.org/?probe=e9f23e9f5f) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [85d81f357a](https://linux-hardware.org/?probe=85d81f357a) | Jan 13, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [9404914df6](https://linux-hardware.org/?probe=9404914df6) | Jan 13, 2022 |
| Lenovo        | ThinkPad T430u 3351CTO      | Notebook    | [41f9777fcf](https://linux-hardware.org/?probe=41f9777fcf) | Jan 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f8b504601e](https://linux-hardware.org/?probe=f8b504601e) | Jan 13, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [c7567b5c29](https://linux-hardware.org/?probe=c7567b5c29) | Jan 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [216bfa74a9](https://linux-hardware.org/?probe=216bfa74a9) | Jan 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [45d63385d2](https://linux-hardware.org/?probe=45d63385d2) | Jan 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | Notebook    | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [538e62155e](https://linux-hardware.org/?probe=538e62155e) | Jan 11, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [10dea3ac81](https://linux-hardware.org/?probe=10dea3ac81) | Jan 11, 2022 |
| Lenovo        | IdeaPad Y470 20090          | Notebook    | [29ff376953](https://linux-hardware.org/?probe=29ff376953) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [34bf588c0b](https://linux-hardware.org/?probe=34bf588c0b) | Jan 11, 2022 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [f05cc95e99](https://linux-hardware.org/?probe=f05cc95e99) | Jan 11, 2022 |
| Dell          | Venue 10 Pro 5055           | Notebook    | [22d084e747](https://linux-hardware.org/?probe=22d084e747) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [63c5a7136b](https://linux-hardware.org/?probe=63c5a7136b) | Jan 11, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a62f3505fe](https://linux-hardware.org/?probe=a62f3505fe) | Jan 11, 2022 |
| Lenovo        | ThinkPad T530 239265U       | Notebook    | [5aba32fde1](https://linux-hardware.org/?probe=5aba32fde1) | Jan 11, 2022 |
| ASRock        | B360M IB-R1                 | Desktop     | [afb5a134ce](https://linux-hardware.org/?probe=afb5a134ce) | Jan 11, 2022 |
| Samsung       | 930QAA                      | Convertible | [56758d8bfb](https://linux-hardware.org/?probe=56758d8bfb) | Jan 10, 2022 |
| Samsung       | 930QAA                      | Convertible | [206f508be5](https://linux-hardware.org/?probe=206f508be5) | Jan 10, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [5668d7e463](https://linux-hardware.org/?probe=5668d7e463) | Jan 10, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [f14ba2d184](https://linux-hardware.org/?probe=f14ba2d184) | Jan 10, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [63db2e4ecc](https://linux-hardware.org/?probe=63db2e4ecc) | Jan 10, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [3b3b0c2855](https://linux-hardware.org/?probe=3b3b0c2855) | Jan 10, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [132d4e0b47](https://linux-hardware.org/?probe=132d4e0b47) | Jan 10, 2022 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | Notebook    | [b6b9155c53](https://linux-hardware.org/?probe=b6b9155c53) | Jan 10, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [62bf8bc805](https://linux-hardware.org/?probe=62bf8bc805) | Jan 10, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [5d7aaea168](https://linux-hardware.org/?probe=5d7aaea168) | Jan 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [72db511d09](https://linux-hardware.org/?probe=72db511d09) | Jan 10, 2022 |
| ASUSTek       | H81-GAMER                   | Desktop     | [e123597c40](https://linux-hardware.org/?probe=e123597c40) | Jan 09, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2fa4c0880f](https://linux-hardware.org/?probe=2fa4c0880f) | Jan 09, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [02fe041d02](https://linux-hardware.org/?probe=02fe041d02) | Jan 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [6b6c84515a](https://linux-hardware.org/?probe=6b6c84515a) | Jan 09, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | Notebook    | [b9812a839e](https://linux-hardware.org/?probe=b9812a839e) | Jan 09, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [8d51630dcf](https://linux-hardware.org/?probe=8d51630dcf) | Jan 09, 2022 |
| ONN           | 100002435                   | Tablet      | [aa4e678faa](https://linux-hardware.org/?probe=aa4e678faa) | Jan 08, 2022 |
| Toshiba       | Satellite C55-A-1NU         | Notebook    | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [dc436bb38c](https://linux-hardware.org/?probe=dc436bb38c) | Jan 08, 2022 |
| Lenovo        | 369A SDK0F82993 WIN         | Desktop     | [e1141045bf](https://linux-hardware.org/?probe=e1141045bf) | Jan 08, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [e0dfa537f4](https://linux-hardware.org/?probe=e0dfa537f4) | Jan 08, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [fc3f2a485a](https://linux-hardware.org/?probe=fc3f2a485a) | Jan 08, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [fa29ca9b4b](https://linux-hardware.org/?probe=fa29ca9b4b) | Jan 08, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [2564a1e4de](https://linux-hardware.org/?probe=2564a1e4de) | Jan 08, 2022 |
| ASUSTek       | Maximus IX CODE             | Desktop     | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| Notebook      | P15SM                       | Notebook    | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| ONN           | 100002435                   | Tablet      | [3587fa7a04](https://linux-hardware.org/?probe=3587fa7a04) | Jan 08, 2022 |
| Dell          | Precision 3551              | Notebook    | [73d2d759ba](https://linux-hardware.org/?probe=73d2d759ba) | Jan 07, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [aa1ce4d9ca](https://linux-hardware.org/?probe=aa1ce4d9ca) | Jan 07, 2022 |
| Dell          | Precision 5510              | Notebook    | [7a763a42bb](https://linux-hardware.org/?probe=7a763a42bb) | Jan 07, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [df6cc34c45](https://linux-hardware.org/?probe=df6cc34c45) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [faa71fac97](https://linux-hardware.org/?probe=faa71fac97) | Jan 06, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [3b6e3858d5](https://linux-hardware.org/?probe=3b6e3858d5) | Jan 06, 2022 |
| ASUSTek       | Z77-A                       | Desktop     | [627b0162be](https://linux-hardware.org/?probe=627b0162be) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [a37ac164fb](https://linux-hardware.org/?probe=a37ac164fb) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [51930e8d89](https://linux-hardware.org/?probe=51930e8d89) | Jan 06, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [6c5e2e7851](https://linux-hardware.org/?probe=6c5e2e7851) | Jan 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [cafe68988e](https://linux-hardware.org/?probe=cafe68988e) | Jan 06, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [47bf32530f](https://linux-hardware.org/?probe=47bf32530f) | Jan 06, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [8d8227634a](https://linux-hardware.org/?probe=8d8227634a) | Jan 06, 2022 |
| Panasonic     | CF-195FYCALM                | Notebook    | [19ad0002e5](https://linux-hardware.org/?probe=19ad0002e5) | Jan 06, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [9ebb75d7a4](https://linux-hardware.org/?probe=9ebb75d7a4) | Jan 06, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [9a5e27cab0](https://linux-hardware.org/?probe=9a5e27cab0) | Jan 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| Samsung       | 550XDA                      | Notebook    | [1bdf544285](https://linux-hardware.org/?probe=1bdf544285) | Jan 05, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | Notebook    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Dell          | Latitude E6520              | Notebook    | [f9c32b0bee](https://linux-hardware.org/?probe=f9c32b0bee) | Jan 05, 2022 |
| Dell          | Latitude E7440              | Notebook    | [c8811522dd](https://linux-hardware.org/?probe=c8811522dd) | Jan 05, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | Desktop     | [b56f576ff8](https://linux-hardware.org/?probe=b56f576ff8) | Jan 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | Notebook    | [270443c029](https://linux-hardware.org/?probe=270443c029) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | Notebook    | [b97121f86e](https://linux-hardware.org/?probe=b97121f86e) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | Notebook    | [9fa953475a](https://linux-hardware.org/?probe=9fa953475a) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4be68e5286](https://linux-hardware.org/?probe=4be68e5286) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [8d492fa1d4](https://linux-hardware.org/?probe=8d492fa1d4) | Jan 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [56a85d54e4](https://linux-hardware.org/?probe=56a85d54e4) | Jan 04, 2022 |
| Dell          | Latitude E5550              | Notebook    | [8956b15ec8](https://linux-hardware.org/?probe=8956b15ec8) | Jan 04, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [3d15bf4d48](https://linux-hardware.org/?probe=3d15bf4d48) | Jan 04, 2022 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [a5ce28f08f](https://linux-hardware.org/?probe=a5ce28f08f) | Jan 04, 2022 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [2befa53304](https://linux-hardware.org/?probe=2befa53304) | Jan 04, 2022 |
| Acer          | Extensa 2540                | Notebook    | [c3587d4c57](https://linux-hardware.org/?probe=c3587d4c57) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [9ac42b2131](https://linux-hardware.org/?probe=9ac42b2131) | Jan 04, 2022 |
| Acer          | Extensa 2540                | Notebook    | [0a39d6fe8c](https://linux-hardware.org/?probe=0a39d6fe8c) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [e8bc9392ff](https://linux-hardware.org/?probe=e8bc9392ff) | Jan 04, 2022 |
| Dell          | Latitude 3470               | Notebook    | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| Dell          | Inspiron 7591               | Notebook    | [4044cf11d2](https://linux-hardware.org/?probe=4044cf11d2) | Jan 04, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [3cae008c9d](https://linux-hardware.org/?probe=3cae008c9d) | Jan 04, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [d5e7352413](https://linux-hardware.org/?probe=d5e7352413) | Jan 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [75db843d7d](https://linux-hardware.org/?probe=75db843d7d) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| HP            | 1495                        | Desktop     | [6298747a55](https://linux-hardware.org/?probe=6298747a55) | Jan 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [8cd52a2f8f](https://linux-hardware.org/?probe=8cd52a2f8f) | Jan 03, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [3953d7ae46](https://linux-hardware.org/?probe=3953d7ae46) | Jan 03, 2022 |
| Intel         | NUC6i7KYB H90766-410        | Mini pc     | [dc32208597](https://linux-hardware.org/?probe=dc32208597) | Jan 03, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [b661a2cdf0](https://linux-hardware.org/?probe=b661a2cdf0) | Jan 03, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [282277fa58](https://linux-hardware.org/?probe=282277fa58) | Jan 02, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [abff969a99](https://linux-hardware.org/?probe=abff969a99) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [b4049969e7](https://linux-hardware.org/?probe=b4049969e7) | Jan 02, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [c5e569b5c7](https://linux-hardware.org/?probe=c5e569b5c7) | Jan 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [60514a96e4](https://linux-hardware.org/?probe=60514a96e4) | Jan 02, 2022 |
| ASRock        | B360M IB-R1                 | Desktop     | [f300f71e62](https://linux-hardware.org/?probe=f300f71e62) | Jan 02, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a1e4b315dc](https://linux-hardware.org/?probe=a1e4b315dc) | Jan 02, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [0692c6e121](https://linux-hardware.org/?probe=0692c6e121) | Jan 02, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [9c2f65c964](https://linux-hardware.org/?probe=9c2f65c964) | Jan 01, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [4fce685dae](https://linux-hardware.org/?probe=4fce685dae) | Jan 01, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [4ce7ea3bb0](https://linux-hardware.org/?probe=4ce7ea3bb0) | Dec 31, 2021 |
| Dell          | Latitude E5570              | Notebook    | [34af93663b](https://linux-hardware.org/?probe=34af93663b) | Dec 31, 2021 |
| Intel         | SKYBAY                      | Desktop     | [043f80cded](https://linux-hardware.org/?probe=043f80cded) | Dec 31, 2021 |
| Google        | Coral                       | Notebook    | [23a0352176](https://linux-hardware.org/?probe=23a0352176) | Dec 31, 2021 |
| ASUSTek       | TP300LD                     | Notebook    | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [6a91ead443](https://linux-hardware.org/?probe=6a91ead443) | Dec 31, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [ec26febbae](https://linux-hardware.org/?probe=ec26febbae) | Dec 31, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [cd66e486be](https://linux-hardware.org/?probe=cd66e486be) | Dec 31, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [298d5a0323](https://linux-hardware.org/?probe=298d5a0323) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [58cb628601](https://linux-hardware.org/?probe=58cb628601) | Dec 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | Notebook    | [c6dbec8e70](https://linux-hardware.org/?probe=c6dbec8e70) | Dec 31, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [c1eeaec01b](https://linux-hardware.org/?probe=c1eeaec01b) | Dec 30, 2021 |
| Google        | Chell                       | Notebook    | [9a2a4a03ed](https://linux-hardware.org/?probe=9a2a4a03ed) | Dec 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [bfd79da0e0](https://linux-hardware.org/?probe=bfd79da0e0) | Dec 30, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [75eea6ae2f](https://linux-hardware.org/?probe=75eea6ae2f) | Dec 30, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [00f3b181b3](https://linux-hardware.org/?probe=00f3b181b3) | Dec 30, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [c3497fe5bd](https://linux-hardware.org/?probe=c3497fe5bd) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| MSI           | X370 GAMING PLUS            | Desktop     | [49f7093e8c](https://linux-hardware.org/?probe=49f7093e8c) | Dec 29, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [c539559392](https://linux-hardware.org/?probe=c539559392) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | Notebook    | [9ba0058839](https://linux-hardware.org/?probe=9ba0058839) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | Notebook    | [dbcf70aced](https://linux-hardware.org/?probe=dbcf70aced) | Dec 29, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [47edce55a4](https://linux-hardware.org/?probe=47edce55a4) | Dec 29, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [5cbf982807](https://linux-hardware.org/?probe=5cbf982807) | Dec 29, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [e3297eb51f](https://linux-hardware.org/?probe=e3297eb51f) | Dec 29, 2021 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [cbf9ee4a86](https://linux-hardware.org/?probe=cbf9ee4a86) | Dec 28, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [41b463b6c4](https://linux-hardware.org/?probe=41b463b6c4) | Dec 28, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [433a512192](https://linux-hardware.org/?probe=433a512192) | Dec 28, 2021 |
| Lenovo        | ThinkPad E480 20KN001QPB    | Notebook    | [0615d7a112](https://linux-hardware.org/?probe=0615d7a112) | Dec 28, 2021 |
| MSI           | H81M-E33                    | Desktop     | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | Notebook    | [bea75ed7d5](https://linux-hardware.org/?probe=bea75ed7d5) | Dec 27, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [cc15a65a54](https://linux-hardware.org/?probe=cc15a65a54) | Dec 27, 2021 |
| Toshiba       | Satellite L12-C-104         | Notebook    | [fae8f8e1f9](https://linux-hardware.org/?probe=fae8f8e1f9) | Dec 27, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [23460afe38](https://linux-hardware.org/?probe=23460afe38) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [707835b4ff](https://linux-hardware.org/?probe=707835b4ff) | Dec 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [f255947b6f](https://linux-hardware.org/?probe=f255947b6f) | Dec 27, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [572bbe8d7b](https://linux-hardware.org/?probe=572bbe8d7b) | Dec 27, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [86651ee07a](https://linux-hardware.org/?probe=86651ee07a) | Dec 26, 2021 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [61dd257cc7](https://linux-hardware.org/?probe=61dd257cc7) | Dec 26, 2021 |
| XFX           | nForce 780i 3-Way SLI 1     | Desktop     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [56c0a83ab8](https://linux-hardware.org/?probe=56c0a83ab8) | Dec 26, 2021 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [e076af5bf8](https://linux-hardware.org/?probe=e076af5bf8) | Dec 26, 2021 |
| HP            | 2000                        | Notebook    | [e3408eb743](https://linux-hardware.org/?probe=e3408eb743) | Dec 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1e8ce2ec6d](https://linux-hardware.org/?probe=1e8ce2ec6d) | Dec 25, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [58e49e7f72](https://linux-hardware.org/?probe=58e49e7f72) | Dec 25, 2021 |
| Dell          | Latitude 7410               | Notebook    | [71a96bfc8f](https://linux-hardware.org/?probe=71a96bfc8f) | Dec 25, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [6fe369b6b7](https://linux-hardware.org/?probe=6fe369b6b7) | Dec 25, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [3a08145f4b](https://linux-hardware.org/?probe=3a08145f4b) | Dec 24, 2021 |
| Cube          | i18-L                       | Notebook    | [6770cf2a44](https://linux-hardware.org/?probe=6770cf2a44) | Dec 24, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ca0f62a716](https://linux-hardware.org/?probe=ca0f62a716) | Dec 24, 2021 |
| Lenovo        | V470 439627U                | Notebook    | [7c44d560dc](https://linux-hardware.org/?probe=7c44d560dc) | Dec 24, 2021 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [f1e535b5ba](https://linux-hardware.org/?probe=f1e535b5ba) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [a02655b4b8](https://linux-hardware.org/?probe=a02655b4b8) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [6e08796257](https://linux-hardware.org/?probe=6e08796257) | Dec 24, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [44dd4eee41](https://linux-hardware.org/?probe=44dd4eee41) | Dec 24, 2021 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| Lenovo        | CRESCENTBAY 31900058 WIN... | All in one  | [91ee24853b](https://linux-hardware.org/?probe=91ee24853b) | Dec 23, 2021 |
| LDLC          | Mercure MH                  | Notebook    | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS2B000    | Notebook    | [abba53c091](https://linux-hardware.org/?probe=abba53c091) | Dec 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [1962ddfdb4](https://linux-hardware.org/?probe=1962ddfdb4) | Dec 23, 2021 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [6efc5bede0](https://linux-hardware.org/?probe=6efc5bede0) | Dec 23, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [4cd052492e](https://linux-hardware.org/?probe=4cd052492e) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| HP            | 250 G1                      | Notebook    | [da8e31b740](https://linux-hardware.org/?probe=da8e31b740) | Dec 23, 2021 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [27379a7599](https://linux-hardware.org/?probe=27379a7599) | Dec 22, 2021 |
| Dell          | Inspiron 5447               | Notebook    | [83331a9c7c](https://linux-hardware.org/?probe=83331a9c7c) | Dec 22, 2021 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [51a7e08e9a](https://linux-hardware.org/?probe=51a7e08e9a) | Dec 22, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [18ea7c2e7e](https://linux-hardware.org/?probe=18ea7c2e7e) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [9b2acc6ea1](https://linux-hardware.org/?probe=9b2acc6ea1) | Dec 22, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [1975ee2fc0](https://linux-hardware.org/?probe=1975ee2fc0) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [5994dbd498](https://linux-hardware.org/?probe=5994dbd498) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [0408aca941](https://linux-hardware.org/?probe=0408aca941) | Dec 21, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [5f27936a88](https://linux-hardware.org/?probe=5f27936a88) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dd197ecb62](https://linux-hardware.org/?probe=dd197ecb62) | Dec 21, 2021 |
| ASUSTek       | P5G41-M                     | Desktop     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7fc27f5255](https://linux-hardware.org/?probe=7fc27f5255) | Dec 21, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [5f47284626](https://linux-hardware.org/?probe=5f47284626) | Dec 21, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [03abaff4ae](https://linux-hardware.org/?probe=03abaff4ae) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [42d4ee98ce](https://linux-hardware.org/?probe=42d4ee98ce) | Dec 21, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e0f736fe3b](https://linux-hardware.org/?probe=e0f736fe3b) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8cd9d762c9](https://linux-hardware.org/?probe=8cd9d762c9) | Dec 20, 2021 |
| Dell          | 0YJPT1 A00                  | Desktop     | [a92e152a7c](https://linux-hardware.org/?probe=a92e152a7c) | Dec 20, 2021 |
| HP            | Pavilion 15                 | Notebook    | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [16e27617b9](https://linux-hardware.org/?probe=16e27617b9) | Dec 20, 2021 |
| Notebook      | N24_25JU                    | Notebook    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [d05d2fe462](https://linux-hardware.org/?probe=d05d2fe462) | Dec 20, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [9c1cf57d74](https://linux-hardware.org/?probe=9c1cf57d74) | Dec 20, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [58f36b9637](https://linux-hardware.org/?probe=58f36b9637) | Dec 20, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [ddb3571ec6](https://linux-hardware.org/?probe=ddb3571ec6) | Dec 20, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI           | X370 SLI PLUS               | Desktop     | [adb27f9347](https://linux-hardware.org/?probe=adb27f9347) | Dec 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [bb28c266ec](https://linux-hardware.org/?probe=bb28c266ec) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d335e16395](https://linux-hardware.org/?probe=d335e16395) | Dec 19, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [e2ce1d7284](https://linux-hardware.org/?probe=e2ce1d7284) | Dec 19, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [9c38b95aa0](https://linux-hardware.org/?probe=9c38b95aa0) | Dec 19, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [e380536aac](https://linux-hardware.org/?probe=e380536aac) | Dec 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [87399b5e8b](https://linux-hardware.org/?probe=87399b5e8b) | Dec 19, 2021 |
| Intel         | NUC6i7KYB H90766-410        | Mini pc     | [c5f8ba42bd](https://linux-hardware.org/?probe=c5f8ba42bd) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [85e3feaeba](https://linux-hardware.org/?probe=85e3feaeba) | Dec 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [25c7dd18f2](https://linux-hardware.org/?probe=25c7dd18f2) | Dec 19, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6653477f61](https://linux-hardware.org/?probe=6653477f61) | Dec 18, 2021 |
| JINGSHA       | Unknown                     | Desktop     | [13da82798c](https://linux-hardware.org/?probe=13da82798c) | Dec 18, 2021 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [2497b24eda](https://linux-hardware.org/?probe=2497b24eda) | Dec 18, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | Notebook    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| Acer          | Nitro AN515-53              | Notebook    | [a9affc8e28](https://linux-hardware.org/?probe=a9affc8e28) | Dec 18, 2021 |
| Dell          | Precision 5540              | Notebook    | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| Gigabyte      | F2A88XM-DS2P                | Desktop     | [c18ddabc8d](https://linux-hardware.org/?probe=c18ddabc8d) | Dec 18, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [305153f0a8](https://linux-hardware.org/?probe=305153f0a8) | Dec 17, 2021 |
| ASUSTek       | P5G41-M                     | Desktop     | [c073d4a4e9](https://linux-hardware.org/?probe=c073d4a4e9) | Dec 17, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [cda7a2c35c](https://linux-hardware.org/?probe=cda7a2c35c) | Dec 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [6bf6c57117](https://linux-hardware.org/?probe=6bf6c57117) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [e985e04d6d](https://linux-hardware.org/?probe=e985e04d6d) | Dec 17, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [6deb57beb2](https://linux-hardware.org/?probe=6deb57beb2) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| AVITA         | NS14A1US                    | Notebook    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [290b1d081b](https://linux-hardware.org/?probe=290b1d081b) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [aba6548652](https://linux-hardware.org/?probe=aba6548652) | Dec 16, 2021 |
| HP            | 805D                        | Desktop     | [dfdc70512c](https://linux-hardware.org/?probe=dfdc70512c) | Dec 16, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [30a4a58c5d](https://linux-hardware.org/?probe=30a4a58c5d) | Dec 16, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [4d52a02213](https://linux-hardware.org/?probe=4d52a02213) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [ff779fe08f](https://linux-hardware.org/?probe=ff779fe08f) | Dec 16, 2021 |
| MSI           | GL63 9SC                    | Notebook    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| HP            | Pavilion dv7                | Notebook    | [0e0f0e3c23](https://linux-hardware.org/?probe=0e0f0e3c23) | Dec 15, 2021 |
| Dell          | Latitude 5500               | Notebook    | [5b9479065e](https://linux-hardware.org/?probe=5b9479065e) | Dec 15, 2021 |
| Lenovo        | ThinkPad E14 20RA007TUE     | Notebook    | [3edd54970c](https://linux-hardware.org/?probe=3edd54970c) | Dec 15, 2021 |
| ASUSTek       | K43U                        | Notebook    | [d7df2cd94e](https://linux-hardware.org/?probe=d7df2cd94e) | Dec 15, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [45a411c9fe](https://linux-hardware.org/?probe=45a411c9fe) | Dec 15, 2021 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [60a7206b05](https://linux-hardware.org/?probe=60a7206b05) | Dec 15, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [2cabe8184b](https://linux-hardware.org/?probe=2cabe8184b) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [660ce7fc74](https://linux-hardware.org/?probe=660ce7fc74) | Dec 15, 2021 |
| Dell          | 0RY007                      | Desktop     | [f3cb490147](https://linux-hardware.org/?probe=f3cb490147) | Dec 14, 2021 |
| Lenovo        | 3111 NOK                    | Mini pc     | [b599c84248](https://linux-hardware.org/?probe=b599c84248) | Dec 14, 2021 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [b2dc7c9e05](https://linux-hardware.org/?probe=b2dc7c9e05) | Dec 14, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4290797f32](https://linux-hardware.org/?probe=4290797f32) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [fb79be9e00](https://linux-hardware.org/?probe=fb79be9e00) | Dec 14, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [1ffa9927c7](https://linux-hardware.org/?probe=1ffa9927c7) | Dec 14, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [a1c2190f8d](https://linux-hardware.org/?probe=a1c2190f8d) | Dec 14, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [dd29feeb10](https://linux-hardware.org/?probe=dd29feeb10) | Dec 14, 2021 |
| Dell          | Latitude 7300               | Notebook    | [23f38f8a7d](https://linux-hardware.org/?probe=23f38f8a7d) | Dec 14, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [8d121836c9](https://linux-hardware.org/?probe=8d121836c9) | Dec 14, 2021 |
| HP            | 2B2B                        | Desktop     | [bf929a4359](https://linux-hardware.org/?probe=bf929a4359) | Dec 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [ae8a45bc5a](https://linux-hardware.org/?probe=ae8a45bc5a) | Dec 14, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [53523a4ea7](https://linux-hardware.org/?probe=53523a4ea7) | Dec 14, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [fd53be96e6](https://linux-hardware.org/?probe=fd53be96e6) | Dec 13, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [2074bdb7a5](https://linux-hardware.org/?probe=2074bdb7a5) | Dec 13, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [3030fcf474](https://linux-hardware.org/?probe=3030fcf474) | Dec 13, 2021 |
| Avell High... | A70 LIV                     | Notebook    | [3930fc87b1](https://linux-hardware.org/?probe=3930fc87b1) | Dec 12, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [27bbd905bf](https://linux-hardware.org/?probe=27bbd905bf) | Dec 12, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [24c8e29d95](https://linux-hardware.org/?probe=24c8e29d95) | Dec 12, 2021 |
| Dell          | Latitude 7290               | Notebook    | [8a2ecfe430](https://linux-hardware.org/?probe=8a2ecfe430) | Dec 12, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [5975d86599](https://linux-hardware.org/?probe=5975d86599) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [169e6793c2](https://linux-hardware.org/?probe=169e6793c2) | Dec 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [021525201e](https://linux-hardware.org/?probe=021525201e) | Dec 12, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bd4a0c5d2f](https://linux-hardware.org/?probe=bd4a0c5d2f) | Dec 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1H60... | Notebook    | [ffb1c97626](https://linux-hardware.org/?probe=ffb1c97626) | Dec 12, 2021 |
| ASUSTek       | P6T                         | Desktop     | [b789a1151e](https://linux-hardware.org/?probe=b789a1151e) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [54058ac7e2](https://linux-hardware.org/?probe=54058ac7e2) | Dec 11, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [6d5c35bf9f](https://linux-hardware.org/?probe=6d5c35bf9f) | Dec 11, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [584be17bec](https://linux-hardware.org/?probe=584be17bec) | Dec 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4fba952635](https://linux-hardware.org/?probe=4fba952635) | Dec 11, 2021 |
| HP            | ZBook 15 G2                 | Notebook    | [d7faa88624](https://linux-hardware.org/?probe=d7faa88624) | Dec 11, 2021 |
| Dell          | Latitude 7300               | Notebook    | [2bb3c232b6](https://linux-hardware.org/?probe=2bb3c232b6) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f3d37d4574](https://linux-hardware.org/?probe=f3d37d4574) | Dec 10, 2021 |
| Dell          | Inspiron 13 5310            | Notebook    | [7a721d2c05](https://linux-hardware.org/?probe=7a721d2c05) | Dec 10, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [8ae1043ce6](https://linux-hardware.org/?probe=8ae1043ce6) | Dec 10, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [bcb885e52b](https://linux-hardware.org/?probe=bcb885e52b) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [4fe4d7393e](https://linux-hardware.org/?probe=4fe4d7393e) | Dec 10, 2021 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [b76ef07c59](https://linux-hardware.org/?probe=b76ef07c59) | Dec 10, 2021 |
| Acer          | Swift SFX14-41G             | Notebook    | [a81ed5c974](https://linux-hardware.org/?probe=a81ed5c974) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [4ba265c070](https://linux-hardware.org/?probe=4ba265c070) | Dec 10, 2021 |
| ASUSTek       | P6T                         | Desktop     | [71ce922273](https://linux-hardware.org/?probe=71ce922273) | Dec 09, 2021 |
| Lenovo        | G570 20079                  | Notebook    | [439a97ec9b](https://linux-hardware.org/?probe=439a97ec9b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [195283a93a](https://linux-hardware.org/?probe=195283a93a) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [bf533d0378](https://linux-hardware.org/?probe=bf533d0378) | Dec 09, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [60e57ae6dd](https://linux-hardware.org/?probe=60e57ae6dd) | Dec 09, 2021 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [d0070c39c4](https://linux-hardware.org/?probe=d0070c39c4) | Dec 09, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [c486c9645b](https://linux-hardware.org/?probe=c486c9645b) | Dec 09, 2021 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1881f48bd1](https://linux-hardware.org/?probe=1881f48bd1) | Dec 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [73645a62d6](https://linux-hardware.org/?probe=73645a62d6) | Dec 09, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [b8e92a4957](https://linux-hardware.org/?probe=b8e92a4957) | Dec 09, 2021 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [f7ca8d84ca](https://linux-hardware.org/?probe=f7ca8d84ca) | Dec 08, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b673a5f067](https://linux-hardware.org/?probe=b673a5f067) | Dec 08, 2021 |
| ASUSTek       | P6T                         | Desktop     | [d04f9d16a8](https://linux-hardware.org/?probe=d04f9d16a8) | Dec 08, 2021 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [80630ad3ed](https://linux-hardware.org/?probe=80630ad3ed) | Dec 08, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [3880c485fb](https://linux-hardware.org/?probe=3880c485fb) | Dec 08, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [fcfdb2cedc](https://linux-hardware.org/?probe=fcfdb2cedc) | Dec 08, 2021 |
| Unknown       | Unknown Product             | Soc         | [a85a563642](https://linux-hardware.org/?probe=a85a563642) | Dec 08, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [82926e68a4](https://linux-hardware.org/?probe=82926e68a4) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [78b37822bc](https://linux-hardware.org/?probe=78b37822bc) | Dec 08, 2021 |
| Sony          | SVE1711Z1RB                 | Notebook    | [adb25167ea](https://linux-hardware.org/?probe=adb25167ea) | Dec 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [9c98446833](https://linux-hardware.org/?probe=9c98446833) | Dec 07, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [809152313d](https://linux-hardware.org/?probe=809152313d) | Dec 07, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [58c6a86730](https://linux-hardware.org/?probe=58c6a86730) | Dec 07, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [ad406a6f63](https://linux-hardware.org/?probe=ad406a6f63) | Dec 07, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [775bafdec8](https://linux-hardware.org/?probe=775bafdec8) | Dec 07, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [0523a58e8a](https://linux-hardware.org/?probe=0523a58e8a) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | Notebook    | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Lenovo        | G570 20079                  | Notebook    | [a6722f2ff3](https://linux-hardware.org/?probe=a6722f2ff3) | Dec 07, 2021 |
| Sony          | SVE1713S1RW                 | Notebook    | [41775b7503](https://linux-hardware.org/?probe=41775b7503) | Dec 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8b704c0d3f](https://linux-hardware.org/?probe=8b704c0d3f) | Dec 06, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [b5a282abf6](https://linux-hardware.org/?probe=b5a282abf6) | Dec 06, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | Desktop     | [5393b5ad7a](https://linux-hardware.org/?probe=5393b5ad7a) | Dec 06, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [4fc7bc5515](https://linux-hardware.org/?probe=4fc7bc5515) | Dec 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [42fe75c227](https://linux-hardware.org/?probe=42fe75c227) | Dec 06, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [9e878d83a3](https://linux-hardware.org/?probe=9e878d83a3) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [0a06cba7c5](https://linux-hardware.org/?probe=0a06cba7c5) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e18de7567f](https://linux-hardware.org/?probe=e18de7567f) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | Desktop     | [82cd98ea5a](https://linux-hardware.org/?probe=82cd98ea5a) | Dec 06, 2021 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | Desktop     | [07f484651e](https://linux-hardware.org/?probe=07f484651e) | Dec 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [05538278b6](https://linux-hardware.org/?probe=05538278b6) | Dec 06, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0550... | Notebook    | [40640fd92f](https://linux-hardware.org/?probe=40640fd92f) | Dec 06, 2021 |
| Framework     | Laptop                      | Notebook    | [64dc54fbc6](https://linux-hardware.org/?probe=64dc54fbc6) | Dec 06, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [9e6cd42a9f](https://linux-hardware.org/?probe=9e6cd42a9f) | Dec 05, 2021 |
| Dell          | Inspiron 7586               | Convertible | [53604c12d1](https://linux-hardware.org/?probe=53604c12d1) | Dec 05, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [8641f9b078](https://linux-hardware.org/?probe=8641f9b078) | Dec 05, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [18ae64d44d](https://linux-hardware.org/?probe=18ae64d44d) | Dec 05, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | Notebook    | [50d1714228](https://linux-hardware.org/?probe=50d1714228) | Dec 05, 2021 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [b296e2a320](https://linux-hardware.org/?probe=b296e2a320) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Dell          | Inspiron 5405               | Notebook    | [91806303e6](https://linux-hardware.org/?probe=91806303e6) | Dec 05, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [f254ee88c6](https://linux-hardware.org/?probe=f254ee88c6) | Dec 05, 2021 |
| Dell          | Latitude E6530              | Notebook    | [de5ad42b2f](https://linux-hardware.org/?probe=de5ad42b2f) | Dec 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [15e8e28073](https://linux-hardware.org/?probe=15e8e28073) | Dec 04, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [b006a547c8](https://linux-hardware.org/?probe=b006a547c8) | Dec 04, 2021 |
| MSI           | Z87M GAMING                 | Desktop     | [4ef67e0560](https://linux-hardware.org/?probe=4ef67e0560) | Dec 04, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [e7d4963834](https://linux-hardware.org/?probe=e7d4963834) | Dec 04, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [1cfd3aadd8](https://linux-hardware.org/?probe=1cfd3aadd8) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [be3c6c3e84](https://linux-hardware.org/?probe=be3c6c3e84) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | Notebook    | [23d42021b2](https://linux-hardware.org/?probe=23d42021b2) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [6239b4eda5](https://linux-hardware.org/?probe=6239b4eda5) | Dec 04, 2021 |
| XFX           | MI-A78S-8209 Ver1.1         | Desktop     | [ce556a2535](https://linux-hardware.org/?probe=ce556a2535) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [511a349d7f](https://linux-hardware.org/?probe=511a349d7f) | Dec 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [f90f047538](https://linux-hardware.org/?probe=f90f047538) | Dec 03, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [fd20b7fc56](https://linux-hardware.org/?probe=fd20b7fc56) | Dec 03, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [8c6244cb77](https://linux-hardware.org/?probe=8c6244cb77) | Dec 03, 2021 |
| Toshiba       | Satellite C70-A-K2W         | Notebook    | [8e46f67032](https://linux-hardware.org/?probe=8e46f67032) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | Notebook    | [775ec45ab8](https://linux-hardware.org/?probe=775ec45ab8) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | Notebook    | [b783f0a79d](https://linux-hardware.org/?probe=b783f0a79d) | Dec 03, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [a7d3041cd2](https://linux-hardware.org/?probe=a7d3041cd2) | Dec 03, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f53047cd0d](https://linux-hardware.org/?probe=f53047cd0d) | Dec 02, 2021 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [ca1727f54a](https://linux-hardware.org/?probe=ca1727f54a) | Dec 02, 2021 |
| Gateway       | SX2185                      | Desktop     | [70e907b207](https://linux-hardware.org/?probe=70e907b207) | Dec 02, 2021 |
| HP            | EliteBook x360 830 G5       | Convertible | [33ef9926a3](https://linux-hardware.org/?probe=33ef9926a3) | Dec 02, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [b108ae97c2](https://linux-hardware.org/?probe=b108ae97c2) | Dec 02, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [4189e1f255](https://linux-hardware.org/?probe=4189e1f255) | Dec 02, 2021 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [ffecd77f3a](https://linux-hardware.org/?probe=ffecd77f3a) | Dec 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [142cab14c6](https://linux-hardware.org/?probe=142cab14c6) | Dec 02, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [508352ad4a](https://linux-hardware.org/?probe=508352ad4a) | Dec 02, 2021 |
| Lenovo        | ThinkPad L390 20NSS43600    | Notebook    | [e9aae12812](https://linux-hardware.org/?probe=e9aae12812) | Dec 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0b2751c5c1](https://linux-hardware.org/?probe=0b2751c5c1) | Dec 02, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [d5c6c6edee](https://linux-hardware.org/?probe=d5c6c6edee) | Dec 01, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [94b9d8b093](https://linux-hardware.org/?probe=94b9d8b093) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [240ca54dfb](https://linux-hardware.org/?probe=240ca54dfb) | Dec 01, 2021 |
| HP            | 2B2E A01                    | All in one  | [6f6101b39b](https://linux-hardware.org/?probe=6f6101b39b) | Dec 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8cebf41624](https://linux-hardware.org/?probe=8cebf41624) | Dec 01, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9b11575394](https://linux-hardware.org/?probe=9b11575394) | Dec 01, 2021 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [24800d20ac](https://linux-hardware.org/?probe=24800d20ac) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [610709bb66](https://linux-hardware.org/?probe=610709bb66) | Nov 30, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [f940ae414d](https://linux-hardware.org/?probe=f940ae414d) | Nov 30, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [0a6feb58e7](https://linux-hardware.org/?probe=0a6feb58e7) | Nov 30, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [1b4de261b3](https://linux-hardware.org/?probe=1b4de261b3) | Nov 30, 2021 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [7ad53e55ba](https://linux-hardware.org/?probe=7ad53e55ba) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [b2d55bd445](https://linux-hardware.org/?probe=b2d55bd445) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [23ae32af07](https://linux-hardware.org/?probe=23ae32af07) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [074ec973ae](https://linux-hardware.org/?probe=074ec973ae) | Nov 30, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [2ceb61c052](https://linux-hardware.org/?probe=2ceb61c052) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [80bbba47f6](https://linux-hardware.org/?probe=80bbba47f6) | Nov 29, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [95cb3fe8b3](https://linux-hardware.org/?probe=95cb3fe8b3) | Nov 29, 2021 |
| Acer          | Predator G9-793             | Notebook    | [b9dc27ddac](https://linux-hardware.org/?probe=b9dc27ddac) | Nov 29, 2021 |
| Dell          | G5 5590                     | Notebook    | [e569e56450](https://linux-hardware.org/?probe=e569e56450) | Nov 29, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [959af2b8dd](https://linux-hardware.org/?probe=959af2b8dd) | Nov 29, 2021 |
| Acer          | Swift SF113-31              | Notebook    | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [a91b7dd31b](https://linux-hardware.org/?probe=a91b7dd31b) | Nov 29, 2021 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [8ece12c9e6](https://linux-hardware.org/?probe=8ece12c9e6) | Nov 28, 2021 |
| Notebook      | NB50TL                      | Notebook    | [15a716161c](https://linux-hardware.org/?probe=15a716161c) | Nov 28, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [b75e21b247](https://linux-hardware.org/?probe=b75e21b247) | Nov 28, 2021 |
| ECS           | H61H2-CM                    | Desktop     | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [b003366a2c](https://linux-hardware.org/?probe=b003366a2c) | Nov 28, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [8e5c4cc27b](https://linux-hardware.org/?probe=8e5c4cc27b) | Nov 28, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [6a4ed949e9](https://linux-hardware.org/?probe=6a4ed949e9) | Nov 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [0852350348](https://linux-hardware.org/?probe=0852350348) | Nov 28, 2021 |
| Dell          | Latitude 7420               | Notebook    | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [e83680db56](https://linux-hardware.org/?probe=e83680db56) | Nov 28, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [eabdd46893](https://linux-hardware.org/?probe=eabdd46893) | Nov 28, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d813ffb878](https://linux-hardware.org/?probe=d813ffb878) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [d559f82ee3](https://linux-hardware.org/?probe=d559f82ee3) | Nov 28, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [783b49e383](https://linux-hardware.org/?probe=783b49e383) | Nov 28, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [5d5d624d8c](https://linux-hardware.org/?probe=5d5d624d8c) | Nov 27, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | Notebook    | [67f32be00d](https://linux-hardware.org/?probe=67f32be00d) | Nov 27, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [d949cb9963](https://linux-hardware.org/?probe=d949cb9963) | Nov 27, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [d980b32136](https://linux-hardware.org/?probe=d980b32136) | Nov 27, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [968f938b4e](https://linux-hardware.org/?probe=968f938b4e) | Nov 27, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [c23e7e890b](https://linux-hardware.org/?probe=c23e7e890b) | Nov 27, 2021 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [1e4799819e](https://linux-hardware.org/?probe=1e4799819e) | Nov 26, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | Notebook    | [ef8336f76a](https://linux-hardware.org/?probe=ef8336f76a) | Nov 26, 2021 |
| Dell          | Precision 5550              | Notebook    | [41caa6a4a0](https://linux-hardware.org/?probe=41caa6a4a0) | Nov 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| ASUSTek       | K54C                        | Notebook    | [2604de426e](https://linux-hardware.org/?probe=2604de426e) | Nov 26, 2021 |
| Acer          | AP714-51T                   | Notebook    | [3fe9bcf889](https://linux-hardware.org/?probe=3fe9bcf889) | Nov 26, 2021 |
| Acer          | AP714-51T                   | Notebook    | [406001fc85](https://linux-hardware.org/?probe=406001fc85) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [c207f61d91](https://linux-hardware.org/?probe=c207f61d91) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [96c90ad6c9](https://linux-hardware.org/?probe=96c90ad6c9) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [039dbf659a](https://linux-hardware.org/?probe=039dbf659a) | Nov 26, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [a000027ce6](https://linux-hardware.org/?probe=a000027ce6) | Nov 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [366fe373c9](https://linux-hardware.org/?probe=366fe373c9) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [beff046f56](https://linux-hardware.org/?probe=beff046f56) | Nov 25, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [395718db33](https://linux-hardware.org/?probe=395718db33) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [2a96a2a7af](https://linux-hardware.org/?probe=2a96a2a7af) | Nov 25, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [f4f5c37779](https://linux-hardware.org/?probe=f4f5c37779) | Nov 25, 2021 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [b6ffc90d4e](https://linux-hardware.org/?probe=b6ffc90d4e) | Nov 25, 2021 |
| Sony          | VPCF131FM                   | Notebook    | [f0ba5e0db2](https://linux-hardware.org/?probe=f0ba5e0db2) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | Notebook    | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| HP            | 3561                        | All in one  | [5ff1d7a72e](https://linux-hardware.org/?probe=5ff1d7a72e) | Nov 24, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [a91462bd5a](https://linux-hardware.org/?probe=a91462bd5a) | Nov 24, 2021 |
| HP            | EliteBook 735 G5            | Notebook    | [d80b574cb4](https://linux-hardware.org/?probe=d80b574cb4) | Nov 24, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [b90083da69](https://linux-hardware.org/?probe=b90083da69) | Nov 24, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [e606757d4a](https://linux-hardware.org/?probe=e606757d4a) | Nov 24, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [96fec5d214](https://linux-hardware.org/?probe=96fec5d214) | Nov 24, 2021 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [35801f40df](https://linux-hardware.org/?probe=35801f40df) | Nov 24, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [79ee4911cb](https://linux-hardware.org/?probe=79ee4911cb) | Nov 24, 2021 |
| MSI           | A55M-E33                    | Desktop     | [e6616870b6](https://linux-hardware.org/?probe=e6616870b6) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b6bfa4b827](https://linux-hardware.org/?probe=b6bfa4b827) | Nov 24, 2021 |
| HP            | 1906                        | Desktop     | [8ec5c16fc7](https://linux-hardware.org/?probe=8ec5c16fc7) | Nov 24, 2021 |
| HP            | 83E1                        | Desktop     | [7598ac7e6c](https://linux-hardware.org/?probe=7598ac7e6c) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [44bf6f6d6f](https://linux-hardware.org/?probe=44bf6f6d6f) | Nov 23, 2021 |
| ASUSTek       | Maximus IV GENE-Z           | Desktop     | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | Desktop     | [c50601fb76](https://linux-hardware.org/?probe=c50601fb76) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3c3fbf498a](https://linux-hardware.org/?probe=3c3fbf498a) | Nov 23, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [5be975dd37](https://linux-hardware.org/?probe=5be975dd37) | Nov 23, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [0c3c7c6bb3](https://linux-hardware.org/?probe=0c3c7c6bb3) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | Notebook    | [d29d6c2f61](https://linux-hardware.org/?probe=d29d6c2f61) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | Notebook    | [6e361a8715](https://linux-hardware.org/?probe=6e361a8715) | Nov 23, 2021 |
| HP            | 1906                        | Desktop     | [90499fe34d](https://linux-hardware.org/?probe=90499fe34d) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| Gigabyte      | GA-MA790X-UD4               | Desktop     | [0a19a35ac4](https://linux-hardware.org/?probe=0a19a35ac4) | Nov 22, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b58b567113](https://linux-hardware.org/?probe=b58b567113) | Nov 22, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [7b9225653f](https://linux-hardware.org/?probe=7b9225653f) | Nov 22, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [365b3888e6](https://linux-hardware.org/?probe=365b3888e6) | Nov 22, 2021 |
| Lenovo        | 3746 No DPK                 | All in one  | [44d15ef318](https://linux-hardware.org/?probe=44d15ef318) | Nov 22, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [ece0600e5d](https://linux-hardware.org/?probe=ece0600e5d) | Nov 22, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [c686d7d85c](https://linux-hardware.org/?probe=c686d7d85c) | Nov 22, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [8fc4f44be5](https://linux-hardware.org/?probe=8fc4f44be5) | Nov 22, 2021 |
| Gigabyte      | F2A85XM-D3H                 | Desktop     | [1c41d8c34c](https://linux-hardware.org/?probe=1c41d8c34c) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [a20fe0f647](https://linux-hardware.org/?probe=a20fe0f647) | Nov 21, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | Notebook    | [f779165258](https://linux-hardware.org/?probe=f779165258) | Nov 21, 2021 |
| Dell          | Latitude E5570              | Notebook    | [8cf8db7a89](https://linux-hardware.org/?probe=8cf8db7a89) | Nov 21, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [8cc8502887](https://linux-hardware.org/?probe=8cc8502887) | Nov 21, 2021 |
| Google        | Relm                        | Notebook    | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [683697e6ee](https://linux-hardware.org/?probe=683697e6ee) | Nov 21, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [92375d0ecc](https://linux-hardware.org/?probe=92375d0ecc) | Nov 21, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [2fa52f3236](https://linux-hardware.org/?probe=2fa52f3236) | Nov 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [faec9a8f8b](https://linux-hardware.org/?probe=faec9a8f8b) | Nov 21, 2021 |
| HP            | Pavilion 17                 | Notebook    | [2d69072cdf](https://linux-hardware.org/?probe=2d69072cdf) | Nov 20, 2021 |
| HP            | 3048h                       | Desktop     | [e38eb769b5](https://linux-hardware.org/?probe=e38eb769b5) | Nov 20, 2021 |
| Dell          | Latitude 5490               | Notebook    | [cbe23836bf](https://linux-hardware.org/?probe=cbe23836bf) | Nov 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [44d1a95b0b](https://linux-hardware.org/?probe=44d1a95b0b) | Nov 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [8dfec492a4](https://linux-hardware.org/?probe=8dfec492a4) | Nov 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [78341a1a16](https://linux-hardware.org/?probe=78341a1a16) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [31cebd4e96](https://linux-hardware.org/?probe=31cebd4e96) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [0be43eb710](https://linux-hardware.org/?probe=0be43eb710) | Nov 19, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [3b34362c42](https://linux-hardware.org/?probe=3b34362c42) | Nov 19, 2021 |
| Acer          | Swift SF514-51              | Notebook    | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [8bf7660808](https://linux-hardware.org/?probe=8bf7660808) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [a524ba65b5](https://linux-hardware.org/?probe=a524ba65b5) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7e7b7d381e](https://linux-hardware.org/?probe=7e7b7d381e) | Nov 19, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d0aea280e7](https://linux-hardware.org/?probe=d0aea280e7) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [02b2e4cb00](https://linux-hardware.org/?probe=02b2e4cb00) | Nov 19, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [0e670dc090](https://linux-hardware.org/?probe=0e670dc090) | Nov 19, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [181c56512d](https://linux-hardware.org/?probe=181c56512d) | Nov 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d7a5775f61](https://linux-hardware.org/?probe=d7a5775f61) | Nov 19, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [d111fd1549](https://linux-hardware.org/?probe=d111fd1549) | Nov 19, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [fbedd3af33](https://linux-hardware.org/?probe=fbedd3af33) | Nov 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [01a15306b9](https://linux-hardware.org/?probe=01a15306b9) | Nov 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| ASUSTek       | X750JN                      | Notebook    | [bb6f44b058](https://linux-hardware.org/?probe=bb6f44b058) | Nov 19, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [839b5c24aa](https://linux-hardware.org/?probe=839b5c24aa) | Nov 19, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [12f769ed4c](https://linux-hardware.org/?probe=12f769ed4c) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f5a721bf24](https://linux-hardware.org/?probe=f5a721bf24) | Nov 19, 2021 |
| Dell          | Precision 5510              | Notebook    | [1d46cced08](https://linux-hardware.org/?probe=1d46cced08) | Nov 19, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [70ee93daac](https://linux-hardware.org/?probe=70ee93daac) | Nov 19, 2021 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [f9b7bdfef8](https://linux-hardware.org/?probe=f9b7bdfef8) | Nov 19, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6a1607ab9d](https://linux-hardware.org/?probe=6a1607ab9d) | Nov 18, 2021 |
| Dell          | Inspiron 7572               | Notebook    | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [dc150f9fba](https://linux-hardware.org/?probe=dc150f9fba) | Nov 18, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c8a6893780](https://linux-hardware.org/?probe=c8a6893780) | Nov 18, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [d9f71fda8f](https://linux-hardware.org/?probe=d9f71fda8f) | Nov 18, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [34aff3ab72](https://linux-hardware.org/?probe=34aff3ab72) | Nov 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f35f04cabd](https://linux-hardware.org/?probe=f35f04cabd) | Nov 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [50535d277c](https://linux-hardware.org/?probe=50535d277c) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [3b2165faa8](https://linux-hardware.org/?probe=3b2165faa8) | Nov 18, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [93c3ab9ed1](https://linux-hardware.org/?probe=93c3ab9ed1) | Nov 18, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [46c44d537a](https://linux-hardware.org/?probe=46c44d537a) | Nov 18, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [01f7a4c33d](https://linux-hardware.org/?probe=01f7a4c33d) | Nov 18, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f6dc8337e7](https://linux-hardware.org/?probe=f6dc8337e7) | Nov 18, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [05020e1e61](https://linux-hardware.org/?probe=05020e1e61) | Nov 18, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [5f40fb240a](https://linux-hardware.org/?probe=5f40fb240a) | Nov 17, 2021 |
| Toshiba       | Satellite C855-12R          | Notebook    | [dbde83db50](https://linux-hardware.org/?probe=dbde83db50) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [427ee1a6de](https://linux-hardware.org/?probe=427ee1a6de) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [585419cd38](https://linux-hardware.org/?probe=585419cd38) | Nov 17, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [04db0a2350](https://linux-hardware.org/?probe=04db0a2350) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | Notebook    | [9dff5423c9](https://linux-hardware.org/?probe=9dff5423c9) | Nov 17, 2021 |
| Dell          | Latitude E7270              | Notebook    | [70a4c30534](https://linux-hardware.org/?probe=70a4c30534) | Nov 17, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [c48f95d233](https://linux-hardware.org/?probe=c48f95d233) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [c69f79e654](https://linux-hardware.org/?probe=c69f79e654) | Nov 17, 2021 |
| HP            | Pavilion 15                 | Notebook    | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| Toshiba       | Satellite C855-12R          | Notebook    | [eefe2dc8be](https://linux-hardware.org/?probe=eefe2dc8be) | Nov 17, 2021 |
| HP            | Pavilion 15                 | Notebook    | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [ddfb1c2b1a](https://linux-hardware.org/?probe=ddfb1c2b1a) | Nov 17, 2021 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [61734716ea](https://linux-hardware.org/?probe=61734716ea) | Nov 16, 2021 |
| HP            | ENVY Laptop 15t-ep000       | Notebook    | [02c2ed5954](https://linux-hardware.org/?probe=02c2ed5954) | Nov 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [c4763ca2a5](https://linux-hardware.org/?probe=c4763ca2a5) | Nov 16, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [db85b885ae](https://linux-hardware.org/?probe=db85b885ae) | Nov 16, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6b1f5ce8b7](https://linux-hardware.org/?probe=6b1f5ce8b7) | Nov 16, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [53b3fced16](https://linux-hardware.org/?probe=53b3fced16) | Nov 16, 2021 |
| Toshiba       | Satellite C855-12R          | Notebook    | [ccf125eb47](https://linux-hardware.org/?probe=ccf125eb47) | Nov 16, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9404dfb1fe](https://linux-hardware.org/?probe=9404dfb1fe) | Nov 16, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [6398858488](https://linux-hardware.org/?probe=6398858488) | Nov 16, 2021 |
| Notebook      | NH55RGQ                     | Notebook    | [b3cb30c28d](https://linux-hardware.org/?probe=b3cb30c28d) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3412d5cf0b](https://linux-hardware.org/?probe=3412d5cf0b) | Nov 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bdd9599f2f](https://linux-hardware.org/?probe=bdd9599f2f) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [1119a0805e](https://linux-hardware.org/?probe=1119a0805e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [dbaa27643e](https://linux-hardware.org/?probe=dbaa27643e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [aad4a92e0e](https://linux-hardware.org/?probe=aad4a92e0e) | Nov 16, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [75e80e1ea8](https://linux-hardware.org/?probe=75e80e1ea8) | Nov 15, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [06f896ff98](https://linux-hardware.org/?probe=06f896ff98) | Nov 15, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b4ebd974c1](https://linux-hardware.org/?probe=b4ebd974c1) | Nov 15, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [8da42387a5](https://linux-hardware.org/?probe=8da42387a5) | Nov 15, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [97ed26b846](https://linux-hardware.org/?probe=97ed26b846) | Nov 15, 2021 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [8cf8f98a53](https://linux-hardware.org/?probe=8cf8f98a53) | Nov 15, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [dd0bfcd823](https://linux-hardware.org/?probe=dd0bfcd823) | Nov 15, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [9ef2a8f6d7](https://linux-hardware.org/?probe=9ef2a8f6d7) | Nov 15, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [098387cb9c](https://linux-hardware.org/?probe=098387cb9c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [516e448510](https://linux-hardware.org/?probe=516e448510) | Nov 14, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [8b02ecc2b6](https://linux-hardware.org/?probe=8b02ecc2b6) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | Notebook    | [70b84217bd](https://linux-hardware.org/?probe=70b84217bd) | Nov 14, 2021 |
| Dell          | Precision 3541              | Notebook    | [a21fd45ac3](https://linux-hardware.org/?probe=a21fd45ac3) | Nov 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [54bb479f64](https://linux-hardware.org/?probe=54bb479f64) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | Notebook    | [d88aea84ef](https://linux-hardware.org/?probe=d88aea84ef) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [a778aba19c](https://linux-hardware.org/?probe=a778aba19c) | Nov 14, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [3a6a636384](https://linux-hardware.org/?probe=3a6a636384) | Nov 14, 2021 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [2bca77430e](https://linux-hardware.org/?probe=2bca77430e) | Nov 14, 2021 |
| Dell          | Latitude 5511               | Notebook    | [dc7c10f4e2](https://linux-hardware.org/?probe=dc7c10f4e2) | Nov 13, 2021 |
| Dell          | Latitude 5511               | Notebook    | [b0ca679bc5](https://linux-hardware.org/?probe=b0ca679bc5) | Nov 13, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [68633b9bf5](https://linux-hardware.org/?probe=68633b9bf5) | Nov 13, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2142069a51](https://linux-hardware.org/?probe=2142069a51) | Nov 13, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [bc6a3771aa](https://linux-hardware.org/?probe=bc6a3771aa) | Nov 13, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [9e8eab1073](https://linux-hardware.org/?probe=9e8eab1073) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | Notebook    | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [e1cc8b1ee3](https://linux-hardware.org/?probe=e1cc8b1ee3) | Nov 13, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [40de24f0e5](https://linux-hardware.org/?probe=40de24f0e5) | Nov 13, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [5cbec68d6e](https://linux-hardware.org/?probe=5cbec68d6e) | Nov 13, 2021 |
| Positivo      | V142N_4G                    | Notebook    | [6afdf02b96](https://linux-hardware.org/?probe=6afdf02b96) | Nov 13, 2021 |
| ASUSTek       | H61M-CS                     | Desktop     | [22858e9ab9](https://linux-hardware.org/?probe=22858e9ab9) | Nov 13, 2021 |
| Acer          | Swift SFX14-41G             | Notebook    | [04e988d138](https://linux-hardware.org/?probe=04e988d138) | Nov 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [85929a9a18](https://linux-hardware.org/?probe=85929a9a18) | Nov 12, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [5991ba5f44](https://linux-hardware.org/?probe=5991ba5f44) | Nov 12, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [3bbda8b194](https://linux-hardware.org/?probe=3bbda8b194) | Nov 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Dell          | Precision 5510              | Notebook    | [80bbc48bce](https://linux-hardware.org/?probe=80bbc48bce) | Nov 12, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e85856bbef](https://linux-hardware.org/?probe=e85856bbef) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| AMI           | Intel                       | Convertible | [670ce3c062](https://linux-hardware.org/?probe=670ce3c062) | Nov 11, 2021 |
| System76      | Oryx Pro                    | Notebook    | [77cf902290](https://linux-hardware.org/?probe=77cf902290) | Nov 11, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [61afe68685](https://linux-hardware.org/?probe=61afe68685) | Nov 11, 2021 |
| Dell          | Latitude E7440              | Notebook    | [e907f0bbf1](https://linux-hardware.org/?probe=e907f0bbf1) | Nov 11, 2021 |
| ASUSTek       | X202EV                      | Notebook    | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| Dell          | 0DXJD9 A00                  | Desktop     | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [f5ceaaf6fe](https://linux-hardware.org/?probe=f5ceaaf6fe) | Nov 11, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [588c351d40](https://linux-hardware.org/?probe=588c351d40) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [ac9d7f968f](https://linux-hardware.org/?probe=ac9d7f968f) | Nov 10, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| ASUSTek       | T102HA                      | Notebook    | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| LG Electro... | 14Z90P-G.AR53A              | Notebook    | [a1fb8771db](https://linux-hardware.org/?probe=a1fb8771db) | Nov 10, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [99ece77400](https://linux-hardware.org/?probe=99ece77400) | Nov 10, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [807e59f1e3](https://linux-hardware.org/?probe=807e59f1e3) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| ZOTAC         | ZBOX-CA621NANO              | Mini pc     | [e540507afc](https://linux-hardware.org/?probe=e540507afc) | Nov 10, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [ca1489298b](https://linux-hardware.org/?probe=ca1489298b) | Nov 10, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c8fb558bb7](https://linux-hardware.org/?probe=c8fb558bb7) | Nov 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | Notebook    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [c5ae0c1fca](https://linux-hardware.org/?probe=c5ae0c1fca) | Nov 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [81605538eb](https://linux-hardware.org/?probe=81605538eb) | Nov 09, 2021 |
| MSI           | GL62M 7RDX                  | Notebook    | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [3587a95d63](https://linux-hardware.org/?probe=3587a95d63) | Nov 09, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [1c63b3b4ce](https://linux-hardware.org/?probe=1c63b3b4ce) | Nov 09, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [09cae8a245](https://linux-hardware.org/?probe=09cae8a245) | Nov 09, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [cb4e2271c0](https://linux-hardware.org/?probe=cb4e2271c0) | Nov 09, 2021 |
| Toshiba       | NB255                       | Notebook    | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| HP            | 2215                        | Desktop     | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d4a2a86c38](https://linux-hardware.org/?probe=d4a2a86c38) | Nov 09, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [fdbec54288](https://linux-hardware.org/?probe=fdbec54288) | Nov 08, 2021 |
| HP            | Notebook                    | Notebook    | [e254c5c947](https://linux-hardware.org/?probe=e254c5c947) | Nov 08, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [5f5424fe84](https://linux-hardware.org/?probe=5f5424fe84) | Nov 08, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [74b5acd6cd](https://linux-hardware.org/?probe=74b5acd6cd) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [a7510caa6d](https://linux-hardware.org/?probe=a7510caa6d) | Nov 08, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [2eebb6842a](https://linux-hardware.org/?probe=2eebb6842a) | Nov 08, 2021 |
| Seco          | C40 C                       | Desktop     | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [0e47ec7819](https://linux-hardware.org/?probe=0e47ec7819) | Nov 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005GMH    | Notebook    | [146b572cd0](https://linux-hardware.org/?probe=146b572cd0) | Nov 08, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [0812e26e5a](https://linux-hardware.org/?probe=0812e26e5a) | Nov 08, 2021 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [65e1d14e1c](https://linux-hardware.org/?probe=65e1d14e1c) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [8988b7e735](https://linux-hardware.org/?probe=8988b7e735) | Nov 08, 2021 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [b996ce8823](https://linux-hardware.org/?probe=b996ce8823) | Nov 07, 2021 |
| Acer          | Aspire Z3-615               | All in one  | [fa3d223e18](https://linux-hardware.org/?probe=fa3d223e18) | Nov 07, 2021 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [6269149643](https://linux-hardware.org/?probe=6269149643) | Nov 07, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [6a2354e970](https://linux-hardware.org/?probe=6a2354e970) | Nov 07, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef16e3ad0f](https://linux-hardware.org/?probe=ef16e3ad0f) | Nov 07, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| Dell          | 0C522T A03                  | Desktop     | [43d8e3d9d8](https://linux-hardware.org/?probe=43d8e3d9d8) | Nov 07, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [b4d29007be](https://linux-hardware.org/?probe=b4d29007be) | Nov 07, 2021 |
| ABIT          | AX78                        | Desktop     | [3d56ae3738](https://linux-hardware.org/?probe=3d56ae3738) | Nov 06, 2021 |
| Dell          | Latitude E7440              | Notebook    | [b2560457a5](https://linux-hardware.org/?probe=b2560457a5) | Nov 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af116b7c35](https://linux-hardware.org/?probe=af116b7c35) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ced169a0b1](https://linux-hardware.org/?probe=ced169a0b1) | Nov 06, 2021 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [34a03f8adf](https://linux-hardware.org/?probe=34a03f8adf) | Nov 06, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [bde89fd503](https://linux-hardware.org/?probe=bde89fd503) | Nov 06, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [37685b5198](https://linux-hardware.org/?probe=37685b5198) | Nov 06, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6cce11439f](https://linux-hardware.org/?probe=6cce11439f) | Nov 06, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| HP            | 250 G1                      | Notebook    | [1c52b861c7](https://linux-hardware.org/?probe=1c52b861c7) | Nov 06, 2021 |
| Lenovo        | ThinkPad E14 20RA001XIX     | Notebook    | [98d8c0fbdb](https://linux-hardware.org/?probe=98d8c0fbdb) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Notebook      | W65_W67RZ                   | Notebook    | [153b2a920d](https://linux-hardware.org/?probe=153b2a920d) | Nov 05, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [f8ce8bca36](https://linux-hardware.org/?probe=f8ce8bca36) | Nov 05, 2021 |
| MSI           | Z97M-G43                    | Desktop     | [7b0e15a051](https://linux-hardware.org/?probe=7b0e15a051) | Nov 05, 2021 |
| HONOR         | NBD-WXX9                    | Notebook    | [1030fbbff6](https://linux-hardware.org/?probe=1030fbbff6) | Nov 05, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [ad6e327cf5](https://linux-hardware.org/?probe=ad6e327cf5) | Nov 05, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [32aedc2d5b](https://linux-hardware.org/?probe=32aedc2d5b) | Nov 05, 2021 |
| Unknown       | Unknown                     | Notebook    | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| ASUSTek       | TP410UAR                    | Convertible | [a4d5174826](https://linux-hardware.org/?probe=a4d5174826) | Nov 05, 2021 |
| HP            | ZBook 14u G5                | Notebook    | [ec192642ba](https://linux-hardware.org/?probe=ec192642ba) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8e06f2617d](https://linux-hardware.org/?probe=8e06f2617d) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [1a2dda8941](https://linux-hardware.org/?probe=1a2dda8941) | Nov 05, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [ed53f501e6](https://linux-hardware.org/?probe=ed53f501e6) | Nov 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [fa84d0d544](https://linux-hardware.org/?probe=fa84d0d544) | Nov 04, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [50301dd3e3](https://linux-hardware.org/?probe=50301dd3e3) | Nov 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [f5ef935897](https://linux-hardware.org/?probe=f5ef935897) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [f29c3d7003](https://linux-hardware.org/?probe=f29c3d7003) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | Notebook    | [a795236afd](https://linux-hardware.org/?probe=a795236afd) | Nov 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [cd291857e2](https://linux-hardware.org/?probe=cd291857e2) | Nov 04, 2021 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [5baf0ce3af](https://linux-hardware.org/?probe=5baf0ce3af) | Nov 04, 2021 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | Notebook    | [6ee78bd50a](https://linux-hardware.org/?probe=6ee78bd50a) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HN0013UK    | Notebook    | [8454cff91f](https://linux-hardware.org/?probe=8454cff91f) | Nov 04, 2021 |
| Dell          | Studio 1537                 | Notebook    | [d040c159b8](https://linux-hardware.org/?probe=d040c159b8) | Nov 04, 2021 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [14c9dda4cd](https://linux-hardware.org/?probe=14c9dda4cd) | Nov 04, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [00a97d0eba](https://linux-hardware.org/?probe=00a97d0eba) | Nov 03, 2021 |
| HP            | ProBook 430 G3              | Notebook    | [1d421060d7](https://linux-hardware.org/?probe=1d421060d7) | Nov 03, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4478f8c509](https://linux-hardware.org/?probe=4478f8c509) | Nov 03, 2021 |
| Dell          | Precision 5510              | Notebook    | [eb702ce1e6](https://linux-hardware.org/?probe=eb702ce1e6) | Nov 03, 2021 |
| HP            | EliteBook x360 830 G5       | Convertible | [dedf8fbd8c](https://linux-hardware.org/?probe=dedf8fbd8c) | Nov 03, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [fe22676441](https://linux-hardware.org/?probe=fe22676441) | Nov 03, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [c68c3a5c3b](https://linux-hardware.org/?probe=c68c3a5c3b) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [10bd49d9c0](https://linux-hardware.org/?probe=10bd49d9c0) | Nov 03, 2021 |
| Dell          | Latitude 5590               | Notebook    | [5bc1ed5978](https://linux-hardware.org/?probe=5bc1ed5978) | Nov 03, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0297ef158a](https://linux-hardware.org/?probe=0297ef158a) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | Notebook    | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | Notebook    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [c26ea680eb](https://linux-hardware.org/?probe=c26ea680eb) | Nov 03, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3acf5c243f](https://linux-hardware.org/?probe=3acf5c243f) | Nov 03, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [10a45363fe](https://linux-hardware.org/?probe=10a45363fe) | Nov 03, 2021 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [f30e20e67b](https://linux-hardware.org/?probe=f30e20e67b) | Nov 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| Lenovo        | ThinkPad X395 20NL0005US    | Notebook    | [b65f4d5ba3](https://linux-hardware.org/?probe=b65f4d5ba3) | Nov 03, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | Notebook    | [8c19662b7e](https://linux-hardware.org/?probe=8c19662b7e) | Nov 03, 2021 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [4aae9bdc03](https://linux-hardware.org/?probe=4aae9bdc03) | Nov 03, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [c8716ec9a6](https://linux-hardware.org/?probe=c8716ec9a6) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | Notebook    | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [54b32173dd](https://linux-hardware.org/?probe=54b32173dd) | Nov 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [40df244ae9](https://linux-hardware.org/?probe=40df244ae9) | Nov 02, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [93de1508cb](https://linux-hardware.org/?probe=93de1508cb) | Oct 31, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [28b152bb19](https://linux-hardware.org/?probe=28b152bb19) | Oct 30, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | Notebook    | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1310b8abf4](https://linux-hardware.org/?probe=1310b8abf4) | Oct 30, 2021 |
| Framework     | Laptop                      | Notebook    | [04db6c2222](https://linux-hardware.org/?probe=04db6c2222) | Oct 29, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [5b10037da5](https://linux-hardware.org/?probe=5b10037da5) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [1be6c8dc87](https://linux-hardware.org/?probe=1be6c8dc87) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [e9a8fb1275](https://linux-hardware.org/?probe=e9a8fb1275) | Oct 27, 2021 |
| BESSTAR Te... | X400                        | Notebook    | [9cfc0bb300](https://linux-hardware.org/?probe=9cfc0bb300) | Oct 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5f67b298ab](https://linux-hardware.org/?probe=5f67b298ab) | Oct 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [136c409f1a](https://linux-hardware.org/?probe=136c409f1a) | Oct 27, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [ae8daa788a](https://linux-hardware.org/?probe=ae8daa788a) | Oct 27, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [91c5853577](https://linux-hardware.org/?probe=91c5853577) | Oct 25, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | Notebook    | [d3720f9145](https://linux-hardware.org/?probe=d3720f9145) | Oct 25, 2021 |
| Alienware     | Area-51m R2                 | Notebook    | [c3f94d8599](https://linux-hardware.org/?probe=c3f94d8599) | Oct 24, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fac95138dc](https://linux-hardware.org/?probe=fac95138dc) | Oct 23, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [725627d16b](https://linux-hardware.org/?probe=725627d16b) | Oct 23, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [98bd384a42](https://linux-hardware.org/?probe=98bd384a42) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c91bc1deb](https://linux-hardware.org/?probe=1c91bc1deb) | Oct 23, 2021 |
| HP            | EliteBook x360 830 G5       | Convertible | [9383081522](https://linux-hardware.org/?probe=9383081522) | Oct 22, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [9932dd3c21](https://linux-hardware.org/?probe=9932dd3c21) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| Foxconn       | H81MXV FAB A                | Desktop     | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [faa49a332b](https://linux-hardware.org/?probe=faa49a332b) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | Notebook    | [4dbc231901](https://linux-hardware.org/?probe=4dbc231901) | Oct 18, 2021 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [746401b748](https://linux-hardware.org/?probe=746401b748) | Oct 18, 2021 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [b1c4af0594](https://linux-hardware.org/?probe=b1c4af0594) | Oct 17, 2021 |
| GPU Compan... | GWTN156-1                   | Notebook    | [3cb0b09b48](https://linux-hardware.org/?probe=3cb0b09b48) | Oct 17, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [ac488ba246](https://linux-hardware.org/?probe=ac488ba246) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [362e1d3b99](https://linux-hardware.org/?probe=362e1d3b99) | Oct 15, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [bc716e921b](https://linux-hardware.org/?probe=bc716e921b) | Oct 15, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [01ce3b252c](https://linux-hardware.org/?probe=01ce3b252c) | Oct 14, 2021 |
| Dell          | Precision 5550              | Notebook    | [15a0f61f84](https://linux-hardware.org/?probe=15a0f61f84) | Oct 14, 2021 |
| Unknown       | Unknown Product             | Soc         | [bf8abdfb09](https://linux-hardware.org/?probe=bf8abdfb09) | Oct 14, 2021 |
| Unknown       | Unknown Product             | Soc         | [3a844f7153](https://linux-hardware.org/?probe=3a844f7153) | Oct 14, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2ff2eb607a](https://linux-hardware.org/?probe=2ff2eb607a) | Oct 14, 2021 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [b9971b685a](https://linux-hardware.org/?probe=b9971b685a) | Oct 12, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [4bb5ac9410](https://linux-hardware.org/?probe=4bb5ac9410) | Oct 12, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [eee2a960f5](https://linux-hardware.org/?probe=eee2a960f5) | Oct 11, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [d4acf59f3b](https://linux-hardware.org/?probe=d4acf59f3b) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5b4efb9e18](https://linux-hardware.org/?probe=5b4efb9e18) | Oct 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [7b26df9bc4](https://linux-hardware.org/?probe=7b26df9bc4) | Oct 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [cfbe862160](https://linux-hardware.org/?probe=cfbe862160) | Oct 10, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [a9ceb4591e](https://linux-hardware.org/?probe=a9ceb4591e) | Oct 09, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [7c210a60ab](https://linux-hardware.org/?probe=7c210a60ab) | Oct 09, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [2eeb05ff03](https://linux-hardware.org/?probe=2eeb05ff03) | Oct 09, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [43ded3a853](https://linux-hardware.org/?probe=43ded3a853) | Oct 09, 2021 |
| HP            | ENVY Laptop 15t-ep000       | Notebook    | [f9b69ffa3d](https://linux-hardware.org/?probe=f9b69ffa3d) | Oct 08, 2021 |
| Dell          | Inspiron 5505               | Notebook    | [d136f5d8f7](https://linux-hardware.org/?probe=d136f5d8f7) | Oct 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b3d0295208](https://linux-hardware.org/?probe=b3d0295208) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26c62915e0](https://linux-hardware.org/?probe=26c62915e0) | Oct 07, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [75d34f09c4](https://linux-hardware.org/?probe=75d34f09c4) | Oct 06, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | Notebook    | [146866c629](https://linux-hardware.org/?probe=146866c629) | Oct 06, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [17a03c217e](https://linux-hardware.org/?probe=17a03c217e) | Oct 04, 2021 |
| Lenovo        | ThinkPad L390 20NUS01W00    | Convertible | [880201a9eb](https://linux-hardware.org/?probe=880201a9eb) | Oct 04, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [db435ab99c](https://linux-hardware.org/?probe=db435ab99c) | Oct 03, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [08adba2c54](https://linux-hardware.org/?probe=08adba2c54) | Oct 02, 2021 |
| HUAWEI        | EUL-WX9                     | Notebook    | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [1dbb7762f6](https://linux-hardware.org/?probe=1dbb7762f6) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Dell          | Studio 1537                 | Notebook    | [aae900457c](https://linux-hardware.org/?probe=aae900457c) | Oct 01, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [103d2198a4](https://linux-hardware.org/?probe=103d2198a4) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| Framework     | Laptop                      | Notebook    | [95576917c8](https://linux-hardware.org/?probe=95576917c8) | Sep 29, 2021 |
| Notebook      | N2x0WU                      | Notebook    | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Gigabyte      | H81M-S2H                    | Desktop     | [b8c27bd56c](https://linux-hardware.org/?probe=b8c27bd56c) | Sep 28, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [82e0f76133](https://linux-hardware.org/?probe=82e0f76133) | Sep 25, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [2f771e8271](https://linux-hardware.org/?probe=2f771e8271) | Sep 24, 2021 |
| Lenovo        | ThinkPad E480 20KNS0MC00    | Notebook    | [ba847bc0c4](https://linux-hardware.org/?probe=ba847bc0c4) | Sep 23, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [e75373a634](https://linux-hardware.org/?probe=e75373a634) | Sep 23, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [0b68c3f5c3](https://linux-hardware.org/?probe=0b68c3f5c3) | Sep 20, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| HP            | G42                         | Notebook    | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
| HP            | ZBook 15u G5                | Notebook    | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [ebac1c499f](https://linux-hardware.org/?probe=ebac1c499f) | Sep 15, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [3875512e39](https://linux-hardware.org/?probe=3875512e39) | Sep 14, 2021 |
| ASUSTek       | ROG STRIX B360-I GAMING     | Desktop     | [4fb9ed180b](https://linux-hardware.org/?probe=4fb9ed180b) | Sep 14, 2021 |
| ASUSTek       | G71V                        | Notebook    | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2766de5f8a](https://linux-hardware.org/?probe=2766de5f8a) | Sep 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [2b21ef140a](https://linux-hardware.org/?probe=2b21ef140a) | Sep 05, 2021 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | Notebook    | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [3231b34d4d](https://linux-hardware.org/?probe=3231b34d4d) | Aug 24, 2021 |
| Dell          | Latitude E5470              | Notebook    | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a94ad8a323](https://linux-hardware.org/?probe=a94ad8a323) | Aug 22, 2021 |
| AZW           | GK mini                     | Mini pc     | [995cc09b8d](https://linux-hardware.org/?probe=995cc09b8d) | Aug 22, 2021 |
| AZW           | GK mini                     | Mini pc     | [2024a6712e](https://linux-hardware.org/?probe=2024a6712e) | Aug 22, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| HP            | 8055                        | Desktop     | [29f5b9a7ab](https://linux-hardware.org/?probe=29f5b9a7ab) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [f48bc9ac9d](https://linux-hardware.org/?probe=f48bc9ac9d) | Aug 07, 2021 |
| Notebook      | P377SM-A                    | Notebook    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [7dcd16d3fd](https://linux-hardware.org/?probe=7dcd16d3fd) | Jul 14, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [eedd464065](https://linux-hardware.org/?probe=eedd464065) | Jul 14, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [8d1e68aad0](https://linux-hardware.org/?probe=8d1e68aad0) | Jul 07, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [852a8a103d](https://linux-hardware.org/?probe=852a8a103d) | Jul 04, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [3a0ca9b90c](https://linux-hardware.org/?probe=3a0ca9b90c) | Jul 01, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [3ed1ee1f81](https://linux-hardware.org/?probe=3ed1ee1f81) | Jun 25, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [f611d9ec88](https://linux-hardware.org/?probe=f611d9ec88) | Jun 23, 2021 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [95ba18d5da](https://linux-hardware.org/?probe=95ba18d5da) | Jun 23, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [511e8019e0](https://linux-hardware.org/?probe=511e8019e0) | Jun 19, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| Notebook      | P377SM-A                    | Notebook    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook      | P377SM-A                    | Notebook    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [7a294509de](https://linux-hardware.org/?probe=7a294509de) | May 15, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [4238374bcc](https://linux-hardware.org/?probe=4238374bcc) | Apr 26, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [89892d4957](https://linux-hardware.org/?probe=89892d4957) | Apr 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [97c124c8a3](https://linux-hardware.org/?probe=97c124c8a3) | Apr 18, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |
| Lenovo        | ThinkPad W541 20EF000UMN    | Notebook    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c0901f4607](https://linux-hardware.org/?probe=c0901f4607) | Mar 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                | Computers | Percent |
|----------------------------------------|-----------|---------|
| 5.14.10-300.fc35.x86_64                | 99        | 7.16%   |
| 5.15.6-200.fc35.x86_64                 | 81        | 5.86%   |
| 5.16.16-200.fc35.x86_64                | 70        | 5.06%   |
| 5.14.16-301.fc35.x86_64                | 68        | 4.92%   |
| 5.15.12-200.fc35.x86_64                | 64        | 4.63%   |
| 5.14.18-300.fc35.x86_64                | 62        | 4.48%   |
| 5.16.12-200.fc35.x86_64                | 61        | 4.41%   |
| 5.16.18-200.fc35.x86_64                | 59        | 4.27%   |
| 5.16.9-200.fc35.x86_64                 | 55        | 3.98%   |
| 5.14.17-301.fc35.x86_64                | 48        | 3.47%   |
| 5.15.16-200.fc35.x86_64                | 46        | 3.33%   |
| 5.16.11-200.fc35.x86_64                | 39        | 2.82%   |
| 5.14.14-300.fc35.x86_64                | 39        | 2.82%   |
| 5.16.5-200.fc35.x86_64                 | 37        | 2.68%   |
| 5.15.11-200.fc35.x86_64                | 36        | 2.6%    |
| 5.15.14-200.fc35.x86_64                | 32        | 2.31%   |
| 5.15.18-200.fc35.x86_64                | 31        | 2.24%   |
| 5.15.13-200.fc35.x86_64                | 30        | 2.17%   |
| 5.15.8-200.fc35.x86_64                 | 29        | 2.1%    |
| 5.15.10-200.fc35.x86_64                | 29        | 2.1%    |
| 5.14.15-300.fc35.x86_64                | 29        | 2.1%    |
| 5.16.8-200.fc35.x86_64                 | 23        | 1.66%   |
| 5.16.15-201.fc35.x86_64                | 23        | 1.66%   |
| 5.15.5-200.fc35.x86_64                 | 22        | 1.59%   |
| 5.15.4-201.fc35.x86_64                 | 21        | 1.52%   |
| 5.16.14-200.fc35.x86_64                | 18        | 1.3%    |
| 5.15.7-200.fc35.x86_64                 | 18        | 1.3%    |
| 5.16.7-200.fc35.x86_64                 | 17        | 1.23%   |
| 5.15.17-200.fc35.x86_64                | 16        | 1.16%   |
| 5.15.15-200.fc35.x86_64                | 16        | 1.16%   |
| 5.14.9-300.fc35.x86_64                 | 15        | 1.08%   |
| 5.14.0-60.fc35.x86_64                  | 10        | 0.72%   |
| 5.16.13-200.fc35.x86_64                | 9         | 0.65%   |
| 5.16.10-200.fc35.x86_64                | 8         | 0.58%   |
| 5.14.11-300.fc35.x86_64                | 7         | 0.51%   |
| 5.16.17-200.fc35.x86_64                | 5         | 0.36%   |
| 5.14.0-0.rc5.42.fc35.x86_64            | 5         | 0.36%   |
| 5.14.7-300.fc35.x86_64                 | 4         | 0.29%   |
| 5.16.2-200.fc35.x86_64                 | 3         | 0.22%   |
| 5.14.6-300.fc35.x86_64                 | 3         | 0.22%   |
| 5.14.12-300.fc35.x86_64                | 3         | 0.22%   |
| 5.14.0-0.rc6.46.fc35.x86_64            | 3         | 0.22%   |
| 5.15.6-200.rog.fc35.x86_64             | 2         | 0.14%   |
| 5.15.5-xm1tt.0.fc35.x86_64             | 2         | 0.14%   |
| 5.14.5-300.fc35.x86_64                 | 2         | 0.14%   |
| 5.14.3-300.fc35.x86_64                 | 2         | 0.14%   |
| 5.14.20-300.fc35.x86_64                | 2         | 0.14%   |
| 5.14.1-300.fc35.x86_64                 | 2         | 0.14%   |
| 5.12.0-0.rc7.189.fc35.x86_64           | 2         | 0.14%   |
| 5.11.12-300.fc34.x86_64                | 2         | 0.14%   |
| 5.9.16-200.fc33.x86_64                 | 1         | 0.07%   |
| 5.8.15-301.fc33.x86_64                 | 1         | 0.07%   |
| 5.17.1-xm1.0.fc35.x86_64               | 1         | 0.07%   |
| 5.17.0-0.rc5.102.vanilla.1.fc35.x86_64 | 1         | 0.07%   |
| 5.16.4-200.fc35.x86_64                 | 1         | 0.07%   |
| 5.16.2-225.vanilla.1.fc35.x86_64       | 1         | 0.07%   |
| 5.16.16-lqx2.0.fc35.x86_64             | 1         | 0.07%   |
| 5.16.13-xm1.0.fc35.x86_64              | 1         | 0.07%   |
| 5.16.12-250.vanilla.1.fc35.x86_64      | 1         | 0.07%   |
| 5.16.12-200.mbp.fc33.x86_64            | 1         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.10 | 99        | 7.19%   |
| 5.15.6  | 86        | 6.25%   |
| 5.16.16 | 71        | 5.16%   |
| 5.14.16 | 69        | 5.01%   |
| 5.15.12 | 65        | 4.72%   |
| 5.16.12 | 63        | 4.58%   |
| 5.14.18 | 63        | 4.58%   |
| 5.16.18 | 59        | 4.28%   |
| 5.16.9  | 55        | 3.99%   |
| 5.14.17 | 48        | 3.49%   |
| 5.15.16 | 46        | 3.34%   |
| 5.16.11 | 40        | 2.9%    |
| 5.14.14 | 40        | 2.9%    |
| 5.16.5  | 37        | 2.69%   |
| 5.15.11 | 37        | 2.69%   |
| 5.15.14 | 33        | 2.4%    |
| 5.15.13 | 32        | 2.32%   |
| 5.15.8  | 31        | 2.25%   |
| 5.15.18 | 31        | 2.25%   |
| 5.14.15 | 30        | 2.18%   |
| 5.15.10 | 29        | 2.11%   |
| 5.15.5  | 24        | 1.74%   |
| 5.16.8  | 23        | 1.67%   |
| 5.16.15 | 23        | 1.67%   |
| 5.15.4  | 23        | 1.67%   |
| 5.14.0  | 20        | 1.45%   |
| 5.16.14 | 18        | 1.31%   |
| 5.15.7  | 18        | 1.31%   |
| 5.16.7  | 17        | 1.23%   |
| 5.15.15 | 17        | 1.23%   |
| 5.15.17 | 16        | 1.16%   |
| 5.14.9  | 16        | 1.16%   |
| 5.16.13 | 10        | 0.73%   |
| 5.16.10 | 10        | 0.73%   |
| 5.14.11 | 7         | 0.51%   |
| 5.12.0  | 7         | 0.51%   |
| 5.16.17 | 5         | 0.36%   |
| 5.16.0  | 5         | 0.36%   |
| 5.16.2  | 4         | 0.29%   |
| 5.14.7  | 4         | 0.29%   |
| 5.13.0  | 4         | 0.29%   |
| 5.15.0  | 3         | 0.22%   |
| 5.14.6  | 3         | 0.22%   |
| 5.14.12 | 3         | 0.22%   |
| 5.15.2  | 2         | 0.15%   |
| 5.14.8  | 2         | 0.15%   |
| 5.14.5  | 2         | 0.15%   |
| 5.14.3  | 2         | 0.15%   |
| 5.14.20 | 2         | 0.15%   |
| 5.14.1  | 2         | 0.15%   |
| 5.13.19 | 2         | 0.15%   |
| 5.11.12 | 2         | 0.15%   |
| 5.9.16  | 1         | 0.07%   |
| 5.8.15  | 1         | 0.07%   |
| 5.17.1  | 1         | 0.07%   |
| 5.17.0  | 1         | 0.07%   |
| 5.16.4  | 1         | 0.07%   |
| 5.16.1  | 1         | 0.07%   |
| 5.15.19 | 1         | 0.07%   |
| 5.14.13 | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 462       | 35.24%  |
| 5.16    | 419       | 31.96%  |
| 5.14    | 402       | 30.66%  |
| 5.13    | 9         | 0.69%   |
| 5.12    | 8         | 0.61%   |
| 5.11    | 4         | 0.31%   |
| 5.10    | 3         | 0.23%   |
| 5.17    | 2         | 0.15%   |
| 5.9     | 1         | 0.08%   |
| 5.8     | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1219      | 99.84%  |
| aarch64 | 2         | 0.16%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 953       | 76.92%  |
| KDE5            | 125       | 10.09%  |
| Unknown         | 47        | 3.79%   |
| Cinnamon        | 24        | 1.94%   |
| X-Cinnamon      | 19        | 1.53%   |
| MATE            | 19        | 1.53%   |
| XFCE            | 15        | 1.21%   |
| GNOME Classic   | 8         | 0.65%   |
| KDE             | 7         | 0.56%   |
| LXDE            | 4         | 0.32%   |
| sway            | 3         | 0.24%   |
| LXQt            | 3         | 0.24%   |
| i3              | 3         | 0.24%   |
| Pantheon        | 2         | 0.16%   |
| openbox         | 2         | 0.16%   |
| fluxbox         | 2         | 0.16%   |
| GNOME Flashback | 1         | 0.08%   |
| DWM             | 1         | 0.08%   |
| bspwm           | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 793       | 63.64%  |
| X11     | 402       | 32.26%  |
| Tty     | 27        | 2.17%   |
| Unknown | 23        | 1.85%   |
| Web     | 1         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 628       | 50.93%  |
| GDM     | 445       | 36.09%  |
| LightDM | 82        | 6.65%   |
| SDDM    | 73        | 5.92%   |
| LXDM    | 3         | 0.24%   |
| XDM     | 1         | 0.08%   |
| TDM     | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 636       | 51.79%  |
| en_GB      | 99        | 8.06%   |
| ru_RU      | 61        | 4.97%   |
| pt_BR      | 54        | 4.4%    |
| de_DE      | 45        | 3.66%   |
| fr_FR      | 43        | 3.5%    |
| it_IT      | 27        | 2.2%    |
| en_AU      | 27        | 2.2%    |
| en_CA      | 25        | 2.04%   |
| pl_PL      | 21        | 1.71%   |
| es_ES      | 20        | 1.63%   |
| es_MX      | 12        | 0.98%   |
| cs_CZ      | 10        | 0.81%   |
| nl_NL      | 9         | 0.73%   |
| nl_BE      | 8         | 0.65%   |
| es_CO      | 7         | 0.57%   |
| es_CL      | 7         | 0.57%   |
| en_IN      | 7         | 0.57%   |
| C          | 7         | 0.57%   |
| zh_CN      | 6         | 0.49%   |
| tr_TR      | 6         | 0.49%   |
| sv_SE      | 5         | 0.41%   |
| fr_CA      | 5         | 0.41%   |
| en_NZ      | 5         | 0.41%   |
| en_IL      | 5         | 0.41%   |
| fr_CH      | 4         | 0.33%   |
| es_AR      | 4         | 0.33%   |
| de_AT      | 4         | 0.33%   |
| Unknown    | 4         | 0.33%   |
| uk_UA      | 3         | 0.24%   |
| ru_UA      | 3         | 0.24%   |
| pt_PT      | 3         | 0.24%   |
| nb_NO      | 3         | 0.24%   |
| hu_HU      | 3         | 0.24%   |
| fi_FI      | 3         | 0.24%   |
| en_IE      | 3         | 0.24%   |
| de_CH      | 3         | 0.24%   |
| ca_ES      | 3         | 0.24%   |
| ro_RO      | 2         | 0.16%   |
| fr_BE      | 2         | 0.16%   |
| es_VE      | 2         | 0.16%   |
| es_GT      | 2         | 0.16%   |
| en_ZA      | 2         | 0.16%   |
| en_DK      | 2         | 0.16%   |
| da_DK      | 2         | 0.16%   |
| ar_SA      | 2         | 0.16%   |
| szl_PL     | 1         | 0.08%   |
| sr_RS      | 1         | 0.08%   |
| sk_SK      | 1         | 0.08%   |
| pa_IN      | 1         | 0.08%   |
| lt_LT      | 1         | 0.08%   |
| ja_JP      | 1         | 0.08%   |
| ga_IE      | 1         | 0.08%   |
| es_PE      | 1         | 0.08%   |
| es_EC      | 1         | 0.08%   |
| en_US.UTF8 | 1         | 0.08%   |
| el_GR      | 1         | 0.08%   |
| bs_BA      | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 982       | 79.64%  |
| BIOS | 251       | 20.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 905       | 73.7%   |
| Ext4    | 279       | 22.72%  |
| Xfs     | 37        | 3.01%   |
| Overlay | 5         | 0.41%   |
| Ext3    | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 636       | 51.41%  |
| GPT     | 528       | 42.68%  |
| MBR     | 73        | 5.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1101      | 89.15%  |
| Yes       | 134       | 10.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 998       | 80.74%  |
| Yes       | 238       | 19.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo                   | 255       | 20.88%  |
| ASUSTek Computer         | 173       | 14.17%  |
| Dell                     | 163       | 13.35%  |
| Hewlett-Packard          | 145       | 11.88%  |
| Gigabyte Technology      | 96        | 7.86%   |
| MSI                      | 83        | 6.8%    |
| Acer                     | 57        | 4.67%   |
| Apple                    | 41        | 3.36%   |
| ASRock                   | 25        | 2.05%   |
| HUAWEI                   | 20        | 1.64%   |
| Intel                    | 16        | 1.31%   |
| Notebook                 | 11        | 0.9%    |
| Toshiba                  | 10        | 0.82%   |
| Sony                     | 9         | 0.74%   |
| Fujitsu                  | 9         | 0.74%   |
| Samsung Electronics      | 8         | 0.66%   |
| Positivo                 | 6         | 0.49%   |
| Google                   | 6         | 0.49%   |
| Framework                | 5         | 0.41%   |
| System76                 | 4         | 0.33%   |
| Microsoft                | 4         | 0.33%   |
| TUXEDO                   | 3         | 0.25%   |
| Razer                    | 3         | 0.25%   |
| ECS                      | 3         | 0.25%   |
| BESSTAR Tech             | 3         | 0.25%   |
| AZW                      | 3         | 0.25%   |
| Avell High Performance   | 3         | 0.25%   |
| Unknown                  | 3         | 0.25%   |
| XFX                      | 2         | 0.16%   |
| Supermicro               | 2         | 0.16%   |
| PC Specialist            | 2         | 0.16%   |
| Panasonic                | 2         | 0.16%   |
| Medion                   | 2         | 0.16%   |
| HONOR                    | 2         | 0.16%   |
| Hampoo                   | 2         | 0.16%   |
| GPU Company              | 2         | 0.16%   |
| Gateway                  | 2         | 0.16%   |
| Fujitsu Siemens          | 2         | 0.16%   |
| AMI                      | 2         | 0.16%   |
| Alienware                | 2         | 0.16%   |
| ABIT                     | 2         | 0.16%   |
| ZOTAC                    | 1         | 0.08%   |
| TrekStor                 | 1         | 0.08%   |
| Timi                     | 1         | 0.08%   |
| SiComputer               | 1         | 0.08%   |
| Seco                     | 1         | 0.08%   |
| SCHNEIDER                | 1         | 0.08%   |
| RCA                      | 1         | 0.08%   |
| Positivo Bahia - VAIO    | 1         | 0.08%   |
| Pegatron                 | 1         | 0.08%   |
| PCWare                   | 1         | 0.08%   |
| ONN                      | 1         | 0.08%   |
| Mediacom                 | 1         | 0.08%   |
| MACHINIST                | 1         | 0.08%   |
| Login Informatica        | 1         | 0.08%   |
| LG Electronics           | 1         | 0.08%   |
| LDLC                     | 1         | 0.08%   |
| Jumper                   | 1         | 0.08%   |
| JINGSHA                  | 1         | 0.08%   |
| Inspire Technology Group | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 8         | 0.66%   |
| MSI MS-7C56                           | 5         | 0.41%   |
| HUAWEI KLVL-WXX9                      | 5         | 0.41%   |
| HP Notebook                           | 5         | 0.41%   |
| Framework Laptop                      | 5         | 0.41%   |
| Unknown                               | 5         | 0.41%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2     | 4         | 0.33%   |
| HP Pavilion Notebook                  | 4         | 0.33%   |
| Gigabyte B450M DS3H                   | 4         | 0.33%   |
| Dell XPS 13 7390                      | 4         | 0.33%   |
| Dell Latitude E7440                   | 4         | 0.33%   |
| ASUS ROG CROSSHAIR VII HERO           | 4         | 0.33%   |
| MSI MS-7D25                           | 3         | 0.25%   |
| MSI MS-7C84                           | 3         | 0.25%   |
| MSI MS-7C37                           | 3         | 0.25%   |
| MSI MS-7B93                           | 3         | 0.25%   |
| MSI MS-7B89                           | 3         | 0.25%   |
| MSI MS-7B86                           | 3         | 0.25%   |
| MSI MS-7B79                           | 3         | 0.25%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.25%   |
| Lenovo IdeaPad 530S-14IKB 81EU        | 3         | 0.25%   |
| Lenovo IdeaPad 3 14ALC6 82KT          | 3         | 0.25%   |
| HUAWEI HVY-WXX9                       | 3         | 0.25%   |
| HP Pavilion Aero Laptop 13-be0xxx     | 3         | 0.25%   |
| HP ENVY x360 Convertible 13-ay0xxx    | 3         | 0.25%   |
| HP EliteBook 840 G3                   | 3         | 0.25%   |
| Gigabyte X570 AORUS MASTER            | 3         | 0.25%   |
| Gigabyte B450 AORUS M                 | 3         | 0.25%   |
| Dell XPS 17 9700                      | 3         | 0.25%   |
| Dell XPS 15 9570                      | 3         | 0.25%   |
| Dell XPS 15 9550                      | 3         | 0.25%   |
| Dell XPS 13 9310                      | 3         | 0.25%   |
| Dell XPS 13 9305                      | 3         | 0.25%   |
| Dell Precision T3600                  | 3         | 0.25%   |
| Dell Precision 5510                   | 3         | 0.25%   |
| Dell OptiPlex 7010                    | 3         | 0.25%   |
| Dell Latitude 7490                    | 3         | 0.25%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM | 3         | 0.25%   |
| ASUS ROG Strix G513QY_G513QY          | 3         | 0.25%   |
| ASUS ROG STRIX B550-I GAMING          | 3         | 0.25%   |
| ASUS ROG STRIX B550-F GAMING          | 3         | 0.25%   |
| ASUS ROG STRIX B450-F GAMING          | 3         | 0.25%   |
| Apple MacBookPro9,2                   | 3         | 0.25%   |
| Apple MacBookPro14,1                  | 3         | 0.25%   |
| Apple iMac12,2                        | 3         | 0.25%   |
| Acer Swift SF314-42                   | 3         | 0.25%   |
| MSI MS-7C95                           | 2         | 0.16%   |
| MSI MS-7C94                           | 2         | 0.16%   |
| MSI MS-7C91                           | 2         | 0.16%   |
| MSI MS-7C52                           | 2         | 0.16%   |
| MSI MS-7B85                           | 2         | 0.16%   |
| MSI MS-7B10                           | 2         | 0.16%   |
| MSI MS-7A34                           | 2         | 0.16%   |
| MSI MS-7A33                           | 2         | 0.16%   |
| MSI MS-7817                           | 2         | 0.16%   |
| MSI GE75 Raider 10SE                  | 2         | 0.16%   |
| MSI Delta 15 A5EFK                    | 2         | 0.16%   |
| Microsoft Surface Pro                 | 2         | 0.16%   |
| Lenovo Yoga S740-14IIL 81RS           | 2         | 0.16%   |
| Lenovo Yoga 9 14ITL5 82BG             | 2         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 126       | 10.32%  |
| Lenovo IdeaPad     | 51        | 4.18%   |
| ASUS ROG           | 50        | 4.1%    |
| Dell Latitude      | 40        | 3.28%   |
| Dell Inspiron      | 40        | 3.28%   |
| Dell XPS           | 34        | 2.78%   |
| HP Pavilion        | 32        | 2.62%   |
| Acer Aspire        | 30        | 2.46%   |
| ASUS PRIME         | 23        | 1.88%   |
| HP EliteBook       | 21        | 1.72%   |
| Dell OptiPlex      | 20        | 1.64%   |
| HP ProBook         | 18        | 1.47%   |
| Dell Precision     | 15        | 1.23%   |
| HP Laptop          | 14        | 1.15%   |
| HP ENVY            | 14        | 1.15%   |
| ASUS TUF           | 13        | 1.06%   |
| Lenovo Yoga        | 12        | 0.98%   |
| Lenovo ThinkCentre | 12        | 0.98%   |
| ASUS VivoBook      | 12        | 0.98%   |
| Lenovo Legion      | 11        | 0.9%    |
| Acer Swift         | 11        | 0.9%    |
| Lenovo ThinkBook   | 9         | 0.74%   |
| Lenovo IdeaPadFlex | 9         | 0.74%   |
| Acer Nitro         | 9         | 0.74%   |
| Toshiba Satellite  | 8         | 0.66%   |
| HP ZBook           | 8         | 0.66%   |
| Gigabyte X570      | 8         | 0.66%   |
| ASUS All           | 8         | 0.66%   |
| Dell Vostro        | 7         | 0.57%   |
| ASUS ZenBook       | 6         | 0.49%   |
| ASUS ASUS          | 6         | 0.49%   |
| MSI MS-7C56        | 5         | 0.41%   |
| HUAWEI KLVL-WXX9   | 5         | 0.41%   |
| HP Notebook        | 5         | 0.41%   |
| HP Compaq          | 5         | 0.41%   |
| Gigabyte Z390      | 5         | 0.41%   |
| Gigabyte B450      | 5         | 0.41%   |
| Framework Laptop   | 5         | 0.41%   |
| Apple iMac12       | 5         | 0.41%   |
| Unknown            | 5         | 0.41%   |
| Microsoft Surface  | 4         | 0.33%   |
| HP OMEN            | 4         | 0.33%   |
| Gigabyte B550      | 4         | 0.33%   |
| Gigabyte B450M     | 4         | 0.33%   |
| Fujitsu LIFEBOOK   | 4         | 0.33%   |
| Dell G5            | 4         | 0.33%   |
| ASUS Maximus       | 4         | 0.33%   |
| Apple MacBookPro11 | 4         | 0.33%   |
| MSI MS-7D25        | 3         | 0.25%   |
| MSI MS-7C84        | 3         | 0.25%   |
| MSI MS-7C37        | 3         | 0.25%   |
| MSI MS-7B93        | 3         | 0.25%   |
| MSI MS-7B89        | 3         | 0.25%   |
| MSI MS-7B86        | 3         | 0.25%   |
| MSI MS-7B79        | 3         | 0.25%   |
| HUAWEI HVY-WXX9    | 3         | 0.25%   |
| HP ProDesk         | 3         | 0.25%   |
| HP EliteDesk       | 3         | 0.25%   |
| Fujitsu ESPRIMO    | 3         | 0.25%   |
| ASUS M5A97         | 3         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 226       | 18.51%  |
| 2021 | 176       | 14.41%  |
| 2019 | 155       | 12.69%  |
| 2018 | 135       | 11.06%  |
| 2017 | 90        | 7.37%   |
| 2014 | 71        | 5.81%   |
| 2013 | 70        | 5.73%   |
| 2016 | 68        | 5.57%   |
| 2011 | 53        | 4.34%   |
| 2015 | 50        | 4.1%    |
| 2012 | 50        | 4.1%    |
| 2010 | 31        | 2.54%   |
| 2008 | 18        | 1.47%   |
| 2009 | 16        | 1.31%   |
| 2022 | 5         | 0.41%   |
| 2007 | 5         | 0.41%   |
| 2006 | 2         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 721       | 59.05%  |
| Desktop        | 387       | 31.7%   |
| Convertible    | 54        | 4.42%   |
| Mini pc        | 24        | 1.97%   |
| All in one     | 19        | 1.56%   |
| Tablet         | 9         | 0.74%   |
| Server         | 5         | 0.41%   |
| System on chip | 2         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1030      | 83.6%   |
| Enabled  | 202       | 16.4%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1213      | 99.34%  |
| Yes  | 8         | 0.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 324       | 26.43%  |
| 4.01-8.0    | 290       | 23.65%  |
| 8.01-16.0   | 229       | 18.68%  |
| 32.01-64.0  | 179       | 14.6%   |
| 3.01-4.0    | 115       | 9.38%   |
| 64.01-256.0 | 51        | 4.16%   |
| 24.01-32.0  | 19        | 1.55%   |
| 1.01-2.0    | 13        | 1.06%   |
| 2.01-3.0    | 6         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 369       | 27.91%  |
| 4.01-8.0   | 363       | 27.46%  |
| 3.01-4.0   | 276       | 20.88%  |
| 1.01-2.0   | 183       | 13.84%  |
| 8.01-16.0  | 92        | 6.96%   |
| 0.51-1.0   | 16        | 1.21%   |
| 16.01-24.0 | 13        | 0.98%   |
| 24.01-32.0 | 7         | 0.53%   |
| 0.01-0.5   | 2         | 0.15%   |
| 32.01-64.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 697       | 56.53%  |
| 2      | 328       | 26.6%   |
| 3      | 107       | 8.68%   |
| 4      | 39        | 3.16%   |
| 5      | 27        | 2.19%   |
| 6      | 17        | 1.38%   |
| 7      | 8         | 0.65%   |
| 0      | 6         | 0.49%   |
| 8      | 2         | 0.16%   |
| 14     | 1         | 0.08%   |
| 9      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 950       | 77.55%  |
| Yes       | 275       | 22.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 977       | 79.43%  |
| No        | 253       | 20.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 998       | 81.74%  |
| No        | 223       | 18.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 885       | 71.95%  |
| No        | 345       | 28.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 220       | 17.96%  |
| Russia       | 87        | 7.1%    |
| Brazil       | 83        | 6.78%   |
| Germany      | 70        | 5.71%   |
| France       | 50        | 4.08%   |
| Canada       | 49        | 4%      |
| UK           | 48        | 3.92%   |
| Italy        | 44        | 3.59%   |
| Poland       | 34        | 2.78%   |
| Spain        | 33        | 2.69%   |
| India        | 33        | 2.69%   |
| Netherlands  | 32        | 2.61%   |
| Australia    | 31        | 2.53%   |
| Czechia      | 23        | 1.88%   |
| Austria      | 22        | 1.8%    |
| Belgium      | 21        | 1.71%   |
| Sweden       | 20        | 1.63%   |
| Turkey       | 18        | 1.47%   |
| Mexico       | 18        | 1.47%   |
| Ukraine      | 16        | 1.31%   |
| Norway       | 15        | 1.22%   |
| Switzerland  | 14        | 1.14%   |
| Indonesia    | 14        | 1.14%   |
| Romania      | 13        | 1.06%   |
| Hungary      | 12        | 0.98%   |
| Chile        | 11        | 0.9%    |
| Belarus      | 11        | 0.9%    |
| Greece       | 10        | 0.82%   |
| Israel       | 9         | 0.73%   |
| Portugal     | 8         | 0.65%   |
| Colombia     | 8         | 0.65%   |
| Argentina    | 8         | 0.65%   |
| Denmark      | 7         | 0.57%   |
| China        | 7         | 0.57%   |
| South Africa | 6         | 0.49%   |
| Saudi Arabia | 6         | 0.49%   |
| Finland      | 6         | 0.49%   |
| New Zealand  | 5         | 0.41%   |
| Japan        | 5         | 0.41%   |
| Ireland      | 5         | 0.41%   |
| Hong Kong    | 5         | 0.41%   |
| Venezuela    | 4         | 0.33%   |
| Philippines  | 4         | 0.33%   |
| Estonia      | 4         | 0.33%   |
| Croatia      | 4         | 0.33%   |
| Bulgaria     | 4         | 0.33%   |
| Kazakhstan   | 3         | 0.24%   |
| Iran         | 3         | 0.24%   |
| Georgia      | 3         | 0.24%   |
| Cyprus       | 3         | 0.24%   |
| Tunisia      | 2         | 0.16%   |
| Thailand     | 2         | 0.16%   |
| Slovenia     | 2         | 0.16%   |
| Slovakia     | 2         | 0.16%   |
| Serbia       | 2         | 0.16%   |
| Peru         | 2         | 0.16%   |
| Panama       | 2         | 0.16%   |
| Myanmar      | 2         | 0.16%   |
| Malaysia     | 2         | 0.16%   |
| Lithuania    | 2         | 0.16%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 32        | 2.51%   |
| Vienna           | 16        | 1.26%   |
| Sydney           | 15        | 1.18%   |
| Istanbul         | 14        | 1.1%    |
| São Paulo       | 13        | 1.02%   |
| Berlin           | 12        | 0.94%   |
| St Petersburg    | 11        | 0.86%   |
| Warsaw           | 9         | 0.71%   |
| Montreal         | 9         | 0.71%   |
| Madrid           | 9         | 0.71%   |
| Minsk            | 8         | 0.63%   |
| Milan            | 8         | 0.63%   |
| Amsterdam        | 8         | 0.63%   |
| Prague           | 7         | 0.55%   |
| Paris            | 7         | 0.55%   |
| Kyiv             | 7         | 0.55%   |
| Athens           | 7         | 0.55%   |
| Yekaterinburg    | 6         | 0.47%   |
| Rome             | 6         | 0.47%   |
| Jakarta          | 6         | 0.47%   |
| Bucharest        | 6         | 0.47%   |
| Zurich           | 5         | 0.39%   |
| WÃ¶rgl         | 5         | 0.39%   |
| Ufa              | 5         | 0.39%   |
| Seattle          | 5         | 0.39%   |
| Rio de Janeiro   | 5         | 0.39%   |
| Mexico City      | 5         | 0.39%   |
| Los Angeles      | 5         | 0.39%   |
| Krakow           | 5         | 0.39%   |
| Coimbatore       | 5         | 0.39%   |
| Budapest         | 5         | 0.39%   |
| Brno             | 5         | 0.39%   |
| Belo Horizonte   | 5         | 0.39%   |
| Zagreb           | 4         | 0.31%   |
| Vancouver        | 4         | 0.31%   |
| Rotterdam        | 4         | 0.31%   |
| Perth            | 4         | 0.31%   |
| Oslo             | 4         | 0.31%   |
| Nizhniy Novgorod | 4         | 0.31%   |
| Munich           | 4         | 0.31%   |
| Melbourne        | 4         | 0.31%   |
| Lyon             | 4         | 0.31%   |
| Helsinki         | 4         | 0.31%   |
| Hamburg          | 4         | 0.31%   |
| Fortaleza        | 4         | 0.31%   |
| Bengaluru        | 4         | 0.31%   |
| Atlanta          | 4         | 0.31%   |
| Antwerp          | 4         | 0.31%   |
| Ankara           | 4         | 0.31%   |
| Weinsberg        | 3         | 0.24%   |
| Springfield      | 3         | 0.24%   |
| Southampton      | 3         | 0.24%   |
| Santiago         | 3         | 0.24%   |
| Riyadh           | 3         | 0.24%   |
| Raleigh          | 3         | 0.24%   |
| Pennsville       | 3         | 0.24%   |
| Nuremberg        | 3         | 0.24%   |
| New Delhi        | 3         | 0.24%   |
| Mumbai           | 3         | 0.24%   |
| Mangawhai        | 3         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 361       | 557    | 19.59%  |
| WDC                            | 252       | 355    | 13.67%  |
| Seagate                        | 201       | 313    | 10.91%  |
| Sandisk                        | 113       | 138    | 6.13%   |
| Toshiba                        | 104       | 122    | 5.64%   |
| Kingston                       | 102       | 119    | 5.53%   |
| Crucial                        | 77        | 92     | 4.18%   |
| Unknown                        | 73        | 90     | 3.96%   |
| SK Hynix                       | 71        | 85     | 3.85%   |
| Intel                          | 65        | 84     | 3.53%   |
| Micron Technology              | 35        | 41     | 1.9%    |
| A-DATA Technology              | 32        | 39     | 1.74%   |
| Phison                         | 29        | 39     | 1.57%   |
| KIOXIA                         | 29        | 44     | 1.57%   |
| Hitachi                        | 25        | 28     | 1.36%   |
| HGST                           | 19        | 25     | 1.03%   |
| Apple                          | 17        | 19     | 0.92%   |
| SPCC                           | 14        | 17     | 0.76%   |
| Silicon Motion                 | 13        | 13     | 0.71%   |
| Patriot                        | 12        | 15     | 0.65%   |
| Corsair                        | 12        | 13     | 0.65%   |
| XPG                            | 11        | 14     | 0.6%    |
| Transcend                      | 10        | 11     | 0.54%   |
| LITEON                         | 10        | 11     | 0.54%   |
| China                          | 9         | 10     | 0.49%   |
| PNY                            | 7         | 9      | 0.38%   |
| Lexar                          | 7         | 8      | 0.38%   |
| Hewlett-Packard                | 7         | 6      | 0.38%   |
| Unknown                        | 6         | 7      | 0.33%   |
| Realtek Semiconductor          | 5         | 6      | 0.27%   |
| PLEXTOR                        | 5         | 6      | 0.27%   |
| GOODRAM                        | 5         | 5      | 0.27%   |
| UMIS                           | 4         | 7      | 0.22%   |
| Team                           | 4         | 6      | 0.22%   |
| SABRENT                        | 4         | 4      | 0.22%   |
| Mushkin                        | 4         | 5      | 0.22%   |
| Micron/Crucial Technology      | 4         | 5      | 0.22%   |
| KingSpec                       | 4         | 4      | 0.22%   |
| JMicron                        | 4         | 7      | 0.22%   |
| ADATA Technology               | 4         | 4      | 0.22%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.16%   |
| SSK                            | 3         | 3      | 0.16%   |
| LITEONIT                       | 3         | 3      | 0.16%   |
| Apacer                         | 3         | 4      | 0.16%   |
| YMTC                           | 2         | 2      | 0.11%   |
| Verbatim                       | 2         | 2      | 0.11%   |
| Solid State Storage Technology | 2         | 2      | 0.11%   |
| Ramsta                         | 2         | 3      | 0.11%   |
| OCZ                            | 2         | 2      | 0.11%   |
| MAXTOR                         | 2         | 2      | 0.11%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.11%   |
| Lenovo                         | 2         | 2      | 0.11%   |
| LDLC                           | 2         | 3      | 0.11%   |
| Intenso                        | 2         | 5      | 0.11%   |
| HPE                            | 2         | 4      | 0.11%   |
| Gigabyte Technology            | 2         | 3      | 0.11%   |
| FORESEE                        | 2         | 2      | 0.11%   |
| BIWIN                          | 2         | 2      | 0.11%   |
| ASMT                           | 2         | 2      | 0.11%   |
| WDC WDS                        | 1         | 1      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 34        | 1.64%   |
| Samsung NVMe SSD Drive 512GB           | 28        | 1.35%   |
| Samsung SSD 860 EVO 500GB              | 21        | 1.01%   |
| SK Hynix NVMe SSD Drive 512GB          | 19        | 0.92%   |
| Kingston SA400S37480G 480GB SSD        | 19        | 0.92%   |
| Samsung NVMe SSD Drive 1TB             | 18        | 0.87%   |
| Kingston SA400S37240G 240GB SSD        | 18        | 0.87%   |
| Samsung NVMe SSD Drive 256GB           | 17        | 0.82%   |
| Sandisk NVMe SSD Drive 512GB           | 16        | 0.77%   |
| Sandisk NVMe SSD Drive 1TB             | 15        | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB         | 14        | 0.68%   |
| Samsung SSD 850 EVO 250GB              | 14        | 0.68%   |
| Sandisk NVMe SSD Drive 500GB           | 13        | 0.63%   |
| Sandisk NVMe SSD Drive 256GB           | 13        | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB         | 12        | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB           | 12        | 0.58%   |
| Samsung SSD 860 EVO 1TB                | 12        | 0.58%   |
| Crucial CT1000MX500SSD1 1TB            | 12        | 0.58%   |
| Unknown MMC Card  64GB                 | 11        | 0.53%   |
| Unknown MMC Card  32GB                 | 11        | 0.53%   |
| Seagate ST1000LM035-1RK172 1TB         | 11        | 0.53%   |
| Samsung SSD 970 EVO Plus 500GB         | 11        | 0.53%   |
| Samsung SSD 850 EVO 500GB              | 11        | 0.53%   |
| Samsung NVMe SSD Drive 250GB           | 10        | 0.48%   |
| Intel NVMe SSD Drive 512GB             | 10        | 0.48%   |
| Crucial CT500MX500SSD1 500GB           | 10        | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 9         | 0.43%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 9         | 0.43%   |
| Seagate ST500DM002-1BD142 500GB        | 9         | 0.43%   |
| Samsung SSD 860 EVO 250GB              | 9         | 0.43%   |
| Samsung NVMe SSD Drive 2TB             | 9         | 0.43%   |
| HGST HTS721010A9E630 1TB               | 9         | 0.43%   |
| SK Hynix NVMe SSD Drive 256GB          | 8         | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB         | 8         | 0.39%   |
| Seagate ST3500418AS 500GB              | 8         | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB         | 8         | 0.39%   |
| Samsung SSD 870 EVO 500GB              | 8         | 0.39%   |
| Samsung NVMe SSD Drive 1024GB          | 8         | 0.39%   |
| KIOXIA NVMe SSD Drive 512GB            | 8         | 0.39%   |
| KIOXIA NVMe SSD Drive 256GB            | 8         | 0.39%   |
| Kingston SV300S37A120G 120GB SSD       | 8         | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 7         | 0.34%   |
| Toshiba MQ04ABF100 1TB                 | 7         | 0.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 7         | 0.34%   |
| Seagate Expansion 500GB                | 7         | 0.34%   |
| Samsung SSD 970 EVO Plus 2TB           | 7         | 0.34%   |
| Samsung SSD 870 EVO 1TB                | 7         | 0.34%   |
| Kingston SA400S37120G 120GB SSD        | 7         | 0.34%   |
| Crucial CT480BX500SSD1 480GB           | 7         | 0.34%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 6         | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 6         | 0.29%   |
| WDC WD30EFRX-68EUZN0 3TB               | 6         | 0.29%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB   | 6         | 0.29%   |
| Unknown MMC Card  128GB                | 6         | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB         | 6         | 0.29%   |
| Sandisk NVMe SSD Drive 1024GB          | 6         | 0.29%   |
| Samsung MZVLB1T0HBLR-000L7 1TB         | 6         | 0.29%   |
| Phison Sabrent 1TB                     | 6         | 0.29%   |
| Micron NVMe SSD Drive 512GB            | 6         | 0.29%   |
| Kingston SA2000M81000G 1TB             | 6         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 195       | 302    | 40.12%  |
| WDC                 | 162       | 239    | 33.33%  |
| Toshiba             | 58        | 68     | 11.93%  |
| Hitachi             | 25        | 28     | 5.14%   |
| HGST                | 19        | 25     | 3.91%   |
| Samsung Electronics | 10        | 14     | 2.06%   |
| Unknown             | 5         | 5      | 1.03%   |
| SABRENT             | 3         | 3      | 0.62%   |
| MAXTOR              | 2         | 2      | 0.41%   |
| USB 3.0             | 1         | 2      | 0.21%   |
| MaxDigital          | 1         | 1      | 0.21%   |
| LaCie               | 1         | 2      | 0.21%   |
| JMicron             | 1         | 3      | 0.21%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |
| ASMT                | 1         | 1      | 0.21%   |
| Apple               | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 146       | 227    | 24.41%  |
| Kingston            | 75        | 88     | 12.54%  |
| Crucial             | 66        | 79     | 11.04%  |
| SanDisk             | 46        | 58     | 7.69%   |
| WDC                 | 45        | 56     | 7.53%   |
| Intel               | 24        | 28     | 4.01%   |
| A-DATA Technology   | 24        | 30     | 4.01%   |
| Toshiba             | 11        | 13     | 1.84%   |
| SPCC                | 11        | 13     | 1.84%   |
| Patriot             | 11        | 14     | 1.84%   |
| Micron Technology   | 11        | 12     | 1.84%   |
| Apple               | 11        | 11     | 1.84%   |
| China               | 9         | 10     | 1.51%   |
| LITEON              | 8         | 9      | 1.34%   |
| Transcend           | 7         | 8      | 1.17%   |
| SK Hynix            | 7         | 7      | 1.17%   |
| PNY                 | 7         | 9      | 1.17%   |
| Corsair             | 5         | 6      | 0.84%   |
| Unknown             | 4         | 4      | 0.67%   |
| PLEXTOR             | 4         | 5      | 0.67%   |
| Mushkin             | 4         | 5      | 0.67%   |
| Lexar               | 4         | 4      | 0.67%   |
| KingSpec            | 4         | 4      | 0.67%   |
| Hewlett-Packard     | 4         | 4      | 0.67%   |
| GOODRAM             | 4         | 4      | 0.67%   |
| Team                | 3         | 5      | 0.5%    |
| LITEONIT            | 3         | 3      | 0.5%    |
| Apacer              | 3         | 4      | 0.5%    |
| Verbatim            | 2         | 2      | 0.33%   |
| Ramsta              | 2         | 3      | 0.33%   |
| OCZ                 | 2         | 2      | 0.33%   |
| JMicron             | 2         | 2      | 0.33%   |
| Intenso             | 2         | 5      | 0.33%   |
| FORESEE             | 2         | 2      | 0.33%   |
| BIWIN               | 2         | 2      | 0.33%   |
| XPG                 | 1         | 2      | 0.17%   |
| WDC WDS             | 1         | 1      | 0.17%   |
| TO Exter            | 1         | 1      | 0.17%   |
| TCSUNBOW            | 1         | 1      | 0.17%   |
| T-FORCE             | 1         | 1      | 0.17%   |
| SUNEAST             | 1         | 1      | 0.17%   |
| Seagate             | 1         | 2      | 0.17%   |
| SABRENT             | 1         | 1      | 0.17%   |
| OWC                 | 1         | 1      | 0.17%   |
| MX                  | 1         | 1      | 0.17%   |
| LS600               | 1         | 1      | 0.17%   |
| HS-SSD-C100         | 1         | 1      | 0.17%   |
| HPE                 | 1         | 3      | 0.17%   |
| Gigabyte Technology | 1         | 1      | 0.17%   |
| GALAX               | 1         | 1      | 0.17%   |
| Dahua               | 1         | 1      | 0.17%   |
| CT1000P2            | 1         | 1      | 0.17%   |
| CT1000MX            | 1         | 1      | 0.17%   |
| ASMT                | 1         | 1      | 0.17%   |
| AMD                 | 1         | 2      | 0.17%   |
| ADATA SU            | 1         | 1      | 0.17%   |
| 1TB                 | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 635       | 882    | 37.91%  |
| SSD     | 521       | 766    | 31.1%   |
| HDD     | 423       | 697    | 25.25%  |
| MMC     | 62        | 83     | 3.7%    |
| Unknown | 34        | 40     | 2.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 719       | 1415   | 48.38%  |
| NVMe | 635       | 881    | 42.73%  |
| SAS  | 70        | 89     | 4.71%   |
| MMC  | 62        | 83     | 4.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 548       | 784    | 54.47%  |
| 0.51-1.0   | 292       | 418    | 29.03%  |
| 1.01-2.0   | 87        | 119    | 8.65%   |
| 3.01-4.0   | 35        | 51     | 3.48%   |
| 2.01-3.0   | 19        | 43     | 1.89%   |
| 4.01-10.0  | 19        | 35     | 1.89%   |
| 10.01-20.0 | 6         | 13     | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 246       | 19.87%  |
| 251-500        | 224       | 18.09%  |
| 101-250        | 175       | 14.14%  |
| 1001-2000      | 171       | 13.81%  |
| 1-20           | 156       | 12.6%   |
| Unknown        | 86        | 6.95%   |
| More than 3000 | 78        | 6.3%    |
| 51-100         | 44        | 3.55%   |
| 2001-3000      | 42        | 3.39%   |
| 21-50          | 16        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 373       | 29.14%  |
| 21-50          | 203       | 15.86%  |
| 101-250        | 173       | 13.52%  |
| 51-100         | 132       | 10.31%  |
| 251-500        | 121       | 9.45%   |
| 501-1000       | 98        | 7.66%   |
| Unknown        | 86        | 6.72%   |
| 1001-2000      | 53        | 4.14%   |
| More than 3000 | 23        | 1.8%    |
| 2001-3000      | 18        | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 5         | 10     | 6.02%   |
| Seagate ST3500418AS 500GB                           | 3         | 4      | 3.61%   |
| Samsung Electronics SSD 870 EVO 500GB               | 3         | 3      | 3.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 5      | 2.41%   |
| HGST HTS721010A9E630 1TB                            | 2         | 2      | 2.41%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 1.2%    |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1      | 1.2%    |
| WDC WD5000AAKS-00UU3A0 500GB                        | 1         | 1      | 1.2%    |
| WDC WD3200BEVT-24A23T0 320GB                        | 1         | 1      | 1.2%    |
| WDC WD30EZRX-00MMMB0 3TB                            | 1         | 1      | 1.2%    |
| WDC WD2500AAKX-753CA1 250GB                         | 1         | 1      | 1.2%    |
| WDC WD1600BEVT-24A23T0 160GB                        | 1         | 1      | 1.2%    |
| WDC WD15EARS-00S0XB0 1TB                            | 1         | 1      | 1.2%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 1         | 1      | 1.2%    |
| WDC WD10EFRX-68JCSN0 1TB                            | 1         | 1      | 1.2%    |
| WDC WD10EALX-009BA0 1TB                             | 1         | 1      | 1.2%    |
| WDC WD1003FBYX-01Y7B1 1TB                           | 1         | 1      | 1.2%    |
| WDC WD1002FAEX-00Z3A0 1TB                           | 1         | 1      | 1.2%    |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 1.2%    |
| Toshiba MQ01ABD050V 500GB                           | 1         | 1      | 1.2%    |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 1.2%    |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1         | 1      | 1.2%    |
| Team T2535T480G 480GB SSD                           | 1         | 2      | 1.2%    |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 1.2%    |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 1.2%    |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 1.2%    |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 1.2%    |
| Seagate ST500LM000-1EJ162-SSHD 500GB                | 1         | 1      | 1.2%    |
| Seagate ST500DM009-2F110A 500GB                     | 1         | 1      | 1.2%    |
| Seagate ST3500630AS 500GB                           | 1         | 1      | 1.2%    |
| Seagate ST3200822A 200GB                            | 1         | 1      | 1.2%    |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 1.2%    |
| Seagate ST31000524AS 1TB                            | 1         | 1      | 1.2%    |
| Seagate ST31000340NS 1TB                            | 1         | 3      | 1.2%    |
| Seagate ST3000DM001-1ER166 3TB                      | 1         | 1      | 1.2%    |
| Seagate ST3000DM001-1CH166 3TB                      | 1         | 3      | 1.2%    |
| Seagate ST2000DM001-1CH164 2TB                      | 1         | 1      | 1.2%    |
| Seagate ST2000DL003-9VT166 2TB                      | 1         | 1      | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 1.2%    |
| Seagate ST1000DM003-1ER162 1TB                      | 1         | 1      | 1.2%    |
| SanDisk SD6PP4M-256G-1006 256GB SSD                 | 1         | 1      | 1.2%    |
| Samsung Electronics SSD 970 EVO 250GB               | 1         | 1      | 1.2%    |
| Samsung Electronics MZNLH256HAJD-000H1 256GB SSD    | 1         | 1      | 1.2%    |
| Samsung Electronics HD501LJ 500GB                   | 1         | 4      | 1.2%    |
| Samsung Electronics HD103UJ 1TB                     | 1         | 1      | 1.2%    |
| PNY CS1311 960GB SSD                                | 1         | 1      | 1.2%    |
| PLEXTOR PX-256M8PeG 256GB                           | 1         | 1      | 1.2%    |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 2      | 1.2%    |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 1.2%    |
| MAXTOR 6Y080M0 81GB                                 | 1         | 1      | 1.2%    |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 1.2%    |
| LITEON CV3-CE256 256GB SSD                          | 1         | 1      | 1.2%    |
| Kingston SV300S37A240G 240GB SSD                    | 1         | 1      | 1.2%    |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 1.2%    |
| Intel SSDSC2CT120A3 120GB                           | 1         | 2      | 1.2%    |
| Intel SSDSC2BF180A5L 180GB                          | 1         | 1      | 1.2%    |
| Intel SSDSA2M080G2GC 80GB                           | 1         | 1      | 1.2%    |
| Intel SSDPEKKW256G7 256GB                           | 1         | 1      | 1.2%    |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 1.2%    |
| Hitachi HTS545025B9SA02 250GB                       | 1         | 1      | 1.2%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 39     | 30.49%  |
| WDC                 | 13        | 13     | 15.85%  |
| Samsung Electronics | 7         | 10     | 8.54%   |
| Crucial             | 6         | 7      | 7.32%   |
| Hitachi             | 5         | 5      | 6.1%    |
| Toshiba             | 4         | 4      | 4.88%   |
| Intel               | 4         | 5      | 4.88%   |
| HGST                | 3         | 3      | 3.66%   |
| Micron Technology   | 2         | 3      | 2.44%   |
| LITEON              | 2         | 2      | 2.44%   |
| Kingston            | 2         | 2      | 2.44%   |
| A-DATA Technology   | 2         | 2      | 2.44%   |
| Team                | 1         | 2      | 1.22%   |
| SK Hynix            | 1         | 1      | 1.22%   |
| SanDisk             | 1         | 1      | 1.22%   |
| PNY                 | 1         | 1      | 1.22%   |
| PLEXTOR             | 1         | 1      | 1.22%   |
| MAXTOR              | 1         | 1      | 1.22%   |
| Corsair             | 1         | 1      | 1.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 39     | 49.02%  |
| WDC                 | 12        | 12     | 23.53%  |
| Hitachi             | 5         | 5      | 9.8%    |
| Toshiba             | 3         | 3      | 5.88%   |
| HGST                | 3         | 3      | 5.88%   |
| Samsung Electronics | 2         | 5      | 3.92%   |
| MAXTOR              | 1         | 1      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 68     | 60.76%  |
| SSD  | 26        | 30     | 32.91%  |
| NVMe | 5         | 5      | 6.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 695       | 1367   | 51.56%  |
| Works    | 574       | 997    | 42.58%  |
| Malfunc  | 78        | 103    | 5.79%   |
| Failed   | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 678       | 40.65%  |
| AMD                              | 270       | 16.19%  |
| Samsung Electronics              | 236       | 14.15%  |
| Sandisk                          | 113       | 6.77%   |
| SK Hynix                         | 62        | 3.72%   |
| Toshiba America Info Systems     | 38        | 2.28%   |
| Phison Electronics               | 35        | 2.1%    |
| Kingston Technology Company      | 29        | 1.74%   |
| KIOXIA                           | 27        | 1.62%   |
| Micron Technology                | 25        | 1.5%    |
| Silicon Motion                   | 19        | 1.14%   |
| ASMedia Technology               | 19        | 1.14%   |
| ADATA Technology                 | 19        | 1.14%   |
| Marvell Technology Group         | 17        | 1.02%   |
| Micron/Crucial Technology        | 15        | 0.9%    |
| Nvidia                           | 13        | 0.78%   |
| JMicron Technology               | 10        | 0.6%    |
| Union Memory (Shenzhen)          | 6         | 0.36%   |
| Realtek Semiconductor            | 6         | 0.36%   |
| Apple                            | 4         | 0.24%   |
| Solid State Storage Technology   | 3         | 0.18%   |
| Lite-On Technology               | 3         | 0.18%   |
| Yangtze Memory Technologies      | 2         | 0.12%   |
| Silicon Image                    | 2         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.12%   |
| LSI Logic / Symbios Logic        | 2         | 0.12%   |
| Lenovo                           | 2         | 0.12%   |
| Broadcom / LSI                   | 2         | 0.12%   |
| VIA Technologies                 | 1         | 0.06%   |
| Unknown                          | 1         | 0.06%   |
| ULi Electronics                  | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| Seagate Technology               | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Dell                             | 1         | 0.06%   |
| Beijing Starblaze Technology     | 1         | 0.06%   |
| Adaptec                          | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 205       | 11.16%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 131       | 7.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 88        | 4.79%   |
| Samsung NVMe SSD Controller 980                                                  | 50        | 2.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 46        | 2.5%    |
| AMD 400 Series Chipset SATA Controller                                           | 46        | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 43        | 2.34%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 41        | 2.23%   |
| Intel Volume Management Device NVMe RAID Controller                              | 40        | 2.18%   |
| AMD 500 Series Chipset SATA Controller                                           | 32        | 1.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 30        | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 29        | 1.58%   |
| KIOXIA Non-Volatile memory controller                                            | 27        | 1.47%   |
| Micron Non-Volatile memory controller                                            | 25        | 1.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 25        | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 25        | 1.36%   |
| SK Hynix Gold P31 SSD                                                            | 24        | 1.31%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 24        | 1.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 24        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 24        | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 24        | 1.31%   |
| Intel Comet Lake SATA AHCI Controller                                            | 22        | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 22        | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 21        | 1.14%   |
| Phison E12 NVMe Controller                                                       | 20        | 1.09%   |
| Intel SSD 660P Series                                                            | 20        | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 20        | 1.09%   |
| Sandisk Non-Volatile memory controller                                           | 18        | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 17        | 0.93%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 17        | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 16        | 0.87%   |
| Intel SATA Controller [RAID mode]                                                | 16        | 0.87%   |
| SK Hynix Non-Volatile memory controller                                          | 15        | 0.82%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 14        | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 14        | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 13        | 0.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 13        | 0.71%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 13        | 0.71%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 12        | 0.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 11        | 0.6%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 11        | 0.6%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 11        | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 11        | 0.6%    |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 10        | 0.54%   |
| Kingston Company A2000 NVMe SSD                                                  | 10        | 0.54%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 10        | 0.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 0.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 0.54%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 9         | 0.49%   |
| SK Hynix BC511                                                                   | 9         | 0.49%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 9         | 0.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 0.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 9         | 0.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 0.49%   |
| AMD FCH IDE Controller                                                           | 9         | 0.49%   |
| AMD 300 Series Chipset SATA Controller                                           | 9         | 0.49%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 8         | 0.44%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 8         | 0.44%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 8         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 848       | 51.55%  |
| NVMe | 633       | 38.48%  |
| RAID | 92        | 5.59%   |
| IDE  | 63        | 3.83%   |
| SAS  | 8         | 0.49%   |
| SCSI | 1         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 859       | 70.35%  |
| AMD    | 360       | 29.48%  |
| ARM    | 2         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 32        | 2.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 31        | 2.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 20        | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 14        | 1.15%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 14        | 1.15%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 13        | 1.06%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 1.06%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 12        | 0.98%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.9%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 11        | 0.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 0.82%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 9         | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.74%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 9         | 0.74%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 9         | 0.74%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 9         | 0.74%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 9         | 0.74%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 9         | 0.74%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 8         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.66%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 0.66%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 8         | 0.66%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 8         | 0.66%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 8         | 0.66%   |
| AMD Ryzen 5 3600 6-Core Processor             | 8         | 0.66%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 7         | 0.57%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 7         | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 0.57%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 7         | 0.57%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 7         | 0.57%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 0.57%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 7         | 0.57%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 6         | 0.49%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.49%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.49%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 6         | 0.49%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 0.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 0.49%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.49%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 6         | 0.49%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 6         | 0.49%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 6         | 0.49%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 5         | 0.41%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.41%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.41%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 5         | 0.41%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.41%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.41%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 282       | 23.1%   |
| Intel Core i5           | 245       | 20.07%  |
| Other                   | 112       | 9.17%   |
| AMD Ryzen 5             | 108       | 8.85%   |
| AMD Ryzen 7             | 103       | 8.44%   |
| Intel Core i3           | 78        | 6.39%   |
| AMD Ryzen 9             | 41        | 3.36%   |
| Intel Xeon              | 24        | 1.97%   |
| Intel Core 2 Duo        | 24        | 1.97%   |
| Intel Celeron           | 24        | 1.97%   |
| Intel Core i9           | 21        | 1.72%   |
| AMD Ryzen 3             | 17        | 1.39%   |
| Intel Pentium           | 16        | 1.31%   |
| Intel Atom              | 16        | 1.31%   |
| AMD Ryzen 7 PRO         | 8         | 0.66%   |
| AMD FX                  | 8         | 0.66%   |
| AMD A4                  | 8         | 0.66%   |
| AMD A10                 | 8         | 0.66%   |
| AMD A6                  | 7         | 0.57%   |
| Intel Pentium Silver    | 6         | 0.49%   |
| AMD Ryzen Threadripper  | 6         | 0.49%   |
| AMD Ryzen 5 PRO         | 6         | 0.49%   |
| AMD Athlon              | 6         | 0.49%   |
| AMD A8                  | 6         | 0.49%   |
| Intel Pentium Dual-Core | 4         | 0.33%   |
| Intel Core 2 Quad       | 3         | 0.25%   |
| AMD Phenom              | 3         | 0.25%   |
| AMD Athlon X4           | 3         | 0.25%   |
| Intel Pentium Dual      | 2         | 0.16%   |
| Intel Core m3           | 2         | 0.16%   |
| AMD Phenom II X4        | 2         | 0.16%   |
| AMD Phenom II X2        | 2         | 0.16%   |
| AMD E                   | 2         | 0.16%   |
| AMD Athlon II X2        | 2         | 0.16%   |
| AMD Athlon 64 X2        | 2         | 0.16%   |
| Intel Pentium Gold      | 1         | 0.08%   |
| Intel Genuine           | 1         | 0.08%   |
| Intel Core m7           | 1         | 0.08%   |
| Intel Core 2 Extreme    | 1         | 0.08%   |
| AMD Ryzen Embedded      | 1         | 0.08%   |
| AMD Ryzen 3 PRO         | 1         | 0.08%   |
| AMD PRO A10             | 1         | 0.08%   |
| AMD Phenom II X6        | 1         | 0.08%   |
| AMD Opteron             | 1         | 0.08%   |
| AMD E2                  | 1         | 0.08%   |
| AMD E1                  | 1         | 0.08%   |
| AMD C-60                | 1         | 0.08%   |
| AMD Athlon X2           | 1         | 0.08%   |
| AMD Athlon II           | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 499       | 40.87%  |
| 2       | 336       | 27.52%  |
| 6       | 168       | 13.76%  |
| 8       | 152       | 12.45%  |
| 12      | 21        | 1.72%   |
| 16      | 16        | 1.31%   |
| 10      | 9         | 0.74%   |
| 1       | 8         | 0.66%   |
| 24      | 4         | 0.33%   |
| 3       | 4         | 0.33%   |
| 40      | 1         | 0.08%   |
| 32      | 1         | 0.08%   |
| 14      | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1216      | 99.59%  |
| 2      | 4         | 0.33%   |
| 4      | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 957       | 78.31%  |
| 1       | 264       | 21.6%   |
| Unknown | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1220      | 99.92%  |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 82        | 6.66%   |
| Unknown    | 71        | 5.77%   |
| 0x806ec    | 59        | 4.79%   |
| 0x306a9    | 58        | 4.71%   |
| 0x306c3    | 57        | 4.63%   |
| 0x206a7    | 50        | 4.06%   |
| 0x806ea    | 47        | 3.82%   |
| 0x806e9    | 43        | 3.49%   |
| 0x906ea    | 42        | 3.41%   |
| 0x406e3    | 35        | 2.84%   |
| 0x0a50000c | 33        | 2.68%   |
| 0x08600106 | 32        | 2.6%    |
| 0x08701021 | 31        | 2.52%   |
| 0x40651    | 29        | 2.36%   |
| 0xa0652    | 28        | 2.27%   |
| 0x506e3    | 27        | 2.19%   |
| 0x906ed    | 23        | 1.87%   |
| 0x906e9    | 23        | 1.87%   |
| 0x08108109 | 23        | 1.87%   |
| 0x306d4    | 20        | 1.62%   |
| 0x1067a    | 20        | 1.62%   |
| 0x08608103 | 17        | 1.38%   |
| 0x08600104 | 17        | 1.38%   |
| 0x706e5    | 15        | 1.22%   |
| 0x0a201016 | 15        | 1.22%   |
| 0x0800820d | 14        | 1.14%   |
| 0x0a201009 | 13        | 1.06%   |
| 0x08108102 | 12        | 0.97%   |
| 0x06001119 | 12        | 0.97%   |
| 0x706a8    | 10        | 0.81%   |
| 0x506c9    | 10        | 0.81%   |
| 0x20655    | 10        | 0.81%   |
| 0x08001138 | 10        | 0.81%   |
| 0x406c4    | 9         | 0.73%   |
| 0x10676    | 9         | 0.73%   |
| 0x0810100b | 9         | 0.73%   |
| 0xa0653    | 8         | 0.65%   |
| 0x90672    | 8         | 0.65%   |
| 0x806eb    | 8         | 0.65%   |
| 0x30678    | 8         | 0.65%   |
| 0x08701013 | 8         | 0.65%   |
| 0xa0655    | 7         | 0.57%   |
| 0x08608102 | 7         | 0.57%   |
| 0x0800820b | 7         | 0.57%   |
| 0x906ec    | 6         | 0.49%   |
| 0x306f2    | 6         | 0.49%   |
| 0x08600103 | 6         | 0.49%   |
| 0x08101016 | 6         | 0.49%   |
| 0x806d1    | 5         | 0.41%   |
| 0x08008206 | 5         | 0.41%   |
| 0x08001137 | 5         | 0.41%   |
| 0x07030105 | 5         | 0.41%   |
| 0x06003106 | 5         | 0.41%   |
| 0xa0671    | 4         | 0.32%   |
| 0x40661    | 4         | 0.32%   |
| 0x206d7    | 4         | 0.32%   |
| 0x08600102 | 4         | 0.32%   |
| 0x0700010b | 4         | 0.32%   |
| 0x0600611a | 4         | 0.32%   |
| 0xa0660    | 3         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 265       | 21.7%   |
| Zen 2            | 103       | 8.44%   |
| Haswell          | 100       | 8.19%   |
| TigerLake        | 87        | 7.13%   |
| Zen 3            | 71        | 5.81%   |
| Skylake          | 70        | 5.73%   |
| IvyBridge        | 65        | 5.32%   |
| Zen+             | 64        | 5.24%   |
| SandyBridge      | 59        | 4.83%   |
| CometLake        | 49        | 4.01%   |
| Zen              | 33        | 2.7%    |
| Unknown          | 31        | 2.54%   |
| Penryn           | 30        | 2.46%   |
| IceLake          | 24        | 1.97%   |
| Silvermont       | 21        | 1.72%   |
| Broadwell        | 21        | 1.72%   |
| Piledriver       | 18        | 1.47%   |
| Westmere         | 17        | 1.39%   |
| Goldmont plus    | 13        | 1.06%   |
| K10              | 11        | 0.9%    |
| Goldmont         | 11        | 0.9%    |
| Alderlake Hybrid | 9         | 0.74%   |
| Puma             | 7         | 0.57%   |
| Core             | 7         | 0.57%   |
| Steamroller      | 6         | 0.49%   |
| Excavator        | 6         | 0.49%   |
| Jaguar           | 5         | 0.41%   |
| Nehalem          | 4         | 0.33%   |
| K10 Llano        | 3         | 0.25%   |
| Bobcat           | 3         | 0.25%   |
| Tremont          | 2         | 0.16%   |
| K8 Hammer        | 2         | 0.16%   |
| Bulldozer        | 2         | 0.16%   |
| Bonnell          | 2         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 710       | 48.17%  |
| Nvidia                           | 394       | 26.73%  |
| AMD                              | 365       | 24.76%  |
| Matrox Electronics Systems       | 2         | 0.14%   |
| ASPEED Technology                | 2         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 79        | 5.27%   |
| AMD Renoir                                                                               | 59        | 3.94%   |
| Intel UHD Graphics 620                                                                   | 48        | 3.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 40        | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 38        | 2.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 2.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 37        | 2.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 36        | 2.4%    |
| AMD Cezanne                                                                              | 35        | 2.33%   |
| Intel HD Graphics 620                                                                    | 34        | 2.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 34        | 2.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 31        | 2.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 2.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 2%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 29        | 1.93%   |
| Intel HD Graphics 530                                                                    | 25        | 1.67%   |
| AMD Lucienne                                                                             | 24        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 19        | 1.27%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 17        | 1.13%   |
| Intel HD Graphics 630                                                                    | 17        | 1.13%   |
| Intel HD Graphics 5500                                                                   | 17        | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 17        | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.07%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 16        | 1.07%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 1%      |
| Nvidia GK208B [GeForce GT 710]                                                           | 12        | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10        | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 9         | 0.6%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 9         | 0.6%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.6%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 9         | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.6%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 9         | 0.6%    |
| Nvidia TU117M                                                                            | 8         | 0.53%   |
| Nvidia GP108M [GeForce MX250]                                                            | 8         | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 0.53%   |
| Intel HD Graphics 500                                                                    | 8         | 0.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 0.53%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.53%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 8         | 0.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.47%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 7         | 0.47%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 7         | 0.47%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 7         | 0.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 0.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 0.47%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 7         | 0.47%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 7         | 0.47%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 6         | 0.4%    |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.4%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.4%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 6         | 0.4%    |
| Intel Tiger Lake UHD Graphics                                                            | 6         | 0.4%    |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.4%    |
| Intel HD Graphics 615                                                                    | 6         | 0.4%    |
| Intel AlderLake-S GT1                                                                    | 6         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 483       | 39.53%  |
| 1 x AMD            | 294       | 24.06%  |
| 1 x Nvidia         | 187       | 15.3%   |
| Intel + Nvidia     | 177       | 14.48%  |
| AMD + Nvidia       | 27        | 2.21%   |
| Intel + AMD        | 22        | 1.8%    |
| 2 x AMD            | 20        | 1.64%   |
| Other              | 4         | 0.33%   |
| 1 x ASPEED         | 2         | 0.16%   |
| 2 x Nvidia         | 1         | 0.08%   |
| 1 x SiS            | 1         | 0.08%   |
| Nvidia + Matrox    | 1         | 0.08%   |
| 1 x Matrox         | 1         | 0.08%   |
| Intel + 2 x Nvidia | 1         | 0.08%   |
| Intel + 2 x AMD    | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1003      | 81.48%  |
| Proprietary | 212       | 17.22%  |
| Unknown     | 16        | 1.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 683       | 55.39%  |
| 1.01-2.0   | 144       | 11.68%  |
| 0.01-0.5   | 143       | 11.6%   |
| 3.01-4.0   | 70        | 5.68%   |
| 0.51-1.0   | 69        | 5.6%    |
| 7.01-8.0   | 68        | 5.52%   |
| 5.01-6.0   | 25        | 2.03%   |
| 8.01-16.0  | 25        | 2.03%   |
| 2.01-3.0   | 6         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 158       | 10.94%  |
| Samsung Electronics     | 150       | 10.39%  |
| Chimei Innolux          | 147       | 10.18%  |
| BOE                     | 142       | 9.83%   |
| LG Display              | 123       | 8.52%   |
| Dell                    | 97        | 6.72%   |
| Goldstar                | 79        | 5.47%   |
| Acer                    | 54        | 3.74%   |
| Sharp                   | 50        | 3.46%   |
| AOC                     | 42        | 2.91%   |
| Hewlett-Packard         | 40        | 2.77%   |
| Lenovo                  | 37        | 2.56%   |
| Apple                   | 37        | 2.56%   |
| Philips                 | 34        | 2.35%   |
| BenQ                    | 33        | 2.29%   |
| Ancor Communications    | 26        | 1.8%    |
| ViewSonic               | 19        | 1.32%   |
| Iiyama                  | 17        | 1.18%   |
| InfoVision              | 16        | 1.11%   |
| ASUSTek Computer        | 16        | 1.11%   |
| CSO                     | 14        | 0.97%   |
| PANDA                   | 13        | 0.9%    |
| Chi Mei Optoelectronics | 9         | 0.62%   |
| Eizo                    | 8         | 0.55%   |
| HannStar                | 6         | 0.42%   |
| TMX                     | 5         | 0.35%   |
| Sony                    | 5         | 0.35%   |
| Vizio                   | 4         | 0.28%   |
| Unknown                 | 4         | 0.28%   |
| Panasonic               | 4         | 0.28%   |
| MSI                     | 4         | 0.28%   |
| InnoLux Display         | 3         | 0.21%   |
| Gigabyte Technology     | 3         | 0.21%   |
| Fujitsu Siemens         | 3         | 0.21%   |
| ___                     | 2         | 0.14%   |
| Unknown (XXX)           | 2         | 0.14%   |
| Mi                      | 2         | 0.14%   |
| JRY                     | 2         | 0.14%   |
| Arnos Instruments       | 2         | 0.14%   |
| YUK                     | 1         | 0.07%   |
| Westinghouse            | 1         | 0.07%   |
| Valve                   | 1         | 0.07%   |
| Toshiba                 | 1         | 0.07%   |
| TIANMA XM               | 1         | 0.07%   |
| TCT                     | 1         | 0.07%   |
| TCL                     | 1         | 0.07%   |
| SHX                     | 1         | 0.07%   |
| Sceptre Tech            | 1         | 0.07%   |
| PRISM+                  | 1         | 0.07%   |
| Plain Tree Systems      | 1         | 0.07%   |
| Pixio                   | 1         | 0.07%   |
| Packard Bell            | 1         | 0.07%   |
| ONN                     | 1         | 0.07%   |
| NEC Computers           | 1         | 0.07%   |
| LG Electronics          | 1         | 0.07%   |
| Kogan                   | 1         | 0.07%   |
| JDI                     | 1         | 0.07%   |
| Insignia                | 1         | 0.07%   |
| HUAWEI                  | 1         | 0.07%   |
| HKC                     | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.94%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 9         | 0.6%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 0.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 7         | 0.47%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 7         | 0.47%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.4%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 5         | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 5         | 0.34%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.34%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 5         | 0.34%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 5         | 0.34%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 5         | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 5         | 0.34%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 4         | 0.27%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 4         | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 4         | 0.27%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                        | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 4         | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.27%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 4         | 0.27%   |
| BOE LCD Monitor BOE0853 1920x1080 344x194mm 15.5-inch                    | 4         | 0.27%   |
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                        | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 4         | 0.27%   |
| AOC Q27G2G4 AOC2702 2560x1440 597x336mm 27.0-inch                        | 4         | 0.27%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                         | 4         | 0.27%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 4         | 0.27%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 3         | 0.2%    |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.2%    |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 3         | 0.2%    |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch        | 3         | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 3         | 0.2%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch        | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 3         | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.2%    |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch             | 3         | 0.2%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch             | 3         | 0.2%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 3         | 0.2%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.2%    |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch             | 3         | 0.2%    |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch                | 3         | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 3         | 0.2%    |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch              | 3         | 0.2%    |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                        | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 3         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 690       | 50.74%  |
| 1366x768 (WXGA)    | 162       | 11.91%  |
| 3840x2160 (4K)     | 116       | 8.53%   |
| 2560x1440 (QHD)    | 116       | 8.53%   |
| 1920x1200 (WUXGA)  | 41        | 3.01%   |
| 1600x900 (HD+)     | 34        | 2.5%    |
| 1440x900 (WXGA+)   | 25        | 1.84%   |
| 1680x1050 (WSXGA+) | 23        | 1.69%   |
| 1280x1024 (SXGA)   | 21        | 1.54%   |
| 3440x1440          | 20        | 1.47%   |
| 2560x1600          | 13        | 0.96%   |
| 2560x1080          | 13        | 0.96%   |
| 2880x1800          | 12        | 0.88%   |
| 1280x800 (WXGA)    | 12        | 0.88%   |
| 2160x1440          | 7         | 0.51%   |
| 3840x2400          | 6         | 0.44%   |
| 2256x1504          | 5         | 0.37%   |
| 3840x1080          | 4         | 0.29%   |
| 1360x768           | 4         | 0.29%   |
| Unknown            | 4         | 0.29%   |
| 2736x1824          | 3         | 0.22%   |
| 3840x1600          | 2         | 0.15%   |
| 3200x2000          | 2         | 0.15%   |
| 3200x1800 (QHD+)   | 2         | 0.15%   |
| 3072x1920          | 2         | 0.15%   |
| 3000x2000          | 2         | 0.15%   |
| 2880x1920          | 2         | 0.15%   |
| 2240x1400          | 2         | 0.15%   |
| 2160x1350          | 2         | 0.15%   |
| 1600x1200          | 2         | 0.15%   |
| 1280x720 (HD)      | 2         | 0.15%   |
| 6784x2160          | 1         | 0.07%   |
| 4480x1080          | 1         | 0.07%   |
| 3840x2560          | 1         | 0.07%   |
| 2400x1600          | 1         | 0.07%   |
| 1920x540           | 1         | 0.07%   |
| 1800x1200          | 1         | 0.07%   |
| 1280x960           | 1         | 0.07%   |
| 1024x768 (XGA)     | 1         | 0.07%   |
| 1024x600           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 325       | 22.31%  |
| 13      | 200       | 13.73%  |
| 27      | 159       | 10.91%  |
| 14      | 142       | 9.75%   |
| 24      | 126       | 8.65%   |
| 21      | 92        | 6.31%   |
| 23      | 84        | 5.77%   |
| 17      | 46        | 3.16%   |
| 31      | 32        | 2.2%    |
| 34      | 30        | 2.06%   |
| 12      | 29        | 1.99%   |
| 19      | 24        | 1.65%   |
| 18      | 20        | 1.37%   |
| 22      | 18        | 1.24%   |
| 20      | 16        | 1.1%    |
| 16      | 13        | 0.89%   |
| 11      | 13        | 0.89%   |
| 84      | 10        | 0.69%   |
| Unknown | 9         | 0.62%   |
| 54      | 6         | 0.41%   |
| 25      | 6         | 0.41%   |
| 72      | 5         | 0.34%   |
| 42      | 5         | 0.34%   |
| 40      | 5         | 0.34%   |
| 26      | 5         | 0.34%   |
| 28      | 4         | 0.27%   |
| 10      | 4         | 0.27%   |
| 49      | 3         | 0.21%   |
| 48      | 3         | 0.21%   |
| 37      | 3         | 0.21%   |
| 35      | 3         | 0.21%   |
| 32      | 3         | 0.21%   |
| 29      | 3         | 0.21%   |
| 74      | 2         | 0.14%   |
| 65      | 2         | 0.14%   |
| 47      | 2         | 0.14%   |
| 55      | 1         | 0.07%   |
| 52      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 33      | 1         | 0.07%   |
| 30      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 575       | 40.18%  |
| 501-600     | 338       | 23.62%  |
| 401-500     | 152       | 10.62%  |
| 201-300     | 152       | 10.62%  |
| 351-400     | 61        | 4.26%   |
| 601-700     | 58        | 4.05%   |
| 701-800     | 33        | 2.31%   |
| 1001-1500   | 18        | 1.26%   |
| 1501-2000   | 17        | 1.19%   |
| 801-900     | 12        | 0.84%   |
| Unknown     | 9         | 0.63%   |
| 901-1000    | 6         | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1010      | 80.35%  |
| 16/10   | 150       | 11.93%  |
| 21/9    | 35        | 2.78%   |
| 3/2     | 23        | 1.83%   |
| 5/4     | 22        | 1.75%   |
| Unknown | 6         | 0.48%   |
| 4/3     | 5         | 0.4%    |
| 32/9    | 4         | 0.32%   |
| 6/5     | 2         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 329       | 22.72%  |
| 81-90          | 255       | 17.61%  |
| 201-250        | 248       | 17.13%  |
| 301-350        | 163       | 11.26%  |
| 71-80          | 92        | 6.35%   |
| 351-500        | 75        | 5.18%   |
| 151-200        | 69        | 4.77%   |
| 251-300        | 46        | 3.18%   |
| 121-130        | 37        | 2.56%   |
| More than 1000 | 28        | 1.93%   |
| 61-70          | 25        | 1.73%   |
| 141-150        | 24        | 1.66%   |
| 501-1000       | 21        | 1.45%   |
| 51-60          | 13        | 0.9%    |
| Unknown        | 9         | 0.62%   |
| 111-120        | 8         | 0.55%   |
| 41-50          | 4         | 0.28%   |
| 131-140        | 2         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 464       | 33.36%  |
| 51-100        | 394       | 28.32%  |
| 101-120       | 312       | 22.43%  |
| 161-240       | 151       | 10.86%  |
| More than 240 | 46        | 3.31%   |
| 1-50          | 15        | 1.08%   |
| Unknown       | 9         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 917       | 74.19%  |
| 2     | 254       | 20.55%  |
| 0     | 34        | 2.75%   |
| 3     | 30        | 2.43%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 699       | 38.73%  |
| Realtek Semiconductor             | 624       | 34.57%  |
| Qualcomm Atheros                  | 157       | 8.7%    |
| Broadcom                          | 75        | 4.16%   |
| MEDIATEK                          | 29        | 1.61%   |
| TP-Link                           | 26        | 1.44%   |
| Ralink Technology                 | 17        | 0.94%   |
| Lenovo                            | 15        | 0.83%   |
| Marvell Technology Group          | 13        | 0.72%   |
| Broadcom Limited                  | 13        | 0.72%   |
| Ralink                            | 12        | 0.66%   |
| Nvidia                            | 10        | 0.55%   |
| Xiaomi                            | 7         | 0.39%   |
| Sierra Wireless                   | 7         | 0.39%   |
| DisplayLink                       | 7         | 0.39%   |
| ASIX Electronics                  | 7         | 0.39%   |
| Qualcomm                          | 6         | 0.33%   |
| Dell                              | 6         | 0.33%   |
| Aquantia                          | 6         | 0.33%   |
| D-Link                            | 5         | 0.28%   |
| ASUSTek Computer                  | 5         | 0.28%   |
| NetGear                           | 4         | 0.22%   |
| Linksys                           | 4         | 0.22%   |
| Google                            | 4         | 0.22%   |
| Samsung Electronics               | 3         | 0.17%   |
| Microsoft                         | 3         | 0.17%   |
| Huawei Technologies               | 3         | 0.17%   |
| Belkin Components                 | 3         | 0.17%   |
| Wilocity                          | 2         | 0.11%   |
| Qualcomm Atheros Communications   | 2         | 0.11%   |
| OPPO Electronics                  | 2         | 0.11%   |
| MosChip Semiconductor             | 2         | 0.11%   |
| ICS Advent                        | 2         | 0.11%   |
| HMD Global                        | 2         | 0.11%   |
| Hewlett-Packard                   | 2         | 0.11%   |
| FIBOCOM                           | 2         | 0.11%   |
| Ericsson Business Mobile Networks | 2         | 0.11%   |
| Edimax Technology                 | 2         | 0.11%   |
| Cypress Semiconductor             | 2         | 0.11%   |
| Apple                             | 2         | 0.11%   |
| Xilinx                            | 1         | 0.06%   |
| Winbond Electronics               | 1         | 0.06%   |
| Unknown                           | 1         | 0.06%   |
| U-Blox                            | 1         | 0.06%   |
| Spreadtrum Communications         | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.06%   |
| Shenzhen Goodix Technology        | 1         | 0.06%   |
| OpenMoko                          | 1         | 0.06%   |
| NetXen Incorporated               | 1         | 0.06%   |
| Mellanox Technologies             | 1         | 0.06%   |
| AVM                               | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 407       | 18.9%   |
| Intel Wi-Fi 6 AX200                                               | 123       | 5.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 67        | 3.11%   |
| Intel Wi-Fi 6 AX201                                               | 67        | 3.11%   |
| Intel Wireless 8265 / 8275                                        | 53        | 2.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 2.18%   |
| Intel I211 Gigabit Network Connection                             | 42        | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 38        | 1.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 35        | 1.63%   |
| Intel Wireless 8260                                               | 35        | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 32        | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 30        | 1.39%   |
| Intel Wireless 7260                                               | 27        | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 27        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 27        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 26        | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 24        | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 22        | 1.02%   |
| Intel Wireless 7265                                               | 22        | 1.02%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 1.02%   |
| Intel Wireless-AC 9260                                            | 21        | 0.98%   |
| Intel Wireless 3165                                               | 20        | 0.93%   |
| Intel Ethernet Controller I225-V                                  | 20        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                              | 19        | 0.88%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 18        | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 17        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 17        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15        | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 0.7%    |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 13        | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 12        | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 12        | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 11        | 0.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 11        | 0.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 11        | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 0.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 0.46%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 0.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 9         | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 8         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.37%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 8         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 7         | 0.33%   |
| Realtek 802.11ac NIC                                              | 7         | 0.33%   |
| Ralink RT5370 Wireless Adapter                                    | 7         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.33%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.33%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.33%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.33%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 589       | 55.62%  |
| Realtek Semiconductor           | 140       | 13.22%  |
| Qualcomm Atheros                | 130       | 12.28%  |
| Broadcom                        | 58        | 5.48%   |
| MEDIATEK                        | 28        | 2.64%   |
| TP-Link                         | 24        | 2.27%   |
| Ralink Technology               | 17        | 1.61%   |
| Ralink                          | 12        | 1.13%   |
| Broadcom Limited                | 11        | 1.04%   |
| Sierra Wireless                 | 7         | 0.66%   |
| Qualcomm                        | 5         | 0.47%   |
| NetGear                         | 4         | 0.38%   |
| Dell                            | 4         | 0.38%   |
| D-Link                          | 4         | 0.38%   |
| ASUSTek Computer                | 4         | 0.38%   |
| Microsoft                       | 3         | 0.28%   |
| Marvell Technology Group        | 3         | 0.28%   |
| Linksys                         | 3         | 0.28%   |
| Belkin Components               | 3         | 0.28%   |
| Wilocity                        | 2         | 0.19%   |
| Qualcomm Atheros Communications | 2         | 0.19%   |
| FIBOCOM                         | 2         | 0.19%   |
| Edimax Technology               | 2         | 0.19%   |
| Hewlett-Packard                 | 1         | 0.09%   |
| AVM                             | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 123       | 11.55%  |
| Intel Wi-Fi 6 AX201                                            | 67        | 6.29%   |
| Intel Wireless 8265 / 8275                                     | 53        | 4.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 38        | 3.57%   |
| Intel Wireless 8260                                            | 35        | 3.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 32        | 3%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 30        | 2.82%   |
| Intel Wireless 7260                                            | 27        | 2.54%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 27        | 2.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 27        | 2.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 26        | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 24        | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 22        | 2.07%   |
| Intel Wireless 7265                                            | 22        | 2.07%   |
| Intel Wireless-AC 9260                                         | 21        | 1.97%   |
| Intel Wireless 3165                                            | 20        | 1.88%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 1.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 17        | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 17        | 1.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 1.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 1.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 0.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 0.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 9         | 0.85%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 8         | 0.75%   |
| Realtek 802.11ac NIC                                           | 7         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                 | 7         | 0.66%   |
| TP-Link 802.11ac NIC                                           | 6         | 0.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 6         | 0.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 0.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 6         | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 0.47%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 5         | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 0.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 5         | 0.47%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 0.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 5         | 0.47%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 5         | 0.47%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 0.47%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 4         | 0.38%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 4         | 0.38%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                  | 4         | 0.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 4         | 0.38%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.38%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.38%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.38%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 4         | 0.38%   |
| TP-Link TL-WN722N v2                                           | 3         | 0.28%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 3         | 0.28%   |
| Ralink RT5372 Wireless Adapter                                 | 3         | 0.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 556       | 53.36%  |
| Intel                            | 324       | 31.09%  |
| Qualcomm Atheros                 | 39        | 3.74%   |
| Broadcom                         | 27        | 2.59%   |
| Lenovo                           | 15        | 1.44%   |
| Nvidia                           | 10        | 0.96%   |
| Marvell Technology Group         | 10        | 0.96%   |
| Xiaomi                           | 7         | 0.67%   |
| DisplayLink                      | 7         | 0.67%   |
| ASIX Electronics                 | 7         | 0.67%   |
| Aquantia                         | 6         | 0.58%   |
| Samsung Electronics              | 3         | 0.29%   |
| TP-Link                          | 2         | 0.19%   |
| OPPO Electronics                 | 2         | 0.19%   |
| MosChip Semiconductor            | 2         | 0.19%   |
| ICS Advent                       | 2         | 0.19%   |
| Huawei Technologies              | 2         | 0.19%   |
| HMD Global                       | 2         | 0.19%   |
| Google                           | 2         | 0.19%   |
| Cypress Semiconductor            | 2         | 0.19%   |
| Broadcom Limited                 | 2         | 0.19%   |
| Apple                            | 2         | 0.19%   |
| Xilinx                           | 1         | 0.1%    |
| Unknown                          | 1         | 0.1%    |
| Spreadtrum Communications        | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| Qualcomm                         | 1         | 0.1%    |
| NetXen Incorporated              | 1         | 0.1%    |
| Mellanox Technologies            | 1         | 0.1%    |
| MediaTek                         | 1         | 0.1%    |
| Linksys                          | 1         | 0.1%    |
| D-Link                           | 1         | 0.1%    |
| ASUSTek Computer                 | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 407       | 37.86%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 67        | 6.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 47        | 4.37%   |
| Intel I211 Gigabit Network Connection                                          | 42        | 3.91%   |
| Realtek RTL8125 2.5GbE Controller                                              | 35        | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 35        | 3.26%   |
| Intel Ethernet Connection (7) I219-V                                           | 22        | 2.05%   |
| Intel Ethernet Controller I225-V                                               | 20        | 1.86%   |
| Intel Ethernet Connection (2) I219-V                                           | 19        | 1.77%   |
| Intel Ethernet Connection (4) I219-LM                                          | 16        | 1.49%   |
| Intel Ethernet Connection (6) I219-V                                           | 15        | 1.4%    |
| Intel Ethernet Connection I219-LM                                              | 13        | 1.21%   |
| Intel Ethernet Connection I217-LM                                              | 12        | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                                          | 11        | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 11        | 1.02%   |
| Intel Ethernet Connection I218-LM                                              | 10        | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                                          | 10        | 0.93%   |
| Intel Ethernet Connection (4) I219-V                                           | 10        | 0.93%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 8         | 0.74%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 7         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.65%   |
| Intel Ethernet Connection I219-V                                               | 7         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                                          | 7         | 0.65%   |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.65%   |
| Intel 82574L Gigabit Network Connection                                        | 7         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 6         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 6         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                                          | 6         | 0.56%   |
| Intel Ethernet Connection (13) I219-V                                          | 6         | 0.56%   |
| Intel Ethernet Connection (11) I219-LM                                         | 6         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 0.47%   |
| Intel Ethernet Connection I217-V                                               | 5         | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.37%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 0.37%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 0.37%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 0.37%   |
| Intel Ethernet Connection (2) I218-V                                           | 4         | 0.37%   |
| Intel Ethernet Connection (13) I219-LM                                         | 4         | 0.37%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4         | 0.37%   |
| DisplayLink Dell Universal Dock D6000                                          | 4         | 0.37%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 4         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 0.28%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 3         | 0.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.28%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 3         | 0.28%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 0.19%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.19%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.19%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.19%   |
| OPPO SDM665-IDP _SN:18689828                                                   | 2         | 0.19%   |
| Nvidia MCP61 Ethernet                                                          | 2         | 0.19%   |
| Nvidia MCP55 Ethernet                                                          | 2         | 0.19%   |
| MosChip MCS7830 10/100 Mbps Ethernet adapter                                   | 2         | 0.19%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 998       | 50.28%  |
| Ethernet | 975       | 49.12%  |
| Modem    | 10        | 0.5%    |
| Unknown  | 2         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 868       | 55.68%  |
| Ethernet | 691       | 44.32%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 637       | 52.04%  |
| 1     | 520       | 42.48%  |
| 3     | 38        | 3.1%    |
| 0     | 23        | 1.88%   |
| 4     | 4         | 0.33%   |
| 6     | 1         | 0.08%   |
| 5     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 922       | 74.84%  |
| Yes  | 310       | 25.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 523       | 58.31%  |
| Realtek Semiconductor           | 82        | 9.14%   |
| Qualcomm Atheros Communications | 53        | 5.91%   |
| Cambridge Silicon Radio         | 43        | 4.79%   |
| Apple                           | 37        | 4.12%   |
| Lite-On Technology              | 29        | 3.23%   |
| Broadcom                        | 26        | 2.9%    |
| IMC Networks                    | 24        | 2.68%   |
| ASUSTek Computer                | 20        | 2.23%   |
| Foxconn / Hon Hai               | 19        | 2.12%   |
| Realtek                         | 13        | 1.45%   |
| Ralink                          | 9         | 1%      |
| MediaTek                        | 4         | 0.45%   |
| Marvell Semiconductor           | 3         | 0.33%   |
| Dell                            | 3         | 0.33%   |
| TP-Link                         | 2         | 0.22%   |
| Hewlett-Packard                 | 2         | 0.22%   |
| Foxconn International           | 2         | 0.22%   |
| Belkin Components               | 2         | 0.22%   |
| Alps Electric                   | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 240       | 26.76%  |
| Intel AX200 Bluetooth                               | 119       | 13.27%  |
| Intel Bluetooth wireless interface                  | 98        | 10.93%  |
| Realtek Bluetooth Radio                             | 66        | 7.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 43        | 4.79%   |
| Qualcomm Atheros  Bluetooth Device                  | 29        | 3.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 20        | 2.23%   |
| Apple Bluetooth Host Controller                     | 18        | 2.01%   |
| Intel Wireless-AC 3168 Bluetooth                    | 17        | 1.9%    |
| Intel AX210 Bluetooth                               | 17        | 1.9%    |
| Realtek 802.11ac WLAN Adapter                       | 12        | 1.34%   |
| IMC Networks Wireless_Device                        | 11        | 1.23%   |
| Ralink RT3290 Bluetooth                             | 9         | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 9         | 1%      |
| Apple Bluetooth USB Host Controller                 | 9         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.78%   |
| Lite-On Bluetooth Device                            | 7         | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.78%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 0.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6         | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.56%   |
| IMC Networks Bluetooth Radio                        | 5         | 0.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.56%   |
| ASUS Bluetooth Radio                                | 5         | 0.56%   |
| MediaTek Wireless_Device                            | 4         | 0.45%   |
| Lite-On Wireless_Device                             | 4         | 0.45%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.45%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 0.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.45%   |
| ASUS ASUS USB-BT500                                 | 4         | 0.45%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.33%   |
| TP-Link UB500 Adapter                               | 2         | 0.22%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.22%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.22%   |
| IMC Networks Bluetooth Device                       | 2         | 0.22%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.22%   |
| Foxconn / Hon Hai BT                                | 2         | 0.22%   |
| Dell BCM20702A0                                     | 2         | 0.22%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.22%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.22%   |
| ASUS Bluetooth Device                               | 2         | 0.22%   |
| ASUS Bluetooth Adapter                              | 2         | 0.22%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.11%   |
| Realtek Bluetooth Radio                             | 1         | 0.11%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.11%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.11%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.11%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.11%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.11%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.11%   |
| IMC Networks Bluetooth                              | 1         | 0.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 822       | 45.24%  |
| AMD                                  | 409       | 22.51%  |
| Nvidia                               | 292       | 16.07%  |
| C-Media Electronics                  | 33        | 1.82%   |
| GN Netcom                            | 16        | 0.88%   |
| Realtek Semiconductor                | 15        | 0.83%   |
| Lenovo                               | 15        | 0.83%   |
| Logitech                             | 14        | 0.77%   |
| JMTek                                | 12        | 0.66%   |
| Creative Labs                        | 11        | 0.61%   |
| Plantronics                          | 10        | 0.55%   |
| Kingston Technology                  | 10        | 0.55%   |
| Texas Instruments                    | 9         | 0.5%    |
| SteelSeries ApS                      | 9         | 0.5%    |
| Razer USA                            | 9         | 0.5%    |
| Focusrite-Novation                   | 8         | 0.44%   |
| Corsair                              | 7         | 0.39%   |
| Creative Technology                  | 6         | 0.33%   |
| Sony                                 | 5         | 0.28%   |
| Sennheiser Communications            | 5         | 0.28%   |
| Generalplus Technology               | 5         | 0.28%   |
| Tenx Technology                      | 4         | 0.22%   |
| Hewlett-Packard                      | 4         | 0.22%   |
| Blue Microphones                     | 4         | 0.22%   |
| Apple                                | 4         | 0.22%   |
| SAVITECH                             | 3         | 0.17%   |
| Samson Technologies                  | 3         | 0.17%   |
| GYROCOM C&C                          | 3         | 0.17%   |
| CMX Systems                          | 3         | 0.17%   |
| Apogee Electronics                   | 3         | 0.17%   |
| XMOS                                 | 2         | 0.11%   |
| Unknown                              | 2         | 0.11%   |
| RODE Microphones                     | 2         | 0.11%   |
| PreSonus Audio Electronics           | 2         | 0.11%   |
| Giga-Byte Technology                 | 2         | 0.11%   |
| Fujitsu                              | 2         | 0.11%   |
| Dell                                 | 2         | 0.11%   |
| Cooler Master                        | 2         | 0.11%   |
| Cambridge Silicon Radio              | 2         | 0.11%   |
| Barco Display Systems                | 2         | 0.11%   |
| Audio-Technica                       | 2         | 0.11%   |
| ASUSTek Computer                     | 2         | 0.11%   |
| Arturia                              | 2         | 0.11%   |
| Unknown                              | 2         | 0.11%   |
| ZOOM                                 | 1         | 0.06%   |
| Yamaha                               | 1         | 0.06%   |
| Valve Software                       | 1         | 0.06%   |
| ULi Electronics                      | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| Thermaltake                          | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.06%   |
| ShareWave                            | 1         | 0.06%   |
| Schiit Audio                         | 1         | 0.06%   |
| Roland                               | 1         | 0.06%   |
| RME                                  | 1         | 0.06%   |
| Quanta                               | 1         | 0.06%   |
| OLKB                                 | 1         | 0.06%   |
| Native Instruments                   | 1         | 0.06%   |
| Microsoft                            | 1         | 0.06%   |
| Micronas                             | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 171       | 7.86%   |
| Intel Sunrise Point-LP HD Audio                                            | 130       | 5.98%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 105       | 4.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 87        | 4%      |
| AMD Starship/Matisse HD Audio Controller                                   | 73        | 3.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 66        | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 62        | 2.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 54        | 2.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 53        | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 50        | 2.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 41        | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 40        | 1.84%   |
| Intel Comet Lake PCH cAVS                                                  | 39        | 1.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 36        | 1.66%   |
| Nvidia GP107GL High Definition Audio Controller                            | 35        | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 35        | 1.61%   |
| Intel Comet Lake PCH-LP cAVS                                               | 34        | 1.56%   |
| AMD FCH Azalia Controller                                                  | 33        | 1.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 31        | 1.43%   |
| Intel 8 Series HD Audio Controller                                         | 31        | 1.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 31        | 1.43%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 27        | 1.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 25        | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 25        | 1.15%   |
| Nvidia Audio device                                                        | 23        | 1.06%   |
| Intel 200 Series PCH HD Audio                                              | 22        | 1.01%   |
| Intel Broadwell-U Audio Controller                                         | 21        | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 20        | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 19        | 0.87%   |
| AMD Navi 10 HDMI Audio                                                     | 19        | 0.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 18        | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                              | 16        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 16        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 15        | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                   | 15        | 0.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 0.64%   |
| Nvidia GP104 High Definition Audio Controller                              | 13        | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 13        | 0.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 13        | 0.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13        | 0.6%    |
| Realtek Semiconductor USB Audio                                            | 12        | 0.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 0.55%   |
| Nvidia TU104 HD Audio Controller                                           | 11        | 0.51%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 11        | 0.51%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 11        | 0.51%   |
| Nvidia GF108 High Definition Audio Controller                              | 10        | 0.46%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                               | 10        | 0.46%   |
| Intel CM238 HD Audio Controller                                            | 10        | 0.46%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 10        | 0.46%   |
| Nvidia GK107 HDMI Audio Controller                                         | 9         | 0.41%   |
| AMD Trinity HDMI Audio Controller                                          | 9         | 0.41%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9         | 0.41%   |
| JMTek USB PnP Audio Device                                                 | 8         | 0.37%   |
| Intel Alder Lake-S HD Audio Controller                                     | 8         | 0.37%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8         | 0.37%   |
| Nvidia High Definition Audio Controller                                    | 7         | 0.32%   |
| Nvidia GK104 HDMI Audio Controller                                         | 7         | 0.32%   |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 0.32%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 177       | 23.76%  |
| SK Hynix            | 124       | 16.64%  |
| Micron Technology   | 93        | 12.48%  |
| Kingston            | 88        | 11.81%  |
| Crucial             | 64        | 8.59%   |
| Unknown             | 47        | 6.31%   |
| Corsair             | 47        | 6.31%   |
| G.Skill             | 23        | 3.09%   |
| A-DATA Technology   | 14        | 1.88%   |
| Ramaxel Technology  | 12        | 1.61%   |
| Team                | 9         | 1.21%   |
| Elpida              | 5         | 0.67%   |
| Unknown (ABCD)      | 4         | 0.54%   |
| Smart               | 4         | 0.54%   |
| Transcend           | 3         | 0.4%    |
| SMART Brazil        | 3         | 0.4%    |
| Patriot             | 3         | 0.4%    |
| GOODRAM             | 3         | 0.4%    |
| Avant               | 3         | 0.4%    |
| TIMETEC             | 2         | 0.27%   |
| Nanya Technology    | 2         | 0.27%   |
| Goldkey             | 2         | 0.27%   |
| Unknown             | 2         | 0.27%   |
| V-GeN               | 1         | 0.13%   |
| Toshiba             | 1         | 0.13%   |
| Qimonda             | 1         | 0.13%   |
| PUSKILL             | 1         | 0.13%   |
| PLEXHD              | 1         | 0.13%   |
| OCZ                 | 1         | 0.13%   |
| Miron               | 1         | 0.13%   |
| fef5                | 1         | 0.13%   |
| ASint Technology    | 1         | 0.13%   |
| Apacer              | 1         | 0.13%   |
| AMD                 | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.27%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.01%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 1.01%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.89%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.89%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 6         | 0.76%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 6         | 0.76%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 0.76%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 5         | 0.63%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.63%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.63%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 5         | 0.63%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.51%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 4         | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 4         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 4         | 0.51%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.51%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s         | 4         | 0.51%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s             | 4         | 0.51%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 4         | 0.51%   |
| Crucial RAM CT51264BF160BJ.C8F 4096MB SODIMM DDR3 1600MT/s       | 4         | 0.51%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 4         | 0.51%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.38%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 3         | 0.38%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.38%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 3         | 0.38%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.38%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.38%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 3         | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.38%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 0.38%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 3         | 0.38%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.38%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.38%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.38%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                | 3         | 0.38%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s       | 3         | 0.38%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 3         | 0.38%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s           | 3         | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 3         | 0.38%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 3         | 0.38%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 2         | 0.25%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.25%   |
| Unknown RAM Module 4GB DIMM 800MT/s                              | 2         | 0.25%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 373       | 58.01%  |
| DDR3    | 159       | 24.73%  |
| LPDDR4  | 44        | 6.84%   |
| LPDDR3  | 36        | 5.6%    |
| Unknown | 17        | 2.64%   |
| DDR2    | 11        | 1.71%   |
| SDRAM   | 2         | 0.31%   |
| DDR     | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 362       | 55.35%  |
| DIMM         | 188       | 28.75%  |
| Row Of Chips | 96        | 14.68%  |
| Chip         | 5         | 0.76%   |
| Unknown      | 2         | 0.31%   |
| FB-DIMM      | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 293       | 42.84%  |
| 4096  | 181       | 26.46%  |
| 16384 | 122       | 17.84%  |
| 2048  | 56        | 8.19%   |
| 32768 | 25        | 3.65%   |
| 1024  | 7         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 153       | 22.3%   |
| 2667    | 123       | 17.93%  |
| 1600    | 109       | 15.89%  |
| 2400    | 49        | 7.14%   |
| 2133    | 41        | 5.98%   |
| 1333    | 29        | 4.23%   |
| 4267    | 26        | 3.79%   |
| 3600    | 22        | 3.21%   |
| 1867    | 19        | 2.77%   |
| 1067    | 12        | 1.75%   |
| 3266    | 9         | 1.31%   |
| 1334    | 9         | 1.31%   |
| 2933    | 8         | 1.17%   |
| 1066    | 8         | 1.17%   |
| 800     | 8         | 1.17%   |
| 3733    | 7         | 1.02%   |
| 667     | 6         | 0.87%   |
| 4266    | 5         | 0.73%   |
| 3466    | 5         | 0.73%   |
| 3400    | 5         | 0.73%   |
| 2666    | 5         | 0.73%   |
| 4800    | 4         | 0.58%   |
| 3533    | 4         | 0.58%   |
| 3000    | 3         | 0.44%   |
| 4199    | 2         | 0.29%   |
| 2800    | 2         | 0.29%   |
| 1866    | 2         | 0.29%   |
| 400     | 2         | 0.29%   |
| 8400    | 1         | 0.15%   |
| 4000    | 1         | 0.15%   |
| 3066    | 1         | 0.15%   |
| 2802    | 1         | 0.15%   |
| 2134    | 1         | 0.15%   |
| 1024    | 1         | 0.15%   |
| 975     | 1         | 0.15%   |
| 333     | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 6         | 28.57%  |
| Hewlett-Packard     | 5         | 23.81%  |
| Samsung Electronics | 3         | 14.29%  |
| Canon               | 3         | 14.29%  |
| Seiko Epson         | 1         | 4.76%   |
| QinHeng Electronics | 1         | 4.76%   |
| Prolific Technology | 1         | 4.76%   |
| Kyocera             | 1         | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Brother HL-L2340D series        | 2         | 9.52%   |
| Seiko Epson WF-2510 Series      | 1         | 4.76%   |
| Samsung SCX-3200 Series         | 1         | 4.76%   |
| Samsung M2070 Series            | 1         | 4.76%   |
| Samsung CLX-6260 Series         | 1         | 4.76%   |
| QinHeng CH340S                  | 1         | 4.76%   |
| Prolific PL2305 Parallel Port   | 1         | 4.76%   |
| Kyocera ECOSYS M5521cdw         | 1         | 4.76%   |
| HP LaserJet CM1415fnw           | 1         | 4.76%   |
| HP LaserJet 400 colorMFP M475dw | 1         | 4.76%   |
| HP LaserJet 1018                | 1         | 4.76%   |
| HP DeskJet F300 series          | 1         | 4.76%   |
| HP DeskJet F2492 All-in-One     | 1         | 4.76%   |
| Canon TR8500 series             | 1         | 4.76%   |
| Canon TR4500 series             | 1         | 4.76%   |
| Canon MF4010 series             | 1         | 4.76%   |
| Brother Printer                 | 1         | 4.76%   |
| Brother MFC-J485DW              | 1         | 4.76%   |
| Brother HL-L2360D series        | 1         | 4.76%   |
| Brother HL-1440 Laser Printer   | 1         | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 4         | 57.14%  |
| Seiko Epson | 3         | 42.86%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500]       | 2         | 28.57%  |
| Canon CanoScan LiDE 220                     | 2         | 28.57%  |
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 1         | 14.29%  |
| Canon CanoScan LiDE 210                     | 1         | 14.29%  |
| Canon CanoScan LiDE 120                     | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 176       | 20.39%  |
| IMC Networks                           | 86        | 9.97%   |
| Acer                                   | 77        | 8.92%   |
| Logitech                               | 75        | 8.69%   |
| Microdia                               | 73        | 8.46%   |
| Realtek Semiconductor                  | 65        | 7.53%   |
| Quanta                                 | 53        | 6.14%   |
| Sunplus Innovation Technology          | 39        | 4.52%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 3.71%   |
| Apple                                  | 28        | 3.24%   |
| Syntek                                 | 25        | 2.9%    |
| Lite-On Technology                     | 21        | 2.43%   |
| Luxvisions Innotech Limited            | 14        | 1.62%   |
| Suyin                                  | 13        | 1.51%   |
| Samsung Electronics                    | 8         | 0.93%   |
| Microsoft                              | 8         | 0.93%   |
| Silicon Motion                         | 6         | 0.7%    |
| Alcor Micro                            | 6         | 0.7%    |
| Lenovo                                 | 5         | 0.58%   |
| Ricoh                                  | 4         | 0.46%   |
| Generalplus Technology                 | 4         | 0.46%   |
| ARC International                      | 4         | 0.46%   |
| Sonix Technology                       | 3         | 0.35%   |
| Creative Technology                    | 3         | 0.35%   |
| Z-Star Microelectronics                | 2         | 0.23%   |
| Trust                                  | 2         | 0.23%   |
| Primax Electronics                     | 2         | 0.23%   |
| MacroSilicon                           | 2         | 0.23%   |
| KYE Systems (Mouse Systems)            | 2         | 0.23%   |
| Jieli Technology                       | 2         | 0.23%   |
| Importek                               | 2         | 0.23%   |
| Genesys Logic                          | 2         | 0.23%   |
| WaveRider Communications               | 1         | 0.12%   |
| USB Camera                             | 1         | 0.12%   |
| Tobii Technology AB                    | 1         | 0.12%   |
| SunplusIT                              | 1         | 0.12%   |
| Razer USA                              | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| Omnivision                             | 1         | 0.12%   |
| Micro Star International               | 1         | 0.12%   |
| LG Electronics                         | 1         | 0.12%   |
| Hewlett-Packard                        | 1         | 0.12%   |
| HD 2MP WEBCAM                          | 1         | 0.12%   |
| Guillemot                              | 1         | 0.12%   |
| Foxconn / Hon Hai                      | 1         | 0.12%   |
| DLUPCA1UIFGOTE                         | 1         | 0.12%   |
| DigiTech                               | 1         | 0.12%   |
| Cubeternet                             | 1         | 0.12%   |
| Audio-Technica                         | 1         | 0.12%   |
| ANYKA                                  | 1         | 0.12%   |
| ALi                                    | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 58        | 6.65%   |
| Microdia Integrated_Webcam_HD                                   | 44        | 5.05%   |
| IMC Networks Integrated Camera                                  | 39        | 4.47%   |
| Acer Integrated Camera                                          | 35        | 4.01%   |
| Realtek Integrated_Webcam_HD                                    | 25        | 2.87%   |
| Sunplus Integrated_Webcam_HD                                    | 22        | 2.52%   |
| Syntek Integrated Camera                                        | 21        | 2.41%   |
| Logitech HD Pro Webcam C920                                     | 20        | 2.29%   |
| Logitech Webcam C270                                            | 19        | 2.18%   |
| Quanta HD User Facing                                           | 17        | 1.95%   |
| Chicony HD Webcam                                               | 16        | 1.83%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 15        | 1.72%   |
| Quanta HP TrueVision HD Camera                                  | 10        | 1.15%   |
| Chicony Integrated Camera (1280x720@30)                         | 10        | 1.15%   |
| Apple Built-in iSight                                           | 10        | 1.15%   |
| Logitech C922 Pro Stream Webcam                                 | 9         | 1.03%   |
| Lite-On HP HD Camera                                            | 9         | 1.03%   |
| Apple FaceTime HD Camera (Built-in)                             | 9         | 1.03%   |
| Samsung Galaxy A5 (MTP)                                         | 8         | 0.92%   |
| Microdia Integrated Webcam                                      | 8         | 0.92%   |
| IMC Networks HD Camera                                          | 8         | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 7         | 0.8%    |
| Chicony USB2.0 Camera                                           | 7         | 0.8%    |
| Chicony HP Wide Vision HD Camera                                | 7         | 0.8%    |
| Chicony HP HD Camera                                            | 7         | 0.8%    |
| Acer SunplusIT Integrated Camera                                | 7         | 0.8%    |
| Lite-On Integrated Camera                                       | 6         | 0.69%   |
| Chicony HD User Facing                                          | 6         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 6         | 0.69%   |
| Acer HD Webcam                                                  | 6         | 0.69%   |
| Acer BisonCam,NB Pro                                            | 6         | 0.69%   |
| Realtek USB Camera                                              | 5         | 0.57%   |
| Realtek Integrated Webcam HD                                    | 5         | 0.57%   |
| Quanta HP Wide Vision HD Camera                                 | 5         | 0.57%   |
| Quanta HP HD Camera                                             | 5         | 0.57%   |
| Chicony EasyCamera                                              | 5         | 0.57%   |
| Alcor Micro USB 2.0 Camera                                      | 5         | 0.57%   |
| Acer Lenovo EasyCamera                                          | 5         | 0.57%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 4         | 0.46%   |
| Sunplus HD WebCam                                               | 4         | 0.46%   |
| Quanta VGA WebCam                                               | 4         | 0.46%   |
| Microdia USB Live camera                                        | 4         | 0.46%   |
| Luxvisions Innotech Limited Integrated Camera                   | 4         | 0.46%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 0.46%   |
| Logitech StreamCam                                              | 4         | 0.46%   |
| Logitech HD Webcam C615                                         | 4         | 0.46%   |
| IMC Networks ov9734_azurewave_camera                            | 4         | 0.46%   |
| Chicony USB2.0 HD UVC WebCam                                    | 4         | 0.46%   |
| Chicony USB 2.0 Camera                                          | 4         | 0.46%   |
| Chicony HP TrueVision HD                                        | 4         | 0.46%   |
| Chicony HP HD Webcam                                            | 4         | 0.46%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 4         | 0.46%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 0.46%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 4         | 0.46%   |
| ARC International Camera                                        | 4         | 0.46%   |
| Apple FaceTime HD Camera                                        | 4         | 0.46%   |
| Acer EasyCamera                                                 | 4         | 0.46%   |
| Acer BisonCam, NB Pro                                           | 4         | 0.46%   |
| Syntek EasyCamera                                               | 3         | 0.34%   |
| Suyin Integrated_Webcam_HD                                      | 3         | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 83        | 40.69%  |
| Validity Sensors           | 51        | 25%     |
| Shenzhen Goodix Technology | 45        | 22.06%  |
| Elan Microelectronics      | 10        | 4.9%    |
| Upek                       | 6         | 2.94%   |
| LighTuning Technology      | 6         | 2.94%   |
| AuthenTec                  | 2         | 0.98%   |
| Samsung Electronics        | 1         | 0.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 36        | 17.65%  |
| Shenzhen Goodix  Fingerprint Device                                        | 27        | 13.24%  |
| Unknown                                                                    | 23        | 11.27%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 7.84%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 4.41%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 4.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 3.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 3.43%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 3.43%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 2.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.94%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.45%   |
| Validity Sensors VFS491                                                    | 4         | 1.96%   |
| Synaptics  WBDI                                                            | 4         | 1.96%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.96%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.47%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.98%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.98%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.98%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.98%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.98%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.49%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.49%   |
| Synaptics WBDI Device                                                      | 1         | 0.49%   |
| Samsung Fingerprint Device                                                 | 1         | 0.49%   |
| AuthenTec AES2810                                                          | 1         | 0.49%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 27        | 43.55%  |
| Broadcom                  | 25        | 40.32%  |
| Lenovo                    | 3         | 4.84%   |
| Upek                      | 2         | 3.23%   |
| Yubico.com                | 1         | 1.61%   |
| O2 Micro                  | 1         | 1.61%   |
| Hewlett-Packard           | 1         | 1.61%   |
| Gemalto (was Gemplus)     | 1         | 1.61%   |
| Aladdin Knowledge Systems | 1         | 1.61%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 43.55%  |
| Broadcom 58200                                                               | 9         | 14.52%  |
| Broadcom 5880                                                                | 7         | 11.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 9.68%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.84%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.23%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 1.61%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.61%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.61%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.61%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.61%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 850       | 68.27%  |
| 1     | 324       | 26.02%  |
| 2     | 55        | 4.42%   |
| 3     | 12        | 0.96%   |
| 5     | 2         | 0.16%   |
| 4     | 2         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 200       | 42.55%  |
| Graphics card            | 96        | 20.43%  |
| Multimedia controller    | 52        | 11.06%  |
| Net/wireless             | 49        | 10.43%  |
| Camera                   | 21        | 4.47%   |
| Bluetooth                | 14        | 2.98%   |
| Chipcard                 | 9         | 1.91%   |
| Communication controller | 7         | 1.49%   |
| Card reader              | 6         | 1.28%   |
| Unassigned class         | 5         | 1.06%   |
| Storage                  | 3         | 0.64%   |
| Sound                    | 3         | 0.64%   |
| Net/ethernet             | 2         | 0.43%   |
| Storage/raid             | 1         | 0.21%   |
| Network                  | 1         | 0.21%   |
| Firewire controller      | 1         | 0.21%   |

