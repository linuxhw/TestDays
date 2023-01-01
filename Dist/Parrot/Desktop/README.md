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

Total: 123

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| HP            | 3397                    | [33ba62be32](https://linux-hardware.org/?probe=33ba62be32) | Dec 10, 2022 |
| ASUSTek       | PRIME B450M-K           | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
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
| Parrot 5.0  | 26       | 29.55%  |
| Parrot 4.11 | 22       | 25%     |
| Parrot 4.10 | 14       | 15.91%  |
| Parrot 4.9  | 9        | 10.23%  |
| Parrot 5.1  | 8        | 9.09%   |
| Parrot 4.8  | 6        | 6.82%   |
| Parrot 4.7  | 3        | 3.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Parrot | 84       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.0-12parrot1-amd64   | 14       | 15.38%  |
| 5.14.0-9parrot1-amd64    | 13       | 14.29%  |
| 5.5.0-1parrot1-amd64     | 12       | 13.19%  |
| 6.0.0-2parrot1-amd64     | 6        | 6.59%   |
| 5.7.0-2parrot2-amd64     | 6        | 6.59%   |
| 5.15.0-15parrot1-amd64   | 6        | 6.59%   |
| 5.10.0-6parrot1-amd64    | 6        | 6.59%   |
| 5.8.0-2parrot1-amd64     | 3        | 3.3%    |
| 5.4.0-4parrot1-amd64     | 3        | 3.3%    |
| 5.10.0-8parrot1-amd64    | 3        | 3.3%    |
| 5.9.0-2parrot1-amd64     | 2        | 2.2%    |
| 5.4.0-2parrot1-amd64     | 2        | 2.2%    |
| 5.3.0-3parrot3-amd64     | 2        | 2.2%    |
| 5.18.0-1parrot1-amd64    | 2        | 2.2%    |
| 5.18.0-14parrot1-amd64   | 2        | 2.2%    |
| 5.14.0-2parrot1-amd64    | 2        | 2.2%    |
| 5.10.0-3parrot1-amd64    | 2        | 2.2%    |
| 5.8.0-1parrot1-amd64     | 1        | 1.1%    |
| 5.6.0-2parrot1-amd64     | 1        | 1.1%    |
| 5.4.0-3parrot1-amd64     | 1        | 1.1%    |
| 5.16.0-12parrot1-686-pae | 1        | 1.1%    |
| 5.10.0-5parrot1-amd64    | 1        | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16.0  | 15       | 16.67%  |
| 5.14.0  | 14       | 15.56%  |
| 5.5.0   | 12       | 13.33%  |
| 5.10.0  | 12       | 13.33%  |
| 6.0.0   | 6        | 6.67%   |
| 5.7.0   | 6        | 6.67%   |
| 5.4.0   | 6        | 6.67%   |
| 5.15.0  | 6        | 6.67%   |
| 5.8.0   | 4        | 4.44%   |
| 5.18.0  | 4        | 4.44%   |
| 5.9.0   | 2        | 2.22%   |
| 5.3.0   | 2        | 2.22%   |
| 5.6.0   | 1        | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 15       | 16.67%  |
| 5.14    | 14       | 15.56%  |
| 5.5     | 12       | 13.33%  |
| 5.10    | 12       | 13.33%  |
| 6.0     | 6        | 6.67%   |
| 5.7     | 6        | 6.67%   |
| 5.4     | 6        | 6.67%   |
| 5.15    | 6        | 6.67%   |
| 5.8     | 4        | 4.44%   |
| 5.18    | 4        | 4.44%   |
| 5.9     | 2        | 2.22%   |
| 5.3     | 2        | 2.22%   |
| 5.6     | 1        | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 83       | 98.81%  |
| i686   | 1        | 1.19%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 60       | 68.97%  |
| KDE5    | 11       | 12.64%  |
| KDE     | 7        | 8.05%   |
| XFCE    | 4        | 4.6%    |
| Unknown | 3        | 3.45%   |
| GNOME   | 2        | 2.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 82       | 97.62%  |
| Wayland | 2        | 2.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 35       | 40.23%  |
| Unknown | 29       | 33.33%  |
| TDM     | 18       | 20.69%  |
| SDDM    | 3        | 3.45%   |
| GDM     | 2        | 2.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 48       | 57.14%  |
| ru_RU | 5        | 5.95%   |
| pt_BR | 3        | 3.57%   |
| fr_FR | 3        | 3.57%   |
| es_ES | 3        | 3.57%   |
| en_IN | 3        | 3.57%   |
| de_DE | 3        | 3.57%   |
| pl_PL | 2        | 2.38%   |
| en_HK | 2        | 2.38%   |
| cs_CZ | 2        | 2.38%   |
| ru_UA | 1        | 1.19%   |
| mk_MK | 1        | 1.19%   |
| it_IT | 1        | 1.19%   |
| es_MX | 1        | 1.19%   |
| en_GB | 1        | 1.19%   |
| en_DK | 1        | 1.19%   |
| en_CA | 1        | 1.19%   |
| en_AU | 1        | 1.19%   |
| de_AT | 1        | 1.19%   |
| an_ES | 1        | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 69       | 79.31%  |
| EFI  | 18       | 20.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 68       | 79.07%  |
| Ext4    | 12       | 13.95%  |
| Xfs     | 3        | 3.49%   |
| Overlay | 3        | 3.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 46       | 52.27%  |
| GPT     | 25       | 28.41%  |
| MBR     | 17       | 19.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 72       | 82.76%  |
| Yes       | 15       | 17.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 58.33%  |
| Yes       | 35       | 41.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 27       | 32.14%  |
| Gigabyte Technology | 12       | 14.29%  |
| Dell                | 10       | 11.9%   |
| Hewlett-Packard     | 8        | 9.52%   |
| MSI                 | 4        | 4.76%   |
| Foxconn             | 3        | 3.57%   |
| ASRock              | 3        | 3.57%   |
| Acer                | 3        | 3.57%   |
| Lenovo              | 2        | 2.38%   |
| ECS                 | 2        | 2.38%   |
| Unknown             | 2        | 2.38%   |
| ZOTAC               | 1        | 1.19%   |
| Wistron             | 1        | 1.19%   |
| Positivo            | 1        | 1.19%   |
| Gateway             | 1        | 1.19%   |
| Daewoo Lucoms       | 1        | 1.19%   |
| Biostar             | 1        | 1.19%   |
| Apple               | 1        | 1.19%   |
| Alienware           | 1        | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Unknown                                   | 3        | 3.57%   |
| HP ProDesk 600 G1 SFF                     | 2        | 2.38%   |
| Gigabyte AX370-Gaming                     | 2        | 2.38%   |
| Foxconn s5710t                            | 2        | 2.38%   |
| Dell Inspiron 5676                        | 2        | 2.38%   |
| ASUS M5A78L-M/USB3                        | 2        | 2.38%   |
| ASUS H110I-PLUS                           | 2        | 2.38%   |
| ASUS Basic 3221BM                         | 2        | 2.38%   |
| Wistron FMVDD2A0H0                        | 1        | 1.19%   |
| Positivo POS-PIG43BC                      | 1        | 1.19%   |
| MSI MS-7C02                               | 1        | 1.19%   |
| MSI MS-7A69                               | 1        | 1.19%   |
| MSI MS-7A34                               | 1        | 1.19%   |
| MSI MS-7529                               | 1        | 1.19%   |
| Lenovo H535 10117                         | 1        | 1.19%   |
| Lenovo H530 10130                         | 1        | 1.19%   |
| HP Victus by 15L Gaming Desktop TG02-0xxx | 1        | 1.19%   |
| HP Compaq Pro 6305 MT                     | 1        | 1.19%   |
| HP Compaq Pro 6300 MT                     | 1        | 1.19%   |
| HP Compaq Elite 8300 SFF                  | 1        | 1.19%   |
| HP Compaq 8200 Elite SFF PC               | 1        | 1.19%   |
| HP Compaq 6005 Pro MT PC                  | 1        | 1.19%   |
| Gigabyte Z97N-WIFI                        | 1        | 1.19%   |
| Gigabyte M61SME-S2                        | 1        | 1.19%   |
| Gigabyte H61M-USB3H                       | 1        | 1.19%   |
| Gigabyte H61M-S2PT                        | 1        | 1.19%   |
| Gigabyte H370M-DS3H                       | 1        | 1.19%   |
| Gigabyte H110M-H DDR3                     | 1        | 1.19%   |
| Gigabyte GA-880GM-D2H                     | 1        | 1.19%   |
| Gigabyte B450M DS3H                       | 1        | 1.19%   |
| Gigabyte A320M-S2H                        | 1        | 1.19%   |
| Gigabyte 970A-DS3P                        | 1        | 1.19%   |
| Gateway SX2855                            | 1        | 1.19%   |
| Foxconn 45CMX/45GMX/45CMX-K               | 1        | 1.19%   |
| ECS GV460AA-ABA a6217c                    | 1        | 1.19%   |
| ECS A740GM-M                              | 1        | 1.19%   |
| Dell XPS 8930                             | 1        | 1.19%   |
| Dell Vostro 200                           | 1        | 1.19%   |
| Dell Studio XPS 9100                      | 1        | 1.19%   |
| Dell OptiPlex 990                         | 1        | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq             | 5        | 5.95%   |
| Dell OptiPlex         | 5        | 5.95%   |
| ASUS PRIME            | 4        | 4.76%   |
| Unknown               | 3        | 3.57%   |
| HP ProDesk            | 2        | 2.38%   |
| Gigabyte AX370-Gaming | 2        | 2.38%   |
| Foxconn s5710t        | 2        | 2.38%   |
| Dell Inspiron         | 2        | 2.38%   |
| ASUS ROG              | 2        | 2.38%   |
| ASUS M5A78L-M         | 2        | 2.38%   |
| ASUS H110I-PLUS       | 2        | 2.38%   |
| ASUS Basic            | 2        | 2.38%   |
| Acer Aspire           | 2        | 2.38%   |
| Wistron FMVDD2A0H0    | 1        | 1.19%   |
| Positivo POS-PIG43BC  | 1        | 1.19%   |
| MSI MS-7C02           | 1        | 1.19%   |
| MSI MS-7A69           | 1        | 1.19%   |
| MSI MS-7A34           | 1        | 1.19%   |
| MSI MS-7529           | 1        | 1.19%   |
| Lenovo H535           | 1        | 1.19%   |
| Lenovo H530           | 1        | 1.19%   |
| HP Victus             | 1        | 1.19%   |
| Gigabyte Z97N-WIFI    | 1        | 1.19%   |
| Gigabyte M61SME-S2    | 1        | 1.19%   |
| Gigabyte H61M-USB3H   | 1        | 1.19%   |
| Gigabyte H61M-S2PT    | 1        | 1.19%   |
| Gigabyte H370M-DS3H   | 1        | 1.19%   |
| Gigabyte H110M-H      | 1        | 1.19%   |
| Gigabyte GA-880GM-D2H | 1        | 1.19%   |
| Gigabyte B450M        | 1        | 1.19%   |
| Gigabyte A320M-S2H    | 1        | 1.19%   |
| Gigabyte 970A-DS3P    | 1        | 1.19%   |
| Gateway SX2855        | 1        | 1.19%   |
| Foxconn 45CMX         | 1        | 1.19%   |
| ECS GV460AA-ABA       | 1        | 1.19%   |
| ECS A740GM-M          | 1        | 1.19%   |
| Dell XPS              | 1        | 1.19%   |
| Dell Vostro           | 1        | 1.19%   |
| Dell Studio           | 1        | 1.19%   |
| Daewoo Lucoms OEM     | 1        | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 11       | 13.1%   |
| 2011 | 10       | 11.9%   |
| 2018 | 8        | 9.52%   |
| 2016 | 8        | 9.52%   |
| 2010 | 8        | 9.52%   |
| 2012 | 7        | 8.33%   |
| 2017 | 6        | 7.14%   |
| 2015 | 5        | 5.95%   |
| 2007 | 5        | 5.95%   |
| 2019 | 4        | 4.76%   |
| 2014 | 3        | 3.57%   |
| 2009 | 3        | 3.57%   |
| 2021 | 2        | 2.38%   |
| 2020 | 2        | 2.38%   |
| 2022 | 1        | 1.19%   |
| 2008 | 1        | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 84       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 84       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 84       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 24       | 27.59%  |
| 4.01-8.0    | 18       | 20.69%  |
| 8.01-16.0   | 18       | 20.69%  |
| 3.01-4.0    | 12       | 13.79%  |
| 32.01-64.0  | 10       | 11.49%  |
| 1.01-2.0    | 3        | 3.45%   |
| 24.01-32.0  | 1        | 1.15%   |
| 64.01-256.0 | 1        | 1.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 30       | 34.09%  |
| 2.01-3.0   | 26       | 29.55%  |
| 4.01-8.0   | 14       | 15.91%  |
| 3.01-4.0   | 9        | 10.23%  |
| 0.51-1.0   | 6        | 6.82%   |
| 8.01-16.0  | 2        | 2.27%   |
| 16.01-24.0 | 1        | 1.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 31       | 35.63%  |
| 1      | 31       | 35.63%  |
| 3      | 13       | 14.94%  |
| 4      | 8        | 9.2%    |
| 5      | 3        | 3.45%   |
| 6      | 1        | 1.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 69.77%  |
| Yes       | 26       | 30.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 82       | 97.62%  |
| No        | 2        | 2.38%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 59       | 68.6%   |
| No        | 27       | 31.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 72.62%  |
| Yes       | 23       | 27.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Desktops | Percent |
|-----------------|----------|---------|
| USA             | 27       | 31.76%  |
| Germany         | 7        | 8.24%   |
| Brazil          | 6        | 7.06%   |
| Spain           | 4        | 4.71%   |
| Russia          | 4        | 4.71%   |
| India           | 4        | 4.71%   |
| Netherlands     | 3        | 3.53%   |
| Italy           | 2        | 2.35%   |
| Hong Kong       | 2        | 2.35%   |
| France          | 2        | 2.35%   |
| Czechia         | 2        | 2.35%   |
| Canada          | 2        | 2.35%   |
| Austria         | 2        | 2.35%   |
| Vietnam         | 1        | 1.18%   |
| Ukraine         | 1        | 1.18%   |
| UK              | 1        | 1.18%   |
| Turkey          | 1        | 1.18%   |
| Romania         | 1        | 1.18%   |
| Poland          | 1        | 1.18%   |
| Philippines     | 1        | 1.18%   |
| Pakistan        | 1        | 1.18%   |
| North Macedonia | 1        | 1.18%   |
| Morocco         | 1        | 1.18%   |
| Mongolia        | 1        | 1.18%   |
| Mexico          | 1        | 1.18%   |
| Egypt           | 1        | 1.18%   |
| Denmark         | 1        | 1.18%   |
| Bulgaria        | 1        | 1.18%   |
| Belgium         | 1        | 1.18%   |
| Australia       | 1        | 1.18%   |
| Algeria         | 1        | 1.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Indianapolis         | 3        | 3.45%   |
| Vienna               | 2        | 2.3%    |
| Uherské Hradiště  | 2        | 2.3%    |
| Ngau Wu Tok          | 2        | 2.3%    |
| Newburgh             | 2        | 2.3%    |
| Madrid               | 2        | 2.3%    |
| Eugene               | 2        | 2.3%    |
| Warsaw               | 1        | 1.15%   |
| Viby J               | 1        | 1.15%   |
| Vapi                 | 1        | 1.15%   |
| Valencia             | 1        | 1.15%   |
| Ulan Bator           | 1        | 1.15%   |
| Terrace              | 1        | 1.15%   |
| Tangier              | 1        | 1.15%   |
| Sydney               | 1        | 1.15%   |
| Springfield          | 1        | 1.15%   |
| Sorocaba             | 1        | 1.15%   |
| Sofia                | 1        | 1.15%   |
| Skopje               | 1        | 1.15%   |
| Sao Paulo            | 1        | 1.15%   |
| Sao Joao de Meriti   | 1        | 1.15%   |
| Santa Maria          | 1        | 1.15%   |
| Saint Paul           | 1        | 1.15%   |
| Rawalpindi           | 1        | 1.15%   |
| Portsmouth           | 1        | 1.15%   |
| Portland             | 1        | 1.15%   |
| Point Pleasant Beach | 1        | 1.15%   |
| Pensacola            | 1        | 1.15%   |
| Ordu                 | 1        | 1.15%   |
| Orange Park          | 1        | 1.15%   |
| Nuremberg            | 1        | 1.15%   |
| Nizhniy Novgorod     | 1        | 1.15%   |
| New Delhi            | 1        | 1.15%   |
| Nam Định          | 1        | 1.15%   |
| Naaldwijk            | 1        | 1.15%   |
| Morelia              | 1        | 1.15%   |
| Montreal             | 1        | 1.15%   |
| Monserrato           | 1        | 1.15%   |
| Milton               | 1        | 1.15%   |
| Milan                | 1        | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 36       | 51     | 23.08%  |
| WDC                 | 34       | 48     | 21.79%  |
| Samsung Electronics | 16       | 25     | 10.26%  |
| Toshiba             | 13       | 13     | 8.33%   |
| Kingston            | 9        | 11     | 5.77%   |
| SanDisk             | 7        | 10     | 4.49%   |
| Hitachi             | 6        | 7      | 3.85%   |
| Crucial             | 4        | 4      | 2.56%   |
| Unknown             | 3        | 3      | 1.92%   |
| JMicron Technology  | 3        | 3      | 1.92%   |
| SPCC                | 2        | 2      | 1.28%   |
| SK hynix            | 2        | 3      | 1.28%   |
| Phison              | 2        | 2      | 1.28%   |
| LITEONIT            | 2        | 2      | 1.28%   |
| Fujitsu             | 2        | 2      | 1.28%   |
| China               | 2        | 5      | 1.28%   |
| Team                | 1        | 2      | 0.64%   |
| Silicon Motion      | 1        | 1      | 0.64%   |
| PNY                 | 1        | 1      | 0.64%   |
| Plextor             | 1        | 1      | 0.64%   |
| OCZ                 | 1        | 1      | 0.64%   |
| Micron Technology   | 1        | 1      | 0.64%   |
| Intenso             | 1        | 1      | 0.64%   |
| HGST                | 1        | 1      | 0.64%   |
| FORESEE             | 1        | 1      | 0.64%   |
| Corsair             | 1        | 1      | 0.64%   |
| Apacer              | 1        | 1      | 0.64%   |
| AMD                 | 1        | 1      | 0.64%   |
| A-DATA Technology   | 1        | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA200 2TB             | 5        | 2.75%   |
| WDC WD5000AADS-00S9B0 500GB        | 3        | 1.65%   |
| Seagate ST31000528AS 1TB           | 3        | 1.65%   |
| Seagate ST250DM000-1BD141 250GB    | 3        | 1.65%   |
| Seagate Expansion 4TB              | 3        | 1.65%   |
| Samsung SSD 860 EVO 500GB          | 3        | 1.65%   |
| Samsung SSD 860 EVO 250GB          | 3        | 1.65%   |
| Kingston SA400S37480G 480GB SSD    | 3        | 1.65%   |
| Kingston SA400S37240G 240GB SSD    | 3        | 1.65%   |
| JMicron Generic 240GB SSD          | 3        | 1.65%   |
| WDC WD2500JS-75MHB0 250GB          | 2        | 1.1%    |
| WDC WD2500AAKX-753CA1 250GB        | 2        | 1.1%    |
| WDC WD10EZRX-00L4HB0 1TB           | 2        | 1.1%    |
| WDC WD10EZEX-00BN5A0 1TB           | 2        | 1.1%    |
| WDC WD10EARS-00Y5B1 1TB            | 2        | 1.1%    |
| Unknown SD/MMC/MS PRO 64GB         | 2        | 1.1%    |
| Toshiba DT01ACA100 1TB             | 2        | 1.1%    |
| Toshiba DT01ACA050 500GB           | 2        | 1.1%    |
| Seagate ST500VT000-1DK142 500GB    | 2        | 1.1%    |
| Seagate ST500LM000-SSHD-8GB        | 2        | 1.1%    |
| Seagate ST2000LM003 HN-M201RAD 2TB | 2        | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 1.1%    |
| Seagate ST1000DM003-1CH162 1TB     | 2        | 1.1%    |
| SanDisk SD6SF1M128G1022I 128GB SSD | 2        | 1.1%    |
| Samsung SSD 840 Series 250GB       | 2        | 1.1%    |
| Fujitsu F300 480GB                 | 2        | 1.1%    |
| WDC WDS500G2B0C-00PXH0 500GB       | 1        | 0.55%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1        | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 0.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1        | 0.55%   |
| WDC WDS120G1G0B-00RC30 120GB SSD   | 1        | 0.55%   |
| WDC WDBRPG5000ANC-WRSN 500GB       | 1        | 0.55%   |
| WDC WDBNCE0010PNC 1TB SSD          | 1        | 0.55%   |
| WDC WD800JD-75MSA3 80GB            | 1        | 0.55%   |
| WDC WD800AAJS-75M0A0 80GB          | 1        | 0.55%   |
| WDC WD60EFAX-68SHWN0 6TB           | 1        | 0.55%   |
| WDC WD5002ABYS-01B1B0 500GB        | 1        | 0.55%   |
| WDC WD5000AAKS-75V0A0 500GB        | 1        | 0.55%   |
| WDC WD5000AACS-00ZUB0 500GB        | 1        | 0.55%   |
| WDC WD40EZRZ-75GXCB0 4TB           | 1        | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 36       | 51     | 39.56%  |
| WDC                 | 28       | 41     | 30.77%  |
| Toshiba             | 13       | 13     | 14.29%  |
| Hitachi             | 6        | 7      | 6.59%   |
| Samsung Electronics | 5        | 7      | 5.49%   |
| Unknown             | 2        | 2      | 2.2%    |
| HGST                | 1        | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 9        | 14     | 16.67%  |
| Kingston            | 9        | 11     | 16.67%  |
| SanDisk             | 6        | 6      | 11.11%  |
| WDC                 | 5        | 5      | 9.26%   |
| Crucial             | 4        | 4      | 7.41%   |
| JMicron Technology  | 3        | 3      | 5.56%   |
| SPCC                | 2        | 2      | 3.7%    |
| LITEONIT            | 2        | 2      | 3.7%    |
| Fujitsu             | 2        | 2      | 3.7%    |
| China               | 2        | 5      | 3.7%    |
| Unknown             | 1        | 1      | 1.85%   |
| Team                | 1        | 2      | 1.85%   |
| PNY                 | 1        | 1      | 1.85%   |
| Plextor             | 1        | 1      | 1.85%   |
| OCZ                 | 1        | 1      | 1.85%   |
| Intenso             | 1        | 1      | 1.85%   |
| FORESEE             | 1        | 1      | 1.85%   |
| Corsair             | 1        | 1      | 1.85%   |
| Apacer              | 1        | 1      | 1.85%   |
| AMD                 | 1        | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 65       | 122    | 53.28%  |
| SSD  | 45       | 65     | 36.89%  |
| NVMe | 12       | 18     | 9.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 76       | 178    | 79.17%  |
| NVMe | 12       | 18     | 12.5%   |
| SAS  | 8        | 9      | 8.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 65       | 123    | 55.08%  |
| 0.51-1.0   | 34       | 42     | 28.81%  |
| 1.01-2.0   | 11       | 14     | 9.32%   |
| 3.01-4.0   | 6        | 6      | 5.08%   |
| 2.01-3.0   | 1        | 1      | 0.85%   |
| 4.01-10.0  | 1        | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 24       | 26.67%  |
| 101-250        | 18       | 20%     |
| 501-1000       | 16       | 17.78%  |
| 1001-2000      | 15       | 16.67%  |
| 2001-3000      | 4        | 4.44%   |
| 51-100         | 4        | 4.44%   |
| Unknown        | 4        | 4.44%   |
| More than 3000 | 2        | 2.22%   |
| 21-50          | 2        | 2.22%   |
| 1-20           | 1        | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 24       | 26.37%  |
| 101-250        | 19       | 20.88%  |
| 1-20           | 15       | 16.48%  |
| 51-100         | 11       | 12.09%  |
| 251-500        | 8        | 8.79%   |
| 501-1000       | 6        | 6.59%   |
| Unknown        | 4        | 4.4%    |
| 1001-2000      | 3        | 3.3%    |
| More than 3000 | 1        | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| SanDisk SD6SF1M128G1022I 128GB SSD | 2        | 2      | 7.41%   |
| WDC WD5000AAKS-75V0A0 500GB        | 1        | 1      | 3.7%    |
| WDC WD5000AADS-00S9B0 500GB        | 1        | 1      | 3.7%    |
| WDC WD2003FZEX-00Z4SA0 2TB         | 1        | 1      | 3.7%    |
| WDC WD10JUCX-63WPNY0 1TB           | 1        | 1      | 3.7%    |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 1      | 3.7%    |
| Seagate ST9500325AS 500GB          | 1        | 1      | 3.7%    |
| Seagate ST9250410AS 250GB          | 1        | 1      | 3.7%    |
| Seagate ST500NM0011 500GB          | 1        | 1      | 3.7%    |
| Seagate ST3500413AS 500GB          | 1        | 1      | 3.7%    |
| Seagate ST3320418AS 320GB          | 1        | 1      | 3.7%    |
| Seagate ST3250824AS 250GB          | 1        | 1      | 3.7%    |
| Seagate ST320LT007-9ZV142 320GB    | 1        | 1      | 3.7%    |
| Seagate ST3160215AS 160GB          | 1        | 1      | 3.7%    |
| Seagate ST31000528AS 1TB           | 1        | 1      | 3.7%    |
| Seagate ST250DM000-1BD141 250GB    | 1        | 1      | 3.7%    |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 3.7%    |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 3.7%    |
| SanDisk SSD PLUS 480GB             | 1        | 1      | 3.7%    |
| SanDisk SSD PLUS 1000GB            | 1        | 1      | 3.7%    |
| Samsung Electronics HM500JI 500GB  | 1        | 1      | 3.7%    |
| Samsung Electronics HD161HJ 160GB  | 1        | 1      | 3.7%    |
| Samsung Electronics HD154UI 1TB    | 1        | 1      | 3.7%    |
| Plextor PX-512M6Pro 512GB SSD      | 1        | 1      | 3.7%    |
| Hitachi HUA722020ALA331 2TB        | 1        | 1      | 3.7%    |
| A-DATA Technology SX7000NP 128GB   | 1        | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 12     | 40%     |
| WDC                 | 5        | 5      | 20%     |
| SanDisk             | 4        | 4      | 16%     |
| Samsung Electronics | 3        | 3      | 12%     |
| Plextor             | 1        | 1      | 4%      |
| Hitachi             | 1        | 1      | 4%      |
| A-DATA Technology   | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 12     | 52.63%  |
| WDC                 | 5        | 5      | 26.32%  |
| Samsung Electronics | 3        | 3      | 15.79%  |
| Hitachi             | 1        | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 21     | 70%     |
| SSD  | 5        | 5      | 25%     |
| NVMe | 1        | 1      | 5%      |

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
| Detected | 50       | 115    | 45.87%  |
| Works    | 40       | 61     | 36.7%   |
| Malfunc  | 17       | 27     | 15.6%   |
| Failed   | 2        | 2      | 1.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 53       | 52.48%  |
| AMD                      | 27       | 26.73%  |
| SanDisk                  | 3        | 2.97%   |
| Samsung Electronics      | 3        | 2.97%   |
| Nvidia                   | 3        | 2.97%   |
| ASMedia Technology       | 3        | 2.97%   |
| SK hynix                 | 2        | 1.98%   |
| Phison Electronics       | 2        | 1.98%   |
| VIA Technologies         | 1        | 0.99%   |
| Silicon Motion           | 1        | 0.99%   |
| Micron Technology        | 1        | 0.99%   |
| Marvell Technology Group | 1        | 0.99%   |
| JMicron Technology       | 1        | 0.99%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 12.78%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 7.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 5.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 5.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 4.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 3.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 3.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 3.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 3.01%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 3.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.26%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 2.26%   |
| Nvidia MCP61 IDE                                                                        | 3        | 2.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.26%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 2.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.5%    |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.5%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.5%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.5%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.5%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.75%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 0.75%   |
| SK hynix BC511                                                                          | 1        | 0.75%   |
| Silicon Motion Non-Volatile memory controller                                           | 1        | 0.75%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.75%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.75%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.75%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.75%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.75%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 1        | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1        | 0.75%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.75%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 62       | 60.78%  |
| IDE  | 23       | 22.55%  |
| NVMe | 12       | 11.76%  |
| RAID | 5        | 4.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 54       | 64.29%  |
| AMD    | 30       | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 3.57%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 3.57%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 2        | 2.38%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 2        | 2.38%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 2        | 2.38%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2        | 2.38%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 2.38%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 2.38%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 2.38%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2        | 2.38%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 2.38%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 2.38%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2        | 2.38%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 2        | 2.38%   |
| AMD FX-8350 Eight-Core Processor            | 2        | 2.38%   |
| Intel Xeon CPU X5460 @ 3.16GHz              | 1        | 1.19%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 1.19%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 1.19%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 1.19%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 1.19%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 1.19%   |
| Intel Core M-5Y10c CPU @ 0.80GHz            | 1        | 1.19%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1        | 1.19%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1        | 1.19%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.19%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.19%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 1.19%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.19%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.19%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 1.19%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 1.19%   |
| Intel Core i5-9500T CPU @ 2.20GHz           | 1        | 1.19%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.19%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.19%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.19%   |
| Intel Core i5-4670S CPU @ 3.10GHz           | 1        | 1.19%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 1.19%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1        | 1.19%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1        | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 14       | 16.67%  |
| Intel Core i7           | 13       | 15.48%  |
| Intel Core i3           | 9        | 10.71%  |
| AMD Ryzen 5             | 6        | 7.14%   |
| Intel Xeon              | 5        | 5.95%   |
| AMD Ryzen 7             | 5        | 5.95%   |
| AMD FX                  | 4        | 4.76%   |
| Intel Pentium Dual-Core | 3        | 3.57%   |
| Intel Pentium           | 3        | 3.57%   |
| Intel Core 2 Duo        | 3        | 3.57%   |
| Other                   | 2        | 2.38%   |
| AMD Athlon II X2        | 2        | 2.38%   |
| AMD A8                  | 2        | 2.38%   |
| AMD A10                 | 2        | 2.38%   |
| Intel Pentium Dual      | 1        | 1.19%   |
| Intel Core M            | 1        | 1.19%   |
| Intel Core 2 Quad       | 1        | 1.19%   |
| AMD Ryzen Threadripper  | 1        | 1.19%   |
| AMD Ryzen 9             | 1        | 1.19%   |
| AMD Ryzen 3             | 1        | 1.19%   |
| AMD Phenom II X4        | 1        | 1.19%   |
| AMD Phenom              | 1        | 1.19%   |
| AMD Athlon 64 X2        | 1        | 1.19%   |
| AMD Athlon 64           | 1        | 1.19%   |
| AMD A4                  | 1        | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 36       | 42.86%  |
| 2      | 27       | 32.14%  |
| 8      | 7        | 8.33%   |
| 6      | 7        | 8.33%   |
| 12     | 3        | 3.57%   |
| 3      | 2        | 2.38%   |
| 1      | 2        | 2.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 83       | 98.81%  |
| 2      | 1        | 1.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 44       | 52.38%  |
| 1      | 40       | 47.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 84       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 52       | 59.77%  |
| 0x906e9    | 5        | 5.75%   |
| 0x206a7    | 5        | 5.75%   |
| 0x306c3    | 4        | 4.6%    |
| 0x306a9    | 2        | 2.3%    |
| 0x1067a    | 2        | 2.3%    |
| 0x08701021 | 2        | 2.3%    |
| 0x08001138 | 2        | 2.3%    |
| 0x06000852 | 2        | 2.3%    |
| 0x906ed    | 1        | 1.15%   |
| 0x906ea    | 1        | 1.15%   |
| 0x90672    | 1        | 1.15%   |
| 0x106a5    | 1        | 1.15%   |
| 0x0a201016 | 1        | 1.15%   |
| 0x08108109 | 1        | 1.15%   |
| 0x0800820d | 1        | 1.15%   |
| 0x0600111f | 1        | 1.15%   |
| 0x06001119 | 1        | 1.15%   |
| 0x010000c8 | 1        | 1.15%   |
| 0x01000095 | 1        | 1.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 13       | 15.48%  |
| Haswell          | 10       | 11.9%   |
| SandyBridge      | 9        | 10.71%  |
| Piledriver       | 8        | 9.52%   |
| Penryn           | 7        | 8.33%   |
| Zen              | 6        | 7.14%   |
| K10              | 5        | 5.95%   |
| Zen 2            | 4        | 4.76%   |
| Skylake          | 4        | 4.76%   |
| Zen+             | 3        | 3.57%   |
| IvyBridge        | 3        | 3.57%   |
| Core             | 3        | 3.57%   |
| Nehalem          | 2        | 2.38%   |
| K8 Hammer        | 2        | 2.38%   |
| Zen 3            | 1        | 1.19%   |
| Westmere         | 1        | 1.19%   |
| Steamroller      | 1        | 1.19%   |
| Broadwell        | 1        | 1.19%   |
| Alderlake Hybrid | 1        | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 38       | 40%     |
| Intel  | 29       | 30.53%  |
| AMD    | 28       | 29.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 6.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 6.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 5.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 4.21%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 3.16%   |
| Intel HD Graphics 630                                                       | 3        | 3.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.16%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 3.16%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 3        | 3.16%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.11%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 2.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.11%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.11%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.11%   |
| AMD RS780L [Radeon 3000]                                                    | 2        | 2.11%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 2.11%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.05%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.05%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.05%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 1.05%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 1.05%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.05%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 1.05%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.05%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.05%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.05%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.05%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.05%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.05%   |
| Nvidia GK104 [GeForce GTX 660 Ti]                                           | 1        | 1.05%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.05%   |
| Nvidia GF119 [GeForce 510]                                                  | 1        | 1.05%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 1.05%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.05%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.05%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.05%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 1.05%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.05%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 35       | 41.67%  |
| 1 x AMD        | 24       | 28.57%  |
| 1 x Intel      | 20       | 23.81%  |
| Intel + AMD    | 2        | 2.38%   |
| AMD + Nvidia   | 2        | 2.38%   |
| Intel + Nvidia | 1        | 1.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 65       | 76.47%  |
| Proprietary | 17       | 20%     |
| Unknown     | 3        | 3.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 50       | 57.47%  |
| 1.01-2.0   | 10       | 11.49%  |
| 0.51-1.0   | 9        | 10.34%  |
| 3.01-4.0   | 8        | 9.2%    |
| 7.01-8.0   | 6        | 6.9%    |
| 5.01-6.0   | 2        | 2.3%    |
| 0.01-0.5   | 2        | 2.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 13.83%  |
| Dell                 | 9        | 9.57%   |
| BenQ                 | 7        | 7.45%   |
| Acer                 | 7        | 7.45%   |
| Goldstar             | 6        | 6.38%   |
| Unknown              | 5        | 5.32%   |
| Philips              | 5        | 5.32%   |
| Hewlett-Packard      | 5        | 5.32%   |
| AOC                  | 5        | 5.32%   |
| Ancor Communications | 4        | 4.26%   |
| Toshiba              | 3        | 3.19%   |
| AUS                  | 3        | 3.19%   |
| Vizio                | 2        | 2.13%   |
| Panasonic            | 2        | 2.13%   |
| NEC Computers        | 2        | 2.13%   |
| ___                  | 1        | 1.06%   |
| ViewSonic            | 1        | 1.06%   |
| STD                  | 1        | 1.06%   |
| Sony                 | 1        | 1.06%   |
| Sceptre              | 1        | 1.06%   |
| RIS                  | 1        | 1.06%   |
| Plain Tree Systems   | 1        | 1.06%   |
| MStar                | 1        | 1.06%   |
| Lenovo               | 1        | 1.06%   |
| Insignia             | 1        | 1.06%   |
| Iiyama               | 1        | 1.06%   |
| GDH                  | 1        | 1.06%   |
| Eizo                 | 1        | 1.06%   |
| Ativa                | 1        | 1.06%   |
| ASUSTek Computer     | 1        | 1.06%   |
| AGO                  | 1        | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor XMD Mi TV 1360x768                                 | 2        | 2.02%   |
| Toshiba TV TSB0105 1920x540 708x398mm 32.0-inch                        | 2        | 2.02%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 2.02%   |
| Panasonic TV MEIA08F 1920x540                                          | 2        | 2.02%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch            | 2        | 2.02%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 2        | 2.02%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                      | 2        | 2.02%   |
| AUS LCD Monitor VG245 1920x1080                                        | 2        | 2.02%   |
| Acer X223W ACR0011 1680x1050 470x300mm 22.0-inch                       | 2        | 2.02%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1        | 1.01%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch              | 1        | 1.01%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                     | 1        | 1.01%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch          | 1        | 1.01%   |
| Unknown PHILCO 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 1.01%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                  | 1        | 1.01%   |
| Unknown LCD Monitor HRX 32H4030 1920x1080                              | 1        | 1.01%   |
| Toshiba TSB-TV TSB0205 1920x1080 531x398mm 26.1-inch                   | 1        | 1.01%   |
| STD LCD Monitor STD0001 1920x1080                                      | 1        | 1.01%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                    | 1        | 1.01%   |
| Sceptre LCD Monitor P30 2560x1080                                      | 1        | 1.01%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 1        | 1.01%   |
| Samsung Electronics SyncMaster SAM064F 1920x1080 510x290mm 23.1-inch   | 1        | 1.01%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1        | 1.01%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch   | 1        | 1.01%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1        | 1.01%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 1        | 1.01%   |
| Samsung Electronics LCD Monitor SAM094D 1920x1080 1210x680mm 54.6-inch | 1        | 1.01%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch   | 1        | 1.01%   |
| Samsung Electronics LCD Monitor SAM06AC 1920x1080 890x500mm 40.2-inch  | 1        | 1.01%   |
| Samsung Electronics LCD Monitor SAM03FE 1280x720                       | 1        | 1.01%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch     | 1        | 1.01%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 1        | 1.01%   |
| RIS photo24 RIS0902 1920x1080 521x293mm 23.5-inch                      | 1        | 1.01%   |
| Plain Tree Systems Monitor PTS0899 1680x1050 474x296mm 22.0-inch       | 1        | 1.01%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch               | 1        | 1.01%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch                | 1        | 1.01%   |
| Philips LCD Monitor PHL 234E5 1920x1080                                | 1        | 1.01%   |
| Philips LCD Monitor PHI32PFL3404 3200x1080                             | 1        | 1.01%   |
| Philips 190C PHL0849 1280x1024 380x300mm 19.1-inch                     | 1        | 1.01%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                         | 1        | 1.01%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 49       | 53.85%  |
| 1680x1050 (WSXGA+) | 8        | 8.79%   |
| 1280x1024 (SXGA)   | 8        | 8.79%   |
| 1360x768           | 5        | 5.49%   |
| 1440x900 (WXGA+)   | 4        | 4.4%    |
| 3840x2160 (4K)     | 3        | 3.3%    |
| 1920x1200 (WUXGA)  | 3        | 3.3%    |
| 2560x1440 (QHD)    | 2        | 2.2%    |
| 2560x1080          | 2        | 2.2%    |
| 1920x540           | 2        | 2.2%    |
| Unknown            | 2        | 2.2%    |
| 3840x1080          | 1        | 1.1%    |
| 3200x1080          | 1        | 1.1%    |
| 1280x720 (HD)      | 1        | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 16       | 16.84%  |
| Unknown | 16       | 16.84%  |
| 27      | 11       | 11.58%  |
| 23      | 10       | 10.53%  |
| 21      | 8        | 8.42%   |
| 22      | 6        | 6.32%   |
| 19      | 6        | 6.32%   |
| 17      | 5        | 5.26%   |
| 32      | 3        | 3.16%   |
| 31      | 3        | 3.16%   |
| 72      | 2        | 2.11%   |
| 54      | 1        | 1.05%   |
| 52      | 1        | 1.05%   |
| 42      | 1        | 1.05%   |
| 41      | 1        | 1.05%   |
| 40      | 1        | 1.05%   |
| 34      | 1        | 1.05%   |
| 25      | 1        | 1.05%   |
| 20      | 1        | 1.05%   |
| 12      | 1        | 1.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 32       | 35.16%  |
| 401-500     | 19       | 20.88%  |
| Unknown     | 16       | 17.58%  |
| 301-350     | 5        | 5.49%   |
| 701-800     | 4        | 4.4%    |
| 601-700     | 4        | 4.4%    |
| 351-400     | 3        | 3.3%    |
| 1501-2000   | 2        | 2.2%    |
| 1001-1500   | 2        | 2.2%    |
| 901-1000    | 2        | 2.2%    |
| 801-900     | 1        | 1.1%    |
| 201-300     | 1        | 1.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 49       | 56.98%  |
| 16/10   | 12       | 13.95%  |
| Unknown | 12       | 13.95%  |
| 5/4     | 8        | 9.3%    |
| 32/9    | 2        | 2.33%   |
| 4/3     | 1        | 1.16%   |
| 3/2     | 1        | 1.16%   |
| 21/9    | 1        | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 32       | 33.33%  |
| Unknown        | 16       | 16.67%  |
| 301-350        | 11       | 11.46%  |
| 151-200        | 10       | 10.42%  |
| 351-500        | 7        | 7.29%   |
| 251-300        | 7        | 7.29%   |
| 141-150        | 5        | 5.21%   |
| More than 1000 | 4        | 4.17%   |
| 501-1000       | 3        | 3.13%   |
| 71-80          | 1        | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 51       | 60%     |
| Unknown | 16       | 18.82%  |
| 101-120 | 9        | 10.59%  |
| 1-50    | 6        | 7.06%   |
| 161-240 | 2        | 2.35%   |
| 121-160 | 1        | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 62       | 70.45%  |
| 2     | 20       | 22.73%  |
| 0     | 4        | 4.55%   |
| 3     | 2        | 2.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 58       | 37.66%  |
| Intel                           | 25       | 16.23%  |
| Ralink Technology               | 11       | 7.14%   |
| Qualcomm Atheros                | 11       | 7.14%   |
| Broadcom                        | 8        | 5.19%   |
| TP-Link                         | 4        | 2.6%    |
| Samsung Electronics             | 4        | 2.6%    |
| Microsoft                       | 4        | 2.6%    |
| Qualcomm Atheros Communications | 3        | 1.95%   |
| Nvidia                          | 3        | 1.95%   |
| D-Link System                   | 3        | 1.95%   |
| Ralink                          | 2        | 1.3%    |
| OnePlus Technology (Shenzhen)   | 2        | 1.3%    |
| NetGear                         | 2        | 1.3%    |
| Broadcom Limited                | 2        | 1.3%    |
| ASUSTek Computer                | 2        | 1.3%    |
| vivo                            | 1        | 0.65%   |
| Mercucys                        | 1        | 0.65%   |
| MediaTek                        | 1        | 0.65%   |
| Marvell Technology Group        | 1        | 0.65%   |
| Linksys                         | 1        | 0.65%   |
| Lenovo                          | 1        | 0.65%   |
| ICS Advent                      | 1        | 0.65%   |
| Huawei Technologies             | 1        | 0.65%   |
| Gemtek                          | 1        | 0.65%   |
| D-Link                          | 1        | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 45       | 26.32%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 5        | 2.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 5        | 2.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 4        | 2.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 4        | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 4        | 2.34%   |
| Ralink RT2870/RT3070 Wireless Adapter                              | 4        | 2.34%   |
| Ralink MT7601U Wireless Adapter                                    | 4        | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 4        | 2.34%   |
| Intel I211 Gigabit Network Connection                              | 4        | 2.34%   |
| Intel Ethernet Connection (2) I219-V                               | 4        | 2.34%   |
| Qualcomm Atheros AR9271 802.11n                                    | 3        | 1.75%   |
| Nvidia MCP61 Ethernet                                              | 3        | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                 | 3        | 1.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 2        | 1.17%   |
| TP-Link Archer T4U ver.3                                           | 2        | 1.17%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 2        | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 2        | 1.17%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:3BB6B401                         | 2        | 1.17%   |
| Microsoft Xbox 360 Wireless Adapter                                | 2        | 1.17%   |
| Intel Ethernet Connection I217-V                                   | 2        | 1.17%   |
| Intel Ethernet Connection I217-LM                                  | 2        | 1.17%   |
| Intel 82579V Gigabit Network Connection                            | 2        | 1.17%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                    | 2        | 1.17%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 2        | 1.17%   |
| vivo 1806                                                          | 1        | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1        | 0.58%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                | 1        | 0.58%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 1        | 0.58%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter           | 1        | 0.58%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                    | 1        | 0.58%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)          | 1        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 1        | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1        | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                  | 1        | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter              | 1        | 0.58%   |
| Ralink RT5572 Wireless Adapter                                     | 1        | 0.58%   |
| Ralink RT5372 Wireless Adapter                                     | 1        | 0.58%   |
| Ralink RT5370 Wireless Adapter                                     | 1        | 0.58%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                               | 1        | 0.58%   |

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
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 5        | 6.85%   |
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
| Realtek Semiconductor    | 51       | 54.84%  |
| Intel                    | 22       | 23.66%  |
| Samsung Electronics      | 4        | 4.3%    |
| Qualcomm Atheros         | 4        | 4.3%    |
| Nvidia                   | 3        | 3.23%   |
| D-Link System            | 2        | 2.15%   |
| Broadcom                 | 2        | 2.15%   |
| vivo                     | 1        | 1.08%   |
| MediaTek                 | 1        | 1.08%   |
| Marvell Technology Group | 1        | 1.08%   |
| ICS Advent               | 1        | 1.08%   |
| Broadcom Limited         | 1        | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45       | 47.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 5.32%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4        | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 4.26%   |
| Intel I211 Gigabit Network Connection                             | 4        | 4.26%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 4.26%   |
| Nvidia MCP61 Ethernet                                             | 3        | 3.19%   |
| Intel Ethernet Connection I217-V                                  | 2        | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.13%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 2.13%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 2.13%   |
| vivo 1806                                                         | 1        | 1.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.06%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.06%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 1.06%   |
| MediaTek TECNO CAMON 18P                                          | 1        | 1.06%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.06%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.06%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.06%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 1.06%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.06%   |
| ICS Advent USB 10/100 LAN                                         | 1        | 1.06%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.06%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1        | 1.06%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 82       | 56.55%  |
| WiFi     | 59       | 40.69%  |
| Unknown  | 4        | 2.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 59.34%  |
| WiFi     | 35       | 38.46%  |
| Unknown  | 2        | 2.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 64.71%  |
| 2     | 24       | 28.24%  |
| 3     | 3        | 3.53%   |
| 0     | 2        | 2.35%   |
| 4     | 1        | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 72       | 83.72%  |
| Yes  | 14       | 16.28%  |

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
| Intel                  | 53       | 38.13%  |
| AMD                    | 38       | 27.34%  |
| Nvidia                 | 35       | 25.18%  |
| C-Media Electronics    | 4        | 2.88%   |
| Logitech               | 2        | 1.44%   |
| Yamaha                 | 1        | 0.72%   |
| Tenx Technology        | 1        | 0.72%   |
| SteelSeries ApS        | 1        | 0.72%   |
| Samson Technologies    | 1        | 0.72%   |
| JMTek                  | 1        | 0.72%   |
| GYROCOM C&C            | 1        | 0.72%   |
| Generalplus Technology | 1        | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10       | 6.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 5.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8        | 4.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8        | 4.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 7        | 4.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 6        | 3.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 3.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 3.01%   |
| AMD FCH Azalia Controller                                                         | 5        | 3.01%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 2.41%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 2.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 4        | 2.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 2.41%   |
| AMD Starship/Matisse HD Audio Controller                                          | 4        | 2.41%   |
| Nvidia MCP61 High Definition Audio                                                | 3        | 1.81%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.81%   |
| Nvidia GK104 HDMI Audio Controller                                                | 3        | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 1.81%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 1.81%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 1.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.81%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 1.2%    |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 1.2%    |
| Nvidia GF106 High Definition Audio Controller                                     | 2        | 1.2%    |
| Nvidia GA104 High Definition Audio Controller                                     | 2        | 1.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 1.2%    |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 2        | 1.2%    |
| C-Media Electronics CM108 Audio Controller                                        | 2        | 1.2%    |
| AMD Trinity HDMI Audio Controller                                                 | 2        | 1.2%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 1.2%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 2        | 1.2%    |
| Yamaha Steinberg UR22mkII                                                         | 1        | 0.6%    |
| Tenx Technology USB AUDIO                                                         | 1        | 0.6%    |
| SteelSeries ApS SteelSeries GameDAC                                               | 1        | 0.6%    |
| Samson Technologies G-Track Pro microphone                                        | 1        | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 13       | 26%     |
| Corsair             | 7        | 14%     |
| Kingston            | 6        | 12%     |
| SK hynix            | 5        | 10%     |
| Crucial             | 5        | 10%     |
| Samsung Electronics | 3        | 6%      |
| G.Skill             | 3        | 6%      |
| Micron Technology   | 2        | 4%      |
| Unifosa             | 1        | 2%      |
| Silicon Power       | 1        | 2%      |
| S                   | 1        | 2%      |
| Nanya Technology    | 1        | 2%      |
| AMD                 | 1        | 2%      |
| A-DATA Technology   | 1        | 2%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 2        | 3.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 2        | 3.7%    |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s      | 2        | 3.7%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 1.85%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s               | 1        | 1.85%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                  | 1        | 1.85%   |
| Unknown RAM Module 4GB DIMM 800MT/s                        | 1        | 1.85%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 1.85%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                       | 1        | 1.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 1.85%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 1        | 1.85%   |
| Unknown RAM Module 2GB DIMM                                | 1        | 1.85%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                | 1        | 1.85%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 1        | 1.85%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 1.85%   |
| SK hynix RAM Module 8GB DIMM DDR4 3200MT/s                 | 1        | 1.85%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                     | 1        | 1.85%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 1.85%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1        | 1.85%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s       | 1        | 1.85%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s       | 1        | 1.85%   |
| Silicon Power RAM SP016GBLFU266B02 16GB DIMM DDR4 2667MT/s | 1        | 1.85%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s        | 1        | 1.85%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s     | 1        | 1.85%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.85%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.85%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                        | 1        | 1.85%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s         | 1        | 1.85%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 1        | 1.85%   |
| Micron RAM 16JTF51264AZ-1G6K1 4GB DIMM DDR3 1600MT/s       | 1        | 1.85%   |
| Kingston RAM KHYXPX-HYJ 8GB SODIMM DDR4 2667MT/s           | 1        | 1.85%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s        | 1        | 1.85%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s     | 1        | 1.85%   |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s        | 1        | 1.85%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 1.85%   |
| Kingston RAM 9905678-005.A00G 8GB DIMM DDR4 2400MT/s       | 1        | 1.85%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s     | 1        | 1.85%   |
| G.Skill RAM F4-2400C15-8GIS 8GB DIMM DDR4 2400MT/s         | 1        | 1.85%   |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s      | 1        | 1.85%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s     | 1        | 1.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 20       | 44.44%  |
| DDR4    | 16       | 35.56%  |
| Unknown | 4        | 8.89%   |
| DDR2    | 3        | 6.67%   |
| SDRAM   | 2        | 4.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 42       | 95.45%  |
| SODIMM | 2        | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 19       | 38.78%  |
| 4096  | 15       | 30.61%  |
| 2048  | 8        | 16.33%  |
| 16384 | 5        | 10.2%   |
| 1024  | 2        | 4.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 13       | 26%     |
| 2400    | 5        | 10%     |
| 3200    | 4        | 8%      |
| 1333    | 4        | 8%      |
| 3600    | 3        | 6%      |
| 2667    | 3        | 6%      |
| Unknown | 3        | 6%      |
| 1867    | 2        | 4%      |
| 800     | 2        | 4%      |
| 3466    | 1        | 2%      |
| 3100    | 1        | 2%      |
| 3000    | 1        | 2%      |
| 2666    | 1        | 2%      |
| 2200    | 1        | 2%      |
| 2133    | 1        | 2%      |
| 1866    | 1        | 2%      |
| 1800    | 1        | 2%      |
| 1067    | 1        | 2%      |
| 1066    | 1        | 2%      |
| 400     | 1        | 2%      |

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
| Apple iPhone5/5C/5S/6                                 | 1        | 6.67%   |

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
| 0     | 64       | 74.42%  |
| 1     | 19       | 22.09%  |
| 2     | 3        | 3.49%   |

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

