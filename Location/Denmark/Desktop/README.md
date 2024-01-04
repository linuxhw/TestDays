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

Total: 550

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 43       | 10.97%  |
| Ubuntu 18.04                 | 30       | 7.65%   |
| Arch Rolling                 | 19       | 4.85%   |
| Zorin 16                     | 15       | 3.83%   |
| Ubuntu 22.04                 | 15       | 3.83%   |
| OpenMandriva 4.2             | 13       | 3.32%   |
| Pop!_OS 22.04                | 11       | 2.81%   |
| Manjaro                      | 9        | 2.3%    |
| Debian 11                    | 9        | 2.3%    |
| Pop!_OS 21.04                | 7        | 1.79%   |
| OpenMandriva 4.3             | 7        | 1.79%   |
| Linux Mint 21.1              | 7        | 1.79%   |
| Linux Mint 20.2              | 7        | 1.79%   |
| Ubuntu 22.10                 | 6        | 1.53%   |
| OpenMandriva 23.03           | 6        | 1.53%   |
| Fedora 38                    | 6        | 1.53%   |
| ArcoLinux Rolling            | 6        | 1.53%   |
| Ubuntu 20.10                 | 5        | 1.28%   |
| Ubuntu 19.04                 | 5        | 1.28%   |
| Pop!_OS 20.10                | 5        | 1.28%   |
| Linux Mint 21.2              | 5        | 1.28%   |
| Linux Mint 20.3              | 5        | 1.28%   |
| Linux Mint 20.1              | 5        | 1.28%   |
| Debian 12                    | 5        | 1.28%   |
| Zorin 15                     | 4        | 1.02%   |
| Ubuntu 21.10                 | 4        | 1.02%   |
| KDE neon 20.04               | 4        | 1.02%   |
| Ubuntu 19.10                 | 3        | 0.77%   |
| Pop!_OS 21.10                | 3        | 0.77%   |
| OpenMandriva 23.08           | 3        | 0.77%   |
| Linux Mint 20                | 3        | 0.77%   |
| Garuda Linux Soaring         | 3        | 0.77%   |
| Fedora 36                    | 3        | 0.77%   |
| Fedora 32                    | 3        | 0.77%   |
| Debian 10                    | 3        | 0.77%   |
| Ubuntu MATE 22.04            | 2        | 0.51%   |
| Ubuntu MATE 20.04            | 2        | 0.51%   |
| Ubuntu 16.04                 | 2        | 0.51%   |
| Pop!_OS 20.04                | 2        | 0.51%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 113      | 30.38%  |
| Linux Mint   | 35       | 9.41%   |
| OpenMandriva | 32       | 8.6%    |
| Pop!_OS      | 28       | 7.53%   |
| Fedora       | 23       | 6.18%   |
| Debian       | 21       | 5.65%   |
| Arch         | 21       | 5.65%   |
| Manjaro      | 20       | 5.38%   |
| Zorin        | 19       | 5.11%   |
| Kubuntu      | 9        | 2.42%   |
| ArcoLinux    | 8        | 2.15%   |
| KDE neon     | 6        | 1.61%   |
| Ubuntu MATE  | 5        | 1.34%   |
| Gentoo       | 4        | 1.08%   |
| ROSA         | 3        | 0.81%   |
| Garuda Linux | 3        | 0.81%   |
| EndeavourOS  | 3        | 0.81%   |
| Xubuntu      | 2        | 0.54%   |
| openSUSE     | 2        | 0.54%   |
| Nobara       | 2        | 0.54%   |
| NixOS        | 2        | 0.54%   |
| MX           | 2        | 0.54%   |
| Lubuntu      | 2        | 0.54%   |
| SteamOS      | 1        | 0.27%   |
| Solus        | 1        | 0.27%   |
| Parrot       | 1        | 0.27%   |
| Endless      | 1        | 0.27%   |
| Elementary   | 1        | 0.27%   |
| BlackPanther | 1        | 0.27%   |
| Anarchy      | 1        | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 11       | 2.59%   |
| 6.2.6-desktop-1omv2390   | 6        | 1.41%   |
| 5.4.0-52-generic         | 6        | 1.41%   |
| 5.16.7-desktop-1omv4003  | 6        | 1.41%   |
| 5.15.0-58-generic        | 5        | 1.18%   |
| 5.15.0-56-generic        | 5        | 1.18%   |
| 5.8.0-43-generic         | 4        | 0.94%   |
| 5.4.0-42-generic         | 4        | 0.94%   |
| 5.11.12-desktop-1omv4002 | 4        | 0.94%   |
| 4.15.0-48-generic        | 4        | 0.94%   |
| 6.2.6-76060206-generic   | 3        | 0.71%   |
| 5.8.5-arch1-1            | 3        | 0.71%   |
| 5.4.0-91-generic         | 3        | 0.71%   |
| 5.4.0-90-generic         | 3        | 0.71%   |
| 5.4.0-73-generic         | 3        | 0.71%   |
| 5.4.0-58-generic         | 3        | 0.71%   |
| 5.4.0-29-generic         | 3        | 0.71%   |
| 5.3.0-28-generic         | 3        | 0.71%   |
| 5.19.0-38-generic        | 3        | 0.71%   |
| 5.15.0-69-generic        | 3        | 0.71%   |
| 5.15.0-46-generic        | 3        | 0.71%   |
| 5.15.0-41-generic        | 3        | 0.71%   |
| 5.13.0-28-generic        | 3        | 0.71%   |
| 5.11.0-7620-generic      | 3        | 0.71%   |
| 5.11.0-41-generic        | 3        | 0.71%   |
| 5.11.0-37-generic        | 3        | 0.71%   |
| 5.11.0-27-generic        | 3        | 0.71%   |
| 5.10.0-20-amd64          | 3        | 0.71%   |
| 5.0.0-13-generic         | 3        | 0.71%   |
| 4.15.0-45-generic        | 3        | 0.71%   |
| 6.4.4-200.fc38.x86_64    | 2        | 0.47%   |
| 6.4.11-desktop-1omv2390  | 2        | 0.47%   |
| 6.2.6-arch1-1            | 2        | 0.47%   |
| 6.2.0-76060200-generic   | 2        | 0.47%   |
| 6.1.9-arch1-1            | 2        | 0.47%   |
| 6.1.0-13-amd64           | 2        | 0.47%   |
| 5.8.0-7642-generic       | 2        | 0.47%   |
| 5.8.0-63-generic         | 2        | 0.47%   |
| 5.8.0-41-generic         | 2        | 0.47%   |
| 5.6.15-1-MANJARO         | 2        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 52       | 12.84%  |
| 5.15.0  | 32       | 7.9%    |
| 4.15.0  | 28       | 6.91%   |
| 5.8.0   | 21       | 5.19%   |
| 5.13.0  | 19       | 4.69%   |
| 5.11.0  | 19       | 4.69%   |
| 5.19.0  | 16       | 3.95%   |
| 6.2.6   | 11       | 2.72%   |
| 5.3.0   | 11       | 2.72%   |
| 5.10.14 | 11       | 2.72%   |
| 5.10.0  | 10       | 2.47%   |
| 5.0.0   | 8        | 1.98%   |
| 6.2.0   | 6        | 1.48%   |
| 5.16.7  | 6        | 1.48%   |
| 6.1.0   | 5        | 1.23%   |
| 4.18.0  | 5        | 1.23%   |
| 5.11.12 | 4        | 0.99%   |
| 4.19.0  | 4        | 0.99%   |
| 6.5.5   | 3        | 0.74%   |
| 5.8.5   | 3        | 0.74%   |
| 5.6.15  | 3        | 0.74%   |
| 6.6.0   | 2        | 0.49%   |
| 6.5.3   | 2        | 0.49%   |
| 6.4.8   | 2        | 0.49%   |
| 6.4.4   | 2        | 0.49%   |
| 6.4.11  | 2        | 0.49%   |
| 6.3.9   | 2        | 0.49%   |
| 6.3.5   | 2        | 0.49%   |
| 6.3.4   | 2        | 0.49%   |
| 6.2.8   | 2        | 0.49%   |
| 6.1.9   | 2        | 0.49%   |
| 6.1.12  | 2        | 0.49%   |
| 6.1.1   | 2        | 0.49%   |
| 5.9.1   | 2        | 0.49%   |
| 5.8.18  | 2        | 0.49%   |
| 5.6.12  | 2        | 0.49%   |
| 5.4.18  | 2        | 0.49%   |
| 5.19.5  | 2        | 0.49%   |
| 5.16.0  | 2        | 0.49%   |
| 5.13.12 | 2        | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 56       | 14.14%  |
| 5.15    | 40       | 10.1%   |
| 5.8     | 30       | 7.58%   |
| 4.15    | 28       | 7.07%   |
| 5.11    | 27       | 6.82%   |
| 5.10    | 23       | 5.81%   |
| 5.13    | 22       | 5.56%   |
| 6.2     | 20       | 5.05%   |
| 5.19    | 19       | 4.8%    |
| 6.1     | 17       | 4.29%   |
| 5.16    | 13       | 3.28%   |
| 5.3     | 11       | 2.78%   |
| 6.3     | 10       | 2.53%   |
| 6.5     | 9        | 2.27%   |
| 6.4     | 9        | 2.27%   |
| 5.0     | 8        | 2.02%   |
| 5.6     | 7        | 1.77%   |
| 6.0     | 6        | 1.52%   |
| 6.6     | 5        | 1.26%   |
| 5.7     | 5        | 1.26%   |
| 4.19    | 5        | 1.26%   |
| 4.18    | 5        | 1.26%   |
| 5.17    | 4        | 1.01%   |
| 5.9     | 3        | 0.76%   |
| 5.14    | 3        | 0.76%   |
| 4.9     | 3        | 0.76%   |
| 5.18    | 2        | 0.51%   |
| 5.12    | 2        | 0.51%   |
| 5.1     | 2        | 0.51%   |
| 5.2     | 1        | 0.25%   |
| 4.17    | 1        | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 350      | 98.87%  |
| i686   | 4        | 1.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 153      | 41.13%  |
| KDE5          | 76       | 20.43%  |
| Unknown       | 60       | 16.13%  |
| X-Cinnamon    | 26       | 6.99%   |
| XFCE          | 23       | 6.18%   |
| MATE          | 9        | 2.42%   |
| KDE           | 7        | 1.88%   |
| Cinnamon      | 4        | 1.08%   |
| LXQt          | 3        | 0.81%   |
| KDE4          | 2        | 0.54%   |
| i3            | 2        | 0.54%   |
| Pantheon      | 1        | 0.27%   |
| openbox       | 1        | 0.27%   |
| LXDE          | 1        | 0.27%   |
| Hyprland      | 1        | 0.27%   |
| enlightenment | 1        | 0.27%   |
| Deepin        | 1        | 0.27%   |
| bspwm         | 1        | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 284      | 76.96%  |
| Wayland | 48       | 13.01%  |
| Unknown | 26       | 7.05%   |
| Tty     | 11       | 2.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 199      | 53.78%  |
| SDDM    | 69       | 18.65%  |
| GDM3    | 36       | 9.73%   |
| GDM     | 25       | 6.76%   |
| LightDM | 22       | 5.95%   |
| TDM     | 15       | 4.05%   |
| KDM     | 2        | 0.54%   |
| LXDM    | 1        | 0.27%   |
| GREETD  | 1        | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 131      | 35.79%  |
| da_DK      | 109      | 29.78%  |
| en_DK      | 51       | 13.93%  |
| Unknown    | 44       | 12.02%  |
| en_GB      | 14       | 3.83%   |
| C          | 4        | 1.09%   |
| ru_RU      | 2        | 0.55%   |
| pl_PL      | 2        | 0.55%   |
| de_DE      | 2        | 0.55%   |
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
| BIOS | 201      | 55.07%  |
| EFI  | 164      | 44.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 276      | 74.19%  |
| Btrfs   | 41       | 11.02%  |
| Overlay | 30       | 8.06%   |
| Unknown | 13       | 3.49%   |
| Tmpfs   | 5        | 1.34%   |
| Zfs     | 4        | 1.08%   |
| Xfs     | 2        | 0.54%   |
| F2fs    | 1        | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 200      | 54.05%  |
| GPT     | 134      | 36.22%  |
| MBR     | 36       | 9.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 285      | 77.66%  |
| Yes       | 82       | 22.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 258      | 71.47%  |
| Yes       | 103      | 28.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 124      | 35.03%  |
| Gigabyte Technology | 49       | 13.84%  |
| MSI                 | 35       | 9.89%   |
| ASRock              | 32       | 9.04%   |
| Lenovo              | 31       | 8.76%   |
| Hewlett-Packard     | 22       | 6.21%   |
| Dell                | 12       | 3.39%   |
| Medion              | 11       | 3.11%   |
| Acer                | 10       | 2.82%   |
| Pegatron            | 4        | 1.13%   |
| Shuttle             | 3        | 0.85%   |
| Intel               | 3        | 0.85%   |
| Packard Bell        | 2        | 0.56%   |
| Fujitsu             | 2        | 0.56%   |
| BESSTAR Tech        | 2        | 0.56%   |
| T-bao               | 1        | 0.28%   |
| NEXCOM              | 1        | 0.28%   |
| Inventec            | 1        | 0.28%   |
| IceWhale Technology | 1        | 0.28%   |
| Fujitsu Siemens     | 1        | 0.28%   |
| eMachines           | 1        | 0.28%   |
| ECS                 | 1        | 0.28%   |
| AMI                 | 1        | 0.28%   |
| Alienware           | 1        | 0.28%   |
| ADLINK Technology   | 1        | 0.28%   |
| ABIT                | 1        | 0.28%   |
| Unknown             | 1        | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 6        | 1.69%   |
| ASUS ROG STRIX B450-E GAMING | 5        | 1.41%   |
| ASUS Z170 PRO GAMING         | 4        | 1.13%   |
| ASUS TUF Gaming X570-PLUS    | 4        | 1.13%   |
| ASUS ROG STRIX B550-F GAMING | 4        | 1.13%   |
| MSI MS-7C37                  | 3        | 0.85%   |
| MSI MS-7C02                  | 3        | 0.85%   |
| Gigabyte X570 AORUS MASTER   | 3        | 0.85%   |
| Dell OptiPlex 9020           | 3        | 0.85%   |
| ASUS ROG STRIX X570-E GAMING | 3        | 0.85%   |
| ASUS PRIME Z390-A            | 3        | 0.85%   |
| MSI MS-7B79                  | 2        | 0.56%   |
| MSI MS-7A34                  | 2        | 0.56%   |
| MSI MS-7693                  | 2        | 0.56%   |
| Medion MS-7797               | 2        | 0.56%   |
| Medion MS-7646               | 2        | 0.56%   |
| Lenovo H30-05 90BJ00CNMT     | 2        | 0.56%   |
| HP Compaq 6200 Pro SFF PC    | 2        | 0.56%   |
| Gigabyte P85-D3              | 2        | 0.56%   |
| BESSTAR Tech HM90            | 2        | 0.56%   |
| ASUS Z170-P                  | 2        | 0.56%   |
| ASUS TUF Gaming B550-PLUS    | 2        | 0.56%   |
| ASUS ROG STRIX X470-I GAMING | 2        | 0.56%   |
| ASUS ROG Maximus X HERO      | 2        | 0.56%   |
| ASUS PRIME Z690M-PLUS D4     | 2        | 0.56%   |
| ASUS PRIME Z370-P            | 2        | 0.56%   |
| ASUS PRIME Z370-A            | 2        | 0.56%   |
| ASUS PRIME X570-P            | 2        | 0.56%   |
| ASUS PRIME B250M-A           | 2        | 0.56%   |
| ASUS PRIME A320M-K           | 2        | 0.56%   |
| ASUS M5A78L-M/USB3           | 2        | 0.56%   |
| ASUS M5A78L-M LX V2          | 2        | 0.56%   |
| ASUS CROSSHAIR VI HERO       | 2        | 0.56%   |
| ASRock B550M-ITX/ac          | 2        | 0.56%   |
| ASRock B450 Gaming K4        | 2        | 0.56%   |
| T-bao MINI PC                | 1        | 0.28%   |
| Shuttle X50V2PLUS            | 1        | 0.28%   |
| Shuttle SN68S                | 1        | 0.28%   |
| Shuttle SH67H3               | 1        | 0.28%   |
| Pegatron HPE-532sc           | 1        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS ROG            | 30       | 8.47%   |
| ASUS PRIME          | 30       | 8.47%   |
| Lenovo ThinkCentre  | 14       | 3.95%   |
| ASUS TUF            | 14       | 3.95%   |
| HP Compaq           | 9        | 2.54%   |
| Gigabyte X570       | 8        | 2.26%   |
| Acer Aspire         | 7        | 1.98%   |
| Lenovo ThinkStation | 6        | 1.69%   |
| Dell OptiPlex       | 6        | 1.69%   |
| ASUS All            | 6        | 1.69%   |
| Lenovo IdeaCentre   | 4        | 1.13%   |
| ASUS Z170           | 4        | 1.13%   |
| ASUS SABERTOOTH     | 4        | 1.13%   |
| ASUS M5A78L-M       | 4        | 1.13%   |
| MSI MS-7C37         | 3        | 0.85%   |
| MSI MS-7C02         | 3        | 0.85%   |
| HP ProLiant         | 3        | 0.85%   |
| Gigabyte B550       | 3        | 0.85%   |
| ASRock Z170         | 3        | 0.85%   |
| ASRock B450         | 3        | 0.85%   |
| MSI MS-7B79         | 2        | 0.56%   |
| MSI MS-7A34         | 2        | 0.56%   |
| MSI MS-7693         | 2        | 0.56%   |
| Medion MS-7797      | 2        | 0.56%   |
| Medion MS-7646      | 2        | 0.56%   |
| Lenovo H30-05       | 2        | 0.56%   |
| HP Pavilion         | 2        | 0.56%   |
| HP EliteDesk        | 2        | 0.56%   |
| Gigabyte Z390       | 2        | 0.56%   |
| Gigabyte P85-D3     | 2        | 0.56%   |
| Gigabyte B650       | 2        | 0.56%   |
| Gigabyte A320M-S2H  | 2        | 0.56%   |
| Fujitsu ESPRIMO     | 2        | 0.56%   |
| Dell Precision      | 2        | 0.56%   |
| BESSTAR Tech HM90   | 2        | 0.56%   |
| ASUS Z170-P         | 2        | 0.56%   |
| ASUS Maximus        | 2        | 0.56%   |
| ASUS CROSSHAIR      | 2        | 0.56%   |
| ASRock Z77          | 2        | 0.56%   |
| ASRock B550M-ITX    | 2        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 40       | 11.3%   |
| 2019 | 39       | 11.02%  |
| 2020 | 35       | 9.89%   |
| 2012 | 31       | 8.76%   |
| 2021 | 25       | 7.06%   |
| 2017 | 25       | 7.06%   |
| 2013 | 21       | 5.93%   |
| 2011 | 21       | 5.93%   |
| 2015 | 20       | 5.65%   |
| 2016 | 19       | 5.37%   |
| 2014 | 16       | 4.52%   |
| 2010 | 15       | 4.24%   |
| 2022 | 14       | 3.95%   |
| 2008 | 12       | 3.39%   |
| 2009 | 11       | 3.11%   |
| 2007 | 6        | 1.69%   |
| 2023 | 2        | 0.56%   |
| 2006 | 2        | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 354      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 347      | 97.75%  |
| Enabled  | 8        | 2.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 354      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 115      | 31.59%  |
| 32.01-64.0      | 81       | 22.25%  |
| 8.01-16.0       | 59       | 16.21%  |
| 3.01-4.0        | 33       | 9.07%   |
| 4.01-8.0        | 32       | 8.79%   |
| 64.01-256.0     | 26       | 7.14%   |
| 24.01-32.0      | 11       | 3.02%   |
| 1.01-2.0        | 4        | 1.1%    |
| 2.01-3.0        | 2        | 0.55%   |
| More than 256.0 | 1        | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 128      | 32%     |
| 2.01-3.0   | 95       | 23.75%  |
| 4.01-8.0   | 75       | 18.75%  |
| 3.01-4.0   | 57       | 14.25%  |
| 8.01-16.0  | 20       | 5%      |
| 0.51-1.0   | 12       | 3%      |
| 24.01-32.0 | 4        | 1%      |
| 0.01-0.5   | 4        | 1%      |
| 16.01-24.0 | 3        | 0.75%   |
| 32.01-64.0 | 2        | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 131      | 35.41%  |
| 2      | 88       | 23.78%  |
| 3      | 75       | 20.27%  |
| 4      | 37       | 10%     |
| 5      | 23       | 6.22%   |
| 6      | 7        | 1.89%   |
| 8      | 3        | 0.81%   |
| 0      | 3        | 0.81%   |
| 7      | 2        | 0.54%   |
| 9      | 1        | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 213      | 59.66%  |
| Yes       | 144      | 40.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 351      | 99.15%  |
| No        | 3        | 0.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 190      | 52.78%  |
| Yes       | 170      | 47.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 231      | 64.53%  |
| Yes       | 127      | 35.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Denmark | 354      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Copenhagen               | 87       | 23.64%  |
| Frederiksberg            | 19       | 5.16%   |
| Odense                   | 16       | 4.35%   |
| Aarhus                   | 13       | 3.53%   |
| Slagelse                 | 10       | 2.72%   |
| Horsens                  | 9        | 2.45%   |
| Silkeborg                | 7        | 1.9%    |
| Esbjerg                  | 7        | 1.9%    |
| Bronshoj                 | 7        | 1.9%    |
| Valby                    | 6        | 1.63%   |
| Aalborg                  | 6        | 1.63%   |
| Aabenraa                 | 6        | 1.63%   |
| Vejle                    | 4        | 1.09%   |
| Roskilde                 | 4        | 1.09%   |
| Hjørring                | 4        | 1.09%   |
| Herlev                   | 4        | 1.09%   |
| Glostrup Municipality    | 4        | 1.09%   |
| Allinge                  | 4        | 1.09%   |
| Albertslund Municipality | 4        | 1.09%   |
| Trige                    | 3        | 0.82%   |
| Taastrup                 | 3        | 0.82%   |
| Svendborg                | 3        | 0.82%   |
| Rødovre Municipality    | 3        | 0.82%   |
| Pandrup                  | 3        | 0.82%   |
| Nyborg                   | 3        | 0.82%   |
| Ishøj                   | 3        | 0.82%   |
| Hvidovre                 | 3        | 0.82%   |
| Gentofte Municipality    | 3        | 0.82%   |
| Fredericia               | 3        | 0.82%   |
| Aabybro                  | 3        | 0.82%   |
| Viby J                   | 2        | 0.54%   |
| Tranbjerg                | 2        | 0.54%   |
| Tilst                    | 2        | 0.54%   |
| Stovring                 | 2        | 0.54%   |
| Soborg                   | 2        | 0.54%   |
| Skanderborg              | 2        | 0.54%   |
| Risskov                  | 2        | 0.54%   |
| Odder                    | 2        | 0.54%   |
| Kongens Lyngby           | 2        | 0.54%   |
| Kolding                  | 2        | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 143      | 265    | 20.97%  |
| Seagate                     | 116      | 177    | 17.01%  |
| WDC                         | 103      | 167    | 15.1%   |
| Kingston                    | 67       | 100    | 9.82%   |
| Crucial                     | 29       | 39     | 4.25%   |
| SanDisk                     | 28       | 38     | 4.11%   |
| Toshiba                     | 27       | 37     | 3.96%   |
| Intel                       | 20       | 24     | 2.93%   |
| Hitachi                     | 17       | 25     | 2.49%   |
| Phison Electronics          | 9        | 14     | 1.32%   |
| Corsair                     | 9        | 12     | 1.32%   |
| Unknown                     | 8        | 9      | 1.17%   |
| Intenso                     | 8        | 11     | 1.17%   |
| Phison                      | 7        | 10     | 1.03%   |
| A-DATA Technology           | 7        | 7      | 1.03%   |
| PNY                         | 5        | 6      | 0.73%   |
| HGST                        | 5        | 8      | 0.73%   |
| SK hynix                    | 4        | 4      | 0.59%   |
| OCZ                         | 4        | 4      | 0.59%   |
| Kingston Technology Company | 4        | 4      | 0.59%   |
| Verbatim                    | 3        | 6      | 0.44%   |
| Micron/Crucial Technology   | 3        | 3      | 0.44%   |
| Micron Technology           | 3        | 4      | 0.44%   |
| LITEON                      | 3        | 3      | 0.44%   |
| JMicron Technology          | 3        | 3      | 0.44%   |
| Fujitsu                     | 3        | 7      | 0.44%   |
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
| Unknown                     | 2        | 4      | 0.29%   |
| USB                         | 1        | 1      | 0.15%   |
| Unknown (CF)                | 1        | 1      | 0.15%   |
| Supersonic                  | 1        | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 12       | 1.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 11       | 1.36%   |
| Seagate ST2000DM001-1ER164 2TB                      | 9        | 1.11%   |
| Samsung SSD 860 QVO 1TB                             | 9        | 1.11%   |
| Kingston SV300S37A120G 120GB SSD                    | 9        | 1.11%   |
| Samsung SSD 860 EVO 1TB                             | 8        | 0.99%   |
| Samsung SSD 850 EVO 250GB                           | 8        | 0.99%   |
| Samsung NVMe SSD Drive 500GB                        | 8        | 0.99%   |
| Kingston SA400S37480G 480GB SSD                     | 8        | 0.99%   |
| Kingston SA400S37240G 240GB SSD                     | 8        | 0.99%   |
| Samsung SSD 860 EVO 500GB                           | 7        | 0.86%   |
| Samsung SSD 850 EVO 500GB                           | 7        | 0.86%   |
| Samsung SSD 840 EVO 250GB                           | 7        | 0.86%   |
| Samsung NVMe SSD Drive 1TB                          | 7        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB                     | 6        | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB                      | 6        | 0.74%   |
| Phison E12 NVMe Controller 1TB                      | 6        | 0.74%   |
| Seagate ST1000DM003-1SB102 1TB                      | 5        | 0.62%   |
| Kingston SA400S37120G 120GB SSD                     | 5        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                         | 5        | 0.62%   |
| Unknown SD/MMC/MS PRO 512GB                         | 4        | 0.49%   |
| Seagate ST4000VN008-2DR166 4TB                      | 4        | 0.49%   |
| Seagate ST2000DM001-1CH164 2TB                      | 4        | 0.49%   |
| Seagate ST1000DM003-1SB10C 1TB                      | 4        | 0.49%   |
| Samsung SSD 970 EVO Plus 500GB                      | 4        | 0.49%   |
| Samsung SSD 970 EVO 1TB                             | 4        | 0.49%   |
| Samsung SSD 850 EVO 120GB                           | 4        | 0.49%   |
| Samsung HD103SJ 1TB                                 | 4        | 0.49%   |
| Phison E16 PCIe4 NVMe Controller 2TB                | 4        | 0.49%   |
| Kingston SV300S37A240G 240GB SSD                    | 4        | 0.49%   |
| Kingston SUV400S37120G 120GB SSD                    | 4        | 0.49%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3        | 0.37%   |
| WDC WD20EARX-00PASB0 2TB                            | 3        | 0.37%   |
| WDC WD1003FZEX-00K3CA0 1TB                          | 3        | 0.37%   |
| Toshiba MQ01ABD100 1TB                              | 3        | 0.37%   |
| Toshiba DT01ACA200 2TB                              | 3        | 0.37%   |
| Toshiba DT01ACA050 500GB                            | 3        | 0.37%   |
| Seagate ST3250310AS 250GB                           | 3        | 0.37%   |
| Seagate ST3000DM008-2DM166 3TB                      | 3        | 0.37%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 112      | 170    | 41.03%  |
| WDC                 | 85       | 148    | 31.14%  |
| Toshiba             | 24       | 34     | 8.79%   |
| Hitachi             | 17       | 25     | 6.23%   |
| Samsung Electronics | 13       | 20     | 4.76%   |
| HGST                | 5        | 8      | 1.83%   |
| Unknown             | 4        | 5      | 1.47%   |
| Fujitsu             | 3        | 7      | 1.1%    |
| Maxtor              | 2        | 2      | 0.73%   |
| Apple               | 2        | 5      | 0.73%   |
| Unknown             | 2        | 4      | 0.73%   |
| USB                 | 1        | 1      | 0.37%   |
| Intenso             | 1        | 2      | 0.37%   |
| Hewlett-Packard     | 1        | 3      | 0.37%   |
| ASMT109x            | 1        | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 86       | 147    | 33.59%  |
| Kingston            | 54       | 75     | 21.09%  |
| Crucial             | 24       | 34     | 9.38%   |
| SanDisk             | 12       | 12     | 4.69%   |
| WDC                 | 10       | 10     | 3.91%   |
| Intel               | 9        | 11     | 3.52%   |
| A-DATA Technology   | 6        | 6      | 2.34%   |
| PNY                 | 5        | 6      | 1.95%   |
| Intenso             | 5        | 5      | 1.95%   |
| OCZ                 | 4        | 4      | 1.56%   |
| Corsair             | 4        | 5      | 1.56%   |
| Verbatim            | 3        | 6      | 1.17%   |
| Micron Technology   | 3        | 4      | 1.17%   |
| LITEON              | 3        | 3      | 1.17%   |
| JMicron Technology  | 3        | 3      | 1.17%   |
| Transcend           | 2        | 2      | 0.78%   |
| Team                | 2        | 2      | 0.78%   |
| Patriot             | 2        | 3      | 0.78%   |
| Leven               | 2        | 2      | 0.78%   |
| AFOX                | 2        | 2      | 0.78%   |
| Unknown (CF)        | 1        | 1      | 0.39%   |
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

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 206      | 364    | 36.65%  |
| HDD     | 203      | 435    | 36.12%  |
| NVMe    | 141      | 235    | 25.09%  |
| Unknown | 8        | 8      | 1.42%   |
| MMC     | 4        | 4      | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 299      | 767    | 62.68%  |
| NVMe | 141      | 234    | 29.56%  |
| SAS  | 33       | 41     | 6.92%   |
| MMC  | 4        | 4      | 0.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 214      | 388    | 46.12%  |
| 0.51-1.0   | 124      | 193    | 26.72%  |
| 1.01-2.0   | 61       | 103    | 13.15%  |
| 2.01-3.0   | 21       | 34     | 4.53%   |
| 4.01-10.0  | 20       | 43     | 4.31%   |
| 3.01-4.0   | 17       | 25     | 3.66%   |
| 10.01-20.0 | 7        | 13     | 1.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 67       | 17.59%  |
| 251-500        | 64       | 16.8%   |
| 101-250        | 62       | 16.27%  |
| 1001-2000      | 50       | 13.12%  |
| More than 3000 | 46       | 12.07%  |
| 2001-3000      | 26       | 6.82%   |
| 1-20           | 26       | 6.82%   |
| Unknown        | 17       | 4.46%   |
| 21-50          | 13       | 3.41%   |
| 51-100         | 10       | 2.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 120      | 31.17%  |
| 21-50          | 58       | 15.06%  |
| 101-250        | 48       | 12.47%  |
| 501-1000       | 40       | 10.39%  |
| 251-500        | 32       | 8.31%   |
| 51-100         | 29       | 7.53%   |
| 1001-2000      | 19       | 4.94%   |
| Unknown        | 17       | 4.42%   |
| More than 3000 | 16       | 4.16%   |
| 2001-3000      | 6        | 1.56%   |

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
| Detected | 235      | 629    | 57.18%  |
| Works    | 145      | 372    | 35.28%  |
| Malfunc  | 31       | 45     | 7.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 216      | 37.89%  |
| AMD                          | 131      | 22.98%  |
| Samsung Electronics          | 67       | 11.75%  |
| Kingston Technology Company  | 25       | 4.39%   |
| ASMedia Technology           | 25       | 4.39%   |
| SanDisk                      | 22       | 3.86%   |
| Phison Electronics           | 20       | 3.51%   |
| JMicron Technology           | 13       | 2.28%   |
| Marvell Technology Group     | 11       | 1.93%   |
| Nvidia                       | 9        | 1.58%   |
| Micron/Crucial Technology    | 8        | 1.4%    |
| Seagate Technology           | 5        | 0.88%   |
| ADATA Technology             | 4        | 0.7%    |
| SK hynix                     | 3        | 0.53%   |
| VIA Technologies             | 2        | 0.35%   |
| Toshiba America Info Systems | 2        | 0.35%   |
| Realtek Semiconductor        | 2        | 0.35%   |
| Silicon Motion               | 1        | 0.18%   |
| KIOXIA                       | 1        | 0.18%   |
| HighPoint Technologies       | 1        | 0.18%   |
| Hewlett-Packard              | 1        | 0.18%   |
| Broadcom / LSI               | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 94       | 13.54%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 40       | 5.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 28       | 4.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 24       | 3.46%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 23       | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 22       | 3.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 22       | 3.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19       | 2.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 18       | 2.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16       | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15       | 2.16%   |
| AMD 500 Series Chipset SATA Controller                                                  | 14       | 2.02%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 12       | 1.73%   |
| Phison E12 NVMe Controller                                                              | 11       | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11       | 1.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9        | 1.3%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 9        | 1.3%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 9        | 1.3%    |
| Intel SATA Controller [RAID mode]                                                       | 9        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.15%   |
| AMD 300 Series Chipset SATA Controller                                                  | 8        | 1.15%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7        | 1.01%   |
| Intel SSD 660P Series                                                                   | 7        | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 1.01%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 6        | 0.86%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 6        | 0.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 6        | 0.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.86%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                                  | 5        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 0.72%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 0.72%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.72%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 0.72%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4        | 0.58%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.58%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 315      | 57.59%  |
| NVMe | 143      | 26.14%  |
| IDE  | 63       | 11.52%  |
| RAID | 25       | 4.57%   |
| SAS  | 1        | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 217      | 61.3%   |
| AMD    | 137      | 38.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 11       | 3.09%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 9        | 2.53%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 8        | 2.25%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 8        | 2.25%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 8        | 2.25%   |
| Intel Core i5-6600K CPU @ 3.50GHz      | 6        | 1.69%   |
| Intel Core i7-8700K CPU @ 3.70GHz      | 5        | 1.4%    |
| Intel Core i5-7500 CPU @ 3.40GHz       | 5        | 1.4%    |
| AMD Ryzen 7 1700 Eight-Core Processor  | 5        | 1.4%    |
| Intel Core i9-9900K CPU @ 3.60GHz      | 4        | 1.12%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 4        | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 4        | 1.12%   |
| Intel Core i5-3350P CPU @ 3.10GHz      | 4        | 1.12%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 4        | 1.12%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 4        | 1.12%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 4        | 1.12%   |
| AMD Ryzen 5 7600X 6-Core Processor     | 4        | 1.12%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 3        | 0.84%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 3        | 0.84%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 3        | 0.84%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 3        | 0.84%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 3        | 0.84%   |
| Intel Core i7 CPU 860 @ 2.80GHz        | 3        | 0.84%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 3        | 0.84%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 3        | 0.84%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 3        | 0.84%   |
| Intel Core i5-2500 CPU @ 3.30GHz       | 3        | 0.84%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 3        | 0.84%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 3        | 0.84%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz   | 3        | 0.84%   |
| Intel 12th Gen Core i9-12900K          | 3        | 0.84%   |
| Intel 12th Gen Core i7-12700K          | 3        | 0.84%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 3        | 0.84%   |
| AMD Ryzen 7 5800X3D 8-Core Processor   | 3        | 0.84%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 3        | 0.84%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 3        | 0.84%   |
| AMD Ryzen 3 1200 Quad-Core Processor   | 3        | 0.84%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 0.56%   |
| Intel Core i7-5820K CPU @ 3.30GHz      | 2        | 0.56%   |
| Intel Core i7-4770S CPU @ 3.10GHz      | 2        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 65       | 18.31%  |
| Intel Core i7           | 61       | 17.18%  |
| AMD Ryzen 7             | 35       | 9.86%   |
| AMD Ryzen 5             | 32       | 9.01%   |
| AMD Ryzen 9             | 24       | 6.76%   |
| Other                   | 18       | 5.07%   |
| Intel Core i3           | 16       | 4.51%   |
| Intel Xeon              | 14       | 3.94%   |
| Intel Core 2 Duo        | 11       | 3.1%    |
| AMD FX                  | 10       | 2.82%   |
| Intel Core i9           | 7        | 1.97%   |
| Intel Celeron           | 6        | 1.69%   |
| Intel Core 2 Quad       | 5        | 1.41%   |
| AMD Ryzen 3             | 5        | 1.41%   |
| AMD Ryzen Threadripper  | 4        | 1.13%   |
| AMD Phenom II X4        | 4        | 1.13%   |
| AMD Athlon 64 X2        | 4        | 1.13%   |
| AMD A8                  | 4        | 1.13%   |
| AMD A6                  | 4        | 1.13%   |
| Intel Pentium           | 3        | 0.85%   |
| Intel Atom              | 3        | 0.85%   |
| AMD Athlon II X4        | 3        | 0.85%   |
| AMD A10                 | 3        | 0.85%   |
| Intel Pentium Dual-Core | 2        | 0.56%   |
| Intel Core 2            | 2        | 0.56%   |
| AMD A4                  | 2        | 0.56%   |
| Intel Pentium Silver    | 1        | 0.28%   |
| Intel Pentium Dual      | 1        | 0.28%   |
| Intel Core m5           | 1        | 0.28%   |
| Intel Core 2 Extreme    | 1        | 0.28%   |
| AMD Phenom II X2        | 1        | 0.28%   |
| AMD GX                  | 1        | 0.28%   |
| AMD E                   | 1        | 0.28%   |
| AMD Athlon II Neo       | 1        | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 136      | 38.2%   |
| 6      | 64       | 17.98%  |
| 2      | 60       | 16.85%  |
| 8      | 49       | 13.76%  |
| 12     | 20       | 5.62%   |
| 16     | 14       | 3.93%   |
| 10     | 4        | 1.12%   |
| 1      | 3        | 0.84%   |
| 24     | 2        | 0.56%   |
| 64     | 1        | 0.28%   |
| 32     | 1        | 0.28%   |
| 14     | 1        | 0.28%   |
| 3      | 1        | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 352      | 99.44%  |
| 2      | 2        | 0.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 228      | 64.41%  |
| 1      | 126      | 35.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 350      | 98.04%  |
| Unknown        | 7        | 1.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 103      | 27.76%  |
| 0x306c3    | 23       | 6.2%    |
| 0x306a9    | 17       | 4.58%   |
| 0x506e3    | 16       | 4.31%   |
| 0x206a7    | 15       | 4.04%   |
| 0x08701021 | 12       | 3.23%   |
| 0x0800820d | 11       | 2.96%   |
| 0x906ea    | 9        | 2.43%   |
| 0x08001138 | 9        | 2.43%   |
| 0x906e9    | 8        | 2.16%   |
| 0x90672    | 8        | 2.16%   |
| 0x1067a    | 8        | 2.16%   |
| 0x0a601203 | 7        | 1.89%   |
| 0x08701013 | 7        | 1.89%   |
| 0x0a201009 | 6        | 1.62%   |
| 0x906ed    | 5        | 1.35%   |
| 0x06000852 | 5        | 1.35%   |
| 0x010000c8 | 5        | 1.35%   |
| 0xa0655    | 4        | 1.08%   |
| 0xa0653    | 4        | 1.08%   |
| 0x906ec    | 4        | 1.08%   |
| 0x6fd      | 4        | 1.08%   |
| 0xa0671    | 3        | 0.81%   |
| 0x106e5    | 3        | 0.81%   |
| 0x10676    | 3        | 0.81%   |
| 0x0a201205 | 3        | 0.81%   |
| 0x0a201016 | 3        | 0.81%   |
| 0x08701030 | 3        | 0.81%   |
| 0x08600106 | 3        | 0.81%   |
| 0x08001129 | 3        | 0.81%   |
| 0x06001119 | 3        | 0.81%   |
| 0x6f6      | 2        | 0.54%   |
| 0x506c9    | 2        | 0.54%   |
| 0x206c2    | 2        | 0.54%   |
| 0x0a50000c | 2        | 0.54%   |
| 0x08108109 | 2        | 0.54%   |
| 0x08001137 | 2        | 0.54%   |
| 0x06003106 | 2        | 0.54%   |
| 0x0600063e | 2        | 0.54%   |
| 0x010000db | 2        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 44       | 12.36%  |
| Zen 2            | 37       | 10.39%  |
| Haswell          | 33       | 9.27%   |
| Skylake          | 25       | 7.02%   |
| Zen 3            | 24       | 6.74%   |
| SandyBridge      | 23       | 6.46%   |
| IvyBridge        | 23       | 6.46%   |
| Penryn           | 16       | 4.49%   |
| Zen+             | 15       | 4.21%   |
| Zen              | 15       | 4.21%   |
| Unknown          | 15       | 4.21%   |
| Piledriver       | 11       | 3.09%   |
| Alderlake Hybrid | 10       | 2.81%   |
| K10              | 9        | 2.53%   |
| CometLake        | 8        | 2.25%   |
| Core             | 7        | 1.97%   |
| Nehalem          | 6        | 1.69%   |
| Westmere         | 4        | 1.12%   |
| K8 Hammer        | 4        | 1.12%   |
| Icelake          | 4        | 1.12%   |
| Steamroller      | 3        | 0.84%   |
| Puma             | 3        | 0.84%   |
| Bulldozer        | 3        | 0.84%   |
| Broadwell        | 3        | 0.84%   |
| Jaguar           | 2        | 0.56%   |
| Goldmont         | 2        | 0.56%   |
| Bonnell          | 2        | 0.56%   |
| Silvermont       | 1        | 0.28%   |
| K10 Llano        | 1        | 0.28%   |
| Goldmont plus    | 1        | 0.28%   |
| Excavator        | 1        | 0.28%   |
| Bobcat           | 1        | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 190      | 49.35%  |
| AMD                        | 108      | 28.05%  |
| Intel                      | 85       | 22.08%  |
| Matrox Electronics Systems | 1        | 0.26%   |
| ASPEED Technology          | 1        | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 16       | 4.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 3.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 3.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 2.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 9        | 2.28%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 8        | 2.03%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 8        | 2.03%   |
| Intel HD Graphics 630                                                       | 8        | 2.03%   |
| Intel HD Graphics 530                                                       | 8        | 2.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 2.03%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 7        | 1.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 1.78%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.52%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 1.52%   |
| AMD Raphael                                                                 | 6        | 1.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.27%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 5        | 1.27%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 5        | 1.27%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 1.27%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 4        | 1.02%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4        | 1.02%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.02%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 4        | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.02%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.02%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 1.02%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 1.02%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 4        | 1.02%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 4        | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 1.02%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.02%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 3        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 3        | 0.76%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.76%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 3        | 0.76%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 0.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 176      | 49.3%   |
| 1 x AMD         | 91       | 25.49%  |
| 1 x Intel       | 64       | 17.93%  |
| 2 x AMD         | 6        | 1.68%   |
| Intel + Nvidia  | 6        | 1.68%   |
| AMD + Nvidia    | 5        | 1.4%    |
| Intel + AMD     | 4        | 1.12%   |
| 2 x Nvidia      | 2        | 0.56%   |
| 2 x Intel       | 1        | 0.28%   |
| Nvidia + ASPEED | 1        | 0.28%   |
| 1 x Matrox      | 1        | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 234      | 63.93%  |
| Proprietary | 120      | 32.79%  |
| Unknown     | 12       | 3.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 138      | 37.6%   |
| 1.01-2.0   | 62       | 16.89%  |
| 7.01-8.0   | 56       | 15.26%  |
| 3.01-4.0   | 24       | 6.54%   |
| 0.01-0.5   | 23       | 6.27%   |
| 5.01-6.0   | 22       | 5.99%   |
| 8.01-16.0  | 17       | 4.63%   |
| 0.51-1.0   | 15       | 4.09%   |
| 2.01-3.0   | 5        | 1.36%   |
| 16.01-24.0 | 4        | 1.09%   |
| 4.01-5.0   | 1        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 87       | 21.97%  |
| Dell                 | 39       | 9.85%   |
| AOC                  | 26       | 6.57%   |
| Philips              | 25       | 6.31%   |
| Ancor Communications | 25       | 6.31%   |
| Hewlett-Packard      | 24       | 6.06%   |
| Acer                 | 24       | 6.06%   |
| BenQ                 | 20       | 5.05%   |
| Lenovo               | 19       | 4.8%    |
| ASUSTek Computer     | 19       | 4.8%    |
| Goldstar             | 14       | 3.54%   |
| Sony                 | 9        | 2.27%   |
| Unknown              | 6        | 1.52%   |
| Medion               | 6        | 1.52%   |
| Lenovo Group Limited | 5        | 1.26%   |
| LG Electronics       | 4        | 1.01%   |
| IBM                  | 3        | 0.76%   |
| Gigabyte Technology  | 3        | 0.76%   |
| Fujitsu Siemens      | 3        | 0.76%   |
| ViewSonic            | 2        | 0.51%   |
| Vestel Elektronik    | 2        | 0.51%   |
| Tech Concepts        | 2        | 0.51%   |
| MSI                  | 2        | 0.51%   |
| Idek Iiyama          | 2        | 0.51%   |
| AUS                  | 2        | 0.51%   |
| Unknown              | 2        | 0.51%   |
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


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch           | 6        | 1.35%   |
| Acer KG241Q ACR0604 1920x1080 521x293mm 23.5-inch                      | 4        | 0.9%    |
| Sony TV SNYEE01 1920x1080                                              | 3        | 0.67%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3        | 0.67%   |
| Samsung Electronics LCD Monitor S24F350 1920x1080                      | 3        | 0.67%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 3        | 0.67%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 3        | 0.67%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 3        | 0.67%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 3        | 0.67%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch       | 3        | 0.67%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 2        | 0.45%   |
| Tech Concepts LCD Monitor TCL SMART TV 3840x2160                       | 2        | 0.45%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch      | 2        | 0.45%   |
| Samsung Electronics SyncMaster SAM055E 1920x1080 510x290mm 23.1-inch   | 2        | 0.45%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 2        | 0.45%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 2        | 0.45%   |
| Samsung Electronics LCD Monitor LF27T35 1920x1080                      | 2        | 0.45%   |
| Samsung Electronics LC27G5xT SAM707A 2560x1440 698x393mm 31.5-inch     | 2        | 0.45%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch     | 2        | 0.45%   |
| Philips PHL 278E8Q PHLC161 1920x1080 598x336mm 27.0-inch               | 2        | 0.45%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch               | 2        | 0.45%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch               | 2        | 0.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2        | 0.45%   |
| Medion MD20444 MED3661 1920x1080 521x293mm 23.5-inch                   | 2        | 0.45%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch             | 2        | 0.45%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch               | 2        | 0.45%   |
| Lenovo G27q-20 LEN66C3 2560x1440 597x336mm 27.0-inch                   | 2        | 0.45%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch             | 2        | 0.45%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch               | 2        | 0.45%   |
| Gigabyte Technology G32QC GBT3200 2560x1440 697x392mm 31.5-inch        | 2        | 0.45%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                      | 2        | 0.45%   |
| Dell P2312H DEL4077 1920x1080 510x287mm 23.0-inch                      | 2        | 0.45%   |
| Dell P1913 DELA089 1440x900 408x255mm 18.9-inch                        | 2        | 0.45%   |
| Dell 2407WFP DELA017 1920x1200 519x324mm 24.1-inch                     | 2        | 0.45%   |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                     | 2        | 0.45%   |
| BenQ G2420HDB BNQ7842 1920x1080 477x268mm 21.5-inch                    | 2        | 0.45%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 2        | 0.45%   |
| BenQ EX3501R BNQ7F5E 3440x1440 819x346mm 35.0-inch                     | 2        | 0.45%   |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch           | 2        | 0.45%   |
| ASUSTek Computer VG27A AUS2722 2560x1440 597x336mm 27.0-inch           | 2        | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 169      | 43.56%  |
| 2560x1440 (QHD)    | 50       | 12.89%  |
| 3840x2160 (4K)     | 44       | 11.34%  |
| 1680x1050 (WSXGA+) | 19       | 4.9%    |
| Unknown            | 18       | 4.64%   |
| 1280x1024 (SXGA)   | 17       | 4.38%   |
| 3440x1440          | 12       | 3.09%   |
| 1920x1200 (WUXGA)  | 9        | 2.32%   |
| 3840x1080          | 7        | 1.8%    |
| 1600x900 (HD+)     | 7        | 1.8%    |
| 1440x900 (WXGA+)   | 7        | 1.8%    |
| 1360x768           | 4        | 1.03%   |
| 3840x1200          | 3        | 0.77%   |
| 2560x1080          | 2        | 0.52%   |
| 1920x540           | 2        | 0.52%   |
| 9840x3840          | 1        | 0.26%   |
| 6400x2160          | 1        | 0.26%   |
| 5760x1440          | 1        | 0.26%   |
| 5760x1080          | 1        | 0.26%   |
| 5120x1440          | 1        | 0.26%   |
| 4608x1440          | 1        | 0.26%   |
| 4480x1440          | 1        | 0.26%   |
| 3840x1600          | 1        | 0.26%   |
| 3280x1080          | 1        | 0.26%   |
| 3200x1200          | 1        | 0.26%   |
| 3200x1080          | 1        | 0.26%   |
| 2560x1600          | 1        | 0.26%   |
| 2560x1024          | 1        | 0.26%   |
| 2288x1287          | 1        | 0.26%   |
| 2048x1152          | 1        | 0.26%   |
| 1600x1200          | 1        | 0.26%   |
| 1366x768 (WXGA)    | 1        | 0.26%   |
| 1360x765           | 1        | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 81       | 20.66%  |
| 24      | 65       | 16.58%  |
| Unknown | 51       | 13.01%  |
| 23      | 43       | 10.97%  |
| 31      | 28       | 7.14%   |
| 21      | 21       | 5.36%   |
| 19      | 17       | 4.34%   |
| 22      | 14       | 3.57%   |
| 20      | 13       | 3.32%   |
| 34      | 11       | 2.81%   |
| 72      | 8        | 2.04%   |
| 84      | 6        | 1.53%   |
| 32      | 4        | 1.02%   |
| 40      | 3        | 0.77%   |
| 17      | 3        | 0.77%   |
| 15      | 3        | 0.77%   |
| 48      | 2        | 0.51%   |
| 38      | 2        | 0.51%   |
| 35      | 2        | 0.51%   |
| 28      | 2        | 0.51%   |
| 25      | 2        | 0.51%   |
| 65      | 1        | 0.26%   |
| 60      | 1        | 0.26%   |
| 54      | 1        | 0.26%   |
| 43      | 1        | 0.26%   |
| 42      | 1        | 0.26%   |
| 39      | 1        | 0.26%   |
| 33      | 1        | 0.26%   |
| 30      | 1        | 0.26%   |
| 29      | 1        | 0.26%   |
| 26      | 1        | 0.26%   |
| 18      | 1        | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 166      | 44.27%  |
| 401-500     | 54       | 14.4%   |
| Unknown     | 51       | 13.6%   |
| 601-700     | 41       | 10.93%  |
| 701-800     | 16       | 4.27%   |
| 1501-2000   | 14       | 3.73%   |
| 351-400     | 12       | 3.2%    |
| 801-900     | 8        | 2.13%   |
| 301-350     | 6        | 1.6%    |
| 1001-1500   | 6        | 1.6%    |
| 901-1000    | 1        | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 233      | 65.08%  |
| Unknown | 45       | 12.57%  |
| 16/10   | 43       | 12.01%  |
| 5/4     | 15       | 4.19%   |
| 21/9    | 15       | 4.19%   |
| 32/9    | 3        | 0.84%   |
| 4/3     | 2        | 0.56%   |
| 3/2     | 1        | 0.28%   |
| 3.20    | 1        | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 114      | 29.38%  |
| 301-350        | 81       | 20.88%  |
| Unknown        | 51       | 13.14%  |
| 351-500        | 49       | 12.63%  |
| 151-200        | 34       | 8.76%   |
| 251-300        | 26       | 6.7%    |
| More than 1000 | 17       | 4.38%   |
| 501-1000       | 10       | 2.58%   |
| 141-150        | 3        | 0.77%   |
| 101-110        | 2        | 0.52%   |
| 111-120        | 1        | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 216      | 60.34%  |
| 101-120 | 63       | 17.6%   |
| Unknown | 51       | 14.25%  |
| 121-160 | 13       | 3.63%   |
| 1-50    | 9        | 2.51%   |
| 161-240 | 6        | 1.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 251      | 69.53%  |
| 2     | 78       | 21.61%  |
| 0     | 20       | 5.54%   |
| 3     | 12       | 3.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 207      | 40.04%  |
| Intel                           | 172      | 33.27%  |
| Qualcomm Atheros                | 19       | 3.68%   |
| Broadcom                        | 18       | 3.48%   |
| MediaTek                        | 10       | 1.93%   |
| Ralink Technology               | 9        | 1.74%   |
| Ralink                          | 9        | 1.74%   |
| Nvidia                          | 9        | 1.74%   |
| Aquantia                        | 7        | 1.35%   |
| TP-Link                         | 6        | 1.16%   |
| ASUSTek Computer                | 6        | 1.16%   |
| Microsoft                       | 5        | 0.97%   |
| Qualcomm Atheros Communications | 4        | 0.77%   |
| IMC Networks                    | 4        | 0.77%   |
| Huawei Technologies             | 4        | 0.77%   |
| OnePlus Technology (Shenzhen)   | 3        | 0.58%   |
| NetGear                         | 3        | 0.58%   |
| Edimax Technology               | 3        | 0.58%   |
| D-Link                          | 3        | 0.58%   |
| Samsung Electronics             | 2        | 0.39%   |
| D-Link System                   | 2        | 0.39%   |
| ASIX Electronics                | 2        | 0.39%   |
| Unknown                         | 1        | 0.19%   |
| Texas Instruments               | 1        | 0.19%   |
| Solarflare Communications       | 1        | 0.19%   |
| ROCCAT                          | 1        | 0.19%   |
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


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 161      | 27.2%   |
| Intel I211 Gigabit Network Connection                             | 31       | 5.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28       | 4.73%   |
| Intel Ethernet Connection (2) I219-V                              | 23       | 3.89%   |
| Intel Wi-Fi 6 AX200                                               | 20       | 3.38%   |
| Intel Ethernet Controller I225-V                                  | 15       | 2.53%   |
| Intel Ethernet Connection (7) I219-V                              | 12       | 2.03%   |
| Intel Ethernet Connection I217-LM                                 | 11       | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 1.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9        | 1.52%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 9        | 1.52%   |
| Intel Wireless-AC 9260                                            | 8        | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 7        | 1.18%   |
| Realtek 802.11ac NIC                                              | 5        | 0.84%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5        | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 0.84%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4        | 0.68%   |
| Intel I210 Gigabit Network Connection                             | 4        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 0.68%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]              | 4        | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.51%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 3        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.51%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.51%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3        | 0.51%   |
| OnePlus (Shenzhen) Android                                        | 3        | 0.51%   |
| Nvidia MCP73 Ethernet                                             | 3        | 0.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 3        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.51%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 0.51%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.51%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 61       | 33.52%  |
| Realtek Semiconductor           | 32       | 17.58%  |
| Broadcom                        | 14       | 7.69%   |
| Qualcomm Atheros                | 11       | 6.04%   |
| Ralink Technology               | 9        | 4.95%   |
| Ralink                          | 9        | 4.95%   |
| MediaTek                        | 9        | 4.95%   |
| TP-Link                         | 6        | 3.3%    |
| ASUSTek Computer                | 6        | 3.3%    |
| Microsoft                       | 5        | 2.75%   |
| Qualcomm Atheros Communications | 4        | 2.2%    |
| IMC Networks                    | 4        | 2.2%    |
| NetGear                         | 3        | 1.65%   |
| Edimax Technology               | 3        | 1.65%   |
| D-Link                          | 3        | 1.65%   |
| D-Link System                   | 2        | 1.1%    |
| Linksys                         | 1        | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 20       | 10.75%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 9        | 4.84%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                         | 9        | 4.84%   |
| Intel Wireless-AC 9260                                                               | 8        | 4.3%    |
| Realtek 802.11ac NIC                                                                 | 5        | 2.69%   |
| Ralink RT5370 Wireless Adapter                                                       | 5        | 2.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                              | 5        | 2.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 5        | 2.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 4        | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4        | 2.15%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                     | 4        | 2.15%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                 | 4        | 2.15%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 3        | 1.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 3        | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3        | 1.61%   |
| Ralink MT7601U Wireless Adapter                                                      | 3        | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 3        | 1.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                        | 3        | 1.61%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                         | 3        | 1.61%   |
| TP-Link 802.11ac WLAN Adapter                                                        | 2        | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.08%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 2        | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 1.08%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 2        | 1.08%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                                            | 2        | 1.08%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                            | 2        | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 2        | 1.08%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2        | 1.08%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 2        | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 2        | 1.08%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                          | 2        | 1.08%   |
| Microsoft Xbox Wireless Adapter for Windows                                          | 2        | 1.08%   |
| Microsoft Xbox 360 Wireless Adapter                                                  | 2        | 1.08%   |
| Intel Wireless 8265 / 8275                                                           | 2        | 1.08%   |
| Intel Wireless 8260                                                                  | 2        | 1.08%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 2        | 1.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 1        | 0.54%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1        | 0.54%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                | 1        | 0.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 194      | 50.26%  |
| Intel                         | 147      | 38.08%  |
| Qualcomm Atheros              | 10       | 2.59%   |
| Nvidia                        | 9        | 2.33%   |
| Aquantia                      | 7        | 1.81%   |
| Broadcom                      | 4        | 1.04%   |
| OnePlus Technology (Shenzhen) | 3        | 0.78%   |
| Samsung Electronics           | 2        | 0.52%   |
| Huawei Technologies           | 2        | 0.52%   |
| ASIX Electronics              | 2        | 0.52%   |
| Solarflare Communications     | 1        | 0.26%   |
| MediaTek                      | 1        | 0.26%   |
| Lenovo                        | 1        | 0.26%   |
| JMicron Technology            | 1        | 0.26%   |
| ICS Advent                    | 1        | 0.26%   |
| HMD Global                    | 1        | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 161      | 40.25%  |
| Intel I211 Gigabit Network Connection                             | 31       | 7.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 28       | 7%      |
| Intel Ethernet Connection (2) I219-V                              | 23       | 5.75%   |
| Intel Ethernet Controller I225-V                                  | 15       | 3.75%   |
| Intel Ethernet Connection (7) I219-V                              | 12       | 3%      |
| Intel Ethernet Connection I217-LM                                 | 11       | 2.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 2.75%   |
| Intel 82579V Gigabit Network Connection                           | 7        | 1.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5        | 1.25%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 1.25%   |
| Intel I210 Gigabit Network Connection                             | 4        | 1%      |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1%      |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 0.75%   |
| OnePlus (Shenzhen) Android                                        | 3        | 0.75%   |
| Nvidia MCP73 Ethernet                                             | 3        | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.75%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 0.75%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.75%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 2        | 0.5%    |
| Intel Ethernet Connection I217-V                                  | 2        | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.5%    |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.5%    |
| Huawei MAR-LX1M                                                   | 2        | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.5%    |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.25%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.25%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 351      | 66.6%   |
| WiFi     | 170      | 32.26%  |
| Modem    | 4        | 0.76%   |
| Unknown  | 2        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 286      | 77.09%  |
| WiFi     | 85       | 22.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 205      | 57.42%  |
| 2     | 124      | 34.73%  |
| 3     | 22       | 6.16%   |
| 0     | 3        | 0.84%   |
| 4     | 2        | 0.56%   |
| 5     | 1        | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 336      | 94.38%  |
| Yes  | 20       | 5.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 58       | 43.94%  |
| Cambridge Silicon Radio         | 33       | 25%     |
| ASUSTek Computer                | 9        | 6.82%   |
| MediaTek                        | 7        | 5.3%    |
| IMC Networks                    | 6        | 4.55%   |
| Qualcomm Atheros Communications | 5        | 3.79%   |
| Broadcom                        | 5        | 3.79%   |
| Realtek Semiconductor           | 4        | 3.03%   |
| Belkin Components               | 2        | 1.52%   |
| Integrated System Solution      | 1        | 0.76%   |
| HTC (High Tech Computer)        | 1        | 0.76%   |
| Edimax Technology               | 1        | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 33       | 25%     |
| Intel AX200 Bluetooth                                                | 16       | 12.12%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 9        | 6.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 8        | 6.06%   |
| Intel Bluetooth wireless interface                                   | 8        | 6.06%   |
| MediaTek Wireless_Device                                             | 7        | 5.3%    |
| Intel Bluetooth Device                                               | 6        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 5        | 3.79%   |
| Intel AX210 Bluetooth                                                | 5        | 3.79%   |
| ASUS Bluetooth Device                                                | 5        | 3.79%   |
| IMC Networks Bluetooth Radio                                         | 4        | 3.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3        | 2.27%   |
| Realtek RTL8821A Bluetooth                                           | 2        | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2        | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2        | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 2        | 1.52%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 2        | 1.52%   |
| ASUS Bluetooth Radio                                                 | 2        | 1.52%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1        | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 0.76%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 0.76%   |
| IMC Networks Wireless_Device                                         | 1        | 0.76%   |
| IMC Networks Bluetooth Device                                        | 1        | 0.76%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.76%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter              | 1        | 0.76%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 0.76%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 0.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.76%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 199      | 29.18%  |
| Nvidia                               | 187      | 27.42%  |
| AMD                                  | 162      | 23.75%  |
| SteelSeries ApS                      | 16       | 2.35%   |
| Kingston Technology                  | 14       | 2.05%   |
| C-Media Electronics                  | 14       | 2.05%   |
| ASUSTek Computer                     | 10       | 1.47%   |
| Logitech                             | 9        | 1.32%   |
| Creative Technology                  | 9        | 1.32%   |
| Creative Labs                        | 9        | 1.32%   |
| GN Netcom                            | 5        | 0.73%   |
| XMOS                                 | 3        | 0.44%   |
| RODE Microphones                     | 3        | 0.44%   |
| Yamaha                               | 2        | 0.29%   |
| VIA Technologies                     | 2        | 0.29%   |
| Texas Instruments                    | 2        | 0.29%   |
| Realtek Semiconductor                | 2        | 0.29%   |
| Razer USA                            | 2        | 0.29%   |
| JMTek                                | 2        | 0.29%   |
| Focusrite-Novation                   | 2        | 0.29%   |
| Corsair                              | 2        | 0.29%   |
| BEHRINGER International              | 2        | 0.29%   |
| Valve Software                       | 1        | 0.15%   |
| Turtle Beach                         | 1        | 0.15%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.15%   |
| Tenx Technology                      | 1        | 0.15%   |
| Syntek                               | 1        | 0.15%   |
| Sony                                 | 1        | 0.15%   |
| Shure                                | 1        | 0.15%   |
| Setek Elektronik                     | 1        | 0.15%   |
| Samsung Electronics                  | 1        | 0.15%   |
| ROCCAT                               | 1        | 0.15%   |
| Musical Fidelity                     | 1        | 0.15%   |
| Hewlett-Packard                      | 1        | 0.15%   |
| GYROCOM C&C                          | 1        | 0.15%   |
| Ensoniq                              | 1        | 0.15%   |
| DSEA A/S                             | 1        | 0.15%   |
| Dell                                 | 1        | 0.15%   |
| Clavia DMI AB                        | 1        | 0.15%   |
| BR23                                 | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 49       | 6.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 26       | 3.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 24       | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 23       | 2.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 22       | 2.83%   |
| Intel 200 Series PCH HD Audio                                                                   | 22       | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 20       | 2.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 18       | 2.32%   |
| AMD Navi 10 HDMI Audio                                                                          | 18       | 2.32%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 18       | 2.32%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 17       | 2.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 16       | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 15       | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                                      | 15       | 1.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 15       | 1.93%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 14       | 1.8%    |
| Nvidia GP106 High Definition Audio Controller                                                   | 13       | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 12       | 1.54%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 12       | 1.54%   |
| AMD FCH Azalia Controller                                                                       | 12       | 1.54%   |
| Nvidia TU104 HD Audio Controller                                                                | 11       | 1.42%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 11       | 1.42%   |
| Nvidia GK104 HDMI Audio Controller                                                              | 10       | 1.29%   |
| Kingston Technology HyperX 7.1 Audio                                                            | 10       | 1.29%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 10       | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 9        | 1.16%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 8        | 1.03%   |
| ASUSTek Computer USB Audio                                                                      | 8        | 1.03%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 7        | 0.9%    |
| Nvidia GK107 HDMI Audio Controller                                                              | 7        | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 7        | 0.9%    |
| Nvidia GP108 High Definition Audio Controller                                                   | 6        | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 6        | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 6        | 0.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 6        | 0.77%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 6        | 0.77%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 6        | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 6        | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                                        | 6        | 0.77%   |
| SteelSeries ApS SteelSeries Arctis 7                                                            | 5        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 49       | 23.22%  |
| Kingston            | 37       | 17.54%  |
| G.Skill             | 32       | 15.17%  |
| Samsung Electronics | 24       | 11.37%  |
| Unknown             | 20       | 9.48%   |
| Crucial             | 13       | 6.16%   |
| Micron Technology   | 12       | 5.69%   |
| SK hynix            | 10       | 4.74%   |
| Ramaxel Technology  | 4        | 1.9%    |
| Nanya Technology    | 3        | 1.42%   |
| Unknown             | 2        | 0.95%   |
| Unknown (ABCD)      | 1        | 0.47%   |
| Unifosa             | 1        | 0.47%   |
| Patriot             | 1        | 0.47%   |
| GOODRAM             | 1        | 0.47%   |
| Elpida              | 1        | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 9        | 4.05%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s | 4        | 1.8%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s  | 4        | 1.8%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s      | 3        | 1.35%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 3        | 1.35%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s | 3        | 1.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 2        | 0.9%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                | 2        | 0.9%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 2        | 0.9%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s  | 2        | 0.9%    |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s    | 2        | 0.9%    |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s    | 2        | 0.9%    |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s    | 2        | 0.9%    |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s    | 2        | 0.9%    |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 1600MT/s | 2        | 0.9%    |
| Kingston RAM KF556C36-16 16GB DIMM DDR5 6400MT/s       | 2        | 0.9%    |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s       | 2        | 0.9%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 0.9%    |
| Kingston RAM HP24D4U7S8MBP-8 8GB DIMM DDR4 2400MT/s    | 2        | 0.9%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s | 2        | 0.9%    |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 2        | 0.9%    |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 2        | 0.9%    |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s  | 2        | 0.9%    |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s    | 2        | 0.9%    |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s  | 2        | 0.9%    |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s   | 2        | 0.9%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s | 2        | 0.9%    |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s | 2        | 0.9%    |
| Unknown                                                | 2        | 0.9%    |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s              | 1        | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s               | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1        | 0.45%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                   | 1        | 0.45%   |
| Unknown RAM Module 4096MB DIMM                         | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s              | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 0.45%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 0.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 1        | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s            | 1        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 109      | 57.07%  |
| DDR3    | 47       | 24.61%  |
| DDR5    | 11       | 5.76%   |
| Unknown | 10       | 5.24%   |
| SDRAM   | 8        | 4.19%   |
| DDR2    | 2        | 1.05%   |
| DDR     | 2        | 1.05%   |
| LPDDR4  | 1        | 0.52%   |
| LPDDR3  | 1        | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 175      | 93.09%  |
| SODIMM | 13       | 6.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 84       | 41.58%  |
| 16384 | 48       | 23.76%  |
| 4096  | 33       | 16.34%  |
| 2048  | 22       | 10.89%  |
| 32768 | 11       | 5.45%   |
| 1024  | 3        | 1.49%   |
| 512   | 1        | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 29       | 14.15%  |
| 3200    | 22       | 10.73%  |
| 3600    | 20       | 9.76%   |
| 1333    | 17       | 8.29%   |
| 2400    | 15       | 7.32%   |
| 3400    | 9        | 4.39%   |
| 2667    | 7        | 3.41%   |
| 3000    | 5        | 2.44%   |
| 2133    | 5        | 2.44%   |
| 1800    | 5        | 2.44%   |
| 3800    | 4        | 1.95%   |
| 3733    | 4        | 1.95%   |
| 3666    | 4        | 1.95%   |
| 3533    | 4        | 1.95%   |
| 6400    | 3        | 1.46%   |
| 5200    | 3        | 1.46%   |
| 4800    | 3        | 1.46%   |
| 3534    | 3        | 1.46%   |
| 2933    | 3        | 1.46%   |
| 2666    | 3        | 1.46%   |
| 1867    | 3        | 1.46%   |
| 667     | 3        | 1.46%   |
| 3866    | 2        | 0.98%   |
| 3500    | 2        | 0.98%   |
| 3466    | 2        | 0.98%   |
| 2800    | 2        | 0.98%   |
| 2048    | 2        | 0.98%   |
| 1639    | 2        | 0.98%   |
| Unknown | 2        | 0.98%   |
| 20306   | 1        | 0.49%   |
| 6000    | 1        | 0.49%   |
| 5600    | 1        | 0.49%   |
| 4400    | 1        | 0.49%   |
| 4000    | 1        | 0.49%   |
| 3333    | 1        | 0.49%   |
| 3266    | 1        | 0.49%   |
| 3100    | 1        | 0.49%   |
| 2733    | 1        | 0.49%   |
| 2448    | 1        | 0.49%   |
| 2000    | 1        | 0.49%   |

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
| Logitech                               | 25       | 53.19%  |
| Microsoft                              | 4        | 8.51%   |
| Creative Technology                    | 3        | 6.38%   |
| Trust                                  | 2        | 4.26%   |
| Sunplus Innovation Technology          | 2        | 4.26%   |
| Samsung Electronics                    | 2        | 4.26%   |
| Valve Software                         | 1        | 2.13%   |
| Quanta                                 | 1        | 2.13%   |
| Oculus VR                              | 1        | 2.13%   |
| Intel                                  | 1        | 2.13%   |
| Hewlett-Packard                        | 1        | 2.13%   |
| GenesysLogic Technology                | 1        | 2.13%   |
| Cubeternet                             | 1        | 2.13%   |
| Chicony Electronics                    | 1        | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Logitech StreamCam                                                   | 4        | 8.51%   |
| Logitech HD Webcam C525                                              | 3        | 6.38%   |
| Logitech HD Pro Webcam C920                                          | 3        | 6.38%   |
| Trust USB Camera                                                     | 2        | 4.26%   |
| Samsung Galaxy series, misc. (MTP mode)                              | 2        | 4.26%   |
| Microsoft LifeCam Cinema                                             | 2        | 4.26%   |
| Logitech Webcam Pro 9000                                             | 2        | 4.26%   |
| Logitech Webcam C270                                                 | 2        | 4.26%   |
| Logitech C930c                                                       | 2        | 4.26%   |
| Logitech C922 Pro Stream Webcam                                      | 2        | 4.26%   |
| Valve Software 3D Camera                                             | 1        | 2.13%   |
| Sunplus SunplusIT PC Camera                                          | 1        | 2.13%   |
| Sunplus Sandberg USB Webcam Pro                                      | 1        | 2.13%   |
| Quanta FREETALK Conference                                           | 1        | 2.13%   |
| Oculus VR Quest 2                                                    | 1        | 2.13%   |
| Microsoft MicrosoftÂ LifeCam Studio                                 | 1        | 2.13%   |
| Microsoft LifeCam HD-3000                                            | 1        | 2.13%   |
| Logitech Webcam C930e                                                | 1        | 2.13%   |
| Logitech Webcam C925e                                                | 1        | 2.13%   |
| Logitech QuickCam Pro 5000                                           | 1        | 2.13%   |
| Logitech QuickCam E 3500                                             | 1        | 2.13%   |
| Logitech HD Webcam C510                                              | 1        | 2.13%   |
| Logitech C670i FHD Webcam                                            | 1        | 2.13%   |
| Logitech BRIO Ultra HD Webcam                                        | 1        | 2.13%   |
| Intel RealSense SR300                                                | 1        | 2.13%   |
| HP HD-4110 Webcam                                                    | 1        | 2.13%   |
| GenesysLogic USB2.0 UVC PC Camera                                    | 1        | 2.13%   |
| Cubeternet USB2.0 Camera                                             | 1        | 2.13%   |
| Creative VF0610 Live! Cam Socialize HD                               | 1        | 2.13%   |
| Creative Live! Cam Sync [VF0520]                                     | 1        | 2.13%   |
| Creative Live! Cam Sync 1080p                                        | 1        | 2.13%   |
| Chicony Gateway Webcam                                               | 1        | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1        | 2.13%   |

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
| 0     | 300      | 83.1%   |
| 1     | 46       | 12.74%  |
| 2     | 10       | 2.77%   |
| 3     | 3        | 0.83%   |
| 6     | 1        | 0.28%   |
| 4     | 1        | 0.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 20       | 27.03%  |
| Net/wireless             | 19       | 25.68%  |
| Sound                    | 7        | 9.46%   |
| Communication controller | 7        | 9.46%   |
| Unassigned class         | 6        | 8.11%   |
| Multimedia controller    | 6        | 8.11%   |
| Storage/raid             | 2        | 2.7%    |
| Net/ethernet             | 2        | 2.7%    |
| Card reader              | 2        | 2.7%    |
| Network                  | 1        | 1.35%   |
| Chipcard                 | 1        | 1.35%   |
| Camera                   | 1        | 1.35%   |

