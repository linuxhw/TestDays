Void Linux - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Void Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Void_Linux/Desktop/README.md) and [notebooks](/Dist/Void_Linux/Notebook/README.md).

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

Total: 341

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | P41T-C31                    | Desktop     | [c6bfdbb4ac](https://linux-hardware.org/?probe=c6bfdbb4ac) | Jan 03, 2025 |
| MSI           | Modern 14 C5M               | Notebook    | [e986a9bd5b](https://linux-hardware.org/?probe=e986a9bd5b) | Dec 20, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [34f734e369](https://linux-hardware.org/?probe=34f734e369) | Dec 08, 2024 |
| Acer          | Aspire 7530                 | Notebook    | [d3ba125ebf](https://linux-hardware.org/?probe=d3ba125ebf) | Dec 07, 2024 |
| TUXEDO        | Sirius 16 Gen2              | Notebook    | [354db7d135](https://linux-hardware.org/?probe=354db7d135) | Dec 03, 2024 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [f153085b7c](https://linux-hardware.org/?probe=f153085b7c) | Nov 21, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [cb494ef824](https://linux-hardware.org/?probe=cb494ef824) | Nov 13, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 MFG_... | Notebook    | [9776c3f272](https://linux-hardware.org/?probe=9776c3f272) | Nov 11, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1ff85be360](https://linux-hardware.org/?probe=1ff85be360) | Oct 30, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1c9f70e101](https://linux-hardware.org/?probe=1c9f70e101) | Oct 30, 2024 |
| TECNO Mobi... | MEGABOOK K16SDA             | Notebook    | [70986a82fc](https://linux-hardware.org/?probe=70986a82fc) | Oct 29, 2024 |
| SHENZHEN Y... | LAITNIN G5                  | Notebook    | [48ddc95621](https://linux-hardware.org/?probe=48ddc95621) | Oct 27, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTS... | Notebook    | [a65fd5c1bd](https://linux-hardware.org/?probe=a65fd5c1bd) | Oct 25, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTS... | Notebook    | [18e9247d81](https://linux-hardware.org/?probe=18e9247d81) | Oct 25, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTS... | Notebook    | [64bcd6a568](https://linux-hardware.org/?probe=64bcd6a568) | Oct 25, 2024 |
| ASRock        | B450M/ac                    | Desktop     | [7d8108e45d](https://linux-hardware.org/?probe=7d8108e45d) | Oct 16, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [de44b9af7c](https://linux-hardware.org/?probe=de44b9af7c) | Oct 15, 2024 |
| Dell          | 0RY007 A01                  | Desktop     | [5d0dff2bab](https://linux-hardware.org/?probe=5d0dff2bab) | Oct 13, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [b1e957c653](https://linux-hardware.org/?probe=b1e957c653) | Oct 07, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [e388b60674](https://linux-hardware.org/?probe=e388b60674) | Oct 05, 2024 |
| Acer          | IAXBT-BL                    | All in one  | [59fb4c7892](https://linux-hardware.org/?probe=59fb4c7892) | Oct 04, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JTS... | Notebook    | [1681159aa6](https://linux-hardware.org/?probe=1681159aa6) | Oct 03, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [8b4bc215f3](https://linux-hardware.org/?probe=8b4bc215f3) | Oct 02, 2024 |
| Positivo      | Mobile                      | Notebook    | [aeb1cab172](https://linux-hardware.org/?probe=aeb1cab172) | Sep 27, 2024 |
| Casper        | NIRVANA                     | Notebook    | [7fec4c1d6a](https://linux-hardware.org/?probe=7fec4c1d6a) | Sep 26, 2024 |
| Lenovo        | ThinkPad T450 20BUS0QB01    | Notebook    | [d690a02173](https://linux-hardware.org/?probe=d690a02173) | Sep 08, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [fb2050ff91](https://linux-hardware.org/?probe=fb2050ff91) | Aug 29, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [caf63dfcd4](https://linux-hardware.org/?probe=caf63dfcd4) | Aug 27, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [d011f81b2c](https://linux-hardware.org/?probe=d011f81b2c) | Aug 21, 2024 |
| Dell          | G15 Special Edition 5521    | Notebook    | [f63c3accfa](https://linux-hardware.org/?probe=f63c3accfa) | Aug 10, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f5055fea58](https://linux-hardware.org/?probe=f5055fea58) | Aug 04, 2024 |
| HP            | Pavilion 15                 | Notebook    | [57e8c42dac](https://linux-hardware.org/?probe=57e8c42dac) | Aug 04, 2024 |
| HP            | Pavilion 15                 | Notebook    | [9a6044e07e](https://linux-hardware.org/?probe=9a6044e07e) | Aug 04, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [7aafcbd9f1](https://linux-hardware.org/?probe=7aafcbd9f1) | Jul 20, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [524616cba4](https://linux-hardware.org/?probe=524616cba4) | Jul 16, 2024 |
| HP            | 15                          | Notebook    | [23f73adbdd](https://linux-hardware.org/?probe=23f73adbdd) | Jul 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d7c2d0c8e1](https://linux-hardware.org/?probe=d7c2d0c8e1) | Jul 08, 2024 |
| Gigabyte      | H310M S2H                   | Desktop     | [a61d3c9e57](https://linux-hardware.org/?probe=a61d3c9e57) | Jul 05, 2024 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [d1bb865d34](https://linux-hardware.org/?probe=d1bb865d34) | Jul 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | Notebook    | [640bc2625d](https://linux-hardware.org/?probe=640bc2625d) | Jun 20, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [0bd7cbd871](https://linux-hardware.org/?probe=0bd7cbd871) | Jun 19, 2024 |
| HP            | 0AE4h                       | Desktop     | [3eedb438d5](https://linux-hardware.org/?probe=3eedb438d5) | Jun 19, 2024 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | Notebook    | [dda20727cf](https://linux-hardware.org/?probe=dda20727cf) | Jun 17, 2024 |
| AMI           | Unknown                     | Desktop     | [287abc46ae](https://linux-hardware.org/?probe=287abc46ae) | Jun 11, 2024 |
| HP            | 8594                        | Desktop     | [f06ecd2e7b](https://linux-hardware.org/?probe=f06ecd2e7b) | Jun 08, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7bc9c456ff](https://linux-hardware.org/?probe=7bc9c456ff) | Jun 05, 2024 |
| TUXEDO        | Pulse 14 Gen3               | Notebook    | [0543a1b5a2](https://linux-hardware.org/?probe=0543a1b5a2) | Jun 04, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [606e2f7d8a](https://linux-hardware.org/?probe=606e2f7d8a) | Jun 04, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [c06c68d9b3](https://linux-hardware.org/?probe=c06c68d9b3) | May 29, 2024 |
| Shuttle       | FH170                       | Desktop     | [7d64c3247b](https://linux-hardware.org/?probe=7d64c3247b) | May 29, 2024 |
| Matsushita... | CF-74GCDADBM                | Notebook    | [95822893cd](https://linux-hardware.org/?probe=95822893cd) | May 23, 2024 |
| HP            | 8594                        | Desktop     | [441198408b](https://linux-hardware.org/?probe=441198408b) | May 22, 2024 |
| Matsushita... | CF-74GCDADBM                | Notebook    | [062929e9d9](https://linux-hardware.org/?probe=062929e9d9) | May 14, 2024 |
| Lenovo        | ThinkPad T420 4180D81       | Notebook    | [586b69e749](https://linux-hardware.org/?probe=586b69e749) | Apr 23, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4113f409f3](https://linux-hardware.org/?probe=4113f409f3) | Apr 22, 2024 |
| Lenovo        | ThinkPad T520 42433ZG       | Notebook    | [d2899d8de6](https://linux-hardware.org/?probe=d2899d8de6) | Apr 19, 2024 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [02724e5adf](https://linux-hardware.org/?probe=02724e5adf) | Apr 15, 2024 |
| ASUSTek       | E402MA                      | Notebook    | [58a1e32393](https://linux-hardware.org/?probe=58a1e32393) | Apr 14, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [d6d03b4ad2](https://linux-hardware.org/?probe=d6d03b4ad2) | Apr 14, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [4e18f485f3](https://linux-hardware.org/?probe=4e18f485f3) | Apr 11, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [27c9e47ccc](https://linux-hardware.org/?probe=27c9e47ccc) | Apr 11, 2024 |
| Acer          | E1-510                      | Notebook    | [c53095abd3](https://linux-hardware.org/?probe=c53095abd3) | Apr 10, 2024 |
| Dell          | Latitude 5400               | Notebook    | [20fa0e002d](https://linux-hardware.org/?probe=20fa0e002d) | Mar 23, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [09665b9825](https://linux-hardware.org/?probe=09665b9825) | Mar 21, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [d5c50b0264](https://linux-hardware.org/?probe=d5c50b0264) | Mar 20, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [14b3cedbef](https://linux-hardware.org/?probe=14b3cedbef) | Mar 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [d2152999e9](https://linux-hardware.org/?probe=d2152999e9) | Mar 13, 2024 |
| Gigabyte      | Z97X-UD7 TH-CF              | Desktop     | [3f20fe5386](https://linux-hardware.org/?probe=3f20fe5386) | Mar 13, 2024 |
| ASUSTek       | ROG Maximus Z790 APEX EN... | Desktop     | [b0c33ebfd2](https://linux-hardware.org/?probe=b0c33ebfd2) | Mar 07, 2024 |
| OrangePi      | Zero3                       | Soc         | [a92d36b760](https://linux-hardware.org/?probe=a92d36b760) | Mar 06, 2024 |
| ASUSTek       | ROG Maximus Z790 APEX EN... | Desktop     | [15c45d681f](https://linux-hardware.org/?probe=15c45d681f) | Mar 06, 2024 |
| Lenovo        | ThinkPad T480 20L6S37W04    | Notebook    | [1278612ad9](https://linux-hardware.org/?probe=1278612ad9) | Mar 05, 2024 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [bf1cfeb779](https://linux-hardware.org/?probe=bf1cfeb779) | Mar 05, 2024 |
| Lenovo        | ThinkPad E590 20NB001AUK    | Notebook    | [45eadbd174](https://linux-hardware.org/?probe=45eadbd174) | Mar 03, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [b68f17fbdf](https://linux-hardware.org/?probe=b68f17fbdf) | Mar 02, 2024 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [4dd27fbd4e](https://linux-hardware.org/?probe=4dd27fbd4e) | Feb 23, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7fe3789b7f](https://linux-hardware.org/?probe=7fe3789b7f) | Feb 23, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [99f1228781](https://linux-hardware.org/?probe=99f1228781) | Feb 20, 2024 |
| Dell          | Latitude 7420               | Notebook    | [29ce5896a7](https://linux-hardware.org/?probe=29ce5896a7) | Feb 05, 2024 |
| Dell          | Latitude 7420               | Notebook    | [cdd5031988](https://linux-hardware.org/?probe=cdd5031988) | Feb 04, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bda104dc07](https://linux-hardware.org/?probe=bda104dc07) | Feb 04, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [c35fdb0865](https://linux-hardware.org/?probe=c35fdb0865) | Feb 04, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [3cec123511](https://linux-hardware.org/?probe=3cec123511) | Feb 04, 2024 |
| HP            | 2ADE                        | Desktop     | [c98c83ddde](https://linux-hardware.org/?probe=c98c83ddde) | Jan 29, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [971c919cef](https://linux-hardware.org/?probe=971c919cef) | Jan 20, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [89387d46ef](https://linux-hardware.org/?probe=89387d46ef) | Jan 18, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [c1e2f276ba](https://linux-hardware.org/?probe=c1e2f276ba) | Jan 18, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [78a77e24d1](https://linux-hardware.org/?probe=78a77e24d1) | Jan 14, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [4b6c5e1edb](https://linux-hardware.org/?probe=4b6c5e1edb) | Jan 08, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [cc169dad66](https://linux-hardware.org/?probe=cc169dad66) | Jan 08, 2024 |
| Dell          | 0G919G A00                  | Desktop     | [265aa7e914](https://linux-hardware.org/?probe=265aa7e914) | Jan 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [9eb47b934a](https://linux-hardware.org/?probe=9eb47b934a) | Jan 02, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [7caa5da564](https://linux-hardware.org/?probe=7caa5da564) | Dec 31, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [b063fdc8bf](https://linux-hardware.org/?probe=b063fdc8bf) | Dec 29, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [9662ee22d6](https://linux-hardware.org/?probe=9662ee22d6) | Dec 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [4f6ecdc95a](https://linux-hardware.org/?probe=4f6ecdc95a) | Dec 19, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [cd261e1bc3](https://linux-hardware.org/?probe=cd261e1bc3) | Dec 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [5f97c0d536](https://linux-hardware.org/?probe=5f97c0d536) | Dec 13, 2023 |
| Apple         | Mac-F42787C8 PVT            | All in one  | [e553ac24bf](https://linux-hardware.org/?probe=e553ac24bf) | Dec 10, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [acb5d61dd5](https://linux-hardware.org/?probe=acb5d61dd5) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [980caec27f](https://linux-hardware.org/?probe=980caec27f) | Dec 03, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [c6f9c552b6](https://linux-hardware.org/?probe=c6f9c552b6) | Nov 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f6d20427d3](https://linux-hardware.org/?probe=f6d20427d3) | Nov 26, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [04fce2b1b1](https://linux-hardware.org/?probe=04fce2b1b1) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [70a8dad823](https://linux-hardware.org/?probe=70a8dad823) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7ed36f1817](https://linux-hardware.org/?probe=7ed36f1817) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f2070cd827](https://linux-hardware.org/?probe=f2070cd827) | Nov 18, 2023 |
| Unknown       | T100                        | Desktop     | [298b8f8764](https://linux-hardware.org/?probe=298b8f8764) | Nov 16, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [426fd54105](https://linux-hardware.org/?probe=426fd54105) | Nov 15, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [a9ff569501](https://linux-hardware.org/?probe=a9ff569501) | Nov 14, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5e3d94c299](https://linux-hardware.org/?probe=5e3d94c299) | Nov 07, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [6a8536f5df](https://linux-hardware.org/?probe=6a8536f5df) | Nov 04, 2023 |
| Supermicro    | X11SCA-F                    | Server      | [e63931ed4f](https://linux-hardware.org/?probe=e63931ed4f) | Nov 04, 2023 |
| Google        | Phaser360                   | Notebook    | [9915a1a3be](https://linux-hardware.org/?probe=9915a1a3be) | Nov 03, 2023 |
| Dell          | 0C27VV A03                  | Desktop     | [3e65f94217](https://linux-hardware.org/?probe=3e65f94217) | Oct 28, 2023 |
| Dell          | Latitude D610               | Notebook    | [270c26c018](https://linux-hardware.org/?probe=270c26c018) | Oct 27, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [9faa5f07eb](https://linux-hardware.org/?probe=9faa5f07eb) | Oct 20, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [4bec650d3e](https://linux-hardware.org/?probe=4bec650d3e) | Oct 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [93113727fa](https://linux-hardware.org/?probe=93113727fa) | Oct 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b000ad74e9](https://linux-hardware.org/?probe=b000ad74e9) | Oct 14, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [d96bdeca74](https://linux-hardware.org/?probe=d96bdeca74) | Oct 10, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c63ad78eb4](https://linux-hardware.org/?probe=c63ad78eb4) | Oct 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c074bb832e](https://linux-hardware.org/?probe=c074bb832e) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| Acer          | One S1003                   | Tablet      | [dd8e16ad67](https://linux-hardware.org/?probe=dd8e16ad67) | Sep 25, 2023 |
| Acer          | One S1003                   | Tablet      | [02c8574cb0](https://linux-hardware.org/?probe=02c8574cb0) | Sep 25, 2023 |
| HP            | 15                          | Notebook    | [d0ddd6fbc9](https://linux-hardware.org/?probe=d0ddd6fbc9) | Sep 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [1e60d905c5](https://linux-hardware.org/?probe=1e60d905c5) | Sep 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [2322edb05f](https://linux-hardware.org/?probe=2322edb05f) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [179381f376](https://linux-hardware.org/?probe=179381f376) | Aug 12, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [4f4304a557](https://linux-hardware.org/?probe=4f4304a557) | Aug 06, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [f86b014869](https://linux-hardware.org/?probe=f86b014869) | Aug 06, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [dd0cfabd4b](https://linux-hardware.org/?probe=dd0cfabd4b) | Jul 29, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [14dbf1a55b](https://linux-hardware.org/?probe=14dbf1a55b) | Jul 26, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [de2e3a3ebb](https://linux-hardware.org/?probe=de2e3a3ebb) | Jul 23, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | Desktop     | [08d9fe81da](https://linux-hardware.org/?probe=08d9fe81da) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [00a862ae7c](https://linux-hardware.org/?probe=00a862ae7c) | Jun 14, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [42eab3e3af](https://linux-hardware.org/?probe=42eab3e3af) | Jun 08, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [827f6ecac2](https://linux-hardware.org/?probe=827f6ecac2) | Jun 07, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [45c21cb512](https://linux-hardware.org/?probe=45c21cb512) | May 24, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [f06fd87a32](https://linux-hardware.org/?probe=f06fd87a32) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [cba22e109f](https://linux-hardware.org/?probe=cba22e109f) | Mar 23, 2023 |
| Acer          | E1-510                      | Notebook    | [86abc88022](https://linux-hardware.org/?probe=86abc88022) | Mar 06, 2023 |
| HP            | ENVY m7 Notebook            | Notebook    | [88d1b48b0c](https://linux-hardware.org/?probe=88d1b48b0c) | Feb 26, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d94b8cf0e0](https://linux-hardware.org/?probe=d94b8cf0e0) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d77029e5a0](https://linux-hardware.org/?probe=d77029e5a0) | Feb 13, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| ASUSTek       | Q325UAR                     | Convertible | [b95d2d4e30](https://linux-hardware.org/?probe=b95d2d4e30) | Feb 02, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [43ba50f36c](https://linux-hardware.org/?probe=43ba50f36c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [35024faf2b](https://linux-hardware.org/?probe=35024faf2b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [3c9f8b612c](https://linux-hardware.org/?probe=3c9f8b612c) | Jan 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a551d228f4](https://linux-hardware.org/?probe=a551d228f4) | Jan 14, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [b9ca7fb340](https://linux-hardware.org/?probe=b9ca7fb340) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| MSI           | B550M PRO                   | Desktop     | [61b36bfa2e](https://linux-hardware.org/?probe=61b36bfa2e) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [b30f8a638b](https://linux-hardware.org/?probe=b30f8a638b) | Dec 26, 2022 |
| MSI           | B550M PRO                   | Desktop     | [57f4a4985a](https://linux-hardware.org/?probe=57f4a4985a) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [34882fc8cb](https://linux-hardware.org/?probe=34882fc8cb) | Nov 16, 2022 |
| Toshiba       | Satellite A300D             | Notebook    | [21952b8d66](https://linux-hardware.org/?probe=21952b8d66) | Nov 15, 2022 |
| Lenovo        | Y520-15IKB 80YY             | Notebook    | [626a442179](https://linux-hardware.org/?probe=626a442179) | Nov 06, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [b487c53dfd](https://linux-hardware.org/?probe=b487c53dfd) | Nov 04, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | Notebook    | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | Notebook    | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [001bcba320](https://linux-hardware.org/?probe=001bcba320) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a3485b332a](https://linux-hardware.org/?probe=a3485b332a) | Sep 27, 2022 |
| Unknown       | 1.0                         | Notebook    | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [2f9e03051e](https://linux-hardware.org/?probe=2f9e03051e) | Aug 13, 2022 |
| Exo           | Exomate X352                | Notebook    | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| ASUSTek       | X455LF                      | Notebook    | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [7e7f71a3c0](https://linux-hardware.org/?probe=7e7f71a3c0) | Jul 23, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [761dd08497](https://linux-hardware.org/?probe=761dd08497) | Jul 23, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [53fd2c87d2](https://linux-hardware.org/?probe=53fd2c87d2) | Jul 16, 2022 |
| HP            | 3397                        | Desktop     | [7d3b738672](https://linux-hardware.org/?probe=7d3b738672) | Jul 14, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [fa17eccd81](https://linux-hardware.org/?probe=fa17eccd81) | Jul 04, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6302e38583](https://linux-hardware.org/?probe=6302e38583) | Jun 22, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [ce610351c3](https://linux-hardware.org/?probe=ce610351c3) | Jun 03, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [1e0c1bed2a](https://linux-hardware.org/?probe=1e0c1bed2a) | Jun 02, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [607d5b3c79](https://linux-hardware.org/?probe=607d5b3c79) | May 14, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| MSI           | Z87-G43                     | Desktop     | [d5612db7ca](https://linux-hardware.org/?probe=d5612db7ca) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | Notebook    | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [abc0c5402d](https://linux-hardware.org/?probe=abc0c5402d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [9389a4bd1e](https://linux-hardware.org/?probe=9389a4bd1e) | Apr 29, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6be9414efd](https://linux-hardware.org/?probe=6be9414efd) | Apr 22, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [59b9a2cbcb](https://linux-hardware.org/?probe=59b9a2cbcb) | Apr 11, 2022 |
| MSI           | B550M PRO                   | Desktop     | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| HP            | ENVY 6                      | Notebook    | [988417aaa7](https://linux-hardware.org/?probe=988417aaa7) | Feb 25, 2022 |
| ASUSTek       | Q325UAR                     | Convertible | [fc83e5d0b3](https://linux-hardware.org/?probe=fc83e5d0b3) | Feb 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [28be6b9f17](https://linux-hardware.org/?probe=28be6b9f17) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [5819fc1b20](https://linux-hardware.org/?probe=5819fc1b20) | Feb 14, 2022 |
| Framework     | Laptop                      | Notebook    | [24c119ef46](https://linux-hardware.org/?probe=24c119ef46) | Feb 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [61374a4048](https://linux-hardware.org/?probe=61374a4048) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [24fedcca0a](https://linux-hardware.org/?probe=24fedcca0a) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA34HMN    | Notebook    | [a4dfbb6e38](https://linux-hardware.org/?probe=a4dfbb6e38) | Jan 10, 2022 |
| HP            | Notebook                    | Notebook    | [3b26596e87](https://linux-hardware.org/?probe=3b26596e87) | Jan 10, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [8ff352de01](https://linux-hardware.org/?probe=8ff352de01) | Dec 31, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [ce95acc16d](https://linux-hardware.org/?probe=ce95acc16d) | Nov 24, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [ae9fd68c7d](https://linux-hardware.org/?probe=ae9fd68c7d) | Nov 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1dec2f3df](https://linux-hardware.org/?probe=b1dec2f3df) | Oct 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [093a7d451a](https://linux-hardware.org/?probe=093a7d451a) | Oct 16, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7917f7d57f](https://linux-hardware.org/?probe=7917f7d57f) | Oct 12, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [30d85d7ea1](https://linux-hardware.org/?probe=30d85d7ea1) | Oct 03, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [6ad302377d](https://linux-hardware.org/?probe=6ad302377d) | Sep 30, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9c0d90d6ab](https://linux-hardware.org/?probe=9c0d90d6ab) | Sep 24, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [4cff8ab563](https://linux-hardware.org/?probe=4cff8ab563) | Sep 24, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [efc517d282](https://linux-hardware.org/?probe=efc517d282) | Sep 22, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b4749d300a](https://linux-hardware.org/?probe=b4749d300a) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b9d873983c](https://linux-hardware.org/?probe=b9d873983c) | Sep 17, 2021 |
| Dell          | G3 3579                     | Notebook    | [95182b0267](https://linux-hardware.org/?probe=95182b0267) | Sep 16, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a0d3015e21](https://linux-hardware.org/?probe=a0d3015e21) | Sep 15, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d3c1b5c10c](https://linux-hardware.org/?probe=d3c1b5c10c) | Sep 11, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [feddf87464](https://linux-hardware.org/?probe=feddf87464) | Sep 01, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [bc2b986f06](https://linux-hardware.org/?probe=bc2b986f06) | Aug 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [85d1c86c68](https://linux-hardware.org/?probe=85d1c86c68) | Aug 19, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | Notebook    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [5dec53ee3f](https://linux-hardware.org/?probe=5dec53ee3f) | Jul 26, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [17aab9510b](https://linux-hardware.org/?probe=17aab9510b) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [e1f4843546](https://linux-hardware.org/?probe=e1f4843546) | Jun 16, 2021 |
| ASRock        | J4005B-ITX                  | Desktop     | [053a28a1b7](https://linux-hardware.org/?probe=053a28a1b7) | Jun 13, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e075758bf](https://linux-hardware.org/?probe=8e075758bf) | May 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [59e32967c4](https://linux-hardware.org/?probe=59e32967c4) | May 26, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [32c0e61ea7](https://linux-hardware.org/?probe=32c0e61ea7) | May 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [bf2d71e7f2](https://linux-hardware.org/?probe=bf2d71e7f2) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c96223f666](https://linux-hardware.org/?probe=c96223f666) | Apr 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [42d648695d](https://linux-hardware.org/?probe=42d648695d) | Mar 26, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [b0e56964ae](https://linux-hardware.org/?probe=b0e56964ae) | Mar 15, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [adf7976842](https://linux-hardware.org/?probe=adf7976842) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bdedf5a7c7](https://linux-hardware.org/?probe=bdedf5a7c7) | Feb 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [35af7cfd3d](https://linux-hardware.org/?probe=35af7cfd3d) | Feb 22, 2021 |
| ASUSTek       | X510UAR                     | Notebook    | [1888d46194](https://linux-hardware.org/?probe=1888d46194) | Feb 21, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [09b0e87eec](https://linux-hardware.org/?probe=09b0e87eec) | Feb 12, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [5d02f20d1d](https://linux-hardware.org/?probe=5d02f20d1d) | Feb 10, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | Notebook    | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [66e8ed8402](https://linux-hardware.org/?probe=66e8ed8402) | Jan 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4fcffbd93](https://linux-hardware.org/?probe=d4fcffbd93) | Jan 22, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [624f71f228](https://linux-hardware.org/?probe=624f71f228) | Jan 21, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [73c3fdc605](https://linux-hardware.org/?probe=73c3fdc605) | Jan 16, 2021 |
| ASUSTek       | PRIME Z270-AR               | Desktop     | [35d08fe710](https://linux-hardware.org/?probe=35d08fe710) | Dec 30, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1f66d0eb72](https://linux-hardware.org/?probe=1f66d0eb72) | Dec 22, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [61887011a6](https://linux-hardware.org/?probe=61887011a6) | Dec 22, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [e84677b145](https://linux-hardware.org/?probe=e84677b145) | Dec 20, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| Dell          | Inspiron 11 - 3148          | Notebook    | [f9ec6964bb](https://linux-hardware.org/?probe=f9ec6964bb) | Nov 29, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [d8adc8e3f8](https://linux-hardware.org/?probe=d8adc8e3f8) | Nov 20, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| Acer          | AO722                       | Notebook    | [cee0cf9a99](https://linux-hardware.org/?probe=cee0cf9a99) | Nov 17, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [438477ec85](https://linux-hardware.org/?probe=438477ec85) | Nov 14, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [ac5adde915](https://linux-hardware.org/?probe=ac5adde915) | Nov 13, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d889341667](https://linux-hardware.org/?probe=d889341667) | Oct 28, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e769e1f93a](https://linux-hardware.org/?probe=e769e1f93a) | Oct 24, 2020 |
| HP            | 82C0                        | Mini pc     | [44430304d3](https://linux-hardware.org/?probe=44430304d3) | Oct 19, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b50f7a3624](https://linux-hardware.org/?probe=b50f7a3624) | Oct 07, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Acer          | Aspire A315-55G             | Notebook    | [d24561be9e](https://linux-hardware.org/?probe=d24561be9e) | Oct 01, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [90d57d39e2](https://linux-hardware.org/?probe=90d57d39e2) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [66f15fef73](https://linux-hardware.org/?probe=66f15fef73) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [ee56035e75](https://linux-hardware.org/?probe=ee56035e75) | Sep 24, 2020 |
| Acer          | Nitro AN715-51              | Notebook    | [d375c469b7](https://linux-hardware.org/?probe=d375c469b7) | Sep 16, 2020 |
| Getac         | V110                        | Notebook    | [f0d3292b48](https://linux-hardware.org/?probe=f0d3292b48) | Sep 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | AOA150                      | Notebook    | [f88d38a138](https://linux-hardware.org/?probe=f88d38a138) | Sep 04, 2020 |
| ASUSTek       | P8H67-V                     | Desktop     | [9bc61b31d4](https://linux-hardware.org/?probe=9bc61b31d4) | Sep 02, 2020 |
| Acer          | AO722                       | Notebook    | [816e97376d](https://linux-hardware.org/?probe=816e97376d) | Aug 21, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [efac4b3e2b](https://linux-hardware.org/?probe=efac4b3e2b) | May 25, 2020 |
| Lenovo        | IdeaPad Z570 10246ZG        | Notebook    | [0a0f078e76](https://linux-hardware.org/?probe=0a0f078e76) | Apr 25, 2020 |
| HP            | 15                          | Notebook    | [66422a127b](https://linux-hardware.org/?probe=66422a127b) | Mar 14, 2020 |
| Dell          | Precision 3530              | Notebook    | [dd006a4ce0](https://linux-hardware.org/?probe=dd006a4ce0) | Mar 07, 2020 |
| Dell          | Latitude E4300              | Notebook    | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| Dell          | 0H8052                      | Desktop     | [18169ce984](https://linux-hardware.org/?probe=18169ce984) | Jan 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [b9eb4a5652](https://linux-hardware.org/?probe=b9eb4a5652) | Jan 24, 2020 |
| Unknown       | Unknown                     | Desktop     | [ac87dc43f3](https://linux-hardware.org/?probe=ac87dc43f3) | Jan 24, 2020 |
| ASUSTek       | X555UJ                      | Notebook    | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [faeec47313](https://linux-hardware.org/?probe=faeec47313) | Jan 21, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [ec79f8e0c6](https://linux-hardware.org/?probe=ec79f8e0c6) | Jan 21, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| Dell          | Inspiron 1501               | Notebook    | [17f0e8e41b](https://linux-hardware.org/?probe=17f0e8e41b) | Dec 03, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3bae5ecb46](https://linux-hardware.org/?probe=3bae5ecb46) | Oct 10, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [230c0c9bc6](https://linux-hardware.org/?probe=230c0c9bc6) | Oct 01, 2019 |
| Dell          | Latitude 3379               | Notebook    | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
| ASRock        | AB350M                      | Desktop     | [1ec4015426](https://linux-hardware.org/?probe=1ec4015426) | Sep 01, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [69e86c050b](https://linux-hardware.org/?probe=69e86c050b) | Aug 18, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [ef4f02af88](https://linux-hardware.org/?probe=ef4f02af88) | Aug 16, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [c2458d18f6](https://linux-hardware.org/?probe=c2458d18f6) | Aug 03, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [51273f53df](https://linux-hardware.org/?probe=51273f53df) | Jul 15, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [5ac8c5ff7b](https://linux-hardware.org/?probe=5ac8c5ff7b) | Jun 25, 2019 |
| MSI           | B350M GAMING PRO            | Desktop     | [20e1f5d7a1](https://linux-hardware.org/?probe=20e1f5d7a1) | Apr 17, 2019 |
| Positivo      | Mobile                      | Notebook    | [0267cf3435](https://linux-hardware.org/?probe=0267cf3435) | Mar 27, 2019 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [1b0a4407c7](https://linux-hardware.org/?probe=1b0a4407c7) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 210       | 80.15%  |
| Void Linux         | 52        | 19.85%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 259       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 6.3.13_1  | 11        | 3.89%   |
| 6.3.12_1  | 9         | 3.18%   |
| 5.13.19_1 | 7         | 2.47%   |
| 6.6.52_1  | 5         | 1.77%   |
| 6.6.21_1  | 5         | 1.77%   |
| 6.6.11_1  | 5         | 1.77%   |
| 5.8.18_1  | 5         | 1.77%   |
| 6.6.22_1  | 4         | 1.41%   |
| 6.1.4_1   | 4         | 1.41%   |
| 6.1.31_1  | 4         | 1.41%   |
| 5.3.9_1   | 4         | 1.41%   |
| 5.18.19_1 | 4         | 1.41%   |
| 5.16.20_1 | 4         | 1.41%   |
| 5.10.17_1 | 4         | 1.41%   |
| 6.9.12_1  | 3         | 1.06%   |
| 6.6.8_1   | 3         | 1.06%   |
| 6.6.63_1  | 3         | 1.06%   |
| 6.6.35_1  | 3         | 1.06%   |
| 6.6.31_1  | 3         | 1.06%   |
| 6.5.13_1  | 3         | 1.06%   |
| 6.5.11_1  | 3         | 1.06%   |
| 5.8.12_1  | 3         | 1.06%   |
| 5.19.17_1 | 3         | 1.06%   |
| 5.18.14_1 | 3         | 1.06%   |
| 5.15.32_1 | 3         | 1.06%   |
| 5.13.13_1 | 3         | 1.06%   |
| 5.12.10_1 | 3         | 1.06%   |
| 6.7.6_1   | 2         | 0.71%   |
| 6.6.9_1   | 2         | 0.71%   |
| 6.6.54_1  | 2         | 0.71%   |
| 6.6.48_1  | 2         | 0.71%   |
| 6.6.32_1  | 2         | 0.71%   |
| 6.6.25_1  | 2         | 0.71%   |
| 6.6.1_1   | 2         | 0.71%   |
| 6.6.17_1  | 2         | 0.71%   |
| 6.6.16_1  | 2         | 0.71%   |
| 6.5.9_1   | 2         | 0.71%   |
| 6.5.5_2   | 2         | 0.71%   |
| 6.5.10_1  | 2         | 0.71%   |
| 6.11.5_1  | 2         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.13  | 11        | 3.89%   |
| 6.3.12  | 9         | 3.18%   |
| 5.13.19 | 7         | 2.47%   |
| 6.6.52  | 5         | 1.77%   |
| 6.6.21  | 5         | 1.77%   |
| 6.6.11  | 5         | 1.77%   |
| 5.8.18  | 5         | 1.77%   |
| 6.6.22  | 4         | 1.41%   |
| 6.1.4   | 4         | 1.41%   |
| 6.1.31  | 4         | 1.41%   |
| 5.8.12  | 4         | 1.41%   |
| 5.3.9   | 4         | 1.41%   |
| 5.18.19 | 4         | 1.41%   |
| 5.16.20 | 4         | 1.41%   |
| 5.10.17 | 4         | 1.41%   |
| 6.9.12  | 3         | 1.06%   |
| 6.6.8   | 3         | 1.06%   |
| 6.6.63  | 3         | 1.06%   |
| 6.6.35  | 3         | 1.06%   |
| 6.6.31  | 3         | 1.06%   |
| 6.5.13  | 3         | 1.06%   |
| 6.5.11  | 3         | 1.06%   |
| 5.19.17 | 3         | 1.06%   |
| 5.18.14 | 3         | 1.06%   |
| 5.15.32 | 3         | 1.06%   |
| 5.13.13 | 3         | 1.06%   |
| 5.12.10 | 3         | 1.06%   |
| 6.8.0   | 2         | 0.71%   |
| 6.7.6   | 2         | 0.71%   |
| 6.6.9   | 2         | 0.71%   |
| 6.6.54  | 2         | 0.71%   |
| 6.6.48  | 2         | 0.71%   |
| 6.6.32  | 2         | 0.71%   |
| 6.6.25  | 2         | 0.71%   |
| 6.6.17  | 2         | 0.71%   |
| 6.6.16  | 2         | 0.71%   |
| 6.6.1   | 2         | 0.71%   |
| 6.5.9   | 2         | 0.71%   |
| 6.5.5   | 2         | 0.71%   |
| 6.5.10  | 2         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6     | 51        | 18.41%  |
| 5.15    | 24        | 8.66%   |
| 6.1     | 22        | 7.94%   |
| 6.3     | 20        | 7.22%   |
| 5.8     | 18        | 6.5%    |
| 5.13    | 16        | 5.78%   |
| 6.5     | 15        | 5.42%   |
| 5.10    | 15        | 5.42%   |
| 5.18    | 12        | 4.33%   |
| 5.12    | 9         | 3.25%   |
| 5.4     | 7         | 2.53%   |
| 6.9     | 6         | 2.17%   |
| 6.8     | 6         | 2.17%   |
| 6.0     | 6         | 2.17%   |
| 6.11    | 5         | 1.81%   |
| 5.3     | 5         | 1.81%   |
| 5.19    | 5         | 1.81%   |
| 5.11    | 5         | 1.81%   |
| 6.7     | 4         | 1.44%   |
| 5.9     | 4         | 1.44%   |
| 5.16    | 4         | 1.44%   |
| 4.19    | 4         | 1.44%   |
| 6.2     | 2         | 0.72%   |
| 6.10    | 2         | 0.72%   |
| 6.4     | 1         | 0.36%   |
| 6.12    | 1         | 0.36%   |
| 5.7     | 1         | 0.36%   |
| 5.6     | 1         | 0.36%   |
| 5.2     | 1         | 0.36%   |
| 5.17    | 1         | 0.36%   |
| 5.14    | 1         | 0.36%   |
| 5.1     | 1         | 0.36%   |
| 4.4     | 1         | 0.36%   |
| 4.14    | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 244       | 94.21%  |
| i686    | 7         | 2.7%    |
| aarch64 | 5         | 1.93%   |
| ppc64le | 1         | 0.39%   |
| ppc64   | 1         | 0.39%   |
| armv7l  | 1         | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 107       | 39.78%  |
| XFCE              | 45        | 16.73%  |
| KDE5              | 20        | 7.43%   |
| GNOME             | 17        | 6.32%   |
| KDE               | 15        | 5.58%   |
| sway              | 12        | 4.46%   |
| MATE              | 9         | 3.35%   |
| i3                | 7         | 2.6%    |
| X-Cinnamon        | 6         | 2.23%   |
| KDE6              | 6         | 2.23%   |
| bspwm             | 4         | 1.49%   |
| awesome           | 4         | 1.49%   |
| river             | 3         | 1.12%   |
| openbox           | 3         | 1.12%   |
| X-Generic         | 2         | 0.74%   |
| Lumina            | 2         | 0.74%   |
| LXQt              | 1         | 0.37%   |
| LXDE              | 1         | 0.37%   |
| i3-with-dbus      | 1         | 0.37%   |
| Hyprland          | 1         | 0.37%   |
| dwm               | 1         | 0.37%   |
| dot-xsession      | 1         | 0.37%   |
| awesome-with-dbus | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 167       | 62.78%  |
| Wayland | 50        | 18.8%   |
| Tty     | 28        | 10.53%  |
| Unknown | 21        | 7.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 190       | 71.43%  |
| LightDM | 32        | 12.03%  |
| SDDM    | 25        | 9.4%    |
| GDM     | 9         | 3.38%   |
| LXDM    | 8         | 3.01%   |
| SLiM    | 1         | 0.38%   |
| LDM     | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 139       | 52.06%  |
| Unknown     | 27        | 10.11%  |
| en_GB       | 17        | 6.37%   |
| en_DK       | 8         | 3%      |
| C           | 8         | 3%      |
| ru_RU       | 7         | 2.62%   |
| fr_FR       | 7         | 2.62%   |
| de_DE       | 7         | 2.62%   |
| en_CA       | 6         | 2.25%   |
| pt_BR       | 5         | 1.87%   |
| it_IT       | 5         | 1.87%   |
| pl_PL       | 4         | 1.5%    |
| es_ES       | 4         | 1.5%    |
| en_AU       | 3         | 1.12%   |
| cs_CZ       | 3         | 1.12%   |
| tr_TR       | 2         | 0.75%   |
| el_GR       | 2         | 0.75%   |
| ru_UA       | 1         | 0.37%   |
| pt_PT       | 1         | 0.37%   |
| nb_NO       | 1         | 0.37%   |
| hu_HU       | 1         | 0.37%   |
| es_HN       | 1         | 0.37%   |
| es_DO       | 1         | 0.37%   |
| es_CL       | 1         | 0.37%   |
| es_AR       | 1         | 0.37%   |
| en_US.utf-8 | 1         | 0.37%   |
| en_NZ       | 1         | 0.37%   |
| en_IE       | 1         | 0.37%   |
| ca_ES       | 1         | 0.37%   |
| bg_BG       | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 144       | 54.55%  |
| BIOS | 120       | 45.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 153       | 57.95%  |
| Btrfs   | 66        | 25%     |
| Xfs     | 17        | 6.44%   |
| Zfs     | 11        | 4.17%   |
| Unknown | 7         | 2.65%   |
| Overlay | 5         | 1.89%   |
| F2fs    | 4         | 1.52%   |
| Ext3    | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 156       | 59.09%  |
| Unknown | 75        | 28.41%  |
| MBR     | 33        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 232       | 88.55%  |
| Yes       | 30        | 11.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 202       | 76.81%  |
| Yes       | 61        | 23.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 51        | 19.69%  |
| ASUSTek Computer               | 44        | 16.99%  |
| Hewlett-Packard                | 29        | 11.2%   |
| Dell                           | 21        | 8.11%   |
| Acer                           | 21        | 8.11%   |
| MSI                            | 20        | 7.72%   |
| Gigabyte Technology            | 14        | 5.41%   |
| ASRock                         | 11        | 4.25%   |
| Unknown                        | 7         | 2.7%    |
| Apple                          | 4         | 1.54%   |
| TUXEDO                         | 3         | 1.16%   |
| HUAWEI                         | 3         | 1.16%   |
| Raspberry Pi Foundation        | 2         | 0.77%   |
| Positivo                       | 2         | 0.77%   |
| Notebook                       | 2         | 0.77%   |
| Microsoft                      | 2         | 0.77%   |
| Framework                      | 2         | 0.77%   |
| Toshiba                        | 1         | 0.39%   |
| Timi                           | 1         | 0.39%   |
| TECNO Mobile Limited           | 1         | 0.39%   |
| Supermicro                     | 1         | 0.39%   |
| Shuttle                        | 1         | 0.39%   |
| SHENZHEN YOUDISI E-COMMERCE    | 1         | 0.39%   |
| Samsung Electronics            | 1         | 0.39%   |
| Razer                          | 1         | 0.39%   |
| Pine Microsystems              | 1         | 0.39%   |
| OrangePi                       | 1         | 0.39%   |
| Nokia                          | 1         | 0.39%   |
| Matsushita Electric Industrial | 1         | 0.39%   |
| Google                         | 1         | 0.39%   |
| Getac                          | 1         | 0.39%   |
| Exo                            | 1         | 0.39%   |
| EVGA                           | 1         | 0.39%   |
| Digibras                       | 1         | 0.39%   |
| Cisco Systems                  | 1         | 0.39%   |
| Chuwi                          | 1         | 0.39%   |
| Casper                         | 1         | 0.39%   |
| AMI                            | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 8         | 3.09%   |
| Positivo Mobile                        | 2         | 0.77%   |
| MSI MS-7C02                            | 2         | 0.77%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW  | 2         | 0.77%   |
| HP Pavilion Notebook                   | 2         | 0.77%   |
| HP Pavilion 15                         | 2         | 0.77%   |
| HP Laptop 15-bw0xx                     | 2         | 0.77%   |
| HP 15                                  | 2         | 0.77%   |
| Dell OptiPlex 780                      | 2         | 0.77%   |
| Dell OptiPlex 7010                     | 2         | 0.77%   |
| ASUS X751LD                            | 2         | 0.77%   |
| ASUS PRIME Z390-P                      | 2         | 0.77%   |
| ASRock B450 Pro4                       | 2         | 0.77%   |
| Apple MacBookPro11,1                   | 2         | 0.77%   |
| Acer Swift SF314-42                    | 2         | 0.77%   |
| TUXEDO Sirius 16 Gen2                  | 1         | 0.39%   |
| TUXEDO Pulse 14 Gen3                   | 1         | 0.39%   |
| TUXEDO Aura 15 Gen1                    | 1         | 0.39%   |
| Toshiba Satellite A200                 | 1         | 0.39%   |
| Timi Redmi Book Pro 15 2022            | 1         | 0.39%   |
| TECNO Mobile Limited MEGABOOK K16SDA   | 1         | 0.39%   |
| Supermicro Super Server                | 1         | 0.39%   |
| Shuttle DH170                          | 1         | 0.39%   |
| SHENZHEN YOUDISI E-COMMERCE LAITNIN G5 | 1         | 0.39%   |
| Samsung 275E4E/275E5E                  | 1         | 0.39%   |
| Razer Blade 14 (2022) - RZ09-0427      | 1         | 0.39%   |
| RPi Raspberry Pi Zero 2 W Rev 1.0      | 1         | 0.39%   |
| RPi Raspberry Pi                       | 1         | 0.39%   |
| Pine Microsystems Pine64 Pinebook Pro  | 1         | 0.39%   |
| OrangePi Zero3                         | 1         | 0.39%   |
| Notebook NV4XMB,ME,MZ                  | 1         | 0.39%   |
| Notebook NH50_70RA                     | 1         | 0.39%   |
| Nokia Booklet 3G                       | 1         | 0.39%   |
| MSI Summit E13FlipEvo A12MT            | 1         | 0.39%   |
| MSI Prestige 15 A10SC                  | 1         | 0.39%   |
| MSI MS-7D95                            | 1         | 0.39%   |
| MSI MS-7D14                            | 1         | 0.39%   |
| MSI MS-7C92                            | 1         | 0.39%   |
| MSI MS-7C56                            | 1         | 0.39%   |
| MSI MS-7C52                            | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo ThinkPad                     | 29        | 11.2%   |
| Acer Aspire                         | 14        | 5.41%   |
| Lenovo IdeaPad                      | 10        | 3.86%   |
| ASUS PRIME                          | 10        | 3.86%   |
| ASUS VivoBook                       | 9         | 3.47%   |
| Unknown                             | 8         | 3.09%   |
| HP Pavilion                         | 6         | 2.32%   |
| Dell OptiPlex                       | 6         | 2.32%   |
| Dell Latitude                       | 6         | 2.32%   |
| HP Laptop                           | 5         | 1.93%   |
| Dell Inspiron                       | 5         | 1.93%   |
| Lenovo ThinkBook                    | 4         | 1.54%   |
| HP Stream                           | 3         | 1.16%   |
| ASUS TUF                            | 3         | 1.16%   |
| ASUS ROG                            | 3         | 1.16%   |
| RPi Raspberry                       | 2         | 0.77%   |
| Positivo Mobile                     | 2         | 0.77%   |
| MSI MS-7C02                         | 2         | 0.77%   |
| Microsoft Surface                   | 2         | 0.77%   |
| HP ENVY                             | 2         | 0.77%   |
| HP EliteDesk                        | 2         | 0.77%   |
| HP Compaq                           | 2         | 0.77%   |
| HP 255                              | 2         | 0.77%   |
| HP 15                               | 2         | 0.77%   |
| Gigabyte H310M                      | 2         | 0.77%   |
| Framework Laptop                    | 2         | 0.77%   |
| ASUS X751LD                         | 2         | 0.77%   |
| ASRock B450                         | 2         | 0.77%   |
| Apple MacBookPro11                  | 2         | 0.77%   |
| Acer Swift                          | 2         | 0.77%   |
| TUXEDO Sirius                       | 1         | 0.39%   |
| TUXEDO Pulse                        | 1         | 0.39%   |
| TUXEDO Aura                         | 1         | 0.39%   |
| Toshiba Satellite                   | 1         | 0.39%   |
| Timi Redmi                          | 1         | 0.39%   |
| TECNO Mobile Limited MEGABOOK       | 1         | 0.39%   |
| Supermicro Super                    | 1         | 0.39%   |
| Shuttle DH170                       | 1         | 0.39%   |
| SHENZHEN YOUDISI E-COMMERCE LAITNIN | 1         | 0.39%   |
| Samsung 275E4E                      | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 34        | 13.13%  |
| 2020    | 30        | 11.58%  |
| 2018    | 26        | 10.04%  |
| 2021    | 20        | 7.72%   |
| 2022    | 18        | 6.95%   |
| 2014    | 16        | 6.18%   |
| 2013    | 16        | 6.18%   |
| 2017    | 15        | 5.79%   |
| 2012    | 11        | 4.25%   |
| 2023    | 10        | 3.86%   |
| 2016    | 10        | 3.86%   |
| 2015    | 10        | 3.86%   |
| 2011    | 10        | 3.86%   |
| 2010    | 7         | 2.7%    |
| Unknown | 7         | 2.7%    |
| 2024    | 4         | 1.54%   |
| 2009    | 4         | 1.54%   |
| 2008    | 4         | 1.54%   |
| 2007    | 3         | 1.16%   |
| 2006    | 2         | 0.77%   |
| 2005    | 2         | 0.77%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 156       | 60.23%  |
| Desktop        | 82        | 31.66%  |
| Convertible    | 7         | 2.7%    |
| Tablet         | 4         | 1.54%   |
| System on chip | 3         | 1.16%   |
| All in one     | 3         | 1.16%   |
| Mini pc        | 2         | 0.77%   |
| Server         | 2         | 0.77%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 258       | 99.61%  |
| Enabled  | 1         | 0.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 258       | 99.61%  |
| Yes  | 1         | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 55        | 20.91%  |
| 4.01-8.0        | 54        | 20.53%  |
| 8.01-16.0       | 44        | 16.73%  |
| 3.01-4.0        | 38        | 14.45%  |
| 32.01-64.0      | 33        | 12.55%  |
| 1.01-2.0        | 12        | 4.56%   |
| 24.01-32.0      | 10        | 3.8%    |
| 64.01-256.0     | 8         | 3.04%   |
| 0.51-1.0        | 4         | 1.52%   |
| 2.01-3.0        | 2         | 0.76%   |
| 0.01-0.5        | 2         | 0.76%   |
| More than 256.0 | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 79        | 28.62%  |
| 2.01-3.0    | 60        | 21.74%  |
| 3.01-4.0    | 39        | 14.13%  |
| 4.01-8.0    | 37        | 13.41%  |
| 0.51-1.0    | 27        | 9.78%   |
| 8.01-16.0   | 17        | 6.16%   |
| 0.01-0.5    | 12        | 4.35%   |
| 16.01-24.0  | 3         | 1.09%   |
| 64.01-256.0 | 2         | 0.72%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 163       | 62.45%  |
| 2      | 57        | 21.84%  |
| 3      | 27        | 10.34%  |
| 4      | 8         | 3.07%   |
| 5      | 3         | 1.15%   |
| 9      | 1         | 0.38%   |
| 7      | 1         | 0.38%   |
| 0      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 207       | 79.92%  |
| Yes       | 52        | 20.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 78.46%  |
| No        | 56        | 21.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 75.77%  |
| No        | 63        | 24.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 65.77%  |
| No        | 89        | 34.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 55        | 21.15%  |
| Russia      | 25        | 9.62%   |
| Germany     | 23        | 8.85%   |
| India       | 12        | 4.62%   |
| Brazil      | 12        | 4.62%   |
| UK          | 11        | 4.23%   |
| Poland      | 10        | 3.85%   |
| France      | 9         | 3.46%   |
| Czechia     | 9         | 3.46%   |
| Canada      | 8         | 3.08%   |
| Italy       | 7         | 2.69%   |
| Denmark     | 6         | 2.31%   |
| Turkey      | 5         | 1.92%   |
| Netherlands | 5         | 1.92%   |
| Greece      | 5         | 1.92%   |
| Ukraine     | 4         | 1.54%   |
| Switzerland | 4         | 1.54%   |
| Spain       | 3         | 1.15%   |
| Bulgaria    | 3         | 1.15%   |
| Australia   | 3         | 1.15%   |
| Argentina   | 3         | 1.15%   |
| Vietnam     | 2         | 0.77%   |
| Thailand    | 2         | 0.77%   |
| Serbia      | 2         | 0.77%   |
| Portugal    | 2         | 0.77%   |
| Norway      | 2         | 0.77%   |
| Morocco     | 2         | 0.77%   |
| Indonesia   | 2         | 0.77%   |
| Finland     | 2         | 0.77%   |
| Uruguay     | 1         | 0.38%   |
| Sweden      | 1         | 0.38%   |
| Romania     | 1         | 0.38%   |
| Peru        | 1         | 0.38%   |
| Pakistan    | 1         | 0.38%   |
| Nigeria     | 1         | 0.38%   |
| New Zealand | 1         | 0.38%   |
| Mexico      | 1         | 0.38%   |
| Latvia      | 1         | 0.38%   |
| Jordan      | 1         | 0.38%   |
| Hungary     | 1         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Moscow             | 8         | 2.97%   |
| Prague             | 6         | 2.23%   |
| Vancouver          | 3         | 1.12%   |
| St Petersburg      | 3         | 1.12%   |
| Sao Paulo          | 3         | 1.12%   |
| Orlando            | 3         | 1.12%   |
| Munich             | 3         | 1.12%   |
| Lublin             | 3         | 1.12%   |
| Harrisonburg       | 3         | 1.12%   |
| Denver             | 3         | 1.12%   |
| Bengaluru          | 3         | 1.12%   |
| Amsterdam          | 3         | 1.12%   |
| Warsaw             | 2         | 0.74%   |
| Toulouse           | 2         | 0.74%   |
| Spring Hill        | 2         | 0.74%   |
| Sofia              | 2         | 0.74%   |
| San Antonio        | 2         | 0.74%   |
| Rome               | 2         | 0.74%   |
| Milan              | 2         | 0.74%   |
| Meknes             | 2         | 0.74%   |
| Kenmore            | 2         | 0.74%   |
| Izmir              | 2         | 0.74%   |
| Ioannina           | 2         | 0.74%   |
| Hyderabad          | 2         | 0.74%   |
| Geneva             | 2         | 0.74%   |
| Bangkok            | 2         | 0.74%   |
| Aalborg            | 2         | 0.74%   |
| Zarqa              | 1         | 0.37%   |
| Zagnansk           | 1         | 0.37%   |
| Yekaterinburg      | 1         | 0.37%   |
| Yambol             | 1         | 0.37%   |
| Worthing           | 1         | 0.37%   |
| Winnipeg           | 1         | 0.37%   |
| Wilen bei Wollerau | 1         | 0.37%   |
| Weatherford        | 1         | 0.37%   |
| Volgograd          | 1         | 0.37%   |
| Vlaardingen        | 1         | 0.37%   |
| Vienna             | 1         | 0.37%   |
| Viby J             | 1         | 0.37%   |
| Verkhnyaya Pyshma  | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 72        | 101    | 19.51%  |
| WDC                          | 45        | 59     | 12.2%   |
| Seagate                      | 45        | 58     | 12.2%   |
| SanDisk                      | 27        | 32     | 7.32%   |
| Kingston                     | 22        | 23     | 5.96%   |
| Unknown                      | 20        | 27     | 5.42%   |
| SK hynix                     | 15        | 20     | 4.07%   |
| Intel                        | 14        | 17     | 3.79%   |
| Toshiba                      | 11        | 12     | 2.98%   |
| Crucial                      | 11        | 13     | 2.98%   |
| HGST                         | 9         | 10     | 2.44%   |
| Hitachi                      | 8         | 8      | 2.17%   |
| Phison Electronics           | 5         | 5      | 1.36%   |
| KIOXIA                       | 5         | 5      | 1.36%   |
| Micron Technology            | 4         | 5      | 1.08%   |
| A-DATA Technology            | 4         | 6      | 1.08%   |
| Phison                       | 3         | 3      | 0.81%   |
| Patriot                      | 3         | 3      | 0.81%   |
| Micron/Crucial Technology    | 3         | 3      | 0.81%   |
| Kingston Technology Company  | 3         | 4      | 0.81%   |
| Apple                        | 3         | 3      | 0.81%   |
| SPCC                         | 2         | 2      | 0.54%   |
| Realtek Semiconductor        | 2         | 2      | 0.54%   |
| MAXIO Technology (Hangzhou)  | 2         | 2      | 0.54%   |
| Lenovo                       | 2         | 2      | 0.54%   |
| Corsair                      | 2         | 2      | 0.54%   |
| China                        | 2         | 2      | 0.54%   |
| XrayDisk                     | 1         | 1      | 0.27%   |
| XPG                          | 1         | 4      | 0.27%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.27%   |
| Union Memory                 | 1         | 1      | 0.27%   |
| Transcend                    | 1         | 1      | 0.27%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.27%   |
| Realtek                      | 1         | 1      | 0.27%   |
| PNY                          | 1         | 1      | 0.27%   |
| ORIGIN                       | 1         | 1      | 0.27%   |
| OCZ                          | 1         | 1      | 0.27%   |
| NGFF                         | 1         | 1      | 0.27%   |
| Maxtor                       | 1         | 1      | 0.27%   |
| LITEONIT                     | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 11        | 2.72%   |
| Unknown MMC Card  32GB                               | 8         | 1.98%   |
| Kingston SA400S37240G 240GB SSD                      | 7         | 1.73%   |
| Seagate ST1000LM035-1RK172 1TB                       | 6         | 1.48%   |
| Unknown MMC Card  64GB                               | 5         | 1.23%   |
| Seagate ST2000DM008-2FR102 2TB                       | 5         | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB                       | 5         | 1.23%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 5         | 1.23%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 4         | 0.99%   |
| Samsung SSD 870 EVO 500GB                            | 4         | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 4         | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 3         | 0.74%   |
| Unknown MMC Card  128GB                              | 3         | 0.74%   |
| Toshiba MQ01ABF050 500GB                             | 3         | 0.74%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 3         | 0.74%   |
| Samsung SSD 870 QVO 1TB                              | 3         | 0.74%   |
| Samsung SSD 850 EVO 500GB                            | 3         | 0.74%   |
| Samsung NVMe SSD Drive 1TB                           | 3         | 0.74%   |
| Phison E12 NVMe Controller 480GB                     | 3         | 0.74%   |
| Kingston SHFS37A120G 120GB SSD                       | 3         | 0.74%   |
| HGST HTS545050A7E680 500GB                           | 3         | 0.74%   |
| Crucial CT500MX500SSD1 500GB                         | 3         | 0.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 2         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 2         | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB                         | 2         | 0.49%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 2         | 0.49%   |
| Toshiba MQ04ABF100 1TB                               | 2         | 0.49%   |
| Toshiba DT01ACA050 500GB                             | 2         | 0.49%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB              | 2         | 0.49%   |
| SK hynix SHPP41-2000GM 2TB                           | 2         | 0.49%   |
| Seagate ST500DM002-1BD142 500GB                      | 2         | 0.49%   |
| Seagate ST1000LM049-2GH172 1TB                       | 2         | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 2         | 0.49%   |
| Seagate ST1000DM003-1CH162 1TB                       | 2         | 0.49%   |
| Sandisk WD Blue SN570 1TB                            | 2         | 0.49%   |
| Samsung SSD 980 PRO 500GB                            | 2         | 0.49%   |
| Samsung SSD 980 500GB                                | 2         | 0.49%   |
| Samsung SSD 970 EVO Plus 1TB                         | 2         | 0.49%   |
| Samsung SSD 870 EVO 1TB                              | 2         | 0.49%   |
| Samsung SSD 860 EVO 500GB                            | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 58     | 36%     |
| WDC                 | 38        | 48     | 30.4%   |
| Toshiba             | 10        | 11     | 8%      |
| HGST                | 9         | 10     | 7.2%    |
| Samsung Electronics | 8         | 9      | 6.4%    |
| Hitachi             | 8         | 8      | 6.4%    |
| XrayDisk            | 1         | 1      | 0.8%    |
| Unknown             | 1         | 1      | 0.8%    |
| Maxtor              | 1         | 1      | 0.8%    |
| JMicron Technology  | 1         | 1      | 0.8%    |
| IBM/Hitachi         | 1         | 1      | 0.8%    |
| Fujitsu             | 1         | 1      | 0.8%    |
| Apple               | 1         | 1      | 0.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 31     | 25.47%  |
| Kingston            | 20        | 21     | 18.87%  |
| SanDisk             | 11        | 13     | 10.38%  |
| Crucial             | 9         | 11     | 8.49%   |
| WDC                 | 6         | 7      | 5.66%   |
| Intel               | 4         | 4      | 3.77%   |
| Patriot             | 3         | 3      | 2.83%   |
| A-DATA Technology   | 3         | 5      | 2.83%   |
| SPCC                | 2         | 2      | 1.89%   |
| China               | 2         | 2      | 1.89%   |
| Apple               | 2         | 2      | 1.89%   |
| Transcend           | 1         | 1      | 0.94%   |
| SK hynix            | 1         | 1      | 0.94%   |
| PNY                 | 1         | 1      | 0.94%   |
| ORIGIN              | 1         | 1      | 0.94%   |
| OCZ                 | 1         | 1      | 0.94%   |
| NGFF                | 1         | 1      | 0.94%   |
| LITEONIT            | 1         | 1      | 0.94%   |
| Lenovo              | 1         | 1      | 0.94%   |
| Intenso             | 1         | 1      | 0.94%   |
| INNOVATION IT       | 1         | 1      | 0.94%   |
| HS-SSD-E100         | 1         | 1      | 0.94%   |
| Gigabyte Technology | 1         | 2      | 0.94%   |
| Corsair             | 1         | 1      | 0.94%   |
| BIWIN               | 1         | 1      | 0.94%   |
| BHT                 | 1         | 1      | 0.94%   |
| AMD                 | 1         | 1      | 0.94%   |
| AGI                 | 1         | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 116       | 162    | 34.52%  |
| HDD     | 107       | 151    | 31.85%  |
| SSD     | 92        | 119    | 27.38%  |
| MMC     | 19        | 24     | 5.65%   |
| Unknown | 2         | 3      | 0.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 161       | 262    | 52.61%  |
| NVMe | 116       | 161    | 37.91%  |
| MMC  | 19        | 24     | 6.21%   |
| SAS  | 10        | 12     | 3.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 111       | 147    | 53.62%  |
| 0.51-1.0   | 68        | 83     | 32.85%  |
| 1.01-2.0   | 20        | 27     | 9.66%   |
| 3.01-4.0   | 4         | 9      | 1.93%   |
| 4.01-10.0  | 4         | 4      | 1.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 62        | 23.22%  |
| 101-250        | 54        | 20.22%  |
| 501-1000       | 52        | 19.48%  |
| 1001-2000      | 28        | 10.49%  |
| Unknown        | 16        | 5.99%   |
| 1-20           | 15        | 5.62%   |
| More than 3000 | 14        | 5.24%   |
| 51-100         | 12        | 4.49%   |
| 21-50          | 7         | 2.62%   |
| 2001-3000      | 7         | 2.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 80        | 29.09%  |
| 101-250        | 49        | 17.82%  |
| 21-50          | 40        | 14.55%  |
| 251-500        | 25        | 9.09%   |
| 51-100         | 24        | 8.73%   |
| 501-1000       | 20        | 7.27%   |
| Unknown        | 16        | 5.82%   |
| 1001-2000      | 14        | 5.09%   |
| More than 3000 | 5         | 1.82%   |
| 2001-3000      | 2         | 0.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Computers | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB                       | 2         | 2      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB                           | 2         | 2      | 4.76%   |
| HGST HTS541010A9E680 1TB                                  | 2         | 2      | 4.76%   |
| WDC WD5000AADS-00S9B0 500GB                               | 1         | 2      | 2.38%   |
| WDC WD2003FZEX-00Z4SA0 2TB                                | 1         | 1      | 2.38%   |
| WDC WD1600BEVS-60VAT0 160GB                               | 1         | 1      | 2.38%   |
| WDC WD10EZEX-08WN4A0 1TB                                  | 1         | 1      | 2.38%   |
| Toshiba MQ04ABF100 1TB                                    | 1         | 2      | 2.38%   |
| Toshiba MQ01ABF050 500GB                                  | 1         | 1      | 2.38%   |
| Seagate ST980811AS 80GB                                   | 1         | 1      | 2.38%   |
| Seagate ST9750420AS 752GB                                 | 1         | 1      | 2.38%   |
| Seagate ST9500325AS 500GB                                 | 1         | 1      | 2.38%   |
| Seagate ST500LT012-9WS142 500GB                           | 1         | 1      | 2.38%   |
| Seagate ST4000VN008-2DR166 4TB                            | 1         | 1      | 2.38%   |
| Seagate ST4000VN000-1H4168 4TB                            | 1         | 2      | 2.38%   |
| Seagate ST3750330AS 752GB                                 | 1         | 1      | 2.38%   |
| Seagate ST3250410AS 250GB                                 | 1         | 1      | 2.38%   |
| Seagate ST3160318AS 160GB                                 | 1         | 1      | 2.38%   |
| Seagate ST2000VX000-1CU164 2TB                            | 1         | 2      | 2.38%   |
| Seagate ST2000DM001-1CH164 2TB                            | 1         | 1      | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB                            | 1         | 1      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                        | 1         | 1      | 2.38%   |
| SanDisk SSD U100 256GB                                    | 1         | 1      | 2.38%   |
| SanDisk SSD PLUS 240GB                                    | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 870 EVO 500GB                     | 1         | 1      | 2.38%   |
| Samsung Electronics HM160HI 160GB                         | 1         | 1      | 2.38%   |
| Samsung Electronics HD502HJ 500GB                         | 1         | 1      | 2.38%   |
| Samsung Electronics HD322HJ 320GB                         | 1         | 1      | 2.38%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 256GB | 1         | 1      | 2.38%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB                         | 1         | 1      | 2.38%   |
| Hitachi HUA722010CLA330 1TB                               | 1         | 1      | 2.38%   |
| Hitachi HTS727575A9E364 752GB                             | 1         | 1      | 2.38%   |
| Hitachi HTS545050B9A300 500GB                             | 1         | 1      | 2.38%   |
| Hitachi HTS545050A7E380 500GB                             | 1         | 1      | 2.38%   |
| Hitachi HTS543216L9A300 160GB                             | 1         | 1      | 2.38%   |
| HGST HTS545050A7E680 500GB                                | 1         | 1      | 2.38%   |
| Crucial CT525MX300SSD1 528GB                              | 1         | 1      | 2.38%   |
| Crucial CT256MX100SSD1 256GB                              | 1         | 1      | 2.38%   |
| A-DATA Technology SU700 120GB SSD                         | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 15        | 19     | 37.5%   |
| Hitachi               | 5         | 5      | 12.5%   |
| WDC                   | 4         | 5      | 10%     |
| Samsung Electronics   | 4         | 4      | 10%     |
| HGST                  | 3         | 3      | 7.5%    |
| Toshiba               | 2         | 3      | 5%      |
| SanDisk               | 2         | 2      | 5%      |
| Crucial               | 2         | 2      | 5%      |
| Realtek Semiconductor | 1         | 1      | 2.5%    |
| IBM/Hitachi           | 1         | 1      | 2.5%    |
| A-DATA Technology     | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 19     | 45.45%  |
| Hitachi             | 5         | 5      | 15.15%  |
| WDC                 | 4         | 5      | 12.12%  |
| Samsung Electronics | 3         | 3      | 9.09%   |
| HGST                | 3         | 3      | 9.09%   |
| Toshiba             | 2         | 3      | 6.06%   |
| IBM/Hitachi         | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 39     | 82.05%  |
| SSD  | 6         | 6      | 15.38%  |
| NVMe | 1         | 1      | 2.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intel SSDSC2BW240H6 240GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 150       | 225    | 51.37%  |
| Detected | 105       | 187    | 35.96%  |
| Malfunc  | 36        | 46     | 12.33%  |
| Failed   | 1         | 1      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 133       | 40.8%   |
| AMD                                     | 62        | 19.02%  |
| Samsung Electronics                     | 45        | 13.8%   |
| SanDisk                                 | 18        | 5.52%   |
| SK hynix                                | 14        | 4.29%   |
| Phison Electronics                      | 9         | 2.76%   |
| KIOXIA                                  | 5         | 1.53%   |
| Kingston Technology Company             | 5         | 1.53%   |
| ASMedia Technology                      | 5         | 1.53%   |
| Micron/Crucial Technology               | 4         | 1.23%   |
| Micron Technology                       | 4         | 1.23%   |
| Marvell Technology Group                | 4         | 1.23%   |
| ADATA Technology                        | 3         | 0.92%   |
| Realtek Semiconductor                   | 2         | 0.61%   |
| Nvidia                                  | 2         | 0.61%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.61%   |
| Union Memory (Shenzhen)                 | 1         | 0.31%   |
| Toshiba America Info Systems            | 1         | 0.31%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.31%   |
| Shenzhen Unionmemory Information System | 1         | 0.31%   |
| Shenzhen Longsys Electronics            | 1         | 0.31%   |
| LSI Logic / Symbios Logic               | 1         | 0.31%   |
| Lenovo                                  | 1         | 0.31%   |
| JMicron Technology                      | 1         | 0.31%   |
| Broadcom                                | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 43        | 11.65%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 24        | 6.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 3.79%   |
| AMD 400 Series Chipset SATA Controller                                         | 12        | 3.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 2.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 9         | 2.44%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 8         | 2.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 1.9%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 1.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 1.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.36%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 5         | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.36%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 4         | 1.08%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 1.08%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 4         | 1.08%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.08%   |
| Intel SATA Controller [RAID Mode]                                              | 4         | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.08%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 4         | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 1.08%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3         | 0.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.81%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.81%   |
| Intel SSD 660P Series                                                          | 3         | 0.81%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3         | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.81%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 172       | 52.28%  |
| NVMe | 117       | 35.56%  |
| IDE  | 22        | 6.69%   |
| RAID | 18        | 5.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 161       | 62.16%  |
| AMD                      | 90        | 34.75%  |
| ARM                      | 6         | 2.32%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.39%   |
| PowerMac11,2             | 1         | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor            | 6         | 2.32%   |
| ARM Processor                                 | 5         | 1.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.54%   |
| Intel Core i9-14900K                          | 3         | 1.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.16%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.16%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 1.16%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.16%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.16%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 3         | 1.16%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 1.16%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.77%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.77%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.77%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.77%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 2         | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.77%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 2         | 0.77%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.77%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.77%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.77%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 0.77%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 2         | 0.77%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.77%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 0.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.77%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics    | 2         | 0.77%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.77%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 2         | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.77%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.77%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 0.77%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 16.6%   |
| Intel Core i7           | 33        | 12.74%  |
| Other                   | 31        | 11.97%  |
| AMD Ryzen 7             | 30        | 11.58%  |
| AMD Ryzen 5             | 27        | 10.42%  |
| Intel Core i3           | 19        | 7.34%   |
| Intel Celeron           | 12        | 4.63%   |
| Intel Atom              | 9         | 3.47%   |
| AMD Ryzen 7 PRO         | 6         | 2.32%   |
| Intel Pentium           | 5         | 1.93%   |
| Intel Core 2 Duo        | 5         | 1.93%   |
| Intel Xeon              | 4         | 1.54%   |
| Intel Core i9           | 4         | 1.54%   |
| Intel Genuine           | 3         | 1.16%   |
| AMD Ryzen 9             | 3         | 1.16%   |
| AMD Ryzen 3             | 3         | 1.16%   |
| AMD FX                  | 3         | 1.16%   |
| Intel Core 2 Quad       | 2         | 0.77%   |
| AMD A8                  | 2         | 0.77%   |
| Intel Pentium M         | 1         | 0.39%   |
| Intel Pentium Gold      | 1         | 0.39%   |
| Intel Pentium 4         | 1         | 0.39%   |
| AMD Turion 64 X2 Mobile | 1         | 0.39%   |
| AMD Ryzen Threadripper  | 1         | 0.39%   |
| AMD Ryzen 5 PRO         | 1         | 0.39%   |
| AMD Phenom II X4        | 1         | 0.39%   |
| AMD E2                  | 1         | 0.39%   |
| AMD E1                  | 1         | 0.39%   |
| AMD C-60                | 1         | 0.39%   |
| AMD Athlon X2           | 1         | 0.39%   |
| AMD Athlon II X3        | 1         | 0.39%   |
| AMD Athlon II X2        | 1         | 0.39%   |
| AMD A6                  | 1         | 0.39%   |
| AMD A4                  | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 82        | 31.66%  |
| 2       | 72        | 27.8%   |
| 6       | 39        | 15.06%  |
| 8       | 38        | 14.67%  |
| 1       | 9         | 3.47%   |
| 12      | 6         | 2.32%   |
| 24      | 3         | 1.16%   |
| 14      | 3         | 1.16%   |
| Unknown | 3         | 1.16%   |
| 64      | 1         | 0.39%   |
| 16      | 1         | 0.39%   |
| 10      | 1         | 0.39%   |
| 3       | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 254       | 98.07%  |
| Unknown | 3         | 1.16%   |
| 2       | 2         | 0.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 181       | 69.88%  |
| 1       | 74        | 28.57%  |
| Unknown | 3         | 1.16%   |
| 4       | 1         | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 243       | 93.82%  |
| Unknown        | 8         | 3.09%   |
| 32-bit         | 5         | 1.93%   |
| 64-bit         | 3         | 1.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 139       | 51.87%  |
| 0x40651    | 8         | 2.99%   |
| 0x306a9    | 7         | 2.61%   |
| 0x906e9    | 5         | 1.87%   |
| 0x0a404102 | 5         | 1.87%   |
| 0x906ea    | 4         | 1.49%   |
| 0x806ec    | 4         | 1.49%   |
| 0x806e9    | 4         | 1.49%   |
| 0x406e3    | 4         | 1.49%   |
| 0x08108102 | 4         | 1.49%   |
| 0x806ea    | 3         | 1.12%   |
| 0x30678    | 3         | 1.12%   |
| 0x206a7    | 3         | 1.12%   |
| 0x0a50000c | 3         | 1.12%   |
| 0x08600104 | 3         | 1.12%   |
| 0x06006705 | 3         | 1.12%   |
| 0x906a3    | 2         | 0.75%   |
| 0x506e3    | 2         | 0.75%   |
| 0x106c2    | 2         | 0.75%   |
| 0x0a50000f | 2         | 0.75%   |
| 0x0a50000d | 2         | 0.75%   |
| 0x0a201009 | 2         | 0.75%   |
| 0x08701030 | 2         | 0.75%   |
| 0x08701021 | 2         | 0.75%   |
| 0x08608103 | 2         | 0.75%   |
| 0x08608102 | 2         | 0.75%   |
| 0x08600106 | 2         | 0.75%   |
| 0x0800820d | 2         | 0.75%   |
| 0x07030105 | 2         | 0.75%   |
| 0x06000852 | 2         | 0.75%   |
| 0x05000119 | 2         | 0.75%   |
| 0x010000c8 | 2         | 0.75%   |
| 0xa0671    | 1         | 0.37%   |
| 0xa0652    | 1         | 0.37%   |
| 0x906ed    | 1         | 0.37%   |
| 0x90675    | 1         | 0.37%   |
| 0x90672    | 1         | 0.37%   |
| 0x806eb    | 1         | 0.37%   |
| 0x806c1    | 1         | 0.37%   |
| 0x706e5    | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 44        | 16.99%  |
| Unknown          | 30        | 11.58%  |
| Zen 3            | 23        | 8.88%   |
| Haswell          | 17        | 6.56%   |
| Zen 2            | 15        | 5.79%   |
| IvyBridge        | 12        | 4.63%   |
| Silvermont       | 11        | 4.25%   |
| Zen+             | 10        | 3.86%   |
| Alderlake Hybrid | 10        | 3.86%   |
| Skylake          | 9         | 3.47%   |
| TigerLake        | 7         | 2.7%    |
| SandyBridge      | 7         | 2.7%    |
| Broadwell        | 6         | 2.32%   |
| Zen              | 5         | 1.93%   |
| Penryn           | 5         | 1.93%   |
| IceLake          | 5         | 1.93%   |
| Excavator        | 5         | 1.93%   |
| Core             | 5         | 1.93%   |
| Goldmont plus    | 4         | 1.54%   |
| Bonnell          | 4         | 1.54%   |
| Puma             | 3         | 1.16%   |
| Piledriver       | 3         | 1.16%   |
| K10              | 3         | 1.16%   |
| CometLake        | 3         | 1.16%   |
| P6               | 2         | 0.77%   |
| Nehalem          | 2         | 0.77%   |
| Bobcat           | 2         | 0.77%   |
| Westmere         | 1         | 0.39%   |
| NetBurst         | 1         | 0.39%   |
| K8 Hammer        | 1         | 0.39%   |
| K8 & K10 hybrid  | 1         | 0.39%   |
| Jaguar           | 1         | 0.39%   |
| Gracemont        | 1         | 0.39%   |
| Goldmont         | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 128       | 42.67%  |
| AMD                              | 91        | 30.33%  |
| Nvidia                           | 77        | 25.67%  |
| ASPEED Technology                | 2         | 0.67%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Matrox Electronics Systems       | 1         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.58%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 8         | 2.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 2.26%   |
| Intel UHD Graphics 620                                                                   | 7         | 2.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.26%   |
| AMD Lucienne                                                                             | 7         | 2.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.94%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 1.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.61%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.61%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.29%   |
| Intel HD Graphics 630                                                                    | 4         | 1.29%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.29%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 1.29%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.29%   |
| AMD Barcelo                                                                              | 4         | 1.29%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 0.97%   |
| Intel HD Graphics 620                                                                    | 3         | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.97%   |
| AMD Phoenix1                                                                             | 3         | 0.97%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 3         | 0.97%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 3         | 0.97%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2         | 0.65%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.65%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.65%   |
| Nvidia GM108M [GeForce 830M]                                                             | 2         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 88        | 33.46%  |
| 1 x AMD        | 77        | 29.28%  |
| 1 x Nvidia     | 38        | 14.45%  |
| Intel + Nvidia | 33        | 12.55%  |
| Other          | 8         | 3.04%   |
| AMD + Nvidia   | 5         | 1.9%    |
| 2 x AMD        | 4         | 1.52%   |
| Intel + AMD    | 3         | 1.14%   |
| 2 x Nvidia     | 2         | 0.76%   |
| AMD + ASPEED   | 2         | 0.76%   |
| 2 x Intel      | 1         | 0.38%   |
| 1 x SiS        | 1         | 0.38%   |
| 1 x Matrox     | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 191       | 72.62%  |
| Proprietary | 61        | 23.19%  |
| Unknown     | 11        | 4.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 154       | 57.25%  |
| 0.01-0.5   | 26        | 9.67%   |
| 1.01-2.0   | 22        | 8.18%   |
| 3.01-4.0   | 21        | 7.81%   |
| 7.01-8.0   | 18        | 6.69%   |
| 0.51-1.0   | 13        | 4.83%   |
| 5.01-6.0   | 5         | 1.86%   |
| 8.01-16.0  | 5         | 1.86%   |
| 16.01-24.0 | 3         | 1.12%   |
| 2.01-3.0   | 2         | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 41        | 14.8%   |
| AU Optronics         | 31        | 11.19%  |
| BOE                  | 28        | 10.11%  |
| Samsung Electronics  | 23        | 8.3%    |
| LG Display           | 22        | 7.94%   |
| Dell                 | 12        | 4.33%   |
| Hewlett-Packard      | 11        | 3.97%   |
| Goldstar             | 9         | 3.25%   |
| Philips              | 7         | 2.53%   |
| AOC                  | 7         | 2.53%   |
| Acer                 | 6         | 2.17%   |
| Lenovo               | 5         | 1.81%   |
| Iiyama               | 5         | 1.81%   |
| Apple                | 5         | 1.81%   |
| PANDA                | 4         | 1.44%   |
| LG Philips           | 4         | 1.44%   |
| BenQ                 | 4         | 1.44%   |
| Ancor Communications | 4         | 1.44%   |
| MSI                  | 3         | 1.08%   |
| CSO                  | 3         | 1.08%   |
| ASUSTek Computer     | 3         | 1.08%   |
| Unknown              | 3         | 1.08%   |
| Unknown              | 2         | 0.72%   |
| TMX                  | 2         | 0.72%   |
| Sharp                | 2         | 0.72%   |
| Fujitsu Siemens      | 2         | 0.72%   |
| ___                  | 1         | 0.36%   |
| Vizio                | 1         | 0.36%   |
| ViewSonic            | 1         | 0.36%   |
| Unknown (XXX)        | 1         | 0.36%   |
| Toshiba              | 1         | 0.36%   |
| TMA                  | 1         | 0.36%   |
| STD                  | 1         | 0.36%   |
| Sceptre Tech         | 1         | 0.36%   |
| Sceptre              | 1         | 0.36%   |
| Quanta Display       | 1         | 0.36%   |
| Panasonic            | 1         | 0.36%   |
| ONN                  | 1         | 0.36%   |
| NEC Computers        | 1         | 0.36%   |
| LG Electronics       | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 4         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 3         | 1.05%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 1.05%   |
| Unknown                                                              | 3         | 1.05%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 2         | 0.7%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 2         | 0.7%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.7%    |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch              | 2         | 0.7%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 2         | 0.7%    |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                | 2         | 0.7%    |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                | 2         | 0.7%    |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch         | 2         | 0.7%    |
| Hewlett-Packard 22w HPN342E 1920x1080 476x268mm 21.5-inch            | 2         | 0.7%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch      | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1614 1920x1200 344x215mm 16.0-inch     | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch      | 2         | 0.7%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO4999 1920x1080 344x193mm 15.5-inch       | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 2         | 0.7%    |
| Apple Color LCD APPA020 2560x1600 286x179mm 13.3-inch                | 2         | 0.7%    |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 2         | 0.7%    |
| ___ LCDTV ___0309 1920x1080 700x390mm 31.5-inch                      | 1         | 0.35%   |
| Vizio E320-B2 VIZ0095 1360x768 477x268mm 21.5-inch                   | 1         | 0.35%   |
| ViewSonic LCD Monitor VX2457 1920x1080                               | 1         | 0.35%   |
| Unknown LCDTV 0309 1366x768 410x260mm 19.1-inch                      | 1         | 0.35%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                            | 1         | 0.35%   |
| Unknown (XXX) Beyond TV XXX9615 3840x2160 1210x680mm 54.6-inch       | 1         | 0.35%   |
| Toshiba LCD Monitor LCD0903 1366x768 295x166mm 13.3-inch             | 1         | 0.35%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                | 1         | 0.35%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 1         | 0.35%   |
| TMA TL140ADXP24-0 TMA2004 2880x1800 300x190mm 14.0-inch              | 1         | 0.35%   |
| STD LED STD0001 1920x1080 480x260mm 21.5-inch                        | 1         | 0.35%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch              | 1         | 0.35%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 1         | 0.35%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch        | 1         | 0.35%   |
| Sceptre LCD Monitor E24 1920x1080                                    | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch | 1         | 0.35%   |
| Samsung Electronics SMS22A350H SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 112       | 41.64%  |
| 1366x768 (WXGA)    | 45        | 16.73%  |
| 2560x1440 (QHD)    | 16        | 5.95%   |
| 1920x1200 (WUXGA)  | 16        | 5.95%   |
| 3840x2160 (4K)     | 15        | 5.58%   |
| 1600x900 (HD+)     | 9         | 3.35%   |
| 3440x1440          | 5         | 1.86%   |
| 2560x1600          | 5         | 1.86%   |
| Unknown            | 5         | 1.86%   |
| 2880x1800          | 4         | 1.49%   |
| 1680x1050 (WSXGA+) | 4         | 1.49%   |
| 1280x800 (WXGA)    | 4         | 1.49%   |
| 2560x1080          | 3         | 1.12%   |
| 2160x1440          | 3         | 1.12%   |
| 1440x900 (WXGA+)   | 3         | 1.12%   |
| 1280x1024 (SXGA)   | 3         | 1.12%   |
| 3840x1080          | 2         | 0.74%   |
| 2256x1504          | 2         | 0.74%   |
| 1920x1280          | 2         | 0.74%   |
| 1024x600           | 2         | 0.74%   |
| 7680x1080          | 1         | 0.37%   |
| 7040x1440          | 1         | 0.37%   |
| 3840x1600          | 1         | 0.37%   |
| 3200x2000          | 1         | 0.37%   |
| 2288x1287          | 1         | 0.37%   |
| 1600x1200          | 1         | 0.37%   |
| 1360x768           | 1         | 0.37%   |
| 1280x720 (HD)      | 1         | 0.37%   |
| 1024x768 (XGA)     | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 66        | 24%     |
| 14      | 31        | 11.27%  |
| 13      | 29        | 10.55%  |
| 24      | 23        | 8.36%   |
| Unknown | 19        | 6.91%   |
| 27      | 13        | 4.73%   |
| 23      | 12        | 4.36%   |
| 21      | 12        | 4.36%   |
| 17      | 8         | 2.91%   |
| 16      | 8         | 2.91%   |
| 34      | 6         | 2.18%   |
| 31      | 6         | 2.18%   |
| 22      | 6         | 2.18%   |
| 11      | 6         | 2.18%   |
| 19      | 4         | 1.45%   |
| 12      | 4         | 1.45%   |
| 28      | 3         | 1.09%   |
| 10      | 3         | 1.09%   |
| 32      | 2         | 0.73%   |
| 25      | 2         | 0.73%   |
| 20      | 2         | 0.73%   |
| 84      | 1         | 0.36%   |
| 54      | 1         | 0.36%   |
| 49      | 1         | 0.36%   |
| 48      | 1         | 0.36%   |
| 40      | 1         | 0.36%   |
| 39      | 1         | 0.36%   |
| 37      | 1         | 0.36%   |
| 33      | 1         | 0.36%   |
| 26      | 1         | 0.36%   |
| 8       | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 117       | 43.17%  |
| 501-600     | 46        | 16.97%  |
| 201-300     | 31        | 11.44%  |
| 401-500     | 22        | 8.12%   |
| Unknown     | 19        | 7.01%   |
| 601-700     | 11        | 4.06%   |
| 701-800     | 9         | 3.32%   |
| 351-400     | 8         | 2.95%   |
| 801-900     | 3         | 1.11%   |
| 1001-1500   | 3         | 1.11%   |
| 1501-2000   | 1         | 0.37%   |
| 101-200     | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 174       | 68.5%   |
| 16/10   | 38        | 14.96%  |
| Unknown | 18        | 7.09%   |
| 3/2     | 9         | 3.54%   |
| 21/9    | 9         | 3.54%   |
| 5/4     | 3         | 1.18%   |
| 32/9    | 2         | 0.79%   |
| 4/3     | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 66        | 24.18%  |
| 81-90          | 47        | 17.22%  |
| 201-250        | 40        | 14.65%  |
| Unknown        | 19        | 6.96%   |
| 351-500        | 17        | 6.23%   |
| 301-350        | 14        | 5.13%   |
| 251-300        | 13        | 4.76%   |
| 71-80          | 11        | 4.03%   |
| 111-120        | 8         | 2.93%   |
| 51-60          | 7         | 2.56%   |
| 151-200        | 7         | 2.56%   |
| 501-1000       | 5         | 1.83%   |
| 61-70          | 4         | 1.47%   |
| 131-140        | 3         | 1.1%    |
| 121-130        | 3         | 1.1%    |
| More than 1000 | 2         | 0.73%   |
| 41-50          | 2         | 0.73%   |
| 141-150        | 2         | 0.73%   |
| 91-100         | 2         | 0.73%   |
| 1-40           | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 81        | 29.67%  |
| 51-100        | 75        | 27.47%  |
| 101-120       | 61        | 22.34%  |
| 161-240       | 30        | 10.99%  |
| Unknown       | 19        | 6.96%   |
| More than 240 | 6         | 2.2%    |
| 1-50          | 1         | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 209       | 79.47%  |
| 2     | 44        | 16.73%  |
| 0     | 8         | 3.04%   |
| 3     | 2         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 142       | 38.07%  |
| Intel                            | 111       | 29.76%  |
| Qualcomm Atheros                 | 28        | 7.51%   |
| Broadcom                         | 23        | 6.17%   |
| MediaTek                         | 11        | 2.95%   |
| TP-Link                          | 6         | 1.61%   |
| Broadcom Limited                 | 6         | 1.61%   |
| Ralink Technology                | 5         | 1.34%   |
| Qualcomm                         | 5         | 1.34%   |
| Xiaomi                           | 3         | 0.8%    |
| Sierra Wireless                  | 3         | 0.8%    |
| Marvell Technology Group         | 3         | 0.8%    |
| Aquantia                         | 3         | 0.8%    |
| Ralink                           | 2         | 0.54%   |
| Qualcomm Atheros Communications  | 2         | 0.54%   |
| Huawei Technologies              | 2         | 0.54%   |
| Cypress Semiconductor            | 2         | 0.54%   |
| ASIX Electronics                 | 2         | 0.54%   |
| Tenda                            | 1         | 0.27%   |
| STMicroelectronics               | 1         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Qualcomm Technologies            | 1         | 0.27%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.27%   |
| Nvidia                           | 1         | 0.27%   |
| Microsoft                        | 1         | 0.27%   |
| Microchip Technology             | 1         | 0.27%   |
| Mellanox Technologies            | 1         | 0.27%   |
| JMicron Technology               | 1         | 0.27%   |
| DisplayLink                      | 1         | 0.27%   |
| ASUSTek Computer                 | 1         | 0.27%   |
| Arduino SA                       | 1         | 0.27%   |
| Apple                            | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 89        | 20.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 4.13%   |
| Intel Wi-Fi 6 AX200                                                    | 18        | 4.13%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 2.29%   |
| Intel Wireless 8265 / 8275                                             | 10        | 2.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8         | 1.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 8         | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 1.83%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                          | 7         | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.15%   |
| Intel Wireless 7265                                                    | 5         | 1.15%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 1.15%   |
| Intel Wi-Fi 6 AX201                                                    | 5         | 1.15%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 4         | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 0.92%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 4         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 0.92%   |
| Intel Wireless 8260                                                    | 4         | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.92%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 4         | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 0.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                        | 3         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 0.46%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 2         | 0.46%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2         | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 89        | 43.2%   |
| Realtek Semiconductor           | 42        | 20.39%  |
| Qualcomm Atheros                | 23        | 11.17%  |
| Broadcom                        | 14        | 6.8%    |
| MediaTek                        | 10        | 4.85%   |
| Ralink Technology               | 5         | 2.43%   |
| TP-Link                         | 4         | 1.94%   |
| Qualcomm                        | 4         | 1.94%   |
| Broadcom Limited                | 4         | 1.94%   |
| Sierra Wireless                 | 3         | 1.46%   |
| Ralink                          | 2         | 0.97%   |
| Qualcomm Atheros Communications | 2         | 0.97%   |
| Tenda                           | 1         | 0.49%   |
| Qualcomm Technologies           | 1         | 0.49%   |
| Microsoft                       | 1         | 0.49%   |
| ASUSTek Computer                | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 18        | 8.65%   |
| Intel Wireless 8265 / 8275                                              | 10        | 4.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 4.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 3.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.4%    |
| Intel Wireless 7265                                                     | 5         | 2.4%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 5         | 2.4%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.4%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.92%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 4         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.92%   |
| Intel Wireless 8260                                                     | 4         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.44%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.44%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.44%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 2         | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.96%   |
| Intel Wireless 7260                                                     | 2         | 0.96%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 0.96%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 2         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 123       | 55.91%  |
| Intel                            | 53        | 24.09%  |
| Broadcom                         | 11        | 5%      |
| Qualcomm Atheros                 | 6         | 2.73%   |
| Xiaomi                           | 3         | 1.36%   |
| Marvell Technology Group         | 3         | 1.36%   |
| Aquantia                         | 3         | 1.36%   |
| TP-Link                          | 2         | 0.91%   |
| Cypress Semiconductor            | 2         | 0.91%   |
| Broadcom Limited                 | 2         | 0.91%   |
| ASIX Electronics                 | 2         | 0.91%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Qualcomm                         | 1         | 0.45%   |
| Nvidia                           | 1         | 0.45%   |
| Microchip Technology             | 1         | 0.45%   |
| Mellanox Technologies            | 1         | 0.45%   |
| MediaTek                         | 1         | 0.45%   |
| JMicron Technology               | 1         | 0.45%   |
| Huawei Technologies              | 1         | 0.45%   |
| DisplayLink                      | 1         | 0.45%   |
| Apple                            | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 89        | 39.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 18        | 8.07%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 3.59%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 3.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.79%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 1.79%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.79%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 1.35%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.9%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 0.9%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.9%    |
| Intel Ethernet Controller I226-V                                       | 2         | 0.9%    |
| Intel Ethernet Connection I219-V                                       | 2         | 0.9%    |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.9%    |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.9%    |
| Cypress K38231_03                                                      | 2         | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.45%   |
| Qualcomm POCO F3                                                       | 1         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.45%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.45%   |
| Microchip LAN7800                                                      | 1         | 0.45%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                | 1         | 0.45%   |
| MediaTek Infinix SMART 5                                               | 1         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.45%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.45%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.45%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 1         | 0.45%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 1         | 0.45%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.45%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 204       | 50.25%  |
| WiFi     | 197       | 48.52%  |
| Modem    | 4         | 0.99%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 160       | 61.54%  |
| Ethernet | 100       | 38.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 123       | 47.49%  |
| 1     | 113       | 43.63%  |
| 0     | 11        | 4.25%   |
| 3     | 10        | 3.86%   |
| 4     | 2         | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 205       | 78.24%  |
| Yes  | 57        | 21.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 44%     |
| Realtek Semiconductor           | 23        | 13.14%  |
| Lite-On Technology              | 12        | 6.86%   |
| Broadcom                        | 11        | 6.29%   |
| IMC Networks                    | 9         | 5.14%   |
| Cambridge Silicon Radio         | 9         | 5.14%   |
| Foxconn / Hon Hai               | 8         | 4.57%   |
| USI                             | 4         | 2.29%   |
| Qualcomm Atheros Communications | 4         | 2.29%   |
| Apple                           | 4         | 2.29%   |
| Realtek                         | 3         | 1.71%   |
| MediaTek                        | 2         | 1.14%   |
| Toshiba                         | 1         | 0.57%   |
| Taiyo Yuden                     | 1         | 0.57%   |
| SINO WEALTH                     | 1         | 0.57%   |
| Ralink                          | 1         | 0.57%   |
| Opticis                         | 1         | 0.57%   |
| Foxconn International           | 1         | 0.57%   |
| Dell                            | 1         | 0.57%   |
| ASUSTek Computer                | 1         | 0.57%   |
| Actions                         | 1         | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 11.36%  |
| Intel AX200 Bluetooth                               | 18        | 10.23%  |
| Realtek Bluetooth Radio                             | 16        | 9.09%   |
| Intel AX201 Bluetooth                               | 14        | 7.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 5.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 5.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.84%   |
| Intel AX211 Bluetooth                               | 5         | 2.84%   |
| Intel AX210 Bluetooth                               | 5         | 2.84%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.84%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 2.84%   |
| USI Bluetooth Device                                | 4         | 2.27%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 2.27%   |
| Realtek Bluetooth Radio                             | 3         | 1.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.7%    |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 1.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.14%   |
| MediaTek Wireless_Device                            | 2         | 1.14%   |
| Lite-On Bluetooth Device                            | 2         | 1.14%   |
| IMC Networks Bluetooth Device                       | 2         | 1.14%   |
| Apple Bluetooth Host Controller                     | 2         | 1.14%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.57%   |
| Taiyo Yuden Bluetooth Device(BC04-External)         | 1         | 0.57%   |
| SINO WEALTH Bluetooth Keyboard                      | 1         | 0.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.57%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.57%   |
| Opticis Bluetooth Radio                             | 1         | 0.57%   |
| Lite-On Wireless_Device                             | 1         | 0.57%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.57%   |
| Lite-On BCM43142A0                                  | 1         | 0.57%   |
| Intel Bluetooth Device                              | 1         | 0.57%   |
| IMC Networks Wireless_Device                        | 1         | 0.57%   |
| IMC Networks Bluetooth                              | 1         | 0.57%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 152       | 42.58%  |
| AMD                                  | 102       | 28.57%  |
| Nvidia                               | 52        | 14.57%  |
| Logitech                             | 6         | 1.68%   |
| C-Media Electronics                  | 6         | 1.68%   |
| JMTek                                | 5         | 1.4%    |
| Corsair                              | 3         | 0.84%   |
| Texas Instruments                    | 2         | 0.56%   |
| Focusrite-Novation                   | 2         | 0.56%   |
| Creative Technology                  | 2         | 0.56%   |
| Astro Gaming                         | 2         | 0.56%   |
| VIA Technologies                     | 1         | 0.28%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.28%   |
| SteelSeries ApS                      | 1         | 0.28%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.28%   |
| SAVITECH                             | 1         | 0.28%   |
| Samson Technologies                  | 1         | 0.28%   |
| Razer USA                            | 1         | 0.28%   |
| Mark of the Unicorn                  | 1         | 0.28%   |
| KTMicro                              | 1         | 0.28%   |
| Kingston Technology                  | 1         | 0.28%   |
| Giga-Byte Technology                 | 1         | 0.28%   |
| Fry's Electronics                    | 1         | 0.28%   |
| FiiO Electronics Technology          | 1         | 0.28%   |
| Elgato Systems                       | 1         | 0.28%   |
| EDFIER                               | 1         | 0.28%   |
| Creative Labs                        | 1         | 0.28%   |
| Cambridge Silicon Radio              | 1         | 0.28%   |
| Cambridge Audio                      | 1         | 0.28%   |
| Blue Microphones                     | 1         | 0.28%   |
| BEHRINGER International              | 1         | 0.28%   |
| ASUSTek Computer                     | 1         | 0.28%   |
| ASRock                               | 1         | 0.28%   |
| Apple                                | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 42        | 9.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 25        | 5.52%   |
| AMD Starship/Matisse HD Audio Controller                                   | 19        | 4.19%   |
| Intel Sunrise Point-LP HD Audio                                            | 18        | 3.97%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 2.87%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 2.65%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 11        | 2.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 1.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 1.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 1.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 1.32%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.32%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 1.32%   |
| JMTek USB PnP Audio Device                                                 | 5         | 1.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 1.1%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.1%    |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.1%    |
| AMD High Definition Audio Controller                                       | 5         | 1.1%    |
| AMD FCH Azalia Controller                                                  | 5         | 1.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 0.88%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4         | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 23.67%  |
| SK hynix            | 47        | 22.71%  |
| Micron Technology   | 23        | 11.11%  |
| Unknown             | 15        | 7.25%   |
| Kingston            | 15        | 7.25%   |
| G.Skill             | 12        | 5.8%    |
| Corsair             | 12        | 5.8%    |
| Crucial             | 8         | 3.86%   |
| A-DATA Technology   | 8         | 3.86%   |
| Ramaxel Technology  | 3         | 1.45%   |
| Transcend           | 2         | 0.97%   |
| Team                | 2         | 0.97%   |
| Nanya Technology    | 2         | 0.97%   |
| Wodposit            | 1         | 0.48%   |
| Unknown (ABCD)      | 1         | 0.48%   |
| Smart               | 1         | 0.48%   |
| Patriot             | 1         | 0.48%   |
| Kingmax             | 1         | 0.48%   |
| Elpida              | 1         | 0.48%   |
| Avant               | 1         | 0.48%   |
| 4ea5                | 1         | 0.48%   |
| 48spaces            | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 1.33%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.88%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.88%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.88%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 0.88%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s       | 2         | 0.88%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.88%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 2         | 0.88%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 2         | 0.88%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 0.88%   |
| Wodposit RAM WPBH32D408SWD-8G 8GB SODIMM DDR4 3200MT/s           | 1         | 0.44%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.44%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.44%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.44%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.44%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 1         | 0.44%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 89        | 49.17%  |
| DDR3    | 55        | 30.39%  |
| LPDDR5  | 7         | 3.87%   |
| DDR5    | 7         | 3.87%   |
| DDR2    | 7         | 3.87%   |
| LPDDR4  | 6         | 3.31%   |
| LPDDR3  | 4         | 2.21%   |
| Unknown | 3         | 1.66%   |
| SDRAM   | 2         | 1.1%    |
| DDR     | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 113       | 62.09%  |
| DIMM         | 51        | 28.02%  |
| Row Of Chips | 17        | 9.34%   |
| Unknown      | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 87        | 43.28%  |
| 4096  | 55        | 27.36%  |
| 16384 | 25        | 12.44%  |
| 2048  | 15        | 7.46%   |
| 32768 | 7         | 3.48%   |
| 1024  | 7         | 3.48%   |
| 512   | 4         | 1.99%   |
| 24576 | 1         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 38        | 19.1%   |
| 3200    | 33        | 16.58%  |
| 2667    | 30        | 15.08%  |
| 2400    | 13        | 6.53%   |
| 1333    | 12        | 6.03%   |
| 3600    | 8         | 4.02%   |
| 6400    | 7         | 3.52%   |
| 2133    | 6         | 3.02%   |
| 1334    | 6         | 3.02%   |
| 667     | 5         | 2.51%   |
| 5600    | 3         | 1.51%   |
| 4800    | 3         | 1.51%   |
| 3733    | 3         | 1.51%   |
| 1867    | 3         | 1.51%   |
| 533     | 3         | 1.51%   |
| Unknown | 3         | 1.51%   |
| 3866    | 2         | 1.01%   |
| 3534    | 2         | 1.01%   |
| 8400    | 1         | 0.5%    |
| 8200    | 1         | 0.5%    |
| 4267    | 1         | 0.5%    |
| 4266    | 1         | 0.5%    |
| 4199    | 1         | 0.5%    |
| 4000    | 1         | 0.5%    |
| 3800    | 1         | 0.5%    |
| 3466    | 1         | 0.5%    |
| 3333    | 1         | 0.5%    |
| 3266    | 1         | 0.5%    |
| 3000    | 1         | 0.5%    |
| 2933    | 1         | 0.5%    |
| 2800    | 1         | 0.5%    |
| 2666    | 1         | 0.5%    |
| 1866    | 1         | 0.5%    |
| 1800    | 1         | 0.5%    |
| 1067    | 1         | 0.5%    |
| 1066    | 1         | 0.5%    |
| 800     | 1         | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 47        | 27.65%  |
| IMC Networks                           | 18        | 10.59%  |
| Microdia                               | 16        | 9.41%   |
| Bison Electronics                      | 15        | 8.82%   |
| Quanta                                 | 11        | 6.47%   |
| Realtek Semiconductor                  | 9         | 5.29%   |
| Logitech                               | 8         | 4.71%   |
| Sunplus Innovation Technology          | 6         | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.53%   |
| Syntek                                 | 4         | 2.35%   |
| Luxvisions Innotech Limited            | 4         | 2.35%   |
| Suyin                                  | 3         | 1.76%   |
| Acer                                   | 3         | 1.76%   |
| Sonix Technology                       | 2         | 1.18%   |
| MacroSilicon                           | 2         | 1.18%   |
| Apple                                  | 2         | 1.18%   |
| Alcor Micro                            | 2         | 1.18%   |
| WaveRider Communications               | 1         | 0.59%   |
| SunplusIT                              | 1         | 0.59%   |
| Silicon Motion                         | 1         | 0.59%   |
| Shine-optics                           | 1         | 0.59%   |
| Samsung Electronics                    | 1         | 0.59%   |
| Microsoft                              | 1         | 0.59%   |
| Intel                                  | 1         | 0.59%   |
| Hewlett-Packard                        | 1         | 0.59%   |
| GEMBIRD                                | 1         | 0.59%   |
| Asuscom Network                        | 1         | 0.59%   |
| Alcorlink                              | 1         | 0.59%   |
| Unknown                                | 1         | 0.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 14        | 8.14%   |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 4.07%   |
| Quanta HD User Facing                         | 4         | 2.33%   |
| Microdia Integrated_Webcam_HD                 | 4         | 2.33%   |
| Chicony HP TrueVision HD Camera               | 4         | 2.33%   |
| Chicony HD WebCam                             | 4         | 2.33%   |
| Bison Integrated RGB Camera                   | 4         | 2.33%   |
| Syntek Integrated Camera                      | 3         | 1.74%   |
| Suyin HP Truevision HD                        | 3         | 1.74%   |
| Realtek USB Camera                            | 3         | 1.74%   |
| Microdia USB 2.0 Camera                       | 3         | 1.74%   |
| Logitech Webcam C270                          | 3         | 1.74%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 1.74%   |
| Chicony USB 2.0 Camera                        | 3         | 1.74%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 1.74%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.16%   |
| Quanta HP Webcam                              | 2         | 1.16%   |
| Microdia Webcam Vitade AF                     | 2         | 1.16%   |
| Microdia HP Integrated Webcam                 | 2         | 1.16%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.16%   |
| IMC Networks Integrated Camera                | 2         | 1.16%   |
| IMC Networks HD Camera                        | 2         | 1.16%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 1.16%   |
| Chicony USB2.0 Camera                         | 2         | 1.16%   |
| Chicony ThinkPad T490 Webcam                  | 2         | 1.16%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.16%   |
| Chicony Integrated Camera (1280x720@30)       | 2         | 1.16%   |
| Chicony HD WebCam (Acer)                      | 2         | 1.16%   |
| Chicony HD User Facing                        | 2         | 1.16%   |
| Chicony EasyCamera                            | 2         | 1.16%   |
| Bison SunplusIT Integrated Camera             | 2         | 1.16%   |
| Bison Lenovo EasyCamera                       | 2         | 1.16%   |
| Bison Integrated Camera                       | 2         | 1.16%   |
| WaveRider USB Live camera                     | 1         | 0.58%   |
| Syntek EasyCamera                             | 1         | 0.58%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 0.58%   |
| Sunplus USB 2.0 Camera                        | 1         | 0.58%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 0.58%   |
| Sunplus HP Wide Vision HD                     | 1         | 0.58%   |
| Sunplus DICOTA 4K                             | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 42.86%  |
| Shenzhen Goodix Technology | 5         | 17.86%  |
| Validity Sensors           | 4         | 14.29%  |
| Upek                       | 3         | 10.71%  |
| Elan Microelectronics      | 2         | 7.14%   |
| FocalTech                  | 1         | 3.57%   |
| Focal-systems.Corp         | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 17.86%  |
| Shenzhen Goodix  FingerPrint Device                    | 4         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 10.71%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 10.71%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 3.57%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 3.57%   |
| Synaptics WBDI                                         | 1         | 3.57%   |
| Synaptics UWP WBDI Device                              | 1         | 3.57%   |
| Synaptics  WBDI                                        | 1         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 3.57%   |
| FocalTech FocalTech Fingerprint Device                 | 1         | 3.57%   |
| Focal-systems.Corp FT9201Fingerprint.Ì              | 1         | 3.57%   |
| Elan ELAN:Fingerprint                                  | 1         | 3.57%   |
| Elan ELAN:ARM-M4                                       | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 5         | 55.56%  |
| Lenovo      | 2         | 22.22%  |
| Broadcom    | 2         | 22.22%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 5         | 55.56%  |
| Lenovo Integrated Smart Card Reader            | 2         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 11.11%  |
| Broadcom 58200                                 | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 191       | 73.46%  |
| 1     | 55        | 21.15%  |
| 2     | 12        | 4.62%   |
| 3     | 2         | 0.77%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 28        | 33.73%  |
| Graphics card            | 17        | 20.48%  |
| Net/wireless             | 9         | 10.84%  |
| Chipcard                 | 9         | 10.84%  |
| Sound                    | 4         | 4.82%   |
| Multimedia controller    | 4         | 4.82%   |
| Communication controller | 4         | 4.82%   |
| Camera                   | 4         | 4.82%   |
| Card reader              | 2         | 2.41%   |
| Net/ethernet             | 1         | 1.2%    |
| Bluetooth                | 1         | 1.2%    |

