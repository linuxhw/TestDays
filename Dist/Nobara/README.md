Nobara - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Nobara.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Nobara/Desktop/README.md) and [notebooks](/Dist/Nobara/Notebook/README.md).

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

Total: 419

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [15318beac5](https://linux-hardware.org/?probe=15318beac5) | Feb 27, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [a5496030e7](https://linux-hardware.org/?probe=a5496030e7) | Feb 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [92f1f7d3b5](https://linux-hardware.org/?probe=92f1f7d3b5) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [101d8d4577](https://linux-hardware.org/?probe=101d8d4577) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [802ba906a0](https://linux-hardware.org/?probe=802ba906a0) | Feb 23, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [b2ef9d5ede](https://linux-hardware.org/?probe=b2ef9d5ede) | Feb 21, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [2752a9660a](https://linux-hardware.org/?probe=2752a9660a) | Feb 19, 2023 |
| Dell          | G3 3590                     | Notebook    | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| HP            | ENVY 15                     | Notebook    | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e81d0741bb](https://linux-hardware.org/?probe=e81d0741bb) | Feb 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [dd63e968bd](https://linux-hardware.org/?probe=dd63e968bd) | Feb 17, 2023 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e486b2bb46](https://linux-hardware.org/?probe=e486b2bb46) | Feb 15, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [486f7258a6](https://linux-hardware.org/?probe=486f7258a6) | Feb 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [dc91c0e32b](https://linux-hardware.org/?probe=dc91c0e32b) | Feb 14, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [c3d08b4f2e](https://linux-hardware.org/?probe=c3d08b4f2e) | Feb 13, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b25d844a19](https://linux-hardware.org/?probe=b25d844a19) | Feb 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| HP            | 17E2                        | Mini pc     | [e99d3c0a69](https://linux-hardware.org/?probe=e99d3c0a69) | Feb 12, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| HP            | 17E2                        | Mini pc     | [ff80271dce](https://linux-hardware.org/?probe=ff80271dce) | Feb 11, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9b95bc446b](https://linux-hardware.org/?probe=9b95bc446b) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c4eb0b2a62](https://linux-hardware.org/?probe=c4eb0b2a62) | Feb 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [fdaab67fe9](https://linux-hardware.org/?probe=fdaab67fe9) | Feb 09, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| HP            | 834F                        | Desktop     | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| HP            | 8054                        | Desktop     | [36f5306e37](https://linux-hardware.org/?probe=36f5306e37) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | Notebook    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [95f5d0904e](https://linux-hardware.org/?probe=95f5d0904e) | Jan 26, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | Notebook    | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | Notebook    | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | Notebook    | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [bc95b86800](https://linux-hardware.org/?probe=bc95b86800) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3eb7e4f3cf](https://linux-hardware.org/?probe=3eb7e4f3cf) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4d52b408c2](https://linux-hardware.org/?probe=4d52b408c2) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| AZW           | S3                          | Mini pc     | [0e94de97c8](https://linux-hardware.org/?probe=0e94de97c8) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | 8054                        | Desktop     | [d4398dee29](https://linux-hardware.org/?probe=d4398dee29) | Jan 08, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c74a6daaaa](https://linux-hardware.org/?probe=c74a6daaaa) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| HP            | 1497                        | Desktop     | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [569f5cd751](https://linux-hardware.org/?probe=569f5cd751) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8c219aafe4](https://linux-hardware.org/?probe=8c219aafe4) | Jan 05, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b6bf9d074f](https://linux-hardware.org/?probe=b6bf9d074f) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [6c40dc7dd6](https://linux-hardware.org/?probe=6c40dc7dd6) | Jan 03, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6d047b6620](https://linux-hardware.org/?probe=6d047b6620) | Dec 30, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [26e56628ec](https://linux-hardware.org/?probe=26e56628ec) | Dec 30, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [dc7201711c](https://linux-hardware.org/?probe=dc7201711c) | Dec 30, 2022 |
| Lenovo        | 3181 SEK0T35577 IOT 4247... | Mini pc     | [fa1b60ae23](https://linux-hardware.org/?probe=fa1b60ae23) | Dec 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [4ca2070d42](https://linux-hardware.org/?probe=4ca2070d42) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | Notebook    | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| HP            | 1589                        | Desktop     | [4769414712](https://linux-hardware.org/?probe=4769414712) | Dec 24, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | Notebook    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [353cbeb5c8](https://linux-hardware.org/?probe=353cbeb5c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Biostar       | X470GTN                     | Desktop     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [3bc811ef2a](https://linux-hardware.org/?probe=3bc811ef2a) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c5c5c07485](https://linux-hardware.org/?probe=c5c5c07485) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c992b15fbe](https://linux-hardware.org/?probe=c992b15fbe) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [4378eff64f](https://linux-hardware.org/?probe=4378eff64f) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | Desktop     | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [94b281cfa1](https://linux-hardware.org/?probe=94b281cfa1) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| Dell          | 0215PR A02                  | Desktop     | [b9d16b98d2](https://linux-hardware.org/?probe=b9d16b98d2) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [d7b2726838](https://linux-hardware.org/?probe=d7b2726838) | Dec 08, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f5bd8a0e5b](https://linux-hardware.org/?probe=f5bd8a0e5b) | Dec 07, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a742429421](https://linux-hardware.org/?probe=a742429421) | Dec 06, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f2025f3847](https://linux-hardware.org/?probe=f2025f3847) | Dec 04, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [69ed3a0345](https://linux-hardware.org/?probe=69ed3a0345) | Dec 02, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [ae30b95cd8](https://linux-hardware.org/?probe=ae30b95cd8) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | Desktop     | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| Dell          | Studio 1737                 | Notebook    | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP            | 8653 A                      | Desktop     | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel         | B75                         | Desktop     | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| MSI           | Z87 XPOWER                  | Desktop     | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| HP            | 2000                        | Notebook    | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| HP            | 1998                        | Desktop     | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | Notebook    | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| HP            | 2000                        | Notebook    | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [062910424d](https://linux-hardware.org/?probe=062910424d) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [a205e0ea70](https://linux-hardware.org/?probe=a205e0ea70) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel         | B75                         | Desktop     | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [d31088804f](https://linux-hardware.org/?probe=d31088804f) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell          | Latitude 7275               | Tablet      | [49ee35636b](https://linux-hardware.org/?probe=49ee35636b) | Sep 24, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gateway       | NE56R                       | Notebook    | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | Notebook    | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP            | 8594                        | Desktop     | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Alienware     | Area-51m R2 A00             | Notebook    | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | Notebook    | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | Notebook    | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | Notebook    | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | Notebook    | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| AZW           | SER                         | Mini pc     | [92460ed2a6](https://linux-hardware.org/?probe=92460ed2a6) | Aug 29, 2022 |
| ASUSTek       | TP500LA                     | Notebook    | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock        | H61M-VG3                    | Desktop     | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| Dell          | G15 5511                    | Notebook    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP            | 8054                        | Desktop     | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [5f2025770d](https://linux-hardware.org/?probe=5f2025770d) | Aug 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| Razer         | Blade                       | Notebook    | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell          | 0J8H4R A01                  | Desktop     | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines     | EL1870                      | Desktop     | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Nobara 36 | 242       | 74.01%  |
| Nobara 37 | 85        | 25.99%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Nobara | 323       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                                  | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64                                   | 36        | 10.62%  |
| 6.0.14-201.fsync.fc36.x86_64                             | 25        | 7.37%   |
| 5.19.14-201.fsync.fc36.x86_64                            | 24        | 7.08%   |
| 6.1.9-200.fsync.fc37.x86_64                              | 17        | 5.01%   |
| 5.19.9-201.fsync.fc36.x86_64                             | 16        | 4.72%   |
| 6.1.4-203.fsync.fc37.x86_64                              | 15        | 4.42%   |
| 5.19.7-204.fsync.fc36.x86_64                             | 15        | 4.42%   |
| 6.0.7-201.fsync.fc36.x86_64                              | 12        | 3.54%   |
| 5.19.16-201.fsync.fc36.x86_64                            | 12        | 3.54%   |
| 6.1.11-201.fsync.fc37.x86_64                             | 11        | 3.24%   |
| 6.0.5-201.fsync.fc36.x86_64                              | 11        | 3.24%   |
| 5.18.13-201.fsync.fc36.x86_64                            | 11        | 3.24%   |
| 6.1.6-203.fsync.fc37.x86_64                              | 10        | 2.95%   |
| 6.1.8-202.fsync.fc37.x86_64                              | 9         | 2.65%   |
| 6.0.9-201.fc36.x86_64                                    | 9         | 2.65%   |
| 6.0.16-301.fsync.fc37.x86_64                             | 8         | 2.36%   |
| 5.19.12-201.fsync.fc36.x86_64                            | 8         | 2.36%   |
| 5.19.10-201.fsync.fc36.x86_64                            | 8         | 2.36%   |
| 5.19.4-201.fsync.fc36.x86_64                             | 7         | 2.06%   |
| 5.18.16-201.fsync.fc36.x86_64                            | 7         | 2.06%   |
| 5.19.15-202.fsync.fc36.x86_64                            | 6         | 1.77%   |
| 5.19.11-201.fsync.fc36.x86_64                            | 6         | 1.77%   |
| 5.18.17-201.fsync.fc36.x86_64                            | 6         | 1.77%   |
| 6.1.6-201.fsync.fc37.x86_64                              | 4         | 1.18%   |
| 6.0.9-202.fc36.x86_64                                    | 4         | 1.18%   |
| 6.0.8-201.fsync.fc36.x86_64                              | 4         | 1.18%   |
| 6.0.7-202.fsync.fc36.x86_64                              | 4         | 1.18%   |
| 5.19.8-201.fsync.fc36.x86_64                             | 4         | 1.18%   |
| 5.18.19-201.fsync.fc36.x86_64                            | 4         | 1.18%   |
| 6.1.8-201.fsync.fc37.x86_64                              | 3         | 0.88%   |
| 5.18.11-201.fsync.fc36.x86_64                            | 3         | 0.88%   |
| 6.1.6-202.fsync.fc37.x86_64                              | 2         | 0.59%   |
| 6.0.18-301.fsync.fc37.x86_64                             | 2         | 0.59%   |
| 6.0.15-301.fsync.fc37.x86_64                             | 2         | 0.59%   |
| 5.19.7-203.fsync.fc36.x86_64                             | 2         | 0.59%   |
| 5.19.13-202.fsync.fc36.x86_64                            | 2         | 0.59%   |
| 5.18.18-201.fsync.fc36.x86_64                            | 2         | 0.59%   |
| 6.2.0-0.rc3.20230109git1fe4fd6f5cad.24.fsync.fc37.x86_64 | 1         | 0.29%   |
| 6.1.8-200.fsync.fc37.x86_64                              | 1         | 0.29%   |
| 6.1.12_tkg_cfs                                           | 1         | 0.29%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.10  | 36        | 10.62%  |
| 6.0.14  | 25        | 7.37%   |
| 5.19.14 | 24        | 7.08%   |
| 6.1.9   | 17        | 5.01%   |
| 5.19.7  | 17        | 5.01%   |
| 6.1.6   | 16        | 4.72%   |
| 6.0.7   | 16        | 4.72%   |
| 5.19.9  | 16        | 4.72%   |
| 6.1.4   | 15        | 4.42%   |
| 6.1.8   | 13        | 3.83%   |
| 6.0.9   | 13        | 3.83%   |
| 5.19.16 | 12        | 3.54%   |
| 6.1.11  | 11        | 3.24%   |
| 6.0.5   | 11        | 3.24%   |
| 5.18.13 | 11        | 3.24%   |
| 6.0.16  | 8         | 2.36%   |
| 5.19.12 | 8         | 2.36%   |
| 5.19.10 | 8         | 2.36%   |
| 5.19.4  | 7         | 2.06%   |
| 5.18.16 | 7         | 2.06%   |
| 5.19.15 | 6         | 1.77%   |
| 5.19.11 | 6         | 1.77%   |
| 5.18.17 | 6         | 1.77%   |
| 6.0.8   | 4         | 1.18%   |
| 5.19.8  | 4         | 1.18%   |
| 5.18.19 | 4         | 1.18%   |
| 5.19.13 | 3         | 0.88%   |
| 5.18.11 | 3         | 0.88%   |
| 6.0.18  | 2         | 0.59%   |
| 6.0.15  | 2         | 0.59%   |
| 5.18.18 | 2         | 0.59%   |
| 6.2.0   | 1         | 0.29%   |
| 6.1.12  | 1         | 0.29%   |
| 6.0.2   | 1         | 0.29%   |
| 6.0.13  | 1         | 0.29%   |
| 5.19.2  | 1         | 0.29%   |
| 5.18.9  | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 116       | 34.63%  |
| 5.19    | 112       | 33.43%  |
| 6.1     | 72        | 21.49%  |
| 5.18    | 34        | 10.15%  |
| 6.2     | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 323       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 235       | 72.53%  |
| KDE5          | 82        | 25.31%  |
| Unknown       | 4         | 1.23%   |
| GNOME Classic | 2         | 0.62%   |
| X-Cinnamon    | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 246       | 74.1%   |
| X11     | 81        | 24.4%   |
| Unknown | 4         | 1.2%    |
| Tty     | 1         | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 271       | 83.13%  |
| GDM     | 34        | 10.43%  |
| SDDM    | 18        | 5.52%   |
| LightDM | 3         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 180       | 55.38%  |
| en_GB   | 23        | 7.08%   |
| es_ES   | 12        | 3.69%   |
| de_DE   | 10        | 3.08%   |
| es_MX   | 9         | 2.77%   |
| en_CA   | 9         | 2.77%   |
| es_AR   | 8         | 2.46%   |
| pl_PL   | 7         | 2.15%   |
| ru_RU   | 5         | 1.54%   |
| pt_BR   | 5         | 1.54%   |
| it_IT   | 5         | 1.54%   |
| fr_FR   | 5         | 1.54%   |
| en_NZ   | 4         | 1.23%   |
| en_IN   | 4         | 1.23%   |
| de_AT   | 4         | 1.23%   |
| pt_PT   | 3         | 0.92%   |
| nl_NL   | 3         | 0.92%   |
| es_CO   | 3         | 0.92%   |
| en_AU   | 3         | 0.92%   |
| Unknown | 3         | 0.92%   |
| sv_SE   | 2         | 0.62%   |
| fi_FI   | 2         | 0.62%   |
| tr_TR   | 1         | 0.31%   |
| sk_SK   | 1         | 0.31%   |
| nb_NO   | 1         | 0.31%   |
| hu_HU   | 1         | 0.31%   |
| hr_HR   | 1         | 0.31%   |
| es_GT   | 1         | 0.31%   |
| es_EC   | 1         | 0.31%   |
| es_CR   | 1         | 0.31%   |
| es_CL   | 1         | 0.31%   |
| en_ZA   | 1         | 0.31%   |
| en_PH   | 1         | 0.31%   |
| en_IL   | 1         | 0.31%   |
| en_IE   | 1         | 0.31%   |
| cs_CZ   | 1         | 0.31%   |
| C       | 1         | 0.31%   |
| ar_SA   | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 259       | 79.94%  |
| BIOS | 65        | 20.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 203       | 62.65%  |
| Ext4  | 119       | 36.73%  |
| Xfs   | 2         | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 268       | 81.96%  |
| GPT     | 53        | 16.21%  |
| MBR     | 6         | 1.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 308       | 95.06%  |
| Yes       | 16        | 4.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 292       | 90.4%   |
| Yes       | 31        | 9.6%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 83        | 25.7%   |
| MSI                 | 42        | 13%     |
| Hewlett-Packard     | 41        | 12.69%  |
| Lenovo              | 38        | 11.76%  |
| Gigabyte Technology | 27        | 8.36%   |
| Dell                | 21        | 6.5%    |
| ASRock              | 17        | 5.26%   |
| Apple               | 11        | 3.41%   |
| Acer                | 8         | 2.48%   |
| Toshiba             | 3         | 0.93%   |
| Intel               | 3         | 0.93%   |
| Alienware           | 3         | 0.93%   |
| Positivo            | 2         | 0.62%   |
| Notebook            | 2         | 0.62%   |
| Biostar             | 2         | 0.62%   |
| AZW                 | 2         | 0.62%   |
| ZOTAC               | 1         | 0.31%   |
| Valve               | 1         | 0.31%   |
| Sony                | 1         | 0.31%   |
| Samsung Electronics | 1         | 0.31%   |
| Razer               | 1         | 0.31%   |
| OEM                 | 1         | 0.31%   |
| Monster             | 1         | 0.31%   |
| Medion              | 1         | 0.31%   |
| HUAWEI              | 1         | 0.31%   |
| Gateway             | 1         | 0.31%   |
| Fujitsu             | 1         | 0.31%   |
| EVOO                | 1         | 0.31%   |
| eMachines           | 1         | 0.31%   |
| ECS                 | 1         | 0.31%   |
| Dynabook            | 1         | 0.31%   |
| Coradir             | 1         | 0.31%   |
| Casper              | 1         | 0.31%   |
| Unknown             | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| MSI MS-7C91                         | 5         | 1.55%   |
| MSI MS-7B86                         | 4         | 1.24%   |
| MSI MS-7C37                         | 3         | 0.93%   |
| ASUS PRIME A320M-K                  | 3         | 0.93%   |
| Unknown                             | 3         | 0.93%   |
| MSI MS-7C02                         | 2         | 0.62%   |
| MSI MS-7693                         | 2         | 0.62%   |
| Lenovo Legion 5 15ARH05 82B5        | 2         | 0.62%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 2         | 0.62%   |
| HP ZBook 15u G3                     | 2         | 0.62%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 2         | 0.62%   |
| HP EliteBook x360 1030 G2           | 2         | 0.62%   |
| Gigabyte Z590I VISION D             | 2         | 0.62%   |
| Gigabyte B450M DS3H                 | 2         | 0.62%   |
| Dell XPS 8700                       | 2         | 0.62%   |
| Dell OptiPlex 390                   | 2         | 0.62%   |
| ASUS ROG CROSSHAIR VIII HERO        | 2         | 0.62%   |
| ZOTAC ZBOX-CI320NANO series         | 1         | 0.31%   |
| Valve Jupiter                       | 1         | 0.31%   |
| Toshiba TECRA A50-A                 | 1         | 0.31%   |
| Toshiba Satellite L850              | 1         | 0.31%   |
| Toshiba Satellite L650              | 1         | 0.31%   |
| Sony SVF1521N6EW                    | 1         | 0.31%   |
| Samsung R520/R522/R620              | 1         | 0.31%   |
| Razer Blade                         | 1         | 0.31%   |
| Positivo N1250                      | 1         | 0.31%   |
| Positivo N1240                      | 1         | 0.31%   |
| OEM SHARKBAY                        | 1         | 0.31%   |
| Notebook P7xxDM2(-G)                | 1         | 0.31%   |
| Notebook NP5x_NP6x_NP7xHP           | 1         | 0.31%   |
| MSI Pulse GL76 12UEK                | 1         | 0.31%   |
| MSI MS-7D53                         | 1         | 0.31%   |
| MSI MS-7D43                         | 1         | 0.31%   |
| MSI MS-7D41                         | 1         | 0.31%   |
| MSI MS-7D25                         | 1         | 0.31%   |
| MSI MS-7D17                         | 1         | 0.31%   |
| MSI MS-7C87                         | 1         | 0.31%   |
| MSI MS-7C84                         | 1         | 0.31%   |
| MSI MS-7C75                         | 1         | 0.31%   |
| MSI MS-7C56                         | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 23        | 7.12%   |
| ASUS PRIME         | 15        | 4.64%   |
| Lenovo IdeaPad     | 12        | 3.72%   |
| ASUS TUF           | 10        | 3.1%    |
| Lenovo ThinkPad    | 8         | 2.48%   |
| HP EliteBook       | 8         | 2.48%   |
| HP Pavilion        | 7         | 2.17%   |
| Lenovo Legion      | 6         | 1.86%   |
| ASUS VivoBook      | 6         | 1.86%   |
| MSI MS-7C91        | 5         | 1.55%   |
| Dell Precision     | 5         | 1.55%   |
| MSI MS-7B86        | 4         | 1.24%   |
| HP ZBook           | 4         | 1.24%   |
| HP ENVY            | 4         | 1.24%   |
| Dell OptiPlex      | 4         | 1.24%   |
| ASUS ASUS          | 4         | 1.24%   |
| Acer Aspire        | 4         | 1.24%   |
| MSI MS-7C37        | 3         | 0.93%   |
| Lenovo ThinkCentre | 3         | 0.93%   |
| HP EliteDesk       | 3         | 0.93%   |
| Gigabyte X570      | 3         | 0.93%   |
| Unknown            | 3         | 0.93%   |
| Toshiba Satellite  | 2         | 0.62%   |
| MSI MS-7C02        | 2         | 0.62%   |
| MSI MS-7693        | 2         | 0.62%   |
| Lenovo G580        | 2         | 0.62%   |
| HP OMEN            | 2         | 0.62%   |
| HP Laptop          | 2         | 0.62%   |
| HP Compaq          | 2         | 0.62%   |
| Gigabyte Z590I     | 2         | 0.62%   |
| Gigabyte B550M     | 2         | 0.62%   |
| Gigabyte B450M     | 2         | 0.62%   |
| Gigabyte B450      | 2         | 0.62%   |
| Dell XPS           | 2         | 0.62%   |
| Dell Inspiron      | 2         | 0.62%   |
| Dell G15           | 2         | 0.62%   |
| ASUS M5A97         | 2         | 0.62%   |
| ASRock X570        | 2         | 0.62%   |
| Apple MacBookPro8  | 2         | 0.62%   |
| Acer Swift         | 2         | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 47        | 14.55%  |
| 2020 | 45        | 13.93%  |
| 2019 | 45        | 13.93%  |
| 2018 | 28        | 8.67%   |
| 2013 | 25        | 7.74%   |
| 2022 | 22        | 6.81%   |
| 2017 | 22        | 6.81%   |
| 2014 | 20        | 6.19%   |
| 2012 | 19        | 5.88%   |
| 2016 | 15        | 4.64%   |
| 2011 | 13        | 4.02%   |
| 2015 | 9         | 2.79%   |
| 2009 | 5         | 1.55%   |
| 2010 | 4         | 1.24%   |
| 2008 | 3         | 0.93%   |
| 2023 | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 162       | 50.15%  |
| Notebook    | 146       | 45.2%   |
| Mini pc     | 6         | 1.86%   |
| Convertible | 5         | 1.55%   |
| All in one  | 3         | 0.93%   |
| Tablet      | 1         | 0.31%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 323       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 323       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 97        | 30.03%  |
| 32.01-64.0  | 61        | 18.89%  |
| 8.01-16.0   | 60        | 18.58%  |
| 4.01-8.0    | 58        | 17.96%  |
| 3.01-4.0    | 28        | 8.67%   |
| 24.01-32.0  | 12        | 3.72%   |
| 64.01-256.0 | 6         | 1.86%   |
| 1.01-2.0    | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 152       | 45.92%  |
| 3.01-4.0   | 78        | 23.56%  |
| 2.01-3.0   | 61        | 18.43%  |
| 8.01-16.0  | 32        | 9.67%   |
| 1.01-2.0   | 5         | 1.51%   |
| 16.01-24.0 | 2         | 0.6%    |
| 24.01-32.0 | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 157       | 48.16%  |
| 2      | 80        | 24.54%  |
| 3      | 51        | 15.64%  |
| 4      | 18        | 5.52%   |
| 5      | 15        | 4.6%    |
| 6      | 3         | 0.92%   |
| 10     | 1         | 0.31%   |
| 7      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 78.4%   |
| Yes       | 70        | 21.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 292       | 90.12%  |
| No        | 32        | 9.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 248       | 76.78%  |
| No        | 75        | 23.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 70.37%  |
| No        | 96        | 29.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 100       | 30.96%  |
| Germany      | 18        | 5.57%   |
| UK           | 14        | 4.33%   |
| Poland       | 12        | 3.72%   |
| Canada       | 12        | 3.72%   |
| Spain        | 11        | 3.41%   |
| Argentina    | 11        | 3.41%   |
| Mexico       | 10        | 3.1%    |
| Italy        | 9         | 2.79%   |
| Brazil       | 9         | 2.79%   |
| France       | 8         | 2.48%   |
| Russia       | 7         | 2.17%   |
| India        | 6         | 1.86%   |
| Sweden       | 5         | 1.55%   |
| Chile        | 5         | 1.55%   |
| Austria      | 5         | 1.55%   |
| Portugal     | 4         | 1.24%   |
| Philippines  | 4         | 1.24%   |
| New Zealand  | 4         | 1.24%   |
| Netherlands  | 4         | 1.24%   |
| Colombia     | 4         | 1.24%   |
| Serbia       | 3         | 0.93%   |
| Romania      | 3         | 0.93%   |
| Norway       | 3         | 0.93%   |
| Indonesia    | 3         | 0.93%   |
| Hungary      | 3         | 0.93%   |
| Finland      | 3         | 0.93%   |
| Czechia      | 3         | 0.93%   |
| Croatia      | 3         | 0.93%   |
| Australia    | 3         | 0.93%   |
| Vietnam      | 2         | 0.62%   |
| South Africa | 2         | 0.62%   |
| Saudi Arabia | 2         | 0.62%   |
| Egypt        | 2         | 0.62%   |
| Belgium      | 2         | 0.62%   |
| Venezuela    | 1         | 0.31%   |
| Ukraine      | 1         | 0.31%   |
| Turkey       | 1         | 0.31%   |
| Taiwan       | 1         | 0.31%   |
| South Korea  | 1         | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Guadalajara  | 4         | 1.2%    |
| Wroclaw      | 3         | 0.9%    |
| Buenos Aires | 3         | 0.9%    |
| Auckland     | 3         | 0.9%    |
| Atlanta      | 3         | 0.9%    |
| Wasilla      | 2         | 0.6%    |
| Warsaw       | 2         | 0.6%    |
| Villa Nueva  | 2         | 0.6%    |
| Vienna       | 2         | 0.6%    |
| Valladolid   | 2         | 0.6%    |
| Stockholm    | 2         | 0.6%    |
| Schmalkalden | 2         | 0.6%    |
| Sao Paulo    | 2         | 0.6%    |
| San Jose     | 2         | 0.6%    |
| San Antonio  | 2         | 0.6%    |
| Rotterdam    | 2         | 0.6%    |
| Rome         | 2         | 0.6%    |
| Poznan       | 2         | 0.6%    |
| Plano        | 2         | 0.6%    |
| Philadelphia | 2         | 0.6%    |
| Panama City  | 2         | 0.6%    |
| Ochsenfurt   | 2         | 0.6%    |
| Mumbai       | 2         | 0.6%    |
| Milano       | 2         | 0.6%    |
| Milan        | 2         | 0.6%    |
| Melbourne    | 2         | 0.6%    |
| Mansfield    | 2         | 0.6%    |
| Madrid       | 2         | 0.6%    |
| London       | 2         | 0.6%    |
| Johannesburg | 2         | 0.6%    |
| Fortaleza    | 2         | 0.6%    |
| Fairbanks    | 2         | 0.6%    |
| Denver       | 2         | 0.6%    |
| Bucharest    | 2         | 0.6%    |
| Berlin       | 2         | 0.6%    |
| Belgrade     | 2         | 0.6%    |
| Zamora       | 1         | 0.3%    |
| Zagreb       | 1         | 0.3%    |
| Zadar        | 1         | 0.3%    |
| Wooster      | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 99        | 148    | 17.55%  |
| WDC                         | 75        | 105    | 13.3%   |
| Seagate                     | 62        | 79     | 10.99%  |
| Kingston                    | 43        | 46     | 7.62%   |
| Toshiba                     | 35        | 38     | 6.21%   |
| Crucial                     | 34        | 44     | 6.03%   |
| Sandisk                     | 32        | 33     | 5.67%   |
| Intel                       | 19        | 26     | 3.37%   |
| Phison Electronics          | 14        | 15     | 2.48%   |
| SK hynix                    | 12        | 13     | 2.13%   |
| Micron Technology           | 12        | 12     | 2.13%   |
| Micron/Crucial Technology   | 11        | 12     | 1.95%   |
| PNY                         | 9         | 13     | 1.6%    |
| Hitachi                     | 8         | 9      | 1.42%   |
| China                       | 8         | 8      | 1.42%   |
| Apple                       | 8         | 9      | 1.42%   |
| Phison                      | 7         | 8      | 1.24%   |
| HGST                        | 5         | 5      | 0.89%   |
| ADATA Technology            | 5         | 5      | 0.89%   |
| Unknown                     | 4         | 5      | 0.71%   |
| SPCC                        | 4         | 4      | 0.71%   |
| KIOXIA                      | 4         | 4      | 0.71%   |
| A-DATA Technology           | 4         | 4      | 0.71%   |
| Silicon Motion              | 3         | 3      | 0.53%   |
| Realtek Semiconductor       | 3         | 3      | 0.53%   |
| Unknown                     | 3         | 4      | 0.53%   |
| USB3.0                      | 2         | 2      | 0.35%   |
| Transcend                   | 2         | 2      | 0.35%   |
| Team                        | 2         | 2      | 0.35%   |
| Mushkin                     | 2         | 2      | 0.35%   |
| LITEON                      | 2         | 2      | 0.35%   |
| Kingston Technology Company | 2         | 2      | 0.35%   |
| HS-SSD-C100                 | 2         | 2      | 0.35%   |
| Drevo                       | 2         | 2      | 0.35%   |
| XPG                         | 1         | 1      | 0.18%   |
| Verbatim                    | 1         | 1      | 0.18%   |
| Union Memory                | 1         | 1      | 0.18%   |
| T-FORCE                     | 1         | 1      | 0.18%   |
| SuperSSpeed                 | 1         | 1      | 0.18%   |
| Solid State Storage         | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB  | 17        | 2.65%   |
| Kingston SA400S37240G 240GB SSD                      | 16        | 2.49%   |
| Samsung SSD 860 EVO 500GB                            | 8         | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 8         | 1.25%   |
| Phison E12 NVMe Controller 1024GB                    | 8         | 1.25%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                  | 8         | 1.25%   |
| Crucial CT1000MX500SSD1 1TB                          | 8         | 1.25%   |
| Intel SSD 660P Series 1024GB                         | 7         | 1.09%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 6         | 0.93%   |
| Samsung SSD 850 EVO 250GB                            | 6         | 0.93%   |
| Toshiba HDWD110 1TB                                  | 5         | 0.78%   |
| Toshiba DT01ACA100 1TB                               | 5         | 0.78%   |
| Seagate ST2000DM008-2FR102 2TB                       | 5         | 0.78%   |
| Seagate ST2000DM001-1ER164 2TB                       | 5         | 0.78%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 5         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 512GB  | 5         | 0.78%   |
| Phison PS5013 E13 NVMe Controller 500GB              | 5         | 0.78%   |
| Crucial CT1000BX500SSD1 1TB                          | 5         | 0.78%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 4         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 4         | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 4         | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB                       | 4         | 0.62%   |
| Samsung SSD 980 500GB                                | 4         | 0.62%   |
| Samsung SSD 980 1TB                                  | 4         | 0.62%   |
| Samsung SSD 860 EVO 1TB                              | 4         | 0.62%   |
| Samsung SSD 850 EVO 500GB                            | 4         | 0.62%   |
| Kingston SA400S37120G 120GB SSD                      | 4         | 0.62%   |
| WDC WDBNCE5000PNC 500GB SSD                          | 3         | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 3         | 0.47%   |
| Toshiba MQ04ABF100 1TB                               | 3         | 0.47%   |
| Toshiba MQ01ABD100 1TB                               | 3         | 0.47%   |
| SK hynix BC511 512GB                                 | 3         | 0.47%   |
| SanDisk SSD PLUS 240GB                               | 3         | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB                       | 3         | 0.47%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB        | 3         | 0.47%   |
| PNY CS900 500GB SSD                                  | 3         | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                     | 3         | 0.47%   |
| Kingston SA400S37480G 480GB SSD                      | 3         | 0.47%   |
| Intel SSDPEKNU512GZ 512GB                            | 3         | 0.47%   |
| Crucial CT500MX500SSD1 500GB                         | 3         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 77     | 34.44%  |
| WDC                 | 59        | 82     | 32.78%  |
| Toshiba             | 28        | 30     | 15.56%  |
| Hitachi             | 8         | 9      | 4.44%   |
| Samsung Electronics | 7         | 12     | 3.89%   |
| HGST                | 5         | 5      | 2.78%   |
| Apple               | 5         | 5      | 2.78%   |
| USB3.0              | 1         | 1      | 0.56%   |
| Unknown             | 1         | 1      | 0.56%   |
| Maxtor              | 1         | 1      | 0.56%   |
| JMicron Technology  | 1         | 1      | 0.56%   |
| HGST HTS            | 1         | 1      | 0.56%   |
| Fujitsu             | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 56     | 22.55%  |
| Crucial             | 33        | 43     | 16.18%  |
| Kingston            | 32        | 34     | 15.69%  |
| WDC                 | 14        | 15     | 6.86%   |
| SanDisk             | 14        | 14     | 6.86%   |
| PNY                 | 9         | 13     | 4.41%   |
| China               | 8         | 8      | 3.92%   |
| Micron Technology   | 5         | 5      | 2.45%   |
| SPCC                | 4         | 4      | 1.96%   |
| Intel               | 4         | 4      | 1.96%   |
| A-DATA Technology   | 4         | 4      | 1.96%   |
| Transcend           | 2         | 2      | 0.98%   |
| Toshiba             | 2         | 2      | 0.98%   |
| Mushkin             | 2         | 2      | 0.98%   |
| LITEON              | 2         | 2      | 0.98%   |
| Drevo               | 2         | 2      | 0.98%   |
| Apple               | 2         | 2      | 0.98%   |
| Verbatim            | 1         | 1      | 0.49%   |
| USB3.0              | 1         | 1      | 0.49%   |
| Team                | 1         | 1      | 0.49%   |
| SuperSSpeed         | 1         | 1      | 0.49%   |
| SK hynix            | 1         | 1      | 0.49%   |
| Seagate             | 1         | 1      | 0.49%   |
| Ramsta              | 1         | 1      | 0.49%   |
| PNY CS90            | 1         | 1      | 0.49%   |
| Patriot             | 1         | 1      | 0.49%   |
| OCZ                 | 1         | 1      | 0.49%   |
| Neo                 | 1         | 1      | 0.49%   |
| MyDigitalSSD        | 1         | 1      | 0.49%   |
| LITEONIT            | 1         | 1      | 0.49%   |
| Lexar               | 1         | 1      | 0.49%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.49%   |
| KingFast            | 1         | 1      | 0.49%   |
| Foxline             | 1         | 1      | 0.49%   |
| Emtec               | 1         | 1      | 0.49%   |
| Unknown             | 1         | 2      | 0.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 171       | 232    | 34.69%  |
| NVMe    | 161       | 226    | 32.66%  |
| HDD     | 150       | 226    | 30.43%  |
| Unknown | 9         | 10     | 1.83%   |
| MMC     | 2         | 2      | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 236       | 446    | 56.46%  |
| NVMe | 161       | 226    | 38.52%  |
| SAS  | 19        | 22     | 4.55%   |
| MMC  | 2         | 2      | 0.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 167       | 220    | 47.44%  |
| 0.51-1.0   | 113       | 147    | 32.1%   |
| 1.01-2.0   | 45        | 60     | 12.78%  |
| 3.01-4.0   | 9         | 9      | 2.56%   |
| 4.01-10.0  | 8         | 11     | 2.27%   |
| 2.01-3.0   | 6         | 6      | 1.7%    |
| 10.01-20.0 | 4         | 5      | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 79        | 24.09%  |
| 251-500        | 72        | 21.95%  |
| 501-1000       | 67        | 20.43%  |
| 1001-2000      | 46        | 14.02%  |
| More than 3000 | 25        | 7.62%   |
| 2001-3000      | 13        | 3.96%   |
| 21-50          | 8         | 2.44%   |
| 51-100         | 8         | 2.44%   |
| Unknown        | 8         | 2.44%   |
| 1-20           | 2         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 97        | 29.04%  |
| 1-20           | 69        | 20.66%  |
| 51-100         | 40        | 11.98%  |
| 101-250        | 39        | 11.68%  |
| 251-500        | 33        | 9.88%   |
| 501-1000       | 22        | 6.59%   |
| 1001-2000      | 11        | 3.29%   |
| More than 3000 | 8         | 2.4%    |
| Unknown        | 8         | 2.4%    |
| 2001-3000      | 7         | 2.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2         | 2      | 16.67%  |
| WDC WD20EURS-63S48Y0 2TB                       | 1         | 1      | 8.33%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1         | 1      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 1      | 8.33%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1         | 1      | 8.33%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 8.33%   |
| Samsung Electronics HD161GJ 160GB              | 1         | 1      | 8.33%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 8.33%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 8.33%   |
| Hitachi HTS54323 320GB                         | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 33.33%  |
| Seagate             | 3         | 3      | 25%     |
| Samsung Electronics | 2         | 2      | 16.67%  |
| Ramsta              | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 44.44%  |
| Seagate             | 3         | 3      | 33.33%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 75%     |
| SSD  | 2         | 2      | 16.67%  |
| NVMe | 1         | 1      | 8.33%   |

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
| Detected | 273       | 565    | 79.82%  |
| Works    | 57        | 118    | 16.67%  |
| Malfunc  | 11        | 12     | 3.22%   |
| Limited  | 1         | 1      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 176       | 35.99%  |
| AMD                            | 113       | 23.11%  |
| Samsung Electronics            | 62        | 12.68%  |
| SanDisk                        | 24        | 4.91%   |
| Phison Electronics             | 21        | 4.29%   |
| Kingston Technology Company    | 14        | 2.86%   |
| Micron/Crucial Technology      | 12        | 2.45%   |
| ASMedia Technology             | 12        | 2.45%   |
| SK hynix                       | 11        | 2.25%   |
| Micron Technology              | 7         | 1.43%   |
| ADATA Technology               | 5         | 1.02%   |
| Toshiba America Info Systems   | 4         | 0.82%   |
| Realtek Semiconductor          | 4         | 0.82%   |
| Nvidia                         | 4         | 0.82%   |
| Marvell Technology Group       | 4         | 0.82%   |
| KIOXIA                         | 4         | 0.82%   |
| Silicon Motion                 | 3         | 0.61%   |
| JMicron Technology             | 2         | 0.41%   |
| Union Memory (Shenzhen)        | 1         | 0.2%    |
| Solid State Storage Technology | 1         | 0.2%    |
| Silicon Image                  | 1         | 0.2%    |
| Shenzhen Longsys Electronics   | 1         | 0.2%    |
| MAXIO Technology (Hangzhou)    | 1         | 0.2%    |
| Broadcom / LSI                 | 1         | 0.2%    |
| Apple                          | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 75        | 13.71%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 28        | 5.12%   |
| AMD 400 Series Chipset SATA Controller                                         | 24        | 4.39%   |
| Samsung NVMe SSD Controller 980                                                | 18        | 3.29%   |
| AMD 500 Series Chipset SATA Controller                                         | 13        | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 2.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 11        | 2.01%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 11        | 2.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 10        | 1.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 1.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 1.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9         | 1.65%   |
| Phison E12 NVMe Controller                                                     | 8         | 1.46%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 8         | 1.46%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 1.46%   |
| Intel SSD 660P Series                                                          | 8         | 1.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 1.46%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 1.46%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 1.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.28%   |
| Micron Non-Volatile memory controller                                          | 7         | 1.28%   |
| Intel SATA Controller [RAID mode]                                              | 7         | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.1%    |
| Kingston Company A2000 NVMe SSD                                                | 6         | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 1.1%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 0.91%   |
| Phison PS5013 E13 NVMe Controller                                              | 5         | 0.91%   |
| Intel Non-Volatile memory controller                                           | 5         | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.91%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5         | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 0.91%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 262       | 56.1%   |
| NVMe | 161       | 34.48%  |
| RAID | 25        | 5.35%   |
| IDE  | 17        | 3.64%   |
| SAS  | 2         | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 190       | 58.82%  |
| AMD    | 133       | 41.18%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 2600 Six-Core Processor         | 7         | 2.17%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 6         | 1.86%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 5         | 1.55%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5         | 1.55%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5         | 1.55%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 5         | 1.55%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5         | 1.55%   |
| AMD FX-8350 Eight-Core Processor            | 5         | 1.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 4         | 1.24%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4         | 1.24%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 1.24%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4         | 1.24%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4         | 1.24%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 4         | 1.24%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4         | 1.24%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 0.93%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3         | 0.93%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 3         | 0.93%   |
| Intel 12th Gen Core i5-12600K               | 3         | 0.93%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 3         | 0.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3         | 0.93%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 3         | 0.93%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 3         | 0.93%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3         | 0.93%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 3         | 0.93%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3         | 0.93%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3         | 0.93%   |
| AMD FX-6300 Six-Core Processor              | 3         | 0.93%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 2         | 0.62%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2         | 0.62%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 2         | 0.62%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 0.62%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 2         | 0.62%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 0.62%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 2         | 0.62%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 2         | 0.62%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 66        | 20.43%  |
| Intel Core i5           | 54        | 16.72%  |
| AMD Ryzen 5             | 49        | 15.17%  |
| AMD Ryzen 7             | 34        | 10.53%  |
| Other                   | 24        | 7.43%   |
| AMD Ryzen 9             | 19        | 5.88%   |
| Intel Core i3           | 17        | 5.26%   |
| AMD FX                  | 11        | 3.41%   |
| Intel Celeron           | 7         | 2.17%   |
| Intel Xeon              | 5         | 1.55%   |
| Intel Pentium           | 5         | 1.55%   |
| Intel Core 2 Duo        | 5         | 1.55%   |
| AMD Ryzen 3             | 5         | 1.55%   |
| Intel Core i9           | 3         | 0.93%   |
| AMD A10                 | 3         | 0.93%   |
| Intel Atom              | 2         | 0.62%   |
| AMD Phenom II X6        | 2         | 0.62%   |
| AMD A6                  | 2         | 0.62%   |
| Intel Pentium Dual-Core | 1         | 0.31%   |
| Intel Core m7           | 1         | 0.31%   |
| Intel Core 2 Extreme    | 1         | 0.31%   |
| AMD Ryzen 3 PRO         | 1         | 0.31%   |
| AMD Phenom II X4        | 1         | 0.31%   |
| AMD G                   | 1         | 0.31%   |
| AMD E                   | 1         | 0.31%   |
| AMD Athlon X4           | 1         | 0.31%   |
| AMD Athlon Dual Core    | 1         | 0.31%   |
| AMD A4                  | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 96        | 29.72%  |
| 2      | 75        | 23.22%  |
| 6      | 72        | 22.29%  |
| 8      | 51        | 15.79%  |
| 12     | 11        | 3.41%   |
| 16     | 6         | 1.86%   |
| 10     | 4         | 1.24%   |
| 3      | 4         | 1.24%   |
| 14     | 2         | 0.62%   |
| 1      | 2         | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 322       | 99.69%  |
| 2      | 1         | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 266       | 82.35%  |
| 1      | 57        | 17.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 323       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 17        | 5.25%   |
| 0x306a9    | 17        | 5.25%   |
| 0x08701021 | 16        | 4.94%   |
| 0x206a7    | 15        | 4.63%   |
| 0x0a50000c | 14        | 4.32%   |
| 0xa0652    | 12        | 3.7%    |
| 0x906ea    | 12        | 3.7%    |
| 0x40651    | 12        | 3.7%    |
| Unknown    | 12        | 3.7%    |
| 0x906e9    | 11        | 3.4%    |
| 0x08108109 | 10        | 3.09%   |
| 0x506e3    | 8         | 2.47%   |
| 0x0800820d | 8         | 2.47%   |
| 0x06000822 | 8         | 2.47%   |
| 0xa0655    | 6         | 1.85%   |
| 0x806e9    | 6         | 1.85%   |
| 0x806c1    | 6         | 1.85%   |
| 0x0a201016 | 6         | 1.85%   |
| 0x08608103 | 6         | 1.85%   |
| 0x906a3    | 5         | 1.54%   |
| 0x90672    | 5         | 1.54%   |
| 0x406e3    | 5         | 1.54%   |
| 0x0a50000d | 5         | 1.54%   |
| 0x08001138 | 5         | 1.54%   |
| 0x906ed    | 4         | 1.23%   |
| 0x906ec    | 4         | 1.23%   |
| 0x806d1    | 4         | 1.23%   |
| 0x1067a    | 4         | 1.23%   |
| 0x0a20120a | 4         | 1.23%   |
| 0x0a201205 | 4         | 1.23%   |
| 0x0a201204 | 4         | 1.23%   |
| 0x08600106 | 4         | 1.23%   |
| 0x08600104 | 4         | 1.23%   |
| 0xa0653    | 3         | 0.93%   |
| 0x30678    | 3         | 0.93%   |
| 0x206d7    | 3         | 0.93%   |
| 0x10676    | 3         | 0.93%   |
| 0x0a601203 | 3         | 0.93%   |
| 0x08108102 | 3         | 0.93%   |
| 0x06003106 | 3         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 13.31%  |
| Zen 3            | 40        | 12.38%  |
| Haswell          | 31        | 9.6%    |
| Zen 2            | 27        | 8.36%   |
| Zen+             | 22        | 6.81%   |
| CometLake        | 21        | 6.5%    |
| SandyBridge      | 19        | 5.88%   |
| IvyBridge        | 17        | 5.26%   |
| Unknown          | 14        | 4.33%   |
| Skylake          | 13        | 4.02%   |
| Piledriver       | 12        | 3.72%   |
| Alderlake Hybrid | 10        | 3.1%    |
| Icelake          | 8         | 2.48%   |
| Zen              | 7         | 2.17%   |
| Penryn           | 7         | 2.17%   |
| TigerLake        | 6         | 1.86%   |
| Silvermont       | 4         | 1.24%   |
| Steamroller      | 3         | 0.93%   |
| K10              | 3         | 0.93%   |
| Broadwell        | 3         | 0.93%   |
| Westmere         | 2         | 0.62%   |
| Goldmont plus    | 2         | 0.62%   |
| Excavator        | 2         | 0.62%   |
| Bobcat           | 2         | 0.62%   |
| Puma             | 1         | 0.31%   |
| Nehalem          | 1         | 0.31%   |
| K8 Hammer        | 1         | 0.31%   |
| Goldmont         | 1         | 0.31%   |
| Bonnell          | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 157       | 37.74%  |
| AMD    | 134       | 32.21%  |
| Intel  | 125       | 30.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15        | 3.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 13        | 3.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 12        | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 12        | 2.8%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 12        | 2.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 2.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9         | 2.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 8         | 1.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 1.64%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 1.64%   |
| AMD Renoir                                                                  | 7         | 1.64%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 7         | 1.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 6         | 1.4%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6         | 1.4%    |
| AMD Lucienne                                                                | 6         | 1.4%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 6         | 1.4%    |
| Nvidia TU117M                                                               | 5         | 1.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 5         | 1.17%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 5         | 1.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5         | 1.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 1.17%   |
| Intel HD Graphics 620                                                       | 5         | 1.17%   |
| Intel HD Graphics 530                                                       | 5         | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 1.17%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 5         | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 4         | 0.93%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4         | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 0.93%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4         | 0.93%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4         | 0.93%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 0.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 0.93%   |
| Intel HD Graphics 630                                                       | 4         | 0.93%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4         | 0.93%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 4         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 3         | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 3         | 0.7%    |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3         | 0.7%    |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3         | 0.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 92        | 28.48%  |
| 1 x Nvidia         | 83        | 25.7%   |
| 1 x Intel          | 56        | 17.34%  |
| Intel + Nvidia     | 49        | 15.17%  |
| AMD + Nvidia       | 22        | 6.81%   |
| Intel + AMD        | 10        | 3.1%    |
| 2 x AMD            | 8         | 2.48%   |
| 2 x Nvidia         | 2         | 0.62%   |
| Intel + 2 x Nvidia | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 198       | 60.92%  |
| Proprietary | 123       | 37.85%  |
| Unknown     | 4         | 1.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 42.2%   |
| 7.01-8.0   | 41        | 12.54%  |
| 0.01-0.5   | 38        | 11.62%  |
| 1.01-2.0   | 32        | 9.79%   |
| 3.01-4.0   | 26        | 7.95%   |
| 8.01-16.0  | 22        | 6.73%   |
| 0.51-1.0   | 18        | 5.5%    |
| 5.01-6.0   | 7         | 2.14%   |
| 16.01-24.0 | 3         | 0.92%   |
| 2.01-3.0   | 2         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 49        | 13.46%  |
| AU Optronics            | 39        | 10.71%  |
| Goldstar                | 25        | 6.87%   |
| Chimei Innolux          | 21        | 5.77%   |
| BOE                     | 21        | 5.77%   |
| LG Display              | 19        | 5.22%   |
| Acer                    | 17        | 4.67%   |
| Dell                    | 14        | 3.85%   |
| Ancor Communications    | 12        | 3.3%    |
| ASUSTek Computer        | 11        | 3.02%   |
| AOC                     | 11        | 3.02%   |
| PANDA                   | 10        | 2.75%   |
| Hewlett-Packard         | 10        | 2.75%   |
| BenQ                    | 10        | 2.75%   |
| Apple                   | 10        | 2.75%   |
| MSI                     | 9         | 2.47%   |
| Vizio                   | 7         | 1.92%   |
| ViewSonic               | 7         | 1.92%   |
| Sony                    | 7         | 1.92%   |
| Sharp                   | 7         | 1.92%   |
| InfoVision              | 5         | 1.37%   |
| Philips                 | 4         | 1.1%    |
| Lenovo                  | 4         | 1.1%    |
| Toshiba                 | 3         | 0.82%   |
| Sceptre Tech            | 3         | 0.82%   |
| HUAWEI                  | 2         | 0.55%   |
| Gigabyte Technology     | 2         | 0.55%   |
| Eizo                    | 2         | 0.55%   |
| Chi Mei Optoelectronics | 2         | 0.55%   |
| ___                     | 1         | 0.27%   |
| Valve                   | 1         | 0.27%   |
| Unknown                 | 1         | 0.27%   |
| Sun                     | 1         | 0.27%   |
| SNC                     | 1         | 0.27%   |
| SFX                     | 1         | 0.27%   |
| PRI                     | 1         | 0.27%   |
| Olevia                  | 1         | 0.27%   |
| NPC                     | 1         | 0.27%   |
| MStar                   | 1         | 0.27%   |
| MLT                     | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 4         | 1.05%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch  | 3         | 0.79%   |
| MSI G27C5 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch          | 3         | 0.79%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 3         | 0.79%   |
| Vizio D43-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                     | 2         | 0.53%   |
| Toshiba TV TSB0108 1440x900 700x390mm 31.5-inch                        | 2         | 0.53%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2         | 0.53%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2         | 0.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2         | 0.53%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 2         | 0.53%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch             | 2         | 0.53%   |
| InfoVision LCD Monitor IVO0535 1920x1080 294x165mm 13.3-inch           | 2         | 0.53%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch               | 2         | 0.53%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2         | 0.53%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2         | 0.53%   |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                     | 2         | 0.53%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch        | 2         | 0.53%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                  | 2         | 0.53%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch         | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.53%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 2         | 0.53%   |
| ASUSTek Computer ROG XG27UQR AUS27BA 3840x2160 596x335mm 26.9-inch     | 2         | 0.53%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch         | 2         | 0.53%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 2         | 0.53%   |
| AOC 2243W AOC2243 1920x1080 477x268mm 21.5-inch                        | 2         | 0.53%   |
| ___ LCD TV ___9000 1360x768                                            | 1         | 0.26%   |
| Vizio VX42L HDTV10A VIZ0030 1280x720 930x523mm 42.0-inch               | 1         | 0.26%   |
| Vizio V435-J01 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 1         | 0.26%   |
| Vizio E601i-A3 VIZ0092 1920x1080 1329x748mm 60.0-inch                  | 1         | 0.26%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 0.26%   |
| Vizio D32h-G9 VIZ1028 1366x768 521x293mm 23.5-inch                     | 1         | 0.26%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch          | 1         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 170       | 48.85%  |
| 1366x768 (WXGA)    | 38        | 10.92%  |
| 3840x2160 (4K)     | 35        | 10.06%  |
| 2560x1440 (QHD)    | 35        | 10.06%  |
| 1680x1050 (WSXGA+) | 8         | 2.3%    |
| 1440x900 (WXGA+)   | 8         | 2.3%    |
| 1920x1200 (WUXGA)  | 6         | 1.72%   |
| 1600x900 (HD+)     | 6         | 1.72%   |
| 1360x768           | 6         | 1.72%   |
| 3440x1440          | 5         | 1.44%   |
| 2560x1080          | 5         | 1.44%   |
| 2880x1800          | 4         | 1.15%   |
| 1920x540           | 4         | 1.15%   |
| 2560x1600          | 3         | 0.86%   |
| 1280x800 (WXGA)    | 3         | 0.86%   |
| 1280x1024 (SXGA)   | 3         | 0.86%   |
| 800x1280           | 1         | 0.29%   |
| 5760x1080          | 1         | 0.29%   |
| 3840x2560          | 1         | 0.29%   |
| 3840x1600          | 1         | 0.29%   |
| 3840x1080          | 1         | 0.29%   |
| 3200x1800 (QHD+)   | 1         | 0.29%   |
| 2520x1680          | 1         | 0.29%   |
| 2240x1400          | 1         | 0.29%   |
| Unknown            | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 89        | 24.12%  |
| 27      | 48        | 13.01%  |
| 23      | 26        | 7.05%   |
| 24      | 23        | 6.23%   |
| 21      | 21        | 5.69%   |
| 31      | 20        | 5.42%   |
| 13      | 20        | 5.42%   |
| 17      | 18        | 4.88%   |
| 14      | 13        | 3.52%   |
| 34      | 7         | 1.9%    |
| Unknown | 7         | 1.9%    |
| 72      | 6         | 1.63%   |
| 48      | 6         | 1.63%   |
| 20      | 6         | 1.63%   |
| 84      | 5         | 1.36%   |
| 26      | 5         | 1.36%   |
| 22      | 5         | 1.36%   |
| 19      | 5         | 1.36%   |
| 18      | 4         | 1.08%   |
| 16      | 3         | 0.81%   |
| 52      | 2         | 0.54%   |
| 49      | 2         | 0.54%   |
| 42      | 2         | 0.54%   |
| 40      | 2         | 0.54%   |
| 38      | 2         | 0.54%   |
| 37      | 2         | 0.54%   |
| 33      | 2         | 0.54%   |
| 29      | 2         | 0.54%   |
| 28      | 2         | 0.54%   |
| 12      | 2         | 0.54%   |
| 75      | 1         | 0.27%   |
| 69      | 1         | 0.27%   |
| 60      | 1         | 0.27%   |
| 58      | 1         | 0.27%   |
| 57      | 1         | 0.27%   |
| 55      | 1         | 0.27%   |
| 54      | 1         | 0.27%   |
| 32      | 1         | 0.27%   |
| 25      | 1         | 0.27%   |
| 11      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 32.22%  |
| 501-600     | 88        | 24.44%  |
| 401-500     | 41        | 11.39%  |
| 601-700     | 30        | 8.33%   |
| 201-300     | 16        | 4.44%   |
| 351-400     | 15        | 4.17%   |
| 1001-1500   | 15        | 4.17%   |
| 1501-2000   | 13        | 3.61%   |
| 701-800     | 10        | 2.78%   |
| Unknown     | 7         | 1.94%   |
| 801-900     | 6         | 1.67%   |
| 901-1000    | 2         | 0.56%   |
| 1-100       | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 257       | 81.07%  |
| 16/10   | 35        | 11.04%  |
| 21/9    | 11        | 3.47%   |
| 5/4     | 3         | 0.95%   |
| 32/9    | 3         | 0.95%   |
| 4/3     | 2         | 0.63%   |
| 3/2     | 2         | 0.63%   |
| Unknown | 2         | 0.63%   |
| 1.96    | 1         | 0.32%   |
| 0.67    | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 24.46%  |
| 201-250        | 62        | 16.85%  |
| 301-350        | 53        | 14.4%   |
| 351-500        | 31        | 8.42%   |
| More than 1000 | 25        | 6.79%   |
| 81-90          | 25        | 6.79%   |
| 151-200        | 19        | 5.16%   |
| 121-130        | 13        | 3.53%   |
| 501-1000       | 11        | 2.99%   |
| 251-300        | 10        | 2.72%   |
| 71-80          | 7         | 1.9%    |
| Unknown        | 7         | 1.9%    |
| 141-150        | 5         | 1.36%   |
| 111-120        | 3         | 0.82%   |
| 61-70          | 2         | 0.54%   |
| 131-140        | 2         | 0.54%   |
| 51-60          | 1         | 0.27%   |
| 41-50          | 1         | 0.27%   |
| 1-40           | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 121       | 34.57%  |
| 121-160       | 93        | 26.57%  |
| 101-120       | 78        | 22.29%  |
| 1-50          | 23        | 6.57%   |
| 161-240       | 20        | 5.71%   |
| More than 240 | 8         | 2.29%   |
| Unknown       | 7         | 2%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 244       | 75.54%  |
| 2     | 57        | 17.65%  |
| 0     | 11        | 3.41%   |
| 3     | 10        | 3.1%    |
| 4     | 1         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 194       | 38.72%  |
| Intel                           | 166       | 33.13%  |
| Qualcomm Atheros                | 38        | 7.58%   |
| Broadcom                        | 27        | 5.39%   |
| MediaTek                        | 15        | 2.99%   |
| TP-Link                         | 10        | 2%      |
| Microsoft                       | 6         | 1.2%    |
| Broadcom Limited                | 5         | 1%      |
| Samsung Electronics             | 4         | 0.8%    |
| Ralink                          | 3         | 0.6%    |
| ASIX Electronics                | 3         | 0.6%    |
| Xiaomi                          | 2         | 0.4%    |
| Ralink Technology               | 2         | 0.4%    |
| Qualcomm                        | 2         | 0.4%    |
| Nvidia                          | 2         | 0.4%    |
| Motorola PCS                    | 2         | 0.4%    |
| Hewlett-Packard                 | 2         | 0.4%    |
| ASUSTek Computer                | 2         | 0.4%    |
| Wacom                           | 1         | 0.2%    |
| T & A Mobile Phones             | 1         | 0.2%    |
| Sierra Wireless                 | 1         | 0.2%    |
| Qualcomm Atheros Communications | 1         | 0.2%    |
| Panasonic (Matsushita)          | 1         | 0.2%    |
| Oculus VR                       | 1         | 0.2%    |
| Marvell Technology Group        | 1         | 0.2%    |
| Linksys                         | 1         | 0.2%    |
| JMicron Technology              | 1         | 0.2%    |
| ICS Advent                      | 1         | 0.2%    |
| Holtek Semiconductor            | 1         | 0.2%    |
| Google                          | 1         | 0.2%    |
| D-Link System                   | 1         | 0.2%    |
| D-Link                          | 1         | 0.2%    |
| Aquantia                        | 1         | 0.2%    |
| Afatech                         | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 151       | 26.03%  |
| Intel Wi-Fi 6 AX200                                               | 30        | 5.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 3.79%   |
| Intel I211 Gigabit Network Connection                             | 19        | 3.28%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 2.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.72%   |
| Intel Ethernet Controller I225-V                                  | 9         | 1.55%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 1.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 8         | 1.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.21%   |
| Intel Wireless 8260                                               | 7         | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 1.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.03%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.03%   |
| Intel Wireless 7265                                               | 6         | 1.03%   |
| Intel Wireless 7260                                               | 6         | 1.03%   |
| Intel Wireless-AC 9260                                            | 5         | 0.86%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4         | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.52%   |
| Microsoft Wireless XBox Controller Dongle                         | 3         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 125       | 48.64%  |
| Realtek Semiconductor           | 41        | 15.95%  |
| Qualcomm Atheros                | 25        | 9.73%   |
| Broadcom                        | 21        | 8.17%   |
| MediaTek                        | 13        | 5.06%   |
| TP-Link                         | 9         | 3.5%    |
| Microsoft                       | 6         | 2.33%   |
| Ralink                          | 3         | 1.17%   |
| Broadcom Limited                | 3         | 1.17%   |
| Ralink Technology               | 2         | 0.78%   |
| ASUSTek Computer                | 2         | 0.78%   |
| Wacom                           | 1         | 0.39%   |
| Sierra Wireless                 | 1         | 0.39%   |
| Qualcomm Atheros Communications | 1         | 0.39%   |
| Panasonic (Matsushita)          | 1         | 0.39%   |
| Linksys                         | 1         | 0.39%   |
| D-Link System                   | 1         | 0.39%   |
| D-Link                          | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 30        | 11.67%  |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 4.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8         | 3.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 2.72%   |
| Intel Wireless 8260                                            | 7         | 2.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 2.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 2.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 2.33%   |
| Intel Wireless 8265 / 8275                                     | 6         | 2.33%   |
| Intel Wireless 7265                                            | 6         | 2.33%   |
| Intel Wireless 7260                                            | 6         | 2.33%   |
| Intel Wireless-AC 9260                                         | 5         | 1.95%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 1.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 4         | 1.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 1.17%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.17%   |
| Microsoft Wireless XBox Controller Dongle                      | 3         | 1.17%   |
| Intel Wireless 3160                                            | 3         | 1.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 1.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.78%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2         | 0.78%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.78%   |
| Realtek 802.11ac NIC                                           | 2         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 181       | 58.01%  |
| Intel                    | 79        | 25.32%  |
| Qualcomm Atheros         | 15        | 4.81%   |
| Broadcom                 | 10        | 3.21%   |
| Samsung Electronics      | 3         | 0.96%   |
| ASIX Electronics         | 3         | 0.96%   |
| Xiaomi                   | 2         | 0.64%   |
| Qualcomm                 | 2         | 0.64%   |
| Nvidia                   | 2         | 0.64%   |
| Motorola PCS             | 2         | 0.64%   |
| MediaTek                 | 2         | 0.64%   |
| Hewlett-Packard          | 2         | 0.64%   |
| Broadcom Limited         | 2         | 0.64%   |
| TP-Link                  | 1         | 0.32%   |
| T & A Mobile Phones      | 1         | 0.32%   |
| Marvell Technology Group | 1         | 0.32%   |
| JMicron Technology       | 1         | 0.32%   |
| ICS Advent               | 1         | 0.32%   |
| Google                   | 1         | 0.32%   |
| Aquantia                 | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 151       | 47.34%  |
| Realtek RTL8125 2.5GbE Controller                                 | 22        | 6.9%    |
| Intel I211 Gigabit Network Connection                             | 19        | 5.96%   |
| Intel Ethernet Controller I225-V                                  | 9         | 2.82%   |
| Intel Ethernet Connection (7) I219-V                              | 9         | 2.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 2.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 1.25%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.94%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.94%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.63%   |
| Motorola PCS moto g(8) plus                                       | 2         | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.63%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.63%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.63%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.63%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.31%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.31%   |
| T & A Mobile Phones A509DL                                        | 1         | 0.31%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.31%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.31%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.31%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.31%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.31%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 293       | 54.06%  |
| WiFi     | 245       | 45.2%   |
| Modem    | 2         | 0.37%   |
| Unknown  | 2         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 173       | 50.44%  |
| WiFi     | 170       | 49.56%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 181       | 56.04%  |
| 1     | 134       | 41.49%  |
| 3     | 6         | 1.86%   |
| 0     | 2         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 225       | 69.02%  |
| Yes  | 101       | 30.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 120       | 52.4%   |
| Realtek Semiconductor           | 19        | 8.3%    |
| Cambridge Silicon Radio         | 17        | 7.42%   |
| Qualcomm Atheros Communications | 10        | 4.37%   |
| IMC Networks                    | 10        | 4.37%   |
| Broadcom                        | 10        | 4.37%   |
| Apple                           | 9         | 3.93%   |
| Foxconn / Hon Hai               | 8         | 3.49%   |
| Lite-On Technology              | 7         | 3.06%   |
| MediaTek                        | 4         | 1.75%   |
| TP-Link                         | 3         | 1.31%   |
| ASUSTek Computer                | 3         | 1.31%   |
| Edimax Technology               | 2         | 0.87%   |
| Toshiba                         | 1         | 0.44%   |
| Realtek                         | 1         | 0.44%   |
| Ralink                          | 1         | 0.44%   |
| Integrated System Solution      | 1         | 0.44%   |
| Foxconn International           | 1         | 0.44%   |
| Dell                            | 1         | 0.44%   |
| Unknown                         | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 34        | 14.85%  |
| Intel AX200 Bluetooth                                   | 31        | 13.54%  |
| Intel AX201 Bluetooth                                   | 24        | 10.48%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 17        | 7.42%   |
| Realtek Bluetooth Radio                                 | 16        | 6.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 10        | 4.37%   |
| Intel AX210 Bluetooth                                   | 6         | 2.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 5         | 2.18%   |
| IMC Networks Wireless_Device                            | 5         | 2.18%   |
| Apple Bluetooth Host Controller                         | 5         | 2.18%   |
| MediaTek Wireless_Device                                | 4         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                        | 4         | 1.75%   |
| Intel Bluetooth Device                                  | 4         | 1.75%   |
| IMC Networks Bluetooth Radio                            | 4         | 1.75%   |
| TP-Link TPuLink UB500 Adapter                           | 3         | 1.31%   |
| Qualcomm Atheros  Bluetooth Device                      | 3         | 1.31%   |
| Foxconn / Hon Hai Wireless_Device                       | 3         | 1.31%   |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 3         | 1.31%   |
| ASUS ASUS USB-BT500                                     | 3         | 1.31%   |
| Realtek  Bluetooth 4.2 Adapter                          | 2         | 0.87%   |
| Qualcomm Atheros Bluetooth USB Host Controller          | 2         | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 2         | 0.87%   |
| Lite-On Bluetooth Device                                | 2         | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                        | 2         | 0.87%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth           | 2         | 0.87%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 2         | 0.87%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                    | 2         | 0.87%   |
| Apple Bluetooth USB Host Controller                     | 2         | 0.87%   |
| Toshiba Askey Bluetooth Module                          | 1         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                 | 1         | 0.44%   |
| Realtek 802.11ac WLAN Adapter                           | 1         | 0.44%   |
| Ralink RT3290 Bluetooth                                 | 1         | 0.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 1         | 0.44%   |
| Qualcomm Atheros AR9462 Bluetooth                       | 1         | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1         | 0.44%   |
| Lite-On Wireless_Device                                 | 1         | 0.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 0.44%   |
| Lite-On Bluetooth Radio                                 | 1         | 0.44%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 1         | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter        | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 183       | 32.05%  |
| AMD                      | 161       | 28.2%   |
| Nvidia                   | 128       | 22.42%  |
| C-Media Electronics      | 19        | 3.33%   |
| Logitech                 | 13        | 2.28%   |
| SteelSeries ApS          | 5         | 0.88%   |
| Razer USA                | 5         | 0.88%   |
| Plantronics              | 5         | 0.88%   |
| ASUSTek Computer         | 5         | 0.88%   |
| Kingston Technology      | 3         | 0.53%   |
| JMTek                    | 3         | 0.53%   |
| Focusrite-Novation       | 3         | 0.53%   |
| Creative Labs            | 3         | 0.53%   |
| Blue Microphones         | 3         | 0.53%   |
| TTGK Technology          | 2         | 0.35%   |
| Sony                     | 2         | 0.35%   |
| Samson Technologies      | 2         | 0.35%   |
| Realtek Semiconductor    | 2         | 0.35%   |
| Generalplus Technology   | 2         | 0.35%   |
| Creative Technology      | 2         | 0.35%   |
| Corsair                  | 2         | 0.35%   |
| Audio-Technica           | 2         | 0.35%   |
| Asahi Kasei Microsystems | 2         | 0.35%   |
| Texas Instruments        | 1         | 0.18%   |
| Tenx Technology          | 1         | 0.18%   |
| SAVITECH                 | 1         | 0.18%   |
| Samsung Electronics      | 1         | 0.18%   |
| ROCCAT                   | 1         | 0.18%   |
| Positive Grid            | 1         | 0.18%   |
| Micro Star International | 1         | 0.18%   |
| MCS                      | 1         | 0.18%   |
| Hewlett-Packard          | 1         | 0.18%   |
| Giga-Byte Technology     | 1         | 0.18%   |
| Elgato Systems           | 1         | 0.18%   |
| Cambridge Silicon Radio  | 1         | 0.18%   |
| Astro Gaming             | 1         | 0.18%   |
| AKAI Professional M.I.   | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 51        | 7.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 38        | 5.49%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 29        | 4.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 26        | 3.76%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 2.75%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 2.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 2.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 15        | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15        | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14        | 2.02%   |
| Nvidia GA104 High Definition Audio Controller                              | 13        | 1.88%   |
| Intel Sunrise Point-LP HD Audio                                            | 13        | 1.88%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 1.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13        | 1.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 12        | 1.73%   |
| Intel Haswell-ULT HD Audio Controller                                      | 12        | 1.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12        | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 1.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 10        | 1.45%   |
| Nvidia GA106 High Definition Audio Controller                              | 10        | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 1.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9         | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 1.16%   |
| Nvidia TU104 HD Audio Controller                                           | 8         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 1.01%   |
| Nvidia GA102 High Definition Audio Controller                              | 7         | 1.01%   |
| AMD Navi 10 HDMI Audio                                                     | 7         | 1.01%   |
| AMD FCH Azalia Controller                                                  | 7         | 1.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.72%   |
| Logitech PRO X Wireless Gaming Headset                                     | 5         | 0.72%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.72%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5         | 0.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 0.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5         | 0.72%   |
| C-Media Electronics USB Audio Device                                       | 5         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 30.77%  |
| Micron Technology   | 11        | 14.1%   |
| SK hynix            | 10        | 12.82%  |
| Corsair             | 8         | 10.26%  |
| Kingston            | 6         | 7.69%   |
| G.Skill             | 4         | 5.13%   |
| Crucial             | 3         | 3.85%   |
| Unknown (ABCD)      | 2         | 2.56%   |
| Unknown             | 2         | 2.56%   |
| Team                | 2         | 2.56%   |
| Transcend           | 1         | 1.28%   |
| Ramaxel Technology  | 1         | 1.28%   |
| Nanya Technology    | 1         | 1.28%   |
| Hewlett-Packard     | 1         | 1.28%   |
| Elpida              | 1         | 1.28%   |
| Asgard              | 1         | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 3.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 2.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 2.41%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 2         | 2.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 2.41%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 1.2%    |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s           | 1         | 1.2%    |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 1.2%    |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 1.2%    |
| Team RAM TEAMGROUP-UD3 8192MB DIMM DDR3 1600MT/s                 | 1         | 1.2%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 1.2%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.2%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.2%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.2%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.2%    |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.2%    |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.2%    |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.2%    |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.2%    |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 1         | 1.2%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.2%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.2%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.2%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.2%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.2%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 1         | 1.2%    |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.2%    |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM DDR 975MT/s             | 1         | 1.2%    |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s              | 1         | 1.2%    |
| Samsung RAM M3 78T2863QZS-CF7 1024MB DIMM DDR2 800MT/s           | 1         | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 42        | 65.63%  |
| DDR3    | 13        | 20.31%  |
| LPDDR4  | 4         | 6.25%   |
| DDR5    | 2         | 3.13%   |
| SDRAM   | 1         | 1.56%   |
| DDR2    | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 51.52%  |
| DIMM         | 26        | 39.39%  |
| Row Of Chips | 6         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 40        | 57.97%  |
| 4096  | 12        | 17.39%  |
| 16384 | 7         | 10.14%  |
| 2048  | 5         | 7.25%   |
| 32768 | 4         | 5.8%    |
| 1024  | 1         | 1.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 20        | 28.17%  |
| 1600  | 10        | 14.08%  |
| 2667  | 6         | 8.45%   |
| 2400  | 6         | 8.45%   |
| 3600  | 4         | 5.63%   |
| 3266  | 3         | 4.23%   |
| 4800  | 2         | 2.82%   |
| 3866  | 2         | 2.82%   |
| 3466  | 2         | 2.82%   |
| 2933  | 2         | 2.82%   |
| 2133  | 2         | 2.82%   |
| 1333  | 2         | 2.82%   |
| 6400  | 1         | 1.41%   |
| 4267  | 1         | 1.41%   |
| 4266  | 1         | 1.41%   |
| 3800  | 1         | 1.41%   |
| 3733  | 1         | 1.41%   |
| 3000  | 1         | 1.41%   |
| 2800  | 1         | 1.41%   |
| 1066  | 1         | 1.41%   |
| 975   | 1         | 1.41%   |
| 800   | 1         | 1.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 2         | 50%     |
| Brother Industries | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Canon TR4500 series        | 1         | 25%     |
| Canon PIXMA MX370 Series   | 1         | 25%     |
| Brother MFC-L2710DN series | 1         | 25%     |
| Brother HL-L2370DW series  | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP ScanJet 2400c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 18.13%  |
| IMC Networks                           | 22        | 12.87%  |
| Logitech                               | 18        | 10.53%  |
| Apple                                  | 13        | 7.6%    |
| Acer                                   | 12        | 7.02%   |
| Microdia                               | 9         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.26%   |
| Realtek Semiconductor                  | 7         | 4.09%   |
| Sunplus Innovation Technology          | 6         | 3.51%   |
| Syntek                                 | 5         | 2.92%   |
| Quanta                                 | 5         | 2.92%   |
| Suyin                                  | 4         | 2.34%   |
| Sonix Technology                       | 4         | 2.34%   |
| Luxvisions Innotech Limited            | 4         | 2.34%   |
| Lite-On Technology                     | 3         | 1.75%   |
| SunplusIT                              | 2         | 1.17%   |
| Samsung Electronics                    | 2         | 1.17%   |
| Microsoft                              | 2         | 1.17%   |
| Hewlett-Packard                        | 2         | 1.17%   |
| Z-Star Microelectronics                | 1         | 0.58%   |
| Tobii Technology AB                    | 1         | 0.58%   |
| Silicon Motion                         | 1         | 0.58%   |
| Owon                                   | 1         | 0.58%   |
| Lenovo                                 | 1         | 0.58%   |
| Intel                                  | 1         | 0.58%   |
| Importek                               | 1         | 0.58%   |
| HD WEBCAM                              | 1         | 0.58%   |
| Goodong Industry                       | 1         | 0.58%   |
| ARC International                      | 1         | 0.58%   |
| ANYKA                                  | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 6.9%    |
| Chicony Integrated Camera                           | 7         | 4.02%   |
| Logitech C922 Pro Stream Webcam                     | 5         | 2.87%   |
| Apple iPhone 5/5C/5S/6/SE                           | 5         | 2.87%   |
| Syntek Integrated Camera                            | 4         | 2.3%    |
| Microdia Integrated_Webcam_HD                       | 4         | 2.3%    |
| IMC Networks Integrated Camera                      | 4         | 2.3%    |
| Acer Integrated Camera                              | 4         | 2.3%    |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.72%   |
| Realtek USB Camera                                  | 3         | 1.72%   |
| Logitech Webcam C270                                | 3         | 1.72%   |
| Logitech HD Pro Webcam C920                         | 3         | 1.72%   |
| Chicony HP Truevision HD                            | 3         | 1.72%   |
| Chicony HD WebCam                                   | 3         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 1.72%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 1.72%   |
| Acer HD Webcam                                      | 3         | 1.72%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.15%   |
| Samsung Galaxy A5 (MTP)                             | 2         | 1.15%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.15%   |
| Microdia Integrated Camera                          | 2         | 1.15%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.15%   |
| Logitech StreamCam                                  | 2         | 1.15%   |
| Logitech QuickCam Pro 9000                          | 2         | 1.15%   |
| Lite-On HP HD Camera                                | 2         | 1.15%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.15%   |
| Chicony USB2.0 Camera                               | 2         | 1.15%   |
| Chicony USB 2.0 Camera                              | 2         | 1.15%   |
| Chicony EasyCamera                                  | 2         | 1.15%   |
| Cheng Uei Precision Industry (Foxlink) HP IR Camera | 2         | 1.15%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 1.15%   |
| Apple FaceTime HD Camera                            | 2         | 1.15%   |
| Apple Built-in iSight                               | 2         | 1.15%   |
| Acer Lenovo Integrated Webcam                       | 2         | 1.15%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.57%   |
| Tobii AB EyeChip                                    | 1         | 0.57%   |
| Syntek EasyCamera                                   | 1         | 0.57%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.57%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.57%   |
| Suyin HP Truevision HD                              | 1         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 11        | 44%     |
| Synaptics                          | 7         | 28%     |
| Shenzhen Goodix Technology         | 3         | 12%     |
| Elan Microelectronics              | 3         | 12%     |
| Realtek USB2.0 Finger Print Bridge | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 20%     |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 12%     |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 8%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 2         | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 8%      |
| Elan ELAN:ARM-M4                                                | 2         | 8%      |
| Validity Sensors Synaptics WBDI                                 | 1         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 4%      |
| Synaptics WBDI Device                                           | 1         | 4%      |
| Synaptics  WBDI                                                 | 1         | 4%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 4%      |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 4%      |
| Elan ELAN:Fingerprint                                           | 1         | 4%      |
| Unknown                                                         | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 3         | 60%     |
| Realtek Semiconductor | 1         | 20%     |
| Broadcom              | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 60%     |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 249       | 75.91%  |
| 1     | 63        | 19.21%  |
| 2     | 15        | 4.57%   |
| 3     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 25        | 26.6%   |
| Net/wireless             | 24        | 25.53%  |
| Graphics card            | 22        | 23.4%   |
| Multimedia controller    | 15        | 15.96%  |
| Unassigned class         | 2         | 2.13%   |
| Bluetooth                | 2         | 2.13%   |
| Sound                    | 1         | 1.06%   |
| Modem                    | 1         | 1.06%   |
| Communication controller | 1         | 1.06%   |
| Chipcard                 | 1         | 1.06%   |

