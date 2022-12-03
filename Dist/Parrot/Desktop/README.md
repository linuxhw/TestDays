Parrot - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 121

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Z170-DELUXE             | [7928d11567](https://linux-hardware.org/?probe=7928d11567) | Nov 19, 2022 |
| Dell          | 0C1R19 A02              | [514ae17aa9](https://linux-hardware.org/?probe=514ae17aa9) | Nov 06, 2022 |
| HP            | 89B5 A                  | [1b04604c98](https://linux-hardware.org/?probe=1b04604c98) | Nov 03, 2022 |
| Gigabyte      | Z97N-WIFI               | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI               | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| ASUSTek       | P5G41T-M LX             | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Gigabyte      | M61SME-S2               | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| ASUSTek       | P6X58D-E                | [d84fc5ce81](https://linux-hardware.org/?probe=d84fc5ce81) | Oct 13, 2022 |
| ASUSTek       | P6X58D-E                | [2a896ec4f6](https://linux-hardware.org/?probe=2a896ec4f6) | Oct 13, 2022 |
| Gigabyte      | H110M-H DDR3-CF         | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| Gigabyte      | H61M-S2PT               | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Gateway       | SX2855                  | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| ASUSTek       | H110M-K                 | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z   | [0539efedb2](https://linux-hardware.org/?probe=0539efedb2) | Jul 18, 2022 |
| ASUSTek       | H110M-K                 | [0e0a7a2fbc](https://linux-hardware.org/?probe=0e0a7a2fbc) | Jul 16, 2022 |
| ASUSTek       | PRIME B550-PLUS         | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS         | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| ASUSTek       | H110M-K                 | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| ASUSTek       | H110M-K                 | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| Gigabyte      | H61M-USB3H              | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Unknown       | TB-4000                 | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Lenovo        | 31900058 STD            | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF           | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| MSI           | G31M3-L V2              | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| HP            | 1495                    | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Unknown       | TB-4000                 | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | PRIME H310M-D R2.0      | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                    | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                  | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                  | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | B350 TOMAHAWK           | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| ECS           | Nettle2                 | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                    | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| Lenovo        | SHARKBAY 31900058 STD   | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD   | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                  | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3              | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                 | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3              | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| ASUSTek       | F2A85-M                 | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                 | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4           | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| MSI           | G31M3-L V2              | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| ASUSTek       | B85M-E                  | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                  | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Unknown       | TB-4000                 | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Unknown       | TB-4000                 | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Dell          | 0GXM1W A02              | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| ASUSTek       | Benicia                 | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| Unknown       | TB-4000                 | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Unknown       | Unknown                 | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01              | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01              | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF            | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| ASUSTek       | M5A99X EVO              | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Alienware     | 0PGRP5 A02              | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer              | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Acer          | Aspire TC-780           | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Dell          | 0T2HR0 A00              | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO             | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF            | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF            | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| MSI           | B450 TOMAHAWK MAX       | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF            | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| ZOTAC         | Unknown                 | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                 | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| HP            | 1850                    | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | 0T10XW A02              | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| HP            | 1850                    | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| Dell          | 0C1R19 A02              | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| ASUSTek       | PRIME X399-A            | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Predator PO3-600 V:1.1  | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| ASUSTek       | M5A78L-M/USB3           | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| HP            | 339A                    | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                    | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| MSI           | B250M MORTAR            | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                  | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| Acer          | Aspire X3990            | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990            | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                   | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Medion        | MS-7621                 | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC             | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| HP            | 3047h                   | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K     | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | Maximus VIII HERO       | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO              | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO              | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ECS           | A740GM-M                | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| ASUSTek       | Z170 PRO GAMING         | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Gigabyte      | H370M DS3H-CF           | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Apple         | Mac-F221BEC8            | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00              | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P               | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Biostar       | H77MU3                  | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS              | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS              | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| ASUSTek       | H110I-PLUS              | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek       | H110I-PLUS              | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Dell          | 0VYXHD A00              | [5e5d0a24f3](https://linux-hardware.org/?probe=5e5d0a24f3) | May 15, 2020 |
| Dell          | 0VYXHD A00              | [5a56c30293](https://linux-hardware.org/?probe=5a56c30293) | May 06, 2020 |
| Dell          | 05DN3X A00              | [7424c0caba](https://linux-hardware.org/?probe=7424c0caba) | May 02, 2020 |
| ASUSTek       | A68HM-PLUS              | [3dc6534b5f](https://linux-hardware.org/?probe=3dc6534b5f) | May 01, 2020 |
| ASUSTek       | A68HM-PLUS              | [6835f4fe95](https://linux-hardware.org/?probe=6835f4fe95) | Apr 28, 2020 |
| Foxconn       | 2A8C                    | [6e636c5fd2](https://linux-hardware.org/?probe=6e636c5fd2) | Apr 27, 2020 |
| Foxconn       | 2A8C                    | [d19700bc2d](https://linux-hardware.org/?probe=d19700bc2d) | Apr 27, 2020 |
| ASUSTek       | M2N68-AM Plus           | [72dcfa02ca](https://linux-hardware.org/?probe=72dcfa02ca) | Apr 26, 2020 |
| Foxconn       | 2A8C                    | [37c314650f](https://linux-hardware.org/?probe=37c314650f) | Apr 26, 2020 |
| Foxconn       | 2A8C                    | [9a9b368a7c](https://linux-hardware.org/?probe=9a9b368a7c) | Apr 26, 2020 |
| ASUSTek       | K31CD-K                 | [b4ad316fa2](https://linux-hardware.org/?probe=b4ad316fa2) | Apr 14, 2020 |
| Dell          | 0CU409                  | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Dell          | 0CU409                  | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H            | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| ASRock        | FM2A68M-DG3+            | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| Gigabyte      | AX370-Gaming-CF se1     | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1     | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Foxconn       | 2A8C                    | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                    | [05e5552eea](https://linux-hardware.org/?probe=05e5552eea) | Jan 19, 2020 |
| ASUSTek       | M5A78L-M/USB3           | [51389e5c4a](https://linux-hardware.org/?probe=51389e5c4a) | Dec 07, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Parrot 5.0  | 26       | 30.23%  |
| Parrot 4.11 | 21       | 24.42%  |
| Parrot 4.10 | 14       | 16.28%  |
| Parrot 4.9  | 9        | 10.47%  |
| Parrot 5.1  | 7        | 8.14%   |
| Parrot 4.8  | 6        | 6.98%   |
| Parrot 4.7  | 3        | 3.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Parrot | 82       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.0-12parrot1-amd64   | 14       | 15.73%  |
| 5.14.0-9parrot1-amd64    | 13       | 14.61%  |
| 5.5.0-1parrot1-amd64     | 12       | 13.48%  |
| 5.7.0-2parrot2-amd64     | 6        | 6.74%   |
| 5.15.0-15parrot1-amd64   | 6        | 6.74%   |
| 5.10.0-6parrot1-amd64    | 6        | 6.74%   |
| 6.0.0-2parrot1-amd64     | 4        | 4.49%   |
| 5.8.0-2parrot1-amd64     | 3        | 3.37%   |
| 5.4.0-4parrot1-amd64     | 3        | 3.37%   |
| 5.10.0-8parrot1-amd64    | 3        | 3.37%   |
| 5.9.0-2parrot1-amd64     | 2        | 2.25%   |
| 5.4.0-2parrot1-amd64     | 2        | 2.25%   |
| 5.3.0-3parrot3-amd64     | 2        | 2.25%   |
| 5.18.0-1parrot1-amd64    | 2        | 2.25%   |
| 5.18.0-14parrot1-amd64   | 2        | 2.25%   |
| 5.14.0-2parrot1-amd64    | 2        | 2.25%   |
| 5.10.0-3parrot1-amd64    | 2        | 2.25%   |
| 5.8.0-1parrot1-amd64     | 1        | 1.12%   |
| 5.6.0-2parrot1-amd64     | 1        | 1.12%   |
| 5.4.0-3parrot1-amd64     | 1        | 1.12%   |
| 5.16.0-12parrot1-686-pae | 1        | 1.12%   |
| 5.10.0-5parrot1-amd64    | 1        | 1.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16.0  | 15       | 17.05%  |
| 5.14.0  | 14       | 15.91%  |
| 5.5.0   | 12       | 13.64%  |
| 5.10.0  | 12       | 13.64%  |
| 5.7.0   | 6        | 6.82%   |
| 5.4.0   | 6        | 6.82%   |
| 5.15.0  | 6        | 6.82%   |
| 6.0.0   | 4        | 4.55%   |
| 5.8.0   | 4        | 4.55%   |
| 5.18.0  | 4        | 4.55%   |
| 5.9.0   | 2        | 2.27%   |
| 5.3.0   | 2        | 2.27%   |
| 5.6.0   | 1        | 1.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 15       | 17.05%  |
| 5.14    | 14       | 15.91%  |
| 5.5     | 12       | 13.64%  |
| 5.10    | 12       | 13.64%  |
| 5.7     | 6        | 6.82%   |
| 5.4     | 6        | 6.82%   |
| 5.15    | 6        | 6.82%   |
| 6.0     | 4        | 4.55%   |
| 5.8     | 4        | 4.55%   |
| 5.18    | 4        | 4.55%   |
| 5.9     | 2        | 2.27%   |
| 5.3     | 2        | 2.27%   |
| 5.6     | 1        | 1.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 81       | 98.78%  |
| i686   | 1        | 1.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 58       | 68.24%  |
| KDE5    | 11       | 12.94%  |
| KDE     | 7        | 8.24%   |
| XFCE    | 4        | 4.71%   |
| Unknown | 3        | 3.53%   |
| GNOME   | 2        | 2.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 80       | 97.56%  |
| Wayland | 2        | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 33       | 38.82%  |
| Unknown | 29       | 34.12%  |
| TDM     | 18       | 21.18%  |
| SDDM    | 3        | 3.53%   |
| GDM     | 2        | 2.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 47       | 57.32%  |
| ru_RU | 4        | 4.88%   |
| pt_BR | 3        | 3.66%   |
| fr_FR | 3        | 3.66%   |
| es_ES | 3        | 3.66%   |
| en_IN | 3        | 3.66%   |
| de_DE | 3        | 3.66%   |
| pl_PL | 2        | 2.44%   |
| en_HK | 2        | 2.44%   |
| cs_CZ | 2        | 2.44%   |
| ru_UA | 1        | 1.22%   |
| mk_MK | 1        | 1.22%   |
| it_IT | 1        | 1.22%   |
| es_MX | 1        | 1.22%   |
| en_GB | 1        | 1.22%   |
| en_DK | 1        | 1.22%   |
| en_CA | 1        | 1.22%   |
| en_AU | 1        | 1.22%   |
| de_AT | 1        | 1.22%   |
| an_ES | 1        | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 67       | 78.82%  |
| EFI  | 18       | 21.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 67       | 79.76%  |
| Ext4    | 12       | 14.29%  |
| Overlay | 3        | 3.57%   |
| Xfs     | 2        | 2.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 46       | 53.49%  |
| GPT     | 24       | 27.91%  |
| MBR     | 16       | 18.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 70       | 82.35%  |
| Yes       | 15       | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 58.54%  |
| Yes       | 34       | 41.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 26       | 31.71%  |
| Gigabyte Technology | 12       | 14.63%  |
| Dell                | 10       | 12.2%   |
| Hewlett-Packard     | 7        | 8.54%   |
| MSI                 | 4        | 4.88%   |
| Foxconn             | 3        | 3.66%   |
| ASRock              | 3        | 3.66%   |
| Acer                | 3        | 3.66%   |
| Lenovo              | 2        | 2.44%   |
| ECS                 | 2        | 2.44%   |
| Unknown             | 2        | 2.44%   |
| ZOTAC               | 1        | 1.22%   |
| Wistron             | 1        | 1.22%   |
| Positivo            | 1        | 1.22%   |
| Gateway             | 1        | 1.22%   |
| Daewoo Lucoms       | 1        | 1.22%   |
| Biostar             | 1        | 1.22%   |
| Apple               | 1        | 1.22%   |
| Alienware           | 1        | 1.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Unknown                                   | 3        | 3.66%   |
| HP ProDesk 600 G1 SFF                     | 2        | 2.44%   |
| Gigabyte AX370-Gaming                     | 2        | 2.44%   |
| Foxconn s5710t                            | 2        | 2.44%   |
| Dell Inspiron 5676                        | 2        | 2.44%   |
| ASUS M5A78L-M/USB3                        | 2        | 2.44%   |
| ASUS H110I-PLUS                           | 2        | 2.44%   |
| ASUS Basic 3221BM                         | 2        | 2.44%   |
| Wistron FMVDD2A0H0                        | 1        | 1.22%   |
| Positivo POS-PIG43BC                      | 1        | 1.22%   |
| MSI MS-7C02                               | 1        | 1.22%   |
| MSI MS-7A69                               | 1        | 1.22%   |
| MSI MS-7A34                               | 1        | 1.22%   |
| MSI MS-7529                               | 1        | 1.22%   |
| Lenovo H535 10117                         | 1        | 1.22%   |
| Lenovo H530 10130                         | 1        | 1.22%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx | 1        | 1.22%   |
| HP Compaq Pro 6305 MT                     | 1        | 1.22%   |
| HP Compaq Pro 6300 MT                     | 1        | 1.22%   |
| HP Compaq 8200 Elite SFF PC               | 1        | 1.22%   |
| HP Compaq 6005 Pro MT PC                  | 1        | 1.22%   |
| Gigabyte Z97N-WIFI                        | 1        | 1.22%   |
| Gigabyte M61SME-S2                        | 1        | 1.22%   |
| Gigabyte H61M-USB3H                       | 1        | 1.22%   |
| Gigabyte H61M-S2PT                        | 1        | 1.22%   |
| Gigabyte H370M-DS3H                       | 1        | 1.22%   |
| Gigabyte H110M-H DDR3                     | 1        | 1.22%   |
| Gigabyte GA-880GM-D2H                     | 1        | 1.22%   |
| Gigabyte B450M DS3H                       | 1        | 1.22%   |
| Gigabyte A320M-S2H                        | 1        | 1.22%   |
| Gigabyte 970A-DS3P                        | 1        | 1.22%   |
| Gateway SX2855                            | 1        | 1.22%   |
| Foxconn 45CMX/45GMX/45CMX-K               | 1        | 1.22%   |
| ECS GV460AA-ABA a6217c                    | 1        | 1.22%   |
| ECS A740GM-M                              | 1        | 1.22%   |
| Dell XPS 8930                             | 1        | 1.22%   |
| Dell Vostro 200                           | 1        | 1.22%   |
| Dell Studio XPS 9100                      | 1        | 1.22%   |
| Dell OptiPlex 990                         | 1        | 1.22%   |
| Dell OptiPlex 7070                        | 1        | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 5        | 6.1%    |
| HP Compaq             | 4        | 4.88%   |
| ASUS PRIME            | 3        | 3.66%   |
| Unknown               | 3        | 3.66%   |
| HP ProDesk            | 2        | 2.44%   |
| Gigabyte AX370-Gaming | 2        | 2.44%   |
| Foxconn s5710t        | 2        | 2.44%   |
| Dell Inspiron         | 2        | 2.44%   |
| ASUS ROG              | 2        | 2.44%   |
| ASUS M5A78L-M         | 2        | 2.44%   |
| ASUS H110I-PLUS       | 2        | 2.44%   |
| ASUS Basic            | 2        | 2.44%   |
| Acer Aspire           | 2        | 2.44%   |
| Wistron FMVDD2A0H0    | 1        | 1.22%   |
| Positivo POS-PIG43BC  | 1        | 1.22%   |
| MSI MS-7C02           | 1        | 1.22%   |
| MSI MS-7A69           | 1        | 1.22%   |
| MSI MS-7A34           | 1        | 1.22%   |
| MSI MS-7529           | 1        | 1.22%   |
| Lenovo H535           | 1        | 1.22%   |
| Lenovo H530           | 1        | 1.22%   |
| HP Victus             | 1        | 1.22%   |
| Gigabyte Z97N-WIFI    | 1        | 1.22%   |
| Gigabyte M61SME-S2    | 1        | 1.22%   |
| Gigabyte H61M-USB3H   | 1        | 1.22%   |
| Gigabyte H61M-S2PT    | 1        | 1.22%   |
| Gigabyte H370M-DS3H   | 1        | 1.22%   |
| Gigabyte H110M-H      | 1        | 1.22%   |
| Gigabyte GA-880GM-D2H | 1        | 1.22%   |
| Gigabyte B450M        | 1        | 1.22%   |
| Gigabyte A320M-S2H    | 1        | 1.22%   |
| Gigabyte 970A-DS3P    | 1        | 1.22%   |
| Gateway SX2855        | 1        | 1.22%   |
| Foxconn 45CMX         | 1        | 1.22%   |
| ECS GV460AA-ABA       | 1        | 1.22%   |
| ECS A740GM-M          | 1        | 1.22%   |
| Dell XPS              | 1        | 1.22%   |
| Dell Vostro           | 1        | 1.22%   |
| Dell Studio           | 1        | 1.22%   |
| Daewoo Lucoms OEM     | 1        | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 11       | 13.41%  |
| 2011 | 10       | 12.2%   |
| 2016 | 8        | 9.76%   |
| 2010 | 8        | 9.76%   |
| 2018 | 7        | 8.54%   |
| 2017 | 6        | 7.32%   |
| 2012 | 6        | 7.32%   |
| 2015 | 5        | 6.1%    |
| 2007 | 5        | 6.1%    |
| 2019 | 4        | 4.88%   |
| 2014 | 3        | 3.66%   |
| 2009 | 3        | 3.66%   |
| 2021 | 2        | 2.44%   |
| 2020 | 2        | 2.44%   |
| 2022 | 1        | 1.22%   |
| 2008 | 1        | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 82       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 82       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 82       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 23       | 27.06%  |
| 4.01-8.0    | 18       | 21.18%  |
| 8.01-16.0   | 17       | 20%     |
| 3.01-4.0    | 12       | 14.12%  |
| 32.01-64.0  | 10       | 11.76%  |
| 1.01-2.0    | 3        | 3.53%   |
| 24.01-32.0  | 1        | 1.18%   |
| 64.01-256.0 | 1        | 1.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 30       | 34.88%  |
| 2.01-3.0   | 24       | 27.91%  |
| 4.01-8.0   | 14       | 16.28%  |
| 3.01-4.0   | 9        | 10.47%  |
| 0.51-1.0   | 6        | 6.98%   |
| 8.01-16.0  | 2        | 2.33%   |
| 16.01-24.0 | 1        | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 36.47%  |
| 1      | 30       | 35.29%  |
| 3      | 13       | 15.29%  |
| 4      | 7        | 8.24%   |
| 5      | 3        | 3.53%   |
| 6      | 1        | 1.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 69.41%  |
| Yes       | 26       | 30.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 80       | 97.56%  |
| No        | 2        | 2.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 59       | 70.24%  |
| No        | 25       | 29.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 71.95%  |
| Yes       | 23       | 28.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Desktops | Percent |
|-----------------|----------|---------|
| USA             | 26       | 31.33%  |
| Germany         | 7        | 8.43%   |
| Brazil          | 6        | 7.23%   |
| Spain           | 4        | 4.82%   |
| India           | 4        | 4.82%   |
| Russia          | 3        | 3.61%   |
| Netherlands     | 3        | 3.61%   |
| Italy           | 2        | 2.41%   |
| Hong Kong       | 2        | 2.41%   |
| France          | 2        | 2.41%   |
| Czechia         | 2        | 2.41%   |
| Canada          | 2        | 2.41%   |
| Austria         | 2        | 2.41%   |
| Vietnam         | 1        | 1.2%    |
| Ukraine         | 1        | 1.2%    |
| UK              | 1        | 1.2%    |
| Turkey          | 1        | 1.2%    |
| Romania         | 1        | 1.2%    |
| Poland          | 1        | 1.2%    |
| Philippines     | 1        | 1.2%    |
| Pakistan        | 1        | 1.2%    |
| North Macedonia | 1        | 1.2%    |
| Morocco         | 1        | 1.2%    |
| Mongolia        | 1        | 1.2%    |
| Mexico          | 1        | 1.2%    |
| Egypt           | 1        | 1.2%    |
| Denmark         | 1        | 1.2%    |
| Bulgaria        | 1        | 1.2%    |
| Belgium         | 1        | 1.2%    |
| Australia       | 1        | 1.2%    |
| Algeria         | 1        | 1.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Indianapolis         | 3        | 3.53%   |
| Vienna               | 2        | 2.35%   |
| Uherské Hradiště  | 2        | 2.35%   |
| Ngau Wu Tok          | 2        | 2.35%   |
| Newburgh             | 2        | 2.35%   |
| Madrid               | 2        | 2.35%   |
| Eugene               | 2        | 2.35%   |
| Warsaw               | 1        | 1.18%   |
| Viby J               | 1        | 1.18%   |
| Vapi                 | 1        | 1.18%   |
| Valencia             | 1        | 1.18%   |
| Ulan Bator           | 1        | 1.18%   |
| Terrace              | 1        | 1.18%   |
| Tangier              | 1        | 1.18%   |
| Sydney               | 1        | 1.18%   |
| Springfield          | 1        | 1.18%   |
| Sorocaba             | 1        | 1.18%   |
| Sofia                | 1        | 1.18%   |
| Skopje               | 1        | 1.18%   |
| Sao Paulo            | 1        | 1.18%   |
| Sao Joao de Meriti   | 1        | 1.18%   |
| Santa Maria          | 1        | 1.18%   |
| Saint Paul           | 1        | 1.18%   |
| Rawalpindi           | 1        | 1.18%   |
| Portsmouth           | 1        | 1.18%   |
| Portland             | 1        | 1.18%   |
| Point Pleasant Beach | 1        | 1.18%   |
| Pensacola            | 1        | 1.18%   |
| Ordu                 | 1        | 1.18%   |
| Orange Park          | 1        | 1.18%   |
| Nuremberg            | 1        | 1.18%   |
| Nizhniy Novgorod     | 1        | 1.18%   |
| New Delhi            | 1        | 1.18%   |
| Nam Định          | 1        | 1.18%   |
| Naaldwijk            | 1        | 1.18%   |
| Morelia              | 1        | 1.18%   |
| Montreal             | 1        | 1.18%   |
| Monserrato           | 1        | 1.18%   |
| Milton               | 1        | 1.18%   |
| Milan                | 1        | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 50     | 23.18%  |
| WDC                 | 33       | 47     | 21.85%  |
| Samsung Electronics | 15       | 24     | 9.93%   |
| Toshiba             | 12       | 12     | 7.95%   |
| Kingston            | 9        | 11     | 5.96%   |
| SanDisk             | 7        | 10     | 4.64%   |
| Hitachi             | 6        | 7      | 3.97%   |
| Crucial             | 4        | 4      | 2.65%   |
| Unknown             | 3        | 3      | 1.99%   |
| JMicron Technology  | 3        | 3      | 1.99%   |
| SPCC                | 2        | 2      | 1.32%   |
| SK hynix            | 2        | 3      | 1.32%   |
| Phison              | 2        | 2      | 1.32%   |
| LITEONIT            | 2        | 2      | 1.32%   |
| Fujitsu             | 2        | 2      | 1.32%   |
| China               | 2        | 5      | 1.32%   |
| Team                | 1        | 2      | 0.66%   |
| Silicon Motion      | 1        | 1      | 0.66%   |
| PNY                 | 1        | 1      | 0.66%   |
| Plextor             | 1        | 1      | 0.66%   |
| OCZ                 | 1        | 1      | 0.66%   |
| Micron Technology   | 1        | 1      | 0.66%   |
| Intenso             | 1        | 1      | 0.66%   |
| HGST                | 1        | 1      | 0.66%   |
| FORESEE             | 1        | 1      | 0.66%   |
| Corsair             | 1        | 1      | 0.66%   |
| Apacer              | 1        | 1      | 0.66%   |
| A-DATA Technology   | 1        | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA200 2TB             | 5        | 2.82%   |
| Seagate ST31000528AS 1TB           | 3        | 1.69%   |
| Seagate ST250DM000-1BD141 250GB    | 3        | 1.69%   |
| Seagate Expansion 1TB              | 3        | 1.69%   |
| Samsung SSD 860 EVO 500GB          | 3        | 1.69%   |
| Samsung SSD 860 EVO 250GB          | 3        | 1.69%   |
| Kingston SA400S37480G 480GB SSD    | 3        | 1.69%   |
| Kingston SA400S37240G 240GB SSD    | 3        | 1.69%   |
| JMicron Generic 1TB                | 3        | 1.69%   |
| WDC WD5000AADS-00S9B0 500GB        | 2        | 1.13%   |
| WDC WD2500JS-75MHB0 250GB          | 2        | 1.13%   |
| WDC WD2500AAKX-753CA1 250GB        | 2        | 1.13%   |
| WDC WD10EZRX-00L4HB0 1TB           | 2        | 1.13%   |
| WDC WD10EZEX-00BN5A0 1TB           | 2        | 1.13%   |
| WDC WD10EARS-00Y5B1 1TB            | 2        | 1.13%   |
| Unknown SD/MMC/MS PRO 8GB          | 2        | 1.13%   |
| Toshiba DT01ACA050 500GB           | 2        | 1.13%   |
| Seagate ST500VT000-1DK142 500GB    | 2        | 1.13%   |
| Seagate ST500LM000-SSHD-8GB        | 2        | 1.13%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 2        | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.13%   |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 1.13%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 2        | 1.13%   |
| Samsung SSD 840 Series 250GB       | 2        | 1.13%   |
| Fujitsu F300 480GB                 | 2        | 1.13%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1        | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1        | 0.56%   |
| WDC WDS120G1G0B-00RC30 120GB SSD   | 1        | 0.56%   |
| WDC WDBRPG5000ANC-WRSN 500GB       | 1        | 0.56%   |
| WDC WDBNCE0010PNC 1TB SSD          | 1        | 0.56%   |
| WDC WD800JD-75MSA3 80GB            | 1        | 0.56%   |
| WDC WD800AAJS-75M0A0 80GB          | 1        | 0.56%   |
| WDC WD60EFAX-68SHWN0 6TB           | 1        | 0.56%   |
| WDC WD5002ABYS-01B1B0 500GB        | 1        | 0.56%   |
| WDC WD5000AAKS-75V0A0 500GB        | 1        | 0.56%   |
| WDC WD5000AACS-00ZUB0 500GB        | 1        | 0.56%   |
| WDC WD40EZRZ-75GXCB0 4TB           | 1        | 0.56%   |
| WDC WD3200LPVX-60V0TT0 320GB       | 1        | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 35       | 50     | 40.23%  |
| WDC                 | 27       | 40     | 31.03%  |
| Toshiba             | 12       | 12     | 13.79%  |
| Hitachi             | 6        | 7      | 6.9%    |
| Samsung Electronics | 4        | 6      | 4.6%    |
| Unknown             | 2        | 2      | 2.3%    |
| HGST                | 1        | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 14     | 16.98%  |
| Kingston            | 9        | 11     | 16.98%  |
| SanDisk             | 6        | 6      | 11.32%  |
| WDC                 | 5        | 5      | 9.43%   |
| Crucial             | 4        | 4      | 7.55%   |
| JMicron Technology  | 3        | 3      | 5.66%   |
| SPCC                | 2        | 2      | 3.77%   |
| LITEONIT            | 2        | 2      | 3.77%   |
| Fujitsu             | 2        | 2      | 3.77%   |
| China               | 2        | 5      | 3.77%   |
| Unknown             | 1        | 1      | 1.89%   |
| Team                | 1        | 2      | 1.89%   |
| PNY                 | 1        | 1      | 1.89%   |
| Plextor             | 1        | 1      | 1.89%   |
| OCZ                 | 1        | 1      | 1.89%   |
| Intenso             | 1        | 1      | 1.89%   |
| FORESEE             | 1        | 1      | 1.89%   |
| Corsair             | 1        | 1      | 1.89%   |
| Apacer              | 1        | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 63       | 118    | 52.94%  |
| SSD  | 44       | 64     | 36.97%  |
| NVMe | 12       | 18     | 10.08%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 74       | 173    | 78.72%  |
| NVMe | 12       | 18     | 12.77%  |
| SAS  | 8        | 9      | 8.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 63       | 117    | 54.31%  |
| 0.51-1.0   | 37       | 46     | 31.9%   |
| 1.01-2.0   | 11       | 14     | 9.48%   |
| 3.01-4.0   | 3        | 3      | 2.59%   |
| 2.01-3.0   | 1        | 1      | 0.86%   |
| 4.01-10.0  | 1        | 1      | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 24       | 27.27%  |
| 101-250        | 18       | 20.45%  |
| 501-1000       | 16       | 18.18%  |
| 1001-2000      | 13       | 14.77%  |
| 2001-3000      | 4        | 4.55%   |
| 51-100         | 4        | 4.55%   |
| Unknown        | 4        | 4.55%   |
| More than 3000 | 2        | 2.27%   |
| 21-50          | 2        | 2.27%   |
| 1-20           | 1        | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 23       | 25.84%  |
| 101-250        | 19       | 21.35%  |
| 1-20           | 15       | 16.85%  |
| 51-100         | 11       | 12.36%  |
| 251-500        | 8        | 8.99%   |
| 501-1000       | 6        | 6.74%   |
| Unknown        | 4        | 4.49%   |
| 1001-2000      | 2        | 2.25%   |
| More than 3000 | 1        | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| SanDisk SD6SF1M128G1022I 128GB SSD | 2        | 2      | 8.33%   |
| WDC WD5000AAKS-75V0A0 500GB        | 1        | 1      | 4.17%   |
| WDC WD2003FZEX-00Z4SA0 2TB         | 1        | 1      | 4.17%   |
| WDC WD10JUCX-63WPNY0 1TB           | 1        | 1      | 4.17%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 1      | 4.17%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 4.17%   |
| Seagate ST9250410AS 250GB          | 1        | 1      | 4.17%   |
| Seagate ST500NM0011 500GB          | 1        | 1      | 4.17%   |
| Seagate ST3500413AS 500GB          | 1        | 1      | 4.17%   |
| Seagate ST3320418AS 320GB          | 1        | 1      | 4.17%   |
| Seagate ST320LT007-9ZV142 320GB    | 1        | 1      | 4.17%   |
| Seagate ST3160215AS 160GB          | 1        | 1      | 4.17%   |
| Seagate ST31000528AS 1TB           | 1        | 1      | 4.17%   |
| Seagate ST250DM000-1BD141 250GB    | 1        | 1      | 4.17%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 4.17%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 4.17%   |
| SanDisk SSD PLUS 480GB             | 1        | 1      | 4.17%   |
| SanDisk SSD PLUS 1000GB            | 1        | 1      | 4.17%   |
| Samsung Electronics HM500JI 500GB  | 1        | 1      | 4.17%   |
| Samsung Electronics HD161HJ 160GB  | 1        | 1      | 4.17%   |
| Plextor PX-512M6Pro 512GB SSD      | 1        | 1      | 4.17%   |
| Hitachi HUA722020ALA331 2TB        | 1        | 1      | 4.17%   |
| A-DATA Technology SX7000NP 128GB   | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 11     | 40.91%  |
| WDC                 | 4        | 4      | 18.18%  |
| SanDisk             | 4        | 4      | 18.18%  |
| Samsung Electronics | 2        | 2      | 9.09%   |
| Plextor             | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 1      | 4.55%   |
| A-DATA Technology   | 1        | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 11     | 56.25%  |
| WDC                 | 4        | 4      | 25%     |
| Samsung Electronics | 2        | 2      | 12.5%   |
| Hitachi             | 1        | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 18     | 68.42%  |
| SSD  | 5        | 5      | 26.32%  |
| NVMe | 1        | 1      | 5.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1        | 1      | 50%     |
| Intenso SSD SATAIII 128GB   | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Intenso | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 50       | 115    | 47.17%  |
| Works    | 38       | 59     | 35.85%  |
| Malfunc  | 16       | 24     | 15.09%  |
| Failed   | 2        | 2      | 1.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 52       | 52.53%  |
| AMD                      | 26       | 26.26%  |
| SanDisk                  | 3        | 3.03%   |
| Samsung Electronics      | 3        | 3.03%   |
| Nvidia                   | 3        | 3.03%   |
| ASMedia Technology       | 3        | 3.03%   |
| SK hynix                 | 2        | 2.02%   |
| Phison Electronics       | 2        | 2.02%   |
| VIA Technologies         | 1        | 1.01%   |
| Silicon Motion           | 1        | 1.01%   |
| Micron Technology        | 1        | 1.01%   |
| Marvell Technology Group | 1        | 1.01%   |
| JMicron Technology       | 1        | 1.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 12.31%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 7.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 5.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 5.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 4.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 3.08%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 3.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.31%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 2.31%   |
| Nvidia MCP61 IDE                                                                        | 3        | 2.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 2.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.31%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.54%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.54%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.54%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.54%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 1.54%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.77%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 0.77%   |
| SK hynix BC511                                                                          | 1        | 0.77%   |
| Silicon Motion Non-Volatile memory controller                                           | 1        | 0.77%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.77%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.77%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.77%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.77%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.77%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 0.77%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1        | 0.77%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.77%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 60       | 60%     |
| IDE  | 23       | 23%     |
| NVMe | 12       | 12%     |
| RAID | 5        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 53       | 64.63%  |
| AMD    | 29       | 35.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 3.66%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 2        | 2.44%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 2.44%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 2        | 2.44%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 2.44%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 2.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 2.44%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 2.44%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 2.44%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2.44%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 2.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.44%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 2.44%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 2.44%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 2.44%   |
| Intel Xeon CPU X5460 @ 3.16GHz              | 1        | 1.22%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 1.22%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 1.22%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 1.22%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.22%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.22%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 1.22%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.22%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1        | 1.22%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.22%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.22%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.22%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.22%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 1.22%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 1.22%   |
| Intel Core i5-9500T CPU @ 2.20GHz           | 1        | 1.22%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.22%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.22%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.22%   |
| Intel Core i5-4670S CPU @ 3.10GHz           | 1        | 1.22%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.22%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.22%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1        | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 14       | 17.07%  |
| Intel Core i7           | 12       | 14.63%  |
| Intel Core i3           | 9        | 10.98%  |
| Intel Xeon              | 5        | 6.1%    |
| AMD Ryzen 7             | 5        | 6.1%    |
| AMD Ryzen 5             | 5        | 6.1%    |
| AMD FX                  | 4        | 4.88%   |
| Intel Pentium Dual-Core | 3        | 3.66%   |
| Intel Pentium           | 3        | 3.66%   |
| Intel Core 2 Duo        | 3        | 3.66%   |
| Other                   | 2        | 2.44%   |
| AMD Athlon II X2        | 2        | 2.44%   |
| AMD A8                  | 2        | 2.44%   |
| AMD A10                 | 2        | 2.44%   |
| Intel Pentium Dual      | 1        | 1.22%   |
| Intel Core M            | 1        | 1.22%   |
| Intel Core 2 Quad       | 1        | 1.22%   |
| AMD Ryzen Threadripper  | 1        | 1.22%   |
| AMD Ryzen 9             | 1        | 1.22%   |
| AMD Ryzen 3             | 1        | 1.22%   |
| AMD Phenom II X4        | 1        | 1.22%   |
| AMD Phenom              | 1        | 1.22%   |
| AMD Athlon 64 X2        | 1        | 1.22%   |
| AMD Athlon 64           | 1        | 1.22%   |
| AMD A4                  | 1        | 1.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 34       | 41.46%  |
| 2      | 27       | 32.93%  |
| 8      | 7        | 8.54%   |
| 6      | 7        | 8.54%   |
| 12     | 3        | 3.66%   |
| 3      | 2        | 2.44%   |
| 1      | 2        | 2.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 81       | 98.78%  |
| 2      | 1        | 1.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 42       | 51.22%  |
| 1      | 40       | 48.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 82       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 51       | 60%     |
| 0x906e9    | 5        | 5.88%   |
| 0x206a7    | 5        | 5.88%   |
| 0x306c3    | 4        | 4.71%   |
| 0x306a9    | 2        | 2.35%   |
| 0x1067a    | 2        | 2.35%   |
| 0x08701021 | 2        | 2.35%   |
| 0x08001138 | 2        | 2.35%   |
| 0x06000852 | 2        | 2.35%   |
| 0x906ed    | 1        | 1.18%   |
| 0x906ea    | 1        | 1.18%   |
| 0x90672    | 1        | 1.18%   |
| 0x106a5    | 1        | 1.18%   |
| 0x0a201016 | 1        | 1.18%   |
| 0x0800820d | 1        | 1.18%   |
| 0x0600111f | 1        | 1.18%   |
| 0x06001119 | 1        | 1.18%   |
| 0x010000c8 | 1        | 1.18%   |
| 0x01000095 | 1        | 1.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 13       | 15.85%  |
| Haswell          | 10       | 12.2%   |
| SandyBridge      | 8        | 9.76%   |
| Piledriver       | 8        | 9.76%   |
| Penryn           | 7        | 8.54%   |
| Zen              | 6        | 7.32%   |
| K10              | 5        | 6.1%    |
| Zen 2            | 4        | 4.88%   |
| Skylake          | 4        | 4.88%   |
| IvyBridge        | 3        | 3.66%   |
| Core             | 3        | 3.66%   |
| Zen+             | 2        | 2.44%   |
| Nehalem          | 2        | 2.44%   |
| K8 Hammer        | 2        | 2.44%   |
| Zen 3            | 1        | 1.22%   |
| Westmere         | 1        | 1.22%   |
| Steamroller      | 1        | 1.22%   |
| Broadwell        | 1        | 1.22%   |
| Alderlake Hybrid | 1        | 1.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 38       | 40.86%  |
| Intel  | 28       | 30.11%  |
| AMD    | 27       | 29.03%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 6.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 5.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 5.38%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 4.3%    |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 3.23%   |
| Intel HD Graphics 630                                                       | 3        | 3.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.23%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 3.23%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 3        | 3.23%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.15%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 2.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.15%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.15%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.15%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 2.15%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 2.15%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.08%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.08%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.08%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.08%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.08%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.08%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.08%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.08%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.08%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.08%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.08%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.08%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                           | 1        | 1.08%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.08%   |
| Nvidia GF119 [GeForce 510]                                                  | 1        | 1.08%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.08%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.08%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.08%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.08%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.08%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.08%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 35       | 42.68%  |
| 1 x AMD        | 23       | 28.05%  |
| 1 x Intel      | 19       | 23.17%  |
| Intel + AMD    | 2        | 2.44%   |
| AMD + Nvidia   | 2        | 2.44%   |
| Intel + Nvidia | 1        | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 63       | 75.9%   |
| Proprietary | 17       | 20.48%  |
| Unknown     | 3        | 3.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 49       | 57.65%  |
| 1.01-2.0   | 9        | 10.59%  |
| 0.51-1.0   | 9        | 10.59%  |
| 3.01-4.0   | 8        | 9.41%   |
| 7.01-8.0   | 6        | 7.06%   |
| 5.01-6.0   | 2        | 2.35%   |
| 0.01-0.5   | 2        | 2.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 14.13%  |
| Dell                 | 9        | 9.78%   |
| Acer                 | 7        | 7.61%   |
| Goldstar             | 6        | 6.52%   |
| BenQ                 | 6        | 6.52%   |
| Unknown              | 5        | 5.43%   |
| Philips              | 5        | 5.43%   |
| AOC                  | 5        | 5.43%   |
| Hewlett-Packard      | 4        | 4.35%   |
| Ancor Communications | 4        | 4.35%   |
| Toshiba              | 3        | 3.26%   |
| AUS                  | 3        | 3.26%   |
| Vizio                | 2        | 2.17%   |
| Panasonic            | 2        | 2.17%   |
| NEC Computers        | 2        | 2.17%   |
| ___                  | 1        | 1.09%   |
| ViewSonic            | 1        | 1.09%   |
| STD                  | 1        | 1.09%   |
| Sony                 | 1        | 1.09%   |
| Sceptre              | 1        | 1.09%   |
| RIS                  | 1        | 1.09%   |
| Plain Tree Systems   | 1        | 1.09%   |
| MStar                | 1        | 1.09%   |
| Lenovo               | 1        | 1.09%   |
| Insignia             | 1        | 1.09%   |
| Iiyama               | 1        | 1.09%   |
| GDH                  | 1        | 1.09%   |
| Eizo                 | 1        | 1.09%   |
| Ativa                | 1        | 1.09%   |
| ASUSTek Computer     | 1        | 1.09%   |
| AGO                  | 1        | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor XMD Mi TV 1360x768                                 | 2        | 2.06%   |
| Toshiba TV TSB0105 1920x540 708x398mm 32.0-inch                        | 2        | 2.06%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 2.06%   |
| Panasonic TV MEIA08F 1920x540                                          | 2        | 2.06%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch            | 2        | 2.06%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 2        | 2.06%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                      | 2        | 2.06%   |
| AUS LCD Monitor VG245 1920x1080                                        | 2        | 2.06%   |
| Acer X223W c ACR0011 1680x1050 473x296mm 22.0-inch                     | 2        | 2.06%   |
| ___ LCD TV ___9000 1360x768                                            | 1        | 1.03%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch              | 1        | 1.03%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                     | 1        | 1.03%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch          | 1        | 1.03%   |
| Unknown PHILCO 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.03%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                  | 1        | 1.03%   |
| Unknown LCD Monitor HRX 32H4030 1920x1080                              | 1        | 1.03%   |
| Toshiba TSB-TV TSB0205 1920x1080 531x398mm 26.1-inch                   | 1        | 1.03%   |
| STD LCD Monitor STD0001 1920x1080                                      | 1        | 1.03%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                    | 1        | 1.03%   |
| Sceptre LCD Monitor P30 2560x1080                                      | 1        | 1.03%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1        | 1.03%   |
| Samsung Electronics SyncMaster SAM064F 1920x1080 510x290mm 23.1-inch   | 1        | 1.03%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch   | 1        | 1.03%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch   | 1        | 1.03%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SAM094D 1920x1080 1210x680mm 54.6-inch | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch   | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SAM06AC 1920x1080 890x500mm 40.2-inch  | 1        | 1.03%   |
| Samsung Electronics LCD Monitor SAM03FE 1280x720                       | 1        | 1.03%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch     | 1        | 1.03%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 1        | 1.03%   |
| RIS photo24 RIS0902 1920x1080 521x293mm 23.5-inch                      | 1        | 1.03%   |
| Plain Tree Systems Monitor PTS0899 1680x1050 474x296mm 22.0-inch       | 1        | 1.03%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch               | 1        | 1.03%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                | 1        | 1.03%   |
| Philips LCD Monitor PHL 234E5 1920x1080                                | 1        | 1.03%   |
| Philips LCD Monitor PHI32PFL3404 3200x1080                             | 1        | 1.03%   |
| Philips 190C PHL0849 1280x1024 380x300mm 19.1-inch                     | 1        | 1.03%   |
| MStar Demo MST0030 1920x1080 1150x650mm 52.0-inch                      | 1        | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 47       | 52.81%  |
| 1680x1050 (WSXGA+) | 8        | 8.99%   |
| 1280x1024 (SXGA)   | 8        | 8.99%   |
| 1360x768           | 5        | 5.62%   |
| 1440x900 (WXGA+)   | 4        | 4.49%   |
| 3840x2160 (4K)     | 3        | 3.37%   |
| 1920x1200 (WUXGA)  | 3        | 3.37%   |
| 2560x1440 (QHD)    | 2        | 2.25%   |
| 2560x1080          | 2        | 2.25%   |
| 1920x540           | 2        | 2.25%   |
| Unknown            | 2        | 2.25%   |
| 3840x1080          | 1        | 1.12%   |
| 3200x1080          | 1        | 1.12%   |
| 1280x720 (HD)      | 1        | 1.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 16       | 17.2%   |
| 24      | 15       | 16.13%  |
| 27      | 11       | 11.83%  |
| 23      | 10       | 10.75%  |
| 21      | 7        | 7.53%   |
| 22      | 6        | 6.45%   |
| 19      | 6        | 6.45%   |
| 17      | 5        | 5.38%   |
| 32      | 3        | 3.23%   |
| 31      | 3        | 3.23%   |
| 72      | 2        | 2.15%   |
| 54      | 1        | 1.08%   |
| 52      | 1        | 1.08%   |
| 42      | 1        | 1.08%   |
| 41      | 1        | 1.08%   |
| 40      | 1        | 1.08%   |
| 34      | 1        | 1.08%   |
| 25      | 1        | 1.08%   |
| 20      | 1        | 1.08%   |
| 12      | 1        | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 31       | 34.83%  |
| 401-500     | 18       | 20.22%  |
| Unknown     | 16       | 17.98%  |
| 301-350     | 5        | 5.62%   |
| 701-800     | 4        | 4.49%   |
| 601-700     | 4        | 4.49%   |
| 351-400     | 3        | 3.37%   |
| 1501-2000   | 2        | 2.25%   |
| 1001-1500   | 2        | 2.25%   |
| 901-1000    | 2        | 2.25%   |
| 801-900     | 1        | 1.12%   |
| 201-300     | 1        | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 47       | 55.95%  |
| 16/10   | 12       | 14.29%  |
| Unknown | 12       | 14.29%  |
| 5/4     | 8        | 9.52%   |
| 32/9    | 2        | 2.38%   |
| 4/3     | 1        | 1.19%   |
| 3/2     | 1        | 1.19%   |
| 21/9    | 1        | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 31.91%  |
| Unknown        | 16       | 17.02%  |
| 301-350        | 11       | 11.7%   |
| 151-200        | 10       | 10.64%  |
| 351-500        | 7        | 7.45%   |
| 251-300        | 7        | 7.45%   |
| 141-150        | 5        | 5.32%   |
| More than 1000 | 4        | 4.26%   |
| 501-1000       | 3        | 3.19%   |
| 71-80          | 1        | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 50       | 60.24%  |
| Unknown | 16       | 19.28%  |
| 101-120 | 8        | 9.64%   |
| 1-50    | 6        | 7.23%   |
| 161-240 | 2        | 2.41%   |
| 121-160 | 1        | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 60       | 69.77%  |
| 2     | 20       | 23.26%  |
| 0     | 4        | 4.65%   |
| 3     | 2        | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 57       | 37.75%  |
| Intel                           | 24       | 15.89%  |
| Ralink Technology               | 11       | 7.28%   |
| Qualcomm Atheros                | 11       | 7.28%   |
| Broadcom                        | 8        | 5.3%    |
| TP-Link                         | 4        | 2.65%   |
| Microsoft                       | 4        | 2.65%   |
| Samsung Electronics             | 3        | 1.99%   |
| Qualcomm Atheros Communications | 3        | 1.99%   |
| Nvidia                          | 3        | 1.99%   |
| D-Link System                   | 3        | 1.99%   |
| Ralink                          | 2        | 1.32%   |
| OnePlus Technology (Shenzhen)   | 2        | 1.32%   |
| NetGear                         | 2        | 1.32%   |
| Broadcom Limited                | 2        | 1.32%   |
| ASUSTek Computer                | 2        | 1.32%   |
| vivo                            | 1        | 0.66%   |
| Mercucys                        | 1        | 0.66%   |
| MediaTek                        | 1        | 0.66%   |
| Marvell Technology Group        | 1        | 0.66%   |
| Linksys                         | 1        | 0.66%   |
| Lenovo                          | 1        | 0.66%   |
| ICS Advent                      | 1        | 0.66%   |
| Huawei Technologies             | 1        | 0.66%   |
| Gemtek                          | 1        | 0.66%   |
| D-Link                          | 1        | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 44       | 26.19%  |
| Realtek 802.11n                                                    | 5        | 2.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 4        | 2.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 4        | 2.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                              | 4        | 2.38%   |
| Ralink MT7601U Wireless Adapter                                    | 4        | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 4        | 2.38%   |
| Intel I211 Gigabit Network Connection                              | 4        | 2.38%   |
| Intel Ethernet Connection (2) I219-V                               | 4        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 4        | 2.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 3        | 1.79%   |
| Qualcomm Atheros AR9271 802.11n                                    | 3        | 1.79%   |
| Nvidia MCP61 Ethernet                                              | 3        | 1.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                 | 3        | 1.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 2        | 1.19%   |
| TP-Link Archer T4U ver.3                                           | 2        | 1.19%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 2        | 1.19%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 2        | 1.19%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:514355CC                         | 2        | 1.19%   |
| Microsoft Xbox 360 Wireless Adapter                                | 2        | 1.19%   |
| Intel Ethernet Connection I217-V                                   | 2        | 1.19%   |
| Intel Ethernet Connection I217-LM                                  | 2        | 1.19%   |
| Intel 82579V Gigabit Network Connection                            | 2        | 1.19%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                    | 2        | 1.19%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 2        | 1.19%   |
| vivo 1806                                                          | 1        | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1        | 0.6%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                | 1        | 0.6%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 1        | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter           | 1        | 0.6%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 1        | 0.6%    |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)          | 1        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 1        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                         | 1        | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                  | 1        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter              | 1        | 0.6%    |
| Ralink RT5572 Wireless Adapter                                     | 1        | 0.6%    |
| Ralink RT5372 Wireless Adapter                                     | 1        | 0.6%    |
| Ralink RT5370 Wireless Adapter                                     | 1        | 0.6%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                               | 1        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 19       | 26.39%  |
| Ralink Technology               | 11       | 15.28%  |
| Qualcomm Atheros                | 8        | 11.11%  |
| Broadcom                        | 6        | 8.33%   |
| Intel                           | 5        | 6.94%   |
| TP-Link                         | 4        | 5.56%   |
| Microsoft                       | 4        | 5.56%   |
| Qualcomm Atheros Communications | 3        | 4.17%   |
| Ralink                          | 2        | 2.78%   |
| NetGear                         | 2        | 2.78%   |
| ASUSTek Computer                | 2        | 2.78%   |
| Mercucys                        | 1        | 1.39%   |
| Linksys                         | 1        | 1.39%   |
| Gemtek                          | 1        | 1.39%   |
| D-Link System                   | 1        | 1.39%   |
| D-Link                          | 1        | 1.39%   |
| Broadcom Limited                | 1        | 1.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek 802.11n                                                         | 5        | 6.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4        | 5.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 4        | 5.48%   |
| Ralink MT7601U Wireless Adapter                                         | 4        | 5.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4        | 5.48%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3        | 4.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3        | 4.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2        | 2.74%   |
| TP-Link Archer T4U ver.3                                                | 2        | 2.74%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2        | 2.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2        | 2.74%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2        | 2.74%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 2        | 2.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1        | 1.37%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1        | 1.37%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 1.37%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.37%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1        | 1.37%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)               | 1        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1        | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 1.37%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 1.37%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 1.37%   |
| Ralink RT5370 Wireless Adapter                                          | 1        | 1.37%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 1        | 1.37%   |
| Ralink RT2500 Wireless 802.11bg                                         | 1        | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.37%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1        | 1.37%   |
| NetGear WPN111 RangeMax Wireless USB 2.0 Adapter                        | 1        | 1.37%   |
| NetGear WG111T                                                          | 1        | 1.37%   |
| Microsoft Xbox360 Wireless Networking Adapter                           | 1        | 1.37%   |
| Microsoft Xbox360 Wireless N Networking Adapter [Atheros AR7010+AR9280] | 1        | 1.37%   |
| Mercucys 802.11n NIC                                                    | 1        | 1.37%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU]  | 1        | 1.37%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]     | 1        | 1.37%   |
| Intel Wireless 7265                                                     | 1        | 1.37%   |
| Intel Wireless 7260                                                     | 1        | 1.37%   |
| Intel Wireless 3160                                                     | 1        | 1.37%   |
| Intel Wi-Fi 6 AX200                                                     | 1        | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1        | 1.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 50       | 55.56%  |
| Intel                    | 21       | 23.33%  |
| Qualcomm Atheros         | 4        | 4.44%   |
| Samsung Electronics      | 3        | 3.33%   |
| Nvidia                   | 3        | 3.33%   |
| D-Link System            | 2        | 2.22%   |
| Broadcom                 | 2        | 2.22%   |
| vivo                     | 1        | 1.11%   |
| MediaTek                 | 1        | 1.11%   |
| Marvell Technology Group | 1        | 1.11%   |
| ICS Advent               | 1        | 1.11%   |
| Broadcom Limited         | 1        | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44       | 48.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 4.4%    |
| Intel I211 Gigabit Network Connection                             | 4        | 4.4%    |
| Intel Ethernet Connection (2) I219-V                              | 4        | 4.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 4.4%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3        | 3.3%    |
| Nvidia MCP61 Ethernet                                             | 3        | 3.3%    |
| Intel Ethernet Connection I217-V                                  | 2        | 2.2%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.2%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.2%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 2.2%    |
| vivo 1806                                                         | 1        | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.1%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.1%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.1%    |
| MediaTek TECNO F1                                                 | 1        | 1.1%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.1%    |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.1%    |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.1%    |
| ICS Advent 10/100M LAN                                            | 1        | 1.1%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.1%    |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1        | 1.1%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 80       | 55.94%  |
| WiFi     | 59       | 41.26%  |
| Unknown  | 4        | 2.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 53       | 58.89%  |
| WiFi     | 35       | 38.89%  |
| Unknown  | 2        | 2.22%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 63.86%  |
| 2     | 24       | 28.92%  |
| 3     | 3        | 3.61%   |
| 0     | 2        | 2.41%   |
| 4     | 1        | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 71       | 84.52%  |
| Yes  | 13       | 15.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 7        | 30.43%  |
| Intel                           | 5        | 21.74%  |
| Qualcomm Atheros Communications | 4        | 17.39%  |
| Realtek Semiconductor           | 2        | 8.7%    |
| Toshiba                         | 1        | 4.35%   |
| IMC Networks                    | 1        | 4.35%   |
| Dell                            | 1        | 4.35%   |
| ASUSTek Computer                | 1        | 4.35%   |
| Apple                           | 1        | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 7        | 30.43%  |
| Qualcomm Atheros  Bluetooth Device                    | 4        | 17.39%  |
| Intel Bluetooth wireless interface                    | 3        | 13.04%  |
| Realtek Bluetooth Radio                               | 2        | 8.7%    |
| Toshiba Atheros AR3012 Bluetooth                      | 1        | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 4.35%   |
| Intel AX200 Bluetooth                                 | 1        | 4.35%   |
| IMC Networks Bluetooth Device                         | 1        | 4.35%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1        | 4.35%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 4.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 52       | 37.96%  |
| AMD                    | 37       | 27.01%  |
| Nvidia                 | 35       | 25.55%  |
| C-Media Electronics    | 4        | 2.92%   |
| Logitech               | 2        | 1.46%   |
| Yamaha                 | 1        | 0.73%   |
| Tenx Technology        | 1        | 0.73%   |
| SteelSeries ApS        | 1        | 0.73%   |
| Samson Technologies    | 1        | 0.73%   |
| JMTek                  | 1        | 0.73%   |
| GYROCOM C&C            | 1        | 0.73%   |
| Generalplus Technology | 1        | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10       | 6.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 5.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8        | 4.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 4.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 7        | 4.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 6        | 3.66%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 3.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 3.05%   |
| AMD FCH Azalia Controller                                                         | 5        | 3.05%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 2.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 2.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4        | 2.44%   |
| AMD Starship/Matisse HD Audio Controller                                          | 4        | 2.44%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 1.83%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.83%   |
| Nvidia GK104 HDMI Audio Controller                                                | 3        | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 1.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 1.83%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 1.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.83%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 1.22%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 1.22%   |
| Nvidia GF106 High Definition Audio Controller                                     | 2        | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 1.22%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 2        | 1.22%   |
| C-Media Electronics CM108 Audio Controller                                        | 2        | 1.22%   |
| AMD Trinity HDMI Audio Controller                                                 | 2        | 1.22%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 1.22%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 2        | 1.22%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 1.22%   |
| Yamaha Steinberg UR22mkII                                                         | 1        | 0.61%   |
| Tenx Technology USB AUDIO                                                         | 1        | 0.61%   |
| SteelSeries ApS SteelSeries GameDAC                                               | 1        | 0.61%   |
| Samson Technologies G-Track Pro microphone                                        | 1        | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 0.61%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 27.08%  |
| Corsair             | 7        | 14.58%  |
| Kingston            | 6        | 12.5%   |
| Crucial             | 5        | 10.42%  |
| SK hynix            | 4        | 8.33%   |
| Samsung Electronics | 3        | 6.25%   |
| G.Skill             | 3        | 6.25%   |
| Micron Technology   | 2        | 4.17%   |
| Unifosa             | 1        | 2.08%   |
| Silicon Power       | 1        | 2.08%   |
| S                   | 1        | 2.08%   |
| Nanya Technology    | 1        | 2.08%   |
| A-DATA Technology   | 1        | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 2        | 3.92%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 2        | 3.92%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s      | 2        | 3.92%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 1.96%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s               | 1        | 1.96%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                  | 1        | 1.96%   |
| Unknown RAM Module 4GB DIMM 800MT/s                        | 1        | 1.96%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 1.96%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                       | 1        | 1.96%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 1.96%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 1        | 1.96%   |
| Unknown RAM Module 2GB DIMM                                | 1        | 1.96%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                | 1        | 1.96%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 1        | 1.96%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 1.96%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                 | 1        | 1.96%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                     | 1        | 1.96%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 1.96%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s       | 1        | 1.96%   |
| Silicon Power RAM SP016GBLFU266B02 16GB DIMM DDR4 2667MT/s | 1        | 1.96%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s        | 1        | 1.96%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s     | 1        | 1.96%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s     | 1        | 1.96%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.96%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                        | 1        | 1.96%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s         | 1        | 1.96%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 1        | 1.96%   |
| Micron RAM 16JTF51264AZ-1G6K1 4GB DIMM DDR3 1600MT/s       | 1        | 1.96%   |
| Kingston RAM KHYXPX-HYJ 8GB SODIMM DDR4 2667MT/s           | 1        | 1.96%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s        | 1        | 1.96%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s     | 1        | 1.96%   |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s        | 1        | 1.96%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 1.96%   |
| Kingston RAM 9905678-005.A00G 8GB DIMM DDR4 2400MT/s       | 1        | 1.96%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s  | 1        | 1.96%   |
| G.Skill RAM F4-2400C15-8GIS 8GB DIMM DDR4 2400MT/s         | 1        | 1.96%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s      | 1        | 1.96%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s     | 1        | 1.96%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s  | 1        | 1.96%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s      | 1        | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 19       | 44.19%  |
| DDR4    | 15       | 34.88%  |
| Unknown | 4        | 9.3%    |
| DDR2    | 3        | 6.98%   |
| SDRAM   | 2        | 4.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 40       | 95.24%  |
| SODIMM | 2        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 19       | 40.43%  |
| 4096  | 14       | 29.79%  |
| 2048  | 8        | 17.02%  |
| 16384 | 4        | 8.51%   |
| 1024  | 2        | 4.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 12       | 25.53%  |
| 2400    | 5        | 10.64%  |
| 3200    | 4        | 8.51%   |
| 1333    | 4        | 8.51%   |
| 3600    | 3        | 6.38%   |
| 2667    | 3        | 6.38%   |
| Unknown | 3        | 6.38%   |
| 1867    | 2        | 4.26%   |
| 800     | 2        | 4.26%   |
| 3466    | 1        | 2.13%   |
| 3100    | 1        | 2.13%   |
| 2666    | 1        | 2.13%   |
| 2200    | 1        | 2.13%   |
| 2133    | 1        | 2.13%   |
| 1866    | 1        | 2.13%   |
| 1067    | 1        | 2.13%   |
| 1066    | 1        | 2.13%   |
| 400     | 1        | 2.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Seiko Epson     | 1        | 33.33%  |
| Hewlett-Packard | 1        | 33.33%  |
| Dymo-CoStar     | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Seiko Epson L120 Series      | 1        | 33.33%  |
| HP OfficeJet Pro 7720 series | 1        | 33.33%  |
| Dymo-CoStar LabelWriter 450  | 1        | 33.33%  |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 5        | 33.33%  |
| Microdia            | 2        | 13.33%  |
| Creative Technology | 2        | 13.33%  |
| Teslong Camera      | 1        | 6.67%   |
| Razer USA           | 1        | 6.67%   |
| LG Electronics      | 1        | 6.67%   |
| Jieli Technology    | 1        | 6.67%   |
| IMC Networks        | 1        | 6.67%   |
| Apple               | 1        | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech HD Webcam C615                               | 2        | 13.33%  |
| Creative Live! Cam Sync HD [VF0770]                   | 2        | 13.33%  |
| Teslong Camera                                        | 1        | 6.67%   |
| Razer USA Gaming Webcam [Kiyo]                        | 1        | 6.67%   |
| Microdia Webcam Vitade AF                             | 1        | 6.67%   |
| Microdia PC Microscope camera                         | 1        | 6.67%   |
| Logitech Webcam C270                                  | 1        | 6.67%   |
| Logitech HD Pro Webcam C920                           | 1        | 6.67%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 6.67%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 6.67%   |
| Jieli USB PHY 2.0                                     | 1        | 6.67%   |
| IMC Networks XHC Camera                               | 1        | 6.67%   |
| Apple iPhone 5/5C/5S/6/SE                             | 1        | 6.67%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 62       | 73.81%  |
| 1     | 19       | 22.62%  |
| 2     | 3        | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 12       | 52.17%  |
| Graphics card            | 6        | 26.09%  |
| Storage/raid             | 1        | 4.35%   |
| Net/ethernet             | 1        | 4.35%   |
| Multimedia controller    | 1        | 4.35%   |
| Communication controller | 1        | 4.35%   |
| Camera                   | 1        | 4.35%   |

