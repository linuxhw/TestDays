Fedora 38 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 38.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_38/Desktop/README.md) and [notebooks](/Dist/Fedora_38/Notebook/README.md).

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

Total: 2839

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V5-531               | Notebook    | [e39cb4e3e6](https://linux-hardware.org/?probe=e39cb4e3e6) | Sep 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [69fc5aab82](https://linux-hardware.org/?probe=69fc5aab82) | Sep 07, 2023 |
| Lenovo        | V580c 20160                 | Notebook    | [87f8bad27d](https://linux-hardware.org/?probe=87f8bad27d) | Sep 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [384d2074ad](https://linux-hardware.org/?probe=384d2074ad) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [8a05090057](https://linux-hardware.org/?probe=8a05090057) | Sep 07, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [a2fab791b4](https://linux-hardware.org/?probe=a2fab791b4) | Sep 07, 2023 |
| Timi          | Redmi Book Pro 14S          | Notebook    | [b2776d8282](https://linux-hardware.org/?probe=b2776d8282) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [24eca3030c](https://linux-hardware.org/?probe=24eca3030c) | Sep 07, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [250bc7b8ea](https://linux-hardware.org/?probe=250bc7b8ea) | Sep 07, 2023 |
| NZXT          | N7 Z370                     | Desktop     | [34a23bdc5f](https://linux-hardware.org/?probe=34a23bdc5f) | Sep 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9911fc5254](https://linux-hardware.org/?probe=9911fc5254) | Sep 07, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [e7d12d040e](https://linux-hardware.org/?probe=e7d12d040e) | Sep 07, 2023 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [2592f883ef](https://linux-hardware.org/?probe=2592f883ef) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b982251e82](https://linux-hardware.org/?probe=b982251e82) | Sep 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [0434d08b59](https://linux-hardware.org/?probe=0434d08b59) | Sep 07, 2023 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [67e211cb5d](https://linux-hardware.org/?probe=67e211cb5d) | Sep 07, 2023 |
| Dell          | Latitude E6500              | Notebook    | [b4b035c4f7](https://linux-hardware.org/?probe=b4b035c4f7) | Sep 07, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [f0c3188082](https://linux-hardware.org/?probe=f0c3188082) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [3c6e29c3c3](https://linux-hardware.org/?probe=3c6e29c3c3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b17a5edce5](https://linux-hardware.org/?probe=b17a5edce5) | Sep 06, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [b6a521128f](https://linux-hardware.org/?probe=b6a521128f) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f59dbec9af](https://linux-hardware.org/?probe=f59dbec9af) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [83c77f6733](https://linux-hardware.org/?probe=83c77f6733) | Sep 06, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [40b17904fa](https://linux-hardware.org/?probe=40b17904fa) | Sep 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c8ee0a00a5](https://linux-hardware.org/?probe=c8ee0a00a5) | Sep 06, 2023 |
| HP            | 3047h                       | Desktop     | [9b6ecf8471](https://linux-hardware.org/?probe=9b6ecf8471) | Sep 06, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [7e81f7531b](https://linux-hardware.org/?probe=7e81f7531b) | Sep 06, 2023 |
| HP            | 3047h                       | Desktop     | [51ba95dc5a](https://linux-hardware.org/?probe=51ba95dc5a) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [c9a07c44d5](https://linux-hardware.org/?probe=c9a07c44d5) | Sep 06, 2023 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [9dd5c2a861](https://linux-hardware.org/?probe=9dd5c2a861) | Sep 06, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [1756563167](https://linux-hardware.org/?probe=1756563167) | Sep 06, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [ce6860153d](https://linux-hardware.org/?probe=ce6860153d) | Sep 06, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | Notebook    | [f946665a24](https://linux-hardware.org/?probe=f946665a24) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [b5f142ae13](https://linux-hardware.org/?probe=b5f142ae13) | Sep 06, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [145414b8e3](https://linux-hardware.org/?probe=145414b8e3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7b99e058ff](https://linux-hardware.org/?probe=7b99e058ff) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [d6b6455af2](https://linux-hardware.org/?probe=d6b6455af2) | Sep 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [7db6779b5c](https://linux-hardware.org/?probe=7db6779b5c) | Sep 06, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [c31e15f2ba](https://linux-hardware.org/?probe=c31e15f2ba) | Sep 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [9614656d9b](https://linux-hardware.org/?probe=9614656d9b) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [25ec8e4a16](https://linux-hardware.org/?probe=25ec8e4a16) | Sep 05, 2023 |
| Dell          | Latitude 7400               | Notebook    | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [bb7f6aed1a](https://linux-hardware.org/?probe=bb7f6aed1a) | Sep 05, 2023 |
| ASUSTek       | E402SA                      | Notebook    | [efad2958a0](https://linux-hardware.org/?probe=efad2958a0) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [3c55d4d55b](https://linux-hardware.org/?probe=3c55d4d55b) | Sep 05, 2023 |
| HP            | 82E0                        | Desktop     | [a86ac881df](https://linux-hardware.org/?probe=a86ac881df) | Sep 05, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [0309bcca29](https://linux-hardware.org/?probe=0309bcca29) | Sep 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [c03e42edee](https://linux-hardware.org/?probe=c03e42edee) | Sep 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [9b4d95cf35](https://linux-hardware.org/?probe=9b4d95cf35) | Sep 05, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [5dbf7515d1](https://linux-hardware.org/?probe=5dbf7515d1) | Sep 05, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [7619d8e5e8](https://linux-hardware.org/?probe=7619d8e5e8) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0fa982f7ad](https://linux-hardware.org/?probe=0fa982f7ad) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [9ab25d4913](https://linux-hardware.org/?probe=9ab25d4913) | Sep 05, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [ea1d0861a1](https://linux-hardware.org/?probe=ea1d0861a1) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [229ca6e8cb](https://linux-hardware.org/?probe=229ca6e8cb) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [ab9c556dc7](https://linux-hardware.org/?probe=ab9c556dc7) | Sep 05, 2023 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [05ad9c1b7b](https://linux-hardware.org/?probe=05ad9c1b7b) | Sep 05, 2023 |
| Acer          | Aspire 4738Z                | Notebook    | [88b34596c0](https://linux-hardware.org/?probe=88b34596c0) | Sep 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [3e2b7d52c5](https://linux-hardware.org/?probe=3e2b7d52c5) | Sep 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c06fdd0648](https://linux-hardware.org/?probe=c06fdd0648) | Sep 05, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [5154be8883](https://linux-hardware.org/?probe=5154be8883) | Sep 05, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [d20cf2e835](https://linux-hardware.org/?probe=d20cf2e835) | Sep 05, 2023 |
| Dell          | G15 5530                    | Notebook    | [91dcc569ee](https://linux-hardware.org/?probe=91dcc569ee) | Sep 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bf7eead9e6](https://linux-hardware.org/?probe=bf7eead9e6) | Sep 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d3cde5f4c5](https://linux-hardware.org/?probe=d3cde5f4c5) | Sep 04, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [5585353638](https://linux-hardware.org/?probe=5585353638) | Sep 04, 2023 |
| ASUSTek       | X99-M WS                    | Desktop     | [f324b3dd33](https://linux-hardware.org/?probe=f324b3dd33) | Sep 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [2a53f8dc55](https://linux-hardware.org/?probe=2a53f8dc55) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d99ec42689](https://linux-hardware.org/?probe=d99ec42689) | Sep 04, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [5139d104cc](https://linux-hardware.org/?probe=5139d104cc) | Sep 04, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [032fca9d1d](https://linux-hardware.org/?probe=032fca9d1d) | Sep 04, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [59b20fdfab](https://linux-hardware.org/?probe=59b20fdfab) | Sep 04, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [3a5b200954](https://linux-hardware.org/?probe=3a5b200954) | Sep 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [da42098f81](https://linux-hardware.org/?probe=da42098f81) | Sep 04, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [94e7b43fe2](https://linux-hardware.org/?probe=94e7b43fe2) | Sep 04, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [fff758a5d9](https://linux-hardware.org/?probe=fff758a5d9) | Sep 04, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [80a94d69c2](https://linux-hardware.org/?probe=80a94d69c2) | Sep 04, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [cfdc48e9f6](https://linux-hardware.org/?probe=cfdc48e9f6) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| Dell          | Latitude 5285               | Notebook    | [9ddc47c6a9](https://linux-hardware.org/?probe=9ddc47c6a9) | Sep 04, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [7189994067](https://linux-hardware.org/?probe=7189994067) | Sep 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [6bf9db20f8](https://linux-hardware.org/?probe=6bf9db20f8) | Sep 04, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [29e55d4d72](https://linux-hardware.org/?probe=29e55d4d72) | Sep 04, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [7e0c89dfdb](https://linux-hardware.org/?probe=7e0c89dfdb) | Sep 04, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [18d1abc9ca](https://linux-hardware.org/?probe=18d1abc9ca) | Sep 04, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [a28608cf93](https://linux-hardware.org/?probe=a28608cf93) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2252b35243](https://linux-hardware.org/?probe=2252b35243) | Sep 03, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [c3e4035d47](https://linux-hardware.org/?probe=c3e4035d47) | Sep 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1211fca3e2](https://linux-hardware.org/?probe=1211fca3e2) | Sep 03, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [89d5a9b606](https://linux-hardware.org/?probe=89d5a9b606) | Sep 03, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | Notebook    | [20be702d65](https://linux-hardware.org/?probe=20be702d65) | Sep 03, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [733f5cb987](https://linux-hardware.org/?probe=733f5cb987) | Sep 03, 2023 |
| Framework     | Laptop                      | Notebook    | [d153316fdd](https://linux-hardware.org/?probe=d153316fdd) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [dd19cc0d48](https://linux-hardware.org/?probe=dd19cc0d48) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [fc0731667e](https://linux-hardware.org/?probe=fc0731667e) | Sep 03, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [5e3f2f01d4](https://linux-hardware.org/?probe=5e3f2f01d4) | Sep 03, 2023 |
| Dell          | Latitude 3540               | Notebook    | [e7d1d4f160](https://linux-hardware.org/?probe=e7d1d4f160) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [926751fb6e](https://linux-hardware.org/?probe=926751fb6e) | Sep 03, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [60d302fc0f](https://linux-hardware.org/?probe=60d302fc0f) | Sep 03, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [720b306ad4](https://linux-hardware.org/?probe=720b306ad4) | Sep 03, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [3593994f4e](https://linux-hardware.org/?probe=3593994f4e) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e0f8242693](https://linux-hardware.org/?probe=e0f8242693) | Sep 02, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [9ae746229d](https://linux-hardware.org/?probe=9ae746229d) | Sep 02, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [8f29742c47](https://linux-hardware.org/?probe=8f29742c47) | Sep 02, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [69ccd7d6f2](https://linux-hardware.org/?probe=69ccd7d6f2) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | Desktop     | [c4c911d725](https://linux-hardware.org/?probe=c4c911d725) | Sep 02, 2023 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | Desktop     | [bc7e99e576](https://linux-hardware.org/?probe=bc7e99e576) | Sep 02, 2023 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [e6c5ae208f](https://linux-hardware.org/?probe=e6c5ae208f) | Sep 02, 2023 |
| Dell          | Latitude 5400               | Notebook    | [aac8791780](https://linux-hardware.org/?probe=aac8791780) | Sep 02, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fc9ec80df9](https://linux-hardware.org/?probe=fc9ec80df9) | Sep 02, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [f592e65a04](https://linux-hardware.org/?probe=f592e65a04) | Sep 02, 2023 |
| Dell          | Inspiron 5482               | Convertible | [05c6ec6d26](https://linux-hardware.org/?probe=05c6ec6d26) | Sep 02, 2023 |
| Lenovo        | 14w Gen 2 82N9              | Notebook    | [87c8a118b5](https://linux-hardware.org/?probe=87c8a118b5) | Sep 02, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [d7fcde026e](https://linux-hardware.org/?probe=d7fcde026e) | Sep 02, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f6a5d73879](https://linux-hardware.org/?probe=f6a5d73879) | Sep 01, 2023 |
| Prestigio     | Multipad Visconte V         | Notebook    | [3c60fe1d14](https://linux-hardware.org/?probe=3c60fe1d14) | Sep 01, 2023 |
| Acer          | One S1003                   | Tablet      | [b49022d342](https://linux-hardware.org/?probe=b49022d342) | Sep 01, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [3080550241](https://linux-hardware.org/?probe=3080550241) | Sep 01, 2023 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [b7439f4404](https://linux-hardware.org/?probe=b7439f4404) | Sep 01, 2023 |
| HP            | 89B5 A                      | Desktop     | [3b6a46c308](https://linux-hardware.org/?probe=3b6a46c308) | Sep 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [90be513b41](https://linux-hardware.org/?probe=90be513b41) | Sep 01, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [7d3823ff94](https://linux-hardware.org/?probe=7d3823ff94) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| ASUSTek       | E3M-ET V5 SERIES            | Desktop     | [62d1008e3a](https://linux-hardware.org/?probe=62d1008e3a) | Sep 01, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [24d0eafc15](https://linux-hardware.org/?probe=24d0eafc15) | Sep 01, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [bda3b1837c](https://linux-hardware.org/?probe=bda3b1837c) | Sep 01, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [edd00c35fd](https://linux-hardware.org/?probe=edd00c35fd) | Sep 01, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [61da3436a8](https://linux-hardware.org/?probe=61da3436a8) | Sep 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [81e9e055de](https://linux-hardware.org/?probe=81e9e055de) | Sep 01, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | Notebook    | [239b46961f](https://linux-hardware.org/?probe=239b46961f) | Sep 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | Notebook    | [e111bad271](https://linux-hardware.org/?probe=e111bad271) | Sep 01, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [a4ee14b9ac](https://linux-hardware.org/?probe=a4ee14b9ac) | Sep 01, 2023 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [5e0da96bdd](https://linux-hardware.org/?probe=5e0da96bdd) | Sep 01, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [3a4c0e0930](https://linux-hardware.org/?probe=3a4c0e0930) | Aug 31, 2023 |
| Apple         | MacBook9,1                  | Notebook    | [b6a28c1e1a](https://linux-hardware.org/?probe=b6a28c1e1a) | Aug 31, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [5b632410e7](https://linux-hardware.org/?probe=5b632410e7) | Aug 31, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L2402CYA... | Notebook    | [9881dd3268](https://linux-hardware.org/?probe=9881dd3268) | Aug 31, 2023 |
| Lenovo        | ThinkPad L470 20J40010GE    | Notebook    | [53adc42d66](https://linux-hardware.org/?probe=53adc42d66) | Aug 31, 2023 |
| Unknown       | H110M2                      | Desktop     | [bff031410a](https://linux-hardware.org/?probe=bff031410a) | Aug 31, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [2d86125311](https://linux-hardware.org/?probe=2d86125311) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [57ecd81ed7](https://linux-hardware.org/?probe=57ecd81ed7) | Aug 31, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [85cb771ac1](https://linux-hardware.org/?probe=85cb771ac1) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [ffa39e6acd](https://linux-hardware.org/?probe=ffa39e6acd) | Aug 31, 2023 |
| Dell          | Latitude 5590               | Notebook    | [59d99ec581](https://linux-hardware.org/?probe=59d99ec581) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [c3d8f5daca](https://linux-hardware.org/?probe=c3d8f5daca) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | Notebook    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [189647b3df](https://linux-hardware.org/?probe=189647b3df) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [f94ed7f5d1](https://linux-hardware.org/?probe=f94ed7f5d1) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | Desktop     | [c38af5d04d](https://linux-hardware.org/?probe=c38af5d04d) | Aug 31, 2023 |
| System76      | Lemur Pro                   | Notebook    | [c04af9751f](https://linux-hardware.org/?probe=c04af9751f) | Aug 31, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [84ed05802d](https://linux-hardware.org/?probe=84ed05802d) | Aug 31, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [9a459d2372](https://linux-hardware.org/?probe=9a459d2372) | Aug 31, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ffb1e72844](https://linux-hardware.org/?probe=ffb1e72844) | Aug 31, 2023 |
| ASUSTek       | EX-H110M-V3                 | Desktop     | [e2b97e4436](https://linux-hardware.org/?probe=e2b97e4436) | Aug 31, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [f5aaee7de3](https://linux-hardware.org/?probe=f5aaee7de3) | Aug 31, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [5fa96dfd97](https://linux-hardware.org/?probe=5fa96dfd97) | Aug 31, 2023 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [2ed0efb0a0](https://linux-hardware.org/?probe=2ed0efb0a0) | Aug 31, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | Desktop     | [04d647ae08](https://linux-hardware.org/?probe=04d647ae08) | Aug 30, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [4c595a576a](https://linux-hardware.org/?probe=4c595a576a) | Aug 30, 2023 |
| HP            | 83DD                        | Mini pc     | [2955a0b6c5](https://linux-hardware.org/?probe=2955a0b6c5) | Aug 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [78e163bc13](https://linux-hardware.org/?probe=78e163bc13) | Aug 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [0842215d23](https://linux-hardware.org/?probe=0842215d23) | Aug 30, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [53b237137d](https://linux-hardware.org/?probe=53b237137d) | Aug 30, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [dc9b122d90](https://linux-hardware.org/?probe=dc9b122d90) | Aug 30, 2023 |
| Dell          | Latitude 5430               | Notebook    | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
| Dell          | 0J2J3Y A00                  | Desktop     | [57ac609885](https://linux-hardware.org/?probe=57ac609885) | Aug 30, 2023 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [193a50f761](https://linux-hardware.org/?probe=193a50f761) | Aug 30, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [a75e60a457](https://linux-hardware.org/?probe=a75e60a457) | Aug 30, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [3cfa79235e](https://linux-hardware.org/?probe=3cfa79235e) | Aug 30, 2023 |
| MSI           | Z270M MORTAR                | Desktop     | [416723b60c](https://linux-hardware.org/?probe=416723b60c) | Aug 30, 2023 |
| Dell          | Latitude 5480               | Notebook    | [88c6621b31](https://linux-hardware.org/?probe=88c6621b31) | Aug 29, 2023 |
| Dell          | Precision 5480              | Notebook    | [5fd5bf187d](https://linux-hardware.org/?probe=5fd5bf187d) | Aug 29, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [dadd0516b5](https://linux-hardware.org/?probe=dadd0516b5) | Aug 29, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | Notebook    | [0eeb1276f0](https://linux-hardware.org/?probe=0eeb1276f0) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d036282290](https://linux-hardware.org/?probe=d036282290) | Aug 29, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [a2f594cf56](https://linux-hardware.org/?probe=a2f594cf56) | Aug 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [7e48b59643](https://linux-hardware.org/?probe=7e48b59643) | Aug 29, 2023 |
| Timi          | A34S                        | Notebook    | [eb6a3c2430](https://linux-hardware.org/?probe=eb6a3c2430) | Aug 29, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [3208c59e9c](https://linux-hardware.org/?probe=3208c59e9c) | Aug 29, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [1fd98a124f](https://linux-hardware.org/?probe=1fd98a124f) | Aug 29, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [7674d12aa5](https://linux-hardware.org/?probe=7674d12aa5) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d627b8c625](https://linux-hardware.org/?probe=d627b8c625) | Aug 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [07d9ceca83](https://linux-hardware.org/?probe=07d9ceca83) | Aug 28, 2023 |
| Fujitsu       | D3817-A1 S26361-D3817-A1... | Desktop     | [50e64dbfa2](https://linux-hardware.org/?probe=50e64dbfa2) | Aug 28, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [4b78bfab47](https://linux-hardware.org/?probe=4b78bfab47) | Aug 28, 2023 |
| Dell          | Latitude E6400              | Notebook    | [2af0a423ef](https://linux-hardware.org/?probe=2af0a423ef) | Aug 28, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [b68e4634b7](https://linux-hardware.org/?probe=b68e4634b7) | Aug 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [8288d35dff](https://linux-hardware.org/?probe=8288d35dff) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5fddb9cc18](https://linux-hardware.org/?probe=5fddb9cc18) | Aug 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a762e96941](https://linux-hardware.org/?probe=a762e96941) | Aug 28, 2023 |
| Microsoft     | Surface Pro 9               | Tablet      | [d6a04f712b](https://linux-hardware.org/?probe=d6a04f712b) | Aug 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [40c64b6ec2](https://linux-hardware.org/?probe=40c64b6ec2) | Aug 28, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [7608fab281](https://linux-hardware.org/?probe=7608fab281) | Aug 28, 2023 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [90e0cad295](https://linux-hardware.org/?probe=90e0cad295) | Aug 28, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [d302b80de1](https://linux-hardware.org/?probe=d302b80de1) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [da73419cb5](https://linux-hardware.org/?probe=da73419cb5) | Aug 27, 2023 |
| Framework     | Laptop                      | Notebook    | [b3e9d2d48d](https://linux-hardware.org/?probe=b3e9d2d48d) | Aug 27, 2023 |
| Corsair       | Voyager a1600               | Notebook    | [405bce7897](https://linux-hardware.org/?probe=405bce7897) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8acc158836](https://linux-hardware.org/?probe=8acc158836) | Aug 27, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c326205a9b](https://linux-hardware.org/?probe=c326205a9b) | Aug 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [864a9d9f37](https://linux-hardware.org/?probe=864a9d9f37) | Aug 27, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [69d14b429e](https://linux-hardware.org/?probe=69d14b429e) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [492a021411](https://linux-hardware.org/?probe=492a021411) | Aug 27, 2023 |
| Dell          | 0KFKMF A00                  | All in one  | [c15583fc1c](https://linux-hardware.org/?probe=c15583fc1c) | Aug 27, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [47b9d876af](https://linux-hardware.org/?probe=47b9d876af) | Aug 27, 2023 |
| Dell          | Latitude E6400              | Notebook    | [fdcbc50452](https://linux-hardware.org/?probe=fdcbc50452) | Aug 27, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [3903bc9e14](https://linux-hardware.org/?probe=3903bc9e14) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [fe02fb8d64](https://linux-hardware.org/?probe=fe02fb8d64) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [c1bea53459](https://linux-hardware.org/?probe=c1bea53459) | Aug 27, 2023 |
| Timi          | TM1701                      | Notebook    | [2a6a4225a0](https://linux-hardware.org/?probe=2a6a4225a0) | Aug 27, 2023 |
| Timi          | TM1701                      | Notebook    | [8ea7c21e18](https://linux-hardware.org/?probe=8ea7c21e18) | Aug 27, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1731ba4ae5](https://linux-hardware.org/?probe=1731ba4ae5) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [5d220003c1](https://linux-hardware.org/?probe=5d220003c1) | Aug 27, 2023 |
| HP            | Pavilion 15                 | Notebook    | [0f51268684](https://linux-hardware.org/?probe=0f51268684) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a8600db157](https://linux-hardware.org/?probe=a8600db157) | Aug 27, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [7bdfc94045](https://linux-hardware.org/?probe=7bdfc94045) | Aug 27, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [d80e4744e9](https://linux-hardware.org/?probe=d80e4744e9) | Aug 27, 2023 |
| MSI           | MS-7388                     | Desktop     | [42530086f2](https://linux-hardware.org/?probe=42530086f2) | Aug 27, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [629b07f8bc](https://linux-hardware.org/?probe=629b07f8bc) | Aug 27, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [f71c3553e6](https://linux-hardware.org/?probe=f71c3553e6) | Aug 27, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [08748d2c86](https://linux-hardware.org/?probe=08748d2c86) | Aug 27, 2023 |
| Lenovo        | IdeaPad Z570 1024DCU        | Notebook    | [8a11757d37](https://linux-hardware.org/?probe=8a11757d37) | Aug 26, 2023 |
| Corsair       | Voyager a1600               | Notebook    | [97a1c576f7](https://linux-hardware.org/?probe=97a1c576f7) | Aug 26, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | Notebook    | [4e5f7a05c6](https://linux-hardware.org/?probe=4e5f7a05c6) | Aug 26, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [b2ad72336f](https://linux-hardware.org/?probe=b2ad72336f) | Aug 26, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [df71a92503](https://linux-hardware.org/?probe=df71a92503) | Aug 26, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [cbbaecabb1](https://linux-hardware.org/?probe=cbbaecabb1) | Aug 26, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [c2efac4748](https://linux-hardware.org/?probe=c2efac4748) | Aug 26, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [9e90f8b308](https://linux-hardware.org/?probe=9e90f8b308) | Aug 26, 2023 |
| ASUSTek       | X542BP                      | Notebook    | [58cc535a58](https://linux-hardware.org/?probe=58cc535a58) | Aug 26, 2023 |
| AZW           | U59                         | Desktop     | [ea7bf087cc](https://linux-hardware.org/?probe=ea7bf087cc) | Aug 26, 2023 |
| AZW           | U59                         | Desktop     | [d35717e2e4](https://linux-hardware.org/?probe=d35717e2e4) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [95548b426e](https://linux-hardware.org/?probe=95548b426e) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [6bd0ecde29](https://linux-hardware.org/?probe=6bd0ecde29) | Aug 26, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [ef267bc627](https://linux-hardware.org/?probe=ef267bc627) | Aug 26, 2023 |
| Apple         | MacBookPro13,2              | Notebook    | [b910d52198](https://linux-hardware.org/?probe=b910d52198) | Aug 26, 2023 |
| ASRock        | B560 Steel Legend           | Desktop     | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [771adfa310](https://linux-hardware.org/?probe=771adfa310) | Aug 25, 2023 |
| MSI           | MS-7388                     | Desktop     | [5c1e4b0c2b](https://linux-hardware.org/?probe=5c1e4b0c2b) | Aug 25, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [b14dfb0798](https://linux-hardware.org/?probe=b14dfb0798) | Aug 25, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [914ba9937f](https://linux-hardware.org/?probe=914ba9937f) | Aug 25, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [22187e6de0](https://linux-hardware.org/?probe=22187e6de0) | Aug 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [810ccd6f4f](https://linux-hardware.org/?probe=810ccd6f4f) | Aug 25, 2023 |
| Dell          | Latitude 3490               | Notebook    | [05705b1834](https://linux-hardware.org/?probe=05705b1834) | Aug 25, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [ef7b263d48](https://linux-hardware.org/?probe=ef7b263d48) | Aug 25, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [2647e2edd8](https://linux-hardware.org/?probe=2647e2edd8) | Aug 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [30ee0ec0ba](https://linux-hardware.org/?probe=30ee0ec0ba) | Aug 24, 2023 |
| HP            | 3047h                       | Desktop     | [5c415723ef](https://linux-hardware.org/?probe=5c415723ef) | Aug 24, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [0d9ddb7de2](https://linux-hardware.org/?probe=0d9ddb7de2) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | Desktop     | [ba401056e8](https://linux-hardware.org/?probe=ba401056e8) | Aug 24, 2023 |
| Packard Be... | GA-T671MG                   | Desktop     | [d51fb378a1](https://linux-hardware.org/?probe=d51fb378a1) | Aug 24, 2023 |
| Dell          | G15 5510                    | Notebook    | [f9e857e751](https://linux-hardware.org/?probe=f9e857e751) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [7e6a7de337](https://linux-hardware.org/?probe=7e6a7de337) | Aug 24, 2023 |
| Sony          | SVF15A1M2ES                 | Notebook    | [b352453232](https://linux-hardware.org/?probe=b352453232) | Aug 24, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [bf7413fc5f](https://linux-hardware.org/?probe=bf7413fc5f) | Aug 24, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [25dc707bff](https://linux-hardware.org/?probe=25dc707bff) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [1a9c135840](https://linux-hardware.org/?probe=1a9c135840) | Aug 24, 2023 |
| LDLC          | SPC-I                       | Notebook    | [bb114215e6](https://linux-hardware.org/?probe=bb114215e6) | Aug 24, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [1330f2ac2a](https://linux-hardware.org/?probe=1330f2ac2a) | Aug 24, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [329842693e](https://linux-hardware.org/?probe=329842693e) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | Notebook    | [5f18850003](https://linux-hardware.org/?probe=5f18850003) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | Notebook    | [de37c3c7eb](https://linux-hardware.org/?probe=de37c3c7eb) | Aug 24, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ce5f964a0c](https://linux-hardware.org/?probe=ce5f964a0c) | Aug 24, 2023 |
| Dell          | Latitude 3490               | Notebook    | [148d4806cb](https://linux-hardware.org/?probe=148d4806cb) | Aug 24, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [68c01672c3](https://linux-hardware.org/?probe=68c01672c3) | Aug 24, 2023 |
| Gigabyte      | H310M M.2                   | Desktop     | [9b1205f50a](https://linux-hardware.org/?probe=9b1205f50a) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [a06cf8de37](https://linux-hardware.org/?probe=a06cf8de37) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [b6591e9fd9](https://linux-hardware.org/?probe=b6591e9fd9) | Aug 24, 2023 |
| AZW           | GTR V02                     | Desktop     | [6c91212b1a](https://linux-hardware.org/?probe=6c91212b1a) | Aug 24, 2023 |
| Xplore        | iX104C6                     | Notebook    | [5d8ea1a454](https://linux-hardware.org/?probe=5d8ea1a454) | Aug 24, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [17525a9aef](https://linux-hardware.org/?probe=17525a9aef) | Aug 24, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [5e5059f835](https://linux-hardware.org/?probe=5e5059f835) | Aug 23, 2023 |
| ASRock        | FP6D4-P1                    | Desktop     | [722789f2ac](https://linux-hardware.org/?probe=722789f2ac) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [fd9fa02e66](https://linux-hardware.org/?probe=fd9fa02e66) | Aug 23, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1bd1add449](https://linux-hardware.org/?probe=1bd1add449) | Aug 23, 2023 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [62a1cc3d3b](https://linux-hardware.org/?probe=62a1cc3d3b) | Aug 23, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f2f57d0e61](https://linux-hardware.org/?probe=f2f57d0e61) | Aug 23, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [adda6295fb](https://linux-hardware.org/?probe=adda6295fb) | Aug 23, 2023 |
| Acer          | Predator PT715-51           | Notebook    | [e187e199c9](https://linux-hardware.org/?probe=e187e199c9) | Aug 23, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [66b46e04d3](https://linux-hardware.org/?probe=66b46e04d3) | Aug 23, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [e11053f833](https://linux-hardware.org/?probe=e11053f833) | Aug 23, 2023 |
| Linx          | LINX12X64                   | Tablet      | [8e57cc64f6](https://linux-hardware.org/?probe=8e57cc64f6) | Aug 23, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [e9b32aa827](https://linux-hardware.org/?probe=e9b32aa827) | Aug 23, 2023 |
| Google        | Nami                        | Notebook    | [db2c6bfb0a](https://linux-hardware.org/?probe=db2c6bfb0a) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [08801db21d](https://linux-hardware.org/?probe=08801db21d) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [9b3cf2a525](https://linux-hardware.org/?probe=9b3cf2a525) | Aug 23, 2023 |
| MSI           | Z370-OC PRO                 | Desktop     | [4ee0bb1c63](https://linux-hardware.org/?probe=4ee0bb1c63) | Aug 23, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | Notebook    | [f429d18938](https://linux-hardware.org/?probe=f429d18938) | Aug 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [310e1f561c](https://linux-hardware.org/?probe=310e1f561c) | Aug 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f7580a556b](https://linux-hardware.org/?probe=f7580a556b) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [68d28831a5](https://linux-hardware.org/?probe=68d28831a5) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [25d163ad9e](https://linux-hardware.org/?probe=25d163ad9e) | Aug 22, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [64f3da359d](https://linux-hardware.org/?probe=64f3da359d) | Aug 22, 2023 |
| Google        | Nami                        | Notebook    | [69d8c7bfb8](https://linux-hardware.org/?probe=69d8c7bfb8) | Aug 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [9ad109a4df](https://linux-hardware.org/?probe=9ad109a4df) | Aug 22, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [bf401f98a7](https://linux-hardware.org/?probe=bf401f98a7) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [f35c644052](https://linux-hardware.org/?probe=f35c644052) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [4f4bed768e](https://linux-hardware.org/?probe=4f4bed768e) | Aug 22, 2023 |
| Dell          | Latitude 7430               | Notebook    | [1ccbb8329f](https://linux-hardware.org/?probe=1ccbb8329f) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [39dbb86112](https://linux-hardware.org/?probe=39dbb86112) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [2d616412f1](https://linux-hardware.org/?probe=2d616412f1) | Aug 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [73a003bf4b](https://linux-hardware.org/?probe=73a003bf4b) | Aug 22, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [76c16d7ffe](https://linux-hardware.org/?probe=76c16d7ffe) | Aug 22, 2023 |
| MSI           | Z370-OC PRO                 | Desktop     | [bbd85c94d6](https://linux-hardware.org/?probe=bbd85c94d6) | Aug 22, 2023 |
| ASUSTek       | B460M-N                     | Desktop     | [382640772b](https://linux-hardware.org/?probe=382640772b) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [55e95b21f1](https://linux-hardware.org/?probe=55e95b21f1) | Aug 22, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [6a3c737df2](https://linux-hardware.org/?probe=6a3c737df2) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [05c761f480](https://linux-hardware.org/?probe=05c761f480) | Aug 22, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [70399bc4c6](https://linux-hardware.org/?probe=70399bc4c6) | Aug 21, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [0091cd8a97](https://linux-hardware.org/?probe=0091cd8a97) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a03d5e6451](https://linux-hardware.org/?probe=a03d5e6451) | Aug 21, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [fdfc3b92f9](https://linux-hardware.org/?probe=fdfc3b92f9) | Aug 21, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [d2378787ac](https://linux-hardware.org/?probe=d2378787ac) | Aug 21, 2023 |
| Dell          | Latitude 3301               | Notebook    | [69389fff09](https://linux-hardware.org/?probe=69389fff09) | Aug 21, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [09d57c6701](https://linux-hardware.org/?probe=09d57c6701) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [63b37fd7f7](https://linux-hardware.org/?probe=63b37fd7f7) | Aug 21, 2023 |
| Lenovo        | ThinkPad T430 2347C32       | Notebook    | [6956f76011](https://linux-hardware.org/?probe=6956f76011) | Aug 21, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [b5b7a6d8f8](https://linux-hardware.org/?probe=b5b7a6d8f8) | Aug 21, 2023 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [dd12e382c8](https://linux-hardware.org/?probe=dd12e382c8) | Aug 21, 2023 |
| HP            | 3048h                       | Desktop     | [959637abde](https://linux-hardware.org/?probe=959637abde) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713IE_G713IE     | Notebook    | [22443858cb](https://linux-hardware.org/?probe=22443858cb) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a8a1e5df49](https://linux-hardware.org/?probe=a8a1e5df49) | Aug 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [359cd5a655](https://linux-hardware.org/?probe=359cd5a655) | Aug 21, 2023 |
| Dell          | Latitude 7490               | Notebook    | [90685f1b4d](https://linux-hardware.org/?probe=90685f1b4d) | Aug 21, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [6047cef31c](https://linux-hardware.org/?probe=6047cef31c) | Aug 21, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [986599dc77](https://linux-hardware.org/?probe=986599dc77) | Aug 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c1a5eb75bf](https://linux-hardware.org/?probe=c1a5eb75bf) | Aug 21, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [d1ee285db9](https://linux-hardware.org/?probe=d1ee285db9) | Aug 21, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [f38ba797d9](https://linux-hardware.org/?probe=f38ba797d9) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [735e03f0f9](https://linux-hardware.org/?probe=735e03f0f9) | Aug 21, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [d4f90e5eff](https://linux-hardware.org/?probe=d4f90e5eff) | Aug 21, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [da3f4808a1](https://linux-hardware.org/?probe=da3f4808a1) | Aug 20, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [5fa4b8ae13](https://linux-hardware.org/?probe=5fa4b8ae13) | Aug 20, 2023 |
| ASRock        | A520M-HDV                   | Desktop     | [cb333c6fae](https://linux-hardware.org/?probe=cb333c6fae) | Aug 20, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [c3a8668cee](https://linux-hardware.org/?probe=c3a8668cee) | Aug 20, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [7da89c9360](https://linux-hardware.org/?probe=7da89c9360) | Aug 20, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [24a2760d65](https://linux-hardware.org/?probe=24a2760d65) | Aug 20, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f3151f84cb](https://linux-hardware.org/?probe=f3151f84cb) | Aug 20, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [448603376e](https://linux-hardware.org/?probe=448603376e) | Aug 20, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [c6f278a589](https://linux-hardware.org/?probe=c6f278a589) | Aug 20, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8e91f085b4](https://linux-hardware.org/?probe=8e91f085b4) | Aug 20, 2023 |
| HP            | 3032h                       | Desktop     | [f3292df409](https://linux-hardware.org/?probe=f3292df409) | Aug 20, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [1b7a1416fc](https://linux-hardware.org/?probe=1b7a1416fc) | Aug 20, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [03bd8885a0](https://linux-hardware.org/?probe=03bd8885a0) | Aug 20, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [645bd9ed6b](https://linux-hardware.org/?probe=645bd9ed6b) | Aug 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [978af80f5a](https://linux-hardware.org/?probe=978af80f5a) | Aug 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [06daace50c](https://linux-hardware.org/?probe=06daace50c) | Aug 20, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [96fb68dc70](https://linux-hardware.org/?probe=96fb68dc70) | Aug 20, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [d79d66d11e](https://linux-hardware.org/?probe=d79d66d11e) | Aug 20, 2023 |
| Sony          | SVF1521USTW                 | Notebook    | [ce7fbec260](https://linux-hardware.org/?probe=ce7fbec260) | Aug 20, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [2561456785](https://linux-hardware.org/?probe=2561456785) | Aug 20, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [ae3c86cccf](https://linux-hardware.org/?probe=ae3c86cccf) | Aug 19, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [a15e796833](https://linux-hardware.org/?probe=a15e796833) | Aug 19, 2023 |
| Sony          | SVF1521USTW                 | Notebook    | [e92fad444f](https://linux-hardware.org/?probe=e92fad444f) | Aug 19, 2023 |
| ASUSTek       | M4A77                       | Desktop     | [89bb5a2821](https://linux-hardware.org/?probe=89bb5a2821) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [36417c2601](https://linux-hardware.org/?probe=36417c2601) | Aug 19, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | Notebook    | [ed572b9b04](https://linux-hardware.org/?probe=ed572b9b04) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [81dd9b9a7a](https://linux-hardware.org/?probe=81dd9b9a7a) | Aug 19, 2023 |
| Lenovo        | Yoga 7 14IAL7 82QE          | Convertible | [dc5d42e6cb](https://linux-hardware.org/?probe=dc5d42e6cb) | Aug 19, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [651f263a9d](https://linux-hardware.org/?probe=651f263a9d) | Aug 19, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [ac85dd7bb4](https://linux-hardware.org/?probe=ac85dd7bb4) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c99b76f9fe](https://linux-hardware.org/?probe=c99b76f9fe) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [c6f3f044c9](https://linux-hardware.org/?probe=c6f3f044c9) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [9734816ff1](https://linux-hardware.org/?probe=9734816ff1) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [80b304814d](https://linux-hardware.org/?probe=80b304814d) | Aug 19, 2023 |
| HP            | Pavilion dv4                | Notebook    | [5f1e0c4484](https://linux-hardware.org/?probe=5f1e0c4484) | Aug 19, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [98ebe4bf9a](https://linux-hardware.org/?probe=98ebe4bf9a) | Aug 19, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [3cdfdae368](https://linux-hardware.org/?probe=3cdfdae368) | Aug 19, 2023 |
| Dell          | 0HT36J A01                  | All in one  | [670a695599](https://linux-hardware.org/?probe=670a695599) | Aug 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [dee14abe77](https://linux-hardware.org/?probe=dee14abe77) | Aug 18, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c43c2f3798](https://linux-hardware.org/?probe=c43c2f3798) | Aug 18, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [64428e8ca9](https://linux-hardware.org/?probe=64428e8ca9) | Aug 18, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [cace7d6efb](https://linux-hardware.org/?probe=cace7d6efb) | Aug 18, 2023 |
| Samsung       | 750QFG                      | Convertible | [ff0b9fb300](https://linux-hardware.org/?probe=ff0b9fb300) | Aug 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [722707e986](https://linux-hardware.org/?probe=722707e986) | Aug 18, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [12c6ae9006](https://linux-hardware.org/?probe=12c6ae9006) | Aug 18, 2023 |
| Dell          | 0YJMC0 A02                  | Desktop     | [f4818214d5](https://linux-hardware.org/?probe=f4818214d5) | Aug 18, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [f7d0bbc3d9](https://linux-hardware.org/?probe=f7d0bbc3d9) | Aug 18, 2023 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | Notebook    | [c9e9e56ddd](https://linux-hardware.org/?probe=c9e9e56ddd) | Aug 18, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [f719885fe3](https://linux-hardware.org/?probe=f719885fe3) | Aug 18, 2023 |
| Dell          | Latitude 7320               | Notebook    | [a51289d9dd](https://linux-hardware.org/?probe=a51289d9dd) | Aug 18, 2023 |
| System76      | Pangolin                    | Notebook    | [5191e3a345](https://linux-hardware.org/?probe=5191e3a345) | Aug 18, 2023 |
| Schenker      | MEDIA (M22)                 | Notebook    | [463903cc03](https://linux-hardware.org/?probe=463903cc03) | Aug 18, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [da33e8f1c1](https://linux-hardware.org/?probe=da33e8f1c1) | Aug 18, 2023 |
| ASUSTek       | PN52                        | Mini pc     | [405bf1e224](https://linux-hardware.org/?probe=405bf1e224) | Aug 18, 2023 |
| MSI           | MS-1057                     | Notebook    | [081ae63942](https://linux-hardware.org/?probe=081ae63942) | Aug 18, 2023 |
| MSI           | MS-1057                     | Notebook    | [615f03f3b8](https://linux-hardware.org/?probe=615f03f3b8) | Aug 18, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cfbf5747b3](https://linux-hardware.org/?probe=cfbf5747b3) | Aug 18, 2023 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [92f8391f8f](https://linux-hardware.org/?probe=92f8391f8f) | Aug 18, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [b8e5fd59d3](https://linux-hardware.org/?probe=b8e5fd59d3) | Aug 18, 2023 |
| Lenovo        | ThinkPad L480 20LTS6S904    | Notebook    | [32ded049ec](https://linux-hardware.org/?probe=32ded049ec) | Aug 17, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [607356bb8f](https://linux-hardware.org/?probe=607356bb8f) | Aug 17, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [df194863d1](https://linux-hardware.org/?probe=df194863d1) | Aug 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8958908392](https://linux-hardware.org/?probe=8958908392) | Aug 17, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [87a6bd39ae](https://linux-hardware.org/?probe=87a6bd39ae) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [4b8894823c](https://linux-hardware.org/?probe=4b8894823c) | Aug 17, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [e688e27904](https://linux-hardware.org/?probe=e688e27904) | Aug 17, 2023 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [3f0d1e0d44](https://linux-hardware.org/?probe=3f0d1e0d44) | Aug 17, 2023 |
| Dell          | Latitude 7440               | Notebook    | [e56c46e8fe](https://linux-hardware.org/?probe=e56c46e8fe) | Aug 17, 2023 |
| Dell          | Latitude 7440               | Notebook    | [aef57d5421](https://linux-hardware.org/?probe=aef57d5421) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [d0d3c76bb8](https://linux-hardware.org/?probe=d0d3c76bb8) | Aug 17, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [0af0e7a958](https://linux-hardware.org/?probe=0af0e7a958) | Aug 17, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [c753cfdb08](https://linux-hardware.org/?probe=c753cfdb08) | Aug 17, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [65a1f155c0](https://linux-hardware.org/?probe=65a1f155c0) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [ae88c56896](https://linux-hardware.org/?probe=ae88c56896) | Aug 17, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [75556aed08](https://linux-hardware.org/?probe=75556aed08) | Aug 16, 2023 |
| ASRock        | A320M-HD R4.0               | Desktop     | [f67dd298b1](https://linux-hardware.org/?probe=f67dd298b1) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [82c579f8a7](https://linux-hardware.org/?probe=82c579f8a7) | Aug 16, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [66691707c9](https://linux-hardware.org/?probe=66691707c9) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480s 20L7001VG... | Notebook    | [b0b2f8a7e1](https://linux-hardware.org/?probe=b0b2f8a7e1) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480s 20L7001VG... | Notebook    | [07b5827382](https://linux-hardware.org/?probe=07b5827382) | Aug 16, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [b27f36262e](https://linux-hardware.org/?probe=b27f36262e) | Aug 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f3c603341d](https://linux-hardware.org/?probe=f3c603341d) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [af217ce6dc](https://linux-hardware.org/?probe=af217ce6dc) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [feeb3d8bbe](https://linux-hardware.org/?probe=feeb3d8bbe) | Aug 16, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [b2377a274f](https://linux-hardware.org/?probe=b2377a274f) | Aug 16, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [8e3f72e46d](https://linux-hardware.org/?probe=8e3f72e46d) | Aug 16, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [bbf606d6e8](https://linux-hardware.org/?probe=bbf606d6e8) | Aug 16, 2023 |
| Dell          | Latitude E5400              | Notebook    | [7d861c3812](https://linux-hardware.org/?probe=7d861c3812) | Aug 16, 2023 |
| Dell          | Latitude 5420               | Notebook    | [12d46be852](https://linux-hardware.org/?probe=12d46be852) | Aug 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b326fccb63](https://linux-hardware.org/?probe=b326fccb63) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [24cd5deaa3](https://linux-hardware.org/?probe=24cd5deaa3) | Aug 16, 2023 |
| Dell          | Latitude 7490               | Notebook    | [efb4abea09](https://linux-hardware.org/?probe=efb4abea09) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [ff958dc821](https://linux-hardware.org/?probe=ff958dc821) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b42d5dec8e](https://linux-hardware.org/?probe=b42d5dec8e) | Aug 16, 2023 |
| Microsoft     | Surface Laptop Studio       | Tablet      | [99da6f8732](https://linux-hardware.org/?probe=99da6f8732) | Aug 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | Notebook    | [da5582d4bf](https://linux-hardware.org/?probe=da5582d4bf) | Aug 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | Notebook    | [63f2bc3a80](https://linux-hardware.org/?probe=63f2bc3a80) | Aug 16, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ee72caa76d](https://linux-hardware.org/?probe=ee72caa76d) | Aug 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8733f22b33](https://linux-hardware.org/?probe=8733f22b33) | Aug 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS03V0... | Notebook    | [f50a83684f](https://linux-hardware.org/?probe=f50a83684f) | Aug 16, 2023 |
| Lenovo        | ThinkPad T550 20CJS1JT00    | Notebook    | [78cd2292c2](https://linux-hardware.org/?probe=78cd2292c2) | Aug 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [725cdd1013](https://linux-hardware.org/?probe=725cdd1013) | Aug 16, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [1ff9bff198](https://linux-hardware.org/?probe=1ff9bff198) | Aug 15, 2023 |
| Dell          | Latitude 3301               | Notebook    | [8cbe049a08](https://linux-hardware.org/?probe=8cbe049a08) | Aug 15, 2023 |
| HP            | 3047h                       | Desktop     | [b136128b47](https://linux-hardware.org/?probe=b136128b47) | Aug 15, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [4ac83eed41](https://linux-hardware.org/?probe=4ac83eed41) | Aug 15, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5e5606074a](https://linux-hardware.org/?probe=5e5606074a) | Aug 15, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [cfa082df13](https://linux-hardware.org/?probe=cfa082df13) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [6e7b731daa](https://linux-hardware.org/?probe=6e7b731daa) | Aug 15, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [9f3c41bd31](https://linux-hardware.org/?probe=9f3c41bd31) | Aug 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [30e2a20d37](https://linux-hardware.org/?probe=30e2a20d37) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [6c933602ca](https://linux-hardware.org/?probe=6c933602ca) | Aug 15, 2023 |
| Topstar       | Cantiga & ICH9M Chipset     | Notebook    | [5102056c71](https://linux-hardware.org/?probe=5102056c71) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [618b4d5598](https://linux-hardware.org/?probe=618b4d5598) | Aug 15, 2023 |
| Dell          | Latitude E6530              | Notebook    | [9cbe752127](https://linux-hardware.org/?probe=9cbe752127) | Aug 15, 2023 |
| Toshiba       | Satellite C55D-A            | Notebook    | [5a86eae963](https://linux-hardware.org/?probe=5a86eae963) | Aug 15, 2023 |
| Google        | Bobba360                    | Notebook    | [e2ae1afdcc](https://linux-hardware.org/?probe=e2ae1afdcc) | Aug 14, 2023 |
| Medion        | MS-7800                     | Desktop     | [afab92f1e4](https://linux-hardware.org/?probe=afab92f1e4) | Aug 14, 2023 |
| MSI           | H510M PRO                   | Desktop     | [df350cd466](https://linux-hardware.org/?probe=df350cd466) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [52bd9574d8](https://linux-hardware.org/?probe=52bd9574d8) | Aug 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [f99741ec7f](https://linux-hardware.org/?probe=f99741ec7f) | Aug 14, 2023 |
| Google        | Bobba360                    | Notebook    | [f211501fde](https://linux-hardware.org/?probe=f211501fde) | Aug 14, 2023 |
| Lenovo        | 1046 SBB1C50531 WIN 3556... | Desktop     | [f24668bfd7](https://linux-hardware.org/?probe=f24668bfd7) | Aug 14, 2023 |
| HP            | Notebook                    | Notebook    | [f32b596c87](https://linux-hardware.org/?probe=f32b596c87) | Aug 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [c192c37af2](https://linux-hardware.org/?probe=c192c37af2) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [d2ccdc066b](https://linux-hardware.org/?probe=d2ccdc066b) | Aug 14, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [11b8c16b30](https://linux-hardware.org/?probe=11b8c16b30) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [c939a92f1d](https://linux-hardware.org/?probe=c939a92f1d) | Aug 14, 2023 |
| Unknown       | V00                         | Mini pc     | [a043004a53](https://linux-hardware.org/?probe=a043004a53) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [74eb1759e1](https://linux-hardware.org/?probe=74eb1759e1) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [56efab026f](https://linux-hardware.org/?probe=56efab026f) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [24b85b3417](https://linux-hardware.org/?probe=24b85b3417) | Aug 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [28be66d0b1](https://linux-hardware.org/?probe=28be66d0b1) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [cc343d2dce](https://linux-hardware.org/?probe=cc343d2dce) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [361ad7057c](https://linux-hardware.org/?probe=361ad7057c) | Aug 13, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0SQ... | Tablet      | [833489f8a8](https://linux-hardware.org/?probe=833489f8a8) | Aug 13, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f256ce0d84](https://linux-hardware.org/?probe=f256ce0d84) | Aug 13, 2023 |
| Dell          | Latitude E7470              | Notebook    | [99518b81f7](https://linux-hardware.org/?probe=99518b81f7) | Aug 13, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [7612329440](https://linux-hardware.org/?probe=7612329440) | Aug 13, 2023 |
| Google        | Blorb                       | Notebook    | [d1abf19439](https://linux-hardware.org/?probe=d1abf19439) | Aug 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [400e17fe60](https://linux-hardware.org/?probe=400e17fe60) | Aug 13, 2023 |
| HP            | ProBook 6450b               | Notebook    | [8862a40143](https://linux-hardware.org/?probe=8862a40143) | Aug 13, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [c7e0716355](https://linux-hardware.org/?probe=c7e0716355) | Aug 13, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [9a7018c6cb](https://linux-hardware.org/?probe=9a7018c6cb) | Aug 13, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [0650746552](https://linux-hardware.org/?probe=0650746552) | Aug 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [8ef1bbdcec](https://linux-hardware.org/?probe=8ef1bbdcec) | Aug 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS3320C    | Notebook    | [51f9e0c482](https://linux-hardware.org/?probe=51f9e0c482) | Aug 13, 2023 |
| HP            | Pavilion Laptop 15z-eh00... | Notebook    | [6f54d654ac](https://linux-hardware.org/?probe=6f54d654ac) | Aug 13, 2023 |
| Toshiba       | Satellite C55D-A            | Notebook    | [136ac6835c](https://linux-hardware.org/?probe=136ac6835c) | Aug 13, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [88056b62e3](https://linux-hardware.org/?probe=88056b62e3) | Aug 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [45cb1198bb](https://linux-hardware.org/?probe=45cb1198bb) | Aug 13, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [dd2538ba1a](https://linux-hardware.org/?probe=dd2538ba1a) | Aug 13, 2023 |
| MSI           | GT62VR 7RE                  | Notebook    | [105839bee0](https://linux-hardware.org/?probe=105839bee0) | Aug 13, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [b718d1c1f8](https://linux-hardware.org/?probe=b718d1c1f8) | Aug 13, 2023 |
| Framework     | Laptop                      | Notebook    | [8ac155813e](https://linux-hardware.org/?probe=8ac155813e) | Aug 13, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [05a4c5e1ec](https://linux-hardware.org/?probe=05a4c5e1ec) | Aug 13, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [25a3921b74](https://linux-hardware.org/?probe=25a3921b74) | Aug 13, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [ed549bc47c](https://linux-hardware.org/?probe=ed549bc47c) | Aug 12, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [3751d5807e](https://linux-hardware.org/?probe=3751d5807e) | Aug 12, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [788c2c9e31](https://linux-hardware.org/?probe=788c2c9e31) | Aug 12, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [57a63573fc](https://linux-hardware.org/?probe=57a63573fc) | Aug 12, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [def5f9423e](https://linux-hardware.org/?probe=def5f9423e) | Aug 12, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f2f4f8a844](https://linux-hardware.org/?probe=f2f4f8a844) | Aug 12, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3d875407fc](https://linux-hardware.org/?probe=3d875407fc) | Aug 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [22690b9d65](https://linux-hardware.org/?probe=22690b9d65) | Aug 12, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [b43e2738d9](https://linux-hardware.org/?probe=b43e2738d9) | Aug 12, 2023 |
| Dell          | G15 5510                    | Notebook    | [3cfac2d234](https://linux-hardware.org/?probe=3cfac2d234) | Aug 12, 2023 |
| Lenovo        | ThinkPad T460p 20FXS1C30... | Notebook    | [08542d994e](https://linux-hardware.org/?probe=08542d994e) | Aug 12, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [05024005e4](https://linux-hardware.org/?probe=05024005e4) | Aug 12, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [411b9f412c](https://linux-hardware.org/?probe=411b9f412c) | Aug 12, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d25ab08211](https://linux-hardware.org/?probe=d25ab08211) | Aug 12, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [90816726b0](https://linux-hardware.org/?probe=90816726b0) | Aug 12, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [d1bf5ba3c3](https://linux-hardware.org/?probe=d1bf5ba3c3) | Aug 12, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [783651bb7d](https://linux-hardware.org/?probe=783651bb7d) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [5b9aef438f](https://linux-hardware.org/?probe=5b9aef438f) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [1f3f8a869b](https://linux-hardware.org/?probe=1f3f8a869b) | Aug 12, 2023 |
| Dell          | Latitude E7270              | Notebook    | [63fd1b0d6b](https://linux-hardware.org/?probe=63fd1b0d6b) | Aug 12, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7ef87af541](https://linux-hardware.org/?probe=7ef87af541) | Aug 12, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [92f4e14369](https://linux-hardware.org/?probe=92f4e14369) | Aug 11, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [377a0e25aa](https://linux-hardware.org/?probe=377a0e25aa) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7574e6b53a](https://linux-hardware.org/?probe=7574e6b53a) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [d4b93affe2](https://linux-hardware.org/?probe=d4b93affe2) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [7a8e32eb89](https://linux-hardware.org/?probe=7a8e32eb89) | Aug 11, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [c336f9aa8c](https://linux-hardware.org/?probe=c336f9aa8c) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [c352abad93](https://linux-hardware.org/?probe=c352abad93) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b174f07d2](https://linux-hardware.org/?probe=4b174f07d2) | Aug 11, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [f4abfc94d4](https://linux-hardware.org/?probe=f4abfc94d4) | Aug 11, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [74283f31aa](https://linux-hardware.org/?probe=74283f31aa) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [29065a56ee](https://linux-hardware.org/?probe=29065a56ee) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [22fc28c382](https://linux-hardware.org/?probe=22fc28c382) | Aug 11, 2023 |
| Lenovo        | IdeaCentre B320             | Desktop     | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [471e3c5077](https://linux-hardware.org/?probe=471e3c5077) | Aug 11, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ee1a7cb0aa](https://linux-hardware.org/?probe=ee1a7cb0aa) | Aug 11, 2023 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [a88d7e81e5](https://linux-hardware.org/?probe=a88d7e81e5) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7da6954bc5](https://linux-hardware.org/?probe=7da6954bc5) | Aug 10, 2023 |
| Dell          | Latitude 5300               | Notebook    | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| Lenovo        | ThinkPad X220 4291SEN       | Notebook    | [b62026890a](https://linux-hardware.org/?probe=b62026890a) | Aug 10, 2023 |
| HP            | 250 G3                      | Notebook    | [512fd5d81f](https://linux-hardware.org/?probe=512fd5d81f) | Aug 10, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [426901227d](https://linux-hardware.org/?probe=426901227d) | Aug 10, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [6743c7ca9d](https://linux-hardware.org/?probe=6743c7ca9d) | Aug 10, 2023 |
| Gigabyte      | AERO 15-WA                  | Notebook    | [bd9f5d0f39](https://linux-hardware.org/?probe=bd9f5d0f39) | Aug 10, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [23fc9401d3](https://linux-hardware.org/?probe=23fc9401d3) | Aug 10, 2023 |
| Dell          | 0MGK50 A01                  | Desktop     | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [4446f503d5](https://linux-hardware.org/?probe=4446f503d5) | Aug 10, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [13edff3291](https://linux-hardware.org/?probe=13edff3291) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [c5491b8e9f](https://linux-hardware.org/?probe=c5491b8e9f) | Aug 10, 2023 |
| HP            | 14                          | Notebook    | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [bb40aa6fd9](https://linux-hardware.org/?probe=bb40aa6fd9) | Aug 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0f34656484](https://linux-hardware.org/?probe=0f34656484) | Aug 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [09037ac346](https://linux-hardware.org/?probe=09037ac346) | Aug 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [466419add0](https://linux-hardware.org/?probe=466419add0) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [afa02e4c02](https://linux-hardware.org/?probe=afa02e4c02) | Aug 09, 2023 |
| Huanan        | X99-TF-Q GAMING V1.2        | Desktop     | [da612198cc](https://linux-hardware.org/?probe=da612198cc) | Aug 09, 2023 |
| Unknown       | HX90                        | Desktop     | [7a14bb927e](https://linux-hardware.org/?probe=7a14bb927e) | Aug 09, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [8f3bc0a06a](https://linux-hardware.org/?probe=8f3bc0a06a) | Aug 09, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| Dell          | 06CJMN A00                  | Desktop     | [cead9bd601](https://linux-hardware.org/?probe=cead9bd601) | Aug 09, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [6dd8126a05](https://linux-hardware.org/?probe=6dd8126a05) | Aug 09, 2023 |
| HP            | Notebook                    | Notebook    | [bac7155006](https://linux-hardware.org/?probe=bac7155006) | Aug 09, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [c801f4bbd0](https://linux-hardware.org/?probe=c801f4bbd0) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | Notebook    | [a8fc44190a](https://linux-hardware.org/?probe=a8fc44190a) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | Notebook    | [766e35e920](https://linux-hardware.org/?probe=766e35e920) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | Latitude 7320               | Notebook    | [6db1867722](https://linux-hardware.org/?probe=6db1867722) | Aug 09, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [82a8a2346a](https://linux-hardware.org/?probe=82a8a2346a) | Aug 08, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [7ce5fc846b](https://linux-hardware.org/?probe=7ce5fc846b) | Aug 08, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [ee7bcf8fe1](https://linux-hardware.org/?probe=ee7bcf8fe1) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [1105c8c2ea](https://linux-hardware.org/?probe=1105c8c2ea) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [c8553cabce](https://linux-hardware.org/?probe=c8553cabce) | Aug 08, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [72eb04ca17](https://linux-hardware.org/?probe=72eb04ca17) | Aug 08, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [914ff5745c](https://linux-hardware.org/?probe=914ff5745c) | Aug 08, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [8839aa58c4](https://linux-hardware.org/?probe=8839aa58c4) | Aug 08, 2023 |
| HP            | 3397                        | Desktop     | [d7edc80c00](https://linux-hardware.org/?probe=d7edc80c00) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1a3b5297dd](https://linux-hardware.org/?probe=1a3b5297dd) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [18208500ee](https://linux-hardware.org/?probe=18208500ee) | Aug 08, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [388bcf4158](https://linux-hardware.org/?probe=388bcf4158) | Aug 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5dfaa2b1c0](https://linux-hardware.org/?probe=5dfaa2b1c0) | Aug 08, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [0ee8428f91](https://linux-hardware.org/?probe=0ee8428f91) | Aug 07, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [e07624ae41](https://linux-hardware.org/?probe=e07624ae41) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [36b0caba9e](https://linux-hardware.org/?probe=36b0caba9e) | Aug 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [d989868a6b](https://linux-hardware.org/?probe=d989868a6b) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [8b5e74e190](https://linux-hardware.org/?probe=8b5e74e190) | Aug 07, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [0a1b8d0627](https://linux-hardware.org/?probe=0a1b8d0627) | Aug 07, 2023 |
| Timi          | A7S                         | Notebook    | [34a354df5a](https://linux-hardware.org/?probe=34a354df5a) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [b4b049b997](https://linux-hardware.org/?probe=b4b049b997) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8633bc5aa5](https://linux-hardware.org/?probe=8633bc5aa5) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [aabc0a8aee](https://linux-hardware.org/?probe=aabc0a8aee) | Aug 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3d4073bb1d](https://linux-hardware.org/?probe=3d4073bb1d) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [1134279f41](https://linux-hardware.org/?probe=1134279f41) | Aug 06, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c19229d536](https://linux-hardware.org/?probe=c19229d536) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [eed6ad702b](https://linux-hardware.org/?probe=eed6ad702b) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [8a3ba73fae](https://linux-hardware.org/?probe=8a3ba73fae) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c3df1aaae9](https://linux-hardware.org/?probe=c3df1aaae9) | Aug 06, 2023 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [572f537532](https://linux-hardware.org/?probe=572f537532) | Aug 06, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c003e20331](https://linux-hardware.org/?probe=c003e20331) | Aug 06, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [e71ac5ca78](https://linux-hardware.org/?probe=e71ac5ca78) | Aug 06, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | Notebook    | [27d1d39b58](https://linux-hardware.org/?probe=27d1d39b58) | Aug 06, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [f9d29dca0d](https://linux-hardware.org/?probe=f9d29dca0d) | Aug 06, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9fe9cf4748](https://linux-hardware.org/?probe=9fe9cf4748) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [56c7715a6d](https://linux-hardware.org/?probe=56c7715a6d) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6a9e7cc3e2](https://linux-hardware.org/?probe=6a9e7cc3e2) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | Notebook    | [61c1a104d2](https://linux-hardware.org/?probe=61c1a104d2) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [932391bfea](https://linux-hardware.org/?probe=932391bfea) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | Notebook    | [fe15934abe](https://linux-hardware.org/?probe=fe15934abe) | Aug 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2e8d48f9bc](https://linux-hardware.org/?probe=2e8d48f9bc) | Aug 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [1b9794e2e3](https://linux-hardware.org/?probe=1b9794e2e3) | Aug 06, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [b47eca38dc](https://linux-hardware.org/?probe=b47eca38dc) | Aug 06, 2023 |
| COMPUMAX C... | MOBIL                       | Notebook    | [60293c1ac3](https://linux-hardware.org/?probe=60293c1ac3) | Aug 06, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [4afe306798](https://linux-hardware.org/?probe=4afe306798) | Aug 05, 2023 |
| Dell          | Venue 8 Pro 5855            | Notebook    | [146fa40942](https://linux-hardware.org/?probe=146fa40942) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6af70944d8](https://linux-hardware.org/?probe=6af70944d8) | Aug 05, 2023 |
| Gateway       | SX2185                      | Desktop     | [a6df16b355](https://linux-hardware.org/?probe=a6df16b355) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [1790fa9d72](https://linux-hardware.org/?probe=1790fa9d72) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | Notebook    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude E6230              | Notebook    | [cc78868322](https://linux-hardware.org/?probe=cc78868322) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [4c1ef04fe9](https://linux-hardware.org/?probe=4c1ef04fe9) | Aug 05, 2023 |
| Multilaser    | PC13X                       | Notebook    | [2f79cffddd](https://linux-hardware.org/?probe=2f79cffddd) | Aug 05, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ea70e92c9a](https://linux-hardware.org/?probe=ea70e92c9a) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [40bc2f506a](https://linux-hardware.org/?probe=40bc2f506a) | Aug 05, 2023 |
| Dell          | Latitude E6220              | Notebook    | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [87fc943eb1](https://linux-hardware.org/?probe=87fc943eb1) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [364b15d850](https://linux-hardware.org/?probe=364b15d850) | Aug 05, 2023 |
| System76      | Darter Pro                  | Notebook    | [55a328cd9a](https://linux-hardware.org/?probe=55a328cd9a) | Aug 05, 2023 |
| Intel         | B75                         | Desktop     | [9411dd987c](https://linux-hardware.org/?probe=9411dd987c) | Aug 05, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [193262b7ea](https://linux-hardware.org/?probe=193262b7ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| Corsair       | Voyager a1600               | Notebook    | [6dea5f2c0c](https://linux-hardware.org/?probe=6dea5f2c0c) | Aug 04, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ccbf514dc7](https://linux-hardware.org/?probe=ccbf514dc7) | Aug 04, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [e6e6cc7b2e](https://linux-hardware.org/?probe=e6e6cc7b2e) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7bc7a7e01c](https://linux-hardware.org/?probe=7bc7a7e01c) | Aug 04, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | Desktop     | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [fcc05278d6](https://linux-hardware.org/?probe=fcc05278d6) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b8fa3962ed](https://linux-hardware.org/?probe=b8fa3962ed) | Aug 04, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [2af2b0aecb](https://linux-hardware.org/?probe=2af2b0aecb) | Aug 04, 2023 |
| Dell          | Latitude 7400               | Notebook    | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Lenovo        | 32DD SDK0J40697 WIN 3305... | Mini pc     | [a894ae9bfc](https://linux-hardware.org/?probe=a894ae9bfc) | Aug 04, 2023 |
| Dell          | Latitude 3420               | Notebook    | [cdecb64c4a](https://linux-hardware.org/?probe=cdecb64c4a) | Aug 04, 2023 |
| AZW           | GTR V02                     | Desktop     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [16511212ba](https://linux-hardware.org/?probe=16511212ba) | Aug 04, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [a02f0405a3](https://linux-hardware.org/?probe=a02f0405a3) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [de1c7d119e](https://linux-hardware.org/?probe=de1c7d119e) | Aug 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [b682f988e8](https://linux-hardware.org/?probe=b682f988e8) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| HP            | ENVY Notebook               | Notebook    | [90325282da](https://linux-hardware.org/?probe=90325282da) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [082f92da07](https://linux-hardware.org/?probe=082f92da07) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [1078db460a](https://linux-hardware.org/?probe=1078db460a) | Aug 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [4077d11575](https://linux-hardware.org/?probe=4077d11575) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [a260479012](https://linux-hardware.org/?probe=a260479012) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3c3d90d709](https://linux-hardware.org/?probe=3c3d90d709) | Aug 04, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [8f3b8dea26](https://linux-hardware.org/?probe=8f3b8dea26) | Aug 04, 2023 |
| ASUSTek       | UX490UAR                    | Notebook    | [6a305978e3](https://linux-hardware.org/?probe=6a305978e3) | Aug 03, 2023 |
| Dell          | Latitude E6510              | Notebook    | [b32213c71d](https://linux-hardware.org/?probe=b32213c71d) | Aug 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c0a4bb6c7e](https://linux-hardware.org/?probe=c0a4bb6c7e) | Aug 03, 2023 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [aa6b646b24](https://linux-hardware.org/?probe=aa6b646b24) | Aug 03, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [620397fdc9](https://linux-hardware.org/?probe=620397fdc9) | Aug 03, 2023 |
| HP            | 1791                        | Desktop     | [61285d3724](https://linux-hardware.org/?probe=61285d3724) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Notebook    | [882d963e19](https://linux-hardware.org/?probe=882d963e19) | Aug 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [0cf8e99478](https://linux-hardware.org/?probe=0cf8e99478) | Aug 03, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [2d10ecdff1](https://linux-hardware.org/?probe=2d10ecdff1) | Aug 03, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [80498caa0d](https://linux-hardware.org/?probe=80498caa0d) | Aug 03, 2023 |
| Microsoft     | Surface Pro 7+              | Tablet      | [1a39b68c7f](https://linux-hardware.org/?probe=1a39b68c7f) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Notebook    | [38d0bcf5d1](https://linux-hardware.org/?probe=38d0bcf5d1) | Aug 03, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e066712070](https://linux-hardware.org/?probe=e066712070) | Aug 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7d96f87e00](https://linux-hardware.org/?probe=7d96f87e00) | Aug 03, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [a956adcb38](https://linux-hardware.org/?probe=a956adcb38) | Aug 03, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [219278bb56](https://linux-hardware.org/?probe=219278bb56) | Aug 03, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [c741db51a0](https://linux-hardware.org/?probe=c741db51a0) | Aug 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7df997ee08](https://linux-hardware.org/?probe=7df997ee08) | Aug 03, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [6478fd4e76](https://linux-hardware.org/?probe=6478fd4e76) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [25dcc9a7c5](https://linux-hardware.org/?probe=25dcc9a7c5) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [3f5df1b569](https://linux-hardware.org/?probe=3f5df1b569) | Aug 03, 2023 |
| Dell          | Latitude E7470              | Notebook    | [7c8c07214a](https://linux-hardware.org/?probe=7c8c07214a) | Aug 03, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [877d855f27](https://linux-hardware.org/?probe=877d855f27) | Aug 02, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [fa53c99b17](https://linux-hardware.org/?probe=fa53c99b17) | Aug 02, 2023 |
| Dell          | Latitude E7470              | Notebook    | [b672c65f9b](https://linux-hardware.org/?probe=b672c65f9b) | Aug 02, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [d0bad7993f](https://linux-hardware.org/?probe=d0bad7993f) | Aug 02, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [2c10cb0378](https://linux-hardware.org/?probe=2c10cb0378) | Aug 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c66b1ed22c](https://linux-hardware.org/?probe=c66b1ed22c) | Aug 02, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [0e3cacbea1](https://linux-hardware.org/?probe=0e3cacbea1) | Aug 02, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [b10154befd](https://linux-hardware.org/?probe=b10154befd) | Aug 02, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [883a115efd](https://linux-hardware.org/?probe=883a115efd) | Aug 02, 2023 |
| Dell          | System XPS L322X            | Notebook    | [dbe168d1a1](https://linux-hardware.org/?probe=dbe168d1a1) | Aug 02, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [2d1e78ec7e](https://linux-hardware.org/?probe=2d1e78ec7e) | Aug 02, 2023 |
| ASUSTek       | X750JN                      | Notebook    | [6f7dc2198b](https://linux-hardware.org/?probe=6f7dc2198b) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | Notebook    | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [517b498a25](https://linux-hardware.org/?probe=517b498a25) | Aug 02, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [18396303b8](https://linux-hardware.org/?probe=18396303b8) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [5bbfe225b6](https://linux-hardware.org/?probe=5bbfe225b6) | Aug 02, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2ff30156cf](https://linux-hardware.org/?probe=2ff30156cf) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8c9bca1e79](https://linux-hardware.org/?probe=8c9bca1e79) | Aug 02, 2023 |
| Dell          | XPS 9320                    | Notebook    | [3abc4aaf82](https://linux-hardware.org/?probe=3abc4aaf82) | Aug 02, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [f37f2f707b](https://linux-hardware.org/?probe=f37f2f707b) | Aug 02, 2023 |
| HP            | Dragonfly Pro               | Notebook    | [630670f052](https://linux-hardware.org/?probe=630670f052) | Aug 01, 2023 |
| Dell          | Precision 7550              | Notebook    | [ab0d21bb4e](https://linux-hardware.org/?probe=ab0d21bb4e) | Aug 01, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [2d7cbca56b](https://linux-hardware.org/?probe=2d7cbca56b) | Aug 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [8353d48977](https://linux-hardware.org/?probe=8353d48977) | Aug 01, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [abe7173905](https://linux-hardware.org/?probe=abe7173905) | Aug 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [13d25503d7](https://linux-hardware.org/?probe=13d25503d7) | Aug 01, 2023 |
| Dell          | Inspiron 15-3573            | Notebook    | [e29b3656ee](https://linux-hardware.org/?probe=e29b3656ee) | Aug 01, 2023 |
| HP            | ProBook 6475b               | Notebook    | [c3cfc235fe](https://linux-hardware.org/?probe=c3cfc235fe) | Aug 01, 2023 |
| ASRock        | H61M/U3S3                   | Desktop     | [33c887e577](https://linux-hardware.org/?probe=33c887e577) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [752821ae1a](https://linux-hardware.org/?probe=752821ae1a) | Aug 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [7a5ef06c39](https://linux-hardware.org/?probe=7a5ef06c39) | Aug 01, 2023 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [287ea63732](https://linux-hardware.org/?probe=287ea63732) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [b847ac4535](https://linux-hardware.org/?probe=b847ac4535) | Aug 01, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70b94de26b](https://linux-hardware.org/?probe=70b94de26b) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [afbf5d75c1](https://linux-hardware.org/?probe=afbf5d75c1) | Jul 31, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [1dfc12fc6c](https://linux-hardware.org/?probe=1dfc12fc6c) | Jul 31, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [7584e2db20](https://linux-hardware.org/?probe=7584e2db20) | Jul 31, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [df2a633f24](https://linux-hardware.org/?probe=df2a633f24) | Jul 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [a7cf8e8ef1](https://linux-hardware.org/?probe=a7cf8e8ef1) | Jul 31, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [9b9830aedf](https://linux-hardware.org/?probe=9b9830aedf) | Jul 31, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b42946849e](https://linux-hardware.org/?probe=b42946849e) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [49a431c092](https://linux-hardware.org/?probe=49a431c092) | Jul 31, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a3bbf1ecd0](https://linux-hardware.org/?probe=a3bbf1ecd0) | Jul 31, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [08e20bb994](https://linux-hardware.org/?probe=08e20bb994) | Jul 31, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [bb88f3afdc](https://linux-hardware.org/?probe=bb88f3afdc) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7890c76098](https://linux-hardware.org/?probe=7890c76098) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS20D00     | Notebook    | [4ef8aa09c6](https://linux-hardware.org/?probe=4ef8aa09c6) | Jul 31, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [beea8be008](https://linux-hardware.org/?probe=beea8be008) | Jul 30, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [9a3416654f](https://linux-hardware.org/?probe=9a3416654f) | Jul 30, 2023 |
| HP            | 8056                        | Desktop     | [3a98a11778](https://linux-hardware.org/?probe=3a98a11778) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5bf8462b77](https://linux-hardware.org/?probe=5bf8462b77) | Jul 30, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| HP            | 0AECh D                     | Desktop     | [50c84d005e](https://linux-hardware.org/?probe=50c84d005e) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [6bf2e91f31](https://linux-hardware.org/?probe=6bf2e91f31) | Jul 30, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7dcc58cdf2](https://linux-hardware.org/?probe=7dcc58cdf2) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [0f9accc3e8](https://linux-hardware.org/?probe=0f9accc3e8) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [f641b9c622](https://linux-hardware.org/?probe=f641b9c622) | Jul 30, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [63b8471789](https://linux-hardware.org/?probe=63b8471789) | Jul 30, 2023 |
| Lenovo        | WEI6 15 ITL 82F2            | Notebook    | [d30f44ebbb](https://linux-hardware.org/?probe=d30f44ebbb) | Jul 30, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [d84e6d9683](https://linux-hardware.org/?probe=d84e6d9683) | Jul 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [d9d3f5bce4](https://linux-hardware.org/?probe=d9d3f5bce4) | Jul 30, 2023 |
| Sony          | SVE14A2V2RS                 | Notebook    | [adc151e590](https://linux-hardware.org/?probe=adc151e590) | Jul 30, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [8e59554b8d](https://linux-hardware.org/?probe=8e59554b8d) | Jul 30, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| HP            | 8617                        | Desktop     | [0c3ee28cd8](https://linux-hardware.org/?probe=0c3ee28cd8) | Jul 30, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [6c5528a787](https://linux-hardware.org/?probe=6c5528a787) | Jul 30, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [4fb6a46f65](https://linux-hardware.org/?probe=4fb6a46f65) | Jul 30, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [529bf65ac4](https://linux-hardware.org/?probe=529bf65ac4) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [df34eb4472](https://linux-hardware.org/?probe=df34eb4472) | Jul 30, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [0449350f3d](https://linux-hardware.org/?probe=0449350f3d) | Jul 30, 2023 |
| HP            | ENVY Laptop 17-cg1xxx       | Notebook    | [16545b3964](https://linux-hardware.org/?probe=16545b3964) | Jul 30, 2023 |
| Lenovo        | ThinkPad T490 20N3S5XF01    | Notebook    | [942cb3149b](https://linux-hardware.org/?probe=942cb3149b) | Jul 29, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [9469c1037c](https://linux-hardware.org/?probe=9469c1037c) | Jul 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [cd073a7899](https://linux-hardware.org/?probe=cd073a7899) | Jul 29, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [10b634ac99](https://linux-hardware.org/?probe=10b634ac99) | Jul 29, 2023 |
| HP            | Beats 15                    | Notebook    | [933bd63249](https://linux-hardware.org/?probe=933bd63249) | Jul 29, 2023 |
| HP            | Beats 15                    | Notebook    | [acea7d6786](https://linux-hardware.org/?probe=acea7d6786) | Jul 29, 2023 |
| HP            | 3397                        | Desktop     | [98e4e362d9](https://linux-hardware.org/?probe=98e4e362d9) | Jul 29, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [dbcda8f4d0](https://linux-hardware.org/?probe=dbcda8f4d0) | Jul 29, 2023 |
| Lenovo        | Unknown                     | Notebook    | [a1dac68b95](https://linux-hardware.org/?probe=a1dac68b95) | Jul 29, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [32ad81bc5d](https://linux-hardware.org/?probe=32ad81bc5d) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [4baa3fe63b](https://linux-hardware.org/?probe=4baa3fe63b) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [254354d9aa](https://linux-hardware.org/?probe=254354d9aa) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [95e189ee7a](https://linux-hardware.org/?probe=95e189ee7a) | Jul 29, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [9669adfa57](https://linux-hardware.org/?probe=9669adfa57) | Jul 29, 2023 |
| HP            | ProBook 4530s               | Notebook    | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [580c4fb755](https://linux-hardware.org/?probe=580c4fb755) | Jul 29, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [733695ae93](https://linux-hardware.org/?probe=733695ae93) | Jul 29, 2023 |
| Samsung       | 550XDA                      | Notebook    | [c140c9176e](https://linux-hardware.org/?probe=c140c9176e) | Jul 29, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [0728a96775](https://linux-hardware.org/?probe=0728a96775) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [dd2b310ecf](https://linux-hardware.org/?probe=dd2b310ecf) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b8e059a47d](https://linux-hardware.org/?probe=b8e059a47d) | Jul 29, 2023 |
| GPD           | G1621-02                    | Notebook    | [1710e0f480](https://linux-hardware.org/?probe=1710e0f480) | Jul 29, 2023 |
| Dell          | XPS 9320                    | Notebook    | [4000df5584](https://linux-hardware.org/?probe=4000df5584) | Jul 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [9416ce803c](https://linux-hardware.org/?probe=9416ce803c) | Jul 28, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [21aa433472](https://linux-hardware.org/?probe=21aa433472) | Jul 28, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Notebook    | [75e93aaa88](https://linux-hardware.org/?probe=75e93aaa88) | Jul 28, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [205f3a047f](https://linux-hardware.org/?probe=205f3a047f) | Jul 28, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [dcd24dfdc7](https://linux-hardware.org/?probe=dcd24dfdc7) | Jul 28, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [ea4fee91b6](https://linux-hardware.org/?probe=ea4fee91b6) | Jul 28, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Notebook    | [730caebd96](https://linux-hardware.org/?probe=730caebd96) | Jul 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [1c3edafdf4](https://linux-hardware.org/?probe=1c3edafdf4) | Jul 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [ba7c69f7e0](https://linux-hardware.org/?probe=ba7c69f7e0) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2e6ab71954](https://linux-hardware.org/?probe=2e6ab71954) | Jul 28, 2023 |
| ASUSTek       | WS C246 PRO                 | Desktop     | [cfffc2ba92](https://linux-hardware.org/?probe=cfffc2ba92) | Jul 28, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [4439f26a90](https://linux-hardware.org/?probe=4439f26a90) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [2e0e88694a](https://linux-hardware.org/?probe=2e0e88694a) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [7864dbf54c](https://linux-hardware.org/?probe=7864dbf54c) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f7c6565b62](https://linux-hardware.org/?probe=f7c6565b62) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [49daa98623](https://linux-hardware.org/?probe=49daa98623) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [058f75de84](https://linux-hardware.org/?probe=058f75de84) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c26daef72c](https://linux-hardware.org/?probe=c26daef72c) | Jul 28, 2023 |
| MSI           | Z270 GAMING PLUS            | Desktop     | [cc489fad92](https://linux-hardware.org/?probe=cc489fad92) | Jul 28, 2023 |
| ASUSTek       | P9D-I Series                | Server      | [b8af713f2c](https://linux-hardware.org/?probe=b8af713f2c) | Jul 28, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [b784cbe3ab](https://linux-hardware.org/?probe=b784cbe3ab) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4bd819d37b](https://linux-hardware.org/?probe=4bd819d37b) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [6287e66ff2](https://linux-hardware.org/?probe=6287e66ff2) | Jul 27, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [da2904da80](https://linux-hardware.org/?probe=da2904da80) | Jul 27, 2023 |
| Lenovo        | ThinkPad E490 20N80029RT    | Notebook    | [69cf27eaae](https://linux-hardware.org/?probe=69cf27eaae) | Jul 27, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [abf0e5979c](https://linux-hardware.org/?probe=abf0e5979c) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [1b3e699a2a](https://linux-hardware.org/?probe=1b3e699a2a) | Jul 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [2c2dfaa670](https://linux-hardware.org/?probe=2c2dfaa670) | Jul 27, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [865315bd06](https://linux-hardware.org/?probe=865315bd06) | Jul 27, 2023 |
| Dell          | Latitude 5530               | Notebook    | [165d2cd3b1](https://linux-hardware.org/?probe=165d2cd3b1) | Jul 27, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [56489a32b2](https://linux-hardware.org/?probe=56489a32b2) | Jul 27, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [aad7b03818](https://linux-hardware.org/?probe=aad7b03818) | Jul 27, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [02cf19407b](https://linux-hardware.org/?probe=02cf19407b) | Jul 26, 2023 |
| HP            | 829A                        | Mini pc     | [c78cd4ea03](https://linux-hardware.org/?probe=c78cd4ea03) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [32b57e4adb](https://linux-hardware.org/?probe=32b57e4adb) | Jul 26, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a9333607eb](https://linux-hardware.org/?probe=a9333607eb) | Jul 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b8b95820c1](https://linux-hardware.org/?probe=b8b95820c1) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [aed4f431ec](https://linux-hardware.org/?probe=aed4f431ec) | Jul 26, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [8daa291377](https://linux-hardware.org/?probe=8daa291377) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | Notebook    | [2e810b1c93](https://linux-hardware.org/?probe=2e810b1c93) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | Notebook    | [4171fc8925](https://linux-hardware.org/?probe=4171fc8925) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f375185ce4](https://linux-hardware.org/?probe=f375185ce4) | Jul 26, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9b8234d640](https://linux-hardware.org/?probe=9b8234d640) | Jul 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9b1ae569c1](https://linux-hardware.org/?probe=9b1ae569c1) | Jul 26, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [5f44d0b1d8](https://linux-hardware.org/?probe=5f44d0b1d8) | Jul 26, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [30cb22d368](https://linux-hardware.org/?probe=30cb22d368) | Jul 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [f321614376](https://linux-hardware.org/?probe=f321614376) | Jul 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [b731684f10](https://linux-hardware.org/?probe=b731684f10) | Jul 25, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [b28bc4ba91](https://linux-hardware.org/?probe=b28bc4ba91) | Jul 25, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [067a1b82b7](https://linux-hardware.org/?probe=067a1b82b7) | Jul 25, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [62bcc903fd](https://linux-hardware.org/?probe=62bcc903fd) | Jul 25, 2023 |
| Intel         | NUC5i5MYBE H47797-206       | Mini pc     | [393855b913](https://linux-hardware.org/?probe=393855b913) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bd31324aeb](https://linux-hardware.org/?probe=bd31324aeb) | Jul 25, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [12902831a7](https://linux-hardware.org/?probe=12902831a7) | Jul 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [31b7924358](https://linux-hardware.org/?probe=31b7924358) | Jul 25, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [da046587dc](https://linux-hardware.org/?probe=da046587dc) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [8cf3728f9b](https://linux-hardware.org/?probe=8cf3728f9b) | Jul 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [a4e9cddcdb](https://linux-hardware.org/?probe=a4e9cddcdb) | Jul 25, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0ecaae8a05](https://linux-hardware.org/?probe=0ecaae8a05) | Jul 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7ee6422d01](https://linux-hardware.org/?probe=7ee6422d01) | Jul 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a7d120e20a](https://linux-hardware.org/?probe=a7d120e20a) | Jul 24, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c49c2e7a5a](https://linux-hardware.org/?probe=c49c2e7a5a) | Jul 24, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [66ab03991c](https://linux-hardware.org/?probe=66ab03991c) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [53de15710b](https://linux-hardware.org/?probe=53de15710b) | Jul 24, 2023 |
| Fujitsu       | CELSIUS H700                | Notebook    | [8a23e1d76a](https://linux-hardware.org/?probe=8a23e1d76a) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [61646d77f1](https://linux-hardware.org/?probe=61646d77f1) | Jul 24, 2023 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [daf09efe6e](https://linux-hardware.org/?probe=daf09efe6e) | Jul 24, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [3086b1ce57](https://linux-hardware.org/?probe=3086b1ce57) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [8ecb2eb1fc](https://linux-hardware.org/?probe=8ecb2eb1fc) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [84c7ea08c6](https://linux-hardware.org/?probe=84c7ea08c6) | Jul 24, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [60b9e2fbc9](https://linux-hardware.org/?probe=60b9e2fbc9) | Jul 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b892c011a8](https://linux-hardware.org/?probe=b892c011a8) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [4f06d87bd5](https://linux-hardware.org/?probe=4f06d87bd5) | Jul 24, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [2afa2c2afe](https://linux-hardware.org/?probe=2afa2c2afe) | Jul 23, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [95290b34e3](https://linux-hardware.org/?probe=95290b34e3) | Jul 23, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [e1f3c75353](https://linux-hardware.org/?probe=e1f3c75353) | Jul 23, 2023 |
| Dell          | 0YGR09 A00                  | All in one  | [256d182fcd](https://linux-hardware.org/?probe=256d182fcd) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [04982390e0](https://linux-hardware.org/?probe=04982390e0) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b13bb2310f](https://linux-hardware.org/?probe=b13bb2310f) | Jul 23, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| ASUSTek       | H170M-PLUS                  | Notebook    | [f17fd3bbe1](https://linux-hardware.org/?probe=f17fd3bbe1) | Jul 23, 2023 |
| HP            | 250 G1                      | Notebook    | [deab96c404](https://linux-hardware.org/?probe=deab96c404) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [ff5e295a5d](https://linux-hardware.org/?probe=ff5e295a5d) | Jul 23, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [09b55ea163](https://linux-hardware.org/?probe=09b55ea163) | Jul 23, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [95b700531a](https://linux-hardware.org/?probe=95b700531a) | Jul 23, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [9a2136d9ef](https://linux-hardware.org/?probe=9a2136d9ef) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [28340d4ad4](https://linux-hardware.org/?probe=28340d4ad4) | Jul 23, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [6323d6b43c](https://linux-hardware.org/?probe=6323d6b43c) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [49cc99fa7e](https://linux-hardware.org/?probe=49cc99fa7e) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [994ae7ffec](https://linux-hardware.org/?probe=994ae7ffec) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [9c92b34677](https://linux-hardware.org/?probe=9c92b34677) | Jul 23, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [eef08e2598](https://linux-hardware.org/?probe=eef08e2598) | Jul 22, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | Notebook    | [f12c3b23e5](https://linux-hardware.org/?probe=f12c3b23e5) | Jul 22, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [3ed87bb81b](https://linux-hardware.org/?probe=3ed87bb81b) | Jul 22, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [b957598d8e](https://linux-hardware.org/?probe=b957598d8e) | Jul 22, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [ea078c7fb9](https://linux-hardware.org/?probe=ea078c7fb9) | Jul 22, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [8c75932124](https://linux-hardware.org/?probe=8c75932124) | Jul 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [51ca7593a6](https://linux-hardware.org/?probe=51ca7593a6) | Jul 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [931df813b1](https://linux-hardware.org/?probe=931df813b1) | Jul 22, 2023 |
| Dell          | Precision M4700             | Notebook    | [0a5346a25d](https://linux-hardware.org/?probe=0a5346a25d) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [ba42ca5ace](https://linux-hardware.org/?probe=ba42ca5ace) | Jul 22, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [ec2be7713c](https://linux-hardware.org/?probe=ec2be7713c) | Jul 22, 2023 |
| HP            | Notebook                    | Notebook    | [fde29b5a32](https://linux-hardware.org/?probe=fde29b5a32) | Jul 22, 2023 |
| Notebook      | PE60RNE_RND_RNC             | Notebook    | [5f2993b629](https://linux-hardware.org/?probe=5f2993b629) | Jul 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c1e386e9cc](https://linux-hardware.org/?probe=c1e386e9cc) | Jul 22, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [b132b3f39c](https://linux-hardware.org/?probe=b132b3f39c) | Jul 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [8c79a454ff](https://linux-hardware.org/?probe=8c79a454ff) | Jul 21, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | Notebook    | [27b5dabe8d](https://linux-hardware.org/?probe=27b5dabe8d) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [d16a211675](https://linux-hardware.org/?probe=d16a211675) | Jul 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [e222d263f6](https://linux-hardware.org/?probe=e222d263f6) | Jul 21, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | Desktop     | [ea68d9762b](https://linux-hardware.org/?probe=ea68d9762b) | Jul 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [fbd6b6197b](https://linux-hardware.org/?probe=fbd6b6197b) | Jul 21, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [355ac636c1](https://linux-hardware.org/?probe=355ac636c1) | Jul 21, 2023 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [0026c9edf0](https://linux-hardware.org/?probe=0026c9edf0) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [32ec9929c9](https://linux-hardware.org/?probe=32ec9929c9) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [fa4def4ece](https://linux-hardware.org/?probe=fa4def4ece) | Jul 21, 2023 |
| Avell High... | B.ON                        | Notebook    | [8269a683ef](https://linux-hardware.org/?probe=8269a683ef) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [d163198c13](https://linux-hardware.org/?probe=d163198c13) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [b541d17031](https://linux-hardware.org/?probe=b541d17031) | Jul 21, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [cf2d22469b](https://linux-hardware.org/?probe=cf2d22469b) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [df2bfbf3e1](https://linux-hardware.org/?probe=df2bfbf3e1) | Jul 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [de8a458cb8](https://linux-hardware.org/?probe=de8a458cb8) | Jul 20, 2023 |
| MSI           | PRO B550-VC                 | Desktop     | [5439295c30](https://linux-hardware.org/?probe=5439295c30) | Jul 20, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [6bc352838a](https://linux-hardware.org/?probe=6bc352838a) | Jul 20, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [dd441dfa0d](https://linux-hardware.org/?probe=dd441dfa0d) | Jul 20, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [e9c650988e](https://linux-hardware.org/?probe=e9c650988e) | Jul 20, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [18a6e9f055](https://linux-hardware.org/?probe=18a6e9f055) | Jul 20, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [cfbad825dc](https://linux-hardware.org/?probe=cfbad825dc) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [c7e1f17f9e](https://linux-hardware.org/?probe=c7e1f17f9e) | Jul 20, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [af457a5412](https://linux-hardware.org/?probe=af457a5412) | Jul 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [e99bf7a4be](https://linux-hardware.org/?probe=e99bf7a4be) | Jul 20, 2023 |
| Dell          | Latitude 5420               | Notebook    | [ea97d72c47](https://linux-hardware.org/?probe=ea97d72c47) | Jul 20, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [f92f9065bc](https://linux-hardware.org/?probe=f92f9065bc) | Jul 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [fc26baabc9](https://linux-hardware.org/?probe=fc26baabc9) | Jul 19, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [b3a1dbc5d0](https://linux-hardware.org/?probe=b3a1dbc5d0) | Jul 19, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [fd2864f7e1](https://linux-hardware.org/?probe=fd2864f7e1) | Jul 19, 2023 |
| Chuwi         | Hi10 X                      | Tablet      | [a2f35813e6](https://linux-hardware.org/?probe=a2f35813e6) | Jul 19, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0C800     | Notebook    | [b894a6d96b](https://linux-hardware.org/?probe=b894a6d96b) | Jul 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [38c5f4d547](https://linux-hardware.org/?probe=38c5f4d547) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [e2cf7ed35f](https://linux-hardware.org/?probe=e2cf7ed35f) | Jul 19, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [22bbaa5937](https://linux-hardware.org/?probe=22bbaa5937) | Jul 19, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [173929b667](https://linux-hardware.org/?probe=173929b667) | Jul 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [360ee7202f](https://linux-hardware.org/?probe=360ee7202f) | Jul 18, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [ba24f3bb61](https://linux-hardware.org/?probe=ba24f3bb61) | Jul 18, 2023 |
| Dell          | 0MN1TX A01                  | Desktop     | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | Desktop     | [0296e5fd5c](https://linux-hardware.org/?probe=0296e5fd5c) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5d3e13fc77](https://linux-hardware.org/?probe=5d3e13fc77) | Jul 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [96585144ab](https://linux-hardware.org/?probe=96585144ab) | Jul 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [ea47e53a45](https://linux-hardware.org/?probe=ea47e53a45) | Jul 18, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [14478a9226](https://linux-hardware.org/?probe=14478a9226) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3618885533](https://linux-hardware.org/?probe=3618885533) | Jul 18, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [d0fff20fb0](https://linux-hardware.org/?probe=d0fff20fb0) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [c4ab55ea69](https://linux-hardware.org/?probe=c4ab55ea69) | Jul 18, 2023 |
| ASUSTek       | M11AD                       | Desktop     | [4019d4eb57](https://linux-hardware.org/?probe=4019d4eb57) | Jul 18, 2023 |
| MSI           | IONA                        | Desktop     | [7b8b6c38e1](https://linux-hardware.org/?probe=7b8b6c38e1) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [bb84df2364](https://linux-hardware.org/?probe=bb84df2364) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [b8caf7c9a3](https://linux-hardware.org/?probe=b8caf7c9a3) | Jul 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [fe1ab04658](https://linux-hardware.org/?probe=fe1ab04658) | Jul 18, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [e0303e4012](https://linux-hardware.org/?probe=e0303e4012) | Jul 17, 2023 |
| HP            | 3048h                       | Desktop     | [ad7b0d8c8d](https://linux-hardware.org/?probe=ad7b0d8c8d) | Jul 17, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [44ac31ab5e](https://linux-hardware.org/?probe=44ac31ab5e) | Jul 17, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [60d7a077dc](https://linux-hardware.org/?probe=60d7a077dc) | Jul 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [14defb538e](https://linux-hardware.org/?probe=14defb538e) | Jul 17, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [3a7fbf07fa](https://linux-hardware.org/?probe=3a7fbf07fa) | Jul 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [2bda9f913a](https://linux-hardware.org/?probe=2bda9f913a) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [3de307450d](https://linux-hardware.org/?probe=3de307450d) | Jul 17, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9d835f25a7](https://linux-hardware.org/?probe=9d835f25a7) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [5633b6ed54](https://linux-hardware.org/?probe=5633b6ed54) | Jul 17, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [7284e87529](https://linux-hardware.org/?probe=7284e87529) | Jul 17, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [49e298a314](https://linux-hardware.org/?probe=49e298a314) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [d8595efd58](https://linux-hardware.org/?probe=d8595efd58) | Jul 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [6039e0f3c4](https://linux-hardware.org/?probe=6039e0f3c4) | Jul 17, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [04dce054f4](https://linux-hardware.org/?probe=04dce054f4) | Jul 17, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [a097322114](https://linux-hardware.org/?probe=a097322114) | Jul 17, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | Notebook    | [9c1cb1fd39](https://linux-hardware.org/?probe=9c1cb1fd39) | Jul 16, 2023 |
| Gigabyte      | AORUS 17 YE5                | Notebook    | [9c17ae5e55](https://linux-hardware.org/?probe=9c17ae5e55) | Jul 16, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [07161141b4](https://linux-hardware.org/?probe=07161141b4) | Jul 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [ec4db25eb9](https://linux-hardware.org/?probe=ec4db25eb9) | Jul 16, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [99b59160a1](https://linux-hardware.org/?probe=99b59160a1) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [999de9eeb2](https://linux-hardware.org/?probe=999de9eeb2) | Jul 16, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [65afe9f74b](https://linux-hardware.org/?probe=65afe9f74b) | Jul 16, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [46a3598028](https://linux-hardware.org/?probe=46a3598028) | Jul 16, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | Notebook    | [1a0f8c842b](https://linux-hardware.org/?probe=1a0f8c842b) | Jul 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [0093aba5fd](https://linux-hardware.org/?probe=0093aba5fd) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6b4e2c6a3e](https://linux-hardware.org/?probe=6b4e2c6a3e) | Jul 16, 2023 |
| MSI           | 2A9C                        | Desktop     | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| Compaq        | 420                         | Notebook    | [e5b8695df7](https://linux-hardware.org/?probe=e5b8695df7) | Jul 16, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [2278b34727](https://linux-hardware.org/?probe=2278b34727) | Jul 16, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [c1834b63c2](https://linux-hardware.org/?probe=c1834b63c2) | Jul 16, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [5bf40815d5](https://linux-hardware.org/?probe=5bf40815d5) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8c3486fa69](https://linux-hardware.org/?probe=8c3486fa69) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b7992c5de7](https://linux-hardware.org/?probe=b7992c5de7) | Jul 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [069bfd995c](https://linux-hardware.org/?probe=069bfd995c) | Jul 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f4bcea4686](https://linux-hardware.org/?probe=f4bcea4686) | Jul 15, 2023 |
| HP            | ZBook Power 15.6 inch G1... | Notebook    | [c2042a2e0e](https://linux-hardware.org/?probe=c2042a2e0e) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [ba3be987e8](https://linux-hardware.org/?probe=ba3be987e8) | Jul 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d2b32f5512](https://linux-hardware.org/?probe=d2b32f5512) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [3577bb1c8f](https://linux-hardware.org/?probe=3577bb1c8f) | Jul 15, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [3becbb23af](https://linux-hardware.org/?probe=3becbb23af) | Jul 15, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [d7512ceea8](https://linux-hardware.org/?probe=d7512ceea8) | Jul 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [14bae4d3e7](https://linux-hardware.org/?probe=14bae4d3e7) | Jul 15, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7872b8a730](https://linux-hardware.org/?probe=7872b8a730) | Jul 15, 2023 |
| Gateway       | SX2185                      | Desktop     | [1fe932f485](https://linux-hardware.org/?probe=1fe932f485) | Jul 15, 2023 |
| Gateway       | SX2185                      | Desktop     | [00e7bb0f9f](https://linux-hardware.org/?probe=00e7bb0f9f) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [fab0c2fb26](https://linux-hardware.org/?probe=fab0c2fb26) | Jul 15, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [94f963ff8c](https://linux-hardware.org/?probe=94f963ff8c) | Jul 15, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [f25464fb37](https://linux-hardware.org/?probe=f25464fb37) | Jul 15, 2023 |
| Dell          | G5 5505                     | Notebook    | [ba144013b3](https://linux-hardware.org/?probe=ba144013b3) | Jul 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_38/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 6.2.9-300.fc38.x86_64               | 229       | 10.23%  |
| 6.2.15-300.fc38.x86_64              | 228       | 10.19%  |
| 6.3.8-200.fc38.x86_64               | 208       | 9.29%   |
| 6.2.14-300.fc38.x86_64              | 151       | 6.75%   |
| 6.2.11-300.fc38.x86_64              | 133       | 5.94%   |
| 6.3.12-200.fc38.x86_64              | 119       | 5.32%   |
| 6.4.11-200.fc38.x86_64              | 90        | 4.02%   |
| 6.4.6-200.fc38.x86_64               | 89        | 3.98%   |
| 6.3.11-200.fc38.x86_64              | 88        | 3.93%   |
| 6.4.7-200.fc38.x86_64               | 75        | 3.35%   |
| 6.3.5-200.fc38.x86_64               | 75        | 3.35%   |
| 6.4.12-200.fc38.x86_64              | 72        | 3.22%   |
| 6.2.13-300.fc38.x86_64              | 72        | 3.22%   |
| 6.4.10-200.fc38.x86_64              | 68        | 3.04%   |
| 6.3.6-200.fc38.x86_64               | 62        | 2.77%   |
| 6.4.13-200.fc38.x86_64              | 61        | 2.73%   |
| 6.2.12-300.fc38.x86_64              | 57        | 2.55%   |
| 6.4.4-200.fc38.x86_64               | 51        | 2.28%   |
| 6.3.4-201.fc38.x86_64               | 50        | 2.23%   |
| 6.3.7-200.fc38.x86_64               | 49        | 2.19%   |
| 6.4.9-200.fc38.x86_64               | 42        | 1.88%   |
| 6.2.8-300.fc38.x86_64               | 14        | 0.63%   |
| 6.2.6-300.fc38.x86_64               | 12        | 0.54%   |
| 6.4.8-200.fc38.x86_64               | 11        | 0.49%   |
| 6.2.10-300.fc38.x86_64              | 10        | 0.45%   |
| 6.2.7-300.fc38.x86_64               | 7         | 0.31%   |
| 6.2.2-301.fc38.x86_64               | 7         | 0.31%   |
| 6.3.3-200.fc38.x86_64               | 6         | 0.27%   |
| 6.2.15-703.inttf.fc38.x86_64        | 6         | 0.27%   |
| 6.2.0-63.fc38.x86_64                | 4         | 0.18%   |
| 6.3.10-200.fc38.x86_64              | 3         | 0.13%   |
| 6.2.2-300.fc38.x86_64               | 3         | 0.13%   |
| 6.4.14-200.fc38.x86_64              | 2         | 0.09%   |
| 6.4.0-0.rc4.334.vanilla.fc38.x86_64 | 2         | 0.09%   |
| 6.3.1-200.fc38.x86_64               | 2         | 0.09%   |
| 6.2.9-300.fc38.aarch64              | 2         | 0.09%   |
| 6.2.5-300.fc38.x86_64               | 2         | 0.09%   |
| 6.2.11-703.inttf.fc38.x86_64        | 2         | 0.09%   |
| 6.1.26-200.fc38.x86_64              | 2         | 0.09%   |
| 6.5.0-61.rog.fc38.x86_64            | 1         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.15  | 235       | 10.51%  |
| 6.2.9   | 231       | 10.33%  |
| 6.3.8   | 210       | 9.39%   |
| 6.2.14  | 153       | 6.84%   |
| 6.2.11  | 135       | 6.03%   |
| 6.3.12  | 119       | 5.32%   |
| 6.4.6   | 90        | 4.02%   |
| 6.4.11  | 90        | 4.02%   |
| 6.3.11  | 89        | 3.98%   |
| 6.4.7   | 77        | 3.44%   |
| 6.3.5   | 75        | 3.35%   |
| 6.4.12  | 73        | 3.26%   |
| 6.2.13  | 72        | 3.22%   |
| 6.4.10  | 70        | 3.13%   |
| 6.3.6   | 63        | 2.82%   |
| 6.4.13  | 61        | 2.73%   |
| 6.2.12  | 57        | 2.55%   |
| 6.4.4   | 53        | 2.37%   |
| 6.3.4   | 50        | 2.24%   |
| 6.3.7   | 49        | 2.19%   |
| 6.4.9   | 42        | 1.88%   |
| 6.2.8   | 14        | 0.63%   |
| 6.2.6   | 12        | 0.54%   |
| 6.2.10  | 12        | 0.54%   |
| 6.2.0   | 12        | 0.54%   |
| 6.4.8   | 11        | 0.49%   |
| 6.2.2   | 10        | 0.45%   |
| 6.3.3   | 8         | 0.36%   |
| 6.2.7   | 7         | 0.31%   |
| 6.5.0   | 6         | 0.27%   |
| 6.4.0   | 6         | 0.27%   |
| 6.3.1   | 5         | 0.22%   |
| 6.1.0   | 5         | 0.22%   |
| 6.3.10  | 3         | 0.13%   |
| 6.0.8   | 3         | 0.13%   |
| 6.4.14  | 2         | 0.09%   |
| 6.3.9   | 2         | 0.09%   |
| 6.2.5   | 2         | 0.09%   |
| 6.1.26  | 2         | 0.09%   |
| 6.0.0   | 2         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 917       | 42.36%  |
| 6.3     | 655       | 30.25%  |
| 6.4     | 562       | 25.96%  |
| 6.1     | 10        | 0.46%   |
| 6.0     | 9         | 0.42%   |
| 6.5     | 6         | 0.28%   |
| 5.19    | 2         | 0.09%   |
| 5.15    | 2         | 0.09%   |
| 5.11    | 1         | 0.05%   |
| 5.10    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2027      | 99.66%  |
| aarch64 | 6         | 0.29%   |
| ppc64le | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 1588      | 77.58%  |
| KDE5          | 295       | 14.41%  |
| Unknown       | 38        | 1.86%   |
| XFCE          | 28        | 1.37%   |
| X-Cinnamon    | 23        | 1.12%   |
| Cinnamon      | 22        | 1.07%   |
| GNOME Classic | 12        | 0.59%   |
| MATE          | 8         | 0.39%   |
| sway          | 7         | 0.34%   |
| Hyprland      | 6         | 0.29%   |
| Budgie        | 5         | 0.24%   |
| LXDE          | 4         | 0.2%    |
| i3            | 4         | 0.2%    |
| LXQt          | 3         | 0.15%   |
| Pantheon      | 1         | 0.05%   |
| KDE4          | 1         | 0.05%   |
| KDE           | 1         | 0.05%   |
| Deepin        | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1629      | 79.27%  |
| X11     | 361       | 17.57%  |
| Tty     | 42        | 2.04%   |
| Unknown | 22        | 1.07%   |
| Xcb     | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1328      | 64.84%  |
| GDM     | 493       | 24.07%  |
| SDDM    | 140       | 6.84%   |
| LightDM | 82        | 4%      |
| LXDM    | 4         | 0.2%    |
| SLiM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1039      | 50.83%  |
| en_GB   | 143       | 7%      |
| ru_RU   | 107       | 5.23%   |
| de_DE   | 102       | 4.99%   |
| pt_BR   | 99        | 4.84%   |
| en_AU   | 58        | 2.84%   |
| fr_FR   | 53        | 2.59%   |
| en_CA   | 51        | 2.5%    |
| it_IT   | 39        | 1.91%   |
| es_ES   | 34        | 1.66%   |
| pl_PL   | 31        | 1.52%   |
| es_MX   | 27        | 1.32%   |
| en_IN   | 23        | 1.13%   |
| es_CL   | 15        | 0.73%   |
| es_CO   | 13        | 0.64%   |
| en_DK   | 13        | 0.64%   |
| pt_PT   | 11        | 0.54%   |
| es_AR   | 11        | 0.54%   |
| zh_CN   | 10        | 0.49%   |
| tr_TR   | 10        | 0.49%   |
| hu_HU   | 10        | 0.49%   |
| cs_CZ   | 10        | 0.49%   |
| de_AT   | 9         | 0.44%   |
| Unknown | 8         | 0.39%   |
| nl_NL   | 6         | 0.29%   |
| fr_CA   | 6         | 0.29%   |
| es_PE   | 6         | 0.29%   |
| en_NZ   | 6         | 0.29%   |
| ru_UA   | 5         | 0.24%   |
| en_PH   | 5         | 0.24%   |
| en_IE   | 5         | 0.24%   |
| de_CH   | 5         | 0.24%   |
| sk_SK   | 4         | 0.2%    |
| es_EC   | 4         | 0.2%    |
| en_ZA   | 4         | 0.2%    |
| da_DK   | 4         | 0.2%    |
| zh_TW   | 3         | 0.15%   |
| sv_SE   | 3         | 0.15%   |
| nl_BE   | 3         | 0.15%   |
| ja_JP   | 3         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1660      | 81.25%  |
| BIOS | 383       | 18.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 1703      | 83.48%  |
| Ext4    | 287       | 14.07%  |
| Xfs     | 42        | 2.06%   |
| Overlay | 4         | 0.2%    |
| Zfs     | 1         | 0.05%   |
| F2fs    | 1         | 0.05%   |
| Ext3    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1294      | 63.25%  |
| GPT     | 709       | 34.65%  |
| MBR     | 43        | 2.1%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1882      | 92.07%  |
| Yes       | 162       | 7.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1751      | 85.88%  |
| Yes       | 288       | 14.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 401       | 19.71%  |
| ASUSTek Computer                     | 319       | 15.68%  |
| Hewlett-Packard                      | 260       | 12.78%  |
| Dell                                 | 257       | 12.64%  |
| MSI                                  | 144       | 7.08%   |
| Gigabyte Technology                  | 124       | 6.1%    |
| Acer                                 | 78        | 3.83%   |
| Apple                                | 72        | 3.54%   |
| ASRock                               | 53        | 2.61%   |
| HUAWEI                               | 37        | 1.82%   |
| Samsung Electronics                  | 22        | 1.08%   |
| Unknown                              | 19        | 0.93%   |
| Microsoft                            | 17        | 0.84%   |
| Intel                                | 17        | 0.84%   |
| Timi                                 | 15        | 0.74%   |
| Google                               | 13        | 0.64%   |
| Toshiba                              | 10        | 0.49%   |
| AZW                                  | 10        | 0.49%   |
| Fujitsu                              | 9         | 0.44%   |
| Sony                                 | 8         | 0.39%   |
| Pegatron                             | 7         | 0.34%   |
| Notebook                             | 7         | 0.34%   |
| Framework                            | 6         | 0.29%   |
| System76                             | 4         | 0.2%    |
| Positivo                             | 4         | 0.2%    |
| Itautec                              | 4         | 0.2%    |
| Huanan                               | 4         | 0.2%    |
| Chuwi                                | 4         | 0.2%    |
| TUXEDO                               | 3         | 0.15%   |
| Shenzhen Meigao Electronic Equipment | 3         | 0.15%   |
| Razer                                | 3         | 0.15%   |
| Positivo Bahia - VAIO                | 3         | 0.15%   |
| PC Specialist                        | 3         | 0.15%   |
| Medion                               | 3         | 0.15%   |
| HONOR                                | 3         | 0.15%   |
| GPU Company                          | 3         | 0.15%   |
| Avell High Performance               | 3         | 0.15%   |
| AMI                                  | 3         | 0.15%   |
| Alienware                            | 3         | 0.15%   |
| ZOTAC                                | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 22        | 1.08%   |
| ASUS All Series                      | 11        | 0.54%   |
| Apple MacBookPro9,2                  | 9         | 0.44%   |
| MSI MS-7C37                          | 6         | 0.29%   |
| HP Notebook                          | 6         | 0.29%   |
| Framework Laptop                     | 6         | 0.29%   |
| Dell XPS 13 9310                     | 6         | 0.29%   |
| Dell OptiPlex 7010                   | 6         | 0.29%   |
| Apple MacBookPro8,1                  | 6         | 0.29%   |
| Gigabyte B550 GAMING X V2            | 5         | 0.25%   |
| Samsung 550XDA                       | 4         | 0.2%    |
| MSI MS-7C02                          | 4         | 0.2%    |
| MSI MS-7B89                          | 4         | 0.2%    |
| MSI MS-7A38                          | 4         | 0.2%    |
| Lenovo IdeaPadFlex 5 14ALC05 82HU    | 4         | 0.2%    |
| Lenovo IdeaPad 3 15ITL6 82H8         | 4         | 0.2%    |
| HP Victus by Laptop 16-e0xxx         | 4         | 0.2%    |
| HP Pavilion x2 Detachable            | 4         | 0.2%    |
| HP Pavilion Aero Laptop 13-be0xxx    | 4         | 0.2%    |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 4         | 0.2%    |
| HP 255 G8 Notebook PC                | 4         | 0.2%    |
| Dell XPS 15 9560                     | 4         | 0.2%    |
| Dell XPS 13 9305                     | 4         | 0.2%    |
| Dell Latitude E7470                  | 4         | 0.2%    |
| Dell Inspiron 15 5510                | 4         | 0.2%    |
| AZW SER                              | 4         | 0.2%    |
| ASUS ROG STRIX B550-I GAMING         | 4         | 0.2%    |
| Apple MacBookPro5,5                  | 4         | 0.2%    |
| Apple MacBookAir7,2                  | 4         | 0.2%    |
| Timi Redmi Book Pro 14 2022          | 3         | 0.15%   |
| MSI MS-7D43                          | 3         | 0.15%   |
| MSI MS-7C95                          | 3         | 0.15%   |
| MSI MS-7C94                          | 3         | 0.15%   |
| MSI MS-7B79                          | 3         | 0.15%   |
| MSI MS-7B17                          | 3         | 0.15%   |
| Microsoft Surface Pro 7              | 3         | 0.15%   |
| Lenovo Yoga 6 13ALC6 82ND            | 3         | 0.15%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 3         | 0.15%   |
| Lenovo Legion 5 15ACH6H 82JU         | 3         | 0.15%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS    | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 183       | 9%      |
| Lenovo IdeaPad     | 78        | 3.83%   |
| Dell Latitude      | 78        | 3.83%   |
| ASUS ROG           | 71        | 3.49%   |
| Dell Inspiron      | 64        | 3.15%   |
| ASUS VivoBook      | 51        | 2.51%   |
| HP Pavilion        | 48        | 2.36%   |
| Acer Aspire        | 45        | 2.21%   |
| ASUS PRIME         | 42        | 2.06%   |
| Dell XPS           | 40        | 1.97%   |
| ASUS TUF           | 33        | 1.62%   |
| Lenovo Yoga        | 31        | 1.52%   |
| HP EliteBook       | 30        | 1.47%   |
| Dell OptiPlex      | 30        | 1.47%   |
| HP Laptop          | 29        | 1.43%   |
| Lenovo Legion      | 28        | 1.38%   |
| HP ENVY            | 25        | 1.23%   |
| HP ProBook         | 24        | 1.18%   |
| Unknown            | 22        | 1.08%   |
| Dell Precision     | 21        | 1.03%   |
| Lenovo ThinkBook   | 18        | 0.88%   |
| ASUS ASUS          | 18        | 0.88%   |
| Microsoft Surface  | 17        | 0.84%   |
| Lenovo ThinkCentre | 15        | 0.74%   |
| HP Compaq          | 15        | 0.74%   |
| Acer Nitro         | 15        | 0.74%   |
| Lenovo IdeaPadFlex | 12        | 0.59%   |
| HP OMEN            | 11        | 0.54%   |
| ASUS ZenBook       | 11        | 0.54%   |
| ASUS All           | 11        | 0.54%   |
| Apple MacBookPro9  | 10        | 0.49%   |
| Dell Vostro        | 9         | 0.44%   |
| Toshiba Satellite  | 8         | 0.39%   |
| HP Victus          | 8         | 0.39%   |
| HP EliteDesk       | 8         | 0.39%   |
| Gigabyte B550M     | 8         | 0.39%   |
| Gigabyte B550      | 8         | 0.39%   |
| HP 255             | 7         | 0.34%   |
| Gigabyte X570      | 7         | 0.34%   |
| Apple MacBookPro8  | 7         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 310       | 15.24%  |
| 2022    | 266       | 13.08%  |
| 2020    | 251       | 12.34%  |
| 2018    | 196       | 9.64%   |
| 2019    | 195       | 9.59%   |
| 2017    | 131       | 6.44%   |
| 2012    | 103       | 5.06%   |
| 2015    | 90        | 4.42%   |
| 2013    | 86        | 4.23%   |
| 2023    | 85        | 4.18%   |
| 2014    | 77        | 3.79%   |
| 2016    | 74        | 3.64%   |
| 2011    | 62        | 3.05%   |
| 2010    | 45        | 2.21%   |
| 2009    | 24        | 1.18%   |
| 2008    | 22        | 1.08%   |
| 2007    | 9         | 0.44%   |
| 2006    | 4         | 0.2%    |
| Unknown | 3         | 0.15%   |
| 2005    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1220      | 59.98%  |
| Desktop        | 616       | 30.29%  |
| Convertible    | 89        | 4.38%   |
| Tablet         | 37        | 1.82%   |
| Mini pc        | 36        | 1.77%   |
| All in one     | 22        | 1.08%   |
| Server         | 10        | 0.49%   |
| System on chip | 4         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1583      | 77.22%  |
| Enabled  | 467       | 22.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2016      | 99.12%  |
| Yes  | 18        | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 523       | 25.52%  |
| 4.01-8.0        | 472       | 23.04%  |
| 8.01-16.0       | 378       | 18.45%  |
| 32.01-64.0      | 300       | 14.64%  |
| 3.01-4.0        | 159       | 7.76%   |
| 64.01-256.0     | 106       | 5.17%   |
| 24.01-32.0      | 76        | 3.71%   |
| 1.01-2.0        | 29        | 1.42%   |
| 2.01-3.0        | 5         | 0.24%   |
| More than 256.0 | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 637       | 29.56%  |
| 2.01-3.0    | 566       | 26.26%  |
| 3.01-4.0    | 530       | 24.59%  |
| 1.01-2.0    | 218       | 10.12%  |
| 8.01-16.0   | 160       | 7.42%   |
| 0.51-1.0    | 21        | 0.97%   |
| 16.01-24.0  | 16        | 0.74%   |
| 32.01-64.0  | 4         | 0.19%   |
| 24.01-32.0  | 2         | 0.09%   |
| 64.01-256.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1246      | 60.4%   |
| 2      | 528       | 25.59%  |
| 3      | 149       | 7.22%   |
| 4      | 76        | 3.68%   |
| 5      | 31        | 1.5%    |
| 6      | 15        | 0.73%   |
| 0      | 6         | 0.29%   |
| 7      | 4         | 0.19%   |
| 10     | 3         | 0.15%   |
| 8      | 3         | 0.15%   |
| 11     | 2         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1642      | 80.53%  |
| Yes       | 397       | 19.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1571      | 77.05%  |
| No        | 468       | 22.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1717      | 84.17%  |
| No        | 323       | 15.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1529      | 74.8%   |
| No        | 515       | 25.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 372       | 18.24%  |
| Germany     | 159       | 7.79%   |
| Brazil      | 151       | 7.4%    |
| Russia      | 119       | 5.83%   |
| Canada      | 78        | 3.82%   |
| UK          | 72        | 3.53%   |
| Italy       | 68        | 3.33%   |
| India       | 66        | 3.24%   |
| France      | 66        | 3.24%   |
| Australia   | 63        | 3.09%   |
| Poland      | 57        | 2.79%   |
| Netherlands | 50        | 2.45%   |
| Mexico      | 50        | 2.45%   |
| Spain       | 42        | 2.06%   |
| Turkey      | 33        | 1.62%   |
| Czechia     | 26        | 1.27%   |
| Colombia    | 24        | 1.18%   |
| Hungary     | 22        | 1.08%   |
| Chile       | 22        | 1.08%   |
| Austria     | 22        | 1.08%   |
| Switzerland | 21        | 1.03%   |
| Belgium     | 21        | 1.03%   |
| Portugal    | 19        | 0.93%   |
| Sweden      | 18        | 0.88%   |
| Norway      | 18        | 0.88%   |
| Indonesia   | 16        | 0.78%   |
| Belarus     | 16        | 0.78%   |
| Argentina   | 16        | 0.78%   |
| Denmark     | 15        | 0.74%   |
| Bulgaria    | 14        | 0.69%   |
| Finland     | 13        | 0.64%   |
| China       | 13        | 0.64%   |
| Thailand    | 12        | 0.59%   |
| Romania     | 12        | 0.59%   |
| Philippines | 12        | 0.59%   |
| Serbia      | 10        | 0.49%   |
| Israel      | 10        | 0.49%   |
| Singapore   | 9         | 0.44%   |
| Ireland     | 9         | 0.44%   |
| Ukraine     | 8         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 30        | 1.45%   |
| Sydney            | 28        | 1.35%   |
| Sao Paulo         | 20        | 0.97%   |
| Berlin            | 17        | 0.82%   |
| Vienna            | 15        | 0.73%   |
| Mexico City       | 14        | 0.68%   |
| St Petersburg     | 13        | 0.63%   |
| Santiago          | 13        | 0.63%   |
| Minsk             | 13        | 0.63%   |
| Melbourne         | 13        | 0.63%   |
| Delhi             | 13        | 0.63%   |
| Warsaw            | 12        | 0.58%   |
| Rio de Janeiro    | 12        | 0.58%   |
| Helsinki          | 12        | 0.58%   |
| Budapest          | 11        | 0.53%   |
| Amsterdam         | 11        | 0.53%   |
| Seattle           | 10        | 0.48%   |
| Prague            | 10        | 0.48%   |
| Paris             | 10        | 0.48%   |
| Istanbul          | 10        | 0.48%   |
| Brussels          | 10        | 0.48%   |
| Sofia             | 9         | 0.44%   |
| Singapore         | 9         | 0.44%   |
| Montreal          | 9         | 0.44%   |
| Palmas            | 8         | 0.39%   |
| Ottawa            | 8         | 0.39%   |
| New York          | 8         | 0.39%   |
| Milan             | 8         | 0.39%   |
| Madrid            | 8         | 0.39%   |
| Brisbane          | 8         | 0.39%   |
| Brasília         | 8         | 0.39%   |
| Bengaluru         | 8         | 0.39%   |
| Bangkok           | 8         | 0.39%   |
| Atlanta           | 8         | 0.39%   |
| Toronto           | 7         | 0.34%   |
| Munich            | 7         | 0.34%   |
| Lisbon            | 7         | 0.34%   |
| Hamburg           | 7         | 0.34%   |
| Frankfurt am Main | 7         | 0.34%   |
| Fortaleza         | 7         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 586       | 827    | 19.68%  |
| Sandisk                        | 276       | 327    | 9.27%   |
| Seagate                        | 257       | 338    | 8.63%   |
| WDC                            | 254       | 352    | 8.53%   |
| Kingston                       | 164       | 190    | 5.51%   |
| Toshiba                        | 146       | 182    | 4.9%    |
| SK hynix                       | 112       | 121    | 3.76%   |
| Unknown                        | 109       | 134    | 3.66%   |
| Intel                          | 103       | 140    | 3.46%   |
| Crucial                        | 100       | 133    | 3.36%   |
| Micron Technology              | 96        | 100    | 3.22%   |
| Phison Electronics             | 54        | 69     | 1.81%   |
| Micron/Crucial Technology      | 42        | 43     | 1.41%   |
| KIOXIA                         | 42        | 48     | 1.41%   |
| Silicon Motion                 | 41        | 48     | 1.38%   |
| A-DATA Technology              | 41        | 46     | 1.38%   |
| Apple                          | 36        | 52     | 1.21%   |
| China                          | 34        | 44     | 1.14%   |
| Hitachi                        | 33        | 43     | 1.11%   |
| Kingston Technology Company    | 28        | 31     | 0.94%   |
| HGST                           | 28        | 28     | 0.94%   |
| ADATA Technology               | 21        | 21     | 0.71%   |
| SPCC                           | 16        | 18     | 0.54%   |
| Patriot                        | 16        | 20     | 0.54%   |
| JMicron Technology             | 16        | 20     | 0.54%   |
| Netac                          | 15        | 16     | 0.5%    |
| MAXIO Technology (Hangzhou)    | 14        | 16     | 0.47%   |
| Realtek Semiconductor          | 11        | 15     | 0.37%   |
| PNY                            | 10        | 13     | 0.34%   |
| Intenso                        | 10        | 11     | 0.34%   |
| Shenzhen Longsys Electronics   | 9         | 9      | 0.3%    |
| Unknown                        | 9         | 11     | 0.3%    |
| Transcend                      | 8         | 10     | 0.27%   |
| Solid State Storage Technology | 8         | 8      | 0.27%   |
| SABRENT                        | 8         | 8      | 0.27%   |
| Phison                         | 8         | 10     | 0.27%   |
| Union Memory (Shenzhen)        | 7         | 9      | 0.24%   |
| Lexar                          | 7         | 7      | 0.24%   |
| KingSpec                       | 7         | 7      | 0.24%   |
| Union Memory                   | 6         | 6      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 137       | 4.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 81        | 2.51%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 38        | 1.18%   |
| Kingston SA400S37240G 240GB SSD                       | 35        | 1.09%   |
| Unknown MMC Card  64GB                                | 33        | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 31        | 0.96%   |
| Samsung SSD 980 1TB                                   | 29        | 0.9%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 28        | 0.87%   |
| Kingston SA400S37480G 480GB SSD                       | 27        | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 25        | 0.78%   |
| Phison E12 NVMe Controller 256GB                      | 25        | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB                        | 24        | 0.74%   |
| Intel SSD 660P Series 512GB                           | 24        | 0.74%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 22        | 0.68%   |
| Crucial CT500MX500SSD1 500GB                          | 21        | 0.65%   |
| Unknown MMC Card  32GB                                | 20        | 0.62%   |
| Unknown MMC Card  128GB                               | 20        | 0.62%   |
| Samsung SSD 860 EVO 500GB                             | 18        | 0.56%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 17        | 0.53%   |
| Samsung SSD 870 EVO 1TB                               | 17        | 0.53%   |
| Samsung SSD 850 EVO 250GB                             | 17        | 0.53%   |
| Sandisk WD Black SN850 256GB                          | 16        | 0.5%    |
| Samsung SSD 860 EVO 1TB                               | 15        | 0.47%   |
| Samsung SSD 850 EVO 500GB                             | 15        | 0.47%   |
| Intel SSDPEKNU512GZ 512GB                             | 15        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB                           | 15        | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                        | 14        | 0.43%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 14        | 0.43%   |
| Toshiba MQ01ABD100 1TB                                | 13        | 0.4%    |
| Seagate ST1000DM010-2EP102 1TB                        | 13        | 0.4%    |
| Kingston SA400S37120G 120GB SSD                       | 13        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 12        | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                        | 12        | 0.37%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 12        | 0.37%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 1024GB   | 12        | 0.37%   |
| Toshiba MQ04ABF100 1TB                                | 11        | 0.34%   |
| Toshiba DT01ACA100 1TB                                | 11        | 0.34%   |
| SK hynix BC501 NVMe Solid State Drive 512GB           | 11        | 0.34%   |
| Seagate ST500DM002-1BD142 500GB                       | 11        | 0.34%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB       | 11        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 244       | 317    | 36.8%   |
| WDC                 | 197       | 273    | 29.71%  |
| Toshiba             | 97        | 122    | 14.63%  |
| Hitachi             | 33        | 43     | 4.98%   |
| HGST                | 28        | 28     | 4.22%   |
| Samsung Electronics | 19        | 21     | 2.87%   |
| Apple               | 14        | 16     | 2.11%   |
| Unknown             | 8         | 10     | 1.21%   |
| SABRENT             | 8         | 8      | 1.21%   |
| QNAP                | 3         | 6      | 0.45%   |
| Maxtor              | 2         | 2      | 0.3%    |
| Fujitsu             | 2         | 2      | 0.3%    |
| USB3.0              | 1         | 1      | 0.15%   |
| USB                 | 1         | 1      | 0.15%   |
| SAGE                | 1         | 1      | 0.15%   |
| LaCie               | 1         | 1      | 0.15%   |
| JMicron Technology  | 1         | 1      | 0.15%   |
| IB                  | 1         | 2      | 0.15%   |
| ASMT                | 1         | 2      | 0.15%   |
| ACASIS              | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 208       | 294    | 22.78%  |
| Kingston            | 120       | 139    | 13.14%  |
| Crucial             | 98        | 129    | 10.73%  |
| SanDisk             | 75        | 87     | 8.21%   |
| WDC                 | 57        | 66     | 6.24%   |
| China               | 34        | 44     | 3.72%   |
| A-DATA Technology   | 33        | 38     | 3.61%   |
| Intel               | 30        | 46     | 3.29%   |
| Micron Technology   | 18        | 19     | 1.97%   |
| Apple               | 17        | 19     | 1.86%   |
| SPCC                | 16        | 18     | 1.75%   |
| Patriot             | 16        | 20     | 1.75%   |
| Toshiba             | 15        | 20     | 1.64%   |
| JMicron Technology  | 11        | 13     | 1.2%    |
| PNY                 | 10        | 13     | 1.1%    |
| Netac               | 9         | 9      | 0.99%   |
| Transcend           | 7         | 9      | 0.77%   |
| Lexar               | 7         | 7      | 0.77%   |
| LITEONIT            | 6         | 6      | 0.66%   |
| LITEON              | 6         | 6      | 0.66%   |
| KingSpec            | 6         | 6      | 0.66%   |
| GOODRAM             | 6         | 9      | 0.66%   |
| Team                | 5         | 5      | 0.55%   |
| OCZ                 | 5         | 8      | 0.55%   |
| Intenso             | 5         | 5      | 0.55%   |
| Gigabyte Technology | 5         | 7      | 0.55%   |
| SK hynix            | 4         | 4      | 0.44%   |
| Hewlett-Packard     | 4         | 4      | 0.44%   |
| Apacer              | 4         | 5      | 0.44%   |
| AMD                 | 4         | 4      | 0.44%   |
| Mushkin             | 3         | 3      | 0.33%   |
| Advantech           | 3         | 3      | 0.33%   |
| Unknown             | 3         | 5      | 0.33%   |
| XrayDisk            | 2         | 2      | 0.22%   |
| TO Exter            | 2         | 2      | 0.22%   |
| Smartbuy            | 2         | 2      | 0.22%   |
| Ramsta              | 2         | 2      | 0.22%   |
| NGFF                | 2         | 2      | 0.22%   |
| MidasForce          | 2         | 2      | 0.22%   |
| Kimtigo             | 2         | 2      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1195      | 1561   | 43.9%   |
| SSD     | 794       | 1141   | 29.17%  |
| HDD     | 574       | 858    | 21.09%  |
| MMC     | 101       | 121    | 3.71%   |
| Unknown | 58        | 66     | 2.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1195      | 1559   | 48.07%  |
| SATA | 1086      | 1933   | 43.68%  |
| SAS  | 104       | 134    | 4.18%   |
| MMC  | 101       | 121    | 4.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 747       | 1096   | 52.9%   |
| 0.51-1.0   | 457       | 602    | 32.37%  |
| 1.01-2.0   | 131       | 179    | 9.28%   |
| 3.01-4.0   | 39        | 48     | 2.76%   |
| 4.01-10.0  | 22        | 47     | 1.56%   |
| 2.01-3.0   | 12        | 13     | 0.85%   |
| 10.01-20.0 | 4         | 14     | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 467       | 22.51%  |
| 251-500        | 399       | 19.23%  |
| 1001-2000      | 348       | 16.77%  |
| 101-250        | 242       | 11.66%  |
| 1-20           | 154       | 7.42%   |
| Unknown        | 147       | 7.08%   |
| More than 3000 | 126       | 6.07%   |
| 2001-3000      | 90        | 4.34%   |
| 51-100         | 71        | 3.42%   |
| 21-50          | 30        | 1.45%   |
| 0              | 1         | 0.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 648       | 30.64%  |
| 21-50          | 373       | 17.64%  |
| 101-250        | 272       | 12.86%  |
| 51-100         | 220       | 10.4%   |
| 251-500        | 194       | 9.17%   |
| Unknown        | 147       | 6.95%   |
| 501-1000       | 137       | 6.48%   |
| 1001-2000      | 71        | 3.36%   |
| More than 3000 | 27        | 1.28%   |
| 2001-3000      | 25        | 1.18%   |
| 0              | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 3      | 3.3%    |
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 3.3%    |
| Intel SSDSC2CT120A3 120GB             | 3         | 7      | 3.3%    |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 3.3%    |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 2.2%    |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 2.2%    |
| Seagate ST31000524AS 1TB              | 2         | 2      | 2.2%    |
| SanDisk SD8SBAT256G1122 256GB SSD     | 2         | 2      | 2.2%    |
| Crucial CT120M500SSD1 120GB           | 2         | 6      | 2.2%    |
| YS SSD 240GB                          | 1         | 1      | 1.1%    |
| Wibtek W800S 512GB SSD                | 1         | 1      | 1.1%    |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1         | 1      | 1.1%    |
| WDC WD5000BPVT-75HXZT1 500GB          | 1         | 1      | 1.1%    |
| WDC WD5000AVCS-632DY1 500GB           | 1         | 1      | 1.1%    |
| WDC WD5000AAKX-603CA0 500GB           | 1         | 1      | 1.1%    |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 1.1%    |
| WDC WD40PURX-64GVNY0 4TB              | 1         | 1      | 1.1%    |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 1      | 1.1%    |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 1      | 1.1%    |
| WDC WD10JPVT-60A1YT0 1TB              | 1         | 1      | 1.1%    |
| WDC WD10EZRZ-00HTKB0 1TB              | 1         | 1      | 1.1%    |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 1.1%    |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 1.1%    |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 1.1%    |
| SSSTC CVB-8D128-HP 128GB              | 1         | 1      | 1.1%    |
| SPCC Solid State Disk 128GB           | 1         | 1      | 1.1%    |
| SK hynix HFS128G3AMNB-2200A 128GB SSD | 1         | 1      | 1.1%    |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.1%    |
| Seagate ST9160412AS 160GB             | 1         | 1      | 1.1%    |
| Seagate ST3750528AS 752GB             | 1         | 1      | 1.1%    |
| Seagate ST3500630NS 500GB             | 1         | 1      | 1.1%    |
| Seagate ST3500418AS 500GB             | 1         | 2      | 1.1%    |
| Seagate ST3320613AS 320GB             | 1         | 1      | 1.1%    |
| Seagate ST2000VX000-1CU164 2TB        | 1         | 1      | 1.1%    |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 1      | 1.1%    |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 1.1%    |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 1.1%    |
| Seagate ST1000DX002-2DV162 1TB        | 1         | 1      | 1.1%    |
| Seagate ST1000DM003-1ER162 1TB        | 1         | 1      | 1.1%    |
| SanDisk SSD PLUS 480GB                | 1         | 1      | 1.1%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 16        | 18     | 18.18%  |
| WDC                         | 13        | 15     | 14.77%  |
| Samsung Electronics         | 11        | 13     | 12.5%   |
| Intel                       | 7         | 11     | 7.95%   |
| Toshiba                     | 5         | 5      | 5.68%   |
| SanDisk                     | 4         | 4      | 4.55%   |
| Kingston                    | 4         | 6      | 4.55%   |
| HGST                        | 4         | 4      | 4.55%   |
| Hitachi                     | 3         | 3      | 3.41%   |
| Crucial                     | 3         | 7      | 3.41%   |
| Micron Technology           | 2         | 2      | 2.27%   |
| LITEONIT                    | 2         | 2      | 2.27%   |
| Intenso                     | 2         | 2      | 2.27%   |
| A-DATA Technology           | 2         | 2      | 2.27%   |
| YS                          | 1         | 1      | 1.14%   |
| Wibtek                      | 1         | 1      | 1.14%   |
| SSSTC                       | 1         | 1      | 1.14%   |
| SPCC                        | 1         | 1      | 1.14%   |
| SK hynix                    | 1         | 1      | 1.14%   |
| Maxtor                      | 1         | 1      | 1.14%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 1.14%   |
| LITEON                      | 1         | 1      | 1.14%   |
| HPE                         | 1         | 1      | 1.14%   |
| China                       | 1         | 1      | 1.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 38.1%   |
| WDC                 | 10        | 11     | 23.81%  |
| Toshiba             | 5         | 5      | 11.9%   |
| HGST                | 4         | 4      | 9.52%   |
| Samsung Electronics | 3         | 4      | 7.14%   |
| Hitachi             | 3         | 3      | 7.14%   |
| Maxtor              | 1         | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 42        | 55     | 48.84%  |
| HDD  | 41        | 46     | 47.67%  |
| NVMe | 3         | 3      | 3.49%   |

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
| Detected | 1399      | 2477   | 65.01%  |
| Works    | 673       | 1166   | 31.27%  |
| Malfunc  | 80        | 104    | 3.72%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1071      | 37.97%  |
| AMD                                     | 424       | 15.03%  |
| Samsung Electronics                     | 410       | 14.53%  |
| SanDisk                                 | 212       | 7.52%   |
| SK hynix                                | 107       | 3.79%   |
| Micron Technology                       | 78        | 2.76%   |
| Kingston Technology Company             | 75        | 2.66%   |
| Phison Electronics                      | 60        | 2.13%   |
| Silicon Motion                          | 43        | 1.52%   |
| Micron/Crucial Technology               | 43        | 1.52%   |
| KIOXIA                                  | 39        | 1.38%   |
| Toshiba America Info Systems            | 38        | 1.35%   |
| ASMedia Technology                      | 35        | 1.24%   |
| ADATA Technology                        | 28        | 0.99%   |
| Marvell Technology Group                | 20        | 0.71%   |
| Solid State Storage Technology          | 14        | 0.5%    |
| MAXIO Technology (Hangzhou)             | 14        | 0.5%    |
| Union Memory (Shenzhen)                 | 13        | 0.46%   |
| Realtek Semiconductor                   | 11        | 0.39%   |
| Seagate Technology                      | 10        | 0.35%   |
| Nvidia                                  | 10        | 0.35%   |
| Shenzhen Longsys Electronics            | 9         | 0.32%   |
| JMicron Technology                      | 8         | 0.28%   |
| LSI Logic / Symbios Logic               | 7         | 0.25%   |
| Netac Technology                        | 6         | 0.21%   |
| Apple                                   | 6         | 0.21%   |
| Lenovo                                  | 5         | 0.18%   |
| Yangtze Memory Technologies             | 4         | 0.14%   |
| Solidigm                                | 4         | 0.14%   |
| VIA Technologies                        | 2         | 0.07%   |
| Silicon Image                           | 2         | 0.07%   |
| INNOGRIT                                | 2         | 0.07%   |
| Broadcom / LSI                          | 2         | 0.07%   |
| Biwin Storage Technology                | 2         | 0.07%   |
| Adaptec                                 | 2         | 0.07%   |
| ULi Electronics                         | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.04%   |
| PMC-Sierra                              | 1         | 0.04%   |
| Lite-On Technology                      | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 302       | 9.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 150       | 4.89%   |
| Samsung NVMe SSD Controller 980                                                | 110       | 3.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 102       | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 93        | 3.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 87        | 2.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 66        | 2.15%   |
| AMD 500 Series Chipset SATA Controller                                         | 60        | 1.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 59        | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 56        | 1.83%   |
| AMD 400 Series Chipset SATA Controller                                         | 56        | 1.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 48        | 1.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 43        | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 42        | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 40        | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 35        | 1.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 34        | 1.11%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 34        | 1.11%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 33        | 1.08%   |
| Intel Tiger Lake-LP SATA Controller                                            | 31        | 1.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 31        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 30        | 0.98%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 29        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 29        | 0.95%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 28        | 0.91%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 28        | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 28        | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 27        | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 26        | 0.85%   |
| Phison E12 NVMe Controller                                                     | 26        | 0.85%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 25        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 25        | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 25        | 0.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 24        | 0.78%   |
| Intel SSD 660P Series                                                          | 24        | 0.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 0.72%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 22        | 0.72%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 22        | 0.72%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 21        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 20        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1296      | 46.77%  |
| NVMe | 1187      | 42.84%  |
| RAID | 209       | 7.54%   |
| IDE  | 71        | 2.56%   |
| SAS  | 4         | 0.14%   |
| SCSI | 4         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 1406      | 69.12%  |
| AMD                      | 620       | 30.48%  |
| ARM                      | 5         | 0.25%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.05%   |
| CentaurHauls             | 1         | 0.05%   |
| Unknown                  | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 50        | 2.46%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 31        | 1.52%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 1.38%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 28        | 1.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 24        | 1.18%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 21        | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 20        | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 19        | 0.93%   |
| Intel 12th Gen Core i7-12700H                 | 19        | 0.93%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 19        | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 0.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 0.84%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 17        | 0.84%   |
| AMD Ryzen 5 3600 6-Core Processor             | 17        | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 16        | 0.79%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 16        | 0.79%   |
| Intel 12th Gen Core i7-1255U                  | 16        | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 16        | 0.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 0.74%   |
| Intel 12th Gen Core i7-1260P                  | 14        | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 13        | 0.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.64%   |
| Intel 12th Gen Core i5-1235U                  | 13        | 0.64%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 13        | 0.64%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 13        | 0.64%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 13        | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 0.59%   |
| Intel 12th Gen Core i5-12500H                 | 12        | 0.59%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 12        | 0.59%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 12        | 0.59%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 12        | 0.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 12        | 0.59%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 12        | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 11        | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.54%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 11        | 0.54%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 11        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 391       | 19.21%  |
| Other                   | 349       | 17.15%  |
| Intel Core i7           | 343       | 16.86%  |
| AMD Ryzen 5             | 213       | 10.47%  |
| AMD Ryzen 7             | 194       | 9.53%   |
| Intel Core i3           | 98        | 4.82%   |
| AMD Ryzen 9             | 79        | 3.88%   |
| Intel Celeron           | 61        | 3%      |
| Intel Xeon              | 45        | 2.21%   |
| Intel Core 2 Duo        | 30        | 1.47%   |
| Intel Atom              | 28        | 1.38%   |
| AMD Ryzen 3             | 22        | 1.08%   |
| Intel Pentium           | 17        | 0.84%   |
| AMD FX                  | 17        | 0.84%   |
| Intel Pentium Silver    | 15        | 0.74%   |
| Intel Core i9           | 15        | 0.74%   |
| AMD Ryzen 7 PRO         | 13        | 0.64%   |
| AMD Ryzen 5 PRO         | 10        | 0.49%   |
| Intel Core 2 Quad       | 9         | 0.44%   |
| AMD Phenom II X4        | 9         | 0.44%   |
| AMD A6                  | 9         | 0.44%   |
| AMD A8                  | 8         | 0.39%   |
| AMD A10                 | 8         | 0.39%   |
| AMD Ryzen Threadripper  | 6         | 0.29%   |
| Intel Pentium Dual      | 5         | 0.25%   |
| AMD Athlon              | 4         | 0.2%    |
| AMD A4                  | 4         | 0.2%    |
| Intel Genuine           | 3         | 0.15%   |
| Intel Core m5           | 3         | 0.15%   |
| Intel Pentium Gold      | 2         | 0.1%    |
| Intel Pentium Dual-Core | 2         | 0.1%    |
| Intel Core m3           | 2         | 0.1%    |
| Intel Core 2            | 2         | 0.1%    |
| AMD Phenom II X2        | 2         | 0.1%    |
| AMD E2                  | 2         | 0.1%    |
| AMD E1                  | 2         | 0.1%    |
| AMD A12                 | 2         | 0.1%    |
| Intel Core M            | 1         | 0.05%   |
| Intel Core 2 Extreme    | 1         | 0.05%   |
| AMD Turion II Dual-Core | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 727       | 35.74%  |
| 2       | 483       | 23.75%  |
| 6       | 300       | 14.75%  |
| 8       | 290       | 14.26%  |
| 12      | 83        | 4.08%   |
| 10      | 51        | 2.51%   |
| 14      | 45        | 2.21%   |
| 16      | 34        | 1.67%   |
| 24      | 7         | 0.34%   |
| 3       | 5         | 0.25%   |
| 1       | 3         | 0.15%   |
| 32      | 2         | 0.1%    |
| Unknown | 2         | 0.1%    |
| 36      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2021      | 99.36%  |
| 2       | 11        | 0.54%   |
| Unknown | 2         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1650      | 81.12%  |
| 1       | 381       | 18.73%  |
| Unknown | 2         | 0.1%    |
| 4       | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2029      | 99.75%  |
| 64-bit         | 4         | 0.2%    |
| Unknown        | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1435      | 70.34%  |
| 0x0a50000c | 71        | 3.48%   |
| 0x0a50000d | 48        | 2.35%   |
| 0x08108109 | 39        | 1.91%   |
| 0x08608103 | 37        | 1.81%   |
| 0x08600106 | 33        | 1.62%   |
| 0x0a601203 | 32        | 1.57%   |
| 0x0a404102 | 32        | 1.57%   |
| 0x0a20120a | 30        | 1.47%   |
| 0x08701021 | 28        | 1.37%   |
| 0x0800820d | 19        | 0.93%   |
| 0x08108102 | 15        | 0.74%   |
| 0x0a201016 | 14        | 0.69%   |
| 0x08600104 | 13        | 0.64%   |
| 0x0a404101 | 12        | 0.59%   |
| 0x08701030 | 12        | 0.59%   |
| 0x06006705 | 9         | 0.44%   |
| 0x06000822 | 8         | 0.39%   |
| 0x08608104 | 7         | 0.34%   |
| 0x010000c8 | 7         | 0.34%   |
| 0x0a201025 | 6         | 0.29%   |
| 0x08600103 | 6         | 0.29%   |
| 0x08001138 | 6         | 0.29%   |
| 0x06001119 | 6         | 0.29%   |
| 0x08701013 | 5         | 0.25%   |
| 0x08608102 | 5         | 0.25%   |
| 0x0600611a | 5         | 0.25%   |
| 0x010000b6 | 5         | 0.25%   |
| 0x0a201009 | 4         | 0.2%    |
| 0x08101016 | 4         | 0.2%    |
| 0x0810100b | 4         | 0.2%    |
| 0x08001137 | 4         | 0.2%    |
| 0x0a201205 | 3         | 0.15%   |
| 0x0a201204 | 3         | 0.15%   |
| 0x08101007 | 3         | 0.15%   |
| 0x0800820c | 3         | 0.15%   |
| 0x0700010f | 3         | 0.15%   |
| 0x06001116 | 3         | 0.15%   |
| 0x906ea    | 2         | 0.1%    |
| 0x806e9    | 2         | 0.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 353       | 17.35%  |
| Zen 3            | 192       | 9.44%   |
| Alderlake Hybrid | 164       | 8.06%   |
| Unknown          | 160       | 7.87%   |
| TigerLake        | 130       | 6.39%   |
| Haswell          | 117       | 5.75%   |
| IvyBridge        | 107       | 5.26%   |
| Zen 2            | 102       | 5.01%   |
| Skylake          | 100       | 4.92%   |
| Zen+             | 80        | 3.93%   |
| SandyBridge      | 68        | 3.34%   |
| IceLake          | 64        | 3.15%   |
| CometLake        | 61        | 3%      |
| Silvermont       | 45        | 2.21%   |
| Broadwell        | 41        | 2.02%   |
| Westmere         | 36        | 1.77%   |
| Penryn           | 35        | 1.72%   |
| Goldmont plus    | 30        | 1.47%   |
| Zen              | 26        | 1.28%   |
| Piledriver       | 24        | 1.18%   |
| Excavator        | 17        | 0.84%   |
| Core             | 16        | 0.79%   |
| K10              | 15        | 0.74%   |
| Tremont          | 11        | 0.54%   |
| Nehalem          | 7         | 0.34%   |
| Goldmont         | 7         | 0.34%   |
| Puma             | 4         | 0.2%    |
| Jaguar           | 4         | 0.2%    |
| Bulldozer        | 4         | 0.2%    |
| Bonnell          | 4         | 0.2%    |
| K8 Hammer        | 3         | 0.15%   |
| Steamroller      | 2         | 0.1%    |
| K10 Llano        | 2         | 0.1%    |
| Gracemont        | 2         | 0.1%    |
| Bobcat           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1152      | 47.14%  |
| AMD                              | 653       | 26.72%  |
| Nvidia                           | 625       | 25.57%  |
| Matrox Electronics Systems       | 8         | 0.33%   |
| ASPEED Technology                | 3         | 0.12%   |
| Zhaoxin                          | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 122       | 4.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 93        | 3.71%   |
| Intel UHD Graphics 620                                                                   | 66        | 2.63%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 64        | 2.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 62        | 2.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 56        | 2.23%   |
| AMD Renoir                                                                               | 53        | 2.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 51        | 2.03%   |
| AMD Lucienne                                                                             | 51        | 2.03%   |
| AMD Rembrandt [Radeon 680M]                                                              | 47        | 1.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 46        | 1.83%   |
| Intel HD Graphics 620                                                                    | 44        | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 43        | 1.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 1.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 1.51%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 38        | 1.51%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 32        | 1.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 31        | 1.24%   |
| Intel HD Graphics 630                                                                    | 30        | 1.2%    |
| Intel HD Graphics 530                                                                    | 30        | 1.2%    |
| AMD Raphael                                                                              | 28        | 1.12%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 27        | 1.08%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 26        | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 24        | 0.96%   |
| Intel HD Graphics 5500                                                                   | 24        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 0.96%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 24        | 0.96%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 24        | 0.96%   |
| AMD Barcelo                                                                              | 24        | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 22        | 0.88%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 22        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 0.84%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 20        | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 20        | 0.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 20        | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 19        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 18        | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 808       | 39.57%  |
| 1 x AMD         | 492       | 24.09%  |
| Intel + Nvidia  | 279       | 13.66%  |
| 1 x Nvidia      | 263       | 12.88%  |
| AMD + Nvidia    | 77        | 3.77%   |
| 2 x AMD         | 43        | 2.11%   |
| Intel + AMD     | 40        | 1.96%   |
| 2 x Intel       | 10        | 0.49%   |
| Other           | 9         | 0.44%   |
| 2 x Nvidia      | 7         | 0.34%   |
| 1 x Matrox      | 7         | 0.34%   |
| 1 x ASPEED      | 2         | 0.1%    |
| 1 x Zhaoxin     | 1         | 0.05%   |
| 1 x VIA         | 1         | 0.05%   |
| 1 x SiS         | 1         | 0.05%   |
| Nvidia + Matrox | 1         | 0.05%   |
| AMD + ASPEED    | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1692      | 82.62%  |
| Proprietary | 293       | 14.31%  |
| Unknown     | 63        | 3.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1096      | 53.39%  |
| 0.01-0.5   | 232       | 11.3%   |
| 1.01-2.0   | 178       | 8.67%   |
| 3.01-4.0   | 167       | 8.13%   |
| 7.01-8.0   | 143       | 6.97%   |
| 0.51-1.0   | 106       | 5.16%   |
| 8.01-16.0  | 62        | 3.02%   |
| 5.01-6.0   | 40        | 1.95%   |
| 2.01-3.0   | 14        | 0.68%   |
| 16.01-24.0 | 14        | 0.68%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 295       | 12.46%  |
| AU Optronics            | 256       | 10.81%  |
| Samsung Electronics     | 248       | 10.47%  |
| Chimei Innolux          | 218       | 9.21%   |
| Goldstar                | 166       | 7.01%   |
| Dell                    | 164       | 6.93%   |
| LG Display              | 163       | 6.88%   |
| Hewlett-Packard         | 68        | 2.87%   |
| Apple                   | 67        | 2.83%   |
| Sharp                   | 55        | 2.32%   |
| Acer                    | 55        | 2.32%   |
| Lenovo                  | 50        | 2.11%   |
| Philips                 | 43        | 1.82%   |
| AOC                     | 43        | 1.82%   |
| BenQ                    | 39        | 1.65%   |
| Ancor Communications    | 33        | 1.39%   |
| ASUSTek Computer        | 32        | 1.35%   |
| PANDA                   | 31        | 1.31%   |
| CSO                     | 29        | 1.22%   |
| InfoVision              | 26        | 1.1%    |
| ViewSonic               | 18        | 0.76%   |
| Iiyama                  | 18        | 0.76%   |
| Gigabyte Technology     | 17        | 0.72%   |
| Chi Mei Optoelectronics | 15        | 0.63%   |
| MSI                     | 13        | 0.55%   |
| Unknown                 | 12        | 0.51%   |
| TMX                     | 12        | 0.51%   |
| Sceptre Tech            | 11        | 0.46%   |
| Toshiba                 | 8         | 0.34%   |
| Sony                    | 8         | 0.34%   |
| Mi                      | 8         | 0.34%   |
| LG Philips              | 7         | 0.3%    |
| Fujitsu Siemens         | 6         | 0.25%   |
| Vizio                   | 4         | 0.17%   |
| NEC Computers           | 4         | 0.17%   |
| HUAWEI                  | 4         | 0.17%   |
| HKC                     | 4         | 0.17%   |
| Hitachi                 | 4         | 0.17%   |
| GDH                     | 4         | 0.17%   |
| Eizo                    | 4         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 14        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 11        | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 10        | 0.41%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 10        | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 10        | 0.41%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 9         | 0.37%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 8         | 0.33%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 8         | 0.33%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 8         | 0.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 7         | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 7         | 0.29%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 7         | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7         | 0.29%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 7         | 0.29%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 7         | 0.29%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 7         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 6         | 0.25%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 6         | 0.25%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 6         | 0.25%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 6         | 0.25%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 6         | 0.25%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.25%   |
| AOC 27G2WG3 AOC2702 1920x1080 598x336mm 27.0-inch                     | 6         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5         | 0.21%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 5         | 0.21%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 798x334mm 34.1-inch              | 5         | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5         | 0.21%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 5         | 0.21%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                   | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 5         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1033      | 46.26%  |
| 1366x768 (WXGA)    | 253       | 11.33%  |
| 3840x2160 (4K)     | 188       | 8.42%   |
| 2560x1440 (QHD)    | 181       | 8.11%   |
| 1920x1200 (WUXGA)  | 72        | 3.22%   |
| 2560x1600          | 64        | 2.87%   |
| 3440x1440          | 50        | 2.24%   |
| 1600x900 (HD+)     | 49        | 2.19%   |
| 1680x1050 (WSXGA+) | 39        | 1.75%   |
| 1280x800 (WXGA)    | 35        | 1.57%   |
| 1440x900 (WXGA+)   | 34        | 1.52%   |
| 2560x1080          | 31        | 1.39%   |
| 2880x1800          | 30        | 1.34%   |
| 1280x1024 (SXGA)   | 28        | 1.25%   |
| 2160x1440          | 12        | 0.54%   |
| 1360x768           | 12        | 0.54%   |
| 2256x1504          | 11        | 0.49%   |
| 3840x2400          | 10        | 0.45%   |
| 3840x1080          | 8         | 0.36%   |
| 2736x1824          | 8         | 0.36%   |
| 2288x1287          | 7         | 0.31%   |
| 1920x1280          | 6         | 0.27%   |
| 3840x1600          | 5         | 0.22%   |
| 2240x1400          | 5         | 0.22%   |
| 1920x540           | 5         | 0.22%   |
| 3456x2160          | 4         | 0.18%   |
| 3200x2000          | 4         | 0.18%   |
| 2880x1620          | 4         | 0.18%   |
| 2520x1680          | 4         | 0.18%   |
| 2160x1350          | 4         | 0.18%   |
| Unknown            | 4         | 0.18%   |
| 3072x1920          | 3         | 0.13%   |
| 2880x1920          | 3         | 0.13%   |
| 2048x1152          | 3         | 0.13%   |
| 1600x1200          | 3         | 0.13%   |
| 1024x768 (XGA)     | 3         | 0.13%   |
| 3840x1100          | 2         | 0.09%   |
| 3200x1800 (QHD+)   | 2         | 0.09%   |
| 2304x1440          | 2         | 0.09%   |
| 800x1280           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 563       | 23.69%  |
| 13      | 273       | 11.49%  |
| 14      | 261       | 10.98%  |
| 27      | 242       | 10.18%  |
| 24      | 168       | 7.07%   |
| 23      | 120       | 5.05%   |
| 21      | 111       | 4.67%   |
| 31      | 76        | 3.2%    |
| 34      | 71        | 2.99%   |
| 17      | 64        | 2.69%   |
| 16      | 62        | 2.61%   |
| 12      | 46        | 1.94%   |
| 19      | 33        | 1.39%   |
| 20      | 30        | 1.26%   |
| 22      | 29        | 1.22%   |
| 18      | 25        | 1.05%   |
| Unknown | 23        | 0.97%   |
| 11      | 19        | 0.8%    |
| 84      | 18        | 0.76%   |
| 32      | 14        | 0.59%   |
| 72      | 13        | 0.55%   |
| 28      | 13        | 0.55%   |
| 54      | 12        | 0.5%    |
| 26      | 11        | 0.46%   |
| 40      | 9         | 0.38%   |
| 35      | 9         | 0.38%   |
| 142     | 7         | 0.29%   |
| 48      | 7         | 0.29%   |
| 52      | 6         | 0.25%   |
| 10      | 6         | 0.25%   |
| 37      | 5         | 0.21%   |
| 25      | 5         | 0.21%   |
| 65      | 4         | 0.17%   |
| 49      | 3         | 0.13%   |
| 42      | 3         | 0.13%   |
| 63      | 2         | 0.08%   |
| 57      | 2         | 0.08%   |
| 38      | 2         | 0.08%   |
| 33      | 2         | 0.08%   |
| 95      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 982       | 42.22%  |
| 501-600        | 475       | 20.42%  |
| 201-300        | 233       | 10.02%  |
| 401-500        | 204       | 8.77%   |
| 601-700        | 123       | 5.29%   |
| 351-400        | 91        | 3.91%   |
| 701-800        | 87        | 3.74%   |
| 1001-1500      | 34        | 1.46%   |
| 1501-2000      | 33        | 1.42%   |
| 801-900        | 28        | 1.2%    |
| Unknown        | 23        | 0.99%   |
| More than 2000 | 7         | 0.3%    |
| 901-1000       | 5         | 0.21%   |
| 1-100          | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1567      | 74.9%   |
| 16/10   | 318       | 15.2%   |
| 21/9    | 87        | 4.16%   |
| 3/2     | 50        | 2.39%   |
| 5/4     | 26        | 1.24%   |
| 4/3     | 10        | 0.48%   |
| 32/9    | 8         | 0.38%   |
| 1.00    | 8         | 0.38%   |
| Unknown | 8         | 0.38%   |
| 6/5     | 3         | 0.14%   |
| 3.40    | 2         | 0.1%    |
| 0.56    | 2         | 0.1%    |
| 2.12    | 1         | 0.05%   |
| 0.67    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 571       | 24.22%  |
| 81-90          | 410       | 17.39%  |
| 201-250        | 319       | 13.53%  |
| 301-350        | 249       | 10.56%  |
| 351-500        | 179       | 7.59%   |
| 71-80          | 116       | 4.92%   |
| 151-200        | 100       | 4.24%   |
| 251-300        | 74        | 3.14%   |
| More than 1000 | 70        | 2.97%   |
| 111-120        | 54        | 2.29%   |
| 121-130        | 51        | 2.16%   |
| 61-70          | 39        | 1.65%   |
| 141-150        | 30        | 1.27%   |
| 501-1000       | 29        | 1.23%   |
| Unknown        | 23        | 0.98%   |
| 51-60          | 22        | 0.93%   |
| 91-100         | 13        | 0.55%   |
| 41-50          | 5         | 0.21%   |
| 131-140        | 3         | 0.13%   |
| 1-40           | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 755       | 33.06%  |
| 51-100        | 604       | 26.44%  |
| 101-120       | 486       | 21.28%  |
| 161-240       | 276       | 12.08%  |
| More than 240 | 85        | 3.72%   |
| 1-50          | 55        | 2.41%   |
| Unknown       | 23        | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1526      | 74.15%  |
| 2     | 396       | 19.24%  |
| 0     | 81        | 3.94%   |
| 3     | 50        | 2.43%   |
| 4     | 5         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1110      | 36.9%   |
| Realtek Semiconductor             | 1058      | 35.17%  |
| Qualcomm Atheros                  | 187       | 6.22%   |
| Broadcom                          | 167       | 5.55%   |
| MediaTek                          | 130       | 4.32%   |
| TP-Link                           | 37        | 1.23%   |
| ASIX Electronics                  | 27        | 0.9%    |
| Broadcom Limited                  | 25        | 0.83%   |
| Ralink Technology                 | 22        | 0.73%   |
| Ralink                            | 19        | 0.63%   |
| Qualcomm                          | 17        | 0.57%   |
| Lenovo                            | 17        | 0.57%   |
| Samsung Electronics               | 15        | 0.5%    |
| Microsoft                         | 15        | 0.5%    |
| Aquantia                          | 14        | 0.47%   |
| Marvell Technology Group          | 12        | 0.4%    |
| Xiaomi                            | 11        | 0.37%   |
| Nvidia                            | 9         | 0.3%    |
| DisplayLink                       | 9         | 0.3%    |
| Sierra Wireless                   | 8         | 0.27%   |
| Qualcomm Atheros Communications   | 8         | 0.27%   |
| OPPO Electronics                  | 7         | 0.23%   |
| NetGear                           | 7         | 0.23%   |
| Dell                              | 7         | 0.23%   |
| Mellanox Technologies             | 6         | 0.2%    |
| Hewlett-Packard                   | 5         | 0.17%   |
| Google                            | 5         | 0.17%   |
| D-Link                            | 5         | 0.17%   |
| ASUSTek Computer                  | 5         | 0.17%   |
| ICS Advent                        | 3         | 0.1%    |
| Huawei Technologies               | 3         | 0.1%    |
| ZyDAS                             | 2         | 0.07%   |
| Wilocity                          | 2         | 0.07%   |
| STMicroelectronics                | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| Ericsson Business Mobile Networks | 2         | 0.07%   |
| AVM                               | 2         | 0.07%   |
| Apple                             | 2         | 0.07%   |
| WEMOS.CC                          | 1         | 0.03%   |
| VIA Technologies                  | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 684       | 19.22%  |
| Intel Wi-Fi 6 AX200                                               | 143       | 4.02%   |
| Intel Wi-Fi 6 AX201                                               | 107       | 3.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 87        | 2.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 84        | 2.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 76        | 2.14%   |
| Intel Wireless 8265 / 8275                                        | 75        | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 68        | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 60        | 1.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 59        | 1.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 56        | 1.57%   |
| Intel Ethernet Controller I225-V                                  | 56        | 1.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 1.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 50        | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 48        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 45        | 1.26%   |
| Intel I211 Gigabit Network Connection                             | 41        | 1.15%   |
| Intel Wireless 7265                                               | 40        | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 33        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 33        | 0.93%   |
| Intel Wireless 8260                                               | 33        | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 33        | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 32        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32        | 0.9%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 31        | 0.87%   |
| Intel Wireless 7260                                               | 30        | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 28        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 27        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 0.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 25        | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 24        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 0.67%   |
| Intel Wireless 3165                                               | 23        | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                     | 22        | 0.62%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 21        | 0.59%   |
| Intel Ethernet Connection (2) I219-V                              | 20        | 0.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 20        | 0.56%   |
| Intel Wireless-AC 9260                                            | 19        | 0.53%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 19        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 938       | 52.11%  |
| Realtek Semiconductor                 | 276       | 15.33%  |
| Qualcomm Atheros                      | 156       | 8.67%   |
| MediaTek                              | 129       | 7.17%   |
| Broadcom                              | 129       | 7.17%   |
| TP-Link                               | 34        | 1.89%   |
| Ralink Technology                     | 22        | 1.22%   |
| Broadcom Limited                      | 21        | 1.17%   |
| Ralink                                | 19        | 1.06%   |
| Qualcomm                              | 12        | 0.67%   |
| Microsoft                             | 12        | 0.67%   |
| Sierra Wireless                       | 8         | 0.44%   |
| Qualcomm Atheros Communications       | 8         | 0.44%   |
| NetGear                               | 7         | 0.39%   |
| ASUSTek Computer                      | 5         | 0.28%   |
| Marvell Technology Group              | 4         | 0.22%   |
| Dell                                  | 4         | 0.22%   |
| ZyDAS                                 | 2         | 0.11%   |
| Wilocity                              | 2         | 0.11%   |
| D-Link                                | 2         | 0.11%   |
| AVM                                   | 2         | 0.11%   |
| Sitecom Europe                        | 1         | 0.06%   |
| Quectel Wireless Solutions            | 1         | 0.06%   |
| Qualcomm Technologies                 | 1         | 0.06%   |
| Mercucys                              | 1         | 0.06%   |
| Hewlett-Packard                       | 1         | 0.06%   |
| Edimax Technology                     | 1         | 0.06%   |
| Belkin Components                     | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 143       | 7.9%    |
| Intel Wi-Fi 6 AX201                                            | 107       | 5.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 84        | 4.64%   |
| Intel Wireless 8265 / 8275                                     | 75        | 4.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 60        | 3.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 59        | 3.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 56        | 3.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 50        | 2.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 48        | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 45        | 2.49%   |
| Intel Wireless 7265                                            | 40        | 2.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 33        | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 33        | 1.82%   |
| Intel Wireless 8260                                            | 33        | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 33        | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 32        | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 32        | 1.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 31        | 1.71%   |
| Intel Wireless 7260                                            | 30        | 1.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 28        | 1.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 27        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 25        | 1.38%   |
| Intel Wireless 3165                                            | 23        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 22        | 1.22%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 21        | 1.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 20        | 1.11%   |
| Intel Wireless-AC 9260                                         | 19        | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 18        | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 18        | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 1%      |
| Intel Alder Lake-S PCH CNVi WiFi                               | 17        | 0.94%   |
| Realtek 802.11ac NIC                                           | 16        | 0.88%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 16        | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 0.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 14        | 0.77%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 13        | 0.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 12        | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 924       | 54.77%  |
| Intel                                  | 485       | 28.75%  |
| Broadcom                               | 69        | 4.09%   |
| Qualcomm Atheros                       | 44        | 2.61%   |
| ASIX Electronics                       | 27        | 1.6%    |
| Lenovo                                 | 17        | 1.01%   |
| Samsung Electronics                    | 15        | 0.89%   |
| Aquantia                               | 14        | 0.83%   |
| Xiaomi                                 | 11        | 0.65%   |
| Nvidia                                 | 9         | 0.53%   |
| DisplayLink                            | 9         | 0.53%   |
| Marvell Technology Group               | 8         | 0.47%   |
| OPPO Electronics                       | 7         | 0.41%   |
| Qualcomm                               | 5         | 0.3%    |
| Mellanox Technologies                  | 5         | 0.3%    |
| Google                                 | 5         | 0.3%    |
| Broadcom Limited                       | 4         | 0.24%   |
| TP-Link                                | 3         | 0.18%   |
| Microsoft                              | 3         | 0.18%   |
| ICS Advent                             | 3         | 0.18%   |
| Hewlett-Packard                        | 3         | 0.18%   |
| D-Link                                 | 3         | 0.18%   |
| Huawei Technologies                    | 2         | 0.12%   |
| Apple                                  | 2         | 0.12%   |
| VIA Technologies                       | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| MediaTek                               | 1         | 0.06%   |
| JMicron Technology                     | 1         | 0.06%   |
| IBM                                    | 1         | 0.06%   |
| HMD Global                             | 1         | 0.06%   |
| Dell                                   | 1         | 0.06%   |
| 3Com                                   | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 684       | 39.58%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 87        | 5.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 76        | 4.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 68        | 3.94%   |
| Intel Ethernet Controller I225-V                                  | 56        | 3.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 2.95%   |
| Intel I211 Gigabit Network Connection                             | 41        | 2.37%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 24        | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 20        | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 1.1%    |
| Intel Ethernet Connection (4) I219-V                              | 19        | 1.1%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 1.04%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.87%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 13        | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 12        | 0.69%   |
| Intel Ethernet Connection (16) I219-V                             | 12        | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.64%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.52%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.52%   |
| Intel Ethernet Connection (16) I219-LM                            | 9         | 0.52%   |
| Intel Ethernet Connection (14) I219-V                             | 9         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.46%   |
| Nvidia MCP79 Ethernet                                             | 8         | 0.46%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 7         | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.41%   |
| OPPO OnePlus Nord                                                 | 6         | 0.35%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 6         | 0.35%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1718      | 51.98%  |
| Ethernet | 1567      | 47.41%  |
| Modem    | 15        | 0.45%   |
| Unknown  | 5         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1355      | 63.62%  |
| Ethernet | 775       | 36.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1060      | 51.91%  |
| 1     | 879       | 43.05%  |
| 3     | 49        | 2.4%    |
| 0     | 38        | 1.86%   |
| 4     | 12        | 0.59%   |
| 6     | 2         | 0.1%    |
| 5     | 2         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1426      | 69.53%  |
| Yes  | 625       | 30.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 831       | 53.47%  |
| Realtek Semiconductor           | 171       | 11%     |
| Foxconn / Hon Hai               | 84        | 5.41%   |
| Qualcomm Atheros Communications | 77        | 4.95%   |
| IMC Networks                    | 68        | 4.38%   |
| Apple                           | 65        | 4.18%   |
| Broadcom                        | 54        | 3.47%   |
| Cambridge Silicon Radio         | 53        | 3.41%   |
| Lite-On Technology              | 30        | 1.93%   |
| MediaTek                        | 24        | 1.54%   |
| Realtek                         | 15        | 0.97%   |
| ASUSTek Computer                | 15        | 0.97%   |
| Dell                            | 10        | 0.64%   |
| TP-Link                         | 8         | 0.51%   |
| Hewlett-Packard                 | 8         | 0.51%   |
| USI                             | 7         | 0.45%   |
| Opticis                         | 6         | 0.39%   |
| Ralink                          | 5         | 0.32%   |
| Toshiba                         | 4         | 0.26%   |
| Marvell Semiconductor           | 4         | 0.26%   |
| Foxconn International           | 4         | 0.26%   |
| Askey Computer                  | 2         | 0.13%   |
| Unknown                         | 2         | 0.13%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Syntek                          | 1         | 0.06%   |
| Smart Modular Technologies      | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| D-Link                          | 1         | 0.06%   |
| AVM                             | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 207       | 13.31%  |
| Intel Bluetooth wireless interface                  | 186       | 11.96%  |
| Realtek Bluetooth Radio                             | 144       | 9.26%   |
| Intel AX200 Bluetooth                               | 138       | 8.87%   |
| Intel Bluetooth Device                              | 111       | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 102       | 6.56%   |
| Intel AX210 Bluetooth                               | 56        | 3.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 53        | 3.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 47        | 3.02%   |
| IMC Networks Wireless_Device                        | 36        | 2.32%   |
| Foxconn / Hon Hai Wireless_Device                   | 33        | 2.12%   |
| Apple Bluetooth Host Controller                     | 31        | 1.99%   |
| MediaTek Wireless_Device                            | 24        | 1.54%   |
| Apple Bluetooth USB Host Controller                 | 23        | 1.48%   |
| Realtek  Bluetooth 4.2 Adapter                      | 22        | 1.41%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 22        | 1.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 1.22%   |
| IMC Networks Bluetooth Radio                        | 19        | 1.22%   |
| Realtek 802.11ac WLAN Adapter                       | 14        | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 11        | 0.71%   |
| IMC Networks Bluetooth Device                       | 11        | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 9         | 0.58%   |
| TP-Link UB5A Adapter                                | 8         | 0.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 0.51%   |
| USI Bluetooth Device                                | 7         | 0.45%   |
| Lite-On Wireless_Device                             | 7         | 0.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 0.39%   |
| Opticis Bluetooth Radio                             | 6         | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.39%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 6         | 0.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.39%   |
| Broadcom BCM2045B (BDC-2.1)                         | 6         | 0.39%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.32%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.32%   |
| ASUS ASUS USB-BT500                                 | 5         | 0.32%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1348      | 45.82%  |
| AMD                                             | 699       | 23.76%  |
| Nvidia                                          | 473       | 16.08%  |
| C-Media Electronics                             | 58        | 1.97%   |
| Logitech                                        | 31        | 1.05%   |
| ASUSTek Computer                                | 23        | 0.78%   |
| Realtek Semiconductor                           | 21        | 0.71%   |
| Lenovo                                          | 21        | 0.71%   |
| JMTek                                           | 17        | 0.58%   |
| Razer USA                                       | 15        | 0.51%   |
| Kingston Technology                             | 15        | 0.51%   |
| GN Netcom                                       | 14        | 0.48%   |
| SteelSeries ApS                                 | 13        | 0.44%   |
| Micro Star International                        | 11        | 0.37%   |
| Generalplus Technology                          | 11        | 0.37%   |
| Focusrite-Novation                              | 10        | 0.34%   |
| Creative Labs                                   | 10        | 0.34%   |
| Creative Technology                             | 9         | 0.31%   |
| Sony                                            | 8         | 0.27%   |
| Hewlett-Packard                                 | 8         | 0.27%   |
| Corsair                                         | 8         | 0.27%   |
| Texas Instruments                               | 7         | 0.24%   |
| Dell                                            | 5         | 0.17%   |
| Samson Technologies                             | 4         | 0.14%   |
| RODE Microphones                                | 4         | 0.14%   |
| Plantronics                                     | 4         | 0.14%   |
| KTMicro                                         | 4         | 0.14%   |
| FIFINE Microphones                              | 4         | 0.14%   |
| Audio-Technica                                  | 4         | 0.14%   |
| Zoran Co. Personal Media Division (Nogatech)    | 3         | 0.1%    |
| Yamaha                                          | 3         | 0.1%    |
| Schiit Audio                                    | 3         | 0.1%    |
| Microsoft                                       | 3         | 0.1%    |
| BEHRINGER International                         | 3         | 0.1%    |
| VIA Technologies                                | 2         | 0.07%   |
| Unknown                                         | 2         | 0.07%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.07%   |
| Jieli Technology                                | 2         | 0.07%   |
| JBL                                             | 2         | 0.07%   |
| FiiO Electronics Technology                     | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 367       | 10.23%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 208       | 5.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 165       | 4.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 130       | 3.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 113       | 3.15%   |
| AMD Starship/Matisse HD Audio Controller                                   | 109       | 3.04%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 104       | 2.9%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 83        | 2.31%   |
| Intel Cannon Lake PCH cAVS                                                 | 79        | 2.2%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 79        | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 64        | 1.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 62        | 1.73%   |
| Nvidia Audio device                                                        | 55        | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 53        | 1.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 53        | 1.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 49        | 1.37%   |
| Nvidia GA106 High Definition Audio Controller                              | 45        | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 45        | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 44        | 1.23%   |
| Intel 200 Series PCH HD Audio                                              | 44        | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 42        | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 41        | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 41        | 1.14%   |
| Nvidia GA104 High Definition Audio Controller                              | 40        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 40        | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 39        | 1.09%   |
| Intel 8 Series HD Audio Controller                                         | 39        | 1.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 35        | 0.98%   |
| Intel Broadwell-U Audio Controller                                         | 33        | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 33        | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 32        | 0.89%   |
| Intel Alder Lake-S HD Audio Controller                                     | 32        | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 31        | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 30        | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 30        | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 30        | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                              | 28        | 0.78%   |
| AMD FCH Azalia Controller                                                  | 25        | 0.7%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 24        | 0.67%   |
| Intel CM238 HD Audio Controller                                            | 24        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 217       | 24.08%  |
| SK hynix                     | 150       | 16.65%  |
| Micron Technology            | 115       | 12.76%  |
| Kingston                     | 84        | 9.32%   |
| Crucial                      | 64        | 7.1%    |
| Corsair                      | 52        | 5.77%   |
| Unknown                      | 45        | 4.99%   |
| G.Skill                      | 35        | 3.88%   |
| A-DATA Technology            | 23        | 2.55%   |
| Unknown                      | 18        | 2%      |
| Ramaxel Technology           | 16        | 1.78%   |
| Smart                        | 10        | 1.11%   |
| Team                         | 7         | 0.78%   |
| Teikon                       | 6         | 0.67%   |
| Elpida                       | 5         | 0.55%   |
| Unknown (ABCD)               | 4         | 0.44%   |
| Nanya Technology             | 4         | 0.44%   |
| V-GeN                        | 3         | 0.33%   |
| Timetec                      | 3         | 0.33%   |
| GOODRAM                      | 3         | 0.33%   |
| Apacer                       | 3         | 0.33%   |
| 4ea5                         | 3         | 0.33%   |
| Qumo                         | 2         | 0.22%   |
| PNY                          | 2         | 0.22%   |
| Patriot                      | 2         | 0.22%   |
| ff                           | 2         | 0.22%   |
| CSX                          | 2         | 0.22%   |
| AMD                          | 2         | 0.22%   |
| Unknown (0x5846)             | 1         | 0.11%   |
| Unknown (0x0E9D)             | 1         | 0.11%   |
| Unknown (0x0B5E)             | 1         | 0.11%   |
| Transcend                    | 1         | 0.11%   |
| Silicon Power                | 1         | 0.11%   |
| Sesame                       | 1         | 0.11%   |
| PUSKILL                      | 1         | 0.11%   |
| Patriot Memory (PDP Systems) | 1         | 0.11%   |
| Neo Forza                    | 1         | 0.11%   |
| Mushkin                      | 1         | 0.11%   |
| Lexar                        | 1         | 0.11%   |
| Goldkey                      | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 18        | 1.92%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.17%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.07%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.75%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.75%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 6         | 0.64%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.64%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.53%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.53%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 5         | 0.53%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5         | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 4         | 0.43%   |
| Smart RAM SH564128FH8N0TNSDR 4GB DIMM DDR3 1600MT/s              | 4         | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.43%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.43%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.43%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 4         | 0.43%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s          | 4         | 0.43%   |
| Crucial RAM CT32G48C40S5.M16A1 32GB SODIMM DDR5 4800MT/s         | 4         | 0.43%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s          | 4         | 0.43%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.43%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 4         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 0.32%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.32%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 3         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 439       | 56.72%  |
| DDR3    | 140       | 18.09%  |
| DDR5    | 55        | 7.11%   |
| LPDDR4  | 42        | 5.43%   |
| LPDDR5  | 35        | 4.52%   |
| LPDDR3  | 30        | 3.88%   |
| DDR2    | 12        | 1.55%   |
| Unknown | 11        | 1.42%   |
| SDRAM   | 6         | 0.78%   |
| DRAM    | 3         | 0.39%   |
| DDR     | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 439       | 56.28%  |
| DIMM         | 211       | 27.05%  |
| Row Of Chips | 116       | 14.87%  |
| Unknown      | 8         | 1.03%   |
| Chip         | 5         | 0.64%   |
| RIMM         | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 363       | 43.58%  |
| 4096  | 172       | 20.65%  |
| 16384 | 168       | 20.17%  |
| 2048  | 63        | 7.56%   |
| 32768 | 53        | 6.36%   |
| 1024  | 14        | 1.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 226       | 27.2%   |
| 2667    | 111       | 13.36%  |
| 1600    | 93        | 11.19%  |
| 2400    | 51        | 6.14%   |
| 2133    | 41        | 4.93%   |
| 6400    | 38        | 4.57%   |
| 4800    | 38        | 4.57%   |
| 3600    | 32        | 3.85%   |
| 4267    | 26        | 3.13%   |
| 1333    | 24        | 2.89%   |
| 1867    | 19        | 2.29%   |
| 1334    | 14        | 1.68%   |
| 1067    | 10        | 1.2%    |
| 3266    | 9         | 1.08%   |
| 667     | 8         | 0.96%   |
| 5600    | 7         | 0.84%   |
| 3400    | 6         | 0.72%   |
| 800     | 6         | 0.72%   |
| Unknown | 6         | 0.72%   |
| 3800    | 5         | 0.6%    |
| 4266    | 4         | 0.48%   |
| 3534    | 4         | 0.48%   |
| 1866    | 4         | 0.48%   |
| 6000    | 3         | 0.36%   |
| 3733    | 3         | 0.36%   |
| 3000    | 3         | 0.36%   |
| 2933    | 3         | 0.36%   |
| 2800    | 3         | 0.36%   |
| 2666    | 3         | 0.36%   |
| 5200    | 2         | 0.24%   |
| 3334    | 2         | 0.24%   |
| 2448    | 2         | 0.24%   |
| 1800    | 2         | 0.24%   |
| 1639    | 2         | 0.24%   |
| 1400    | 2         | 0.24%   |
| 1066    | 2         | 0.24%   |
| 400     | 2         | 0.24%   |
| 12800   | 1         | 0.12%   |
| 8400    | 1         | 0.12%   |
| 5800    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 46.43%  |
| Seiko Epson         | 5         | 17.86%  |
| Samsung Electronics | 2         | 7.14%   |
| Dymo-CoStar         | 2         | 7.14%   |
| Canon               | 2         | 7.14%   |
| Brother Industries  | 2         | 7.14%   |
| STMicroelectronics  | 1         | 3.57%   |
| Pantum              | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 7.14%   |
| HP LaserJet P1102                                                     | 2         | 7.14%   |
| HP LaserJet 1010                                                      | 2         | 7.14%   |
| STMicroelectronics USB Printing Support                               | 1         | 3.57%   |
| Seiko Epson WF-2860 Series                                            | 1         | 3.57%   |
| Seiko Epson L120 Series                                               | 1         | 3.57%   |
| Seiko Epson ET-2710 Series                                            | 1         | 3.57%   |
| Samsung ML-216x Series Laser Printer                                  | 1         | 3.57%   |
| Samsung M2070 Series                                                  | 1         | 3.57%   |
| Pantum M6500W-series                                                  | 1         | 3.57%   |
| HP LaserJet Professional P1102w                                       | 1         | 3.57%   |
| HP LaserJet 1020                                                      | 1         | 3.57%   |
| HP Ink Tank 310 series                                                | 1         | 3.57%   |
| HP ENVY Photo 7800 series                                             | 1         | 3.57%   |
| HP ENVY Inspire 7200 series                                           | 1         | 3.57%   |
| HP ENVY 5000 series                                                   | 1         | 3.57%   |
| HP DeskJet 3700 series                                                | 1         | 3.57%   |
| HP DeskJet 2600 series                                                | 1         | 3.57%   |
| HP Deskjet 2050 J510                                                  | 1         | 3.57%   |
| Dymo-CoStar LabelWriter 400                                           | 1         | 3.57%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 1         | 3.57%   |
| Canon TR4500 series                                                   | 1         | 3.57%   |
| Canon PIXMA MP250                                                     | 1         | 3.57%   |
| Brother HL-2130 series                                                | 1         | 3.57%   |
| Brother HL-1440 Laser Printer                                         | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 75%     |
| Seiko Epson | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210               | 2         | 50%     |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 25%     |
| Canon CanoScan 4400F                  | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 232       | 16.89%  |
| IMC Networks                           | 158       | 11.5%   |
| Bison Electronics                      | 110       | 8.01%   |
| Microdia                               | 109       | 7.93%   |
| Logitech                               | 98        | 7.13%   |
| Quanta                                 | 96        | 6.99%   |
| Realtek Semiconductor                  | 84        | 6.11%   |
| Apple                                  | 67        | 4.88%   |
| Sunplus Innovation Technology          | 62        | 4.51%   |
| Cheng Uei Precision Industry (Foxlink) | 45        | 3.28%   |
| Luxvisions Innotech Limited            | 43        | 3.13%   |
| Sonix Technology                       | 34        | 2.47%   |
| Syntek                                 | 33        | 2.4%    |
| Lite-On Technology                     | 22        | 1.6%    |
| Acer                                   | 19        | 1.38%   |
| Suyin                                  | 17        | 1.24%   |
| Microsoft                              | 14        | 1.02%   |
| SunplusIT                              | 11        | 0.8%    |
| Alcor Micro                            | 9         | 0.66%   |
| Samsung Electronics                    | 7         | 0.51%   |
| Silicon Motion                         | 6         | 0.44%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 0.44%   |
| Lenovo                                 | 6         | 0.44%   |
| Unknown                                | 6         | 0.44%   |
| Razer USA                              | 5         | 0.36%   |
| AVerMedia Technologies                 | 5         | 0.36%   |
| Ricoh                                  | 4         | 0.29%   |
| Importek                               | 4         | 0.29%   |
| Trust                                  | 3         | 0.22%   |
| Google                                 | 3         | 0.22%   |
| Generalplus Technology                 | 3         | 0.22%   |
| Cubeternet                             | 3         | 0.22%   |
| Z-Star Microelectronics                | 2         | 0.15%   |
| XHT-211220-ZW                          | 2         | 0.15%   |
| Unknown (3730304231385031345945)       | 2         | 0.15%   |
| Tobii Technology AB                    | 2         | 0.15%   |
| ShineTech                              | 2         | 0.15%   |
| Primax Electronics                     | 2         | 0.15%   |
| MacroSilicon                           | 2         | 0.15%   |
| LG Electronics                         | 2         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 80        | 5.78%   |
| Microdia Integrated_Webcam_HD                       | 64        | 4.62%   |
| IMC Networks Integrated Camera                      | 59        | 4.26%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 49        | 3.54%   |
| Bison Integrated Camera                             | 46        | 3.32%   |
| Realtek Integrated_Webcam_HD                        | 43        | 3.1%    |
| Syntek Integrated Camera                            | 27        | 1.95%   |
| Logitech HD Pro Webcam C920                         | 24        | 1.73%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 20        | 1.44%   |
| Sunplus Integrated_Webcam_HD                        | 19        | 1.37%   |
| Sonix USB2.0 FHD UVC WebCam                         | 17        | 1.23%   |
| Apple FaceTime HD Camera                            | 17        | 1.23%   |
| Quanta HP Wide Vision HD Camera                     | 16        | 1.16%   |
| Quanta HD User Facing                               | 16        | 1.16%   |
| Chicony HD WebCam                                   | 16        | 1.16%   |
| Sonix USB2.0 HD UVC WebCam                          | 15        | 1.08%   |
| Bison Integrated RGB Camera                         | 15        | 1.08%   |
| Logitech Webcam C270                                | 14        | 1.01%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 14        | 1.01%   |
| Apple FaceTime HD Camera (Built-in)                 | 14        | 1.01%   |
| Bison HD Webcam                                     | 13        | 0.94%   |
| Lite-On Integrated Camera                           | 12        | 0.87%   |
| Chicony Integrated Camera (1280x720@30)             | 12        | 0.87%   |
| Apple Built-in iSight                               | 12        | 0.87%   |
| Luxvisions Innotech Limited Integrated Camera       | 11        | 0.79%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 10        | 0.72%   |
| IMC Networks HD Camera                              | 10        | 0.72%   |
| Chicony HP TrueVision HD Camera                     | 10        | 0.72%   |
| Quanta HD Camera                                    | 9         | 0.65%   |
| Microdia Integrated_Webcam_FHD                      | 9         | 0.65%   |
| Chicony HP Wide Vision HD Camera                    | 9         | 0.65%   |
| Quanta HP HD Camera                                 | 8         | 0.58%   |
| Quanta ACER HD User Facing                          | 8         | 0.58%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 8         | 0.58%   |
| Logitech HD Webcam C525                             | 8         | 0.58%   |
| Chicony HP HD Camera                                | 8         | 0.58%   |
| Chicony HD User Facing                              | 8         | 0.58%   |
| Bison SunplusIT Integrated Camera                   | 8         | 0.58%   |
| Samsung Galaxy series, misc. (MTP mode)             | 7         | 0.51%   |
| Quanta HD Webcam                                    | 7         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 99        | 31.94%  |
| Shenzhen Goodix Technology         | 75        | 24.19%  |
| Validity Sensors                   | 60        | 19.35%  |
| Elan Microelectronics              | 30        | 9.68%   |
| Upek                               | 12        | 3.87%   |
| Realtek USB2.0 Finger Print Bridge | 11        | 3.55%   |
| LighTuning Technology              | 9         | 2.9%    |
| AuthenTec                          | 8         | 2.58%   |
| Samsung Electronics                | 4         | 1.29%   |
| STMicroelectronics                 | 1         | 0.32%   |
| Focal-systems.Corp                 | 1         | 0.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 50        | 16.13%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 8.71%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 6.13%   |
| Elan ELAN:ARM-M4                                                           | 18        | 5.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 5.48%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.87%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 3.87%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 11        | 3.55%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 3.23%   |
| Synaptics WBDI                                                             | 8         | 2.58%   |
| Synaptics UWP WBDI Device                                                  | 8         | 2.58%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 2.58%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 2.58%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.58%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 2.26%   |
| Synaptics UWP WBDI                                                         | 6         | 1.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.61%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 1.61%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.61%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 1.29%   |
| Synaptics  WBDI                                                            | 4         | 1.29%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.29%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 1.29%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 0.97%   |
| Validity Sensors VFS491                                                    | 3         | 0.97%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.97%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 0.97%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.65%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.65%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.65%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.65%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 0.65%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.65%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.32%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.32%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 58        | 56.86%  |
| Alcor Micro           | 25        | 24.51%  |
| Upek                  | 5         | 4.9%    |
| Lenovo                | 4         | 3.92%   |
| Gemalto (was Gemplus) | 3         | 2.94%   |
| Yubico.com            | 2         | 1.96%   |
| O2 Micro              | 2         | 1.96%   |
| Realtek Semiconductor | 1         | 0.98%   |
| Cherry                | 1         | 0.98%   |
| BIT4ID                | 1         | 0.98%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 28        | 27.45%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 24.51%  |
| Broadcom 5880                                                                | 12        | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 8.82%   |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 8.82%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.9%    |
| Lenovo Integrated Smart Card Reader                                          | 4         | 3.92%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.96%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.96%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.98%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.98%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.98%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.98%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.98%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.98%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1339      | 65.03%  |
| 1     | 581       | 28.22%  |
| 2     | 118       | 5.73%   |
| 3     | 15        | 0.73%   |
| 6     | 2         | 0.1%    |
| 4     | 2         | 0.1%    |
| 8     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 305       | 35.67%  |
| Graphics card            | 211       | 24.68%  |
| Multimedia controller    | 123       | 14.39%  |
| Net/wireless             | 91        | 10.64%  |
| Camera                   | 22        | 2.57%   |
| Chipcard                 | 18        | 2.11%   |
| Bluetooth                | 18        | 2.11%   |
| Unassigned class         | 14        | 1.64%   |
| Communication controller | 14        | 1.64%   |
| Sound                    | 12        | 1.4%    |
| Storage                  | 9         | 1.05%   |
| Card reader              | 8         | 0.94%   |
| Net/ethernet             | 5         | 0.58%   |
| Network                  | 2         | 0.23%   |
| Modem                    | 2         | 0.23%   |
| Storage/nvme             | 1         | 0.12%   |

