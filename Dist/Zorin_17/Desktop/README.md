Zorin 17 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 17.

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

Total: 1184

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | H61M-DS2                    | [2ef34839f4](https://linux-hardware.org/?probe=2ef34839f4) | Jan 06, 2025 |
| Gigabyte      | Z170X-Gaming 7              | [ad40db7f67](https://linux-hardware.org/?probe=ad40db7f67) | Jan 06, 2025 |
| MSI           | MS-B0A41                    | [72d4614eaf](https://linux-hardware.org/?probe=72d4614eaf) | Jan 05, 2025 |
| Dell          | 0HY9JP A00                  | [3047d18f75](https://linux-hardware.org/?probe=3047d18f75) | Jan 05, 2025 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [b2b5aa8eec](https://linux-hardware.org/?probe=b2b5aa8eec) | Jan 05, 2025 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [38b497d193](https://linux-hardware.org/?probe=38b497d193) | Jan 05, 2025 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [394cfdc261](https://linux-hardware.org/?probe=394cfdc261) | Jan 05, 2025 |
| Gigabyte      | Z97X-UD5H                   | [381b6fc010](https://linux-hardware.org/?probe=381b6fc010) | Jan 05, 2025 |
| Intel         | H61 V1.6B                   | [eb28b5f6be](https://linux-hardware.org/?probe=eb28b5f6be) | Jan 04, 2025 |
| HP            | 805D                        | [269af351cb](https://linux-hardware.org/?probe=269af351cb) | Jan 04, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | [989a72852c](https://linux-hardware.org/?probe=989a72852c) | Jan 04, 2025 |
| Intel         | H61                         | [2a8ff4b81a](https://linux-hardware.org/?probe=2a8ff4b81a) | Jan 03, 2025 |
| Intel         | H61                         | [bb2c7db34e](https://linux-hardware.org/?probe=bb2c7db34e) | Jan 03, 2025 |
| OEM           | B75 Ver:1.41                | [31c5df1f0f](https://linux-hardware.org/?probe=31c5df1f0f) | Jan 01, 2025 |
| Gigabyte      | GA-MA790XT-UD4P             | [2e3ebfe841](https://linux-hardware.org/?probe=2e3ebfe841) | Jan 01, 2025 |
| Dell          | 04GJJT A00                  | [444d672dcb](https://linux-hardware.org/?probe=444d672dcb) | Jan 01, 2025 |
| Intel         | DH87RL AAG74240-402         | [047af1c88e](https://linux-hardware.org/?probe=047af1c88e) | Jan 01, 2025 |
| MSI           | B450 GAMING PLUS MAX        | [15b1774620](https://linux-hardware.org/?probe=15b1774620) | Jan 01, 2025 |
| Gigabyte      | X570 AORUS ULTRA            | [8b12a21b9a](https://linux-hardware.org/?probe=8b12a21b9a) | Dec 31, 2024 |
| ASRock        | A75 Extreme6                | [86fd341a89](https://linux-hardware.org/?probe=86fd341a89) | Dec 31, 2024 |
| HP            | 198E                        | [039237d3ac](https://linux-hardware.org/?probe=039237d3ac) | Dec 30, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [81eb291a07](https://linux-hardware.org/?probe=81eb291a07) | Dec 30, 2024 |
| AZW           | GK35                        | [ed7df72829](https://linux-hardware.org/?probe=ed7df72829) | Dec 29, 2024 |
| ASUSTek       | PRIME H610M-K ARGB          | [8f2f1603ad](https://linux-hardware.org/?probe=8f2f1603ad) | Dec 29, 2024 |
| Gigabyte      | Z97X-Gaming 5               | [dc533b139f](https://linux-hardware.org/?probe=dc533b139f) | Dec 29, 2024 |
| Dell          | 0XCR8D A03                  | [77abfbec81](https://linux-hardware.org/?probe=77abfbec81) | Dec 29, 2024 |
| HP            | 1497                        | [256c3def88](https://linux-hardware.org/?probe=256c3def88) | Dec 29, 2024 |
| Gigabyte      | Z97X-Gaming 3               | [daf6ad0471](https://linux-hardware.org/?probe=daf6ad0471) | Dec 28, 2024 |
| Gigabyte      | Z97X-Gaming 3               | [089e2c01de](https://linux-hardware.org/?probe=089e2c01de) | Dec 28, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [d5047e58d1](https://linux-hardware.org/?probe=d5047e58d1) | Dec 28, 2024 |
| MSI           | FM2-A75IA-E53               | [4736ddfd8c](https://linux-hardware.org/?probe=4736ddfd8c) | Dec 28, 2024 |
| Dell          | 05XGC8 A01                  | [59297e30b7](https://linux-hardware.org/?probe=59297e30b7) | Dec 27, 2024 |
| Dell          | 05XGC8 A01                  | [4714a00d4c](https://linux-hardware.org/?probe=4714a00d4c) | Dec 27, 2024 |
| ASRock        | X870 Pro RS WiFi            | [97eaca87bb](https://linux-hardware.org/?probe=97eaca87bb) | Dec 27, 2024 |
| HP            | 83F2                        | [28232611f8](https://linux-hardware.org/?probe=28232611f8) | Dec 27, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | [59a746132a](https://linux-hardware.org/?probe=59a746132a) | Dec 26, 2024 |
| Dell          | 0200DY A02                  | [048527009c](https://linux-hardware.org/?probe=048527009c) | Dec 26, 2024 |
| Lenovo        | SDK0J40700 WIN              | [783314e5b3](https://linux-hardware.org/?probe=783314e5b3) | Dec 26, 2024 |
| ASRock        | A320M-HDV R4.0              | [ee9f566833](https://linux-hardware.org/?probe=ee9f566833) | Dec 26, 2024 |
| ASRock        | A320M-HDV R4.0              | [03bac79df3](https://linux-hardware.org/?probe=03bac79df3) | Dec 26, 2024 |
| Packard Be... | TBGM01                      | [68d8628be3](https://linux-hardware.org/?probe=68d8628be3) | Dec 25, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | [b0f84564ba](https://linux-hardware.org/?probe=b0f84564ba) | Dec 25, 2024 |
| Dell          | 06FW8P A02                  | [42c00b7a8a](https://linux-hardware.org/?probe=42c00b7a8a) | Dec 24, 2024 |
| Fujitsu Si... | D2461-A2 S26361-D2461-A2    | [246c7d0034](https://linux-hardware.org/?probe=246c7d0034) | Dec 24, 2024 |
| ASUSTek       | PRIME B450M-K II            | [1440d04792](https://linux-hardware.org/?probe=1440d04792) | Dec 24, 2024 |
| Lenovo        | 36EB SDK0R32862 WIN 3258... | [572d308e92](https://linux-hardware.org/?probe=572d308e92) | Dec 23, 2024 |
| Gigabyte      | B450M DS3H V2               | [c8554294b6](https://linux-hardware.org/?probe=c8554294b6) | Dec 23, 2024 |
| HP            | 83E9                        | [149bf1039e](https://linux-hardware.org/?probe=149bf1039e) | Dec 23, 2024 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [482ce52b8d](https://linux-hardware.org/?probe=482ce52b8d) | Dec 22, 2024 |
| ASUSTek       | PRIME H470-PLUS             | [93ed037f43](https://linux-hardware.org/?probe=93ed037f43) | Dec 22, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [15936c57d6](https://linux-hardware.org/?probe=15936c57d6) | Dec 20, 2024 |
| Google        | Teemo                       | [220fc873b9](https://linux-hardware.org/?probe=220fc873b9) | Dec 19, 2024 |
| Gigabyte      | Z77-DS3H                    | [edefe68947](https://linux-hardware.org/?probe=edefe68947) | Dec 19, 2024 |
| ASRock        | FM2A68M-DG3+                | [c649082ef1](https://linux-hardware.org/?probe=c649082ef1) | Dec 19, 2024 |
| ASRock        | FM2A68M-DG3+                | [61b3ee9f74](https://linux-hardware.org/?probe=61b3ee9f74) | Dec 19, 2024 |
| Packard Be... | TBGM01                      | [8fe4cbb492](https://linux-hardware.org/?probe=8fe4cbb492) | Dec 18, 2024 |
| Gigabyte      | GA-MA790XT-UD4P             | [a3dfcce270](https://linux-hardware.org/?probe=a3dfcce270) | Dec 18, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [b7fa7d97c0](https://linux-hardware.org/?probe=b7fa7d97c0) | Dec 17, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [1e479b232e](https://linux-hardware.org/?probe=1e479b232e) | Dec 16, 2024 |
| Acer          | Predator G3610              | [e1311f0567](https://linux-hardware.org/?probe=e1311f0567) | Dec 16, 2024 |
| Huanan        | B85                         | [b296e2c8e1](https://linux-hardware.org/?probe=b296e2c8e1) | Dec 15, 2024 |
| MSI           | Eclipse Plus                | [bd3c3d2f09](https://linux-hardware.org/?probe=bd3c3d2f09) | Dec 15, 2024 |
| Lenovo        | 10064                       | [b162e666ea](https://linux-hardware.org/?probe=b162e666ea) | Dec 15, 2024 |
| Acer          | Predator G3610              | [6daec71034](https://linux-hardware.org/?probe=6daec71034) | Dec 15, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | [8e8893c238](https://linux-hardware.org/?probe=8e8893c238) | Dec 14, 2024 |
| ASUSTek       | H110M-R                     | [87c39f6163](https://linux-hardware.org/?probe=87c39f6163) | Dec 14, 2024 |
| ASUSTek       | PRIME A320M-K               | [9e55c65b62](https://linux-hardware.org/?probe=9e55c65b62) | Dec 14, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [880ae3d999](https://linux-hardware.org/?probe=880ae3d999) | Dec 14, 2024 |
| Dell          | 0200DY A02                  | [8cdb0aff4f](https://linux-hardware.org/?probe=8cdb0aff4f) | Dec 14, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [99ca8a0388](https://linux-hardware.org/?probe=99ca8a0388) | Dec 13, 2024 |
| Biostar       | A520MH                      | [b62ff2bde3](https://linux-hardware.org/?probe=b62ff2bde3) | Dec 13, 2024 |
| Dell          | 09WH54 A00                  | [f1bb8a4c8b](https://linux-hardware.org/?probe=f1bb8a4c8b) | Dec 12, 2024 |
| HP            | 3032h                       | [ca96a21d5f](https://linux-hardware.org/?probe=ca96a21d5f) | Dec 12, 2024 |
| Intel         | X79F1 V2.0                  | [b22f83ab40](https://linux-hardware.org/?probe=b22f83ab40) | Dec 12, 2024 |
| Intel         | H55                         | [9d104d8648](https://linux-hardware.org/?probe=9d104d8648) | Dec 11, 2024 |
| Unknown       | Unknown                     | [209746eb6c](https://linux-hardware.org/?probe=209746eb6c) | Dec 11, 2024 |
| HP            | 8105                        | [96072984b0](https://linux-hardware.org/?probe=96072984b0) | Dec 11, 2024 |
| wpc           | zrd616                      | [f00be7af29](https://linux-hardware.org/?probe=f00be7af29) | Dec 11, 2024 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [7bcd9c0153](https://linux-hardware.org/?probe=7bcd9c0153) | Dec 10, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | [114c039a04](https://linux-hardware.org/?probe=114c039a04) | Dec 10, 2024 |
| Gigabyte      | B760 AORUS ELITE AX         | [1f88096982](https://linux-hardware.org/?probe=1f88096982) | Dec 09, 2024 |
| MSI           | Eclipse Plus                | [c3573619ad](https://linux-hardware.org/?probe=c3573619ad) | Dec 08, 2024 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [3fb4762109](https://linux-hardware.org/?probe=3fb4762109) | Dec 08, 2024 |
| Positivo      | POS-PIH81DL                 | [898e87127f](https://linux-hardware.org/?probe=898e87127f) | Dec 08, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [dd5a713c21](https://linux-hardware.org/?probe=dd5a713c21) | Dec 07, 2024 |
| ASUSTek       | PRIME Z490-A                | [c9392314ab](https://linux-hardware.org/?probe=c9392314ab) | Dec 07, 2024 |
| Dell          | 0J8H4R A00                  | [762b620190](https://linux-hardware.org/?probe=762b620190) | Dec 07, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [9aef334f00](https://linux-hardware.org/?probe=9aef334f00) | Dec 06, 2024 |
| Gigabyte      | EP43-UD3L                   | [5e962e2194](https://linux-hardware.org/?probe=5e962e2194) | Dec 05, 2024 |
| MSI           | B450M PRO-VDH MAX           | [b0ff4ecc5f](https://linux-hardware.org/?probe=b0ff4ecc5f) | Dec 05, 2024 |
| HP            | 8105                        | [536d499bb8](https://linux-hardware.org/?probe=536d499bb8) | Dec 04, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [8b336590d9](https://linux-hardware.org/?probe=8b336590d9) | Dec 04, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1b34f91a7e](https://linux-hardware.org/?probe=1b34f91a7e) | Dec 04, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [c8b86d2a3e](https://linux-hardware.org/?probe=c8b86d2a3e) | Dec 04, 2024 |
| MSI           | B350 TOMAHAWK               | [7909d61813](https://linux-hardware.org/?probe=7909d61813) | Dec 04, 2024 |
| Login Info... | LOG-BAT-I                   | [c5ba631810](https://linux-hardware.org/?probe=c5ba631810) | Dec 04, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [959bb88eae](https://linux-hardware.org/?probe=959bb88eae) | Dec 03, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b1af910648](https://linux-hardware.org/?probe=b1af910648) | Dec 03, 2024 |
| ASUSTek       | X99-A II                    | [53d19a5849](https://linux-hardware.org/?probe=53d19a5849) | Dec 03, 2024 |
| Dell          | 0M9KCM A01                  | [5c2a5074f2](https://linux-hardware.org/?probe=5c2a5074f2) | Dec 02, 2024 |
| Acer          | Aspire X3960                | [875985a78d](https://linux-hardware.org/?probe=875985a78d) | Dec 02, 2024 |
| MSI           | B760M GAMING PLUS WIFI      | [8ec6dab60d](https://linux-hardware.org/?probe=8ec6dab60d) | Dec 02, 2024 |
| Dell          | 0M9KCM A01                  | [c24a105e90](https://linux-hardware.org/?probe=c24a105e90) | Dec 02, 2024 |
| HP            | 8054                        | [aff3ac8a75](https://linux-hardware.org/?probe=aff3ac8a75) | Dec 02, 2024 |
| ASUSTek       | P8Z77-V PRO                 | [d064733dcb](https://linux-hardware.org/?probe=d064733dcb) | Dec 02, 2024 |
| HP            | 821D                        | [20e39b95ab](https://linux-hardware.org/?probe=20e39b95ab) | Dec 01, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [734efedbfa](https://linux-hardware.org/?probe=734efedbfa) | Dec 01, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [10e229d327](https://linux-hardware.org/?probe=10e229d327) | Dec 01, 2024 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [315f389132](https://linux-hardware.org/?probe=315f389132) | Nov 30, 2024 |
| ASRock        | A520M-HVS                   | [6fc786e56e](https://linux-hardware.org/?probe=6fc786e56e) | Nov 29, 2024 |
| MSI           | GF615M-P33                  | [df34126457](https://linux-hardware.org/?probe=df34126457) | Nov 28, 2024 |
| MSI           | GF615M-P33                  | [2e1f2c05cd](https://linux-hardware.org/?probe=2e1f2c05cd) | Nov 28, 2024 |
| Dell          | 0KWVT8 A00                  | [bd9c6385dd](https://linux-hardware.org/?probe=bd9c6385dd) | Nov 28, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [7b8612d136](https://linux-hardware.org/?probe=7b8612d136) | Nov 27, 2024 |
| GEEKOM        | Mini IT12                   | [f5b92bba05](https://linux-hardware.org/?probe=f5b92bba05) | Nov 26, 2024 |
| GEEKOM        | Mini IT12                   | [a896649890](https://linux-hardware.org/?probe=a896649890) | Nov 26, 2024 |
| GEEKOM        | Mini IT12                   | [49be531cbb](https://linux-hardware.org/?probe=49be531cbb) | Nov 26, 2024 |
| Intel         | DX79TO AAG28805-402         | [4b26bc3324](https://linux-hardware.org/?probe=4b26bc3324) | Nov 26, 2024 |
| MSI           | 2A9C                        | [69c4dafac6](https://linux-hardware.org/?probe=69c4dafac6) | Nov 26, 2024 |
| ASUSTek       | P8Z77-V LX                  | [978715d9f7](https://linux-hardware.org/?probe=978715d9f7) | Nov 26, 2024 |
| HP            | 84FE                        | [e5540a94da](https://linux-hardware.org/?probe=e5540a94da) | Nov 26, 2024 |
| Gigabyte      | B760 AORUS ELITE AX         | [d3c62f2b89](https://linux-hardware.org/?probe=d3c62f2b89) | Nov 25, 2024 |
| ASUSTek       | M11AD                       | [b3222c19f5](https://linux-hardware.org/?probe=b3222c19f5) | Nov 25, 2024 |
| ASUSTek       | M11AD                       | [63ed444411](https://linux-hardware.org/?probe=63ed444411) | Nov 25, 2024 |
| Dell          | 0KWVT8 A00                  | [790161652a](https://linux-hardware.org/?probe=790161652a) | Nov 25, 2024 |
| Apple         | Mac-F221BEC8                | [2681ae7326](https://linux-hardware.org/?probe=2681ae7326) | Nov 25, 2024 |
| Apple         | Mac-F221BEC8                | [76f9ffcdab](https://linux-hardware.org/?probe=76f9ffcdab) | Nov 25, 2024 |
| HP            | 2AA2                        | [ad8688b30a](https://linux-hardware.org/?probe=ad8688b30a) | Nov 24, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [41d8012fc9](https://linux-hardware.org/?probe=41d8012fc9) | Nov 24, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8d5b062bbb](https://linux-hardware.org/?probe=8d5b062bbb) | Nov 24, 2024 |
| Huanan        | X99-8M-F V1.1               | [10d9ba5f68](https://linux-hardware.org/?probe=10d9ba5f68) | Nov 24, 2024 |
| Dell          | 0XC837                      | [af2a699551](https://linux-hardware.org/?probe=af2a699551) | Nov 24, 2024 |
| Colorful T... | C.Z77 X5 V20                | [5883b61b95](https://linux-hardware.org/?probe=5883b61b95) | Nov 24, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [3f588402aa](https://linux-hardware.org/?probe=3f588402aa) | Nov 23, 2024 |
| HP            | 2ADC                        | [80db44ef55](https://linux-hardware.org/?probe=80db44ef55) | Nov 23, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [770555fffb](https://linux-hardware.org/?probe=770555fffb) | Nov 23, 2024 |
| HP            | 1497                        | [8d58b02962](https://linux-hardware.org/?probe=8d58b02962) | Nov 23, 2024 |
| HP            | 2ADC                        | [eb84d86558](https://linux-hardware.org/?probe=eb84d86558) | Nov 23, 2024 |
| Biostar       | GF8200C M2+                 | [07b481323c](https://linux-hardware.org/?probe=07b481323c) | Nov 22, 2024 |
| Biostar       | GF8200C M2+                 | [8094c6177a](https://linux-hardware.org/?probe=8094c6177a) | Nov 22, 2024 |
| Dell          | 0HD5W2 A01                  | [92e0094425](https://linux-hardware.org/?probe=92e0094425) | Nov 22, 2024 |
| ASUSTek       | H110M-A/M.2                 | [6c4b43e660](https://linux-hardware.org/?probe=6c4b43e660) | Nov 22, 2024 |
| JW Technol... | JW-IG41-MKII V1.1           | [e48cac1e60](https://linux-hardware.org/?probe=e48cac1e60) | Nov 21, 2024 |
| HP            | 8055                        | [593178f988](https://linux-hardware.org/?probe=593178f988) | Nov 21, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [e61aed8e47](https://linux-hardware.org/?probe=e61aed8e47) | Nov 21, 2024 |
| Dell          | 0HD5W2 A01                  | [bce97e2d1d](https://linux-hardware.org/?probe=bce97e2d1d) | Nov 21, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bec30cdc12](https://linux-hardware.org/?probe=bec30cdc12) | Nov 20, 2024 |
| Intel         | D34010WYK H14771-304        | [51e96c807d](https://linux-hardware.org/?probe=51e96c807d) | Nov 19, 2024 |
| Dell          | 0M5DCD A00                  | [9987b49eb1](https://linux-hardware.org/?probe=9987b49eb1) | Nov 19, 2024 |
| Intel         | D34010WYK H14771-304        | [d35a3bd5f8](https://linux-hardware.org/?probe=d35a3bd5f8) | Nov 18, 2024 |
| Login Info... | LOG-BAT-I                   | [2c0e29b140](https://linux-hardware.org/?probe=2c0e29b140) | Nov 18, 2024 |
| ASRock        | A320M Pro4                  | [69c029ae2e](https://linux-hardware.org/?probe=69c029ae2e) | Nov 18, 2024 |
| AMD           | A88                         | [9203b9c5a1](https://linux-hardware.org/?probe=9203b9c5a1) | Nov 18, 2024 |
| ASRock        | Z590 Phantom Gaming-ITX/... | [d158bc88f9](https://linux-hardware.org/?probe=d158bc88f9) | Nov 18, 2024 |
| MSI           | A520M-A PRO                 | [70aebceb5e](https://linux-hardware.org/?probe=70aebceb5e) | Nov 18, 2024 |
| ASUSTek       | P5K                         | [dfdb2cf6ee](https://linux-hardware.org/?probe=dfdb2cf6ee) | Nov 17, 2024 |
| AMI           | Intel                       | [266b0fb8f5](https://linux-hardware.org/?probe=266b0fb8f5) | Nov 17, 2024 |
| HP            | 805A                        | [4d0512b55a](https://linux-hardware.org/?probe=4d0512b55a) | Nov 16, 2024 |
| ASUSTek       | A68HM-PLUS                  | [1d7aa20bd7](https://linux-hardware.org/?probe=1d7aa20bd7) | Nov 16, 2024 |
| ASUSTek       | A68HM-PLUS                  | [c88c8d82af](https://linux-hardware.org/?probe=c88c8d82af) | Nov 16, 2024 |
| Unknown       | Unknown                     | [3ddf105c9b](https://linux-hardware.org/?probe=3ddf105c9b) | Nov 16, 2024 |
| Unknown       | Unknown                     | [2f9a6a3df7](https://linux-hardware.org/?probe=2f9a6a3df7) | Nov 16, 2024 |
| Pegatron      | 2A9A                        | [f28e0b8f3d](https://linux-hardware.org/?probe=f28e0b8f3d) | Nov 16, 2024 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | [7055ac7293](https://linux-hardware.org/?probe=7055ac7293) | Nov 15, 2024 |
| ASUSTek       | P5E-VM SE                   | [0c40e6c351](https://linux-hardware.org/?probe=0c40e6c351) | Nov 15, 2024 |
| Dell          | 0HD5W2 A01                  | [a7c7d8ba31](https://linux-hardware.org/?probe=a7c7d8ba31) | Nov 14, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [14bab473d3](https://linux-hardware.org/?probe=14bab473d3) | Nov 13, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [0c44989ab0](https://linux-hardware.org/?probe=0c44989ab0) | Nov 13, 2024 |
| Intel         | B75                         | [3702d043f1](https://linux-hardware.org/?probe=3702d043f1) | Nov 13, 2024 |
| Intel         | B75                         | [b9f5a481dc](https://linux-hardware.org/?probe=b9f5a481dc) | Nov 13, 2024 |
| HP            | 2B02                        | [a0b3253900](https://linux-hardware.org/?probe=a0b3253900) | Nov 13, 2024 |
| HP            | 2B02                        | [d5120d2bd5](https://linux-hardware.org/?probe=d5120d2bd5) | Nov 12, 2024 |
| MSI           | B365M PRO-VDH               | [82d0c85a4c](https://linux-hardware.org/?probe=82d0c85a4c) | Nov 12, 2024 |
| HP            | 1998                        | [369ca1dd47](https://linux-hardware.org/?probe=369ca1dd47) | Nov 12, 2024 |
| ASUSTek       | P5K                         | [909b21807d](https://linux-hardware.org/?probe=909b21807d) | Nov 11, 2024 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [b394d3009b](https://linux-hardware.org/?probe=b394d3009b) | Nov 11, 2024 |
| ASUSTek       | P5Q                         | [9e6cca17b9](https://linux-hardware.org/?probe=9e6cca17b9) | Nov 10, 2024 |
| ASUSTek       | P5Q                         | [3b2b10209b](https://linux-hardware.org/?probe=3b2b10209b) | Nov 10, 2024 |
| ASUSTek       | M4A78LT-M                   | [4a59573437](https://linux-hardware.org/?probe=4a59573437) | Nov 10, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [cb797d9021](https://linux-hardware.org/?probe=cb797d9021) | Nov 10, 2024 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [8e2635b72b](https://linux-hardware.org/?probe=8e2635b72b) | Nov 09, 2024 |
| Dell          | 0KC9NP A01                  | [d4ce086214](https://linux-hardware.org/?probe=d4ce086214) | Nov 09, 2024 |
| HP            | 1905                        | [02b35a093f](https://linux-hardware.org/?probe=02b35a093f) | Nov 08, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | [8fad4727cc](https://linux-hardware.org/?probe=8fad4727cc) | Nov 08, 2024 |
| Lenovo        | NO DPK                      | [bc3bb9ceab](https://linux-hardware.org/?probe=bc3bb9ceab) | Nov 08, 2024 |
| ASUSTek       | P6X58D PREMIUM              | [a3eba13ef1](https://linux-hardware.org/?probe=a3eba13ef1) | Nov 08, 2024 |
| ASRock        | A520M-HVS                   | [5f9ee0de7f](https://linux-hardware.org/?probe=5f9ee0de7f) | Nov 07, 2024 |
| Gigabyte      | B760M AORUS ELITE           | [52a1a63a06](https://linux-hardware.org/?probe=52a1a63a06) | Nov 07, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [b61fa3d781](https://linux-hardware.org/?probe=b61fa3d781) | Nov 06, 2024 |
| HP            | 83F3                        | [e3c4ab7715](https://linux-hardware.org/?probe=e3c4ab7715) | Nov 06, 2024 |
| ASRock        | B450M Steel Legend          | [7b279ff880](https://linux-hardware.org/?probe=7b279ff880) | Nov 06, 2024 |
| Lenovo        | 3176 NOK                    | [5e69593bff](https://linux-hardware.org/?probe=5e69593bff) | Nov 06, 2024 |
| ASRock        | B450M Steel Legend          | [7ebbb04692](https://linux-hardware.org/?probe=7ebbb04692) | Nov 06, 2024 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [91e79369d6](https://linux-hardware.org/?probe=91e79369d6) | Nov 05, 2024 |
| Gigabyte      | Z890 AORUS ELITE X ICE      | [db6488790e](https://linux-hardware.org/?probe=db6488790e) | Nov 05, 2024 |
| Gigabyte      | Z890 AORUS ELITE X ICE      | [35195bf24c](https://linux-hardware.org/?probe=35195bf24c) | Nov 05, 2024 |
| Gigabyte      | P55-USB3                    | [f2fb29214a](https://linux-hardware.org/?probe=f2fb29214a) | Nov 05, 2024 |
| Casper        | C17B                        | [5d63a37717](https://linux-hardware.org/?probe=5d63a37717) | Nov 04, 2024 |
| Pegatron      | NARRA5                      | [23ce1fc4eb](https://linux-hardware.org/?probe=23ce1fc4eb) | Nov 04, 2024 |
| Alienware     | 0TYR0X A00                  | [8ac9740dcd](https://linux-hardware.org/?probe=8ac9740dcd) | Nov 03, 2024 |
| wpc           | zrd616                      | [1002f7593c](https://linux-hardware.org/?probe=1002f7593c) | Nov 02, 2024 |
| HP            | 8B3B A                      | [169caafde2](https://linux-hardware.org/?probe=169caafde2) | Nov 02, 2024 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | [3e6a954b64](https://linux-hardware.org/?probe=3e6a954b64) | Nov 02, 2024 |
| Dell          | 0P096C A01                  | [a3a653274c](https://linux-hardware.org/?probe=a3a653274c) | Nov 01, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [747dc000aa](https://linux-hardware.org/?probe=747dc000aa) | Nov 01, 2024 |
| HP            | 805A                        | [92461038c0](https://linux-hardware.org/?probe=92461038c0) | Oct 31, 2024 |
| MACHINIST     | E5-MR9A V1.0                | [54d4d9d3ba](https://linux-hardware.org/?probe=54d4d9d3ba) | Oct 31, 2024 |
| Medion        | MS-7366                     | [0fe38a33d1](https://linux-hardware.org/?probe=0fe38a33d1) | Oct 31, 2024 |
| ASUSTek       | A55BM-E                     | [3f7b67ed7e](https://linux-hardware.org/?probe=3f7b67ed7e) | Oct 31, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | [c4f0ec932d](https://linux-hardware.org/?probe=c4f0ec932d) | Oct 30, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | [c453bcc368](https://linux-hardware.org/?probe=c453bcc368) | Oct 30, 2024 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [a0cf793a11](https://linux-hardware.org/?probe=a0cf793a11) | Oct 30, 2024 |
| Dell          | 0N826N A03                  | [0c1f187190](https://linux-hardware.org/?probe=0c1f187190) | Oct 29, 2024 |
| Shuttle       | FZ87                        | [87e4a221d2](https://linux-hardware.org/?probe=87e4a221d2) | Oct 29, 2024 |
| Gigabyte      | H97-D3H-CF                  | [e84fc0d40a](https://linux-hardware.org/?probe=e84fc0d40a) | Oct 28, 2024 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | [c65be546ec](https://linux-hardware.org/?probe=c65be546ec) | Oct 28, 2024 |
| HP            | 3047h                       | [42a80cd524](https://linux-hardware.org/?probe=42a80cd524) | Oct 28, 2024 |
| HP            | 3047h                       | [a0af71f769](https://linux-hardware.org/?probe=a0af71f769) | Oct 28, 2024 |
| HP            | 1998                        | [a5201bcf6a](https://linux-hardware.org/?probe=a5201bcf6a) | Oct 28, 2024 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [6a6fb283b0](https://linux-hardware.org/?probe=6a6fb283b0) | Oct 28, 2024 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [08bd9a802a](https://linux-hardware.org/?probe=08bd9a802a) | Oct 28, 2024 |
| Dell          | 0D28YY A00                  | [ffb4541701](https://linux-hardware.org/?probe=ffb4541701) | Oct 27, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [1503565765](https://linux-hardware.org/?probe=1503565765) | Oct 27, 2024 |
| Medion        | MS-7366                     | [786514f25e](https://linux-hardware.org/?probe=786514f25e) | Oct 27, 2024 |
| Gigabyte      | GA-E350N-USB3               | [7225d38fe2](https://linux-hardware.org/?probe=7225d38fe2) | Oct 25, 2024 |
| Gigabyte      | GA-E350N-USB3               | [95f022084d](https://linux-hardware.org/?probe=95f022084d) | Oct 25, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [7d6371be67](https://linux-hardware.org/?probe=7d6371be67) | Oct 24, 2024 |
| Dell          | 0YJPT1 A00                  | [cf6085e6f9](https://linux-hardware.org/?probe=cf6085e6f9) | Oct 24, 2024 |
| MSI           | X570-A PRO                  | [34af986c90](https://linux-hardware.org/?probe=34af986c90) | Oct 23, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [0bd767b322](https://linux-hardware.org/?probe=0bd767b322) | Oct 23, 2024 |
| MSI           | B365M PRO-VDH               | [191f1bfd03](https://linux-hardware.org/?probe=191f1bfd03) | Oct 23, 2024 |
| MSI           | H81M-E33                    | [ab67b3a504](https://linux-hardware.org/?probe=ab67b3a504) | Oct 23, 2024 |
| MSI           | B365M PRO-VDH               | [3356b35619](https://linux-hardware.org/?probe=3356b35619) | Oct 23, 2024 |
| Unknown       | X79                         | [a454957608](https://linux-hardware.org/?probe=a454957608) | Oct 23, 2024 |
| Dell          | 088DT1 A01                  | [5089c146d6](https://linux-hardware.org/?probe=5089c146d6) | Oct 22, 2024 |
| Dell          | 0WR7PY A01                  | [c9ee515b39](https://linux-hardware.org/?probe=c9ee515b39) | Oct 22, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | [f610cef4b5](https://linux-hardware.org/?probe=f610cef4b5) | Oct 21, 2024 |
| ECS           | GeForce6100PM-M2            | [ba0d87fee9](https://linux-hardware.org/?probe=ba0d87fee9) | Oct 21, 2024 |
| ASRock        | A520M-HDV                   | [bb6af03bf3](https://linux-hardware.org/?probe=bb6af03bf3) | Oct 21, 2024 |
| Dell          | 0HHV7N A00                  | [2f0d46fb23](https://linux-hardware.org/?probe=2f0d46fb23) | Oct 20, 2024 |
| HP            | 82F2 A01                    | [22bea705e2](https://linux-hardware.org/?probe=22bea705e2) | Oct 20, 2024 |
| Gigabyte      | M68MT-S2                    | [7fc2990d42](https://linux-hardware.org/?probe=7fc2990d42) | Oct 20, 2024 |
| Gigabyte      | Z170X-Gaming 7              | [cd7d1f8910](https://linux-hardware.org/?probe=cd7d1f8910) | Oct 20, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | [2882c1b751](https://linux-hardware.org/?probe=2882c1b751) | Oct 19, 2024 |
| ASRock        | Z77 Pro4                    | [484a1c621c](https://linux-hardware.org/?probe=484a1c621c) | Oct 19, 2024 |
| Gigabyte      | P35C-DS3R                   | [d486c0f3cc](https://linux-hardware.org/?probe=d486c0f3cc) | Oct 19, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V1.2       | [6a3b145dbc](https://linux-hardware.org/?probe=6a3b145dbc) | Oct 19, 2024 |
| MACHINIST     | X99-MR9A PRO MAX V1.2       | [464acfecba](https://linux-hardware.org/?probe=464acfecba) | Oct 19, 2024 |
| ASUSTek       | P5G41-M LX                  | [02f29e0739](https://linux-hardware.org/?probe=02f29e0739) | Oct 18, 2024 |
| Dell          | 07F37C A00                  | [10c1d68877](https://linux-hardware.org/?probe=10c1d68877) | Oct 17, 2024 |
| Dell          | 0JP3NX A01                  | [591b9985d6](https://linux-hardware.org/?probe=591b9985d6) | Oct 17, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | [3ffc7f702a](https://linux-hardware.org/?probe=3ffc7f702a) | Oct 17, 2024 |
| HP            | 3648h                       | [0aff8ec887](https://linux-hardware.org/?probe=0aff8ec887) | Oct 17, 2024 |
| Gigabyte      | P55A-UD5                    | [427287ea8d](https://linux-hardware.org/?probe=427287ea8d) | Oct 16, 2024 |
| ASUSTek       | CROSSBLADE RANGER           | [7ad6aad489](https://linux-hardware.org/?probe=7ad6aad489) | Oct 16, 2024 |
| ASRock        | H81M-DGS R2.0               | [c498134667](https://linux-hardware.org/?probe=c498134667) | Oct 16, 2024 |
| ASRock        | H81M-DGS R2.0               | [bc56e44248](https://linux-hardware.org/?probe=bc56e44248) | Oct 16, 2024 |
| Dell          | 033FF6 A00                  | [eb7537a3dd](https://linux-hardware.org/?probe=eb7537a3dd) | Oct 15, 2024 |
| ASUSTek       | P8B75-M LX PLUS             | [b4b50a0e63](https://linux-hardware.org/?probe=b4b50a0e63) | Oct 15, 2024 |
| MSI           | PRO Z790-P WIFI             | [80a134427f](https://linux-hardware.org/?probe=80a134427f) | Oct 15, 2024 |
| OEM           | X79G                        | [c6b10f3799](https://linux-hardware.org/?probe=c6b10f3799) | Oct 14, 2024 |
| Alienware     | 0P0JWX A00                  | [c2a8e068bd](https://linux-hardware.org/?probe=c2a8e068bd) | Oct 14, 2024 |
| ASUSTek       | G10CE                       | [752a87865a](https://linux-hardware.org/?probe=752a87865a) | Oct 14, 2024 |
| MSI           | Z390-A PRO                  | [2a5b1c44cc](https://linux-hardware.org/?probe=2a5b1c44cc) | Oct 13, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [abb2c26d54](https://linux-hardware.org/?probe=abb2c26d54) | Oct 13, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [b59a4de42d](https://linux-hardware.org/?probe=b59a4de42d) | Oct 13, 2024 |
| Dell          | 0XPDFK A01                  | [5b41e36020](https://linux-hardware.org/?probe=5b41e36020) | Oct 12, 2024 |
| Dell          | 0XPDFK A01                  | [feea088ac3](https://linux-hardware.org/?probe=feea088ac3) | Oct 12, 2024 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [21f53b5459](https://linux-hardware.org/?probe=21f53b5459) | Oct 11, 2024 |
| MSI           | PRO Z790-P WIFI             | [504f098627](https://linux-hardware.org/?probe=504f098627) | Oct 11, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [19bda37f58](https://linux-hardware.org/?probe=19bda37f58) | Oct 10, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [98ce6f6b57](https://linux-hardware.org/?probe=98ce6f6b57) | Oct 10, 2024 |
| ECS           | Iris8                       | [7ebf751b4d](https://linux-hardware.org/?probe=7ebf751b4d) | Oct 10, 2024 |
| Gigabyte      | B150M-D3P-WG-CF             | [de88d62e95](https://linux-hardware.org/?probe=de88d62e95) | Oct 09, 2024 |
| Gigabyte      | B150M-D3P-WG-CF             | [d0e808d5c5](https://linux-hardware.org/?probe=d0e808d5c5) | Oct 09, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | [3258142b11](https://linux-hardware.org/?probe=3258142b11) | Oct 09, 2024 |
| HP            | 3648h                       | [0920749527](https://linux-hardware.org/?probe=0920749527) | Oct 09, 2024 |
| Gigabyte      | Z68AP-D3                    | [1205d137c5](https://linux-hardware.org/?probe=1205d137c5) | Oct 09, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [a41400db8d](https://linux-hardware.org/?probe=a41400db8d) | Oct 09, 2024 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [c5c62657ee](https://linux-hardware.org/?probe=c5c62657ee) | Oct 08, 2024 |
| Unknown       | Unknown                     | [290c3faa24](https://linux-hardware.org/?probe=290c3faa24) | Oct 08, 2024 |
| Unknown       | Unknown                     | [ae49c8f2cb](https://linux-hardware.org/?probe=ae49c8f2cb) | Oct 08, 2024 |
| Unknown       | Unknown                     | [51d8f5f774](https://linux-hardware.org/?probe=51d8f5f774) | Oct 08, 2024 |
| MSI           | PRO Z690-A DDR4             | [323ebbba62](https://linux-hardware.org/?probe=323ebbba62) | Oct 08, 2024 |
| ASUSTek       | P6T DELUXE V2               | [83d59869de](https://linux-hardware.org/?probe=83d59869de) | Oct 07, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [92e702792f](https://linux-hardware.org/?probe=92e702792f) | Oct 07, 2024 |
| Alienware     | 0446JC A01                  | [7bc596b378](https://linux-hardware.org/?probe=7bc596b378) | Oct 07, 2024 |
| ASUSTek       | PRIME H310M-F R2.0          | [1b09e0c3c0](https://linux-hardware.org/?probe=1b09e0c3c0) | Oct 06, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [bc06f61edf](https://linux-hardware.org/?probe=bc06f61edf) | Oct 06, 2024 |
| MSI           | B550-A PRO                  | [00e8066675](https://linux-hardware.org/?probe=00e8066675) | Oct 06, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [37e187d1c9](https://linux-hardware.org/?probe=37e187d1c9) | Oct 06, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [4ecb717139](https://linux-hardware.org/?probe=4ecb717139) | Oct 06, 2024 |
| ASRock        | H61M-DGS                    | [6bdbe5bc33](https://linux-hardware.org/?probe=6bdbe5bc33) | Oct 05, 2024 |
| Biostar       | A320MH                      | [c281d9f2aa](https://linux-hardware.org/?probe=c281d9f2aa) | Oct 05, 2024 |
| MSI           | MAG Z790 TOMAHAWK MAX WI... | [229998424d](https://linux-hardware.org/?probe=229998424d) | Oct 05, 2024 |
| Alienware     | 0446JC A01                  | [60b8cc6ef1](https://linux-hardware.org/?probe=60b8cc6ef1) | Oct 03, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [49a3a7f013](https://linux-hardware.org/?probe=49a3a7f013) | Oct 03, 2024 |
| ASRock        | Z790 Pro RS/D4              | [fbe99fdf47](https://linux-hardware.org/?probe=fbe99fdf47) | Oct 02, 2024 |
| ASUSTek       | Maximus VIII HERO           | [690a6356bc](https://linux-hardware.org/?probe=690a6356bc) | Oct 01, 2024 |
| ASUSTek       | CROSSBLADE RANGER           | [7a2d2bacd1](https://linux-hardware.org/?probe=7a2d2bacd1) | Oct 01, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [7cbe0719e7](https://linux-hardware.org/?probe=7cbe0719e7) | Oct 01, 2024 |
| Intel         | X79G-A V2.0                 | [a1557bdeba](https://linux-hardware.org/?probe=a1557bdeba) | Oct 01, 2024 |
| ECS           | H61H2-MV                    | [29d29072da](https://linux-hardware.org/?probe=29d29072da) | Oct 01, 2024 |
| ASRock        | H61M-VS4                    | [14561e27dc](https://linux-hardware.org/?probe=14561e27dc) | Oct 01, 2024 |
| Intel         | X79G-A V2.0                 | [b5e98605a4](https://linux-hardware.org/?probe=b5e98605a4) | Sep 30, 2024 |
| ASUSTek       | H81M-PLUS                   | [9c0542b834](https://linux-hardware.org/?probe=9c0542b834) | Sep 30, 2024 |
| Dell          | 0FM586                      | [67cb39d9d4](https://linux-hardware.org/?probe=67cb39d9d4) | Sep 29, 2024 |
| ASRock        | J3355B-ITX                  | [3d82bcbf1c](https://linux-hardware.org/?probe=3d82bcbf1c) | Sep 29, 2024 |
| ASRock        | J3355B-ITX                  | [2e9ef6e2bc](https://linux-hardware.org/?probe=2e9ef6e2bc) | Sep 29, 2024 |
| Lenovo        | SHARKBAY NOK                | [fc1ea5dd8c](https://linux-hardware.org/?probe=fc1ea5dd8c) | Sep 28, 2024 |
| HP            | 3647h                       | [a7f7f8a677](https://linux-hardware.org/?probe=a7f7f8a677) | Sep 28, 2024 |
| Gigabyte      | B760 DS3H                   | [740eb5ea15](https://linux-hardware.org/?probe=740eb5ea15) | Sep 27, 2024 |
| MSI           | PRESTIGE X570 CREATION      | [8dc1f740de](https://linux-hardware.org/?probe=8dc1f740de) | Sep 26, 2024 |
| MSI           | PRESTIGE X570 CREATION      | [0df47e18d9](https://linux-hardware.org/?probe=0df47e18d9) | Sep 26, 2024 |
| Dell          | 0D24M8 A01                  | [f4d0cccdf1](https://linux-hardware.org/?probe=f4d0cccdf1) | Sep 26, 2024 |
| Dell          | 0D24M8 A01                  | [93b881282f](https://linux-hardware.org/?probe=93b881282f) | Sep 26, 2024 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [7d35226fe2](https://linux-hardware.org/?probe=7d35226fe2) | Sep 26, 2024 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [355059e70a](https://linux-hardware.org/?probe=355059e70a) | Sep 26, 2024 |
| ASRock        | B450M Steel Legend          | [a524e39cfb](https://linux-hardware.org/?probe=a524e39cfb) | Sep 26, 2024 |
| Gigabyte      | F2A78M-DASHV                | [ebba91d68c](https://linux-hardware.org/?probe=ebba91d68c) | Sep 26, 2024 |
| Gigabyte      | A320M-S2H-CF                | [fcf3d67e7b](https://linux-hardware.org/?probe=fcf3d67e7b) | Sep 25, 2024 |
| Dell          | 0NW73C A01                  | [a219f52b9b](https://linux-hardware.org/?probe=a219f52b9b) | Sep 25, 2024 |
| Dell          | 0NW73C A01                  | [6f6c30cd6f](https://linux-hardware.org/?probe=6f6c30cd6f) | Sep 25, 2024 |
| Dell          | 04Y8V0 A01                  | [0bb87c76b0](https://linux-hardware.org/?probe=0bb87c76b0) | Sep 24, 2024 |
| HP            | 82A1                        | [9e17703561](https://linux-hardware.org/?probe=9e17703561) | Sep 24, 2024 |
| Gigabyte      | H61M-S2PH                   | [98c9e52a71](https://linux-hardware.org/?probe=98c9e52a71) | Sep 24, 2024 |
| Gigabyte      | GA-78LMT-USB3               | [1e4a64e920](https://linux-hardware.org/?probe=1e4a64e920) | Sep 23, 2024 |
| Dell          | 0GK1K2 A00                  | [2053759f81](https://linux-hardware.org/?probe=2053759f81) | Sep 23, 2024 |
| MSI           | B350 TOMAHAWK               | [532f17f668](https://linux-hardware.org/?probe=532f17f668) | Sep 23, 2024 |
| Medion        | MS-7366                     | [d3f9e281e9](https://linux-hardware.org/?probe=d3f9e281e9) | Sep 23, 2024 |
| Gigabyte      | P55A-UD5                    | [03ad1cf760](https://linux-hardware.org/?probe=03ad1cf760) | Sep 23, 2024 |
| Gigabyte      | P55A-UD5                    | [46eade1992](https://linux-hardware.org/?probe=46eade1992) | Sep 23, 2024 |
| ASUSTek       | PRIME Z790-V AX             | [3c4b7eecfb](https://linux-hardware.org/?probe=3c4b7eecfb) | Sep 22, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [7f53516227](https://linux-hardware.org/?probe=7f53516227) | Sep 22, 2024 |
| ASRock        | B450M Pro4-F                | [aff31dc8ce](https://linux-hardware.org/?probe=aff31dc8ce) | Sep 22, 2024 |
| MSI           | Z97 PC Mate                 | [9e5fa5693a](https://linux-hardware.org/?probe=9e5fa5693a) | Sep 22, 2024 |
| HP            | 0B4Ch D                     | [798c2aed63](https://linux-hardware.org/?probe=798c2aed63) | Sep 22, 2024 |
| Dell          | 0HY9JP A00                  | [61ca1b22ed](https://linux-hardware.org/?probe=61ca1b22ed) | Sep 22, 2024 |
| Dell          | 0HY9JP A00                  | [6a8448c74c](https://linux-hardware.org/?probe=6a8448c74c) | Sep 21, 2024 |
| AZW           | Gemini T34                  | [0744db5764](https://linux-hardware.org/?probe=0744db5764) | Sep 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a6ba08b6d0](https://linux-hardware.org/?probe=a6ba08b6d0) | Sep 21, 2024 |
| Foxconn       | 2ADA                        | [09ddcff37c](https://linux-hardware.org/?probe=09ddcff37c) | Sep 21, 2024 |
| Foxconn       | 2ADA                        | [8a70dadf79](https://linux-hardware.org/?probe=8a70dadf79) | Sep 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a6f270baac](https://linux-hardware.org/?probe=a6f270baac) | Sep 21, 2024 |
| HP            | 83F2                        | [e77b1d8784](https://linux-hardware.org/?probe=e77b1d8784) | Sep 20, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4c35212f77](https://linux-hardware.org/?probe=4c35212f77) | Sep 20, 2024 |
| Gigabyte      | A320M-S2H-CF                | [1a65b79c49](https://linux-hardware.org/?probe=1a65b79c49) | Sep 20, 2024 |
| Gigabyte      | A320M-S2H-CF                | [04ce3b5ab8](https://linux-hardware.org/?probe=04ce3b5ab8) | Sep 20, 2024 |
| ASUSTek       | P5G41-M LX2/GB              | [d473c7ebc9](https://linux-hardware.org/?probe=d473c7ebc9) | Sep 20, 2024 |
| ASUSTek       | PRIME X570-P                | [a5c7ffb693](https://linux-hardware.org/?probe=a5c7ffb693) | Sep 19, 2024 |
| HP            | 8105                        | [6603f1b056](https://linux-hardware.org/?probe=6603f1b056) | Sep 18, 2024 |
| Gigabyte      | B550 AORUS MASTER           | [4516011590](https://linux-hardware.org/?probe=4516011590) | Sep 18, 2024 |
| MSI           | Z87-G45 GAMING              | [789f0a6fbf](https://linux-hardware.org/?probe=789f0a6fbf) | Sep 17, 2024 |
| MSI           | Z87-G45 GAMING              | [8a1c41d355](https://linux-hardware.org/?probe=8a1c41d355) | Sep 17, 2024 |
| Soyo          | SY-YL B550M                 | [29b9693d47](https://linux-hardware.org/?probe=29b9693d47) | Sep 16, 2024 |
| Soyo          | SY-YL B550M                 | [5747eedde0](https://linux-hardware.org/?probe=5747eedde0) | Sep 16, 2024 |
| MSI           | H97M-G43                    | [4dabb8fc52](https://linux-hardware.org/?probe=4dabb8fc52) | Sep 16, 2024 |
| ASRock        | X79 Extreme6                | [9d80286a36](https://linux-hardware.org/?probe=9d80286a36) | Sep 15, 2024 |
| MSI           | PRO B760M-A WIFI            | [9b9efad16f](https://linux-hardware.org/?probe=9b9efad16f) | Sep 15, 2024 |
| Lenovo        | ThinkCentre M90p 5536P79    | [1792792ecc](https://linux-hardware.org/?probe=1792792ecc) | Sep 15, 2024 |
| Gigabyte      | GA-MA790GP-UD4H             | [1f2d668bb5](https://linux-hardware.org/?probe=1f2d668bb5) | Sep 14, 2024 |
| Gigabyte      | GA-MA790GP-UD4H             | [21a9a51b58](https://linux-hardware.org/?probe=21a9a51b58) | Sep 14, 2024 |
| MSI           | Z97I AC                     | [37fd401ef9](https://linux-hardware.org/?probe=37fd401ef9) | Sep 14, 2024 |
| Gigabyte      | X570S GAMING X              | [f6e2dd1616](https://linux-hardware.org/?probe=f6e2dd1616) | Sep 14, 2024 |
| Gigabyte      | B450M GAMING                | [44396af634](https://linux-hardware.org/?probe=44396af634) | Sep 14, 2024 |
| Dell          | 0DR845                      | [99a6870586](https://linux-hardware.org/?probe=99a6870586) | Sep 14, 2024 |
| OEM           | HN B85 Ver:1.4              | [9805a265f7](https://linux-hardware.org/?probe=9805a265f7) | Sep 14, 2024 |
| Dell          | 0DR845                      | [4f3086d8f3](https://linux-hardware.org/?probe=4f3086d8f3) | Sep 14, 2024 |
| Gigabyte      | B85M-D3H                    | [85a9d1959d](https://linux-hardware.org/?probe=85a9d1959d) | Sep 12, 2024 |
| MSI           | G41M-P26                    | [1b4b146b2d](https://linux-hardware.org/?probe=1b4b146b2d) | Sep 12, 2024 |
| ASUSTek       | P5B SE                      | [4c42931311](https://linux-hardware.org/?probe=4c42931311) | Sep 12, 2024 |
| ASUSTek       | H61M-A/BR                   | [a12a233151](https://linux-hardware.org/?probe=a12a233151) | Sep 11, 2024 |
| Pegatron      | TRUCKEE                     | [3a969b02aa](https://linux-hardware.org/?probe=3a969b02aa) | Sep 10, 2024 |
| ASUSTek       | PRIME B450M-GAMING II       | [e52afda022](https://linux-hardware.org/?probe=e52afda022) | Sep 10, 2024 |
| Dell          | 0GK1K2 A00                  | [419d6d0d86](https://linux-hardware.org/?probe=419d6d0d86) | Sep 10, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [67ea32fd29](https://linux-hardware.org/?probe=67ea32fd29) | Sep 10, 2024 |
| HP            | 1496                        | [9c85110b54](https://linux-hardware.org/?probe=9c85110b54) | Sep 10, 2024 |
| Gigabyte      | Z68X-UD4-B3                 | [cd72028c04](https://linux-hardware.org/?probe=cd72028c04) | Sep 10, 2024 |
| Gigabyte      | B450M GAMING                | [30cf1482a9](https://linux-hardware.org/?probe=30cf1482a9) | Sep 09, 2024 |
| ASUSTek       | PRIME Z790-V AX             | [a26aa376a2](https://linux-hardware.org/?probe=a26aa376a2) | Sep 09, 2024 |
| Gigabyte      | Z97X-UD5H                   | [cf117faf85](https://linux-hardware.org/?probe=cf117faf85) | Sep 09, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [4d3e149c23](https://linux-hardware.org/?probe=4d3e149c23) | Sep 09, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [0aadc1015c](https://linux-hardware.org/?probe=0aadc1015c) | Sep 09, 2024 |
| Gigabyte      | P67A-UD3P-B3                | [6ae597c28f](https://linux-hardware.org/?probe=6ae597c28f) | Sep 09, 2024 |
| Gigabyte      | P67A-UD3P-B3                | [dcdf09a7a3](https://linux-hardware.org/?probe=dcdf09a7a3) | Sep 09, 2024 |
| Dell          | 0C1R19 A01                  | [0af83e9521](https://linux-hardware.org/?probe=0af83e9521) | Sep 08, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [fcca865215](https://linux-hardware.org/?probe=fcca865215) | Sep 08, 2024 |
| ASUSTek       | M5A78L-M LX V2              | [ad890df61e](https://linux-hardware.org/?probe=ad890df61e) | Sep 08, 2024 |
| MSI           | B460M PRO-VDH WIFI          | [b07fd86d98](https://linux-hardware.org/?probe=b07fd86d98) | Sep 07, 2024 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [a75adced7f](https://linux-hardware.org/?probe=a75adced7f) | Sep 07, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4ca41527c4](https://linux-hardware.org/?probe=4ca41527c4) | Sep 07, 2024 |
| Dell          | 01W26N A00                  | [22dab9c6fe](https://linux-hardware.org/?probe=22dab9c6fe) | Sep 06, 2024 |
| Dell          | 0GK1K2 A00                  | [272836d37d](https://linux-hardware.org/?probe=272836d37d) | Sep 06, 2024 |
| HP            | 3397                        | [28acd7c27e](https://linux-hardware.org/?probe=28acd7c27e) | Sep 06, 2024 |
| ASRock        | B550M PG Riptide            | [949b7b0048](https://linux-hardware.org/?probe=949b7b0048) | Sep 06, 2024 |
| HP            | 198E                        | [46f98dc702](https://linux-hardware.org/?probe=46f98dc702) | Sep 05, 2024 |
| ASUSTek       | H110M-E/M.2                 | [168422221e](https://linux-hardware.org/?probe=168422221e) | Sep 04, 2024 |
| MSI           | Z270 GAMING PLUS            | [5699b4657d](https://linux-hardware.org/?probe=5699b4657d) | Sep 04, 2024 |
| ASUSTek       | Leonite2                    | [c3d5c40036](https://linux-hardware.org/?probe=c3d5c40036) | Sep 04, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [69140094a9](https://linux-hardware.org/?probe=69140094a9) | Sep 03, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [07507726c8](https://linux-hardware.org/?probe=07507726c8) | Sep 03, 2024 |
| HP            | 18E5                        | [041180d946](https://linux-hardware.org/?probe=041180d946) | Sep 02, 2024 |
| Acer          | Veriton M6660G V:1.0        | [b47231d100](https://linux-hardware.org/?probe=b47231d100) | Sep 02, 2024 |
| Acer          | Veriton M6660G V:1.0        | [cd646ccb52](https://linux-hardware.org/?probe=cd646ccb52) | Sep 02, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | [3e5f800134](https://linux-hardware.org/?probe=3e5f800134) | Sep 01, 2024 |
| Gigabyte      | Z97X-UD5H                   | [2eccb0d2f4](https://linux-hardware.org/?probe=2eccb0d2f4) | Aug 31, 2024 |
| ASRock        | FM2A88M-HD+                 | [3f322eb9de](https://linux-hardware.org/?probe=3f322eb9de) | Aug 31, 2024 |
| ASRock        | H110M-HG4                   | [19b67b31b6](https://linux-hardware.org/?probe=19b67b31b6) | Aug 30, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | [3afa3d3f1c](https://linux-hardware.org/?probe=3afa3d3f1c) | Aug 30, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1f3576e380](https://linux-hardware.org/?probe=1f3576e380) | Aug 29, 2024 |
| Intel         | DX58SO2 AAG10925-205        | [8ac6c88914](https://linux-hardware.org/?probe=8ac6c88914) | Aug 29, 2024 |
| MSI           | PRO B760-VC WIFI            | [6b4e94f9ad](https://linux-hardware.org/?probe=6b4e94f9ad) | Aug 29, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [e36c8d0f5d](https://linux-hardware.org/?probe=e36c8d0f5d) | Aug 29, 2024 |
| MSI           | Z97I GAMING ACK             | [0e21542635](https://linux-hardware.org/?probe=0e21542635) | Aug 28, 2024 |
| SZMZ          | B75-MS V1.0                 | [d4d6bf2159](https://linux-hardware.org/?probe=d4d6bf2159) | Aug 28, 2024 |
| ASUSTek       | M5A97 R2.0                  | [273d4ce682](https://linux-hardware.org/?probe=273d4ce682) | Aug 27, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [efcae1b0fb](https://linux-hardware.org/?probe=efcae1b0fb) | Aug 27, 2024 |
| Lenovo        | H420                        | [37b2ead81c](https://linux-hardware.org/?probe=37b2ead81c) | Aug 27, 2024 |
| Intel         | DG45ID AAE27729-310         | [1b25e65d41](https://linux-hardware.org/?probe=1b25e65d41) | Aug 26, 2024 |
| Intel         | DG45ID AAE27729-310         | [2eec4fd640](https://linux-hardware.org/?probe=2eec4fd640) | Aug 26, 2024 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [7976200bb6](https://linux-hardware.org/?probe=7976200bb6) | Aug 26, 2024 |
| Intel         | DX58SO2 AAG10925-205        | [28c5f9177d](https://linux-hardware.org/?probe=28c5f9177d) | Aug 26, 2024 |
| AMD           | Inagua CRB                  | [9f0aa145c1](https://linux-hardware.org/?probe=9f0aa145c1) | Aug 25, 2024 |
| MSI           | PRESTIGE X570 CREATION      | [83e7a5d640](https://linux-hardware.org/?probe=83e7a5d640) | Aug 25, 2024 |
| ECS           | P45T-A                      | [22b56330c6](https://linux-hardware.org/?probe=22b56330c6) | Aug 25, 2024 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [fd69fed81f](https://linux-hardware.org/?probe=fd69fed81f) | Aug 24, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [6bfb0ed86d](https://linux-hardware.org/?probe=6bfb0ed86d) | Aug 24, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | [131bcb8651](https://linux-hardware.org/?probe=131bcb8651) | Aug 24, 2024 |
| Pegatron      | 2ACB                        | [dc2370aa9d](https://linux-hardware.org/?probe=dc2370aa9d) | Aug 23, 2024 |
| ASUSTek       | H97-PLUS                    | [60f5f3139e](https://linux-hardware.org/?probe=60f5f3139e) | Aug 23, 2024 |
| Gigabyte      | H77-D3H                     | [ae0adb934b](https://linux-hardware.org/?probe=ae0adb934b) | Aug 23, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [099d384a90](https://linux-hardware.org/?probe=099d384a90) | Aug 22, 2024 |
| MSI           | A320M PRO-VH                | [0d6565a713](https://linux-hardware.org/?probe=0d6565a713) | Aug 22, 2024 |
| ASUSTek       | Z10PA-D8 Series             | [9d140d5c3a](https://linux-hardware.org/?probe=9d140d5c3a) | Aug 22, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | [94cd7c3d5a](https://linux-hardware.org/?probe=94cd7c3d5a) | Aug 21, 2024 |
| ASUSTek       | P5B SE                      | [84d58daafa](https://linux-hardware.org/?probe=84d58daafa) | Aug 21, 2024 |
| Gigabyte      | H61M-D2H-USB3               | [34a696cc95](https://linux-hardware.org/?probe=34a696cc95) | Aug 21, 2024 |
| Gigabyte      | H61M-D2H-USB3               | [bc8bf812ae](https://linux-hardware.org/?probe=bc8bf812ae) | Aug 21, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [1dbcd28c43](https://linux-hardware.org/?probe=1dbcd28c43) | Aug 20, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [e02d8c78f1](https://linux-hardware.org/?probe=e02d8c78f1) | Aug 20, 2024 |
| Dell          | 0DF42J A00                  | [1c15285413](https://linux-hardware.org/?probe=1c15285413) | Aug 20, 2024 |
| ASUSTek       | PRIME X570-PRO              | [65b10f5f77](https://linux-hardware.org/?probe=65b10f5f77) | Aug 20, 2024 |
| Pegatron      | 2AD5                        | [d57e937e5c](https://linux-hardware.org/?probe=d57e937e5c) | Aug 20, 2024 |
| HP            | 828A                        | [6df0fbf71f](https://linux-hardware.org/?probe=6df0fbf71f) | Aug 20, 2024 |
| MSI           | Z97I GAMING ACK             | [a251ae1d39](https://linux-hardware.org/?probe=a251ae1d39) | Aug 19, 2024 |
| ASUSTek       | P5G41-M LX                  | [cab64cb216](https://linux-hardware.org/?probe=cab64cb216) | Aug 19, 2024 |
| ASUSTek       | P5G41-M LX                  | [92fa9a6ed6](https://linux-hardware.org/?probe=92fa9a6ed6) | Aug 19, 2024 |
| HP            | 1825                        | [02ef5994ff](https://linux-hardware.org/?probe=02ef5994ff) | Aug 19, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [4f97646b00](https://linux-hardware.org/?probe=4f97646b00) | Aug 19, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [403698fef1](https://linux-hardware.org/?probe=403698fef1) | Aug 19, 2024 |
| ASUSTek       | M5A97 R2.0                  | [dae06bd004](https://linux-hardware.org/?probe=dae06bd004) | Aug 19, 2024 |
| ASRock        | H61M-VG3                    | [bd7e312add](https://linux-hardware.org/?probe=bd7e312add) | Aug 18, 2024 |
| Gigabyte      | Z790 GAMING X AX            | [db12103f69](https://linux-hardware.org/?probe=db12103f69) | Aug 18, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [779bb04c1f](https://linux-hardware.org/?probe=779bb04c1f) | Aug 17, 2024 |
| ASUSTek       | M5A97 PRO                   | [85d72ce8ce](https://linux-hardware.org/?probe=85d72ce8ce) | Aug 17, 2024 |
| Gigabyte      | B365M D3H-CF                | [ddc502c99e](https://linux-hardware.org/?probe=ddc502c99e) | Aug 17, 2024 |
| HP            | 2AF2 A01                    | [6fbeb8f276](https://linux-hardware.org/?probe=6fbeb8f276) | Aug 17, 2024 |
| Acer          | Aspire X1920                | [4245827fac](https://linux-hardware.org/?probe=4245827fac) | Aug 17, 2024 |
| Dell          | 0C1R19 A02                  | [73907078c5](https://linux-hardware.org/?probe=73907078c5) | Aug 16, 2024 |
| ASRock        | 970 Pro3 R2.0               | [e4d80ec38a](https://linux-hardware.org/?probe=e4d80ec38a) | Aug 15, 2024 |
| ASUSTek       | Z170-DELUXE                 | [03a0b28016](https://linux-hardware.org/?probe=03a0b28016) | Aug 15, 2024 |
| Lenovo        | H420                        | [6e49e6445e](https://linux-hardware.org/?probe=6e49e6445e) | Aug 15, 2024 |
| Lenovo        | H420                        | [1cb944e646](https://linux-hardware.org/?probe=1cb944e646) | Aug 15, 2024 |
| Gigabyte      | Z97X-UD5H                   | [5c29098135](https://linux-hardware.org/?probe=5c29098135) | Aug 14, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [c7570156ec](https://linux-hardware.org/?probe=c7570156ec) | Aug 13, 2024 |
| Biostar       | G31D-M7                     | [71dfbf10b9](https://linux-hardware.org/?probe=71dfbf10b9) | Aug 13, 2024 |
| ASUSTek       | Maximus VII HERO            | [2063ec62ad](https://linux-hardware.org/?probe=2063ec62ad) | Aug 12, 2024 |
| MSI           | MPG X570S CARBON MAX WIF... | [d19f12645c](https://linux-hardware.org/?probe=d19f12645c) | Aug 12, 2024 |
| ASUSTek       | P5G41-M LX                  | [c6aa02cea8](https://linux-hardware.org/?probe=c6aa02cea8) | Aug 12, 2024 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [8422b2b4ea](https://linux-hardware.org/?probe=8422b2b4ea) | Aug 12, 2024 |
| HP            | 0AECh                       | [1c5baeab15](https://linux-hardware.org/?probe=1c5baeab15) | Aug 11, 2024 |
| ASRock        | Z370 Pro4                   | [6b7d85b5a8](https://linux-hardware.org/?probe=6b7d85b5a8) | Aug 11, 2024 |
| OEM           | Intel H81                   | [94a2e82a82](https://linux-hardware.org/?probe=94a2e82a82) | Aug 10, 2024 |
| ASRock        | B75 Pro3                    | [6ab1327d8e](https://linux-hardware.org/?probe=6ab1327d8e) | Aug 10, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [1e1acfa187](https://linux-hardware.org/?probe=1e1acfa187) | Aug 10, 2024 |
| ASUSTek       | H110M-A/M.2                 | [d40bcc40d2](https://linux-hardware.org/?probe=d40bcc40d2) | Aug 10, 2024 |
| Dell          | 08NPPY A00                  | [1b5d58c752](https://linux-hardware.org/?probe=1b5d58c752) | Aug 10, 2024 |
| Unknown       | Unknown                     | [cd77a3f765](https://linux-hardware.org/?probe=cd77a3f765) | Aug 09, 2024 |
| Dell          | 08NPPY A00                  | [f88978a24f](https://linux-hardware.org/?probe=f88978a24f) | Aug 09, 2024 |
| HP            | 802E                        | [58ed838fa5](https://linux-hardware.org/?probe=58ed838fa5) | Aug 09, 2024 |
| Dell          | 0C1R19 A01                  | [405cb25bf0](https://linux-hardware.org/?probe=405cb25bf0) | Aug 08, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [f4fe227b79](https://linux-hardware.org/?probe=f4fe227b79) | Aug 08, 2024 |
| Huanan        | X99-F8D V2.3                | [2b231c01bf](https://linux-hardware.org/?probe=2b231c01bf) | Aug 08, 2024 |
| HP            | 802E                        | [3dc5751041](https://linux-hardware.org/?probe=3dc5751041) | Aug 07, 2024 |
| Dell          | 0C2KJT A00                  | [d9536f5bdc](https://linux-hardware.org/?probe=d9536f5bdc) | Aug 06, 2024 |
| Gigabyte      | B85M-D3PH                   | [15a6c41a20](https://linux-hardware.org/?probe=15a6c41a20) | Aug 06, 2024 |
| Gigabyte      | B85M-D3PH                   | [003a4086b3](https://linux-hardware.org/?probe=003a4086b3) | Aug 06, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [72322fc02f](https://linux-hardware.org/?probe=72322fc02f) | Aug 05, 2024 |
| Dell          | 0C2KJT A00                  | [61f2261368](https://linux-hardware.org/?probe=61f2261368) | Aug 05, 2024 |
| HP            | 0B40h                       | [4e504e2f3a](https://linux-hardware.org/?probe=4e504e2f3a) | Aug 05, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [e5bcb293a4](https://linux-hardware.org/?probe=e5bcb293a4) | Aug 05, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | [578712aebe](https://linux-hardware.org/?probe=578712aebe) | Aug 04, 2024 |
| ASRock        | B450M Gaming                | [9c5b23d377](https://linux-hardware.org/?probe=9c5b23d377) | Aug 04, 2024 |
| MSI           | PRO B650-P WIFI             | [259f8a14d7](https://linux-hardware.org/?probe=259f8a14d7) | Aug 03, 2024 |
| HP            | 83F3                        | [8b1a108704](https://linux-hardware.org/?probe=8b1a108704) | Aug 03, 2024 |
| Intel         | X79M-S                      | [ae490654dd](https://linux-hardware.org/?probe=ae490654dd) | Aug 02, 2024 |
| Foxconn       | 2ABF                        | [aa9011109a](https://linux-hardware.org/?probe=aa9011109a) | Aug 02, 2024 |
| Gigabyte      | B450M DS3H-CF               | [9cd3c443d5](https://linux-hardware.org/?probe=9cd3c443d5) | Aug 02, 2024 |
| Gigabyte      | B450M DS3H-CF               | [25a6958d0f](https://linux-hardware.org/?probe=25a6958d0f) | Aug 02, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0b395a199b](https://linux-hardware.org/?probe=0b395a199b) | Aug 02, 2024 |
| HP            | 8054                        | [718b5d5274](https://linux-hardware.org/?probe=718b5d5274) | Aug 01, 2024 |
| HP            | 2AA2                        | [145f593604](https://linux-hardware.org/?probe=145f593604) | Aug 01, 2024 |
| Dell          | 0KYWH7 A01                  | [270c00f058](https://linux-hardware.org/?probe=270c00f058) | Jul 31, 2024 |
| Dell          | 0GDG8Y A00                  | [64d001394a](https://linux-hardware.org/?probe=64d001394a) | Jul 31, 2024 |
| MSI           | X470 GAMING PLUS MAX        | [eadf688d56](https://linux-hardware.org/?probe=eadf688d56) | Jul 30, 2024 |
| ASRock        | H310CM-HDV/M.2              | [8cd5ccd611](https://linux-hardware.org/?probe=8cd5ccd611) | Jul 30, 2024 |
| ASUSTek       | P5G41C-M                    | [1da51f7040](https://linux-hardware.org/?probe=1da51f7040) | Jul 30, 2024 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [24758c0301](https://linux-hardware.org/?probe=24758c0301) | Jul 30, 2024 |
| ASRock        | B550M-HVS SE                | [a7b15f0d48](https://linux-hardware.org/?probe=a7b15f0d48) | Jul 30, 2024 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | [abcceb4671](https://linux-hardware.org/?probe=abcceb4671) | Jul 30, 2024 |
| Intel         | X79F1 V2.0                  | [5d2cdcb140](https://linux-hardware.org/?probe=5d2cdcb140) | Jul 29, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [98dfe380f2](https://linux-hardware.org/?probe=98dfe380f2) | Jul 28, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [fcf665c644](https://linux-hardware.org/?probe=fcf665c644) | Jul 28, 2024 |
| ASUSTek       | Rampage V EXTREME           | [d305f053e4](https://linux-hardware.org/?probe=d305f053e4) | Jul 28, 2024 |
| Intel         | X79F1 V2.0                  | [a43b37cede](https://linux-hardware.org/?probe=a43b37cede) | Jul 27, 2024 |
| Gigabyte      | Z68X-UD4-B3                 | [007a26742b](https://linux-hardware.org/?probe=007a26742b) | Jul 27, 2024 |
| Foxconn       | H55MXV Series               | [9d2a5c4b9c](https://linux-hardware.org/?probe=9d2a5c4b9c) | Jul 26, 2024 |
| ASRock        | B550M PG Riptide            | [d4a82d0c2b](https://linux-hardware.org/?probe=d4a82d0c2b) | Jul 24, 2024 |
| MSI           | B85M-G43                    | [667048af27](https://linux-hardware.org/?probe=667048af27) | Jul 23, 2024 |
| ASUSTek       | Maximus VI IMPACT           | [02afbc4600](https://linux-hardware.org/?probe=02afbc4600) | Jul 23, 2024 |
| MSI           | Z370 GAMING PRO CARBON A... | [b0c0954f50](https://linux-hardware.org/?probe=b0c0954f50) | Jul 23, 2024 |
| Dell          | 0W0CHX A00                  | [48e627bbf5](https://linux-hardware.org/?probe=48e627bbf5) | Jul 22, 2024 |
| Gigabyte      | H97-D3H-CF                  | [f372a92cfa](https://linux-hardware.org/?probe=f372a92cfa) | Jul 21, 2024 |
| MSI           | X370 GAMING PRO CARBON      | [d1c5d7c110](https://linux-hardware.org/?probe=d1c5d7c110) | Jul 21, 2024 |
| ASUSTek       | PRIME X570-P                | [747f8d06d0](https://linux-hardware.org/?probe=747f8d06d0) | Jul 21, 2024 |
| ASUSTek       | A88XM-PLUS                  | [2b0ba480f8](https://linux-hardware.org/?probe=2b0ba480f8) | Jul 21, 2024 |
| Lenovo        | IdeaCentre K330             | [7962671df9](https://linux-hardware.org/?probe=7962671df9) | Jul 21, 2024 |
| Gigabyte      | H97-D3H-CF                  | [8f97d0913c](https://linux-hardware.org/?probe=8f97d0913c) | Jul 20, 2024 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [742fc54f71](https://linux-hardware.org/?probe=742fc54f71) | Jul 20, 2024 |
| MSI           | Z97 MPOWER                  | [9e981d7197](https://linux-hardware.org/?probe=9e981d7197) | Jul 19, 2024 |
| ASUSTek       | Rampage III Formula         | [376fbf2cba](https://linux-hardware.org/?probe=376fbf2cba) | Jul 19, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [67f8fcdd69](https://linux-hardware.org/?probe=67f8fcdd69) | Jul 19, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [bce1e4a580](https://linux-hardware.org/?probe=bce1e4a580) | Jul 19, 2024 |
| ASUSTek       | PRIME A320M-E               | [539493da66](https://linux-hardware.org/?probe=539493da66) | Jul 18, 2024 |
| MSI           | PRO Z690-A WIFI             | [43e0308d5f](https://linux-hardware.org/?probe=43e0308d5f) | Jul 18, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [57e7532fcd](https://linux-hardware.org/?probe=57e7532fcd) | Jul 18, 2024 |
| HP            | 83F2                        | [d30af24b31](https://linux-hardware.org/?probe=d30af24b31) | Jul 18, 2024 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [755ed47b23](https://linux-hardware.org/?probe=755ed47b23) | Jul 18, 2024 |
| ASUSTek       | H97-PLUS                    | [0064f13ebc](https://linux-hardware.org/?probe=0064f13ebc) | Jul 18, 2024 |
| Gigabyte      | H97-Gaming 3                | [d168a40603](https://linux-hardware.org/?probe=d168a40603) | Jul 17, 2024 |
| Gigabyte      | H97-Gaming 3                | [eb0bd9e0e4](https://linux-hardware.org/?probe=eb0bd9e0e4) | Jul 17, 2024 |
| Intel         | HM65DESK                    | [5610460f43](https://linux-hardware.org/?probe=5610460f43) | Jul 17, 2024 |
| Dell          | 07F37C A00                  | [65e747e381](https://linux-hardware.org/?probe=65e747e381) | Jul 17, 2024 |
| ASUSTek       | H97-PLUS                    | [188509cc48](https://linux-hardware.org/?probe=188509cc48) | Jul 16, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f2c0a826a4](https://linux-hardware.org/?probe=f2c0a826a4) | Jul 16, 2024 |
| MSI           | Z370 GAMING PRO CARBON A... | [cc6d4ce84a](https://linux-hardware.org/?probe=cc6d4ce84a) | Jul 16, 2024 |
| AMI           | Intel                       | [1efab61403](https://linux-hardware.org/?probe=1efab61403) | Jul 15, 2024 |
| HP            | 18E7                        | [a81a274c88](https://linux-hardware.org/?probe=a81a274c88) | Jul 15, 2024 |
| HP            | 2B2C                        | [e584455db2](https://linux-hardware.org/?probe=e584455db2) | Jul 14, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [4034455f1d](https://linux-hardware.org/?probe=4034455f1d) | Jul 14, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [84fb4b927a](https://linux-hardware.org/?probe=84fb4b927a) | Jul 14, 2024 |
| Gigabyte      | G41MT-S2P                   | [54823f9cdc](https://linux-hardware.org/?probe=54823f9cdc) | Jul 14, 2024 |
| ASUSTek       | P7H55-M                     | [05015c412f](https://linux-hardware.org/?probe=05015c412f) | Jul 13, 2024 |
| Dell          | 0KP561                      | [c6124f8409](https://linux-hardware.org/?probe=c6124f8409) | Jul 11, 2024 |
| Gigabyte      | 2AC8                        | [1e2a5ee6c4](https://linux-hardware.org/?probe=1e2a5ee6c4) | Jul 11, 2024 |
| ASUSTek       | K30BF_M32BF                 | [b863f86841](https://linux-hardware.org/?probe=b863f86841) | Jul 10, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [6d995ffeef](https://linux-hardware.org/?probe=6d995ffeef) | Jul 10, 2024 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [7b9b5db174](https://linux-hardware.org/?probe=7b9b5db174) | Jul 10, 2024 |
| ASUSTek       | PRIME H270M-PLUS            | [c0faa014a2](https://linux-hardware.org/?probe=c0faa014a2) | Jul 10, 2024 |
| MSI           | B550-A PRO                  | [cd3ea20f60](https://linux-hardware.org/?probe=cd3ea20f60) | Jul 09, 2024 |
| MSI           | B550-A PRO                  | [6613cedf60](https://linux-hardware.org/?probe=6613cedf60) | Jul 08, 2024 |
| HP            | 1495                        | [0a67df4ccd](https://linux-hardware.org/?probe=0a67df4ccd) | Jul 07, 2024 |
| Gigabyte      | Z68X-UD4-B3                 | [deca980aa2](https://linux-hardware.org/?probe=deca980aa2) | Jul 07, 2024 |
| ECS           | H61H2-M12                   | [7bcab0a14c](https://linux-hardware.org/?probe=7bcab0a14c) | Jul 07, 2024 |
| Dell          | 0VRWRC A00                  | [4548d660df](https://linux-hardware.org/?probe=4548d660df) | Jul 05, 2024 |
| Dell          | 0VRWRC A00                  | [63b605d9aa](https://linux-hardware.org/?probe=63b605d9aa) | Jul 05, 2024 |
| HP            | 82F1                        | [674aa5ccf0](https://linux-hardware.org/?probe=674aa5ccf0) | Jul 05, 2024 |
| MSI           | PRO B650-S WIFI             | [13e804d76d](https://linux-hardware.org/?probe=13e804d76d) | Jul 05, 2024 |
| Dell          | 0PC5F7 A00                  | [7b1c638bbb](https://linux-hardware.org/?probe=7b1c638bbb) | Jul 05, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [811ec78a14](https://linux-hardware.org/?probe=811ec78a14) | Jul 05, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [687f4a1e43](https://linux-hardware.org/?probe=687f4a1e43) | Jul 05, 2024 |
| Dell          | 00V62H A01                  | [2f05983248](https://linux-hardware.org/?probe=2f05983248) | Jul 05, 2024 |
| MSI           | A320M-A PRO MAX             | [497ab84801](https://linux-hardware.org/?probe=497ab84801) | Jul 05, 2024 |
| Gigabyte      | GA-970A-UD3                 | [3a5b3b17a9](https://linux-hardware.org/?probe=3a5b3b17a9) | Jul 05, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [2a6242fb25](https://linux-hardware.org/?probe=2a6242fb25) | Jul 04, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [2000b5b97c](https://linux-hardware.org/?probe=2000b5b97c) | Jul 04, 2024 |
| MSI           | PRO B760-VC WIFI            | [c7e0014220](https://linux-hardware.org/?probe=c7e0014220) | Jul 03, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | [fe2659f635](https://linux-hardware.org/?probe=fe2659f635) | Jul 02, 2024 |
| Gigabyte      | B550 GAMING X V2            | [b71aca2c54](https://linux-hardware.org/?probe=b71aca2c54) | Jul 02, 2024 |
| Google        | Buddy                       | [9850f5eaa6](https://linux-hardware.org/?probe=9850f5eaa6) | Jul 02, 2024 |
| Gigabyte      | H110M-H-CF                  | [76c9592d22](https://linux-hardware.org/?probe=76c9592d22) | Jul 02, 2024 |
| Gigabyte      | 990FXA-UD3                  | [d8060e3528](https://linux-hardware.org/?probe=d8060e3528) | Jul 01, 2024 |
| ASRock        | Wolfdale1333-D667           | [d7f5ce177c](https://linux-hardware.org/?probe=d7f5ce177c) | Jul 01, 2024 |
| ASUSTek       | M5A78L-M LX3                | [7e2d6ae5ec](https://linux-hardware.org/?probe=7e2d6ae5ec) | Jun 29, 2024 |
| BESSTAR Te... | UM350                       | [241717fe92](https://linux-hardware.org/?probe=241717fe92) | Jun 29, 2024 |
| Intel         | DB75EN AAG39650-303         | [c7975e249f](https://linux-hardware.org/?probe=c7975e249f) | Jun 29, 2024 |
| Intel         | DB75EN AAG39650-303         | [64a0ac84f4](https://linux-hardware.org/?probe=64a0ac84f4) | Jun 29, 2024 |
| Pegatron      | 2ACB                        | [88a6be55cc](https://linux-hardware.org/?probe=88a6be55cc) | Jun 29, 2024 |
| ASUSTek       | PRIME H510M-E               | [0c54b817e6](https://linux-hardware.org/?probe=0c54b817e6) | Jun 28, 2024 |
| Gigabyte      | Z170X-Gaming 7              | [ff2ce379be](https://linux-hardware.org/?probe=ff2ce379be) | Jun 28, 2024 |
| ASRock        | 970 Extreme3                | [563ffce561](https://linux-hardware.org/?probe=563ffce561) | Jun 28, 2024 |
| Acer          | Nitro N50-600 V:1.1         | [67616a4253](https://linux-hardware.org/?probe=67616a4253) | Jun 28, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | [e8d01ecf38](https://linux-hardware.org/?probe=e8d01ecf38) | Jun 27, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [34ac307ec2](https://linux-hardware.org/?probe=34ac307ec2) | Jun 27, 2024 |
| ASRock        | N100DC-ITX                  | [b1f1c48f11](https://linux-hardware.org/?probe=b1f1c48f11) | Jun 27, 2024 |
| ASUSTek       | M5A78L LE                   | [3c6f7d07fa](https://linux-hardware.org/?probe=3c6f7d07fa) | Jun 27, 2024 |
| Gigabyte      | B450 AORUS ELITE V2         | [8f8bc7a2dd](https://linux-hardware.org/?probe=8f8bc7a2dd) | Jun 26, 2024 |
| Intel         | H55                         | [e173beb86d](https://linux-hardware.org/?probe=e173beb86d) | Jun 26, 2024 |
| Intel         | H55                         | [e4b405726d](https://linux-hardware.org/?probe=e4b405726d) | Jun 26, 2024 |
| Dell          | 08NPPY A00                  | [a16f3c2982](https://linux-hardware.org/?probe=a16f3c2982) | Jun 25, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [c8f9823971](https://linux-hardware.org/?probe=c8f9823971) | Jun 25, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [4407bce46b](https://linux-hardware.org/?probe=4407bce46b) | Jun 25, 2024 |
| ASRock        | B365M-HDV                   | [bc488687bd](https://linux-hardware.org/?probe=bc488687bd) | Jun 25, 2024 |
| HP            | 1496                        | [697290ca7b](https://linux-hardware.org/?probe=697290ca7b) | Jun 24, 2024 |
| HP            | 1496                        | [732fe59724](https://linux-hardware.org/?probe=732fe59724) | Jun 24, 2024 |
| ASRock        | B365M-HDV                   | [4a3bb5f053](https://linux-hardware.org/?probe=4a3bb5f053) | Jun 24, 2024 |
| Lenovo        | 3706 NOK                    | [c281c31cf0](https://linux-hardware.org/?probe=c281c31cf0) | Jun 24, 2024 |
| MSI           | MEG Z490 UNIFY              | [a41d8af1bf](https://linux-hardware.org/?probe=a41d8af1bf) | Jun 23, 2024 |
| GEEKOM        | Mini IT12                   | [31bd93719f](https://linux-hardware.org/?probe=31bd93719f) | Jun 23, 2024 |
| Gigabyte      | Z77X-UP4 TH                 | [70868b4564](https://linux-hardware.org/?probe=70868b4564) | Jun 23, 2024 |
| Gigabyte      | G41MT-S2PT                  | [347663d539](https://linux-hardware.org/?probe=347663d539) | Jun 23, 2024 |
| HP            | 83E1                        | [7eba4ae3ce](https://linux-hardware.org/?probe=7eba4ae3ce) | Jun 23, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [ea2fec59e5](https://linux-hardware.org/?probe=ea2fec59e5) | Jun 23, 2024 |
| Dell          | 0HD5W2 A01                  | [8405915abd](https://linux-hardware.org/?probe=8405915abd) | Jun 22, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [5920bffb0e](https://linux-hardware.org/?probe=5920bffb0e) | Jun 22, 2024 |
| ASUSTek       | P8Z77-V DELUXE              | [7213917f20](https://linux-hardware.org/?probe=7213917f20) | Jun 22, 2024 |
| ASUSTek       | P8Z77-V DELUXE              | [9d29e07483](https://linux-hardware.org/?probe=9d29e07483) | Jun 22, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [4a7ecd6fee](https://linux-hardware.org/?probe=4a7ecd6fee) | Jun 22, 2024 |
| Dell          | 048DY8 A01                  | [24b75bf751](https://linux-hardware.org/?probe=24b75bf751) | Jun 22, 2024 |
| ASUSTek       | M5A99X EVO R2.0             | [2a22fc7970](https://linux-hardware.org/?probe=2a22fc7970) | Jun 22, 2024 |
| Lenovo        | 3706 NOK                    | [059d6e5256](https://linux-hardware.org/?probe=059d6e5256) | Jun 21, 2024 |
| Dell          | 0XCR8D A00                  | [2518c5257b](https://linux-hardware.org/?probe=2518c5257b) | Jun 21, 2024 |
| Gigabyte      | B450M DS3H-CF               | [9ecc5174a0](https://linux-hardware.org/?probe=9ecc5174a0) | Jun 21, 2024 |
| Gigabyte      | B450 AORUS ELITE V2         | [2b6036029d](https://linux-hardware.org/?probe=2b6036029d) | Jun 20, 2024 |
| Intel         | X99-P4 V1.0                 | [54e7735d9d](https://linux-hardware.org/?probe=54e7735d9d) | Jun 20, 2024 |
| Dell          | 0D24M8 A01                  | [2cdf2b71a1](https://linux-hardware.org/?probe=2cdf2b71a1) | Jun 20, 2024 |
| OEM           | X99-Turbo                   | [4690143a6c](https://linux-hardware.org/?probe=4690143a6c) | Jun 20, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [fc938957da](https://linux-hardware.org/?probe=fc938957da) | Jun 20, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [5dc928988a](https://linux-hardware.org/?probe=5dc928988a) | Jun 20, 2024 |
| Gigabyte      | H110M-H-CF                  | [0a37394d73](https://linux-hardware.org/?probe=0a37394d73) | Jun 19, 2024 |
| Dell          | 0PC5F7 A00                  | [46359a3c9f](https://linux-hardware.org/?probe=46359a3c9f) | Jun 19, 2024 |
| HP            | 1998                        | [cccee42308](https://linux-hardware.org/?probe=cccee42308) | Jun 19, 2024 |
| HP            | 1998                        | [ee549aa7c5](https://linux-hardware.org/?probe=ee549aa7c5) | Jun 19, 2024 |
| ASUSTek       | PRIME B250M-K               | [01f026ddaa](https://linux-hardware.org/?probe=01f026ddaa) | Jun 19, 2024 |
| ASUSTek       | PRIME B250M-K               | [0ff135390e](https://linux-hardware.org/?probe=0ff135390e) | Jun 18, 2024 |
| ASUSTek       | Rampage V EXTREME           | [84659788e8](https://linux-hardware.org/?probe=84659788e8) | Jun 18, 2024 |
| ASRock        | B550 Phantom Gaming-ITX/... | [e691440c04](https://linux-hardware.org/?probe=e691440c04) | Jun 18, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1bcea64f89](https://linux-hardware.org/?probe=1bcea64f89) | Jun 18, 2024 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [16e15084e4](https://linux-hardware.org/?probe=16e15084e4) | Jun 18, 2024 |
| Gigabyte      | F2A88X-UP4                  | [0c0aa2515c](https://linux-hardware.org/?probe=0c0aa2515c) | Jun 18, 2024 |
| ASUSTek       | CM6731_CM6431_CM6331        | [05e39b7f74](https://linux-hardware.org/?probe=05e39b7f74) | Jun 18, 2024 |
| MSI           | MEG Z490 UNIFY              | [c635186519](https://linux-hardware.org/?probe=c635186519) | Jun 18, 2024 |
| MSI           | H61M-P20                    | [faf4f9d4c0](https://linux-hardware.org/?probe=faf4f9d4c0) | Jun 17, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | [9310315283](https://linux-hardware.org/?probe=9310315283) | Jun 15, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [e9c06e7f92](https://linux-hardware.org/?probe=e9c06e7f92) | Jun 15, 2024 |
| HP            | 3647h                       | [859770d7b5](https://linux-hardware.org/?probe=859770d7b5) | Jun 15, 2024 |
| Dell          | 0WR7PY A03                  | [3b5179dcbe](https://linux-hardware.org/?probe=3b5179dcbe) | Jun 15, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [a36f6851fe](https://linux-hardware.org/?probe=a36f6851fe) | Jun 14, 2024 |
| ASRock        | 970 Extreme3                | [801978ff22](https://linux-hardware.org/?probe=801978ff22) | Jun 13, 2024 |
| MSI           | Z370 GAMING PRO CARBON      | [1e9836317d](https://linux-hardware.org/?probe=1e9836317d) | Jun 13, 2024 |
| Acer          | Aspire XC-1780              | [8b2550f530](https://linux-hardware.org/?probe=8b2550f530) | Jun 13, 2024 |
| ASUSTek       | P6X58D-E                    | [78a00f04ae](https://linux-hardware.org/?probe=78a00f04ae) | Jun 13, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [8d41eec671](https://linux-hardware.org/?probe=8d41eec671) | Jun 13, 2024 |
| Dell          | 0F5C5X A00                  | [8db1dee6a9](https://linux-hardware.org/?probe=8db1dee6a9) | Jun 13, 2024 |
| Dell          | 07N90W A02                  | [182ba2b5cd](https://linux-hardware.org/?probe=182ba2b5cd) | Jun 12, 2024 |
| Dell          | 04JGCK A01                  | [526e6f9dde](https://linux-hardware.org/?probe=526e6f9dde) | Jun 12, 2024 |
| GEEKOM        | Mini IT13                   | [a77767e25f](https://linux-hardware.org/?probe=a77767e25f) | Jun 11, 2024 |
| Gigabyte      | F2A55M-HD2                  | [b150413a21](https://linux-hardware.org/?probe=b150413a21) | Jun 11, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [433a3215e8](https://linux-hardware.org/?probe=433a3215e8) | Jun 10, 2024 |
| Gigabyte      | F2A88X-UP4                  | [385923ca25](https://linux-hardware.org/?probe=385923ca25) | Jun 10, 2024 |
| ASUSTek       | P8Z77-V LK                  | [c213ea08a9](https://linux-hardware.org/?probe=c213ea08a9) | Jun 09, 2024 |
| Shenzhen M... | AHWSA                       | [045c9b575c](https://linux-hardware.org/?probe=045c9b575c) | Jun 09, 2024 |
| HP            | 86FC MVB                    | [8893d3db7d](https://linux-hardware.org/?probe=8893d3db7d) | Jun 09, 2024 |
| Unknown       | Unknown                     | [dd41666ea6](https://linux-hardware.org/?probe=dd41666ea6) | Jun 09, 2024 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [7f0c1bcf56](https://linux-hardware.org/?probe=7f0c1bcf56) | Jun 08, 2024 |
| MSI           | B550-A PRO                  | [6cd484c0d1](https://linux-hardware.org/?probe=6cd484c0d1) | Jun 08, 2024 |
| Simply NUC    | NUC13OXv9B                  | [1b387b937c](https://linux-hardware.org/?probe=1b387b937c) | Jun 07, 2024 |
| Simply NUC    | NUC13OXv9B                  | [63ec0d6774](https://linux-hardware.org/?probe=63ec0d6774) | Jun 07, 2024 |
| ASUSTek       | Rampage V EXTREME           | [937bf0ad3d](https://linux-hardware.org/?probe=937bf0ad3d) | Jun 06, 2024 |
| ASUSTek       | PRIME A320M-K               | [3b97096fe8](https://linux-hardware.org/?probe=3b97096fe8) | Jun 06, 2024 |
| ASUSTek       | Z87I-PRO                    | [b07dfdb192](https://linux-hardware.org/?probe=b07dfdb192) | Jun 06, 2024 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [eeaf7933b5](https://linux-hardware.org/?probe=eeaf7933b5) | Jun 06, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [7e1173c163](https://linux-hardware.org/?probe=7e1173c163) | Jun 06, 2024 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [113ebcd7cf](https://linux-hardware.org/?probe=113ebcd7cf) | Jun 05, 2024 |
| ASRock        | H81M-HDS                    | [45e878f6c6](https://linux-hardware.org/?probe=45e878f6c6) | Jun 04, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | [142fbd5e4d](https://linux-hardware.org/?probe=142fbd5e4d) | Jun 04, 2024 |
| Gigabyte      | Z690 UD AX DDR4             | [5a1a134b18](https://linux-hardware.org/?probe=5a1a134b18) | Jun 04, 2024 |
| ASUSTek       | P5KPL-VM                    | [eb6bf209db](https://linux-hardware.org/?probe=eb6bf209db) | Jun 04, 2024 |
| Gigabyte      | A520 AORUS ELITE            | [550e710714](https://linux-hardware.org/?probe=550e710714) | Jun 03, 2024 |
| Gigabyte      | B450 AORUS M                | [b843ca7c74](https://linux-hardware.org/?probe=b843ca7c74) | Jun 03, 2024 |
| HP            | 8055                        | [b259f209ba](https://linux-hardware.org/?probe=b259f209ba) | Jun 03, 2024 |
| Dell          | 0GM819                      | [aa16fce025](https://linux-hardware.org/?probe=aa16fce025) | Jun 02, 2024 |
| MSI           | B150M BAZOOKA PLUS          | [b64ff0d990](https://linux-hardware.org/?probe=b64ff0d990) | Jun 02, 2024 |
| HP            | 8061                        | [e5fc57bd4c](https://linux-hardware.org/?probe=e5fc57bd4c) | Jun 02, 2024 |
| Dell          | 0NKW6Y A00                  | [11b9dc77a8](https://linux-hardware.org/?probe=11b9dc77a8) | Jun 01, 2024 |
| Dell          | 09WH54 A00                  | [7cc20d86bb](https://linux-hardware.org/?probe=7cc20d86bb) | Jun 01, 2024 |
| Intel         | DH61BF AAG81311-102         | [e33f8a4718](https://linux-hardware.org/?probe=e33f8a4718) | Jun 01, 2024 |
| AMD           | A520                        | [70342967ba](https://linux-hardware.org/?probe=70342967ba) | Jun 01, 2024 |
| Intel         | DQ77MK AAG39642-500         | [03352367e1](https://linux-hardware.org/?probe=03352367e1) | May 31, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1e996d4684](https://linux-hardware.org/?probe=1e996d4684) | May 31, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [c149b1e744](https://linux-hardware.org/?probe=c149b1e744) | May 31, 2024 |
| Dell          | 0N826N A01                  | [9b8babfe9b](https://linux-hardware.org/?probe=9b8babfe9b) | May 30, 2024 |
| ASRock        | Z790 Pro RS                 | [6eef2066b7](https://linux-hardware.org/?probe=6eef2066b7) | May 30, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | [0ed14496f1](https://linux-hardware.org/?probe=0ed14496f1) | May 30, 2024 |
| ASRock        | H310M-ITX/ac                | [a81cb3838b](https://linux-hardware.org/?probe=a81cb3838b) | May 29, 2024 |
| ASRock        | B450 Pro4                   | [2c7477ec0f](https://linux-hardware.org/?probe=2c7477ec0f) | May 29, 2024 |
| ASUSTek       | P8P67                       | [4f259e1879](https://linux-hardware.org/?probe=4f259e1879) | May 29, 2024 |
| Gigabyte      | B550M DS3H                  | [248bbb1f38](https://linux-hardware.org/?probe=248bbb1f38) | May 28, 2024 |
| ASUSTek       | P8P67                       | [27bd573017](https://linux-hardware.org/?probe=27bd573017) | May 28, 2024 |
| Intel         | HM65DESK                    | [409e1dd9dd](https://linux-hardware.org/?probe=409e1dd9dd) | May 28, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | [96a5a5f044](https://linux-hardware.org/?probe=96a5a5f044) | May 28, 2024 |
| Dell          | 06X1TJ A00                  | [ecf96aec64](https://linux-hardware.org/?probe=ecf96aec64) | May 28, 2024 |
| Dell          | 0YXT71 A03                  | [f479ae953e](https://linux-hardware.org/?probe=f479ae953e) | May 27, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [64d0817408](https://linux-hardware.org/?probe=64d0817408) | May 27, 2024 |
| Intel         | HM65DESK                    | [be8146dbdd](https://linux-hardware.org/?probe=be8146dbdd) | May 27, 2024 |
| ASRock        | B85M Pro4                   | [78ed1f5f67](https://linux-hardware.org/?probe=78ed1f5f67) | May 26, 2024 |
| Foxconn       | Irvine HP P/N               | [d82937f6cf](https://linux-hardware.org/?probe=d82937f6cf) | May 26, 2024 |
| ZOTAC         | AMD HUDSON-M1               | [3bcc9158f0](https://linux-hardware.org/?probe=3bcc9158f0) | May 26, 2024 |
| ZOTAC         | AMD HUDSON-M1               | [f8899b739a](https://linux-hardware.org/?probe=f8899b739a) | May 26, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [6523f3e29a](https://linux-hardware.org/?probe=6523f3e29a) | May 25, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [5c6a5a3f0c](https://linux-hardware.org/?probe=5c6a5a3f0c) | May 24, 2024 |
| Dell          | 0TP412                      | [d78622c7e2](https://linux-hardware.org/?probe=d78622c7e2) | May 24, 2024 |
| Dell          | 018D1Y A00                  | [10d18b74b7](https://linux-hardware.org/?probe=10d18b74b7) | May 24, 2024 |
| Dell          | 05XGC8 A01                  | [4b62db7f29](https://linux-hardware.org/?probe=4b62db7f29) | May 21, 2024 |
| ASRock        | Z490M Pro4                  | [d1b9fe839b](https://linux-hardware.org/?probe=d1b9fe839b) | May 21, 2024 |
| GEEKOM        | Mini IT12                   | [9c26a93c58](https://linux-hardware.org/?probe=9c26a93c58) | May 21, 2024 |
| Unknown       | AB07C                       | [c3707f019e](https://linux-hardware.org/?probe=c3707f019e) | May 20, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [57794688a5](https://linux-hardware.org/?probe=57794688a5) | May 20, 2024 |
| Dell          | 018D1Y A00                  | [41cef7a181](https://linux-hardware.org/?probe=41cef7a181) | May 20, 2024 |
| HP            | 8105                        | [a19b444b72](https://linux-hardware.org/?probe=a19b444b72) | May 19, 2024 |
| ASUSTek       | PRIME X570-PRO              | [fbc31b1a58](https://linux-hardware.org/?probe=fbc31b1a58) | May 19, 2024 |
| Intel         | TH510-D4 v2.3               | [d1382cd7f8](https://linux-hardware.org/?probe=d1382cd7f8) | May 19, 2024 |
| Biostar       | A68N-2100E                  | [d751496ef5](https://linux-hardware.org/?probe=d751496ef5) | May 19, 2024 |
| Gigabyte      | B85M-D3H                    | [07870d5c5d](https://linux-hardware.org/?probe=07870d5c5d) | May 19, 2024 |
| BESSTAR Te... | HM90                        | [cde83725e7](https://linux-hardware.org/?probe=cde83725e7) | May 18, 2024 |
| Gigabyte      | Q270M-D3H                   | [11ae7a8461](https://linux-hardware.org/?probe=11ae7a8461) | May 18, 2024 |
| ASUSTek       | PRIME H370-A                | [a8ece004b8](https://linux-hardware.org/?probe=a8ece004b8) | May 18, 2024 |
| Gigabyte      | P41-ES3G                    | [169e3458d5](https://linux-hardware.org/?probe=169e3458d5) | May 18, 2024 |
| BESSTAR Te... | HM90                        | [5a9e195b3c](https://linux-hardware.org/?probe=5a9e195b3c) | May 17, 2024 |
| MSI           | B150M BAZOOKA PLUS          | [0a84f22ff7](https://linux-hardware.org/?probe=0a84f22ff7) | May 17, 2024 |
| Dell          | 0HD5W2 A01                  | [7dba2b2096](https://linux-hardware.org/?probe=7dba2b2096) | May 17, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [a33b0eef1c](https://linux-hardware.org/?probe=a33b0eef1c) | May 17, 2024 |
| Dell          | 08NPPY A00                  | [3e313633af](https://linux-hardware.org/?probe=3e313633af) | May 16, 2024 |
| MSI           | X58 Pro-E                   | [3702db3a4c](https://linux-hardware.org/?probe=3702db3a4c) | May 14, 2024 |
| Acer          | Veriton X4620G v1.0         | [0bdc1651c3](https://linux-hardware.org/?probe=0bdc1651c3) | May 14, 2024 |
| HC Technol... | HCAR5000-MI                 | [a8c6e1d54a](https://linux-hardware.org/?probe=a8c6e1d54a) | May 13, 2024 |
| Gigabyte      | EP43-DS3LR                  | [e82835983b](https://linux-hardware.org/?probe=e82835983b) | May 13, 2024 |
| ASUSTek       | P5QL PRO                    | [acd53ca948](https://linux-hardware.org/?probe=acd53ca948) | May 13, 2024 |
| ASUSTek       | P5QL PRO                    | [9cf04d890a](https://linux-hardware.org/?probe=9cf04d890a) | May 13, 2024 |
| Dell          | 0D6H9T A01                  | [fe8da11f5b](https://linux-hardware.org/?probe=fe8da11f5b) | May 13, 2024 |
| Gigabyte      | Z390 DESIGNARE-CF           | [f7c5a6e0ba](https://linux-hardware.org/?probe=f7c5a6e0ba) | May 12, 2024 |
| Gigabyte      | F2A68HM-DS2                 | [dc6896f24a](https://linux-hardware.org/?probe=dc6896f24a) | May 12, 2024 |
| ASUSTek       | PRIME A320M-K               | [b77ea29a30](https://linux-hardware.org/?probe=b77ea29a30) | May 12, 2024 |
| Lenovo        | NO DPK                      | [c966bf3114](https://linux-hardware.org/?probe=c966bf3114) | May 11, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3455c4e687](https://linux-hardware.org/?probe=3455c4e687) | May 11, 2024 |
| Dell          | 0HY9JP A02                  | [f798ace200](https://linux-hardware.org/?probe=f798ace200) | May 10, 2024 |
| ASUSTek       | H81M-CS/BR                  | [3fd42d5154](https://linux-hardware.org/?probe=3fd42d5154) | May 10, 2024 |
| ASUSTek       | PRIME H370-A                | [c1a4231ea2](https://linux-hardware.org/?probe=c1a4231ea2) | May 09, 2024 |
| MSI           | H310M PRO-VD                | [586c4844be](https://linux-hardware.org/?probe=586c4844be) | May 09, 2024 |
| Lenovo        | 110536U ThinkServer TS13... | [d3196733cd](https://linux-hardware.org/?probe=d3196733cd) | May 08, 2024 |
| ASUSTek       | P8H77-V LE                  | [e896127dc3](https://linux-hardware.org/?probe=e896127dc3) | May 08, 2024 |
| Unknown       | Unknown                     | [14f9a58589](https://linux-hardware.org/?probe=14f9a58589) | May 08, 2024 |
| GEEKOM        | Mini IT12                   | [bf478cb069](https://linux-hardware.org/?probe=bf478cb069) | May 06, 2024 |
| HP            | 8906 SMVB                   | [16dcd59b91](https://linux-hardware.org/?probe=16dcd59b91) | May 06, 2024 |
| Medion        | MS-7366                     | [0c36270a48](https://linux-hardware.org/?probe=0c36270a48) | May 06, 2024 |
| MSI           | PRO X670-P WIFI             | [a411b722e3](https://linux-hardware.org/?probe=a411b722e3) | May 05, 2024 |
| Unknown       | Unknown                     | [d676549abd](https://linux-hardware.org/?probe=d676549abd) | May 05, 2024 |
| ASRock        | B450M-HDV R4.0              | [fc52b48b01](https://linux-hardware.org/?probe=fc52b48b01) | May 05, 2024 |
| ECS           | P45T-A                      | [c1f450f8a1](https://linux-hardware.org/?probe=c1f450f8a1) | May 04, 2024 |
| Gigabyte      | EP43-S3L                    | [96cd4e9337](https://linux-hardware.org/?probe=96cd4e9337) | May 04, 2024 |
| Gigabyte      | H61M-S2P                    | [157cc8b4cc](https://linux-hardware.org/?probe=157cc8b4cc) | May 04, 2024 |
| GEEKOM        | Mini IT12                   | [d1264f51d1](https://linux-hardware.org/?probe=d1264f51d1) | May 03, 2024 |
| Gigabyte      | H81M-S1                     | [b0e189e984](https://linux-hardware.org/?probe=b0e189e984) | May 03, 2024 |
| Gigabyte      | H81M-S1                     | [8bc865780b](https://linux-hardware.org/?probe=8bc865780b) | May 03, 2024 |
| Dell          | 0773VG A02                  | [2eb962e78c](https://linux-hardware.org/?probe=2eb962e78c) | May 03, 2024 |
| Biostar       | B450MHP                     | [5d30a1821f](https://linux-hardware.org/?probe=5d30a1821f) | May 02, 2024 |
| ASUSTek       | PRIME A520M-A II            | [49bbc3443a](https://linux-hardware.org/?probe=49bbc3443a) | May 02, 2024 |
| Gigabyte      | H97-HD3                     | [98d2071b97](https://linux-hardware.org/?probe=98d2071b97) | May 01, 2024 |
| Lenovo        | ThinkCentre M91p 7005AK8    | [8eeaa81159](https://linux-hardware.org/?probe=8eeaa81159) | Apr 30, 2024 |
| Gigabyte      | H61M-S1                     | [4067e2b325](https://linux-hardware.org/?probe=4067e2b325) | Apr 30, 2024 |
| Gigabyte      | H61M-S1                     | [ea6fdbe20e](https://linux-hardware.org/?probe=ea6fdbe20e) | Apr 30, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | [c4d5dca0ad](https://linux-hardware.org/?probe=c4d5dca0ad) | Apr 30, 2024 |
| NCR           | Pocono                      | [b0073723fe](https://linux-hardware.org/?probe=b0073723fe) | Apr 29, 2024 |
| ASUSTek       | P8H61-I R2.0                | [2e6e9ca3ee](https://linux-hardware.org/?probe=2e6e9ca3ee) | Apr 29, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [a036c4124f](https://linux-hardware.org/?probe=a036c4124f) | Apr 29, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [9b8290696d](https://linux-hardware.org/?probe=9b8290696d) | Apr 29, 2024 |
| HP            | 3398                        | [e412887ebc](https://linux-hardware.org/?probe=e412887ebc) | Apr 29, 2024 |
| Dell          | 06D7TR A00                  | [43e7eeb6e7](https://linux-hardware.org/?probe=43e7eeb6e7) | Apr 28, 2024 |
| Gigabyte      | H61M-S2PV                   | [c3bf425427](https://linux-hardware.org/?probe=c3bf425427) | Apr 27, 2024 |
| AOpen         | D1009 A1A4                  | [d8b2d00731](https://linux-hardware.org/?probe=d8b2d00731) | Apr 27, 2024 |
| ASUSTek       | P8Z77-M PRO                 | [686e6cab2f](https://linux-hardware.org/?probe=686e6cab2f) | Apr 26, 2024 |
| ASUSTek       | M2R-FVM                     | [90232f8ff9](https://linux-hardware.org/?probe=90232f8ff9) | Apr 26, 2024 |
| ASUSTek       | M2R-FVM                     | [fc2624bc84](https://linux-hardware.org/?probe=fc2624bc84) | Apr 26, 2024 |
| Positivo      | POS-PIQ77CL                 | [ca5ecf0b4c](https://linux-hardware.org/?probe=ca5ecf0b4c) | Apr 25, 2024 |
| Gigabyte      | F2A68HM-HD2                 | [4f56e23067](https://linux-hardware.org/?probe=4f56e23067) | Apr 25, 2024 |
| Unknown       | Unknown                     | [c226f7eee7](https://linux-hardware.org/?probe=c226f7eee7) | Apr 25, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [713bf3357d](https://linux-hardware.org/?probe=713bf3357d) | Apr 24, 2024 |
| ASUSTek       | P8H67-I                     | [0d76590ae1](https://linux-hardware.org/?probe=0d76590ae1) | Apr 24, 2024 |
| Dell          | 0VRWRC A00                  | [19c02bd31c](https://linux-hardware.org/?probe=19c02bd31c) | Apr 23, 2024 |
| ASUSTek       | P5G41T-M LX2/BR             | [7e16d97409](https://linux-hardware.org/?probe=7e16d97409) | Apr 22, 2024 |
| Biostar       | H61MLV3                     | [a383411310](https://linux-hardware.org/?probe=a383411310) | Apr 21, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [84aa58d0c4](https://linux-hardware.org/?probe=84aa58d0c4) | Apr 21, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [ef45ce093c](https://linux-hardware.org/?probe=ef45ce093c) | Apr 20, 2024 |
| HP            | 1632                        | [1a23bb9aba](https://linux-hardware.org/?probe=1a23bb9aba) | Apr 19, 2024 |
| HP            | 1632                        | [2d11bc974f](https://linux-hardware.org/?probe=2d11bc974f) | Apr 18, 2024 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [886d3b50ff](https://linux-hardware.org/?probe=886d3b50ff) | Apr 18, 2024 |
| ASRock        | A520M-HDV                   | [9a415b8705](https://linux-hardware.org/?probe=9a415b8705) | Apr 17, 2024 |
| ASUSTek       | H110M-CS                    | [551218b127](https://linux-hardware.org/?probe=551218b127) | Apr 17, 2024 |
| HP            | 1495                        | [cd403691ad](https://linux-hardware.org/?probe=cd403691ad) | Apr 16, 2024 |
| HP            | 8299                        | [1a596e43da](https://linux-hardware.org/?probe=1a596e43da) | Apr 15, 2024 |
| ASRock        | A520M-HDV                   | [56905e2bc8](https://linux-hardware.org/?probe=56905e2bc8) | Apr 15, 2024 |
| HP            | 8299                        | [aa03fa8e4c](https://linux-hardware.org/?probe=aa03fa8e4c) | Apr 15, 2024 |
| ASRock        | A520M-HDV                   | [47e7cdb053](https://linux-hardware.org/?probe=47e7cdb053) | Apr 15, 2024 |
| MSI           | B250M BAZOOKA               | [b2b7ae9a04](https://linux-hardware.org/?probe=b2b7ae9a04) | Apr 15, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [f65f90469b](https://linux-hardware.org/?probe=f65f90469b) | Apr 14, 2024 |
| Dell          | 0NK5PH A00                  | [f0cf8ecdba](https://linux-hardware.org/?probe=f0cf8ecdba) | Apr 14, 2024 |
| Gigabyte      | F2A68HM-DS2                 | [62cafd8bff](https://linux-hardware.org/?probe=62cafd8bff) | Apr 13, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | [e2bf219dba](https://linux-hardware.org/?probe=e2bf219dba) | Apr 13, 2024 |
| Dell          | 0T10XW A00                  | [f899cbf1fc](https://linux-hardware.org/?probe=f899cbf1fc) | Apr 12, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [9eed5870ee](https://linux-hardware.org/?probe=9eed5870ee) | Apr 12, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | [d0eaff6eb9](https://linux-hardware.org/?probe=d0eaff6eb9) | Apr 11, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [33e3402952](https://linux-hardware.org/?probe=33e3402952) | Apr 11, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [11e58d238c](https://linux-hardware.org/?probe=11e58d238c) | Apr 11, 2024 |
| NCR           | Pocono                      | [fb4ef04821](https://linux-hardware.org/?probe=fb4ef04821) | Apr 10, 2024 |
| Pegatron      | 2A73h                       | [941a2d0e0d](https://linux-hardware.org/?probe=941a2d0e0d) | Apr 10, 2024 |
| HP            | 339A                        | [e7fb50b1c8](https://linux-hardware.org/?probe=e7fb50b1c8) | Apr 09, 2024 |
| Intel         | H61                         | [cfc6e7e901](https://linux-hardware.org/?probe=cfc6e7e901) | Apr 09, 2024 |
| Alienware     | 0T76PD A01                  | [79ec44cce4](https://linux-hardware.org/?probe=79ec44cce4) | Apr 09, 2024 |
| MSI           | B450M-A PRO MAX             | [6f8f2695ef](https://linux-hardware.org/?probe=6f8f2695ef) | Apr 08, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | [334edc82aa](https://linux-hardware.org/?probe=334edc82aa) | Apr 07, 2024 |
| MSI           | MPG B550 GAMING PLUS        | [87b303490c](https://linux-hardware.org/?probe=87b303490c) | Apr 07, 2024 |
| Dell          | 0V8WGR A02                  | [c8eb38c52c](https://linux-hardware.org/?probe=c8eb38c52c) | Apr 07, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [42e382179c](https://linux-hardware.org/?probe=42e382179c) | Apr 07, 2024 |
| Gigabyte      | G41M-Combo                  | [4fa66fe035](https://linux-hardware.org/?probe=4fa66fe035) | Apr 07, 2024 |
| HP            | 1905                        | [d55405d144](https://linux-hardware.org/?probe=d55405d144) | Apr 06, 2024 |
| STGAUBRON     | B75M4 V1.1                  | [243f4caa39](https://linux-hardware.org/?probe=243f4caa39) | Apr 05, 2024 |
| Dell          | 08HPGT A01                  | [355095de09](https://linux-hardware.org/?probe=355095de09) | Apr 05, 2024 |
| Dell          | 08HPGT A01                  | [8d0476dbc7](https://linux-hardware.org/?probe=8d0476dbc7) | Apr 05, 2024 |
| ASRock        | H81M-HDS                    | [068539b9ec](https://linux-hardware.org/?probe=068539b9ec) | Apr 05, 2024 |
| Unknown       | 1.0                         | [a9918419c7](https://linux-hardware.org/?probe=a9918419c7) | Apr 03, 2024 |
| Foxconn       | G31MX Series                | [283c7c622c](https://linux-hardware.org/?probe=283c7c622c) | Apr 03, 2024 |
| Gateway       | SX2851                      | [099ecc5b59](https://linux-hardware.org/?probe=099ecc5b59) | Apr 03, 2024 |
| Pegatron      | JESSE                       | [1f14f883ca](https://linux-hardware.org/?probe=1f14f883ca) | Apr 02, 2024 |
| Gigabyte      | B450M S2H                   | [1d0e019001](https://linux-hardware.org/?probe=1d0e019001) | Apr 01, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [efd659b2da](https://linux-hardware.org/?probe=efd659b2da) | Apr 01, 2024 |
| ASRock        | H310CM-DVS                  | [c543e25407](https://linux-hardware.org/?probe=c543e25407) | Mar 31, 2024 |
| ASRock        | H310CM-DVS                  | [39914bc3e6](https://linux-hardware.org/?probe=39914bc3e6) | Mar 31, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | [c32641d945](https://linux-hardware.org/?probe=c32641d945) | Mar 31, 2024 |
| ASRock        | 990FX Extreme3              | [1c846440f3](https://linux-hardware.org/?probe=1c846440f3) | Mar 30, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | [2fa735d18d](https://linux-hardware.org/?probe=2fa735d18d) | Mar 30, 2024 |
| Unknown       | Unknown                     | [cd151074ab](https://linux-hardware.org/?probe=cd151074ab) | Mar 30, 2024 |
| Gigabyte      | Z87X-UD5H-CF                | [890d342e54](https://linux-hardware.org/?probe=890d342e54) | Mar 30, 2024 |
| Dell          | 051FJ8 A01                  | [05e406828c](https://linux-hardware.org/?probe=05e406828c) | Mar 29, 2024 |
| MSI           | B550-A PRO                  | [da4de8a0b3](https://linux-hardware.org/?probe=da4de8a0b3) | Mar 29, 2024 |
| ASRock        | 980DE3/U3S3 R2.0            | [31798dfffc](https://linux-hardware.org/?probe=31798dfffc) | Mar 29, 2024 |
| ASUSTek       | TUF Gaming B550-PRO         | [81603f2f58](https://linux-hardware.org/?probe=81603f2f58) | Mar 29, 2024 |
| ASRock        | Z87 Extreme6                | [eaf00b2d47](https://linux-hardware.org/?probe=eaf00b2d47) | Mar 29, 2024 |
| Gigabyte      | G41M-Combo                  | [de15aa9a55](https://linux-hardware.org/?probe=de15aa9a55) | Mar 29, 2024 |
| HP            | 0B54h D                     | [e7d521b51c](https://linux-hardware.org/?probe=e7d521b51c) | Mar 28, 2024 |
| Intel         | D2700MUD AAG32419-602       | [52eec4d012](https://linux-hardware.org/?probe=52eec4d012) | Mar 28, 2024 |
| ASRock        | Z87 Extreme6                | [0980c3538e](https://linux-hardware.org/?probe=0980c3538e) | Mar 28, 2024 |
| Gigabyte      | GA-880GM-USB3               | [77bf8490e6](https://linux-hardware.org/?probe=77bf8490e6) | Mar 28, 2024 |
| Gigabyte      | Q87M-D2H                    | [7de05d2618](https://linux-hardware.org/?probe=7de05d2618) | Mar 27, 2024 |
| Gigabyte      | Q87M-D2H                    | [577e8ee500](https://linux-hardware.org/?probe=577e8ee500) | Mar 27, 2024 |
| ASUSTek       | P8H61-M LX2 R2.0            | [a7b3ddbaee](https://linux-hardware.org/?probe=a7b3ddbaee) | Mar 27, 2024 |
| Pegatron      | 2A73h                       | [193e8e5cb1](https://linux-hardware.org/?probe=193e8e5cb1) | Mar 26, 2024 |
| MSI           | B350 TOMAHAWK               | [10ca4510ec](https://linux-hardware.org/?probe=10ca4510ec) | Mar 26, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | [704e412f17](https://linux-hardware.org/?probe=704e412f17) | Mar 26, 2024 |
| Acer          | Aspire X3450                | [5b799c7536](https://linux-hardware.org/?probe=5b799c7536) | Mar 26, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [feb35a6b9c](https://linux-hardware.org/?probe=feb35a6b9c) | Mar 25, 2024 |
| Dell          | 01TKCC A01                  | [65070b32f2](https://linux-hardware.org/?probe=65070b32f2) | Mar 25, 2024 |
| ASUSTek       | P8Z77-V                     | [ec744f652d](https://linux-hardware.org/?probe=ec744f652d) | Mar 25, 2024 |
| ASUSTek       | P8Z77-V                     | [89c81c0a65](https://linux-hardware.org/?probe=89c81c0a65) | Mar 25, 2024 |
| Dell          | 0KWVT8 A00                  | [ae811bf4d9](https://linux-hardware.org/?probe=ae811bf4d9) | Mar 24, 2024 |
| HP            | 1905                        | [ee5ca084c4](https://linux-hardware.org/?probe=ee5ca084c4) | Mar 24, 2024 |
| HP            | 1905                        | [05c7e6e706](https://linux-hardware.org/?probe=05c7e6e706) | Mar 24, 2024 |
| ASUSTek       | P6T DELUXE V2               | [526ba57aee](https://linux-hardware.org/?probe=526ba57aee) | Mar 24, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX         | [d3025e223c](https://linux-hardware.org/?probe=d3025e223c) | Mar 24, 2024 |
| HP            | 2ADC                        | [d94b5fa4e7](https://linux-hardware.org/?probe=d94b5fa4e7) | Mar 23, 2024 |
| Gigabyte      | GA-880GM-USB3               | [5d0f3460a5](https://linux-hardware.org/?probe=5d0f3460a5) | Mar 23, 2024 |
| Gigabyte      | B550 UD AC-Y1               | [8c6f8835ea](https://linux-hardware.org/?probe=8c6f8835ea) | Mar 23, 2024 |
| Lenovo        | ThinkCentre M58p 6234FB9    | [38a5a34e54](https://linux-hardware.org/?probe=38a5a34e54) | Mar 23, 2024 |
| AZW           | U59                         | [06a180e5a9](https://linux-hardware.org/?probe=06a180e5a9) | Mar 22, 2024 |
| Gigabyte      | B460 HD3 se2                | [ac86e944ff](https://linux-hardware.org/?probe=ac86e944ff) | Mar 22, 2024 |
| ASUSTek       | P9X79 DELUXE                | [dabc36a5b3](https://linux-hardware.org/?probe=dabc36a5b3) | Mar 22, 2024 |
| HP            | 8433 11                     | [5b2290d410](https://linux-hardware.org/?probe=5b2290d410) | Mar 21, 2024 |
| ECS           | A785GM-AD3                  | [452fc5ac26](https://linux-hardware.org/?probe=452fc5ac26) | Mar 21, 2024 |
| ASRock        | A320M-HDV R4.0              | [cd5d6341fb](https://linux-hardware.org/?probe=cd5d6341fb) | Mar 21, 2024 |
| ASUSTek       | B85M-C/C/SI                 | [b456ba2213](https://linux-hardware.org/?probe=b456ba2213) | Mar 20, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [17d208911e](https://linux-hardware.org/?probe=17d208911e) | Mar 20, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [ae0e79e6da](https://linux-hardware.org/?probe=ae0e79e6da) | Mar 20, 2024 |
| AMI           | Intel                       | [fc4348f291](https://linux-hardware.org/?probe=fc4348f291) | Mar 20, 2024 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [969fc32897](https://linux-hardware.org/?probe=969fc32897) | Mar 20, 2024 |
| ASUSTek       | B85M-C/C/SI                 | [d374aaf228](https://linux-hardware.org/?probe=d374aaf228) | Mar 19, 2024 |
| Acer          | Veriton L6610G              | [c5e6b0ac2a](https://linux-hardware.org/?probe=c5e6b0ac2a) | Mar 19, 2024 |
| Dell          | 0NK5PH A00                  | [ee2fd9c92e](https://linux-hardware.org/?probe=ee2fd9c92e) | Mar 19, 2024 |
| Dell          | 0XFWHV A00                  | [366d65567e](https://linux-hardware.org/?probe=366d65567e) | Mar 19, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d9e56f3325](https://linux-hardware.org/?probe=d9e56f3325) | Mar 19, 2024 |
| HP            | 843B                        | [d867363097](https://linux-hardware.org/?probe=d867363097) | Mar 19, 2024 |
| HP            | 843B                        | [f32e4ee209](https://linux-hardware.org/?probe=f32e4ee209) | Mar 19, 2024 |
| ASRock        | X570 Steel Legend           | [902b7d5554](https://linux-hardware.org/?probe=902b7d5554) | Mar 18, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [4774169c78](https://linux-hardware.org/?probe=4774169c78) | Mar 18, 2024 |
| HP            | 2ADC                        | [8c1fc992f0](https://linux-hardware.org/?probe=8c1fc992f0) | Mar 17, 2024 |
| Pegatron      | IPMH61P1                    | [6221b2b986](https://linux-hardware.org/?probe=6221b2b986) | Mar 17, 2024 |
| Gigabyte      | F2A88XM-D3H                 | [2780dec79d](https://linux-hardware.org/?probe=2780dec79d) | Mar 17, 2024 |
| MSI           | MAG B550 TOMAHAWK           | [4428cc7de0](https://linux-hardware.org/?probe=4428cc7de0) | Mar 17, 2024 |
| Gateway       | SX2851                      | [68e1f2c952](https://linux-hardware.org/?probe=68e1f2c952) | Mar 17, 2024 |
| Gigabyte      | B450M S2H                   | [c1dbd5edb2](https://linux-hardware.org/?probe=c1dbd5edb2) | Mar 17, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | [f1bb876476](https://linux-hardware.org/?probe=f1bb876476) | Mar 16, 2024 |
| MSI           | B150 GAMING M3              | [f8b1e50645](https://linux-hardware.org/?probe=f8b1e50645) | Mar 16, 2024 |
| HP            | 805D                        | [7878b71cab](https://linux-hardware.org/?probe=7878b71cab) | Mar 15, 2024 |
| ASUSTek       | PRIME Z390-A                | [1b4cf177e5](https://linux-hardware.org/?probe=1b4cf177e5) | Mar 15, 2024 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [7a11b99920](https://linux-hardware.org/?probe=7a11b99920) | Mar 15, 2024 |
| Lenovo        | 1057 SDK0T76528 WIN 3556... | [ff14bf45ec](https://linux-hardware.org/?probe=ff14bf45ec) | Mar 14, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [b175004524](https://linux-hardware.org/?probe=b175004524) | Mar 14, 2024 |
| ASUSTek       | P8P67 EVO                   | [3ece14c501](https://linux-hardware.org/?probe=3ece14c501) | Mar 13, 2024 |
| IBM           | 8215MUC                     | [b6c69c2119](https://linux-hardware.org/?probe=b6c69c2119) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [3a8d8640a9](https://linux-hardware.org/?probe=3a8d8640a9) | Mar 12, 2024 |
| Pegatron      | JESSE                       | [5602b9f4e2](https://linux-hardware.org/?probe=5602b9f4e2) | Mar 12, 2024 |
| ASUSTek       | PRIME Z390-A                | [94831371a9](https://linux-hardware.org/?probe=94831371a9) | Mar 12, 2024 |
| Gigabyte      | H410M S2H V3                | [0f5989dcbc](https://linux-hardware.org/?probe=0f5989dcbc) | Mar 12, 2024 |
| Gigabyte      | A320M-S2H-CF                | [020b8b531a](https://linux-hardware.org/?probe=020b8b531a) | Mar 12, 2024 |
| Gigabyte      | A320M-S2H-CF                | [84502e8400](https://linux-hardware.org/?probe=84502e8400) | Mar 12, 2024 |
| DIEBOLD       | Canyon                      | [109f1d1d93](https://linux-hardware.org/?probe=109f1d1d93) | Mar 12, 2024 |
| DIEBOLD       | Canyon                      | [a92906b4f5](https://linux-hardware.org/?probe=a92906b4f5) | Mar 12, 2024 |
| MSI           | 785GT-E63                   | [1533ab1a7c](https://linux-hardware.org/?probe=1533ab1a7c) | Mar 12, 2024 |
| HP            | 8653 A                      | [e90335d9c9](https://linux-hardware.org/?probe=e90335d9c9) | Mar 12, 2024 |
| SiS           | B550S Ver:1.16              | [97c4226745](https://linux-hardware.org/?probe=97c4226745) | Mar 12, 2024 |
| Dell          | 0D6H9T A01                  | [6a4e81ad5e](https://linux-hardware.org/?probe=6a4e81ad5e) | Mar 11, 2024 |
| MSI           | MEG Z590 ACE GOLD EDITIO... | [df6500bf6b](https://linux-hardware.org/?probe=df6500bf6b) | Mar 10, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [53ca2b56ef](https://linux-hardware.org/?probe=53ca2b56ef) | Mar 10, 2024 |
| HP            | 8265                        | [a805d1a4b0](https://linux-hardware.org/?probe=a805d1a4b0) | Mar 10, 2024 |
| MSI           | B450M-A PRO MAX II          | [e38d871b42](https://linux-hardware.org/?probe=e38d871b42) | Mar 10, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [eecc91d036](https://linux-hardware.org/?probe=eecc91d036) | Mar 10, 2024 |
| QIYIDA        | ED4 V1.1                    | [0fcfff37bf](https://linux-hardware.org/?probe=0fcfff37bf) | Mar 10, 2024 |
| Dell          | 0KWVT8 A00                  | [c80fca1d72](https://linux-hardware.org/?probe=c80fca1d72) | Mar 09, 2024 |
| ASUSTek       | PRIME B450M-A II            | [b591cc5cfe](https://linux-hardware.org/?probe=b591cc5cfe) | Mar 09, 2024 |
| Lenovo        | MAHOBAY NOK                 | [4bd7a64be3](https://linux-hardware.org/?probe=4bd7a64be3) | Mar 09, 2024 |
| Unknown       | Unknown                     | [2b737bd393](https://linux-hardware.org/?probe=2b737bd393) | Mar 09, 2024 |
| HP            | 3647h                       | [04d7f488a7](https://linux-hardware.org/?probe=04d7f488a7) | Mar 09, 2024 |
| ASUSTek       | PRIME Z490-P                | [f208bbae00](https://linux-hardware.org/?probe=f208bbae00) | Mar 08, 2024 |
| Dell          | 0D24M8 A01                  | [cdf2cddb43](https://linux-hardware.org/?probe=cdf2cddb43) | Mar 08, 2024 |
| ASRock        | H81M-VG4                    | [96f9d92727](https://linux-hardware.org/?probe=96f9d92727) | Mar 08, 2024 |
| ASUSTek       | PRIME Z490-P                | [b4f141c9da](https://linux-hardware.org/?probe=b4f141c9da) | Mar 08, 2024 |
| Dell          | 0KWVT8 A03                  | [4ad718e45b](https://linux-hardware.org/?probe=4ad718e45b) | Mar 08, 2024 |
| Gigabyte      | H410M S2H V3                | [f2ae26b3f5](https://linux-hardware.org/?probe=f2ae26b3f5) | Mar 07, 2024 |
| ASRock        | B450M Pro4                  | [6e793fa7a4](https://linux-hardware.org/?probe=6e793fa7a4) | Mar 07, 2024 |
| ASUSTek       | STRIX H270F GAMING          | [6e35097ed2](https://linux-hardware.org/?probe=6e35097ed2) | Mar 07, 2024 |
| Gigabyte      | Z97X-UD5H                   | [76cf4afca4](https://linux-hardware.org/?probe=76cf4afca4) | Mar 06, 2024 |
| HP            | 89B5 A                      | [52f3d1ebea](https://linux-hardware.org/?probe=52f3d1ebea) | Mar 05, 2024 |
| HP            | 89B5 A                      | [ada6553f38](https://linux-hardware.org/?probe=ada6553f38) | Mar 05, 2024 |
| Dell          | 0T10XW A00                  | [ef08d738fb](https://linux-hardware.org/?probe=ef08d738fb) | Mar 04, 2024 |
| Dell          | 0PU052                      | [d99b3dfb94](https://linux-hardware.org/?probe=d99b3dfb94) | Mar 03, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | [813c36f5cf](https://linux-hardware.org/?probe=813c36f5cf) | Mar 03, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | [69bec2f38f](https://linux-hardware.org/?probe=69bec2f38f) | Mar 03, 2024 |
| ASRock        | 980DE3/U3S3                 | [3818d7195f](https://linux-hardware.org/?probe=3818d7195f) | Mar 03, 2024 |
| Gigabyte      | A520M DS3H V2               | [2046b817c7](https://linux-hardware.org/?probe=2046b817c7) | Mar 03, 2024 |
| MSI           | B450M GAMING PLUS           | [8eaf2b59af](https://linux-hardware.org/?probe=8eaf2b59af) | Mar 03, 2024 |
| ECS           | H61H2-M2                    | [bec82f9c2a](https://linux-hardware.org/?probe=bec82f9c2a) | Mar 02, 2024 |
| Gigabyte      | G31M-S2C                    | [b9ddd2512e](https://linux-hardware.org/?probe=b9ddd2512e) | Mar 02, 2024 |
| Gigabyte      | G31M-S2C                    | [c9ab34da1a](https://linux-hardware.org/?probe=c9ab34da1a) | Mar 02, 2024 |
| Unknown       | Unknown                     | [271452e819](https://linux-hardware.org/?probe=271452e819) | Mar 01, 2024 |
| Dell          | 0D24M8 A01                  | [6573368c36](https://linux-hardware.org/?probe=6573368c36) | Mar 01, 2024 |
| Gigabyte      | G31M-S2C                    | [47d6164c5a](https://linux-hardware.org/?probe=47d6164c5a) | Feb 29, 2024 |
| ASUSTek       | P8H61-M PLUS2               | [9539fc46cc](https://linux-hardware.org/?probe=9539fc46cc) | Feb 29, 2024 |
| ECS           | H61H2-M2                    | [d8ff6883f1](https://linux-hardware.org/?probe=d8ff6883f1) | Feb 29, 2024 |
| Supermicro    | C2SBC-Q                     | [d90714db33](https://linux-hardware.org/?probe=d90714db33) | Feb 29, 2024 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [08482c8ae5](https://linux-hardware.org/?probe=08482c8ae5) | Feb 29, 2024 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [f7550261f5](https://linux-hardware.org/?probe=f7550261f5) | Feb 29, 2024 |
| Gigabyte      | Z97X-UD5H                   | [a9c902341e](https://linux-hardware.org/?probe=a9c902341e) | Feb 28, 2024 |
| ASUSTek       | TUF Z370-PRO GAMING         | [636e341039](https://linux-hardware.org/?probe=636e341039) | Feb 28, 2024 |
| ASUSTek       | H110M-R                     | [99161beb5e](https://linux-hardware.org/?probe=99161beb5e) | Feb 28, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | [84b3a163a6](https://linux-hardware.org/?probe=84b3a163a6) | Feb 28, 2024 |
| HP            | 83EE                        | [86edbf63e7](https://linux-hardware.org/?probe=86edbf63e7) | Feb 28, 2024 |
| ASRock        | H81M-VG4                    | [031f559cf7](https://linux-hardware.org/?probe=031f559cf7) | Feb 27, 2024 |
| MSI           | B450 GAMING PLUS MAX        | [d2373db1a8](https://linux-hardware.org/?probe=d2373db1a8) | Feb 27, 2024 |
| Gigabyte      | B450 AORUS M                | [196330861b](https://linux-hardware.org/?probe=196330861b) | Feb 27, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | [7fe90d068b](https://linux-hardware.org/?probe=7fe90d068b) | Feb 26, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS       | [5b006b8b96](https://linux-hardware.org/?probe=5b006b8b96) | Feb 26, 2024 |
| Lenovo        | ThinkCentre M71z 1761E4U    | [07258c1d6d](https://linux-hardware.org/?probe=07258c1d6d) | Feb 25, 2024 |
| Colorful T... | C.Z77 X5 V20                | [c4b1274d4e](https://linux-hardware.org/?probe=c4b1274d4e) | Feb 25, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [d8df626171](https://linux-hardware.org/?probe=d8df626171) | Feb 25, 2024 |
| Unknown       | E-H61                       | [899be10105](https://linux-hardware.org/?probe=899be10105) | Feb 24, 2024 |
| Unknown       | E-H61                       | [fa84a51212](https://linux-hardware.org/?probe=fa84a51212) | Feb 24, 2024 |
| Intel         | X58                         | [f4526c5a1c](https://linux-hardware.org/?probe=f4526c5a1c) | Feb 23, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [eeace60b7a](https://linux-hardware.org/?probe=eeace60b7a) | Feb 23, 2024 |
| Biostar       | A320MH                      | [cbd7260993](https://linux-hardware.org/?probe=cbd7260993) | Feb 23, 2024 |
| HP            | 2215                        | [eef0673d86](https://linux-hardware.org/?probe=eef0673d86) | Feb 21, 2024 |
| HP            | 2215                        | [d23162f59f](https://linux-hardware.org/?probe=d23162f59f) | Feb 20, 2024 |
| ASUSTek       | K30BF_M32BF                 | [a39f9b2921](https://linux-hardware.org/?probe=a39f9b2921) | Feb 20, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [1ccd345da2](https://linux-hardware.org/?probe=1ccd345da2) | Feb 20, 2024 |
| GEEKOM        | A5                          | [43d1283121](https://linux-hardware.org/?probe=43d1283121) | Feb 20, 2024 |
| ASRock        | H410M-HVS                   | [d07941ad3f](https://linux-hardware.org/?probe=d07941ad3f) | Feb 20, 2024 |
| Gigabyte      | EP35-DS3                    | [083ed26b97](https://linux-hardware.org/?probe=083ed26b97) | Feb 20, 2024 |
| Dell          | 051FJ8 A01                  | [0949817cb6](https://linux-hardware.org/?probe=0949817cb6) | Feb 19, 2024 |
| Dell          | 0PGKWF A00                  | [83c1da9c3c](https://linux-hardware.org/?probe=83c1da9c3c) | Feb 19, 2024 |
| TB            | WTR R1                      | [ab65edc6c3](https://linux-hardware.org/?probe=ab65edc6c3) | Feb 19, 2024 |
| ASUSTek       | B85-PLUS                    | [87ad4ddd6d](https://linux-hardware.org/?probe=87ad4ddd6d) | Feb 19, 2024 |
| Dell          | 0KWVT8 A03                  | [96c3415965](https://linux-hardware.org/?probe=96c3415965) | Feb 19, 2024 |
| Dell          | 0KWVT8 A03                  | [8a1cafd28d](https://linux-hardware.org/?probe=8a1cafd28d) | Feb 19, 2024 |
| OEM           | B75 Ver:1.41                | [bdc300e725](https://linux-hardware.org/?probe=bdc300e725) | Feb 18, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [eff6e16943](https://linux-hardware.org/?probe=eff6e16943) | Feb 17, 2024 |
| OEM           | B75 Ver:1.41                | [f685a6eccc](https://linux-hardware.org/?probe=f685a6eccc) | Feb 17, 2024 |
| Gigabyte      | B650 GAMING X AX            | [658984c494](https://linux-hardware.org/?probe=658984c494) | Feb 17, 2024 |
| MSI           | B450M PRO-VDH MAX           | [c325b99554](https://linux-hardware.org/?probe=c325b99554) | Feb 16, 2024 |
| Intel         | DH67GD AAG10206-205         | [c1b6c3c87e](https://linux-hardware.org/?probe=c1b6c3c87e) | Feb 16, 2024 |
| MSI           | 2AE0                        | [85d065236b](https://linux-hardware.org/?probe=85d065236b) | Feb 15, 2024 |
| MSI           | B450-A PRO MAX              | [ca82f5e8f1](https://linux-hardware.org/?probe=ca82f5e8f1) | Feb 15, 2024 |
| HP            | 3047h                       | [05f8efc7c6](https://linux-hardware.org/?probe=05f8efc7c6) | Feb 15, 2024 |
| Unknown       | Unknown                     | [37f24823aa](https://linux-hardware.org/?probe=37f24823aa) | Feb 15, 2024 |
| Acer          | v1.0                        | [a7ba3b84dc](https://linux-hardware.org/?probe=a7ba3b84dc) | Feb 14, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_17/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 6.5.0-35-generic        | 90       | 9.59%   |
| 6.8.0-40-generic        | 88       | 9.38%   |
| 6.5.0-41-generic        | 71       | 7.57%   |
| 6.8.0-49-generic        | 67       | 7.14%   |
| 6.8.0-45-generic        | 66       | 7.04%   |
| 6.2.0-39-generic        | 64       | 6.82%   |
| 6.5.0-26-generic        | 61       | 6.5%    |
| 6.5.0-28-generic        | 46       | 4.9%    |
| 6.5.0-14-generic        | 45       | 4.8%    |
| 6.8.0-48-generic        | 42       | 4.48%   |
| 6.5.0-45-generic        | 40       | 4.26%   |
| 6.5.0-21-generic        | 38       | 4.05%   |
| 6.8.0-50-generic        | 35       | 3.73%   |
| 6.8.0-47-generic        | 34       | 3.62%   |
| 6.5.0-25-generic        | 33       | 3.52%   |
| 6.5.0-15-generic        | 28       | 2.99%   |
| 6.5.0-27-generic        | 26       | 2.77%   |
| 6.5.0-18-generic        | 17       | 1.81%   |
| 6.5.0-44-generic        | 15       | 1.6%    |
| 6.5.0-17-generic        | 15       | 1.6%    |
| 6.2.0-37-generic        | 2        | 0.21%   |
| 6.9.5-x64v3-xanmod1     | 1        | 0.11%   |
| 6.9.3-060903-generic    | 1        | 0.11%   |
| 6.8.8-060808-generic    | 1        | 0.11%   |
| 6.8.0-41-generic        | 1        | 0.11%   |
| 6.7.7-060707-generic    | 1        | 0.11%   |
| 6.7.5-060705-generic    | 1        | 0.11%   |
| 6.7.10-x64v4-xanmod1    | 1        | 0.11%   |
| 6.12.1-1-liquorix-amd64 | 1        | 0.11%   |
| 6.10.8-061008-generic   | 1        | 0.11%   |
| 6.1.0-1035-oem          | 1        | 0.11%   |
| 5.15.0-92-generic       | 1        | 0.11%   |
| 5.15.0-60-generic       | 1        | 0.11%   |
| 5.15.0-125-lowlatency   | 1        | 0.11%   |
| 5.15.0-124-lowlatency   | 1        | 0.11%   |
| 5.15.0-105-generic      | 1        | 0.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.5.0   | 486      | 54.92%  |
| 6.8.0   | 320      | 36.16%  |
| 6.2.0   | 66       | 7.46%   |
| 5.15.0  | 4        | 0.45%   |
| 6.9.5   | 1        | 0.11%   |
| 6.9.3   | 1        | 0.11%   |
| 6.8.8   | 1        | 0.11%   |
| 6.7.7   | 1        | 0.11%   |
| 6.7.5   | 1        | 0.11%   |
| 6.7.10  | 1        | 0.11%   |
| 6.12.1  | 1        | 0.11%   |
| 6.10.8  | 1        | 0.11%   |
| 6.1.0   | 1        | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.5     | 486      | 54.98%  |
| 6.8     | 321      | 36.31%  |
| 6.2     | 66       | 7.47%   |
| 5.15    | 4        | 0.45%   |
| 6.9     | 2        | 0.23%   |
| 6.7     | 2        | 0.23%   |
| 6.12    | 1        | 0.11%   |
| 6.10    | 1        | 0.11%   |
| 6.1     | 1        | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 846      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 827      | 97.75%  |
| XFCE          | 18       | 2.13%   |
| Enlightenment | 1        | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 549      | 63.99%  |
| X11     | 305      | 35.55%  |
| Tty     | 2        | 0.23%   |
| Unknown | 2        | 0.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 741      | 86.06%  |
| GDM3    | 116      | 13.47%  |
| LightDM | 4        | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 296      | 34.95%  |
| de_DE | 97       | 11.45%  |
| pt_BR | 74       | 8.74%   |
| it_IT | 42       | 4.96%   |
| fr_FR | 38       | 4.49%   |
| en_GB | 35       | 4.13%   |
| es_ES | 27       | 3.19%   |
| en_CA | 26       | 3.07%   |
| en_AU | 23       | 2.72%   |
| nl_NL | 16       | 1.89%   |
| en_IN | 16       | 1.89%   |
| pl_PL | 13       | 1.53%   |
| es_MX | 12       | 1.42%   |
| tr_TR | 11       | 1.3%    |
| pt_PT | 11       | 1.3%    |
| es_AR | 9        | 1.06%   |
| cs_CZ | 8        | 0.94%   |
| ru_RU | 7        | 0.83%   |
| en_NZ | 7        | 0.83%   |
| hu_HU | 6        | 0.71%   |
| en_ZA | 6        | 0.71%   |
| nb_NO | 5        | 0.59%   |
| es_CO | 5        | 0.59%   |
| en_IE | 5        | 0.59%   |
| nl_BE | 4        | 0.47%   |
| de_AT | 4        | 0.47%   |
| sv_SE | 3        | 0.35%   |
| sr_RS | 3        | 0.35%   |
| es_PE | 3        | 0.35%   |
| da_DK | 3        | 0.35%   |
| ro_RO | 2        | 0.24%   |
| ja_JP | 2        | 0.24%   |
| fr_BE | 2        | 0.24%   |
| es_VE | 2        | 0.24%   |
| es_PY | 2        | 0.24%   |
| es_CL | 2        | 0.24%   |
| es_BO | 2        | 0.24%   |
| en_SG | 2        | 0.24%   |
| zh_TW | 1        | 0.12%   |
| sv_FI | 1        | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 803      | 94.36%  |
| EFI  | 48       | 5.64%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 728      | 84.55%  |
| Tmpfs   | 69       | 8.01%   |
| Zfs     | 29       | 3.37%   |
| Btrfs   | 16       | 1.86%   |
| Overlay | 15       | 1.74%   |
| Xfs     | 2        | 0.23%   |
| Ext2    | 2        | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 741      | 86.06%  |
| GPT     | 111      | 12.89%  |
| MBR     | 9        | 1.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 833      | 98.23%  |
| Yes       | 15       | 1.77%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 783      | 91.26%  |
| Yes       | 75       | 8.74%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 179      | 21.16%  |
| Gigabyte Technology | 134      | 15.84%  |
| MSI                 | 98       | 11.58%  |
| Dell                | 92       | 10.87%  |
| Hewlett-Packard     | 72       | 8.51%   |
| ASRock              | 59       | 6.97%   |
| Lenovo              | 37       | 4.37%   |
| Intel               | 31       | 3.66%   |
| Unknown             | 18       | 2.13%   |
| Acer                | 15       | 1.77%   |
| Fujitsu             | 11       | 1.3%    |
| Pegatron            | 8        | 0.95%   |
| ECS                 | 8        | 0.95%   |
| Biostar             | 8        | 0.95%   |
| OEM                 | 6        | 0.71%   |
| Foxconn             | 6        | 0.71%   |
| MACHINIST           | 4        | 0.47%   |
| AMI                 | 4        | 0.47%   |
| Alienware           | 4        | 0.47%   |
| Huanan              | 3        | 0.35%   |
| Google              | 3        | 0.35%   |
| GEEKOM              | 3        | 0.35%   |
| AZW                 | 3        | 0.35%   |
| AMD                 | 3        | 0.35%   |
| Shuttle             | 2        | 0.24%   |
| Positivo            | 2        | 0.24%   |
| Packard Bell        | 2        | 0.24%   |
| Fujitsu Siemens     | 2        | 0.24%   |
| BESSTAR Tech        | 2        | 0.24%   |
| Apple               | 2        | 0.24%   |
| ZOTAC               | 1        | 0.12%   |
| wpc                 | 1        | 0.12%   |
| TB                  | 1        | 0.12%   |
| T-bao               | 1        | 0.12%   |
| SZMZ                | 1        | 0.12%   |
| Supermicro          | 1        | 0.12%   |
| STGAUBRON           | 1        | 0.12%   |
| Soyo                | 1        | 0.12%   |
| SiS                 | 1        | 0.12%   |
| Simply NUC          | 1        | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 19       | 2.25%   |
| ASUS All Series                | 13       | 1.54%   |
| MSI MS-7C56                    | 7        | 0.83%   |
| MSI MS-7C37                    | 6        | 0.71%   |
| Dell OptiPlex 9020             | 6        | 0.71%   |
| Dell OptiPlex 7010             | 6        | 0.71%   |
| ASUS TUF Gaming X570-PLUS      | 6        | 0.71%   |
| Fujitsu ESPRIMO Q920           | 5        | 0.59%   |
| Dell OptiPlex 790              | 5        | 0.59%   |
| Gigabyte Z790 AORUS ELITE AX   | 4        | 0.47%   |
| Dell OptiPlex 990              | 4        | 0.47%   |
| Dell OptiPlex 7040             | 4        | 0.47%   |
| Dell OptiPlex 3050             | 4        | 0.47%   |
| ASUS A0000001                  | 4        | 0.47%   |
| MSI MS-7E07                    | 3        | 0.35%   |
| MSI MS-7C91                    | 3        | 0.35%   |
| MSI MS-7C52                    | 3        | 0.35%   |
| MSI MS-7B86                    | 3        | 0.35%   |
| MSI MS-7A38                    | 3        | 0.35%   |
| MSI MS-7A34                    | 3        | 0.35%   |
| MSI MS-7850                    | 3        | 0.35%   |
| MSI MS-7817                    | 3        | 0.35%   |
| HP Z230 Tower Workstation      | 3        | 0.35%   |
| Gigabyte A320M-S2H             | 3        | 0.35%   |
| Dell OptiPlex 755              | 3        | 0.35%   |
| Dell OptiPlex 7050             | 3        | 0.35%   |
| Dell Inspiron 580              | 3        | 0.35%   |
| ASUS TUF Gaming B650-PLUS WIFI | 3        | 0.35%   |
| ASUS M5A97 R2.0                | 3        | 0.35%   |
| ASRock A520M-HDV               | 3        | 0.35%   |
| AMI Intel                      | 3        | 0.35%   |
| OEM B75                        | 2        | 0.24%   |
| MSI MS-7E26                    | 2        | 0.24%   |
| MSI MS-7D99                    | 2        | 0.24%   |
| MSI MS-7D75                    | 2        | 0.24%   |
| MSI MS-7C39                    | 2        | 0.24%   |
| MSI MS-7B45                    | 2        | 0.24%   |
| MSI MS-7788                    | 2        | 0.24%   |
| Intel X79F1 V2.0               | 2        | 0.24%   |
| Intel H61                      | 2        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 56       | 6.62%   |
| ASUS PRIME         | 29       | 3.43%   |
| ASUS ROG           | 27       | 3.19%   |
| ASUS TUF           | 25       | 2.96%   |
| Lenovo ThinkCentre | 21       | 2.48%   |
| Unknown            | 19       | 2.25%   |
| HP EliteDesk       | 16       | 1.89%   |
| HP Compaq          | 14       | 1.65%   |
| HP ProDesk         | 13       | 1.54%   |
| ASUS All           | 13       | 1.54%   |
| Dell Precision     | 12       | 1.42%   |
| Dell Inspiron      | 12       | 1.42%   |
| Fujitsu ESPRIMO    | 9        | 1.06%   |
| Acer Aspire        | 8        | 0.95%   |
| MSI MS-7C56        | 7        | 0.83%   |
| Gigabyte B450      | 7        | 0.83%   |
| MSI MS-7C37        | 6        | 0.71%   |
| Lenovo IdeaCentre  | 6        | 0.71%   |
| Gigabyte B550      | 6        | 0.71%   |
| Gigabyte B450M     | 6        | 0.71%   |
| HP Pavilion        | 5        | 0.59%   |
| Gigabyte Z790      | 5        | 0.59%   |
| Dell XPS           | 5        | 0.59%   |
| ASUS P8Z77-V       | 5        | 0.59%   |
| ASUS M5A78L-M      | 5        | 0.59%   |
| Gigabyte Z390      | 4        | 0.47%   |
| Dell Vostro        | 4        | 0.47%   |
| ASUS M5A97         | 4        | 0.47%   |
| ASUS A0000001      | 4        | 0.47%   |
| ASRock B450M       | 4        | 0.47%   |
| Alienware Aurora   | 4        | 0.47%   |
| Acer Veriton       | 4        | 0.47%   |
| MSI MS-7E07        | 3        | 0.35%   |
| MSI MS-7C91        | 3        | 0.35%   |
| MSI MS-7C52        | 3        | 0.35%   |
| MSI MS-7B86        | 3        | 0.35%   |
| MSI MS-7A38        | 3        | 0.35%   |
| MSI MS-7A34        | 3        | 0.35%   |
| MSI MS-7850        | 3        | 0.35%   |
| MSI MS-7817        | 3        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 76       | 8.98%   |
| 2012    | 63       | 7.45%   |
| 2023    | 62       | 7.33%   |
| 2020    | 60       | 7.09%   |
| 2022    | 59       | 6.97%   |
| 2019    | 59       | 6.97%   |
| 2018    | 58       | 6.86%   |
| 2011    | 58       | 6.86%   |
| 2017    | 53       | 6.26%   |
| 2014    | 53       | 6.26%   |
| 2021    | 47       | 5.56%   |
| 2010    | 43       | 5.08%   |
| 2016    | 39       | 4.61%   |
| 2009    | 34       | 4.02%   |
| 2015    | 28       | 3.31%   |
| 2008    | 20       | 2.36%   |
| 2007    | 18       | 2.13%   |
| 2024    | 11       | 1.3%    |
| 2006    | 4        | 0.47%   |
| Unknown | 1        | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 846      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 839      | 99.17%  |
| Enabled  | 7        | 0.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 843      | 99.65%  |
| Yes  | 3        | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 224      | 26.42%  |
| 32.01-64.0      | 155      | 18.28%  |
| 8.01-16.0       | 147      | 17.33%  |
| 4.01-8.0        | 128      | 15.09%  |
| 3.01-4.0        | 78       | 9.2%    |
| 64.01-256.0     | 64       | 7.55%   |
| 24.01-32.0      | 38       | 4.48%   |
| 1.01-2.0        | 7        | 0.83%   |
| 2.01-3.0        | 6        | 0.71%   |
| More than 256.0 | 1        | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 304      | 33.41%  |
| 1.01-2.0   | 214      | 23.52%  |
| 3.01-4.0   | 169      | 18.57%  |
| 4.01-8.0   | 168      | 18.46%  |
| 8.01-16.0  | 42       | 4.62%   |
| 16.01-24.0 | 8        | 0.88%   |
| 0.51-1.0   | 3        | 0.33%   |
| 32.01-64.0 | 1        | 0.11%   |
| 24.01-32.0 | 1        | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 356      | 41.16%  |
| 2      | 254      | 29.36%  |
| 3      | 129      | 14.91%  |
| 4      | 65       | 7.51%   |
| 5      | 22       | 2.54%   |
| 6      | 20       | 2.31%   |
| 8      | 8        | 0.92%   |
| 7      | 6        | 0.69%   |
| 9      | 3        | 0.35%   |
| 11     | 1        | 0.12%   |
| 10     | 1        | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 500      | 58.82%  |
| Yes       | 350      | 41.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 841      | 99.41%  |
| No        | 5        | 0.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 452      | 53.11%  |
| No        | 399      | 46.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 504      | 58.88%  |
| Yes       | 352      | 41.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 174      | 20.4%   |
| Germany      | 109      | 12.78%  |
| Brazil       | 78       | 9.14%   |
| Italy        | 45       | 5.28%   |
| UK           | 38       | 4.45%   |
| France       | 36       | 4.22%   |
| Canada       | 33       | 3.87%   |
| Netherlands  | 25       | 2.93%   |
| Spain        | 23       | 2.7%    |
| Australia    | 22       | 2.58%   |
| India        | 19       | 2.23%   |
| Mexico       | 17       | 1.99%   |
| Poland       | 16       | 1.88%   |
| Portugal     | 15       | 1.76%   |
| Turkey       | 12       | 1.41%   |
| Argentina    | 11       | 1.29%   |
| Romania      | 9        | 1.06%   |
| Hungary      | 9        | 1.06%   |
| Egypt        | 9        | 1.06%   |
| Belgium      | 9        | 1.06%   |
| Norway       | 8        | 0.94%   |
| Czechia      | 8        | 0.94%   |
| Sweden       | 7        | 0.82%   |
| Russia       | 7        | 0.82%   |
| New Zealand  | 7        | 0.82%   |
| Switzerland  | 6        | 0.7%    |
| South Africa | 6        | 0.7%    |
| Saudi Arabia | 6        | 0.7%    |
| Colombia     | 6        | 0.7%    |
| Indonesia    | 5        | 0.59%   |
| Denmark      | 5        | 0.59%   |
| Peru         | 4        | 0.47%   |
| Japan        | 4        | 0.47%   |
| Austria      | 4        | 0.47%   |
| Serbia       | 3        | 0.35%   |
| Ireland      | 3        | 0.35%   |
| Greece       | 3        | 0.35%   |
| Chile        | 3        | 0.35%   |
| Bulgaria     | 3        | 0.35%   |
| Venezuela    | 2        | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Sydney           | 12       | 1.36%   |
| Berlin           | 11       | 1.24%   |
| Sao Paulo        | 7        | 0.79%   |
| Rio de Janeiro   | 6        | 0.68%   |
| Milan            | 6        | 0.68%   |
| Paris            | 5        | 0.57%   |
| Mumbai           | 5        | 0.57%   |
| Cairo            | 5        | 0.57%   |
| Brisbane         | 5        | 0.57%   |
| Stockholm        | 4        | 0.45%   |
| Sao Goncalo      | 4        | 0.45%   |
| Istanbul         | 4        | 0.45%   |
| Budapest         | 4        | 0.45%   |
| Atlanta          | 4        | 0.45%   |
| Amsterdam        | 4        | 0.45%   |
| Albuquerque      | 4        | 0.45%   |
| Stuttgart        | 3        | 0.34%   |
| Santiago         | 3        | 0.34%   |
| Prague           | 3        | 0.34%   |
| Oklahoma City    | 3        | 0.34%   |
| Minneapolis      | 3        | 0.34%   |
| Milano           | 3        | 0.34%   |
| Miami            | 3        | 0.34%   |
| Manchester       | 3        | 0.34%   |
| Los Angeles      | 3        | 0.34%   |
| Guarulhos        | 3        | 0.34%   |
| Dallas           | 3        | 0.34%   |
| Colorado Springs | 3        | 0.34%   |
| Chicago          | 3        | 0.34%   |
| Chennai          | 3        | 0.34%   |
| Calgary          | 3        | 0.34%   |
| Bengaluru        | 3        | 0.34%   |
| Belém           | 3        | 0.34%   |
| Auckland         | 3        | 0.34%   |
| Antrim           | 3        | 0.34%   |
| Adelaide         | 3        | 0.34%   |
| Zwickau          | 2        | 0.23%   |
| Zurich           | 2        | 0.23%   |
| Zevenaar         | 2        | 0.23%   |
| Wellington       | 2        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC                          | 240      | 344    | 15.45%  |
| Seagate                      | 226      | 324    | 14.55%  |
| Samsung Electronics          | 211      | 337    | 13.59%  |
| Kingston                     | 104      | 129    | 6.7%    |
| Sandisk                      | 92       | 139    | 5.92%   |
| Crucial                      | 63       | 78     | 4.06%   |
| Toshiba                      | 55       | 68     | 3.54%   |
| Hitachi                      | 40       | 50     | 2.58%   |
| China                        | 35       | 43     | 2.25%   |
| Phison Electronics           | 30       | 39     | 1.93%   |
| Micron/Crucial Technology    | 26       | 35     | 1.67%   |
| Kingston Technology Company  | 24       | 26     | 1.55%   |
| Silicon Motion               | 21       | 22     | 1.35%   |
| Unknown                      | 18       | 31     | 1.16%   |
| Intenso                      | 18       | 20     | 1.16%   |
| Intel                        | 17       | 20     | 1.09%   |
| SK hynix                     | 16       | 22     | 1.03%   |
| A-DATA Technology            | 15       | 16     | 0.97%   |
| PNY                          | 13       | 17     | 0.84%   |
| Micron Technology            | 13       | 15     | 0.84%   |
| MAXIO Technology (Hangzhou)  | 13       | 18     | 0.84%   |
| HGST                         | 13       | 18     | 0.84%   |
| SPCC                         | 12       | 12     | 0.77%   |
| Realtek Semiconductor        | 12       | 12     | 0.77%   |
| Shenzhen Longsys Electronics | 10       | 11     | 0.64%   |
| ADATA Technology             | 10       | 10     | 0.64%   |
| Corsair                      | 9        | 13     | 0.58%   |
| OCZ                          | 8        | 9      | 0.52%   |
| Unknown                      | 8        | 11     | 0.52%   |
| Verbatim                     | 7        | 12     | 0.45%   |
| Team                         | 7        | 7      | 0.45%   |
| LITEON                       | 7        | 10     | 0.45%   |
| Lexar                        | 7        | 9      | 0.45%   |
| Fanxiang                     | 7        | 10     | 0.45%   |
| Netac                        | 6        | 7      | 0.39%   |
| SABRENT                      | 5        | 7      | 0.32%   |
| Patriot                      | 5        | 7      | 0.32%   |
| Maxtor                       | 5        | 5      | 0.32%   |
| KIOXIA-EXCERIA               | 5        | 6      | 0.32%   |
| KingSpec                     | 5        | 7      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 25       | 1.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 24       | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 24       | 1.36%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 18       | 1.02%   |
| Seagate ST500DM002-1BD142 500GB                       | 18       | 1.02%   |
| Seagate ST1000DM003-1CH162 1TB                        | 13       | 0.74%   |
| Samsung SSD 870 EVO 500GB                             | 12       | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 12       | 0.68%   |
| Kingston SA400S37480G 480GB SSD                       | 12       | 0.68%   |
| Crucial CT500MX500SSD1 500GB                          | 12       | 0.68%   |
| Toshiba DT01ACA100 1TB                                | 11       | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB                        | 11       | 0.62%   |
| Samsung SSD 990 PRO 2TB                               | 10       | 0.57%   |
| Samsung SSD 860 EVO 500GB                             | 10       | 0.57%   |
| Samsung SSD 850 EVO 250GB                             | 10       | 0.57%   |
| Kingston SA400S37120G 120GB SSD                       | 10       | 0.57%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 9        | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB                        | 9        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                           | 9        | 0.51%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 8        | 0.45%   |
| Seagate ST3500413AS 500GB                             | 8        | 0.45%   |
| Seagate ST2000DM008-2FR102 2TB                        | 8        | 0.45%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 8        | 0.45%   |
| Kingston Company SNV2S1000G 1TB                       | 8        | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                      | 8        | 0.45%   |
| Kingston SA400S37960G 960GB SSD                       | 8        | 0.45%   |
| Unknown                                               | 8        | 0.45%   |
| WDC WD20EFRX-68EUZN0 2TB                              | 7        | 0.4%    |
| WDC WD20EARX-00PASB0 2TB                              | 7        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 7        | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 7        | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 7        | 0.4%    |
| Samsung SSD 850 EVO 500GB                             | 7        | 0.4%    |
| Phison PS5013 E13 NVMe Controller 512GB               | 7        | 0.4%    |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 7        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                          | 7        | 0.4%    |
| Unknown SD/MMC/MS PRO 128GB                           | 6        | 0.34%   |
| Seagate ST31000524AS 1TB                              | 6        | 0.34%   |
| Seagate Expansion 1TB                                 | 6        | 0.34%   |
| SanDisk SSD PLUS 240GB                                | 6        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 219      | 309    | 37.12%  |
| WDC                 | 215      | 303    | 36.44%  |
| Toshiba             | 47       | 60     | 7.97%   |
| Hitachi             | 40       | 50     | 6.78%   |
| Samsung Electronics | 24       | 28     | 4.07%   |
| HGST                | 13       | 18     | 2.2%    |
| Unknown             | 7        | 7      | 1.19%   |
| Maxtor              | 5        | 5      | 0.85%   |
| SABRENT             | 4        | 6      | 0.68%   |
| JMicron Technology  | 3        | 3      | 0.51%   |
| LaCie               | 2        | 2      | 0.34%   |
| External            | 2        | 2      | 0.34%   |
| WD MediaMax         | 1        | 1      | 0.17%   |
| WALRAM              | 1        | 1      | 0.17%   |
| MARVELL             | 1        | 1      | 0.17%   |
| Intenso             | 1        | 2      | 0.17%   |
| HPE                 | 1        | 1      | 0.17%   |
| Fujitsu             | 1        | 1      | 0.17%   |
| Fantom              | 1        | 1      | 0.17%   |
| ASMT                | 1        | 1      | 0.17%   |
| Apple               | 1        | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 123      | 179    | 21.13%  |
| Kingston            | 91       | 110    | 15.64%  |
| Crucial             | 60       | 74     | 10.31%  |
| SanDisk             | 43       | 50     | 7.39%   |
| China               | 34       | 42     | 5.84%   |
| WDC                 | 30       | 37     | 5.15%   |
| A-DATA Technology   | 14       | 15     | 2.41%   |
| PNY                 | 13       | 17     | 2.23%   |
| Intel               | 12       | 13     | 2.06%   |
| SPCC                | 11       | 11     | 1.89%   |
| Intenso             | 11       | 11     | 1.89%   |
| OCZ                 | 8        | 9      | 1.37%   |
| Team                | 7        | 7      | 1.2%    |
| LITEON              | 7        | 10     | 1.2%    |
| Lexar               | 7        | 9      | 1.2%    |
| Micron Technology   | 6        | 8      | 1.03%   |
| Corsair             | 6        | 8      | 1.03%   |
| Verbatim            | 5        | 10     | 0.86%   |
| SK hynix            | 5        | 7      | 0.86%   |
| KingSpec            | 5        | 7      | 0.86%   |
| Transcend           | 4        | 4      | 0.69%   |
| Patriot             | 4        | 6      | 0.69%   |
| Netac               | 4        | 5      | 0.69%   |
| Unknown             | 4        | 6      | 0.69%   |
| Toshiba             | 3        | 3      | 0.52%   |
| Seagate             | 3        | 5      | 0.52%   |
| KIOXIA-EXCERIA      | 3        | 4      | 0.52%   |
| Hewlett-Packard     | 3        | 3      | 0.52%   |
| GOODRAM             | 3        | 4      | 0.52%   |
| Fanxiang            | 3        | 3      | 0.52%   |
| ASMT                | 3        | 4      | 0.52%   |
| Apacer              | 3        | 3      | 0.52%   |
| XrayDisk            | 2        | 3      | 0.34%   |
| LITEONIT            | 2        | 2      | 0.34%   |
| Gigabyte Technology | 2        | 2      | 0.34%   |
| EVM                 | 2        | 2      | 0.34%   |
| Emtec               | 2        | 2      | 0.34%   |
| EAGET               | 2        | 2      | 0.34%   |
| BlueRay             | 2        | 2      | 0.34%   |
| Zebronics           | 1        | 1      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 483      | 803    | 36.81%  |
| SSD     | 478      | 734    | 36.43%  |
| NVMe    | 299      | 495    | 22.79%  |
| Unknown | 48       | 66     | 3.66%   |
| MMC     | 4        | 4      | 0.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 727      | 1499   | 65.97%  |
| NVMe | 297      | 489    | 26.95%  |
| SAS  | 74       | 110    | 6.72%   |
| MMC  | 4        | 4      | 0.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 513      | 779    | 49.52%  |
| 0.51-1.0   | 292      | 412    | 28.19%  |
| 1.01-2.0   | 126      | 185    | 12.16%  |
| 3.01-4.0   | 42       | 69     | 4.05%   |
| 4.01-10.0  | 33       | 54     | 3.19%   |
| 2.01-3.0   | 20       | 24     | 1.93%   |
| 10.01-20.0 | 9        | 13     | 0.87%   |
| 20.01-50.0 | 1        | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 244      | 28.11%  |
| 251-500        | 168      | 19.35%  |
| 501-1000       | 139      | 16.01%  |
| 1001-2000      | 99       | 11.41%  |
| More than 3000 | 86       | 9.91%   |
| 51-100         | 39       | 4.49%   |
| 2001-3000      | 28       | 3.23%   |
| 1-20           | 24       | 2.76%   |
| 21-50          | 22       | 2.53%   |
| Unknown        | 18       | 2.07%   |
| 0              | 1        | 0.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 268      | 29.55%  |
| 1-20           | 253      | 27.89%  |
| 51-100         | 90       | 9.92%   |
| 101-250        | 79       | 8.71%   |
| 251-500        | 60       | 6.62%   |
| 501-1000       | 54       | 5.95%   |
| 1001-2000      | 40       | 4.41%   |
| More than 3000 | 27       | 2.98%   |
| Unknown        | 18       | 1.98%   |
| 2001-3000      | 17       | 1.87%   |
| 0              | 1        | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB                  | 1        | 1      | 6.67%   |
| WDC WD3200AAJS-56M0A0 320GB                  | 1        | 1      | 6.67%   |
| WDC WD3200AAJS-22L7A0 320GB                  | 1        | 1      | 6.67%   |
| WDC WD3200AAJS-08B4A0 320GB                  | 1        | 1      | 6.67%   |
| WDC WD15EARS-00MVWB0 1TB                     | 1        | 1      | 6.67%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1        | 1      | 6.67%   |
| Seagate ST2000LM007-1R8174 2TB               | 1        | 1      | 6.67%   |
| SanDisk SSD PLUS 240GB                       | 1        | 2      | 6.67%   |
| Samsung Electronics SSD 870 EVO 1TB          | 1        | 1      | 6.67%   |
| Samsung Electronics SSD 850 PRO 512GB        | 1        | 1      | 6.67%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1        | 1      | 6.67%   |
| Kingston SA400S37960G 960GB SSD              | 1        | 1      | 6.67%   |
| Hitachi HDS721680PLA380 80GB                 | 1        | 1      | 6.67%   |
| China SSD 1TB                                | 1        | 1      | 6.67%   |
| A-DATA Technology SX8200PNP 512GB            | 1        | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 6      | 30.77%  |
| Samsung Electronics | 3        | 3      | 23.08%  |
| Seagate             | 1        | 1      | 7.69%   |
| SanDisk             | 1        | 2      | 7.69%   |
| Kingston            | 1        | 1      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |
| China               | 1        | 1      | 7.69%   |
| A-DATA Technology   | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 6      | 66.67%  |
| Seagate | 1        | 1      | 16.67%  |
| Hitachi | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 6        | 7      | 46.15%  |
| HDD  | 6        | 8      | 46.15%  |
| NVMe | 1        | 1      | 7.69%   |

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
| Detected | 803      | 1973   | 92.41%  |
| Works    | 53       | 113    | 6.1%    |
| Malfunc  | 13       | 16     | 1.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 564      | 43.09%  |
| AMD                           | 265      | 20.24%  |
| Samsung Electronics           | 88       | 6.72%   |
| SanDisk                       | 53       | 4.05%   |
| ASMedia Technology            | 49       | 3.74%   |
| Kingston Technology Company   | 38       | 2.9%    |
| Phison Electronics            | 34       | 2.6%    |
| Micron/Crucial Technology     | 29       | 2.22%   |
| Marvell Technology Group      | 25       | 1.91%   |
| JMicron Technology            | 25       | 1.91%   |
| Silicon Motion                | 22       | 1.68%   |
| MAXIO Technology (Hangzhou)   | 14       | 1.07%   |
| Realtek Semiconductor         | 13       | 0.99%   |
| SK hynix                      | 11       | 0.84%   |
| ADATA Technology              | 11       | 0.84%   |
| Shenzhen Longsys Electronics  | 10       | 0.76%   |
| Nvidia                        | 9        | 0.69%   |
| Micron Technology             | 8        | 0.61%   |
| Toshiba America Info Systems  | 5        | 0.38%   |
| Seagate Technology            | 5        | 0.38%   |
| KIOXIA                        | 5        | 0.38%   |
| LSI Logic / Symbios Logic     | 4        | 0.31%   |
| Broadcom / LSI                | 4        | 0.31%   |
| Integrated Technology Express | 3        | 0.23%   |
| Hosin Global Electronics      | 3        | 0.23%   |
| VIA Technologies              | 2        | 0.15%   |
| Netac Technology              | 2        | 0.15%   |
| Adaptec                       | 2        | 0.15%   |
| Unknown                       | 2        | 0.15%   |
| OCZ Technology Group          | 1        | 0.08%   |
| INNOGRIT                      | 1        | 0.08%   |
| HighPoint Technologies        | 1        | 0.08%   |
| Biwin Storage Technology      | 1        | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 118      | 7.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 79       | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 50       | 3.23%   |
| AMD 500 Series Chipset SATA Controller                                                  | 48       | 3.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 46       | 2.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 44       | 2.84%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 43       | 2.78%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 43       | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 42       | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 33       | 2.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 28       | 1.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 27       | 1.74%   |
| Intel SATA Controller [RAID mode]                                                       | 26       | 1.68%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 26       | 1.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26       | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 26       | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 26       | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 26       | 1.68%   |
| AMD 600 Series Chipset SATA Controller                                                  | 26       | 1.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 24       | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 23       | 1.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 1.36%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 20       | 1.29%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 19       | 1.23%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                             | 18       | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 16       | 1.03%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 15       | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 15       | 0.97%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 13       | 0.84%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 12       | 0.77%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 12       | 0.77%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 12       | 0.77%   |
| Sandisk WD Black SN850X NVMe SSD                                                        | 11       | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 11       | 0.71%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 11       | 0.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 10       | 0.65%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 9        | 0.58%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 0.58%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 0.58%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 8        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 704      | 57.38%  |
| NVMe | 297      | 24.21%  |
| IDE  | 162      | 13.2%   |
| RAID | 56       | 4.56%   |
| SAS  | 5        | 0.41%   |
| SCSI | 3        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 572      | 67.61%  |
| AMD    | 274      | 32.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor      | 15       | 1.77%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 14       | 1.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 13       | 1.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 13       | 1.53%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 13       | 1.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 11       | 1.3%    |
| AMD Ryzen 7 5800X 8-Core Processor     | 11       | 1.3%    |
| AMD Ryzen 5 5600G with Radeon Graphics | 11       | 1.3%    |
| Intel Core i5-6500 CPU @ 3.20GHz       | 10       | 1.18%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 10       | 1.18%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 9        | 1.06%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 9        | 1.06%   |
| AMD FX-6300 Six-Core Processor         | 9        | 1.06%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 8        | 0.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 8        | 0.94%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 7        | 0.83%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 7        | 0.83%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 7        | 0.83%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 7        | 0.83%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 7        | 0.83%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 7        | 0.83%   |
| Intel Core i5-7400 CPU @ 3.00GHz       | 7        | 0.83%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 7        | 0.83%   |
| Intel Core i3-6100 CPU @ 3.70GHz       | 7        | 0.83%   |
| AMD Ryzen 7 7700X 8-Core Processor     | 7        | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 7        | 0.83%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 7        | 0.83%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 6        | 0.71%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 6        | 0.71%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 6        | 0.71%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 6        | 0.71%   |
| Intel N100                             | 5        | 0.59%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 5        | 0.59%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 5        | 0.59%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 5        | 0.59%   |
| Intel Core i3-4170 CPU @ 3.70GHz       | 5        | 0.59%   |
| Intel Core i3 CPU 550 @ 3.20GHz        | 5        | 0.59%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz   | 5        | 0.59%   |
| AMD Ryzen 9 7900X 12-Core Processor    | 5        | 0.59%   |
| AMD Ryzen 5 5500                       | 5        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 165      | 19.48%  |
| Intel Core i7           | 122      | 14.4%   |
| AMD Ryzen 5             | 72       | 8.5%    |
| Intel Core i3           | 66       | 7.79%   |
| AMD Ryzen 7             | 63       | 7.44%   |
| Other                   | 59       | 6.97%   |
| Intel Xeon              | 41       | 4.84%   |
| AMD Ryzen 9             | 32       | 3.78%   |
| Intel Core 2 Duo        | 28       | 3.31%   |
| Intel Celeron           | 22       | 2.6%    |
| AMD FX                  | 22       | 2.6%    |
| Intel Core 2 Quad       | 20       | 2.36%   |
| Intel Pentium           | 15       | 1.77%   |
| Intel Core i9           | 14       | 1.65%   |
| AMD A10                 | 11       | 1.3%    |
| AMD Phenom II X4        | 10       | 1.18%   |
| AMD Ryzen 3             | 8        | 0.94%   |
| AMD A8                  | 8        | 0.94%   |
| Intel Pentium Dual-Core | 7        | 0.83%   |
| AMD A6                  | 6        | 0.71%   |
| Intel Pentium Dual      | 4        | 0.47%   |
| AMD E1                  | 4        | 0.47%   |
| AMD Athlon II X4        | 4        | 0.47%   |
| Intel Pentium Gold      | 3        | 0.35%   |
| AMD Ryzen 5 PRO         | 3        | 0.35%   |
| AMD Ryzen 3 PRO         | 3        | 0.35%   |
| AMD Phenom II X6        | 3        | 0.35%   |
| AMD E                   | 3        | 0.35%   |
| AMD Athlon II X2        | 3        | 0.35%   |
| Intel Atom              | 2        | 0.24%   |
| AMD Phenom II X2        | 2        | 0.24%   |
| AMD GX                  | 2        | 0.24%   |
| AMD Athlon 64 X2        | 2        | 0.24%   |
| AMD Athlon              | 2        | 0.24%   |
| AMD A4                  | 2        | 0.24%   |
| Intel Pentium 4         | 1        | 0.12%   |
| Intel Core 2 Extreme    | 1        | 0.12%   |
| Intel Core 2            | 1        | 0.12%   |
| Intel Core              | 1        | 0.12%   |
| AMD Sempron             | 1        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 330      | 38.92%  |
| 2      | 184      | 21.7%   |
| 6      | 117      | 13.8%   |
| 8      | 93       | 10.97%  |
| 12     | 39       | 4.6%    |
| 16     | 19       | 2.24%   |
| 14     | 14       | 1.65%   |
| 3      | 14       | 1.65%   |
| 10     | 12       | 1.42%   |
| 1      | 10       | 1.18%   |
| 24     | 7        | 0.83%   |
| 20     | 6        | 0.71%   |
| 18     | 2        | 0.24%   |
| 32     | 1        | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 838      | 99.05%  |
| 2      | 7        | 0.83%   |
| 20     | 1        | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 514      | 60.61%  |
| 1      | 334      | 39.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 846      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 833      | 98%     |
| 0x0a601206 | 3        | 0.35%   |
| 0x0a20120a | 3        | 0.35%   |
| 0x08001138 | 2        | 0.24%   |
| 0x306c3    | 1        | 0.12%   |
| 0x0a601203 | 1        | 0.12%   |
| 0x0a50000d | 1        | 0.12%   |
| 0x0a50000c | 1        | 0.12%   |
| 0x0a20102b | 1        | 0.12%   |
| 0x08701030 | 1        | 0.12%   |
| 0x08701021 | 1        | 0.12%   |
| 0x0800820d | 1        | 0.12%   |
| 0x06003109 | 1        | 0.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 113      | 13.36%  |
| Unknown          | 92       | 10.87%  |
| Zen 3            | 77       | 9.1%    |
| KabyLake         | 74       | 8.75%   |
| IvyBridge        | 73       | 8.63%   |
| SandyBridge      | 65       | 7.68%   |
| Skylake          | 46       | 5.44%   |
| Penryn           | 45       | 5.32%   |
| Zen 2            | 42       | 4.96%   |
| K10              | 27       | 3.19%   |
| Piledriver       | 24       | 2.84%   |
| Zen              | 18       | 2.13%   |
| Zen+             | 17       | 2.01%   |
| Nehalem          | 17       | 2.01%   |
| Core             | 17       | 2.01%   |
| Westmere         | 16       | 1.89%   |
| CometLake        | 13       | 1.54%   |
| Steamroller      | 10       | 1.18%   |
| Bulldozer        | 8        | 0.95%   |
| Goldmont plus    | 6        | 0.71%   |
| Excavator        | 6        | 0.71%   |
| Goldmont         | 5        | 0.59%   |
| Broadwell        | 5        | 0.59%   |
| Bobcat           | 5        | 0.59%   |
| K8 Hammer        | 4        | 0.47%   |
| K10 Llano        | 4        | 0.47%   |
| Alderlake Hybrid | 4        | 0.47%   |
| Silvermont       | 3        | 0.35%   |
| Puma             | 2        | 0.24%   |
| NetBurst         | 2        | 0.24%   |
| Jaguar           | 2        | 0.24%   |
| Icelake          | 2        | 0.24%   |
| TigerLake        | 1        | 0.12%   |
| Bonnell          | 1        | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 355      | 38.63%  |
| AMD                        | 281      | 30.58%  |
| Intel                      | 280      | 30.47%  |
| Matrox Electronics Systems | 1        | 0.11%   |
| ATI Technologies           | 1        | 0.11%   |
| 3DLabs                     | 1        | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 49       | 5.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 30       | 3.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 30       | 3.19%   |
| Intel HD Graphics 530                                                       | 28       | 2.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 26       | 2.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 23       | 2.45%   |
| Nvidia GK208B [GeForce GT 710]                                              | 22       | 2.34%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 21       | 2.24%   |
| AMD Raphael                                                                 | 19       | 2.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 18       | 1.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13       | 1.38%   |
| Nvidia GF119 [GeForce GT 610]                                               | 13       | 1.38%   |
| Intel HD Graphics 630                                                       | 13       | 1.38%   |
| Nvidia GT218 [GeForce 210]                                                  | 12       | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 12       | 1.28%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 12       | 1.28%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 11       | 1.17%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 11       | 1.17%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 1.06%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 10       | 1.06%   |
| Nvidia GK208B [GeForce GT 730]                                              | 9        | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 8        | 0.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 8        | 0.85%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 8        | 0.85%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 8        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 0.75%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 7        | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                         | 7        | 0.75%   |
| Intel AlderLake-S GT1                                                       | 7        | 0.75%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 7        | 0.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 0.75%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 7        | 0.75%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 7        | 0.75%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 7        | 0.75%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 7        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 0.64%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 0.64%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 6        | 0.64%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 6        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 317      | 37.34%  |
| 1 x AMD              | 244      | 28.74%  |
| 1 x Intel            | 230      | 27.09%  |
| Intel + Nvidia       | 20       | 2.36%   |
| AMD + Nvidia         | 17       | 2%      |
| 2 x AMD              | 11       | 1.3%    |
| Intel + AMD          | 5        | 0.59%   |
| 2 x Nvidia           | 2        | 0.24%   |
| 3 x AMD              | 1        | 0.12%   |
| 2 x AMD + 1 x 3DLabs | 1        | 0.12%   |
| 1 x Matrox           | 1        | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 576      | 67.53%  |
| Proprietary | 217      | 25.44%  |
| Unknown     | 60       | 7.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 705      | 82.26%  |
| 1.01-2.0   | 38       | 4.43%   |
| 7.01-8.0   | 34       | 3.97%   |
| 8.01-16.0  | 26       | 3.03%   |
| 5.01-6.0   | 16       | 1.87%   |
| 3.01-4.0   | 16       | 1.87%   |
| 0.51-1.0   | 12       | 1.4%    |
| 0.01-0.5   | 4        | 0.47%   |
| 2.01-3.0   | 3        | 0.35%   |
| 16.01-24.0 | 3        | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 144      | 17.25%  |
| Goldstar             | 100      | 11.98%  |
| Dell                 | 83       | 9.94%   |
| Hewlett-Packard      | 62       | 7.43%   |
| Acer                 | 59       | 7.07%   |
| AOC                  | 50       | 5.99%   |
| Philips              | 38       | 4.55%   |
| BenQ                 | 33       | 3.95%   |
| Ancor Communications | 29       | 3.47%   |
| ViewSonic            | 19       | 2.28%   |
| Lenovo               | 19       | 2.28%   |
| ASUSTek Computer     | 19       | 2.28%   |
| Sony                 | 18       | 2.16%   |
| Iiyama               | 12       | 1.44%   |
| Hitachi              | 9        | 1.08%   |
| HKC                  | 7        | 0.84%   |
| Fujitsu Siemens      | 7        | 0.84%   |
| Unknown              | 6        | 0.72%   |
| Sceptre Tech         | 6        | 0.72%   |
| MSI                  | 6        | 0.72%   |
| Vizio                | 5        | 0.6%    |
| NEC Computers        | 5        | 0.6%    |
| Eizo                 | 4        | 0.48%   |
| Vestel Elektronik    | 3        | 0.36%   |
| STD                  | 3        | 0.36%   |
| RTK                  | 3        | 0.36%   |
| Panasonic            | 3        | 0.36%   |
| Mi                   | 3        | 0.36%   |
| Gigabyte Technology  | 3        | 0.36%   |
| CTV                  | 3        | 0.36%   |
| ___                  | 2        | 0.24%   |
| Xiaomi               | 2        | 0.24%   |
| VIE                  | 2        | 0.24%   |
| Videoseven           | 2        | 0.24%   |
| Unknown (XXX)        | 2        | 0.24%   |
| Toshiba              | 2        | 0.24%   |
| SKY                  | 2        | 0.24%   |
| Sharp                | 2        | 0.24%   |
| Sceptre              | 2        | 0.24%   |
| LG Electronics       | 2        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                      | 6        | 0.68%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                 | 5        | 0.57%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 5        | 0.57%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                        | 5        | 0.57%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 4        | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 4        | 0.46%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch       | 4        | 0.46%   |
| Philips FTV PHL04C3 1920x1080 1440x810mm 65.0-inch                      | 4        | 0.46%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch                 | 4        | 0.46%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch                | 4        | 0.46%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 4        | 0.46%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch   | 3        | 0.34%   |
| Samsung Electronics S19B300 SAM08A5 1366x768 410x230mm 18.5-inch        | 3        | 0.34%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch       | 3        | 0.34%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 3        | 0.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3        | 0.34%   |
| Hewlett-Packard LA2306 HWP294A 1920x1080 509x286mm 23.0-inch            | 3        | 0.34%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                  | 3        | 0.34%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 3        | 0.34%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 3        | 0.34%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 3        | 0.34%   |
| Dell IN2030M DELF03C 1600x900 443x249mm 20.0-inch                       | 3        | 0.34%   |
| CTV TELEFUNKEN CTV0030 1920x1080 708x398mm 32.0-inch                    | 3        | 0.34%   |
| ASUSTek Computer VA27EHE AUS27D2 1920x1080 598x336mm 27.0-inch          | 3        | 0.34%   |
| AOC Q32E2WG5B AOC3202 2560x1440 698x393mm 31.5-inch                     | 3        | 0.34%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                            | 3        | 0.34%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                      | 3        | 0.34%   |
| ___ LCDTV16 ___0101 1920x1080                                           | 2        | 0.23%   |
| ViewSonic XG3220 SERIES VSC1D35 3840x2160 698x393mm 31.5-inch           | 2        | 0.23%   |
| VIE HORIZON Z24 VIE2380 1920x1080 527x296mm 23.8-inch                   | 2        | 0.23%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 2        | 0.23%   |
| STD Monitor STD2023 1920x1080 600x330mm 27.0-inch                       | 2        | 0.23%   |
| Sony TV *00 SNYF303 1920x1080 952x535mm 43.0-inch                       | 2        | 0.23%   |
| Sony SDM-HS95P SNY2600 1280x1024 376x301mm 19.0-inch                    | 2        | 0.23%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x257mm 19.1-inch     | 2        | 0.23%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch       | 2        | 0.23%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch        | 2        | 0.23%   |
| Samsung Electronics Odyssey G5 SAM7488 2560x1440 597x336mm 27.0-inch    | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0C44 3840x2160 1872x1053mm 84.6-inch | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 2        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 362      | 44.86%  |
| 3840x2160 (4K)     | 129      | 15.99%  |
| 2560x1440 (QHD)    | 57       | 7.06%   |
| 1600x900 (HD+)     | 36       | 4.46%   |
| 1366x768 (WXGA)    | 34       | 4.21%   |
| 1440x900 (WXGA+)   | 32       | 3.97%   |
| 1280x1024 (SXGA)   | 30       | 3.72%   |
| 1680x1050 (WSXGA+) | 25       | 3.1%    |
| 1920x1200 (WUXGA)  | 19       | 2.35%   |
| 3440x1440          | 17       | 2.11%   |
| 1360x768           | 13       | 1.61%   |
| 3840x1080          | 10       | 1.24%   |
| 2560x1080          | 10       | 1.24%   |
| Unknown            | 7        | 0.87%   |
| 2560x1600          | 4        | 0.5%    |
| 1920x540           | 4        | 0.5%    |
| 3840x1600          | 3        | 0.37%   |
| 5120x1440          | 2        | 0.25%   |
| 2560x2880          | 2        | 0.25%   |
| 1024x768 (XGA)     | 2        | 0.25%   |
| 5760x2160          | 1        | 0.12%   |
| 5120x1080          | 1        | 0.12%   |
| 3840x1200          | 1        | 0.12%   |
| 2880x1440          | 1        | 0.12%   |
| 2288x1287          | 1        | 0.12%   |
| 1920x1600          | 1        | 0.12%   |
| 1600x1200          | 1        | 0.12%   |
| 1280x960           | 1        | 0.12%   |
| 1280x768           | 1        | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 136      | 16.31%  |
| 24      | 99       | 11.87%  |
| 23      | 93       | 11.15%  |
| 21      | 72       | 8.63%   |
| 31      | 59       | 7.07%   |
| Unknown | 51       | 6.12%   |
| 19      | 40       | 4.8%    |
| 18      | 36       | 4.32%   |
| 20      | 33       | 3.96%   |
| 84      | 29       | 3.48%   |
| 34      | 24       | 2.88%   |
| 22      | 19       | 2.28%   |
| 32      | 18       | 2.16%   |
| 17      | 17       | 2.04%   |
| 72      | 13       | 1.56%   |
| 40      | 9        | 1.08%   |
| 15      | 9        | 1.08%   |
| 54      | 6        | 0.72%   |
| 48      | 6        | 0.72%   |
| 26      | 6        | 0.72%   |
| 65      | 5        | 0.6%    |
| 49      | 5        | 0.6%    |
| 42      | 5        | 0.6%    |
| 28      | 5        | 0.6%    |
| 75      | 4        | 0.48%   |
| 25      | 4        | 0.48%   |
| 74      | 3        | 0.36%   |
| 39      | 3        | 0.36%   |
| 37      | 3        | 0.36%   |
| 29      | 3        | 0.36%   |
| 60      | 2        | 0.24%   |
| 46      | 2        | 0.24%   |
| 16      | 2        | 0.24%   |
| 86      | 1        | 0.12%   |
| 69      | 1        | 0.12%   |
| 64      | 1        | 0.12%   |
| 62      | 1        | 0.12%   |
| 59      | 1        | 0.12%   |
| 55      | 1        | 0.12%   |
| 43      | 1        | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 298      | 36.61%  |
| 401-500     | 186      | 22.85%  |
| 601-700     | 88       | 10.81%  |
| 1501-2000   | 51       | 6.27%   |
| Unknown     | 51       | 6.27%   |
| 701-800     | 42       | 5.16%   |
| 1001-1500   | 30       | 3.69%   |
| 301-350     | 23       | 2.83%   |
| 351-400     | 19       | 2.33%   |
| 801-900     | 15       | 1.84%   |
| 901-1000    | 9        | 1.11%   |
| 201-300     | 2        | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 568      | 73.77%  |
| 16/10   | 83       | 10.78%  |
| Unknown | 39       | 5.06%   |
| 21/9    | 29       | 3.77%   |
| 5/4     | 25       | 3.25%   |
| 32/9    | 10       | 1.3%    |
| 4/3     | 8        | 1.04%   |
| 6/5     | 2        | 0.26%   |
| 2.00    | 2        | 0.26%   |
| 0.89    | 2        | 0.26%   |
| 3/2     | 1        | 0.13%   |
| 0.80    | 1        | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 221      | 26.92%  |
| 301-350        | 137      | 16.69%  |
| 351-500        | 110      | 13.4%   |
| 151-200        | 99       | 12.06%  |
| More than 1000 | 69       | 8.4%    |
| Unknown        | 51       | 6.21%   |
| 141-150        | 42       | 5.12%   |
| 251-300        | 40       | 4.87%   |
| 501-1000       | 34       | 4.14%   |
| 131-140        | 5        | 0.61%   |
| 111-120        | 5        | 0.61%   |
| 101-110        | 5        | 0.61%   |
| 81-90          | 1        | 0.12%   |
| 71-80          | 1        | 0.12%   |
| 121-130        | 1        | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 497      | 63.39%  |
| 101-120       | 128      | 16.33%  |
| Unknown       | 51       | 6.51%   |
| 121-160       | 46       | 5.87%   |
| 1-50          | 45       | 5.74%   |
| 161-240       | 16       | 2.04%   |
| More than 240 | 1        | 0.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 647      | 75.06%  |
| 2     | 112      | 12.99%  |
| 0     | 87       | 10.09%  |
| 3     | 15       | 1.74%   |
| 4     | 1        | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 566      | 45.14%  |
| Intel                                 | 359      | 28.63%  |
| Qualcomm Atheros                      | 61       | 4.86%   |
| Broadcom                              | 43       | 3.43%   |
| TP-Link                               | 35       | 2.79%   |
| Ralink Technology                     | 31       | 2.47%   |
| MediaTek                              | 27       | 2.15%   |
| Ralink                                | 19       | 1.52%   |
| Microsoft                             | 11       | 0.88%   |
| NetGear                               | 9        | 0.72%   |
| Nvidia                                | 8        | 0.64%   |
| Samsung Electronics                   | 7        | 0.56%   |
| Marvell Technology Group              | 7        | 0.56%   |
| Qualcomm Technologies                 | 5        | 0.4%    |
| Qualcomm Atheros Communications       | 5        | 0.4%    |
| ASUSTek Computer                      | 5        | 0.4%    |
| ASIX Electronics                      | 5        | 0.4%    |
| D-Link                                | 4        | 0.32%   |
| Aquantia                              | 4        | 0.32%   |
| Xiaomi                                | 3        | 0.24%   |
| Linksys                               | 3        | 0.24%   |
| D-Link System                         | 3        | 0.24%   |
| ZyXEL Communications                  | 2        | 0.16%   |
| Manta                                 | 2        | 0.16%   |
| BUFFALO                               | 2        | 0.16%   |
| Broadcom Limited                      | 2        | 0.16%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.16%   |
| ZTopInc                               | 1        | 0.08%   |
| Wilocity                              | 1        | 0.08%   |
| Texas Instruments                     | 1        | 0.08%   |
| T & A Mobile Phones                   | 1        | 0.08%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.08%   |
| Sitecom Europe                        | 1        | 0.08%   |
| Raspberry Pi                          | 1        | 0.08%   |
| QinHeng Electronics                   | 1        | 0.08%   |
| Panini                                | 1        | 0.08%   |
| Motorola PCS                          | 1        | 0.08%   |
| Micro Star International              | 1        | 0.08%   |
| Mercucys                              | 1        | 0.08%   |
| Mellanox Technologies                 | 1        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 397      | 27.59%  |
| Realtek RTL8125 2.5GbE Controller                                      | 71       | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 39       | 2.71%   |
| Intel Ethernet Controller I225-V                                       | 34       | 2.36%   |
| Intel Ethernet Connection I217-LM                                      | 34       | 2.36%   |
| Intel Ethernet Connection (2) I219-V                                   | 32       | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 28       | 1.95%   |
| Intel I211 Gigabit Network Connection                                  | 28       | 1.95%   |
| Realtek 802.11ac NIC                                                   | 26       | 1.81%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 25       | 1.74%   |
| Intel Wi-Fi 6 AX200                                                    | 25       | 1.74%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 20       | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                                  | 19       | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 16       | 1.11%   |
| Ralink MT7601U Wireless Adapter                                        | 16       | 1.11%   |
| Intel 82579V Gigabit Network Connection                                | 14       | 0.97%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 13       | 0.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 12       | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 12       | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 11       | 0.76%   |
| Intel Ethernet Connection I217-V                                       | 11       | 0.76%   |
| Intel Ethernet Connection (7) I219-V                                   | 10       | 0.69%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 9        | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9        | 0.63%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 9        | 0.63%   |
| Intel Wireless 7260                                                    | 9        | 0.63%   |
| Intel Ethernet Controller I226-V                                       | 9        | 0.63%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 9        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8        | 0.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 8        | 0.56%   |
| Ralink RT5370 Wireless Adapter                                         | 7        | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7        | 0.49%   |
| Intel Wireless 7265                                                    | 7        | 0.49%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                        | 7        | 0.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 6        | 0.42%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 6        | 0.42%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 6        | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 6        | 0.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6        | 0.42%   |
| Intel Ethernet Connection (2) I218-V                                   | 6        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 141      | 28.83%  |
| Intel                                 | 132      | 26.99%  |
| TP-Link                               | 34       | 6.95%   |
| Ralink Technology                     | 31       | 6.34%   |
| Qualcomm Atheros                      | 31       | 6.34%   |
| MediaTek                              | 23       | 4.7%    |
| Ralink                                | 19       | 3.89%   |
| Broadcom                              | 18       | 3.68%   |
| Microsoft                             | 11       | 2.25%   |
| NetGear                               | 9        | 1.84%   |
| Qualcomm Technologies                 | 5        | 1.02%   |
| Qualcomm Atheros Communications       | 5        | 1.02%   |
| ASUSTek Computer                      | 5        | 1.02%   |
| D-Link                                | 4        | 0.82%   |
| Linksys                               | 3        | 0.61%   |
| ZyXEL Communications                  | 2        | 0.41%   |
| D-Link System                         | 2        | 0.41%   |
| BUFFALO                               | 2        | 0.41%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.41%   |
| ZTopInc                               | 1        | 0.2%    |
| Wilocity                              | 1        | 0.2%    |
| Sitecom Europe                        | 1        | 0.2%    |
| Micro Star International              | 1        | 0.2%    |
| Mercucys                              | 1        | 0.2%    |
| IMC Networks                          | 1        | 0.2%    |
| Gemtek                                | 1        | 0.2%    |
| Edimax Technology                     | 1        | 0.2%    |
| Belkin Components                     | 1        | 0.2%    |
| AVM                                   | 1        | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Realtek 802.11ac NIC                                             | 26       | 5.21%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]        | 25       | 5.01%   |
| Intel Wi-Fi 6 AX200                                              | 25       | 5.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                               | 20       | 4.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 16       | 3.21%   |
| Ralink MT7601U Wireless Adapter                                  | 16       | 3.21%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                | 13       | 2.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 12       | 2.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 11       | 2.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter    | 11       | 2.2%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                       | 9        | 1.8%    |
| Microsoft Xbox Wireless Adapter for Windows                      | 9        | 1.8%    |
| Intel Wireless 7260                                              | 9        | 1.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 9        | 1.8%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]          | 8        | 1.6%    |
| Ralink RT5370 Wireless Adapter                                   | 7        | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 7        | 1.4%    |
| Intel Wireless 7265                                              | 7        | 1.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                      | 6        | 1.2%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter            | 6        | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter    | 6        | 1.2%    |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller      | 5        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 5        | 1%      |
| Realtek RTL8192EE PCIe Wireless Network Adapter                  | 5        | 1%      |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800] | 5        | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                 | 5        | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                  | 5        | 1%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter     | 5        | 1%      |
| TP-Link Archer T3U [Realtek RTL8812BU]                           | 4        | 0.8%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                              | 4        | 0.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]       | 4        | 0.8%    |
| TP-Link 802.11ac WLAN Adapter                                    | 4        | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller      | 4        | 0.8%    |
| Realtek 802.11ac WLAN Adapter                                    | 4        | 0.8%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                        | 4        | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                  | 4        | 0.8%    |
| NetGear A6210                                                    | 4        | 0.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                          | 4        | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                     | 3        | 0.6%    |
| TP-Link 802.11ac NIC                                             | 3        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 510      | 56.67%  |
| Intel                             | 283      | 31.44%  |
| Qualcomm Atheros                  | 33       | 3.67%   |
| Broadcom                          | 26       | 2.89%   |
| Nvidia                            | 8        | 0.89%   |
| Marvell Technology Group          | 7        | 0.78%   |
| Samsung Electronics               | 5        | 0.56%   |
| ASIX Electronics                  | 5        | 0.56%   |
| MediaTek                          | 4        | 0.44%   |
| Aquantia                          | 4        | 0.44%   |
| Xiaomi                            | 3        | 0.33%   |
| Broadcom Limited                  | 2        | 0.22%   |
| TP-Link                           | 1        | 0.11%   |
| T & A Mobile Phones               | 1        | 0.11%   |
| Sundance Technology Inc / IC Plus | 1        | 0.11%   |
| Panini                            | 1        | 0.11%   |
| Motorola PCS                      | 1        | 0.11%   |
| Mellanox Technologies             | 1        | 0.11%   |
| Lenovo                            | 1        | 0.11%   |
| Huawei Technologies               | 1        | 0.11%   |
| DisplayLink                       | 1        | 0.11%   |
| D-Link System                     | 1        | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 397      | 42.69%  |
| Realtek RTL8125 2.5GbE Controller                                             | 71       | 7.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 39       | 4.19%   |
| Intel Ethernet Controller I225-V                                              | 34       | 3.66%   |
| Intel Ethernet Connection I217-LM                                             | 34       | 3.66%   |
| Intel Ethernet Connection (2) I219-V                                          | 32       | 3.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 28       | 3.01%   |
| Intel I211 Gigabit Network Connection                                         | 28       | 3.01%   |
| Intel Ethernet Connection (2) I219-LM                                         | 19       | 2.04%   |
| Intel 82579V Gigabit Network Connection                                       | 14       | 1.51%   |
| Intel Ethernet Connection I217-V                                              | 11       | 1.18%   |
| Intel Ethernet Connection (7) I219-V                                          | 10       | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 9        | 0.97%   |
| Intel Ethernet Controller I226-V                                              | 9        | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 8        | 0.86%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                               | 7        | 0.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 6        | 0.65%   |
| Intel Ethernet Connection (2) I218-V                                          | 6        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 5        | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 5        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                                         | 5        | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                                         | 5        | 0.54%   |
| Intel 82574L Gigabit Network Connection                                       | 5        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 5        | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 5        | 0.54%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 4        | 0.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 4        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 4        | 0.43%   |
| Nvidia MCP61 Ethernet                                                         | 4        | 0.43%   |
| Intel I210 Gigabit Network Connection                                         | 4        | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 4        | 0.43%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                              | 4        | 0.43%   |
| ASIX AX88179 Gigabit Ethernet                                                 | 4        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3        | 0.32%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 3        | 0.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 3        | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 3        | 0.32%   |
| Intel Ethernet Connection (17) I219-LM                                        | 3        | 0.32%   |
| Intel Ethernet Connection (14) I219-V                                         | 3        | 0.32%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 841      | 64.59%  |
| WiFi     | 451      | 34.64%  |
| Modem    | 8        | 0.61%   |
| Unknown  | 2        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 632      | 70.14%  |
| WiFi     | 269      | 29.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 521      | 61.44%  |
| 2     | 286      | 33.73%  |
| 3     | 30       | 3.54%   |
| 4     | 5        | 0.59%   |
| 0     | 4        | 0.47%   |
| 5     | 2        | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 535      | 62.87%  |
| Yes  | 316      | 37.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 123      | 33.51%  |
| Cambridge Silicon Radio         | 78       | 21.25%  |
| Realtek Semiconductor           | 50       | 13.62%  |
| ASUSTek Computer                | 22       | 5.99%   |
| IMC Networks                    | 21       | 5.72%   |
| MediaTek                        | 16       | 4.36%   |
| Qualcomm Atheros Communications | 12       | 3.27%   |
| Foxconn / Hon Hai               | 9        | 2.45%   |
| TP-Link                         | 7        | 1.91%   |
| Broadcom                        | 7        | 1.91%   |
| Actions                         | 7        | 1.91%   |
| Integrated System Solution      | 3        | 0.82%   |
| Realtek                         | 2        | 0.54%   |
| Apple                           | 2        | 0.54%   |
| Roper                           | 1        | 0.27%   |
| Qcom                            | 1        | 0.27%   |
| Micro Star International        | 1        | 0.27%   |
| Kensington                      | 1        | 0.27%   |
| Hewlett-Packard                 | 1        | 0.27%   |
| Edimax Technology               | 1        | 0.27%   |
| Dynex                           | 1        | 0.27%   |
| Belkin Components               | 1        | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 78       | 21.25%  |
| Realtek Bluetooth Radio                               | 40       | 10.9%   |
| Intel AX210 Bluetooth                                 | 23       | 6.27%   |
| Intel AX200 Bluetooth                                 | 23       | 6.27%   |
| Intel Bluetooth wireless interface                    | 18       | 4.9%    |
| Intel AX211 Bluetooth                                 | 17       | 4.63%   |
| MediaTek Wireless_Device                              | 16       | 4.36%   |
| Intel Wireless-AC 3168 Bluetooth                      | 12       | 3.27%   |
| Intel AX201 Bluetooth                                 | 10       | 2.72%   |
| IMC Networks Wireless_Device                          | 10       | 2.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 8        | 2.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 8        | 2.18%   |
| IMC Networks Bluetooth Radio                          | 8        | 2.18%   |
| ASUS ASUS USB-BT500                                   | 8        | 2.18%   |
| TP-Link TP-Link Bluetooth USB Adapter                 | 7        | 1.91%   |
| Actions general adapter                               | 7        | 1.91%   |
| Foxconn / Hon Hai Bluetooth Device                    | 6        | 1.63%   |
| Realtek  Bluetooth 4.2 Adapter                        | 4        | 1.09%   |
| Qualcomm Atheros  Bluetooth Device                    | 4        | 1.09%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4        | 1.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 4        | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3        | 0.82%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 0.82%   |
| ASUS Bluetooth Radio                                  | 3        | 0.82%   |
| Realtek Bluetooth 5.3 Radio                           | 2        | 0.54%   |
| Realtek Bluetooth Radio                               | 2        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 2        | 0.54%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 2        | 0.54%   |
| IMC Networks Bluetooth                                | 2        | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                     | 2        | 0.54%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 0.54%   |
| ASUS Bluetooth Device                                 | 2        | 0.54%   |
| ASUS BCM20702A0                                       | 2        | 0.54%   |
| Roper Class 1 Bluetooth Dongle                        | 1        | 0.27%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1        | 0.27%   |
| Realtek RTL8821A Bluetooth                            | 1        | 0.27%   |
| Realtek RTL8723B Bluetooth                            | 1        | 0.27%   |
| Realtek Bluetooth 5.4 Radio                           | 1        | 0.27%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 560      | 37.89%  |
| AMD                                          | 354      | 23.95%  |
| Nvidia                                       | 341      | 23.07%  |
| C-Media Electronics                          | 31       | 2.1%    |
| Creative Labs                                | 20       | 1.35%   |
| ASUSTek Computer                             | 13       | 0.88%   |
| Micro Star International                     | 12       | 0.81%   |
| Logitech                                     | 8        | 0.54%   |
| Texas Instruments                            | 7        | 0.47%   |
| JMTek                                        | 7        | 0.47%   |
| Zoran Co. Personal Media Division (Nogatech) | 6        | 0.41%   |
| Thesycon Systemsoftware & Consulting         | 5        | 0.34%   |
| SteelSeries ApS                              | 5        | 0.34%   |
| Razer USA                                    | 5        | 0.34%   |
| Plantronics                                  | 5        | 0.34%   |
| Kingston Technology                          | 5        | 0.34%   |
| Focusrite-Novation                           | 5        | 0.34%   |
| Creative Technology                          | 5        | 0.34%   |
| Trust                                        | 4        | 0.27%   |
| Jieli Technology                             | 4        | 0.27%   |
| GN Netcom                                    | 4        | 0.27%   |
| Unknown                                      | 4        | 0.27%   |
| Walmart                                      | 3        | 0.2%    |
| Tenx Technology                              | 3        | 0.2%    |
| Lautsprecher Teufel                          | 3        | 0.2%    |
| KTMicro                                      | 3        | 0.2%    |
| Hewlett-Packard                              | 3        | 0.2%    |
| DSEA A/S                                     | 3        | 0.2%    |
| Corsair                                      | 3        | 0.2%    |
| RODE Microphones                             | 2        | 0.14%   |
| Medeli Electronics                           | 2        | 0.14%   |
| M-Audio                                      | 2        | 0.14%   |
| Generalplus Technology                       | 2        | 0.14%   |
| Dell                                         | 2        | 0.14%   |
| Blue Microphones                             | 2        | 0.14%   |
| BEHRINGER International                      | 2        | 0.14%   |
| Astro Gaming                                 | 2        | 0.14%   |
| VIA Technologies                             | 1        | 0.07%   |
| USB Audio                                    | 1        | 0.07%   |
| Thomann                                      | 1        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 86       | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 82       | 4.71%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 78       | 4.48%   |
| AMD Starship/Matisse HD Audio Controller                                          | 74       | 4.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 56       | 3.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 48       | 2.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 47       | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 47       | 2.7%    |
| Intel 200 Series PCH HD Audio                                                     | 44       | 2.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 42       | 2.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 40       | 2.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 33       | 1.9%    |
| AMD FCH Azalia Controller                                                         | 31       | 1.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 29       | 1.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 29       | 1.67%   |
| Nvidia GA104 High Definition Audio Controller                                     | 26       | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                        | 26       | 1.49%   |
| Intel Raptor Lake High Definition Audio Controller                                | 25       | 1.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 25       | 1.44%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 23       | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 22       | 1.26%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 22       | 1.26%   |
| Intel Alder Lake-S HD Audio Controller                                            | 20       | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 20       | 1.15%   |
| Nvidia GF119 HDMI Audio Controller                                                | 18       | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                                     | 18       | 1.03%   |
| Nvidia High Definition Audio Controller                                           | 17       | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 17       | 0.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 17       | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                                     | 16       | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                                     | 16       | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 16       | 0.92%   |
| AMD Navi 31 HDMI/DP Audio                                                         | 15       | 0.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 14       | 0.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 14       | 0.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 13       | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                     | 12       | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                                     | 12       | 0.69%   |
| Nvidia GA102 High Definition Audio Controller                                     | 12       | 0.69%   |
| Nvidia AD104 High Definition Audio Controller                                     | 12       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 17       | 18.28%  |
| Corsair             | 16       | 17.2%   |
| SK hynix            | 11       | 11.83%  |
| Unknown             | 9        | 9.68%   |
| G.Skill             | 8        | 8.6%    |
| Samsung Electronics | 7        | 7.53%   |
| Crucial             | 7        | 7.53%   |
| Micron Technology   | 4        | 4.3%    |
| A-DATA Technology   | 4        | 4.3%    |
| Team                | 2        | 2.15%   |
| Unknown (C289)      | 1        | 1.08%   |
| Unknown (0x0E9D)    | 1        | 1.08%   |
| Unknown (0x0B38)    | 1        | 1.08%   |
| Smart               | 1        | 1.08%   |
| Patriot             | 1        | 1.08%   |
| Nanya Technology    | 1        | 1.08%   |
| Multilaser          | 1        | 1.08%   |
| Juhor               | 1        | 1.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                          | 2        | 1.9%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s               | 2        | 1.9%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s               | 2        | 1.9%    |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s               | 2        | 1.9%    |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s                | 2        | 1.9%    |
| G.Skill RAM F4-3200C16-16GTZR 16GB DIMM DDR4 3600MT/s              | 2        | 1.9%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s             | 2        | 1.9%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s              | 2        | 1.9%    |
| Unknown RAM Module 8GB DIMM 1066MT/s                               | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM 400MT/s                                | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                               | 1        | 0.95%   |
| Unknown RAM Module 4GB DIMM                                        | 1        | 0.95%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                           | 1        | 0.95%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                | 1        | 0.95%   |
| Unknown RAM Module 2GB DIMM 533MT/s                                | 1        | 0.95%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                | 1        | 0.95%   |
| Unknown (C289) RAM Module 16GB DIMM DDR4 2133MT/s                  | 1        | 0.95%   |
| Unknown (0x0E9D) RAM KINSOTIN16GB2666MHZ 16GB SODIMM DDR4 2667MT/s | 1        | 0.95%   |
| Unknown (0x0B38) RAM GMA16G4SCL196P-26 16GB SODIMM DDR4 2667MT/s   | 1        | 0.95%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                 | 1        | 0.95%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s                 | 1        | 0.95%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s                | 1        | 0.95%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1        | 0.95%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s               | 1        | 0.95%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s               | 1        | 0.95%   |
| SK hynix RAM HMT41GU6AFR8C-PB 8GB DIMM DDR3 1600MT/s               | 1        | 0.95%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s               | 1        | 0.95%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s               | 1        | 0.95%   |
| SK hynix RAM HMT325U6BFR8C-H9 2048MB DIMM DDR3 1333MT/s            | 1        | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s             | 1        | 0.95%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 3200MT/s              | 1        | 0.95%   |
| SK hynix RAM DMT351E6CFR8C-H9 4GB DIMM DDR3 1333MT/s               | 1        | 0.95%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                          | 1        | 0.95%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                          | 1        | 0.95%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                          | 1        | 0.95%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s              | 1        | 0.95%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s             | 1        | 0.95%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s                | 1        | 0.95%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s             | 1        | 0.95%   |
| Patriot RAM 1600 CL9 Series 8GB DIMM DDR3 1600MT/s                 | 1        | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 39       | 49.37%  |
| DDR3    | 21       | 26.58%  |
| DDR5    | 11       | 13.92%  |
| Unknown | 7        | 8.86%   |
| DDR2    | 1        | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 71       | 91.03%  |
| SODIMM | 7        | 8.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 36.36%  |
| 16384 | 25       | 28.41%  |
| 4096  | 20       | 22.73%  |
| 2048  | 6        | 6.82%   |
| 32768 | 4        | 4.55%   |
| 1024  | 1        | 1.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 10.64%  |
| 1333    | 10       | 10.64%  |
| 3600    | 9        | 9.57%   |
| 2667    | 8        | 8.51%   |
| 3200    | 7        | 7.45%   |
| 2400    | 5        | 5.32%   |
| 3733    | 4        | 4.26%   |
| 2133    | 4        | 4.26%   |
| 6000    | 3        | 3.19%   |
| 5600    | 3        | 3.19%   |
| 1800    | 3        | 3.19%   |
| 5200    | 2        | 2.13%   |
| 3534    | 2        | 2.13%   |
| 3400    | 2        | 2.13%   |
| 1866    | 2        | 2.13%   |
| 1648    | 2        | 2.13%   |
| 1066    | 2        | 2.13%   |
| 800     | 2        | 2.13%   |
| 7000    | 1        | 1.06%   |
| 6400    | 1        | 1.06%   |
| 4800    | 1        | 1.06%   |
| 3800    | 1        | 1.06%   |
| 3466    | 1        | 1.06%   |
| 3000    | 1        | 1.06%   |
| 2933    | 1        | 1.06%   |
| 2800    | 1        | 1.06%   |
| 2200    | 1        | 1.06%   |
| 1867    | 1        | 1.06%   |
| 667     | 1        | 1.06%   |
| 533     | 1        | 1.06%   |
| 400     | 1        | 1.06%   |
| Unknown | 1        | 1.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 15       | 31.91%  |
| Seiko Epson              | 7        | 14.89%  |
| Samsung Electronics      | 7        | 14.89%  |
| Brother Industries       | 6        | 12.77%  |
| Canon                    | 5        | 10.64%  |
| Lexmark International    | 2        | 4.26%   |
| Dymo-CoStar              | 2        | 4.26%   |
| Zhuhai Poskey Technology | 1        | 2.13%   |
| Ricoh                    | 1        | 2.13%   |
| Kyocera                  | 1        | 2.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung SCX-3400 Series                               | 3        | 6.25%   |
| HP DeskJet 2700 series                                | 3        | 6.25%   |
| Seiko Epson ET-4850 Series                            | 2        | 4.17%   |
| Canon CanoScan LiDE 300                               | 2        | 4.17%   |
| Zhuhai Poskey 4B-2054L                                | 1        | 2.08%   |
| Seiko Epson XP-3100 Series                            | 1        | 2.08%   |
| Seiko Epson L6270 Series                              | 1        | 2.08%   |
| Seiko Epson L3150 Series                              | 1        | 2.08%   |
| Seiko Epson L3110 Series                              | 1        | 2.08%   |
| Seiko Epson ET-4700 Series                            | 1        | 2.08%   |
| Samsung ML-216x Series Laser Printer                  | 1        | 2.08%   |
| Samsung CLX-3180 Series                               | 1        | 2.08%   |
| Samsung CLX-3170 Series                               | 1        | 2.08%   |
| Samsung C48x Series Color Laser Multifunction Printer | 1        | 2.08%   |
| Ricoh Printing Support                                | 1        | 2.08%   |
| Lexmark International MS710                           | 1        | 2.08%   |
| Lexmark International CX310dn                         | 1        | 2.08%   |
| Kyocera ECOSYS P2235dn                                | 1        | 2.08%   |
| HP Smart Tank 580-590 series                          | 1        | 2.08%   |
| HP OfficeJet 4650 series                              | 1        | 2.08%   |
| HP LaserJet M101-M106                                 | 1        | 2.08%   |
| HP LaserJet 400 M401n                                 | 1        | 2.08%   |
| HP LaserJet 1020                                      | 1        | 2.08%   |
| HP HP LaserJet Pro M404-M405                          | 1        | 2.08%   |
| HP ENVY 6000 series                                   | 1        | 2.08%   |
| HP ENVY 5540 series                                   | 1        | 2.08%   |
| HP Deskjet F4500 series                               | 1        | 2.08%   |
| HP Deskjet 2050 J510                                  | 1        | 2.08%   |
| HP Deskjet 1010 series                                | 1        | 2.08%   |
| HP Color LaserJet CP1215                              | 1        | 2.08%   |
| Dymo-CoStar LabelWriter 450                           | 1        | 2.08%   |
| Dymo-CoStar DYMO LabelWriter 4XL                      | 1        | 2.08%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                | 1        | 2.08%   |
| Canon PIXMA MP280                                     | 1        | 2.08%   |
| Canon PIXMA MP230                                     | 1        | 2.08%   |
| Canon G3020 series                                    | 1        | 2.08%   |
| Brother Printer                                       | 1        | 2.08%   |
| Brother MFC-J475DW                                    | 1        | 2.08%   |
| Brother MFC-1910W                                     | 1        | 2.08%   |
| Brother HL-L2350DW series                             | 1        | 2.08%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 8        | 72.73%  |
| Seiko Epson     | 1        | 9.09%   |
| Mustek Systems  | 1        | 9.09%   |
| Hewlett-Packard | 1        | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Canon CanoScan LiDE 220                     | 2        | 18.18%  |
| Seiko Epson GT-F670 [Perfection V200 Photo] | 1        | 9.09%   |
| Mustek Systems ScanExpress 1200 UB          | 1        | 9.09%   |
| HP ScanJet 5300c/5370c                      | 1        | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1        | 9.09%   |
| Canon CanoScan LiDE 90                      | 1        | 9.09%   |
| Canon CanoScan LiDE 210                     | 1        | 9.09%   |
| Canon CanoScan LiDE 200                     | 1        | 9.09%   |
| Canon CanoScan LiDE 110                     | 1        | 9.09%   |
| Canon CanoScan 8800F                        | 1        | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 65       | 40.88%  |
| Microdia                      | 13       | 8.18%   |
| Microsoft                     | 11       | 6.92%   |
| Chicony Electronics           | 8        | 5.03%   |
| Sunplus Innovation Technology | 7        | 4.4%    |
| Realtek Semiconductor         | 5        | 3.14%   |
| Generalplus Technology        | 4        | 2.52%   |
| Z-Star Microelectronics       | 3        | 1.89%   |
| Insta360                      | 3        | 1.89%   |
| Trust                         | 2        | 1.26%   |
| SunplusIT                     | 2        | 1.26%   |
| Sonix Technology              | 2        | 1.26%   |
| Razer USA                     | 2        | 1.26%   |
| eMeet                         | 2        | 1.26%   |
| ARC International             | 2        | 1.26%   |
| Apple                         | 2        | 1.26%   |
| 2M UVC CAMERA                 | 2        | 1.26%   |
| Teslong Camera                | 1        | 0.63%   |
| Tatung                        | 1        | 0.63%   |
| Suyin                         | 1        | 0.63%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 0.63%   |
| Remo Tech                     | 1        | 0.63%   |
| OmniVision Technologies       | 1        | 0.63%   |
| Netchip Technology            | 1        | 0.63%   |
| MacroSilicon                  | 1        | 0.63%   |
| Lenovo                        | 1        | 0.63%   |
| KYE Systems (Mouse Systems)   | 1        | 0.63%   |
| Jieli Technology              | 1        | 0.63%   |
| IPEVO                         | 1        | 0.63%   |
| Huawei Technologies           | 1        | 0.63%   |
| Hewlett-Packard               | 1        | 0.63%   |
| Guillemot                     | 1        | 0.63%   |
| Google                        | 1        | 0.63%   |
| Genesys Logic                 | 1        | 0.63%   |
| GEMBIRD                       | 1        | 0.63%   |
| Creative Technology           | 1        | 0.63%   |
| AVerMedia Technologies        | 1        | 0.63%   |
| Arkmicro Technologies         | 1        | 0.63%   |
| Anker PowerConf C200          | 1        | 0.63%   |
| A4Tech                        | 1        | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 17       | 10.63%  |
| Logitech HD Pro Webcam C920             | 13       | 8.13%   |
| Microsoft LifeCam HD-3000               | 5        | 3.13%   |
| Logitech Logitech Webcam C925e          | 5        | 3.13%   |
| Logitech HD Webcam C525                 | 5        | 3.13%   |
| Logitech C922 Pro Stream Webcam         | 5        | 3.13%   |
| Logitech BRIO Ultra HD Webcam           | 4        | 2.5%    |
| Sunplus DICOTA 4K                       | 3        | 1.88%   |
| Microsoft LifeCam VX-2000               | 3        | 1.88%   |
| Microdia Webcam Vitade AF               | 3        | 1.88%   |
| Microdia USB 2.0 Camera                 | 3        | 1.88%   |
| Insta360 Link                           | 3        | 1.88%   |
| Generalplus GENERAL WEBCAM              | 3        | 1.88%   |
| Chicony HP High Definition 1MP Webcam   | 3        | 1.88%   |
| Realtek HP 1.0MP High Definition Webcam | 2        | 1.25%   |
| Realtek FULL HD 1080P Webcam            | 2        | 1.25%   |
| Microsoft LifeCam Cinema                | 2        | 1.25%   |
| Microdia Streaming Camera W8GS          | 2        | 1.25%   |
| Logitech Webcam C930e                   | 2        | 1.25%   |
| Logitech Webcam C310                    | 2        | 1.25%   |
| Logitech HD Webcam C615                 | 2        | 1.25%   |
| eMeet HD Webcam C960                    | 2        | 1.25%   |
| Chicony CNF8050 Webcam                  | 2        | 1.25%   |
| ARC International Camera                | 2        | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 2        | 1.25%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam     | 2        | 1.25%   |
| Z-Star Venus USB2.0 Camera              | 1        | 0.63%   |
| Z-Star Proxima USB2.0 Camera            | 1        | 0.63%   |
| Z-Star Lenovo IdeaCentre Web Camera     | 1        | 0.63%   |
| Trust Webcam                            | 1        | 0.63%   |
| Trust Trust Full HD Webcam              | 1        | 0.63%   |
| Teslong Camera Teslong Camera           | 1        | 0.63%   |
| Tatung MAX64380                         | 1        | 0.63%   |
| Suyin HD WebCam                         | 1        | 0.63%   |
| SunplusIT USB camera                    | 1        | 0.63%   |
| SunplusIT USB 2.0 Camera                | 1        | 0.63%   |
| Sunplus USB Camera                      | 1        | 0.63%   |
| Sunplus USB 2.0 Camera                  | 1        | 0.63%   |
| Sunplus HK 5M WebCAM                    | 1        | 0.63%   |
| Sunplus Full HD webcam                  | 1        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Dell      | 2        | 50%     |
| Microsoft | 1        | 25%     |
| AuthenTec | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 2        | 50%     |
| Microsoft Fingerprint Reader                   | 1        | 25%     |
| AuthenTec AES2810                              | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| SCM Microsystems          | 1        | 14.29%  |
| Reiner SCT Kartensysteme  | 1        | 14.29%  |
| NXP Semiconductors        | 1        | 14.29%  |
| Lenovo                    | 1        | 14.29%  |
| Gemalto (was Gemplus)     | 1        | 14.29%  |
| Bit4id                    | 1        | 14.29%  |
| Aladdin Knowledge Systems | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 1        | 14.29%  |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 14.29%  |
| NXP Semiconductors HUSCR-NFC                                               | 1        | 14.29%  |
| Lenovo Smartcard Keyboard                                                  | 1        | 14.29%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 1        | 14.29%  |
| Bit4id miniLector EVO                                                      | 1        | 14.29%  |
| Aladdin Knowledge Systems Token JC                                         | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 688      | 79.63%  |
| 1     | 157      | 18.17%  |
| 2     | 16       | 1.85%   |
| 3     | 3        | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 96       | 50%     |
| Net/wireless             | 45       | 23.44%  |
| Multimedia controller    | 11       | 5.73%   |
| Unassigned class         | 9        | 4.69%   |
| Card reader              | 5        | 2.6%    |
| Net/ethernet             | 4        | 2.08%   |
| Chipcard                 | 4        | 2.08%   |
| Bluetooth                | 4        | 2.08%   |
| Storage/raid             | 3        | 1.56%   |
| Storage/ide              | 2        | 1.04%   |
| Network                  | 2        | 1.04%   |
| Communication controller | 2        | 1.04%   |
| Video                    | 1        | 0.52%   |
| Unclassified device      | 1        | 0.52%   |
| Tv card                  | 1        | 0.52%   |
| Fingerprint reader       | 1        | 0.52%   |
| Dvb card                 | 1        | 0.52%   |

