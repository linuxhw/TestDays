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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.2-zen1-1-zen      | 7         | 3.06%   |
| 5.14.14-zen1-1-zen     | 6         | 2.62%   |
| 5.16.4-zen1-1-zen      | 5         | 2.18%   |
| 5.15.13-zen1-1-zen     | 5         | 2.18%   |
| 5.15.12-zen1-1-zen     | 5         | 2.18%   |
| 5.13.9-zen1-1-zen      | 5         | 2.18%   |
| 5.13.13-zen1-1-zen     | 5         | 2.18%   |
| 5.11.16-zen1-1-zen     | 5         | 2.18%   |
| 5.11.11-zen1-1-zen     | 5         | 2.18%   |
| 5.16.2-zen1-1-zen      | 4         | 1.75%   |
| 5.15.7-zen1-1-zen      | 4         | 1.75%   |
| 5.15.6-zen2-1-zen      | 4         | 1.75%   |
| 5.10.4-107-tkg-bmq     | 4         | 1.75%   |
| 5.10.1-103-tkg-bmq     | 4         | 1.75%   |
| 5.9.10-zen1-1-zen      | 3         | 1.31%   |
| 5.9.1-zen2-1-zen       | 3         | 1.31%   |
| 5.16.5-zen1-1-zen      | 3         | 1.31%   |
| 5.15.5-zen1-1-zen      | 3         | 1.31%   |
| 5.15.10-zen1-1-zen     | 3         | 1.31%   |
| 5.14.6-zen1-1-zen      | 3         | 1.31%   |
| 5.14.15-zen1-1-zen     | 3         | 1.31%   |
| 5.10.8-112-tkg-bmq     | 3         | 1.31%   |
| 5.10.2-104-tkg-bmq     | 3         | 1.31%   |
| 5.10.15-120-tkg-bmq    | 3         | 1.31%   |
| 5.10.10-115-tkg-bmq    | 3         | 1.31%   |
| 5.9.8-zen1-1-zen       | 2         | 0.87%   |
| 5.9.2-zen1-1-zen       | 2         | 0.87%   |
| 5.9.11-zen2-1-zen      | 2         | 0.87%   |
| 5.8.14-zen1-1-zen      | 2         | 0.87%   |
| 5.16.9-zen1-1-zen      | 2         | 0.87%   |
| 5.16.8-zen1-1-zen      | 2         | 0.87%   |
| 5.16.8-arch1-1         | 2         | 0.87%   |
| 5.16.10-zen1-1-zen     | 2         | 0.87%   |
| 5.16.1-zen1-1-zen      | 2         | 0.87%   |
| 5.16.0-zen1-1-zen      | 2         | 0.87%   |
| 5.15.4-zen1-1-zen      | 2         | 0.87%   |
| 5.14.9-zen2-1-zen      | 2         | 0.87%   |
| 5.14.12-zen1-1-zen     | 2         | 0.87%   |
| 5.13.5-zen1-1-zen      | 2         | 0.87%   |
| 5.13.12-zen1-1-zen     | 2         | 0.87%   |
| 5.12.9-zen1-1-zen      | 2         | 0.87%   |
| 5.12.7-zen1-1-zen      | 2         | 0.87%   |
| 5.12.4-zen1-2-zen      | 2         | 0.87%   |
| 5.12.2-153-tkg-bmq     | 2         | 0.87%   |
| 5.12.15-zen1-1-zen     | 2         | 0.87%   |
| 5.12.14-zen1-1-zen     | 2         | 0.87%   |
| 5.12.13-zen1-1-zen     | 2         | 0.87%   |
| 5.12.12-AMD-znver2     | 2         | 0.87%   |
| 5.11.6-zen1-1-zen      | 2         | 0.87%   |
| 5.10.7-111-tkg-bmq     | 2         | 0.87%   |
| 5.9.9-zen1-1-zen       | 1         | 0.44%   |
| 5.9.6-zen1-1-zen       | 1         | 0.44%   |
| 5.9.4-zen1-1-zen       | 1         | 0.44%   |
| 5.9.14-99-tkg-bmq      | 1         | 0.44%   |
| 5.8.5-zen1-1-zen       | 1         | 0.44%   |
| 5.8.10-zen1-1-zen      | 1         | 0.44%   |
| 5.8.0-xanmod1-1-xanmod | 1         | 0.44%   |
| 5.6.6-zen1-1-zen       | 1         | 0.44%   |
| 5.4.97-120-tkg-bmq     | 1         | 0.44%   |
| 5.16.7-arch1-1         | 1         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.2  | 7         | 3.06%   |
| 5.14.14 | 6         | 2.62%   |
| 5.11.11 | 6         | 2.62%   |
| 5.10.4  | 6         | 2.62%   |
| 5.16.5  | 5         | 2.18%   |
| 5.16.4  | 5         | 2.18%   |
| 5.15.7  | 5         | 2.18%   |
| 5.15.6  | 5         | 2.18%   |
| 5.15.13 | 5         | 2.18%   |
| 5.15.12 | 5         | 2.18%   |
| 5.13.9  | 5         | 2.18%   |
| 5.13.13 | 5         | 2.18%   |
| 5.11.16 | 5         | 2.18%   |
| 5.16.8  | 4         | 1.75%   |
| 5.16.2  | 4         | 1.75%   |
| 5.15.10 | 4         | 1.75%   |
| 5.12.13 | 4         | 1.75%   |
| 5.10.15 | 4         | 1.75%   |
| 5.10.1  | 4         | 1.75%   |
| 5.9.10  | 3         | 1.31%   |
| 5.9.1   | 3         | 1.31%   |
| 5.16.10 | 3         | 1.31%   |
| 5.16.0  | 3         | 1.31%   |
| 5.15.5  | 3         | 1.31%   |
| 5.14.6  | 3         | 1.31%   |
| 5.14.15 | 3         | 1.31%   |
| 5.14.12 | 3         | 1.31%   |
| 5.12.9  | 3         | 1.31%   |
| 5.12.12 | 3         | 1.31%   |
| 5.11.6  | 3         | 1.31%   |
| 5.10.8  | 3         | 1.31%   |
| 5.10.2  | 3         | 1.31%   |
| 5.10.10 | 3         | 1.31%   |
| 5.9.8   | 2         | 0.87%   |
| 5.9.2   | 2         | 0.87%   |
| 5.9.11  | 2         | 0.87%   |
| 5.8.14  | 2         | 0.87%   |
| 5.16.9  | 2         | 0.87%   |
| 5.16.1  | 2         | 0.87%   |
| 5.15.4  | 2         | 0.87%   |
| 5.15.11 | 2         | 0.87%   |
| 5.14.9  | 2         | 0.87%   |
| 5.14.5  | 2         | 0.87%   |
| 5.14.11 | 2         | 0.87%   |
| 5.13.5  | 2         | 0.87%   |
| 5.13.4  | 2         | 0.87%   |
| 5.13.19 | 2         | 0.87%   |
| 5.13.12 | 2         | 0.87%   |
| 5.12.7  | 2         | 0.87%   |
| 5.12.4  | 2         | 0.87%   |
| 5.12.2  | 2         | 0.87%   |
| 5.12.15 | 2         | 0.87%   |
| 5.12.14 | 2         | 0.87%   |
| 5.11.0  | 2         | 0.87%   |
| 5.10.7  | 2         | 0.87%   |
| 5.10.12 | 2         | 0.87%   |
| 5.9.9   | 1         | 0.44%   |
| 5.9.6   | 1         | 0.44%   |
| 5.9.4   | 1         | 0.44%   |
| 5.9.14  | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 41        | 18.81%  |
| 5.10    | 36        | 16.51%  |
| 5.16    | 30        | 13.76%  |
| 5.14    | 24        | 11.01%  |
| 5.12    | 23        | 10.55%  |
| 5.11    | 23        | 10.55%  |
| 5.13    | 21        | 9.63%   |
| 5.9     | 13        | 5.96%   |
| 5.8     | 5         | 2.29%   |
| 5.6     | 1         | 0.46%   |
| 5.4     | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 202       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 121       | 59.02%  |
| KDE               | 34        | 16.59%  |
| GNOME             | 28        | 13.66%  |
| XFCE              | 9         | 4.39%   |
| X-Cinnamon        | 2         | 0.98%   |
| sway              | 2         | 0.98%   |
| i3                | 2         | 0.98%   |
| Deepin            | 2         | 0.98%   |
| Yaru:ubuntu:GNOME | 1         | 0.49%   |
| MATE              | 1         | 0.49%   |
| LXQt              | 1         | 0.49%   |
| Budgie            | 1         | 0.49%   |
| Unknown           | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 194       | 95.57%  |
| Wayland | 7         | 3.45%   |
| Tty     | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 101       | 49.75%  |
| Unknown | 73        | 35.96%  |
| LightDM | 15        | 7.39%   |
| GDM     | 13        | 6.4%    |
| GREETD  | 1         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 98        | 48.04%  |
| en_GB   | 23        | 11.27%  |
| de_DE   | 15        | 7.35%   |
| en_IN   | 11        | 5.39%   |
| it_IT   | 7         | 3.43%   |
| es_ES   | 5         | 2.45%   |
| ru_RU   | 4         | 1.96%   |
| pt_BR   | 4         | 1.96%   |
| nl_NL   | 3         | 1.47%   |
| es_MX   | 3         | 1.47%   |
| en_AU   | 3         | 1.47%   |
| sv_SE   | 2         | 0.98%   |
| pl_PL   | 2         | 0.98%   |
| fr_FR   | 2         | 0.98%   |
| fr_BE   | 2         | 0.98%   |
| fi_FI   | 2         | 0.98%   |
| es_VE   | 2         | 0.98%   |
| es_CO   | 2         | 0.98%   |
| en_ZA   | 2         | 0.98%   |
| en_CA   | 2         | 0.98%   |
| tr_TR   | 1         | 0.49%   |
| sk_SK   | 1         | 0.49%   |
| nb_NO   | 1         | 0.49%   |
| ko_KR   | 1         | 0.49%   |
| iu_CA   | 1         | 0.49%   |
| es_AR   | 1         | 0.49%   |
| el_GR   | 1         | 0.49%   |
| de_AT   | 1         | 0.49%   |
| da_DK   | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 132       | 65.02%  |
| BIOS | 71        | 34.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 199       | 98.51%  |
| Ext4  | 2         | 0.99%   |
| F2fs  | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 121       | 59.61%  |
| Unknown | 69        | 33.99%  |
| MBR     | 13        | 6.4%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 182       | 88.78%  |
| Yes       | 23        | 11.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 136       | 67%     |
| Yes       | 67        | 33%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 35        | 17.33%  |
| Lenovo              | 33        | 16.34%  |
| Hewlett-Packard     | 28        | 13.86%  |
| Dell                | 21        | 10.4%   |
| MSI                 | 16        | 7.92%   |
| Gigabyte Technology | 15        | 7.43%   |
| Acer                | 14        | 6.93%   |
| ASRock              | 8         | 3.96%   |
| Notebook            | 3         | 1.49%   |
| Medion              | 3         | 1.49%   |
| Apple               | 3         | 1.49%   |
| Samsung Electronics | 2         | 0.99%   |
| Razer               | 2         | 0.99%   |
| Pegatron            | 2         | 0.99%   |
| Fujitsu             | 2         | 0.99%   |
| Alienware           | 2         | 0.99%   |
| Unknown             | 2         | 0.99%   |
| Toshiba             | 1         | 0.5%    |
| Sony                | 1         | 0.5%    |
| PC Specialist       | 1         | 0.5%    |
| Panasonic           | 1         | 0.5%    |
| OEM                 | 1         | 0.5%    |
| HONOR               | 1         | 0.5%    |
| GPU Company         | 1         | 0.5%    |
| Google              | 1         | 0.5%    |
| Fujitsu Siemens     | 1         | 0.5%    |
| Chuwi               | 1         | 0.5%    |
| Biostar             | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 1.98%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 3         | 1.49%   |
| ASUS TUF GAMING X570-PLUS                  | 3         | 1.49%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 0.99%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.99%   |
| Gigabyte AB350-Gaming 3                    | 2         | 0.99%   |
| Dell Inspiron 3668                         | 2         | 0.99%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.99%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.99%   |
| Acer Nitro AN515-44                        | 2         | 0.99%   |
| Toshiba Satellite C55-A                    | 1         | 0.5%    |
| Sony VPCSB1C5E                             | 1         | 0.5%    |
| Samsung 550XCJ/550XCR                      | 1         | 0.5%    |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.5%    |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.5%    |
| Razer Blade                                | 1         | 0.5%    |
| Pegatron p7-1030                           | 1         | 0.5%    |
| Pegatron h9-1301es                         | 1         | 0.5%    |
| PC Specialist GK5NPFO                      | 1         | 0.5%    |
| Panasonic CF-191HYAX1M                     | 1         | 0.5%    |
| Notebook W54_W550SU2                       | 1         | 0.5%    |
| Notebook P7xxDM2(-G)                       | 1         | 0.5%    |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 0.5%    |
| MSI MS-7C91                                | 1         | 0.5%    |
| MSI MS-7C83                                | 1         | 0.5%    |
| MSI MS-7C52                                | 1         | 0.5%    |
| MSI MS-7C09                                | 1         | 0.5%    |
| MSI MS-7B98                                | 1         | 0.5%    |
| MSI MS-7B09                                | 1         | 0.5%    |
| MSI MS-7A78                                | 1         | 0.5%    |
| MSI MS-7A39                                | 1         | 0.5%    |
| MSI MS-7A32                                | 1         | 0.5%    |
| MSI MS-7818                                | 1         | 0.5%    |
| MSI MS-7816                                | 1         | 0.5%    |
| MSI MS-7758                                | 1         | 0.5%    |
| MSI GP75 Leopard 9SD                       | 1         | 0.5%    |
| MSI GF63 Thin 9SC                          | 1         | 0.5%    |
| MSI GE72VR 6RF                             | 1         | 0.5%    |
| MSI A320M-HDV R4.0                         | 1         | 0.5%    |
| Medion P861X                               | 1         | 0.5%    |
| Medion E7419 MD60025                       | 1         | 0.5%    |
| Medion Akoya P5238 F/C395                  | 1         | 0.5%    |
| Lenovo Yoga Slim 7 14ARE05 82A2            | 1         | 0.5%    |
| Lenovo ThinkStation S20 4105O1U            | 1         | 0.5%    |
| Lenovo ThinkPad T530 24296KG               | 1         | 0.5%    |
| Lenovo ThinkPad T510 4384WB4               | 1         | 0.5%    |
| Lenovo ThinkPad T470s 20HGS0B900           | 1         | 0.5%    |
| Lenovo ThinkPad T470 20HD000RUS            | 1         | 0.5%    |
| Lenovo ThinkPad T440p 20AWS58F00           | 1         | 0.5%    |
| Lenovo ThinkPad T440p 20AWS4RC00           | 1         | 0.5%    |
| Lenovo ThinkPad T14 Gen 1 20UDS00N00       | 1         | 0.5%    |
| Lenovo ThinkPad P1 20MDS00P00              | 1         | 0.5%    |
| Lenovo ThinkCentre M93p 10A90048US         | 1         | 0.5%    |
| Lenovo ThinkCentre M93p 10A90016US         | 1         | 0.5%    |
| Lenovo ThinkCentre M91p 7033CG1            | 1         | 0.5%    |
| Lenovo ThinkBook 14-IIL 20SL               | 1         | 0.5%    |
| Lenovo Legion S7 15ACH6 82K8               | 1         | 0.5%    |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 1         | 0.5%    |
| Lenovo Legion 5 15IMH05H 81Y6              | 1         | 0.5%    |
| Lenovo LEGION 5 15IMH05 82AU               | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 11        | 5.45%   |
| Lenovo ThinkPad        | 10        | 4.95%   |
| Lenovo IdeaPad         | 10        | 4.95%   |
| HP Pavilion            | 9         | 4.46%   |
| ASUS ROG               | 7         | 3.47%   |
| Acer Aspire            | 7         | 3.47%   |
| ASUS PRIME             | 6         | 2.97%   |
| ASUS TUF               | 5         | 2.48%   |
| Lenovo Legion          | 4         | 1.98%   |
| Dell XPS               | 4         | 1.98%   |
| Dell Latitude          | 4         | 1.98%   |
| Acer Nitro             | 4         | 1.98%   |
| Unknown                | 4         | 1.98%   |
| Lenovo ThinkCentre     | 3         | 1.49%   |
| HP OMEN                | 3         | 1.49%   |
| HP Laptop              | 3         | 1.49%   |
| Razer Blade            | 2         | 0.99%   |
| HP EliteBook           | 2         | 0.99%   |
| Gigabyte X570          | 2         | 0.99%   |
| Gigabyte B450          | 2         | 0.99%   |
| Gigabyte AB350-Gaming  | 2         | 0.99%   |
| ASUS ASUS              | 2         | 0.99%   |
| ASRock X470            | 2         | 0.99%   |
| Toshiba Satellite      | 1         | 0.5%    |
| Sony VPCSB1C5E         | 1         | 0.5%    |
| Samsung 550XCJ         | 1         | 0.5%    |
| Samsung 300V3A         | 1         | 0.5%    |
| Pegatron p7-1030       | 1         | 0.5%    |
| Pegatron h9-1301es     | 1         | 0.5%    |
| PC Specialist GK5NPFO  | 1         | 0.5%    |
| Panasonic CF-191HYAX1M | 1         | 0.5%    |
| Notebook W54           | 1         | 0.5%    |
| Notebook P7xxDM2(-G)   | 1         | 0.5%    |
| Notebook N85           | 1         | 0.5%    |
| MSI MS-7C91            | 1         | 0.5%    |
| MSI MS-7C83            | 1         | 0.5%    |
| MSI MS-7C52            | 1         | 0.5%    |
| MSI MS-7C09            | 1         | 0.5%    |
| MSI MS-7B98            | 1         | 0.5%    |
| MSI MS-7B09            | 1         | 0.5%    |
| MSI MS-7A78            | 1         | 0.5%    |
| MSI MS-7A39            | 1         | 0.5%    |
| MSI MS-7A32            | 1         | 0.5%    |
| MSI MS-7818            | 1         | 0.5%    |
| MSI MS-7816            | 1         | 0.5%    |
| MSI MS-7758            | 1         | 0.5%    |
| MSI GP75               | 1         | 0.5%    |
| MSI GF63               | 1         | 0.5%    |
| MSI GE72VR             | 1         | 0.5%    |
| MSI A320M-HDV          | 1         | 0.5%    |
| Medion P861X           | 1         | 0.5%    |
| Medion E7419           | 1         | 0.5%    |
| Medion Akoya           | 1         | 0.5%    |
| Lenovo Yoga            | 1         | 0.5%    |
| Lenovo ThinkStation    | 1         | 0.5%    |
| Lenovo ThinkBook       | 1         | 0.5%    |
| Lenovo K450e           | 1         | 0.5%    |
| Lenovo G510            | 1         | 0.5%    |
| HONOR HLYL-WXX9        | 1         | 0.5%    |
| HP Spectre             | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 34        | 16.83%  |
| 2019 | 27        | 13.37%  |
| 2018 | 22        | 10.89%  |
| 2017 | 22        | 10.89%  |
| 2021 | 20        | 9.9%    |
| 2013 | 15        | 7.43%   |
| 2016 | 13        | 6.44%   |
| 2012 | 13        | 6.44%   |
| 2014 | 11        | 5.45%   |
| 2011 | 9         | 4.46%   |
| 2010 | 7         | 3.47%   |
| 2015 | 3         | 1.49%   |
| 2009 | 3         | 1.49%   |
| 2007 | 2         | 0.99%   |
| 2008 | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 109       | 53.96%  |
| Desktop     | 84        | 41.58%  |
| Convertible | 4         | 1.98%   |
| All in one  | 4         | 1.98%   |
| Mini pc     | 1         | 0.5%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 202       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 201       | 99.5%   |
| Yes  | 1         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 55        | 27.09%  |
| 8.01-16.0   | 47        | 23.15%  |
| 4.01-8.0    | 45        | 22.17%  |
| 32.01-64.0  | 30        | 14.78%  |
| 3.01-4.0    | 13        | 6.4%    |
| 24.01-32.0  | 9         | 4.43%   |
| 64.01-256.0 | 3         | 1.48%   |
| 2.01-3.0    | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 73        | 34.11%  |
| 3.01-4.0   | 52        | 24.3%   |
| 2.01-3.0   | 46        | 21.5%   |
| 8.01-16.0  | 26        | 12.15%  |
| 1.01-2.0   | 13        | 6.07%   |
| 16.01-24.0 | 3         | 1.4%    |
| 0.51-1.0   | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 85        | 40.87%  |
| 2      | 66        | 31.73%  |
| 3      | 29        | 13.94%  |
| 4      | 15        | 7.21%   |
| 5      | 7         | 3.37%   |
| 9      | 3         | 1.44%   |
| 6      | 3         | 1.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 69.76%  |
| Yes       | 62        | 30.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 86.63%  |
| No        | 27        | 13.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 80%     |
| No        | 41        | 20%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 71.08%  |
| No        | 59        | 28.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 61        | 30.05%  |
| Germany      | 21        | 10.34%  |
| UK           | 14        | 6.9%    |
| Italy        | 11        | 5.42%   |
| India        | 11        | 5.42%   |
| Spain        | 5         | 2.46%   |
| Russia       | 5         | 2.46%   |
| Romania      | 5         | 2.46%   |
| Canada       | 5         | 2.46%   |
| Brazil       | 5         | 2.46%   |
| Sweden       | 4         | 1.97%   |
| Poland       | 4         | 1.97%   |
| Netherlands  | 4         | 1.97%   |
| Mexico       | 4         | 1.97%   |
| France       | 4         | 1.97%   |
| Finland      | 3         | 1.48%   |
| Belgium      | 3         | 1.48%   |
| Australia    | 3         | 1.48%   |
| Venezuela    | 2         | 0.99%   |
| South Africa | 2         | 0.99%   |
| Puerto Rico  | 2         | 0.99%   |
| Colombia     | 2         | 0.99%   |
| Turkey       | 1         | 0.49%   |
| Switzerland  | 1         | 0.49%   |
| South Korea  | 1         | 0.49%   |
| Slovakia     | 1         | 0.49%   |
| Singapore    | 1         | 0.49%   |
| Serbia       | 1         | 0.49%   |
| Philippines  | 1         | 0.49%   |
| Norway       | 1         | 0.49%   |
| Luxembourg   | 1         | 0.49%   |
| Lithuania    | 1         | 0.49%   |
| Latvia       | 1         | 0.49%   |
| Kuwait       | 1         | 0.49%   |
| Kenya        | 1         | 0.49%   |
| Iceland      | 1         | 0.49%   |
| Hungary      | 1         | 0.49%   |
| Greece       | 1         | 0.49%   |
| Denmark      | 1         | 0.49%   |
| Czechia      | 1         | 0.49%   |
| China        | 1         | 0.49%   |
| Chile        | 1         | 0.49%   |
| Bahrain      | 1         | 0.49%   |
| Austria      | 1         | 0.49%   |
| Argentina    | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| London                   | 4         | 1.9%    |
| Sydney                   | 2         | 0.95%   |
| San Jose                 | 2         | 0.95%   |
| Puebla City              | 2         | 0.95%   |
| Oklahoma City            | 2         | 0.95%   |
| Milan                    | 2         | 0.95%   |
| Kingsport                | 2         | 0.95%   |
| Helsinki                 | 2         | 0.95%   |
| Groningen                | 2         | 0.95%   |
| Chicago                  | 2         | 0.95%   |
| Cape Town                | 2         | 0.95%   |
| Calenzano                | 2         | 0.95%   |
| Bryansk                  | 2         | 0.95%   |
| Berlin                   | 2         | 0.95%   |
| Winston-Salem            | 1         | 0.48%   |
| Windermere               | 1         | 0.48%   |
| West Des Moines          | 1         | 0.48%   |
| Welwyn Garden City       | 1         | 0.48%   |
| Warsaw                   | 1         | 0.48%   |
| Vufflens-la-Ville        | 1         | 0.48%   |
| Volzhskiy                | 1         | 0.48%   |
| Volgograd                | 1         | 0.48%   |
| Viganello                | 1         | 0.48%   |
| Vienna                   | 1         | 0.48%   |
| Valenzano                | 1         | 0.48%   |
| Valence                  | 1         | 0.48%   |
| Turku                    | 1         | 0.48%   |
| Turin                    | 1         | 0.48%   |
| Tucson                   | 1         | 0.48%   |
| Toronto                  | 1         | 0.48%   |
| Toms River               | 1         | 0.48%   |
| TimiИ™oara            | 1         | 0.48%   |
| TimiÈ™oara            | 1         | 0.48%   |
| Tekoa                    | 1         | 0.48%   |
| Tampa                    | 1         | 0.48%   |
| Stuttgart                | 1         | 0.48%   |
| Stockton-on-Tees         | 1         | 0.48%   |
| Stockholm                | 1         | 0.48%   |
| Stavropol                | 1         | 0.48%   |
| St Louis                 | 1         | 0.48%   |
| Spring Hill              | 1         | 0.48%   |
| Spitalfields             | 1         | 0.48%   |
| Southampton              | 1         | 0.48%   |
| Singapore                | 1         | 0.48%   |
| Sighetu MarmaÅ£iei     | 1         | 0.48%   |
| Shreveport               | 1         | 0.48%   |
| Seattle                  | 1         | 0.48%   |
| Satu Mare                | 1         | 0.48%   |
| Sarasota                 | 1         | 0.48%   |
| Santa Cruz de Tenerife   | 1         | 0.48%   |
| Santa Clara              | 1         | 0.48%   |
| San Juan                 | 1         | 0.48%   |
| San Francisco            | 1         | 0.48%   |
| Salto da Divisa          | 1         | 0.48%   |
| Saint-Maur-des-FossÃ©s | 1         | 0.48%   |
| Riga                     | 1         | 0.48%   |
| Reno                     | 1         | 0.48%   |
| Regina                   | 1         | 0.48%   |
| Qalali                   | 1         | 0.48%   |
| Pune                     | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 64        | 114    | 17.11%  |
| Seagate                   | 57        | 78     | 15.24%  |
| WDC                       | 54        | 67     | 14.44%  |
| Toshiba                   | 24        | 28     | 6.42%   |
| Crucial                   | 18        | 25     | 4.81%   |
| SanDisk                   | 17        | 22     | 4.55%   |
| Kingston                  | 16        | 22     | 4.28%   |
| SK Hynix                  | 13        | 14     | 3.48%   |
| Unknown                   | 10        | 10     | 2.67%   |
| HGST                      | 9         | 9      | 2.41%   |
| Phison                    | 8         | 9      | 2.14%   |
| Intel                     | 8         | 10     | 2.14%   |
| Hitachi                   | 7         | 7      | 1.87%   |
| SPCC                      | 5         | 5      | 1.34%   |
| A-DATA Technology         | 5         | 8      | 1.34%   |
| Micron Technology         | 4         | 4      | 1.07%   |
| Corsair                   | 4         | 7      | 1.07%   |
| China                     | 4         | 6      | 1.07%   |
| XPG                       | 3         | 4      | 0.8%    |
| PNY                       | 3         | 3      | 0.8%    |
| KIOXIA                    | 3         | 4      | 0.8%    |
| Union Memory (Shenzhen)   | 2         | 2      | 0.53%   |
| Transcend                 | 2         | 2      | 0.53%   |
| Silicon Motion            | 2         | 2      | 0.53%   |
| Mushkin                   | 2         | 2      | 0.53%   |
| Micron/Crucial Technology | 2         | 3      | 0.53%   |
| LITEONIT                  | 2         | 2      | 0.53%   |
| WDC WDS                   | 1         | 1      | 0.27%   |
| WD MediaMax               | 1         | 1      | 0.27%   |
| VisionTek                 | 1         | 2      | 0.27%   |
| USB30                     | 1         | 2      | 0.27%   |
| UMIS                      | 1         | 1      | 0.27%   |
| TO Exter                  | 1         | 1      | 0.27%   |
| SSSTC                     | 1         | 1      | 0.27%   |
| ShanDianZhe               | 1         | 1      | 0.27%   |
| SABRENT                   | 1         | 2      | 0.27%   |
| QUMO                      | 1         | 1      | 0.27%   |
| PNY CS90                  | 1         | 1      | 0.27%   |
| Phison Electronics        | 1         | 1      | 0.27%   |
| OCZ                       | 1         | 1      | 0.27%   |
| Netac                     | 1         | 1      | 0.27%   |
| LITEON                    | 1         | 1      | 0.27%   |
| Lenovo                    | 1         | 1      | 0.27%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.27%   |
| Intenso                   | 1         | 1      | 0.27%   |
| Inateck                   | 1         | 1      | 0.27%   |
| HS-SSD-E100               | 1         | 1      | 0.27%   |
| FORESEE                   | 1         | 1      | 0.27%   |
| EMTEC                     | 1         | 1      | 0.27%   |
| ASMT                      | 1         | 1      | 0.27%   |
| ASMedia                   | 1         | 2      | 0.27%   |
| Apple                     | 1         | 1      | 0.27%   |
| Unknown                   | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB             | 7         | 1.68%   |
| Seagate ST1000LM049-2GH172 1TB         | 5         | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 1.2%    |
| Samsung SSD 970 EVO Plus 500GB         | 5         | 1.2%    |
| Samsung SSD 850 EVO 250GB              | 5         | 1.2%    |
| Crucial CT1000MX500SSD1 1TB            | 5         | 1.2%    |
| Samsung SSD 860 EVO 500GB              | 4         | 0.96%   |
| Samsung SSD 860 EVO 1TB                | 4         | 0.96%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 0.96%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 0.72%   |
| Toshiba DT01ACA100 1TB                 | 3         | 0.72%   |
| Seagate ST2000DM008-2FR102 2TB         | 3         | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB         | 3         | 0.72%   |
| Seagate Portable 1TB                   | 3         | 0.72%   |
| SanDisk SSD PLUS 1000GB                | 3         | 0.72%   |
| Sandisk NVMe SSD Drive 500GB           | 3         | 0.72%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 0.72%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.72%   |
| XPG NVMe SSD Drive 512GB               | 2         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2         | 0.48%   |
| WDC WD20EARX-00PASB0 2TB               | 2         | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 0.48%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB   | 2         | 0.48%   |
| Unknown MMC Card  16GB                 | 2         | 0.48%   |
| Toshiba HDWD110 1TB                    | 2         | 0.48%   |
| SPCC Solid State Disk 512GB            | 2         | 0.48%   |
| SK Hynix SC311 SATA 256GB SSD          | 2         | 0.48%   |
| SK Hynix NVMe SSD Drive 512GB          | 2         | 0.48%   |
| Seagate ST4000DM004-2CV104 4TB         | 2         | 0.48%   |
| Seagate ST3320820AS 320GB              | 2         | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB         | 2         | 0.48%   |
| Seagate ST2000DL003-9VT166 2TB         | 2         | 0.48%   |
| Seagate ST1000LM014-1EJ164 1TB         | 2         | 0.48%   |
| Seagate Expansion+ 2TB                 | 2         | 0.48%   |
| Seagate Expansion Desk 8TB             | 2         | 0.48%   |
| Seagate Backup+ Hub BK 8TB             | 2         | 0.48%   |
| Sandisk NVMe SSD Drive 1TB             | 2         | 0.48%   |
| Samsung SSD 970 EVO Plus 2TB           | 2         | 0.48%   |
| Samsung SSD 970 EVO 250GB              | 2         | 0.48%   |
| Samsung SSD 870 QVO 1TB                | 2         | 0.48%   |
| Samsung SSD 870 EVO 500GB              | 2         | 0.48%   |
| Samsung SSD 850 EVO 500GB              | 2         | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.48%   |
| Samsung NVMe SSD Drive 250GB           | 2         | 0.48%   |
| Samsung MZYLF128HCHP-000L2 128GB SSD   | 2         | 0.48%   |
| Phison NVMe SSD Drive 2TB              | 2         | 0.48%   |
| Phison NVMe SSD Drive 256GB            | 2         | 0.48%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 2         | 0.48%   |
| KIOXIA NVMe SSD Drive 512GB            | 2         | 0.48%   |
| Kingston SV300S37A120G 120GB SSD       | 2         | 0.48%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 0.48%   |
| Intel SSDPEKNW010T8 1TB                | 2         | 0.48%   |
| HGST HTS725050A7E630 500GB             | 2         | 0.48%   |
| Crucial CT1000P1SSD8 1TB               | 2         | 0.48%   |
| Corsair Force MP300 960GB              | 2         | 0.48%   |
| XPG SPECTRIX S20G 1TB                  | 1         | 0.24%   |
| WDC WDS500G2X0C-00L350 500GB           | 1         | 0.24%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 73     | 40.6%   |
| WDC                 | 35        | 45     | 26.32%  |
| Toshiba             | 17        | 20     | 12.78%  |
| HGST                | 9         | 9      | 6.77%   |
| Hitachi             | 7         | 7      | 5.26%   |
| Samsung Electronics | 4         | 4      | 3.01%   |
| Unknown             | 1         | 1      | 0.75%   |
| SABRENT             | 1         | 2      | 0.75%   |
| Intenso             | 1         | 1      | 0.75%   |
| Inateck             | 1         | 1      | 0.75%   |
| ASMT                | 1         | 1      | 0.75%   |
| ASMedia             | 1         | 2      | 0.75%   |
| Apple               | 1         | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 47     | 27.73%  |
| Crucial             | 14        | 19     | 11.76%  |
| Kingston            | 13        | 19     | 10.92%  |
| SanDisk             | 10        | 14     | 8.4%    |
| WDC                 | 8         | 9      | 6.72%   |
| A-DATA Technology   | 5         | 8      | 4.2%    |
| SPCC                | 4         | 4      | 3.36%   |
| China               | 4         | 6      | 3.36%   |
| SK Hynix            | 3         | 3      | 2.52%   |
| Transcend           | 2         | 2      | 1.68%   |
| Toshiba             | 2         | 3      | 1.68%   |
| PNY                 | 2         | 2      | 1.68%   |
| Mushkin             | 2         | 2      | 1.68%   |
| LITEONIT            | 2         | 2      | 1.68%   |
| WDC WDS             | 1         | 1      | 0.84%   |
| VisionTek           | 1         | 2      | 0.84%   |
| USB30               | 1         | 2      | 0.84%   |
| Unknown             | 1         | 1      | 0.84%   |
| TO Exter            | 1         | 1      | 0.84%   |
| QUMO                | 1         | 1      | 0.84%   |
| PNY CS90            | 1         | 1      | 0.84%   |
| OCZ                 | 1         | 1      | 0.84%   |
| Netac               | 1         | 1      | 0.84%   |
| Micron Technology   | 1         | 1      | 0.84%   |
| LITEON              | 1         | 1      | 0.84%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.84%   |
| FORESEE             | 1         | 1      | 0.84%   |
| EMTEC               | 1         | 1      | 0.84%   |
| Corsair             | 1         | 1      | 0.84%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 104       | 167    | 32.91%  |
| SSD     | 97        | 157    | 30.7%   |
| NVMe    | 96        | 156    | 30.38%  |
| Unknown | 11        | 11     | 3.48%   |
| MMC     | 8         | 8      | 2.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 149       | 292    | 53.41%  |
| NVMe | 96        | 156    | 34.41%  |
| SAS  | 26        | 43     | 9.32%   |
| MMC  | 8         | 8      | 2.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 97        | 150    | 42.73%  |
| 0.51-1.0   | 80        | 103    | 35.24%  |
| 1.01-2.0   | 30        | 43     | 13.22%  |
| 4.01-10.0  | 7         | 10     | 3.08%   |
| 3.01-4.0   | 6         | 7      | 2.64%   |
| 2.01-3.0   | 6         | 10     | 2.64%   |
| 10.01-20.0 | 1         | 1      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 77        | 37.56%  |
| 1001-2000      | 44        | 21.46%  |
| 501-1000       | 30        | 14.63%  |
| 2001-3000      | 28        | 13.66%  |
| 251-500        | 13        | 6.34%   |
| Unknown        | 9         | 4.39%   |
| 101-250        | 2         | 0.98%   |
| 1-20           | 2         | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 23.36%  |
| 251-500        | 41        | 19.16%  |
| 1001-2000      | 33        | 15.42%  |
| 501-1000       | 29        | 13.55%  |
| 51-100         | 24        | 11.21%  |
| 2001-3000      | 12        | 5.61%   |
| More than 3000 | 10        | 4.67%   |
| Unknown        | 9         | 4.21%   |
| 21-50          | 3         | 1.4%    |
| 1-20           | 3         | 1.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60A0RT0 500GB          | 1         | 1      | 4.55%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 4.55%   |
| WDC WD30EZRX-00DC0B0 3TB              | 1         | 1      | 4.55%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 4.55%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 4.55%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 4.55%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 4.55%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 4.55%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 4.55%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 7      | 4.55%   |
| OCZ TRION100 480GB SSD                | 1         | 1      | 4.55%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 4.55%   |
| Kingston SH103S3240G 240GB SSD        | 1         | 1      | 4.55%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 4.55%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 4.55%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 4.55%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 4.55%   |
| HGST HTS541075A9E680 752GB            | 1         | 1      | 4.55%   |
| Crucial CT960M500SSD1 960GB           | 1         | 1      | 4.55%   |
| Apple HDD HTS545050A7E362 500GB       | 1         | 1      | 4.55%   |
| A-DATA Technology SU800 1TB SSD       | 1         | 1      | 4.55%   |

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
| Samsung Electronics | 1         | 7      | 4.55%   |
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
| NVMe | 1         | 7      | 4.55%   |

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
| Works    | 115       | 238    | 47.92%  |
| Detected | 103       | 233    | 42.92%  |
| Malfunc  | 22        | 28     | 9.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 122       | 41.78%  |
| AMD                            | 61        | 20.89%  |
| Samsung Electronics            | 33        | 11.3%   |
| Sandisk                        | 18        | 6.16%   |
| Phison Electronics             | 13        | 4.45%   |
| SK Hynix                       | 10        | 3.42%   |
| Micron/Crucial Technology      | 5         | 1.71%   |
| Union Memory (Shenzhen)        | 4         | 1.37%   |
| Toshiba America Info Systems   | 4         | 1.37%   |
| ASMedia Technology             | 4         | 1.37%   |
| Kingston Technology Company    | 3         | 1.03%   |
| Silicon Motion                 | 2         | 0.68%   |
| Micron Technology              | 2         | 0.68%   |
| KIOXIA                         | 2         | 0.68%   |
| JMicron Technology             | 2         | 0.68%   |
| ADATA Technology               | 2         | 0.68%   |
| Solid State Storage Technology | 1         | 0.34%   |
| Realtek Semiconductor          | 1         | 0.34%   |
| Nvidia                         | 1         | 0.34%   |
| Marvell Technology Group       | 1         | 0.34%   |
| Lenovo                         | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 48        | 14.37%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 26        | 7.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 4.49%   |
| AMD 400 Series Chipset SATA Controller                                         | 11        | 3.29%   |
| Phison E12 NVMe Controller                                                     | 10        | 2.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 2.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 2.69%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 8         | 2.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.5%    |
| Intel SSD 660P Series                                                          | 5         | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 1.5%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 5         | 1.5%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 4         | 1.2%    |
| SK Hynix BC501 NVMe Solid State Drive                                          | 4         | 1.2%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 1.2%    |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 1.2%    |
| SK Hynix Gold P31 SSD                                                          | 3         | 0.9%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 0.9%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 0.9%    |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.9%    |
| AMD X399 Series Chipset SATA Controller                                        | 3         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.6%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.6%    |
| SK Hynix BC511                                                                 | 2         | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.6%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.6%    |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.6%    |
| Phison NVMe Storage Controller                                                 | 2         | 0.6%    |
| Micron/Crucial NVMe Controller                                                 | 2         | 0.6%    |
| Micron Non-Volatile memory controller                                          | 2         | 0.6%    |
| KIOXIA Non-Volatile memory controller                                          | 2         | 0.6%    |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.6%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 0.6%    |
| Intel PROSet/Wireless WiFi Software extension                                  | 2         | 0.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.6%    |
| AMD FCH SATA Controller D                                                      | 2         | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 0.6%    |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.3%    |
| SK Hynix Non-Volatile memory controller                                        | 1         | 0.3%    |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.3%    |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 0.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 158       | 55.83%  |
| NVMe | 96        | 33.92%  |
| RAID | 17        | 6.01%   |
| IDE  | 12        | 4.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 127       | 62.87%  |
| AMD    | 75        | 37.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 2.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 2.48%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 2.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.98%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 1.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 1.49%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 1.49%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 1.49%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.49%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.99%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.99%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.99%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.99%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.99%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.99%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 2         | 0.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.99%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 2         | 0.99%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.99%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 0.99%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.99%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 0.99%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.99%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 0.99%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 0.99%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.99%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.99%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 2         | 0.99%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.99%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 0.99%   |
| Intel Xeon CPU W3550 @ 3.07GHz                | 1         | 0.5%    |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz           | 1         | 0.5%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.5%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.5%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.5%    |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.5%    |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.5%    |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.5%    |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 1         | 0.5%    |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.5%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.5%    |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.5%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.5%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.5%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.5%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.5%    |
| Intel Core i7-4770K CPU @ 3.50GHz             | 1         | 0.5%    |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.5%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.5%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.5%    |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.5%    |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 49        | 24.26%  |
| Intel Core i5           | 38        | 18.81%  |
| AMD Ryzen 7             | 24        | 11.88%  |
| AMD Ryzen 5             | 22        | 10.89%  |
| Intel Core i3           | 16        | 7.92%   |
| Other                   | 7         | 3.47%   |
| Intel Celeron           | 6         | 2.97%   |
| AMD Ryzen 9             | 5         | 2.48%   |
| AMD Ryzen 3             | 4         | 1.98%   |
| AMD Ryzen Threadripper  | 3         | 1.49%   |
| Intel Xeon              | 2         | 0.99%   |
| Intel Pentium Silver    | 2         | 0.99%   |
| Intel Pentium Dual-Core | 2         | 0.99%   |
| Intel Pentium           | 2         | 0.99%   |
| Intel Core 2 Duo        | 2         | 0.99%   |
| AMD Ryzen 7 PRO         | 2         | 0.99%   |
| AMD FX                  | 2         | 0.99%   |
| AMD A8                  | 2         | 0.99%   |
| AMD A4                  | 2         | 0.99%   |
| AMD A10                 | 2         | 0.99%   |
| Intel Core m3           | 1         | 0.5%    |
| Intel Core i9           | 1         | 0.5%    |
| Intel Core 2 Quad       | 1         | 0.5%    |
| AMD Turion              | 1         | 0.5%    |
| AMD Phenom II X6        | 1         | 0.5%    |
| AMD Phenom II X4        | 1         | 0.5%    |
| AMD Phenom II X2        | 1         | 0.5%    |
| AMD A6                  | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 77        | 38.12%  |
| 2      | 55        | 27.23%  |
| 6      | 35        | 17.33%  |
| 8      | 27        | 13.37%  |
| 12     | 4         | 1.98%   |
| 16     | 2         | 0.99%   |
| 24     | 1         | 0.5%    |
| 10     | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 202       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 158       | 78.22%  |
| 1      | 44        | 21.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 202       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 39.13%  |
| 0x306a9    | 10        | 4.83%   |
| 0x906ea    | 9         | 4.35%   |
| 0x306c3    | 9         | 4.35%   |
| 0x206a7    | 8         | 3.86%   |
| 0x906e9    | 6         | 2.9%    |
| 0x08701021 | 6         | 2.9%    |
| 0x0800820d | 5         | 2.42%   |
| 0x506e3    | 4         | 1.93%   |
| 0x0a50000c | 4         | 1.93%   |
| 0x08600103 | 4         | 1.93%   |
| 0x08108109 | 4         | 1.93%   |
| 0xa0652    | 3         | 1.45%   |
| 0x806e9    | 3         | 1.45%   |
| 0x08600104 | 3         | 1.45%   |
| 0x08108102 | 3         | 1.45%   |
| 0x806ec    | 2         | 0.97%   |
| 0x806ea    | 2         | 0.97%   |
| 0x806c1    | 2         | 0.97%   |
| 0x40651    | 2         | 0.97%   |
| 0x106e5    | 2         | 0.97%   |
| 0x1067a    | 2         | 0.97%   |
| 0x08600106 | 2         | 0.97%   |
| 0x08001137 | 2         | 0.97%   |
| 0x06006705 | 2         | 0.97%   |
| 0xa0660    | 1         | 0.48%   |
| 0xa0655    | 1         | 0.48%   |
| 0xa0653    | 1         | 0.48%   |
| 0x906ed    | 1         | 0.48%   |
| 0x906ec    | 1         | 0.48%   |
| 0x906eb    | 1         | 0.48%   |
| 0x706e5    | 1         | 0.48%   |
| 0x706a8    | 1         | 0.48%   |
| 0x706a1    | 1         | 0.48%   |
| 0x506c9    | 1         | 0.48%   |
| 0x406e3    | 1         | 0.48%   |
| 0x20655    | 1         | 0.48%   |
| 0x106a5    | 1         | 0.48%   |
| 0x10676    | 1         | 0.48%   |
| 0x0a50000b | 1         | 0.48%   |
| 0x0a201204 | 1         | 0.48%   |
| 0x0a201016 | 1         | 0.48%   |
| 0x08701013 | 1         | 0.48%   |
| 0x08608103 | 1         | 0.48%   |
| 0x08101016 | 1         | 0.48%   |
| 0x0810100b | 1         | 0.48%   |
| 0x08101007 | 1         | 0.48%   |
| 0x07030105 | 1         | 0.48%   |
| 0x0700010f | 1         | 0.48%   |
| 0x06003106 | 1         | 0.48%   |
| 0x06000852 | 1         | 0.48%   |
| 0x010000dc | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 39        | 19.31%  |
| Zen 2           | 24        | 11.88%  |
| Haswell         | 18        | 8.91%   |
| Zen+            | 17        | 8.42%   |
| IvyBridge       | 15        | 7.43%   |
| SandyBridge     | 12        | 5.94%   |
| CometLake       | 11        | 5.45%   |
| Zen 3           | 10        | 4.95%   |
| Skylake         | 9         | 4.46%   |
| Zen             | 8         | 3.96%   |
| Penryn          | 5         | 2.48%   |
| TigerLake       | 4         | 1.98%   |
| Puma            | 3         | 1.49%   |
| Piledriver      | 3         | 1.49%   |
| Nehalem         | 3         | 1.49%   |
| K10             | 3         | 1.49%   |
| Goldmont plus   | 3         | 1.49%   |
| Westmere        | 2         | 0.99%   |
| Steamroller     | 2         | 0.99%   |
| Silvermont      | 2         | 0.99%   |
| IceLake         | 2         | 0.99%   |
| Excavator       | 2         | 0.99%   |
| Unknown         | 2         | 0.99%   |
| K8 & K10 hybrid | 1         | 0.5%    |
| Jaguar          | 1         | 0.5%    |
| Goldmont        | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 97        | 37.45%  |
| Intel  | 91        | 35.14%  |
| AMD    | 71        | 27.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                  | 12        | 4.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10        | 3.73%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 9         | 3.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9         | 3.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 8         | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 2.61%   |
| Intel HD Graphics 630                                                       | 7         | 2.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6         | 2.24%   |
| AMD Cezanne                                                                 | 6         | 2.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 1.87%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 5         | 1.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 5         | 1.87%   |
| Intel HD Graphics 620                                                       | 5         | 1.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 4         | 1.49%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4         | 1.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 1.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 4         | 1.49%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 4         | 1.49%   |
| Nvidia TU117M                                                               | 3         | 1.12%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 3         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 3         | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.12%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 3         | 1.12%   |
| Intel UHD Graphics 620                                                      | 3         | 1.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 1.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3         | 1.12%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3         | 1.12%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2         | 0.75%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2         | 0.75%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2         | 0.75%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2         | 0.75%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2         | 0.75%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 0.75%   |
| Nvidia GK107GLM [Quadro K1000M]                                             | 2         | 0.75%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 0.75%   |
| Intel HD Graphics 530                                                       | 2         | 0.75%   |
| Intel HD Graphics 510                                                       | 2         | 0.75%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 2         | 0.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 0.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 0.75%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2         | 0.75%   |
| AMD Mullins [Radeon R3 Graphics]                                            | 2         | 0.75%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.37%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.37%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.37%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1         | 0.37%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.37%   |
| Nvidia GT218M [NVS 3100M]                                                   | 1         | 0.37%   |
| Nvidia GT215GLM [Quadro FX 1800M]                                           | 1         | 0.37%   |
| Nvidia Graphics Device                                                      | 1         | 0.37%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 51        | 25.25%  |
| 1 x AMD            | 48        | 23.76%  |
| 1 x Nvidia         | 46        | 22.77%  |
| Intel + Nvidia     | 30        | 14.85%  |
| AMD + Nvidia       | 17        | 8.42%   |
| Intel + AMD        | 4         | 1.98%   |
| 2 x Nvidia         | 2         | 0.99%   |
| 2 x AMD            | 2         | 0.99%   |
| Intel + 2 x Nvidia | 2         | 0.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 127       | 62.56%  |
| Proprietary | 76        | 37.44%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 105       | 50.97%  |
| 0.01-0.5   | 22        | 10.68%  |
| 1.01-2.0   | 21        | 10.19%  |
| 7.01-8.0   | 17        | 8.25%   |
| 3.01-4.0   | 16        | 7.77%   |
| 5.01-6.0   | 9         | 4.37%   |
| 0.51-1.0   | 9         | 4.37%   |
| 8.01-16.0  | 4         | 1.94%   |
| 2.01-3.0   | 2         | 0.97%   |
| 16.01-24.0 | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 11.98%  |
| Samsung Electronics     | 28        | 11.57%  |
| LG Display              | 21        | 8.68%   |
| BOE                     | 17        | 7.02%   |
| Dell                    | 15        | 6.2%    |
| Chimei Innolux          | 14        | 5.79%   |
| Goldstar                | 12        | 4.96%   |
| Acer                    | 12        | 4.96%   |
| Hewlett-Packard         | 10        | 4.13%   |
| AOC                     | 9         | 3.72%   |
| BenQ                    | 8         | 3.31%   |
| PANDA                   | 7         | 2.89%   |
| Unknown                 | 6         | 2.48%   |
| Sharp                   | 6         | 2.48%   |
| Lenovo                  | 5         | 2.07%   |
| Ancor Communications    | 5         | 2.07%   |
| ASUSTek Computer        | 4         | 1.65%   |
| Sony                    | 3         | 1.24%   |
| MSI                     | 3         | 1.24%   |
| Vizio                   | 2         | 0.83%   |
| Philips                 | 2         | 0.83%   |
| Mi                      | 2         | 0.83%   |
| Iiyama                  | 2         | 0.83%   |
| CSO                     | 2         | 0.83%   |
| Apple                   | 2         | 0.83%   |
| ONN                     | 1         | 0.41%   |
| MiTAC                   | 1         | 0.41%   |
| LG Electronics          | 1         | 0.41%   |
| Lenovo Group Limited    | 1         | 0.41%   |
| Insignia                | 1         | 0.41%   |
| InfoVision              | 1         | 0.41%   |
| HPN                     | 1         | 0.41%   |
| HKC                     | 1         | 0.41%   |
| Gigabyte Technology     | 1         | 0.41%   |
| G-Story                 | 1         | 0.41%   |
| Fujitsu Siemens         | 1         | 0.41%   |
| Eizo                    | 1         | 0.41%   |
| CPT                     | 1         | 0.41%   |
| Chi Mei Optoelectronics | 1         | 0.41%   |
| AOpen                   | 1         | 0.41%   |
| Alba                    | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 4         | 1.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3         | 1.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch   | 2         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.81%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 0.81%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                       | 2         | 0.81%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                | 2         | 0.81%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2         | 0.81%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.81%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch       | 2         | 0.81%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 2         | 0.81%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                  | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch         | 2         | 0.81%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2         | 0.81%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                     | 2         | 0.81%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2         | 0.81%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1         | 0.4%    |
| Vizio D28h-C1 VIZ0095 1360x768 607x345mm 27.5-inch                     | 1         | 0.4%    |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1         | 0.4%    |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1         | 0.4%    |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 0.4%    |
| Unknown LCD Monitor RJT HDMI                                           | 1         | 0.4%    |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1         | 0.4%    |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1         | 0.4%    |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.4%    |
| Sony TV SNY1802 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.4%    |
| Sony TV SNY0801 1360x768 1600x900mm 72.3-inch                          | 1         | 0.4%    |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch                | 1         | 0.4%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.4%    |
| Sharp LQ133T1JW17 SHP1409 2560x1440 294x165mm 13.3-inch                | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                | 1         | 0.4%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                | 1         | 0.4%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.4%    |
| Samsung Electronics U28E850 SAM0CCB 3840x2160 607x345mm 27.5-inch      | 1         | 0.4%    |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 1         | 0.4%    |
| Samsung Electronics T22B300 SAM092D 1920x1080 477x268mm 21.5-inch      | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM00BB 1280x1024 376x301mm 19.0-inch   | 1         | 0.4%    |
| Samsung Electronics S24E450 SAM0CA0 1920x1080 531x299mm 24.0-inch      | 1         | 0.4%    |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch      | 1         | 0.4%    |
| Samsung Electronics LU28R55 SAM1016 3840x2160 632x360mm 28.6-inch      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SyncMaster 3840x1080                   | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch   | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch   | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0FBE 3840x2160 950x540mm 43.0-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor C32R50x 3840x1080                      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor C32R50x                                | 1         | 0.4%    |
| Samsung Electronics LCD Monitor C27F390 3840x1080                      | 1         | 0.4%    |
| Samsung Electronics LCD Monitor C27F390 1920x1080                      | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 115       | 49.78%  |
| 1366x768 (WXGA)    | 22        | 9.52%   |
| 3840x2160 (4K)     | 17        | 7.36%   |
| 1600x900 (HD+)     | 12        | 5.19%   |
| 2560x1440 (QHD)    | 11        | 4.76%   |
| Unknown            | 8         | 3.46%   |
| 1680x1050 (WSXGA+) | 6         | 2.6%    |
| 3840x1080          | 5         | 2.16%   |
| 3440x1440          | 5         | 2.16%   |
| 2560x1080          | 4         | 1.73%   |
| 1440x900 (WXGA+)   | 4         | 1.73%   |
| 7680x2160          | 2         | 0.87%   |
| 2560x1600          | 2         | 0.87%   |
| 2256x1504          | 2         | 0.87%   |
| 1920x1200 (WUXGA)  | 2         | 0.87%   |
| 1360x768           | 2         | 0.87%   |
| 1280x800 (WXGA)    | 2         | 0.87%   |
| 1280x1024 (SXGA)   | 2         | 0.87%   |
| 4480x1440          | 1         | 0.43%   |
| 3840x2400          | 1         | 0.43%   |
| 3840x1200          | 1         | 0.43%   |
| 3200x1800 (QHD+)   | 1         | 0.43%   |
| 2160x1440          | 1         | 0.43%   |
| 2048x1152          | 1         | 0.43%   |
| 1680x945           | 1         | 0.43%   |
| 1600x1200          | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 69        | 29.74%  |
| 27      | 26        | 11.21%  |
| Unknown | 20        | 8.62%   |
| 23      | 15        | 6.47%   |
| 24      | 14        | 6.03%   |
| 14      | 14        | 6.03%   |
| 13      | 12        | 5.17%   |
| 17      | 9         | 3.88%   |
| 22      | 7         | 3.02%   |
| 34      | 6         | 2.59%   |
| 21      | 6         | 2.59%   |
| 19      | 6         | 2.59%   |
| 72      | 3         | 1.29%   |
| 49      | 3         | 1.29%   |
| 40      | 3         | 1.29%   |
| 31      | 3         | 1.29%   |
| 20      | 3         | 1.29%   |
| 18      | 3         | 1.29%   |
| 16      | 3         | 1.29%   |
| 28      | 2         | 0.86%   |
| 48      | 1         | 0.43%   |
| 43      | 1         | 0.43%   |
| 33      | 1         | 0.43%   |
| 25      | 1         | 0.43%   |
| 11      | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 91        | 39.91%  |
| 501-600     | 50        | 21.93%  |
| 401-500     | 23        | 10.09%  |
| Unknown     | 20        | 8.77%   |
| 351-400     | 10        | 4.39%   |
| 601-700     | 8         | 3.51%   |
| 201-300     | 8         | 3.51%   |
| 701-800     | 7         | 3.07%   |
| 1001-1500   | 4         | 1.75%   |
| 801-900     | 3         | 1.32%   |
| 1501-2000   | 3         | 1.32%   |
| 901-1000    | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 162       | 75.7%   |
| 16/10   | 19        | 8.88%   |
| Unknown | 18        | 8.41%   |
| 21/9    | 7         | 3.27%   |
| 3/2     | 3         | 1.4%    |
| 5/4     | 2         | 0.93%   |
| 32/9    | 2         | 0.93%   |
| 4/3     | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 30.13%  |
| 201-250        | 34        | 14.85%  |
| 301-350        | 26        | 11.35%  |
| 81-90          | 22        | 9.61%   |
| Unknown        | 20        | 8.73%   |
| 351-500        | 11        | 4.8%    |
| 151-200        | 10        | 4.37%   |
| 121-130        | 8         | 3.49%   |
| 251-300        | 6         | 2.62%   |
| 501-1000       | 6         | 2.62%   |
| More than 1000 | 5         | 2.18%   |
| 71-80          | 4         | 1.75%   |
| 141-150        | 4         | 1.75%   |
| 111-120        | 2         | 0.87%   |
| 51-60          | 1         | 0.44%   |
| 91-100         | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 71        | 32.42%  |
| 51-100        | 64        | 29.22%  |
| 101-120       | 44        | 20.09%  |
| Unknown       | 20        | 9.13%   |
| 161-240       | 10        | 4.57%   |
| More than 240 | 5         | 2.28%   |
| 1-50          | 5         | 2.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 149       | 73.04%  |
| 2     | 46        | 22.55%  |
| 3     | 7         | 3.43%   |
| 0     | 2         | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 120       | 37.5%   |
| Intel                             | 102       | 31.88%  |
| Qualcomm Atheros                  | 37        | 11.56%  |
| Broadcom                          | 14        | 4.38%   |
| Ralink Technology                 | 5         | 1.56%   |
| NetGear                           | 5         | 1.56%   |
| MediaTek                          | 4         | 1.25%   |
| TP-Link                           | 3         | 0.94%   |
| Samsung Electronics               | 3         | 0.94%   |
| Linksys                           | 3         | 0.94%   |
| Aquantia                          | 3         | 0.94%   |
| Ralink                            | 2         | 0.63%   |
| DisplayLink                       | 2         | 0.63%   |
| ASIX Electronics                  | 2         | 0.63%   |
| Xiaomi                            | 1         | 0.31%   |
| Wacom                             | 1         | 0.31%   |
| Qualcomm                          | 1         | 0.31%   |
| Nvidia                            | 1         | 0.31%   |
| Microsoft                         | 1         | 0.31%   |
| Lenovo                            | 1         | 0.31%   |
| InterBiometrics                   | 1         | 0.31%   |
| Holtek Semiconductor              | 1         | 0.31%   |
| Ericsson Business Mobile Networks | 1         | 0.31%   |
| Dell                              | 1         | 0.31%   |
| Broadcom Limited                  | 1         | 0.31%   |
| Belkin Components                 | 1         | 0.31%   |
| ASUSTek Computer                  | 1         | 0.31%   |
| Alteon Networks                   | 1         | 0.31%   |
| Accton Technology                 | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 88        | 23.66%  |
| Intel Wi-Fi 6 AX200                                                 | 17        | 4.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 11        | 2.96%   |
| Intel I211 Gigabit Network Connection                               | 11        | 2.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 8         | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 8         | 2.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 7         | 1.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 7         | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 7         | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 6         | 1.61%   |
| Intel Ethernet Controller I225-V                                    | 6         | 1.61%   |
| Intel Ethernet Connection I217-LM                                   | 6         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 6         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 6         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 6         | 1.61%   |
| Intel Wireless-AC 9260                                              | 5         | 1.34%   |
| Intel Wireless 3165                                                 | 5         | 1.34%   |
| Realtek RTL8125 2.5GbE Controller                                   | 4         | 1.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 4         | 1.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 4         | 1.08%   |
| Intel Wireless 8265 / 8275                                          | 4         | 1.08%   |
| Intel Wireless 7260                                                 | 4         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 3         | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3         | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 3         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 3         | 0.81%   |
| Intel Centrino Advanced-N 6200                                      | 3         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                            | 3         | 0.81%   |
| TP-Link TL WN823N RTL8192EU                                         | 2         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)         | 2         | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2         | 0.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 2         | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 2         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                           | 2         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 2         | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2         | 0.54%   |
| NetGear A6210                                                       | 2         | 0.54%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter       | 2         | 0.54%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2         | 0.54%   |
| Intel Wireless 8260                                                 | 2         | 0.54%   |
| Intel Wi-Fi 6 AX201                                                 | 2         | 0.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 2         | 0.54%   |
| Intel Ethernet Connection I219-LM                                   | 2         | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                               | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                | 2         | 0.54%   |
| Intel Centrino Ultimate-N 6300                                      | 2         | 0.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 0.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 2         | 0.54%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express              | 2         | 0.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 2         | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                       | 2         | 0.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1         | 0.27%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                            | 1         | 0.27%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1         | 0.27%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 1         | 0.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 1         | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 79        | 44.63%  |
| Realtek Semiconductor | 33        | 18.64%  |
| Qualcomm Atheros      | 28        | 15.82%  |
| Broadcom              | 10        | 5.65%   |
| Ralink Technology     | 5         | 2.82%   |
| NetGear               | 5         | 2.82%   |
| TP-Link               | 3         | 1.69%   |
| MEDIATEK              | 3         | 1.69%   |
| Linksys               | 3         | 1.69%   |
| Ralink                | 2         | 1.13%   |
| Wacom                 | 1         | 0.56%   |
| Microsoft             | 1         | 0.56%   |
| Dell                  | 1         | 0.56%   |
| Broadcom Limited      | 1         | 0.56%   |
| ASUSTek Computer      | 1         | 0.56%   |
| Accton Technology     | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 17        | 9.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 11        | 6.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 8         | 4.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 7         | 3.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 7         | 3.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 6         | 3.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 6         | 3.37%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 6         | 3.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 6         | 3.37%   |
| Intel Wireless-AC 9260                                                    | 5         | 2.81%   |
| Intel Wireless 3165                                                       | 5         | 2.81%   |
| Intel Wireless 8265 / 8275                                                | 4         | 2.25%   |
| Intel Wireless 7260                                                       | 4         | 2.25%   |
| Ralink RT2870/RT3070 Wireless Adapter                                     | 3         | 1.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 3         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 3         | 1.69%   |
| Intel Centrino Advanced-N 6200                                            | 3         | 1.69%   |
| TP-Link TL WN823N RTL8192EU                                               | 2         | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2         | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 2         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 2         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                          | 2         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                          | 2         | 1.12%   |
| NetGear A6210                                                             | 2         | 1.12%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter             | 2         | 1.12%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]       | 2         | 1.12%   |
| Intel Wireless 8260                                                       | 2         | 1.12%   |
| Intel Wi-Fi 6 AX201                                                       | 2         | 1.12%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 2         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                            | 2         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 2         | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                            | 2         | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                       | 2         | 1.12%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                  | 1         | 0.56%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                | 1         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                  | 1         | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.56%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                    | 1         | 0.56%   |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1         | 0.56%   |
| Realtek RTL8191SEvA Wireless LAN Controller                               | 1         | 0.56%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                                    | 1         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                       | 1         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                              | 1         | 0.56%   |
| Ralink Wireless Adapter Canyon CN-WF511                                   | 1         | 0.56%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                         | 1         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                           | 1         | 0.56%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1         | 0.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)            | 1         | 0.56%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                          | 1         | 0.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)   | 1         | 0.56%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                     | 1         | 0.56%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.56%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]               | 1         | 0.56%   |
| Microsoft Wireless XBox Controller Dongle                                 | 1         | 0.56%   |
| MediaTek WiFi                                                             | 1         | 0.56%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                         | 1         | 0.56%   |
| Intel Wireless 7265                                                       | 1         | 0.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection             | 1         | 0.56%   |
| Intel Gemini Lake PCH CNVi WiFi                                           | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 106       | 55.79%  |
| Intel                 | 46        | 24.21%  |
| Qualcomm Atheros      | 14        | 7.37%   |
| Broadcom              | 7         | 3.68%   |
| Samsung Electronics   | 3         | 1.58%   |
| Aquantia              | 3         | 1.58%   |
| DisplayLink           | 2         | 1.05%   |
| ASIX Electronics      | 2         | 1.05%   |
| Xiaomi                | 1         | 0.53%   |
| Qualcomm              | 1         | 0.53%   |
| Nvidia                | 1         | 0.53%   |
| MediaTek              | 1         | 0.53%   |
| Lenovo                | 1         | 0.53%   |
| Belkin Components     | 1         | 0.53%   |
| Alteon Networks       | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 46.07%  |
| Intel I211 Gigabit Network Connection                             | 11        | 5.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 4.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.66%   |
| Intel Ethernet Controller I225-V                                  | 6         | 3.14%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 2.09%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 2.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.57%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.57%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.05%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.05%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.05%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.52%   |
| Qualcomm 8920FT CD-ROM                                            | 1         | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.52%   |
| MediaTek Wiko U316AT                                              | 1         | 0.52%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.52%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.52%   |
| DisplayLink ThinkPad USB 3.0 Dock                                 | 1         | 0.52%   |
| DisplayLink Dell D1000 USB3.0 Dock                                | 1         | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.52%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 0.52%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1         | 0.52%   |
| Belkin Components F5D5050 100Mbps Ethernet                        | 1         | 0.52%   |
| Aquantia Ethernet controller                                      | 1         | 0.52%   |
| Alteon Networks Ethernet controller                               | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 175       | 51.32%  |
| WiFi     | 163       | 47.8%   |
| Modem    | 2         | 0.59%   |
| Unknown  | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 130       | 55.32%  |
| Ethernet | 104       | 44.26%  |
| Unknown  | 1         | 0.43%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 56.65%  |
| 1     | 78        | 38.42%  |
| 3     | 6         | 2.96%   |
| 0     | 3         | 1.48%   |
| 4     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 161       | 79.31%  |
| Yes  | 42        | 20.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 45.21%  |
| Realtek Semiconductor           | 21        | 14.38%  |
| Qualcomm Atheros Communications | 21        | 14.38%  |
| Cambridge Silicon Radio         | 7         | 4.79%   |
| IMC Networks                    | 6         | 4.11%   |
| Broadcom                        | 5         | 3.42%   |
| Lite-On Technology              | 4         | 2.74%   |
| ASUSTek Computer                | 3         | 2.05%   |
| Apple                           | 3         | 2.05%   |
| Qualcomm Atheros                | 2         | 1.37%   |
| Hewlett-Packard                 | 2         | 1.37%   |
| Foxconn / Hon Hai               | 2         | 1.37%   |
| Dell                            | 2         | 1.37%   |
| Realtek                         | 1         | 0.68%   |
| Dynex                           | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 18        | 12.33%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 17        | 11.64%  |
| Intel AX200 Bluetooth                                                               | 17        | 11.64%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 7.53%   |
| Intel AX201 Bluetooth                                                               | 10        | 6.85%   |
| Realtek Bluetooth Radio                                                             | 9         | 6.16%   |
| Intel Bluetooth wireless interface                                                  | 8         | 5.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 4.79%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 4.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 5         | 3.42%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 2.05%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.37%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.37%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.37%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.37%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.37%   |
| ASUS Bluetooth Radio                                                                | 2         | 1.37%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.68%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.68%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.68%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.68%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.68%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.68%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.68%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.68%   |
| Dell BCM20702A0                                                                     | 1         | 0.68%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.68%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.68%   |
| Broadcom BCM2045A0                                                                  | 1         | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 125       | 39.06%  |
| AMD                       | 83        | 25.94%  |
| Nvidia                    | 68        | 21.25%  |
| C-Media Electronics       | 7         | 2.19%   |
| Logitech                  | 6         | 1.88%   |
| Sony                      | 2         | 0.63%   |
| Sennheiser Communications | 2         | 0.63%   |
| RODE Microphones          | 2         | 0.63%   |
| JMTek                     | 2         | 0.63%   |
| Generalplus Technology    | 2         | 0.63%   |
| Creative Technology       | 2         | 0.63%   |
| Creative Labs             | 2         | 0.63%   |
| Yamaha                    | 1         | 0.31%   |
| Turtle Beach              | 1         | 0.31%   |
| Trust                     | 1         | 0.31%   |
| Texas Instruments         | 1         | 0.31%   |
| Tenx Technology           | 1         | 0.31%   |
| SteelSeries ApS           | 1         | 0.31%   |
| Plantronics               | 1         | 0.31%   |
| Phison Electronics        | 1         | 0.31%   |
| Kingston Technology       | 1         | 0.31%   |
| Huawei Technologies       | 1         | 0.31%   |
| Hewlett-Packard           | 1         | 0.31%   |
| GN Netcom                 | 1         | 0.31%   |
| Focusrite-Novation        | 1         | 0.31%   |
| EVGA                      | 1         | 0.31%   |
| DigiTech                  | 1         | 0.31%   |
| Corsair                   | 1         | 0.31%   |
| Blue Microphones          | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 32        | 8.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 16        | 4.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 3.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 3.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 2.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 11        | 2.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 2.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 2.1%    |
| Nvidia GP104 High Definition Audio Controller                              | 7         | 1.84%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.84%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.57%   |
| Nvidia GM204 High Definition Audio Controller                              | 6         | 1.57%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.57%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 1.57%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 1.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.31%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 1.31%   |
| Nvidia High Definition Audio Controller                                    | 4         | 1.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.05%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 4         | 1.05%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 4         | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.05%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 0.79%   |
| Nvidia Audio device                                                        | 3         | 0.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 0.79%   |
| Intel Comet Lake PCH-V cAVS                                                | 3         | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.79%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 0.79%   |
| C-Media Electronics SADES Hammer                                           | 3         | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.79%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 0.79%   |
| RODE Microphones RODE NT-USB                                               | 2         | 0.52%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2         | 0.52%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.52%   |
| Nvidia GF106 High Definition Audio Controller                              | 2         | 0.52%   |
| Nvidia GA102 High Definition Audio Controller                              | 2         | 0.52%   |
| Logitech G933 Wireless Headset Dongle                                      | 2         | 0.52%   |
| JMTek USB PnP Audio Device                                                 | 2         | 0.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.52%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 0.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.52%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.52%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 2         | 0.52%   |
| AMD High Definition Audio Controller                                       | 2         | 0.52%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.52%   |
| Yamaha Steinberg UR22mkII                                                  | 1         | 0.26%   |
| Turtle Beach Ear Force P11 Headset                                         | 1         | 0.26%   |
| Trust GXT 363 headset                                                      | 1         | 0.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 23.27%  |
| SK Hynix            | 26        | 16.35%  |
| Crucial             | 16        | 10.06%  |
| Micron Technology   | 13        | 8.18%   |
| G.Skill             | 11        | 6.92%   |
| Corsair             | 10        | 6.29%   |
| Kingston            | 8         | 5.03%   |
| Unknown             | 7         | 4.4%    |
| Patriot             | 6         | 3.77%   |
| Ramaxel Technology  | 5         | 3.14%   |
| A-DATA Technology   | 4         | 2.52%   |
| Team                | 3         | 1.89%   |
| Unknown (ABCD)      | 2         | 1.26%   |
| Smart               | 2         | 1.26%   |
| Nanya Technology    | 2         | 1.26%   |
| Transcend           | 1         | 0.63%   |
| TIMETEC             | 1         | 0.63%   |
| Elpida              | 1         | 0.63%   |
| CSX                 | 1         | 0.63%   |
| Avant               | 1         | 0.63%   |
| Apacer              | 1         | 0.63%   |
| 48spaces            | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 2.33%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.33%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 4         | 2.33%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 4         | 2.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s            | 3         | 1.74%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 3         | 1.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.74%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s            | 3         | 1.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.16%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 1.16%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.16%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s             | 2         | 1.16%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 1.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.16%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.16%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.16%   |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2667MT/s               | 2         | 1.16%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 2         | 1.16%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 2         | 1.16%   |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.16%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 1         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.58%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                             | 1         | 0.58%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s            | 1         | 0.58%   |
| Transcend RAM JM2666HSE-16G 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.58%   |
| TIMETEC RAM SD3-1866 8GB SODIMM DDR3 1866MT/s                    | 1         | 0.58%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s              | 1         | 0.58%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s               | 1         | 0.58%   |
| Team RAM TEAMGROUP-SD4-2133 8GB SODIMM DDR4 2133MT/s             | 1         | 0.58%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.58%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB DDR4 2667MT/s                   | 1         | 0.58%   |
| SK Hynix RAM Module 4GB Row Of Chips LPDDR3 1333MT/s             | 1         | 0.58%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.58%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.58%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s     | 1         | 0.58%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.58%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.58%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.58%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.58%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.58%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                        | 1         | 0.58%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.58%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                       | 1         | 0.58%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 0.58%   |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1600MT/s            | 1         | 0.58%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.58%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.58%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 89        | 66.42%  |
| DDR3    | 36        | 26.87%  |
| LPDDR4  | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| DDR2    | 2         | 1.49%   |
| LPDDR3  | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 63.24%  |
| DIMM         | 41        | 30.15%  |
| Row Of Chips | 8         | 5.88%   |
| Unknown      | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 78        | 51.66%  |
| 4096  | 40        | 26.49%  |
| 16384 | 25        | 16.56%  |
| 2048  | 5         | 3.31%   |
| 32768 | 2         | 1.32%   |
| 1024  | 1         | 0.66%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 33        | 21.71%  |
| 2667  | 32        | 21.05%  |
| 1600  | 27        | 17.76%  |
| 2400  | 15        | 9.87%   |
| 3600  | 11        | 7.24%   |
| 2133  | 4         | 2.63%   |
| 3466  | 3         | 1.97%   |
| 3266  | 3         | 1.97%   |
| 1334  | 3         | 1.97%   |
| 1333  | 3         | 1.97%   |
| 3866  | 2         | 1.32%   |
| 2666  | 2         | 1.32%   |
| 1866  | 2         | 1.32%   |
| 1800  | 2         | 1.32%   |
| 800   | 2         | 1.32%   |
| 4266  | 1         | 0.66%   |
| 4200  | 1         | 0.66%   |
| 3067  | 1         | 0.66%   |
| 2933  | 1         | 0.66%   |
| 2200  | 1         | 0.66%   |
| 1867  | 1         | 0.66%   |
| 1066  | 1         | 0.66%   |
| 667   | 1         | 0.66%   |

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
| Chicony Electronics                    | 32        | 24.81%  |
| IMC Networks                           | 12        | 9.3%    |
| Logitech                               | 11        | 8.53%   |
| Realtek Semiconductor                  | 10        | 7.75%   |
| Microdia                               | 10        | 7.75%   |
| Quanta                                 | 6         | 4.65%   |
| Microsoft                              | 6         | 4.65%   |
| Acer                                   | 6         | 4.65%   |
| Sunplus Innovation Technology          | 4         | 3.1%    |
| Apple                                  | 4         | 3.1%    |
| Syntek                                 | 3         | 2.33%   |
| Suyin                                  | 3         | 2.33%   |
| Lite-On Technology                     | 3         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.33%   |
| Silicon Motion                         | 2         | 1.55%   |
| Luxvisions Innotech Limited            | 2         | 1.55%   |
| Jieli Technology                       | 2         | 1.55%   |
| Z-Star Microelectronics                | 1         | 0.78%   |
| WaveRider Communications               | 1         | 0.78%   |
| Sonix Technology                       | 1         | 0.78%   |
| Samsung Electronics                    | 1         | 0.78%   |
| Razer USA                              | 1         | 0.78%   |
| MacroSilicon                           | 1         | 0.78%   |
| Lenovo                                 | 1         | 0.78%   |
| Importek                               | 1         | 0.78%   |
| Genesys Logic                          | 1         | 0.78%   |
| DJKANA1BIF866I                         | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 7         | 5.38%   |
| IMC Networks Integrated Camera                      | 6         | 4.62%   |
| Chicony Integrated Camera                           | 6         | 4.62%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 3.85%   |
| Chicony HD WebCam                                   | 5         | 3.85%   |
| Chicony HD User Facing                              | 4         | 3.08%   |
| Syntek Integrated Camera                            | 3         | 2.31%   |
| Lite-On HP Wide Vision HD Camera                    | 3         | 2.31%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.54%   |
| Quanta HP Wide Vision HD Camera                     | 2         | 1.54%   |
| Microsoft LifeCam HD-5000                           | 2         | 1.54%   |
| Microsoft LifeCam HD-3000                           | 2         | 1.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.54%   |
| Logitech Webcam C930e                               | 2         | 1.54%   |
| Logitech Webcam C270                                | 2         | 1.54%   |
| Logitech HD Webcam C910                             | 2         | 1.54%   |
| Jieli USB PHY 2.0                                   | 2         | 1.54%   |
| Chicony USB 2.0 Camera                              | 2         | 1.54%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.54%   |
| Chicony EasyCamera                                  | 2         | 1.54%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 1.54%   |
| Acer Integrated Camera                              | 2         | 1.54%   |
| Z-Star A4 TECH USB 2.0 Camera J                     | 1         | 0.77%   |
| WaveRider USB 2.0 Camera                            | 1         | 0.77%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.77%   |
| Suyin HP Integrated Webcam                          | 1         | 0.77%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.77%   |
| Sunplus MTD Camera                                  | 1         | 0.77%   |
| Sunplus Integrated Webcam                           | 1         | 0.77%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.77%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.77%   |
| Silicon Motion Web Camera                           | 1         | 0.77%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.77%   |
| Realtek USB Camera                                  | 1         | 0.77%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.77%   |
| Realtek Integrated Webcam                           | 1         | 0.77%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.77%   |
| Realtek HD WebCam                                   | 1         | 0.77%   |
| Realtek FULL HD 1080P Webcam                        | 1         | 0.77%   |
| Realtek FJ Camera                                   | 1         | 0.77%   |
| Realtek EasyCamera                                  | 1         | 0.77%   |
| Realtek Built-In Video Camera                       | 1         | 0.77%   |
| Realtek Acer 640 x 480 laptop camera                | 1         | 0.77%   |
| Razer USA Razer Kiyo Pro                            | 1         | 0.77%   |
| Quanta WEBCAM                                       | 1         | 0.77%   |
| Quanta HP True Vision HD Camera                     | 1         | 0.77%   |
| Quanta HD User Facing                               | 1         | 0.77%   |
| Quanta HD Camera                                    | 1         | 0.77%   |
| Microsoft Xbox NUI Camera                           | 1         | 0.77%   |
| Microsoft Modern Webcam                             | 1         | 0.77%   |
| Microdia Webcam Vitade AF                           | 1         | 0.77%   |
| Microdia PC Microscope camera                       | 1         | 0.77%   |
| Microdia HP Integrated Webcam                       | 1         | 0.77%   |
| MacroSilicon USB Video                              | 1         | 0.77%   |
| Logitech Webcam Pro 9000                            | 1         | 0.77%   |
| Logitech Webcam C925e                               | 1         | 0.77%   |
| Logitech HD Webcam C510                             | 1         | 0.77%   |
| Logitech HD Pro Webcam C920                         | 1         | 0.77%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 0.77%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 30%     |
| Synaptics                  | 6         | 30%     |
| Shenzhen Goodix Technology | 4         | 20%     |
| LighTuning Technology      | 2         | 10%     |
| AuthenTec                  | 2         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                   | 2         | 10%     |
| Shenzhen Goodix  FingerPrint Device               | 2         | 10%     |
| Unknown                                           | 2         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 5%      |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 5%      |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 5%      |
| Synaptics WBDI Device                             | 1         | 5%      |
| Synaptics  WBDI Fingerprint Reader - USB 052      | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5%      |
| Shenzhen Goodix Fingerprint Reader                | 1         | 5%      |
| Shenzhen Goodix FingerPrint                       | 1         | 5%      |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 5%      |
| AuthenTec AES2810                                 | 1         | 5%      |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 55.56%  |
| Upek        | 1         | 11.11%  |
| O2 Micro    | 1         | 11.11%  |
| Lenovo      | 1         | 11.11%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 22.22%  |
| Broadcom 5880                                                                | 2         | 22.22%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 100       | 48.78%  |
| 0     | 70        | 34.15%  |
| 2     | 28        | 13.66%  |
| 3     | 6         | 2.93%   |
| 4     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 116       | 65.17%  |
| Fingerprint reader       | 20        | 11.24%  |
| Graphics card            | 10        | 5.62%   |
| Net/wireless             | 9         | 5.06%   |
| Chipcard                 | 9         | 5.06%   |
| Net/ethernet             | 6         | 3.37%   |
| Camera                   | 3         | 1.69%   |
| Multimedia controller    | 2         | 1.12%   |
| Wireless                 | 1         | 0.56%   |
| Storage                  | 1         | 0.56%   |
| Bluetooth                | 1         | 0.56%   |

