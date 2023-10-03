Linux in UK - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

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

Total: 12009

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | XPS 15 9500                 | Notebook    | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| Acer          | Predator G9-793             | Notebook    | [fd305490af](https://linux-hardware.org/?probe=fd305490af) | Oct 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [1448f32279](https://linux-hardware.org/?probe=1448f32279) | Oct 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [d64d0a1997](https://linux-hardware.org/?probe=d64d0a1997) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0b4432877e](https://linux-hardware.org/?probe=0b4432877e) | Sep 30, 2023 |
| Entroware     | Hybris                      | Notebook    | [5b124e9b7f](https://linux-hardware.org/?probe=5b124e9b7f) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | Desktop     | [1dbbeda8cd](https://linux-hardware.org/?probe=1dbbeda8cd) | Sep 30, 2023 |
| Medion        | B660M DS3H AX DDR4          | Desktop     | [57a42b9ccf](https://linux-hardware.org/?probe=57a42b9ccf) | Sep 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [4835df59b1](https://linux-hardware.org/?probe=4835df59b1) | Sep 30, 2023 |
| HP            | Pavilion dv5                | Notebook    | [0b1da8643f](https://linux-hardware.org/?probe=0b1da8643f) | Sep 30, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [80d27e2808](https://linux-hardware.org/?probe=80d27e2808) | Sep 30, 2023 |
| Lenovo        | YB1-X91F                    | Convertible | [36523ad102](https://linux-hardware.org/?probe=36523ad102) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [2afa933d2a](https://linux-hardware.org/?probe=2afa933d2a) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [a7a8e627cb](https://linux-hardware.org/?probe=a7a8e627cb) | Sep 30, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [d74284aa9f](https://linux-hardware.org/?probe=d74284aa9f) | Sep 29, 2023 |
| Intel         | D33217CK G76541-302         | Desktop     | [d1aab6a8d0](https://linux-hardware.org/?probe=d1aab6a8d0) | Sep 29, 2023 |
| OEGStone      | C4100/C5100                 | Notebook    | [0c27e50b14](https://linux-hardware.org/?probe=0c27e50b14) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WY00    | Notebook    | [6a18fb9b21](https://linux-hardware.org/?probe=6a18fb9b21) | Sep 29, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [c602f8fba9](https://linux-hardware.org/?probe=c602f8fba9) | Sep 29, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [710a10efce](https://linux-hardware.org/?probe=710a10efce) | Sep 29, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [2a3e49f18f](https://linux-hardware.org/?probe=2a3e49f18f) | Sep 29, 2023 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [5d1175b3f3](https://linux-hardware.org/?probe=5d1175b3f3) | Sep 28, 2023 |
| HP            | 3397                        | Desktop     | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| Google        | Swanky                      | Notebook    | [599959ccbe](https://linux-hardware.org/?probe=599959ccbe) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [cb2cbda84d](https://linux-hardware.org/?probe=cb2cbda84d) | Sep 28, 2023 |
| Dell          | Precision 3560              | Notebook    | [14af02a240](https://linux-hardware.org/?probe=14af02a240) | Sep 28, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [dcf11408af](https://linux-hardware.org/?probe=dcf11408af) | Sep 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [39bc0d89fe](https://linux-hardware.org/?probe=39bc0d89fe) | Sep 28, 2023 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [31fe0087b8](https://linux-hardware.org/?probe=31fe0087b8) | Sep 28, 2023 |
| HP            | 84F5                        | Mini pc     | [ef936bc0cb](https://linux-hardware.org/?probe=ef936bc0cb) | Sep 28, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [0e08685628](https://linux-hardware.org/?probe=0e08685628) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | Notebook    | [2b7f074e47](https://linux-hardware.org/?probe=2b7f074e47) | Sep 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5M000    | Notebook    | [58ddf5337a](https://linux-hardware.org/?probe=58ddf5337a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| Dell          | Precision 5570              | Notebook    | [f00d32a04a](https://linux-hardware.org/?probe=f00d32a04a) | Sep 27, 2023 |
| Lenovo        | YB1-X91F                    | Convertible | [f5fa6cb83d](https://linux-hardware.org/?probe=f5fa6cb83d) | Sep 27, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [6bdac98313](https://linux-hardware.org/?probe=6bdac98313) | Sep 27, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [9a3f695f09](https://linux-hardware.org/?probe=9a3f695f09) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [fb82c6e942](https://linux-hardware.org/?probe=fb82c6e942) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [c7ec123b46](https://linux-hardware.org/?probe=c7ec123b46) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc0d6b9ebb](https://linux-hardware.org/?probe=cc0d6b9ebb) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [0f2a543485](https://linux-hardware.org/?probe=0f2a543485) | Sep 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [75f65a0438](https://linux-hardware.org/?probe=75f65a0438) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [277f5aca9b](https://linux-hardware.org/?probe=277f5aca9b) | Sep 26, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [4a36dbb8ff](https://linux-hardware.org/?probe=4a36dbb8ff) | Sep 26, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [1fdceb9309](https://linux-hardware.org/?probe=1fdceb9309) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [47d912c5a9](https://linux-hardware.org/?probe=47d912c5a9) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [d2a926c703](https://linux-hardware.org/?probe=d2a926c703) | Sep 26, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [461eeadd52](https://linux-hardware.org/?probe=461eeadd52) | Sep 26, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [efd53d662d](https://linux-hardware.org/?probe=efd53d662d) | Sep 25, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [2568280c44](https://linux-hardware.org/?probe=2568280c44) | Sep 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3420c7e013](https://linux-hardware.org/?probe=3420c7e013) | Sep 25, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [e7a6f47b2f](https://linux-hardware.org/?probe=e7a6f47b2f) | Sep 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [7a64b4c44f](https://linux-hardware.org/?probe=7a64b4c44f) | Sep 25, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [8b10c3ad64](https://linux-hardware.org/?probe=8b10c3ad64) | Sep 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [6185e37a03](https://linux-hardware.org/?probe=6185e37a03) | Sep 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2bb252778b](https://linux-hardware.org/?probe=2bb252778b) | Sep 25, 2023 |
| Sony          | VAIO                        | All in one  | [75e484b949](https://linux-hardware.org/?probe=75e484b949) | Sep 24, 2023 |
| Lenovo        | ThinkPad X270 20HMS0EXOO    | Notebook    | [0818b5e737](https://linux-hardware.org/?probe=0818b5e737) | Sep 24, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [53051aa7eb](https://linux-hardware.org/?probe=53051aa7eb) | Sep 24, 2023 |
| HP            | ProBook 6545b               | Notebook    | [b0abb62083](https://linux-hardware.org/?probe=b0abb62083) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | Notebook    | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [8b5b196475](https://linux-hardware.org/?probe=8b5b196475) | Sep 24, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [65d749c96e](https://linux-hardware.org/?probe=65d749c96e) | Sep 23, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [f4232cfca8](https://linux-hardware.org/?probe=f4232cfca8) | Sep 23, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [083c0510ac](https://linux-hardware.org/?probe=083c0510ac) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d3322d740d](https://linux-hardware.org/?probe=d3322d740d) | Sep 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [13a9f1d65a](https://linux-hardware.org/?probe=13a9f1d65a) | Sep 23, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [c84457748d](https://linux-hardware.org/?probe=c84457748d) | Sep 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [d464d79df3](https://linux-hardware.org/?probe=d464d79df3) | Sep 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [e473797863](https://linux-hardware.org/?probe=e473797863) | Sep 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c49107d782](https://linux-hardware.org/?probe=c49107d782) | Sep 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| HP            | 1998                        | Desktop     | [f2c4af4cb6](https://linux-hardware.org/?probe=f2c4af4cb6) | Sep 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [e63d1ae740](https://linux-hardware.org/?probe=e63d1ae740) | Sep 22, 2023 |
| HP            | 1998                        | Desktop     | [ef51f7d583](https://linux-hardware.org/?probe=ef51f7d583) | Sep 22, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [bdd8beafed](https://linux-hardware.org/?probe=bdd8beafed) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [d9d063b9e8](https://linux-hardware.org/?probe=d9d063b9e8) | Sep 22, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a437fe8bcf](https://linux-hardware.org/?probe=a437fe8bcf) | Sep 21, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [ee1cb0c5cc](https://linux-hardware.org/?probe=ee1cb0c5cc) | Sep 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c2c49834e5](https://linux-hardware.org/?probe=c2c49834e5) | Sep 21, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [54a894ffd7](https://linux-hardware.org/?probe=54a894ffd7) | Sep 21, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [6c2de2dfb8](https://linux-hardware.org/?probe=6c2de2dfb8) | Sep 21, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [dd18901106](https://linux-hardware.org/?probe=dd18901106) | Sep 21, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [92b6ccd3ad](https://linux-hardware.org/?probe=92b6ccd3ad) | Sep 21, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [6aae39a72b](https://linux-hardware.org/?probe=6aae39a72b) | Sep 21, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [66262df4c4](https://linux-hardware.org/?probe=66262df4c4) | Sep 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [043be725eb](https://linux-hardware.org/?probe=043be725eb) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2bb7ed1454](https://linux-hardware.org/?probe=2bb7ed1454) | Sep 21, 2023 |
| Dell          | 0RY206                      | Desktop     | [11a31518a3](https://linux-hardware.org/?probe=11a31518a3) | Sep 20, 2023 |
| ASUSTek       | X501A                       | Notebook    | [5045eb238f](https://linux-hardware.org/?probe=5045eb238f) | Sep 20, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [5c5a2a36e2](https://linux-hardware.org/?probe=5c5a2a36e2) | Sep 20, 2023 |
| MSI           | Z270 GAMING M5              | Desktop     | [005d3394c9](https://linux-hardware.org/?probe=005d3394c9) | Sep 20, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [35d24c31cf](https://linux-hardware.org/?probe=35d24c31cf) | Sep 20, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3434dd8b54](https://linux-hardware.org/?probe=3434dd8b54) | Sep 20, 2023 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [e4686e182a](https://linux-hardware.org/?probe=e4686e182a) | Sep 19, 2023 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [2bc60f54d0](https://linux-hardware.org/?probe=2bc60f54d0) | Sep 19, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8d4b7a978b](https://linux-hardware.org/?probe=8d4b7a978b) | Sep 19, 2023 |
| Dell          | Precision 5550              | Notebook    | [a1c163a7e2](https://linux-hardware.org/?probe=a1c163a7e2) | Sep 19, 2023 |
| Mini PC       | Cherry Trail CR             | Notebook    | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [2d5c5ab820](https://linux-hardware.org/?probe=2d5c5ab820) | Sep 19, 2023 |
| Samsung       | DP500A2D-A02UK SEC_SW_RE... | All in one  | [e0c767e50f](https://linux-hardware.org/?probe=e0c767e50f) | Sep 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [7baec97424](https://linux-hardware.org/?probe=7baec97424) | Sep 19, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2b913a2e83](https://linux-hardware.org/?probe=2b913a2e83) | Sep 19, 2023 |
| Lenovo        | ThinkPad T430 2349BG6       | Notebook    | [dbd8f7715f](https://linux-hardware.org/?probe=dbd8f7715f) | Sep 19, 2023 |
| Dell          | Precision 3581              | Notebook    | [e1c8eb2810](https://linux-hardware.org/?probe=e1c8eb2810) | Sep 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [85d131b5fc](https://linux-hardware.org/?probe=85d131b5fc) | Sep 18, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [f2d4f47a8e](https://linux-hardware.org/?probe=f2d4f47a8e) | Sep 18, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [144dcee0ae](https://linux-hardware.org/?probe=144dcee0ae) | Sep 18, 2023 |
| Intel         | NUC5i5MYBE H47797-203       | Mini pc     | [c66e0fc949](https://linux-hardware.org/?probe=c66e0fc949) | Sep 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [2d2ec7d22c](https://linux-hardware.org/?probe=2d2ec7d22c) | Sep 18, 2023 |
| Gigabyte      | Z97P-D3                     | Desktop     | [3baa74b1a6](https://linux-hardware.org/?probe=3baa74b1a6) | Sep 17, 2023 |
| Unknown       | M17PRO                      | Notebook    | [ccf362f14d](https://linux-hardware.org/?probe=ccf362f14d) | Sep 17, 2023 |
| Schenker      | XMG CORE (M19, GTX 1650)    | Notebook    | [612bda7c21](https://linux-hardware.org/?probe=612bda7c21) | Sep 17, 2023 |
| Lenovo        | 3181 NO DPK                 | Mini pc     | [53531ff3b6](https://linux-hardware.org/?probe=53531ff3b6) | Sep 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [7e958c35eb](https://linux-hardware.org/?probe=7e958c35eb) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [cd0090bea7](https://linux-hardware.org/?probe=cd0090bea7) | Sep 16, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [a16a2ef714](https://linux-hardware.org/?probe=a16a2ef714) | Sep 16, 2023 |
| MSI           | GS43VR 7RE                  | Notebook    | [d9893a35c8](https://linux-hardware.org/?probe=d9893a35c8) | Sep 16, 2023 |
| Acer          | Aspire 5720                 | Notebook    | [9bfcaaa71a](https://linux-hardware.org/?probe=9bfcaaa71a) | Sep 16, 2023 |
| Acer          | Aspire 5720                 | Notebook    | [bad46323d7](https://linux-hardware.org/?probe=bad46323d7) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [cd5cabf48f](https://linux-hardware.org/?probe=cd5cabf48f) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| Dell          | XPS 9320                    | Notebook    | [99fce2103f](https://linux-hardware.org/?probe=99fce2103f) | Sep 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2d83cd3f6f](https://linux-hardware.org/?probe=2d83cd3f6f) | Sep 16, 2023 |
| HP            | Compaq 6820s                | Notebook    | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | Notebook    | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [2dae5fb442](https://linux-hardware.org/?probe=2dae5fb442) | Sep 16, 2023 |
| Dell          | Latitude E5570              | Notebook    | [fd5ba4aa5a](https://linux-hardware.org/?probe=fd5ba4aa5a) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [2073aca95d](https://linux-hardware.org/?probe=2073aca95d) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [fa484cf261](https://linux-hardware.org/?probe=fa484cf261) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [d23a7d46f3](https://linux-hardware.org/?probe=d23a7d46f3) | Sep 15, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [c1f02dd477](https://linux-hardware.org/?probe=c1f02dd477) | Sep 15, 2023 |
| ASUSTek       | UN68U                       | Mini pc     | [e71236e7af](https://linux-hardware.org/?probe=e71236e7af) | Sep 15, 2023 |
| Dell          | XPS 9320                    | Notebook    | [054584d248](https://linux-hardware.org/?probe=054584d248) | Sep 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [982f29b6cc](https://linux-hardware.org/?probe=982f29b6cc) | Sep 14, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [43020fecfb](https://linux-hardware.org/?probe=43020fecfb) | Sep 14, 2023 |
| Clevo         | P170EM                      | Notebook    | [ee87854652](https://linux-hardware.org/?probe=ee87854652) | Sep 14, 2023 |
| HP            | 0A9Ch                       | Desktop     | [4894ac01b8](https://linux-hardware.org/?probe=4894ac01b8) | Sep 14, 2023 |
| Dell          | Precision 7530              | Notebook    | [035a4eb568](https://linux-hardware.org/?probe=035a4eb568) | Sep 14, 2023 |
| Dell          | Latitude 7390               | Notebook    | [4d8e0cb72b](https://linux-hardware.org/?probe=4d8e0cb72b) | Sep 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [aea796bbd9](https://linux-hardware.org/?probe=aea796bbd9) | Sep 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ff1efba80e](https://linux-hardware.org/?probe=ff1efba80e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| Acer          | AOA150                      | Notebook    | [bc32c4814d](https://linux-hardware.org/?probe=bc32c4814d) | Sep 13, 2023 |
| Dell          | Latitude 7390               | Notebook    | [2afdbd653c](https://linux-hardware.org/?probe=2afdbd653c) | Sep 13, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c2c784daa8](https://linux-hardware.org/?probe=c2c784daa8) | Sep 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7769de42b0](https://linux-hardware.org/?probe=7769de42b0) | Sep 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8fc40b8424](https://linux-hardware.org/?probe=8fc40b8424) | Sep 12, 2023 |
| HP            | Compaq 6730b (NN204ET#AB... | Notebook    | [255f6ba979](https://linux-hardware.org/?probe=255f6ba979) | Sep 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [b360f71c3d](https://linux-hardware.org/?probe=b360f71c3d) | Sep 11, 2023 |
| HP            | 2B36                        | Desktop     | [ac92866980](https://linux-hardware.org/?probe=ac92866980) | Sep 11, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [016a705fea](https://linux-hardware.org/?probe=016a705fea) | Sep 11, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [1f61e7bc5d](https://linux-hardware.org/?probe=1f61e7bc5d) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [ff9bf89fad](https://linux-hardware.org/?probe=ff9bf89fad) | Sep 11, 2023 |
| Acer          | Aspire C20-820              | All in one  | [1b2bdeafca](https://linux-hardware.org/?probe=1b2bdeafca) | Sep 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [e4a14b2349](https://linux-hardware.org/?probe=e4a14b2349) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0ac203a0c5](https://linux-hardware.org/?probe=0ac203a0c5) | Sep 11, 2023 |
| ASUSTek       | N551JX                      | Notebook    | [8c034b254e](https://linux-hardware.org/?probe=8c034b254e) | Sep 11, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [dc3c32cc6a](https://linux-hardware.org/?probe=dc3c32cc6a) | Sep 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [793d3e47ff](https://linux-hardware.org/?probe=793d3e47ff) | Sep 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [36c9a9e4d4](https://linux-hardware.org/?probe=36c9a9e4d4) | Sep 10, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [c5be1f9523](https://linux-hardware.org/?probe=c5be1f9523) | Sep 10, 2023 |
| GreatWall     | W1011                       | Tablet      | [8b75bc883d](https://linux-hardware.org/?probe=8b75bc883d) | Sep 10, 2023 |
| Google        | Lillipup                    | Notebook    | [c3a892cdca](https://linux-hardware.org/?probe=c3a892cdca) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [3021f551f4](https://linux-hardware.org/?probe=3021f551f4) | Sep 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [6aea4eb6c4](https://linux-hardware.org/?probe=6aea4eb6c4) | Sep 09, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [15211eeedf](https://linux-hardware.org/?probe=15211eeedf) | Sep 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [249a085da0](https://linux-hardware.org/?probe=249a085da0) | Sep 09, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cdf1a3f17b](https://linux-hardware.org/?probe=cdf1a3f17b) | Sep 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [a03aa3f52d](https://linux-hardware.org/?probe=a03aa3f52d) | Sep 09, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [1474c70336](https://linux-hardware.org/?probe=1474c70336) | Sep 09, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [1715b12029](https://linux-hardware.org/?probe=1715b12029) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fd38d07a69](https://linux-hardware.org/?probe=fd38d07a69) | Sep 08, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [0429117716](https://linux-hardware.org/?probe=0429117716) | Sep 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [b5081191af](https://linux-hardware.org/?probe=b5081191af) | Sep 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [81aab795b5](https://linux-hardware.org/?probe=81aab795b5) | Sep 08, 2023 |
| Lenovo        | Yoga 6-13ALC6 Laptop 82N... | Convertible | [9c82ad0fd7](https://linux-hardware.org/?probe=9c82ad0fd7) | Sep 08, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [6870581b7c](https://linux-hardware.org/?probe=6870581b7c) | Sep 08, 2023 |
| Intel         | S5500BC E25124-456          | Server      | [d7d5249bc9](https://linux-hardware.org/?probe=d7d5249bc9) | Sep 08, 2023 |
| Dell          | Inspiron 7306 2n1           | Convertible | [5d501c1fd6](https://linux-hardware.org/?probe=5d501c1fd6) | Sep 08, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [2614f063f8](https://linux-hardware.org/?probe=2614f063f8) | Sep 07, 2023 |
| HP            | 1497                        | Desktop     | [1729554f58](https://linux-hardware.org/?probe=1729554f58) | Sep 07, 2023 |
| Shenzhen M... | AHBAA OEM                   | Desktop     | [d4e6f24af3](https://linux-hardware.org/?probe=d4e6f24af3) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4fd02051b6](https://linux-hardware.org/?probe=4fd02051b6) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [3221a3e5dd](https://linux-hardware.org/?probe=3221a3e5dd) | Sep 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bae1c4e9](https://linux-hardware.org/?probe=13bae1c4e9) | Sep 07, 2023 |
| ASRock        | Z87 Pro4                    | Desktop     | [89b861e771](https://linux-hardware.org/?probe=89b861e771) | Sep 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [16cb5e0d5b](https://linux-hardware.org/?probe=16cb5e0d5b) | Sep 06, 2023 |
| eMachines     | eM350                       | Notebook    | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 20MD0014UK      | Notebook    | [428c816118](https://linux-hardware.org/?probe=428c816118) | Sep 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | Notebook    | [f24dc99222](https://linux-hardware.org/?probe=f24dc99222) | Sep 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [af67c49814](https://linux-hardware.org/?probe=af67c49814) | Sep 06, 2023 |
| Sony          | SVF1521A7EB                 | Notebook    | [8b130feb09](https://linux-hardware.org/?probe=8b130feb09) | Sep 06, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [57764e02db](https://linux-hardware.org/?probe=57764e02db) | Sep 06, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [8b44f9cbdc](https://linux-hardware.org/?probe=8b44f9cbdc) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [f50ce96f55](https://linux-hardware.org/?probe=f50ce96f55) | Sep 06, 2023 |
| HP            | 1497                        | Desktop     | [66bc78bedb](https://linux-hardware.org/?probe=66bc78bedb) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [cd1be324d4](https://linux-hardware.org/?probe=cd1be324d4) | Sep 05, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | Notebook    | [6ab6bec7be](https://linux-hardware.org/?probe=6ab6bec7be) | Sep 05, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [306dab3d42](https://linux-hardware.org/?probe=306dab3d42) | Sep 05, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [005ebd39ce](https://linux-hardware.org/?probe=005ebd39ce) | Sep 05, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [dcb565d513](https://linux-hardware.org/?probe=dcb565d513) | Sep 04, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [80a94d69c2](https://linux-hardware.org/?probe=80a94d69c2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| HP            | Compaq 6730b (NN204ET#AB... | Notebook    | [7165368bfe](https://linux-hardware.org/?probe=7165368bfe) | Sep 04, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [464ff29a95](https://linux-hardware.org/?probe=464ff29a95) | Sep 04, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [15826e3d9e](https://linux-hardware.org/?probe=15826e3d9e) | Sep 04, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [1f2c94fe31](https://linux-hardware.org/?probe=1f2c94fe31) | Sep 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [a0e83b70f5](https://linux-hardware.org/?probe=a0e83b70f5) | Sep 03, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a30ea8885d](https://linux-hardware.org/?probe=a30ea8885d) | Sep 03, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| Dell          | G15 5511                    | Notebook    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Intel         | S5500BC E25124-456          | Server      | [f7e5a67d41](https://linux-hardware.org/?probe=f7e5a67d41) | Sep 03, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [727e431acb](https://linux-hardware.org/?probe=727e431acb) | Sep 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS24300    | Notebook    | [a28d4357d8](https://linux-hardware.org/?probe=a28d4357d8) | Sep 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [23f9814b2b](https://linux-hardware.org/?probe=23f9814b2b) | Sep 03, 2023 |
| Dell          | Studio 1735                 | Notebook    | [88cf1723e0](https://linux-hardware.org/?probe=88cf1723e0) | Sep 03, 2023 |
| ASUSTek       | STRIKER II EXTREME          | Desktop     | [eafb53342a](https://linux-hardware.org/?probe=eafb53342a) | Sep 03, 2023 |
| Framework     | Laptop                      | Notebook    | [d153316fdd](https://linux-hardware.org/?probe=d153316fdd) | Sep 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [024e3beca4](https://linux-hardware.org/?probe=024e3beca4) | Sep 03, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [720b306ad4](https://linux-hardware.org/?probe=720b306ad4) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [e6df46a4a8](https://linux-hardware.org/?probe=e6df46a4a8) | Sep 03, 2023 |
| Timi          | TM1613                      | Notebook    | [6acee9a858](https://linux-hardware.org/?probe=6acee9a858) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e0f8242693](https://linux-hardware.org/?probe=e0f8242693) | Sep 02, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [17eed28ecb](https://linux-hardware.org/?probe=17eed28ecb) | Sep 02, 2023 |
| Medion        | B460H6-EM                   | Desktop     | [ec8f0bbb13](https://linux-hardware.org/?probe=ec8f0bbb13) | Sep 02, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [56445f0197](https://linux-hardware.org/?probe=56445f0197) | Sep 02, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [9028ba6c0f](https://linux-hardware.org/?probe=9028ba6c0f) | Sep 02, 2023 |
| MSI           | A320M-A PRO M2              | Desktop     | [6745b7e37d](https://linux-hardware.org/?probe=6745b7e37d) | Sep 01, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [6cd52cad83](https://linux-hardware.org/?probe=6cd52cad83) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [5b976d122b](https://linux-hardware.org/?probe=5b976d122b) | Sep 01, 2023 |
| Dell          | Vostro 3590                 | Notebook    | [9a914c816e](https://linux-hardware.org/?probe=9a914c816e) | Sep 01, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [73147203ca](https://linux-hardware.org/?probe=73147203ca) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [2220cac066](https://linux-hardware.org/?probe=2220cac066) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [6f761aa23b](https://linux-hardware.org/?probe=6f761aa23b) | Aug 31, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [ac52854722](https://linux-hardware.org/?probe=ac52854722) | Aug 31, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [ef4d28f614](https://linux-hardware.org/?probe=ef4d28f614) | Aug 31, 2023 |
| Gigabyte      | GA-73PVM-S2H                | Desktop     | [4abb2ab82b](https://linux-hardware.org/?probe=4abb2ab82b) | Aug 31, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [cef6754cd9](https://linux-hardware.org/?probe=cef6754cd9) | Aug 31, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [9830dce088](https://linux-hardware.org/?probe=9830dce088) | Aug 31, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f0f4af9185](https://linux-hardware.org/?probe=f0f4af9185) | Aug 31, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [32d9616a38](https://linux-hardware.org/?probe=32d9616a38) | Aug 31, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [2a0a234dbf](https://linux-hardware.org/?probe=2a0a234dbf) | Aug 31, 2023 |
| AZW           | MINI S                      | Desktop     | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [aad9baafe2](https://linux-hardware.org/?probe=aad9baafe2) | Aug 31, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dffa9dee7c](https://linux-hardware.org/?probe=dffa9dee7c) | Aug 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [86b1c6ecfa](https://linux-hardware.org/?probe=86b1c6ecfa) | Aug 30, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [f468606e38](https://linux-hardware.org/?probe=f468606e38) | Aug 30, 2023 |
| ASUSTek       | S500CA                      | Notebook    | [60d87bd79b](https://linux-hardware.org/?probe=60d87bd79b) | Aug 30, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [18f51f883e](https://linux-hardware.org/?probe=18f51f883e) | Aug 30, 2023 |
| Lenovo        | ThinkPad X200 7459BN8       | Notebook    | [38c0341384](https://linux-hardware.org/?probe=38c0341384) | Aug 30, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c051ef93ac](https://linux-hardware.org/?probe=c051ef93ac) | Aug 30, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a31df2b8fe](https://linux-hardware.org/?probe=a31df2b8fe) | Aug 30, 2023 |
| Dell          | Latitude 5290               | Notebook    | [0b4debc293](https://linux-hardware.org/?probe=0b4debc293) | Aug 30, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [93f309e8ad](https://linux-hardware.org/?probe=93f309e8ad) | Aug 29, 2023 |
| Acer          | Aspire 5720                 | Notebook    | [36403a156e](https://linux-hardware.org/?probe=36403a156e) | Aug 29, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [c4bec90c4e](https://linux-hardware.org/?probe=c4bec90c4e) | Aug 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c190907cc8](https://linux-hardware.org/?probe=c190907cc8) | Aug 29, 2023 |
| Dell          | Latitude 7440               | Convertible | [3021c76410](https://linux-hardware.org/?probe=3021c76410) | Aug 29, 2023 |
| Acer          | TravelMate Spin B118-G2-... | Convertible | [c1e12f9da7](https://linux-hardware.org/?probe=c1e12f9da7) | Aug 29, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [0789880eae](https://linux-hardware.org/?probe=0789880eae) | Aug 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d8714663f](https://linux-hardware.org/?probe=7d8714663f) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [704a62ef33](https://linux-hardware.org/?probe=704a62ef33) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [beb1174dde](https://linux-hardware.org/?probe=beb1174dde) | Aug 29, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d97cedcf3c](https://linux-hardware.org/?probe=d97cedcf3c) | Aug 28, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [50b9b4c466](https://linux-hardware.org/?probe=50b9b4c466) | Aug 28, 2023 |
| Acer          | Aspire V5-471               | Notebook    | [c5d2dabe27](https://linux-hardware.org/?probe=c5d2dabe27) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2b217724e7](https://linux-hardware.org/?probe=2b217724e7) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [306a487e6d](https://linux-hardware.org/?probe=306a487e6d) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | Notebook    | [9f725ce1a7](https://linux-hardware.org/?probe=9f725ce1a7) | Aug 28, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [62464b6b0d](https://linux-hardware.org/?probe=62464b6b0d) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | Notebook    | [c091e0bc8b](https://linux-hardware.org/?probe=c091e0bc8b) | Aug 28, 2023 |
| Dell          | Latitude E7240              | Notebook    | [1eab9b5f8d](https://linux-hardware.org/?probe=1eab9b5f8d) | Aug 28, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [f52ee2433e](https://linux-hardware.org/?probe=f52ee2433e) | Aug 28, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [08229cf960](https://linux-hardware.org/?probe=08229cf960) | Aug 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [8a68ffe7b0](https://linux-hardware.org/?probe=8a68ffe7b0) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| Dell EMC      | Edge Gateway 3200           | Mini pc     | [71d8873664](https://linux-hardware.org/?probe=71d8873664) | Aug 28, 2023 |
| Dell          | Latitude 7480               | Notebook    | [95f7cd5046](https://linux-hardware.org/?probe=95f7cd5046) | Aug 27, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| Dell          | Latitude E6420              | Notebook    | [1e2c15f171](https://linux-hardware.org/?probe=1e2c15f171) | Aug 27, 2023 |
| Dell          | 0KFKMF A00                  | All in one  | [c15583fc1c](https://linux-hardware.org/?probe=c15583fc1c) | Aug 27, 2023 |
| Dell          | 0RY206                      | Desktop     | [fff4c01588](https://linux-hardware.org/?probe=fff4c01588) | Aug 27, 2023 |
| Packard Be... | IMEDIA S3730                | Desktop     | [88e192b5f0](https://linux-hardware.org/?probe=88e192b5f0) | Aug 27, 2023 |
| HP            | 843C                        | Desktop     | [6ad21e7d94](https://linux-hardware.org/?probe=6ad21e7d94) | Aug 27, 2023 |
| Lenovo        | 31900058 STD                | All in one  | [5c0b22c537](https://linux-hardware.org/?probe=5c0b22c537) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | Notebook    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Studio 1737                 | Notebook    | [8e668fe167](https://linux-hardware.org/?probe=8e668fe167) | Aug 27, 2023 |
| ZOOSTORM      | 7200-9062A                  | Notebook    | [5ee843d3d1](https://linux-hardware.org/?probe=5ee843d3d1) | Aug 26, 2023 |
| Unknown       | V00                         | Mini pc     | [81085cf18b](https://linux-hardware.org/?probe=81085cf18b) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| Acer          | Aspire V5-571               | Notebook    | [033994cebf](https://linux-hardware.org/?probe=033994cebf) | Aug 26, 2023 |
| Packard Be... | IMEDIA S3730                | Desktop     | [fc3a889045](https://linux-hardware.org/?probe=fc3a889045) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [9bd4ef3aac](https://linux-hardware.org/?probe=9bd4ef3aac) | Aug 26, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [6f26d24018](https://linux-hardware.org/?probe=6f26d24018) | Aug 26, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [978f1e9fa5](https://linux-hardware.org/?probe=978f1e9fa5) | Aug 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [53b787dc90](https://linux-hardware.org/?probe=53b787dc90) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [83695164cc](https://linux-hardware.org/?probe=83695164cc) | Aug 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [dc1c907cda](https://linux-hardware.org/?probe=dc1c907cda) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [ee4e04964c](https://linux-hardware.org/?probe=ee4e04964c) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [376d5e8a22](https://linux-hardware.org/?probe=376d5e8a22) | Aug 25, 2023 |
| HUAWEI        | MACHR-WX9                   | Notebook    | [a8c4ca7aee](https://linux-hardware.org/?probe=a8c4ca7aee) | Aug 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [0145505cea](https://linux-hardware.org/?probe=0145505cea) | Aug 25, 2023 |
| Packard Be... | EasyNote TJ66               | Notebook    | [010fe56f65](https://linux-hardware.org/?probe=010fe56f65) | Aug 25, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [3add2f8945](https://linux-hardware.org/?probe=3add2f8945) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [7355715562](https://linux-hardware.org/?probe=7355715562) | Aug 25, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [8237cf85b3](https://linux-hardware.org/?probe=8237cf85b3) | Aug 25, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [51ea627e30](https://linux-hardware.org/?probe=51ea627e30) | Aug 25, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c8e9f89359](https://linux-hardware.org/?probe=c8e9f89359) | Aug 25, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [116561b889](https://linux-hardware.org/?probe=116561b889) | Aug 25, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [3ac1398c61](https://linux-hardware.org/?probe=3ac1398c61) | Aug 25, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [282429187d](https://linux-hardware.org/?probe=282429187d) | Aug 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [3ddae42f27](https://linux-hardware.org/?probe=3ddae42f27) | Aug 25, 2023 |
| Lenovo        | ThinkPad T430 2349KAG       | Notebook    | [f2348b8eee](https://linux-hardware.org/?probe=f2348b8eee) | Aug 25, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [53323ddb53](https://linux-hardware.org/?probe=53323ddb53) | Aug 25, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [78125c34b4](https://linux-hardware.org/?probe=78125c34b4) | Aug 25, 2023 |
| Sony          | SVF15A1M2ES                 | Notebook    | [b352453232](https://linux-hardware.org/?probe=b352453232) | Aug 24, 2023 |
| Google        | Eldrid                      | Notebook    | [e451d840cf](https://linux-hardware.org/?probe=e451d840cf) | Aug 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [98dce455d0](https://linux-hardware.org/?probe=98dce455d0) | Aug 24, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [5b5a4fa5d9](https://linux-hardware.org/?probe=5b5a4fa5d9) | Aug 23, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f2f57d0e61](https://linux-hardware.org/?probe=f2f57d0e61) | Aug 23, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [adda6295fb](https://linux-hardware.org/?probe=adda6295fb) | Aug 23, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4f0b15f8e2](https://linux-hardware.org/?probe=4f0b15f8e2) | Aug 23, 2023 |
| Linx          | LINX12X64                   | Tablet      | [8e57cc64f6](https://linux-hardware.org/?probe=8e57cc64f6) | Aug 23, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [3a0ddb0171](https://linux-hardware.org/?probe=3a0ddb0171) | Aug 23, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [09820a2ab9](https://linux-hardware.org/?probe=09820a2ab9) | Aug 23, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [618b994ac1](https://linux-hardware.org/?probe=618b994ac1) | Aug 23, 2023 |
| Acer          | AOD255                      | Notebook    | [06c6346db1](https://linux-hardware.org/?probe=06c6346db1) | Aug 23, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | Notebook    | [0005c7836c](https://linux-hardware.org/?probe=0005c7836c) | Aug 22, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | Notebook    | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [fce52ede18](https://linux-hardware.org/?probe=fce52ede18) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [f35c644052](https://linux-hardware.org/?probe=f35c644052) | Aug 22, 2023 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [fe7b3d01bb](https://linux-hardware.org/?probe=fe7b3d01bb) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [4f4bed768e](https://linux-hardware.org/?probe=4f4bed768e) | Aug 22, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e5301a4a98](https://linux-hardware.org/?probe=e5301a4a98) | Aug 22, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [c6a3274c8f](https://linux-hardware.org/?probe=c6a3274c8f) | Aug 21, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [9cd3fa37a0](https://linux-hardware.org/?probe=9cd3fa37a0) | Aug 21, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [6b7db15c2c](https://linux-hardware.org/?probe=6b7db15c2c) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [62cddb0954](https://linux-hardware.org/?probe=62cddb0954) | Aug 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [99448eedb6](https://linux-hardware.org/?probe=99448eedb6) | Aug 21, 2023 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [c121ae9a76](https://linux-hardware.org/?probe=c121ae9a76) | Aug 21, 2023 |
| HP            | 8054                        | Desktop     | [d5582dbf37](https://linux-hardware.org/?probe=d5582dbf37) | Aug 21, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [e3f7de5c66](https://linux-hardware.org/?probe=e3f7de5c66) | Aug 20, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [dc96aa9cee](https://linux-hardware.org/?probe=dc96aa9cee) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [50af29acb9](https://linux-hardware.org/?probe=50af29acb9) | Aug 19, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | Desktop     | [1cd8a1d54a](https://linux-hardware.org/?probe=1cd8a1d54a) | Aug 19, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [f56bdd302b](https://linux-hardware.org/?probe=f56bdd302b) | Aug 19, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [e9816ab65b](https://linux-hardware.org/?probe=e9816ab65b) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [97a87f1178](https://linux-hardware.org/?probe=97a87f1178) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | Notebook    | [cb1eebf517](https://linux-hardware.org/?probe=cb1eebf517) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | Notebook    | [87d16e9431](https://linux-hardware.org/?probe=87d16e9431) | Aug 19, 2023 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [329cfbcae1](https://linux-hardware.org/?probe=329cfbcae1) | Aug 18, 2023 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [323664ecb8](https://linux-hardware.org/?probe=323664ecb8) | Aug 18, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | Notebook    | [c9e9e56ddd](https://linux-hardware.org/?probe=c9e9e56ddd) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| MSI           | Indio                       | Desktop     | [162ed509d4](https://linux-hardware.org/?probe=162ed509d4) | Aug 18, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [92a3afc475](https://linux-hardware.org/?probe=92a3afc475) | Aug 17, 2023 |
| Dell          | 0KP561                      | Desktop     | [2b6a6b6139](https://linux-hardware.org/?probe=2b6a6b6139) | Aug 17, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [507f2bea7c](https://linux-hardware.org/?probe=507f2bea7c) | Aug 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c647987aaf](https://linux-hardware.org/?probe=c647987aaf) | Aug 16, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [b27f36262e](https://linux-hardware.org/?probe=b27f36262e) | Aug 16, 2023 |
| Dell          | Inspiron 7370               | Notebook    | [2676762739](https://linux-hardware.org/?probe=2676762739) | Aug 16, 2023 |
| Gigabyte      | Z590 VISION G               | Desktop     | [0954ff78e7](https://linux-hardware.org/?probe=0954ff78e7) | Aug 16, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [c3d834a0df](https://linux-hardware.org/?probe=c3d834a0df) | Aug 16, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [0e1d37c108](https://linux-hardware.org/?probe=0e1d37c108) | Aug 16, 2023 |
| Lenovo        | YB1-X91F                    | Convertible | [6fec30634b](https://linux-hardware.org/?probe=6fec30634b) | Aug 16, 2023 |
| Acer          | Aspire V5-571               | Notebook    | [bb39a5a125](https://linux-hardware.org/?probe=bb39a5a125) | Aug 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [1be68b93d4](https://linux-hardware.org/?probe=1be68b93d4) | Aug 15, 2023 |
| MSI           | 970A-G46                    | Desktop     | [d1b6347c9a](https://linux-hardware.org/?probe=d1b6347c9a) | Aug 15, 2023 |
| MSI           | GP62 6QF                    | Notebook    | [d9455cbed8](https://linux-hardware.org/?probe=d9455cbed8) | Aug 15, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [12e5d1c399](https://linux-hardware.org/?probe=12e5d1c399) | Aug 15, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [884688ddbf](https://linux-hardware.org/?probe=884688ddbf) | Aug 15, 2023 |
| Samsung       | 755XDA                      | Notebook    | [3be32e2365](https://linux-hardware.org/?probe=3be32e2365) | Aug 15, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [9f3c41bd31](https://linux-hardware.org/?probe=9f3c41bd31) | Aug 15, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [891e757894](https://linux-hardware.org/?probe=891e757894) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | Notebook    | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Dell          | 0RY206                      | Desktop     | [f060a8a559](https://linux-hardware.org/?probe=f060a8a559) | Aug 14, 2023 |
| Google        | Bobba360                    | Notebook    | [e2ae1afdcc](https://linux-hardware.org/?probe=e2ae1afdcc) | Aug 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [fe4612b027](https://linux-hardware.org/?probe=fe4612b027) | Aug 14, 2023 |
| Google        | Bobba360                    | Notebook    | [f211501fde](https://linux-hardware.org/?probe=f211501fde) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [dfae10b78d](https://linux-hardware.org/?probe=dfae10b78d) | Aug 14, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [302fb03dce](https://linux-hardware.org/?probe=302fb03dce) | Aug 13, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [c822a4c96f](https://linux-hardware.org/?probe=c822a4c96f) | Aug 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [9db2ba151b](https://linux-hardware.org/?probe=9db2ba151b) | Aug 13, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [493f1773eb](https://linux-hardware.org/?probe=493f1773eb) | Aug 13, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [d6cfe894c9](https://linux-hardware.org/?probe=d6cfe894c9) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [b0f8b16669](https://linux-hardware.org/?probe=b0f8b16669) | Aug 13, 2023 |
| Lenovo        | ThinkPad 10 20C10024UK      | Tablet      | [874a9bfe43](https://linux-hardware.org/?probe=874a9bfe43) | Aug 13, 2023 |
| Lenovo        | ThinkPad 10 20C10024UK      | Tablet      | [a76cb3b7ef](https://linux-hardware.org/?probe=a76cb3b7ef) | Aug 13, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [74e54546c6](https://linux-hardware.org/?probe=74e54546c6) | Aug 13, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [2461c78ff0](https://linux-hardware.org/?probe=2461c78ff0) | Aug 13, 2023 |
| Dell          | Inspiron 14 7435 2-in-1     | Convertible | [ee7ca4926f](https://linux-hardware.org/?probe=ee7ca4926f) | Aug 13, 2023 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [cd8b4a2836](https://linux-hardware.org/?probe=cd8b4a2836) | Aug 13, 2023 |
| HP            | Pavilion dv5                | Notebook    | [78530d4418](https://linux-hardware.org/?probe=78530d4418) | Aug 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS3320C    | Notebook    | [51f9e0c482](https://linux-hardware.org/?probe=51f9e0c482) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a4f97e45f1](https://linux-hardware.org/?probe=a4f97e45f1) | Aug 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [a737674e04](https://linux-hardware.org/?probe=a737674e04) | Aug 12, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [e1a3542078](https://linux-hardware.org/?probe=e1a3542078) | Aug 12, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [a32f4633c2](https://linux-hardware.org/?probe=a32f4633c2) | Aug 12, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [411b9f412c](https://linux-hardware.org/?probe=411b9f412c) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [20559d710a](https://linux-hardware.org/?probe=20559d710a) | Aug 12, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [ec7b05c868](https://linux-hardware.org/?probe=ec7b05c868) | Aug 12, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [783651bb7d](https://linux-hardware.org/?probe=783651bb7d) | Aug 12, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| HP            | Pavilion dv5                | Notebook    | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| HP            | Pavilion dv5                | Notebook    | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [83a0a8a2aa](https://linux-hardware.org/?probe=83a0a8a2aa) | Aug 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [f062831bd7](https://linux-hardware.org/?probe=f062831bd7) | Aug 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [44fe085499](https://linux-hardware.org/?probe=44fe085499) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ee14fdafcf](https://linux-hardware.org/?probe=ee14fdafcf) | Aug 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [67414922e3](https://linux-hardware.org/?probe=67414922e3) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [24629e2553](https://linux-hardware.org/?probe=24629e2553) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [6f422f386f](https://linux-hardware.org/?probe=6f422f386f) | Aug 10, 2023 |
| Gigabyte      | AERO 15-WA                  | Notebook    | [bd9f5d0f39](https://linux-hardware.org/?probe=bd9f5d0f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4d79d769d2](https://linux-hardware.org/?probe=4d79d769d2) | Aug 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [8d27e3953f](https://linux-hardware.org/?probe=8d27e3953f) | Aug 09, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [14382141e9](https://linux-hardware.org/?probe=14382141e9) | Aug 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [691838cd8c](https://linux-hardware.org/?probe=691838cd8c) | Aug 09, 2023 |
| ASUSTek       | ROG Flow X16 GV601VI_GV6... | Convertible | [99ffb28c11](https://linux-hardware.org/?probe=99ffb28c11) | Aug 08, 2023 |
| Dell          | Inspiron 7537               | Notebook    | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Dell          | Latitude D630               | Notebook    | [a57bb7cde1](https://linux-hardware.org/?probe=a57bb7cde1) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6165a2d50e](https://linux-hardware.org/?probe=6165a2d50e) | Aug 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [6738a625d8](https://linux-hardware.org/?probe=6738a625d8) | Aug 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [66488bdd81](https://linux-hardware.org/?probe=66488bdd81) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5babb790d3](https://linux-hardware.org/?probe=5babb790d3) | Aug 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5dfaa2b1c0](https://linux-hardware.org/?probe=5dfaa2b1c0) | Aug 08, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [58d7c4be4c](https://linux-hardware.org/?probe=58d7c4be4c) | Aug 08, 2023 |
| Acer          | Aspire 1825PTZ              | Notebook    | [553d2539fa](https://linux-hardware.org/?probe=553d2539fa) | Aug 07, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [84b0c88b0a](https://linux-hardware.org/?probe=84b0c88b0a) | Aug 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [de8e0fbde8](https://linux-hardware.org/?probe=de8e0fbde8) | Aug 07, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0cb4da66e3](https://linux-hardware.org/?probe=0cb4da66e3) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [b4b049b997](https://linux-hardware.org/?probe=b4b049b997) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8633bc5aa5](https://linux-hardware.org/?probe=8633bc5aa5) | Aug 07, 2023 |
| Dell          | 00KM0D A00                  | All in one  | [f6d752be40](https://linux-hardware.org/?probe=f6d752be40) | Aug 07, 2023 |
| Dell          | 00KM0D A00                  | All in one  | [30324c6293](https://linux-hardware.org/?probe=30324c6293) | Aug 07, 2023 |
| Dell          | Latitude 5411               | Notebook    | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | Notebook    | [3e9ce860b6](https://linux-hardware.org/?probe=3e9ce860b6) | Aug 07, 2023 |
| MSI           | 970A-G43                    | Desktop     | [68384da884](https://linux-hardware.org/?probe=68384da884) | Aug 06, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [691c44286e](https://linux-hardware.org/?probe=691c44286e) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c3df1aaae9](https://linux-hardware.org/?probe=c3df1aaae9) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [ec7fa20ab4](https://linux-hardware.org/?probe=ec7fa20ab4) | Aug 06, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [247f361473](https://linux-hardware.org/?probe=247f361473) | Aug 06, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [dfe905b869](https://linux-hardware.org/?probe=dfe905b869) | Aug 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c95daf7007](https://linux-hardware.org/?probe=c95daf7007) | Aug 06, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [28384fb38c](https://linux-hardware.org/?probe=28384fb38c) | Aug 06, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5bb0feab0c](https://linux-hardware.org/?probe=5bb0feab0c) | Aug 06, 2023 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [5ec7de1222](https://linux-hardware.org/?probe=5ec7de1222) | Aug 06, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [ffa55735b6](https://linux-hardware.org/?probe=ffa55735b6) | Aug 06, 2023 |
| Dell          | Latitude 5590               | Notebook    | [83d389e795](https://linux-hardware.org/?probe=83d389e795) | Aug 06, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [fed729f0aa](https://linux-hardware.org/?probe=fed729f0aa) | Aug 05, 2023 |
| Dell          | Venue 8 Pro 5855            | Notebook    | [146fa40942](https://linux-hardware.org/?probe=146fa40942) | Aug 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [570728a351](https://linux-hardware.org/?probe=570728a351) | Aug 05, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [34e27f60e0](https://linux-hardware.org/?probe=34e27f60e0) | Aug 05, 2023 |
| Lenovo        | 100w Gen 3 82HY             | Notebook    | [3feb7899d2](https://linux-hardware.org/?probe=3feb7899d2) | Aug 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| HP            | 470 G7 Notebook PC          | Notebook    | [7e4a9b4618](https://linux-hardware.org/?probe=7e4a9b4618) | Aug 04, 2023 |
| GPD           | G1621-02                    | Notebook    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [a9072f3117](https://linux-hardware.org/?probe=a9072f3117) | Aug 04, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [f74b524df1](https://linux-hardware.org/?probe=f74b524df1) | Aug 04, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [cc7ae6c4e9](https://linux-hardware.org/?probe=cc7ae6c4e9) | Aug 04, 2023 |
| HP            | 255 G3                      | Notebook    | [c8b3db6b0b](https://linux-hardware.org/?probe=c8b3db6b0b) | Aug 03, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [71f5ef03f9](https://linux-hardware.org/?probe=71f5ef03f9) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | Notebook    | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [4d21c35777](https://linux-hardware.org/?probe=4d21c35777) | Aug 03, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [bb292f568a](https://linux-hardware.org/?probe=bb292f568a) | Aug 03, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [1a9566fa0a](https://linux-hardware.org/?probe=1a9566fa0a) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B760-A GAMING ... | Desktop     | [f629b6e16e](https://linux-hardware.org/?probe=f629b6e16e) | Aug 03, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | Desktop     | [04f8c42dba](https://linux-hardware.org/?probe=04f8c42dba) | Aug 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [f928feaff9](https://linux-hardware.org/?probe=f928feaff9) | Aug 02, 2023 |
| Supermicro    | X9DAi                       | Desktop     | [d7390704d8](https://linux-hardware.org/?probe=d7390704d8) | Aug 02, 2023 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [c7e057da76](https://linux-hardware.org/?probe=c7e057da76) | Aug 02, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [5e74aca4e7](https://linux-hardware.org/?probe=5e74aca4e7) | Aug 02, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [0e5d30b504](https://linux-hardware.org/?probe=0e5d30b504) | Aug 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [c66316cd62](https://linux-hardware.org/?probe=c66316cd62) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [f3f9a4366b](https://linux-hardware.org/?probe=f3f9a4366b) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1ad3dc2f1b](https://linux-hardware.org/?probe=1ad3dc2f1b) | Aug 01, 2023 |
| Apple         | Mac-F2218FC8                | All in one  | [1e13eec6e4](https://linux-hardware.org/?probe=1e13eec6e4) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [35f27e05c6](https://linux-hardware.org/?probe=35f27e05c6) | Jul 31, 2023 |
| HP            | 3398                        | Desktop     | [c271d5d40e](https://linux-hardware.org/?probe=c271d5d40e) | Jul 31, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| MSI           | H81M-P33                    | Desktop     | [d5cb55a484](https://linux-hardware.org/?probe=d5cb55a484) | Jul 31, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [07a919f178](https://linux-hardware.org/?probe=07a919f178) | Jul 31, 2023 |
| HP            | ProBook 4740s               | Notebook    | [d0aae87145](https://linux-hardware.org/?probe=d0aae87145) | Jul 31, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [7a8510c7fd](https://linux-hardware.org/?probe=7a8510c7fd) | Jul 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [940a0b000a](https://linux-hardware.org/?probe=940a0b000a) | Jul 31, 2023 |
| HP            | ProBook 4740s               | Notebook    | [985ee4b495](https://linux-hardware.org/?probe=985ee4b495) | Jul 30, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [a42e1c787e](https://linux-hardware.org/?probe=a42e1c787e) | Jul 30, 2023 |
| Dell          | 0CU409                      | Desktop     | [7b665ec8f2](https://linux-hardware.org/?probe=7b665ec8f2) | Jul 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2b75ad8b2c](https://linux-hardware.org/?probe=2b75ad8b2c) | Jul 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [82e4fa2fbc](https://linux-hardware.org/?probe=82e4fa2fbc) | Jul 30, 2023 |
| Pine Micro... | Pine64 RockPro64 v2.1       | Soc         | [f9b68dbdc9](https://linux-hardware.org/?probe=f9b68dbdc9) | Jul 30, 2023 |
| Lenovo        | ThinkCentre M91p 4518A4M    | Desktop     | [2ba45b1cfa](https://linux-hardware.org/?probe=2ba45b1cfa) | Jul 30, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [9469c1037c](https://linux-hardware.org/?probe=9469c1037c) | Jul 29, 2023 |
| HP            | ENVY Notebook               | Notebook    | [3e13681e00](https://linux-hardware.org/?probe=3e13681e00) | Jul 29, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [dbcda8f4d0](https://linux-hardware.org/?probe=dbcda8f4d0) | Jul 29, 2023 |
| Lenovo        | C205                        | All in one  | [e0a01bba61](https://linux-hardware.org/?probe=e0a01bba61) | Jul 29, 2023 |
| Razer         | Blade                       | Notebook    | [6c3ef3aa59](https://linux-hardware.org/?probe=6c3ef3aa59) | Jul 29, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a70852def5](https://linux-hardware.org/?probe=a70852def5) | Jul 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1N700    | Notebook    | [3486243fd6](https://linux-hardware.org/?probe=3486243fd6) | Jul 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fecdf7e593](https://linux-hardware.org/?probe=fecdf7e593) | Jul 29, 2023 |
| Dell          | XPS 9320                    | Notebook    | [4000df5584](https://linux-hardware.org/?probe=4000df5584) | Jul 29, 2023 |
| Dell          | 0PU052                      | Desktop     | [f51bdc3bf5](https://linux-hardware.org/?probe=f51bdc3bf5) | Jul 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [ff714f1791](https://linux-hardware.org/?probe=ff714f1791) | Jul 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [ba7c69f7e0](https://linux-hardware.org/?probe=ba7c69f7e0) | Jul 28, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bc3cb3cbfd](https://linux-hardware.org/?probe=bc3cb3cbfd) | Jul 28, 2023 |
| Dell          | Latitude 3410               | Notebook    | [449e4c62f3](https://linux-hardware.org/?probe=449e4c62f3) | Jul 28, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [b784cbe3ab](https://linux-hardware.org/?probe=b784cbe3ab) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4a34b9da9b](https://linux-hardware.org/?probe=4a34b9da9b) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a26bbadd26](https://linux-hardware.org/?probe=a26bbadd26) | Jul 27, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [cd318f6b75](https://linux-hardware.org/?probe=cd318f6b75) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [4895ec9de1](https://linux-hardware.org/?probe=4895ec9de1) | Jul 27, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [7c716b6ab0](https://linux-hardware.org/?probe=7c716b6ab0) | Jul 27, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [84ab2faa6f](https://linux-hardware.org/?probe=84ab2faa6f) | Jul 27, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [5c91300246](https://linux-hardware.org/?probe=5c91300246) | Jul 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3f7bed61a8](https://linux-hardware.org/?probe=3f7bed61a8) | Jul 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [aed4f431ec](https://linux-hardware.org/?probe=aed4f431ec) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [1adda13639](https://linux-hardware.org/?probe=1adda13639) | Jul 26, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [ee10ac6c06](https://linux-hardware.org/?probe=ee10ac6c06) | Jul 26, 2023 |
| HP            | Notebook                    | Notebook    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [4b9680f094](https://linux-hardware.org/?probe=4b9680f094) | Jul 25, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [858b41037e](https://linux-hardware.org/?probe=858b41037e) | Jul 25, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Dell          | Latitude 5530               | Notebook    | [cccd0bf0b8](https://linux-hardware.org/?probe=cccd0bf0b8) | Jul 25, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [6fc7661aae](https://linux-hardware.org/?probe=6fc7661aae) | Jul 25, 2023 |
| MSI           | Katana GF66 11UG            | Notebook    | [bd45023e8e](https://linux-hardware.org/?probe=bd45023e8e) | Jul 25, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [8f4eb83f05](https://linux-hardware.org/?probe=8f4eb83f05) | Jul 25, 2023 |
| Acer          | Swift SFE16-43              | Notebook    | [ada40722ae](https://linux-hardware.org/?probe=ada40722ae) | Jul 25, 2023 |
| Lenovo        | 36ED SDK0J40700 WIN 3258... | All in one  | [2c730fd2b8](https://linux-hardware.org/?probe=2c730fd2b8) | Jul 25, 2023 |
| Lenovo        | 36ED SDK0J40700 WIN 3258... | All in one  | [d179eaf4eb](https://linux-hardware.org/?probe=d179eaf4eb) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | Notebook    | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| Lenovo        | Yoga 9 14IRP8 83B1          | Convertible | [3f563f695c](https://linux-hardware.org/?probe=3f563f695c) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [e46d04faa8](https://linux-hardware.org/?probe=e46d04faa8) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [0b7f69aaf6](https://linux-hardware.org/?probe=0b7f69aaf6) | Jul 25, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [5be0e1a212](https://linux-hardware.org/?probe=5be0e1a212) | Jul 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [0b4b6b015b](https://linux-hardware.org/?probe=0b4b6b015b) | Jul 24, 2023 |
| Chuwi         | CoreBook Pro                | Notebook    | [21ab3832ea](https://linux-hardware.org/?probe=21ab3832ea) | Jul 24, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [3d08e59ce3](https://linux-hardware.org/?probe=3d08e59ce3) | Jul 24, 2023 |
| Dell          | Latitude 2110               | Notebook    | [05a7868709](https://linux-hardware.org/?probe=05a7868709) | Jul 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2ff464874e](https://linux-hardware.org/?probe=2ff464874e) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [273533f7f8](https://linux-hardware.org/?probe=273533f7f8) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| Dell          | 0YGR09 A00                  | All in one  | [256d182fcd](https://linux-hardware.org/?probe=256d182fcd) | Jul 23, 2023 |
| Gigabyte      | P17FR5                      | Notebook    | [817b78d77b](https://linux-hardware.org/?probe=817b78d77b) | Jul 23, 2023 |
| PC Special... | Standard                    | Notebook    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| HP            | Notebook                    | Notebook    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | Desktop     | [4c4109b8f3](https://linux-hardware.org/?probe=4c4109b8f3) | Jul 23, 2023 |
| HP            | 8350                        | Desktop     | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [ff5e295a5d](https://linux-hardware.org/?probe=ff5e295a5d) | Jul 23, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [5c5147b82d](https://linux-hardware.org/?probe=5c5147b82d) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | Desktop     | [d89bdeec87](https://linux-hardware.org/?probe=d89bdeec87) | Jul 23, 2023 |
| Dell          | 0757V0 A00                  | Desktop     | [e367a3740a](https://linux-hardware.org/?probe=e367a3740a) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS1N700    | Notebook    | [e42f9111c6](https://linux-hardware.org/?probe=e42f9111c6) | Jul 23, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9a62fe1979](https://linux-hardware.org/?probe=9a62fe1979) | Jul 22, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [17c61c9ced](https://linux-hardware.org/?probe=17c61c9ced) | Jul 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [5072be5d0f](https://linux-hardware.org/?probe=5072be5d0f) | Jul 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [0e8e6ce1ae](https://linux-hardware.org/?probe=0e8e6ce1ae) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [f27670217e](https://linux-hardware.org/?probe=f27670217e) | Jul 22, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [9f52ae219f](https://linux-hardware.org/?probe=9f52ae219f) | Jul 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [fa8db9f24a](https://linux-hardware.org/?probe=fa8db9f24a) | Jul 22, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [dee00fe6af](https://linux-hardware.org/?probe=dee00fe6af) | Jul 22, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [c06811057a](https://linux-hardware.org/?probe=c06811057a) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [355ac636c1](https://linux-hardware.org/?probe=355ac636c1) | Jul 21, 2023 |
| Dell          | System XPS L702X            | Notebook    | [21f1d68bc1](https://linux-hardware.org/?probe=21f1d68bc1) | Jul 21, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [a131a7a5fb](https://linux-hardware.org/?probe=a131a7a5fb) | Jul 21, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [6b8d5cb0c1](https://linux-hardware.org/?probe=6b8d5cb0c1) | Jul 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [1ee2e5b63d](https://linux-hardware.org/?probe=1ee2e5b63d) | Jul 20, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [2f55654def](https://linux-hardware.org/?probe=2f55654def) | Jul 20, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [e82f5072df](https://linux-hardware.org/?probe=e82f5072df) | Jul 20, 2023 |
| Dell          | Vostro 1500                 | Notebook    | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [d8e84157ab](https://linux-hardware.org/?probe=d8e84157ab) | Jul 20, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [def74bc1c9](https://linux-hardware.org/?probe=def74bc1c9) | Jul 19, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e0b92a00b5](https://linux-hardware.org/?probe=e0b92a00b5) | Jul 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [140474e198](https://linux-hardware.org/?probe=140474e198) | Jul 19, 2023 |
| Lenovo        | ThinkPad E560 20EV000YUK    | Notebook    | [0e89144534](https://linux-hardware.org/?probe=0e89144534) | Jul 19, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [94c330e355](https://linux-hardware.org/?probe=94c330e355) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [ba24f3bb61](https://linux-hardware.org/?probe=ba24f3bb61) | Jul 18, 2023 |
| Valve         | Jupiter                     | Notebook    | [3abdfed88b](https://linux-hardware.org/?probe=3abdfed88b) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| Valve         | Jupiter                     | Notebook    | [4beb3117df](https://linux-hardware.org/?probe=4beb3117df) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [f0ecaa209e](https://linux-hardware.org/?probe=f0ecaa209e) | Jul 18, 2023 |
| Sony          | VAIO                        | All in one  | [ea7a51d543](https://linux-hardware.org/?probe=ea7a51d543) | Jul 18, 2023 |
| Packard Be... | IMEDIA S2885                | Desktop     | [fa20588062](https://linux-hardware.org/?probe=fa20588062) | Jul 17, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [a448a20876](https://linux-hardware.org/?probe=a448a20876) | Jul 17, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [958f57fd27](https://linux-hardware.org/?probe=958f57fd27) | Jul 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [399566f5ce](https://linux-hardware.org/?probe=399566f5ce) | Jul 17, 2023 |
| Sony          | VGN-S3HP                    | Notebook    | [6e2c92c447](https://linux-hardware.org/?probe=6e2c92c447) | Jul 17, 2023 |
| Dell          | Precision M6800             | Notebook    | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [3a7fbf07fa](https://linux-hardware.org/?probe=3a7fbf07fa) | Jul 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [db1e3d03e2](https://linux-hardware.org/?probe=db1e3d03e2) | Jul 17, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [4dacb4cf51](https://linux-hardware.org/?probe=4dacb4cf51) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [15d7862757](https://linux-hardware.org/?probe=15d7862757) | Jul 16, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [07161141b4](https://linux-hardware.org/?probe=07161141b4) | Jul 16, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [a79d62db7c](https://linux-hardware.org/?probe=a79d62db7c) | Jul 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [ec4db25eb9](https://linux-hardware.org/?probe=ec4db25eb9) | Jul 16, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [9dd235116d](https://linux-hardware.org/?probe=9dd235116d) | Jul 16, 2023 |
| Supermicro    | X9SRA/X9SRA-3               | Server      | [15d31e889c](https://linux-hardware.org/?probe=15d31e889c) | Jul 16, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [87763ca861](https://linux-hardware.org/?probe=87763ca861) | Jul 16, 2023 |
| Dell          | G5 5587                     | Notebook    | [fc861c593a](https://linux-hardware.org/?probe=fc861c593a) | Jul 16, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [8231c1b7c0](https://linux-hardware.org/?probe=8231c1b7c0) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | Desktop     | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [8977d2e0a3](https://linux-hardware.org/?probe=8977d2e0a3) | Jul 16, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [35f3837811](https://linux-hardware.org/?probe=35f3837811) | Jul 16, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [a4bd524029](https://linux-hardware.org/?probe=a4bd524029) | Jul 15, 2023 |
| Dell          | 073MMW A03                  | Desktop     | [f76738403e](https://linux-hardware.org/?probe=f76738403e) | Jul 15, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [8e41b4b86d](https://linux-hardware.org/?probe=8e41b4b86d) | Jul 15, 2023 |
| Dell          | Latitude E4300              | Notebook    | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Acer          | Aspire A315-32              | Notebook    | [7044de848c](https://linux-hardware.org/?probe=7044de848c) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | Notebook    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [95f81cdf21](https://linux-hardware.org/?probe=95f81cdf21) | Jul 15, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [08dede9db3](https://linux-hardware.org/?probe=08dede9db3) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [32b56b85c4](https://linux-hardware.org/?probe=32b56b85c4) | Jul 15, 2023 |
| Dell          | G15 5510                    | Notebook    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | Notebook    | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c27ff02a84](https://linux-hardware.org/?probe=c27ff02a84) | Jul 14, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [dc3bdab530](https://linux-hardware.org/?probe=dc3bdab530) | Jul 14, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [ca425f6c38](https://linux-hardware.org/?probe=ca425f6c38) | Jul 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4155214585](https://linux-hardware.org/?probe=4155214585) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | Notebook    | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0ac2423aa2](https://linux-hardware.org/?probe=0ac2423aa2) | Jul 14, 2023 |
| Notebook      | N150ZU                      | Notebook    | [61be22ac36](https://linux-hardware.org/?probe=61be22ac36) | Jul 14, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [2b9ee1f8b7](https://linux-hardware.org/?probe=2b9ee1f8b7) | Jul 14, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [fc3514e9a6](https://linux-hardware.org/?probe=fc3514e9a6) | Jul 14, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [163766c886](https://linux-hardware.org/?probe=163766c886) | Jul 14, 2023 |
| Acer          | Swift SF313-52              | Notebook    | [3b393fc916](https://linux-hardware.org/?probe=3b393fc916) | Jul 14, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [c1dba9e7b8](https://linux-hardware.org/?probe=c1dba9e7b8) | Jul 14, 2023 |
| Google        | Droid                       | Notebook    | [9b77a9ba04](https://linux-hardware.org/?probe=9b77a9ba04) | Jul 14, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | Notebook    | [4df76c784c](https://linux-hardware.org/?probe=4df76c784c) | Jul 13, 2023 |
| ASUSTek       | P5E-V HDMI                  | Desktop     | [460e520a69](https://linux-hardware.org/?probe=460e520a69) | Jul 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [4b9cba03ac](https://linux-hardware.org/?probe=4b9cba03ac) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [965ca81d78](https://linux-hardware.org/?probe=965ca81d78) | Jul 13, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [d7d01a7da5](https://linux-hardware.org/?probe=d7d01a7da5) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T0Q    | Notebook    | [0d5f86f700](https://linux-hardware.org/?probe=0d5f86f700) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2f943c811e](https://linux-hardware.org/?probe=2f943c811e) | Jul 13, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [11ab455725](https://linux-hardware.org/?probe=11ab455725) | Jul 13, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [9e49d96293](https://linux-hardware.org/?probe=9e49d96293) | Jul 13, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [dd2c7b0c60](https://linux-hardware.org/?probe=dd2c7b0c60) | Jul 12, 2023 |
| Google        | Lillipup                    | Notebook    | [b7b430e7b4](https://linux-hardware.org/?probe=b7b430e7b4) | Jul 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [15067533b3](https://linux-hardware.org/?probe=15067533b3) | Jul 12, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [95c073864d](https://linux-hardware.org/?probe=95c073864d) | Jul 12, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [ad18a95d12](https://linux-hardware.org/?probe=ad18a95d12) | Jul 12, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [9479004a7e](https://linux-hardware.org/?probe=9479004a7e) | Jul 12, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [f8ffcb4828](https://linux-hardware.org/?probe=f8ffcb4828) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [ad75f0a6e0](https://linux-hardware.org/?probe=ad75f0a6e0) | Jul 12, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [e951c1d4f4](https://linux-hardware.org/?probe=e951c1d4f4) | Jul 12, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d78fb6bdd4](https://linux-hardware.org/?probe=d78fb6bdd4) | Jul 12, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| HP            | 630                         | Notebook    | [671710637c](https://linux-hardware.org/?probe=671710637c) | Jul 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [90466d16ca](https://linux-hardware.org/?probe=90466d16ca) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | Notebook    | [08bbd89b8c](https://linux-hardware.org/?probe=08bbd89b8c) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | Notebook    | [23b123605f](https://linux-hardware.org/?probe=23b123605f) | Jul 11, 2023 |
| Sony          | SVP1321M2EB                 | Notebook    | [e767bbc26b](https://linux-hardware.org/?probe=e767bbc26b) | Jul 11, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [069cf3a06d](https://linux-hardware.org/?probe=069cf3a06d) | Jul 11, 2023 |
| Sony          | VPCZ214GX                   | Notebook    | [d63fc5c563](https://linux-hardware.org/?probe=d63fc5c563) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [db34bf69af](https://linux-hardware.org/?probe=db34bf69af) | Jul 11, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [059cda8a87](https://linux-hardware.org/?probe=059cda8a87) | Jul 11, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [e1700a0ab4](https://linux-hardware.org/?probe=e1700a0ab4) | Jul 11, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [44af6cae51](https://linux-hardware.org/?probe=44af6cae51) | Jul 11, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [59c50a4a34](https://linux-hardware.org/?probe=59c50a4a34) | Jul 11, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | Desktop     | [08d9fe81da](https://linux-hardware.org/?probe=08d9fe81da) | Jul 10, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [429e4e7636](https://linux-hardware.org/?probe=429e4e7636) | Jul 10, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [56de408d31](https://linux-hardware.org/?probe=56de408d31) | Jul 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [5d55bf223d](https://linux-hardware.org/?probe=5d55bf223d) | Jul 10, 2023 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [44f9b46596](https://linux-hardware.org/?probe=44f9b46596) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [96ca518dc6](https://linux-hardware.org/?probe=96ca518dc6) | Jul 09, 2023 |
| ASUSTek       | K54C                        | Notebook    | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ba7cde1766](https://linux-hardware.org/?probe=ba7cde1766) | Jul 09, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f24ba1fb9c](https://linux-hardware.org/?probe=f24ba1fb9c) | Jul 09, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [43ec3cf70b](https://linux-hardware.org/?probe=43ec3cf70b) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [aa2805e577](https://linux-hardware.org/?probe=aa2805e577) | Jul 09, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [db2be54a62](https://linux-hardware.org/?probe=db2be54a62) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [0b6dcc1ea9](https://linux-hardware.org/?probe=0b6dcc1ea9) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [26896deb1e](https://linux-hardware.org/?probe=26896deb1e) | Jul 09, 2023 |
| MSI           | MPG Z490 GAMING CARBON W... | Desktop     | [84e16d3238](https://linux-hardware.org/?probe=84e16d3238) | Jul 09, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [513a03f793](https://linux-hardware.org/?probe=513a03f793) | Jul 08, 2023 |
| Dell          | 01TKCC A01                  | Desktop     | [b3ab41fd8f](https://linux-hardware.org/?probe=b3ab41fd8f) | Jul 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [ef7acb569d](https://linux-hardware.org/?probe=ef7acb569d) | Jul 08, 2023 |
| Acer          | Nitro N50-620               | Desktop     | [8286ddb9ae](https://linux-hardware.org/?probe=8286ddb9ae) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [ffde5244e6](https://linux-hardware.org/?probe=ffde5244e6) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [2e2541c7a6](https://linux-hardware.org/?probe=2e2541c7a6) | Jul 08, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [3a64eabd9b](https://linux-hardware.org/?probe=3a64eabd9b) | Jul 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [703f0e9012](https://linux-hardware.org/?probe=703f0e9012) | Jul 08, 2023 |
| Toshiba       | PORTEGE X30T-E              | Tablet      | [2942c2e2d5](https://linux-hardware.org/?probe=2942c2e2d5) | Jul 07, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | Desktop     | [53d1debf85](https://linux-hardware.org/?probe=53d1debf85) | Jul 07, 2023 |
| HP            | 2B4B                        | Desktop     | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| HP            | 2B4B                        | Desktop     | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| Lenovo        | IdeaCentre B320             | Desktop     | [58bb7cf40a](https://linux-hardware.org/?probe=58bb7cf40a) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [43cb92095e](https://linux-hardware.org/?probe=43cb92095e) | Jul 07, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [93f50211c2](https://linux-hardware.org/?probe=93f50211c2) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [03f454349c](https://linux-hardware.org/?probe=03f454349c) | Jul 06, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [9a6e78196d](https://linux-hardware.org/?probe=9a6e78196d) | Jul 06, 2023 |
| HP            | 3398                        | Desktop     | [3124ceac21](https://linux-hardware.org/?probe=3124ceac21) | Jul 06, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [0c15ba467a](https://linux-hardware.org/?probe=0c15ba467a) | Jul 06, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [b4b26d2f53](https://linux-hardware.org/?probe=b4b26d2f53) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [e17ab8bbe7](https://linux-hardware.org/?probe=e17ab8bbe7) | Jul 06, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [bdc65d0c9f](https://linux-hardware.org/?probe=bdc65d0c9f) | Jul 05, 2023 |
| Lenovo        | ThinkPad T400 6474W7T       | Notebook    | [56144d66ac](https://linux-hardware.org/?probe=56144d66ac) | Jul 05, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [bd9c7a22d6](https://linux-hardware.org/?probe=bd9c7a22d6) | Jul 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [bb0e10ceef](https://linux-hardware.org/?probe=bb0e10ceef) | Jul 05, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [b180548e9c](https://linux-hardware.org/?probe=b180548e9c) | Jul 05, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [c945bae843](https://linux-hardware.org/?probe=c945bae843) | Jul 05, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [f4fdc8a532](https://linux-hardware.org/?probe=f4fdc8a532) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [da18aba906](https://linux-hardware.org/?probe=da18aba906) | Jul 04, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [d5b720740f](https://linux-hardware.org/?probe=d5b720740f) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [f9688a073f](https://linux-hardware.org/?probe=f9688a073f) | Jul 04, 2023 |
| Apple         | Mac-F4208DA9 PVT            | Desktop     | [6c2cdc1c76](https://linux-hardware.org/?probe=6c2cdc1c76) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [8b40767026](https://linux-hardware.org/?probe=8b40767026) | Jul 04, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [ed7caf91c0](https://linux-hardware.org/?probe=ed7caf91c0) | Jul 03, 2023 |
| Acer          | Aspire M3910                | Desktop     | [837d0f7852](https://linux-hardware.org/?probe=837d0f7852) | Jul 03, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [cf3da29bba](https://linux-hardware.org/?probe=cf3da29bba) | Jul 03, 2023 |
| ASUSTek       | WS X299 PRO_SE              | Desktop     | [d31cedc2ad](https://linux-hardware.org/?probe=d31cedc2ad) | Jul 03, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | Notebook    | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [47654b63c6](https://linux-hardware.org/?probe=47654b63c6) | Jul 02, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [d69b1af76b](https://linux-hardware.org/?probe=d69b1af76b) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| Intel         | NUC13ANBi7 M89645-202       | Mini pc     | [3482361f0c](https://linux-hardware.org/?probe=3482361f0c) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9c8f32ac20](https://linux-hardware.org/?probe=9c8f32ac20) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [6c32038385](https://linux-hardware.org/?probe=6c32038385) | Jul 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [1b82430294](https://linux-hardware.org/?probe=1b82430294) | Jul 02, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [e7e4a3562f](https://linux-hardware.org/?probe=e7e4a3562f) | Jul 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [29b2c807e6](https://linux-hardware.org/?probe=29b2c807e6) | Jul 01, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [ed2ea8b876](https://linux-hardware.org/?probe=ed2ea8b876) | Jul 01, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| Unknown       | V00                         | Mini pc     | [ab56e54ced](https://linux-hardware.org/?probe=ab56e54ced) | Jul 01, 2023 |
| Unknown       | V00                         | Mini pc     | [36483eddb0](https://linux-hardware.org/?probe=36483eddb0) | Jul 01, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [c1e18957a4](https://linux-hardware.org/?probe=c1e18957a4) | Jul 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d9b6645cae](https://linux-hardware.org/?probe=d9b6645cae) | Jul 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [e9f511bc00](https://linux-hardware.org/?probe=e9f511bc00) | Jul 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [be62cc78df](https://linux-hardware.org/?probe=be62cc78df) | Jul 01, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [a0fdd16a9e](https://linux-hardware.org/?probe=a0fdd16a9e) | Jul 01, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dea1298c2e](https://linux-hardware.org/?probe=dea1298c2e) | Jul 01, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [8f38634e0e](https://linux-hardware.org/?probe=8f38634e0e) | Jul 01, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [06ae615fd1](https://linux-hardware.org/?probe=06ae615fd1) | Jul 01, 2023 |
| Toshiba       | Satellite Pro L650          | Notebook    | [d8da913f23](https://linux-hardware.org/?probe=d8da913f23) | Jul 01, 2023 |
| Teclast       | F15Plus 2                   | Notebook    | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [6c8a67be9e](https://linux-hardware.org/?probe=6c8a67be9e) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [a582972a5e](https://linux-hardware.org/?probe=a582972a5e) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Intel         | X99H                        | Desktop     | [8e8c7e8b20](https://linux-hardware.org/?probe=8e8c7e8b20) | Jun 30, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [fe8b1af179](https://linux-hardware.org/?probe=fe8b1af179) | Jun 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [89d751f07f](https://linux-hardware.org/?probe=89d751f07f) | Jun 30, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [e1ed0643fb](https://linux-hardware.org/?probe=e1ed0643fb) | Jun 30, 2023 |
| HP            | Unknown                     | Notebook    | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [0e98c1f04a](https://linux-hardware.org/?probe=0e98c1f04a) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [703ae4bd0b](https://linux-hardware.org/?probe=703ae4bd0b) | Jun 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [265cbaedcc](https://linux-hardware.org/?probe=265cbaedcc) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf3c982248](https://linux-hardware.org/?probe=bf3c982248) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | Desktop     | [e8b15eb823](https://linux-hardware.org/?probe=e8b15eb823) | Jun 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [93e0628fbe](https://linux-hardware.org/?probe=93e0628fbe) | Jun 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ddb283952b](https://linux-hardware.org/?probe=ddb283952b) | Jun 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [56e2b61337](https://linux-hardware.org/?probe=56e2b61337) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| Google        | Reef                        | Notebook    | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [031ec94437](https://linux-hardware.org/?probe=031ec94437) | Jun 28, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [9cb1b45a65](https://linux-hardware.org/?probe=9cb1b45a65) | Jun 28, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [2b47aff042](https://linux-hardware.org/?probe=2b47aff042) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [81bbfe3459](https://linux-hardware.org/?probe=81bbfe3459) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [ebb41279ae](https://linux-hardware.org/?probe=ebb41279ae) | Jun 28, 2023 |
| Lenovo        | ThinkPad X240 20AL007LUK    | Notebook    | [ee0761a131](https://linux-hardware.org/?probe=ee0761a131) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [dc758ef355](https://linux-hardware.org/?probe=dc758ef355) | Jun 28, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1ef6edecef](https://linux-hardware.org/?probe=1ef6edecef) | Jun 28, 2023 |
| MSI           | GE70 2PL                    | Notebook    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9128946047](https://linux-hardware.org/?probe=9128946047) | Jun 27, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [a2ef6d8517](https://linux-hardware.org/?probe=a2ef6d8517) | Jun 27, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [3d2a2196ae](https://linux-hardware.org/?probe=3d2a2196ae) | Jun 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [f6d3a1e787](https://linux-hardware.org/?probe=f6d3a1e787) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| Dell          | Precision M6800             | Notebook    | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [88baca047c](https://linux-hardware.org/?probe=88baca047c) | Jun 27, 2023 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [51f9f56f44](https://linux-hardware.org/?probe=51f9f56f44) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [fe27e643ac](https://linux-hardware.org/?probe=fe27e643ac) | Jun 26, 2023 |
| HP            | 859B                        | Desktop     | [63fdd4ed7e](https://linux-hardware.org/?probe=63fdd4ed7e) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| Samsung       | 935QDB                      | Convertible | [d206412575](https://linux-hardware.org/?probe=d206412575) | Jun 26, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ad1a470baf](https://linux-hardware.org/?probe=ad1a470baf) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [7c0c11558d](https://linux-hardware.org/?probe=7c0c11558d) | Jun 26, 2023 |
| HP            | Unknown                     | Notebook    | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | Notebook    | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [9f89885724](https://linux-hardware.org/?probe=9f89885724) | Jun 25, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| Medion        | E2228T MD61050              | Convertible | [595ec84ebc](https://linux-hardware.org/?probe=595ec84ebc) | Jun 25, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [75f62d2200](https://linux-hardware.org/?probe=75f62d2200) | Jun 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [27c389d734](https://linux-hardware.org/?probe=27c389d734) | Jun 24, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [1e1660833e](https://linux-hardware.org/?probe=1e1660833e) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [54ef5b6567](https://linux-hardware.org/?probe=54ef5b6567) | Jun 23, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [a9cd7361e6](https://linux-hardware.org/?probe=a9cd7361e6) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | Notebook    | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| ASRock        | Z87M Pro4                   | Desktop     | [762b33c8e7](https://linux-hardware.org/?probe=762b33c8e7) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [184b19f00c](https://linux-hardware.org/?probe=184b19f00c) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| ASUSTek       | TP550LA                     | Notebook    | [7728203a8a](https://linux-hardware.org/?probe=7728203a8a) | Jun 22, 2023 |
| ASUSTek       | TP550LA                     | Notebook    | [fed72172d2](https://linux-hardware.org/?probe=fed72172d2) | Jun 22, 2023 |
| Medion        | Erazer P6661 MD60303        | Notebook    | [22fb03fe41](https://linux-hardware.org/?probe=22fb03fe41) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [f1e506486c](https://linux-hardware.org/?probe=f1e506486c) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [5c9111463c](https://linux-hardware.org/?probe=5c9111463c) | Jun 21, 2023 |
| Acer          | Aspire 5742Z                | Notebook    | [d1513c944e](https://linux-hardware.org/?probe=d1513c944e) | Jun 21, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [fd3c5ae570](https://linux-hardware.org/?probe=fd3c5ae570) | Jun 21, 2023 |
| HP            | Unknown                     | Notebook    | [4f27a83f9e](https://linux-hardware.org/?probe=4f27a83f9e) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [881e4f3437](https://linux-hardware.org/?probe=881e4f3437) | Jun 20, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [4760bb7306](https://linux-hardware.org/?probe=4760bb7306) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [092370b958](https://linux-hardware.org/?probe=092370b958) | Jun 20, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [b968cb073e](https://linux-hardware.org/?probe=b968cb073e) | Jun 20, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [8260bcf9b3](https://linux-hardware.org/?probe=8260bcf9b3) | Jun 20, 2023 |
| Alienware     | 17 R3                       | Notebook    | [45613f348f](https://linux-hardware.org/?probe=45613f348f) | Jun 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [53b1d3f262](https://linux-hardware.org/?probe=53b1d3f262) | Jun 20, 2023 |
| Dell          | Latitude 7390               | Notebook    | [98d09ed56c](https://linux-hardware.org/?probe=98d09ed56c) | Jun 20, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [2344c78f90](https://linux-hardware.org/?probe=2344c78f90) | Jun 20, 2023 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [5864261490](https://linux-hardware.org/?probe=5864261490) | Jun 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [529320d8fe](https://linux-hardware.org/?probe=529320d8fe) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [36f8057a1d](https://linux-hardware.org/?probe=36f8057a1d) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [e6e1708182](https://linux-hardware.org/?probe=e6e1708182) | Jun 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [159b20029e](https://linux-hardware.org/?probe=159b20029e) | Jun 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [0875b8b413](https://linux-hardware.org/?probe=0875b8b413) | Jun 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| AZW           | GTi                         | Desktop     | [0aaf2297b4](https://linux-hardware.org/?probe=0aaf2297b4) | Jun 17, 2023 |
| Dell          | Latitude 5430               | Notebook    | [1797038bf6](https://linux-hardware.org/?probe=1797038bf6) | Jun 17, 2023 |
| HP            | ENVY m6                     | Notebook    | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1b0dd608b2](https://linux-hardware.org/?probe=1b0dd608b2) | Jun 16, 2023 |
| GEO           | GEOBOOK 2E                  | Notebook    | [9ab9fe3052](https://linux-hardware.org/?probe=9ab9fe3052) | Jun 16, 2023 |
| Unknown       | NETGEAR ReadyNAS 104        | Desktop     | [99df077926](https://linux-hardware.org/?probe=99df077926) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [af1a5cda08](https://linux-hardware.org/?probe=af1a5cda08) | Jun 16, 2023 |
| Acer          | Aspire ES1-522              | Notebook    | [25f52202b2](https://linux-hardware.org/?probe=25f52202b2) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | Notebook    | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [89ac5ef04b](https://linux-hardware.org/?probe=89ac5ef04b) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [f242fcd667](https://linux-hardware.org/?probe=f242fcd667) | Jun 15, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [160f6f4afb](https://linux-hardware.org/?probe=160f6f4afb) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [5fe5f59145](https://linux-hardware.org/?probe=5fe5f59145) | Jun 15, 2023 |
| ASUSTek       | PRIME H310T R2.0            | Desktop     | [7974c3961d](https://linux-hardware.org/?probe=7974c3961d) | Jun 15, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [c1375ab639](https://linux-hardware.org/?probe=c1375ab639) | Jun 15, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [4b99537b32](https://linux-hardware.org/?probe=4b99537b32) | Jun 15, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [3dd5692b24](https://linux-hardware.org/?probe=3dd5692b24) | Jun 15, 2023 |
| HP            | Unknown                     | Notebook    | [00c49ad567](https://linux-hardware.org/?probe=00c49ad567) | Jun 14, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [550aa0fda6](https://linux-hardware.org/?probe=550aa0fda6) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [9b67ef406b](https://linux-hardware.org/?probe=9b67ef406b) | Jun 14, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASRock        | Z97 Extreme6                | Desktop     | [8f727c50fb](https://linux-hardware.org/?probe=8f727c50fb) | Jun 14, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3d5cabad57](https://linux-hardware.org/?probe=3d5cabad57) | Jun 14, 2023 |
| Google        | Ampton                      | Notebook    | [294fa26d20](https://linux-hardware.org/?probe=294fa26d20) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| PC Special... | P65_P67RGRERA               | Notebook    | [49773a4767](https://linux-hardware.org/?probe=49773a4767) | Jun 14, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [448deb90fa](https://linux-hardware.org/?probe=448deb90fa) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [922c598503](https://linux-hardware.org/?probe=922c598503) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [e7f84bdb10](https://linux-hardware.org/?probe=e7f84bdb10) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [7b3593a797](https://linux-hardware.org/?probe=7b3593a797) | Jun 13, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [1302a62eeb](https://linux-hardware.org/?probe=1302a62eeb) | Jun 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [6dadff138b](https://linux-hardware.org/?probe=6dadff138b) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [23a30f1056](https://linux-hardware.org/?probe=23a30f1056) | Jun 13, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| Dell          | Latitude 5411               | Notebook    | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [f47c4b27fe](https://linux-hardware.org/?probe=f47c4b27fe) | Jun 13, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [40d06bae85](https://linux-hardware.org/?probe=40d06bae85) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [4c5907abd5](https://linux-hardware.org/?probe=4c5907abd5) | Jun 12, 2023 |
| Timi          | RedmiBook Pro 14            | Notebook    | [7b2e093b24](https://linux-hardware.org/?probe=7b2e093b24) | Jun 12, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [0b42de0b42](https://linux-hardware.org/?probe=0b42de0b42) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [5286f937d8](https://linux-hardware.org/?probe=5286f937d8) | Jun 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [b7ffc34483](https://linux-hardware.org/?probe=b7ffc34483) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [7221d4851c](https://linux-hardware.org/?probe=7221d4851c) | Jun 11, 2023 |
| Entroware     | Poseidon                    | Desktop     | [506bfb1a08](https://linux-hardware.org/?probe=506bfb1a08) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Acer          | Aspire F5-571               | Notebook    | [e54e3157fc](https://linux-hardware.org/?probe=e54e3157fc) | Jun 11, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [777f28f9e8](https://linux-hardware.org/?probe=777f28f9e8) | Jun 11, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [bc315fc56f](https://linux-hardware.org/?probe=bc315fc56f) | Jun 11, 2023 |
| HP            | 8350                        | Desktop     | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7eda1ce433](https://linux-hardware.org/?probe=7eda1ce433) | Jun 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4fcc967374](https://linux-hardware.org/?probe=4fcc967374) | Jun 11, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [82e1661a51](https://linux-hardware.org/?probe=82e1661a51) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [6f6440cf1e](https://linux-hardware.org/?probe=6f6440cf1e) | Jun 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [dedc98e84e](https://linux-hardware.org/?probe=dedc98e84e) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [4cb72d56f7](https://linux-hardware.org/?probe=4cb72d56f7) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c23450b0df](https://linux-hardware.org/?probe=c23450b0df) | Jun 10, 2023 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [873975925d](https://linux-hardware.org/?probe=873975925d) | Jun 10, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | Notebook    | [4b6aa9a912](https://linux-hardware.org/?probe=4b6aa9a912) | Jun 10, 2023 |
| HP            | ProBook 4510s               | Notebook    | [43a29ea83e](https://linux-hardware.org/?probe=43a29ea83e) | Jun 09, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [adcb3b193a](https://linux-hardware.org/?probe=adcb3b193a) | Jun 09, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [50c36acc0d](https://linux-hardware.org/?probe=50c36acc0d) | Jun 09, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [e68e693394](https://linux-hardware.org/?probe=e68e693394) | Jun 08, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [28a5b69096](https://linux-hardware.org/?probe=28a5b69096) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| AZW           | Green G4 10                 | Desktop     | [326b499893](https://linux-hardware.org/?probe=326b499893) | Jun 08, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [697f2b18e8](https://linux-hardware.org/?probe=697f2b18e8) | Jun 08, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [4614addc21](https://linux-hardware.org/?probe=4614addc21) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [340054cdd5](https://linux-hardware.org/?probe=340054cdd5) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| HP            | 8350                        | Desktop     | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [73fa9d854f](https://linux-hardware.org/?probe=73fa9d854f) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ff5fc17acc](https://linux-hardware.org/?probe=ff5fc17acc) | Jun 07, 2023 |
| ECS           | GF8100VM-M5                 | Desktop     | [6aa065057f](https://linux-hardware.org/?probe=6aa065057f) | Jun 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [27771c5ea8](https://linux-hardware.org/?probe=27771c5ea8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X61 7674GS3        | Notebook    | [629a290a98](https://linux-hardware.org/?probe=629a290a98) | Jun 07, 2023 |
| Foxconn       | H55M-S                      | Desktop     | [83b86844c0](https://linux-hardware.org/?probe=83b86844c0) | Jun 06, 2023 |
| Sony          | VPCEH3N6E                   | Notebook    | [788ddd35a8](https://linux-hardware.org/?probe=788ddd35a8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e4335c33f6](https://linux-hardware.org/?probe=e4335c33f6) | Jun 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [99a7a5bd6e](https://linux-hardware.org/?probe=99a7a5bd6e) | Jun 06, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [76a8e35b72](https://linux-hardware.org/?probe=76a8e35b72) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [413ef09459](https://linux-hardware.org/?probe=413ef09459) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [78459738e9](https://linux-hardware.org/?probe=78459738e9) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [b969b91080](https://linux-hardware.org/?probe=b969b91080) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [8c6a275a93](https://linux-hardware.org/?probe=8c6a275a93) | Jun 05, 2023 |
| Dell          | Latitude E5250              | Notebook    | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [e3f89d1faa](https://linux-hardware.org/?probe=e3f89d1faa) | Jun 04, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 1136      | 13.33%  |
| Ubuntu 18.04                 | 600       | 7.04%   |
| Ubuntu 22.04                 | 491       | 5.76%   |
| Zorin 16                     | 220       | 2.58%   |
| Arch Rolling                 | 176       | 2.07%   |
| Debian 11                    | 173       | 2.03%   |
| Pop!_OS 22.04                | 153       | 1.8%    |
| OpenMandriva 4.3             | 145       | 1.7%    |
| OpenMandriva 4.2             | 133       | 1.56%   |
| Manjaro                      | 127       | 1.49%   |
| ArcoLinux Rolling            | 124       | 1.46%   |
| Linux Mint 20.3              | 120       | 1.41%   |
| Linux Mint 21.1              | 116       | 1.36%   |
| Linux Mint 20.2              | 113       | 1.33%   |
| Linux Mint 19.3              | 112       | 1.31%   |
| KDE neon 20.04               | 112       | 1.31%   |
| Pop!_OS 20.04                | 108       | 1.27%   |
| Ubuntu 19.04                 | 105       | 1.23%   |
| Ubuntu 20.10                 | 100       | 1.17%   |
| Pop!_OS 21.04                | 100       | 1.17%   |
| Arch                         | 97        | 1.14%   |
| Zorin 15                     | 94        | 1.1%    |
| Ubuntu 21.10                 | 94        | 1.1%    |
| Ubuntu 19.10                 | 89        | 1.04%   |
| Pop!_OS 20.10                | 86        | 1.01%   |
| Linux Mint 20.1              | 86        | 1.01%   |
| Fedora 38                    | 86        | 1.01%   |
| OpenMandriva 23.01           | 82        | 0.96%   |
| Ubuntu 21.04                 | 81        | 0.95%   |
| OpenMandriva 23.03           | 78        | 0.92%   |
| Xubuntu 20.04                | 77        | 0.9%    |
| Fedora 36                    | 70        | 0.82%   |
| Fedora 37                    | 68        | 0.8%    |
| Linux Mint 20                | 67        | 0.79%   |
| Kubuntu 20.04                | 60        | 0.7%    |
| Fedora 34                    | 60        | 0.7%    |
| Ubuntu 23.04                 | 57        | 0.67%   |
| Pop!_OS 21.10                | 57        | 0.67%   |
| openSUSE Tumbleweed-XXXXXXXX | 57        | 0.67%   |
| Fedora 35                    | 57        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2770      | 34.24%  |
| Linux Mint    | 728       | 9%      |
| OpenMandriva  | 514       | 6.35%   |
| Pop!_OS       | 479       | 5.92%   |
| Fedora        | 469       | 5.8%    |
| Zorin         | 324       | 4.01%   |
| Debian        | 313       | 3.87%   |
| Arch          | 271       | 3.35%   |
| Manjaro       | 252       | 3.12%   |
| Kubuntu       | 195       | 2.41%   |
| KDE neon      | 162       | 2%      |
| Xubuntu       | 159       | 1.97%   |
| ArcoLinux     | 128       | 1.58%   |
| SteamOS       | 106       | 1.31%   |
| openSUSE      | 83        | 1.03%   |
| Gentoo        | 81        | 1%      |
| ROSA          | 79        | 0.98%   |
| Elementary    | 77        | 0.95%   |
| Ubuntu MATE   | 68        | 0.84%   |
| Lubuntu       | 60        | 0.74%   |
| Endless       | 57        | 0.7%    |
| Kali          | 53        | 0.66%   |
| Ubuntu Unity  | 51        | 0.63%   |
| Clear Linux   | 46        | 0.57%   |
| BlackPanther  | 44        | 0.54%   |
| EndeavourOS   | 33        | 0.41%   |
| Nobara        | 31        | 0.38%   |
| LMDE          | 31        | 0.38%   |
| MX            | 30        | 0.37%   |
| Garuda Linux  | 28        | 0.35%   |
| CentOS        | 28        | 0.35%   |
| Raspbian      | 25        | 0.31%   |
| Ubuntu Budgie | 24        | 0.3%    |
| Parrot        | 19        | 0.23%   |
| RHEL          | 18        | 0.22%   |
| Peppermint    | 17        | 0.21%   |
| NixOS         | 16        | 0.2%    |
| Slackware     | 13        | 0.16%   |
| Alpine        | 9         | 0.11%   |
| Linux Lite    | 8         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 152       | 1.6%    |
| 5.16.7-desktop-1omv4003  | 137       | 1.44%   |
| 5.10.14-desktop-1omv4002 | 130       | 1.37%   |
| 5.15.0-56-generic        | 85        | 0.89%   |
| 5.4.0-48-generic         | 81        | 0.85%   |
| 6.2.6-desktop-1omv2390   | 77        | 0.81%   |
| 5.4.0-52-generic         | 76        | 0.8%    |
| 6.1.1-desktop-1omv2290   | 74        | 0.78%   |
| 5.4.0-29-generic         | 73        | 0.77%   |
| 5.4.0-26-generic         | 70        | 0.74%   |
| 5.3.0-28-generic         | 65        | 0.68%   |
| 5.15.0-52-generic        | 65        | 0.68%   |
| 5.15.0-58-generic        | 64        | 0.67%   |
| 5.15.0-46-generic        | 64        | 0.67%   |
| 5.3.0-40-generic         | 60        | 0.63%   |
| 5.4.0-40-generic         | 53        | 0.56%   |
| 5.4.0-58-generic         | 51        | 0.54%   |
| 5.4.0-37-generic         | 51        | 0.54%   |
| 5.11.0-27-generic        | 51        | 0.54%   |
| 5.4.0-65-generic         | 45        | 0.47%   |
| 5.4.0-33-generic         | 45        | 0.47%   |
| 5.11.0-38-generic        | 45        | 0.47%   |
| 5.0.0-32-generic         | 45        | 0.47%   |
| 5.4.0-91-generic         | 43        | 0.45%   |
| 5.19.0-35-generic        | 43        | 0.45%   |
| 5.13.0-7614-generic      | 43        | 0.45%   |
| 5.11.0-25-generic        | 43        | 0.45%   |
| 5.13.0-valve36-1-neptune | 42        | 0.44%   |
| 6.2.0-26-generic         | 41        | 0.43%   |
| 5.4.0-7634-generic       | 41        | 0.43%   |
| 5.4.0-54-generic         | 41        | 0.43%   |
| 5.3.0-46-generic         | 41        | 0.43%   |
| 5.4.0-74-generic         | 40        | 0.42%   |
| 5.4.0-66-generic         | 40        | 0.42%   |
| 5.8.0-7630-generic       | 39        | 0.41%   |
| 5.8.0-43-generic         | 39        | 0.41%   |
| 5.11.0-7620-generic      | 39        | 0.41%   |
| 5.0.0-37-generic         | 39        | 0.41%   |
| 5.15.0-48-generic        | 38        | 0.4%    |
| 5.13.0-39-generic        | 38        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1512      | 17.09%  |
| 5.15.0  | 798       | 9.02%   |
| 5.13.0  | 469       | 5.3%    |
| 5.11.0  | 457       | 5.16%   |
| 5.8.0   | 450       | 5.09%   |
| 4.15.0  | 420       | 4.75%   |
| 5.3.0   | 374       | 4.23%   |
| 5.19.0  | 295       | 3.33%   |
| 5.0.0   | 244       | 2.76%   |
| 5.10.0  | 205       | 2.32%   |
| 4.18.0  | 181       | 2.05%   |
| 6.2.0   | 160       | 1.81%   |
| 5.16.7  | 138       | 1.56%   |
| 5.10.14 | 130       | 1.47%   |
| 6.2.6   | 120       | 1.36%   |
| 6.1.1   | 79        | 0.89%   |
| 6.1.0   | 71        | 0.8%    |
| 4.19.0  | 58        | 0.66%   |
| 6.4.11  | 38        | 0.43%   |
| 5.17.5  | 37        | 0.42%   |
| 5.14.0  | 36        | 0.41%   |
| 4.18.16 | 34        | 0.38%   |
| 6.0.0   | 33        | 0.37%   |
| 6.0.6   | 26        | 0.29%   |
| 6.0.12  | 26        | 0.29%   |
| 4.9.60  | 26        | 0.29%   |
| 5.9.16  | 25        | 0.28%   |
| 5.18.0  | 22        | 0.25%   |
| 5.16.13 | 21        | 0.24%   |
| 4.4.0   | 21        | 0.24%   |
| 6.4.12  | 19        | 0.21%   |
| 5.17.1  | 19        | 0.21%   |
| 6.2.9   | 18        | 0.2%    |
| 5.18.12 | 18        | 0.2%    |
| 5.16.11 | 18        | 0.2%    |
| 6.4.6   | 17        | 0.19%   |
| 6.3.5   | 17        | 0.19%   |
| 5.15.12 | 17        | 0.19%   |
| 5.13.12 | 17        | 0.19%   |
| 5.7.0   | 16        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1603      | 18.38%  |
| 5.15    | 994       | 11.4%   |
| 5.13    | 555       | 6.36%   |
| 5.8     | 537       | 6.16%   |
| 5.11    | 516       | 5.92%   |
| 5.10    | 470       | 5.39%   |
| 5.3     | 425       | 4.87%   |
| 4.15    | 422       | 4.84%   |
| 5.19    | 386       | 4.43%   |
| 6.2     | 380       | 4.36%   |
| 6.1     | 300       | 3.44%   |
| 5.0     | 254       | 2.91%   |
| 5.16    | 249       | 2.86%   |
| 4.18    | 218       | 2.5%    |
| 6.0     | 157       | 1.8%    |
| 6.4     | 153       | 1.75%   |
| 5.14    | 109       | 1.25%   |
| 5.17    | 108       | 1.24%   |
| 6.3     | 102       | 1.17%   |
| 5.9     | 95        | 1.09%   |
| 5.18    | 93        | 1.07%   |
| 4.19    | 91        | 1.04%   |
| 5.12    | 88        | 1.01%   |
| 5.6     | 77        | 0.88%   |
| 4.9     | 74        | 0.85%   |
| 5.7     | 68        | 0.78%   |
| 5.5     | 42        | 0.48%   |
| 6.5     | 35        | 0.4%    |
| 4.4     | 25        | 0.29%   |
| 5.2     | 23        | 0.26%   |
| 5.1     | 16        | 0.18%   |
| 4.14    | 10        | 0.11%   |
| 3.10    | 10        | 0.11%   |
| 4.1     | 9         | 0.1%    |
| 4.20    | 5         | 0.06%   |
| 4.13    | 5         | 0.06%   |
| 3.13    | 4         | 0.05%   |
| 4.16    | 3         | 0.03%   |
| 4.12    | 3         | 0.03%   |
| 4.8     | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7480      | 96.35%  |
| i686    | 182       | 2.34%   |
| aarch64 | 72        | 0.93%   |
| armv7l  | 27        | 0.35%   |
| riscv64 | 1         | 0.01%   |
| armv6l  | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 3650      | 44.86%  |
| KDE5             | 1400      | 17.21%  |
| Unknown          | 967       | 11.88%  |
| X-Cinnamon       | 592       | 7.28%   |
| XFCE             | 548       | 6.73%   |
| MATE             | 208       | 2.56%   |
| KDE              | 180       | 2.21%   |
| Cinnamon         | 91        | 1.12%   |
| Pantheon         | 73        | 0.9%    |
| LXQt             | 61        | 0.75%   |
| Unity            | 54        | 0.66%   |
| LXDE             | 54        | 0.66%   |
| KDE4             | 36        | 0.44%   |
| i3               | 34        | 0.42%   |
| Budgie           | 34        | 0.42%   |
| GNOME Flashback  | 28        | 0.34%   |
| sway             | 15        | 0.18%   |
| Deepin           | 13        | 0.16%   |
| openbox          | 11        | 0.14%   |
| GNOME Classic    | 11        | 0.14%   |
| Hyprland         | 10        | 0.12%   |
| awesome          | 9         | 0.11%   |
| qtile            | 8         | 0.1%    |
| lightdm-xsession | 7         | 0.09%   |
| xmonad           | 6         | 0.07%   |
| bspwm            | 6         | 0.07%   |
| trinity          | 4         | 0.05%   |
| chadwm           | 4         | 0.05%   |
| mwm              | 3         | 0.04%   |
| Enlightenment    | 3         | 0.04%   |
| DWM              | 3         | 0.04%   |
| i3-with-shmlog   | 2         | 0.02%   |
| Cutefish         | 2         | 0.02%   |
| xubuntu          | 1         | 0.01%   |
| WindowMaker      | 1         | 0.01%   |
| Unicorn:XFCE     | 1         | 0.01%   |
| Phosh:GNOME      | 1         | 0.01%   |
| LeftWM           | 1         | 0.01%   |
| icewm            | 1         | 0.01%   |
| Hypr             | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 6057      | 75.87%  |
| Wayland | 1258      | 15.76%  |
| Unknown | 472       | 5.91%   |
| Tty     | 195       | 2.44%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4340      | 53.59%  |
| SDDM    | 1153      | 14.24%  |
| GDM3    | 858       | 10.59%  |
| GDM     | 767       | 9.47%   |
| LightDM | 705       | 8.7%    |
| TDM     | 198       | 2.44%   |
| KDM     | 35        | 0.43%   |
| XDM     | 15        | 0.19%   |
| LXDM    | 9         | 0.11%   |
| SLiM    | 6         | 0.07%   |
| Ly      | 6         | 0.07%   |
| GREETD  | 2         | 0.02%   |
| XINIT   | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| LY-DM   | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_GB          | 5782      | 72.6%   |
| en_US          | 996       | 12.51%  |
| Unknown        | 823       | 10.33%  |
| C              | 128       | 1.61%   |
| pl_PL          | 64        | 0.8%    |
| POSIX          | 15        | 0.19%   |
| de_DE          | 14        | 0.18%   |
| ru_RU          | 13        | 0.16%   |
| en_IE          | 11        | 0.14%   |
| en_CA          | 11        | 0.14%   |
| it_IT          | 10        | 0.13%   |
| fr_FR          | 10        | 0.13%   |
| en_IN          | 7         | 0.09%   |
| en_AU          | 7         | 0.09%   |
| ro_RO          | 6         | 0.08%   |
| hu_HU          | 6         | 0.08%   |
| es_ES          | 6         | 0.08%   |
| cs_CZ          | 6         | 0.08%   |
| C.UTF8         | 6         | 0.08%   |
| pt_PT          | 4         | 0.05%   |
| zh_CN          | 3         | 0.04%   |
| uk_UA          | 3         | 0.04%   |
| sk_SK          | 3         | 0.04%   |
| pt_BR          | 3         | 0.04%   |
| nl_NL          | 2         | 0.03%   |
| lt_LT          | 2         | 0.03%   |
| en_ZA          | 2         | 0.03%   |
| en_GB.iso88591 | 2         | 0.03%   |
| da_DK          | 2         | 0.03%   |
| bg_BG          | 2         | 0.03%   |
| wbp_AU         | 1         | 0.01%   |
| us             | 1         | 0.01%   |
| tr_TR          | 1         | 0.01%   |
| ru_UA          | 1         | 0.01%   |
| nl_BE          | 1         | 0.01%   |
| fi_FI          | 1         | 0.01%   |
| et_EE          | 1         | 0.01%   |
| en_US.utf-8    | 1         | 0.01%   |
| en_SG          | 1         | 0.01%   |
| en_IL          | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 4114      | 51.85%  |
| EFI  | 3820      | 48.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 6054      | 75.75%  |
| Btrfs    | 774       | 9.68%   |
| Overlay  | 539       | 6.74%   |
| Unknown  | 233       | 2.92%   |
| Tmpfs    | 163       | 2.04%   |
| Xfs      | 113       | 1.41%   |
| Zfs      | 65        | 0.81%   |
| Ext2     | 21        | 0.26%   |
| Ext3     | 13        | 0.16%   |
| F2fs     | 11        | 0.14%   |
| Aufs     | 2         | 0.03%   |
| XXXX     | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Lvm      | 1         | 0.01%   |
| ExX4     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4468      | 56.05%  |
| GPT     | 2792      | 35.03%  |
| MBR     | 711       | 8.92%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6744      | 85.01%  |
| Yes       | 1189      | 14.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5786      | 73.23%  |
| Yes       | 2115      | 26.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1195      | 15.41%  |
| ASUSTek Computer        | 1127      | 14.53%  |
| Lenovo                  | 986       | 12.71%  |
| Hewlett-Packard         | 963       | 12.42%  |
| Gigabyte Technology     | 556       | 7.17%   |
| MSI                     | 432       | 5.57%   |
| Acer                    | 366       | 4.72%   |
| Apple                   | 234       | 3.02%   |
| ASRock                  | 226       | 2.91%   |
| Toshiba                 | 174       | 2.24%   |
| Intel                   | 140       | 1.81%   |
| Valve                   | 97        | 1.25%   |
| Samsung Electronics     | 91        | 1.17%   |
| Raspberry Pi Foundation | 79        | 1.02%   |
| Sony                    | 67        | 0.86%   |
| Unknown                 | 67        | 0.86%   |
| Google                  | 49        | 0.63%   |
| Fujitsu                 | 49        | 0.63%   |
| PC Specialist           | 46        | 0.59%   |
| Microsoft               | 46        | 0.59%   |
| HUAWEI                  | 46        | 0.59%   |
| Packard Bell            | 38        | 0.49%   |
| Foxconn                 | 34        | 0.44%   |
| Notebook                | 32        | 0.41%   |
| Alienware               | 30        | 0.39%   |
| AZW                     | 29        | 0.37%   |
| Pegatron                | 23        | 0.3%    |
| Fujitsu Siemens         | 22        | 0.28%   |
| Medion                  | 21        | 0.27%   |
| Razer                   | 20        | 0.26%   |
| Star Labs               | 19        | 0.25%   |
| GEO                     | 19        | 0.25%   |
| Biostar                 | 18        | 0.23%   |
| Entroware               | 17        | 0.22%   |
| Linx                    | 16        | 0.21%   |
| AMI                     | 16        | 0.21%   |
| Dixonsxp                | 14        | 0.18%   |
| TUXEDO                  | 13        | 0.17%   |
| Supermicro              | 12        | 0.15%   |
| Clevo                   | 12        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Valve Jupiter                      | 97        | 1.25%   |
| Unknown                            | 91        | 1.17%   |
| ASUS All Series                    | 78        | 1.01%   |
| Dell OptiPlex 7010                 | 33        | 0.43%   |
| MSI MS-7C02                        | 29        | 0.37%   |
| HP Pavilion g6                     | 26        | 0.34%   |
| RPi Raspberry Pi                   | 24        | 0.31%   |
| MSI MS-7C37                        | 22        | 0.28%   |
| ASUS M5A78L-M/USB3                 | 22        | 0.28%   |
| HP Notebook                        | 21        | 0.27%   |
| Dell OptiPlex 755                  | 21        | 0.27%   |
| ASUS TUF Gaming X570-PLUS          | 21        | 0.27%   |
| HP Pavilion 15                     | 20        | 0.26%   |
| ASUS ROG STRIX B450-F GAMING       | 20        | 0.26%   |
| Dell OptiPlex 780                  | 19        | 0.25%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 17        | 0.22%   |
| HP Pavilion Notebook               | 17        | 0.22%   |
| Dell OptiPlex 790                  | 17        | 0.22%   |
| Dell XPS 15 9560                   | 16        | 0.21%   |
| Dell XPS 15 7590                   | 16        | 0.21%   |
| Gigabyte 970A-DS3P                 | 15        | 0.19%   |
| Dell Inspiron 1545                 | 15        | 0.19%   |
| ASUS ROG STRIX B550-F GAMING       | 15        | 0.19%   |
| ASUS PRIME A320M-K                 | 15        | 0.19%   |
| Gigabyte X570 AORUS ELITE          | 14        | 0.18%   |
| Dell XPS 15 9570                   | 14        | 0.18%   |
| Dell XPS 13 9380                   | 14        | 0.18%   |
| Dell XPS 13 9370                   | 14        | 0.18%   |
| MSI MS-7C91                        | 13        | 0.17%   |
| Microsoft Surface Pro 4            | 13        | 0.17%   |
| Dell XPS 13 9360                   | 13        | 0.17%   |
| Dell OptiPlex 3020                 | 13        | 0.17%   |
| Dell Latitude E6400                | 13        | 0.17%   |
| Gigabyte GA-78LMT-USB3             | 12        | 0.15%   |
| Dell Latitude E6410                | 12        | 0.15%   |
| ASUS PRIME B450-PLUS               | 12        | 0.15%   |
| Apple MacBookPro12,1               | 12        | 0.15%   |
| Toshiba Satellite C660             | 11        | 0.14%   |
| Lenovo V145-15AST 81MT             | 11        | 0.14%   |
| HP ProLiant MicroServer            | 11        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 463       | 5.97%   |
| Dell Latitude          | 276       | 3.56%   |
| Acer Aspire            | 261       | 3.37%   |
| Dell Inspiron          | 250       | 3.22%   |
| Dell OptiPlex          | 210       | 2.71%   |
| Dell XPS               | 205       | 2.64%   |
| ASUS ROG               | 180       | 2.32%   |
| HP Pavilion            | 160       | 2.06%   |
| Toshiba Satellite      | 150       | 1.93%   |
| Lenovo IdeaPad         | 147       | 1.9%    |
| ASUS PRIME             | 137       | 1.77%   |
| HP EliteBook           | 115       | 1.48%   |
| Dell Precision         | 106       | 1.37%   |
| HP Compaq              | 100       | 1.29%   |
| Valve Jupiter          | 97        | 1.25%   |
| Unknown                | 91        | 1.17%   |
| RPi Raspberry          | 79        | 1.02%   |
| ASUS All               | 78        | 1.01%   |
| Lenovo ThinkCentre     | 75        | 0.97%   |
| HP Laptop              | 72        | 0.93%   |
| HP ProBook             | 66        | 0.85%   |
| ASUS VivoBook          | 65        | 0.84%   |
| ASUS TUF               | 63        | 0.81%   |
| HP ENVY                | 60        | 0.77%   |
| Lenovo Yoga            | 54        | 0.7%    |
| Dell Vostro            | 50        | 0.64%   |
| Microsoft Surface      | 46        | 0.59%   |
| Gigabyte X570          | 38        | 0.49%   |
| HP ProLiant            | 36        | 0.46%   |
| Lenovo Legion          | 32        | 0.41%   |
| HP EliteDesk           | 32        | 0.41%   |
| ASUS M5A78L-M          | 32        | 0.41%   |
| ASUS ZenBook           | 31        | 0.4%    |
| MSI MS-7C02            | 29        | 0.37%   |
| HP Stream              | 29        | 0.37%   |
| Acer Swift             | 29        | 0.37%   |
| Gigabyte GA-78LMT-USB3 | 27        | 0.35%   |
| HP Spectre             | 26        | 0.34%   |
| MSI MS-7C37            | 22        | 0.28%   |
| Lenovo ThinkBook       | 21        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 742       | 9.57%   |
| 2019    | 657       | 8.47%   |
| 2020    | 623       | 8.03%   |
| 2012    | 614       | 7.92%   |
| 2013    | 531       | 6.85%   |
| 2017    | 515       | 6.64%   |
| 2011    | 500       | 6.45%   |
| 2014    | 491       | 6.33%   |
| 2021    | 475       | 6.13%   |
| 2015    | 410       | 5.29%   |
| 2010    | 397       | 5.12%   |
| 2016    | 394       | 5.08%   |
| 2022    | 347       | 4.47%   |
| 2009    | 302       | 3.89%   |
| 2008    | 289       | 3.73%   |
| 2007    | 201       | 2.59%   |
| 2006    | 83        | 1.07%   |
| Unknown | 81        | 1.04%   |
| 2023    | 64        | 0.83%   |
| 2005    | 27        | 0.35%   |
| 2004    | 6         | 0.08%   |
| 2003    | 3         | 0.04%   |
| 2002    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3955      | 51%     |
| Desktop        | 3059      | 39.45%  |
| Convertible    | 175       | 2.26%   |
| Mini pc        | 163       | 2.1%    |
| All in one     | 142       | 1.83%   |
| Tablet         | 102       | 1.32%   |
| System on chip | 91        | 1.17%   |
| Server         | 63        | 0.81%   |
| Phone          | 4         | 0.05%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7197      | 92.06%  |
| Enabled  | 621       | 7.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7685      | 99.08%  |
| Yes  | 71        | 0.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1755      | 22.21%  |
| 16.01-24.0      | 1693      | 21.43%  |
| 8.01-16.0       | 1359      | 17.2%   |
| 3.01-4.0        | 1312      | 16.61%  |
| 32.01-64.0      | 871       | 11.02%  |
| 1.01-2.0        | 328       | 4.15%   |
| 64.01-256.0     | 241       | 3.05%   |
| 2.01-3.0        | 134       | 1.7%    |
| 24.01-32.0      | 129       | 1.63%   |
| 0.51-1.0        | 61        | 0.77%   |
| More than 256.0 | 12        | 0.15%   |
| 0.01-0.5        | 6         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 3117      | 35.81%  |
| 2.01-3.0    | 2155      | 24.76%  |
| 4.01-8.0    | 1231      | 14.14%  |
| 3.01-4.0    | 1088      | 12.5%   |
| 0.51-1.0    | 529       | 6.08%   |
| 8.01-16.0   | 361       | 4.15%   |
| 0.01-0.5    | 118       | 1.36%   |
| 16.01-24.0  | 53        | 0.61%   |
| 24.01-32.0  | 25        | 0.29%   |
| 32.01-64.0  | 19        | 0.22%   |
| 64.01-256.0 | 5         | 0.06%   |
| Unknown     | 4         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4532      | 56.38%  |
| 2       | 2014      | 25.05%  |
| 3       | 655       | 8.15%   |
| 4       | 359       | 4.47%   |
| 5       | 199       | 2.48%   |
| 6       | 95        | 1.18%   |
| 0       | 77        | 0.96%   |
| 7       | 42        | 0.52%   |
| 8       | 17        | 0.21%   |
| 9       | 14        | 0.17%   |
| Unknown | 8         | 0.1%    |
| 11      | 7         | 0.09%   |
| 10      | 6         | 0.07%   |
| 12      | 5         | 0.06%   |
| 13      | 3         | 0.04%   |
| 29      | 1         | 0.01%   |
| 25      | 1         | 0.01%   |
| 23      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4768      | 60.86%  |
| Yes       | 3066      | 39.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6486      | 83.45%  |
| No        | 1286      | 16.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5963      | 76.21%  |
| No        | 1861      | 23.79%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4628      | 58.91%  |
| No        | 3228      | 41.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 7755      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 507       | 5.9%    |
| Manchester          | 193       | 2.25%   |
| Birmingham          | 139       | 1.62%   |
| Bristol             | 134       | 1.56%   |
| Glasgow             | 122       | 1.42%   |
| Edinburgh           | 118       | 1.37%   |
| Sheffield           | 104       | 1.21%   |
| Nottingham          | 104       | 1.21%   |
| Leeds               | 102       | 1.19%   |
| Liverpool           | 100       | 1.16%   |
| Islington           | 80        | 0.93%   |
| Reading             | 79        | 0.92%   |
| Cambridge           | 70        | 0.81%   |
| Norwich             | 64        | 0.75%   |
| Southampton         | 58        | 0.68%   |
| Leicester           | 56        | 0.65%   |
| Milton Keynes       | 54        | 0.63%   |
| Croydon             | 54        | 0.63%   |
| Coventry            | 53        | 0.62%   |
| Cardiff             | 52        | 0.61%   |
| Derby               | 51        | 0.59%   |
| Bradford            | 51        | 0.59%   |
| York                | 45        | 0.52%   |
| Newcastle upon Tyne | 45        | 0.52%   |
| Oxford              | 44        | 0.51%   |
| Swindon             | 43        | 0.5%    |
| Hackney             | 43        | 0.5%    |
| Brighton            | 42        | 0.49%   |
| Aberdeen            | 42        | 0.49%   |
| Gloucester          | 40        | 0.47%   |
| Bolton              | 40        | 0.47%   |
| Wolverhampton       | 38        | 0.44%   |
| Wigan               | 38        | 0.44%   |
| Plymouth            | 38        | 0.44%   |
| Sunderland          | 34        | 0.4%    |
| Walsall             | 33        | 0.38%   |
| Harrow              | 32        | 0.37%   |
| Stoke-on-Trent      | 31        | 0.36%   |
| Kensington          | 31        | 0.36%   |
| City of London      | 31        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1803      | 2835   | 15.33%  |
| Seagate                     | 1710      | 2871   | 14.54%  |
| WDC                         | 1569      | 2602   | 13.34%  |
| Toshiba                     | 770       | 1066   | 6.55%   |
| SanDisk                     | 712       | 972    | 6.05%   |
| Unknown                     | 647       | 876    | 5.5%    |
| Crucial                     | 632       | 918    | 5.37%   |
| Kingston                    | 503       | 677    | 4.28%   |
| Hitachi                     | 419       | 575    | 3.56%   |
| SK hynix                    | 261       | 308    | 2.22%   |
| Intel                       | 254       | 344    | 2.16%   |
| HGST                        | 177       | 259    | 1.5%    |
| Phison                      | 159       | 214    | 1.35%   |
| Micron Technology           | 135       | 160    | 1.15%   |
| Apple                       | 121       | 167    | 1.03%   |
| China                       | 120       | 165    | 1.02%   |
| A-DATA Technology           | 101       | 133    | 0.86%   |
| KIOXIA                      | 80        | 107    | 0.68%   |
| Phison Electronics          | 75        | 113    | 0.64%   |
| OCZ                         | 71        | 82     | 0.6%    |
| Micron/Crucial Technology   | 67        | 86     | 0.57%   |
| PNY                         | 65        | 81     | 0.55%   |
| Silicon Motion              | 64        | 78     | 0.54%   |
| Maxtor                      | 60        | 91     | 0.51%   |
| LITEON                      | 59        | 74     | 0.5%    |
| Transcend                   | 56        | 67     | 0.48%   |
| Corsair                     | 53        | 73     | 0.45%   |
| Unknown                     | 49        | 62     | 0.42%   |
| Fujitsu                     | 46        | 64     | 0.39%   |
| Kingston Technology Company | 38        | 40     | 0.32%   |
| Integral                    | 35        | 41     | 0.3%    |
| LITEONIT                    | 33        | 42     | 0.28%   |
| Netac                       | 31        | 41     | 0.26%   |
| JMicron Technology          | 31        | 44     | 0.26%   |
| SABRENT                     | 30        | 34     | 0.26%   |
| Patriot                     | 28        | 44     | 0.24%   |
| Gigabyte Technology         | 27        | 36     | 0.23%   |
| SPCC                        | 26        | 40     | 0.22%   |
| ASMT                        | 25        | 57     | 0.21%   |
| Drevo                       | 19        | 31     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 127       | 0.96%   |
| Samsung SSD 850 EVO 250GB                           | 100       | 0.76%   |
| Kingston SA400S37240G 240GB SSD                     | 99        | 0.75%   |
| Seagate ST3500312CS 500GB                           | 93        | 0.7%    |
| Crucial CT1000MX500SSD1 1TB                         | 87        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB                      | 86        | 0.65%   |
| Samsung SSD 850 EVO 500GB                           | 84        | 0.64%   |
| Unknown MMC Card  64GB                              | 82        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB                      | 82        | 0.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 81        | 0.61%   |
| Crucial CT500MX500SSD1 500GB                        | 80        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 77        | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB                      | 74        | 0.56%   |
| Kingston SA400S37120G 120GB SSD                     | 71        | 0.54%   |
| Samsung SSD 860 EVO 500GB                           | 69        | 0.52%   |
| Unknown MMC Card  128GB                             | 63        | 0.48%   |
| Samsung SSD 860 EVO 1TB                             | 63        | 0.48%   |
| Samsung NVMe SSD Drive 500GB                        | 63        | 0.48%   |
| Toshiba MQ01ABD100 1TB                              | 62        | 0.47%   |
| Seagate ST500DM002-1BD142 500GB                     | 61        | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB                        | 61        | 0.46%   |
| Samsung NVMe SSD Drive 512GB                        | 54        | 0.41%   |
| Crucial CT240BX500SSD1 240GB                        | 53        | 0.4%    |
| Samsung NVMe SSD Drive 1TB                          | 50        | 0.38%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 49        | 0.37%   |
| Unknown                                             | 49        | 0.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 48        | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB                      | 46        | 0.35%   |
| Unknown SD/MMC/MS PRO 128GB                         | 45        | 0.34%   |
| Seagate Expansion 1TB                               | 44        | 0.33%   |
| SanDisk NVMe SSD Drive 1TB                          | 44        | 0.33%   |
| Crucial CT250MX500SSD1 250GB                        | 44        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                    | 43        | 0.33%   |
| Samsung SSD 840 EVO 250GB                           | 42        | 0.32%   |
| Toshiba DT01ACA100 1TB                              | 40        | 0.3%    |
| SanDisk SSD PLUS 480GB                              | 40        | 0.3%    |
| Unknown MMC Card  16GB                              | 39        | 0.3%    |
| Toshiba MQ01ABF050 500GB                            | 39        | 0.3%    |
| SanDisk SSD PLUS 240GB                              | 39        | 0.3%    |
| Kingston SA400S37480G 480GB SSD                     | 39        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1655      | 2744   | 36.05%  |
| WDC                 | 1228      | 2088   | 26.75%  |
| Toshiba             | 565       | 781    | 12.31%  |
| Hitachi             | 418       | 573    | 9.1%    |
| Samsung Electronics | 226       | 321    | 4.92%   |
| HGST                | 175       | 256    | 3.81%   |
| Unknown             | 52        | 71     | 1.13%   |
| Apple               | 51        | 62     | 1.11%   |
| Maxtor              | 50        | 80     | 1.09%   |
| Fujitsu             | 46        | 64     | 1%      |
| SABRENT             | 27        | 31     | 0.59%   |
| Hewlett-Packard     | 15        | 50     | 0.33%   |
| ASMT                | 12        | 41     | 0.26%   |
| USB3.0              | 9         | 14     | 0.2%    |
| SSK                 | 7         | 8      | 0.15%   |
| ASMedia             | 7         | 13     | 0.15%   |
| WD MediaMax         | 4         | 4      | 0.09%   |
| LaCie               | 4         | 4      | 0.09%   |
| HPE                 | 4         | 7      | 0.09%   |
| External            | 4         | 4      | 0.09%   |
| USB                 | 3         | 3      | 0.07%   |
| ASMT109x            | 3         | 5      | 0.07%   |
| RSH-339             | 2         | 2      | 0.04%   |
| KESU                | 2         | 6      | 0.04%   |
| JMicron Technology  | 2         | 5      | 0.04%   |
| Initio              | 2         | 2      | 0.04%   |
| IBM/Hitachi         | 2         | 2      | 0.04%   |
| ExcelStor           | 2         | 4      | 0.04%   |
| TDAS                | 1         | 8      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| NETAPP              | 1         | 4      | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| LIO-ORG             | 1         | 8      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 884       | 1331   | 22.48%  |
| Crucial             | 571       | 846    | 14.52%  |
| SanDisk             | 448       | 583    | 11.39%  |
| Kingston            | 427       | 573    | 10.86%  |
| WDC                 | 211       | 299    | 5.37%   |
| China               | 116       | 158    | 2.95%   |
| Intel               | 98        | 112    | 2.49%   |
| A-DATA Technology   | 79        | 102    | 2.01%   |
| OCZ                 | 71        | 82     | 1.81%   |
| Toshiba             | 66        | 85     | 1.68%   |
| Micron Technology   | 64        | 75     | 1.63%   |
| SK hynix            | 63        | 77     | 1.6%    |
| PNY                 | 62        | 74     | 1.58%   |
| LITEON              | 57        | 72     | 1.45%   |
| Apple               | 54        | 69     | 1.37%   |
| Transcend           | 52        | 63     | 1.32%   |
| Integral            | 35        | 41     | 0.89%   |
| LITEONIT            | 33        | 42     | 0.84%   |
| Corsair             | 31        | 44     | 0.79%   |
| Netac               | 30        | 38     | 0.76%   |
| Patriot             | 27        | 43     | 0.69%   |
| Seagate             | 25        | 32     | 0.64%   |
| SPCC                | 22        | 35     | 0.56%   |
| Gigabyte Technology | 20        | 27     | 0.51%   |
| Drevo               | 19        | 31     | 0.48%   |
| Team                | 15        | 16     | 0.38%   |
| KIOXIA-EXCERIA      | 15        | 20     | 0.38%   |
| JMicron Technology  | 15        | 21     | 0.38%   |
| Unknown             | 14        | 20     | 0.36%   |
| Lexar               | 13        | 15     | 0.33%   |
| Vaseky              | 12        | 17     | 0.31%   |
| TO Exter            | 12        | 14     | 0.31%   |
| TCSUNBOW            | 12        | 19     | 0.31%   |
| ASMT                | 12        | 15     | 0.31%   |
| ORTIAL              | 11        | 12     | 0.28%   |
| Maxtor              | 10        | 11     | 0.25%   |
| Plextor             | 8         | 11     | 0.2%    |
| Unknown             | 8         | 9      | 0.2%    |
| XUM                 | 7         | 7      | 0.18%   |
| Teclast             | 7         | 8      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3728      | 7276   | 36.2%   |
| SSD     | 3312      | 5406   | 32.16%  |
| NVMe    | 2496      | 3658   | 24.24%  |
| MMC     | 600       | 791    | 5.83%   |
| Unknown | 162       | 237    | 1.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5690      | 12034  | 61.19%  |
| NVMe | 2491      | 3640   | 26.79%  |
| MMC  | 600       | 791    | 6.45%   |
| SAS  | 518       | 903    | 5.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 4241      | 6983   | 55.74%  |
| 0.51-1.0        | 2060      | 3227   | 27.08%  |
| 1.01-2.0        | 682       | 1174   | 8.96%   |
| 3.01-4.0        | 233       | 481    | 3.06%   |
| 4.01-10.0       | 181       | 409    | 2.38%   |
| 2.01-3.0        | 180       | 327    | 2.37%   |
| 10.01-20.0      | 29        | 79     | 0.38%   |
| More than 100.0 | 1         | 1      | 0.01%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2169      | 26.19%  |
| 251-500        | 1634      | 19.73%  |
| 501-1000       | 1257      | 15.18%  |
| 1001-2000      | 670       | 8.09%   |
| 1-20           | 593       | 7.16%   |
| More than 3000 | 547       | 6.6%    |
| 51-100         | 524       | 6.33%   |
| 21-50          | 373       | 4.5%    |
| 2001-3000      | 263       | 3.18%   |
| Unknown        | 253       | 3.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3358      | 39.11%  |
| 21-50          | 1403      | 16.34%  |
| 101-250        | 1005      | 11.71%  |
| 51-100         | 903       | 10.52%  |
| 251-500        | 638       | 7.43%   |
| 501-1000       | 442       | 5.15%   |
| 1001-2000      | 287       | 3.34%   |
| Unknown        | 253       | 2.95%   |
| More than 3000 | 195       | 2.27%   |
| 2001-3000      | 99        | 1.15%   |
| 0              | 2         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 8         | 12     | 1.34%   |
| Seagate ST9500325AS 500GB                | 7         | 11     | 1.17%   |
| Seagate ST500LM021-1KJ152 500GB          | 6         | 6      | 1%      |
| Seagate ST500DM002-1BD142 500GB          | 6         | 6      | 1%      |
| Seagate ST3500418AS 500GB                | 6         | 6      | 1%      |
| Seagate ST1000LM035-1RK172 1TB           | 6         | 6      | 1%      |
| Samsung Electronics HD103UJ 1TB          | 6         | 8      | 1%      |
| HGST HTS725050A7E630 500GB               | 6         | 9      | 1%      |
| Seagate ST3500312CS 500GB                | 5         | 7      | 0.84%   |
| Hitachi HTS547575A9E384 752GB            | 5         | 7      | 0.84%   |
| Seagate ST2000DM001-1CH164 2TB           | 4         | 5      | 0.67%   |
| Samsung Electronics SSD 960 EVO 250GB    | 4         | 5      | 0.67%   |
| Samsung Electronics HD103SJ 1TB          | 4         | 5      | 0.67%   |
| Hitachi HTS545025B9A300 250GB            | 4         | 4      | 0.67%   |
| Hitachi HTS542512K9SA00 120GB            | 4         | 4      | 0.67%   |
| Hitachi HDT721010SLA360 1TB              | 4         | 5      | 0.67%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 0.67%   |
| WDC WD6400AAKS-22A7B2 640GB              | 3         | 3      | 0.5%    |
| WDC WD60EFRX-68L0BN1 6TB                 | 3         | 20     | 0.5%    |
| WDC WD5000BEVT-75A0RT0 500GB             | 3         | 5      | 0.5%    |
| WDC WD40EFRX-68WT0N0 4TB                 | 3         | 10     | 0.5%    |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 3         | 3      | 0.5%    |
| Toshiba MK1656GSY 160GB                  | 3         | 3      | 0.5%    |
| Toshiba DT01ACA050 500GB                 | 3         | 4      | 0.5%    |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 0.5%    |
| Seagate ST3500620AS 500GB                | 3         | 4      | 0.5%    |
| Seagate ST2000DM006-2DM164 2TB           | 3         | 3      | 0.5%    |
| Seagate ST1000LM014-SSHD-8GB             | 3         | 4      | 0.5%    |
| SanDisk SSD PLUS 480GB                   | 3         | 3      | 0.5%    |
| Samsung Electronics SSD 840 Series 120GB | 3         | 3      | 0.5%    |
| Kingston SV300S37A120G 120GB SSD         | 3         | 4      | 0.5%    |
| Intel SSDSC2BF180A5L 180GB               | 3         | 3      | 0.5%    |
| Intel SSDPEKKW512G7 512GB                | 3         | 6      | 0.5%    |
| Hitachi HUA723030ALA640 3TB              | 3         | 4      | 0.5%    |
| Hitachi HTS543216L9A300 160GB            | 3         | 3      | 0.5%    |
| Hitachi HDS721010CLA332 1TB              | 3         | 3      | 0.5%    |
| Hitachi HDP725050GLA360 500GB            | 3         | 3      | 0.5%    |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 0.5%    |
| Crucial CT525MX300SSD4 528GB             | 3         | 3      | 0.5%    |
| Crucial CT480M500SSD1 480GB              | 3         | 3      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 174    | 24.48%  |
| WDC                 | 120       | 188    | 20.83%  |
| Hitachi             | 70        | 94     | 12.15%  |
| Samsung Electronics | 51        | 67     | 8.85%   |
| Toshiba             | 38        | 44     | 6.6%    |
| Crucial             | 27        | 33     | 4.69%   |
| Intel               | 18        | 27     | 3.13%   |
| HGST                | 17        | 20     | 2.95%   |
| SanDisk             | 14        | 18     | 2.43%   |
| Kingston            | 11        | 16     | 1.91%   |
| SK hynix            | 7         | 7      | 1.22%   |
| Micron Technology   | 5         | 5      | 0.87%   |
| LITEON              | 5         | 5      | 0.87%   |
| Fujitsu             | 5         | 5      | 0.87%   |
| A-DATA Technology   | 5         | 5      | 0.87%   |
| Maxtor              | 4         | 5      | 0.69%   |
| Drevo               | 4         | 10     | 0.69%   |
| Corsair             | 4         | 8      | 0.69%   |
| OCZ                 | 3         | 3      | 0.52%   |
| Hewlett-Packard     | 3         | 3      | 0.52%   |
| WD MediaMax         | 2         | 2      | 0.35%   |
| Unknown             | 2         | 2      | 0.35%   |
| China               | 2         | 2      | 0.35%   |
| BAITITON            | 2         | 5      | 0.35%   |
| Apple               | 2         | 3      | 0.35%   |
| Zheino              | 1         | 2      | 0.17%   |
| VENO                | 1         | 1      | 0.17%   |
| Team                | 1         | 1      | 0.17%   |
| Netac               | 1         | 1      | 0.17%   |
| Mushkin             | 1         | 1      | 0.17%   |
| LITEONIT            | 1         | 2      | 0.17%   |
| Lexar               | 1         | 1      | 0.17%   |
| KingSpec            | 1         | 1      | 0.17%   |
| faspeed             | 1         | 1      | 0.17%   |
| BIWIN               | 1         | 1      | 0.17%   |
| Apacer              | 1         | 1      | 0.17%   |
| AGI                 | 1         | 1      | 0.17%   |
| 2-Power             | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 141       | 174    | 33.65%  |
| WDC                 | 116       | 184    | 27.68%  |
| Hitachi             | 70        | 94     | 16.71%  |
| Toshiba             | 36        | 42     | 8.59%   |
| Samsung Electronics | 21        | 28     | 5.01%   |
| HGST                | 17        | 20     | 4.06%   |
| Fujitsu             | 5         | 5      | 1.19%   |
| Maxtor              | 4         | 5      | 0.95%   |
| Hewlett-Packard     | 3         | 3      | 0.72%   |
| WD MediaMax         | 2         | 2      | 0.48%   |
| Unknown             | 2         | 2      | 0.48%   |
| Apple               | 2         | 3      | 0.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 379       | 562    | 70.84%  |
| SSD  | 130       | 169    | 24.3%   |
| NVMe | 26        | 36     | 4.86%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB              | 2         | 3      | 18.18%  |
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 9.09%   |
| Toshiba DT01ACA100 1TB                        | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB           | 1         | 1      | 9.09%   |
| Seagate ST3160815AS 160GB                     | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 980 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 960 EVO 250GB         | 1         | 2      | 9.09%   |
| Samsung Electronics HD502IJ 500GB             | 1         | 1      | 9.09%   |
| Hitachi HTS547550A9E384 500GB                 | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba                 | 4         | 5      | 36.36%  |
| Samsung Electronics     | 3         | 4      | 27.27%  |
| Seagate                 | 2         | 2      | 18.18%  |
| Union Memory (Shenzhen) | 1         | 1      | 9.09%   |
| Hitachi                 | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5125      | 11158  | 61.13%  |
| Works    | 2730      | 5430   | 32.56%  |
| Malfunc  | 519       | 767    | 6.19%   |
| Failed   | 10        | 13     | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4832      | 49.16%  |
| AMD                              | 1666      | 16.95%  |
| Samsung Electronics              | 929       | 9.45%   |
| SanDisk                          | 420       | 4.27%   |
| Phison Electronics               | 262       | 2.67%   |
| SK hynix                         | 193       | 1.96%   |
| ASMedia Technology               | 191       | 1.94%   |
| Toshiba America Info Systems     | 157       | 1.6%    |
| Nvidia                           | 156       | 1.59%   |
| Micron/Crucial Technology        | 126       | 1.28%   |
| Marvell Technology Group         | 120       | 1.22%   |
| Kingston Technology Company      | 114       | 1.16%   |
| JMicron Technology               | 90        | 0.92%   |
| KIOXIA                           | 75        | 0.76%   |
| Micron Technology                | 74        | 0.75%   |
| Silicon Motion                   | 72        | 0.73%   |
| ADATA Technology                 | 47        | 0.48%   |
| LSI Logic / Symbios Logic        | 37        | 0.38%   |
| Broadcom / LSI                   | 27        | 0.27%   |
| Seagate Technology               | 26        | 0.26%   |
| VIA Technologies                 | 21        | 0.21%   |
| Apple                            | 21        | 0.21%   |
| Silicon Image                    | 19        | 0.19%   |
| O2 Micro                         | 16        | 0.16%   |
| Hewlett-Packard                  | 16        | 0.16%   |
| Silicon Integrated Systems [SiS] | 15        | 0.15%   |
| Union Memory (Shenzhen)          | 12        | 0.12%   |
| Lenovo                           | 12        | 0.12%   |
| Realtek Semiconductor            | 11        | 0.11%   |
| MAXIO Technology (Hangzhou)      | 11        | 0.11%   |
| Solid State Storage Technology   | 10        | 0.1%    |
| Adaptec                          | 10        | 0.1%    |
| Shenzhen Longsys Electronics     | 8         | 0.08%   |
| Lite-On Technology               | 6         | 0.06%   |
| Yangtze Memory Technologies      | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| INNOGRIT                         | 3         | 0.03%   |
| Solidigm                         | 2         | 0.02%   |
| Netac Technology                 | 2         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1127      | 9.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 465       | 4.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 328       | 2.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 316       | 2.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 298       | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 267       | 2.33%   |
| AMD 400 Series Chipset SATA Controller                                         | 234       | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 191       | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 191       | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 187       | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 183       | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 178       | 1.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 170       | 1.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 161       | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 154       | 1.34%   |
| Samsung NVMe SSD Controller 980                                                | 145       | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 145       | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 142       | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 137       | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 133       | 1.16%   |
| Intel SATA Controller [RAID mode]                                              | 129       | 1.13%   |
| Phison E12 NVMe Controller                                                     | 125       | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 124       | 1.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 122       | 1.06%   |
| AMD 500 Series Chipset SATA Controller                                         | 122       | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 121       | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 120       | 1.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 107       | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 104       | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 100       | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                          | 97        | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 96        | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 91        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 91        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 86        | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 85        | 0.74%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 80        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 79        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 79        | 0.69%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 72        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5493      | 55.57%  |
| NVMe | 2504      | 25.33%  |
| IDE  | 1152      | 11.66%  |
| RAID | 664       | 6.72%   |
| SAS  | 44        | 0.45%   |
| SCSI | 27        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5612      | 72.37%  |
| AMD                   | 2043      | 26.34%  |
| ARM                   | 96        | 1.24%   |
| sifive,u74-mc         | 1         | 0.01%   |
| QUALCOMM              | 1         | 0.01%   |
| Marvell Semiconductor | 1         | 0.01%   |
| CentaurHauls          | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Custom APU 0405                     | 97        | 1.25%   |
| AMD Ryzen 5 3600 6-Core Processor       | 81        | 1.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 73        | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 70        | 0.9%    |
| ARM Processor                           | 67        | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 61        | 0.78%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 55        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 53        | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 52        | 0.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 51        | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 51        | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 51        | 0.66%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 49        | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 48        | 0.62%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 45        | 0.58%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 45        | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 44        | 0.57%   |
| AMD FX-8350 Eight-Core Processor        | 44        | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 43        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 42        | 0.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 42        | 0.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 41        | 0.53%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 40        | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 39        | 0.5%    |
| Intel Celeron CPU N3060 @ 1.60GHz       | 39        | 0.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz       | 38        | 0.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 38        | 0.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 38        | 0.49%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 38        | 0.49%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 37        | 0.48%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 37        | 0.48%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 37        | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 35        | 0.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 34        | 0.44%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 34        | 0.44%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 34        | 0.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 33        | 0.42%   |
| AMD FX-6300 Six-Core Processor          | 33        | 0.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 32        | 0.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 31        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1545      | 19.87%  |
| Intel Core i7           | 1441      | 18.54%  |
| Other                   | 605       | 7.78%   |
| Intel Core i3           | 481       | 6.19%   |
| AMD Ryzen 5             | 423       | 5.44%   |
| Intel Celeron           | 387       | 4.98%   |
| AMD Ryzen 7             | 359       | 4.62%   |
| Intel Core 2 Duo        | 337       | 4.33%   |
| Intel Xeon              | 212       | 2.73%   |
| Intel Pentium           | 193       | 2.48%   |
| AMD Ryzen 9             | 171       | 2.2%    |
| AMD FX                  | 161       | 2.07%   |
| Intel Atom              | 139       | 1.79%   |
| AMD A6                  | 87        | 1.12%   |
| AMD Ryzen 3             | 86        | 1.11%   |
| AMD A8                  | 82        | 1.05%   |
| Intel Pentium Dual-Core | 78        | 1%      |
| Intel Core 2 Quad       | 68        | 0.87%   |
| Intel Core i9           | 60        | 0.77%   |
| AMD A10                 | 57        | 0.73%   |
| Intel Core 2            | 55        | 0.71%   |
| AMD A4                  | 46        | 0.59%   |
| Intel Pentium Dual      | 44        | 0.57%   |
| AMD Athlon II X2        | 41        | 0.53%   |
| AMD Phenom II X4        | 34        | 0.44%   |
| Intel Genuine           | 29        | 0.37%   |
| AMD Ryzen Threadripper  | 29        | 0.37%   |
| ARM BCM                 | 28        | 0.36%   |
| AMD Athlon 64 X2        | 27        | 0.35%   |
| AMD Athlon              | 25        | 0.32%   |
| AMD E1                  | 24        | 0.31%   |
| Intel Pentium 4         | 23        | 0.3%    |
| AMD E                   | 23        | 0.3%    |
| AMD Ryzen 7 PRO         | 22        | 0.28%   |
| Intel Celeron Dual-Core | 20        | 0.26%   |
| Intel Pentium Silver    | 19        | 0.24%   |
| Intel Pentium D         | 17        | 0.22%   |
| AMD Athlon II X4        | 17        | 0.22%   |
| Intel Celeron M         | 14        | 0.18%   |
| AMD Phenom II X6        | 14        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3061      | 39.38%  |
| 4       | 2731      | 35.13%  |
| 6       | 734       | 9.44%   |
| 8       | 599       | 7.71%   |
| 1       | 193       | 2.48%   |
| 12      | 158       | 2.03%   |
| 16      | 96        | 1.24%   |
| 3       | 68        | 0.87%   |
| 10      | 48        | 0.62%   |
| 14      | 41        | 0.53%   |
| 24      | 18        | 0.23%   |
| 32      | 7         | 0.09%   |
| Unknown | 5         | 0.06%   |
| 20      | 3         | 0.04%   |
| 64      | 2         | 0.03%   |
| 40      | 2         | 0.03%   |
| 36      | 2         | 0.03%   |
| 28      | 2         | 0.03%   |
| 44      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7648      | 98.62%  |
| 2       | 97        | 1.25%   |
| Unknown | 5         | 0.06%   |
| 4       | 3         | 0.04%   |
| 3       | 2         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5059      | 65.16%  |
| 1       | 2700      | 34.78%  |
| Unknown | 5         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7522      | 96.66%  |
| Unknown        | 180       | 2.31%   |
| 32-bit         | 75        | 0.96%   |
| 64-bit         | 5         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2306      | 28.54%  |
| 0x306a9    | 382       | 4.73%   |
| 0x206a7    | 375       | 4.64%   |
| 0x306c3    | 318       | 3.94%   |
| 0x1067a    | 271       | 3.35%   |
| 0x906ea    | 166       | 2.05%   |
| 0x806ea    | 148       | 1.83%   |
| 0x506e3    | 146       | 1.81%   |
| 0x08701021 | 141       | 1.75%   |
| 0x806ec    | 135       | 1.67%   |
| 0x806e9    | 135       | 1.67%   |
| 0x406e3    | 134       | 1.66%   |
| 0x40651    | 127       | 1.57%   |
| 0x20655    | 120       | 1.49%   |
| 0x806c1    | 117       | 1.45%   |
| 0x906e9    | 114       | 1.41%   |
| 0x306d4    | 113       | 1.4%    |
| 0x6fd      | 98        | 1.21%   |
| 0x406c4    | 92        | 1.14%   |
| 0x010000c8 | 83        | 1.03%   |
| 0x06000852 | 82        | 1.01%   |
| 0x30678    | 74        | 0.92%   |
| 0x0800820d | 74        | 0.92%   |
| 0x06001119 | 69        | 0.85%   |
| 0x10676    | 67        | 0.83%   |
| 0x08108109 | 64        | 0.79%   |
| 0x08701013 | 56        | 0.69%   |
| 0x506c9    | 55        | 0.68%   |
| 0x6fb      | 53        | 0.66%   |
| 0x0a50000c | 53        | 0.66%   |
| 0xa0652    | 51        | 0.63%   |
| 0x706e5    | 51        | 0.63%   |
| 0x20652    | 49        | 0.61%   |
| 0x06006705 | 47        | 0.58%   |
| 0x906ed    | 45        | 0.56%   |
| 0x406c3    | 45        | 0.56%   |
| 0x08600106 | 43        | 0.53%   |
| 0x08108102 | 42        | 0.52%   |
| 0x706a1    | 40        | 0.5%    |
| 0x206c2    | 37        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1104      | 14.19%  |
| Haswell          | 639       | 8.21%   |
| IvyBridge        | 524       | 6.74%   |
| SandyBridge      | 519       | 6.67%   |
| Penryn           | 413       | 5.31%   |
| Skylake          | 407       | 5.23%   |
| Unknown          | 385       | 4.95%   |
| Zen 2            | 377       | 4.85%   |
| Silvermont       | 279       | 3.59%   |
| Core             | 270       | 3.47%   |
| Westmere         | 260       | 3.34%   |
| Zen+             | 250       | 3.21%   |
| Zen 3            | 232       | 2.98%   |
| Piledriver       | 212       | 2.72%   |
| TigerLake        | 182       | 2.34%   |
| K10              | 181       | 2.33%   |
| Broadwell        | 175       | 2.25%   |
| Zen              | 163       | 2.1%    |
| CometLake        | 142       | 1.83%   |
| Icelake          | 119       | 1.53%   |
| Excavator        | 118       | 1.52%   |
| Alderlake Hybrid | 106       | 1.36%   |
| Goldmont plus    | 101       | 1.3%    |
| Nehalem          | 81        | 1.04%   |
| Goldmont         | 68        | 0.87%   |
| Puma             | 61        | 0.78%   |
| K8 Hammer        | 61        | 0.78%   |
| Steamroller      | 54        | 0.69%   |
| Bobcat           | 49        | 0.63%   |
| Bonnell          | 48        | 0.62%   |
| NetBurst         | 45        | 0.58%   |
| P6               | 40        | 0.51%   |
| Jaguar           | 33        | 0.42%   |
| Bulldozer        | 29        | 0.37%   |
| Tremont          | 20        | 0.26%   |
| K8 & K10 hybrid  | 13        | 0.17%   |
| K10 Llano        | 12        | 0.15%   |
| K6               | 4         | 0.05%   |
| Gracemont        | 4         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4286      | 48.83%  |
| Nvidia                                       | 2395      | 27.29%  |
| AMD                                          | 2010      | 22.9%   |
| Matrox Electronics Systems                   | 41        | 0.47%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.17%   |
| ASPEED Technology                            | 14        | 0.16%   |
| ATI Technologies                             | 8         | 0.09%   |
| VIA Technologies                             | 5         | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| Alliance Semiconductor                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 383       | 4.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 293       | 3.23%   |
| Intel UHD Graphics 620                                                                   | 180       | 1.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 173       | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 171       | 1.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 170       | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 166       | 1.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 163       | 1.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 162       | 1.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 158       | 1.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 156       | 1.72%   |
| Intel HD Graphics 620                                                                    | 147       | 1.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 142       | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 138       | 1.52%   |
| Intel HD Graphics 5500                                                                   | 117       | 1.29%   |
| Intel HD Graphics 630                                                                    | 114       | 1.26%   |
| Intel HD Graphics 530                                                                    | 112       | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 112       | 1.23%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 109       | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 109       | 1.2%    |
| AMD Renoir                                                                               | 105       | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 103       | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 97        | 1.07%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 97        | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 86        | 0.95%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 84        | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 73        | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 72        | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 68        | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 67        | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 64        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 63        | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 61        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 61        | 0.67%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 59        | 0.65%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 58        | 0.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 56        | 0.62%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 56        | 0.62%   |
| Intel HD Graphics 500                                                                    | 54        | 0.59%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 50        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 3310      | 42.26%  |
| 1 x AMD                              | 1701      | 21.72%  |
| 1 x Nvidia                           | 1511      | 19.29%  |
| Intel + Nvidia                       | 740       | 9.45%   |
| Intel + AMD                          | 121       | 1.54%   |
| Other                                | 111       | 1.42%   |
| AMD + Nvidia                         | 96        | 1.23%   |
| 2 x AMD                              | 91        | 1.16%   |
| 1 x Matrox                           | 36        | 0.46%   |
| 2 x Nvidia                           | 34        | 0.43%   |
| 2 x Intel                            | 26        | 0.33%   |
| 1 x SiS                              | 14        | 0.18%   |
| Nvidia + ASPEED                      | 7         | 0.09%   |
| 1 x ASPEED                           | 7         | 0.09%   |
| 1 x VIA                              | 5         | 0.06%   |
| Nvidia + Matrox                      | 4         | 0.05%   |
| Intel + AMD + 1 x Nvidia             | 4         | 0.05%   |
| 2 x AMD + 1 x Nvidia                 | 3         | 0.04%   |
| Intel + 2 x Nvidia                   | 2         | 0.03%   |
| 3 x AMD                              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.01%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.01%   |
| 1 x XGI                              | 1         | 0.01%   |
| 1 x Intel + 3 x Nvidia               | 1         | 0.01%   |
| Intel + 2 x AMD                      | 1         | 0.01%   |
| Intel + AMD + 3 x Nvidia             | 1         | 0.01%   |
| 1 x Huawei Technologies              | 1         | 0.01%   |
| AMD + SiS                            | 1         | 0.01%   |
| AMD + ASPEED                         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6135      | 77.6%   |
| Proprietary | 1380      | 17.46%  |
| Unknown     | 391       | 4.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4598      | 57.28%  |
| 0.01-0.5   | 889       | 11.08%  |
| 1.01-2.0   | 816       | 10.17%  |
| 0.51-1.0   | 520       | 6.48%   |
| 3.01-4.0   | 466       | 5.81%   |
| 7.01-8.0   | 365       | 4.55%   |
| 5.01-6.0   | 175       | 2.18%   |
| 8.01-16.0  | 130       | 1.62%   |
| 2.01-3.0   | 53        | 0.66%   |
| 16.01-24.0 | 11        | 0.14%   |
| 4.01-5.0   | 2         | 0.02%   |
| 24.01-32.0 | 1         | 0.01%   |
| 0          | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 961       | 11.7%   |
| AU Optronics            | 883       | 10.75%  |
| LG Display              | 696       | 8.48%   |
| Dell                    | 574       | 6.99%   |
| Chimei Innolux          | 545       | 6.64%   |
| BOE                     | 525       | 6.39%   |
| Acer                    | 352       | 4.29%   |
| Goldstar                | 280       | 3.41%   |
| Hewlett-Packard         | 268       | 3.26%   |
| BenQ                    | 265       | 3.23%   |
| AOC                     | 257       | 3.13%   |
| Sharp                   | 236       | 2.87%   |
| Apple                   | 190       | 2.31%   |
| Iiyama                  | 180       | 2.19%   |
| Lenovo                  | 161       | 1.96%   |
| Ancor Communications    | 149       | 1.81%   |
| Philips                 | 123       | 1.5%    |
| ViewSonic               | 89        | 1.08%   |
| Chi Mei Optoelectronics | 89        | 1.08%   |
| Sony                    | 86        | 1.05%   |
| ASUSTek Computer        | 75        | 0.91%   |
| Unknown                 | 68        | 0.83%   |
| PANDA                   | 66        | 0.8%    |
| HannStar                | 64        | 0.78%   |
| Panasonic               | 59        | 0.72%   |
| Valve                   | 56        | 0.68%   |
| LG Philips              | 49        | 0.6%    |
| InfoVision              | 49        | 0.6%    |
| Toshiba                 | 47        | 0.57%   |
| Vestel Elektronik       | 46        | 0.56%   |
| LG Electronics          | 43        | 0.52%   |
| MSI                     | 34        | 0.41%   |
| NEC Computers           | 33        | 0.4%    |
| Analogix                | 26        | 0.32%   |
| Gigabyte Technology     | 25        | 0.3%    |
| CSO                     | 22        | 0.27%   |
| Hitachi                 | 20        | 0.24%   |
| OEM                     | 19        | 0.23%   |
| Idek Iiyama             | 17        | 0.21%   |
| CVT                     | 17        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 53        | 0.62%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch   | 45        | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 43        | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 35        | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 33        | 0.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 32        | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 31        | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 29        | 0.34%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 29        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 28        | 0.33%   |
| Analogix ANX7530 U ANX7539 800x1280                                  | 26        | 0.31%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                      | 24        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 22        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 22        | 0.26%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                      | 22        | 0.26%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 21        | 0.25%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                   | 21        | 0.25%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 19        | 0.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 18        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 18        | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 17        | 0.2%    |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch          | 17        | 0.2%    |
| OEM 22_LCD_TV OEM3700 1920x540                                       | 17        | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 17        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 17        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 17        | 0.2%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 17        | 0.2%    |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                    | 17        | 0.2%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 15        | 0.18%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 15        | 0.18%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 15        | 0.18%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch        | 15        | 0.18%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 14        | 0.16%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 14        | 0.16%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 14        | 0.16%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 14        | 0.16%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 14        | 0.16%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch         | 14        | 0.16%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 13        | 0.15%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 13        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3249      | 41.07%  |
| 1366x768 (WXGA)    | 1308      | 16.53%  |
| 3840x2160 (4K)     | 636       | 8.04%   |
| 2560x1440 (QHD)    | 430       | 5.44%   |
| 1280x1024 (SXGA)   | 251       | 3.17%   |
| 1280x800 (WXGA)    | 219       | 2.77%   |
| 1600x900 (HD+)     | 212       | 2.68%   |
| 1920x1200 (WUXGA)  | 196       | 2.48%   |
| 1680x1050 (WSXGA+) | 193       | 2.44%   |
| 1440x900 (WXGA+)   | 188       | 2.38%   |
| Unknown            | 113       | 1.43%   |
| 3440x1440          | 110       | 1.39%   |
| 800x1280           | 76        | 0.96%   |
| 2560x1600          | 67        | 0.85%   |
| 1360x768           | 62        | 0.78%   |
| 2560x1080          | 60        | 0.76%   |
| 3840x1080          | 53        | 0.67%   |
| 1920x540           | 51        | 0.64%   |
| 2880x1800          | 40        | 0.51%   |
| 3840x2400          | 39        | 0.49%   |
| 1024x768 (XGA)     | 32        | 0.4%    |
| 3200x1800 (QHD+)   | 26        | 0.33%   |
| 2736x1824          | 26        | 0.33%   |
| 1600x1200          | 24        | 0.3%    |
| 1024x600           | 22        | 0.28%   |
| 1280x720 (HD)      | 21        | 0.27%   |
| 2160x1440          | 19        | 0.24%   |
| 1920x1280          | 12        | 0.15%   |
| 2288x1287          | 11        | 0.14%   |
| 2256x1504          | 10        | 0.13%   |
| 5120x1440          | 8         | 0.1%    |
| 5760x1080          | 7         | 0.09%   |
| 3840x1200          | 6         | 0.08%   |
| 3456x2160          | 6         | 0.08%   |
| 3072x1920          | 6         | 0.08%   |
| 7680x2160          | 5         | 0.06%   |
| 3840x1600          | 5         | 0.06%   |
| 3200x1080          | 5         | 0.06%   |
| 3000x2000          | 5         | 0.06%   |
| 2880x1920          | 5         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1822      | 22.3%   |
| 13      | 779       | 9.53%   |
| 27      | 666       | 8.15%   |
| 24      | 588       | 7.2%    |
| Unknown | 517       | 6.33%   |
| 23      | 491       | 6.01%   |
| 14      | 475       | 5.81%   |
| 21      | 461       | 5.64%   |
| 17      | 401       | 4.91%   |
| 12      | 238       | 2.91%   |
| 19      | 205       | 2.51%   |
| 31      | 184       | 2.25%   |
| 11      | 128       | 1.57%   |
| 34      | 126       | 1.54%   |
| 84      | 123       | 1.51%   |
| 22      | 117       | 1.43%   |
| 18      | 90        | 1.1%    |
| 20      | 87        | 1.06%   |
| 72      | 66        | 0.81%   |
| 16      | 55        | 0.67%   |
| 7       | 53        | 0.65%   |
| 26      | 50        | 0.61%   |
| 32      | 47        | 0.58%   |
| 10      | 42        | 0.51%   |
| 25      | 40        | 0.49%   |
| 54      | 33        | 0.4%    |
| 3       | 26        | 0.32%   |
| 48      | 21        | 0.26%   |
| 40      | 20        | 0.24%   |
| 28      | 20        | 0.24%   |
| 33      | 19        | 0.23%   |
| 39      | 17        | 0.21%   |
| 65      | 16        | 0.2%    |
| 60      | 12        | 0.15%   |
| 52      | 12        | 0.15%   |
| 46      | 12        | 0.15%   |
| 35      | 12        | 0.15%   |
| 55      | 9         | 0.11%   |
| 142     | 8         | 0.1%    |
| 43      | 8         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2694      | 33.48%  |
| 501-600        | 1628      | 20.23%  |
| 201-300        | 892       | 11.09%  |
| 401-500        | 834       | 10.37%  |
| Unknown        | 517       | 6.43%   |
| 351-400        | 484       | 6.02%   |
| 601-700        | 299       | 3.72%   |
| 701-800        | 198       | 2.46%   |
| 1501-2000      | 191       | 2.37%   |
| 1001-1500      | 145       | 1.8%    |
| 1-100          | 76        | 0.94%   |
| 801-900        | 54        | 0.67%   |
| 901-1000       | 16        | 0.2%    |
| More than 2000 | 10        | 0.12%   |
| 101-200        | 8         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5405      | 72.15%  |
| 16/10   | 940       | 12.55%  |
| Unknown | 450       | 6.01%   |
| 5/4     | 233       | 3.11%   |
| 21/9    | 153       | 2.04%   |
| 3/2     | 108       | 1.44%   |
| 4/3     | 66        | 0.88%   |
| 0.67    | 53        | 0.71%   |
| 6/5     | 39        | 0.52%   |
| 32/9    | 23        | 0.31%   |
| 1.00    | 13        | 0.17%   |
| 3.20    | 2         | 0.03%   |
| 0.62    | 2         | 0.03%   |
| 0.56    | 2         | 0.03%   |
| 3.40    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1815      | 22.44%  |
| 201-250        | 1311      | 16.21%  |
| 81-90          | 851       | 10.52%  |
| 301-350        | 702       | 8.68%   |
| Unknown        | 517       | 6.39%   |
| 151-200        | 445       | 5.5%    |
| 71-80          | 416       | 5.14%   |
| 351-500        | 404       | 5%      |
| More than 1000 | 304       | 3.76%   |
| 121-130        | 238       | 2.94%   |
| 251-300        | 226       | 2.79%   |
| 61-70          | 211       | 2.61%   |
| 141-150        | 169       | 2.09%   |
| 51-60          | 133       | 1.64%   |
| 501-1000       | 100       | 1.24%   |
| 1-40           | 84        | 1.04%   |
| 111-120        | 59        | 0.73%   |
| 131-140        | 50        | 0.62%   |
| 41-50          | 38        | 0.47%   |
| 91-100         | 15        | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2457      | 31.14%  |
| 101-120       | 1938      | 24.56%  |
| 121-160       | 1874      | 23.75%  |
| 161-240       | 612       | 7.76%   |
| Unknown       | 517       | 6.55%   |
| More than 240 | 281       | 3.56%   |
| 1-50          | 211       | 2.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6357      | 79.88%  |
| 2     | 1079      | 13.56%  |
| 0     | 396       | 4.98%   |
| 3     | 114       | 1.43%   |
| 4     | 11        | 0.14%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3860      | 33.5%   |
| Intel                             | 3854      | 33.44%  |
| Qualcomm Atheros                  | 1150      | 9.98%   |
| Broadcom                          | 787       | 6.83%   |
| Ralink Technology                 | 216       | 1.87%   |
| Marvell Technology Group          | 174       | 1.51%   |
| Broadcom Limited                  | 161       | 1.4%    |
| Nvidia                            | 127       | 1.1%    |
| TP-Link                           | 123       | 1.07%   |
| Ralink                            | 118       | 1.02%   |
| MediaTek                          | 116       | 1.01%   |
| ASIX Electronics                  | 55        | 0.48%   |
| Samsung Electronics               | 47        | 0.41%   |
| DisplayLink                       | 43        | 0.37%   |
| Microsoft                         | 41        | 0.36%   |
| Ericsson Business Mobile Networks | 41        | 0.36%   |
| Dell                              | 39        | 0.34%   |
| NetGear                           | 32        | 0.28%   |
| Lenovo                            | 30        | 0.26%   |
| Belkin Components                 | 30        | 0.26%   |
| Qualcomm Atheros Communications   | 29        | 0.25%   |
| Qualcomm                          | 28        | 0.24%   |
| Huawei Technologies               | 28        | 0.24%   |
| Edimax Technology                 | 26        | 0.23%   |
| Aquantia                          | 24        | 0.21%   |
| Hewlett-Packard                   | 19        | 0.16%   |
| Sierra Wireless                   | 17        | 0.15%   |
| ASUSTek Computer                  | 16        | 0.14%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.13%   |
| Microchip Technology              | 14        | 0.12%   |
| JMicron Technology                | 12        | 0.1%    |
| Google                            | 12        | 0.1%    |
| Xiaomi                            | 11        | 0.1%    |
| Mellanox Technologies             | 11        | 0.1%    |
| VIA Technologies                  | 10        | 0.09%   |
| D-Link                            | 10        | 0.09%   |
| Apple                             | 10        | 0.09%   |
| OPPO Electronics                  | 9         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.08%   |
| D-Link System                     | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2497      | 18.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 432       | 3.17%   |
| Intel Wi-Fi 6 AX200                                               | 372       | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 309       | 2.27%   |
| Intel I211 Gigabit Network Connection                             | 253       | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 227       | 1.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 203       | 1.49%   |
| Intel Wireless 7265                                               | 183       | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 180       | 1.32%   |
| Intel Wireless 7260                                               | 178       | 1.31%   |
| Realtek RTL8125 2.5GbE Controller                                 | 167       | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 160       | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 158       | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 150       | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 135       | 0.99%   |
| Intel Wireless 3165                                               | 134       | 0.98%   |
| Intel Wireless 8260                                               | 132       | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 127       | 0.93%   |
| Intel Ethernet Connection (2) I219-V                              | 127       | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 125       | 0.92%   |
| Intel Wi-Fi 6 AX201                                               | 120       | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 114       | 0.84%   |
| Intel Wireless-AC 9260                                            | 99        | 0.73%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 99        | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 93        | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 91        | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 90        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 85        | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 81        | 0.59%   |
| Realtek 802.11ac NIC                                              | 79        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 78        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 77        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                   | 73        | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 72        | 0.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 72        | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                     | 72        | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 71        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 71        | 0.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 70        | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 69        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2811      | 44.18%  |
| Realtek Semiconductor           | 1113      | 17.49%  |
| Qualcomm Atheros                | 932       | 14.65%  |
| Broadcom                        | 501       | 7.87%   |
| Ralink Technology               | 216       | 3.39%   |
| Ralink                          | 117       | 1.84%   |
| TP-Link                         | 116       | 1.82%   |
| Broadcom Limited                | 116       | 1.82%   |
| MediaTek                        | 106       | 1.67%   |
| Microsoft                       | 38        | 0.6%    |
| Marvell Technology Group        | 38        | 0.6%    |
| NetGear                         | 32        | 0.5%    |
| Qualcomm Atheros Communications | 29        | 0.46%   |
| Belkin Components               | 29        | 0.46%   |
| Edimax Technology               | 26        | 0.41%   |
| Dell                            | 22        | 0.35%   |
| Sierra Wireless                 | 17        | 0.27%   |
| Qualcomm                        | 16        | 0.25%   |
| ASUSTek Computer                | 15        | 0.24%   |
| D-Link                          | 10        | 0.16%   |
| D-Link System                   | 7         | 0.11%   |
| Micro Star International        | 6         | 0.09%   |
| IMC Networks                    | 6         | 0.09%   |
| Fibocom                         | 5         | 0.08%   |
| ZyDAS                           | 4         | 0.06%   |
| Linksys                         | 4         | 0.06%   |
| Gemtek                          | 4         | 0.06%   |
| Wacom                           | 3         | 0.05%   |
| TRENDnet                        | 3         | 0.05%   |
| Sitecom Europe                  | 3         | 0.05%   |
| Wilocity                        | 2         | 0.03%   |
| Qualcomm Technologies           | 2         | 0.03%   |
| Philips (or NXP)                | 2         | 0.03%   |
| Hewlett-Packard                 | 2         | 0.03%   |
| Texas Instruments               | 1         | 0.02%   |
| Senao                           | 1         | 0.02%   |
| InProComm                       | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| CyberTAN Technology             | 1         | 0.02%   |
| BUFFALO                         | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 372       | 5.79%   |
| Intel Wireless 8265 / 8275                                              | 227       | 3.54%   |
| Intel Wireless 7265                                                     | 183       | 2.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 180       | 2.8%    |
| Intel Wireless 7260                                                     | 178       | 2.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 160       | 2.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 158       | 2.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 150       | 2.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 135       | 2.1%    |
| Intel Wireless 3165                                                     | 134       | 2.09%   |
| Intel Wireless 8260                                                     | 132       | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 127       | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 125       | 1.95%   |
| Intel Wi-Fi 6 AX201                                                     | 120       | 1.87%   |
| Intel Wireless-AC 9260                                                  | 99        | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 99        | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 93        | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 90        | 1.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 85        | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 81        | 1.26%   |
| Realtek 802.11ac NIC                                                    | 79        | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 78        | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 77        | 1.2%    |
| Ralink MT7601U Wireless Adapter                                         | 73        | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 72        | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                           | 72        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 71        | 1.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 71        | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 70        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 63        | 0.98%   |
| Intel Wireless 3160                                                     | 61        | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 0.95%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 60        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                          | 57        | 0.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 52        | 0.81%   |
| Intel WiFi Link 5100                                                    | 51        | 0.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 49        | 0.76%   |
| Intel Centrino Ultimate-N 6300                                          | 46        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 0.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 43        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3361      | 48.82%  |
| Intel                                  | 2067      | 30.02%  |
| Broadcom                               | 402       | 5.84%   |
| Qualcomm Atheros                       | 323       | 4.69%   |
| Marvell Technology Group               | 136       | 1.98%   |
| Nvidia                                 | 127       | 1.84%   |
| ASIX Electronics                       | 55        | 0.8%    |
| Broadcom Limited                       | 48        | 0.7%    |
| Samsung Electronics                    | 46        | 0.67%   |
| DisplayLink                            | 43        | 0.62%   |
| Lenovo                                 | 27        | 0.39%   |
| Huawei Technologies                    | 24        | 0.35%   |
| Aquantia                               | 24        | 0.35%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.2%    |
| Microchip Technology                   | 13        | 0.19%   |
| Qualcomm                               | 12        | 0.17%   |
| JMicron Technology                     | 12        | 0.17%   |
| Google                                 | 12        | 0.17%   |
| Xiaomi                                 | 11        | 0.16%   |
| VIA Technologies                       | 10        | 0.15%   |
| Mellanox Technologies                  | 10        | 0.15%   |
| OPPO Electronics                       | 9         | 0.13%   |
| MediaTek                               | 9         | 0.13%   |
| OnePlus Technology (Shenzhen)          | 8         | 0.12%   |
| Apple                                  | 8         | 0.12%   |
| TP-Link                                | 7         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 6         | 0.09%   |
| Motorola PCS                           | 6         | 0.09%   |
| ICS Advent                             | 6         | 0.09%   |
| Attansic Technology                    | 5         | 0.07%   |
| T & A Mobile Phones                    | 4         | 0.06%   |
| Standard Microsystems                  | 4         | 0.06%   |
| Hewlett-Packard                        | 4         | 0.06%   |
| Emulex                                 | 4         | 0.06%   |
| Microsoft                              | 3         | 0.04%   |
| HTC (High Tech Computer)               | 3         | 0.04%   |
| 3Com                                   | 3         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| Research In Motion                     | 2         | 0.03%   |
| QLogic                                 | 2         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2497      | 35.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 432       | 6.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 309       | 4.38%   |
| Intel I211 Gigabit Network Connection                             | 253       | 3.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 203       | 2.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 167       | 2.37%   |
| Intel Ethernet Connection (2) I219-V                              | 127       | 1.8%    |
| Intel Ethernet Connection I217-LM                                 | 114       | 1.62%   |
| Intel Ethernet Controller I225-V                                  | 91        | 1.29%   |
| Intel Ethernet Connection (7) I219-V                              | 71        | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 69        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 68        | 0.96%   |
| Intel 82577LM Gigabit Network Connection                          | 68        | 0.96%   |
| Intel Ethernet Connection I218-LM                                 | 64        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 54        | 0.77%   |
| Nvidia MCP61 Ethernet                                             | 52        | 0.74%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 49        | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 48        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 45        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 45        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 45        | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 45        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 45        | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 44        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 43        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.6%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 42        | 0.6%    |
| Intel 82567LM Gigabit Network Connection                          | 41        | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 40        | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 37        | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 37        | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 36        | 0.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 36        | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 36        | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 33        | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 32        | 0.45%   |
| Nvidia MCP79 Ethernet                                             | 30        | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 30        | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 30        | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 29        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6480      | 51.46%  |
| WiFi     | 5955      | 47.29%  |
| Modem    | 140       | 1.11%   |
| Unknown  | 18        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4614      | 57.55%  |
| Ethernet | 3402      | 42.43%  |
| Modem    | 1         | 0.01%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4051      | 51.9%   |
| 1     | 3293      | 42.19%  |
| 0     | 211       | 2.7%    |
| 3     | 178       | 2.28%   |
| 4     | 45        | 0.58%   |
| 5     | 18        | 0.23%   |
| 6     | 8         | 0.1%    |
| 8     | 2         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6809      | 86.43%  |
| Yes  | 1069      | 13.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2200      | 46.82%  |
| Realtek Semiconductor           | 391       | 8.32%   |
| Cambridge Silicon Radio         | 341       | 7.26%   |
| Qualcomm Atheros Communications | 324       | 6.9%    |
| Broadcom                        | 293       | 6.24%   |
| IMC Networks                    | 217       | 4.62%   |
| Apple                           | 211       | 4.49%   |
| Foxconn / Hon Hai               | 130       | 2.77%   |
| Lite-On Technology              | 109       | 2.32%   |
| ASUSTek Computer                | 78        | 1.66%   |
| Dell                            | 77        | 1.64%   |
| Toshiba                         | 58        | 1.23%   |
| Hewlett-Packard                 | 46        | 0.98%   |
| Marvell Semiconductor           | 34        | 0.72%   |
| MediaTek                        | 30        | 0.64%   |
| Realtek                         | 23        | 0.49%   |
| Belkin Components               | 19        | 0.4%    |
| Alps Electric                   | 19        | 0.4%    |
| TP-Link                         | 16        | 0.34%   |
| Foxconn International           | 14        | 0.3%    |
| Integrated System Solution      | 10        | 0.21%   |
| Ralink                          | 9         | 0.19%   |
| Taiyo Yuden                     | 6         | 0.13%   |
| Ralink Technology               | 6         | 0.13%   |
| Askey Computer                  | 6         | 0.13%   |
| USI                             | 5         | 0.11%   |
| Micro Star International        | 5         | 0.11%   |
| Logitech                        | 4         | 0.09%   |
| HTC (High Tech Computer)        | 4         | 0.09%   |
| Edimax Technology               | 3         | 0.06%   |
| Unknown                         | 3         | 0.06%   |
| Sitecom Europe                  | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 867       | 18.44%  |
| Intel AX200 Bluetooth                               | 344       | 7.32%   |
| Intel AX201 Bluetooth                               | 341       | 7.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 341       | 7.25%   |
| Realtek Bluetooth Radio                             | 251       | 5.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 223       | 4.74%   |
| IMC Networks Bluetooth Radio                        | 145       | 3.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 120       | 2.55%   |
| Apple Bluetooth Host Controller                     | 102       | 2.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 89        | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 89        | 1.89%   |
| Intel AX210 Bluetooth                               | 89        | 1.89%   |
| Intel Bluetooth Device                              | 82        | 1.74%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 79        | 1.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 79        | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 75        | 1.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 63        | 1.34%   |
| Foxconn / Hon Hai Bluetooth Device                  | 63        | 1.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 61        | 1.3%    |
| Apple Bluetooth USB Host Controller                 | 52        | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 42        | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                         | 42        | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 0.72%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 32        | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 32        | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 31        | 0.66%   |
| MediaTek Wireless_Device                            | 30        | 0.64%   |
| Marvell Bluetooth and Wireless LAN Composite        | 30        | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 29        | 0.62%   |
| IMC Networks Bluetooth Device                       | 27        | 0.57%   |
| Lite-On Bluetooth Device                            | 26        | 0.55%   |
| IMC Networks Wireless_Device                        | 26        | 0.55%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 24        | 0.51%   |
| Realtek RTL8821A Bluetooth                          | 23        | 0.49%   |
| Realtek Bluetooth Radio                             | 23        | 0.49%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 0.47%   |
| Apple Bluetooth HCI                                 | 22        | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 0.45%   |
| Toshiba Bluetooth Device                            | 19        | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5320      | 49.23%  |
| AMD                                          | 2313      | 21.4%   |
| Nvidia                                       | 1880      | 17.4%   |
| C-Media Electronics                          | 201       | 1.86%   |
| Creative Labs                                | 93        | 0.86%   |
| Logitech                                     | 68        | 0.63%   |
| Texas Instruments                            | 61        | 0.56%   |
| Realtek Semiconductor                        | 43        | 0.4%    |
| JMTek                                        | 39        | 0.36%   |
| Focusrite-Novation                           | 38        | 0.35%   |
| ASUSTek Computer                             | 38        | 0.35%   |
| Razer USA                                    | 37        | 0.34%   |
| Creative Technology                          | 34        | 0.31%   |
| GN Netcom                                    | 33        | 0.31%   |
| SteelSeries ApS                              | 29        | 0.27%   |
| Plantronics                                  | 29        | 0.27%   |
| Micro Star International                     | 27        | 0.25%   |
| VIA Technologies                             | 22        | 0.2%    |
| Corsair                                      | 22        | 0.2%    |
| Kingston Technology                          | 21        | 0.19%   |
| Lenovo                                       | 20        | 0.19%   |
| Blue Microphones                             | 20        | 0.19%   |
| Generalplus Technology                       | 18        | 0.17%   |
| Apple                                        | 16        | 0.15%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.14%   |
| BEHRINGER International                      | 14        | 0.13%   |
| XMOS                                         | 12        | 0.11%   |
| Sennheiser Communications                    | 12        | 0.11%   |
| Thesycon Systemsoftware & Consulting         | 10        | 0.09%   |
| Tenx Technology                              | 10        | 0.09%   |
| Hewlett-Packard                              | 10        | 0.09%   |
| Dell                                         | 10        | 0.09%   |
| AKAI Professional M.I.                       | 10        | 0.09%   |
| ATI Technologies                             | 9         | 0.08%   |
| Sony                                         | 8         | 0.07%   |
| Microsoft                                    | 8         | 0.07%   |
| KTMicro                                      | 8         | 0.07%   |
| GYROCOM C&C                                  | 8         | 0.07%   |
| DSEA A/S                                     | 8         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 7         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 551       | 4.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 522       | 4.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 511       | 3.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 451       | 3.52%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 369       | 2.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 358       | 2.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 307       | 2.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 294       | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 287       | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 261       | 2.04%   |
| AMD FCH Azalia Controller                                                                         | 261       | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 250       | 1.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 242       | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 197       | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 193       | 1.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 187       | 1.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 181       | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 173       | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 172       | 1.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 170       | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 165       | 1.29%   |
| Intel Broadwell-U Audio Controller                                                                | 157       | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 156       | 1.22%   |
| Intel 200 Series PCH HD Audio                                                                     | 155       | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 154       | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 150       | 1.17%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 145       | 1.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 137       | 1.07%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 118       | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 116       | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 116       | 0.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 113       | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 111       | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 108       | 0.84%   |
| Intel Comet Lake PCH cAVS                                                                         | 106       | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 104       | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 100       | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 95        | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 94        | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 88        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 846       | 19.5%   |
| SK hynix            | 775       | 17.87%  |
| Corsair             | 516       | 11.89%  |
| Micron Technology   | 440       | 10.14%  |
| Crucial             | 419       | 9.66%   |
| Unknown             | 394       | 9.08%   |
| Kingston            | 387       | 8.92%   |
| Ramaxel Technology  | 68        | 1.57%   |
| A-DATA Technology   | 62        | 1.43%   |
| Elpida              | 55        | 1.27%   |
| Nanya Technology    | 52        | 1.2%    |
| G.Skill             | 44        | 1.01%   |
| Unknown (ABCD)      | 39        | 0.9%    |
| Team                | 29        | 0.67%   |
| Unknown             | 27        | 0.62%   |
| Patriot             | 20        | 0.46%   |
| Transcend           | 10        | 0.23%   |
| Hewlett-Packard     | 10        | 0.23%   |
| Qimonda             | 9         | 0.21%   |
| ASint Technology    | 8         | 0.18%   |
| A Force             | 8         | 0.18%   |
| Apacer              | 7         | 0.16%   |
| Toshiba             | 6         | 0.14%   |
| Timetec             | 6         | 0.14%   |
| GOODRAM             | 6         | 0.14%   |
| KLEVV               | 4         | 0.09%   |
| GSkill              | 4         | 0.09%   |
| 4ea5                | 4         | 0.09%   |
| Lexar Co Limited    | 3         | 0.07%   |
| Lexar               | 3         | 0.07%   |
| ff                  | 3         | 0.07%   |
| Essencore           | 3         | 0.07%   |
| CSX                 | 3         | 0.07%   |
| Axiom               | 3         | 0.07%   |
| V-Color             | 2         | 0.05%   |
| Unknown (F301)      | 2         | 0.05%   |
| Unknown (0x0702)    | 2         | 0.05%   |
| Unknown (0B38)      | 2         | 0.05%   |
| Thermaltake         | 2         | 0.05%   |
| SHARETRONIC         | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 50        | 1.07%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 43        | 0.92%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 34        | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 30        | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 28        | 0.6%    |
| Unknown                                                          | 27        | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 26        | 0.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 23        | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 22        | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 21        | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 20        | 0.43%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.41%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 18        | 0.39%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 18        | 0.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.36%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 17        | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 16        | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 16        | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.34%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.34%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 16        | 0.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 15        | 0.32%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 0.32%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 15        | 0.32%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 14        | 0.3%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 14        | 0.3%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 14        | 0.3%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 14        | 0.3%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 0.3%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 13        | 0.28%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 13        | 0.28%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 12        | 0.26%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1709      | 45.26%  |
| DDR3    | 1216      | 32.2%   |
| DDR2    | 204       | 5.4%    |
| LPDDR4  | 165       | 4.37%   |
| LPDDR3  | 128       | 3.39%   |
| Unknown | 114       | 3.02%   |
| SDRAM   | 107       | 2.83%   |
| DDR5    | 69        | 1.83%   |
| LPDDR5  | 28        | 0.74%   |
| DDR     | 27        | 0.72%   |
| DRAM    | 9         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1965      | 52.7%   |
| DIMM         | 1412      | 37.87%  |
| Row Of Chips | 293       | 7.86%   |
| Unknown      | 25        | 0.67%   |
| Chip         | 22        | 0.59%   |
| RIMM         | 7         | 0.19%   |
| FB-DIMM      | 5         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1561      | 38.18%  |
| 4096   | 1080      | 26.42%  |
| 16384  | 612       | 14.97%  |
| 2048   | 503       | 12.3%   |
| 1024   | 162       | 3.96%   |
| 32768  | 146       | 3.57%   |
| 512    | 19        | 0.46%   |
| 256    | 2         | 0.05%   |
| 131072 | 1         | 0.02%   |
| 16     | 1         | 0.02%   |
| 13     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 788       | 19.23%  |
| 2667    | 524       | 12.79%  |
| 3200    | 521       | 12.71%  |
| 2400    | 325       | 7.93%   |
| 1333    | 276       | 6.73%   |
| 2133    | 210       | 5.12%   |
| 3600    | 130       | 3.17%   |
| 667     | 115       | 2.81%   |
| 1867    | 104       | 2.54%   |
| 1334    | 96        | 2.34%   |
| 800     | 95        | 2.32%   |
| 4267    | 67        | 1.63%   |
| Unknown | 63        | 1.54%   |
| 1067    | 53        | 1.29%   |
| 4800    | 47        | 1.15%   |
| 3400    | 44        | 1.07%   |
| 3266    | 42        | 1.02%   |
| 3000    | 42        | 1.02%   |
| 1066    | 42        | 1.02%   |
| 3733    | 34        | 0.83%   |
| 6400    | 32        | 0.78%   |
| 1866    | 32        | 0.78%   |
| 2048    | 31        | 0.76%   |
| 1800    | 31        | 0.76%   |
| 2800    | 27        | 0.66%   |
| 4199    | 25        | 0.61%   |
| 2933    | 25        | 0.61%   |
| 3533    | 22        | 0.54%   |
| 2666    | 22        | 0.54%   |
| 533     | 22        | 0.54%   |
| 4266    | 19        | 0.46%   |
| 400     | 16        | 0.39%   |
| 3800    | 14        | 0.34%   |
| 975     | 12        | 0.29%   |
| 3666    | 10        | 0.24%   |
| 6000    | 8         | 0.2%    |
| 49926   | 7         | 0.17%   |
| 1639    | 7         | 0.17%   |
| 8400    | 6         | 0.15%   |
| 3534    | 6         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 75        | 41.44%  |
| Canon                 | 33        | 18.23%  |
| Brother Industries    | 17        | 9.39%   |
| Seiko Epson           | 16        | 8.84%   |
| Samsung Electronics   | 16        | 8.84%   |
| Prolific Technology   | 5         | 2.76%   |
| Lexmark International | 4         | 2.21%   |
| STMicroelectronics    | 2         | 1.1%    |
| QinHeng Electronics   | 2         | 1.1%    |
| Oki Data              | 2         | 1.1%    |
| Kyocera               | 2         | 1.1%    |
| Dymo-CoStar           | 2         | 1.1%    |
| Seiko Instruments     | 1         | 0.55%   |
| Ricoh                 | 1         | 0.55%   |
| Pantum                | 1         | 0.55%   |
| Dell                  | 1         | 0.55%   |
| Apple                 | 1         | 0.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 7         | 3.83%   |
| HP ENVY 4520 series                                       | 6         | 3.28%   |
| Prolific PL2305 Parallel Port                             | 5         | 2.73%   |
| HP ENVY 5000 series                                       | 5         | 2.73%   |
| Canon PIXMA MG2500 Series                                 | 5         | 2.73%   |
| HP DeskJet 2600 series                                    | 4         | 2.19%   |
| Canon PIXMA MG3600 Series                                 | 4         | 2.19%   |
| HP DeskJet 2130 series                                    | 3         | 1.64%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.09%   |
| Seiko Epson XP-240 Series                                 | 2         | 1.09%   |
| Seiko Epson XP-200 Series                                 | 2         | 1.09%   |
| Samsung ML-2250 Series                                    | 2         | 1.09%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.09%   |
| Samsung M2020 Series                                      | 2         | 1.09%   |
| Samsung C43x Series                                       | 2         | 1.09%   |
| QinHeng CH340S                                            | 2         | 1.09%   |
| Oki Data USB Device                                       | 2         | 1.09%   |
| HP LaserJet P2015 series                                  | 2         | 1.09%   |
| HP LaserJet 200 colorMFP M276nw                           | 2         | 1.09%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.09%   |
| HP Deskjet F2280 series                                   | 2         | 1.09%   |
| HP DeskJet 3700 series                                    | 2         | 1.09%   |
| HP DeskJet 3630 series                                    | 2         | 1.09%   |
| HP DeskJet 2700 series                                    | 2         | 1.09%   |
| HP Deskjet 2540 series                                    | 2         | 1.09%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.09%   |
| HP Color LaserJet CP1215                                  | 2         | 1.09%   |
| Canon PIXMA MX920 Series                                  | 2         | 1.09%   |
| Canon PIXMA MP495                                         | 2         | 1.09%   |
| Canon MG5700 series                                       | 2         | 1.09%   |
| Canon LiDE 300                                            | 2         | 1.09%   |
| Canon iP7200 series                                       | 2         | 1.09%   |
| Brother HL-3140CW series                                  | 2         | 1.09%   |
| Brother DCP-7055 scanner/printer                          | 2         | 1.09%   |
| Seiko Instruments SLP-450 Driver                          | 1         | 0.55%   |
| Seiko Epson XP-211 214 216 Series                         | 1         | 0.55%   |
| Seiko Epson WF-3520 Series                                | 1         | 0.55%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.55%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.55%   |
| Seiko Epson L355 Series                                   | 1         | 0.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 28        | 65.12%  |
| Seiko Epson        | 8         | 18.6%   |
| Hewlett-Packard    | 3         | 6.98%   |
| Ultima Electronics | 2         | 4.65%   |
| Mustek Systems     | 1         | 2.33%   |
| AGFA-Gevaert NV    | 1         | 2.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 5         | 11.63%  |
| Canon CanoScan LiDE 220                                                               | 5         | 11.63%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 4         | 9.3%    |
| Canon CanoScan LiDE 200                                                               | 3         | 6.98%   |
| Canon CanoScan LiDE 110                                                               | 3         | 6.98%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 4.65%   |
| Seiko Epson Scanner                                                                   | 2         | 4.65%   |
| HP ScanJet 5300c/5370c                                                                | 2         | 4.65%   |
| Canon CanoScan LiDE 100                                                               | 2         | 4.65%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 1         | 2.33%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.33%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 2.33%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 2.33%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 2.33%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 2.33%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1         | 2.33%   |
| HP Scanjet G2710                                                                      | 1         | 2.33%   |
| Canon CanoScan LiDE 90                                                                | 1         | 2.33%   |
| Canon CanoScan LiDE 70                                                                | 1         | 2.33%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 2.33%   |
| Canon CanoScan LIDE 25                                                                | 1         | 2.33%   |
| Canon CanoScan LiDE 210                                                               | 1         | 2.33%   |
| Canon CanoScan 3000/3000F/3000ex                                                      | 1         | 2.33%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1         | 2.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 943       | 21.21%  |
| Microdia                               | 459       | 10.33%  |
| Realtek Semiconductor                  | 344       | 7.74%   |
| IMC Networks                           | 314       | 7.06%   |
| Logitech                               | 311       | 7%      |
| Sunplus Innovation Technology          | 218       | 4.9%    |
| Bison Electronics                      | 172       | 3.87%   |
| Apple                                  | 172       | 3.87%   |
| Quanta                                 | 148       | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 148       | 3.33%   |
| Suyin                                  | 121       | 2.72%   |
| Lite-On Technology                     | 103       | 2.32%   |
| Acer                                   | 103       | 2.32%   |
| Syntek                                 | 88        | 1.98%   |
| Microsoft                              | 83        | 1.87%   |
| Silicon Motion                         | 66        | 1.48%   |
| Alcor Micro                            | 53        | 1.19%   |
| Samsung Electronics                    | 48        | 1.08%   |
| Ricoh                                  | 46        | 1.03%   |
| Lenovo                                 | 44        | 0.99%   |
| Luxvisions Innotech Limited            | 39        | 0.88%   |
| Z-Star Microelectronics                | 35        | 0.79%   |
| ARC International                      | 30        | 0.67%   |
| Generalplus Technology                 | 27        | 0.61%   |
| GEMBIRD                                | 25        | 0.56%   |
| Sonix Technology                       | 20        | 0.45%   |
| MacroSilicon                           | 17        | 0.38%   |
| Creative Technology                    | 16        | 0.36%   |
| ALi                                    | 16        | 0.36%   |
| SunplusIT                              | 13        | 0.29%   |
| Razer USA                              | 13        | 0.29%   |
| Primax Electronics                     | 11        | 0.25%   |
| Aveo Technology                        | 10        | 0.22%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.2%    |
| Huawei Technologies                    | 9         | 0.2%    |
| Sunplus Technology                     | 8         | 0.18%   |
| OmniVision Technologies                | 8         | 0.18%   |
| Importek                               | 8         | 0.18%   |
| Hewlett-Packard                        | 8         | 0.18%   |
| Tobii Technology AB                    | 7         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 198       | 4.4%    |
| Chicony Integrated Camera                               | 166       | 3.69%   |
| Realtek Integrated_Webcam_HD                            | 115       | 2.56%   |
| Logitech HD Pro Webcam C920                             | 103       | 2.29%   |
| IMC Networks Integrated Camera                          | 92        | 2.05%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 87        | 1.94%   |
| Sunplus Integrated_Webcam_HD                            | 80        | 1.78%   |
| Chicony HD WebCam                                       | 64        | 1.42%   |
| Logitech Webcam C270                                    | 59        | 1.31%   |
| Apple FaceTime HD Camera (Built-in)                     | 54        | 1.2%    |
| Apple Built-in iSight                                   | 50        | 1.11%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 48        | 1.07%   |
| Chicony USB2.0 Camera                                   | 40        | 0.89%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 40        | 0.89%   |
| Microdia Webcam Vitade AF                               | 39        | 0.87%   |
| Chicony TOSHIBA Web Camera - HD                         | 39        | 0.87%   |
| Bison Integrated Camera                                 | 39        | 0.87%   |
| Microdia Integrated Webcam                              | 38        | 0.85%   |
| Syntek Integrated Camera                                | 37        | 0.82%   |
| Lite-On Integrated Camera                               | 37        | 0.82%   |
| Chicony HP TrueVision HD Camera                         | 36        | 0.8%    |
| Realtek USB Camera                                      | 34        | 0.76%   |
| Microsoft LifeCam HD-3000                               | 33        | 0.73%   |
| Chicony USB 2.0 Camera                                  | 33        | 0.73%   |
| Acer BisonCam,NB Pro                                    | 33        | 0.73%   |
| Microdia USB 2.0 Camera                                 | 32        | 0.71%   |
| Chicony HP Truevision HD                                | 32        | 0.71%   |
| Chicony HP HD Camera                                    | 32        | 0.71%   |
| Chicony EasyCamera                                      | 30        | 0.67%   |
| ARC International Camera                                | 30        | 0.67%   |
| Chicony HP Wide Vision HD Camera                        | 28        | 0.62%   |
| Bison SunplusIT Integrated Camera                       | 28        | 0.62%   |
| Syntek Lenovo EasyCamera                                | 26        | 0.58%   |
| Quanta HD User Facing                                   | 26        | 0.58%   |
| Chicony VGA Webcam                                      | 25        | 0.56%   |
| Chicony Integrated Camera (1280x720@30)                 | 25        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 24        | 0.53%   |
| Apple FaceTime HD Camera                                | 24        | 0.53%   |
| Microsoft LifeCam Cinema                                | 23        | 0.51%   |
| Alcor Micro USB 2.0 Web Camera                          | 22        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 234       | 30.95%  |
| Synaptics                          | 207       | 27.38%  |
| Shenzhen Goodix Technology         | 116       | 15.34%  |
| AuthenTec                          | 53        | 7.01%   |
| Upek                               | 52        | 6.88%   |
| LighTuning Technology              | 35        | 4.63%   |
| Elan Microelectronics              | 35        | 4.63%   |
| STMicroelectronics                 | 16        | 2.12%   |
| Samsung Electronics                | 3         | 0.4%    |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.26%   |
| HOLTEK                             | 2         | 0.26%   |
| Focal-systems.Corp                 | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 59        | 7.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 50        | 6.61%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 5.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 42        | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 39        | 5.16%   |
| Synaptics UWP WBDI                                                         | 34        | 4.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 29        | 3.84%   |
| Shenzhen Goodix Fingerprint Reader                                         | 29        | 3.84%   |
| Shenzhen Goodix FingerPrint                                                | 28        | 3.7%    |
| Validity Sensors Synaptics WBDI                                            | 24        | 3.17%   |
| Synaptics  WBDI                                                            | 19        | 2.51%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.38%   |
| Validity Sensors VFS491                                                    | 17        | 2.25%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 16        | 2.12%   |
| STMicroelectronics Fingerprint Reader                                      | 16        | 2.12%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 16        | 2.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 15        | 1.98%   |
| AuthenTec AES2810                                                          | 15        | 1.98%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.72%   |
| Elan ELAN:Fingerprint                                                      | 12        | 1.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 1.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 1.46%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 11        | 1.46%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 10        | 1.32%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.32%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 10        | 1.32%   |
| Elan ELAN:ARM-M4                                                           | 10        | 1.32%   |
| Unknown                                                                    | 10        | 1.32%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.19%   |
| Synaptics WBDI Device                                                      | 8         | 1.06%   |
| Synaptics UWP WBDI Device                                                  | 8         | 1.06%   |
| Synaptics WBDI                                                             | 7         | 0.93%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 0.93%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.93%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 6         | 0.79%   |
| AuthenTec AES1600                                                          | 6         | 0.79%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.66%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.66%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 185       | 51.53%  |
| Alcor Micro               | 81        | 22.56%  |
| Upek                      | 28        | 7.8%    |
| Lenovo                    | 25        | 6.96%   |
| O2 Micro                  | 24        | 6.69%   |
| Gemalto (was Gemplus)     | 4         | 1.11%   |
| SCM Microsystems          | 3         | 0.84%   |
| Yubico.com                | 1         | 0.28%   |
| Purism, SPC               | 1         | 0.28%   |
| OmniKey                   | 1         | 0.28%   |
| Hewlett-Packard           | 1         | 0.28%   |
| Clay Logic                | 1         | 0.28%   |
| Chicony Electronics       | 1         | 0.28%   |
| Cherry                    | 1         | 0.28%   |
| BIT4ID                    | 1         | 0.28%   |
| Aladdin Knowledge Systems | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 76        | 21.17%  |
| Broadcom BCM5880 Secure Applications Processor                               | 71        | 19.78%  |
| Broadcom 5880                                                                | 48        | 13.37%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 34        | 9.47%   |
| Broadcom 58200                                                               | 30        | 8.36%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 7.8%    |
| Lenovo Integrated Smart Card Reader                                          | 23        | 6.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 5.29%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.39%   |
| Alcor Micro Watchdata W 1981                                                 | 5         | 1.39%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.84%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.56%   |
| Lenovo Smartcard Keyboard                                                    | 2         | 0.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.56%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.28%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.28%   |
| Purism, SPC Librem Key                                                       | 1         | 0.28%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.28%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.28%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.28%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.28%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.28%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.28%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.28%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5601      | 70.25%  |
| 1     | 1851      | 23.22%  |
| 2     | 423       | 5.31%   |
| 3     | 71        | 0.89%   |
| 4     | 13        | 0.16%   |
| 5     | 7         | 0.09%   |
| 7     | 3         | 0.04%   |
| 6     | 3         | 0.04%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 737       | 25.59%  |
| Graphics card            | 658       | 22.85%  |
| Net/wireless             | 444       | 15.42%  |
| Chipcard                 | 326       | 11.32%  |
| Multimedia controller    | 182       | 6.32%   |
| Communication controller | 118       | 4.1%    |
| Sound                    | 67        | 2.33%   |
| Unassigned class         | 64        | 2.22%   |
| Camera                   | 61        | 2.12%   |
| Bluetooth                | 56        | 1.94%   |
| Storage                  | 42        | 1.46%   |
| Net/ethernet             | 26        | 0.9%    |
| Card reader              | 24        | 0.83%   |
| Modem                    | 19        | 0.66%   |
| Network                  | 17        | 0.59%   |
| Storage/raid             | 10        | 0.35%   |
| Flash memory             | 8         | 0.28%   |
| Firewire controller      | 6         | 0.21%   |
| Dvb card                 | 6         | 0.21%   |
| Storage/ide              | 5         | 0.17%   |
| Storage/nvme             | 3         | 0.1%    |
| Unclassified device      | 1         | 0.03%   |

