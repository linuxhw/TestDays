Linux Mint - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Linux Mint.

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

Total: 8394

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 3397                        | [24eb596bce](https://linux-hardware.org/?probe=24eb596bce) | Nov 02, 2022 |
| HP            | 1589                        | [81a347a6a7](https://linux-hardware.org/?probe=81a347a6a7) | Nov 02, 2022 |
| Dell          | 02YRK5 A02                  | [2c63ff26e5](https://linux-hardware.org/?probe=2c63ff26e5) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d28b33e126](https://linux-hardware.org/?probe=d28b33e126) | Nov 01, 2022 |
| Dell          | 0XR1GT A00                  | [8f551aaa52](https://linux-hardware.org/?probe=8f551aaa52) | Nov 01, 2022 |
| Dell          | 088DT1 A01                  | [efcbf8a2eb](https://linux-hardware.org/?probe=efcbf8a2eb) | Nov 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [a3a55bf3e4](https://linux-hardware.org/?probe=a3a55bf3e4) | Nov 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [8d99f1fb3b](https://linux-hardware.org/?probe=8d99f1fb3b) | Nov 01, 2022 |
| ASUSTek       | B150M-V PLUS                | [a451844625](https://linux-hardware.org/?probe=a451844625) | Nov 01, 2022 |
| HP            | 8054                        | [9e1b99d9bb](https://linux-hardware.org/?probe=9e1b99d9bb) | Nov 01, 2022 |
| Dell          | 040DDP A00                  | [22b1e93203](https://linux-hardware.org/?probe=22b1e93203) | Oct 31, 2022 |
| ASUSTek       | Z87-K                       | [7edc0875ed](https://linux-hardware.org/?probe=7edc0875ed) | Oct 31, 2022 |
| Pegatron      | 2AABh                       | [94dd13992c](https://linux-hardware.org/?probe=94dd13992c) | Oct 31, 2022 |
| MSI           | H110M PRO-VD PLUS           | [ced3229025](https://linux-hardware.org/?probe=ced3229025) | Oct 31, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e309413fea](https://linux-hardware.org/?probe=e309413fea) | Oct 31, 2022 |
| ASUSTek       | P8H77-M                     | [2ae72e7e22](https://linux-hardware.org/?probe=2ae72e7e22) | Oct 31, 2022 |
| Gigabyte      | GA-MA770-UD3                | [e49d4af683](https://linux-hardware.org/?probe=e49d4af683) | Oct 31, 2022 |
| HP            | 18E4                        | [89b197e8a9](https://linux-hardware.org/?probe=89b197e8a9) | Oct 31, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [14e8385f99](https://linux-hardware.org/?probe=14e8385f99) | Oct 31, 2022 |
| Gigabyte      | A520M H                     | [0a8043d206](https://linux-hardware.org/?probe=0a8043d206) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [13741c554f](https://linux-hardware.org/?probe=13741c554f) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [e6e466cd8f](https://linux-hardware.org/?probe=e6e466cd8f) | Oct 31, 2022 |
| ASRock        | Z97 Extreme3                | [c741e4ffe8](https://linux-hardware.org/?probe=c741e4ffe8) | Oct 31, 2022 |
| MSI           | Z97 GAMING 3                | [cc2d45c3ff](https://linux-hardware.org/?probe=cc2d45c3ff) | Oct 30, 2022 |
| Gigabyte      | X570 GAMING X               | [d6c135685f](https://linux-hardware.org/?probe=d6c135685f) | Oct 30, 2022 |
| MSI           | Z97 GAMING 3                | [c0926e68a0](https://linux-hardware.org/?probe=c0926e68a0) | Oct 30, 2022 |
| Pegatron      | IPMIP-GS                    | [4e46d903ae](https://linux-hardware.org/?probe=4e46d903ae) | Oct 30, 2022 |
| MSI           | A320M PRO-M2 V2             | [d7c699118b](https://linux-hardware.org/?probe=d7c699118b) | Oct 30, 2022 |
| ASUSTek       | A88XM-PLUS                  | [10aa435a0b](https://linux-hardware.org/?probe=10aa435a0b) | Oct 30, 2022 |
| MSI           | Z77A-GD65                   | [a7bc380726](https://linux-hardware.org/?probe=a7bc380726) | Oct 30, 2022 |
| Dell          | 0M5DCD A00                  | [c3049c59a8](https://linux-hardware.org/?probe=c3049c59a8) | Oct 30, 2022 |
| Dell          | 0M5DCD A00                  | [daae18ab91](https://linux-hardware.org/?probe=daae18ab91) | Oct 30, 2022 |
| ASUSTek       | G11CD                       | [2a9d64387c](https://linux-hardware.org/?probe=2a9d64387c) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [eb71b41aa8](https://linux-hardware.org/?probe=eb71b41aa8) | Oct 29, 2022 |
| HP            | 0AECh D                     | [ee09a01e9e](https://linux-hardware.org/?probe=ee09a01e9e) | Oct 29, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [290f3b115f](https://linux-hardware.org/?probe=290f3b115f) | Oct 29, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [bf841b86f5](https://linux-hardware.org/?probe=bf841b86f5) | Oct 29, 2022 |
| ASUSTek       | M4A785-M                    | [73eae83658](https://linux-hardware.org/?probe=73eae83658) | Oct 29, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [650f1fd648](https://linux-hardware.org/?probe=650f1fd648) | Oct 29, 2022 |
| Gigabyte      | GA-MA770-UD3                | [52a6d45e82](https://linux-hardware.org/?probe=52a6d45e82) | Oct 29, 2022 |
| ASUSTek       | PRIME A320I-K               | [91f4cd151f](https://linux-hardware.org/?probe=91f4cd151f) | Oct 29, 2022 |
| ASRock        | FM2A88X-ITX+                | [00b65eaa83](https://linux-hardware.org/?probe=00b65eaa83) | Oct 29, 2022 |
| Techvision    | TVI7309X B0                 | [65b5280dd1](https://linux-hardware.org/?probe=65b5280dd1) | Oct 29, 2022 |
| ASUSTek       | PRIME H410M-K               | [5a371accfe](https://linux-hardware.org/?probe=5a371accfe) | Oct 29, 2022 |
| ASRock        | B85 Pro4                    | [856d32288b](https://linux-hardware.org/?probe=856d32288b) | Oct 29, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [7d5d2ec0ba](https://linux-hardware.org/?probe=7d5d2ec0ba) | Oct 28, 2022 |
| ASRock        | Z370 Pro4                   | [04e898b2f6](https://linux-hardware.org/?probe=04e898b2f6) | Oct 28, 2022 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [8c85b7ec2e](https://linux-hardware.org/?probe=8c85b7ec2e) | Oct 28, 2022 |
| Lenovo        | MAHOBAY NOK                 | [267b0a3f94](https://linux-hardware.org/?probe=267b0a3f94) | Oct 28, 2022 |
| Gigabyte      | GA-MA790FX-DQ6              | [8ba31a020c](https://linux-hardware.org/?probe=8ba31a020c) | Oct 28, 2022 |
| HP            | 339A                        | [0fdbd7b1d7](https://linux-hardware.org/?probe=0fdbd7b1d7) | Oct 28, 2022 |
| AZW           | Green G2                    | [628aba3de0](https://linux-hardware.org/?probe=628aba3de0) | Oct 27, 2022 |
| Lenovo        | 0B98401 PRO                 | [99f9bbd5ad](https://linux-hardware.org/?probe=99f9bbd5ad) | Oct 27, 2022 |
| MSI           | H110M PRO-VD PLUS           | [d3c4092754](https://linux-hardware.org/?probe=d3c4092754) | Oct 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [81e31b481f](https://linux-hardware.org/?probe=81e31b481f) | Oct 27, 2022 |
| ASRock        | H61M-VG4                    | [25b8826346](https://linux-hardware.org/?probe=25b8826346) | Oct 27, 2022 |
| HP            | 1589                        | [4a15b6de0f](https://linux-hardware.org/?probe=4a15b6de0f) | Oct 27, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [9285fb0d9d](https://linux-hardware.org/?probe=9285fb0d9d) | Oct 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [4659be383c](https://linux-hardware.org/?probe=4659be383c) | Oct 27, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [469345600b](https://linux-hardware.org/?probe=469345600b) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [26c34998ae](https://linux-hardware.org/?probe=26c34998ae) | Oct 26, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [8c97ee418a](https://linux-hardware.org/?probe=8c97ee418a) | Oct 26, 2022 |
| HP            | 1494                        | [fa63090109](https://linux-hardware.org/?probe=fa63090109) | Oct 26, 2022 |
| ASUSTek       | Z87-A                       | [0b4711df41](https://linux-hardware.org/?probe=0b4711df41) | Oct 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | [dbb72f4c00](https://linux-hardware.org/?probe=dbb72f4c00) | Oct 26, 2022 |
| PCWare        | IPMH61R3                    | [9f9410b99d](https://linux-hardware.org/?probe=9f9410b99d) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [705e51d33e](https://linux-hardware.org/?probe=705e51d33e) | Oct 25, 2022 |
| ASUSTek       | Z87-PRO                     | [a48316f550](https://linux-hardware.org/?probe=a48316f550) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [824eb583d8](https://linux-hardware.org/?probe=824eb583d8) | Oct 25, 2022 |
| Alienware     | 046MHW A00                  | [592883e78e](https://linux-hardware.org/?probe=592883e78e) | Oct 25, 2022 |
| Alienware     | 046MHW A00                  | [734fb9ac8c](https://linux-hardware.org/?probe=734fb9ac8c) | Oct 25, 2022 |
| Gigabyte      | H97M-D3H                    | [72532e08fe](https://linux-hardware.org/?probe=72532e08fe) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [a38f9baa55](https://linux-hardware.org/?probe=a38f9baa55) | Oct 25, 2022 |
| ASRock        | 4Core1600-GLAN/M            | [33bf20761f](https://linux-hardware.org/?probe=33bf20761f) | Oct 25, 2022 |
| Gigabyte      | 970A-DS3P                   | [995f7abb0c](https://linux-hardware.org/?probe=995f7abb0c) | Oct 25, 2022 |
| HP            | 805F                        | [eaa3994f86](https://linux-hardware.org/?probe=eaa3994f86) | Oct 25, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [ef9fdf5dcd](https://linux-hardware.org/?probe=ef9fdf5dcd) | Oct 25, 2022 |
| Gigabyte      | F2A78M-HD2                  | [6cffc39cfc](https://linux-hardware.org/?probe=6cffc39cfc) | Oct 25, 2022 |
| Gigabyte      | P41T-D3                     | [fa69e3fada](https://linux-hardware.org/?probe=fa69e3fada) | Oct 25, 2022 |
| Gigabyte      | P41T-D3                     | [c96d8030a6](https://linux-hardware.org/?probe=c96d8030a6) | Oct 25, 2022 |
| Gigabyte      | 965P-DS3                    | [18dad8d151](https://linux-hardware.org/?probe=18dad8d151) | Oct 25, 2022 |
| Gigabyte      | Z87-HD3                     | [da7fe35832](https://linux-hardware.org/?probe=da7fe35832) | Oct 25, 2022 |
| Unknown       | SKYBAY                      | [63f22191e8](https://linux-hardware.org/?probe=63f22191e8) | Oct 24, 2022 |
| HP            | 805A                        | [dbe3ff75e8](https://linux-hardware.org/?probe=dbe3ff75e8) | Oct 24, 2022 |
| HP            | 1589                        | [0be048ec45](https://linux-hardware.org/?probe=0be048ec45) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | [b393d57b17](https://linux-hardware.org/?probe=b393d57b17) | Oct 24, 2022 |
| MSI           | B350M PRO-VD PLUS           | [93068b4cf8](https://linux-hardware.org/?probe=93068b4cf8) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | [1e80f1de23](https://linux-hardware.org/?probe=1e80f1de23) | Oct 24, 2022 |
| Dell          | 0J3C2F A00                  | [d165241883](https://linux-hardware.org/?probe=d165241883) | Oct 24, 2022 |
| ASUSTek       | P8Z68-V LX                  | [86cff422a6](https://linux-hardware.org/?probe=86cff422a6) | Oct 23, 2022 |
| Biostar       | TH67XE                      | [b523b997f6](https://linux-hardware.org/?probe=b523b997f6) | Oct 23, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [eafcc0b1b0](https://linux-hardware.org/?probe=eafcc0b1b0) | Oct 23, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [b7b190000b](https://linux-hardware.org/?probe=b7b190000b) | Oct 23, 2022 |
| MSI           | A320M PRO-M2 V2             | [1691497b7a](https://linux-hardware.org/?probe=1691497b7a) | Oct 23, 2022 |
| Unknown       | 1.0                         | [2a12c33601](https://linux-hardware.org/?probe=2a12c33601) | Oct 23, 2022 |
| AZW           | Green G2                    | [56ee35acfc](https://linux-hardware.org/?probe=56ee35acfc) | Oct 23, 2022 |
| Gigabyte      | H87-HD3                     | [bdd6e6d3a5](https://linux-hardware.org/?probe=bdd6e6d3a5) | Oct 23, 2022 |
| Lenovo        | ThinkServer TS140           | [6f0f7b249a](https://linux-hardware.org/?probe=6f0f7b249a) | Oct 22, 2022 |
| MSI           | B550-A PRO                  | [52d3513a9c](https://linux-hardware.org/?probe=52d3513a9c) | Oct 22, 2022 |
| Gigabyte      | A520M DS3H                  | [3faf4b3ca9](https://linux-hardware.org/?probe=3faf4b3ca9) | Oct 22, 2022 |
| HP            | 213D A01                    | [c7ffdb8626](https://linux-hardware.org/?probe=c7ffdb8626) | Oct 22, 2022 |
| ASRock        | B450M-HDV R4.0              | [0ec4fb54a6](https://linux-hardware.org/?probe=0ec4fb54a6) | Oct 21, 2022 |
| MSI           | B550-A PRO                  | [d17faed180](https://linux-hardware.org/?probe=d17faed180) | Oct 21, 2022 |
| ASRock        | B450M-HDV R4.0              | [1f659498a2](https://linux-hardware.org/?probe=1f659498a2) | Oct 21, 2022 |
| MSI           | H81M-E34                    | [b036f0d602](https://linux-hardware.org/?probe=b036f0d602) | Oct 21, 2022 |
| MSI           | H81M-P33                    | [4bc1726059](https://linux-hardware.org/?probe=4bc1726059) | Oct 21, 2022 |
| MSI           | Z97 GAMING 3                | [2b5803628a](https://linux-hardware.org/?probe=2b5803628a) | Oct 20, 2022 |
| MSI           | Z97 GAMING 3                | [94c634f9b8](https://linux-hardware.org/?probe=94c634f9b8) | Oct 20, 2022 |
| MSI           | H110M GAMING                | [20689f6175](https://linux-hardware.org/?probe=20689f6175) | Oct 20, 2022 |
| Acer          | Extensa M2610 V:1.0         | [1791236969](https://linux-hardware.org/?probe=1791236969) | Oct 20, 2022 |
| Acer          | Extensa M2610 V:1.0         | [e482e312c8](https://linux-hardware.org/?probe=e482e312c8) | Oct 20, 2022 |
| Dell          | 0J3C2F A00                  | [c97e42e738](https://linux-hardware.org/?probe=c97e42e738) | Oct 20, 2022 |
| ASRock        | X399 Taichi                 | [0c5809902b](https://linux-hardware.org/?probe=0c5809902b) | Oct 20, 2022 |
| HP            | 3047h                       | [1a0f4c46f9](https://linux-hardware.org/?probe=1a0f4c46f9) | Oct 20, 2022 |
| ASRock        | N68C-GS FX                  | [9e0b1677e4](https://linux-hardware.org/?probe=9e0b1677e4) | Oct 20, 2022 |
| ASUSTek       | H170M-PLUS                  | [e34cb7ea31](https://linux-hardware.org/?probe=e34cb7ea31) | Oct 20, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | [13830a8b2b](https://linux-hardware.org/?probe=13830a8b2b) | Oct 20, 2022 |
| Dell          | 0PC5F7 A02                  | [1e54b1512b](https://linux-hardware.org/?probe=1e54b1512b) | Oct 20, 2022 |
| ECS           | H61H2-WM                    | [934781c2fb](https://linux-hardware.org/?probe=934781c2fb) | Oct 19, 2022 |
| HP            | 802F                        | [9e51fdba18](https://linux-hardware.org/?probe=9e51fdba18) | Oct 19, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7f736b0a22](https://linux-hardware.org/?probe=7f736b0a22) | Oct 19, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [116fff483b](https://linux-hardware.org/?probe=116fff483b) | Oct 19, 2022 |
| ASUSTek       | M3N78-VM                    | [825d6ebf7f](https://linux-hardware.org/?probe=825d6ebf7f) | Oct 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e0b5c85988](https://linux-hardware.org/?probe=e0b5c85988) | Oct 18, 2022 |
| Dell          | 09WH54 A00                  | [b16396bd74](https://linux-hardware.org/?probe=b16396bd74) | Oct 18, 2022 |
| Gigabyte      | B450M GAMING                | [e1eacaa737](https://linux-hardware.org/?probe=e1eacaa737) | Oct 18, 2022 |
| Acer          | Aspire M1930                | [5b9cbd4f58](https://linux-hardware.org/?probe=5b9cbd4f58) | Oct 18, 2022 |
| Dell          | 0XHGV1 A01                  | [fcac80ff4a](https://linux-hardware.org/?probe=fcac80ff4a) | Oct 18, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [ef6d1400a3](https://linux-hardware.org/?probe=ef6d1400a3) | Oct 17, 2022 |
| ASRock        | X300-ITX                    | [a391ce99bf](https://linux-hardware.org/?probe=a391ce99bf) | Oct 17, 2022 |
| ASUSTek       | Maximus IV Extreme          | [d84677af13](https://linux-hardware.org/?probe=d84677af13) | Oct 17, 2022 |
| Dell          | 0J3C2F A02                  | [284e02a5b2](https://linux-hardware.org/?probe=284e02a5b2) | Oct 17, 2022 |
| ASUSTek       | PRIME A520M-A II            | [cbf3a839e2](https://linux-hardware.org/?probe=cbf3a839e2) | Oct 17, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [2d7d5c19c0](https://linux-hardware.org/?probe=2d7d5c19c0) | Oct 17, 2022 |
| Shuttle       | FS81                        | [61c0ca02f3](https://linux-hardware.org/?probe=61c0ca02f3) | Oct 16, 2022 |
| MSI           | A68HM-E33 V2                | [ff59edf4e0](https://linux-hardware.org/?probe=ff59edf4e0) | Oct 16, 2022 |
| ASUSTek       | PRO B460M-C                 | [eb850e075d](https://linux-hardware.org/?probe=eb850e075d) | Oct 16, 2022 |
| Acer          | Aspire M1930                | [9fa87ae442](https://linux-hardware.org/?probe=9fa87ae442) | Oct 16, 2022 |
| ASUSTek       | PRIME B450M-K II            | [d1d815635a](https://linux-hardware.org/?probe=d1d815635a) | Oct 16, 2022 |
| Dell          | 0D6H9T A00                  | [52dec54de2](https://linux-hardware.org/?probe=52dec54de2) | Oct 16, 2022 |
| AZW           | Green G2                    | [f7a9322b66](https://linux-hardware.org/?probe=f7a9322b66) | Oct 16, 2022 |
| Pegatron      | 2A84h                       | [5b46511238](https://linux-hardware.org/?probe=5b46511238) | Oct 15, 2022 |
| HP            | 8027                        | [9f3d6e24b5](https://linux-hardware.org/?probe=9f3d6e24b5) | Oct 15, 2022 |
| Acer          | Aspire TC-865 V:1.1         | [dd4d81390a](https://linux-hardware.org/?probe=dd4d81390a) | Oct 15, 2022 |
| MSI           | A68HM-E33 V2                | [b2a7c6be3a](https://linux-hardware.org/?probe=b2a7c6be3a) | Oct 15, 2022 |
| Acer          | Aspire TC-865 V:1.1         | [dfe2b3b3bf](https://linux-hardware.org/?probe=dfe2b3b3bf) | Oct 15, 2022 |
| Dell          | 09KPNV A01                  | [5261790ba7](https://linux-hardware.org/?probe=5261790ba7) | Oct 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [3f4c203116](https://linux-hardware.org/?probe=3f4c203116) | Oct 15, 2022 |
| Dell          | 051FJ8 A00                  | [4df6746d88](https://linux-hardware.org/?probe=4df6746d88) | Oct 15, 2022 |
| Dell          | 051FJ8 A00                  | [9008c96170](https://linux-hardware.org/?probe=9008c96170) | Oct 15, 2022 |
| Gigabyte      | P55M-UD2                    | [0e3ba8fdb3](https://linux-hardware.org/?probe=0e3ba8fdb3) | Oct 14, 2022 |
| ASRock        | 970M Pro3                   | [ca8ac557b3](https://linux-hardware.org/?probe=ca8ac557b3) | Oct 14, 2022 |
| Unknown       | Unknown                     | [8a680cbcbe](https://linux-hardware.org/?probe=8a680cbcbe) | Oct 13, 2022 |
| ASUSTek       | P8H67-V                     | [0a4b34dba9](https://linux-hardware.org/?probe=0a4b34dba9) | Oct 13, 2022 |
| Gigabyte      | H81M-S2H                    | [3e38f64c1c](https://linux-hardware.org/?probe=3e38f64c1c) | Oct 13, 2022 |
| ASUSTek       | PRIME A520M-A II            | [736d5cdccc](https://linux-hardware.org/?probe=736d5cdccc) | Oct 13, 2022 |
| MSI           | A320M PRO-M2 V2             | [6c895cb5df](https://linux-hardware.org/?probe=6c895cb5df) | Oct 13, 2022 |
| ASUSTek       | PRIME A520M-K               | [e1bdf49dbf](https://linux-hardware.org/?probe=e1bdf49dbf) | Oct 13, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [3ffa813244](https://linux-hardware.org/?probe=3ffa813244) | Oct 13, 2022 |
| Toshiba       | STI 005492G                 | [e803b9bcf3](https://linux-hardware.org/?probe=e803b9bcf3) | Oct 13, 2022 |
| Acer          | Aspire XC100A               | [6fade2c77f](https://linux-hardware.org/?probe=6fade2c77f) | Oct 13, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [e172a9d71b](https://linux-hardware.org/?probe=e172a9d71b) | Oct 13, 2022 |
| Gigabyte      | P55A-UD3                    | [100f7e1b46](https://linux-hardware.org/?probe=100f7e1b46) | Oct 12, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [f7e78e8188](https://linux-hardware.org/?probe=f7e78e8188) | Oct 12, 2022 |
| ASRock        | B550M Phantom Gaming 4      | [9744660229](https://linux-hardware.org/?probe=9744660229) | Oct 12, 2022 |
| Gigabyte      | 946GMX-S2                   | [491d0c69ca](https://linux-hardware.org/?probe=491d0c69ca) | Oct 12, 2022 |
| Gigabyte      | X570S GAMING X              | [e966aea162](https://linux-hardware.org/?probe=e966aea162) | Oct 12, 2022 |
| Gigabyte      | 946GMX-S2                   | [09ee887f3a](https://linux-hardware.org/?probe=09ee887f3a) | Oct 12, 2022 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | [f3b5809fc9](https://linux-hardware.org/?probe=f3b5809fc9) | Oct 12, 2022 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [1798dba7f1](https://linux-hardware.org/?probe=1798dba7f1) | Oct 12, 2022 |
| ASUSTek       | P8H77-M PRO                 | [16bee4f203](https://linux-hardware.org/?probe=16bee4f203) | Oct 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [f293609698](https://linux-hardware.org/?probe=f293609698) | Oct 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [ca3428ecf2](https://linux-hardware.org/?probe=ca3428ecf2) | Oct 12, 2022 |
| ASUSTek       | P8H67-M LE                  | [4f4f9e3cef](https://linux-hardware.org/?probe=4f4f9e3cef) | Oct 11, 2022 |
| ASUSTek       | P8Z77-V                     | [27b7798784](https://linux-hardware.org/?probe=27b7798784) | Oct 11, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [0e8d79a9a9](https://linux-hardware.org/?probe=0e8d79a9a9) | Oct 11, 2022 |
| Gigabyte      | X299X DESIGNARE 10G         | [fd590a067e](https://linux-hardware.org/?probe=fd590a067e) | Oct 10, 2022 |
| BESSTAR Te... | T3 MRD                      | [d223d492fe](https://linux-hardware.org/?probe=d223d492fe) | Oct 10, 2022 |
| Dell          | 0RW203                      | [306036aa6f](https://linux-hardware.org/?probe=306036aa6f) | Oct 10, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [9e82633709](https://linux-hardware.org/?probe=9e82633709) | Oct 10, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [dd3d3724d6](https://linux-hardware.org/?probe=dd3d3724d6) | Oct 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [2b7e826ffe](https://linux-hardware.org/?probe=2b7e826ffe) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [32d74cab14](https://linux-hardware.org/?probe=32d74cab14) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [abbdbe7e68](https://linux-hardware.org/?probe=abbdbe7e68) | Oct 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [c2193db5fb](https://linux-hardware.org/?probe=c2193db5fb) | Oct 09, 2022 |
| ASUSTek       | P5Q Premium                 | [8c0a201199](https://linux-hardware.org/?probe=8c0a201199) | Oct 09, 2022 |
| ECS           | A890GXM-A2                  | [d6f77b12c2](https://linux-hardware.org/?probe=d6f77b12c2) | Oct 09, 2022 |
| Intel         | DG965LV AAD36275-502        | [e46b9af4cb](https://linux-hardware.org/?probe=e46b9af4cb) | Oct 09, 2022 |
| ASRock        | 970M Pro3                   | [9eaf0bffca](https://linux-hardware.org/?probe=9eaf0bffca) | Oct 09, 2022 |
| ASUSTek       | P8H77-M PRO                 | [ec2b212e33](https://linux-hardware.org/?probe=ec2b212e33) | Oct 09, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [37068529a1](https://linux-hardware.org/?probe=37068529a1) | Oct 09, 2022 |
| Gigabyte      | F2A68HM-S1                  | [379f85dfb3](https://linux-hardware.org/?probe=379f85dfb3) | Oct 09, 2022 |
| Gigabyte      | F2A68HM-S1                  | [f02be8db4c](https://linux-hardware.org/?probe=f02be8db4c) | Oct 09, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [f80d633c86](https://linux-hardware.org/?probe=f80d633c86) | Oct 09, 2022 |
| Gigabyte      | GA-970A-D3                  | [b43b76907b](https://linux-hardware.org/?probe=b43b76907b) | Oct 08, 2022 |
| ASRock        | A320M-HDV R4.0              | [5793d73ce0](https://linux-hardware.org/?probe=5793d73ce0) | Oct 08, 2022 |
| Gigabyte      | B365M D3H-CF                | [2ad7a0c296](https://linux-hardware.org/?probe=2ad7a0c296) | Oct 08, 2022 |
| ASUSTek       | P8H67-M LE                  | [9cd069f242](https://linux-hardware.org/?probe=9cd069f242) | Oct 07, 2022 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [8ac874aef9](https://linux-hardware.org/?probe=8ac874aef9) | Oct 07, 2022 |
| ASRock        | B450M Pro4                  | [f1eaa7e9cc](https://linux-hardware.org/?probe=f1eaa7e9cc) | Oct 07, 2022 |
| ASRock        | 970M Pro3                   | [76d2eeb1d0](https://linux-hardware.org/?probe=76d2eeb1d0) | Oct 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [b457bc3cd2](https://linux-hardware.org/?probe=b457bc3cd2) | Oct 07, 2022 |
| Inventec      | DQ Class A02                | [08c66f26fe](https://linux-hardware.org/?probe=08c66f26fe) | Oct 07, 2022 |
| HP            | ProLiant ML110 Gen9         | [de23da6c1d](https://linux-hardware.org/?probe=de23da6c1d) | Oct 07, 2022 |
| MSI           | B550-A PRO                  | [364bf92a01](https://linux-hardware.org/?probe=364bf92a01) | Oct 07, 2022 |
| ASRock        | 970M Pro3                   | [9d6e9e9a08](https://linux-hardware.org/?probe=9d6e9e9a08) | Oct 07, 2022 |
| ASUSTek       | M3N78-VM                    | [828ba358e2](https://linux-hardware.org/?probe=828ba358e2) | Oct 06, 2022 |
| ASUSTek       | M3N78-VM                    | [6743600262](https://linux-hardware.org/?probe=6743600262) | Oct 06, 2022 |
| Lenovo        | 3853RN9                     | [4274c2b526](https://linux-hardware.org/?probe=4274c2b526) | Oct 06, 2022 |
| Lenovo        | 3853RN9                     | [41bfe2f107](https://linux-hardware.org/?probe=41bfe2f107) | Oct 06, 2022 |
| Gigabyte      | H87M-D3H                    | [8b9d7f32d1](https://linux-hardware.org/?probe=8b9d7f32d1) | Oct 06, 2022 |
| Dell          | 09KPNV A01                  | [6ad101df29](https://linux-hardware.org/?probe=6ad101df29) | Oct 06, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2423d31aeb](https://linux-hardware.org/?probe=2423d31aeb) | Oct 05, 2022 |
| MSI           | B450-A PRO                  | [5ff1f9c5c3](https://linux-hardware.org/?probe=5ff1f9c5c3) | Oct 05, 2022 |
| ASRock        | H61M-VG4                    | [7fe9bf7f20](https://linux-hardware.org/?probe=7fe9bf7f20) | Oct 05, 2022 |
| Gigabyte      | GA-MA69VM-S2                | [c6dd3eef5d](https://linux-hardware.org/?probe=c6dd3eef5d) | Oct 05, 2022 |
| MSI           | A320M-A PRO                 | [40dd630e96](https://linux-hardware.org/?probe=40dd630e96) | Oct 05, 2022 |
| MSI           | A520M-A PRO                 | [ce78c6c4ee](https://linux-hardware.org/?probe=ce78c6c4ee) | Oct 05, 2022 |
| Dell          | 088DT1 A00                  | [164b0caca9](https://linux-hardware.org/?probe=164b0caca9) | Oct 04, 2022 |
| Dell          | 088DT1 A01                  | [d2f8a7069b](https://linux-hardware.org/?probe=d2f8a7069b) | Oct 04, 2022 |
| MSI           | H81M-E34                    | [ddae6a50ce](https://linux-hardware.org/?probe=ddae6a50ce) | Oct 04, 2022 |
| HP            | 1497                        | [17a2f79f3f](https://linux-hardware.org/?probe=17a2f79f3f) | Oct 04, 2022 |
| HP            | 1497                        | [fab365512a](https://linux-hardware.org/?probe=fab365512a) | Oct 04, 2022 |
| ASUSTek       | G15DK                       | [3c8be02775](https://linux-hardware.org/?probe=3c8be02775) | Oct 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [9954860560](https://linux-hardware.org/?probe=9954860560) | Oct 04, 2022 |
| Biostar       | A960D+V2                    | [9199dbc3dc](https://linux-hardware.org/?probe=9199dbc3dc) | Oct 03, 2022 |
| ASUSTek       | G15DK                       | [76a03b7071](https://linux-hardware.org/?probe=76a03b7071) | Oct 03, 2022 |
| ASUSTek       | M3N-HT DELUXE               | [b278d1ade6](https://linux-hardware.org/?probe=b278d1ade6) | Oct 03, 2022 |
| ASUSTek       | P8Z68-V LX                  | [42b887e821](https://linux-hardware.org/?probe=42b887e821) | Oct 03, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [44c003007e](https://linux-hardware.org/?probe=44c003007e) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6209CM1    | [15fb3b5261](https://linux-hardware.org/?probe=15fb3b5261) | Oct 02, 2022 |
| MSI           | X570-A PRO                  | [ba513cf2ee](https://linux-hardware.org/?probe=ba513cf2ee) | Oct 02, 2022 |
| Apple         | Mac-F221BEC8                | [15ed095440](https://linux-hardware.org/?probe=15ed095440) | Oct 02, 2022 |
| MSI           | 970A-G43                    | [c8f6fa5b53](https://linux-hardware.org/?probe=c8f6fa5b53) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [7309d377f6](https://linux-hardware.org/?probe=7309d377f6) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | [aedfaab130](https://linux-hardware.org/?probe=aedfaab130) | Oct 02, 2022 |
| Unknown       | X79-P3                      | [9269fd5ff4](https://linux-hardware.org/?probe=9269fd5ff4) | Oct 01, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ff1c77c45a](https://linux-hardware.org/?probe=ff1c77c45a) | Oct 01, 2022 |
| Positivo      | POS-PIH81DL                 | [c17fe23ea7](https://linux-hardware.org/?probe=c17fe23ea7) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M58 9728AHG     | [a2bc7fc88f](https://linux-hardware.org/?probe=a2bc7fc88f) | Oct 01, 2022 |
| Dell          | 0RW203                      | [c8a408311d](https://linux-hardware.org/?probe=c8a408311d) | Oct 01, 2022 |
| ASUSTek       | B75M-A                      | [cbeab03cbd](https://linux-hardware.org/?probe=cbeab03cbd) | Oct 01, 2022 |
| Foxconn       | 2AB1                        | [18971aaf86](https://linux-hardware.org/?probe=18971aaf86) | Oct 01, 2022 |
| Apple         | Mac-F221BEC8                | [ab0a3e1a94](https://linux-hardware.org/?probe=ab0a3e1a94) | Sep 30, 2022 |
| Dell          | 0NK70N A03                  | [9cfa433855](https://linux-hardware.org/?probe=9cfa433855) | Sep 30, 2022 |
| ASUSTek       | P8H67-M                     | [583fe6d90d](https://linux-hardware.org/?probe=583fe6d90d) | Sep 30, 2022 |
| Lenovo        | ThinkCentre M58 9728AHG     | [773ae7f01e](https://linux-hardware.org/?probe=773ae7f01e) | Sep 30, 2022 |
| ASRock        | N68C-S UCC                  | [90d8579454](https://linux-hardware.org/?probe=90d8579454) | Sep 30, 2022 |
| Dell          | 0KJCC5 A00                  | [f9582eb0a8](https://linux-hardware.org/?probe=f9582eb0a8) | Sep 29, 2022 |
| HP            | 158A                        | [151ee8b7d6](https://linux-hardware.org/?probe=151ee8b7d6) | Sep 29, 2022 |
| HP            | 81C9                        | [c92ebd45a9](https://linux-hardware.org/?probe=c92ebd45a9) | Sep 29, 2022 |
| Acer          | Veriton X6610G              | [66733e59e2](https://linux-hardware.org/?probe=66733e59e2) | Sep 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [25e3064dd2](https://linux-hardware.org/?probe=25e3064dd2) | Sep 29, 2022 |
| Dell          | 0NK70N A03                  | [7e2d1b00fd](https://linux-hardware.org/?probe=7e2d1b00fd) | Sep 28, 2022 |
| Dell          | 06D7TR A02                  | [a0d832ff6a](https://linux-hardware.org/?probe=a0d832ff6a) | Sep 28, 2022 |
| MSI           | X299 SLI PLUS               | [1695ba8137](https://linux-hardware.org/?probe=1695ba8137) | Sep 28, 2022 |
| ASUSTek       | PRIME B450M-K               | [262a244d81](https://linux-hardware.org/?probe=262a244d81) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | [9b3c73c104](https://linux-hardware.org/?probe=9b3c73c104) | Sep 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | [4cdcef3ebd](https://linux-hardware.org/?probe=4cdcef3ebd) | Sep 28, 2022 |
| MSI           | B550-A PRO                  | [2a5a7aeb95](https://linux-hardware.org/?probe=2a5a7aeb95) | Sep 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [63cd838fcc](https://linux-hardware.org/?probe=63cd838fcc) | Sep 27, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1979013fa2](https://linux-hardware.org/?probe=1979013fa2) | Sep 27, 2022 |
| HP            | 8433 11                     | [a1d424bced](https://linux-hardware.org/?probe=a1d424bced) | Sep 27, 2022 |
| HP            | 802F                        | [12645dcde4](https://linux-hardware.org/?probe=12645dcde4) | Sep 27, 2022 |
| Dell          | 018D1Y A00                  | [744202f733](https://linux-hardware.org/?probe=744202f733) | Sep 26, 2022 |
| Biostar       | TH67XE                      | [24df0079b5](https://linux-hardware.org/?probe=24df0079b5) | Sep 26, 2022 |
| HP            | 1494                        | [aa2bd7da6c](https://linux-hardware.org/?probe=aa2bd7da6c) | Sep 26, 2022 |
| ASUSTek       | P5N7A-VM                    | [e8ac8a9926](https://linux-hardware.org/?probe=e8ac8a9926) | Sep 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [202e51c5d3](https://linux-hardware.org/?probe=202e51c5d3) | Sep 26, 2022 |
| MSI           | A68HM-E33 V2                | [939c0c0a19](https://linux-hardware.org/?probe=939c0c0a19) | Sep 25, 2022 |
| ASUSTek       | B150-PLUS                   | [c64181dd6a](https://linux-hardware.org/?probe=c64181dd6a) | Sep 25, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [dfdb7b73ae](https://linux-hardware.org/?probe=dfdb7b73ae) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [208c7988f7](https://linux-hardware.org/?probe=208c7988f7) | Sep 25, 2022 |
| HP            | 8433 11                     | [dffc61c155](https://linux-hardware.org/?probe=dffc61c155) | Sep 24, 2022 |
| HP            | 802F                        | [2390f9c154](https://linux-hardware.org/?probe=2390f9c154) | Sep 24, 2022 |
| ASUSTek       | Leonite2                    | [f7e1dc7c9d](https://linux-hardware.org/?probe=f7e1dc7c9d) | Sep 24, 2022 |
| ASUSTek       | Leonite2                    | [63d494787f](https://linux-hardware.org/?probe=63d494787f) | Sep 24, 2022 |
| ASRock        | 4CoreDual-SATA2             | [eb0e992df7](https://linux-hardware.org/?probe=eb0e992df7) | Sep 24, 2022 |
| Dell          | 0C7195                      | [9711ab00d7](https://linux-hardware.org/?probe=9711ab00d7) | Sep 24, 2022 |
| Gigabyte      | G31M-S2C                    | [d0aa96a903](https://linux-hardware.org/?probe=d0aa96a903) | Sep 24, 2022 |
| MSI           | H510M PRO                   | [bb7475d072](https://linux-hardware.org/?probe=bb7475d072) | Sep 24, 2022 |
| Lenovo        | NO DPK                      | [7bdaedd0f7](https://linux-hardware.org/?probe=7bdaedd0f7) | Sep 24, 2022 |
| Gateway       | IPISB-VR                    | [21ee50eb69](https://linux-hardware.org/?probe=21ee50eb69) | Sep 24, 2022 |
| ASUSTek       | P8B75-M LE                  | [8975676700](https://linux-hardware.org/?probe=8975676700) | Sep 24, 2022 |
| ASRock        | X399 Taichi                 | [e6de41eac0](https://linux-hardware.org/?probe=e6de41eac0) | Sep 24, 2022 |
| HP            | 8643 SMVB                   | [c2e100d58d](https://linux-hardware.org/?probe=c2e100d58d) | Sep 24, 2022 |
| HP            | 802F                        | [1b25932752](https://linux-hardware.org/?probe=1b25932752) | Sep 23, 2022 |
| HP            | 8055                        | [a45563167c](https://linux-hardware.org/?probe=a45563167c) | Sep 23, 2022 |
| Medion        | B460H6-EM                   | [9ab2a06631](https://linux-hardware.org/?probe=9ab2a06631) | Sep 23, 2022 |
| ASUSTek       | M2N68-AM SE2                | [412f70b76b](https://linux-hardware.org/?probe=412f70b76b) | Sep 23, 2022 |
| Medion        | H110H4-EM                   | [2fa25ddedf](https://linux-hardware.org/?probe=2fa25ddedf) | Sep 23, 2022 |
| Dell          | 0WR7PY A02                  | [0c47cbc25d](https://linux-hardware.org/?probe=0c47cbc25d) | Sep 23, 2022 |
| Medion        | H110H4-EM                   | [8e7d4a7aeb](https://linux-hardware.org/?probe=8e7d4a7aeb) | Sep 23, 2022 |
| Dell          | 0WR7PY A02                  | [53fc678043](https://linux-hardware.org/?probe=53fc678043) | Sep 23, 2022 |
| HP            | 0AA0h                       | [5757039d29](https://linux-hardware.org/?probe=5757039d29) | Sep 23, 2022 |
| MSI           | B350 PC MATE                | [0c4332eead](https://linux-hardware.org/?probe=0c4332eead) | Sep 23, 2022 |
| HP            | 1494                        | [cd3778e7eb](https://linux-hardware.org/?probe=cd3778e7eb) | Sep 22, 2022 |
| MSI           | 760GM-P34                   | [af750add66](https://linux-hardware.org/?probe=af750add66) | Sep 22, 2022 |
| HP            | 1494                        | [4a3ad3e89d](https://linux-hardware.org/?probe=4a3ad3e89d) | Sep 22, 2022 |
| ASUSTek       | M5A78L-M LX3                | [75a6fc3a08](https://linux-hardware.org/?probe=75a6fc3a08) | Sep 22, 2022 |
| Gigabyte      | 945GM-S2                    | [9fcea940e6](https://linux-hardware.org/?probe=9fcea940e6) | Sep 22, 2022 |
| Gigabyte      | 990FXA-UD5                  | [7c8d5609e0](https://linux-hardware.org/?probe=7c8d5609e0) | Sep 22, 2022 |
| ASUSTek       | P5B                         | [f265d37bf5](https://linux-hardware.org/?probe=f265d37bf5) | Sep 22, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [e1af6b9e74](https://linux-hardware.org/?probe=e1af6b9e74) | Sep 22, 2022 |
| OEM           | B75 Ver:1.41                | [e22d2bac17](https://linux-hardware.org/?probe=e22d2bac17) | Sep 22, 2022 |
| HP            | 802F                        | [1f4d3353d2](https://linux-hardware.org/?probe=1f4d3353d2) | Sep 22, 2022 |
| ASUSTek       | PRIME Z390-A                | [5e4d865987](https://linux-hardware.org/?probe=5e4d865987) | Sep 21, 2022 |
| HP            | 1494                        | [5018a8dade](https://linux-hardware.org/?probe=5018a8dade) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | [67067bfc09](https://linux-hardware.org/?probe=67067bfc09) | Sep 21, 2022 |
| Gigabyte      | Z590 UD AC                  | [3add13cf6d](https://linux-hardware.org/?probe=3add13cf6d) | Sep 21, 2022 |
| Dell          | 0773VG A02                  | [84f143d4ea](https://linux-hardware.org/?probe=84f143d4ea) | Sep 21, 2022 |
| Dell          | 0D6H9T A00                  | [63b718ac3a](https://linux-hardware.org/?probe=63b718ac3a) | Sep 21, 2022 |
| ASUSTek       | PRIME B450M-A               | [2ac923fd8c](https://linux-hardware.org/?probe=2ac923fd8c) | Sep 21, 2022 |
| Dell          | 0D6H9T A00                  | [90437079a3](https://linux-hardware.org/?probe=90437079a3) | Sep 20, 2022 |
| Digiboard     | NM70-TI                     | [ace83d527c](https://linux-hardware.org/?probe=ace83d527c) | Sep 20, 2022 |
| ASUSTek       | Z97-A                       | [cc9467d0fe](https://linux-hardware.org/?probe=cc9467d0fe) | Sep 20, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [94d45ff789](https://linux-hardware.org/?probe=94d45ff789) | Sep 19, 2022 |
| HP            | 81C9                        | [3795beb1c4](https://linux-hardware.org/?probe=3795beb1c4) | Sep 19, 2022 |
| Intel         | DH61BF AAG81311-101         | [43c2f57807](https://linux-hardware.org/?probe=43c2f57807) | Sep 19, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [aba8915769](https://linux-hardware.org/?probe=aba8915769) | Sep 19, 2022 |
| Intel         | DG33BU AAD79951-407         | [d35104af13](https://linux-hardware.org/?probe=d35104af13) | Sep 19, 2022 |
| Gigabyte      | H97M-D3H                    | [57db36ecc9](https://linux-hardware.org/?probe=57db36ecc9) | Sep 19, 2022 |
| HP            | 0AA8h                       | [3c274fc7f3](https://linux-hardware.org/?probe=3c274fc7f3) | Sep 19, 2022 |
| Wistron       | ProLiant ML110 G6           | [c986542d56](https://linux-hardware.org/?probe=c986542d56) | Sep 18, 2022 |
| Wistron       | ProLiant ML110 G6           | [a17cc62b40](https://linux-hardware.org/?probe=a17cc62b40) | Sep 18, 2022 |
| Gigabyte      | H61M-DS2                    | [3a2c9cfad3](https://linux-hardware.org/?probe=3a2c9cfad3) | Sep 18, 2022 |
| Gigabyte      | F2A88X-D3H                  | [55ab1865a0](https://linux-hardware.org/?probe=55ab1865a0) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | [916e9d7e5e](https://linux-hardware.org/?probe=916e9d7e5e) | Sep 18, 2022 |
| HP            | 18E7                        | [710a40851e](https://linux-hardware.org/?probe=710a40851e) | Sep 18, 2022 |
| ASUSTek       | P5G41T-M LX                 | [50647a7656](https://linux-hardware.org/?probe=50647a7656) | Sep 17, 2022 |
| Foxconn       | G31MXP FAB:1.1              | [d401319e57](https://linux-hardware.org/?probe=d401319e57) | Sep 17, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [b3350b3f69](https://linux-hardware.org/?probe=b3350b3f69) | Sep 17, 2022 |
| Intel         | X79M-S                      | [91e75d3183](https://linux-hardware.org/?probe=91e75d3183) | Sep 17, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [b9693eaf7c](https://linux-hardware.org/?probe=b9693eaf7c) | Sep 17, 2022 |
| Intel         | X79M-S                      | [48c5f5ed77](https://linux-hardware.org/?probe=48c5f5ed77) | Sep 17, 2022 |
| ASUSTek       | P5K                         | [4cf17a7b6f](https://linux-hardware.org/?probe=4cf17a7b6f) | Sep 17, 2022 |
| ASUSTek       | P5K                         | [4a3727841e](https://linux-hardware.org/?probe=4a3727841e) | Sep 17, 2022 |
| Dell          | 0F5C5X A00                  | [db1c09a2cc](https://linux-hardware.org/?probe=db1c09a2cc) | Sep 16, 2022 |
| System76      | Thelio Mira thelio-mira-... | [e5e20422fd](https://linux-hardware.org/?probe=e5e20422fd) | Sep 16, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e6fe8aa148](https://linux-hardware.org/?probe=e6fe8aa148) | Sep 16, 2022 |
| ASUSTek       | P5B                         | [37bf9261b4](https://linux-hardware.org/?probe=37bf9261b4) | Sep 16, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [26699f7431](https://linux-hardware.org/?probe=26699f7431) | Sep 16, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [b8262094b0](https://linux-hardware.org/?probe=b8262094b0) | Sep 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c99c4f9785](https://linux-hardware.org/?probe=c99c4f9785) | Sep 15, 2022 |
| AZW           | GK mini                     | [19b8b4dc85](https://linux-hardware.org/?probe=19b8b4dc85) | Sep 15, 2022 |
| ASUSTek       | H81M-K                      | [fe48912653](https://linux-hardware.org/?probe=fe48912653) | Sep 15, 2022 |
| ASUSTek       | H81M-K                      | [a6bc49b4f3](https://linux-hardware.org/?probe=a6bc49b4f3) | Sep 15, 2022 |
| HP            | 18E6                        | [d95bebd7fe](https://linux-hardware.org/?probe=d95bebd7fe) | Sep 15, 2022 |
| HP            | 339A                        | [78e4f67b19](https://linux-hardware.org/?probe=78e4f67b19) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | [b05bacb493](https://linux-hardware.org/?probe=b05bacb493) | Sep 14, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [87f0f15c82](https://linux-hardware.org/?probe=87f0f15c82) | Sep 14, 2022 |
| Intel         | DH67BL AAG10189-209         | [3507c0cdb7](https://linux-hardware.org/?probe=3507c0cdb7) | Sep 14, 2022 |
| HP            | 18E6                        | [261f9e8c10](https://linux-hardware.org/?probe=261f9e8c10) | Sep 14, 2022 |
| AZW           | Green G2                    | [b52a17d2b2](https://linux-hardware.org/?probe=b52a17d2b2) | Sep 14, 2022 |
| ASUSTek       | P5B                         | [ae8f6e2ed7](https://linux-hardware.org/?probe=ae8f6e2ed7) | Sep 14, 2022 |
| Gigabyte      | B365M H                     | [20125b1c13](https://linux-hardware.org/?probe=20125b1c13) | Sep 13, 2022 |
| ASUSTek       | PRIME B350M-A               | [47b0975057](https://linux-hardware.org/?probe=47b0975057) | Sep 13, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | [70aa78efc6](https://linux-hardware.org/?probe=70aa78efc6) | Sep 13, 2022 |
| ASUSTek       | H81M-K                      | [19ddc4ed5d](https://linux-hardware.org/?probe=19ddc4ed5d) | Sep 13, 2022 |
| ASRock        | Z77 Pro4-M                  | [38928465ac](https://linux-hardware.org/?probe=38928465ac) | Sep 13, 2022 |
| Dell          | 0P01GV A03                  | [f23afc903c](https://linux-hardware.org/?probe=f23afc903c) | Sep 13, 2022 |
| ASUSTek       | PRIME B550M-A               | [fd2497acae](https://linux-hardware.org/?probe=fd2497acae) | Sep 12, 2022 |
| Gigabyte      | AX370-Gaming K3             | [e3720a691a](https://linux-hardware.org/?probe=e3720a691a) | Sep 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b251a95678](https://linux-hardware.org/?probe=b251a95678) | Sep 12, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [00bca0eeff](https://linux-hardware.org/?probe=00bca0eeff) | Sep 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b3c2018879](https://linux-hardware.org/?probe=b3c2018879) | Sep 12, 2022 |
| PCWare        | IPMH61R3                    | [2312ab0f92](https://linux-hardware.org/?probe=2312ab0f92) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [2391f4673a](https://linux-hardware.org/?probe=2391f4673a) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [89963f6bf1](https://linux-hardware.org/?probe=89963f6bf1) | Sep 12, 2022 |
| Gigabyte      | H61MS                       | [9b10176111](https://linux-hardware.org/?probe=9b10176111) | Sep 12, 2022 |
| Gigabyte      | H81M-D2V                    | [6da1838df1](https://linux-hardware.org/?probe=6da1838df1) | Sep 12, 2022 |
| Unknown       | Unknown                     | [637418c4f3](https://linux-hardware.org/?probe=637418c4f3) | Sep 12, 2022 |
| ASUSTek       | PRIME X370-PRO              | [2228f0dc13](https://linux-hardware.org/?probe=2228f0dc13) | Sep 12, 2022 |
| HP            | 8464                        | [50cb2002e6](https://linux-hardware.org/?probe=50cb2002e6) | Sep 12, 2022 |
| ECS           | G31T-M9                     | [547762d8bf](https://linux-hardware.org/?probe=547762d8bf) | Sep 11, 2022 |
| Dell          | 09KPNV A00                  | [7063a1b842](https://linux-hardware.org/?probe=7063a1b842) | Sep 11, 2022 |
| Dell          | 09KPNV A00                  | [8d243eeb2a](https://linux-hardware.org/?probe=8d243eeb2a) | Sep 11, 2022 |
| Gigabyte      | H61M-DS2                    | [105dae5731](https://linux-hardware.org/?probe=105dae5731) | Sep 11, 2022 |
| Pegatron      | Benicia                     | [1f8dceb256](https://linux-hardware.org/?probe=1f8dceb256) | Sep 11, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [c7eb1fd4ca](https://linux-hardware.org/?probe=c7eb1fd4ca) | Sep 11, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4df5d0194d](https://linux-hardware.org/?probe=4df5d0194d) | Sep 11, 2022 |
| Foxconn       | 2AA9                        | [b671b09c1a](https://linux-hardware.org/?probe=b671b09c1a) | Sep 11, 2022 |
| HP            | ProLiant MicroServer        | [a36990dcf7](https://linux-hardware.org/?probe=a36990dcf7) | Sep 10, 2022 |
| ASUSTek       | P5N7A-VM                    | [ac23f75aa7](https://linux-hardware.org/?probe=ac23f75aa7) | Sep 10, 2022 |
| ECS           | H61H2-M6                    | [99f3146843](https://linux-hardware.org/?probe=99f3146843) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [d79e449b58](https://linux-hardware.org/?probe=d79e449b58) | Sep 10, 2022 |
| ASUSTek       | M5A78L/USB3                 | [49158d0782](https://linux-hardware.org/?probe=49158d0782) | Sep 10, 2022 |
| MSI           | B550-A PRO                  | [f1bdda02e5](https://linux-hardware.org/?probe=f1bdda02e5) | Sep 10, 2022 |
| ASUSTek       | H81M-E                      | [1a9835fb13](https://linux-hardware.org/?probe=1a9835fb13) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5aa9031e93](https://linux-hardware.org/?probe=5aa9031e93) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [81fcfbb095](https://linux-hardware.org/?probe=81fcfbb095) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | [1d6ec4fb3b](https://linux-hardware.org/?probe=1d6ec4fb3b) | Sep 10, 2022 |
| HP            | ProLiant MicroServer        | [6d58a3f327](https://linux-hardware.org/?probe=6d58a3f327) | Sep 09, 2022 |
| HP            | ProLiant MicroServer        | [08e7851933](https://linux-hardware.org/?probe=08e7851933) | Sep 09, 2022 |
| Gigabyte      | X570 AORUS PRO              | [8d1d861b1c](https://linux-hardware.org/?probe=8d1d861b1c) | Sep 09, 2022 |
| Dell          | 0P01GV A03                  | [d71609c89e](https://linux-hardware.org/?probe=d71609c89e) | Sep 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [951a99cc8f](https://linux-hardware.org/?probe=951a99cc8f) | Sep 09, 2022 |
| Dell          | 0C7195                      | [728b74ef0c](https://linux-hardware.org/?probe=728b74ef0c) | Sep 09, 2022 |
| Dell          | 08NPPY A00                  | [55cf772a79](https://linux-hardware.org/?probe=55cf772a79) | Sep 09, 2022 |
| MSI           | MS-7817                     | [99a24afc9e](https://linux-hardware.org/?probe=99a24afc9e) | Sep 09, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [2c39df8b9f](https://linux-hardware.org/?probe=2c39df8b9f) | Sep 08, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [246c6ed8a6](https://linux-hardware.org/?probe=246c6ed8a6) | Sep 08, 2022 |
| Packard Be... | IMEDIA S2883                | [c4fe9ee6f0](https://linux-hardware.org/?probe=c4fe9ee6f0) | Sep 08, 2022 |
| Acer          | Aspire TC-895 V:1.0         | [04b2bf9115](https://linux-hardware.org/?probe=04b2bf9115) | Sep 08, 2022 |
| Gigabyte      | H310M S2P                   | [aaab0c5335](https://linux-hardware.org/?probe=aaab0c5335) | Sep 08, 2022 |
| ASUSTek       | PRIME B450M-K II            | [c7a272ed96](https://linux-hardware.org/?probe=c7a272ed96) | Sep 08, 2022 |
| Pegatron      | Benicia                     | [95339a1bdd](https://linux-hardware.org/?probe=95339a1bdd) | Sep 08, 2022 |
| Gigabyte      | M68MT-S2                    | [86af6e4676](https://linux-hardware.org/?probe=86af6e4676) | Sep 08, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a355222b61](https://linux-hardware.org/?probe=a355222b61) | Sep 07, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [a45b18c4bb](https://linux-hardware.org/?probe=a45b18c4bb) | Sep 07, 2022 |
| Dell          | 0JCTF8 A00                  | [7a0145000a](https://linux-hardware.org/?probe=7a0145000a) | Sep 07, 2022 |
| Dell          | 0DR845                      | [f945fc3f5e](https://linux-hardware.org/?probe=f945fc3f5e) | Sep 07, 2022 |
| Dell          | 0M863N A01                  | [a353883ee2](https://linux-hardware.org/?probe=a353883ee2) | Sep 07, 2022 |
| MSI           | Z170A GAMING PRO            | [e690f6c747](https://linux-hardware.org/?probe=e690f6c747) | Sep 06, 2022 |
| MSI           | Z97 PC Mate                 | [512c793b51](https://linux-hardware.org/?probe=512c793b51) | Sep 06, 2022 |
| MSI           | 760GM-P21                   | [c3eb52f6ab](https://linux-hardware.org/?probe=c3eb52f6ab) | Sep 06, 2022 |
| HP            | 8265                        | [2b74e032bd](https://linux-hardware.org/?probe=2b74e032bd) | Sep 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | [bcdb385277](https://linux-hardware.org/?probe=bcdb385277) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [ab4f06e457](https://linux-hardware.org/?probe=ab4f06e457) | Sep 05, 2022 |
| ASUSTek       | H81M-PLUS                   | [826b486f77](https://linux-hardware.org/?probe=826b486f77) | Sep 05, 2022 |
| HP            | 8265                        | [f7f460fb43](https://linux-hardware.org/?probe=f7f460fb43) | Sep 05, 2022 |
| ASUSTek       | P9X79 DELUXE                | [2aa7ada396](https://linux-hardware.org/?probe=2aa7ada396) | Sep 05, 2022 |
| Gigabyte      | Z690 AERO G DDR4            | [ccd383a106](https://linux-hardware.org/?probe=ccd383a106) | Sep 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2176e4d70f](https://linux-hardware.org/?probe=2176e4d70f) | Sep 05, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [1f5b368c96](https://linux-hardware.org/?probe=1f5b368c96) | Sep 05, 2022 |
| Gigabyte      | GA-M56S-S3                  | [8b8ba6c7f9](https://linux-hardware.org/?probe=8b8ba6c7f9) | Sep 05, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [9cd2bcff37](https://linux-hardware.org/?probe=9cd2bcff37) | Sep 04, 2022 |
| AMI           | Cherry Trail CR             | [63136bf463](https://linux-hardware.org/?probe=63136bf463) | Sep 04, 2022 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | [ed16086671](https://linux-hardware.org/?probe=ed16086671) | Sep 04, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | [0859dbdb1c](https://linux-hardware.org/?probe=0859dbdb1c) | Sep 04, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [106bdf4d1b](https://linux-hardware.org/?probe=106bdf4d1b) | Sep 04, 2022 |
| Intel         | DQ67SW AAG12527-306         | [9ab6c11be2](https://linux-hardware.org/?probe=9ab6c11be2) | Sep 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [312013ef36](https://linux-hardware.org/?probe=312013ef36) | Sep 03, 2022 |
| Gigabyte      | B560 HD3                    | [35c081a440](https://linux-hardware.org/?probe=35c081a440) | Sep 03, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [14af0852b9](https://linux-hardware.org/?probe=14af0852b9) | Sep 03, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [6c80288d39](https://linux-hardware.org/?probe=6c80288d39) | Sep 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [709825bde3](https://linux-hardware.org/?probe=709825bde3) | Sep 03, 2022 |
| MSI           | H170 GAMING M3              | [b0d669cf4b](https://linux-hardware.org/?probe=b0d669cf4b) | Sep 03, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c13f075f83](https://linux-hardware.org/?probe=c13f075f83) | Sep 03, 2022 |
| ASRock        | 4CoreDual-SATA2             | [c64d84d331](https://linux-hardware.org/?probe=c64d84d331) | Sep 03, 2022 |
| Intel         | X79M-S                      | [a435283f55](https://linux-hardware.org/?probe=a435283f55) | Sep 03, 2022 |
| HP            | 2AF3                        | [58eae39fe2](https://linux-hardware.org/?probe=58eae39fe2) | Sep 03, 2022 |
| ASUSTek       | PRIME Z270-A                | [e742b2e06c](https://linux-hardware.org/?probe=e742b2e06c) | Sep 03, 2022 |
| ASRock        | Q1900-ITX                   | [3f3708d874](https://linux-hardware.org/?probe=3f3708d874) | Sep 02, 2022 |
| ASRock        | A520M-HVS                   | [69253a16ad](https://linux-hardware.org/?probe=69253a16ad) | Sep 02, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | [b765d1e662](https://linux-hardware.org/?probe=b765d1e662) | Sep 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [a2878122de](https://linux-hardware.org/?probe=a2878122de) | Sep 01, 2022 |
| Gigabyte      | Z370 HD3-OP-CF              | [55f8dbfb24](https://linux-hardware.org/?probe=55f8dbfb24) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [836d60c547](https://linux-hardware.org/?probe=836d60c547) | Sep 01, 2022 |
| Gigabyte      | Z370 HD3-OP-CF              | [ead5d021a7](https://linux-hardware.org/?probe=ead5d021a7) | Sep 01, 2022 |
| Gigabyte      | Z97-HD3                     | [32e71c2905](https://linux-hardware.org/?probe=32e71c2905) | Sep 01, 2022 |
| HP            | 1589                        | [fce9004571](https://linux-hardware.org/?probe=fce9004571) | Sep 01, 2022 |
| MSI           | H110M GAMING                | [2699df47df](https://linux-hardware.org/?probe=2699df47df) | Sep 01, 2022 |
| HP            | 3398                        | [8b5bad68cb](https://linux-hardware.org/?probe=8b5bad68cb) | Sep 01, 2022 |
| Gigabyte      | 990FXA-UD5                  | [e5364d8761](https://linux-hardware.org/?probe=e5364d8761) | Sep 01, 2022 |
| ECS           | H61H2-M2                    | [9735a8ef90](https://linux-hardware.org/?probe=9735a8ef90) | Sep 01, 2022 |
| Unknown       | HX90                        | [71295a28ed](https://linux-hardware.org/?probe=71295a28ed) | Sep 01, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [ea730c9b2d](https://linux-hardware.org/?probe=ea730c9b2d) | Sep 01, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [d98546fd95](https://linux-hardware.org/?probe=d98546fd95) | Aug 31, 2022 |
| Dell          | 0R092H                      | [1a3a337c23](https://linux-hardware.org/?probe=1a3a337c23) | Aug 31, 2022 |
| JGINYUE       | B85I PLUS V2.1              | [d171691ef3](https://linux-hardware.org/?probe=d171691ef3) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [1f8274de5a](https://linux-hardware.org/?probe=1f8274de5a) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [567bf4b44a](https://linux-hardware.org/?probe=567bf4b44a) | Aug 31, 2022 |
| ASUSTek       | GL10DH                      | [c197df704f](https://linux-hardware.org/?probe=c197df704f) | Aug 31, 2022 |
| HP            | 805A                        | [477936d851](https://linux-hardware.org/?probe=477936d851) | Aug 30, 2022 |
| ASRock        | N68-S UCC                   | [1d38f1f08e](https://linux-hardware.org/?probe=1d38f1f08e) | Aug 30, 2022 |
| ASUSTek       | M2N-TE                      | [82e7cc26e7](https://linux-hardware.org/?probe=82e7cc26e7) | Aug 30, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [70ee26740a](https://linux-hardware.org/?probe=70ee26740a) | Aug 30, 2022 |
| HP            | 2B36                        | [c6de6225af](https://linux-hardware.org/?probe=c6de6225af) | Aug 29, 2022 |
| OEM           | G41 775 ICH7 8712           | [4225df6517](https://linux-hardware.org/?probe=4225df6517) | Aug 29, 2022 |
| Gigabyte      | B365M D3H-CF                | [4a96f9e792](https://linux-hardware.org/?probe=4a96f9e792) | Aug 29, 2022 |
| Medion        | Cattle24 1M                 | [eb19c533e0](https://linux-hardware.org/?probe=eb19c533e0) | Aug 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [7a2c713719](https://linux-hardware.org/?probe=7a2c713719) | Aug 29, 2022 |
| ASRock        | N68-S                       | [9d18792f64](https://linux-hardware.org/?probe=9d18792f64) | Aug 29, 2022 |
| MSI           | MAG B550M MORTAR            | [82ff6d598a](https://linux-hardware.org/?probe=82ff6d598a) | Aug 29, 2022 |
| OEM           | Intel H81                   | [8732ebea02](https://linux-hardware.org/?probe=8732ebea02) | Aug 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [c7ace10271](https://linux-hardware.org/?probe=c7ace10271) | Aug 28, 2022 |
| Gigabyte      | GA-870A-UD3                 | [809a84e36c](https://linux-hardware.org/?probe=809a84e36c) | Aug 28, 2022 |
| Gigabyte      | GA-870A-UD3                 | [d037b5e961](https://linux-hardware.org/?probe=d037b5e961) | Aug 28, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [17e8c1560b](https://linux-hardware.org/?probe=17e8c1560b) | Aug 28, 2022 |
| Acer          | Aspire TC-780               | [eba35d616c](https://linux-hardware.org/?probe=eba35d616c) | Aug 28, 2022 |
| Unknown       | 1.0                         | [38ebf9fce3](https://linux-hardware.org/?probe=38ebf9fce3) | Aug 28, 2022 |
| Shuttle       | XH310V2                     | [375b995195](https://linux-hardware.org/?probe=375b995195) | Aug 28, 2022 |
| Gigabyte      | A320M-S2H-CF                | [b7ebc75f83](https://linux-hardware.org/?probe=b7ebc75f83) | Aug 28, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [942675a80c](https://linux-hardware.org/?probe=942675a80c) | Aug 28, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [273e1c9459](https://linux-hardware.org/?probe=273e1c9459) | Aug 27, 2022 |
| HP            | 2820h                       | [66e45394e9](https://linux-hardware.org/?probe=66e45394e9) | Aug 27, 2022 |
| Gigabyte      | M61PME-S2                   | [8f8107b683](https://linux-hardware.org/?probe=8f8107b683) | Aug 27, 2022 |
| ASUSTek       | Z170-K                      | [137641269c](https://linux-hardware.org/?probe=137641269c) | Aug 27, 2022 |
| Gigabyte      | M61PME-S2                   | [e3b89ab2db](https://linux-hardware.org/?probe=e3b89ab2db) | Aug 27, 2022 |
| Gigabyte      | Z490 UD                     | [a872472b1c](https://linux-hardware.org/?probe=a872472b1c) | Aug 26, 2022 |
| ECS           | H61H2-M2                    | [72ebc08e0c](https://linux-hardware.org/?probe=72ebc08e0c) | Aug 26, 2022 |
| ASUSTek       | M5A78L-M LX                 | [5efc5cdd53](https://linux-hardware.org/?probe=5efc5cdd53) | Aug 25, 2022 |
| ASUSTek       | Benicia                     | [08f930384d](https://linux-hardware.org/?probe=08f930384d) | Aug 25, 2022 |
| ASRock        | FM2A68M-DG3+                | [9076ba4635](https://linux-hardware.org/?probe=9076ba4635) | Aug 25, 2022 |
| ASRock        | FM2A68M-DG3+                | [6190b5c039](https://linux-hardware.org/?probe=6190b5c039) | Aug 25, 2022 |
| Lenovo        | SHARKBAY 0B98405 STD        | [f8f9cd2bfc](https://linux-hardware.org/?probe=f8f9cd2bfc) | Aug 25, 2022 |
| OEM           | Intel H81                   | [cbedace60c](https://linux-hardware.org/?probe=cbedace60c) | Aug 25, 2022 |
| MSI           | MS-7369                     | [3f701de216](https://linux-hardware.org/?probe=3f701de216) | Aug 25, 2022 |
| MSI           | H110M GAMING                | [67b7ccfcb9](https://linux-hardware.org/?probe=67b7ccfcb9) | Aug 25, 2022 |
| HP            | 18E4                        | [13d5c6848a](https://linux-hardware.org/?probe=13d5c6848a) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [94446a9884](https://linux-hardware.org/?probe=94446a9884) | Aug 24, 2022 |
| ASRock        | Z87 Extreme4                | [c1c23ef82f](https://linux-hardware.org/?probe=c1c23ef82f) | Aug 24, 2022 |
| ASUSTek       | P5B                         | [27c91a4b60](https://linux-hardware.org/?probe=27c91a4b60) | Aug 24, 2022 |
| HP            | 1906                        | [b26f30eca5](https://linux-hardware.org/?probe=b26f30eca5) | Aug 24, 2022 |
| IBASE Tech... | MI970VFA                    | [27fc0d8773](https://linux-hardware.org/?probe=27fc0d8773) | Aug 24, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | [b5e5debf66](https://linux-hardware.org/?probe=b5e5debf66) | Aug 24, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [d396a491c2](https://linux-hardware.org/?probe=d396a491c2) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a8eb4233e8](https://linux-hardware.org/?probe=a8eb4233e8) | Aug 23, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [bb84a4e155](https://linux-hardware.org/?probe=bb84a4e155) | Aug 23, 2022 |
| ASUSTek       | H61M-C                      | [93ac400083](https://linux-hardware.org/?probe=93ac400083) | Aug 23, 2022 |
| ASUSTek       | VC66-C2                     | [f2f42bd538](https://linux-hardware.org/?probe=f2f42bd538) | Aug 23, 2022 |
| ASUSTek       | Z97-P                       | [bcd3bcb389](https://linux-hardware.org/?probe=bcd3bcb389) | Aug 22, 2022 |
| MSI           | P41T-C31                    | [f8487b4fdb](https://linux-hardware.org/?probe=f8487b4fdb) | Aug 22, 2022 |
| ASUSTek       | H110M-A/M.2                 | [dab0f526b0](https://linux-hardware.org/?probe=dab0f526b0) | Aug 22, 2022 |
| ASUSTek       | H61M-C                      | [8d187f0a28](https://linux-hardware.org/?probe=8d187f0a28) | Aug 22, 2022 |
| ASRock        | G41M-VS3                    | [659ccaca6e](https://linux-hardware.org/?probe=659ccaca6e) | Aug 22, 2022 |
| Dell          | 0T10XW A01                  | [30ebde5edc](https://linux-hardware.org/?probe=30ebde5edc) | Aug 21, 2022 |
| HP            | 2B36                        | [9890b96e0e](https://linux-hardware.org/?probe=9890b96e0e) | Aug 21, 2022 |
| MSI           | B550-A PRO                  | [421874f76a](https://linux-hardware.org/?probe=421874f76a) | Aug 21, 2022 |
| ECS           | H61H2-M2                    | [97ec1c67e8](https://linux-hardware.org/?probe=97ec1c67e8) | Aug 21, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [066815dcef](https://linux-hardware.org/?probe=066815dcef) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [aaf726faa0](https://linux-hardware.org/?probe=aaf726faa0) | Aug 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [ed2076bba5](https://linux-hardware.org/?probe=ed2076bba5) | Aug 20, 2022 |
| ASRock        | FM2A88X-ITX+                | [44940c79b7](https://linux-hardware.org/?probe=44940c79b7) | Aug 20, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [d5e91a17b8](https://linux-hardware.org/?probe=d5e91a17b8) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-K II            | [6b101e9381](https://linux-hardware.org/?probe=6b101e9381) | Aug 19, 2022 |
| HP            | 097Ch                       | [ac391817bc](https://linux-hardware.org/?probe=ac391817bc) | Aug 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [2494475fe0](https://linux-hardware.org/?probe=2494475fe0) | Aug 19, 2022 |
| Intel         | DH87RL AAG74240-401         | [ebc0328fe0](https://linux-hardware.org/?probe=ebc0328fe0) | Aug 19, 2022 |
| Acer          | Aspire XC-830               | [b3e0135d65](https://linux-hardware.org/?probe=b3e0135d65) | Aug 19, 2022 |
| MSI           | MS-7528                     | [723f567e19](https://linux-hardware.org/?probe=723f567e19) | Aug 19, 2022 |
| MSI           | MS-7528                     | [4d549f68ce](https://linux-hardware.org/?probe=4d549f68ce) | Aug 19, 2022 |
| ASUSTek       | H81M-E                      | [2b0b66767d](https://linux-hardware.org/?probe=2b0b66767d) | Aug 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX         | [49943f84c8](https://linux-hardware.org/?probe=49943f84c8) | Aug 18, 2022 |
| MSI           | B350M MORTAR                | [d1c6be49c4](https://linux-hardware.org/?probe=d1c6be49c4) | Aug 18, 2022 |
| Dell          | 05XGC8 A00                  | [43741daa2d](https://linux-hardware.org/?probe=43741daa2d) | Aug 18, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [02f9463f2b](https://linux-hardware.org/?probe=02f9463f2b) | Aug 17, 2022 |
| ASRock        | 775Dual-VSTA                | [89ac2bb6fe](https://linux-hardware.org/?probe=89ac2bb6fe) | Aug 17, 2022 |
| HP            | 872B                        | [466f4962fe](https://linux-hardware.org/?probe=466f4962fe) | Aug 17, 2022 |
| ASUSTek       | P8B75-M LX                  | [1efeb7be2c](https://linux-hardware.org/?probe=1efeb7be2c) | Aug 17, 2022 |
| Intel         | DH87RL AAG74240-401         | [a8c5b732f4](https://linux-hardware.org/?probe=a8c5b732f4) | Aug 17, 2022 |
| Dell          | 0GY6Y8 A02                  | [caf9167ca7](https://linux-hardware.org/?probe=caf9167ca7) | Aug 16, 2022 |
| Dell          | 0GY6Y8 A02                  | [6d1b561c11](https://linux-hardware.org/?probe=6d1b561c11) | Aug 16, 2022 |
| HP            | 0B54h D                     | [2d1764e553](https://linux-hardware.org/?probe=2d1764e553) | Aug 16, 2022 |
| Gigabyte      | H81M-D2V                    | [aa03343ca1](https://linux-hardware.org/?probe=aa03343ca1) | Aug 16, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [9e3fd854a1](https://linux-hardware.org/?probe=9e3fd854a1) | Aug 16, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [8f472765f9](https://linux-hardware.org/?probe=8f472765f9) | Aug 16, 2022 |
| Gigabyte      | B450M GAMING                | [a3d9fca7aa](https://linux-hardware.org/?probe=a3d9fca7aa) | Aug 16, 2022 |
| AZW           | Green G2                    | [56c93e6508](https://linux-hardware.org/?probe=56c93e6508) | Aug 16, 2022 |
| ECS           | H61H2-WM                    | [64b79fd126](https://linux-hardware.org/?probe=64b79fd126) | Aug 15, 2022 |
| ASUSTek       | P5G41T-M LX3                | [0aefa0613d](https://linux-hardware.org/?probe=0aefa0613d) | Aug 15, 2022 |
| ASUSTek       | P5G41T-M LX3                | [d000ce4d8c](https://linux-hardware.org/?probe=d000ce4d8c) | Aug 15, 2022 |
| MSI           | H61M-P20                    | [9adc2fa427](https://linux-hardware.org/?probe=9adc2fa427) | Aug 15, 2022 |
| ASUSTek       | P7P55D                      | [cd43fbf16a](https://linux-hardware.org/?probe=cd43fbf16a) | Aug 15, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [7ff7caebc5](https://linux-hardware.org/?probe=7ff7caebc5) | Aug 15, 2022 |
| ASUSTek       | P5K SE                      | [59168fc3cb](https://linux-hardware.org/?probe=59168fc3cb) | Aug 14, 2022 |
| ASRock        | FM2A55M-HD+                 | [dc086ed32c](https://linux-hardware.org/?probe=dc086ed32c) | Aug 14, 2022 |
| Gigabyte      | H81M-D2V                    | [76ab505e7c](https://linux-hardware.org/?probe=76ab505e7c) | Aug 14, 2022 |
| ASRock        | J4125B-ITX                  | [81a8491905](https://linux-hardware.org/?probe=81a8491905) | Aug 14, 2022 |
| ASRock        | FM2A55M-HD+                 | [6c7f56d3cd](https://linux-hardware.org/?probe=6c7f56d3cd) | Aug 14, 2022 |
| MSI           | Boston                      | [aa89e501bd](https://linux-hardware.org/?probe=aa89e501bd) | Aug 14, 2022 |
| MSI           | H510M PRO                   | [30a01dd713](https://linux-hardware.org/?probe=30a01dd713) | Aug 14, 2022 |
| ASUSTek       | PRIME B550M-A               | [bd04485397](https://linux-hardware.org/?probe=bd04485397) | Aug 14, 2022 |
| HP            | 8062                        | [0f24b44d56](https://linux-hardware.org/?probe=0f24b44d56) | Aug 14, 2022 |
| ASUSTek       | M2VTVM-VM890                | [8a822a57e8](https://linux-hardware.org/?probe=8a822a57e8) | Aug 13, 2022 |
| ASUSTek       | PRIME B550M-A               | [bd608fb7bc](https://linux-hardware.org/?probe=bd608fb7bc) | Aug 13, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [5c8d31c692](https://linux-hardware.org/?probe=5c8d31c692) | Aug 13, 2022 |
| HP            | 8906 SMVB                   | [9aeadd926d](https://linux-hardware.org/?probe=9aeadd926d) | Aug 13, 2022 |
| HP            | 8906 SMVB                   | [4f7bbd7462](https://linux-hardware.org/?probe=4f7bbd7462) | Aug 13, 2022 |
| HP            | 805B                        | [188fdd3a56](https://linux-hardware.org/?probe=188fdd3a56) | Aug 13, 2022 |
| MSI           | H61M-P20                    | [acc2520058](https://linux-hardware.org/?probe=acc2520058) | Aug 13, 2022 |
| MSI           | B450-A PRO                  | [e635669620](https://linux-hardware.org/?probe=e635669620) | Aug 13, 2022 |
| MSI           | Boston                      | [890c944be0](https://linux-hardware.org/?probe=890c944be0) | Aug 12, 2022 |
| MSI           | MAG B550M MORTAR            | [baf348cae9](https://linux-hardware.org/?probe=baf348cae9) | Aug 12, 2022 |
| HP            | 18E7                        | [f1c1f9c891](https://linux-hardware.org/?probe=f1c1f9c891) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ba9961565a](https://linux-hardware.org/?probe=ba9961565a) | Aug 12, 2022 |
| Foxconn       | 2ADA                        | [9aae49b54c](https://linux-hardware.org/?probe=9aae49b54c) | Aug 11, 2022 |
| HP            | 805A                        | [c7671a704a](https://linux-hardware.org/?probe=c7671a704a) | Aug 11, 2022 |
| ASRock        | H410M-HVS                   | [4d1acc8488](https://linux-hardware.org/?probe=4d1acc8488) | Aug 11, 2022 |
| ASRock        | B550M-ITX/ac                | [8898e9247d](https://linux-hardware.org/?probe=8898e9247d) | Aug 11, 2022 |
| HP            | 18E7                        | [531c621cdb](https://linux-hardware.org/?probe=531c621cdb) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f9efd8697b](https://linux-hardware.org/?probe=f9efd8697b) | Aug 11, 2022 |
| Gigabyte      | Z87M-D3HP                   | [b6612680e2](https://linux-hardware.org/?probe=b6612680e2) | Aug 11, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [7792f4471e](https://linux-hardware.org/?probe=7792f4471e) | Aug 10, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | [5035953069](https://linux-hardware.org/?probe=5035953069) | Aug 10, 2022 |
| Vorke         | V1 Plus                     | [a31728f53e](https://linux-hardware.org/?probe=a31728f53e) | Aug 10, 2022 |
| ASRock        | 990FX Killer                | [cba7d360f1](https://linux-hardware.org/?probe=cba7d360f1) | Aug 10, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [f3dcea80d5](https://linux-hardware.org/?probe=f3dcea80d5) | Aug 10, 2022 |
| AZW           | Green G2                    | [ef3034c1a3](https://linux-hardware.org/?probe=ef3034c1a3) | Aug 10, 2022 |
| ASUSTek       | VC66-C2                     | [2bf56f453d](https://linux-hardware.org/?probe=2bf56f453d) | Aug 10, 2022 |
| MSI           | B550-A PRO                  | [b9fb53384c](https://linux-hardware.org/?probe=b9fb53384c) | Aug 09, 2022 |
| ASUSTek       | P5VD2-VM                    | [1d8a97ade8](https://linux-hardware.org/?probe=1d8a97ade8) | Aug 09, 2022 |
| Foxconn       | 2ABF                        | [89d9f69018](https://linux-hardware.org/?probe=89d9f69018) | Aug 09, 2022 |
| Pegatron      | 2A99                        | [af5300a24d](https://linux-hardware.org/?probe=af5300a24d) | Aug 08, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [c599bb0199](https://linux-hardware.org/?probe=c599bb0199) | Aug 08, 2022 |
| MSI           | 760GM-P23                   | [68e7d5dbe4](https://linux-hardware.org/?probe=68e7d5dbe4) | Aug 08, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [935f3a82af](https://linux-hardware.org/?probe=935f3a82af) | Aug 08, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [254f5e8412](https://linux-hardware.org/?probe=254f5e8412) | Aug 08, 2022 |
| HP            | 0A98h                       | [e31e5c99a1](https://linux-hardware.org/?probe=e31e5c99a1) | Aug 08, 2022 |
| Foxconn       | 2ABF                        | [ee62b165ef](https://linux-hardware.org/?probe=ee62b165ef) | Aug 08, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7ca881aae7](https://linux-hardware.org/?probe=7ca881aae7) | Aug 08, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [aada9001dd](https://linux-hardware.org/?probe=aada9001dd) | Aug 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [e221390896](https://linux-hardware.org/?probe=e221390896) | Aug 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [a4df22fe39](https://linux-hardware.org/?probe=a4df22fe39) | Aug 08, 2022 |
| Acer          | Aspire XC-830               | [b4e118e0a5](https://linux-hardware.org/?probe=b4e118e0a5) | Aug 07, 2022 |
| Intel         | D975XBX2 AAD53350-503       | [67f56805b0](https://linux-hardware.org/?probe=67f56805b0) | Aug 07, 2022 |
| HP            | 1589                        | [0827fa8662](https://linux-hardware.org/?probe=0827fa8662) | Aug 07, 2022 |
| Foxconn       | 2ABF                        | [bfa218709f](https://linux-hardware.org/?probe=bfa218709f) | Aug 07, 2022 |
| ASUSTek       | P5Q                         | [f45edaf8a6](https://linux-hardware.org/?probe=f45edaf8a6) | Aug 07, 2022 |
| ASUSTek       | P5Q                         | [e07c48b40d](https://linux-hardware.org/?probe=e07c48b40d) | Aug 07, 2022 |
| HP            | 1497                        | [2fe6cb5b2c](https://linux-hardware.org/?probe=2fe6cb5b2c) | Aug 07, 2022 |
| HP            | 1497                        | [24959f2c80](https://linux-hardware.org/?probe=24959f2c80) | Aug 07, 2022 |
| ASRock        | B450M-HDV R4.0              | [ec538ff66a](https://linux-hardware.org/?probe=ec538ff66a) | Aug 07, 2022 |
| HP            | 1998                        | [1ae818eb7c](https://linux-hardware.org/?probe=1ae818eb7c) | Aug 07, 2022 |
| Biostar       | B550MH                      | [228a44e3f0](https://linux-hardware.org/?probe=228a44e3f0) | Aug 06, 2022 |
| HP            | 3031h                       | [2409514846](https://linux-hardware.org/?probe=2409514846) | Aug 06, 2022 |
| ASRock        | 880GM-LE FX                 | [957edc332a](https://linux-hardware.org/?probe=957edc332a) | Aug 06, 2022 |
| Intel         | 945GCT-M                    | [0481d5180e](https://linux-hardware.org/?probe=0481d5180e) | Aug 06, 2022 |
| HP            | 198E                        | [4327be921d](https://linux-hardware.org/?probe=4327be921d) | Aug 06, 2022 |
| HP            | 198E                        | [284e29b3ea](https://linux-hardware.org/?probe=284e29b3ea) | Aug 06, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | [0a0341c481](https://linux-hardware.org/?probe=0a0341c481) | Aug 05, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | [06d2014c22](https://linux-hardware.org/?probe=06d2014c22) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | [48606f92a6](https://linux-hardware.org/?probe=48606f92a6) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | [c55f1b0a46](https://linux-hardware.org/?probe=c55f1b0a46) | Aug 05, 2022 |
| ASRock        | H61M-HVGS                   | [1c95e4f03d](https://linux-hardware.org/?probe=1c95e4f03d) | Aug 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [3b290b6c0b](https://linux-hardware.org/?probe=3b290b6c0b) | Aug 04, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [2030bc92d7](https://linux-hardware.org/?probe=2030bc92d7) | Aug 04, 2022 |
| MSI           | Z170A GAMING M5             | [37ccdc4cf7](https://linux-hardware.org/?probe=37ccdc4cf7) | Aug 04, 2022 |
| MSI           | 970 GAMING                  | [5eee2883a9](https://linux-hardware.org/?probe=5eee2883a9) | Aug 04, 2022 |
| Standard      | X50-V2                      | [cb09d559a8](https://linux-hardware.org/?probe=cb09d559a8) | Aug 04, 2022 |
| ASRock        | H97M Pro4                   | [c290aae7c6](https://linux-hardware.org/?probe=c290aae7c6) | Aug 04, 2022 |
| MSI           | MEG B550 UNIFY-X            | [7e2cdd3016](https://linux-hardware.org/?probe=7e2cdd3016) | Aug 04, 2022 |
| MSI           | MEG B550 UNIFY-X            | [ced1fc4e4a](https://linux-hardware.org/?probe=ced1fc4e4a) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [996ac97066](https://linux-hardware.org/?probe=996ac97066) | Aug 03, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [3342aeb08c](https://linux-hardware.org/?probe=3342aeb08c) | Aug 03, 2022 |
| Biostar       | TA880GU3+                   | [323c68d80f](https://linux-hardware.org/?probe=323c68d80f) | Aug 03, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [dcc08c0fa5](https://linux-hardware.org/?probe=dcc08c0fa5) | Aug 03, 2022 |
| Gigabyte      | G33M-S2                     | [5bd6c356cd](https://linux-hardware.org/?probe=5bd6c356cd) | Aug 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [4e6ea804e9](https://linux-hardware.org/?probe=4e6ea804e9) | Aug 02, 2022 |
| HP            | ProLiant ML310e Gen8        | [7a12318176](https://linux-hardware.org/?probe=7a12318176) | Aug 02, 2022 |
| ASRock        | X370 Taichi                 | [7d13857a3a](https://linux-hardware.org/?probe=7d13857a3a) | Aug 02, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | [1c92a49cd4](https://linux-hardware.org/?probe=1c92a49cd4) | Aug 01, 2022 |
| HP            | 1493                        | [2925e7a321](https://linux-hardware.org/?probe=2925e7a321) | Aug 01, 2022 |
| MSI           | X370 KRAIT GAMING           | [fe950a68a3](https://linux-hardware.org/?probe=fe950a68a3) | Aug 01, 2022 |
| Acer          | Aspire X3470                | [88ad041430](https://linux-hardware.org/?probe=88ad041430) | Jul 31, 2022 |
| ASRock        | N68-S3 UCC                  | [bcb1d1da28](https://linux-hardware.org/?probe=bcb1d1da28) | Jul 31, 2022 |
| MSI           | Z97 PC Mate                 | [73ebbe2902](https://linux-hardware.org/?probe=73ebbe2902) | Jul 31, 2022 |
| MSI           | Z97 PC Mate                 | [22a32957dc](https://linux-hardware.org/?probe=22a32957dc) | Jul 31, 2022 |
| Gigabyte      | Z87-HD3                     | [83936d3cf0](https://linux-hardware.org/?probe=83936d3cf0) | Jul 31, 2022 |
| MSI           | Z490-A PRO                  | [054fdc9187](https://linux-hardware.org/?probe=054fdc9187) | Jul 31, 2022 |
| ASUSTek       | PRIME X570-P                | [e962ba603d](https://linux-hardware.org/?probe=e962ba603d) | Jul 31, 2022 |
| ASUSTek       | PRIME Z490-A                | [a1923838e1](https://linux-hardware.org/?probe=a1923838e1) | Jul 31, 2022 |
| MSI           | MAG B550M MORTAR            | [8614c5b8df](https://linux-hardware.org/?probe=8614c5b8df) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [b0265ffd70](https://linux-hardware.org/?probe=b0265ffd70) | Jul 30, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [af062992d8](https://linux-hardware.org/?probe=af062992d8) | Jul 30, 2022 |
| Gigabyte      | G33M-S2                     | [0a96778f7c](https://linux-hardware.org/?probe=0a96778f7c) | Jul 30, 2022 |
| Dell          | 06NWYK A00                  | [1182388bb6](https://linux-hardware.org/?probe=1182388bb6) | Jul 30, 2022 |
| MSI           | A320M-A PRO MAX             | [3249abb411](https://linux-hardware.org/?probe=3249abb411) | Jul 30, 2022 |
| MSI           | A320M-A PRO MAX             | [5a750a1294](https://linux-hardware.org/?probe=5a750a1294) | Jul 30, 2022 |
| HP            | 18E7                        | [3d7c1549eb](https://linux-hardware.org/?probe=3d7c1549eb) | Jul 29, 2022 |
| Gigabyte      | B550 AORUS ELITE AX         | [eee9c60bec](https://linux-hardware.org/?probe=eee9c60bec) | Jul 29, 2022 |
| ASRock        | B85 Pro4                    | [98e02ef2cd](https://linux-hardware.org/?probe=98e02ef2cd) | Jul 29, 2022 |
| ASRock        | B85 Pro4                    | [ec68a40236](https://linux-hardware.org/?probe=ec68a40236) | Jul 29, 2022 |
| Biostar       | A880G+                      | [5f10c78e54](https://linux-hardware.org/?probe=5f10c78e54) | Jul 29, 2022 |
| Gigabyte      | H510M S2H                   | [7c42ac18e4](https://linux-hardware.org/?probe=7c42ac18e4) | Jul 29, 2022 |
| HP            | 339A                        | [fa0d80162a](https://linux-hardware.org/?probe=fa0d80162a) | Jul 29, 2022 |
| MSI           | Z390-A PRO                  | [32c295bae1](https://linux-hardware.org/?probe=32c295bae1) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-GAMING II       | [0cc1bc9401](https://linux-hardware.org/?probe=0cc1bc9401) | Jul 29, 2022 |
| ASUSTek       | M4N78                       | [870702db59](https://linux-hardware.org/?probe=870702db59) | Jul 29, 2022 |
| Biostar       | B350GTN                     | [75d6302ab0](https://linux-hardware.org/?probe=75d6302ab0) | Jul 29, 2022 |
| ASUSTek       | P8B75-M LX                  | [af972287a0](https://linux-hardware.org/?probe=af972287a0) | Jul 29, 2022 |
| AZW           | Green G2                    | [c3e6905701](https://linux-hardware.org/?probe=c3e6905701) | Jul 29, 2022 |
| AZW           | Green G2                    | [acf3761817](https://linux-hardware.org/?probe=acf3761817) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2953cb274f](https://linux-hardware.org/?probe=2953cb274f) | Jul 28, 2022 |
| HP            | 21F5                        | [27cf2d6a42](https://linux-hardware.org/?probe=27cf2d6a42) | Jul 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [297217baa1](https://linux-hardware.org/?probe=297217baa1) | Jul 28, 2022 |
| Gigabyte      | H410M H                     | [eb92148078](https://linux-hardware.org/?probe=eb92148078) | Jul 28, 2022 |
| MSI           | B550-A PRO                  | [f597d7cc46](https://linux-hardware.org/?probe=f597d7cc46) | Jul 28, 2022 |
| ASUSTek       | G10DK                       | [70a71d84a6](https://linux-hardware.org/?probe=70a71d84a6) | Jul 28, 2022 |
| Positivo      | POS-RIB360EE 11158935       | [1c687dcef7](https://linux-hardware.org/?probe=1c687dcef7) | Jul 28, 2022 |
| MSI           | B550-A PRO                  | [2ae0b5a47a](https://linux-hardware.org/?probe=2ae0b5a47a) | Jul 28, 2022 |
| ASUSTek       | PRIME X470-PRO              | [ce5af45a80](https://linux-hardware.org/?probe=ce5af45a80) | Jul 28, 2022 |
| Lenovo        | Tiger Hill                  | [66597a565e](https://linux-hardware.org/?probe=66597a565e) | Jul 28, 2022 |
| Gigabyte      | Z97X-UD5H                   | [9b3bb82b80](https://linux-hardware.org/?probe=9b3bb82b80) | Jul 28, 2022 |
| ASUSTek       | Z170-A                      | [47f6481e91](https://linux-hardware.org/?probe=47f6481e91) | Jul 28, 2022 |
| Intel         | X99 V1.0                    | [da677f5a3b](https://linux-hardware.org/?probe=da677f5a3b) | Jul 28, 2022 |
| HP            | 806A                        | [6a6df5d868](https://linux-hardware.org/?probe=6a6df5d868) | Jul 28, 2022 |
| ASRock        | H310CM-ITX/ac               | [df9564b6b3](https://linux-hardware.org/?probe=df9564b6b3) | Jul 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [cb4bc3fa42](https://linux-hardware.org/?probe=cb4bc3fa42) | Jul 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [9f5bf108ac](https://linux-hardware.org/?probe=9f5bf108ac) | Jul 27, 2022 |
| MSI           | 970A-G43                    | [9095b31f2f](https://linux-hardware.org/?probe=9095b31f2f) | Jul 26, 2022 |
| ASUSTek       | P5KC                        | [7e9c9d2fc4](https://linux-hardware.org/?probe=7e9c9d2fc4) | Jul 26, 2022 |
| Dell          | 06NWYK A00                  | [effad14bc0](https://linux-hardware.org/?probe=effad14bc0) | Jul 26, 2022 |
| Gigabyte      | EP45-DS3                    | [5b5fe46f75](https://linux-hardware.org/?probe=5b5fe46f75) | Jul 26, 2022 |
| Gigabyte      | Z590 AORUS MASTER           | [300ddea4d6](https://linux-hardware.org/?probe=300ddea4d6) | Jul 26, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [32045fd953](https://linux-hardware.org/?probe=32045fd953) | Jul 26, 2022 |
| Gigabyte      | B85-HD3                     | [9447f1eb98](https://linux-hardware.org/?probe=9447f1eb98) | Jul 26, 2022 |
| Gigabyte      | Z590 GAMING X               | [6701685bb5](https://linux-hardware.org/?probe=6701685bb5) | Jul 26, 2022 |
| Acer          | WMCP78M                     | [fa9866b7e5](https://linux-hardware.org/?probe=fa9866b7e5) | Jul 26, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | [e471e3ed10](https://linux-hardware.org/?probe=e471e3ed10) | Jul 26, 2022 |
| Gigabyte      | Z87-D3HP-CF                 | [88b45b1956](https://linux-hardware.org/?probe=88b45b1956) | Jul 26, 2022 |
| MSI           | H510M PRO                   | [07c98d99d5](https://linux-hardware.org/?probe=07c98d99d5) | Jul 25, 2022 |
| MSI           | H510M PRO                   | [e8693a9212](https://linux-hardware.org/?probe=e8693a9212) | Jul 25, 2022 |
| AZW           | SEi                         | [00755b9883](https://linux-hardware.org/?probe=00755b9883) | Jul 25, 2022 |
| Gigabyte      | Z390 M-CF                   | [ae2926d93e](https://linux-hardware.org/?probe=ae2926d93e) | Jul 24, 2022 |
| Intel         | X99                         | [046538e5fc](https://linux-hardware.org/?probe=046538e5fc) | Jul 24, 2022 |
| Dell          | 0WN7Y6 A02                  | [4059b7a331](https://linux-hardware.org/?probe=4059b7a331) | Jul 24, 2022 |
| ASUSTek       | P8H61-MX                    | [6614f30e6a](https://linux-hardware.org/?probe=6614f30e6a) | Jul 24, 2022 |
| ASRock        | X470 Gaming K4              | [4f26f0dbda](https://linux-hardware.org/?probe=4f26f0dbda) | Jul 24, 2022 |
| Gigabyte      | MJPLNAB-00                  | [d414e51a0c](https://linux-hardware.org/?probe=d414e51a0c) | Jul 23, 2022 |
| ASUSTek       | P5E3 PRO                    | [357b10a053](https://linux-hardware.org/?probe=357b10a053) | Jul 23, 2022 |
| Gigabyte      | MJPLNAB-00                  | [9dcb499f3e](https://linux-hardware.org/?probe=9dcb499f3e) | Jul 23, 2022 |
| Minix         | NEO Z83-4 V1.1              | [e8c6448552](https://linux-hardware.org/?probe=e8c6448552) | Jul 23, 2022 |
| MSI           | G31TM-P21                   | [abc0948b06](https://linux-hardware.org/?probe=abc0948b06) | Jul 23, 2022 |
| HP            | 339A                        | [313af629be](https://linux-hardware.org/?probe=313af629be) | Jul 23, 2022 |
| MSI           | 970 GAMING                  | [2814270f24](https://linux-hardware.org/?probe=2814270f24) | Jul 23, 2022 |
| Pegatron      | 2ACD                        | [c8ce65cd26](https://linux-hardware.org/?probe=c8ce65cd26) | Jul 23, 2022 |
| ASRock        | Z270 Professional Gaming... | [c84ebb5a1a](https://linux-hardware.org/?probe=c84ebb5a1a) | Jul 23, 2022 |
| ASUSTek       | P8P67 PRO                   | [54e6e291bd](https://linux-hardware.org/?probe=54e6e291bd) | Jul 22, 2022 |
| Dell          | 0P01GV A03                  | [60b77cc6b5](https://linux-hardware.org/?probe=60b77cc6b5) | Jul 22, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS            | [3c5c67efc0](https://linux-hardware.org/?probe=3c5c67efc0) | Jul 22, 2022 |
| HP            | 08B4h                       | [8ff662507a](https://linux-hardware.org/?probe=8ff662507a) | Jul 22, 2022 |
| Intel         | Z77                         | [c858c41f36](https://linux-hardware.org/?probe=c858c41f36) | Jul 22, 2022 |
| Intel         | Z77                         | [d1f38293b3](https://linux-hardware.org/?probe=d1f38293b3) | Jul 22, 2022 |
| MSI           | Z77A-GD65                   | [f0cf5d1f55](https://linux-hardware.org/?probe=f0cf5d1f55) | Jul 22, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [2986a26253](https://linux-hardware.org/?probe=2986a26253) | Jul 22, 2022 |
| MSI           | Z77A-GD65                   | [edfa6cb848](https://linux-hardware.org/?probe=edfa6cb848) | Jul 22, 2022 |
| Lenovo        | NOK                         | [a47a727578](https://linux-hardware.org/?probe=a47a727578) | Jul 22, 2022 |
| HP            | 0AECh D                     | [ca7abdaae0](https://linux-hardware.org/?probe=ca7abdaae0) | Jul 22, 2022 |
| ASUSTek       | P8B75-M LE                  | [f5c169fed7](https://linux-hardware.org/?probe=f5c169fed7) | Jul 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b6fc243a07](https://linux-hardware.org/?probe=b6fc243a07) | Jul 22, 2022 |
| ASUSTek       | PRIME Z390-A                | [83d47fc3dc](https://linux-hardware.org/?probe=83d47fc3dc) | Jul 22, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [b08505b90e](https://linux-hardware.org/?probe=b08505b90e) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2e97c3de0b](https://linux-hardware.org/?probe=2e97c3de0b) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d567131bf9](https://linux-hardware.org/?probe=d567131bf9) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | [210b75c48e](https://linux-hardware.org/?probe=210b75c48e) | Jul 21, 2022 |
| Gigabyte      | G41MT-S2PT                  | [b291af1e34](https://linux-hardware.org/?probe=b291af1e34) | Jul 21, 2022 |
| Unknown       | Unknown                     | [752319bda0](https://linux-hardware.org/?probe=752319bda0) | Jul 21, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [e80a3e71e2](https://linux-hardware.org/?probe=e80a3e71e2) | Jul 21, 2022 |
| Intel         | STK1AW32SC H91596-307       | [78225ba5b9](https://linux-hardware.org/?probe=78225ba5b9) | Jul 21, 2022 |
| ASUSTek       | A88X-PRO                    | [be81f08ed2](https://linux-hardware.org/?probe=be81f08ed2) | Jul 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [6de28040de](https://linux-hardware.org/?probe=6de28040de) | Jul 21, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [06b84340f2](https://linux-hardware.org/?probe=06b84340f2) | Jul 21, 2022 |
| HP            | 2AF7                        | [3791eccf74](https://linux-hardware.org/?probe=3791eccf74) | Jul 20, 2022 |
| HP            | 2AF7                        | [43cc1f3d0a](https://linux-hardware.org/?probe=43cc1f3d0a) | Jul 20, 2022 |
| ASUSTek       | Z87M-PLUS                   | [da502f8dfd](https://linux-hardware.org/?probe=da502f8dfd) | Jul 20, 2022 |
| Foxconn       | ETON                        | [1686897e74](https://linux-hardware.org/?probe=1686897e74) | Jul 20, 2022 |
| ASUSTek       | P8Z68-V LX                  | [0de7d2f427](https://linux-hardware.org/?probe=0de7d2f427) | Jul 20, 2022 |
| Gigabyte      | 970A-DS3P                   | [17befc2dd5](https://linux-hardware.org/?probe=17befc2dd5) | Jul 20, 2022 |
| Gigabyte      | H410M H V3                  | [37521f84c8](https://linux-hardware.org/?probe=37521f84c8) | Jul 20, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [0ce9af7993](https://linux-hardware.org/?probe=0ce9af7993) | Jul 20, 2022 |
| HP            | 1998                        | [08e093657d](https://linux-hardware.org/?probe=08e093657d) | Jul 20, 2022 |
| Gigabyte      | B150M-D3H-CF                | [65fb347b62](https://linux-hardware.org/?probe=65fb347b62) | Jul 19, 2022 |
| Gigabyte      | EP45-UD3P                   | [888e64f06a](https://linux-hardware.org/?probe=888e64f06a) | Jul 19, 2022 |
| ECS           | A990FXM-A                   | [6351c9023d](https://linux-hardware.org/?probe=6351c9023d) | Jul 19, 2022 |
| MSI           | B450-A PRO MAX              | [2e74bdb9aa](https://linux-hardware.org/?probe=2e74bdb9aa) | Jul 19, 2022 |
| Foxconn       | 2ABF                        | [765d75028c](https://linux-hardware.org/?probe=765d75028c) | Jul 19, 2022 |
| MACHINIST     | X79 V2.82H                  | [67faad589b](https://linux-hardware.org/?probe=67faad589b) | Jul 19, 2022 |
| Dell          | 08WKV3 A00                  | [05fb8c3ed5](https://linux-hardware.org/?probe=05fb8c3ed5) | Jul 19, 2022 |
| MSI           | G31M3-L V2                  | [cd6d617e34](https://linux-hardware.org/?probe=cd6d617e34) | Jul 19, 2022 |
| MSI           | G31M3-L V2                  | [aaa3013f66](https://linux-hardware.org/?probe=aaa3013f66) | Jul 18, 2022 |
| Dell          | 0D28YY A00                  | [129009177c](https://linux-hardware.org/?probe=129009177c) | Jul 18, 2022 |
| Dell          | 0D28YY A00                  | [3a633633a2](https://linux-hardware.org/?probe=3a633633a2) | Jul 18, 2022 |
| ASUSTek       | PRIME A320M-K               | [48d9b9f502](https://linux-hardware.org/?probe=48d9b9f502) | Jul 18, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [6aac7a75e7](https://linux-hardware.org/?probe=6aac7a75e7) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-E               | [db7cb6f32b](https://linux-hardware.org/?probe=db7cb6f32b) | Jul 18, 2022 |
| ASUSTek       | P8B75-M LE                  | [34f50b057e](https://linux-hardware.org/?probe=34f50b057e) | Jul 18, 2022 |
| ASUSTek       | SABERTOOTH Z87              | [64d5fa573d](https://linux-hardware.org/?probe=64d5fa573d) | Jul 18, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [d6c5a9efaf](https://linux-hardware.org/?probe=d6c5a9efaf) | Jul 18, 2022 |
| Pegatron      | 2ACD                        | [2864879f93](https://linux-hardware.org/?probe=2864879f93) | Jul 18, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [24c82034e6](https://linux-hardware.org/?probe=24c82034e6) | Jul 18, 2022 |
| ASUSTek       | PRIME X570-P                | [8c48826e45](https://linux-hardware.org/?probe=8c48826e45) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [dac8603f3d](https://linux-hardware.org/?probe=dac8603f3d) | Jul 17, 2022 |
| Gigabyte      | G33M-S2                     | [c6c4a561e1](https://linux-hardware.org/?probe=c6c4a561e1) | Jul 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | [38ebe8f368](https://linux-hardware.org/?probe=38ebe8f368) | Jul 17, 2022 |
| Gigabyte      | F2A85XM-D3H                 | [129bcce64f](https://linux-hardware.org/?probe=129bcce64f) | Jul 17, 2022 |
| Gigabyte      | B560M DS3H V2               | [43d7f05696](https://linux-hardware.org/?probe=43d7f05696) | Jul 17, 2022 |
| HP            | 1998                        | [8aa7e05c70](https://linux-hardware.org/?probe=8aa7e05c70) | Jul 17, 2022 |
| Apple         | Mac-F221BEC8                | [5f5367ebdd](https://linux-hardware.org/?probe=5f5367ebdd) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [68d8843883](https://linux-hardware.org/?probe=68d8843883) | Jul 17, 2022 |
| Lenovo        | Bantry CRB NOK              | [0fdca53da8](https://linux-hardware.org/?probe=0fdca53da8) | Jul 17, 2022 |
| BESSTAR Te... | HM90                        | [ee18049d28](https://linux-hardware.org/?probe=ee18049d28) | Jul 17, 2022 |
| ASRock        | H110M-DGS R3.0              | [895550b6d3](https://linux-hardware.org/?probe=895550b6d3) | Jul 17, 2022 |
| Dell          | 08NPPY A00                  | [23d9101cd2](https://linux-hardware.org/?probe=23d9101cd2) | Jul 17, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [7142849ed0](https://linux-hardware.org/?probe=7142849ed0) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [057b18a904](https://linux-hardware.org/?probe=057b18a904) | Jul 16, 2022 |
| Gigabyte      | M57SLI-S4                   | [288984fb9e](https://linux-hardware.org/?probe=288984fb9e) | Jul 16, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [5b07f65ff5](https://linux-hardware.org/?probe=5b07f65ff5) | Jul 16, 2022 |
| ASUSTek       | CM6870                      | [b52692fd5e](https://linux-hardware.org/?probe=b52692fd5e) | Jul 16, 2022 |
| MSI           | Boston                      | [c1474f9d2f](https://linux-hardware.org/?probe=c1474f9d2f) | Jul 15, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | [75e4cc3704](https://linux-hardware.org/?probe=75e4cc3704) | Jul 15, 2022 |
| Intel         | H61                         | [8865d7959a](https://linux-hardware.org/?probe=8865d7959a) | Jul 15, 2022 |
| ASUSTek       | P5E3 PRO                    | [b4c3e4eeb0](https://linux-hardware.org/?probe=b4c3e4eeb0) | Jul 15, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [cb6916e513](https://linux-hardware.org/?probe=cb6916e513) | Jul 15, 2022 |
| ASUSTek       | H81M-K                      | [1d2991137d](https://linux-hardware.org/?probe=1d2991137d) | Jul 15, 2022 |
| Medion        | MS-7633                     | [35af25c619](https://linux-hardware.org/?probe=35af25c619) | Jul 15, 2022 |
| Gigabyte      | Z390 DESIGNARE-CF           | [a81e48e206](https://linux-hardware.org/?probe=a81e48e206) | Jul 15, 2022 |
| ECS           | H81H3-WM                    | [e38b93a0c9](https://linux-hardware.org/?probe=e38b93a0c9) | Jul 15, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [fecf83d1eb](https://linux-hardware.org/?probe=fecf83d1eb) | Jul 14, 2022 |
| ASUSTek       | M4A78 PRO                   | [119c291cd5](https://linux-hardware.org/?probe=119c291cd5) | Jul 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [0893dc4cc3](https://linux-hardware.org/?probe=0893dc4cc3) | Jul 14, 2022 |
| Dell          | 0MGK50 A02                  | [0c0ac374b4](https://linux-hardware.org/?probe=0c0ac374b4) | Jul 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9da64b4efa](https://linux-hardware.org/?probe=9da64b4efa) | Jul 14, 2022 |
| Dell          | 0MFHTR A00                  | [2ba698429a](https://linux-hardware.org/?probe=2ba698429a) | Jul 14, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [386dd1ac4b](https://linux-hardware.org/?probe=386dd1ac4b) | Jul 14, 2022 |
| Gigabyte      | B365 HD3                    | [c40e564503](https://linux-hardware.org/?probe=c40e564503) | Jul 14, 2022 |
| Gigabyte      | B365 HD3                    | [985ec392f9](https://linux-hardware.org/?probe=985ec392f9) | Jul 14, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [3a443e4fcb](https://linux-hardware.org/?probe=3a443e4fcb) | Jul 14, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | [050da1ebe6](https://linux-hardware.org/?probe=050da1ebe6) | Jul 13, 2022 |
| MSI           | Z77A-GD65                   | [b2990d4341](https://linux-hardware.org/?probe=b2990d4341) | Jul 13, 2022 |
| MSI           | B365M PRO-VDH               | [7ff6dc5131](https://linux-hardware.org/?probe=7ff6dc5131) | Jul 13, 2022 |
| HP            | 0AE8h C                     | [9e71cf3fbc](https://linux-hardware.org/?probe=9e71cf3fbc) | Jul 13, 2022 |
| MSI           | X370 GAMING M7 ACK          | [df70d8d905](https://linux-hardware.org/?probe=df70d8d905) | Jul 13, 2022 |
| Dell          | 0WR7PY A01                  | [5f479562d2](https://linux-hardware.org/?probe=5f479562d2) | Jul 13, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [5537dda056](https://linux-hardware.org/?probe=5537dda056) | Jul 13, 2022 |
| ASRock        | B365M Pro4                  | [5701f5019e](https://linux-hardware.org/?probe=5701f5019e) | Jul 13, 2022 |
| MSI           | MEG B550 UNIFY-X            | [bb5cce0952](https://linux-hardware.org/?probe=bb5cce0952) | Jul 12, 2022 |
| Dell          | 0C27VV A02                  | [d08ca1549c](https://linux-hardware.org/?probe=d08ca1549c) | Jul 12, 2022 |
| Acer          | Aspire X3470                | [61b7216da0](https://linux-hardware.org/?probe=61b7216da0) | Jul 12, 2022 |
| ASUSTek       | ROG Maximus X HERO          | [575388d90b](https://linux-hardware.org/?probe=575388d90b) | Jul 12, 2022 |
| ECS           | H61H2-WM                    | [f0a17960d3](https://linux-hardware.org/?probe=f0a17960d3) | Jul 12, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [320a4240ce](https://linux-hardware.org/?probe=320a4240ce) | Jul 12, 2022 |
| Dell          | 0P01GV A03                  | [6b4cd20919](https://linux-hardware.org/?probe=6b4cd20919) | Jul 12, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [aba10c973c](https://linux-hardware.org/?probe=aba10c973c) | Jul 11, 2022 |
| AZW           | Green G2                    | [2940e9d90b](https://linux-hardware.org/?probe=2940e9d90b) | Jul 11, 2022 |
| Dell          | 0200DY A01                  | [99eacb5700](https://linux-hardware.org/?probe=99eacb5700) | Jul 11, 2022 |
| ASRock        | P43DE                       | [0dbb7293a1](https://linux-hardware.org/?probe=0dbb7293a1) | Jul 11, 2022 |
| Positivo      | POS-MI945AA                 | [ab451b5409](https://linux-hardware.org/?probe=ab451b5409) | Jul 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [0e8e13e1f2](https://linux-hardware.org/?probe=0e8e13e1f2) | Jul 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c350afe818](https://linux-hardware.org/?probe=c350afe818) | Jul 10, 2022 |
| ASRock        | P43DE                       | [2aa8290d56](https://linux-hardware.org/?probe=2aa8290d56) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | [39e99bec7a](https://linux-hardware.org/?probe=39e99bec7a) | Jul 10, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [abe1c10adf](https://linux-hardware.org/?probe=abe1c10adf) | Jul 09, 2022 |
| MSI           | B450-A PRO MAX              | [00495f3422](https://linux-hardware.org/?probe=00495f3422) | Jul 09, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [8434bd1682](https://linux-hardware.org/?probe=8434bd1682) | Jul 09, 2022 |
| Dell          | 0Y2MRG A00                  | [43118c9fc8](https://linux-hardware.org/?probe=43118c9fc8) | Jul 09, 2022 |
| Dell          | 0Y2MRG A00                  | [1a6fd4101e](https://linux-hardware.org/?probe=1a6fd4101e) | Jul 09, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [49cc36caf5](https://linux-hardware.org/?probe=49cc36caf5) | Jul 09, 2022 |
| ASRock        | AMCP7A-ION                  | [5852afeb48](https://linux-hardware.org/?probe=5852afeb48) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0c96551a28](https://linux-hardware.org/?probe=0c96551a28) | Jul 09, 2022 |
| Unknown       | HX90                        | [1ae069958c](https://linux-hardware.org/?probe=1ae069958c) | Jul 08, 2022 |
| HP            | 2B2C                        | [0ba46e3565](https://linux-hardware.org/?probe=0ba46e3565) | Jul 07, 2022 |
| Gigabyte      | GA-MA790XT-UD4P             | [46c7d18e75](https://linux-hardware.org/?probe=46c7d18e75) | Jul 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [503c38154f](https://linux-hardware.org/?probe=503c38154f) | Jul 07, 2022 |
| Dell          | 0DR845                      | [424649e737](https://linux-hardware.org/?probe=424649e737) | Jul 07, 2022 |
| ASRock        | P67 Pro3                    | [b70f0fde7a](https://linux-hardware.org/?probe=b70f0fde7a) | Jul 07, 2022 |
| ASUSTek       | PRIME X570-P                | [28b43e6c1f](https://linux-hardware.org/?probe=28b43e6c1f) | Jul 06, 2022 |
| Positivo      | POS-MIG31AG                 | [3a03195633](https://linux-hardware.org/?probe=3a03195633) | Jul 06, 2022 |
| Dell          | 0WG864                      | [8ba728c209](https://linux-hardware.org/?probe=8ba728c209) | Jul 06, 2022 |
| ASUSTek       | M2N68-AM SE2                | [602e9ed838](https://linux-hardware.org/?probe=602e9ed838) | Jul 05, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [aed7de4f94](https://linux-hardware.org/?probe=aed7de4f94) | Jul 05, 2022 |
| Dell          | 09KPNV A00                  | [7eb69e794e](https://linux-hardware.org/?probe=7eb69e794e) | Jul 05, 2022 |
| Medion        | MS-7713                     | [c99970c90f](https://linux-hardware.org/?probe=c99970c90f) | Jul 05, 2022 |
| ASUSTek       | IP4BL-ME_S                  | [63a5ec5213](https://linux-hardware.org/?probe=63a5ec5213) | Jul 05, 2022 |
| MSI           | A88X-G43                    | [c8261ecc77](https://linux-hardware.org/?probe=c8261ecc77) | Jul 05, 2022 |
| ASRock        | X370 Gaming K4              | [f3c391da3b](https://linux-hardware.org/?probe=f3c391da3b) | Jul 05, 2022 |
| ASRock        | X370 Pro4                   | [d77bbb292c](https://linux-hardware.org/?probe=d77bbb292c) | Jul 04, 2022 |
| ASRock        | X370 Pro4                   | [31d8330aaa](https://linux-hardware.org/?probe=31d8330aaa) | Jul 04, 2022 |
| HP            | 3048h                       | [a007a37d76](https://linux-hardware.org/?probe=a007a37d76) | Jul 04, 2022 |
| Biostar       | J3060NH                     | [63d3e6c980](https://linux-hardware.org/?probe=63d3e6c980) | Jul 04, 2022 |
| AZW           | Green G2                    | [8104b2d04e](https://linux-hardware.org/?probe=8104b2d04e) | Jul 04, 2022 |
| ASUSTek       | P5E3 PRO                    | [aed74cd5a2](https://linux-hardware.org/?probe=aed74cd5a2) | Jul 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [2cabe9acd0](https://linux-hardware.org/?probe=2cabe9acd0) | Jul 03, 2022 |
| HP            | 2AA6 PVT                    | [965700558a](https://linux-hardware.org/?probe=965700558a) | Jul 03, 2022 |
| ASRock        | B365M Pro4                  | [8b2e08891d](https://linux-hardware.org/?probe=8b2e08891d) | Jul 03, 2022 |
| ASUSTek       | M4A87TD/USB3                | [537a056c32](https://linux-hardware.org/?probe=537a056c32) | Jul 03, 2022 |
| ASRock        | J4105M                      | [502c01c109](https://linux-hardware.org/?probe=502c01c109) | Jul 03, 2022 |
| Gigabyte      | Z170X-GamingG1              | [3f04cb8ead](https://linux-hardware.org/?probe=3f04cb8ead) | Jul 03, 2022 |
| ASRock        | X470 Gaming K4              | [4496c249aa](https://linux-hardware.org/?probe=4496c249aa) | Jul 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [a746300279](https://linux-hardware.org/?probe=a746300279) | Jul 03, 2022 |
| Dell          | 042P49 A01                  | [a4042d3acc](https://linux-hardware.org/?probe=a4042d3acc) | Jul 02, 2022 |
| ASRock        | AM1B-M                      | [e0e4a278c9](https://linux-hardware.org/?probe=e0e4a278c9) | Jul 02, 2022 |
| Medion        | MS-7667                     | [22ac257e4a](https://linux-hardware.org/?probe=22ac257e4a) | Jul 02, 2022 |
| Intel         | D2500CC AAG81477-400        | [c9a6658803](https://linux-hardware.org/?probe=c9a6658803) | Jul 02, 2022 |
| ASRock        | P67 Pro3                    | [9f1ed28d62](https://linux-hardware.org/?probe=9f1ed28d62) | Jul 02, 2022 |
| HP            | 0A64h                       | [bb600b4036](https://linux-hardware.org/?probe=bb600b4036) | Jul 02, 2022 |
| Dell          | 0YXT71 A00                  | [4779be3ea5](https://linux-hardware.org/?probe=4779be3ea5) | Jul 02, 2022 |
| Dell          | 0YXT71 A00                  | [c2b1c8f011](https://linux-hardware.org/?probe=c2b1c8f011) | Jul 02, 2022 |
| Dell          | 09KPNV A00                  | [163fad4354](https://linux-hardware.org/?probe=163fad4354) | Jul 02, 2022 |
| Dell          | 054KM3 A01                  | [149f746382](https://linux-hardware.org/?probe=149f746382) | Jul 02, 2022 |
| ASRock        | P67 Pro3                    | [403db88011](https://linux-hardware.org/?probe=403db88011) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [4ba5c0b79e](https://linux-hardware.org/?probe=4ba5c0b79e) | Jul 01, 2022 |
| Dell          | 0MFHTR A00                  | [bb4d1c2872](https://linux-hardware.org/?probe=bb4d1c2872) | Jul 01, 2022 |
| ASUSTek       | H81M-K                      | [08ed20d4da](https://linux-hardware.org/?probe=08ed20d4da) | Jul 01, 2022 |
| Dell          | 0P01GV A03                  | [0bbac8ce1f](https://linux-hardware.org/?probe=0bbac8ce1f) | Jul 01, 2022 |
| Biostar       | TA790GX 128M                | [c7021e0b8c](https://linux-hardware.org/?probe=c7021e0b8c) | Jul 01, 2022 |
| Pegatron      | 2ACD                        | [3979af0018](https://linux-hardware.org/?probe=3979af0018) | Jul 01, 2022 |
| ASRock        | P67 Pro3                    | [632dbea587](https://linux-hardware.org/?probe=632dbea587) | Jul 01, 2022 |
| ASUSTek       | K30BF_M32BF                 | [dac4b154d6](https://linux-hardware.org/?probe=dac4b154d6) | Jul 01, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d17c3a2817](https://linux-hardware.org/?probe=d17c3a2817) | Jun 30, 2022 |
| MSI           | Z87 MPOWER                  | [ba26baf84a](https://linux-hardware.org/?probe=ba26baf84a) | Jun 30, 2022 |
| MSI           | MEG X570 ACE                | [6dff126482](https://linux-hardware.org/?probe=6dff126482) | Jun 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [a40fb66860](https://linux-hardware.org/?probe=a40fb66860) | Jun 30, 2022 |
| ASRock        | 775Dual-VSTA                | [31825f35da](https://linux-hardware.org/?probe=31825f35da) | Jun 30, 2022 |
| ASUSTek       | PRIME X570-P                | [7eeeee6c93](https://linux-hardware.org/?probe=7eeeee6c93) | Jun 30, 2022 |
| ASUSTek       | PRIME X570-P                | [53dac35f18](https://linux-hardware.org/?probe=53dac35f18) | Jun 30, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [c12aa3088a](https://linux-hardware.org/?probe=c12aa3088a) | Jun 30, 2022 |
| ASRock        | P67 Pro3                    | [aaf8589ded](https://linux-hardware.org/?probe=aaf8589ded) | Jun 30, 2022 |
| Gigabyte      | Z87-HD3                     | [8d9a85c7f3](https://linux-hardware.org/?probe=8d9a85c7f3) | Jun 30, 2022 |
| Gigabyte      | B460M D3H                   | [d620225518](https://linux-hardware.org/?probe=d620225518) | Jun 30, 2022 |
| MSI           | A320M-A PRO MAX             | [9a35c1249b](https://linux-hardware.org/?probe=9a35c1249b) | Jun 30, 2022 |
| MSI           | A320M-A PRO MAX             | [c8f0217b26](https://linux-hardware.org/?probe=c8f0217b26) | Jun 29, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [608388f911](https://linux-hardware.org/?probe=608388f911) | Jun 29, 2022 |
| MSI           | A320M-A PRO MAX             | [d3af5b938a](https://linux-hardware.org/?probe=d3af5b938a) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [6b034bb489](https://linux-hardware.org/?probe=6b034bb489) | Jun 29, 2022 |
| PCWare        | IPMH61R3                    | [492951e8cf](https://linux-hardware.org/?probe=492951e8cf) | Jun 29, 2022 |
| ASRock        | X470 Gaming K4              | [2ec3c19308](https://linux-hardware.org/?probe=2ec3c19308) | Jun 29, 2022 |
| Gigabyte      | GA-870A-UD3                 | [7b07f30b17](https://linux-hardware.org/?probe=7b07f30b17) | Jun 29, 2022 |
| ASRock        | P67 Pro3                    | [bdecafbe1d](https://linux-hardware.org/?probe=bdecafbe1d) | Jun 29, 2022 |
| HP            | 8643 SMVB                   | [a0bf95fa0c](https://linux-hardware.org/?probe=a0bf95fa0c) | Jun 29, 2022 |
| MSI           | H310M PRO-VD                | [1aec9e08e9](https://linux-hardware.org/?probe=1aec9e08e9) | Jun 28, 2022 |
| ASRock        | P43DE                       | [f52d106d92](https://linux-hardware.org/?probe=f52d106d92) | Jun 28, 2022 |
| Dell          | 0Y3R3K A01                  | [d6465d0684](https://linux-hardware.org/?probe=d6465d0684) | Jun 28, 2022 |
| ASUSTek       | TUF Gaming H670-PRO WIFI... | [ea4459628e](https://linux-hardware.org/?probe=ea4459628e) | Jun 28, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | [ff60a3cb61](https://linux-hardware.org/?probe=ff60a3cb61) | Jun 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [291139aa4f](https://linux-hardware.org/?probe=291139aa4f) | Jun 28, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [6ca667e6c4](https://linux-hardware.org/?probe=6ca667e6c4) | Jun 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [369f504484](https://linux-hardware.org/?probe=369f504484) | Jun 28, 2022 |
| ASUSTek       | A88X-GAMER                  | [b7e193f50c](https://linux-hardware.org/?probe=b7e193f50c) | Jun 28, 2022 |
| MSI           | H310M PRO-VD                | [1812911a41](https://linux-hardware.org/?probe=1812911a41) | Jun 28, 2022 |
| Dell          | 0WN7Y6 A01                  | [a07a657c67](https://linux-hardware.org/?probe=a07a657c67) | Jun 28, 2022 |
| ASRock        | 970M Pro3                   | [f817d55df3](https://linux-hardware.org/?probe=f817d55df3) | Jun 28, 2022 |
| Dell          | 02YYK5 A01                  | [ab6a2f07c6](https://linux-hardware.org/?probe=ab6a2f07c6) | Jun 28, 2022 |
| ASUSTek       | P5KPL-AM                    | [f9a3a492d9](https://linux-hardware.org/?probe=f9a3a492d9) | Jun 27, 2022 |
| Gigabyte      | G33M-S2                     | [1acedf0aa3](https://linux-hardware.org/?probe=1acedf0aa3) | Jun 26, 2022 |
| Dell          | 0P01GV A03                  | [74401fdf8b](https://linux-hardware.org/?probe=74401fdf8b) | Jun 26, 2022 |
| HP            | 82A2                        | [cbc788e1d4](https://linux-hardware.org/?probe=cbc788e1d4) | Jun 26, 2022 |
| ASUSTek       | PRIME Z270-A                | [8c2de24375](https://linux-hardware.org/?probe=8c2de24375) | Jun 26, 2022 |
| HP            | 1496                        | [97616aecd6](https://linux-hardware.org/?probe=97616aecd6) | Jun 26, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [e457a60dd4](https://linux-hardware.org/?probe=e457a60dd4) | Jun 26, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [5047471b41](https://linux-hardware.org/?probe=5047471b41) | Jun 26, 2022 |
| ASRock        | A320M-HDV R4.0              | [547346f0a9](https://linux-hardware.org/?probe=547346f0a9) | Jun 26, 2022 |
| HP            | 1496                        | [3ab73cb742](https://linux-hardware.org/?probe=3ab73cb742) | Jun 26, 2022 |
| Gigabyte      | G31M-ES2L                   | [fc35cfc7f6](https://linux-hardware.org/?probe=fc35cfc7f6) | Jun 25, 2022 |
| ASRock        | Z77 Extreme4                | [8caff7e62e](https://linux-hardware.org/?probe=8caff7e62e) | Jun 25, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ac7c0c7169](https://linux-hardware.org/?probe=ac7c0c7169) | Jun 25, 2022 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | [1faf7dc08f](https://linux-hardware.org/?probe=1faf7dc08f) | Jun 25, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [fe8f74c9c1](https://linux-hardware.org/?probe=fe8f74c9c1) | Jun 25, 2022 |
| Dell          | 0XHGV1 A01                  | [9d9ae107c9](https://linux-hardware.org/?probe=9d9ae107c9) | Jun 25, 2022 |
| Intel         | X99 V1.0                    | [17e64443b0](https://linux-hardware.org/?probe=17e64443b0) | Jun 25, 2022 |
| Acer          | Aspire M1470                | [c36091e1c4](https://linux-hardware.org/?probe=c36091e1c4) | Jun 24, 2022 |
| Gigabyte      | G33M-S2                     | [949fb9a5e7](https://linux-hardware.org/?probe=949fb9a5e7) | Jun 24, 2022 |
| ASRock        | P43DE                       | [80f90e4fcd](https://linux-hardware.org/?probe=80f90e4fcd) | Jun 24, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [6a5e82663e](https://linux-hardware.org/?probe=6a5e82663e) | Jun 24, 2022 |
| HP            | 8265                        | [3de1cae37a](https://linux-hardware.org/?probe=3de1cae37a) | Jun 24, 2022 |
| Foxconn       | G31MXP/G31MXP-K FAB:1.0     | [87e5572caa](https://linux-hardware.org/?probe=87e5572caa) | Jun 24, 2022 |
| MSI           | MAG B550M MORTAR            | [4140ae9d15](https://linux-hardware.org/?probe=4140ae9d15) | Jun 24, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | [3902def32a](https://linux-hardware.org/?probe=3902def32a) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | [319b0094a5](https://linux-hardware.org/?probe=319b0094a5) | Jun 24, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | [d9e6c94ff9](https://linux-hardware.org/?probe=d9e6c94ff9) | Jun 24, 2022 |
| Intel         | H61                         | [e5a2c316f3](https://linux-hardware.org/?probe=e5a2c316f3) | Jun 24, 2022 |
| Intel         | H61                         | [d3b87d18d8](https://linux-hardware.org/?probe=d3b87d18d8) | Jun 24, 2022 |
| Intel         | H55                         | [853a94f10d](https://linux-hardware.org/?probe=853a94f10d) | Jun 23, 2022 |
| ASRock        | H97M Anniversary            | [c207afc887](https://linux-hardware.org/?probe=c207afc887) | Jun 23, 2022 |
| Dell          | 0W0CHX A00                  | [874e7081c6](https://linux-hardware.org/?probe=874e7081c6) | Jun 23, 2022 |
| Gigabyte      | Z87-HD3                     | [21d2b9f0fb](https://linux-hardware.org/?probe=21d2b9f0fb) | Jun 23, 2022 |
| MSI           | MAG B550M MORTAR            | [209001317a](https://linux-hardware.org/?probe=209001317a) | Jun 23, 2022 |
| MSI           | X570-A PRO                  | [f23e2ad2eb](https://linux-hardware.org/?probe=f23e2ad2eb) | Jun 23, 2022 |
| Gigabyte      | B450M S2H                   | [6dd752fab5](https://linux-hardware.org/?probe=6dd752fab5) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [914da7c9a4](https://linux-hardware.org/?probe=914da7c9a4) | Jun 23, 2022 |
| Dell          | 0XHGV1 A01                  | [656f558626](https://linux-hardware.org/?probe=656f558626) | Jun 23, 2022 |
| ASRock        | A320M-HDV R4.0              | [cf4479fbe9](https://linux-hardware.org/?probe=cf4479fbe9) | Jun 22, 2022 |
| Gigabyte      | F2A68HM-S1                  | [3c8fa6df0d](https://linux-hardware.org/?probe=3c8fa6df0d) | Jun 22, 2022 |
| Intel         | DX58SO AAE29331-703         | [edb0ff1a68](https://linux-hardware.org/?probe=edb0ff1a68) | Jun 22, 2022 |
| HP            | 3397                        | [337e956c95](https://linux-hardware.org/?probe=337e956c95) | Jun 22, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [ca1f97100c](https://linux-hardware.org/?probe=ca1f97100c) | Jun 22, 2022 |
| ASUSTek       | PRIME Z270-A                | [463b7612de](https://linux-hardware.org/?probe=463b7612de) | Jun 22, 2022 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [62aec95456](https://linux-hardware.org/?probe=62aec95456) | Jun 22, 2022 |
| Dell          | 0C7195                      | [de1b3a50c4](https://linux-hardware.org/?probe=de1b3a50c4) | Jun 21, 2022 |
| Dell          | 0C7195                      | [849bd15857](https://linux-hardware.org/?probe=849bd15857) | Jun 21, 2022 |
| Dell          | 0XR1GT A00                  | [9a2a323056](https://linux-hardware.org/?probe=9a2a323056) | Jun 21, 2022 |
| Dell          | 0GY6Y8 A03                  | [d830a11b04](https://linux-hardware.org/?probe=d830a11b04) | Jun 20, 2022 |
| HP            | 1495                        | [23d2147ac4](https://linux-hardware.org/?probe=23d2147ac4) | Jun 20, 2022 |
| Gigabyte      | 970A-D3P                    | [d0b9dab8ea](https://linux-hardware.org/?probe=d0b9dab8ea) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3fad3e1c0b](https://linux-hardware.org/?probe=3fad3e1c0b) | Jun 19, 2022 |
| ASRock        | H55M                        | [980af488d9](https://linux-hardware.org/?probe=980af488d9) | Jun 19, 2022 |
| ASRock        | P67 Pro3                    | [9804004de5](https://linux-hardware.org/?probe=9804004de5) | Jun 18, 2022 |
| ASRock        | X470 Gaming K4              | [cbd28eb0ed](https://linux-hardware.org/?probe=cbd28eb0ed) | Jun 18, 2022 |
| HP            | 1825                        | [493985b52d](https://linux-hardware.org/?probe=493985b52d) | Jun 18, 2022 |
| MSI           | 760GM-P23                   | [7780379c50](https://linux-hardware.org/?probe=7780379c50) | Jun 18, 2022 |
| MSI           | 760GM-P23                   | [77f495e6f2](https://linux-hardware.org/?probe=77f495e6f2) | Jun 18, 2022 |
| ASRock        | P67 Pro3                    | [2c0a807c9c](https://linux-hardware.org/?probe=2c0a807c9c) | Jun 17, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [4a18a31e47](https://linux-hardware.org/?probe=4a18a31e47) | Jun 17, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [c8ff6a7094](https://linux-hardware.org/?probe=c8ff6a7094) | Jun 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [1cc4490d99](https://linux-hardware.org/?probe=1cc4490d99) | Jun 17, 2022 |
| HP            | 2B29                        | [a845bb9ffa](https://linux-hardware.org/?probe=a845bb9ffa) | Jun 17, 2022 |
| HP            | 1589                        | [1d686eba5c](https://linux-hardware.org/?probe=1d686eba5c) | Jun 17, 2022 |
| Acer          | Aspire TC-230               | [ac205eb1ec](https://linux-hardware.org/?probe=ac205eb1ec) | Jun 17, 2022 |
| MSI           | H310M PRO-VD                | [6516a467b5](https://linux-hardware.org/?probe=6516a467b5) | Jun 17, 2022 |
| MSI           | 970A-G43                    | [9514e1e2ef](https://linux-hardware.org/?probe=9514e1e2ef) | Jun 16, 2022 |
| Dell          | 0TP412                      | [aa585dda89](https://linux-hardware.org/?probe=aa585dda89) | Jun 16, 2022 |
| ASUSTek       | PRIME X570-P                | [d1c0e8e35c](https://linux-hardware.org/?probe=d1c0e8e35c) | Jun 16, 2022 |
| Dell          | 0C7195                      | [fd059539b2](https://linux-hardware.org/?probe=fd059539b2) | Jun 16, 2022 |
| Dell          | 0C7195                      | [192423f74c](https://linux-hardware.org/?probe=192423f74c) | Jun 16, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [58e8e1ab87](https://linux-hardware.org/?probe=58e8e1ab87) | Jun 16, 2022 |
| AZW           | Gemini T34                  | [553b174ce2](https://linux-hardware.org/?probe=553b174ce2) | Jun 16, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [bce90f59c8](https://linux-hardware.org/?probe=bce90f59c8) | Jun 16, 2022 |
| ASRock        | H370M-HDV                   | [4d6a88cd74](https://linux-hardware.org/?probe=4d6a88cd74) | Jun 16, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [6c1c388f3a](https://linux-hardware.org/?probe=6c1c388f3a) | Jun 15, 2022 |
| HP            | 1790                        | [341a6c4c70](https://linux-hardware.org/?probe=341a6c4c70) | Jun 15, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Linux_Mint/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Linux Mint 20.3 | 991      | 17.38%  |
| Linux Mint 20.1 | 896      | 15.71%  |
| Linux Mint 20.2 | 874      | 15.33%  |
| Linux Mint 19.3 | 847      | 14.85%  |
| Linux Mint 20   | 776      | 13.61%  |
| Linux Mint 19.1 | 401      | 7.03%   |
| Linux Mint 19.2 | 319      | 5.59%   |
| Linux Mint 21   | 255      | 4.47%   |
| Linux Mint 19   | 151      | 2.65%   |
| Linux Mint 18.3 | 133      | 2.33%   |
| Linux Mint 18.2 | 30       | 0.53%   |
| Linux Mint 18.1 | 12       | 0.21%   |
| Linux Mint 18   | 9        | 0.16%   |
| Linux Mint 17.3 | 5        | 0.09%   |
| Linux Mint 17.1 | 2        | 0.04%   |
| Linux Mint 13   | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Linux Mint | 5277     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.0-91-generic  | 229      | 3.57%   |
| 5.4.0-58-generic  | 208      | 3.24%   |
| 5.4.0-42-generic  | 149      | 2.32%   |
| 5.4.0-74-generic  | 147      | 2.29%   |
| 5.4.0-65-generic  | 147      | 2.29%   |
| 5.4.0-77-generic  | 131      | 2.04%   |
| 5.4.0-81-generic  | 115      | 1.79%   |
| 5.4.0-72-generic  | 113      | 1.76%   |
| 5.0.0-32-generic  | 113      | 1.76%   |
| 5.4.0-66-generic  | 112      | 1.74%   |
| 5.4.0-88-generic  | 110      | 1.71%   |
| 4.15.0-54-generic | 106      | 1.65%   |
| 5.4.0-90-generic  | 105      | 1.64%   |
| 5.4.0-70-generic  | 105      | 1.64%   |
| 5.4.0-122-generic | 103      | 1.6%    |
| 5.4.0-73-generic  | 102      | 1.59%   |
| 5.4.0-107-generic | 101      | 1.57%   |
| 4.15.0-20-generic | 101      | 1.57%   |
| 5.4.0-80-generic  | 98       | 1.53%   |
| 5.4.0-89-generic  | 91       | 1.42%   |
| 5.4.0-100-generic | 89       | 1.39%   |
| 5.4.0-26-generic  | 83       | 1.29%   |
| 5.4.0-109-generic | 78       | 1.21%   |
| 5.4.0-48-generic  | 76       | 1.18%   |
| 5.4.0-121-generic | 74       | 1.15%   |
| 4.15.0-46-generic | 70       | 1.09%   |
| 5.4.0-52-generic  | 63       | 0.98%   |
| 5.4.0-96-generic  | 62       | 0.97%   |
| 5.15.0-48-generic | 62       | 0.97%   |
| 5.4.0-104-generic | 58       | 0.9%    |
| 5.4.0-84-generic  | 57       | 0.89%   |
| 5.4.0-113-generic | 57       | 0.89%   |
| 5.3.0-46-generic  | 57       | 0.89%   |
| 5.15.0-47-generic | 56       | 0.87%   |
| 5.4.0-67-generic  | 53       | 0.83%   |
| 5.4.0-125-generic | 50       | 0.78%   |
| 5.3.0-40-generic  | 50       | 0.78%   |
| 5.4.0-99-generic  | 49       | 0.76%   |
| 5.4.0-97-generic  | 49       | 0.76%   |
| 5.4.0-92-generic  | 47       | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 3267     | 58.39%  |
| 4.15.0  | 888      | 15.87%  |
| 5.3.0   | 355      | 6.34%   |
| 5.15.0  | 317      | 5.67%   |
| 5.0.0   | 186      | 3.32%   |
| 5.13.0  | 123      | 2.2%    |
| 5.8.0   | 99       | 1.77%   |
| 5.11.0  | 71       | 1.27%   |
| 4.4.0   | 35       | 0.63%   |
| 4.10.0  | 34       | 0.61%   |
| 4.13.0  | 26       | 0.46%   |
| 4.18.0  | 23       | 0.41%   |
| 4.8.0   | 14       | 0.25%   |
| 5.14.0  | 10       | 0.18%   |
| 5.9.0   | 5        | 0.09%   |
| 5.10.0  | 5        | 0.09%   |
| 5.3.6   | 4        | 0.07%   |
| 5.17.0  | 4        | 0.07%   |
| 5.4.1   | 3        | 0.05%   |
| 5.16.0  | 3        | 0.05%   |
| 5.12.0  | 3        | 0.05%   |
| 5.0.9   | 3        | 0.05%   |
| 4.20.17 | 3        | 0.05%   |
| 4.11.0  | 3        | 0.05%   |
| 5.8.18  | 2        | 0.04%   |
| 5.7.19  | 2        | 0.04%   |
| 5.7.0   | 2        | 0.04%   |
| 5.19.0  | 2        | 0.04%   |
| 5.18.12 | 2        | 0.04%   |
| 5.17.9  | 2        | 0.04%   |
| 5.15.5  | 2        | 0.04%   |
| 5.15.10 | 2        | 0.04%   |
| 5.13.4  | 2        | 0.04%   |
| 5.12.9  | 2        | 0.04%   |
| 5.11.6  | 2        | 0.04%   |
| 5.10.1  | 2        | 0.04%   |
| 5.0.21  | 2        | 0.04%   |
| 4.20.6  | 2        | 0.04%   |
| 4.16.0  | 2        | 0.04%   |
| 3.19.0  | 2        | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 3273     | 58.53%  |
| 4.15    | 889      | 15.9%   |
| 5.3     | 361      | 6.46%   |
| 5.15    | 326      | 5.83%   |
| 5.0     | 197      | 3.52%   |
| 5.13    | 126      | 2.25%   |
| 5.8     | 103      | 1.84%   |
| 5.11    | 77       | 1.38%   |
| 4.4     | 35       | 0.63%   |
| 4.10    | 34       | 0.61%   |
| 4.13    | 27       | 0.48%   |
| 4.18    | 24       | 0.43%   |
| 5.10    | 14       | 0.25%   |
| 4.8     | 14       | 0.25%   |
| 5.17    | 11       | 0.2%    |
| 5.14    | 11       | 0.2%    |
| 5.9     | 8        | 0.14%   |
| 5.7     | 8        | 0.14%   |
| 4.20    | 8        | 0.14%   |
| 5.16    | 6        | 0.11%   |
| 5.12    | 5        | 0.09%   |
| 5.18    | 4        | 0.07%   |
| 5.6     | 3        | 0.05%   |
| 5.5     | 3        | 0.05%   |
| 5.2     | 3        | 0.05%   |
| 4.14    | 3        | 0.05%   |
| 4.11    | 3        | 0.05%   |
| 5.19    | 2        | 0.04%   |
| 4.19    | 2        | 0.04%   |
| 4.16    | 2        | 0.04%   |
| 4.12    | 2        | 0.04%   |
| 3.19    | 2        | 0.04%   |
| 3.13    | 2        | 0.04%   |
| 6.0     | 1        | 0.02%   |
| 4.17    | 1        | 0.02%   |
| 3.2     | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 5091     | 96.37%  |
| i686   | 192      | 3.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| X-Cinnamon      | 3092     | 56.81%  |
| MATE            | 682      | 12.53%  |
| Cinnamon        | 532      | 9.77%   |
| Unknown         | 524      | 9.63%   |
| XFCE            | 448      | 8.23%   |
| GNOME           | 102      | 1.87%   |
| KDE5            | 23       | 0.42%   |
| KDE             | 20       | 0.37%   |
| LXDE            | 6        | 0.11%   |
| Pantheon        | 2        | 0.04%   |
| KDE4            | 2        | 0.04%   |
| i3              | 2        | 0.04%   |
| Budgie          | 2        | 0.04%   |
| Trinity         | 1        | 0.02%   |
| qtile           | 1        | 0.02%   |
| LXQt            | 1        | 0.02%   |
| GNOME Flashback | 1        | 0.02%   |
| GNOME Classic   | 1        | 0.02%   |
| enlightenment   | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 5240     | 99.17%  |
| Tty     | 31       | 0.59%   |
| Wayland | 10       | 0.19%   |
| Unknown | 3        | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3502     | 65.24%  |
| LightDM | 1014     | 18.89%  |
| TDM     | 775      | 14.44%  |
| MDM     | 41       | 0.76%   |
| SDDM    | 21       | 0.39%   |
| GDM     | 14       | 0.26%   |
| GDM3    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1324     | 24.66%  |
| de_DE   | 756      | 14.08%  |
| Unknown | 679      | 12.64%  |
| pt_BR   | 422      | 7.86%   |
| ru_RU   | 230      | 4.28%   |
| en_GB   | 219      | 4.08%   |
| fr_FR   | 215      | 4%      |
| en_CA   | 137      | 2.55%   |
| it_IT   | 135      | 2.51%   |
| C       | 120      | 2.23%   |
| es_ES   | 119      | 2.22%   |
| pl_PL   | 98       | 1.82%   |
| en_AU   | 96       | 1.79%   |
| nl_NL   | 67       | 1.25%   |
| es_AR   | 59       | 1.1%    |
| pt_PT   | 40       | 0.74%   |
| cs_CZ   | 39       | 0.73%   |
| ru_UA   | 36       | 0.67%   |
| hu_HU   | 32       | 0.6%    |
| es_MX   | 32       | 0.6%    |
| de_AT   | 30       | 0.56%   |
| en_IN   | 29       | 0.54%   |
| en_ZA   | 28       | 0.52%   |
| fi_FI   | 26       | 0.48%   |
| de_CH   | 26       | 0.48%   |
| fr_CA   | 24       | 0.45%   |
| sv_SE   | 21       | 0.39%   |
| sk_SK   | 21       | 0.39%   |
| en_NZ   | 19       | 0.35%   |
| fr_BE   | 18       | 0.34%   |
| uk_UA   | 16       | 0.3%    |
| tr_TR   | 15       | 0.28%   |
| es_CO   | 14       | 0.26%   |
| es_CL   | 14       | 0.26%   |
| en_IE   | 14       | 0.26%   |
| el_GR   | 12       | 0.22%   |
| nl_BE   | 11       | 0.2%    |
| es_PE   | 11       | 0.2%    |
| da_DK   | 11       | 0.2%    |
| zh_CN   | 10       | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3405     | 63.64%  |
| EFI  | 1945     | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 4590     | 85.51%  |
| Unknown | 512      | 9.54%   |
| Btrfs   | 105      | 1.96%   |
| Overlay | 102      | 1.9%    |
| Xfs     | 18       | 0.34%   |
| Ext2    | 15       | 0.28%   |
| Ext3    | 14       | 0.26%   |
| Zfs     | 7        | 0.13%   |
| Jfs     | 2        | 0.04%   |
| Aufs    | 2        | 0.04%   |
| Tmpfs   | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3586     | 67.03%  |
| GPT     | 1071     | 20.02%  |
| MBR     | 693      | 12.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4838     | 90.75%  |
| Yes       | 493      | 9.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4288     | 80.28%  |
| Yes       | 1053     | 19.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1297     | 24.58%  |
| Gigabyte Technology | 891      | 16.88%  |
| MSI                 | 551      | 10.44%  |
| ASRock              | 512      | 9.7%    |
| Dell                | 439      | 8.32%   |
| Hewlett-Packard     | 394      | 7.47%   |
| Lenovo              | 175      | 3.32%   |
| Intel               | 150      | 2.84%   |
| Acer                | 101      | 1.91%   |
| Pegatron            | 87       | 1.65%   |
| Biostar             | 65       | 1.23%   |
| Unknown             | 65       | 1.23%   |
| Foxconn             | 62       | 1.17%   |
| ECS                 | 57       | 1.08%   |
| Fujitsu             | 45       | 0.85%   |
| Medion              | 41       | 0.78%   |
| Positivo            | 31       | 0.59%   |
| Fujitsu Siemens     | 26       | 0.49%   |
| PCWare              | 17       | 0.32%   |
| Apple               | 15       | 0.28%   |
| Shuttle             | 14       | 0.27%   |
| Gateway             | 14       | 0.27%   |
| Semp Toshiba        | 12       | 0.23%   |
| eMachines           | 12       | 0.23%   |
| Packard Bell        | 11       | 0.21%   |
| OEM                 | 10       | 0.19%   |
| AZW                 | 10       | 0.19%   |
| BESSTAR Tech        | 9        | 0.17%   |
| Itautec             | 8        | 0.15%   |
| Huanan              | 8        | 0.15%   |
| AMI                 | 8        | 0.15%   |
| Alienware           | 8        | 0.15%   |
| Supermicro          | 6        | 0.11%   |
| ABIT                | 5        | 0.09%   |
| Wistron             | 4        | 0.08%   |
| TYAN Computer       | 4        | 0.08%   |
| PCChips             | 4        | 0.08%   |
| Megaware            | 4        | 0.08%   |
| AMD                 | 4        | 0.08%   |
| ZOTAC               | 3        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 119      | 2.26%   |
| Unknown                      | 75       | 1.42%   |
| Dell OptiPlex 790            | 28       | 0.53%   |
| Dell OptiPlex 7010           | 28       | 0.53%   |
| MSI MS-7693                  | 26       | 0.49%   |
| ASUS M5A78L-M/USB3           | 25       | 0.47%   |
| Dell OptiPlex 780            | 24       | 0.45%   |
| Gigabyte B450M DS3H          | 21       | 0.4%    |
| ASUS PRIME A320M-K           | 21       | 0.4%    |
| ASUS TUF Gaming X570-PLUS    | 20       | 0.38%   |
| MSI MS-7C37                  | 19       | 0.36%   |
| MSI MS-7817                  | 19       | 0.36%   |
| MSI MS-7721                  | 19       | 0.36%   |
| Dell OptiPlex 755            | 19       | 0.36%   |
| MSI MS-7C56                  | 17       | 0.32%   |
| MSI MS-7C02                  | 17       | 0.32%   |
| Dell OptiPlex 9020           | 17       | 0.32%   |
| HP EliteDesk 800 G1 SFF      | 16       | 0.3%    |
| Gigabyte 970A-DS3P           | 16       | 0.3%    |
| Dell OptiPlex 390            | 16       | 0.3%    |
| Dell OptiPlex 3020           | 16       | 0.3%    |
| MSI MS-7B86                  | 15       | 0.28%   |
| HP Compaq Elite 8300 SFF     | 15       | 0.28%   |
| Dell OptiPlex 990            | 15       | 0.28%   |
| ASUS ROG STRIX B450-F GAMING | 15       | 0.28%   |
| ASUS M5A97 R2.0              | 15       | 0.28%   |
| ASUS M5A78L-M PLUS/USB3      | 15       | 0.28%   |
| MSI MS-7B79                  | 14       | 0.27%   |
| MSI MS-7641                  | 14       | 0.27%   |
| HP Compaq 8200 Elite SFF PC  | 14       | 0.27%   |
| Gigabyte G31M-ES2L           | 14       | 0.27%   |
| MSI MS-7A34                  | 13       | 0.25%   |
| Intel H61                    | 13       | 0.25%   |
| Dell OptiPlex 745            | 13       | 0.25%   |
| ASUS PRIME B450M-A           | 13       | 0.25%   |
| ASRock N68C-S UCC            | 13       | 0.25%   |
| MSI MS-7C91                  | 12       | 0.23%   |
| Dell OptiPlex 3010           | 12       | 0.23%   |
| ASUS PRIME B350-PLUS         | 12       | 0.23%   |
| ASRock B450M Pro4            | 12       | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 273      | 5.17%   |
| ASUS PRIME              | 199      | 3.77%   |
| HP Compaq               | 181      | 3.43%   |
| ASUS All                | 119      | 2.26%   |
| Lenovo ThinkCentre      | 112      | 2.12%   |
| ASUS ROG                | 86       | 1.63%   |
| ASUS TUF                | 76       | 1.44%   |
| Unknown                 | 75       | 1.42%   |
| Acer Aspire             | 68       | 1.29%   |
| ASUS M5A78L-M           | 62       | 1.17%   |
| Dell Inspiron           | 60       | 1.14%   |
| HP EliteDesk            | 50       | 0.95%   |
| Dell Precision          | 43       | 0.81%   |
| ASUS P8H61-M            | 37       | 0.7%    |
| ASUS M5A97              | 36       | 0.68%   |
| Gigabyte B450           | 33       | 0.63%   |
| Fujitsu ESPRIMO         | 30       | 0.57%   |
| HP ProDesk              | 29       | 0.55%   |
| Gigabyte B450M          | 29       | 0.55%   |
| Gigabyte GA-78LMT-USB3  | 28       | 0.53%   |
| MSI MS-7693             | 26       | 0.49%   |
| ASRock B450M            | 26       | 0.49%   |
| ASUS SABERTOOTH         | 25       | 0.47%   |
| Acer Veriton            | 23       | 0.44%   |
| Gigabyte X570           | 22       | 0.42%   |
| Lenovo IdeaCentre       | 21       | 0.4%    |
| Gigabyte B550           | 21       | 0.4%    |
| Dell Vostro             | 20       | 0.38%   |
| MSI MS-7C37             | 19       | 0.36%   |
| MSI MS-7817             | 19       | 0.36%   |
| MSI MS-7721             | 19       | 0.36%   |
| ASUS P5KPL-AM           | 18       | 0.34%   |
| MSI MS-7C56             | 17       | 0.32%   |
| MSI MS-7C02             | 17       | 0.32%   |
| HP Pavilion             | 17       | 0.32%   |
| Gigabyte Z390           | 17       | 0.32%   |
| Gigabyte A320M-S2H      | 17       | 0.32%   |
| Gigabyte 970A-DS3P      | 17       | 0.32%   |
| ASUS P5G41T-M           | 17       | 0.32%   |
| Fujitsu Siemens ESPRIMO | 16       | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 567      | 10.74%  |
| 2011    | 507      | 9.61%   |
| 2013    | 479      | 9.08%   |
| 2018    | 454      | 8.6%    |
| 2009    | 362      | 6.86%   |
| 2010    | 358      | 6.78%   |
| 2014    | 348      | 6.59%   |
| 2020    | 311      | 5.89%   |
| 2019    | 301      | 5.7%    |
| 2017    | 290      | 5.5%    |
| 2008    | 280      | 5.31%   |
| 2007    | 239      | 4.53%   |
| 2015    | 230      | 4.36%   |
| 2016    | 209      | 3.96%   |
| 2021    | 147      | 2.79%   |
| 2006    | 110      | 2.08%   |
| 2005    | 32       | 0.61%   |
| 2022    | 23       | 0.44%   |
| 2004    | 14       | 0.27%   |
| 2003    | 11       | 0.21%   |
| 2002    | 3        | 0.06%   |
| Unknown | 2        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 5277     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 5134     | 97.05%  |
| Enabled  | 156      | 2.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 5275     | 99.96%  |
| Yes  | 2        | 0.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1231     | 22.88%  |
| 8.01-16.0       | 1135     | 21.09%  |
| 3.01-4.0        | 1022     | 18.99%  |
| 4.01-8.0        | 876      | 16.28%  |
| 32.01-64.0      | 560      | 10.41%  |
| 1.01-2.0        | 234      | 4.35%   |
| 64.01-256.0     | 116      | 2.16%   |
| 2.01-3.0        | 92       | 1.71%   |
| 24.01-32.0      | 80       | 1.49%   |
| 0.51-1.0        | 32       | 0.59%   |
| More than 256.0 | 2        | 0.04%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 2318     | 39.09%  |
| 2.01-3.0   | 1519     | 25.62%  |
| 4.01-8.0   | 695      | 11.72%  |
| 3.01-4.0   | 676      | 11.4%   |
| 0.51-1.0   | 494      | 8.33%   |
| 8.01-16.0  | 169      | 2.85%   |
| 0.01-0.5   | 22       | 0.37%   |
| 16.01-24.0 | 21       | 0.35%   |
| 24.01-32.0 | 11       | 0.19%   |
| Unknown    | 3        | 0.05%   |
| 32.01-64.0 | 2        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2217     | 40.35%  |
| 2       | 1645     | 29.94%  |
| 3       | 843      | 15.34%  |
| 4       | 427      | 7.77%   |
| 5       | 183      | 3.33%   |
| 6       | 76       | 1.38%   |
| 7       | 41       | 0.75%   |
| 0       | 29       | 0.53%   |
| 8       | 18       | 0.33%   |
| 9       | 8        | 0.15%   |
| 10      | 4        | 0.07%   |
| 14      | 2        | 0.04%   |
| 22      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3096     | 57.98%  |
| No        | 2244     | 42.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 5211     | 98.71%  |
| No        | 68       | 1.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3120     | 58.26%  |
| Yes       | 2235     | 41.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4014     | 74.9%   |
| Yes       | 1345     | 25.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 919      | 17.33%  |
| Germany      | 850      | 16.03%  |
| Brazil       | 615      | 11.6%   |
| Russia       | 357      | 6.73%   |
| France       | 236      | 4.45%   |
| UK           | 218      | 4.11%   |
| Canada       | 194      | 3.66%   |
| Italy        | 152      | 2.87%   |
| Spain        | 144      | 2.72%   |
| Poland       | 119      | 2.24%   |
| Netherlands  | 115      | 2.17%   |
| Australia    | 112      | 2.11%   |
| Ukraine      | 106      | 2%      |
| Argentina    | 64       | 1.21%   |
| Switzerland  | 56       | 1.06%   |
| Austria      | 53       | 1%      |
| Belgium      | 52       | 0.98%   |
| Czechia      | 48       | 0.91%   |
| Mexico       | 47       | 0.89%   |
| Sweden       | 44       | 0.83%   |
| Hungary      | 44       | 0.83%   |
| Portugal     | 41       | 0.77%   |
| Finland      | 37       | 0.7%    |
| India        | 36       | 0.68%   |
| South Africa | 35       | 0.66%   |
| Romania      | 27       | 0.51%   |
| Greece       | 27       | 0.51%   |
| Denmark      | 25       | 0.47%   |
| Slovakia     | 24       | 0.45%   |
| Belarus      | 24       | 0.45%   |
| Turkey       | 23       | 0.43%   |
| New Zealand  | 22       | 0.41%   |
| Colombia     | 22       | 0.41%   |
| Japan        | 20       | 0.38%   |
| Serbia       | 19       | 0.36%   |
| Bulgaria     | 19       | 0.36%   |
| Chile        | 18       | 0.34%   |
| Norway       | 17       | 0.32%   |
| Ireland      | 17       | 0.32%   |
| Indonesia    | 16       | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Sao Paulo         | 75       | 1.34%   |
| Moscow            | 69       | 1.23%   |
| Berlin            | 58       | 1.04%   |
| Rio de Janeiro    | 38       | 0.68%   |
| Vienna            | 35       | 0.63%   |
| Hamburg           | 35       | 0.63%   |
| Paris             | 29       | 0.52%   |
| Munich            | 29       | 0.52%   |
| St Petersburg     | 26       | 0.46%   |
| Montreal          | 26       | 0.46%   |
| Warsaw            | 25       | 0.45%   |
| Frankfurt am Main | 25       | 0.45%   |
| Sydney            | 24       | 0.43%   |
| Madrid            | 24       | 0.43%   |
| Amsterdam         | 24       | 0.43%   |
| Kyiv              | 23       | 0.41%   |
| London            | 21       | 0.38%   |
| Brasília         | 21       | 0.38%   |
| Rome              | 19       | 0.34%   |
| New York          | 19       | 0.34%   |
| Leipzig           | 19       | 0.34%   |
| Chicago           | 19       | 0.34%   |
| Budapest          | 19       | 0.34%   |
| Cologne           | 18       | 0.32%   |
| Brisbane          | 17       | 0.3%    |
| Vancouver         | 16       | 0.29%   |
| Toronto           | 16       | 0.29%   |
| Milan             | 16       | 0.29%   |
| Melbourne         | 16       | 0.29%   |
| Helsinki          | 15       | 0.27%   |
| Porto Alegre      | 14       | 0.25%   |
| Perth             | 14       | 0.25%   |
| Düsseldorf       | 14       | 0.25%   |
| Athens            | 14       | 0.25%   |
| Stuttgart         | 13       | 0.23%   |
| Minsk             | 13       | 0.23%   |
| Mexico City       | 13       | 0.23%   |
| Dresden           | 13       | 0.23%   |
| Curitiba          | 13       | 0.23%   |
| Belo Horizonte    | 13       | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 1999     | 3334   | 21.38%  |
| Seagate                   | 1950     | 3178   | 20.85%  |
| Samsung Electronics       | 1338     | 2132   | 14.31%  |
| Kingston                  | 586      | 792    | 6.27%   |
| Toshiba                   | 442      | 576    | 4.73%   |
| Hitachi                   | 408      | 548    | 4.36%   |
| Crucial                   | 377      | 524    | 4.03%   |
| SanDisk                   | 361      | 515    | 3.86%   |
| A-DATA Technology         | 141      | 187    | 1.51%   |
| Maxtor                    | 114      | 159    | 1.22%   |
| Intel                     | 109      | 157    | 1.17%   |
| Unknown                   | 92       | 146    | 0.98%   |
| HGST                      | 91       | 132    | 0.97%   |
| China                     | 89       | 109    | 0.95%   |
| Intenso                   | 76       | 100    | 0.81%   |
| Phison                    | 69       | 100    | 0.74%   |
| OCZ                       | 57       | 73     | 0.61%   |
| SPCC                      | 56       | 75     | 0.6%    |
| Patriot                   | 55       | 66     | 0.59%   |
| Corsair                   | 50       | 59     | 0.53%   |
| PNY                       | 47       | 62     | 0.5%    |
| Silicon Motion            | 40       | 65     | 0.43%   |
| Transcend                 | 39       | 61     | 0.42%   |
| GOODRAM                   | 34       | 41     | 0.36%   |
| SK hynix                  | 33       | 44     | 0.35%   |
| Micron Technology         | 33       | 39     | 0.35%   |
| XPG                       | 27       | 38     | 0.29%   |
| Apacer                    | 26       | 30     | 0.28%   |
| Micron/Crucial Technology | 24       | 34     | 0.26%   |
| JMicron Technology        | 23       | 28     | 0.25%   |
| Plextor                   | 22       | 30     | 0.24%   |
| Fujitsu                   | 21       | 30     | 0.22%   |
| Team                      | 20       | 26     | 0.21%   |
| ASMT                      | 19       | 28     | 0.2%    |
| Unknown                   | 19       | 29     | 0.2%    |
| Lexar                     | 18       | 20     | 0.19%   |
| KingSpec                  | 17       | 30     | 0.18%   |
| Hewlett-Packard           | 17       | 20     | 0.18%   |
| LITEON                    | 15       | 16     | 0.16%   |
| Realtek Semiconductor     | 14       | 18     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 162      | 1.5%    |
| Kingston SA400S37240G 240GB SSD  | 140      | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB   | 113      | 1.05%   |
| Toshiba DT01ACA100 1TB           | 111      | 1.03%   |
| Samsung SSD 850 EVO 250GB        | 103      | 0.95%   |
| Samsung SSD 860 EVO 500GB        | 92       | 0.85%   |
| Kingston SA400S37120G 120GB SSD  | 86       | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB         | 80       | 0.74%   |
| Kingston SV300S37A120G 120GB SSD | 79       | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB   | 78       | 0.72%   |
| Seagate ST3500418AS 500GB        | 76       | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB   | 75       | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB   | 68       | 0.63%   |
| Samsung SSD 850 EVO 500GB        | 67       | 0.62%   |
| Crucial CT240BX500SSD1 240GB     | 63       | 0.58%   |
| Samsung SSD 860 EVO 250GB        | 62       | 0.57%   |
| Samsung SSD 860 EVO 1TB          | 62       | 0.57%   |
| Seagate ST2000DM006-2DM164 2TB   | 59       | 0.55%   |
| Samsung NVMe SSD Drive 500GB     | 57       | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB         | 55       | 0.51%   |
| Kingston SA400S37480G 480GB SSD  | 53       | 0.49%   |
| Crucial CT500MX500SSD1 500GB     | 53       | 0.49%   |
| Seagate ST31000524AS 1TB         | 52       | 0.48%   |
| Crucial CT1000MX500SSD1 1TB      | 51       | 0.47%   |
| Seagate ST31000528AS 1TB         | 50       | 0.46%   |
| Toshiba HDWD110 1TB              | 48       | 0.44%   |
| Seagate Expansion 2TB            | 47       | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB   | 46       | 0.43%   |
| Seagate ST3500413AS 500GB        | 43       | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB   | 43       | 0.4%    |
| SanDisk SSD PLUS 240GB           | 42       | 0.39%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 41       | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 40       | 0.37%   |
| Toshiba DT01ACA050 500GB         | 39       | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB   | 39       | 0.36%   |
| SanDisk SDSSDA240G 240GB         | 39       | 0.36%   |
| Toshiba DT01ACA200 2TB           | 38       | 0.35%   |
| Unknown SD/MMC/MS PRO 1TB        | 36       | 0.33%   |
| Seagate ST1000DM003-1SB102 1TB   | 36       | 0.33%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 34       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1918     | 3091   | 35.85%  |
| WDC                 | 1809     | 2997   | 33.81%  |
| Samsung Electronics | 443      | 630    | 8.28%   |
| Toshiba             | 412      | 530    | 7.7%    |
| Hitachi             | 408      | 548    | 7.63%   |
| Maxtor              | 112      | 157    | 2.09%   |
| HGST                | 91       | 132    | 1.7%    |
| Unknown             | 43       | 57     | 0.8%    |
| Fujitsu             | 20       | 29     | 0.37%   |
| SABRENT             | 12       | 13     | 0.22%   |
| Intenso             | 10       | 11     | 0.19%   |
| ExcelStor           | 6        | 8      | 0.11%   |
| ASMT                | 6        | 12     | 0.11%   |
| WD MediaMax         | 5        | 12     | 0.09%   |
| JMicron Technology  | 5        | 7      | 0.09%   |
| Hewlett-Packard     | 5        | 6      | 0.09%   |
| ASMT109x            | 3        | 3      | 0.06%   |
| ASMedia             | 3        | 3      | 0.06%   |
| Apple               | 3        | 3      | 0.06%   |
| USB3.0              | 2        | 2      | 0.04%   |
| SAGE                | 2        | 2      | 0.04%   |
| RSH-319             | 2        | 2      | 0.04%   |
| PHD 3.0             | 2        | 3      | 0.04%   |
| Maxtor 6            | 2        | 3      | 0.04%   |
| Maxone              | 2        | 2      | 0.04%   |
| HPE                 | 2        | 3      | 0.04%   |
| Unknown             | 2        | 4      | 0.04%   |
| USB 3.0             | 1        | 3      | 0.02%   |
| USB                 | 1        | 1      | 0.02%   |
| TrueNAS             | 1        | 3      | 0.02%   |
| TANDBERG            | 1        | 1      | 0.02%   |
| Synology            | 1        | 1      | 0.02%   |
| Storeva             | 1        | 1      | 0.02%   |
| SATAFIRM            | 1        | 1      | 0.02%   |
| Quantum             | 1        | 1      | 0.02%   |
| MaxDigital          | 1        | 1      | 0.02%   |
| MARVELL             | 1        | 1      | 0.02%   |
| Magnetic Data       | 1        | 1      | 0.02%   |
| LaCie               | 1        | 1      | 0.02%   |
| KESU                | 1        | 2      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 690      | 1047   | 21.89%  |
| Kingston            | 520      | 695    | 16.5%   |
| Crucial             | 354      | 494    | 11.23%  |
| SanDisk             | 302      | 427    | 9.58%   |
| WDC                 | 215      | 289    | 6.82%   |
| A-DATA Technology   | 112      | 150    | 3.55%   |
| China               | 87       | 107    | 2.76%   |
| Intel               | 65       | 86     | 2.06%   |
| OCZ                 | 56       | 71     | 1.78%   |
| Intenso             | 55       | 74     | 1.74%   |
| SPCC                | 52       | 71     | 1.65%   |
| Patriot             | 52       | 63     | 1.65%   |
| PNY                 | 43       | 57     | 1.36%   |
| Transcend           | 35       | 50     | 1.11%   |
| Corsair             | 35       | 40     | 1.11%   |
| GOODRAM             | 33       | 40     | 1.05%   |
| Toshiba             | 32       | 40     | 1.02%   |
| Micron Technology   | 25       | 31     | 0.79%   |
| Apacer              | 23       | 27     | 0.73%   |
| Team                | 19       | 25     | 0.6%    |
| Plextor             | 19       | 24     | 0.6%    |
| SK hynix            | 18       | 22     | 0.57%   |
| KingSpec            | 17       | 30     | 0.54%   |
| Lexar               | 16       | 18     | 0.51%   |
| LITEON              | 14       | 15     | 0.44%   |
| Seagate             | 13       | 23     | 0.41%   |
| TO Exter            | 12       | 16     | 0.38%   |
| ASMT                | 12       | 15     | 0.38%   |
| Unknown             | 11       | 18     | 0.35%   |
| LITEONIT            | 10       | 10     | 0.32%   |
| Hewlett-Packard     | 9        | 11     | 0.29%   |
| KingDian            | 8        | 9      | 0.25%   |
| Gigabyte Technology | 8        | 17     | 0.25%   |
| AMD                 | 8        | 8      | 0.25%   |
| Unknown             | 7        | 7      | 0.22%   |
| Smartbuy            | 7        | 11     | 0.22%   |
| Mushkin             | 7        | 10     | 0.22%   |
| Verbatim            | 6        | 7      | 0.19%   |
| Leven               | 6        | 6      | 0.19%   |
| Pioneer             | 5        | 6      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 4050     | 8297   | 52.46%  |
| SSD     | 2659     | 4329   | 34.44%  |
| NVMe    | 836      | 1249   | 10.83%  |
| Unknown | 154      | 224    | 1.99%   |
| MMC     | 21       | 33     | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4999     | 12220  | 79.77%  |
| NVMe | 827      | 1230   | 13.2%   |
| SAS  | 420      | 649    | 6.7%    |
| MMC  | 21       | 33     | 0.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 3847     | 7045   | 52.76%  |
| 0.51-1.0   | 2048     | 3246   | 28.09%  |
| 1.01-2.0   | 830      | 1365   | 11.38%  |
| 3.01-4.0   | 234      | 424    | 3.21%   |
| 2.01-3.0   | 189      | 300    | 2.59%   |
| 4.01-10.0  | 123      | 204    | 1.69%   |
| 10.01-20.0 | 19       | 40     | 0.26%   |
| 0          | 2        | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1407     | 25.08%  |
| 251-500        | 1084     | 19.33%  |
| 501-1000       | 939      | 16.74%  |
| 1001-2000      | 697      | 12.43%  |
| More than 3000 | 534      | 9.52%   |
| 2001-3000      | 341      | 6.08%   |
| 51-100         | 328      | 5.85%   |
| 21-50          | 140      | 2.5%    |
| 1-20           | 103      | 1.84%   |
| Unknown        | 36       | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1293     | 22.11%  |
| 21-50          | 1104     | 18.88%  |
| 101-250        | 863      | 14.76%  |
| 51-100         | 752      | 12.86%  |
| 501-1000       | 539      | 9.22%   |
| 251-500        | 536      | 9.17%   |
| 1001-2000      | 370      | 6.33%   |
| More than 3000 | 203      | 3.47%   |
| 2001-3000      | 151      | 2.58%   |
| Unknown        | 36       | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 23       | 23     | 3.58%   |
| Seagate ST3500418AS 500GB             | 15       | 17     | 2.34%   |
| Seagate ST31000528AS 1TB              | 7        | 9      | 1.09%   |
| WDC WD10EARS-00Y5B1 1TB               | 6        | 6      | 0.93%   |
| Seagate ST3500320AS 500GB             | 6        | 8      | 0.93%   |
| Seagate ST31000524AS 1TB              | 6        | 7      | 0.93%   |
| Seagate ST1000DM003-9YN162 1TB        | 6        | 6      | 0.93%   |
| WDC WD10EZEX-00BN5A0 1TB              | 5        | 6      | 0.78%   |
| Seagate ST3250318AS 250GB             | 5        | 6      | 0.78%   |
| Seagate ST2000DM001-1CH164 2TB        | 5        | 5      | 0.78%   |
| Seagate ST1000DM003-1CH162 1TB        | 5        | 6      | 0.78%   |
| Samsung Electronics HD502HI 500GB     | 5        | 5      | 0.78%   |
| Samsung Electronics HD322HJ 320GB     | 5        | 7      | 0.78%   |
| Crucial CT525MX300SSD1 528GB          | 5        | 5      | 0.78%   |
| WDC WD5000AAKS-00A7B0 500GB           | 4        | 4      | 0.62%   |
| WDC WD3200AAJS-00L7A0 320GB           | 4        | 4      | 0.62%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 4        | 4      | 0.62%   |
| Seagate ST31500341AS 1TB              | 4        | 5      | 0.62%   |
| Seagate ST2000DM001-9YN164 2TB        | 4        | 4      | 0.62%   |
| Seagate ST1500DL003-9VT16L 1TB        | 4        | 4      | 0.62%   |
| Samsung Electronics SSD 970 EVO 500GB | 4        | 5      | 0.62%   |
| Samsung Electronics HD501LJ 500GB     | 4        | 6      | 0.62%   |
| Samsung Electronics HD161HJ 160GB     | 4        | 4      | 0.62%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 4      | 0.62%   |
| Maxtor STM3250310AS 250GB             | 4        | 5      | 0.62%   |
| Hitachi HDS721010CLA332 1TB           | 4        | 4      | 0.62%   |
| WDC WD5000AAKX-003CA0 500GB           | 3        | 3      | 0.47%   |
| WDC WD5000AAKX-001CA0 500GB           | 3        | 3      | 0.47%   |
| WDC WD40EFRX-68WT0N0 4TB              | 3        | 6      | 0.47%   |
| WDC WD3200AAJS-56M0A0 320GB           | 3        | 3      | 0.47%   |
| WDC WD20EZRX-00DC0B0 2TB              | 3        | 7      | 0.47%   |
| Seagate ST9320325AS 320GB             | 3        | 3      | 0.47%   |
| Seagate ST9250315AS 250GB             | 3        | 3      | 0.47%   |
| Seagate ST500LT012-1DG142 500GB       | 3        | 3      | 0.47%   |
| Seagate ST3500413AS 500GB             | 3        | 5      | 0.47%   |
| Seagate ST3250820AS 250GB             | 3        | 3      | 0.47%   |
| Seagate ST320LT012-1DG14C 320GB       | 3        | 3      | 0.47%   |
| Seagate ST31000333AS 1TB              | 3        | 3      | 0.47%   |
| Seagate ST2000DM006-2DM164 2TB        | 3        | 3      | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB        | 3        | 4      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 196      | 231    | 32.18%  |
| WDC                 | 168      | 211    | 27.59%  |
| Samsung Electronics | 71       | 85     | 11.66%  |
| Hitachi             | 47       | 55     | 7.72%   |
| Toshiba             | 16       | 16     | 2.63%   |
| Maxtor              | 16       | 21     | 2.63%   |
| Crucial             | 14       | 15     | 2.3%    |
| SanDisk             | 13       | 14     | 2.13%   |
| Kingston            | 13       | 14     | 2.13%   |
| Intel               | 6        | 6      | 0.99%   |
| Corsair             | 6        | 9      | 0.99%   |
| OCZ                 | 5        | 5      | 0.82%   |
| HGST                | 4        | 4      | 0.66%   |
| China               | 4        | 5      | 0.66%   |
| A-DATA Technology   | 3        | 3      | 0.49%   |
| SPCC                | 2        | 3      | 0.33%   |
| SK hynix            | 2        | 2      | 0.33%   |
| Plextor             | 2        | 2      | 0.33%   |
| Micron Technology   | 2        | 3      | 0.33%   |
| LITEONIT            | 2        | 2      | 0.33%   |
| LDLC                | 2        | 2      | 0.33%   |
| Kingmax             | 2        | 2      | 0.33%   |
| Intenso             | 2        | 2      | 0.33%   |
| Unknown             | 1        | 1      | 0.16%   |
| Transcend           | 1        | 1      | 0.16%   |
| Mushkin             | 1        | 1      | 0.16%   |
| Leven               | 1        | 1      | 0.16%   |
| HS-SSD-E100         | 1        | 1      | 0.16%   |
| Hewlett-Packard     | 1        | 1      | 0.16%   |
| Fujitsu             | 1        | 2      | 0.16%   |
| FEASSO              | 1        | 2      | 0.16%   |
| ExcelStor           | 1        | 1      | 0.16%   |
| ASMedia             | 1        | 1      | 0.16%   |
| Unknown             | 1        | 2      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 196      | 231    | 38.43%  |
| WDC                 | 164      | 207    | 32.16%  |
| Samsung Electronics | 60       | 72     | 11.76%  |
| Hitachi             | 47       | 55     | 9.22%   |
| Toshiba             | 16       | 16     | 3.14%   |
| Maxtor              | 16       | 21     | 3.14%   |
| HGST                | 4        | 4      | 0.78%   |
| Unknown             | 1        | 1      | 0.2%    |
| Hewlett-Packard     | 1        | 1      | 0.2%    |
| Fujitsu             | 1        | 2      | 0.2%    |
| FEASSO              | 1        | 2      | 0.2%    |
| ExcelStor           | 1        | 1      | 0.2%    |
| ASMedia             | 1        | 1      | 0.2%    |
| Unknown             | 1        | 2      | 0.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 455      | 616    | 82.28%  |
| SSD  | 88       | 98     | 15.91%  |
| NVMe | 10       | 12     | 1.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD252HJ 250GB | 2        | 2      | 28.57%  |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 14.29%  |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 14.29%  |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 14.29%  |
| Hitachi HDS721050CLA362 500GB     | 1        | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 4      | 57.14%  |
| Hitachi             | 2        | 2      | 28.57%  |
| Toshiba             | 1        | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3653     | 9881   | 62.59%  |
| Works    | 1636     | 3518   | 28.03%  |
| Malfunc  | 540      | 726    | 9.25%   |
| Failed   | 7        | 7      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3340     | 48.8%   |
| AMD                              | 1626     | 23.76%  |
| Samsung Electronics              | 336      | 4.91%   |
| Nvidia                           | 254      | 3.71%   |
| ASMedia Technology               | 214      | 3.13%   |
| JMicron Technology               | 193      | 2.82%   |
| Marvell Technology Group         | 189      | 2.76%   |
| SanDisk                          | 109      | 1.59%   |
| Phison Electronics               | 109      | 1.59%   |
| VIA Technologies                 | 73       | 1.07%   |
| Kingston Technology Company      | 72       | 1.05%   |
| Silicon Motion                   | 59       | 0.86%   |
| Micron/Crucial Technology        | 49       | 0.72%   |
| ADATA Technology                 | 47       | 0.69%   |
| Realtek Semiconductor            | 24       | 0.35%   |
| LSI Logic / Symbios Logic        | 20       | 0.29%   |
| Silicon Image                    | 18       | 0.26%   |
| SK hynix                         | 15       | 0.22%   |
| Adaptec                          | 12       | 0.18%   |
| Broadcom / LSI                   | 11       | 0.16%   |
| Silicon Integrated Systems [SiS] | 9        | 0.13%   |
| Micron Technology                | 9        | 0.13%   |
| Lite-On Technology               | 9        | 0.13%   |
| Toshiba America Info Systems     | 7        | 0.1%    |
| Seagate Technology               | 7        | 0.1%    |
| Integrated Technology Express    | 6        | 0.09%   |
| ULi Electronics                  | 3        | 0.04%   |
| Shenzhen Longsys Electronics     | 3        | 0.04%   |
| KIOXIA                           | 3        | 0.04%   |
| HighPoint Technologies           | 3        | 0.04%   |
| Unknown                          | 2        | 0.03%   |
| OCZ Technology Group             | 2        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.03%   |
| Union Memory (Shenzhen)          | 1        | 0.01%   |
| Transcend                        | 1        | 0.01%   |
| Solid State Storage Technology   | 1        | 0.01%   |
| Promise Technology               | 1        | 0.01%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.01%   |
| Hewlett-Packard                  | 1        | 0.01%   |
| Artop Electronic                 | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 785      | 8.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 388      | 4.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 368      | 4.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 345      | 3.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 334      | 3.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 299      | 3.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 285      | 3.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 253      | 2.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 246      | 2.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 245      | 2.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 228      | 2.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 214      | 2.34%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 197      | 2.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 194      | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 183      | 2%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 183      | 2%      |
| Intel SATA Controller [RAID mode]                                                       | 178      | 1.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 159      | 1.74%   |
| Nvidia MCP61 SATA Controller                                                            | 155      | 1.69%   |
| Nvidia MCP61 IDE                                                                        | 124      | 1.36%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 120      | 1.31%   |
| AMD FCH SATA Controller D                                                               | 98       | 1.07%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 97       | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 90       | 0.98%   |
| AMD 300 Series Chipset SATA Controller                                                  | 89       | 0.97%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 87       | 0.95%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 77       | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 72       | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 69       | 0.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 66       | 0.72%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 66       | 0.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 62       | 0.68%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 60       | 0.66%   |
| JMicron JMB368 IDE controller                                                           | 59       | 0.64%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 56       | 0.61%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 55       | 0.6%    |
| AMD FCH IDE Controller                                                                  | 55       | 0.6%    |
| Phison E12 NVMe Controller                                                              | 54       | 0.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 51       | 0.56%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 48       | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3883     | 55.71%  |
| IDE  | 1897     | 27.22%  |
| NVMe | 837      | 12.01%  |
| RAID | 299      | 4.29%   |
| SAS  | 27       | 0.39%   |
| SCSI | 27       | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 3423     | 64.87%  |
| AMD          | 1853     | 35.11%  |
| CentaurHauls | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 82       | 1.55%   |
| AMD Ryzen 5 3600 6-Core Processor           | 81       | 1.53%   |
| AMD FX-8350 Eight-Core Processor            | 75       | 1.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 71       | 1.34%   |
| AMD FX-6300 Six-Core Processor              | 62       | 1.17%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 61       | 1.15%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 61       | 1.15%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 60       | 1.13%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 57       | 1.08%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 56       | 1.06%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 51       | 0.96%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 49       | 0.92%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 49       | 0.92%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 48       | 0.91%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 46       | 0.87%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 45       | 0.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 44       | 0.83%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 43       | 0.81%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 40       | 0.75%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 38       | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 36       | 0.68%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 36       | 0.68%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 35       | 0.66%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 34       | 0.64%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 33       | 0.62%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 31       | 0.59%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 31       | 0.59%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 30       | 0.57%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 30       | 0.57%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 29       | 0.55%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 29       | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 28       | 0.53%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 28       | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 26       | 0.49%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 26       | 0.49%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 26       | 0.49%   |
| AMD Athlon II X2 250 Processor              | 26       | 0.49%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 25       | 0.47%   |
| AMD FX-4300 Quad-Core Processor             | 25       | 0.47%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 24       | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 950      | 17.95%  |
| Intel Core i7           | 606      | 11.45%  |
| Intel Core i3           | 394      | 7.45%   |
| AMD Ryzen 5             | 368      | 6.95%   |
| AMD FX                  | 304      | 5.74%   |
| Intel Core 2 Duo        | 249      | 4.71%   |
| Intel Xeon              | 226      | 4.27%   |
| AMD Ryzen 7             | 209      | 3.95%   |
| Intel Core 2 Quad       | 172      | 3.25%   |
| Intel Pentium           | 164      | 3.1%    |
| Intel Celeron           | 156      | 2.95%   |
| Intel Pentium Dual-Core | 136      | 2.57%   |
| AMD Ryzen 3             | 98       | 1.85%   |
| AMD Phenom II X4        | 90       | 1.7%    |
| AMD Athlon 64 X2        | 84       | 1.59%   |
| AMD Athlon II X2        | 79       | 1.49%   |
| Other                   | 74       | 1.4%    |
| AMD A8                  | 67       | 1.27%   |
| AMD Ryzen 9             | 65       | 1.23%   |
| Intel Pentium Dual      | 57       | 1.08%   |
| AMD Athlon II X4        | 56       | 1.06%   |
| Intel Pentium 4         | 51       | 0.96%   |
| Intel Core 2            | 51       | 0.96%   |
| AMD A4                  | 47       | 0.89%   |
| AMD A10                 | 47       | 0.89%   |
| Intel Atom              | 45       | 0.85%   |
| Intel Core i9           | 40       | 0.76%   |
| Intel Pentium D         | 36       | 0.68%   |
| AMD A6                  | 36       | 0.68%   |
| AMD Athlon              | 33       | 0.62%   |
| AMD Phenom II X6        | 32       | 0.6%    |
| AMD Sempron             | 27       | 0.51%   |
| AMD Phenom              | 25       | 0.47%   |
| AMD Athlon II X3        | 21       | 0.4%    |
| Intel Pentium Gold      | 19       | 0.36%   |
| AMD Athlon X4           | 19       | 0.36%   |
| AMD Ryzen 5 PRO         | 16       | 0.3%    |
| AMD Phenom II X2        | 16       | 0.3%    |
| AMD Ryzen Threadripper  | 13       | 0.25%   |
| AMD Athlon 64           | 11       | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2157     | 40.69%  |
| 2       | 1697     | 32.01%  |
| 6       | 623      | 11.75%  |
| 8       | 337      | 6.36%   |
| 1       | 199      | 3.75%   |
| 3       | 125      | 2.36%   |
| 12      | 80       | 1.51%   |
| 16      | 31       | 0.58%   |
| 10      | 30       | 0.57%   |
| Unknown | 9        | 0.17%   |
| 24      | 4        | 0.08%   |
| 18      | 3        | 0.06%   |
| 20      | 2        | 0.04%   |
| 64      | 1        | 0.02%   |
| 32      | 1        | 0.02%   |
| 14      | 1        | 0.02%   |
| 5       | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 5227     | 99.05%  |
| 2      | 50       | 0.95%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2743     | 51.79%  |
| 2       | 2543     | 48.02%  |
| Unknown | 9        | 0.17%   |
| 8       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4900     | 91.74%  |
| Unknown        | 407      | 7.62%   |
| 32-bit         | 34       | 0.64%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 568      | 10.49%  |
| 0x306c3    | 483      | 8.92%   |
| 0x206a7    | 420      | 7.76%   |
| 0x306a9    | 365      | 6.74%   |
| 0x1067a    | 361      | 6.67%   |
| 0x06000852 | 218      | 4.03%   |
| 0x506e3    | 182      | 3.36%   |
| 0x010000c8 | 168      | 3.1%    |
| 0x08701021 | 154      | 2.84%   |
| 0x906e9    | 140      | 2.59%   |
| 0x906ea    | 132      | 2.44%   |
| 0x0800820d | 121      | 2.23%   |
| 0x6fd      | 92       | 1.7%    |
| 0x6fb      | 89       | 1.64%   |
| 0x06001119 | 86       | 1.59%   |
| 0x10676    | 65       | 1.2%    |
| 0x08108109 | 65       | 1.2%    |
| 0x08701013 | 64       | 1.18%   |
| 0x106e5    | 60       | 1.11%   |
| 0xa0655    | 56       | 1.03%   |
| 0x010000db | 56       | 1.03%   |
| 0x0600063e | 53       | 0.98%   |
| 0x20655    | 51       | 0.94%   |
| 0x06003106 | 44       | 0.81%   |
| 0x08001138 | 43       | 0.79%   |
| 0x906ed    | 38       | 0.7%    |
| 0x08001137 | 38       | 0.7%    |
| 0xa0653    | 37       | 0.68%   |
| 0x306f2    | 36       | 0.66%   |
| 0xa0671    | 35       | 0.65%   |
| 0x20652    | 35       | 0.65%   |
| 0x0600611a | 33       | 0.61%   |
| 0x206c2    | 32       | 0.59%   |
| 0x0a50000c | 31       | 0.57%   |
| 0x6f6      | 30       | 0.55%   |
| 0x106a5    | 29       | 0.54%   |
| 0x10677    | 29       | 0.54%   |
| 0x08101016 | 29       | 0.54%   |
| 0x010000dc | 29       | 0.54%   |
| 0x03000027 | 28       | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 562      | 10.63%  |
| Penryn           | 475      | 8.99%   |
| SandyBridge      | 473      | 8.95%   |
| IvyBridge        | 423      | 8%      |
| KabyLake         | 389      | 7.36%   |
| K10              | 359      | 6.79%   |
| Piledriver       | 340      | 6.43%   |
| Core             | 263      | 4.98%   |
| Zen 2            | 261      | 4.94%   |
| Zen+             | 219      | 4.14%   |
| Skylake          | 210      | 3.97%   |
| Zen              | 184      | 3.48%   |
| Zen 3            | 129      | 2.44%   |
| Westmere         | 125      | 2.37%   |
| K8 Hammer        | 122      | 2.31%   |
| NetBurst         | 103      | 1.95%   |
| Nehalem          | 102      | 1.93%   |
| CometLake        | 100      | 1.89%   |
| Bulldozer        | 61       | 1.15%   |
| Steamroller      | 56       | 1.06%   |
| Silvermont       | 47       | 0.89%   |
| Excavator        | 43       | 0.81%   |
| Unknown          | 42       | 0.79%   |
| Bonnell          | 33       | 0.62%   |
| K10 Llano        | 31       | 0.59%   |
| Goldmont plus    | 27       | 0.51%   |
| Bobcat           | 23       | 0.44%   |
| Jaguar           | 18       | 0.34%   |
| Goldmont         | 15       | 0.28%   |
| Alderlake Hybrid | 15       | 0.28%   |
| Broadwell        | 10       | 0.19%   |
| Icelake          | 9        | 0.17%   |
| Puma             | 6        | 0.11%   |
| Tremont          | 4        | 0.08%   |
| K6               | 4        | 0.08%   |
| TigerLake        | 2        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 2165     | 38.82%  |
| Intel                                        | 1706     | 30.59%  |
| AMD                                          | 1658     | 29.73%  |
| VIA Technologies                             | 16       | 0.29%   |
| Matrox Electronics Systems                   | 14       | 0.25%   |
| Silicon Integrated Systems [SiS]             | 7        | 0.13%   |
| ATI Technologies                             | 5        | 0.09%   |
| S3 Graphics                                  | 3        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.04%   |
| ASPEED Technology                            | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 254      | 4.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 245      | 4.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 189      | 3.29%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 174      | 3.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 144      | 2.51%   |
| Nvidia GK208B [GeForce GT 710]                                              | 141      | 2.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 132      | 2.3%    |
| Intel HD Graphics 530                                                       | 106      | 1.85%   |
| Nvidia GT218 [GeForce 210]                                                  | 99       | 1.73%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 91       | 1.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 91       | 1.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 84       | 1.46%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 81       | 1.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 79       | 1.38%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 72       | 1.26%   |
| Intel HD Graphics 630                                                       | 62       | 1.08%   |
| AMD RS780L [Radeon 3000]                                                    | 62       | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 62       | 1.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 58       | 1.01%   |
| Intel Core Processor Integrated Graphics Controller                         | 55       | 0.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 52       | 0.91%   |
| Nvidia GK208B [GeForce GT 730]                                              | 51       | 0.89%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 48       | 0.84%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 47       | 0.82%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 47       | 0.82%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 46       | 0.8%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 45       | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 45       | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 43       | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 41       | 0.71%   |
| Nvidia GF119 [GeForce GT 610]                                               | 40       | 0.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 38       | 0.66%   |
| AMD Cezanne                                                                 | 38       | 0.66%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 37       | 0.65%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 35       | 0.61%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 35       | 0.61%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 33       | 0.58%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 33       | 0.58%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 33       | 0.58%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 33       | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 2049     | 38.44%  |
| 1 x AMD             | 1539     | 28.87%  |
| 1 x Intel           | 1503     | 28.19%  |
| 2 x AMD             | 63       | 1.18%   |
| Intel + Nvidia      | 51       | 0.96%   |
| Intel + AMD         | 27       | 0.51%   |
| AMD + Nvidia        | 27       | 0.51%   |
| 2 x Nvidia          | 26       | 0.49%   |
| 1 x VIA             | 16       | 0.3%    |
| 1 x Matrox          | 14       | 0.26%   |
| 1 x SiS             | 7        | 0.13%   |
| 3 x AMD             | 2        | 0.04%   |
| 1 x S3 Graphics     | 2        | 0.04%   |
| Nvidia + XGI        | 2        | 0.04%   |
| Nvidia + ASPEED     | 1        | 0.02%   |
| Intel + 2 x Nvidia  | 1        | 0.02%   |
| Intel + S3 Graphics | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3538     | 65.76%  |
| Proprietary | 1585     | 29.46%  |
| Unknown     | 257      | 4.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1664     | 30.63%  |
| 1.01-2.0   | 1020     | 18.77%  |
| 0.51-1.0   | 808      | 14.87%  |
| 0.01-0.5   | 784      | 14.43%  |
| 3.01-4.0   | 487      | 8.96%   |
| 7.01-8.0   | 341      | 6.28%   |
| 5.01-6.0   | 189      | 3.48%   |
| 2.01-3.0   | 72       | 1.33%   |
| 8.01-16.0  | 59       | 1.09%   |
| 16.01-24.0 | 7        | 0.13%   |
| 4.01-5.0   | 2        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 926      | 16.97%  |
| Goldstar             | 572      | 10.48%  |
| Dell                 | 496      | 9.09%   |
| Acer                 | 411      | 7.53%   |
| Hewlett-Packard      | 361      | 6.62%   |
| AOC                  | 293      | 5.37%   |
| Ancor Communications | 257      | 4.71%   |
| BenQ                 | 246      | 4.51%   |
| Philips              | 236      | 4.33%   |
| LG Electronics       | 158      | 2.9%    |
| Unknown              | 134      | 2.46%   |
| ViewSonic            | 108      | 1.98%   |
| Iiyama               | 96       | 1.76%   |
| Sony                 | 70       | 1.28%   |
| ASUSTek Computer     | 62       | 1.14%   |
| Eizo                 | 55       | 1.01%   |
| NEC Computers        | 53       | 0.97%   |
| Lenovo               | 48       | 0.88%   |
| Fujitsu Siemens      | 47       | 0.86%   |
| HannStar             | 40       | 0.73%   |
| Vizio                | 36       | 0.66%   |
| Medion               | 31       | 0.57%   |
| Panasonic            | 26       | 0.48%   |
| Toshiba              | 25       | 0.46%   |
| Unknown              | 24       | 0.44%   |
| Sceptre Tech         | 23       | 0.42%   |
| Idek Iiyama          | 20       | 0.37%   |
| Sharp                | 16       | 0.29%   |
| Vestel Elektronik    | 15       | 0.27%   |
| FUS                  | 15       | 0.27%   |
| AUS                  | 15       | 0.27%   |
| Hitachi              | 14       | 0.26%   |
| MSI                  | 13       | 0.24%   |
| Gateway              | 13       | 0.24%   |
| Plain Tree Systems   | 12       | 0.22%   |
| Packard Bell         | 12       | 0.22%   |
| Insignia             | 12       | 0.22%   |
| VIZ                  | 11       | 0.2%    |
| Lenovo Group Limited | 11       | 0.2%    |
| Compal               | 11       | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 29       | 0.5%    |
| Unknown                                                                | 24       | 0.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 21       | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 18       | 0.31%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 17       | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 16       | 0.27%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 15       | 0.26%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                       | 15       | 0.26%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 14       | 0.24%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 14       | 0.24%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 13       | 0.22%   |
| Unknown LCD Monitor SAMSUNG                                            | 11       | 0.19%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                | 11       | 0.19%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch       | 11       | 0.19%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 11       | 0.19%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 10       | 0.17%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch    | 10       | 0.17%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 10       | 0.17%   |
| LG Electronics LCD Monitor LG TV 1920x1080                             | 10       | 0.17%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 10       | 0.17%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch  | 10       | 0.17%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 9        | 0.15%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch    | 9        | 0.15%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                | 9        | 0.15%   |
| Philips LCD Monitor FTV 1920x1080                                      | 9        | 0.15%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 9        | 0.15%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                           | 9        | 0.15%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 8        | 0.14%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 8        | 0.14%   |
| Goldstar MONITOR GSM59C6 1920x1080 509x286mm 23.0-inch                 | 8        | 0.14%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                      | 8        | 0.14%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 8        | 0.14%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                         | 8        | 0.14%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch    | 7        | 0.12%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 7        | 0.12%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch   | 7        | 0.12%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 7        | 0.12%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 7        | 0.12%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 7        | 0.12%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                 | 7        | 0.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2285     | 42.07%  |
| 1280x1024 (SXGA)   | 476      | 8.76%   |
| 1680x1050 (WSXGA+) | 357      | 6.57%   |
| 3840x2160 (4K)     | 334      | 6.15%   |
| 1366x768 (WXGA)    | 286      | 5.27%   |
| 1440x900 (WXGA+)   | 245      | 4.51%   |
| 2560x1440 (QHD)    | 227      | 4.18%   |
| Unknown            | 215      | 3.96%   |
| 1600x900 (HD+)     | 180      | 3.31%   |
| 1920x1200 (WUXGA)  | 165      | 3.04%   |
| 1360x768           | 134      | 2.47%   |
| 3840x1080          | 72       | 1.33%   |
| 2560x1080          | 65       | 1.2%    |
| 1024x768 (XGA)     | 54       | 0.99%   |
| 1600x1200          | 38       | 0.7%    |
| 3440x1440          | 36       | 0.66%   |
| 1920x540           | 29       | 0.53%   |
| 1280x720 (HD)      | 21       | 0.39%   |
| 3200x1080          | 17       | 0.31%   |
| 3600x1080          | 14       | 0.26%   |
| 2560x1600          | 10       | 0.18%   |
| 4480x1440          | 9        | 0.17%   |
| 5760x1080          | 8        | 0.15%   |
| 3840x1200          | 8        | 0.15%   |
| 1280x960           | 8        | 0.15%   |
| 5120x1440          | 7        | 0.13%   |
| 3520x1080          | 7        | 0.13%   |
| 1152x864           | 7        | 0.13%   |
| 3360x1050          | 6        | 0.11%   |
| 3286x1080          | 6        | 0.11%   |
| 5120x1080          | 5        | 0.09%   |
| 3280x1080          | 5        | 0.09%   |
| 1280x768           | 5        | 0.09%   |
| 3840x1600          | 4        | 0.07%   |
| 2960x1050          | 4        | 0.07%   |
| 2560x1024          | 4        | 0.07%   |
| 2288x1287          | 4        | 0.07%   |
| 2048x1152          | 4        | 0.07%   |
| 2944x1080          | 3        | 0.06%   |
| 1280x800 (WXGA)    | 3        | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 991      | 18.41%  |
| 24      | 583      | 10.83%  |
| 23      | 568      | 10.55%  |
| 21      | 529      | 9.83%   |
| 27      | 502      | 9.33%   |
| 19      | 397      | 7.38%   |
| 18      | 284      | 5.28%   |
| 22      | 237      | 4.4%    |
| 17      | 224      | 4.16%   |
| 20      | 215      | 3.99%   |
| 31      | 156      | 2.9%    |
| 15      | 102      | 1.89%   |
| 34      | 78       | 1.45%   |
| 84      | 61       | 1.13%   |
| 32      | 49       | 0.91%   |
| 72      | 47       | 0.87%   |
| 54      | 43       | 0.8%    |
| 40      | 41       | 0.76%   |
| 25      | 33       | 0.61%   |
| 26      | 21       | 0.39%   |
| 16      | 19       | 0.35%   |
| 46      | 17       | 0.32%   |
| 52      | 11       | 0.2%    |
| 39      | 11       | 0.2%    |
| 37      | 11       | 0.2%    |
| 33      | 11       | 0.2%    |
| 65      | 10       | 0.19%   |
| 48      | 9        | 0.17%   |
| 36      | 9        | 0.17%   |
| 28      | 9        | 0.17%   |
| 12      | 9        | 0.17%   |
| 47      | 8        | 0.15%   |
| 29      | 8        | 0.15%   |
| 13      | 8        | 0.15%   |
| 74      | 7        | 0.13%   |
| 60      | 6        | 0.11%   |
| 55      | 6        | 0.11%   |
| 42      | 6        | 0.11%   |
| 49      | 5        | 0.09%   |
| 14      | 5        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1574     | 29.9%   |
| 401-500        | 1391     | 26.42%  |
| Unknown        | 991      | 18.82%  |
| 301-350        | 307      | 5.83%   |
| 351-400        | 268      | 5.09%   |
| 601-700        | 234      | 4.44%   |
| 701-800        | 147      | 2.79%   |
| 1001-1500      | 123      | 2.34%   |
| 1501-2000      | 122      | 2.32%   |
| 801-900        | 69       | 1.31%   |
| 201-300        | 22       | 0.42%   |
| 901-1000       | 15       | 0.28%   |
| More than 2000 | 2        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2824     | 55.34%  |
| Unknown | 918      | 17.99%  |
| 16/10   | 683      | 13.38%  |
| 5/4     | 408      | 8%      |
| 4/3     | 122      | 2.39%   |
| 21/9    | 84       | 1.65%   |
| 3/2     | 27       | 0.53%   |
| 6/5     | 18       | 0.35%   |
| 32/9    | 10       | 0.2%    |
| 1.96    | 4        | 0.08%   |
| 1.00    | 3        | 0.06%   |
| 2.00    | 1        | 0.02%   |
| 11/10   | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1560     | 29.45%  |
| Unknown        | 991      | 18.71%  |
| 151-200        | 777      | 14.67%  |
| 301-350        | 511      | 9.65%   |
| 141-150        | 419      | 7.91%   |
| 351-500        | 310      | 5.85%   |
| 251-300        | 227      | 4.29%   |
| More than 1000 | 210      | 3.96%   |
| 501-1000       | 124      | 2.34%   |
| 101-110        | 88       | 1.66%   |
| 131-140        | 32       | 0.6%    |
| 111-120        | 21       | 0.4%    |
| 71-80          | 10       | 0.19%   |
| 121-130        | 7        | 0.13%   |
| 81-90          | 5        | 0.09%   |
| 91-100         | 5        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2986     | 58.38%  |
| Unknown | 991      | 19.37%  |
| 101-120 | 731      | 14.29%  |
| 1-50    | 230      | 4.5%    |
| 121-160 | 118      | 2.31%   |
| 161-240 | 59       | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4329     | 80.64%  |
| 2     | 720      | 13.41%  |
| 0     | 248      | 4.62%   |
| 3     | 65       | 1.21%   |
| 4     | 6        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 3323     | 44.44%  |
| Intel                                  | 1752     | 23.43%  |
| Qualcomm Atheros                       | 521      | 6.97%   |
| Ralink Technology                      | 257      | 3.44%   |
| Broadcom                               | 227      | 3.04%   |
| Nvidia                                 | 207      | 2.77%   |
| TP-Link                                | 148      | 1.98%   |
| Ralink                                 | 135      | 1.81%   |
| Marvell Technology Group               | 70       | 0.94%   |
| Qualcomm Atheros Communications        | 64       | 0.86%   |
| Broadcom Limited                       | 62       | 0.83%   |
| D-Link System                          | 51       | 0.68%   |
| NetGear                                | 50       | 0.67%   |
| Samsung Electronics                    | 49       | 0.66%   |
| D-Link                                 | 41       | 0.55%   |
| VIA Technologies                       | 40       | 0.53%   |
| MediaTek                               | 39       | 0.52%   |
| ASUSTek Computer                       | 32       | 0.43%   |
| Xiaomi                                 | 30       | 0.4%    |
| Microsoft                              | 23       | 0.31%   |
| Huawei Technologies                    | 23       | 0.31%   |
| Belkin Components                      | 22       | 0.29%   |
| IMC Networks                           | 21       | 0.28%   |
| Linksys                                | 20       | 0.27%   |
| ASIX Electronics                       | 20       | 0.27%   |
| Aquantia                               | 20       | 0.27%   |
| Edimax Technology                      | 18       | 0.24%   |
| Motorola PCS                           | 13       | 0.17%   |
| AVM                                    | 12       | 0.16%   |
| Sundance Technology Inc / IC Plus      | 10       | 0.13%   |
| Sitecom Europe                         | 9        | 0.12%   |
| Qualcomm                               | 7        | 0.09%   |
| ZyDAS                                  | 5        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 5        | 0.07%   |
| Silicon Integrated Systems [SiS]       | 5        | 0.07%   |
| Motorola                               | 5        | 0.07%   |
| Microchip Technology                   | 5        | 0.07%   |
| Gemtek                                 | 5        | 0.07%   |
| DisplayLink                            | 5        | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 5        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2642     | 31.99%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 260      | 3.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 174      | 2.11%   |
| Intel I211 Gigabit Network Connection                             | 172      | 2.08%   |
| Intel Ethernet Connection (2) I219-V                              | 172      | 2.08%   |
| Intel Wi-Fi 6 AX200                                               | 155      | 1.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 137      | 1.66%   |
| Nvidia MCP61 Ethernet                                             | 129      | 1.56%   |
| Ralink MT7601U Wireless Adapter                                   | 113      | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 103      | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 94       | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 93       | 1.13%   |
| Intel 82579V Gigabit Network Connection                           | 82       | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 80       | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 71       | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 70       | 0.85%   |
| Realtek 802.11ac NIC                                              | 69       | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 68       | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 67       | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 58       | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 56       | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                   | 51       | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 50       | 0.61%   |
| Ralink RT5370 Wireless Adapter                                    | 46       | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 45       | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45       | 0.54%   |
| Intel Wireless-AC 9260                                            | 44       | 0.53%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 43       | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 41       | 0.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 38       | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 37       | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 36       | 0.44%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 36       | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 36       | 0.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 34       | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 34       | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 33       | 0.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 32       | 0.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 32       | 0.39%   |
| Intel Wireless 3165                                               | 32       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 612      | 25.26%  |
| Intel                                 | 511      | 21.09%  |
| Ralink Technology                     | 257      | 10.61%  |
| Qualcomm Atheros                      | 254      | 10.48%  |
| TP-Link                               | 148      | 6.11%   |
| Ralink                                | 135      | 5.57%   |
| Broadcom                              | 76       | 3.14%   |
| Qualcomm Atheros Communications       | 64       | 2.64%   |
| NetGear                               | 50       | 2.06%   |
| D-Link                                | 41       | 1.69%   |
| ASUSTek Computer                      | 32       | 1.32%   |
| D-Link System                         | 30       | 1.24%   |
| MediaTek                              | 24       | 0.99%   |
| Microsoft                             | 23       | 0.95%   |
| IMC Networks                          | 21       | 0.87%   |
| Linksys                               | 20       | 0.83%   |
| Belkin Components                     | 20       | 0.83%   |
| Edimax Technology                     | 18       | 0.74%   |
| Broadcom Limited                      | 13       | 0.54%   |
| AVM                                   | 12       | 0.5%    |
| Sitecom Europe                        | 9        | 0.37%   |
| ZyDAS                                 | 5        | 0.21%   |
| Gemtek                                | 5        | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5        | 0.21%   |
| Tenda                                 | 4        | 0.17%   |
| ZyXEL Communications                  | 3        | 0.12%   |
| TRENDnet                              | 3        | 0.12%   |
| Texas Instruments                     | 3        | 0.12%   |
| Marvell Technology Group              | 3        | 0.12%   |
| Accton Technology                     | 3        | 0.12%   |
| Wacom                                 | 2        | 0.08%   |
| Samsung Electronics                   | 2        | 0.08%   |
| Mercucys                              | 2        | 0.08%   |
| Xiaomi                                | 1        | 0.04%   |
| VIA Technologies                      | 1        | 0.04%   |
| Sagem                                 | 1        | 0.04%   |
| PLANEX                                | 1        | 0.04%   |
| Philips (or NXP)                      | 1        | 0.04%   |
| Netopia                               | 1        | 0.04%   |
| Micro Star International              | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 155      | 6.3%    |
| Ralink MT7601U Wireless Adapter                                | 113      | 4.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 71       | 2.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 70       | 2.84%   |
| Realtek 802.11ac NIC                                           | 69       | 2.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 68       | 2.76%   |
| Qualcomm Atheros AR9271 802.11n                                | 51       | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 50       | 2.03%   |
| Ralink RT5370 Wireless Adapter                                 | 46       | 1.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 45       | 1.83%   |
| Intel Wireless-AC 9260                                         | 44       | 1.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 43       | 1.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 38       | 1.54%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 34       | 1.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 32       | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 32       | 1.3%    |
| Intel Wireless 3165                                            | 32       | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 31       | 1.26%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 28       | 1.14%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 28       | 1.14%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 27       | 1.1%    |
| Intel Wireless 7260                                            | 27       | 1.1%    |
| Ralink RT2561/RT61 802.11g PCI                                 | 25       | 1.02%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 24       | 0.98%   |
| Intel Wireless 8260                                            | 23       | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 23       | 0.93%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 22       | 0.89%   |
| Intel Wireless 7265                                            | 22       | 0.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 21       | 0.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 21       | 0.85%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 20       | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 20       | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 19       | 0.77%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 19       | 0.77%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 19       | 0.77%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 18       | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18       | 0.73%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 18       | 0.73%   |
| Microsoft Xbox 360 Wireless Adapter                            | 18       | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 17       | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 3088     | 55.11%  |
| Intel                                  | 1461     | 26.08%  |
| Qualcomm Atheros                       | 284      | 5.07%   |
| Nvidia                                 | 207      | 3.69%   |
| Broadcom                               | 151      | 2.69%   |
| Marvell Technology Group               | 67       | 1.2%    |
| Broadcom Limited                       | 49       | 0.87%   |
| Samsung Electronics                    | 47       | 0.84%   |
| VIA Technologies                       | 38       | 0.68%   |
| Xiaomi                                 | 29       | 0.52%   |
| D-Link System                          | 21       | 0.37%   |
| ASIX Electronics                       | 20       | 0.36%   |
| Aquantia                               | 20       | 0.36%   |
| MediaTek                               | 15       | 0.27%   |
| Huawei Technologies                    | 13       | 0.23%   |
| Sundance Technology Inc / IC Plus      | 10       | 0.18%   |
| Motorola PCS                           | 10       | 0.18%   |
| Qualcomm                               | 6        | 0.11%   |
| Silicon Integrated Systems [SiS]       | 5        | 0.09%   |
| DisplayLink                            | 5        | 0.09%   |
| ZTE WCDMA Technologies MSM             | 4        | 0.07%   |
| LG Electronics                         | 4        | 0.07%   |
| Google                                 | 4        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.05%   |
| OPPO Electronics                       | 3        | 0.05%   |
| Apple                                  | 3        | 0.05%   |
| Spreadtrum Communications              | 2        | 0.04%   |
| OnePlus                                | 2        | 0.04%   |
| Microchip Technology                   | 2        | 0.04%   |
| Mellanox Technologies                  | 2        | 0.04%   |
| JMicron Technology                     | 2        | 0.04%   |
| ICS Advent                             | 2        | 0.04%   |
| HTC (High Tech Computer)               | 2        | 0.04%   |
| ADMtek                                 | 2        | 0.04%   |
| 3Com                                   | 2        | 0.04%   |
| vivo                                   | 1        | 0.02%   |
| ULi Electronics                        | 1        | 0.02%   |
| Trendchip Technologies                 | 1        | 0.02%   |
| Tehuti Networks                        | 1        | 0.02%   |
| T & A Mobile Phones                    | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2642     | 46.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 260      | 4.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 174      | 3.04%   |
| Intel I211 Gigabit Network Connection                             | 172      | 3%      |
| Intel Ethernet Connection (2) I219-V                              | 172      | 3%      |
| Realtek RTL8125 2.5GbE Controller                                 | 137      | 2.39%   |
| Nvidia MCP61 Ethernet                                             | 129      | 2.25%   |
| Intel Ethernet Connection I217-LM                                 | 103      | 1.8%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 94       | 1.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 93       | 1.62%   |
| Intel 82579V Gigabit Network Connection                           | 82       | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 80       | 1.4%    |
| Intel Ethernet Connection I217-V                                  | 67       | 1.17%   |
| Intel Ethernet Connection (2) I218-V                              | 58       | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 56       | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45       | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 41       | 0.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 37       | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 36       | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 36       | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 36       | 0.63%   |
| Intel 82574L Gigabit Network Connection                           | 34       | 0.59%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 33       | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 31       | 0.54%   |
| Intel 82578DM Gigabit Network Connection                          | 31       | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 30       | 0.52%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 28       | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 25       | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 24       | 0.42%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 22       | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 22       | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22       | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 21       | 0.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21       | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 21       | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19       | 0.33%   |
| Nvidia MCP77 Ethernet                                             | 19       | 0.33%   |
| Intel 82562V-2 10/100 Network Connection                          | 18       | 0.31%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 17       | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 16       | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5212     | 69.33%  |
| WiFi     | 2234     | 29.72%  |
| Modem    | 49       | 0.65%   |
| Unknown  | 23       | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4103     | 74.97%  |
| WiFi     | 1367     | 24.98%  |
| Unknown  | 3        | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3775     | 71.16%  |
| 2     | 1339     | 25.24%  |
| 3     | 117      | 2.21%   |
| 0     | 51       | 0.96%   |
| 4     | 14       | 0.26%   |
| 5     | 6        | 0.11%   |
| 7     | 2        | 0.04%   |
| 6     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 4410     | 82.28%  |
| Yes     | 949      | 17.71%  |
| Unknown | 1        | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 457      | 33.31%  |
| Cambridge Silicon Radio         | 457      | 33.31%  |
| Broadcom                        | 102      | 7.43%   |
| Realtek Semiconductor           | 95       | 6.92%   |
| ASUSTek Computer                | 83       | 6.05%   |
| Qualcomm Atheros Communications | 45       | 3.28%   |
| IMC Networks                    | 29       | 2.11%   |
| Apple                           | 15       | 1.09%   |
| Integrated System Solution      | 14       | 1.02%   |
| Lite-On Technology              | 13       | 0.95%   |
| MediaTek                        | 9        | 0.66%   |
| Belkin Components               | 9        | 0.66%   |
| Edimax Technology               | 5        | 0.36%   |
| Dell                            | 5        | 0.36%   |
| Conwise Technology              | 5        | 0.36%   |
| TP-Link                         | 4        | 0.29%   |
| Dynex                           | 4        | 0.29%   |
| Ralink                          | 3        | 0.22%   |
| Logitech                        | 3        | 0.22%   |
| Motorola PCS                    | 2        | 0.15%   |
| Micro Star International        | 2        | 0.15%   |
| Hewlett-Packard                 | 2        | 0.15%   |
| Roper                           | 1        | 0.07%   |
| Primax Electronics              | 1        | 0.07%   |
| Microsoft                       | 1        | 0.07%   |
| Kensington                      | 1        | 0.07%   |
| HTC (High Tech Computer)        | 1        | 0.07%   |
| Fujitsu Siemens Computers       | 1        | 0.07%   |
| Foxconn / Hon Hai               | 1        | 0.07%   |
| D-Link                          | 1        | 0.07%   |
| Cypress Semiconductor           | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 456      | 33.19%  |
| Intel AX200 Bluetooth                                    | 138      | 10.04%  |
| Intel Bluetooth wireless interface                       | 110      | 8.01%   |
| Realtek Bluetooth Radio                                  | 69       | 5.02%   |
| Intel Wireless-AC 3168 Bluetooth                         | 67       | 4.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 60       | 4.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 43       | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 38       | 2.77%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 37       | 2.69%   |
| Intel AX201 Bluetooth                                    | 29       | 2.11%   |
| Intel AX210 Bluetooth                                    | 22       | 1.6%    |
| Realtek  Bluetooth 4.2 Adapter                           | 20       | 1.46%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 17       | 1.24%   |
| IMC Networks Bluetooth Radio                             | 15       | 1.09%   |
| ASUS BCM20702A0                                          | 12       | 0.87%   |
| Qualcomm Atheros  Bluetooth Device                       | 10       | 0.73%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 10       | 0.73%   |
| ASUS ASUS USB-BT500                                      | 10       | 0.73%   |
| MediaTek Wireless_Device                                 | 9        | 0.66%   |
| Lite-On Bluetooth Device                                 | 9        | 0.66%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 9        | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 7        | 0.51%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 7        | 0.51%   |
| ASUS Bluetooth Radio                                     | 7        | 0.51%   |
| Realtek RTL8821A Bluetooth                               | 6        | 0.44%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 6        | 0.44%   |
| IMC Networks Bluetooth Device                            | 6        | 0.44%   |
| Broadcom BCM2045 Bluetooth                               | 6        | 0.44%   |
| ASUS Qualcomm Bluetooth 4.1                              | 6        | 0.44%   |
| Apple Bluetooth USB Host Controller                      | 6        | 0.44%   |
| Conwise CW6622                                           | 5        | 0.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 5        | 0.36%   |
| TP-Link TPuLink UB500 Adapter                            | 4        | 0.29%   |
| Integrated System Solution Bluetooth Device              | 4        | 0.29%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 4        | 0.29%   |
| Broadcom HP Bluethunder                                  | 4        | 0.29%   |
| Broadcom Bluetooth 3.0 Dongle                            | 4        | 0.29%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 4        | 0.29%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 4        | 0.29%   |
| ASUS Bluetooth Adapter                                   | 4        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 3230     | 38.01%  |
| AMD                                             | 2209     | 26%     |
| Nvidia                                          | 1978     | 23.28%  |
| C-Media Electronics                             | 227      | 2.67%   |
| Creative Labs                                   | 137      | 1.61%   |
| Logitech                                        | 87       | 1.02%   |
| VIA Technologies                                | 52       | 0.61%   |
| Texas Instruments                               | 47       | 0.55%   |
| Generalplus Technology                          | 41       | 0.48%   |
| JMTek                                           | 35       | 0.41%   |
| Kingston Technology                             | 31       | 0.36%   |
| Creative Technology                             | 27       | 0.32%   |
| Razer USA                                       | 20       | 0.24%   |
| GN Netcom                                       | 19       | 0.22%   |
| SteelSeries ApS                                 | 15       | 0.18%   |
| Corsair                                         | 15       | 0.18%   |
| Plantronics                                     | 14       | 0.16%   |
| Focusrite-Novation                              | 14       | 0.16%   |
| Tenx Technology                                 | 13       | 0.15%   |
| M-Audio                                         | 11       | 0.13%   |
| Sennheiser Communications                       | 10       | 0.12%   |
| ASUSTek Computer                                | 10       | 0.12%   |
| Silicon Integrated Systems [SiS]                | 9        | 0.11%   |
| Microsoft                                       | 8        | 0.09%   |
| Dell                                            | 8        | 0.09%   |
| Yamaha                                          | 7        | 0.08%   |
| Samson Technologies                             | 7        | 0.08%   |
| Ensoniq                                         | 7        | 0.08%   |
| Blue Microphones                                | 7        | 0.08%   |
| BEHRINGER International                         | 7        | 0.08%   |
| XMOS                                            | 6        | 0.07%   |
| Realtek Semiconductor                           | 6        | 0.07%   |
| Asahi Kasei Microsystems                        | 6        | 0.07%   |
| Sony                                            | 5        | 0.06%   |
| SAVITECH                                        | 5        | 0.06%   |
| Licensed by Sony Computer Entertainment America | 5        | 0.06%   |
| KTMicro                                         | 5        | 0.06%   |
| ATI Technologies                                | 5        | 0.06%   |
| AKAI Professional M.I.                          | 5        | 0.06%   |
| RODE Microphones                                | 4        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 547      | 5.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 539      | 5.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 415      | 4.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 339      | 3.46%   |
| AMD Starship/Matisse HD Audio Controller                                          | 305      | 3.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 291      | 2.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 270      | 2.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 256      | 2.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 233      | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                            | 218      | 2.22%   |
| AMD FCH Azalia Controller                                                         | 217      | 2.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 212      | 2.16%   |
| Intel 200 Series PCH HD Audio                                                     | 205      | 2.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 189      | 1.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 187      | 1.91%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 172      | 1.75%   |
| Nvidia MCP61 High Definition Audio                                                | 150      | 1.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 149      | 1.52%   |
| Nvidia High Definition Audio Controller                                           | 146      | 1.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 138      | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 137      | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                        | 130      | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 120      | 1.22%   |
| Nvidia GP106 High Definition Audio Controller                                     | 107      | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 107      | 1.09%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 106      | 1.08%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 102      | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                                     | 100      | 1.02%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 96       | 0.98%   |
| Nvidia GP104 High Definition Audio Controller                                     | 95       | 0.97%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 91       | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                     | 88       | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 87       | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                                     | 81       | 0.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 75       | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                                | 72       | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 66       | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                                | 65       | 0.66%   |
| Nvidia GM204 High Definition Audio Controller                                     | 61       | 0.62%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 57       | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 411      | 17.5%   |
| Kingston            | 405      | 17.24%  |
| Corsair             | 273      | 11.62%  |
| SK hynix            | 204      | 8.68%   |
| Crucial             | 197      | 8.39%   |
| Samsung Electronics | 195      | 8.3%    |
| G.Skill             | 191      | 8.13%   |
| Micron Technology   | 91       | 3.87%   |
| A-DATA Technology   | 46       | 1.96%   |
| Patriot             | 37       | 1.58%   |
| Nanya Technology    | 37       | 1.58%   |
| Team                | 34       | 1.45%   |
| Ramaxel Technology  | 22       | 0.94%   |
| Elpida              | 17       | 0.72%   |
| GOODRAM             | 15       | 0.64%   |
| AMD                 | 14       | 0.6%    |
| Unknown             | 12       | 0.51%   |
| Transcend           | 9        | 0.38%   |
| Kingmax             | 9        | 0.38%   |
| GeIL                | 8        | 0.34%   |
| Unifosa             | 7        | 0.3%    |
| Smart               | 7        | 0.3%    |
| Unknown (ABCD)      | 6        | 0.26%   |
| Teikon              | 5        | 0.21%   |
| Silicon Power       | 5        | 0.21%   |
| Apacer              | 5        | 0.21%   |
| Wilk Elektronik     | 4        | 0.17%   |
| Sesame              | 4        | 0.17%   |
| PNY                 | 4        | 0.17%   |
| OCZ                 | 4        | 0.17%   |
| Multilaser          | 4        | 0.17%   |
| Kllisre             | 4        | 0.17%   |
| Avant               | 4        | 0.17%   |
| Unknown (0x8551)    | 3        | 0.13%   |
| Ramos Technology    | 3        | 0.13%   |
| Qumo                | 3        | 0.13%   |
| KETECH              | 3        | 0.13%   |
| CSX                 | 3        | 0.13%   |
| Wilk                | 2        | 0.09%   |
| V-Color             | 2        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 28       | 1.09%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 25       | 0.97%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 22       | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 21       | 0.82%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                  | 21       | 0.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 20       | 0.78%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s  | 17       | 0.66%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 17       | 0.66%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 16       | 0.62%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 16       | 0.62%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s             | 15       | 0.58%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 15       | 0.58%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                   | 14       | 0.54%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 14       | 0.54%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 13       | 0.5%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 12       | 0.47%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 12       | 0.47%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 12       | 0.47%   |
| Unknown                                                  | 12       | 0.47%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 11       | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 11       | 0.43%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 11       | 0.43%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s       | 11       | 0.43%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s | 11       | 0.43%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 11       | 0.43%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 11       | 0.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s             | 10       | 0.39%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                   | 10       | 0.39%   |
| Unknown RAM Module 1024MB DIMM SDRAM                     | 10       | 0.39%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s              | 10       | 0.39%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s   | 10       | 0.39%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s      | 10       | 0.39%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 9        | 0.35%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 9        | 0.35%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s      | 9        | 0.35%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 9        | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR2                      | 8        | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s              | 8        | 0.31%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s      | 8        | 0.31%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 8        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 817      | 39.53%  |
| DDR3         | 791      | 38.27%  |
| Unknown      | 168      | 8.13%   |
| DDR2         | 144      | 6.97%   |
| SDRAM        | 104      | 5.03%   |
| DDR          | 31       | 1.5%    |
| LPDDR4       | 9        | 0.44%   |
| DRAM         | 2        | 0.1%    |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1910     | 94.18%  |
| SODIMM       | 109      | 5.37%   |
| FB-DIMM      | 5        | 0.25%   |
| RIMM         | 3        | 0.15%   |
| Row Of Chips | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 778      | 34.81%  |
| 4096  | 612      | 27.38%  |
| 2048  | 403      | 18.03%  |
| 16384 | 247      | 11.05%  |
| 1024  | 106      | 4.74%   |
| 32768 | 65       | 2.91%   |
| 512   | 19       | 0.85%   |
| 1536  | 2        | 0.09%   |
| 256   | 2        | 0.09%   |
| 16    | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 447      | 19.67%  |
| 1333    | 354      | 15.58%  |
| 3200    | 176      | 7.75%   |
| 2400    | 132      | 5.81%   |
| 3600    | 129      | 5.68%   |
| 800     | 115      | 5.06%   |
| 2667    | 107      | 4.71%   |
| 2133    | 105      | 4.62%   |
| 667     | 82       | 3.61%   |
| Unknown | 64       | 2.82%   |
| 1867    | 51       | 2.24%   |
| 3000    | 48       | 2.11%   |
| 1866    | 41       | 1.8%    |
| 2933    | 34       | 1.5%    |
| 3400    | 32       | 1.41%   |
| 1800    | 30       | 1.32%   |
| 3466    | 28       | 1.23%   |
| 2666    | 25       | 1.1%    |
| 1066    | 24       | 1.06%   |
| 3800    | 18       | 0.79%   |
| 3866    | 17       | 0.75%   |
| 3733    | 17       | 0.75%   |
| 400     | 14       | 0.62%   |
| 2800    | 13       | 0.57%   |
| 1067    | 13       | 0.57%   |
| 1334    | 10       | 0.44%   |
| 333     | 9        | 0.4%    |
| 2733    | 8        | 0.35%   |
| 3151    | 7        | 0.31%   |
| 2000    | 7        | 0.31%   |
| 3266    | 6        | 0.26%   |
| 2048    | 6        | 0.26%   |
| 533     | 6        | 0.26%   |
| 49926   | 5        | 0.22%   |
| 3334    | 5        | 0.22%   |
| 3100    | 5        | 0.22%   |
| 3007    | 5        | 0.22%   |
| 2465    | 5        | 0.22%   |
| 1639    | 5        | 0.22%   |
| 2200    | 4        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 143      | 37.34%  |
| Brother Industries       | 86       | 22.45%  |
| Canon                    | 58       | 15.14%  |
| Samsung Electronics      | 31       | 8.09%   |
| Seiko Epson              | 30       | 7.83%   |
| QinHeng Electronics      | 6        | 1.57%   |
| Prolific Technology      | 4        | 1.04%   |
| Dymo-CoStar              | 4        | 1.04%   |
| Panasonic (Matsushita)   | 3        | 0.78%   |
| Xerox                    | 2        | 0.52%   |
| Seiko Instruments        | 2        | 0.52%   |
| Pantum                   | 2        | 0.52%   |
| Kyocera                  | 2        | 0.52%   |
| Dell                     | 2        | 0.52%   |
| Sato                     | 1        | 0.26%   |
| Ricoh                    | 1        | 0.26%   |
| Oki Data                 | 1        | 0.26%   |
| NXP Semiconductors       | 1        | 0.26%   |
| Magic Control Technology | 1        | 0.26%   |
| Fuji Xerox               | 1        | 0.26%   |
| Agere Systems (Lucent)   | 1        | 0.26%   |
| Unknown                  | 1        | 0.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                      | 7        | 1.82%   |
| QinHeng CH340S                                        | 6        | 1.56%   |
| Brother Printer                                       | 6        | 1.56%   |
| Samsung M2070 Series                                  | 5        | 1.3%    |
| Samsung M2020 Series                                  | 5        | 1.3%    |
| HP Officejet 4500 G510n-z                             | 5        | 1.3%    |
| HP LaserJet Professional P1102w                       | 5        | 1.3%    |
| HP DeskJet 2620 All-in-One Printer                    | 5        | 1.3%    |
| Brother HL-L2360D series                              | 5        | 1.3%    |
| Samsung SCX-3400 Series                               | 4        | 1.04%   |
| Prolific PL2305 Parallel Port                         | 4        | 1.04%   |
| HP OfficeJet 5200 series                              | 4        | 1.04%   |
| HP LaserJet P1005                                     | 4        | 1.04%   |
| HP LaserJet 1018                                      | 4        | 1.04%   |
| HP DeskJet F4200 series                               | 4        | 1.04%   |
| Brother DCP-7055 scanner/printer                      | 4        | 1.04%   |
| Seiko Epson L210 Series                               | 3        | 0.78%   |
| Samsung C48x Series Color Laser Multifunction Printer | 3        | 0.78%   |
| Panasonic (Matsushita) KX-MB1520G                     | 3        | 0.78%   |
| HP OfficeJet Pro 8020 series                          | 3        | 0.78%   |
| HP OfficeJet Pro 69                                   | 3        | 0.78%   |
| HP LaserJet Professional P 1102w                      | 3        | 0.78%   |
| HP ENVY 5540 series                                   | 3        | 0.78%   |
| HP ENVY 4520 series                                   | 3        | 0.78%   |
| HP DeskJet 3630 series                                | 3        | 0.78%   |
| HP Deskjet 2540 series                                | 3        | 0.78%   |
| HP DeskJet 2130 series                                | 3        | 0.78%   |
| Canon LiDE 400                                        | 3        | 0.78%   |
| Brother MFC-L8600CDW                                  | 3        | 0.78%   |
| Brother MFC-J497DW                                    | 3        | 0.78%   |
| Brother HL-2270DW Laser Printer                       | 3        | 0.78%   |
| Brother HL-1210W series                               | 3        | 0.78%   |
| Brother HL-1110 series                                | 3        | 0.78%   |
| Seiko Epson Printer                                   | 2        | 0.52%   |
| Seiko Epson L365 Series                               | 2        | 0.52%   |
| Seiko Epson L222 Series                               | 2        | 0.52%   |
| Seiko Epson ET-2710 Series                            | 2        | 0.52%   |
| HP OfficeJet 6950                                     | 2        | 0.52%   |
| HP OfficeJet 4650 series                              | 2        | 0.52%   |
| HP OfficeJet 3830 series                              | 2        | 0.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 63       | 59.43%  |
| Seiko Epson                 | 20       | 18.87%  |
| Hewlett-Packard             | 11       | 10.38%  |
| Mustek Systems              | 4        | 3.77%   |
| Ultima Electronics          | 2        | 1.89%   |
| AGFA-Gevaert NV             | 2        | 1.89%   |
| Acer Peripherals (now BenQ) | 2        | 1.89%   |
| UMAX                        | 1        | 0.94%   |
| Microtek International      | 1        | 0.94%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LIDE 25                                                                | 10       | 9.43%   |
| Canon CanoScan LiDE 110                                                               | 10       | 9.43%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 7        | 6.6%    |
| Canon CanoScan LiDE 120                                                               | 6        | 5.66%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 4        | 3.77%   |
| Canon CanoScan LiDE 700F                                                              | 4        | 3.77%   |
| Canon CanoScan LiDE 220                                                               | 4        | 3.77%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 3        | 2.83%   |
| Canon CanoScan LiDE 90                                                                | 3        | 2.83%   |
| Canon CanoScan LiDE 60                                                                | 3        | 2.83%   |
| Canon CanoScan LiDE 210                                                               | 3        | 2.83%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2        | 1.89%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 2        | 1.89%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2        | 1.89%   |
| Mustek Systems SNAPSCAN e22                                                           | 2        | 1.89%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 2        | 1.89%   |
| HP ScanJet 2400c                                                                      | 2        | 1.89%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 1.89%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 2        | 1.89%   |
| Canon CanoScan LiDE 100                                                               | 2        | 1.89%   |
| Canon CanoScan 9000F Mark II                                                          | 2        | 1.89%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                           | 2        | 1.89%   |
| UMAX Astra 4400/4450                                                                  | 1        | 0.94%   |
| Seiko Epson Stylus Photo RX500/510                                                    | 1        | 0.94%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1        | 0.94%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 0.94%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 0.94%   |
| Seiko Epson GT-F600 [Perfection 4180]                                                 | 1        | 0.94%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 0.94%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 0.94%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1        | 0.94%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1        | 0.94%   |
| Microtek International USB1200 Scanner                                                | 1        | 0.94%   |
| HP ScanJet G3010                                                                      | 1        | 0.94%   |
| HP ScanJet 5200c                                                                      | 1        | 0.94%   |
| HP ScanJet 4070 PhotoSmart                                                            | 1        | 0.94%   |
| HP ScanJet 3800c                                                                      | 1        | 0.94%   |
| HP ScanJet 3670                                                                       | 1        | 0.94%   |
| HP Scanjet 300                                                                        | 1        | 0.94%   |
| HP ScanJet 2200c                                                                      | 1        | 0.94%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 358      | 34.42%  |
| Microdia                               | 97       | 9.33%   |
| Microsoft                              | 73       | 7.02%   |
| Samsung Electronics                    | 56       | 5.38%   |
| Generalplus Technology                 | 33       | 3.17%   |
| Chicony Electronics                    | 33       | 3.17%   |
| Z-Star Microelectronics                | 32       | 3.08%   |
| Sunplus Innovation Technology          | 29       | 2.79%   |
| KYE Systems (Mouse Systems)            | 22       | 2.12%   |
| GEMBIRD                                | 22       | 2.12%   |
| Creative Technology                    | 21       | 2.02%   |
| Realtek Semiconductor                  | 20       | 1.92%   |
| Apple                                  | 19       | 1.83%   |
| Aveo Technology                        | 17       | 1.63%   |
| IMC Networks                           | 15       | 1.44%   |
| ARC International                      | 13       | 1.25%   |
| Arkmicro Technologies                  | 12       | 1.15%   |
| Cubeternet                             | 10       | 0.96%   |
| Genesys Logic                          | 9        | 0.87%   |
| Sonix Technology                       | 8        | 0.77%   |
| MacroSilicon                           | 8        | 0.77%   |
| LG Electronics                         | 8        | 0.77%   |
| Jieli Technology                       | 8        | 0.77%   |
| Alcor Micro                            | 7        | 0.67%   |
| Pixart Imaging                         | 6        | 0.58%   |
| Philips (or NXP)                       | 6        | 0.58%   |
| Novatek Microelectronics               | 6        | 0.58%   |
| Hewlett-Packard                        | 5        | 0.48%   |
| Trust                                  | 4        | 0.38%   |
| Silicon Motion                         | 4        | 0.38%   |
| Huawei Technologies                    | 4        | 0.38%   |
| Guillemot                              | 4        | 0.38%   |
| AVerMedia Technologies                 | 4        | 0.38%   |
| Asuscom Network                        | 4        | 0.38%   |
| Unknown                                | 3        | 0.29%   |
| Syntek                                 | 3        | 0.29%   |
| SJ-180517-N                            | 3        | 0.29%   |
| HD USB Camera                          | 3        | 0.29%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.29%   |
| 2M UVC CAMERA                          | 3        | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 90       | 8.64%   |
| Samsung Galaxy series, misc. (MTP mode)           | 56       | 5.37%   |
| Logitech HD Pro Webcam C920                       | 40       | 3.84%   |
| Microsoft LifeCam HD-3000                         | 32       | 3.07%   |
| Microdia Webcam Vitade AF                         | 27       | 2.59%   |
| Logitech HD Webcam C525                           | 26       | 2.5%    |
| Logitech Webcam C170                              | 24       | 2.3%    |
| Logitech Webcam C310                              | 23       | 2.21%   |
| Generalplus GENERAL WEBCAM                        | 22       | 2.11%   |
| Apple iPhone 5/5C/5S/6/SE                         | 19       | 1.82%   |
| Microdia Camera                                   | 18       | 1.73%   |
| Z-Star Venus USB2.0 Camera                        | 13       | 1.25%   |
| Sunplus Full HD webcam                            | 13       | 1.25%   |
| Microdia USB Live camera                          | 13       | 1.25%   |
| Microdia Sonix USB 2.0 Camera                     | 13       | 1.25%   |
| ARC International Camera                          | 13       | 1.25%   |
| Logitech Webcam C210                              | 12       | 1.15%   |
| Microdia USB 2.0 Camera                           | 11       | 1.06%   |
| Generalplus 808 Camera                            | 11       | 1.06%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 11       | 1.06%   |
| Logitech HD Webcam C615                           | 10       | 0.96%   |
| IMC Networks XHC Camera                           | 10       | 0.96%   |
| Chicony HP High Definition 1MP Webcam             | 10       | 0.96%   |
| Realtek FULL HD 1080P Webcam                      | 9        | 0.86%   |
| GEMBIRD USB2.0 PC CAMERA                          | 9        | 0.86%   |
| Arkmicro USB2.0 PC CAMERA                         | 9        | 0.86%   |
| Microsoft LifeCam Cinema                          | 8        | 0.77%   |
| Logitech Webcam C200                              | 8        | 0.77%   |
| Logitech QuickCam Pro 9000                        | 8        | 0.77%   |
| Logitech HD Webcam C910                           | 8        | 0.77%   |
| Logitech C920 PRO HD Webcam                       | 8        | 0.77%   |
| Jieli USB PHY 2.0                                 | 8        | 0.77%   |
| Sunplus FHD Camera Microphone                     | 7        | 0.67%   |
| Microsoft LifeCam HD-5000                         | 7        | 0.67%   |
| Logitech Webcam C925e                             | 7        | 0.67%   |
| Logitech C922 Pro Stream Webcam                   | 7        | 0.67%   |
| Logitech BRIO Ultra HD Webcam                     | 7        | 0.67%   |
| Creative Live! Cam Chat HD [VF0700]               | 7        | 0.67%   |
| Aveo UVC camera (Bresser microscope)              | 7        | 0.67%   |
| Aveo USB2.0 Camera                                | 7        | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 4        | 44.44%  |
| Upek                       | 1        | 11.11%  |
| Synaptics                  | 1        | 11.11%  |
| STMicroelectronics         | 1        | 11.11%  |
| Shenzhen Goodix Technology | 1        | 11.11%  |
| AuthenTec                  | 1        | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]            | 4        | 44.44%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 11.11%  |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1        | 11.11%  |
| STMicroelectronics Fingerprint Reader                  | 1        | 11.11%  |
| Shenzhen Goodix  Fingerprint Device                    | 1        | 11.11%  |
| AuthenTec AES2550 Fingerprint Sensor                   | 1        | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 8        | 24.24%  |
| OmniKey                           | 4        | 12.12%  |
| SCM Microsystems                  | 3        | 9.09%   |
| Realtek Semiconductor             | 2        | 6.06%   |
| Gemalto (was Gemplus)             | 2        | 6.06%   |
| Chicony Electronics               | 2        | 6.06%   |
| VASCO Data Security International | 1        | 3.03%   |
| Reiner SCT Kartensysteme          | 1        | 3.03%   |
| Precise Biometrics                | 1        | 3.03%   |
| In Focus Systems                  | 1        | 3.03%   |
| Hewlett-Packard                   | 1        | 3.03%   |
| Giesecke & Devrient               | 1        | 3.03%   |
| Fujitsu Siemens Computers         | 1        | 3.03%   |
| BIT4ID                            | 1        | 3.03%   |
| Aladdin R.D.                      | 1        | 3.03%   |
| Aladdin Knowledge Systems         | 1        | 3.03%   |
| Aktiv                             | 1        | 3.03%   |
| Advanced Card Systems             | 1        | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Alcor Micro Watchdata W 1981                                    | 5        | 15.15%  |
| OmniKey CardMan 3021 / 3121                                     | 3        | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                             | 3        | 9.09%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 2        | 6.06%   |
| Realtek Semiconductor Smart Card Reader Interface               | 2        | 6.06%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 2        | 6.06%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 2        | 6.06%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 3.03%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 3.03%   |
| Reiner SCT Kartensysteme tanJack USB                            | 1        | 3.03%   |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader      | 1        | 3.03%   |
| OmniKey CardMan 1021                                            | 1        | 3.03%   |
| In Focus Systems EMV Smartcard Reader                           | 1        | 3.03%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                   | 1        | 3.03%   |
| Giesecke & Devrient StarSign CUT                                | 1        | 3.03%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                   | 1        | 3.03%   |
| BIT4ID miniLector-S                                             | 1        | 3.03%   |
| Aladdin R.D. JaCarta                                            | 1        | 3.03%   |
| Aladdin Knowledge Systems Token JC                              | 1        | 3.03%   |
| Aktiv Rutoken lite                                              | 1        | 3.03%   |
| Advanced Card Systems ACR122U                                   | 1        | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 4455     | 82.58%  |
| 1     | 775      | 14.37%  |
| 2     | 125      | 2.32%   |
| 3     | 26       | 0.48%   |
| 4     | 8        | 0.15%   |
| 5     | 5        | 0.09%   |
| 6     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 360      | 32.64%  |
| Net/wireless             | 294      | 26.65%  |
| Communication controller | 124      | 11.24%  |
| Unassigned class         | 49       | 4.44%   |
| Multimedia controller    | 44       | 3.99%   |
| Sound                    | 40       | 3.63%   |
| Network                  | 30       | 2.72%   |
| Bluetooth                | 25       | 2.27%   |
| Camera                   | 22       | 1.99%   |
| Chipcard                 | 20       | 1.81%   |
| Storage/raid             | 16       | 1.45%   |
| Net/ethernet             | 16       | 1.45%   |
| Card reader              | 15       | 1.36%   |
| Storage/ide              | 13       | 1.18%   |
| Modem                    | 13       | 1.18%   |
| Fingerprint reader       | 8        | 0.73%   |
| Dvb card                 | 7        | 0.63%   |
| Tv card                  | 2        | 0.18%   |
| Firewire controller      | 2        | 0.18%   |
| Unclassified device      | 1        | 0.09%   |
| Storage/nvme             | 1        | 0.09%   |
| Storage/ata              | 1        | 0.09%   |

