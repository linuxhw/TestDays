Fedora 35 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell       | 0T7D40 A01                  | [4ce7ea3bb0](https://linux-hardware.org/?probe=4ce7ea3bb0) | Dec 31, 2021 |
| Intel      | SKYBAY                      | [043f80cded](https://linux-hardware.org/?probe=043f80cded) | Dec 31, 2021 |
| ASUSTek    | PRIME B450M-A               | [58cb628601](https://linux-hardware.org/?probe=58cb628601) | Dec 31, 2021 |
| Gigabyte   | F2A88XM-DS2P                | [75eea6ae2f](https://linux-hardware.org/?probe=75eea6ae2f) | Dec 30, 2021 |
| ASUSTek    | TUF B365M-PLUS GAMING       | [00f3b181b3](https://linux-hardware.org/?probe=00f3b181b3) | Dec 30, 2021 |
| MSI        | X370 GAMING PLUS            | [49f7093e8c](https://linux-hardware.org/?probe=49f7093e8c) | Dec 29, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [47edce55a4](https://linux-hardware.org/?probe=47edce55a4) | Dec 29, 2021 |
| ASUSTek    | TUF B365M-PLUS GAMING       | [e3297eb51f](https://linux-hardware.org/?probe=e3297eb51f) | Dec 29, 2021 |
| Gigabyte   | TRX40 AORUS XTREME          | [cbf9ee4a86](https://linux-hardware.org/?probe=cbf9ee4a86) | Dec 28, 2021 |
| MSI        | H81M-E33                    | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| XFX        | nForce 780i 3-Way SLI 1     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| ASUSTek    | M2N-E                       | [3a08145f4b](https://linux-hardware.org/?probe=3a08145f4b) | Dec 24, 2021 |
| ASUSTek    | ROG Maximus XI HERO         | [ca0f62a716](https://linux-hardware.org/?probe=ca0f62a716) | Dec 24, 2021 |
| MSI        | MEG Z390 GODLIKE            | [f1e535b5ba](https://linux-hardware.org/?probe=f1e535b5ba) | Dec 24, 2021 |
| Gigabyte   | Z390 M-CF                   | [6efc5bede0](https://linux-hardware.org/?probe=6efc5bede0) | Dec 23, 2021 |
| ASUSTek    | TUF B365M-PLUS GAMING       | [4cd052492e](https://linux-hardware.org/?probe=4cd052492e) | Dec 23, 2021 |
| MSI        | A320M PRO-VH PLUS           | [27379a7599](https://linux-hardware.org/?probe=27379a7599) | Dec 22, 2021 |
| MSI        | PRO Z690-A WIFI DDR4        | [51a7e08e9a](https://linux-hardware.org/?probe=51a7e08e9a) | Dec 22, 2021 |
| MSI        | X470 GAMING M7 AC           | [9b2acc6ea1](https://linux-hardware.org/?probe=9b2acc6ea1) | Dec 22, 2021 |
| Gigabyte   | B450 AORUS ELITE            | [dd197ecb62](https://linux-hardware.org/?probe=dd197ecb62) | Dec 21, 2021 |
| ASUSTek    | P5G41-M                     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII IMPAC... | [03abaff4ae](https://linux-hardware.org/?probe=03abaff4ae) | Dec 21, 2021 |
| Gigabyte   | EP45-DS3L                   | [e0f736fe3b](https://linux-hardware.org/?probe=e0f736fe3b) | Dec 20, 2021 |
| Dell       | 0YJPT1 A00                  | [a92e152a7c](https://linux-hardware.org/?probe=a92e152a7c) | Dec 20, 2021 |
| ASRock     | X399 Taichi                 | [16e27617b9](https://linux-hardware.org/?probe=16e27617b9) | Dec 20, 2021 |
| Gigabyte   | H61M-USB3V                  | [d05d2fe462](https://linux-hardware.org/?probe=d05d2fe462) | Dec 20, 2021 |
| ASUSTek    | PRIME H270-PLUS             | [9c1cf57d74](https://linux-hardware.org/?probe=9c1cf57d74) | Dec 20, 2021 |
| Dell       | 0C522T A03                  | [58f36b9637](https://linux-hardware.org/?probe=58f36b9637) | Dec 20, 2021 |
| Dell       | 0YXT71 A03                  | [0a48d9579b](https://linux-hardware.org/?probe=0a48d9579b) | Dec 19, 2021 |
| MSI        | X370 SLI PLUS               | [adb27f9347](https://linux-hardware.org/?probe=adb27f9347) | Dec 19, 2021 |
| Lenovo     | 312A SDK0J40697 WIN 3305... | [e2ce1d7284](https://linux-hardware.org/?probe=e2ce1d7284) | Dec 19, 2021 |
| MSI        | MAG B550 TOMAHAWK           | [6653477f61](https://linux-hardware.org/?probe=6653477f61) | Dec 18, 2021 |
| JINGSHA    | Unknown                     | [13da82798c](https://linux-hardware.org/?probe=13da82798c) | Dec 18, 2021 |
| Gigabyte   | H370 HD3-CF                 | [2497b24eda](https://linux-hardware.org/?probe=2497b24eda) | Dec 18, 2021 |
| Gigabyte   | F2A88XM-DS2P                | [c18ddabc8d](https://linux-hardware.org/?probe=c18ddabc8d) | Dec 18, 2021 |
| ASUSTek    | P5G41-M                     | [c073d4a4e9](https://linux-hardware.org/?probe=c073d4a4e9) | Dec 17, 2021 |
| ASUSTek    | ROG STRIX Z690-G GAMING ... | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek    | ROG STRIX Z690-G GAMING ... | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| HP         | 805D                        | [dfdc70512c](https://linux-hardware.org/?probe=dfdc70512c) | Dec 16, 2021 |
| ASUSTek    | Z97-PRO GAMER               | [45a411c9fe](https://linux-hardware.org/?probe=45a411c9fe) | Dec 15, 2021 |
| Gigabyte   | TRX40 AORUS MASTER          | [5915e986de](https://linux-hardware.org/?probe=5915e986de) | Dec 15, 2021 |
| MSI        | MPG B550 GAMING EDGE WIF... | [60a7206b05](https://linux-hardware.org/?probe=60a7206b05) | Dec 15, 2021 |
| ASUSTek    | ROG STRIX X570-F GAMING     | [660ce7fc74](https://linux-hardware.org/?probe=660ce7fc74) | Dec 15, 2021 |
| Dell       | 0RY007                      | [f3cb490147](https://linux-hardware.org/?probe=f3cb490147) | Dec 14, 2021 |
| Gigabyte   | Z270P-D3-CF                 | [b2dc7c9e05](https://linux-hardware.org/?probe=b2dc7c9e05) | Dec 14, 2021 |
| HP         | 2B2B                        | [bf929a4359](https://linux-hardware.org/?probe=bf929a4359) | Dec 14, 2021 |
| ASUSTek    | Z97-PRO GAMER               | [53523a4ea7](https://linux-hardware.org/?probe=53523a4ea7) | Dec 14, 2021 |
| MSI        | MPG B550 GAMING PLUS        | [3030fcf474](https://linux-hardware.org/?probe=3030fcf474) | Dec 13, 2021 |
| Gigabyte   | Z170-D3H-CF                 | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Gigabyte   | B560M DS3H V2               | [169e6793c2](https://linux-hardware.org/?probe=169e6793c2) | Dec 12, 2021 |
| ASUSTek    | ROG CROSSHAIR VII HERO      | [021525201e](https://linux-hardware.org/?probe=021525201e) | Dec 12, 2021 |
| MSI        | MAG B550 TOMAHAWK           | [bd4a0c5d2f](https://linux-hardware.org/?probe=bd4a0c5d2f) | Dec 12, 2021 |
| ASUSTek    | P6T                         | [b789a1151e](https://linux-hardware.org/?probe=b789a1151e) | Dec 11, 2021 |
| Gigabyte   | X570 AORUS PRO              | [8ae1043ce6](https://linux-hardware.org/?probe=8ae1043ce6) | Dec 10, 2021 |
| Gigabyte   | 990FXA-UD3                  | [b76ef07c59](https://linux-hardware.org/?probe=b76ef07c59) | Dec 10, 2021 |
| ASUSTek    | P6T                         | [71ce922273](https://linux-hardware.org/?probe=71ce922273) | Dec 09, 2021 |
| ASUSTek    | ROG STRIX X470-I GAMING     | [bf533d0378](https://linux-hardware.org/?probe=bf533d0378) | Dec 09, 2021 |
| Gigabyte   | Z690 UD DDR4                | [d0070c39c4](https://linux-hardware.org/?probe=d0070c39c4) | Dec 09, 2021 |
| Gigabyte   | Z77-D3H                     | [c486c9645b](https://linux-hardware.org/?probe=c486c9645b) | Dec 09, 2021 |
| Dell       | 040DDP A01                  | [b8e92a4957](https://linux-hardware.org/?probe=b8e92a4957) | Dec 09, 2021 |
| ASUSTek    | P6T                         | [d04f9d16a8](https://linux-hardware.org/?probe=d04f9d16a8) | Dec 08, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [82926e68a4](https://linux-hardware.org/?probe=82926e68a4) | Dec 08, 2021 |
| Supermicro | X9DRi-LN4+/X9DR3-LN4+       | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| Apple      | Mac-F221BEC8                | [809152313d](https://linux-hardware.org/?probe=809152313d) | Dec 07, 2021 |
| ASUSTek    | SABERTOOTH X79              | [58c6a86730](https://linux-hardware.org/?probe=58c6a86730) | Dec 07, 2021 |
| Gigabyte   | Z97P-D3                     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| XFX        | MI-A78S-8209 Ver1.1         | [5393b5ad7a](https://linux-hardware.org/?probe=5393b5ad7a) | Dec 06, 2021 |
| ASUSTek    | TUF GAMING B550-PLUS        | [9e878d83a3](https://linux-hardware.org/?probe=9e878d83a3) | Dec 06, 2021 |
| ASUSTek    | TUF GAMING B550-PLUS        | [0a06cba7c5](https://linux-hardware.org/?probe=0a06cba7c5) | Dec 06, 2021 |
| Lenovo     | 3642 SDK0J40700 WIN 3258... | [82cd98ea5a](https://linux-hardware.org/?probe=82cd98ea5a) | Dec 06, 2021 |
| Lenovo     | 3642 SDK0J40700 WIN 3258... | [07f484651e](https://linux-hardware.org/?probe=07f484651e) | Dec 06, 2021 |
| Gigabyte   | B450 AORUS M                | [18ae64d44d](https://linux-hardware.org/?probe=18ae64d44d) | Dec 05, 2021 |
| ASUSTek    | TUF B365M-PLUS GAMING       | [b296e2a320](https://linux-hardware.org/?probe=b296e2a320) | Dec 05, 2021 |
| Dell       | 0M859N A00                  | [f254ee88c6](https://linux-hardware.org/?probe=f254ee88c6) | Dec 05, 2021 |
| MSI        | Z87M GAMING                 | [4ef67e0560](https://linux-hardware.org/?probe=4ef67e0560) | Dec 04, 2021 |
| ASUSTek    | Z87-A                       | [e7d4963834](https://linux-hardware.org/?probe=e7d4963834) | Dec 04, 2021 |
| XFX        | MI-A78S-8209 Ver1.1         | [ce556a2535](https://linux-hardware.org/?probe=ce556a2535) | Dec 04, 2021 |
| Dell       | 0J3C2F A00                  | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| ASUSTek    | TUF GAMING B550-PLUS        | [511a349d7f](https://linux-hardware.org/?probe=511a349d7f) | Dec 03, 2021 |
| Gigabyte   | Z390 I AORUS PRO WIFI-CF    | [fd20b7fc56](https://linux-hardware.org/?probe=fd20b7fc56) | Dec 03, 2021 |
| Dell       | 06D7TR A00                  | [8c6244cb77](https://linux-hardware.org/?probe=8c6244cb77) | Dec 03, 2021 |
| MSI        | MEG Z390 GODLIKE            | [ca1727f54a](https://linux-hardware.org/?probe=ca1727f54a) | Dec 02, 2021 |
| Gateway    | SX2185                      | [70e907b207](https://linux-hardware.org/?probe=70e907b207) | Dec 02, 2021 |
| Dell       | 040DDP A01                  | [b108ae97c2](https://linux-hardware.org/?probe=b108ae97c2) | Dec 02, 2021 |
| MSI        | X370 XPOWER GAMING TITAN... | [56bd9b515c](https://linux-hardware.org/?probe=56bd9b515c) | Dec 02, 2021 |
| ASUSTek    | H81M-C                      | [ffecd77f3a](https://linux-hardware.org/?probe=ffecd77f3a) | Dec 02, 2021 |
| MSI        | B550M PRO-VDH WIFI          | [508352ad4a](https://linux-hardware.org/?probe=508352ad4a) | Dec 02, 2021 |
| Gigabyte   | B85M-D3V-A                  | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| Huanan     | X99-F8 V2.0                 | [1b4de261b3](https://linux-hardware.org/?probe=1b4de261b3) | Nov 30, 2021 |
| Gigabyte   | Z690 UD DDR4                | [7ad53e55ba](https://linux-hardware.org/?probe=7ad53e55ba) | Nov 30, 2021 |
| Apple      | Mac-F221BEC8                | [2ceb61c052](https://linux-hardware.org/?probe=2ceb61c052) | Nov 30, 2021 |
| Gigabyte   | EX58-UD3R                   | [8ece12c9e6](https://linux-hardware.org/?probe=8ece12c9e6) | Nov 28, 2021 |
| ECS        | H61H2-CM                    | [525be50825](https://linux-hardware.org/?probe=525be50825) | Nov 28, 2021 |
| Gigabyte   | H170-Gaming 3               | [e83680db56](https://linux-hardware.org/?probe=e83680db56) | Nov 28, 2021 |
| Gigabyte   | X570 AORUS MASTER           | [d813ffb878](https://linux-hardware.org/?probe=d813ffb878) | Nov 28, 2021 |
| Gigabyte   | AB350M-DS3H V2-CF           | [5d5d624d8c](https://linux-hardware.org/?probe=5d5d624d8c) | Nov 27, 2021 |
| MSI        | B450-A PRO MAX              | [d949cb9963](https://linux-hardware.org/?probe=d949cb9963) | Nov 27, 2021 |
| Dell       | 06D7TR A00                  | [d980b32136](https://linux-hardware.org/?probe=d980b32136) | Nov 27, 2021 |
| ASRock     | H81M-HG4 R4.0               | [c23e7e890b](https://linux-hardware.org/?probe=c23e7e890b) | Nov 27, 2021 |
| ASUSTek    | M4A77T/USB3                 | [e23dea02cf](https://linux-hardware.org/?probe=e23dea02cf) | Nov 26, 2021 |
| Gigabyte   | AB350M-Gaming 3-CF          | [1e4799819e](https://linux-hardware.org/?probe=1e4799819e) | Nov 26, 2021 |
| Gigabyte   | B550 AORUS ELITE            | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek    | Maximus IV GENE-Z           | [89729fef47](https://linux-hardware.org/?probe=89729fef47) | Nov 25, 2021 |
| Apple      | Mac-F221BEC8                | [f4f5c37779](https://linux-hardware.org/?probe=f4f5c37779) | Nov 25, 2021 |
| Gigabyte   | Z690 UD DDR4                | [b6ffc90d4e](https://linux-hardware.org/?probe=b6ffc90d4e) | Nov 25, 2021 |
| MSI        | B550-A PRO                  | [b90083da69](https://linux-hardware.org/?probe=b90083da69) | Nov 24, 2021 |
| Apple      | Mac-F221BEC8                | [e606757d4a](https://linux-hardware.org/?probe=e606757d4a) | Nov 24, 2021 |
| Dell       | 0C522T A03                  | [96fec5d214](https://linux-hardware.org/?probe=96fec5d214) | Nov 24, 2021 |
| Gigabyte   | B550 AORUS PRO              | [35801f40df](https://linux-hardware.org/?probe=35801f40df) | Nov 24, 2021 |
| Dell       | 0C522T A03                  | [79ee4911cb](https://linux-hardware.org/?probe=79ee4911cb) | Nov 24, 2021 |
| MSI        | A55M-E33                    | [e6616870b6](https://linux-hardware.org/?probe=e6616870b6) | Nov 24, 2021 |
| HP         | 1906                        | [8ec5c16fc7](https://linux-hardware.org/?probe=8ec5c16fc7) | Nov 24, 2021 |
| HP         | 83E1                        | [7598ac7e6c](https://linux-hardware.org/?probe=7598ac7e6c) | Nov 23, 2021 |
| ASUSTek    | Maximus IV GENE-Z           | [dab6e17223](https://linux-hardware.org/?probe=dab6e17223) | Nov 23, 2021 |
| Lenovo     | 3731 SDK0J40697 WIN 3305... | [c50601fb76](https://linux-hardware.org/?probe=c50601fb76) | Nov 23, 2021 |
| HP         | 0B4Ch D                     | [0c3c7c6bb3](https://linux-hardware.org/?probe=0c3c7c6bb3) | Nov 23, 2021 |
| HP         | 1906                        | [90499fe34d](https://linux-hardware.org/?probe=90499fe34d) | Nov 23, 2021 |
| Gigabyte   | X570 AORUS ELITE            | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| Gigabyte   | GA-MA790X-UD4               | [0a19a35ac4](https://linux-hardware.org/?probe=0a19a35ac4) | Nov 22, 2021 |
| ASRock     | G41M-VS3                    | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| Pegatron   | 2AD5                        | [8fc4f44be5](https://linux-hardware.org/?probe=8fc4f44be5) | Nov 22, 2021 |
| Gigabyte   | F2A85XM-D3H                 | [1c41d8c34c](https://linux-hardware.org/?probe=1c41d8c34c) | Nov 22, 2021 |
| ASRock     | X570 Phantom Gaming 4       | [683697e6ee](https://linux-hardware.org/?probe=683697e6ee) | Nov 21, 2021 |
| MSI        | B450M-A PRO MAX             | [92375d0ecc](https://linux-hardware.org/?probe=92375d0ecc) | Nov 21, 2021 |
| Dell       | 0M859N A00                  | [2fa52f3236](https://linux-hardware.org/?probe=2fa52f3236) | Nov 21, 2021 |
| Gigabyte   | B450M DS3H-CF               | [faec9a8f8b](https://linux-hardware.org/?probe=faec9a8f8b) | Nov 21, 2021 |
| HP         | 3048h                       | [e38eb769b5](https://linux-hardware.org/?probe=e38eb769b5) | Nov 20, 2021 |
| ASUSTek    | M5A78L-M/USB3               | [44d1a95b0b](https://linux-hardware.org/?probe=44d1a95b0b) | Nov 20, 2021 |
| MSI        | B450 GAMING PRO CARBON A... | [3b34362c42](https://linux-hardware.org/?probe=3b34362c42) | Nov 19, 2021 |
| ASUSTek    | A68HM-K                     | [8bf7660808](https://linux-hardware.org/?probe=8bf7660808) | Nov 19, 2021 |
| ASUSTek    | H87-PRO                     | [02b2e4cb00](https://linux-hardware.org/?probe=02b2e4cb00) | Nov 19, 2021 |
| ASUSTek    | H87-PRO                     | [181c56512d](https://linux-hardware.org/?probe=181c56512d) | Nov 19, 2021 |
| Dell       | 0YNVJG A01                  | [00f5cc73fe](https://linux-hardware.org/?probe=00f5cc73fe) | Nov 19, 2021 |
| Dell       | 0YNVJG A01                  | [fbedd3af33](https://linux-hardware.org/?probe=fbedd3af33) | Nov 19, 2021 |
| Pegatron   | 2AD5                        | [839b5c24aa](https://linux-hardware.org/?probe=839b5c24aa) | Nov 19, 2021 |
| MSI        | B450 TOMAHAWK               | [6a1607ab9d](https://linux-hardware.org/?probe=6a1607ab9d) | Nov 18, 2021 |
| MSI        | MPG X570 GAMING PRO CARB... | [c8a6893780](https://linux-hardware.org/?probe=c8a6893780) | Nov 18, 2021 |
| MSI        | A320M-A PRO MAX             | [d9f71fda8f](https://linux-hardware.org/?probe=d9f71fda8f) | Nov 18, 2021 |
| Dell       | 0C27VV A01                  | [34aff3ab72](https://linux-hardware.org/?probe=34aff3ab72) | Nov 18, 2021 |
| Gigabyte   | B450M DS3H-CF               | [f35f04cabd](https://linux-hardware.org/?probe=f35f04cabd) | Nov 18, 2021 |
| ASUSTek    | ROG CROSSHAIR VI HERO       | [50535d277c](https://linux-hardware.org/?probe=50535d277c) | Nov 18, 2021 |
| ASUSTek    | PRIME B360M-K               | [3b2165faa8](https://linux-hardware.org/?probe=3b2165faa8) | Nov 18, 2021 |
| Gigabyte   | B550M DS3H                  | [93c3ab9ed1](https://linux-hardware.org/?probe=93c3ab9ed1) | Nov 18, 2021 |
| Gigabyte   | H97M-D3H                    | [f6dc8337e7](https://linux-hardware.org/?probe=f6dc8337e7) | Nov 18, 2021 |
| MSI        | Z77A-G43                    | [04db0a2350](https://linux-hardware.org/?probe=04db0a2350) | Nov 17, 2021 |
| ASRock     | X470 Master SLI             | [c48f95d233](https://linux-hardware.org/?probe=c48f95d233) | Nov 17, 2021 |
| Gigabyte   | H370M DS3H-CF               | [c69f79e654](https://linux-hardware.org/?probe=c69f79e654) | Nov 17, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII IMPAC... | [ddfb1c2b1a](https://linux-hardware.org/?probe=ddfb1c2b1a) | Nov 17, 2021 |
| Dell       | 0GY6Y8 A02                  | [61734716ea](https://linux-hardware.org/?probe=61734716ea) | Nov 16, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [9404dfb1fe](https://linux-hardware.org/?probe=9404dfb1fe) | Nov 16, 2021 |
| Gigabyte   | X570 AORUS MASTER           | [3412d5cf0b](https://linux-hardware.org/?probe=3412d5cf0b) | Nov 16, 2021 |
| Gigabyte   | X570 AORUS MASTER           | [bdd9599f2f](https://linux-hardware.org/?probe=bdd9599f2f) | Nov 16, 2021 |
| ASUSTek    | M2N-E                       | [8da42387a5](https://linux-hardware.org/?probe=8da42387a5) | Nov 15, 2021 |
| Gigabyte   | B560M DS3H                  | [97ed26b846](https://linux-hardware.org/?probe=97ed26b846) | Nov 15, 2021 |
| ASRock     | B450 Pro4                   | [098387cb9c](https://linux-hardware.org/?probe=098387cb9c) | Nov 15, 2021 |
| Gigabyte   | GA-78LMT-USB3               | [bc6a3771aa](https://linux-hardware.org/?probe=bc6a3771aa) | Nov 13, 2021 |
| ASUSTek    | M3A78-EM                    | [e1cc8b1ee3](https://linux-hardware.org/?probe=e1cc8b1ee3) | Nov 13, 2021 |
| ASUSTek    | H61M-CS                     | [22858e9ab9](https://linux-hardware.org/?probe=22858e9ab9) | Nov 13, 2021 |
| Apple      | Mac-F221BEC8                | [5991ba5f44](https://linux-hardware.org/?probe=5991ba5f44) | Nov 12, 2021 |
| ASUSTek    | TUF B450M-PLUS GAMING       | [e85856bbef](https://linux-hardware.org/?probe=e85856bbef) | Nov 12, 2021 |
| Dell       | 0DXJD9 A00                  | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| Intel      | D33217GKE G69901-205        | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| MSI        | Z390-A PRO                  | [ca1489298b](https://linux-hardware.org/?probe=ca1489298b) | Nov 10, 2021 |
| Gigabyte   | X570 UD                     | [c5ae0c1fca](https://linux-hardware.org/?probe=c5ae0c1fca) | Nov 09, 2021 |
| Gigabyte   | Z390 I AORUS PRO WIFI-CF    | [189e19c60d](https://linux-hardware.org/?probe=189e19c60d) | Nov 09, 2021 |
| Dell       | 040DDP A01                  | [3587a95d63](https://linux-hardware.org/?probe=3587a95d63) | Nov 09, 2021 |
| Intel      | D33217GKE G69901-205        | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| Dell       | 0HD5W2 A00                  | [09cae8a245](https://linux-hardware.org/?probe=09cae8a245) | Nov 09, 2021 |
| HP         | 2215                        | [4e65fa6078](https://linux-hardware.org/?probe=4e65fa6078) | Nov 09, 2021 |
| Gigabyte   | EP45-DS3L                   | [fdbec54288](https://linux-hardware.org/?probe=fdbec54288) | Nov 08, 2021 |
| Gigabyte   | H97M-D3H                    | [74b5acd6cd](https://linux-hardware.org/?probe=74b5acd6cd) | Nov 08, 2021 |
| ASRock     | A300M-STX                   | [a7510caa6d](https://linux-hardware.org/?probe=a7510caa6d) | Nov 08, 2021 |
| ASRock     | A300M-STX                   | [2eebb6842a](https://linux-hardware.org/?probe=2eebb6842a) | Nov 08, 2021 |
| Seco       | C40 C                       | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI        | X570-A PRO                  | [0e47ec7819](https://linux-hardware.org/?probe=0e47ec7819) | Nov 08, 2021 |
| ASUSTek    | PRIME B550M-A               | [ef16e3ad0f](https://linux-hardware.org/?probe=ef16e3ad0f) | Nov 07, 2021 |
| Gigabyte   | EP45-DS3L                   | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| Dell       | 0C522T A03                  | [43d8e3d9d8](https://linux-hardware.org/?probe=43d8e3d9d8) | Nov 07, 2021 |
| ABIT       | AX78                        | [3d56ae3738](https://linux-hardware.org/?probe=3d56ae3738) | Nov 06, 2021 |
| MSI        | MEG X570 UNIFY              | [37685b5198](https://linux-hardware.org/?probe=37685b5198) | Nov 06, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [6cce11439f](https://linux-hardware.org/?probe=6cce11439f) | Nov 06, 2021 |
| ASUSTek    | M5A97                       | [f8ce8bca36](https://linux-hardware.org/?probe=f8ce8bca36) | Nov 05, 2021 |
| MSI        | Z97M-G43                    | [7b0e15a051](https://linux-hardware.org/?probe=7b0e15a051) | Nov 05, 2021 |
| ASUSTek    | Z170 PRO GAMING             | [ad6e327cf5](https://linux-hardware.org/?probe=ad6e327cf5) | Nov 05, 2021 |
| ASRock     | G41M-VS3                    | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| Gigabyte   | H97M-D3H                    | [fa84d0d544](https://linux-hardware.org/?probe=fa84d0d544) | Nov 04, 2021 |
| ASUSTek    | PRIME Z370-P                | [50301dd3e3](https://linux-hardware.org/?probe=50301dd3e3) | Nov 04, 2021 |
| Gigabyte   | B150M-D3H-CF                | [f5ef935897](https://linux-hardware.org/?probe=f5ef935897) | Nov 04, 2021 |
| Gigabyte   | H61M-S2V-B3                 | [5baf0ce3af](https://linux-hardware.org/?probe=5baf0ce3af) | Nov 04, 2021 |
| Lenovo     | MAHOBAY Win8 Pro DPK TPG    | [14c9dda4cd](https://linux-hardware.org/?probe=14c9dda4cd) | Nov 04, 2021 |
| MSI        | B450M MORTAR                | [00a97d0eba](https://linux-hardware.org/?probe=00a97d0eba) | Nov 03, 2021 |
| Dell       | 0YNVJG A01                  | [0243b19a08](https://linux-hardware.org/?probe=0243b19a08) | Nov 03, 2021 |
| Dell       | 0YNVJG A01                  | [f7d58b572d](https://linux-hardware.org/?probe=f7d58b572d) | Nov 03, 2021 |
| ASUSTek    | P8Z77-V                     | [c7a18968cf](https://linux-hardware.org/?probe=c7a18968cf) | Nov 03, 2021 |
| ASUSTek    | Z87M-PLUS                   | [c26ea680eb](https://linux-hardware.org/?probe=c26ea680eb) | Nov 03, 2021 |
| Gigabyte   | Z170-D3H-CF                 | [3acf5c243f](https://linux-hardware.org/?probe=3acf5c243f) | Nov 03, 2021 |
| MSI        | MAG B550M MORTAR            | [10a45363fe](https://linux-hardware.org/?probe=10a45363fe) | Nov 03, 2021 |
| ASRock     | G41M-VS3                    | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| MSI        | B365M PRO-VH                | [c2976ad59c](https://linux-hardware.org/?probe=c2976ad59c) | Nov 03, 2021 |
| MSI        | B450 GAMING PRO CARBON A... | [c8716ec9a6](https://linux-hardware.org/?probe=c8716ec9a6) | Nov 03, 2021 |
| MSI        | MPG X570 GAMING PRO CARB... | [93de1508cb](https://linux-hardware.org/?probe=93de1508cb) | Oct 31, 2021 |
| Lenovo     | 1046 SDK0T08861 WIN 3305... | [136c409f1a](https://linux-hardware.org/?probe=136c409f1a) | Oct 27, 2021 |
| Lenovo     | 1046 SDK0T08861 WIN 3305... | [ae8daa788a](https://linux-hardware.org/?probe=ae8daa788a) | Oct 27, 2021 |
| MSI        | B550-A PRO                  | [91c5853577](https://linux-hardware.org/?probe=91c5853577) | Oct 25, 2021 |
| Fujitsu    | D3120-A1 S26361-D3120-A1    | [fac95138dc](https://linux-hardware.org/?probe=fac95138dc) | Oct 23, 2021 |
| Foxconn    | H81MXV FAB A                | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| ASUSTek    | PRIME B460M-A               | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| ASUSTek    | ROG STRIX B560-G GAMING ... | [746401b748](https://linux-hardware.org/?probe=746401b748) | Oct 18, 2021 |
| MSI        | B350 PC MATE                | [bc716e921b](https://linux-hardware.org/?probe=bc716e921b) | Oct 15, 2021 |
| Dell       | 0WMJ54 A01                  | [01ce3b252c](https://linux-hardware.org/?probe=01ce3b252c) | Oct 14, 2021 |
| ASUSTek    | PRIME B550M-A               | [2ff2eb607a](https://linux-hardware.org/?probe=2ff2eb607a) | Oct 14, 2021 |
| ASUSTek    | PRIME A320I-K               | [eee2a960f5](https://linux-hardware.org/?probe=eee2a960f5) | Oct 11, 2021 |
| ASUSTek    | PRIME B350-PLUS             | [7b26df9bc4](https://linux-hardware.org/?probe=7b26df9bc4) | Oct 10, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek    | ROG Maximus XI FORMULA      | [cfbe862160](https://linux-hardware.org/?probe=cfbe862160) | Oct 10, 2021 |
| Fujitsu    | D3220-A1 S26361-D3220-A1    | [a9ceb4591e](https://linux-hardware.org/?probe=a9ceb4591e) | Oct 09, 2021 |
| Fujitsu    | D3220-A1 S26361-D3220-A1    | [7c210a60ab](https://linux-hardware.org/?probe=7c210a60ab) | Oct 09, 2021 |
| Gigabyte   | H61N-USB3                   | [43ded3a853](https://linux-hardware.org/?probe=43ded3a853) | Oct 09, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [b3d0295208](https://linux-hardware.org/?probe=b3d0295208) | Oct 08, 2021 |
| Gigabyte   | H61N-USB3                   | [75d34f09c4](https://linux-hardware.org/?probe=75d34f09c4) | Oct 06, 2021 |
| MSI        | B550-A PRO                  | [17a03c217e](https://linux-hardware.org/?probe=17a03c217e) | Oct 04, 2021 |
| Gigabyte   | Z170-D3H-CF                 | [103d2198a4](https://linux-hardware.org/?probe=103d2198a4) | Sep 30, 2021 |
| Gigabyte   | Z170-D3H-CF                 | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| Gigabyte   | H81M-S2H                    | [b8c27bd56c](https://linux-hardware.org/?probe=b8c27bd56c) | Sep 28, 2021 |
| ASRock     | B450M-HDV R4.0              | [2f771e8271](https://linux-hardware.org/?probe=2f771e8271) | Sep 24, 2021 |
| ASUSTek    | TUF GAMING B550M-PLUS       | [e75373a634](https://linux-hardware.org/?probe=e75373a634) | Sep 23, 2021 |
| ASUSTek    | ROG STRIX B360-I GAMING     | [3875512e39](https://linux-hardware.org/?probe=3875512e39) | Sep 14, 2021 |
| ASUSTek    | ROG STRIX B360-I GAMING     | [4fb9ed180b](https://linux-hardware.org/?probe=4fb9ed180b) | Sep 14, 2021 |
| Dell       | 0WMJ54 A01                  | [3231b34d4d](https://linux-hardware.org/?probe=3231b34d4d) | Aug 24, 2021 |
| Dell       | 0WMJ54 A01                  | [a94ad8a323](https://linux-hardware.org/?probe=a94ad8a323) | Aug 22, 2021 |
| HP         | 8055                        | [29f5b9a7ab](https://linux-hardware.org/?probe=29f5b9a7ab) | Aug 12, 2021 |
| Dell       | 0KC9NP A01                  | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| Dell       | 0KC9NP A01                  | [f48bc9ac9d](https://linux-hardware.org/?probe=f48bc9ac9d) | Aug 07, 2021 |
| ASUSTek    | Maximus V FORMULA           | [466ef3bd27](https://linux-hardware.org/?probe=466ef3bd27) | Jul 29, 2021 |
| Dell       | 0KC9NP A01                  | [7dcd16d3fd](https://linux-hardware.org/?probe=7dcd16d3fd) | Jul 14, 2021 |
| Dell       | 0KC9NP A01                  | [eedd464065](https://linux-hardware.org/?probe=eedd464065) | Jul 14, 2021 |
| Dell       | 0KC9NP A01                  | [8d1e68aad0](https://linux-hardware.org/?probe=8d1e68aad0) | Jul 07, 2021 |
| Dell       | 0KC9NP A01                  | [852a8a103d](https://linux-hardware.org/?probe=852a8a103d) | Jul 04, 2021 |
| Dell       | 0KC9NP A01                  | [3a0ca9b90c](https://linux-hardware.org/?probe=3a0ca9b90c) | Jul 01, 2021 |
| Dell       | 0KC9NP A01                  | [3ed1ee1f81](https://linux-hardware.org/?probe=3ed1ee1f81) | Jun 25, 2021 |
| Dell       | 0KC9NP A01                  | [f611d9ec88](https://linux-hardware.org/?probe=f611d9ec88) | Jun 23, 2021 |
| ASUSTek    | Maximus V FORMULA           | [95ba18d5da](https://linux-hardware.org/?probe=95ba18d5da) | Jun 23, 2021 |
| Dell       | 0KC9NP A01                  | [511e8019e0](https://linux-hardware.org/?probe=511e8019e0) | Jun 19, 2021 |
| Dell       | 0KC9NP A01                  | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Gigabyte   | F2A88XN-WIFI                | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| ASUSTek    | Maximus V FORMULA           | [3e15dd7136](https://linux-hardware.org/?probe=3e15dd7136) | May 19, 2021 |
| ECS        | MCP61M-M3                   | [2e5b21af19](https://linux-hardware.org/?probe=2e5b21af19) | Apr 17, 2021 |
| ASUSTek    | PRIME X570-PRO              | [3f7cbcea74](https://linux-hardware.org/?probe=3f7cbcea74) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| 5.15.6-200.fc35.x86_64                                        | 28       | 14.66%  |
| 5.14.18-300.fc35.x86_64                                       | 20       | 10.47%  |
| 5.14.17-301.fc35.x86_64                                       | 17       | 8.9%    |
| 5.14.16-301.fc35.x86_64                                       | 17       | 8.9%    |
| 5.14.10-300.fc35.x86_64                                       | 15       | 7.85%   |
| 5.14.14-300.fc35.x86_64                                       | 14       | 7.33%   |
| 5.15.8-200.fc35.x86_64                                        | 12       | 6.28%   |
| 5.14.15-300.fc35.x86_64                                       | 11       | 5.76%   |
| 5.15.5-200.fc35.x86_64                                        | 5        | 2.62%   |
| 5.15.4-201.fc35.x86_64                                        | 5        | 2.62%   |
| 5.15.11-200.fc35.x86_64                                       | 5        | 2.62%   |
| 5.15.10-200.fc35.x86_64                                       | 5        | 2.62%   |
| 5.14.9-300.fc35.x86_64                                        | 5        | 2.62%   |
| 5.15.7-200.fc35.x86_64                                        | 4        | 2.09%   |
| 5.14.0-60.fc35.x86_64                                         | 3        | 1.57%   |
| 5.12.0-0.rc7.189.fc35.x86_64                                  | 2        | 1.05%   |
| 5.16.0-0.rc6.41.vanilla.1.fc35.x86_64                         | 1        | 0.52%   |
| 5.16.0-0.rc2.18.vanilla.1.fc35.x86_64                         | 1        | 0.52%   |
| 5.16.0-0.rc1.20211115git8ab774587903.14.vanilla.1.fc35.x86_64 | 1        | 0.52%   |
| 5.15.5-xm1tt.0.fc35.x86_64                                    | 1        | 0.52%   |
| 5.15.4-xm1.0.fc35.x86_64                                      | 1        | 0.52%   |
| 5.15.2_tkg_bmq                                                | 1        | 0.52%   |
| 5.15.0-500.chinfo.fc35.x86_64                                 | 1        | 0.52%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.vanilla.1.fc35.x86_64 | 1        | 0.52%   |
| 5.14.8-lqx1.0.fc35.x86_64                                     | 1        | 0.52%   |
| 5.14.7-300.fc35.x86_64                                        | 1        | 0.52%   |
| 5.14.6-300.fc35.x86_64                                        | 1        | 0.52%   |
| 5.14.20-300.fc35.x86_64                                       | 1        | 0.52%   |
| 5.14.18-301.fsync.fc35.x86_64                                 | 1        | 0.52%   |
| 5.14.13_MY                                                    | 1        | 0.52%   |
| 5.14.1-300.fc35.x86_64                                        | 1        | 0.52%   |
| 5.14.0-0.rc6.46.fc35.x86_64                                   | 1        | 0.52%   |
| 5.13.7-200.fc34.x86_64                                        | 1        | 0.52%   |
| 5.13.0-58.fc35.x86_64                                         | 1        | 0.52%   |
| 5.13.0-0.rc7.20210623git0c18f29aae7c.53.fc35.x86_64           | 1        | 0.52%   |
| 5.13.0-0.rc6.45.fc35.x86_64                                   | 1        | 0.52%   |
| 5.13.0-0.rc2.20210521git79a106fc6585.22.fc35.x86_64           | 1        | 0.52%   |
| 5.13.0-0.rc2.19.fc35.x86_64                                   | 1        | 0.52%   |
| 5.13.0-0.rc1.13.fc35.x86_64                                   | 1        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.6  | 28       | 14.97%  |
| 5.14.18 | 21       | 11.23%  |
| 5.14.17 | 17       | 9.09%   |
| 5.14.16 | 17       | 9.09%   |
| 5.14.10 | 15       | 8.02%   |
| 5.14.14 | 14       | 7.49%   |
| 5.15.8  | 12       | 6.42%   |
| 5.14.15 | 11       | 5.88%   |
| 5.15.5  | 6        | 3.21%   |
| 5.15.4  | 6        | 3.21%   |
| 5.15.11 | 5        | 2.67%   |
| 5.15.10 | 5        | 2.67%   |
| 5.14.9  | 5        | 2.67%   |
| 5.15.7  | 4        | 2.14%   |
| 5.14.0  | 4        | 2.14%   |
| 5.13.0  | 3        | 1.6%    |
| 5.16.0  | 2        | 1.07%   |
| 5.15.0  | 2        | 1.07%   |
| 5.12.0  | 2        | 1.07%   |
| 5.15.2  | 1        | 0.53%   |
| 5.14.8  | 1        | 0.53%   |
| 5.14.7  | 1        | 0.53%   |
| 5.14.6  | 1        | 0.53%   |
| 5.14.20 | 1        | 0.53%   |
| 5.14.13 | 1        | 0.53%   |
| 5.14.1  | 1        | 0.53%   |
| 5.13.7  | 1        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 108      | 58.7%   |
| 5.15    | 68       | 36.96%  |
| 5.13    | 4        | 2.17%   |
| 5.16    | 2        | 1.09%   |
| 5.12    | 2        | 1.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 177      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 128      | 71.51%  |
| KDE5          | 23       | 12.85%  |
| Unknown       | 10       | 5.59%   |
| X-Cinnamon    | 6        | 3.35%   |
| MATE          | 5        | 2.79%   |
| XFCE          | 3        | 1.68%   |
| KDE           | 2        | 1.12%   |
| LXDE          | 1        | 0.56%   |
| GNOME Classic | 1        | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 92       | 51.11%  |
| X11     | 78       | 43.33%  |
| Tty     | 6        | 3.33%   |
| Unknown | 4        | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 102      | 57.63%  |
| GDM     | 49       | 27.68%  |
| SDDM    | 13       | 7.34%   |
| LightDM | 13       | 7.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 85       | 48.02%  |
| ru_RU      | 15       | 8.47%   |
| de_DE      | 10       | 5.65%   |
| pt_BR      | 8        | 4.52%   |
| en_GB      | 8        | 4.52%   |
| es_ES      | 7        | 3.95%   |
| fr_FR      | 6        | 3.39%   |
| en_CA      | 4        | 2.26%   |
| pl_PL      | 3        | 1.69%   |
| ru_UA      | 2        | 1.13%   |
| it_IT      | 2        | 1.13%   |
| es_MX      | 2        | 1.13%   |
| es_CO      | 2        | 1.13%   |
| es_CL      | 2        | 1.13%   |
| en_AU      | 2        | 1.13%   |
| cs_CZ      | 2        | 1.13%   |
| sv_SE      | 1        | 0.56%   |
| pt_PT      | 1        | 0.56%   |
| pa_IN      | 1        | 0.56%   |
| nl_BE      | 1        | 0.56%   |
| ja_JP      | 1        | 0.56%   |
| hu_HU      | 1        | 0.56%   |
| fr_CH      | 1        | 0.56%   |
| es_VE      | 1        | 0.56%   |
| en_US.UTF8 | 1        | 0.56%   |
| en_NZ      | 1        | 0.56%   |
| en_IN      | 1        | 0.56%   |
| en_IL      | 1        | 0.56%   |
| en_IE      | 1        | 0.56%   |
| de_CH      | 1        | 0.56%   |
| ca_ES      | 1        | 0.56%   |
| ar_SA      | 1        | 0.56%   |
| Unknown    | 1        | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 115      | 64.97%  |
| BIOS | 62       | 35.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 121      | 67.98%  |
| Ext4  | 52       | 29.21%  |
| Xfs   | 4        | 2.25%   |
| Ext3  | 1        | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 98       | 55.06%  |
| GPT     | 65       | 36.52%  |
| MBR     | 15       | 8.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 156      | 87.64%  |
| Yes       | 22       | 12.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 79.33%  |
| Yes       | 37       | 20.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 45       | 25.42%  |
| ASUSTek Computer    | 45       | 25.42%  |
| MSI                 | 33       | 18.64%  |
| Dell                | 15       | 8.47%   |
| Hewlett-Packard     | 8        | 4.52%   |
| ASRock              | 8        | 4.52%   |
| Lenovo              | 5        | 2.82%   |
| XFX                 | 2        | 1.13%   |
| Intel               | 2        | 1.13%   |
| Fujitsu             | 2        | 1.13%   |
| ECS                 | 2        | 1.13%   |
| Apple               | 2        | 1.13%   |
| Supermicro          | 1        | 0.56%   |
| Seco                | 1        | 0.56%   |
| Pegatron            | 1        | 0.56%   |
| JINGSHA             | 1        | 0.56%   |
| Huanan              | 1        | 0.56%   |
| Gateway             | 1        | 0.56%   |
| Foxconn             | 1        | 0.56%   |
| ABIT                | 1        | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 5        | 2.82%   |
| MSI MS-7C56                            | 3        | 1.69%   |
| MSI MS-7C91                            | 2        | 1.13%   |
| MSI MS-7C52                            | 2        | 1.13%   |
| MSI MS-7B93                            | 2        | 1.13%   |
| MSI MS-7B10                            | 2        | 1.13%   |
| MSI MS-7A33                            | 2        | 1.13%   |
| Gigabyte Z390 I AORUS PRO WIFI         | 2        | 1.13%   |
| Gigabyte X570 AORUS MASTER             | 2        | 1.13%   |
| Gigabyte H97M-D3H                      | 2        | 1.13%   |
| Gigabyte B450M DS3H                    | 2        | 1.13%   |
| Dell OptiPlex 7010                     | 2        | 1.13%   |
| Dell OptiPlex 3020                     | 2        | 1.13%   |
| ASUS TUF GAMING B550-PLUS              | 2        | 1.13%   |
| Apple MacPro5,1                        | 2        | 1.13%   |
| XFX nForce 780i 3-Way SLI              | 1        | 0.56%   |
| XFX MI-A78S-8209 Ver1.1                | 1        | 0.56%   |
| Supermicro PIO-617R-TLN4F+-ST031       | 1        | 0.56%   |
| Seco C40                               | 1        | 0.56%   |
| Pegatron h9-1350                       | 1        | 0.56%   |
| MSI MS-7D25                            | 1        | 0.56%   |
| MSI MS-7C95                            | 1        | 0.56%   |
| MSI MS-7C94                            | 1        | 0.56%   |
| MSI MS-7C37                            | 1        | 0.56%   |
| MSI MS-7C35                            | 1        | 0.56%   |
| MSI MS-7C31                            | 1        | 0.56%   |
| MSI MS-7C02                            | 1        | 0.56%   |
| MSI MS-7B98                            | 1        | 0.56%   |
| MSI MS-7B89                            | 1        | 0.56%   |
| MSI MS-7B86                            | 1        | 0.56%   |
| MSI MS-7B85                            | 1        | 0.56%   |
| MSI MS-7B77                            | 1        | 0.56%   |
| MSI MS-7B07                            | 1        | 0.56%   |
| MSI MS-7A34                            | 1        | 0.56%   |
| MSI MS-7A31                            | 1        | 0.56%   |
| MSI MS-7924                            | 1        | 0.56%   |
| MSI MS-7866                            | 1        | 0.56%   |
| MSI MS-7817                            | 1        | 0.56%   |
| MSI MS-7758                            | 1        | 0.56%   |
| MSI MS-7721                            | 1        | 0.56%   |
| Lenovo V55t-15ARE 11KG0004CK           | 1        | 0.56%   |
| Lenovo ThinkStation P620 30E0CTO1WW    | 1        | 0.56%   |
| Lenovo ThinkCentre M72z 3543A9G        | 1        | 0.56%   |
| Lenovo ThinkCentre M720s 10ST006UGE    | 1        | 0.56%   |
| Lenovo IdeaCentre 710-25ISH 90FB0001US | 1        | 0.56%   |
| Intel Inspire                          | 1        | 0.56%   |
| Intel D33217GKE G69901-205             | 1        | 0.56%   |
| Huanan X99-F8                          | 1        | 0.56%   |
| HP Z400 Workstation                    | 1        | 0.56%   |
| HP Z230 SFF Workstation                | 1        | 0.56%   |
| HP ProDesk 600 G2 SFF                  | 1        | 0.56%   |
| HP EliteDesk 800 G4 SFF                | 1        | 0.56%   |
| HP EliteDesk 800 G2 DM 35W             | 1        | 0.56%   |
| HP EliteDesk 705 G1 SFF                | 1        | 0.56%   |
| HP Compaq 6000 Pro SFF PC              | 1        | 0.56%   |
| HP 27-k350xt                           | 1        | 0.56%   |
| Gigabyte Z97P-D3                       | 1        | 0.56%   |
| Gigabyte Z77-D3H                       | 1        | 0.56%   |
| Gigabyte Z690 UD DDR4                  | 1        | 0.56%   |
| Gigabyte Z390 M                        | 1        | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Dell OptiPlex                    | 12       | 6.78%   |
| ASUS ROG                         | 12       | 6.78%   |
| ASUS PRIME                       | 9        | 5.08%   |
| Gigabyte X570                    | 6        | 3.39%   |
| ASUS TUF                         | 5        | 2.82%   |
| ASUS All                         | 5        | 2.82%   |
| MSI MS-7C56                      | 3        | 1.69%   |
| HP EliteDesk                     | 3        | 1.69%   |
| Gigabyte Z390                    | 3        | 1.69%   |
| MSI MS-7C91                      | 2        | 1.13%   |
| MSI MS-7C52                      | 2        | 1.13%   |
| MSI MS-7B93                      | 2        | 1.13%   |
| MSI MS-7B10                      | 2        | 1.13%   |
| MSI MS-7A33                      | 2        | 1.13%   |
| Lenovo ThinkCentre               | 2        | 1.13%   |
| Gigabyte TRX40                   | 2        | 1.13%   |
| Gigabyte H97M-D3H                | 2        | 1.13%   |
| Gigabyte B550                    | 2        | 1.13%   |
| Gigabyte B450M                   | 2        | 1.13%   |
| Gigabyte B450                    | 2        | 1.13%   |
| Fujitsu ESPRIMO                  | 2        | 1.13%   |
| ASUS Maximus                     | 2        | 1.13%   |
| Apple MacPro5                    | 2        | 1.13%   |
| XFX nForce                       | 1        | 0.56%   |
| XFX MI-A78S-8209                 | 1        | 0.56%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 0.56%   |
| Seco C40                         | 1        | 0.56%   |
| Pegatron h9-1350                 | 1        | 0.56%   |
| MSI MS-7D25                      | 1        | 0.56%   |
| MSI MS-7C95                      | 1        | 0.56%   |
| MSI MS-7C94                      | 1        | 0.56%   |
| MSI MS-7C37                      | 1        | 0.56%   |
| MSI MS-7C35                      | 1        | 0.56%   |
| MSI MS-7C31                      | 1        | 0.56%   |
| MSI MS-7C02                      | 1        | 0.56%   |
| MSI MS-7B98                      | 1        | 0.56%   |
| MSI MS-7B89                      | 1        | 0.56%   |
| MSI MS-7B86                      | 1        | 0.56%   |
| MSI MS-7B85                      | 1        | 0.56%   |
| MSI MS-7B77                      | 1        | 0.56%   |
| MSI MS-7B07                      | 1        | 0.56%   |
| MSI MS-7A34                      | 1        | 0.56%   |
| MSI MS-7A31                      | 1        | 0.56%   |
| MSI MS-7924                      | 1        | 0.56%   |
| MSI MS-7866                      | 1        | 0.56%   |
| MSI MS-7817                      | 1        | 0.56%   |
| MSI MS-7758                      | 1        | 0.56%   |
| MSI MS-7721                      | 1        | 0.56%   |
| Lenovo V55t-15ARE                | 1        | 0.56%   |
| Lenovo ThinkStation              | 1        | 0.56%   |
| Lenovo IdeaCentre                | 1        | 0.56%   |
| Intel Inspire                    | 1        | 0.56%   |
| Intel D33217GKE                  | 1        | 0.56%   |
| Huanan X99-F8                    | 1        | 0.56%   |
| HP Z400                          | 1        | 0.56%   |
| HP Z230                          | 1        | 0.56%   |
| HP ProDesk                       | 1        | 0.56%   |
| HP Compaq                        | 1        | 0.56%   |
| HP 27-k350xt                     | 1        | 0.56%   |
| Gigabyte Z97P-D3                 | 1        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 42       | 23.73%  |
| 2019 | 26       | 14.69%  |
| 2020 | 22       | 12.43%  |
| 2018 | 20       | 11.3%   |
| 2013 | 13       | 7.34%   |
| 2014 | 12       | 6.78%   |
| 2015 | 10       | 5.65%   |
| 2009 | 8        | 4.52%   |
| 2016 | 6        | 3.39%   |
| 2012 | 6        | 3.39%   |
| 2017 | 4        | 2.26%   |
| 2010 | 3        | 1.69%   |
| 2008 | 3        | 1.69%   |
| 2011 | 2        | 1.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 177      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 165      | 93.22%  |
| Enabled  | 12       | 6.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 177      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 51       | 28.81%  |
| 32.01-64.0  | 47       | 26.55%  |
| 8.01-16.0   | 30       | 16.95%  |
| 4.01-8.0    | 20       | 11.3%   |
| 64.01-256.0 | 13       | 7.34%   |
| 3.01-4.0    | 11       | 6.21%   |
| 24.01-32.0  | 2        | 1.13%   |
| 2.01-3.0    | 2        | 1.13%   |
| 1.01-2.0    | 1        | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 60       | 32.09%  |
| 4.01-8.0   | 52       | 27.81%  |
| 3.01-4.0   | 28       | 14.97%  |
| 1.01-2.0   | 24       | 12.83%  |
| 8.01-16.0  | 14       | 7.49%   |
| 0.51-1.0   | 4        | 2.14%   |
| 24.01-32.0 | 2        | 1.07%   |
| 16.01-24.0 | 2        | 1.07%   |
| 0.01-0.5   | 1        | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 53       | 29.94%  |
| 1      | 52       | 29.38%  |
| 3      | 41       | 23.16%  |
| 5      | 13       | 7.34%   |
| 6      | 7        | 3.95%   |
| 4      | 7        | 3.95%   |
| 7      | 2        | 1.13%   |
| 14     | 1        | 0.56%   |
| 9      | 1        | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 62.36%  |
| Yes       | 67       | 37.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 177      | 99.44%  |
| No        | 1        | 0.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 52.54%  |
| Yes       | 84       | 47.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 55.93%  |
| Yes       | 78       | 44.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 35       | 19.77%  |
| Germany      | 15       | 8.47%   |
| Russia       | 14       | 7.91%   |
| Spain        | 10       | 5.65%   |
| Brazil       | 10       | 5.65%   |
| Canada       | 8        | 4.52%   |
| Poland       | 6        | 3.39%   |
| France       | 6        | 3.39%   |
| UK           | 5        | 2.82%   |
| Romania      | 5        | 2.82%   |
| Ukraine      | 4        | 2.26%   |
| Switzerland  | 4        | 2.26%   |
| India        | 4        | 2.26%   |
| Mexico       | 3        | 1.69%   |
| Italy        | 3        | 1.69%   |
| Hong Kong    | 3        | 1.69%   |
| Czechia      | 3        | 1.69%   |
| Chile        | 3        | 1.69%   |
| Belgium      | 3        | 1.69%   |
| Belarus      | 3        | 1.69%   |
| Sweden       | 2        | 1.13%   |
| Norway       | 2        | 1.13%   |
| Netherlands  | 2        | 1.13%   |
| Israel       | 2        | 1.13%   |
| Greece       | 2        | 1.13%   |
| Colombia     | 2        | 1.13%   |
| Austria      | 2        | 1.13%   |
| Australia    | 2        | 1.13%   |
| Yemen        | 1        | 0.56%   |
| Venezuela    | 1        | 0.56%   |
| Turkey       | 1        | 0.56%   |
| Slovakia     | 1        | 0.56%   |
| Saudi Arabia | 1        | 0.56%   |
| New Zealand  | 1        | 0.56%   |
| Kyrgyzstan   | 1        | 0.56%   |
| Kazakhstan   | 1        | 0.56%   |
| Japan        | 1        | 0.56%   |
| Ireland      | 1        | 0.56%   |
| Indonesia    | 1        | 0.56%   |
| Hungary      | 1        | 0.56%   |
| Estonia      | 1        | 0.56%   |
| Cyprus       | 1        | 0.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Moscow                      | 5        | 2.78%   |
| Berlin                      | 4        | 2.22%   |
| Minsk                       | 3        | 1.67%   |
| Weinsberg                   | 2        | 1.11%   |
| Vienna                      | 2        | 1.11%   |
| Ufa                         | 2        | 1.11%   |
| Timi?�oara                  | 2        | 1.11%   |
| S??o Paulo                  | 2        | 1.11%   |
| Los Angeles                 | 2        | 1.11%   |
| Kyiv                        | 2        | 1.11%   |
| Bainbridge Island           | 2        | 1.11%   |
| Athens                      | 2        | 1.11%   |
| Amsterdam                   | 2        | 1.11%   |
| Zurich                      | 1        | 0.56%   |
| Zapopan                     | 1        | 0.56%   |
| Yekaterinburg               | 1        | 0.56%   |
| Winterthur                  | 1        | 0.56%   |
| Wilmington                  | 1        | 0.56%   |
| Willowbrook                 | 1        | 0.56%   |
| Westerronfeld               | 1        | 0.56%   |
| Waynesville                 | 1        | 0.56%   |
| Warsaw                      | 1        | 0.56%   |
| Voronezh                    | 1        | 0.56%   |
| Volgograd                   | 1        | 0.56%   |
| Vinnytsia                   | 1        | 0.56%   |
| Villavicencio               | 1        | 0.56%   |
| Verrieres-le-Buisson        | 1        | 0.56%   |
| Veresegyhaz                 | 1        | 0.56%   |
| Vancouver                   | 1        | 0.56%   |
| Valencia                    | 1        | 0.56%   |
| Vaellingby                  | 1        | 0.56%   |
| Ulan-Ude                    | 1        | 0.56%   |
| Udine                       | 1        | 0.56%   |
| Tung Chung                  | 1        | 0.56%   |
| Trois-Rivi??res             | 1        | 0.56%   |
| Toulouse                    | 1        | 0.56%   |
| Tlajomulco de Zuniga        | 1        | 0.56%   |
| Tikhoretsk                  | 1        | 0.56%   |
| Temple                      | 1        | 0.56%   |
| Tartu                       | 1        | 0.56%   |
| Tampa                       | 1        | 0.56%   |
| Sunderland                  | 1        | 0.56%   |
| Stuttgart                   | 1        | 0.56%   |
| Stavanger                   | 1        | 0.56%   |
| Somerville                  | 1        | 0.56%   |
| Serra                       | 1        | 0.56%   |
| Seattle                     | 1        | 0.56%   |
| Saskatoon                   | 1        | 0.56%   |
| Sanlucar la Mayor           | 1        | 0.56%   |
| Sanaa                       | 1        | 0.56%   |
| San Sebasti??n de los Reyes | 1        | 0.56%   |
| San Jose                    | 1        | 0.56%   |
| Roznov pod Radhostem        | 1        | 0.56%   |
| Roquetas de Mar             | 1        | 0.56%   |
| Romont                      | 1        | 0.56%   |
| Rome                        | 1        | 0.56%   |
| Regina                      | 1        | 0.56%   |
| Raleigh                     | 1        | 0.56%   |
| Providencia                 | 1        | 0.56%   |
| Prospect Park               | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 67       | 105    | 19.2%   |
| Samsung Electronics         | 65       | 111    | 18.62%  |
| WDC                         | 63       | 102    | 18.05%  |
| Kingston                    | 25       | 28     | 7.16%   |
| Crucial                     | 21       | 21     | 6.02%   |
| SanDisk                     | 17       | 17     | 4.87%   |
| Toshiba                     | 13       | 18     | 3.72%   |
| A-DATA Technology           | 9        | 12     | 2.58%   |
| SPCC                        | 7        | 9      | 2.01%   |
| Phison                      | 6        | 10     | 1.72%   |
| Silicon Motion              | 5        | 5      | 1.43%   |
| Patriot                     | 5        | 5      | 1.43%   |
| Hitachi                     | 5        | 5      | 1.43%   |
| Unknown                     | 4        | 4      | 1.15%   |
| GOODRAM                     | 4        | 4      | 1.15%   |
| XPG                         | 3        | 5      | 0.86%   |
| Intel                       | 3        | 4      | 0.86%   |
| Realtek Semiconductor       | 2        | 2      | 0.57%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.57%   |
| Corsair                     | 2        | 2      | 0.57%   |
| Apacer                      | 2        | 2      | 0.57%   |
| USB 3.0                     | 1        | 2      | 0.29%   |
| T-FORCE                     | 1        | 1      | 0.29%   |
| SUNEAST                     | 1        | 1      | 0.29%   |
| SK Hynix                    | 1        | 1      | 0.29%   |
| SABRENT                     | 1        | 1      | 0.29%   |
| PNY                         | 1        | 1      | 0.29%   |
| PLEXTOR                     | 1        | 1      | 0.29%   |
| OWC                         | 1        | 1      | 0.29%   |
| Mushkin                     | 1        | 1      | 0.29%   |
| Micron/Crucial Technology   | 1        | 1      | 0.29%   |
| Micron Technology           | 1        | 1      | 0.29%   |
| MAXTOR                      | 1        | 1      | 0.29%   |
| LS600                       | 1        | 1      | 0.29%   |
| Lexar                       | 1        | 1      | 0.29%   |
| Intenso                     | 1        | 4      | 0.29%   |
| Hewlett-Packard             | 1        | 1      | 0.29%   |
| Dahua                       | 1        | 1      | 0.29%   |
| China                       | 1        | 1      | 0.29%   |
| Unknown                     | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB         | 13       | 3.03%   |
| Seagate ST2000DM008-2FR102 2TB       | 9        | 2.1%    |
| Samsung SSD 860 EVO 500GB            | 8        | 1.86%   |
| Seagate ST1000DM010-2EP102 1TB       | 7        | 1.63%   |
| Kingston SA400S37480G 480GB SSD      | 6        | 1.4%    |
| Seagate ST500DM002-1BD142 500GB      | 5        | 1.17%   |
| Samsung SSD 970 EVO Plus 500GB       | 5        | 1.17%   |
| Seagate ST1000DM003-1ER162 1TB       | 4        | 0.93%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3        | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3        | 0.7%    |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 3        | 0.7%    |
| WDC WD5000AADS-00S9B0 500GB          | 3        | 0.7%    |
| WDC WD30EFRX-68EUZN0 3TB             | 3        | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB             | 3        | 0.7%    |
| WDC WD1002FAEX-00Z3A0 1TB            | 3        | 0.7%    |
| Seagate ST8000DM004-2CX188 8TB       | 3        | 0.7%    |
| Seagate ST31000528AS 1TB             | 3        | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB       | 3        | 0.7%    |
| Sandisk NVMe SSD Drive 500GB         | 3        | 0.7%    |
| Samsung SSD 970 EVO 250GB            | 3        | 0.7%    |
| Samsung SSD 870 EVO 1TB              | 3        | 0.7%    |
| Samsung SSD 860 EVO 1TB              | 3        | 0.7%    |
| Samsung SSD 850 EVO 250GB            | 3        | 0.7%    |
| Samsung NVMe SSD Drive 2TB           | 3        | 0.7%    |
| Samsung NVMe SSD Drive 250GB         | 3        | 0.7%    |
| Samsung NVMe SSD Drive 1TB           | 3        | 0.7%    |
| Phison NVMe SSD Drive 2TB            | 3        | 0.7%    |
| Kingston SV300S37A120G 120GB SSD     | 3        | 0.7%    |
| Kingston SA400S37240G 240GB SSD      | 3        | 0.7%    |
| Crucial CT480BX500SSD1 480GB         | 3        | 0.7%    |
| Crucial CT1000MX500SSD1 1TB          | 3        | 0.7%    |
| WDC WDS100T3X0C-00SJG0 1TB           | 2        | 0.47%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2        | 0.47%   |
| WDC WD40EZRZ-00WN9B0 4TB             | 2        | 0.47%   |
| WDC WD2500AAKX-753CA1 250GB          | 2        | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2        | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB             | 2        | 0.47%   |
| Unknown MMC Card  32GB               | 2        | 0.47%   |
| Toshiba HDWD120 2TB                  | 2        | 0.47%   |
| Toshiba DT01ACA200 2TB               | 2        | 0.47%   |
| Toshiba DT01ACA050 500GB             | 2        | 0.47%   |
| SPCC M.2 PCIe SSD 256GB              | 2        | 0.47%   |
| Silicon Motion NVMe SSD Drive 2TB    | 2        | 0.47%   |
| Silicon Motion NVMe SSD Drive 1024GB | 2        | 0.47%   |
| Seagate ST4000DM005-2DP166 4TB       | 2        | 0.47%   |
| Seagate ST4000DM004-2CV104 4TB       | 2        | 0.47%   |
| Seagate ST3500630AS 500GB            | 2        | 0.47%   |
| Seagate ST3500418AS 500GB            | 2        | 0.47%   |
| Seagate ST3000DM008-2DM166 3TB       | 2        | 0.47%   |
| Seagate ST2000DL003-9VT166 2TB       | 2        | 0.47%   |
| SanDisk SSD PLUS 240GB               | 2        | 0.47%   |
| Sandisk NVMe SSD Drive 1TB           | 2        | 0.47%   |
| Samsung SSD 970 EVO Plus 2TB         | 2        | 0.47%   |
| Samsung SSD 860 EVO 250GB            | 2        | 0.47%   |
| Samsung SSD 850 PRO 256GB            | 2        | 0.47%   |
| Samsung SSD 850 EVO 500GB            | 2        | 0.47%   |
| Samsung SSD 850 EVO 1TB              | 2        | 0.47%   |
| Samsung SSD 840 PRO Series 256GB     | 2        | 0.47%   |
| Samsung HD103UJ 1TB                  | 2        | 0.47%   |
| Patriot Burst 120GB SSD              | 2        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 65       | 103    | 47.1%   |
| WDC                 | 49       | 78     | 35.51%  |
| Toshiba             | 12       | 15     | 8.7%    |
| Samsung Electronics | 5        | 6      | 3.62%   |
| Hitachi             | 5        | 5      | 3.62%   |
| USB 3.0             | 1        | 2      | 0.72%   |
| MAXTOR              | 1        | 1      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 36       | 59     | 26.09%  |
| Kingston            | 18       | 20     | 13.04%  |
| Crucial             | 18       | 18     | 13.04%  |
| WDC                 | 14       | 18     | 10.14%  |
| SanDisk             | 10       | 10     | 7.25%   |
| A-DATA Technology   | 7        | 10     | 5.07%   |
| Patriot             | 5        | 5      | 3.62%   |
| SPCC                | 4        | 5      | 2.9%    |
| GOODRAM             | 4        | 4      | 2.9%    |
| Apacer              | 2        | 2      | 1.45%   |
| XPG                 | 1        | 2      | 0.72%   |
| Unknown             | 1        | 1      | 0.72%   |
| Toshiba             | 1        | 1      | 0.72%   |
| T-FORCE             | 1        | 1      | 0.72%   |
| SUNEAST             | 1        | 1      | 0.72%   |
| Seagate             | 1        | 1      | 0.72%   |
| SABRENT             | 1        | 1      | 0.72%   |
| PNY                 | 1        | 1      | 0.72%   |
| PLEXTOR             | 1        | 1      | 0.72%   |
| OWC                 | 1        | 1      | 0.72%   |
| Mushkin             | 1        | 1      | 0.72%   |
| Micron Technology   | 1        | 1      | 0.72%   |
| LS600               | 1        | 1      | 0.72%   |
| Lexar               | 1        | 1      | 0.72%   |
| Intenso             | 1        | 4      | 0.72%   |
| Intel               | 1        | 1      | 0.72%   |
| Hewlett-Packard     | 1        | 1      | 0.72%   |
| Dahua               | 1        | 1      | 0.72%   |
| Corsair             | 1        | 1      | 0.72%   |
| China               | 1        | 1      | 0.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 111      | 210    | 38.01%  |
| SSD     | 106      | 175    | 36.3%   |
| NVMe    | 70       | 106    | 23.97%  |
| MMC     | 3        | 3      | 1.03%   |
| Unknown | 2        | 2      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 152      | 379    | 65.52%  |
| NVMe | 70       | 106    | 30.17%  |
| SAS  | 7        | 8      | 3.02%   |
| MMC  | 3        | 3      | 1.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 114      | 177    | 44.53%  |
| 0.51-1.0   | 71       | 109    | 27.73%  |
| 1.01-2.0   | 35       | 38     | 13.67%  |
| 3.01-4.0   | 13       | 15     | 5.08%   |
| 2.01-3.0   | 12       | 28     | 4.69%   |
| 4.01-10.0  | 10       | 16     | 3.91%   |
| 10.01-20.0 | 1        | 2      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 40       | 22.35%  |
| 1001-2000      | 31       | 17.32%  |
| 101-250        | 28       | 15.64%  |
| More than 3000 | 25       | 13.97%  |
| 251-500        | 22       | 12.29%  |
| 2001-3000      | 17       | 9.5%    |
| 1-20           | 6        | 3.35%   |
| Unknown        | 5        | 2.79%   |
| 51-100         | 4        | 2.23%   |
| 21-50          | 1        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 34       | 18.89%  |
| 251-500        | 24       | 13.33%  |
| 21-50          | 23       | 12.78%  |
| 501-1000       | 23       | 12.78%  |
| 101-250        | 19       | 10.56%  |
| 51-100         | 19       | 10.56%  |
| 1001-2000      | 17       | 9.44%   |
| More than 3000 | 9        | 5%      |
| 2001-3000      | 7        | 3.89%   |
| Unknown        | 5        | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Desktops | Drives | Percent |
|-----------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 4        | 6      | 14.81%  |
| WDC WD30EZRX-00MMMB0 3TB                            | 1        | 1      | 3.7%    |
| WDC WD2500AAKX-753CA1 250GB                         | 1        | 1      | 3.7%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 1        | 1      | 3.7%    |
| WDC WD10EFRX-68JCSN0 1TB                            | 1        | 1      | 3.7%    |
| WDC WD1003FBYX-01Y7B1 1TB                           | 1        | 1      | 3.7%    |
| WDC WD1002FAEX-00Z3A0 1TB                           | 1        | 1      | 3.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1        | 1      | 3.7%    |
| Seagate ST500LM000-1EJ162-SSHD 500GB                | 1        | 1      | 3.7%    |
| Seagate ST3500630AS 500GB                           | 1        | 1      | 3.7%    |
| Seagate ST3200822A 200GB                            | 1        | 1      | 3.7%    |
| Seagate ST31000528AS 1TB                            | 1        | 1      | 3.7%    |
| Seagate ST31000524AS 1TB                            | 1        | 1      | 3.7%    |
| Seagate ST3000DM001-1ER166 3TB                      | 1        | 1      | 3.7%    |
| Seagate ST2000DL003-9VT166 2TB                      | 1        | 1      | 3.7%    |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 1      | 3.7%    |
| Seagate ST1000DM003-1ER162 1TB                      | 1        | 1      | 3.7%    |
| Samsung Electronics SSD 970 EVO 250GB               | 1        | 1      | 3.7%    |
| Samsung Electronics HD103UJ 1TB                     | 1        | 1      | 3.7%    |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1        | 1      | 3.7%    |
| Kingston SV300S37A240G 240GB SSD                    | 1        | 1      | 3.7%    |
| Kingston SV300S37A120G 120GB SSD                    | 1        | 1      | 3.7%    |
| Crucial CT128MX100SSD1 128GB                        | 1        | 1      | 3.7%    |
| A-DATA Technology SX8100NP 1TB                      | 1        | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 16     | 51.85%  |
| WDC                 | 6        | 6      | 22.22%  |
| Samsung Electronics | 2        | 2      | 7.41%   |
| Kingston            | 2        | 2      | 7.41%   |
| Micron Technology   | 1        | 1      | 3.7%    |
| Crucial             | 1        | 1      | 3.7%    |
| A-DATA Technology   | 1        | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 16     | 66.67%  |
| WDC                 | 6        | 6      | 28.57%  |
| Samsung Electronics | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 23     | 75%     |
| SSD  | 4        | 4      | 16.67%  |
| NVMe | 2        | 2      | 8.33%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 101      | 277    | 49.27%  |
| Works    | 80       | 190    | 39.02%  |
| Malfunc  | 24       | 29     | 11.71%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 93       | 33.57%  |
| AMD                          | 80       | 28.88%  |
| Samsung Electronics          | 31       | 11.19%  |
| Sandisk                      | 12       | 4.33%   |
| ASMedia Technology           | 10       | 3.61%   |
| Phison Electronics           | 8        | 2.89%   |
| Kingston Technology Company  | 7        | 2.53%   |
| Silicon Motion               | 5        | 1.81%   |
| JMicron Technology           | 5        | 1.81%   |
| Nvidia                       | 4        | 1.44%   |
| Micron/Crucial Technology    | 4        | 1.44%   |
| Marvell Technology Group     | 4        | 1.44%   |
| Realtek Semiconductor        | 3        | 1.08%   |
| ADATA Technology             | 3        | 1.08%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.72%   |
| LSI Logic / Symbios Logic    | 2        | 0.72%   |
| Toshiba America Info Systems | 1        | 0.36%   |
| SK Hynix                     | 1        | 0.36%   |
| Silicon Image                | 1        | 0.36%   |
| KIOXIA                       | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 55       | 16.62%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 24       | 7.25%   |
| AMD 400 Series Chipset SATA Controller                                           | 18       | 5.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 15       | 4.53%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                         | 15       | 4.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14       | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 10       | 3.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9        | 2.72%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 9        | 2.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8        | 2.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5        | 1.51%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 5        | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 5        | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 5        | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5        | 1.51%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 4        | 1.21%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 4        | 1.21%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4        | 1.21%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 4        | 1.21%   |
| AMD X370 Series Chipset SATA Controller                                          | 4        | 1.21%   |
| AMD 300 Series Chipset SATA Controller                                           | 4        | 1.21%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3        | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3        | 0.91%   |
| Phison E12 NVMe Controller                                                       | 3        | 0.91%   |
| Kingston Company A2000 NVMe SSD                                                  | 3        | 0.91%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3        | 0.91%   |
| Intel SATA Controller [RAID mode]                                                | 3        | 0.91%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3        | 0.91%   |
| Intel 600 Series Chipset Family SATA AHCI Controller                             | 3        | 0.91%   |
| AMD FCH SATA Controller D                                                        | 3        | 0.91%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 3        | 0.91%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2        | 0.6%    |
| Realtek RTS5763DL NVMe SSD Controller                                            | 2        | 0.6%    |
| Nvidia MCP55 SATA Controller                                                     | 2        | 0.6%    |
| Nvidia MCP55 IDE                                                                 | 2        | 0.6%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2        | 0.6%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1001                                     | 2        | 0.6%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2        | 0.6%    |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]          | 2        | 0.6%    |
| Kingston Company KC2000 NVMe SSD                                                 | 2        | 0.6%    |
| Intel SSD 660P Series                                                            | 2        | 0.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2        | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 2        | 0.6%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2        | 0.6%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2        | 0.6%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2        | 0.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2        | 0.6%    |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]    | 2        | 0.6%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 2        | 0.6%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2        | 0.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 0.6%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1        | 0.3%    |
| SK Hynix BC511                                                                   | 1        | 0.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.3%    |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                             | 1        | 0.3%    |
| Samsung NVMe SSD Controller 980                                                  | 1        | 0.3%    |
| Realtek Realtek Non-Volatile memory controller                                   | 1        | 0.3%    |
| Phison PS5013 E13 NVMe Controller                                                | 1        | 0.3%    |
| Nvidia SATA controller                                                           | 1        | 0.3%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1        | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 164      | 62.36%  |
| NVMe | 70       | 26.62%  |
| IDE  | 22       | 8.37%   |
| RAID | 4        | 1.52%   |
| SAS  | 3        | 1.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 94       | 53.11%  |
| AMD    | 83       | 46.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 3.95%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 2.82%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 2.82%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 2.82%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 2.26%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 2.26%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 2.26%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 2.26%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 1.69%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 1.69%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 3        | 1.69%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 1.69%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3        | 1.69%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 1.69%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 2        | 1.13%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 2        | 1.13%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 1.13%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 2        | 1.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.13%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 1.13%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 1.13%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 2        | 1.13%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 1.13%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 1.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 1.13%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.13%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.13%   |
| Intel 12th Gen Core i5-12600K               | 2        | 1.13%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.13%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2        | 1.13%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.13%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.13%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 1.13%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 2        | 1.13%   |
| AMD Athlon II X2 250 Processor              | 2        | 1.13%   |
| Intel Xeon CPU W3565 @ 3.20GHz              | 1        | 0.56%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz         | 1        | 0.56%   |
| Intel Xeon CPU E5-2673 v3 @ 2.40GHz         | 1        | 0.56%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1        | 0.56%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1        | 0.56%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz         | 1        | 0.56%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1        | 0.56%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 1        | 0.56%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.56%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.56%   |
| Intel Core i9-9900T CPU @ 2.10GHz           | 1        | 0.56%   |
| Intel Core i9-9900KS CPU @ 4.00GHz          | 1        | 0.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 0.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.56%   |
| Intel Core i7-4790T CPU @ 2.70GHz           | 1        | 0.56%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1        | 0.56%   |
| Intel Core i7-3820 CPU @ 3.60GHz            | 1        | 0.56%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 0.56%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 0.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.56%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 0.56%   |
| Intel Core i5-6600T CPU @ 2.70GHz           | 1        | 0.56%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 1        | 0.56%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1        | 0.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 30       | 16.95%  |
| Intel Core i5           | 28       | 15.82%  |
| AMD Ryzen 5             | 25       | 14.12%  |
| AMD Ryzen 7             | 16       | 9.04%   |
| AMD Ryzen 9             | 11       | 6.21%   |
| Intel Xeon              | 8        | 4.52%   |
| Intel Core i3           | 7        | 3.95%   |
| AMD Ryzen 3             | 6        | 3.39%   |
| Other                   | 5        | 2.82%   |
| Intel Core i9           | 5        | 2.82%   |
| Intel Core 2 Duo        | 5        | 2.82%   |
| AMD Ryzen Threadripper  | 4        | 2.26%   |
| AMD FX                  | 4        | 2.26%   |
| Intel Pentium           | 3        | 1.69%   |
| AMD Phenom              | 3        | 1.69%   |
| AMD A10                 | 3        | 1.69%   |
| AMD Athlon II X2        | 2        | 1.13%   |
| AMD A8                  | 2        | 1.13%   |
| Intel Pentium Dual-Core | 1        | 0.56%   |
| Intel Core 2 Extreme    | 1        | 0.56%   |
| Intel Celeron           | 1        | 0.56%   |
| AMD Ryzen Embedded      | 1        | 0.56%   |
| AMD Phenom II X6        | 1        | 0.56%   |
| AMD Athlon X4           | 1        | 0.56%   |
| AMD Athlon 64 X2        | 1        | 0.56%   |
| AMD Athlon              | 1        | 0.56%   |
| AMD A6                  | 1        | 0.56%   |
| AMD A4                  | 1        | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 63       | 35.59%  |
| 6      | 38       | 21.47%  |
| 2      | 27       | 15.25%  |
| 8      | 25       | 14.12%  |
| 12     | 8        | 4.52%   |
| 16     | 6        | 3.39%   |
| 24     | 3        | 1.69%   |
| 10     | 3        | 1.69%   |
| 3      | 2        | 1.13%   |
| 32     | 1        | 0.56%   |
| 1      | 1        | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 175      | 98.87%  |
| 2      | 2        | 1.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 120      | 67.8%   |
| 1      | 57       | 32.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 177      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 18       | 10.17%  |
| Unknown    | 14       | 7.91%   |
| 0x306a9    | 12       | 6.78%   |
| 0x08701021 | 12       | 6.78%   |
| 0x906ed    | 8        | 4.52%   |
| 0x506e3    | 8        | 4.52%   |
| 0x906ea    | 7        | 3.95%   |
| 0x0800820d | 7        | 3.95%   |
| 0x0a201016 | 6        | 3.39%   |
| 0x0a201009 | 6        | 3.39%   |
| 0x206a7    | 5        | 2.82%   |
| 0x1067a    | 5        | 2.82%   |
| 0x08101016 | 4        | 2.26%   |
| 0x06003106 | 4        | 2.26%   |
| 0x90672    | 3        | 1.69%   |
| 0x106a5    | 3        | 1.69%   |
| 0x08701013 | 3        | 1.69%   |
| 0x0810100b | 3        | 1.69%   |
| 0x08008206 | 3        | 1.69%   |
| 0x08001138 | 3        | 1.69%   |
| 0x08001137 | 3        | 1.69%   |
| 0xa0671    | 2        | 1.13%   |
| 0x906ec    | 2        | 1.13%   |
| 0x306f2    | 2        | 1.13%   |
| 0x206c2    | 2        | 1.13%   |
| 0x10676    | 2        | 1.13%   |
| 0x0a50000c | 2        | 1.13%   |
| 0x0800820b | 2        | 1.13%   |
| 0x06001119 | 2        | 1.13%   |
| 0x010000b6 | 2        | 1.13%   |
| 0xa0655    | 1        | 0.56%   |
| 0x906eb    | 1        | 0.56%   |
| 0x906e9    | 1        | 0.56%   |
| 0x806e9    | 1        | 0.56%   |
| 0x40671    | 1        | 0.56%   |
| 0x306e4    | 1        | 0.56%   |
| 0x20655    | 1        | 0.56%   |
| 0x0a50000b | 1        | 0.56%   |
| 0x0a201006 | 1        | 0.56%   |
| 0x08600104 | 1        | 0.56%   |
| 0x0830104d | 1        | 0.56%   |
| 0x08301025 | 1        | 0.56%   |
| 0x08101013 | 1        | 0.56%   |
| 0x07000106 | 1        | 0.56%   |
| 0x0600611a | 1        | 0.56%   |
| 0x06000822 | 1        | 0.56%   |
| 0x06000629 | 1        | 0.56%   |
| 0x06000623 | 1        | 0.56%   |
| 0x010000bf | 1        | 0.56%   |
| 0x01000095 | 1        | 0.56%   |
| 0x01000083 | 1        | 0.56%   |
| 0x01000065 | 1        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 22       | 12.43%  |
| Haswell          | 22       | 12.43%  |
| Zen 3            | 19       | 10.73%  |
| Zen 2            | 19       | 10.73%  |
| Zen              | 14       | 7.91%   |
| IvyBridge        | 14       | 7.91%   |
| Zen+             | 12       | 6.78%   |
| Skylake          | 9        | 5.08%   |
| SandyBridge      | 7        | 3.95%   |
| Penryn           | 7        | 3.95%   |
| K10              | 6        | 3.39%   |
| Steamroller      | 4        | 2.26%   |
| Piledriver       | 4        | 2.26%   |
| Westmere         | 3        | 1.69%   |
| Nehalem          | 3        | 1.69%   |
| Alderlake Hybrid | 3        | 1.69%   |
| Icelake          | 2        | 1.13%   |
| Bulldozer        | 2        | 1.13%   |
| K8 Hammer        | 1        | 0.56%   |
| Jaguar           | 1        | 0.56%   |
| Excavator        | 1        | 0.56%   |
| CometLake        | 1        | 0.56%   |
| Broadwell        | 1        | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 72       | 38.5%   |
| AMD               | 64       | 34.22%  |
| Intel             | 50       | 26.74%  |
| ASPEED Technology | 1        | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12       | 6.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 5.24%   |
| Nvidia GK208B [GeForce GT 710]                                              | 8        | 4.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.19%   |
| Intel HD Graphics 530                                                       | 8        | 4.19%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 3.66%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 6        | 3.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 3.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.09%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.09%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 2.09%   |
| AMD Cezanne                                                                 | 4        | 2.09%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 1.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 1.57%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.57%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 3        | 1.57%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3        | 1.57%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3        | 1.57%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 1.57%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.05%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 2        | 1.05%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.05%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 1.05%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 1.05%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.05%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.05%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 1.05%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 1.05%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 1.05%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 2        | 1.05%   |
| Intel AlderLake-S GT1                                                       | 2        | 1.05%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.05%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2        | 1.05%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.52%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.52%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 1        | 0.52%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.52%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.52%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 1        | 0.52%   |
| Nvidia GT200b [GeForce GTX 285]                                             | 1        | 0.52%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.52%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1        | 0.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 0.52%   |
| Nvidia GP107 [GeForce GTX 1050 3GB]                                         | 1        | 0.52%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.52%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.52%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.52%   |
| Nvidia GM108M [GeForce 830M]                                                | 1        | 0.52%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.52%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.52%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.52%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 0.52%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 0.52%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.52%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 0.52%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 67       | 37.85%  |
| 1 x AMD        | 61       | 34.46%  |
| 1 x Intel      | 39       | 22.03%  |
| Intel + Nvidia | 4        | 2.26%   |
| 2 x AMD        | 3        | 1.69%   |
| Other          | 1        | 0.56%   |
| 2 x Nvidia     | 1        | 0.56%   |
| 1 x ASPEED     | 1        | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 127      | 71.75%  |
| Proprietary | 46       | 25.99%  |
| Unknown     | 4        | 2.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 74       | 41.57%  |
| 1.01-2.0   | 24       | 13.48%  |
| 7.01-8.0   | 22       | 12.36%  |
| 0.51-1.0   | 18       | 10.11%  |
| 3.01-4.0   | 17       | 9.55%   |
| 0.01-0.5   | 9        | 5.06%   |
| 5.01-6.0   | 8        | 4.49%   |
| 8.01-16.0  | 6        | 3.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 31       | 15.5%   |
| Dell                 | 25       | 12.5%   |
| Goldstar             | 24       | 12%     |
| Hewlett-Packard      | 18       | 9%      |
| Acer                 | 15       | 7.5%    |
| AOC                  | 14       | 7%      |
| Philips              | 11       | 5.5%    |
| Ancor Communications | 10       | 5%      |
| ViewSonic            | 8        | 4%      |
| BenQ                 | 7        | 3.5%    |
| Iiyama               | 5        | 2.5%    |
| ASUSTek Computer     | 5        | 2.5%    |
| Lenovo               | 4        | 2%      |
| Eizo                 | 4        | 2%      |
| HannStar             | 2        | 1%      |
| Westinghouse         | 1        | 0.5%    |
| Unknown (XXX)        | 1        | 0.5%    |
| TCL                  | 1        | 0.5%    |
| Sony                 | 1        | 0.5%    |
| Sceptre Tech         | 1        | 0.5%    |
| PRISM+               | 1        | 0.5%    |
| Plain Tree Systems   | 1        | 0.5%    |
| Panasonic            | 1        | 0.5%    |
| Packard Bell         | 1        | 0.5%    |
| NEC Computers        | 1        | 0.5%    |
| MSI                  | 1        | 0.5%    |
| Gigabyte Technology  | 1        | 0.5%    |
| Fujitsu Siemens      | 1        | 0.5%    |
| CHE                  | 1        | 0.5%    |
| Belinea              | 1        | 0.5%    |
| Arnos Instruments    | 1        | 0.5%    |
| Apple                | 1        | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 1.42%   |
| Samsung Electronics S22C350 SAM0A32 1920x1080 477x268mm 21.5-inch      | 2        | 0.95%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch      | 2        | 0.95%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 2        | 0.95%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 2        | 0.95%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch              | 2        | 0.95%   |
| Dell U2515H DELD06F 2560x1440 553x311mm 25.0-inch                      | 2        | 0.95%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                      | 2        | 0.95%   |
| AOC U34G2G4R3 AOC3402 3440x1440 797x334mm 34.0-inch                    | 2        | 0.95%   |
| Acer VG240Y ACR0673 1920x1080 527x296mm 23.8-inch                      | 2        | 0.95%   |
| Westinghouse EU24H1G1 WDT1D42 1366x768 1150x650mm 52.0-inch            | 1        | 0.47%   |
| ViewSonic VX3258 SERIES VSCDE35 2560x1440 697x392mm 31.5-inch          | 1        | 0.47%   |
| ViewSonic VX2336 SERIES VSC402A 1920x1080 510x290mm 23.1-inch          | 1        | 0.47%   |
| ViewSonic VX2268wm VSC0E23 1680x1050 474x296mm 22.0-inch               | 1        | 0.47%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch               | 1        | 0.47%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch          | 1        | 0.47%   |
| ViewSonic VA2419 Series VSC7B32 1920x1080 527x296mm 23.8-inch          | 1        | 0.47%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch           | 1        | 0.47%   |
| ViewSonic VA1926wSERIES VSC5920 1440x900 410x256mm 19.0-inch           | 1        | 0.47%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch         | 1        | 0.47%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                    | 1        | 0.47%   |
| Sony TV SNY4502 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.47%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch          | 1        | 0.47%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 1        | 0.47%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch      | 1        | 0.47%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch      | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM04DD 1920x1080 477x268mm 21.5-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch    | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM020D 1280x1024 338x270mm 17.0-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM01B8 1280x1024 338x270mm 17.0-inch   | 1        | 0.47%   |
| Samsung Electronics SMBX2440 SAM068B 1920x1080 530x300mm 24.0-inch     | 1        | 0.47%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1        | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 0.47%   |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch      | 1        | 0.47%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch      | 1        | 0.47%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 1        | 0.47%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch      | 1        | 0.47%   |
| Samsung Electronics LS27R75 SAM102D 2560x1440 598x336mm 27.0-inch      | 1        | 0.47%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch    | 1        | 0.47%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1        | 0.47%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch | 1        | 0.47%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 1060x590mm 47.8-inch | 1        | 0.47%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch     | 1        | 0.47%   |
| Samsung Electronics C27HG7x SAM0E16 2560x1440 598x336mm 27.0-inch      | 1        | 0.47%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch      | 1        | 0.47%   |
| PRISM+ ULTRON 2754C INN0027 1920x1080 598x337mm 27.0-inch              | 1        | 0.47%   |
| Plain Tree Systems Monitor PTS0770 1440x900 410x256mm 19.0-inch        | 1        | 0.47%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch             | 1        | 0.47%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 1        | 0.47%   |
| Philips PHL 274E5 PHLC0C8 1920x1080 600x340mm 27.2-inch                | 1        | 0.47%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch              | 1        | 0.47%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 530x300mm 24.0-inch                | 1        | 0.47%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.47%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch                | 1        | 0.47%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                | 1        | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 98       | 51.31%  |
| 2560x1440 (QHD)    | 22       | 11.52%  |
| 3840x2160 (4K)     | 20       | 10.47%  |
| 1920x1200 (WUXGA)  | 9        | 4.71%   |
| 1280x1024 (SXGA)   | 9        | 4.71%   |
| 1680x1050 (WSXGA+) | 7        | 3.66%   |
| 1600x900 (HD+)     | 5        | 2.62%   |
| 1366x768 (WXGA)    | 5        | 2.62%   |
| 3440x1440          | 4        | 2.09%   |
| 1440x900 (WXGA+)   | 4        | 2.09%   |
| 2560x1080          | 3        | 1.57%   |
| 3840x1080          | 2        | 1.05%   |
| 3840x1600          | 1        | 0.52%   |
| 2560x1600          | 1        | 0.52%   |
| 1280x720 (HD)      | 1        | 0.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 40       | 19.9%   |
| 27     | 37       | 18.41%  |
| 21     | 30       | 14.93%  |
| 23     | 24       | 11.94%  |
| 31     | 11       | 5.47%   |
| 34     | 7        | 3.48%   |
| 22     | 7        | 3.48%   |
| 19     | 7        | 3.48%   |
| 17     | 6        | 2.99%   |
| 20     | 5        | 2.49%   |
| 18     | 5        | 2.49%   |
| 25     | 4        | 1.99%   |
| 54     | 3        | 1.49%   |
| 42     | 3        | 1.49%   |
| 47     | 2        | 1%      |
| 32     | 2        | 1%      |
| 72     | 1        | 0.5%    |
| 52     | 1        | 0.5%    |
| 49     | 1        | 0.5%    |
| 48     | 1        | 0.5%    |
| 37     | 1        | 0.5%    |
| 30     | 1        | 0.5%    |
| 28     | 1        | 0.5%    |
| 16     | 1        | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 94       | 48.45%  |
| 401-500     | 51       | 26.29%  |
| 601-700     | 16       | 8.25%   |
| 701-800     | 9        | 4.64%   |
| 1001-1500   | 8        | 4.12%   |
| 301-350     | 6        | 3.09%   |
| 351-400     | 5        | 2.58%   |
| 901-1000    | 3        | 1.55%   |
| 801-900     | 1        | 0.52%   |
| 1501-2000   | 1        | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 135      | 75.42%  |
| 16/10 | 24       | 13.41%  |
| 5/4   | 9        | 5.03%   |
| 21/9  | 8        | 4.47%   |
| 32/9  | 2        | 1.12%   |
| 6/5   | 1        | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 75       | 37.88%  |
| 301-350        | 37       | 18.69%  |
| 151-200        | 23       | 11.62%  |
| 351-500        | 21       | 10.61%  |
| 251-300        | 17       | 8.59%   |
| 141-150        | 11       | 5.56%   |
| 501-1000       | 8        | 4.04%   |
| More than 1000 | 5        | 2.53%   |
| 121-130        | 1        | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 115      | 60.85%  |
| 101-120 | 54       | 28.57%  |
| 121-160 | 11       | 5.82%   |
| 1-50    | 5        | 2.65%   |
| 161-240 | 4        | 2.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 126      | 71.19%  |
| 2     | 40       | 22.6%   |
| 0     | 7        | 3.95%   |
| 3     | 3        | 1.69%   |
| 4     | 1        | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 101      | 40.08%  |
| Intel                           | 86       | 34.13%  |
| Qualcomm Atheros                | 16       | 6.35%   |
| Ralink Technology               | 10       | 3.97%   |
| TP-Link                         | 7        | 2.78%   |
| Broadcom                        | 7        | 2.78%   |
| Nvidia                          | 3        | 1.19%   |
| Aquantia                        | 3        | 1.19%   |
| NetGear                         | 2        | 0.79%   |
| Google                          | 2        | 0.79%   |
| Edimax Technology               | 2        | 0.79%   |
| Belkin Components               | 2        | 0.79%   |
| ASUSTek Computer                | 2        | 0.79%   |
| Xiaomi                          | 1        | 0.4%    |
| Qualcomm Atheros Communications | 1        | 0.4%    |
| Mellanox Technologies           | 1        | 0.4%    |
| Marvell Technology Group        | 1        | 0.4%    |
| ICS Advent                      | 1        | 0.4%    |
| Huawei Technologies             | 1        | 0.4%    |
| HMD Global                      | 1        | 0.4%    |
| D-Link                          | 1        | 0.4%    |
| AVM                             | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 85       | 29.31%  |
| Intel Wi-Fi 6 AX200                                               | 21       | 7.24%   |
| Intel I211 Gigabit Network Connection                             | 19       | 6.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12       | 4.14%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 3.45%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5        | 1.72%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.72%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.72%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 4        | 1.38%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.03%   |
| Ralink RT5370 Wireless Adapter                                    | 3        | 1.03%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 1.03%   |
| Intel Wireless-AC 9260                                            | 3        | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 1.03%   |
| TP-Link 802.11ac NIC                                              | 2        | 0.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.69%   |
| Ralink RT5372 Wireless Adapter                                    | 2        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.69%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.69%   |
| Intel Wireless 8260                                               | 2        | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.69%   |
| Intel 600 Series Chipset Family Wireless-AC 9560                  | 2        | 0.69%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2        | 0.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2        | 0.69%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.34%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.34%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.34%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 0.34%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.34%   |
| Realtek RTL-8129                                                  | 1        | 0.34%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.34%   |
| Realtek 802.11ac NIC                                              | 1        | 0.34%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.34%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1        | 0.34%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1        | 0.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.34%   |
| Qualcomm Atheros AR5523                                           | 1        | 0.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.34%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 0.34%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.34%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.34%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]             | 1        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 44       | 48.35%  |
| Ralink Technology               | 10       | 10.99%  |
| Realtek Semiconductor           | 8        | 8.79%   |
| TP-Link                         | 7        | 7.69%   |
| Qualcomm Atheros                | 7        | 7.69%   |
| Broadcom                        | 5        | 5.49%   |
| NetGear                         | 2        | 2.2%    |
| Edimax Technology               | 2        | 2.2%    |
| Belkin Components               | 2        | 2.2%    |
| Qualcomm Atheros Communications | 1        | 1.1%    |
| D-Link                          | 1        | 1.1%    |
| AVM                             | 1        | 1.1%    |
| ASUSTek Computer                | 1        | 1.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                     | 21       | 22.83%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                        | 5        | 5.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                                         | 5        | 5.43%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                             | 4        | 4.35%   |
| Ralink RT5370 Wireless Adapter                                                          | 3        | 3.26%   |
| Intel Wireless-AC 9260                                                                  | 3        | 3.26%   |
| TP-Link 802.11ac NIC                                                                    | 2        | 2.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                         | 2        | 2.17%   |
| Ralink RT5372 Wireless Adapter                                                          | 2        | 2.17%   |
| Ralink MT7601U Wireless Adapter                                                         | 2        | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                              | 2        | 2.17%   |
| Intel Wireless 8260                                                                     | 2        | 2.17%   |
| Intel 600 Series Chipset Family Wireless-AC 9560                                        | 2        | 2.17%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                      | 2        | 2.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                                         | 2        | 2.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                            | 1        | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                      | 1        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                         | 1        | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                | 1        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                         | 1        | 1.09%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                  | 1        | 1.09%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                  | 1        | 1.09%   |
| Realtek 802.11ac NIC                                                                    | 1        | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                   | 1        | 1.09%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                   | 1        | 1.09%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                       | 1        | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                              | 1        | 1.09%   |
| Qualcomm Atheros AR5523                                                                 | 1        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                        | 1        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                        | 1        | 1.09%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                        | 1        | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                          | 1        | 1.09%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                   | 1        | 1.09%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101]                        | 1        | 1.09%   |
| Intel Wireless 8265 / 8275                                                              | 1        | 1.09%   |
| Intel Wireless 3165                                                                     | 1        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                  | 1        | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                                          | 1        | 1.09%   |
| Intel Centrino Wireless-N 2230                                                          | 1        | 1.09%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                           | 1        | 1.09%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                          | 1        | 1.09%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]                       | 1        | 1.09%   |
| D-Link 11ac adapter                                                                     | 1        | 1.09%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                      | 1        | 1.09%   |
| Belkin Components F7D2102 802.11n N300 Micro Wireless Adapter v3000 [Realtek RTL8192CU] | 1        | 1.09%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870]                  | 1        | 1.09%   |
| AVM FRITZ!WLAN AC 860                                                                   | 1        | 1.09%   |
| ASUS AC51 802.11a/b/g/n/ac Wireless Adapter [Mediatek MT7610U]                          | 1        | 1.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 97       | 51.6%   |
| Intel                    | 66       | 35.11%  |
| Qualcomm Atheros         | 9        | 4.79%   |
| Nvidia                   | 3        | 1.6%    |
| Aquantia                 | 3        | 1.6%    |
| Broadcom                 | 2        | 1.06%   |
| Xiaomi                   | 1        | 0.53%   |
| Mellanox Technologies    | 1        | 0.53%   |
| Marvell Technology Group | 1        | 0.53%   |
| ICS Advent               | 1        | 0.53%   |
| Huawei Technologies      | 1        | 0.53%   |
| HMD Global               | 1        | 0.53%   |
| Google                   | 1        | 0.53%   |
| ASUSTek Computer         | 1        | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 85       | 43.37%  |
| Intel I211 Gigabit Network Connection                                         | 19       | 9.69%   |
| Realtek RTL8125 2.5GbE Controller                                             | 12       | 6.12%   |
| Intel Ethernet Connection (7) I219-V                                          | 10       | 5.1%    |
| Intel Ethernet Connection (2) I219-V                                          | 5        | 2.55%   |
| Intel 82579V Gigabit Network Connection                                       | 5        | 2.55%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 2.55%   |
| Intel Ethernet Controller I225-V                                              | 4        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 3        | 1.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3        | 1.53%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 1.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 2        | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2        | 1.02%   |
| Nvidia MCP55 Ethernet                                                         | 2        | 1.02%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2        | 1.02%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.02%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 2        | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.51%   |
| Realtek USB 10/100/1G/2.5G LAN                                                | 1        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.51%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.51%   |
| Nvidia MCP61 Ethernet                                                         | 1        | 0.51%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.51%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.51%   |
| Intel I350 Gigabit Network Connection                                         | 1        | 0.51%   |
| Intel Ethernet Controller 10G X550T                                           | 1        | 0.51%   |
| Intel Ethernet Connection (2) I218-V                                          | 1        | 0.51%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.51%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.51%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.51%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.51%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1        | 0.51%   |
| Huawei E353/E3131                                                             | 1        | 0.51%   |
| HMD Global Android                                                            | 1        | 0.51%   |
| Google Nexus/Pixel Device (tether)                                            | 1        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.51%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 1        | 0.51%   |
| ASUS USB 10/100/1G/2.5G LAN                                                   | 1        | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 1        | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 176      | 67.18%  |
| WiFi     | 84       | 32.06%  |
| Modem    | 1        | 0.38%   |
| Unknown  | 1        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 162      | 72.65%  |
| WiFi     | 61       | 27.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 109      | 61.58%  |
| 2     | 52       | 29.38%  |
| 3     | 12       | 6.78%   |
| 4     | 2        | 1.13%   |
| 5     | 1        | 0.56%   |
| 0     | 1        | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 132      | 74.58%  |
| Yes  | 45       | 25.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 43       | 52.44%  |
| Cambridge Silicon Radio         | 17       | 20.73%  |
| Broadcom                        | 6        | 7.32%   |
| ASUSTek Computer                | 5        | 6.1%    |
| Qualcomm Atheros Communications | 3        | 3.66%   |
| Apple                           | 3        | 3.66%   |
| TP-Link                         | 2        | 2.44%   |
| Realtek Semiconductor           | 2        | 2.44%   |
| Lite-On Technology              | 1        | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 21       | 25.61%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17       | 20.73%  |
| Intel Bluetooth Device                              | 11       | 13.41%  |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 6.1%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4        | 4.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 3.66%   |
| TP-Link UB500 Adapter                               | 2        | 2.44%   |
| Realtek Bluetooth Radio                             | 2        | 2.44%   |
| Qualcomm Atheros  Bluetooth Device                  | 2        | 2.44%   |
| ASUS Bluetooth Radio                                | 2        | 2.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2        | 2.44%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 1.22%   |
| Lite-On Bluetooth Device                            | 1        | 1.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1        | 1.22%   |
| Intel Bluetooth wireless interface                  | 1        | 1.22%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 1.22%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 1.22%   |
| ASUS Qualcomm Bluetooth 4.1                         | 1        | 1.22%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.22%   |
| ASUS BCM20702A0                                     | 1        | 1.22%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 93       | 29.71%  |
| Intel                       | 88       | 28.12%  |
| Nvidia                      | 68       | 21.73%  |
| C-Media Electronics         | 8        | 2.56%   |
| Creative Labs               | 6        | 1.92%   |
| Plantronics                 | 5        | 1.6%    |
| Texas Instruments           | 4        | 1.28%   |
| Razer USA                   | 3        | 0.96%   |
| GN Netcom                   | 3        | 0.96%   |
| SteelSeries ApS             | 2        | 0.64%   |
| Sennheiser Communications   | 2        | 0.64%   |
| SAVITECH                    | 2        | 0.64%   |
| Kingston Technology         | 2        | 0.64%   |
| JMTek                       | 2        | 0.64%   |
| Giga-Byte Technology        | 2        | 0.64%   |
| Focusrite-Novation          | 2        | 0.64%   |
| Blue Microphones            | 2        | 0.64%   |
| Apple                       | 2        | 0.64%   |
| Unknown                     | 1        | 0.32%   |
| Tenx Technology             | 1        | 0.32%   |
| Samson Technologies         | 1        | 0.32%   |
| GYROCOM C&C                 | 1        | 0.32%   |
| Goldvish                    | 1        | 0.32%   |
| Generalplus Technology      | 1        | 0.32%   |
| FiiO Electronics Technology | 1        | 0.32%   |
| Elite Silicon               | 1        | 0.32%   |
| DigiTech                    | 1        | 0.32%   |
| Dell                        | 1        | 0.32%   |
| Creative Technology         | 1        | 0.32%   |
| Corsair                     | 1        | 0.32%   |
| Cooler Master               | 1        | 0.32%   |
| Audio-Technica              | 1        | 0.32%   |
| ASUSTek Computer            | 1        | 0.32%   |
| Arturia                     | 1        | 0.32%   |
| AKAI Professional M.I.      | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                      | 31       | 8.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                           | 17       | 4.52%   |
| Intel Cannon Lake PCH cAVS                                                    | 16       | 4.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller           | 14       | 3.72%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                           | 13       | 3.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                    | 12       | 3.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                         | 10       | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller    | 10       | 2.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller              | 9        | 2.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller           | 9        | 2.39%   |
| AMD Navi 10 HDMI Audio                                                        | 9        | 2.39%   |
| Nvidia TU106 High Definition Audio Controller                                 | 8        | 2.13%   |
| Nvidia GP107GL High Definition Audio Controller                               | 8        | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller               | 8        | 2.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                  | 8        | 2.13%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                     | 8        | 2.13%   |
| AMD FCH Azalia Controller                                                     | 7        | 1.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                              | 6        | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                           | 6        | 1.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                  | 6        | 1.6%    |
| Intel 9 Series Chipset Family HD Audio Controller                             | 5        | 1.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]       | 5        | 1.33%   |
| Nvidia GP106 High Definition Audio Controller                                 | 4        | 1.06%   |
| Intel 200 Series PCH HD Audio                                                 | 4        | 1.06%   |
| AMD Renoir Radeon High Definition Audio Controller                            | 4        | 1.06%   |
| Nvidia GM206 High Definition Audio Controller                                 | 3        | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                 | 3        | 0.8%    |
| Nvidia GK104 HDMI Audio Controller                                            | 3        | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                 | 3        | 0.8%    |
| Nvidia GA102 High Definition Audio Controller                                 | 3        | 0.8%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                 | 3        | 0.8%    |
| C-Media Electronics USB Audio Device                                          | 3        | 0.8%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                    | 3        | 0.8%    |
| Texas Instruments PCM2902 Audio Codec                                         | 2        | 0.53%   |
| Nvidia TU116 High Definition Audio Controller                                 | 2        | 0.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                | 2        | 0.53%   |
| Nvidia TU104 HD Audio Controller                                              | 2        | 0.53%   |
| Nvidia MCP55 High Definition Audio                                            | 2        | 0.53%   |
| Nvidia GP108 High Definition Audio Controller                                 | 2        | 0.53%   |
| Nvidia GP104 High Definition Audio Controller                                 | 2        | 0.53%   |
| Nvidia GM204 High Definition Audio Controller                                 | 2        | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                            | 2        | 0.53%   |
| Nvidia Audio device                                                           | 2        | 0.53%   |
| Intel USB PnP Sound Device                                                    | 2        | 0.53%   |
| Intel Tiger Lake-H HD Audio Controller                                        | 2        | 0.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                       | 2        | 0.53%   |
| Intel C610/X99 series chipset HD Audio Controller                             | 2        | 0.53%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                           | 2        | 0.53%   |
| Intel 600 Series Chipset Family Smart Sound Technology (SST) Audio Controller | 2        | 0.53%   |
| GN Netcom Jabra Link 370                                                      | 2        | 0.53%   |
| Giga-Byte Technology USB Audio                                                | 2        | 0.53%   |
| AMD Trinity HDMI Audio Controller                                             | 2        | 0.53%   |
| AMD Kaveri HDMI/DP Audio Controller                                           | 2        | 0.53%   |
| AMD Kabini HDMI/DP Audio                                                      | 2        | 0.53%   |
| Unknown Realtek USB Audio Rear                                                | 1        | 0.27%   |
| Unknown Realtek USB Audio Front                                               | 1        | 0.27%   |
| Texas Instruments PCM2903B Audio CODEC                                        | 1        | 0.27%   |
| Texas Instruments PCM2900 Audio Codec                                         | 1        | 0.27%   |
| Tenx Technology USB AUDIO                                                     | 1        | 0.27%   |
| SteelSeries ApS SteelSeries Arctis 7                                          | 1        | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 24       | 24.74%  |
| Corsair             | 18       | 18.56%  |
| Crucial             | 10       | 10.31%  |
| Unknown             | 9        | 9.28%   |
| SK Hynix            | 9        | 9.28%   |
| Samsung Electronics | 8        | 8.25%   |
| G.Skill             | 7        | 7.22%   |
| Micron Technology   | 3        | 3.09%   |
| Patriot             | 2        | 2.06%   |
| V-GeN               | 1        | 1.03%   |
| Team                | 1        | 1.03%   |
| PLEXHD              | 1        | 1.03%   |
| OCZ                 | 1        | 1.03%   |
| GOODRAM             | 1        | 1.03%   |
| Apacer              | 1        | 1.03%   |
| A-DATA Technology   | 1        | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 3        | 2.86%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s    | 3        | 2.86%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 2        | 1.9%    |
| SK Hynix RAM Module 4GB DIMM DDR3 1066MT/s               | 2        | 1.9%    |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s     | 2        | 1.9%    |
| Kingston RAM Module 4GB DIMM DDR3 1066MT/s               | 2        | 1.9%    |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s  | 2        | 1.9%    |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 2        | 1.9%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 2        | 1.9%    |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s   | 2        | 1.9%    |
| V-GeN RAM D4H8GL32A8TS 8GB DIMM DDR4 3200MT/s            | 1        | 0.95%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                     | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM 800MT/s                      | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 0.95%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 0.95%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                 | 1        | 0.95%   |
| Unknown RAM Module 16GB SODIMM DDR4 2667MT/s             | 1        | 0.95%   |
| Team RAM TEAMGROUP-UD4-4000 8GB DIMM DDR4 3200MT/s       | 1        | 0.95%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.95%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 0.95%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s     | 1        | 0.95%   |
| SK Hynix RAM HMP125U6EFR8C-S6 2GB DIMM DDR2 800MT/s      | 1        | 0.95%   |
| SK Hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s     | 1        | 0.95%   |
| SK Hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s     | 1        | 0.95%   |
| SK Hynix RAM HMA41GR7MFR4N-TF 8GB DIMM DDR4 2667MT/s     | 1        | 0.95%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s              | 1        | 0.95%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                | 1        | 0.95%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s    | 1        | 0.95%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1866MT/s   | 1        | 0.95%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s      | 1        | 0.95%   |
| Samsung RAM M378A2G43MX3-CWE 16GB DIMM DDR4 3200MT/s     | 1        | 0.95%   |
| Samsung RAM M378A2G43AB3-CWE 16GB DIMM DDR4 3200MT/s     | 1        | 0.95%   |
| PLEXHD RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 0.95%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s           | 1        | 0.95%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s       | 1        | 0.95%   |
| OCZ RAM OCZ2P8002G 2GB DIMM DDR2 1024MT/s                | 1        | 0.95%   |
| Micron RAM 8KTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s   | 1        | 0.95%   |
| Micron RAM 16HTF25664AZ-800H1 2GB DIMM DDR2 800MT/s      | 1        | 0.95%   |
| Micron RAM 16ATF2G64AZ-2G1B1 16GB DIMM DDR4 2133MT/s     | 1        | 0.95%   |
| Kingston RAM KHX3600C17D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 0.95%   |
| Kingston RAM KHX2666C16D4/16GX 16GB DIMM DDR4 2667MT/s   | 1        | 0.95%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s        | 1        | 0.95%   |
| Kingston RAM KHX2400C15D4/32GX 32GB DIMM DDR4 2400MT/s   | 1        | 0.95%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s        | 1        | 0.95%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 0.95%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s     | 1        | 0.95%   |
| Kingston RAM KF548C38-16 16GB DIMM 4800MT/s              | 1        | 0.95%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 0.95%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 1        | 0.95%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 0.95%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 0.95%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s    | 1        | 0.95%   |
| Kingston RAM 99U5471-036.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 0.95%   |
| Kingston RAM 99U5402-056.A00LF 2GB DIMM DDR3 1333MT/s    | 1        | 0.95%   |
| Kingston RAM 99P5474-050.A00LF 4096MB DIMM DDR3 1333MT/s | 1        | 0.95%   |
| Kingston RAM 9905584-015.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 0.95%   |
| Kingston RAM 9905428-193.A00LF 8GB SODIMM DDR3 1600MT/s  | 1        | 0.95%   |
| GOODRAM RAM GR1600D364L11S/4G 4GB DIMM DDR3 1600MT/s     | 1        | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 49       | 57.65%  |
| DDR3    | 27       | 31.76%  |
| Unknown | 6        | 7.06%   |
| DDR2    | 3        | 3.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 81       | 95.29%  |
| SODIMM | 4        | 4.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 34       | 38.64%  |
| 4096  | 22       | 25%     |
| 16384 | 21       | 23.86%  |
| 2048  | 8        | 9.09%   |
| 32768 | 2        | 2.27%   |
| 1024  | 1        | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 18       | 19.15%  |
| 3200  | 14       | 14.89%  |
| 3600  | 8        | 8.51%   |
| 1333  | 7        | 7.45%   |
| 2400  | 6        | 6.38%   |
| 2667  | 5        | 5.32%   |
| 2133  | 5        | 5.32%   |
| 800   | 5        | 5.32%   |
| 3400  | 4        | 4.26%   |
| 2933  | 4        | 4.26%   |
| 3466  | 3        | 3.19%   |
| 2666  | 3        | 3.19%   |
| 3533  | 2        | 2.13%   |
| 3000  | 2        | 2.13%   |
| 1066  | 2        | 2.13%   |
| 4800  | 1        | 1.06%   |
| 3266  | 1        | 1.06%   |
| 2800  | 1        | 1.06%   |
| 1866  | 1        | 1.06%   |
| 1067  | 1        | 1.06%   |
| 1024  | 1        | 1.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 3        | 42.86%  |
| Canon              | 2        | 28.57%  |
| Kyocera            | 1        | 14.29%  |
| Hewlett-Packard    | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Brother HL-L2340D series | 2        | 28.57%  |
| Kyocera ECOSYS M5521cdw  | 1        | 14.29%  |
| HP LaserJet CM1415fnw    | 1        | 14.29%  |
| Canon TR4500 series      | 1        | 14.29%  |
| Canon MF4010 series      | 1        | 14.29%  |
| Brother HL-L2360D series | 1        | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 3        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 33.33%  |
| Canon CanoScan LiDE 210 | 1        | 33.33%  |
| Canon CanoScan LiDE 120 | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 22       | 55%     |
| Apple                                  | 3        | 7.5%    |
| Z-Star Microelectronics                | 2        | 5%      |
| Microsoft                              | 2        | 5%      |
| KYE Systems (Mouse Systems)            | 2        | 5%      |
| Microdia                               | 1        | 2.5%    |
| Micro Star International               | 1        | 2.5%    |
| LG Electronics                         | 1        | 2.5%    |
| Lenovo                                 | 1        | 2.5%    |
| Hewlett-Packard                        | 1        | 2.5%    |
| Generalplus Technology                 | 1        | 2.5%    |
| Cubeternet                             | 1        | 2.5%    |
| Creative Technology                    | 1        | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) | 1        | 2.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                 | 5        | 12.5%   |
| Logitech HD Pro Webcam C920                                          | 4        | 10%     |
| Logitech StreamCam                                                   | 2        | 5%      |
| Logitech QuickCam Pro 9000                                           | 2        | 5%      |
| Logitech HD Webcam C525                                              | 2        | 5%      |
| Apple iPhone 5/5C/5S/6/SE                                            | 2        | 5%      |
| Z-Star Venus USB2.0 Camera                                           | 1        | 2.5%    |
| Z-Star Sirius USB 2.0 Camera                                         | 1        | 2.5%    |
| Microsoft Xbox NUI Camera                                            | 1        | 2.5%    |
| Microsoft LifeCam Cinema                                             | 1        | 2.5%    |
| Microdia Webcam Vitade AF                                            | 1        | 2.5%    |
| Micro Star International MSI USB Device                              | 1        | 2.5%    |
| Logitech Webcam C930e                                                | 1        | 2.5%    |
| Logitech QuickCam Ultra Vision                                       | 1        | 2.5%    |
| Logitech QuickCam Communicate Deluxe                                 | 1        | 2.5%    |
| Logitech HD Webcam C615                                              | 1        | 2.5%    |
| Logitech HD Webcam C510                                              | 1        | 2.5%    |
| Logitech C922 Pro Stream Webcam                                      | 1        | 2.5%    |
| Logitech BRIO                                                        | 1        | 2.5%    |
| LG AN-VC500 Camera                                                   | 1        | 2.5%    |
| Lenovo 500 RGB Camera                                                | 1        | 2.5%    |
| KYE Systems (Mouse Systems) Genius iSlim 330                         | 1        | 2.5%    |
| KYE Systems (Mouse Systems) FaceCam 1000X                            | 1        | 2.5%    |
| HP Webcam 1300                                                       | 1        | 2.5%    |
| Generalplus GENERAL WEBCAM                                           | 1        | 2.5%    |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101]  | 1        | 2.5%    |
| Creative Live! Cam Sync HD [VF0770]                                  | 1        | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 2.5%    |
| Apple iSight in LED Cinema Display                                   | 1        | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 159      | 88.83%  |
| 1     | 19       | 10.61%  |
| 2     | 1        | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 27.78%  |
| Graphics card            | 5        | 27.78%  |
| Communication controller | 3        | 16.67%  |
| Unassigned class         | 2        | 11.11%  |
| Camera                   | 2        | 11.11%  |
| Sound                    | 1        | 5.56%   |

