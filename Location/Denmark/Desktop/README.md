Linux in Denmark - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 560

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | T-P5G31A                    | [ca450a3a63](https://linux-hardware.org/?probe=ca450a3a63) | Jan 28, 2024 |
| MSI           | Z170A TOMAHAWK AC           | [bd66397010](https://linux-hardware.org/?probe=bd66397010) | Jan 23, 2024 |
| ASRock        | B760M Steel Legend WiFi     | [a3bc588c07](https://linux-hardware.org/?probe=a3bc588c07) | Jan 13, 2024 |
| ASRock        | B450M-HDV R4.0              | [b98e94bfb3](https://linux-hardware.org/?probe=b98e94bfb3) | Jan 13, 2024 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | [7049dd3f9a](https://linux-hardware.org/?probe=7049dd3f9a) | Jan 12, 2024 |
| Lenovo        | NO DPK                      | [739397b2fd](https://linux-hardware.org/?probe=739397b2fd) | Jan 10, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [af48a525ff](https://linux-hardware.org/?probe=af48a525ff) | Jan 06, 2024 |
| HP            | 1495                        | [90db2bac77](https://linux-hardware.org/?probe=90db2bac77) | Jan 05, 2024 |
| HP            | 18E4                        | [e89784f165](https://linux-hardware.org/?probe=e89784f165) | Jan 05, 2024 |
| ASUSTek       | A4320A6420                  | [5df0f2025e](https://linux-hardware.org/?probe=5df0f2025e) | Jan 04, 2024 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [080172526c](https://linux-hardware.org/?probe=080172526c) | Dec 31, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [a80537094f](https://linux-hardware.org/?probe=a80537094f) | Dec 15, 2023 |
| HP            | 1497                        | [f2951d81c8](https://linux-hardware.org/?probe=f2951d81c8) | Dec 12, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [f47146cdb9](https://linux-hardware.org/?probe=f47146cdb9) | Dec 07, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| ASUSTek       | Z97-P                       | [109cecbcba](https://linux-hardware.org/?probe=109cecbcba) | Dec 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4c55de5adb](https://linux-hardware.org/?probe=4c55de5adb) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [c166853e23](https://linux-hardware.org/?probe=c166853e23) | Nov 26, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [a8e3339ba9](https://linux-hardware.org/?probe=a8e3339ba9) | Nov 26, 2023 |
| MSI           | PRO H610M-G DDR4            | [5c10f3d5a1](https://linux-hardware.org/?probe=5c10f3d5a1) | Nov 25, 2023 |
| MSI           | PRO H610M-G DDR4            | [05ba5178cb](https://linux-hardware.org/?probe=05ba5178cb) | Nov 25, 2023 |
| MSI           | IONA                        | [ccadf6afaf](https://linux-hardware.org/?probe=ccadf6afaf) | Nov 21, 2023 |
| ADLINK Tec... | MXE5400                     | [ae09533003](https://linux-hardware.org/?probe=ae09533003) | Nov 20, 2023 |
| MSI           | PRO H610M-G DDR4            | [0d4fe4c2b9](https://linux-hardware.org/?probe=0d4fe4c2b9) | Nov 19, 2023 |
| Intel         | STK2MV64CC H89290-502       | [041670b7d8](https://linux-hardware.org/?probe=041670b7d8) | Nov 13, 2023 |
| Gigabyte      | EP45T-UD3R                  | [0940fc528f](https://linux-hardware.org/?probe=0940fc528f) | Nov 09, 2023 |
| HP            | 1495                        | [fe18b89530](https://linux-hardware.org/?probe=fe18b89530) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [17acb71f9d](https://linux-hardware.org/?probe=17acb71f9d) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [bc3444ed2f](https://linux-hardware.org/?probe=bc3444ed2f) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3c1e4ea8bf](https://linux-hardware.org/?probe=3c1e4ea8bf) | Nov 04, 2023 |
| ASUSTek       | PRIME X570-P                | [f54d8e7dea](https://linux-hardware.org/?probe=f54d8e7dea) | Nov 01, 2023 |
| ASUSTek       | PRIME X570-P                | [9a2f1f7750](https://linux-hardware.org/?probe=9a2f1f7750) | Nov 01, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [949a1ab2bb](https://linux-hardware.org/?probe=949a1ab2bb) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3b8a5a44c7](https://linux-hardware.org/?probe=3b8a5a44c7) | Oct 21, 2023 |
| Packard Be... | IMEDIA S2380                | [905b7ea7f0](https://linux-hardware.org/?probe=905b7ea7f0) | Oct 20, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | [f824921cbb](https://linux-hardware.org/?probe=f824921cbb) | Oct 17, 2023 |
| ASUSTek       | PRIME B365M-K               | [e5e897e96a](https://linux-hardware.org/?probe=e5e897e96a) | Oct 09, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [b04266e656](https://linux-hardware.org/?probe=b04266e656) | Oct 08, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [f68374e7cd](https://linux-hardware.org/?probe=f68374e7cd) | Oct 05, 2023 |
| ASRock        | B450 Gaming K4              | [8311d775a9](https://linux-hardware.org/?probe=8311d775a9) | Oct 01, 2023 |
| ASUSTek       | P9X79                       | [d663285ae0](https://linux-hardware.org/?probe=d663285ae0) | Sep 19, 2023 |
| ASRock        | B450 Gaming K4              | [ad66bafcae](https://linux-hardware.org/?probe=ad66bafcae) | Sep 17, 2023 |
| Acer          | Aspire X1470                | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| ASUSTek       | P5GC-MX                     | [7d13cd846d](https://linux-hardware.org/?probe=7d13cd846d) | Sep 04, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [0faa734044](https://linux-hardware.org/?probe=0faa734044) | Sep 04, 2023 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | [595afb8cf0](https://linux-hardware.org/?probe=595afb8cf0) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | [569d6b6121](https://linux-hardware.org/?probe=569d6b6121) | Aug 27, 2023 |
| HP            | 1905                        | [f680d1c561](https://linux-hardware.org/?probe=f680d1c561) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | [a0c3124b6a](https://linux-hardware.org/?probe=a0c3124b6a) | Aug 27, 2023 |
| Dell          | 0XCR8D A02                  | [1f5f734faa](https://linux-hardware.org/?probe=1f5f734faa) | Aug 26, 2023 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | [7a89f9b5a7](https://linux-hardware.org/?probe=7a89f9b5a7) | Aug 26, 2023 |
| ASRock        | AB350 Pro4                  | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [150d68269d](https://linux-hardware.org/?probe=150d68269d) | Aug 08, 2023 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [a5eb82b4f9](https://linux-hardware.org/?probe=a5eb82b4f9) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [eb92759c2a](https://linux-hardware.org/?probe=eb92759c2a) | Aug 05, 2023 |
| HP            | 844C                        | [36185008dc](https://linux-hardware.org/?probe=36185008dc) | Aug 03, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [3f09ac4cae](https://linux-hardware.org/?probe=3f09ac4cae) | Jul 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | [0a3cc7970c](https://linux-hardware.org/?probe=0a3cc7970c) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| ASRock        | X670E Steel Legend          | [8744428bf6](https://linux-hardware.org/?probe=8744428bf6) | Jul 23, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| ASRock        | B450 Gaming K4              | [ad2c07dc8e](https://linux-hardware.org/?probe=ad2c07dc8e) | Jul 17, 2023 |
| Lenovo        | MAHOBAY                     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| ASRock        | B450 Gaming K4              | [1c43d30f02](https://linux-hardware.org/?probe=1c43d30f02) | Jul 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [7573efcc6c](https://linux-hardware.org/?probe=7573efcc6c) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [30d6b8bfde](https://linux-hardware.org/?probe=30d6b8bfde) | Jul 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [4b2cf13c22](https://linux-hardware.org/?probe=4b2cf13c22) | Jul 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [07c8a86c16](https://linux-hardware.org/?probe=07c8a86c16) | Jul 02, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [ed171ca808](https://linux-hardware.org/?probe=ed171ca808) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [62dd78e250](https://linux-hardware.org/?probe=62dd78e250) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fd367d0725](https://linux-hardware.org/?probe=fd367d0725) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | [edf3326608](https://linux-hardware.org/?probe=edf3326608) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | [9ef5114c59](https://linux-hardware.org/?probe=9ef5114c59) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| Acer          | Aspire XC600 v1.0           | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| ASUSTek       | PRIME Z590-P                | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [72fc2eea56](https://linux-hardware.org/?probe=72fc2eea56) | Jun 03, 2023 |
| ASRock        | B450 Gaming K4              | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| ASUSTek       | PRIME Z390-A                | [9131b2b568](https://linux-hardware.org/?probe=9131b2b568) | May 31, 2023 |
| Gigabyte      | B660 DS3H DDR4              | [807dd44df4](https://linux-hardware.org/?probe=807dd44df4) | May 28, 2023 |
| MSI           | B150M MORTAR                | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| BESSTAR Te... | HM90                        | [bc2b7d421d](https://linux-hardware.org/?probe=bc2b7d421d) | May 22, 2023 |
| Gigabyte      | EP45T-UD3R                  | [848d0db1b2](https://linux-hardware.org/?probe=848d0db1b2) | May 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [9419d4d25c](https://linux-hardware.org/?probe=9419d4d25c) | May 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | [f48dba1e04](https://linux-hardware.org/?probe=f48dba1e04) | May 16, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [b65333ae05](https://linux-hardware.org/?probe=b65333ae05) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | [9caca8f4cc](https://linux-hardware.org/?probe=9caca8f4cc) | May 10, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [c8ab230418](https://linux-hardware.org/?probe=c8ab230418) | May 08, 2023 |
| Dell          | 0NW6H5 A00                  | [11e8fb1ecd](https://linux-hardware.org/?probe=11e8fb1ecd) | May 02, 2023 |
| Dell          | 0NW6H5 A00                  | [2675aa56c4](https://linux-hardware.org/?probe=2675aa56c4) | May 02, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| ASUSTek       | Z170-P                      | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| HP            | 339A                        | [1be48a395d](https://linux-hardware.org/?probe=1be48a395d) | Apr 21, 2023 |
| Acer          | Aspire XC-230               | [d31e8d7c7d](https://linux-hardware.org/?probe=d31e8d7c7d) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [ebdd0f2a6a](https://linux-hardware.org/?probe=ebdd0f2a6a) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | [878d249691](https://linux-hardware.org/?probe=878d249691) | Apr 18, 2023 |
| Pegatron      | 2AD5                        | [245db62c73](https://linux-hardware.org/?probe=245db62c73) | Apr 18, 2023 |
| Pegatron      | 2AD5                        | [ad23efbf03](https://linux-hardware.org/?probe=ad23efbf03) | Apr 14, 2023 |
| HP            | 339A                        | [57e1af32cd](https://linux-hardware.org/?probe=57e1af32cd) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [1bf207dfca](https://linux-hardware.org/?probe=1bf207dfca) | Apr 13, 2023 |
| Lenovo        | NO DPK                      | [4d84f3549a](https://linux-hardware.org/?probe=4d84f3549a) | Apr 13, 2023 |
| MSI           | 970 GAMING                  | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [32c138c982](https://linux-hardware.org/?probe=32c138c982) | Mar 31, 2023 |
| HP            | 3398                        | [ed9f84a231](https://linux-hardware.org/?probe=ed9f84a231) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [d1e1b40549](https://linux-hardware.org/?probe=d1e1b40549) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bcd49e85cb](https://linux-hardware.org/?probe=bcd49e85cb) | Mar 27, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [c722a5f7b2](https://linux-hardware.org/?probe=c722a5f7b2) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [56854770ba](https://linux-hardware.org/?probe=56854770ba) | Mar 24, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [62a95efc48](https://linux-hardware.org/?probe=62a95efc48) | Mar 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASUSTek       | PRIME X570-P                | [8681f176da](https://linux-hardware.org/?probe=8681f176da) | Mar 17, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [f3bb3c5ef1](https://linux-hardware.org/?probe=f3bb3c5ef1) | Mar 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [fc7d8aee1f](https://linux-hardware.org/?probe=fc7d8aee1f) | Mar 16, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| Acer          | Aspire X1935                | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| ASRock        | X570M Pro4                  | [d3ac8dd45f](https://linux-hardware.org/?probe=d3ac8dd45f) | Mar 11, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [fd33b65218](https://linux-hardware.org/?probe=fd33b65218) | Mar 04, 2023 |
| ASUSTek       | SABERTOOTH P67              | [80720d46a2](https://linux-hardware.org/?probe=80720d46a2) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH P67              | [dd01af3afe](https://linux-hardware.org/?probe=dd01af3afe) | Mar 03, 2023 |
| HP            | 3032h                       | [007bbeffa0](https://linux-hardware.org/?probe=007bbeffa0) | Feb 26, 2023 |
| Dell          | 01TN68 A02                  | [ce7bdb1ddf](https://linux-hardware.org/?probe=ce7bdb1ddf) | Feb 21, 2023 |
| Dell          | 01TN68 A02                  | [0dd1f15a92](https://linux-hardware.org/?probe=0dd1f15a92) | Feb 21, 2023 |
| HP            | 1497                        | [47ffeac7cf](https://linux-hardware.org/?probe=47ffeac7cf) | Feb 20, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [9f6834d4a9](https://linux-hardware.org/?probe=9f6834d4a9) | Feb 17, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [131f8f99a2](https://linux-hardware.org/?probe=131f8f99a2) | Feb 17, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [01355a0714](https://linux-hardware.org/?probe=01355a0714) | Feb 17, 2023 |
| ASRock        | H81M-HDS                    | [b744809cc2](https://linux-hardware.org/?probe=b744809cc2) | Feb 14, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | [a527005a2a](https://linux-hardware.org/?probe=a527005a2a) | Feb 06, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [4d007a868e](https://linux-hardware.org/?probe=4d007a868e) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [29dc75351d](https://linux-hardware.org/?probe=29dc75351d) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [54d35f2b7f](https://linux-hardware.org/?probe=54d35f2b7f) | Feb 03, 2023 |
| HP            | 1905                        | [9ddf75323e](https://linux-hardware.org/?probe=9ddf75323e) | Feb 03, 2023 |
| ASRock        | X300M-STX                   | [5ce1aa97c6](https://linux-hardware.org/?probe=5ce1aa97c6) | Feb 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | [28f4fb8e15](https://linux-hardware.org/?probe=28f4fb8e15) | Feb 01, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ef9c1299e6](https://linux-hardware.org/?probe=ef9c1299e6) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [78b817b650](https://linux-hardware.org/?probe=78b817b650) | Jan 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4f24524e7d](https://linux-hardware.org/?probe=4f24524e7d) | Jan 19, 2023 |
| ASRock        | B550M-ITX/ac                | [a7ac9067b0](https://linux-hardware.org/?probe=a7ac9067b0) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fd99b07929](https://linux-hardware.org/?probe=fd99b07929) | Jan 18, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [5480333c5b](https://linux-hardware.org/?probe=5480333c5b) | Jan 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [286de51ef8](https://linux-hardware.org/?probe=286de51ef8) | Jan 13, 2023 |
| HP            | ProLiant MicroServer Gen... | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [fcda893618](https://linux-hardware.org/?probe=fcda893618) | Jan 13, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | [fcc2d12f0d](https://linux-hardware.org/?probe=fcc2d12f0d) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| ASRock        | B450M-HDV R4.0              | [df9ca70fa3](https://linux-hardware.org/?probe=df9ca70fa3) | Jan 02, 2023 |
| Gigabyte      | P85-D3                      | [8d017ea6af](https://linux-hardware.org/?probe=8d017ea6af) | Jan 01, 2023 |
| Gigabyte      | P85-D3                      | [aebeaf8b5e](https://linux-hardware.org/?probe=aebeaf8b5e) | Jan 01, 2023 |
| ASUSTek       | PRIME Z390-A                | [da48bed048](https://linux-hardware.org/?probe=da48bed048) | Dec 24, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [e964534175](https://linux-hardware.org/?probe=e964534175) | Dec 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d367461182](https://linux-hardware.org/?probe=d367461182) | Dec 19, 2022 |
| ASUSTek       | PRIME Z270-A                | [ea3dbee733](https://linux-hardware.org/?probe=ea3dbee733) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | [441dc6d8a0](https://linux-hardware.org/?probe=441dc6d8a0) | Dec 13, 2022 |
| Gigabyte      | B650 GAMING X AX            | [2473215632](https://linux-hardware.org/?probe=2473215632) | Dec 10, 2022 |
| ASUSTek       | M80CJ-O                     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| Lenovo        | SHARKBAY NOK                | [ef7a013f9b](https://linux-hardware.org/?probe=ef7a013f9b) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [6b2389329d](https://linux-hardware.org/?probe=6b2389329d) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [9282404406](https://linux-hardware.org/?probe=9282404406) | Nov 30, 2022 |
| ASUSTek       | PRIME TRX40-PRO             | [ecafbb7acb](https://linux-hardware.org/?probe=ecafbb7acb) | Nov 20, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [9b0f3f926d](https://linux-hardware.org/?probe=9b0f3f926d) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [1cc37489d5](https://linux-hardware.org/?probe=1cc37489d5) | Nov 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [ea05374336](https://linux-hardware.org/?probe=ea05374336) | Nov 19, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [de3eac26e1](https://linux-hardware.org/?probe=de3eac26e1) | Nov 18, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [07b8a83017](https://linux-hardware.org/?probe=07b8a83017) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [75ffcfaf88](https://linux-hardware.org/?probe=75ffcfaf88) | Nov 11, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [9a7d0e6d37](https://linux-hardware.org/?probe=9a7d0e6d37) | Nov 03, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [81a04d40a3](https://linux-hardware.org/?probe=81a04d40a3) | Nov 03, 2022 |
| Inventec      | DQ Class A02                | [f64d3223c5](https://linux-hardware.org/?probe=f64d3223c5) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | [c4fddde4b6](https://linux-hardware.org/?probe=c4fddde4b6) | Oct 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| Gigabyte      | 990FXA-UD5                  | [7c8d5609e0](https://linux-hardware.org/?probe=7c8d5609e0) | Sep 22, 2022 |
| Gigabyte      | EX58-UD4P                   | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [e55484acd4](https://linux-hardware.org/?probe=e55484acd4) | Sep 17, 2022 |
| Lenovo        | SDK0J40700 WIN              | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| MSI           | X570-A PRO                  | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Gigabyte      | 990FXA-UD5                  | [e5364d8761](https://linux-hardware.org/?probe=e5364d8761) | Sep 01, 2022 |
| Unknown       | TB-4000                     | [8f7f2e486a](https://linux-hardware.org/?probe=8f7f2e486a) | Aug 30, 2022 |
| ASUSTek       | SABERTOOTH X58              | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| Gigabyte      | P85-D3                      | [06b934d14f](https://linux-hardware.org/?probe=06b934d14f) | Aug 26, 2022 |
| Unknown       | TB-4000                     | [a3cfbd4659](https://linux-hardware.org/?probe=a3cfbd4659) | Aug 25, 2022 |
| Gigabyte      | B460M DS3H V2               | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| Unknown       | TB-4000                     | [906699e408](https://linux-hardware.org/?probe=906699e408) | Aug 14, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [0009de2dbb](https://linux-hardware.org/?probe=0009de2dbb) | Aug 11, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Lenovo        | SDK0J40700 WIN              | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Packard Be... | H57M01                      | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| Lenovo        | SDK0J40700 WIN              | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| Gigabyte      | MJPLNAB-00                  | [d414e51a0c](https://linux-hardware.org/?probe=d414e51a0c) | Jul 23, 2022 |
| Gigabyte      | MJPLNAB-00                  | [9dcb499f3e](https://linux-hardware.org/?probe=9dcb499f3e) | Jul 23, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [a74834b383](https://linux-hardware.org/?probe=a74834b383) | Jul 04, 2022 |
| HP            | 805D                        | [3610332b9c](https://linux-hardware.org/?probe=3610332b9c) | Jul 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [c12aa3088a](https://linux-hardware.org/?probe=c12aa3088a) | Jun 30, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [b0c272ff93](https://linux-hardware.org/?probe=b0c272ff93) | Jun 26, 2022 |
| Lenovo        | SDK0J40700 WIN              | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| ASUSTek       | H110I-PLUS                  | [36389b33b6](https://linux-hardware.org/?probe=36389b33b6) | Jun 12, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [d3fdbc7413](https://linux-hardware.org/?probe=d3fdbc7413) | Jun 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [9c7b2faf2c](https://linux-hardware.org/?probe=9c7b2faf2c) | Jun 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a307c95089](https://linux-hardware.org/?probe=a307c95089) | Jun 08, 2022 |
| Unknown       | TB-4000                     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| BESSTAR Te... | HM90                        | [5272429aa9](https://linux-hardware.org/?probe=5272429aa9) | Jun 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| MSI           | 970A-G43                    | [92dd93dd78](https://linux-hardware.org/?probe=92dd93dd78) | May 24, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [bc9270aeff](https://linux-hardware.org/?probe=bc9270aeff) | May 13, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [f0e5f896a4](https://linux-hardware.org/?probe=f0e5f896a4) | May 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [21486c437b](https://linux-hardware.org/?probe=21486c437b) | May 08, 2022 |
| Gigabyte      | G41M-Combo                  | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Unknown       | TB-4000                     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| MSI           | MS-1T11                     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [91aa85fff9](https://linux-hardware.org/?probe=91aa85fff9) | Apr 21, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [27825828c9](https://linux-hardware.org/?probe=27825828c9) | Apr 05, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [ddc3550f6b](https://linux-hardware.org/?probe=ddc3550f6b) | Apr 04, 2022 |
| ASRock        | X99 Extreme4                | [e29b4c30f1](https://linux-hardware.org/?probe=e29b4c30f1) | Apr 04, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a5c5028fde](https://linux-hardware.org/?probe=a5c5028fde) | Apr 03, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [d978436f5f](https://linux-hardware.org/?probe=d978436f5f) | Apr 03, 2022 |
| ASUSTek       | PRIME Z370-P                | [f3cd1a314c](https://linux-hardware.org/?probe=f3cd1a314c) | Mar 25, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [4ce05dd1e2](https://linux-hardware.org/?probe=4ce05dd1e2) | Mar 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f3b52d9201](https://linux-hardware.org/?probe=f3b52d9201) | Mar 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5c40bf9192](https://linux-hardware.org/?probe=5c40bf9192) | Mar 21, 2022 |
| ASUSTek       | PRIME B250M-A               | [8be4c394f1](https://linux-hardware.org/?probe=8be4c394f1) | Mar 18, 2022 |
| Gigabyte      | MFLP7IP-00                  | [304c5939e7](https://linux-hardware.org/?probe=304c5939e7) | Mar 18, 2022 |
| Shuttle       | X50V2PLUS V1.00             | [0bd650dfff](https://linux-hardware.org/?probe=0bd650dfff) | Mar 16, 2022 |
| ASUSTek       | PRIME A320M-K               | [500a30847d](https://linux-hardware.org/?probe=500a30847d) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [04e8e7704e](https://linux-hardware.org/?probe=04e8e7704e) | Feb 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c1929d8540](https://linux-hardware.org/?probe=c1929d8540) | Feb 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [bdc86d995a](https://linux-hardware.org/?probe=bdc86d995a) | Feb 21, 2022 |
| Dell          | 0KC9NP A01                  | [f9a0fa24f8](https://linux-hardware.org/?probe=f9a0fa24f8) | Feb 18, 2022 |
| ASRock        | FM2A55M-DGS                 | [efe38992bd](https://linux-hardware.org/?probe=efe38992bd) | Feb 15, 2022 |
| Dell          | 0GTK4K A02                  | [466029e620](https://linux-hardware.org/?probe=466029e620) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e63f72d407](https://linux-hardware.org/?probe=e63f72d407) | Feb 07, 2022 |
| Medion        | MS-7800                     | [9693a4d35c](https://linux-hardware.org/?probe=9693a4d35c) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [40ed6ce0c5](https://linux-hardware.org/?probe=40ed6ce0c5) | Feb 04, 2022 |
| Unknown       | TB-4000                     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [b8f4a15736](https://linux-hardware.org/?probe=b8f4a15736) | Jan 25, 2022 |
| ASUSTek       | P8H67-M                     | [a69dd56657](https://linux-hardware.org/?probe=a69dd56657) | Jan 21, 2022 |
| Gigabyte      | B460M AORUS PRO             | [1e301a4129](https://linux-hardware.org/?probe=1e301a4129) | Jan 19, 2022 |
| Acer          | Predator G6-710             | [29bdcc72c9](https://linux-hardware.org/?probe=29bdcc72c9) | Jan 18, 2022 |
| ASUSTek       | P8H67-M                     | [1568252a07](https://linux-hardware.org/?probe=1568252a07) | Jan 17, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | [46932917d4](https://linux-hardware.org/?probe=46932917d4) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| MSI           | A68HM GRENADE               | [18ca0bdd91](https://linux-hardware.org/?probe=18ca0bdd91) | Dec 27, 2021 |
| MSI           | X470 GAMING PRO             | [d683987eea](https://linux-hardware.org/?probe=d683987eea) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [32e8c7ccb2](https://linux-hardware.org/?probe=32e8c7ccb2) | Dec 22, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [1e14543dfd](https://linux-hardware.org/?probe=1e14543dfd) | Dec 18, 2021 |
| HP            | 3031h                       | [8a8888c824](https://linux-hardware.org/?probe=8a8888c824) | Dec 17, 2021 |
| ABIT          | I-G31                       | [048b7bcf6a](https://linux-hardware.org/?probe=048b7bcf6a) | Dec 13, 2021 |
| Dell          | 0YXT71 A01                  | [fbe4f7fdb9](https://linux-hardware.org/?probe=fbe4f7fdb9) | Dec 12, 2021 |
| ASUSTek       | Z170-P                      | [6e857bc210](https://linux-hardware.org/?probe=6e857bc210) | Dec 09, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [ac173fd5ba](https://linux-hardware.org/?probe=ac173fd5ba) | Dec 09, 2021 |
| ASUSTek       | PRIME Z390-A                | [e884cd44db](https://linux-hardware.org/?probe=e884cd44db) | Dec 08, 2021 |
| HP            | 3031h                       | [68cf960e7f](https://linux-hardware.org/?probe=68cf960e7f) | Dec 02, 2021 |
| HP            | 3031h                       | [1c49cd6404](https://linux-hardware.org/?probe=1c49cd6404) | Dec 02, 2021 |
| HP            | 8299                        | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| HP            | 8299                        | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [6071fde7dd](https://linux-hardware.org/?probe=6071fde7dd) | Nov 28, 2021 |
| Acer          | Aspire X3995                | [cde003006d](https://linux-hardware.org/?probe=cde003006d) | Nov 22, 2021 |
| Acer          | Aspire X3995                | [2e97d6ef1c](https://linux-hardware.org/?probe=2e97d6ef1c) | Nov 22, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [ea4842466c](https://linux-hardware.org/?probe=ea4842466c) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [faf9e68f7a](https://linux-hardware.org/?probe=faf9e68f7a) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [2b2ea53377](https://linux-hardware.org/?probe=2b2ea53377) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [b4512f4b54](https://linux-hardware.org/?probe=b4512f4b54) | Nov 18, 2021 |
| ASRock        | Z170 Gaming K4              | [53281d6c95](https://linux-hardware.org/?probe=53281d6c95) | Nov 17, 2021 |
| Dell          | 0YXT71 A01                  | [6f599a0889](https://linux-hardware.org/?probe=6f599a0889) | Nov 03, 2021 |
| T-bao         | MINI PC V1.0                | [72ce248d0c](https://linux-hardware.org/?probe=72ce248d0c) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [be8c7e44de](https://linux-hardware.org/?probe=be8c7e44de) | Oct 23, 2021 |
| MSI           | Z77A-G45                    | [7a31ca9e22](https://linux-hardware.org/?probe=7a31ca9e22) | Oct 23, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [e1ddc26c5e](https://linux-hardware.org/?probe=e1ddc26c5e) | Oct 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [c0c2de7d52](https://linux-hardware.org/?probe=c0c2de7d52) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [56f27fef6e](https://linux-hardware.org/?probe=56f27fef6e) | Oct 16, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [a36474b9ff](https://linux-hardware.org/?probe=a36474b9ff) | Oct 04, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASRock        | H470M-ITX/ac                | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [201176552b](https://linux-hardware.org/?probe=201176552b) | Sep 21, 2021 |
| Medion        | B360H4-EM V1.0              | [1985156471](https://linux-hardware.org/?probe=1985156471) | Sep 19, 2021 |
| Dell          | 0XCR8D A02                  | [9cb5ea4f4a](https://linux-hardware.org/?probe=9cb5ea4f4a) | Sep 11, 2021 |
| ASRock        | P55M Pro                    | [b6408718ee](https://linux-hardware.org/?probe=b6408718ee) | Sep 02, 2021 |
| ASRock        | 980DE3/U3S3                 | [e8aadc0af0](https://linux-hardware.org/?probe=e8aadc0af0) | Aug 24, 2021 |
| Medion        | MS-7616                     | [cbd20c24d8](https://linux-hardware.org/?probe=cbd20c24d8) | Aug 20, 2021 |
| HP            | 212B                        | [ee483c7463](https://linux-hardware.org/?probe=ee483c7463) | Aug 08, 2021 |
| ASUSTek       | P8B75-M                     | [4d29ffa0f7](https://linux-hardware.org/?probe=4d29ffa0f7) | Aug 03, 2021 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [4135f29492](https://linux-hardware.org/?probe=4135f29492) | Aug 02, 2021 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [59cd9e3edd](https://linux-hardware.org/?probe=59cd9e3edd) | Aug 01, 2021 |
| Pegatron      | 2AB6                        | [79dffb5346](https://linux-hardware.org/?probe=79dffb5346) | Jul 31, 2021 |
| Gigabyte      | P85-D3                      | [51f83ebd4a](https://linux-hardware.org/?probe=51f83ebd4a) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Lenovo        | ThinkCentre Edge71 1577G... | [cf7f13e31c](https://linux-hardware.org/?probe=cf7f13e31c) | Jul 29, 2021 |
| ASRock        | H310CM-DVS                  | [5ae2994458](https://linux-hardware.org/?probe=5ae2994458) | Jul 28, 2021 |
| Medion        | Z370H4-EM                   | [f19570a630](https://linux-hardware.org/?probe=f19570a630) | Jul 24, 2021 |
| Shuttle       | FH67                        | [611a7c28dc](https://linux-hardware.org/?probe=611a7c28dc) | Jul 22, 2021 |
| Shuttle       | FH67                        | [3d3fb6c381](https://linux-hardware.org/?probe=3d3fb6c381) | Jul 22, 2021 |
| ASRock        | 980DE3/U3S3                 | [9ca97016e0](https://linux-hardware.org/?probe=9ca97016e0) | Jul 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [5fcfefa75a](https://linux-hardware.org/?probe=5fcfefa75a) | Jul 19, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [0c0d9cc784](https://linux-hardware.org/?probe=0c0d9cc784) | Jul 15, 2021 |
| ASUSTek       | PRIME Z370-A                | [208a9ee715](https://linux-hardware.org/?probe=208a9ee715) | Jun 23, 2021 |
| ASUSTek       | PRIME Z370-A                | [86fce52939](https://linux-hardware.org/?probe=86fce52939) | Jun 23, 2021 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [ca43a33e1d](https://linux-hardware.org/?probe=ca43a33e1d) | Jun 18, 2021 |
| Lenovo        | Bantry CRB SDK0J40697 WI... | [4a0a83693b](https://linux-hardware.org/?probe=4a0a83693b) | Jun 14, 2021 |
| ASRock        | P55M Pro                    | [cac3198045](https://linux-hardware.org/?probe=cac3198045) | Jun 14, 2021 |
| HP            | 212B                        | [b72ab2aea5](https://linux-hardware.org/?probe=b72ab2aea5) | Jun 09, 2021 |
| ASRock        | P55M Pro                    | [b994c1917a](https://linux-hardware.org/?probe=b994c1917a) | Jun 03, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| MSI           | Z87 MPOWER                  | [848def4822](https://linux-hardware.org/?probe=848def4822) | May 29, 2021 |
| ASUSTek       | PRIME B450M-A               | [e0217f85a6](https://linux-hardware.org/?probe=e0217f85a6) | May 28, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [f9358acedf](https://linux-hardware.org/?probe=f9358acedf) | May 27, 2021 |
| ASUSTek       | PRIME B450M-A               | [787c1b3a8c](https://linux-hardware.org/?probe=787c1b3a8c) | May 26, 2021 |
| ASUSTek       | B85M-G                      | [92f19ca1e6](https://linux-hardware.org/?probe=92f19ca1e6) | May 25, 2021 |
| ASUSTek       | NARRA2                      | [0b2cf24d70](https://linux-hardware.org/?probe=0b2cf24d70) | May 25, 2021 |
| Medion        | MS-7646                     | [799be90f9c](https://linux-hardware.org/?probe=799be90f9c) | May 11, 2021 |
| ASRock        | J4105-ITX                   | [2cb8135a58](https://linux-hardware.org/?probe=2cb8135a58) | May 08, 2021 |
| ASUSTek       | PRIME B450M-K               | [a8271c73ee](https://linux-hardware.org/?probe=a8271c73ee) | May 02, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [9e0202e76a](https://linux-hardware.org/?probe=9e0202e76a) | Apr 27, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [31cb6e83ed](https://linux-hardware.org/?probe=31cb6e83ed) | Apr 19, 2021 |
| Acer          | Veriton M275                | [246a662951](https://linux-hardware.org/?probe=246a662951) | Apr 17, 2021 |
| Gigabyte      | B75M-D3H                    | [cd772af567](https://linux-hardware.org/?probe=cd772af567) | Apr 14, 2021 |
| Gigabyte      | EP35-DS4                    | [e37cf6fc8d](https://linux-hardware.org/?probe=e37cf6fc8d) | Apr 12, 2021 |
| MSI           | Z87 MPOWER                  | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09cf1ed052](https://linux-hardware.org/?probe=09cf1ed052) | Apr 08, 2021 |
| ASRock        | Z270 Pro4                   | [b90dd1b4d2](https://linux-hardware.org/?probe=b90dd1b4d2) | Apr 02, 2021 |
| Medion        | MS-7797                     | [947bc894eb](https://linux-hardware.org/?probe=947bc894eb) | Apr 01, 2021 |
| ASUSTek       | PRIME Z370-A                | [757d1d0707](https://linux-hardware.org/?probe=757d1d0707) | Mar 31, 2021 |
| ASUSTek       | PRIME Z370-A                | [eb1782ad49](https://linux-hardware.org/?probe=eb1782ad49) | Mar 31, 2021 |
| Dell          | 0CU409                      | [53a8c28aed](https://linux-hardware.org/?probe=53a8c28aed) | Mar 24, 2021 |
| Acer          | Aspire XC-605               | [f8ad366bd9](https://linux-hardware.org/?probe=f8ad366bd9) | Mar 19, 2021 |
| ASUSTek       | PRIME X470-PRO              | [54288c23c9](https://linux-hardware.org/?probe=54288c23c9) | Mar 18, 2021 |
| ECS           | Nettle3                     | [f7ec16d7e7](https://linux-hardware.org/?probe=f7ec16d7e7) | Mar 16, 2021 |
| HP            | 3032h                       | [79b0bf2416](https://linux-hardware.org/?probe=79b0bf2416) | Mar 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [9ebf280981](https://linux-hardware.org/?probe=9ebf280981) | Mar 05, 2021 |
| Gigabyte      | A320M-S2H-CF                | [efa91095ab](https://linux-hardware.org/?probe=efa91095ab) | Mar 05, 2021 |
| ASUSTek       | M4N75TD                     | [9daf1b6529](https://linux-hardware.org/?probe=9daf1b6529) | Feb 28, 2021 |
| ASUSTek       | P5P43TD                     | [3a2604a18a](https://linux-hardware.org/?probe=3a2604a18a) | Feb 27, 2021 |
| HP            | 1998                        | [43bd925171](https://linux-hardware.org/?probe=43bd925171) | Feb 27, 2021 |
| ASUSTek       | PRIME Z270-A                | [66ce820cff](https://linux-hardware.org/?probe=66ce820cff) | Feb 25, 2021 |
| ASRock        | QC5000-ITX/WiFi             | [d321b1eb90](https://linux-hardware.org/?probe=d321b1eb90) | Feb 21, 2021 |
| ASRock        | Z270 Pro4                   | [7114de29ed](https://linux-hardware.org/?probe=7114de29ed) | Feb 20, 2021 |
| Medion        | MS-7797                     | [3c4d9332e4](https://linux-hardware.org/?probe=3c4d9332e4) | Feb 19, 2021 |
| MSI           | B150M PRO-VH                | [255e61b850](https://linux-hardware.org/?probe=255e61b850) | Feb 13, 2021 |
| Medion        | MS-7797                     | [7e6811c842](https://linux-hardware.org/?probe=7e6811c842) | Feb 10, 2021 |
| Medion        | MS-7797                     | [394c3c87f4](https://linux-hardware.org/?probe=394c3c87f4) | Feb 10, 2021 |
| ASRock        | B550M-ITX/ac                | [909d040ae4](https://linux-hardware.org/?probe=909d040ae4) | Feb 07, 2021 |
| Medion        | MS-7708                     | [53ba901c28](https://linux-hardware.org/?probe=53ba901c28) | Feb 01, 2021 |
| Medion        | MS-7708                     | [8ef1638192](https://linux-hardware.org/?probe=8ef1638192) | Feb 01, 2021 |
| Lenovo        | ThinkServer TS140           | [8f911a91ca](https://linux-hardware.org/?probe=8f911a91ca) | Jan 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [34257c05a5](https://linux-hardware.org/?probe=34257c05a5) | Jan 27, 2021 |
| Gigabyte      | GA-780T-D3L                 | [2f2ede94cb](https://linux-hardware.org/?probe=2f2ede94cb) | Jan 17, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | [fc3f785613](https://linux-hardware.org/?probe=fc3f785613) | Jan 15, 2021 |
| NEXCOM        | NDIS B322                   | [c2789ca746](https://linux-hardware.org/?probe=c2789ca746) | Jan 06, 2021 |
| Gigabyte      | B550M DS3H                  | [16d30d3356](https://linux-hardware.org/?probe=16d30d3356) | Dec 30, 2020 |
| Gigabyte      | B550M DS3H                  | [944fc761f4](https://linux-hardware.org/?probe=944fc761f4) | Dec 30, 2020 |
| ASUSTek       | Z97-K                       | [3eacdc5965](https://linux-hardware.org/?probe=3eacdc5965) | Dec 28, 2020 |
| MSI           | B150M PRO-VH                | [f225de5ed7](https://linux-hardware.org/?probe=f225de5ed7) | Dec 25, 2020 |
| MSI           | B150M PRO-VH                | [6971a673ec](https://linux-hardware.org/?probe=6971a673ec) | Dec 25, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [13d6a7172d](https://linux-hardware.org/?probe=13d6a7172d) | Dec 15, 2020 |
| Gigabyte      | J3455N-D3H                  | [a9a1ba9727](https://linux-hardware.org/?probe=a9a1ba9727) | Dec 13, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [968983910f](https://linux-hardware.org/?probe=968983910f) | Dec 08, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [b3c78e0e70](https://linux-hardware.org/?probe=b3c78e0e70) | Dec 07, 2020 |
| Gigabyte      | B550 AORUS PRO AC           | [1a5eee726d](https://linux-hardware.org/?probe=1a5eee726d) | Dec 05, 2020 |
| MSI           | MPG Z490 GAMING PLUS        | [95b94bfe02](https://linux-hardware.org/?probe=95b94bfe02) | Dec 04, 2020 |
| MSI           | X570-A PRO                  | [0c57860179](https://linux-hardware.org/?probe=0c57860179) | Dec 02, 2020 |
| Medion        | B360H4-EM V1.0              | [718acb9fc0](https://linux-hardware.org/?probe=718acb9fc0) | Dec 02, 2020 |
| MSI           | B150M PRO-VH                | [ed280391f2](https://linux-hardware.org/?probe=ed280391f2) | Nov 30, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [f49b6c5048](https://linux-hardware.org/?probe=f49b6c5048) | Nov 27, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [ce4048d43f](https://linux-hardware.org/?probe=ce4048d43f) | Nov 24, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [9845e5eb1e](https://linux-hardware.org/?probe=9845e5eb1e) | Nov 15, 2020 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [91207c72e3](https://linux-hardware.org/?probe=91207c72e3) | Nov 15, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [d2afbbe9f9](https://linux-hardware.org/?probe=d2afbbe9f9) | Nov 10, 2020 |
| Lenovo        | ThinkCentre Edge72 3484F... | [8864ed7825](https://linux-hardware.org/?probe=8864ed7825) | Nov 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [54f14d0d27](https://linux-hardware.org/?probe=54f14d0d27) | Nov 02, 2020 |
| ASRock        | Z170 OC Formula             | [067d0719a1](https://linux-hardware.org/?probe=067d0719a1) | Oct 30, 2020 |
| ASRock        | TRX40 Creator               | [3b1961ec14](https://linux-hardware.org/?probe=3b1961ec14) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [2e111f0b77](https://linux-hardware.org/?probe=2e111f0b77) | Oct 29, 2020 |
| Dell          | 0CT017                      | [4f36a920b3](https://linux-hardware.org/?probe=4f36a920b3) | Oct 26, 2020 |
| ASRock        | B450M Pro4                  | [375a230939](https://linux-hardware.org/?probe=375a230939) | Oct 26, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [b7a16467ac](https://linux-hardware.org/?probe=b7a16467ac) | Oct 19, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [97ae9ff8fd](https://linux-hardware.org/?probe=97ae9ff8fd) | Oct 16, 2020 |
| ASUSTek       | PRIME B250M-A               | [afee01c14d](https://linux-hardware.org/?probe=afee01c14d) | Oct 11, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [734e996f73](https://linux-hardware.org/?probe=734e996f73) | Oct 07, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [ce1874a3be](https://linux-hardware.org/?probe=ce1874a3be) | Oct 07, 2020 |
| ASRock        | Z170 Extreme4               | [39a631ad3c](https://linux-hardware.org/?probe=39a631ad3c) | Oct 06, 2020 |
| Pegatron      | 2AD5                        | [4d341edca9](https://linux-hardware.org/?probe=4d341edca9) | Oct 05, 2020 |
| MSI           | Z87 MPOWER                  | [c361400ba5](https://linux-hardware.org/?probe=c361400ba5) | Oct 02, 2020 |
| HP            | 3398                        | [95d758781c](https://linux-hardware.org/?probe=95d758781c) | Oct 01, 2020 |
| ASUSTek       | Z170-DELUXE                 | [619ac1f764](https://linux-hardware.org/?probe=619ac1f764) | Sep 30, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [09b275ac93](https://linux-hardware.org/?probe=09b275ac93) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS PRO              | [1fd3e30c8e](https://linux-hardware.org/?probe=1fd3e30c8e) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5032W3M     | [b6dc69bcc6](https://linux-hardware.org/?probe=b6dc69bcc6) | Sep 23, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [4298ad10c2](https://linux-hardware.org/?probe=4298ad10c2) | Sep 05, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [d98e57a21a](https://linux-hardware.org/?probe=d98e57a21a) | Sep 05, 2020 |
| Gigabyte      | X570 GAMING X               | [9cd1bda591](https://linux-hardware.org/?probe=9cd1bda591) | Sep 04, 2020 |
| Medion        | MS-7366                     | [ff7271711d](https://linux-hardware.org/?probe=ff7271711d) | Aug 25, 2020 |
| HP            | 2AFA                        | [b60453f85a](https://linux-hardware.org/?probe=b60453f85a) | Aug 23, 2020 |
| HP            | 2AFA                        | [4c206cac6d](https://linux-hardware.org/?probe=4c206cac6d) | Aug 22, 2020 |
| ASUSTek       | Z170-PRO                    | [7a14a06010](https://linux-hardware.org/?probe=7a14a06010) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [9ac43f513b](https://linux-hardware.org/?probe=9ac43f513b) | Aug 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [5c7a68d981](https://linux-hardware.org/?probe=5c7a68d981) | Aug 07, 2020 |
| Gigabyte      | Z77P-D3                     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| MSI           | B450 TOMAHAWK               | [c44d7421b8](https://linux-hardware.org/?probe=c44d7421b8) | Jul 24, 2020 |
| MSI           | X470 GAMING PRO             | [c12505e247](https://linux-hardware.org/?probe=c12505e247) | Jul 21, 2020 |
| MSI           | X470 GAMING PRO             | [ca1dac6b45](https://linux-hardware.org/?probe=ca1dac6b45) | Jul 21, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [861ca18aab](https://linux-hardware.org/?probe=861ca18aab) | Jul 16, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [ce07e0a768](https://linux-hardware.org/?probe=ce07e0a768) | Jul 14, 2020 |
| Lenovo        | ThinkCentre M58 7359WQR     | [73e0df5013](https://linux-hardware.org/?probe=73e0df5013) | Jul 09, 2020 |
| Gigabyte      | X570 UD                     | [ab1e04310e](https://linux-hardware.org/?probe=ab1e04310e) | Jul 07, 2020 |
| Gigabyte      | X570 UD                     | [319bbe63a2](https://linux-hardware.org/?probe=319bbe63a2) | Jul 07, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [1fa9af511a](https://linux-hardware.org/?probe=1fa9af511a) | Jul 03, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [57643353ce](https://linux-hardware.org/?probe=57643353ce) | Jun 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [9546ca8c2a](https://linux-hardware.org/?probe=9546ca8c2a) | Jun 29, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [b92d2bdb9d](https://linux-hardware.org/?probe=b92d2bdb9d) | Jun 28, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | [8f5fc60880](https://linux-hardware.org/?probe=8f5fc60880) | Jun 20, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [fdabb9483a](https://linux-hardware.org/?probe=fdabb9483a) | Jun 19, 2020 |
| Gigabyte      | Z87X-UD4H-CF                | [bef7a799cc](https://linux-hardware.org/?probe=bef7a799cc) | Jun 18, 2020 |
| Gigabyte      | X570 AORUS MASTER           | [415c3a4a20](https://linux-hardware.org/?probe=415c3a4a20) | Jun 18, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [1bd41519c5](https://linux-hardware.org/?probe=1bd41519c5) | Jun 13, 2020 |
| ASUSTek       | Maximus VIII HERO           | [3e632a857d](https://linux-hardware.org/?probe=3e632a857d) | Jun 06, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [c83816398c](https://linux-hardware.org/?probe=c83816398c) | Jun 05, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [82591ffa30](https://linux-hardware.org/?probe=82591ffa30) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [637d3d6ccc](https://linux-hardware.org/?probe=637d3d6ccc) | Jun 01, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [bde3e045ca](https://linux-hardware.org/?probe=bde3e045ca) | May 31, 2020 |
| ASUSTek       | E45M1-I DELUXE              | [58f57667ee](https://linux-hardware.org/?probe=58f57667ee) | May 25, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [8ab04c0e95](https://linux-hardware.org/?probe=8ab04c0e95) | May 22, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [a1a244d013](https://linux-hardware.org/?probe=a1a244d013) | May 21, 2020 |
| AMI           | Cherry Trail FFD            | [2646be2c9b](https://linux-hardware.org/?probe=2646be2c9b) | May 17, 2020 |
| AMI           | Cherry Trail FFD            | [1abe48ca91](https://linux-hardware.org/?probe=1abe48ca91) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | [aa8b123cdd](https://linux-hardware.org/?probe=aa8b123cdd) | May 17, 2020 |
| Gigabyte      | GA-870A-UD3                 | [c6f0fde0d2](https://linux-hardware.org/?probe=c6f0fde0d2) | May 16, 2020 |
| Gigabyte      | GA-870A-UD3                 | [9d150cc443](https://linux-hardware.org/?probe=9d150cc443) | May 16, 2020 |
| ASUSTek       | B85M-G                      | [f575cb11cb](https://linux-hardware.org/?probe=f575cb11cb) | May 08, 2020 |
| ASRock        | B450 Gaming K4              | [d82dc4eb4f](https://linux-hardware.org/?probe=d82dc4eb4f) | May 01, 2020 |
| ASRock        | B450 Gaming K4              | [c08ec23742](https://linux-hardware.org/?probe=c08ec23742) | May 01, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [3d3bc60c59](https://linux-hardware.org/?probe=3d3bc60c59) | Apr 28, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [ed1abce019](https://linux-hardware.org/?probe=ed1abce019) | Apr 23, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [0cbe6fdb9b](https://linux-hardware.org/?probe=0cbe6fdb9b) | Apr 21, 2020 |
| ASUSTek       | P8Z77-V LE PLUS             | [61d4286e96](https://linux-hardware.org/?probe=61d4286e96) | Apr 06, 2020 |
| ECS           | Nettle3                     | [51538f1902](https://linux-hardware.org/?probe=51538f1902) | Apr 02, 2020 |
| ECS           | Nettle3                     | [5a8f6b27a0](https://linux-hardware.org/?probe=5a8f6b27a0) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [fee80882b4](https://linux-hardware.org/?probe=fee80882b4) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [309423fc5a](https://linux-hardware.org/?probe=309423fc5a) | Apr 02, 2020 |
| ASRock        | Z77 Pro4-M                  | [cc7be1cc44](https://linux-hardware.org/?probe=cc7be1cc44) | Apr 02, 2020 |
| Dell          | 0F373D A00                  | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [fbc59a267b](https://linux-hardware.org/?probe=fbc59a267b) | Mar 23, 2020 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [548b742928](https://linux-hardware.org/?probe=548b742928) | Mar 22, 2020 |
| HP            | ProLiant MicroServer        | [b8fc545d86](https://linux-hardware.org/?probe=b8fc545d86) | Mar 19, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [73276b8f74](https://linux-hardware.org/?probe=73276b8f74) | Mar 09, 2020 |
| ASUSTek       | P5QL-VM EPU                 | [da8bd96ca5](https://linux-hardware.org/?probe=da8bd96ca5) | Mar 07, 2020 |
| ASUSTek       | Z97-A-USB31                 | [63b94ee87e](https://linux-hardware.org/?probe=63b94ee87e) | Mar 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | [da2608360d](https://linux-hardware.org/?probe=da2608360d) | Feb 23, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | [078b188645](https://linux-hardware.org/?probe=078b188645) | Feb 16, 2020 |
| Gigabyte      | Z68X-UD7-B3                 | [700eabb523](https://linux-hardware.org/?probe=700eabb523) | Feb 15, 2020 |
| HP            | 86D3                        | [83613548dc](https://linux-hardware.org/?probe=83613548dc) | Feb 13, 2020 |
| Alienware     | 06G6JW A00                  | [f3eab06bb2](https://linux-hardware.org/?probe=f3eab06bb2) | Feb 10, 2020 |
| MSI           | Z97-G43                     | [01c2993ade](https://linux-hardware.org/?probe=01c2993ade) | Jan 25, 2020 |
| HP            | ProLiant ML350 G6           | [3472820868](https://linux-hardware.org/?probe=3472820868) | Jan 17, 2020 |
| HP            | ProLiant ML350 G6           | [86fb31ed72](https://linux-hardware.org/?probe=86fb31ed72) | Jan 16, 2020 |
| ASUSTek       | M4A88T-M                    | [643a92956a](https://linux-hardware.org/?probe=643a92956a) | Jan 13, 2020 |
| Gigabyte      | EG41M-US2H                  | [697f2f05e2](https://linux-hardware.org/?probe=697f2f05e2) | Jan 12, 2020 |
| eMachines     | ET1850                      | [7c1a93e022](https://linux-hardware.org/?probe=7c1a93e022) | Dec 23, 2019 |
| Gigabyte      | Z77P-D3                     | [3de82df337](https://linux-hardware.org/?probe=3de82df337) | Dec 17, 2019 |
| Gigabyte      | H61N-USB3                   | [ee74c9e54c](https://linux-hardware.org/?probe=ee74c9e54c) | Dec 12, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | [44e3d900f5](https://linux-hardware.org/?probe=44e3d900f5) | Dec 02, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ed930b473b](https://linux-hardware.org/?probe=ed930b473b) | Nov 24, 2019 |
| Gigabyte      | Z77P-D3                     | [e2bc0cfec5](https://linux-hardware.org/?probe=e2bc0cfec5) | Nov 24, 2019 |
| Gigabyte      | Z77P-D3                     | [53e0ab44e0](https://linux-hardware.org/?probe=53e0ab44e0) | Nov 23, 2019 |
| Gigabyte      | Z77P-D3                     | [9a1e3d5db9](https://linux-hardware.org/?probe=9a1e3d5db9) | Nov 23, 2019 |
| Packard Be... | IMEDIA L4880                | [a9a53bf7f4](https://linux-hardware.org/?probe=a9a53bf7f4) | Nov 18, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [0029decba2](https://linux-hardware.org/?probe=0029decba2) | Nov 08, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [6b013738c6](https://linux-hardware.org/?probe=6b013738c6) | Oct 24, 2019 |
| HP            | 3397                        | [27d2857bca](https://linux-hardware.org/?probe=27d2857bca) | Sep 30, 2019 |
| Gigabyte      | EG41M-US2H                  | [9717827455](https://linux-hardware.org/?probe=9717827455) | Sep 27, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [6298b19758](https://linux-hardware.org/?probe=6298b19758) | Sep 25, 2019 |
| ASUSTek       | PRIME Z370-A                | [6d7e7fdc51](https://linux-hardware.org/?probe=6d7e7fdc51) | Sep 23, 2019 |
| ASUSTek       | Z10PA-D8 Series             | [7436c74dcb](https://linux-hardware.org/?probe=7436c74dcb) | Sep 11, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [340c34926f](https://linux-hardware.org/?probe=340c34926f) | Aug 22, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [d1e5249043](https://linux-hardware.org/?probe=d1e5249043) | Aug 19, 2019 |
| ASRock        | HM65-MXM                    | [0d687e29cb](https://linux-hardware.org/?probe=0d687e29cb) | Aug 12, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [fbdbd66417](https://linux-hardware.org/?probe=fbdbd66417) | Aug 11, 2019 |
| Dell          | 06X1TJ A01                  | [faf781dda9](https://linux-hardware.org/?probe=faf781dda9) | Aug 05, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [2ed5b5afc5](https://linux-hardware.org/?probe=2ed5b5afc5) | Jul 21, 2019 |
| MSI           | B350M MORTAR ARCTIC         | [aa7226b798](https://linux-hardware.org/?probe=aa7226b798) | Jul 21, 2019 |
| Lenovo        | ThinkCentre M81 5032W3M     | [cb4983baf6](https://linux-hardware.org/?probe=cb4983baf6) | Jul 18, 2019 |
| ASRock        | FM2A78M-HD+                 | [4c45eb1803](https://linux-hardware.org/?probe=4c45eb1803) | Jul 10, 2019 |
| Intel         | DH77EB AAG39073-304         | [08b86f6f4c](https://linux-hardware.org/?probe=08b86f6f4c) | Jul 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [706e1e0baf](https://linux-hardware.org/?probe=706e1e0baf) | Jun 30, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [11a091fb81](https://linux-hardware.org/?probe=11a091fb81) | Jun 22, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [8fc47ce184](https://linux-hardware.org/?probe=8fc47ce184) | Jun 15, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [7ba347026e](https://linux-hardware.org/?probe=7ba347026e) | Jun 13, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [3f7e0702b6](https://linux-hardware.org/?probe=3f7e0702b6) | Jun 12, 2019 |
| Dell          | 088DT1 A01                  | [5ea359299f](https://linux-hardware.org/?probe=5ea359299f) | Jun 11, 2019 |
| ASUSTek       | X99-A/USB                   | [d1e49be03d](https://linux-hardware.org/?probe=d1e49be03d) | Jun 11, 2019 |
| Gigabyte      | P85-D3                      | [16a7890585](https://linux-hardware.org/?probe=16a7890585) | Jun 09, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [9f8322e22a](https://linux-hardware.org/?probe=9f8322e22a) | Jun 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [0c0c2eca20](https://linux-hardware.org/?probe=0c0c2eca20) | Jun 08, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [3608798d1a](https://linux-hardware.org/?probe=3608798d1a) | May 24, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [e50d4d260b](https://linux-hardware.org/?probe=e50d4d260b) | May 23, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [1cbc7d5be7](https://linux-hardware.org/?probe=1cbc7d5be7) | May 16, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [cb3502a316](https://linux-hardware.org/?probe=cb3502a316) | May 09, 2019 |
| MSI           | B350 TOMAHAWK               | [3db9496e05](https://linux-hardware.org/?probe=3db9496e05) | May 08, 2019 |
| MSI           | B450 TOMAHAWK               | [0f966d6a2d](https://linux-hardware.org/?probe=0f966d6a2d) | May 08, 2019 |
| ASUSTek       | CROSSHAIR VI HERO           | [7653740066](https://linux-hardware.org/?probe=7653740066) | May 04, 2019 |
| HP            | 0A58h                       | [ec6b93d879](https://linux-hardware.org/?probe=ec6b93d879) | May 02, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [ca0ce2b4fc](https://linux-hardware.org/?probe=ca0ce2b4fc) | Apr 26, 2019 |
| Gigabyte      | PA65-UD3-B3                 | [e08bb193b2](https://linux-hardware.org/?probe=e08bb193b2) | Apr 24, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [79831da7d2](https://linux-hardware.org/?probe=79831da7d2) | Apr 15, 2019 |
| Dell          | 04JGCK A02                  | [fd0e8a37d1](https://linux-hardware.org/?probe=fd0e8a37d1) | Apr 09, 2019 |
| ASRock        | 4Core1600Twins-P35          | [a5f4c15c85](https://linux-hardware.org/?probe=a5f4c15c85) | Apr 07, 2019 |
| ASUSTek       | P7P55D                      | [b25ec7e75a](https://linux-hardware.org/?probe=b25ec7e75a) | Mar 18, 2019 |
| Shuttle       | FN68S V10                   | [10121de278](https://linux-hardware.org/?probe=10121de278) | Mar 04, 2019 |
| Shuttle       | FN68S V10                   | [d15d7c5f21](https://linux-hardware.org/?probe=d15d7c5f21) | Mar 04, 2019 |
| ASRock        | 4Core1600Twins-P35          | [98b19f2fc7](https://linux-hardware.org/?probe=98b19f2fc7) | Feb 25, 2019 |
| ASRock        | Z77 Pro4                    | [08a0af469d](https://linux-hardware.org/?probe=08a0af469d) | Feb 20, 2019 |
| ASRock        | 4Core1600Twins-P35          | [e94ef5e02e](https://linux-hardware.org/?probe=e94ef5e02e) | Feb 16, 2019 |
| ASRock        | Z77 Pro4                    | [ba845b8712](https://linux-hardware.org/?probe=ba845b8712) | Feb 15, 2019 |
| ASRock        | Z77 Pro4                    | [e104fbc941](https://linux-hardware.org/?probe=e104fbc941) | Feb 14, 2019 |
| Acer          | FMCP7A-ION                  | [22a3849e3a](https://linux-hardware.org/?probe=22a3849e3a) | Dec 05, 2018 |
| Medion        | MS-7646                     | [cb720a4df0](https://linux-hardware.org/?probe=cb720a4df0) | Nov 25, 2018 |
| Medion        | MS-7713                     | [94a415c6c3](https://linux-hardware.org/?probe=94a415c6c3) | Nov 23, 2018 |
| Medion        | MS-7646                     | [7ff447b20e](https://linux-hardware.org/?probe=7ff447b20e) | Nov 22, 2018 |
| Lenovo        | 5025a26                     | [75a078fe71](https://linux-hardware.org/?probe=75a078fe71) | Nov 15, 2018 |
| ASUSTek       | PRIME Z370-P                | [89bfd874c0](https://linux-hardware.org/?probe=89bfd874c0) | Nov 03, 2018 |
| MSI           | B75MA-E31                   | [b1600ef31c](https://linux-hardware.org/?probe=b1600ef31c) | Nov 02, 2018 |
| ASUSTek       | H81M-P PLUS                 | [67c13bd391](https://linux-hardware.org/?probe=67c13bd391) | Oct 25, 2018 |
| Pegatron      | 2AB5                        | [85d0b75160](https://linux-hardware.org/?probe=85d0b75160) | Oct 24, 2018 |
| Pegatron      | 2AB5                        | [25cf879f80](https://linux-hardware.org/?probe=25cf879f80) | Oct 24, 2018 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f67b4afee6](https://linux-hardware.org/?probe=f67b4afee6) | Aug 11, 2018 |
| HP            | 82FE 11                     | [bd284d1c9d](https://linux-hardware.org/?probe=bd284d1c9d) | Dec 11, 2017 |
| ASUSTek       | P6T7 WS SUPERCOMPUTER       | [0f0a556912](https://linux-hardware.org/?probe=0f0a556912) | Jul 03, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Ubuntu 20.04         | 43       | 10.7%   |
| Ubuntu 18.04         | 30       | 7.46%   |
| Arch Rolling         | 19       | 4.73%   |
| Ubuntu 22.04         | 17       | 4.23%   |
| Zorin 16             | 15       | 3.73%   |
| OpenMandriva 4.2     | 13       | 3.23%   |
| Pop!_OS 22.04        | 11       | 2.74%   |
| Manjaro              | 9        | 2.24%   |
| Debian 11            | 9        | 2.24%   |
| Pop!_OS 21.04        | 7        | 1.74%   |
| OpenMandriva 4.3     | 7        | 1.74%   |
| Linux Mint 21.1      | 7        | 1.74%   |
| Linux Mint 20.2      | 7        | 1.74%   |
| Ubuntu 22.10         | 6        | 1.49%   |
| OpenMandriva 23.03   | 6        | 1.49%   |
| Linux Mint 21.2      | 6        | 1.49%   |
| Linux Mint 20.1      | 6        | 1.49%   |
| Fedora 38            | 6        | 1.49%   |
| ArcoLinux Rolling    | 6        | 1.49%   |
| Ubuntu 20.10         | 5        | 1.24%   |
| Ubuntu 19.04         | 5        | 1.24%   |
| Pop!_OS 20.10        | 5        | 1.24%   |
| Linux Mint 20.3      | 5        | 1.24%   |
| Debian 12            | 5        | 1.24%   |
| Zorin 15             | 4        | 1%      |
| Ubuntu 21.10         | 4        | 1%      |
| KDE neon 20.04       | 4        | 1%      |
| Ubuntu 19.10         | 3        | 0.75%   |
| Pop!_OS 21.10        | 3        | 0.75%   |
| OpenMandriva 23.08   | 3        | 0.75%   |
| Linux Mint 20        | 3        | 0.75%   |
| Linux Mint 19.1      | 3        | 0.75%   |
| Garuda Linux Soaring | 3        | 0.75%   |
| Fedora 36            | 3        | 0.75%   |
| Fedora 32            | 3        | 0.75%   |
| Debian 10            | 3        | 0.75%   |
| Ubuntu MATE 22.04    | 2        | 0.5%    |
| Ubuntu MATE 20.04    | 2        | 0.5%    |
| Ubuntu 16.04         | 2        | 0.5%    |
| Pop!_OS 20.04        | 2        | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 115      | 30.1%   |
| Linux Mint   | 38       | 9.95%   |
| OpenMandriva | 33       | 8.64%   |
| Pop!_OS      | 28       | 7.33%   |
| Fedora       | 23       | 6.02%   |
| Debian       | 22       | 5.76%   |
| Arch         | 21       | 5.5%    |
| Manjaro      | 20       | 5.24%   |
| Zorin        | 19       | 4.97%   |
| Kubuntu      | 9        | 2.36%   |
| ArcoLinux    | 8        | 2.09%   |
| KDE neon     | 6        | 1.57%   |
| Ubuntu MATE  | 5        | 1.31%   |
| Gentoo       | 4        | 1.05%   |
| EndeavourOS  | 4        | 1.05%   |
| ROSA         | 3        | 0.79%   |
| Nobara       | 3        | 0.79%   |
| Garuda Linux | 3        | 0.79%   |
| Xubuntu      | 2        | 0.52%   |
| openSUSE     | 2        | 0.52%   |
| NixOS        | 2        | 0.52%   |
| MX           | 2        | 0.52%   |
| Lubuntu      | 2        | 0.52%   |
| Ubuntu Kylin | 1        | 0.26%   |
| SteamOS      | 1        | 0.26%   |
| Solus        | 1        | 0.26%   |
| Parrot       | 1        | 0.26%   |
| Endless      | 1        | 0.26%   |
| Elementary   | 1        | 0.26%   |
| BlackPanther | 1        | 0.26%   |
| Anarchy      | 1        | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 11       | 2.53%   |
| 6.2.6-desktop-1omv2390   | 6        | 1.38%   |
| 5.4.0-52-generic         | 6        | 1.38%   |
| 5.16.7-desktop-1omv4003  | 6        | 1.38%   |
| 5.15.0-58-generic        | 5        | 1.15%   |
| 5.15.0-56-generic        | 5        | 1.15%   |
| 5.8.0-43-generic         | 4        | 0.92%   |
| 5.4.0-42-generic         | 4        | 0.92%   |
| 5.19.0-38-generic        | 4        | 0.92%   |
| 5.11.12-desktop-1omv4002 | 4        | 0.92%   |
| 4.15.0-48-generic        | 4        | 0.92%   |
| 6.2.6-76060206-generic   | 3        | 0.69%   |
| 5.8.5-arch1-1            | 3        | 0.69%   |
| 5.4.0-91-generic         | 3        | 0.69%   |
| 5.4.0-90-generic         | 3        | 0.69%   |
| 5.4.0-73-generic         | 3        | 0.69%   |
| 5.4.0-58-generic         | 3        | 0.69%   |
| 5.4.0-29-generic         | 3        | 0.69%   |
| 5.3.0-28-generic         | 3        | 0.69%   |
| 5.15.0-88-generic        | 3        | 0.69%   |
| 5.15.0-69-generic        | 3        | 0.69%   |
| 5.15.0-46-generic        | 3        | 0.69%   |
| 5.15.0-41-generic        | 3        | 0.69%   |
| 5.13.0-28-generic        | 3        | 0.69%   |
| 5.11.0-7620-generic      | 3        | 0.69%   |
| 5.11.0-41-generic        | 3        | 0.69%   |
| 5.11.0-37-generic        | 3        | 0.69%   |
| 5.11.0-27-generic        | 3        | 0.69%   |
| 5.10.0-20-amd64          | 3        | 0.69%   |
| 5.0.0-13-generic         | 3        | 0.69%   |
| 4.15.0-45-generic        | 3        | 0.69%   |
| 6.6.2-desktop-1omv2390   | 2        | 0.46%   |
| 6.4.4-200.fc38.x86_64    | 2        | 0.46%   |
| 6.4.11-desktop-1omv2390  | 2        | 0.46%   |
| 6.2.6-arch1-1            | 2        | 0.46%   |
| 6.2.0-76060200-generic   | 2        | 0.46%   |
| 6.1.9-arch1-1            | 2        | 0.46%   |
| 6.1.0-13-amd64           | 2        | 0.46%   |
| 5.8.0-7642-generic       | 2        | 0.46%   |
| 5.8.0-63-generic         | 2        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 53       | 12.77%  |
| 5.15.0  | 33       | 7.95%   |
| 4.15.0  | 29       | 6.99%   |
| 5.8.0   | 21       | 5.06%   |
| 5.13.0  | 19       | 4.58%   |
| 5.11.0  | 19       | 4.58%   |
| 5.19.0  | 17       | 4.1%    |
| 6.2.6   | 11       | 2.65%   |
| 5.3.0   | 11       | 2.65%   |
| 5.10.14 | 11       | 2.65%   |
| 5.10.0  | 10       | 2.41%   |
| 5.0.0   | 8        | 1.93%   |
| 6.2.0   | 7        | 1.69%   |
| 5.16.7  | 6        | 1.45%   |
| 6.1.0   | 5        | 1.2%    |
| 4.18.0  | 5        | 1.2%    |
| 5.11.12 | 4        | 0.96%   |
| 4.19.0  | 4        | 0.96%   |
| 6.5.5   | 3        | 0.72%   |
| 5.8.5   | 3        | 0.72%   |
| 5.6.15  | 3        | 0.72%   |
| 6.6.8   | 2        | 0.48%   |
| 6.6.2   | 2        | 0.48%   |
| 6.6.0   | 2        | 0.48%   |
| 6.5.3   | 2        | 0.48%   |
| 6.5.0   | 2        | 0.48%   |
| 6.4.8   | 2        | 0.48%   |
| 6.4.4   | 2        | 0.48%   |
| 6.4.11  | 2        | 0.48%   |
| 6.3.9   | 2        | 0.48%   |
| 6.3.5   | 2        | 0.48%   |
| 6.3.4   | 2        | 0.48%   |
| 6.2.8   | 2        | 0.48%   |
| 6.1.9   | 2        | 0.48%   |
| 6.1.12  | 2        | 0.48%   |
| 6.1.1   | 2        | 0.48%   |
| 5.9.1   | 2        | 0.48%   |
| 5.8.18  | 2        | 0.48%   |
| 5.6.12  | 2        | 0.48%   |
| 5.4.18  | 2        | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 57       | 14.04%  |
| 5.15    | 41       | 10.1%   |
| 5.8     | 30       | 7.39%   |
| 4.15    | 29       | 7.14%   |
| 5.11    | 27       | 6.65%   |
| 5.10    | 23       | 5.67%   |
| 5.13    | 22       | 5.42%   |
| 6.2     | 21       | 5.17%   |
| 5.19    | 20       | 4.93%   |
| 6.1     | 17       | 4.19%   |
| 5.16    | 13       | 3.2%    |
| 5.3     | 11       | 2.71%   |
| 6.5     | 10       | 2.46%   |
| 6.3     | 10       | 2.46%   |
| 6.4     | 9        | 2.22%   |
| 6.6     | 8        | 1.97%   |
| 5.0     | 8        | 1.97%   |
| 5.6     | 7        | 1.72%   |
| 6.0     | 6        | 1.48%   |
| 5.7     | 5        | 1.23%   |
| 4.19    | 5        | 1.23%   |
| 4.18    | 5        | 1.23%   |
| 5.17    | 4        | 0.99%   |
| 5.9     | 3        | 0.74%   |
| 5.14    | 3        | 0.74%   |
| 4.9     | 3        | 0.74%   |
| 5.18    | 2        | 0.49%   |
| 5.12    | 2        | 0.49%   |
| 5.1     | 2        | 0.49%   |
| 6.7     | 1        | 0.25%   |
| 5.2     | 1        | 0.25%   |
| 4.17    | 1        | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 360      | 98.9%   |
| i686   | 4        | 1.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 156      | 40.84%  |
| KDE5          | 77       | 20.16%  |
| Unknown       | 60       | 15.71%  |
| X-Cinnamon    | 28       | 7.33%   |
| XFCE          | 25       | 6.54%   |
| MATE          | 9        | 2.36%   |
| KDE           | 8        | 2.09%   |
| Cinnamon      | 4        | 1.05%   |
| LXQt          | 3        | 0.79%   |
| KDE4          | 2        | 0.52%   |
| i3            | 2        | 0.52%   |
| UKUI          | 1        | 0.26%   |
| Pantheon      | 1        | 0.26%   |
| openbox       | 1        | 0.26%   |
| LXDE          | 1        | 0.26%   |
| Hyprland      | 1        | 0.26%   |
| enlightenment | 1        | 0.26%   |
| Deepin        | 1        | 0.26%   |
| bspwm         | 1        | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 291      | 76.78%  |
| Wayland | 51       | 13.46%  |
| Unknown | 26       | 6.86%   |
| Tty     | 11       | 2.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 203      | 53.42%  |
| SDDM    | 71       | 18.68%  |
| GDM3    | 39       | 10.26%  |
| GDM     | 25       | 6.58%   |
| LightDM | 23       | 6.05%   |
| TDM     | 15       | 3.95%   |
| KDM     | 2        | 0.53%   |
| LXDM    | 1        | 0.26%   |
| GREETD  | 1        | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 134      | 35.64%  |
| da_DK      | 114      | 30.32%  |
| en_DK      | 52       | 13.83%  |
| Unknown    | 44       | 11.7%   |
| en_GB      | 14       | 3.72%   |
| C          | 5        | 1.33%   |
| ru_RU      | 2        | 0.53%   |
| pl_PL      | 2        | 0.53%   |
| de_DE      | 2        | 0.53%   |
| it_IT      | 1        | 0.27%   |
| io_001     | 1        | 0.27%   |
| es_ES      | 1        | 0.27%   |
| en_US.UTF8 | 1        | 0.27%   |
| en_IE      | 1        | 0.27%   |
| de_CH      | 1        | 0.27%   |
| de_AT      | 1        | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 205      | 54.67%  |
| EFI  | 170      | 45.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 281      | 73.56%  |
| Btrfs   | 42       | 10.99%  |
| Overlay | 31       | 8.12%   |
| Unknown | 13       | 3.4%    |
| Tmpfs   | 8        | 2.09%   |
| Zfs     | 4        | 1.05%   |
| Xfs     | 2        | 0.52%   |
| F2fs    | 1        | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 204      | 53.68%  |
| GPT     | 139      | 36.58%  |
| MBR     | 37       | 9.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 294      | 77.98%  |
| Yes       | 83       | 22.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 267      | 71.97%  |
| Yes       | 104      | 28.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 127      | 34.89%  |
| Gigabyte Technology | 49       | 13.46%  |
| MSI                 | 36       | 9.89%   |
| ASRock              | 34       | 9.34%   |
| Lenovo              | 33       | 9.07%   |
| Hewlett-Packard     | 24       | 6.59%   |
| Dell                | 12       | 3.3%    |
| Medion              | 11       | 3.02%   |
| Acer                | 10       | 2.75%   |
| Pegatron            | 4        | 1.1%    |
| Shuttle             | 3        | 0.82%   |
| Intel               | 3        | 0.82%   |
| Packard Bell        | 2        | 0.55%   |
| Fujitsu             | 2        | 0.55%   |
| BESSTAR Tech        | 2        | 0.55%   |
| T-bao               | 1        | 0.27%   |
| NEXCOM              | 1        | 0.27%   |
| Inventec            | 1        | 0.27%   |
| IceWhale Technology | 1        | 0.27%   |
| Fujitsu Siemens     | 1        | 0.27%   |
| eMachines           | 1        | 0.27%   |
| ECS                 | 1        | 0.27%   |
| AMI                 | 1        | 0.27%   |
| Alienware           | 1        | 0.27%   |
| ADLINK Technology   | 1        | 0.27%   |
| ABIT                | 1        | 0.27%   |
| Unknown             | 1        | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 6        | 1.65%   |
| ASUS ROG STRIX B450-E GAMING        | 5        | 1.37%   |
| ASUS Z170 PRO GAMING                | 4        | 1.1%    |
| ASUS TUF Gaming X570-PLUS           | 4        | 1.1%    |
| ASUS ROG STRIX B550-F GAMING        | 4        | 1.1%    |
| MSI MS-7C37                         | 3        | 0.82%   |
| MSI MS-7C02                         | 3        | 0.82%   |
| Gigabyte X570 AORUS MASTER          | 3        | 0.82%   |
| Dell OptiPlex 9020                  | 3        | 0.82%   |
| ASUS ROG STRIX X570-E GAMING        | 3        | 0.82%   |
| ASUS PRIME Z390-A                   | 3        | 0.82%   |
| MSI MS-7B79                         | 2        | 0.55%   |
| MSI MS-7A34                         | 2        | 0.55%   |
| MSI MS-7693                         | 2        | 0.55%   |
| Medion MS-7797                      | 2        | 0.55%   |
| Medion MS-7646                      | 2        | 0.55%   |
| Lenovo ThinkStation P500 30A6S14F00 | 2        | 0.55%   |
| Lenovo H30-05 90BJ00CNMT            | 2        | 0.55%   |
| HP Compaq 8200 Elite SFF PC         | 2        | 0.55%   |
| HP Compaq 6200 Pro SFF PC           | 2        | 0.55%   |
| Gigabyte P85-D3                     | 2        | 0.55%   |
| BESSTAR Tech HM90                   | 2        | 0.55%   |
| ASUS Z170-P                         | 2        | 0.55%   |
| ASUS TUF Gaming B550-PLUS           | 2        | 0.55%   |
| ASUS ROG STRIX X670E-E GAMING WIFI  | 2        | 0.55%   |
| ASUS ROG STRIX X470-I GAMING        | 2        | 0.55%   |
| ASUS ROG Maximus X HERO             | 2        | 0.55%   |
| ASUS PRIME Z690M-PLUS D4            | 2        | 0.55%   |
| ASUS PRIME Z370-P                   | 2        | 0.55%   |
| ASUS PRIME Z370-A                   | 2        | 0.55%   |
| ASUS PRIME X570-P                   | 2        | 0.55%   |
| ASUS PRIME B250M-A                  | 2        | 0.55%   |
| ASUS PRIME A320M-K                  | 2        | 0.55%   |
| ASUS M5A78L-M/USB3                  | 2        | 0.55%   |
| ASUS M5A78L-M LX V2                 | 2        | 0.55%   |
| ASUS CROSSHAIR VI HERO              | 2        | 0.55%   |
| ASRock B550M-ITX/ac                 | 2        | 0.55%   |
| ASRock B450M-HDV R4.0               | 2        | 0.55%   |
| ASRock B450 Gaming K4               | 2        | 0.55%   |
| T-bao MINI PC                       | 1        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS ROG            | 31       | 8.52%   |
| ASUS PRIME          | 30       | 8.24%   |
| Lenovo ThinkCentre  | 14       | 3.85%   |
| ASUS TUF            | 14       | 3.85%   |
| HP Compaq           | 10       | 2.75%   |
| Gigabyte X570       | 8        | 2.2%    |
| Lenovo ThinkStation | 7        | 1.92%   |
| Acer Aspire         | 7        | 1.92%   |
| Dell OptiPlex       | 6        | 1.65%   |
| ASUS All            | 6        | 1.65%   |
| Lenovo IdeaCentre   | 5        | 1.37%   |
| ASUS Z170           | 4        | 1.1%    |
| ASUS SABERTOOTH     | 4        | 1.1%    |
| ASUS M5A78L-M       | 4        | 1.1%    |
| MSI MS-7C37         | 3        | 0.82%   |
| MSI MS-7C02         | 3        | 0.82%   |
| HP ProLiant         | 3        | 0.82%   |
| HP EliteDesk        | 3        | 0.82%   |
| Gigabyte B550       | 3        | 0.82%   |
| ASRock Z170         | 3        | 0.82%   |
| ASRock B450         | 3        | 0.82%   |
| MSI MS-7B79         | 2        | 0.55%   |
| MSI MS-7A34         | 2        | 0.55%   |
| MSI MS-7693         | 2        | 0.55%   |
| Medion MS-7797      | 2        | 0.55%   |
| Medion MS-7646      | 2        | 0.55%   |
| Lenovo H30-05       | 2        | 0.55%   |
| HP Pavilion         | 2        | 0.55%   |
| Gigabyte Z390       | 2        | 0.55%   |
| Gigabyte P85-D3     | 2        | 0.55%   |
| Gigabyte B650       | 2        | 0.55%   |
| Gigabyte A320M-S2H  | 2        | 0.55%   |
| Fujitsu ESPRIMO     | 2        | 0.55%   |
| Dell Precision      | 2        | 0.55%   |
| BESSTAR Tech HM90   | 2        | 0.55%   |
| ASUS Z170-P         | 2        | 0.55%   |
| ASUS Maximus        | 2        | 0.55%   |
| ASUS CROSSHAIR      | 2        | 0.55%   |
| ASRock Z77          | 2        | 0.55%   |
| ASRock B550M-ITX    | 2        | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 41       | 11.26%  |
| 2019 | 39       | 10.71%  |
| 2020 | 35       | 9.62%   |
| 2012 | 31       | 8.52%   |
| 2021 | 26       | 7.14%   |
| 2017 | 25       | 6.87%   |
| 2013 | 22       | 6.04%   |
| 2011 | 22       | 6.04%   |
| 2016 | 21       | 5.77%   |
| 2015 | 21       | 5.77%   |
| 2022 | 16       | 4.4%    |
| 2014 | 16       | 4.4%    |
| 2010 | 15       | 4.12%   |
| 2008 | 13       | 3.57%   |
| 2009 | 11       | 3.02%   |
| 2007 | 6        | 1.65%   |
| 2023 | 2        | 0.55%   |
| 2006 | 2        | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 364      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 357      | 97.81%  |
| Enabled  | 8        | 2.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 364      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 118      | 31.55%  |
| 32.01-64.0      | 82       | 21.93%  |
| 8.01-16.0       | 59       | 15.78%  |
| 3.01-4.0        | 35       | 9.36%   |
| 4.01-8.0        | 34       | 9.09%   |
| 64.01-256.0     | 28       | 7.49%   |
| 24.01-32.0      | 11       | 2.94%   |
| 1.01-2.0        | 4        | 1.07%   |
| 2.01-3.0        | 2        | 0.53%   |
| More than 256.0 | 1        | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 130      | 31.71%  |
| 2.01-3.0    | 99       | 24.15%  |
| 4.01-8.0    | 75       | 18.29%  |
| 3.01-4.0    | 59       | 14.39%  |
| 8.01-16.0   | 21       | 5.12%   |
| 0.51-1.0    | 12       | 2.93%   |
| 24.01-32.0  | 4        | 0.98%   |
| 0.01-0.5    | 4        | 0.98%   |
| 16.01-24.0  | 3        | 0.73%   |
| 32.01-64.0  | 2        | 0.49%   |
| 64.01-256.0 | 1        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 136      | 35.79%  |
| 2      | 90       | 23.68%  |
| 3      | 76       | 20%     |
| 4      | 37       | 9.74%   |
| 5      | 23       | 6.05%   |
| 6      | 7        | 1.84%   |
| 0      | 4        | 1.05%   |
| 8      | 3        | 0.79%   |
| 7      | 3        | 0.79%   |
| 9      | 1        | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 219      | 59.67%  |
| Yes       | 148      | 40.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 361      | 99.18%  |
| No        | 3        | 0.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 195      | 52.7%   |
| Yes       | 175      | 47.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 236      | 64.13%  |
| Yes       | 132      | 35.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Denmark | 364      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Copenhagen               | 88       | 23.28%  |
| Frederiksberg            | 20       | 5.29%   |
| Odense                   | 16       | 4.23%   |
| Aarhus                   | 14       | 3.7%    |
| Slagelse                 | 10       | 2.65%   |
| Horsens                  | 9        | 2.38%   |
| Silkeborg                | 7        | 1.85%   |
| Esbjerg                  | 7        | 1.85%   |
| Bronshoj                 | 7        | 1.85%   |
| Valby                    | 6        | 1.59%   |
| Aalborg                  | 6        | 1.59%   |
| Aabenraa                 | 6        | 1.59%   |
| Hjørring                | 5        | 1.32%   |
| Vejle                    | 4        | 1.06%   |
| Roskilde                 | 4        | 1.06%   |
| Herlev                   | 4        | 1.06%   |
| Glostrup Municipality    | 4        | 1.06%   |
| Allinge                  | 4        | 1.06%   |
| Albertslund Municipality | 4        | 1.06%   |
| Trige                    | 3        | 0.79%   |
| Tilst                    | 3        | 0.79%   |
| Taastrup                 | 3        | 0.79%   |
| Svendborg                | 3        | 0.79%   |
| Rødovre Municipality    | 3        | 0.79%   |
| Pandrup                  | 3        | 0.79%   |
| Nyborg                   | 3        | 0.79%   |
| Ishøj                   | 3        | 0.79%   |
| Hvidovre                 | 3        | 0.79%   |
| Gentofte Municipality    | 3        | 0.79%   |
| Fredericia               | 3        | 0.79%   |
| Aabybro                  | 3        | 0.79%   |
| Viby J                   | 2        | 0.53%   |
| Tranbjerg                | 2        | 0.53%   |
| Stovring                 | 2        | 0.53%   |
| Soborg                   | 2        | 0.53%   |
| Skanderborg              | 2        | 0.53%   |
| Risskov                  | 2        | 0.53%   |
| Ringsted                 | 2        | 0.53%   |
| Odder                    | 2        | 0.53%   |
| Norresundby              | 2        | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 145      | 268    | 20.86%  |
| Seagate                     | 118      | 180    | 16.98%  |
| WDC                         | 103      | 167    | 14.82%  |
| Kingston                    | 69       | 106    | 9.93%   |
| Crucial                     | 29       | 39     | 4.17%   |
| SanDisk                     | 28       | 38     | 4.03%   |
| Toshiba                     | 27       | 37     | 3.88%   |
| Intel                       | 20       | 24     | 2.88%   |
| Hitachi                     | 17       | 25     | 2.45%   |
| Intenso                     | 11       | 14     | 1.58%   |
| Phison Electronics          | 10       | 16     | 1.44%   |
| Unknown                     | 9        | 14     | 1.29%   |
| Corsair                     | 9        | 12     | 1.29%   |
| Phison                      | 7        | 10     | 1.01%   |
| A-DATA Technology           | 7        | 7      | 1.01%   |
| PNY                         | 5        | 6      | 0.72%   |
| HGST                        | 5        | 8      | 0.72%   |
| SK hynix                    | 4        | 4      | 0.58%   |
| OCZ                         | 4        | 4      | 0.58%   |
| Micron/Crucial Technology   | 4        | 4      | 0.58%   |
| Kingston Technology Company | 4        | 4      | 0.58%   |
| Verbatim                    | 3        | 6      | 0.43%   |
| Micron Technology           | 3        | 4      | 0.43%   |
| LITEON                      | 3        | 3      | 0.43%   |
| JMicron Technology          | 3        | 3      | 0.43%   |
| Fujitsu                     | 3        | 7      | 0.43%   |
| Unknown                     | 3        | 5      | 0.43%   |
| XPG                         | 2        | 2      | 0.29%   |
| Transcend                   | 2        | 2      | 0.29%   |
| Team                        | 2        | 2      | 0.29%   |
| Realtek Semiconductor       | 2        | 3      | 0.29%   |
| Patriot                     | 2        | 3      | 0.29%   |
| Maxtor                      | 2        | 2      | 0.29%   |
| Leven                       | 2        | 2      | 0.29%   |
| HUAWEI                      | 2        | 2      | 0.29%   |
| Apple                       | 2        | 5      | 0.29%   |
| AFOX                        | 2        | 2      | 0.29%   |
| USB                         | 1        | 1      | 0.14%   |
| Unknown (CF)                | 1        | 1      | 0.14%   |
| Supersonic                  | 1        | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 12       | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 11       | 1.33%   |
| Seagate ST2000DM001-1ER164 2TB                     | 9        | 1.09%   |
| Samsung SSD 860 QVO 1TB                            | 9        | 1.09%   |
| Kingston SV300S37A120G 120GB SSD                   | 9        | 1.09%   |
| Kingston SA400S37480G 480GB SSD                    | 9        | 1.09%   |
| Samsung SSD 860 EVO 1TB                            | 8        | 0.97%   |
| Samsung SSD 850 EVO 250GB                          | 8        | 0.97%   |
| Samsung NVMe SSD Drive 500GB                       | 8        | 0.97%   |
| Kingston SA400S37240G 240GB SSD                    | 8        | 0.97%   |
| Samsung SSD 860 EVO 500GB                          | 7        | 0.84%   |
| Samsung SSD 850 EVO 500GB                          | 7        | 0.84%   |
| Samsung SSD 840 EVO 250GB                          | 7        | 0.84%   |
| Samsung NVMe SSD Drive 1TB                         | 7        | 0.84%   |
| Seagate ST500DM002-1BD142 500GB                    | 6        | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB                     | 6        | 0.72%   |
| Phison E12 NVMe Controller 1TB                     | 6        | 0.72%   |
| Seagate ST1000DM003-1SB102 1TB                     | 5        | 0.6%    |
| Phison E16 PCIe4 NVMe Controller 2TB               | 5        | 0.6%    |
| Kingston SA400S37120G 120GB SSD                    | 5        | 0.6%    |
| Crucial CT1000MX500SSD1 1TB                        | 5        | 0.6%    |
| Unknown SD/MMC/MS PRO 256GB                        | 4        | 0.48%   |
| Unknown Compact Flash 977MB                        | 4        | 0.48%   |
| Seagate ST4000VN008-2DR166 4TB                     | 4        | 0.48%   |
| Seagate ST2000DM001-1CH164 2TB                     | 4        | 0.48%   |
| Seagate ST1000DM003-1SB10C 1TB                     | 4        | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB                     | 4        | 0.48%   |
| Samsung SSD 970 EVO 1TB                            | 4        | 0.48%   |
| Samsung SSD 850 EVO 120GB                          | 4        | 0.48%   |
| Samsung HD103SJ 1TB                                | 4        | 0.48%   |
| Kingston SV300S37A240G 240GB SSD                   | 4        | 0.48%   |
| Kingston SUV400S37120G 120GB SSD                   | 4        | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 3        | 0.36%   |
| WDC WD20EARX-00PASB0 2TB                           | 3        | 0.36%   |
| WDC WD1003FZEX-00K3CA0 1TB                         | 3        | 0.36%   |
| Toshiba MQ01ABD100 1TB                             | 3        | 0.36%   |
| Toshiba DT01ACA200 2TB                             | 3        | 0.36%   |
| Toshiba DT01ACA050 500GB                           | 3        | 0.36%   |
| Seagate ST3250310AS 250GB                          | 3        | 0.36%   |
| Seagate ST3000DM008-2DM166 3TB                     | 3        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 114      | 173    | 41.01%  |
| WDC                 | 85       | 148    | 30.58%  |
| Toshiba             | 24       | 34     | 8.63%   |
| Hitachi             | 17       | 25     | 6.12%   |
| Samsung Electronics | 13       | 20     | 4.68%   |
| HGST                | 5        | 8      | 1.8%    |
| Unknown             | 4        | 5      | 1.44%   |
| JMicron Technology  | 3        | 3      | 1.08%   |
| Fujitsu             | 3        | 7      | 1.08%   |
| Maxtor              | 2        | 2      | 0.72%   |
| Apple               | 2        | 5      | 0.72%   |
| Unknown             | 2        | 4      | 0.72%   |
| Unknown (CF)        | 1        | 1      | 0.36%   |
| Intenso             | 1        | 2      | 0.36%   |
| Hewlett-Packard     | 1        | 3      | 0.36%   |
| ASMT109x            | 1        | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 87       | 148    | 33.59%  |
| Kingston            | 55       | 76     | 21.24%  |
| Crucial             | 24       | 34     | 9.27%   |
| SanDisk             | 12       | 12     | 4.63%   |
| WDC                 | 10       | 10     | 3.86%   |
| Intel               | 9        | 11     | 3.47%   |
| Intenso             | 8        | 8      | 3.09%   |
| A-DATA Technology   | 6        | 6      | 2.32%   |
| PNY                 | 5        | 6      | 1.93%   |
| OCZ                 | 4        | 4      | 1.54%   |
| Corsair             | 4        | 5      | 1.54%   |
| Verbatim            | 3        | 6      | 1.16%   |
| Micron Technology   | 3        | 4      | 1.16%   |
| LITEON              | 3        | 3      | 1.16%   |
| Transcend           | 2        | 2      | 0.77%   |
| Team                | 2        | 2      | 0.77%   |
| Patriot             | 2        | 3      | 0.77%   |
| Leven               | 2        | 2      | 0.77%   |
| AFOX                | 2        | 2      | 0.77%   |
| USB                 | 1        | 1      | 0.39%   |
| Toshiba             | 1        | 1      | 0.39%   |
| Supersonic          | 1        | 1      | 0.39%   |
| SK hynix            | 1        | 1      | 0.39%   |
| Shark               | 1        | 1      | 0.39%   |
| Ramaxel Technology  | 1        | 1      | 0.39%   |
| OCZ-VERTEX3         | 1        | 3      | 0.39%   |
| LITEONIT            | 1        | 1      | 0.39%   |
| KingDian            | 1        | 1      | 0.39%   |
| INDMEM              | 1        | 1      | 0.39%   |
| GOODRAM             | 1        | 5      | 0.39%   |
| FORESEE             | 1        | 1      | 0.39%   |
| China               | 1        | 1      | 0.39%   |
| ADATA SU            | 1        | 1      | 0.39%   |
| 2-Power             | 1        | 2      | 0.39%   |
| Unknown             | 1        | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 211      | 367    | 36.44%  |
| HDD     | 208      | 441    | 35.92%  |
| NVMe    | 144      | 245    | 24.87%  |
| Unknown | 12       | 13     | 2.07%   |
| MMC     | 4        | 4      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 305      | 775    | 62.63%  |
| NVMe | 144      | 244    | 29.57%  |
| SAS  | 34       | 47     | 6.98%   |
| MMC  | 4        | 4      | 0.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 222      | 403    | 47.74%  |
| 0.51-1.0   | 122      | 192    | 26.24%  |
| 1.01-2.0   | 57       | 98     | 12.26%  |
| 2.01-3.0   | 22       | 36     | 4.73%   |
| 4.01-10.0  | 20       | 44     | 4.3%    |
| 3.01-4.0   | 15       | 22     | 3.23%   |
| 10.01-20.0 | 7        | 13     | 1.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 69       | 17.65%  |
| 251-500        | 65       | 16.62%  |
| 101-250        | 64       | 16.37%  |
| 1001-2000      | 51       | 13.04%  |
| More than 3000 | 48       | 12.28%  |
| 1-20           | 28       | 7.16%   |
| 2001-3000      | 26       | 6.65%   |
| Unknown        | 17       | 4.35%   |
| 21-50          | 13       | 3.32%   |
| 51-100         | 10       | 2.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 122      | 30.89%  |
| 21-50          | 59       | 14.94%  |
| 101-250        | 49       | 12.41%  |
| 501-1000       | 40       | 10.13%  |
| 251-500        | 34       | 8.61%   |
| 51-100         | 31       | 7.85%   |
| 1001-2000      | 20       | 5.06%   |
| Unknown        | 17       | 4.3%    |
| More than 3000 | 16       | 4.05%   |
| 2001-3000      | 7        | 1.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD      | 3        | 5      | 7.32%   |
| Kingston SHPM2280P2H 480G SSD         | 2        | 2      | 4.88%   |
| WDC WD5000AAKX-001CA0 500GB           | 1        | 1      | 2.44%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1      | 2.44%   |
| WDC WD10EZRX-00A8LB0 1TB              | 1        | 1      | 2.44%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1        | 1      | 2.44%   |
| WDC WD10EURX-73FH1Y0 1TB              | 1        | 1      | 2.44%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 1      | 2.44%   |
| Toshiba MQ01ABD100 1TB                | 1        | 1      | 2.44%   |
| Toshiba DT01ACA050 500GB              | 1        | 1      | 2.44%   |
| Seagate ST380013AS 80GB               | 1        | 1      | 2.44%   |
| Seagate ST3400633AS 400GB             | 1        | 1      | 2.44%   |
| Seagate ST3250318AS 250GB             | 1        | 1      | 2.44%   |
| Seagate ST320LT020-9YG142 320GB       | 1        | 1      | 2.44%   |
| Seagate ST3200822AS 200GB             | 1        | 1      | 2.44%   |
| Seagate ST31500341AS 1TB              | 1        | 1      | 2.44%   |
| Seagate ST31000524AS 1TB              | 1        | 1      | 2.44%   |
| Seagate ST2000DX002-2DV164 2TB        | 1        | 1      | 2.44%   |
| Seagate ST2000DM008-2FR102 2TB        | 1        | 1      | 2.44%   |
| Seagate ST2000DL003-9VT166 2TB        | 1        | 1      | 2.44%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 1      | 2.44%   |
| SanDisk SDSSDX240GG25 240GB           | 1        | 1      | 2.44%   |
| Samsung Electronics SSD 750 EVO 250GB | 1        | 1      | 2.44%   |
| Samsung Electronics SP0812C 80GB      | 1        | 1      | 2.44%   |
| Samsung Electronics HD753LJ 752GB     | 1        | 1      | 2.44%   |
| Samsung Electronics HD103SJ 1TB       | 1        | 1      | 2.44%   |
| OCZ AGILITY3 240GB SSD                | 1        | 1      | 2.44%   |
| Leven JAJS300M480C 480GB              | 1        | 1      | 2.44%   |
| Kingston SA400S37480G 480GB SSD       | 1        | 1      | 2.44%   |
| Kingston SA400S37240G 240GB SSD       | 1        | 1      | 2.44%   |
| Kingston SA400S37120G 120GB SSD       | 1        | 1      | 2.44%   |
| Intel SSDSC2BW480H6 480GB             | 1        | 1      | 2.44%   |
| Intel SSDPEKKF256G7L 256GB            | 1        | 1      | 2.44%   |
| Hitachi HDT721025SLA380 250GB         | 1        | 1      | 2.44%   |
| Hitachi HDS721616PLA380 160GB         | 1        | 1      | 2.44%   |
| Hitachi HDP725032GLA360 320GB         | 1        | 2      | 2.44%   |
| Crucial CT275MX300SSD1 275GB          | 1        | 1      | 2.44%   |
| Unknown                               | 1        | 2      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 11     | 25%     |
| Kingston            | 8        | 10     | 22.22%  |
| WDC                 | 5        | 6      | 13.89%  |
| Samsung Electronics | 3        | 4      | 8.33%   |
| Toshiba             | 2        | 2      | 5.56%   |
| Intel               | 2        | 2      | 5.56%   |
| Hitachi             | 2        | 4      | 5.56%   |
| SanDisk             | 1        | 1      | 2.78%   |
| OCZ                 | 1        | 1      | 2.78%   |
| Leven               | 1        | 1      | 2.78%   |
| Crucial             | 1        | 1      | 2.78%   |
| Unknown             | 1        | 2      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 11     | 42.86%  |
| WDC                 | 5        | 6      | 23.81%  |
| Toshiba             | 2        | 2      | 9.52%   |
| Samsung Electronics | 2        | 3      | 9.52%   |
| Hitachi             | 2        | 4      | 9.52%   |
| Unknown             | 1        | 2      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 28     | 54.84%  |
| SSD  | 13       | 16     | 41.94%  |
| NVMe | 1        | 1      | 3.23%   |

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
| Detected | 242      | 643    | 57.48%  |
| Works    | 148      | 382    | 35.15%  |
| Malfunc  | 31       | 45     | 7.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 224      | 38.36%  |
| AMD                          | 133      | 22.77%  |
| Samsung Electronics          | 68       | 11.64%  |
| Kingston Technology Company  | 26       | 4.45%   |
| ASMedia Technology           | 25       | 4.28%   |
| SanDisk                      | 22       | 3.77%   |
| Phison Electronics           | 21       | 3.6%    |
| JMicron Technology           | 13       | 2.23%   |
| Marvell Technology Group     | 11       | 1.88%   |
| Nvidia                       | 9        | 1.54%   |
| Micron/Crucial Technology    | 9        | 1.54%   |
| Seagate Technology           | 5        | 0.86%   |
| ADATA Technology             | 4        | 0.68%   |
| SK hynix                     | 3        | 0.51%   |
| VIA Technologies             | 2        | 0.34%   |
| Toshiba America Info Systems | 2        | 0.34%   |
| Realtek Semiconductor        | 2        | 0.34%   |
| Silicon Motion               | 1        | 0.17%   |
| KIOXIA                       | 1        | 0.17%   |
| HighPoint Technologies       | 1        | 0.17%   |
| Hewlett-Packard              | 1        | 0.17%   |
| Broadcom / LSI               | 1        | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 87       | 12.22%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 41       | 5.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 29       | 4.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25       | 3.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 24       | 3.37%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 23       | 3.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 22       | 3.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19       | 2.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 18       | 2.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16       | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15       | 2.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 14       | 1.97%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 12       | 1.69%   |
| Phison E12 NVMe Controller                                                              | 11       | 1.54%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 1.54%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 10       | 1.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9        | 1.26%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 9        | 1.26%   |
| AMD 600 Series Chipset SATA Controller                                                  | 9        | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.12%   |
| AMD 300 Series Chipset SATA Controller                                                  | 8        | 1.12%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 7        | 0.98%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7        | 0.98%   |
| Intel SSD 660P Series                                                                   | 7        | 0.98%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.98%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 6        | 0.84%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 0.84%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 0.84%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                      | 5        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 0.7%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.7%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 0.7%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4        | 0.56%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 323      | 57.58%  |
| NVMe | 146      | 26.02%  |
| IDE  | 66       | 11.76%  |
| RAID | 25       | 4.46%   |
| SAS  | 1        | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 225      | 61.81%  |
| AMD    | 139      | 38.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 11       | 3.01%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 10       | 2.73%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 8        | 2.19%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 8        | 2.19%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 8        | 2.19%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 6        | 1.64%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 5        | 1.37%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 5        | 1.37%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 5        | 1.37%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 4        | 1.09%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 4        | 1.09%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 4        | 1.09%   |
| Intel Core i5-3350P CPU @ 3.10GHz      | 4        | 1.09%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 4        | 1.09%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 4        | 1.09%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 4        | 1.09%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 4        | 1.09%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 4        | 1.09%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 4        | 1.09%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 0.82%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 3        | 0.82%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 3        | 0.82%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 3        | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 3        | 0.82%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 3        | 0.82%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 3        | 0.82%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 3        | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 3        | 0.82%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 0.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 3        | 0.82%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz   | 3        | 0.82%   |
| Intel 12th Gen Core i9-12900K          | 3        | 0.82%   |
| Intel 12th Gen Core i7-12700K          | 3        | 0.82%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 3        | 0.82%   |
| AMD Ryzen 7 5800X3D 8-Core Processor   | 3        | 0.82%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 0.82%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 3        | 0.82%   |
| AMD Ryzen 3 1200 Quad-Core Processor   | 3        | 0.82%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz    | 2        | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 68       | 18.63%  |
| Intel Core i7           | 62       | 16.99%  |
| AMD Ryzen 7             | 36       | 9.86%   |
| AMD Ryzen 5             | 32       | 8.77%   |
| AMD Ryzen 9             | 24       | 6.58%   |
| Other                   | 19       | 5.21%   |
| Intel Core i3           | 16       | 4.38%   |
| Intel Xeon              | 15       | 4.11%   |
| Intel Core 2 Duo        | 11       | 3.01%   |
| AMD FX                  | 10       | 2.74%   |
| Intel Core i9           | 7        | 1.92%   |
| Intel Celeron           | 7        | 1.92%   |
| AMD Ryzen 3             | 6        | 1.64%   |
| Intel Core 2 Quad       | 5        | 1.37%   |
| Intel Pentium           | 4        | 1.1%    |
| AMD Ryzen Threadripper  | 4        | 1.1%    |
| AMD Phenom II X4        | 4        | 1.1%    |
| AMD Athlon 64 X2        | 4        | 1.1%    |
| AMD A8                  | 4        | 1.1%    |
| AMD A6                  | 4        | 1.1%    |
| Intel Atom              | 3        | 0.82%   |
| AMD Athlon II X4        | 3        | 0.82%   |
| AMD A10                 | 3        | 0.82%   |
| Intel Pentium Dual-Core | 2        | 0.55%   |
| Intel Core 2            | 2        | 0.55%   |
| AMD A4                  | 2        | 0.55%   |
| Intel Pentium Silver    | 1        | 0.27%   |
| Intel Pentium Dual      | 1        | 0.27%   |
| Intel Core m5           | 1        | 0.27%   |
| Intel Core 2 Extreme    | 1        | 0.27%   |
| AMD Phenom II X2        | 1        | 0.27%   |
| AMD GX                  | 1        | 0.27%   |
| AMD E                   | 1        | 0.27%   |
| AMD Athlon II Neo       | 1        | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 140      | 38.25%  |
| 6      | 66       | 18.03%  |
| 2      | 62       | 16.94%  |
| 8      | 50       | 13.66%  |
| 12     | 20       | 5.46%   |
| 16     | 15       | 4.1%    |
| 10     | 4        | 1.09%   |
| 1      | 3        | 0.82%   |
| 24     | 2        | 0.55%   |
| 64     | 1        | 0.27%   |
| 32     | 1        | 0.27%   |
| 14     | 1        | 0.27%   |
| 3      | 1        | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 362      | 99.45%  |
| 2      | 2        | 0.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 234      | 64.29%  |
| 1      | 130      | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 360      | 98.09%  |
| Unknown        | 7        | 1.91%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 109      | 28.61%  |
| 0x306c3    | 23       | 6.04%   |
| 0x306a9    | 17       | 4.46%   |
| 0x506e3    | 16       | 4.2%    |
| 0x206a7    | 16       | 4.2%    |
| 0x08701021 | 12       | 3.15%   |
| 0x0800820d | 11       | 2.89%   |
| 0x906ea    | 9        | 2.36%   |
| 0x08001138 | 9        | 2.36%   |
| 0x906e9    | 8        | 2.1%    |
| 0x90672    | 8        | 2.1%    |
| 0x1067a    | 8        | 2.1%    |
| 0x0a601203 | 7        | 1.84%   |
| 0x08701013 | 7        | 1.84%   |
| 0x0a201009 | 6        | 1.57%   |
| 0x906ed    | 5        | 1.31%   |
| 0x6fd      | 5        | 1.31%   |
| 0x06000852 | 5        | 1.31%   |
| 0x010000c8 | 5        | 1.31%   |
| 0xa0655    | 4        | 1.05%   |
| 0xa0653    | 4        | 1.05%   |
| 0x906ec    | 4        | 1.05%   |
| 0x08600106 | 4        | 1.05%   |
| 0xa0671    | 3        | 0.79%   |
| 0x106e5    | 3        | 0.79%   |
| 0x10676    | 3        | 0.79%   |
| 0x0a201205 | 3        | 0.79%   |
| 0x0a201016 | 3        | 0.79%   |
| 0x08701030 | 3        | 0.79%   |
| 0x08001129 | 3        | 0.79%   |
| 0x06001119 | 3        | 0.79%   |
| 0x6f6      | 2        | 0.52%   |
| 0x506c9    | 2        | 0.52%   |
| 0x206c2    | 2        | 0.52%   |
| 0x0a50000c | 2        | 0.52%   |
| 0x08108109 | 2        | 0.52%   |
| 0x08001137 | 2        | 0.52%   |
| 0x06003106 | 2        | 0.52%   |
| 0x0600063e | 2        | 0.52%   |
| 0x010000db | 2        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 44       | 12.02%  |
| Zen 2            | 38       | 10.38%  |
| Haswell          | 36       | 9.84%   |
| Skylake          | 26       | 7.1%    |
| Zen 3            | 24       | 6.56%   |
| SandyBridge      | 24       | 6.56%   |
| IvyBridge        | 23       | 6.28%   |
| Penryn           | 16       | 4.37%   |
| Unknown          | 16       | 4.37%   |
| Zen+             | 15       | 4.1%    |
| Zen              | 15       | 4.1%    |
| Piledriver       | 11       | 3.01%   |
| Alderlake Hybrid | 11       | 3.01%   |
| K10              | 9        | 2.46%   |
| CometLake        | 9        | 2.46%   |
| Core             | 8        | 2.19%   |
| Nehalem          | 6        | 1.64%   |
| Westmere         | 4        | 1.09%   |
| K8 Hammer        | 4        | 1.09%   |
| Icelake          | 4        | 1.09%   |
| Steamroller      | 3        | 0.82%   |
| Puma             | 3        | 0.82%   |
| Bulldozer        | 3        | 0.82%   |
| Broadwell        | 3        | 0.82%   |
| Jaguar           | 2        | 0.55%   |
| Goldmont         | 2        | 0.55%   |
| Bonnell          | 2        | 0.55%   |
| Silvermont       | 1        | 0.27%   |
| K10 Llano        | 1        | 0.27%   |
| Goldmont plus    | 1        | 0.27%   |
| Excavator        | 1        | 0.27%   |
| Bobcat           | 1        | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 195      | 49.24%  |
| AMD                        | 110      | 27.78%  |
| Intel                      | 89       | 22.47%  |
| Matrox Electronics Systems | 1        | 0.25%   |
| ASPEED Technology          | 1        | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 16       | 3.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 3.46%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 3.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 10       | 2.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 2.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 2.22%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 8        | 1.98%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 8        | 1.98%   |
| Intel HD Graphics 630                                                       | 8        | 1.98%   |
| Intel HD Graphics 530                                                       | 8        | 1.98%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 7        | 1.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 1.73%   |
| AMD Raphael                                                                 | 7        | 1.73%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 6        | 1.48%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.48%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 1.48%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 1.23%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 1.23%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.23%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.99%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 0.99%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 0.99%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4        | 0.99%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 0.99%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 0.99%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 4        | 0.99%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 0.99%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.99%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 0.99%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 4        | 0.99%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 4        | 0.99%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 0.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 0.99%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 0.99%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 3        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 3        | 0.74%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.74%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 3        | 0.74%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 180      | 49.05%  |
| 1 x AMD         | 93       | 25.34%  |
| 1 x Intel       | 67       | 18.26%  |
| Intel + Nvidia  | 7        | 1.91%   |
| 2 x AMD         | 6        | 1.63%   |
| AMD + Nvidia    | 5        | 1.36%   |
| Intel + AMD     | 4        | 1.09%   |
| 2 x Nvidia      | 2        | 0.54%   |
| 2 x Intel       | 1        | 0.27%   |
| Nvidia + ASPEED | 1        | 0.27%   |
| 1 x Matrox      | 1        | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 240      | 63.83%  |
| Proprietary | 124      | 32.98%  |
| Unknown     | 12       | 3.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 143      | 37.93%  |
| 1.01-2.0   | 63       | 16.71%  |
| 7.01-8.0   | 56       | 14.85%  |
| 3.01-4.0   | 24       | 6.37%   |
| 0.01-0.5   | 24       | 6.37%   |
| 5.01-6.0   | 23       | 6.1%    |
| 8.01-16.0  | 18       | 4.77%   |
| 0.51-1.0   | 16       | 4.24%   |
| 2.01-3.0   | 5        | 1.33%   |
| 16.01-24.0 | 4        | 1.06%   |
| 4.01-5.0   | 1        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 87       | 21.38%  |
| Dell                 | 40       | 9.83%   |
| Ancor Communications | 28       | 6.88%   |
| AOC                  | 27       | 6.63%   |
| Hewlett-Packard      | 26       | 6.39%   |
| Philips              | 25       | 6.14%   |
| Acer                 | 24       | 5.9%    |
| BenQ                 | 21       | 5.16%   |
| Lenovo               | 20       | 4.91%   |
| ASUSTek Computer     | 19       | 4.67%   |
| Goldstar             | 16       | 3.93%   |
| Sony                 | 9        | 2.21%   |
| Unknown              | 6        | 1.47%   |
| Medion               | 6        | 1.47%   |
| Lenovo Group Limited | 5        | 1.23%   |
| LG Electronics       | 4        | 0.98%   |
| IBM                  | 3        | 0.74%   |
| Gigabyte Technology  | 3        | 0.74%   |
| Fujitsu Siemens      | 3        | 0.74%   |
| ViewSonic            | 2        | 0.49%   |
| Vestel Elektronik    | 2        | 0.49%   |
| Tech Concepts        | 2        | 0.49%   |
| MSI                  | 2        | 0.49%   |
| Idek Iiyama          | 2        | 0.49%   |
| AUS                  | 2        | 0.49%   |
| Unknown              | 2        | 0.49%   |
| Wacom                | 1        | 0.25%   |
| Vestel               | 1        | 0.25%   |
| Valve                | 1        | 0.25%   |
| TopView              | 1        | 0.25%   |
| Pixio                | 1        | 0.25%   |
| Pioneer              | 1        | 0.25%   |
| Panasonic            | 1        | 0.25%   |
| Packard Bell         | 1        | 0.25%   |
| OTC                  | 1        | 0.25%   |
| OEM                  | 1        | 0.25%   |
| Mi                   | 1        | 0.25%   |
| Iiyama               | 1        | 0.25%   |
| IFS                  | 1        | 0.25%   |
| HCT                  | 1        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6        | 1.32%   |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                     | 4        | 0.88%   |
| Sony TV SNYEE01 1920x1080                                             | 3        | 0.66%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3        | 0.66%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                     | 3        | 0.66%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 3        | 0.66%   |
| BenQ EX3501R BNQ7F5E 3440x1440 819x346mm 35.0-inch                    | 3        | 0.66%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3        | 0.66%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3        | 0.66%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 3        | 0.66%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch      | 3        | 0.66%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 2        | 0.44%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                      | 2        | 0.44%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 2        | 0.44%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch  | 2        | 0.44%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 2        | 0.44%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 520x290mm 23.4-inch     | 2        | 0.44%   |
| Samsung Electronics LCD Monitor LF27T35 1920x1080                     | 2        | 0.44%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch    | 2        | 0.44%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch    | 2        | 0.44%   |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch              | 2        | 0.44%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 2        | 0.44%   |
| Philips PHL 272B8Q PHL0918 2560x1440 600x340mm 27.2-inch              | 2        | 0.44%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2        | 0.44%   |
| Medion MD20444 MED3661 1920x1080 521x293mm 23.5-inch                  | 2        | 0.44%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 2        | 0.44%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch              | 2        | 0.44%   |
| Lenovo G27q-20 LEN66C3 2560x1440 597x336mm 27.0-inch                  | 2        | 0.44%   |
| Lenovo C27-35 LEN66BA 1920x1080 597x336mm 27.0-inch                   | 2        | 0.44%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 2        | 0.44%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 509x286mm 23.0-inch          | 2        | 0.44%   |
| Goldstar 27GL850 GSM5B80 1920x1080 700x390mm 31.5-inch                | 2        | 0.44%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch       | 2        | 0.44%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                     | 2        | 0.44%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                     | 2        | 0.44%   |
| Dell P1913 DELA089 1440x900 408x255mm 18.9-inch                       | 2        | 0.44%   |
| Dell 2407WFP DELA017 1920x1200 519x324mm 24.1-inch                    | 2        | 0.44%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 2        | 0.44%   |
| BenQ G2420HDB BNQ7842 1920x1080 477x268mm 21.5-inch                   | 2        | 0.44%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 2        | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 175      | 43.86%  |
| 2560x1440 (QHD)    | 50       | 12.53%  |
| 3840x2160 (4K)     | 45       | 11.28%  |
| 1680x1050 (WSXGA+) | 20       | 5.01%   |
| 1280x1024 (SXGA)   | 18       | 4.51%   |
| Unknown            | 18       | 4.51%   |
| 3440x1440          | 13       | 3.26%   |
| 1920x1200 (WUXGA)  | 9        | 2.26%   |
| 1600x900 (HD+)     | 8        | 2.01%   |
| 3840x1080          | 7        | 1.75%   |
| 1440x900 (WXGA+)   | 7        | 1.75%   |
| 1360x768           | 4        | 1%      |
| 3840x1200          | 3        | 0.75%   |
| 2560x1080          | 2        | 0.5%    |
| 1920x540           | 2        | 0.5%    |
| 9840x3840          | 1        | 0.25%   |
| 6400x2160          | 1        | 0.25%   |
| 5760x1440          | 1        | 0.25%   |
| 5760x1080          | 1        | 0.25%   |
| 5120x1440          | 1        | 0.25%   |
| 4608x1440          | 1        | 0.25%   |
| 4480x1440          | 1        | 0.25%   |
| 3840x1600          | 1        | 0.25%   |
| 3280x1080          | 1        | 0.25%   |
| 3200x1200          | 1        | 0.25%   |
| 3200x1080          | 1        | 0.25%   |
| 2560x1600          | 1        | 0.25%   |
| 2560x1024          | 1        | 0.25%   |
| 2288x1287          | 1        | 0.25%   |
| 2048x1152          | 1        | 0.25%   |
| 1600x1200          | 1        | 0.25%   |
| 1366x768 (WXGA)    | 1        | 0.25%   |
| 1360x765           | 1        | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 82       | 20.4%   |
| 24      | 66       | 16.42%  |
| Unknown | 51       | 12.69%  |
| 23      | 45       | 11.19%  |
| 31      | 30       | 7.46%   |
| 21      | 21       | 5.22%   |
| 19      | 18       | 4.48%   |
| 22      | 15       | 3.73%   |
| 20      | 13       | 3.23%   |
| 34      | 11       | 2.74%   |
| 72      | 8        | 1.99%   |
| 84      | 6        | 1.49%   |
| 32      | 4        | 1%      |
| 17      | 4        | 1%      |
| 40      | 3        | 0.75%   |
| 35      | 3        | 0.75%   |
| 15      | 3        | 0.75%   |
| 48      | 2        | 0.5%    |
| 38      | 2        | 0.5%    |
| 28      | 2        | 0.5%    |
| 25      | 2        | 0.5%    |
| 65      | 1        | 0.25%   |
| 60      | 1        | 0.25%   |
| 54      | 1        | 0.25%   |
| 43      | 1        | 0.25%   |
| 42      | 1        | 0.25%   |
| 39      | 1        | 0.25%   |
| 33      | 1        | 0.25%   |
| 30      | 1        | 0.25%   |
| 29      | 1        | 0.25%   |
| 26      | 1        | 0.25%   |
| 18      | 1        | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 170      | 44.16%  |
| 401-500     | 56       | 14.55%  |
| Unknown     | 51       | 13.25%  |
| 601-700     | 43       | 11.17%  |
| 701-800     | 16       | 4.16%   |
| 1501-2000   | 14       | 3.64%   |
| 351-400     | 12       | 3.12%   |
| 801-900     | 9        | 2.34%   |
| 301-350     | 7        | 1.82%   |
| 1001-1500   | 6        | 1.56%   |
| 901-1000    | 1        | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 240      | 65.22%  |
| Unknown | 45       | 12.23%  |
| 16/10   | 44       | 11.96%  |
| 5/4     | 16       | 4.35%   |
| 21/9    | 16       | 4.35%   |
| 32/9    | 3        | 0.82%   |
| 4/3     | 2        | 0.54%   |
| 3/2     | 1        | 0.27%   |
| 3.20    | 1        | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 118      | 29.65%  |
| 301-350        | 82       | 20.6%   |
| 351-500        | 52       | 13.07%  |
| Unknown        | 51       | 12.81%  |
| 151-200        | 35       | 8.79%   |
| 251-300        | 26       | 6.53%   |
| More than 1000 | 17       | 4.27%   |
| 501-1000       | 10       | 2.51%   |
| 141-150        | 4        | 1.01%   |
| 101-110        | 2        | 0.5%    |
| 111-120        | 1        | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 225      | 60.98%  |
| 101-120 | 64       | 17.34%  |
| Unknown | 51       | 13.82%  |
| 121-160 | 15       | 4.07%   |
| 1-50    | 9        | 2.44%   |
| 161-240 | 5        | 1.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 260      | 70.08%  |
| 2     | 79       | 21.29%  |
| 0     | 20       | 5.39%   |
| 3     | 12       | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 214      | 40.23%  |
| Intel                           | 177      | 33.27%  |
| Qualcomm Atheros                | 20       | 3.76%   |
| Broadcom                        | 18       | 3.38%   |
| MediaTek                        | 10       | 1.88%   |
| Ralink Technology               | 9        | 1.69%   |
| Ralink                          | 9        | 1.69%   |
| Nvidia                          | 9        | 1.69%   |
| TP-Link                         | 7        | 1.32%   |
| Aquantia                        | 7        | 1.32%   |
| ASUSTek Computer                | 6        | 1.13%   |
| Microsoft                       | 5        | 0.94%   |
| Qualcomm Atheros Communications | 4        | 0.75%   |
| IMC Networks                    | 4        | 0.75%   |
| Huawei Technologies             | 4        | 0.75%   |
| OnePlus Technology (Shenzhen)   | 3        | 0.56%   |
| NetGear                         | 3        | 0.56%   |
| Edimax Technology               | 3        | 0.56%   |
| D-Link                          | 3        | 0.56%   |
| Samsung Electronics             | 2        | 0.38%   |
| D-Link System                   | 2        | 0.38%   |
| ASIX Electronics                | 2        | 0.38%   |
| Unknown                         | 1        | 0.19%   |
| Texas Instruments               | 1        | 0.19%   |
| Solarflare Communications       | 1        | 0.19%   |
| ROCCAT                          | 1        | 0.19%   |
| Motorola PCS                    | 1        | 0.19%   |
| Linksys                         | 1        | 0.19%   |
| Lenovo                          | 1        | 0.19%   |
| JMicron Technology              | 1        | 0.19%   |
| InterBiometrics                 | 1        | 0.19%   |
| ICS Advent                      | 1        | 0.19%   |
| HMD Global                      | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 166      | 27.21%  |
| Intel I211 Gigabit Network Connection                                          | 31       | 5.08%   |
| Realtek RTL8125 2.5GbE Controller                                              | 29       | 4.75%   |
| Intel Ethernet Connection (2) I219-V                                           | 23       | 3.77%   |
| Intel Wi-Fi 6 AX200                                                            | 20       | 3.28%   |
| Intel Ethernet Controller I225-V                                               | 15       | 2.46%   |
| Intel Ethernet Connection I217-LM                                              | 12       | 1.97%   |
| Intel Ethernet Connection (7) I219-V                                           | 12       | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12       | 1.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 9        | 1.48%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 9        | 1.48%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 8        | 1.31%   |
| Intel 82579V Gigabit Network Connection                                        | 7        | 1.15%   |
| Realtek 802.11ac NIC                                                           | 5        | 0.82%   |
| Ralink RT5370 Wireless Adapter                                                 | 5        | 0.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 5        | 0.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 5        | 0.82%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 5        | 0.82%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 5        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 4        | 0.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4        | 0.66%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 0.66%   |
| Intel Ethernet Connection (2) I218-V                                           | 4        | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 4        | 0.66%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 4        | 0.66%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                           | 4        | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 3        | 0.49%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                | 3        | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 3        | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3        | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 0.49%   |
| Ralink MT7601U Wireless Adapter                                                | 3        | 0.49%   |
| OnePlus (Shenzhen) Android                                                     | 3        | 0.49%   |
| Nvidia MCP73 Ethernet                                                          | 3        | 0.49%   |
| Microsoft Xbox Wireless Adapter for Windows                                    | 3        | 0.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 3        | 0.49%   |
| Intel Wireless 8260                                                            | 3        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 63       | 33.69%  |
| Realtek Semiconductor           | 33       | 17.65%  |
| Broadcom                        | 14       | 7.49%   |
| Qualcomm Atheros                | 12       | 6.42%   |
| Ralink Technology               | 9        | 4.81%   |
| Ralink                          | 9        | 4.81%   |
| MediaTek                        | 9        | 4.81%   |
| TP-Link                         | 7        | 3.74%   |
| ASUSTek Computer                | 6        | 3.21%   |
| Microsoft                       | 5        | 2.67%   |
| Qualcomm Atheros Communications | 4        | 2.14%   |
| IMC Networks                    | 4        | 2.14%   |
| NetGear                         | 3        | 1.6%    |
| Edimax Technology               | 3        | 1.6%    |
| D-Link                          | 3        | 1.6%    |
| D-Link System                   | 2        | 1.07%   |
| Linksys                         | 1        | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 20       | 10.47%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 9        | 4.71%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                         | 9        | 4.71%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                              | 8        | 4.19%   |
| Realtek 802.11ac NIC                                                                 | 5        | 2.62%   |
| Ralink RT5370 Wireless Adapter                                                       | 5        | 2.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 5        | 2.62%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 5        | 2.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 4        | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 4        | 2.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 2.09%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 4        | 2.09%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                 | 4        | 2.09%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 3        | 1.57%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 1.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 1.57%   |
| Ralink MT7601U Wireless Adapter                                                      | 3        | 1.57%   |
| Microsoft Xbox Wireless Adapter for Windows                                          | 3        | 1.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 3        | 1.57%   |
| Intel Wireless 8260                                                                  | 3        | 1.57%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                         | 3        | 1.57%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 2        | 1.05%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 2        | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 1.05%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 2        | 1.05%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                            | 2        | 1.05%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 2        | 1.05%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 2        | 1.05%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                          | 2        | 1.05%   |
| Microsoft Xbox 360 Wireless Adapter                                                  | 2        | 1.05%   |
| Intel Wireless 8265 / 8275                                                           | 2        | 1.05%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                    | 2        | 1.05%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 2        | 1.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 1        | 0.52%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 201      | 50.63%  |
| Intel                         | 150      | 37.78%  |
| Qualcomm Atheros              | 10       | 2.52%   |
| Nvidia                        | 9        | 2.27%   |
| Aquantia                      | 7        | 1.76%   |
| Broadcom                      | 4        | 1.01%   |
| OnePlus Technology (Shenzhen) | 3        | 0.76%   |
| Samsung Electronics           | 2        | 0.5%    |
| Huawei Technologies           | 2        | 0.5%    |
| ASIX Electronics              | 2        | 0.5%    |
| Solarflare Communications     | 1        | 0.25%   |
| Motorola PCS                  | 1        | 0.25%   |
| MediaTek                      | 1        | 0.25%   |
| Lenovo                        | 1        | 0.25%   |
| JMicron Technology            | 1        | 0.25%   |
| ICS Advent                    | 1        | 0.25%   |
| HMD Global                    | 1        | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 166      | 40.19%  |
| Intel I211 Gigabit Network Connection                                          | 31       | 7.51%   |
| Realtek RTL8125 2.5GbE Controller                                              | 29       | 7.02%   |
| Intel Ethernet Connection (2) I219-V                                           | 23       | 5.57%   |
| Intel Ethernet Controller I225-V                                               | 15       | 3.63%   |
| Intel Ethernet Connection I217-LM                                              | 12       | 2.91%   |
| Intel Ethernet Connection (7) I219-V                                           | 12       | 2.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12       | 2.91%   |
| Intel 82579V Gigabit Network Connection                                        | 7        | 1.69%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 5        | 1.21%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 5        | 1.21%   |
| Intel I210 Gigabit Network Connection                                          | 4        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                                           | 4        | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3        | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3        | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3        | 0.73%   |
| OnePlus (Shenzhen) Android                                                     | 3        | 0.73%   |
| Nvidia MCP73 Ethernet                                                          | 3        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3        | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3        | 0.73%   |
| Intel Ethernet Connection (2) I218-LM                                          | 3        | 0.73%   |
| Intel Ethernet Connection (17) I219-V                                          | 3        | 0.73%   |
| Intel Ethernet Connection (11) I219-V                                          | 3        | 0.73%   |
| Intel 82574L Gigabit Network Connection                                        | 3        | 0.73%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2        | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2        | 0.48%   |
| Nvidia MCP61 Ethernet                                                          | 2        | 0.48%   |
| Intel Ethernet Connection I217-V                                               | 2        | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2        | 0.48%   |
| Intel 82576 Gigabit Network Connection                                         | 2        | 0.48%   |
| Huawei STG-LX1                                                                 | 2        | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2        | 0.48%   |
| Solarflare SFC9020 10G Ethernet Controller                                     | 1        | 0.24%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1        | 0.24%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1        | 0.24%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1        | 0.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 361      | 66.61%  |
| WiFi     | 175      | 32.29%  |
| Modem    | 4        | 0.74%   |
| Unknown  | 2        | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 294      | 77.17%  |
| WiFi     | 87       | 22.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 209      | 56.95%  |
| 2     | 128      | 34.88%  |
| 3     | 22       | 5.99%   |
| 0     | 4        | 1.09%   |
| 5     | 2        | 0.54%   |
| 4     | 2        | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 342      | 93.44%  |
| Yes  | 24       | 6.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 61       | 44.53%  |
| Cambridge Silicon Radio         | 33       | 24.09%  |
| ASUSTek Computer                | 9        | 6.57%   |
| MediaTek                        | 7        | 5.11%   |
| IMC Networks                    | 7        | 5.11%   |
| Realtek Semiconductor           | 5        | 3.65%   |
| Qualcomm Atheros Communications | 5        | 3.65%   |
| Broadcom                        | 5        | 3.65%   |
| Belkin Components               | 2        | 1.46%   |
| Integrated System Solution      | 1        | 0.73%   |
| HTC (High Tech Computer)        | 1        | 0.73%   |
| Edimax Technology               | 1        | 0.73%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 33       | 24.09%  |
| Intel AX200 Bluetooth                                                | 16       | 11.68%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 9        | 6.57%   |
| Intel Bluetooth wireless interface                                   | 9        | 6.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 8        | 5.84%   |
| MediaTek Wireless_Device                                             | 7        | 5.11%   |
| Intel AX210 Bluetooth                                                | 6        | 4.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 5        | 3.65%   |
| ASUS ASUS USB-BT500                                                  | 5        | 3.65%   |
| Intel AX201 Bluetooth                                                | 4        | 2.92%   |
| IMC Networks Bluetooth Radio                                         | 4        | 2.92%   |
| Realtek Bluetooth Radio                                              | 3        | 2.19%   |
| Intel Bluetooth Device                                               | 3        | 2.19%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3        | 2.19%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2        | 1.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2        | 1.46%   |
| IMC Networks Bluetooth Device                                        | 2        | 1.46%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 2        | 1.46%   |
| ASUS Bluetooth Radio                                                 | 2        | 1.46%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 0.73%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.73%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.73%   |
| IMC Networks Wireless_Device                                         | 1        | 0.73%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.73%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 0.73%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 0.73%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 0.73%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.73%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.73%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 207      | 29.53%  |
| Nvidia                               | 192      | 27.39%  |
| AMD                                  | 164      | 23.4%   |
| SteelSeries ApS                      | 16       | 2.28%   |
| Kingston Technology                  | 15       | 2.14%   |
| C-Media Electronics                  | 14       | 2%      |
| ASUSTek Computer                     | 11       | 1.57%   |
| Logitech                             | 10       | 1.43%   |
| Creative Technology                  | 9        | 1.28%   |
| Creative Labs                        | 9        | 1.28%   |
| GN Netcom                            | 5        | 0.71%   |
| XMOS                                 | 3        | 0.43%   |
| RODE Microphones                     | 3        | 0.43%   |
| Realtek Semiconductor                | 3        | 0.43%   |
| Yamaha                               | 2        | 0.29%   |
| VIA Technologies                     | 2        | 0.29%   |
| Texas Instruments                    | 2        | 0.29%   |
| Razer USA                            | 2        | 0.29%   |
| JMTek                                | 2        | 0.29%   |
| Focusrite-Novation                   | 2        | 0.29%   |
| Corsair                              | 2        | 0.29%   |
| BEHRINGER International              | 2        | 0.29%   |
| Valve Software                       | 1        | 0.14%   |
| Turtle Beach                         | 1        | 0.14%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.14%   |
| Tenx Technology                      | 1        | 0.14%   |
| Syntek                               | 1        | 0.14%   |
| Sony                                 | 1        | 0.14%   |
| Shure                                | 1        | 0.14%   |
| Setek Elektronik                     | 1        | 0.14%   |
| Samsung Electronics                  | 1        | 0.14%   |
| ROCCAT                               | 1        | 0.14%   |
| Musical Fidelity                     | 1        | 0.14%   |
| Hewlett-Packard                      | 1        | 0.14%   |
| GYROCOM C&C                          | 1        | 0.14%   |
| Ensoniq                              | 1        | 0.14%   |
| DSEA A/S                             | 1        | 0.14%   |
| Dell                                 | 1        | 0.14%   |
| Clavia DMI AB                        | 1        | 0.14%   |
| BR23                                 | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 49       | 6.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 26       | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 25       | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 25       | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 22       | 2.75%   |
| Intel 200 Series PCH HD Audio                                                                   | 22       | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 21       | 2.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 19       | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 19       | 2.38%   |
| AMD Navi 10 HDMI Audio                                                                          | 18       | 2.25%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 17       | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 17       | 2.13%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 16       | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 16       | 2%      |
| Intel Cannon Lake PCH cAVS                                                                      | 15       | 1.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 15       | 1.88%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 13       | 1.63%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 12       | 1.5%    |
| Intel Alder Lake-S HD Audio Controller                                                          | 12       | 1.5%    |
| AMD FCH Azalia Controller                                                                       | 12       | 1.5%    |
| Nvidia TU104 HD Audio Controller                                                                | 11       | 1.38%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 11       | 1.38%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 11       | 1.38%   |
| Kingston Technology HyperX 7.1 Audio                                                            | 11       | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 10       | 1.25%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 10       | 1.25%   |
| ASUSTek Computer USB Audio                                                                      | 9        | 1.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 8        | 1%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 8        | 1%      |
| Nvidia GM204 High Definition Audio Controller                                                   | 7        | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 7        | 0.88%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 7        | 0.88%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 6        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 6        | 0.75%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 6        | 0.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 6        | 0.75%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 6        | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 6        | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                                        | 6        | 0.75%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 6        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 49       | 22.58%  |
| Kingston            | 38       | 17.51%  |
| G.Skill             | 33       | 15.21%  |
| Samsung Electronics | 24       | 11.06%  |
| Unknown             | 20       | 9.22%   |
| Crucial             | 14       | 6.45%   |
| Micron Technology   | 12       | 5.53%   |
| SK hynix            | 11       | 5.07%   |
| Ramaxel Technology  | 4        | 1.84%   |
| Nanya Technology    | 4        | 1.84%   |
| Elpida              | 2        | 0.92%   |
| Unknown             | 2        | 0.92%   |
| Unknown (ABCD)      | 1        | 0.46%   |
| Unifosa             | 1        | 0.46%   |
| Patriot             | 1        | 0.46%   |
| GOODRAM             | 1        | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 9        | 3.95%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s | 4        | 1.75%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s  | 4        | 1.75%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 3        | 1.32%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 3        | 1.32%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 3        | 1.32%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 2        | 0.88%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 2        | 0.88%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 2        | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s  | 2        | 0.88%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s    | 2        | 0.88%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s    | 2        | 0.88%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s    | 2        | 0.88%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s    | 2        | 0.88%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 2        | 0.88%   |
| Kingston RAM KF556C36-16 16GB DIMM DDR5 6400MT/s       | 2        | 0.88%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s       | 2        | 0.88%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 0.88%   |
| Kingston RAM HP24D4U7S8MBP-8 8GB DIMM DDR4 2400MT/s    | 2        | 0.88%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 2        | 0.88%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 2        | 0.88%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 2        | 0.88%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s  | 2        | 0.88%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s    | 2        | 0.88%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s  | 2        | 0.88%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3066MT/s   | 2        | 0.88%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s | 2        | 0.88%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s | 2        | 0.88%   |
| Unknown                                                | 2        | 0.88%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s              | 1        | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s               | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.44%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                   | 1        | 0.44%   |
| Unknown RAM Module 4096MB DIMM                         | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s              | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 0.44%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 1        | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s            | 1        | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 110      | 56.41%  |
| DDR3    | 49       | 25.13%  |
| DDR5    | 12       | 6.15%   |
| Unknown | 10       | 5.13%   |
| SDRAM   | 8        | 4.1%    |
| DDR2    | 2        | 1.03%   |
| DDR     | 2        | 1.03%   |
| LPDDR4  | 1        | 0.51%   |
| LPDDR3  | 1        | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 178      | 92.71%  |
| SODIMM | 14       | 7.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 86       | 41.55%  |
| 16384 | 49       | 23.67%  |
| 4096  | 35       | 16.91%  |
| 2048  | 22       | 10.63%  |
| 32768 | 11       | 5.31%   |
| 1024  | 3        | 1.45%   |
| 512   | 1        | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 31       | 14.83%  |
| 3200    | 22       | 10.53%  |
| 3600    | 21       | 10.05%  |
| 1333    | 17       | 8.13%   |
| 2400    | 15       | 7.18%   |
| 3800    | 8        | 3.83%   |
| 2667    | 7        | 3.35%   |
| 3400    | 5        | 2.39%   |
| 2133    | 5        | 2.39%   |
| 1800    | 5        | 2.39%   |
| 3733    | 4        | 1.91%   |
| 3666    | 4        | 1.91%   |
| 3533    | 4        | 1.91%   |
| 6400    | 3        | 1.44%   |
| 5200    | 3        | 1.44%   |
| 4800    | 3        | 1.44%   |
| 3534    | 3        | 1.44%   |
| 3000    | 3        | 1.44%   |
| 2933    | 3        | 1.44%   |
| 2666    | 3        | 1.44%   |
| 1867    | 3        | 1.44%   |
| 667     | 3        | 1.44%   |
| 6000    | 2        | 0.96%   |
| 3866    | 2        | 0.96%   |
| 3500    | 2        | 0.96%   |
| 3466    | 2        | 0.96%   |
| 3066    | 2        | 0.96%   |
| 2800    | 2        | 0.96%   |
| 2048    | 2        | 0.96%   |
| 1639    | 2        | 0.96%   |
| Unknown | 2        | 0.96%   |
| 20306   | 1        | 0.48%   |
| 5600    | 1        | 0.48%   |
| 4400    | 1        | 0.48%   |
| 4000    | 1        | 0.48%   |
| 3333    | 1        | 0.48%   |
| 3266    | 1        | 0.48%   |
| 3100    | 1        | 0.48%   |
| 2733    | 1        | 0.48%   |
| 2448    | 1        | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 46.67%  |
| Brother Industries  | 5        | 33.33%  |
| Xerox               | 1        | 6.67%   |
| Prolific Technology | 1        | 6.67%   |
| Canon               | 1        | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother DCP-J140W             | 2        | 13.33%  |
| Xerox Phaser 6125N            | 1        | 6.67%   |
| Prolific PL2305 Parallel Port | 1        | 6.67%   |
| HP LaserJet 1020              | 1        | 6.67%   |
| HP ENVY Photo 6200 series     | 1        | 6.67%   |
| HP ENVY 4520 series           | 1        | 6.67%   |
| HP Deskjet D4300 series       | 1        | 6.67%   |
| HP DeskJet 5940               | 1        | 6.67%   |
| HP DeskJet 5550               | 1        | 6.67%   |
| HP DeskJet 2600 series        | 1        | 6.67%   |
| Canon iP7200 series           | 1        | 6.67%   |
| Brother HL-5250DN Printer     | 1        | 6.67%   |
| Brother HL-2240D series       | 1        | 6.67%   |
| Brother HL-2030 Laser Printer | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| HP ScanJet 5470c/5490c | 1        | 50%     |
| HP PSC 1200            | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 25       | 50%     |
| Microsoft                              | 5        | 10%     |
| Creative Technology                    | 3        | 6%      |
| Trust                                  | 2        | 4%      |
| Sunplus Innovation Technology          | 2        | 4%      |
| Samsung Electronics                    | 2        | 4%      |
| Chicony Electronics                    | 2        | 4%      |
| Valve Software                         | 1        | 2%      |
| Quanta                                 | 1        | 2%      |
| Oculus VR                              | 1        | 2%      |
| Microdia                               | 1        | 2%      |
| Intel                                  | 1        | 2%      |
| Hewlett-Packard                        | 1        | 2%      |
| GenesysLogic Technology                | 1        | 2%      |
| Cubeternet                             | 1        | 2%      |
| Cheng Uei Precision Industry (Foxlink) | 1        | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech StreamCam                                                   | 4        | 8%      |
| Microsoft LifeCam Cinema                                             | 3        | 6%      |
| Logitech HD Webcam C525                                              | 3        | 6%      |
| Logitech HD Pro Webcam C920                                          | 3        | 6%      |
| Trust USB Camera                                                     | 2        | 4%      |
| Samsung Galaxy series, misc. (MTP mode)                              | 2        | 4%      |
| Logitech Webcam Pro 9000                                             | 2        | 4%      |
| Logitech Webcam C270                                                 | 2        | 4%      |
| Logitech C930c                                                       | 2        | 4%      |
| Logitech C922 Pro Stream Webcam                                      | 2        | 4%      |
| Valve Software 3D Camera                                             | 1        | 2%      |
| Sunplus SunplusIT PC Camera                                          | 1        | 2%      |
| Sunplus Sandberg USB Webcam Pro                                      | 1        | 2%      |
| Quanta FREETALK Conference                                           | 1        | 2%      |
| Oculus VR Quest 2                                                    | 1        | 2%      |
| Microsoft MicrosoftÂ LifeCam Studio                                 | 1        | 2%      |
| Microsoft LifeCam HD-3000                                            | 1        | 2%      |
| Microdia USB 2.0 Camera                                              | 1        | 2%      |
| Logitech Webcam C930e                                                | 1        | 2%      |
| Logitech Webcam C925e                                                | 1        | 2%      |
| Logitech QuickCam Pro 5000                                           | 1        | 2%      |
| Logitech QuickCam E 3500                                             | 1        | 2%      |
| Logitech HD Webcam C510                                              | 1        | 2%      |
| Logitech C670i FHD Webcam                                            | 1        | 2%      |
| Logitech BRIO Ultra HD Webcam                                        | 1        | 2%      |
| Intel RealSense SR300                                                | 1        | 2%      |
| HP HD-4110 Webcam                                                    | 1        | 2%      |
| GenesysLogic USB2.0 UVC PC Camera                                    | 1        | 2%      |
| Cubeternet USB2.0 Camera                                             | 1        | 2%      |
| Creative VF0610 Live! Cam Socialize HD                               | 1        | 2%      |
| Creative Live! Cam Sync [VF0520]                                     | 1        | 2%      |
| Creative Live! Cam Sync 1080p                                        | 1        | 2%      |
| Chicony USB2.0 HD UVC WebCam                                         | 1        | 2%      |
| Chicony Gateway Webcam                                               | 1        | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 2%      |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Advanced Card Systems ACR1252 Dual Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 308      | 83.02%  |
| 1     | 48       | 12.94%  |
| 2     | 10       | 2.7%    |
| 3     | 3        | 0.81%   |
| 6     | 1        | 0.27%   |
| 4     | 1        | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 20       | 26.32%  |
| Graphics card            | 20       | 26.32%  |
| Unassigned class         | 7        | 9.21%   |
| Sound                    | 7        | 9.21%   |
| Communication controller | 7        | 9.21%   |
| Multimedia controller    | 6        | 7.89%   |
| Storage/raid             | 2        | 2.63%   |
| Net/ethernet             | 2        | 2.63%   |
| Card reader              | 2        | 2.63%   |
| Network                  | 1        | 1.32%   |
| Chipcard                 | 1        | 1.32%   |
| Camera                   | 1        | 1.32%   |

