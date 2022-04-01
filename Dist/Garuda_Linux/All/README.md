Garuda Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Garuda_Linux/Desktop/README.md) and [notebooks](/Dist/Garuda_Linux/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 340

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | A68HM-PLUS                  | Desktop     | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [21e6b2c7c3](https://linux-hardware.org/?probe=21e6b2c7c3) | Mar 22, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [d4a63f4b81](https://linux-hardware.org/?probe=d4a63f4b81) | Mar 20, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [370e992e57](https://linux-hardware.org/?probe=370e992e57) | Mar 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [4935a5660c](https://linux-hardware.org/?probe=4935a5660c) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b4c8253286](https://linux-hardware.org/?probe=b4c8253286) | Feb 23, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [acb2659ec1](https://linux-hardware.org/?probe=acb2659ec1) | Feb 19, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a88902a823](https://linux-hardware.org/?probe=a88902a823) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [499191c566](https://linux-hardware.org/?probe=499191c566) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | Notebook    | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| HP            | 8767 A                      | Desktop     | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e2b8b640f8](https://linux-hardware.org/?probe=e2b8b640f8) | Feb 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [1b98c3db08](https://linux-hardware.org/?probe=1b98c3db08) | Feb 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [6dc9aa1e88](https://linux-hardware.org/?probe=6dc9aa1e88) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | Notebook    | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | Notebook    | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | Desktop     | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [2227a23892](https://linux-hardware.org/?probe=2227a23892) | Jan 20, 2022 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [6261484b31](https://linux-hardware.org/?probe=6261484b31) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | Desktop     | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | Notebook    | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [37dc48f3f3](https://linux-hardware.org/?probe=37dc48f3f3) | Jan 02, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [f506cf2d37](https://linux-hardware.org/?probe=f506cf2d37) | Jan 02, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | Notebook    | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | Notebook    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [8d397e7af8](https://linux-hardware.org/?probe=8d397e7af8) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| ASRock        | H77M-ITX                    | Desktop     | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e6b9de389b](https://linux-hardware.org/?probe=e6b9de389b) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN715-52              | Notebook    | [2b74aabc3a](https://linux-hardware.org/?probe=2b74aabc3a) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b5b437249c](https://linux-hardware.org/?probe=b5b437249c) | Nov 29, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [dd3bc71908](https://linux-hardware.org/?probe=dd3bc71908) | Nov 26, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | Notebook    | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [0f3490892c](https://linux-hardware.org/?probe=0f3490892c) | Nov 14, 2021 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [5ae2157abe](https://linux-hardware.org/?probe=5ae2157abe) | Nov 04, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [e153488f12](https://linux-hardware.org/?probe=e153488f12) | Oct 28, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| Panasonic     | CF-191HYAX1M                | Notebook    | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [5154b1932f](https://linux-hardware.org/?probe=5154b1932f) | Oct 24, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [ec046ac486](https://linux-hardware.org/?probe=ec046ac486) | Oct 24, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [9b9f21a8eb](https://linux-hardware.org/?probe=9b9f21a8eb) | Oct 19, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| Lenovo        | ThinkPad T510 4384WB4       | Notebook    | [4a54d7fd48](https://linux-hardware.org/?probe=4a54d7fd48) | Oct 16, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [64fd7ae16c](https://linux-hardware.org/?probe=64fd7ae16c) | Oct 11, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [1963eb2e26](https://linux-hardware.org/?probe=1963eb2e26) | Sep 28, 2021 |
| Notebook      | P7xxDM2                     | Notebook    | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
| Acer          | Aspire V3-572P              | Notebook    | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [10b47851d2](https://linux-hardware.org/?probe=10b47851d2) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [91a1652ef2](https://linux-hardware.org/?probe=91a1652ef2) | Sep 18, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [646d26abf7](https://linux-hardware.org/?probe=646d26abf7) | Sep 08, 2021 |
| Razer         | Blade                       | Notebook    | [1ce95784c0](https://linux-hardware.org/?probe=1ce95784c0) | Sep 05, 2021 |
| Razer         | Blade                       | Notebook    | [58a2a48dc4](https://linux-hardware.org/?probe=58a2a48dc4) | Sep 05, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [e4593929ff](https://linux-hardware.org/?probe=e4593929ff) | Sep 05, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware     | 0TYR0X A00                  | Desktop     | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [c18bca5109](https://linux-hardware.org/?probe=c18bca5109) | Aug 16, 2021 |
| Google        | Kindred                     | Notebook    | [ac298188ae](https://linux-hardware.org/?probe=ac298188ae) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [4ec8d56e38](https://linux-hardware.org/?probe=4ec8d56e38) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [c8892394cf](https://linux-hardware.org/?probe=c8892394cf) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| Medion        | H110H4-EM2                  | Desktop     | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| ASRock        | X470 Taichi                 | Desktop     | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| Acer          | IPMBW-BR                    | All in one  | [a2ef77ad47](https://linux-hardware.org/?probe=a2ef77ad47) | Aug 03, 2021 |
| ASUSTek       | G750JZ                      | Notebook    | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d25176b845](https://linux-hardware.org/?probe=d25176b845) | Jul 30, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0340b4c57f](https://linux-hardware.org/?probe=0340b4c57f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [e436ae3019](https://linux-hardware.org/?probe=e436ae3019) | Jul 23, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [49cd19882f](https://linux-hardware.org/?probe=49cd19882f) | Jul 23, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cfaf6bb9ab](https://linux-hardware.org/?probe=cfaf6bb9ab) | Jul 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Notebook      | W54_W550SU2                 | Notebook    | [b026148da5](https://linux-hardware.org/?probe=b026148da5) | Jul 15, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [f72a03865c](https://linux-hardware.org/?probe=f72a03865c) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [c65f4896a2](https://linux-hardware.org/?probe=c65f4896a2) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Lenovo        | LEGION 5 15IMH05 82AU       | Notebook    | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar       | H310MHP                     | Desktop     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cc5fd0194e](https://linux-hardware.org/?probe=cc5fd0194e) | Jun 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [11e99b82d5](https://linux-hardware.org/?probe=11e99b82d5) | Jun 22, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [92ae7459b4](https://linux-hardware.org/?probe=92ae7459b4) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8a7a518013](https://linux-hardware.org/?probe=8a7a518013) | Jun 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a93d77d45b](https://linux-hardware.org/?probe=a93d77d45b) | Jun 06, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| MSI           | GE72VR 6RF                  | Notebook    | [faea47290a](https://linux-hardware.org/?probe=faea47290a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e7fda6091a](https://linux-hardware.org/?probe=e7fda6091a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d2a26e0f30](https://linux-hardware.org/?probe=d2a26e0f30) | May 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Acer          | Spin SP513-54N              | Convertible | [aa8934716b](https://linux-hardware.org/?probe=aa8934716b) | May 13, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP            | 844C                        | Desktop     | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP            | 844C                        | Desktop     | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| Alienware     | 17 R3                       | Notebook    | [f9ee772f9e](https://linux-hardware.org/?probe=f9ee772f9e) | May 05, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d9bf75c99c](https://linux-hardware.org/?probe=d9bf75c99c) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [22931f83cc](https://linux-hardware.org/?probe=22931f83cc) | Apr 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [25808be952](https://linux-hardware.org/?probe=25808be952) | Apr 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3c7f354ce4](https://linux-hardware.org/?probe=3c7f354ce4) | Apr 19, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d97babb331](https://linux-hardware.org/?probe=d97babb331) | Apr 18, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [743ff3a2aa](https://linux-hardware.org/?probe=743ff3a2aa) | Apr 18, 2021 |
| Medion        | P861X                       | Notebook    | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | Notebook    | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [4deb77ef82](https://linux-hardware.org/?probe=4deb77ef82) | Apr 10, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [2012ac3d84](https://linux-hardware.org/?probe=2012ac3d84) | Apr 07, 2021 |
| Dell          | Inspiron 5755               | Notebook    | [ae6589874e](https://linux-hardware.org/?probe=ae6589874e) | Apr 07, 2021 |
| HP            | 2B3B                        | All in one  | [1a5d2c36ec](https://linux-hardware.org/?probe=1a5d2c36ec) | Apr 06, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [9f68dee6f5](https://linux-hardware.org/?probe=9f68dee6f5) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [8cc9da4310](https://linux-hardware.org/?probe=8cc9da4310) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [938494cf89](https://linux-hardware.org/?probe=938494cf89) | Mar 31, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Lenovo        | ThinkPad T470 20HD000RUS    | Notebook    | [751dd3bb74](https://linux-hardware.org/?probe=751dd3bb74) | Mar 19, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1e6cbeb181](https://linux-hardware.org/?probe=1e6cbeb181) | Mar 17, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b4580812c2](https://linux-hardware.org/?probe=b4580812c2) | Mar 15, 2021 |
| HP            | 2AF7                        | Desktop     | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP            | 2AF7                        | Desktop     | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| Dell          | XPS L702X                   | Notebook    | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | XPS L702X                   | Notebook    | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [51244d0897](https://linux-hardware.org/?probe=51244d0897) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | Notebook    | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [9dececac24](https://linux-hardware.org/?probe=9dececac24) | Feb 11, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [23cece38ed](https://linux-hardware.org/?probe=23cece38ed) | Feb 02, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| HP            | 1825                        | Desktop     | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP            | 1825                        | Desktop     | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| Dell          | Latitude E6520              | Notebook    | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | Notebook    | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [c504347399](https://linux-hardware.org/?probe=c504347399) | Jan 23, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [643af77934](https://linux-hardware.org/?probe=643af77934) | Jan 18, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| HP            | Compaq 6735b                | Notebook    | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [86c3c2d1d3](https://linux-hardware.org/?probe=86c3c2d1d3) | Jan 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [ad733c377c](https://linux-hardware.org/?probe=ad733c377c) | Jan 09, 2021 |
| ASUSTek       | CM5671                      | Desktop     | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [d4206bf424](https://linux-hardware.org/?probe=d4206bf424) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1d461bb9db](https://linux-hardware.org/?probe=1d461bb9db) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [ce7f267835](https://linux-hardware.org/?probe=ce7f267835) | Dec 23, 2020 |
| Toshiba       | Satellite C55-A             | Notebook    | [43dbeef737](https://linux-hardware.org/?probe=43dbeef737) | Dec 22, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [b02c7cd17e](https://linux-hardware.org/?probe=b02c7cd17e) | Dec 19, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP            | 8643 SMVB                   | Desktop     | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e63bb99c0a](https://linux-hardware.org/?probe=e63bb99c0a) | Nov 30, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1ff8a24823](https://linux-hardware.org/?probe=1ff8a24823) | Nov 18, 2020 |
| HP            | 18E7                        | Desktop     | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| Dell          | Latitude E6430              | Notebook    | [760e7ca474](https://linux-hardware.org/?probe=760e7ca474) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [428abb1a9b](https://linux-hardware.org/?probe=428abb1a9b) | Oct 31, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | Desktop     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | Board                       | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [e8a88c2b81](https://linux-hardware.org/?probe=e8a88c2b81) | Aug 12, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [7380887fb8](https://linux-hardware.org/?probe=7380887fb8) | Aug 09, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [faac6d06ac](https://linux-hardware.org/?probe=faac6d06ac) | Aug 09, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |
| HP            | 450                         | Notebook    | [edeb9f6780](https://linux-hardware.org/?probe=edeb9f6780) | Apr 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 137       | 63.13%  |
| Garuda Linux         | 75        | 34.56%  |
| Garuda Rolling       | 5         | 2.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Garuda Linux | 214       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.15.2-zen1-1-zen   | 7         | 2.87%   |
| 5.16.4-zen1-1-zen   | 6         | 2.46%   |
| 5.14.14-zen1-1-zen  | 6         | 2.46%   |
| 5.15.7-zen1-1-zen   | 5         | 2.05%   |
| 5.15.13-zen1-1-zen  | 5         | 2.05%   |
| 5.15.12-zen1-1-zen  | 5         | 2.05%   |
| 5.13.9-zen1-1-zen   | 5         | 2.05%   |
| 5.13.13-zen1-1-zen  | 5         | 2.05%   |
| 5.11.16-zen1-1-zen  | 5         | 2.05%   |
| 5.11.11-zen1-1-zen  | 5         | 2.05%   |
| 5.16.2-zen1-1-zen   | 4         | 1.64%   |
| 5.16.16-zen1-1-zen  | 4         | 1.64%   |
| 5.15.6-zen2-1-zen   | 4         | 1.64%   |
| 5.10.4-107-tkg-bmq  | 4         | 1.64%   |
| 5.10.1-103-tkg-bmq  | 4         | 1.64%   |
| 5.9.10-zen1-1-zen   | 3         | 1.23%   |
| 5.9.1-zen2-1-zen    | 3         | 1.23%   |
| 5.16.5-zen1-1-zen   | 3         | 1.23%   |
| 5.16.14-zen1-1-zen  | 3         | 1.23%   |
| 5.16.11-zen1-1-zen  | 3         | 1.23%   |
| 5.15.5-zen1-1-zen   | 3         | 1.23%   |
| 5.15.10-zen1-1-zen  | 3         | 1.23%   |
| 5.14.6-zen1-1-zen   | 3         | 1.23%   |
| 5.14.15-zen1-1-zen  | 3         | 1.23%   |
| 5.10.8-112-tkg-bmq  | 3         | 1.23%   |
| 5.10.2-104-tkg-bmq  | 3         | 1.23%   |
| 5.10.15-120-tkg-bmq | 3         | 1.23%   |
| 5.10.10-115-tkg-bmq | 3         | 1.23%   |
| 5.9.8-zen1-1-zen    | 2         | 0.82%   |
| 5.9.2-zen1-1-zen    | 2         | 0.82%   |
| 5.9.11-zen2-1-zen   | 2         | 0.82%   |
| 5.8.14-zen1-1-zen   | 2         | 0.82%   |
| 5.16.9-zen1-1-zen   | 2         | 0.82%   |
| 5.16.8-zen1-1-zen   | 2         | 0.82%   |
| 5.16.8-arch1-1      | 2         | 0.82%   |
| 5.16.15-zen1-1-zen  | 2         | 0.82%   |
| 5.16.10-zen1-1-zen  | 2         | 0.82%   |
| 5.16.1-zen1-1-zen   | 2         | 0.82%   |
| 5.16.0-zen1-1-zen   | 2         | 0.82%   |
| 5.15.4-zen1-1-zen   | 2         | 0.82%   |
| 5.14.9-zen2-1-zen   | 2         | 0.82%   |
| 5.14.12-zen1-1-zen  | 2         | 0.82%   |
| 5.13.5-zen1-1-zen   | 2         | 0.82%   |
| 5.13.12-zen1-1-zen  | 2         | 0.82%   |
| 5.12.9-zen1-1-zen   | 2         | 0.82%   |
| 5.12.7-zen1-1-zen   | 2         | 0.82%   |
| 5.12.4-zen1-2-zen   | 2         | 0.82%   |
| 5.12.2-153-tkg-bmq  | 2         | 0.82%   |
| 5.12.15-zen1-1-zen  | 2         | 0.82%   |
| 5.12.14-zen1-1-zen  | 2         | 0.82%   |
| 5.12.13-zen1-1-zen  | 2         | 0.82%   |
| 5.12.12-AMD-znver2  | 2         | 0.82%   |
| 5.11.6-zen1-1-zen   | 2         | 0.82%   |
| 5.10.7-111-tkg-bmq  | 2         | 0.82%   |
| 5.9.9-zen1-1-zen    | 1         | 0.41%   |
| 5.9.6-zen1-1-zen    | 1         | 0.41%   |
| 5.9.4-zen1-1-zen    | 1         | 0.41%   |
| 5.9.14-99-tkg-bmq   | 1         | 0.41%   |
| 5.8.5-zen1-1-zen    | 1         | 0.41%   |
| 5.8.10-zen1-1-zen   | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.2  | 7         | 2.87%   |
| 5.16.4  | 6         | 2.46%   |
| 5.15.7  | 6         | 2.46%   |
| 5.14.14 | 6         | 2.46%   |
| 5.11.11 | 6         | 2.46%   |
| 5.10.4  | 6         | 2.46%   |
| 5.16.5  | 5         | 2.05%   |
| 5.15.6  | 5         | 2.05%   |
| 5.15.13 | 5         | 2.05%   |
| 5.15.12 | 5         | 2.05%   |
| 5.13.9  | 5         | 2.05%   |
| 5.13.13 | 5         | 2.05%   |
| 5.11.16 | 5         | 2.05%   |
| 5.16.8  | 4         | 1.64%   |
| 5.16.2  | 4         | 1.64%   |
| 5.16.16 | 4         | 1.64%   |
| 5.15.10 | 4         | 1.64%   |
| 5.12.13 | 4         | 1.64%   |
| 5.10.15 | 4         | 1.64%   |
| 5.10.1  | 4         | 1.64%   |
| 5.9.10  | 3         | 1.23%   |
| 5.9.1   | 3         | 1.23%   |
| 5.16.14 | 3         | 1.23%   |
| 5.16.11 | 3         | 1.23%   |
| 5.16.10 | 3         | 1.23%   |
| 5.16.0  | 3         | 1.23%   |
| 5.15.5  | 3         | 1.23%   |
| 5.14.6  | 3         | 1.23%   |
| 5.14.15 | 3         | 1.23%   |
| 5.14.12 | 3         | 1.23%   |
| 5.12.9  | 3         | 1.23%   |
| 5.12.12 | 3         | 1.23%   |
| 5.11.6  | 3         | 1.23%   |
| 5.10.8  | 3         | 1.23%   |
| 5.10.2  | 3         | 1.23%   |
| 5.10.10 | 3         | 1.23%   |
| 5.9.8   | 2         | 0.82%   |
| 5.9.2   | 2         | 0.82%   |
| 5.9.11  | 2         | 0.82%   |
| 5.8.14  | 2         | 0.82%   |
| 5.16.9  | 2         | 0.82%   |
| 5.16.15 | 2         | 0.82%   |
| 5.16.1  | 2         | 0.82%   |
| 5.15.4  | 2         | 0.82%   |
| 5.15.11 | 2         | 0.82%   |
| 5.14.9  | 2         | 0.82%   |
| 5.14.5  | 2         | 0.82%   |
| 5.14.11 | 2         | 0.82%   |
| 5.13.5  | 2         | 0.82%   |
| 5.13.4  | 2         | 0.82%   |
| 5.13.19 | 2         | 0.82%   |
| 5.13.12 | 2         | 0.82%   |
| 5.12.7  | 2         | 0.82%   |
| 5.12.4  | 2         | 0.82%   |
| 5.12.2  | 2         | 0.82%   |
| 5.12.15 | 2         | 0.82%   |
| 5.12.14 | 2         | 0.82%   |
| 5.11.0  | 2         | 0.82%   |
| 5.10.7  | 2         | 0.82%   |
| 5.10.12 | 2         | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 42        | 18.18%  |
| 5.16    | 41        | 17.75%  |
| 5.10    | 36        | 15.58%  |
| 5.14    | 25        | 10.82%  |
| 5.12    | 23        | 9.96%   |
| 5.11    | 23        | 9.96%   |
| 5.13    | 21        | 9.09%   |
| 5.9     | 13        | 5.63%   |
| 5.8     | 5         | 2.16%   |
| 5.6     | 1         | 0.43%   |
| 5.4     | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 214       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 129       | 59.45%  |
| KDE               | 34        | 15.67%  |
| GNOME             | 30        | 13.82%  |
| XFCE              | 9         | 4.15%   |
| X-Cinnamon        | 3         | 1.38%   |
| sway              | 2         | 0.92%   |
| i3                | 2         | 0.92%   |
| Deepin            | 2         | 0.92%   |
| Yaru:ubuntu:GNOME | 1         | 0.46%   |
| qtile-default     | 1         | 0.46%   |
| MATE              | 1         | 0.46%   |
| LXQt              | 1         | 0.46%   |
| Budgie            | 1         | 0.46%   |
| Unknown           | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 204       | 94.88%  |
| Wayland | 9         | 4.19%   |
| Tty     | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 107       | 49.77%  |
| Unknown | 78        | 36.28%  |
| LightDM | 16        | 7.44%   |
| GDM     | 13        | 6.05%   |
| GREETD  | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 105       | 48.61%  |
| en_GB   | 24        | 11.11%  |
| de_DE   | 16        | 7.41%   |
| en_IN   | 12        | 5.56%   |
| it_IT   | 7         | 3.24%   |
| es_ES   | 5         | 2.31%   |
| ru_RU   | 4         | 1.85%   |
| pt_BR   | 4         | 1.85%   |
| es_MX   | 4         | 1.85%   |
| en_AU   | 4         | 1.85%   |
| nl_NL   | 3         | 1.39%   |
| sv_SE   | 2         | 0.93%   |
| pl_PL   | 2         | 0.93%   |
| fr_FR   | 2         | 0.93%   |
| fr_BE   | 2         | 0.93%   |
| fi_FI   | 2         | 0.93%   |
| es_VE   | 2         | 0.93%   |
| es_CO   | 2         | 0.93%   |
| en_ZA   | 2         | 0.93%   |
| en_CA   | 2         | 0.93%   |
| tr_TR   | 1         | 0.46%   |
| sk_SK   | 1         | 0.46%   |
| nb_NO   | 1         | 0.46%   |
| ko_KR   | 1         | 0.46%   |
| iu_CA   | 1         | 0.46%   |
| es_AR   | 1         | 0.46%   |
| el_GR   | 1         | 0.46%   |
| de_AT   | 1         | 0.46%   |
| da_DK   | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 137       | 63.72%  |
| BIOS | 78        | 36.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 211       | 98.6%   |
| Ext4  | 2         | 0.93%   |
| F2fs  | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 127       | 59.07%  |
| Unknown | 75        | 34.88%  |
| MBR     | 13        | 6.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 192       | 88.48%  |
| Yes       | 25        | 11.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 145       | 67.44%  |
| Yes       | 70        | 32.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 37        | 17.29%  |
| Lenovo              | 34        | 15.89%  |
| Hewlett-Packard     | 28        | 13.08%  |
| Dell                | 22        | 10.28%  |
| MSI                 | 20        | 9.35%   |
| Gigabyte Technology | 15        | 7.01%   |
| Acer                | 14        | 6.54%   |
| ASRock              | 9         | 4.21%   |
| Apple               | 4         | 1.87%   |
| Notebook            | 3         | 1.4%    |
| Medion              | 3         | 1.4%    |
| Toshiba             | 2         | 0.93%   |
| Samsung Electronics | 2         | 0.93%   |
| Razer               | 2         | 0.93%   |
| Pegatron            | 2         | 0.93%   |
| Fujitsu             | 2         | 0.93%   |
| Alienware           | 2         | 0.93%   |
| Unknown             | 2         | 0.93%   |
| Sony                | 1         | 0.47%   |
| PC Specialist       | 1         | 0.47%   |
| Panasonic           | 1         | 0.47%   |
| OEM                 | 1         | 0.47%   |
| HUAWEI              | 1         | 0.47%   |
| HONOR               | 1         | 0.47%   |
| GPU Company         | 1         | 0.47%   |
| Google              | 1         | 0.47%   |
| Fujitsu Siemens     | 1         | 0.47%   |
| Chuwi               | 1         | 0.47%   |
| Biostar             | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 1.87%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 3         | 1.4%    |
| ASUS TUF GAMING X570-PLUS                  | 3         | 1.4%    |
| MSI MS-7C91                                | 2         | 0.93%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 0.93%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.93%   |
| Gigabyte AB350-Gaming 3                    | 2         | 0.93%   |
| Dell Inspiron 3668                         | 2         | 0.93%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.93%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.93%   |
| Acer Nitro AN515-44                        | 2         | 0.93%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.47%   |
| Toshiba Satellite C55-A                    | 1         | 0.47%   |
| Sony VPCSB1C5E                             | 1         | 0.47%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.47%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.47%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.47%   |
| Razer Blade                                | 1         | 0.47%   |
| Pegatron p7-1030                           | 1         | 0.47%   |
| Pegatron h9-1301es                         | 1         | 0.47%   |
| PC Specialist GK5NPFO                      | 1         | 0.47%   |
| Panasonic CF-191HYAX1M                     | 1         | 0.47%   |
| Notebook W54_W550SU2                       | 1         | 0.47%   |
| Notebook P7xxDM2(-G)                       | 1         | 0.47%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.47%   |
| MSI MS-7C90                                | 1         | 0.47%   |
| MSI MS-7C83                                | 1         | 0.47%   |
| MSI MS-7C52                                | 1         | 0.47%   |
| MSI MS-7C09                                | 1         | 0.47%   |
| MSI MS-7B98                                | 1         | 0.47%   |
| MSI MS-7B09                                | 1         | 0.47%   |
| MSI MS-7A78                                | 1         | 0.47%   |
| MSI MS-7A39                                | 1         | 0.47%   |
| MSI MS-7A32                                | 1         | 0.47%   |
| MSI MS-7818                                | 1         | 0.47%   |
| MSI MS-7816                                | 1         | 0.47%   |
| MSI MS-7758                                | 1         | 0.47%   |
| MSI GS76 Stealth 11UG                      | 1         | 0.47%   |
| MSI GP75 Leopard 9SD                       | 1         | 0.47%   |
| MSI GF63 Thin 9SC                          | 1         | 0.47%   |
| MSI GE72VR 6RF                             | 1         | 0.47%   |
| MSI GE63 Raider RGB 8RE                    | 1         | 0.47%   |
| MSI A320M-HDV R4.0                         | 1         | 0.47%   |
| Medion P861X                               | 1         | 0.47%   |
| Medion E7419 MD60025                       | 1         | 0.47%   |
| Medion Akoya P5238 F/C395                  | 1         | 0.47%   |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 0.47%   |
| Lenovo ThinkStation S20 4105O1U            | 1         | 0.47%   |
| Lenovo ThinkPad T530 24296KG               | 1         | 0.47%   |
| Lenovo ThinkPad T510 4384WB4               | 1         | 0.47%   |
| Lenovo ThinkPad T470s 20HGS0B900           | 1         | 0.47%   |
| Lenovo ThinkPad T470 20HD000RUS            | 1         | 0.47%   |
| Lenovo ThinkPad T440p 20AWS58F00           | 1         | 0.47%   |
| Lenovo ThinkPad T440p 20AWS4RC00           | 1         | 0.47%   |
| Lenovo ThinkPad T14 Gen 1 20UDS00N00       | 1         | 0.47%   |
| Lenovo ThinkPad P1 20MDS00P00              | 1         | 0.47%   |
| Lenovo ThinkCentre M93p 10A90048US         | 1         | 0.47%   |
| Lenovo ThinkCentre M93p 10A90016US         | 1         | 0.47%   |
| Lenovo ThinkCentre M91p 7033CG1            | 1         | 0.47%   |
| Lenovo ThinkBook 14-IIL 20SL               | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 11        | 5.14%   |
| Lenovo ThinkPad        | 10        | 4.67%   |
| Lenovo IdeaPad         | 10        | 4.67%   |
| HP Pavilion            | 9         | 4.21%   |
| ASUS ROG               | 8         | 3.74%   |
| Acer Aspire            | 7         | 3.27%   |
| ASUS PRIME             | 6         | 2.8%    |
| Lenovo Legion          | 5         | 2.34%   |
| Dell Latitude          | 5         | 2.34%   |
| ASUS TUF               | 5         | 2.34%   |
| Dell XPS               | 4         | 1.87%   |
| Acer Nitro             | 4         | 1.87%   |
| Unknown                | 4         | 1.87%   |
| Lenovo ThinkCentre     | 3         | 1.4%    |
| HP OMEN                | 3         | 1.4%    |
| HP Laptop              | 3         | 1.4%    |
| Toshiba Satellite      | 2         | 0.93%   |
| Razer Blade            | 2         | 0.93%   |
| MSI MS-7C91            | 2         | 0.93%   |
| HP EliteBook           | 2         | 0.93%   |
| Gigabyte X570          | 2         | 0.93%   |
| Gigabyte B450          | 2         | 0.93%   |
| Gigabyte AB350-Gaming  | 2         | 0.93%   |
| ASUS VivoBook          | 2         | 0.93%   |
| ASUS ASUS              | 2         | 0.93%   |
| ASRock X470            | 2         | 0.93%   |
| Sony VPCSB1C5E         | 1         | 0.47%   |
| Samsung 550XCJ         | 1         | 0.47%   |
| Samsung 300V3A         | 1         | 0.47%   |
| Pegatron p7-1030       | 1         | 0.47%   |
| Pegatron h9-1301es     | 1         | 0.47%   |
| PC Specialist GK5NPFO  | 1         | 0.47%   |
| Panasonic CF-191HYAX1M | 1         | 0.47%   |
| Notebook W54           | 1         | 0.47%   |
| Notebook P7xxDM2(-G)   | 1         | 0.47%   |
| Notebook N85           | 1         | 0.47%   |
| MSI MS-7C90            | 1         | 0.47%   |
| MSI MS-7C83            | 1         | 0.47%   |
| MSI MS-7C52            | 1         | 0.47%   |
| MSI MS-7C09            | 1         | 0.47%   |
| MSI MS-7B98            | 1         | 0.47%   |
| MSI MS-7B09            | 1         | 0.47%   |
| MSI MS-7A78            | 1         | 0.47%   |
| MSI MS-7A39            | 1         | 0.47%   |
| MSI MS-7A32            | 1         | 0.47%   |
| MSI MS-7818            | 1         | 0.47%   |
| MSI MS-7816            | 1         | 0.47%   |
| MSI MS-7758            | 1         | 0.47%   |
| MSI GS76               | 1         | 0.47%   |
| MSI GP75               | 1         | 0.47%   |
| MSI GF63               | 1         | 0.47%   |
| MSI GE72VR             | 1         | 0.47%   |
| MSI GE63               | 1         | 0.47%   |
| MSI A320M-HDV          | 1         | 0.47%   |
| Medion P861X           | 1         | 0.47%   |
| Medion E7419           | 1         | 0.47%   |
| Medion Akoya           | 1         | 0.47%   |
| Lenovo Yoga            | 1         | 0.47%   |
| Lenovo ThinkStation    | 1         | 0.47%   |
| Lenovo ThinkBook       | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 38        | 17.76%  |
| 2019 | 27        | 12.62%  |
| 2018 | 24        | 11.21%  |
| 2021 | 23        | 10.75%  |
| 2017 | 22        | 10.28%  |
| 2013 | 15        | 7.01%   |
| 2016 | 14        | 6.54%   |
| 2012 | 13        | 6.07%   |
| 2014 | 12        | 5.61%   |
| 2011 | 9         | 4.21%   |
| 2010 | 7         | 3.27%   |
| 2015 | 4         | 1.87%   |
| 2009 | 3         | 1.4%    |
| 2007 | 2         | 0.93%   |
| 2008 | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 117       | 54.67%  |
| Desktop     | 88        | 41.12%  |
| Convertible | 4         | 1.87%   |
| All in one  | 4         | 1.87%   |
| Mini pc     | 1         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 214       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 213       | 99.53%  |
| Yes  | 1         | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 58        | 26.98%  |
| 4.01-8.0    | 49        | 22.79%  |
| 8.01-16.0   | 48        | 22.33%  |
| 32.01-64.0  | 33        | 15.35%  |
| 3.01-4.0    | 13        | 6.05%   |
| 24.01-32.0  | 9         | 4.19%   |
| 64.01-256.0 | 4         | 1.86%   |
| 2.01-3.0    | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 81        | 35.53%  |
| 3.01-4.0   | 55        | 24.12%  |
| 2.01-3.0   | 48        | 21.05%  |
| 8.01-16.0  | 27        | 11.84%  |
| 1.01-2.0   | 13        | 5.7%    |
| 16.01-24.0 | 3         | 1.32%   |
| 0.51-1.0   | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 41.36%  |
| 2      | 67        | 30.45%  |
| 3      | 31        | 14.09%  |
| 4      | 17        | 7.73%   |
| 5      | 8         | 3.64%   |
| 9      | 3         | 1.36%   |
| 6      | 3         | 1.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 159       | 72.94%  |
| Yes       | 59        | 27.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 85.51%  |
| No        | 31        | 14.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 80.18%  |
| No        | 43        | 19.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 71.3%   |
| No        | 62        | 28.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 67        | 31.16%  |
| Germany      | 22        | 10.23%  |
| UK           | 15        | 6.98%   |
| India        | 12        | 5.58%   |
| Italy        | 11        | 5.12%   |
| Spain        | 5         | 2.33%   |
| Russia       | 5         | 2.33%   |
| Romania      | 5         | 2.33%   |
| Netherlands  | 5         | 2.33%   |
| Mexico       | 5         | 2.33%   |
| Canada       | 5         | 2.33%   |
| Brazil       | 5         | 2.33%   |
| Sweden       | 4         | 1.86%   |
| Poland       | 4         | 1.86%   |
| France       | 4         | 1.86%   |
| Australia    | 4         | 1.86%   |
| Finland      | 3         | 1.4%    |
| Belgium      | 3         | 1.4%    |
| Venezuela    | 2         | 0.93%   |
| South Africa | 2         | 0.93%   |
| Puerto Rico  | 2         | 0.93%   |
| Colombia     | 2         | 0.93%   |
| Turkey       | 1         | 0.47%   |
| Switzerland  | 1         | 0.47%   |
| South Korea  | 1         | 0.47%   |
| Slovakia     | 1         | 0.47%   |
| Singapore    | 1         | 0.47%   |
| Serbia       | 1         | 0.47%   |
| Philippines  | 1         | 0.47%   |
| Norway       | 1         | 0.47%   |
| Luxembourg   | 1         | 0.47%   |
| Lithuania    | 1         | 0.47%   |
| Latvia       | 1         | 0.47%   |
| Kuwait       | 1         | 0.47%   |
| Kenya        | 1         | 0.47%   |
| Iceland      | 1         | 0.47%   |
| Hungary      | 1         | 0.47%   |
| Greece       | 1         | 0.47%   |
| Denmark      | 1         | 0.47%   |
| Czechia      | 1         | 0.47%   |
| China        | 1         | 0.47%   |
| Chile        | 1         | 0.47%   |
| Bahrain      | 1         | 0.47%   |
| Austria      | 1         | 0.47%   |
| Argentina    | 1         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| London                   | 4         | 1.79%   |
| Berlin                   | 3         | 1.35%   |
| Sydney                   | 2         | 0.9%    |
| San Jose                 | 2         | 0.9%    |
| Puebla City              | 2         | 0.9%    |
| Portland                 | 2         | 0.9%    |
| Oklahoma City            | 2         | 0.9%    |
| Milan                    | 2         | 0.9%    |
| Kingsport                | 2         | 0.9%    |
| Helsinki                 | 2         | 0.9%    |
| Groningen                | 2         | 0.9%    |
| Chicago                  | 2         | 0.9%    |
| Cape Town                | 2         | 0.9%    |
| Calenzano                | 2         | 0.9%    |
| Bryansk                  | 2         | 0.9%    |
| Winston-Salem            | 1         | 0.45%   |
| Windermere               | 1         | 0.45%   |
| West Des Moines          | 1         | 0.45%   |
| Welwyn Garden City       | 1         | 0.45%   |
| Weiterstadt              | 1         | 0.45%   |
| Warsaw                   | 1         | 0.45%   |
| Vufflens-la-Ville        | 1         | 0.45%   |
| Volzhskiy                | 1         | 0.45%   |
| Volgograd                | 1         | 0.45%   |
| Viganello                | 1         | 0.45%   |
| Vienna                   | 1         | 0.45%   |
| Valenzano                | 1         | 0.45%   |
| Valence                  | 1         | 0.45%   |
| Turku                    | 1         | 0.45%   |
| Turin                    | 1         | 0.45%   |
| Tucson                   | 1         | 0.45%   |
| Toronto                  | 1         | 0.45%   |
| Toms River               | 1         | 0.45%   |
| TimiИ™oara            | 1         | 0.45%   |
| TimiÈ™oara            | 1         | 0.45%   |
| Tekoa                    | 1         | 0.45%   |
| Tampa                    | 1         | 0.45%   |
| Stuttgart                | 1         | 0.45%   |
| Stockton-on-Tees         | 1         | 0.45%   |
| Stockholm                | 1         | 0.45%   |
| Stavropol                | 1         | 0.45%   |
| St Louis                 | 1         | 0.45%   |
| Spring Hill              | 1         | 0.45%   |
| Spitalfields             | 1         | 0.45%   |
| Southampton              | 1         | 0.45%   |
| Singapore                | 1         | 0.45%   |
| Sighetu MarmaÅ£iei     | 1         | 0.45%   |
| Shreveport               | 1         | 0.45%   |
| Seattle                  | 1         | 0.45%   |
| Satu Mare                | 1         | 0.45%   |
| Sarasota                 | 1         | 0.45%   |
| Santa Cruz de Tenerife   | 1         | 0.45%   |
| Santa Clara              | 1         | 0.45%   |
| San Juan                 | 1         | 0.45%   |
| San Francisco            | 1         | 0.45%   |
| Salto da Divisa          | 1         | 0.45%   |
| Saint-Maur-des-FossÃ©s | 1         | 0.45%   |
| Riga                     | 1         | 0.45%   |
| Reno                     | 1         | 0.45%   |
| Regina                   | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 69        | 125    | 17.42%  |
| Seagate                   | 61        | 85     | 15.4%   |
| WDC                       | 57        | 71     | 14.39%  |
| Toshiba                   | 25        | 29     | 6.31%   |
| Sandisk                   | 18        | 25     | 4.55%   |
| Crucial                   | 18        | 26     | 4.55%   |
| Kingston                  | 17        | 23     | 4.29%   |
| SK Hynix                  | 14        | 15     | 3.54%   |
| Unknown                   | 10        | 10     | 2.53%   |
| HGST                      | 10        | 10     | 2.53%   |
| Phison                    | 9         | 10     | 2.27%   |
| Intel                     | 8         | 10     | 2.02%   |
| Hitachi                   | 7         | 7      | 1.77%   |
| SPCC                      | 5         | 5      | 1.26%   |
| Micron Technology         | 5         | 5      | 1.26%   |
| A-DATA Technology         | 5         | 8      | 1.26%   |
| Silicon Motion            | 4         | 4      | 1.01%   |
| PNY                       | 4         | 4      | 1.01%   |
| Corsair                   | 4         | 7      | 1.01%   |
| China                     | 4         | 6      | 1.01%   |
| XPG                       | 3         | 4      | 0.76%   |
| KIOXIA                    | 3         | 4      | 0.76%   |
| Union Memory (Shenzhen)   | 2         | 2      | 0.51%   |
| Transcend                 | 2         | 2      | 0.51%   |
| Mushkin                   | 2         | 2      | 0.51%   |
| Micron/Crucial Technology | 2         | 3      | 0.51%   |
| LITEONIT                  | 2         | 2      | 0.51%   |
| WDC WDS                   | 1         | 1      | 0.25%   |
| WD MediaMax               | 1         | 1      | 0.25%   |
| VisionTek                 | 1         | 2      | 0.25%   |
| USB30                     | 1         | 2      | 0.25%   |
| UMIS                      | 1         | 1      | 0.25%   |
| TO Exter                  | 1         | 1      | 0.25%   |
| SSSTC                     | 1         | 1      | 0.25%   |
| ShanDianZhe               | 1         | 1      | 0.25%   |
| SABRENT                   | 1         | 2      | 0.25%   |
| QUMO                      | 1         | 1      | 0.25%   |
| PNY CS90                  | 1         | 1      | 0.25%   |
| Phison Electronics        | 1         | 1      | 0.25%   |
| OCZ                       | 1         | 1      | 0.25%   |
| Netac                     | 1         | 1      | 0.25%   |
| LITEON                    | 1         | 1      | 0.25%   |
| Lenovo                    | 1         | 1      | 0.25%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.25%   |
| Intenso                   | 1         | 2      | 0.25%   |
| Inateck                   | 1         | 1      | 0.25%   |
| HS-SSD-E100               | 1         | 1      | 0.25%   |
| FORESEE                   | 1         | 1      | 0.25%   |
| EMTEC                     | 1         | 1      | 0.25%   |
| ASMT                      | 1         | 1      | 0.25%   |
| ASMedia                   | 1         | 2      | 0.25%   |
| Apple                     | 1         | 1      | 0.25%   |
| Unknown                   | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB           | 8         | 1.81%   |
| Samsung SSD 970 EVO Plus 500GB       | 6         | 1.36%   |
| Seagate ST1000LM049-2GH172 1TB       | 5         | 1.13%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 1.13%   |
| Samsung SSD 860 EVO 500GB            | 5         | 1.13%   |
| Samsung SSD 850 EVO 250GB            | 5         | 1.13%   |
| Crucial CT1000MX500SSD1 1TB          | 5         | 1.13%   |
| Seagate ST2000DM008-2FR102 2TB       | 4         | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 0.9%    |
| Samsung SSD 860 EVO 1TB              | 4         | 0.9%    |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.9%    |
| Toshiba MQ01ABD100 1TB               | 3         | 0.68%   |
| Toshiba DT01ACA100 1TB               | 3         | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.68%   |
| Seagate Portable 5TB                 | 3         | 0.68%   |
| SanDisk SSD PLUS 1000GB              | 3         | 0.68%   |
| Sandisk NVMe SSD Drive 500GB         | 3         | 0.68%   |
| Sandisk NVMe SSD Drive 1TB           | 3         | 0.68%   |
| Samsung SSD 970 EVO 250GB            | 3         | 0.68%   |
| Samsung SSD 870 EVO 500GB            | 3         | 0.68%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 0.68%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.68%   |
| XPG NVMe SSD Drive 512GB             | 2         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.45%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 0.45%   |
| WDC WD10EZEX-60WN4A0 1TB             | 2         | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.45%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 2         | 0.45%   |
| Unknown MMC Card  16GB               | 2         | 0.45%   |
| Toshiba HDWD110 1TB                  | 2         | 0.45%   |
| SPCC Solid State Disk 512GB          | 2         | 0.45%   |
| SK Hynix SC311 SATA 256GB SSD        | 2         | 0.45%   |
| SK Hynix NVMe SSD Drive 512GB        | 2         | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB       | 2         | 0.45%   |
| Seagate ST3320820AS 320GB            | 2         | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.45%   |
| Seagate ST2000DL003-9VT166 2TB       | 2         | 0.45%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.45%   |
| Seagate Expansion Desk 4TB           | 2         | 0.45%   |
| Seagate Expansion 320GB              | 2         | 0.45%   |
| Seagate Backup+ Hub BK 10TB          | 2         | 0.45%   |
| Samsung SSD 980 PRO 500GB            | 2         | 0.45%   |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 0.45%   |
| Samsung SSD 870 QVO 1TB              | 2         | 0.45%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.45%   |
| Samsung NVMe SSD Drive 256GB         | 2         | 0.45%   |
| Samsung NVMe SSD Drive 250GB         | 2         | 0.45%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD | 2         | 0.45%   |
| PNY ELITE PSSD 960GB                 | 2         | 0.45%   |
| Phison NVMe SSD Drive 2TB            | 2         | 0.45%   |
| Phison NVMe SSD Drive 256GB          | 2         | 0.45%   |
| Micron/Crucial NVMe SSD Drive 1TB    | 2         | 0.45%   |
| KIOXIA NVMe SSD Drive 512GB          | 2         | 0.45%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.45%   |
| Kingston SHSS37A240G 240GB SSD       | 2         | 0.45%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.45%   |
| Intel SSDPEKNW010T8 1TB              | 2         | 0.45%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 80     | 41.43%  |
| WDC                 | 36        | 47     | 25.71%  |
| Toshiba             | 18        | 21     | 12.86%  |
| HGST                | 10        | 10     | 7.14%   |
| Hitachi             | 7         | 7      | 5%      |
| Samsung Electronics | 4         | 4      | 2.86%   |
| Unknown             | 1         | 1      | 0.71%   |
| SABRENT             | 1         | 2      | 0.71%   |
| Intenso             | 1         | 2      | 0.71%   |
| Inateck             | 1         | 1      | 0.71%   |
| ASMT                | 1         | 1      | 0.71%   |
| ASMedia             | 1         | 2      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 49     | 27.42%  |
| Kingston            | 14        | 20     | 11.29%  |
| Crucial             | 14        | 20     | 11.29%  |
| SanDisk             | 10        | 16     | 8.06%   |
| WDC                 | 9         | 10     | 7.26%   |
| A-DATA Technology   | 5         | 8      | 4.03%   |
| SPCC                | 4         | 4      | 3.23%   |
| SK Hynix            | 4         | 4      | 3.23%   |
| China               | 4         | 6      | 3.23%   |
| PNY                 | 3         | 3      | 2.42%   |
| Transcend           | 2         | 2      | 1.61%   |
| Toshiba             | 2         | 3      | 1.61%   |
| Mushkin             | 2         | 2      | 1.61%   |
| LITEONIT            | 2         | 2      | 1.61%   |
| WDC WDS             | 1         | 1      | 0.81%   |
| VisionTek           | 1         | 2      | 0.81%   |
| USB30               | 1         | 2      | 0.81%   |
| Unknown             | 1         | 1      | 0.81%   |
| TO Exter            | 1         | 1      | 0.81%   |
| QUMO                | 1         | 1      | 0.81%   |
| PNY CS90            | 1         | 1      | 0.81%   |
| OCZ                 | 1         | 1      | 0.81%   |
| Netac               | 1         | 1      | 0.81%   |
| Micron Technology   | 1         | 1      | 0.81%   |
| LITEON              | 1         | 1      | 0.81%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.81%   |
| FORESEE             | 1         | 1      | 0.81%   |
| EMTEC               | 1         | 1      | 0.81%   |
| Corsair             | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 110       | 179    | 32.74%  |
| NVMe    | 105       | 171    | 31.25%  |
| SSD     | 102       | 166    | 30.36%  |
| Unknown | 11        | 11     | 3.27%   |
| MMC     | 8         | 8      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 156       | 311    | 52.7%   |
| NVMe | 105       | 171    | 35.47%  |
| SAS  | 27        | 45     | 9.12%   |
| MMC  | 8         | 8      | 2.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 103       | 160    | 42.74%  |
| 0.51-1.0   | 88        | 114    | 36.51%  |
| 1.01-2.0   | 29        | 43     | 12.03%  |
| 3.01-4.0   | 8         | 9      | 3.32%   |
| 2.01-3.0   | 7         | 12     | 2.9%    |
| 4.01-10.0  | 5         | 6      | 2.07%   |
| 10.01-20.0 | 1         | 1      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 83        | 38.25%  |
| 1001-2000      | 46        | 21.2%   |
| 501-1000       | 31        | 14.29%  |
| 2001-3000      | 29        | 13.36%  |
| 251-500        | 13        | 5.99%   |
| Unknown        | 10        | 4.61%   |
| 101-250        | 3         | 1.38%   |
| 1-20           | 2         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 53        | 23.45%  |
| 251-500        | 43        | 19.03%  |
| 1001-2000      | 34        | 15.04%  |
| 501-1000       | 30        | 13.27%  |
| 51-100         | 27        | 11.95%  |
| 2001-3000      | 12        | 5.31%   |
| More than 3000 | 11        | 4.87%   |
| Unknown        | 10        | 4.42%   |
| 21-50          | 3         | 1.33%   |
| 1-20           | 3         | 1.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60A0RT0 500GB          | 1         | 1      | 4.35%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 4.35%   |
| WDC WD30EZRX-00DC0B0 3TB              | 1         | 1      | 4.35%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 4.35%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 4.35%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 4.35%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 4.35%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 4.35%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 980 1TB       | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 7      | 4.35%   |
| OCZ TRION100 480GB SSD                | 1         | 1      | 4.35%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 4.35%   |
| Kingston SH103S3240G 240GB SSD        | 1         | 1      | 4.35%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 4.35%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 4.35%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 4.35%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 4.35%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 4.35%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 4.35%   |
| Crucial CT960M500SSD1 960GB           | 1         | 1      | 4.35%   |
| Apple HDD HTS545050A7E362 500GB       | 1         | 1      | 4.35%   |
| A-DATA Technology SU800 1TB SSD       | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 27.27%  |
| Seagate             | 3         | 3      | 13.64%  |
| Hitachi             | 3         | 3      | 13.64%  |
| HGST                | 3         | 3      | 13.64%  |
| Kingston            | 2         | 2      | 9.09%   |
| Samsung Electronics | 1         | 8      | 4.55%   |
| OCZ                 | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |
| Apple               | 1         | 1      | 4.55%   |
| A-DATA Technology   | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 6      | 37.5%   |
| Seagate | 3         | 3      | 18.75%  |
| Hitachi | 3         | 3      | 18.75%  |
| HGST    | 3         | 3      | 18.75%  |
| Apple   | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 72.73%  |
| SSD  | 5         | 5      | 22.73%  |
| NVMe | 1         | 8      | 4.55%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 121       | 255    | 48.02%  |
| Detected | 109       | 251    | 43.25%  |
| Malfunc  | 22        | 29     | 8.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 124       | 39.74%  |
| AMD                            | 67        | 21.47%  |
| Samsung Electronics            | 38        | 12.18%  |
| Sandisk                        | 20        | 6.41%   |
| Phison Electronics             | 14        | 4.49%   |
| SK Hynix                       | 10        | 3.21%   |
| Micron/Crucial Technology      | 5         | 1.6%    |
| ASMedia Technology             | 5         | 1.6%    |
| Union Memory (Shenzhen)        | 4         | 1.28%   |
| Toshiba America Info Systems   | 4         | 1.28%   |
| Silicon Motion                 | 4         | 1.28%   |
| Micron Technology              | 3         | 0.96%   |
| Kingston Technology Company    | 3         | 0.96%   |
| KIOXIA                         | 2         | 0.64%   |
| JMicron Technology             | 2         | 0.64%   |
| ADATA Technology               | 2         | 0.64%   |
| Solid State Storage Technology | 1         | 0.32%   |
| Realtek Semiconductor          | 1         | 0.32%   |
| Nvidia                         | 1         | 0.32%   |
| Marvell Technology Group       | 1         | 0.32%   |
| Lenovo                         | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 51        | 14.37%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 30        | 8.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 4.23%   |
| AMD 400 Series Chipset SATA Controller                                         | 12        | 3.38%   |
| Phison E12 NVMe Controller                                                     | 10        | 2.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 2.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 2.82%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 9         | 2.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.41%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.41%   |
| Intel SSD 660P Series                                                          | 5         | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.41%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 4         | 1.13%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 4         | 1.13%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 1.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 1.13%   |
| SK Hynix Gold P31 SSD                                                          | 3         | 0.85%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.85%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 0.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.85%   |
| Micron Non-Volatile memory controller                                          | 3         | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 0.85%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.85%   |
| AMD X399 Series Chipset SATA Controller                                        | 3         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.85%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.56%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.56%   |
| SK Hynix BC511                                                                 | 2         | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.56%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.56%   |
| Phison NVMe Storage Controller                                                 | 2         | 0.56%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.56%   |
| Micron/Crucial NVMe Controller                                                 | 2         | 0.56%   |
| KIOXIA Non-Volatile memory controller                                          | 2         | 0.56%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.56%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 0.56%   |
| Intel PROSet/Wireless WiFi Software extension                                  | 2         | 0.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.56%   |
| AMD FCH SATA Controller D                                                      | 2         | 0.56%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 0.56%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.28%   |
| SK Hynix Non-Volatile memory controller                                        | 1         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 165       | 55%     |
| NVMe | 105       | 35%     |
| RAID | 18        | 6%      |
| IDE  | 12        | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 132       | 61.68%  |
| AMD    | 82        | 38.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 2.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 2.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.34%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 2.34%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.87%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.87%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.4%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 1.4%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.4%    |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 1.4%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 1.4%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.4%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.93%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.93%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.93%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.93%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.93%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.93%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 2         | 0.93%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 0.93%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.93%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 0.93%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.93%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 0.93%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.93%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.93%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.93%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 0.93%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.93%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 0.93%   |
| Intel Xeon CPU W3550 @ 3.07GHz                | 1         | 0.47%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz           | 1         | 0.47%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.47%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.47%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.47%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.47%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.47%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.47%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.47%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.47%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.47%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.47%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.47%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.47%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.47%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.47%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.47%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.47%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.47%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1         | 0.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.47%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 51        | 23.83%  |
| Intel Core i5           | 40        | 18.69%  |
| AMD Ryzen 5             | 26        | 12.15%  |
| AMD Ryzen 7             | 24        | 11.21%  |
| Intel Core i3           | 16        | 7.48%   |
| Other                   | 8         | 3.74%   |
| AMD Ryzen 9             | 7         | 3.27%   |
| Intel Celeron           | 6         | 2.8%    |
| AMD Ryzen 3             | 4         | 1.87%   |
| AMD Ryzen Threadripper  | 3         | 1.4%    |
| AMD FX                  | 3         | 1.4%    |
| Intel Xeon              | 2         | 0.93%   |
| Intel Pentium Silver    | 2         | 0.93%   |
| Intel Pentium Dual-Core | 2         | 0.93%   |
| Intel Pentium           | 2         | 0.93%   |
| Intel Core 2 Duo        | 2         | 0.93%   |
| AMD Ryzen 7 PRO         | 2         | 0.93%   |
| AMD A8                  | 2         | 0.93%   |
| AMD A4                  | 2         | 0.93%   |
| AMD A10                 | 2         | 0.93%   |
| Intel Core m3           | 1         | 0.47%   |
| Intel Core i9           | 1         | 0.47%   |
| Intel Core 2 Quad       | 1         | 0.47%   |
| AMD Turion              | 1         | 0.47%   |
| AMD Phenom II X6        | 1         | 0.47%   |
| AMD Phenom II X4        | 1         | 0.47%   |
| AMD Phenom II X2        | 1         | 0.47%   |
| AMD A6                  | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 77        | 35.98%  |
| 2      | 58        | 27.1%   |
| 6      | 41        | 19.16%  |
| 8      | 28        | 13.08%  |
| 16     | 4         | 1.87%   |
| 12     | 4         | 1.87%   |
| 24     | 1         | 0.47%   |
| 10     | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 214       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 170       | 79.44%  |
| 1      | 44        | 20.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 214       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 40.64%  |
| 0x306a9    | 10        | 4.57%   |
| 0x906ea    | 9         | 4.11%   |
| 0x306c3    | 9         | 4.11%   |
| 0x206a7    | 8         | 3.65%   |
| 0x906e9    | 6         | 2.74%   |
| 0x08701021 | 6         | 2.74%   |
| 0x0800820d | 5         | 2.28%   |
| 0x506e3    | 4         | 1.83%   |
| 0x0a50000c | 4         | 1.83%   |
| 0x08600103 | 4         | 1.83%   |
| 0x08108109 | 4         | 1.83%   |
| 0xa0652    | 3         | 1.37%   |
| 0x806e9    | 3         | 1.37%   |
| 0x08600106 | 3         | 1.37%   |
| 0x08600104 | 3         | 1.37%   |
| 0x08108102 | 3         | 1.37%   |
| 0x806ec    | 2         | 0.91%   |
| 0x806ea    | 2         | 0.91%   |
| 0x806c1    | 2         | 0.91%   |
| 0x40651    | 2         | 0.91%   |
| 0x106e5    | 2         | 0.91%   |
| 0x1067a    | 2         | 0.91%   |
| 0x08608103 | 2         | 0.91%   |
| 0x08001137 | 2         | 0.91%   |
| 0x06006705 | 2         | 0.91%   |
| 0xa0660    | 1         | 0.46%   |
| 0xa0655    | 1         | 0.46%   |
| 0xa0653    | 1         | 0.46%   |
| 0x906ed    | 1         | 0.46%   |
| 0x906ec    | 1         | 0.46%   |
| 0x906eb    | 1         | 0.46%   |
| 0x706e5    | 1         | 0.46%   |
| 0x706a8    | 1         | 0.46%   |
| 0x706a1    | 1         | 0.46%   |
| 0x506c9    | 1         | 0.46%   |
| 0x406e3    | 1         | 0.46%   |
| 0x20655    | 1         | 0.46%   |
| 0x106a5    | 1         | 0.46%   |
| 0x10676    | 1         | 0.46%   |
| 0x0a50000b | 1         | 0.46%   |
| 0x0a201204 | 1         | 0.46%   |
| 0x0a201016 | 1         | 0.46%   |
| 0x0a201009 | 1         | 0.46%   |
| 0x08701013 | 1         | 0.46%   |
| 0x08101016 | 1         | 0.46%   |
| 0x0810100b | 1         | 0.46%   |
| 0x08101007 | 1         | 0.46%   |
| 0x07030105 | 1         | 0.46%   |
| 0x0700010f | 1         | 0.46%   |
| 0x06006110 | 1         | 0.46%   |
| 0x06003106 | 1         | 0.46%   |
| 0x06000852 | 1         | 0.46%   |
| 0x010000dc | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 40        | 18.69%  |
| Zen 2           | 26        | 12.15%  |
| Haswell         | 18        | 8.41%   |
| Zen+            | 17        | 7.94%   |
| IvyBridge       | 15        | 7.01%   |
| Zen 3           | 13        | 6.07%   |
| SandyBridge     | 12        | 5.61%   |
| CometLake       | 12        | 5.61%   |
| Skylake         | 9         | 4.21%   |
| Zen             | 8         | 3.74%   |
| Penryn          | 5         | 2.34%   |
| TigerLake       | 4         | 1.87%   |
| Unknown         | 4         | 1.87%   |
| Puma            | 3         | 1.4%    |
| Piledriver      | 3         | 1.4%    |
| Nehalem         | 3         | 1.4%    |
| K10             | 3         | 1.4%    |
| Goldmont plus   | 3         | 1.4%    |
| Excavator       | 3         | 1.4%    |
| Westmere        | 2         | 0.93%   |
| Steamroller     | 2         | 0.93%   |
| Silvermont      | 2         | 0.93%   |
| IceLake         | 2         | 0.93%   |
| Broadwell       | 2         | 0.93%   |
| K8 & K10 hybrid | 1         | 0.47%   |
| Jaguar          | 1         | 0.47%   |
| Goldmont        | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 102       | 37.23%  |
| Intel  | 96        | 35.04%  |
| AMD    | 76        | 27.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                  | 13        | 4.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10        | 3.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 9         | 3.18%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 9         | 3.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9         | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 2.47%   |
| Intel HD Graphics 630                                                       | 7         | 2.47%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7         | 2.47%   |
| AMD Cezanne                                                                 | 6         | 2.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 1.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 5         | 1.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 5         | 1.77%   |
| Intel HD Graphics 620                                                       | 5         | 1.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 5         | 1.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 1.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 4         | 1.41%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 4         | 1.41%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4         | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 1.41%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 4         | 1.41%   |
| Nvidia TU117M                                                               | 3         | 1.06%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 3         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.06%   |
| Intel UHD Graphics 620                                                      | 3         | 1.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 1.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3         | 1.06%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3         | 1.06%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3         | 1.06%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2         | 0.71%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2         | 0.71%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.71%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 0.71%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.71%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2         | 0.71%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2         | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2         | 0.71%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2         | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 0.71%   |
| Nvidia GK107GLM [Quadro K1000M]                                             | 2         | 0.71%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 0.71%   |
| Intel HD Graphics 530                                                       | 2         | 0.71%   |
| Intel HD Graphics 510                                                       | 2         | 0.71%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 2         | 0.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 0.71%   |
| AMD Mullins [Radeon R3 Graphics]                                            | 2         | 0.71%   |
| AMD Lucienne                                                                | 2         | 0.71%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.35%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.35%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.35%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                      | 1         | 0.35%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1         | 0.35%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.35%   |
| Nvidia GT218M [NVS 3100M]                                                   | 1         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 53        | 24.77%  |
| 1 x AMD            | 53        | 24.77%  |
| 1 x Nvidia         | 48        | 22.43%  |
| Intel + Nvidia     | 33        | 15.42%  |
| AMD + Nvidia       | 17        | 7.94%   |
| Intel + AMD        | 4         | 1.87%   |
| 2 x Nvidia         | 2         | 0.93%   |
| 2 x AMD            | 2         | 0.93%   |
| Intel + 2 x Nvidia | 2         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 135       | 62.79%  |
| Proprietary | 80        | 37.21%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 112       | 51.38%  |
| 0.01-0.5   | 25        | 11.47%  |
| 1.01-2.0   | 21        | 9.63%   |
| 7.01-8.0   | 17        | 7.8%    |
| 3.01-4.0   | 16        | 7.34%   |
| 5.01-6.0   | 10        | 4.59%   |
| 0.51-1.0   | 9         | 4.13%   |
| 8.01-16.0  | 5         | 2.29%   |
| 2.01-3.0   | 2         | 0.92%   |
| 16.01-24.0 | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 12.02%  |
| Samsung Electronics     | 29        | 11.24%  |
| LG Display              | 22        | 8.53%   |
| BOE                     | 19        | 7.36%   |
| Dell                    | 17        | 6.59%   |
| Chimei Innolux          | 16        | 6.2%    |
| Acer                    | 13        | 5.04%   |
| Goldstar                | 12        | 4.65%   |
| Hewlett-Packard         | 10        | 3.88%   |
| AOC                     | 9         | 3.49%   |
| BenQ                    | 8         | 3.1%    |
| PANDA                   | 7         | 2.71%   |
| Ancor Communications    | 7         | 2.71%   |
| Unknown                 | 6         | 2.33%   |
| Sharp                   | 6         | 2.33%   |
| Lenovo                  | 5         | 1.94%   |
| ASUSTek Computer        | 4         | 1.55%   |
| Sony                    | 3         | 1.16%   |
| MSI                     | 3         | 1.16%   |
| Apple                   | 3         | 1.16%   |
| Vizio                   | 2         | 0.78%   |
| Philips                 | 2         | 0.78%   |
| Mi                      | 2         | 0.78%   |
| Iiyama                  | 2         | 0.78%   |
| Gigabyte Technology     | 2         | 0.78%   |
| CSO                     | 2         | 0.78%   |
| ONN                     | 1         | 0.39%   |
| MiTAC                   | 1         | 0.39%   |
| LTM                     | 1         | 0.39%   |
| LG Electronics          | 1         | 0.39%   |
| Lenovo Group Limited    | 1         | 0.39%   |
| Insignia                | 1         | 0.39%   |
| InfoVision              | 1         | 0.39%   |
| HPN                     | 1         | 0.39%   |
| HKC                     | 1         | 0.39%   |
| G-Story                 | 1         | 0.39%   |
| Fujitsu Siemens         | 1         | 0.39%   |
| Eizo                    | 1         | 0.39%   |
| CPT                     | 1         | 0.39%   |
| Chi Mei Optoelectronics | 1         | 0.39%   |
| AOpen                   | 1         | 0.39%   |
| Alba                    | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 4         | 1.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3         | 1.14%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch   | 2         | 0.76%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.76%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 0.76%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 2         | 0.76%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                | 2         | 0.76%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.76%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.76%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 2         | 0.76%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                  | 2         | 0.76%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 0.76%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                  | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch         | 2         | 0.76%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2         | 0.76%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                     | 2         | 0.76%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2         | 0.76%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1         | 0.38%   |
| Vizio E320-B2 VIZ0095 1360x768 477x268mm 21.5-inch                     | 1         | 0.38%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1         | 0.38%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1         | 0.38%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 0.38%   |
| Unknown LCD Monitor RJT HDMI                                           | 1         | 0.38%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1         | 0.38%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1         | 0.38%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.38%   |
| Sony TV SNY1802 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.38%   |
| Sony TV SNY0801 1360x768                                               | 1         | 0.38%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch                | 1         | 0.38%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.38%   |
| Sharp LQ133T1JW17 SHP1409 2560x1440 294x165mm 13.3-inch                | 1         | 0.38%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.38%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.38%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.38%   |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1         | 0.38%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1         | 0.38%   |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch      | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1         | 0.38%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch    | 1         | 0.38%   |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1         | 0.38%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch      | 1         | 0.38%   |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0FBE 3840x2160 950x540mm 43.0-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 1210x680mm 54.6-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 480x270mm 21.7-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                      | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1         | 0.38%   |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                      | 1         | 0.38%   |
| Samsung Electronics LCD Monitor C32R50x                                | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 123       | 50.2%   |
| 1366x768 (WXGA)    | 24        | 9.8%    |
| 3840x2160 (4K)     | 17        | 6.94%   |
| 2560x1440 (QHD)    | 12        | 4.9%    |
| 1600x900 (HD+)     | 12        | 4.9%    |
| Unknown            | 8         | 3.27%   |
| 1680x1050 (WSXGA+) | 6         | 2.45%   |
| 3840x1080          | 5         | 2.04%   |
| 3440x1440          | 5         | 2.04%   |
| 2560x1080          | 4         | 1.63%   |
| 1440x900 (WXGA+)   | 4         | 1.63%   |
| 2560x1600          | 3         | 1.22%   |
| 7680x2160          | 2         | 0.82%   |
| 2256x1504          | 2         | 0.82%   |
| 1920x1200 (WUXGA)  | 2         | 0.82%   |
| 1360x768           | 2         | 0.82%   |
| 1280x800 (WXGA)    | 2         | 0.82%   |
| 1280x1024 (SXGA)   | 2         | 0.82%   |
| 4480x1440          | 1         | 0.41%   |
| 3840x2400          | 1         | 0.41%   |
| 3840x1200          | 1         | 0.41%   |
| 3200x1800 (QHD+)   | 1         | 0.41%   |
| 2880x1440          | 1         | 0.41%   |
| 2160x1440          | 1         | 0.41%   |
| 2048x1152          | 1         | 0.41%   |
| 1680x945           | 1         | 0.41%   |
| 1600x1200          | 1         | 0.41%   |
| 1024x768 (XGA)     | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 72        | 29.15%  |
| 27      | 28        | 11.34%  |
| Unknown | 21        | 8.5%    |
| 23      | 17        | 6.88%   |
| 24      | 15        | 6.07%   |
| 14      | 15        | 6.07%   |
| 13      | 13        | 5.26%   |
| 17      | 10        | 4.05%   |
| 22      | 7         | 2.83%   |
| 34      | 6         | 2.43%   |
| 21      | 6         | 2.43%   |
| 19      | 6         | 2.43%   |
| 16      | 4         | 1.62%   |
| 72      | 3         | 1.21%   |
| 49      | 3         | 1.21%   |
| 31      | 3         | 1.21%   |
| 20      | 3         | 1.21%   |
| 18      | 3         | 1.21%   |
| 40      | 2         | 0.81%   |
| 28      | 2         | 0.81%   |
| 54      | 1         | 0.4%    |
| 48      | 1         | 0.4%    |
| 43      | 1         | 0.4%    |
| 39      | 1         | 0.4%    |
| 33      | 1         | 0.4%    |
| 25      | 1         | 0.4%    |
| 12      | 1         | 0.4%    |
| 11      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 95        | 39.26%  |
| 501-600     | 54        | 22.31%  |
| 401-500     | 23        | 9.5%    |
| Unknown     | 21        | 8.68%   |
| 351-400     | 12        | 4.96%   |
| 201-300     | 10        | 4.13%   |
| 601-700     | 8         | 3.31%   |
| 701-800     | 7         | 2.89%   |
| 1001-1500   | 5         | 2.07%   |
| 801-900     | 3         | 1.24%   |
| 1501-2000   | 3         | 1.24%   |
| 901-1000    | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 173       | 75.88%  |
| 16/10   | 21        | 9.21%   |
| Unknown | 18        | 7.89%   |
| 21/9    | 7         | 3.07%   |
| 3/2     | 3         | 1.32%   |
| 5/4     | 2         | 0.88%   |
| 32/9    | 2         | 0.88%   |
| 4/3     | 1         | 0.44%   |
| 2.00    | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 73        | 30.04%  |
| 201-250        | 36        | 14.81%  |
| 301-350        | 28        | 11.52%  |
| 81-90          | 24        | 9.88%   |
| Unknown        | 21        | 8.64%   |
| 351-500        | 11        | 4.53%   |
| 151-200        | 10        | 4.12%   |
| 121-130        | 9         | 3.7%    |
| More than 1000 | 6         | 2.47%   |
| 251-300        | 6         | 2.47%   |
| 501-1000       | 6         | 2.47%   |
| 71-80          | 4         | 1.65%   |
| 141-150        | 4         | 1.65%   |
| 111-120        | 2         | 0.82%   |
| 61-70          | 1         | 0.41%   |
| 51-60          | 1         | 0.41%   |
| 91-100         | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 77        | 33.05%  |
| 51-100        | 67        | 28.76%  |
| 101-120       | 46        | 19.74%  |
| Unknown       | 21        | 9.01%   |
| 161-240       | 10        | 4.29%   |
| 1-50          | 7         | 3%      |
| More than 240 | 5         | 2.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 157       | 72.69%  |
| 2     | 50        | 23.15%  |
| 3     | 7         | 3.24%   |
| 0     | 2         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 127       | 37.35%  |
| Intel                             | 110       | 32.35%  |
| Qualcomm Atheros                  | 38        | 11.18%  |
| Broadcom                          | 15        | 4.41%   |
| Ralink Technology                 | 5         | 1.47%   |
| NetGear                           | 5         | 1.47%   |
| MEDIATEK                          | 5         | 1.47%   |
| TP-Link                           | 3         | 0.88%   |
| Samsung Electronics               | 3         | 0.88%   |
| Linksys                           | 3         | 0.88%   |
| Aquantia                          | 3         | 0.88%   |
| Ralink                            | 2         | 0.59%   |
| Qualcomm                          | 2         | 0.59%   |
| DisplayLink                       | 2         | 0.59%   |
| ASIX Electronics                  | 2         | 0.59%   |
| Xiaomi                            | 1         | 0.29%   |
| Wacom                             | 1         | 0.29%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.29%   |
| Nvidia                            | 1         | 0.29%   |
| Microsoft                         | 1         | 0.29%   |
| Lenovo                            | 1         | 0.29%   |
| InterBiometrics                   | 1         | 0.29%   |
| Holtek Semiconductor              | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| Dell                              | 1         | 0.29%   |
| Broadcom Limited                  | 1         | 0.29%   |
| Belkin Components                 | 1         | 0.29%   |
| ASUSTek Computer                  | 1         | 0.29%   |
| Alteon Networks                   | 1         | 0.29%   |
| Accton Technology                 | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 91        | 23.04%  |
| Intel Wi-Fi 6 AX200                                                 | 20        | 5.06%   |
| Intel I211 Gigabit Network Connection                               | 12        | 3.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 11        | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 8         | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 8         | 2.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 7         | 1.77%   |
| Realtek RTL8125 2.5GbE Controller                                   | 7         | 1.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7         | 1.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 7         | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 7         | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 7         | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 6         | 1.52%   |
| Intel Ethernet Controller I225-V                                    | 6         | 1.52%   |
| Intel Ethernet Connection I217-LM                                   | 6         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6         | 1.52%   |
| Intel Wireless-AC 9260                                              | 5         | 1.27%   |
| Intel Wireless 8265 / 8275                                          | 5         | 1.27%   |
| Intel Wireless 3165                                                 | 5         | 1.27%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 4         | 1.01%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4         | 1.01%   |
| Intel Wireless 7260                                                 | 4         | 1.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 4         | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3         | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3         | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 3         | 0.76%   |
| Intel Centrino Advanced-N 6200                                      | 3         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                            | 3         | 0.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 2         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 2         | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller           | 2         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2         | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2         | 0.51%   |
| NetGear A6210                                                       | 2         | 0.51%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter       | 2         | 0.51%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2         | 0.51%   |
| Intel Wireless 8260                                                 | 2         | 0.51%   |
| Intel Wireless 7265                                                 | 2         | 0.51%   |
| Intel Wi-Fi 6 AX201                                                 | 2         | 0.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 2         | 0.51%   |
| Intel Ethernet Connection I219-LM                                   | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                               | 2         | 0.51%   |
| Intel Ethernet Connection (2) I219-V                                | 2         | 0.51%   |
| Intel Centrino Ultimate-N 6300                                      | 2         | 0.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 2         | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express              | 2         | 0.51%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 0.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 2         | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                       | 2         | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1         | 0.25%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                            | 1         | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 87        | 46.52%  |
| Realtek Semiconductor | 34        | 18.18%  |
| Qualcomm Atheros      | 28        | 14.97%  |
| Broadcom              | 11        | 5.88%   |
| Ralink Technology     | 5         | 2.67%   |
| NetGear               | 5         | 2.67%   |
| TP-Link               | 3         | 1.6%    |
| MEDIATEK              | 3         | 1.6%    |
| Linksys               | 3         | 1.6%    |
| Ralink                | 2         | 1.07%   |
| Wacom                 | 1         | 0.53%   |
| Microsoft             | 1         | 0.53%   |
| Dell                  | 1         | 0.53%   |
| Broadcom Limited      | 1         | 0.53%   |
| ASUSTek Computer      | 1         | 0.53%   |
| Accton Technology     | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 20        | 10.64%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 11        | 5.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 8         | 4.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 7         | 3.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 7         | 3.72%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 7         | 3.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 7         | 3.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 6         | 3.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6         | 3.19%   |
| Intel Wireless-AC 9260                                                    | 5         | 2.66%   |
| Intel Wireless 8265 / 8275                                                | 5         | 2.66%   |
| Intel Wireless 3165                                                       | 5         | 2.66%   |
| Intel Wireless 7260                                                       | 4         | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 4         | 2.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 3         | 1.6%    |
| Intel Centrino Advanced-N 6200                                            | 3         | 1.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                               | 2         | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2         | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 2         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 2         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 2         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 1.06%   |
| NetGear A6210                                                             | 2         | 1.06%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter             | 2         | 1.06%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2         | 1.06%   |
| Intel Wireless 8260                                                       | 2         | 1.06%   |
| Intel Wireless 7265                                                       | 2         | 1.06%   |
| Intel Wi-Fi 6 AX201                                                       | 2         | 1.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 2         | 1.06%   |
| Intel Centrino Ultimate-N 6300                                            | 2         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 2         | 1.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 2         | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                       | 2         | 1.06%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                  | 1         | 0.53%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.53%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1         | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1         | 0.53%   |
| Realtek RTL8191SEvA Wireless LAN Controller                               | 1         | 0.53%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1         | 0.53%   |
| Realtek 802.11n WLAN Adapter                                              | 1         | 0.53%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1         | 0.53%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                         | 1         | 0.53%   |
| Ralink MT7601U Wireless Adapter                                           | 1         | 0.53%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1         | 0.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.53%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1         | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.53%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1         | 0.53%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.53%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]               | 1         | 0.53%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1         | 0.53%   |
| MediaTek WiFi                                                             | 1         | 0.53%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1         | 0.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection             | 1         | 0.53%   |
| Intel Gemini Lake PCH CNVi WiFi                                           | 1         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 112       | 55.72%  |
| Intel                 | 48        | 23.88%  |
| Qualcomm Atheros      | 15        | 7.46%   |
| Broadcom              | 7         | 3.48%   |
| Samsung Electronics   | 3         | 1.49%   |
| Aquantia              | 3         | 1.49%   |
| Qualcomm              | 2         | 1%      |
| MediaTek              | 2         | 1%      |
| DisplayLink           | 2         | 1%      |
| ASIX Electronics      | 2         | 1%      |
| Xiaomi                | 1         | 0.5%    |
| Nvidia                | 1         | 0.5%    |
| Lenovo                | 1         | 0.5%    |
| Belkin Components     | 1         | 0.5%    |
| Alteon Networks       | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 91        | 44.83%  |
| Intel I211 Gigabit Network Connection                             | 12        | 5.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 3.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.45%   |
| Intel Ethernet Controller I225-V                                  | 6         | 2.96%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.96%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 1.97%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 1.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.48%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.99%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.99%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.99%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.99%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.99%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.49%   |
| Qualcomm SDM710-QRD _SN:0BC14CBF                                  | 1         | 0.49%   |
| Qualcomm Redmi Note 7                                             | 1         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.49%   |
| MediaTek U FEEL                                                   | 1         | 0.49%   |
| MediaTek Infinix HOT 10 Play                                      | 1         | 0.49%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.49%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.49%   |
| DisplayLink ThinkPad USB 3.0 Dock                                 | 1         | 0.49%   |
| DisplayLink Dell D1000 USB3.0 Dock                                | 1         | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.49%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 0.49%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1         | 0.49%   |
| Belkin Components F5D5050 100Mbps Ethernet                        | 1         | 0.49%   |
| Aquantia Ethernet controller                                      | 1         | 0.49%   |
| Alteon Networks Ethernet controller                               | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 183       | 50.83%  |
| WiFi     | 173       | 48.06%  |
| Modem    | 2         | 0.56%   |
| Unknown  | 2         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 55.69%  |
| Ethernet | 108       | 43.9%   |
| Unknown  | 1         | 0.41%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 121       | 56.28%  |
| 1     | 83        | 38.6%   |
| 3     | 7         | 3.26%   |
| 0     | 3         | 1.4%    |
| 4     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 169       | 78.6%   |
| Yes  | 46        | 21.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 47.74%  |
| Qualcomm Atheros Communications | 23        | 14.84%  |
| Realtek Semiconductor           | 21        | 13.55%  |
| Cambridge Silicon Radio         | 7         | 4.52%   |
| IMC Networks                    | 6         | 3.87%   |
| Broadcom                        | 5         | 3.23%   |
| Lite-On Technology              | 4         | 2.58%   |
| Apple                           | 4         | 2.58%   |
| ASUSTek Computer                | 3         | 1.94%   |
| Hewlett-Packard                 | 2         | 1.29%   |
| Foxconn / Hon Hai               | 2         | 1.29%   |
| Dell                            | 2         | 1.29%   |
| Realtek                         | 1         | 0.65%   |
| Dynex                           | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                                               | 20        | 12.9%   |
| Intel Bluetooth wireless interface                                                  | 15        | 9.68%   |
| Realtek Bluetooth Radio                                                             | 11        | 7.1%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 7.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 7.1%    |
| Intel AX201 Bluetooth                                                               | 11        | 7.1%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 5.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 4.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 3.87%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 3.87%   |
| Intel Bluetooth Device                                                              | 5         | 3.23%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.94%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.29%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.29%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.29%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.29%   |
| ASUS Bluetooth Radio                                                                | 2         | 1.29%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.65%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.65%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.65%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.65%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.65%   |
| Dynex BCM20702A0                                                                    | 1         | 0.65%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.65%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.65%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.65%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.65%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.65%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.65%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 130       | 38.24%  |
| AMD                       | 90        | 26.47%  |
| Nvidia                    | 73        | 21.47%  |
| C-Media Electronics       | 8         | 2.35%   |
| Logitech                  | 6         | 1.76%   |
| Sony                      | 2         | 0.59%   |
| Sennheiser Communications | 2         | 0.59%   |
| RODE Microphones          | 2         | 0.59%   |
| JMTek                     | 2         | 0.59%   |
| Generalplus Technology    | 2         | 0.59%   |
| Creative Technology       | 2         | 0.59%   |
| Creative Labs             | 2         | 0.59%   |
| Yamaha                    | 1         | 0.29%   |
| Turtle Beach              | 1         | 0.29%   |
| Trust                     | 1         | 0.29%   |
| Texas Instruments         | 1         | 0.29%   |
| Tenx Technology           | 1         | 0.29%   |
| SteelSeries ApS           | 1         | 0.29%   |
| Realtek Semiconductor     | 1         | 0.29%   |
| Plantronics               | 1         | 0.29%   |
| Phison Electronics        | 1         | 0.29%   |
| Kingston Technology       | 1         | 0.29%   |
| Jieli Technology          | 1         | 0.29%   |
| Huawei Technologies       | 1         | 0.29%   |
| Hewlett-Packard           | 1         | 0.29%   |
| GN Netcom                 | 1         | 0.29%   |
| Focusrite-Novation        | 1         | 0.29%   |
| EVGA                      | 1         | 0.29%   |
| DigiTech                  | 1         | 0.29%   |
| Corsair                   | 1         | 0.29%   |
| Blue Microphones          | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 33        | 8.11%   |
| AMD Starship/Matisse HD Audio Controller                                   | 20        | 4.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 3.69%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 3.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 3.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 2.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11        | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 2.46%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 1.97%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 1.97%   |
| Nvidia GP104 High Definition Audio Controller                              | 7         | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.72%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.72%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.47%   |
| Nvidia GM204 High Definition Audio Controller                              | 6         | 1.47%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.47%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.47%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 1.23%   |
| Nvidia High Definition Audio Controller                                    | 4         | 0.98%   |
| Nvidia Audio device                                                        | 4         | 0.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 0.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 0.98%   |
| C-Media Electronics KLIM Mantis Audio 7.1                                  | 4         | 0.98%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 4         | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.74%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 0.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 0.74%   |
| Intel Comet Lake PCH-V cAVS                                                | 3         | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.74%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.74%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 0.74%   |
| RODE Microphones RODE NT-USB                                               | 2         | 0.49%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.49%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia GF106 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 0.49%   |
| Logitech G933 Wireless Headset Dongle                                      | 2         | 0.49%   |
| JMTek USB PnP Audio Device                                                 | 2         | 0.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.49%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.49%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.49%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 0.49%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.49%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.49%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2         | 0.49%   |
| AMD High Definition Audio Controller                                       | 2         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 23.49%  |
| SK Hynix            | 27        | 16.27%  |
| Crucial             | 16        | 9.64%   |
| Micron Technology   | 14        | 8.43%   |
| G.Skill             | 13        | 7.83%   |
| Corsair             | 10        | 6.02%   |
| Kingston            | 9         | 5.42%   |
| Unknown             | 7         | 4.22%   |
| Patriot             | 6         | 3.61%   |
| Ramaxel Technology  | 5         | 3.01%   |
| A-DATA Technology   | 4         | 2.41%   |
| Team                | 3         | 1.81%   |
| Unknown (ABCD)      | 2         | 1.2%    |
| Smart               | 2         | 1.2%    |
| Nanya Technology    | 2         | 1.2%    |
| Transcend           | 1         | 0.6%    |
| TIMETEC             | 1         | 0.6%    |
| Elpida              | 1         | 0.6%    |
| CSX                 | 1         | 0.6%    |
| Avant               | 1         | 0.6%    |
| Apacer              | 1         | 0.6%    |
| 48spaces            | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 2.79%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 5         | 2.79%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                | 5         | 2.79%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 2.23%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 1.68%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 1.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 3         | 1.68%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s               | 3         | 1.68%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.12%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 2         | 1.12%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                | 2         | 1.12%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 1.12%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.12%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.12%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1.12%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.12%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2667MT/s                  | 2         | 1.12%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4096MB SODIMM DDR3 1600MT/s             | 2         | 1.12%   |
| G.Skill RAM F4-3600C16-16GVKC 16384MB DIMM DDR4 3866MT/s            | 2         | 1.12%   |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s               | 2         | 1.12%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.56%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                                | 1         | 0.56%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s               | 1         | 0.56%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s            | 1         | 0.56%   |
| TIMETEC RAM SD3-1866 8GB SODIMM DDR3 1866MT/s                       | 1         | 0.56%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s                  | 1         | 0.56%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s                  | 1         | 0.56%   |
| Team RAM TEAMGROUP-SD4-2133 8GB SODIMM DDR4 2133MT/s                | 1         | 0.56%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s            | 1         | 0.56%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                      | 1         | 0.56%   |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s                | 1         | 0.56%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.56%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.56%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s                | 1         | 0.56%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.56%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8192MB Row Of Chips DDR4 2667MT/s     | 1         | 0.56%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.56%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.56%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s        | 1         | 0.56%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.56%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.56%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.56%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.56%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.56%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.56%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                           | 1         | 0.56%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 0.56%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                          | 1         | 0.56%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 0.56%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1600MT/s               | 1         | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 0.56%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 94        | 67.14%  |
| DDR3    | 37        | 26.43%  |
| LPDDR4  | 3         | 2.14%   |
| Unknown | 3         | 2.14%   |
| DDR2    | 2         | 1.43%   |
| LPDDR3  | 1         | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 62.68%  |
| DIMM         | 43        | 30.28%  |
| Row Of Chips | 9         | 6.34%   |
| Unknown      | 1         | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 81        | 51.59%  |
| 4096  | 42        | 26.75%  |
| 16384 | 26        | 16.56%  |
| 2048  | 5         | 3.18%   |
| 32768 | 2         | 1.27%   |
| 1024  | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 35        | 22.15%  |
| 2667  | 33        | 20.89%  |
| 1600  | 28        | 17.72%  |
| 2400  | 15        | 9.49%   |
| 3600  | 12        | 7.59%   |
| 2133  | 4         | 2.53%   |
| 3466  | 3         | 1.9%    |
| 3266  | 3         | 1.9%    |
| 1334  | 3         | 1.9%    |
| 1333  | 3         | 1.9%    |
| 3866  | 2         | 1.27%   |
| 2666  | 2         | 1.27%   |
| 1866  | 2         | 1.27%   |
| 1800  | 2         | 1.27%   |
| 800   | 2         | 1.27%   |
| 4266  | 1         | 0.63%   |
| 4200  | 1         | 0.63%   |
| 4000  | 1         | 0.63%   |
| 3067  | 1         | 0.63%   |
| 2933  | 1         | 0.63%   |
| 2200  | 1         | 0.63%   |
| 1867  | 1         | 0.63%   |
| 1066  | 1         | 0.63%   |
| 667   | 1         | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 37.5%   |
| Samsung Electronics | 1         | 12.5%   |
| Kyocera             | 1         | 12.5%   |
| Fuji Xerox          | 1         | 12.5%   |
| Dymo-CoStar         | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series   | 1         | 12.5%   |
| Kyocera FS-1030D printer         | 1         | 12.5%   |
| HP OfficeJet Pro 8020 series     | 1         | 12.5%   |
| HP LaserJet 200 colorMFP M275nw  | 1         | 12.5%   |
| HP DeskJet Plus 4100 series      | 1         | 12.5%   |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 12.5%   |
| Dymo-CoStar LabelWriter 450      | 1         | 12.5%   |
| Brother HL-5370DW series         | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 23.91%  |
| Logitech                               | 13        | 9.42%   |
| IMC Networks                           | 13        | 9.42%   |
| Realtek Semiconductor                  | 10        | 7.25%   |
| Microdia                               | 10        | 7.25%   |
| Acer                                   | 8         | 5.8%    |
| Quanta                                 | 7         | 5.07%   |
| Microsoft                              | 6         | 4.35%   |
| Sunplus Innovation Technology          | 5         | 3.62%   |
| Syntek                                 | 4         | 2.9%    |
| Apple                                  | 4         | 2.9%    |
| Suyin                                  | 3         | 2.17%   |
| Lite-On Technology                     | 3         | 2.17%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.17%   |
| Silicon Motion                         | 2         | 1.45%   |
| Luxvisions Innotech Limited            | 2         | 1.45%   |
| Jieli Technology                       | 2         | 1.45%   |
| Z-Star Microelectronics                | 1         | 0.72%   |
| WaveRider Communications               | 1         | 0.72%   |
| Sonix Technology                       | 1         | 0.72%   |
| Samsung Electronics                    | 1         | 0.72%   |
| Razer USA                              | 1         | 0.72%   |
| MacroSilicon                           | 1         | 0.72%   |
| Lenovo                                 | 1         | 0.72%   |
| Importek                               | 1         | 0.72%   |
| Genesys Logic                          | 1         | 0.72%   |
| DJKANA1BIFZTDM                         | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 6         | 4.32%   |
| IMC Networks Integrated Camera                      | 6         | 4.32%   |
| Chicony Integrated Camera                           | 6         | 4.32%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 3.6%    |
| Chicony HD WebCam                                   | 5         | 3.6%    |
| Syntek Integrated Camera                            | 4         | 2.88%   |
| Chicony HD User Facing                              | 4         | 2.88%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 2.16%   |
| Lite-On HP Wide Vision HD Camera                    | 3         | 2.16%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 1.44%   |
| Microsoft LifeCam HD-5000                           | 2         | 1.44%   |
| Microsoft LifeCam HD-3000                           | 2         | 1.44%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.44%   |
| Logitech Webcam C930e                               | 2         | 1.44%   |
| Logitech Webcam C270                                | 2         | 1.44%   |
| Logitech HD Webcam C910                             | 2         | 1.44%   |
| Logitech C922 Pro Stream Webcam                     | 2         | 1.44%   |
| Jieli USB PHY 2.0                                   | 2         | 1.44%   |
| Chicony USB 2.0 Camera                              | 2         | 1.44%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.44%   |
| Chicony EasyCamera                                  | 2         | 1.44%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 1.44%   |
| Acer Integrated Camera                              | 2         | 1.44%   |
| Acer HD Webcam                                      | 2         | 1.44%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 0.72%   |
| WaveRider USB Live camera                           | 1         | 0.72%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.72%   |
| Suyin HP Integrated Webcam                          | 1         | 0.72%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.72%   |
| Sunplus MTD Camera                                  | 1         | 0.72%   |
| Sunplus Integrated Webcam                           | 1         | 0.72%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.72%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.72%   |
| Silicon Motion Web Camera                           | 1         | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.72%   |
| Realtek USB Camera                                  | 1         | 0.72%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.72%   |
| Realtek Integrated Webcam                           | 1         | 0.72%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.72%   |
| Realtek HD WebCam                                   | 1         | 0.72%   |
| Realtek FULL HD 1080P Webcam                        | 1         | 0.72%   |
| Realtek FJ Camera                                   | 1         | 0.72%   |
| Realtek EasyCamera                                  | 1         | 0.72%   |
| Realtek Built-In Video Camera                       | 1         | 0.72%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 0.72%   |
| Razer USA Razer Kiyo Pro                            | 1         | 0.72%   |
| Quanta WEBCAM                                       | 1         | 0.72%   |
| Quanta USB2.0 VGA UVC WebCam                        | 1         | 0.72%   |
| Quanta HP True Vision HD Camera                     | 1         | 0.72%   |
| Quanta HD User Facing                               | 1         | 0.72%   |
| Quanta HD Camera                                    | 1         | 0.72%   |
| Microsoft Xbox NUI Camera                           | 1         | 0.72%   |
| Microsoft Modern Webcam                             | 1         | 0.72%   |
| Microdia Webcam Vitade AF                           | 1         | 0.72%   |
| Microdia PC Microscope camera                       | 1         | 0.72%   |
| Microdia Integrated Webcam HD                       | 1         | 0.72%   |
| Microdia HP Integrated Webcam                       | 1         | 0.72%   |
| MacroSilicon MiraBox Capture                        | 1         | 0.72%   |
| Logitech Webcam Pro 9000                            | 1         | 0.72%   |
| Logitech Webcam C925e                               | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 24%     |
| Synaptics                  | 6         | 24%     |
| Shenzhen Goodix Technology | 5         | 20%     |
| Elan Microelectronics      | 4         | 16%     |
| LighTuning Technology      | 2         | 8%      |
| AuthenTec                  | 2         | 8%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 3         | 12%     |
| Elan ELAN:ARM-M4                                  | 3         | 12%     |
| Validity Sensors Synaptics WBDI                   | 2         | 8%      |
| Unknown                                           | 2         | 8%      |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 4%      |
| Synaptics WBDI Device                             | 1         | 4%      |
| Synaptics  WBDI Fingerprint Reader - USB 052      | 1         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 4%      |
| Shenzhen Goodix Fingerprint Reader                | 1         | 4%      |
| Shenzhen Goodix FingerPrint                       | 1         | 4%      |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 4%      |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 4%      |
| Elan ELAN:Fingerprint                             | 1         | 4%      |
| AuthenTec AES2810                                 | 1         | 4%      |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 60%     |
| Upek        | 1         | 10%     |
| O2 Micro    | 1         | 10%     |
| Lenovo      | 1         | 10%     |
| Alcor Micro | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 30%     |
| Broadcom 5880                                                                | 2         | 20%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 103       | 47.47%  |
| 0     | 73        | 33.64%  |
| 2     | 34        | 15.67%  |
| 3     | 6         | 2.76%   |
| 4     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 121       | 62.69%  |
| Fingerprint reader       | 25        | 12.95%  |
| Graphics card            | 11        | 5.7%    |
| Chipcard                 | 10        | 5.18%   |
| Net/wireless             | 9         | 4.66%   |
| Net/ethernet             | 6         | 3.11%   |
| Camera                   | 4         | 2.07%   |
| Multimedia controller    | 3         | 1.55%   |
| Wireless                 | 1         | 0.52%   |
| Storage                  | 1         | 0.52%   |
| Network                  | 1         | 0.52%   |
| Bluetooth                | 1         | 0.52%   |

