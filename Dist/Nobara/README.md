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

Total: 358

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Nobara 36 | 240       | 85.71%  |
| Nobara 37 | 40        | 14.29%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Nobara | 277       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                                  | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64                                   | 35        | 12.07%  |
| 5.19.14-201.fsync.fc36.x86_64                            | 24        | 8.28%   |
| 6.0.14-201.fsync.fc36.x86_64                             | 23        | 7.93%   |
| 5.19.9-201.fsync.fc36.x86_64                             | 16        | 5.52%   |
| 5.19.7-204.fsync.fc36.x86_64                             | 15        | 5.17%   |
| 6.0.7-201.fsync.fc36.x86_64                              | 12        | 4.14%   |
| 5.19.16-201.fsync.fc36.x86_64                            | 12        | 4.14%   |
| 6.1.4-203.fsync.fc37.x86_64                              | 11        | 3.79%   |
| 6.0.5-201.fsync.fc36.x86_64                              | 11        | 3.79%   |
| 5.18.13-201.fsync.fc36.x86_64                            | 11        | 3.79%   |
| 6.0.9-201.fc36.x86_64                                    | 9         | 3.1%    |
| 6.1.6-203.fsync.fc37.x86_64                              | 8         | 2.76%   |
| 6.0.16-301.fsync.fc37.x86_64                             | 8         | 2.76%   |
| 5.19.12-201.fsync.fc36.x86_64                            | 8         | 2.76%   |
| 5.19.10-201.fsync.fc36.x86_64                            | 8         | 2.76%   |
| 5.19.4-201.fsync.fc36.x86_64                             | 7         | 2.41%   |
| 5.18.16-201.fsync.fc36.x86_64                            | 7         | 2.41%   |
| 5.19.15-202.fsync.fc36.x86_64                            | 6         | 2.07%   |
| 5.19.11-201.fsync.fc36.x86_64                            | 6         | 2.07%   |
| 5.18.17-201.fsync.fc36.x86_64                            | 6         | 2.07%   |
| 6.1.6-201.fsync.fc37.x86_64                              | 4         | 1.38%   |
| 6.0.9-202.fc36.x86_64                                    | 4         | 1.38%   |
| 6.0.8-201.fsync.fc36.x86_64                              | 4         | 1.38%   |
| 6.0.7-202.fsync.fc36.x86_64                              | 4         | 1.38%   |
| 5.19.8-201.fsync.fc36.x86_64                             | 4         | 1.38%   |
| 5.18.19-201.fsync.fc36.x86_64                            | 4         | 1.38%   |
| 5.18.11-201.fsync.fc36.x86_64                            | 3         | 1.03%   |
| 6.1.6-202.fsync.fc37.x86_64                              | 2         | 0.69%   |
| 6.0.18-301.fsync.fc37.x86_64                             | 2         | 0.69%   |
| 6.0.15-301.fsync.fc37.x86_64                             | 2         | 0.69%   |
| 5.19.7-203.fsync.fc36.x86_64                             | 2         | 0.69%   |
| 5.19.13-202.fsync.fc36.x86_64                            | 2         | 0.69%   |
| 5.18.18-201.fsync.fc36.x86_64                            | 2         | 0.69%   |
| 6.2.0-0.rc3.20230109git1fe4fd6f5cad.24.fsync.fc37.x86_64 | 1         | 0.34%   |
| 6.1.8-201.fsync.fc37.x86_64                              | 1         | 0.34%   |
| 6.1.8-200.fsync.fc37.x86_64                              | 1         | 0.34%   |
| 6.0.2-xm1.0.fc36.x86_64                                  | 1         | 0.34%   |
| 6.0.13-201.fsync.fc36.x86_64                             | 1         | 0.34%   |
| 5.19.2-602.inttf.fc36.x86_64                             | 1         | 0.34%   |
| 5.19.13-201.fsync.fc36.x86_64                            | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.10  | 35        | 12.07%  |
| 5.19.14 | 24        | 8.28%   |
| 6.0.14  | 23        | 7.93%   |
| 5.19.7  | 17        | 5.86%   |
| 6.0.7   | 16        | 5.52%   |
| 5.19.9  | 16        | 5.52%   |
| 6.1.6   | 14        | 4.83%   |
| 6.0.9   | 13        | 4.48%   |
| 5.19.16 | 12        | 4.14%   |
| 6.1.4   | 11        | 3.79%   |
| 6.0.5   | 11        | 3.79%   |
| 5.18.13 | 11        | 3.79%   |
| 6.0.16  | 8         | 2.76%   |
| 5.19.12 | 8         | 2.76%   |
| 5.19.10 | 8         | 2.76%   |
| 5.19.4  | 7         | 2.41%   |
| 5.18.16 | 7         | 2.41%   |
| 5.19.15 | 6         | 2.07%   |
| 5.19.11 | 6         | 2.07%   |
| 5.18.17 | 6         | 2.07%   |
| 6.0.8   | 4         | 1.38%   |
| 5.19.8  | 4         | 1.38%   |
| 5.18.19 | 4         | 1.38%   |
| 5.19.13 | 3         | 1.03%   |
| 5.18.11 | 3         | 1.03%   |
| 6.1.8   | 2         | 0.69%   |
| 6.0.18  | 2         | 0.69%   |
| 6.0.15  | 2         | 0.69%   |
| 5.18.18 | 2         | 0.69%   |
| 6.2.0   | 1         | 0.34%   |
| 6.0.2   | 1         | 0.34%   |
| 6.0.13  | 1         | 0.34%   |
| 5.19.2  | 1         | 0.34%   |
| 5.18.9  | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 114       | 39.58%  |
| 5.19    | 112       | 38.89%  |
| 5.18    | 34        | 11.81%  |
| 6.1     | 27        | 9.38%   |
| 6.2     | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 277       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 206       | 74.1%   |
| KDE5          | 65        | 23.38%  |
| Unknown       | 4         | 1.44%   |
| GNOME Classic | 2         | 0.72%   |
| X-Cinnamon    | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 214       | 75.35%  |
| X11     | 66        | 23.24%  |
| Unknown | 4         | 1.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 235       | 83.93%  |
| GDM     | 28        | 10%     |
| SDDM    | 15        | 5.36%   |
| LightDM | 2         | 0.71%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 155       | 55.56%  |
| en_GB   | 16        | 5.73%   |
| es_ES   | 9         | 3.23%   |
| de_DE   | 9         | 3.23%   |
| es_MX   | 8         | 2.87%   |
| es_AR   | 8         | 2.87%   |
| en_CA   | 8         | 2.87%   |
| pl_PL   | 7         | 2.51%   |
| ru_RU   | 5         | 1.79%   |
| fr_FR   | 5         | 1.79%   |
| pt_BR   | 4         | 1.43%   |
| pt_PT   | 3         | 1.08%   |
| nl_NL   | 3         | 1.08%   |
| it_IT   | 3         | 1.08%   |
| es_CO   | 3         | 1.08%   |
| en_NZ   | 3         | 1.08%   |
| en_IN   | 3         | 1.08%   |
| en_AU   | 3         | 1.08%   |
| de_AT   | 3         | 1.08%   |
| Unknown | 3         | 1.08%   |
| sv_SE   | 2         | 0.72%   |
| fi_FI   | 2         | 0.72%   |
| tr_TR   | 1         | 0.36%   |
| sk_SK   | 1         | 0.36%   |
| nb_NO   | 1         | 0.36%   |
| hu_HU   | 1         | 0.36%   |
| hr_HR   | 1         | 0.36%   |
| es_GT   | 1         | 0.36%   |
| es_EC   | 1         | 0.36%   |
| es_CR   | 1         | 0.36%   |
| es_CL   | 1         | 0.36%   |
| en_ZA   | 1         | 0.36%   |
| en_PH   | 1         | 0.36%   |
| en_IE   | 1         | 0.36%   |
| cs_CZ   | 1         | 0.36%   |
| C       | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 218       | 78.42%  |
| BIOS | 60        | 21.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 160       | 57.55%  |
| Ext4  | 116       | 41.73%  |
| Xfs   | 2         | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 232       | 82.56%  |
| GPT     | 43        | 15.3%   |
| MBR     | 6         | 2.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 264       | 94.96%  |
| Yes       | 14        | 5.04%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 253       | 91.34%  |
| Yes       | 24        | 8.66%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 69        | 24.91%  |
| Lenovo              | 35        | 12.64%  |
| MSI                 | 34        | 12.27%  |
| Hewlett-Packard     | 33        | 11.91%  |
| Gigabyte Technology | 22        | 7.94%   |
| Dell                | 17        | 6.14%   |
| ASRock              | 15        | 5.42%   |
| Apple               | 11        | 3.97%   |
| Acer                | 7         | 2.53%   |
| Toshiba             | 3         | 1.08%   |
| Intel               | 3         | 1.08%   |
| Alienware           | 3         | 1.08%   |
| Positivo            | 2         | 0.72%   |
| Notebook            | 2         | 0.72%   |
| Biostar             | 2         | 0.72%   |
| AZW                 | 2         | 0.72%   |
| ZOTAC               | 1         | 0.36%   |
| Valve               | 1         | 0.36%   |
| Samsung Electronics | 1         | 0.36%   |
| Razer               | 1         | 0.36%   |
| OEM                 | 1         | 0.36%   |
| Monster             | 1         | 0.36%   |
| Medion              | 1         | 0.36%   |
| HUAWEI              | 1         | 0.36%   |
| Gateway             | 1         | 0.36%   |
| Fujitsu             | 1         | 0.36%   |
| EVOO                | 1         | 0.36%   |
| eMachines           | 1         | 0.36%   |
| ECS                 | 1         | 0.36%   |
| Dynabook            | 1         | 0.36%   |
| Coradir             | 1         | 0.36%   |
| Casper              | 1         | 0.36%   |
| Unknown             | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| MSI MS-7C91                    | 4         | 1.44%   |
| MSI MS-7B86                    | 4         | 1.44%   |
| MSI MS-7C37                    | 3         | 1.08%   |
| ASUS PRIME A320M-K             | 3         | 1.08%   |
| Unknown                        | 3         | 1.08%   |
| MSI MS-7C02                    | 2         | 0.72%   |
| MSI MS-7693                    | 2         | 0.72%   |
| Lenovo Legion 5 15ARH05 82B5   | 2         | 0.72%   |
| Lenovo IdeaPad Y700-15ISK 80NV | 2         | 0.72%   |
| Gigabyte Z590I VISION D        | 2         | 0.72%   |
| Gigabyte B450M DS3H            | 2         | 0.72%   |
| Dell OptiPlex 390              | 2         | 0.72%   |
| ASUS ROG CROSSHAIR VIII HERO   | 2         | 0.72%   |
| ZOTAC ZBOX-CI320NANO series    | 1         | 0.36%   |
| Valve Jupiter                  | 1         | 0.36%   |
| Toshiba TECRA A50-A            | 1         | 0.36%   |
| Toshiba Satellite L850         | 1         | 0.36%   |
| Toshiba Satellite L650         | 1         | 0.36%   |
| Samsung R520/R522/R620         | 1         | 0.36%   |
| Razer Blade                    | 1         | 0.36%   |
| Positivo N1250                 | 1         | 0.36%   |
| Positivo N1240                 | 1         | 0.36%   |
| OEM SHARKBAY                   | 1         | 0.36%   |
| Notebook P7xxDM2(-G)           | 1         | 0.36%   |
| Notebook NP5x_NP6x_NP7xHP      | 1         | 0.36%   |
| MSI Pulse GL76 12UEK           | 1         | 0.36%   |
| MSI MS-7D53                    | 1         | 0.36%   |
| MSI MS-7D41                    | 1         | 0.36%   |
| MSI MS-7D25                    | 1         | 0.36%   |
| MSI MS-7D17                    | 1         | 0.36%   |
| MSI MS-7C84                    | 1         | 0.36%   |
| MSI MS-7C75                    | 1         | 0.36%   |
| MSI MS-7C35                    | 1         | 0.36%   |
| MSI MS-7B79                    | 1         | 0.36%   |
| MSI MS-7B51                    | 1         | 0.36%   |
| MSI MS-7B50                    | 1         | 0.36%   |
| MSI MS-7B17                    | 1         | 0.36%   |
| MSI MS-7A34                    | 1         | 0.36%   |
| MSI MS-7811                    | 1         | 0.36%   |
| MSI MS-7721                    | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| ASUS ROG             | 18        | 6.5%    |
| ASUS PRIME           | 13        | 4.69%   |
| Lenovo IdeaPad       | 10        | 3.61%   |
| ASUS TUF             | 9         | 3.25%   |
| Lenovo ThinkPad      | 7         | 2.53%   |
| Lenovo Legion        | 6         | 2.17%   |
| HP Pavilion          | 6         | 2.17%   |
| HP EliteBook         | 5         | 1.81%   |
| Dell Precision       | 5         | 1.81%   |
| ASUS VivoBook        | 5         | 1.81%   |
| MSI MS-7C91          | 4         | 1.44%   |
| MSI MS-7B86          | 4         | 1.44%   |
| Dell OptiPlex        | 4         | 1.44%   |
| Acer Aspire          | 4         | 1.44%   |
| MSI MS-7C37          | 3         | 1.08%   |
| Lenovo ThinkCentre   | 3         | 1.08%   |
| HP ZBook             | 3         | 1.08%   |
| HP ENVY              | 3         | 1.08%   |
| HP EliteDesk         | 3         | 1.08%   |
| ASUS ASUS            | 3         | 1.08%   |
| Unknown              | 3         | 1.08%   |
| Toshiba Satellite    | 2         | 0.72%   |
| MSI MS-7C02          | 2         | 0.72%   |
| MSI MS-7693          | 2         | 0.72%   |
| Lenovo G580          | 2         | 0.72%   |
| HP OMEN              | 2         | 0.72%   |
| HP Laptop            | 2         | 0.72%   |
| HP Compaq            | 2         | 0.72%   |
| Gigabyte Z590I       | 2         | 0.72%   |
| Gigabyte X570        | 2         | 0.72%   |
| Gigabyte B450M       | 2         | 0.72%   |
| Gigabyte B450        | 2         | 0.72%   |
| Dell G15             | 2         | 0.72%   |
| ASUS M5A97           | 2         | 0.72%   |
| ASRock X570          | 2         | 0.72%   |
| Apple MacBookPro8    | 2         | 0.72%   |
| Acer Swift           | 2         | 0.72%   |
| ZOTAC ZBOX-CI320NANO | 1         | 0.36%   |
| Valve Jupiter        | 1         | 0.36%   |
| Toshiba TECRA        | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 43        | 15.52%  |
| 2019 | 40        | 14.44%  |
| 2020 | 30        | 10.83%  |
| 2018 | 25        | 9.03%   |
| 2013 | 21        | 7.58%   |
| 2022 | 20        | 7.22%   |
| 2017 | 19        | 6.86%   |
| 2014 | 19        | 6.86%   |
| 2012 | 17        | 6.14%   |
| 2011 | 13        | 4.69%   |
| 2016 | 12        | 4.33%   |
| 2015 | 8         | 2.89%   |
| 2009 | 5         | 1.81%   |
| 2008 | 3         | 1.08%   |
| 2010 | 2         | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 137       | 49.46%  |
| Notebook    | 128       | 46.21%  |
| Mini pc     | 5         | 1.81%   |
| Convertible | 3         | 1.08%   |
| All in one  | 3         | 1.08%   |
| Tablet      | 1         | 0.36%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 277       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 277       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 82        | 29.6%   |
| 8.01-16.0   | 58        | 20.94%  |
| 32.01-64.0  | 52        | 18.77%  |
| 4.01-8.0    | 46        | 16.61%  |
| 3.01-4.0    | 27        | 9.75%   |
| 24.01-32.0  | 7         | 2.53%   |
| 64.01-256.0 | 4         | 1.44%   |
| 1.01-2.0    | 1         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 135       | 47.37%  |
| 3.01-4.0   | 65        | 22.81%  |
| 2.01-3.0   | 49        | 17.19%  |
| 8.01-16.0  | 29        | 10.18%  |
| 1.01-2.0   | 4         | 1.4%    |
| 16.01-24.0 | 2         | 0.7%    |
| 24.01-32.0 | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 135       | 48.21%  |
| 2      | 73        | 26.07%  |
| 3      | 42        | 15%     |
| 5      | 15        | 5.36%   |
| 4      | 11        | 3.93%   |
| 6      | 2         | 0.71%   |
| 10     | 1         | 0.36%   |
| 7      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 221       | 79.78%  |
| Yes       | 56        | 20.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 88.49%  |
| No        | 32        | 11.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 212       | 76.53%  |
| No        | 65        | 23.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 68.35%  |
| No        | 88        | 31.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 85        | 30.69%  |
| Germany      | 15        | 5.42%   |
| Poland       | 11        | 3.97%   |
| Canada       | 11        | 3.97%   |
| UK           | 10        | 3.61%   |
| Argentina    | 10        | 3.61%   |
| Mexico       | 9         | 3.25%   |
| Spain        | 8         | 2.89%   |
| France       | 8         | 2.89%   |
| Russia       | 7         | 2.53%   |
| Brazil       | 7         | 2.53%   |
| India        | 5         | 1.81%   |
| Chile        | 5         | 1.81%   |
| Sweden       | 4         | 1.44%   |
| Portugal     | 4         | 1.44%   |
| Philippines  | 4         | 1.44%   |
| Netherlands  | 4         | 1.44%   |
| Italy        | 4         | 1.44%   |
| Colombia     | 4         | 1.44%   |
| Austria      | 4         | 1.44%   |
| Serbia       | 3         | 1.08%   |
| Norway       | 3         | 1.08%   |
| New Zealand  | 3         | 1.08%   |
| Indonesia    | 3         | 1.08%   |
| Hungary      | 3         | 1.08%   |
| Croatia      | 3         | 1.08%   |
| Australia    | 3         | 1.08%   |
| Vietnam      | 2         | 0.72%   |
| South Africa | 2         | 0.72%   |
| Romania      | 2         | 0.72%   |
| Finland      | 2         | 0.72%   |
| Egypt        | 2         | 0.72%   |
| Czechia      | 2         | 0.72%   |
| Belgium      | 2         | 0.72%   |
| Venezuela    | 1         | 0.36%   |
| Ukraine      | 1         | 0.36%   |
| Turkey       | 1         | 0.36%   |
| Taiwan       | 1         | 0.36%   |
| South Korea  | 1         | 0.36%   |
| Slovakia     | 1         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Guadalajara   | 4         | 1.4%    |
| Buenos Aires  | 3         | 1.05%   |
| Atlanta       | 3         | 1.05%   |
| Wroclaw       | 2         | 0.7%    |
| Wasilla       | 2         | 0.7%    |
| Warsaw        | 2         | 0.7%    |
| Villa Nueva   | 2         | 0.7%    |
| Valladolid    | 2         | 0.7%    |
| Schmalkalden  | 2         | 0.7%    |
| Sao Paulo     | 2         | 0.7%    |
| San José     | 2         | 0.7%    |
| San Antonio   | 2         | 0.7%    |
| Rotterdam     | 2         | 0.7%    |
| Rome          | 2         | 0.7%    |
| Poznan        | 2         | 0.7%    |
| Plano         | 2         | 0.7%    |
| Philadelphia  | 2         | 0.7%    |
| Panama City   | 2         | 0.7%    |
| Ochsenfurt    | 2         | 0.7%    |
| Melbourne     | 2         | 0.7%    |
| Mansfield     | 2         | 0.7%    |
| Johannesburg  | 2         | 0.7%    |
| Fortaleza     | 2         | 0.7%    |
| Fairbanks     | 2         | 0.7%    |
| Berlin        | 2         | 0.7%    |
| Belgrade      | 2         | 0.7%    |
| Auckland      | 2         | 0.7%    |
| Zamora        | 1         | 0.35%   |
| Zagreb        | 1         | 0.35%   |
| Zadar         | 1         | 0.35%   |
| Wooster       | 1         | 0.35%   |
| Wiesbaden     | 1         | 0.35%   |
| Wesley Chapel | 1         | 0.35%   |
| Wellington    | 1         | 0.35%   |
| Wayne         | 1         | 0.35%   |
| Waldorf       | 1         | 0.35%   |
| Wabrzezno     | 1         | 0.35%   |
| Vouziers      | 1         | 0.35%   |
| Vladivostok   | 1         | 0.35%   |
| Vineland      | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 89        | 129    | 18.39%  |
| WDC                          | 65        | 90     | 13.43%  |
| Seagate                      | 53        | 69     | 10.95%  |
| Toshiba                      | 33        | 35     | 6.82%   |
| Kingston                     | 33        | 35     | 6.82%   |
| Crucial                      | 29        | 36     | 5.99%   |
| Sandisk                      | 25        | 26     | 5.17%   |
| Intel                        | 16        | 21     | 3.31%   |
| Phison Electronics           | 12        | 13     | 2.48%   |
| SK hynix                     | 9         | 9      | 1.86%   |
| Micron Technology            | 9         | 9      | 1.86%   |
| Micron/Crucial Technology    | 8         | 8      | 1.65%   |
| Hitachi                      | 8         | 9      | 1.65%   |
| China                        | 8         | 8      | 1.65%   |
| Apple                        | 8         | 9      | 1.65%   |
| PNY                          | 7         | 11     | 1.45%   |
| Phison                       | 6         | 7      | 1.24%   |
| ADATA Technology             | 5         | 5      | 1.03%   |
| KIOXIA                       | 4         | 4      | 0.83%   |
| HGST                         | 4         | 4      | 0.83%   |
| A-DATA Technology            | 4         | 4      | 0.83%   |
| Unknown                      | 3         | 3      | 0.62%   |
| SPCC                         | 3         | 3      | 0.62%   |
| Realtek Semiconductor        | 3         | 3      | 0.62%   |
| Unknown                      | 3         | 4      | 0.62%   |
| Transcend                    | 2         | 2      | 0.41%   |
| Team                         | 2         | 2      | 0.41%   |
| Silicon Motion               | 2         | 2      | 0.41%   |
| Mushkin                      | 2         | 2      | 0.41%   |
| LITEON                       | 2         | 2      | 0.41%   |
| Kingston Technology Company  | 2         | 2      | 0.41%   |
| HS-SSD-C100                  | 2         | 2      | 0.41%   |
| XPG                          | 1         | 1      | 0.21%   |
| Verbatim                     | 1         | 1      | 0.21%   |
| USB3.0                       | 1         | 1      | 0.21%   |
| SuperSSpeed                  | 1         | 1      | 0.21%   |
| Solid State Storage          | 1         | 1      | 0.21%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.21%   |
| Ramsta                       | 1         | 1      | 0.21%   |
| PNY CS90                     | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 14        | 2.55%   |
| Kingston SA400S37240G 240GB SSD                      | 12        | 2.19%   |
| Phison E12 NVMe Controller 1TB                       | 8         | 1.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 7         | 1.28%   |
| Intel SSD 660P Series 512GB                          | 7         | 1.28%   |
| Crucial CT1000MX500SSD1 1TB                          | 7         | 1.28%   |
| Samsung SSD 860 EVO 500GB                            | 6         | 1.09%   |
| Samsung SSD 850 EVO 250GB                            | 6         | 1.09%   |
| Toshiba HDWD110 1TB                                  | 5         | 0.91%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 5         | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 4         | 0.73%   |
| Toshiba DT01ACA100 1TB                               | 4         | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB                       | 4         | 0.73%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 4         | 0.73%   |
| Samsung SSD 850 EVO 500GB                            | 4         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 4         | 0.73%   |
| WDC WDBNCE5000PNC 500GB SSD                          | 3         | 0.55%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 3         | 0.55%   |
| Toshiba MQ04ABF100 1TB                               | 3         | 0.55%   |
| Toshiba MQ01ABD100 1TB                               | 3         | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB                       | 3         | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB                       | 3         | 0.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB       | 3         | 0.55%   |
| SanDisk SSD PLUS 240GB                               | 3         | 0.55%   |
| Samsung SSD 980 500GB                                | 3         | 0.55%   |
| Samsung SSD 980 1TB                                  | 3         | 0.55%   |
| Samsung SSD 860 EVO 1TB                              | 3         | 0.55%   |
| Phison PS5013 E13 NVMe Controller 256GB              | 3         | 0.55%   |
| Kingston SA400S37120G 120GB SSD                      | 3         | 0.55%   |
| Crucial CT480BX500SSD1 480GB                         | 3         | 0.55%   |
| Crucial CT1000BX500SSD1 1TB                          | 3         | 0.55%   |
| Unknown                                              | 3         | 0.55%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                     | 2         | 0.36%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 2         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 2         | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                       | 2         | 0.36%   |
| WDC WD5000BEVT-75ZAT0 500GB                          | 2         | 0.36%   |
| WDC WD20EURS-63S48Y0 2TB                             | 2         | 0.36%   |
| WDC WD20EARS-00MVWB0 2TB                             | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 67     | 33.97%  |
| WDC                 | 50        | 69     | 32.05%  |
| Toshiba             | 26        | 27     | 16.67%  |
| Hitachi             | 8         | 9      | 5.13%   |
| Samsung Electronics | 6         | 11     | 3.85%   |
| Apple               | 5         | 5      | 3.21%   |
| HGST                | 4         | 4      | 2.56%   |
| Unknown             | 1         | 1      | 0.64%   |
| Maxtor              | 1         | 1      | 0.64%   |
| HGST HTS            | 1         | 1      | 0.64%   |
| Fujitsu             | 1         | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 49     | 23.43%  |
| Crucial             | 29        | 36     | 16.57%  |
| Kingston            | 24        | 26     | 13.71%  |
| WDC                 | 13        | 14     | 7.43%   |
| SanDisk             | 12        | 12     | 6.86%   |
| China               | 8         | 8      | 4.57%   |
| PNY                 | 7         | 11     | 4%      |
| A-DATA Technology   | 4         | 4      | 2.29%   |
| SPCC                | 3         | 3      | 1.71%   |
| Intel               | 3         | 3      | 1.71%   |
| Transcend           | 2         | 2      | 1.14%   |
| Toshiba             | 2         | 2      | 1.14%   |
| Mushkin             | 2         | 2      | 1.14%   |
| Micron Technology   | 2         | 2      | 1.14%   |
| LITEON              | 2         | 2      | 1.14%   |
| Apple               | 2         | 2      | 1.14%   |
| Verbatim            | 1         | 1      | 0.57%   |
| USB3.0              | 1         | 1      | 0.57%   |
| Team                | 1         | 1      | 0.57%   |
| SuperSSpeed         | 1         | 1      | 0.57%   |
| SK hynix            | 1         | 1      | 0.57%   |
| Seagate             | 1         | 1      | 0.57%   |
| Ramsta              | 1         | 1      | 0.57%   |
| PNY CS90            | 1         | 1      | 0.57%   |
| Patriot             | 1         | 1      | 0.57%   |
| OCZ                 | 1         | 1      | 0.57%   |
| MyDigitalSSD        | 1         | 1      | 0.57%   |
| LITEONIT            | 1         | 1      | 0.57%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.57%   |
| KingFast            | 1         | 1      | 0.57%   |
| JMicron Technology  | 1         | 1      | 0.57%   |
| Foxline             | 1         | 1      | 0.57%   |
| Emtec               | 1         | 1      | 0.57%   |
| Drevo               | 1         | 1      | 0.57%   |
| Unknown             | 1         | 2      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 142       | 198    | 34.22%  |
| NVMe    | 135       | 188    | 32.53%  |
| HDD     | 129       | 196    | 31.08%  |
| Unknown | 7         | 7      | 1.69%   |
| MMC     | 2         | 2      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 201       | 383    | 56.78%  |
| NVMe | 135       | 188    | 38.14%  |
| SAS  | 16        | 18     | 4.52%   |
| MMC  | 2         | 2      | 0.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 144       | 196    | 48.32%  |
| 0.51-1.0   | 96        | 122    | 32.21%  |
| 1.01-2.0   | 36        | 52     | 12.08%  |
| 4.01-10.0  | 7         | 8      | 2.35%   |
| 3.01-4.0   | 6         | 6      | 2.01%   |
| 2.01-3.0   | 6         | 6      | 2.01%   |
| 10.01-20.0 | 3         | 4      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 75        | 26.6%   |
| 251-500        | 61        | 21.63%  |
| 501-1000       | 58        | 20.57%  |
| 1001-2000      | 37        | 13.12%  |
| More than 3000 | 23        | 8.16%   |
| 2001-3000      | 8         | 2.84%   |
| 51-100         | 8         | 2.84%   |
| Unknown        | 6         | 2.13%   |
| 21-50          | 5         | 1.77%   |
| 1-20           | 1         | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 80        | 27.78%  |
| 1-20           | 66        | 22.92%  |
| 101-250        | 36        | 12.5%   |
| 51-100         | 33        | 11.46%  |
| 251-500        | 26        | 9.03%   |
| 501-1000       | 20        | 6.94%   |
| More than 3000 | 7         | 2.43%   |
| 2001-3000      | 7         | 2.43%   |
| 1001-2000      | 7         | 2.43%   |
| Unknown        | 6         | 2.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2         | 2      | 18.18%  |
| WDC WD20EURS-63S48Y0 2TB                       | 1         | 1      | 9.09%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1         | 1      | 9.09%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1         | 1      | 9.09%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 9.09%   |
| Samsung Electronics HD161GJ 160GB              | 1         | 1      | 9.09%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 9.09%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 9.09%   |
| Hitachi HTS54323 320GB                         | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 36.36%  |
| Seagate             | 2         | 2      | 18.18%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| Ramsta              | 1         | 1      | 9.09%   |
| Micron Technology   | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 50%     |
| Seagate             | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 72.73%  |
| SSD  | 2         | 2      | 18.18%  |
| NVMe | 1         | 1      | 9.09%   |

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
| Detected | 235       | 480    | 79.93%  |
| Works    | 48        | 99     | 16.33%  |
| Malfunc  | 10        | 11     | 3.4%    |
| Limited  | 1         | 1      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 151       | 36.39%  |
| AMD                            | 95        | 22.89%  |
| Samsung Electronics            | 55        | 13.25%  |
| SanDisk                        | 18        | 4.34%   |
| Phison Electronics             | 18        | 4.34%   |
| Kingston Technology Company    | 11        | 2.65%   |
| ASMedia Technology             | 9         | 2.17%   |
| SK hynix                       | 8         | 1.93%   |
| Micron/Crucial Technology      | 8         | 1.93%   |
| Micron Technology              | 7         | 1.69%   |
| ADATA Technology               | 5         | 1.2%    |
| Toshiba America Info Systems   | 4         | 0.96%   |
| Realtek Semiconductor          | 4         | 0.96%   |
| Nvidia                         | 4         | 0.96%   |
| Marvell Technology Group       | 4         | 0.96%   |
| KIOXIA                         | 4         | 0.96%   |
| Silicon Motion                 | 2         | 0.48%   |
| JMicron Technology             | 2         | 0.48%   |
| Solid State Storage Technology | 1         | 0.24%   |
| Silicon Image                  | 1         | 0.24%   |
| Shenzhen Longsys Electronics   | 1         | 0.24%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.24%   |
| Broadcom / LSI                 | 1         | 0.24%   |
| Apple                          | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 67        | 14.32%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 23        | 4.91%   |
| AMD 400 Series Chipset SATA Controller                                         | 21        | 4.49%   |
| Samsung NVMe SSD Controller 980                                                | 17        | 3.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 2.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 1.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 1.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9         | 1.92%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 1.92%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 1.92%   |
| Phison E12 NVMe Controller                                                     | 8         | 1.71%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 1.71%   |
| Intel SSD 660P Series                                                          | 8         | 1.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 1.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 1.71%   |
| Micron Non-Volatile memory controller                                          | 7         | 1.5%    |
| Intel SATA Controller [RAID mode]                                              | 7         | 1.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 1.28%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 1.07%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.07%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.07%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 5         | 1.07%   |
| Kingston Company A2000 NVMe SSD                                                | 5         | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.07%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 0.85%   |
| Intel Non-Volatile memory controller                                           | 4         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 0.85%   |
| AMD FCH SATA Controller D                                                      | 4         | 0.85%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.64%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 3         | 0.64%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 220       | 55.42%  |
| NVMe | 135       | 34.01%  |
| RAID | 25        | 6.3%    |
| IDE  | 15        | 3.78%   |
| SAS  | 2         | 0.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 162       | 58.48%  |
| AMD    | 115       | 41.52%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 2600 Six-Core Processor     | 7         | 2.53%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 5         | 1.81%   |
| AMD FX-8350 Eight-Core Processor        | 5         | 1.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 1.44%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 4         | 1.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 4         | 1.44%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4         | 1.44%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 4         | 1.44%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 4         | 1.44%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 4         | 1.44%   |
| AMD Ryzen 5 3600 6-Core Processor       | 4         | 1.44%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 3         | 1.08%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 3         | 1.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.08%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 3         | 1.08%   |
| Intel Core i3-4030U CPU @ 1.90GHz       | 3         | 1.08%   |
| Intel 12th Gen Core i5-12600K           | 3         | 1.08%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 1.08%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 3         | 1.08%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 3         | 1.08%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 1.08%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 3         | 1.08%   |
| AMD FX-6300 Six-Core Processor          | 3         | 1.08%   |
| Intel Pentium CPU B960 @ 2.20GHz        | 2         | 0.72%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 2         | 0.72%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 2         | 0.72%   |
| Intel Core i5-7600K CPU @ 3.80GHz       | 2         | 0.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 2         | 0.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.72%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 2         | 0.72%   |
| Intel Core i3-3240 CPU @ 3.40GHz        | 2         | 0.72%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 2         | 0.72%   |
| Intel 12th Gen Core i7-12700H           | 2         | 0.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 0.72%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz  | 2         | 0.72%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz | 2         | 0.72%   |
| AMD Ryzen 9 5900HS with Radeon Graphics | 2         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 54        | 19.49%  |
| Intel Core i5           | 44        | 15.88%  |
| AMD Ryzen 5             | 43        | 15.52%  |
| AMD Ryzen 7             | 29        | 10.47%  |
| Other                   | 21        | 7.58%   |
| AMD Ryzen 9             | 16        | 5.78%   |
| Intel Core i3           | 15        | 5.42%   |
| AMD FX                  | 10        | 3.61%   |
| Intel Celeron           | 7         | 2.53%   |
| Intel Xeon              | 5         | 1.81%   |
| Intel Core 2 Duo        | 5         | 1.81%   |
| Intel Pentium           | 4         | 1.44%   |
| AMD Ryzen 3             | 4         | 1.44%   |
| Intel Core i9           | 3         | 1.08%   |
| Intel Atom              | 2         | 0.72%   |
| AMD Phenom II X6        | 2         | 0.72%   |
| AMD A6                  | 2         | 0.72%   |
| AMD A10                 | 2         | 0.72%   |
| Intel Pentium Dual-Core | 1         | 0.36%   |
| Intel Core m7           | 1         | 0.36%   |
| Intel Core 2 Extreme    | 1         | 0.36%   |
| AMD Ryzen 3 PRO         | 1         | 0.36%   |
| AMD Phenom II X4        | 1         | 0.36%   |
| AMD E                   | 1         | 0.36%   |
| AMD Athlon X4           | 1         | 0.36%   |
| AMD Athlon Dual Core    | 1         | 0.36%   |
| AMD A4                  | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 83        | 29.96%  |
| 2      | 64        | 23.1%   |
| 6      | 60        | 21.66%  |
| 8      | 45        | 16.25%  |
| 12     | 10        | 3.61%   |
| 16     | 4         | 1.44%   |
| 10     | 4         | 1.44%   |
| 3      | 3         | 1.08%   |
| 14     | 2         | 0.72%   |
| 1      | 2         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 276       | 99.64%  |
| 2      | 1         | 0.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 226       | 81.59%  |
| 1      | 51        | 18.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 277       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 15        | 5.4%    |
| 0x306c3    | 14        | 5.04%   |
| 0x206a7    | 14        | 5.04%   |
| 0x0a50000c | 14        | 5.04%   |
| 0x08701021 | 13        | 4.68%   |
| 0x40651    | 11        | 3.96%   |
| 0x906e9    | 10        | 3.6%    |
| Unknown    | 10        | 3.6%    |
| 0x906ea    | 9         | 3.24%   |
| 0x08108109 | 9         | 3.24%   |
| 0xa0652    | 8         | 2.88%   |
| 0x0800820d | 8         | 2.88%   |
| 0x06000822 | 8         | 2.88%   |
| 0x506e3    | 7         | 2.52%   |
| 0xa0655    | 6         | 2.16%   |
| 0x0a201016 | 6         | 2.16%   |
| 0x08608103 | 6         | 2.16%   |
| 0x906a3    | 5         | 1.8%    |
| 0x806c1    | 5         | 1.8%    |
| 0x08001138 | 5         | 1.8%    |
| 0x906ed    | 4         | 1.44%   |
| 0x806e9    | 4         | 1.44%   |
| 0x806d1    | 4         | 1.44%   |
| 0x406e3    | 4         | 1.44%   |
| 0x1067a    | 4         | 1.44%   |
| 0x0a50000d | 4         | 1.44%   |
| 0x08600104 | 4         | 1.44%   |
| 0x906ec    | 3         | 1.08%   |
| 0x90672    | 3         | 1.08%   |
| 0x30678    | 3         | 1.08%   |
| 0x206d7    | 3         | 1.08%   |
| 0x10676    | 3         | 1.08%   |
| 0x0a201205 | 3         | 1.08%   |
| 0x0a201204 | 3         | 1.08%   |
| 0x08600106 | 3         | 1.08%   |
| 0x08108102 | 3         | 1.08%   |
| 0x06003106 | 3         | 1.08%   |
| 0xa0671    | 2         | 0.72%   |
| 0xa0653    | 2         | 0.72%   |
| 0x806ea    | 2         | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 34        | 12.27%  |
| Zen 3            | 33        | 11.91%  |
| Haswell          | 27        | 9.75%   |
| Zen 2            | 23        | 8.3%    |
| Zen+             | 21        | 7.58%   |
| SandyBridge      | 18        | 6.5%    |
| CometLake        | 16        | 5.78%   |
| IvyBridge        | 15        | 5.42%   |
| Unknown          | 12        | 4.33%   |
| Skylake          | 11        | 3.97%   |
| Piledriver       | 11        | 3.97%   |
| IceLake          | 8         | 2.89%   |
| Alderlake Hybrid | 8         | 2.89%   |
| Penryn           | 7         | 2.53%   |
| Zen              | 6         | 2.17%   |
| TigerLake        | 5         | 1.81%   |
| Silvermont       | 4         | 1.44%   |
| Steamroller      | 3         | 1.08%   |
| K10              | 3         | 1.08%   |
| Goldmont plus    | 2         | 0.72%   |
| Broadwell        | 2         | 0.72%   |
| Westmere         | 1         | 0.36%   |
| Puma             | 1         | 0.36%   |
| Nehalem          | 1         | 0.36%   |
| K8 Hammer        | 1         | 0.36%   |
| Goldmont         | 1         | 0.36%   |
| Excavator        | 1         | 0.36%   |
| Bonnell          | 1         | 0.36%   |
| Bobcat           | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 136       | 38.53%  |
| AMD    | 113       | 32.01%  |
| Intel  | 104       | 29.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12        | 3.3%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 12        | 3.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 11        | 3.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11        | 3.02%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 10        | 2.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9         | 2.47%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 8         | 2.2%    |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 8         | 2.2%    |
| AMD Renoir                                                                  | 6         | 1.65%   |
| AMD Lucienne                                                                | 6         | 1.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 5         | 1.37%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 5         | 1.37%   |
| Intel HD Graphics 530                                                       | 5         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 1.37%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 1.37%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5         | 1.37%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 5         | 1.37%   |
| Nvidia TU117M                                                               | 4         | 1.1%    |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 4         | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 1.1%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4         | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 1.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 1.1%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 1.1%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4         | 1.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 1.1%    |
| Intel Alder Lake-P Integrated Graphics Controller                           | 4         | 1.1%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4         | 1.1%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 3         | 0.82%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3         | 0.82%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 3         | 0.82%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3         | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 0.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 0.82%   |
| Intel HD Graphics 630                                                       | 3         | 0.82%   |
| Intel HD Graphics 620                                                       | 3         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 0.82%   |
| Intel AlderLake-S GT1                                                       | 3         | 0.82%   |
| AMD Rembrandt [Radeon 680M]                                                 | 3         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Nvidia         | 77        | 27.8%   |
| 1 x AMD            | 77        | 27.8%   |
| 1 x Intel          | 48        | 17.33%  |
| Intel + Nvidia     | 37        | 13.36%  |
| AMD + Nvidia       | 19        | 6.86%   |
| Intel + AMD        | 9         | 3.25%   |
| 2 x AMD            | 7         | 2.53%   |
| 2 x Nvidia         | 2         | 0.72%   |
| Intel + 2 x Nvidia | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 169       | 60.57%  |
| Proprietary | 106       | 37.99%  |
| Unknown     | 4         | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 119       | 42.35%  |
| 0.01-0.5   | 33        | 11.74%  |
| 7.01-8.0   | 32        | 11.39%  |
| 1.01-2.0   | 28        | 9.96%   |
| 3.01-4.0   | 24        | 8.54%   |
| 8.01-16.0  | 19        | 6.76%   |
| 0.51-1.0   | 15        | 5.34%   |
| 5.01-6.0   | 7         | 2.49%   |
| 2.01-3.0   | 2         | 0.71%   |
| 16.01-24.0 | 2         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 38        | 12.14%  |
| AU Optronics         | 35        | 11.18%  |
| Goldstar             | 24        | 7.67%   |
| BOE                  | 20        | 6.39%   |
| LG Display           | 17        | 5.43%   |
| Chimei Innolux       | 16        | 5.11%   |
| Acer                 | 16        | 5.11%   |
| Dell                 | 13        | 4.15%   |
| Apple                | 10        | 3.19%   |
| Ancor Communications | 10        | 3.19%   |
| BenQ                 | 9         | 2.88%   |
| ASUSTek Computer     | 9         | 2.88%   |
| AOC                  | 9         | 2.88%   |
| MSI                  | 8         | 2.56%   |
| Sony                 | 7         | 2.24%   |
| Sharp                | 7         | 2.24%   |
| PANDA                | 7         | 2.24%   |
| Hewlett-Packard      | 7         | 2.24%   |
| Vizio                | 6         | 1.92%   |
| ViewSonic            | 6         | 1.92%   |
| Philips              | 4         | 1.28%   |
| Lenovo               | 4         | 1.28%   |
| Toshiba              | 3         | 0.96%   |
| Sceptre Tech         | 3         | 0.96%   |
| InfoVision           | 3         | 0.96%   |
| HUAWEI               | 2         | 0.64%   |
| Gigabyte Technology  | 2         | 0.64%   |
| ___                  | 1         | 0.32%   |
| Valve                | 1         | 0.32%   |
| Unknown              | 1         | 0.32%   |
| SNC                  | 1         | 0.32%   |
| SFX                  | 1         | 0.32%   |
| PRI                  | 1         | 0.32%   |
| NPC                  | 1         | 0.32%   |
| MStar                | 1         | 0.32%   |
| MLT                  | 1         | 0.32%   |
| Iiyama               | 1         | 0.32%   |
| Hitachi              | 1         | 0.32%   |
| GDH                  | 1         | 0.32%   |
| Eizo                 | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| MSI G27C4 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 3         | 0.92%   |
| Toshiba TV TSB0108 1440x900 700x390mm 31.5-inch                        | 2         | 0.61%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch  | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2         | 0.61%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2         | 0.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.61%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 2         | 0.61%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch             | 2         | 0.61%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch               | 2         | 0.61%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2         | 0.61%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch        | 2         | 0.61%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                  | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch         | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch          | 2         | 0.61%   |
| ASUSTek Computer ROG XG27UQR AUS27BA 3840x2160 596x335mm 26.9-inch     | 2         | 0.61%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch         | 2         | 0.61%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 2         | 0.61%   |
| ___ LCD TV ___9000 1360x768                                            | 1         | 0.31%   |
| Vizio VX42L HDTV10A VIZ0030 1280x720 930x523mm 42.0-inch               | 1         | 0.31%   |
| Vizio V435-J01 VIZ1039 3840x2160 941x529mm 42.5-inch                   | 1         | 0.31%   |
| Vizio E601i-A3 VIZ0092 1920x1080 1329x748mm 60.0-inch                  | 1         | 0.31%   |
| Vizio E400i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                   | 1         | 0.31%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 0.31%   |
| Vizio D24h-G9 VIZ1028 1360x768 521x293mm 23.5-inch                     | 1         | 0.31%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch          | 1         | 0.31%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch          | 1         | 0.31%   |
| ViewSonic VX3218-PC-mhd VSCEB3A 1920x1080 609x348mm 27.6-inch          | 1         | 0.31%   |
| ViewSonic VX2768-2KP VSC0A3B 2560x1440 600x340mm 27.2-inch             | 1         | 0.31%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch          | 1         | 0.31%   |
| ViewSonic VA2446 Series VSC732E 1920x1080 521x293mm 23.5-inch          | 1         | 0.31%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 1         | 0.31%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                       | 1         | 0.31%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch               | 1         | 0.31%   |
| Sony TV SNYEB01 1360x768                                               | 1         | 0.31%   |
| Sony TV SNY8F03 1360x768                                               | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 141       | 47%     |
| 3840x2160 (4K)     | 33        | 11%     |
| 1366x768 (WXGA)    | 32        | 10.67%  |
| 2560x1440 (QHD)    | 30        | 10%     |
| 1680x1050 (WSXGA+) | 8         | 2.67%   |
| 1440x900 (WXGA+)   | 7         | 2.33%   |
| 3440x1440          | 5         | 1.67%   |
| 2560x1080          | 5         | 1.67%   |
| 1920x1200 (WUXGA)  | 5         | 1.67%   |
| 1600x900 (HD+)     | 5         | 1.67%   |
| 1360x768           | 5         | 1.67%   |
| 2880x1800          | 4         | 1.33%   |
| 2560x1600          | 3         | 1%      |
| 1920x540           | 3         | 1%      |
| 1280x800 (WXGA)    | 3         | 1%      |
| 1280x1024 (SXGA)   | 3         | 1%      |
| 800x1280           | 1         | 0.33%   |
| 5760x1080          | 1         | 0.33%   |
| 3840x2560          | 1         | 0.33%   |
| 3840x1600          | 1         | 0.33%   |
| 3200x1800 (QHD+)   | 1         | 0.33%   |
| 2520x1680          | 1         | 0.33%   |
| 2240x1400          | 1         | 0.33%   |
| Unknown            | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 73        | 22.96%  |
| 27      | 42        | 13.21%  |
| 23      | 23        | 7.23%   |
| 21      | 19        | 5.97%   |
| 17      | 18        | 5.66%   |
| 31      | 17        | 5.35%   |
| 24      | 17        | 5.35%   |
| 13      | 17        | 5.35%   |
| 14      | 13        | 4.09%   |
| 34      | 7         | 2.2%    |
| 72      | 6         | 1.89%   |
| 84      | 5         | 1.57%   |
| 26      | 5         | 1.57%   |
| 22      | 5         | 1.57%   |
| 20      | 5         | 1.57%   |
| 19      | 5         | 1.57%   |
| Unknown | 5         | 1.57%   |
| 48      | 4         | 1.26%   |
| 18      | 3         | 0.94%   |
| 16      | 3         | 0.94%   |
| 52      | 2         | 0.63%   |
| 42      | 2         | 0.63%   |
| 40      | 2         | 0.63%   |
| 38      | 2         | 0.63%   |
| 29      | 2         | 0.63%   |
| 28      | 2         | 0.63%   |
| 12      | 2         | 0.63%   |
| 75      | 1         | 0.31%   |
| 69      | 1         | 0.31%   |
| 60      | 1         | 0.31%   |
| 58      | 1         | 0.31%   |
| 55      | 1         | 0.31%   |
| 54      | 1         | 0.31%   |
| 49      | 1         | 0.31%   |
| 37      | 1         | 0.31%   |
| 33      | 1         | 0.31%   |
| 32      | 1         | 0.31%   |
| 10      | 1         | 0.31%   |
| 7       | 1         | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 32.04%  |
| 501-600     | 74        | 23.95%  |
| 401-500     | 37        | 11.97%  |
| 601-700     | 25        | 8.09%   |
| 351-400     | 15        | 4.85%   |
| 201-300     | 13        | 4.21%   |
| 1501-2000   | 13        | 4.21%   |
| 1001-1500   | 11        | 3.56%   |
| 701-800     | 9         | 2.91%   |
| 801-900     | 5         | 1.62%   |
| Unknown     | 5         | 1.62%   |
| 901-1000    | 2         | 0.65%   |
| 1-100       | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 215       | 79.93%  |
| 16/10   | 32        | 11.9%   |
| 21/9    | 11        | 4.09%   |
| 5/4     | 3         | 1.12%   |
| 4/3     | 2         | 0.74%   |
| 32/9    | 2         | 0.74%   |
| 3/2     | 2         | 0.74%   |
| 0.67    | 1         | 0.37%   |
| Unknown | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 74        | 23.49%  |
| 201-250        | 53        | 16.83%  |
| 301-350        | 47        | 14.92%  |
| 351-500        | 27        | 8.57%   |
| 81-90          | 24        | 7.62%   |
| More than 1000 | 23        | 7.3%    |
| 151-200        | 16        | 5.08%   |
| 121-130        | 13        | 4.13%   |
| 501-1000       | 8         | 2.54%   |
| 251-300        | 6         | 1.9%    |
| 71-80          | 5         | 1.59%   |
| 141-150        | 5         | 1.59%   |
| Unknown        | 5         | 1.59%   |
| 111-120        | 3         | 0.95%   |
| 61-70          | 2         | 0.63%   |
| 131-140        | 2         | 0.63%   |
| 41-50          | 1         | 0.32%   |
| 1-40           | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 105       | 35%     |
| 121-160       | 77        | 25.67%  |
| 101-120       | 69        | 23%     |
| 1-50          | 18        | 6%      |
| 161-240       | 18        | 6%      |
| More than 240 | 8         | 2.67%   |
| Unknown       | 5         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 206       | 74.37%  |
| 2     | 50        | 18.05%  |
| 0     | 11        | 3.97%   |
| 3     | 9         | 3.25%   |
| 4     | 1         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 166       | 39.06%  |
| Intel                           | 139       | 32.71%  |
| Qualcomm Atheros                | 30        | 7.06%   |
| Broadcom                        | 24        | 5.65%   |
| MediaTek                        | 13        | 3.06%   |
| TP-Link                         | 9         | 2.12%   |
| Microsoft                       | 6         | 1.41%   |
| Broadcom Limited                | 5         | 1.18%   |
| Samsung Electronics             | 3         | 0.71%   |
| Ralink                          | 3         | 0.71%   |
| ASIX Electronics                | 3         | 0.71%   |
| Xiaomi                          | 2         | 0.47%   |
| Ralink Technology               | 2         | 0.47%   |
| Qualcomm                        | 2         | 0.47%   |
| Nvidia                          | 2         | 0.47%   |
| ASUSTek Computer                | 2         | 0.47%   |
| Wacom                           | 1         | 0.24%   |
| T & A Mobile Phones             | 1         | 0.24%   |
| Sierra Wireless                 | 1         | 0.24%   |
| Qualcomm Atheros Communications | 1         | 0.24%   |
| Panasonic (Matsushita)          | 1         | 0.24%   |
| Oculus VR                       | 1         | 0.24%   |
| Motorola PCS                    | 1         | 0.24%   |
| Marvell Technology Group        | 1         | 0.24%   |
| Linksys                         | 1         | 0.24%   |
| ICS Advent                      | 1         | 0.24%   |
| Holtek Semiconductor            | 1         | 0.24%   |
| Google                          | 1         | 0.24%   |
| D-Link                          | 1         | 0.24%   |
| Afatech                         | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 128       | 25.96%  |
| Intel Wi-Fi 6 AX200                                               | 29        | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 15        | 3.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 1.83%   |
| Intel Ethernet Controller I225-V                                  | 8         | 1.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 1.42%   |
| Intel Ethernet Connection (7) I219-V                              | 7         | 1.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 1.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 1.22%   |
| Intel Wireless 8260                                               | 6         | 1.22%   |
| Intel Wireless 7260                                               | 6         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.01%   |
| Intel Wireless 7265                                               | 5         | 1.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.81%   |
| Intel Wireless-AC 9260                                            | 4         | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.81%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.81%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.81%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.61%   |
| Microsoft Wireless XBox Controller Dongle                         | 3         | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.61%   |
| Intel Wireless 8265 / 8275                                        | 3         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 102       | 45.95%  |
| Realtek Semiconductor           | 39        | 17.57%  |
| Qualcomm Atheros                | 19        | 8.56%   |
| Broadcom                        | 19        | 8.56%   |
| MediaTek                        | 13        | 5.86%   |
| TP-Link                         | 8         | 3.6%    |
| Microsoft                       | 6         | 2.7%    |
| Ralink                          | 3         | 1.35%   |
| Broadcom Limited                | 3         | 1.35%   |
| Ralink Technology               | 2         | 0.9%    |
| ASUSTek Computer                | 2         | 0.9%    |
| Wacom                           | 1         | 0.45%   |
| Sierra Wireless                 | 1         | 0.45%   |
| Qualcomm Atheros Communications | 1         | 0.45%   |
| Panasonic (Matsushita)          | 1         | 0.45%   |
| Linksys                         | 1         | 0.45%   |
| D-Link                          | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 29        | 13.06%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 9         | 4.05%   |
| Intel Comet Lake PCH CNVi WiFi                                | 9         | 4.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 7         | 3.15%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 6         | 2.7%    |
| Intel Wireless 8260                                           | 6         | 2.7%    |
| Intel Wireless 7260                                           | 6         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                               | 6         | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 5         | 2.25%   |
| Intel Wireless 7265                                           | 5         | 2.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 5         | 2.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 4         | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 4         | 1.8%    |
| Intel Wireless-AC 9260                                        | 4         | 1.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 4         | 1.8%    |
| Intel Wi-Fi 6 AX201                                           | 4         | 1.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 4         | 1.8%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 4         | 1.8%    |
| Broadcom BCM43142 802.11b/g/n                                 | 4         | 1.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.35%   |
| Microsoft Wireless XBox Controller Dongle                     | 3         | 1.35%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 3         | 1.35%   |
| Intel Wireless 8265 / 8275                                    | 3         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 3         | 1.35%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 3         | 1.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2         | 0.9%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2         | 0.9%    |
| TP-Link 802.11ac NIC                                          | 2         | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2         | 0.9%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 2         | 0.9%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 2         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2         | 0.9%    |
| Realtek 802.11ac NIC                                          | 2         | 0.9%    |
| Microsoft Xbox 360 Wireless Adapter                           | 2         | 0.9%    |
| Intel Wireless 3165                                           | 2         | 0.9%    |
| Intel Wireless 3160                                           | 2         | 0.9%    |
| Intel WiFi Link 5100                                          | 2         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 153       | 58.4%   |
| Intel                    | 67        | 25.57%  |
| Qualcomm Atheros         | 13        | 4.96%   |
| Broadcom                 | 9         | 3.44%   |
| Samsung Electronics      | 3         | 1.15%   |
| ASIX Electronics         | 3         | 1.15%   |
| Xiaomi                   | 2         | 0.76%   |
| Qualcomm                 | 2         | 0.76%   |
| Nvidia                   | 2         | 0.76%   |
| Broadcom Limited         | 2         | 0.76%   |
| TP-Link                  | 1         | 0.38%   |
| T & A Mobile Phones      | 1         | 0.38%   |
| Motorola PCS             | 1         | 0.38%   |
| Marvell Technology Group | 1         | 0.38%   |
| ICS Advent               | 1         | 0.38%   |
| Google                   | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 128       | 47.76%  |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 6.34%   |
| Intel I211 Gigabit Network Connection                             | 15        | 5.6%    |
| Intel Ethernet Controller I225-V                                  | 8         | 2.99%   |
| Intel Ethernet Connection (7) I219-V                              | 7         | 2.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.24%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 1.49%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.12%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.12%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.75%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.75%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.75%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.75%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.37%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.37%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.37%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.37%   |
| Qualcomm FP3                                                      | 1         | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 246       | 53.59%  |
| WiFi     | 210       | 45.75%  |
| Unknown  | 2         | 0.44%   |
| Modem    | 1         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 50.17%  |
| Ethernet | 146       | 49.83%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 151       | 54.51%  |
| 1     | 120       | 43.32%  |
| 3     | 4         | 1.44%   |
| 0     | 2         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 195       | 69.64%  |
| Yes  | 85        | 30.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 50.79%  |
| Realtek Semiconductor           | 18        | 9.42%   |
| Cambridge Silicon Radio         | 13        | 6.81%   |
| IMC Networks                    | 9         | 4.71%   |
| Broadcom                        | 9         | 4.71%   |
| Apple                           | 9         | 4.71%   |
| Foxconn / Hon Hai               | 8         | 4.19%   |
| Qualcomm Atheros Communications | 6         | 3.14%   |
| Lite-On Technology              | 6         | 3.14%   |
| MediaTek                        | 3         | 1.57%   |
| ASUSTek Computer                | 3         | 1.57%   |
| TP-Link                         | 2         | 1.05%   |
| Toshiba                         | 1         | 0.52%   |
| Realtek                         | 1         | 0.52%   |
| Ralink                          | 1         | 0.52%   |
| Integrated System Solution      | 1         | 0.52%   |
| Foxconn International           | 1         | 0.52%   |
| Edimax Technology               | 1         | 0.52%   |
| Dell                            | 1         | 0.52%   |
| Unknown                         | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                                 | 29        | 15.18%  |
| Intel Bluetooth wireless interface                    | 28        | 14.66%  |
| Intel Bluetooth Device                                | 23        | 12.04%  |
| Realtek Bluetooth Radio                               | 15        | 7.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 13        | 6.81%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 6         | 3.14%   |
| Apple Bluetooth Host Controller                       | 5         | 2.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4         | 2.09%   |
| Intel AX210 Bluetooth                                 | 4         | 2.09%   |
| IMC Networks Wireless_Device                          | 4         | 2.09%   |
| IMC Networks Bluetooth Radio                          | 4         | 2.09%   |
| MediaTek Wireless_Device                              | 3         | 1.57%   |
| Lite-On Bluetooth Device                              | 3         | 1.57%   |
| Foxconn / Hon Hai Wireless_Device                     | 3         | 1.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3         | 1.57%   |
| ASUS ASUS USB-BT500                                   | 3         | 1.57%   |
| TP-Link TPuLink UB500 Adapter                         | 2         | 1.05%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 2         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2         | 1.05%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth         | 2         | 1.05%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2         | 1.05%   |
| Apple Bluetooth USB Host Controller                   | 2         | 1.05%   |
| Toshiba Askey Bluetooth Module                        | 1         | 0.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1         | 0.52%   |
| Realtek Bluetooth Radio                               | 1         | 0.52%   |
| Ralink RT3290 Bluetooth                               | 1         | 0.52%   |
| Qualcomm Atheros  Bluetooth Device                    | 1         | 0.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 1         | 0.52%   |
| Lite-On Wireless_Device                               | 1         | 0.52%   |
| Lite-On Bluetooth Radio                               | 1         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 1         | 0.52%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.52%   |
| IMC Networks Bluetooth Device                         | 1         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module     | 1         | 0.52%   |
| Foxconn / Hon Hai BT                                  | 1         | 0.52%   |
| Foxconn / Hon Hai Bluetooth Device                    | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 156       | 31.97%  |
| AMD                      | 139       | 28.48%  |
| Nvidia                   | 112       | 22.95%  |
| C-Media Electronics      | 15        | 3.07%   |
| Logitech                 | 11        | 2.25%   |
| SteelSeries ApS          | 4         | 0.82%   |
| Razer USA                | 4         | 0.82%   |
| Plantronics              | 4         | 0.82%   |
| ASUSTek Computer         | 4         | 0.82%   |
| Kingston Technology      | 3         | 0.61%   |
| JMTek                    | 3         | 0.61%   |
| Focusrite-Novation       | 3         | 0.61%   |
| Blue Microphones         | 3         | 0.61%   |
| Sony                     | 2         | 0.41%   |
| Samson Technologies      | 2         | 0.41%   |
| Realtek Semiconductor    | 2         | 0.41%   |
| Generalplus Technology   | 2         | 0.41%   |
| Creative Technology      | 2         | 0.41%   |
| Creative Labs            | 2         | 0.41%   |
| Corsair                  | 2         | 0.41%   |
| Asahi Kasei Microsystems | 2         | 0.41%   |
| TTGK Technology          | 1         | 0.2%    |
| Texas Instruments        | 1         | 0.2%    |
| ROCCAT                   | 1         | 0.2%    |
| Positive Grid            | 1         | 0.2%    |
| Micro Star International | 1         | 0.2%    |
| Hewlett-Packard          | 1         | 0.2%    |
| Giga-Byte Technology     | 1         | 0.2%    |
| Elgato Systems           | 1         | 0.2%    |
| Cambridge Silicon Radio  | 1         | 0.2%    |
| Audio-Technica           | 1         | 0.2%    |
| AKAI Professional M.I.   | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 46        | 7.78%   |
| AMD Starship/Matisse HD Audio Controller                                   | 29        | 4.91%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 4.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 23        | 3.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 2.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14        | 2.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 2.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 12        | 2.03%   |
| Intel Comet Lake PCH cAVS                                                  | 12        | 2.03%   |
| Intel 8 Series HD Audio Controller                                         | 12        | 2.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 2.03%   |
| Nvidia GA104 High Definition Audio Controller                              | 11        | 1.86%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 1.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 1.86%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11        | 1.86%   |
| Nvidia GA106 High Definition Audio Controller                              | 10        | 1.69%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.69%   |
| Nvidia GP104 High Definition Audio Controller                              | 9         | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.35%   |
| Nvidia TU104 HD Audio Controller                                           | 8         | 1.35%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 1.18%   |
| Nvidia GA102 High Definition Audio Controller                              | 7         | 1.18%   |
| AMD FCH Azalia Controller                                                  | 7         | 1.18%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 7         | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.02%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 1.02%   |
| AMD Navi 10 HDMI Audio                                                     | 6         | 1.02%   |
| Logitech PRO X Wireless Gaming Headset                                     | 5         | 0.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 0.85%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.85%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 5         | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.68%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4         | 0.68%   |
| C-Media Electronics USB Audio Device                                       | 4         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 29.41%  |
| SK hynix            | 10        | 14.71%  |
| Micron Technology   | 10        | 14.71%  |
| Corsair             | 7         | 10.29%  |
| Kingston            | 5         | 7.35%   |
| G.Skill             | 3         | 4.41%   |
| Unknown (ABCD)      | 2         | 2.94%   |
| Unknown             | 2         | 2.94%   |
| Team                | 2         | 2.94%   |
| Crucial             | 2         | 2.94%   |
| Transcend           | 1         | 1.47%   |
| Ramaxel Technology  | 1         | 1.47%   |
| Nanya Technology    | 1         | 1.47%   |
| Elpida              | 1         | 1.47%   |
| Asgard              | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 4.17%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 2.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 2.78%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 2.78%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 1.39%   |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s           | 1         | 1.39%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 1.39%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 1.39%   |
| Team RAM TEAMGROUP-UD3 8192MB DIMM DDR3 1600MT/s                 | 1         | 1.39%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.39%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.39%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 1.39%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.39%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 1         | 1.39%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.39%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.39%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 1         | 1.39%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.39%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM DDR 975MT/s             | 1         | 1.39%   |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s              | 1         | 1.39%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 1         | 1.39%   |
| Samsung RAM K4AAG165WA-BCWE 8GB SODIMM DDR4 3200MT/s             | 1         | 1.39%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Nanya RAM M2S4G64CB8HG4N-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.39%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 1         | 1.39%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 34        | 61.82%  |
| DDR3    | 12        | 21.82%  |
| LPDDR4  | 4         | 7.27%   |
| DDR5    | 2         | 3.64%   |
| SDRAM   | 1         | 1.82%   |
| DDR2    | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 52.63%  |
| DIMM         | 21        | 36.84%  |
| Row Of Chips | 6         | 10.53%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 34        | 56.67%  |
| 4096  | 11        | 18.33%  |
| 16384 | 6         | 10%     |
| 2048  | 5         | 8.33%   |
| 32768 | 3         | 5%      |
| 1024  | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 18        | 30%     |
| 1600  | 9         | 15%     |
| 2400  | 5         | 8.33%   |
| 3600  | 4         | 6.67%   |
| 2667  | 4         | 6.67%   |
| 4800  | 2         | 3.33%   |
| 2933  | 2         | 3.33%   |
| 2133  | 2         | 3.33%   |
| 1333  | 2         | 3.33%   |
| 6400  | 1         | 1.67%   |
| 4267  | 1         | 1.67%   |
| 4266  | 1         | 1.67%   |
| 3866  | 1         | 1.67%   |
| 3800  | 1         | 1.67%   |
| 3733  | 1         | 1.67%   |
| 3466  | 1         | 1.67%   |
| 3000  | 1         | 1.67%   |
| 2800  | 1         | 1.67%   |
| 1066  | 1         | 1.67%   |
| 975   | 1         | 1.67%   |
| 800   | 1         | 1.67%   |

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
| Chicony Electronics                    | 27        | 17.76%  |
| Logitech                               | 18        | 11.84%  |
| IMC Networks                           | 17        | 11.18%  |
| Apple                                  | 12        | 7.89%   |
| Acer                                   | 11        | 7.24%   |
| Microdia                               | 8         | 5.26%   |
| Realtek Semiconductor                  | 7         | 4.61%   |
| Sunplus Innovation Technology          | 6         | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.95%   |
| Syntek                                 | 5         | 3.29%   |
| Quanta                                 | 5         | 3.29%   |
| Sonix Technology                       | 4         | 2.63%   |
| Suyin                                  | 3         | 1.97%   |
| Luxvisions Innotech Limited            | 3         | 1.97%   |
| Samsung Electronics                    | 2         | 1.32%   |
| Microsoft                              | 2         | 1.32%   |
| Lite-On Technology                     | 2         | 1.32%   |
| Hewlett-Packard                        | 2         | 1.32%   |
| Z-Star Microelectronics                | 1         | 0.66%   |
| Tobii Technology AB                    | 1         | 0.66%   |
| SunplusIT                              | 1         | 0.66%   |
| Silicon Motion                         | 1         | 0.66%   |
| Owon                                   | 1         | 0.66%   |
| Lenovo                                 | 1         | 0.66%   |
| Intel                                  | 1         | 0.66%   |
| Importek                               | 1         | 0.66%   |
| HD WEBCAM                              | 1         | 0.66%   |
| Goodong Industry                       | 1         | 0.66%   |
| ARC International                      | 1         | 0.66%   |
| ANYKA                                  | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 10        | 6.54%   |
| Chicony Integrated Camera                           | 6         | 3.92%   |
| Logitech C922 Pro Stream Webcam                     | 5         | 3.27%   |
| Syntek Integrated Camera                            | 4         | 2.61%   |
| Apple iPhone 5/5C/5S/6/SE                           | 4         | 2.61%   |
| Acer Integrated Camera                              | 4         | 2.61%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.96%   |
| Realtek USB Camera                                  | 3         | 1.96%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.96%   |
| Logitech Webcam C270                                | 3         | 1.96%   |
| Logitech HD Pro Webcam C920                         | 3         | 1.96%   |
| IMC Networks Integrated Camera                      | 3         | 1.96%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 1.96%   |
| Acer HD Webcam                                      | 3         | 1.96%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.31%   |
| Samsung Galaxy A5 (MTP)                             | 2         | 1.31%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.31%   |
| Microdia Laptop_Integrated_Webcam_FHD               | 2         | 1.31%   |
| Logitech StreamCam                                  | 2         | 1.31%   |
| Logitech QuickCam Pro 9000                          | 2         | 1.31%   |
| Chicony USB2.0 Camera                               | 2         | 1.31%   |
| Chicony USB 2.0 Camera                              | 2         | 1.31%   |
| Chicony HP Truevision HD                            | 2         | 1.31%   |
| Chicony HD Webcam                                   | 2         | 1.31%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 1.31%   |
| Apple FaceTime HD Camera                            | 2         | 1.31%   |
| Apple Built-in iSight                               | 2         | 1.31%   |
| Acer Lenovo EasyCamera                              | 2         | 1.31%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.65%   |
| Tobii AB EyeChip                                    | 1         | 0.65%   |
| Syntek EasyCamera                                   | 1         | 0.65%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.65%   |
| Suyin HP Truevision HD                              | 1         | 0.65%   |
| Suyin HP TrueVision Full HD                         | 1         | 0.65%   |
| SunplusIT MTD camera                                | 1         | 0.65%   |
| Sunplus Laptop Integrated WebCam HD                 | 1         | 0.65%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.65%   |
| Sunplus HD WebCam                                   | 1         | 0.65%   |
| Sunplus Asus Webcam                                 | 1         | 0.65%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 8         | 38.1%   |
| Synaptics                          | 6         | 28.57%  |
| Shenzhen Goodix Technology         | 3         | 14.29%  |
| Elan Microelectronics              | 3         | 14.29%  |
| Realtek USB2.0 Finger Print Bridge | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 23.81%  |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 9.52%   |
| Elan ELAN:ARM-M4                                                | 2         | 9.52%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 4.76%   |
| Synaptics WBDI Device                                           | 1         | 4.76%   |
| Synaptics  WBDI                                                 | 1         | 4.76%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 4.76%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 4.76%   |
| Elan ELAN:Fingerprint                                           | 1         | 4.76%   |
| Unknown                                                         | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 33.33%  |
| Broadcom              | 1         | 33.33%  |
| Alcor Micro           | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 211       | 75.36%  |
| 1     | 58        | 20.71%  |
| 2     | 11        | 3.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 26.58%  |
| Graphics card            | 19        | 24.05%  |
| Net/wireless             | 17        | 21.52%  |
| Multimedia controller    | 14        | 17.72%  |
| Unassigned class         | 2         | 2.53%   |
| Bluetooth                | 2         | 2.53%   |
| Sound                    | 1         | 1.27%   |
| Modem                    | 1         | 1.27%   |
| Communication controller | 1         | 1.27%   |
| Chipcard                 | 1         | 1.27%   |

