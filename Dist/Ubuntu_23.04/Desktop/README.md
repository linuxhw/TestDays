Ubuntu 23.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

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

Total: 223

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Intel         | DP45SG AAE27733-404         | [7abba8629e](https://linux-hardware.org/?probe=7abba8629e) | Jun 10, 2023 |
| Intel         | DP45SG AAE27733-404         | [afaced265f](https://linux-hardware.org/?probe=afaced265f) | Jun 10, 2023 |
| HP            | 81B4                        | [2d7748536f](https://linux-hardware.org/?probe=2d7748536f) | Jun 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| HP            | 0B4Ch D                     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [4f69ba649a](https://linux-hardware.org/?probe=4f69ba649a) | Jun 09, 2023 |
| ASRock        | X670E Pro RS                | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| AZW           | Green G4 10                 | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| BESSTAR Te... | UM700                       | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| Dell          | 0HN7XN A01                  | [c44abee9e7](https://linux-hardware.org/?probe=c44abee9e7) | Jun 08, 2023 |
| ASUSTek       | WS Z390 PRO                 | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| ASUSTek       | B85M-E                      | [9ea0a82205](https://linux-hardware.org/?probe=9ea0a82205) | Jun 07, 2023 |
| Dell          | 0R6PCT A01                  | [e1623fbc8e](https://linux-hardware.org/?probe=e1623fbc8e) | Jun 07, 2023 |
| Dell          | 0RY007                      | [49c7cbbfde](https://linux-hardware.org/?probe=49c7cbbfde) | Jun 06, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [fe852e8a1d](https://linux-hardware.org/?probe=fe852e8a1d) | Jun 06, 2023 |
| Pegatron      | H81-M1                      | [2641e6773e](https://linux-hardware.org/?probe=2641e6773e) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [1c99e1316c](https://linux-hardware.org/?probe=1c99e1316c) | Jun 05, 2023 |
| MSI           | 990FXA GAMING               | [60fb09bf5e](https://linux-hardware.org/?probe=60fb09bf5e) | Jun 05, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [32da3735d9](https://linux-hardware.org/?probe=32da3735d9) | Jun 05, 2023 |
| ASUSTek       | Z170-K                      | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-V                | [d0fd3fd90a](https://linux-hardware.org/?probe=d0fd3fd90a) | Jun 04, 2023 |
| ASUSTek       | PRIME Z590-V                | [bc93ac1588](https://linux-hardware.org/?probe=bc93ac1588) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| ASUSTek       | H170-PRO                    | [b9fd75507c](https://linux-hardware.org/?probe=b9fd75507c) | Jun 04, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [82542c4daa](https://linux-hardware.org/?probe=82542c4daa) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [0c8afa948b](https://linux-hardware.org/?probe=0c8afa948b) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK               | [aaed1b39af](https://linux-hardware.org/?probe=aaed1b39af) | Jun 03, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| Intel         | X99 V102                    | [ed5a67e8a5](https://linux-hardware.org/?probe=ed5a67e8a5) | Jun 03, 2023 |
| MSI           | H97M-G43                    | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [8d783c6b00](https://linux-hardware.org/?probe=8d783c6b00) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [51868dd3c8](https://linux-hardware.org/?probe=51868dd3c8) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [44571410f0](https://linux-hardware.org/?probe=44571410f0) | Jun 03, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [d54d77b051](https://linux-hardware.org/?probe=d54d77b051) | Jun 03, 2023 |
| HP            | 3047h                       | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| MSI           | B250 GAMING PRO CARBON      | [ef7acf6baa](https://linux-hardware.org/?probe=ef7acf6baa) | Jun 03, 2023 |
| Dell          | 0M6C7G A00                  | [93bdbbdafb](https://linux-hardware.org/?probe=93bdbbdafb) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [4e17d7c6e8](https://linux-hardware.org/?probe=4e17d7c6e8) | Jun 03, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [965de576c7](https://linux-hardware.org/?probe=965de576c7) | Jun 03, 2023 |
| Dell          | 0RY007                      | [f3028ff55d](https://linux-hardware.org/?probe=f3028ff55d) | Jun 02, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [8aab7c6536](https://linux-hardware.org/?probe=8aab7c6536) | Jun 01, 2023 |
| HP            | 83E2                        | [eaf5f90360](https://linux-hardware.org/?probe=eaf5f90360) | Jun 01, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [3b9639141c](https://linux-hardware.org/?probe=3b9639141c) | May 31, 2023 |
| Dell          | 0RY007                      | [b726df555b](https://linux-hardware.org/?probe=b726df555b) | May 31, 2023 |
| Dell          | 0RY007                      | [32e931c79b](https://linux-hardware.org/?probe=32e931c79b) | May 31, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [953ee1ef05](https://linux-hardware.org/?probe=953ee1ef05) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| ASRock        | Z77 Extreme3                | [e45b1707bd](https://linux-hardware.org/?probe=e45b1707bd) | May 31, 2023 |
| ZOTAC         | Unknown                     | [0626de1b2a](https://linux-hardware.org/?probe=0626de1b2a) | May 31, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2703e7856e](https://linux-hardware.org/?probe=2703e7856e) | May 30, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [45e5adbb22](https://linux-hardware.org/?probe=45e5adbb22) | May 30, 2023 |
| Intel         | DH61BF AAG81311-102         | [22123492ab](https://linux-hardware.org/?probe=22123492ab) | May 30, 2023 |
| ASRock        | Z77 Extreme3                | [67c96085bf](https://linux-hardware.org/?probe=67c96085bf) | May 30, 2023 |
| ASUSTek       | ROG STRIX Z790-H GAMING ... | [11432ddeb6](https://linux-hardware.org/?probe=11432ddeb6) | May 29, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| Gigabyte      | B360M D2V                   | [7fce8e04b2](https://linux-hardware.org/?probe=7fce8e04b2) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [7e895c167b](https://linux-hardware.org/?probe=7e895c167b) | May 27, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [526503fef7](https://linux-hardware.org/?probe=526503fef7) | May 27, 2023 |
| AAEON         | UP-CHCR1 V0.4               | [b77201e825](https://linux-hardware.org/?probe=b77201e825) | May 26, 2023 |
| Dell          | 0MGK50 A02                  | [4572d76da5](https://linux-hardware.org/?probe=4572d76da5) | May 26, 2023 |
| Gigabyte      | P43-ES3G                    | [9683a94030](https://linux-hardware.org/?probe=9683a94030) | May 26, 2023 |
| Dell          | 0RY007                      | [6fb4081584](https://linux-hardware.org/?probe=6fb4081584) | May 25, 2023 |
| ASUSTek       | PRIME B460M-K               | [e55e554596](https://linux-hardware.org/?probe=e55e554596) | May 25, 2023 |
| ASUSTek       | A88XM-PLUS                  | [55790e804a](https://linux-hardware.org/?probe=55790e804a) | May 25, 2023 |
| Dell          | 03KWTV A02                  | [60ade2d50f](https://linux-hardware.org/?probe=60ade2d50f) | May 25, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [b291f783a2](https://linux-hardware.org/?probe=b291f783a2) | May 25, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [a2a31dbbee](https://linux-hardware.org/?probe=a2a31dbbee) | May 24, 2023 |
| ASUSTek       | Z87-DELUXE/DUAL             | [0f0c4f64ce](https://linux-hardware.org/?probe=0f0c4f64ce) | May 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [ed936908c9](https://linux-hardware.org/?probe=ed936908c9) | May 23, 2023 |
| Intel         | DG31PR AAD97573-302         | [a36e076c17](https://linux-hardware.org/?probe=a36e076c17) | May 23, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [8b3acda484](https://linux-hardware.org/?probe=8b3acda484) | May 22, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [76bd19169a](https://linux-hardware.org/?probe=76bd19169a) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| Unknown       | DT138IB                     | [130e17f9e3](https://linux-hardware.org/?probe=130e17f9e3) | May 21, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [f511a54601](https://linux-hardware.org/?probe=f511a54601) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [8952bab351](https://linux-hardware.org/?probe=8952bab351) | May 21, 2023 |
| Gigabyte      | H77M-D3H                    | [88cf891056](https://linux-hardware.org/?probe=88cf891056) | May 21, 2023 |
| MSI           | H110M PRO-VD PLUS           | [d549fb62db](https://linux-hardware.org/?probe=d549fb62db) | May 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c242460e72](https://linux-hardware.org/?probe=c242460e72) | May 20, 2023 |
| HP            | 8055                        | [ddfca600c1](https://linux-hardware.org/?probe=ddfca600c1) | May 20, 2023 |
| ASUSTek       | PRIME B460M-K               | [c6ce2f365a](https://linux-hardware.org/?probe=c6ce2f365a) | May 20, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| HP            | 8055                        | [d7b466e881](https://linux-hardware.org/?probe=d7b466e881) | May 20, 2023 |
| ASRock        | Z77 Extreme3                | [b60db9bc14](https://linux-hardware.org/?probe=b60db9bc14) | May 20, 2023 |
| ASUSTek       | Z170-A                      | [e168b46b94](https://linux-hardware.org/?probe=e168b46b94) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9f1830f264](https://linux-hardware.org/?probe=9f1830f264) | May 19, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| ASUSTek       | PRIME B650M-A II            | [183b85c77c](https://linux-hardware.org/?probe=183b85c77c) | May 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [9dbbfc6c8e](https://linux-hardware.org/?probe=9dbbfc6c8e) | May 19, 2023 |
| Gigabyte      | H67A-D3H-B3                 | [606bb335e6](https://linux-hardware.org/?probe=606bb335e6) | May 19, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [f79cecb83e](https://linux-hardware.org/?probe=f79cecb83e) | May 19, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [e4b87f1e56](https://linux-hardware.org/?probe=e4b87f1e56) | May 19, 2023 |
| MSI           | MS-B9311                    | [3cfc1fbb83](https://linux-hardware.org/?probe=3cfc1fbb83) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d8d391a609](https://linux-hardware.org/?probe=d8d391a609) | May 18, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [87418d1634](https://linux-hardware.org/?probe=87418d1634) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| Gateway       | DS10G                       | [556a92e56a](https://linux-hardware.org/?probe=556a92e56a) | May 18, 2023 |
| ASUSTek       | M2N68-AM SE2                | [41971afc9c](https://linux-hardware.org/?probe=41971afc9c) | May 17, 2023 |
| Gigabyte      | H61M-DS2                    | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [74b2c2122c](https://linux-hardware.org/?probe=74b2c2122c) | May 17, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [212936564d](https://linux-hardware.org/?probe=212936564d) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [5553ae2ec9](https://linux-hardware.org/?probe=5553ae2ec9) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [f297fbda85](https://linux-hardware.org/?probe=f297fbda85) | May 16, 2023 |
| Intel         | H61                         | [c54c89a4b1](https://linux-hardware.org/?probe=c54c89a4b1) | May 16, 2023 |
| MSI           | 3664h                       | [b45eee9c3a](https://linux-hardware.org/?probe=b45eee9c3a) | May 16, 2023 |
| HP            | 8055                        | [639cc3308f](https://linux-hardware.org/?probe=639cc3308f) | May 16, 2023 |
| HP            | 8055                        | [15c8401c45](https://linux-hardware.org/?probe=15c8401c45) | May 16, 2023 |
| HP            | 3397                        | [3cfe6e2812](https://linux-hardware.org/?probe=3cfe6e2812) | May 15, 2023 |
| Dell          | 0KV3RP A00                  | [d324b5e64d](https://linux-hardware.org/?probe=d324b5e64d) | May 15, 2023 |
| Intel         | DX79SI AAG28808-600         | [d222ee2f89](https://linux-hardware.org/?probe=d222ee2f89) | May 14, 2023 |
| Lenovo        | NOK                         | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| Gigabyte      | H61M-DS2                    | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| Gigabyte      | 970A-DS3                    | [97ef085eca](https://linux-hardware.org/?probe=97ef085eca) | May 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [07bf228811](https://linux-hardware.org/?probe=07bf228811) | May 14, 2023 |
| Dell          | 0GWHMW A00                  | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [bfff1b604f](https://linux-hardware.org/?probe=bfff1b604f) | May 13, 2023 |
| Dell          | 0D883F A05                  | [99e782e805](https://linux-hardware.org/?probe=99e782e805) | May 13, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [6d362f8c74](https://linux-hardware.org/?probe=6d362f8c74) | May 13, 2023 |
| Intel         | DG43GT AAE62768-303         | [4cc21b00e7](https://linux-hardware.org/?probe=4cc21b00e7) | May 12, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | [33f3e64e8f](https://linux-hardware.org/?probe=33f3e64e8f) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | [dbf711a2f5](https://linux-hardware.org/?probe=dbf711a2f5) | May 11, 2023 |
| Dell          | 0GU083 A00                  | [eec8f60d12](https://linux-hardware.org/?probe=eec8f60d12) | May 11, 2023 |
| Dell          | 0J3C2F A02                  | [622dd024aa](https://linux-hardware.org/?probe=622dd024aa) | May 11, 2023 |
| ASRock        | H110M-HG4                   | [7995d3740a](https://linux-hardware.org/?probe=7995d3740a) | May 10, 2023 |
| ASRock        | H110M-HG4                   | [2864ff8227](https://linux-hardware.org/?probe=2864ff8227) | May 10, 2023 |
| Gigabyte      | B360N WIFI-CF               | [e4b3bba2b5](https://linux-hardware.org/?probe=e4b3bba2b5) | May 10, 2023 |
| ASRock        | B450M-HDV R4.0              | [297c4b54d4](https://linux-hardware.org/?probe=297c4b54d4) | May 10, 2023 |
| MSI           | B450 GAMING PLUS            | [df94e4a72a](https://linux-hardware.org/?probe=df94e4a72a) | May 10, 2023 |
| Dell          | 03NVJ6 A02                  | [9f509a2647](https://linux-hardware.org/?probe=9f509a2647) | May 10, 2023 |
| ASUSTek       | M2N68-AM SE2                | [39b8aee709](https://linux-hardware.org/?probe=39b8aee709) | May 10, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [1e41703eca](https://linux-hardware.org/?probe=1e41703eca) | May 09, 2023 |
| ASRock        | Z97 Extreme4                | [5803f15c1d](https://linux-hardware.org/?probe=5803f15c1d) | May 09, 2023 |
| ASUSTek       | M2N68-AM SE2                | [669dc67190](https://linux-hardware.org/?probe=669dc67190) | May 09, 2023 |
| Acer          | Aspire TC-1760              | [24664f3383](https://linux-hardware.org/?probe=24664f3383) | May 09, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [de7b924fdb](https://linux-hardware.org/?probe=de7b924fdb) | May 08, 2023 |
| ASUSTek       | PRIME B450M-A               | [83c0648d66](https://linux-hardware.org/?probe=83c0648d66) | May 08, 2023 |
| Dell          | 0VNP2H A00                  | [ec04c034d3](https://linux-hardware.org/?probe=ec04c034d3) | May 08, 2023 |
| Gigabyte      | Z690 AERO G                 | [7673380766](https://linux-hardware.org/?probe=7673380766) | May 07, 2023 |
| ASUSTek       | M11BB                       | [35d2ca0280](https://linux-hardware.org/?probe=35d2ca0280) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Google        | Zako                        | [5d6aa6c0df](https://linux-hardware.org/?probe=5d6aa6c0df) | May 06, 2023 |
| ASRock        | Z97 Extreme4                | [7b83def3e1](https://linux-hardware.org/?probe=7b83def3e1) | May 06, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7cf447e261](https://linux-hardware.org/?probe=7cf447e261) | May 05, 2023 |
| ASUSTek       | P8H61-M LX                  | [6c96dbe3f3](https://linux-hardware.org/?probe=6c96dbe3f3) | May 05, 2023 |
| MSI           | H110M PRO-VD PLUS           | [af27e2497a](https://linux-hardware.org/?probe=af27e2497a) | May 05, 2023 |
| HP            | 212B                        | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASRock        | Z77 Extreme3                | [0da080327f](https://linux-hardware.org/?probe=0da080327f) | May 05, 2023 |
| MSI           | A68HM-E33 V2                | [14a87bc11a](https://linux-hardware.org/?probe=14a87bc11a) | May 04, 2023 |
| MSI           | A68HM-E33 V2                | [2f3264f25f](https://linux-hardware.org/?probe=2f3264f25f) | May 04, 2023 |
| Dell          | 0RY007                      | [3ec4846de7](https://linux-hardware.org/?probe=3ec4846de7) | May 03, 2023 |
| ASUSTek       | B150M-A/M.2                 | [cd68a79e95](https://linux-hardware.org/?probe=cd68a79e95) | May 03, 2023 |
| Lenovo        | IdeaCentre K320 10031       | [86fc44372c](https://linux-hardware.org/?probe=86fc44372c) | May 03, 2023 |
| Dell          | 0RY007                      | [54e2c92bb9](https://linux-hardware.org/?probe=54e2c92bb9) | May 02, 2023 |
| HP            | 198E                        | [9c02a85763](https://linux-hardware.org/?probe=9c02a85763) | May 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [0dd7d869b2](https://linux-hardware.org/?probe=0dd7d869b2) | May 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1362f2e3df](https://linux-hardware.org/?probe=1362f2e3df) | May 02, 2023 |
| Gigabyte      | H110M-DS2-CF                | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [e89da96576](https://linux-hardware.org/?probe=e89da96576) | May 01, 2023 |
| ASRock        | Z77 Extreme3                | [0aa06876c7](https://linux-hardware.org/?probe=0aa06876c7) | May 01, 2023 |
| Shuttle       | FS35V4                      | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | A520M-A PRO                 | [aa8e8397f6](https://linux-hardware.org/?probe=aa8e8397f6) | May 01, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [705ff684a9](https://linux-hardware.org/?probe=705ff684a9) | Apr 30, 2023 |
| ASRock        | FM2A68M-HD+                 | [467bb5ded2](https://linux-hardware.org/?probe=467bb5ded2) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [233ea7cdd8](https://linux-hardware.org/?probe=233ea7cdd8) | Apr 30, 2023 |
| Colorful T... | CVN B550M GAMING FROZEN ... | [177fe2fc00](https://linux-hardware.org/?probe=177fe2fc00) | Apr 30, 2023 |
| ASUSTek       | B85M-G R2.0                 | [243a170e5a](https://linux-hardware.org/?probe=243a170e5a) | Apr 30, 2023 |
| HP            | ProLiant ML10 v2            | [3582be2f06](https://linux-hardware.org/?probe=3582be2f06) | Apr 30, 2023 |
| Dell          | 0T10XW A02                  | [2cd32d1efe](https://linux-hardware.org/?probe=2cd32d1efe) | Apr 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [4801547d54](https://linux-hardware.org/?probe=4801547d54) | Apr 29, 2023 |
| Apple         | Mac-F221BEC8                | [033718212c](https://linux-hardware.org/?probe=033718212c) | Apr 28, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [77150d1166](https://linux-hardware.org/?probe=77150d1166) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | NOK                         | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| Unknown       | G41                         | [2a6a185bec](https://linux-hardware.org/?probe=2a6a185bec) | Apr 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| HP            | 1905                        | [7b15ec2d7d](https://linux-hardware.org/?probe=7b15ec2d7d) | Apr 26, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [eaac4c0ba0](https://linux-hardware.org/?probe=eaac4c0ba0) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [8f417742d1](https://linux-hardware.org/?probe=8f417742d1) | Apr 26, 2023 |
| ASUSTek       | H110-PLUS                   | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| Dell          | 0JP3NX A01                  | [2fa64e56ff](https://linux-hardware.org/?probe=2fa64e56ff) | Apr 25, 2023 |
| ASRock        | X670E Pro RS                | [e36216c3c7](https://linux-hardware.org/?probe=e36216c3c7) | Apr 25, 2023 |
| Dell          | 0K071D A01                  | [0c7edbd8ea](https://linux-hardware.org/?probe=0c7edbd8ea) | Apr 25, 2023 |
| ASUSTek       | P8B75-V                     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| Dell          | 0JP3NX A01                  | [609eeb8038](https://linux-hardware.org/?probe=609eeb8038) | Apr 24, 2023 |
| MSI           | H81M PRO-VD                 | [00ade274cb](https://linux-hardware.org/?probe=00ade274cb) | Apr 24, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | [88c455761b](https://linux-hardware.org/?probe=88c455761b) | Apr 24, 2023 |
| ASUSTek       | PRIME B450M-K II            | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| MSI           | B460M PRO-VDH               | [f7709c23a1](https://linux-hardware.org/?probe=f7709c23a1) | Apr 24, 2023 |
| MSI           | Z97S SLI Krait Edition      | [6ed93f8338](https://linux-hardware.org/?probe=6ed93f8338) | Apr 24, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [0dfc7cce7a](https://linux-hardware.org/?probe=0dfc7cce7a) | Apr 23, 2023 |
| ASUSTek       | M5A78L LE                   | [df70910ec6](https://linux-hardware.org/?probe=df70910ec6) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [4e664e5e26](https://linux-hardware.org/?probe=4e664e5e26) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| ASRock        | A75M-HVS                    | [a4964506f7](https://linux-hardware.org/?probe=a4964506f7) | Apr 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [67f15c6f4a](https://linux-hardware.org/?probe=67f15c6f4a) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [180784b3a2](https://linux-hardware.org/?probe=180784b3a2) | Apr 22, 2023 |
| ASRock        | Z170 Gaming K4              | [8209f53171](https://linux-hardware.org/?probe=8209f53171) | Apr 22, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| ASRock        | Z97E-ITX/ac                 | [f916f697ed](https://linux-hardware.org/?probe=f916f697ed) | Apr 22, 2023 |
| Biostar       | H410MH S2                   | [0f2593dc78](https://linux-hardware.org/?probe=0f2593dc78) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [a60c54ec31](https://linux-hardware.org/?probe=a60c54ec31) | Apr 22, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [f89cce4966](https://linux-hardware.org/?probe=f89cce4966) | Apr 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [170b38e40f](https://linux-hardware.org/?probe=170b38e40f) | Apr 20, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M LX                 | [c34c1abf02](https://linux-hardware.org/?probe=c34c1abf02) | Apr 18, 2023 |
| BESSTAR Te... | UM700                       | [2e820040bc](https://linux-hardware.org/?probe=2e820040bc) | Apr 02, 2023 |
| ASUSTek       | M5A78L LE                   | [7a23362aac](https://linux-hardware.org/?probe=7a23362aac) | Mar 31, 2023 |
| HP            | 18E5                        | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| MSI           | A320M PRO-VD PLUS           | [6677ab11b2](https://linux-hardware.org/?probe=6677ab11b2) | Feb 28, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [580db05e08](https://linux-hardware.org/?probe=580db05e08) | Feb 27, 2023 |
| Gigabyte      | GA-880GM-USB3               | [bb5da28703](https://linux-hardware.org/?probe=bb5da28703) | Feb 23, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Gigabyte      | B85M-D3H                    | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [1817579f89](https://linux-hardware.org/?probe=1817579f89) | Nov 25, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 6.2.0-20-generic      | 153      | 90.53%  |
| 5.19.0-21-generic     | 5        | 2.96%   |
| 6.3.2-060302-generic  | 2        | 1.18%   |
| 6.2.0-18-generic      | 2        | 1.18%   |
| 6.3.6-060306-generic  | 1        | 0.59%   |
| 6.3.4-060304-generic  | 1        | 0.59%   |
| 6.2.0-19-generic      | 1        | 0.59%   |
| 6.2.0-1003-lowlatency | 1        | 0.59%   |
| 6.1.0-16-generic      | 1        | 0.59%   |
| 5.19.0-42-generic     | 1        | 0.59%   |
| 5.19.0-28-generic     | 1        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.0   | 156      | 92.86%  |
| 5.19.0  | 7        | 4.17%   |
| 6.3.2   | 2        | 1.19%   |
| 6.3.6   | 1        | 0.6%    |
| 6.3.4   | 1        | 0.6%    |
| 6.1.0   | 1        | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 156      | 92.86%  |
| 5.19    | 7        | 4.17%   |
| 6.3     | 4        | 2.38%   |
| 6.1     | 1        | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 168      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 161      | 95.83%  |
| X-Cinnamon      | 4        | 2.38%   |
| Unknown         | 2        | 1.19%   |
| GNOME Flashback | 1        | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 98       | 57.99%  |
| X11     | 68       | 40.24%  |
| Tty     | 3        | 1.78%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 147      | 87.5%   |
| Unknown | 16       | 9.52%   |
| LightDM | 4        | 2.38%   |
| GDM     | 1        | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| en_US            | 85       | 50.3%   |
| de_DE            | 20       | 11.83%  |
| C                | 8        | 4.73%   |
| fr_FR            | 7        | 4.14%   |
| es_ES            | 6        | 3.55%   |
| pt_BR            | 4        | 2.37%   |
| en_GB            | 4        | 2.37%   |
| en_CA            | 4        | 2.37%   |
| ru_RU            | 3        | 1.78%   |
| it_IT            | 3        | 1.78%   |
| en_AU            | 3        | 1.78%   |
| cs_CZ            | 3        | 1.78%   |
| zh_CN            | 2        | 1.18%   |
| en_IL            | 2        | 1.18%   |
| tr_TR            | 1        | 0.59%   |
| sv_SE            | 1        | 0.59%   |
| pl_PL            | 1        | 0.59%   |
| nl_NL            | 1        | 0.59%   |
| lt_LT            | 1        | 0.59%   |
| ko_KR            | 1        | 0.59%   |
| fr_CH            | 1        | 0.59%   |
| fi_FI            | 1        | 0.59%   |
| es_AR            | 1        | 0.59%   |
| en_US.ISO-8859-1 | 1        | 0.59%   |
| en_SG            | 1        | 0.59%   |
| en_NZ            | 1        | 0.59%   |
| el_GR            | 1        | 0.59%   |
| de_CH            | 1        | 0.59%   |
| de_AT            | 1        | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 124      | 73.37%  |
| EFI  | 45       | 26.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Tmpfs | 101      | 59.76%  |
| Ext4  | 64       | 37.87%  |
| Btrfs | 2        | 1.18%   |
| Zfs   | 1        | 0.59%   |
| Xfs   | 1        | 0.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 137      | 81.55%  |
| MBR     | 18       | 10.71%  |
| Unknown | 13       | 7.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 132      | 78.11%  |
| Yes       | 37       | 21.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 59.17%  |
| Yes       | 69       | 40.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 51       | 30.36%  |
| MSI                 | 22       | 13.1%   |
| Gigabyte Technology | 22       | 13.1%   |
| Dell                | 17       | 10.12%  |
| Hewlett-Packard     | 12       | 7.14%   |
| ASRock              | 11       | 6.55%   |
| Intel               | 7        | 4.17%   |
| Lenovo              | 6        | 3.57%   |
| Fujitsu             | 3        | 1.79%   |
| BESSTAR Tech        | 2        | 1.19%   |
| Unknown             | 2        | 1.19%   |
| ZOTAC               | 1        | 0.6%    |
| Shuttle             | 1        | 0.6%    |
| Pegatron            | 1        | 0.6%    |
| Huanan              | 1        | 0.6%    |
| Google              | 1        | 0.6%    |
| Gateway             | 1        | 0.6%    |
| Fujitsu Siemens     | 1        | 0.6%    |
| Colorful Technology | 1        | 0.6%    |
| Biostar             | 1        | 0.6%    |
| AZW                 | 1        | 0.6%    |
| Apple               | 1        | 0.6%    |
| Acer                | 1        | 0.6%    |
| AAEON               | 1        | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 4        | 2.38%   |
| Unknown                                 | 3        | 1.79%   |
| MSI MS-7721                             | 2        | 1.19%   |
| HP EliteDesk 800 G2 DM 35W              | 2        | 1.19%   |
| BESSTAR Tech UM700                      | 2        | 1.19%   |
| ASUS TUF Gaming X570-PLUS               | 2        | 1.19%   |
| ASUS PRIME X670-P WIFI                  | 2        | 1.19%   |
| ASUS PRIME B450M-K II                   | 2        | 1.19%   |
| ASRock X670E Pro RS                     | 2        | 1.19%   |
| Shuttle XS35V4                          | 1        | 0.6%    |
| Pegatron H81-M1                         | 1        | 0.6%    |
| MSI Pro 3000/3080                       | 1        | 0.6%    |
| MSI MS-7E01                             | 1        | 0.6%    |
| MSI MS-7D99                             | 1        | 0.6%    |
| MSI MS-7D74                             | 1        | 0.6%    |
| MSI MS-7C96                             | 1        | 0.6%    |
| MSI MS-7C95                             | 1        | 0.6%    |
| MSI MS-7C84                             | 1        | 0.6%    |
| MSI MS-7C83                             | 1        | 0.6%    |
| MSI MS-7C09                             | 1        | 0.6%    |
| MSI MS-7C02                             | 1        | 0.6%    |
| MSI MS-7B86                             | 1        | 0.6%    |
| MSI MS-7B38                             | 1        | 0.6%    |
| MSI MS-7B18                             | 1        | 0.6%    |
| MSI MS-7A64                             | 1        | 0.6%    |
| MSI MS-7A15                             | 1        | 0.6%    |
| MSI MS-7924                             | 1        | 0.6%    |
| MSI MS-7922                             | 1        | 0.6%    |
| MSI MS-7893                             | 1        | 0.6%    |
| MSI MS-7846                             | 1        | 0.6%    |
| MSI MEG Z590 Aegis Ti5 (MS-B931)        | 1        | 0.6%    |
| Lenovo ThinkCentre M72e 35972Z8         | 1        | 0.6%    |
| Lenovo ThinkCentre M710s 10M8S14C00     | 1        | 0.6%    |
| Lenovo ThinkCentre M710q 10MR0021GE     | 1        | 0.6%    |
| Lenovo IdeaCentre K320 10031            | 1        | 0.6%    |
| Lenovo IdeaCentre G5 14IMB05 90N900CTFR | 1        | 0.6%    |
| Lenovo IdeaCentre 310S-08ASR 90G9006DIX | 1        | 0.6%    |
| Intel X99 V102                          | 1        | 0.6%    |
| Intel Nobilis                           | 1        | 0.6%    |
| Intel H61                               | 1        | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 16       | 9.52%   |
| Dell OptiPlex      | 9        | 5.36%   |
| ASUS TUF           | 7        | 4.17%   |
| HP EliteDesk       | 4        | 2.38%   |
| ASUS ROG           | 4        | 2.38%   |
| ASUS All           | 4        | 2.38%   |
| Lenovo ThinkCentre | 3        | 1.79%   |
| Lenovo IdeaCentre  | 3        | 1.79%   |
| Gigabyte X570      | 3        | 1.79%   |
| Dell Precision     | 3        | 1.79%   |
| Unknown            | 3        | 1.79%   |
| MSI MS-7721        | 2        | 1.19%   |
| HP Compaq          | 2        | 1.19%   |
| Gigabyte Z690      | 2        | 1.19%   |
| Fujitsu ESPRIMO    | 2        | 1.19%   |
| Dell XPS           | 2        | 1.19%   |
| Dell Inspiron      | 2        | 1.19%   |
| BESSTAR Tech UM700 | 2        | 1.19%   |
| ASUS P8H61-M       | 2        | 1.19%   |
| ASRock X670E       | 2        | 1.19%   |
| Shuttle XS35V4     | 1        | 0.6%    |
| Pegatron H81-M1    | 1        | 0.6%    |
| MSI Pro            | 1        | 0.6%    |
| MSI MS-7E01        | 1        | 0.6%    |
| MSI MS-7D99        | 1        | 0.6%    |
| MSI MS-7D74        | 1        | 0.6%    |
| MSI MS-7C96        | 1        | 0.6%    |
| MSI MS-7C95        | 1        | 0.6%    |
| MSI MS-7C84        | 1        | 0.6%    |
| MSI MS-7C83        | 1        | 0.6%    |
| MSI MS-7C09        | 1        | 0.6%    |
| MSI MS-7C02        | 1        | 0.6%    |
| MSI MS-7B86        | 1        | 0.6%    |
| MSI MS-7B38        | 1        | 0.6%    |
| MSI MS-7B18        | 1        | 0.6%    |
| MSI MS-7A64        | 1        | 0.6%    |
| MSI MS-7A15        | 1        | 0.6%    |
| MSI MS-7924        | 1        | 0.6%    |
| MSI MS-7922        | 1        | 0.6%    |
| MSI MS-7893        | 1        | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 18       | 10.71%  |
| 2021 | 18       | 10.71%  |
| 2018 | 15       | 8.93%   |
| 2015 | 15       | 8.93%   |
| 2013 | 14       | 8.33%   |
| 2020 | 13       | 7.74%   |
| 2014 | 13       | 7.74%   |
| 2010 | 10       | 5.95%   |
| 2012 | 9        | 5.36%   |
| 2011 | 9        | 5.36%   |
| 2019 | 8        | 4.76%   |
| 2023 | 6        | 3.57%   |
| 2017 | 6        | 3.57%   |
| 2016 | 6        | 3.57%   |
| 2009 | 4        | 2.38%   |
| 2006 | 2        | 1.19%   |
| 2008 | 1        | 0.6%    |
| 2007 | 1        | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 168      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 164      | 97.04%  |
| Enabled  | 5        | 2.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 167      | 99.4%   |
| Yes  | 1        | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 38       | 22.62%  |
| 32.01-64.0      | 31       | 18.45%  |
| 4.01-8.0        | 26       | 15.48%  |
| 8.01-16.0       | 21       | 12.5%   |
| 3.01-4.0        | 20       | 11.9%   |
| 64.01-256.0     | 18       | 10.71%  |
| 24.01-32.0      | 11       | 6.55%   |
| More than 256.0 | 1        | 0.6%    |
| 2.01-3.0        | 1        | 0.6%    |
| 1.01-2.0        | 1        | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 52       | 30.41%  |
| 1.01-2.0   | 47       | 27.49%  |
| 4.01-8.0   | 41       | 23.98%  |
| 3.01-4.0   | 20       | 11.7%   |
| 8.01-16.0  | 8        | 4.68%   |
| 24.01-32.0 | 1        | 0.58%   |
| 16.01-24.0 | 1        | 0.58%   |
| 0.51-1.0   | 1        | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 70       | 41.18%  |
| 2      | 41       | 24.12%  |
| 3      | 23       | 13.53%  |
| 4      | 19       | 11.18%  |
| 5      | 10       | 5.88%   |
| 6      | 5        | 2.94%   |
| 8      | 1        | 0.59%   |
| 0      | 1        | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 64.29%  |
| Yes       | 60       | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 164      | 97.04%  |
| No        | 5        | 2.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 100      | 59.52%  |
| No        | 68       | 40.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 54.17%  |
| Yes       | 77       | 45.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 38       | 22.62%  |
| Germany      | 20       | 11.9%   |
| Canada       | 12       | 7.14%   |
| France       | 9        | 5.36%   |
| Brazil       | 6        | 3.57%   |
| UK           | 5        | 2.98%   |
| Sweden       | 5        | 2.98%   |
| Netherlands  | 5        | 2.98%   |
| Italy        | 5        | 2.98%   |
| Australia    | 5        | 2.98%   |
| Switzerland  | 4        | 2.38%   |
| Spain        | 4        | 2.38%   |
| Czechia      | 4        | 2.38%   |
| Turkey       | 3        | 1.79%   |
| Russia       | 3        | 1.79%   |
| Israel       | 3        | 1.79%   |
| Poland       | 2        | 1.19%   |
| Philippines  | 2        | 1.19%   |
| Lithuania    | 2        | 1.19%   |
| Iran         | 2        | 1.19%   |
| India        | 2        | 1.19%   |
| Hong Kong    | 2        | 1.19%   |
| Greece       | 2        | 1.19%   |
| Finland      | 2        | 1.19%   |
| China        | 2        | 1.19%   |
| Belgium      | 2        | 1.19%   |
| Austria      | 2        | 1.19%   |
| Sri Lanka    | 1        | 0.6%    |
| South Korea  | 1        | 0.6%    |
| South Africa | 1        | 0.6%    |
| Singapore    | 1        | 0.6%    |
| Serbia       | 1        | 0.6%    |
| Portugal     | 1        | 0.6%    |
| Peru         | 1        | 0.6%    |
| Paraguay     | 1        | 0.6%    |
| Norway       | 1        | 0.6%    |
| New Zealand  | 1        | 0.6%    |
| Malaysia     | 1        | 0.6%    |
| Indonesia    | 1        | 0.6%    |
| Chile        | 1        | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Sao Paulo          | 3        | 1.78%   |
| Tehran             | 2        | 1.18%   |
| Prague             | 2        | 1.18%   |
| Petah Tikva        | 2        | 1.18%   |
| Montreal           | 2        | 1.18%   |
| Melbourne          | 2        | 1.18%   |
| Heilbronn          | 2        | 1.18%   |
| Biel/Bienne        | 2        | 1.18%   |
| Amsterdam          | 2        | 1.18%   |
| Zaandam            | 1        | 0.59%   |
| Yuma               | 1        | 0.59%   |
| York               | 1        | 0.59%   |
| Würzburg          | 1        | 0.59%   |
| Wuhan              | 1        | 0.59%   |
| Winston-Salem      | 1        | 0.59%   |
| Winnipeg           | 1        | 0.59%   |
| Windsor            | 1        | 0.59%   |
| Wil                | 1        | 0.59%   |
| Wedel              | 1        | 0.59%   |
| Warsaw             | 1        | 0.59%   |
| Vitry-le-François | 1        | 0.59%   |
| Visakhapatnam      | 1        | 0.59%   |
| Virginia Beach     | 1        | 0.59%   |
| Vienna             | 1        | 0.59%   |
| Versailles         | 1        | 0.59%   |
| Valencia           | 1        | 0.59%   |
| Tupelo             | 1        | 0.59%   |
| Toronto            | 1        | 0.59%   |
| Tampa              | 1        | 0.59%   |
| Tamarac            | 1        | 0.59%   |
| Tajrish            | 1        | 0.59%   |
| Sydney             | 1        | 0.59%   |
| Surrey             | 1        | 0.59%   |
| Surat              | 1        | 0.59%   |
| Stenungsund        | 1        | 0.59%   |
| Steinberg am See   | 1        | 0.59%   |
| Soledade           | 1        | 0.59%   |
| Singapore          | 1        | 0.59%   |
| Saratov            | 1        | 0.59%   |
| Santiago           | 1        | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 62       | 78     | 19.25%  |
| Samsung Electronics         | 61       | 85     | 18.94%  |
| WDC                         | 54       | 72     | 16.77%  |
| SanDisk                     | 17       | 21     | 5.28%   |
| Kingston                    | 16       | 19     | 4.97%   |
| Toshiba                     | 14       | 16     | 4.35%   |
| Hitachi                     | 14       | 16     | 4.35%   |
| Crucial                     | 8        | 9      | 2.48%   |
| SK hynix                    | 5        | 5      | 1.55%   |
| Kingston Technology Company | 5        | 7      | 1.55%   |
| Intel                       | 5        | 6      | 1.55%   |
| Unknown                     | 4        | 4      | 1.24%   |
| Phison Electronics          | 4        | 5      | 1.24%   |
| PNY                         | 3        | 4      | 0.93%   |
| Micron/Crucial Technology   | 3        | 3      | 0.93%   |
| China                       | 3        | 3      | 0.93%   |
| SABRENT                     | 2        | 5      | 0.62%   |
| Phison                      | 2        | 3      | 0.62%   |
| Patriot                     | 2        | 2      | 0.62%   |
| OCZ                         | 2        | 2      | 0.62%   |
| Micron Technology           | 2        | 3      | 0.62%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.62%   |
| HGST                        | 2        | 2      | 0.62%   |
| Gigabyte Technology         | 2        | 2      | 0.62%   |
| A-DATA Technology           | 2        | 2      | 0.62%   |
| Yangtze Memory Technologies | 1        | 1      | 0.31%   |
| Verbatim                    | 1        | 2      | 0.31%   |
| Transcend                   | 1        | 1      | 0.31%   |
| TEXTORM                     | 1        | 1      | 0.31%   |
| Smartbuy                    | 1        | 2      | 0.31%   |
| Silicon Motion              | 1        | 1      | 0.31%   |
| Rogueware                   | 1        | 1      | 0.31%   |
| Realtek Semiconductor       | 1        | 2      | 0.31%   |
| Realtek                     | 1        | 1      | 0.31%   |
| OWC                         | 1        | 2      | 0.31%   |
| Neo                         | 1        | 2      | 0.31%   |
| MSI                         | 1        | 1      | 0.31%   |
| LITEONIT                    | 1        | 1      | 0.31%   |
| LITEON                      | 1        | 1      | 0.31%   |
| Lexar                       | 1        | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 10       | 2.75%   |
| Seagate ST1000DM010-2EP102 1TB                      | 7        | 1.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 6        | 1.65%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 4        | 1.1%    |
| Seagate ST1000DM003-1CH162 1TB                      | 4        | 1.1%    |
| Samsung SSD 990 PRO 1TB                             | 4        | 1.1%    |
| Samsung SSD 860 EVO 500GB                           | 4        | 1.1%    |
| Samsung SSD 850 EVO 250GB                           | 4        | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 4        | 1.1%    |
| Kingston SA400S37240G 240GB SSD                     | 4        | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3        | 0.83%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 3        | 0.83%   |
| Toshiba DT01ACA200 2TB                              | 3        | 0.83%   |
| Toshiba DT01ACA100 1TB                              | 3        | 0.83%   |
| Seagate ST4000DM004-2CV104 4TB                      | 3        | 0.83%   |
| Seagate ST2000DM008-2FR102 2TB                      | 3        | 0.83%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3        | 0.83%   |
| Samsung SSD 980 1TB                                 | 3        | 0.83%   |
| Samsung SSD 870 EVO 500GB                           | 3        | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 3        | 0.83%   |
| Kingston Company SNV2S2000G 2TB                     | 3        | 0.83%   |
| Kingston SA400S37480G 480GB SSD                     | 3        | 0.83%   |
| WDC WD80EFAX-68KNBN0 8TB                            | 2        | 0.55%   |
| WDC WD5000AAKX-001CA0 500GB                         | 2        | 0.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 2        | 0.55%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 2        | 0.55%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 0.55%   |
| Seagate ST6000DM003-2CY186 6TB                      | 2        | 0.55%   |
| Seagate ST500DM002-1BD142 500GB                     | 2        | 0.55%   |
| Seagate ST3500418AS 500GB                           | 2        | 0.55%   |
| Seagate ST2000LM007-1R8174 2TB                      | 2        | 0.55%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2        | 0.55%   |
| Seagate ST1000DM003-9YN162 1TB                      | 2        | 0.55%   |
| Seagate ST1000DM003-1SB10C 1TB                      | 2        | 0.55%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2        | 0.55%   |
| SanDisk SSD PLUS 480GB                              | 2        | 0.55%   |
| SanDisk SSD PLUS 1000GB                             | 2        | 0.55%   |
| SanDisk SD8SB8U-128G-1016 128GB SSD                 | 2        | 0.55%   |
| SanDisk NVMe SSD Drive 500GB                        | 2        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 60       | 76     | 41.67%  |
| WDC                 | 49       | 64     | 34.03%  |
| Hitachi             | 14       | 16     | 9.72%   |
| Toshiba             | 12       | 14     | 8.33%   |
| Samsung Electronics | 4        | 5      | 2.78%   |
| HGST                | 2        | 2      | 1.39%   |
| Unknown             | 1        | 1      | 0.69%   |
| ASMT                | 1        | 3      | 0.69%   |
| Apple               | 1        | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 30       | 40     | 31.91%  |
| Kingston            | 12       | 15     | 12.77%  |
| SanDisk             | 9        | 10     | 9.57%   |
| WDC                 | 6        | 6      | 6.38%   |
| Crucial             | 6        | 7      | 6.38%   |
| Intel               | 3        | 4      | 3.19%   |
| China               | 3        | 3      | 3.19%   |
| SABRENT             | 2        | 5      | 2.13%   |
| PNY                 | 2        | 2      | 2.13%   |
| Patriot             | 2        | 2      | 2.13%   |
| OCZ                 | 2        | 2      | 2.13%   |
| A-DATA Technology   | 2        | 2      | 2.13%   |
| Verbatim            | 1        | 2      | 1.06%   |
| Toshiba             | 1        | 1      | 1.06%   |
| TEXTORM             | 1        | 1      | 1.06%   |
| Smartbuy            | 1        | 2      | 1.06%   |
| Rogueware           | 1        | 1      | 1.06%   |
| Phison              | 1        | 1      | 1.06%   |
| OWC                 | 1        | 2      | 1.06%   |
| Neo                 | 1        | 2      | 1.06%   |
| MSI                 | 1        | 1      | 1.06%   |
| Micron Technology   | 1        | 2      | 1.06%   |
| LITEONIT            | 1        | 1      | 1.06%   |
| LITEON              | 1        | 1      | 1.06%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.06%   |
| KingSpec            | 1        | 1      | 1.06%   |
| Inland              | 1        | 1      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 114      | 182    | 42.7%   |
| SSD     | 76       | 118    | 28.46%  |
| NVMe    | 71       | 103    | 26.59%  |
| Unknown | 5        | 5      | 1.87%   |
| MMC     | 1        | 1      | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 139      | 285    | 62.33%  |
| NVMe | 71       | 102    | 31.84%  |
| SAS  | 12       | 21     | 5.38%   |
| MMC  | 1        | 1      | 0.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 87       | 136    | 42.23%  |
| 0.51-1.0   | 63       | 90     | 30.58%  |
| 1.01-2.0   | 29       | 34     | 14.08%  |
| 3.01-4.0   | 12       | 18     | 5.83%   |
| 4.01-10.0  | 7        | 10     | 3.4%    |
| 2.01-3.0   | 4        | 4      | 1.94%   |
| 10.01-20.0 | 4        | 8      | 1.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 40       | 23.53%  |
| 251-500        | 38       | 22.35%  |
| 101-250        | 31       | 18.24%  |
| More than 3000 | 18       | 10.59%  |
| 1001-2000      | 17       | 10%     |
| 2001-3000      | 9        | 5.29%   |
| 51-100         | 8        | 4.71%   |
| 1-20           | 5        | 2.94%   |
| 21-50          | 3        | 1.76%   |
| Unknown        | 1        | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 53       | 31.55%  |
| 21-50          | 35       | 20.83%  |
| 101-250        | 23       | 13.69%  |
| 51-100         | 17       | 10.12%  |
| 251-500        | 15       | 8.93%   |
| More than 3000 | 7        | 4.17%   |
| 2001-3000      | 7        | 4.17%   |
| 1001-2000      | 5        | 2.98%   |
| 501-1000       | 5        | 2.98%   |
| Unknown        | 1        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Desktops | Drives | Percent |
|-----------------------------------------|----------|--------|---------|
| WDC WD5000HHTZ-04N21V0 500GB            | 1        | 1      | 10%     |
| WDC WD5000AAKS-00UU3A0 500GB            | 1        | 1      | 10%     |
| WDC WD10EZRZ-00HTKB0 1TB                | 1        | 1      | 10%     |
| WDC WD10EZEX-22MFCA0 1TB                | 1        | 2      | 10%     |
| WDC WD10EARS-22Y5B1 1TB                 | 1        | 1      | 10%     |
| Seagate ST500DM002-1BD142 500GB         | 1        | 1      | 10%     |
| Samsung Electronics SSD 960 EVO 250GB   | 1        | 1      | 10%     |
| Neo Forza NFS121SA312-6007000 120GB SSD | 1        | 2      | 10%     |
| Hitachi HDS721010CLA332 1TB             | 1        | 1      | 10%     |
| Gigabyte Technology GP-GM30512G-G 512GB | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 6      | 50%     |
| Seagate             | 1        | 1      | 10%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Neo                 | 1        | 2      | 10%     |
| Hitachi             | 1        | 1      | 10%     |
| Gigabyte Technology | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 6      | 71.43%  |
| Seagate | 1        | 1      | 14.29%  |
| Hitachi | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 8      | 70%     |
| NVMe | 2        | 2      | 20%     |
| SSD  | 1        | 2      | 10%     |

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
| Detected | 124      | 297    | 70.06%  |
| Works    | 44       | 100    | 24.86%  |
| Malfunc  | 9        | 12     | 5.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 114      | 44.02%  |
| AMD                          | 50       | 19.31%  |
| Samsung Electronics          | 33       | 12.74%  |
| SanDisk                      | 10       | 3.86%   |
| Kingston Technology Company  | 10       | 3.86%   |
| Phison Electronics           | 7        | 2.7%    |
| ASMedia Technology           | 6        | 2.32%   |
| SK hynix                     | 5        | 1.93%   |
| Micron/Crucial Technology    | 5        | 1.93%   |
| Marvell Technology Group     | 3        | 1.16%   |
| Silicon Motion               | 2        | 0.77%   |
| Seagate Technology           | 2        | 0.77%   |
| Realtek Semiconductor        | 2        | 0.77%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.77%   |
| Yangtze Memory Technologies  | 1        | 0.39%   |
| Toshiba America Info Systems | 1        | 0.39%   |
| Shenzhen Longsys Electronics | 1        | 0.39%   |
| Nvidia                       | 1        | 0.39%   |
| Micron Technology            | 1        | 0.39%   |
| KIOXIA                       | 1        | 0.39%   |
| JMicron Technology           | 1        | 0.39%   |
| INNOGRIT                     | 1        | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 33       | 10.65%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 4.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 4.19%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 11       | 3.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 3.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8        | 2.58%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8        | 2.58%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 2.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6        | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 1.94%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 1.94%   |
| Samsung Electronics Non-Volatile memory controller                                      | 5        | 1.61%   |
| Kingston Company Company Non-Volatile memory controller                                 | 5        | 1.61%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5        | 1.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.61%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.61%   |
| Samsung NVMe SSD Controller 980                                                         | 4        | 1.29%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 4        | 1.29%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 1.29%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 1.29%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.29%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.29%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.29%   |
| SanDisk WD Black SN770 NVMe SSD                                                         | 3        | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 0.97%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 0.97%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                                        | 2        | 0.65%   |
| Seagate FireCuda 530 SSD                                                                | 2        | 0.65%   |
| Sandisk Western Digital WD Black SN850X NVMe SSD                                        | 2        | 0.65%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 2        | 0.65%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.65%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 2        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 142      | 55.04%  |
| NVMe | 71       | 27.52%  |
| IDE  | 25       | 9.69%   |
| RAID | 20       | 7.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 117      | 69.64%  |
| AMD    | 51       | 30.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i7-4790 CPU @ 3.60GHz              | 4        | 2.38%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4        | 2.38%   |
| Intel 12th Gen Core i7-12700                  | 4        | 2.38%   |
| AMD Ryzen 9 7900X 12-Core Processor           | 4        | 2.38%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 3        | 1.79%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 1.79%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 3        | 1.79%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3        | 1.79%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 2        | 1.19%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2        | 1.19%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 2        | 1.19%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2        | 1.19%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2        | 1.19%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 2        | 1.19%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2        | 1.19%   |
| Intel Core i3-6100T CPU @ 3.20GHz             | 2        | 1.19%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2        | 1.19%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2        | 1.19%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 2        | 1.19%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz          | 2        | 1.19%   |
| Intel 13th Gen Core i9-13900K                 | 2        | 1.19%   |
| Intel 12th Gen Core i7-12700K                 | 2        | 1.19%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.19%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz       | 2        | 1.19%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 2        | 1.19%   |
| AMD Ryzen 9 7900 12-Core Processor            | 2        | 1.19%   |
| AMD Ryzen 7 7700X 8-Core Processor            | 2        | 1.19%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2        | 1.19%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2        | 1.19%   |
| AMD Ryzen 5 5500                              | 2        | 1.19%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 2        | 1.19%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2        | 1.19%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2        | 1.19%   |
| AMD Phenom II X4 965 Processor                | 2        | 1.19%   |
| AMD FX-6300 Six-Core Processor                | 2        | 1.19%   |
| AMD A10-6700 APU with Radeon HD Graphics      | 2        | 1.19%   |
| Intel Xeon CPU X5690 @ 3.47GHz                | 1        | 0.6%    |
| Intel Xeon CPU X5660 @ 2.80GHz                | 1        | 0.6%    |
| Intel Xeon CPU X5550 @ 2.67GHz                | 1        | 0.6%    |
| Intel Xeon CPU E5450 @ 3.00GHz                | 1        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 36       | 21.43%  |
| Intel Core i7          | 25       | 14.88%  |
| Other                  | 21       | 12.5%   |
| AMD Ryzen 5            | 14       | 8.33%   |
| Intel Xeon             | 11       | 6.55%   |
| Intel Core i3          | 11       | 6.55%   |
| AMD Ryzen 9            | 11       | 6.55%   |
| AMD Ryzen 7            | 9        | 5.36%   |
| Intel Core 2 Duo       | 7        | 4.17%   |
| AMD Phenom II X4       | 3        | 1.79%   |
| AMD A10                | 3        | 1.79%   |
| Intel Pentium          | 2        | 1.19%   |
| Intel Celeron          | 2        | 1.19%   |
| AMD FX                 | 2        | 1.19%   |
| Intel Core 2 Quad      | 1        | 0.6%    |
| Intel Celeron D        | 1        | 0.6%    |
| Intel Atom             | 1        | 0.6%    |
| AMD Ryzen Threadripper | 1        | 0.6%    |
| AMD Phenom             | 1        | 0.6%    |
| AMD Athlon II X4       | 1        | 0.6%    |
| AMD Athlon II X3       | 1        | 0.6%    |
| AMD Athlon Dual Core   | 1        | 0.6%    |
| AMD A8                 | 1        | 0.6%    |
| AMD A6                 | 1        | 0.6%    |
| AMD A4                 | 1        | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 64       | 38.1%   |
| 6      | 31       | 18.45%  |
| 2      | 25       | 14.88%  |
| 12     | 18       | 10.71%  |
| 8      | 15       | 8.93%   |
| 16     | 5        | 2.98%   |
| 3      | 3        | 1.79%   |
| 1      | 3        | 1.79%   |
| 24     | 2        | 1.19%   |
| 32     | 1        | 0.6%    |
| 14     | 1        | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 165      | 98.21%  |
| 2      | 3        | 1.79%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 99       | 58.58%  |
| 1      | 70       | 41.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 168      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 147      | 87.5%   |
| 0x0a601203 | 8        | 4.76%   |
| 0x0a20120a | 2        | 1.19%   |
| 0x010000c8 | 2        | 1.19%   |
| 0xf64      | 1        | 0.6%    |
| 0x306c3    | 1        | 0.6%    |
| 0x0a50000c | 1        | 0.6%    |
| 0x0a201205 | 1        | 0.6%    |
| 0x0a201025 | 1        | 0.6%    |
| 0x08701021 | 1        | 0.6%    |
| 0x08108109 | 1        | 0.6%    |
| 0x06006705 | 1        | 0.6%    |
| 0x06000852 | 1        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 28       | 16.57%  |
| Haswell          | 23       | 13.61%  |
| KabyLake         | 15       | 8.88%   |
| Skylake          | 13       | 7.69%   |
| Zen 3            | 12       | 7.1%    |
| IvyBridge        | 11       | 6.51%   |
| SandyBridge      | 9        | 5.33%   |
| Penryn           | 9        | 5.33%   |
| Piledriver       | 8        | 4.73%   |
| CometLake        | 7        | 4.14%   |
| Zen+             | 6        | 3.55%   |
| K10              | 6        | 3.55%   |
| Zen 2            | 5        | 2.96%   |
| Westmere         | 3        | 1.78%   |
| Alderlake Hybrid | 3        | 1.78%   |
| Silvermont       | 2        | 1.18%   |
| Core             | 2        | 1.18%   |
| NetBurst         | 1        | 0.59%   |
| Nehalem          | 1        | 0.59%   |
| K8 Hammer        | 1        | 0.59%   |
| Icelake          | 1        | 0.59%   |
| Gracemont        | 1        | 0.59%   |
| Excavator        | 1        | 0.59%   |
| Broadwell        | 1        | 0.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 66       | 36.26%  |
| Intel                      | 61       | 33.52%  |
| AMD                        | 54       | 29.67%  |
| Matrox Electronics Systems | 1        | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 5.88%   |
| AMD Raphael                                                                 | 10       | 5.35%   |
| Intel HD Graphics 530                                                       | 8        | 4.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 3.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 3.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 2.67%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 2.14%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.6%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.6%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 1.6%    |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 3        | 1.6%    |
| Nvidia AD102 [GeForce RTX 4090]                                             | 3        | 1.6%    |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 3        | 1.6%    |
| Intel HD Graphics 630                                                       | 3        | 1.6%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 1.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.6%    |
| Intel AlderLake-S GT1                                                       | 3        | 1.6%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 1.6%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 1.6%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.6%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 1.07%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 1.07%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.07%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.07%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.07%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.07%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2        | 1.07%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 2        | 1.07%   |
| Nvidia AD104 [GeForce RTX 4070 Ti]                                          | 2        | 1.07%   |
| Nvidia AD103 [GeForce RTX 4080]                                             | 2        | 1.07%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 2        | 1.07%   |
| AMD Richland [Radeon HD 8670D]                                              | 2        | 1.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.07%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2        | 1.07%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 1.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.07%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.07%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 53       | 31.55%  |
| 1 x Intel      | 53       | 31.55%  |
| 1 x AMD        | 45       | 26.79%  |
| Intel + Nvidia | 6        | 3.57%   |
| AMD + Nvidia   | 6        | 3.57%   |
| 2 x AMD        | 3        | 1.79%   |
| 2 x Nvidia     | 1        | 0.6%    |
| 1 x Matrox     | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 121      | 72.02%  |
| Proprietary | 44       | 26.19%  |
| Unknown     | 3        | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 126      | 75%     |
| 7.01-8.0   | 9        | 5.36%   |
| 1.01-2.0   | 8        | 4.76%   |
| 0.01-0.5   | 7        | 4.17%   |
| 0.51-1.0   | 5        | 2.98%   |
| 3.01-4.0   | 4        | 2.38%   |
| 16.01-24.0 | 4        | 2.38%   |
| 8.01-16.0  | 3        | 1.79%   |
| 5.01-6.0   | 2        | 1.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 28       | 15.82%  |
| Dell                 | 18       | 10.17%  |
| Goldstar             | 17       | 9.6%    |
| Hewlett-Packard      | 14       | 7.91%   |
| Ancor Communications | 13       | 7.34%   |
| Acer                 | 13       | 7.34%   |
| AOC                  | 12       | 6.78%   |
| Philips              | 8        | 4.52%   |
| Iiyama               | 7        | 3.95%   |
| ViewSonic            | 5        | 2.82%   |
| BenQ                 | 5        | 2.82%   |
| MSI                  | 3        | 1.69%   |
| Lenovo               | 3        | 1.69%   |
| Unknown (XXX)        | 2        | 1.13%   |
| Sceptre Tech         | 2        | 1.13%   |
| NEC Computers        | 2        | 1.13%   |
| MiTAC                | 2        | 1.13%   |
| Hitachi              | 2        | 1.13%   |
| Gigabyte Technology  | 2        | 1.13%   |
| ASUSTek Computer     | 2        | 1.13%   |
| Vizio                | 1        | 0.56%   |
| Toshiba              | 1        | 0.56%   |
| TCL                  | 1        | 0.56%   |
| SANYO                | 1        | 0.56%   |
| Positivo             | 1        | 0.56%   |
| NECCI                | 1        | 0.56%   |
| KTC                  | 1        | 0.56%   |
| JVC                  | 1        | 0.56%   |
| HKM                  | 1        | 0.56%   |
| HKC                  | 1        | 0.56%   |
| Fujitsu Siemens      | 1        | 0.56%   |
| FAY                  | 1        | 0.56%   |
| Eizo                 | 1        | 0.56%   |
| Daewoo               | 1        | 0.56%   |
| CVT                  | 1        | 0.56%   |
| CHD                  | 1        | 0.56%   |
| Unknown              | 1        | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                   | 3        | 1.63%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 2        | 1.09%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2        | 1.09%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 2        | 1.09%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 1.09%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                      | 2        | 1.09%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                         | 2        | 1.09%   |
| Vizio E422VLE VIZ0092 1920x1080 930x523mm 42.0-inch                     | 1        | 0.54%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch           | 1        | 0.54%   |
| ViewSonic VX2235wm VSC591E 1680x1050 474x296mm 22.0-inch                | 1        | 0.54%   |
| ViewSonic VG2755-2K VSC4E37 2560x1440 597x336mm 27.0-inch               | 1        | 0.54%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch               | 1        | 0.54%   |
| ViewSonic VA2702w VSCE727 1920x1080 598x336mm 27.0-inch                 | 1        | 0.54%   |
| Unknown (XXX) LED TV XXX3553 1920x1080 530x290mm 23.8-inch              | 1        | 0.54%   |
| Unknown (XXX) HD TV XXXC37E 1920x1080 700x390mm 31.5-inch               | 1        | 0.54%   |
| Toshiba TV TSB0200 1360x768 409x230mm 18.5-inch                         | 1        | 0.54%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                     | 1        | 0.54%   |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch          | 1        | 0.54%   |
| Sceptre Tech E32 SPT0CB8 1366x768 575x323mm 26.0-inch                   | 1        | 0.54%   |
| SANYO LCD-42S SAN0A28 1360x765 708x398mm 32.0-inch                      | 1        | 0.54%   |
| Samsung Electronics U32H85x SAM0E3A 3840x2160 697x392mm 31.5-inch       | 1        | 0.54%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM0485 1920x1080 520x320mm 24.0-inch    | 1        | 0.54%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 338x270mm 17.0-inch    | 1        | 0.54%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1        | 0.54%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 1        | 0.54%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch       | 1        | 0.54%   |
| Samsung Electronics S24B350 SAM08DA 1920x1080 531x299mm 24.0-inch       | 1        | 0.54%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.54%   |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch       | 1        | 0.54%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 527x296mm 23.8-inch     | 1        | 0.54%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch     | 1        | 0.54%   |
| Samsung Electronics LF22T35 SAM707C 1920x1080 477x268mm 21.5-inch       | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SyncMaster                              | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SAM723F 3840x2160 700x390mm 31.5-inch   | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SAM0F09 3840x2160 1872x1053mm 84.6-inch | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SAM0D47 1920x1080 480x270mm 21.7-inch   | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1        | 0.54%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch   | 1        | 0.54%   |
| Samsung Electronics LCD Monitor C32JG5x 2560x1440                       | 1        | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 82       | 47.67%  |
| 3840x2160 (4K)     | 26       | 15.12%  |
| 2560x1440 (QHD)    | 24       | 13.95%  |
| 1440x900 (WXGA+)   | 7        | 4.07%   |
| 3840x1080          | 4        | 2.33%   |
| 1280x1024 (SXGA)   | 4        | 2.33%   |
| 3440x1440          | 3        | 1.74%   |
| 2560x1080          | 3        | 1.74%   |
| 1920x1200 (WUXGA)  | 3        | 1.74%   |
| 1600x900 (HD+)     | 3        | 1.74%   |
| 1366x768 (WXGA)    | 3        | 1.74%   |
| 1920x540           | 2        | 1.16%   |
| 1680x1050 (WSXGA+) | 2        | 1.16%   |
| Unknown            | 2        | 1.16%   |
| 3840x1600          | 1        | 0.58%   |
| 1360x768           | 1        | 0.58%   |
| 1280x720 (HD)      | 1        | 0.58%   |
| 1024x768 (XGA)     | 1        | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 32       | 18.08%  |
| 24      | 22       | 12.43%  |
| 21      | 21       | 11.86%  |
| 23      | 20       | 11.3%   |
| 31      | 18       | 10.17%  |
| 19      | 10       | 5.65%   |
| Unknown | 7        | 3.95%   |
| 34      | 5        | 2.82%   |
| 52      | 3        | 1.69%   |
| 48      | 3        | 1.69%   |
| 40      | 3        | 1.69%   |
| 32      | 3        | 1.69%   |
| 26      | 3        | 1.69%   |
| 18      | 3        | 1.69%   |
| 17      | 3        | 1.69%   |
| 84      | 2        | 1.13%   |
| 65      | 2        | 1.13%   |
| 22      | 2        | 1.13%   |
| 72      | 1        | 0.56%   |
| 63      | 1        | 0.56%   |
| 60      | 1        | 0.56%   |
| 54      | 1        | 0.56%   |
| 46      | 1        | 0.56%   |
| 43      | 1        | 0.56%   |
| 42      | 1        | 0.56%   |
| 38      | 1        | 0.56%   |
| 37      | 1        | 0.56%   |
| 33      | 1        | 0.56%   |
| 28      | 1        | 0.56%   |
| 20      | 1        | 0.56%   |
| 15      | 1        | 0.56%   |
| 14      | 1        | 0.56%   |
| 10      | 1        | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 71       | 40.57%  |
| 401-500     | 34       | 19.43%  |
| 601-700     | 23       | 13.14%  |
| 1001-1500   | 12       | 6.86%   |
| 701-800     | 9        | 5.14%   |
| Unknown     | 7        | 4%      |
| 801-900     | 4        | 2.29%   |
| 351-400     | 4        | 2.29%   |
| 301-350     | 3        | 1.71%   |
| 1501-2000   | 3        | 1.71%   |
| 901-1000    | 3        | 1.71%   |
| 201-300     | 2        | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 121      | 75.63%  |
| 16/10   | 14       | 8.75%   |
| 21/9    | 7        | 4.38%   |
| 5/4     | 5        | 3.13%   |
| 32/9    | 5        | 3.13%   |
| Unknown | 5        | 3.13%   |
| 4/3     | 3        | 1.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 46       | 26.29%  |
| 301-350        | 34       | 19.43%  |
| 351-500        | 27       | 15.43%  |
| 151-200        | 19       | 10.86%  |
| 251-300        | 12       | 6.86%   |
| More than 1000 | 11       | 6.29%   |
| 501-1000       | 10       | 5.71%   |
| Unknown        | 7        | 4%      |
| 141-150        | 5        | 2.86%   |
| 101-110        | 2        | 1.14%   |
| 51-60          | 1        | 0.57%   |
| 131-140        | 1        | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 98       | 58.68%  |
| 101-120 | 40       | 23.95%  |
| 121-160 | 11       | 6.59%   |
| 1-50    | 8        | 4.79%   |
| Unknown | 7        | 4.19%   |
| 161-240 | 3        | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 126      | 75%     |
| 2     | 31       | 18.45%  |
| 0     | 9        | 5.36%   |
| 4     | 1        | 0.6%    |
| 3     | 1        | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 111      | 43.87%  |
| Intel                           | 71       | 28.06%  |
| Broadcom                        | 12       | 4.74%   |
| TP-Link                         | 9        | 3.56%   |
| Qualcomm Atheros                | 9        | 3.56%   |
| MediaTek                        | 7        | 2.77%   |
| Ralink Technology               | 5        | 1.98%   |
| Microsoft                       | 3        | 1.19%   |
| D-Link                          | 3        | 1.19%   |
| Aquantia                        | 3        | 1.19%   |
| Samsung Electronics             | 2        | 0.79%   |
| Mellanox Technologies           | 2        | 0.79%   |
| Google                          | 2        | 0.79%   |
| ASUSTek Computer                | 2        | 0.79%   |
| Z-Com                           | 1        | 0.4%    |
| Xiaomi                          | 1        | 0.4%    |
| Ralink                          | 1        | 0.4%    |
| Qualcomm Atheros Communications | 1        | 0.4%    |
| Nvidia                          | 1        | 0.4%    |
| NetGear                         | 1        | 0.4%    |
| Linksys                         | 1        | 0.4%    |
| Guillemot                       | 1        | 0.4%    |
| Edimax Technology               | 1        | 0.4%    |
| Dresden Elektronik              | 1        | 0.4%    |
| AVM                             | 1        | 0.4%    |
| Apple                           | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80       | 27.49%  |
| Realtek RTL8125 2.5GbE Controller                                 | 17       | 5.84%   |
| Intel Ethernet Controller I225-V                                  | 8        | 2.75%   |
| Intel Wi-Fi 6 AX200                                               | 7        | 2.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 1.72%   |
| Intel I211 Gigabit Network Connection                             | 5        | 1.72%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 5        | 1.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4        | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 1.37%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.37%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.37%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 1.37%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 4        | 1.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 3        | 1.03%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3        | 1.03%   |
| Realtek 802.11ac NIC                                              | 3        | 1.03%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 1.03%   |
| Microsoft Xbox 360 Wireless Adapter                               | 3        | 1.03%   |
| Intel Wireless-AC 9260                                            | 3        | 1.03%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.03%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 1.03%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 1.03%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2        | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.69%   |
| Intel Wireless 7265                                               | 2        | 0.69%   |
| Intel Wireless 3165                                               | 2        | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.69%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.69%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.69%   |
| D-Link 802.11ac NIC                                               | 2        | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 37       | 35.24%  |
| Realtek Semiconductor           | 20       | 19.05%  |
| TP-Link                         | 9        | 8.57%   |
| MediaTek                        | 7        | 6.67%   |
| Qualcomm Atheros                | 6        | 5.71%   |
| Ralink Technology               | 5        | 4.76%   |
| Broadcom                        | 5        | 4.76%   |
| Microsoft                       | 3        | 2.86%   |
| D-Link                          | 3        | 2.86%   |
| ASUSTek Computer                | 2        | 1.9%    |
| Z-Com                           | 1        | 0.95%   |
| Ralink                          | 1        | 0.95%   |
| Qualcomm Atheros Communications | 1        | 0.95%   |
| NetGear                         | 1        | 0.95%   |
| Linksys                         | 1        | 0.95%   |
| Guillemot                       | 1        | 0.95%   |
| Edimax Technology               | 1        | 0.95%   |
| AVM                             | 1        | 0.95%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 7        | 6.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 5        | 4.72%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 5        | 4.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 4        | 3.77%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 4        | 3.77%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 3        | 2.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 3        | 2.83%   |
| Realtek 802.11ac NIC                                          | 3        | 2.83%   |
| Ralink MT7601U Wireless Adapter                               | 3        | 2.83%   |
| Microsoft Xbox 360 Wireless Adapter                           | 3        | 2.83%   |
| Intel Wireless-AC 9260                                        | 3        | 2.83%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3        | 2.83%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter            | 3        | 2.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 2        | 1.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 1.89%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 2        | 1.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2        | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2        | 1.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 2        | 1.89%   |
| Intel Wireless 7265                                           | 2        | 1.89%   |
| Intel Wireless 3165                                           | 2        | 1.89%   |
| D-Link 802.11ac NIC                                           | 2        | 1.89%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 2        | 1.89%   |
| ASUS 802.11ac NIC                                             | 2        | 1.89%   |
| Z-Com XG-703A 802.11g Wireless Adapter [Intersil ISL3887]     | 1        | 0.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1        | 0.94%   |
| TP-Link Archer T4U ver.3                                      | 1        | 0.94%   |
| TP-Link 802.11n NIC                                           | 1        | 0.94%   |
| TP-Link 802.11ac NIC                                          | 1        | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 1        | 0.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1        | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1        | 0.94%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1        | 0.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 1        | 0.94%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                        | 1        | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                    | 1        | 0.94%   |
| Realtek RTL8187 Wireless Adapter                              | 1        | 0.94%   |
| Realtek 8821CE PCIe 802.11ac Wireless Network Controller      | 1        | 0.94%   |
| Ralink RT2501/RT2573 Wireless Adapter                         | 1        | 0.94%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter             | 1        | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 105      | 59.32%  |
| Intel                 | 51       | 28.81%  |
| Broadcom              | 7        | 3.95%   |
| Qualcomm Atheros      | 3        | 1.69%   |
| Aquantia              | 3        | 1.69%   |
| Mellanox Technologies | 2        | 1.13%   |
| Google                | 2        | 1.13%   |
| Xiaomi                | 1        | 0.56%   |
| Samsung Electronics   | 1        | 0.56%   |
| Nvidia                | 1        | 0.56%   |
| Apple                 | 1        | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80       | 43.72%  |
| Realtek RTL8125 2.5GbE Controller                                 | 17       | 9.29%   |
| Intel Ethernet Controller I225-V                                  | 8        | 4.37%   |
| Intel I211 Gigabit Network Connection                             | 5        | 2.73%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 2.19%   |
| Intel Ethernet Connection (7) I219-V                              | 4        | 2.19%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.19%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 2.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 2.19%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.64%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.09%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2        | 1.09%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.09%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.09%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 1.09%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 1.09%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.55%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.55%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.55%   |
| Mellanox MT27520 Family [ConnectX-3 Pro]                          | 1        | 0.55%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1        | 0.55%   |
| Intel Ethernet Controller X550                                    | 1        | 0.55%   |
| Intel Ethernet Controller I226-V                                  | 1        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.55%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.55%   |
| Intel Ethernet Connection (10) I219-V                             | 1        | 0.55%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.55%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.55%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 163      | 61.51%  |
| WiFi     | 100      | 37.74%  |
| Modem    | 2        | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 129      | 72.47%  |
| WiFi     | 49       | 27.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 94       | 55.95%  |
| 2     | 60       | 35.71%  |
| 3     | 9        | 5.36%   |
| 0     | 4        | 2.38%   |
| 5     | 1        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 114      | 67.86%  |
| Yes  | 54       | 32.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 36       | 45.57%  |
| Realtek Semiconductor           | 8        | 10.13%  |
| Cambridge Silicon Radio         | 8        | 10.13%  |
| IMC Networks                    | 6        | 7.59%   |
| MediaTek                        | 5        | 6.33%   |
| ASUSTek Computer                | 5        | 6.33%   |
| TP-Link                         | 3        | 3.8%    |
| Qualcomm Atheros Communications | 3        | 3.8%    |
| Integrated System Solution      | 1        | 1.27%   |
| Foxconn / Hon Hai               | 1        | 1.27%   |
| Dynex                           | 1        | 1.27%   |
| Broadcom                        | 1        | 1.27%   |
| Apple                           | 1        | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                                  | 8        | 10.13%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 8        | 10.13%  |
| Intel Bluetooth wireless interface                       | 7        | 8.86%   |
| Intel AX201 Bluetooth                                    | 7        | 8.86%   |
| Intel AX200 Bluetooth                                    | 7        | 8.86%   |
| MediaTek Wireless_Device                                 | 5        | 6.33%   |
| Intel Bluetooth Device                                   | 5        | 6.33%   |
| Intel AX210 Bluetooth                                    | 4        | 5.06%   |
| IMC Networks Bluetooth Radio                             | 4        | 5.06%   |
| TP-Link UB500 Adapter                                    | 3        | 3.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 3        | 3.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3        | 3.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 3        | 3.8%    |
| Qualcomm Atheros  Bluetooth Device                       | 2        | 2.53%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 1.27%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 1.27%   |
| IMC Networks Wireless_Device                             | 1        | 1.27%   |
| IMC Networks BCM20702A0                                  | 1        | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1        | 1.27%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 1.27%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 1.27%   |
| ASUS BCM20702A0                                          | 1        | 1.27%   |
| ASUS ASUS USB-BT500                                      | 1        | 1.27%   |
| Apple Bluetooth Host Controller                          | 1        | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 112      | 38.49%  |
| AMD                                             | 67       | 23.02%  |
| Nvidia                                          | 64       | 21.99%  |
| C-Media Electronics                             | 7        | 2.41%   |
| Logitech                                        | 6        | 2.06%   |
| Texas Instruments                               | 3        | 1.03%   |
| GN Netcom                                       | 3        | 1.03%   |
| ASUSTek Computer                                | 3        | 1.03%   |
| VIA Technologies                                | 2        | 0.69%   |
| SteelSeries ApS                                 | 2        | 0.69%   |
| Giga-Byte Technology                            | 2        | 0.69%   |
| USB Audio                                       | 1        | 0.34%   |
| Trust                                           | 1        | 0.34%   |
| Tenx Technology                                 | 1        | 0.34%   |
| SAVITECH                                        | 1        | 0.34%   |
| Samson Technologies                             | 1        | 0.34%   |
| Realtek Semiconductor                           | 1        | 0.34%   |
| Razer USA                                       | 1        | 0.34%   |
| Nektar                                          | 1        | 0.34%   |
| Native Instruments                              | 1        | 0.34%   |
| Micro Star International                        | 1        | 0.34%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.34%   |
| Lenovo                                          | 1        | 0.34%   |
| KORG                                            | 1        | 0.34%   |
| JBL                                             | 1        | 0.34%   |
| ESS Technology                                  | 1        | 0.34%   |
| Creative Technology                             | 1        | 0.34%   |
| Creative Labs                                   | 1        | 0.34%   |
| Corsair                                         | 1        | 0.34%   |
| BEHRINGER International                         | 1        | 0.34%   |
| Astro Gaming                                    | 1        | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 16       | 4.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 14       | 4.05%   |
| AMD Starship/Matisse HD Audio Controller                                          | 14       | 4.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11       | 3.18%   |
| Intel Alder Lake-S HD Audio Controller                                            | 11       | 3.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 11       | 3.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11       | 3.18%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 10       | 2.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 9        | 2.6%    |
| Intel Cannon Lake PCH cAVS                                                        | 8        | 2.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 2.31%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 8        | 2.31%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 7        | 2.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7        | 2.02%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 6        | 1.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6        | 1.73%   |
| Intel 200 Series PCH HD Audio                                                     | 6        | 1.73%   |
| AMD FCH Azalia Controller                                                         | 6        | 1.73%   |
| Nvidia GM204 High Definition Audio Controller                                     | 5        | 1.45%   |
| Nvidia Audio device                                                               | 5        | 1.45%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 5        | 1.45%   |
| AMD Trinity HDMI Audio Controller                                                 | 5        | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4        | 1.16%   |
| Nvidia GA102 High Definition Audio Controller                                     | 4        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 1.16%   |
| Intel Comet Lake PCH-V cAVS                                                       | 4        | 1.16%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1                  | 4        | 1.16%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 4        | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 1.16%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.87%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3        | 0.87%   |
| Nvidia GK106 HDMI Audio Controller                                                | 3        | 0.87%   |
| Nvidia GA106 High Definition Audio Controller                                     | 3        | 0.87%   |
| Nvidia AD102 High Definition Audio Controller                                     | 3        | 0.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 0.87%   |
| C-Media Electronics CM108 Audio Controller                                        | 3        | 0.87%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 3        | 0.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Kingston                             | 17       | 22.97%  |
| Corsair                              | 10       | 13.51%  |
| G.Skill                              | 8        | 10.81%  |
| Unknown                              | 5        | 6.76%   |
| SK hynix                             | 5        | 6.76%   |
| Samsung Electronics                  | 5        | 6.76%   |
| Micron Technology                    | 5        | 6.76%   |
| Crucial                              | 4        | 5.41%   |
| GOODRAM                              | 2        | 2.7%    |
| Unknown (0x9801)                     | 1        | 1.35%   |
| Unifosa                              | 1        | 1.35%   |
| Transcend                            | 1        | 1.35%   |
| Ramaxel Technology                   | 1        | 1.35%   |
| Patriot Memory                       | 1        | 1.35%   |
| Lexar                                | 1        | 1.35%   |
| Juhor                                | 1        | 1.35%   |
| Hewlett-Packard                      | 1        | 1.35%   |
| Elpida                               | 1        | 1.35%   |
| Chun Well Technology Holding Limited | 1        | 1.35%   |
| Atermiter                            | 1        | 1.35%   |
| ASint Technology                     | 1        | 1.35%   |
| Unknown                              | 1        | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 2        | 2.5%    |
| Kingston RAM KF560C36-16 16GB DIMM 6000MT/s                | 2        | 2.5%    |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s           | 2        | 2.5%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s      | 2        | 2.5%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s        | 2        | 2.5%    |
| Unknown RAM Module 4GB DIMM SDRAM                          | 1        | 1.25%   |
| Unknown RAM Module 2GB DIMM DDR 533MT/s                    | 1        | 1.25%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 1        | 1.25%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                   | 1        | 1.25%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                   | 1        | 1.25%   |
| Unknown (0x9801) RAM Module 4GB DIMM DDR3 1334MT/s         | 1        | 1.25%   |
| Unifosa RAM HU524303EP0200 2GB DIMM DDR3 1333MT/s          | 1        | 1.25%   |
| Transcend RAM JM2666HLB-8G 8GB DIMM DDR4 2667MT/s          | 1        | 1.25%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s               | 1        | 1.25%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1        | 1.25%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s       | 1        | 1.25%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2400MT/s       | 1        | 1.25%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 1        | 1.25%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s        | 1        | 1.25%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s             | 1        | 1.25%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s        | 1        | 1.25%   |
| Samsung RAM M378A5244CB0-CTD 4GB DIMM DDR4 3334MT/s        | 1        | 1.25%   |
| Samsung RAM M378A5244CB0-CRC 4096MB DIMM DDR4 3066MT/s     | 1        | 1.25%   |
| Samsung RAM M378A1G44AB0-CWE 8GB DIMM DDR4 3200MT/s        | 1        | 1.25%   |
| Ramaxel RAM RMR1870EC58E9F1333 4GB DIMM DDR3 1333MT/s      | 1        | 1.25%   |
| Patriot Memory RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s | 1        | 1.25%   |
| Micron RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1        | 1.25%   |
| Micron RAM 4ATF51264AZ-3G2R1 4GB DIMM DDR4 3200MT/s        | 1        | 1.25%   |
| Micron RAM 18ASF1G72PZ-2G1A2 8GB DIMM DDR4 2400MT/s        | 1        | 1.25%   |
| Micron RAM 16ATF2G64AZ-3G2J1 16GB DIMM DDR4 3200MT/s       | 1        | 1.25%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s        | 1        | 1.25%   |
| Lexar RAM LD4AU008G-H3200GST 8GB DIMM DDR4 3200MT/s        | 1        | 1.25%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 1        | 1.25%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s        | 1        | 1.25%   |
| Kingston RAM KHX2400C11D3/4GX 4GB DIMM DDR3 2400MT/s       | 1        | 1.25%   |
| Kingston RAM KHX1866C10D3/ 8GB DIMM DDR3 1866MT/s          | 1        | 1.25%   |
| Kingston RAM KHX1600C9D3/4 4096MB DIMM DDR3 1600MT/s       | 1        | 1.25%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s        | 1        | 1.25%   |
| Kingston RAM KF556C40-16 16GB DIMM DDR5 5600MT/s           | 1        | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 32       | 46.38%  |
| DDR3    | 14       | 20.29%  |
| DDR5    | 13       | 18.84%  |
| SDRAM   | 5        | 7.25%   |
| DDR2    | 2        | 2.9%    |
| Unknown | 2        | 2.9%    |
| DDR     | 1        | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 60       | 92.31%  |
| SODIMM | 5        | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 26       | 36.62%  |
| 16384 | 18       | 25.35%  |
| 4096  | 12       | 16.9%   |
| 32768 | 8        | 11.27%  |
| 2048  | 5        | 7.04%   |
| 1024  | 2        | 2.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 11       | 15.07%  |
| 1600    | 9        | 12.33%  |
| 2400    | 5        | 6.85%   |
| 1333    | 5        | 6.85%   |
| 3600    | 4        | 5.48%   |
| 2667    | 4        | 5.48%   |
| 6000    | 3        | 4.11%   |
| 5600    | 3        | 4.11%   |
| 2133    | 3        | 4.11%   |
| 6400    | 2        | 2.74%   |
| 5808    | 2        | 2.74%   |
| 5200    | 2        | 2.74%   |
| 3866    | 2        | 2.74%   |
| 800     | 2        | 2.74%   |
| 4800    | 1        | 1.37%   |
| 4199    | 1        | 1.37%   |
| 3666    | 1        | 1.37%   |
| 3466    | 1        | 1.37%   |
| 3400    | 1        | 1.37%   |
| 3334    | 1        | 1.37%   |
| 3066    | 1        | 1.37%   |
| 2933    | 1        | 1.37%   |
| 2666    | 1        | 1.37%   |
| 1867    | 1        | 1.37%   |
| 1866    | 1        | 1.37%   |
| 1334    | 1        | 1.37%   |
| 1066    | 1        | 1.37%   |
| 667     | 1        | 1.37%   |
| 533     | 1        | 1.37%   |
| Unknown | 1        | 1.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 25%     |
| Hewlett-Packard     | 2        | 25%     |
| Seiko Epson         | 1        | 12.5%   |
| QinHeng Electronics | 1        | 12.5%   |
| Canon               | 1        | 12.5%   |
| Brother Industries  | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson ET-2820 Series | 1        | 12.5%   |
| Samsung SCX-3400 Series    | 1        | 12.5%   |
| Samsung CLX-3170 Series    | 1        | 12.5%   |
| QinHeng CH340S             | 1        | 12.5%   |
| HP DeskJet 960c            | 1        | 12.5%   |
| HP ColorLaserJet M253-M254 | 1        | 12.5%   |
| Canon TR4500 series        | 1        | 12.5%   |
| Brother MFC-9330CDW        | 1        | 12.5%   |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 14       | 43.75%  |
| Microsoft                   | 4        | 12.5%   |
| Apple                       | 4        | 12.5%   |
| Samsung Electronics         | 2        | 6.25%   |
| Razer USA                   | 1        | 3.13%   |
| Pixart Imaging              | 1        | 3.13%   |
| KYE Systems (Mouse Systems) | 1        | 3.13%   |
| Generalplus Technology      | 1        | 3.13%   |
| eMeet-200611                | 1        | 3.13%   |
| eMeet                       | 1        | 3.13%   |
| AVerMedia Technologies      | 1        | 3.13%   |
| ARC International           | 1        | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 5        | 15.15%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 3        | 9.09%   |
| Samsung Galaxy series, misc. (MTP mode)  | 2        | 6.06%   |
| Microsoft LifeCam HD-3000                | 2        | 6.06%   |
| Logitech BRIO Ultra HD Webcam            | 2        | 6.06%   |
| Razer USA Gaming Webcam [Kiyo]           | 1        | 3.03%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 1        | 3.03%   |
| Microsoft LifeCam NX-6000                | 1        | 3.03%   |
| Microsoft LifeCam HD-5000                | 1        | 3.03%   |
| Logitech Webcam Pro 9000                 | 1        | 3.03%   |
| Logitech Webcam C170                     | 1        | 3.03%   |
| Logitech StreamCam                       | 1        | 3.03%   |
| Logitech QuickCam Pro 9000               | 1        | 3.03%   |
| Logitech HD Webcam C615                  | 1        | 3.03%   |
| Logitech HD Pro Webcam C920              | 1        | 3.03%   |
| Logitech Brio 500                        | 1        | 3.03%   |
| KYE Systems (Mouse Systems) PC-W3 Camera | 1        | 3.03%   |
| Generalplus GENERAL WEBCAM               | 1        | 3.03%   |
| eMeet-200611 eMeet Nova                  | 1        | 3.03%   |
| eMeet HD Webcam C960                     | 1        | 3.03%   |
| AVerMedia Live Streamer CAM 313          | 1        | 3.03%   |
| ARC International Camera                 | 1        | 3.03%   |
| Apple iPod Touch 2.Gen                   | 1        | 3.03%   |
| Apple iPad 2                             | 1        | 3.03%   |

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
| 0     | 145      | 85.29%  |
| 1     | 24       | 14.12%  |
| 2     | 1        | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 8        | 34.78%  |
| Unassigned class         | 5        | 21.74%  |
| Graphics card            | 5        | 21.74%  |
| Communication controller | 2        | 8.7%    |
| Bluetooth                | 2        | 8.7%    |
| Multimedia controller    | 1        | 4.35%   |

