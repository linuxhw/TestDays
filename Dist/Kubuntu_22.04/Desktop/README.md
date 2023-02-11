Kubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 277

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | NO DPK                      | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| HP            | 3397                        | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Gigabyte      | X570S AORUS MASTER          | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [1a619ff898](https://linux-hardware.org/?probe=1a619ff898) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| Dell          | 0WPMFG A00                  | [02a8ab8bdc](https://linux-hardware.org/?probe=02a8ab8bdc) | Jan 05, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [54403a8bbf](https://linux-hardware.org/?probe=54403a8bbf) | Jan 02, 2023 |
| ASUSTek       | G10DK                       | [e75694d9a6](https://linux-hardware.org/?probe=e75694d9a6) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| Dell          | 0PTTT9 A00                  | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| HP            | 8399                        | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| MSI           | X470 GAMING PLUS            | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| Dell          | 084J0R A00                  | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| Lenovo        | NOK                         | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| ASUSTek       | H170-PRO                    | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| ASRock        | B450M Pro4                  | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| Dell          | 084J0R A00                  | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Gigabyte      | H97-HD3                     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Gigabyte      | H110M-S2H-CF                | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Unknown       | Unknown                     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| Gigabyte      | H97-HD3                     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| Supermicro    | X9DAL                       | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASRock        | X99 Extreme4                | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Dell          | 0773VG A00                  | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| Gigabyte      | B660M D3H DDR4              | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Shuttle       | FH61R                       | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 844C                        | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-P                | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| Gigabyte      | B365M D2V                   | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| MSI           | A320M PRO-M2 V2             | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| MSI           | H110M PRO-D                 | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| JWIPC         | A320I S1                    | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| Gigabyte      | Z68XP-UD3                   | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Gigabyte      | P55-US3L                    | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| Acer          | Aspire G7750                | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Apple         | Mac-F221BEC8                | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| ASUSTek       | PRIME B450M-K II            | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Dell          | 042P49 A02                  | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| Dell          | 0GY6Y8 A02                  | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Acer          | Aspire G7750                | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| ASUSTek       | Z97-K                       | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| ASRock        | H470M-HVS                   | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| MSI           | B450-A PRO MAX              | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Pegatron      | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| ASRock        | B450M/ac R2.0               | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| MSI           | B450-A PRO                  | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| MSI           | B350 PC MATE                | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| MSI           | B350 PC MATE                | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Dell          | 0C2XKD A01                  | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| HP            | 8459                        | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek       | P8H67                       | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| ASUSTek       | GRYPHON Z87                 | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| HP            | 18E9                        | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| ASUSTek       | P9X79 PRO                   | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| HP            | 8459                        | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| ASRock        | A320M Pro4                  | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| ABIT          | IP35 Pro                    | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| ASUSTek       | P8P67 LE                    | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| ASRock        | X570M Pro4                  | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| ASUSTek       | X99-A/USB                   | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | 0KC9NP A01                  | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| AZW           | Gemini J45                  | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| ASUSTek       | M5A78L LE                   | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek       | P7H55-M LE                  | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| Gigabyte      | B85M-D2V                    | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| ASRock        | B560M Pro4                  | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| ASUSTek       | M5A78L LE                   | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| Dell          | 0KJCC5 A00                  | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| MSI           | B450M PRO-M2                | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| Lenovo        | SHARKBAY NOK                | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Gigabyte      | X570 GAMING X               | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| ASUSTek       | PRIME B550M-K               | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Biostar       | A68N-2100K                  | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP            | 0AACh                       | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Dell          | 0K240Y A02                  | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Gigabyte      | H410M S2H V3                | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Gigabyte      | B550M DS3H                  | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| Gigabyte      | P35-DS3L                    | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.15.0-56-generic          | 22       | 9.69%   |
| 5.15.0-52-generic          | 19       | 8.37%   |
| 5.15.0-43-generic          | 17       | 7.49%   |
| 5.15.0-48-generic          | 14       | 6.17%   |
| 5.15.0-47-generic          | 12       | 5.29%   |
| 5.15.0-46-generic          | 12       | 5.29%   |
| 5.15.0-27-generic          | 12       | 5.29%   |
| 5.15.0-40-generic          | 11       | 4.85%   |
| 5.15.0-41-generic          | 10       | 4.41%   |
| 5.15.0-53-generic          | 9        | 3.96%   |
| 5.15.0-58-generic          | 8        | 3.52%   |
| 5.15.0-50-generic          | 7        | 3.08%   |
| 5.15.0-25-generic          | 7        | 3.08%   |
| 5.15.0-30-generic          | 6        | 2.64%   |
| 5.15.0-48-lowlatency       | 5        | 2.2%    |
| 5.15.0-56-lowlatency       | 4        | 1.76%   |
| 5.15.0-37-generic          | 4        | 1.76%   |
| 5.15.0-33-generic          | 4        | 1.76%   |
| 5.15.0-57-generic          | 3        | 1.32%   |
| 5.15.0-27-lowlatency       | 3        | 1.32%   |
| 5.15.0-52-lowlatency       | 2        | 0.88%   |
| 5.15.0-47-lowlatency       | 2        | 0.88%   |
| 5.15.0-43-lowlatency       | 2        | 0.88%   |
| 5.15.0-39-generic          | 2        | 0.88%   |
| 6.1.5-x64v3-xanmod1        | 1        | 0.44%   |
| 6.0.1-060001-generic       | 1        | 0.44%   |
| 6.0.0                      | 1        | 0.44%   |
| 5.4.0-122-generic          | 1        | 0.44%   |
| 5.19.12-xanmod1            | 1        | 0.44%   |
| 5.18.4-xanmod1             | 1        | 0.44%   |
| 5.18.4-vitodoc             | 1        | 0.44%   |
| 5.18.12-051812-generic     | 1        | 0.44%   |
| 5.18.10-051810-generic     | 1        | 0.44%   |
| 5.17.6-051706-generic      | 1        | 0.44%   |
| 5.17.14-xanmod1            | 1        | 0.44%   |
| 5.17.0-12.1-liquorix-amd64 | 1        | 0.44%   |
| 5.17.0-1021-oem            | 1        | 0.44%   |
| 5.17.0-1017-oem            | 1        | 0.44%   |
| 5.17.0-051700-generic      | 1        | 0.44%   |
| 5.16.0-051600rc3-generic   | 1        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 197      | 91.2%   |
| 5.17.0  | 4        | 1.85%   |
| 5.18.4  | 2        | 0.93%   |
| 5.13.0  | 2        | 0.93%   |
| 6.1.5   | 1        | 0.46%   |
| 6.0.1   | 1        | 0.46%   |
| 6.0.0   | 1        | 0.46%   |
| 5.4.0   | 1        | 0.46%   |
| 5.19.12 | 1        | 0.46%   |
| 5.18.12 | 1        | 0.46%   |
| 5.18.10 | 1        | 0.46%   |
| 5.17.6  | 1        | 0.46%   |
| 5.17.14 | 1        | 0.46%   |
| 5.16.0  | 1        | 0.46%   |
| 5.15.13 | 1        | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 198      | 91.67%  |
| 5.17    | 6        | 2.78%   |
| 5.18    | 4        | 1.85%   |
| 6.0     | 2        | 0.93%   |
| 5.13    | 2        | 0.93%   |
| 6.1     | 1        | 0.46%   |
| 5.4     | 1        | 0.46%   |
| 5.19    | 1        | 0.46%   |
| 5.16    | 1        | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 214      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| KDE5   | 212      | 99.07%  |
| GNOME  | 1        | 0.47%   |
| Budgie | 1        | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 206      | 96.26%  |
| Wayland | 4        | 1.87%   |
| Tty     | 3        | 1.4%    |
| Web     | 1        | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 148      | 68.52%  |
| Unknown | 47       | 21.76%  |
| GDM3    | 14       | 6.48%   |
| LightDM | 7        | 3.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Desktops | Percent |
|--------|----------|---------|
| en_US  | 101      | 47.2%   |
| fr_FR  | 20       | 9.35%   |
| de_DE  | 15       | 7.01%   |
| it_IT  | 11       | 5.14%   |
| ru_RU  | 10       | 4.67%   |
| en_GB  | 9        | 4.21%   |
| en_AU  | 8        | 3.74%   |
| pt_BR  | 5        | 2.34%   |
| pl_PL  | 3        | 1.4%    |
| en_CA  | 3        | 1.4%    |
| nl_NL  | 2        | 0.93%   |
| es_ES  | 2        | 0.93%   |
| es_AR  | 2        | 0.93%   |
| en_ZA  | 2        | 0.93%   |
| en_PH  | 2        | 0.93%   |
| en_NZ  | 2        | 0.93%   |
| en_IN  | 2        | 0.93%   |
| cs_CZ  | 2        | 0.93%   |
| C      | 2        | 0.93%   |
| sl_SI  | 1        | 0.47%   |
| osa_US | 1        | 0.47%   |
| fr_BE  | 1        | 0.47%   |
| fi_FI  | 1        | 0.47%   |
| es_CO  | 1        | 0.47%   |
| en_IL  | 1        | 0.47%   |
| en_AG  | 1        | 0.47%   |
| el_GR  | 1        | 0.47%   |
| de_LU  | 1        | 0.47%   |
| de_CH  | 1        | 0.47%   |
| de_AT  | 1        | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 126      | 58.6%   |
| EFI  | 89       | 41.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 189      | 88.32%  |
| Btrfs   | 12       | 5.61%   |
| Overlay | 11       | 5.14%   |
| Xfs     | 1        | 0.47%   |
| Ext3    | 1        | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 122      | 55.96%  |
| Unknown | 77       | 35.32%  |
| MBR     | 19       | 8.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 182      | 83.87%  |
| Yes       | 35       | 16.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 129      | 60.28%  |
| Yes       | 85       | 39.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 58       | 27.1%   |
| Gigabyte Technology | 42       | 19.63%  |
| MSI                 | 31       | 14.49%  |
| ASRock              | 21       | 9.81%   |
| Dell                | 19       | 8.88%   |
| Lenovo              | 10       | 4.67%   |
| Hewlett-Packard     | 8        | 3.74%   |
| Supermicro          | 4        | 1.87%   |
| Acer                | 3        | 1.4%    |
| Shuttle             | 2        | 0.93%   |
| Fujitsu             | 2        | 0.93%   |
| Biostar             | 2        | 0.93%   |
| Apple               | 2        | 0.93%   |
| Positivo            | 1        | 0.47%   |
| Pegatron            | 1        | 0.47%   |
| OEM                 | 1        | 0.47%   |
| JWIPC               | 1        | 0.47%   |
| Huanan              | 1        | 0.47%   |
| Foxconn             | 1        | 0.47%   |
| BESSTAR Tech        | 1        | 0.47%   |
| AZW                 | 1        | 0.47%   |
| ABIT                | 1        | 0.47%   |
| Unknown             | 1        | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 7        | 3.27%   |
| ASUS ROG STRIX B550-F GAMING   | 5        | 2.34%   |
| MSI MS-7B79                    | 4        | 1.87%   |
| Gigabyte B450M DS3H            | 3        | 1.4%    |
| Dell OptiPlex 7010             | 3        | 1.4%    |
| Supermicro SKAGIT09            | 2        | 0.93%   |
| MSI MS-7C95                    | 2        | 0.93%   |
| MSI MS-7C56                    | 2        | 0.93%   |
| MSI MS-7B86                    | 2        | 0.93%   |
| MSI MS-7B84                    | 2        | 0.93%   |
| Gigabyte X570 GAMING X         | 2        | 0.93%   |
| Gigabyte B450 I AORUS PRO WIFI | 2        | 0.93%   |
| Dell OptiPlex 7040             | 2        | 0.93%   |
| ASUS STRIX Z270E GAMING        | 2        | 0.93%   |
| ASUS ROG ZENITH EXTREME        | 2        | 0.93%   |
| ASUS ROG STRIX X570-E GAMING   | 2        | 0.93%   |
| ASUS ROG STRIX B550-I GAMING   | 2        | 0.93%   |
| ASRock B450M Pro4              | 2        | 0.93%   |
| ASRock A320M-HDV R4.0          | 2        | 0.93%   |
| Supermicro X9DAL               | 1        | 0.47%   |
| Supermicro X8ST3               | 1        | 0.47%   |
| Shuttle SH61R                  | 1        | 0.47%   |
| Shuttle NC01U                  | 1        | 0.47%   |
| Positivo POS-PARS760GCD        | 1        | 0.47%   |
| Pegatron p6740la               | 1        | 0.47%   |
| OEM G41 775 ICH7 8712          | 1        | 0.47%   |
| MSI MS-7D54                    | 1        | 0.47%   |
| MSI MS-7D09                    | 1        | 0.47%   |
| MSI MS-7C80                    | 1        | 0.47%   |
| MSI MS-7C71                    | 1        | 0.47%   |
| MSI MS-7C37                    | 1        | 0.47%   |
| MSI MS-7B98                    | 1        | 0.47%   |
| MSI MS-7B89                    | 1        | 0.47%   |
| MSI MS-7B61                    | 1        | 0.47%   |
| MSI MS-7B17                    | 1        | 0.47%   |
| MSI MS-7A78                    | 1        | 0.47%   |
| MSI MS-7A40                    | 1        | 0.47%   |
| MSI MS-7A38                    | 1        | 0.47%   |
| MSI MS-7A34                    | 1        | 0.47%   |
| MSI MS-7A32                    | 1        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS ROG                | 17       | 7.94%   |
| Dell OptiPlex           | 10       | 4.67%   |
| ASUS PRIME              | 9        | 4.21%   |
| Lenovo ThinkCentre      | 7        | 3.27%   |
| ASUS All                | 7        | 3.27%   |
| ASUS TUF                | 6        | 2.8%    |
| MSI MS-7B79             | 4        | 1.87%   |
| Gigabyte X570           | 4        | 1.87%   |
| Dell Precision          | 4        | 1.87%   |
| Gigabyte B450M          | 3        | 1.4%    |
| Gigabyte B450           | 3        | 1.4%    |
| Dell XPS                | 3        | 1.4%    |
| ASUS STRIX              | 3        | 1.4%    |
| ASUS M5A78L-M           | 3        | 1.4%    |
| ASRock B450M            | 3        | 1.4%    |
| ASRock A320M-HDV        | 3        | 1.4%    |
| Supermicro SKAGIT09     | 2        | 0.93%   |
| MSI MS-7C95             | 2        | 0.93%   |
| MSI MS-7C56             | 2        | 0.93%   |
| MSI MS-7B86             | 2        | 0.93%   |
| MSI MS-7B84             | 2        | 0.93%   |
| Lenovo IdeaCentre       | 2        | 0.93%   |
| HP ProDesk              | 2        | 0.93%   |
| HP Compaq               | 2        | 0.93%   |
| Gigabyte H410M          | 2        | 0.93%   |
| Gigabyte B660M          | 2        | 0.93%   |
| Gigabyte B365M          | 2        | 0.93%   |
| Fujitsu ESPRIMO         | 2        | 0.93%   |
| Dell Inspiron           | 2        | 0.93%   |
| ASRock B550             | 2        | 0.93%   |
| Acer Aspire             | 2        | 0.93%   |
| Supermicro X9DAL        | 1        | 0.47%   |
| Supermicro X8ST3        | 1        | 0.47%   |
| Shuttle SH61R           | 1        | 0.47%   |
| Shuttle NC01U           | 1        | 0.47%   |
| Positivo POS-PARS760GCD | 1        | 0.47%   |
| Pegatron p6740la        | 1        | 0.47%   |
| OEM G41                 | 1        | 0.47%   |
| MSI MS-7D54             | 1        | 0.47%   |
| MSI MS-7D09             | 1        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 33       | 15.42%  |
| 2020 | 28       | 13.08%  |
| 2019 | 26       | 12.15%  |
| 2021 | 19       | 8.88%   |
| 2014 | 17       | 7.94%   |
| 2017 | 14       | 6.54%   |
| 2016 | 14       | 6.54%   |
| 2012 | 13       | 6.07%   |
| 2013 | 12       | 5.61%   |
| 2015 | 10       | 4.67%   |
| 2011 | 10       | 4.67%   |
| 2010 | 7        | 3.27%   |
| 2022 | 3        | 1.4%    |
| 2009 | 3        | 1.4%    |
| 2007 | 3        | 1.4%    |
| 2008 | 2        | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 214      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 211      | 98.6%   |
| Enabled  | 3        | 1.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 214      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 69       | 32.09%  |
| 32.01-64.0  | 59       | 27.44%  |
| 8.01-16.0   | 34       | 15.81%  |
| 64.01-256.0 | 18       | 8.37%   |
| 4.01-8.0    | 17       | 7.91%   |
| 3.01-4.0    | 12       | 5.58%   |
| 24.01-32.0  | 6        | 2.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 64       | 28.83%  |
| 4.01-8.0   | 54       | 24.32%  |
| 3.01-4.0   | 38       | 17.12%  |
| 1.01-2.0   | 37       | 16.67%  |
| 8.01-16.0  | 20       | 9.01%   |
| 16.01-24.0 | 5        | 2.25%   |
| 0.51-1.0   | 3        | 1.35%   |
| 32.01-64.0 | 1        | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 65       | 30.09%  |
| 1      | 56       | 25.93%  |
| 3      | 45       | 20.83%  |
| 4      | 19       | 8.8%    |
| 5      | 14       | 6.48%   |
| 6      | 9        | 4.17%   |
| 7      | 5        | 2.31%   |
| 11     | 1        | 0.46%   |
| 9      | 1        | 0.46%   |
| 8      | 1        | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 57.67%  |
| Yes       | 91       | 42.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 213      | 99.53%  |
| No        | 1        | 0.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 118      | 54.88%  |
| No        | 97       | 45.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 56.07%  |
| Yes       | 94       | 43.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 46       | 21.5%   |
| Germany      | 21       | 9.81%   |
| France       | 19       | 8.88%   |
| Italy        | 14       | 6.54%   |
| UK           | 10       | 4.67%   |
| Russia       | 10       | 4.67%   |
| Brazil       | 10       | 4.67%   |
| Poland       | 7        | 3.27%   |
| Netherlands  | 7        | 3.27%   |
| Australia    | 7        | 3.27%   |
| Canada       | 5        | 2.34%   |
| Spain        | 4        | 1.87%   |
| Finland      | 4        | 1.87%   |
| New Zealand  | 3        | 1.4%    |
| India        | 3        | 1.4%    |
| Argentina    | 3        | 1.4%    |
| Thailand     | 2        | 0.93%   |
| Switzerland  | 2        | 0.93%   |
| South Africa | 2        | 0.93%   |
| Slovenia     | 2        | 0.93%   |
| Serbia       | 2        | 0.93%   |
| Portugal     | 2        | 0.93%   |
| Philippines  | 2        | 0.93%   |
| Iran         | 2        | 0.93%   |
| Czechia      | 2        | 0.93%   |
| Bulgaria     | 2        | 0.93%   |
| Belgium      | 2        | 0.93%   |
| Austria      | 2        | 0.93%   |
| Vietnam      | 1        | 0.47%   |
| Ukraine      | 1        | 0.47%   |
| Turkey       | 1        | 0.47%   |
| Sweden       | 1        | 0.47%   |
| Romania      | 1        | 0.47%   |
| Mexico       | 1        | 0.47%   |
| Malta        | 1        | 0.47%   |
| Malaysia     | 1        | 0.47%   |
| Luxembourg   | 1        | 0.47%   |
| Kazakhstan   | 1        | 0.47%   |
| Israel       | 1        | 0.47%   |
| Indonesia    | 1        | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Munich         | 4        | 1.84%   |
| Rio de Janeiro | 3        | 1.38%   |
| Moscow         | 3        | 1.38%   |
| Milan          | 3        | 1.38%   |
| Dallas         | 3        | 1.38%   |
| Berlin         | 3        | 1.38%   |
| Wroclaw        | 2        | 0.92%   |
| Washington     | 2        | 0.92%   |
| Vienna         | 2        | 0.92%   |
| Turku          | 2        | 0.92%   |
| Sydney         | 2        | 0.92%   |
| Prague         | 2        | 0.92%   |
| New York       | 2        | 0.92%   |
| Montreal       | 2        | 0.92%   |
| Melbourne      | 2        | 0.92%   |
| London         | 2        | 0.92%   |
| Columbus       | 2        | 0.92%   |
| Canberra       | 2        | 0.92%   |
| Brasília      | 2        | 0.92%   |
| Bougival       | 2        | 0.92%   |
| Belgrade       | 2        | 0.92%   |
| Auckland       | 2        | 0.92%   |
| Amsterdam      | 2        | 0.92%   |
| Zaandam        | 1        | 0.46%   |
| Yerevan        | 1        | 0.46%   |
| Wheaton        | 1        | 0.46%   |
| Whangarei      | 1        | 0.46%   |
| Wembley        | 1        | 0.46%   |
| Waukee         | 1        | 0.46%   |
| Vrhnika        | 1        | 0.46%   |
| Volgograd      | 1        | 0.46%   |
| Vladivostok    | 1        | 0.46%   |
| Vitebsk        | 1        | 0.46%   |
| Villa Nueva    | 1        | 0.46%   |
| Varna          | 1        | 0.46%   |
| Valencia       | 1        | 0.46%   |
| Ustron         | 1        | 0.46%   |
| Union City     | 1        | 0.46%   |
| Turin          | 1        | 0.46%   |
| Torun          | 1        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Samsung Electronics         | 78       | 120    | 17.69%  |
| WDC                         | 76       | 114    | 17.23%  |
| Seagate                     | 68       | 117    | 15.42%  |
| Kingston                    | 33       | 39     | 7.48%   |
| Toshiba                     | 24       | 28     | 5.44%   |
| SanDisk                     | 22       | 24     | 4.99%   |
| Crucial                     | 17       | 21     | 3.85%   |
| Hitachi                     | 16       | 16     | 3.63%   |
| Intel                       | 8        | 8      | 1.81%   |
| Phison                      | 6        | 6      | 1.36%   |
| Patriot                     | 6        | 8      | 1.36%   |
| A-DATA Technology           | 6        | 7      | 1.36%   |
| Unknown                     | 5        | 8      | 1.13%   |
| HGST                        | 5        | 9      | 1.13%   |
| China                       | 4        | 5      | 0.91%   |
| Transcend                   | 3        | 4      | 0.68%   |
| PNY                         | 3        | 4      | 0.68%   |
| Phison Electronics          | 3        | 3      | 0.68%   |
| Micron Technology           | 3        | 3      | 0.68%   |
| Lexar                       | 3        | 3      | 0.68%   |
| Intenso                     | 3        | 4      | 0.68%   |
| Corsair                     | 3        | 4      | 0.68%   |
| T-FORCE                     | 2        | 2      | 0.45%   |
| SABRENT                     | 2        | 2      | 0.45%   |
| OCZ                         | 2        | 2      | 0.45%   |
| Micron/Crucial Technology   | 2        | 2      | 0.45%   |
| Maxtor                      | 2        | 2      | 0.45%   |
| KODAK                       | 2        | 2      | 0.45%   |
| Kingston Technology Company | 2        | 2      | 0.45%   |
| Emtec                       | 2        | 2      | 0.45%   |
| XPG                         | 1        | 1      | 0.23%   |
| Verbatim                    | 1        | 1      | 0.23%   |
| ValueTech                   | 1        | 1      | 0.23%   |
| USB3.0                      | 1        | 1      | 0.23%   |
| Team                        | 1        | 1      | 0.23%   |
| Smartbuy                    | 1        | 1      | 0.23%   |
| SK hynix                    | 1        | 3      | 0.23%   |
| Realtek Semiconductor       | 1        | 1      | 0.23%   |
| Plextor                     | 1        | 1      | 0.23%   |
| O2 Micro                    | 1        | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 9        | 1.72%   |
| Seagate ST4000DM004-2CV104 4TB                      | 8        | 1.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 7        | 1.34%   |
| Toshiba DT01ACA100 1TB                              | 5        | 0.96%   |
| SanDisk NVMe SSD Drive 500GB                        | 5        | 0.96%   |
| Samsung SSD 850 EVO 500GB                           | 5        | 0.96%   |
| Toshiba HDWD110 1TB                                 | 4        | 0.76%   |
| Samsung SSD 970 EVO Plus 1TB                        | 4        | 0.76%   |
| Samsung SSD 860 EVO 500GB                           | 4        | 0.76%   |
| Samsung SSD 860 EVO 1TB                             | 4        | 0.76%   |
| Samsung NVMe SSD Drive 500GB                        | 4        | 0.76%   |
| Kingston SA400S37480G 480GB SSD                     | 4        | 0.76%   |
| Kingston SA2000M81000G 1TB                          | 4        | 0.76%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 3        | 0.57%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 3        | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 0.57%   |
| Seagate ST4000VN008-2DR166 4TB                      | 3        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 0.57%   |
| SanDisk NVMe SSD Drive 1TB                          | 3        | 0.57%   |
| Samsung SSD 980 500GB                               | 3        | 0.57%   |
| Samsung SSD 980 1TB                                 | 3        | 0.57%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3        | 0.57%   |
| Samsung SSD 870 EVO 1TB                             | 3        | 0.57%   |
| Samsung SSD 850 EVO 120GB                           | 3        | 0.57%   |
| Samsung SSD 840 PRO Series 128GB                    | 3        | 0.57%   |
| Samsung HD103SI 1TB                                 | 3        | 0.57%   |
| Kingston SA400S37120G 120GB SSD                     | 3        | 0.57%   |
| Hitachi HTS547550A9E384 500GB                       | 3        | 0.57%   |
| Crucial CT500MX500SSD1 500GB                        | 3        | 0.57%   |
| Crucial CT240BX500SSD1 240GB                        | 3        | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2        | 0.38%   |
| WDC WDBNCE5000PNC 500GB SSD                         | 2        | 0.38%   |
| WDC WD5000AAKX-753CA1 500GB                         | 2        | 0.38%   |
| WDC WD5000AADS-00S9B0 500GB                         | 2        | 0.38%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 2        | 0.38%   |
| WDC WD40EZRX-00SPEB0 4TB                            | 2        | 0.38%   |
| WDC WD40EFAX-68JH4N1 4TB                            | 2        | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 2        | 0.38%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 2        | 0.38%   |
| Unknown SD/MMC 2GB                                  | 2        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 68       | 95     | 35.05%  |
| Seagate             | 63       | 107    | 32.47%  |
| Toshiba             | 21       | 24     | 10.82%  |
| Hitachi             | 16       | 16     | 8.25%   |
| Samsung Electronics | 14       | 15     | 7.22%   |
| HGST                | 5        | 9      | 2.58%   |
| SABRENT             | 2        | 2      | 1.03%   |
| USB3.0              | 1        | 1      | 0.52%   |
| Unknown             | 1        | 1      | 0.52%   |
| Maxtor              | 1        | 1      | 0.52%   |
| JMicron Technology  | 1        | 1      | 0.52%   |
| IET                 | 1        | 1      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 44       | 64     | 26.51%  |
| Kingston            | 27       | 29     | 16.27%  |
| Crucial             | 14       | 16     | 8.43%   |
| SanDisk             | 12       | 12     | 7.23%   |
| WDC                 | 11       | 13     | 6.63%   |
| Patriot             | 6        | 8      | 3.61%   |
| Intel               | 4        | 4      | 2.41%   |
| China               | 4        | 5      | 2.41%   |
| A-DATA Technology   | 4        | 5      | 2.41%   |
| Toshiba             | 3        | 3      | 1.81%   |
| PNY                 | 3        | 4      | 1.81%   |
| Micron Technology   | 3        | 3      | 1.81%   |
| Lexar               | 3        | 3      | 1.81%   |
| Transcend           | 2        | 2      | 1.2%    |
| OCZ                 | 2        | 2      | 1.2%    |
| KODAK               | 2        | 2      | 1.2%    |
| Intenso             | 2        | 2      | 1.2%    |
| Verbatim            | 1        | 1      | 0.6%    |
| ValueTech           | 1        | 1      | 0.6%    |
| Team                | 1        | 1      | 0.6%    |
| T-FORCE             | 1        | 1      | 0.6%    |
| Smartbuy            | 1        | 1      | 0.6%    |
| Seagate             | 1        | 1      | 0.6%    |
| Plextor             | 1        | 1      | 0.6%    |
| Mushkin             | 1        | 2      | 0.6%    |
| Maxtor              | 1        | 1      | 0.6%    |
| KIOXIA-EXCERIA      | 1        | 2      | 0.6%    |
| KingFast            | 1        | 1      | 0.6%    |
| INNOVATION IT       | 1        | 1      | 0.6%    |
| INDMEM              | 1        | 1      | 0.6%    |
| Hewlett-Packard     | 1        | 1      | 0.6%    |
| GOODRAM             | 1        | 1      | 0.6%    |
| Drevo               | 1        | 1      | 0.6%    |
| Apple               | 1        | 1      | 0.6%    |
| Apacer              | 1        | 1      | 0.6%    |
| Aireye              | 1        | 1      | 0.6%    |
| ADATA SU            | 1        | 1      | 0.6%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 146      | 273    | 39.25%  |
| SSD     | 137      | 199    | 36.83%  |
| NVMe    | 77       | 116    | 20.7%   |
| Unknown | 11       | 16     | 2.96%   |
| MMC     | 1        | 1      | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 195      | 448    | 65.44%  |
| NVMe | 77       | 116    | 25.84%  |
| SAS  | 25       | 40     | 8.39%   |
| MMC  | 1        | 1      | 0.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 144      | 228    | 45.57%  |
| 0.51-1.0   | 79       | 110    | 25%     |
| 1.01-2.0   | 37       | 45     | 11.71%  |
| 3.01-4.0   | 31       | 52     | 9.81%   |
| 4.01-10.0  | 13       | 23     | 4.11%   |
| 2.01-3.0   | 10       | 12     | 3.16%   |
| 10.01-20.0 | 2        | 2      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 41       | 18.72%  |
| More than 3000 | 37       | 16.89%  |
| 1001-2000      | 37       | 16.89%  |
| 251-500        | 32       | 14.61%  |
| 2001-3000      | 29       | 13.24%  |
| 101-250        | 29       | 13.24%  |
| 1-20           | 9        | 4.11%   |
| 51-100         | 4        | 1.83%   |
| Unknown        | 1        | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 33       | 15%     |
| 101-250        | 32       | 14.55%  |
| 501-1000       | 32       | 14.55%  |
| 1-20           | 29       | 13.18%  |
| 51-100         | 22       | 10%     |
| 21-50          | 21       | 9.55%   |
| 1001-2000      | 21       | 9.55%   |
| More than 3000 | 19       | 8.64%   |
| 2001-3000      | 10       | 4.55%   |
| Unknown        | 1        | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Desktops | Drives | Percent |
|------------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                | 2        | 2      | 6.06%   |
| WDC WD5000AZRX-00A3KB0 500GB                   | 1        | 1      | 3.03%   |
| WDC WD5000AVVS-63M8B0 500GB                    | 1        | 1      | 3.03%   |
| WDC WD10EZEX-22MFCA0 1TB                       | 1        | 1      | 3.03%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1        | 1      | 3.03%   |
| WDC WD10EARS-00MVWB0 1TB                       | 1        | 1      | 3.03%   |
| WDC WD10EADS-00L5B1 1TB                        | 1        | 1      | 3.03%   |
| T-FORCE SSD 512GB                              | 1        | 1      | 3.03%   |
| Seagate ST500LT012-9WS142 500GB                | 1        | 1      | 3.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1        | 1      | 3.03%   |
| Seagate ST4000VN008-2DR166 4TB                 | 1        | 2      | 3.03%   |
| Seagate ST3500630AS 500GB                      | 1        | 1      | 3.03%   |
| Seagate ST3160827AS 160GB                      | 1        | 1      | 3.03%   |
| Seagate ST31500341AS 1TB                       | 1        | 1      | 3.03%   |
| Seagate ST31000524AS 1TB                       | 1        | 2      | 3.03%   |
| Seagate ST1000DM003-1SB102 1TB                 | 1        | 1      | 3.03%   |
| Seagate ST1000DM003-1CH162 1TB                 | 1        | 1      | 3.03%   |
| SanDisk SDSSDX240GG25 240GB                    | 1        | 1      | 3.03%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1        | 1      | 3.03%   |
| Samsung Electronics SSD 840 Series 250GB       | 1        | 1      | 3.03%   |
| Samsung Electronics SSD 840 Series 120GB       | 1        | 1      | 3.03%   |
| Samsung Electronics HM321HI 320GB              | 1        | 1      | 3.03%   |
| Samsung Electronics HD103SI 1TB                | 1        | 1      | 3.03%   |
| Micron Technology 5100_MTFDDAV960TCB 960GB SSD | 1        | 1      | 3.03%   |
| Kingston SA400S37480G 480GB SSD                | 1        | 1      | 3.03%   |
| Hitachi HTS547550A9E384 500GB                  | 1        | 1      | 3.03%   |
| Hitachi HDS721010CLA630 1TB                    | 1        | 1      | 3.03%   |
| Hitachi HDP725050GLA360 500GB                  | 1        | 1      | 3.03%   |
| Hitachi HCT721010SLA360 1TB                    | 1        | 1      | 3.03%   |
| HGST HUH728080ALE600 8TB                       | 1        | 1      | 3.03%   |
| Crucial CT525MX300SSD1 528GB                   | 1        | 1      | 3.03%   |
| Crucial CT240M500SSD1 240GB                    | 1        | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 13     | 30%     |
| WDC                 | 5        | 6      | 16.67%  |
| Samsung Electronics | 5        | 5      | 16.67%  |
| Hitachi             | 4        | 4      | 13.33%  |
| Crucial             | 2        | 2      | 6.67%   |
| T-FORCE             | 1        | 1      | 3.33%   |
| SanDisk             | 1        | 1      | 3.33%   |
| Micron Technology   | 1        | 1      | 3.33%   |
| Kingston            | 1        | 1      | 3.33%   |
| HGST                | 1        | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 13     | 42.86%  |
| WDC                 | 5        | 6      | 23.81%  |
| Hitachi             | 4        | 4      | 19.05%  |
| Samsung Electronics | 2        | 2      | 9.52%   |
| HGST                | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 26     | 67.86%  |
| SSD  | 9        | 9      | 32.14%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1        | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 50%     |
| Hitachi             | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 118      | 297    | 46.46%  |
| Works    | 108      | 271    | 42.52%  |
| Malfunc  | 27       | 35     | 10.63%  |
| Failed   | 1        | 2      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 122      | 36.97%  |
| AMD                         | 92       | 27.88%  |
| Samsung Electronics         | 32       | 9.7%    |
| Sandisk                     | 15       | 4.55%   |
| ASMedia Technology          | 13       | 3.94%   |
| Phison Electronics          | 11       | 3.33%   |
| Kingston Technology Company | 10       | 3.03%   |
| Micron/Crucial Technology   | 6        | 1.82%   |
| JMicron Technology          | 6        | 1.82%   |
| ADATA Technology            | 4        | 1.21%   |
| Seagate Technology          | 3        | 0.91%   |
| Marvell Technology Group    | 3        | 0.91%   |
| LSI Logic / Symbios Logic   | 3        | 0.91%   |
| KIOXIA                      | 2        | 0.61%   |
| VIA Technologies            | 1        | 0.3%    |
| SK hynix                    | 1        | 0.3%    |
| Silicon Motion              | 1        | 0.3%    |
| Silicon Image               | 1        | 0.3%    |
| Realtek Semiconductor       | 1        | 0.3%    |
| O2 Micro                    | 1        | 0.3%    |
| INNOGRIT                    | 1        | 0.3%    |
| Broadcom / LSI              | 1        | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 57       | 14.18%  |
| AMD 400 Series Chipset SATA Controller                                         | 27       | 6.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 20       | 4.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 17       | 4.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12       | 2.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 12       | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11       | 2.74%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 11       | 2.74%   |
| Intel SATA Controller [RAID mode]                                              | 9        | 2.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9        | 2.24%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9        | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 9        | 2.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8        | 1.99%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 7        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7        | 1.74%   |
| AMD FCH SATA Controller D                                                      | 7        | 1.74%   |
| Samsung NVMe SSD Controller 980                                                | 6        | 1.49%   |
| Phison E12 NVMe Controller                                                     | 6        | 1.49%   |
| Kingston Company A2000 NVMe SSD                                                | 6        | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6        | 1.49%   |
| SanDisk Non-Volatile memory controller                                         | 5        | 1.24%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5        | 1.24%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 1.24%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 5        | 1.24%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 5        | 1.24%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 5        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5        | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4        | 1%      |
| JMicron JMB363 SATA/IDE Controller                                             | 4        | 1%      |
| Intel SSD 660P Series                                                          | 4        | 1%      |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4        | 1%      |
| AMD 300 Series Chipset SATA Controller                                         | 4        | 1%      |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3        | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3        | 0.75%   |
| Kingston Company Company Non-Volatile memory controller                        | 3        | 0.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 0.75%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3        | 0.75%   |
| AMD X399 Series Chipset SATA Controller                                        | 3        | 0.75%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 0.75%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 197      | 62.74%  |
| NVMe | 76       | 24.2%   |
| IDE  | 24       | 7.64%   |
| RAID | 15       | 4.78%   |
| SAS  | 1        | 0.32%   |
| SCSI | 1        | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 122      | 57.01%  |
| AMD    | 92       | 42.99%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor             | 8        | 3.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 5        | 2.34%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 5        | 2.34%   |
| Intel Core i5-10400F CPU @ 2.90GHz             | 5        | 2.34%   |
| AMD Ryzen 5 2600X Six-Core Processor           | 5        | 2.34%   |
| Intel Core i7-6700 CPU @ 3.40GHz               | 4        | 1.87%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 4        | 1.87%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 4        | 1.87%   |
| AMD Ryzen 5 3600 6-Core Processor              | 4        | 1.87%   |
| Intel Core i7-7700K CPU @ 4.20GHz              | 3        | 1.4%    |
| Intel Core i7-4790K CPU @ 4.00GHz              | 3        | 1.4%    |
| Intel Core i5-9600K CPU @ 3.70GHz              | 3        | 1.4%    |
| AMD Ryzen 9 5950X 16-Core Processor            | 3        | 1.4%    |
| AMD Ryzen 7 5700X 8-Core Processor             | 3        | 1.4%    |
| AMD Ryzen 7 3700X 8-Core Processor             | 3        | 1.4%    |
| AMD Ryzen 7 2700X Eight-Core Processor         | 3        | 1.4%    |
| AMD Ryzen 7 2700 Eight-Core Processor          | 3        | 1.4%    |
| AMD Ryzen 5 5600G with Radeon Graphics         | 3        | 1.4%    |
| Intel Pentium CPU G2020 @ 2.90GHz              | 2        | 0.93%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 2        | 0.93%   |
| Intel Core i7-5820K CPU @ 3.30GHz              | 2        | 0.93%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 2        | 0.93%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 2        | 0.93%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 2        | 0.93%   |
| Intel Core i5-4590 CPU @ 3.30GHz               | 2        | 0.93%   |
| Intel Core i3-6100T CPU @ 3.20GHz              | 2        | 0.93%   |
| Intel Core i3-4130 CPU @ 3.40GHz               | 2        | 0.93%   |
| Intel Core i3-10100F CPU @ 3.60GHz             | 2        | 0.93%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz           | 2        | 0.93%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor | 2        | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 2        | 0.93%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics     | 2        | 0.93%   |
| AMD Ryzen 7 1700 Eight-Core Processor          | 2        | 0.93%   |
| AMD Ryzen 5 5600 6-Core Processor              | 2        | 0.93%   |
| AMD Ryzen 5 5500                               | 2        | 0.93%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 2        | 0.93%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 0.93%   |
| AMD FX-8350 Eight-Core Processor               | 2        | 0.93%   |
| Intel Xeon CPU X3440 @ 2.53GHz                 | 1        | 0.47%   |
| Intel Xeon CPU W5580 @ 3.20GHz                 | 1        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 41       | 19.16%  |
| Intel Core i5          | 31       | 14.49%  |
| AMD Ryzen 5            | 31       | 14.49%  |
| AMD Ryzen 7            | 21       | 9.81%   |
| Intel Core i3          | 13       | 6.07%   |
| AMD Ryzen 9            | 12       | 5.61%   |
| Intel Xeon             | 11       | 5.14%   |
| Other                  | 8        | 3.74%   |
| Intel Pentium          | 8        | 3.74%   |
| AMD FX                 | 5        | 2.34%   |
| Intel Core 2 Duo       | 4        | 1.87%   |
| AMD Ryzen 3            | 4        | 1.87%   |
| AMD Ryzen Threadripper | 3        | 1.4%    |
| Intel Core i9          | 2        | 0.93%   |
| Intel Core 2 Quad      | 2        | 0.93%   |
| Intel Celeron          | 2        | 0.93%   |
| AMD Ryzen 7 PRO        | 2        | 0.93%   |
| AMD Phenom II X2       | 2        | 0.93%   |
| AMD Opteron            | 2        | 0.93%   |
| AMD A6                 | 2        | 0.93%   |
| Intel Pentium Gold     | 1        | 0.47%   |
| AMD Phenom II X6       | 1        | 0.47%   |
| AMD Phenom II X4       | 1        | 0.47%   |
| AMD E1                 | 1        | 0.47%   |
| AMD Athlon II X2       | 1        | 0.47%   |
| AMD Athlon 64 X2       | 1        | 0.47%   |
| AMD A8                 | 1        | 0.47%   |
| AMD A4                 | 1        | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 75       | 35.05%  |
| 6      | 53       | 24.77%  |
| 8      | 33       | 15.42%  |
| 2      | 33       | 15.42%  |
| 16     | 8        | 3.74%   |
| 12     | 7        | 3.27%   |
| 10     | 3        | 1.4%    |
| 1      | 2        | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 213      | 99.53%  |
| 2      | 1        | 0.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 155      | 72.43%  |
| 1      | 59       | 27.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 214      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 99       | 45.62%  |
| 0x306c3    | 9        | 4.15%   |
| 0x08701021 | 9        | 4.15%   |
| 0x0800820d | 7        | 3.23%   |
| 0x506e3    | 6        | 2.76%   |
| 0xa0653    | 5        | 2.3%    |
| 0x906e9    | 5        | 2.3%    |
| 0x306a9    | 5        | 2.3%    |
| 0x0a50000c | 5        | 2.3%    |
| 0x906ed    | 4        | 1.84%   |
| 0x206a7    | 4        | 1.84%   |
| 0x0a201205 | 4        | 1.84%   |
| 0x010000c8 | 4        | 1.84%   |
| 0xa0655    | 3        | 1.38%   |
| 0x906ea    | 3        | 1.38%   |
| 0x90672    | 3        | 1.38%   |
| 0x0a201016 | 3        | 1.38%   |
| 0x08001138 | 3        | 1.38%   |
| 0x406f1    | 2        | 0.92%   |
| 0x306f2    | 2        | 0.92%   |
| 0x206d7    | 2        | 0.92%   |
| 0x1067a    | 2        | 0.92%   |
| 0x0a50000d | 2        | 0.92%   |
| 0x0a20120a | 2        | 0.92%   |
| 0x0a201204 | 2        | 0.92%   |
| 0x0a201009 | 2        | 0.92%   |
| 0x06000852 | 2        | 0.92%   |
| 0x806ea    | 1        | 0.46%   |
| 0x6fb      | 1        | 0.46%   |
| 0x306e4    | 1        | 0.46%   |
| 0x206d6    | 1        | 0.46%   |
| 0x106e5    | 1        | 0.46%   |
| 0x106a5    | 1        | 0.46%   |
| 0x0a201005 | 1        | 0.46%   |
| 0x08701013 | 1        | 0.46%   |
| 0x08600106 | 1        | 0.46%   |
| 0x08600103 | 1        | 0.46%   |
| 0x08001137 | 1        | 0.46%   |
| 0x08001136 | 1        | 0.46%   |
| 0x08001126 | 1        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 30       | 13.95%  |
| Haswell          | 26       | 12.09%  |
| KabyLake         | 22       | 10.23%  |
| Zen 2            | 17       | 7.91%   |
| IvyBridge        | 17       | 7.91%   |
| Zen+             | 16       | 7.44%   |
| CometLake        | 12       | 5.58%   |
| Skylake          | 11       | 5.12%   |
| Zen              | 10       | 4.65%   |
| SandyBridge      | 10       | 4.65%   |
| Piledriver       | 8        | 3.72%   |
| K10              | 6        | 2.79%   |
| Nehalem          | 5        | 2.33%   |
| Unknown          | 5        | 2.33%   |
| Penryn           | 4        | 1.86%   |
| Excavator        | 3        | 1.4%    |
| Broadwell        | 3        | 1.4%    |
| Alderlake Hybrid | 3        | 1.4%    |
| Westmere         | 2        | 0.93%   |
| Core             | 2        | 0.93%   |
| Puma             | 1        | 0.47%   |
| K8 Hammer        | 1        | 0.47%   |
| Goldmont         | 1        | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 113      | 49.56%  |
| AMD                        | 72       | 31.58%  |
| Intel                      | 41       | 17.98%  |
| Matrox Electronics Systems | 2        | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 11       | 4.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 4.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 3.49%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 2.62%   |
| Intel HD Graphics 530                                                       | 6        | 2.62%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 2.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5        | 2.18%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 1.75%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 1.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.75%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 1.75%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.75%   |
| Intel HD Graphics 630                                                       | 4        | 1.75%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 1.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.75%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.31%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.31%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.31%   |
| AMD Renoir                                                                  | 3        | 1.31%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.31%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 3        | 1.31%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 2        | 0.87%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.87%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.87%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 0.87%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.87%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 0.87%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 2        | 0.87%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 0.87%   |
| Nvidia GK208B [GeForce GT 720]                                              | 2        | 0.87%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 2        | 0.87%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.87%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 2        | 0.87%   |
| Nvidia GA104 [GeForce RTX 3060]                                             | 2        | 0.87%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.87%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2        | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 109      | 50.93%  |
| 1 x AMD                  | 66       | 30.84%  |
| 1 x Intel                | 31       | 14.49%  |
| Intel + AMD              | 2        | 0.93%   |
| 2 x Nvidia               | 1        | 0.47%   |
| 2 x AMD                  | 1        | 0.47%   |
| Nvidia + Matrox          | 1        | 0.47%   |
| Intel + Nvidia           | 1        | 0.47%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.47%   |
| AMD + Matrox             | 1        | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 125      | 58.41%  |
| Proprietary | 81       | 37.85%  |
| Unknown     | 8        | 3.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 98       | 44.95%  |
| 7.01-8.0   | 25       | 11.47%  |
| 1.01-2.0   | 24       | 11.01%  |
| 3.01-4.0   | 22       | 10.09%  |
| 5.01-6.0   | 14       | 6.42%   |
| 0.51-1.0   | 14       | 6.42%   |
| 0.01-0.5   | 10       | 4.59%   |
| 8.01-16.0  | 7        | 3.21%   |
| 16.01-24.0 | 2        | 0.92%   |
| 4.01-5.0   | 1        | 0.46%   |
| 2.01-3.0   | 1        | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 47       | 18.65%  |
| Dell                 | 33       | 13.1%   |
| Goldstar             | 29       | 11.51%  |
| Hewlett-Packard      | 19       | 7.54%   |
| Acer                 | 16       | 6.35%   |
| AOC                  | 14       | 5.56%   |
| Philips              | 12       | 4.76%   |
| BenQ                 | 11       | 4.37%   |
| Ancor Communications | 11       | 4.37%   |
| Iiyama               | 9        | 3.57%   |
| Sony                 | 5        | 1.98%   |
| ViewSonic            | 4        | 1.59%   |
| ASUSTek Computer     | 4        | 1.59%   |
| NEC Computers        | 3        | 1.19%   |
| Vizio                | 2        | 0.79%   |
| LG Electronics       | 2        | 0.79%   |
| Idek Iiyama          | 2        | 0.79%   |
| Gigabyte Technology  | 2        | 0.79%   |
| Fujitsu Siemens      | 2        | 0.79%   |
| Denver               | 2        | 0.79%   |
| Xiaomi               | 1        | 0.4%    |
| Vita                 | 1        | 0.4%    |
| Vestel Elektronik    | 1        | 0.4%    |
| Unknown              | 1        | 0.4%    |
| Sunplus              | 1        | 0.4%    |
| STD                  | 1        | 0.4%    |
| Sceptre Tech         | 1        | 0.4%    |
| RTK                  | 1        | 0.4%    |
| QUS                  | 1        | 0.4%    |
| Planar               | 1        | 0.4%    |
| PAR                  | 1        | 0.4%    |
| Panasonic            | 1        | 0.4%    |
| MVD                  | 1        | 0.4%    |
| MSI                  | 1        | 0.4%    |
| Medion               | 1        | 0.4%    |
| Lenovo               | 1        | 0.4%    |
| HKC                  | 1        | 0.4%    |
| Envision Peripherals | 1        | 0.4%    |
| Eizo                 | 1        | 0.4%    |
| CLB                  | 1        | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 1.12%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 1.12%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 3        | 1.12%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 3        | 1.12%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 2        | 0.75%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.75%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 2        | 0.75%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch             | 2        | 0.75%   |
| Hewlett-Packard 2311x HWP2939 1920x1080 510x287mm 23.0-inch           | 2        | 0.75%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 0.75%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                 | 2        | 0.75%   |
| Dell S3422DW DELD102 3440x1440 797x334mm 34.0-inch                    | 2        | 0.75%   |
| Dell P2719H DEL4184 1920x1080 600x340mm 27.2-inch                     | 2        | 0.75%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                     | 2        | 0.75%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                     | 2        | 0.75%   |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                     | 2        | 0.75%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                    | 1        | 0.37%   |
| Vizio V435-J01 VIZ1039 3840x2160 941x529mm 42.5-inch                  | 1        | 0.37%   |
| Vizio D32hn-D0 VIZ1007 1366x768 697x392mm 31.5-inch                   | 1        | 0.37%   |
| Vita VT988 VIT03DC 1280x1024 376x301mm 19.0-inch                      | 1        | 0.37%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1        | 0.37%   |
| ViewSonic VX2439wm VSC3D24 1920x1080 520x290mm 23.4-inch              | 1        | 0.37%   |
| ViewSonic VA2261 VSC0F30 1920x1080 477x268mm 21.5-inch                | 1        | 0.37%   |
| ViewSonic LCD Monitor VSCD62F 1920x1080 620x340mm 27.8-inch           | 1        | 0.37%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 1        | 0.37%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1        | 0.37%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch               | 1        | 0.37%   |
| STD LCD Monitor STD0001 1920x1080                                     | 1        | 0.37%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 0.37%   |
| Sony TV SNYEA01 1920x1080                                             | 1        | 0.37%   |
| Sony TV SNYC901 1920x1080                                             | 1        | 0.37%   |
| Sony TV SNY7702 1920x1080 708x398mm 32.0-inch                         | 1        | 0.37%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                    | 1        | 0.37%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1        | 0.37%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch     | 1        | 0.37%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1        | 0.37%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1        | 0.37%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch     | 1        | 0.37%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch     | 1        | 0.37%   |
| Samsung Electronics T19C300 SAM0A98 1366x768 410x230mm 18.5-inch      | 1        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 121      | 50.63%  |
| 3840x2160 (4K)     | 28       | 11.72%  |
| 2560x1440 (QHD)    | 17       | 7.11%   |
| 1920x1200 (WUXGA)  | 13       | 5.44%   |
| 1680x1050 (WSXGA+) | 12       | 5.02%   |
| 1280x1024 (SXGA)   | 10       | 4.18%   |
| 3440x1440          | 7        | 2.93%   |
| 1366x768 (WXGA)    | 7        | 2.93%   |
| 2560x1080          | 5        | 2.09%   |
| 1600x900 (HD+)     | 4        | 1.67%   |
| 1440x900 (WXGA+)   | 3        | 1.26%   |
| 3840x1080          | 2        | 0.84%   |
| 1280x720 (HD)      | 2        | 0.84%   |
| Unknown            | 2        | 0.84%   |
| 5760x1080          | 1        | 0.42%   |
| 3840x1600          | 1        | 0.42%   |
| 3840x1200          | 1        | 0.42%   |
| 3600x1200          | 1        | 0.42%   |
| 2288x1287          | 1        | 0.42%   |
| 1360x768           | 1        | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 49       | 19.52%  |
| 27      | 37       | 14.74%  |
| 23      | 33       | 13.15%  |
| 21      | 27       | 10.76%  |
| 31      | 16       | 6.37%   |
| 34      | 12       | 4.78%   |
| 19      | 11       | 4.38%   |
| 22      | 10       | 3.98%   |
| Unknown | 9        | 3.59%   |
| 18      | 7        | 2.79%   |
| 32      | 5        | 1.99%   |
| 72      | 4        | 1.59%   |
| 40      | 4        | 1.59%   |
| 46      | 3        | 1.2%    |
| 25      | 3        | 1.2%    |
| 20      | 3        | 1.2%    |
| 17      | 3        | 1.2%    |
| 36      | 2        | 0.8%    |
| 142     | 1        | 0.4%    |
| 84      | 1        | 0.4%    |
| 69      | 1        | 0.4%    |
| 65      | 1        | 0.4%    |
| 60      | 1        | 0.4%    |
| 55      | 1        | 0.4%    |
| 54      | 1        | 0.4%    |
| 49      | 1        | 0.4%    |
| 48      | 1        | 0.4%    |
| 43      | 1        | 0.4%    |
| 38      | 1        | 0.4%    |
| 37      | 1        | 0.4%    |
| 26      | 1        | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 101      | 42.62%  |
| 401-500        | 52       | 21.94%  |
| 601-700        | 24       | 10.13%  |
| 701-800        | 19       | 8.02%   |
| 1001-1500      | 9        | 3.8%    |
| Unknown        | 9        | 3.8%    |
| 801-900        | 6        | 2.53%   |
| 351-400        | 6        | 2.53%   |
| 1501-2000      | 6        | 2.53%   |
| 301-350        | 3        | 1.27%   |
| More than 2000 | 1        | 0.42%   |
| 901-1000       | 1        | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 159      | 72.6%   |
| 16/10   | 28       | 12.79%  |
| 21/9    | 13       | 5.94%   |
| 5/4     | 9        | 4.11%   |
| Unknown | 6        | 2.74%   |
| 32/9    | 2        | 0.91%   |
| 3/2     | 1        | 0.46%   |
| 1.00    | 1        | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 87       | 36.1%   |
| 301-350        | 37       | 15.35%  |
| 351-500        | 33       | 13.69%  |
| 151-200        | 23       | 9.54%   |
| 251-300        | 18       | 7.47%   |
| 501-1000       | 14       | 5.81%   |
| More than 1000 | 11       | 4.56%   |
| 141-150        | 9        | 3.73%   |
| Unknown        | 9        | 3.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 138      | 62.73%  |
| 101-120 | 41       | 18.64%  |
| 1-50    | 14       | 6.36%   |
| 121-160 | 13       | 5.91%   |
| Unknown | 9        | 4.09%   |
| 161-240 | 5        | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 137      | 63.72%  |
| 2     | 64       | 29.77%  |
| 0     | 10       | 4.65%   |
| 3     | 3        | 1.4%    |
| 4     | 1        | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 135      | 41.41%  |
| Intel                           | 103      | 31.6%   |
| Qualcomm Atheros                | 17       | 5.21%   |
| Broadcom                        | 12       | 3.68%   |
| Ralink Technology               | 9        | 2.76%   |
| TP-Link                         | 8        | 2.45%   |
| Aquantia                        | 6        | 1.84%   |
| Ralink                          | 4        | 1.23%   |
| Huawei Technologies             | 4        | 1.23%   |
| Samsung Electronics             | 3        | 0.92%   |
| MediaTek                        | 3        | 0.92%   |
| Xiaomi                          | 2        | 0.61%   |
| D-Link                          | 2        | 0.61%   |
| ASUSTek Computer                | 2        | 0.61%   |
| ASIX Electronics                | 2        | 0.61%   |
| ZyXEL Communications            | 1        | 0.31%   |
| Wilocity                        | 1        | 0.31%   |
| VIA Technologies                | 1        | 0.31%   |
| U-Blox                          | 1        | 0.31%   |
| Qualcomm Atheros Communications | 1        | 0.31%   |
| NetGear                         | 1        | 0.31%   |
| Microsoft                       | 1        | 0.31%   |
| Mercucys                        | 1        | 0.31%   |
| Linksys                         | 1        | 0.31%   |
| LG Electronics                  | 1        | 0.31%   |
| Edimax Technology               | 1        | 0.31%   |
| DisplayLink                     | 1        | 0.31%   |
| D-Link System                   | 1        | 0.31%   |
| Bose                            | 1        | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 105      | 27.85%  |
| Intel I211 Gigabit Network Connection                             | 16       | 4.24%   |
| Intel Ethernet Controller I225-V                                  | 15       | 3.98%   |
| Intel Wi-Fi 6 AX200                                               | 13       | 3.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11       | 2.92%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 2.39%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 1.86%   |
| Realtek 802.11ac NIC                                              | 6        | 1.59%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 6        | 1.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 1.33%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 1.33%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.33%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4        | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 1.06%   |
| Intel Wireless-AC 9260                                            | 4        | 1.06%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4        | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.8%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 0.8%    |
| Ralink RT5370 Wireless Adapter                                    | 3        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3        | 0.8%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.8%    |
| Intel 82579V Gigabit Network Connection                           | 3        | 0.8%    |
| Huawei ELS-NX9                                                    | 3        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.53%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2        | 0.53%   |
| TP-Link 802.11ac NIC                                              | 2        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.53%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.53%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 2        | 0.53%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2        | 0.53%   |
| Intel Wireless 8260                                               | 2        | 0.53%   |
| Intel Wireless 7260                                               | 2        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 39       | 30.95%  |
| Realtek Semiconductor           | 30       | 23.81%  |
| Broadcom                        | 11       | 8.73%   |
| Ralink Technology               | 9        | 7.14%   |
| Qualcomm Atheros                | 9        | 7.14%   |
| TP-Link                         | 8        | 6.35%   |
| Ralink                          | 4        | 3.17%   |
| MediaTek                        | 2        | 1.59%   |
| D-Link                          | 2        | 1.59%   |
| ASUSTek Computer                | 2        | 1.59%   |
| ZyXEL Communications            | 1        | 0.79%   |
| Wilocity                        | 1        | 0.79%   |
| Qualcomm Atheros Communications | 1        | 0.79%   |
| NetGear                         | 1        | 0.79%   |
| Microsoft                       | 1        | 0.79%   |
| Mercucys                        | 1        | 0.79%   |
| Linksys                         | 1        | 0.79%   |
| LG Electronics                  | 1        | 0.79%   |
| Edimax Technology               | 1        | 0.79%   |
| D-Link System                   | 1        | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 13       | 10.08%  |
| Realtek 802.11ac NIC                                       | 6        | 4.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 6        | 4.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 5        | 3.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 4        | 3.1%    |
| Intel Wireless-AC 9260                                     | 4        | 3.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 4        | 3.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 3        | 2.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 3        | 2.33%   |
| Ralink RT5370 Wireless Adapter                             | 3        | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3        | 2.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 3        | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                             | 3        | 2.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 2        | 1.55%   |
| TP-Link 802.11ac NIC                                       | 2        | 1.55%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 2        | 1.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2        | 1.55%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 2        | 1.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 2        | 1.55%   |
| Intel Wireless 8260                                        | 2        | 1.55%   |
| Intel Wireless 7260                                        | 2        | 1.55%   |
| Intel Wireless 3165                                        | 2        | 1.55%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 2        | 1.55%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2        | 1.55%   |
| ZyXEL ZyAIR G-202 802.11bg                                 | 1        | 0.78%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 0.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 0.78%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 0.78%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                 | 1        | 0.78%   |
| TP-Link 802.11ac WLAN Adapter                              | 1        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1        | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1        | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter    | 1        | 0.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                 | 1        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 0.78%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 1        | 0.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 1        | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1        | 0.78%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 123      | 51.04%  |
| Intel                 | 87       | 36.1%   |
| Qualcomm Atheros      | 8        | 3.32%   |
| Aquantia              | 6        | 2.49%   |
| Huawei Technologies   | 4        | 1.66%   |
| Samsung Electronics   | 3        | 1.24%   |
| Broadcom              | 3        | 1.24%   |
| Xiaomi                | 2        | 0.83%   |
| ASIX Electronics      | 2        | 0.83%   |
| VIA Technologies      | 1        | 0.41%   |
| MediaTek              | 1        | 0.41%   |
| DisplayLink           | 1        | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 105      | 42.68%  |
| Intel I211 Gigabit Network Connection                             | 16       | 6.5%    |
| Intel Ethernet Controller I225-V                                  | 15       | 6.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 11       | 4.47%   |
| Intel Ethernet Connection (2) I219-V                              | 9        | 3.66%   |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.85%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 2.03%   |
| Intel Ethernet Connection (14) I219-V                             | 5        | 2.03%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 2.03%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 2.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 1.63%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.22%   |
| Huawei ELS-NX9                                                    | 3        | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.81%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.81%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1        | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.41%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.41%   |
| MediaTek File-CD Gadget                                           | 1        | 0.41%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.41%   |
| Intel Ethernet Connection I218-LM                                 | 1        | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.41%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 0.41%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 213      | 63.96%  |
| WiFi     | 118      | 35.44%  |
| Modem    | 2        | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 159      | 72.6%   |
| WiFi     | 60       | 27.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 128      | 59.81%  |
| 2     | 72       | 33.64%  |
| 3     | 11       | 5.14%   |
| 4     | 2        | 0.93%   |
| 6     | 1        | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 146      | 67.91%  |
| Yes  | 69       | 32.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 35       | 35%     |
| Cambridge Silicon Radio         | 30       | 30%     |
| Realtek Semiconductor           | 10       | 10%     |
| ASUSTek Computer                | 9        | 9%      |
| Broadcom                        | 4        | 4%      |
| IMC Networks                    | 3        | 3%      |
| Edimax Technology               | 3        | 3%      |
| TP-Link                         | 2        | 2%      |
| MediaTek                        | 2        | 2%      |
| Qualcomm Atheros Communications | 1        | 1%      |
| Apple                           | 1        | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 30       | 29.7%   |
| Intel AX200 Bluetooth                                   | 13       | 12.87%  |
| Realtek Bluetooth Radio                                 | 7        | 6.93%   |
| Intel Bluetooth wireless interface                      | 6        | 5.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 4        | 3.96%   |
| Intel Wireless-AC 3168 Bluetooth                        | 4        | 3.96%   |
| Intel Bluetooth Device                                  | 4        | 3.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 4        | 3.96%   |
| ASUS ASUS USB-BT500                                     | 4        | 3.96%   |
| Realtek  Bluetooth 4.2 Adapter                          | 3        | 2.97%   |
| IMC Networks Bluetooth Radio                            | 3        | 2.97%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3        | 2.97%   |
| TP-Link TPuLink UB500 Adapter                           | 2        | 1.98%   |
| MediaTek Wireless_Device                                | 2        | 1.98%   |
| ASUS Qualcomm Bluetooth 4.1                             | 2        | 1.98%   |
| Qualcomm Atheros  Bluetooth Device                      | 1        | 0.99%   |
| Intel AX210 Bluetooth                                   | 1        | 0.99%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter             | 1        | 0.99%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 1        | 0.99%   |
| Edimax Bluetooth Adapter                                | 1        | 0.99%   |
| Broadcom BCM43142 Bluetooth 4.0                         | 1        | 0.99%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE   | 1        | 0.99%   |
| ASUS Bluetooth Device                                   | 1        | 0.99%   |
| ASUS Bluetooth Adapter                                  | 1        | 0.99%   |
| Apple Bluetooth USB Host Controller                     | 1        | 0.99%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 118      | 27.96%  |
| AMD                      | 116      | 27.49%  |
| Nvidia                   | 109      | 25.83%  |
| C-Media Electronics      | 11       | 2.61%   |
| GN Netcom                | 6        | 1.42%   |
| JMTek                    | 4        | 0.95%   |
| Creative Labs            | 4        | 0.95%   |
| Texas Instruments        | 3        | 0.71%   |
| Tenx Technology          | 3        | 0.71%   |
| Kingston Technology      | 3        | 0.71%   |
| Generalplus Technology   | 3        | 0.71%   |
| Blue Microphones         | 3        | 0.71%   |
| VIA Technologies         | 2        | 0.47%   |
| SteelSeries ApS          | 2        | 0.47%   |
| Razer USA                | 2        | 0.47%   |
| M-Audio                  | 2        | 0.47%   |
| KORG                     | 2        | 0.47%   |
| BY EDIFIER               | 2        | 0.47%   |
| ASUSTek Computer         | 2        | 0.47%   |
| ZOOM                     | 1        | 0.24%   |
| Yamaha                   | 1        | 0.24%   |
| Veho                     | 1        | 0.24%   |
| Unknown (ABC)            | 1        | 0.24%   |
| Unknown                  | 1        | 0.24%   |
| TerraTec Electronic      | 1        | 0.24%   |
| Samson Technologies      | 1        | 0.24%   |
| Roland                   | 1        | 0.24%   |
| QinHeng Electronics      | 1        | 0.24%   |
| Philips (or NXP)         | 1        | 0.24%   |
| Nordic Semiconductor ASA | 1        | 0.24%   |
| Microsoft                | 1        | 0.24%   |
| Microdia                 | 1        | 0.24%   |
| Micro Star International | 1        | 0.24%   |
| Logitech                 | 1        | 0.24%   |
| Lenovo                   | 1        | 0.24%   |
| Hangzhou Worlde          | 1        | 0.24%   |
| DSEA A/S                 | 1        | 0.24%   |
| Dell                     | 1        | 0.24%   |
| Corsair                  | 1        | 0.24%   |
| Bose                     | 1        | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 34       | 7.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 22       | 4.55%   |
| AMD Family 17h/19h HD Audio Controller                                     | 16       | 3.31%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13       | 2.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13       | 2.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13       | 2.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13       | 2.69%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 2.48%   |
| Nvidia TU116 High Definition Audio Controller                              | 11       | 2.28%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 2.28%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 10       | 2.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 1.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 8        | 1.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 1.66%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 8        | 1.66%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8        | 1.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7        | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.45%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 1.45%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 1.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 1.45%   |
| Nvidia TU104 HD Audio Controller                                           | 6        | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                              | 6        | 1.24%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 1.24%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                  | 6        | 1.24%   |
| Intel Audio device                                                         | 6        | 1.24%   |
| Nvidia High Definition Audio Controller                                    | 5        | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                              | 4        | 0.83%   |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 0.83%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4        | 0.83%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 0.83%   |
| Tenx Technology USB AUDIO                                                  | 3        | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                              | 3        | 0.62%   |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 0.62%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.62%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 29       | 21.64%  |
| Corsair             | 25       | 18.66%  |
| G.Skill             | 17       | 12.69%  |
| Crucial             | 12       | 8.96%   |
| Unknown             | 9        | 6.72%   |
| SK hynix            | 7        | 5.22%   |
| Samsung Electronics | 7        | 5.22%   |
| Micron Technology   | 7        | 5.22%   |
| Team                | 5        | 3.73%   |
| Patriot             | 3        | 2.24%   |
| Ramaxel Technology  | 2        | 1.49%   |
| PNY                 | 2        | 1.49%   |
| Unknown             | 2        | 1.49%   |
| Unifosa             | 1        | 0.75%   |
| Qumo                | 1        | 0.75%   |
| Lexar               | 1        | 0.75%   |
| Kingmax             | 1        | 0.75%   |
| Atermiter           | 1        | 0.75%   |
| AMD                 | 1        | 0.75%   |
| A-DATA Technology   | 1        | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 3        | 2.03%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 3        | 2.03%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s     | 2        | 1.35%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s  | 2        | 1.35%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s  | 2        | 1.35%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8192MB DIMM DDR4 2667MT/s  | 2        | 1.35%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 2        | 1.35%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 1.35%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 2        | 1.35%   |
| Crucial RAM CT8G4DFRA266.C8FE 8GB DIMM DDR4 2933MT/s   | 2        | 1.35%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s  | 2        | 1.35%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s | 2        | 1.35%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s  | 2        | 1.35%   |
| Unknown                                                | 2        | 1.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.68%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s             | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1        | 0.68%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 1        | 0.68%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s             | 1        | 0.68%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s    | 1        | 0.68%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s     | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s    | 1        | 0.68%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s     | 1        | 0.68%   |
| SK hynix RAM Module 8GB DIMM DDR4 2133MT/s             | 1        | 0.68%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.68%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s   | 1        | 0.68%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.68%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.68%   |
| SK hynix RAM HMT351R7CFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.68%   |
| SK hynix RAM HMA81GU6MFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 0.68%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 1        | 0.68%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s         | 1        | 0.68%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 0.68%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 1        | 0.68%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s    | 1        | 0.68%   |
| Qumo RAM QUM4U-16G2666N19 16GB DIMM DDR4 2666MT/s      | 1        | 0.68%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s    | 1        | 0.68%   |
| PNY RAM 8GBF1X08LIII43-12-K 8GB DIMM DDR4 2667MT/s     | 1        | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 86       | 68.25%  |
| DDR3    | 29       | 23.02%  |
| SDRAM   | 4        | 3.17%   |
| Unknown | 3        | 2.38%   |
| DDR5    | 2        | 1.59%   |
| DDR2    | 2        | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 119      | 95.2%   |
| SODIMM | 5        | 4%      |
| RIMM   | 1        | 0.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 60       | 44.78%  |
| 16384 | 34       | 25.37%  |
| 4096  | 21       | 15.67%  |
| 32768 | 9        | 6.72%   |
| 2048  | 9        | 6.72%   |
| 1024  | 1        | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 19       | 13.97%  |
| 3200  | 18       | 13.24%  |
| 3600  | 15       | 11.03%  |
| 2667  | 13       | 9.56%   |
| 1333  | 12       | 8.82%   |
| 2400  | 8        | 5.88%   |
| 2133  | 8        | 5.88%   |
| 3000  | 5        | 3.68%   |
| 3800  | 4        | 2.94%   |
| 2666  | 4        | 2.94%   |
| 3066  | 3        | 2.21%   |
| 1066  | 3        | 2.21%   |
| 3866  | 2        | 1.47%   |
| 2933  | 2        | 1.47%   |
| 1867  | 2        | 1.47%   |
| 6000  | 1        | 0.74%   |
| 5800  | 1        | 0.74%   |
| 4133  | 1        | 0.74%   |
| 4000  | 1        | 0.74%   |
| 3733  | 1        | 0.74%   |
| 3666  | 1        | 0.74%   |
| 3467  | 1        | 0.74%   |
| 3466  | 1        | 0.74%   |
| 3400  | 1        | 0.74%   |
| 3334  | 1        | 0.74%   |
| 3333  | 1        | 0.74%   |
| 3266  | 1        | 0.74%   |
| 2800  | 1        | 0.74%   |
| 2448  | 1        | 0.74%   |
| 2134  | 1        | 0.74%   |
| 1866  | 1        | 0.74%   |
| 1648  | 1        | 0.74%   |
| 800   | 1        | 0.74%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 6        | 31.58%  |
| Seiko Epson         | 3        | 15.79%  |
| Samsung Electronics | 2        | 10.53%  |
| Canon               | 2        | 10.53%  |
| Brother Industries  | 2        | 10.53%  |
| Xerox               | 1        | 5.26%   |
| Kyocera             | 1        | 5.26%   |
| Dymo-CoStar         | 1        | 5.26%   |
| Datamax-O'Neil      | 1        | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung M2070 Series                  | 2        | 10.53%  |
| Xerox Phaser 3140 and 3155            | 1        | 5.26%   |
| Seiko Epson XP-3100 Series            | 1        | 5.26%   |
| Seiko Epson L3110 Series              | 1        | 5.26%   |
| Seiko Epson L220 Series               | 1        | 5.26%   |
| Kyocera Mita FS-820                   | 1        | 5.26%   |
| HP OfficeJet 5500 series              | 1        | 5.26%   |
| HP LaserJet 1022                      | 1        | 5.26%   |
| HP ENVY 4500 series                   | 1        | 5.26%   |
| HP DeskJet D2300                      | 1        | 5.26%   |
| HP DeskJet 3630 series                | 1        | 5.26%   |
| HP ColorLaserJet M253-M254            | 1        | 5.26%   |
| Dymo-CoStar LabelWriter 450           | 1        | 5.26%   |
| Datamax-O'Neil Datamax E-4304         | 1        | 5.26%   |
| Canon PIXMA MX470 Series              | 1        | 5.26%   |
| Canon LaserShot LBP-1120 Printer      | 1        | 5.26%   |
| Brother PT-P700 P-touch Label Printer | 1        | 5.26%   |
| Brother MFC-J460DW                    | 1        | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 5        | 71.43%  |
| Seiko Epson    | 1        | 14.29%  |
| Mustek Systems | 1        | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2        | 28.57%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 14.29%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1        | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1        | 14.29%  |
| Canon CanoScan LiDE 220                     | 1        | 14.29%  |
| Canon CanoScan LiDE 210                     | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 22       | 41.51%  |
| Microdia                      | 5        | 9.43%   |
| Sunplus Innovation Technology | 3        | 5.66%   |
| Microsoft                     | 3        | 5.66%   |
| Samsung Electronics           | 2        | 3.77%   |
| KYE Systems (Mouse Systems)   | 2        | 3.77%   |
| Jieli Technology              | 2        | 3.77%   |
| Generalplus Technology        | 2        | 3.77%   |
| Alcor Micro                   | 2        | 3.77%   |
| Unknown                       | 1        | 1.89%   |
| Silicon Motion                | 1        | 1.89%   |
| Realtek Semiconductor         | 1        | 1.89%   |
| Razer USA                     | 1        | 1.89%   |
| IMC Networks                  | 1        | 1.89%   |
| Hewlett-Packard               | 1        | 1.89%   |
| HD WEBCAM                     | 1        | 1.89%   |
| Cubeternet                    | 1        | 1.89%   |
| Asuscom Network               | 1        | 1.89%   |
| ARC International             | 1        | 1.89%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                                | 5        | 9.43%   |
| Logitech HD Pro Webcam C920                                         | 4        | 7.55%   |
| Logitech C920 PRO HD Webcam                                         | 3        | 5.66%   |
| Samsung Galaxy A5 (MTP)                                             | 2        | 3.77%   |
| Microdia Webcam Vitade AF                                           | 2        | 3.77%   |
| Microdia Laptop_Integrated_Webcam_FHD                               | 2        | 3.77%   |
| Logitech Webcam C170                                                | 2        | 3.77%   |
| Logitech HD Webcam C910                                             | 2        | 3.77%   |
| Jieli USB PHY 2.0                                                   | 2        | 3.77%   |
| Alcor Micro USB 2.0 PC Camera                                       | 2        | 3.77%   |
| Unknown HD camera                                                   | 1        | 1.89%   |
| Sunplus UC40M Audio                                                 | 1        | 1.89%   |
| Sunplus SPCA2281 Web Camera                                         | 1        | 1.89%   |
| Sunplus ezcap U3 capture-04                                         | 1        | 1.89%   |
| Silicon Motion 300k Pixel Camera                                    | 1        | 1.89%   |
| Realtek HK 2M CAM                                                   | 1        | 1.89%   |
| Razer USA Razer Kiyo Pro                                            | 1        | 1.89%   |
| Microsoft MicrosoftÂ LifeCam Studio                                | 1        | 1.89%   |
| Microsoft LifeCam HD-3000                                           | 1        | 1.89%   |
| Microsoft LifeCam Cinema                                            | 1        | 1.89%   |
| Microdia PC Microscope camera                                       | 1        | 1.89%   |
| Logitech Webcam C310                                                | 1        | 1.89%   |
| Logitech QuickCam Pro for Notebooks                                 | 1        | 1.89%   |
| Logitech HD Webcam C615                                             | 1        | 1.89%   |
| Logitech HD Webcam C525                                             | 1        | 1.89%   |
| Logitech C922 Pro Stream Webcam                                     | 1        | 1.89%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 1.89%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                          | 1        | 1.89%   |
| KYE Systems (Mouse Systems) eFace 2025                              | 1        | 1.89%   |
| IMC Networks UVC VGA Webcam                                         | 1        | 1.89%   |
| HP Webcam 1300                                                      | 1        | 1.89%   |
| HD WEBCAM Web Camera                                                | 1        | 1.89%   |
| Generalplus 808 Camera #9 (web-cam mode)                            | 1        | 1.89%   |
| Generalplus 2K HD Camera                                            | 1        | 1.89%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 1.89%   |
| Asuscom Network Depstech webcam                                     | 1        | 1.89%   |
| ARC International Camera                                            | 1        | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Synaptics | 2        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 2        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 25%     |
| OmniKey               | 1        | 25%     |
| Gemalto (was Gemplus) | 1        | 25%     |
| BIT4ID                | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 25%     |
| OmniKey CardMan 1021                              | 1        | 25%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 25%     |
| BIT4ID miniLector EVO                             | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 173      | 80.47%  |
| 1     | 36       | 16.74%  |
| 2     | 5        | 2.33%   |
| 3     | 1        | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 15       | 32.61%  |
| Graphics card            | 10       | 21.74%  |
| Unassigned class         | 7        | 15.22%  |
| Multimedia controller    | 3        | 6.52%   |
| Chipcard                 | 3        | 6.52%   |
| Fingerprint reader       | 2        | 4.35%   |
| Bluetooth                | 2        | 4.35%   |
| Sound                    | 1        | 2.17%   |
| Net/ethernet             | 1        | 2.17%   |
| Communication controller | 1        | 2.17%   |
| Camera                   | 1        | 2.17%   |

