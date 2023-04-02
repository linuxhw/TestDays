ROSA - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for ROSA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ROSA/Desktop/README.md) and [notebooks](/Dist/ROSA/Notebook/README.md).

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

Total: 41817

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 8906 SMVB                   | Desktop     | [74430f2160](https://linux-hardware.org/?probe=74430f2160) | Apr 01, 2023 |
| HP            | Presario CQ58               | Notebook    | [e8f8f289ac](https://linux-hardware.org/?probe=e8f8f289ac) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [978a5e2579](https://linux-hardware.org/?probe=978a5e2579) | Apr 01, 2023 |
| Toshiba       | Satellite S50-A-K7M         | Notebook    | [af163d8ec3](https://linux-hardware.org/?probe=af163d8ec3) | Apr 01, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [ac658bcb80](https://linux-hardware.org/?probe=ac658bcb80) | Apr 01, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [af64a32a09](https://linux-hardware.org/?probe=af64a32a09) | Apr 01, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [a6953d3b96](https://linux-hardware.org/?probe=a6953d3b96) | Apr 01, 2023 |
| Unknown       | X79                         | Desktop     | [d0592836a5](https://linux-hardware.org/?probe=d0592836a5) | Apr 01, 2023 |
| Lenovo        | ThinkPad X201s 514328U      | Notebook    | [011c475758](https://linux-hardware.org/?probe=011c475758) | Apr 01, 2023 |
| Acer          | WG43M                       | Desktop     | [77cb0bf517](https://linux-hardware.org/?probe=77cb0bf517) | Apr 01, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [5ed3be8dbc](https://linux-hardware.org/?probe=5ed3be8dbc) | Mar 31, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [74313ae73b](https://linux-hardware.org/?probe=74313ae73b) | Mar 31, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [51c601477f](https://linux-hardware.org/?probe=51c601477f) | Mar 31, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [323d8881a5](https://linux-hardware.org/?probe=323d8881a5) | Mar 31, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [573f5db37d](https://linux-hardware.org/?probe=573f5db37d) | Mar 31, 2023 |
| ASUSTek       | GL502VMK                    | Notebook    | [fe7f43d2db](https://linux-hardware.org/?probe=fe7f43d2db) | Mar 31, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [4d3e61950f](https://linux-hardware.org/?probe=4d3e61950f) | Mar 31, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8228733171](https://linux-hardware.org/?probe=8228733171) | Mar 31, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6df4368a49](https://linux-hardware.org/?probe=6df4368a49) | Mar 31, 2023 |
| ASUSTek       | X101H                       | Notebook    | [a8a30f0050](https://linux-hardware.org/?probe=a8a30f0050) | Mar 30, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [51f6d77f50](https://linux-hardware.org/?probe=51f6d77f50) | Mar 30, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [49a4903c58](https://linux-hardware.org/?probe=49a4903c58) | Mar 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8e7a5551df](https://linux-hardware.org/?probe=8e7a5551df) | Mar 30, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [d68a126b9b](https://linux-hardware.org/?probe=d68a126b9b) | Mar 30, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [04b9e48603](https://linux-hardware.org/?probe=04b9e48603) | Mar 30, 2023 |
| Dell          | Vostro 5468                 | Notebook    | [4ad7375ed0](https://linux-hardware.org/?probe=4ad7375ed0) | Mar 30, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [6bb5f276cd](https://linux-hardware.org/?probe=6bb5f276cd) | Mar 30, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [fecc161428](https://linux-hardware.org/?probe=fecc161428) | Mar 30, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [d88393be26](https://linux-hardware.org/?probe=d88393be26) | Mar 30, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [5938e606b6](https://linux-hardware.org/?probe=5938e606b6) | Mar 30, 2023 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0580e11b2f](https://linux-hardware.org/?probe=0580e11b2f) | Mar 29, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [f019265109](https://linux-hardware.org/?probe=f019265109) | Mar 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [e62607df55](https://linux-hardware.org/?probe=e62607df55) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d7fedcc338](https://linux-hardware.org/?probe=d7fedcc338) | Mar 29, 2023 |
| ASRock        | N68PV-GS                    | Desktop     | [1c473cd5c6](https://linux-hardware.org/?probe=1c473cd5c6) | Mar 29, 2023 |
| Gigabyte      | 945P-S3                     | Desktop     | [8aa985b6fa](https://linux-hardware.org/?probe=8aa985b6fa) | Mar 29, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [55a22382cc](https://linux-hardware.org/?probe=55a22382cc) | Mar 29, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [ca172328f1](https://linux-hardware.org/?probe=ca172328f1) | Mar 29, 2023 |
| Lenovo        | ThinkPad X201s 514328U      | Notebook    | [a6dbe138a5](https://linux-hardware.org/?probe=a6dbe138a5) | Mar 29, 2023 |
| Dell          | System XPS L702X            | Notebook    | [2c8aed8334](https://linux-hardware.org/?probe=2c8aed8334) | Mar 29, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [607219699e](https://linux-hardware.org/?probe=607219699e) | Mar 29, 2023 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [1f333c98e1](https://linux-hardware.org/?probe=1f333c98e1) | Mar 29, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [c0eeee7caf](https://linux-hardware.org/?probe=c0eeee7caf) | Mar 29, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [10fd7d1526](https://linux-hardware.org/?probe=10fd7d1526) | Mar 28, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [53543ce276](https://linux-hardware.org/?probe=53543ce276) | Mar 28, 2023 |
| Pegatron      | H36QR                       | Notebook    | [a9f1036ba5](https://linux-hardware.org/?probe=a9f1036ba5) | Mar 28, 2023 |
| Pegatron      | H36QR                       | Notebook    | [c3cf444e89](https://linux-hardware.org/?probe=c3cf444e89) | Mar 28, 2023 |
| HP            | Notebook                    | Notebook    | [f18d14ac70](https://linux-hardware.org/?probe=f18d14ac70) | Mar 28, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | Notebook    | [6e3a79c8b3](https://linux-hardware.org/?probe=6e3a79c8b3) | Mar 28, 2023 |
| MSI           | GE72 6QC                    | Notebook    | [6e593cf965](https://linux-hardware.org/?probe=6e593cf965) | Mar 28, 2023 |
| Gigabyte      | 946GMX-S2                   | Desktop     | [41f98f54fd](https://linux-hardware.org/?probe=41f98f54fd) | Mar 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d97a249a99](https://linux-hardware.org/?probe=d97a249a99) | Mar 28, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [b097373c25](https://linux-hardware.org/?probe=b097373c25) | Mar 28, 2023 |
| MSI           | 770-C45                     | Desktop     | [9b23a7e2d0](https://linux-hardware.org/?probe=9b23a7e2d0) | Mar 28, 2023 |
| Aquarius      | NS685U R11                  | Notebook    | [ecd08ca6d1](https://linux-hardware.org/?probe=ecd08ca6d1) | Mar 28, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [b8a7f41c86](https://linux-hardware.org/?probe=b8a7f41c86) | Mar 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [23438353bb](https://linux-hardware.org/?probe=23438353bb) | Mar 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c49cc33482](https://linux-hardware.org/?probe=c49cc33482) | Mar 28, 2023 |
| MSI           | MS-AA721 100                | All in one  | [f2703ea41c](https://linux-hardware.org/?probe=f2703ea41c) | Mar 28, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | Desktop     | [727f980b20](https://linux-hardware.org/?probe=727f980b20) | Mar 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b26a988f6](https://linux-hardware.org/?probe=0b26a988f6) | Mar 27, 2023 |
| Intel         | X79v2.72 KD V2.0            | Desktop     | [7b9dfca8cc](https://linux-hardware.org/?probe=7b9dfca8cc) | Mar 27, 2023 |
| Foxconn       | 2AA9                        | Desktop     | [97192fc35b](https://linux-hardware.org/?probe=97192fc35b) | Mar 27, 2023 |
| Acer          | NB-EX2510G-53DE             | Notebook    | [d331242786](https://linux-hardware.org/?probe=d331242786) | Mar 27, 2023 |
| Haier         | P1510SD                     | Notebook    | [8bba4e9b5f](https://linux-hardware.org/?probe=8bba4e9b5f) | Mar 27, 2023 |
| Pegatron      | A15                         | Notebook    | [2a0a6bdafc](https://linux-hardware.org/?probe=2a0a6bdafc) | Mar 27, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [696a8c86bf](https://linux-hardware.org/?probe=696a8c86bf) | Mar 27, 2023 |
| MSI           | GE72 6QC                    | Notebook    | [e7c328a9f5](https://linux-hardware.org/?probe=e7c328a9f5) | Mar 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [f5274197b8](https://linux-hardware.org/?probe=f5274197b8) | Mar 27, 2023 |
| MSI           | Katana GF76 11UE            | Notebook    | [b82e15f498](https://linux-hardware.org/?probe=b82e15f498) | Mar 27, 2023 |
| Sony          | VPCF13E8R                   | Notebook    | [a9c7f1d8bc](https://linux-hardware.org/?probe=a9c7f1d8bc) | Mar 27, 2023 |
| Dell          | Latitude E6430              | Notebook    | [ec464ade9c](https://linux-hardware.org/?probe=ec464ade9c) | Mar 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [6f77d9be36](https://linux-hardware.org/?probe=6f77d9be36) | Mar 26, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [797053b2f7](https://linux-hardware.org/?probe=797053b2f7) | Mar 26, 2023 |
| Gigabyte      | Z590 D                      | Desktop     | [095ade7803](https://linux-hardware.org/?probe=095ade7803) | Mar 26, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [36d80a146f](https://linux-hardware.org/?probe=36d80a146f) | Mar 26, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [38d87a8061](https://linux-hardware.org/?probe=38d87a8061) | Mar 26, 2023 |
| MSI           | GE72 6QC                    | Notebook    | [83793f19c1](https://linux-hardware.org/?probe=83793f19c1) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bbfe5423c9](https://linux-hardware.org/?probe=bbfe5423c9) | Mar 26, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [9d123ef87d](https://linux-hardware.org/?probe=9d123ef87d) | Mar 26, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [732b7b7fab](https://linux-hardware.org/?probe=732b7b7fab) | Mar 26, 2023 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [fff8f87d2a](https://linux-hardware.org/?probe=fff8f87d2a) | Mar 25, 2023 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [c33415cb2b](https://linux-hardware.org/?probe=c33415cb2b) | Mar 25, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [71fc8dc05c](https://linux-hardware.org/?probe=71fc8dc05c) | Mar 25, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [c98eac375f](https://linux-hardware.org/?probe=c98eac375f) | Mar 25, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [1879a953b7](https://linux-hardware.org/?probe=1879a953b7) | Mar 25, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [9ab6fd4ae0](https://linux-hardware.org/?probe=9ab6fd4ae0) | Mar 25, 2023 |
| Toshiba       | Satellite A500              | Notebook    | [cd79c573c6](https://linux-hardware.org/?probe=cd79c573c6) | Mar 25, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [f692116967](https://linux-hardware.org/?probe=f692116967) | Mar 25, 2023 |
| Dell          | 01TKCC A01                  | Desktop     | [c250d03840](https://linux-hardware.org/?probe=c250d03840) | Mar 25, 2023 |
| Samsung       | NC10                        | Notebook    | [96a0efc869](https://linux-hardware.org/?probe=96a0efc869) | Mar 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [e9d97f4745](https://linux-hardware.org/?probe=e9d97f4745) | Mar 25, 2023 |
| Sony          | VPCF1390X                   | Notebook    | [328d720f61](https://linux-hardware.org/?probe=328d720f61) | Mar 25, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [357a52fe14](https://linux-hardware.org/?probe=357a52fe14) | Mar 25, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [4150c3835d](https://linux-hardware.org/?probe=4150c3835d) | Mar 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f185ea819d](https://linux-hardware.org/?probe=f185ea819d) | Mar 24, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [b63ec78860](https://linux-hardware.org/?probe=b63ec78860) | Mar 24, 2023 |
| MACHINIST     | X99-RS9 V3.1                | Desktop     | [c1e2b5e7fb](https://linux-hardware.org/?probe=c1e2b5e7fb) | Mar 24, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [c310b97b8d](https://linux-hardware.org/?probe=c310b97b8d) | Mar 24, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [dbea63ed43](https://linux-hardware.org/?probe=dbea63ed43) | Mar 24, 2023 |
| Unknown       | Unknown                     | Notebook    | [17cc340907](https://linux-hardware.org/?probe=17cc340907) | Mar 24, 2023 |
| Unknown       | Unknown                     | Notebook    | [359168b631](https://linux-hardware.org/?probe=359168b631) | Mar 24, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a021e21c5f](https://linux-hardware.org/?probe=a021e21c5f) | Mar 24, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [e6219dd355](https://linux-hardware.org/?probe=e6219dd355) | Mar 24, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [18071acd7e](https://linux-hardware.org/?probe=18071acd7e) | Mar 24, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [ae7d4327f5](https://linux-hardware.org/?probe=ae7d4327f5) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [aa102c68bf](https://linux-hardware.org/?probe=aa102c68bf) | Mar 23, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [f517d6c26d](https://linux-hardware.org/?probe=f517d6c26d) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [8023b22765](https://linux-hardware.org/?probe=8023b22765) | Mar 23, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [03da177044](https://linux-hardware.org/?probe=03da177044) | Mar 23, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [f03dde8b73](https://linux-hardware.org/?probe=f03dde8b73) | Mar 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4efbf8be88](https://linux-hardware.org/?probe=4efbf8be88) | Mar 23, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [f16afa095b](https://linux-hardware.org/?probe=f16afa095b) | Mar 23, 2023 |
| HP            | 3048h                       | Desktop     | [8cee790d83](https://linux-hardware.org/?probe=8cee790d83) | Mar 23, 2023 |
| ASUSTek       | X556UB                      | Notebook    | [97a85936b2](https://linux-hardware.org/?probe=97a85936b2) | Mar 23, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [73d22216c2](https://linux-hardware.org/?probe=73d22216c2) | Mar 23, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [f170457555](https://linux-hardware.org/?probe=f170457555) | Mar 23, 2023 |
| ASUSTek       | K61IC                       | Notebook    | [b16fb0d3c8](https://linux-hardware.org/?probe=b16fb0d3c8) | Mar 23, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [577716237d](https://linux-hardware.org/?probe=577716237d) | Mar 22, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [2df8b64f07](https://linux-hardware.org/?probe=2df8b64f07) | Mar 22, 2023 |
| HP            | 635                         | Notebook    | [fef3dd1785](https://linux-hardware.org/?probe=fef3dd1785) | Mar 22, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [32fa1d46e2](https://linux-hardware.org/?probe=32fa1d46e2) | Mar 22, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [59a7093d9b](https://linux-hardware.org/?probe=59a7093d9b) | Mar 22, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [55d3d0217c](https://linux-hardware.org/?probe=55d3d0217c) | Mar 22, 2023 |
| MACHINIST     | X99-k9 V2.0                 | Desktop     | [24377b0218](https://linux-hardware.org/?probe=24377b0218) | Mar 22, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [957e5f5f8d](https://linux-hardware.org/?probe=957e5f5f8d) | Mar 22, 2023 |
| ASUSTek       | M2N-MX                      | Desktop     | [7eead8bd18](https://linux-hardware.org/?probe=7eead8bd18) | Mar 22, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [7d8950b25b](https://linux-hardware.org/?probe=7d8950b25b) | Mar 21, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [c58012d73d](https://linux-hardware.org/?probe=c58012d73d) | Mar 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a526417aaf](https://linux-hardware.org/?probe=a526417aaf) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e96b4f9ca9](https://linux-hardware.org/?probe=e96b4f9ca9) | Mar 21, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3a70b6918f](https://linux-hardware.org/?probe=3a70b6918f) | Mar 21, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [52b14963e3](https://linux-hardware.org/?probe=52b14963e3) | Mar 21, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [11e2caa120](https://linux-hardware.org/?probe=11e2caa120) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [e128423a13](https://linux-hardware.org/?probe=e128423a13) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [cf5df0e653](https://linux-hardware.org/?probe=cf5df0e653) | Mar 20, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [4df457f6bb](https://linux-hardware.org/?probe=4df457f6bb) | Mar 20, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [9a5bfcc056](https://linux-hardware.org/?probe=9a5bfcc056) | Mar 20, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [0648d2d9c3](https://linux-hardware.org/?probe=0648d2d9c3) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [9b2ff390f6](https://linux-hardware.org/?probe=9b2ff390f6) | Mar 20, 2023 |
| Acer          | Extensa 2509                | Notebook    | [8e0efd63c5](https://linux-hardware.org/?probe=8e0efd63c5) | Mar 20, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [2ef180bad0](https://linux-hardware.org/?probe=2ef180bad0) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5b1bccd269](https://linux-hardware.org/?probe=5b1bccd269) | Mar 20, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [e49b9e39d5](https://linux-hardware.org/?probe=e49b9e39d5) | Mar 20, 2023 |
| ASUSTek       | X751NV                      | Notebook    | [934e232587](https://linux-hardware.org/?probe=934e232587) | Mar 20, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [470a7a9123](https://linux-hardware.org/?probe=470a7a9123) | Mar 20, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [a48a2fbdd0](https://linux-hardware.org/?probe=a48a2fbdd0) | Mar 19, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [cd708d0e58](https://linux-hardware.org/?probe=cd708d0e58) | Mar 19, 2023 |
| Dell          | 01TKCC A01                  | Desktop     | [fd02c2aade](https://linux-hardware.org/?probe=fd02c2aade) | Mar 19, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [4f56864a63](https://linux-hardware.org/?probe=4f56864a63) | Mar 19, 2023 |
| Soyo          | SY-Classic B660M            | Desktop     | [cebe1d8722](https://linux-hardware.org/?probe=cebe1d8722) | Mar 19, 2023 |
| Lenovo        | ThinkPad T430 23493V2       | Notebook    | [96a7658d91](https://linux-hardware.org/?probe=96a7658d91) | Mar 19, 2023 |
| HP            | 0A54h                       | Desktop     | [6ec15582a7](https://linux-hardware.org/?probe=6ec15582a7) | Mar 19, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [82e7cb9669](https://linux-hardware.org/?probe=82e7cb9669) | Mar 19, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [4d50b47e95](https://linux-hardware.org/?probe=4d50b47e95) | Mar 19, 2023 |
| MB            | A320-SF110                  | Desktop     | [588c8f3fe5](https://linux-hardware.org/?probe=588c8f3fe5) | Mar 19, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [99096c6a78](https://linux-hardware.org/?probe=99096c6a78) | Mar 19, 2023 |
| ASUSTek       | N56DP                       | Notebook    | [c49dee996b](https://linux-hardware.org/?probe=c49dee996b) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e0a2f725e3](https://linux-hardware.org/?probe=e0a2f725e3) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a77ff93d75](https://linux-hardware.org/?probe=a77ff93d75) | Mar 19, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [8c50fc6c24](https://linux-hardware.org/?probe=8c50fc6c24) | Mar 19, 2023 |
| Supermicro    | X9SRL-F                     | Server      | [eef379bee2](https://linux-hardware.org/?probe=eef379bee2) | Mar 19, 2023 |
| Supermicro    | X9SRL-F                     | Server      | [87f035b169](https://linux-hardware.org/?probe=87f035b169) | Mar 18, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [2283637069](https://linux-hardware.org/?probe=2283637069) | Mar 18, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [1bedc9be7e](https://linux-hardware.org/?probe=1bedc9be7e) | Mar 18, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [bdb5c6a4ee](https://linux-hardware.org/?probe=bdb5c6a4ee) | Mar 18, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [caf54bddb9](https://linux-hardware.org/?probe=caf54bddb9) | Mar 18, 2023 |
| Positivo      | N6440                       | Notebook    | [98323051b5](https://linux-hardware.org/?probe=98323051b5) | Mar 18, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [d7d537c353](https://linux-hardware.org/?probe=d7d537c353) | Mar 18, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [213f4f774f](https://linux-hardware.org/?probe=213f4f774f) | Mar 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [b33066c1b7](https://linux-hardware.org/?probe=b33066c1b7) | Mar 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [233610a033](https://linux-hardware.org/?probe=233610a033) | Mar 18, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [94b8c06fdd](https://linux-hardware.org/?probe=94b8c06fdd) | Mar 18, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [e45da01a7e](https://linux-hardware.org/?probe=e45da01a7e) | Mar 18, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [877608b32b](https://linux-hardware.org/?probe=877608b32b) | Mar 18, 2023 |
| Acer          | Aspire 5310                 | Notebook    | [132691cbda](https://linux-hardware.org/?probe=132691cbda) | Mar 18, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [fe58227748](https://linux-hardware.org/?probe=fe58227748) | Mar 17, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [09541b3bdd](https://linux-hardware.org/?probe=09541b3bdd) | Mar 17, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [613aec2276](https://linux-hardware.org/?probe=613aec2276) | Mar 17, 2023 |
| Biostar       | G41-M7                      | Desktop     | [7109205ef0](https://linux-hardware.org/?probe=7109205ef0) | Mar 17, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [814c2e63c6](https://linux-hardware.org/?probe=814c2e63c6) | Mar 17, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [bb6be61738](https://linux-hardware.org/?probe=bb6be61738) | Mar 17, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e151d5d899](https://linux-hardware.org/?probe=e151d5d899) | Mar 17, 2023 |
| Biostar       | G41-M7                      | Desktop     | [b1fe372b7d](https://linux-hardware.org/?probe=b1fe372b7d) | Mar 17, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [be0d148aa6](https://linux-hardware.org/?probe=be0d148aa6) | Mar 17, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [3b591bcb12](https://linux-hardware.org/?probe=3b591bcb12) | Mar 17, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [97ef9205b5](https://linux-hardware.org/?probe=97ef9205b5) | Mar 17, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [244382a7f5](https://linux-hardware.org/?probe=244382a7f5) | Mar 17, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [f154cf28db](https://linux-hardware.org/?probe=f154cf28db) | Mar 16, 2023 |
| ASUSTek       | X55A                        | Notebook    | [5cf7c3643d](https://linux-hardware.org/?probe=5cf7c3643d) | Mar 16, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [2159ca2389](https://linux-hardware.org/?probe=2159ca2389) | Mar 16, 2023 |
| ASUSTek       | P7H57D-V EVO                | Desktop     | [f93f85e76d](https://linux-hardware.org/?probe=f93f85e76d) | Mar 16, 2023 |
| Lenovo        | ThinkPad X230 23245C8       | Notebook    | [7015f3b169](https://linux-hardware.org/?probe=7015f3b169) | Mar 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4b60a30117](https://linux-hardware.org/?probe=4b60a30117) | Mar 16, 2023 |
| ASUSTek       | N76VB                       | Notebook    | [20afa1889d](https://linux-hardware.org/?probe=20afa1889d) | Mar 15, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [727c7d3b7b](https://linux-hardware.org/?probe=727c7d3b7b) | Mar 15, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [dfe927cc13](https://linux-hardware.org/?probe=dfe927cc13) | Mar 15, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e128413357](https://linux-hardware.org/?probe=e128413357) | Mar 15, 2023 |
| ECS           | K8M890M-M                   | Desktop     | [f38e796f51](https://linux-hardware.org/?probe=f38e796f51) | Mar 15, 2023 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [95fcbd0967](https://linux-hardware.org/?probe=95fcbd0967) | Mar 15, 2023 |
| Gigabyte      | H55-UD3H                    | Desktop     | [bd69e8e59c](https://linux-hardware.org/?probe=bd69e8e59c) | Mar 15, 2023 |
| ASUSTek       | P5Q SE2                     | Desktop     | [4f76198c2d](https://linux-hardware.org/?probe=4f76198c2d) | Mar 15, 2023 |
| Acer          | Extensa 5630                | Notebook    | [e78d4a3c28](https://linux-hardware.org/?probe=e78d4a3c28) | Mar 14, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [98382222cd](https://linux-hardware.org/?probe=98382222cd) | Mar 14, 2023 |
| Acer          | Aspire 7110                 | Notebook    | [ec44273fd3](https://linux-hardware.org/?probe=ec44273fd3) | Mar 14, 2023 |
| ASUSTek       | 1215P                       | Notebook    | [7cfe211e09](https://linux-hardware.org/?probe=7cfe211e09) | Mar 14, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [31a56518c3](https://linux-hardware.org/?probe=31a56518c3) | Mar 14, 2023 |
| Lenovo        | ThinkPad X230 23245C8       | Notebook    | [5aaf852168](https://linux-hardware.org/?probe=5aaf852168) | Mar 14, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [25f7fa6e96](https://linux-hardware.org/?probe=25f7fa6e96) | Mar 14, 2023 |
| Lenovo        | V110-15AST 80TD             | Notebook    | [a574807ec1](https://linux-hardware.org/?probe=a574807ec1) | Mar 14, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [3d98403721](https://linux-hardware.org/?probe=3d98403721) | Mar 14, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [decf2fb7ba](https://linux-hardware.org/?probe=decf2fb7ba) | Mar 14, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [9084414030](https://linux-hardware.org/?probe=9084414030) | Mar 14, 2023 |
| ASRock        | H55M Pro                    | Desktop     | [fe7531d450](https://linux-hardware.org/?probe=fe7531d450) | Mar 14, 2023 |
| MSI           | 770-C45                     | Desktop     | [ec1fc57db4](https://linux-hardware.org/?probe=ec1fc57db4) | Mar 14, 2023 |
| ASUSTek       | P5K                         | Desktop     | [2257feac11](https://linux-hardware.org/?probe=2257feac11) | Mar 14, 2023 |
| Gigabyte      | E350N WIN8                  | Desktop     | [fd71263100](https://linux-hardware.org/?probe=fd71263100) | Mar 14, 2023 |
| eMachines     | eME730G                     | Notebook    | [ef96ec0313](https://linux-hardware.org/?probe=ef96ec0313) | Mar 14, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [72f5663d9d](https://linux-hardware.org/?probe=72f5663d9d) | Mar 13, 2023 |
| Intel         | X79                         | Desktop     | [ae742c13ae](https://linux-hardware.org/?probe=ae742c13ae) | Mar 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d4ebb8d458](https://linux-hardware.org/?probe=d4ebb8d458) | Mar 13, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [d0e82a7ba0](https://linux-hardware.org/?probe=d0e82a7ba0) | Mar 13, 2023 |
| MSI           | H61M-P32/W8                 | Desktop     | [9eefe8ac8e](https://linux-hardware.org/?probe=9eefe8ac8e) | Mar 13, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [b6d6f5ed8d](https://linux-hardware.org/?probe=b6d6f5ed8d) | Mar 13, 2023 |
| Acer          | Aspire one                  | Notebook    | [60c75cc14d](https://linux-hardware.org/?probe=60c75cc14d) | Mar 13, 2023 |
| Foxconn       | nT-330i                     | Desktop     | [e4b99289c7](https://linux-hardware.org/?probe=e4b99289c7) | Mar 13, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [84b199bf8b](https://linux-hardware.org/?probe=84b199bf8b) | Mar 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [e78843ce7e](https://linux-hardware.org/?probe=e78843ce7e) | Mar 13, 2023 |
| ECS           | K8M890M-M                   | Desktop     | [5adfeea7d1](https://linux-hardware.org/?probe=5adfeea7d1) | Mar 12, 2023 |
| Acer          | Aspire one                  | Notebook    | [c3d7bc326a](https://linux-hardware.org/?probe=c3d7bc326a) | Mar 12, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [3103d0f0c2](https://linux-hardware.org/?probe=3103d0f0c2) | Mar 12, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [0e89d9279d](https://linux-hardware.org/?probe=0e89d9279d) | Mar 12, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [8541575b10](https://linux-hardware.org/?probe=8541575b10) | Mar 12, 2023 |
| Fujitsu       | D2778-D1 S26361-D2778-D1    | Desktop     | [092aec6abe](https://linux-hardware.org/?probe=092aec6abe) | Mar 12, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [1f3f97f186](https://linux-hardware.org/?probe=1f3f97f186) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge 13IAL# 019... | Notebook    | [1d91216d1b](https://linux-hardware.org/?probe=1d91216d1b) | Mar 12, 2023 |
| Pegatron      | C15B                        | Notebook    | [539f4fbf7a](https://linux-hardware.org/?probe=539f4fbf7a) | Mar 12, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b1df269b3c](https://linux-hardware.org/?probe=b1df269b3c) | Mar 12, 2023 |
| ASUSTek       | GL702VM                     | Notebook    | [62a45a1b6d](https://linux-hardware.org/?probe=62a45a1b6d) | Mar 12, 2023 |
| Dell          | 0M859N A00                  | Desktop     | [4de136eea0](https://linux-hardware.org/?probe=4de136eea0) | Mar 11, 2023 |
| ASUSTek       | GL702VM                     | Notebook    | [ae185a2005](https://linux-hardware.org/?probe=ae185a2005) | Mar 11, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [3633c704cc](https://linux-hardware.org/?probe=3633c704cc) | Mar 11, 2023 |
| Supermicro    | X9SRL-F                     | Server      | [dceb5c3175](https://linux-hardware.org/?probe=dceb5c3175) | Mar 11, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [c249ea9094](https://linux-hardware.org/?probe=c249ea9094) | Mar 11, 2023 |
| Supermicro    | X9SRL-F                     | Server      | [c0880336e5](https://linux-hardware.org/?probe=c0880336e5) | Mar 11, 2023 |
| ASUSTek       | M3400WUA                    | All in one  | [e593179048](https://linux-hardware.org/?probe=e593179048) | Mar 11, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [70fe849438](https://linux-hardware.org/?probe=70fe849438) | Mar 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [a909644dc4](https://linux-hardware.org/?probe=a909644dc4) | Mar 11, 2023 |
| ASUSTek       | X541NC                      | Notebook    | [d7e16d4472](https://linux-hardware.org/?probe=d7e16d4472) | Mar 11, 2023 |
| Sony          | SVE1713P1RB                 | Notebook    | [efa148ef67](https://linux-hardware.org/?probe=efa148ef67) | Mar 11, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [816307ec8e](https://linux-hardware.org/?probe=816307ec8e) | Mar 11, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [d479ffc245](https://linux-hardware.org/?probe=d479ffc245) | Mar 11, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c3c00e99aa](https://linux-hardware.org/?probe=c3c00e99aa) | Mar 11, 2023 |
| ASUSTek       | K46CM                       | Notebook    | [e0cce23d86](https://linux-hardware.org/?probe=e0cce23d86) | Mar 11, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [c9c401bdb5](https://linux-hardware.org/?probe=c9c401bdb5) | Mar 11, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [849ea0e3dc](https://linux-hardware.org/?probe=849ea0e3dc) | Mar 11, 2023 |
| ASUSTek       | K53SM                       | Notebook    | [aa3efc3683](https://linux-hardware.org/?probe=aa3efc3683) | Mar 11, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [811704abe4](https://linux-hardware.org/?probe=811704abe4) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [bd2a89f7c1](https://linux-hardware.org/?probe=bd2a89f7c1) | Mar 11, 2023 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [ccd888c89f](https://linux-hardware.org/?probe=ccd888c89f) | Mar 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [a6dc5e13d0](https://linux-hardware.org/?probe=a6dc5e13d0) | Mar 10, 2023 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [058f4d66e2](https://linux-hardware.org/?probe=058f4d66e2) | Mar 10, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [fb2f4741e9](https://linux-hardware.org/?probe=fb2f4741e9) | Mar 10, 2023 |
| Dell          | Vostro 5581                 | Notebook    | [72b648b75c](https://linux-hardware.org/?probe=72b648b75c) | Mar 10, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [9260aaddc7](https://linux-hardware.org/?probe=9260aaddc7) | Mar 10, 2023 |
| Dell          | Vostro 5581                 | Notebook    | [c7a13194c8](https://linux-hardware.org/?probe=c7a13194c8) | Mar 10, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [b38727d178](https://linux-hardware.org/?probe=b38727d178) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [d64a783d3a](https://linux-hardware.org/?probe=d64a783d3a) | Mar 10, 2023 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [cd975ff510](https://linux-hardware.org/?probe=cd975ff510) | Mar 10, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [898271efb7](https://linux-hardware.org/?probe=898271efb7) | Mar 09, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [249f986099](https://linux-hardware.org/?probe=249f986099) | Mar 09, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | Desktop     | [271d259059](https://linux-hardware.org/?probe=271d259059) | Mar 08, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [6bc8cc9c28](https://linux-hardware.org/?probe=6bc8cc9c28) | Mar 08, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | Desktop     | [4cb9932b91](https://linux-hardware.org/?probe=4cb9932b91) | Mar 08, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [3b83e42348](https://linux-hardware.org/?probe=3b83e42348) | Mar 08, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [ef22a14cc5](https://linux-hardware.org/?probe=ef22a14cc5) | Mar 08, 2023 |
| HP            | Compaq 610                  | Notebook    | [3f5ffc0582](https://linux-hardware.org/?probe=3f5ffc0582) | Mar 08, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [5785eede0a](https://linux-hardware.org/?probe=5785eede0a) | Mar 08, 2023 |
| Gigabyte      | 8IPE1000-G                  | Desktop     | [58d94793e2](https://linux-hardware.org/?probe=58d94793e2) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [38c0ccd72e](https://linux-hardware.org/?probe=38c0ccd72e) | Mar 08, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [246f8d46b3](https://linux-hardware.org/?probe=246f8d46b3) | Mar 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c4c9827316](https://linux-hardware.org/?probe=c4c9827316) | Mar 08, 2023 |
| ASUSTek       | P5Q-EM                      | Desktop     | [371913da58](https://linux-hardware.org/?probe=371913da58) | Mar 08, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [1f5114d6a5](https://linux-hardware.org/?probe=1f5114d6a5) | Mar 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [ce2373e31a](https://linux-hardware.org/?probe=ce2373e31a) | Mar 07, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [55883b5a5d](https://linux-hardware.org/?probe=55883b5a5d) | Mar 07, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [9ff521edc3](https://linux-hardware.org/?probe=9ff521edc3) | Mar 07, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [887c698c7d](https://linux-hardware.org/?probe=887c698c7d) | Mar 07, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [46fa342e07](https://linux-hardware.org/?probe=46fa342e07) | Mar 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a5841cbe8f](https://linux-hardware.org/?probe=a5841cbe8f) | Mar 07, 2023 |
| Acer          | Aspire C22-820              | All in one  | [07d4bf17aa](https://linux-hardware.org/?probe=07d4bf17aa) | Mar 06, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [00b928f630](https://linux-hardware.org/?probe=00b928f630) | Mar 06, 2023 |
| Sony          | SVT1313X9RS                 | Notebook    | [c2766f4ac5](https://linux-hardware.org/?probe=c2766f4ac5) | Mar 06, 2023 |
| Lenovo        | ThinkPad Edge 03014EG       | Notebook    | [e3186561ef](https://linux-hardware.org/?probe=e3186561ef) | Mar 06, 2023 |
| Acer          | Aspire M3-581TG             | Notebook    | [2f8939e9ed](https://linux-hardware.org/?probe=2f8939e9ed) | Mar 06, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [6faa586824](https://linux-hardware.org/?probe=6faa586824) | Mar 06, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [efd6fd1985](https://linux-hardware.org/?probe=efd6fd1985) | Mar 06, 2023 |
| EPoX Compu... | MCP61S DDR2: AGF6110-M S... | Desktop     | [537087cc72](https://linux-hardware.org/?probe=537087cc72) | Mar 06, 2023 |
| HP            | 2B0A                        | All in one  | [35f88e8f33](https://linux-hardware.org/?probe=35f88e8f33) | Mar 06, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [2c8192e064](https://linux-hardware.org/?probe=2c8192e064) | Mar 06, 2023 |
| Acer          | Aspire 4253G                | Notebook    | [80228255b2](https://linux-hardware.org/?probe=80228255b2) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f85824345a](https://linux-hardware.org/?probe=f85824345a) | Mar 06, 2023 |
| EPoX Compu... | NF550/570 DDR2: AF550/57... | Desktop     | [de616ef63b](https://linux-hardware.org/?probe=de616ef63b) | Mar 06, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [3884dbf23c](https://linux-hardware.org/?probe=3884dbf23c) | Mar 05, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [36b6cd2a7e](https://linux-hardware.org/?probe=36b6cd2a7e) | Mar 05, 2023 |
| Toshiba       | Satellite U300              | Notebook    | [6e33105e71](https://linux-hardware.org/?probe=6e33105e71) | Mar 05, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [1f391b4852](https://linux-hardware.org/?probe=1f391b4852) | Mar 05, 2023 |
| ASUSTek       | X102BA                      | Notebook    | [6c425f0640](https://linux-hardware.org/?probe=6c425f0640) | Mar 05, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [93b1720fa7](https://linux-hardware.org/?probe=93b1720fa7) | Mar 05, 2023 |
| ASUSTek       | V6J                         | Notebook    | [10819a91fd](https://linux-hardware.org/?probe=10819a91fd) | Mar 05, 2023 |
| Biostar       | A320MH                      | Desktop     | [f4701d1a66](https://linux-hardware.org/?probe=f4701d1a66) | Mar 05, 2023 |
| Lenovo        | 371D 31900002 WIN 180194... | All in one  | [2bd3cdbc37](https://linux-hardware.org/?probe=2bd3cdbc37) | Mar 05, 2023 |
| ASUSTek       | M51Tr                       | Notebook    | [3d4d35a9a7](https://linux-hardware.org/?probe=3d4d35a9a7) | Mar 05, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [e42a2e580a](https://linux-hardware.org/?probe=e42a2e580a) | Mar 05, 2023 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [8555857264](https://linux-hardware.org/?probe=8555857264) | Mar 05, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b51b70bc1a](https://linux-hardware.org/?probe=b51b70bc1a) | Mar 05, 2023 |
| Gigabyte      | H110M-D3H R2-CF             | Desktop     | [35866f074d](https://linux-hardware.org/?probe=35866f074d) | Mar 04, 2023 |
| Acer          | Aspire V3-551G              | Notebook    | [ae3684f7c7](https://linux-hardware.org/?probe=ae3684f7c7) | Mar 04, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [268e27cc20](https://linux-hardware.org/?probe=268e27cc20) | Mar 04, 2023 |
| Samsung       | R530/R730                   | Notebook    | [277c940c6b](https://linux-hardware.org/?probe=277c940c6b) | Mar 04, 2023 |
| Sony          | VPCZ12S9R                   | Notebook    | [bbc4c5d9ae](https://linux-hardware.org/?probe=bbc4c5d9ae) | Mar 04, 2023 |
| ASUSTek       | K53TA                       | Notebook    | [5bfd8132fb](https://linux-hardware.org/?probe=5bfd8132fb) | Mar 04, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [eadfad8fc8](https://linux-hardware.org/?probe=eadfad8fc8) | Mar 04, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [17889079ab](https://linux-hardware.org/?probe=17889079ab) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [dd9492dd43](https://linux-hardware.org/?probe=dd9492dd43) | Mar 03, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [0e8d1a9e75](https://linux-hardware.org/?probe=0e8d1a9e75) | Mar 03, 2023 |
| ASUSTek       | PN52                        | Mini pc     | [5f0d451ee3](https://linux-hardware.org/?probe=5f0d451ee3) | Mar 03, 2023 |
| eMachines     | eM355                       | Notebook    | [a882cab474](https://linux-hardware.org/?probe=a882cab474) | Mar 03, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [c76495f7b0](https://linux-hardware.org/?probe=c76495f7b0) | Mar 03, 2023 |
| ASUSTek       | PN52                        | Mini pc     | [820f30037a](https://linux-hardware.org/?probe=820f30037a) | Mar 03, 2023 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [55b187db64](https://linux-hardware.org/?probe=55b187db64) | Mar 03, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [89a9f53a7e](https://linux-hardware.org/?probe=89a9f53a7e) | Mar 03, 2023 |
| ASUSTek       | F5SL                        | Notebook    | [c959885e6f](https://linux-hardware.org/?probe=c959885e6f) | Mar 03, 2023 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [db674213ce](https://linux-hardware.org/?probe=db674213ce) | Mar 03, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [771fd25f9d](https://linux-hardware.org/?probe=771fd25f9d) | Mar 02, 2023 |
| Acer          | Aspire 3690                 | Notebook    | [6f2794495c](https://linux-hardware.org/?probe=6f2794495c) | Mar 02, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [8c7ab87113](https://linux-hardware.org/?probe=8c7ab87113) | Mar 02, 2023 |
| AMI           | Aptio CRB E220AQ-600        | Mini pc     | [f341b62f96](https://linux-hardware.org/?probe=f341b62f96) | Mar 02, 2023 |
| Intel         | H61                         | Desktop     | [7bc298c53d](https://linux-hardware.org/?probe=7bc298c53d) | Mar 02, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ee48e03827](https://linux-hardware.org/?probe=ee48e03827) | Mar 02, 2023 |
| Irbis         | 15NBC1000                   | Notebook    | [c10f6c3c00](https://linux-hardware.org/?probe=c10f6c3c00) | Mar 02, 2023 |
| ASUSTek       | K40AF                       | Notebook    | [09472e2548](https://linux-hardware.org/?probe=09472e2548) | Mar 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [ad513cea88](https://linux-hardware.org/?probe=ad513cea88) | Mar 02, 2023 |
| Acer          | Aspire 3690                 | Notebook    | [36266c4a83](https://linux-hardware.org/?probe=36266c4a83) | Mar 02, 2023 |
| Maibenben     | XiaoMai5                    | Notebook    | [f4f5217397](https://linux-hardware.org/?probe=f4f5217397) | Mar 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ea9a7523dc](https://linux-hardware.org/?probe=ea9a7523dc) | Mar 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0a096e93c1](https://linux-hardware.org/?probe=0a096e93c1) | Mar 01, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | Desktop     | [ada9b78c86](https://linux-hardware.org/?probe=ada9b78c86) | Mar 01, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [0befe28d1b](https://linux-hardware.org/?probe=0befe28d1b) | Mar 01, 2023 |
| Lenovo        | 370C No DPK                 | All in one  | [ae16b78fa0](https://linux-hardware.org/?probe=ae16b78fa0) | Mar 01, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [e137d431d2](https://linux-hardware.org/?probe=e137d431d2) | Mar 01, 2023 |
| ASUSTek       | K53TK                       | Notebook    | [09398155fc](https://linux-hardware.org/?probe=09398155fc) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [ee3aeec484](https://linux-hardware.org/?probe=ee3aeec484) | Mar 01, 2023 |
| Biostar       | A320MH                      | Desktop     | [d1f48d6cab](https://linux-hardware.org/?probe=d1f48d6cab) | Mar 01, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [a37a935237](https://linux-hardware.org/?probe=a37a935237) | Mar 01, 2023 |
| ASUSTek       | K40AF                       | Notebook    | [71ec4e0527](https://linux-hardware.org/?probe=71ec4e0527) | Mar 01, 2023 |
| Acer          | AOHAPPY2                    | Notebook    | [9bbd271b36](https://linux-hardware.org/?probe=9bbd271b36) | Feb 28, 2023 |
| HP            | ProLiant ML350 G5           | Desktop     | [073427bc3c](https://linux-hardware.org/?probe=073427bc3c) | Feb 28, 2023 |
| HP            | ProLiant ML350 Gen9         | Desktop     | [bbad31d175](https://linux-hardware.org/?probe=bbad31d175) | Feb 28, 2023 |
| HP            | 255 G2                      | Notebook    | [10397efd1b](https://linux-hardware.org/?probe=10397efd1b) | Feb 28, 2023 |
| MSI           | MS-7210 100                 | Desktop     | [5cb2d5ea2c](https://linux-hardware.org/?probe=5cb2d5ea2c) | Feb 28, 2023 |
| MSI           | MS-7210 100                 | Desktop     | [a541b48e4d](https://linux-hardware.org/?probe=a541b48e4d) | Feb 28, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [882168458c](https://linux-hardware.org/?probe=882168458c) | Feb 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [e4bb117847](https://linux-hardware.org/?probe=e4bb117847) | Feb 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [732f6c8c00](https://linux-hardware.org/?probe=732f6c8c00) | Feb 27, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [394ad3d24f](https://linux-hardware.org/?probe=394ad3d24f) | Feb 27, 2023 |
| Gigabyte      | B365M D2V                   | Desktop     | [aa39313621](https://linux-hardware.org/?probe=aa39313621) | Feb 27, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3696f0b49e](https://linux-hardware.org/?probe=3696f0b49e) | Feb 27, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [e3090d9725](https://linux-hardware.org/?probe=e3090d9725) | Feb 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7936e7db49](https://linux-hardware.org/?probe=7936e7db49) | Feb 27, 2023 |
| Acer          | Aspire 3690                 | Notebook    | [c93af7d4eb](https://linux-hardware.org/?probe=c93af7d4eb) | Feb 27, 2023 |
| Acer          | Aspire 3690                 | Notebook    | [b119bda1a6](https://linux-hardware.org/?probe=b119bda1a6) | Feb 27, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [ffdac8fa88](https://linux-hardware.org/?probe=ffdac8fa88) | Feb 27, 2023 |
| Sony          | VPCSB2L1R                   | Notebook    | [6ed9bd210d](https://linux-hardware.org/?probe=6ed9bd210d) | Feb 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [e8e3f57eef](https://linux-hardware.org/?probe=e8e3f57eef) | Feb 26, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [9f543932d2](https://linux-hardware.org/?probe=9f543932d2) | Feb 26, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [2986fb12e2](https://linux-hardware.org/?probe=2986fb12e2) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8d8e5bc41d](https://linux-hardware.org/?probe=8d8e5bc41d) | Feb 26, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [77a5832b3f](https://linux-hardware.org/?probe=77a5832b3f) | Feb 26, 2023 |
| Dell          | 0UP453                      | Desktop     | [e45bff8252](https://linux-hardware.org/?probe=e45bff8252) | Feb 26, 2023 |
| Acer          | AOHAPPY2                    | Notebook    | [830a1212b7](https://linux-hardware.org/?probe=830a1212b7) | Feb 26, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [05c92ac080](https://linux-hardware.org/?probe=05c92ac080) | Feb 26, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [2fe5c30b13](https://linux-hardware.org/?probe=2fe5c30b13) | Feb 26, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [4b96538701](https://linux-hardware.org/?probe=4b96538701) | Feb 26, 2023 |
| Acer          | Extensa 2519                | Notebook    | [b80f0bc182](https://linux-hardware.org/?probe=b80f0bc182) | Feb 26, 2023 |
| Acer          | Extensa 2519                | Notebook    | [3ee3fea5eb](https://linux-hardware.org/?probe=3ee3fea5eb) | Feb 26, 2023 |
| ASRock        | 880GM-LE                    | Desktop     | [32366172e4](https://linux-hardware.org/?probe=32366172e4) | Feb 26, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [887241ec59](https://linux-hardware.org/?probe=887241ec59) | Feb 26, 2023 |
| eMachines     | Rhine V1.42                 | Notebook    | [c0c7b48991](https://linux-hardware.org/?probe=c0c7b48991) | Feb 26, 2023 |
| Unknown       | Intel X79                   | Desktop     | [0f7920afd6](https://linux-hardware.org/?probe=0f7920afd6) | Feb 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [b4e0540b00](https://linux-hardware.org/?probe=b4e0540b00) | Feb 25, 2023 |
| Acer          | Aspire Z1-601               | All in one  | [dd0dffa557](https://linux-hardware.org/?probe=dd0dffa557) | Feb 25, 2023 |
| HP            | 1497                        | Desktop     | [bd24913452](https://linux-hardware.org/?probe=bd24913452) | Feb 24, 2023 |
| HP            | 1497                        | Desktop     | [ebf580cb5d](https://linux-hardware.org/?probe=ebf580cb5d) | Feb 24, 2023 |
| ASUSTek       | P5Q-EM                      | Desktop     | [3fef9c126a](https://linux-hardware.org/?probe=3fef9c126a) | Feb 24, 2023 |
| ASRock        | 760GM-GS3                   | Desktop     | [5440ad3270](https://linux-hardware.org/?probe=5440ad3270) | Feb 24, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [8fa16a1dec](https://linux-hardware.org/?probe=8fa16a1dec) | Feb 24, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [6b7b16645d](https://linux-hardware.org/?probe=6b7b16645d) | Feb 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9c0b9ff47a](https://linux-hardware.org/?probe=9c0b9ff47a) | Feb 24, 2023 |
| Toshiba       | Satellite U300              | Notebook    | [d5973ad69a](https://linux-hardware.org/?probe=d5973ad69a) | Feb 24, 2023 |
| Lenovo        | ThinkPad X201 3680U6V       | Notebook    | [abcf384939](https://linux-hardware.org/?probe=abcf384939) | Feb 23, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [4cddc9362b](https://linux-hardware.org/?probe=4cddc9362b) | Feb 23, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [accb966ada](https://linux-hardware.org/?probe=accb966ada) | Feb 23, 2023 |
| Acer          | AOHAPPY2                    | Notebook    | [a7a5e4b46c](https://linux-hardware.org/?probe=a7a5e4b46c) | Feb 23, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [8b1222a755](https://linux-hardware.org/?probe=8b1222a755) | Feb 23, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e76bd912f8](https://linux-hardware.org/?probe=e76bd912f8) | Feb 23, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [7d6e4cd766](https://linux-hardware.org/?probe=7d6e4cd766) | Feb 23, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [59a1b07ad5](https://linux-hardware.org/?probe=59a1b07ad5) | Feb 23, 2023 |
| Dell          | XPS 15 9575                 | Convertible | [38981fcd34](https://linux-hardware.org/?probe=38981fcd34) | Feb 22, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [3dab1052d4](https://linux-hardware.org/?probe=3dab1052d4) | Feb 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b7071da133](https://linux-hardware.org/?probe=b7071da133) | Feb 22, 2023 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [564ecd80d9](https://linux-hardware.org/?probe=564ecd80d9) | Feb 22, 2023 |
| Unknown       | NF-CK804                    | Desktop     | [3dd6239815](https://linux-hardware.org/?probe=3dd6239815) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [feea587fef](https://linux-hardware.org/?probe=feea587fef) | Feb 22, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [c56e36cd0e](https://linux-hardware.org/?probe=c56e36cd0e) | Feb 22, 2023 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [af3c7b2459](https://linux-hardware.org/?probe=af3c7b2459) | Feb 22, 2023 |
| Toshiba       | Satellite A300D             | Notebook    | [fd0d9d5ba1](https://linux-hardware.org/?probe=fd0d9d5ba1) | Feb 22, 2023 |
| ASUSTek       | X551CAP                     | Notebook    | [1ed860d561](https://linux-hardware.org/?probe=1ed860d561) | Feb 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [caff81fa5f](https://linux-hardware.org/?probe=caff81fa5f) | Feb 20, 2023 |
| Samsung       | N102                        | Notebook    | [736977f523](https://linux-hardware.org/?probe=736977f523) | Feb 20, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [132a805814](https://linux-hardware.org/?probe=132a805814) | Feb 20, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [5b0cf6bef1](https://linux-hardware.org/?probe=5b0cf6bef1) | Feb 20, 2023 |
| Haier         | A1410ED                     | Notebook    | [0188ad4a9b](https://linux-hardware.org/?probe=0188ad4a9b) | Feb 20, 2023 |
| Haier         | A1410ED                     | Notebook    | [0551c42cf8](https://linux-hardware.org/?probe=0551c42cf8) | Feb 20, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [c9d8617e08](https://linux-hardware.org/?probe=c9d8617e08) | Feb 20, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5bcd20c966](https://linux-hardware.org/?probe=5bcd20c966) | Feb 20, 2023 |
| Intel         | X79M-S                      | Desktop     | [89ac8fc3ce](https://linux-hardware.org/?probe=89ac8fc3ce) | Feb 20, 2023 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [509f76c7ec](https://linux-hardware.org/?probe=509f76c7ec) | Feb 20, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [45e185354c](https://linux-hardware.org/?probe=45e185354c) | Feb 20, 2023 |
| Gigabyte      | 945P-S3                     | Desktop     | [2cdcb107ab](https://linux-hardware.org/?probe=2cdcb107ab) | Feb 20, 2023 |
| DNS           | MB40IA1                     | Notebook    | [9aaf027f52](https://linux-hardware.org/?probe=9aaf027f52) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [c0032d4f0b](https://linux-hardware.org/?probe=c0032d4f0b) | Feb 19, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [82ab7aabe2](https://linux-hardware.org/?probe=82ab7aabe2) | Feb 19, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [970f04658e](https://linux-hardware.org/?probe=970f04658e) | Feb 19, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [331f606733](https://linux-hardware.org/?probe=331f606733) | Feb 19, 2023 |
| HP            | Unknown                     | Notebook    | [69b276cb01](https://linux-hardware.org/?probe=69b276cb01) | Feb 19, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [87c921a93a](https://linux-hardware.org/?probe=87c921a93a) | Feb 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b27447bfa3](https://linux-hardware.org/?probe=b27447bfa3) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [b8b41b7a6e](https://linux-hardware.org/?probe=b8b41b7a6e) | Feb 19, 2023 |
| ASUSTek       | M51Sn                       | Notebook    | [999f32a65f](https://linux-hardware.org/?probe=999f32a65f) | Feb 18, 2023 |
| Gigabyte      | H410M S2H                   | Desktop     | [bdb8c0094b](https://linux-hardware.org/?probe=bdb8c0094b) | Feb 18, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [75db698bfd](https://linux-hardware.org/?probe=75db698bfd) | Feb 18, 2023 |
| OEM           | Intel H81                   | Desktop     | [2dc44e8ff2](https://linux-hardware.org/?probe=2dc44e8ff2) | Feb 18, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [1fc2c6c2f5](https://linux-hardware.org/?probe=1fc2c6c2f5) | Feb 18, 2023 |
| Samsung       | R519/R719                   | Notebook    | [17524cf177](https://linux-hardware.org/?probe=17524cf177) | Feb 18, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [f70df82711](https://linux-hardware.org/?probe=f70df82711) | Feb 18, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [cbe7b5e34f](https://linux-hardware.org/?probe=cbe7b5e34f) | Feb 18, 2023 |
| Biostar       | H61MLB                      | Desktop     | [b79584c7c9](https://linux-hardware.org/?probe=b79584c7c9) | Feb 18, 2023 |
| Acer          | AOHAPPY2                    | Notebook    | [1f71a1ad75](https://linux-hardware.org/?probe=1f71a1ad75) | Feb 18, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [f9000d049e](https://linux-hardware.org/?probe=f9000d049e) | Feb 17, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [55a53738ee](https://linux-hardware.org/?probe=55a53738ee) | Feb 17, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [3faff8d320](https://linux-hardware.org/?probe=3faff8d320) | Feb 17, 2023 |
| MSI           | B460M PRO-VDH               | Desktop     | [38f8f579be](https://linux-hardware.org/?probe=38f8f579be) | Feb 17, 2023 |
| HP            | 3031h                       | Desktop     | [f3d2748999](https://linux-hardware.org/?probe=f3d2748999) | Feb 17, 2023 |
| Acer          | Aspire 5540                 | Notebook    | [ce25cbe4f9](https://linux-hardware.org/?probe=ce25cbe4f9) | Feb 17, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9187251796](https://linux-hardware.org/?probe=9187251796) | Feb 17, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [1ceaa9af7d](https://linux-hardware.org/?probe=1ceaa9af7d) | Feb 17, 2023 |
| ASRock        | 760GM-GS3                   | Desktop     | [88433e4e24](https://linux-hardware.org/?probe=88433e4e24) | Feb 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [650a873a5a](https://linux-hardware.org/?probe=650a873a5a) | Feb 16, 2023 |
| Intel         | DP67BA AAG10219-300         | Desktop     | [8fc0c69640](https://linux-hardware.org/?probe=8fc0c69640) | Feb 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4b78132251](https://linux-hardware.org/?probe=4b78132251) | Feb 16, 2023 |
| MSI           | G41M-P28                    | Desktop     | [85efceb14b](https://linux-hardware.org/?probe=85efceb14b) | Feb 16, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [f0f2625313](https://linux-hardware.org/?probe=f0f2625313) | Feb 15, 2023 |
| Toshiba       | Satellite U300              | Notebook    | [3925a92635](https://linux-hardware.org/?probe=3925a92635) | Feb 15, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [bc0fe319be](https://linux-hardware.org/?probe=bc0fe319be) | Feb 15, 2023 |
| ASRock        | Z77 Pro3                    | Desktop     | [095671c1c9](https://linux-hardware.org/?probe=095671c1c9) | Feb 15, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [261e3ca363](https://linux-hardware.org/?probe=261e3ca363) | Feb 15, 2023 |
| Unknown       | X79A                        | Desktop     | [4cf2d15d70](https://linux-hardware.org/?probe=4cf2d15d70) | Feb 14, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [e856a4629d](https://linux-hardware.org/?probe=e856a4629d) | Feb 14, 2023 |
| ASRock        | AQH410T                     | Desktop     | [9ca03a8dcd](https://linux-hardware.org/?probe=9ca03a8dcd) | Feb 14, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [0da8e9ac4c](https://linux-hardware.org/?probe=0da8e9ac4c) | Feb 14, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [da50295fcc](https://linux-hardware.org/?probe=da50295fcc) | Feb 14, 2023 |
| ICL           | RAYbook Si1512              | Notebook    | [d1565e917f](https://linux-hardware.org/?probe=d1565e917f) | Feb 14, 2023 |
| ICL           | RAYbook Si1512              | Notebook    | [aba6ac482b](https://linux-hardware.org/?probe=aba6ac482b) | Feb 14, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2120a2f3b5](https://linux-hardware.org/?probe=2120a2f3b5) | Feb 13, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [6338542845](https://linux-hardware.org/?probe=6338542845) | Feb 13, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [409d6e3cb3](https://linux-hardware.org/?probe=409d6e3cb3) | Feb 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c66b51a84d](https://linux-hardware.org/?probe=c66b51a84d) | Feb 13, 2023 |
| Unknown       | X133                        | Notebook    | [537237c180](https://linux-hardware.org/?probe=537237c180) | Feb 13, 2023 |
| AMI           | Aptio CRB E220AQ-600        | Mini pc     | [b93e11cebc](https://linux-hardware.org/?probe=b93e11cebc) | Feb 13, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [e3580e73af](https://linux-hardware.org/?probe=e3580e73af) | Feb 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [55a63c3dce](https://linux-hardware.org/?probe=55a63c3dce) | Feb 13, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [570fd77e58](https://linux-hardware.org/?probe=570fd77e58) | Feb 13, 2023 |
| Biostar       | A320MH                      | Desktop     | [d51405079c](https://linux-hardware.org/?probe=d51405079c) | Feb 13, 2023 |
| WeiBu         | Aptio CRB                   | Mini pc     | [183e716ff5](https://linux-hardware.org/?probe=183e716ff5) | Feb 13, 2023 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [8bf6aedf43](https://linux-hardware.org/?probe=8bf6aedf43) | Feb 12, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [7b98ade6b1](https://linux-hardware.org/?probe=7b98ade6b1) | Feb 12, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [8f60713f8a](https://linux-hardware.org/?probe=8f60713f8a) | Feb 12, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [06dc671402](https://linux-hardware.org/?probe=06dc671402) | Feb 12, 2023 |
| Haier         | A1410ED                     | Notebook    | [5c90c9c566](https://linux-hardware.org/?probe=5c90c9c566) | Feb 12, 2023 |
| MSI           | MS-7369                     | Desktop     | [f2d9a7a428](https://linux-hardware.org/?probe=f2d9a7a428) | Feb 12, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [4b94eea923](https://linux-hardware.org/?probe=4b94eea923) | Feb 12, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [15b41bf352](https://linux-hardware.org/?probe=15b41bf352) | Feb 12, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [eeda09fb13](https://linux-hardware.org/?probe=eeda09fb13) | Feb 12, 2023 |
| Sony          | SVE14A2V1RWI                | Notebook    | [09509862be](https://linux-hardware.org/?probe=09509862be) | Feb 12, 2023 |
| MSI           | 770-C45                     | Desktop     | [80cd4311f5](https://linux-hardware.org/?probe=80cd4311f5) | Feb 12, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [faf97ec5ac](https://linux-hardware.org/?probe=faf97ec5ac) | Feb 12, 2023 |
| OEM           | Intel H81                   | Desktop     | [89ca7b56ce](https://linux-hardware.org/?probe=89ca7b56ce) | Feb 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [b090683ed1](https://linux-hardware.org/?probe=b090683ed1) | Feb 12, 2023 |
| Unknown       | X79A                        | Desktop     | [d2cdf88906](https://linux-hardware.org/?probe=d2cdf88906) | Feb 12, 2023 |
| Medion        | TJ4105                      | Desktop     | [b9f44d3290](https://linux-hardware.org/?probe=b9f44d3290) | Feb 11, 2023 |
| ASUSTek       | 1025C                       | Notebook    | [a5ae0e6be9](https://linux-hardware.org/?probe=a5ae0e6be9) | Feb 11, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [0207d4f5eb](https://linux-hardware.org/?probe=0207d4f5eb) | Feb 11, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [4a3b0fd844](https://linux-hardware.org/?probe=4a3b0fd844) | Feb 11, 2023 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [2a6b583e08](https://linux-hardware.org/?probe=2a6b583e08) | Feb 11, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [fc04f9445d](https://linux-hardware.org/?probe=fc04f9445d) | Feb 11, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [226310e919](https://linux-hardware.org/?probe=226310e919) | Feb 10, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [d88dcef939](https://linux-hardware.org/?probe=d88dcef939) | Feb 10, 2023 |
| IBM           | ThinkPad T41 23731HG        | Notebook    | [3f4c1d8c96](https://linux-hardware.org/?probe=3f4c1d8c96) | Feb 10, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [ad01ef1c97](https://linux-hardware.org/?probe=ad01ef1c97) | Feb 10, 2023 |
| Lenovo        | G70-80 80FF                 | Notebook    | [ade67f432f](https://linux-hardware.org/?probe=ade67f432f) | Feb 10, 2023 |
| EPoX Compu... | nForce4 DDR: 9NPA3I / 9N... | Desktop     | [978c5bad53](https://linux-hardware.org/?probe=978c5bad53) | Feb 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5e82ed12a7](https://linux-hardware.org/?probe=5e82ed12a7) | Feb 10, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [31d8a68d71](https://linux-hardware.org/?probe=31d8a68d71) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [2a366ac100](https://linux-hardware.org/?probe=2a366ac100) | Feb 09, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [5e29ff0071](https://linux-hardware.org/?probe=5e29ff0071) | Feb 09, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6cd301542b](https://linux-hardware.org/?probe=6cd301542b) | Feb 09, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [5644272d9e](https://linux-hardware.org/?probe=5644272d9e) | Feb 09, 2023 |
| Unknown       | X99H                        | Desktop     | [722aafff41](https://linux-hardware.org/?probe=722aafff41) | Feb 09, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [f501974f04](https://linux-hardware.org/?probe=f501974f04) | Feb 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [d0f9bc7752](https://linux-hardware.org/?probe=d0f9bc7752) | Feb 09, 2023 |
| Intel         | DG31PR AAD97573-301         | Desktop     | [665f8e7d81](https://linux-hardware.org/?probe=665f8e7d81) | Feb 09, 2023 |
| Notebook      | W65_67SJ                    | Notebook    | [6f4b26218a](https://linux-hardware.org/?probe=6f4b26218a) | Feb 08, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ea138517da](https://linux-hardware.org/?probe=ea138517da) | Feb 08, 2023 |
| Notebook      | W65_67SJ                    | Notebook    | [1736d50901](https://linux-hardware.org/?probe=1736d50901) | Feb 08, 2023 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [6c056321fa](https://linux-hardware.org/?probe=6c056321fa) | Feb 08, 2023 |
| Samsung       | R519/R719                   | Notebook    | [b67d6600ae](https://linux-hardware.org/?probe=b67d6600ae) | Feb 08, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [cd84a3ed54](https://linux-hardware.org/?probe=cd84a3ed54) | Feb 08, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [0c02735e75](https://linux-hardware.org/?probe=0c02735e75) | Feb 08, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [5872694b2c](https://linux-hardware.org/?probe=5872694b2c) | Feb 08, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [8fb4060e1f](https://linux-hardware.org/?probe=8fb4060e1f) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c3fd4be797](https://linux-hardware.org/?probe=c3fd4be797) | Feb 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [133f0c845d](https://linux-hardware.org/?probe=133f0c845d) | Feb 07, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [d7157a7862](https://linux-hardware.org/?probe=d7157a7862) | Feb 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [e58b6f75be](https://linux-hardware.org/?probe=e58b6f75be) | Feb 07, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [1620065d9c](https://linux-hardware.org/?probe=1620065d9c) | Feb 07, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [8d7cca4218](https://linux-hardware.org/?probe=8d7cca4218) | Feb 07, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2a21f87922](https://linux-hardware.org/?probe=2a21f87922) | Feb 07, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [35c52844f5](https://linux-hardware.org/?probe=35c52844f5) | Feb 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [b6c83b73c5](https://linux-hardware.org/?probe=b6c83b73c5) | Feb 07, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [6745d62f6e](https://linux-hardware.org/?probe=6745d62f6e) | Feb 07, 2023 |
| THUNDEROBO... | 911 Plus                    | Notebook    | [63fe672aa8](https://linux-hardware.org/?probe=63fe672aa8) | Feb 07, 2023 |
| HP            | 0AA0h                       | Desktop     | [921b7f0d0c](https://linux-hardware.org/?probe=921b7f0d0c) | Feb 07, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [62a01ed1f1](https://linux-hardware.org/?probe=62a01ed1f1) | Feb 07, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [079f741109](https://linux-hardware.org/?probe=079f741109) | Feb 07, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [04d1d12416](https://linux-hardware.org/?probe=04d1d12416) | Feb 07, 2023 |
| Toshiba       | Satellite C870-196          | Notebook    | [85ded7d8d0](https://linux-hardware.org/?probe=85ded7d8d0) | Feb 06, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [ab4ab47498](https://linux-hardware.org/?probe=ab4ab47498) | Feb 06, 2023 |
| MSI           | U90/U100                    | Notebook    | [f7dc915782](https://linux-hardware.org/?probe=f7dc915782) | Feb 06, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [89ff251118](https://linux-hardware.org/?probe=89ff251118) | Feb 06, 2023 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [32c834326a](https://linux-hardware.org/?probe=32c834326a) | Feb 06, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [b045a54f0b](https://linux-hardware.org/?probe=b045a54f0b) | Feb 06, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [47f300cd75](https://linux-hardware.org/?probe=47f300cd75) | Feb 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ebbbcf807a](https://linux-hardware.org/?probe=ebbbcf807a) | Feb 06, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [b644932b49](https://linux-hardware.org/?probe=b644932b49) | Feb 06, 2023 |
| Acer          | FMCP7A-ION-LE               | Desktop     | [4567c6a09c](https://linux-hardware.org/?probe=4567c6a09c) | Feb 06, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [9d66ef100a](https://linux-hardware.org/?probe=9d66ef100a) | Feb 06, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [d93258a6f8](https://linux-hardware.org/?probe=d93258a6f8) | Feb 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ebe7e665d6](https://linux-hardware.org/?probe=ebe7e665d6) | Feb 05, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [8884f6f6dd](https://linux-hardware.org/?probe=8884f6f6dd) | Feb 05, 2023 |
| Huanan        | X79 VAA1                    | Desktop     | [62888124bd](https://linux-hardware.org/?probe=62888124bd) | Feb 05, 2023 |
| Acer          | WG43M                       | Desktop     | [e463181f54](https://linux-hardware.org/?probe=e463181f54) | Feb 05, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d6cea67f50](https://linux-hardware.org/?probe=d6cea67f50) | Feb 05, 2023 |
| THUNDEROBO... | 911 Plus                    | Notebook    | [bae8523a8a](https://linux-hardware.org/?probe=bae8523a8a) | Feb 05, 2023 |
| Sony          | VPCY11M1R                   | Notebook    | [2de520036a](https://linux-hardware.org/?probe=2de520036a) | Feb 05, 2023 |
| ASUSTek       | M2N                         | Desktop     | [cc5d457ca6](https://linux-hardware.org/?probe=cc5d457ca6) | Feb 05, 2023 |
| ASRock        | A75M-HVS                    | Desktop     | [74c7bde15c](https://linux-hardware.org/?probe=74c7bde15c) | Feb 05, 2023 |
| HP            | Notebook                    | Notebook    | [ad5aca71c1](https://linux-hardware.org/?probe=ad5aca71c1) | Feb 04, 2023 |
| ASUSTek       | M4A785T-M                   | Desktop     | [5402edfed1](https://linux-hardware.org/?probe=5402edfed1) | Feb 04, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [b95575866c](https://linux-hardware.org/?probe=b95575866c) | Feb 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b71a6e4da9](https://linux-hardware.org/?probe=b71a6e4da9) | Feb 04, 2023 |
| Lenovo        | 3746 No DPK                 | All in one  | [3b66e6134f](https://linux-hardware.org/?probe=3b66e6134f) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4214ad8f29](https://linux-hardware.org/?probe=4214ad8f29) | Feb 04, 2023 |
| MSI           | GP60 2OD                    | Notebook    | [5c91f4e591](https://linux-hardware.org/?probe=5c91f4e591) | Feb 03, 2023 |
| JGINYUE       | H97I GAMING V1.0            | Desktop     | [d83687e8ea](https://linux-hardware.org/?probe=d83687e8ea) | Feb 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [c26575b761](https://linux-hardware.org/?probe=c26575b761) | Feb 03, 2023 |
| Graviton      | DMB-H610-TMI01              | All in one  | [53c72256da](https://linux-hardware.org/?probe=53c72256da) | Feb 03, 2023 |
| MSI           | GP60 2OD                    | Notebook    | [6820f98769](https://linux-hardware.org/?probe=6820f98769) | Feb 03, 2023 |
| Biostar       | A320MH                      | Desktop     | [61f708d874](https://linux-hardware.org/?probe=61f708d874) | Feb 03, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [f26da18faa](https://linux-hardware.org/?probe=f26da18faa) | Feb 02, 2023 |
| MSI           | 770-C45                     | Desktop     | [fa06564503](https://linux-hardware.org/?probe=fa06564503) | Feb 02, 2023 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [0021264c10](https://linux-hardware.org/?probe=0021264c10) | Feb 02, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [e29b47f46f](https://linux-hardware.org/?probe=e29b47f46f) | Feb 02, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [044d301912](https://linux-hardware.org/?probe=044d301912) | Feb 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b3fc9704f0](https://linux-hardware.org/?probe=b3fc9704f0) | Feb 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3b016839cd](https://linux-hardware.org/?probe=3b016839cd) | Feb 02, 2023 |
| Biostar       | G41-M7                      | Desktop     | [862afd5a70](https://linux-hardware.org/?probe=862afd5a70) | Feb 01, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [477504bfc6](https://linux-hardware.org/?probe=477504bfc6) | Feb 01, 2023 |
| MSI           | MS-N0E1 Ver                 | Notebook    | [9c4dcef9c6](https://linux-hardware.org/?probe=9c4dcef9c6) | Feb 01, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [c790793197](https://linux-hardware.org/?probe=c790793197) | Feb 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [de3138b686](https://linux-hardware.org/?probe=de3138b686) | Feb 01, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [86156a3b50](https://linux-hardware.org/?probe=86156a3b50) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e53e3c6e8](https://linux-hardware.org/?probe=7e53e3c6e8) | Jan 31, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [204706229b](https://linux-hardware.org/?probe=204706229b) | Jan 31, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [f5379a55ea](https://linux-hardware.org/?probe=f5379a55ea) | Jan 31, 2023 |
| ASUSTek       | H110-PLUS                   | Desktop     | [c20a43e3e5](https://linux-hardware.org/?probe=c20a43e3e5) | Jan 31, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [260d257a0c](https://linux-hardware.org/?probe=260d257a0c) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [4830eacf5e](https://linux-hardware.org/?probe=4830eacf5e) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [0b59b68d55](https://linux-hardware.org/?probe=0b59b68d55) | Jan 30, 2023 |
| MSI           | GL75 Leopard 10SCSR         | Notebook    | [8e30762127](https://linux-hardware.org/?probe=8e30762127) | Jan 30, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [10c275723f](https://linux-hardware.org/?probe=10c275723f) | Jan 30, 2023 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [8f41c8cf5c](https://linux-hardware.org/?probe=8f41c8cf5c) | Jan 30, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [d826805d37](https://linux-hardware.org/?probe=d826805d37) | Jan 30, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [54f6c27c09](https://linux-hardware.org/?probe=54f6c27c09) | Jan 30, 2023 |
| ZoomSmart     | A1002                       | Tablet      | [f8733ffc4d](https://linux-hardware.org/?probe=f8733ffc4d) | Jan 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [d25ed40cf3](https://linux-hardware.org/?probe=d25ed40cf3) | Jan 30, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [a7232f4811](https://linux-hardware.org/?probe=a7232f4811) | Jan 30, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [7359bcfbfb](https://linux-hardware.org/?probe=7359bcfbfb) | Jan 29, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [c8c73a9f67](https://linux-hardware.org/?probe=c8c73a9f67) | Jan 29, 2023 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [183bb56595](https://linux-hardware.org/?probe=183bb56595) | Jan 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [868269808a](https://linux-hardware.org/?probe=868269808a) | Jan 29, 2023 |
| ASRock        | P45DE3                      | Desktop     | [e4c2e737f7](https://linux-hardware.org/?probe=e4c2e737f7) | Jan 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [23d04579d4](https://linux-hardware.org/?probe=23d04579d4) | Jan 29, 2023 |
| ASRock        | Z77M                        | Desktop     | [83a27ed2b5](https://linux-hardware.org/?probe=83a27ed2b5) | Jan 29, 2023 |
| ASRock        | G41M-S3                     | Desktop     | [2196343afa](https://linux-hardware.org/?probe=2196343afa) | Jan 29, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [943a02b7e9](https://linux-hardware.org/?probe=943a02b7e9) | Jan 29, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [c52b5b3357](https://linux-hardware.org/?probe=c52b5b3357) | Jan 29, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [e768563b42](https://linux-hardware.org/?probe=e768563b42) | Jan 29, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [93e0f40842](https://linux-hardware.org/?probe=93e0f40842) | Jan 29, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [017467452c](https://linux-hardware.org/?probe=017467452c) | Jan 29, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [2fb747792d](https://linux-hardware.org/?probe=2fb747792d) | Jan 29, 2023 |
| ASUSTek       | X550MJ                      | Notebook    | [51fd1f6c24](https://linux-hardware.org/?probe=51fd1f6c24) | Jan 28, 2023 |
| Unknown       | X79                         | Desktop     | [164508bcb4](https://linux-hardware.org/?probe=164508bcb4) | Jan 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8492e549e2](https://linux-hardware.org/?probe=8492e549e2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | Desktop     | [836e9a9809](https://linux-hardware.org/?probe=836e9a9809) | Jan 28, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [be48644835](https://linux-hardware.org/?probe=be48644835) | Jan 27, 2023 |
| ASUSTek       | M2N-MX                      | Desktop     | [0920c10a0e](https://linux-hardware.org/?probe=0920c10a0e) | Jan 27, 2023 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [8289da39ca](https://linux-hardware.org/?probe=8289da39ca) | Jan 27, 2023 |
| ASUSTek       | N56DP                       | Notebook    | [a746d3fd78](https://linux-hardware.org/?probe=a746d3fd78) | Jan 27, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [547e171057](https://linux-hardware.org/?probe=547e171057) | Jan 27, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [6ad6470149](https://linux-hardware.org/?probe=6ad6470149) | Jan 27, 2023 |
| Acer          | Aspire 5532                 | Notebook    | [88e8887c6c](https://linux-hardware.org/?probe=88e8887c6c) | Jan 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [7ce2ff0443](https://linux-hardware.org/?probe=7ce2ff0443) | Jan 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [acbaa4516c](https://linux-hardware.org/?probe=acbaa4516c) | Jan 27, 2023 |
| Clevo         | M770SUA                     | Notebook    | [3a19bae169](https://linux-hardware.org/?probe=3a19bae169) | Jan 27, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [ecd1e46811](https://linux-hardware.org/?probe=ecd1e46811) | Jan 27, 2023 |
| Lenovo        | G480 20156                  | Notebook    | [9e09139dbc](https://linux-hardware.org/?probe=9e09139dbc) | Jan 26, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [ddc52a086f](https://linux-hardware.org/?probe=ddc52a086f) | Jan 26, 2023 |
| MSI           | 770-C45                     | Desktop     | [3da3ee46c2](https://linux-hardware.org/?probe=3da3ee46c2) | Jan 26, 2023 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [7f70263934](https://linux-hardware.org/?probe=7f70263934) | Jan 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [02dffce8d7](https://linux-hardware.org/?probe=02dffce8d7) | Jan 26, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [1033fae7e9](https://linux-hardware.org/?probe=1033fae7e9) | Jan 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6290f61a46](https://linux-hardware.org/?probe=6290f61a46) | Jan 26, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [e9f4894d6d](https://linux-hardware.org/?probe=e9f4894d6d) | Jan 26, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [8c568dd8e5](https://linux-hardware.org/?probe=8c568dd8e5) | Jan 26, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [34c55ab8ae](https://linux-hardware.org/?probe=34c55ab8ae) | Jan 26, 2023 |
| iRU           | v1.0                        | Desktop     | [5dfa804f74](https://linux-hardware.org/?probe=5dfa804f74) | Jan 26, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [0b25483160](https://linux-hardware.org/?probe=0b25483160) | Jan 26, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [ee7b9f5fd0](https://linux-hardware.org/?probe=ee7b9f5fd0) | Jan 26, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [883b4a1c39](https://linux-hardware.org/?probe=883b4a1c39) | Jan 26, 2023 |
| MSI           | 770-C45                     | Desktop     | [42ffd24c35](https://linux-hardware.org/?probe=42ffd24c35) | Jan 25, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [ee6e7a2924](https://linux-hardware.org/?probe=ee6e7a2924) | Jan 25, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [fe11977488](https://linux-hardware.org/?probe=fe11977488) | Jan 25, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c2867457c2](https://linux-hardware.org/?probe=c2867457c2) | Jan 25, 2023 |
| MSI           | 770-C45                     | Desktop     | [1991e96ff2](https://linux-hardware.org/?probe=1991e96ff2) | Jan 25, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [d56d0b1732](https://linux-hardware.org/?probe=d56d0b1732) | Jan 25, 2023 |
| Acer          | Extensa 2540                | Notebook    | [af5b1ea485](https://linux-hardware.org/?probe=af5b1ea485) | Jan 25, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [41b1ad4545](https://linux-hardware.org/?probe=41b1ad4545) | Jan 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [8a7a7f6b72](https://linux-hardware.org/?probe=8a7a7f6b72) | Jan 25, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [a9dace6356](https://linux-hardware.org/?probe=a9dace6356) | Jan 24, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [e7afbd79e9](https://linux-hardware.org/?probe=e7afbd79e9) | Jan 24, 2023 |
| ZoomSmart     | A1002                       | Tablet      | [9bfc68ab23](https://linux-hardware.org/?probe=9bfc68ab23) | Jan 24, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | Notebook    | [3b1ce8fc77](https://linux-hardware.org/?probe=3b1ce8fc77) | Jan 24, 2023 |
| Alienware     | 18                          | Notebook    | [982870ed1f](https://linux-hardware.org/?probe=982870ed1f) | Jan 24, 2023 |
| Alienware     | 18                          | Notebook    | [afe83f1946](https://linux-hardware.org/?probe=afe83f1946) | Jan 24, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [e8e7a44a2a](https://linux-hardware.org/?probe=e8e7a44a2a) | Jan 24, 2023 |
| Biostar       | G41-M7                      | Desktop     | [3f66a61637](https://linux-hardware.org/?probe=3f66a61637) | Jan 24, 2023 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [770e25fefd](https://linux-hardware.org/?probe=770e25fefd) | Jan 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e2d597c046](https://linux-hardware.org/?probe=e2d597c046) | Jan 24, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [416a11089a](https://linux-hardware.org/?probe=416a11089a) | Jan 23, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [0a7ef9990f](https://linux-hardware.org/?probe=0a7ef9990f) | Jan 23, 2023 |
| Acer          | Extensa 5630                | Notebook    | [ae62db30e8](https://linux-hardware.org/?probe=ae62db30e8) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [257f3b320c](https://linux-hardware.org/?probe=257f3b320c) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [10fa3eeed2](https://linux-hardware.org/?probe=10fa3eeed2) | Jan 23, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [6d55940af7](https://linux-hardware.org/?probe=6d55940af7) | Jan 23, 2023 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [18fdd7a490](https://linux-hardware.org/?probe=18fdd7a490) | Jan 23, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [77d58eb890](https://linux-hardware.org/?probe=77d58eb890) | Jan 23, 2023 |
| Samsung       | N148P/N208P/N218P/NB28P     | Notebook    | [f665dc3839](https://linux-hardware.org/?probe=f665dc3839) | Jan 23, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [37f26b2f10](https://linux-hardware.org/?probe=37f26b2f10) | Jan 23, 2023 |
| ASUSTek       | Z97-C                       | Desktop     | [3a89f39a8f](https://linux-hardware.org/?probe=3a89f39a8f) | Jan 23, 2023 |
| Samsung       | NC10                        | Notebook    | [6bd13301d9](https://linux-hardware.org/?probe=6bd13301d9) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [b1ced07f7b](https://linux-hardware.org/?probe=b1ced07f7b) | Jan 22, 2023 |
| HP            | ProBook 5330m               | Notebook    | [989327864b](https://linux-hardware.org/?probe=989327864b) | Jan 22, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [167dae47d7](https://linux-hardware.org/?probe=167dae47d7) | Jan 22, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [0e1605a304](https://linux-hardware.org/?probe=0e1605a304) | Jan 22, 2023 |
| MSI           | CR500                       | Notebook    | [4aaddddd7f](https://linux-hardware.org/?probe=4aaddddd7f) | Jan 22, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [bd85a7e96e](https://linux-hardware.org/?probe=bd85a7e96e) | Jan 22, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [ecfd1795a0](https://linux-hardware.org/?probe=ecfd1795a0) | Jan 22, 2023 |
| ASRock        | B360 Pro4                   | Desktop     | [9cd508a59c](https://linux-hardware.org/?probe=9cd508a59c) | Jan 22, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a0b3d87534](https://linux-hardware.org/?probe=a0b3d87534) | Jan 22, 2023 |
| Huanan        | H97-ZD3 V2.0                | Desktop     | [afb82fa3cf](https://linux-hardware.org/?probe=afb82fa3cf) | Jan 22, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [569626e023](https://linux-hardware.org/?probe=569626e023) | Jan 22, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [c861b7e450](https://linux-hardware.org/?probe=c861b7e450) | Jan 22, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [0bf19053f1](https://linux-hardware.org/?probe=0bf19053f1) | Jan 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7d63d494c6](https://linux-hardware.org/?probe=7d63d494c6) | Jan 21, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [0d5c4881c1](https://linux-hardware.org/?probe=0d5c4881c1) | Jan 21, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [9672c4222a](https://linux-hardware.org/?probe=9672c4222a) | Jan 21, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [18efa12cb2](https://linux-hardware.org/?probe=18efa12cb2) | Jan 21, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [df4c3bb4d2](https://linux-hardware.org/?probe=df4c3bb4d2) | Jan 21, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [3f270588f4](https://linux-hardware.org/?probe=3f270588f4) | Jan 21, 2023 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [f2dff18301](https://linux-hardware.org/?probe=f2dff18301) | Jan 21, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [cdc37dfe5e](https://linux-hardware.org/?probe=cdc37dfe5e) | Jan 20, 2023 |
| Sony          | VGN-FJ3SR_B                 | Notebook    | [4dc8b8d09d](https://linux-hardware.org/?probe=4dc8b8d09d) | Jan 20, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [712d12e3e9](https://linux-hardware.org/?probe=712d12e3e9) | Jan 20, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [b3df4a1dfa](https://linux-hardware.org/?probe=b3df4a1dfa) | Jan 20, 2023 |
| Lenovo        | B450                        | Notebook    | [96b87672bf](https://linux-hardware.org/?probe=96b87672bf) | Jan 20, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [459b2e28d0](https://linux-hardware.org/?probe=459b2e28d0) | Jan 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [4ebd222ef1](https://linux-hardware.org/?probe=4ebd222ef1) | Jan 20, 2023 |
| ECS           | G41T-M7                     | Desktop     | [e6be57e3c3](https://linux-hardware.org/?probe=e6be57e3c3) | Jan 20, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [9abd51692e](https://linux-hardware.org/?probe=9abd51692e) | Jan 20, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f44f319e21](https://linux-hardware.org/?probe=f44f319e21) | Jan 20, 2023 |
| Huanan        | X99-F8D V2.4                | Desktop     | [26bc61b381](https://linux-hardware.org/?probe=26bc61b381) | Jan 19, 2023 |
| AZW           | U59                         | Desktop     | [6621409d8c](https://linux-hardware.org/?probe=6621409d8c) | Jan 19, 2023 |
| Biostar       | A780LB                      | Desktop     | [ffce251f42](https://linux-hardware.org/?probe=ffce251f42) | Jan 19, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [348a5d1848](https://linux-hardware.org/?probe=348a5d1848) | Jan 19, 2023 |
| Lenovo        | G70-80 80FF                 | Notebook    | [1ce03f27f3](https://linux-hardware.org/?probe=1ce03f27f3) | Jan 19, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [cfe663eeb9](https://linux-hardware.org/?probe=cfe663eeb9) | Jan 19, 2023 |
| ASUSTek       | P4P800                      | Desktop     | [f37bee349c](https://linux-hardware.org/?probe=f37bee349c) | Jan 18, 2023 |
| Intel         | DG41MJ AAE54659-206         | Desktop     | [98a0ca82de](https://linux-hardware.org/?probe=98a0ca82de) | Jan 18, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [42bf8b9a0d](https://linux-hardware.org/?probe=42bf8b9a0d) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [82eea2cc7b](https://linux-hardware.org/?probe=82eea2cc7b) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [02a6db2951](https://linux-hardware.org/?probe=02a6db2951) | Jan 18, 2023 |
| Lenovo        | ThinkCentre M57e 6305B2U    | Desktop     | [fbd4306314](https://linux-hardware.org/?probe=fbd4306314) | Jan 18, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [a42e9dbc36](https://linux-hardware.org/?probe=a42e9dbc36) | Jan 18, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [d4147630a1](https://linux-hardware.org/?probe=d4147630a1) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [a9de8742d5](https://linux-hardware.org/?probe=a9de8742d5) | Jan 17, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [ac58bc440d](https://linux-hardware.org/?probe=ac58bc440d) | Jan 17, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [2024f1ae76](https://linux-hardware.org/?probe=2024f1ae76) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b01089cba7](https://linux-hardware.org/?probe=b01089cba7) | Jan 17, 2023 |
| Biostar       | A780LB                      | Desktop     | [fe4d79e9f8](https://linux-hardware.org/?probe=fe4d79e9f8) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bffcece8fb](https://linux-hardware.org/?probe=bffcece8fb) | Jan 17, 2023 |
| HP            | Notebook                    | Notebook    | [a998060574](https://linux-hardware.org/?probe=a998060574) | Jan 17, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [bdfe91e3c9](https://linux-hardware.org/?probe=bdfe91e3c9) | Jan 17, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [4507d2f32d](https://linux-hardware.org/?probe=4507d2f32d) | Jan 17, 2023 |
| ASUSTek       | P12R-E Series 60SB0A90-S... | Server      | [f4bf235ea8](https://linux-hardware.org/?probe=f4bf235ea8) | Jan 17, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [e3638a2110](https://linux-hardware.org/?probe=e3638a2110) | Jan 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [df0f33ee66](https://linux-hardware.org/?probe=df0f33ee66) | Jan 16, 2023 |
| Intel         | X99                         | Desktop     | [f966e7aa92](https://linux-hardware.org/?probe=f966e7aa92) | Jan 16, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [37891c1ea9](https://linux-hardware.org/?probe=37891c1ea9) | Jan 16, 2023 |
| Huanan        | H97-ZD3 V2.0                | Desktop     | [aececc6971](https://linux-hardware.org/?probe=aececc6971) | Jan 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [363f8daa52](https://linux-hardware.org/?probe=363f8daa52) | Jan 16, 2023 |
| MSI           | 970A-G43                    | Desktop     | [f15370df26](https://linux-hardware.org/?probe=f15370df26) | Jan 16, 2023 |
| ECS           | G41T-M7                     | Desktop     | [51a45a431a](https://linux-hardware.org/?probe=51a45a431a) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | Desktop     | [2ebeb3fa1a](https://linux-hardware.org/?probe=2ebeb3fa1a) | Jan 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [84f591bd6b](https://linux-hardware.org/?probe=84f591bd6b) | Jan 16, 2023 |
| HP            | Notebook                    | Notebook    | [219540f0f7](https://linux-hardware.org/?probe=219540f0f7) | Jan 16, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [c1660ab5a4](https://linux-hardware.org/?probe=c1660ab5a4) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | Desktop     | [939ab29431](https://linux-hardware.org/?probe=939ab29431) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2ec1685227](https://linux-hardware.org/?probe=2ec1685227) | Jan 15, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f51c90cadc](https://linux-hardware.org/?probe=f51c90cadc) | Jan 15, 2023 |
| MSI           | 970A-G43                    | Desktop     | [669512ff6c](https://linux-hardware.org/?probe=669512ff6c) | Jan 15, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [832efe11f1](https://linux-hardware.org/?probe=832efe11f1) | Jan 15, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [d412197c51](https://linux-hardware.org/?probe=d412197c51) | Jan 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bf4ea0ba42](https://linux-hardware.org/?probe=bf4ea0ba42) | Jan 15, 2023 |
| Kraftway      | ACCORD                      | Notebook    | [63039ae17f](https://linux-hardware.org/?probe=63039ae17f) | Jan 15, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [b5b29198b0](https://linux-hardware.org/?probe=b5b29198b0) | Jan 15, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [fe4b311f78](https://linux-hardware.org/?probe=fe4b311f78) | Jan 15, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [adc92101d7](https://linux-hardware.org/?probe=adc92101d7) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a65831f165](https://linux-hardware.org/?probe=a65831f165) | Jan 15, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [af5169b24d](https://linux-hardware.org/?probe=af5169b24d) | Jan 15, 2023 |
| Irbis         | NB264                       | Notebook    | [ed534a1d30](https://linux-hardware.org/?probe=ed534a1d30) | Jan 15, 2023 |
| HP            | 15                          | Notebook    | [6df03629da](https://linux-hardware.org/?probe=6df03629da) | Jan 15, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [282e0e478f](https://linux-hardware.org/?probe=282e0e478f) | Jan 15, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [c59c9570d6](https://linux-hardware.org/?probe=c59c9570d6) | Jan 14, 2023 |
| HP            | 84EE 1100                   | All in one  | [79c81fcfb5](https://linux-hardware.org/?probe=79c81fcfb5) | Jan 14, 2023 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | Notebook    | [17487f7b28](https://linux-hardware.org/?probe=17487f7b28) | Jan 14, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | Notebook    | [fd3560384c](https://linux-hardware.org/?probe=fd3560384c) | Jan 14, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [6fc2ac2b48](https://linux-hardware.org/?probe=6fc2ac2b48) | Jan 14, 2023 |
| HP            | Mini 110-3700               | Notebook    | [564cb84405](https://linux-hardware.org/?probe=564cb84405) | Jan 14, 2023 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | Notebook    | [a02f812ef3](https://linux-hardware.org/?probe=a02f812ef3) | Jan 14, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [69819d1ce1](https://linux-hardware.org/?probe=69819d1ce1) | Jan 14, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [64e3a1d972](https://linux-hardware.org/?probe=64e3a1d972) | Jan 14, 2023 |
| Dell          | Inspiron ME051              | Notebook    | [853b489238](https://linux-hardware.org/?probe=853b489238) | Jan 14, 2023 |
| Dell          | Inspiron ME051              | Notebook    | [e806b368b7](https://linux-hardware.org/?probe=e806b368b7) | Jan 14, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [7c5f173e5c](https://linux-hardware.org/?probe=7c5f173e5c) | Jan 13, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [7cde78238f](https://linux-hardware.org/?probe=7cde78238f) | Jan 13, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [ae418043f3](https://linux-hardware.org/?probe=ae418043f3) | Jan 13, 2023 |
| HP            | Notebook                    | Notebook    | [3fc38fa55e](https://linux-hardware.org/?probe=3fc38fa55e) | Jan 13, 2023 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [19be6bae3d](https://linux-hardware.org/?probe=19be6bae3d) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [9ebcc90bcf](https://linux-hardware.org/?probe=9ebcc90bcf) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [71f6d9b711](https://linux-hardware.org/?probe=71f6d9b711) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c551a35ec7](https://linux-hardware.org/?probe=c551a35ec7) | Jan 12, 2023 |
| Acer          | Aspire ES1-331              | Notebook    | [970c4e185f](https://linux-hardware.org/?probe=970c4e185f) | Jan 12, 2023 |
| Acer          | Aspire A315-41G             | Notebook    | [2bfe8a0134](https://linux-hardware.org/?probe=2bfe8a0134) | Jan 12, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [feee0755d0](https://linux-hardware.org/?probe=feee0755d0) | Jan 12, 2023 |
| ASUSTek       | TP401CA                     | Convertible | [781a6d0157](https://linux-hardware.org/?probe=781a6d0157) | Jan 11, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [5b24178097](https://linux-hardware.org/?probe=5b24178097) | Jan 11, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [ae85db39c6](https://linux-hardware.org/?probe=ae85db39c6) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [5c4331e8b9](https://linux-hardware.org/?probe=5c4331e8b9) | Jan 11, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [e9a8dfc18e](https://linux-hardware.org/?probe=e9a8dfc18e) | Jan 11, 2023 |
| Clevo         | E512xQ/E4129                | Notebook    | [6c78caccf5](https://linux-hardware.org/?probe=6c78caccf5) | Jan 11, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [9d614553aa](https://linux-hardware.org/?probe=9d614553aa) | Jan 11, 2023 |
| MSI           | GP60 2OD                    | Notebook    | [dbd191a73b](https://linux-hardware.org/?probe=dbd191a73b) | Jan 11, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [8d567b585a](https://linux-hardware.org/?probe=8d567b585a) | Jan 10, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [c4de77365a](https://linux-hardware.org/?probe=c4de77365a) | Jan 10, 2023 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [91caa09e7b](https://linux-hardware.org/?probe=91caa09e7b) | Jan 10, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [87c8f3902d](https://linux-hardware.org/?probe=87c8f3902d) | Jan 10, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [77ecead5ed](https://linux-hardware.org/?probe=77ecead5ed) | Jan 09, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [d9f3023575](https://linux-hardware.org/?probe=d9f3023575) | Jan 09, 2023 |
| Samsung       | RV420/RV520/RV720           | Notebook    | [c0697ead47](https://linux-hardware.org/?probe=c0697ead47) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | Desktop     | [ef4b23a73d](https://linux-hardware.org/?probe=ef4b23a73d) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2f03fd41c1](https://linux-hardware.org/?probe=2f03fd41c1) | Jan 09, 2023 |
| ASUSTek       | K54L                        | Notebook    | [88b71478e6](https://linux-hardware.org/?probe=88b71478e6) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | Desktop     | [2a22078fe1](https://linux-hardware.org/?probe=2a22078fe1) | Jan 09, 2023 |
| ASUSTek       | K61IC                       | Notebook    | [c593968311](https://linux-hardware.org/?probe=c593968311) | Jan 09, 2023 |
| MSI           | GV72 8RD                    | Notebook    | [5fa5d4ef58](https://linux-hardware.org/?probe=5fa5d4ef58) | Jan 09, 2023 |
| Acer          | TravelMate P278-M           | Notebook    | [6b2be0a8cc](https://linux-hardware.org/?probe=6b2be0a8cc) | Jan 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [71bd754745](https://linux-hardware.org/?probe=71bd754745) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [505cec778a](https://linux-hardware.org/?probe=505cec778a) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9924742c7d](https://linux-hardware.org/?probe=9924742c7d) | Jan 08, 2023 |
| ASUSTek       | M3400WUA                    | All in one  | [25ba18f752](https://linux-hardware.org/?probe=25ba18f752) | Jan 08, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [51f731b0f4](https://linux-hardware.org/?probe=51f731b0f4) | Jan 08, 2023 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [5b64e74a17](https://linux-hardware.org/?probe=5b64e74a17) | Jan 08, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [49f4c2fbc8](https://linux-hardware.org/?probe=49f4c2fbc8) | Jan 08, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [e5d4ce1aa7](https://linux-hardware.org/?probe=e5d4ce1aa7) | Jan 08, 2023 |
| Dell          | Latitude 5490               | Notebook    | [8fd07b1457](https://linux-hardware.org/?probe=8fd07b1457) | Jan 08, 2023 |
| ASUSTek       | 1003HAG                     | Notebook    | [0b411dbd38](https://linux-hardware.org/?probe=0b411dbd38) | Jan 08, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e082e7aece](https://linux-hardware.org/?probe=e082e7aece) | Jan 07, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [93957e7a70](https://linux-hardware.org/?probe=93957e7a70) | Jan 07, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [b4bf97514d](https://linux-hardware.org/?probe=b4bf97514d) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [9193043004](https://linux-hardware.org/?probe=9193043004) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [a6d1d6523b](https://linux-hardware.org/?probe=a6d1d6523b) | Jan 07, 2023 |
| Lenovo        | 0x36C4                      | All in one  | [cb6d0ac822](https://linux-hardware.org/?probe=cb6d0ac822) | Jan 07, 2023 |
| ASUSTek       | 1003HAG                     | Notebook    | [eb8e81a088](https://linux-hardware.org/?probe=eb8e81a088) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [57ec88a87b](https://linux-hardware.org/?probe=57ec88a87b) | Jan 07, 2023 |
| MB            | A320-SF110                  | Desktop     | [d23ec63d82](https://linux-hardware.org/?probe=d23ec63d82) | Jan 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6893b29920](https://linux-hardware.org/?probe=6893b29920) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7f2254139c](https://linux-hardware.org/?probe=7f2254139c) | Jan 07, 2023 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [a9288e85f6](https://linux-hardware.org/?probe=a9288e85f6) | Jan 06, 2023 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [633f31b57e](https://linux-hardware.org/?probe=633f31b57e) | Jan 06, 2023 |
| Gigabyte      | GA-A75M-DS2                 | Desktop     | [843dbca31d](https://linux-hardware.org/?probe=843dbca31d) | Jan 06, 2023 |
| MB            | A320-SF110                  | Desktop     | [5b690cf226](https://linux-hardware.org/?probe=5b690cf226) | Jan 06, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | Desktop     | [e59b16e379](https://linux-hardware.org/?probe=e59b16e379) | Jan 06, 2023 |
| ASRock        | A320D4-P1                   | Desktop     | [b6a61f9d2d](https://linux-hardware.org/?probe=b6a61f9d2d) | Jan 06, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [7b61bf12d0](https://linux-hardware.org/?probe=7b61bf12d0) | Jan 06, 2023 |
| ASRock        | D1800M                      | Desktop     | [f70a4786d7](https://linux-hardware.org/?probe=f70a4786d7) | Jan 06, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [e94f2584b0](https://linux-hardware.org/?probe=e94f2584b0) | Jan 06, 2023 |
| HP            | Compaq 515                  | Notebook    | [6cc60c3d13](https://linux-hardware.org/?probe=6cc60c3d13) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [1b36fc58ae](https://linux-hardware.org/?probe=1b36fc58ae) | Jan 05, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [bf8c10bdca](https://linux-hardware.org/?probe=bf8c10bdca) | Jan 05, 2023 |
| MSI           | H61M-P20                    | Desktop     | [f48c04fe8f](https://linux-hardware.org/?probe=f48c04fe8f) | Jan 05, 2023 |
| ASRock        | Z77M                        | Desktop     | [fe6f6a7b05](https://linux-hardware.org/?probe=fe6f6a7b05) | Jan 05, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [729add189b](https://linux-hardware.org/?probe=729add189b) | Jan 05, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c2df57a53f](https://linux-hardware.org/?probe=c2df57a53f) | Jan 05, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [5be962cfea](https://linux-hardware.org/?probe=5be962cfea) | Jan 05, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e1b3de18e9](https://linux-hardware.org/?probe=e1b3de18e9) | Jan 05, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [e3fd4121a2](https://linux-hardware.org/?probe=e3fd4121a2) | Jan 04, 2023 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [8601b7f2e9](https://linux-hardware.org/?probe=8601b7f2e9) | Jan 04, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [f4631a1285](https://linux-hardware.org/?probe=f4631a1285) | Jan 04, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [738739788a](https://linux-hardware.org/?probe=738739788a) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5194029152](https://linux-hardware.org/?probe=5194029152) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [f6de50a76b](https://linux-hardware.org/?probe=f6de50a76b) | Jan 04, 2023 |
| Maibenben     | PC34 V1.0                   | Desktop     | [0ed25644b7](https://linux-hardware.org/?probe=0ed25644b7) | Jan 04, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c07ba0a973](https://linux-hardware.org/?probe=c07ba0a973) | Jan 04, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [50315135d2](https://linux-hardware.org/?probe=50315135d2) | Jan 04, 2023 |
| ECS           | G41T-M2                     | Desktop     | [8df8f82fb8](https://linux-hardware.org/?probe=8df8f82fb8) | Jan 04, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [5e6f9a181c](https://linux-hardware.org/?probe=5e6f9a181c) | Jan 04, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [f57c26d714](https://linux-hardware.org/?probe=f57c26d714) | Jan 04, 2023 |
| Lenovo        | H420                        | Desktop     | [0765ceb3e8](https://linux-hardware.org/?probe=0765ceb3e8) | Jan 04, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [c3c074f183](https://linux-hardware.org/?probe=c3c074f183) | Jan 03, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [aa99474aec](https://linux-hardware.org/?probe=aa99474aec) | Jan 03, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [89868317cd](https://linux-hardware.org/?probe=89868317cd) | Jan 03, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [f75b0a7e71](https://linux-hardware.org/?probe=f75b0a7e71) | Jan 03, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [b86543e8cf](https://linux-hardware.org/?probe=b86543e8cf) | Jan 03, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [3ba1d0e689](https://linux-hardware.org/?probe=3ba1d0e689) | Jan 03, 2023 |
| Dell          | Precision M6400             | Notebook    | [8f1b979d06](https://linux-hardware.org/?probe=8f1b979d06) | Jan 03, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [b482fc96ea](https://linux-hardware.org/?probe=b482fc96ea) | Jan 03, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [63a14c970b](https://linux-hardware.org/?probe=63a14c970b) | Jan 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8eef31a350](https://linux-hardware.org/?probe=8eef31a350) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c8618e40a6](https://linux-hardware.org/?probe=c8618e40a6) | Jan 03, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [ee31a67035](https://linux-hardware.org/?probe=ee31a67035) | Jan 03, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [f55d8b7bc9](https://linux-hardware.org/?probe=f55d8b7bc9) | Jan 03, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [07e46fc5f7](https://linux-hardware.org/?probe=07e46fc5f7) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4842e4b3e5](https://linux-hardware.org/?probe=4842e4b3e5) | Jan 03, 2023 |
| Jumper        | EZpad                       | Tablet      | [cfa761d534](https://linux-hardware.org/?probe=cfa761d534) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a959b07b66](https://linux-hardware.org/?probe=a959b07b66) | Jan 02, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [3a801b9e90](https://linux-hardware.org/?probe=3a801b9e90) | Jan 01, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [c1818201ce](https://linux-hardware.org/?probe=c1818201ce) | Jan 01, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [33bf029e5f](https://linux-hardware.org/?probe=33bf029e5f) | Jan 01, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [75f2e6fae1](https://linux-hardware.org/?probe=75f2e6fae1) | Dec 31, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2161cbc9a0](https://linux-hardware.org/?probe=2161cbc9a0) | Dec 31, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [0d3ed20685](https://linux-hardware.org/?probe=0d3ed20685) | Dec 31, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [896aeb4e20](https://linux-hardware.org/?probe=896aeb4e20) | Dec 31, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [7b10613c1e](https://linux-hardware.org/?probe=7b10613c1e) | Dec 31, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [92920d8ac2](https://linux-hardware.org/?probe=92920d8ac2) | Dec 31, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [e8b804ddd5](https://linux-hardware.org/?probe=e8b804ddd5) | Dec 31, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [14b589709d](https://linux-hardware.org/?probe=14b589709d) | Dec 31, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [729e1569a8](https://linux-hardware.org/?probe=729e1569a8) | Dec 30, 2022 |
| MSI           | B360M GAMING PLUS           | Desktop     | [9d4f6afc25](https://linux-hardware.org/?probe=9d4f6afc25) | Dec 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [6f29ccd86e](https://linux-hardware.org/?probe=6f29ccd86e) | Dec 30, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b0a607e8d8](https://linux-hardware.org/?probe=b0a607e8d8) | Dec 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5710b93654](https://linux-hardware.org/?probe=5710b93654) | Dec 30, 2022 |
| AZW           | U59                         | Desktop     | [290e34b89a](https://linux-hardware.org/?probe=290e34b89a) | Dec 30, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [379552e4d2](https://linux-hardware.org/?probe=379552e4d2) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2d63537d23](https://linux-hardware.org/?probe=2d63537d23) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [41da11b027](https://linux-hardware.org/?probe=41da11b027) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [954fdfcd25](https://linux-hardware.org/?probe=954fdfcd25) | Dec 30, 2022 |
| Prestigio     | PSB141C04CGH                | Notebook    | [591f91b689](https://linux-hardware.org/?probe=591f91b689) | Dec 29, 2022 |
| Gigabyte      | B550 GAMING X               | Desktop     | [6e92b3e37b](https://linux-hardware.org/?probe=6e92b3e37b) | Dec 29, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [83acd419e0](https://linux-hardware.org/?probe=83acd419e0) | Dec 29, 2022 |
| ASUSTek       | H97-PRO                     | Desktop     | [b96b861fd7](https://linux-hardware.org/?probe=b96b861fd7) | Dec 29, 2022 |
| ASUSTek       | K40IN                       | Notebook    | [1b4a2d0604](https://linux-hardware.org/?probe=1b4a2d0604) | Dec 29, 2022 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [2cdb821b42](https://linux-hardware.org/?probe=2cdb821b42) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [556bc61c51](https://linux-hardware.org/?probe=556bc61c51) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [f0ab6f0649](https://linux-hardware.org/?probe=f0ab6f0649) | Dec 29, 2022 |
| Aquarius      | NS685U R11                  | Notebook    | [d99ae12a0c](https://linux-hardware.org/?probe=d99ae12a0c) | Dec 29, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [221e9b9fd6](https://linux-hardware.org/?probe=221e9b9fd6) | Dec 28, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [1afc5015f1](https://linux-hardware.org/?probe=1afc5015f1) | Dec 28, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [91c217e497](https://linux-hardware.org/?probe=91c217e497) | Dec 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e36e85614e](https://linux-hardware.org/?probe=e36e85614e) | Dec 28, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [7fb63e4360](https://linux-hardware.org/?probe=7fb63e4360) | Dec 27, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [415c0ff63e](https://linux-hardware.org/?probe=415c0ff63e) | Dec 27, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [3b9dbdb180](https://linux-hardware.org/?probe=3b9dbdb180) | Dec 27, 2022 |
| Toshiba       | Satellite U300              | Notebook    | [88861461c8](https://linux-hardware.org/?probe=88861461c8) | Dec 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1aac1f7eca](https://linux-hardware.org/?probe=1aac1f7eca) | Dec 27, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [1707593d6d](https://linux-hardware.org/?probe=1707593d6d) | Dec 27, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [802e160a5a](https://linux-hardware.org/?probe=802e160a5a) | Dec 27, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [2b7f53c989](https://linux-hardware.org/?probe=2b7f53c989) | Dec 27, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [3733446191](https://linux-hardware.org/?probe=3733446191) | Dec 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [155c738d10](https://linux-hardware.org/?probe=155c738d10) | Dec 27, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [542b5ae2f6](https://linux-hardware.org/?probe=542b5ae2f6) | Dec 27, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [8b34b357bb](https://linux-hardware.org/?probe=8b34b357bb) | Dec 27, 2022 |
| Gigabyte      | i1520N                      | Notebook    | [4f94938d1b](https://linux-hardware.org/?probe=4f94938d1b) | Dec 27, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [17bd139f0c](https://linux-hardware.org/?probe=17bd139f0c) | Dec 26, 2022 |
| Acer          | Aspire Z1-612               | All in one  | [19582f3331](https://linux-hardware.org/?probe=19582f3331) | Dec 26, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [1ba62f0fab](https://linux-hardware.org/?probe=1ba62f0fab) | Dec 26, 2022 |
| Dell          | G5 5590                     | Notebook    | [43fbc3b36d](https://linux-hardware.org/?probe=43fbc3b36d) | Dec 26, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [f9d83535bd](https://linux-hardware.org/?probe=f9d83535bd) | Dec 26, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [735d3cfda2](https://linux-hardware.org/?probe=735d3cfda2) | Dec 26, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [5d26c7c543](https://linux-hardware.org/?probe=5d26c7c543) | Dec 26, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [2d98a8cef2](https://linux-hardware.org/?probe=2d98a8cef2) | Dec 25, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [5174af9fdd](https://linux-hardware.org/?probe=5174af9fdd) | Dec 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c702bed39d](https://linux-hardware.org/?probe=c702bed39d) | Dec 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [8f4d031a78](https://linux-hardware.org/?probe=8f4d031a78) | Dec 25, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [85b55a267a](https://linux-hardware.org/?probe=85b55a267a) | Dec 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [8994b9a877](https://linux-hardware.org/?probe=8994b9a877) | Dec 25, 2022 |
| Pegatron      | C15B                        | Notebook    | [f838b3f22c](https://linux-hardware.org/?probe=f838b3f22c) | Dec 25, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [1571f74238](https://linux-hardware.org/?probe=1571f74238) | Dec 25, 2022 |
| HP            | 0AACh                       | Desktop     | [b83da338ee](https://linux-hardware.org/?probe=b83da338ee) | Dec 25, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [3442037418](https://linux-hardware.org/?probe=3442037418) | Dec 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f48ac4aa81](https://linux-hardware.org/?probe=f48ac4aa81) | Dec 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b98be1b1e7](https://linux-hardware.org/?probe=b98be1b1e7) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [5368526dc0](https://linux-hardware.org/?probe=5368526dc0) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [fab270a7bf](https://linux-hardware.org/?probe=fab270a7bf) | Dec 25, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [84ea64b29c](https://linux-hardware.org/?probe=84ea64b29c) | Dec 24, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [407f76f02f](https://linux-hardware.org/?probe=407f76f02f) | Dec 24, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [bb8b44cf69](https://linux-hardware.org/?probe=bb8b44cf69) | Dec 24, 2022 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [70312467b7](https://linux-hardware.org/?probe=70312467b7) | Dec 24, 2022 |
| Gigabyte      | B660M D2H DDR4              | Desktop     | [c34803fb1e](https://linux-hardware.org/?probe=c34803fb1e) | Dec 24, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [6f60f1b6da](https://linux-hardware.org/?probe=6f60f1b6da) | Dec 24, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [c107bb3a14](https://linux-hardware.org/?probe=c107bb3a14) | Dec 24, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [cf3882b3f7](https://linux-hardware.org/?probe=cf3882b3f7) | Dec 24, 2022 |
| Gigabyte      | H55M-S2H                    | Desktop     | [7cecfa756a](https://linux-hardware.org/?probe=7cecfa756a) | Dec 24, 2022 |
| HP            | 0AACh                       | Desktop     | [4a7840e1cf](https://linux-hardware.org/?probe=4a7840e1cf) | Dec 24, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [40c2593694](https://linux-hardware.org/?probe=40c2593694) | Dec 24, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [81febc2905](https://linux-hardware.org/?probe=81febc2905) | Dec 23, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [0d45265efc](https://linux-hardware.org/?probe=0d45265efc) | Dec 23, 2022 |
| Unknown       | 865GV-ICH5                  | Desktop     | [fe2ef2ef31](https://linux-hardware.org/?probe=fe2ef2ef31) | Dec 23, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [73dc1109eb](https://linux-hardware.org/?probe=73dc1109eb) | Dec 23, 2022 |
| Intel         | ChiefRiver                  | Notebook    | [a23ea2e43e](https://linux-hardware.org/?probe=a23ea2e43e) | Dec 23, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [b53beddded](https://linux-hardware.org/?probe=b53beddded) | Dec 23, 2022 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [daf1310bfa](https://linux-hardware.org/?probe=daf1310bfa) | Dec 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [672c320794](https://linux-hardware.org/?probe=672c320794) | Dec 22, 2022 |
| HP            | G62                         | Notebook    | [00b47da7dc](https://linux-hardware.org/?probe=00b47da7dc) | Dec 22, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [1a8f388366](https://linux-hardware.org/?probe=1a8f388366) | Dec 22, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [8981102ebe](https://linux-hardware.org/?probe=8981102ebe) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ae98ccd9c2](https://linux-hardware.org/?probe=ae98ccd9c2) | Dec 22, 2022 |
| Unknown       | 865GV-ICH5                  | Desktop     | [f42b7383f4](https://linux-hardware.org/?probe=f42b7383f4) | Dec 22, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [2683bf55bf](https://linux-hardware.org/?probe=2683bf55bf) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c485d688ad](https://linux-hardware.org/?probe=c485d688ad) | Dec 22, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [4fc8630d91](https://linux-hardware.org/?probe=4fc8630d91) | Dec 22, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [ad317dc4fd](https://linux-hardware.org/?probe=ad317dc4fd) | Dec 22, 2022 |
| ASUSTek       | P5K PRO                     | Desktop     | [4088ff40e3](https://linux-hardware.org/?probe=4088ff40e3) | Dec 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [10a98289bb](https://linux-hardware.org/?probe=10a98289bb) | Dec 21, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [b7311f5a21](https://linux-hardware.org/?probe=b7311f5a21) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [c39538e70e](https://linux-hardware.org/?probe=c39538e70e) | Dec 21, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [afac6a5bfa](https://linux-hardware.org/?probe=afac6a5bfa) | Dec 21, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d6e55e247a](https://linux-hardware.org/?probe=d6e55e247a) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [cc485cc076](https://linux-hardware.org/?probe=cc485cc076) | Dec 21, 2022 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [e7383e309b](https://linux-hardware.org/?probe=e7383e309b) | Dec 21, 2022 |
| eMachines     | E525                        | Notebook    | [8368666118](https://linux-hardware.org/?probe=8368666118) | Dec 21, 2022 |
| ASUSTek       | X555SJ                      | Notebook    | [c580c82fe2](https://linux-hardware.org/?probe=c580c82fe2) | Dec 21, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [ba8b12c87e](https://linux-hardware.org/?probe=ba8b12c87e) | Dec 21, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c56023ff15](https://linux-hardware.org/?probe=c56023ff15) | Dec 21, 2022 |
| Pegatron      | A17                         | Notebook    | [f40a055eac](https://linux-hardware.org/?probe=f40a055eac) | Dec 21, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Gigabyte      | EP43-S3L                    | Desktop     | [8a24afa21d](https://linux-hardware.org/?probe=8a24afa21d) | Dec 20, 2022 |
| Intel         | X99                         | Desktop     | [ce9b83b781](https://linux-hardware.org/?probe=ce9b83b781) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [e7cfce65f6](https://linux-hardware.org/?probe=e7cfce65f6) | Dec 20, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [44d3238797](https://linux-hardware.org/?probe=44d3238797) | Dec 20, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [a39b8f54af](https://linux-hardware.org/?probe=a39b8f54af) | Dec 20, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [8777d682b0](https://linux-hardware.org/?probe=8777d682b0) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [7c854ad5e0](https://linux-hardware.org/?probe=7c854ad5e0) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [f82010222c](https://linux-hardware.org/?probe=f82010222c) | Dec 20, 2022 |
| ASRock        | Z77M                        | Desktop     | [33c2afa3e0](https://linux-hardware.org/?probe=33c2afa3e0) | Dec 20, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [de20614d06](https://linux-hardware.org/?probe=de20614d06) | Dec 19, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [66e45d9a82](https://linux-hardware.org/?probe=66e45d9a82) | Dec 19, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [90ea21bd4a](https://linux-hardware.org/?probe=90ea21bd4a) | Dec 19, 2022 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [c8f2df83aa](https://linux-hardware.org/?probe=c8f2df83aa) | Dec 19, 2022 |
| ASRock        | P67 Pro3 SE                 | Desktop     | [5a59282fea](https://linux-hardware.org/?probe=5a59282fea) | Dec 19, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [aa5228e9b8](https://linux-hardware.org/?probe=aa5228e9b8) | Dec 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ROSA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ROSA R10           | 4389      | 14.14%  |
| ROSA R11           | 4116      | 13.26%  |
| ROSA R8            | 3637      | 11.72%  |
| ROSA R6            | 3496      | 11.26%  |
| ROSA R7            | 3301      | 10.64%  |
| ROSA R8.1          | 2852      | 9.19%   |
| ROSA R9            | 2548      | 8.21%   |
| ROSA R11.1         | 2273      | 7.32%   |
| ROSA 12.2          | 1989      | 6.41%   |
| ROSA 12.3          | 924       | 2.98%   |
| ROSA R5            | 571       | 1.84%   |
| ROSA 12.1          | 339       | 1.09%   |
| ROSA 12            | 190       | 0.61%   |
| ROSA R4            | 121       | 0.39%   |
| ROSA R3            | 86        | 0.28%   |
| ROSA R12           | 71        | 0.23%   |
| ROSA 12.4          | 42        | 0.14%   |
| ROSA 2019.05       | 20        | 0.06%   |
| ROSA R9-R11        | 16        | 0.05%   |
| ROSA R2            | 16        | 0.05%   |
| ROSA 2012.0        | 12        | 0.04%   |
| ROSA Chrome 2.0    | 7         | 0.02%   |
| ROSA R4-R8         | 4         | 0.01%   |
| ROSA DX 1.0        | 4         | 0.01%   |
| ROSA Nickel 2019.0 | 3         | 0.01%   |
| ROSA 2021.1        | 3         | 0.01%   |
| ROSA DX 2.0        | 2         | 0.01%   |
| ROSA 2019.0        | 2         | 0.01%   |
| ROSA SX 1.0        | 1         | 0.003%  |
| ROSA R1            | 1         | 0.003%  |
| ROSA 13.0          | 1         | 0.003%  |
| ROSA 1.0           | 1         | 0.003%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| ROSA | 25702     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 2053      | 6.13%   |
| 3.14.44-nrj-desktop-2rosa-x86_64    | 1866      | 5.57%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 1827      | 5.45%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 1801      | 5.37%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 1744      | 5.2%    |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 1600      | 4.77%   |
| 4.1.15-nrj-desktop-1rosa-x86_64     | 1381      | 4.12%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 971       | 2.9%    |
| 3.14.44-nrj-desktop-2rosa-i586      | 833       | 2.49%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 782       | 2.33%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 697       | 2.08%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 647       | 1.93%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 580       | 1.73%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 549       | 1.64%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 519       | 1.55%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 502       | 1.5%    |
| 4.9.20-nrj-desktop-1rosa-i586       | 491       | 1.46%   |
| 4.1.16-nrj-desktop-1rosa-x86_64     | 463       | 1.38%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 457       | 1.36%   |
| 4.15.0-desktop-45.1rosa-i586        | 454       | 1.35%   |
| 4.1.15-nrj-desktop-1rosa-i586       | 452       | 1.35%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 446       | 1.33%   |
| 5.4.32-generic-2rosa-x86_64         | 438       | 1.31%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 426       | 1.27%   |
| 5.4.83-generic-2rosa-x86_64         | 390       | 1.16%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 379       | 1.13%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 362       | 1.08%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 340       | 1.01%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 334       | 1%      |
| 5.15.75-generic-1rosa2021.1-x86_64  | 328       | 0.98%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 311       | 0.93%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 278       | 0.83%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 272       | 0.81%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 270       | 0.81%   |
| 3.14.53-nrj-desktop-1rosa-x86_64    | 270       | 0.81%   |
| 4.1.22-nrj-desktop-2rosa-x86_64     | 258       | 0.77%   |
| 4.1.33-nrj-desktop-1rosa-x86_64     | 250       | 0.75%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 228       | 0.68%   |
| 3.14.25-nrj-desktop-1rosa           | 219       | 0.65%   |
| 4.1.13-nrj-desktop-1rosa-x86_64     | 200       | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 4401      | 13.39%  |
| 3.14.44  | 2695      | 8.2%    |
| 4.9.60   | 2594      | 7.89%   |
| 4.9.20   | 2317      | 7.05%   |
| 4.1.25   | 2172      | 6.61%   |
| 4.1.15   | 1832      | 5.57%   |
| 5.10.74  | 1797      | 5.47%   |
| 4.1.34   | 1349      | 4.1%    |
| 4.1.38   | 1110      | 3.38%   |
| 4.9.9    | 1002      | 3.05%   |
| 4.9.124  | 973       | 2.96%   |
| 4.9.155  | 687       | 2.09%   |
| 4.9.76   | 638       | 1.94%   |
| 4.1.16   | 631       | 1.92%   |
| 5.4.32   | 598       | 1.82%   |
| 4.9.41   | 589       | 1.79%   |
| 5.4.83   | 496       | 1.51%   |
| 4.1.19   | 390       | 1.19%   |
| 3.14.53  | 387       | 1.18%   |
| 5.15.75  | 373       | 1.13%   |
| 5.10.118 | 370       | 1.13%   |
| 4.1.22   | 366       | 1.11%   |
| 4.9.95   | 339       | 1.03%   |
| 4.1.33   | 339       | 1.03%   |
| 4.1.13   | 305       | 0.93%   |
| 5.15.79  | 272       | 0.83%   |
| 4.9.111  | 244       | 0.74%   |
| 3.14.25  | 222       | 0.68%   |
| 3.14.33  | 196       | 0.6%    |
| 5.10.71  | 185       | 0.56%   |
| 4.9.87   | 174       | 0.53%   |
| 3.14.39  | 134       | 0.41%   |
| 4.9.14   | 109       | 0.33%   |
| 5.4.40   | 104       | 0.32%   |
| 5.17.11  | 93        | 0.28%   |
| 4.9.34   | 80        | 0.24%   |
| 4.13.0   | 79        | 0.24%   |
| 5.15.77  | 77        | 0.23%   |
| 5.10.155 | 74        | 0.23%   |
| 3.14.15  | 66        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 8438      | 28.37%  |
| 4.1     | 7556      | 25.41%  |
| 4.15    | 4415      | 14.84%  |
| 3.14    | 3541      | 11.91%  |
| 5.10    | 2345      | 7.88%   |
| 5.4     | 1251      | 4.21%   |
| 5.15    | 802       | 2.7%    |
| 4.4     | 150       | 0.5%    |
| 4.13    | 108       | 0.36%   |
| 3.10    | 101       | 0.34%   |
| 5.17    | 94        | 0.32%   |
| 4.8     | 77        | 0.26%   |
| 5.18    | 76        | 0.26%   |
| 6.1     | 61        | 0.21%   |
| 5.0     | 57        | 0.19%   |
| 6.0     | 53        | 0.18%   |
| 4.0     | 48        | 0.16%   |
| 4.7     | 47        | 0.16%   |
| 4.6     | 46        | 0.15%   |
| 4.16    | 44        | 0.15%   |
| 4.19    | 41        | 0.14%   |
| 4.18    | 40        | 0.13%   |
| 3.18    | 38        | 0.13%   |
| 4.14    | 32        | 0.11%   |
| 4.3     | 27        | 0.09%   |
| 5.16    | 26        | 0.09%   |
| 4.2     | 26        | 0.09%   |
| 4.5     | 24        | 0.08%   |
| 4.17    | 21        | 0.07%   |
| 4.11    | 17        | 0.06%   |
| 5.5     | 16        | 0.05%   |
| 4.12    | 15        | 0.05%   |
| 3.0     | 14        | 0.05%   |
| 5.3     | 12        | 0.04%   |
| 5.2     | 12        | 0.04%   |
| 4.10    | 9         | 0.03%   |
| 3.17    | 9         | 0.03%   |
| 5.9     | 7         | 0.02%   |
| 5.8     | 7         | 0.02%   |
| 5.6     | 6         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 20198     | 76.76%  |
| i686    | 6110      | 23.22%  |
| aarch64 | 3         | 0.01%   |
| e2k     | 1         | 0.004%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE4       | 18088     | 65.29%  |
| KDE5       | 6385      | 23.05%  |
| GNOME      | 1461      | 5.27%   |
| LXQt       | 916       | 3.31%   |
| MATE       | 362       | 1.31%   |
| XFCE       | 224       | 0.81%   |
| LXDE       | 164       | 0.59%   |
| Unknown    | 93        | 0.34%   |
| KDE        | 4         | 0.01%   |
| Budgie     | 2         | 0.01%   |
| X-Cinnamon | 1         | 0.004%  |
| i3         | 1         | 0.004%  |
| Cinnamon   | 1         | 0.004%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 23484     | 89.57%  |
| Wayland | 2718      | 10.37%  |
| Tty     | 15        | 0.06%   |
| Unknown | 3         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 18256     | 66.32%  |
| SDDM    | 6920      | 25.14%  |
| GDM     | 2047      | 7.44%   |
| LightDM | 143       | 0.52%   |
| TDM     | 115       | 0.42%   |
| Unknown | 26        | 0.09%   |
| XDM     | 19        | 0.07%   |
| LXDM    | 1         | 0.004%  |
| LDM     | 1         | 0.004%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 21103     | 79.25%  |
| ru_RU       | 4892      | 18.37%  |
| en_US       | 164       | 0.62%   |
| de_DE       | 75        | 0.28%   |
| pl_PL       | 74        | 0.28%   |
| es_ES       | 46        | 0.17%   |
| pt_BR       | 41        | 0.15%   |
| fr_FR       | 39        | 0.15%   |
| en_GB       | 34        | 0.13%   |
| it_IT       | 33        | 0.12%   |
| ru_UA       | 23        | 0.09%   |
| ro_RO       | 9         | 0.03%   |
| pt_PT       | 9         | 0.03%   |
| es_PE       | 6         | 0.02%   |
| C           | 6         | 0.02%   |
| es_MX       | 5         | 0.02%   |
| es_CO       | 5         | 0.02%   |
| tr_TR       | 4         | 0.02%   |
| hu_HU       | 4         | 0.02%   |
| fr_BE       | 4         | 0.02%   |
| es_AR       | 4         | 0.02%   |
| cs_CZ       | 4         | 0.02%   |
| sk_SK       | 3         | 0.01%   |
| en_IN       | 3         | 0.01%   |
| bg_BG       | 3         | 0.01%   |
| ru_BY       | 2         | 0.01%   |
| nl_NL       | 2         | 0.01%   |
| lv_LV       | 2         | 0.01%   |
| lt_LT       | 2         | 0.01%   |
| es_VE       | 2         | 0.01%   |
| el_GR       | 2         | 0.01%   |
| da_DK       | 2         | 0.01%   |
| be_BY       | 2         | 0.01%   |
| tt_RU       | 1         | 0.004%  |
| sv_SE       | 1         | 0.004%  |
| sr_RS@latin | 1         | 0.004%  |
| sr_RS       | 1         | 0.004%  |
| sr_ME       | 1         | 0.004%  |
| ru_KZ       | 1         | 0.004%  |
| ja_JP       | 1         | 0.004%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 20486     | 77.94%  |
| EFI  | 5798      | 22.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Unknown  | 16470     | 60.33%  |
| Ext4     | 10289     | 37.69%  |
| Btrfs    | 383       | 1.4%    |
| Ext3     | 68        | 0.25%   |
| Ext2     | 24        | 0.09%   |
| Xfs      | 21        | 0.08%   |
| Aufs     | 14        | 0.05%   |
| F2fs     | 12        | 0.04%   |
| SAMSUNG  | 6         | 0.02%   |
| Reiserfs | 4         | 0.01%   |
| Overlay  | 3         | 0.01%   |
| Jfs      | 1         | 0.004%  |
| Exfat    | 1         | 0.004%  |
| 2G       | 1         | 0.004%  |
| 20G      | 1         | 0.004%  |
| 12G      | 1         | 0.004%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 16303     | 58.92%  |
| GPT     | 6148      | 22.22%  |
| Unknown | 5218      | 18.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 23681     | 89.34%  |
| Yes       | 2826      | 10.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 21520     | 80.06%  |
| Yes       | 5359      | 19.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 6900      | 26.85%  |
| Gigabyte Technology | 3027      | 11.78%  |
| Lenovo              | 2217      | 8.63%   |
| Hewlett-Packard     | 2104      | 8.19%   |
| Acer                | 2070      | 8.05%   |
| MSI                 | 1593      | 6.2%    |
| ASRock              | 1442      | 5.61%   |
| Dell                | 1089      | 4.24%   |
| Samsung Electronics | 920       | 3.58%   |
| Toshiba             | 479       | 1.86%   |
| Intel               | 425       | 1.65%   |
| Sony                | 328       | 1.28%   |
| ECS                 | 290       | 1.13%   |
| Packard Bell        | 262       | 1.02%   |
| Unknown             | 235       | 0.91%   |
| Biostar             | 206       | 0.8%    |
| Pegatron            | 186       | 0.72%   |
| eMachines           | 181       | 0.7%    |
| Foxconn             | 171       | 0.67%   |
| Apple               | 113       | 0.44%   |
| Fujitsu Siemens     | 111       | 0.43%   |
| Notebook            | 102       | 0.4%    |
| Clevo               | 98        | 0.38%   |
| Fujitsu             | 92        | 0.36%   |
| DNS                 | 50        | 0.19%   |
| Quanta              | 42        | 0.16%   |
| Medion              | 38        | 0.15%   |
| Huanan              | 36        | 0.14%   |
| EPoX Computer       | 35        | 0.14%   |
| WinFast             | 33        | 0.13%   |
| DEXP                | 30        | 0.12%   |
| AMI                 | 30        | 0.12%   |
| Supermicro          | 25        | 0.1%    |
| Prestigio           | 24        | 0.09%   |
| Irbis               | 24        | 0.09%   |
| Aquarius            | 24        | 0.09%   |
| IBM                 | 23        | 0.09%   |
| Digma               | 23        | 0.09%   |
| Nvidia              | 18        | 0.07%   |
| ABIT                | 18        | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUS All Series              | 360       | 1.4%    |
| Unknown                      | 341       | 1.33%   |
| HP Pavilion g6               | 178       | 0.69%   |
| HP Pavilion dv6              | 108       | 0.42%   |
| ASUS M5A78L-M LX3            | 78        | 0.3%    |
| HP Notebook                  | 77        | 0.3%    |
| MSI MS-7817                  | 75        | 0.29%   |
| ASUS M5A97 R2.0              | 68        | 0.26%   |
| ASRock G31M-S                | 66        | 0.26%   |
| Acer Aspire V3-571G          | 66        | 0.26%   |
| Lenovo G570 20079            | 65        | 0.25%   |
| Gigabyte 970A-DS3P           | 62        | 0.24%   |
| ASRock N68C-S UCC            | 60        | 0.23%   |
| MSI MS-7529                  | 57        | 0.22%   |
| Lenovo B590 20206            | 56        | 0.22%   |
| Gigabyte H61M-S1             | 55        | 0.21%   |
| Gigabyte G31M-ES2L           | 55        | 0.21%   |
| MSI MS-7592                  | 53        | 0.21%   |
| HP Pavilion dv7              | 53        | 0.21%   |
| ASUS P5K                     | 53        | 0.21%   |
| Packard Bell EasyNote TE11HC | 52        | 0.2%    |
| Lenovo G50-30 80G0           | 51        | 0.2%    |
| HP Pavilion g7               | 51        | 0.2%    |
| Lenovo G500 20236            | 49        | 0.19%   |
| ASUS P5B                     | 48        | 0.19%   |
| HP Pavilion 15               | 47        | 0.18%   |
| Dell Inspiron N5110          | 47        | 0.18%   |
| ASUS P8H61-M LX3 R2.0        | 47        | 0.18%   |
| ASUS P5KPL-AM                | 47        | 0.18%   |
| MSI MS-7309                  | 46        | 0.18%   |
| ASUS P8Z77-V LX              | 46        | 0.18%   |
| MSI MS-7788                  | 45        | 0.18%   |
| ASUS P5G41T-M LX2/GB         | 45        | 0.18%   |
| ASUS M5A97 LE R2.0           | 45        | 0.18%   |
| Lenovo G50-45 80E3           | 43        | 0.17%   |
| ASUS P5KPL-AM IN/ROEM/SI     | 43        | 0.17%   |
| Acer Aspire 5750G            | 43        | 0.17%   |
| Acer Aspire 5742G            | 42        | 0.16%   |
| Toshiba Satellite C660       | 41        | 0.16%   |
| ASRock G41M-VS3              | 41        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1489      | 5.79%   |
| HP Pavilion           | 640       | 2.49%   |
| Dell Inspiron         | 496       | 1.93%   |
| Lenovo IdeaPad        | 492       | 1.91%   |
| Toshiba Satellite     | 434       | 1.69%   |
| Lenovo ThinkPad       | 361       | 1.4%    |
| ASUS All              | 360       | 1.4%    |
| HP Compaq             | 350       | 1.36%   |
| Unknown               | 341       | 1.33%   |
| Packard Bell EasyNote | 207       | 0.81%   |
| ASUS M5A78L-M         | 205       | 0.8%    |
| Dell Latitude         | 202       | 0.79%   |
| ASUS PRIME            | 192       | 0.75%   |
| HP ProBook            | 190       | 0.74%   |
| ASUS P8H61-M          | 186       | 0.72%   |
| Acer Extensa          | 170       | 0.66%   |
| ASUS P5KPL-AM         | 159       | 0.62%   |
| ASUS M5A97            | 155       | 0.6%    |
| Dell OptiPlex         | 145       | 0.56%   |
| ASUS P5K              | 139       | 0.54%   |
| ASUS P8Z77-V          | 132       | 0.51%   |
| ASUS P5G41T-M         | 118       | 0.46%   |
| HP Laptop             | 115       | 0.45%   |
| Dell Vostro           | 107       | 0.42%   |
| ASUS P5Q              | 107       | 0.42%   |
| Lenovo G580           | 100       | 0.39%   |
| HP EliteBook          | 96        | 0.37%   |
| Lenovo B590           | 94        | 0.37%   |
| Acer TravelMate       | 87        | 0.34%   |
| Lenovo ThinkCentre    | 78        | 0.3%    |
| HP Notebook           | 77        | 0.3%    |
| MSI MS-7817           | 75        | 0.29%   |
| ASUS SABERTOOTH       | 69        | 0.27%   |
| ASUS VivoBook         | 68        | 0.26%   |
| Lenovo G570           | 66        | 0.26%   |
| ASRock G31M-S         | 66        | 0.26%   |
| Gigabyte 970A-DS3P    | 63        | 0.25%   |
| ASRock N68C-S         | 62        | 0.24%   |
| HP ENVY               | 58        | 0.23%   |
| MSI MS-7529           | 57        | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 3681      | 14.32%  |
| 2011    | 3408      | 13.26%  |
| 2010    | 2748      | 10.69%  |
| 2009    | 2402      | 9.35%   |
| 2013    | 2209      | 8.59%   |
| 2008    | 2110      | 8.21%   |
| 2007    | 1906      | 7.42%   |
| 2014    | 1356      | 5.28%   |
| 2006    | 1137      | 4.42%   |
| 2015    | 979       | 3.81%   |
| 2016    | 807       | 3.14%   |
| 2018    | 661       | 2.57%   |
| 2017    | 599       | 2.33%   |
| 2005    | 422       | 1.64%   |
| 2019    | 367       | 1.43%   |
| 2020    | 278       | 1.08%   |
| 2021    | 273       | 1.06%   |
| 2004    | 149       | 0.58%   |
| 2003    | 80        | 0.31%   |
| 2022    | 63        | 0.25%   |
| Unknown | 46        | 0.18%   |
| 2002    | 15        | 0.06%   |
| 2001    | 5         | 0.02%   |
| 2000    | 1         | 0.004%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 13014     | 50.63%  |
| Notebook       | 12197     | 47.46%  |
| All in one     | 245       | 0.95%   |
| Mini pc        | 121       | 0.47%   |
| Tablet         | 55        | 0.21%   |
| Server         | 38        | 0.15%   |
| Convertible    | 27        | 0.11%   |
| System on chip | 3         | 0.01%   |
| Stick pc       | 2         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 25700     | 99.98%  |
| Enabled  | 5         | 0.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25694     | 99.97%  |
| Yes  | 8         | 0.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 8973      | 33.14%  |
| 8.01-16.0       | 4395      | 16.23%  |
| 4.01-8.0        | 4273      | 15.78%  |
| 1.01-2.0        | 3610      | 13.33%  |
| 2.01-3.0        | 2625      | 9.69%   |
| 16.01-24.0      | 1585      | 5.85%   |
| 0.51-1.0        | 750       | 2.77%   |
| Unknown         | 380       | 1.4%    |
| 32.01-64.0      | 316       | 1.17%   |
| 24.01-32.0      | 92        | 0.34%   |
| 64.01-256.0     | 39        | 0.14%   |
| 0.01-0.5        | 38        | 0.14%   |
| More than 256.0 | 3         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 13659     | 45.95%  |
| 1.01-2.0   | 11588     | 38.98%  |
| 2.01-3.0   | 2029      | 6.83%   |
| 0.01-0.5   | 1151      | 3.87%   |
| 3.01-4.0   | 483       | 1.62%   |
| Unknown    | 447       | 1.5%    |
| 4.01-8.0   | 326       | 1.1%    |
| 8.01-16.0  | 35        | 0.12%   |
| 16.01-24.0 | 7         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 17748     | 65.3%   |
| 2       | 6247      | 22.99%  |
| 3       | 1991      | 7.33%   |
| 4       | 629       | 2.31%   |
| 5       | 228       | 0.84%   |
| 0       | 203       | 0.75%   |
| 6       | 84        | 0.31%   |
| 7       | 19        | 0.07%   |
| 8       | 12        | 0.04%   |
| Unknown | 10        | 0.04%   |
| 9       | 5         | 0.02%   |
| 10      | 2         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17104     | 64.92%  |
| No        | 9242      | 35.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24898     | 96.82%  |
| No        | 818       | 3.18%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15556     | 59.79%  |
| No        | 10460     | 40.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 17140     | 65.54%  |
| Yes       | 9013      | 34.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 14571     | 53.77%  |
| Unknown     | 8003      | 29.53%  |
| Ukraine     | 1087      | 4.01%   |
| Belarus     | 421       | 1.55%   |
| Germany     | 349       | 1.29%   |
| Poland      | 330       | 1.22%   |
| Kazakhstan  | 239       | 0.88%   |
| USA         | 189       | 0.7%    |
| Italy       | 182       | 0.67%   |
| France      | 174       | 0.64%   |
| Brazil      | 126       | 0.46%   |
| Spain       | 108       | 0.4%    |
| UK          | 77        | 0.28%   |
| Canada      | 76        | 0.28%   |
| Moldova     | 68        | 0.25%   |
| Romania     | 65        | 0.24%   |
| Latvia      | 53        | 0.2%    |
| Bulgaria    | 48        | 0.18%   |
| Mexico      | 44        | 0.16%   |
| Serbia      | 41        | 0.15%   |
| Czechia     | 38        | 0.14%   |
| Austria     | 36        | 0.13%   |
| Israel      | 34        | 0.13%   |
| Turkey      | 32        | 0.12%   |
| Estonia     | 32        | 0.12%   |
| Slovakia    | 30        | 0.11%   |
| Belgium     | 29        | 0.11%   |
| Australia   | 29        | 0.11%   |
| Lithuania   | 28        | 0.1%    |
| Netherlands | 26        | 0.1%    |
| Finland     | 26        | 0.1%    |
| Uzbekistan  | 25        | 0.09%   |
| Switzerland | 25        | 0.09%   |
| Greece      | 23        | 0.08%   |
| Colombia    | 23        | 0.08%   |
| India       | 22        | 0.08%   |
| Argentina   | 22        | 0.08%   |
| Hungary     | 21        | 0.08%   |
| Sweden      | 20        | 0.07%   |
| Portugal    | 19        | 0.07%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 8005      | 27.71%  |
| Moscow           | 2341      | 8.1%    |
| St Petersburg    | 997       | 3.45%   |
| Pecherskoye      | 759       | 2.63%   |
| Novosibirsk      | 511       | 1.77%   |
| Krasnodar        | 450       | 1.56%   |
| Yekaterinburg    | 409       | 1.42%   |
| Samara           | 345       | 1.19%   |
| Nizhniy Novgorod | 341       | 1.18%   |
| Rostov-on-Don    | 291       | 1.01%   |
| Chelyabinsk      | 276       | 0.96%   |
| Perm             | 266       | 0.92%   |
| Voronezh         | 251       | 0.87%   |
| Krasnoyarsk      | 219       | 0.76%   |
| Saratov          | 213       | 0.74%   |
| Omsk             | 175       | 0.61%   |
| Volgograd        | 165       | 0.57%   |
| Kazan’         | 161       | 0.56%   |
| Minsk            | 153       | 0.53%   |
| Khabarovsk       | 153       | 0.53%   |
| Barnaul          | 142       | 0.49%   |
| Tyumen           | 141       | 0.49%   |
| Stavropol        | 138       | 0.48%   |
| Ufa              | 135       | 0.47%   |
| Vladivostok      | 122       | 0.42%   |
| Irkutsk          | 120       | 0.42%   |
| Kyiv             | 116       | 0.4%    |
| Kemerovo         | 116       | 0.4%    |
| Yaroslavl        | 112       | 0.39%   |
| Tula             | 104       | 0.36%   |
| Kaliningrad      | 104       | 0.36%   |
| Novokuznetsk     | 101       | 0.35%   |
| Simferopol       | 99        | 0.34%   |
| Orenburg         | 99        | 0.34%   |
| Bryansk          | 99        | 0.34%   |
| Belgorod         | 94        | 0.33%   |
| Kirov            | 92        | 0.32%   |
| Surgut           | 91        | 0.32%   |
| Astrakhan        | 88        | 0.3%    |
| Lipetsk          | 87        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Seagate             | 8965      | 14018   | 24.94%  |
| WDC                 | 8488      | 13485   | 23.62%  |
| Hitachi             | 2965      | 4124    | 8.25%   |
| Toshiba             | 2839      | 3987    | 7.9%    |
| Samsung Electronics | 2814      | 4181    | 7.83%   |
| Kingston            | 1418      | 1948    | 3.95%   |
| HGST                | 889       | 1331    | 2.47%   |
| Unknown             | 817       | 1080    | 2.27%   |
| SanDisk             | 550       | 773     | 1.53%   |
| Maxtor              | 474       | 608     | 1.32%   |
| A-DATA Technology   | 398       | 567     | 1.11%   |
| China               | 379       | 507     | 1.05%   |
| OCZ                 | 374       | 504     | 1.04%   |
| SPCC                | 373       | 533     | 1.04%   |
| Intel               | 321       | 495     | 0.89%   |
| Fujitsu             | 307       | 372     | 0.85%   |
| Crucial             | 303       | 419     | 0.84%   |
| HUAWEI              | 285       | 334     | 0.79%   |
| Plextor             | 262       | 393     | 0.73%   |
| Smartbuy            | 170       | 220     | 0.47%   |
| Apacer              | 157       | 220     | 0.44%   |
| Transcend           | 154       | 218     | 0.43%   |
| Corsair             | 134       | 178     | 0.37%   |
| GOODRAM             | 126       | 166     | 0.35%   |
| SK hynix            | 124       | 170     | 0.34%   |
| KingSpec            | 124       | 169     | 0.34%   |
| Patriot             | 117       | 150     | 0.33%   |
| AMD                 | 117       | 143     | 0.33%   |
| TF CARD             | 72        | 94      | 0.2%    |
| KingDian            | 63        | 94      | 0.18%   |
| Micron Technology   | 62        | 79      | 0.17%   |
| Gigabyte Technology | 60        | 79      | 0.17%   |
| Netac               | 58        | 70      | 0.16%   |
| Apple               | 49        | 62      | 0.14%   |
| ZTE                 | 46        | 53      | 0.13%   |
| Kingmax             | 46        | 96      | 0.13%   |
| Silicon Motion      | 42        | 51      | 0.12%   |
| JMicron Technology  | 36        | 38      | 0.1%    |
| XPG                 | 34        | 39      | 0.09%   |
| Mass                | 34        | Unknown | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 496       | 1.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 420       | 1.07%   |
| Seagate ST500LT012-1DG142 500GB     | 377       | 0.96%   |
| Seagate ST9500325AS 500GB           | 345       | 0.88%   |
| Seagate ST3500418AS 500GB           | 340       | 0.86%   |
| Toshiba MQ01ABF050 500GB            | 298       | 0.76%   |
| Kingston SV300S37A120G 120GB SSD    | 285       | 0.73%   |
| Toshiba DT01ACA050 500GB            | 284       | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB      | 282       | 0.72%   |
| Toshiba DT01ACA100 1TB              | 237       | 0.6%    |
| Seagate ST9320325AS 320GB           | 237       | 0.6%    |
| HGST HTS545050A7E680 500GB          | 223       | 0.57%   |
| Unknown xD/SD/M.S.                  | 207       | 0.53%   |
| Seagate ST3250410AS 250GB           | 192       | 0.49%   |
| Kingston SA400S37120G 120GB SSD     | 190       | 0.48%   |
| Seagate ST500LT012-9WS142 500GB     | 186       | 0.47%   |
| WDC WD5000AAKX-001CA0 500GB         | 182       | 0.46%   |
| Hitachi HTS543232A7A384 320GB       | 182       | 0.46%   |
| Seagate ST380011A 80GB              | 181       | 0.46%   |
| Seagate ST9250315AS 250GB           | 179       | 0.46%   |
| Seagate ST3160815AS 160GB           | 177       | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB      | 170       | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 166       | 0.42%   |
| Seagate ST31000528AS 1TB            | 163       | 0.41%   |
| Seagate ST3250310AS 250GB           | 162       | 0.41%   |
| Toshiba HDWD110 1TB                 | 161       | 0.41%   |
| Seagate ST31000524AS 1TB            | 161       | 0.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 158       | 0.4%    |
| Toshiba MQ01ABD100 1TB              | 157       | 0.4%    |
| Seagate ST380815AS 80GB             | 156       | 0.4%    |
| Kingston SA400S37240G 240GB SSD     | 150       | 0.38%   |
| Seagate ST320LT020-9YG142 320GB     | 145       | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB            | 143       | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB      | 142       | 0.36%   |
| HGST HTS545050A7E380 500GB          | 142       | 0.36%   |
| HUAWEI TF CARD Storage 16GB         | 135       | 0.34%   |
| HUAWEI SD Storage 128GB             | 134       | 0.34%   |
| Hitachi HTS547550A9E384 500GB       | 133       | 0.34%   |
| Hitachi HDS721050CLA362 500GB       | 133       | 0.34%   |
| Hitachi HTS545025B9A300 250GB       | 125       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8940      | 13959  | 33.94%  |
| WDC                 | 8143      | 12830  | 30.91%  |
| Hitachi             | 2965      | 4124   | 11.26%  |
| Toshiba             | 2707      | 3787   | 10.28%  |
| Samsung Electronics | 1734      | 2474   | 6.58%   |
| HGST                | 889       | 1331   | 3.37%   |
| Maxtor              | 472       | 606    | 1.79%   |
| Fujitsu             | 305       | 369    | 1.16%   |
| IBM/Hitachi         | 31        | 36     | 0.12%   |
| Unknown             | 29        | 39     | 0.11%   |
| Apple               | 27        | 34     | 0.1%    |
| Hewlett-Packard     | 12        | 23     | 0.05%   |
| ExcelStor           | 12        | 19     | 0.05%   |
| ASMT                | 10        | 23     | 0.04%   |
| WD MediaMax         | 8         | 12     | 0.03%   |
| Quantum             | 6         | 6      | 0.02%   |
| IBM                 | 6         | 9      | 0.02%   |
| USB3.0              | 4         | 4      | 0.02%   |
| ASMedia             | 4         | 11     | 0.02%   |
| Magnetic Data       | 3         | 3      | 0.01%   |
| Intenso             | 3         | 3      | 0.01%   |
| HGST HTS            | 3         | 3      | 0.01%   |
| PHD 3.0             | 2         | 2      | 0.01%   |
| JMicron Technology  | 2         | 2      | 0.01%   |
| HPE                 | 2         | 2      | 0.01%   |
| CLOVER              | 2         | 2      | 0.01%   |
| Unknown             | 2         | 2      | 0.01%   |
| ZALMAN              | 1         | 1      | 0.004%  |
| USB 3.0             | 1         | 1      | 0.004%  |
| USB                 | 1         | 1      | 0.004%  |
| TPH01204000GB       | 1         | 1      | 0.004%  |
| TPH00100500GB       | 1         | 1      | 0.004%  |
| Speeding            | 1         | 1      | 0.004%  |
| SILICONMOTION       | 1         | 1      | 0.004%  |
| Silicon             | 1         | 1      | 0.004%  |
| SAGE                | 1         | 1      | 0.004%  |
| SABRENT             | 1         | 1      | 0.004%  |
| OEM                 | 1         | 2      | 0.004%  |
| MSCC                | 1         | 1      | 0.004%  |
| MR2020              | 1         | 1      | 0.004%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1330      | 1823   | 17.67%  |
| Samsung Electronics | 899       | 1373   | 11.95%  |
| SanDisk             | 478       | 684    | 6.35%   |
| WDC                 | 395       | 524    | 5.25%   |
| China               | 378       | 506    | 5.02%   |
| OCZ                 | 373       | 503    | 4.96%   |
| SPCC                | 367       | 525    | 4.88%   |
| A-DATA Technology   | 352       | 484    | 4.68%   |
| Crucial             | 293       | 401    | 3.89%   |
| Intel               | 264       | 407    | 3.51%   |
| Plextor             | 253       | 377    | 3.36%   |
| Smartbuy            | 164       | 213    | 2.18%   |
| Apacer              | 147       | 203    | 1.95%   |
| Transcend           | 146       | 202    | 1.94%   |
| Corsair             | 133       | 176    | 1.77%   |
| KingSpec            | 124       | 169    | 1.65%   |
| GOODRAM             | 123       | 163    | 1.63%   |
| Toshiba             | 120       | 171    | 1.59%   |
| Patriot             | 110       | 143    | 1.46%   |
| AMD                 | 107       | 129    | 1.42%   |
| KingDian            | 62        | 93     | 0.82%   |
| Netac               | 46        | 56     | 0.61%   |
| Kingmax             | 46        | 96     | 0.61%   |
| Gigabyte Technology | 43        | 52     | 0.57%   |
| SK hynix            | 42        | 61     | 0.56%   |
| Micron Technology   | 38        | 49     | 0.5%    |
| LITEONIT            | 33        | 49     | 0.44%   |
| Team                | 30        | 36     | 0.4%    |
| JMicron Technology  | 27        | 30     | 0.36%   |
| XrayDisk            | 26        | 35     | 0.35%   |
| LITEON              | 26        | 37     | 0.35%   |
| KingFast            | 23        | 31     | 0.31%   |
| OCZ-VERTEX3         | 22        | 33     | 0.29%   |
| Apple               | 21        | 27     | 0.28%   |
| Unknown             | 21        | 23     | 0.28%   |
| PNY                 | 20        | 25     | 0.27%   |
| Intenso             | 19        | 24     | 0.25%   |
| Foxline             | 19        | 26     | 0.25%   |
| Zheino              | 17        | 22     | 0.23%   |
| Londisk             | 15        | 17     | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 22150     | 39737  | 71.33%  |
| SSD     | 6693      | 10520  | 21.55%  |
| NVMe    | 887       | 1298   | 2.86%   |
| Unknown | 696       | 838    | 2.24%   |
| MMC     | 628       | 861    | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 24919     | 49831  | 90.82%  |
| SAS  | 1017      | 1280   | 3.71%   |
| NVMe | 875       | 1282   | 3.19%   |
| MMC  | 628       | 861    | 2.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 21434     | 37194  | 72.9%   |
| 0.51-1.0        | 6528      | 10718  | 22.2%   |
| 1.01-2.0        | 1065      | 1739   | 3.62%   |
| 2.01-3.0        | 205       | 316    | 0.7%    |
| 3.01-4.0        | 116       | 198    | 0.39%   |
| 4.01-10.0       | 47        | 86     | 0.16%   |
| 10.01-20.0      | 4         | 5      | 0.01%   |
| More than 100.0 | 1         | 1      | 0.003%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 7487      | 25.24%  |
| 251-500        | 6521      | 21.98%  |
| 1-20           | 4155      | 14.01%  |
| 51-100         | 3419      | 11.52%  |
| 501-1000       | 3196      | 10.77%  |
| 21-50          | 2582      | 8.7%    |
| 1001-2000      | 1289      | 4.34%   |
| Unknown        | 457       | 1.54%   |
| 2001-3000      | 330       | 1.11%   |
| More than 3000 | 231       | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19150     | 64.7%   |
| 21-50          | 2810      | 9.49%   |
| 101-250        | 2219      | 7.5%    |
| 51-100         | 1916      | 6.47%   |
| 251-500        | 1510      | 5.1%    |
| 501-1000       | 971       | 3.28%   |
| Unknown        | 457       | 1.54%   |
| 1001-2000      | 395       | 1.33%   |
| 2001-3000      | 92        | 0.31%   |
| More than 3000 | 80        | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 248       | 341    | 1.98%   |
| Seagate ST500DM002-1BD142 500GB    | 201       | 264    | 1.61%   |
| Seagate ST500LT012-9WS142 500GB    | 181       | 227    | 1.45%   |
| Seagate ST3500418AS 500GB          | 170       | 232    | 1.36%   |
| Seagate ST9320325AS 320GB          | 139       | 176    | 1.11%   |
| Seagate ST3250410AS 250GB          | 122       | 156    | 0.98%   |
| Seagate ST9250315AS 250GB          | 121       | 151    | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 112       | 131    | 0.9%    |
| Seagate ST3250310AS 250GB          | 107       | 163    | 0.86%   |
| Seagate ST500LT012-1DG142 500GB    | 101       | 126    | 0.81%   |
| HGST HTS545050A7E680 500GB         | 101       | 135    | 0.81%   |
| WDC WD5000AAKX-001CA0 500GB        | 98        | 122    | 0.78%   |
| Seagate ST320LT020-9YG142 320GB    | 89        | 125    | 0.71%   |
| Seagate ST3320613AS 320GB          | 82        | 113    | 0.66%   |
| Seagate ST31000528AS 1TB           | 81        | 108    | 0.65%   |
| Hitachi HTS543232A7A384 320GB      | 79        | 97     | 0.63%   |
| Seagate ST3160815AS 160GB          | 70        | 83     | 0.56%   |
| HGST HTS545050A7E380 500GB         | 70        | 110    | 0.56%   |
| Hitachi HTS545025B9A300 250GB      | 69        | 89     | 0.55%   |
| WDC WD5000AADS-00S9B0 500GB        | 65        | 78     | 0.52%   |
| Seagate ST380011A 80GB             | 65        | 74     | 0.52%   |
| Samsung Electronics HD080HJ 80GB   | 65        | 80     | 0.52%   |
| Seagate ST3160811AS 160GB          | 64        | 90     | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB     | 62        | 90     | 0.5%    |
| Seagate ST31000524AS 1TB           | 61        | 88     | 0.49%   |
| Hitachi HTS541612J9SA00 120GB      | 60        | 74     | 0.48%   |
| Hitachi HDS721616PLA380 160GB      | 59        | 77     | 0.47%   |
| Seagate ST320LT012-9WS14C 320GB    | 57        | 82     | 0.46%   |
| Toshiba MQ01ABD050 500GB           | 56        | 72     | 0.45%   |
| Hitachi HTS547550A9E384 500GB      | 56        | 77     | 0.45%   |
| Seagate ST1000DM003-9YN162 1TB     | 55        | 66     | 0.44%   |
| Samsung Electronics HD160JJ/ 160GB | 55        | 85     | 0.44%   |
| Hitachi HDS721050CLA362 500GB      | 54        | 69     | 0.43%   |
| Hitachi HDP725050GLA360 500GB      | 54        | 72     | 0.43%   |
| Seagate ST3250318AS 250GB          | 53        | 71     | 0.42%   |
| Hitachi HTS547575A9E384 752GB      | 53        | 76     | 0.42%   |
| Hitachi HTS545050B9A300 500GB      | 53        | 75     | 0.42%   |
| WDC WD3200AAJS-00L7A0 320GB        | 50        | 59     | 0.4%    |
| WDC WD10EARS-00Y5B1 1TB            | 50        | 82     | 0.4%    |
| Seagate ST9500420AS 500GB          | 50        | 72     | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4105      | 5758   | 34.37%  |
| WDC                 | 2835      | 3942   | 23.74%  |
| Hitachi             | 1607      | 2152   | 13.46%  |
| Samsung Electronics | 931       | 1257   | 7.8%    |
| Toshiba             | 870       | 1148   | 7.28%   |
| HGST                | 292       | 412    | 2.44%   |
| Maxtor              | 281       | 347    | 2.35%   |
| Kingston            | 173       | 214    | 1.45%   |
| Fujitsu             | 129       | 157    | 1.08%   |
| SanDisk             | 81        | 98     | 0.68%   |
| SPCC                | 68        | 86     | 0.57%   |
| OCZ                 | 68        | 96     | 0.57%   |
| Intel               | 60        | 71     | 0.5%    |
| A-DATA Technology   | 50        | 73     | 0.42%   |
| Corsair             | 41        | 51     | 0.34%   |
| Kingmax             | 31        | 58     | 0.26%   |
| Crucial             | 31        | 48     | 0.26%   |
| IBM/Hitachi         | 27        | 32     | 0.23%   |
| China               | 27        | 35     | 0.23%   |
| KingSpec            | 22        | 33     | 0.18%   |
| Plextor             | 18        | 24     | 0.15%   |
| AMD                 | 14        | 18     | 0.12%   |
| SK hynix            | 13        | 18     | 0.11%   |
| LITEONIT            | 12        | 17     | 0.1%    |
| Transcend           | 9         | 11     | 0.08%   |
| OCZ-VERTEX3         | 8         | 15     | 0.07%   |
| Netac               | 8         | 9      | 0.07%   |
| ExcelStor           | 8         | 10     | 0.07%   |
| Apple               | 7         | 8      | 0.06%   |
| Micron Technology   | 6         | 11     | 0.05%   |
| Patriot             | 5         | 5      | 0.04%   |
| Mushkin             | 5         | 5      | 0.04%   |
| IBM                 | 5         | 7      | 0.04%   |
| Unknown             | 5         | 7      | 0.04%   |
| Smartbuy            | 4         | 4      | 0.03%   |
| Hewlett-Packard     | 4         | 5      | 0.03%   |
| Apacer              | 4         | 9      | 0.03%   |
| WD MediaMax         | 3         | 5      | 0.03%   |
| Team                | 3         | 3      | 0.03%   |
| SSSTC               | 3         | 4      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4105      | 5758   | 37.21%  |
| WDC                 | 2795      | 3882   | 25.33%  |
| Hitachi             | 1607      | 2152   | 14.57%  |
| Samsung Electronics | 899       | 1218   | 8.15%   |
| Toshiba             | 864       | 1142   | 7.83%   |
| HGST                | 292       | 412    | 2.65%   |
| Maxtor              | 281       | 347    | 2.55%   |
| Fujitsu             | 129       | 157    | 1.17%   |
| IBM/Hitachi         | 27        | 32     | 0.24%   |
| ExcelStor           | 8         | 10     | 0.07%   |
| IBM                 | 5         | 7      | 0.05%   |
| Apple               | 5         | 6      | 0.05%   |
| WD MediaMax         | 3         | 5      | 0.03%   |
| Hewlett-Packard     | 3         | 4      | 0.03%   |
| Quantum             | 2         | 2      | 0.02%   |
| ASMT                | 2         | 4      | 0.02%   |
| TPH00100500GB       | 1         | 1      | 0.01%   |
| MARSHAL             | 1         | 2      | 0.01%   |
| Magnetic Data       | 1         | 1      | 0.01%   |
| LaCie               | 1         | 1      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10104     | 15145  | 91.8%   |
| SSD  | 883       | 1184   | 8.02%   |
| NVMe | 19        | 25     | 0.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB          | 13        | 14     | 3.23%   |
| Seagate ST31000528AS 1TB           | 12        | 14     | 2.98%   |
| Seagate ST9500325AS 500GB          | 7         | 9      | 1.74%   |
| Seagate ST31000524AS 1TB           | 7         | 8      | 1.74%   |
| Samsung Electronics HM321HI 320GB  | 7         | 9      | 1.74%   |
| HGST HTS545050A7E680 500GB         | 7         | 7      | 1.74%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 6         | 7      | 1.49%   |
| Seagate ST3500412AS 500GB          | 6         | 8      | 1.49%   |
| Hitachi HDS721010DLE630 1TB        | 6         | 8      | 1.49%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 5         | 6      | 1.24%   |
| Seagate ST9320325AS 320GB          | 5         | 6      | 1.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 5      | 1.24%   |
| Samsung Electronics HD502HJ 500GB  | 5         | 5      | 1.24%   |
| HGST HTS545050A7E380 500GB         | 5         | 5      | 1.24%   |
| Toshiba MQ01ABD050 500GB           | 4         | 4      | 0.99%   |
| Toshiba MK6465GSX 640GB            | 4         | 6      | 0.99%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 0.99%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 0.99%   |
| Seagate ST3500410AS 500GB          | 4         | 5      | 0.99%   |
| Seagate ST31000333AS 1TB           | 4         | 4      | 0.99%   |
| Samsung Electronics SP0411N 40GB   | 4         | 5      | 0.99%   |
| Samsung Electronics HD502IJ 500GB  | 4         | 4      | 0.99%   |
| Samsung Electronics HD322GJ 320GB  | 4         | 5      | 0.99%   |
| WDC WD5000AAKS-00V1A0 500GB        | 3         | 4      | 0.74%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 3      | 0.74%   |
| WDC WD3200AAJS-00L7A0 320GB        | 3         | 4      | 0.74%   |
| WDC WD1600BEVS-22RST0 160GB        | 3         | 4      | 0.74%   |
| WDC WD15EARS-00MVWB0 1TB           | 3         | 6      | 0.74%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 0.74%   |
| Seagate ST3750528AS 752GB          | 3         | 3      | 0.74%   |
| Seagate ST32000542AS 2TB           | 3         | 5      | 0.74%   |
| Samsung Electronics HM160HI 160GB  | 3         | 3      | 0.74%   |
| Maxtor 6Y080L0 82GB                | 3         | 3      | 0.74%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 0.74%   |
| Hitachi HTS547550A9E384 500GB      | 3         | 4      | 0.74%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 3      | 0.74%   |
| Hitachi HDS721050DLE630 500GB      | 3         | 3      | 0.74%   |
| HGST HTS721010A9E630 1TB           | 3         | 4      | 0.74%   |
| WDC WD7501AALS-00J7B0 752GB        | 2         | 2      | 0.5%    |
| WDC WD5000BPVT-00HXZT1 500GB       | 2         | 2      | 0.5%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 122       | 149    | 30.42%  |
| WDC                 | 105       | 124    | 26.18%  |
| Samsung Electronics | 63        | 72     | 15.71%  |
| Toshiba             | 38        | 44     | 9.48%   |
| Hitachi             | 38        | 42     | 9.48%   |
| HGST                | 19        | 21     | 4.74%   |
| Maxtor              | 10        | 10     | 2.49%   |
| Fujitsu             | 2         | 2      | 0.5%    |
| Apple               | 2         | 3      | 0.5%    |
| Hewlett-Packard     | 1         | 1      | 0.25%   |
| Corsair             | 1         | 1      | 0.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 17916     | 33350  | 57.4%   |
| Malfunc  | 10766     | 16354  | 34.49%  |
| Detected | 2132      | 3081   | 6.83%   |
| Failed   | 398       | 469    | 1.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 18042     | 62.92%  |
| AMD                              | 5478      | 19.1%   |
| Nvidia                           | 1514      | 5.28%   |
| JMicron Technology               | 1091      | 3.8%    |
| Marvell Technology Group         | 593       | 2.07%   |
| ASMedia Technology               | 365       | 1.27%   |
| VIA Technologies                 | 326       | 1.14%   |
| Samsung Electronics              | 247       | 0.86%   |
| Silicon Integrated Systems [SiS] | 189       | 0.66%   |
| SanDisk                          | 102       | 0.36%   |
| Silicon Motion                   | 98        | 0.34%   |
| Kingston Technology Company      | 97        | 0.34%   |
| SK hynix                         | 60        | 0.21%   |
| Phison Electronics               | 58        | 0.2%    |
| Silicon Image                    | 55        | 0.19%   |
| ADATA Technology                 | 51        | 0.18%   |
| Integrated Technology Express    | 42        | 0.15%   |
| Realtek Semiconductor            | 34        | 0.12%   |
| Micron Technology                | 24        | 0.08%   |
| KIOXIA                           | 20        | 0.07%   |
| LSI Logic / Symbios Logic        | 19        | 0.07%   |
| Lite-On Technology               | 18        | 0.06%   |
| ULi Electronics                  | 16        | 0.06%   |
| Toshiba America Info Systems     | 15        | 0.05%   |
| Union Memory (Shenzhen)          | 14        | 0.05%   |
| Micron/Crucial Technology        | 14        | 0.05%   |
| Adaptec                          | 13        | 0.05%   |
| Solid State Storage Technology   | 10        | 0.03%   |
| MAXIO Technology (Hangzhou)      | 10        | 0.03%   |
| Netac Technology                 | 8         | 0.03%   |
| Hewlett-Packard                  | 8         | 0.03%   |
| Promise Technology               | 7         | 0.02%   |
| OCZ Technology Group             | 7         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 6         | 0.02%   |
| Shenzhen Longsys Electronics     | 4         | 0.01%   |
| Broadcom / LSI                   | 3         | 0.01%   |
| ATI Technologies                 | 3         | 0.01%   |
| Transcend                        | 2         | 0.01%   |
| Seagate Technology               | 2         | 0.01%   |
| Artop Electronic                 | 2         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 2086      | 5.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2047      | 5.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1769      | 4.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1702      | 4.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1647      | 4.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1493      | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1225      | 3.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1181      | 3.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1070      | 2.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 850       | 2.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 715       | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 707       | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 705       | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 674       | 1.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 668       | 1.73%   |
| Nvidia MCP61 SATA Controller                                                            | 663       | 1.72%   |
| Nvidia MCP61 IDE                                                                        | 619       | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 607       | 1.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 536       | 1.39%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 534       | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 483       | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 436       | 1.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 425       | 1.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 425       | 1.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 424       | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 420       | 1.09%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 397       | 1.03%   |
| JMicron JMB368 IDE controller                                                           | 377       | 0.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 368       | 0.95%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 349       | 0.91%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 330       | 0.86%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 321       | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 320       | 0.83%   |
| AMD SB600 IDE                                                                           | 318       | 0.82%   |
| AMD FCH IDE Controller                                                                  | 311       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 309       | 0.8%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 303       | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 268       | 0.7%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 232       | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 231       | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 17669     | 58.59%  |
| IDE  | 10914     | 36.19%  |
| NVMe | 881       | 2.92%   |
| RAID | 653       | 2.17%   |
| SCSI | 23        | 0.08%   |
| SAS  | 16        | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 18910     | 73.57%  |
| AMD          | 6778      | 26.37%  |
| CentaurHauls | 12        | 0.05%   |
| ARM          | 3         | 0.01%   |
| MBE8C-PC     | 1         | 0.004%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 241       | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 218       | 0.84%   |
| Intel Pentium 4 CPU 3.00GHz                 | 200       | 0.77%   |
| Intel Atom CPU N450 @ 1.66GHz               | 170       | 0.66%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 161       | 0.62%   |
| Intel Atom CPU N270 @ 1.60GHz               | 156       | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 155       | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 152       | 0.59%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 152       | 0.59%   |
| AMD Athlon II X2 250 Processor              | 151       | 0.58%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 145       | 0.56%   |
| AMD FX-6300 Six-Core Processor              | 145       | 0.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 144       | 0.56%   |
| AMD E-450 APU with Radeon HD Graphics       | 140       | 0.54%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 133       | 0.51%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 132       | 0.51%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 130       | 0.5%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 130       | 0.5%    |
| Intel Core i3-2310M CPU @ 2.10GHz           | 129       | 0.5%    |
| Intel Atom CPU N2600 @ 1.60GHz              | 128       | 0.49%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 127       | 0.49%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 125       | 0.48%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 124       | 0.48%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 122       | 0.47%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 116       | 0.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 114       | 0.44%   |
| Intel Atom CPU N455 @ 1.66GHz               | 113       | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 111       | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 106       | 0.41%   |
| AMD FX-8350 Eight-Core Processor            | 105       | 0.41%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 104       | 0.4%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 103       | 0.4%    |
| Intel Atom CPU N570 @ 1.66GHz               | 102       | 0.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 100       | 0.39%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 99        | 0.38%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 97        | 0.37%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 90        | 0.35%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 89        | 0.34%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 85        | 0.33%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 85        | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3662      | 14.16%  |
| Intel Core i3           | 2736      | 10.58%  |
| Intel Core 2 Duo        | 2059      | 7.96%   |
| Intel Celeron           | 1932      | 7.47%   |
| Intel Pentium           | 1750      | 6.77%   |
| Intel Core i7           | 1564      | 6.05%   |
| Intel Atom              | 1201      | 4.64%   |
| Intel Pentium Dual-Core | 856       | 3.31%   |
| AMD FX                  | 741       | 2.87%   |
| AMD Athlon 64 X2        | 726       | 2.81%   |
| AMD Athlon II X2        | 510       | 1.97%   |
| Intel Core 2 Quad       | 474       | 1.83%   |
| Intel Pentium 4         | 458       | 1.77%   |
| Intel Xeon              | 414       | 1.6%    |
| Intel Core 2            | 409       | 1.58%   |
| Intel Pentium Dual      | 408       | 1.58%   |
| AMD A6                  | 351       | 1.36%   |
| AMD A4                  | 332       | 1.28%   |
| AMD Ryzen 5             | 323       | 1.25%   |
| AMD A8                  | 321       | 1.24%   |
| AMD Phenom II X4        | 316       | 1.22%   |
| AMD A10                 | 283       | 1.09%   |
| AMD E                   | 275       | 1.06%   |
| Intel Genuine           | 231       | 0.89%   |
| AMD Athlon II X4        | 217       | 0.84%   |
| AMD E1                  | 179       | 0.69%   |
| Intel Pentium D         | 171       | 0.66%   |
| AMD Athlon II X3        | 164       | 0.63%   |
| Other                   | 163       | 0.63%   |
| AMD Athlon 64           | 161       | 0.62%   |
| Intel Celeron M         | 139       | 0.54%   |
| AMD Ryzen 3             | 125       | 0.48%   |
| AMD Ryzen 7             | 123       | 0.48%   |
| AMD Turion 64 X2 Mobile | 117       | 0.45%   |
| Intel Celeron Dual-Core | 116       | 0.45%   |
| AMD Phenom              | 114       | 0.44%   |
| AMD E2                  | 114       | 0.44%   |
| AMD Athlon              | 112       | 0.43%   |
| AMD Sempron             | 111       | 0.43%   |
| AMD Athlon X4           | 102       | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 15134     | 57.38%  |
| 4       | 5721      | 21.69%  |
| 1       | 2174      | 8.24%   |
| Unknown | 1870      | 7.09%   |
| 6       | 667       | 2.53%   |
| 3       | 447       | 1.69%   |
| 8       | 277       | 1.05%   |
| 12      | 35        | 0.13%   |
| 10      | 17        | 0.06%   |
| 16      | 10        | 0.04%   |
| 20      | 7         | 0.03%   |
| 24      | 6         | 0.02%   |
| 192     | 2         | 0.01%   |
| 18      | 2         | 0.01%   |
| 120     | 1         | 0.004%  |
| 28      | 1         | 0.004%  |
| 14      | 1         | 0.004%  |
| 5       | 1         | 0.004%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 25522     | 99%     |
| Unknown | 159       | 0.62%   |
| 2       | 91        | 0.35%   |
| 4       | 7         | 0.03%   |
| 8       | 2         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 14804     | 56.14%  |
| 2       | 9695      | 36.77%  |
| Unknown | 1870      | 7.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24170     | 93.11%  |
| 32-bit         | 984       | 3.79%   |
| Unknown        | 626       | 2.41%   |
| 64-bit         | 179       | 0.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 2928      | 11.12%  |
| 0x306a9    | 2395      | 9.1%    |
| 0x1067a    | 2172      | 8.25%   |
| Unknown    | 1732      | 6.58%   |
| 0x306c3    | 1268      | 4.82%   |
| 0x6fd      | 996       | 3.78%   |
| 0x010000c8 | 923       | 3.51%   |
| 0x20655    | 810       | 3.08%   |
| 0x10676    | 611       | 2.32%   |
| 0x106ca    | 545       | 2.07%   |
| 0x06001119 | 513       | 1.95%   |
| 0x30678    | 458       | 1.74%   |
| 0x40651    | 440       | 1.67%   |
| 0x6fb      | 428       | 1.63%   |
| 0x20652    | 335       | 1.27%   |
| 0x506e3    | 334       | 1.27%   |
| 0x6f6      | 284       | 1.08%   |
| 0x03000027 | 267       | 1.01%   |
| 0x906e9    | 257       | 0.98%   |
| 0x106c2    | 252       | 0.96%   |
| 0x05000119 | 239       | 0.91%   |
| 0x10661    | 228       | 0.87%   |
| 0x30661    | 226       | 0.86%   |
| 0x0600084f | 222       | 0.84%   |
| 0x306d4    | 215       | 0.82%   |
| 0x906ea    | 201       | 0.76%   |
| 0x406c4    | 198       | 0.75%   |
| 0x106e5    | 195       | 0.74%   |
| 0x06000852 | 195       | 0.74%   |
| 0x406e3    | 183       | 0.7%    |
| 0x010000b6 | 182       | 0.69%   |
| 0x07030105 | 168       | 0.64%   |
| 0x6f2      | 167       | 0.63%   |
| 0x406c3    | 163       | 0.62%   |
| 0x010000db | 162       | 0.62%   |
| 0xf41      | 140       | 0.53%   |
| 0x6e8      | 135       | 0.51%   |
| 0xf49      | 134       | 0.51%   |
| 0x06003106 | 133       | 0.51%   |
| 0x806e9    | 127       | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 3002      | 11.59%  |
| Penryn           | 2796      | 10.8%   |
| IvyBridge        | 2456      | 9.48%   |
| Core             | 2302      | 8.89%   |
| K10              | 1857      | 7.17%   |
| Haswell          | 1786      | 6.9%    |
| Westmere         | 1187      | 4.58%   |
| K8 Hammer        | 1140      | 4.4%    |
| Piledriver       | 1114      | 4.3%    |
| Bonnell          | 967       | 3.73%   |
| Silvermont       | 896       | 3.46%   |
| KabyLake         | 846       | 3.27%   |
| NetBurst         | 815       | 3.15%   |
| Skylake          | 546       | 2.11%   |
| Bobcat           | 478       | 1.85%   |
| Unknown          | 420       | 1.62%   |
| P6               | 344       | 1.33%   |
| K10 Llano        | 325       | 1.25%   |
| Nehalem          | 271       | 1.05%   |
| Broadwell        | 233       | 0.9%    |
| Zen              | 216       | 0.83%   |
| Puma             | 216       | 0.83%   |
| Zen+             | 209       | 0.81%   |
| Bulldozer        | 193       | 0.75%   |
| Excavator        | 189       | 0.73%   |
| Jaguar           | 181       | 0.7%    |
| Steamroller      | 152       | 0.59%   |
| Zen 2            | 125       | 0.48%   |
| K8 & K10 hybrid  | 122       | 0.47%   |
| Goldmont plus    | 105       | 0.41%   |
| CometLake        | 97        | 0.37%   |
| Goldmont         | 95        | 0.37%   |
| Zen 3            | 86        | 0.33%   |
| Icelake          | 41        | 0.16%   |
| TigerLake        | 34        | 0.13%   |
| K6               | 26        | 0.1%    |
| Tremont          | 15        | 0.06%   |
| Alderlake Hybrid | 15        | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 11151     | 37.61%  |
| Nvidia                           | 10707     | 36.12%  |
| AMD                              | 7624      | 25.72%  |
| Silicon Integrated Systems [SiS] | 61        | 0.21%   |
| VIA Technologies                 | 48        | 0.16%   |
| Matrox Electronics Systems       | 23        | 0.08%   |
| ASPEED Technology                | 16        | 0.05%   |
| ATI Technologies                 | 8         | 0.03%   |
| S3 Graphics                      | 5         | 0.02%   |
| Zhaoxin                          | 1         | 0.003%  |
| Trident Microsystems             | 1         | 0.003%  |
| Huawei Technologies              | 1         | 0.003%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2061      | 6.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1395      | 4.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 585       | 1.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 574       | 1.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 524       | 1.64%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 514       | 1.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 439       | 1.38%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 425       | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 380       | 1.19%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 380       | 1.19%   |
| Nvidia GT218 [GeForce 210]                                                               | 375       | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 369       | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 369       | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 368       | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 322       | 1.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 282       | 0.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 278       | 0.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 275       | 0.86%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 249       | 0.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 245       | 0.77%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 239       | 0.75%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 236       | 0.74%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 229       | 0.72%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 219       | 0.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 216       | 0.68%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 216       | 0.68%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 216       | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 215       | 0.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 214       | 0.67%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 198       | 0.62%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 194       | 0.61%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 193       | 0.61%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 187       | 0.59%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 179       | 0.56%   |
| Intel HD Graphics 5500                                                                   | 175       | 0.55%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 170       | 0.53%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 169       | 0.53%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 167       | 0.52%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 167       | 0.52%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 166       | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| 1 x Nvidia                    | 7979      | 30.56%  |
| 1 x Intel                     | 7636      | 29.25%  |
| 1 x AMD                       | 5829      | 22.33%  |
| Intel + Nvidia                | 2634      | 10.09%  |
| 2 x AMD                       | 1070      | 4.1%    |
| Intel + AMD                   | 682       | 2.61%   |
| AMD + Nvidia                  | 64        | 0.25%   |
| 1 x SiS                       | 61        | 0.23%   |
| 1 x VIA                       | 48        | 0.18%   |
| 2 x Nvidia                    | 33        | 0.13%   |
| 1 x Matrox                    | 18        | 0.07%   |
| Other                         | 15        | 0.06%   |
| 1 x ASPEED                    | 9         | 0.03%   |
| Nvidia + Matrox               | 5         | 0.02%   |
| 1 x S3 Graphics               | 4         | 0.02%   |
| AMD + ASPEED                  | 4         | 0.02%   |
| 3 x AMD                       | 3         | 0.01%   |
| 3 x Nvidia                    | 2         | 0.01%   |
| Nvidia + ASPEED               | 2         | 0.01%   |
| 2 x AMD + 1 x Nvidia          | 1         | 0.004%  |
| 1 x Zhaoxin                   | 1         | 0.004%  |
| 1 x Trident Microsystems      | 1         | 0.004%  |
| Intel + 2 x Nvidia            | 1         | 0.004%  |
| Intel + SiS + 1 x S3 Graphics | 1         | 0.004%  |
| Intel + ASPEED                | 1         | 0.004%  |
| 1 x Huawei Technologies       | 1         | 0.004%  |
| AMD + 2 x Nvidia              | 1         | 0.004%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 21853     | 80.64%  |
| Proprietary | 3687      | 13.61%  |
| Unknown     | 1558      | 5.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 8372      | 30.53%  |
| 0.01-0.5   | 7303      | 26.63%  |
| Unknown    | 5855      | 21.35%  |
| 0.51-1.0   | 3958      | 14.43%  |
| 3.01-4.0   | 1393      | 5.08%   |
| 7.01-8.0   | 216       | 0.79%   |
| 2.01-3.0   | 163       | 0.59%   |
| 5.01-6.0   | 130       | 0.47%   |
| 8.01-16.0  | 31        | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 5576      | 21.86%  |
| AU Optronics            | 2786      | 10.92%  |
| LG Display              | 2236      | 8.77%   |
| Goldstar                | 2215      | 8.68%   |
| Acer                    | 1512      | 5.93%   |
| Chi Mei Optoelectronics | 1181      | 4.63%   |
| BenQ                    | 1074      | 4.21%   |
| Chimei Innolux          | 979       | 3.84%   |
| Philips                 | 886       | 3.47%   |
| BOE                     | 661       | 2.59%   |
| ViewSonic               | 622       | 2.44%   |
| Dell                    | 547       | 2.14%   |
| Ancor Communications    | 531       | 2.08%   |
| AOC                     | 480       | 1.88%   |
| Hewlett-Packard         | 426       | 1.67%   |
| LG Philips              | 423       | 1.66%   |
| Lenovo                  | 396       | 1.55%   |
| HannStar                | 324       | 1.27%   |
| NEC Computers           | 313       | 1.23%   |
| Sony                    | 213       | 0.83%   |
| CPT                     | 182       | 0.71%   |
| Iiyama                  | 140       | 0.55%   |
| InfoVision              | 127       | 0.5%    |
| Apple                   | 112       | 0.44%   |
| Plain Tree Systems      | 79        | 0.31%   |
| Toshiba                 | 76        | 0.3%    |
| Envision Peripherals    | 58        | 0.23%   |
| Fujitsu Siemens         | 57        | 0.22%   |
| Unknown                 | 52        | 0.2%    |
| InnoLux Display         | 51        | 0.2%    |
| Quanta Display          | 48        | 0.19%   |
| Packard Bell            | 48        | 0.19%   |
| Sharp                   | 47        | 0.18%   |
| ___                     | 42        | 0.16%   |
| MiTAC                   | 41        | 0.16%   |
| Panasonic               | 40        | 0.16%   |
| ASUSTek Computer        | 38        | 0.15%   |
| PANDA                   | 33        | 0.13%   |
| Belinea                 | 30        | 0.12%   |
| KTC                     | 26        | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 337       | 1.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 310       | 1.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 246       | 0.95%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 211       | 0.81%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 155       | 0.6%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 134       | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 128       | 0.49%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 122       | 0.47%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 116       | 0.45%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch      | 114       | 0.44%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 107       | 0.41%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 104       | 0.4%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch      | 103       | 0.4%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 97        | 0.37%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch      | 96        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 95        | 0.37%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 95        | 0.37%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                   | 93        | 0.36%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 89        | 0.34%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch      | 78        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 75        | 0.29%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 75        | 0.29%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                        | 72        | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 71        | 0.27%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 69        | 0.27%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 66        | 0.25%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 66        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 66        | 0.25%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch              | 62        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 62        | 0.24%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 60        | 0.23%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                  | 59        | 0.23%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                       | 59        | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 57        | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 57        | 0.22%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch             | 57        | 0.22%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch      | 56        | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                   | 55        | 0.21%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch               | 55        | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 55        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 7118      | 28.18%  |
| 1920x1080 (FHD)    | 7077      | 28.02%  |
| 1280x1024 (SXGA)   | 3262      | 12.91%  |
| 1600x900 (HD+)     | 1574      | 6.23%   |
| 1280x800 (WXGA)    | 1297      | 5.13%   |
| 1440x900 (WXGA+)   | 1123      | 4.45%   |
| 1680x1050 (WSXGA+) | 1111      | 4.4%    |
| 1024x600           | 595       | 2.36%   |
| 1920x1200 (WUXGA)  | 353       | 1.4%    |
| 3840x2160 (4K)     | 313       | 1.24%   |
| 1024x768 (XGA)     | 290       | 1.15%   |
| 1360x768           | 285       | 1.13%   |
| 2560x1440 (QHD)    | 211       | 0.84%   |
| 1600x1200          | 152       | 0.6%    |
| 2560x1080          | 97        | 0.38%   |
| 1920x540           | 63        | 0.25%   |
| 1280x720 (HD)      | 59        | 0.23%   |
| 1400x1050          | 49        | 0.19%   |
| 1152x864           | 38        | 0.15%   |
| 3440x1440          | 24        | 0.1%    |
| 2288x1287          | 24        | 0.1%    |
| 1680x945           | 20        | 0.08%   |
| 2560x1600          | 17        | 0.07%   |
| 2048x1536          | 16        | 0.06%   |
| 2048x1152          | 13        | 0.05%   |
| 1920x1440          | 12        | 0.05%   |
| 1280x960           | 12        | 0.05%   |
| 2160x1440          | 8         | 0.03%   |
| 1280x768           | 8         | 0.03%   |
| 1024x576           | 8         | 0.03%   |
| 2880x1800          | 4         | 0.02%   |
| Unknown            | 4         | 0.02%   |
| 4093x4093          | 3         | 0.01%   |
| 3200x1800 (QHD+)   | 3         | 0.01%   |
| 2880x1920          | 3         | 0.01%   |
| 2736x1824          | 3         | 0.01%   |
| 832x624            | 1         | 0.004%  |
| 640x480            | 1         | 0.004%  |
| 3840x2560          | 1         | 0.004%  |
| 3840x1200          | 1         | 0.004%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 7930      | 30.97%  |
| 17      | 2787      | 10.88%  |
| 19      | 2302      | 8.99%   |
| 21      | 2259      | 8.82%   |
| 23      | 1875      | 7.32%   |
| 24      | 1092      | 4.26%   |
| 18      | 998       | 3.9%    |
| 14      | 863       | 3.37%   |
| 20      | 812       | 3.17%   |
| 13      | 676       | 2.64%   |
| 27      | 666       | 2.6%    |
| 22      | 636       | 2.48%   |
| 10      | 619       | 2.42%   |
| 11      | 319       | 1.25%   |
| 12      | 267       | 1.04%   |
| Unknown | 209       | 0.82%   |
| 31      | 166       | 0.65%   |
| 72      | 130       | 0.51%   |
| 54      | 110       | 0.43%   |
| 40      | 102       | 0.4%    |
| 16      | 101       | 0.39%   |
| 32      | 100       | 0.39%   |
| 34      | 89        | 0.35%   |
| 52      | 60        | 0.23%   |
| 26      | 57        | 0.22%   |
| 25      | 53        | 0.21%   |
| 84      | 51        | 0.2%    |
| 46      | 43        | 0.17%   |
| 8       | 34        | 0.13%   |
| 48      | 30        | 0.12%   |
| 42      | 24        | 0.09%   |
| 43      | 17        | 0.07%   |
| 28      | 15        | 0.06%   |
| 37      | 12        | 0.05%   |
| 65      | 10        | 0.04%   |
| 55      | 10        | 0.04%   |
| 33      | 10        | 0.04%   |
| 29      | 10        | 0.04%   |
| 47      | 7         | 0.03%   |
| 50      | 6         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 10380     | 40.92%  |
| 401-500        | 5421      | 21.37%  |
| 501-600        | 3538      | 13.95%  |
| 351-400        | 3059      | 12.06%  |
| 201-300        | 1639      | 6.46%   |
| 1001-1500      | 290       | 1.14%   |
| 601-700        | 231       | 0.91%   |
| Unknown        | 209       | 0.82%   |
| 701-800        | 202       | 0.8%    |
| 1501-2000      | 186       | 0.73%   |
| 801-900        | 123       | 0.48%   |
| 901-1000       | 45        | 0.18%   |
| 101-200        | 36        | 0.14%   |
| More than 2000 | 9         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 16779     | 67.59%  |
| 16/10   | 3774      | 15.2%   |
| 5/4     | 3064      | 12.34%  |
| 4/3     | 815       | 3.28%   |
| 3/2     | 188       | 0.76%   |
| 21/9    | 96        | 0.39%   |
| 6/5     | 57        | 0.23%   |
| Unknown | 32        | 0.13%   |
| 32/9    | 11        | 0.04%   |
| 1.00    | 5         | 0.02%   |
| 2.21    | 1         | 0.004%  |
| 2.00    | 1         | 0.004%  |
| 1.96    | 1         | 0.004%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7663      | 30.07%  |
| 201-250        | 5029      | 19.73%  |
| 151-200        | 3789      | 14.87%  |
| 141-150        | 2338      | 9.17%   |
| 81-90          | 1154      | 4.53%   |
| 121-130        | 929       | 3.65%   |
| 301-350        | 712       | 2.79%   |
| 41-50          | 622       | 2.44%   |
| More than 1000 | 432       | 1.7%    |
| 351-500        | 367       | 1.44%   |
| 251-300        | 357       | 1.4%    |
| 71-80          | 335       | 1.31%   |
| 131-140        | 334       | 1.31%   |
| 51-60          | 319       | 1.25%   |
| 111-120        | 246       | 0.97%   |
| 61-70          | 242       | 0.95%   |
| 501-1000       | 231       | 0.91%   |
| Unknown        | 209       | 0.82%   |
| 91-100         | 141       | 0.55%   |
| 1-40           | 36        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 12305     | 49.36%  |
| 101-120       | 9470      | 37.99%  |
| 121-160       | 2197      | 8.81%   |
| 1-50          | 555       | 2.23%   |
| Unknown       | 209       | 0.84%   |
| 161-240       | 164       | 0.66%   |
| More than 240 | 27        | 0.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 24139     | 92.25%  |
| 2     | 1420      | 5.43%   |
| 0     | 565       | 2.16%   |
| 3     | 44        | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 15751     | 39.96%  |
| Qualcomm Atheros                       | 7936      | 20.13%  |
| Intel                                  | 4536      | 11.51%  |
| Broadcom                               | 2883      | 7.31%   |
| Nvidia                                 | 1245      | 3.16%   |
| Marvell Technology Group               | 1047      | 2.66%   |
| Broadcom Limited                       | 834       | 2.12%   |
| Ralink                                 | 819       | 2.08%   |
| Huawei Technologies                    | 653       | 1.66%   |
| Ralink Technology                      | 593       | 1.5%    |
| VIA Technologies                       | 319       | 0.81%   |
| Qualcomm Atheros Communications        | 240       | 0.61%   |
| D-Link System                          | 208       | 0.53%   |
| D-Link                                 | 190       | 0.48%   |
| TP-Link                                | 179       | 0.45%   |
| JMicron Technology                     | 176       | 0.45%   |
| ASUSTek Computer                       | 165       | 0.42%   |
| Attansic Technology                    | 153       | 0.39%   |
| MediaTek                               | 143       | 0.36%   |
| ZTE WCDMA Technologies MSM             | 134       | 0.34%   |
| Silicon Integrated Systems [SiS]       | 132       | 0.33%   |
| Samsung Electronics                    | 87        | 0.22%   |
| Xiaomi                                 | 76        | 0.19%   |
| Sundance Technology Inc / IC Plus      | 66        | 0.17%   |
| HTC (High Tech Computer)               | 57        | 0.14%   |
| Gemtek                                 | 48        | 0.12%   |
| NetGear                                | 46        | 0.12%   |
| 3Com                                   | 46        | 0.12%   |
| Ericsson Business Mobile Networks      | 39        | 0.1%    |
| Qualcomm                               | 28        | 0.07%   |
| ASIX Electronics                       | 26        | 0.07%   |
| T & A Mobile Phones                    | 23        | 0.06%   |
| Hewlett-Packard                        | 23        | 0.06%   |
| LSI                                    | 22        | 0.06%   |
| IMC Networks                           | 22        | 0.06%   |
| Microsoft                              | 20        | 0.05%   |
| ZyXEL Communications                   | 19        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 19        | 0.05%   |
| Lenovo                                 | 17        | 0.04%   |
| Vimtron Electronics                    | 16        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 11180     | 25.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2867      | 6.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2000      | 4.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1205      | 2.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 861       | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 859       | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 737       | 1.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 591       | 1.35%   |
| Nvidia MCP61 Ethernet                                                   | 588       | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 586       | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 503       | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 454       | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 385       | 0.88%   |
| Huawei Modem/Networkcard                                                | 361       | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 325       | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 320       | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 317       | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 292       | 0.67%   |
| Ralink MT7601U Wireless Adapter                                         | 287       | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 287       | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 284       | 0.65%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 276       | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 272       | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 265       | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 261       | 0.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 259       | 0.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 255       | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 249       | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 239       | 0.54%   |
| Intel 82579V Gigabit Network Connection                                 | 231       | 0.53%   |
| Intel WiFi Link 5100                                                    | 222       | 0.51%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 210       | 0.48%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 196       | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                         | 194       | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 194       | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 177       | 0.4%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 173       | 0.39%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 171       | 0.39%   |
| Intel Wireless 7260                                                     | 165       | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                 | 163       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 5757      | 35.74%  |
| Intel                           | 3037      | 18.85%  |
| Realtek Semiconductor           | 2372      | 14.73%  |
| Broadcom                        | 1966      | 12.21%  |
| Ralink                          | 819       | 5.08%   |
| Ralink Technology               | 593       | 3.68%   |
| Broadcom Limited                | 376       | 2.33%   |
| Qualcomm Atheros Communications | 240       | 1.49%   |
| D-Link                          | 182       | 1.13%   |
| TP-Link                         | 175       | 1.09%   |
| ASUSTek Computer                | 148       | 0.92%   |
| D-Link System                   | 113       | 0.7%    |
| MediaTek                        | 74        | 0.46%   |
| NetGear                         | 45        | 0.28%   |
| IMC Networks                    | 22        | 0.14%   |
| Microsoft                       | 19        | 0.12%   |
| ZyXEL Communications            | 15        | 0.09%   |
| Edimax Technology               | 13        | 0.08%   |
| Belkin Components               | 12        | 0.07%   |
| Mercucys                        | 11        | 0.07%   |
| Sierra Wireless                 | 9         | 0.06%   |
| Linksys                         | 9         | 0.06%   |
| Marvell Technology Group        | 8         | 0.05%   |
| Dell                            | 8         | 0.05%   |
| ZyDAS                           | 7         | 0.04%   |
| Micro Star International        | 6         | 0.04%   |
| Gemtek                          | 6         | 0.04%   |
| Tenda                           | 5         | 0.03%   |
| Sitecom Europe                  | 5         | 0.03%   |
| Sagem                           | 5         | 0.03%   |
| Qualcomm                        | 5         | 0.03%   |
| Hewlett-Packard                 | 5         | 0.03%   |
| TRENDnet                        | 4         | 0.02%   |
| Fujitsu Siemens Computers       | 4         | 0.02%   |
| Accton Technology               | 4         | 0.02%   |
| Xiaomi                          | 3         | 0.02%   |
| VIA Technologies                | 3         | 0.02%   |
| Texas Instruments               | 3         | 0.02%   |
| BUFFALO                         | 3         | 0.02%   |
| AboCom Systems                  | 3         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2000      | 12.28%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1205      | 7.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 859       | 5.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 737       | 4.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 591       | 3.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 503       | 3.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 454       | 2.79%   |
| Broadcom BCM43142 802.11b/g/n                                           | 385       | 2.36%   |
| Ralink MT7601U Wireless Adapter                                         | 287       | 1.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 272       | 1.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 265       | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 255       | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 249       | 1.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 239       | 1.47%   |
| Intel WiFi Link 5100                                                    | 222       | 1.36%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 210       | 1.29%   |
| Qualcomm Atheros AR9271 802.11n                                         | 194       | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 194       | 1.19%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 173       | 1.06%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 171       | 1.05%   |
| Intel Wireless 7260                                                     | 165       | 1.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 162       | 0.99%   |
| Intel Centrino Wireless-N 130                                           | 159       | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 149       | 0.92%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 143       | 0.88%   |
| Intel Wireless 7265                                                     | 137       | 0.84%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 136       | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 136       | 0.84%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 135       | 0.83%   |
| Ralink RT5370 Wireless Adapter                                          | 131       | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 129       | 0.79%   |
| Intel Centrino Wireless-N 2230                                          | 126       | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 114       | 0.7%    |
| Intel Wireless 3165                                                     | 107       | 0.66%   |
| Intel WiMAX/WiFi Link 5150                                              | 101       | 0.62%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 99        | 0.61%   |
| Intel Centrino Wireless-N 100                                           | 95        | 0.58%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 92        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 88        | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 86        | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 15069     | 57.05%  |
| Qualcomm Atheros                       | 3306      | 12.52%  |
| Intel                                  | 2196      | 8.31%   |
| Nvidia                                 | 1244      | 4.71%   |
| Broadcom                               | 1204      | 4.56%   |
| Marvell Technology Group               | 1040      | 3.94%   |
| Broadcom Limited                       | 475       | 1.8%    |
| VIA Technologies                       | 308       | 1.17%   |
| JMicron Technology                     | 176       | 0.67%   |
| Attansic Technology                    | 153       | 0.58%   |
| Huawei Technologies                    | 152       | 0.58%   |
| Silicon Integrated Systems [SiS]       | 129       | 0.49%   |
| ZTE WCDMA Technologies MSM             | 123       | 0.47%   |
| D-Link System                          | 96        | 0.36%   |
| Samsung Electronics                    | 83        | 0.31%   |
| Xiaomi                                 | 73        | 0.28%   |
| Sundance Technology Inc / IC Plus      | 66        | 0.25%   |
| MediaTek                               | 66        | 0.25%   |
| HTC (High Tech Computer)               | 57        | 0.22%   |
| 3Com                                   | 46        | 0.17%   |
| Gemtek                                 | 42        | 0.16%   |
| ASIX Electronics                       | 26        | 0.1%    |
| Qualcomm                               | 23        | 0.09%   |
| T & A Mobile Phones                    | 20        | 0.08%   |
| ASUSTek Computer                       | 18        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 17        | 0.06%   |
| Vimtron Electronics                    | 16        | 0.06%   |
| GCT Semiconductor                      | 16        | 0.06%   |
| Spreadtrum Communications              | 15        | 0.06%   |
| Lenovo                                 | 15        | 0.06%   |
| NTmore                                 | 14        | 0.05%   |
| ICS Advent                             | 9         | 0.03%   |
| ULi Electronics                        | 8         | 0.03%   |
| Davicom Semiconductor                  | 8         | 0.03%   |
| D-Link                                 | 8         | 0.03%   |
| Motorola PCS                           | 7         | 0.03%   |
| ADMtek                                 | 7         | 0.03%   |
| OPPO Electronics                       | 6         | 0.02%   |
| LG Electronics                         | 6         | 0.02%   |
| Android                                | 6         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11180     | 41.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2867      | 10.72%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 861       | 3.22%   |
| Nvidia MCP61 Ethernet                                             | 588       | 2.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 586       | 2.19%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 325       | 1.21%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 320       | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 317       | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 292       | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 287       | 1.07%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 284       | 1.06%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 276       | 1.03%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 261       | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 259       | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 231       | 0.86%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 196       | 0.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 177       | 0.66%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 163       | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 160       | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 160       | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 157       | 0.59%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 153       | 0.57%   |
| Intel Ethernet Connection (2) I219-V                              | 150       | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 145       | 0.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 143       | 0.53%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 131       | 0.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 131       | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 122       | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 121       | 0.45%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 115       | 0.43%   |
| Nvidia MCP77 Ethernet                                             | 115       | 0.43%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 115       | 0.43%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 113       | 0.42%   |
| Nvidia CK804 Ethernet Controller                                  | 110       | 0.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 110       | 0.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 109       | 0.41%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 106       | 0.4%    |
| Intel I211 Gigabit Network Connection                             | 106       | 0.4%    |
| Nvidia MCP51 Ethernet Controller                                  | 104       | 0.39%   |
| Intel 82577LM Gigabit Network Connection                          | 96        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 24880     | 60.33%  |
| WiFi     | 15553     | 37.71%  |
| Modem    | 776       | 1.88%   |
| Unknown  | 34        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 13846     | 52.77%  |
| WiFi     | 12378     | 47.18%  |
| Unknown  | 10        | 0.04%   |
| Modem    | 4         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 13892     | 53.71%  |
| 1     | 11456     | 44.29%  |
| 0     | 332       | 1.28%   |
| 3     | 163       | 0.63%   |
| 4     | 19        | 0.07%   |
| 6     | 2         | 0.01%   |
| 33    | 1         | 0.004%  |
| 16    | 1         | 0.004%  |
| 11    | 1         | 0.004%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 18786     | 69.52%  |
| Unknown | 8003      | 29.62%  |
| Yes     | 234       | 0.87%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 1385      | 15.18%  |
| Intel                           | 1338      | 14.67%  |
| Broadcom                        | 1038      | 11.38%  |
| Realtek Semiconductor           | 851       | 9.33%   |
| Cambridge Silicon Radio         | 750       | 8.22%   |
| IMC Networks                    | 605       | 6.63%   |
| Foxconn / Hon Hai               | 585       | 6.41%   |
| Lite-On Technology              | 583       | 6.39%   |
| ASUSTek Computer                | 412       | 4.52%   |
| Ralink                          | 265       | 2.91%   |
| Toshiba                         | 232       | 2.54%   |
| Hewlett-Packard                 | 228       | 2.5%    |
| Dell                            | 194       | 2.13%   |
| Foxconn International           | 180       | 1.97%   |
| Apple                           | 115       | 1.26%   |
| Alps Electric                   | 74        | 0.81%   |
| Ralink Technology               | 61        | 0.67%   |
| Integrated System Solution      | 57        | 0.62%   |
| MediaTek                        | 26        | 0.29%   |
| Chicony Electronics             | 21        | 0.23%   |
| Micro Star International        | 18        | 0.2%    |
| Taiyo Yuden                     | 16        | 0.18%   |
| Askey Computer                  | 12        | 0.13%   |
| Realtek                         | 10        | 0.11%   |
| USI                             | 9         | 0.1%    |
| TP-Link                         | 9         | 0.1%    |
| Qcom                            | 9         | 0.1%    |
| Roper                           | 8         | 0.09%   |
| Conwise Technology              | 6         | 0.07%   |
| Syntek                          | 4         | 0.04%   |
| Logitech                        | 4         | 0.04%   |
| Samsung Electronics             | 3         | 0.03%   |
| Belkin Components               | 3         | 0.03%   |
| Opticis                         | 2         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.01%   |
| Qualcomm Atheros                | 1         | 0.01%   |
| Primax Electronics              | 1         | 0.01%   |
| Marvell Semiconductor           | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| D-Link                          | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 750       | 8.21%   |
| Intel Bluetooth wireless interface                                                  | 584       | 6.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 530       | 5.81%   |
| Realtek Bluetooth Radio                                                             | 465       | 5.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 346       | 3.79%   |
| Ralink RT3290 Bluetooth                                                             | 265       | 2.9%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 233       | 2.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 207       | 2.27%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 201       | 2.2%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 199       | 2.18%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 197       | 2.16%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 178       | 1.95%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 174       | 1.91%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 162       | 1.77%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 152       | 1.66%   |
| Broadcom BCM2045 Bluetooth                                                          | 147       | 1.61%   |
| Lite-On Bluetooth Device                                                            | 146       | 1.6%    |
| Realtek RTL8723B Bluetooth                                                          | 137       | 1.5%    |
| IMC Networks Bluetooth Device                                                       | 130       | 1.42%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 128       | 1.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 118       | 1.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 105       | 1.15%   |
| Qualcomm Atheros Bluetooth                                                          | 102       | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 99        | 1.08%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 97        | 1.06%   |
| Toshiba Integrated Bluetooth HCI                                                    | 92        | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 92        | 1.01%   |
| IMC Networks Bluetooth Radio                                                        | 87        | 0.95%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 86        | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 85        | 0.93%   |
| Broadcom HP Portable Valentine                                                      | 84        | 0.92%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 83        | 0.91%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 78        | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 76        | 0.83%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 72        | 0.79%   |
| IMC Networks Bluetooth Module                                                       | 71        | 0.78%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 71        | 0.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 67        | 0.73%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 67        | 0.73%   |
| Realtek RTL8723A Bluetooth                                                          | 66        | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 17829     | 51.53%  |
| AMD                                             | 7743      | 22.38%  |
| Nvidia                                          | 6823      | 19.72%  |
| C-Media Electronics                             | 584       | 1.69%   |
| Creative Labs                                   | 460       | 1.33%   |
| VIA Technologies                                | 214       | 0.62%   |
| Silicon Integrated Systems [SiS]                | 185       | 0.53%   |
| Creative Technology                             | 83        | 0.24%   |
| Logitech                                        | 68        | 0.2%    |
| JMTek                                           | 45        | 0.13%   |
| Texas Instruments                               | 43        | 0.12%   |
| Generalplus Technology                          | 36        | 0.1%    |
| Plantronics                                     | 26        | 0.08%   |
| Ensoniq                                         | 24        | 0.07%   |
| ASUSTek Computer                                | 20        | 0.06%   |
| Pixart Imaging                                  | 19        | 0.05%   |
| Tenx Technology                                 | 18        | 0.05%   |
| ULi Electronics                                 | 16        | 0.05%   |
| Razer USA                                       | 14        | 0.04%   |
| Kingston Technology                             | 11        | 0.03%   |
| Yamaha                                          | 10        | 0.03%   |
| Shenzhen Rapoo Technology                       | 10        | 0.03%   |
| M-Audio                                         | 10        | 0.03%   |
| Aureal Semiconductor                            | 10        | 0.03%   |
| A4Tech                                          | 10        | 0.03%   |
| iCreate Technologies                            | 9         | 0.03%   |
| ESS Technology                                  | 9         | 0.03%   |
| Asahi Kasei Microsystems                        | 9         | 0.03%   |
| XMOS                                            | 8         | 0.02%   |
| Guillemot                                       | 8         | 0.02%   |
| ATI Technologies                                | 8         | 0.02%   |
| Yealink Network Technology                      | 7         | 0.02%   |
| Samson Technologies                             | 7         | 0.02%   |
| Licensed by Sony Computer Entertainment America | 7         | 0.02%   |
| GYROCOM C&C                                     | 7         | 0.02%   |
| Focusrite-Novation                              | 7         | 0.02%   |
| Sony                                            | 6         | 0.02%   |
| Philips (or NXP)                                | 6         | 0.02%   |
| Fortemedia                                      | 6         | 0.02%   |
| EGO SYStems                                     | 6         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3151      | 7.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2888      | 7.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2670      | 6.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2629      | 6.59%   |
| AMD FCH Azalia Controller                                                                         | 1594      | 3.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1448      | 3.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1326      | 3.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1119      | 2.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 924       | 2.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 872       | 2.18%   |
| Nvidia High Definition Audio Controller                                                           | 778       | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 684       | 1.71%   |
| Nvidia MCP61 High Definition Audio                                                                | 642       | 1.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 605       | 1.52%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 561       | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 456       | 1.14%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 449       | 1.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 446       | 1.12%   |
| Intel 8 Series HD Audio Controller                                                                | 446       | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 444       | 1.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 444       | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 443       | 1.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 417       | 1.04%   |
| AMD Wrestler HDMI Audio                                                                           | 400       | 1%      |
| AMD Trinity HDMI Audio Controller                                                                 | 400       | 1%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 391       | 0.98%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 366       | 0.92%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 343       | 0.86%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 334       | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 331       | 0.83%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 311       | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 297       | 0.74%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 296       | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 288       | 0.72%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 280       | 0.7%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 252       | 0.63%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 251       | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 245       | 0.61%   |
| Intel 200 Series PCH HD Audio                                                                     | 226       | 0.57%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 222       | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 9263      | 32.44%  |
| Samsung Electronics   | 3992      | 13.98%  |
| Kingston              | 3865      | 13.53%  |
| SK hynix              | 3293      | 11.53%  |
| Micron Technology     | 1157      | 4.05%   |
| Crucial               | 943       | 3.3%    |
| Elpida                | 802       | 2.81%   |
| Nanya Technology      | 735       | 2.57%   |
| Corsair               | 657       | 2.3%    |
| Ramaxel Technology    | 524       | 1.83%   |
| A-DATA Technology     | 506       | 1.77%   |
| AMD                   | 301       | 1.05%   |
| Patriot               | 275       | 0.96%   |
| ASint Technology      | 179       | 0.63%   |
| Goodram               | 160       | 0.56%   |
| Goldkey               | 158       | 0.55%   |
| Transcend             | 138       | 0.48%   |
| 48spaces              | 125       | 0.44%   |
| Silicon Power         | 110       | 0.39%   |
| G.Skill               | 99        | 0.35%   |
| Kingmax               | 98        | 0.34%   |
| Apacer                | 80        | 0.28%   |
| Qimonda               | 79        | 0.28%   |
| Qumo                  | 78        | 0.27%   |
| SHARETRONIC           | 77        | 0.27%   |
| Unifosa               | 71        | 0.25%   |
| Team                  | 68        | 0.24%   |
| GeIL                  | 62        | 0.22%   |
| Unknown (ABCD)        | 59        | 0.21%   |
| Foxline               | 52        | 0.18%   |
| Kllisre               | 49        | 0.17%   |
| Unknown               | 43        | 0.15%   |
| Toshiba               | 31        | 0.11%   |
| KETECH                | 30        | 0.11%   |
| Ramos Technology      | 19        | 0.07%   |
| Atermiter             | 19        | 0.07%   |
| Smart                 | 18        | 0.06%   |
| TakeMS                | 17        | 0.06%   |
| Kingmax Semiconductor | 17        | 0.06%   |
| Hexon                 | 14        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                               | 486       | 1.5%    |
| Unknown RAM Module 2048MB DIMM SDRAM                                      | 473       | 1.46%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                    | 443       | 1.37%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                      | 415       | 1.28%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                   | 371       | 1.14%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                   | 350       | 1.08%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                               | 324       | 1%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 314       | 0.97%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                                    | 250       | 0.77%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                               | 248       | 0.76%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 225       | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 222       | 0.68%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 208       | 0.64%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                               | 206       | 0.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 201       | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 200       | 0.62%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 193       | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 192       | 0.59%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 186       | 0.57%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 177       | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 171       | 0.53%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                                    | 164       | 0.51%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                    | 162       | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                              | 160       | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 160       | 0.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 157       | 0.48%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                                    | 146       | 0.45%   |
| Unknown RAM Module 512MB DIMM SDRAM                                       | 144       | 0.44%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 140       | 0.43%   |
| Unknown RAM Module 1024MB DIMM                                            | 138       | 0.43%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                     | 133       | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                   | 132       | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 132       | 0.41%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 131       | 0.4%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 125       | 0.39%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                       | 124       | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                              | 123       | 0.38%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                     | 120       | 0.37%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 117       | 0.36%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 110       | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 12293     | 48.83%  |
| DDR2    | 3935      | 15.63%  |
| Unknown | 3093      | 12.29%  |
| SDRAM   | 2406      | 9.56%   |
| DDR4    | 2334      | 9.27%   |
| DDR     | 736       | 2.92%   |
| DRAM    | 199       | 0.79%   |
| LPDDR4  | 131       | 0.52%   |
| LPDDR3  | 33        | 0.13%   |
| DDR5    | 5         | 0.02%   |
| LPDDR5  | 3         | 0.01%   |
| EEPROM  | 3         | 0.01%   |
| SRAM    | 1         | 0.004%  |
| RAM     | 1         | 0.004%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 12599     | 51.33%  |
| SODIMM       | 11824     | 48.17%  |
| Row Of Chips | 80        | 0.33%   |
| Chip         | 25        | 0.1%    |
| FB-DIMM      | 10        | 0.04%   |
| Unknown      | 7         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 10030     | 34.41%  |
| 2048    | 9695      | 33.26%  |
| 1024    | 4520      | 15.51%  |
| 8192    | 3339      | 11.46%  |
| 512     | 957       | 3.28%   |
| 16384   | 316       | 1.08%   |
| 256     | 198       | 0.68%   |
| 32768   | 62        | 0.21%   |
| Unknown | 10        | 0.03%   |
| 128     | 6         | 0.02%   |
| 32      | 4         | 0.01%   |
| 1536    | 3         | 0.01%   |
| 16      | 3         | 0.01%   |
| 1       | 3         | 0.01%   |
| 32767   | 1         | 0.003%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 6978      | 25.34%  |
| 1333    | 3749      | 13.61%  |
| Unknown | 2573      | 9.34%   |
| 800     | 2331      | 8.47%   |
| 667     | 2232      | 8.11%   |
| 1334    | 2092      | 7.6%    |
| 2400    | 805       | 2.92%   |
| 2667    | 692       | 2.51%   |
| 1067    | 544       | 1.98%   |
| 2133    | 514       | 1.87%   |
| 400     | 510       | 1.85%   |
| 533     | 496       | 1.8%    |
| 4199    | 471       | 1.71%   |
| 1066    | 421       | 1.53%   |
| 3200    | 417       | 1.51%   |
| 1867    | 353       | 1.28%   |
| 333     | 306       | 1.11%   |
| 2048    | 256       | 0.93%   |
| 1866    | 182       | 0.66%   |
| 975     | 125       | 0.45%   |
| 3600    | 109       | 0.4%    |
| 3400    | 109       | 0.4%    |
| 266     | 109       | 0.4%    |
| 1800    | 103       | 0.37%   |
| 3266    | 96        | 0.35%   |
| 2933    | 77        | 0.28%   |
| 1639    | 74        | 0.27%   |
| 2666    | 51        | 0.19%   |
| 3466    | 49        | 0.18%   |
| 66      | 49        | 0.18%   |
| 3000    | 48        | 0.17%   |
| 2000    | 42        | 0.15%   |
| 1648    | 37        | 0.13%   |
| 2800    | 35        | 0.13%   |
| 1400    | 35        | 0.13%   |
| 200     | 32        | 0.12%   |
| 2134    | 31        | 0.11%   |
| 49926   | 25        | 0.09%   |
| 2866    | 25        | 0.09%   |
| 3333    | 24        | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 511       | 30.73%  |
| Canon                           | 386       | 23.21%  |
| Samsung Electronics             | 282       | 16.96%  |
| Seiko Epson                     | 165       | 9.92%   |
| Brother Industries              | 109       | 6.55%   |
| Xerox                           | 49        | 2.95%   |
| Panasonic (Matsushita)          | 38        | 2.29%   |
| Kyocera                         | 25        | 1.5%    |
| Pantum                          | 24        | 1.44%   |
| Ricoh                           | 20        | 1.2%    |
| Prolific Technology             | 13        | 0.78%   |
| QinHeng Electronics             | 8         | 0.48%   |
| Lexmark International           | 8         | 0.48%   |
| TSC Auto ID Technology          | 4         | 0.24%   |
| WinChipHead                     | 3         | 0.18%   |
| STMicroelectronics              | 2         | 0.12%   |
| Sharp                           | 2         | 0.12%   |
| cab Produkttechnik GmbH & Co KG | 2         | 0.12%   |
| Yurex                           | 1         | 0.06%   |
| Xiaomi                          | 1         | 0.06%   |
| Toshiba TEC                     | 1         | 0.06%   |
| Samsung Info. Systems America   | 1         | 0.06%   |
| NXP Semiconductors              | 1         | 0.06%   |
| Konica Minolta                  | 1         | 0.06%   |
| KODAK                           | 1         | 0.06%   |
| Fuji Xerox                      | 1         | 0.06%   |
| Dell                            | 1         | 0.06%   |
| Custom Engineering SPA          | 1         | 0.06%   |
| ATEN International              | 1         | 0.06%   |
| Apple                           | 1         | 0.06%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet 1020                      | 58        | 3.42%   |
| HP LaserJet 1018                      | 48        | 2.83%   |
| HP LaserJet P1102                     | 44        | 2.59%   |
| Samsung SCX-4200 series               | 43        | 2.53%   |
| Canon LBP2900                         | 38        | 2.24%   |
| Seiko Epson Printer                   | 34        | 2%      |
| Panasonic (Matsushita) KX-MB1500RU    | 25        | 1.47%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 24        | 1.41%   |
| Samsung SCX-3400 Series               | 24        | 1.41%   |
| HP LaserJet 1010                      | 24        | 1.41%   |
| Samsung SCX-3200 Series               | 23        | 1.36%   |
| Canon MF4410                          | 23        | 1.36%   |
| Canon MF3010                          | 23        | 1.36%   |
| HP LaserJet P1005                     | 22        | 1.3%    |
| Seiko Epson L210 Series               | 18        | 1.06%   |
| Samsung ML-1640 Series Laser Printer  | 17        | 1%      |
| Canon LBP3010/LBP3018/LBP3050         | 16        | 0.94%   |
| Samsung ML-1210 Printer               | 15        | 0.88%   |
| Canon MF4010 series                   | 15        | 0.88%   |
| Canon LBP6000                         | 15        | 0.88%   |
| HP Deskjet 2050 J510                  | 14        | 0.82%   |
| Canon PIXMA MG2500 Series             | 14        | 0.82%   |
| Canon LaserShot LBP-1120 Printer      | 14        | 0.82%   |
| Samsung M2070 Series                  | 13        | 0.77%   |
| Prolific PL2305 Parallel Port         | 13        | 0.77%   |
| Canon LBP810                          | 13        | 0.77%   |
| Canon iP7200 series                   | 13        | 0.77%   |
| Brother HL-2030 Laser Printer         | 13        | 0.77%   |
| Xerox Phaser 3140 and 3155            | 12        | 0.71%   |
| Samsung ML-2010P Mono Laser Printer   | 12        | 0.71%   |
| HP LaserJet 1200                      | 12        | 0.71%   |
| Canon MG2400 series                   | 12        | 0.71%   |
| Brother HL-1110 series                | 12        | 0.71%   |
| Brother DCP-7057 scanner/printer      | 12        | 0.71%   |
| HP LaserJet 1320                      | 11        | 0.65%   |
| HP LaserJet 1000                      | 11        | 0.65%   |
| HP DeskJet 2130 series                | 11        | 0.65%   |
| Canon LBP6020                         | 11        | 0.65%   |
| Samsung SCX-4100 Scanner              | 10        | 0.59%   |
| Samsung M2020 Series                  | 10        | 0.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 172       | 36.21%  |
| Seiko Epson                 | 114       | 24%     |
| Hewlett-Packard             | 82        | 17.26%  |
| Mustek Systems              | 49        | 10.32%  |
| Acer Peripherals (now BenQ) | 19        | 4%      |
| Ultima Electronics          | 18        | 3.79%   |
| KYE Systems (Mouse Systems) | 7         | 1.47%   |
| Fujitsu                     | 4         | 0.84%   |
| Microtek International      | 2         | 0.42%   |
| Avision                     | 2         | 0.42%   |
| AGFA-Gevaert NV             | 2         | 0.42%   |
| Visioneer                   | 1         | 0.21%   |
| Plustek                     | 1         | 0.21%   |
| Papillon Systems            | 1         | 0.21%   |
| Canon Electronics           | 1         | 0.21%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                                                | 31        | 6.51%   |
| HP ScanJet 2400c                                                                      | 26        | 5.46%   |
| Canon CanoScan LiDE 110                                                               | 26        | 5.46%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 21        | 4.41%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 18        | 3.78%   |
| Canon CanoScan LiDE 120                                                               | 18        | 3.78%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 17        | 3.57%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 16        | 3.36%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 15        | 3.15%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 14        | 2.94%   |
| Canon CanoScan LiDE 210                                                               | 12        | 2.52%   |
| Canon CanoScan LiDE 60                                                                | 11        | 2.31%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 10        | 2.1%    |
| Canon CanoScan LiDE 100                                                               | 10        | 2.1%    |
| Canon CanoScan LiDE 220                                                               | 9         | 1.89%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 8         | 1.68%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 8         | 1.68%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 7         | 1.47%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 7         | 1.47%   |
| Seiko Epson Perfection 660                                                            | 6         | 1.26%   |
| Mustek Systems SNAPSCAN e22                                                           | 6         | 1.26%   |
| Canon CanoScan                                                                        | 6         | 1.26%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 5         | 1.05%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 5         | 1.05%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 4         | 0.84%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 4         | 0.84%   |
| HP ScanJet 3800c                                                                      | 4         | 0.84%   |
| HP Scanjet 200                                                                        | 4         | 0.84%   |
| Canon CanoScan LiDE 70                                                                | 4         | 0.84%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 4         | 0.84%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 3         | 0.63%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 3         | 0.63%   |
| HP ScanJet G3010                                                                      | 3         | 0.63%   |
| HP ScanJet 3970c                                                                      | 3         | 0.63%   |
| HP ScanJet 3770                                                                       | 3         | 0.63%   |
| HP ScanJet 3500c                                                                      | 3         | 0.63%   |
| HP ScanJet 2200c                                                                      | 3         | 0.63%   |
| HP PSC 1200                                                                           | 3         | 0.63%   |
| Fujitsu ScanSnap SV600                                                                | 3         | 0.63%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 3         | 0.63%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2970      | 21.5%   |
| Logitech                               | 1083      | 7.84%   |
| Suyin                                  | 944       | 6.83%   |
| Acer                                   | 921       | 6.67%   |
| IMC Networks                           | 875       | 6.33%   |
| Z-Star Microelectronics                | 842       | 6.09%   |
| Microdia                               | 817       | 5.91%   |
| Realtek Semiconductor                  | 740       | 5.36%   |
| Silicon Motion                         | 594       | 4.3%    |
| Sunplus Innovation Technology          | 575       | 4.16%   |
| Alcor Micro                            | 373       | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 335       | 2.42%   |
| Syntek                                 | 323       | 2.34%   |
| Quanta                                 | 174       | 1.26%   |
| Microsoft                              | 167       | 1.21%   |
| ALi                                    | 165       | 1.19%   |
| Ricoh                                  | 156       | 1.13%   |
| Apple                                  | 137       | 0.99%   |
| KYE Systems (Mouse Systems)            | 127       | 0.92%   |
| DigiTech                               | 125       | 0.9%    |
| Cubeternet                             | 107       | 0.77%   |
| Pixart Imaging                         | 106       | 0.77%   |
| Arkmicro Technologies                  | 103       | 0.75%   |
| Aveo Technology                        | 98        | 0.71%   |
| Bison Electronics                      | 93        | 0.67%   |
| GEMBIRD                                | 90        | 0.65%   |
| Samsung Electronics                    | 81        | 0.59%   |
| Lenovo                                 | 68        | 0.49%   |
| Lite-On Technology                     | 63        | 0.46%   |
| Importek                               | 54        | 0.39%   |
| Primax Electronics                     | 46        | 0.33%   |
| Creative Technology                    | 40        | 0.29%   |
| Genesys Logic                          | 32        | 0.23%   |
| OmniVision Technologies                | 26        | 0.19%   |
| Sunplus Technology                     | 23        | 0.17%   |
| Nokia Mobile Phones                    | 21        | 0.15%   |
| Luxvisions Innotech Limited            | 21        | 0.15%   |
| Guillemot                              | 21        | 0.15%   |
| Image Processor                        | 18        | 0.13%   |
| Philips (or NXP)                       | 17        | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Logitech Webcam C270                     | 364       | 2.63%   |
| Chicony HD WebCam                        | 304       | 2.2%    |
| Z-Star Venus USB2.0 Camera               | 283       | 2.05%   |
| Chicony Lenovo EasyCamera                | 274       | 1.98%   |
| Acer Lenovo Integrated Webcam            | 270       | 1.95%   |
| IMC Networks UVC VGA Webcam              | 205       | 1.48%   |
| Sunplus HD WebCam                        | 199       | 1.44%   |
| Chicony USB 2.0 Camera                   | 196       | 1.42%   |
| Acer Lenovo EasyCamera                   | 194       | 1.4%    |
| Z-Star A4 TECH USB2.0 PC Camera J        | 165       | 1.19%   |
| Chicony USB2.0 HD UVC WebCam             | 161       | 1.16%   |
| Acer BisonCam, NB Pro                    | 151       | 1.09%   |
| Microdia Camera                          | 150       | 1.08%   |
| Chicony Integrated Camera                | 126       | 0.91%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 120       | 0.87%   |
| Microdia Sonix USB 2.0 Camera            | 120       | 0.87%   |
| Realtek Lenovo EasyCamera                | 119       | 0.86%   |
| Z-Star Vimicro USB Camera (Altair)       | 116       | 0.84%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 114       | 0.82%   |
| Silicon Motion WebCam SC-0311139N        | 113       | 0.82%   |
| Syntek Lenovo EasyCamera                 | 112       | 0.81%   |
| ALi Gateway Webcam                       | 112       | 0.81%   |
| IMC Networks Integrated Webcam           | 110       | 0.8%    |
| Alcor Micro Asus Integrated Webcam       | 109       | 0.79%   |
| DigiTech USB 2.0 PC Camera               | 104       | 0.75%   |
| Realtek USB Camera                       | 100       | 0.72%   |
| Chicony USB2.0 VGA UVC WebCam            | 98        | 0.71%   |
| Suyin 1.3M HD WebCam                     | 96        | 0.69%   |
| Sunplus Asus Webcam                      | 94        | 0.68%   |
| Arkmicro USB2.0 PC CAMERA                | 93        | 0.67%   |
| Chicony HP Truevision HD                 | 92        | 0.66%   |
| Logitech Webcam C170                     | 89        | 0.64%   |
| Chicony USB2.0 0.3M UVC WebCam           | 86        | 0.62%   |
| Logitech Webcam C310                     | 85        | 0.61%   |
| Logitech Webcam C210                     | 84        | 0.61%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 83        | 0.6%    |
| Chicony HP Webcam                        | 83        | 0.6%    |
| Chicony 1.3M Webcam                      | 81        | 0.59%   |
| Suyin Acer CrystalEye Webcam             | 80        | 0.58%   |
| IMC Networks USB2.0 UVC HD Webcam        | 80        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 427       | 42.79%  |
| AuthenTec                  | 226       | 22.65%  |
| Upek                       | 157       | 15.73%  |
| STMicroelectronics         | 74        | 7.41%   |
| LighTuning Technology      | 64        | 6.41%   |
| Synaptics                  | 15        | 1.5%    |
| Shenzhen Goodix Technology | 15        | 1.5%    |
| Elan Microelectronics      | 15        | 1.5%    |
| Microsoft                  | 2         | 0.2%    |
| Focal-systems.Corp         | 2         | 0.2%    |
| DigitalPersona             | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 140       | 14.03%  |
| Validity Sensors Fingerprint scanner                                       | 114       | 11.42%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 87        | 8.72%   |
| STMicroelectronics Fingerprint Reader                                      | 74        | 7.41%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 74        | 7.41%   |
| AuthenTec AES1600                                                          | 63        | 6.31%   |
| AuthenTec AES2810                                                          | 55        | 5.51%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 4.51%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 40        | 4.01%   |
| LighTuning Fingerprint Reader                                              | 40        | 4.01%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 31        | 3.11%   |
| Validity Sensors VFS491                                                    | 26        | 2.61%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 2.51%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 24        | 2.4%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 19        | 1.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 18        | 1.8%    |
| Upek TCS5B Fingerprint sensor                                              | 17        | 1.7%    |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 1.3%    |
| Elan ELAN:Fingerprint                                                      | 13        | 1.3%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 0.8%    |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.7%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.7%    |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.6%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 0.6%    |
| Validity Sensors Synaptics WBDI                                            | 4         | 0.4%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.3%    |
| Synaptics  WBDI                                                            | 3         | 0.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 0.3%    |
| Synaptics UWP WBDI                                                         | 2         | 0.2%    |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 0.2%    |
| Microsoft Fingerprint Reader                                               | 2         | 0.2%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.1%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.1%    |
| Synaptics WBDI                                                             | 1         | 0.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.1%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 0.1%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Broadcom                                | 102       | 33.01%  |
| O2 Micro                                | 52        | 16.83%  |
| Alcor Micro                             | 35        | 11.33%  |
| Upek                                    | 27        | 8.74%   |
| Lenovo                                  | 27        | 8.74%   |
| Aladdin Knowledge Systems               | 14        | 4.53%   |
| Advanced Card Systems                   | 11        | 3.56%   |
| OmniKey                                 | 8         | 2.59%   |
| Aktiv                                   | 8         | 2.59%   |
| Realtek Semiconductor                   | 5         | 1.62%   |
| Gemalto (was Gemplus)                   | 5         | 1.62%   |
| Athena Smartcard Solutions              | 4         | 1.29%   |
| Aladdin R.D.                            | 3         | 0.97%   |
| Castles Technology                      | 2         | 0.65%   |
| Reiner SCT Kartensysteme                | 1         | 0.32%   |
| In Focus Systems                        | 1         | 0.32%   |
| Future Technology Devices International | 1         | 0.32%   |
| Cherry                                  | 1         | 0.32%   |
| BIFIT                                   | 1         | 0.32%   |
| Avtor                                   | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 67        | 21.68%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 36        | 11.65%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 27        | 8.74%   |
| Lenovo Integrated Smart Card Reader                                          | 27        | 8.74%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 8.74%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 26        | 8.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 16        | 5.18%   |
| Aladdin Knowledge Systems Token JC                                           | 14        | 4.53%   |
| Alcor Micro Watchdata W 1981                                                 | 8         | 2.59%   |
| Broadcom 5880                                                                | 7         | 2.27%   |
| Aktiv Rutoken lite                                                           | 7         | 2.27%   |
| OmniKey CardMan 1021                                                         | 6         | 1.94%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 1.62%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 1.29%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.29%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.97%   |
| Aladdin R.D. JaCarta                                                         | 3         | 0.97%   |
| Advanced Card Systems Token USB 64K                                          | 3         | 0.97%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.65%   |
| Castles Technology EZCCID Smart Card Reader                                  | 2         | 0.65%   |
| Broadcom 58200                                                               | 2         | 0.65%   |
| Advanced Card Systems ACR3901U                                               | 2         | 0.65%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.32%   |
| OmniKey CardMan 4321                                                         | 1         | 0.32%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.32%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.32%   |
| Future Technology Devices International Parsec Desktop Reader PR-EH08        | 1         | 0.32%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.32%   |
| BIFIT iBank2Key                                                              | 1         | 0.32%   |
| Avtor SecureToken                                                            | 1         | 0.32%   |
| Aktiv KAZTOKEN                                                               | 1         | 0.32%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.32%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 20835     | 77.86%  |
| 1     | 4917      | 18.37%  |
| 2     | 875       | 3.27%   |
| 3     | 106       | 0.4%    |
| 4     | 22        | 0.08%   |
| 5     | 3         | 0.01%   |
| 9     | 1         | 0.004%  |
| 7     | 1         | 0.004%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3282      | 50.38%  |
| Fingerprint reader       | 996       | 15.29%  |
| Net/wireless             | 522       | 8.01%   |
| Bluetooth                | 354       | 5.43%   |
| Chipcard                 | 292       | 4.48%   |
| Communication controller | 239       | 3.67%   |
| Multimedia controller    | 235       | 3.61%   |
| Camera                   | 139       | 2.13%   |
| Storage                  | 124       | 1.9%    |
| Flash memory             | 98        | 1.5%    |
| Unassigned class         | 65        | 1%      |
| Sound                    | 36        | 0.55%   |
| Modem                    | 30        | 0.46%   |
| Dvb card                 | 26        | 0.4%    |
| Card reader              | 26        | 0.4%    |
| Net/ethernet             | 15        | 0.23%   |
| Network                  | 13        | 0.2%    |
| Tv card                  | 6         | 0.09%   |
| Video                    | 5         | 0.08%   |
| Storage/raid             | 5         | 0.08%   |
| Storage/ata              | 4         | 0.06%   |
| Wireless                 | 1         | 0.02%   |
| Storage/ide              | 1         | 0.02%   |

