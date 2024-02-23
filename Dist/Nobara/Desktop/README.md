Nobara - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Nobara.

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

Total: 590

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Z390-PLUS GAMING        | [f708da8a98](https://linux-hardware.org/?probe=f708da8a98) | Feb 01, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | [52f18f604d](https://linux-hardware.org/?probe=52f18f604d) | Feb 01, 2024 |
| Intel         | B75                         | [000ad7f808](https://linux-hardware.org/?probe=000ad7f808) | Jan 31, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | [df2c10b408](https://linux-hardware.org/?probe=df2c10b408) | Jan 29, 2024 |
| HP            | 1497                        | [edbda38746](https://linux-hardware.org/?probe=edbda38746) | Jan 29, 2024 |
| HP            | 212B                        | [fb3993d66a](https://linux-hardware.org/?probe=fb3993d66a) | Jan 28, 2024 |
| NZXT          | N7 B650E                    | [2a31518f97](https://linux-hardware.org/?probe=2a31518f97) | Jan 28, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a85c3034f2](https://linux-hardware.org/?probe=a85c3034f2) | Jan 27, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [c1267550bc](https://linux-hardware.org/?probe=c1267550bc) | Jan 27, 2024 |
| ASUSTek       | PRIME B450M-K II            | [531cd352a8](https://linux-hardware.org/?probe=531cd352a8) | Jan 27, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [30139ed46d](https://linux-hardware.org/?probe=30139ed46d) | Jan 27, 2024 |
| Gigabyte      | B460M DS3H AC V2-Y1         | [13a3740810](https://linux-hardware.org/?probe=13a3740810) | Jan 26, 2024 |
| ASUSTek       | PRIME B450M-K II            | [04feb5fc7d](https://linux-hardware.org/?probe=04feb5fc7d) | Jan 26, 2024 |
| ASRock        | B450M Pro4 R2.0             | [cb67574020](https://linux-hardware.org/?probe=cb67574020) | Jan 26, 2024 |
| ASRock        | B550 Pro4                   | [e6dfa57418](https://linux-hardware.org/?probe=e6dfa57418) | Jan 26, 2024 |
| ASRock        | Z97 Anniversary             | [0973057025](https://linux-hardware.org/?probe=0973057025) | Jan 25, 2024 |
| NZXT          | N7 B650E                    | [9354117703](https://linux-hardware.org/?probe=9354117703) | Jan 25, 2024 |
| Pegatron      | 2AB6                        | [660b2b76ed](https://linux-hardware.org/?probe=660b2b76ed) | Jan 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f7ebff5e4f](https://linux-hardware.org/?probe=f7ebff5e4f) | Jan 20, 2024 |
| MSI           | MEG X570 UNIFY              | [d732f80c75](https://linux-hardware.org/?probe=d732f80c75) | Jan 18, 2024 |
| ASRock        | B450M Pro4                  | [195a26ad26](https://linux-hardware.org/?probe=195a26ad26) | Jan 17, 2024 |
| ASUSTek       | PRIME A320M-K               | [b4bb61edfe](https://linux-hardware.org/?probe=b4bb61edfe) | Jan 17, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [781a81dea6](https://linux-hardware.org/?probe=781a81dea6) | Jan 17, 2024 |
| MSI           | Z170-A PRO                  | [bcf19edc1d](https://linux-hardware.org/?probe=bcf19edc1d) | Jan 16, 2024 |
| ASUSTek       | Q87M-E                      | [318aab51d9](https://linux-hardware.org/?probe=318aab51d9) | Jan 15, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | [3ea676a743](https://linux-hardware.org/?probe=3ea676a743) | Jan 14, 2024 |
| Dell          | 0DYHRY A00                  | [d605dd9a8a](https://linux-hardware.org/?probe=d605dd9a8a) | Jan 14, 2024 |
| ASRock        | Z97M Pro4                   | [594754cd87](https://linux-hardware.org/?probe=594754cd87) | Jan 13, 2024 |
| ASRock        | B760M Steel Legend WiFi     | [a3bc588c07](https://linux-hardware.org/?probe=a3bc588c07) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [23c4e3e208](https://linux-hardware.org/?probe=23c4e3e208) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b98091e5e6](https://linux-hardware.org/?probe=b98091e5e6) | Jan 13, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | [e3c1908003](https://linux-hardware.org/?probe=e3c1908003) | Jan 13, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [1b25ee0779](https://linux-hardware.org/?probe=1b25ee0779) | Jan 13, 2024 |
| ASUSTek       | PRIME Z390-A                | [bcbcc04761](https://linux-hardware.org/?probe=bcbcc04761) | Jan 13, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [e5de7f8ed8](https://linux-hardware.org/?probe=e5de7f8ed8) | Jan 13, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [daefd59105](https://linux-hardware.org/?probe=daefd59105) | Jan 13, 2024 |
| Intel         | X79G V2.x                   | [cf61b1759b](https://linux-hardware.org/?probe=cf61b1759b) | Jan 12, 2024 |
| MSI           | B250M PRO-VD                | [5f11aaf980](https://linux-hardware.org/?probe=5f11aaf980) | Jan 12, 2024 |
| ASRock        | B650M Pro RS WiFi           | [2a5022eba4](https://linux-hardware.org/?probe=2a5022eba4) | Jan 11, 2024 |
| MSI           | B450M PRO-VDH MAX           | [7c77830f2f](https://linux-hardware.org/?probe=7c77830f2f) | Jan 10, 2024 |
| MSI           | B450M MORTAR TITANIUM       | [03202bdde9](https://linux-hardware.org/?probe=03202bdde9) | Jan 10, 2024 |
| ASUSTek       | G10DK                       | [7339bf1ed8](https://linux-hardware.org/?probe=7339bf1ed8) | Jan 09, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [e1d9aaa0f2](https://linux-hardware.org/?probe=e1d9aaa0f2) | Jan 09, 2024 |
| MSI           | B450M MORTAR TITANIUM       | [cd8ee8db1f](https://linux-hardware.org/?probe=cd8ee8db1f) | Jan 09, 2024 |
| MSI           | B250M PRO-VD                | [fc9099926d](https://linux-hardware.org/?probe=fc9099926d) | Jan 09, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | [ce4125a4f0](https://linux-hardware.org/?probe=ce4125a4f0) | Jan 09, 2024 |
| HP            | 8054                        | [94be81d143](https://linux-hardware.org/?probe=94be81d143) | Jan 08, 2024 |
| ASRock        | B450M Pro4                  | [1c83544337](https://linux-hardware.org/?probe=1c83544337) | Jan 08, 2024 |
| Alienware     | 0P0JWX A00                  | [47bd2f6e34](https://linux-hardware.org/?probe=47bd2f6e34) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [ea0e1750c9](https://linux-hardware.org/?probe=ea0e1750c9) | Jan 06, 2024 |
| ASUSTek       | PRIME H410M-K               | [c16b44c1ce](https://linux-hardware.org/?probe=c16b44c1ce) | Jan 06, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [7f28dd699b](https://linux-hardware.org/?probe=7f28dd699b) | Jan 06, 2024 |
| MSI           | MEG X570 UNIFY              | [56df310601](https://linux-hardware.org/?probe=56df310601) | Jan 06, 2024 |
| HP            | 83E1                        | [d3f2371283](https://linux-hardware.org/?probe=d3f2371283) | Jan 05, 2024 |
| ASRock        | H61M                        | [e4a7c28d85](https://linux-hardware.org/?probe=e4a7c28d85) | Jan 04, 2024 |
| Gigabyte      | Z370P D3-CF                 | [42e67a91b0](https://linux-hardware.org/?probe=42e67a91b0) | Jan 04, 2024 |
| Dell          | 0MG0RG A00                  | [f3847b13ce](https://linux-hardware.org/?probe=f3847b13ce) | Jan 04, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | [fb4e22f4a6](https://linux-hardware.org/?probe=fb4e22f4a6) | Jan 03, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f10936a9f7](https://linux-hardware.org/?probe=f10936a9f7) | Jan 02, 2024 |
| ASRock        | B550M-ITX/ac                | [2ae0bbe734](https://linux-hardware.org/?probe=2ae0bbe734) | Jan 01, 2024 |
| MSI           | B250M PRO-VD                | [f0cb030b5f](https://linux-hardware.org/?probe=f0cb030b5f) | Jan 01, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [e1c9fdb53b](https://linux-hardware.org/?probe=e1c9fdb53b) | Dec 31, 2023 |
| ASRock        | B550M-ITX/ac                | [2f69bdfbc7](https://linux-hardware.org/?probe=2f69bdfbc7) | Dec 30, 2023 |
| Gigabyte      | Z77X-UD3H                   | [85c8033229](https://linux-hardware.org/?probe=85c8033229) | Dec 30, 2023 |
| ASRock        | B550M-ITX/ac                | [3729a3492e](https://linux-hardware.org/?probe=3729a3492e) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [9f85581cdb](https://linux-hardware.org/?probe=9f85581cdb) | Dec 29, 2023 |
| Gigabyte      | H61M-S1                     | [6b98d84cb0](https://linux-hardware.org/?probe=6b98d84cb0) | Dec 28, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [ce4c03fbee](https://linux-hardware.org/?probe=ce4c03fbee) | Dec 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [e1bbb2ee71](https://linux-hardware.org/?probe=e1bbb2ee71) | Dec 26, 2023 |
| HP            | 8767 A                      | [6d2a367189](https://linux-hardware.org/?probe=6d2a367189) | Dec 25, 2023 |
| MSI           | MEG X570 UNIFY              | [5cc2120efc](https://linux-hardware.org/?probe=5cc2120efc) | Dec 25, 2023 |
| MSI           | MEG X570 UNIFY              | [6bcc868ad6](https://linux-hardware.org/?probe=6bcc868ad6) | Dec 25, 2023 |
| Gigabyte      | B550 UD AC                  | [b00112da41](https://linux-hardware.org/?probe=b00112da41) | Dec 24, 2023 |
| MSI           | B550-A PRO                  | [64a00841b2](https://linux-hardware.org/?probe=64a00841b2) | Dec 23, 2023 |
| MSI           | PRO B650M-A WIFI            | [4adc5f3f81](https://linux-hardware.org/?probe=4adc5f3f81) | Dec 22, 2023 |
| Alienware     | 0P0JWX A00                  | [99d0e56ef1](https://linux-hardware.org/?probe=99d0e56ef1) | Dec 22, 2023 |
| HP            | 83E0                        | [07e6f563f9](https://linux-hardware.org/?probe=07e6f563f9) | Dec 22, 2023 |
| ASUSTek       | B85-PLUS                    | [58a2ef76f9](https://linux-hardware.org/?probe=58a2ef76f9) | Dec 22, 2023 |
| MSI           | B250M PRO-VD                | [1a4d75f062](https://linux-hardware.org/?probe=1a4d75f062) | Dec 22, 2023 |
| MSI           | H81M-E34                    | [4b1991c655](https://linux-hardware.org/?probe=4b1991c655) | Dec 21, 2023 |
| ASUSTek       | Pro B550M-C                 | [4e3b422400](https://linux-hardware.org/?probe=4e3b422400) | Dec 19, 2023 |
| MSI           | B250M PRO-VD                | [925bd9bbac](https://linux-hardware.org/?probe=925bd9bbac) | Dec 19, 2023 |
| ASUSTek       | Pro B550M-C                 | [1cd7c1b629](https://linux-hardware.org/?probe=1cd7c1b629) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c2a8ace4dd](https://linux-hardware.org/?probe=c2a8ace4dd) | Dec 18, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [8a69294494](https://linux-hardware.org/?probe=8a69294494) | Dec 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [ec58c18087](https://linux-hardware.org/?probe=ec58c18087) | Dec 17, 2023 |
| Gigabyte      | H310M A-CF                  | [cdf7a1ffd4](https://linux-hardware.org/?probe=cdf7a1ffd4) | Dec 15, 2023 |
| MSI           | B450M PRO-M2 MAX            | [93e9419d49](https://linux-hardware.org/?probe=93e9419d49) | Dec 14, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [5d1e9e6d47](https://linux-hardware.org/?probe=5d1e9e6d47) | Dec 13, 2023 |
| ASRock        | X570 Taichi                 | [e17d6cbfa7](https://linux-hardware.org/?probe=e17d6cbfa7) | Dec 12, 2023 |
| MACHINIST     | X99-K9 V2.0                 | [68ba082c42](https://linux-hardware.org/?probe=68ba082c42) | Dec 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [dc0acbdb23](https://linux-hardware.org/?probe=dc0acbdb23) | Dec 10, 2023 |
| ASRock        | X99 Professional Gaming ... | [46be0f459d](https://linux-hardware.org/?probe=46be0f459d) | Dec 10, 2023 |
| AZW           | GTR V02                     | [ece705bc91](https://linux-hardware.org/?probe=ece705bc91) | Dec 09, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [9da65cd80e](https://linux-hardware.org/?probe=9da65cd80e) | Dec 07, 2023 |
| ASRock        | H61M-VG3                    | [acf5ffd938](https://linux-hardware.org/?probe=acf5ffd938) | Dec 06, 2023 |
| MSI           | X470 GAMING PLUS            | [5326fc7737](https://linux-hardware.org/?probe=5326fc7737) | Dec 06, 2023 |
| ASUSTek       | PRIME B450M-K               | [110604e0da](https://linux-hardware.org/?probe=110604e0da) | Dec 05, 2023 |
| ASRock        | H570 Steel Legend           | [e1478d8694](https://linux-hardware.org/?probe=e1478d8694) | Dec 03, 2023 |
| ASRock        | H570 Steel Legend           | [f1d29c75a0](https://linux-hardware.org/?probe=f1d29c75a0) | Dec 03, 2023 |
| HP            | 0B54h D                     | [bffc586a45](https://linux-hardware.org/?probe=bffc586a45) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [a5997eb3f2](https://linux-hardware.org/?probe=a5997eb3f2) | Dec 02, 2023 |
| Dell          | 0FDY5C A00                  | [0d5166b475](https://linux-hardware.org/?probe=0d5166b475) | Dec 02, 2023 |
| ASRock        | B450M Pro4                  | [f86124413d](https://linux-hardware.org/?probe=f86124413d) | Dec 01, 2023 |
| ASRock        | H310CM-DVS                  | [ec402bfe2f](https://linux-hardware.org/?probe=ec402bfe2f) | Nov 30, 2023 |
| Dell          | 0FDY5C A00                  | [2eaa838401](https://linux-hardware.org/?probe=2eaa838401) | Nov 30, 2023 |
| Acer          | Veriton N4680G              | [033223b8bc](https://linux-hardware.org/?probe=033223b8bc) | Nov 30, 2023 |
| MSI           | B450-A PRO MAX              | [6357a41a39](https://linux-hardware.org/?probe=6357a41a39) | Nov 30, 2023 |
| ASUSTek       | B85M-G R2.0                 | [11d3e45e2d](https://linux-hardware.org/?probe=11d3e45e2d) | Nov 29, 2023 |
| ASUSTek       | B85M-G R2.0                 | [d2dcb1f2da](https://linux-hardware.org/?probe=d2dcb1f2da) | Nov 29, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [e5509bd1ba](https://linux-hardware.org/?probe=e5509bd1ba) | Nov 28, 2023 |
| ASUSTek       | Maximus VIII FORMULA        | [a39fba5394](https://linux-hardware.org/?probe=a39fba5394) | Nov 27, 2023 |
| Google        | Kench                       | [efdf5874c1](https://linux-hardware.org/?probe=efdf5874c1) | Nov 27, 2023 |
| MSI           | Z170A GAMING M5             | [ab44413728](https://linux-hardware.org/?probe=ab44413728) | Nov 26, 2023 |
| MSI           | PRO H610M-G DDR4            | [5c10f3d5a1](https://linux-hardware.org/?probe=5c10f3d5a1) | Nov 25, 2023 |
| MSI           | PRO H610M-G DDR4            | [05ba5178cb](https://linux-hardware.org/?probe=05ba5178cb) | Nov 25, 2023 |
| HP            | 8054                        | [dfa212d5da](https://linux-hardware.org/?probe=dfa212d5da) | Nov 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0f9d912f7f](https://linux-hardware.org/?probe=0f9d912f7f) | Nov 24, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [c3b398c792](https://linux-hardware.org/?probe=c3b398c792) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2ab108f743](https://linux-hardware.org/?probe=2ab108f743) | Nov 22, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [639c2b7832](https://linux-hardware.org/?probe=639c2b7832) | Nov 20, 2023 |
| MSI           | PRO H610M-G DDR4            | [0d4fe4c2b9](https://linux-hardware.org/?probe=0d4fe4c2b9) | Nov 19, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [db393353d9](https://linux-hardware.org/?probe=db393353d9) | Nov 18, 2023 |
| ASRock        | B550M Pro4                  | [c00a7584bf](https://linux-hardware.org/?probe=c00a7584bf) | Nov 18, 2023 |
| MSI           | B450M GAMING PLUS           | [038ffaab27](https://linux-hardware.org/?probe=038ffaab27) | Nov 13, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [404f1947fd](https://linux-hardware.org/?probe=404f1947fd) | Nov 11, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [993c65a274](https://linux-hardware.org/?probe=993c65a274) | Nov 06, 2023 |
| Gigabyte      | 970A-DS3P FX                | [615e914ddd](https://linux-hardware.org/?probe=615e914ddd) | Nov 05, 2023 |
| Gigabyte      | 970A-DS3P FX                | [7ba5de3dfd](https://linux-hardware.org/?probe=7ba5de3dfd) | Nov 05, 2023 |
| ASRock        | B450M-HDV R4.0              | [c17ad7033c](https://linux-hardware.org/?probe=c17ad7033c) | Nov 05, 2023 |
| ASRock        | X470 Taichi Ultimate        | [2b9b1f909c](https://linux-hardware.org/?probe=2b9b1f909c) | Nov 05, 2023 |
| ASUSTek       | PRIME Z370-P II             | [701314a2ff](https://linux-hardware.org/?probe=701314a2ff) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [119816ea7d](https://linux-hardware.org/?probe=119816ea7d) | Nov 04, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [6d39c4f814](https://linux-hardware.org/?probe=6d39c4f814) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [e928da88d7](https://linux-hardware.org/?probe=e928da88d7) | Nov 03, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [72a2946c83](https://linux-hardware.org/?probe=72a2946c83) | Nov 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [8161abddda](https://linux-hardware.org/?probe=8161abddda) | Nov 01, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | [5b82a04d09](https://linux-hardware.org/?probe=5b82a04d09) | Oct 31, 2023 |
| ASRock        | B450M-HDV R4.0              | [d9da25aaae](https://linux-hardware.org/?probe=d9da25aaae) | Oct 31, 2023 |
| ASUSTek       | P8H77-M                     | [d40277c6b4](https://linux-hardware.org/?probe=d40277c6b4) | Oct 30, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [9dad78d2eb](https://linux-hardware.org/?probe=9dad78d2eb) | Oct 27, 2023 |
| Gigabyte      | Z77-D3H                     | [2355d71878](https://linux-hardware.org/?probe=2355d71878) | Oct 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [38cbc0d5d7](https://linux-hardware.org/?probe=38cbc0d5d7) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [29adbcb90f](https://linux-hardware.org/?probe=29adbcb90f) | Oct 24, 2023 |
| Gigabyte      | H77-D3H                     | [2c786f10b7](https://linux-hardware.org/?probe=2c786f10b7) | Oct 22, 2023 |
| Gigabyte      | H77-D3H                     | [7b1e876aef](https://linux-hardware.org/?probe=7b1e876aef) | Oct 22, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | [72d780f5f7](https://linux-hardware.org/?probe=72d780f5f7) | Oct 22, 2023 |
| MSI           | Z170A PC MATE               | [2f2798b05c](https://linux-hardware.org/?probe=2f2798b05c) | Oct 22, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [4a7b98d45e](https://linux-hardware.org/?probe=4a7b98d45e) | Oct 18, 2023 |
| MSI           | B350 PC MATE                | [a4661384e1](https://linux-hardware.org/?probe=a4661384e1) | Oct 17, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [fb2bf1baa8](https://linux-hardware.org/?probe=fb2bf1baa8) | Oct 16, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a116875c3f](https://linux-hardware.org/?probe=a116875c3f) | Oct 15, 2023 |
| Pegatron      | 2AB6                        | [9f5a8c985a](https://linux-hardware.org/?probe=9f5a8c985a) | Oct 15, 2023 |
| Pegatron      | 2AB6                        | [6f3a56878d](https://linux-hardware.org/?probe=6f3a56878d) | Oct 15, 2023 |
| ASRock        | X670E PG Lightning          | [d2e0e9fc07](https://linux-hardware.org/?probe=d2e0e9fc07) | Oct 14, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [dc82ec9351](https://linux-hardware.org/?probe=dc82ec9351) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [15d9d16ec9](https://linux-hardware.org/?probe=15d9d16ec9) | Oct 09, 2023 |
| Biostar       | A320MH                      | [9623471fc7](https://linux-hardware.org/?probe=9623471fc7) | Oct 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | [06f03211a6](https://linux-hardware.org/?probe=06f03211a6) | Oct 06, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | [811561ec05](https://linux-hardware.org/?probe=811561ec05) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d3e6e2aa83](https://linux-hardware.org/?probe=d3e6e2aa83) | Oct 03, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [78c54897a1](https://linux-hardware.org/?probe=78c54897a1) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [288f5f8266](https://linux-hardware.org/?probe=288f5f8266) | Sep 30, 2023 |
| Pegatron      | 2AB6                        | [4bb43a39c1](https://linux-hardware.org/?probe=4bb43a39c1) | Sep 29, 2023 |
| HP            | 8906 SMVB                   | [55c34c64a6](https://linux-hardware.org/?probe=55c34c64a6) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [c33d31195f](https://linux-hardware.org/?probe=c33d31195f) | Sep 26, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [5043f41a8d](https://linux-hardware.org/?probe=5043f41a8d) | Sep 20, 2023 |
| AZW           | GTR V02                     | [2d4817f092](https://linux-hardware.org/?probe=2d4817f092) | Sep 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [27763442c0](https://linux-hardware.org/?probe=27763442c0) | Sep 16, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [52f0ac41db](https://linux-hardware.org/?probe=52f0ac41db) | Sep 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [caf0257156](https://linux-hardware.org/?probe=caf0257156) | Sep 13, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [b9f46a8a9b](https://linux-hardware.org/?probe=b9f46a8a9b) | Sep 12, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [f818765b79](https://linux-hardware.org/?probe=f818765b79) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3857377d7a](https://linux-hardware.org/?probe=3857377d7a) | Sep 09, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [6521407977](https://linux-hardware.org/?probe=6521407977) | Sep 06, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [b395463f0e](https://linux-hardware.org/?probe=b395463f0e) | Sep 06, 2023 |
| Gigabyte      | B550M K                     | [95d0f9505b](https://linux-hardware.org/?probe=95d0f9505b) | Sep 03, 2023 |
| MSI           | PRO X670-P WIFI             | [174cff0e19](https://linux-hardware.org/?probe=174cff0e19) | Sep 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [07a44c323f](https://linux-hardware.org/?probe=07a44c323f) | Sep 01, 2023 |
| Pegatron      | 2AB6                        | [a0649549b3](https://linux-hardware.org/?probe=a0649549b3) | Sep 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c865cde7a2](https://linux-hardware.org/?probe=c865cde7a2) | Sep 01, 2023 |
| ASRock        | Z490M Pro4                  | [e07d4a9c90](https://linux-hardware.org/?probe=e07d4a9c90) | Aug 30, 2023 |
| MSI           | Z170A GAMING M3             | [cdbff2ba81](https://linux-hardware.org/?probe=cdbff2ba81) | Aug 28, 2023 |
| Gigabyte      | H410M H                     | [a4fe691c36](https://linux-hardware.org/?probe=a4fe691c36) | Aug 28, 2023 |
| ASRock        | B650 PG Lightning           | [de1d12ec95](https://linux-hardware.org/?probe=de1d12ec95) | Aug 24, 2023 |
| Gigabyte      | H310M H x.x                 | [523acf034e](https://linux-hardware.org/?probe=523acf034e) | Aug 23, 2023 |
| MSI           | PRO X670-P WIFI             | [0887b2e549](https://linux-hardware.org/?probe=0887b2e549) | Aug 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [f7d3395ffc](https://linux-hardware.org/?probe=f7d3395ffc) | Aug 18, 2023 |
| ASUSTek       | Pro B550M-C                 | [712bd65558](https://linux-hardware.org/?probe=712bd65558) | Aug 16, 2023 |
| Pegatron      | Benicia                     | [0ab394fa9e](https://linux-hardware.org/?probe=0ab394fa9e) | Aug 15, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [e9b2347b46](https://linux-hardware.org/?probe=e9b2347b46) | Aug 14, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | [f4d0fd6811](https://linux-hardware.org/?probe=f4d0fd6811) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | [a5681e12d3](https://linux-hardware.org/?probe=a5681e12d3) | Aug 12, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [f016fa3756](https://linux-hardware.org/?probe=f016fa3756) | Aug 11, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [d490bb32ec](https://linux-hardware.org/?probe=d490bb32ec) | Aug 10, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [fffee60e72](https://linux-hardware.org/?probe=fffee60e72) | Aug 10, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [d9c999ffa3](https://linux-hardware.org/?probe=d9c999ffa3) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [f7c7290847](https://linux-hardware.org/?probe=f7c7290847) | Aug 08, 2023 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [9a0fa703d7](https://linux-hardware.org/?probe=9a0fa703d7) | Aug 07, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [ec7fa20ab4](https://linux-hardware.org/?probe=ec7fa20ab4) | Aug 06, 2023 |
| ASRock        | B550M Steel Legend          | [d9107b9cb9](https://linux-hardware.org/?probe=d9107b9cb9) | Aug 06, 2023 |
| MSI           | FM2-A55M-E33                | [28384fb38c](https://linux-hardware.org/?probe=28384fb38c) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | [5ec7de1222](https://linux-hardware.org/?probe=5ec7de1222) | Aug 06, 2023 |
| MSI           | PRO X670-P WIFI             | [cd0d64a16a](https://linux-hardware.org/?probe=cd0d64a16a) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [53c9161fc5](https://linux-hardware.org/?probe=53c9161fc5) | Aug 03, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | [18dad15a33](https://linux-hardware.org/?probe=18dad15a33) | Aug 02, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [ceb7e754a1](https://linux-hardware.org/?probe=ceb7e754a1) | Aug 02, 2023 |
| ASRock        | Z170 Extreme6+              | [84c1a14a56](https://linux-hardware.org/?probe=84c1a14a56) | Aug 01, 2023 |
| Gigabyte      | B75M-D3H                    | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| NZXT          | N7 B650E                    | [38e481c3d5](https://linux-hardware.org/?probe=38e481c3d5) | Jul 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [513ac15990](https://linux-hardware.org/?probe=513ac15990) | Jul 28, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [c9c42e4857](https://linux-hardware.org/?probe=c9c42e4857) | Jul 26, 2023 |
| ASUSTek       | X99-DELUXE II               | [35f41c1327](https://linux-hardware.org/?probe=35f41c1327) | Jul 25, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [567693892b](https://linux-hardware.org/?probe=567693892b) | Jul 23, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [228ded2955](https://linux-hardware.org/?probe=228ded2955) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [5f9962eafc](https://linux-hardware.org/?probe=5f9962eafc) | Jul 21, 2023 |
| MSI           | B450M PRO-M2 V2             | [2109b6ace6](https://linux-hardware.org/?probe=2109b6ace6) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [022d677eda](https://linux-hardware.org/?probe=022d677eda) | Jul 21, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | [25311760a9](https://linux-hardware.org/?probe=25311760a9) | Jul 21, 2023 |
| ASRock        | Z170 Extreme6+              | [5ead4ab228](https://linux-hardware.org/?probe=5ead4ab228) | Jul 17, 2023 |
| HP            | 8906 SMVB                   | [70b7e2a7f5](https://linux-hardware.org/?probe=70b7e2a7f5) | Jul 16, 2023 |
| ASRock        | H370 Performance            | [43286f18d3](https://linux-hardware.org/?probe=43286f18d3) | Jul 16, 2023 |
| HP            | 3396                        | [5713dca497](https://linux-hardware.org/?probe=5713dca497) | Jul 15, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [d8550d27e3](https://linux-hardware.org/?probe=d8550d27e3) | Jul 15, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [7026c5b007](https://linux-hardware.org/?probe=7026c5b007) | Jul 14, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [8e3cc576fd](https://linux-hardware.org/?probe=8e3cc576fd) | Jul 14, 2023 |
| MSI           | PRO Z690-A WIFI             | [d20f9ee7a7](https://linux-hardware.org/?probe=d20f9ee7a7) | Jul 14, 2023 |
| MSI           | Z87-G45 GAMING              | [110a53c220](https://linux-hardware.org/?probe=110a53c220) | Jul 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [e612d95542](https://linux-hardware.org/?probe=e612d95542) | Jul 12, 2023 |
| Unknown       | EA A520M-E                  | [184201d556](https://linux-hardware.org/?probe=184201d556) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [0e411803b2](https://linux-hardware.org/?probe=0e411803b2) | Jul 10, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [429e4e7636](https://linux-hardware.org/?probe=429e4e7636) | Jul 10, 2023 |
| Acer          | Nitro N50-620               | [8286ddb9ae](https://linux-hardware.org/?probe=8286ddb9ae) | Jul 08, 2023 |
| Shenzhen M... | F6BFC                       | [f4f1e6f9ff](https://linux-hardware.org/?probe=f4f1e6f9ff) | Jul 05, 2023 |
| GPD           | G1618-03                    | [0cb58087bf](https://linux-hardware.org/?probe=0cb58087bf) | Jul 04, 2023 |
| Gigabyte      | B550M DS3H AC               | [626416c230](https://linux-hardware.org/?probe=626416c230) | Jul 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ff0f73c325](https://linux-hardware.org/?probe=ff0f73c325) | Jul 02, 2023 |
| Gigabyte      | X670 GAMING X AX            | [e7e4a3562f](https://linux-hardware.org/?probe=e7e4a3562f) | Jul 02, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [488ebd160a](https://linux-hardware.org/?probe=488ebd160a) | Jul 02, 2023 |
| ASRock        | X299 Taichi CLX             | [ff1f31ff36](https://linux-hardware.org/?probe=ff1f31ff36) | Jul 01, 2023 |
| ASRock        | X299 Taichi CLX             | [d4362fb3ca](https://linux-hardware.org/?probe=d4362fb3ca) | Jul 01, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | [c93f4f0d0b](https://linux-hardware.org/?probe=c93f4f0d0b) | Jun 30, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5b780b9ebd](https://linux-hardware.org/?probe=5b780b9ebd) | Jun 24, 2023 |
| ASRock        | B85M Pro4                   | [0ee3f7532c](https://linux-hardware.org/?probe=0ee3f7532c) | Jun 23, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [379c36642b](https://linux-hardware.org/?probe=379c36642b) | Jun 22, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | [2656caf6b8](https://linux-hardware.org/?probe=2656caf6b8) | Jun 22, 2023 |
| MSI           | H81M-E34                    | [ac0a9c170f](https://linux-hardware.org/?probe=ac0a9c170f) | Jun 22, 2023 |
| MSI           | H81M-E34                    | [666f5d0ce5](https://linux-hardware.org/?probe=666f5d0ce5) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| ASRock        | Z370 Gaming-ITX/ac          | [e05a90c6c5](https://linux-hardware.org/?probe=e05a90c6c5) | Jun 16, 2023 |
| HP            | 8054                        | [97a4b34236](https://linux-hardware.org/?probe=97a4b34236) | Jun 15, 2023 |
| ASRock        | X470 Master SLI             | [448a3cf6b1](https://linux-hardware.org/?probe=448a3cf6b1) | Jun 15, 2023 |
| ASRock        | B650E Steel Legend WiFi     | [3edca35793](https://linux-hardware.org/?probe=3edca35793) | Jun 14, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | [6febc3ef2e](https://linux-hardware.org/?probe=6febc3ef2e) | Jun 13, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [6491127e6e](https://linux-hardware.org/?probe=6491127e6e) | Jun 09, 2023 |
| ASRock        | B450 Steel Legend           | [483ac7223f](https://linux-hardware.org/?probe=483ac7223f) | Jun 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [12736be80e](https://linux-hardware.org/?probe=12736be80e) | Jun 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [bc00b26e0a](https://linux-hardware.org/?probe=bc00b26e0a) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ee25039289](https://linux-hardware.org/?probe=ee25039289) | Jun 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| Gigabyte      | X570 AORUS PRO              | [efa9cac1df](https://linux-hardware.org/?probe=efa9cac1df) | Jun 04, 2023 |
| ASRock        | FM2A68M-DG3+                | [3e7ad22b6b](https://linux-hardware.org/?probe=3e7ad22b6b) | Jun 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| ASRock        | B650E Steel Legend WiFi     | [88d16bf040](https://linux-hardware.org/?probe=88d16bf040) | May 31, 2023 |
| Dell          | 0J3C2F A02                  | [c2640c22ff](https://linux-hardware.org/?probe=c2640c22ff) | May 27, 2023 |
| HP            | 1497                        | [94f79f2f74](https://linux-hardware.org/?probe=94f79f2f74) | May 27, 2023 |
| HP            | 1497                        | [d2cca6c2a1](https://linux-hardware.org/?probe=d2cca6c2a1) | May 27, 2023 |
| Shenzhen M... | F7BFC                       | [6bf848e58f](https://linux-hardware.org/?probe=6bf848e58f) | May 25, 2023 |
| AOpen         | iBDWMUx-MD R1.04            | [cc674d2878](https://linux-hardware.org/?probe=cc674d2878) | May 25, 2023 |
| ASRock        | AB350M Pro4                 | [1efd2eb268](https://linux-hardware.org/?probe=1efd2eb268) | May 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | [c43cfd04ad](https://linux-hardware.org/?probe=c43cfd04ad) | May 24, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [0d3bc48240](https://linux-hardware.org/?probe=0d3bc48240) | May 23, 2023 |
| ASRock        | B650E Steel Legend WiFi     | [b034244bec](https://linux-hardware.org/?probe=b034244bec) | May 20, 2023 |
| langchao      | IPM41-D3                    | [2f659faa92](https://linux-hardware.org/?probe=2f659faa92) | May 20, 2023 |
| MSI           | PRO Z690-A DDR4             | [758f0dbd4b](https://linux-hardware.org/?probe=758f0dbd4b) | May 19, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [ca0ae58640](https://linux-hardware.org/?probe=ca0ae58640) | May 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [fee6b2f55b](https://linux-hardware.org/?probe=fee6b2f55b) | May 17, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [dc2f3b9cdc](https://linux-hardware.org/?probe=dc2f3b9cdc) | May 17, 2023 |
| ASRock        | Z97 Pro3                    | [f8be8d5d2c](https://linux-hardware.org/?probe=f8be8d5d2c) | May 16, 2023 |
| ASRock        | Z97 Pro3                    | [34b2fb40b9](https://linux-hardware.org/?probe=34b2fb40b9) | May 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [bd6f8927b4](https://linux-hardware.org/?probe=bd6f8927b4) | May 12, 2023 |
| ASUSTek       | B85-PLUS                    | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| MSI           | PRO Z690-A DDR4             | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| ASUSTek       | P8B75-M LE                  | [2b0bc04757](https://linux-hardware.org/?probe=2b0bc04757) | May 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [ebe0f52831](https://linux-hardware.org/?probe=ebe0f52831) | May 10, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [aa31c3dd8f](https://linux-hardware.org/?probe=aa31c3dd8f) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [dc1db599ea](https://linux-hardware.org/?probe=dc1db599ea) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [e2ce1c3d6c](https://linux-hardware.org/?probe=e2ce1c3d6c) | May 07, 2023 |
| Gigabyte      | P43-ES3G                    | [1095d1ef7f](https://linux-hardware.org/?probe=1095d1ef7f) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [de65a79bf1](https://linux-hardware.org/?probe=de65a79bf1) | May 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [4b76463d57](https://linux-hardware.org/?probe=4b76463d57) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [b0a2a0b536](https://linux-hardware.org/?probe=b0a2a0b536) | May 06, 2023 |
| ASUSTek       | B85-PLUS                    | [352e8b2616](https://linux-hardware.org/?probe=352e8b2616) | May 03, 2023 |
| MSI           | B450 GAMING PLUS            | [017222d810](https://linux-hardware.org/?probe=017222d810) | May 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [62d194e85e](https://linux-hardware.org/?probe=62d194e85e) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [e2acacabb3](https://linux-hardware.org/?probe=e2acacabb3) | Apr 30, 2023 |
| MSI           | B450 GAMING PLUS            | [8aa973e0f5](https://linux-hardware.org/?probe=8aa973e0f5) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | [9419686ec7](https://linux-hardware.org/?probe=9419686ec7) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | [1f61fda034](https://linux-hardware.org/?probe=1f61fda034) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [b2616ea409](https://linux-hardware.org/?probe=b2616ea409) | Apr 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [169e095fab](https://linux-hardware.org/?probe=169e095fab) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c80b811f3e](https://linux-hardware.org/?probe=c80b811f3e) | Apr 27, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [072b88204c](https://linux-hardware.org/?probe=072b88204c) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [f02e8339e9](https://linux-hardware.org/?probe=f02e8339e9) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [8de5e39740](https://linux-hardware.org/?probe=8de5e39740) | Apr 25, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e4064abe78](https://linux-hardware.org/?probe=e4064abe78) | Apr 24, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [8db6f88fd3](https://linux-hardware.org/?probe=8db6f88fd3) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [47831c9091](https://linux-hardware.org/?probe=47831c9091) | Apr 18, 2023 |
| Gigabyte      | B150M-D3H-CF                | [c248c05349](https://linux-hardware.org/?probe=c248c05349) | Apr 18, 2023 |
| MSI           | Z87M GAMING                 | [9552ef2174](https://linux-hardware.org/?probe=9552ef2174) | Apr 17, 2023 |
| HP            | 18E7                        | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d40208e7f6](https://linux-hardware.org/?probe=d40208e7f6) | Apr 17, 2023 |
| Protectli     | FW6 Ver                     | [7371569bbf](https://linux-hardware.org/?probe=7371569bbf) | Apr 15, 2023 |
| Dell          | 0KWVT8 A00                  | [d1084f0d90](https://linux-hardware.org/?probe=d1084f0d90) | Apr 15, 2023 |
| ASUSTek       | A68HM-K                     | [6419c7fb77](https://linux-hardware.org/?probe=6419c7fb77) | Apr 15, 2023 |
| Protectli     | FW6 Ver                     | [26db4eab1f](https://linux-hardware.org/?probe=26db4eab1f) | Apr 15, 2023 |
| MSI           | B450 GAMING PLUS            | [d49b1775be](https://linux-hardware.org/?probe=d49b1775be) | Apr 14, 2023 |
| Dell          | 0XR1GT A00                  | [1c8d776510](https://linux-hardware.org/?probe=1c8d776510) | Apr 13, 2023 |
| Dell          | 0XR1GT A00                  | [06e6f2f745](https://linux-hardware.org/?probe=06e6f2f745) | Apr 13, 2023 |
| Dell          | 0KWVT8 A00                  | [4cea64e81b](https://linux-hardware.org/?probe=4cea64e81b) | Apr 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | [3e3a141713](https://linux-hardware.org/?probe=3e3a141713) | Apr 11, 2023 |
| HP            | 805F                        | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| HP            | 805F                        | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS            | [b35b8e1503](https://linux-hardware.org/?probe=b35b8e1503) | Apr 09, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [5a044a37f7](https://linux-hardware.org/?probe=5a044a37f7) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | [81a8d7a1fc](https://linux-hardware.org/?probe=81a8d7a1fc) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [c599e701fc](https://linux-hardware.org/?probe=c599e701fc) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [aa3b0a7d6f](https://linux-hardware.org/?probe=aa3b0a7d6f) | Apr 04, 2023 |
| MSI           | B450 GAMING PLUS            | [731bd99503](https://linux-hardware.org/?probe=731bd99503) | Apr 03, 2023 |
| Gigabyte      | Z77P-D3                     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS            | [539137fb36](https://linux-hardware.org/?probe=539137fb36) | Apr 01, 2023 |
| ASUSTek       | B85M-G R2.0                 | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| Intel         | X79                         | [c06125262b](https://linux-hardware.org/?probe=c06125262b) | Mar 31, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASRock        | X470 Master SLI             | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASUSTek       | M3N78 PRO                   | [0f9abe9400](https://linux-hardware.org/?probe=0f9abe9400) | Mar 28, 2023 |
| MSI           | B450 GAMING PLUS            | [5242d56a0f](https://linux-hardware.org/?probe=5242d56a0f) | Mar 27, 2023 |
| MSI           | B550-A PRO                  | [ebb59fa31d](https://linux-hardware.org/?probe=ebb59fa31d) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [b084807397](https://linux-hardware.org/?probe=b084807397) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bc38c5ed22](https://linux-hardware.org/?probe=bc38c5ed22) | Mar 26, 2023 |
| ASUSTek       | PRIME B450M-A               | [6601de8aae](https://linux-hardware.org/?probe=6601de8aae) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9240540b33](https://linux-hardware.org/?probe=9240540b33) | Mar 24, 2023 |
| Gigabyte      | GA-970A-DS3                 | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| ASRock        | B660M-ITX/ac                | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| Dell          | 0XR1GT A00                  | [0912041935](https://linux-hardware.org/?probe=0912041935) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | [61e1c5eff9](https://linux-hardware.org/?probe=61e1c5eff9) | Mar 21, 2023 |
| ASRock        | X670E Steel Legend          | [7891e82ac4](https://linux-hardware.org/?probe=7891e82ac4) | Mar 17, 2023 |
| ASUSTek       | PRIME X370-PRO              | [ab4a88037a](https://linux-hardware.org/?probe=ab4a88037a) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | [23e21d1440](https://linux-hardware.org/?probe=23e21d1440) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| Intel         | DB85FL AAG89861-203         | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| MSI           | X470 GAMING PLUS            | [727390b14d](https://linux-hardware.org/?probe=727390b14d) | Mar 14, 2023 |
| ASRock        | X670E Steel Legend          | [0eefdece9c](https://linux-hardware.org/?probe=0eefdece9c) | Mar 13, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [7320131972](https://linux-hardware.org/?probe=7320131972) | Mar 13, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [1ad75bea9c](https://linux-hardware.org/?probe=1ad75bea9c) | Mar 12, 2023 |
| ASRock        | X670E Steel Legend          | [3ec784f6be](https://linux-hardware.org/?probe=3ec784f6be) | Mar 11, 2023 |
| ASUSTek       | PRIME B450M-A               | [7ba7da9138](https://linux-hardware.org/?probe=7ba7da9138) | Mar 10, 2023 |
| MSI           | B450 GAMING PLUS            | [46b213149e](https://linux-hardware.org/?probe=46b213149e) | Mar 10, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| Dell          | 0773VG A01                  | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| ASRock        | H310M-HDV                   | [316510fe69](https://linux-hardware.org/?probe=316510fe69) | Mar 07, 2023 |
| Acer          | Aspire X1400                | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [21db48a23b](https://linux-hardware.org/?probe=21db48a23b) | Mar 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4eb7bea837](https://linux-hardware.org/?probe=4eb7bea837) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1d24df340b](https://linux-hardware.org/?probe=1d24df340b) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [950e36afc7](https://linux-hardware.org/?probe=950e36afc7) | Mar 03, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [15318beac5](https://linux-hardware.org/?probe=15318beac5) | Feb 27, 2023 |
| MSI           | Z170A-G45 GAMING            | [a5496030e7](https://linux-hardware.org/?probe=a5496030e7) | Feb 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| ASUSTek       | P8Z77-M PRO                 | [92f1f7d3b5](https://linux-hardware.org/?probe=92f1f7d3b5) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [101d8d4577](https://linux-hardware.org/?probe=101d8d4577) | Feb 25, 2023 |
| ASUSTek       | H97M-E                      | [b2ef9d5ede](https://linux-hardware.org/?probe=b2ef9d5ede) | Feb 21, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [2752a9660a](https://linux-hardware.org/?probe=2752a9660a) | Feb 19, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| MSI           | B550-A PRO                  | [e81d0741bb](https://linux-hardware.org/?probe=e81d0741bb) | Feb 17, 2023 |
| MSI           | B550-A PRO                  | [dd63e968bd](https://linux-hardware.org/?probe=dd63e968bd) | Feb 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | [e486b2bb46](https://linux-hardware.org/?probe=e486b2bb46) | Feb 15, 2023 |
| Dell          | 0KWVT8 A02                  | [486f7258a6](https://linux-hardware.org/?probe=486f7258a6) | Feb 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [dc91c0e32b](https://linux-hardware.org/?probe=dc91c0e32b) | Feb 14, 2023 |
| Dell          | 0KWVT8 A02                  | [c3d08b4f2e](https://linux-hardware.org/?probe=c3d08b4f2e) | Feb 13, 2023 |
| ASRock        | B650M PG Riptide            | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| ASUSTek       | PRIME X570-P                | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| MSI           | PRO Z690-A DDR4             | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | [fdaab67fe9](https://linux-hardware.org/?probe=fdaab67fe9) | Feb 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| MSI           | PRO Z690-A DDR4             | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| HP            | 834F                        | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| HP            | 8054                        | [36f5306e37](https://linux-hardware.org/?probe=36f5306e37) | Jan 30, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [95f5d0904e](https://linux-hardware.org/?probe=95f5d0904e) | Jan 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| MSI           | B450 GAMING PLUS            | [bc95b86800](https://linux-hardware.org/?probe=bc95b86800) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3eb7e4f3cf](https://linux-hardware.org/?probe=3eb7e4f3cf) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Gigabyte      | B450 AORUS M                | [4d52b408c2](https://linux-hardware.org/?probe=4d52b408c2) | Jan 19, 2023 |
| MSI           | GF615M-P33                  | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| ASUSTek       | PRIME Z370-A                | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| HP            | 8054                        | [d4398dee29](https://linux-hardware.org/?probe=d4398dee29) | Jan 08, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c74a6daaaa](https://linux-hardware.org/?probe=c74a6daaaa) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| HP            | 1497                        | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASRock        | H77M-ITX                    | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [569f5cd751](https://linux-hardware.org/?probe=569f5cd751) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| ASUSTek       | G20AJ                       | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b6bf9d074f](https://linux-hardware.org/?probe=b6bf9d074f) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [6c40dc7dd6](https://linux-hardware.org/?probe=6c40dc7dd6) | Jan 03, 2023 |
| ASUSTek       | M5A88-M                     | [dc7201711c](https://linux-hardware.org/?probe=dc7201711c) | Dec 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [4ca2070d42](https://linux-hardware.org/?probe=4ca2070d42) | Dec 29, 2022 |
| ASUSTek       | PRIME Z270-P                | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| HP            | 1589                        | [4769414712](https://linux-hardware.org/?probe=4769414712) | Dec 24, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [353cbeb5c8](https://linux-hardware.org/?probe=353cbeb5c8) | Dec 19, 2022 |
| Biostar       | X470GTN                     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| ASUSTek       | M5A88-M                     | [3bc811ef2a](https://linux-hardware.org/?probe=3bc811ef2a) | Dec 17, 2022 |
| HP            | 2ABD A01                    | [c5c5c07485](https://linux-hardware.org/?probe=c5c5c07485) | Dec 16, 2022 |
| HP            | 2ABD A01                    | [c992b15fbe](https://linux-hardware.org/?probe=c992b15fbe) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASRock        | H310M-HDV/M.2               | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| ASUSTek       | M5A88-M                     | [4378eff64f](https://linux-hardware.org/?probe=4378eff64f) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| Gigabyte      | H81M-H                      | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| Dell          | 0215PR A02                  | [b9d16b98d2](https://linux-hardware.org/?probe=b9d16b98d2) | Dec 09, 2022 |
| Gigabyte      | Z590I VISION D              | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | [d7b2726838](https://linux-hardware.org/?probe=d7b2726838) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | [f5bd8a0e5b](https://linux-hardware.org/?probe=f5bd8a0e5b) | Dec 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [a742429421](https://linux-hardware.org/?probe=a742429421) | Dec 06, 2022 |
| ASUSTek       | M5A88-M                     | [69ed3a0345](https://linux-hardware.org/?probe=69ed3a0345) | Dec 02, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel         | X79G V2.x                   | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Gigabyte      | H410M H V3                  | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock        | B550 Extreme4               | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Gigabyte      | H310M M.2 x.x               | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| Alienware     | 0PGRP5 A01                  | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI           | MEG X570 UNIFY              | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| ASRock        | N68C-GS4 FX                 | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell          | 042P49 A02                  | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| ECS           | H61H2-CM                    | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASRock        | Z77 Pro4                    | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP            | 8653 A                      | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| Dell          | 09KPNV A00                  | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel         | B75                         | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP            | 3029h                       | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| MSI           | Z87 XPOWER                  | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell          | 0F6X5P A00                  | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| MSI           | PRO Z690-A DDR4             | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| HP            | 1998                        | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock        | B450M Steel Legend          | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| ASUSTek       | H61M-K                      | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell          | 0M5DCD A00                  | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| MSI           | MEG X570 UNIFY              | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock        | X470 Master SLI             | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| Gigabyte      | H270-Gaming 3               | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel         | B75                         | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek       | PRIME H410M-A               | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| MSI           | 970 GAMING                  | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell          | 0G785M A00                  | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gigabyte      | EP45-UD3L                   | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP            | 8594                        | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte      | EP45-UD3L                   | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock        | X470 Master SLI             | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Dell          | 0G785M A00                  | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| Unknown       | T3 MRD                      | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar       | H410MH S2                   | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo        | MAHOBAY NOK                 | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| Gigabyte      | H110M-H-CF                  | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware     | 01NYPT A00                  | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| ASRock        | B560 Steel Legend           | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek       | P8Z68-V PRO                 | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock        | H61M-VG3                    | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| ASUSTek       | B85M-E                      | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| ASRock        | X470 Master SLI             | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock        | Z97 Extreme6                | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock        | 760GM-HDV                   | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP            | 8906 SMVB                   | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP            | 8054                        | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek       | G20AJ                       | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI           | B450-A PRO MAX              | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| MSI           | X570-A PRO                  | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| MSI           | 970 GAMING                  | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell          | 0J8H4R A01                  | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines     | EL1870                      | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Nobara/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Nobara 37 | 133      | 30.5%   |
| Nobara 36 | 131      | 30.05%  |
| Nobara 38 | 126      | 28.9%   |
| Nobara 39 | 46       | 10.55%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Nobara | 426      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Desktops | Percent |
|-------------------------------|----------|---------|
| 6.4.10-202.fsync.fc38.x86_64  | 32       | 6.69%   |
| 6.0.14-201.fsync.fc36.x86_64  | 24       | 5.02%   |
| 6.2.14-300.fsync.fc37.x86_64  | 21       | 4.39%   |
| 6.1.14-201.fsync.fc37.x86_64  | 16       | 3.35%   |
| 6.0.10-201.fc36.x86_64        | 16       | 3.35%   |
| 6.3.12-204.fsync.fc38.x86_64  | 15       | 3.14%   |
| 6.7.0-204.fsync.fc39.x86_64   | 13       | 2.72%   |
| 6.6.9-200.fsync.fc39.x86_64   | 12       | 2.51%   |
| 6.2.12-200.fsync.fc37.x86_64  | 12       | 2.51%   |
| 6.6.7-203.fsync.fc38.x86_64   | 10       | 2.09%   |
| 6.2.6-201.fsync.fc37.x86_64   | 10       | 2.09%   |
| 6.5.9-201.fsync.fc38.x86_64   | 9        | 1.88%   |
| 5.19.14-201.fsync.fc36.x86_64 | 9        | 1.88%   |
| 6.7.0-201.fsync.fc39.x86_64   | 8        | 1.67%   |
| 6.5.6-200.fsync.fc38.x86_64   | 8        | 1.67%   |
| 6.2.8-200.fsync.fc37.x86_64   | 8        | 1.67%   |
| 6.2.10-200.fsync.fc37.x86_64  | 8        | 1.67%   |
| 6.1.9-200.fsync.fc37.x86_64   | 8        | 1.67%   |
| 5.19.9-201.fsync.fc36.x86_64  | 8        | 1.67%   |
| 5.19.7-204.fsync.fc36.x86_64  | 8        | 1.67%   |
| 5.19.16-201.fsync.fc36.x86_64 | 8        | 1.67%   |
| 6.3.7-200.fsync.fc37.x86_64   | 7        | 1.46%   |
| 6.3.12-205.fsync.fc38.x86_64  | 7        | 1.46%   |
| 6.3.10-200.fsync.fc38.x86_64  | 7        | 1.46%   |
| 6.1.6-203.fsync.fc37.x86_64   | 7        | 1.46%   |
| 6.1.4-203.fsync.fc37.x86_64   | 7        | 1.46%   |
| 6.1.11-201.fsync.fc37.x86_64  | 7        | 1.46%   |
| 5.18.13-201.fsync.fc36.x86_64 | 7        | 1.46%   |
| 6.6.8-200.fsync.fc39.x86_64   | 6        | 1.26%   |
| 6.2.11-202.fsync.fc37.x86_64  | 6        | 1.26%   |
| 6.0.9-201.fc36.x86_64         | 6        | 1.26%   |
| 6.0.7-201.fsync.fc36.x86_64   | 6        | 1.26%   |
| 6.0.5-201.fsync.fc36.x86_64   | 6        | 1.26%   |
| 5.19.10-201.fsync.fc36.x86_64 | 6        | 1.26%   |
| 6.6.7-203.fsync.fc39.x86_64   | 5        | 1.05%   |
| 6.6.2-201.fsync.fc38.x86_64   | 5        | 1.05%   |
| 6.5.3-200.fsync.fc37.x86_64   | 5        | 1.05%   |
| 6.3.12-203.fsync.fc38.x86_64  | 5        | 1.05%   |
| 6.5.9-200.fsync.fc38.x86_64   | 4        | 0.84%   |
| 6.5.5-201.fsync.fc38.x86_64   | 4        | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.4.10  | 35       | 7.35%   |
| 6.3.12  | 31       | 6.51%   |
| 6.7.0   | 25       | 5.25%   |
| 6.0.14  | 24       | 5.04%   |
| 6.2.14  | 21       | 4.41%   |
| 6.6.7   | 19       | 3.99%   |
| 6.1.14  | 16       | 3.36%   |
| 6.0.10  | 16       | 3.36%   |
| 6.6.9   | 12       | 2.52%   |
| 6.5.9   | 12       | 2.52%   |
| 6.2.12  | 12       | 2.52%   |
| 6.2.6   | 10       | 2.1%    |
| 6.3.10  | 9        | 1.89%   |
| 6.1.6   | 9        | 1.89%   |
| 5.19.7  | 9        | 1.89%   |
| 5.19.14 | 9        | 1.89%   |
| 6.5.6   | 8        | 1.68%   |
| 6.2.8   | 8        | 1.68%   |
| 6.2.11  | 8        | 1.68%   |
| 6.2.10  | 8        | 1.68%   |
| 6.1.9   | 8        | 1.68%   |
| 6.0.7   | 8        | 1.68%   |
| 5.19.9  | 8        | 1.68%   |
| 5.19.16 | 8        | 1.68%   |
| 6.5.3   | 7        | 1.47%   |
| 6.3.7   | 7        | 1.47%   |
| 6.1.4   | 7        | 1.47%   |
| 6.1.11  | 7        | 1.47%   |
| 5.18.13 | 7        | 1.47%   |
| 6.6.8   | 6        | 1.26%   |
| 6.1.8   | 6        | 1.26%   |
| 6.0.9   | 6        | 1.26%   |
| 6.0.5   | 6        | 1.26%   |
| 5.19.10 | 6        | 1.26%   |
| 6.6.4   | 5        | 1.05%   |
| 6.6.2   | 5        | 1.05%   |
| 6.5.5   | 5        | 1.05%   |
| 6.6.3   | 4        | 0.84%   |
| 6.5.11  | 4        | 0.84%   |
| 6.4.8   | 4        | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 64       | 13.85%  |
| 6.0     | 64       | 13.85%  |
| 5.19    | 56       | 12.12%  |
| 6.1     | 53       | 11.47%  |
| 6.3     | 52       | 11.26%  |
| 6.6     | 50       | 10.82%  |
| 6.4     | 40       | 8.66%   |
| 6.5     | 35       | 7.58%   |
| 6.7     | 25       | 5.41%   |
| 5.18    | 23       | 4.98%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 426      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 268      | 62.18%  |
| KDE5          | 157      | 36.43%  |
| GNOME Classic | 2        | 0.46%   |
| Unknown       | 2        | 0.46%   |
| X-Cinnamon    | 1        | 0.23%   |
| sway          | 1        | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 337      | 77.12%  |
| X11     | 98       | 22.43%  |
| Unknown | 2        | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 358      | 83.64%  |
| GDM     | 42       | 9.81%   |
| SDDM    | 26       | 6.07%   |
| LightDM | 2        | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 216      | 50.59%  |
| de_DE   | 44       | 10.3%   |
| en_GB   | 38       | 8.9%    |
| en_CA   | 15       | 3.51%   |
| es_ES   | 13       | 3.04%   |
| es_MX   | 12       | 2.81%   |
| fr_FR   | 11       | 2.58%   |
| ru_RU   | 10       | 2.34%   |
| es_AR   | 8        | 1.87%   |
| pt_BR   | 7        | 1.64%   |
| de_AT   | 6        | 1.41%   |
| pl_PL   | 4        | 0.94%   |
| it_IT   | 4        | 0.94%   |
| es_CO   | 4        | 0.94%   |
| nl_NL   | 3        | 0.7%    |
| en_NZ   | 3        | 0.7%    |
| en_AU   | 3        | 0.7%    |
| da_DK   | 3        | 0.7%    |
| hu_HU   | 2        | 0.47%   |
| en_PH   | 2        | 0.47%   |
| sv_SE   | 1        | 0.23%   |
| sk_SK   | 1        | 0.23%   |
| pt_PT   | 1        | 0.23%   |
| nl_BE   | 1        | 0.23%   |
| nb_NO   | 1        | 0.23%   |
| fr_BE   | 1        | 0.23%   |
| fi_FI   | 1        | 0.23%   |
| es_VE   | 1        | 0.23%   |
| es_UY   | 1        | 0.23%   |
| es_GT   | 1        | 0.23%   |
| es_EC   | 1        | 0.23%   |
| es_CU   | 1        | 0.23%   |
| es_CL   | 1        | 0.23%   |
| en_ZA   | 1        | 0.23%   |
| en_IL   | 1        | 0.23%   |
| cs_CZ   | 1        | 0.23%   |
| C       | 1        | 0.23%   |
| ar_SA   | 1        | 0.23%   |
| Unknown | 1        | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 339      | 79.02%  |
| BIOS | 90       | 20.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 352      | 82.24%  |
| Ext4  | 75       | 17.52%  |
| Xfs   | 1        | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 356      | 82.98%  |
| GPT     | 68       | 15.85%  |
| MBR     | 5        | 1.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 406      | 95.08%  |
| Yes       | 21       | 4.92%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 388      | 91.08%  |
| Yes       | 38       | 8.92%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 127      | 29.81%  |
| MSI                                  | 99       | 23.24%  |
| Gigabyte Technology                  | 68       | 15.96%  |
| ASRock                               | 58       | 13.62%  |
| Hewlett-Packard                      | 19       | 4.46%   |
| Dell                                 | 16       | 3.76%   |
| Intel                                | 7        | 1.64%   |
| Lenovo                               | 3        | 0.7%    |
| Biostar                              | 3        | 0.7%    |
| Alienware                            | 3        | 0.7%    |
| Acer                                 | 3        | 0.7%    |
| Shenzhen Meigao Electronic Equipment | 2        | 0.47%   |
| Pegatron                             | 2        | 0.47%   |
| NZXT                                 | 2        | 0.47%   |
| Unknown                              | 2        | 0.47%   |
| Protectli                            | 1        | 0.23%   |
| OEM                                  | 1        | 0.23%   |
| MACHINIST                            | 1        | 0.23%   |
| langchao                             | 1        | 0.23%   |
| GPD                                  | 1        | 0.23%   |
| Google                               | 1        | 0.23%   |
| Fujitsu                              | 1        | 0.23%   |
| eMachines                            | 1        | 0.23%   |
| ECS                                  | 1        | 0.23%   |
| AZW                                  | 1        | 0.23%   |
| AOpen                                | 1        | 0.23%   |
| Acidanthera                          | 1        | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| MSI MS-7B86                        | 10       | 2.35%   |
| MSI MS-7C37                        | 7        | 1.64%   |
| MSI MS-7C91                        | 6        | 1.41%   |
| MSI MS-7B79                        | 6        | 1.41%   |
| ASUS All Series                    | 6        | 1.41%   |
| MSI MS-7D25                        | 5        | 1.17%   |
| MSI MS-7C56                        | 5        | 1.17%   |
| MSI MS-7C02                        | 5        | 1.17%   |
| ASUS ROG STRIX B550-F GAMING       | 5        | 1.17%   |
| ASUS TUF Gaming X570-PLUS          | 4        | 0.94%   |
| ASUS TUF Gaming B550M-PLUS         | 4        | 0.94%   |
| ASUS ROG STRIX B650E-I GAMING WIFI | 4        | 0.94%   |
| MSI MS-7C35                        | 3        | 0.7%    |
| Intel X79                          | 3        | 0.7%    |
| Gigabyte X570 AORUS ELITE          | 3        | 0.7%    |
| Gigabyte B550 AORUS ELITE V2       | 3        | 0.7%    |
| Dell XPS 8700                      | 3        | 0.7%    |
| ASUS PRIME A320M-K                 | 3        | 0.7%    |
| ASRock B450M Pro4                  | 3        | 0.7%    |
| NZXT N7 B650E                      | 2        | 0.47%   |
| MSI MS-7C87                        | 2        | 0.47%   |
| MSI MS-7B85                        | 2        | 0.47%   |
| MSI MS-7B84                        | 2        | 0.47%   |
| MSI MS-7B51                        | 2        | 0.47%   |
| MSI MS-7B17                        | 2        | 0.47%   |
| MSI MS-7A34                        | 2        | 0.47%   |
| MSI MS-7977                        | 2        | 0.47%   |
| MSI MS-7971                        | 2        | 0.47%   |
| MSI MS-7817                        | 2        | 0.47%   |
| MSI MS-7721                        | 2        | 0.47%   |
| MSI MS-7693                        | 2        | 0.47%   |
| Intel B75                          | 2        | 0.47%   |
| HP Compaq 6200 Pro SFF PC          | 2        | 0.47%   |
| Gigabyte Z77-D3H                   | 2        | 0.47%   |
| Gigabyte Z590I VISION D            | 2        | 0.47%   |
| Gigabyte X570 AORUS ELITE WIFI     | 2        | 0.47%   |
| Gigabyte B550I AORUS PRO AX        | 2        | 0.47%   |
| Gigabyte B550 GAMING X V2          | 2        | 0.47%   |
| Gigabyte B450M DS3H                | 2        | 0.47%   |
| Dell OptiPlex 390                  | 2        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| ASUS ROG       | 36       | 8.45%   |
| ASUS TUF       | 28       | 6.57%   |
| ASUS PRIME     | 26       | 6.1%    |
| MSI MS-7B86    | 10       | 2.35%   |
| Gigabyte X570  | 8        | 1.88%   |
| MSI MS-7C37    | 7        | 1.64%   |
| Dell OptiPlex  | 7        | 1.64%   |
| MSI MS-7C91    | 6        | 1.41%   |
| MSI MS-7B79    | 6        | 1.41%   |
| Gigabyte B550  | 6        | 1.41%   |
| ASUS All       | 6        | 1.41%   |
| MSI MS-7D25    | 5        | 1.17%   |
| MSI MS-7C56    | 5        | 1.17%   |
| MSI MS-7C02    | 5        | 1.17%   |
| HP EliteDesk   | 5        | 1.17%   |
| Gigabyte B550M | 5        | 1.17%   |
| ASRock B450M   | 5        | 1.17%   |
| HP Pavilion    | 4        | 0.94%   |
| HP Compaq      | 4        | 0.94%   |
| ASRock B550    | 4        | 0.94%   |
| MSI MS-7C35    | 3        | 0.7%    |
| Intel X79      | 3        | 0.7%    |
| Gigabyte H310M | 3        | 0.7%    |
| Dell XPS       | 3        | 0.7%    |
| Dell Precision | 3        | 0.7%    |
| ASRock Z97     | 3        | 0.7%    |
| ASRock X670E   | 3        | 0.7%    |
| ASRock B550M   | 3        | 0.7%    |
| ASRock B450    | 3        | 0.7%    |
| NZXT N7        | 2        | 0.47%   |
| MSI MS-7C87    | 2        | 0.47%   |
| MSI MS-7B85    | 2        | 0.47%   |
| MSI MS-7B84    | 2        | 0.47%   |
| MSI MS-7B51    | 2        | 0.47%   |
| MSI MS-7B17    | 2        | 0.47%   |
| MSI MS-7A34    | 2        | 0.47%   |
| MSI MS-7977    | 2        | 0.47%   |
| MSI MS-7971    | 2        | 0.47%   |
| MSI MS-7817    | 2        | 0.47%   |
| MSI MS-7721    | 2        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 65       | 15.26%  |
| 2019 | 65       | 15.26%  |
| 2018 | 64       | 15.02%  |
| 2022 | 46       | 10.8%   |
| 2021 | 44       | 10.33%  |
| 2013 | 24       | 5.63%   |
| 2012 | 24       | 5.63%   |
| 2017 | 19       | 4.46%   |
| 2014 | 16       | 3.76%   |
| 2016 | 15       | 3.52%   |
| 2011 | 14       | 3.29%   |
| 2015 | 10       | 2.35%   |
| 2023 | 9        | 2.11%   |
| 2010 | 4        | 0.94%   |
| 2008 | 4        | 0.94%   |
| 2009 | 3        | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 426      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 426      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 425      | 99.77%  |
| Yes  | 1        | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 149      | 34.73%  |
| 32.01-64.0  | 141      | 32.87%  |
| 24.01-32.0  | 35       | 8.16%   |
| 8.01-16.0   | 34       | 7.93%   |
| 64.01-256.0 | 31       | 7.23%   |
| 4.01-8.0    | 25       | 5.83%   |
| 3.01-4.0    | 14       | 3.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 206      | 44.69%  |
| 3.01-4.0   | 110      | 23.86%  |
| 2.01-3.0   | 64       | 13.88%  |
| 8.01-16.0  | 50       | 10.85%  |
| 1.01-2.0   | 19       | 4.12%   |
| 16.01-24.0 | 9        | 1.95%   |
| 24.01-32.0 | 2        | 0.43%   |
| 32.01-64.0 | 1        | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 128      | 29.29%  |
| 1      | 101      | 23.11%  |
| 3      | 98       | 22.43%  |
| 4      | 49       | 11.21%  |
| 5      | 32       | 7.32%   |
| 6      | 12       | 2.75%   |
| 7      | 7        | 1.6%    |
| 8      | 5        | 1.14%   |
| 10     | 2        | 0.46%   |
| 9      | 2        | 0.46%   |
| 0      | 1        | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 348      | 80.74%  |
| Yes       | 83       | 19.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 423      | 99.3%   |
| No        | 3        | 0.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 257      | 59.77%  |
| No        | 173      | 40.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 227      | 52.91%  |
| No        | 202      | 47.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 129      | 30.28%  |
| Germany      | 53       | 12.44%  |
| UK           | 22       | 5.16%   |
| Canada       | 22       | 5.16%   |
| France       | 18       | 4.23%   |
| Argentina    | 14       | 3.29%   |
| Netherlands  | 13       | 3.05%   |
| Russia       | 12       | 2.82%   |
| Brazil       | 12       | 2.82%   |
| Spain        | 11       | 2.58%   |
| Sweden       | 8        | 1.88%   |
| Italy        | 8        | 1.88%   |
| Mexico       | 7        | 1.64%   |
| Austria      | 7        | 1.64%   |
| Colombia     | 6        | 1.41%   |
| Australia    | 6        | 1.41%   |
| Poland       | 5        | 1.17%   |
| Hungary      | 5        | 1.17%   |
| Saudi Arabia | 4        | 0.94%   |
| Venezuela    | 3        | 0.7%    |
| Philippines  | 3        | 0.7%    |
| New Zealand  | 3        | 0.7%    |
| Finland      | 3        | 0.7%    |
| Estonia      | 3        | 0.7%    |
| Denmark      | 3        | 0.7%    |
| Chile        | 3        | 0.7%    |
| Belgium      | 3        | 0.7%    |
| Turkey       | 2        | 0.47%   |
| South Africa | 2        | 0.47%   |
| Serbia       | 2        | 0.47%   |
| Romania      | 2        | 0.47%   |
| Portugal     | 2        | 0.47%   |
| Norway       | 2        | 0.47%   |
| Lithuania    | 2        | 0.47%   |
| Japan        | 2        | 0.47%   |
| Czechia      | 2        | 0.47%   |
| Uruguay      | 1        | 0.23%   |
| Ukraine      | 1        | 0.23%   |
| UAE          | 1        | 0.23%   |
| Thailand     | 1        | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Buenos Aires             | 4        | 0.9%    |
| Berlin                   | 4        | 0.9%    |
| Toronto                  | 3        | 0.68%   |
| Stockholm                | 3        | 0.68%   |
| Seattle                  | 3        | 0.68%   |
| Melbourne                | 3        | 0.68%   |
| Atlanta                  | 3        | 0.68%   |
| Amsterdam                | 3        | 0.68%   |
| Wuppertal                | 2        | 0.45%   |
| Vilnius                  | 2        | 0.45%   |
| Vienna                   | 2        | 0.45%   |
| Victoria                 | 2        | 0.45%   |
| Toulouse                 | 2        | 0.45%   |
| Tartu                    | 2        | 0.45%   |
| Stuttgart                | 2        | 0.45%   |
| Sacramento               | 2        | 0.45%   |
| Rotterdam                | 2        | 0.45%   |
| Roseville                | 2        | 0.45%   |
| Rome                     | 2        | 0.45%   |
| Philadelphia             | 2        | 0.45%   |
| Osnabrück               | 2        | 0.45%   |
| Oberhausen               | 2        | 0.45%   |
| New York                 | 2        | 0.45%   |
| Mainz                    | 2        | 0.45%   |
| Los Angeles              | 2        | 0.45%   |
| Lexington                | 2        | 0.45%   |
| Karlsruhe                | 2        | 0.45%   |
| Istres                   | 2        | 0.45%   |
| Hjørring                | 2        | 0.45%   |
| Herten                   | 2        | 0.45%   |
| Helsinki                 | 2        | 0.45%   |
| Guadalajara              | 2        | 0.45%   |
| Gothenburg               | 2        | 0.45%   |
| Goiânia                 | 2        | 0.45%   |
| Gdynia                   | 2        | 0.45%   |
| Frankfurt am Main        | 2        | 0.45%   |
| Donostia / San Sebastian | 2        | 0.45%   |
| Denver                   | 2        | 0.45%   |
| Dallas                   | 2        | 0.45%   |
| Cologne                  | 2        | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 161      | 304    | 17.09%  |
| WDC                         | 128      | 194    | 13.59%  |
| Seagate                     | 125      | 181    | 13.27%  |
| Sandisk                     | 67       | 89     | 7.11%   |
| Kingston                    | 62       | 73     | 6.58%   |
| Crucial                     | 60       | 90     | 6.37%   |
| Toshiba                     | 53       | 65     | 5.63%   |
| Phison Electronics          | 28       | 35     | 2.97%   |
| Micron/Crucial Technology   | 28       | 39     | 2.97%   |
| Intel                       | 16       | 23     | 1.7%    |
| PNY                         | 15       | 24     | 1.59%   |
| Kingston Technology Company | 14       | 17     | 1.49%   |
| Hitachi                     | 11       | 15     | 1.17%   |
| Silicon Motion              | 10       | 12     | 1.06%   |
| SPCC                        | 9        | 11     | 0.96%   |
| Realtek Semiconductor       | 9        | 11     | 0.96%   |
| Phison                      | 8        | 9      | 0.85%   |
| ADATA Technology            | 8        | 9      | 0.85%   |
| Unknown                     | 7        | 15     | 0.74%   |
| China                       | 7        | 7      | 0.74%   |
| A-DATA Technology           | 7        | 8      | 0.74%   |
| Micron Technology           | 6        | 6      | 0.64%   |
| Team                        | 5        | 5      | 0.53%   |
| SK hynix                    | 5        | 7      | 0.53%   |
| HGST                        | 5        | 8      | 0.53%   |
| Verbatim                    | 4        | 5      | 0.42%   |
| MAXIO Technology (Hangzhou) | 4        | 4      | 0.42%   |
| KIOXIA                      | 4        | 5      | 0.42%   |
| Intenso                     | 4        | 5      | 0.42%   |
| Corsair                     | 4        | 4      | 0.42%   |
| OCZ                         | 3        | 3      | 0.32%   |
| KIOXIA-EXCERIA              | 3        | 4      | 0.32%   |
| USB3.0                      | 2        | 2      | 0.21%   |
| Transcend                   | 2        | 2      | 0.21%   |
| SABRENT                     | 2        | 3      | 0.21%   |
| Maxtor                      | 2        | 2      | 0.21%   |
| Lexar                       | 2        | 3      | 0.21%   |
| KingFast                    | 2        | 2      | 0.21%   |
| JMicron Technology          | 2        | 5      | 0.21%   |
| Fanxiang                    | 2        | 2      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 39       | 3.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 25       | 2.21%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 20       | 1.77%   |
| Kingston SA400S37240G 240GB SSD                       | 17       | 1.5%    |
| Phison E12 NVMe Controller 1TB                        | 16       | 1.41%   |
| Samsung SSD 860 EVO 500GB                             | 15       | 1.33%   |
| Samsung SSD 860 EVO 1TB                               | 14       | 1.24%   |
| Crucial CT1000MX500SSD1 1TB                           | 14       | 1.24%   |
| Samsung SSD 850 EVO 500GB                             | 13       | 1.15%   |
| Seagate ST2000DM008-2FR102 2TB                        | 12       | 1.06%   |
| Toshiba DT01ACA100 1TB                                | 10       | 0.88%   |
| Intel SSD 660P Series 1024GB                          | 10       | 0.88%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                  | 9        | 0.8%    |
| Samsung SSD 850 EVO 250GB                             | 9        | 0.8%    |
| Samsung SSD 980 1TB                                   | 8        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                       | 8        | 0.71%   |
| Crucial CT1000BX500SSD1 1TB                           | 8        | 0.71%   |
| Samsung SSD 870 EVO 1TB                               | 7        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 7        | 0.62%   |
| Crucial CT240BX500SSD1 240GB                          | 7        | 0.62%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 6        | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 6        | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB                              | 6        | 0.53%   |
| Toshiba HDWD110 1TB                                   | 6        | 0.53%   |
| Toshiba DT01ACA200 2TB                                | 6        | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 6        | 0.53%   |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                        | 6        | 0.53%   |
| Samsung SSD 860 EVO 250GB                             | 6        | 0.53%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 6        | 0.53%   |
| Kingston Company A2000 NVMe SSD 500GB                 | 6        | 0.53%   |
| Crucial CT2000MX500SSD1 2TB                           | 6        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 5        | 0.44%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                        | 5        | 0.44%   |
| Sandisk WD Blue SN570 500GB                           | 5        | 0.44%   |
| Sandisk WD Blue SN570 1TB                             | 5        | 0.44%   |
| Samsung SSD 980 500GB                                 | 5        | 0.44%   |
| Samsung HD103SI 1TB                                   | 5        | 0.44%   |
| PNY CS900 500GB SSD                                   | 5        | 0.44%   |
| Kingston SA400S37120G 120GB SSD                       | 5        | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 122      | 174    | 38.61%  |
| WDC                 | 104      | 153    | 32.91%  |
| Toshiba             | 47       | 58     | 14.87%  |
| Samsung Electronics | 17       | 28     | 5.38%   |
| Hitachi             | 11       | 15     | 3.48%   |
| HGST                | 5        | 8      | 1.58%   |
| Maxtor              | 2        | 2      | 0.63%   |
| JMicron Technology  | 2        | 5      | 0.63%   |
| ASMT                | 2        | 2      | 0.63%   |
| Apple               | 2        | 2      | 0.63%   |
| SABRENT             | 1        | 2      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 96       | 136    | 26.3%   |
| Crucial             | 59       | 89     | 16.16%  |
| Kingston            | 49       | 56     | 13.42%  |
| WDC                 | 33       | 38     | 9.04%   |
| SanDisk             | 20       | 25     | 5.48%   |
| PNY                 | 15       | 24     | 4.11%   |
| SPCC                | 9        | 11     | 2.47%   |
| China               | 7        | 7      | 1.92%   |
| A-DATA Technology   | 7        | 8      | 1.92%   |
| Toshiba             | 4        | 4      | 1.1%    |
| Team                | 4        | 4      | 1.1%    |
| Intel               | 4        | 5      | 1.1%    |
| Verbatim            | 3        | 4      | 0.82%   |
| OCZ                 | 3        | 3      | 0.82%   |
| Micron Technology   | 3        | 3      | 0.82%   |
| KIOXIA-EXCERIA      | 3        | 4      | 0.82%   |
| Intenso             | 3        | 3      | 0.82%   |
| Corsair             | 3        | 3      | 0.82%   |
| USB3.0              | 2        | 2      | 0.55%   |
| Transcend           | 2        | 2      | 0.55%   |
| Seagate             | 2        | 2      | 0.55%   |
| Lexar               | 2        | 3      | 0.55%   |
| Drevo               | 2        | 2      | 0.55%   |
| Apacer              | 2        | 2      | 0.55%   |
| XSTAR               | 1        | 1      | 0.27%   |
| XrayDisk            | 1        | 1      | 0.27%   |
| WDC WDS             | 1        | 1      | 0.27%   |
| SuperSSpeed         | 1        | 1      | 0.27%   |
| SK hynix            | 1        | 1      | 0.27%   |
| SD                  | 1        | 1      | 0.27%   |
| SCY                 | 1        | 1      | 0.27%   |
| SABRENT             | 1        | 1      | 0.27%   |
| Rogueware           | 1        | 1      | 0.27%   |
| Ramaxel Technology  | 1        | 1      | 0.27%   |
| PNY CS90            | 1        | 1      | 0.27%   |
| Plextor             | 1        | 1      | 0.27%   |
| Patriot             | 1        | 1      | 0.27%   |
| ORTIAL              | 1        | 1      | 0.27%   |
| Neo                 | 1        | 1      | 0.27%   |
| MyDigitalSSD        | 1        | 1      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 281      | 468    | 35.52%  |
| HDD     | 247      | 450    | 31.23%  |
| NVMe    | 243      | 412    | 30.72%  |
| Unknown | 19       | 25     | 2.4%    |
| MMC     | 1        | 1      | 0.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 356      | 887    | 55.89%  |
| NVMe | 242      | 408    | 37.99%  |
| SAS  | 38       | 60     | 5.97%   |
| MMC  | 1        | 1      | 0.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 239      | 390    | 40.17%  |
| 0.51-1.0   | 195      | 288    | 32.77%  |
| 1.01-2.0   | 90       | 144    | 15.13%  |
| 3.01-4.0   | 28       | 38     | 4.71%   |
| 4.01-10.0  | 23       | 33     | 3.87%   |
| 2.01-3.0   | 16       | 20     | 2.69%   |
| 10.01-20.0 | 4        | 5      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 103      | 23.46%  |
| More than 3000 | 90       | 20.5%   |
| 501-1000       | 71       | 16.17%  |
| 251-500        | 63       | 14.35%  |
| 101-250        | 46       | 10.48%  |
| 2001-3000      | 40       | 9.11%   |
| 21-50          | 11       | 2.51%   |
| 51-100         | 7        | 1.59%   |
| Unknown        | 5        | 1.14%   |
| 1-20           | 3        | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 90       | 19.69%  |
| 1-20           | 68       | 14.88%  |
| 101-250        | 65       | 14.22%  |
| 501-1000       | 50       | 10.94%  |
| 251-500        | 47       | 10.28%  |
| 51-100         | 45       | 9.85%   |
| 1001-2000      | 36       | 7.88%   |
| More than 3000 | 27       | 5.91%   |
| 2001-3000      | 24       | 5.25%   |
| Unknown        | 5        | 1.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2        | 2      | 16.67%  |
| WDC WD30EZRX-00DC0B0 3TB                       | 1        | 1      | 8.33%   |
| WDC WD20EURS-63S48Y0 2TB                       | 1        | 1      | 8.33%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1        | 1      | 8.33%   |
| WDC WD10EACS-00D6B0 1TB                        | 1        | 1      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB                | 1        | 1      | 8.33%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1        | 1      | 8.33%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1        | 1      | 8.33%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1        | 1      | 8.33%   |
| Samsung Electronics HD161GJ 160GB              | 1        | 1      | 8.33%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 50%     |
| Seagate             | 3        | 3      | 25%     |
| Samsung Electronics | 2        | 2      | 16.67%  |
| Micron Technology   | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 60%     |
| Seagate             | 3        | 3      | 30%     |
| Samsung Electronics | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 10     | 83.33%  |
| NVMe | 1        | 1      | 8.33%   |
| SSD  | 1        | 1      | 8.33%   |

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
| Detected | 362      | 1148   | 81.72%  |
| Works    | 69       | 195    | 15.58%  |
| Malfunc  | 11       | 12     | 2.48%   |
| Limited  | 1        | 1      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 232      | 30.73%  |
| Intel                        | 193      | 25.56%  |
| Samsung Electronics          | 88       | 11.66%  |
| SanDisk                      | 50       | 6.62%   |
| Phison Electronics           | 36       | 4.77%   |
| Kingston Technology Company  | 30       | 3.97%   |
| Micron/Crucial Technology    | 29       | 3.84%   |
| ASMedia Technology           | 29       | 3.84%   |
| Silicon Motion               | 10       | 1.32%   |
| Realtek Semiconductor        | 10       | 1.32%   |
| ADATA Technology             | 8        | 1.06%   |
| Marvell Technology Group     | 5        | 0.66%   |
| SK hynix                     | 4        | 0.53%   |
| Nvidia                       | 4        | 0.53%   |
| MAXIO Technology (Hangzhou)  | 4        | 0.53%   |
| KIOXIA                       | 4        | 0.53%   |
| Solidigm                     | 3        | 0.4%    |
| Micron Technology            | 3        | 0.4%    |
| JMicron Technology           | 3        | 0.4%    |
| Toshiba America Info Systems | 2        | 0.26%   |
| Seagate Technology           | 2        | 0.26%   |
| Broadcom / LSI               | 2        | 0.26%   |
| Silicon Image                | 1        | 0.13%   |
| Shenzhen Longsys Electronics | 1        | 0.13%   |
| LSI Logic / Symbios Logic    | 1        | 0.13%   |
| Biwin Storage Technology     | 1        | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 108      | 12.4%   |
| AMD 400 Series Chipset SATA Controller                                         | 61       | 7%      |
| AMD 500 Series Chipset SATA Controller                                         | 55       | 6.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 46       | 5.28%   |
| AMD 600 Series Chipset SATA Controller                                         | 31       | 3.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 28       | 3.21%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 28       | 3.21%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 22       | 2.53%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 20       | 2.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19       | 2.18%   |
| Phison E12 NVMe Controller                                                     | 17       | 1.95%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 16       | 1.84%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 16       | 1.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 14       | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 14       | 1.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 13       | 1.49%   |
| Intel SATA Controller [RAID mode]                                              | 13       | 1.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13       | 1.49%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 12       | 1.38%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 11       | 1.26%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 11       | 1.26%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 10       | 1.15%   |
| Intel SSD 660P Series                                                          | 10       | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10       | 1.15%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 9        | 1.03%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 9        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8        | 0.92%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 8        | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8        | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                         | 8        | 0.92%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 7        | 0.8%    |
| Phison E16 PCIe4 NVMe Controller                                               | 7        | 0.8%    |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 7        | 0.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 6        | 0.69%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 6        | 0.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 6        | 0.69%   |
| AMD FCH SATA Controller D                                                      | 6        | 0.69%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 5        | 0.57%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 5        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 396      | 57.64%  |
| NVMe | 242      | 35.23%  |
| IDE  | 25       | 3.64%   |
| RAID | 20       | 2.91%   |
| SAS  | 4        | 0.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 238      | 55.87%  |
| Intel  | 188      | 44.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 21       | 4.9%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 16       | 3.73%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 14       | 3.26%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 13       | 3.03%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 12       | 2.8%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 10       | 2.33%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 8        | 1.86%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 8        | 1.86%   |
| AMD Ryzen 7 7800X3D 8-Core Processor        | 8        | 1.86%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 7        | 1.63%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 7        | 1.63%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 7        | 1.63%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 7        | 1.63%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 7        | 1.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 1.4%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 1.4%    |
| AMD Ryzen 9 7950X 16-Core Processor         | 6        | 1.4%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 6        | 1.4%    |
| AMD Ryzen 5 7600X 6-Core Processor          | 6        | 1.4%    |
| AMD FX-8350 Eight-Core Processor            | 6        | 1.4%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 5        | 1.17%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 5        | 1.17%   |
| AMD Ryzen 5 5500                            | 5        | 1.17%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 5        | 1.17%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4        | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 0.93%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4        | 0.93%   |
| Intel 12th Gen Core i5-12600K               | 4        | 0.93%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 4        | 0.93%   |
| AMD Ryzen 5 5600 6-Core Processor           | 4        | 0.93%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.7%    |
| Intel Core i5-8600K CPU @ 3.60GHz           | 3        | 0.7%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.7%    |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.7%    |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3        | 0.7%    |
| Intel 13th Gen Core i7-13700K               | 3        | 0.7%    |
| Intel 12th Gen Core i7-12700K               | 3        | 0.7%    |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 3        | 0.7%    |
| AMD Ryzen 9 7950X3D 16-Core Processor       | 3        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 91       | 21.21%  |
| AMD Ryzen 7             | 67       | 15.62%  |
| Intel Core i5           | 59       | 13.75%  |
| Intel Core i7           | 48       | 11.19%  |
| AMD Ryzen 9             | 43       | 10.02%  |
| Other                   | 30       | 6.99%   |
| Intel Core i3           | 18       | 4.2%    |
| Intel Xeon              | 17       | 3.96%   |
| AMD FX                  | 12       | 2.8%    |
| Intel Core i9           | 9        | 2.1%    |
| AMD Ryzen 3             | 9        | 2.1%    |
| Intel Pentium           | 3        | 0.7%    |
| AMD Phenom II X6        | 3        | 0.7%    |
| Intel Core 2 Duo        | 2        | 0.47%   |
| Intel Celeron           | 2        | 0.47%   |
| AMD A4                  | 2        | 0.47%   |
| AMD A10                 | 2        | 0.47%   |
| Intel Pentium Dual-Core | 1        | 0.23%   |
| Intel Core 2 Quad       | 1        | 0.23%   |
| Intel Atom              | 1        | 0.23%   |
| AMD Ryzen Threadripper  | 1        | 0.23%   |
| AMD Phenom II X4        | 1        | 0.23%   |
| AMD Phenom              | 1        | 0.23%   |
| AMD Athlon X4           | 1        | 0.23%   |
| AMD Athlon II X2        | 1        | 0.23%   |
| AMD Athlon Dual Core    | 1        | 0.23%   |
| AMD Athlon              | 1        | 0.23%   |
| AMD A8                  | 1        | 0.23%   |
| AMD A6                  | 1        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 135      | 31.69%  |
| 4      | 100      | 23.47%  |
| 8      | 92       | 21.6%   |
| 2      | 31       | 7.28%   |
| 12     | 27       | 6.34%   |
| 16     | 24       | 5.63%   |
| 10     | 6        | 1.41%   |
| 3      | 4        | 0.94%   |
| 1      | 3        | 0.7%    |
| 24     | 2        | 0.47%   |
| 14     | 2        | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 424      | 99.53%  |
| 2      | 2        | 0.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 344      | 80.19%  |
| 1      | 85       | 19.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 426      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 124      | 28.57%  |
| 0x08701021 | 38       | 8.76%   |
| 0x0a601203 | 24       | 5.53%   |
| 0x0800820d | 19       | 4.38%   |
| 0x0a201016 | 16       | 3.69%   |
| 0x306c3    | 15       | 3.46%   |
| 0x0a20120a | 14       | 3.23%   |
| 0x306a9    | 12       | 2.76%   |
| 0x0a50000d | 12       | 2.76%   |
| 0x08701030 | 9        | 2.07%   |
| 0x08108109 | 8        | 1.84%   |
| 0x06000822 | 8        | 1.84%   |
| 0x206a7    | 7        | 1.61%   |
| 0x906ea    | 6        | 1.38%   |
| 0x90672    | 6        | 1.38%   |
| 0x0a201205 | 6        | 1.38%   |
| 0x0a201204 | 6        | 1.38%   |
| 0xa0655    | 5        | 1.15%   |
| 0x906e9    | 5        | 1.15%   |
| 0x0a601206 | 5        | 1.15%   |
| 0x0a50000c | 5        | 1.15%   |
| 0x0a20120e | 5        | 1.15%   |
| 0x08001138 | 5        | 1.15%   |
| 0xa0653    | 4        | 0.92%   |
| 0x906ed    | 4        | 0.92%   |
| 0x906ec    | 4        | 0.92%   |
| 0x506e3    | 4        | 0.92%   |
| 0x206d7    | 4        | 0.92%   |
| 0x0a201025 | 4        | 0.92%   |
| 0x0a201009 | 4        | 0.92%   |
| 0x08701013 | 4        | 0.92%   |
| 0x0800820b | 3        | 0.69%   |
| 0x06003106 | 3        | 0.69%   |
| 0x06001119 | 3        | 0.69%   |
| 0x010000bf | 3        | 0.69%   |
| 0xa0671    | 2        | 0.46%   |
| 0x1067a    | 2        | 0.46%   |
| 0x0a404102 | 2        | 0.46%   |
| 0x08600106 | 2        | 0.46%   |
| 0x00000000 | 2        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 84       | 19.67%  |
| Zen 2            | 55       | 12.88%  |
| KabyLake         | 42       | 9.84%   |
| Unknown          | 36       | 8.43%   |
| Zen+             | 33       | 7.73%   |
| Haswell          | 32       | 7.49%   |
| IvyBridge        | 24       | 5.62%   |
| Alderlake Hybrid | 19       | 4.45%   |
| CometLake        | 18       | 4.22%   |
| SandyBridge      | 17       | 3.98%   |
| Skylake          | 14       | 3.28%   |
| Piledriver       | 14       | 3.28%   |
| Zen              | 7        | 1.64%   |
| Icelake          | 7        | 1.64%   |
| K10              | 6        | 1.41%   |
| Penryn           | 4        | 0.94%   |
| Broadwell        | 4        | 0.94%   |
| Steamroller      | 3        | 0.7%    |
| Westmere         | 1        | 0.23%   |
| TigerLake        | 1        | 0.23%   |
| Silvermont       | 1        | 0.23%   |
| Nehalem          | 1        | 0.23%   |
| K8 Hammer        | 1        | 0.23%   |
| Excavator        | 1        | 0.23%   |
| Core             | 1        | 0.23%   |
| Bulldozer        | 1        | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 222      | 47.03%  |
| Nvidia | 185      | 39.19%  |
| Intel  | 65       | 13.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 44       | 8.73%   |
| AMD Raphael                                                                 | 28       | 5.56%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 27       | 5.36%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 20       | 3.97%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 19       | 3.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 15       | 2.98%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 14       | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 12       | 2.38%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 10       | 1.98%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 10       | 1.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 10       | 1.98%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 7        | 1.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 1.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 1.39%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 6        | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 1.19%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 1.19%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 6        | 1.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 1.19%   |
| Intel AlderLake-S GT1                                                       | 6        | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.99%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 0.99%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 0.99%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 5        | 0.99%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 5        | 0.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 0.99%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.79%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 0.79%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 0.79%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 4        | 0.79%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 0.79%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 4        | 0.79%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 4        | 0.79%   |
| AMD Navi 32 [Radeon RX 7700 XT / 7800 XT]                                   | 4        | 0.79%   |
| AMD Navi 21 [Radeon RX 6950 XT]                                             | 4        | 0.79%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 0.79%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.6%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 179      | 41.63%  |
| 1 x Nvidia     | 164      | 38.14%  |
| 1 x Intel      | 39       | 9.07%   |
| 2 x AMD        | 23       | 5.35%   |
| AMD + Nvidia   | 13       | 3.02%   |
| Intel + Nvidia | 5        | 1.16%   |
| Intel + AMD    | 4        | 0.93%   |
| 2 x Nvidia     | 3        | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 279      | 64.73%  |
| Proprietary | 141      | 32.71%  |
| Unknown     | 11       | 2.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 128      | 29.36%  |
| 7.01-8.0   | 102      | 23.39%  |
| 8.01-16.0  | 70       | 16.06%  |
| 3.01-4.0   | 37       | 8.49%   |
| 1.01-2.0   | 33       | 7.57%   |
| 0.01-0.5   | 18       | 4.13%   |
| 16.01-24.0 | 17       | 3.9%    |
| 5.01-6.0   | 15       | 3.44%   |
| 0.51-1.0   | 12       | 2.75%   |
| 2.01-3.0   | 4        | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 85       | 16.54%  |
| Goldstar             | 61       | 11.87%  |
| Acer                 | 48       | 9.34%   |
| Dell                 | 44       | 8.56%   |
| Ancor Communications | 33       | 6.42%   |
| BenQ                 | 32       | 6.23%   |
| ASUSTek Computer     | 25       | 4.86%   |
| Hewlett-Packard      | 24       | 4.67%   |
| AOC                  | 23       | 4.47%   |
| MSI                  | 13       | 2.53%   |
| Vizio                | 10       | 1.95%   |
| ViewSonic            | 10       | 1.95%   |
| Philips              | 9        | 1.75%   |
| Sony                 | 8        | 1.56%   |
| Lenovo               | 8        | 1.56%   |
| Iiyama               | 8        | 1.56%   |
| Gigabyte Technology  | 8        | 1.56%   |
| Sceptre Tech         | 5        | 0.97%   |
| Toshiba              | 4        | 0.78%   |
| Unknown              | 3        | 0.58%   |
| Viotek               | 2        | 0.39%   |
| SANYO                | 2        | 0.39%   |
| Pixio                | 2        | 0.39%   |
| NEC Computers        | 2        | 0.39%   |
| Insignia             | 2        | 0.39%   |
| HannStar             | 2        | 0.39%   |
| Eizo                 | 2        | 0.39%   |
| Corsair              | 2        | 0.39%   |
| Yeyian               | 1        | 0.19%   |
| Yamaha               | 1        | 0.19%   |
| WIT                  | 1        | 0.19%   |
| Valve                | 1        | 0.19%   |
| SNC                  | 1        | 0.19%   |
| Sharp                | 1        | 0.19%   |
| SFX                  | 1        | 0.19%   |
| PRI                  | 1        | 0.19%   |
| Plain Tree Systems   | 1        | 0.19%   |
| Panasonic            | 1        | 0.19%   |
| Packard Bell         | 1        | 0.19%   |
| Olevia               | 1        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 7        | 1.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 5        | 0.91%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 4        | 0.73%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 4        | 0.73%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 4        | 0.73%   |
| Acer GN246HL ACR02F9 1920x1080 531x299mm 24.0-inch                     | 4        | 0.73%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 3        | 0.55%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 3        | 0.55%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                     | 3        | 0.55%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch            | 3        | 0.55%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 3        | 0.55%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 3        | 0.55%   |
| BenQ EX3501R BNQ7F5E 3440x1440 819x346mm 35.0-inch                     | 3        | 0.55%   |
| ASUSTek Computer VA27EHE AUS27D2 1920x1080 598x336mm 27.0-inch         | 3        | 0.55%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch         | 3        | 0.55%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                       | 3        | 0.55%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 3        | 0.55%   |
| Acer GN246HL ACR02FA 1920x1080 531x299mm 24.0-inch                     | 3        | 0.55%   |
| Vizio V405-H9 VIZ1039 3840x2160 878x485mm 39.5-inch                    | 2        | 0.37%   |
| Vizio E32-C1 VIZ1004 1920x1080 698x392mm 31.5-inch                     | 2        | 0.37%   |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                    | 2        | 0.37%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch          | 2        | 0.37%   |
| Toshiba TV TSB0108 1920x540                                            | 2        | 0.37%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch         | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 2        | 0.37%   |
| Samsung Electronics SMB2230H SAM0648 1920x1080                         | 2        | 0.37%   |
| Samsung Electronics Odyssey G52A SAM7181 2560x1440 597x336mm 27.0-inch | 2        | 0.37%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch  | 2        | 0.37%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 2        | 0.37%   |
| Samsung Electronics LC27G7xT SAM105C 2560x1440 597x336mm 27.0-inch     | 2        | 0.37%   |
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 2        | 0.37%   |
| Hewlett-Packard X27i HPN3678 2560x1440 597x336mm 27.0-inch             | 2        | 0.37%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch               | 2        | 0.37%   |
| Goldstar ULTRAGEAR GSM5C0A 1920x1080 600x340mm 27.2-inch               | 2        | 0.37%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch               | 2        | 0.37%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.37%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 2        | 0.37%   |
| Goldstar QHD GSM772A 2560x1440 697x392mm 31.5-inch                     | 2        | 0.37%   |
| Goldstar LG ULTRAWIDE GSM76E4 3440x1440 800x340mm 34.2-inch            | 2        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 202      | 41.48%  |
| 2560x1440 (QHD)    | 92       | 18.89%  |
| 3840x2160 (4K)     | 67       | 13.76%  |
| 3440x1440          | 22       | 4.52%   |
| 1680x1050 (WSXGA+) | 17       | 3.49%   |
| 2560x1080          | 11       | 2.26%   |
| 1280x1024 (SXGA)   | 11       | 2.26%   |
| 1440x900 (WXGA+)   | 9        | 1.85%   |
| 1600x900 (HD+)     | 8        | 1.64%   |
| 1360x768           | 8        | 1.64%   |
| 1920x540           | 7        | 1.44%   |
| 1366x768 (WXGA)    | 7        | 1.44%   |
| 1920x1200 (WUXGA)  | 6        | 1.23%   |
| 3840x1080          | 5        | 1.03%   |
| 2288x1287          | 4        | 0.82%   |
| 2560x1600          | 3        | 0.62%   |
| 3840x1600          | 2        | 0.41%   |
| Unknown            | 2        | 0.41%   |
| 5760x1080          | 1        | 0.21%   |
| 3840x2560          | 1        | 0.21%   |
| 2048x1152          | 1        | 0.21%   |
| 1600x1200          | 1        | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 117      | 23.08%  |
| 24      | 56       | 11.05%  |
| 23      | 51       | 10.06%  |
| 21      | 43       | 8.48%   |
| 31      | 39       | 7.69%   |
| 34      | 24       | 4.73%   |
| 19      | 14       | 2.76%   |
| 84      | 13       | 2.56%   |
| 22      | 13       | 2.56%   |
| Unknown | 12       | 2.37%   |
| 40      | 11       | 2.17%   |
| 32      | 10       | 1.97%   |
| 20      | 9        | 1.78%   |
| 18      | 9        | 1.78%   |
| 72      | 8        | 1.58%   |
| 48      | 8        | 1.58%   |
| 29      | 7        | 1.38%   |
| 17      | 7        | 1.38%   |
| 42      | 6        | 1.18%   |
| 49      | 4        | 0.79%   |
| 35      | 4        | 0.79%   |
| 33      | 4        | 0.79%   |
| 26      | 4        | 0.79%   |
| 142     | 3        | 0.59%   |
| 54      | 3        | 0.59%   |
| 52      | 3        | 0.59%   |
| 28      | 3        | 0.59%   |
| 25      | 3        | 0.59%   |
| 69      | 2        | 0.39%   |
| 60      | 2        | 0.39%   |
| 38      | 2        | 0.39%   |
| 37      | 2        | 0.39%   |
| 14      | 2        | 0.39%   |
| 100     | 1        | 0.2%    |
| 85      | 1        | 0.2%    |
| 75      | 1        | 0.2%    |
| 58      | 1        | 0.2%    |
| 55      | 1        | 0.2%    |
| 47      | 1        | 0.2%    |
| 46      | 1        | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 203      | 41.26%  |
| 401-500        | 85       | 17.28%  |
| 601-700        | 60       | 12.2%   |
| 701-800        | 37       | 7.52%   |
| 1501-2000      | 25       | 5.08%   |
| 1001-1500      | 24       | 4.88%   |
| 801-900        | 19       | 3.86%   |
| Unknown        | 12       | 2.44%   |
| 301-350        | 9        | 1.83%   |
| 901-1000       | 7        | 1.42%   |
| 351-400        | 6        | 1.22%   |
| More than 2000 | 4        | 0.81%   |
| 201-300        | 1        | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 324      | 75.7%   |
| 16/10   | 36       | 8.41%   |
| 21/9    | 34       | 7.94%   |
| 5/4     | 12       | 2.8%    |
| 32/9    | 7        | 1.64%   |
| 4/3     | 4        | 0.93%   |
| 3/2     | 4        | 0.93%   |
| 1.00    | 3        | 0.7%    |
| Unknown | 3        | 0.7%    |
| 1.96    | 1        | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 131      | 26.63%  |
| 301-350        | 124      | 25.2%   |
| 351-500        | 81       | 16.46%  |
| More than 1000 | 44       | 8.94%   |
| 151-200        | 38       | 7.72%   |
| 501-1000       | 30       | 6.1%    |
| 251-300        | 18       | 3.66%   |
| Unknown        | 12       | 2.44%   |
| 141-150        | 11       | 2.24%   |
| 81-90          | 1        | 0.2%    |
| 101-110        | 1        | 0.2%    |
| 91-100         | 1        | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 272      | 58.37%  |
| 101-120 | 117      | 25.11%  |
| 1-50    | 33       | 7.08%   |
| 121-160 | 21       | 4.51%   |
| Unknown | 12       | 2.58%   |
| 161-240 | 11       | 2.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 291      | 66.9%   |
| 2     | 106      | 24.37%  |
| 3     | 21       | 4.83%   |
| 0     | 15       | 3.45%   |
| 4     | 2        | 0.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 275      | 41.48%  |
| Intel                           | 209      | 31.52%  |
| MediaTek                        | 36       | 5.43%   |
| TP-Link                         | 24       | 3.62%   |
| Qualcomm Atheros                | 24       | 3.62%   |
| Microsoft                       | 19       | 2.87%   |
| Broadcom                        | 16       | 2.41%   |
| Ralink Technology               | 10       | 1.51%   |
| Aquantia                        | 5        | 0.75%   |
| Xiaomi                          | 3        | 0.45%   |
| Broadcom Limited                | 3        | 0.45%   |
| ASUSTek Computer                | 3        | 0.45%   |
| Samsung Electronics             | 2        | 0.3%    |
| Ralink                          | 2        | 0.3%    |
| Qualcomm Atheros Communications | 2        | 0.3%    |
| Qualcomm                        | 2        | 0.3%    |
| Oculus VR                       | 2        | 0.3%    |
| NetGear                         | 2        | 0.3%    |
| Motorola PCS                    | 2        | 0.3%    |
| D-Link System                   | 2        | 0.3%    |
| D-Link                          | 2        | 0.3%    |
| Belkin Components               | 2        | 0.3%    |
| ZTE WCDMA Technologies MSM      | 1        | 0.15%   |
| Wacom                           | 1        | 0.15%   |
| T & A Mobile Phones             | 1        | 0.15%   |
| ROCCAT                          | 1        | 0.15%   |
| Padix (Rockfire)                | 1        | 0.15%   |
| OPPO Electronics                | 1        | 0.15%   |
| Nvidia                          | 1        | 0.15%   |
| Microchip Technology            | 1        | 0.15%   |
| Mellanox Technologies           | 1        | 0.15%   |
| Loupedeck                       | 1        | 0.15%   |
| Linksys                         | 1        | 0.15%   |
| ICS Advent                      | 1        | 0.15%   |
| Holtek Semiconductor            | 1        | 0.15%   |
| DisplayLink                     | 1        | 0.15%   |
| AVM                             | 1        | 0.15%   |
| ASIX Electronics                | 1        | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 195      | 25.36%  |
| Realtek RTL8125 2.5GbE Controller                                      | 70       | 9.1%    |
| Intel Wi-Fi 6 AX200                                                    | 44       | 5.72%   |
| Intel I211 Gigabit Network Connection                                  | 38       | 4.94%   |
| Intel Ethernet Controller I225-V                                       | 38       | 4.94%   |
| Intel Ethernet Connection (7) I219-V                                   | 18       | 2.34%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 17       | 2.21%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 16       | 2.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 16       | 2.08%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 13       | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 13       | 1.69%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 13       | 1.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 9        | 1.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 8        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 1.04%   |
| Intel Ethernet Connection (2) I218-V                                   | 8        | 1.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8        | 1.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7        | 0.91%   |
| Realtek 802.11ac NIC                                                   | 6        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6        | 0.78%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 6        | 0.78%   |
| TP-Link 802.11ac NIC                                                   | 5        | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 5        | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5        | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 0.65%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4        | 0.52%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 4        | 0.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 4        | 0.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 4        | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4        | 0.52%   |
| Intel Wireless 7265                                                    | 4        | 0.52%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 0.52%   |
| Intel Ethernet Connection (12) I219-V                                  | 4        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3        | 0.39%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 3        | 0.39%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                        | 3        | 0.39%   |
| Ralink RT5370 Wireless Adapter                                         | 3        | 0.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 116      | 40.14%  |
| Realtek Semiconductor           | 44       | 15.22%  |
| MediaTek                        | 36       | 12.46%  |
| TP-Link                         | 24       | 8.3%    |
| Microsoft                       | 19       | 6.57%   |
| Broadcom                        | 14       | 4.84%   |
| Ralink Technology               | 10       | 3.46%   |
| Qualcomm Atheros                | 7        | 2.42%   |
| ASUSTek Computer                | 3        | 1.04%   |
| Ralink                          | 2        | 0.69%   |
| Qualcomm Atheros Communications | 2        | 0.69%   |
| NetGear                         | 2        | 0.69%   |
| D-Link System                   | 2        | 0.69%   |
| Broadcom Limited                | 2        | 0.69%   |
| Belkin Components               | 2        | 0.69%   |
| Wacom                           | 1        | 0.35%   |
| Linksys                         | 1        | 0.35%   |
| D-Link                          | 1        | 0.35%   |
| AVM                             | 1        | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 44       | 15.12%  |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 17       | 5.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 16       | 5.5%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 16       | 5.5%    |
| Microsoft Xbox Wireless Adapter for Windows                   | 13       | 4.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 13       | 4.47%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 13       | 4.47%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 9        | 3.09%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 8        | 2.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 7        | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 7        | 2.41%   |
| Realtek 802.11ac NIC                                          | 6        | 2.06%   |
| Microsoft Xbox 360 Wireless Adapter                           | 6        | 2.06%   |
| TP-Link 802.11ac NIC                                          | 5        | 1.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 5        | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5        | 1.72%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 4        | 1.37%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 4        | 1.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 4        | 1.37%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 4        | 1.37%   |
| Intel Wireless 7265                                           | 4        | 1.37%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 3        | 1.03%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter               | 3        | 1.03%   |
| Ralink RT5370 Wireless Adapter                                | 3        | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3        | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3        | 1.03%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 3        | 1.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 2        | 0.69%   |
| TP-Link Archer T4U ver.3                                      | 2        | 0.69%   |
| TP-Link 802.11n NIC                                           | 2        | 0.69%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter           | 2        | 0.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 2        | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2        | 0.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 2        | 0.69%   |
| Ralink MT7601U Wireless Adapter                               | 2        | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                               | 2        | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2        | 0.69%   |
| Intel Wireless 8265 / 8275                                    | 2        | 0.69%   |
| ASUS 802.11ac NIC                                             | 2        | 0.69%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                      | 1        | 0.34%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 263      | 57.42%  |
| Intel                      | 151      | 32.97%  |
| Qualcomm Atheros           | 17       | 3.71%   |
| Aquantia                   | 5        | 1.09%   |
| Xiaomi                     | 3        | 0.66%   |
| Samsung Electronics        | 2        | 0.44%   |
| Qualcomm                   | 2        | 0.44%   |
| Motorola PCS               | 2        | 0.44%   |
| Broadcom                   | 2        | 0.44%   |
| ZTE WCDMA Technologies MSM | 1        | 0.22%   |
| T & A Mobile Phones        | 1        | 0.22%   |
| OPPO Electronics           | 1        | 0.22%   |
| Nvidia                     | 1        | 0.22%   |
| Mellanox Technologies      | 1        | 0.22%   |
| MediaTek                   | 1        | 0.22%   |
| ICS Advent                 | 1        | 0.22%   |
| DisplayLink                | 1        | 0.22%   |
| D-Link                     | 1        | 0.22%   |
| Broadcom Limited           | 1        | 0.22%   |
| ASIX Electronics           | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Desktops | Percent |
|---------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 195      | 41.4%   |
| Realtek RTL8125 2.5GbE Controller                                               | 70       | 14.86%  |
| Intel I211 Gigabit Network Connection                                           | 38       | 8.07%   |
| Intel Ethernet Controller I225-V                                                | 38       | 8.07%   |
| Intel Ethernet Connection (7) I219-V                                            | 18       | 3.82%   |
| Intel Ethernet Connection (2) I219-V                                            | 8        | 1.7%    |
| Intel Ethernet Connection (2) I218-V                                            | 8        | 1.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 8        | 1.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                   | 6        | 1.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 5        | 1.06%   |
| Intel 82579V Gigabit Network Connection                                         | 5        | 1.06%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 4        | 0.85%   |
| Intel Ethernet Connection I217-LM                                               | 4        | 0.85%   |
| Intel Ethernet Connection (12) I219-V                                           | 4        | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 3        | 0.64%   |
| Intel Ethernet Connection I217-V                                                | 3        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                           | 3        | 0.64%   |
| Intel Ethernet Connection (17) I219-V                                           | 3        | 0.64%   |
| Intel Ethernet Connection (14) I219-V                                           | 3        | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                                   | 2        | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 2        | 0.42%   |
| Motorola PCS moto g52                                                           | 2        | 0.42%   |
| Intel I210 Gigabit Network Connection                                           | 2        | 0.42%   |
| Intel Ethernet Connection (11) I219-V                                           | 2        | 0.42%   |
| Aquantia AQtion AQC113CS NBase-T/IEEE 802.3an Ethernet Controller [Antigua 10G] | 2        | 0.42%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]  | 2        | 0.42%   |
| ZTE WCDMA MSM Unisoc Phone                                                      | 1        | 0.21%   |
| T & A Mobile Phones TCL 30 XE 5G                                                | 1        | 0.21%   |
| Realtek RTL8150 Fast Ethernet Adapter                                           | 1        | 0.21%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller               | 1        | 0.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 1        | 0.21%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 1        | 0.21%   |
| Realtek Killer E3000 2.5GbE Controller                                          | 1        | 0.21%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                       | 1        | 0.21%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                       | 1        | 0.21%   |
| Qualcomm Android                                                                | 1        | 0.21%   |
| Qualcomm A0001                                                                  | 1        | 0.21%   |
| OPPO SM8350-IDP _SN:361A1B3C                                                    | 1        | 0.21%   |
| Nvidia MCP61 Ethernet                                                           | 1        | 0.21%   |
| Mellanox MT27500 Family [ConnectX-3]                                            | 1        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 423      | 61.84%  |
| WiFi     | 254      | 37.13%  |
| Modem    | 4        | 0.58%   |
| Unknown  | 3        | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 323      | 73.08%  |
| WiFi     | 119      | 26.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 223      | 52.1%   |
| 2     | 180      | 42.06%  |
| 3     | 20       | 4.67%   |
| 0     | 3        | 0.7%    |
| 6     | 1        | 0.23%   |
| 4     | 1        | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 272      | 63.4%   |
| Yes  | 157      | 36.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 110      | 46.03%  |
| Cambridge Silicon Radio         | 42       | 17.57%  |
| MediaTek                        | 25       | 10.46%  |
| Realtek Semiconductor           | 10       | 4.18%   |
| ASUSTek Computer                | 10       | 4.18%   |
| Broadcom                        | 9        | 3.77%   |
| Foxconn / Hon Hai               | 7        | 2.93%   |
| TP-Link                         | 6        | 2.51%   |
| Qualcomm Atheros Communications | 6        | 2.51%   |
| IMC Networks                    | 5        | 2.09%   |
| Edimax Technology               | 2        | 0.84%   |
| Actions                         | 2        | 0.84%   |
| Lite-On Technology              | 1        | 0.42%   |
| Integrated System Solution      | 1        | 0.42%   |
| Dynex                           | 1        | 0.42%   |
| Dell                            | 1        | 0.42%   |
| Unknown                         | 1        | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                    | 42       | 17.5%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 42       | 17.5%   |
| MediaTek Wireless_Device                                 | 25       | 10.42%  |
| Intel AX210 Bluetooth                                    | 15       | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                         | 13       | 5.42%   |
| Intel Bluetooth wireless interface                       | 10       | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 9        | 3.75%   |
| Realtek Bluetooth Radio                                  | 8        | 3.33%   |
| Intel AX201 Bluetooth                                    | 8        | 3.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 7        | 2.92%   |
| TP-Link UB500 Adapter                                    | 6        | 2.5%    |
| Intel Bluetooth Device                                   | 6        | 2.5%    |
| Foxconn / Hon Hai Wireless_Device                        | 6        | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 6        | 2.5%    |
| ASUS ASUS USB-BT500                                      | 6        | 2.5%    |
| Qualcomm Atheros Bluetooth USB Host Controller           | 3        | 1.25%   |
| IMC Networks Wireless_Device                             | 3        | 1.25%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 2        | 0.83%   |
| IMC Networks Bluetooth Radio                             | 2        | 0.83%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter  | 2        | 0.83%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 0.83%   |
| Actions general adapter                                  | 2        | 0.83%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 0.42%   |
| Lite-On Bluetooth Radio                                  | 1        | 0.42%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.42%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.42%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1        | 0.42%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.42%   |
| Dell Broadcom BCM20702A0 Bluetooth                       | 1        | 0.42%   |
| Broadcom Bluetooth Device                                | 1        | 0.42%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 0.42%   |
| Broadcom BCM2045 Bluetooth                               | 1        | 0.42%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 0.42%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 0.42%   |
| Unknown                                                  | 1        | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 294      | 32.96%  |
| Intel                      | 185      | 20.74%  |
| Nvidia                     | 184      | 20.63%  |
| C-Media Electronics        | 33       | 3.7%    |
| Logitech                   | 28       | 3.14%   |
| Kingston Technology        | 14       | 1.57%   |
| Creative Labs              | 14       | 1.57%   |
| ASUSTek Computer           | 13       | 1.46%   |
| Razer USA                  | 10       | 1.12%   |
| SteelSeries ApS            | 8        | 0.9%    |
| JMTek                      | 7        | 0.78%   |
| Texas Instruments          | 6        | 0.67%   |
| Realtek Semiconductor      | 6        | 0.67%   |
| Creative Technology        | 6        | 0.67%   |
| Samson Technologies        | 5        | 0.56%   |
| Plantronics                | 5        | 0.56%   |
| Micro Star International   | 5        | 0.56%   |
| Focusrite-Novation         | 5        | 0.56%   |
| Corsair                    | 5        | 0.56%   |
| SAVITECH                   | 3        | 0.34%   |
| Blue Microphones           | 3        | 0.34%   |
| BEHRINGER International    | 3        | 0.34%   |
| Audio-Technica             | 3        | 0.34%   |
| Astro Gaming               | 3        | 0.34%   |
| Sony                       | 2        | 0.22%   |
| ROCCAT                     | 2        | 0.22%   |
| PreSonus Audio Electronics | 2        | 0.22%   |
| ONN                        | 2        | 0.22%   |
| Hewlett-Packard            | 2        | 0.22%   |
| GN Netcom                  | 2        | 0.22%   |
| Cambridge Silicon Radio    | 2        | 0.22%   |
| Asahi Kasei Microsystems   | 2        | 0.22%   |
| Unknown                    | 2        | 0.22%   |
| VIA Technologies           | 1        | 0.11%   |
| Turtle Beach               | 1        | 0.11%   |
| Trust                      | 1        | 0.11%   |
| Tenx Technology            | 1        | 0.11%   |
| Solid State System         | 1        | 0.11%   |
| Positive Grid              | 1        | 0.11%   |
| Ploopy                     | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                                        | 109      | 10.01%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 78       | 7.16%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 57       | 5.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 47       | 4.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 30       | 2.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 28       | 2.57%   |
| Intel Cannon Lake PCH cAVS                                                                      | 23       | 2.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 22       | 2.02%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 20       | 1.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 20       | 1.84%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 19       | 1.74%   |
| AMD Navi 31 HDMI/DP Audio                                                                       | 19       | 1.74%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 18       | 1.65%   |
| AMD Navi 10 HDMI Audio                                                                          | 18       | 1.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 17       | 1.56%   |
| Intel 200 Series PCH HD Audio                                                                   | 17       | 1.56%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 16       | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 16       | 1.47%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 15       | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 15       | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 14       | 1.29%   |
| ASUSTek Computer USB Audio                                                                      | 13       | 1.19%   |
| Nvidia TU104 HD Audio Controller                                                                | 12       | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 12       | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                                                   | 11       | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 11       | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                                                   | 11       | 1.01%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 11       | 1.01%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 9        | 0.83%   |
| C-Media Electronics USB Audio Device                                                            | 9        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 8        | 0.73%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 8        | 0.73%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 8        | 0.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 8        | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 8        | 0.73%   |
| Logitech PRO X Wireless Gaming Headset                                                          | 7        | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 7        | 0.64%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 7        | 0.64%   |
| AMD FCH Azalia Controller                                                                       | 7        | 0.64%   |
| Kingston Technology HyperX 7.1 Audio                                                            | 6        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 21       | 23.86%  |
| G.Skill             | 17       | 19.32%  |
| Kingston            | 14       | 15.91%  |
| Samsung Electronics | 7        | 7.95%   |
| Crucial             | 7        | 7.95%   |
| Unknown             | 5        | 5.68%   |
| Team                | 5        | 5.68%   |
| SK hynix            | 3        | 3.41%   |
| A-DATA Technology   | 3        | 3.41%   |
| Ramaxel Technology  | 1        | 1.14%   |
| Micron Technology   | 1        | 1.14%   |
| Hewlett-Packard     | 1        | 1.14%   |
| GOODRAM             | 1        | 1.14%   |
| Asgard              | 1        | 1.14%   |
| Unknown             | 1        | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 5        | 5.32%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s     | 3        | 3.19%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s               | 2        | 2.13%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s    | 2        | 2.13%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s       | 2        | 2.13%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s    | 2        | 2.13%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 2        | 2.13%   |
| Corsair RAM CMY16GX3M2A1866C9 8GB DIMM DDR3 2400MT/s    | 2        | 2.13%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s   | 2        | 2.13%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s  | 2        | 2.13%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 1.06%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 1.06%   |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s  | 1        | 1.06%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s      | 1        | 1.06%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s      | 1        | 1.06%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s     | 1        | 1.06%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s     | 1        | 1.06%   |
| Team RAM TEAMGROUP-UD3 8GB DIMM DDR3 1600MT/s           | 1        | 1.06%   |
| SK hynix RAM Module 4GB DIMM DDR4 2400MT/s              | 1        | 1.06%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 1.06%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.06%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s               | 1        | 1.06%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s     | 1        | 1.06%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 1.06%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s   | 1        | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 1.06%   |
| Samsung RAM M392B2G70BM0 16GB DIMM DDR3 1333MT/s        | 1        | 1.06%   |
| Samsung RAM M392B2G70AM0 16GB DIMM DDR3 1333MT/s        | 1        | 1.06%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s     | 1        | 1.06%   |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s     | 1        | 1.06%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s   | 1        | 1.06%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.06%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2933MT/s    | 1        | 1.06%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s     | 1        | 1.06%   |
| Kingston RAM KF560C36-16 16GB DIMM DDR5 6000MT/s        | 1        | 1.06%   |
| Kingston RAM KF560C32-16 16GB DIMM DDR5 6000MT/s        | 1        | 1.06%   |
| Kingston RAM KF552C40-16 16GB DIMM DDR5 5200MT/s        | 1        | 1.06%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 1        | 1.06%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s   | 1        | 1.06%   |
| Kingston RAM CL16-18-18 D4-3200 16GB DIMM DDR4 3200MT/s | 1        | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 52       | 65%     |
| DDR3    | 15       | 18.75%  |
| DDR5    | 10       | 12.5%   |
| SDRAM   | 1        | 1.25%   |
| LPDDR4  | 1        | 1.25%   |
| Unknown | 1        | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 78       | 97.5%   |
| SODIMM       | 1        | 1.25%   |
| Row Of Chips | 1        | 1.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 37       | 44.05%  |
| 16384 | 25       | 29.76%  |
| 32768 | 10       | 11.9%   |
| 4096  | 6        | 7.14%   |
| 2048  | 5        | 5.95%   |
| 1024  | 1        | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 14       | 16.09%  |
| 3200  | 12       | 13.79%  |
| 1600  | 9        | 10.34%  |
| 3733  | 6        | 6.9%    |
| 6000  | 5        | 5.75%   |
| 2400  | 5        | 5.75%   |
| 1333  | 4        | 4.6%    |
| 3866  | 3        | 3.45%   |
| 3800  | 3        | 3.45%   |
| 2667  | 3        | 3.45%   |
| 5600  | 2        | 2.3%    |
| 3534  | 2        | 2.3%    |
| 3466  | 2        | 2.3%    |
| 2933  | 2        | 2.3%    |
| 1066  | 2        | 2.3%    |
| 5800  | 1        | 1.15%   |
| 5200  | 1        | 1.15%   |
| 4800  | 1        | 1.15%   |
| 4267  | 1        | 1.15%   |
| 3933  | 1        | 1.15%   |
| 3533  | 1        | 1.15%   |
| 3400  | 1        | 1.15%   |
| 3334  | 1        | 1.15%   |
| 3266  | 1        | 1.15%   |
| 3100  | 1        | 1.15%   |
| 3066  | 1        | 1.15%   |
| 2800  | 1        | 1.15%   |
| 800   | 1        | 1.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 4        | 30.77%  |
| Brother Industries | 4        | 30.77%  |
| Hewlett-Packard    | 2        | 15.38%  |
| STMicroelectronics | 1        | 7.69%   |
| Seiko Epson        | 1        | 7.69%   |
| Dell               | 1        | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 7.69%   |
| Seiko Epson XP-2100 Series                                | 1        | 7.69%   |
| HP DeskJet Plus 4100 series                               | 1        | 7.69%   |
| HP Color LaserJet CP1215                                  | 1        | 7.69%   |
| Dell 1130 Laser Printer                                   | 1        | 7.69%   |
| Canon TS700 series                                        | 1        | 7.69%   |
| Canon TR4500 series                                       | 1        | 7.69%   |
| Canon PIXMA MX370 Series                                  | 1        | 7.69%   |
| Canon G2000 series                                        | 1        | 7.69%   |
| Brother MFC-L2710DN series                                | 1        | 7.69%   |
| Brother HL-L2370DW series                                 | 1        | 7.69%   |
| Brother HL-L2320D series                                  | 1        | 7.69%   |
| Brother DCP-1510                                          | 1        | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Canon           | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| HP ScanJet 2400c              | 1        | 50%     |
| Canon CanoScan N1240U/LiDE 30 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 26       | 30.59%  |
| Microsoft                     | 8        | 9.41%   |
| Microdia                      | 8        | 9.41%   |
| Apple                         | 7        | 8.24%   |
| Sunplus Innovation Technology | 3        | 3.53%   |
| Generalplus Technology        | 3        | 3.53%   |
| ARC International             | 3        | 3.53%   |
| webcamvendor                  | 2        | 2.35%   |
| Samsung Electronics           | 2        | 2.35%   |
| Razer USA                     | 2        | 2.35%   |
| MacroSilicon                  | 2        | 2.35%   |
| Hewlett-Packard               | 2        | 2.35%   |
| Elgato Systems                | 2        | 2.35%   |
| Chicony Electronics           | 2        | 2.35%   |
| YGTek                         | 1        | 1.18%   |
| WCM_USB                       | 1        | 1.18%   |
| SunplusIT                     | 1        | 1.18%   |
| Owon                          | 1        | 1.18%   |
| Minton Optic Industry         | 1        | 1.18%   |
| lihappe8                      | 1        | 1.18%   |
| Lenovo                        | 1        | 1.18%   |
| KYE Systems (Mouse Systems)   | 1        | 1.18%   |
| EVGA                          | 1        | 1.18%   |
| Cubeternet                    | 1        | 1.18%   |
| Creative Technology           | 1        | 1.18%   |
| AVerMedia Technologies        | 1        | 1.18%   |
| ANYKA                         | 1        | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                  | 7        | 8.24%   |
| Logitech C922 Pro Stream Webcam                              | 7        | 8.24%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                           | 7        | 8.24%   |
| Logitech Webcam C270                                         | 4        | 4.71%   |
| Microsoft LifeCam Cinema                                     | 3        | 3.53%   |
| Microdia USB 2.0 Camera                                      | 3        | 3.53%   |
| Microdia Integrated Camera                                   | 3        | 3.53%   |
| Logitech StreamCam                                           | 3        | 3.53%   |
| ARC International Camera                                     | 3        | 3.53%   |
| webcamvendor webcamproduct                                   | 2        | 2.35%   |
| Sunplus Full HD webcam                                       | 2        | 2.35%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 2        | 2.35%   |
| Razer USA Gaming Webcam [Kiyo]                               | 2        | 2.35%   |
| MacroSilicon USB3. 0 capture                                 | 2        | 2.35%   |
| Logitech C920 PRO HD Webcam                                  | 2        | 2.35%   |
| Generalplus 808 Camera                                       | 2        | 2.35%   |
| Elgato Systems Elgato Facecam                                | 2        | 2.35%   |
| YGTek Webcam                                                 | 1        | 1.18%   |
| WCM_USB WEB CAM                                              | 1        | 1.18%   |
| SunplusIT Umax Webcam W5                                     | 1        | 1.18%   |
| Sunplus Sandberg USB Webcam Pro                              | 1        | 1.18%   |
| Owon USB CAMERA                                              | 1        | 1.18%   |
| Minton Optic Industry S-Cam F5/D-Link DSC-350 Digital Camera | 1        | 1.18%   |
| Microsoft Xbox NUI Camera                                    | 1        | 1.18%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks          | 1        | 1.18%   |
| Microsoft LifeCam VX-800                                     | 1        | 1.18%   |
| Microsoft LifeCam Studio                                     | 1        | 1.18%   |
| Microsoft LifeCam HD-3000                                    | 1        | 1.18%   |
| Microdia Webcam Vitade AF                                    | 1        | 1.18%   |
| Microdia USB Live camera                                     | 1        | 1.18%   |
| Logitech QuickCam Pro 9000                                   | 1        | 1.18%   |
| Logitech HD Webcam C910                                      | 1        | 1.18%   |
| Logitech BRIO 4K Stream Edition                              | 1        | 1.18%   |
| lihappe8 USB 2.0 Camera                                      | 1        | 1.18%   |
| Lenovo Lenovo 500 RGB Camera                                 | 1        | 1.18%   |
| KYE Systems (Mouse Systems) Genius Webcam                    | 1        | 1.18%   |
| HP Webcam HD-2200                                            | 1        | 1.18%   |
| HP Webcam HD 2300                                            | 1        | 1.18%   |
| Generalplus GENERAL WEBCAM                                   | 1        | 1.18%   |
| EVGA XR1 Capture Box                                         | 1        | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 357      | 82.26%  |
| 1     | 69       | 15.9%   |
| 2     | 7        | 1.61%   |
| 3     | 1        | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 38       | 45.24%  |
| Graphics card            | 26       | 30.95%  |
| Unassigned class         | 5        | 5.95%   |
| Multimedia controller    | 5        | 5.95%   |
| Sound                    | 3        | 3.57%   |
| Net/ethernet             | 2        | 2.38%   |
| Camera                   | 2        | 2.38%   |
| Fingerprint reader       | 1        | 1.19%   |
| Communication controller | 1        | 1.19%   |
| Card reader              | 1        | 1.19%   |

