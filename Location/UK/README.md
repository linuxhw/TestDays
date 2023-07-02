Linux in UK - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

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

Total: 11210

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| lapbook       | S15 PRO                     | Notebook    | [06ae615fd1](https://linux-hardware.org/?probe=06ae615fd1) | Jul 01, 2023 |
| Toshiba       | Satellite Pro L650          | Notebook    | [d8da913f23](https://linux-hardware.org/?probe=d8da913f23) | Jul 01, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [6c8a67be9e](https://linux-hardware.org/?probe=6c8a67be9e) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [a582972a5e](https://linux-hardware.org/?probe=a582972a5e) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Intel         | X99H                        | Desktop     | [8e8c7e8b20](https://linux-hardware.org/?probe=8e8c7e8b20) | Jun 30, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [fe8b1af179](https://linux-hardware.org/?probe=fe8b1af179) | Jun 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [89d751f07f](https://linux-hardware.org/?probe=89d751f07f) | Jun 30, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [e1ed0643fb](https://linux-hardware.org/?probe=e1ed0643fb) | Jun 30, 2023 |
| HP            | Unknown                     | Notebook    | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [0e98c1f04a](https://linux-hardware.org/?probe=0e98c1f04a) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [703ae4bd0b](https://linux-hardware.org/?probe=703ae4bd0b) | Jun 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [265cbaedcc](https://linux-hardware.org/?probe=265cbaedcc) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf3c982248](https://linux-hardware.org/?probe=bf3c982248) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [e8b15eb823](https://linux-hardware.org/?probe=e8b15eb823) | Jun 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [93e0628fbe](https://linux-hardware.org/?probe=93e0628fbe) | Jun 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ddb283952b](https://linux-hardware.org/?probe=ddb283952b) | Jun 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [56e2b61337](https://linux-hardware.org/?probe=56e2b61337) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| Google        | Reef                        | Notebook    | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [031ec94437](https://linux-hardware.org/?probe=031ec94437) | Jun 28, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [9cb1b45a65](https://linux-hardware.org/?probe=9cb1b45a65) | Jun 28, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [2b47aff042](https://linux-hardware.org/?probe=2b47aff042) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [81bbfe3459](https://linux-hardware.org/?probe=81bbfe3459) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [ebb41279ae](https://linux-hardware.org/?probe=ebb41279ae) | Jun 28, 2023 |
| Lenovo        | ThinkPad X240 20AL007LUK    | Notebook    | [ee0761a131](https://linux-hardware.org/?probe=ee0761a131) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [dc758ef355](https://linux-hardware.org/?probe=dc758ef355) | Jun 28, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1ef6edecef](https://linux-hardware.org/?probe=1ef6edecef) | Jun 28, 2023 |
| MSI           | GE70 2PL                    | Notebook    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9128946047](https://linux-hardware.org/?probe=9128946047) | Jun 27, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [a2ef6d8517](https://linux-hardware.org/?probe=a2ef6d8517) | Jun 27, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [3d2a2196ae](https://linux-hardware.org/?probe=3d2a2196ae) | Jun 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [f6d3a1e787](https://linux-hardware.org/?probe=f6d3a1e787) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| Dell          | Precision M6800             | Notebook    | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [88baca047c](https://linux-hardware.org/?probe=88baca047c) | Jun 27, 2023 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [51f9f56f44](https://linux-hardware.org/?probe=51f9f56f44) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [fe27e643ac](https://linux-hardware.org/?probe=fe27e643ac) | Jun 26, 2023 |
| HP            | 859B                        | Desktop     | [63fdd4ed7e](https://linux-hardware.org/?probe=63fdd4ed7e) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| Samsung       | 935QDB                      | Convertible | [d206412575](https://linux-hardware.org/?probe=d206412575) | Jun 26, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ad1a470baf](https://linux-hardware.org/?probe=ad1a470baf) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [7c0c11558d](https://linux-hardware.org/?probe=7c0c11558d) | Jun 26, 2023 |
| HP            | Unknown                     | Notebook    | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | Notebook    | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [9f89885724](https://linux-hardware.org/?probe=9f89885724) | Jun 25, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| Medion        | E2228T MD61050              | Convertible | [595ec84ebc](https://linux-hardware.org/?probe=595ec84ebc) | Jun 25, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [75f62d2200](https://linux-hardware.org/?probe=75f62d2200) | Jun 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [27c389d734](https://linux-hardware.org/?probe=27c389d734) | Jun 24, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [1e1660833e](https://linux-hardware.org/?probe=1e1660833e) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [54ef5b6567](https://linux-hardware.org/?probe=54ef5b6567) | Jun 23, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [a9cd7361e6](https://linux-hardware.org/?probe=a9cd7361e6) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | Notebook    | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| ASRock        | Z87M Pro4                   | Desktop     | [762b33c8e7](https://linux-hardware.org/?probe=762b33c8e7) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [184b19f00c](https://linux-hardware.org/?probe=184b19f00c) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| ASUSTek       | TP550LA                     | Notebook    | [7728203a8a](https://linux-hardware.org/?probe=7728203a8a) | Jun 22, 2023 |
| ASUSTek       | TP550LA                     | Notebook    | [fed72172d2](https://linux-hardware.org/?probe=fed72172d2) | Jun 22, 2023 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [22fb03fe41](https://linux-hardware.org/?probe=22fb03fe41) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [f1e506486c](https://linux-hardware.org/?probe=f1e506486c) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [5c9111463c](https://linux-hardware.org/?probe=5c9111463c) | Jun 21, 2023 |
| Acer          | Aspire 5742Z                | Notebook    | [d1513c944e](https://linux-hardware.org/?probe=d1513c944e) | Jun 21, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [fd3c5ae570](https://linux-hardware.org/?probe=fd3c5ae570) | Jun 21, 2023 |
| HP            | Unknown                     | Notebook    | [4f27a83f9e](https://linux-hardware.org/?probe=4f27a83f9e) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [881e4f3437](https://linux-hardware.org/?probe=881e4f3437) | Jun 20, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [4760bb7306](https://linux-hardware.org/?probe=4760bb7306) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [092370b958](https://linux-hardware.org/?probe=092370b958) | Jun 20, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [b968cb073e](https://linux-hardware.org/?probe=b968cb073e) | Jun 20, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [8260bcf9b3](https://linux-hardware.org/?probe=8260bcf9b3) | Jun 20, 2023 |
| Alienware     | 17 R3                       | Notebook    | [45613f348f](https://linux-hardware.org/?probe=45613f348f) | Jun 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [53b1d3f262](https://linux-hardware.org/?probe=53b1d3f262) | Jun 20, 2023 |
| Dell          | Latitude 7390               | Notebook    | [98d09ed56c](https://linux-hardware.org/?probe=98d09ed56c) | Jun 20, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [2344c78f90](https://linux-hardware.org/?probe=2344c78f90) | Jun 20, 2023 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [5864261490](https://linux-hardware.org/?probe=5864261490) | Jun 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [529320d8fe](https://linux-hardware.org/?probe=529320d8fe) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [36f8057a1d](https://linux-hardware.org/?probe=36f8057a1d) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [e6e1708182](https://linux-hardware.org/?probe=e6e1708182) | Jun 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [159b20029e](https://linux-hardware.org/?probe=159b20029e) | Jun 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [0875b8b413](https://linux-hardware.org/?probe=0875b8b413) | Jun 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| AZW           | GTi                         | Desktop     | [0aaf2297b4](https://linux-hardware.org/?probe=0aaf2297b4) | Jun 17, 2023 |
| Dell          | Latitude 5430               | Notebook    | [1797038bf6](https://linux-hardware.org/?probe=1797038bf6) | Jun 17, 2023 |
| HP            | ENVY m6                     | Notebook    | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1b0dd608b2](https://linux-hardware.org/?probe=1b0dd608b2) | Jun 16, 2023 |
| GEO           | GEOBOOK 2E                  | Notebook    | [9ab9fe3052](https://linux-hardware.org/?probe=9ab9fe3052) | Jun 16, 2023 |
| Unknown       | NETGEAR ReadyNAS 104        | Desktop     | [99df077926](https://linux-hardware.org/?probe=99df077926) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [af1a5cda08](https://linux-hardware.org/?probe=af1a5cda08) | Jun 16, 2023 |
| Acer          | Aspire ES1-522              | Notebook    | [25f52202b2](https://linux-hardware.org/?probe=25f52202b2) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | Notebook    | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [89ac5ef04b](https://linux-hardware.org/?probe=89ac5ef04b) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [f242fcd667](https://linux-hardware.org/?probe=f242fcd667) | Jun 15, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [160f6f4afb](https://linux-hardware.org/?probe=160f6f4afb) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [5fe5f59145](https://linux-hardware.org/?probe=5fe5f59145) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [7974c3961d](https://linux-hardware.org/?probe=7974c3961d) | Jun 15, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [c1375ab639](https://linux-hardware.org/?probe=c1375ab639) | Jun 15, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [4b99537b32](https://linux-hardware.org/?probe=4b99537b32) | Jun 15, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [3dd5692b24](https://linux-hardware.org/?probe=3dd5692b24) | Jun 15, 2023 |
| HP            | Unknown                     | Notebook    | [00c49ad567](https://linux-hardware.org/?probe=00c49ad567) | Jun 14, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [550aa0fda6](https://linux-hardware.org/?probe=550aa0fda6) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [9b67ef406b](https://linux-hardware.org/?probe=9b67ef406b) | Jun 14, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASRock        | Z97 Extreme6                | Desktop     | [8f727c50fb](https://linux-hardware.org/?probe=8f727c50fb) | Jun 14, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3d5cabad57](https://linux-hardware.org/?probe=3d5cabad57) | Jun 14, 2023 |
| Google        | Ampton                      | Notebook    | [294fa26d20](https://linux-hardware.org/?probe=294fa26d20) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| PC Special... | P65_P67RGRERA               | Notebook    | [49773a4767](https://linux-hardware.org/?probe=49773a4767) | Jun 14, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [448deb90fa](https://linux-hardware.org/?probe=448deb90fa) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [922c598503](https://linux-hardware.org/?probe=922c598503) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [e7f84bdb10](https://linux-hardware.org/?probe=e7f84bdb10) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [7b3593a797](https://linux-hardware.org/?probe=7b3593a797) | Jun 13, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [1302a62eeb](https://linux-hardware.org/?probe=1302a62eeb) | Jun 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [6dadff138b](https://linux-hardware.org/?probe=6dadff138b) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [23a30f1056](https://linux-hardware.org/?probe=23a30f1056) | Jun 13, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| Dell          | Latitude 5411               | Notebook    | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [f47c4b27fe](https://linux-hardware.org/?probe=f47c4b27fe) | Jun 13, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [40d06bae85](https://linux-hardware.org/?probe=40d06bae85) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [4c5907abd5](https://linux-hardware.org/?probe=4c5907abd5) | Jun 12, 2023 |
| Timi          | RedmiBook Pro 14            | Notebook    | [7b2e093b24](https://linux-hardware.org/?probe=7b2e093b24) | Jun 12, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [0b42de0b42](https://linux-hardware.org/?probe=0b42de0b42) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [5286f937d8](https://linux-hardware.org/?probe=5286f937d8) | Jun 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [b7ffc34483](https://linux-hardware.org/?probe=b7ffc34483) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [7221d4851c](https://linux-hardware.org/?probe=7221d4851c) | Jun 11, 2023 |
| Entroware     | Poseidon                    | Desktop     | [506bfb1a08](https://linux-hardware.org/?probe=506bfb1a08) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Acer          | Aspire F5-571               | Notebook    | [e54e3157fc](https://linux-hardware.org/?probe=e54e3157fc) | Jun 11, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [777f28f9e8](https://linux-hardware.org/?probe=777f28f9e8) | Jun 11, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [bc315fc56f](https://linux-hardware.org/?probe=bc315fc56f) | Jun 11, 2023 |
| HP            | 8350                        | Desktop     | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7eda1ce433](https://linux-hardware.org/?probe=7eda1ce433) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4fcc967374](https://linux-hardware.org/?probe=4fcc967374) | Jun 11, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [82e1661a51](https://linux-hardware.org/?probe=82e1661a51) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [6f6440cf1e](https://linux-hardware.org/?probe=6f6440cf1e) | Jun 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [dedc98e84e](https://linux-hardware.org/?probe=dedc98e84e) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [4cb72d56f7](https://linux-hardware.org/?probe=4cb72d56f7) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c23450b0df](https://linux-hardware.org/?probe=c23450b0df) | Jun 10, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [873975925d](https://linux-hardware.org/?probe=873975925d) | Jun 10, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [4b6aa9a912](https://linux-hardware.org/?probe=4b6aa9a912) | Jun 10, 2023 |
| HP            | ProBook 4510s               | Notebook    | [43a29ea83e](https://linux-hardware.org/?probe=43a29ea83e) | Jun 09, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [adcb3b193a](https://linux-hardware.org/?probe=adcb3b193a) | Jun 09, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [50c36acc0d](https://linux-hardware.org/?probe=50c36acc0d) | Jun 09, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [e68e693394](https://linux-hardware.org/?probe=e68e693394) | Jun 08, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [28a5b69096](https://linux-hardware.org/?probe=28a5b69096) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| AZW           | Green G4 10                 | Desktop     | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [697f2b18e8](https://linux-hardware.org/?probe=697f2b18e8) | Jun 08, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [4614addc21](https://linux-hardware.org/?probe=4614addc21) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [340054cdd5](https://linux-hardware.org/?probe=340054cdd5) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| HP            | 8350                        | Desktop     | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [73fa9d854f](https://linux-hardware.org/?probe=73fa9d854f) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ff5fc17acc](https://linux-hardware.org/?probe=ff5fc17acc) | Jun 07, 2023 |
| ECS           | GF8100VM-M5                 | Desktop     | [6aa065057f](https://linux-hardware.org/?probe=6aa065057f) | Jun 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [27771c5ea8](https://linux-hardware.org/?probe=27771c5ea8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X61 7674GS3        | Notebook    | [629a290a98](https://linux-hardware.org/?probe=629a290a98) | Jun 07, 2023 |
| Foxconn       | H55M-S                      | Desktop     | [83b86844c0](https://linux-hardware.org/?probe=83b86844c0) | Jun 06, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [788ddd35a8](https://linux-hardware.org/?probe=788ddd35a8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e4335c33f6](https://linux-hardware.org/?probe=e4335c33f6) | Jun 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [99a7a5bd6e](https://linux-hardware.org/?probe=99a7a5bd6e) | Jun 06, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [76a8e35b72](https://linux-hardware.org/?probe=76a8e35b72) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [413ef09459](https://linux-hardware.org/?probe=413ef09459) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [78459738e9](https://linux-hardware.org/?probe=78459738e9) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [b969b91080](https://linux-hardware.org/?probe=b969b91080) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [8c6a275a93](https://linux-hardware.org/?probe=8c6a275a93) | Jun 05, 2023 |
| Dell          | Latitude E5250              | Notebook    | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [e3f89d1faa](https://linux-hardware.org/?probe=e3f89d1faa) | Jun 04, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | Desktop     | [a6804d8ca1](https://linux-hardware.org/?probe=a6804d8ca1) | Jun 04, 2023 |
| MSI           | Katana GF66 11UG            | Notebook    | [d50f02e996](https://linux-hardware.org/?probe=d50f02e996) | Jun 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [5716ed966d](https://linux-hardware.org/?probe=5716ed966d) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [a3d127e3ba](https://linux-hardware.org/?probe=a3d127e3ba) | Jun 04, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [e541266510](https://linux-hardware.org/?probe=e541266510) | Jun 04, 2023 |
| Dell          | Latitude E5520              | Notebook    | [7e2d1fdd22](https://linux-hardware.org/?probe=7e2d1fdd22) | Jun 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [fc6e3f084f](https://linux-hardware.org/?probe=fc6e3f084f) | Jun 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [77d585fa03](https://linux-hardware.org/?probe=77d585fa03) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [f39742476c](https://linux-hardware.org/?probe=f39742476c) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [efa49bf468](https://linux-hardware.org/?probe=efa49bf468) | Jun 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [a9c6f5e0e6](https://linux-hardware.org/?probe=a9c6f5e0e6) | Jun 04, 2023 |
| HP            | Notebook                    | Notebook    | [45553d6493](https://linux-hardware.org/?probe=45553d6493) | Jun 04, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [406fc17c32](https://linux-hardware.org/?probe=406fc17c32) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [dc8f67bb03](https://linux-hardware.org/?probe=dc8f67bb03) | Jun 03, 2023 |
| Foxconn       | A74ML-K                     | Desktop     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [7bdff81d7d](https://linux-hardware.org/?probe=7bdff81d7d) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [e7409e91d9](https://linux-hardware.org/?probe=e7409e91d9) | Jun 03, 2023 |
| Sony          | SVF1521A1EW                 | Notebook    | [4e3fe0308e](https://linux-hardware.org/?probe=4e3fe0308e) | Jun 02, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [2604bac5a5](https://linux-hardware.org/?probe=2604bac5a5) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1b82c0c3c8](https://linux-hardware.org/?probe=1b82c0c3c8) | Jun 02, 2023 |
| Dell          | 0NNNCT A01                  | Desktop     | [1a1e7426a3](https://linux-hardware.org/?probe=1a1e7426a3) | Jun 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9a91f8aedc](https://linux-hardware.org/?probe=9a91f8aedc) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| Intel         | AB2L .A003                  | Mini pc     | [25fb11cde7](https://linux-hardware.org/?probe=25fb11cde7) | Jun 01, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Lenovo        | ThinkPad X61 7674GS3        | Notebook    | [194299200c](https://linux-hardware.org/?probe=194299200c) | Jun 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [16c536cda1](https://linux-hardware.org/?probe=16c536cda1) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [a13bd80e8a](https://linux-hardware.org/?probe=a13bd80e8a) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | Notebook    | [f3dc10c852](https://linux-hardware.org/?probe=f3dc10c852) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | Notebook    | [1d128e6153](https://linux-hardware.org/?probe=1d128e6153) | Jun 01, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [e822eb4072](https://linux-hardware.org/?probe=e822eb4072) | Jun 01, 2023 |
| Lenovo        | 370B SDK0J40700 WIN 3258... | All in one  | [e98c5409ac](https://linux-hardware.org/?probe=e98c5409ac) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [01692ad602](https://linux-hardware.org/?probe=01692ad602) | May 31, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [6b3efa1ef7](https://linux-hardware.org/?probe=6b3efa1ef7) | May 31, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [5f63504f03](https://linux-hardware.org/?probe=5f63504f03) | May 31, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [ac6f421fef](https://linux-hardware.org/?probe=ac6f421fef) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [c76d767402](https://linux-hardware.org/?probe=c76d767402) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [4ed64d3d45](https://linux-hardware.org/?probe=4ed64d3d45) | May 30, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1c87272ed8](https://linux-hardware.org/?probe=1c87272ed8) | May 29, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Fusion5       | FWIN232                     | Tablet      | [9b5781e140](https://linux-hardware.org/?probe=9b5781e140) | May 28, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [2bb14772ce](https://linux-hardware.org/?probe=2bb14772ce) | May 28, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [7ac306d4fa](https://linux-hardware.org/?probe=7ac306d4fa) | May 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [66bff91fdb](https://linux-hardware.org/?probe=66bff91fdb) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [9ee2d1266b](https://linux-hardware.org/?probe=9ee2d1266b) | May 27, 2023 |
| ASRock        | H510M-HDV                   | Desktop     | [27ca3c6650](https://linux-hardware.org/?probe=27ca3c6650) | May 27, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [0577b02521](https://linux-hardware.org/?probe=0577b02521) | May 27, 2023 |
| ASRock        | H510M-HDV                   | Desktop     | [c6315a675c](https://linux-hardware.org/?probe=c6315a675c) | May 27, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [ce0ecf0cce](https://linux-hardware.org/?probe=ce0ecf0cce) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [ecf6ecb00d](https://linux-hardware.org/?probe=ecf6ecb00d) | May 26, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | Notebook    | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 8437                        | Desktop     | [c1c9154683](https://linux-hardware.org/?probe=c1c9154683) | May 26, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [5037ec3f4a](https://linux-hardware.org/?probe=5037ec3f4a) | May 26, 2023 |
| HP            | ENVY Laptop 13-ah0503na     | Notebook    | [cdf2d7b4b4](https://linux-hardware.org/?probe=cdf2d7b4b4) | May 25, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [a88cd7c5a6](https://linux-hardware.org/?probe=a88cd7c5a6) | May 25, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [afda741dec](https://linux-hardware.org/?probe=afda741dec) | May 25, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [7389c979b6](https://linux-hardware.org/?probe=7389c979b6) | May 25, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| Dell          | Latitude 5521               | Notebook    | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [4bbba2e730](https://linux-hardware.org/?probe=4bbba2e730) | May 25, 2023 |
| Dell          | Latitude 7390               | Notebook    | [999bb94a31](https://linux-hardware.org/?probe=999bb94a31) | May 24, 2023 |
| Lenovo        | ThinkPad T431s 20ACA01V0... | Notebook    | [253f7d5359](https://linux-hardware.org/?probe=253f7d5359) | May 24, 2023 |
| Dell EMC      | Edge Gateway 3200           | Mini pc     | [617aeb0068](https://linux-hardware.org/?probe=617aeb0068) | May 24, 2023 |
| Lenovo        | ThinkPad W530 24472BG       | Notebook    | [6431c2bb45](https://linux-hardware.org/?probe=6431c2bb45) | May 24, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [af5b849c20](https://linux-hardware.org/?probe=af5b849c20) | May 23, 2023 |
| Lenovo        | ThinkPad T470s 20HGS4RU0... | Notebook    | [ac8df81694](https://linux-hardware.org/?probe=ac8df81694) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [2cf9c98869](https://linux-hardware.org/?probe=2cf9c98869) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [4da667cc7e](https://linux-hardware.org/?probe=4da667cc7e) | May 23, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a3817d2576](https://linux-hardware.org/?probe=a3817d2576) | May 23, 2023 |
| HP            | Notebook                    | Notebook    | [6e7c128799](https://linux-hardware.org/?probe=6e7c128799) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3d594ff1da](https://linux-hardware.org/?probe=3d594ff1da) | May 23, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | Notebook    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| HP            | 21EF                        | Desktop     | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d5b2c1e7b5](https://linux-hardware.org/?probe=d5b2c1e7b5) | May 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [5e89fe1dc9](https://linux-hardware.org/?probe=5e89fe1dc9) | May 22, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [56fba05f01](https://linux-hardware.org/?probe=56fba05f01) | May 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| AZW           | U59                         | Desktop     | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | Desktop     | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| SYWZ          | S200 Series                 | Desktop     | [6878838d6f](https://linux-hardware.org/?probe=6878838d6f) | May 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [c7f1f9d62a](https://linux-hardware.org/?probe=c7f1f9d62a) | May 22, 2023 |
| Microsoft     | Surface Book                | Tablet      | [01c76b5ed7](https://linux-hardware.org/?probe=01c76b5ed7) | May 21, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [bc39784c46](https://linux-hardware.org/?probe=bc39784c46) | May 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a6f95de398](https://linux-hardware.org/?probe=a6f95de398) | May 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [548626d011](https://linux-hardware.org/?probe=548626d011) | May 21, 2023 |
| Unknown       | V00                         | Mini pc     | [7b8747aad5](https://linux-hardware.org/?probe=7b8747aad5) | May 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [05f3c4f274](https://linux-hardware.org/?probe=05f3c4f274) | May 21, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [d404dc5e03](https://linux-hardware.org/?probe=d404dc5e03) | May 21, 2023 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [5a30bf445a](https://linux-hardware.org/?probe=5a30bf445a) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| Samsung       | DeskTop System              | Desktop     | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [d5213cca3c](https://linux-hardware.org/?probe=d5213cca3c) | May 20, 2023 |
| ASUSTek       | X705UDR                     | Notebook    | [e1f2bf110a](https://linux-hardware.org/?probe=e1f2bf110a) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [f051e7f6da](https://linux-hardware.org/?probe=f051e7f6da) | May 20, 2023 |
| HP            | 1905                        | Desktop     | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| Dell          | Latitude 7280               | Notebook    | [9b98a88e3d](https://linux-hardware.org/?probe=9b98a88e3d) | May 19, 2023 |
| HP            | 1905                        | Desktop     | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [d52cf51575](https://linux-hardware.org/?probe=d52cf51575) | May 19, 2023 |
| Eii           | WSA116                      | Notebook    | [cff66832fd](https://linux-hardware.org/?probe=cff66832fd) | May 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA21D00    | Notebook    | [a692a56bc0](https://linux-hardware.org/?probe=a692a56bc0) | May 19, 2023 |
| Advent        | Roma                        | Notebook    | [f6ca4c331a](https://linux-hardware.org/?probe=f6ca4c331a) | May 19, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [a6755db2c4](https://linux-hardware.org/?probe=a6755db2c4) | May 19, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [3f5ffac86c](https://linux-hardware.org/?probe=3f5ffac86c) | May 19, 2023 |
| Unknown       | V00                         | Mini pc     | [3abd6900c9](https://linux-hardware.org/?probe=3abd6900c9) | May 19, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [c2f9737977](https://linux-hardware.org/?probe=c2f9737977) | May 19, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [ce94bc6589](https://linux-hardware.org/?probe=ce94bc6589) | May 18, 2023 |
| Entroware     | Kratos                      | Notebook    | [ecf875b8e5](https://linux-hardware.org/?probe=ecf875b8e5) | May 18, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [52ee676c29](https://linux-hardware.org/?probe=52ee676c29) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [3c8dcfcf15](https://linux-hardware.org/?probe=3c8dcfcf15) | May 18, 2023 |
| HP            | 3398                        | Desktop     | [a49cbc797b](https://linux-hardware.org/?probe=a49cbc797b) | May 18, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ba813a3367](https://linux-hardware.org/?probe=ba813a3367) | May 18, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d23967583a](https://linux-hardware.org/?probe=d23967583a) | May 18, 2023 |
| Lenovo        | ThinkPad Yoga 460 20EM00... | Convertible | [83edbdf941](https://linux-hardware.org/?probe=83edbdf941) | May 17, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [d4884bd764](https://linux-hardware.org/?probe=d4884bd764) | May 17, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [c6d11a2f8e](https://linux-hardware.org/?probe=c6d11a2f8e) | May 17, 2023 |
| Google        | Samus                       | Notebook    | [d627862e56](https://linux-hardware.org/?probe=d627862e56) | May 16, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | Desktop     | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [546f6e95e9](https://linux-hardware.org/?probe=546f6e95e9) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [54fc8d0489](https://linux-hardware.org/?probe=54fc8d0489) | May 16, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [9ea7971a18](https://linux-hardware.org/?probe=9ea7971a18) | May 16, 2023 |
| eMachines     | E625                        | Notebook    | [8638b2b8c8](https://linux-hardware.org/?probe=8638b2b8c8) | May 15, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [4ea868b4d1](https://linux-hardware.org/?probe=4ea868b4d1) | May 15, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [1bf9f3a0df](https://linux-hardware.org/?probe=1bf9f3a0df) | May 15, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| Dell          | Inspiron 5405               | Notebook    | [9d3ae56a5e](https://linux-hardware.org/?probe=9d3ae56a5e) | May 15, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | Notebook    | [8921a6d64e](https://linux-hardware.org/?probe=8921a6d64e) | May 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [6df9aa02d5](https://linux-hardware.org/?probe=6df9aa02d5) | May 14, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| AMI           | Intel                       | Desktop     | [569d80a4a0](https://linux-hardware.org/?probe=569d80a4a0) | May 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [162219b0fe](https://linux-hardware.org/?probe=162219b0fe) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [f5fa402f37](https://linux-hardware.org/?probe=f5fa402f37) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [49a47c559e](https://linux-hardware.org/?probe=49a47c559e) | May 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [91986cf051](https://linux-hardware.org/?probe=91986cf051) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | Desktop     | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| ASUSTek       | X510UQR                     | Notebook    | [2062004d5f](https://linux-hardware.org/?probe=2062004d5f) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [46e74189f2](https://linux-hardware.org/?probe=46e74189f2) | May 13, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| Dell          | G7 7700                     | Notebook    | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [a60326fa0a](https://linux-hardware.org/?probe=a60326fa0a) | May 13, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2d1acb409a](https://linux-hardware.org/?probe=2d1acb409a) | May 13, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [edc8069ae1](https://linux-hardware.org/?probe=edc8069ae1) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [1146828988](https://linux-hardware.org/?probe=1146828988) | May 13, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [fd2bd3be00](https://linux-hardware.org/?probe=fd2bd3be00) | May 13, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [971b7bfcd1](https://linux-hardware.org/?probe=971b7bfcd1) | May 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [82f01de919](https://linux-hardware.org/?probe=82f01de919) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [8bad0045f6](https://linux-hardware.org/?probe=8bad0045f6) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [78e2c8b948](https://linux-hardware.org/?probe=78e2c8b948) | May 12, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [c9ad858393](https://linux-hardware.org/?probe=c9ad858393) | May 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [01ee28074b](https://linux-hardware.org/?probe=01ee28074b) | May 12, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [f9c1eb381f](https://linux-hardware.org/?probe=f9c1eb381f) | May 11, 2023 |
| Toshiba       | Satellite C75-A             | Notebook    | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [e18646482f](https://linux-hardware.org/?probe=e18646482f) | May 11, 2023 |
| Dell          | Latitude 7390               | Notebook    | [ab2ea4f7a0](https://linux-hardware.org/?probe=ab2ea4f7a0) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [ec1f5e50b8](https://linux-hardware.org/?probe=ec1f5e50b8) | May 11, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [e1ce381308](https://linux-hardware.org/?probe=e1ce381308) | May 11, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [5b0f8f8419](https://linux-hardware.org/?probe=5b0f8f8419) | May 11, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a7178f5792](https://linux-hardware.org/?probe=a7178f5792) | May 11, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d3893db138](https://linux-hardware.org/?probe=d3893db138) | May 10, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [a196cd6710](https://linux-hardware.org/?probe=a196cd6710) | May 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3ea46668c4](https://linux-hardware.org/?probe=3ea46668c4) | May 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [2b0bc04757](https://linux-hardware.org/?probe=2b0bc04757) | May 10, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
| Lenovo        | ThinkPad T450s 20BWS34A0... | Notebook    | [775c2839fa](https://linux-hardware.org/?probe=775c2839fa) | May 10, 2023 |
| Dell          | Latitude 5420               | Notebook    | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| Sony          | SVT1312B4E                  | Notebook    | [dc0f581bc3](https://linux-hardware.org/?probe=dc0f581bc3) | May 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [588003adc9](https://linux-hardware.org/?probe=588003adc9) | May 09, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6c5da31f8b](https://linux-hardware.org/?probe=6c5da31f8b) | May 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| MSI           | MS-7502 Fab D               | Desktop     | [ca5881d77e](https://linux-hardware.org/?probe=ca5881d77e) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0628913a60](https://linux-hardware.org/?probe=0628913a60) | May 08, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [e44f7dfac5](https://linux-hardware.org/?probe=e44f7dfac5) | May 08, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [cabb24b0e7](https://linux-hardware.org/?probe=cabb24b0e7) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f5499886e9](https://linux-hardware.org/?probe=f5499886e9) | May 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7f274b189d](https://linux-hardware.org/?probe=7f274b189d) | May 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a4f7fc7b31](https://linux-hardware.org/?probe=a4f7fc7b31) | May 08, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [dcf5cd4ca2](https://linux-hardware.org/?probe=dcf5cd4ca2) | May 08, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [332c45b4be](https://linux-hardware.org/?probe=332c45b4be) | May 07, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [2e778bdf24](https://linux-hardware.org/?probe=2e778bdf24) | May 07, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [30bd232e19](https://linux-hardware.org/?probe=30bd232e19) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [923397bc88](https://linux-hardware.org/?probe=923397bc88) | May 07, 2023 |
| Lenovo        | V110-15IKB 80TH             | Notebook    | [a908ca11db](https://linux-hardware.org/?probe=a908ca11db) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [369bf3dc68](https://linux-hardware.org/?probe=369bf3dc68) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [f7a174063f](https://linux-hardware.org/?probe=f7a174063f) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [b3c5b71d27](https://linux-hardware.org/?probe=b3c5b71d27) | May 07, 2023 |
| Dell          | Latitude E7440              | Notebook    | [e49cf2551c](https://linux-hardware.org/?probe=e49cf2551c) | May 07, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [af42781d8a](https://linux-hardware.org/?probe=af42781d8a) | May 06, 2023 |
| Dell          | Studio 1749                 | Notebook    | [43eb37cfd7](https://linux-hardware.org/?probe=43eb37cfd7) | May 06, 2023 |
| Dell          | Latitude E4200              | Notebook    | [af2baa1787](https://linux-hardware.org/?probe=af2baa1787) | May 06, 2023 |
| Acer          | Predator PO3-620            | Desktop     | [9ef46f7f3e](https://linux-hardware.org/?probe=9ef46f7f3e) | May 06, 2023 |
| MSI           | MS-7502 Fab D               | Desktop     | [9b80139aca](https://linux-hardware.org/?probe=9b80139aca) | May 06, 2023 |
| MSI           | MEG Z590 ACE GOLD EDITIO... | Desktop     | [e34348c1b5](https://linux-hardware.org/?probe=e34348c1b5) | May 06, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [70862b2870](https://linux-hardware.org/?probe=70862b2870) | May 06, 2023 |
| Google        | Samus                       | Notebook    | [aed9bd140f](https://linux-hardware.org/?probe=aed9bd140f) | May 06, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [a7ef6c976c](https://linux-hardware.org/?probe=a7ef6c976c) | May 06, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [644110c9b9](https://linux-hardware.org/?probe=644110c9b9) | May 06, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [ee58ce6d9c](https://linux-hardware.org/?probe=ee58ce6d9c) | May 06, 2023 |
| MSI           | GS43VR 7RE                  | Notebook    | [4eb5973faa](https://linux-hardware.org/?probe=4eb5973faa) | May 06, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [5c506f94e0](https://linux-hardware.org/?probe=5c506f94e0) | May 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [db330cab38](https://linux-hardware.org/?probe=db330cab38) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [8e19b0629d](https://linux-hardware.org/?probe=8e19b0629d) | May 05, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f7f8025263](https://linux-hardware.org/?probe=f7f8025263) | May 05, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [64aa7fb49b](https://linux-hardware.org/?probe=64aa7fb49b) | May 05, 2023 |
| HP            | 304Ah                       | Desktop     | [d9a160845c](https://linux-hardware.org/?probe=d9a160845c) | May 05, 2023 |
| Medion        | Akoya E1317T                | Notebook    | [e8eb05a52a](https://linux-hardware.org/?probe=e8eb05a52a) | May 05, 2023 |
| HP            | 21EF                        | Desktop     | [6dd5a8409e](https://linux-hardware.org/?probe=6dd5a8409e) | May 05, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [624e1c3f06](https://linux-hardware.org/?probe=624e1c3f06) | May 05, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [7fd9fd4619](https://linux-hardware.org/?probe=7fd9fd4619) | May 04, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [040ab09ebe](https://linux-hardware.org/?probe=040ab09ebe) | May 04, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fb5ac306a](https://linux-hardware.org/?probe=2fb5ac306a) | May 04, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| HP            | 1589                        | Desktop     | [af8e129ecd](https://linux-hardware.org/?probe=af8e129ecd) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e8c596445b](https://linux-hardware.org/?probe=e8c596445b) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [372a18076a](https://linux-hardware.org/?probe=372a18076a) | May 04, 2023 |
| Google        | Samus                       | Notebook    | [a7dfa29233](https://linux-hardware.org/?probe=a7dfa29233) | May 04, 2023 |
| Supermicro    | H12SSL-NT                   | Server      | [6161a05cf1](https://linux-hardware.org/?probe=6161a05cf1) | May 04, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [61cde0d9b2](https://linux-hardware.org/?probe=61cde0d9b2) | May 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b3ed654fde](https://linux-hardware.org/?probe=b3ed654fde) | May 04, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6ec4c764ea](https://linux-hardware.org/?probe=6ec4c764ea) | May 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [df62d15ecc](https://linux-hardware.org/?probe=df62d15ecc) | May 03, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [7996838ce9](https://linux-hardware.org/?probe=7996838ce9) | May 03, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [aac11fced2](https://linux-hardware.org/?probe=aac11fced2) | May 03, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [c488f6ab32](https://linux-hardware.org/?probe=c488f6ab32) | May 03, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [da9c172649](https://linux-hardware.org/?probe=da9c172649) | May 03, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [b68d1b92de](https://linux-hardware.org/?probe=b68d1b92de) | May 03, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [c20844716d](https://linux-hardware.org/?probe=c20844716d) | May 03, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [f87b1ac774](https://linux-hardware.org/?probe=f87b1ac774) | May 03, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [d8b268f8f7](https://linux-hardware.org/?probe=d8b268f8f7) | May 03, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [3c7546e88a](https://linux-hardware.org/?probe=3c7546e88a) | May 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [388caab99a](https://linux-hardware.org/?probe=388caab99a) | May 02, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [26bb61d72f](https://linux-hardware.org/?probe=26bb61d72f) | May 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [ae3ef173a7](https://linux-hardware.org/?probe=ae3ef173a7) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| Advent        | Roma                        | Notebook    | [ec7568545d](https://linux-hardware.org/?probe=ec7568545d) | May 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [f28e109a4b](https://linux-hardware.org/?probe=f28e109a4b) | May 02, 2023 |
| ASUSTek       | X401A1                      | Notebook    | [2a7d35cc4e](https://linux-hardware.org/?probe=2a7d35cc4e) | May 01, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [3c422c5e96](https://linux-hardware.org/?probe=3c422c5e96) | May 01, 2023 |
| Samsung       | 950QDB                      | Convertible | [ecae18f163](https://linux-hardware.org/?probe=ecae18f163) | May 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Acer          | Aspire M3970                | Desktop     | [87a55abfa7](https://linux-hardware.org/?probe=87a55abfa7) | May 01, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [d4b7c4a4db](https://linux-hardware.org/?probe=d4b7c4a4db) | May 01, 2023 |
| Dell          | Precision 5530              | Notebook    | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f75b4a9457](https://linux-hardware.org/?probe=f75b4a9457) | May 01, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [3b45144d62](https://linux-hardware.org/?probe=3b45144d62) | Apr 30, 2023 |
| Toshiba       | EQUIUM P200                 | Notebook    | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1e10eaa9ae](https://linux-hardware.org/?probe=1e10eaa9ae) | Apr 30, 2023 |
| Lenovo        | ThinkPad X230 2325V1K       | Notebook    | [d630569df9](https://linux-hardware.org/?probe=d630569df9) | Apr 30, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | Notebook    | [dff6f75899](https://linux-hardware.org/?probe=dff6f75899) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f0a784354c](https://linux-hardware.org/?probe=f0a784354c) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [332a777929](https://linux-hardware.org/?probe=332a777929) | Apr 30, 2023 |
| HP            | 1998                        | Desktop     | [4ba5ef1211](https://linux-hardware.org/?probe=4ba5ef1211) | Apr 30, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7521d3d742](https://linux-hardware.org/?probe=7521d3d742) | Apr 30, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e3371ae2dc](https://linux-hardware.org/?probe=e3371ae2dc) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [a158a30802](https://linux-hardware.org/?probe=a158a30802) | Apr 29, 2023 |
| Intel         | S5500BC E25124-453          | Server      | [94527a8584](https://linux-hardware.org/?probe=94527a8584) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [6b44ad5061](https://linux-hardware.org/?probe=6b44ad5061) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [ce73a703b6](https://linux-hardware.org/?probe=ce73a703b6) | Apr 29, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [e70d66b3ba](https://linux-hardware.org/?probe=e70d66b3ba) | Apr 29, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [855bed0070](https://linux-hardware.org/?probe=855bed0070) | Apr 28, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [8a23a0fef0](https://linux-hardware.org/?probe=8a23a0fef0) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| HP            | ENVY Notebook               | Notebook    | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| Intel         | S5500BC E25124-453          | Server      | [567a76c24f](https://linux-hardware.org/?probe=567a76c24f) | Apr 28, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | Desktop     | [c8fe6ab042](https://linux-hardware.org/?probe=c8fe6ab042) | Apr 28, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | Notebook    | [6569669912](https://linux-hardware.org/?probe=6569669912) | Apr 28, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [9130280424](https://linux-hardware.org/?probe=9130280424) | Apr 28, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [2de1d6f6f5](https://linux-hardware.org/?probe=2de1d6f6f5) | Apr 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [0958caf898](https://linux-hardware.org/?probe=0958caf898) | Apr 27, 2023 |
| HP            | 1589                        | Desktop     | [632f486421](https://linux-hardware.org/?probe=632f486421) | Apr 27, 2023 |
| Lenovo        | Legion 7-16-ITHg6 82K6      | Notebook    | [2baf2cbc85](https://linux-hardware.org/?probe=2baf2cbc85) | Apr 27, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | Notebook    | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [ae51577ddc](https://linux-hardware.org/?probe=ae51577ddc) | Apr 27, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [19c2a17ec5](https://linux-hardware.org/?probe=19c2a17ec5) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [e35780d356](https://linux-hardware.org/?probe=e35780d356) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [ac51617470](https://linux-hardware.org/?probe=ac51617470) | Apr 26, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [f0ea43f3fd](https://linux-hardware.org/?probe=f0ea43f3fd) | Apr 26, 2023 |
| Intel         | DQ67OW AAG12528-307         | Desktop     | [28245ea080](https://linux-hardware.org/?probe=28245ea080) | Apr 25, 2023 |
| HP            | 18E9                        | Desktop     | [b9bb679cca](https://linux-hardware.org/?probe=b9bb679cca) | Apr 25, 2023 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [8a600077f6](https://linux-hardware.org/?probe=8a600077f6) | Apr 25, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [19ca73662f](https://linux-hardware.org/?probe=19ca73662f) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Google        | Sasuke                      | Notebook    | [7615a1b1e5](https://linux-hardware.org/?probe=7615a1b1e5) | Apr 25, 2023 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [cd95f8ec71](https://linux-hardware.org/?probe=cd95f8ec71) | Apr 25, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [290a99fee9](https://linux-hardware.org/?probe=290a99fee9) | Apr 25, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [9306db1f90](https://linux-hardware.org/?probe=9306db1f90) | Apr 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [620668d216](https://linux-hardware.org/?probe=620668d216) | Apr 25, 2023 |
| Dell          | Latitude XT2                | Notebook    | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Intel         | HM570                       | Desktop     | [1220357b3d](https://linux-hardware.org/?probe=1220357b3d) | Apr 24, 2023 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [f68e55cabc](https://linux-hardware.org/?probe=f68e55cabc) | Apr 24, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [c78c7e9ec1](https://linux-hardware.org/?probe=c78c7e9ec1) | Apr 24, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [267c5b8075](https://linux-hardware.org/?probe=267c5b8075) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [70d478e2eb](https://linux-hardware.org/?probe=70d478e2eb) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [2931b721a3](https://linux-hardware.org/?probe=2931b721a3) | Apr 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [df85ceaa6b](https://linux-hardware.org/?probe=df85ceaa6b) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [455c6b5e28](https://linux-hardware.org/?probe=455c6b5e28) | Apr 23, 2023 |
| Linx          | LINX10V64                   | Tablet      | [84fc9aff4b](https://linux-hardware.org/?probe=84fc9aff4b) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [982ca9079d](https://linux-hardware.org/?probe=982ca9079d) | Apr 23, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [d8b51c995c](https://linux-hardware.org/?probe=d8b51c995c) | Apr 23, 2023 |
| MSI           | A88XM-E35                   | Desktop     | [c26812e2e1](https://linux-hardware.org/?probe=c26812e2e1) | Apr 23, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [bdfb512e83](https://linux-hardware.org/?probe=bdfb512e83) | Apr 23, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [25e942e55c](https://linux-hardware.org/?probe=25e942e55c) | Apr 22, 2023 |
| Gigabyte      | B460 HD3                    | Desktop     | [c9e3b1d5ea](https://linux-hardware.org/?probe=c9e3b1d5ea) | Apr 22, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | Notebook    | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [0cd5599131](https://linux-hardware.org/?probe=0cd5599131) | Apr 22, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [3c0a66f0fc](https://linux-hardware.org/?probe=3c0a66f0fc) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [5aa26aea52](https://linux-hardware.org/?probe=5aa26aea52) | Apr 22, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [4f473af7a9](https://linux-hardware.org/?probe=4f473af7a9) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [936e6fc768](https://linux-hardware.org/?probe=936e6fc768) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e0763f0f69](https://linux-hardware.org/?probe=e0763f0f69) | Apr 22, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [18391e6b6e](https://linux-hardware.org/?probe=18391e6b6e) | Apr 21, 2023 |
| HP            | 18E5                        | Desktop     | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f1227ea669](https://linux-hardware.org/?probe=f1227ea669) | Apr 21, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [6b0104f339](https://linux-hardware.org/?probe=6b0104f339) | Apr 21, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [03bcaf6334](https://linux-hardware.org/?probe=03bcaf6334) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [dfbfce9d2e](https://linux-hardware.org/?probe=dfbfce9d2e) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [66f95f2851](https://linux-hardware.org/?probe=66f95f2851) | Apr 21, 2023 |
| Google        | Swanky                      | Notebook    | [92156daf53](https://linux-hardware.org/?probe=92156daf53) | Apr 21, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [61d7104ec4](https://linux-hardware.org/?probe=61d7104ec4) | Apr 21, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [ea76b8632f](https://linux-hardware.org/?probe=ea76b8632f) | Apr 20, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [2afe988f2e](https://linux-hardware.org/?probe=2afe988f2e) | Apr 20, 2023 |
| Acer          | Aspire M3970                | Desktop     | [d43372f3fd](https://linux-hardware.org/?probe=d43372f3fd) | Apr 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| Dell          | 05WNJ2 A02                  | Server      | [a0623dc5a7](https://linux-hardware.org/?probe=a0623dc5a7) | Apr 20, 2023 |
| Lenovo        | 300e 2nd Gen 82GK           | Convertible | [54c7413bc5](https://linux-hardware.org/?probe=54c7413bc5) | Apr 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [063b4867ba](https://linux-hardware.org/?probe=063b4867ba) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | Desktop     | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | Notebook    | [1ba852f185](https://linux-hardware.org/?probe=1ba852f185) | Apr 20, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [68a7470480](https://linux-hardware.org/?probe=68a7470480) | Apr 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | Desktop     | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [04a458482b](https://linux-hardware.org/?probe=04a458482b) | Apr 19, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | Desktop     | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | Notebook    | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [85700f4804](https://linux-hardware.org/?probe=85700f4804) | Apr 19, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [5cbbc95995](https://linux-hardware.org/?probe=5cbbc95995) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [ff7225c921](https://linux-hardware.org/?probe=ff7225c921) | Apr 19, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a70cdf4848](https://linux-hardware.org/?probe=a70cdf4848) | Apr 19, 2023 |
| Dell          | G5 5590                     | Notebook    | [c7334114be](https://linux-hardware.org/?probe=c7334114be) | Apr 18, 2023 |
| Lenovo        | CRESCENTBAY 31900058 WIN... | All in one  | [529c1ed52a](https://linux-hardware.org/?probe=529c1ed52a) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [323dc7fa4b](https://linux-hardware.org/?probe=323dc7fa4b) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [28d52a565b](https://linux-hardware.org/?probe=28d52a565b) | Apr 18, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [c7a5aadd85](https://linux-hardware.org/?probe=c7a5aadd85) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | Notebook    | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [5c07d2203c](https://linux-hardware.org/?probe=5c07d2203c) | Apr 17, 2023 |
| Samsung       | 930QED                      | Convertible | [fdfe04c5c9](https://linux-hardware.org/?probe=fdfe04c5c9) | Apr 17, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c5ceac2597](https://linux-hardware.org/?probe=c5ceac2597) | Apr 17, 2023 |
| Sony          | SVE1711C5E                  | Notebook    | [e4fbd8fca9](https://linux-hardware.org/?probe=e4fbd8fca9) | Apr 17, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [a70c93f2e7](https://linux-hardware.org/?probe=a70c93f2e7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| AZW           | Speed S                     | Desktop     | [7cf5e54f5b](https://linux-hardware.org/?probe=7cf5e54f5b) | Apr 16, 2023 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [fd0b3fe549](https://linux-hardware.org/?probe=fd0b3fe549) | Apr 16, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [3ad1ee8197](https://linux-hardware.org/?probe=3ad1ee8197) | Apr 16, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [2092251807](https://linux-hardware.org/?probe=2092251807) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [000e6c6702](https://linux-hardware.org/?probe=000e6c6702) | Apr 16, 2023 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [44222bc590](https://linux-hardware.org/?probe=44222bc590) | Apr 16, 2023 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [592c412bd9](https://linux-hardware.org/?probe=592c412bd9) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [962c5734bc](https://linux-hardware.org/?probe=962c5734bc) | Apr 15, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [2e860ef402](https://linux-hardware.org/?probe=2e860ef402) | Apr 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [00ee6cd73f](https://linux-hardware.org/?probe=00ee6cd73f) | Apr 15, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [11b817e884](https://linux-hardware.org/?probe=11b817e884) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [19fc60d2a5](https://linux-hardware.org/?probe=19fc60d2a5) | Apr 14, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [f5940f5ed5](https://linux-hardware.org/?probe=f5940f5ed5) | Apr 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [f3248c9bca](https://linux-hardware.org/?probe=f3248c9bca) | Apr 14, 2023 |
| Acer          | Aspire M3970                | Desktop     | [0792e082e7](https://linux-hardware.org/?probe=0792e082e7) | Apr 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4f384271e](https://linux-hardware.org/?probe=d4f384271e) | Apr 14, 2023 |
| Clevo         | W760T/M740T/M760T           | Notebook    | [0dfaa8f0e8](https://linux-hardware.org/?probe=0dfaa8f0e8) | Apr 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| HUAWEI        | MRG-WXX                     | Notebook    | [56c255e5f0](https://linux-hardware.org/?probe=56c255e5f0) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [bd9c1c1e6d](https://linux-hardware.org/?probe=bd9c1c1e6d) | Apr 14, 2023 |
| HP            | Notebook                    | Notebook    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [0632bfe4d0](https://linux-hardware.org/?probe=0632bfe4d0) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [407ca5845d](https://linux-hardware.org/?probe=407ca5845d) | Apr 13, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [106963edf7](https://linux-hardware.org/?probe=106963edf7) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Shuttle       | FH67                        | Desktop     | [daa2f39981](https://linux-hardware.org/?probe=daa2f39981) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | Notebook    | [9ac01d9237](https://linux-hardware.org/?probe=9ac01d9237) | Apr 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [615a9d3871](https://linux-hardware.org/?probe=615a9d3871) | Apr 12, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| Sony          | SVE1711C5E                  | Notebook    | [07c6f843fb](https://linux-hardware.org/?probe=07c6f843fb) | Apr 12, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [551fabbc17](https://linux-hardware.org/?probe=551fabbc17) | Apr 12, 2023 |
| Dell          | 02K9CR A01                  | Desktop     | [45c419b8d6](https://linux-hardware.org/?probe=45c419b8d6) | Apr 12, 2023 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [19c864f074](https://linux-hardware.org/?probe=19c864f074) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Lenovo        | YB1-X91F                    | Convertible | [e4c0490b89](https://linux-hardware.org/?probe=e4c0490b89) | Apr 12, 2023 |
| Google        | Gnawty                      | Notebook    | [ddb0fea339](https://linux-hardware.org/?probe=ddb0fea339) | Apr 12, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [e92e5de977](https://linux-hardware.org/?probe=e92e5de977) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [8297ce2712](https://linux-hardware.org/?probe=8297ce2712) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [e3fc8c8f43](https://linux-hardware.org/?probe=e3fc8c8f43) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [7f718ab68f](https://linux-hardware.org/?probe=7f718ab68f) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01cae1e152](https://linux-hardware.org/?probe=01cae1e152) | Apr 10, 2023 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [6fd82ceaec](https://linux-hardware.org/?probe=6fd82ceaec) | Apr 09, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [5a039fc6fb](https://linux-hardware.org/?probe=5a039fc6fb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | Notebook    | [8def87668b](https://linux-hardware.org/?probe=8def87668b) | Apr 09, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [bc5cbcd2cb](https://linux-hardware.org/?probe=bc5cbcd2cb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| Dell          | Inspiron 7570               | Notebook    | [2bac711aba](https://linux-hardware.org/?probe=2bac711aba) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [7dc7e5e5c3](https://linux-hardware.org/?probe=7dc7e5e5c3) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [b1c4404d58](https://linux-hardware.org/?probe=b1c4404d58) | Apr 09, 2023 |
| Dell          | 0PU052                      | Desktop     | [8f8c7f3a02](https://linux-hardware.org/?probe=8f8c7f3a02) | Apr 09, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [52728f9e37](https://linux-hardware.org/?probe=52728f9e37) | Apr 08, 2023 |
| Google        | Ampton                      | Notebook    | [e3945d7727](https://linux-hardware.org/?probe=e3945d7727) | Apr 08, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [14a3d5f4be](https://linux-hardware.org/?probe=14a3d5f4be) | Apr 08, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [ef0fbbe0aa](https://linux-hardware.org/?probe=ef0fbbe0aa) | Apr 08, 2023 |
| Dell          | 0KRC95 A01                  | Desktop     | [9300a95302](https://linux-hardware.org/?probe=9300a95302) | Apr 07, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [aab830c5dd](https://linux-hardware.org/?probe=aab830c5dd) | Apr 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0f3e23c7ce](https://linux-hardware.org/?probe=0f3e23c7ce) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| HP            | 82A2                        | Desktop     | [68d2b054d7](https://linux-hardware.org/?probe=68d2b054d7) | Apr 07, 2023 |
| Google        | Bluebird                    | Notebook    | [6ab22238ac](https://linux-hardware.org/?probe=6ab22238ac) | Apr 07, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [5dc44169d0](https://linux-hardware.org/?probe=5dc44169d0) | Apr 07, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [77c6d48d6b](https://linux-hardware.org/?probe=77c6d48d6b) | Apr 06, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [a0584206ea](https://linux-hardware.org/?probe=a0584206ea) | Apr 06, 2023 |
| Dell          | Latitude 7320               | Convertible | [1e86d8349b](https://linux-hardware.org/?probe=1e86d8349b) | Apr 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [e05bffcc8a](https://linux-hardware.org/?probe=e05bffcc8a) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [e2b1578d42](https://linux-hardware.org/?probe=e2b1578d42) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [2cd7831b58](https://linux-hardware.org/?probe=2cd7831b58) | Apr 06, 2023 |
| Google        | Bard                        | Notebook    | [cc1d159d0c](https://linux-hardware.org/?probe=cc1d159d0c) | Apr 05, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [43469cea83](https://linux-hardware.org/?probe=43469cea83) | Apr 05, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [64c9557d34](https://linux-hardware.org/?probe=64c9557d34) | Apr 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8bf7c8a569](https://linux-hardware.org/?probe=8bf7c8a569) | Apr 05, 2023 |
| Dell          | Latitude E5550              | Notebook    | [5527315153](https://linux-hardware.org/?probe=5527315153) | Apr 05, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [011057afa2](https://linux-hardware.org/?probe=011057afa2) | Apr 05, 2023 |
| HP            | 0A9Ch                       | Desktop     | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [5c12ed53b7](https://linux-hardware.org/?probe=5c12ed53b7) | Apr 05, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [6896e5d9e2](https://linux-hardware.org/?probe=6896e5d9e2) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [b5740f3323](https://linux-hardware.org/?probe=b5740f3323) | Apr 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [40ec4e3ec9](https://linux-hardware.org/?probe=40ec4e3ec9) | Apr 04, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [4e7cae1fde](https://linux-hardware.org/?probe=4e7cae1fde) | Apr 04, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [b7068fce05](https://linux-hardware.org/?probe=b7068fce05) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ed948ed552](https://linux-hardware.org/?probe=ed948ed552) | Apr 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1eae1b3796](https://linux-hardware.org/?probe=1eae1b3796) | Apr 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [1af0b7675b](https://linux-hardware.org/?probe=1af0b7675b) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| Dell          | Studio 1558                 | Notebook    | [e9b75d657d](https://linux-hardware.org/?probe=e9b75d657d) | Apr 04, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [3e174ff8a3](https://linux-hardware.org/?probe=3e174ff8a3) | Apr 04, 2023 |
| Lenovo        | Brazos                      | Notebook    | [6415cb26c2](https://linux-hardware.org/?probe=6415cb26c2) | Apr 03, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4061ae40b8](https://linux-hardware.org/?probe=4061ae40b8) | Apr 03, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [b65273209b](https://linux-hardware.org/?probe=b65273209b) | Apr 03, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| AZW           | GTR V01                     | Mini pc     | [83603a9aa8](https://linux-hardware.org/?probe=83603a9aa8) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9a44a4b80a](https://linux-hardware.org/?probe=9a44a4b80a) | Apr 03, 2023 |
| Pegatron      | JESSE                       | Desktop     | [60c37e2dda](https://linux-hardware.org/?probe=60c37e2dda) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d7f3280e60](https://linux-hardware.org/?probe=d7f3280e60) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb4f4da720](https://linux-hardware.org/?probe=fb4f4da720) | Apr 03, 2023 |
| Advent        | Roma                        | Notebook    | [e1bd64e5b5](https://linux-hardware.org/?probe=e1bd64e5b5) | Apr 03, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [daa2099403](https://linux-hardware.org/?probe=daa2099403) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8f8d89fe9a](https://linux-hardware.org/?probe=8f8d89fe9a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a5d404ca3d](https://linux-hardware.org/?probe=a5d404ca3d) | Apr 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [77b1f3bc3e](https://linux-hardware.org/?probe=77b1f3bc3e) | Apr 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [65cee818b6](https://linux-hardware.org/?probe=65cee818b6) | Apr 02, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [36c7cf7a43](https://linux-hardware.org/?probe=36c7cf7a43) | Apr 02, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | Notebook    | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| AZW           | U59                         | Desktop     | [ad59e8fe21](https://linux-hardware.org/?probe=ad59e8fe21) | Apr 02, 2023 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | Notebook    | [3ec9fed32b](https://linux-hardware.org/?probe=3ec9fed32b) | Apr 02, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [16e982e5cb](https://linux-hardware.org/?probe=16e982e5cb) | Apr 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [7d6ecc10d8](https://linux-hardware.org/?probe=7d6ecc10d8) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [58e2308d1e](https://linux-hardware.org/?probe=58e2308d1e) | Apr 02, 2023 |
| Acer          | Predator PO3-610            | Desktop     | [c5fd8fda48](https://linux-hardware.org/?probe=c5fd8fda48) | Apr 02, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [dda3791c20](https://linux-hardware.org/?probe=dda3791c20) | Apr 01, 2023 |
| Eii           | WSA116                      | Notebook    | [00bf1c190b](https://linux-hardware.org/?probe=00bf1c190b) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | Notebook    | [4fc2057b02](https://linux-hardware.org/?probe=4fc2057b02) | Apr 01, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [575a0650aa](https://linux-hardware.org/?probe=575a0650aa) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | Notebook    | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| HP            | Notebook                    | Notebook    | [348d80772f](https://linux-hardware.org/?probe=348d80772f) | Apr 01, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [cea0d2797d](https://linux-hardware.org/?probe=cea0d2797d) | Apr 01, 2023 |
| Acer          | H57M01                      | Desktop     | [215701a84d](https://linux-hardware.org/?probe=215701a84d) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ecd633a350](https://linux-hardware.org/?probe=ecd633a350) | Apr 01, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [dc5fce2825](https://linux-hardware.org/?probe=dc5fce2825) | Apr 01, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [664da8ff45](https://linux-hardware.org/?probe=664da8ff45) | Apr 01, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [714ed0f007](https://linux-hardware.org/?probe=714ed0f007) | Apr 01, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [82d28ac7c0](https://linux-hardware.org/?probe=82d28ac7c0) | Apr 01, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [1146b0ebfc](https://linux-hardware.org/?probe=1146b0ebfc) | Apr 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [2628ea9d8e](https://linux-hardware.org/?probe=2628ea9d8e) | Apr 01, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [caaa544589](https://linux-hardware.org/?probe=caaa544589) | Apr 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [d9a7a6ccf6](https://linux-hardware.org/?probe=d9a7a6ccf6) | Mar 31, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | Desktop     | [49917003da](https://linux-hardware.org/?probe=49917003da) | Mar 31, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [dbe7f7ac9b](https://linux-hardware.org/?probe=dbe7f7ac9b) | Mar 31, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [8ce3dc1981](https://linux-hardware.org/?probe=8ce3dc1981) | Mar 31, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [68fce9ae2d](https://linux-hardware.org/?probe=68fce9ae2d) | Mar 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [d5e7a881e6](https://linux-hardware.org/?probe=d5e7a881e6) | Mar 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [5b3718d617](https://linux-hardware.org/?probe=5b3718d617) | Mar 31, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [fe51f2c62f](https://linux-hardware.org/?probe=fe51f2c62f) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [31d333ecc9](https://linux-hardware.org/?probe=31d333ecc9) | Mar 30, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [3bf5fd0cfd](https://linux-hardware.org/?probe=3bf5fd0cfd) | Mar 30, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [889f3e8521](https://linux-hardware.org/?probe=889f3e8521) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [492d575f31](https://linux-hardware.org/?probe=492d575f31) | Mar 30, 2023 |
| Lenovo        | ThinkPad T400 6475J92       | Notebook    | [1d3c812668](https://linux-hardware.org/?probe=1d3c812668) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [53504486d2](https://linux-hardware.org/?probe=53504486d2) | Mar 29, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [029fa06a9a](https://linux-hardware.org/?probe=029fa06a9a) | Mar 29, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [1c80487906](https://linux-hardware.org/?probe=1c80487906) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| IP3 Tech      | IB8                         | Desktop     | [c12033f9e7](https://linux-hardware.org/?probe=c12033f9e7) | Mar 29, 2023 |
| Lenovo        | ThinkPad T460p 20HYSJKDO... | Notebook    | [1d24c2743f](https://linux-hardware.org/?probe=1d24c2743f) | Mar 29, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [a091222ad4](https://linux-hardware.org/?probe=a091222ad4) | Mar 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [40a3ae2220](https://linux-hardware.org/?probe=40a3ae2220) | Mar 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [a63f5d9198](https://linux-hardware.org/?probe=a63f5d9198) | Mar 28, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [f16690a3df](https://linux-hardware.org/?probe=f16690a3df) | Mar 28, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [8e7d5a0eb8](https://linux-hardware.org/?probe=8e7d5a0eb8) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [2b09d1f769](https://linux-hardware.org/?probe=2b09d1f769) | Mar 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a37020a71d](https://linux-hardware.org/?probe=a37020a71d) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [b8d58bafe3](https://linux-hardware.org/?probe=b8d58bafe3) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [68117fedfe](https://linux-hardware.org/?probe=68117fedfe) | Mar 28, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [03e9908048](https://linux-hardware.org/?probe=03e9908048) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [f511f8bcb1](https://linux-hardware.org/?probe=f511f8bcb1) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [face5f2ef3](https://linux-hardware.org/?probe=face5f2ef3) | Mar 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b26a988f6](https://linux-hardware.org/?probe=0b26a988f6) | Mar 27, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [1dd1eab13e](https://linux-hardware.org/?probe=1dd1eab13e) | Mar 27, 2023 |
| HP            | 1998                        | Desktop     | [82adc9926e](https://linux-hardware.org/?probe=82adc9926e) | Mar 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d6ddfac9d0](https://linux-hardware.org/?probe=d6ddfac9d0) | Mar 27, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [519fc70e27](https://linux-hardware.org/?probe=519fc70e27) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [645c8515a1](https://linux-hardware.org/?probe=645c8515a1) | Mar 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [8a713b663d](https://linux-hardware.org/?probe=8a713b663d) | Mar 27, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5dcd20300a](https://linux-hardware.org/?probe=5dcd20300a) | Mar 27, 2023 |
| Dell          | Latitude 7280               | Notebook    | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| ASUSTek       | M4A78-HTPC                  | Desktop     | [be398d5786](https://linux-hardware.org/?probe=be398d5786) | Mar 27, 2023 |
| HP            | 8704                        | Desktop     | [ab934a36cb](https://linux-hardware.org/?probe=ab934a36cb) | Mar 26, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [36c8e41310](https://linux-hardware.org/?probe=36c8e41310) | Mar 26, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [f1ed5dd70d](https://linux-hardware.org/?probe=f1ed5dd70d) | Mar 26, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [d18cb08996](https://linux-hardware.org/?probe=d18cb08996) | Mar 26, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [797053b2f7](https://linux-hardware.org/?probe=797053b2f7) | Mar 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bf08e5eecd](https://linux-hardware.org/?probe=bf08e5eecd) | Mar 26, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d79b6fc95c](https://linux-hardware.org/?probe=d79b6fc95c) | Mar 26, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [aeec5e2588](https://linux-hardware.org/?probe=aeec5e2588) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8fde777c54](https://linux-hardware.org/?probe=8fde777c54) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| LG Electro... | 16Z90Q-K.AA78A1             | Notebook    | [009542d035](https://linux-hardware.org/?probe=009542d035) | Mar 26, 2023 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [7e37be5b8c](https://linux-hardware.org/?probe=7e37be5b8c) | Mar 25, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [1ea635d2a0](https://linux-hardware.org/?probe=1ea635d2a0) | Mar 25, 2023 |
| HP            | Stream Notebook             | Notebook    | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [7ade2b1d1a](https://linux-hardware.org/?probe=7ade2b1d1a) | Mar 24, 2023 |
| Dell          | Precision 3510              | Notebook    | [2ea0671f5d](https://linux-hardware.org/?probe=2ea0671f5d) | Mar 24, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G513IE_G513IE     | Notebook    | [bc6baa37ef](https://linux-hardware.org/?probe=bc6baa37ef) | Mar 24, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [5bac43b2f0](https://linux-hardware.org/?probe=5bac43b2f0) | Mar 24, 2023 |
| Dell          | 0W13NR A08                  | Server      | [13bd99e4bc](https://linux-hardware.org/?probe=13bd99e4bc) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4731315325](https://linux-hardware.org/?probe=4731315325) | Mar 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [e4d1155524](https://linux-hardware.org/?probe=e4d1155524) | Mar 23, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| Notebook      | W510LU                      | Notebook    | [076125acc3](https://linux-hardware.org/?probe=076125acc3) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [70314c0c37](https://linux-hardware.org/?probe=70314c0c37) | Mar 23, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [10d078d9e2](https://linux-hardware.org/?probe=10d078d9e2) | Mar 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [8fc3d21cf8](https://linux-hardware.org/?probe=8fc3d21cf8) | Mar 22, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [9bfb72d26a](https://linux-hardware.org/?probe=9bfb72d26a) | Mar 21, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [d32441b2c3](https://linux-hardware.org/?probe=d32441b2c3) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [9c3ac61461](https://linux-hardware.org/?probe=9c3ac61461) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [10431e8027](https://linux-hardware.org/?probe=10431e8027) | Mar 20, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Acer          | Revo RL80                   | Desktop     | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| Fujitsu Si... | AMILO Xi 3670               | Notebook    | [bb018988d6](https://linux-hardware.org/?probe=bb018988d6) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [c9c86f1e79](https://linux-hardware.org/?probe=c9c86f1e79) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [436b9d15b0](https://linux-hardware.org/?probe=436b9d15b0) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [29a6e93a49](https://linux-hardware.org/?probe=29a6e93a49) | Mar 20, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [0d7cc03c37](https://linux-hardware.org/?probe=0d7cc03c37) | Mar 20, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [1840c57073](https://linux-hardware.org/?probe=1840c57073) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [8b7918d34b](https://linux-hardware.org/?probe=8b7918d34b) | Mar 20, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [9de8a9a50a](https://linux-hardware.org/?probe=9de8a9a50a) | Mar 20, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [cd5adbbfc0](https://linux-hardware.org/?probe=cd5adbbfc0) | Mar 19, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [87e3ca6a56](https://linux-hardware.org/?probe=87e3ca6a56) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [adc87fc9fa](https://linux-hardware.org/?probe=adc87fc9fa) | Mar 19, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| Notebook      | N150ZU                      | Notebook    | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [63a8165aff](https://linux-hardware.org/?probe=63a8165aff) | Mar 19, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [f60325ef42](https://linux-hardware.org/?probe=f60325ef42) | Mar 19, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [972b8e8c3c](https://linux-hardware.org/?probe=972b8e8c3c) | Mar 19, 2023 |
| HP            | 3397                        | Desktop     | [3f0b2c8e5b](https://linux-hardware.org/?probe=3f0b2c8e5b) | Mar 19, 2023 |
| Dell          | Inspiron 15 7510            | Notebook    | [f7aebbae36](https://linux-hardware.org/?probe=f7aebbae36) | Mar 18, 2023 |
| Unknown       | V00                         | Mini pc     | [6a0c74a051](https://linux-hardware.org/?probe=6a0c74a051) | Mar 18, 2023 |
| Unknown       | V00                         | Mini pc     | [d84f3134b9](https://linux-hardware.org/?probe=d84f3134b9) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [49df72f291](https://linux-hardware.org/?probe=49df72f291) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [1f939ee045](https://linux-hardware.org/?probe=1f939ee045) | Mar 18, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [06d89bd973](https://linux-hardware.org/?probe=06d89bd973) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [5e6e5276e3](https://linux-hardware.org/?probe=5e6e5276e3) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [9c677b7a7b](https://linux-hardware.org/?probe=9c677b7a7b) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [703cc66d3e](https://linux-hardware.org/?probe=703cc66d3e) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| Dell          | Latitude 3410               | Notebook    | [8c71ef60d0](https://linux-hardware.org/?probe=8c71ef60d0) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [def0907a23](https://linux-hardware.org/?probe=def0907a23) | Mar 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7c909a0c5a](https://linux-hardware.org/?probe=7c909a0c5a) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [113406acd8](https://linux-hardware.org/?probe=113406acd8) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [e967c05c1e](https://linux-hardware.org/?probe=e967c05c1e) | Mar 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [674c4a159e](https://linux-hardware.org/?probe=674c4a159e) | Mar 18, 2023 |
| Lenovo        | V580c 20160                 | Notebook    | [b7f2837ccd](https://linux-hardware.org/?probe=b7f2837ccd) | Mar 17, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [d9ac37a2da](https://linux-hardware.org/?probe=d9ac37a2da) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [63dba9dd56](https://linux-hardware.org/?probe=63dba9dd56) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [70a1f8041b](https://linux-hardware.org/?probe=70a1f8041b) | Mar 17, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [e4eb6f31af](https://linux-hardware.org/?probe=e4eb6f31af) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [761d6accb1](https://linux-hardware.org/?probe=761d6accb1) | Mar 16, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [2193d33376](https://linux-hardware.org/?probe=2193d33376) | Mar 16, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [9861151d08](https://linux-hardware.org/?probe=9861151d08) | Mar 16, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ccd15bcfae](https://linux-hardware.org/?probe=ccd15bcfae) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [c6c5f88e4b](https://linux-hardware.org/?probe=c6c5f88e4b) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | Notebook    | [3c632e35c3](https://linux-hardware.org/?probe=3c632e35c3) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [dfe0b34f8b](https://linux-hardware.org/?probe=dfe0b34f8b) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [9f440a48b9](https://linux-hardware.org/?probe=9f440a48b9) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [0ee987e184](https://linux-hardware.org/?probe=0ee987e184) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | Notebook    | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| ZOTAC         | ZBOXNANO-AQ01               | Mini pc     | [ad4d45d3fa](https://linux-hardware.org/?probe=ad4d45d3fa) | Mar 14, 2023 |
| ZOTAC         | ZBOXNANO-AQ01               | Mini pc     | [3d0b03a361](https://linux-hardware.org/?probe=3d0b03a361) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [e2f98f4fd2](https://linux-hardware.org/?probe=e2f98f4fd2) | Mar 14, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [9331f6026e](https://linux-hardware.org/?probe=9331f6026e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [7e90a81e0b](https://linux-hardware.org/?probe=7e90a81e0b) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [1ad8d706ff](https://linux-hardware.org/?probe=1ad8d706ff) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [08924a17f9](https://linux-hardware.org/?probe=08924a17f9) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [ba5c82bc14](https://linux-hardware.org/?probe=ba5c82bc14) | Mar 14, 2023 |
| Google        | Teemo                       | Desktop     | [8082fe87d4](https://linux-hardware.org/?probe=8082fe87d4) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [b3bea1d3a0](https://linux-hardware.org/?probe=b3bea1d3a0) | Mar 14, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [2124288941](https://linux-hardware.org/?probe=2124288941) | Mar 13, 2023 |
| Dell          | 02M8NY A02                  | Desktop     | [b3c31072bb](https://linux-hardware.org/?probe=b3c31072bb) | Mar 13, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [12277151fa](https://linux-hardware.org/?probe=12277151fa) | Mar 13, 2023 |
| Acer          | EM61SM/EM61PM               | Desktop     | [9c746ee546](https://linux-hardware.org/?probe=9c746ee546) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [8c344866da](https://linux-hardware.org/?probe=8c344866da) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [fdb6080ba5](https://linux-hardware.org/?probe=fdb6080ba5) | Mar 13, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [686fb235ce](https://linux-hardware.org/?probe=686fb235ce) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [12d8200114](https://linux-hardware.org/?probe=12d8200114) | Mar 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [ca456dde7d](https://linux-hardware.org/?probe=ca456dde7d) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| OEGStone      | W240EU/W250EUQ/W270EUQ      | Notebook    | [45ea3c4094](https://linux-hardware.org/?probe=45ea3c4094) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [7ce318cc22](https://linux-hardware.org/?probe=7ce318cc22) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [2be528d875](https://linux-hardware.org/?probe=2be528d875) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [83dcd35e5f](https://linux-hardware.org/?probe=83dcd35e5f) | Mar 12, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [1ad7f4ea8e](https://linux-hardware.org/?probe=1ad7f4ea8e) | Mar 12, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [f6c972404c](https://linux-hardware.org/?probe=f6c972404c) | Mar 12, 2023 |
| Gigabyte      | H170M-D3H-CF                | Desktop     | [ec4064a64c](https://linux-hardware.org/?probe=ec4064a64c) | Mar 11, 2023 |
| Gigabyte      | H170M-D3H-CF                | Desktop     | [929aa1d9a8](https://linux-hardware.org/?probe=929aa1d9a8) | Mar 11, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [d841d9761a](https://linux-hardware.org/?probe=d841d9761a) | Mar 11, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [d822a4112f](https://linux-hardware.org/?probe=d822a4112f) | Mar 11, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b17210218f](https://linux-hardware.org/?probe=b17210218f) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [382901fcd7](https://linux-hardware.org/?probe=382901fcd7) | Mar 11, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [2f86f93df5](https://linux-hardware.org/?probe=2f86f93df5) | Mar 11, 2023 |
| ASUSTek       | P5E-V HDMI                  | Desktop     | [0f85d5d628](https://linux-hardware.org/?probe=0f85d5d628) | Mar 11, 2023 |
| Dell          | Latitude E6530              | Notebook    | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Google        | Ampton                      | Notebook    | [641b7d64fc](https://linux-hardware.org/?probe=641b7d64fc) | Mar 10, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [354cdf8592](https://linux-hardware.org/?probe=354cdf8592) | Mar 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [d4cc4ff572](https://linux-hardware.org/?probe=d4cc4ff572) | Mar 10, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [9bcfd20d80](https://linux-hardware.org/?probe=9bcfd20d80) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [661125aac2](https://linux-hardware.org/?probe=661125aac2) | Mar 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| Foxconn       | ETON                        | Desktop     | [3a087bc020](https://linux-hardware.org/?probe=3a087bc020) | Mar 10, 2023 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [cd975ff510](https://linux-hardware.org/?probe=cd975ff510) | Mar 10, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [9c3d2e652a](https://linux-hardware.org/?probe=9c3d2e652a) | Mar 09, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| Dell          | Latitude 7285               | Notebook    | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [026c39773a](https://linux-hardware.org/?probe=026c39773a) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | Notebook    | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| ASUSTek       | Maximus VI IMPACT           | Desktop     | [bca54b81fc](https://linux-hardware.org/?probe=bca54b81fc) | Mar 09, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [69f4444885](https://linux-hardware.org/?probe=69f4444885) | Mar 09, 2023 |
| AZW           | MINI S                      | Desktop     | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [fbb65f4a4e](https://linux-hardware.org/?probe=fbb65f4a4e) | Mar 09, 2023 |
| Google        | Cave                        | Notebook    | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [705893644e](https://linux-hardware.org/?probe=705893644e) | Mar 08, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 1133      | 14.27%  |
| Ubuntu 18.04                 | 599       | 7.54%   |
| Ubuntu 22.04                 | 425       | 5.35%   |
| Zorin 16                     | 198       | 2.49%   |
| Debian 11                    | 169       | 2.13%   |
| Arch Rolling                 | 147       | 1.85%   |
| OpenMandriva 4.3             | 144       | 1.81%   |
| Pop!_OS 22.04                | 136       | 1.71%   |
| OpenMandriva 4.2             | 133       | 1.67%   |
| Manjaro                      | 119       | 1.5%    |
| Linux Mint 20.3              | 116       | 1.46%   |
| Linux Mint 20.2              | 113       | 1.42%   |
| Linux Mint 19.3              | 112       | 1.41%   |
| KDE neon 20.04               | 112       | 1.41%   |
| ArcoLinux Rolling            | 110       | 1.39%   |
| Pop!_OS 20.04                | 108       | 1.36%   |
| Ubuntu 19.04                 | 105       | 1.32%   |
| Ubuntu 20.10                 | 100       | 1.26%   |
| Pop!_OS 21.04                | 100       | 1.26%   |
| Linux Mint 21.1              | 99        | 1.25%   |
| Arch                         | 97        | 1.22%   |
| Ubuntu 21.10                 | 94        | 1.18%   |
| Zorin 15                     | 93        | 1.17%   |
| Ubuntu 19.10                 | 89        | 1.12%   |
| Pop!_OS 20.10                | 86        | 1.08%   |
| Linux Mint 20.1              | 86        | 1.08%   |
| Ubuntu 21.04                 | 81        | 1.02%   |
| OpenMandriva 23.01           | 79        | 0.99%   |
| Xubuntu 20.04                | 77        | 0.97%   |
| Fedora 36                    | 69        | 0.87%   |
| Linux Mint 20                | 67        | 0.84%   |
| Fedora 37                    | 67        | 0.84%   |
| OpenMandriva 23.03           | 65        | 0.82%   |
| Kubuntu 20.04                | 60        | 0.76%   |
| Fedora 34                    | 60        | 0.76%   |
| Pop!_OS 21.10                | 57        | 0.72%   |
| Fedora 35                    | 57        | 0.72%   |
| Ubuntu 18.10                 | 56        | 0.71%   |
| Linux Mint 21                | 53        | 0.67%   |
| openSUSE Tumbleweed-XXXXXXXX | 51        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2672      | 35.4%   |
| Linux Mint    | 673       | 8.92%   |
| Pop!_OS       | 462       | 6.12%   |
| OpenMandriva  | 459       | 6.08%   |
| Fedora        | 413       | 5.47%   |
| Zorin         | 301       | 3.99%   |
| Debian        | 282       | 3.74%   |
| Manjaro       | 242       | 3.21%   |
| Arch          | 242       | 3.21%   |
| Kubuntu       | 169       | 2.24%   |
| KDE neon      | 155       | 2.05%   |
| Xubuntu       | 148       | 1.96%   |
| ArcoLinux     | 114       | 1.51%   |
| SteamOS       | 90        | 1.19%   |
| ROSA          | 79        | 1.05%   |
| Elementary    | 74        | 0.98%   |
| Gentoo        | 73        | 0.97%   |
| openSUSE      | 72        | 0.95%   |
| Ubuntu MATE   | 65        | 0.86%   |
| Lubuntu       | 55        | 0.73%   |
| Endless       | 54        | 0.72%   |
| Ubuntu Unity  | 49        | 0.65%   |
| Kali          | 49        | 0.65%   |
| Clear Linux   | 46        | 0.61%   |
| BlackPanther  | 42        | 0.56%   |
| LMDE          | 30        | 0.4%    |
| CentOS        | 27        | 0.36%   |
| Ubuntu Budgie | 24        | 0.32%   |
| MX            | 24        | 0.32%   |
| EndeavourOS   | 24        | 0.32%   |
| Nobara        | 23        | 0.3%    |
| Garuda Linux  | 23        | 0.3%    |
| Raspbian      | 22        | 0.29%   |
| RHEL          | 17        | 0.23%   |
| Peppermint    | 17        | 0.23%   |
| Parrot        | 17        | 0.23%   |
| NixOS         | 13        | 0.17%   |
| Slackware     | 12        | 0.16%   |
| Alpine        | 9         | 0.12%   |
| Reborn OS     | 7         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 152       | 1.72%   |
| 5.16.7-desktop-1omv4003  | 136       | 1.54%   |
| 5.10.14-desktop-1omv4002 | 130       | 1.47%   |
| 5.15.0-56-generic        | 82        | 0.93%   |
| 5.4.0-48-generic         | 81        | 0.92%   |
| 5.4.0-52-generic         | 76        | 0.86%   |
| 5.4.0-29-generic         | 73        | 0.82%   |
| 6.1.1-desktop-1omv2290   | 71        | 0.8%    |
| 5.4.0-26-generic         | 70        | 0.79%   |
| 6.2.6-desktop-1omv2390   | 65        | 0.73%   |
| 5.3.0-28-generic         | 65        | 0.73%   |
| 5.15.0-52-generic        | 65        | 0.73%   |
| 5.15.0-46-generic        | 64        | 0.72%   |
| 5.15.0-58-generic        | 63        | 0.71%   |
| 5.3.0-40-generic         | 60        | 0.68%   |
| 5.4.0-40-generic         | 53        | 0.6%    |
| 5.4.0-58-generic         | 51        | 0.58%   |
| 5.4.0-37-generic         | 51        | 0.58%   |
| 5.11.0-27-generic        | 51        | 0.58%   |
| 5.4.0-65-generic         | 45        | 0.51%   |
| 5.4.0-33-generic         | 45        | 0.51%   |
| 5.11.0-38-generic        | 45        | 0.51%   |
| 5.0.0-32-generic         | 45        | 0.51%   |
| 5.4.0-91-generic         | 43        | 0.49%   |
| 5.19.0-35-generic        | 43        | 0.49%   |
| 5.13.0-7614-generic      | 43        | 0.49%   |
| 5.11.0-25-generic        | 43        | 0.49%   |
| 5.4.0-7634-generic       | 41        | 0.46%   |
| 5.4.0-54-generic         | 41        | 0.46%   |
| 5.3.0-46-generic         | 41        | 0.46%   |
| 5.4.0-74-generic         | 40        | 0.45%   |
| 5.4.0-66-generic         | 40        | 0.45%   |
| 5.8.0-7630-generic       | 39        | 0.44%   |
| 5.8.0-43-generic         | 39        | 0.44%   |
| 5.11.0-7620-generic      | 39        | 0.44%   |
| 5.0.0-37-generic         | 39        | 0.44%   |
| 5.15.0-48-generic        | 38        | 0.43%   |
| 5.13.0-28-generic        | 38        | 0.43%   |
| 5.11.0-40-generic        | 38        | 0.43%   |
| 5.3.0-42-generic         | 37        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1507      | 18.3%   |
| 5.15.0  | 712       | 8.64%   |
| 5.11.0  | 455       | 5.52%   |
| 5.13.0  | 454       | 5.51%   |
| 5.8.0   | 449       | 5.45%   |
| 4.15.0  | 417       | 5.06%   |
| 5.3.0   | 374       | 4.54%   |
| 5.19.0  | 257       | 3.12%   |
| 5.0.0   | 244       | 2.96%   |
| 5.10.0  | 200       | 2.43%   |
| 4.18.0  | 181       | 2.2%    |
| 5.16.7  | 137       | 1.66%   |
| 5.10.14 | 130       | 1.58%   |
| 6.2.6   | 100       | 1.21%   |
| 6.1.1   | 76        | 0.92%   |
| 4.19.0  | 58        | 0.7%    |
| 6.2.0   | 47        | 0.57%   |
| 6.1.0   | 39        | 0.47%   |
| 5.17.5  | 36        | 0.44%   |
| 5.14.0  | 34        | 0.41%   |
| 4.18.16 | 32        | 0.39%   |
| 6.0.0   | 31        | 0.38%   |
| 6.0.6   | 26        | 0.32%   |
| 6.0.12  | 26        | 0.32%   |
| 4.9.60  | 26        | 0.32%   |
| 5.9.16  | 25        | 0.3%    |
| 5.18.0  | 22        | 0.27%   |
| 4.4.0   | 21        | 0.25%   |
| 5.17.1  | 19        | 0.23%   |
| 5.16.13 | 19        | 0.23%   |
| 5.18.12 | 18        | 0.22%   |
| 5.16.11 | 18        | 0.22%   |
| 5.15.12 | 17        | 0.21%   |
| 5.13.12 | 17        | 0.21%   |
| 5.7.0   | 16        | 0.19%   |
| 5.6.14  | 16        | 0.19%   |
| 5.16.0  | 16        | 0.19%   |
| 4.9.20  | 16        | 0.19%   |
| 6.1.9   | 15        | 0.18%   |
| 5.17.0  | 15        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1598      | 19.68%  |
| 5.15    | 906       | 11.16%  |
| 5.13    | 540       | 6.65%   |
| 5.8     | 536       | 6.6%    |
| 5.11    | 513       | 6.32%   |
| 5.10    | 465       | 5.73%   |
| 5.3     | 424       | 5.22%   |
| 4.15    | 419       | 5.16%   |
| 5.19    | 347       | 4.27%   |
| 5.0     | 254       | 3.13%   |
| 5.16    | 248       | 3.05%   |
| 6.1     | 239       | 2.94%   |
| 6.2     | 238       | 2.93%   |
| 4.18    | 216       | 2.66%   |
| 6.0     | 154       | 1.9%    |
| 5.17    | 107       | 1.32%   |
| 5.14    | 103       | 1.27%   |
| 5.9     | 95        | 1.17%   |
| 5.18    | 93        | 1.15%   |
| 4.19    | 91        | 1.12%   |
| 5.12    | 88        | 1.08%   |
| 5.6     | 77        | 0.95%   |
| 4.9     | 74        | 0.91%   |
| 5.7     | 68        | 0.84%   |
| 6.3     | 63        | 0.78%   |
| 5.5     | 42        | 0.52%   |
| 4.4     | 25        | 0.31%   |
| 5.2     | 23        | 0.28%   |
| 5.1     | 16        | 0.2%    |
| 4.14    | 10        | 0.12%   |
| 4.1     | 9         | 0.11%   |
| 3.10    | 9         | 0.11%   |
| 4.20    | 5         | 0.06%   |
| 4.13    | 5         | 0.06%   |
| 3.13    | 4         | 0.05%   |
| 6.4     | 3         | 0.04%   |
| 4.16    | 3         | 0.04%   |
| 4.12    | 3         | 0.04%   |
| 4.8     | 2         | 0.02%   |
| 5       | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6973      | 96.27%  |
| i686    | 176       | 2.43%   |
| aarch64 | 66        | 0.91%   |
| armv7l  | 27        | 0.37%   |
| armv6l  | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 3435      | 45.22%  |
| KDE5             | 1244      | 16.38%  |
| Unknown          | 945       | 12.44%  |
| X-Cinnamon       | 544       | 7.16%   |
| XFCE             | 505       | 6.65%   |
| MATE             | 196       | 2.58%   |
| KDE              | 179       | 2.36%   |
| Cinnamon         | 88        | 1.16%   |
| Pantheon         | 70        | 0.92%   |
| Unity            | 51        | 0.67%   |
| LXQt             | 51        | 0.67%   |
| LXDE             | 50        | 0.66%   |
| KDE4             | 36        | 0.47%   |
| Budgie           | 33        | 0.43%   |
| i3               | 32        | 0.42%   |
| GNOME Flashback  | 26        | 0.34%   |
| sway             | 14        | 0.18%   |
| Deepin           | 13        | 0.17%   |
| openbox          | 11        | 0.14%   |
| GNOME Classic    | 10        | 0.13%   |
| qtile            | 8         | 0.11%   |
| awesome          | 8         | 0.11%   |
| lightdm-xsession | 7         | 0.09%   |
| xmonad           | 5         | 0.07%   |
| bspwm            | 5         | 0.07%   |
| trinity          | 4         | 0.05%   |
| Hyprland         | 4         | 0.05%   |
| enlightenment    | 3         | 0.04%   |
| DWM              | 3         | 0.04%   |
| mwm              | 2         | 0.03%   |
| i3-with-shmlog   | 2         | 0.03%   |
| Cutefish         | 2         | 0.03%   |
| chadwm           | 2         | 0.03%   |
| xubuntu          | 1         | 0.01%   |
| WindowMaker      | 1         | 0.01%   |
| Phosh:GNOME      | 1         | 0.01%   |
| LeftWM           | 1         | 0.01%   |
| icewm            | 1         | 0.01%   |
| Hypr             | 1         | 0.01%   |
| GNUstep          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5753      | 77.3%   |
| Wayland | 1041      | 13.99%  |
| Unknown | 464       | 6.23%   |
| Tty     | 183       | 2.46%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4150      | 54.92%  |
| SDDM    | 1028      | 13.6%   |
| GDM3    | 752       | 9.95%   |
| GDM     | 725       | 9.59%   |
| LightDM | 627       | 8.3%    |
| TDM     | 198       | 2.62%   |
| KDM     | 35        | 0.46%   |
| XDM     | 15        | 0.2%    |
| LXDM    | 9         | 0.12%   |
| SLiM    | 6         | 0.08%   |
| Ly      | 6         | 0.08%   |
| GREETD  | 2         | 0.03%   |
| XINIT   | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_GB          | 5368      | 72.28%  |
| en_US          | 912       | 12.28%  |
| Unknown        | 816       | 10.99%  |
| C              | 114       | 1.53%   |
| pl_PL          | 58        | 0.78%   |
| POSIX          | 14        | 0.19%   |
| ru_RU          | 13        | 0.18%   |
| de_DE          | 12        | 0.16%   |
| it_IT          | 10        | 0.13%   |
| fr_FR          | 10        | 0.13%   |
| en_IE          | 10        | 0.13%   |
| en_CA          | 10        | 0.13%   |
| en_AU          | 7         | 0.09%   |
| ro_RO          | 6         | 0.08%   |
| en_IN          | 6         | 0.08%   |
| cs_CZ          | 6         | 0.08%   |
| hu_HU          | 5         | 0.07%   |
| es_ES          | 5         | 0.07%   |
| C.UTF8         | 5         | 0.07%   |
| pt_PT          | 4         | 0.05%   |
| zh_CN          | 3         | 0.04%   |
| sk_SK          | 3         | 0.04%   |
| pt_BR          | 3         | 0.04%   |
| uk_UA          | 2         | 0.03%   |
| nl_NL          | 2         | 0.03%   |
| lt_LT          | 2         | 0.03%   |
| en_ZA          | 2         | 0.03%   |
| en_GB.iso88591 | 2         | 0.03%   |
| da_DK          | 2         | 0.03%   |
| bg_BG          | 2         | 0.03%   |
| wbp_AU         | 1         | 0.01%   |
| tr_TR          | 1         | 0.01%   |
| ru_UA          | 1         | 0.01%   |
| nl_BE          | 1         | 0.01%   |
| fi_FI          | 1         | 0.01%   |
| et_EE          | 1         | 0.01%   |
| en_US.utf-8    | 1         | 0.01%   |
| en_SG          | 1         | 0.01%   |
| en_IL          | 1         | 0.01%   |
| en_HK          | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3887      | 52.51%  |
| EFI  | 3516      | 47.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5753      | 77.26%  |
| Btrfs    | 656       | 8.81%   |
| Overlay  | 505       | 6.78%   |
| Unknown  | 233       | 3.13%   |
| Xfs      | 105       | 1.41%   |
| Tmpfs    | 85        | 1.14%   |
| Zfs      | 62        | 0.83%   |
| Ext2     | 21        | 0.28%   |
| Ext3     | 11        | 0.15%   |
| F2fs     | 10        | 0.13%   |
| Aufs     | 2         | 0.03%   |
| Reiserfs | 1         | 0.01%   |
| Lvm      | 1         | 0.01%   |
| ExX4     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4294      | 57.75%  |
| GPT     | 2477      | 33.31%  |
| MBR     | 665       | 8.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6287      | 84.94%  |
| Yes       | 1115      | 15.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5371      | 72.87%  |
| Yes       | 2000      | 27.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1117      | 15.44%  |
| ASUSTek Computer        | 1053      | 14.55%  |
| Hewlett-Packard         | 915       | 12.65%  |
| Lenovo                  | 898       | 12.41%  |
| Gigabyte Technology     | 523       | 7.23%   |
| MSI                     | 401       | 5.54%   |
| Acer                    | 342       | 4.73%   |
| ASRock                  | 220       | 3.04%   |
| Apple                   | 211       | 2.92%   |
| Toshiba                 | 168       | 2.32%   |
| Intel                   | 130       | 1.8%    |
| Samsung Electronics     | 86        | 1.19%   |
| Valve                   | 82        | 1.13%   |
| Raspberry Pi Foundation | 74        | 1.02%   |
| Sony                    | 60        | 0.83%   |
| Unknown                 | 57        | 0.79%   |
| Fujitsu                 | 48        | 0.66%   |
| PC Specialist           | 44        | 0.61%   |
| Microsoft               | 44        | 0.61%   |
| HUAWEI                  | 44        | 0.61%   |
| Google                  | 44        | 0.61%   |
| Packard Bell            | 35        | 0.48%   |
| Foxconn                 | 33        | 0.46%   |
| Notebook                | 30        | 0.41%   |
| Alienware               | 27        | 0.37%   |
| AZW                     | 26        | 0.36%   |
| Pegatron                | 22        | 0.3%    |
| Fujitsu Siemens         | 21        | 0.29%   |
| Star Labs               | 19        | 0.26%   |
| Razer                   | 19        | 0.26%   |
| Medion                  | 19        | 0.26%   |
| GEO                     | 18        | 0.25%   |
| Biostar                 | 18        | 0.25%   |
| Entroware               | 16        | 0.22%   |
| Linx                    | 15        | 0.21%   |
| AMI                     | 15        | 0.21%   |
| Dixonsxp                | 14        | 0.19%   |
| TUXEDO                  | 13        | 0.18%   |
| Supermicro              | 11        | 0.15%   |
| Clevo                   | 11        | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Valve Jupiter                      | 82        | 1.13%   |
| Unknown                            | 81        | 1.12%   |
| ASUS All Series                    | 75        | 1.04%   |
| Dell OptiPlex 7010                 | 31        | 0.43%   |
| MSI MS-7C02                        | 29        | 0.4%    |
| HP Pavilion g6                     | 25        | 0.35%   |
| RPi Raspberry Pi                   | 23        | 0.32%   |
| MSI MS-7C37                        | 22        | 0.3%    |
| Dell OptiPlex 755                  | 21        | 0.29%   |
| HP Notebook                        | 20        | 0.28%   |
| ASUS TUF Gaming X570-PLUS          | 20        | 0.28%   |
| ASUS M5A78L-M/USB3                 | 20        | 0.28%   |
| HP Pavilion 15                     | 19        | 0.26%   |
| Dell OptiPlex 780                  | 19        | 0.26%   |
| ASUS ROG STRIX B450-F GAMING       | 19        | 0.26%   |
| Dell OptiPlex 790                  | 17        | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 16        | 0.22%   |
| HP Pavilion Notebook               | 16        | 0.22%   |
| Dell XPS 15 7590                   | 16        | 0.22%   |
| Gigabyte 970A-DS3P                 | 15        | 0.21%   |
| Dell Inspiron 1545                 | 15        | 0.21%   |
| Dell XPS 15 9560                   | 14        | 0.19%   |
| Dell XPS 13 9380                   | 14        | 0.19%   |
| Gigabyte X570 AORUS ELITE          | 13        | 0.18%   |
| Dell XPS 13 9370                   | 13        | 0.18%   |
| ASUS PRIME A320M-K                 | 13        | 0.18%   |
| MSI MS-7C91                        | 12        | 0.17%   |
| Gigabyte GA-78LMT-USB3             | 12        | 0.17%   |
| Dell XPS 15 9570                   | 12        | 0.17%   |
| Dell XPS 13 9360                   | 12        | 0.17%   |
| Dell OptiPlex 3020                 | 12        | 0.17%   |
| Dell Latitude E6400                | 12        | 0.17%   |
| ASUS ROG STRIX B550-F GAMING       | 12        | 0.17%   |
| Toshiba Satellite C660             | 11        | 0.15%   |
| Microsoft Surface Pro 4            | 11        | 0.15%   |
| Lenovo V145-15AST 81MT             | 11        | 0.15%   |
| HP ProLiant MicroServer            | 11        | 0.15%   |
| Dell XPS 13 7390                   | 11        | 0.15%   |
| Dell Latitude E6410                | 11        | 0.15%   |
| MSI MS-7B85                        | 10        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 416       | 5.75%   |
| Dell Latitude          | 259       | 3.58%   |
| Acer Aspire            | 247       | 3.41%   |
| Dell Inspiron          | 235       | 3.25%   |
| Dell OptiPlex          | 198       | 2.74%   |
| Dell XPS               | 186       | 2.57%   |
| ASUS ROG               | 162       | 2.24%   |
| HP Pavilion            | 156       | 2.16%   |
| Toshiba Satellite      | 146       | 2.02%   |
| Lenovo IdeaPad         | 137       | 1.89%   |
| ASUS PRIME             | 127       | 1.76%   |
| HP EliteBook           | 110       | 1.52%   |
| Dell Precision         | 100       | 1.38%   |
| HP Compaq              | 95        | 1.31%   |
| Valve Jupiter          | 82        | 1.13%   |
| Unknown                | 81        | 1.12%   |
| ASUS All               | 75        | 1.04%   |
| RPi Raspberry          | 74        | 1.02%   |
| Lenovo ThinkCentre     | 69        | 0.95%   |
| HP Laptop              | 65        | 0.9%    |
| HP ProBook             | 62        | 0.86%   |
| ASUS TUF               | 60        | 0.83%   |
| ASUS VivoBook          | 55        | 0.76%   |
| HP ENVY                | 54        | 0.75%   |
| Lenovo Yoga            | 50        | 0.69%   |
| Dell Vostro            | 47        | 0.65%   |
| Microsoft Surface      | 44        | 0.61%   |
| Gigabyte X570          | 36        | 0.5%    |
| HP ProLiant            | 35        | 0.48%   |
| HP EliteDesk           | 30        | 0.41%   |
| ASUS M5A78L-M          | 30        | 0.41%   |
| MSI MS-7C02            | 29        | 0.4%    |
| HP Stream              | 28        | 0.39%   |
| ASUS ZenBook           | 28        | 0.39%   |
| Gigabyte GA-78LMT-USB3 | 27        | 0.37%   |
| Lenovo Legion          | 26        | 0.36%   |
| HP Spectre             | 26        | 0.36%   |
| Acer Swift             | 25        | 0.35%   |
| MSI MS-7C37            | 22        | 0.3%    |
| Lenovo ThinkBook       | 21        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 700       | 9.67%   |
| 2019    | 629       | 8.69%   |
| 2020    | 591       | 8.17%   |
| 2012    | 567       | 7.84%   |
| 2013    | 507       | 7.01%   |
| 2017    | 482       | 6.66%   |
| 2011    | 477       | 6.59%   |
| 2014    | 457       | 6.32%   |
| 2021    | 426       | 5.89%   |
| 2015    | 386       | 5.33%   |
| 2010    | 384       | 5.31%   |
| 2016    | 369       | 5.1%    |
| 2009    | 292       | 4.04%   |
| 2008    | 279       | 3.86%   |
| 2022    | 275       | 3.8%    |
| 2007    | 191       | 2.64%   |
| 2006    | 83        | 1.15%   |
| Unknown | 75        | 1.04%   |
| 2023    | 28        | 0.39%   |
| 2005    | 26        | 0.36%   |
| 2004    | 6         | 0.08%   |
| 2003    | 3         | 0.04%   |
| 2002    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3676      | 50.8%   |
| Desktop        | 2892      | 39.97%  |
| Convertible    | 157       | 2.17%   |
| Mini pc        | 145       | 2%      |
| All in one     | 122       | 1.69%   |
| Tablet         | 95        | 1.31%   |
| System on chip | 85        | 1.17%   |
| Server         | 59        | 0.82%   |
| Phone          | 4         | 0.06%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6722      | 92.16%  |
| Enabled  | 572       | 7.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7171      | 99.1%   |
| Yes  | 65        | 0.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1633      | 22.15%  |
| 16.01-24.0      | 1579      | 21.42%  |
| 8.01-16.0       | 1278      | 17.33%  |
| 3.01-4.0        | 1257      | 17.05%  |
| 32.01-64.0      | 786       | 10.66%  |
| 1.01-2.0        | 312       | 4.23%   |
| 64.01-256.0     | 209       | 2.83%   |
| 2.01-3.0        | 128       | 1.74%   |
| 24.01-32.0      | 114       | 1.55%   |
| 0.51-1.0        | 59        | 0.8%    |
| More than 256.0 | 12        | 0.16%   |
| 0.01-0.5        | 6         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2973      | 36.62%  |
| 2.01-3.0    | 2011      | 24.77%  |
| 4.01-8.0    | 1113      | 13.71%  |
| 3.01-4.0    | 993       | 12.23%  |
| 0.51-1.0    | 505       | 6.22%   |
| 8.01-16.0   | 317       | 3.9%    |
| 0.01-0.5    | 112       | 1.38%   |
| 16.01-24.0  | 48        | 0.59%   |
| 24.01-32.0  | 20        | 0.25%   |
| 32.01-64.0  | 18        | 0.22%   |
| 64.01-256.0 | 5         | 0.06%   |
| Unknown     | 4         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4219      | 56.28%  |
| 2       | 1865      | 24.88%  |
| 3       | 613       | 8.18%   |
| 4       | 337       | 4.5%    |
| 5       | 187       | 2.49%   |
| 6       | 94        | 1.25%   |
| 0       | 76        | 1.01%   |
| 7       | 41        | 0.55%   |
| 8       | 16        | 0.21%   |
| 9       | 14        | 0.19%   |
| Unknown | 8         | 0.11%   |
| 11      | 7         | 0.09%   |
| 10      | 6         | 0.08%   |
| 12      | 5         | 0.07%   |
| 13      | 3         | 0.04%   |
| 29      | 1         | 0.01%   |
| 25      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4366      | 59.72%  |
| Yes       | 2945      | 40.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6083      | 83.9%   |
| No        | 1167      | 16.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5527      | 75.7%   |
| No        | 1774      | 24.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4265      | 58.18%  |
| No        | 3066      | 41.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 7236      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 473       | 5.91%   |
| Manchester          | 176       | 2.2%    |
| Birmingham          | 134       | 1.68%   |
| Bristol             | 129       | 1.61%   |
| Glasgow             | 114       | 1.43%   |
| Edinburgh           | 109       | 1.36%   |
| Nottingham          | 101       | 1.26%   |
| Sheffield           | 98        | 1.23%   |
| Liverpool           | 95        | 1.19%   |
| Leeds               | 93        | 1.16%   |
| Reading             | 72        | 0.9%    |
| Islington           | 72        | 0.9%    |
| Norwich             | 63        | 0.79%   |
| Cambridge           | 63        | 0.79%   |
| Southampton         | 53        | 0.66%   |
| Croydon             | 52        | 0.65%   |
| Milton Keynes       | 51        | 0.64%   |
| Leicester           | 51        | 0.64%   |
| Derby               | 50        | 0.63%   |
| Coventry            | 48        | 0.6%    |
| Cardiff             | 46        | 0.58%   |
| Bradford            | 45        | 0.56%   |
| Newcastle upon Tyne | 43        | 0.54%   |
| York                | 42        | 0.53%   |
| Oxford              | 41        | 0.51%   |
| Hackney             | 40        | 0.5%    |
| Gloucester          | 40        | 0.5%    |
| Aberdeen            | 40        | 0.5%    |
| Brighton            | 39        | 0.49%   |
| Swindon             | 38        | 0.48%   |
| Plymouth            | 37        | 0.46%   |
| Wolverhampton       | 36        | 0.45%   |
| Bolton              | 36        | 0.45%   |
| Wigan               | 34        | 0.43%   |
| Sunderland          | 33        | 0.41%   |
| Walsall             | 32        | 0.4%    |
| Stoke-on-Trent      | 31        | 0.39%   |
| Kensington          | 31        | 0.39%   |
| Harrow              | 31        | 0.39%   |
| Clapham             | 30        | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1671      | 2632   | 15.23%  |
| Seagate                     | 1636      | 2747   | 14.91%  |
| WDC                         | 1509      | 2499   | 13.75%  |
| Toshiba                     | 730       | 1010   | 6.65%   |
| SanDisk                     | 650       | 877    | 5.92%   |
| Unknown                     | 600       | 815    | 5.47%   |
| Crucial                     | 585       | 836    | 5.33%   |
| Kingston                    | 461       | 625    | 4.2%    |
| Hitachi                     | 400       | 553    | 3.64%   |
| Intel                       | 229       | 307    | 2.09%   |
| SK hynix                    | 228       | 270    | 2.08%   |
| HGST                        | 166       | 243    | 1.51%   |
| Phison                      | 157       | 211    | 1.43%   |
| Micron Technology           | 121       | 144    | 1.1%    |
| China                       | 111       | 154    | 1.01%   |
| Apple                       | 110       | 152    | 1%      |
| A-DATA Technology           | 98        | 129    | 0.89%   |
| KIOXIA                      | 72        | 96     | 0.66%   |
| OCZ                         | 65        | 74     | 0.59%   |
| PNY                         | 63        | 79     | 0.57%   |
| Phison Electronics          | 62        | 91     | 0.56%   |
| Maxtor                      | 57        | 87     | 0.52%   |
| LITEON                      | 57        | 70     | 0.52%   |
| Silicon Motion              | 56        | 70     | 0.51%   |
| Transcend                   | 53        | 63     | 0.48%   |
| Micron/Crucial Technology   | 52        | 70     | 0.47%   |
| Corsair                     | 51        | 70     | 0.46%   |
| Unknown                     | 46        | 58     | 0.42%   |
| Fujitsu                     | 44        | 61     | 0.4%    |
| LITEONIT                    | 32        | 40     | 0.29%   |
| Kingston Technology Company | 30        | 32     | 0.27%   |
| Integral                    | 30        | 35     | 0.27%   |
| JMicron Technology          | 29        | 42     | 0.26%   |
| SABRENT                     | 27        | 31     | 0.25%   |
| Netac                       | 27        | 36     | 0.25%   |
| ASMT                        | 25        | 57     | 0.23%   |
| Patriot                     | 24        | 38     | 0.22%   |
| Gigabyte Technology         | 24        | 31     | 0.22%   |
| SPCC                        | 19        | 32     | 0.17%   |
| Drevo                       | 19        | 31     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 124       | 1%      |
| Samsung SSD 850 EVO 250GB                           | 93        | 0.75%   |
| Seagate ST3500312CS 500GB                           | 92        | 0.75%   |
| Kingston SA400S37240G 240GB SSD                     | 86        | 0.7%    |
| Samsung SSD 850 EVO 500GB                           | 80        | 0.65%   |
| Crucial CT1000MX500SSD1 1TB                         | 79        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB                      | 78        | 0.63%   |
| Unknown MMC Card  64GB                              | 75        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 75        | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB                      | 74        | 0.6%    |
| Crucial CT500MX500SSD1 500GB                        | 73        | 0.59%   |
| Samsung SSD 860 EVO 500GB                           | 68        | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB                      | 66        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                     | 66        | 0.53%   |
| Samsung NVMe SSD Drive 500GB                        | 63        | 0.51%   |
| Seagate ST500DM002-1BD142 500GB                     | 61        | 0.49%   |
| Unknown MMC Card  128GB                             | 60        | 0.49%   |
| Toshiba MQ01ABD100 1TB                              | 60        | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB                        | 60        | 0.49%   |
| Samsung SSD 860 EVO 1TB                             | 59        | 0.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 59        | 0.48%   |
| Samsung NVMe SSD Drive 512GB                        | 54        | 0.44%   |
| Crucial CT240BX500SSD1 240GB                        | 51        | 0.41%   |
| Samsung NVMe SSD Drive 1TB                          | 50        | 0.4%    |
| Samsung NVMe SSD Drive 256GB                        | 49        | 0.4%    |
| Unknown                                             | 46        | 0.37%   |
| Crucial CT250MX500SSD1 250GB                        | 44        | 0.36%   |
| Unknown SD/MMC/MS PRO 250GB                         | 43        | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB                      | 43        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 42        | 0.34%   |
| Seagate Expansion 1TB                               | 41        | 0.33%   |
| Samsung SSD 840 EVO 250GB                           | 41        | 0.33%   |
| SanDisk NVMe SSD Drive 1TB                          | 40        | 0.32%   |
| Toshiba DT01ACA100 1TB                              | 38        | 0.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 38        | 0.31%   |
| Unknown MMC Card  16GB                              | 37        | 0.3%    |
| Seagate ST2000DM001-1ER164 2TB                      | 37        | 0.3%    |
| HGST HTS721010A9E630 1TB                            | 37        | 0.3%    |
| Toshiba MQ01ABF050 500GB                            | 36        | 0.29%   |
| Seagate ST1000DM003-1ER162 1TB                      | 36        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1585      | 2637   | 36.35%  |
| WDC                 | 1175      | 2005   | 26.95%  |
| Toshiba             | 540       | 747    | 12.39%  |
| Hitachi             | 399       | 551    | 9.15%   |
| Samsung Electronics | 218       | 308    | 5%      |
| HGST                | 164       | 240    | 3.76%   |
| Unknown             | 50        | 67     | 1.15%   |
| Apple               | 48        | 59     | 1.1%    |
| Maxtor              | 47        | 76     | 1.08%   |
| Fujitsu             | 44        | 61     | 1.01%   |
| Hewlett-Packard     | 15        | 50     | 0.34%   |
| ASMT                | 12        | 41     | 0.28%   |
| USB3.0              | 9         | 14     | 0.21%   |
| ASMedia             | 7         | 13     | 0.16%   |
| SSK                 | 6         | 7      | 0.14%   |
| WD MediaMax         | 4         | 4      | 0.09%   |
| LaCie               | 4         | 4      | 0.09%   |
| HPE                 | 4         | 7      | 0.09%   |
| ASMT109x            | 3         | 5      | 0.07%   |
| USB                 | 2         | 2      | 0.05%   |
| RSH-339             | 2         | 2      | 0.05%   |
| KESU                | 2         | 6      | 0.05%   |
| JMicron Technology  | 2         | 5      | 0.05%   |
| IBM/Hitachi         | 2         | 2      | 0.05%   |
| ExcelStor           | 2         | 4      | 0.05%   |
| SAGE                | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| NETAPP              | 1         | 4      | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| LIO-ORG             | 1         | 8      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| External            | 1         | 1      | 0.02%   |
| Advantech           | 1         | 1      | 0.02%   |
| Unknown             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 829       | 1249   | 22.59%  |
| Crucial             | 534       | 775    | 14.55%  |
| SanDisk             | 431       | 556    | 11.74%  |
| Kingston            | 388       | 524    | 10.57%  |
| WDC                 | 204       | 287    | 5.56%   |
| China               | 107       | 147    | 2.92%   |
| Intel               | 91        | 104    | 2.48%   |
| A-DATA Technology   | 76        | 98     | 2.07%   |
| OCZ                 | 65        | 74     | 1.77%   |
| Toshiba             | 62        | 79     | 1.69%   |
| Micron Technology   | 61        | 72     | 1.66%   |
| PNY                 | 60        | 72     | 1.63%   |
| SK hynix            | 57        | 70     | 1.55%   |
| LITEON              | 55        | 68     | 1.5%    |
| Transcend           | 49        | 59     | 1.34%   |
| Apple               | 48        | 62     | 1.31%   |
| LITEONIT            | 32        | 40     | 0.87%   |
| Integral            | 30        | 35     | 0.82%   |
| Corsair             | 30        | 43     | 0.82%   |
| Netac               | 26        | 33     | 0.71%   |
| Patriot             | 24        | 38     | 0.65%   |
| Seagate             | 22        | 26     | 0.6%    |
| Drevo               | 19        | 31     | 0.52%   |
| Gigabyte Technology | 18        | 23     | 0.49%   |
| SPCC                | 15        | 28     | 0.41%   |
| Unknown             | 14        | 19     | 0.38%   |
| Team                | 14        | 15     | 0.38%   |
| KIOXIA-EXCERIA      | 14        | 18     | 0.38%   |
| Lexar               | 13        | 15     | 0.35%   |
| TO Exter            | 12        | 14     | 0.33%   |
| ASMT                | 12        | 15     | 0.33%   |
| Vaseky              | 11        | 16     | 0.3%    |
| TCSUNBOW            | 11        | 17     | 0.3%    |
| ORTIAL              | 11        | 11     | 0.3%    |
| Maxtor              | 10        | 11     | 0.27%   |
| Unknown             | 8         | 9      | 0.22%   |
| Plextor             | 7         | 10     | 0.19%   |
| KingDian            | 7         | 10     | 0.19%   |
| Teclast             | 6         | 6      | 0.16%   |
| Star                | 6         | 7      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3546      | 6941   | 36.93%  |
| SSD     | 3103      | 5022   | 32.31%  |
| NVMe    | 2247      | 3295   | 23.4%   |
| MMC     | 554       | 736    | 5.77%   |
| Unknown | 153       | 231    | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5385      | 11397  | 62.28%  |
| NVMe | 2219      | 3231   | 25.67%  |
| MMC  | 554       | 736    | 6.41%   |
| SAS  | 488       | 861    | 5.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 4006      | 6591   | 55.83%  |
| 0.51-1.0        | 1936      | 3022   | 26.98%  |
| 1.01-2.0        | 654       | 1131   | 9.11%   |
| 3.01-4.0        | 202       | 429    | 2.82%   |
| 4.01-10.0       | 179       | 406    | 2.49%   |
| 2.01-3.0        | 171       | 314    | 2.38%   |
| 10.01-20.0      | 25        | 68     | 0.35%   |
| More than 100.0 | 1         | 1      | 0.01%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2048      | 26.52%  |
| 251-500        | 1522      | 19.71%  |
| 501-1000       | 1164      | 15.07%  |
| 1001-2000      | 611       | 7.91%   |
| 1-20           | 551       | 7.13%   |
| 51-100         | 497       | 6.44%   |
| More than 3000 | 495       | 6.41%   |
| 21-50          | 359       | 4.65%   |
| 2001-3000      | 243       | 3.15%   |
| Unknown        | 233       | 3.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3166      | 39.54%  |
| 21-50          | 1304      | 16.29%  |
| 101-250        | 936       | 11.69%  |
| 51-100         | 838       | 10.47%  |
| 251-500        | 588       | 7.34%   |
| 501-1000       | 402       | 5.02%   |
| 1001-2000      | 267       | 3.33%   |
| Unknown        | 233       | 2.91%   |
| More than 3000 | 177       | 2.21%   |
| 2001-3000      | 94        | 1.17%   |
| 0              | 2         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 8         | 12     | 1.43%   |
| Seagate ST9500325AS 500GB                | 7         | 11     | 1.25%   |
| Seagate ST500DM002-1BD142 500GB          | 6         | 6      | 1.07%   |
| Seagate ST3500418AS 500GB                | 6         | 6      | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB           | 6         | 6      | 1.07%   |
| HGST HTS725050A7E630 500GB               | 6         | 9      | 1.07%   |
| Seagate ST500LM021-1KJ152 500GB          | 5         | 5      | 0.89%   |
| Seagate ST3500312CS 500GB                | 5         | 7      | 0.89%   |
| Samsung Electronics HD103UJ 1TB          | 5         | 7      | 0.89%   |
| Hitachi HTS547575A9E384 752GB            | 5         | 7      | 0.89%   |
| Seagate ST2000DM001-1CH164 2TB           | 4         | 5      | 0.72%   |
| Samsung Electronics SSD 960 EVO 250GB    | 4         | 5      | 0.72%   |
| Samsung Electronics HD103SJ 1TB          | 4         | 5      | 0.72%   |
| Hitachi HTS545025B9A300 250GB            | 4         | 4      | 0.72%   |
| Hitachi HDT721010SLA360 1TB              | 4         | 5      | 0.72%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 0.72%   |
| WDC WD5000BEVT-75A0RT0 500GB             | 3         | 5      | 0.54%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 3         | 10     | 0.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 3         | 3      | 0.54%   |
| Toshiba MK1656GSY 160GB                  | 3         | 3      | 0.54%   |
| Toshiba DT01ACA050 500GB                 | 3         | 4      | 0.54%   |
| Seagate ST3500620AS 500GB                | 3         | 4      | 0.54%   |
| Seagate ST2000DM006-2DM164 2TB           | 3         | 3      | 0.54%   |
| Seagate ST1000LM014-SSHD-8GB             | 3         | 4      | 0.54%   |
| SanDisk SSD PLUS 480GB                   | 3         | 3      | 0.54%   |
| Samsung Electronics SSD 840 Series 120GB | 3         | 3      | 0.54%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 3      | 0.54%   |
| Intel SSDPEKKW512G7 512GB                | 3         | 5      | 0.54%   |
| Hitachi HUA723030ALA640 3TB              | 3         | 4      | 0.54%   |
| Hitachi HTS542512K9SA00 120GB            | 3         | 3      | 0.54%   |
| Hitachi HDS721010CLA332 1TB              | 3         | 3      | 0.54%   |
| Hitachi HDP725050GLA360 500GB            | 3         | 3      | 0.54%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 0.54%   |
| Crucial CT525MX300SSD4 528GB             | 3         | 3      | 0.54%   |
| Crucial CT480M500SSD1 480GB              | 3         | 3      | 0.54%   |
| WDC WD800JD-00HKA0 80GB                  | 2         | 2      | 0.36%   |
| WDC WD6400AAKS-22A7B2 640GB              | 2         | 2      | 0.36%   |
| WDC WD6400AAKS-22A7B0 640GB              | 2         | 2      | 0.36%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 2         | 3      | 0.36%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 2         | 2      | 0.36%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 135       | 168    | 25.09%  |
| WDC                 | 113       | 178    | 21%     |
| Hitachi             | 64        | 88     | 11.9%   |
| Samsung Electronics | 47        | 61     | 8.74%   |
| Toshiba             | 35        | 41     | 6.51%   |
| Crucial             | 27        | 33     | 5.02%   |
| HGST                | 17        | 20     | 3.16%   |
| Intel               | 16        | 24     | 2.97%   |
| SanDisk             | 13        | 17     | 2.42%   |
| Kingston            | 9         | 11     | 1.67%   |
| SK hynix            | 6         | 6      | 1.12%   |
| Micron Technology   | 5         | 5      | 0.93%   |
| LITEON              | 5         | 5      | 0.93%   |
| Fujitsu             | 5         | 5      | 0.93%   |
| A-DATA Technology   | 5         | 5      | 0.93%   |
| Maxtor              | 4         | 5      | 0.74%   |
| Drevo               | 4         | 10     | 0.74%   |
| Hewlett-Packard     | 3         | 3      | 0.56%   |
| Corsair             | 3         | 7      | 0.56%   |
| WD MediaMax         | 2         | 2      | 0.37%   |
| Unknown             | 2         | 2      | 0.37%   |
| OCZ                 | 2         | 2      | 0.37%   |
| China               | 2         | 2      | 0.37%   |
| BAITITON            | 2         | 5      | 0.37%   |
| Zheino              | 1         | 2      | 0.19%   |
| VENO                | 1         | 1      | 0.19%   |
| Team                | 1         | 1      | 0.19%   |
| Mushkin             | 1         | 1      | 0.19%   |
| KingSpec            | 1         | 1      | 0.19%   |
| faspeed             | 1         | 1      | 0.19%   |
| BIWIN               | 1         | 1      | 0.19%   |
| Apple               | 1         | 2      | 0.19%   |
| Apacer              | 1         | 1      | 0.19%   |
| AGI                 | 1         | 1      | 0.19%   |
| 2-Power             | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 135       | 168    | 34.09%  |
| WDC                 | 109       | 174    | 27.53%  |
| Hitachi             | 64        | 88     | 16.16%  |
| Toshiba             | 34        | 40     | 8.59%   |
| Samsung Electronics | 20        | 27     | 5.05%   |
| HGST                | 17        | 20     | 4.29%   |
| Fujitsu             | 5         | 5      | 1.26%   |
| Maxtor              | 4         | 5      | 1.01%   |
| Hewlett-Packard     | 3         | 3      | 0.76%   |
| WD MediaMax         | 2         | 2      | 0.51%   |
| Unknown             | 2         | 2      | 0.51%   |
| Apple               | 1         | 2      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 357       | 536    | 71.69%  |
| SSD  | 118       | 152    | 23.69%  |
| NVMe | 23        | 31     | 4.62%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB      | 2         | 3      | 22.22%  |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 11.11%  |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 11.11%  |
| Seagate ST3160815AS 160GB             | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 980 1TB       | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 11.11%  |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 11.11%  |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 5      | 44.44%  |
| Samsung Electronics | 3         | 4      | 33.33%  |
| Seagate             | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4840      | 10558  | 61.92%  |
| Works    | 2486      | 4937   | 31.8%   |
| Malfunc  | 483       | 719    | 6.18%   |
| Failed   | 8         | 11     | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4540      | 49.75%  |
| AMD                              | 1562      | 17.12%  |
| Samsung Electronics              | 844       | 9.25%   |
| SanDisk                          | 368       | 4.03%   |
| Phison Electronics               | 246       | 2.7%    |
| ASMedia Technology               | 184       | 2.02%   |
| SK hynix                         | 166       | 1.82%   |
| Nvidia                           | 150       | 1.64%   |
| Toshiba America Info Systems     | 146       | 1.6%    |
| Marvell Technology Group         | 118       | 1.29%   |
| Kingston Technology Company      | 103       | 1.13%   |
| Micron/Crucial Technology        | 100       | 1.1%    |
| JMicron Technology               | 89        | 0.98%   |
| KIOXIA                           | 67        | 0.73%   |
| Silicon Motion                   | 64        | 0.7%    |
| Micron Technology                | 63        | 0.69%   |
| ADATA Technology                 | 43        | 0.47%   |
| LSI Logic / Symbios Logic        | 36        | 0.39%   |
| Broadcom / LSI                   | 25        | 0.27%   |
| VIA Technologies                 | 21        | 0.23%   |
| Seagate Technology               | 21        | 0.23%   |
| Silicon Image                    | 19        | 0.21%   |
| Apple                            | 18        | 0.2%    |
| Silicon Integrated Systems [SiS] | 15        | 0.16%   |
| Hewlett-Packard                  | 15        | 0.16%   |
| O2 Micro                         | 12        | 0.13%   |
| Lenovo                           | 11        | 0.12%   |
| Solid State Storage Technology   | 10        | 0.11%   |
| Adaptec                          | 10        | 0.11%   |
| Union Memory (Shenzhen)          | 9         | 0.1%    |
| Realtek Semiconductor            | 9         | 0.1%    |
| Shenzhen Longsys Electronics     | 6         | 0.07%   |
| Lite-On Technology               | 6         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.05%   |
| Yangtze Memory Technologies      | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| Solidigm                         | 2         | 0.02%   |
| Netac Technology                 | 2         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1056      | 9.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 433       | 4.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 306       | 2.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 292       | 2.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 277       | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 247       | 2.31%   |
| AMD 400 Series Chipset SATA Controller                                         | 221       | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 184       | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 183       | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 181       | 1.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 176       | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 166       | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 164       | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 146       | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller                            | 144       | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 138       | 1.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 138       | 1.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 131       | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 127       | 1.19%   |
| Intel SATA Controller [RAID mode]                                              | 125       | 1.17%   |
| Samsung NVMe SSD Controller 980                                                | 122       | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 118       | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 118       | 1.11%   |
| Phison E12 NVMe Controller                                                     | 117       | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 113       | 1.06%   |
| AMD 500 Series Chipset SATA Controller                                         | 107       | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 106       | 0.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 106       | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 101       | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 95        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 91        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 89        | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 86        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 84        | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 79        | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 79        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 74        | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 73        | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 66        | 0.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 66        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5148      | 56.02%  |
| NVMe | 2239      | 24.36%  |
| IDE  | 1115      | 12.13%  |
| RAID | 620       | 6.75%   |
| SAS  | 41        | 0.45%   |
| SCSI | 27        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5251      | 72.57%  |
| AMD                   | 1892      | 26.15%  |
| ARM                   | 90        | 1.24%   |
| QUALCOMM              | 1         | 0.01%   |
| Marvell Semiconductor | 1         | 0.01%   |
| CentaurHauls          | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Custom APU 0405                     | 82        | 1.13%   |
| AMD Ryzen 5 3600 6-Core Processor       | 78        | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 68        | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 64        | 0.88%   |
| ARM Processor                           | 64        | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 56        | 0.77%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 52        | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 50        | 0.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 49        | 0.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 48        | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 48        | 0.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 46        | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 46        | 0.63%   |
| AMD FX-8350 Eight-Core Processor        | 44        | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 41        | 0.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 41        | 0.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 40        | 0.55%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 40        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 39        | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 39        | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 39        | 0.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 38        | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 38        | 0.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 38        | 0.52%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 37        | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 37        | 0.51%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 37        | 0.51%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 36        | 0.5%    |
| Intel Core i7-2600 CPU @ 3.40GHz        | 36        | 0.5%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 36        | 0.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz       | 35        | 0.48%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 33        | 0.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 31        | 0.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 31        | 0.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 31        | 0.43%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 31        | 0.43%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 31        | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 30        | 0.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 29        | 0.4%    |
| Intel Core i7-4790 CPU @ 3.60GHz        | 29        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1445      | 19.93%  |
| Intel Core i7           | 1351      | 18.63%  |
| Other                   | 518       | 7.14%   |
| Intel Core i3           | 455       | 6.27%   |
| AMD Ryzen 5             | 382       | 5.27%   |
| Intel Celeron           | 364       | 5.02%   |
| AMD Ryzen 7             | 325       | 4.48%   |
| Intel Core 2 Duo        | 319       | 4.4%    |
| Intel Xeon              | 205       | 2.83%   |
| Intel Pentium           | 189       | 2.61%   |
| AMD FX                  | 153       | 2.11%   |
| AMD Ryzen 9             | 149       | 2.05%   |
| Intel Atom              | 128       | 1.77%   |
| AMD A6                  | 84        | 1.16%   |
| AMD Ryzen 3             | 81        | 1.12%   |
| AMD A8                  | 80        | 1.1%    |
| Intel Pentium Dual-Core | 76        | 1.05%   |
| Intel Core 2 Quad       | 67        | 0.92%   |
| AMD A10                 | 57        | 0.79%   |
| Intel Core 2            | 55        | 0.76%   |
| Intel Core i9           | 54        | 0.74%   |
| Intel Pentium Dual      | 43        | 0.59%   |
| AMD A4                  | 42        | 0.58%   |
| AMD Athlon II X2        | 41        | 0.57%   |
| AMD Phenom II X4        | 34        | 0.47%   |
| Intel Genuine           | 28        | 0.39%   |
| AMD Ryzen Threadripper  | 28        | 0.39%   |
| ARM BCM                 | 25        | 0.34%   |
| AMD Athlon 64 X2        | 25        | 0.34%   |
| AMD Athlon              | 25        | 0.34%   |
| AMD E1                  | 24        | 0.33%   |
| Intel Pentium 4         | 23        | 0.32%   |
| AMD E                   | 22        | 0.3%    |
| Intel Celeron Dual-Core | 20        | 0.28%   |
| Intel Pentium Silver    | 17        | 0.23%   |
| Intel Pentium D         | 17        | 0.23%   |
| AMD Athlon II X4        | 17        | 0.23%   |
| AMD Ryzen 7 PRO         | 16        | 0.22%   |
| Intel Celeron M         | 14        | 0.19%   |
| AMD Phenom II X6        | 14        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2920      | 40.27%  |
| 4       | 2542      | 35.06%  |
| 6       | 681       | 9.39%   |
| 8       | 537       | 7.41%   |
| 1       | 185       | 2.55%   |
| 12      | 136       | 1.88%   |
| 16      | 85        | 1.17%   |
| 3       | 62        | 0.86%   |
| 10      | 37        | 0.51%   |
| 14      | 29        | 0.4%    |
| 24      | 15        | 0.21%   |
| 32      | 6         | 0.08%   |
| 20      | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 64      | 2         | 0.03%   |
| 40      | 2         | 0.03%   |
| 28      | 2         | 0.03%   |
| 44      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7137      | 98.63%  |
| 2       | 91        | 1.26%   |
| 4       | 3         | 0.04%   |
| Unknown | 3         | 0.04%   |
| 3       | 2         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4670      | 64.47%  |
| 1       | 2571      | 35.49%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7009      | 96.5%   |
| Unknown        | 176       | 2.42%   |
| 32-bit         | 73        | 1.01%   |
| 64-bit         | 5         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1969      | 26.14%  |
| 0x306a9    | 375       | 4.98%   |
| 0x206a7    | 368       | 4.89%   |
| 0x306c3    | 310       | 4.12%   |
| 0x1067a    | 268       | 3.56%   |
| 0x906ea    | 164       | 2.18%   |
| 0x806ea    | 144       | 1.91%   |
| 0x506e3    | 144       | 1.91%   |
| 0x08701021 | 137       | 1.82%   |
| 0x406e3    | 130       | 1.73%   |
| 0x806ec    | 129       | 1.71%   |
| 0x806e9    | 129       | 1.71%   |
| 0x40651    | 124       | 1.65%   |
| 0x20655    | 116       | 1.54%   |
| 0x806c1    | 114       | 1.51%   |
| 0x906e9    | 110       | 1.46%   |
| 0x306d4    | 110       | 1.46%   |
| 0x6fd      | 95        | 1.26%   |
| 0x406c4    | 90        | 1.19%   |
| 0x010000c8 | 82        | 1.09%   |
| 0x06000852 | 79        | 1.05%   |
| 0x30678    | 73        | 0.97%   |
| 0x0800820d | 68        | 0.9%    |
| 0x06001119 | 68        | 0.9%    |
| 0x10676    | 64        | 0.85%   |
| 0x08108109 | 60        | 0.8%    |
| 0x08701013 | 55        | 0.73%   |
| 0x506c9    | 54        | 0.72%   |
| 0x6fb      | 53        | 0.7%    |
| 0xa0652    | 51        | 0.68%   |
| 0x706e5    | 50        | 0.66%   |
| 0x20652    | 48        | 0.64%   |
| 0x0a50000c | 47        | 0.62%   |
| 0x06006705 | 46        | 0.61%   |
| 0x906ed    | 45        | 0.6%    |
| 0x406c3    | 44        | 0.58%   |
| 0x08108102 | 40        | 0.53%   |
| 0x08600106 | 39        | 0.52%   |
| 0x706a1    | 38        | 0.5%    |
| 0x206c2    | 37        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1032      | 14.22%  |
| Haswell          | 604       | 8.33%   |
| SandyBridge      | 497       | 6.85%   |
| IvyBridge        | 489       | 6.74%   |
| Penryn           | 396       | 5.46%   |
| Skylake          | 375       | 5.17%   |
| Zen 2            | 356       | 4.91%   |
| Unknown          | 317       | 4.37%   |
| Silvermont       | 268       | 3.69%   |
| Core             | 262       | 3.61%   |
| Westmere         | 250       | 3.45%   |
| Zen+             | 235       | 3.24%   |
| Piledriver       | 204       | 2.81%   |
| Zen 3            | 192       | 2.65%   |
| K10              | 179       | 2.47%   |
| TigerLake        | 164       | 2.26%   |
| Broadwell        | 163       | 2.25%   |
| Zen              | 156       | 2.15%   |
| CometLake        | 133       | 1.83%   |
| Excavator        | 114       | 1.57%   |
| Icelake          | 108       | 1.49%   |
| Goldmont plus    | 91        | 1.25%   |
| Nehalem          | 79        | 1.09%   |
| Alderlake Hybrid | 75        | 1.03%   |
| Goldmont         | 66        | 0.91%   |
| Puma             | 59        | 0.81%   |
| K8 Hammer        | 59        | 0.81%   |
| Steamroller      | 54        | 0.74%   |
| Bobcat           | 48        | 0.66%   |
| NetBurst         | 45        | 0.62%   |
| Bonnell          | 43        | 0.59%   |
| P6               | 39        | 0.54%   |
| Jaguar           | 29        | 0.4%    |
| Bulldozer        | 28        | 0.39%   |
| Tremont          | 16        | 0.22%   |
| K8 & K10 hybrid  | 13        | 0.18%   |
| K10 Llano        | 12        | 0.17%   |
| K6               | 4         | 0.06%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3990      | 48.82%  |
| Nvidia                                       | 2236      | 27.36%  |
| AMD                                          | 1863      | 22.79%  |
| Matrox Electronics Systems                   | 40        | 0.49%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.18%   |
| ASPEED Technology                            | 13        | 0.16%   |
| ATI Technologies                             | 8         | 0.1%    |
| VIA Technologies                             | 5         | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| Alliance Semiconductor                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 366       | 4.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 272       | 3.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 167       | 1.98%   |
| Intel UHD Graphics 620                                                                   | 165       | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 163       | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 159       | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 158       | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 152       | 1.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 152       | 1.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 146       | 1.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 144       | 1.7%    |
| Intel HD Graphics 620                                                                    | 137       | 1.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 129       | 1.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 129       | 1.53%   |
| Intel HD Graphics 5500                                                                   | 112       | 1.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 109       | 1.29%   |
| Intel HD Graphics 630                                                                    | 109       | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 108       | 1.28%   |
| Intel HD Graphics 530                                                                    | 103       | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 102       | 1.21%   |
| AMD Renoir                                                                               | 96        | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 93        | 1.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 93        | 1.1%    |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 82        | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 81        | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 77        | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 71        | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 63        | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 62        | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 62        | 0.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 60        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 59        | 0.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 57        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 56        | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 56        | 0.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 55        | 0.65%   |
| Intel HD Graphics 500                                                                    | 53        | 0.63%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 53        | 0.63%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 50        | 0.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 48        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 3102      | 42.45%  |
| 1 x AMD                              | 1581      | 21.63%  |
| 1 x Nvidia                           | 1429      | 19.55%  |
| Intel + Nvidia                       | 675       | 9.24%   |
| Intel + AMD                          | 108       | 1.48%   |
| Other                                | 103       | 1.41%   |
| AMD + Nvidia                         | 87        | 1.19%   |
| 2 x AMD                              | 84        | 1.15%   |
| 1 x Matrox                           | 35        | 0.48%   |
| 2 x Nvidia                           | 30        | 0.41%   |
| 2 x Intel                            | 20        | 0.27%   |
| 1 x SiS                              | 14        | 0.19%   |
| Nvidia + ASPEED                      | 7         | 0.1%    |
| 1 x ASPEED                           | 6         | 0.08%   |
| 1 x VIA                              | 5         | 0.07%   |
| Nvidia + Matrox                      | 4         | 0.05%   |
| Intel + AMD + 1 x Nvidia             | 4         | 0.05%   |
| 2 x AMD + 1 x Nvidia                 | 3         | 0.04%   |
| Intel + 2 x Nvidia                   | 2         | 0.03%   |
| 3 x AMD                              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.01%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.01%   |
| 1 x XGI                              | 1         | 0.01%   |
| 1 x Intel + 3 x Nvidia               | 1         | 0.01%   |
| Intel + 2 x AMD                      | 1         | 0.01%   |
| 1 x Huawei Technologies              | 1         | 0.01%   |
| AMD + SiS                            | 1         | 0.01%   |
| AMD + ASPEED                         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5716      | 77.47%  |
| Proprietary | 1296      | 17.57%  |
| Unknown     | 366       | 4.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4248      | 56.74%  |
| 0.01-0.5   | 836       | 11.17%  |
| 1.01-2.0   | 775       | 10.35%  |
| 0.51-1.0   | 503       | 6.72%   |
| 3.01-4.0   | 443       | 5.92%   |
| 7.01-8.0   | 337       | 4.5%    |
| 5.01-6.0   | 169       | 2.26%   |
| 8.01-16.0  | 116       | 1.55%   |
| 2.01-3.0   | 51        | 0.68%   |
| 16.01-24.0 | 6         | 0.08%   |
| 4.01-5.0   | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |
| 0          | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 898       | 11.79%  |
| AU Optronics            | 822       | 10.79%  |
| LG Display              | 656       | 8.61%   |
| Dell                    | 534       | 7.01%   |
| Chimei Innolux          | 509       | 6.68%   |
| BOE                     | 478       | 6.27%   |
| Acer                    | 331       | 4.34%   |
| Goldstar                | 256       | 3.36%   |
| Hewlett-Packard         | 250       | 3.28%   |
| AOC                     | 240       | 3.15%   |
| BenQ                    | 239       | 3.14%   |
| Sharp                   | 219       | 2.87%   |
| Apple                   | 169       | 2.22%   |
| Iiyama                  | 163       | 2.14%   |
| Lenovo                  | 141       | 1.85%   |
| Ancor Communications    | 140       | 1.84%   |
| Philips                 | 118       | 1.55%   |
| ViewSonic               | 84        | 1.1%    |
| Chi Mei Optoelectronics | 83        | 1.09%   |
| Sony                    | 79        | 1.04%   |
| Unknown                 | 67        | 0.88%   |
| ASUSTek Computer        | 67        | 0.88%   |
| HannStar                | 63        | 0.83%   |
| PANDA                   | 62        | 0.81%   |
| Panasonic               | 56        | 0.74%   |
| LG Philips              | 47        | 0.62%   |
| Toshiba                 | 46        | 0.6%    |
| Vestel Elektronik       | 44        | 0.58%   |
| LG Electronics          | 41        | 0.54%   |
| InfoVision              | 41        | 0.54%   |
| Valve                   | 40        | 0.53%   |
| NEC Computers           | 33        | 0.43%   |
| MSI                     | 30        | 0.39%   |
| Analogix                | 26        | 0.34%   |
| Gigabyte Technology     | 22        | 0.29%   |
| CSO                     | 20        | 0.26%   |
| OEM                     | 18        | 0.24%   |
| Hitachi                 | 18        | 0.24%   |
| Idek Iiyama             | 16        | 0.21%   |
| MiTAC                   | 15        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch | 43        | 0.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 42        | 0.53%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 38        | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 32        | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 32        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 30        | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 29        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 28        | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 28        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 27        | 0.34%   |
| Analogix ANX7530 U ANX7539 800x1280 60x50mm 3.1-inch                 | 26        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 22        | 0.28%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                      | 22        | 0.28%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                      | 21        | 0.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 20        | 0.25%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 18        | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 18        | 0.23%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                   | 18        | 0.23%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 17        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 17        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 17        | 0.22%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 16        | 0.2%    |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch         | 16        | 0.2%    |
| OEM 26_LCD_TV OEM3700 1920x1080                                      | 16        | 0.2%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 16        | 0.2%    |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                    | 16        | 0.2%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 15        | 0.19%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 15        | 0.19%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch        | 15        | 0.19%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 14        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 14        | 0.18%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 14        | 0.18%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 14        | 0.18%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch         | 14        | 0.18%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 13        | 0.16%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 13        | 0.16%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch         | 13        | 0.16%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 13        | 0.16%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 13        | 0.16%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 13        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3007      | 40.91%  |
| 1366x768 (WXGA)    | 1252      | 17.03%  |
| 3840x2160 (4K)     | 577       | 7.85%   |
| 2560x1440 (QHD)    | 394       | 5.36%   |
| 1280x1024 (SXGA)   | 246       | 3.35%   |
| 1280x800 (WXGA)    | 207       | 2.82%   |
| 1600x900 (HD+)     | 196       | 2.67%   |
| 1680x1050 (WSXGA+) | 190       | 2.59%   |
| 1440x900 (WXGA+)   | 181       | 2.46%   |
| 1920x1200 (WUXGA)  | 174       | 2.37%   |
| Unknown            | 110       | 1.5%    |
| 3440x1440          | 96        | 1.31%   |
| 800x1280           | 61        | 0.83%   |
| 1360x768           | 58        | 0.79%   |
| 2560x1080          | 57        | 0.78%   |
| 2560x1600          | 52        | 0.71%   |
| 3840x1080          | 50        | 0.68%   |
| 1920x540           | 49        | 0.67%   |
| 2880x1800          | 32        | 0.44%   |
| 3840x2400          | 31        | 0.42%   |
| 1024x768 (XGA)     | 31        | 0.42%   |
| 3200x1800 (QHD+)   | 24        | 0.33%   |
| 2736x1824          | 24        | 0.33%   |
| 1600x1200          | 23        | 0.31%   |
| 2160x1440          | 19        | 0.26%   |
| 1280x720 (HD)      | 19        | 0.26%   |
| 1024x600           | 18        | 0.24%   |
| 2288x1287          | 10        | 0.14%   |
| 1920x1280          | 9         | 0.12%   |
| 5120x1440          | 8         | 0.11%   |
| 5760x1080          | 7         | 0.1%    |
| 2256x1504          | 7         | 0.1%    |
| 3840x1200          | 6         | 0.08%   |
| 3072x1920          | 6         | 0.08%   |
| 7680x2160          | 5         | 0.07%   |
| 3200x1080          | 5         | 0.07%   |
| 2880x1920          | 5         | 0.07%   |
| 2560x1700          | 5         | 0.07%   |
| 1680x945           | 5         | 0.07%   |
| 5760x2160          | 4         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1706      | 22.52%  |
| 13      | 733       | 9.68%   |
| 27      | 597       | 7.88%   |
| 24      | 540       | 7.13%   |
| Unknown | 501       | 6.61%   |
| 23      | 462       | 6.1%    |
| 14      | 432       | 5.7%    |
| 21      | 423       | 5.58%   |
| 17      | 373       | 4.92%   |
| 12      | 221       | 2.92%   |
| 19      | 201       | 2.65%   |
| 31      | 164       | 2.16%   |
| 11      | 119       | 1.57%   |
| 84      | 117       | 1.54%   |
| 22      | 116       | 1.53%   |
| 34      | 114       | 1.5%    |
| 18      | 86        | 1.14%   |
| 20      | 78        | 1.03%   |
| 72      | 60        | 0.79%   |
| 26      | 43        | 0.57%   |
| 16      | 42        | 0.55%   |
| 25      | 40        | 0.53%   |
| 32      | 39        | 0.51%   |
| 10      | 38        | 0.5%    |
| 7       | 38        | 0.5%    |
| 54      | 30        | 0.4%    |
| 3       | 26        | 0.34%   |
| 48      | 19        | 0.25%   |
| 33      | 19        | 0.25%   |
| 40      | 18        | 0.24%   |
| 28      | 18        | 0.24%   |
| 65      | 16        | 0.21%   |
| 39      | 16        | 0.21%   |
| 46      | 12        | 0.16%   |
| 60      | 11        | 0.15%   |
| 52      | 10        | 0.13%   |
| 35      | 10        | 0.13%   |
| 55      | 9         | 0.12%   |
| 43      | 8         | 0.11%   |
| 142     | 7         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2512      | 33.62%  |
| 501-600        | 1499      | 20.06%  |
| 201-300        | 827       | 11.07%  |
| 401-500        | 784       | 10.49%  |
| Unknown        | 501       | 6.71%   |
| 351-400        | 449       | 6.01%   |
| 601-700        | 271       | 3.63%   |
| 1501-2000      | 179       | 2.4%    |
| 701-800        | 177       | 2.37%   |
| 1001-1500      | 135       | 1.81%   |
| 1-100          | 61        | 0.82%   |
| 801-900        | 47        | 0.63%   |
| 901-1000       | 14        | 0.19%   |
| More than 2000 | 9         | 0.12%   |
| 101-200        | 6         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5018      | 72.12%  |
| 16/10   | 864       | 12.42%  |
| Unknown | 437       | 6.28%   |
| 5/4     | 228       | 3.28%   |
| 21/9    | 137       | 1.97%   |
| 3/2     | 96        | 1.38%   |
| 4/3     | 66        | 0.95%   |
| 0.67    | 38        | 0.55%   |
| 6/5     | 36        | 0.52%   |
| 32/9    | 22        | 0.32%   |
| 1.00    | 11        | 0.16%   |
| 3.20    | 2         | 0.03%   |
| 3.40    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1701      | 22.67%  |
| 201-250        | 1228      | 16.37%  |
| 81-90          | 782       | 10.42%  |
| 301-350        | 628       | 8.37%   |
| Unknown        | 501       | 6.68%   |
| 151-200        | 418       | 5.57%   |
| 71-80          | 397       | 5.29%   |
| 351-500        | 358       | 4.77%   |
| More than 1000 | 282       | 3.76%   |
| 121-130        | 214       | 2.85%   |
| 251-300        | 209       | 2.79%   |
| 61-70          | 194       | 2.59%   |
| 141-150        | 166       | 2.21%   |
| 51-60          | 124       | 1.65%   |
| 501-1000       | 94        | 1.25%   |
| 1-40           | 67        | 0.89%   |
| 131-140        | 48        | 0.64%   |
| 111-120        | 43        | 0.57%   |
| 41-50          | 34        | 0.45%   |
| 91-100         | 14        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2302      | 31.45%  |
| 101-120       | 1815      | 24.8%   |
| 121-160       | 1722      | 23.52%  |
| 161-240       | 534       | 7.3%    |
| Unknown       | 501       | 6.84%   |
| More than 240 | 251       | 3.43%   |
| 1-50          | 195       | 2.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5947      | 80.14%  |
| 2     | 988       | 13.31%  |
| 0     | 372       | 5.01%   |
| 3     | 103       | 1.39%   |
| 4     | 10        | 0.13%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3621      | 33.68%  |
| Intel                             | 3577      | 33.27%  |
| Qualcomm Atheros                  | 1082      | 10.06%  |
| Broadcom                          | 740       | 6.88%   |
| Ralink Technology                 | 205       | 1.91%   |
| Marvell Technology Group          | 168       | 1.56%   |
| Broadcom Limited                  | 152       | 1.41%   |
| Nvidia                            | 121       | 1.13%   |
| TP-Link                           | 113       | 1.05%   |
| Ralink                            | 113       | 1.05%   |
| MediaTek                          | 93        | 0.87%   |
| ASIX Electronics                  | 46        | 0.43%   |
| Ericsson Business Mobile Networks | 41        | 0.38%   |
| Samsung Electronics               | 40        | 0.37%   |
| DisplayLink                       | 39        | 0.36%   |
| Microsoft                         | 37        | 0.34%   |
| Dell                              | 36        | 0.33%   |
| NetGear                           | 30        | 0.28%   |
| Belkin Components                 | 29        | 0.27%   |
| Qualcomm Atheros Communications   | 27        | 0.25%   |
| Lenovo                            | 27        | 0.25%   |
| Huawei Technologies               | 26        | 0.24%   |
| Edimax Technology                 | 25        | 0.23%   |
| Aquantia                          | 22        | 0.2%    |
| Qualcomm                          | 21        | 0.2%    |
| Hewlett-Packard                   | 18        | 0.17%   |
| ASUSTek Computer                  | 16        | 0.15%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.14%   |
| Sierra Wireless                   | 14        | 0.13%   |
| Microchip Technology              | 12        | 0.11%   |
| Mellanox Technologies             | 11        | 0.1%    |
| JMicron Technology                | 11        | 0.1%    |
| Google                            | 11        | 0.1%    |
| Xiaomi                            | 10        | 0.09%   |
| VIA Technologies                  | 10        | 0.09%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.08%   |
| D-Link                            | 9         | 0.08%   |
| Apple                             | 9         | 0.08%   |
| D-Link System                     | 8         | 0.07%   |
| OPPO Electronics                  | 7         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2350      | 18.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 421       | 3.31%   |
| Intel Wi-Fi 6 AX200                                               | 350       | 2.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 296       | 2.33%   |
| Intel I211 Gigabit Network Connection                             | 241       | 1.89%   |
| Intel Wireless 8265 / 8275                                        | 206       | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 184       | 1.45%   |
| Intel Wireless 7265                                               | 172       | 1.35%   |
| Intel Wireless 7260                                               | 167       | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 155       | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 151       | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 143       | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 141       | 1.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 140       | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 130       | 1.02%   |
| Intel Wireless 3165                                               | 125       | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 124       | 0.97%   |
| Intel Wireless 8260                                               | 123       | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 121       | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 118       | 0.93%   |
| Intel Wi-Fi 6 AX201                                               | 110       | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 107       | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 88        | 0.69%   |
| Intel Wireless-AC 9260                                            | 88        | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 86        | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 84        | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 83        | 0.65%   |
| Realtek 802.11ac NIC                                              | 77        | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 75        | 0.59%   |
| Intel Ethernet Controller I225-V                                  | 72        | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 72        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 72        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 70        | 0.55%   |
| Ralink MT7601U Wireless Adapter                                   | 69        | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 69        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 67        | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                     | 67        | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 65        | 0.51%   |
| Intel 82577LM Gigabit Network Connection                          | 65        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2593      | 43.91%  |
| Realtek Semiconductor           | 1039      | 17.6%   |
| Qualcomm Atheros                | 881       | 14.92%  |
| Broadcom                        | 466       | 7.89%   |
| Ralink Technology               | 205       | 3.47%   |
| Ralink                          | 112       | 1.9%    |
| Broadcom Limited                | 110       | 1.86%   |
| TP-Link                         | 107       | 1.81%   |
| MediaTek                        | 83        | 1.41%   |
| Microsoft                       | 35        | 0.59%   |
| Marvell Technology Group        | 35        | 0.59%   |
| NetGear                         | 30        | 0.51%   |
| Belkin Components               | 28        | 0.47%   |
| Qualcomm Atheros Communications | 27        | 0.46%   |
| Edimax Technology               | 25        | 0.42%   |
| Dell                            | 21        | 0.36%   |
| ASUSTek Computer                | 15        | 0.25%   |
| Sierra Wireless                 | 14        | 0.24%   |
| Qualcomm                        | 11        | 0.19%   |
| D-Link                          | 9         | 0.15%   |
| D-Link System                   | 7         | 0.12%   |
| Micro Star International        | 6         | 0.1%    |
| IMC Networks                    | 6         | 0.1%    |
| ZyDAS                           | 4         | 0.07%   |
| Linksys                         | 4         | 0.07%   |
| Gemtek                          | 4         | 0.07%   |
| Fibocom                         | 4         | 0.07%   |
| Wacom                           | 3         | 0.05%   |
| TRENDnet                        | 3         | 0.05%   |
| Sitecom Europe                  | 3         | 0.05%   |
| Wilocity                        | 2         | 0.03%   |
| Hewlett-Packard                 | 2         | 0.03%   |
| Texas Instruments               | 1         | 0.02%   |
| Senao                           | 1         | 0.02%   |
| Philips (or NXP)                | 1         | 0.02%   |
| InProComm                       | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| CyberTAN Technology             | 1         | 0.02%   |
| BUFFALO                         | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 350       | 5.87%   |
| Intel Wireless 8265 / 8275                                              | 206       | 3.46%   |
| Intel Wireless 7265                                                     | 172       | 2.89%   |
| Intel Wireless 7260                                                     | 167       | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 155       | 2.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 151       | 2.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 141       | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 140       | 2.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 130       | 2.18%   |
| Intel Wireless 3165                                                     | 125       | 2.1%    |
| Intel Wireless 8260                                                     | 123       | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 121       | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 118       | 1.98%   |
| Intel Wi-Fi 6 AX201                                                     | 110       | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 88        | 1.48%   |
| Intel Wireless-AC 9260                                                  | 88        | 1.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 1.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 84        | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 83        | 1.39%   |
| Realtek 802.11ac NIC                                                    | 77        | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 75        | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 72        | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 72        | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 70        | 1.17%   |
| Ralink MT7601U Wireless Adapter                                         | 69        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 69        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 67        | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                           | 67        | 1.12%   |
| Intel Wireless 3160                                                     | 59        | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 58        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 57        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 57        | 0.96%   |
| Ralink RT5370 Wireless Adapter                                          | 56        | 0.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 56        | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 50        | 0.84%   |
| Intel WiFi Link 5100                                                    | 50        | 0.84%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 46        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                          | 45        | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 41        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3163      | 49.06%  |
| Intel                                  | 1935      | 30.01%  |
| Broadcom                               | 383       | 5.94%   |
| Qualcomm Atheros                       | 299       | 4.64%   |
| Marvell Technology Group               | 133       | 2.06%   |
| Nvidia                                 | 121       | 1.88%   |
| ASIX Electronics                       | 46        | 0.71%   |
| Broadcom Limited                       | 45        | 0.7%    |
| DisplayLink                            | 39        | 0.6%    |
| Samsung Electronics                    | 30        | 0.47%   |
| Lenovo                                 | 26        | 0.4%    |
| Huawei Technologies                    | 22        | 0.34%   |
| Aquantia                               | 22        | 0.34%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.22%   |
| Microchip Technology                   | 11        | 0.17%   |
| JMicron Technology                     | 11        | 0.17%   |
| Google                                 | 11        | 0.17%   |
| Xiaomi                                 | 10        | 0.16%   |
| VIA Technologies                       | 10        | 0.16%   |
| Qualcomm                               | 10        | 0.16%   |
| Mellanox Technologies                  | 10        | 0.16%   |
| MediaTek                               | 9         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 8         | 0.12%   |
| OPPO Electronics                       | 7         | 0.11%   |
| Apple                                  | 7         | 0.11%   |
| TP-Link                                | 6         | 0.09%   |
| Motorola PCS                           | 6         | 0.09%   |
| ICS Advent                             | 5         | 0.08%   |
| Attansic Technology                    | 5         | 0.08%   |
| T & A Mobile Phones                    | 4         | 0.06%   |
| Standard Microsystems                  | 4         | 0.06%   |
| Hewlett-Packard                        | 4         | 0.06%   |
| HTC (High Tech Computer)               | 3         | 0.05%   |
| Emulex                                 | 3         | 0.05%   |
| 3Com                                   | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| Research In Motion                     | 2         | 0.03%   |
| QLogic                                 | 2         | 0.03%   |
| Microsoft                              | 2         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2350      | 35.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 421       | 6.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 296       | 4.48%   |
| Intel I211 Gigabit Network Connection                             | 241       | 3.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 184       | 2.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 143       | 2.17%   |
| Intel Ethernet Connection (2) I219-V                              | 124       | 1.88%   |
| Intel Ethernet Connection I217-LM                                 | 107       | 1.62%   |
| Intel Ethernet Controller I225-V                                  | 72        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 68        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 65        | 0.98%   |
| Intel 82577LM Gigabit Network Connection                          | 65        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 60        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 51        | 0.77%   |
| Nvidia MCP61 Ethernet                                             | 51        | 0.77%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 45        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 43        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 43        | 0.65%   |
| Intel 82574L Gigabit Network Connection                           | 43        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 42        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 42        | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 42        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 42        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 41        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 37        | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 37        | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 36        | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 35        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                              | 35        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 35        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 33        | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 33        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 31        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 30        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 29        | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 27        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 26        | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 26        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6077      | 51.68%  |
| WiFi     | 5520      | 46.95%  |
| Modem    | 143       | 1.22%   |
| Unknown  | 18        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4281      | 57.28%  |
| Ethernet | 3190      | 42.68%  |
| Modem    | 2         | 0.03%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3783      | 51.93%  |
| 1     | 3068      | 42.11%  |
| 0     | 197       | 2.7%    |
| 3     | 167       | 2.29%   |
| 4     | 42        | 0.58%   |
| 5     | 18        | 0.25%   |
| 6     | 8         | 0.11%   |
| 8     | 2         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6403      | 87.17%  |
| Yes  | 942       | 12.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2011      | 46.43%  |
| Realtek Semiconductor           | 355       | 8.2%    |
| Cambridge Silicon Radio         | 326       | 7.53%   |
| Qualcomm Atheros Communications | 306       | 7.07%   |
| Broadcom                        | 279       | 6.44%   |
| Apple                           | 193       | 4.46%   |
| IMC Networks                    | 192       | 4.43%   |
| Foxconn / Hon Hai               | 113       | 2.61%   |
| Lite-On Technology              | 105       | 2.42%   |
| Dell                            | 76        | 1.75%   |
| ASUSTek Computer                | 73        | 1.69%   |
| Toshiba                         | 55        | 1.27%   |
| Hewlett-Packard                 | 43        | 0.99%   |
| Marvell Semiconductor           | 33        | 0.76%   |
| Realtek                         | 22        | 0.51%   |
| MediaTek                        | 19        | 0.44%   |
| Belkin Components               | 19        | 0.44%   |
| Alps Electric                   | 18        | 0.42%   |
| Foxconn International           | 14        | 0.32%   |
| TP-Link                         | 12        | 0.28%   |
| Integrated System Solution      | 10        | 0.23%   |
| Ralink                          | 9         | 0.21%   |
| Taiyo Yuden                     | 6         | 0.14%   |
| Ralink Technology               | 6         | 0.14%   |
| Askey Computer                  | 6         | 0.14%   |
| Micro Star International        | 5         | 0.12%   |
| USI                             | 4         | 0.09%   |
| Logitech                        | 4         | 0.09%   |
| HTC (High Tech Computer)        | 4         | 0.09%   |
| Edimax Technology               | 3         | 0.07%   |
| Unknown                         | 3         | 0.07%   |
| Sitecom Europe                  | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 803       | 18.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 326       | 7.52%   |
| Intel AX200 Bluetooth                               | 322       | 7.43%   |
| Intel AX201 Bluetooth                               | 313       | 7.22%   |
| Realtek Bluetooth Radio                             | 221       | 5.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 210       | 4.85%   |
| IMC Networks Bluetooth Radio                        | 125       | 2.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 114       | 2.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 86        | 1.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 80        | 1.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 76        | 1.75%   |
| Intel AX210 Bluetooth                               | 75        | 1.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 73        | 1.68%   |
| Apple Bluetooth USB Host Controller                 | 72        | 1.66%   |
| Apple Bluetooth Host Controller                     | 70        | 1.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 68        | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 61        | 1.41%   |
| Foxconn / Hon Hai Bluetooth Device                  | 58        | 1.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 56        | 1.29%   |
| Intel Bluetooth Device                              | 54        | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 41        | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                         | 40        | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 0.78%   |
| Marvell Bluetooth and Wireless LAN Composite        | 29        | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 29        | 0.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 29        | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 27        | 0.62%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 27        | 0.62%   |
| IMC Networks Bluetooth Device                       | 26        | 0.6%    |
| Dell DW375 Bluetooth Module                         | 26        | 0.6%    |
| Lite-On Bluetooth Device                            | 24        | 0.55%   |
| IMC Networks Wireless_Device                        | 23        | 0.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 23        | 0.53%   |
| Realtek RTL8821A Bluetooth                          | 22        | 0.51%   |
| Realtek Bluetooth Radio                             | 22        | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 0.51%   |
| Apple Bluetooth HCI                                 | 21        | 0.48%   |
| MediaTek Wireless_Device                            | 19        | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                    | 19        | 0.44%   |
| Toshiba Bluetooth Device                            | 17        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4975      | 49.5%   |
| AMD                                  | 2143      | 21.32%  |
| Nvidia                               | 1760      | 17.51%  |
| C-Media Electronics                  | 185       | 1.84%   |
| Creative Labs                        | 91        | 0.91%   |
| Logitech                             | 64        | 0.64%   |
| Texas Instruments                    | 56        | 0.56%   |
| Realtek Semiconductor                | 38        | 0.38%   |
| JMTek                                | 36        | 0.36%   |
| Focusrite-Novation                   | 33        | 0.33%   |
| ASUSTek Computer                     | 33        | 0.33%   |
| Creative Technology                  | 32        | 0.32%   |
| GN Netcom                            | 31        | 0.31%   |
| Razer USA                            | 30        | 0.3%    |
| SteelSeries ApS                      | 28        | 0.28%   |
| Plantronics                          | 26        | 0.26%   |
| Micro Star International             | 21        | 0.21%   |
| Corsair                              | 21        | 0.21%   |
| Blue Microphones                     | 20        | 0.2%    |
| VIA Technologies                     | 19        | 0.19%   |
| Lenovo                               | 19        | 0.19%   |
| Kingston Technology                  | 18        | 0.18%   |
| Generalplus Technology               | 16        | 0.16%   |
| Apple                                | 16        | 0.16%   |
| Silicon Integrated Systems [SiS]     | 15        | 0.15%   |
| Sennheiser Communications            | 12        | 0.12%   |
| XMOS                                 | 10        | 0.1%    |
| Thesycon Systemsoftware & Consulting | 10        | 0.1%    |
| Tenx Technology                      | 10        | 0.1%    |
| Dell                                 | 10        | 0.1%    |
| BEHRINGER International              | 10        | 0.1%    |
| Hewlett-Packard                      | 9         | 0.09%   |
| ATI Technologies                     | 9         | 0.09%   |
| Sony                                 | 8         | 0.08%   |
| GYROCOM C&C                          | 8         | 0.08%   |
| AKAI Professional M.I.               | 8         | 0.08%   |
| KTMicro                              | 7         | 0.07%   |
| Conexant Systems                     | 7         | 0.07%   |
| Yamaha                               | 6         | 0.06%   |
| Samson Technologies                  | 6         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 508       | 4.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 480       | 4.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 452       | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 429       | 3.6%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 341       | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 335       | 2.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 297       | 2.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 286       | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 268       | 2.25%   |
| AMD FCH Azalia Controller                                                                         | 254       | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 244       | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 239       | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 205       | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 185       | 1.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 180       | 1.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 179       | 1.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 166       | 1.39%   |
| Intel 8 Series HD Audio Controller                                                                | 165       | 1.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 163       | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 163       | 1.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 154       | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 153       | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 147       | 1.24%   |
| Intel Broadwell-U Audio Controller                                                                | 147       | 1.24%   |
| Intel 200 Series PCH HD Audio                                                                     | 147       | 1.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 140       | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 129       | 1.08%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 115       | 0.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 111       | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 109       | 0.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 109       | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 106       | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 104       | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 103       | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 102       | 0.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 100       | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 93        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 90        | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 90        | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 85        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 782       | 19.58%  |
| SK hynix            | 703       | 17.61%  |
| Corsair             | 476       | 11.92%  |
| Micron Technology   | 401       | 10.04%  |
| Crucial             | 392       | 9.82%   |
| Unknown             | 381       | 9.54%   |
| Kingston            | 350       | 8.77%   |
| Ramaxel Technology  | 62        | 1.55%   |
| A-DATA Technology   | 57        | 1.43%   |
| Nanya Technology    | 49        | 1.23%   |
| Elpida              | 49        | 1.23%   |
| G.Skill             | 39        | 0.98%   |
| Unknown (ABCD)      | 38        | 0.95%   |
| Team                | 29        | 0.73%   |
| Unknown             | 20        | 0.5%    |
| Patriot             | 19        | 0.48%   |
| Transcend           | 10        | 0.25%   |
| Qimonda             | 9         | 0.23%   |
| Hewlett-Packard     | 9         | 0.23%   |
| ASint Technology    | 7         | 0.18%   |
| Apacer              | 7         | 0.18%   |
| A Force             | 7         | 0.18%   |
| Toshiba             | 6         | 0.15%   |
| Timetec             | 6         | 0.15%   |
| Goodram             | 5         | 0.13%   |
| KLEVV               | 4         | 0.1%    |
| GSkill              | 4         | 0.1%    |
| Essencore           | 3         | 0.08%   |
| Axiom               | 3         | 0.08%   |
| 4ea5                | 3         | 0.08%   |
| V-Color             | 2         | 0.05%   |
| Unknown (F301)      | 2         | 0.05%   |
| Unknown (0x0702)    | 2         | 0.05%   |
| Unknown (0B38)      | 2         | 0.05%   |
| Thermaltake         | 2         | 0.05%   |
| Neo Forza           | 2         | 0.05%   |
| Lexar               | 2         | 0.05%   |
| Innodisk            | 2         | 0.05%   |
| Infineon            | 2         | 0.05%   |
| ff                  | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 45        | 1.04%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 41        | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 33        | 0.77%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 26        | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 25        | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.49%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 20        | 0.46%   |
| Unknown                                                          | 20        | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 19        | 0.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.42%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 18        | 0.42%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 17        | 0.39%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 17        | 0.39%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 16        | 0.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 15        | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 15        | 0.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 15        | 0.35%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 14        | 0.32%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 14        | 0.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 14        | 0.32%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.32%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 14        | 0.32%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 13        | 0.3%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.3%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 12        | 0.28%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 12        | 0.28%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 12        | 0.28%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.26%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 11        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1565      | 45%     |
| DDR3    | 1138      | 32.72%  |
| DDR2    | 192       | 5.52%   |
| LPDDR4  | 150       | 4.31%   |
| LPDDR3  | 119       | 3.42%   |
| Unknown | 111       | 3.19%   |
| SDRAM   | 105       | 3.02%   |
| DDR5    | 47        | 1.35%   |
| DDR     | 25        | 0.72%   |
| LPDDR5  | 18        | 0.52%   |
| DRAM    | 8         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1793      | 52.26%  |
| DIMM         | 1321      | 38.5%   |
| Row Of Chips | 261       | 7.61%   |
| Unknown      | 23        | 0.67%   |
| Chip         | 22        | 0.64%   |
| RIMM         | 7         | 0.2%    |
| FB-DIMM      | 4         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1413      | 37.65%  |
| 4096   | 1017      | 27.1%   |
| 16384  | 551       | 14.68%  |
| 2048   | 473       | 12.6%   |
| 1024   | 153       | 4.08%   |
| 32768  | 124       | 3.3%    |
| 512    | 17        | 0.45%   |
| 256    | 2         | 0.05%   |
| 131072 | 1         | 0.03%   |
| 16     | 1         | 0.03%   |
| 13     | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 748       | 19.83%  |
| 2667    | 491       | 13.01%  |
| 3200    | 452       | 11.98%  |
| 2400    | 304       | 8.06%   |
| 1333    | 268       | 7.1%    |
| 2133    | 192       | 5.09%   |
| 3600    | 122       | 3.23%   |
| 667     | 106       | 2.81%   |
| 1867    | 97        | 2.57%   |
| 1334    | 91        | 2.41%   |
| 800     | 90        | 2.39%   |
| Unknown | 61        | 1.62%   |
| 4267    | 60        | 1.59%   |
| 1067    | 46        | 1.22%   |
| 3400    | 42        | 1.11%   |
| 1066    | 40        | 1.06%   |
| 3266    | 39        | 1.03%   |
| 3000    | 37        | 0.98%   |
| 4800    | 33        | 0.87%   |
| 3733    | 32        | 0.85%   |
| 2048    | 31        | 0.82%   |
| 1866    | 30        | 0.8%    |
| 4199    | 24        | 0.64%   |
| 2933    | 23        | 0.61%   |
| 2800    | 23        | 0.61%   |
| 3533    | 21        | 0.56%   |
| 2666    | 21        | 0.56%   |
| 533     | 21        | 0.56%   |
| 6400    | 20        | 0.53%   |
| 1800    | 19        | 0.5%    |
| 400     | 16        | 0.42%   |
| 4266    | 15        | 0.4%    |
| 3800    | 12        | 0.32%   |
| 975     | 12        | 0.32%   |
| 6000    | 7         | 0.19%   |
| 3666    | 7         | 0.19%   |
| 1639    | 7         | 0.19%   |
| 49926   | 6         | 0.16%   |
| 8400    | 6         | 0.16%   |
| 3534    | 6         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 73        | 42.44%  |
| Canon                 | 30        | 17.44%  |
| Samsung Electronics   | 16        | 9.3%    |
| Seiko Epson           | 15        | 8.72%   |
| Brother Industries    | 15        | 8.72%   |
| Prolific Technology   | 5         | 2.91%   |
| Lexmark International | 4         | 2.33%   |
| STMicroelectronics    | 2         | 1.16%   |
| QinHeng Electronics   | 2         | 1.16%   |
| Oki Data              | 2         | 1.16%   |
| Kyocera               | 2         | 1.16%   |
| Dymo-CoStar           | 2         | 1.16%   |
| Seiko Instruments     | 1         | 0.58%   |
| Ricoh                 | 1         | 0.58%   |
| Dell                  | 1         | 0.58%   |
| Apple                 | 1         | 0.58%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 7         | 4.02%   |
| HP ENVY 4520 series                                       | 6         | 3.45%   |
| Prolific PL2305 Parallel Port                             | 5         | 2.87%   |
| HP ENVY 5000 series                                       | 5         | 2.87%   |
| Canon PIXMA MG2500 Series                                 | 5         | 2.87%   |
| HP DeskJet 2620 All-in-One Printer                        | 4         | 2.3%    |
| HP DeskJet 2130 series                                    | 3         | 1.72%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.15%   |
| Seiko Epson XP-240 Series                                 | 2         | 1.15%   |
| Seiko Epson XP-200 Series                                 | 2         | 1.15%   |
| Samsung ML-2250 Series                                    | 2         | 1.15%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.15%   |
| Samsung M2020 Series                                      | 2         | 1.15%   |
| Samsung C43x Series                                       | 2         | 1.15%   |
| QinHeng CH340S                                            | 2         | 1.15%   |
| Oki Data USB Device                                       | 2         | 1.15%   |
| HP LaserJet P2015 series                                  | 2         | 1.15%   |
| HP LaserJet 200 colorMFP M276nw                           | 2         | 1.15%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.15%   |
| HP Deskjet F2280 series                                   | 2         | 1.15%   |
| HP DeskJet 3700 series                                    | 2         | 1.15%   |
| HP DeskJet 3630 series                                    | 2         | 1.15%   |
| HP Deskjet 2540 series                                    | 2         | 1.15%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.15%   |
| HP Color LaserJet CP1215                                  | 2         | 1.15%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.15%   |
| Canon PIXMA MP495                                         | 2         | 1.15%   |
| Canon PIXMA MG3600 Series                                 | 2         | 1.15%   |
| Canon MG5700 series                                       | 2         | 1.15%   |
| Canon iP7200 series                                       | 2         | 1.15%   |
| Canon CanoScan LiDE 300                                   | 2         | 1.15%   |
| Brother HL-3140CW series                                  | 2         | 1.15%   |
| Brother DCP-7055 scanner/printer                          | 2         | 1.15%   |
| Seiko Instruments SLP-450 Driver                          | 1         | 0.57%   |
| Seiko Epson XP-211 214 216 Series                         | 1         | 0.57%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.57%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.57%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.57%   |
| Seiko Epson L355 Series                                   | 1         | 0.57%   |
| Samsung SCX-4300 Series                                   | 1         | 0.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 25        | 62.5%   |
| Seiko Epson        | 8         | 20%     |
| Hewlett-Packard    | 3         | 7.5%    |
| Ultima Electronics | 2         | 5%      |
| Mustek Systems     | 1         | 2.5%    |
| AGFA-Gevaert NV    | 1         | 2.5%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 5         | 12.5%   |
| Canon CanoScan LiDE 220                                                               | 4         | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3         | 7.5%    |
| Canon CanoScan LiDE 200                                                               | 3         | 7.5%    |
| Canon CanoScan LiDE 110                                                               | 3         | 7.5%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 5%      |
| Seiko Epson Scanner                                                                   | 2         | 5%      |
| HP ScanJet 5300c/5370c                                                                | 2         | 5%      |
| Canon CanoScan LiDE 100                                                               | 2         | 5%      |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 1         | 2.5%    |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.5%    |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 2.5%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 2.5%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 2.5%    |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 2.5%    |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1         | 2.5%    |
| HP Scanjet G2710                                                                      | 1         | 2.5%    |
| Canon CanoScan LiDE 90                                                                | 1         | 2.5%    |
| Canon CanoScan LiDE 70                                                                | 1         | 2.5%    |
| Canon CanoScan LiDE 600F                                                              | 1         | 2.5%    |
| Canon CanoScan LiDE 210                                                               | 1         | 2.5%    |
| Canon CanoScan 3000/3000F/3000ex                                                      | 1         | 2.5%    |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1         | 2.5%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 882       | 21.37%  |
| Microdia                               | 428       | 10.37%  |
| Realtek Semiconductor                  | 323       | 7.82%   |
| IMC Networks                           | 288       | 6.98%   |
| Logitech                               | 286       | 6.93%   |
| Sunplus Innovation Technology          | 200       | 4.84%   |
| Bison Electronics                      | 182       | 4.41%   |
| Apple                                  | 159       | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 140       | 3.39%   |
| Quanta                                 | 136       | 3.29%   |
| Suyin                                  | 117       | 2.83%   |
| Lite-On Technology                     | 97        | 2.35%   |
| Microsoft                              | 79        | 1.91%   |
| Syntek                                 | 78        | 1.89%   |
| Acer                                   | 72        | 1.74%   |
| Silicon Motion                         | 63        | 1.53%   |
| Alcor Micro                            | 52        | 1.26%   |
| Samsung Electronics                    | 47        | 1.14%   |
| Ricoh                                  | 44        | 1.07%   |
| Lenovo                                 | 39        | 0.94%   |
| Luxvisions Innotech Limited            | 35        | 0.85%   |
| Z-Star Microelectronics                | 30        | 0.73%   |
| ARC International                      | 27        | 0.65%   |
| Generalplus Technology                 | 26        | 0.63%   |
| GEMBIRD                                | 23        | 0.56%   |
| MacroSilicon                           | 16        | 0.39%   |
| Creative Technology                    | 16        | 0.39%   |
| Sonix Technology                       | 15        | 0.36%   |
| ALi                                    | 13        | 0.31%   |
| Primax Electronics                     | 12        | 0.29%   |
| Razer USA                              | 11        | 0.27%   |
| Aveo Technology                        | 10        | 0.24%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.22%   |
| Huawei Technologies                    | 9         | 0.22%   |
| Hewlett-Packard                        | 8         | 0.19%   |
| SunplusIT                              | 7         | 0.17%   |
| Sunplus Technology                     | 7         | 0.17%   |
| OmniVision Technologies                | 7         | 0.17%   |
| Intel                                  | 7         | 0.17%   |
| Importek                               | 7         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 183       | 4.39%   |
| Chicony Integrated Camera                               | 152       | 3.64%   |
| Realtek Integrated_Webcam_HD                            | 107       | 2.56%   |
| Logitech HD Pro Webcam C920                             | 85        | 2.04%   |
| IMC Networks Integrated Camera                          | 82        | 1.97%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 80        | 1.92%   |
| Sunplus Integrated_Webcam_HD                            | 63        | 1.51%   |
| Chicony HD WebCam                                       | 63        | 1.51%   |
| Logitech Webcam C270                                    | 55        | 1.32%   |
| Chicony TOSHIBA Web Camera - HD                         | 50        | 1.2%    |
| Samsung Galaxy A5 (MTP)                                 | 47        | 1.13%   |
| Apple FaceTime HD Camera (Built-in)                     | 47        | 1.13%   |
| Apple Built-in iSight                                   | 47        | 1.13%   |
| Chicony USB2.0 Camera                                   | 39        | 0.93%   |
| Bison Integrated Camera                                 | 39        | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 39        | 0.93%   |
| Microdia Integrated Webcam                              | 37        | 0.89%   |
| Microdia Webcam Vitade AF                               | 35        | 0.84%   |
| Chicony USB 2.0 Camera                                  | 34        | 0.81%   |
| Microsoft LifeCam HD-3000                               | 32        | 0.77%   |
| Lite-On Integrated Camera                               | 32        | 0.77%   |
| Chicony HP TrueVision HD Camera                         | 30        | 0.72%   |
| Chicony HP TrueVision HD                                | 30        | 0.72%   |
| Syntek Integrated Camera                                | 29        | 0.7%    |
| Chicony HP HD Camera                                    | 29        | 0.7%    |
| Realtek USB Camera                                      | 28        | 0.67%   |
| Chicony HP Wide Vision HD Camera                        | 27        | 0.65%   |
| Chicony EasyCamera                                      | 27        | 0.65%   |
| ARC International Camera                                | 27        | 0.65%   |
| Bison BisonCam,NB Pro                                   | 26        | 0.62%   |
| Syntek Lenovo EasyCamera                                | 25        | 0.6%    |
| Chicony VGA Webcam                                      | 25        | 0.6%    |
| Bison SunplusIT Integrated Camera                       | 25        | 0.6%    |
| Alcor Micro USB 2.0 Camera                              | 25        | 0.6%    |
| Quanta HD User Facing                                   | 23        | 0.55%   |
| Microsoft LifeCam Cinema                                | 23        | 0.55%   |
| Chicony Integrated Camera (1280x720@30)                 | 23        | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 23        | 0.55%   |
| Apple FaceTime HD Camera                                | 23        | 0.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 19        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 225       | 31.82%  |
| Synaptics                          | 188       | 26.59%  |
| Shenzhen Goodix Technology         | 109       | 15.42%  |
| Upek                               | 49        | 6.93%   |
| AuthenTec                          | 47        | 6.65%   |
| LighTuning Technology              | 33        | 4.67%   |
| Elan Microelectronics              | 33        | 4.67%   |
| STMicroelectronics                 | 16        | 2.26%   |
| Samsung Electronics                | 3         | 0.42%   |
| HOLTEK                             | 2         | 0.28%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.14%   |
| Focal-systems.Corp                 | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 59        | 8.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 47        | 6.65%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 6.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 5.37%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 37        | 5.23%   |
| Synaptics UWP WBDI                                                         | 31        | 4.38%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 3.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 3.54%   |
| Shenzhen Goodix FingerPrint                                                | 23        | 3.25%   |
| Validity Sensors Synaptics WBDI                                            | 22        | 3.11%   |
| Synaptics  WBDI                                                            | 19        | 2.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 2.4%    |
| Validity Sensors VFS491                                                    | 16        | 2.26%   |
| STMicroelectronics Fingerprint Reader                                      | 16        | 2.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 15        | 2.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 15        | 2.12%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.98%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.98%   |
| Elan ELAN:Fingerprint                                                      | 14        | 1.98%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 1.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 1.56%   |
| AuthenTec AES2810                                                          | 11        | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.41%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 10        | 1.41%   |
| Elan ELAN:ARM-M4                                                           | 9         | 1.27%   |
| Unknown                                                                    | 9         | 1.27%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 8         | 1.13%   |
| Synaptics WBDI Device                                                      | 8         | 1.13%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.13%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.99%   |
| Synaptics WBDI                                                             | 6         | 0.85%   |
| Synaptics UWP WBDI Device                                                  | 6         | 0.85%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 6         | 0.85%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.85%   |
| AuthenTec AES1600                                                          | 6         | 0.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.71%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.71%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 172       | 51.5%   |
| Alcor Micro               | 75        | 22.46%  |
| Upek                      | 26        | 7.78%   |
| Lenovo                    | 24        | 7.19%   |
| O2 Micro                  | 22        | 6.59%   |
| Gemalto (was Gemplus)     | 4         | 1.2%    |
| SCM Microsystems          | 3         | 0.9%    |
| Yubico.com                | 1         | 0.3%    |
| Purism, SPC               | 1         | 0.3%    |
| OmniKey                   | 1         | 0.3%    |
| Hewlett-Packard           | 1         | 0.3%    |
| Clay Logic                | 1         | 0.3%    |
| Chicony Electronics       | 1         | 0.3%    |
| BIT4ID                    | 1         | 0.3%    |
| Aladdin Knowledge Systems | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 70        | 20.96%  |
| Broadcom BCM5880 Secure Applications Processor                               | 69        | 20.66%  |
| Broadcom 5880                                                                | 44        | 13.17%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 31        | 9.28%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 7.78%   |
| Broadcom 58200                                                               | 26        | 7.78%   |
| Lenovo Integrated Smart Card Reader                                          | 22        | 6.59%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 5.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.5%    |
| Alcor Micro Watchdata W 1981                                                 | 5         | 1.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.9%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.6%    |
| Lenovo Smartcard Keyboard                                                    | 2         | 0.6%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.6%    |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.3%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.3%    |
| Purism, SPC Librem Key                                                       | 1         | 0.3%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.3%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.3%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.3%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.3%    |
| BIT4ID miniLector EVO                                                        | 1         | 0.3%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5249      | 70.59%  |
| 1     | 1729      | 23.25%  |
| 2     | 371       | 4.99%   |
| 3     | 60        | 0.81%   |
| 4     | 13        | 0.17%   |
| 5     | 7         | 0.09%   |
| 7     | 3         | 0.04%   |
| 6     | 3         | 0.04%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 688       | 26.12%  |
| Graphics card            | 556       | 21.11%  |
| Net/wireless             | 423       | 16.06%  |
| Chipcard                 | 304       | 11.54%  |
| Multimedia controller    | 162       | 6.15%   |
| Communication controller | 116       | 4.4%    |
| Sound                    | 60        | 2.28%   |
| Unassigned class         | 58        | 2.2%    |
| Camera                   | 56        | 2.13%   |
| Bluetooth                | 54        | 2.05%   |
| Storage                  | 40        | 1.52%   |
| Net/ethernet             | 24        | 0.91%   |
| Card reader              | 22        | 0.84%   |
| Modem                    | 18        | 0.68%   |
| Network                  | 16        | 0.61%   |
| Storage/raid             | 10        | 0.38%   |
| Flash memory             | 8         | 0.3%    |
| Dvb card                 | 6         | 0.23%   |
| Firewire controller      | 5         | 0.19%   |
| Storage/ide              | 4         | 0.15%   |
| Storage/nvme             | 3         | 0.11%   |
| Unclassified device      | 1         | 0.04%   |

