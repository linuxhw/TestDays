Ubuntu MATE 20.04 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE_20.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE_20.04/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-mate-20.04

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
| HP            | ProBook 455 G7              | Notebook    | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5f6c245dc5](https://linux-hardware.org/?probe=5f6c245dc5) | Sep 28, 2021 |
| MSI           | H61M-P23                    | Desktop     | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [6a2e918e37](https://linux-hardware.org/?probe=6a2e918e37) | Sep 28, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [384af306e6](https://linux-hardware.org/?probe=384af306e6) | Sep 27, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [5422d3bf1d](https://linux-hardware.org/?probe=5422d3bf1d) | Sep 27, 2021 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [060da3d3ab](https://linux-hardware.org/?probe=060da3d3ab) | Sep 26, 2021 |
| HP            | 8265                        | Desktop     | [f840aed42d](https://linux-hardware.org/?probe=f840aed42d) | Sep 21, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f93c2362ff](https://linux-hardware.org/?probe=f93c2362ff) | Sep 21, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [523fe48a54](https://linux-hardware.org/?probe=523fe48a54) | Sep 19, 2021 |
| HP            | 3397                        | Desktop     | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [3c40bbda61](https://linux-hardware.org/?probe=3c40bbda61) | Sep 18, 2021 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [7983bf0ab7](https://linux-hardware.org/?probe=7983bf0ab7) | Sep 18, 2021 |
| ASRock        | H110M-STX                   | Desktop     | [6bb90d3b07](https://linux-hardware.org/?probe=6bb90d3b07) | Sep 16, 2021 |
| Teclast       | F15S                        | Notebook    | [b6fcd1a34d](https://linux-hardware.org/?probe=b6fcd1a34d) | Sep 13, 2021 |
| Teclast       | F15S                        | Notebook    | [93d4fafebd](https://linux-hardware.org/?probe=93d4fafebd) | Sep 13, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [0fdc4bc08a](https://linux-hardware.org/?probe=0fdc4bc08a) | Sep 13, 2021 |
| Dell          | Latitude E7450              | Notebook    | [012bae3aa2](https://linux-hardware.org/?probe=012bae3aa2) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | Notebook    | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [1172b42b6b](https://linux-hardware.org/?probe=1172b42b6b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [14109edfc9](https://linux-hardware.org/?probe=14109edfc9) | Sep 07, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [cb82d03efe](https://linux-hardware.org/?probe=cb82d03efe) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Acer          | Spin SP111-33               | Convertible | [2a5ddf7be8](https://linux-hardware.org/?probe=2a5ddf7be8) | Sep 05, 2021 |
| HP            | 3396                        | Desktop     | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [5ee9ab86d7](https://linux-hardware.org/?probe=5ee9ab86d7) | Aug 31, 2021 |
| ASRock        | H110M-STX                   | Desktop     | [a0b807eb42](https://linux-hardware.org/?probe=a0b807eb42) | Aug 30, 2021 |
| MSI           | Z370 PC PRO                 | Desktop     | [c594736488](https://linux-hardware.org/?probe=c594736488) | Aug 30, 2021 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [16250b0c12](https://linux-hardware.org/?probe=16250b0c12) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [41e440c2e5](https://linux-hardware.org/?probe=41e440c2e5) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e086d2eb61](https://linux-hardware.org/?probe=e086d2eb61) | Aug 29, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| Packard Be... | EasyNote SL65               | Notebook    | [934368dd02](https://linux-hardware.org/?probe=934368dd02) | Aug 20, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | Notebook    | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [70e369f2ba](https://linux-hardware.org/?probe=70e369f2ba) | Aug 19, 2021 |
| Acer          | Extensa 5630                | Notebook    | [f32dfbfe2a](https://linux-hardware.org/?probe=f32dfbfe2a) | Aug 15, 2021 |
| ASRock        | M3A785GMH/128M              | Desktop     | [4ace1ea1ac](https://linux-hardware.org/?probe=4ace1ea1ac) | Aug 15, 2021 |
| HP            | Notebook                    | Notebook    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| MSI           | X79A-GD45                   | Desktop     | [c5b78e1a01](https://linux-hardware.org/?probe=c5b78e1a01) | Aug 13, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [bbfbd42562](https://linux-hardware.org/?probe=bbfbd42562) | Aug 07, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [399d9ceec5](https://linux-hardware.org/?probe=399d9ceec5) | Aug 06, 2021 |
| Intel         | AMI                         | Notebook    | [c11ff5c3a9](https://linux-hardware.org/?probe=c11ff5c3a9) | Aug 06, 2021 |
| Intel         | AMI                         | Notebook    | [bfe9befd10](https://linux-hardware.org/?probe=bfe9befd10) | Aug 05, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [c861e28d21](https://linux-hardware.org/?probe=c861e28d21) | Aug 05, 2021 |
| ASRock        | Q1900M                      | Desktop     | [700f4a0ca1](https://linux-hardware.org/?probe=700f4a0ca1) | Aug 02, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [fe0cf5b120](https://linux-hardware.org/?probe=fe0cf5b120) | Aug 01, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [e706b18dd8](https://linux-hardware.org/?probe=e706b18dd8) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | Notebook    | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [49be4c6d59](https://linux-hardware.org/?probe=49be4c6d59) | Jul 23, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [6dcb19e468](https://linux-hardware.org/?probe=6dcb19e468) | Jul 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [647fe69592](https://linux-hardware.org/?probe=647fe69592) | Jul 22, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| MSI           | H61M-E33                    | Desktop     | [0d1a9284a9](https://linux-hardware.org/?probe=0d1a9284a9) | Jul 17, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [011a83c682](https://linux-hardware.org/?probe=011a83c682) | Jul 17, 2021 |
| Dell          | Studio 1558                 | Notebook    | [d1fad8f698](https://linux-hardware.org/?probe=d1fad8f698) | Jul 16, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | Notebook    | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [d49086311b](https://linux-hardware.org/?probe=d49086311b) | Jul 12, 2021 |
| Unknown       | TB-4000                     | Desktop     | [fb3e1984b0](https://linux-hardware.org/?probe=fb3e1984b0) | Jul 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [ae14beb6fd](https://linux-hardware.org/?probe=ae14beb6fd) | Jul 09, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [ebd157141b](https://linux-hardware.org/?probe=ebd157141b) | Jul 08, 2021 |
| Gigabyte      | H81M-S1                     | Desktop     | [4b2c3ea073](https://linux-hardware.org/?probe=4b2c3ea073) | Jul 07, 2021 |
| ASUSTek       | Z170-AR                     | Desktop     | [37343856a5](https://linux-hardware.org/?probe=37343856a5) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | Notebook    | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [9bb3c8dbe9](https://linux-hardware.org/?probe=9bb3c8dbe9) | Jul 02, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [90235ac63a](https://linux-hardware.org/?probe=90235ac63a) | Jun 30, 2021 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [55bdc0f976](https://linux-hardware.org/?probe=55bdc0f976) | Jun 28, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [212819389c](https://linux-hardware.org/?probe=212819389c) | Jun 25, 2021 |
| HP            | Pavilion dv7                | Notebook    | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [7fba4b1b78](https://linux-hardware.org/?probe=7fba4b1b78) | Jun 23, 2021 |
| Dell          | Latitude E6400              | Notebook    | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| HP            | 1495                        | Desktop     | [03ab704550](https://linux-hardware.org/?probe=03ab704550) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [c71b41c7a8](https://linux-hardware.org/?probe=c71b41c7a8) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [f39e5005bd](https://linux-hardware.org/?probe=f39e5005bd) | Jun 20, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d41809b4c9](https://linux-hardware.org/?probe=d41809b4c9) | Jun 19, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [b10313d89f](https://linux-hardware.org/?probe=b10313d89f) | Jun 17, 2021 |
| eMachines     | EL1352                      | Desktop     | [f175ae71f2](https://linux-hardware.org/?probe=f175ae71f2) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [0616fdb086](https://linux-hardware.org/?probe=0616fdb086) | Jun 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [3d47d96665](https://linux-hardware.org/?probe=3d47d96665) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c9bea47caa](https://linux-hardware.org/?probe=c9bea47caa) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c9c757474a](https://linux-hardware.org/?probe=c9c757474a) | Jun 12, 2021 |
| Dell          | Latitude E6510              | Notebook    | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [17af721bae](https://linux-hardware.org/?probe=17af721bae) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [23dc47130c](https://linux-hardware.org/?probe=23dc47130c) | Jun 10, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [1ab4ff25ab](https://linux-hardware.org/?probe=1ab4ff25ab) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b5aa561890](https://linux-hardware.org/?probe=b5aa561890) | Jun 05, 2021 |
| ASUSTek       | K73SJ                       | Notebook    | [cb0f042995](https://linux-hardware.org/?probe=cb0f042995) | Jun 04, 2021 |
| Dell          | Latitude 7420               | Notebook    | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [d732611ebb](https://linux-hardware.org/?probe=d732611ebb) | Jun 02, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [913ea68973](https://linux-hardware.org/?probe=913ea68973) | May 31, 2021 |
| Inventec      | Z CLASS A02                 | Desktop     | [7fc4815cbd](https://linux-hardware.org/?probe=7fc4815cbd) | May 29, 2021 |
| HP            | Pavilion                    | Notebook    | [1fa0cb66b1](https://linux-hardware.org/?probe=1fa0cb66b1) | May 26, 2021 |
| Dell          | Precision M4800             | Notebook    | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Dell          | Precision M4800             | Notebook    | [fd49c10a9f](https://linux-hardware.org/?probe=fd49c10a9f) | May 24, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | Notebook    | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [6b9dbebe2f](https://linux-hardware.org/?probe=6b9dbebe2f) | May 18, 2021 |
| Acer          | Board                       | Desktop     | [7f9d35f468](https://linux-hardware.org/?probe=7f9d35f468) | May 18, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [c56840df98](https://linux-hardware.org/?probe=c56840df98) | May 17, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f1592b156b](https://linux-hardware.org/?probe=f1592b156b) | May 16, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | Notebook    | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | Notebook    | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Dell          | G7 7588                     | Notebook    | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| HP            | Pavilion                    | Notebook    | [ade11f7a65](https://linux-hardware.org/?probe=ade11f7a65) | May 08, 2021 |
| Cube          | i18-L                       | Notebook    | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [7761ccf4be](https://linux-hardware.org/?probe=7761ccf4be) | May 07, 2021 |
| HP            | Pavilion                    | Notebook    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [9ff1a95290](https://linux-hardware.org/?probe=9ff1a95290) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| Dell          | G7 7588                     | Notebook    | [1393a855bb](https://linux-hardware.org/?probe=1393a855bb) | Apr 25, 2021 |
| Intel         | S5520HC E26045-407          | Server      | [61dfd26e01](https://linux-hardware.org/?probe=61dfd26e01) | Apr 24, 2021 |
| Intel         | S5520HC E26045-407          | Server      | [28bf977c65](https://linux-hardware.org/?probe=28bf977c65) | Apr 24, 2021 |
| ONE-NETBOO... | A1                          | Notebook    | [86c38b0aca](https://linux-hardware.org/?probe=86c38b0aca) | Apr 23, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3835eff7c6](https://linux-hardware.org/?probe=3835eff7c6) | Apr 21, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [289a9d70d9](https://linux-hardware.org/?probe=289a9d70d9) | Apr 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | Desktop     | [d5310b7f74](https://linux-hardware.org/?probe=d5310b7f74) | Apr 15, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [75f43079fb](https://linux-hardware.org/?probe=75f43079fb) | Apr 13, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [dce5f8220a](https://linux-hardware.org/?probe=dce5f8220a) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [fb0db0afbd](https://linux-hardware.org/?probe=fb0db0afbd) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [236be7c7e7](https://linux-hardware.org/?probe=236be7c7e7) | Apr 12, 2021 |
| HP            | Pavilion dv6                | Notebook    | [bf634bb665](https://linux-hardware.org/?probe=bf634bb665) | Apr 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c2aed97877](https://linux-hardware.org/?probe=c2aed97877) | Apr 08, 2021 |
| HP            | 15                          | Notebook    | [acc9ccddfa](https://linux-hardware.org/?probe=acc9ccddfa) | Apr 08, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [946c22503a](https://linux-hardware.org/?probe=946c22503a) | Apr 07, 2021 |
| HP            | ProBook 4530s               | Notebook    | [12a7784eb4](https://linux-hardware.org/?probe=12a7784eb4) | Apr 06, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1d9693a3dc](https://linux-hardware.org/?probe=1d9693a3dc) | Apr 05, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [16218d28da](https://linux-hardware.org/?probe=16218d28da) | Apr 04, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [fa8acecaa2](https://linux-hardware.org/?probe=fa8acecaa2) | Apr 01, 2021 |
| HP            | 3397                        | Desktop     | [e5812883ce](https://linux-hardware.org/?probe=e5812883ce) | Mar 31, 2021 |
| Dell          | Latitude E7250              | Notebook    | [d88e8eb416](https://linux-hardware.org/?probe=d88e8eb416) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| Dell          | Latitude 7310               | Notebook    | [9f4c2f64a5](https://linux-hardware.org/?probe=9f4c2f64a5) | Mar 30, 2021 |
| Dell          | Latitude E7250              | Notebook    | [d1716d96f2](https://linux-hardware.org/?probe=d1716d96f2) | Mar 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [dc5e67af5a](https://linux-hardware.org/?probe=dc5e67af5a) | Mar 27, 2021 |
| ASRock        | H310M-STX                   | Desktop     | [419277b830](https://linux-hardware.org/?probe=419277b830) | Mar 26, 2021 |
| Acer          | Aspire 4740                 | Notebook    | [3551944dd9](https://linux-hardware.org/?probe=3551944dd9) | Mar 25, 2021 |
| Supermicro    | X10SRM-TFA                  | Server      | [3fc4f3458f](https://linux-hardware.org/?probe=3fc4f3458f) | Mar 24, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [f3ac6366a6](https://linux-hardware.org/?probe=f3ac6366a6) | Mar 24, 2021 |
| Samsung       | 760XBE                      | Notebook    | [3cacabef7b](https://linux-hardware.org/?probe=3cacabef7b) | Mar 23, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4d7e0c9e41](https://linux-hardware.org/?probe=4d7e0c9e41) | Mar 23, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | Notebook    | [92bcacad15](https://linux-hardware.org/?probe=92bcacad15) | Mar 22, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e9b0291347](https://linux-hardware.org/?probe=e9b0291347) | Mar 21, 2021 |
| Samsung       | 760XBE                      | Notebook    | [26e28d0645](https://linux-hardware.org/?probe=26e28d0645) | Mar 21, 2021 |
| HP            | 1497                        | Desktop     | [d35a7eef80](https://linux-hardware.org/?probe=d35a7eef80) | Mar 19, 2021 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [e4faf817fd](https://linux-hardware.org/?probe=e4faf817fd) | Mar 19, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [cc01498ee9](https://linux-hardware.org/?probe=cc01498ee9) | Mar 18, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9210657e45](https://linux-hardware.org/?probe=9210657e45) | Mar 17, 2021 |
| ASRock        | 960GM-S3 FX                 | Desktop     | [5784a74c50](https://linux-hardware.org/?probe=5784a74c50) | Mar 17, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [f58ddcc3f4](https://linux-hardware.org/?probe=f58ddcc3f4) | Mar 17, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [1919b6a57f](https://linux-hardware.org/?probe=1919b6a57f) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [2b8f8e4cec](https://linux-hardware.org/?probe=2b8f8e4cec) | Mar 14, 2021 |
| MSI           | B85M-P33                    | Desktop     | [e7d2bb8e63](https://linux-hardware.org/?probe=e7d2bb8e63) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [957f68f2b7](https://linux-hardware.org/?probe=957f68f2b7) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [839bc4873c](https://linux-hardware.org/?probe=839bc4873c) | Mar 08, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [b5cf5849a1](https://linux-hardware.org/?probe=b5cf5849a1) | Mar 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cc361e0dbf](https://linux-hardware.org/?probe=cc361e0dbf) | Mar 04, 2021 |
| HP            | 2B2C                        | Desktop     | [20c11c9bbc](https://linux-hardware.org/?probe=20c11c9bbc) | Mar 04, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [e4437002b3](https://linux-hardware.org/?probe=e4437002b3) | Mar 04, 2021 |
| Medion        | B460H6-EM                   | Desktop     | [2ab61e6080](https://linux-hardware.org/?probe=2ab61e6080) | Mar 03, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [0286dc8c95](https://linux-hardware.org/?probe=0286dc8c95) | Mar 02, 2021 |
| HP            | Pavilion g7                 | Notebook    | [6d79297a65](https://linux-hardware.org/?probe=6d79297a65) | Feb 26, 2021 |
| HP            | Pavilion g7                 | Notebook    | [41d55a3dd7](https://linux-hardware.org/?probe=41d55a3dd7) | Feb 26, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [53ada57eb3](https://linux-hardware.org/?probe=53ada57eb3) | Feb 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [45c92f0ad1](https://linux-hardware.org/?probe=45c92f0ad1) | Feb 22, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [f1349be70a](https://linux-hardware.org/?probe=f1349be70a) | Feb 19, 2021 |
| Unknown       | XH61X000.100                | Desktop     | [029de8905d](https://linux-hardware.org/?probe=029de8905d) | Feb 17, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [5bd6c548d2](https://linux-hardware.org/?probe=5bd6c548d2) | Feb 15, 2021 |
| JINGSHA       | Board                       | Desktop     | [01ab676e78](https://linux-hardware.org/?probe=01ab676e78) | Feb 15, 2021 |
| Positivo      | N8X0EK1                     | Notebook    | [c6ac8d6eca](https://linux-hardware.org/?probe=c6ac8d6eca) | Feb 15, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [87f43dfecd](https://linux-hardware.org/?probe=87f43dfecd) | Feb 12, 2021 |
| Dell          | Latitude E6500              | Notebook    | [75d199bcfd](https://linux-hardware.org/?probe=75d199bcfd) | Feb 12, 2021 |
| Dell          | Studio 1747                 | Notebook    | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [bd107eb4ae](https://linux-hardware.org/?probe=bd107eb4ae) | Feb 10, 2021 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [fa48450d71](https://linux-hardware.org/?probe=fa48450d71) | Feb 09, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [952ca96633](https://linux-hardware.org/?probe=952ca96633) | Feb 09, 2021 |
| Notebook      | W310CZ/CZ-T                 | Notebook    | [2b60fc9e91](https://linux-hardware.org/?probe=2b60fc9e91) | Feb 09, 2021 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [bbff698cb8](https://linux-hardware.org/?probe=bbff698cb8) | Feb 09, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [394af8312b](https://linux-hardware.org/?probe=394af8312b) | Feb 07, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [0e61287ad7](https://linux-hardware.org/?probe=0e61287ad7) | Feb 07, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ad3df90a2e](https://linux-hardware.org/?probe=ad3df90a2e) | Feb 06, 2021 |
| Gateway       | DX4885                      | Desktop     | [48628b0b95](https://linux-hardware.org/?probe=48628b0b95) | Feb 03, 2021 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [e39393dcdb](https://linux-hardware.org/?probe=e39393dcdb) | Feb 02, 2021 |
| Intel         | H61M-S1                     | Desktop     | [38a03ee5be](https://linux-hardware.org/?probe=38a03ee5be) | Jan 31, 2021 |
| Acer          | Aspire ES1-521              | Notebook    | [73b3295031](https://linux-hardware.org/?probe=73b3295031) | Jan 29, 2021 |
| Dell          | G7 7588                     | Notebook    | [ae6d47978a](https://linux-hardware.org/?probe=ae6d47978a) | Jan 28, 2021 |
| Dell          | G7 7588                     | Notebook    | [1006977f89](https://linux-hardware.org/?probe=1006977f89) | Jan 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [20d082d72c](https://linux-hardware.org/?probe=20d082d72c) | Jan 26, 2021 |
| ASUSTek       | LITHIUM                     | Desktop     | [e2c8ad85fb](https://linux-hardware.org/?probe=e2c8ad85fb) | Jan 24, 2021 |
| ASUSTek       | LITHIUM                     | Desktop     | [3f3f25d596](https://linux-hardware.org/?probe=3f3f25d596) | Jan 24, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [4695d8c639](https://linux-hardware.org/?probe=4695d8c639) | Jan 24, 2021 |
| ASUSTek       | P5N-D                       | Desktop     | [cac7f8ae52](https://linux-hardware.org/?probe=cac7f8ae52) | Jan 23, 2021 |
| ASUSTek       | P5N-D                       | Desktop     | [b637c75d21](https://linux-hardware.org/?probe=b637c75d21) | Jan 23, 2021 |
| Acer          | Spin SP111-33               | Convertible | [0a09d00b74](https://linux-hardware.org/?probe=0a09d00b74) | Jan 23, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | Notebook    | [4cae7dc78d](https://linux-hardware.org/?probe=4cae7dc78d) | Jan 18, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [f2e3b573f5](https://linux-hardware.org/?probe=f2e3b573f5) | Jan 16, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | Notebook    | [e8b3cf2cbd](https://linux-hardware.org/?probe=e8b3cf2cbd) | Jan 14, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | Notebook    | [8117aff9b0](https://linux-hardware.org/?probe=8117aff9b0) | Jan 14, 2021 |
| Medion        | X682X                       | Notebook    | [bf7dbceaa3](https://linux-hardware.org/?probe=bf7dbceaa3) | Jan 13, 2021 |
| Dell          | 0200DY A03                  | Desktop     | [5e5ca98e54](https://linux-hardware.org/?probe=5e5ca98e54) | Jan 13, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [86c7eb6c5b](https://linux-hardware.org/?probe=86c7eb6c5b) | Jan 11, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [474542bd76](https://linux-hardware.org/?probe=474542bd76) | Jan 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7faa994c80](https://linux-hardware.org/?probe=7faa994c80) | Jan 10, 2021 |
| ASUSTek       | P7P55 LX                    | Desktop     | [d13d4667c3](https://linux-hardware.org/?probe=d13d4667c3) | Jan 09, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [7b2ec8b1a2](https://linux-hardware.org/?probe=7b2ec8b1a2) | Jan 08, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [1b3b03be98](https://linux-hardware.org/?probe=1b3b03be98) | Jan 07, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [fb8fa788e3](https://linux-hardware.org/?probe=fb8fa788e3) | Jan 07, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [4f385a65db](https://linux-hardware.org/?probe=4f385a65db) | Jan 03, 2021 |
| Samsung       | SR58P                       | Notebook    | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| MSI           | H87-G43                     | Desktop     | [8b1363882c](https://linux-hardware.org/?probe=8b1363882c) | Jan 03, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e253bc608d](https://linux-hardware.org/?probe=e253bc608d) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1483935c23](https://linux-hardware.org/?probe=1483935c23) | Jan 02, 2021 |
| Acer          | Aspire E1-532P              | Notebook    | [a1f1287741](https://linux-hardware.org/?probe=a1f1287741) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [30041ef295](https://linux-hardware.org/?probe=30041ef295) | Jan 01, 2021 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [708c6c3ab6](https://linux-hardware.org/?probe=708c6c3ab6) | Dec 28, 2020 |
| HP            | Notebook                    | Notebook    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA32VLM    | Notebook    | [cfa92bb7f3](https://linux-hardware.org/?probe=cfa92bb7f3) | Dec 28, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e50d894b93](https://linux-hardware.org/?probe=e50d894b93) | Dec 28, 2020 |
| ASUSTek       | X302LA                      | Notebook    | [f5dde37fb9](https://linux-hardware.org/?probe=f5dde37fb9) | Dec 26, 2020 |
| Gigabyte      | Z97-HD3                     | Desktop     | [417a2cbe50](https://linux-hardware.org/?probe=417a2cbe50) | Dec 26, 2020 |
| ASUSTek       | X302LA                      | Notebook    | [a35e9f4b28](https://linux-hardware.org/?probe=a35e9f4b28) | Dec 25, 2020 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [8d897ef7a8](https://linux-hardware.org/?probe=8d897ef7a8) | Dec 24, 2020 |
| Star Labs     | LabTop                      | Notebook    | [b8c8467e92](https://linux-hardware.org/?probe=b8c8467e92) | Dec 20, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [46e2c41ee6](https://linux-hardware.org/?probe=46e2c41ee6) | Dec 17, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9ad04d0568](https://linux-hardware.org/?probe=9ad04d0568) | Dec 16, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e9fb6116b3](https://linux-hardware.org/?probe=e9fb6116b3) | Dec 14, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| HP            | 82A2                        | Desktop     | [8b443d9da5](https://linux-hardware.org/?probe=8b443d9da5) | Dec 12, 2020 |
| HP            | 82A2                        | Desktop     | [58faddeba3](https://linux-hardware.org/?probe=58faddeba3) | Dec 12, 2020 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [e1d03e259e](https://linux-hardware.org/?probe=e1d03e259e) | Dec 09, 2020 |
| Toshiba       | Satellite Pro L500          | Notebook    | [d01d9e0d34](https://linux-hardware.org/?probe=d01d9e0d34) | Dec 08, 2020 |
| Dell          | Inspiron 3520               | Notebook    | [be6f5d9f85](https://linux-hardware.org/?probe=be6f5d9f85) | Dec 07, 2020 |
| Gigabyte      | EP45T-EXTREME               | Desktop     | [9320edd724](https://linux-hardware.org/?probe=9320edd724) | Dec 07, 2020 |
| Dell          | Latitude D630               | Notebook    | [475177f3da](https://linux-hardware.org/?probe=475177f3da) | Dec 07, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [5862508036](https://linux-hardware.org/?probe=5862508036) | Dec 06, 2020 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [eba95d11b5](https://linux-hardware.org/?probe=eba95d11b5) | Dec 04, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2f04deaf4e](https://linux-hardware.org/?probe=2f04deaf4e) | Dec 03, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [ee0aa7b52f](https://linux-hardware.org/?probe=ee0aa7b52f) | Dec 02, 2020 |
| Dell          | Precision 7710              | Notebook    | [f017e7a0d2](https://linux-hardware.org/?probe=f017e7a0d2) | Nov 30, 2020 |
| Acer          | Aspire E5-523               | Notebook    | [cfd9403111](https://linux-hardware.org/?probe=cfd9403111) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Dell          | Latitude E6400              | Notebook    | [a39e2e7fa3](https://linux-hardware.org/?probe=a39e2e7fa3) | Nov 27, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [94f75b4e92](https://linux-hardware.org/?probe=94f75b4e92) | Nov 22, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [49224bd7f8](https://linux-hardware.org/?probe=49224bd7f8) | Nov 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [833a22d4ee](https://linux-hardware.org/?probe=833a22d4ee) | Nov 20, 2020 |
| HP            | EliteBook 830 G6            | Notebook    | [c47a2f5f86](https://linux-hardware.org/?probe=c47a2f5f86) | Nov 18, 2020 |
| ASUSTek       | WS C246M PRO Series         | Desktop     | [502bd89093](https://linux-hardware.org/?probe=502bd89093) | Nov 18, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [08c8440950](https://linux-hardware.org/?probe=08c8440950) | Nov 17, 2020 |
| ASUSTek       | WS C246M PRO Series         | Desktop     | [dc20d9cf64](https://linux-hardware.org/?probe=dc20d9cf64) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | Notebook    | [968f302807](https://linux-hardware.org/?probe=968f302807) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | Notebook    | [2a9231cde8](https://linux-hardware.org/?probe=2a9231cde8) | Nov 17, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [b8e7eedfed](https://linux-hardware.org/?probe=b8e7eedfed) | Nov 17, 2020 |
| Dell          | Latitude E6420              | Notebook    | [3452613a4c](https://linux-hardware.org/?probe=3452613a4c) | Nov 16, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| Dell          | 0WG864                      | Desktop     | [1c2384097b](https://linux-hardware.org/?probe=1c2384097b) | Nov 15, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [153a36bfa0](https://linux-hardware.org/?probe=153a36bfa0) | Nov 14, 2020 |
| HP            | 1790                        | Desktop     | [02138cec8b](https://linux-hardware.org/?probe=02138cec8b) | Nov 08, 2020 |
| HP            | 1905                        | Desktop     | [6f20f6aa7d](https://linux-hardware.org/?probe=6f20f6aa7d) | Nov 08, 2020 |
| Intel         | SLIMBOOK                    | Desktop     | [2250e4a10f](https://linux-hardware.org/?probe=2250e4a10f) | Nov 07, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | 3397                        | Desktop     | [17188b10a3](https://linux-hardware.org/?probe=17188b10a3) | Nov 06, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [659c1c8745](https://linux-hardware.org/?probe=659c1c8745) | Nov 06, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [248ce84271](https://linux-hardware.org/?probe=248ce84271) | Nov 05, 2020 |
| Unknown       | Unknown                     | Soc         | [c30e84eeae](https://linux-hardware.org/?probe=c30e84eeae) | Nov 04, 2020 |
| Dell          | Latitude E6420              | Notebook    | [6cdd815251](https://linux-hardware.org/?probe=6cdd815251) | Nov 04, 2020 |
| Dell          | Latitude E6420              | Notebook    | [10d44f2853](https://linux-hardware.org/?probe=10d44f2853) | Nov 04, 2020 |
| Acer          | Aspire A314-32              | Notebook    | [686d0b8c4f](https://linux-hardware.org/?probe=686d0b8c4f) | Nov 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [39ba29b6a3](https://linux-hardware.org/?probe=39ba29b6a3) | Nov 02, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4f36ffb293](https://linux-hardware.org/?probe=4f36ffb293) | Nov 01, 2020 |
| Supermicro    | X10SAE                      | Server      | [ef95821afc](https://linux-hardware.org/?probe=ef95821afc) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [0ed9f03fcd](https://linux-hardware.org/?probe=0ed9f03fcd) | Nov 01, 2020 |
| Pegatron      | NARRA3                      | Desktop     | [2fbfcbd44d](https://linux-hardware.org/?probe=2fbfcbd44d) | Oct 31, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [d9a9dae79a](https://linux-hardware.org/?probe=d9a9dae79a) | Oct 31, 2020 |
| Unknown       | Unknown                     | Soc         | [1194b41aeb](https://linux-hardware.org/?probe=1194b41aeb) | Oct 31, 2020 |
| Unknown       | Unknown                     | Soc         | [d48278c2fc](https://linux-hardware.org/?probe=d48278c2fc) | Oct 31, 2020 |
| Lenovo        | Board                       | Desktop     | [69bc4fbb1b](https://linux-hardware.org/?probe=69bc4fbb1b) | Oct 30, 2020 |
| HP            | 1493                        | Desktop     | [34134cab7f](https://linux-hardware.org/?probe=34134cab7f) | Oct 30, 2020 |
| HP            | 1493                        | Desktop     | [dd1964d532](https://linux-hardware.org/?probe=dd1964d532) | Oct 30, 2020 |
| Lenovo        | ThinkPad E520 1143B5G       | Notebook    | [146fc730d7](https://linux-hardware.org/?probe=146fc730d7) | Oct 29, 2020 |
| MSI           | GE72 7RE                    | Notebook    | [f75b251f96](https://linux-hardware.org/?probe=f75b251f96) | Oct 29, 2020 |
| HP            | 1497                        | Desktop     | [1d068e5c77](https://linux-hardware.org/?probe=1d068e5c77) | Oct 28, 2020 |
| HP            | 3047h                       | Desktop     | [4f58775069](https://linux-hardware.org/?probe=4f58775069) | Oct 28, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [a13afb5c54](https://linux-hardware.org/?probe=a13afb5c54) | Oct 27, 2020 |
| Acer          | Aspire 5715Z                | Notebook    | [a2fca6b9da](https://linux-hardware.org/?probe=a2fca6b9da) | Oct 26, 2020 |
| Lenovo        | V570 HuronRiver Platform    | Notebook    | [62082c183e](https://linux-hardware.org/?probe=62082c183e) | Oct 26, 2020 |
| ASUSTek       | X751LK                      | Notebook    | [0dad6a22c5](https://linux-hardware.org/?probe=0dad6a22c5) | Oct 26, 2020 |
| HP            | Pavilion dv7                | Notebook    | [59e2fce913](https://linux-hardware.org/?probe=59e2fce913) | Oct 26, 2020 |
| Dell          | Precision M4800             | Notebook    | [2f91204b5e](https://linux-hardware.org/?probe=2f91204b5e) | Oct 26, 2020 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [dd929b231e](https://linux-hardware.org/?probe=dd929b231e) | Oct 26, 2020 |
| ASRock        | G31M-GS                     | Desktop     | [0a9aa8dcd2](https://linux-hardware.org/?probe=0a9aa8dcd2) | Oct 26, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [fd598f0888](https://linux-hardware.org/?probe=fd598f0888) | Oct 25, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [07f3bdda40](https://linux-hardware.org/?probe=07f3bdda40) | Oct 25, 2020 |
| Biostar       | A320MH                      | Desktop     | [8c1edce824](https://linux-hardware.org/?probe=8c1edce824) | Oct 24, 2020 |
| Dell          | 0V6XGW A00                  | Desktop     | [1518ff90f9](https://linux-hardware.org/?probe=1518ff90f9) | Oct 24, 2020 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [ab60c752a9](https://linux-hardware.org/?probe=ab60c752a9) | Oct 23, 2020 |
| HP            | 3047h                       | Desktop     | [ecba048272](https://linux-hardware.org/?probe=ecba048272) | Oct 21, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [658b7105e1](https://linux-hardware.org/?probe=658b7105e1) | Oct 21, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c720d8a96a](https://linux-hardware.org/?probe=c720d8a96a) | Oct 21, 2020 |
| Dell          | G3 3590                     | Notebook    | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| HP            | 3047h                       | Desktop     | [4c9083177a](https://linux-hardware.org/?probe=4c9083177a) | Oct 21, 2020 |
| HP            | 3047h                       | Desktop     | [67e7807767](https://linux-hardware.org/?probe=67e7807767) | Oct 21, 2020 |
| Lenovo        | ThinkPad E560 20EV0013MS    | Notebook    | [6a0824824b](https://linux-hardware.org/?probe=6a0824824b) | Oct 20, 2020 |
| HP            | 3047h                       | Desktop     | [4dd1cde645](https://linux-hardware.org/?probe=4dd1cde645) | Oct 20, 2020 |
| Dell          | Latitude E6430              | Notebook    | [67b44ea2b4](https://linux-hardware.org/?probe=67b44ea2b4) | Oct 20, 2020 |
| HP            | 3047h                       | Desktop     | [d84da1ea3e](https://linux-hardware.org/?probe=d84da1ea3e) | Oct 20, 2020 |
| HP            | 3047h                       | Desktop     | [134da552c2](https://linux-hardware.org/?probe=134da552c2) | Oct 20, 2020 |
| HP            | 304Ah                       | Desktop     | [3163a2892d](https://linux-hardware.org/?probe=3163a2892d) | Oct 19, 2020 |
| HP            | 3397                        | Desktop     | [8bdef2c49c](https://linux-hardware.org/?probe=8bdef2c49c) | Oct 19, 2020 |
| HP            | Compaq 6730s                | Notebook    | [b8d5fd5eea](https://linux-hardware.org/?probe=b8d5fd5eea) | Oct 19, 2020 |
| HP            | Notebook                    | Notebook    | [669e2e8ce6](https://linux-hardware.org/?probe=669e2e8ce6) | Oct 19, 2020 |
| Lenovo        | G50-80 80R0                 | Notebook    | [51ec4152a2](https://linux-hardware.org/?probe=51ec4152a2) | Oct 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e5aa6a33a6](https://linux-hardware.org/?probe=e5aa6a33a6) | Oct 18, 2020 |
| HP            | 3397                        | Desktop     | [5a6fac5a0f](https://linux-hardware.org/?probe=5a6fac5a0f) | Oct 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c45c0eb7e4](https://linux-hardware.org/?probe=c45c0eb7e4) | Oct 16, 2020 |
| HP            | ProBook 4430s               | Notebook    | [c816b204bf](https://linux-hardware.org/?probe=c816b204bf) | Oct 15, 2020 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2c4fc7773a](https://linux-hardware.org/?probe=2c4fc7773a) | Oct 14, 2020 |
| Lenovo        | ThinkPad X270 20HN0013MX    | Notebook    | [3dbb81e06d](https://linux-hardware.org/?probe=3dbb81e06d) | Oct 14, 2020 |
| Dell          | 042P49 A01                  | Desktop     | [44c14427a0](https://linux-hardware.org/?probe=44c14427a0) | Oct 13, 2020 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [d386e709dc](https://linux-hardware.org/?probe=d386e709dc) | Oct 12, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a489f1cb59](https://linux-hardware.org/?probe=a489f1cb59) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [097db248db](https://linux-hardware.org/?probe=097db248db) | Oct 12, 2020 |
| Unknown       | Unknown                     | Soc         | [72e115769d](https://linux-hardware.org/?probe=72e115769d) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [41141f049e](https://linux-hardware.org/?probe=41141f049e) | Oct 11, 2020 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2c0322f113](https://linux-hardware.org/?probe=2c0322f113) | Oct 10, 2020 |
| Dell          | 0FR6WH A01                  | Desktop     | [2776ae6a1a](https://linux-hardware.org/?probe=2776ae6a1a) | Oct 09, 2020 |
| Dell          | 0T656F A01                  | Desktop     | [f44db9c73a](https://linux-hardware.org/?probe=f44db9c73a) | Oct 09, 2020 |
| Pegatron      | 2A84h                       | Desktop     | [a8d97c37b7](https://linux-hardware.org/?probe=a8d97c37b7) | Oct 08, 2020 |
| Dell          | 0HN7XN A00                  | Desktop     | [885b19f22a](https://linux-hardware.org/?probe=885b19f22a) | Oct 08, 2020 |
| Dell          | Latitude E6420              | Notebook    | [1e2a1974f2](https://linux-hardware.org/?probe=1e2a1974f2) | Oct 08, 2020 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [01948526e2](https://linux-hardware.org/?probe=01948526e2) | Oct 08, 2020 |
| Acer          | Aspire 5715Z                | Notebook    | [e112fe04f3](https://linux-hardware.org/?probe=e112fe04f3) | Oct 08, 2020 |
| HP            | 3646h                       | Desktop     | [d5dd5824e3](https://linux-hardware.org/?probe=d5dd5824e3) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [1f6fe3684d](https://linux-hardware.org/?probe=1f6fe3684d) | Oct 07, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [8872b79e71](https://linux-hardware.org/?probe=8872b79e71) | Oct 07, 2020 |
| Medion        | E15302                      | Notebook    | [957a41b1b5](https://linux-hardware.org/?probe=957a41b1b5) | Oct 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2866055b35](https://linux-hardware.org/?probe=2866055b35) | Oct 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e91b4e0378](https://linux-hardware.org/?probe=e91b4e0378) | Oct 07, 2020 |
| Dell          | 0TVR1F A01                  | Desktop     | [3de8c4e65d](https://linux-hardware.org/?probe=3de8c4e65d) | Oct 06, 2020 |
| Dell          | 0TVR1F A01                  | Desktop     | [ae1a5155a6](https://linux-hardware.org/?probe=ae1a5155a6) | Oct 05, 2020 |
| Gigabyte      | B460M DS3H                  | Desktop     | [c607051cd6](https://linux-hardware.org/?probe=c607051cd6) | Oct 04, 2020 |
| Gigabyte      | B460M DS3H                  | Desktop     | [a96b9c0e32](https://linux-hardware.org/?probe=a96b9c0e32) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [28bab55cdf](https://linux-hardware.org/?probe=28bab55cdf) | Oct 02, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | Notebook    | [e2a36190d7](https://linux-hardware.org/?probe=e2a36190d7) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | Notebook    | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e8349f9863](https://linux-hardware.org/?probe=e8349f9863) | Sep 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [65476de549](https://linux-hardware.org/?probe=65476de549) | Sep 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f3137e99a6](https://linux-hardware.org/?probe=f3137e99a6) | Sep 29, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [16d07f52d6](https://linux-hardware.org/?probe=16d07f52d6) | Sep 29, 2020 |
| HP            | 3047h                       | Desktop     | [8276b976a7](https://linux-hardware.org/?probe=8276b976a7) | Sep 28, 2020 |
| Medion        | E2228T MD61250              | Convertible | [bcd49135b7](https://linux-hardware.org/?probe=bcd49135b7) | Sep 26, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7bab2d2c6c](https://linux-hardware.org/?probe=7bab2d2c6c) | Sep 26, 2020 |
| HP            | 1497                        | Desktop     | [3c6ed08ddd](https://linux-hardware.org/?probe=3c6ed08ddd) | Sep 25, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [21991336a9](https://linux-hardware.org/?probe=21991336a9) | Sep 25, 2020 |
| Dell          | 09M8Y8 A01                  | Desktop     | [7086c0ba36](https://linux-hardware.org/?probe=7086c0ba36) | Sep 25, 2020 |
| System76      | Serval WS                   | Notebook    | [7add8e6511](https://linux-hardware.org/?probe=7add8e6511) | Sep 25, 2020 |
| Dell          | Precision M6700             | Notebook    | [1b20609aaa](https://linux-hardware.org/?probe=1b20609aaa) | Sep 25, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [3140b90a75](https://linux-hardware.org/?probe=3140b90a75) | Sep 24, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4150c870a5](https://linux-hardware.org/?probe=4150c870a5) | Sep 24, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7b9403ff54](https://linux-hardware.org/?probe=7b9403ff54) | Sep 24, 2020 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [ac61b9b105](https://linux-hardware.org/?probe=ac61b9b105) | Sep 23, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6ff89bce9c](https://linux-hardware.org/?probe=6ff89bce9c) | Sep 21, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a53b5a24b](https://linux-hardware.org/?probe=1a53b5a24b) | Sep 21, 2020 |
| Intel         | DG43GT AAE62768-301         | Desktop     | [028847b86e](https://linux-hardware.org/?probe=028847b86e) | Sep 21, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [91c2f7bfb9](https://linux-hardware.org/?probe=91c2f7bfb9) | Sep 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [6fa6138bb4](https://linux-hardware.org/?probe=6fa6138bb4) | Sep 18, 2020 |
| Dell          | 0WX729                      | Desktop     | [f2cc61a6f1](https://linux-hardware.org/?probe=f2cc61a6f1) | Sep 17, 2020 |
| Dell          | Latitude E6410              | Notebook    | [8a3b88673f](https://linux-hardware.org/?probe=8a3b88673f) | Sep 17, 2020 |
| Dell          | 0WX729                      | Desktop     | [4fdbabe245](https://linux-hardware.org/?probe=4fdbabe245) | Sep 17, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [d026d40366](https://linux-hardware.org/?probe=d026d40366) | Sep 17, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | Notebook    | [a96ad52bc9](https://linux-hardware.org/?probe=a96ad52bc9) | Sep 16, 2020 |
| Dell          | Latitude E6410              | Notebook    | [8930b7e16f](https://linux-hardware.org/?probe=8930b7e16f) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [299b899172](https://linux-hardware.org/?probe=299b899172) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [b45cb0028d](https://linux-hardware.org/?probe=b45cb0028d) | Sep 16, 2020 |
| Dell          | 0D441T A01                  | Desktop     | [a5c5a78a7c](https://linux-hardware.org/?probe=a5c5a78a7c) | Sep 16, 2020 |
| HP            | Compaq 8710w (GC124EA#AK... | Notebook    | [dc5006e254](https://linux-hardware.org/?probe=dc5006e254) | Sep 15, 2020 |
| Dell          | 0TW904                      | Desktop     | [20994a3808](https://linux-hardware.org/?probe=20994a3808) | Sep 15, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [092f9a6491](https://linux-hardware.org/?probe=092f9a6491) | Sep 15, 2020 |
| HP            | G42                         | Notebook    | [9cb42d6f5f](https://linux-hardware.org/?probe=9cb42d6f5f) | Sep 15, 2020 |
| HP            | G42                         | Notebook    | [72d647e1b9](https://linux-hardware.org/?probe=72d647e1b9) | Sep 15, 2020 |
| Dell          | 0T656F A01                  | Desktop     | [a004d9a942](https://linux-hardware.org/?probe=a004d9a942) | Sep 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [740ac03586](https://linux-hardware.org/?probe=740ac03586) | Sep 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f64d2d6e24](https://linux-hardware.org/?probe=f64d2d6e24) | Sep 13, 2020 |
| HP            | 18E7                        | Desktop     | [18852c6be3](https://linux-hardware.org/?probe=18852c6be3) | Sep 11, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [0bba6eaf71](https://linux-hardware.org/?probe=0bba6eaf71) | Sep 11, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| Dell          | 0T656F A01                  | Desktop     | [6b43e65d15](https://linux-hardware.org/?probe=6b43e65d15) | Sep 10, 2020 |
| Dell          | 0TVR1F A01                  | Desktop     | [22aaefa03b](https://linux-hardware.org/?probe=22aaefa03b) | Sep 10, 2020 |
| Dell          | 042P49 A01                  | Desktop     | [282331caa5](https://linux-hardware.org/?probe=282331caa5) | Sep 10, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [bfc77d64c6](https://linux-hardware.org/?probe=bfc77d64c6) | Sep 09, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [d269751a9e](https://linux-hardware.org/?probe=d269751a9e) | Sep 09, 2020 |
| Acer          | Aspire A315-42G             | Notebook    | [ab24b14a42](https://linux-hardware.org/?probe=ab24b14a42) | Sep 09, 2020 |
| Dell          | 0PV3YR A05                  | Server      | [0e92eb8c77](https://linux-hardware.org/?probe=0e92eb8c77) | Sep 09, 2020 |
| Dell          | 0N820C A02                  | Desktop     | [a43f37d51e](https://linux-hardware.org/?probe=a43f37d51e) | Sep 08, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [3ae339618d](https://linux-hardware.org/?probe=3ae339618d) | Sep 08, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [d2f477c7f5](https://linux-hardware.org/?probe=d2f477c7f5) | Sep 08, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [c39d1b0af6](https://linux-hardware.org/?probe=c39d1b0af6) | Sep 05, 2020 |
| MSI           | Creator TRX40               | Desktop     | [48149893d7](https://linux-hardware.org/?probe=48149893d7) | Sep 04, 2020 |
| HP            | 3397                        | Desktop     | [e9da9cd17f](https://linux-hardware.org/?probe=e9da9cd17f) | Sep 03, 2020 |
| HP            | 339A                        | Desktop     | [5f29fd9231](https://linux-hardware.org/?probe=5f29fd9231) | Sep 03, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e3bc793dc3](https://linux-hardware.org/?probe=e3bc793dc3) | Sep 03, 2020 |
| HP            | 3397                        | Desktop     | [a8ea68de6d](https://linux-hardware.org/?probe=a8ea68de6d) | Sep 03, 2020 |
| Dell          | Latitude E6420              | Notebook    | [676828b4d4](https://linux-hardware.org/?probe=676828b4d4) | Sep 03, 2020 |
| MSI           | MEG X570 UNIFY              | Desktop     | [7e2dae216d](https://linux-hardware.org/?probe=7e2dae216d) | Sep 03, 2020 |
| Dell          | 03K80F A00                  | Desktop     | [a3452cb614](https://linux-hardware.org/?probe=a3452cb614) | Sep 02, 2020 |
| Dell          | 0HY9JP A00                  | Desktop     | [e797b1bf14](https://linux-hardware.org/?probe=e797b1bf14) | Sep 02, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2b44d73e4b](https://linux-hardware.org/?probe=2b44d73e4b) | Sep 02, 2020 |
| HP            | 1497                        | Desktop     | [edf6c3ecfa](https://linux-hardware.org/?probe=edf6c3ecfa) | Sep 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [6057658605](https://linux-hardware.org/?probe=6057658605) | Sep 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [9b1f1928c7](https://linux-hardware.org/?probe=9b1f1928c7) | Sep 01, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [b5600f5c06](https://linux-hardware.org/?probe=b5600f5c06) | Aug 31, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [461e0244f4](https://linux-hardware.org/?probe=461e0244f4) | Aug 31, 2020 |
| Positivo      | Mobile                      | Notebook    | [2249764f28](https://linux-hardware.org/?probe=2249764f28) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [cae373d70b](https://linux-hardware.org/?probe=cae373d70b) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c77cf6f3fa](https://linux-hardware.org/?probe=c77cf6f3fa) | Aug 30, 2020 |
| Toshiba       | Satellite M500              | Notebook    | [42449081bb](https://linux-hardware.org/?probe=42449081bb) | Aug 29, 2020 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [b26cdf0225](https://linux-hardware.org/?probe=b26cdf0225) | Aug 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dbb2bb4c60](https://linux-hardware.org/?probe=dbb2bb4c60) | Aug 28, 2020 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b39122c844](https://linux-hardware.org/?probe=b39122c844) | Aug 25, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [8d0d4f27be](https://linux-hardware.org/?probe=8d0d4f27be) | Aug 22, 2020 |
| HP            | 250 G4 Notebook PC          | Notebook    | [97eeff2c12](https://linux-hardware.org/?probe=97eeff2c12) | Aug 22, 2020 |
| Toshiba       | STI 010432                  | Desktop     | [7d6c45eed4](https://linux-hardware.org/?probe=7d6c45eed4) | Aug 20, 2020 |
| Toshiba       | STI 010432                  | Desktop     | [da8ae751c9](https://linux-hardware.org/?probe=da8ae751c9) | Aug 20, 2020 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b5c4317a43](https://linux-hardware.org/?probe=b5c4317a43) | Aug 20, 2020 |
| Intel         | Board                       | Desktop     | [0792f8e763](https://linux-hardware.org/?probe=0792f8e763) | Aug 20, 2020 |
| ASRock        | 990FX Extreme4              | Desktop     | [9d89158c0c](https://linux-hardware.org/?probe=9d89158c0c) | Aug 19, 2020 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [f3ea863c21](https://linux-hardware.org/?probe=f3ea863c21) | Aug 19, 2020 |
| Lenovo        | ThinkPad W530 24478K0       | Notebook    | [74fda860f1](https://linux-hardware.org/?probe=74fda860f1) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [5ffb6aaedb](https://linux-hardware.org/?probe=5ffb6aaedb) | Aug 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [83214468ce](https://linux-hardware.org/?probe=83214468ce) | Aug 17, 2020 |
| MSI           | GP72MVR 7RFX                | Notebook    | [39da2f58b5](https://linux-hardware.org/?probe=39da2f58b5) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | Desktop     | [844d21cfba](https://linux-hardware.org/?probe=844d21cfba) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | Desktop     | [d568758fb5](https://linux-hardware.org/?probe=d568758fb5) | Aug 16, 2020 |
| Toshiba       | STI 010432                  | Desktop     | [93e07b3103](https://linux-hardware.org/?probe=93e07b3103) | Aug 16, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [021ed0aac6](https://linux-hardware.org/?probe=021ed0aac6) | Aug 16, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0e5e076914](https://linux-hardware.org/?probe=0e5e076914) | Aug 15, 2020 |
| GPD           | MicroPC                     | Notebook    | [bb39ae1b31](https://linux-hardware.org/?probe=bb39ae1b31) | Aug 15, 2020 |
| Sony          | VPCEH1S1E                   | Notebook    | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3e086d75b0](https://linux-hardware.org/?probe=3e086d75b0) | Aug 12, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ab576b0cd8](https://linux-hardware.org/?probe=ab576b0cd8) | Aug 12, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [f2da7fe3f0](https://linux-hardware.org/?probe=f2da7fe3f0) | Aug 12, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [27573f027c](https://linux-hardware.org/?probe=27573f027c) | Aug 12, 2020 |
| Intel         | Board                       | Desktop     | [501444c3d4](https://linux-hardware.org/?probe=501444c3d4) | Aug 12, 2020 |
| Intel         | Board                       | Desktop     | [aca06096b6](https://linux-hardware.org/?probe=aca06096b6) | Aug 12, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1c6f36de59](https://linux-hardware.org/?probe=1c6f36de59) | Aug 10, 2020 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [608ff52425](https://linux-hardware.org/?probe=608ff52425) | Aug 06, 2020 |
| HP            | Pavilion x2 Detachable      | Tablet      | [93bb4b7ef5](https://linux-hardware.org/?probe=93bb4b7ef5) | Aug 06, 2020 |
| HP            | Pavilion dm1                | Notebook    | [ccb974921b](https://linux-hardware.org/?probe=ccb974921b) | Aug 05, 2020 |
| Gigabyte      | Z77P-D3                     | Desktop     | [ce15c17648](https://linux-hardware.org/?probe=ce15c17648) | Aug 05, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [7bfd99a9bd](https://linux-hardware.org/?probe=7bfd99a9bd) | Aug 05, 2020 |
| Dell          | XPS L702X                   | Notebook    | [86885b0835](https://linux-hardware.org/?probe=86885b0835) | Aug 04, 2020 |
| MSI           | GV62 8RD                    | Notebook    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [bd1790913e](https://linux-hardware.org/?probe=bd1790913e) | Aug 03, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [09aac7d871](https://linux-hardware.org/?probe=09aac7d871) | Aug 01, 2020 |
| Dell          | Precision M4800             | Notebook    | [defc3ac914](https://linux-hardware.org/?probe=defc3ac914) | Aug 01, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8936a7017a](https://linux-hardware.org/?probe=8936a7017a) | Jul 28, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [3ee7d0dc49](https://linux-hardware.org/?probe=3ee7d0dc49) | Jul 28, 2020 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [efd445830e](https://linux-hardware.org/?probe=efd445830e) | Jul 27, 2020 |
| Dell          | Inspiron 7520               | Notebook    | [a1ea369f96](https://linux-hardware.org/?probe=a1ea369f96) | Jul 27, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [e9661e7816](https://linux-hardware.org/?probe=e9661e7816) | Jul 27, 2020 |
| Intel         | DH87RL AAG74240-402         | Desktop     | [dfb8a55f7f](https://linux-hardware.org/?probe=dfb8a55f7f) | Jul 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [3ff385285a](https://linux-hardware.org/?probe=3ff385285a) | Jul 26, 2020 |
| Dell          | Inspiron 3421               | Notebook    | [12424c5a76](https://linux-hardware.org/?probe=12424c5a76) | Jul 25, 2020 |
| HP            | Pavilion g4                 | Notebook    | [a10cfaa6e2](https://linux-hardware.org/?probe=a10cfaa6e2) | Jul 24, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [6affb516f1](https://linux-hardware.org/?probe=6affb516f1) | Jul 24, 2020 |
| ASUSTek       | AM1M-A                      | Desktop     | [8a3873a0c3](https://linux-hardware.org/?probe=8a3873a0c3) | Jul 24, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [3e594f7ff4](https://linux-hardware.org/?probe=3e594f7ff4) | Jul 24, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [baa26535f9](https://linux-hardware.org/?probe=baa26535f9) | Jul 23, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [9dbcace7db](https://linux-hardware.org/?probe=9dbcace7db) | Jul 21, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [292d396a46](https://linux-hardware.org/?probe=292d396a46) | Jul 21, 2020 |
| Dell          | Vostro 3560                 | Notebook    | [c83b65951c](https://linux-hardware.org/?probe=c83b65951c) | Jul 20, 2020 |
| HP            | ZBook 17 G2                 | Notebook    | [61d82db95d](https://linux-hardware.org/?probe=61d82db95d) | Jul 20, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [8e5e5de5c3](https://linux-hardware.org/?probe=8e5e5de5c3) | Jul 20, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [9577cafcf7](https://linux-hardware.org/?probe=9577cafcf7) | Jul 19, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [c3a79140eb](https://linux-hardware.org/?probe=c3a79140eb) | Jul 18, 2020 |
| Lenovo        | ThinkPad T490 20N3CTO1WW    | Notebook    | [b6f9682f0b](https://linux-hardware.org/?probe=b6f9682f0b) | Jul 15, 2020 |
| ASUSTek       | X555LJ                      | Notebook    | [5657a6a512](https://linux-hardware.org/?probe=5657a6a512) | Jul 14, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [68e6b713ca](https://linux-hardware.org/?probe=68e6b713ca) | Jul 14, 2020 |
| Dell          | G7 7588                     | Notebook    | [8c4a8875bd](https://linux-hardware.org/?probe=8c4a8875bd) | Jul 14, 2020 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [bd28d2c132](https://linux-hardware.org/?probe=bd28d2c132) | Jul 13, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [eba8df9bea](https://linux-hardware.org/?probe=eba8df9bea) | Jul 12, 2020 |
| Dell          | G7 7588                     | Notebook    | [aee8398552](https://linux-hardware.org/?probe=aee8398552) | Jul 12, 2020 |
| HP            | 8434 11                     | Desktop     | [377d6d5aa4](https://linux-hardware.org/?probe=377d6d5aa4) | Jul 10, 2020 |
| Lenovo        | Board                       | Desktop     | [30edd53934](https://linux-hardware.org/?probe=30edd53934) | Jul 09, 2020 |
| Sony          | VPCF1290X                   | Notebook    | [f7c7a3ca92](https://linux-hardware.org/?probe=f7c7a3ca92) | Jul 08, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [096c493c42](https://linux-hardware.org/?probe=096c493c42) | Jul 06, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [f4dd6bbdec](https://linux-hardware.org/?probe=f4dd6bbdec) | Jul 06, 2020 |
| Lenovo        | ThinkPad 11e 20D9CTO1WW     | Notebook    | [11c17aa062](https://linux-hardware.org/?probe=11c17aa062) | Jul 05, 2020 |
| Acer          | Aspire 7750G                | Notebook    | [f6a31e475d](https://linux-hardware.org/?probe=f6a31e475d) | Jul 05, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [7e6be23ee7](https://linux-hardware.org/?probe=7e6be23ee7) | Jul 04, 2020 |
| Unknown       | Raspberry Pi                | Soc         | [8bcdced5b3](https://linux-hardware.org/?probe=8bcdced5b3) | Jul 04, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [994e71e658](https://linux-hardware.org/?probe=994e71e658) | Jul 03, 2020 |
| HP            | 250 G4                      | Notebook    | [ca40ef5473](https://linux-hardware.org/?probe=ca40ef5473) | Jul 02, 2020 |
| MSI           | A78M-E35                    | Desktop     | [baf6228acf](https://linux-hardware.org/?probe=baf6228acf) | Jul 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f7afeb0f26](https://linux-hardware.org/?probe=f7afeb0f26) | Jul 01, 2020 |
| HP            | Pavilion g6                 | Notebook    | [0175164903](https://linux-hardware.org/?probe=0175164903) | Jul 01, 2020 |
| Hardkernel    | ODROID-C2                   | Soc         | [537289447f](https://linux-hardware.org/?probe=537289447f) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c1d0ef500e](https://linux-hardware.org/?probe=c1d0ef500e) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6a9b477b88](https://linux-hardware.org/?probe=6a9b477b88) | Jun 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [cd4ada5990](https://linux-hardware.org/?probe=cd4ada5990) | Jun 28, 2020 |
| HP            | Pavilion g6                 | Notebook    | [efc97f097b](https://linux-hardware.org/?probe=efc97f097b) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [944b66e3ba](https://linux-hardware.org/?probe=944b66e3ba) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [3f58959650](https://linux-hardware.org/?probe=3f58959650) | Jun 24, 2020 |
| Lenovo        | ThinkPad T520 4243RS6       | Notebook    | [881175c7ec](https://linux-hardware.org/?probe=881175c7ec) | Jun 23, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [143bbac73c](https://linux-hardware.org/?probe=143bbac73c) | Jun 23, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | Notebook    | [c5a7e2708f](https://linux-hardware.org/?probe=c5a7e2708f) | Jun 22, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [1f2d306b05](https://linux-hardware.org/?probe=1f2d306b05) | Jun 20, 2020 |
| IBM           | Board                       | Desktop     | [28e9762210](https://linux-hardware.org/?probe=28e9762210) | Jun 16, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2290a03a3](https://linux-hardware.org/?probe=e2290a03a3) | Jun 16, 2020 |
| Lenovo        | ThinkPad X240 qqqq          | Notebook    | [04328e30ac](https://linux-hardware.org/?probe=04328e30ac) | Jun 15, 2020 |
| Sony          | VPCF1290X                   | Notebook    | [55652dadf6](https://linux-hardware.org/?probe=55652dadf6) | Jun 15, 2020 |
| Dell          | 0JTHY5 A00                  | All in one  | [5da41dbee9](https://linux-hardware.org/?probe=5da41dbee9) | Jun 15, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8fce25fa5d](https://linux-hardware.org/?probe=8fce25fa5d) | Jun 13, 2020 |
| Lenovo        | ThinkPad T430 2349H86       | Notebook    | [5ef2ab445e](https://linux-hardware.org/?probe=5ef2ab445e) | Jun 13, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | Notebook    | [5467542c77](https://linux-hardware.org/?probe=5467542c77) | Jun 12, 2020 |
| HP            | Pavilion g6                 | Notebook    | [78f5ccb141](https://linux-hardware.org/?probe=78f5ccb141) | Jun 11, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [02f2a001e1](https://linux-hardware.org/?probe=02f2a001e1) | Jun 11, 2020 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [994e3df746](https://linux-hardware.org/?probe=994e3df746) | Jun 11, 2020 |
| ASRock        | H110M-STX                   | Desktop     | [3c35aef096](https://linux-hardware.org/?probe=3c35aef096) | Jun 10, 2020 |
| Dell          | 0478VN A00                  | Desktop     | [f02bda5144](https://linux-hardware.org/?probe=f02bda5144) | Jun 09, 2020 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [61fe34704e](https://linux-hardware.org/?probe=61fe34704e) | Jun 08, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [4c810c7859](https://linux-hardware.org/?probe=4c810c7859) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [35995e9a53](https://linux-hardware.org/?probe=35995e9a53) | Jun 06, 2020 |
| ASUSTek       | X541SA                      | Notebook    | [508fc56922](https://linux-hardware.org/?probe=508fc56922) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [d6bcbe862e](https://linux-hardware.org/?probe=d6bcbe862e) | Jun 05, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8dbad33afb](https://linux-hardware.org/?probe=8dbad33afb) | Jun 05, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8177bd99b7](https://linux-hardware.org/?probe=8177bd99b7) | Jun 05, 2020 |
| Toshiba       | Satellite M500              | Notebook    | [96d989965c](https://linux-hardware.org/?probe=96d989965c) | Jun 04, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3da3ba498c](https://linux-hardware.org/?probe=3da3ba498c) | Jun 03, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [56c24dddd4](https://linux-hardware.org/?probe=56c24dddd4) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [140b5cec40](https://linux-hardware.org/?probe=140b5cec40) | May 31, 2020 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [9c5c59ed91](https://linux-hardware.org/?probe=9c5c59ed91) | May 30, 2020 |
| Packard Be... | EasyNote ME69BMP            | Notebook    | [7023dc94da](https://linux-hardware.org/?probe=7023dc94da) | May 28, 2020 |
| Dell          | Precision M6800             | Notebook    | [fac8dbf769](https://linux-hardware.org/?probe=fac8dbf769) | May 28, 2020 |
| Packard Be... | EasyNote ME69BMP            | Notebook    | [17cb4d2a9a](https://linux-hardware.org/?probe=17cb4d2a9a) | May 28, 2020 |
| Dell          | Precision M4800             | Notebook    | [4f404379b5](https://linux-hardware.org/?probe=4f404379b5) | May 27, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| Lenovo        | ThinkPad T480s 20L7001HM... | Notebook    | [8c6c9a5faa](https://linux-hardware.org/?probe=8c6c9a5faa) | May 25, 2020 |
| Toshiba       | Satellite M500              | Notebook    | [89bc529650](https://linux-hardware.org/?probe=89bc529650) | May 23, 2020 |
| Sony          | VPCF1290X                   | Notebook    | [6d41a82565](https://linux-hardware.org/?probe=6d41a82565) | May 22, 2020 |
| Sony          | VPCF1290X                   | Notebook    | [e260c25549](https://linux-hardware.org/?probe=e260c25549) | May 20, 2020 |
| IBM           | Board                       | Desktop     | [784c83d7d6](https://linux-hardware.org/?probe=784c83d7d6) | May 19, 2020 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8fd77159e9](https://linux-hardware.org/?probe=8fd77159e9) | May 19, 2020 |
| ASUSTek       | X541SA                      | Notebook    | [af59d45f16](https://linux-hardware.org/?probe=af59d45f16) | May 19, 2020 |
| Dell          | 0WF810                      | Desktop     | [24f1a1287d](https://linux-hardware.org/?probe=24f1a1287d) | May 17, 2020 |
| Dell          | 0WF810                      | Desktop     | [6ae0e21069](https://linux-hardware.org/?probe=6ae0e21069) | May 17, 2020 |
| Dell          | 0WF810                      | Desktop     | [e6f27fd467](https://linux-hardware.org/?probe=e6f27fd467) | May 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7610ec6c42](https://linux-hardware.org/?probe=7610ec6c42) | May 17, 2020 |
| Dell          | Latitude E6400              | Notebook    | [5575a3dc87](https://linux-hardware.org/?probe=5575a3dc87) | May 17, 2020 |
| Dell          | Latitude E6400              | Notebook    | [4ad76f6e55](https://linux-hardware.org/?probe=4ad76f6e55) | May 16, 2020 |
| Dell          | Latitude E6400              | Notebook    | [7402a2d316](https://linux-hardware.org/?probe=7402a2d316) | May 16, 2020 |
| Dell          | Latitude E6400              | Notebook    | [9c8f7c7f2c](https://linux-hardware.org/?probe=9c8f7c7f2c) | May 16, 2020 |
| Dell          | Latitude E6400              | Notebook    | [491ea13111](https://linux-hardware.org/?probe=491ea13111) | May 16, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4806bd297f](https://linux-hardware.org/?probe=4806bd297f) | May 16, 2020 |
| Dell          | Latitude E6400              | Notebook    | [0e2b5d699e](https://linux-hardware.org/?probe=0e2b5d699e) | May 16, 2020 |
| HP            | 250 G1                      | Notebook    | [bc48855d22](https://linux-hardware.org/?probe=bc48855d22) | May 16, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d777dde1e9](https://linux-hardware.org/?probe=d777dde1e9) | May 15, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b56e1d0e1a](https://linux-hardware.org/?probe=b56e1d0e1a) | May 13, 2020 |
| Lenovo        | SDK0E50510 WIN 262507961... | Desktop     | [0400e155ee](https://linux-hardware.org/?probe=0400e155ee) | May 10, 2020 |
| Lenovo        | ThinkPad X240 20AMS08816    | Notebook    | [5581eee295](https://linux-hardware.org/?probe=5581eee295) | May 10, 2020 |
| Dell          | XPS L502X                   | Notebook    | [f095fb06d8](https://linux-hardware.org/?probe=f095fb06d8) | May 09, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [567162aae3](https://linux-hardware.org/?probe=567162aae3) | May 09, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [33e1791dd6](https://linux-hardware.org/?probe=33e1791dd6) | May 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1d17b00751](https://linux-hardware.org/?probe=1d17b00751) | May 05, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9a72c58dee](https://linux-hardware.org/?probe=9a72c58dee) | May 04, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a3765f096d](https://linux-hardware.org/?probe=a3765f096d) | May 04, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c5b6d15b98](https://linux-hardware.org/?probe=c5b6d15b98) | May 04, 2020 |
| Samsung       | 550P5C/550P7C               | Notebook    | [4262f676d3](https://linux-hardware.org/?probe=4262f676d3) | May 04, 2020 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [88dd0cfbcb](https://linux-hardware.org/?probe=88dd0cfbcb) | May 02, 2020 |
| Gigabyte      | GA-A75-D3H                  | Desktop     | [530009d42a](https://linux-hardware.org/?probe=530009d42a) | May 02, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [015ef81b51](https://linux-hardware.org/?probe=015ef81b51) | May 02, 2020 |
| ASUSTek       | G73Sw                       | Notebook    | [d4abec1a93](https://linux-hardware.org/?probe=d4abec1a93) | May 02, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [f986b480ad](https://linux-hardware.org/?probe=f986b480ad) | May 01, 2020 |
| Dell          | Inspiron 3576               | Notebook    | [4dc9474ba1](https://linux-hardware.org/?probe=4dc9474ba1) | Apr 29, 2020 |
| Intel         | D946GZIS AAD45436-306       | Desktop     | [483b574b1a](https://linux-hardware.org/?probe=483b574b1a) | Apr 25, 2020 |
| Sony          | VPCS12X9E                   | Notebook    | [3631a4d89d](https://linux-hardware.org/?probe=3631a4d89d) | Apr 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ba2c3155d7](https://linux-hardware.org/?probe=ba2c3155d7) | Apr 22, 2020 |
| Lenovo        | ThinkPad T460s 20F9003WM... | Notebook    | [1b1c89732c](https://linux-hardware.org/?probe=1b1c89732c) | Apr 19, 2020 |
| HP            | EliteBook 755 G5            | Notebook    | [db0ea12ab8](https://linux-hardware.org/?probe=db0ea12ab8) | Apr 16, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [154b970640](https://linux-hardware.org/?probe=154b970640) | Mar 25, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [513772febc](https://linux-hardware.org/?probe=513772febc) | Mar 01, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [ad9b0ebdf6](https://linux-hardware.org/?probe=ad9b0ebdf6) | Feb 25, 2020 |
| Acer          | Aspire V3-574G              | Notebook    | [471f9aa9b0](https://linux-hardware.org/?probe=471f9aa9b0) | Jan 02, 2020 |
| MSI           | GP72 6QF                    | Notebook    | [98dc37dc79](https://linux-hardware.org/?probe=98dc37dc79) | Oct 21, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 40        | 8.3%    |
| 5.4.0-48-generic        | 37        | 7.68%   |
| 5.4.0-52-generic        | 31        | 6.43%   |
| 5.4.0-47-generic        | 23        | 4.77%   |
| 5.4.0-40-generic        | 18        | 3.73%   |
| 5.4.0-45-generic        | 16        | 3.32%   |
| 5.4.0-65-generic        | 14        | 2.9%    |
| 5.4.0-58-generic        | 13        | 2.7%    |
| 5.4.0-66-generic        | 10        | 2.07%   |
| 5.4.0-56-generic        | 10        | 2.07%   |
| 5.4.0-31-generic        | 10        | 2.07%   |
| 5.4.0-29-generic        | 10        | 2.07%   |
| 5.8.0-59-generic        | 9         | 1.87%   |
| 5.4.0-81-generic        | 9         | 1.87%   |
| 5.4.0-26-generic        | 9         | 1.87%   |
| 5.8.0-50-generic        | 8         | 1.66%   |
| 5.4.0-74-generic        | 8         | 1.66%   |
| 5.4.0-67-generic        | 8         | 1.66%   |
| 5.4.0-37-generic        | 8         | 1.66%   |
| 5.8.0-48-generic        | 7         | 1.45%   |
| 5.4.0-80-generic        | 7         | 1.45%   |
| 5.4.0-54-generic        | 7         | 1.45%   |
| 5.4.0-33-generic        | 7         | 1.45%   |
| 5.8.0-53-generic        | 6         | 1.24%   |
| 5.8.0-43-generic        | 6         | 1.24%   |
| 5.4.0-73-generic        | 6         | 1.24%   |
| 5.4.0-72-generic        | 6         | 1.24%   |
| 5.4.0-51-generic        | 6         | 1.24%   |
| 5.4.0-1019-raspi        | 6         | 1.24%   |
| 5.4.0-62-generic        | 5         | 1.04%   |
| 5.4.0-39-generic        | 5         | 1.04%   |
| 5.8.0-55-generic        | 4         | 0.83%   |
| 5.4.0-77-generic        | 4         | 0.83%   |
| 5.4.0-70-generic        | 4         | 0.83%   |
| 5.4.0-59-generic        | 4         | 0.83%   |
| 5.4.0-34-generic        | 4         | 0.83%   |
| 5.4.0-28-generic        | 4         | 0.83%   |
| 5.4.0-1012-raspi        | 4         | 0.83%   |
| 5.11.0-27-generic       | 4         | 0.83%   |
| 5.8.0-45-generic        | 3         | 0.62%   |
| 5.4.0-14-generic        | 3         | 0.62%   |
| 5.4.0-1015-raspi        | 3         | 0.62%   |
| 5.11.0-25-generic       | 3         | 0.62%   |
| 5.8.0-63-generic        | 2         | 0.41%   |
| 5.8.0-38-generic        | 2         | 0.41%   |
| 5.4.0-88-generic        | 2         | 0.41%   |
| 5.4.0-84-generic        | 2         | 0.41%   |
| 5.4.0-64-generic        | 2         | 0.41%   |
| 5.4.0-60-generic        | 2         | 0.41%   |
| 5.4.0-44-generic        | 2         | 0.41%   |
| 5.4.0-43-generic        | 2         | 0.41%   |
| 5.4.0-42-lowlatency     | 2         | 0.41%   |
| 5.4.0-1022-raspi        | 2         | 0.41%   |
| 5.4.0-1018-raspi        | 2         | 0.41%   |
| 5.11.0-34-generic       | 2         | 0.41%   |
| 5.9.3-050903-generic    | 1         | 0.21%   |
| 5.9.0-050900rc8-generic | 1         | 0.21%   |
| 5.8.17-rockchip64       | 1         | 0.21%   |
| 5.8.0-57-generic        | 1         | 0.21%   |
| 5.8.0-52-generic        | 1         | 0.21%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 355       | 82.56%  |
| 5.8.0   | 50        | 11.63%  |
| 5.11.0  | 11        | 2.56%   |
| 5.3.0   | 2         | 0.47%   |
| 5.9.3   | 1         | 0.23%   |
| 5.9.0   | 1         | 0.23%   |
| 5.8.17  | 1         | 0.23%   |
| 5.7.6   | 1         | 0.23%   |
| 5.7.0   | 1         | 0.23%   |
| 5.6.7   | 1         | 0.23%   |
| 5.5.11  | 1         | 0.23%   |
| 5.10.5  | 1         | 0.23%   |
| 5.10.27 | 1         | 0.23%   |
| 5.10.0  | 1         | 0.23%   |
| 4.9.230 | 1         | 0.23%   |
| 4.14.89 | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 355       | 82.56%  |
| 5.8     | 51        | 11.86%  |
| 5.11    | 11        | 2.56%   |
| 5.10    | 3         | 0.7%    |
| 5.9     | 2         | 0.47%   |
| 5.7     | 2         | 0.47%   |
| 5.3     | 2         | 0.47%   |
| 5.6     | 1         | 0.23%   |
| 5.5     | 1         | 0.23%   |
| 4.9     | 1         | 0.23%   |
| 4.14    | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 404       | 94.61%  |
| aarch64 | 22        | 5.15%   |
| armv7l  | 1         | 0.23%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 420       | 98.36%  |
| X-Cinnamon | 2         | 0.47%   |
| GNOME      | 2         | 0.47%   |
| Trinity    | 1         | 0.23%   |
| i3         | 1         | 0.23%   |
| cinnamon   | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 416       | 97.2%   |
| Tty     | 9         | 2.1%    |
| Wayland | 3         | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 214       | 49.08%  |
| Unknown | 159       | 36.47%  |
| LightDM | 41        | 9.4%    |
| GDM     | 18        | 4.13%   |
| SDDM    | 2         | 0.46%   |
| SLiM    | 1         | 0.23%   |
| GDM3    | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 122       | 28.44%  |
| pt_BR   | 81        | 18.88%  |
| de_DE   | 32        | 7.46%   |
| fr_FR   | 30        | 6.99%   |
| en_GB   | 26        | 6.06%   |
| ru_RU   | 14        | 3.26%   |
| es_ES   | 14        | 3.26%   |
| it_IT   | 13        | 3.03%   |
| C       | 12        | 2.8%    |
| en_CA   | 10        | 2.33%   |
| es_AR   | 8         | 1.86%   |
| pl_PL   | 6         | 1.4%    |
| nl_NL   | 5         | 1.17%   |
| de_CH   | 5         | 1.17%   |
| ru_UA   | 4         | 0.93%   |
| en_AU   | 4         | 0.93%   |
| cs_CZ   | 4         | 0.93%   |
| en_PH   | 3         | 0.7%    |
| en_IN   | 3         | 0.7%    |
| sv_SE   | 2         | 0.47%   |
| hu_HU   | 2         | 0.47%   |
| hr_HR   | 2         | 0.47%   |
| fr_CA   | 2         | 0.47%   |
| fi_FI   | 2         | 0.47%   |
| da_DK   | 2         | 0.47%   |
| ca_ES   | 2         | 0.47%   |
| uk_UA   | 1         | 0.23%   |
| sk_SK   | 1         | 0.23%   |
| lv_LV   | 1         | 0.23%   |
| ja_JP   | 1         | 0.23%   |
| fr_BE   | 1         | 0.23%   |
| eu_ES   | 1         | 0.23%   |
| et_EE   | 1         | 0.23%   |
| es_UY   | 1         | 0.23%   |
| es_PE   | 1         | 0.23%   |
| es_PA   | 1         | 0.23%   |
| es_MX   | 1         | 0.23%   |
| es_GT   | 1         | 0.23%   |
| es_CL   | 1         | 0.23%   |
| en_ZA   | 1         | 0.23%   |
| en_SG   | 1         | 0.23%   |
| en_IE   | 1         | 0.23%   |
| el_GR   | 1         | 0.23%   |
| de_AT   | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 223       | 51.86%  |
| EFI  | 207       | 48.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 404       | 94.17%  |
| Overlay | 11        | 2.56%   |
| Btrfs   | 5         | 1.17%   |
| Xfs     | 4         | 0.93%   |
| Zfs     | 3         | 0.7%    |
| ExX4    | 1         | 0.23%   |
| Ext3    | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 164       | 38.05%  |
| GPT     | 143       | 33.18%  |
| MBR     | 124       | 28.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 381       | 88.4%   |
| Yes       | 50        | 11.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 312       | 72.06%  |
| Yes       | 121       | 27.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 82        | 19.2%   |
| Dell                    | 76        | 17.8%   |
| Lenovo                  | 55        | 12.88%  |
| ASUSTek Computer        | 53        | 12.41%  |
| Gigabyte Technology     | 26        | 6.09%   |
| MSI                     | 22        | 5.15%   |
| Raspberry Pi Foundation | 19        | 4.45%   |
| Acer                    | 15        | 3.51%   |
| ASRock                  | 13        | 3.04%   |
| Intel                   | 12        | 2.81%   |
| Toshiba                 | 6         | 1.41%   |
| Samsung Electronics     | 5         | 1.17%   |
| Medion                  | 5         | 1.17%   |
| Unknown                 | 5         | 1.17%   |
| Sony                    | 3         | 0.7%    |
| Apple                   | 3         | 0.7%    |
| Supermicro              | 2         | 0.47%   |
| Positivo                | 2         | 0.47%   |
| Pegatron                | 2         | 0.47%   |
| Packard Bell            | 2         | 0.47%   |
| Notebook                | 2         | 0.47%   |
| Biostar                 | 2         | 0.47%   |
| Wortmann AG             | 1         | 0.23%   |
| Teclast                 | 1         | 0.23%   |
| System76                | 1         | 0.23%   |
| Star Labs               | 1         | 0.23%   |
| Semp Toshiba            | 1         | 0.23%   |
| Pine Microsystems       | 1         | 0.23%   |
| ONE-NETBOOK TECHNOLOGY  | 1         | 0.23%   |
| JINGSHA                 | 1         | 0.23%   |
| IBM                     | 1         | 0.23%   |
| Hardkernel              | 1         | 0.23%   |
| GPD                     | 1         | 0.23%   |
| Gateway                 | 1         | 0.23%   |
| Fujitsu Siemens         | 1         | 0.23%   |
| Cube                    | 1         | 0.23%   |
| Chuwi                   | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| RPi Raspberry Pi 4 Model B Rev 1.2         | 8         | 1.87%   |
| HP Compaq 6005 Pro SFF PC                  | 8         | 1.87%   |
| HP Compaq Elite 8300 SFF                   | 7         | 1.64%   |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 6         | 1.41%   |
| Dell OptiPlex 3010                         | 5         | 1.17%   |
| Dell Latitude E6420                        | 5         | 1.17%   |
| Unknown                                    | 5         | 1.17%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 4         | 0.94%   |
| Dell OptiPlex 390                          | 4         | 0.94%   |
| HP Notebook                                | 3         | 0.7%    |
| HP Compaq 6200 Pro SFF PC                  | 3         | 0.7%    |
| Dell Precision M4800                       | 3         | 0.7%    |
| Dell OptiPlex 360                          | 3         | 0.7%    |
| Dell Latitude E6410                        | 3         | 0.7%    |
| ASUS M5A78L-M/USB3                         | 3         | 0.7%    |
| MSI MS-7680                                | 2         | 0.47%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 0.47%   |
| Lenovo IdeaPad Flex 5 14ARE05 81X2         | 2         | 0.47%   |
| HP x2 Detachable 10-p0XX                   | 2         | 0.47%   |
| HP Pavilion g6                             | 2         | 0.47%   |
| HP Pavilion dv7                            | 2         | 0.47%   |
| HP EliteBook 8470p                         | 2         | 0.47%   |
| HP Compaq 4000 Pro SFF PC                  | 2         | 0.47%   |
| Gigabyte Z97-HD3                           | 2         | 0.47%   |
| Gigabyte B450M DS3H                        | 2         | 0.47%   |
| Dell OptiPlex 780                          | 2         | 0.47%   |
| Dell OptiPlex 755                          | 2         | 0.47%   |
| Dell OptiPlex 380                          | 2         | 0.47%   |
| Dell OptiPlex 330                          | 2         | 0.47%   |
| Dell Latitude E6430                        | 2         | 0.47%   |
| Dell Inspiron 3421                         | 2         | 0.47%   |
| ASUS ZenBook UX431DA_UM431DA               | 2         | 0.47%   |
| ASUS P8H61-M LX3 R2.0                      | 2         | 0.47%   |
| ASUS M2N68-AM Plus                         | 2         | 0.47%   |
| ASUS All Series                            | 2         | 0.47%   |
| ASRock B450M Pro4                          | 2         | 0.47%   |
| Wortmann AG TERRA_MOBILE_1749              | 1         | 0.23%   |
| Toshiba Satellite Pro L500                 | 1         | 0.23%   |
| Toshiba Satellite Pro C660                 | 1         | 0.23%   |
| Toshiba Satellite M500                     | 1         | 0.23%   |
| Toshiba Satellite L350D                    | 1         | 0.23%   |
| Toshiba Satellite C675                     | 1         | 0.23%   |
| Toshiba Satellite C660                     | 1         | 0.23%   |
| Teclast F15S                               | 1         | 0.23%   |
| System76 Serval WS                         | 1         | 0.23%   |
| Supermicro X10SAE                          | 1         | 0.23%   |
| Supermicro Super Server                    | 1         | 0.23%   |
| Star Labs LabTop                           | 1         | 0.23%   |
| Sony VPCS12X9E                             | 1         | 0.23%   |
| Sony VPCF1290X                             | 1         | 0.23%   |
| Sony VPCEH1S1E                             | 1         | 0.23%   |
| Semp Toshiba STI                           | 1         | 0.23%   |
| Samsung SR58P                              | 1         | 0.23%   |
| Samsung 550P5C/550P7C                      | 1         | 0.23%   |
| Samsung 530U4E/540U4E                      | 1         | 0.23%   |
| Samsung 350V5C/351V5C/3540VC/3440VC        | 1         | 0.23%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.23%   |
| RPi Raspberry Pi 3 Model B Rev 1.2         | 1         | 0.23%   |
| Positivo N8X0EK1                           | 1         | 0.23%   |
| Positivo Mobile                            | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 33        | 7.73%   |
| HP Compaq             | 28        | 6.56%   |
| Dell OptiPlex         | 27        | 6.32%   |
| RPi Raspberry         | 19        | 4.45%   |
| Dell Latitude         | 18        | 4.22%   |
| HP Pavilion           | 15        | 3.51%   |
| Acer Aspire           | 11        | 2.58%   |
| Lenovo IdeaPad        | 10        | 2.34%   |
| Dell Inspiron         | 10        | 2.34%   |
| HP EliteBook          | 8         | 1.87%   |
| Dell Precision        | 8         | 1.87%   |
| Toshiba Satellite     | 6         | 1.41%   |
| ASUS PRIME            | 6         | 1.41%   |
| HP 250                | 5         | 1.17%   |
| Unknown               | 5         | 1.17%   |
| Lenovo ThinkCentre    | 4         | 0.94%   |
| HP ProBook            | 4         | 0.94%   |
| Dell XPS              | 4         | 0.94%   |
| ASUS M5A78L-M         | 4         | 0.94%   |
| HP Notebook           | 3         | 0.7%    |
| Dell Vostro           | 3         | 0.7%    |
| ASUS VivoBook         | 3         | 0.7%    |
| ASUS M5A97            | 3         | 0.7%    |
| Packard Bell EasyNote | 2         | 0.47%   |
| MSI MS-7680           | 2         | 0.47%   |
| Lenovo ThinkBook      | 2         | 0.47%   |
| Lenovo Legion         | 2         | 0.47%   |
| HP ZBook              | 2         | 0.47%   |
| HP x2                 | 2         | 0.47%   |
| HP ProLiant           | 2         | 0.47%   |
| HP ProDesk            | 2         | 0.47%   |
| HP Laptop             | 2         | 0.47%   |
| Gigabyte Z97-HD3      | 2         | 0.47%   |
| Gigabyte X570         | 2         | 0.47%   |
| Gigabyte B450M        | 2         | 0.47%   |
| Gigabyte B450         | 2         | 0.47%   |
| Dell Studio           | 2         | 0.47%   |
| ASUS ZenBook          | 2         | 0.47%   |
| ASUS TUF              | 2         | 0.47%   |
| ASUS P9X79            | 2         | 0.47%   |
| ASUS P8H61-M          | 2         | 0.47%   |
| ASUS M2N68-AM         | 2         | 0.47%   |
| ASUS All              | 2         | 0.47%   |
| ASRock B450M          | 2         | 0.47%   |
| Wortmann AG TERRA     | 1         | 0.23%   |
| Teclast F15S          | 1         | 0.23%   |
| System76 Serval       | 1         | 0.23%   |
| Supermicro X10SAE     | 1         | 0.23%   |
| Supermicro Super      | 1         | 0.23%   |
| Star Labs LabTop      | 1         | 0.23%   |
| Sony VPCS12X9E        | 1         | 0.23%   |
| Sony VPCF1290X        | 1         | 0.23%   |
| Sony VPCEH1S1E        | 1         | 0.23%   |
| Semp Toshiba STI      | 1         | 0.23%   |
| Samsung SR58P         | 1         | 0.23%   |
| Samsung 550P5C        | 1         | 0.23%   |
| Samsung 530U4E        | 1         | 0.23%   |
| Samsung 350V5C        | 1         | 0.23%   |
| Samsung 300E4A        | 1         | 0.23%   |
| Positivo N8X0EK1      | 1         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 56        | 13.11%  |
| 2019    | 55        | 12.88%  |
| 2020    | 50        | 11.71%  |
| 2011    | 39        | 9.13%   |
| 2012    | 31        | 7.26%   |
| 2013    | 30        | 7.03%   |
| 2015    | 29        | 6.79%   |
| 2014    | 25        | 5.85%   |
| Unknown | 21        | 4.92%   |
| 2010    | 18        | 4.22%   |
| 2016    | 16        | 3.75%   |
| 2009    | 14        | 3.28%   |
| 2017    | 13        | 3.04%   |
| 2021    | 12        | 2.81%   |
| 2008    | 12        | 2.81%   |
| 2006    | 3         | 0.7%    |
| 2007    | 2         | 0.47%   |
| 2005    | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 200       | 46.84%  |
| Desktop        | 183       | 42.86%  |
| System on chip | 22        | 5.15%   |
| Convertible    | 8         | 1.87%   |
| Server         | 6         | 1.41%   |
| Tablet         | 3         | 0.7%    |
| Mini pc        | 3         | 0.7%    |
| All in one     | 2         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 401       | 93.69%  |
| Enabled  | 27        | 6.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 427       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 145       | 33.8%   |
| 4.01-8.0        | 84        | 19.58%  |
| 8.01-16.0       | 64        | 14.92%  |
| 16.01-24.0      | 61        | 14.22%  |
| 32.01-64.0      | 32        | 7.46%   |
| 64.01-256.0     | 16        | 3.73%   |
| 1.01-2.0        | 9         | 2.1%    |
| 24.01-32.0      | 7         | 1.63%   |
| 2.01-3.0        | 7         | 1.63%   |
| 0.51-1.0        | 3         | 0.7%    |
| More than 256.0 | 1         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 165       | 36.42%  |
| 2.01-3.0   | 92        | 20.31%  |
| 0.51-1.0   | 84        | 18.54%  |
| 4.01-8.0   | 48        | 10.6%   |
| 3.01-4.0   | 46        | 10.15%  |
| 8.01-16.0  | 11        | 2.43%   |
| 32.01-64.0 | 2         | 0.44%   |
| 24.01-32.0 | 2         | 0.44%   |
| 16.01-24.0 | 2         | 0.44%   |
| 0.01-0.5   | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 274       | 62.41%  |
| 2      | 105       | 23.92%  |
| 3      | 31        | 7.06%   |
| 4      | 11        | 2.51%   |
| 5      | 4         | 0.91%   |
| 7      | 3         | 0.68%   |
| 0      | 3         | 0.68%   |
| 10     | 2         | 0.46%   |
| 8      | 2         | 0.46%   |
| 6      | 2         | 0.46%   |
| 11     | 1         | 0.23%   |
| 9      | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 215       | 50%     |
| No        | 215       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 375       | 87.62%  |
| No        | 53        | 12.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 275       | 64.1%   |
| No        | 154       | 35.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 216       | 50.23%  |
| Yes       | 214       | 49.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Brazil       | 90        | 20.93%  |
| USA          | 51        | 11.86%  |
| Germany      | 39        | 9.07%   |
| France       | 34        | 7.91%   |
| UK           | 28        | 6.51%   |
| Spain        | 18        | 4.19%   |
| Russia       | 18        | 4.19%   |
| Italy        | 16        | 3.72%   |
| Canada       | 11        | 2.56%   |
| Argentina    | 10        | 2.33%   |
| Netherlands  | 9         | 2.09%   |
| Ukraine      | 8         | 1.86%   |
| Switzerland  | 8         | 1.86%   |
| Czechia      | 7         | 1.63%   |
| Poland       | 6         | 1.4%    |
| Finland      | 5         | 1.16%   |
| Norway       | 4         | 0.93%   |
| Turkey       | 3         | 0.7%    |
| Sweden       | 3         | 0.7%    |
| Mexico       | 3         | 0.7%    |
| India        | 3         | 0.7%    |
| Greece       | 3         | 0.7%    |
| Croatia      | 3         | 0.7%    |
| Chile        | 3         | 0.7%    |
| Austria      | 3         | 0.7%    |
| Australia    | 3         | 0.7%    |
| Vietnam      | 2         | 0.47%   |
| Taiwan       | 2         | 0.47%   |
| Philippines  | 2         | 0.47%   |
| Japan        | 2         | 0.47%   |
| Ireland      | 2         | 0.47%   |
| Indonesia    | 2         | 0.47%   |
| Hungary      | 2         | 0.47%   |
| Denmark      | 2         | 0.47%   |
| Belgium      | 2         | 0.47%   |
| Belarus      | 2         | 0.47%   |
| Uruguay      | 1         | 0.23%   |
| UAE          | 1         | 0.23%   |
| Thailand     | 1         | 0.23%   |
| South Africa | 1         | 0.23%   |
| Slovakia     | 1         | 0.23%   |
| Singapore    | 1         | 0.23%   |
| Saudi Arabia | 1         | 0.23%   |
| Réunion     | 1         | 0.23%   |
| Romania      | 1         | 0.23%   |
| Peru         | 1         | 0.23%   |
| Panama       | 1         | 0.23%   |
| Malaysia     | 1         | 0.23%   |
| Luxembourg   | 1         | 0.23%   |
| Latvia       | 1         | 0.23%   |
| Kenya        | 1         | 0.23%   |
| Hong Kong    | 1         | 0.23%   |
| Guatemala    | 1         | 0.23%   |
| Estonia      | 1         | 0.23%   |
| Ecuador      | 1         | 0.23%   |
| Cyprus       | 1         | 0.23%   |
| Bulgaria     | 1         | 0.23%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| São Paulo             | 33        | 7.42%   |
| Jundiaí               | 24        | 5.39%   |
| Itatiba                | 8         | 1.8%    |
| Berlin                 | 6         | 1.35%   |
| Paris                  | 5         | 1.12%   |
| Manchester             | 5         | 1.12%   |
| Rome                   | 4         | 0.9%    |
| Zurich                 | 3         | 0.67%   |
| Zagreb                 | 3         | 0.67%   |
| Rio de Janeiro         | 3         | 0.67%   |
| Moscow                 | 3         | 0.67%   |
| Le Kremlin-Bicetre     | 3         | 0.67%   |
| Bergschenhoek          | 3         | 0.67%   |
| Barcelona              | 3         | 0.67%   |
| Yekaterinburg          | 2         | 0.45%   |
| Włocławek            | 2         | 0.45%   |
| Vigo                   | 2         | 0.45%   |
| Vienna                 | 2         | 0.45%   |
| Trondheim              | 2         | 0.45%   |
| São José dos Pinhais | 2         | 0.45%   |
| Srednyaya Akhtuba      | 2         | 0.45%   |
| Prague                 | 2         | 0.45%   |
| Oslo                   | 2         | 0.45%   |
| Nottingham             | 2         | 0.45%   |
| Montreal               | 2         | 0.45%   |
| Milan                  | 2         | 0.45%   |
| Melbourne              | 2         | 0.45%   |
| Marseille              | 2         | 0.45%   |
| Madrid                 | 2         | 0.45%   |
| London                 | 2         | 0.45%   |
| Lodz                   | 2         | 0.45%   |
| Kyiv                   | 2         | 0.45%   |
| Kirchheim unter Teck   | 2         | 0.45%   |
| Karlsruhe              | 2         | 0.45%   |
| Ho Chi Minh City       | 2         | 0.45%   |
| Herriman               | 2         | 0.45%   |
| Florence               | 2         | 0.45%   |
| Essen                  | 2         | 0.45%   |
| Ely                    | 2         | 0.45%   |
| Durham                 | 2         | 0.45%   |
| Dublin                 | 2         | 0.45%   |
| Biysk                  | 2         | 0.45%   |
| Biddulph               | 2         | 0.45%   |
| Basel                  | 2         | 0.45%   |
| Bagnoles-de-l'Orne     | 2         | 0.45%   |
| Ankara                 | 2         | 0.45%   |
| Amsterdam              | 2         | 0.45%   |
| Zapopan                | 1         | 0.22%   |
| Worb                   | 1         | 0.22%   |
| Windsor                | 1         | 0.22%   |
| Willimantic            | 1         | 0.22%   |
| Westbury               | 1         | 0.22%   |
| West Babylon           | 1         | 0.22%   |
| Welland                | 1         | 0.22%   |
| Wejherowo              | 1         | 0.22%   |
| Warren                 | 1         | 0.22%   |
| Wake Forest            | 1         | 0.22%   |
| Viña del Mar          | 1         | 0.22%   |
| Village-Neuf           | 1         | 0.22%   |
| Vigneux-sur-Seine      | 1         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 120       | 161    | 20.1%   |
| Seagate                   | 103       | 152    | 17.25%  |
| Samsung Electronics       | 76        | 107    | 12.73%  |
| Unknown                   | 45        | 61     | 7.54%   |
| Kingston                  | 43        | 55     | 7.2%    |
| Toshiba                   | 37        | 52     | 6.2%    |
| SanDisk                   | 25        | 29     | 4.19%   |
| Hitachi                   | 22        | 26     | 3.69%   |
| Intel                     | 17        | 20     | 2.85%   |
| Crucial                   | 14        | 23     | 2.35%   |
| SK Hynix                  | 9         | 12     | 1.51%   |
| A-DATA Technology         | 8         | 8      | 1.34%   |
| HGST                      | 7         | 9      | 1.17%   |
| China                     | 6         | 7      | 1.01%   |
| Silicon Motion            | 5         | 6      | 0.84%   |
| PNY                       | 5         | 5      | 0.84%   |
| Patriot                   | 4         | 6      | 0.67%   |
| Phison                    | 3         | 3      | 0.5%    |
| MAXTOR                    | 3         | 9      | 0.5%    |
| Apacer                    | 3         | 3      | 0.5%    |
| Micron/Crucial Technology | 2         | 4      | 0.34%   |
| Micron Technology         | 2         | 2      | 0.34%   |
| KIOXIA                    | 2         | 2      | 0.34%   |
| JMicron                   | 2         | 4      | 0.34%   |
| Intenso                   | 2         | 2      | 0.34%   |
| Fujitsu                   | 2         | 2      | 0.34%   |
| Vaseky                    | 1         | 1      | 0.17%   |
| USB3.0                    | 1         | 1      | 0.17%   |
| Union Memory              | 1         | 1      | 0.17%   |
| Transcend                 | 1         | 1      | 0.17%   |
| TO Exter                  | 1         | 1      | 0.17%   |
| Solid State Storage       | 1         | 1      | 0.17%   |
| SMI                       | 1         | 1      | 0.17%   |
| SMART                     | 1         | 1      | 0.17%   |
| SABRENT                   | 1         | 1      | 0.17%   |
| Realtek Semiconductor     | 1         | 1      | 0.17%   |
| PLEXTOR                   | 1         | 1      | 0.17%   |
| OCZ                       | 1         | 1      | 0.17%   |
| Netac                     | 1         | 1      | 0.17%   |
| Mushkin                   | 1         | 1      | 0.17%   |
| Marlin                    | 1         | 1      | 0.17%   |
| LITEONIT                  | 1         | 2      | 0.17%   |
| Lexar                     | 1         | 1      | 0.17%   |
| LDLC                      | 1         | 1      | 0.17%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.17%   |
| KingSpec                  | 1         | 1      | 0.17%   |
| Inateck                   | 1         | 1      | 0.17%   |
| Hewlett-Packard           | 1         | 1      | 0.17%   |
| FORESEE                   | 1         | 1      | 0.17%   |
| faspeed                   | 1         | 1      | 0.17%   |
| ASMT109x                  | 1         | 2      | 0.17%   |
| ASMT                      | 1         | 2      | 0.17%   |
| AMD                       | 1         | 1      | 0.17%   |
| AGI                       | 1         | 1      | 0.17%   |
| addlink                   | 1         | 2      | 0.17%   |
| ADATA SP                  | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  64GB               | 11        | 1.7%    |
| Seagate ST500DM002-1BD142 500GB      | 11        | 1.7%    |
| Kingston SA400S37120G 120GB SSD      | 11        | 1.7%    |
| Unknown MMC Card  32GB               | 10        | 1.54%   |
| Kingston SA400S37240G 240GB SSD      | 8         | 1.23%   |
| WDC WD5000AAKX-083CA1 500GB          | 6         | 0.93%   |
| WDC WD5000AAKX-003CA0 500GB          | 6         | 0.93%   |
| Unknown MMC Card  16GB               | 6         | 0.93%   |
| Toshiba MQ01ABF050 500GB             | 6         | 0.93%   |
| Seagate ST320LT007-9ZV142 320GB      | 6         | 0.93%   |
| Seagate ST3500418AS 500GB            | 5         | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB       | 5         | 0.77%   |
| Samsung HD322HJ 320GB                | 5         | 0.77%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 0.62%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB       | 4         | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.62%   |
| Samsung SSD 860 EVO 500GB            | 4         | 0.62%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 0.46%   |
| WDC WD2500AAKX-753CA1 250GB          | 3         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB             | 3         | 0.46%   |
| Unknown SD/MMC/MS PRO 128GB          | 3         | 0.46%   |
| Unknown MMC Card  128GB              | 3         | 0.46%   |
| Unknown DA4064  64GB                 | 3         | 0.46%   |
| Toshiba MQ04ABF100 1TB               | 3         | 0.46%   |
| Seagate ST8000DM004-2CX188 8TB       | 3         | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB       | 3         | 0.46%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 0.46%   |
| SanDisk SSD U100 16GB                | 3         | 0.46%   |
| Sandisk NVMe SSD Drive 512GB         | 3         | 0.46%   |
| Samsung NVMe SSD Drive 500GB         | 3         | 0.46%   |
| Samsung HD502HJ 500GB                | 3         | 0.46%   |
| Kingston SV300S37A240G 240GB SSD     | 3         | 0.46%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 0.46%   |
| Intel SSDPEKNW512G8 512GB            | 3         | 0.46%   |
| Hitachi HTS545050B9A300 500GB        | 3         | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.31%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 2         | 0.31%   |
| WDC WD5000AZLX-75K2TA0 500GB         | 2         | 0.31%   |
| WDC WD3200AAKS-75L9A0 320GB          | 2         | 0.31%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 2         | 0.31%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 0.31%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 0.31%   |
| WDC WD10EZEX-08M2NA0 1TB             | 2         | 0.31%   |
| WDC WD10EARX-00N0YB0 1TB             | 2         | 0.31%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 2         | 0.31%   |
| Toshiba MQ01ACF032 320GB             | 2         | 0.31%   |
| Toshiba MQ01ABD050 500GB             | 2         | 0.31%   |
| Toshiba MK7559GSXP 752GB             | 2         | 0.31%   |
| Toshiba MK2561GSYN 250GB             | 2         | 0.31%   |
| Toshiba DT01ACA300 3TB               | 2         | 0.31%   |
| Seagate ST9500420AS 500GB            | 2         | 0.31%   |
| Seagate ST9250410AS 250GB            | 2         | 0.31%   |
| Seagate ST3500630AS 500GB            | 2         | 0.31%   |
| Seagate ST3320620AS 320GB            | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 102       | 150    | 35.42%  |
| WDC                 | 97        | 131    | 33.68%  |
| Toshiba             | 31        | 46     | 10.76%  |
| Hitachi             | 22        | 26     | 7.64%   |
| Samsung Electronics | 18        | 18     | 6.25%   |
| HGST                | 7         | 9      | 2.43%   |
| Unknown             | 3         | 3      | 1.04%   |
| MAXTOR              | 2         | 7      | 0.69%   |
| Fujitsu             | 2         | 2      | 0.69%   |
| USB3.0              | 1         | 1      | 0.35%   |
| TO Exter            | 1         | 1      | 0.35%   |
| ASMT109x            | 1         | 2      | 0.35%   |
| ASMT                | 1         | 2      | 0.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 40        | 47     | 21.62%  |
| Samsung Electronics | 39        | 57     | 21.08%  |
| SanDisk             | 19        | 23     | 10.27%  |
| WDC                 | 15        | 19     | 8.11%   |
| Crucial             | 13        | 22     | 7.03%   |
| Intel               | 8         | 10     | 4.32%   |
| A-DATA Technology   | 8         | 8      | 4.32%   |
| China               | 6         | 7      | 3.24%   |
| PNY                 | 5         | 5      | 2.7%    |
| Toshiba             | 3         | 3      | 1.62%   |
| Patriot             | 3         | 5      | 1.62%   |
| Apacer              | 3         | 3      | 1.62%   |
| Seagate             | 2         | 2      | 1.08%   |
| Intenso             | 2         | 2      | 1.08%   |
| Vaseky              | 1         | 1      | 0.54%   |
| Transcend           | 1         | 1      | 0.54%   |
| SMI                 | 1         | 1      | 0.54%   |
| SMART               | 1         | 1      | 0.54%   |
| SK Hynix            | 1         | 4      | 0.54%   |
| SABRENT             | 1         | 1      | 0.54%   |
| PLEXTOR             | 1         | 1      | 0.54%   |
| OCZ                 | 1         | 1      | 0.54%   |
| Netac               | 1         | 1      | 0.54%   |
| Mushkin             | 1         | 1      | 0.54%   |
| Micron Technology   | 1         | 1      | 0.54%   |
| MAXTOR              | 1         | 2      | 0.54%   |
| LITEONIT            | 1         | 2      | 0.54%   |
| Lexar               | 1         | 1      | 0.54%   |
| LDLC                | 1         | 1      | 0.54%   |
| KingSpec            | 1         | 1      | 0.54%   |
| FORESEE             | 1         | 1      | 0.54%   |
| AMD                 | 1         | 1      | 0.54%   |
| ADATA SP            | 1         | 1      | 0.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 248       | 398    | 46.1%   |
| SSD     | 163       | 237    | 30.3%   |
| NVMe    | 80        | 103    | 14.87%  |
| MMC     | 41        | 58     | 7.62%   |
| Unknown | 6         | 8      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 343       | 615    | 70.43%  |
| NVMe | 80        | 103    | 16.43%  |
| MMC  | 41        | 58     | 8.42%   |
| SAS  | 23        | 28     | 4.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 264       | 373    | 60.41%  |
| 0.51-1.0   | 110       | 146    | 25.17%  |
| 1.01-2.0   | 34        | 52     | 7.78%   |
| 4.01-10.0  | 11        | 28     | 2.52%   |
| 3.01-4.0   | 10        | 15     | 2.29%   |
| 2.01-3.0   | 6         | 12     | 1.37%   |
| 10.01-20.0 | 2         | 9      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 133       | 30.09%  |
| 101-250        | 91        | 20.59%  |
| 501-1000       | 68        | 15.38%  |
| 1001-2000      | 38        | 8.6%    |
| 51-100         | 29        | 6.56%   |
| More than 3000 | 27        | 6.11%   |
| 1-20           | 24        | 5.43%   |
| 21-50          | 19        | 4.3%    |
| 2001-3000      | 13        | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 172       | 37.8%   |
| 21-50          | 71        | 15.6%   |
| 101-250        | 69        | 15.16%  |
| 51-100         | 51        | 11.21%  |
| 251-500        | 37        | 8.13%   |
| 501-1000       | 25        | 5.49%   |
| 1001-2000      | 14        | 3.08%   |
| 2001-3000      | 9         | 1.98%   |
| More than 3000 | 7         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB          | 5         | 5      | 7.14%   |
| WDC WD5000AAKX-083CA1 500GB              | 4         | 4      | 5.71%   |
| Seagate ST320LT007-9ZV142 320GB          | 4         | 4      | 5.71%   |
| WDC WD5000AAKX-003CA0 500GB              | 2         | 2      | 2.86%   |
| WDC WD2500AAKX-753CA1 250GB              | 2         | 2      | 2.86%   |
| Toshiba MK7559GSXP 752GB                 | 2         | 2      | 2.86%   |
| Seagate ST3500418AS 500GB                | 2         | 2      | 2.86%   |
| Samsung Electronics HD502HJ 500GB        | 2         | 2      | 2.86%   |
| WDC WD7500BPVT-75HXZT1 752GB             | 1         | 1      | 1.43%   |
| WDC WD7500BPKT-75PK4T0 752GB             | 1         | 1      | 1.43%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 1      | 1.43%   |
| WDC WD5000BPKT-75PK4T0 500GB             | 1         | 2      | 1.43%   |
| WDC WD3200AAJS-40VWA1 320GB              | 1         | 1      | 1.43%   |
| WDC WD2500YS-01SHB1 256GB                | 1         | 1      | 1.43%   |
| WDC WD2500AAKX-75U6AA0 250GB             | 1         | 1      | 1.43%   |
| WDC WD2500AAJS-75M0A0 250GB              | 1         | 1      | 1.43%   |
| WDC WD1600AAJS-75M0A0 160GB              | 1         | 2      | 1.43%   |
| WDC WD15EADS-00P8B0 1TB                  | 1         | 1      | 1.43%   |
| WDC WD1200JD-00HBB0 120GB                | 1         | 1      | 1.43%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1         | 1      | 1.43%   |
| WDC WD10EFRX-68PJCN0 1TB                 | 1         | 1      | 1.43%   |
| Vaseky V820/1TB SSD                      | 1         | 1      | 1.43%   |
| Toshiba MQ01ABD050 500GB                 | 1         | 1      | 1.43%   |
| Toshiba MK5065GSX 500GB                  | 1         | 1      | 1.43%   |
| Toshiba MK5055GSX 500GB                  | 1         | 1      | 1.43%   |
| Seagate ST9500420AS 500GB                | 1         | 1      | 1.43%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 1.43%   |
| Seagate ST9250410AS 250GB                | 1         | 1      | 1.43%   |
| Seagate ST9160821AS 160GB                | 1         | 1      | 1.43%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1      | 1.43%   |
| Seagate ST3750525AS 752GB                | 1         | 1      | 1.43%   |
| Seagate ST3360320AS 360GB                | 1         | 2      | 1.43%   |
| Seagate ST3320620AS 320GB                | 1         | 1      | 1.43%   |
| Seagate ST3250318AS 250GB                | 1         | 1      | 1.43%   |
| Seagate ST3250310AS 250GB                | 1         | 1      | 1.43%   |
| Seagate ST31000333AS 1TB                 | 1         | 1      | 1.43%   |
| Seagate ST1000DM003-1CH162 1TB           | 1         | 1      | 1.43%   |
| SanDisk SSD PLUS 480GB                   | 1         | 1      | 1.43%   |
| Samsung Electronics SSD 840 Series 250GB | 1         | 1      | 1.43%   |
| Samsung Electronics SP2504C 250GB        | 1         | 1      | 1.43%   |
| Samsung Electronics HM160HI 160GB        | 1         | 1      | 1.43%   |
| OCZ VERTEX450 128GB SSD                  | 1         | 1      | 1.43%   |
| MAXTOR 6Y160M0 163GB                     | 1         | 1      | 1.43%   |
| Kingston SHPM2280P2H 240G SSD            | 1         | 1      | 1.43%   |
| Intel SSDSA2M080G2GC 80GB                | 1         | 1      | 1.43%   |
| Hitachi HTS722016K9A300 160GB            | 1         | 1      | 1.43%   |
| Hitachi HTS547575A9E384 752GB            | 1         | 1      | 1.43%   |
| Hitachi HTS545050B9A300 500GB            | 1         | 1      | 1.43%   |
| Hitachi HDT721050SLA360 500GB            | 1         | 1      | 1.43%   |
| HGST HDN726040ALE614 4TB                 | 1         | 2      | 1.43%   |
| Fujitsu MHZ2320BH G1 320GB               | 1         | 1      | 1.43%   |
| Crucial CT1050MX300SSD1 1TB              | 1         | 1      | 1.43%   |
| China SSD 120GB                          | 1         | 1      | 1.43%   |
| ASMT USB 3.0 Destop H 2TB                | 1         | 2      | 1.43%   |
| A-DATA Technology SP900 64GB SSD         | 1         | 1      | 1.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 24     | 33.33%  |
| WDC                 | 20        | 23     | 28.99%  |
| Toshiba             | 5         | 5      | 7.25%   |
| Samsung Electronics | 5         | 5      | 7.25%   |
| Hitachi             | 4         | 4      | 5.8%    |
| Vaseky              | 1         | 1      | 1.45%   |
| SanDisk             | 1         | 1      | 1.45%   |
| OCZ                 | 1         | 1      | 1.45%   |
| MAXTOR              | 1         | 1      | 1.45%   |
| Kingston            | 1         | 1      | 1.45%   |
| Intel               | 1         | 1      | 1.45%   |
| HGST                | 1         | 2      | 1.45%   |
| Fujitsu             | 1         | 1      | 1.45%   |
| Crucial             | 1         | 1      | 1.45%   |
| China               | 1         | 1      | 1.45%   |
| ASMT                | 1         | 2      | 1.45%   |
| A-DATA Technology   | 1         | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 24     | 38.33%  |
| WDC                 | 20        | 23     | 33.33%  |
| Toshiba             | 5         | 5      | 8.33%   |
| Samsung Electronics | 4         | 4      | 6.67%   |
| Hitachi             | 4         | 4      | 6.67%   |
| MAXTOR              | 1         | 1      | 1.67%   |
| HGST                | 1         | 2      | 1.67%   |
| Fujitsu             | 1         | 1      | 1.67%   |
| ASMT                | 1         | 2      | 1.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 56        | 66     | 86.15%  |
| SSD  | 9         | 9      | 13.85%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 215       | 365    | 46.94%  |
| Detected | 180       | 364    | 39.3%   |
| Malfunc  | 63        | 75     | 13.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 290       | 60.8%   |
| AMD                              | 79        | 16.56%  |
| Samsung Electronics              | 21        | 4.4%    |
| Sandisk                          | 13        | 2.73%   |
| Marvell Technology Group         | 9         | 1.89%   |
| ASMedia Technology               | 9         | 1.89%   |
| SK Hynix                         | 8         | 1.68%   |
| Silicon Motion                   | 7         | 1.47%   |
| Nvidia                           | 6         | 1.26%   |
| Kingston Technology Company      | 5         | 1.05%   |
| Phison Electronics               | 4         | 0.84%   |
| KIOXIA                           | 4         | 0.84%   |
| Toshiba America Info Systems     | 3         | 0.63%   |
| Micron/Crucial Technology        | 3         | 0.63%   |
| JMicron Technology               | 3         | 0.63%   |
| Union Memory (Shenzhen)          | 2         | 0.42%   |
| Silicon Integrated Systems [SiS] | 2         | 0.42%   |
| LSI Logic / Symbios Logic        | 2         | 0.42%   |
| Hewlett-Packard                  | 2         | 0.42%   |
| VIA Technologies                 | 1         | 0.21%   |
| Solid State Storage Technology   | 1         | 0.21%   |
| Realtek Semiconductor            | 1         | 0.21%   |
| Micron Technology                | 1         | 0.21%   |
| Integrated Technology Express    | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 46        | 8%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25        | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 22        | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 22        | 3.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17        | 2.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17        | 2.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 16        | 2.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 15        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 2.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14        | 2.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 2.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13        | 2.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12        | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11        | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11        | 1.91%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9         | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 7         | 1.22%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 1.22%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 6         | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.04%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6         | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 1.04%   |
| Intel SSD 660P Series                                                                   | 5         | 0.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 5         | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 5         | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 5         | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 5         | 0.87%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 4         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 0.7%    |
| Nvidia MCP61 SATA Controller                                                            | 4         | 0.7%    |
| KIOXIA Non-Volatile memory controller                                                   | 4         | 0.7%    |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.7%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 4         | 0.7%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3         | 0.52%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.52%   |
| Nvidia MCP61 IDE                                                                        | 3         | 0.52%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.52%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 0.52%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 0.52%   |
| AMD FCH SATA Controller D                                                               | 3         | 0.52%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 2         | 0.35%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.35%   |
| SK Hynix BC511                                                                          | 2         | 0.35%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 2         | 0.35%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 0.35%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.35%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.35%   |
| Sandisk PC SN520 NVMe SSD                                                               | 2         | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 309       | 62.55%  |
| NVMe | 78        | 15.79%  |
| IDE  | 76        | 15.38%  |
| RAID | 27        | 5.47%   |
| SAS  | 4         | 0.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 316       | 74%     |
| AMD    | 88        | 20.61%  |
| ARM    | 23        | 5.39%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 22        | 5.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 9         | 2.11%   |
| AMD Phenom II X4 B97 Processor                | 7         | 1.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.17%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 5         | 1.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.94%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.94%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 0.94%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 4         | 0.94%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 0.94%   |
| AMD FX-8350 Eight-Core Processor              | 4         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.7%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 0.7%    |
| Intel Core i7-3930K CPU @ 3.20GHz             | 3         | 0.7%    |
| Intel Core i7-3770K CPU @ 3.50GHz             | 3         | 0.7%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.7%    |
| Intel Core i5-3570 CPU @ 3.40GHz              | 3         | 0.7%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.7%    |
| Intel Core i5-2500 CPU @ 3.30GHz              | 3         | 0.7%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.7%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 3         | 0.7%    |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 3         | 0.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.7%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 0.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.7%    |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 2         | 0.47%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.47%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 0.47%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 2         | 0.47%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.47%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.47%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 2         | 0.47%   |
| Intel Core i7-4790S CPU @ 3.20GHz             | 2         | 0.47%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.47%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 2         | 0.47%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.47%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.47%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.47%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.47%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.47%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.47%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.47%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.47%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.47%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 0.47%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.47%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.47%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.47%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.47%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 2         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 93        | 21.78%  |
| Intel Core i7                  | 81        | 18.97%  |
| Intel Core i3                  | 40        | 9.37%   |
| Other                          | 29        | 6.79%   |
| Intel Core 2 Duo               | 24        | 5.62%   |
| Intel Celeron                  | 15        | 3.51%   |
| AMD Ryzen 5                    | 15        | 3.51%   |
| Intel Pentium                  | 13        | 3.04%   |
| AMD Ryzen 7                    | 13        | 3.04%   |
| Intel Xeon                     | 12        | 2.81%   |
| AMD FX                         | 10        | 2.34%   |
| Intel Core 2 Quad              | 8         | 1.87%   |
| AMD Phenom II X4               | 8         | 1.87%   |
| AMD Athlon II X2               | 6         | 1.41%   |
| Intel Pentium Dual-Core        | 5         | 1.17%   |
| Intel Atom                     | 4         | 0.94%   |
| AMD Ryzen 9                    | 4         | 0.94%   |
| AMD Ryzen 3                    | 4         | 0.94%   |
| AMD A6                         | 4         | 0.94%   |
| Intel Core 2                   | 3         | 0.7%    |
| AMD Athlon                     | 3         | 0.7%    |
| AMD A4                         | 3         | 0.7%    |
| Intel Pentium Silver           | 2         | 0.47%   |
| Intel Pentium Dual             | 2         | 0.47%   |
| Intel Pentium D                | 2         | 0.47%   |
| Intel Core m3                  | 2         | 0.47%   |
| AMD Ryzen Threadripper         | 2         | 0.47%   |
| AMD A8                         | 2         | 0.47%   |
| Intel Xeon Silver              | 1         | 0.23%   |
| Intel Pentium 4                | 1         | 0.23%   |
| Intel Genuine                  | 1         | 0.23%   |
| Intel Core M                   | 1         | 0.23%   |
| Intel Core i9                  | 1         | 0.23%   |
| Intel Core 2 Extreme           | 1         | 0.23%   |
| Intel Celeron Dual-Core        | 1         | 0.23%   |
| ARM BCM                        | 1         | 0.23%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.23%   |
| AMD Turion II Neo              | 1         | 0.23%   |
| AMD Ryzen 7 PRO                | 1         | 0.23%   |
| AMD Ryzen 5 PRO                | 1         | 0.23%   |
| AMD Ryzen 3 PRO                | 1         | 0.23%   |
| AMD Phenom II X6               | 1         | 0.23%   |
| AMD Phenom II                  | 1         | 0.23%   |
| AMD E                          | 1         | 0.23%   |
| AMD Athlon X2                  | 1         | 0.23%   |
| AMD Athlon 64 X2               | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 190       | 44.5%   |
| 2      | 176       | 41.22%  |
| 6      | 29        | 6.79%   |
| 8      | 13        | 3.04%   |
| 16     | 5         | 1.17%   |
| 12     | 4         | 0.94%   |
| 1      | 4         | 0.94%   |
| 3      | 3         | 0.7%    |
| 24     | 2         | 0.47%   |
| 10     | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 421       | 98.59%  |
| 2      | 6         | 1.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 240       | 56.07%  |
| 1      | 188       | 43.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 408       | 95.33%  |
| Unknown        | 19        | 4.44%   |
| 64-bit         | 1         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 13.72%  |
| 0x306a9    | 44        | 10.23%  |
| 0x206a7    | 41        | 9.53%   |
| 0x306c3    | 24        | 5.58%   |
| 0x1067a    | 21        | 4.88%   |
| 0x010000c8 | 12        | 2.79%   |
| 0x806ec    | 11        | 2.56%   |
| 0x906ea    | 10        | 2.33%   |
| 0x306d4    | 10        | 2.33%   |
| 0x906e9    | 7         | 1.63%   |
| 0x806ea    | 7         | 1.63%   |
| 0x806e9    | 7         | 1.63%   |
| 0x6fd      | 7         | 1.63%   |
| 0x40651    | 7         | 1.63%   |
| 0x20655    | 7         | 1.63%   |
| 0x6fb      | 6         | 1.4%    |
| 0x08701021 | 6         | 1.4%    |
| 0x06000852 | 6         | 1.4%    |
| 0x506e3    | 5         | 1.16%   |
| 0x406e3    | 5         | 1.16%   |
| 0x406c4    | 5         | 1.16%   |
| 0x30678    | 5         | 1.16%   |
| 0x20652    | 5         | 1.16%   |
| 0x106e5    | 5         | 1.16%   |
| 0x10676    | 5         | 1.16%   |
| 0x08701013 | 5         | 1.16%   |
| 0x08600106 | 5         | 1.16%   |
| 0x08108102 | 5         | 1.16%   |
| 0x06006705 | 5         | 1.16%   |
| 0x706a1    | 4         | 0.93%   |
| 0x206d7    | 4         | 0.93%   |
| 0x0800820d | 4         | 0.93%   |
| 0xa0653    | 3         | 0.7%    |
| 0x806c1    | 3         | 0.7%    |
| 0x706e5    | 3         | 0.7%    |
| 0x6f6      | 3         | 0.7%    |
| 0x08108109 | 3         | 0.7%    |
| 0x08101016 | 3         | 0.7%    |
| 0x0810100b | 3         | 0.7%    |
| 0xa0660    | 2         | 0.47%   |
| 0x906ed    | 2         | 0.47%   |
| 0x906eb    | 2         | 0.47%   |
| 0x6fa      | 2         | 0.47%   |
| 0x506c9    | 2         | 0.47%   |
| 0x406c3    | 2         | 0.47%   |
| 0x306f2    | 2         | 0.47%   |
| 0x30673    | 2         | 0.47%   |
| 0x106a5    | 2         | 0.47%   |
| 0x02000032 | 2         | 0.47%   |
| 0xf62      | 1         | 0.23%   |
| 0xf47      | 1         | 0.23%   |
| 0xf43      | 1         | 0.23%   |
| 0x906ec    | 1         | 0.23%   |
| 0x706a8    | 1         | 0.23%   |
| 0x50657    | 1         | 0.23%   |
| 0x306e4    | 1         | 0.23%   |
| 0x206d6    | 1         | 0.23%   |
| 0x206c2    | 1         | 0.23%   |
| 0x10677    | 1         | 0.23%   |
| 0x0a201016 | 1         | 0.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 54        | 12.65%  |
| SandyBridge     | 50        | 11.71%  |
| IvyBridge       | 47        | 11.01%  |
| Haswell         | 38        | 8.9%    |
| Penryn          | 28        | 6.56%   |
| Unknown         | 23        | 5.39%   |
| Zen 2           | 18        | 4.22%   |
| K10             | 18        | 4.22%   |
| Core            | 18        | 4.22%   |
| Silvermont      | 14        | 3.28%   |
| Westmere        | 13        | 3.04%   |
| Skylake         | 13        | 3.04%   |
| Broadwell       | 13        | 3.04%   |
| Zen+            | 12        | 2.81%   |
| Zen             | 11        | 2.58%   |
| Piledriver      | 11        | 2.58%   |
| Nehalem         | 7         | 1.64%   |
| Excavator       | 7         | 1.64%   |
| Goldmont plus   | 5         | 1.17%   |
| CometLake       | 5         | 1.17%   |
| TigerLake       | 3         | 0.7%    |
| Puma            | 3         | 0.7%    |
| NetBurst        | 3         | 0.7%    |
| IceLake         | 3         | 0.7%    |
| Zen 3           | 2         | 0.47%   |
| K8 & K10 hybrid | 2         | 0.47%   |
| Goldmont        | 2         | 0.47%   |
| K8 Hammer       | 1         | 0.23%   |
| Jaguar          | 1         | 0.23%   |
| Bulldozer       | 1         | 0.23%   |
| Bobcat          | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 242       | 52.27%  |
| Nvidia                           | 109       | 23.54%  |
| AMD                              | 108       | 23.33%  |
| ASPEED Technology                | 2         | 0.43%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Matrox Electronics Systems       | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 35        | 7.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 4.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 3.18%   |
| Intel HD Graphics 5500                                                                   | 12        | 2.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.91%   |
| AMD RS880 [Radeon HD 4200]                                                               | 9         | 1.91%   |
| AMD Picasso                                                                              | 9         | 1.91%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.48%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6         | 1.27%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.27%   |
| AMD Renoir                                                                               | 6         | 1.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.06%   |
| Intel HD Graphics 630                                                                    | 5         | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.85%   |
| Intel HD Graphics 530                                                                    | 4         | 0.85%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 0.85%   |
| AMD RS780L [Radeon 3000]                                                                 | 4         | 0.85%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 4         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.64%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.64%   |
| Intel HD Graphics 620                                                                    | 3         | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.64%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.64%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 0.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.64%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.64%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 3         | 0.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 0.64%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.42%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.42%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.42%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2         | 0.42%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.42%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.42%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.42%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 2         | 0.42%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.42%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 2         | 0.42%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 0.42%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                                       | 2         | 0.42%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.42%   |
| Intel HD Graphics 500                                                                    | 2         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 188       | 43.93%  |
| 1 x AMD         | 90        | 21.03%  |
| 1 x Nvidia      | 67        | 15.65%  |
| Intel + Nvidia  | 39        | 9.11%   |
| Other           | 23        | 5.37%   |
| Intel + AMD     | 12        | 2.8%    |
| 2 x AMD         | 4         | 0.93%   |
| 2 x Nvidia      | 1         | 0.23%   |
| 1 x SiS         | 1         | 0.23%   |
| Nvidia + ASPEED | 1         | 0.23%   |
| 1 x Matrox      | 1         | 0.23%   |
| 1 x ASPEED      | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 322       | 74.88%  |
| Proprietary | 75        | 17.44%  |
| Unknown     | 33        | 7.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 246       | 57.21%  |
| 0.01-0.5   | 50        | 11.63%  |
| 1.01-2.0   | 49        | 11.4%   |
| 0.51-1.0   | 37        | 8.6%    |
| 3.01-4.0   | 25        | 5.81%   |
| 7.01-8.0   | 14        | 3.26%   |
| 5.01-6.0   | 5         | 1.16%   |
| 2.01-3.0   | 3         | 0.7%    |
| 16.01-24.0 | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 74        | 16.55%  |
| Samsung Electronics     | 64        | 14.32%  |
| AU Optronics            | 54        | 12.08%  |
| LG Display              | 40        | 8.95%   |
| Chimei Innolux          | 32        | 7.16%   |
| Goldstar                | 22        | 4.92%   |
| BOE                     | 19        | 4.25%   |
| Philips                 | 15        | 3.36%   |
| BenQ                    | 14        | 3.13%   |
| Acer                    | 10        | 2.24%   |
| Hewlett-Packard         | 9         | 2.01%   |
| Ancor Communications    | 9         | 2.01%   |
| AOC                     | 7         | 1.57%   |
| Unknown                 | 6         | 1.34%   |
| PANDA                   | 6         | 1.34%   |
| Chi Mei Optoelectronics | 6         | 1.34%   |
| Lenovo                  | 5         | 1.12%   |
| LG Philips              | 4         | 0.89%   |
| Vizio                   | 3         | 0.67%   |
| Sharp                   | 3         | 0.67%   |
| Iiyama                  | 3         | 0.67%   |
| Apple                   | 3         | 0.67%   |
| Vestel Elektronik       | 2         | 0.45%   |
| Toshiba                 | 2         | 0.45%   |
| Sony                    | 2         | 0.45%   |
| NEC Computers           | 2         | 0.45%   |
| InnoLux Display         | 2         | 0.45%   |
| HannStar                | 2         | 0.45%   |
| Gateway                 | 2         | 0.45%   |
| Belinea                 | 2         | 0.45%   |
| VIZ                     | 1         | 0.22%   |
| ViewSonic               | 1         | 0.22%   |
| Targa                   | 1         | 0.22%   |
| Seiko/Epson             | 1         | 0.22%   |
| Sceptre Tech            | 1         | 0.22%   |
| Sceptre                 | 1         | 0.22%   |
| Packard Bell            | 1         | 0.22%   |
| Onkyo                   | 1         | 0.22%   |
| MS_ Nvidia              | 1         | 0.22%   |
| MStar                   | 1         | 0.22%   |
| MiTAC                   | 1         | 0.22%   |
| Medion                  | 1         | 0.22%   |
| LGD                     | 1         | 0.22%   |
| LG Electronics          | 1         | 0.22%   |
| ITE                     | 1         | 0.22%   |
| Insignia                | 1         | 0.22%   |
| InfoVision              | 1         | 0.22%   |
| GDH                     | 1         | 0.22%   |
| Fujitsu Siemens         | 1         | 0.22%   |
| Element                 | 1         | 0.22%   |
| Eizo                    | 1         | 0.22%   |
| Daewoo                  | 1         | 0.22%   |
| Compal                  | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                      | 31        | 6.64%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 5         | 1.07%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                      | 5         | 1.07%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 5         | 1.07%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 4         | 0.86%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 3         | 0.64%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                       | 3         | 0.64%   |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                      | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch          | 3         | 0.64%   |
| Vizio VO320E VIZ0035 1366x768 700x390mm 31.5-inch                      | 2         | 0.43%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 2         | 0.43%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch   | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch   | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                      | 2         | 0.43%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 600x340mm 27.2-inch                | 2         | 0.43%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 2         | 0.43%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch            | 2         | 0.43%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 2         | 0.43%   |
| Goldstar W2253 GSM56DB 1920x1080 477x268mm 21.5-inch                   | 2         | 0.43%   |
| Goldstar E2340 GSM57A6 1920x1080 510x290mm 23.1-inch                   | 2         | 0.43%   |
| Goldstar 23LC1R GSM5617 1360x768 930x523mm 42.0-inch                   | 2         | 0.43%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                      | 2         | 0.43%   |
| Dell E1709W DELD022 1440x900 370x230mm 17.2-inch                       | 2         | 0.43%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                      | 2         | 0.43%   |
| Dell 2007FP DELA020 1600x1200 367x275mm 18.1-inch                      | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch       | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch        | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch       | 2         | 0.43%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                   | 2         | 0.43%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                  | 2         | 0.43%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 0.43%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 2         | 0.43%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch          | 2         | 0.43%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 2         | 0.43%   |
| AU Optronics LCD Monitor AUO18D4 1280x800 216x135mm 10.0-inch          | 2         | 0.43%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 2         | 0.43%   |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                    | 1         | 0.21%   |
| VIZ LCD Monitor E322VL 1920x1080                                       | 1         | 0.21%   |
| ViewSonic VX1935wm VSC2A1E 1440x900 408x255mm 18.9-inch                | 1         | 0.21%   |
| Unknown LCD Monitor Sony SDM-X82 1280x1024                             | 1         | 0.21%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1         | 0.21%   |
| Unknown LCD Monitor SAMSUNG 1360x768                                   | 1         | 0.21%   |
| Unknown LCD Monitor FormacTFT2010 1600x1200                            | 1         | 0.21%   |
| Unknown LCD Monitor ELE E4SW5017RKU                                    | 1         | 0.21%   |
| Unknown LCD Monitor CHHWJT 1920x1080                                   | 1         | 0.21%   |
| Toshiba TV TSB2017 3840x2160                                           | 1         | 0.21%   |
| Toshiba 49FHD_LCD_TV TSB3700 1920x1080 1360x768mm 61.5-inch            | 1         | 0.21%   |
| Targa LCD Monitor LCDTV16                                              | 1         | 0.21%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 531x299mm 24.0-inch  | 1         | 0.21%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                          | 1         | 0.21%   |
| Sharp LCD SHP4200 1920x1080 410x230mm 18.5-inch                        | 1         | 0.21%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                | 1         | 0.21%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.21%   |
| Seiko/Epson LCD Monitor 1440x900                                       | 1         | 0.21%   |
| Sceptre Tech Sceptre X24WG SPT2401 1920x1200 518x324mm 24.1-inch       | 1         | 0.21%   |
| Sceptre Tech Sceptre T27 SPT0AD7 1920x1080 600x330mm 27.0-inch         | 1         | 0.21%   |
| Sceptre LCD Monitor X24WG 3840x1200                                    | 1         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 155       | 35.71%  |
| 1366x768 (WXGA)    | 89        | 20.51%  |
| 1280x1024 (SXGA)   | 47        | 10.83%  |
| 3840x2160 (4K)     | 23        | 5.3%    |
| 1600x900 (HD+)     | 23        | 5.3%    |
| 1680x1050 (WSXGA+) | 15        | 3.46%   |
| 1440x900 (WXGA+)   | 14        | 3.23%   |
| 1280x800 (WXGA)    | 13        | 3%      |
| 2560x1440 (QHD)    | 11        | 2.53%   |
| 1920x1200 (WUXGA)  | 8         | 1.84%   |
| 1360x768           | 8         | 1.84%   |
| Unknown            | 6         | 1.38%   |
| 1600x1200          | 4         | 0.92%   |
| 3440x1440          | 3         | 0.69%   |
| 3200x1800 (QHD+)   | 2         | 0.46%   |
| 5040x1050          | 1         | 0.23%   |
| 4240x1440          | 1         | 0.23%   |
| 3840x1200          | 1         | 0.23%   |
| 3840x1080          | 1         | 0.23%   |
| 3000x1920          | 1         | 0.23%   |
| 2640x1024          | 1         | 0.23%   |
| 2560x1600          | 1         | 0.23%   |
| 2160x1440          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |
| 1680x945           | 1         | 0.23%   |
| 1400x1050          | 1         | 0.23%   |
| 1152x864           | 1         | 0.23%   |
| 1024x768 (XGA)     | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 98        | 21.83%  |
| 17      | 62        | 13.81%  |
| 13      | 34        | 7.57%   |
| 14      | 33        | 7.35%   |
| Unknown | 33        | 7.35%   |
| 24      | 26        | 5.79%   |
| 23      | 26        | 5.79%   |
| 21      | 23        | 5.12%   |
| 27      | 18        | 4.01%   |
| 18      | 15        | 3.34%   |
| 22      | 12        | 2.67%   |
| 19      | 10        | 2.23%   |
| 12      | 9         | 2%      |
| 84      | 6         | 1.34%   |
| 11      | 6         | 1.34%   |
| 31      | 5         | 1.11%   |
| 20      | 5         | 1.11%   |
| 10      | 4         | 0.89%   |
| 52      | 3         | 0.67%   |
| 40      | 3         | 0.67%   |
| 72      | 2         | 0.45%   |
| 42      | 2         | 0.45%   |
| 36      | 2         | 0.45%   |
| 34      | 2         | 0.45%   |
| 33      | 2         | 0.45%   |
| 32      | 2         | 0.45%   |
| 49      | 1         | 0.22%   |
| 48      | 1         | 0.22%   |
| 46      | 1         | 0.22%   |
| 29      | 1         | 0.22%   |
| 26      | 1         | 0.22%   |
| 8       | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 186       | 41.99%  |
| 501-600     | 65        | 14.67%  |
| 401-500     | 60        | 13.54%  |
| 201-300     | 33        | 7.45%   |
| Unknown     | 33        | 7.45%   |
| 351-400     | 30        | 6.77%   |
| 701-800     | 8         | 1.81%   |
| 601-700     | 8         | 1.81%   |
| 1501-2000   | 8         | 1.81%   |
| 1001-1500   | 6         | 1.35%   |
| 801-900     | 3         | 0.68%   |
| 901-1000    | 2         | 0.45%   |
| 101-200     | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 286       | 67.77%  |
| 16/10   | 49        | 11.61%  |
| 5/4     | 43        | 10.19%  |
| Unknown | 27        | 6.4%    |
| 4/3     | 7         | 1.66%   |
| 3/2     | 6         | 1.42%   |
| 21/9    | 2         | 0.47%   |
| 1.96    | 1         | 0.24%   |
| 0.62    | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 94        | 21.03%  |
| 201-250        | 69        | 15.44%  |
| 81-90          | 54        | 12.08%  |
| 141-150        | 52        | 11.63%  |
| Unknown        | 33        | 7.38%   |
| 151-200        | 23        | 5.15%   |
| 301-350        | 19        | 4.25%   |
| 121-130        | 15        | 3.36%   |
| 71-80          | 13        | 2.91%   |
| More than 1000 | 12        | 2.68%   |
| 251-300        | 12        | 2.68%   |
| 351-500        | 11        | 2.46%   |
| 61-70          | 9         | 2.01%   |
| 501-1000       | 9         | 2.01%   |
| 131-140        | 7         | 1.57%   |
| 51-60          | 6         | 1.34%   |
| 41-50          | 4         | 0.89%   |
| 111-120        | 3         | 0.67%   |
| 1-40           | 1         | 0.22%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 169       | 38.85%  |
| 101-120       | 107       | 24.6%   |
| 121-160       | 93        | 21.38%  |
| Unknown       | 33        | 7.59%   |
| 161-240       | 17        | 3.91%   |
| 1-50          | 10        | 2.3%    |
| More than 240 | 6         | 1.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 359       | 83.49%  |
| 2     | 51        | 11.86%  |
| 0     | 14        | 3.26%   |
| 3     | 6         | 1.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 205       | 34.51%  |
| Intel                             | 199       | 33.5%   |
| Qualcomm Atheros                  | 67        | 11.28%  |
| Broadcom                          | 41        | 6.9%    |
| Broadcom Limited                  | 10        | 1.68%   |
| Ralink                            | 8         | 1.35%   |
| Ralink Technology                 | 7         | 1.18%   |
| Marvell Technology Group          | 6         | 1.01%   |
| TP-Link                           | 5         | 0.84%   |
| Qualcomm Atheros Communications   | 5         | 0.84%   |
| Nvidia                            | 5         | 0.84%   |
| Xiaomi                            | 3         | 0.51%   |
| ASUSTek Computer                  | 3         | 0.51%   |
| Aquantia                          | 3         | 0.51%   |
| Standard Microsystems             | 2         | 0.34%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.34%   |
| Sierra Wireless                   | 2         | 0.34%   |
| Linksys                           | 2         | 0.34%   |
| ASIX Electronics                  | 2         | 0.34%   |
| ZyDAS                             | 1         | 0.17%   |
| Tenda                             | 1         | 0.17%   |
| Sitecom Europe                    | 1         | 0.17%   |
| Samsung Electronics               | 1         | 0.17%   |
| Realtek                           | 1         | 0.17%   |
| QLogic                            | 1         | 0.17%   |
| NetGear                           | 1         | 0.17%   |
| Netchip Technology                | 1         | 0.17%   |
| Microsoft                         | 1         | 0.17%   |
| MediaTek                          | 1         | 0.17%   |
| Lenovo                            | 1         | 0.17%   |
| Hewlett-Packard                   | 1         | 0.17%   |
| Fibocom                           | 1         | 0.17%   |
| Ericsson Business Mobile Networks | 1         | 0.17%   |
| Edimax Technology                 | 1         | 0.17%   |
| Dell                              | 1         | 0.17%   |
| D-Link System                     | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 146       | 21.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 5.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 4.62%   |
| Intel Wireless 7260                                               | 14        | 2.02%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 13        | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.59%   |
| Intel Wireless 3165                                               | 11        | 1.59%   |
| Intel Wireless 7265                                               | 10        | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 10        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.3%    |
| Intel I211 Gigabit Network Connection                             | 9         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.16%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8         | 1.16%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.58%   |
| Nvidia MCP61 Ethernet                                             | 4         | 0.58%   |
| Intel Wireless-AC 9260                                            | 4         | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.58%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 3         | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.43%   |
| Realtek 802.11ac NIC                                              | 3         | 0.43%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.43%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 0.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.43%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.43%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.43%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 3         | 0.43%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.43%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.43%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.43%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.43%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 3         | 0.43%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 3         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 128       | 44.14%  |
| Qualcomm Atheros                | 51        | 17.59%  |
| Realtek Semiconductor           | 45        | 15.52%  |
| Broadcom                        | 17        | 5.86%   |
| Ralink                          | 8         | 2.76%   |
| Ralink Technology               | 7         | 2.41%   |
| Broadcom Limited                | 7         | 2.41%   |
| TP-Link                         | 5         | 1.72%   |
| Qualcomm Atheros Communications | 5         | 1.72%   |
| ASUSTek Computer                | 3         | 1.03%   |
| Linksys                         | 2         | 0.69%   |
| ZyDAS                           | 1         | 0.34%   |
| Xiaomi                          | 1         | 0.34%   |
| Tenda                           | 1         | 0.34%   |
| Sitecom Europe                  | 1         | 0.34%   |
| Realtek                         | 1         | 0.34%   |
| NetGear                         | 1         | 0.34%   |
| Microsoft                       | 1         | 0.34%   |
| MediaTek                        | 1         | 0.34%   |
| Hewlett-Packard                 | 1         | 0.34%   |
| Fibocom                         | 1         | 0.34%   |
| Edimax Technology               | 1         | 0.34%   |
| Dell                            | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                                  | 14        | 4.83%   |
| Intel Wi-Fi 6 AX200                                                                  | 13        | 4.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 13        | 4.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 12        | 4.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 11        | 3.79%   |
| Intel Wireless 3165                                                                  | 11        | 3.79%   |
| Intel Wireless 7265                                                                  | 10        | 3.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                  | 10        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 9         | 3.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 8         | 2.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 8         | 2.76%   |
| Intel Wireless 8265 / 8275                                                           | 7         | 2.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 6         | 2.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 5         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                    | 5         | 1.72%   |
| Intel Centrino Ultimate-N 6300                                                       | 5         | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 5         | 1.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                      | 4         | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4         | 1.38%   |
| Intel Wireless-AC 9260                                                               | 4         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                             | 4         | 1.38%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 3         | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 3         | 1.03%   |
| Realtek 802.11ac NIC                                                                 | 3         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                                      | 3         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 3         | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 3         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 3         | 1.03%   |
| Intel Wi-Fi 6 AX201                                                                  | 3         | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                      | 3         | 1.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                                      | 3         | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 3         | 1.03%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                         | 3         | 1.03%   |
| Intel Centrino Advanced-N 6235                                                       | 3         | 1.03%   |
| Intel Centrino Advanced-N 6200                                                       | 3         | 1.03%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                           | 3         | 1.03%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                            | 3         | 1.03%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                      | 2         | 0.69%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2         | 0.69%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                      | 2         | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 2         | 0.69%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                             | 2         | 0.69%   |
| Ralink RT5370 Wireless Adapter                                                       | 2         | 0.69%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 2         | 0.69%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 2         | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 2         | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)              | 2         | 0.69%   |
| Intel Wireless 8260                                                                  | 2         | 0.69%   |
| Intel WiFi Link 5100                                                                 | 2         | 0.69%   |
| Broadcom BCM4321 802.11a/b/g/n                                                       | 2         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                                        | 2         | 0.69%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]                   | 2         | 0.69%   |
| ZyDAS ZD1211B 802.11g                                                                | 1         | 0.34%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                                    | 1         | 0.34%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                | 1         | 0.34%   |
| TP-Link 802.11n NIC                                                                  | 1         | 0.34%   |
| Tenda U12                                                                            | 1         | 0.34%   |
| Sitecom Europe 802.11n WLAN Adapter                                                  | 1         | 0.34%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                             | 1         | 0.34%   |
| Realtek RTL8723DE Wireless Network Adapter                                           | 1         | 0.34%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 192       | 48.85%  |
| Intel                            | 128       | 32.57%  |
| Broadcom                         | 24        | 6.11%   |
| Qualcomm Atheros                 | 17        | 4.33%   |
| Marvell Technology Group         | 6         | 1.53%   |
| Nvidia                           | 5         | 1.27%   |
| Broadcom Limited                 | 3         | 0.76%   |
| Aquantia                         | 3         | 0.76%   |
| Xiaomi                           | 2         | 0.51%   |
| Standard Microsystems            | 2         | 0.51%   |
| Silicon Integrated Systems [SiS] | 2         | 0.51%   |
| Sierra Wireless                  | 2         | 0.51%   |
| ASIX Electronics                 | 2         | 0.51%   |
| Samsung Electronics              | 1         | 0.25%   |
| QLogic                           | 1         | 0.25%   |
| Netchip Technology               | 1         | 0.25%   |
| Lenovo                           | 1         | 0.25%   |
| D-Link System                    | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 146       | 36.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 9.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 7.98%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 2.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 2.24%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.24%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8         | 2%      |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.5%    |
| Intel Ethernet Connection I217-V                                  | 5         | 1.25%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1%      |
| Nvidia MCP61 Ethernet                                             | 4         | 1%      |
| Intel Ethernet Connection I218-LM                                 | 4         | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1%      |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.75%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.75%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 3         | 0.75%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.5%    |
| Standard Microsystems SMSC9512/9514 Fast Ethernet Adapter         | 2         | 0.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.5%    |
| Sierra Wireless EM7345 4G LTE                                     | 2         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.5%    |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.5%    |
| Intel 82567V-4 Gigabit Network Connection                         | 2         | 0.5%    |
| Intel 82567V-2 Gigabit Network Connection                         | 2         | 0.5%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.5%    |
| Broadcom Limited NetLink BCM5787 Gigabit Ethernet PCI Express     | 2         | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.25%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.25%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.25%   |
| QLogic cLOM8214 1/10GbE Controller                                | 1         | 0.25%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.25%   |
| Netchip Linux-USB Ethernet/RNDIS Gadget                           | 1         | 0.25%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.25%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.25%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.25%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.25%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.25%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.25%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.25%   |
| Intel Ethernet Controller 10G X550T                               | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 375       | 57.6%   |
| WiFi     | 275       | 42.24%  |
| Modem    | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 272       | 52.51%  |
| WiFi     | 246       | 47.49%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 210       | 48.95%  |
| 1     | 184       | 42.89%  |
| 0     | 25        | 5.83%   |
| 3     | 7         | 1.63%   |
| 4     | 2         | 0.47%   |
| 6     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 398       | 92.77%  |
| Yes  | 31        | 7.23%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 44.24%  |
| Qualcomm Atheros Communications | 24        | 11.06%  |
| Broadcom                        | 22        | 10.14%  |
| Realtek Semiconductor           | 20        | 9.22%   |
| Cambridge Silicon Radio         | 18        | 8.29%   |
| IMC Networks                    | 9         | 4.15%   |
| Dell                            | 9         | 4.15%   |
| Lite-On Technology              | 7         | 3.23%   |
| Foxconn / Hon Hai               | 3         | 1.38%   |
| ASUSTek Computer                | 3         | 1.38%   |
| Apple                           | 3         | 1.38%   |
| Ralink Technology               | 1         | 0.46%   |
| Ralink                          | 1         | 0.46%   |
| Belkin Components               | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                 | 57        | 26.27%  |
| Intel Bluetooth wireless interface                     | 23        | 10.6%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 18        | 8.29%   |
| Realtek Bluetooth Radio                                | 11        | 5.07%   |
| Intel AX200 Bluetooth                                  | 11        | 5.07%   |
| Qualcomm Atheros  Bluetooth Device                     | 9         | 4.15%   |
| Realtek  Bluetooth 4.2 Adapter                         | 8         | 3.69%   |
| Qualcomm Atheros AR3011 Bluetooth                      | 7         | 3.23%   |
| Dell DW375 Bluetooth Module                            | 6         | 2.76%   |
| IMC Networks Bluetooth Device                          | 5         | 2.3%    |
| Qualcomm Atheros Bluetooth USB Host Controller         | 4         | 1.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 4         | 1.84%   |
| Lite-On Bluetooth Device                               | 4         | 1.84%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                   | 4         | 1.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 3         | 1.38%   |
| Broadcom HP Portable SoftSailing                       | 3         | 1.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                      | 3         | 1.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 3         | 1.38%   |
| Broadcom BCM2045B (BDC-2.1)                            | 3         | 1.38%   |
| Apple Bluetooth HCI                                    | 3         | 1.38%   |
| Lite-On Atheros AR3012 Bluetooth                       | 2         | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter       | 2         | 0.92%   |
| IMC Networks Bluetooth Radio                           | 2         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                     | 2         | 0.92%   |
| Dell Broadcom BCM20702A0 Bluetooth                     | 2         | 0.92%   |
| Broadcom BCM43142A0 Bluetooth 4.0                      | 2         | 0.92%   |
| Realtek 802.11n WLAN Adapter                           | 1         | 0.46%   |
| Ralink CSR BS8510                                      | 1         | 0.46%   |
| Ralink RT3290 Bluetooth                                | 1         | 0.46%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device           | 1         | 0.46%   |
| IMC Networks BCM20702A0                                | 1         | 0.46%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 0.46%   |
| Foxconn / Hon Hai BCM20702A0                           | 1         | 0.46%   |
| Dell Wireless 370 Bluetooth Mini-card                  | 1         | 0.46%   |
| Broadcom HP Portable Valentine                         | 1         | 0.46%   |
| Broadcom Bluetooth 3.0 Device                          | 1         | 0.46%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter       | 1         | 0.46%   |
| Broadcom BCM2045 Bluetooth                             | 1         | 0.46%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter  | 1         | 0.46%   |
| ASUS BT-270 Bluetooth Adapter                          | 1         | 0.46%   |
| ASUS Broadcom BCM20702A0 Bluetooth                     | 1         | 0.46%   |
| ASUS ASUS USB-BT500                                    | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 304       | 56.3%   |
| AMD                                            | 107       | 19.81%  |
| Nvidia                                         | 88        | 16.3%   |
| C-Media Electronics                            | 7         | 1.3%    |
| Logitech                                       | 3         | 0.56%   |
| Generalplus Technology                         | 3         | 0.56%   |
| Corsair                                        | 3         | 0.56%   |
| Silicon Integrated Systems [SiS]               | 2         | 0.37%   |
| Razer USA                                      | 2         | 0.37%   |
| Plantronics                                    | 2         | 0.37%   |
| Lenovo                                         | 2         | 0.37%   |
| Kingston Technology                            | 2         | 0.37%   |
| JMTek                                          | 2         | 0.37%   |
| Creative Labs                                  | 2         | 0.37%   |
| XMOS                                           | 1         | 0.19%   |
| Sony                                           | 1         | 0.19%   |
| Siemens Information and Communication Products | 1         | 0.19%   |
| Realtek Semiconductor                          | 1         | 0.19%   |
| Micro Star International                       | 1         | 0.19%   |
| Hewlett-Packard                                | 1         | 0.19%   |
| Focusrite-Novation                             | 1         | 0.19%   |
| FiiO Electronics Technology                    | 1         | 0.19%   |
| Creative Technology                            | 1         | 0.19%   |
| BEHRINGER International                        | 1         | 0.19%   |
| Alesis                                         | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 51        | 7.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 40        | 6.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 28        | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25        | 3.89%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 23        | 3.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 21        | 3.27%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 3.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18        | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 2.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 2.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 2.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 2.02%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 2.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 2.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 1.71%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 1.24%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 8         | 1.24%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 8         | 1.24%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.09%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 7         | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 1.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 6         | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 0.93%   |
| AMD High Definition Audio Controller                                                              | 6         | 0.93%   |
| AMD FCH Azalia Controller                                                                         | 6         | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 0.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 0.93%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6         | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.78%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 5         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 0.78%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 5         | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.62%   |
| Nvidia MCP61 High Definition Audio                                                                | 4         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.62%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 0.62%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.62%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.47%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 0.47%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.47%   |
| Intel Comet Lake PCH-V Smart Sound Technology Audio Controller                                    | 3         | 0.47%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.47%   |
| Generalplus Technology Usb Audio Device                                                           | 3         | 0.47%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 3         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 56        | 17.55%  |
| SK Hynix                                         | 50        | 15.67%  |
| Kingston                                         | 47        | 14.73%  |
| Unknown                                          | 45        | 14.11%  |
| Micron Technology                                | 25        | 7.84%   |
| Crucial                                          | 20        | 6.27%   |
| Corsair                                          | 12        | 3.76%   |
| Elpida                                           | 10        | 3.13%   |
| Smart                                            | 8         | 2.51%   |
| Nanya Technology                                 | 7         | 2.19%   |
| G.Skill                                          | 6         | 1.88%   |
| Teikon                                           | 4         | 1.25%   |
| Ramaxel Technology                               | 4         | 1.25%   |
| Patriot                                          | 4         | 1.25%   |
| A-DATA Technology                                | 4         | 1.25%   |
| Team                                             | 3         | 0.94%   |
| Unknown (ABCD)                                   | 2         | 0.63%   |
| GOODRAM                                          | 2         | 0.63%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.31%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.31%   |
| Unknown (00FFFFFFFFFFFFFF)                       | 1         | 0.31%   |
| Transcend                                        | 1         | 0.31%   |
| Qimonda                                          | 1         | 0.31%   |
| Netlist                                          | 1         | 0.31%   |
| GeIL                                             | 1         | 0.31%   |
| atermiter                                        | 1         | 0.31%   |
| ASint Technology                                 | 1         | 0.31%   |
| Apacer                                           | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 6         | 1.74%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                       | 5         | 1.45%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 1.16%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s            | 4         | 1.16%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s            | 3         | 0.87%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s              | 3         | 0.87%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 2         | 0.58%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 2         | 0.58%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 2         | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DRAM                               | 2         | 0.58%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s                        | 2         | 0.58%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 2         | 0.58%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                         | 2         | 0.58%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 2         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 0.58%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s               | 2         | 0.58%   |
| SK Hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s               | 2         | 0.58%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.58%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.58%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.58%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s           | 2         | 0.58%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.58%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.58%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 2         | 0.58%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM 1334MT/s                 | 2         | 0.58%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 2         | 0.58%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 0.58%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s               | 2         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.58%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s      | 2         | 0.58%   |
| Micron RAM MT52L1G32D4PG-093 8192MB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.58%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 2         | 0.58%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                        | 2         | 0.58%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Kingston RAM 99U5471-054.A00LF 8192MB DIMM DDR3 1600MT/s            | 2         | 0.58%   |
| Elpida RAM EBJ41EF8BCFA-DJ-F 4096MB DIMM DDR3 1333MT/s              | 2         | 0.58%   |
| Crucial RAM CT51264BF160BJ.M8F 4096MB SODIMM DDR3 1600MT/s          | 2         | 0.58%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s          | 2         | 0.58%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s                | 2         | 0.58%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8192MB SODIMM DDR4 2667MT/s             | 2         | 0.58%   |
| Unknown RAM Module 8192MB DIMM SDRAM                                | 1         | 0.29%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                        | 1         | 0.29%   |
| Unknown RAM Module 8192MB DIMM 667MT/s                              | 1         | 0.29%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                | 1         | 0.29%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 0.29%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 4096MB DIMM DDR3 667MT/s                         | 1         | 0.29%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                        | 1         | 0.29%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                              | 1         | 0.29%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                              | 1         | 0.29%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                                | 1         | 0.29%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.29%   |
| Unknown RAM Module 2048MB SODIMM DDR3                               | 1         | 0.29%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                       | 1         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 134       | 48.38%  |
| DDR4    | 84        | 30.32%  |
| DDR2    | 20        | 7.22%   |
| Unknown | 11        | 3.97%   |
| SDRAM   | 10        | 3.61%   |
| LPDDR4  | 7         | 2.53%   |
| LPDDR3  | 6         | 2.17%   |
| DDR     | 3         | 1.08%   |
| DRAM    | 2         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 143       | 52.57%  |
| DIMM         | 115       | 42.28%  |
| Row Of Chips | 12        | 4.41%   |
| Chip         | 2         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 106       | 35.45%  |
| 8192  | 85        | 28.43%  |
| 2048  | 61        | 20.4%   |
| 16384 | 26        | 8.7%    |
| 1024  | 10        | 3.34%   |
| 32768 | 9         | 3.01%   |
| 1536  | 1         | 0.33%   |
| 512   | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 74        | 24.83%  |
| 1333    | 41        | 13.76%  |
| 2667    | 40        | 13.42%  |
| 3200    | 24        | 8.05%   |
| 2400    | 17        | 5.7%    |
| 1334    | 17        | 5.7%    |
| 800     | 13        | 4.36%   |
| 667     | 12        | 4.03%   |
| 2133    | 10        | 3.36%   |
| Unknown | 7         | 2.35%   |
| 3266    | 6         | 2.01%   |
| 1067    | 6         | 2.01%   |
| 4199    | 4         | 1.34%   |
| 1066    | 4         | 1.34%   |
| 2666    | 3         | 1.01%   |
| 49926   | 2         | 0.67%   |
| 1867    | 2         | 0.67%   |
| 533     | 2         | 0.67%   |
| 400     | 2         | 0.67%   |
| 4267    | 1         | 0.34%   |
| 3866    | 1         | 0.34%   |
| 3733    | 1         | 0.34%   |
| 3600    | 1         | 0.34%   |
| 3500    | 1         | 0.34%   |
| 3400    | 1         | 0.34%   |
| 3100    | 1         | 0.34%   |
| 2473    | 1         | 0.34%   |
| 2048    | 1         | 0.34%   |
| 1400    | 1         | 0.34%   |
| 975     | 1         | 0.34%   |
| 266     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 7         | 38.89%  |
| Brother Industries     | 3         | 16.67%  |
| Seiko Epson            | 2         | 11.11%  |
| Canon                  | 2         | 11.11%  |
| Samsung Electronics    | 1         | 5.56%   |
| QinHeng Electronics    | 1         | 5.56%   |
| Panasonic (Matsushita) | 1         | 5.56%   |
| Bixolon                | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| HP LaserJet Professional P 1102w   | 2         | 10.53%  |
| Brother Printer                    | 2         | 10.53%  |
| Seiko Epson PX-105 Series          | 1         | 5.26%   |
| Seiko Epson Printer                | 1         | 5.26%   |
| Samsung M2020 Series               | 1         | 5.26%   |
| QinHeng CH340S                     | 1         | 5.26%   |
| Panasonic (Matsushita) KX-MB2130RU | 1         | 5.26%   |
| HP OfficeJet 6950                  | 1         | 5.26%   |
| HP LaserJet 1022                   | 1         | 5.26%   |
| HP Deskjet F4500 series            | 1         | 5.26%   |
| HP Deskjet 3050 J610 series        | 1         | 5.26%   |
| HP DeskJet 2130 series             | 1         | 5.26%   |
| Canon PIXMA MG2500 Series          | 1         | 5.26%   |
| Canon Pixma iP4500 Printer         | 1         | 5.26%   |
| Brother HL-3170CDW series          | 1         | 5.26%   |
| Brother DCP-7055 scanner/printer   | 1         | 5.26%   |
| Bixolon Printer                    | 1         | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Canon       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 33.33%  |
| Seiko Epson ES-D400 [GT-S80]                     | 1         | 33.33%  |
| Canon CanoScan LiDE 210                          | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 25.93%  |
| Acer                                   | 19        | 8.8%    |
| Microdia                               | 18        | 8.33%   |
| Sunplus Innovation Technology          | 17        | 7.87%   |
| IMC Networks                           | 15        | 6.94%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 5.09%   |
| Logitech                               | 10        | 4.63%   |
| Realtek Semiconductor                  | 9         | 4.17%   |
| Ricoh                                  | 8         | 3.7%    |
| Quanta                                 | 8         | 3.7%    |
| Syntek                                 | 5         | 2.31%   |
| Silicon Motion                         | 5         | 2.31%   |
| Lite-On Technology                     | 5         | 2.31%   |
| Apple                                  | 5         | 2.31%   |
| Suyin                                  | 4         | 1.85%   |
| Microsoft                              | 2         | 0.93%   |
| KYE Systems (Mouse Systems)            | 2         | 0.93%   |
| Creative Technology                    | 2         | 0.93%   |
| Aveo Technology                        | 2         | 0.93%   |
| Z-Star Microelectronics                | 1         | 0.46%   |
| Y Media                                | 1         | 0.46%   |
| Sweex                                  | 1         | 0.46%   |
| Sunplus Technology                     | 1         | 0.46%   |
| Samsung Electronics                    | 1         | 0.46%   |
| Ruision                                | 1         | 0.46%   |
| Primax Electronics                     | 1         | 0.46%   |
| MacroSilicon                           | 1         | 0.46%   |
| Lenovo                                 | 1         | 0.46%   |
| DJKANA1BIEMDD7                         | 1         | 0.46%   |
| Cubeternet                             | 1         | 0.46%   |
| ARC International                      | 1         | 0.46%   |
| Alcor Micro                            | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony integrated camera                               | 16        | 7.34%   |
| Sunplus Integrated_Webcam_HD                            | 9         | 4.13%   |
| Acer Integrated Camera                                  | 6         | 2.75%   |
| Acer BisonCam, NB Pro                                   | 6         | 2.75%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 2.29%   |
| Ricoh HD Webcam                                         | 4         | 1.83%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 4         | 1.83%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 3         | 1.38%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.38%   |
| Microdia Integrated Webcam                              | 3         | 1.38%   |
| Lite-On HP HD Camera                                    | 3         | 1.38%   |
| IMC Networks Integrated Camera                          | 3         | 1.38%   |
| Chicony USB2.0 VGA UVC WebCam                           | 3         | 1.38%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 3         | 1.38%   |
| Apple iPhone5/5C/5S/6                                   | 3         | 1.38%   |
| Syntek Integrated Camera                                | 2         | 0.92%   |
| Syntek EasyCamera                                       | 2         | 0.92%   |
| Silicon Motion WebCam SC-13HDL11939N                    | 2         | 0.92%   |
| Ricoh Sony Visual Communication Camera                  | 2         | 0.92%   |
| Ricoh Laptop_Integrated_Webcam_FHD                      | 2         | 0.92%   |
| Realtek USB Camera                                      | 2         | 0.92%   |
| Quanta VGA WebCam                                       | 2         | 0.92%   |
| Quanta Laptop_Integrated_Webcam_2HDM                    | 2         | 0.92%   |
| Quanta HD User Facing                                   | 2         | 0.92%   |
| Microsoft LifeCam HD-3000                               | 2         | 0.92%   |
| Microdia Laptop_Integrated_Webcam_2M                    | 2         | 0.92%   |
| Microdia Integrated_Webcam_HD                           | 2         | 0.92%   |
| Microdia Dell Integrated HD Webcam                      | 2         | 0.92%   |
| Logitech Webcam C270                                    | 2         | 0.92%   |
| Logitech QuickCam Pro 9000                              | 2         | 0.92%   |
| IMC Networks XHC Camera                                 | 2         | 0.92%   |
| Chicony USB2.0 UVC WebCam                               | 2         | 0.92%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 2         | 0.92%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 0.92%   |
| Chicony HP Webcam-101                                   | 2         | 0.92%   |
| Chicony HP HD Webcam [Fixed]                            | 2         | 0.92%   |
| Chicony HD WebCam (Acer)                                | 2         | 0.92%   |
| Chicony CNF9055 Toshiba Webcam                          | 2         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 2         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 2         | 0.92%   |
| Aveo UVC camera (Bresser microscope)                    | 2         | 0.92%   |
| Acer Lenovo EasyCamera                                  | 2         | 0.92%   |
| Z-Star Venus USB2.0 Camera                              | 1         | 0.46%   |
| Y Media USB Camera                                      | 1         | 0.46%   |
| Syntek USB Video Device                                 | 1         | 0.46%   |
| Sweex WC060 Series HD Webcam                            | 1         | 0.46%   |
| Suyin Sony Visual Communication Camera                  | 1         | 0.46%   |
| Suyin HP TrueVision HD Integrated Webcam                | 1         | 0.46%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.46%   |
| Suyin 1.3M HD WebCam                                    | 1         | 0.46%   |
| Sunplus HD Camera                                       | 1         | 0.46%   |
| Sunplus Integrated_Webcam_FHD                           | 1         | 0.46%   |
| Sunplus HP Universal Camera                             | 1         | 0.46%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.46%   |
| Sunplus HD WebCam                                       | 1         | 0.46%   |
| Sunplus Dell Integrated Webcam                          | 1         | 0.46%   |
| Silicon Motion WebCam SCB-1100N                         | 1         | 0.46%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 1         | 0.46%   |
| Silicon Motion 300k Pixel Camera                        | 1         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 41.67%  |
| Synaptics                  | 11        | 30.56%  |
| Shenzhen Goodix Technology | 4         | 11.11%  |
| Upek                       | 3         | 8.33%   |
| Elan Microelectronics      | 2         | 5.56%   |
| Focal-systems.Corp         | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 8.33%   |
| Validity Sensors VFS491                                    | 3         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 3         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 5.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 5.56%   |
| Elan ELAN:Fingerprint                                      | 2         | 5.56%   |
| Unknown                                                    | 2         | 5.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.78%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.78%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.78%   |
| Validity Sensors Synaptics WBDI                            | 1         | 2.78%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 2.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.78%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 2.78%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 20        | 60.61%  |
| Alcor Micro           | 5         | 15.15%  |
| Upek                  | 2         | 6.06%   |
| Lenovo                | 2         | 6.06%   |
| O2 Micro              | 1         | 3.03%   |
| Gemalto (was Gemplus) | 1         | 3.03%   |
| Chicony Electronics   | 1         | 3.03%   |
| Advanced Card Systems | 1         | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 30.3%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 21.21%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 15.15%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 6.06%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.06%   |
| Broadcom 58200                                                               | 2         | 6.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.03%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 3.03%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 3.03%   |
| Broadcom 5880                                                                | 1         | 3.03%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 334       | 76.96%  |
| 1     | 78        | 17.97%  |
| 2     | 18        | 4.15%   |
| 8     | 2         | 0.46%   |
| 4     | 1         | 0.23%   |
| 3     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 27.69%  |
| Chipcard                 | 31        | 23.85%  |
| Graphics card            | 22        | 16.92%  |
| Storage                  | 8         | 6.15%   |
| Net/wireless             | 7         | 5.38%   |
| Communication controller | 7         | 5.38%   |
| Unassigned class         | 3         | 2.31%   |
| Camera                   | 3         | 2.31%   |
| Bluetooth                | 3         | 2.31%   |
| Sound                    | 2         | 1.54%   |
| Network                  | 2         | 1.54%   |
| Multimedia controller    | 2         | 1.54%   |
| Tv card                  | 1         | 0.77%   |
| Storage/ata              | 1         | 0.77%   |
| Firewire controller      | 1         | 0.77%   |
| Card reader              | 1         | 0.77%   |

