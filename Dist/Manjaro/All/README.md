Manjaro - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Manjaro.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro/Desktop/README.md) and [notebooks](/Dist/Manjaro/Notebook/README.md).

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

Total: 11081

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | N14xWU                      | Notebook    | [0460984dea](https://linux-hardware.org/?probe=0460984dea) | Jan 02, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | Notebook    | [095d9cbf7e](https://linux-hardware.org/?probe=095d9cbf7e) | Jan 01, 2024 |
| Dell          | Latitude 7490               | Notebook    | [efab03db5f](https://linux-hardware.org/?probe=efab03db5f) | Jan 01, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [769bd9153a](https://linux-hardware.org/?probe=769bd9153a) | Jan 01, 2024 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [9c99c1bf71](https://linux-hardware.org/?probe=9c99c1bf71) | Dec 31, 2023 |
| ASRock        | B75M-DGS                    | Desktop     | [3a2df88d60](https://linux-hardware.org/?probe=3a2df88d60) | Dec 31, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | Desktop     | [080172526c](https://linux-hardware.org/?probe=080172526c) | Dec 31, 2023 |
| Lenovo        | ThinkPad X390 20Q0004VUS    | Notebook    | [4bd6b36cd6](https://linux-hardware.org/?probe=4bd6b36cd6) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4YE0... | Notebook    | [74d75dc18d](https://linux-hardware.org/?probe=74d75dc18d) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4UD0... | Notebook    | [0305a2f3cf](https://linux-hardware.org/?probe=0305a2f3cf) | Dec 30, 2023 |
| Dell          | Latitude E7440              | Notebook    | [d9fb6a9ead](https://linux-hardware.org/?probe=d9fb6a9ead) | Dec 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [394c35d74b](https://linux-hardware.org/?probe=394c35d74b) | Dec 30, 2023 |
| HP            | 8949 11                     | Desktop     | [1add0bc0e2](https://linux-hardware.org/?probe=1add0bc0e2) | Dec 30, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [5cfb3467bc](https://linux-hardware.org/?probe=5cfb3467bc) | Dec 29, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [2f24e45b02](https://linux-hardware.org/?probe=2f24e45b02) | Dec 29, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [0daa9bd3eb](https://linux-hardware.org/?probe=0daa9bd3eb) | Dec 29, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [751429a259](https://linux-hardware.org/?probe=751429a259) | Dec 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [d5ac5fcf72](https://linux-hardware.org/?probe=d5ac5fcf72) | Dec 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [990d141701](https://linux-hardware.org/?probe=990d141701) | Dec 28, 2023 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [3bf93539f3](https://linux-hardware.org/?probe=3bf93539f3) | Dec 28, 2023 |
| Dell          | Latitude 7490               | Notebook    | [7eab9f671e](https://linux-hardware.org/?probe=7eab9f671e) | Dec 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [32ce52498b](https://linux-hardware.org/?probe=32ce52498b) | Dec 28, 2023 |
| Google        | Dratini                     | Notebook    | [a81971bf37](https://linux-hardware.org/?probe=a81971bf37) | Dec 28, 2023 |
| HP            | ProBook 6470b               | Notebook    | [60858223c4](https://linux-hardware.org/?probe=60858223c4) | Dec 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [313a669de8](https://linux-hardware.org/?probe=313a669de8) | Dec 27, 2023 |
| Panasonic     | FZ-M1CCA17E3                | Notebook    | [c55632d60a](https://linux-hardware.org/?probe=c55632d60a) | Dec 27, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [c62c257897](https://linux-hardware.org/?probe=c62c257897) | Dec 27, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [99dfa98b06](https://linux-hardware.org/?probe=99dfa98b06) | Dec 27, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [87efb02531](https://linux-hardware.org/?probe=87efb02531) | Dec 27, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [969aa3e243](https://linux-hardware.org/?probe=969aa3e243) | Dec 26, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [0260c1a342](https://linux-hardware.org/?probe=0260c1a342) | Dec 26, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [25e443386a](https://linux-hardware.org/?probe=25e443386a) | Dec 26, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [97f532d3c8](https://linux-hardware.org/?probe=97f532d3c8) | Dec 26, 2023 |
| Dell          | Precision 7520              | Notebook    | [e4390e22b6](https://linux-hardware.org/?probe=e4390e22b6) | Dec 26, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [2013c4457a](https://linux-hardware.org/?probe=2013c4457a) | Dec 26, 2023 |
| Wiltronic     | MAGNUS PLUS                 | Tablet      | [774cf36756](https://linux-hardware.org/?probe=774cf36756) | Dec 26, 2023 |
| ASRock        | X670E Taichi                | Desktop     | [281602cb0e](https://linux-hardware.org/?probe=281602cb0e) | Dec 26, 2023 |
| MECHREVO      | Jiaolong16Q Series GM6BG... | Notebook    | [900da4b920](https://linux-hardware.org/?probe=900da4b920) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [522209b304](https://linux-hardware.org/?probe=522209b304) | Dec 26, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5HM0... | Notebook    | [79bfce6143](https://linux-hardware.org/?probe=79bfce6143) | Dec 25, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [9e99d63708](https://linux-hardware.org/?probe=9e99d63708) | Dec 25, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [9f369b34fa](https://linux-hardware.org/?probe=9f369b34fa) | Dec 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ef5699b685](https://linux-hardware.org/?probe=ef5699b685) | Dec 24, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [cccb18ead9](https://linux-hardware.org/?probe=cccb18ead9) | Dec 24, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [d845a3492b](https://linux-hardware.org/?probe=d845a3492b) | Dec 24, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [a6e1fc3b29](https://linux-hardware.org/?probe=a6e1fc3b29) | Dec 24, 2023 |
| MSI           | PRO B650-S WIFI             | Desktop     | [c084478d6e](https://linux-hardware.org/?probe=c084478d6e) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [03b1209523](https://linux-hardware.org/?probe=03b1209523) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b7f3ca9ba4](https://linux-hardware.org/?probe=b7f3ca9ba4) | Dec 23, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [6cc304ea54](https://linux-hardware.org/?probe=6cc304ea54) | Dec 23, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [fe19f4de86](https://linux-hardware.org/?probe=fe19f4de86) | Dec 23, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [a72824a48c](https://linux-hardware.org/?probe=a72824a48c) | Dec 23, 2023 |
| MSI           | B560M PRO                   | Desktop     | [3885df62ab](https://linux-hardware.org/?probe=3885df62ab) | Dec 23, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [155e0f1c37](https://linux-hardware.org/?probe=155e0f1c37) | Dec 22, 2023 |
| ASUSTek       | Maximus VI GENE             | Desktop     | [178aab1062](https://linux-hardware.org/?probe=178aab1062) | Dec 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [e20360557a](https://linux-hardware.org/?probe=e20360557a) | Dec 22, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [52af26d8a1](https://linux-hardware.org/?probe=52af26d8a1) | Dec 21, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [62624ca97b](https://linux-hardware.org/?probe=62624ca97b) | Dec 21, 2023 |
| Lenovo        | ThinkPad X201 3680WXT       | Notebook    | [a6e0d33afd](https://linux-hardware.org/?probe=a6e0d33afd) | Dec 21, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [8fc737975c](https://linux-hardware.org/?probe=8fc737975c) | Dec 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [98298e164f](https://linux-hardware.org/?probe=98298e164f) | Dec 20, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [963de967ae](https://linux-hardware.org/?probe=963de967ae) | Dec 19, 2023 |
| HP            | 83E0                        | Desktop     | [8f41483d26](https://linux-hardware.org/?probe=8f41483d26) | Dec 19, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [df369cf5be](https://linux-hardware.org/?probe=df369cf5be) | Dec 19, 2023 |
| Lenovo        | 3704 SDK0K17763 WIN 1801... | Desktop     | [9a2472e628](https://linux-hardware.org/?probe=9a2472e628) | Dec 19, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [8939d0afc4](https://linux-hardware.org/?probe=8939d0afc4) | Dec 19, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6fe6e99364](https://linux-hardware.org/?probe=6fe6e99364) | Dec 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS19500     | Notebook    | [7067fb02ed](https://linux-hardware.org/?probe=7067fb02ed) | Dec 18, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7b5e55e475](https://linux-hardware.org/?probe=7b5e55e475) | Dec 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [448a2dec7d](https://linux-hardware.org/?probe=448a2dec7d) | Dec 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ebfec06632](https://linux-hardware.org/?probe=ebfec06632) | Dec 17, 2023 |
| Lenovo        | ThinkPad T460 20FNS11S00    | Notebook    | [901a636942](https://linux-hardware.org/?probe=901a636942) | Dec 17, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [b935091ecd](https://linux-hardware.org/?probe=b935091ecd) | Dec 17, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [14b5a5a3ca](https://linux-hardware.org/?probe=14b5a5a3ca) | Dec 17, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [4e47d91bc7](https://linux-hardware.org/?probe=4e47d91bc7) | Dec 17, 2023 |
| Lenovo        | ThinkPad T460 20FNS11S00    | Notebook    | [34acff5fa8](https://linux-hardware.org/?probe=34acff5fa8) | Dec 17, 2023 |
| Lenovo        | ThinkPad T460 20FNS11S00    | Notebook    | [8a344f72ea](https://linux-hardware.org/?probe=8a344f72ea) | Dec 17, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [78ef6792a1](https://linux-hardware.org/?probe=78ef6792a1) | Dec 16, 2023 |
| HP            | Stream Laptop 14-DS0xxx     | Notebook    | [3e26902ac1](https://linux-hardware.org/?probe=3e26902ac1) | Dec 15, 2023 |
| ASRock        | 760GM-HDV                   | Desktop     | [c1403f5d52](https://linux-hardware.org/?probe=c1403f5d52) | Dec 15, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [ee1bdd536f](https://linux-hardware.org/?probe=ee1bdd536f) | Dec 15, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fecb896f9f](https://linux-hardware.org/?probe=fecb896f9f) | Dec 14, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [165e16505d](https://linux-hardware.org/?probe=165e16505d) | Dec 14, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [ebfb65701f](https://linux-hardware.org/?probe=ebfb65701f) | Dec 14, 2023 |
| Acer          | TMP645-M                    | Notebook    | [55c3db256a](https://linux-hardware.org/?probe=55c3db256a) | Dec 13, 2023 |
| GEO           | GEOBOOK 2E                  | Notebook    | [86b33e33ca](https://linux-hardware.org/?probe=86b33e33ca) | Dec 12, 2023 |
| GEO           | GEOBOOK 2E                  | Notebook    | [cac69d7624](https://linux-hardware.org/?probe=cac69d7624) | Dec 12, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [38b83e3350](https://linux-hardware.org/?probe=38b83e3350) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [25b995fdda](https://linux-hardware.org/?probe=25b995fdda) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [52ffec69ce](https://linux-hardware.org/?probe=52ffec69ce) | Dec 12, 2023 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [514227865f](https://linux-hardware.org/?probe=514227865f) | Dec 12, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [2cfceea8dc](https://linux-hardware.org/?probe=2cfceea8dc) | Dec 12, 2023 |
| ASUSTek       | X550VB                      | Notebook    | [cfc8172838](https://linux-hardware.org/?probe=cfc8172838) | Dec 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [f932ad9551](https://linux-hardware.org/?probe=f932ad9551) | Dec 11, 2023 |
| Lenovo        | ThinkPad T470s 20HF005NU... | Notebook    | [0d9a5839df](https://linux-hardware.org/?probe=0d9a5839df) | Dec 11, 2023 |
| Gigabyte      | Z270-Gaming K3 2017-06-1... | Desktop     | [5292573e8d](https://linux-hardware.org/?probe=5292573e8d) | Dec 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [e7febd26d4](https://linux-hardware.org/?probe=e7febd26d4) | Dec 10, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [2ba6a00229](https://linux-hardware.org/?probe=2ba6a00229) | Dec 10, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [d906394ed7](https://linux-hardware.org/?probe=d906394ed7) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [098d790720](https://linux-hardware.org/?probe=098d790720) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [090ebbd9dd](https://linux-hardware.org/?probe=090ebbd9dd) | Dec 10, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [581807905e](https://linux-hardware.org/?probe=581807905e) | Dec 10, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [b3f7b8b30a](https://linux-hardware.org/?probe=b3f7b8b30a) | Dec 09, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [4684efbcaa](https://linux-hardware.org/?probe=4684efbcaa) | Dec 09, 2023 |
| Samsung       | R428/P428                   | Notebook    | [bcfc7ba90f](https://linux-hardware.org/?probe=bcfc7ba90f) | Dec 09, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [47aafe0845](https://linux-hardware.org/?probe=47aafe0845) | Dec 08, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [f7f70db230](https://linux-hardware.org/?probe=f7f70db230) | Dec 08, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [7fd1a6be19](https://linux-hardware.org/?probe=7fd1a6be19) | Dec 08, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [eac155f5e6](https://linux-hardware.org/?probe=eac155f5e6) | Dec 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [c652e80145](https://linux-hardware.org/?probe=c652e80145) | Dec 08, 2023 |
| Dell          | Latitude 7410               | Notebook    | [5d528f2b74](https://linux-hardware.org/?probe=5d528f2b74) | Dec 08, 2023 |
| Dell          | Latitude 7400               | Notebook    | [692f8c13ff](https://linux-hardware.org/?probe=692f8c13ff) | Dec 07, 2023 |
| Alienware     | m18 R1                      | Notebook    | [79c8580eb9](https://linux-hardware.org/?probe=79c8580eb9) | Dec 07, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [7606deffc4](https://linux-hardware.org/?probe=7606deffc4) | Dec 07, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [650771c55d](https://linux-hardware.org/?probe=650771c55d) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [1dd3b89bd1](https://linux-hardware.org/?probe=1dd3b89bd1) | Dec 07, 2023 |
| Alienware     | m18 R1                      | Notebook    | [4a4c2cec97](https://linux-hardware.org/?probe=4a4c2cec97) | Dec 06, 2023 |
| HP            | 83E0                        | Desktop     | [a4266f2a5e](https://linux-hardware.org/?probe=a4266f2a5e) | Dec 06, 2023 |
| Lenovo        | ThinkPad X220 4290JN8       | Notebook    | [f9cec63bf8](https://linux-hardware.org/?probe=f9cec63bf8) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [7d7cf8fd3d](https://linux-hardware.org/?probe=7d7cf8fd3d) | Dec 06, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [5f29bdfad1](https://linux-hardware.org/?probe=5f29bdfad1) | Dec 05, 2023 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | Notebook    | [e238c1edb9](https://linux-hardware.org/?probe=e238c1edb9) | Dec 05, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [d5ee40d605](https://linux-hardware.org/?probe=d5ee40d605) | Dec 05, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [1d99a563c9](https://linux-hardware.org/?probe=1d99a563c9) | Dec 05, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [3a8de1659a](https://linux-hardware.org/?probe=3a8de1659a) | Dec 05, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [fe06cb32bc](https://linux-hardware.org/?probe=fe06cb32bc) | Dec 05, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [362161fd73](https://linux-hardware.org/?probe=362161fd73) | Dec 04, 2023 |
| Lenovo        | ThinkPad L590 20Q7001CGE    | Notebook    | [03b128fbc9](https://linux-hardware.org/?probe=03b128fbc9) | Dec 04, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [a7dd623bb6](https://linux-hardware.org/?probe=a7dd623bb6) | Dec 04, 2023 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [aeae361474](https://linux-hardware.org/?probe=aeae361474) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [452f677f7f](https://linux-hardware.org/?probe=452f677f7f) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | Notebook    | [e6f0d9a3ae](https://linux-hardware.org/?probe=e6f0d9a3ae) | Dec 03, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [8b11ad9f77](https://linux-hardware.org/?probe=8b11ad9f77) | Dec 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [3a6eb27098](https://linux-hardware.org/?probe=3a6eb27098) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ae8ecce4bd](https://linux-hardware.org/?probe=ae8ecce4bd) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0b017377f1](https://linux-hardware.org/?probe=0b017377f1) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [0338afa4db](https://linux-hardware.org/?probe=0338afa4db) | Dec 01, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [940148ec06](https://linux-hardware.org/?probe=940148ec06) | Dec 01, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [fd46463395](https://linux-hardware.org/?probe=fd46463395) | Dec 01, 2023 |
| Dell          | Precision 7520              | Notebook    | [3651203e23](https://linux-hardware.org/?probe=3651203e23) | Dec 01, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [0a9f2b8eae](https://linux-hardware.org/?probe=0a9f2b8eae) | Dec 01, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [dab90c4a4f](https://linux-hardware.org/?probe=dab90c4a4f) | Dec 01, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [3953185e28](https://linux-hardware.org/?probe=3953185e28) | Dec 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [cd167c532c](https://linux-hardware.org/?probe=cd167c532c) | Dec 01, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [bb6640572b](https://linux-hardware.org/?probe=bb6640572b) | Nov 30, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [bd0ae5856a](https://linux-hardware.org/?probe=bd0ae5856a) | Nov 30, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [e9e1177170](https://linux-hardware.org/?probe=e9e1177170) | Nov 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S4XW00    | Notebook    | [13a434ff63](https://linux-hardware.org/?probe=13a434ff63) | Nov 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [a12db959e6](https://linux-hardware.org/?probe=a12db959e6) | Nov 30, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [a139e1830c](https://linux-hardware.org/?probe=a139e1830c) | Nov 29, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [da1096c1ed](https://linux-hardware.org/?probe=da1096c1ed) | Nov 29, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [10c0db94d1](https://linux-hardware.org/?probe=10c0db94d1) | Nov 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [d0c3893980](https://linux-hardware.org/?probe=d0c3893980) | Nov 29, 2023 |
| Notebook      | P7xxTM                      | Notebook    | [d1a0cf0f45](https://linux-hardware.org/?probe=d1a0cf0f45) | Nov 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [6ccad5b430](https://linux-hardware.org/?probe=6ccad5b430) | Nov 28, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [bd3a1b9c9a](https://linux-hardware.org/?probe=bd3a1b9c9a) | Nov 28, 2023 |
| Gigabyte      | A55M-DS2                    | Desktop     | [bb5c7bef3f](https://linux-hardware.org/?probe=bb5c7bef3f) | Nov 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [77e8b3479a](https://linux-hardware.org/?probe=77e8b3479a) | Nov 27, 2023 |
| HP            | 2820h                       | Desktop     | [e9bdfab0be](https://linux-hardware.org/?probe=e9bdfab0be) | Nov 27, 2023 |
| HP            | 2B36                        | Desktop     | [3e8b681ec7](https://linux-hardware.org/?probe=3e8b681ec7) | Nov 27, 2023 |
| TECNO Mobi... | MEGABOOK T14TA              | Notebook    | [602741eba3](https://linux-hardware.org/?probe=602741eba3) | Nov 26, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [bb98eb3ce9](https://linux-hardware.org/?probe=bb98eb3ce9) | Nov 26, 2023 |
| Fujitsu       | LIFEBOOK E4511              | Notebook    | [a849237ab7](https://linux-hardware.org/?probe=a849237ab7) | Nov 26, 2023 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [8c3b31ac03](https://linux-hardware.org/?probe=8c3b31ac03) | Nov 26, 2023 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [9285954ed6](https://linux-hardware.org/?probe=9285954ed6) | Nov 26, 2023 |
| Shenzhen W... | Alder Lake N                | Notebook    | [0cd16ad752](https://linux-hardware.org/?probe=0cd16ad752) | Nov 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6448093265](https://linux-hardware.org/?probe=6448093265) | Nov 25, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [a5b04f6fdb](https://linux-hardware.org/?probe=a5b04f6fdb) | Nov 24, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [b11d29c96b](https://linux-hardware.org/?probe=b11d29c96b) | Nov 24, 2023 |
| MSI           | B550M PRO                   | Desktop     | [e834bc66b9](https://linux-hardware.org/?probe=e834bc66b9) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [2a14b62cf5](https://linux-hardware.org/?probe=2a14b62cf5) | Nov 24, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [5d6b4323e5](https://linux-hardware.org/?probe=5d6b4323e5) | Nov 24, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [2a29f65958](https://linux-hardware.org/?probe=2a29f65958) | Nov 24, 2023 |
| Gateway       | P-6301                      | Notebook    | [d16a00d10d](https://linux-hardware.org/?probe=d16a00d10d) | Nov 24, 2023 |
| Gateway       | P-6301                      | Notebook    | [d9c74ac6f8](https://linux-hardware.org/?probe=d9c74ac6f8) | Nov 24, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [1dea02682f](https://linux-hardware.org/?probe=1dea02682f) | Nov 24, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ee82d7417c](https://linux-hardware.org/?probe=ee82d7417c) | Nov 23, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [6115c9c76e](https://linux-hardware.org/?probe=6115c9c76e) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S9GM01    | Notebook    | [9c8590e300](https://linux-hardware.org/?probe=9c8590e300) | Nov 23, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [dea4d9231a](https://linux-hardware.org/?probe=dea4d9231a) | Nov 23, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [6f740bc140](https://linux-hardware.org/?probe=6f740bc140) | Nov 22, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [01d429e284](https://linux-hardware.org/?probe=01d429e284) | Nov 22, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | Desktop     | [bc11e1264c](https://linux-hardware.org/?probe=bc11e1264c) | Nov 22, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [6791592808](https://linux-hardware.org/?probe=6791592808) | Nov 22, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [69d5dcd30b](https://linux-hardware.org/?probe=69d5dcd30b) | Nov 22, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [40b88a9c74](https://linux-hardware.org/?probe=40b88a9c74) | Nov 21, 2023 |
| Google        | Pujjo                       | Notebook    | [a196388078](https://linux-hardware.org/?probe=a196388078) | Nov 21, 2023 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [cb6bad64b4](https://linux-hardware.org/?probe=cb6bad64b4) | Nov 21, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [eb4b335400](https://linux-hardware.org/?probe=eb4b335400) | Nov 21, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [463f733cdb](https://linux-hardware.org/?probe=463f733cdb) | Nov 20, 2023 |
| GEO           | GeoFlex 110                 | Convertible | [48186c506a](https://linux-hardware.org/?probe=48186c506a) | Nov 20, 2023 |
| MSI           | Thin GF63 12VF              | Notebook    | [ca1a9ef401](https://linux-hardware.org/?probe=ca1a9ef401) | Nov 20, 2023 |
| GEO           | GeoFlex 110                 | Convertible | [cbb890150c](https://linux-hardware.org/?probe=cbb890150c) | Nov 20, 2023 |
| GEO           | GeoFlex 110                 | Convertible | [f8965dd876](https://linux-hardware.org/?probe=f8965dd876) | Nov 20, 2023 |
| Dell          | 0WPMFG A00                  | Desktop     | [9cf9520fc3](https://linux-hardware.org/?probe=9cf9520fc3) | Nov 20, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [828da99472](https://linux-hardware.org/?probe=828da99472) | Nov 20, 2023 |
| Alurin        | ALU-BAR-R555-000-156        | Notebook    | [ce453601f1](https://linux-hardware.org/?probe=ce453601f1) | Nov 19, 2023 |
| HP            | Pavilion dv6                | Notebook    | [15c38c7e03](https://linux-hardware.org/?probe=15c38c7e03) | Nov 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [b53d35a567](https://linux-hardware.org/?probe=b53d35a567) | Nov 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [9fd0ad28e8](https://linux-hardware.org/?probe=9fd0ad28e8) | Nov 19, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [7a4e5e7709](https://linux-hardware.org/?probe=7a4e5e7709) | Nov 19, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [78dac027a1](https://linux-hardware.org/?probe=78dac027a1) | Nov 19, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [b3b8fff6bb](https://linux-hardware.org/?probe=b3b8fff6bb) | Nov 19, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [f67560f762](https://linux-hardware.org/?probe=f67560f762) | Nov 19, 2023 |
| HP            | Laptop 15-ef3xxx            | Notebook    | [196040012f](https://linux-hardware.org/?probe=196040012f) | Nov 18, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [3ce3a10b05](https://linux-hardware.org/?probe=3ce3a10b05) | Nov 18, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | Desktop     | [5368b237d8](https://linux-hardware.org/?probe=5368b237d8) | Nov 18, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [ece45e3b1c](https://linux-hardware.org/?probe=ece45e3b1c) | Nov 18, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [1f7e5feb84](https://linux-hardware.org/?probe=1f7e5feb84) | Nov 17, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [01ea5c9a87](https://linux-hardware.org/?probe=01ea5c9a87) | Nov 17, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [fa0b8c4a6a](https://linux-hardware.org/?probe=fa0b8c4a6a) | Nov 17, 2023 |
| Lenovo        | SHARKBAY 31900059 STD       | Desktop     | [7af93dbd28](https://linux-hardware.org/?probe=7af93dbd28) | Nov 17, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [e57d2d64f5](https://linux-hardware.org/?probe=e57d2d64f5) | Nov 17, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [75009bf512](https://linux-hardware.org/?probe=75009bf512) | Nov 17, 2023 |
| Samsung       | 730QED                      | Convertible | [5942a94e2d](https://linux-hardware.org/?probe=5942a94e2d) | Nov 16, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [492ee4603f](https://linux-hardware.org/?probe=492ee4603f) | Nov 15, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c4db182f7c](https://linux-hardware.org/?probe=c4db182f7c) | Nov 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1f39069a7f](https://linux-hardware.org/?probe=1f39069a7f) | Nov 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [90f5f3a274](https://linux-hardware.org/?probe=90f5f3a274) | Nov 14, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [3394acc120](https://linux-hardware.org/?probe=3394acc120) | Nov 14, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [79fb5c8b87](https://linux-hardware.org/?probe=79fb5c8b87) | Nov 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [a09eca53d5](https://linux-hardware.org/?probe=a09eca53d5) | Nov 14, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [fac1d1b119](https://linux-hardware.org/?probe=fac1d1b119) | Nov 14, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [a5def4d720](https://linux-hardware.org/?probe=a5def4d720) | Nov 14, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [f29ef35eec](https://linux-hardware.org/?probe=f29ef35eec) | Nov 13, 2023 |
| Samsung       | 950QED                      | Convertible | [8fde5ad518](https://linux-hardware.org/?probe=8fde5ad518) | Nov 13, 2023 |
| Timi          | Mi Laptop Pro 15 2020       | Notebook    | [ade278e9c7](https://linux-hardware.org/?probe=ade278e9c7) | Nov 13, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [8599ff1b2c](https://linux-hardware.org/?probe=8599ff1b2c) | Nov 13, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [08f1651d1f](https://linux-hardware.org/?probe=08f1651d1f) | Nov 12, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [56107ca4c0](https://linux-hardware.org/?probe=56107ca4c0) | Nov 12, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [87ddc0384e](https://linux-hardware.org/?probe=87ddc0384e) | Nov 11, 2023 |
| Acer          | Spin SP314-21               | Convertible | [62418c922d](https://linux-hardware.org/?probe=62418c922d) | Nov 11, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [bcbad28ab7](https://linux-hardware.org/?probe=bcbad28ab7) | Nov 11, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [c9f63fc134](https://linux-hardware.org/?probe=c9f63fc134) | Nov 11, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [4c87f0ac2c](https://linux-hardware.org/?probe=4c87f0ac2c) | Nov 10, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [2b545ce55f](https://linux-hardware.org/?probe=2b545ce55f) | Nov 10, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [238ea043b4](https://linux-hardware.org/?probe=238ea043b4) | Nov 10, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [b7f860630b](https://linux-hardware.org/?probe=b7f860630b) | Nov 10, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [0de73c41cd](https://linux-hardware.org/?probe=0de73c41cd) | Nov 10, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [6c0d3672d5](https://linux-hardware.org/?probe=6c0d3672d5) | Nov 10, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [0be0ae7171](https://linux-hardware.org/?probe=0be0ae7171) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c59084f5fe](https://linux-hardware.org/?probe=c59084f5fe) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [0cdc1967cc](https://linux-hardware.org/?probe=0cdc1967cc) | Nov 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [9bb56dd3fd](https://linux-hardware.org/?probe=9bb56dd3fd) | Nov 09, 2023 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [10234424e1](https://linux-hardware.org/?probe=10234424e1) | Nov 09, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [14438106c9](https://linux-hardware.org/?probe=14438106c9) | Nov 09, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [9f34bb8f83](https://linux-hardware.org/?probe=9f34bb8f83) | Nov 09, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [fc8b4307d1](https://linux-hardware.org/?probe=fc8b4307d1) | Nov 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [58c681b475](https://linux-hardware.org/?probe=58c681b475) | Nov 09, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [4a82e665de](https://linux-hardware.org/?probe=4a82e665de) | Nov 08, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8ba89e650a](https://linux-hardware.org/?probe=8ba89e650a) | Nov 08, 2023 |
| Olivetti      | P55-AEU-323-4G320           | Notebook    | [5d53de5c7d](https://linux-hardware.org/?probe=5d53de5c7d) | Nov 08, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [2fb76b07c1](https://linux-hardware.org/?probe=2fb76b07c1) | Nov 08, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [da358e24b6](https://linux-hardware.org/?probe=da358e24b6) | Nov 07, 2023 |
| HP            | 158B                        | Desktop     | [b8bd2429fa](https://linux-hardware.org/?probe=b8bd2429fa) | Nov 07, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [895fc6adb6](https://linux-hardware.org/?probe=895fc6adb6) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [5a5dbd719b](https://linux-hardware.org/?probe=5a5dbd719b) | Nov 07, 2023 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [fc34295ec7](https://linux-hardware.org/?probe=fc34295ec7) | Nov 07, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [d847f42603](https://linux-hardware.org/?probe=d847f42603) | Nov 07, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [752c83c717](https://linux-hardware.org/?probe=752c83c717) | Nov 07, 2023 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [90b1049e2a](https://linux-hardware.org/?probe=90b1049e2a) | Nov 07, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [61fdbe9ec2](https://linux-hardware.org/?probe=61fdbe9ec2) | Nov 07, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [ed6ede63bc](https://linux-hardware.org/?probe=ed6ede63bc) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [7433f93679](https://linux-hardware.org/?probe=7433f93679) | Nov 07, 2023 |
| HP            | 8053                        | Desktop     | [c46468ecb6](https://linux-hardware.org/?probe=c46468ecb6) | Nov 07, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [09b818e1d3](https://linux-hardware.org/?probe=09b818e1d3) | Nov 07, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [437f0962bf](https://linux-hardware.org/?probe=437f0962bf) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e149cb0865](https://linux-hardware.org/?probe=e149cb0865) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [94fdbbd7bd](https://linux-hardware.org/?probe=94fdbbd7bd) | Nov 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [5fafb134cf](https://linux-hardware.org/?probe=5fafb134cf) | Nov 06, 2023 |
| Dell          | Precision M4800             | Notebook    | [e67352eb0f](https://linux-hardware.org/?probe=e67352eb0f) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8e3e7668cf](https://linux-hardware.org/?probe=8e3e7668cf) | Nov 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7152c7ed2c](https://linux-hardware.org/?probe=7152c7ed2c) | Nov 05, 2023 |
| HP            | 530                         | Notebook    | [710ba89827](https://linux-hardware.org/?probe=710ba89827) | Nov 05, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [034b113ac8](https://linux-hardware.org/?probe=034b113ac8) | Nov 05, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [a424739d4f](https://linux-hardware.org/?probe=a424739d4f) | Nov 05, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [3f295082ce](https://linux-hardware.org/?probe=3f295082ce) | Nov 05, 2023 |
| HP            | 1998                        | Desktop     | [d454314b77](https://linux-hardware.org/?probe=d454314b77) | Nov 05, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bdd24f60d2](https://linux-hardware.org/?probe=bdd24f60d2) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [f45893cbf7](https://linux-hardware.org/?probe=f45893cbf7) | Nov 05, 2023 |
| MSI           | H110I PRO                   | Desktop     | [c335c71c4b](https://linux-hardware.org/?probe=c335c71c4b) | Nov 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [8efb96e5d7](https://linux-hardware.org/?probe=8efb96e5d7) | Nov 04, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [8841ab599e](https://linux-hardware.org/?probe=8841ab599e) | Nov 04, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [e6459bb42f](https://linux-hardware.org/?probe=e6459bb42f) | Nov 04, 2023 |
| MSI           | B560M PRO                   | Desktop     | [903907b7c0](https://linux-hardware.org/?probe=903907b7c0) | Nov 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5ff7f9b284](https://linux-hardware.org/?probe=5ff7f9b284) | Nov 04, 2023 |
| Lenovo        | 317E NOK                    | Desktop     | [1d038af880](https://linux-hardware.org/?probe=1d038af880) | Nov 04, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [f0354d2416](https://linux-hardware.org/?probe=f0354d2416) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [798cba826c](https://linux-hardware.org/?probe=798cba826c) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c601304f7](https://linux-hardware.org/?probe=2c601304f7) | Nov 04, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [ded1d73643](https://linux-hardware.org/?probe=ded1d73643) | Nov 03, 2023 |
| HP            | 0B54h D                     | Desktop     | [574e5fd946](https://linux-hardware.org/?probe=574e5fd946) | Nov 03, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [44890192a1](https://linux-hardware.org/?probe=44890192a1) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2aa4f1a7f7](https://linux-hardware.org/?probe=2aa4f1a7f7) | Nov 03, 2023 |
| ASUSTek       | PRIME H770-PLUS D4          | Desktop     | [62645c6b56](https://linux-hardware.org/?probe=62645c6b56) | Nov 02, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [f07206a75c](https://linux-hardware.org/?probe=f07206a75c) | Nov 02, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | Notebook    | [4d3101d9f8](https://linux-hardware.org/?probe=4d3101d9f8) | Nov 02, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [476a922e2f](https://linux-hardware.org/?probe=476a922e2f) | Nov 02, 2023 |
| MSI           | B560M PRO                   | Desktop     | [adf6c161fa](https://linux-hardware.org/?probe=adf6c161fa) | Nov 02, 2023 |
| Fujitsu       | LIFEBOOK T937               | Convertible | [530a390355](https://linux-hardware.org/?probe=530a390355) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480 20L60017UK    | Notebook    | [e8b030e97f](https://linux-hardware.org/?probe=e8b030e97f) | Nov 02, 2023 |
| Gigabyte      | AORUS 17G KD                | Notebook    | [ac471f8580](https://linux-hardware.org/?probe=ac471f8580) | Nov 02, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [fffa5fb420](https://linux-hardware.org/?probe=fffa5fb420) | Nov 02, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | Notebook    | [fab360eece](https://linux-hardware.org/?probe=fab360eece) | Nov 02, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [b7d7cde99a](https://linux-hardware.org/?probe=b7d7cde99a) | Nov 01, 2023 |
| Unknown       | 1.0                         | Desktop     | [6265787d93](https://linux-hardware.org/?probe=6265787d93) | Nov 01, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [08ee10dc83](https://linux-hardware.org/?probe=08ee10dc83) | Nov 01, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [a7f47546e5](https://linux-hardware.org/?probe=a7f47546e5) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [d64009bcc1](https://linux-hardware.org/?probe=d64009bcc1) | Nov 01, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [8901bca741](https://linux-hardware.org/?probe=8901bca741) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [f5d0c4d34a](https://linux-hardware.org/?probe=f5d0c4d34a) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [0a7341e5e0](https://linux-hardware.org/?probe=0a7341e5e0) | Nov 01, 2023 |
| Dell          | Precision 5550              | Notebook    | [87a9861125](https://linux-hardware.org/?probe=87a9861125) | Nov 01, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | Notebook    | [a2273dea0e](https://linux-hardware.org/?probe=a2273dea0e) | Nov 01, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [e03b553957](https://linux-hardware.org/?probe=e03b553957) | Nov 01, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [9775caad00](https://linux-hardware.org/?probe=9775caad00) | Oct 31, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [f34d479454](https://linux-hardware.org/?probe=f34d479454) | Oct 31, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [45280b44d0](https://linux-hardware.org/?probe=45280b44d0) | Oct 31, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [7b71031ba1](https://linux-hardware.org/?probe=7b71031ba1) | Oct 31, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [3ab77e3324](https://linux-hardware.org/?probe=3ab77e3324) | Oct 31, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [d370c488e4](https://linux-hardware.org/?probe=d370c488e4) | Oct 31, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [c26ec81fab](https://linux-hardware.org/?probe=c26ec81fab) | Oct 31, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [aef5a9f17c](https://linux-hardware.org/?probe=aef5a9f17c) | Oct 31, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [7941dfd8cf](https://linux-hardware.org/?probe=7941dfd8cf) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [ed27ef3491](https://linux-hardware.org/?probe=ed27ef3491) | Oct 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [9dd62a1bb2](https://linux-hardware.org/?probe=9dd62a1bb2) | Oct 31, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [2bab6515f4](https://linux-hardware.org/?probe=2bab6515f4) | Oct 30, 2023 |
| Dell          | Latitude 7370               | Notebook    | [f47b42c0b0](https://linux-hardware.org/?probe=f47b42c0b0) | Oct 30, 2023 |
| Sony          | SVE1511B1RB                 | Notebook    | [74651497a9](https://linux-hardware.org/?probe=74651497a9) | Oct 30, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [f123c19bb4](https://linux-hardware.org/?probe=f123c19bb4) | Oct 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6cafea6b4c](https://linux-hardware.org/?probe=6cafea6b4c) | Oct 30, 2023 |
| ASUSTek       | K84L                        | Notebook    | [e6d103b3e4](https://linux-hardware.org/?probe=e6d103b3e4) | Oct 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [923dc22e28](https://linux-hardware.org/?probe=923dc22e28) | Oct 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [ab6738f16c](https://linux-hardware.org/?probe=ab6738f16c) | Oct 29, 2023 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [e2e7788338](https://linux-hardware.org/?probe=e2e7788338) | Oct 29, 2023 |
| Dell          | Latitude E5400              | Notebook    | [169d73bee0](https://linux-hardware.org/?probe=169d73bee0) | Oct 28, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [551a5c8aa2](https://linux-hardware.org/?probe=551a5c8aa2) | Oct 28, 2023 |
| HP            | Notebook                    | Notebook    | [715435e533](https://linux-hardware.org/?probe=715435e533) | Oct 28, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [e34317a76d](https://linux-hardware.org/?probe=e34317a76d) | Oct 28, 2023 |
| GEEKOM        | Mini IT12                   | Desktop     | [b9509f49f1](https://linux-hardware.org/?probe=b9509f49f1) | Oct 28, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [10af2377c2](https://linux-hardware.org/?probe=10af2377c2) | Oct 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [80b9cb5e56](https://linux-hardware.org/?probe=80b9cb5e56) | Oct 28, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | Desktop     | [52e07e7ffe](https://linux-hardware.org/?probe=52e07e7ffe) | Oct 28, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [7610254116](https://linux-hardware.org/?probe=7610254116) | Oct 27, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [b7f872ea23](https://linux-hardware.org/?probe=b7f872ea23) | Oct 27, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [484d866dc6](https://linux-hardware.org/?probe=484d866dc6) | Oct 27, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a619c8a955](https://linux-hardware.org/?probe=a619c8a955) | Oct 27, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [5ca426e5c3](https://linux-hardware.org/?probe=5ca426e5c3) | Oct 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [15488b723a](https://linux-hardware.org/?probe=15488b723a) | Oct 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e8432e79c8](https://linux-hardware.org/?probe=e8432e79c8) | Oct 26, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [e71634ac32](https://linux-hardware.org/?probe=e71634ac32) | Oct 26, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [3a1039b4b6](https://linux-hardware.org/?probe=3a1039b4b6) | Oct 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [755d25d933](https://linux-hardware.org/?probe=755d25d933) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9cb0b1ec27](https://linux-hardware.org/?probe=9cb0b1ec27) | Oct 26, 2023 |
| Gigabyte      | AERO 17 XE5                 | Notebook    | [47d1cb500e](https://linux-hardware.org/?probe=47d1cb500e) | Oct 25, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [d61428d56d](https://linux-hardware.org/?probe=d61428d56d) | Oct 25, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [62bbdaec23](https://linux-hardware.org/?probe=62bbdaec23) | Oct 24, 2023 |
| HP            | 212B                        | Desktop     | [714373878e](https://linux-hardware.org/?probe=714373878e) | Oct 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1bd81ebf81](https://linux-hardware.org/?probe=1bd81ebf81) | Oct 24, 2023 |
| HP            | 83EF                        | Desktop     | [9953e14c0a](https://linux-hardware.org/?probe=9953e14c0a) | Oct 24, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [47b5a808aa](https://linux-hardware.org/?probe=47b5a808aa) | Oct 24, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [48233204f6](https://linux-hardware.org/?probe=48233204f6) | Oct 23, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [07e8b4df09](https://linux-hardware.org/?probe=07e8b4df09) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S4M20... | Notebook    | [799084c1a9](https://linux-hardware.org/?probe=799084c1a9) | Oct 23, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [1a97d77c76](https://linux-hardware.org/?probe=1a97d77c76) | Oct 23, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [d1f12415b9](https://linux-hardware.org/?probe=d1f12415b9) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [bd89e392d1](https://linux-hardware.org/?probe=bd89e392d1) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [cb6130951a](https://linux-hardware.org/?probe=cb6130951a) | Oct 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c927a93a85](https://linux-hardware.org/?probe=c927a93a85) | Oct 23, 2023 |
| Google        | Gandof                      | Notebook    | [7a07edf626](https://linux-hardware.org/?probe=7a07edf626) | Oct 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [bebe071d7c](https://linux-hardware.org/?probe=bebe071d7c) | Oct 23, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [93043f297f](https://linux-hardware.org/?probe=93043f297f) | Oct 22, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [ce9770538c](https://linux-hardware.org/?probe=ce9770538c) | Oct 22, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [ee15c1dbea](https://linux-hardware.org/?probe=ee15c1dbea) | Oct 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fde726622c](https://linux-hardware.org/?probe=fde726622c) | Oct 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [116946c81c](https://linux-hardware.org/?probe=116946c81c) | Oct 22, 2023 |
| Dell          | 09WH54 A01                  | Desktop     | [4211349cc4](https://linux-hardware.org/?probe=4211349cc4) | Oct 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [43f9375597](https://linux-hardware.org/?probe=43f9375597) | Oct 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [67c6d6e482](https://linux-hardware.org/?probe=67c6d6e482) | Oct 21, 2023 |
| MSI           | GL62VR 7RFX                 | Notebook    | [0d88fb381c](https://linux-hardware.org/?probe=0d88fb381c) | Oct 21, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [04f6bc7f0c](https://linux-hardware.org/?probe=04f6bc7f0c) | Oct 21, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [1ae8f16052](https://linux-hardware.org/?probe=1ae8f16052) | Oct 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9403CVA... | Notebook    | [eaffd30f59](https://linux-hardware.org/?probe=eaffd30f59) | Oct 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9403CVA... | Notebook    | [aafd893b0d](https://linux-hardware.org/?probe=aafd893b0d) | Oct 21, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8ef0f47332](https://linux-hardware.org/?probe=8ef0f47332) | Oct 20, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [a0b48d8a7e](https://linux-hardware.org/?probe=a0b48d8a7e) | Oct 20, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [17f5bf3cef](https://linux-hardware.org/?probe=17f5bf3cef) | Oct 20, 2023 |
| Eluktronic... | MECH-15 G3                  | Notebook    | [1b63389cc6](https://linux-hardware.org/?probe=1b63389cc6) | Oct 20, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [65f3d76afa](https://linux-hardware.org/?probe=65f3d76afa) | Oct 19, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [79a2d6de1a](https://linux-hardware.org/?probe=79a2d6de1a) | Oct 19, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [7fd0eeaeec](https://linux-hardware.org/?probe=7fd0eeaeec) | Oct 19, 2023 |
| Biostar       | A320MH                      | Desktop     | [e2c20a6c0c](https://linux-hardware.org/?probe=e2c20a6c0c) | Oct 19, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [84517c1f4c](https://linux-hardware.org/?probe=84517c1f4c) | Oct 19, 2023 |
| Lenovo        | Legion R7000P APH8 82Y9     | Notebook    | [9c6fb34bab](https://linux-hardware.org/?probe=9c6fb34bab) | Oct 18, 2023 |
| Biostar       | A320MH                      | Desktop     | [62a3d049b2](https://linux-hardware.org/?probe=62a3d049b2) | Oct 18, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [fecce40ebb](https://linux-hardware.org/?probe=fecce40ebb) | Oct 18, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [71eba7e232](https://linux-hardware.org/?probe=71eba7e232) | Oct 18, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [4b1c8afb11](https://linux-hardware.org/?probe=4b1c8afb11) | Oct 17, 2023 |
| Lenovo        | 1046 SBB1C50523 WIN 3556... | Desktop     | [f824921cbb](https://linux-hardware.org/?probe=f824921cbb) | Oct 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5f780203e2](https://linux-hardware.org/?probe=5f780203e2) | Oct 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [9729d18e10](https://linux-hardware.org/?probe=9729d18e10) | Oct 16, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [6f80d0517c](https://linux-hardware.org/?probe=6f80d0517c) | Oct 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0504910ad7](https://linux-hardware.org/?probe=0504910ad7) | Oct 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [9b7bc3fc9d](https://linux-hardware.org/?probe=9b7bc3fc9d) | Oct 16, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [c976b314a2](https://linux-hardware.org/?probe=c976b314a2) | Oct 16, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [2dfea2666c](https://linux-hardware.org/?probe=2dfea2666c) | Oct 15, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [af4857609e](https://linux-hardware.org/?probe=af4857609e) | Oct 15, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [f71ad29f6a](https://linux-hardware.org/?probe=f71ad29f6a) | Oct 15, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [016669d718](https://linux-hardware.org/?probe=016669d718) | Oct 14, 2023 |
| Clevo         | W150ER                      | Notebook    | [e119814a32](https://linux-hardware.org/?probe=e119814a32) | Oct 14, 2023 |
| HP            | 15                          | Notebook    | [f5392b4484](https://linux-hardware.org/?probe=f5392b4484) | Oct 14, 2023 |
| HP            | Pavilion dv7                | Notebook    | [ae2789f31f](https://linux-hardware.org/?probe=ae2789f31f) | Oct 14, 2023 |
| HP            | Pavilion dv7                | Notebook    | [de47e931a1](https://linux-hardware.org/?probe=de47e931a1) | Oct 14, 2023 |
| Samsung       | 950QDB                      | Convertible | [51ddfa2dbf](https://linux-hardware.org/?probe=51ddfa2dbf) | Oct 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e79f4b834d](https://linux-hardware.org/?probe=e79f4b834d) | Oct 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c1e1d017af](https://linux-hardware.org/?probe=c1e1d017af) | Oct 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ac840f060f](https://linux-hardware.org/?probe=ac840f060f) | Oct 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [d1386e080d](https://linux-hardware.org/?probe=d1386e080d) | Oct 12, 2023 |
| MSI           | B560M PRO                   | Desktop     | [3ad673132a](https://linux-hardware.org/?probe=3ad673132a) | Oct 12, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [39e3632f1f](https://linux-hardware.org/?probe=39e3632f1f) | Oct 11, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [17b8025f8d](https://linux-hardware.org/?probe=17b8025f8d) | Oct 11, 2023 |
| Lenovo        | 317E NOK                    | Desktop     | [618b7ebe59](https://linux-hardware.org/?probe=618b7ebe59) | Oct 11, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [e185192929](https://linux-hardware.org/?probe=e185192929) | Oct 11, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [b1b0f03790](https://linux-hardware.org/?probe=b1b0f03790) | Oct 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a5c5f58ddb](https://linux-hardware.org/?probe=a5c5f58ddb) | Oct 11, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [00580f0c7d](https://linux-hardware.org/?probe=00580f0c7d) | Oct 10, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [6e046b22c3](https://linux-hardware.org/?probe=6e046b22c3) | Oct 10, 2023 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [2c7e31eb6f](https://linux-hardware.org/?probe=2c7e31eb6f) | Oct 09, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [9b5474fee0](https://linux-hardware.org/?probe=9b5474fee0) | Oct 09, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [1bb42f8755](https://linux-hardware.org/?probe=1bb42f8755) | Oct 09, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [90041fa012](https://linux-hardware.org/?probe=90041fa012) | Oct 09, 2023 |
| Gateway       | NV57H                       | Notebook    | [141355e1e3](https://linux-hardware.org/?probe=141355e1e3) | Oct 09, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [a46f5ac57a](https://linux-hardware.org/?probe=a46f5ac57a) | Oct 09, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [d7188e68cb](https://linux-hardware.org/?probe=d7188e68cb) | Oct 08, 2023 |
| TrekStor      | YOURBOOK C11B               | Convertible | [cea0d12a81](https://linux-hardware.org/?probe=cea0d12a81) | Oct 08, 2023 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [146bc4cb2c](https://linux-hardware.org/?probe=146bc4cb2c) | Oct 08, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b03eea6d75](https://linux-hardware.org/?probe=b03eea6d75) | Oct 08, 2023 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [47e7797579](https://linux-hardware.org/?probe=47e7797579) | Oct 08, 2023 |
| HP            | 212B                        | Desktop     | [faa56daf1d](https://linux-hardware.org/?probe=faa56daf1d) | Oct 07, 2023 |
| HP            | 83E8                        | Desktop     | [c1028de72b](https://linux-hardware.org/?probe=c1028de72b) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [e401b0c370](https://linux-hardware.org/?probe=e401b0c370) | Oct 07, 2023 |
| Dell          | Precision 7710              | Notebook    | [6dcd757659](https://linux-hardware.org/?probe=6dcd757659) | Oct 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [6bc395bbda](https://linux-hardware.org/?probe=6bc395bbda) | Oct 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [ad60cd6e18](https://linux-hardware.org/?probe=ad60cd6e18) | Oct 06, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [da6b1b88e6](https://linux-hardware.org/?probe=da6b1b88e6) | Oct 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [8c4bcd5155](https://linux-hardware.org/?probe=8c4bcd5155) | Oct 06, 2023 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [10baa7a046](https://linux-hardware.org/?probe=10baa7a046) | Oct 06, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [f68374e7cd](https://linux-hardware.org/?probe=f68374e7cd) | Oct 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cbf93da8d0](https://linux-hardware.org/?probe=cbf93da8d0) | Oct 04, 2023 |
| Acer          | Aspire ES1-732              | Notebook    | [9f011f4756](https://linux-hardware.org/?probe=9f011f4756) | Oct 04, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [faf6d73cad](https://linux-hardware.org/?probe=faf6d73cad) | Oct 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [573f1da6a9](https://linux-hardware.org/?probe=573f1da6a9) | Oct 03, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [c41cd8be8e](https://linux-hardware.org/?probe=c41cd8be8e) | Oct 03, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [e3121d6d02](https://linux-hardware.org/?probe=e3121d6d02) | Oct 03, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [5d8ef7c003](https://linux-hardware.org/?probe=5d8ef7c003) | Oct 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2e1316fb48](https://linux-hardware.org/?probe=2e1316fb48) | Oct 03, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [83ede540d1](https://linux-hardware.org/?probe=83ede540d1) | Oct 03, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [6a2fa93249](https://linux-hardware.org/?probe=6a2fa93249) | Oct 03, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [c9a7b94ace](https://linux-hardware.org/?probe=c9a7b94ace) | Oct 03, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | Notebook    | [21ee2a6e8f](https://linux-hardware.org/?probe=21ee2a6e8f) | Oct 03, 2023 |
| Lenovo        | ThinkPad L460 20FVS12A00    | Notebook    | [ad3d8f3522](https://linux-hardware.org/?probe=ad3d8f3522) | Oct 02, 2023 |
| Lenovo        | ThinkPad T420s 4170CTO      | Notebook    | [f141fc2bd7](https://linux-hardware.org/?probe=f141fc2bd7) | Oct 02, 2023 |
| MSI           | B560M PRO                   | Desktop     | [1312550a66](https://linux-hardware.org/?probe=1312550a66) | Oct 02, 2023 |
| Dell          | Precision 5480              | Notebook    | [21bd104767](https://linux-hardware.org/?probe=21bd104767) | Oct 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4e0bb2d740](https://linux-hardware.org/?probe=4e0bb2d740) | Oct 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [840bfbb2cb](https://linux-hardware.org/?probe=840bfbb2cb) | Oct 01, 2023 |
| HUAWEI        | VLT-WX0                     | Notebook    | [6778af4012](https://linux-hardware.org/?probe=6778af4012) | Oct 01, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [8311d775a9](https://linux-hardware.org/?probe=8311d775a9) | Oct 01, 2023 |
| Dell          | G7 7700                     | Notebook    | [62bd529b36](https://linux-hardware.org/?probe=62bd529b36) | Oct 01, 2023 |
| HUAWEI        | MateBook X                  | Notebook    | [5479e52948](https://linux-hardware.org/?probe=5479e52948) | Oct 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| MSI           | B560M PRO                   | Desktop     | [1dc06a927c](https://linux-hardware.org/?probe=1dc06a927c) | Sep 29, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [51f3cd7354](https://linux-hardware.org/?probe=51f3cd7354) | Sep 29, 2023 |
| MSI           | B560M PRO                   | Desktop     | [ce2f5b7349](https://linux-hardware.org/?probe=ce2f5b7349) | Sep 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| Lenovo        | ThinkPad Yoga 460 20ELS0... | Convertible | [29617a5db5](https://linux-hardware.org/?probe=29617a5db5) | Sep 29, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [e55a394d41](https://linux-hardware.org/?probe=e55a394d41) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F60097US    | Notebook    | [607d788fde](https://linux-hardware.org/?probe=607d788fde) | Sep 28, 2023 |
| Acer          | Aspire ES1-732              | Notebook    | [f30d62d67b](https://linux-hardware.org/?probe=f30d62d67b) | Sep 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [4c1a2e1e21](https://linux-hardware.org/?probe=4c1a2e1e21) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [3ee705f2f3](https://linux-hardware.org/?probe=3ee705f2f3) | Sep 28, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [2b86c9fac4](https://linux-hardware.org/?probe=2b86c9fac4) | Sep 28, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [9d767beb12](https://linux-hardware.org/?probe=9d767beb12) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [7ed50e5e43](https://linux-hardware.org/?probe=7ed50e5e43) | Sep 27, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [0dcef3e6c3](https://linux-hardware.org/?probe=0dcef3e6c3) | Sep 27, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [7cfa1007ee](https://linux-hardware.org/?probe=7cfa1007ee) | Sep 27, 2023 |
| Dell          | Inspiron N5040              | Notebook    | [c48d158b62](https://linux-hardware.org/?probe=c48d158b62) | Sep 27, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [84ad07c3f9](https://linux-hardware.org/?probe=84ad07c3f9) | Sep 27, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [a9c8158139](https://linux-hardware.org/?probe=a9c8158139) | Sep 27, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [79e6dd1302](https://linux-hardware.org/?probe=79e6dd1302) | Sep 27, 2023 |
| Google        | Blorb                       | Notebook    | [efa4ad9e2c](https://linux-hardware.org/?probe=efa4ad9e2c) | Sep 26, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [3b76e2cd65](https://linux-hardware.org/?probe=3b76e2cd65) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [124f7a0f29](https://linux-hardware.org/?probe=124f7a0f29) | Sep 26, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [65369ae480](https://linux-hardware.org/?probe=65369ae480) | Sep 25, 2023 |
| HP            | 8949 11                     | Desktop     | [acb62cff2b](https://linux-hardware.org/?probe=acb62cff2b) | Sep 25, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [381be3d212](https://linux-hardware.org/?probe=381be3d212) | Sep 25, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [508cf38973](https://linux-hardware.org/?probe=508cf38973) | Sep 24, 2023 |
| HP            | ENVY m4                     | Notebook    | [8d7da36940](https://linux-hardware.org/?probe=8d7da36940) | Sep 24, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [5735f79e4f](https://linux-hardware.org/?probe=5735f79e4f) | Sep 23, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [4fb741bdb3](https://linux-hardware.org/?probe=4fb741bdb3) | Sep 23, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [c970ee5a12](https://linux-hardware.org/?probe=c970ee5a12) | Sep 23, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [fbeac0cab4](https://linux-hardware.org/?probe=fbeac0cab4) | Sep 23, 2023 |
| HP            | 8055                        | Desktop     | [d8ea4bc33a](https://linux-hardware.org/?probe=d8ea4bc33a) | Sep 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [537e551c45](https://linux-hardware.org/?probe=537e551c45) | Sep 23, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [14d87bfb5d](https://linux-hardware.org/?probe=14d87bfb5d) | Sep 22, 2023 |
| Lenovo        | IdeaPad Flex-14IWL 81SQ     | Convertible | [480d8732d2](https://linux-hardware.org/?probe=480d8732d2) | Sep 22, 2023 |
| Lenovo        | IdeaPad Flex-14IWL 81SQ     | Convertible | [28af4771b9](https://linux-hardware.org/?probe=28af4771b9) | Sep 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [a9f9ccb4f9](https://linux-hardware.org/?probe=a9f9ccb4f9) | Sep 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c2c49834e5](https://linux-hardware.org/?probe=c2c49834e5) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [8b39e51416](https://linux-hardware.org/?probe=8b39e51416) | Sep 21, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [c2d2a28c33](https://linux-hardware.org/?probe=c2d2a28c33) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ae7455bac3](https://linux-hardware.org/?probe=ae7455bac3) | Sep 21, 2023 |
| Dell          | Precision 7520              | Notebook    | [2fd68ca236](https://linux-hardware.org/?probe=2fd68ca236) | Sep 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [816502caea](https://linux-hardware.org/?probe=816502caea) | Sep 21, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [b449a82c4f](https://linux-hardware.org/?probe=b449a82c4f) | Sep 21, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [66262df4c4](https://linux-hardware.org/?probe=66262df4c4) | Sep 21, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [192f065f70](https://linux-hardware.org/?probe=192f065f70) | Sep 21, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [063f211c4d](https://linux-hardware.org/?probe=063f211c4d) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6337af2f4c](https://linux-hardware.org/?probe=6337af2f4c) | Sep 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [dde4d0b10f](https://linux-hardware.org/?probe=dde4d0b10f) | Sep 20, 2023 |
| ASUSTek       | Z450UA                      | Notebook    | [60d85e59da](https://linux-hardware.org/?probe=60d85e59da) | Sep 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [00c6b8cced](https://linux-hardware.org/?probe=00c6b8cced) | Sep 20, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [01d8f27500](https://linux-hardware.org/?probe=01d8f27500) | Sep 20, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d8305c7c45](https://linux-hardware.org/?probe=d8305c7c45) | Sep 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0H200    | Notebook    | [c38151f281](https://linux-hardware.org/?probe=c38151f281) | Sep 20, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7ff48f538f](https://linux-hardware.org/?probe=7ff48f538f) | Sep 19, 2023 |
| HP            | 212B                        | Desktop     | [1d71ef5e64](https://linux-hardware.org/?probe=1d71ef5e64) | Sep 19, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6088e9b2fa](https://linux-hardware.org/?probe=6088e9b2fa) | Sep 19, 2023 |
| HP            | 3047h                       | Desktop     | [f684816e88](https://linux-hardware.org/?probe=f684816e88) | Sep 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [286398db3c](https://linux-hardware.org/?probe=286398db3c) | Sep 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [ad024119be](https://linux-hardware.org/?probe=ad024119be) | Sep 19, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c2cd300139](https://linux-hardware.org/?probe=c2cd300139) | Sep 19, 2023 |
| Microsoft     | Surface Pro 2               | Tablet      | [6b14cbf5b9](https://linux-hardware.org/?probe=6b14cbf5b9) | Sep 18, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [19e013b8e8](https://linux-hardware.org/?probe=19e013b8e8) | Sep 18, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [417ad95c4c](https://linux-hardware.org/?probe=417ad95c4c) | Sep 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [75f2d2b31d](https://linux-hardware.org/?probe=75f2d2b31d) | Sep 18, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [7b293fe65e](https://linux-hardware.org/?probe=7b293fe65e) | Sep 18, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [e517de2d8f](https://linux-hardware.org/?probe=e517de2d8f) | Sep 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [78535377d6](https://linux-hardware.org/?probe=78535377d6) | Sep 18, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [15dd923faa](https://linux-hardware.org/?probe=15dd923faa) | Sep 17, 2023 |
| HP            | 212B                        | Desktop     | [a041c8b5a9](https://linux-hardware.org/?probe=a041c8b5a9) | Sep 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [10709d2c51](https://linux-hardware.org/?probe=10709d2c51) | Sep 17, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ad66bafcae](https://linux-hardware.org/?probe=ad66bafcae) | Sep 17, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [a25ee31882](https://linux-hardware.org/?probe=a25ee31882) | Sep 17, 2023 |
| Lenovo        | 3181 NO DPK                 | Mini pc     | [53531ff3b6](https://linux-hardware.org/?probe=53531ff3b6) | Sep 17, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [1398fa87b2](https://linux-hardware.org/?probe=1398fa87b2) | Sep 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b8459514db](https://linux-hardware.org/?probe=b8459514db) | Sep 17, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c27b81ea3e](https://linux-hardware.org/?probe=c27b81ea3e) | Sep 17, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [8db77afc82](https://linux-hardware.org/?probe=8db77afc82) | Sep 17, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [2e5c8bb8ed](https://linux-hardware.org/?probe=2e5c8bb8ed) | Sep 17, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [0ebcb848ff](https://linux-hardware.org/?probe=0ebcb848ff) | Sep 16, 2023 |
| HP            | 3647h                       | Desktop     | [89c406366a](https://linux-hardware.org/?probe=89c406366a) | Sep 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [b7ff5a9cf2](https://linux-hardware.org/?probe=b7ff5a9cf2) | Sep 16, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [a6d51b9c90](https://linux-hardware.org/?probe=a6d51b9c90) | Sep 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [c40357b67a](https://linux-hardware.org/?probe=c40357b67a) | Sep 16, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [cbc5e29bf6](https://linux-hardware.org/?probe=cbc5e29bf6) | Sep 16, 2023 |
| Biostar       | X370GTN                     | Desktop     | [1ac44acadd](https://linux-hardware.org/?probe=1ac44acadd) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [567443136d](https://linux-hardware.org/?probe=567443136d) | Sep 15, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [4d35879250](https://linux-hardware.org/?probe=4d35879250) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [2073aca95d](https://linux-hardware.org/?probe=2073aca95d) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [fa484cf261](https://linux-hardware.org/?probe=fa484cf261) | Sep 15, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [4d0eb9b8d2](https://linux-hardware.org/?probe=4d0eb9b8d2) | Sep 15, 2023 |
| MSI           | PRO B660M-B DDR4            | Desktop     | [9463a6f106](https://linux-hardware.org/?probe=9463a6f106) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [43f6a3bfc1](https://linux-hardware.org/?probe=43f6a3bfc1) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [dcd2b90824](https://linux-hardware.org/?probe=dcd2b90824) | Sep 14, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [bc597f4c0c](https://linux-hardware.org/?probe=bc597f4c0c) | Sep 14, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [ba15fb6ed7](https://linux-hardware.org/?probe=ba15fb6ed7) | Sep 14, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [5d79965e45](https://linux-hardware.org/?probe=5d79965e45) | Sep 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1703cfdd5e](https://linux-hardware.org/?probe=1703cfdd5e) | Sep 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7769de42b0](https://linux-hardware.org/?probe=7769de42b0) | Sep 13, 2023 |
| HP            | 0A60h                       | Desktop     | [107f849e6b](https://linux-hardware.org/?probe=107f849e6b) | Sep 13, 2023 |
| Dell          | Latitude 7410               | Notebook    | [59abc2d869](https://linux-hardware.org/?probe=59abc2d869) | Sep 12, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d4e392a0ad](https://linux-hardware.org/?probe=d4e392a0ad) | Sep 12, 2023 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | Notebook    | [9506117d6f](https://linux-hardware.org/?probe=9506117d6f) | Sep 12, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c6f2b822c7](https://linux-hardware.org/?probe=c6f2b822c7) | Sep 12, 2023 |
| HP            | 870C                        | Desktop     | [3de222afdb](https://linux-hardware.org/?probe=3de222afdb) | Sep 12, 2023 |
| HP            | 620                         | Notebook    | [59577ac122](https://linux-hardware.org/?probe=59577ac122) | Sep 12, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6a7ee91a3f](https://linux-hardware.org/?probe=6a7ee91a3f) | Sep 11, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [3859055e8d](https://linux-hardware.org/?probe=3859055e8d) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0ac203a0c5](https://linux-hardware.org/?probe=0ac203a0c5) | Sep 11, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [667560b69c](https://linux-hardware.org/?probe=667560b69c) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [793d3e47ff](https://linux-hardware.org/?probe=793d3e47ff) | Sep 10, 2023 |
| Toshiba       | Satellite M645              | Notebook    | [40c02e9bc9](https://linux-hardware.org/?probe=40c02e9bc9) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [6b9804a536](https://linux-hardware.org/?probe=6b9804a536) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [d824341957](https://linux-hardware.org/?probe=d824341957) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [3021f551f4](https://linux-hardware.org/?probe=3021f551f4) | Sep 09, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [6e5224fa1d](https://linux-hardware.org/?probe=6e5224fa1d) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3f937bad2e](https://linux-hardware.org/?probe=3f937bad2e) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [1474c70336](https://linux-hardware.org/?probe=1474c70336) | Sep 09, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [524bbba65a](https://linux-hardware.org/?probe=524bbba65a) | Sep 09, 2023 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [11e5581873](https://linux-hardware.org/?probe=11e5581873) | Sep 08, 2023 |
| HP            | 2B36                        | Desktop     | [20552523c6](https://linux-hardware.org/?probe=20552523c6) | Sep 08, 2023 |
| HP            | 339A                        | Desktop     | [4ba272aaf9](https://linux-hardware.org/?probe=4ba272aaf9) | Sep 08, 2023 |
| HP            | 2B36                        | Desktop     | [7697b6ff27](https://linux-hardware.org/?probe=7697b6ff27) | Sep 08, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [480df18bcb](https://linux-hardware.org/?probe=480df18bcb) | Sep 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b5ea617856](https://linux-hardware.org/?probe=b5ea617856) | Sep 08, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [d35d89339d](https://linux-hardware.org/?probe=d35d89339d) | Sep 08, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | Notebook    | [650c9dbdd3](https://linux-hardware.org/?probe=650c9dbdd3) | Sep 07, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [7cbd11709c](https://linux-hardware.org/?probe=7cbd11709c) | Sep 07, 2023 |
| MSI           | B360M GAMING PLUS           | Desktop     | [1faaa87b61](https://linux-hardware.org/?probe=1faaa87b61) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [699fb7e97e](https://linux-hardware.org/?probe=699fb7e97e) | Sep 07, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [84368e642c](https://linux-hardware.org/?probe=84368e642c) | Sep 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9e7c97275d](https://linux-hardware.org/?probe=9e7c97275d) | Sep 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [04d60f1b2d](https://linux-hardware.org/?probe=04d60f1b2d) | Sep 06, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [68fe74d684](https://linux-hardware.org/?probe=68fe74d684) | Sep 06, 2023 |
| HP            | 1905                        | Desktop     | [e0da3a1a45](https://linux-hardware.org/?probe=e0da3a1a45) | Sep 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [6c4c9936b0](https://linux-hardware.org/?probe=6c4c9936b0) | Sep 06, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [4a5a98638e](https://linux-hardware.org/?probe=4a5a98638e) | Sep 06, 2023 |
| ASRock        | Z690 PG Velocita            | Desktop     | [0064d9d9e2](https://linux-hardware.org/?probe=0064d9d9e2) | Sep 06, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [89ce951011](https://linux-hardware.org/?probe=89ce951011) | Sep 05, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [0f5597eb7e](https://linux-hardware.org/?probe=0f5597eb7e) | Sep 05, 2023 |
| MSI           | MS-B0A81                    | Desktop     | [2c4cc9e78f](https://linux-hardware.org/?probe=2c4cc9e78f) | Sep 05, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [ca342c2a7e](https://linux-hardware.org/?probe=ca342c2a7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349KQ3       | Notebook    | [287ea35176](https://linux-hardware.org/?probe=287ea35176) | Sep 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [945acb9ea2](https://linux-hardware.org/?probe=945acb9ea2) | Sep 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [24a7c8a496](https://linux-hardware.org/?probe=24a7c8a496) | Sep 04, 2023 |
| Chuwi         | MiniBook X                  | Convertible | [a298625ea9](https://linux-hardware.org/?probe=a298625ea9) | Sep 04, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [d7b4b0f2f1](https://linux-hardware.org/?probe=d7b4b0f2f1) | Sep 04, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [590b5224d9](https://linux-hardware.org/?probe=590b5224d9) | Sep 04, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [80f9f3915b](https://linux-hardware.org/?probe=80f9f3915b) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [908a64b09a](https://linux-hardware.org/?probe=908a64b09a) | Sep 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [8146fce36b](https://linux-hardware.org/?probe=8146fce36b) | Sep 03, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [7ebd20a049](https://linux-hardware.org/?probe=7ebd20a049) | Sep 03, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [4ee783a52f](https://linux-hardware.org/?probe=4ee783a52f) | Sep 03, 2023 |
| Notebook      | NK50S5_SZ                   | Notebook    | [f0718be353](https://linux-hardware.org/?probe=f0718be353) | Sep 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [49101faf53](https://linux-hardware.org/?probe=49101faf53) | Sep 02, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [e446721809](https://linux-hardware.org/?probe=e446721809) | Sep 02, 2023 |
| Biostar       | A320MH                      | Desktop     | [8791e4dd20](https://linux-hardware.org/?probe=8791e4dd20) | Sep 02, 2023 |
| Google        | Galtic                      | Notebook    | [e9ccd3a286](https://linux-hardware.org/?probe=e9ccd3a286) | Sep 01, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [a19ece12f0](https://linux-hardware.org/?probe=a19ece12f0) | Sep 01, 2023 |
| HP            | 82F1                        | Desktop     | [6fca2da71a](https://linux-hardware.org/?probe=6fca2da71a) | Sep 01, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [1cb91dff9e](https://linux-hardware.org/?probe=1cb91dff9e) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [e9f211faf1](https://linux-hardware.org/?probe=e9f211faf1) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [b1a3900bdd](https://linux-hardware.org/?probe=b1a3900bdd) | Sep 01, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [42eb5f3ad4](https://linux-hardware.org/?probe=42eb5f3ad4) | Aug 31, 2023 |
| BANGHO        | GM-15Z12 RTX3060 i7         | Notebook    | [4e77460452](https://linux-hardware.org/?probe=4e77460452) | Aug 31, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [0e6c0b300b](https://linux-hardware.org/?probe=0e6c0b300b) | Aug 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [88b6c0365c](https://linux-hardware.org/?probe=88b6c0365c) | Aug 31, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | Notebook    | [a5fd9c62e8](https://linux-hardware.org/?probe=a5fd9c62e8) | Aug 30, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [6eca0a231c](https://linux-hardware.org/?probe=6eca0a231c) | Aug 30, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bec8171350](https://linux-hardware.org/?probe=bec8171350) | Aug 30, 2023 |
| Dell          | 07KY25 A00                  | Desktop     | [9346896df5](https://linux-hardware.org/?probe=9346896df5) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [c9fa671277](https://linux-hardware.org/?probe=c9fa671277) | Aug 29, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [071fa35482](https://linux-hardware.org/?probe=071fa35482) | Aug 29, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [4a38e28073](https://linux-hardware.org/?probe=4a38e28073) | Aug 29, 2023 |
| GPD           | G1619-01                    | Notebook    | [0e12028a4d](https://linux-hardware.org/?probe=0e12028a4d) | Aug 28, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [d0453c59f5](https://linux-hardware.org/?probe=d0453c59f5) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [efc8be8369](https://linux-hardware.org/?probe=efc8be8369) | Aug 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [85640356ad](https://linux-hardware.org/?probe=85640356ad) | Aug 28, 2023 |
| MSI           | 970A-G46                    | Desktop     | [5b4c3411dc](https://linux-hardware.org/?probe=5b4c3411dc) | Aug 28, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [db36b0429d](https://linux-hardware.org/?probe=db36b0429d) | Aug 27, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [2d9703804d](https://linux-hardware.org/?probe=2d9703804d) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [569d6b6121](https://linux-hardware.org/?probe=569d6b6121) | Aug 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [a0c3124b6a](https://linux-hardware.org/?probe=a0c3124b6a) | Aug 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [c675cc9767](https://linux-hardware.org/?probe=c675cc9767) | Aug 27, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9c34344e6d](https://linux-hardware.org/?probe=9c34344e6d) | Aug 26, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [2eb35196a6](https://linux-hardware.org/?probe=2eb35196a6) | Aug 26, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [c154878ecd](https://linux-hardware.org/?probe=c154878ecd) | Aug 26, 2023 |
| HP            | ProBook 450 15.6 inch G1... | Notebook    | [973d7867a4](https://linux-hardware.org/?probe=973d7867a4) | Aug 26, 2023 |
| Lenovo        | ThinkPad T430 2349KAG       | Notebook    | [f2348b8eee](https://linux-hardware.org/?probe=f2348b8eee) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [24c8bedd43](https://linux-hardware.org/?probe=24c8bedd43) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [d31df9053b](https://linux-hardware.org/?probe=d31df9053b) | Aug 23, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [74fe0374b3](https://linux-hardware.org/?probe=74fe0374b3) | Aug 23, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [3c5cdd0318](https://linux-hardware.org/?probe=3c5cdd0318) | Aug 23, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [69d3db7d28](https://linux-hardware.org/?probe=69d3db7d28) | Aug 23, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [3231dcefb4](https://linux-hardware.org/?probe=3231dcefb4) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [99448eedb6](https://linux-hardware.org/?probe=99448eedb6) | Aug 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [839ae55173](https://linux-hardware.org/?probe=839ae55173) | Aug 21, 2023 |
| Timi          | Xiaomi Book Air 13 2022     | Convertible | [e4c7b8207c](https://linux-hardware.org/?probe=e4c7b8207c) | Aug 20, 2023 |
| Lenovo        | ThinkPad L430 24662W2       | Notebook    | [10b7d76c38](https://linux-hardware.org/?probe=10b7d76c38) | Aug 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [4fc5a7442a](https://linux-hardware.org/?probe=4fc5a7442a) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [50af29acb9](https://linux-hardware.org/?probe=50af29acb9) | Aug 19, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [f8c85e442f](https://linux-hardware.org/?probe=f8c85e442f) | Aug 19, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [47b747684d](https://linux-hardware.org/?probe=47b747684d) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [540a2db767](https://linux-hardware.org/?probe=540a2db767) | Aug 18, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [28b621194b](https://linux-hardware.org/?probe=28b621194b) | Aug 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [99b060481a](https://linux-hardware.org/?probe=99b060481a) | Aug 18, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [753e0098e5](https://linux-hardware.org/?probe=753e0098e5) | Aug 17, 2023 |
| ASRock        | H61M-HG4                    | Desktop     | [6fbc46fea9](https://linux-hardware.org/?probe=6fbc46fea9) | Aug 17, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [54a5786749](https://linux-hardware.org/?probe=54a5786749) | Aug 17, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b63e7d3466](https://linux-hardware.org/?probe=b63e7d3466) | Aug 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c093ae6eb5](https://linux-hardware.org/?probe=c093ae6eb5) | Aug 17, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [3b6cc87ac7](https://linux-hardware.org/?probe=3b6cc87ac7) | Aug 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [c965074769](https://linux-hardware.org/?probe=c965074769) | Aug 17, 2023 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [086cffe9b9](https://linux-hardware.org/?probe=086cffe9b9) | Aug 16, 2023 |
| BESSTAR Te... | VB9                         | Mini pc     | [f4f73b1d87](https://linux-hardware.org/?probe=f4f73b1d87) | Aug 16, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Notebook    | [e9690dda8e](https://linux-hardware.org/?probe=e9690dda8e) | Aug 16, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [3372d46d8c](https://linux-hardware.org/?probe=3372d46d8c) | Aug 16, 2023 |
| HP            | 15                          | Notebook    | [9b9e2459a8](https://linux-hardware.org/?probe=9b9e2459a8) | Aug 15, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [214e2092c6](https://linux-hardware.org/?probe=214e2092c6) | Aug 15, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4907b10657](https://linux-hardware.org/?probe=4907b10657) | Aug 15, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [639ec473a1](https://linux-hardware.org/?probe=639ec473a1) | Aug 15, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [0d11484b59](https://linux-hardware.org/?probe=0d11484b59) | Aug 15, 2023 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [a14844e2b4](https://linux-hardware.org/?probe=a14844e2b4) | Aug 14, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [076c807d2d](https://linux-hardware.org/?probe=076c807d2d) | Aug 14, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f4bcea527c](https://linux-hardware.org/?probe=f4bcea527c) | Aug 14, 2023 |
| ASUSTek       | G15CE                       | Desktop     | [a9ac3a3ce4](https://linux-hardware.org/?probe=a9ac3a3ce4) | Aug 13, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e0c6e5b185](https://linux-hardware.org/?probe=e0c6e5b185) | Aug 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [182445f47d](https://linux-hardware.org/?probe=182445f47d) | Aug 13, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e0e2f927ae](https://linux-hardware.org/?probe=e0e2f927ae) | Aug 13, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [3be73537be](https://linux-hardware.org/?probe=3be73537be) | Aug 13, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | Notebook    | [f709dd85f7](https://linux-hardware.org/?probe=f709dd85f7) | Aug 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [fe5f1d5c1b](https://linux-hardware.org/?probe=fe5f1d5c1b) | Aug 12, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [e39fddb92c](https://linux-hardware.org/?probe=e39fddb92c) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1d5206dc94](https://linux-hardware.org/?probe=1d5206dc94) | Aug 12, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [1f4aa5bf97](https://linux-hardware.org/?probe=1f4aa5bf97) | Aug 12, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4fe6eb4d59](https://linux-hardware.org/?probe=4fe6eb4d59) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [79cc445925](https://linux-hardware.org/?probe=79cc445925) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [b9d1b6d44a](https://linux-hardware.org/?probe=b9d1b6d44a) | Aug 12, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [6f5a32d65f](https://linux-hardware.org/?probe=6f5a32d65f) | Aug 11, 2023 |
| Gigabyte      | M720-US3                    | Desktop     | [222bc02e4f](https://linux-hardware.org/?probe=222bc02e4f) | Aug 11, 2023 |
| Acer          | TMP255-M                    | Notebook    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| HP            | 83E8                        | Desktop     | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [22916d4c12](https://linux-hardware.org/?probe=22916d4c12) | Aug 10, 2023 |
| HP            | 872E                        | Mini pc     | [0318907909](https://linux-hardware.org/?probe=0318907909) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [0521e62bf9](https://linux-hardware.org/?probe=0521e62bf9) | Aug 10, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [198fcb1fc2](https://linux-hardware.org/?probe=198fcb1fc2) | Aug 10, 2023 |
| Positivo      | Presley 3                   | Notebook    | [16ddbd1a75](https://linux-hardware.org/?probe=16ddbd1a75) | Aug 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [00bb870b78](https://linux-hardware.org/?probe=00bb870b78) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4a7cc2835f](https://linux-hardware.org/?probe=4a7cc2835f) | Aug 09, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [f50b51555f](https://linux-hardware.org/?probe=f50b51555f) | Aug 09, 2023 |
| Positivo      | Presley 3                   | Notebook    | [9edde2ea30](https://linux-hardware.org/?probe=9edde2ea30) | Aug 09, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [0c755e3349](https://linux-hardware.org/?probe=0c755e3349) | Aug 09, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [3702186068](https://linux-hardware.org/?probe=3702186068) | Aug 08, 2023 |
| Lenovo        | ThinkPad T440 20B7S4NV07    | Notebook    | [af7992a11e](https://linux-hardware.org/?probe=af7992a11e) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [77f61b77f5](https://linux-hardware.org/?probe=77f61b77f5) | Aug 08, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7889f62638](https://linux-hardware.org/?probe=7889f62638) | Aug 08, 2023 |
| Lenovo        | ThinkPad X230 2324BV7       | Notebook    | [e1f092d38b](https://linux-hardware.org/?probe=e1f092d38b) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [fa4f74161f](https://linux-hardware.org/?probe=fa4f74161f) | Aug 08, 2023 |
| Dell          | Inspiron 7306 2n1           | Convertible | [d2e707746f](https://linux-hardware.org/?probe=d2e707746f) | Aug 08, 2023 |
| ASUSTek       | N550LF                      | Notebook    | [57f7da9570](https://linux-hardware.org/?probe=57f7da9570) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [121b892fa8](https://linux-hardware.org/?probe=121b892fa8) | Aug 08, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [61c59e48d2](https://linux-hardware.org/?probe=61c59e48d2) | Aug 08, 2023 |
| Jumper        | QCYL-200                    | Notebook    | [24da6190dc](https://linux-hardware.org/?probe=24da6190dc) | Aug 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b73a01acaf](https://linux-hardware.org/?probe=b73a01acaf) | Aug 07, 2023 |
| AZW           | U59                         | Desktop     | [d7b7b7641b](https://linux-hardware.org/?probe=d7b7b7641b) | Aug 07, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [78fbe42595](https://linux-hardware.org/?probe=78fbe42595) | Aug 07, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [f7845429c8](https://linux-hardware.org/?probe=f7845429c8) | Aug 07, 2023 |
| Dell          | Latitude 5480               | Notebook    | [f3f7a29ca0](https://linux-hardware.org/?probe=f3f7a29ca0) | Aug 07, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [36a20bb009](https://linux-hardware.org/?probe=36a20bb009) | Aug 07, 2023 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [f84c568d4b](https://linux-hardware.org/?probe=f84c568d4b) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [4323af2ade](https://linux-hardware.org/?probe=4323af2ade) | Aug 07, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [e9dfd6bbb6](https://linux-hardware.org/?probe=e9dfd6bbb6) | Aug 06, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [0a7dc12f31](https://linux-hardware.org/?probe=0a7dc12f31) | Aug 06, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [c130dece41](https://linux-hardware.org/?probe=c130dece41) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [a58ca66b2f](https://linux-hardware.org/?probe=a58ca66b2f) | Aug 06, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [6a53759849](https://linux-hardware.org/?probe=6a53759849) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [52bf9ffa35](https://linux-hardware.org/?probe=52bf9ffa35) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [230032816b](https://linux-hardware.org/?probe=230032816b) | Aug 06, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [97505d521e](https://linux-hardware.org/?probe=97505d521e) | Aug 06, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [34dc1bc754](https://linux-hardware.org/?probe=34dc1bc754) | Aug 06, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5bb0feab0c](https://linux-hardware.org/?probe=5bb0feab0c) | Aug 06, 2023 |
| Lenovo        | B330-15IKBR 81M1            | Notebook    | [f03fa524d7](https://linux-hardware.org/?probe=f03fa524d7) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [66d6565a06](https://linux-hardware.org/?probe=66d6565a06) | Aug 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [70aa79986f](https://linux-hardware.org/?probe=70aa79986f) | Aug 05, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [5e28b5b07a](https://linux-hardware.org/?probe=5e28b5b07a) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [6fd7ffb05b](https://linux-hardware.org/?probe=6fd7ffb05b) | Aug 04, 2023 |
| SANTECH       | NL5xNU                      | Notebook    | [68d1f62251](https://linux-hardware.org/?probe=68d1f62251) | Aug 04, 2023 |
| HP            | 8055                        | Desktop     | [21c8e1fdc2](https://linux-hardware.org/?probe=21c8e1fdc2) | Aug 03, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [2e309e76d7](https://linux-hardware.org/?probe=2e309e76d7) | Aug 03, 2023 |
| HP            | 2215                        | Desktop     | [f0589325fc](https://linux-hardware.org/?probe=f0589325fc) | Aug 03, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [0f5b976e39](https://linux-hardware.org/?probe=0f5b976e39) | Aug 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [92f3b39535](https://linux-hardware.org/?probe=92f3b39535) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [c4e404738e](https://linux-hardware.org/?probe=c4e404738e) | Aug 01, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [56e2fa207e](https://linux-hardware.org/?probe=56e2fa207e) | Aug 01, 2023 |
| Lenovo        | B330-15IKBR 81M1            | Notebook    | [1f69ed5c1e](https://linux-hardware.org/?probe=1f69ed5c1e) | Aug 01, 2023 |
| TUXEDO        | N7x0WU                      | Notebook    | [05c525a9a7](https://linux-hardware.org/?probe=05c525a9a7) | Jul 31, 2023 |
| HP            | ProBook 4740s               | Notebook    | [d0aae87145](https://linux-hardware.org/?probe=d0aae87145) | Jul 31, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [65dcccd422](https://linux-hardware.org/?probe=65dcccd422) | Jul 30, 2023 |
| HP            | ProBook 4740s               | Notebook    | [985ee4b495](https://linux-hardware.org/?probe=985ee4b495) | Jul 30, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [19b97459c1](https://linux-hardware.org/?probe=19b97459c1) | Jul 30, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [1fe8eab1c6](https://linux-hardware.org/?probe=1fe8eab1c6) | Jul 30, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [5319374e1d](https://linux-hardware.org/?probe=5319374e1d) | Jul 30, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8672df49e2](https://linux-hardware.org/?probe=8672df49e2) | Jul 30, 2023 |
| ASUSTek       | UX461UN                     | Convertible | [8f48f3562c](https://linux-hardware.org/?probe=8f48f3562c) | Jul 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [c8391bd952](https://linux-hardware.org/?probe=c8391bd952) | Jul 29, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [c8116c748a](https://linux-hardware.org/?probe=c8116c748a) | Jul 29, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [d23aa8f750](https://linux-hardware.org/?probe=d23aa8f750) | Jul 29, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [1006fe2c7b](https://linux-hardware.org/?probe=1006fe2c7b) | Jul 29, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [701402e2a7](https://linux-hardware.org/?probe=701402e2a7) | Jul 29, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [151b7d8d31](https://linux-hardware.org/?probe=151b7d8d31) | Jul 29, 2023 |
| Lenovo        | ThinkPad T420 4180C31       | Notebook    | [7fafc1656d](https://linux-hardware.org/?probe=7fafc1656d) | Jul 28, 2023 |
| Lenovo        | ThinkPad E575 20H8S02W00    | Notebook    | [afde3ea804](https://linux-hardware.org/?probe=afde3ea804) | Jul 28, 2023 |
| Dell          | 0PU052                      | Desktop     | [f51bdc3bf5](https://linux-hardware.org/?probe=f51bdc3bf5) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [06731541dd](https://linux-hardware.org/?probe=06731541dd) | Jul 28, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [cedff6ca6f](https://linux-hardware.org/?probe=cedff6ca6f) | Jul 28, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [c51105da6a](https://linux-hardware.org/?probe=c51105da6a) | Jul 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [b32778a4bd](https://linux-hardware.org/?probe=b32778a4bd) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fd41467554](https://linux-hardware.org/?probe=fd41467554) | Jul 28, 2023 |
| Google        | Blooglet                    | Notebook    | [d8c14e29b6](https://linux-hardware.org/?probe=d8c14e29b6) | Jul 27, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [e550626a11](https://linux-hardware.org/?probe=e550626a11) | Jul 27, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [900f299e10](https://linux-hardware.org/?probe=900f299e10) | Jul 26, 2023 |
| Acer          | TMP255-M                    | Notebook    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [96dcaad094](https://linux-hardware.org/?probe=96dcaad094) | Jul 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b5b201f80a](https://linux-hardware.org/?probe=b5b201f80a) | Jul 26, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [784b86f367](https://linux-hardware.org/?probe=784b86f367) | Jul 25, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [4872d1fdf6](https://linux-hardware.org/?probe=4872d1fdf6) | Jul 25, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [9acc2dda36](https://linux-hardware.org/?probe=9acc2dda36) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [cfdb26e14f](https://linux-hardware.org/?probe=cfdb26e14f) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [5262229deb](https://linux-hardware.org/?probe=5262229deb) | Jul 25, 2023 |
| MSI           | ZH77A-G41                   | Desktop     | [8528da5360](https://linux-hardware.org/?probe=8528da5360) | Jul 24, 2023 |
| Dell          | Latitude 9330               | Convertible | [715c703b85](https://linux-hardware.org/?probe=715c703b85) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [8f3dc1cb65](https://linux-hardware.org/?probe=8f3dc1cb65) | Jul 24, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [a8f7397fcf](https://linux-hardware.org/?probe=a8f7397fcf) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [7a6a20b8ed](https://linux-hardware.org/?probe=7a6a20b8ed) | Jul 23, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [4cd0b97344](https://linux-hardware.org/?probe=4cd0b97344) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [6094ce5501](https://linux-hardware.org/?probe=6094ce5501) | Jul 23, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b0e064a98a](https://linux-hardware.org/?probe=b0e064a98a) | Jul 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [46218bae31](https://linux-hardware.org/?probe=46218bae31) | Jul 23, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [bda4392623](https://linux-hardware.org/?probe=bda4392623) | Jul 22, 2023 |
| Dell          | Vostro 3578                 | Notebook    | [bd32828bf5](https://linux-hardware.org/?probe=bd32828bf5) | Jul 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | Notebook    | [7a3abd2e4d](https://linux-hardware.org/?probe=7a3abd2e4d) | Jul 22, 2023 |
| AMI           | Intel                       | Desktop     | [fe2999b2aa](https://linux-hardware.org/?probe=fe2999b2aa) | Jul 22, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [6285ba6300](https://linux-hardware.org/?probe=6285ba6300) | Jul 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42fc5ff144](https://linux-hardware.org/?probe=42fc5ff144) | Jul 21, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [1c164d4bc9](https://linux-hardware.org/?probe=1c164d4bc9) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [65972dbe80](https://linux-hardware.org/?probe=65972dbe80) | Jul 21, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [6df8743ac8](https://linux-hardware.org/?probe=6df8743ac8) | Jul 21, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2dbb6f2466](https://linux-hardware.org/?probe=2dbb6f2466) | Jul 20, 2023 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [3014bea7d8](https://linux-hardware.org/?probe=3014bea7d8) | Jul 20, 2023 |
| ASUSTek       | GL702VM                     | Notebook    | [f2a5e69f00](https://linux-hardware.org/?probe=f2a5e69f00) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [765ac65603](https://linux-hardware.org/?probe=765ac65603) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e6bbbc4d41](https://linux-hardware.org/?probe=e6bbbc4d41) | Jul 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3d605ad77f](https://linux-hardware.org/?probe=3d605ad77f) | Jul 19, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [3d0b2577a1](https://linux-hardware.org/?probe=3d0b2577a1) | Jul 18, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [b098dc2f61](https://linux-hardware.org/?probe=b098dc2f61) | Jul 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [f62d1b0d14](https://linux-hardware.org/?probe=f62d1b0d14) | Jul 17, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ad2c07dc8e](https://linux-hardware.org/?probe=ad2c07dc8e) | Jul 17, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [e2973a88aa](https://linux-hardware.org/?probe=e2973a88aa) | Jul 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b0c8aaef19](https://linux-hardware.org/?probe=b0c8aaef19) | Jul 16, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [ad6ff2b754](https://linux-hardware.org/?probe=ad6ff2b754) | Jul 16, 2023 |
| HP            | 83E0                        | Desktop     | [35abf30fff](https://linux-hardware.org/?probe=35abf30fff) | Jul 16, 2023 |
| ASUSTek       | X75A1                       | Notebook    | [745ef2a79f](https://linux-hardware.org/?probe=745ef2a79f) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [d06ca4b9c2](https://linux-hardware.org/?probe=d06ca4b9c2) | Jul 16, 2023 |
| ASUSTek       | N53SM                       | Notebook    | [103e7e5196](https://linux-hardware.org/?probe=103e7e5196) | Jul 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [5e43c9d869](https://linux-hardware.org/?probe=5e43c9d869) | Jul 15, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [a9cb1108f6](https://linux-hardware.org/?probe=a9cb1108f6) | Jul 15, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [6b86cc4c89](https://linux-hardware.org/?probe=6b86cc4c89) | Jul 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [a01053a59a](https://linux-hardware.org/?probe=a01053a59a) | Jul 15, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [479e8276b4](https://linux-hardware.org/?probe=479e8276b4) | Jul 15, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [567736ec02](https://linux-hardware.org/?probe=567736ec02) | Jul 14, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [c9a21bf55e](https://linux-hardware.org/?probe=c9a21bf55e) | Jul 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [be15faa71b](https://linux-hardware.org/?probe=be15faa71b) | Jul 14, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b8b0b27baf](https://linux-hardware.org/?probe=b8b0b27baf) | Jul 14, 2023 |
| HP            | 86F3 00100                  | All in one  | [3ab66add04](https://linux-hardware.org/?probe=3ab66add04) | Jul 14, 2023 |
| HP            | 86F3 00100                  | All in one  | [95577f518a](https://linux-hardware.org/?probe=95577f518a) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [4092f45d41](https://linux-hardware.org/?probe=4092f45d41) | Jul 14, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [1ee27caac4](https://linux-hardware.org/?probe=1ee27caac4) | Jul 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [4b9cba03ac](https://linux-hardware.org/?probe=4b9cba03ac) | Jul 13, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [7f06f99146](https://linux-hardware.org/?probe=7f06f99146) | Jul 13, 2023 |
| HP            | 3397                        | Desktop     | [d20efc761c](https://linux-hardware.org/?probe=d20efc761c) | Jul 13, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [e69bd50c8e](https://linux-hardware.org/?probe=e69bd50c8e) | Jul 13, 2023 |
| ASUSTek       | X456UV                      | Notebook    | [b0a9e3905f](https://linux-hardware.org/?probe=b0a9e3905f) | Jul 13, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c8cf9bcf47](https://linux-hardware.org/?probe=c8cf9bcf47) | Jul 13, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [1c43d30f02](https://linux-hardware.org/?probe=1c43d30f02) | Jul 13, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [51cf410b69](https://linux-hardware.org/?probe=51cf410b69) | Jul 12, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [fbc602a7b6](https://linux-hardware.org/?probe=fbc602a7b6) | Jul 12, 2023 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [e62935623d](https://linux-hardware.org/?probe=e62935623d) | Jul 12, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [fa1cb6ffb8](https://linux-hardware.org/?probe=fa1cb6ffb8) | Jul 12, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NUS... | Convertible | [a1334a7b0f](https://linux-hardware.org/?probe=a1334a7b0f) | Jul 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [611ea83c30](https://linux-hardware.org/?probe=611ea83c30) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [cb6e26bcb4](https://linux-hardware.org/?probe=cb6e26bcb4) | Jul 11, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [37049406c3](https://linux-hardware.org/?probe=37049406c3) | Jul 11, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [8aadac9d4b](https://linux-hardware.org/?probe=8aadac9d4b) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [59b334f01a](https://linux-hardware.org/?probe=59b334f01a) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8f40997f5f](https://linux-hardware.org/?probe=8f40997f5f) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [7d19e6a8f5](https://linux-hardware.org/?probe=7d19e6a8f5) | Jul 10, 2023 |
| Dell          | Latitude 3490               | Notebook    | [6fcb4ace67](https://linux-hardware.org/?probe=6fcb4ace67) | Jul 10, 2023 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [1473d3cd3b](https://linux-hardware.org/?probe=1473d3cd3b) | Jul 10, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [b463aaca78](https://linux-hardware.org/?probe=b463aaca78) | Jul 10, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [1e5cf5e071](https://linux-hardware.org/?probe=1e5cf5e071) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [3cad86057a](https://linux-hardware.org/?probe=3cad86057a) | Jul 09, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [2d5d457159](https://linux-hardware.org/?probe=2d5d457159) | Jul 09, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [e853f79dd4](https://linux-hardware.org/?probe=e853f79dd4) | Jul 09, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [9fd763e236](https://linux-hardware.org/?probe=9fd763e236) | Jul 09, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [9120c3aa90](https://linux-hardware.org/?probe=9120c3aa90) | Jul 09, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [b48f49fab3](https://linux-hardware.org/?probe=b48f49fab3) | Jul 09, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [290c9aca96](https://linux-hardware.org/?probe=290c9aca96) | Jul 09, 2023 |
| Acer          | TravelMate P2510-G2-M       | Notebook    | [c96a405528](https://linux-hardware.org/?probe=c96a405528) | Jul 09, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [9dee0fcab9](https://linux-hardware.org/?probe=9dee0fcab9) | Jul 09, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [a2bd9b682d](https://linux-hardware.org/?probe=a2bd9b682d) | Jul 08, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [362fd95251](https://linux-hardware.org/?probe=362fd95251) | Jul 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e394b88e49](https://linux-hardware.org/?probe=e394b88e49) | Jul 08, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [e87ea192ea](https://linux-hardware.org/?probe=e87ea192ea) | Jul 08, 2023 |
| ASUSTek       | UX550VE                     | Notebook    | [b782a00935](https://linux-hardware.org/?probe=b782a00935) | Jul 08, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [2378ebea87](https://linux-hardware.org/?probe=2378ebea87) | Jul 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21EM... | Notebook    | [59782374c4](https://linux-hardware.org/?probe=59782374c4) | Jul 07, 2023 |
| Lenovo        | ThinkPad X250 20CLS21F00    | Notebook    | [4e47f48ca8](https://linux-hardware.org/?probe=4e47f48ca8) | Jul 07, 2023 |
| Framework     | Laptop                      | Notebook    | [ea4c4585d0](https://linux-hardware.org/?probe=ea4c4585d0) | Jul 06, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| ASUSTek       | K53SV                       | Notebook    | [851a3a00cf](https://linux-hardware.org/?probe=851a3a00cf) | Jul 05, 2023 |
| Dell          | Latitude 3490               | Notebook    | [a730cef547](https://linux-hardware.org/?probe=a730cef547) | Jul 05, 2023 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [7de6676a0c](https://linux-hardware.org/?probe=7de6676a0c) | Jul 05, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [b67973ece1](https://linux-hardware.org/?probe=b67973ece1) | Jul 04, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f3828ea18b](https://linux-hardware.org/?probe=f3828ea18b) | Jul 04, 2023 |
| MSI           | FX603                       | Notebook    | [8b0664bd4e](https://linux-hardware.org/?probe=8b0664bd4e) | Jul 04, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [87873c1e0e](https://linux-hardware.org/?probe=87873c1e0e) | Jul 03, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [cc0464c9a4](https://linux-hardware.org/?probe=cc0464c9a4) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [7aaa5d2eec](https://linux-hardware.org/?probe=7aaa5d2eec) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [6686fca24b](https://linux-hardware.org/?probe=6686fca24b) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [ccb318cd32](https://linux-hardware.org/?probe=ccb318cd32) | Jul 03, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b66a2be1fe](https://linux-hardware.org/?probe=b66a2be1fe) | Jul 03, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [40b92fc7ba](https://linux-hardware.org/?probe=40b92fc7ba) | Jul 02, 2023 |
| HP            | 8918                        | Desktop     | [da7b695c7b](https://linux-hardware.org/?probe=da7b695c7b) | Jul 02, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [e0810c9450](https://linux-hardware.org/?probe=e0810c9450) | Jul 02, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [babec703df](https://linux-hardware.org/?probe=babec703df) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [277a9bb8e4](https://linux-hardware.org/?probe=277a9bb8e4) | Jul 02, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [c0fa0d6c73](https://linux-hardware.org/?probe=c0fa0d6c73) | Jul 02, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [29b2c807e6](https://linux-hardware.org/?probe=29b2c807e6) | Jul 01, 2023 |
| MSI           | H61MA-E35                   | Desktop     | [a5b11bc53c](https://linux-hardware.org/?probe=a5b11bc53c) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [f182eda3d3](https://linux-hardware.org/?probe=f182eda3d3) | Jul 01, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [292b7f6f0f](https://linux-hardware.org/?probe=292b7f6f0f) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [559c10480e](https://linux-hardware.org/?probe=559c10480e) | Jun 30, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [661dc06ef7](https://linux-hardware.org/?probe=661dc06ef7) | Jun 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e555922bb2](https://linux-hardware.org/?probe=e555922bb2) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [954ac9a8e4](https://linux-hardware.org/?probe=954ac9a8e4) | Jun 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [265cbaedcc](https://linux-hardware.org/?probe=265cbaedcc) | Jun 30, 2023 |
| HP            | 89B5 A                      | Desktop     | [f0330163de](https://linux-hardware.org/?probe=f0330163de) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [9d40263129](https://linux-hardware.org/?probe=9d40263129) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [4e47d108a0](https://linux-hardware.org/?probe=4e47d108a0) | Jun 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [1c349accca](https://linux-hardware.org/?probe=1c349accca) | Jun 29, 2023 |
| Alienware     | 17 R4                       | Notebook    | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| Google        | Reef                        | Notebook    | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b94582735c](https://linux-hardware.org/?probe=b94582735c) | Jun 28, 2023 |
| Acer          | Aspire VN7-593G             | Notebook    | [2302cbfba7](https://linux-hardware.org/?probe=2302cbfba7) | Jun 28, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [81bbfe3459](https://linux-hardware.org/?probe=81bbfe3459) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [ebb41279ae](https://linux-hardware.org/?probe=ebb41279ae) | Jun 28, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [32e4f74711](https://linux-hardware.org/?probe=32e4f74711) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [2debd02f0c](https://linux-hardware.org/?probe=2debd02f0c) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [3b775b8099](https://linux-hardware.org/?probe=3b775b8099) | Jun 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [6f96789257](https://linux-hardware.org/?probe=6f96789257) | Jun 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f46408c9b6](https://linux-hardware.org/?probe=f46408c9b6) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [f94b4ddd1b](https://linux-hardware.org/?probe=f94b4ddd1b) | Jun 27, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [5e1d8d04f2](https://linux-hardware.org/?probe=5e1d8d04f2) | Jun 26, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [6e179dbfb0](https://linux-hardware.org/?probe=6e179dbfb0) | Jun 26, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [9dbf9f98a6](https://linux-hardware.org/?probe=9dbf9f98a6) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [4518a77b73](https://linux-hardware.org/?probe=4518a77b73) | Jun 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9af91d0ced](https://linux-hardware.org/?probe=9af91d0ced) | Jun 26, 2023 |
| HP            | 1493                        | Desktop     | [b22e0342bc](https://linux-hardware.org/?probe=b22e0342bc) | Jun 25, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [4493e92d84](https://linux-hardware.org/?probe=4493e92d84) | Jun 25, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [e460d017ec](https://linux-hardware.org/?probe=e460d017ec) | Jun 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14bd8b577f](https://linux-hardware.org/?probe=14bd8b577f) | Jun 25, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd418c39bf](https://linux-hardware.org/?probe=bd418c39bf) | Jun 25, 2023 |
| HP            | 8437                        | Desktop     | [477b6d5623](https://linux-hardware.org/?probe=477b6d5623) | Jun 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [df9521a37d](https://linux-hardware.org/?probe=df9521a37d) | Jun 24, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [090549881a](https://linux-hardware.org/?probe=090549881a) | Jun 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [85221c654f](https://linux-hardware.org/?probe=85221c654f) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [74b9f1b367](https://linux-hardware.org/?probe=74b9f1b367) | Jun 24, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [96c2d6503c](https://linux-hardware.org/?probe=96c2d6503c) | Jun 24, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e23ab4ba9](https://linux-hardware.org/?probe=0e23ab4ba9) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [3e08f1644a](https://linux-hardware.org/?probe=3e08f1644a) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [574653afac](https://linux-hardware.org/?probe=574653afac) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [fa6b09cc1d](https://linux-hardware.org/?probe=fa6b09cc1d) | Jun 23, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a3a840a283](https://linux-hardware.org/?probe=a3a840a283) | Jun 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7ba7b1dc58](https://linux-hardware.org/?probe=7ba7b1dc58) | Jun 22, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [e72c8358c4](https://linux-hardware.org/?probe=e72c8358c4) | Jun 22, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [08974b3246](https://linux-hardware.org/?probe=08974b3246) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [38c278b214](https://linux-hardware.org/?probe=38c278b214) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [816c32de98](https://linux-hardware.org/?probe=816c32de98) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [f1e506486c](https://linux-hardware.org/?probe=f1e506486c) | Jun 21, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [a6a3ed2eae](https://linux-hardware.org/?probe=a6a3ed2eae) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [edf3326608](https://linux-hardware.org/?probe=edf3326608) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Intel         | NUC7i3BNB J22859-308        | Mini pc     | [3b9990b59d](https://linux-hardware.org/?probe=3b9990b59d) | Jun 21, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [ba4e83abed](https://linux-hardware.org/?probe=ba4e83abed) | Jun 20, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [5160dd29d0](https://linux-hardware.org/?probe=5160dd29d0) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5a51d4431b](https://linux-hardware.org/?probe=5a51d4431b) | Jun 20, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8e74890c4f](https://linux-hardware.org/?probe=8e74890c4f) | Jun 19, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [98f052ad58](https://linux-hardware.org/?probe=98f052ad58) | Jun 19, 2023 |
| Framework     | Laptop                      | Notebook    | [7d010a367e](https://linux-hardware.org/?probe=7d010a367e) | Jun 19, 2023 |
| MSI           | GT70 2OC/2OD                | Notebook    | [adee2af879](https://linux-hardware.org/?probe=adee2af879) | Jun 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [bfe09e12f0](https://linux-hardware.org/?probe=bfe09e12f0) | Jun 18, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [be5a148c53](https://linux-hardware.org/?probe=be5a148c53) | Jun 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | Notebook    | [591e97398c](https://linux-hardware.org/?probe=591e97398c) | Jun 18, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c454cb2cf0](https://linux-hardware.org/?probe=c454cb2cf0) | Jun 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [0875b8b413](https://linux-hardware.org/?probe=0875b8b413) | Jun 18, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [93e28671fa](https://linux-hardware.org/?probe=93e28671fa) | Jun 18, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [a281272278](https://linux-hardware.org/?probe=a281272278) | Jun 17, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [97a4ed6110](https://linux-hardware.org/?probe=97a4ed6110) | Jun 17, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [b4cd8c843f](https://linux-hardware.org/?probe=b4cd8c843f) | Jun 17, 2023 |
| Dell          | Latitude 5491               | Notebook    | [0673ab5ff5](https://linux-hardware.org/?probe=0673ab5ff5) | Jun 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bcb3a62b53](https://linux-hardware.org/?probe=bcb3a62b53) | Jun 17, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [777a9e4f49](https://linux-hardware.org/?probe=777a9e4f49) | Jun 17, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Manjaro        | 3160      | 39.75%  |
| Manjaro 22.0.0 | 323       | 4.06%   |
| Manjaro 20.1   | 291       | 3.66%   |
| Manjaro 20.2.1 | 283       | 3.56%   |
| Manjaro 20.2   | 243       | 3.06%   |
| Manjaro 20.0.3 | 223       | 2.81%   |
| Manjaro 21.2.6 | 176       | 2.21%   |
| Manjaro 23.0.0 | 171       | 2.15%   |
| Manjaro 21.1.0 | 149       | 1.87%   |
| Manjaro 18.1.5 | 143       | 1.8%    |
| Manjaro 21.2.0 | 127       | 1.6%    |
| Manjaro 21.2.5 | 126       | 1.58%   |
| Manjaro 21.1.6 | 114       | 1.43%   |
| Manjaro 21.0.7 | 113       | 1.42%   |
| Manjaro 20.0   | 101       | 1.27%   |
| Manjaro 19.0.2 | 97        | 1.22%   |
| Manjaro 18.0.4 | 96        | 1.21%   |
| Manjaro 21.0   | 87        | 1.09%   |
| Manjaro 23.1.0 | 85        | 1.07%   |
| Manjaro 21.0.5 | 80        | 1.01%   |
| Manjaro 20.1.2 | 80        | 1.01%   |
| Manjaro 21.2.3 | 74        | 0.93%   |
| Manjaro 21.2.1 | 73        | 0.92%   |
| Manjaro 22.1.0 | 72        | 0.91%   |
| Manjaro 20.1.1 | 71        | 0.89%   |
| Manjaro 20.0.1 | 69        | 0.87%   |
| Manjaro 22.0.4 | 56        | 0.7%    |
| Manjaro 21.3.7 | 56        | 0.7%    |
| Manjaro 21.3.6 | 50        | 0.63%   |
| Manjaro 21.0.4 | 50        | 0.63%   |
| Manjaro 23.0.4 | 47        | 0.59%   |
| Manjaro 21.2.2 | 46        | 0.58%   |
| Manjaro 21.2.4 | 45        | 0.57%   |
| Manjaro 21.1.2 | 41        | 0.52%   |
| Manjaro 21.1.4 | 37        | 0.47%   |
| Manjaro 21.0.1 | 36        | 0.45%   |
| Manjaro 22.0.5 | 35        | 0.44%   |
| Manjaro 21.0.2 | 34        | 0.43%   |
| Manjaro 23.0.2 | 32        | 0.4%    |
| Manjaro 21.3.1 | 32        | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Manjaro | 7289      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 295       | 3.39%   |
| 5.13.19-2-MANJARO | 181       | 2.08%   |
| 5.8.6-1-MANJARO   | 140       | 1.61%   |
| 5.9.11-3-MANJARO  | 129       | 1.48%   |
| 5.8.11-1-MANJARO  | 122       | 1.4%    |
| 5.15.28-1-MANJARO | 118       | 1.35%   |
| 5.10.42-1-MANJARO | 102       | 1.17%   |
| 6.1.1-1-MANJARO   | 101       | 1.16%   |
| 5.8.18-1-MANJARO  | 101       | 1.16%   |
| 5.15.32-1-MANJARO | 100       | 1.15%   |
| 6.1.12-1-MANJARO  | 86        | 0.99%   |
| 6.1.31-2-MANJARO  | 82        | 0.94%   |
| 5.15.12-1-MANJARO | 82        | 0.94%   |
| 6.5.5-1-MANJARO   | 74        | 0.85%   |
| 5.6.16-1-MANJARO  | 74        | 0.85%   |
| 5.15.60-1-MANJARO | 74        | 0.85%   |
| 5.8.16-2-MANJARO  | 73        | 0.84%   |
| 5.10.2-2-MANJARO  | 65        | 0.75%   |
| 5.15.65-1-MANJARO | 62        | 0.71%   |
| 5.7.9-1-MANJARO   | 61        | 0.7%    |
| 5.10.36-2-MANJARO | 61        | 0.7%    |
| 5.6.19-2-MANJARO  | 60        | 0.69%   |
| 5.10.7-3-MANJARO  | 60        | 0.69%   |
| 5.7.0-3-MANJARO   | 58        | 0.67%   |
| 5.8.3-2-MANJARO   | 57        | 0.65%   |
| 5.6.15-1-MANJARO  | 57        | 0.65%   |
| 5.12.9-1-MANJARO  | 54        | 0.62%   |
| 5.7.17-2-MANJARO  | 52        | 0.6%    |
| 5.15.78-1-MANJARO | 51        | 0.59%   |
| 5.15.41-1-MANJARO | 51        | 0.59%   |
| 5.14.10-1-MANJARO | 51        | 0.59%   |
| 5.9.1-1-MANJARO   | 50        | 0.57%   |
| 5.17.1-3-MANJARO  | 49        | 0.56%   |
| 5.16.14-1-MANJARO | 49        | 0.56%   |
| 5.10.23-1-MANJARO | 49        | 0.56%   |
| 5.15.74-3-MANJARO | 48        | 0.55%   |
| 5.15.7-1-MANJARO  | 48        | 0.55%   |
| 5.11.6-1-MANJARO  | 47        | 0.54%   |
| 5.15.85-1-MANJARO | 45        | 0.52%   |
| 5.15.25-1-MANJARO | 45        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.16  | 295       | 3.39%   |
| 5.13.19 | 182       | 2.09%   |
| 5.8.6   | 140       | 1.61%   |
| 5.9.11  | 136       | 1.56%   |
| 5.8.11  | 123       | 1.41%   |
| 5.15.28 | 118       | 1.36%   |
| 5.10.42 | 102       | 1.17%   |
| 6.1.1   | 101       | 1.16%   |
| 5.8.18  | 101       | 1.16%   |
| 5.15.32 | 101       | 1.16%   |
| 6.1.31  | 88        | 1.01%   |
| 6.1.12  | 86        | 0.99%   |
| 5.15.12 | 82        | 0.94%   |
| 6.5.5   | 75        | 0.86%   |
| 5.8.16  | 74        | 0.85%   |
| 5.6.16  | 74        | 0.85%   |
| 5.15.60 | 74        | 0.85%   |
| 5.7.0   | 73        | 0.84%   |
| 5.9.1   | 69        | 0.79%   |
| 5.6.19  | 66        | 0.76%   |
| 5.10.2  | 65        | 0.75%   |
| 5.15.65 | 62        | 0.71%   |
| 5.10.7  | 62        | 0.71%   |
| 5.7.9   | 61        | 0.7%    |
| 5.17.1  | 61        | 0.7%    |
| 5.10.36 | 61        | 0.7%    |
| 5.8.3   | 58        | 0.67%   |
| 5.6.15  | 57        | 0.65%   |
| 5.12.9  | 54        | 0.62%   |
| 5.7.17  | 53        | 0.61%   |
| 5.15.78 | 51        | 0.59%   |
| 5.15.41 | 51        | 0.59%   |
| 5.14.10 | 51        | 0.59%   |
| 5.15.7  | 50        | 0.57%   |
| 5.16.14 | 49        | 0.56%   |
| 5.15.74 | 49        | 0.56%   |
| 5.10.23 | 49        | 0.56%   |
| 5.11.6  | 48        | 0.55%   |
| 5.6.12  | 46        | 0.53%   |
| 5.15.2  | 46        | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1282      | 15.69%  |
| 5.10    | 926       | 11.33%  |
| 6.1     | 736       | 9.01%   |
| 5.4     | 632       | 7.73%   |
| 5.9     | 591       | 7.23%   |
| 5.8     | 553       | 6.77%   |
| 5.6     | 393       | 4.81%   |
| 5.13    | 359       | 4.39%   |
| 5.7     | 264       | 3.23%   |
| 6.5     | 233       | 2.85%   |
| 4.19    | 200       | 2.45%   |
| 5.11    | 185       | 2.26%   |
| 5.16    | 177       | 2.17%   |
| 5.12    | 157       | 1.92%   |
| 5.14    | 153       | 1.87%   |
| 6.0     | 152       | 1.86%   |
| 5.17    | 142       | 1.74%   |
| 5.19    | 139       | 1.7%    |
| 5.18    | 131       | 1.6%    |
| 5.5     | 109       | 1.33%   |
| 6.6     | 104       | 1.27%   |
| 5.3     | 92        | 1.13%   |
| 6.3     | 91        | 1.11%   |
| 6.2     | 91        | 1.11%   |
| 6.4     | 77        | 0.94%   |
| 4.14    | 60        | 0.73%   |
| 5.2     | 41        | 0.5%    |
| 5.0     | 30        | 0.37%   |
| 5.1     | 26        | 0.32%   |
| 4.20    | 14        | 0.17%   |
| 4.18    | 12        | 0.15%   |
| 6.7     | 5         | 0.06%   |
| 4.9     | 4         | 0.05%   |
| 4.16    | 4         | 0.05%   |
| 4.17    | 3         | 0.04%   |
| 4.7     | 2         | 0.02%   |
| 4.4     | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7286      | 99.96%  |
| i686    | 2         | 0.03%   |
| aarch64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| KDE5                     | 2871      | 38.09%  |
| GNOME                    | 1583      | 21%     |
| XFCE                     | 1559      | 20.68%  |
| KDE                      | 568       | 7.54%   |
| Unknown                  | 326       | 4.33%   |
| X-Cinnamon               | 191       | 2.53%   |
| i3                       | 138       | 1.83%   |
| MATE                     | 69        | 0.92%   |
| Cinnamon                 | 57        | 0.76%   |
| Deepin                   | 50        | 0.66%   |
| Budgie                   | 31        | 0.41%   |
| Awesome                  | 18        | 0.24%   |
| LXQt                     | 17        | 0.23%   |
| sway                     | 14        | 0.19%   |
| LXDE                     | 7         | 0.09%   |
| Bspwm                    | 5         | 0.07%   |
| qtile                    | 4         | 0.05%   |
| i3-with-shmlog           | 4         | 0.05%   |
| Hyprland                 | 3         | 0.04%   |
| GNOME Classic            | 3         | 0.04%   |
| DWM                      | 3         | 0.04%   |
| Yaru:ubuntu:GNOME        | 2         | 0.03%   |
| leftwm                   | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNOME Flashback          | 2         | 0.03%   |
| Enlightenment            | 2         | 0.03%   |
| xinitrc                  | 1         | 0.01%   |
| Unity                    | 1         | 0.01%   |
| swayLANG=en_CA.UTF-8     | 1         | 0.01%   |
| openbox                  | 1         | 0.01%   |
| herbstluftwm             | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 6233      | 83.91%  |
| Wayland | 977       | 13.15%  |
| Unknown | 147       | 1.98%   |
| Tty     | 71        | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3141      | 42.01%  |
| SDDM    | 1886      | 25.22%  |
| LightDM | 1259      | 16.84%  |
| GDM     | 946       | 12.65%  |
| TDM     | 218       | 2.92%   |
| LXDM    | 10        | 0.13%   |
| GREETD  | 8         | 0.11%   |
| SLiM    | 3         | 0.04%   |
| XDM     | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| LYNDE   | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 3063      | 41.45%  |
| de_DE   | 594       | 8.04%   |
| ru_RU   | 514       | 6.96%   |
| en_GB   | 514       | 6.96%   |
| Unknown | 427       | 5.78%   |
| pt_BR   | 309       | 4.18%   |
| fr_FR   | 205       | 2.77%   |
| it_IT   | 170       | 2.3%    |
| en_CA   | 160       | 2.17%   |
| es_ES   | 157       | 2.12%   |
| pl_PL   | 131       | 1.77%   |
| en_AU   | 96        | 1.3%    |
| en_IN   | 85        | 1.15%   |
| es_MX   | 69        | 0.93%   |
| zh_CN   | 57        | 0.77%   |
| de_AT   | 47        | 0.64%   |
| nl_NL   | 43        | 0.58%   |
| ru_UA   | 39        | 0.53%   |
| es_AR   | 39        | 0.53%   |
| en_IE   | 30        | 0.41%   |
| sv_SE   | 29        | 0.39%   |
| fi_FI   | 26        | 0.35%   |
| es_CL   | 25        | 0.34%   |
| de_CH   | 25        | 0.34%   |
| cs_CZ   | 25        | 0.34%   |
| hu_HU   | 24        | 0.32%   |
| pt_PT   | 23        | 0.31%   |
| C       | 22        | 0.3%    |
| tr_TR   | 21        | 0.28%   |
| en_NZ   | 20        | 0.27%   |
| en_DK   | 20        | 0.27%   |
| es_CO   | 19        | 0.26%   |
| en_ZA   | 19        | 0.26%   |
| en_PH   | 19        | 0.26%   |
| uk_UA   | 18        | 0.24%   |
| fr_CA   | 17        | 0.23%   |
| el_GR   | 14        | 0.19%   |
| nl_BE   | 13        | 0.18%   |
| en_IL   | 13        | 0.18%   |
| da_DK   | 13        | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 4136      | 55.74%  |
| EFI  | 3284      | 44.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 6096      | 82.56%  |
| Btrfs    | 766       | 10.37%  |
| Overlay  | 143       | 1.94%   |
| Unknown  | 129       | 1.75%   |
| Tmpfs    | 114       | 1.54%   |
| Xfs      | 88        | 1.19%   |
| F2fs     | 27        | 0.37%   |
| Ext3     | 6         | 0.08%   |
| Ext2     | 5         | 0.07%   |
| Zfs      | 4         | 0.05%   |
| Reiserfs | 3         | 0.04%   |
| XXXX     | 1         | 0.01%   |
| XXXfs    | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3443      | 46.26%  |
| Unknown | 3368      | 45.25%  |
| MBR     | 632       | 8.49%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6486      | 87.66%  |
| Yes       | 913       | 12.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5087      | 68.64%  |
| Yes       | 2324      | 31.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 1338      | 18.36%  |
| Lenovo              | 1169      | 16.04%  |
| Hewlett-Packard     | 946       | 12.98%  |
| Dell                | 764       | 10.48%  |
| Gigabyte Technology | 582       | 7.98%   |
| MSI                 | 569       | 7.81%   |
| Acer                | 366       | 5.02%   |
| ASRock              | 308       | 4.23%   |
| Apple               | 149       | 2.04%   |
| Intel               | 95        | 1.3%    |
| HUAWEI              | 76        | 1.04%   |
| Samsung Electronics | 73        | 1%      |
| Toshiba             | 66        | 0.91%   |
| Unknown             | 49        | 0.67%   |
| Timi                | 42        | 0.58%   |
| Fujitsu             | 42        | 0.58%   |
| Google              | 37        | 0.51%   |
| Sony                | 34        | 0.47%   |
| Notebook            | 32        | 0.44%   |
| TUXEDO              | 24        | 0.33%   |
| Microsoft           | 24        | 0.33%   |
| Biostar             | 23        | 0.32%   |
| Alienware           | 20        | 0.27%   |
| Pegatron            | 18        | 0.25%   |
| Medion              | 18        | 0.25%   |
| AZW                 | 18        | 0.25%   |
| Razer               | 16        | 0.22%   |
| Positivo            | 16        | 0.22%   |
| Schenker            | 14        | 0.19%   |
| Packard Bell        | 13        | 0.18%   |
| Huanan              | 13        | 0.18%   |
| HONOR               | 13        | 0.18%   |
| LG Electronics      | 12        | 0.16%   |
| Framework           | 12        | 0.16%   |
| Foxconn             | 12        | 0.16%   |
| Chuwi               | 11        | 0.15%   |
| BESSTAR Tech        | 10        | 0.14%   |
| System76            | 9         | 0.12%   |
| Panasonic           | 9         | 0.12%   |
| Clevo               | 8         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS All Series                     | 77        | 1.06%   |
| Unknown                             | 61        | 0.84%   |
| MSI MS-7C37                         | 32        | 0.44%   |
| MSI MS-7C02                         | 30        | 0.41%   |
| Gigabyte B450M DS3H                 | 30        | 0.41%   |
| ASUS TUF Gaming X570-PLUS           | 25        | 0.34%   |
| HP Notebook                         | 23        | 0.32%   |
| MSI MS-7C91                         | 21        | 0.29%   |
| ASUS PRIME A320M-K                  | 20        | 0.27%   |
| MSI MS-7B86                         | 17        | 0.23%   |
| Gigabyte X570 AORUS ELITE           | 16        | 0.22%   |
| ASRock B450M Pro4                   | 16        | 0.22%   |
| MSI MS-7B79                         | 15        | 0.21%   |
| MSI MS-7A38                         | 15        | 0.21%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 15        | 0.21%   |
| ASUS ROG STRIX B450-F GAMING        | 15        | 0.21%   |
| Dell XPS 13 9310                    | 14        | 0.19%   |
| ASUS ROG STRIX B550-F GAMING        | 14        | 0.19%   |
| Lenovo Legion 5 15ARH05 82B5        | 13        | 0.18%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2   | 13        | 0.18%   |
| Dell XPS 15 9500                    | 13        | 0.18%   |
| Dell OptiPlex 9020                  | 13        | 0.18%   |
| HP Pavilion Notebook                | 12        | 0.16%   |
| ASUS TUF Gaming B550M-PLUS          | 12        | 0.16%   |
| ASUS PRIME B450M-A                  | 12        | 0.16%   |
| ASUS PRIME B350-PLUS                | 12        | 0.16%   |
| MSI MS-7B89                         | 11        | 0.15%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 11        | 0.15%   |
| HP Pavilion dv7                     | 11        | 0.15%   |
| Gigabyte B450 AORUS M               | 11        | 0.15%   |
| Gigabyte B450 AORUS ELITE           | 11        | 0.15%   |
| Gigabyte 970A-DS3P                  | 11        | 0.15%   |
| Dell OptiPlex 7010                  | 11        | 0.15%   |
| Dell Inspiron 3542                  | 11        | 0.15%   |
| Apple MacBookPro9,2                 | 11        | 0.15%   |
| MSI MS-7693                         | 10        | 0.14%   |
| HP Pavilion dv6                     | 10        | 0.14%   |
| HP Laptop 15-bs0xx                  | 10        | 0.14%   |
| Gigabyte X570 AORUS MASTER          | 10        | 0.14%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 10        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 493       | 6.76%   |
| Lenovo IdeaPad     | 271       | 3.72%   |
| ASUS ROG           | 231       | 3.17%   |
| Acer Aspire        | 229       | 3.14%   |
| Dell Inspiron      | 212       | 2.91%   |
| ASUS PRIME         | 182       | 2.5%    |
| HP Pavilion        | 175       | 2.4%    |
| Dell Latitude      | 163       | 2.24%   |
| Dell XPS           | 125       | 1.71%   |
| ASUS TUF           | 122       | 1.67%   |
| HP Laptop          | 111       | 1.52%   |
| HP ProBook         | 110       | 1.51%   |
| HP EliteBook       | 110       | 1.51%   |
| ASUS VivoBook      | 92        | 1.26%   |
| Dell OptiPlex      | 91        | 1.25%   |
| Lenovo Legion      | 85        | 1.17%   |
| ASUS All           | 77        | 1.06%   |
| HP ENVY            | 76        | 1.04%   |
| Dell Precision     | 75        | 1.03%   |
| Unknown            | 61        | 0.84%   |
| Lenovo Yoga        | 60        | 0.82%   |
| HP Compaq          | 58        | 0.8%    |
| Toshiba Satellite  | 57        | 0.78%   |
| Gigabyte X570      | 53        | 0.73%   |
| Gigabyte B450M     | 47        | 0.64%   |
| Dell Vostro        | 46        | 0.63%   |
| ASUS ZenBook       | 43        | 0.59%   |
| HP OMEN            | 40        | 0.55%   |
| Acer Swift         | 38        | 0.52%   |
| Gigabyte B450      | 37        | 0.51%   |
| Acer Nitro         | 36        | 0.49%   |
| MSI MS-7C37        | 32        | 0.44%   |
| Lenovo ThinkCentre | 32        | 0.44%   |
| MSI MS-7C02        | 30        | 0.41%   |
| Fujitsu LIFEBOOK   | 30        | 0.41%   |
| ASUS ASUS          | 29        | 0.4%    |
| Lenovo ThinkBook   | 28        | 0.38%   |
| ASRock B450M       | 26        | 0.36%   |
| Gigabyte B550      | 25        | 0.34%   |
| Microsoft Surface  | 24        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 935       | 12.83%  |
| 2020    | 930       | 12.76%  |
| 2018    | 907       | 12.44%  |
| 2017    | 594       | 8.15%   |
| 2021    | 565       | 7.75%   |
| 2012    | 528       | 7.24%   |
| 2013    | 420       | 5.76%   |
| 2014    | 406       | 5.57%   |
| 2011    | 364       | 4.99%   |
| 2016    | 350       | 4.8%    |
| 2015    | 344       | 4.72%   |
| 2022    | 265       | 3.64%   |
| 2010    | 219       | 3%      |
| 2009    | 144       | 1.98%   |
| 2008    | 130       | 1.78%   |
| 2007    | 87        | 1.19%   |
| 2023    | 69        | 0.95%   |
| 2006    | 21        | 0.29%   |
| Unknown | 6         | 0.08%   |
| 2005    | 5         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 4030      | 55.29%  |
| Desktop     | 2786      | 38.22%  |
| Convertible | 269       | 3.69%   |
| Mini pc     | 87        | 1.19%   |
| All in one  | 56        | 0.77%   |
| Tablet      | 52        | 0.71%   |
| Server      | 8         | 0.11%   |
| Phone       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7285      | 99.9%   |
| Enabled  | 7         | 0.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7234      | 99.25%  |
| Yes  | 55        | 0.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1983      | 26.82%  |
| 4.01-8.0        | 1600      | 21.64%  |
| 8.01-16.0       | 1461      | 19.76%  |
| 32.01-64.0      | 979       | 13.24%  |
| 3.01-4.0        | 821       | 11.11%  |
| 64.01-256.0     | 215       | 2.91%   |
| 24.01-32.0      | 186       | 2.52%   |
| 1.01-2.0        | 107       | 1.45%   |
| 2.01-3.0        | 38        | 0.51%   |
| More than 256.0 | 2         | 0.03%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 2042      | 25.06%  |
| 4.01-8.0        | 1906      | 23.39%  |
| 1.01-2.0        | 1876      | 23.02%  |
| 3.01-4.0        | 1399      | 17.17%  |
| 8.01-16.0       | 567       | 6.96%   |
| 0.51-1.0        | 226       | 2.77%   |
| 16.01-24.0      | 74        | 0.91%   |
| 24.01-32.0      | 22        | 0.27%   |
| 0.01-0.5        | 20        | 0.25%   |
| 32.01-64.0      | 15        | 0.18%   |
| More than 256.0 | 1         | 0.01%   |
| 64.01-256.0     | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3823      | 50.83%  |
| 2      | 2128      | 28.29%  |
| 3      | 756       | 10.05%  |
| 4      | 405       | 5.38%   |
| 5      | 217       | 2.89%   |
| 6      | 83        | 1.1%    |
| 7      | 39        | 0.52%   |
| 0      | 31        | 0.41%   |
| 8      | 17        | 0.23%   |
| 9      | 11        | 0.15%   |
| 11     | 5         | 0.07%   |
| 10     | 3         | 0.04%   |
| 12     | 2         | 0.03%   |
| 20     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5371      | 73.03%  |
| Yes       | 1984      | 26.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6062      | 83.02%  |
| No        | 1240      | 16.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5778      | 78.74%  |
| No        | 1560      | 21.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4946      | 67.11%  |
| No        | 2424      | 32.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1236      | 16.83%  |
| Germany      | 872       | 11.88%  |
| Russia       | 653       | 8.89%   |
| Brazil       | 428       | 5.83%   |
| France       | 280       | 3.81%   |
| UK           | 259       | 3.53%   |
| Italy        | 250       | 3.41%   |
| Canada       | 236       | 3.21%   |
| Poland       | 212       | 2.89%   |
| Spain        | 210       | 2.86%   |
| Netherlands  | 165       | 2.25%   |
| Ukraine      | 147       | 2%      |
| India        | 133       | 1.81%   |
| Australia    | 108       | 1.47%   |
| Sweden       | 103       | 1.4%    |
| Mexico       | 103       | 1.4%    |
| Austria      | 99        | 1.35%   |
| Switzerland  | 77        | 1.05%   |
| China        | 76        | 1.04%   |
| Romania      | 66        | 0.9%    |
| Turkey       | 65        | 0.89%   |
| Finland      | 65        | 0.89%   |
| Belgium      | 64        | 0.87%   |
| Czechia      | 60        | 0.82%   |
| Hungary      | 58        | 0.79%   |
| Argentina    | 58        | 0.79%   |
| Portugal     | 56        | 0.76%   |
| Greece       | 56        | 0.76%   |
| Norway       | 52        | 0.71%   |
| Bulgaria     | 52        | 0.71%   |
| Indonesia    | 51        | 0.69%   |
| Belarus      | 47        | 0.64%   |
| Denmark      | 44        | 0.6%    |
| Colombia     | 35        | 0.48%   |
| Chile        | 34        | 0.46%   |
| Taiwan       | 31        | 0.42%   |
| Bangladesh   | 30        | 0.41%   |
| South Africa | 29        | 0.39%   |
| Israel       | 28        | 0.38%   |
| Iran         | 28        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 156       | 2.01%   |
| St Petersburg     | 85        | 1.09%   |
| Berlin            | 62        | 0.8%    |
| Vienna            | 58        | 0.75%   |
| Paris             | 54        | 0.7%    |
| Sao Paulo         | 50        | 0.64%   |
| Warsaw            | 47        | 0.61%   |
| Kyiv              | 43        | 0.55%   |
| Amsterdam         | 43        | 0.55%   |
| Frankfurt am Main | 39        | 0.5%    |
| Toronto           | 35        | 0.45%   |
| Milan             | 34        | 0.44%   |
| Madrid            | 34        | 0.44%   |
| Hamburg           | 34        | 0.44%   |
| Munich            | 31        | 0.4%    |
| Rome              | 30        | 0.39%   |
| Helsinki          | 29        | 0.37%   |
| Stockholm         | 28        | 0.36%   |
| Minsk             | 28        | 0.36%   |
| Melbourne         | 28        | 0.36%   |
| Athens            | 28        | 0.36%   |
| Sydney            | 26        | 0.33%   |
| Istanbul          | 26        | 0.33%   |
| Novosibirsk       | 25        | 0.32%   |
| Bucharest         | 25        | 0.32%   |
| London            | 24        | 0.31%   |
| Bengaluru         | 24        | 0.31%   |
| Barcelona         | 24        | 0.31%   |
| Sofia             | 23        | 0.3%    |
| Seattle           | 23        | 0.3%    |
| Yekaterinburg     | 22        | 0.28%   |
| Rio de Janeiro    | 22        | 0.28%   |
| Prague            | 22        | 0.28%   |
| Mexico City       | 22        | 0.28%   |
| Cologne           | 22        | 0.28%   |
| Budapest          | 22        | 0.28%   |
| Krakow            | 21        | 0.27%   |
| Dhaka             | 20        | 0.26%   |
| Stuttgart         | 19        | 0.24%   |
| Portland          | 19        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2108      | 3261   | 17.52%  |
| WDC                         | 1653      | 2518   | 13.74%  |
| Seagate                     | 1582      | 2411   | 13.15%  |
| Toshiba                     | 748       | 937    | 6.22%   |
| SanDisk                     | 744       | 982    | 6.19%   |
| Kingston                    | 692       | 905    | 5.75%   |
| Crucial                     | 517       | 723    | 4.3%    |
| Unknown                     | 369       | 487    | 3.07%   |
| SK hynix                    | 341       | 412    | 2.83%   |
| Intel                       | 336       | 443    | 2.79%   |
| Hitachi                     | 243       | 320    | 2.02%   |
| HGST                        | 222       | 288    | 1.85%   |
| Micron Technology           | 191       | 242    | 1.59%   |
| A-DATA Technology           | 160       | 219    | 1.33%   |
| Phison                      | 134       | 184    | 1.11%   |
| China                       | 118       | 153    | 0.98%   |
| Silicon Motion              | 92        | 119    | 0.76%   |
| Micron/Crucial Technology   | 89        | 110    | 0.74%   |
| KIOXIA                      | 88        | 103    | 0.73%   |
| Apple                       | 87        | 107    | 0.72%   |
| Phison Electronics          | 86        | 97     | 0.71%   |
| Transcend                   | 61        | 68     | 0.51%   |
| PNY                         | 58        | 88     | 0.48%   |
| SPCC                        | 55        | 65     | 0.46%   |
| Intenso                     | 51        | 70     | 0.42%   |
| Patriot                     | 49        | 64     | 0.41%   |
| OCZ                         | 49        | 69     | 0.41%   |
| GOODRAM                     | 49        | 79     | 0.41%   |
| JMicron Technology          | 47        | 55     | 0.39%   |
| Kingston Technology Company | 44        | 47     | 0.37%   |
| XPG                         | 43        | 54     | 0.36%   |
| Plextor                     | 36        | 48     | 0.3%    |
| Corsair                     | 36        | 47     | 0.3%    |
| Realtek Semiconductor       | 35        | 43     | 0.29%   |
| LITEON                      | 35        | 42     | 0.29%   |
| LITEONIT                    | 33        | 42     | 0.27%   |
| ADATA Technology            | 30        | 39     | 0.25%   |
| Lexar                       | 26        | 31     | 0.22%   |
| Team                        | 25        | 32     | 0.21%   |
| Apacer                      | 24        | 26     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 162       | 1.2%    |
| Kingston SA400S37240G 240GB SSD                     | 139       | 1.03%   |
| Samsung SSD 860 EVO 500GB                           | 123       | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB                      | 112       | 0.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 97        | 0.72%   |
| Samsung SSD 850 EVO 500GB                           | 94        | 0.7%    |
| Crucial CT500MX500SSD1 500GB                        | 88        | 0.65%   |
| Samsung NVMe SSD Drive 512GB                        | 86        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB                      | 85        | 0.63%   |
| Samsung SSD 850 EVO 250GB                           | 85        | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB                      | 84        | 0.62%   |
| Samsung NVMe SSD Drive 500GB                        | 83        | 0.62%   |
| Kingston SA400S37120G 120GB SSD                     | 83        | 0.62%   |
| Samsung NVMe SSD Drive 1TB                          | 82        | 0.61%   |
| Kingston SA400S37480G 480GB SSD                     | 77        | 0.57%   |
| Crucial CT1000MX500SSD1 1TB                         | 77        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 72        | 0.53%   |
| Samsung SSD 860 EVO 1TB                             | 70        | 0.52%   |
| Toshiba MQ01ABD100 1TB                              | 69        | 0.51%   |
| HGST HTS721010A9E630 1TB                            | 66        | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 63        | 0.47%   |
| Toshiba DT01ACA100 1TB                              | 63        | 0.47%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 61        | 0.45%   |
| Crucial CT240BX500SSD1 240GB                        | 61        | 0.45%   |
| Unknown MMC Card  64GB                              | 60        | 0.44%   |
| Toshiba MQ04ABF100 1TB                              | 60        | 0.44%   |
| Samsung SSD 860 EVO 250GB                           | 60        | 0.44%   |
| SK hynix NVMe SSD Drive 512GB                       | 55        | 0.41%   |
| Seagate Expansion 2TB                               | 55        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                        | 52        | 0.39%   |
| Unknown SD/MMC/MS PRO 512GB                         | 48        | 0.36%   |
| Samsung SSD 980 1TB                                 | 48        | 0.36%   |
| Toshiba MQ01ABF050 500GB                            | 47        | 0.35%   |
| Seagate ST500DM002-1BD142 500GB                     | 46        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB                      | 46        | 0.34%   |
| SanDisk NVMe SSD Drive 500GB                        | 45        | 0.33%   |
| Unknown MMC Card  32GB                              | 44        | 0.33%   |
| Intel NVMe SSD Drive 512GB                          | 44        | 0.33%   |
| Toshiba HDWD110 1TB                                 | 43        | 0.32%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 43        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1542      | 2334   | 36.39%  |
| WDC                 | 1324      | 2006   | 31.24%  |
| Toshiba             | 550       | 690    | 12.98%  |
| Hitachi             | 243       | 320    | 5.73%   |
| HGST                | 220       | 286    | 5.19%   |
| Samsung Electronics | 161       | 243    | 3.8%    |
| Unknown             | 54        | 66     | 1.27%   |
| Fujitsu             | 20        | 29     | 0.47%   |
| Apple               | 20        | 25     | 0.47%   |
| Maxtor              | 15        | 17     | 0.35%   |
| SABRENT             | 14        | 14     | 0.33%   |
| TO Exter            | 9         | 12     | 0.21%   |
| USB3.0              | 8         | 8      | 0.19%   |
| Intenso             | 8         | 13     | 0.19%   |
| External            | 6         | 8      | 0.14%   |
| ASMT                | 6         | 12     | 0.14%   |
| JMicron Technology  | 5         | 9      | 0.12%   |
| USB                 | 4         | 4      | 0.09%   |
| Hewlett-Packard     | 4         | 4      | 0.09%   |
| MaxDigital          | 3         | 3      | 0.07%   |
| HGST HTS            | 3         | 3      | 0.07%   |
| SSK                 | 2         | 3      | 0.05%   |
| Maxone              | 2         | 3      | 0.05%   |
| Apricorn            | 2         | 2      | 0.05%   |
| StoreJet            | 1         | 1      | 0.02%   |
| QNAP                | 1         | 1      | 0.02%   |
| Pioneer             | 1         | 3      | 0.02%   |
| MARSHAL             | 1         | 1      | 0.02%   |
| Lenovo              | 1         | 1      | 0.02%   |
| KESU                | 1         | 1      | 0.02%   |
| Initio              | 1         | 1      | 0.02%   |
| Inateck             | 1         | 1      | 0.02%   |
| IBM/Hitachi         | 1         | 1      | 0.02%   |
| IB-377U3            | 1         | 1      | 0.02%   |
| HPE                 | 1         | 1      | 0.02%   |
| ACASIS              | 1         | 1      | 0.02%   |
| Unknown             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1013      | 1444   | 24.9%   |
| Kingston            | 549       | 705    | 13.49%  |
| Crucial             | 476       | 673    | 11.7%   |
| SanDisk             | 335       | 442    | 8.23%   |
| WDC                 | 245       | 322    | 6.02%   |
| A-DATA Technology   | 131       | 180    | 3.22%   |
| China               | 118       | 153    | 2.9%    |
| Intel               | 101       | 127    | 2.48%   |
| Micron Technology   | 74        | 94     | 1.82%   |
| SK hynix            | 66        | 78     | 1.62%   |
| Toshiba             | 57        | 73     | 1.4%    |
| Transcend           | 54        | 60     | 1.33%   |
| PNY                 | 52        | 82     | 1.28%   |
| OCZ                 | 49        | 69     | 1.2%    |
| Apple               | 48        | 54     | 1.18%   |
| GOODRAM             | 47        | 77     | 1.16%   |
| Patriot             | 46        | 61     | 1.13%   |
| SPCC                | 44        | 53     | 1.08%   |
| Intenso             | 34        | 46     | 0.84%   |
| Plextor             | 33        | 45     | 0.81%   |
| LITEONIT            | 33        | 42     | 0.81%   |
| LITEON              | 29        | 36     | 0.71%   |
| Lexar               | 25        | 30     | 0.61%   |
| Corsair             | 25        | 34     | 0.61%   |
| Apacer              | 23        | 25     | 0.57%   |
| JMicron Technology  | 22        | 23     | 0.54%   |
| Team                | 21        | 28     | 0.52%   |
| Seagate             | 18        | 25     | 0.44%   |
| KingSpec            | 17        | 20     | 0.42%   |
| Gigabyte Technology | 15        | 21     | 0.37%   |
| Netac               | 14        | 21     | 0.34%   |
| Leven               | 12        | 13     | 0.29%   |
| Unknown             | 12        | 15     | 0.29%   |
| KingDian            | 11        | 11     | 0.27%   |
| ASMT                | 10        | 14     | 0.25%   |
| Hewlett-Packard     | 9         | 13     | 0.22%   |
| Mushkin             | 8         | 10     | 0.2%    |
| NGFF                | 7         | 7      | 0.17%   |
| Unknown             | 6         | 7      | 0.15%   |
| Hoodisk             | 6         | 7      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3436      | 6129   | 32.66%  |
| SSD     | 3418      | 5469   | 32.49%  |
| NVMe    | 3208      | 4637   | 30.49%  |
| MMC     | 287       | 366    | 2.73%   |
| Unknown | 172       | 231    | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5183      | 11105  | 56.51%  |
| NVMe | 3206      | 4620   | 34.95%  |
| SAS  | 496       | 741    | 5.41%   |
| MMC  | 287       | 366    | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3703      | 6103   | 50.33%  |
| 0.51-1.0   | 2364      | 3487   | 32.13%  |
| 1.01-2.0   | 760       | 1117   | 10.33%  |
| 3.01-4.0   | 210       | 343    | 2.85%   |
| 4.01-10.0  | 154       | 283    | 2.09%   |
| 2.01-3.0   | 140       | 221    | 1.9%    |
| 10.01-20.0 | 26        | 44     | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1735      | 22.7%   |
| 251-500        | 1690      | 22.11%  |
| 501-1000       | 1242      | 16.25%  |
| 1001-2000      | 870       | 11.38%  |
| More than 3000 | 533       | 6.97%   |
| Unknown        | 456       | 5.97%   |
| 51-100         | 396       | 5.18%   |
| 2001-3000      | 340       | 4.45%   |
| 1-20           | 213       | 2.79%   |
| 21-50          | 169       | 2.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1567      | 19.62%  |
| 101-250        | 1300      | 16.27%  |
| 21-50          | 1291      | 16.16%  |
| 51-100         | 1072      | 13.42%  |
| 251-500        | 879       | 11%     |
| 501-1000       | 681       | 8.53%   |
| Unknown        | 456       | 5.71%   |
| 1001-2000      | 397       | 4.97%   |
| More than 3000 | 197       | 2.47%   |
| 2001-3000      | 143       | 1.79%   |
| 0              | 5         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 11        | 12     | 1.83%   |
| HGST HTS721010A9E630 1TB              | 10        | 10     | 1.67%   |
| HGST HTS545050A7E680 500GB            | 10        | 10     | 1.67%   |
| Seagate ST500DM002-1BD142 500GB       | 8         | 11     | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 8         | 8      | 1.33%   |
| Toshiba MQ01ABD100 1TB                | 7         | 9      | 1.17%   |
| HGST HTS545050A7E380 500GB            | 7         | 7      | 1.17%   |
| WDC WD5000AAKX-001CA0 500GB           | 6         | 8      | 1%      |
| Toshiba MQ01ABD050 500GB              | 6         | 6      | 1%      |
| Seagate ST500LT012-9WS142 500GB       | 6         | 24     | 1%      |
| Crucial CT525MX300SSD1 528GB          | 6         | 6      | 1%      |
| WDC WD10EARS-00Y5B1 1TB               | 5         | 5      | 0.83%   |
| Seagate ST9320325AS 320GB             | 5         | 6      | 0.83%   |
| Samsung Electronics SSD 870 EVO 1TB   | 5         | 5      | 0.83%   |
| Samsung Electronics HD103SJ 1TB       | 5         | 5      | 0.83%   |
| Hitachi HDS721010CLA332 1TB           | 5         | 5      | 0.83%   |
| HGST HTS725050A7E630 500GB            | 5         | 5      | 0.83%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 4         | 4      | 0.67%   |
| Toshiba MQ01ABF050 500GB              | 4         | 4      | 0.67%   |
| Seagate ST9500325AS 500GB             | 4         | 5      | 0.67%   |
| Seagate ST3500413AS 500GB             | 4         | 5      | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB        | 4         | 4      | 0.67%   |
| Seagate ST1000DX001-1CM162 1TB        | 4         | 6      | 0.67%   |
| Seagate ST1000DM003-9YN162 1TB        | 4         | 6      | 0.67%   |
| Samsung Electronics SSD 960 EVO 250GB | 4         | 5      | 0.67%   |
| Samsung Electronics HD103UJ 1TB       | 4         | 6      | 0.67%   |
| Kingston SV300S37A120G 120GB SSD      | 4         | 4      | 0.67%   |
| Hitachi HTS723232A7A364 320GB         | 4         | 4      | 0.67%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 0.67%   |
| WDC WD20EARS-00MVWB0 2TB              | 3         | 3      | 0.5%    |
| WDC WD15EARS-00MVWB0 1TB              | 3         | 3      | 0.5%    |
| WDC WD10JPVX-75JC3T0 1TB              | 3         | 4      | 0.5%    |
| WDC WD10EZEX-00RKKA0 1TB              | 3         | 3      | 0.5%    |
| WDC WD10EZEX-00BN5A0 1TB              | 3         | 3      | 0.5%    |
| WDC WD10EARX-00N0YB0 1TB              | 3         | 4      | 0.5%    |
| Seagate ST9750420AS 752GB             | 3         | 3      | 0.5%    |
| Seagate ST500LM021-1KJ152 500GB       | 3         | 4      | 0.5%    |
| Seagate ST4000DM000-1F2168 4TB        | 3         | 13     | 0.5%    |
| Seagate ST3250318AS 250GB             | 3         | 3      | 0.5%    |
| Seagate ST31000524AS 1TB              | 3         | 5      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 156       | 230    | 26.71%  |
| WDC                   | 135       | 157    | 23.12%  |
| HGST                  | 43        | 43     | 7.36%   |
| Samsung Electronics   | 42        | 49     | 7.19%   |
| Hitachi               | 39        | 42     | 6.68%   |
| Toshiba               | 38        | 45     | 6.51%   |
| Crucial               | 18        | 21     | 3.08%   |
| Kingston              | 17        | 17     | 2.91%   |
| Intel                 | 16        | 18     | 2.74%   |
| SanDisk               | 15        | 18     | 2.57%   |
| SK hynix              | 12        | 17     | 2.05%   |
| A-DATA Technology     | 8         | 9      | 1.37%   |
| Micron Technology     | 7         | 9      | 1.2%    |
| LITEON                | 3         | 3      | 0.51%   |
| Apacer                | 3         | 3      | 0.51%   |
| Transcend             | 2         | 2      | 0.34%   |
| OCZ                   | 2         | 2      | 0.34%   |
| KingSpec              | 2         | 3      | 0.34%   |
| Corsair               | 2         | 6      | 0.34%   |
| ASMT                  | 2         | 6      | 0.34%   |
| Unknown               | 2         | 2      | 0.34%   |
| TwinMOS               | 1         | 1      | 0.17%   |
| SPCC                  | 1         | 1      | 0.17%   |
| Realtek Semiconductor | 1         | 1      | 0.17%   |
| Realtek               | 1         | 1      | 0.17%   |
| Phison                | 1         | 2      | 0.17%   |
| Patriot               | 1         | 1      | 0.17%   |
| Netac                 | 1         | 1      | 0.17%   |
| Maxtor                | 1         | 1      | 0.17%   |
| MaxDigital            | 1         | 1      | 0.17%   |
| MARSHAL               | 1         | 1      | 0.17%   |
| LITEONIT              | 1         | 1      | 0.17%   |
| JMicron Technology    | 1         | 1      | 0.17%   |
| Intenso               | 1         | 4      | 0.17%   |
| IM3D                  | 1         | 1      | 0.17%   |
| Hewlett-Packard       | 1         | 1      | 0.17%   |
| Fujitsu               | 1         | 1      | 0.17%   |
| Faspeed               | 1         | 1      | 0.17%   |
| Drevo                 | 1         | 1      | 0.17%   |
| China                 | 1         | 1      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 155       | 227    | 36.3%   |
| WDC                 | 132       | 154    | 30.91%  |
| HGST                | 43        | 43     | 10.07%  |
| Hitachi             | 39        | 42     | 9.13%   |
| Toshiba             | 34        | 41     | 7.96%   |
| Samsung Electronics | 20        | 25     | 4.68%   |
| Maxtor              | 1         | 1      | 0.23%   |
| MaxDigital          | 1         | 1      | 0.23%   |
| MARSHAL             | 1         | 1      | 0.23%   |
| Fujitsu             | 1         | 1      | 0.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 405       | 536    | 72.45%  |
| SSD  | 127       | 160    | 22.72%  |
| NVMe | 27        | 30     | 4.83%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB                     | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-24ZEST0 320GB                     | 1         | 1      | 6.67%   |
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 6.67%   |
| WDC WD1600AAJS-65WAA0 160GB                      | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 6.67%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 6.67%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 6.67%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 6.67%   |
| Seagate ST31000524AS 1TB                         | 1         | 2      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 6.67%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 33.33%  |
| Seagate             | 4         | 5      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Kingston            | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4729      | 10513  | 58.59%  |
| Works    | 2788      | 5577   | 34.54%  |
| Malfunc  | 539       | 726    | 6.68%   |
| Failed   | 15        | 16     | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4292      | 42.91%  |
| AMD                              | 1937      | 19.37%  |
| Samsung Electronics              | 1181      | 11.81%  |
| SanDisk                          | 547       | 5.47%   |
| SK hynix                         | 272       | 2.72%   |
| Phison Electronics               | 233       | 2.33%   |
| Kingston Technology Company      | 195       | 1.95%   |
| ASMedia Technology               | 185       | 1.85%   |
| Toshiba America Info Systems     | 138       | 1.38%   |
| Micron/Crucial Technology        | 131       | 1.31%   |
| Micron Technology                | 116       | 1.16%   |
| Silicon Motion                   | 110       | 1.1%    |
| KIOXIA                           | 101       | 1.01%   |
| ADATA Technology                 | 83        | 0.83%   |
| Marvell Technology Group         | 82        | 0.82%   |
| JMicron Technology               | 69        | 0.69%   |
| Nvidia                           | 63        | 0.63%   |
| Realtek Semiconductor            | 49        | 0.49%   |
| Union Memory (Shenzhen)          | 35        | 0.35%   |
| Solid State Storage Technology   | 22        | 0.22%   |
| Lite-On Technology               | 19        | 0.19%   |
| Apple                            | 19        | 0.19%   |
| Shenzhen Longsys Electronics     | 16        | 0.16%   |
| Seagate Technology               | 16        | 0.16%   |
| MAXIO Technology (Hangzhou)      | 12        | 0.12%   |
| LSI Logic / Symbios Logic        | 10        | 0.1%    |
| VIA Technologies                 | 8         | 0.08%   |
| Lenovo                           | 7         | 0.07%   |
| Broadcom / LSI                   | 7         | 0.07%   |
| Yangtze Memory Technologies      | 6         | 0.06%   |
| Silicon Image                    | 6         | 0.06%   |
| Biwin Storage Technology         | 5         | 0.05%   |
| INNOGRIT                         | 4         | 0.04%   |
| Adaptec                          | 4         | 0.04%   |
| Transcend                        | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| Unknown                          | 3         | 0.03%   |
| Silicon Integrated Systems [SiS] | 2         | 0.02%   |
| Netac Technology                 | 2         | 0.02%   |
| HighPoint Technologies           | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1450      | 12.83%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 629       | 5.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 396       | 3.5%    |
| AMD 400 Series Chipset SATA Controller                                         | 369       | 3.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 293       | 2.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 286       | 2.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 254       | 2.25%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 202       | 1.79%   |
| AMD 500 Series Chipset SATA Controller                                         | 182       | 1.61%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 181       | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 180       | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 173       | 1.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 169       | 1.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 158       | 1.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 157       | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 152       | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 148       | 1.31%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 144       | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 143       | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 140       | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                            | 139       | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 137       | 1.21%   |
| Intel SSD 660P Series                                                          | 127       | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 123       | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 115       | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 113       | 1%      |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 104       | 0.92%   |
| Phison E12 NVMe Controller                                                     | 104       | 0.92%   |
| Intel SATA Controller [RAID mode]                                              | 101       | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 99        | 0.88%   |
| AMD 300 Series Chipset SATA Controller                                         | 92        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 89        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 88        | 0.78%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 80        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 78        | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 72        | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 72        | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 69        | 0.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 67        | 0.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 65        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5493      | 55.98%  |
| NVMe | 3216      | 32.78%  |
| RAID | 552       | 5.63%   |
| IDE  | 526       | 5.36%   |
| SAS  | 22        | 0.22%   |
| SCSI | 3         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 4911      | 67.37%  |
| AMD    | 2378      | 32.62%  |
| ARM    | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 141       | 1.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 100       | 1.37%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 86        | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 83        | 1.14%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 80        | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 79        | 1.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 76        | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 75        | 1.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 73        | 1%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 73        | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 72        | 0.98%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 70        | 0.96%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 66        | 0.9%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 66        | 0.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 62        | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 58        | 0.79%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 58        | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 56        | 0.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 55        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 50        | 0.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 50        | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 49        | 0.67%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 47        | 0.64%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 47        | 0.64%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 47        | 0.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 46        | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 45        | 0.62%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 44        | 0.6%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 44        | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 43        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 40        | 0.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 39        | 0.53%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 37        | 0.51%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 37        | 0.51%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 37        | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 34        | 0.47%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 33        | 0.45%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 33        | 0.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 32        | 0.44%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 31        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1606      | 21.98%  |
| Intel Core i7           | 1505      | 20.6%   |
| AMD Ryzen 5             | 792       | 10.84%  |
| AMD Ryzen 7             | 656       | 8.98%   |
| Other                   | 467       | 6.39%   |
| Intel Core i3           | 424       | 5.8%    |
| Intel Celeron           | 241       | 3.3%    |
| AMD Ryzen 9             | 192       | 2.63%   |
| Intel Core 2 Duo        | 150       | 2.05%   |
| Intel Xeon              | 139       | 1.9%    |
| Intel Pentium           | 129       | 1.77%   |
| AMD FX                  | 126       | 1.72%   |
| AMD Ryzen 3             | 111       | 1.52%   |
| Intel Core i9           | 50        | 0.68%   |
| Intel Atom              | 49        | 0.67%   |
| AMD Ryzen 7 PRO         | 46        | 0.63%   |
| Intel Pentium Dual-Core | 45        | 0.62%   |
| AMD A10                 | 45        | 0.62%   |
| AMD A8                  | 42        | 0.57%   |
| AMD A4                  | 38        | 0.52%   |
| Intel Core 2 Quad       | 32        | 0.44%   |
| AMD Ryzen Threadripper  | 31        | 0.42%   |
| AMD A6                  | 31        | 0.42%   |
| AMD Phenom II X4        | 29        | 0.4%    |
| Intel Pentium Silver    | 27        | 0.37%   |
| Intel Core 2            | 24        | 0.33%   |
| AMD E1                  | 24        | 0.33%   |
| AMD Athlon              | 22        | 0.3%    |
| AMD Athlon II X2        | 21        | 0.29%   |
| AMD E                   | 19        | 0.26%   |
| AMD Ryzen 5 PRO         | 18        | 0.25%   |
| AMD Phenom II X6        | 14        | 0.19%   |
| AMD Athlon 64 X2        | 13        | 0.18%   |
| Intel Pentium Gold      | 10        | 0.14%   |
| Intel Pentium Dual      | 10        | 0.14%   |
| Intel Genuine           | 10        | 0.14%   |
| AMD E2                  | 10        | 0.14%   |
| AMD Athlon X4           | 9         | 0.12%   |
| AMD Athlon II X4        | 9         | 0.12%   |
| Intel Core m3           | 8         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2641      | 36.16%  |
| 2       | 2224      | 30.45%  |
| 6       | 1114      | 15.25%  |
| 8       | 853       | 11.68%  |
| 12      | 165       | 2.26%   |
| 16      | 92        | 1.26%   |
| 3       | 53        | 0.73%   |
| 14      | 49        | 0.67%   |
| 1       | 46        | 0.63%   |
| 10      | 45        | 0.62%   |
| 24      | 10        | 0.14%   |
| 32      | 5         | 0.07%   |
| Unknown | 3         | 0.04%   |
| 20      | 2         | 0.03%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 7263      | 99.64%  |
| 2      | 25        | 0.34%   |
| 4      | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5577      | 76.4%   |
| 1       | 1720      | 23.56%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7193      | 98.59%  |
| Unknown        | 102       | 1.4%    |
| 64-bit         | 1         | 0.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3834      | 50.82%  |
| 0x306a9    | 221       | 2.93%   |
| 0x906ea    | 186       | 2.47%   |
| 0x306c3    | 171       | 2.27%   |
| 0x206a7    | 147       | 1.95%   |
| 0x08701021 | 145       | 1.92%   |
| 0x806ea    | 137       | 1.82%   |
| 0x806ec    | 131       | 1.74%   |
| 0x806c1    | 119       | 1.58%   |
| 0x0800820d | 107       | 1.42%   |
| 0x806e9    | 100       | 1.33%   |
| 0x906e9    | 87        | 1.15%   |
| 0x406e3    | 86        | 1.14%   |
| 0x506e3    | 83        | 1.1%    |
| 0x0a50000c | 81        | 1.07%   |
| 0x40651    | 80        | 1.06%   |
| 0x08701013 | 78        | 1.03%   |
| 0x08600106 | 76        | 1.01%   |
| 0x08108102 | 72        | 0.95%   |
| 0x08108109 | 70        | 0.93%   |
| 0x1067a    | 69        | 0.91%   |
| 0x306d4    | 63        | 0.84%   |
| 0x06000852 | 53        | 0.7%    |
| 0x706e5    | 51        | 0.68%   |
| 0x08600104 | 49        | 0.65%   |
| 0xa0652    | 48        | 0.64%   |
| 0x08600103 | 48        | 0.64%   |
| 0x08608103 | 47        | 0.62%   |
| 0x806eb    | 46        | 0.61%   |
| 0x20655    | 35        | 0.46%   |
| 0x906a3    | 34        | 0.45%   |
| 0x08001138 | 33        | 0.44%   |
| 0x010000c8 | 28        | 0.37%   |
| 0x0a50000d | 27        | 0.36%   |
| 0x0a201016 | 27        | 0.36%   |
| 0x0810100b | 27        | 0.36%   |
| 0x906ed    | 24        | 0.32%   |
| 0x406c4    | 24        | 0.32%   |
| 0x08600102 | 24        | 0.32%   |
| 0x506c9    | 23        | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1381      | 18.9%   |
| Zen 2            | 653       | 8.94%   |
| Haswell          | 616       | 8.43%   |
| IvyBridge        | 466       | 6.38%   |
| Zen+             | 448       | 6.13%   |
| SandyBridge      | 397       | 5.43%   |
| Skylake          | 374       | 5.12%   |
| Zen 3            | 357       | 4.89%   |
| Unknown          | 328       | 4.49%   |
| Zen              | 226       | 3.09%   |
| TigerLake        | 218       | 2.98%   |
| Penryn           | 207       | 2.83%   |
| Broadwell        | 182       | 2.49%   |
| CometLake        | 171       | 2.34%   |
| Piledriver       | 158       | 2.16%   |
| Westmere         | 138       | 1.89%   |
| IceLake          | 123       | 1.68%   |
| Silvermont       | 121       | 1.66%   |
| K10              | 96        | 1.31%   |
| Goldmont plus    | 96        | 1.31%   |
| Alderlake Hybrid | 87        | 1.19%   |
| Core             | 84        | 1.15%   |
| Excavator        | 73        | 1%      |
| Goldmont         | 51        | 0.7%    |
| Nehalem          | 47        | 0.64%   |
| Steamroller      | 32        | 0.44%   |
| Bobcat           | 32        | 0.44%   |
| Puma             | 29        | 0.4%    |
| K8 Hammer        | 24        | 0.33%   |
| Jaguar           | 24        | 0.33%   |
| Bulldozer        | 19        | 0.26%   |
| K10 Llano        | 16        | 0.22%   |
| Bonnell          | 13        | 0.18%   |
| Tremont          | 7         | 0.1%    |
| NetBurst         | 6         | 0.08%   |
| K8 & K10 hybrid  | 5         | 0.07%   |
| Gracemont        | 2         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 3765      | 42.19%  |
| Nvidia                     | 2861      | 32.06%  |
| AMD                        | 2288      | 25.64%  |
| ASPEED Technology          | 5         | 0.06%   |
| ATI Technologies           | 3         | 0.03%   |
| Matrox Electronics Systems | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 283       | 3.1%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 277       | 3.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 255       | 2.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 244       | 2.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 230       | 2.52%   |
| Intel UHD Graphics 620                                                                   | 228       | 2.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 213       | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 192       | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 185       | 2.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 184       | 2.01%   |
| Intel HD Graphics 620                                                                    | 166       | 1.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 164       | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 141       | 1.54%   |
| Intel HD Graphics 5500                                                                   | 140       | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 129       | 1.41%   |
| Intel HD Graphics 630                                                                    | 128       | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 116       | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 110       | 1.2%    |
| Intel HD Graphics 530                                                                    | 105       | 1.15%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 102       | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 98        | 1.07%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 97        | 1.06%   |
| AMD Lucienne                                                                             | 94        | 1.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 93        | 1.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 79        | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 78        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 76        | 0.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 76        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 72        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 71        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 66        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 65        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 61        | 0.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 59        | 0.65%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 59        | 0.65%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 55        | 0.6%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 55        | 0.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 53        | 0.58%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 51        | 0.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 50        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2410      | 32.8%   |
| 1 x AMD            | 1777      | 24.19%  |
| 1 x Nvidia         | 1471      | 20.02%  |
| Intel + Nvidia     | 1119      | 15.23%  |
| AMD + Nvidia       | 240       | 3.27%   |
| Intel + AMD        | 154       | 2.1%    |
| 2 x AMD            | 127       | 1.73%   |
| 2 x Nvidia         | 30        | 0.41%   |
| 2 x Intel          | 6         | 0.08%   |
| Other              | 4         | 0.05%   |
| 1 x ASPEED         | 4         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| Nvidia + ASPEED    | 1         | 0.01%   |
| 1 x Matrox         | 1         | 0.01%   |
| Intel + 2 x AMD    | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5343      | 72.47%  |
| Proprietary | 2012      | 27.29%  |
| Unknown     | 18        | 0.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4672      | 62.74%  |
| 1.01-2.0   | 607       | 8.15%   |
| 7.01-8.0   | 474       | 6.36%   |
| 0.01-0.5   | 473       | 6.35%   |
| 3.01-4.0   | 430       | 5.77%   |
| 0.51-1.0   | 294       | 3.95%   |
| 5.01-6.0   | 256       | 3.44%   |
| 8.01-16.0  | 150       | 2.01%   |
| 2.01-3.0   | 64        | 0.86%   |
| 16.01-24.0 | 25        | 0.34%   |
| 4.01-5.0   | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 968       | 11.23%  |
| AU Optronics            | 877       | 10.18%  |
| BOE                     | 796       | 9.24%   |
| Chimei Innolux          | 755       | 8.76%   |
| LG Display              | 739       | 8.57%   |
| Goldstar                | 495       | 5.74%   |
| Dell                    | 463       | 5.37%   |
| Acer                    | 318       | 3.69%   |
| AOC                     | 258       | 2.99%   |
| BenQ                    | 245       | 2.84%   |
| Hewlett-Packard         | 236       | 2.74%   |
| Ancor Communications    | 229       | 2.66%   |
| Philips                 | 187       | 2.17%   |
| Sharp                   | 177       | 2.05%   |
| Lenovo                  | 135       | 1.57%   |
| Apple                   | 133       | 1.54%   |
| LG Electronics          | 122       | 1.42%   |
| ViewSonic               | 105       | 1.22%   |
| PANDA                   | 104       | 1.21%   |
| ASUSTek Computer        | 94        | 1.09%   |
| Chi Mei Optoelectronics | 86        | 1%      |
| Iiyama                  | 70        | 0.81%   |
| Unknown                 | 55        | 0.64%   |
| Unknown                 | 52        | 0.6%    |
| InfoVision              | 47        | 0.55%   |
| Sony                    | 45        | 0.52%   |
| CSO                     | 36        | 0.42%   |
| MSI                     | 30        | 0.35%   |
| Panasonic               | 29        | 0.34%   |
| Vizio                   | 26        | 0.3%    |
| Gigabyte Technology     | 26        | 0.3%    |
| Eizo                    | 26        | 0.3%    |
| Fujitsu Siemens         | 25        | 0.29%   |
| NEC Computers           | 24        | 0.28%   |
| TMX                     | 22        | 0.26%   |
| Sceptre Tech            | 22        | 0.26%   |
| Toshiba                 | 18        | 0.21%   |
| LGD                     | 18        | 0.21%   |
| LG Philips              | 18        | 0.21%   |
| AUS                     | 17        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 52        | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 49        | 0.54%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 46        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 45        | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 37        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 32        | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 30        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 28        | 0.31%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 24        | 0.27%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 23        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 23        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 23        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 23        | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 21        | 0.23%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 21        | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 18        | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 18        | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 18        | 0.2%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 18        | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 18        | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 16        | 0.18%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 16        | 0.18%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 15        | 0.17%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                         | 15        | 0.17%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 14        | 0.16%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.16%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                        | 14        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 14        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 14        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 14        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 13        | 0.14%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 13        | 0.14%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 13        | 0.14%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 13        | 0.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.14%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 13        | 0.14%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.14%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 12        | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3871      | 47.24%  |
| 1366x768 (WXGA)    | 1170      | 14.28%  |
| 3840x2160 (4K)     | 565       | 6.89%   |
| 2560x1440 (QHD)    | 497       | 6.06%   |
| 1600x900 (HD+)     | 223       | 2.72%   |
| Unknown            | 213       | 2.6%    |
| 1920x1200 (WUXGA)  | 189       | 2.31%   |
| 1680x1050 (WSXGA+) | 166       | 2.03%   |
| 1280x1024 (SXGA)   | 154       | 1.88%   |
| 1440x900 (WXGA+)   | 148       | 1.81%   |
| 3440x1440          | 114       | 1.39%   |
| 2560x1080          | 108       | 1.32%   |
| 1280x800 (WXGA)    | 99        | 1.21%   |
| 3840x1080          | 85        | 1.04%   |
| 2560x1600          | 83        | 1.01%   |
| 2880x1800          | 51        | 0.62%   |
| 1360x768           | 44        | 0.54%   |
| 2160x1440          | 30        | 0.37%   |
| 3840x2400          | 27        | 0.33%   |
| 1920x540           | 18        | 0.22%   |
| 2256x1504          | 17        | 0.21%   |
| 5120x1440          | 15        | 0.18%   |
| 4480x1440          | 15        | 0.18%   |
| 3200x1800 (QHD+)   | 14        | 0.17%   |
| 3840x1600          | 13        | 0.16%   |
| 1280x720 (HD)      | 12        | 0.15%   |
| 3456x2160          | 11        | 0.13%   |
| 2736x1824          | 11        | 0.13%   |
| 1024x768 (XGA)     | 11        | 0.13%   |
| 5760x1080          | 10        | 0.12%   |
| 3200x2000          | 10        | 0.12%   |
| 1920x1280          | 9         | 0.11%   |
| 1600x1200          | 9         | 0.11%   |
| 5760x2160          | 8         | 0.1%    |
| 3840x1200          | 7         | 0.09%   |
| 3600x1080          | 7         | 0.09%   |
| 3286x1080          | 7         | 0.09%   |
| 3000x2000          | 7         | 0.09%   |
| 2520x1680          | 7         | 0.09%   |
| 2880x1920          | 6         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2079      | 24.56%  |
| 13      | 812       | 9.59%   |
| 14      | 677       | 8%      |
| Unknown | 674       | 7.96%   |
| 27      | 664       | 7.84%   |
| 24      | 639       | 7.55%   |
| 23      | 513       | 6.06%   |
| 21      | 432       | 5.1%    |
| 17      | 366       | 4.32%   |
| 31      | 204       | 2.41%   |
| 34      | 174       | 2.06%   |
| 19      | 169       | 2%      |
| 12      | 122       | 1.44%   |
| 22      | 113       | 1.33%   |
| 18      | 106       | 1.25%   |
| 20      | 87        | 1.03%   |
| 16      | 84        | 0.99%   |
| 11      | 67        | 0.79%   |
| 84      | 55        | 0.65%   |
| 40      | 48        | 0.57%   |
| 54      | 36        | 0.43%   |
| 32      | 36        | 0.43%   |
| 72      | 32        | 0.38%   |
| 25      | 27        | 0.32%   |
| 26      | 23        | 0.27%   |
| 28      | 22        | 0.26%   |
| 48      | 18        | 0.21%   |
| 65      | 17        | 0.2%    |
| 37      | 16        | 0.19%   |
| 33      | 14        | 0.17%   |
| 42      | 13        | 0.15%   |
| 29      | 11        | 0.13%   |
| 49      | 10        | 0.12%   |
| 43      | 9         | 0.11%   |
| 35      | 9         | 0.11%   |
| 52      | 8         | 0.09%   |
| 46      | 7         | 0.08%   |
| 39      | 7         | 0.08%   |
| 36      | 7         | 0.08%   |
| 10      | 7         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3229      | 38.98%  |
| 501-600        | 1649      | 19.91%  |
| 401-500        | 800       | 9.66%   |
| Unknown        | 674       | 8.14%   |
| 201-300        | 606       | 7.32%   |
| 351-400        | 460       | 5.55%   |
| 601-700        | 303       | 3.66%   |
| 701-800        | 230       | 2.78%   |
| 1001-1500      | 113       | 1.36%   |
| 1501-2000      | 102       | 1.23%   |
| 801-900        | 85        | 1.03%   |
| 901-1000       | 23        | 0.28%   |
| 101-200        | 5         | 0.06%   |
| More than 2000 | 3         | 0.04%   |
| 1-100          | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5571      | 73.99%  |
| 16/10   | 781       | 10.37%  |
| Unknown | 623       | 8.27%   |
| 21/9    | 199       | 2.64%   |
| 5/4     | 144       | 1.91%   |
| 3/2     | 118       | 1.57%   |
| 4/3     | 41        | 0.54%   |
| 32/9    | 22        | 0.29%   |
| 6/5     | 6         | 0.08%   |
| 1.00    | 5         | 0.07%   |
| 0.56    | 5         | 0.07%   |
| 0.62    | 3         | 0.04%   |
| 3.40    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
| 3.20    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2077      | 24.8%   |
| 201-250        | 1371      | 16.37%  |
| 81-90          | 1165      | 13.91%  |
| 301-350        | 678       | 8.09%   |
| Unknown        | 674       | 8.05%   |
| 351-500        | 458       | 5.47%   |
| 151-200        | 349       | 4.17%   |
| 71-80          | 324       | 3.87%   |
| 121-130        | 266       | 3.18%   |
| 251-300        | 215       | 2.57%   |
| More than 1000 | 191       | 2.28%   |
| 141-150        | 144       | 1.72%   |
| 501-1000       | 132       | 1.58%   |
| 61-70          | 105       | 1.25%   |
| 111-120        | 72        | 0.86%   |
| 51-60          | 70        | 0.84%   |
| 131-140        | 47        | 0.56%   |
| 91-100         | 25        | 0.3%    |
| 1-40           | 7         | 0.08%   |
| 41-50          | 6         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2349      | 28.91%  |
| 51-100        | 2349      | 28.91%  |
| 101-120       | 1806      | 22.23%  |
| Unknown       | 674       | 8.3%    |
| 161-240       | 562       | 6.92%   |
| More than 240 | 229       | 2.82%   |
| 1-50          | 156       | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5737      | 77.04%  |
| 2     | 1447      | 19.43%  |
| 3     | 183       | 2.46%   |
| 0     | 61        | 0.82%   |
| 4     | 19        | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4127      | 37.64%  |
| Intel                             | 3778      | 34.46%  |
| Qualcomm Atheros                  | 1057      | 9.64%   |
| Broadcom                          | 442       | 4.03%   |
| MediaTek                          | 202       | 1.84%   |
| TP-Link                           | 143       | 1.3%    |
| Ralink Technology                 | 137       | 1.25%   |
| Broadcom Limited                  | 102       | 0.93%   |
| Ralink                            | 77        | 0.7%    |
| Marvell Technology Group          | 63        | 0.57%   |
| Microsoft                         | 51        | 0.47%   |
| ASIX Electronics                  | 50        | 0.46%   |
| Xiaomi                            | 49        | 0.45%   |
| Samsung Electronics               | 48        | 0.44%   |
| Nvidia                            | 45        | 0.41%   |
| Sierra Wireless                   | 38        | 0.35%   |
| Qualcomm Atheros Communications   | 34        | 0.31%   |
| Aquantia                          | 34        | 0.31%   |
| DisplayLink                       | 32        | 0.29%   |
| Lenovo                            | 31        | 0.28%   |
| Huawei Technologies               | 29        | 0.26%   |
| ASUSTek Computer                  | 29        | 0.26%   |
| Qualcomm                          | 26        | 0.24%   |
| NetGear                           | 25        | 0.23%   |
| D-Link                            | 24        | 0.22%   |
| Dell                              | 23        | 0.21%   |
| Linksys                           | 19        | 0.17%   |
| JMicron Technology                | 17        | 0.16%   |
| Hewlett-Packard                   | 16        | 0.15%   |
| Ericsson Business Mobile Networks | 14        | 0.13%   |
| Edimax Technology                 | 14        | 0.13%   |
| Google                            | 11        | 0.1%    |
| D-Link System                     | 10        | 0.09%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.08%   |
| Microchip Technology              | 9         | 0.08%   |
| Fibocom                           | 9         | 0.08%   |
| Motorola PCS                      | 8         | 0.07%   |
| Mellanox Technologies             | 8         | 0.07%   |
| Apple                             | 8         | 0.07%   |
| ZyXEL Communications              | 7         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2869      | 22.27%  |
| Intel Wi-Fi 6 AX200                                               | 548       | 4.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 368       | 2.86%   |
| Intel I211 Gigabit Network Connection                             | 301       | 2.34%   |
| Intel Wireless 8265 / 8275                                        | 259       | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 224       | 1.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 219       | 1.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 216       | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 205       | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 200       | 1.55%   |
| Intel Wireless 7265                                               | 180       | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 165       | 1.28%   |
| Intel Wireless 7260                                               | 162       | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 161       | 1.25%   |
| Intel Wi-Fi 6 AX201                                               | 156       | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 133       | 1.03%   |
| Intel Ethernet Connection (2) I219-V                              | 130       | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 129       | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 119       | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 116       | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 113       | 0.88%   |
| Intel Wireless 8260                                               | 112       | 0.87%   |
| Intel Ethernet Controller I225-V                                  | 111       | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 108       | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 107       | 0.83%   |
| Intel Wireless-AC 9260                                            | 101       | 0.78%   |
| Intel Wireless 3165                                               | 100       | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 98        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 95        | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 92        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 87        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 83        | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 79        | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 75        | 0.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 75        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 66        | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 65        | 0.5%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 64        | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 61        | 0.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2969      | 48.43%  |
| Realtek Semiconductor                 | 1053      | 17.18%  |
| Qualcomm Atheros                      | 826       | 13.47%  |
| Broadcom                              | 323       | 5.27%   |
| MediaTek                              | 187       | 3.05%   |
| Ralink Technology                     | 137       | 2.23%   |
| TP-Link                               | 136       | 2.22%   |
| Ralink                                | 77        | 1.26%   |
| Broadcom Limited                      | 76        | 1.24%   |
| Microsoft                             | 48        | 0.78%   |
| Sierra Wireless                       | 38        | 0.62%   |
| Qualcomm Atheros Communications       | 34        | 0.55%   |
| ASUSTek Computer                      | 27        | 0.44%   |
| NetGear                               | 25        | 0.41%   |
| D-Link                                | 24        | 0.39%   |
| Dell                                  | 19        | 0.31%   |
| Linksys                               | 18        | 0.29%   |
| Marvell Technology Group              | 16        | 0.26%   |
| Qualcomm                              | 14        | 0.23%   |
| Edimax Technology                     | 13        | 0.21%   |
| Fibocom                               | 9         | 0.15%   |
| ZyXEL Communications                  | 7         | 0.11%   |
| Ericsson Business Mobile Networks     | 7         | 0.11%   |
| D-Link System                         | 7         | 0.11%   |
| Hewlett-Packard                       | 5         | 0.08%   |
| Belkin Components                     | 4         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.07%   |
| ZyDAS                                 | 3         | 0.05%   |
| Quectel Wireless Solutions            | 3         | 0.05%   |
| Mercucys                              | 3         | 0.05%   |
| IMC Networks                          | 3         | 0.05%   |
| AVM                                   | 3         | 0.05%   |
| Xiaomi                                | 2         | 0.03%   |
| Tenda                                 | 2         | 0.03%   |
| Samsung Electronics                   | 2         | 0.03%   |
| Wacom                                 | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Qualcomm Technologies                 | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 548       | 8.87%   |
| Intel Wireless 8265 / 8275                                     | 259       | 4.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 205       | 3.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 200       | 3.24%   |
| Intel Wireless 7265                                            | 180       | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 165       | 2.67%   |
| Intel Wireless 7260                                            | 162       | 2.62%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 161       | 2.6%    |
| Intel Wi-Fi 6 AX201                                            | 156       | 2.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 133       | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 129       | 2.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 119       | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 116       | 1.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 113       | 1.83%   |
| Intel Wireless 8260                                            | 112       | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 108       | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 107       | 1.73%   |
| Intel Wireless-AC 9260                                         | 101       | 1.63%   |
| Intel Wireless 3165                                            | 100       | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 98        | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 95        | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 92        | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 83        | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 79        | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 75        | 1.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 75        | 1.21%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 63        | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 61        | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 51        | 0.83%   |
| Intel Wireless 3160                                            | 49        | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 47        | 0.76%   |
| Realtek 802.11ac NIC                                           | 47        | 0.76%   |
| Ralink MT7601U Wireless Adapter                                | 47        | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 47        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 44        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 44        | 0.71%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 44        | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 44        | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                  | 41        | 0.66%   |
| Intel Centrino Wireless-N 2230                                 | 39        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3695      | 57.38%  |
| Intel                                  | 1745      | 27.1%   |
| Qualcomm Atheros                       | 317       | 4.92%   |
| Broadcom                               | 182       | 2.83%   |
| ASIX Electronics                       | 50        | 0.78%   |
| Marvell Technology Group               | 47        | 0.73%   |
| Xiaomi                                 | 46        | 0.71%   |
| Nvidia                                 | 45        | 0.7%    |
| Aquantia                               | 34        | 0.53%   |
| DisplayLink                            | 32        | 0.5%    |
| Lenovo                                 | 31        | 0.48%   |
| Broadcom Limited                       | 29        | 0.45%   |
| Samsung Electronics                    | 27        | 0.42%   |
| Huawei Technologies                    | 19        | 0.3%    |
| JMicron Technology                     | 17        | 0.26%   |
| MediaTek                               | 12        | 0.19%   |
| Qualcomm                               | 11        | 0.17%   |
| Google                                 | 10        | 0.16%   |
| Mellanox Technologies                  | 8         | 0.12%   |
| TP-Link                                | 7         | 0.11%   |
| Apple                                  | 7         | 0.11%   |
| OPPO Electronics                       | 6         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 5         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.08%   |
| Motorola PCS                           | 5         | 0.08%   |
| ICS Advent                             | 4         | 0.06%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| Microsoft                              | 3         | 0.05%   |
| HMD Global                             | 3         | 0.05%   |
| Hewlett-Packard                        | 3         | 0.05%   |
| D-Link System                          | 3         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| National Semiconductor                 | 2         | 0.03%   |
| Foxconn / Hon Hai                      | 2         | 0.03%   |
| Attansic Technology                    | 2         | 0.03%   |
| ASUSTek Computer                       | 2         | 0.03%   |
| VIA Technologies                       | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2869      | 43.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 368       | 5.58%   |
| Intel I211 Gigabit Network Connection                             | 301       | 4.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 224       | 3.4%    |
| Realtek RTL8125 2.5GbE Controller                                 | 219       | 3.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 216       | 3.27%   |
| Intel Ethernet Connection (2) I219-V                              | 130       | 1.97%   |
| Intel Ethernet Controller I225-V                                  | 111       | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 87        | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 66        | 1%      |
| Intel 82579V Gigabit Network Connection                           | 65        | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 0.92%   |
| Intel Ethernet Connection I217-V                                  | 54        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 53        | 0.8%    |
| Intel Ethernet Connection (4) I219-V                              | 48        | 0.73%   |
| Intel Ethernet Connection (2) I218-V                              | 46        | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 45        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 42        | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 40        | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                     | 40        | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 38        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 35        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 34        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 34        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 32        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 30        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 30        | 0.45%   |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 29        | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 29        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 26        | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 23        | 0.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 23        | 0.35%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 23        | 0.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.35%   |
| Intel Ethernet Connection I219-V                                  | 22        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6049      | 50.71%  |
| WiFi     | 5778      | 48.44%  |
| Modem    | 89        | 0.75%   |
| Unknown  | 12        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4526      | 59.2%   |
| Ethernet | 3118      | 40.78%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3834      | 52.36%  |
| 1     | 3216      | 43.92%  |
| 3     | 174       | 2.38%   |
| 0     | 78        | 1.07%   |
| 4     | 10        | 0.14%   |
| 5     | 8         | 0.11%   |
| 8     | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6061      | 81.67%  |
| Yes  | 1360      | 18.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2540      | 50.58%  |
| Realtek Semiconductor           | 549       | 10.93%  |
| Cambridge Silicon Radio         | 378       | 7.53%   |
| Qualcomm Atheros Communications | 350       | 6.97%   |
| IMC Networks                    | 214       | 4.26%   |
| Broadcom                        | 173       | 3.44%   |
| Lite-On Technology              | 160       | 3.19%   |
| Apple                           | 130       | 2.59%   |
| Foxconn / Hon Hai               | 120       | 2.39%   |
| ASUSTek Computer                | 111       | 2.21%   |
| Realtek                         | 50        | 1%      |
| MediaTek                        | 40        | 0.8%    |
| Ralink                          | 26        | 0.52%   |
| Hewlett-Packard                 | 24        | 0.48%   |
| Dell                            | 24        | 0.48%   |
| TP-Link                         | 22        | 0.44%   |
| Toshiba                         | 15        | 0.3%    |
| Marvell Semiconductor           | 12        | 0.24%   |
| Edimax Technology               | 11        | 0.22%   |
| Opticis                         | 9         | 0.18%   |
| Foxconn International           | 9         | 0.18%   |
| Dynex                           | 7         | 0.14%   |
| Ralink Technology               | 6         | 0.12%   |
| Alps Electric                   | 6         | 0.12%   |
| HTC (High Tech Computer)        | 5         | 0.1%    |
| Belkin Components               | 5         | 0.1%    |
| SINO WEALTH                     | 4         | 0.08%   |
| Integrated System Solution      | 4         | 0.08%   |
| Conwise Technology              | 4         | 0.08%   |
| Askey Computer                  | 4         | 0.08%   |
| USI                             | 3         | 0.06%   |
| Fujitsu                         | 2         | 0.04%   |
| Sitecom Europe                  | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 812       | 16.14%  |
| Intel AX200 Bluetooth                               | 521       | 10.36%  |
| Intel Bluetooth Device                              | 470       | 9.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 378       | 7.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 364       | 7.24%   |
| Realtek Bluetooth Radio                             | 358       | 7.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 177       | 3.52%   |
| Realtek  Bluetooth 4.2 Adapter                      | 135       | 2.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 115       | 2.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 95        | 1.89%   |
| Intel AX210 Bluetooth                               | 85        | 1.69%   |
| IMC Networks Bluetooth Radio                        | 80        | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 65        | 1.29%   |
| Apple Bluetooth USB Host Controller                 | 56        | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 54        | 1.07%   |
| IMC Networks Wireless_Device                        | 52        | 1.03%   |
| Realtek Bluetooth Radio                             | 50        | 0.99%   |
| Apple Bluetooth Host Controller                     | 50        | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 48        | 0.95%   |
| Lite-On Bluetooth Device                            | 46        | 0.91%   |
| IMC Networks Bluetooth Device                       | 46        | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 42        | 0.83%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 41        | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 40        | 0.8%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 40        | 0.8%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 39        | 0.78%   |
| MediaTek Wireless_Device                            | 38        | 0.76%   |
| Ralink RT3290 Bluetooth                             | 26        | 0.52%   |
| Foxconn / Hon Hai Wireless_Device                   | 24        | 0.48%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 23        | 0.46%   |
| TP-Link UB500 Adapter                               | 22        | 0.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 21        | 0.42%   |
| ASUS Bluetooth Device                               | 21        | 0.42%   |
| Lite-On Wireless_Device                             | 19        | 0.38%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.38%   |
| Realtek RTL8821A Bluetooth                          | 18        | 0.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 18        | 0.36%   |
| ASUS Bluetooth Radio                                | 18        | 0.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 17        | 0.34%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 17        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 4800      | 43.66%  |
| AMD                      | 2702      | 24.57%  |
| Nvidia                   | 1977      | 17.98%  |
| C-Media Electronics      | 246       | 2.24%   |
| Logitech                 | 105       | 0.95%   |
| Creative Labs            | 71        | 0.65%   |
| Kingston Technology      | 67        | 0.61%   |
| JMTek                    | 63        | 0.57%   |
| Texas Instruments        | 53        | 0.48%   |
| Focusrite-Novation       | 44        | 0.4%    |
| SteelSeries ApS          | 43        | 0.39%   |
| ASUSTek Computer         | 41        | 0.37%   |
| Realtek Semiconductor    | 40        | 0.36%   |
| Razer USA                | 39        | 0.35%   |
| Creative Technology      | 39        | 0.35%   |
| Corsair                  | 39        | 0.35%   |
| Generalplus Technology   | 38        | 0.35%   |
| Lenovo                   | 31        | 0.28%   |
| GN Netcom                | 31        | 0.28%   |
| Blue Microphones         | 29        | 0.26%   |
| Plantronics              | 27        | 0.25%   |
| BEHRINGER International  | 24        | 0.22%   |
| Sony                     | 18        | 0.16%   |
| GYROCOM C&C              | 17        | 0.15%   |
| Apple                    | 15        | 0.14%   |
| Samson Technologies      | 14        | 0.13%   |
| DSEA A/S                 | 14        | 0.13%   |
| RODE Microphones         | 11        | 0.1%    |
| Micro Star International | 11        | 0.1%    |
| M-Audio                  | 11        | 0.1%    |
| Audio-Technica           | 11        | 0.1%    |
| VIA Technologies         | 10        | 0.09%   |
| Hewlett-Packard          | 10        | 0.09%   |
| XMOS                     | 9         | 0.08%   |
| Turtle Beach             | 9         | 0.08%   |
| SAVITECH                 | 9         | 0.08%   |
| Microsoft                | 9         | 0.08%   |
| Giga-Byte Technology     | 9         | 0.08%   |
| DCMT Technology          | 9         | 0.08%   |
| Yamaha                   | 8         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 994       | 7.48%   |
| Intel Sunrise Point-LP HD Audio                                            | 593       | 4.46%   |
| AMD Starship/Matisse HD Audio Controller                                   | 493       | 3.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 493       | 3.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 455       | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 358       | 2.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 345       | 2.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 322       | 2.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 322       | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 285       | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 259       | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 218       | 1.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 218       | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 211       | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 204       | 1.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 192       | 1.44%   |
| Intel 8 Series HD Audio Controller                                         | 190       | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 189       | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 167       | 1.26%   |
| AMD FCH Azalia Controller                                                  | 167       | 1.26%   |
| Intel Broadwell-U Audio Controller                                         | 166       | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 164       | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 159       | 1.2%    |
| Intel 200 Series PCH HD Audio                                              | 151       | 1.14%   |
| Nvidia GP104 High Definition Audio Controller                              | 150       | 1.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 150       | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                               | 148       | 1.11%   |
| AMD Navi 10 HDMI Audio                                                     | 130       | 0.98%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 119       | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                              | 118       | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 115       | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 115       | 0.87%   |
| Intel CM238 HD Audio Controller                                            | 111       | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 110       | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 107       | 0.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 103       | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 97        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 96        | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 93        | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 92        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1134      | 22.69%  |
| SK hynix                     | 748       | 14.97%  |
| Kingston                     | 608       | 12.16%  |
| Micron Technology            | 516       | 10.32%  |
| Corsair                      | 369       | 7.38%   |
| Crucial                      | 325       | 6.5%    |
| Unknown                      | 316       | 6.32%   |
| G.Skill                      | 277       | 5.54%   |
| A-DATA Technology            | 116       | 2.32%   |
| Ramaxel Technology           | 77        | 1.54%   |
| Elpida                       | 63        | 1.26%   |
| Team                         | 57        | 1.14%   |
| Patriot                      | 47        | 0.94%   |
| Nanya Technology             | 44        | 0.88%   |
| Unknown (ABCD)               | 34        | 0.68%   |
| Goodram                      | 31        | 0.62%   |
| Unknown                      | 25        | 0.5%    |
| Smart                        | 22        | 0.44%   |
| Transcend                    | 20        | 0.4%    |
| AMD                          | 13        | 0.26%   |
| Apacer                       | 10        | 0.2%    |
| Silicon Power                | 7         | 0.14%   |
| Kllisre                      | 7         | 0.14%   |
| ASint Technology             | 7         | 0.14%   |
| PNY                          | 5         | 0.1%    |
| Patriot Memory (PDP Systems) | 5         | 0.1%    |
| Neo Forza                    | 5         | 0.1%    |
| GeIL                         | 5         | 0.1%    |
| Timetec                      | 4         | 0.08%   |
| Teikon                       | 4         | 0.08%   |
| Smart Brazil                 | 4         | 0.08%   |
| Qumo                         | 4         | 0.08%   |
| Kingmax                      | 4         | 0.08%   |
| Goldkey                      | 4         | 0.08%   |
| Avant                        | 4         | 0.08%   |
| Atermiter                    | 4         | 0.08%   |
| SHARETRONIC                  | 3         | 0.06%   |
| CSX                          | 3         | 0.06%   |
| Unknown (08C8)               | 2         | 0.04%   |
| TwinMOS                      | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 61        | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 59        | 1.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 50        | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 47        | 0.88%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 46        | 0.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 43        | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 37        | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 37        | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 34        | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 34        | 0.64%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 34        | 0.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 30        | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 29        | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 29        | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.5%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.49%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.49%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 26        | 0.49%   |
| Unknown                                                          | 25        | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 22        | 0.41%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 22        | 0.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 21        | 0.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 21        | 0.39%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 21        | 0.39%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 21        | 0.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 20        | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.36%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 18        | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 18        | 0.34%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 18        | 0.34%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s              | 18        | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.32%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 17        | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.32%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 17        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2437      | 56.45%  |
| DDR3    | 1189      | 27.54%  |
| LPDDR4  | 183       | 4.24%   |
| LPDDR3  | 131       | 3.03%   |
| Unknown | 87        | 2.02%   |
| DDR5    | 80        | 1.85%   |
| DDR2    | 79        | 1.83%   |
| SDRAM   | 78        | 1.81%   |
| LPDDR5  | 35        | 0.81%   |
| DDR     | 13        | 0.3%    |
| DRAM    | 5         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2346      | 54.43%  |
| DIMM         | 1523      | 35.34%  |
| Row Of Chips | 397       | 9.21%   |
| Chip         | 23        | 0.53%   |
| Unknown      | 15        | 0.35%   |
| RIMM         | 3         | 0.07%   |
| FB-DIMM      | 3         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2097      | 44.71%  |
| 4096  | 1183      | 25.22%  |
| 16384 | 770       | 16.42%  |
| 2048  | 370       | 7.89%   |
| 32768 | 190       | 4.05%   |
| 1024  | 71        | 1.51%   |
| 512   | 5         | 0.11%   |
| 3072  | 2         | 0.04%   |
| 65536 | 1         | 0.02%   |
| 12288 | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 835       | 17.67%  |
| 1600    | 822       | 17.4%   |
| 2667    | 782       | 16.55%  |
| 2400    | 343       | 7.26%   |
| 2133    | 248       | 5.25%   |
| 1333    | 213       | 4.51%   |
| 3600    | 188       | 3.98%   |
| 1867    | 107       | 2.26%   |
| 1334    | 107       | 2.26%   |
| 4267    | 79        | 1.67%   |
| 3266    | 65        | 1.38%   |
| 3400    | 61        | 1.29%   |
| 800     | 59        | 1.25%   |
| 3733    | 56        | 1.19%   |
| 3000    | 54        | 1.14%   |
| 667     | 50        | 1.06%   |
| 4800    | 48        | 1.02%   |
| Unknown | 39        | 0.83%   |
| 6400    | 38        | 0.8%    |
| 3800    | 37        | 0.78%   |
| 1866    | 36        | 0.76%   |
| 3533    | 35        | 0.74%   |
| 1067    | 34        | 0.72%   |
| 3866    | 29        | 0.61%   |
| 3466    | 27        | 0.57%   |
| 1800    | 27        | 0.57%   |
| 4199    | 26        | 0.55%   |
| 2933    | 26        | 0.55%   |
| 2666    | 22        | 0.47%   |
| 1066    | 22        | 0.47%   |
| 4266    | 21        | 0.44%   |
| 2800    | 15        | 0.32%   |
| 2048    | 13        | 0.28%   |
| 3666    | 12        | 0.25%   |
| 6000    | 10        | 0.21%   |
| 975     | 10        | 0.21%   |
| 5600    | 9         | 0.19%   |
| 5200    | 8         | 0.17%   |
| 3534    | 8         | 0.17%   |
| 8400    | 7         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 60        | 37.04%  |
| Brother Industries    | 28        | 17.28%  |
| Canon                 | 23        | 14.2%   |
| Seiko Epson           | 16        | 9.88%   |
| Samsung Electronics   | 10        | 6.17%   |
| Pantum                | 4         | 2.47%   |
| Apple                 | 3         | 1.85%   |
| Xerox                 | 2         | 1.23%   |
| STMicroelectronics    | 2         | 1.23%   |
| Ricoh                 | 2         | 1.23%   |
| Prolific Technology   | 2         | 1.23%   |
| Dymo-CoStar           | 2         | 1.23%   |
| Zebra                 | 1         | 0.62%   |
| Xiaomi                | 1         | 0.62%   |
| Sagem                 | 1         | 0.62%   |
| QinHeng Electronics   | 1         | 0.62%   |
| Oki Data              | 1         | 0.62%   |
| Lexmark International | 1         | 0.62%   |
| Kyocera               | 1         | 0.62%   |
| Graphtec America      | 1         | 0.62%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP OfficeJet 5200 series                                  | 4         | 2.45%   |
| HP LaserJet 1300                                          | 3         | 1.84%   |
| HP ENVY 4520 series                                       | 3         | 1.84%   |
| Apple Gamesir-T1s 2.0b                                    | 3         | 1.84%   |
| Xerox Phaser 3020                                         | 2         | 1.23%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.23%   |
| Seiko Epson L3150 Series                                  | 2         | 1.23%   |
| Seiko Epson L120 Series                                   | 2         | 1.23%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 1.23%   |
| Samsung M2020 Series                                      | 2         | 1.23%   |
| Prolific PL2305 Parallel Port                             | 2         | 1.23%   |
| HP Officejet 2620 series                                  | 2         | 1.23%   |
| HP LaserJet 3020                                          | 2         | 1.23%   |
| HP DeskJet 4530 series                                    | 2         | 1.23%   |
| HP DeskJet 3630 series                                    | 2         | 1.23%   |
| HP DeskJet 2700 series                                    | 2         | 1.23%   |
| HP DeskJet 2600 series                                    | 2         | 1.23%   |
| HP DeskJet 2130 series                                    | 2         | 1.23%   |
| HP Color LaserJet Pro M453-4                              | 2         | 1.23%   |
| Canon PIXMA MX340                                         | 2         | 1.23%   |
| Canon PIXMA MP250                                         | 2         | 1.23%   |
| Canon PIXMA MG2500 Series                                 | 2         | 1.23%   |
| Canon MG5700 series                                       | 2         | 1.23%   |
| Canon LiDE 400                                            | 2         | 1.23%   |
| Canon G3010 series                                        | 2         | 1.23%   |
| Brother MFC-L2710DW series                                | 2         | 1.23%   |
| Brother HL-L2300D series                                  | 2         | 1.23%   |
| Brother HL-5370DW series                                  | 2         | 1.23%   |
| Brother HL-1110 series                                    | 2         | 1.23%   |
| Brother DCP-7040                                          | 2         | 1.23%   |
| Zebra ZTC ZC100                                           | 1         | 0.61%   |
| Xiaomi MiMouse 2                                          | 1         | 0.61%   |
| Seiko Epson XP-4100 Series                                | 1         | 0.61%   |
| Seiko Epson XP-3100 Series                                | 1         | 0.61%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.61%   |
| Seiko Epson Printer                                       | 1         | 0.61%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.61%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.61%   |
| Seiko Epson L805 Series                                   | 1         | 0.61%   |
| Seiko Epson L6270 Series                                  | 1         | 0.61%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 22        | 64.71%  |
| Seiko Epson        | 6         | 17.65%  |
| Hewlett-Packard    | 2         | 5.88%   |
| Visioneer          | 1         | 2.94%   |
| Ultima Electronics | 1         | 2.94%   |
| Mustek Systems     | 1         | 2.94%   |
| AGFA-Gevaert NV    | 1         | 2.94%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                               | 5         | 14.71%  |
| Canon CanoScan LiDE 110                                                               | 5         | 14.71%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3         | 8.82%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 5.88%   |
| Canon CanoScan LIDE 25                                                                | 2         | 5.88%   |
| Canon CanoScan LiDE 210                                                               | 2         | 5.88%   |
| Visioneer OneTouch 5300 USB                                                           | 1         | 2.94%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 2.94%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 2.94%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 2.94%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 2.94%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1         | 2.94%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 2.94%   |
| HP ScanJet 3500c                                                                      | 1         | 2.94%   |
| HP ScanJet 3400cse                                                                    | 1         | 2.94%   |
| Canon CanoScan LiDE 90                                                                | 1         | 2.94%   |
| Canon CanoScan LiDE 500F                                                              | 1         | 2.94%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 2.94%   |
| Canon CanoScan LiDE 200                                                               | 1         | 2.94%   |
| Canon CanoScan LiDE 120                                                               | 1         | 2.94%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1         | 2.94%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 943       | 20.01%  |
| IMC Networks                           | 545       | 11.56%  |
| Microdia                               | 362       | 7.68%   |
| Logitech                               | 342       | 7.26%   |
| Realtek Semiconductor                  | 341       | 7.24%   |
| Bison Electronics                      | 283       | 6%      |
| Quanta                                 | 266       | 5.64%   |
| Sunplus Innovation Technology          | 206       | 4.37%   |
| Cheng Uei Precision Industry (Foxlink) | 157       | 3.33%   |
| Syntek                                 | 130       | 2.76%   |
| Lite-On Technology                     | 125       | 2.65%   |
| Apple                                  | 110       | 2.33%   |
| Suyin                                  | 97        | 2.06%   |
| Microsoft                              | 74        | 1.57%   |
| Luxvisions Innotech Limited            | 69        | 1.46%   |
| Silicon Motion                         | 61        | 1.29%   |
| Acer                                   | 61        | 1.29%   |
| Samsung Electronics                    | 54        | 1.15%   |
| Alcor Micro                            | 53        | 1.12%   |
| Sonix Technology                       | 28        | 0.59%   |
| Z-Star Microelectronics                | 27        | 0.57%   |
| Ricoh                                  | 22        | 0.47%   |
| SunplusIT                              | 17        | 0.36%   |
| Lenovo                                 | 15        | 0.32%   |
| Creative Technology                    | 15        | 0.32%   |
| MacroSilicon                           | 14        | 0.3%    |
| GEMBIRD                                | 14        | 0.3%    |
| Importek                               | 13        | 0.28%   |
| Genesys Logic                          | 11        | 0.23%   |
| Generalplus Technology                 | 11        | 0.23%   |
| Primax Electronics                     | 10        | 0.21%   |
| Cubeternet                             | 10        | 0.21%   |
| ARC International                      | 10        | 0.21%   |
| LG Electronics                         | 9         | 0.19%   |
| KYE Systems (Mouse Systems)            | 9         | 0.19%   |
| Google                                 | 8         | 0.17%   |
| icSpring                               | 7         | 0.15%   |
| DigiTech                               | 7         | 0.15%   |
| Creality 3D Technology                 | 7         | 0.15%   |
| ALi                                    | 7         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 240       | 5.05%   |
| IMC Networks Integrated Camera                      | 185       | 3.9%    |
| Microdia Integrated_Webcam_HD                       | 153       | 3.22%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 140       | 2.95%   |
| Realtek Integrated_Webcam_HD                        | 126       | 2.65%   |
| Bison Integrated Camera                             | 104       | 2.19%   |
| Chicony HD Webcam                                   | 95        | 2%      |
| Syntek Integrated Camera                            | 90        | 1.9%    |
| Logitech Webcam C270                                | 76        | 1.6%    |
| Sunplus Integrated_Webcam_HD                        | 72        | 1.52%   |
| Logitech HD Pro Webcam C920                         | 61        | 1.28%   |
| Samsung Galaxy series, misc. (MTP mode)             | 54        | 1.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 51        | 1.07%   |
| Quanta HD User Facing                               | 43        | 0.91%   |
| Lite-On Integrated Camera                           | 43        | 0.91%   |
| Chicony HP Wide Vision HD Camera                    | 41        | 0.86%   |
| Quanta HP TrueVision HD Camera                      | 37        | 0.78%   |
| Bison HD Webcam                                     | 35        | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE                           | 35        | 0.74%   |
| Chicony HP HD Camera                                | 32        | 0.67%   |
| Logitech C922 Pro Stream Webcam                     | 31        | 0.65%   |
| IMC Networks HD Camera                              | 31        | 0.65%   |
| Realtek USB camera                                  | 29        | 0.61%   |
| Lite-On HP HD Camera                                | 29        | 0.61%   |
| Chicony HD User Facing                              | 29        | 0.61%   |
| Microdia Webcam Vitade AF                           | 28        | 0.59%   |
| Microsoft LifeCam HD-3000                           | 27        | 0.57%   |
| Microdia Integrated Webcam                          | 27        | 0.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 27        | 0.57%   |
| Quanta HP Wide Vision HD Camera                     | 26        | 0.55%   |
| Chicony USB2.0 HD UVC WebCam                        | 26        | 0.55%   |
| Chicony USB2.0 Camera                               | 26        | 0.55%   |
| Chicony EasyCamera                                  | 26        | 0.55%   |
| Bison SunplusIT Integrated Camera                   | 26        | 0.55%   |
| Bison Lenovo EasyCamera                             | 26        | 0.55%   |
| Apple FaceTime HD Camera (Built-in)                 | 26        | 0.55%   |
| Quanta HD Webcam                                    | 25        | 0.53%   |
| Chicony HP TrueVision HD Camera                     | 25        | 0.53%   |
| Chicony Lenovo EasyCamera                           | 24        | 0.51%   |
| Chicony HP TrueVision HD                            | 24        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 300       | 31.28%  |
| Validity Sensors                   | 275       | 28.68%  |
| Shenzhen Goodix Technology         | 195       | 20.33%  |
| Elan Microelectronics              | 73        | 7.61%   |
| LighTuning Technology              | 38        | 3.96%   |
| Upek                               | 28        | 2.92%   |
| AuthenTec                          | 23        | 2.4%    |
| STMicroelectronics                 | 8         | 0.83%   |
| Samsung Electronics                | 6         | 0.63%   |
| Focal-systems.Corp                 | 5         | 0.52%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.31%   |
| DigitalPersona                     | 2         | 0.21%   |
| HOLTEK                             | 1         | 0.1%    |
| Futronic Technology                | 1         | 0.1%    |
| Dell                               | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 96        | 10.01%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 72        | 7.51%   |
| Shenzhen Goodix Fingerprint Reader                                         | 69        | 7.19%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 55        | 5.74%   |
| Elan ELAN:Fingerprint                                                      | 44        | 4.59%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 42        | 4.38%   |
| Synaptics UWP WBDI                                                         | 35        | 3.65%   |
| Validity Sensors Synaptics WBDI                                            | 34        | 3.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 32        | 3.34%   |
| Synaptics WBDI                                                             | 31        | 3.23%   |
| Shenzhen Goodix FingerPrint                                                | 30        | 3.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 25        | 2.61%   |
| Synaptics Fingerprint reader [HP G6]                                       | 25        | 2.61%   |
| Elan ELAN:ARM-M4                                                           | 25        | 2.61%   |
| Synaptics  WBDI                                                            | 23        | 2.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 2.4%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 1.98%   |
| Validity Sensors VFS491                                                    | 19        | 1.98%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 19        | 1.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 1.88%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 15        | 1.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 1.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.36%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 12        | 1.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 10        | 1.04%   |
| Synaptics UWP WBDI Device                                                  | 8         | 0.83%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 0.83%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.83%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 0.63%   |
| Synaptics WBDI Device                                                      | 6         | 0.63%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.52%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 5         | 0.52%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 0.52%   |
| AuthenTec AES2810                                                          | 5         | 0.52%   |
| Unknown                                                                    | 5         | 0.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 108       | 35.53%  |
| Broadcom                          | 102       | 33.55%  |
| Upek                              | 18        | 5.92%   |
| O2 Micro                          | 18        | 5.92%   |
| Lenovo                            | 17        | 5.59%   |
| Gemalto (was Gemplus)             | 11        | 3.62%   |
| Yubico.com                        | 9         | 2.96%   |
| Realtek Semiconductor             | 5         | 1.64%   |
| VASCO Data Security International | 4         | 1.32%   |
| OmniKey                           | 3         | 0.99%   |
| SCM Microsystems                  | 1         | 0.33%   |
| Reiner SCT Kartensysteme          | 1         | 0.33%   |
| Hewlett-Packard                   | 1         | 0.33%   |
| Clay Logic                        | 1         | 0.33%   |
| Cherry                            | 1         | 0.33%   |
| C3PO                              | 1         | 0.33%   |
| Bit4id                            | 1         | 0.33%   |
| Aladdin Knowledge Systems         | 1         | 0.33%   |
| Advanced Card Systems             | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 107       | 35.2%   |
| Broadcom BCM5880 Secure Applications Processor                               | 36        | 11.84%  |
| Broadcom 5880                                                                | 31        | 10.2%   |
| Broadcom 58200                                                               | 22        | 7.24%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 18        | 5.92%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 5.59%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 4.28%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 1.97%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 1.64%   |
| OmniKey 3x21 Smart Card Reader                                               | 3         | 0.99%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.99%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.66%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 2         | 0.66%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.33%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.33%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.33%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.33%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.33%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.33%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.33%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.33%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.33%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.33%   |
| Bit4id miniLector EVO                                                        | 1         | 0.33%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.33%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.33%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5180      | 69.71%  |
| 1     | 1841      | 24.77%  |
| 2     | 378       | 5.09%   |
| 3     | 28        | 0.38%   |
| 4     | 4         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 942       | 36%     |
| Graphics card            | 449       | 17.16%  |
| Net/wireless             | 336       | 12.84%  |
| Chipcard                 | 268       | 10.24%  |
| Multimedia controller    | 216       | 8.25%   |
| Camera                   | 91        | 3.48%   |
| Net/ethernet             | 67        | 2.56%   |
| Unassigned class         | 60        | 2.29%   |
| Bluetooth                | 50        | 1.91%   |
| Sound                    | 29        | 1.11%   |
| Communication controller | 27        | 1.03%   |
| Storage                  | 21        | 0.8%    |
| Card reader              | 17        | 0.65%   |
| Dvb card                 | 14        | 0.53%   |
| Network                  | 10        | 0.38%   |
| Storage/raid             | 7         | 0.27%   |
| Modem                    | 5         | 0.19%   |
| Video                    | 2         | 0.08%   |
| Storage/nvme             | 2         | 0.08%   |
| Storage/ide              | 2         | 0.08%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |

