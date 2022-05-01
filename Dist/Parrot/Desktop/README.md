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

Total: 99

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| SLIMBOOK      | ONE-AMD-M4              | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
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
| SLIMBOOK      | ONE-AMD-M4              | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Dell          | 0GXM1W A02              | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| ASUSTek       | Benicia                 | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
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
| Gigabyte      | A320M-S2H-CF            | [6647d75cdb](https://linux-hardware.org/?probe=6647d75cdb) | Aug 20, 2021 |
| MSI           | B450 TOMAHAWK MAX       | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF            | [5363cc3efd](https://linux-hardware.org/?probe=5363cc3efd) | Aug 12, 2021 |
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
| ASUSTek       | A68HM-PLUS              | [e65034291f](https://linux-hardware.org/?probe=e65034291f) | May 22, 2020 |
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
| Unknown       | Unknown                 | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Unknown       | Unknown                 | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H            | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| ASRock        | FM2A68M-DG3+            | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| Gigabyte      | AX370-Gaming-CF se1     | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1     | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Foxconn       | 2A8C                    | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                    | [e1c6df0bfd](https://linux-hardware.org/?probe=e1c6df0bfd) | Jan 19, 2020 |
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
| Parrot 4.11 | 20       | 29.85%  |
| Parrot 5.0  | 15       | 22.39%  |
| Parrot 4.10 | 14       | 20.9%   |
| Parrot 4.9  | 9        | 13.43%  |
| Parrot 4.8  | 6        | 8.96%   |
| Parrot 4.7  | 3        | 4.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Parrot | 65       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.5.0-1parrot1-amd64   | 12       | 17.14%  |
| 5.14.0-9parrot1-amd64  | 12       | 17.14%  |
| 5.7.0-2parrot2-amd64   | 6        | 8.57%   |
| 5.16.0-12parrot1-amd64 | 6        | 8.57%   |
| 5.15.0-15parrot1-amd64 | 6        | 8.57%   |
| 5.10.0-6parrot1-amd64  | 5        | 7.14%   |
| 5.8.0-2parrot1-amd64   | 3        | 4.29%   |
| 5.4.0-4parrot1-amd64   | 3        | 4.29%   |
| 5.10.0-8parrot1-amd64  | 3        | 4.29%   |
| 5.9.0-2parrot1-amd64   | 2        | 2.86%   |
| 5.4.0-2parrot1-amd64   | 2        | 2.86%   |
| 5.3.0-3parrot3-amd64   | 2        | 2.86%   |
| 5.14.0-2parrot1-amd64  | 2        | 2.86%   |
| 5.10.0-3parrot1-amd64  | 2        | 2.86%   |
| 5.8.0-1parrot1-amd64   | 1        | 1.43%   |
| 5.6.0-2parrot1-amd64   | 1        | 1.43%   |
| 5.4.0-3parrot1-amd64   | 1        | 1.43%   |
| 5.10.0-5parrot1-amd64  | 1        | 1.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 13       | 18.84%  |
| 5.5.0   | 12       | 17.39%  |
| 5.10.0  | 11       | 15.94%  |
| 5.7.0   | 6        | 8.7%    |
| 5.4.0   | 6        | 8.7%    |
| 5.16.0  | 6        | 8.7%    |
| 5.15.0  | 6        | 8.7%    |
| 5.8.0   | 4        | 5.8%    |
| 5.9.0   | 2        | 2.9%    |
| 5.3.0   | 2        | 2.9%    |
| 5.6.0   | 1        | 1.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 13       | 18.84%  |
| 5.5     | 12       | 17.39%  |
| 5.10    | 11       | 15.94%  |
| 5.7     | 6        | 8.7%    |
| 5.4     | 6        | 8.7%    |
| 5.16    | 6        | 8.7%    |
| 5.15    | 6        | 8.7%    |
| 5.8     | 4        | 5.8%    |
| 5.9     | 2        | 2.9%    |
| 5.3     | 2        | 2.9%    |
| 5.6     | 1        | 1.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 65       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 42       | 62.69%  |
| KDE5    | 10       | 14.93%  |
| KDE     | 7        | 10.45%  |
| XFCE    | 4        | 5.97%   |
| GNOME   | 2        | 2.99%   |
| Unknown | 2        | 2.99%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 63       | 96.92%  |
| Wayland | 2        | 3.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 37.31%  |
| LightDM | 20       | 29.85%  |
| TDM     | 18       | 26.87%  |
| SDDM    | 2        | 2.99%   |
| GDM     | 2        | 2.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 33       | 50.77%  |
| ru_RU | 4        | 6.15%   |
| pt_BR | 3        | 4.62%   |
| en_IN | 3        | 4.62%   |
| de_DE | 3        | 4.62%   |
| pl_PL | 2        | 3.08%   |
| fr_FR | 2        | 3.08%   |
| es_ES | 2        | 3.08%   |
| en_HK | 2        | 3.08%   |
| cs_CZ | 2        | 3.08%   |
| ru_UA | 1        | 1.54%   |
| mk_MK | 1        | 1.54%   |
| it_IT | 1        | 1.54%   |
| es_MX | 1        | 1.54%   |
| en_DK | 1        | 1.54%   |
| en_CA | 1        | 1.54%   |
| en_AU | 1        | 1.54%   |
| de_AT | 1        | 1.54%   |
| an_ES | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 56       | 83.58%  |
| EFI  | 11       | 16.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 53       | 80.3%   |
| Ext4    | 9        | 13.64%  |
| Xfs     | 2        | 3.03%   |
| Overlay | 2        | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 40       | 59.7%   |
| GPT     | 17       | 25.37%  |
| MBR     | 10       | 14.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 82.35%  |
| Yes       | 12       | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 39       | 60%     |
| Yes       | 26       | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 20       | 30.77%  |
| Dell                | 10       | 15.38%  |
| Gigabyte Technology | 6        | 9.23%   |
| Hewlett-Packard     | 5        | 7.69%   |
| MSI                 | 4        | 6.15%   |
| Foxconn             | 3        | 4.62%   |
| ASRock              | 3        | 4.62%   |
| Acer                | 3        | 4.62%   |
| ECS                 | 2        | 3.08%   |
| ZOTAC               | 1        | 1.54%   |
| Wistron             | 1        | 1.54%   |
| SLIMBOOK            | 1        | 1.54%   |
| Positivo            | 1        | 1.54%   |
| Lenovo              | 1        | 1.54%   |
| Daewoo Lucoms       | 1        | 1.54%   |
| Biostar             | 1        | 1.54%   |
| Apple               | 1        | 1.54%   |
| Alienware           | 1        | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| HP ProDesk 600 G1 SFF        | 2        | 3.08%   |
| Gigabyte AX370-Gaming        | 2        | 3.08%   |
| Foxconn s5710t               | 2        | 3.08%   |
| Dell Inspiron 5676           | 2        | 3.08%   |
| ASUS M5A78L-M/USB3           | 2        | 3.08%   |
| ASUS H110I-PLUS              | 2        | 3.08%   |
| ASUS Basic 3221BM            | 2        | 3.08%   |
| Wistron FMVDD2A0H0           | 1        | 1.54%   |
| SLIMBOOK ONE-AMD-M4          | 1        | 1.54%   |
| Positivo POS-PIG43BC         | 1        | 1.54%   |
| MSI MS-7C02                  | 1        | 1.54%   |
| MSI MS-7A69                  | 1        | 1.54%   |
| MSI MS-7A34                  | 1        | 1.54%   |
| MSI MS-7529                  | 1        | 1.54%   |
| Lenovo H530 10130            | 1        | 1.54%   |
| HP Compaq Pro 6305 MT        | 1        | 1.54%   |
| HP Compaq Pro 6300 MT        | 1        | 1.54%   |
| HP Compaq 6005 Pro MT PC     | 1        | 1.54%   |
| Gigabyte H370M-DS3H          | 1        | 1.54%   |
| Gigabyte GA-880GM-D2H        | 1        | 1.54%   |
| Gigabyte A320M-S2H           | 1        | 1.54%   |
| Gigabyte 970A-DS3P           | 1        | 1.54%   |
| Foxconn 45CMX/45GMX/45CMX-K  | 1        | 1.54%   |
| ECS GV460AA-ABA a6217c       | 1        | 1.54%   |
| ECS A740GM-M                 | 1        | 1.54%   |
| Dell XPS 8930                | 1        | 1.54%   |
| Dell Vostro 200              | 1        | 1.54%   |
| Dell Studio XPS 9100         | 1        | 1.54%   |
| Dell OptiPlex 990            | 1        | 1.54%   |
| Dell OptiPlex 7070           | 1        | 1.54%   |
| Dell OptiPlex 7010           | 1        | 1.54%   |
| Dell OptiPlex 3020           | 1        | 1.54%   |
| Dell OptiPlex 3010           | 1        | 1.54%   |
| Daewoo Lucoms OEM            | 1        | 1.54%   |
| Biostar H77MU3               | 1        | 1.54%   |
| ASUS Z170 PRO GAMING         | 1        | 1.54%   |
| ASUS ROG STRIX B450-F GAMING | 1        | 1.54%   |
| ASUS ROG CROSSHAIR VIII HERO | 1        | 1.54%   |
| ASUS PRIME X399-A            | 1        | 1.54%   |
| ASUS PRIME H310M-D R2.0      | 1        | 1.54%   |
| ASUS P8H67-M PRO             | 1        | 1.54%   |
| ASUS Maximus VIII HERO       | 1        | 1.54%   |
| ASUS M5A99X EVO              | 1        | 1.54%   |
| ASUS M2N68-AM Plus           | 1        | 1.54%   |
| ASUS KJ250AA-ABE a6336.es    | 1        | 1.54%   |
| ASUS K31CD-K                 | 1        | 1.54%   |
| ASUS H170M-E D3              | 1        | 1.54%   |
| ASUS F2A85-M                 | 1        | 1.54%   |
| ASUS A68HM-PLUS              | 1        | 1.54%   |
| ASRock Z87M Extreme4         | 1        | 1.54%   |
| ASRock Z87 Killer            | 1        | 1.54%   |
| ASRock FM2A68M-DG3+          | 1        | 1.54%   |
| Apple MacPro5,1              | 1        | 1.54%   |
| Alienware X51 R2             | 1        | 1.54%   |
| Acer Predator PO3-600        | 1        | 1.54%   |
| Acer Aspire X3990            | 1        | 1.54%   |
| Acer Aspire TC-780           | 1        | 1.54%   |
| Unknown                      | 1        | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 5        | 7.69%   |
| HP Compaq             | 3        | 4.62%   |
| HP ProDesk            | 2        | 3.08%   |
| Gigabyte AX370-Gaming | 2        | 3.08%   |
| Foxconn s5710t        | 2        | 3.08%   |
| Dell Inspiron         | 2        | 3.08%   |
| ASUS ROG              | 2        | 3.08%   |
| ASUS PRIME            | 2        | 3.08%   |
| ASUS M5A78L-M         | 2        | 3.08%   |
| ASUS H110I-PLUS       | 2        | 3.08%   |
| ASUS Basic            | 2        | 3.08%   |
| Acer Aspire           | 2        | 3.08%   |
| Wistron FMVDD2A0H0    | 1        | 1.54%   |
| SLIMBOOK ONE-AMD-M4   | 1        | 1.54%   |
| Positivo POS-PIG43BC  | 1        | 1.54%   |
| MSI MS-7C02           | 1        | 1.54%   |
| MSI MS-7A69           | 1        | 1.54%   |
| MSI MS-7A34           | 1        | 1.54%   |
| MSI MS-7529           | 1        | 1.54%   |
| Lenovo H530           | 1        | 1.54%   |
| Gigabyte H370M-DS3H   | 1        | 1.54%   |
| Gigabyte GA-880GM-D2H | 1        | 1.54%   |
| Gigabyte A320M-S2H    | 1        | 1.54%   |
| Gigabyte 970A-DS3P    | 1        | 1.54%   |
| Foxconn 45CMX         | 1        | 1.54%   |
| ECS GV460AA-ABA       | 1        | 1.54%   |
| ECS A740GM-M          | 1        | 1.54%   |
| Dell XPS              | 1        | 1.54%   |
| Dell Vostro           | 1        | 1.54%   |
| Dell Studio           | 1        | 1.54%   |
| Daewoo Lucoms OEM     | 1        | 1.54%   |
| Biostar H77MU3        | 1        | 1.54%   |
| ASUS Z170             | 1        | 1.54%   |
| ASUS P8H67-M          | 1        | 1.54%   |
| ASUS Maximus          | 1        | 1.54%   |
| ASUS M5A99X           | 1        | 1.54%   |
| ASUS M2N68-AM         | 1        | 1.54%   |
| ASUS KJ250AA-ABE      | 1        | 1.54%   |
| ASUS K31CD-K          | 1        | 1.54%   |
| ASUS H170M-E          | 1        | 1.54%   |
| ASUS F2A85-M          | 1        | 1.54%   |
| ASUS A68HM-PLUS       | 1        | 1.54%   |
| ASRock Z87M           | 1        | 1.54%   |
| ASRock Z87            | 1        | 1.54%   |
| ASRock FM2A68M-DG3+   | 1        | 1.54%   |
| Apple MacPro5         | 1        | 1.54%   |
| Alienware X51         | 1        | 1.54%   |
| Acer Predator         | 1        | 1.54%   |
| Unknown               | 1        | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 8        | 12.31%  |
| 2011 | 8        | 12.31%  |
| 2018 | 6        | 9.23%   |
| 2017 | 6        | 9.23%   |
| 2010 | 6        | 9.23%   |
| 2016 | 5        | 7.69%   |
| 2015 | 5        | 7.69%   |
| 2012 | 5        | 7.69%   |
| 2007 | 4        | 6.15%   |
| 2019 | 3        | 4.62%   |
| 2009 | 3        | 4.62%   |
| 2021 | 2        | 3.08%   |
| 2014 | 2        | 3.08%   |
| 2020 | 1        | 1.54%   |
| 2008 | 1        | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 65       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 65       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 65       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 16       | 23.88%  |
| 8.01-16.0   | 15       | 22.39%  |
| 4.01-8.0    | 13       | 19.4%   |
| 3.01-4.0    | 11       | 16.42%  |
| 32.01-64.0  | 7        | 10.45%  |
| 1.01-2.0    | 3        | 4.48%   |
| 24.01-32.0  | 1        | 1.49%   |
| 64.01-256.0 | 1        | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 26       | 38.81%  |
| 2.01-3.0   | 16       | 23.88%  |
| 4.01-8.0   | 13       | 19.4%   |
| 3.01-4.0   | 5        | 7.46%   |
| 0.51-1.0   | 4        | 5.97%   |
| 8.01-16.0  | 2        | 2.99%   |
| 16.01-24.0 | 1        | 1.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 25       | 37.31%  |
| 1      | 22       | 32.84%  |
| 3      | 13       | 19.4%   |
| 5      | 3        | 4.48%   |
| 4      | 3        | 4.48%   |
| 6      | 1        | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 72.73%  |
| Yes       | 18       | 27.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 63       | 96.92%  |
| No        | 2        | 3.08%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 46       | 68.66%  |
| No        | 21       | 31.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 72.31%  |
| Yes       | 18       | 27.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Desktops | Percent |
|-----------------|----------|---------|
| USA             | 20       | 30.3%   |
| Germany         | 7        | 10.61%  |
| Brazil          | 5        | 7.58%   |
| Spain           | 3        | 4.55%   |
| Russia          | 3        | 4.55%   |
| Netherlands     | 3        | 4.55%   |
| India           | 3        | 4.55%   |
| Italy           | 2        | 3.03%   |
| Hong Kong       | 2        | 3.03%   |
| Czechia         | 2        | 3.03%   |
| Austria         | 2        | 3.03%   |
| Vietnam         | 1        | 1.52%   |
| Ukraine         | 1        | 1.52%   |
| Romania         | 1        | 1.52%   |
| Poland          | 1        | 1.52%   |
| Pakistan        | 1        | 1.52%   |
| North Macedonia | 1        | 1.52%   |
| Morocco         | 1        | 1.52%   |
| Mexico          | 1        | 1.52%   |
| France          | 1        | 1.52%   |
| Egypt           | 1        | 1.52%   |
| Denmark         | 1        | 1.52%   |
| Canada          | 1        | 1.52%   |
| Belgium         | 1        | 1.52%   |
| Australia       | 1        | 1.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Indianapolis        | 3        | 4.41%   |
| Uherské Hradiště | 2        | 2.94%   |
| Newburgh            | 2        | 2.94%   |
| Madrid              | 2        | 2.94%   |
| Eugene              | 2        | 2.94%   |
| Central             | 2        | 2.94%   |
| Warsaw              | 1        | 1.47%   |
| Vienna              | 1        | 1.47%   |
| Viby J              | 1        | 1.47%   |
| Vapi                | 1        | 1.47%   |
| Traunstein          | 1        | 1.47%   |
| Terrace             | 1        | 1.47%   |
| Ternopil            | 1        | 1.47%   |
| Tangier             | 1        | 1.47%   |
| Skopje              | 1        | 1.47%   |
| Sassari             | 1        | 1.47%   |
| Sao Paulo           | 1        | 1.47%   |
| Sao Joao de Meriti  | 1        | 1.47%   |
| Santa Maria         | 1        | 1.47%   |
| Saint Paul          | 1        | 1.47%   |
| Rottweil            | 1        | 1.47%   |
| Rawalpindi          | 1        | 1.47%   |
| Portsmouth          | 1        | 1.47%   |
| Portland            | 1        | 1.47%   |
| Orange Park         | 1        | 1.47%   |
| Offenbach           | 1        | 1.47%   |
| Nuremberg           | 1        | 1.47%   |
| Nizhniy Novgorod    | 1        | 1.47%   |
| Newark              | 1        | 1.47%   |
| Nam Định         | 1        | 1.47%   |
| Naaldwijk           | 1        | 1.47%   |
| Morelia             | 1        | 1.47%   |
| Milton              | 1        | 1.47%   |
| Milan               | 1        | 1.47%   |
| Melbourne           | 1        | 1.47%   |
| Mardan              | 1        | 1.47%   |
| Lyon                | 1        | 1.47%   |
| Los Angeles         | 1        | 1.47%   |
| Lafayette           | 1        | 1.47%   |
| Krefeld             | 1        | 1.47%   |
| Krasnogorsk         | 1        | 1.47%   |
| Kolkata             | 1        | 1.47%   |
| Khabarovsk          | 1        | 1.47%   |
| Iasi                | 1        | 1.47%   |
| HortolГўndia      | 1        | 1.47%   |
| Dudenhofen          | 1        | 1.47%   |
| Darien              | 1        | 1.47%   |
| Cologne             | 1        | 1.47%   |
| Chicago             | 1        | 1.47%   |
| Campinas            | 1        | 1.47%   |
| Bussum              | 1        | 1.47%   |
| Brussels            | 1        | 1.47%   |
| Brunswick           | 1        | 1.47%   |
| Brunn am Gebirge    | 1        | 1.47%   |
| Braunschweig        | 1        | 1.47%   |
| Bonita Springs      | 1        | 1.47%   |
| Beri Khas           | 1        | 1.47%   |
| Barcelona           | 1        | 1.47%   |
| Atlanta             | 1        | 1.47%   |
| Amsterdam           | 1        | 1.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 37     | 21.95%  |
| WDC                 | 25       | 37     | 20.33%  |
| Samsung Electronics | 13       | 20     | 10.57%  |
| Toshiba             | 11       | 11     | 8.94%   |
| Sandisk             | 7        | 9      | 5.69%   |
| Kingston            | 7        | 8      | 5.69%   |
| Hitachi             | 5        | 6      | 4.07%   |
| Crucial             | 4        | 4      | 3.25%   |
| JMicron             | 3        | 3      | 2.44%   |
| Unknown             | 2        | 2      | 1.63%   |
| SK Hynix            | 2        | 2      | 1.63%   |
| LITEONIT            | 2        | 2      | 1.63%   |
| Fujitsu             | 2        | 2      | 1.63%   |
| China               | 2        | 5      | 1.63%   |
| Team                | 1        | 2      | 0.81%   |
| SPCC                | 1        | 1      | 0.81%   |
| Silicon Motion      | 1        | 1      | 0.81%   |
| PNY                 | 1        | 1      | 0.81%   |
| PLEXTOR             | 1        | 1      | 0.81%   |
| Phison              | 1        | 1      | 0.81%   |
| OCZ                 | 1        | 1      | 0.81%   |
| Intenso             | 1        | 1      | 0.81%   |
| HGST                | 1        | 1      | 0.81%   |
| FORESEE             | 1        | 1      | 0.81%   |
| A-DATA Technology   | 1        | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA200 2TB              | 5        | 3.5%    |
| Seagate ST250DM000-1BD141 250GB     | 3        | 2.1%    |
| Seagate Expansion+ 2TB              | 3        | 2.1%    |
| Samsung SSD 860 EVO 500GB           | 3        | 2.1%    |
| Samsung SSD 860 EVO 250GB           | 3        | 2.1%    |
| Kingston SA400S37480G 480GB SSD     | 3        | 2.1%    |
| JMicron Generic 240GB               | 3        | 2.1%    |
| WDC WD2500JS-75MHB0 250GB           | 2        | 1.4%    |
| WDC WD2500AAKX-753CA1 250GB         | 2        | 1.4%    |
| WDC WD10EZRX-00L4HB0 1TB            | 2        | 1.4%    |
| WDC WD10EARS-00Y5B1 1TB             | 2        | 1.4%    |
| Unknown SD/MMC/MS PRO 16GB          | 2        | 1.4%    |
| Toshiba DT01ACA050 500GB            | 2        | 1.4%    |
| Seagate ST500VT000-1DK142 500GB     | 2        | 1.4%    |
| Seagate ST500LM000-SSHD-8GB         | 2        | 1.4%    |
| Seagate ST31000528AS 1TB            | 2        | 1.4%    |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 2        | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2        | 1.4%    |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 2        | 1.4%    |
| Samsung SSD 840 Series 250GB        | 2        | 1.4%    |
| Fujitsu F300 480GB                  | 2        | 1.4%    |
| WDC WDS500G2B0C-00PXH0 500GB        | 1        | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 0.7%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1        | 0.7%    |
| WDC WDS120G1G0B-00RC30 120GB SSD    | 1        | 0.7%    |
| WDC WDBRPG5000ANC-WRSN 500GB        | 1        | 0.7%    |
| WDC WDBNCE0010PNC 1TB SSD           | 1        | 0.7%    |
| WDC WD800JD-75MSA3 80GB             | 1        | 0.7%    |
| WDC WD800AAJS-75M0A0 80GB           | 1        | 0.7%    |
| WDC WD60EFAX-68SHWN0 6TB            | 1        | 0.7%    |
| WDC WD5000AAKS-75V0A0 500GB         | 1        | 0.7%    |
| WDC WD5000AACS-00ZUB0 500GB         | 1        | 0.7%    |
| WDC WD40EZRZ-75GXCB0 4TB            | 1        | 0.7%    |
| WDC WD3200LPVX-60V0TT0 320GB        | 1        | 0.7%    |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 0.7%    |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 0.7%    |
| WDC WD2000JD-22HBC0 200GB           | 1        | 0.7%    |
| WDC WD10SPCX-24HWST0 1TB            | 1        | 0.7%    |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 0.7%    |
| WDC WD10JUCX-63WPNY0 1TB            | 1        | 0.7%    |
| WDC WD10EZEX-00WN4A0 1TB            | 1        | 0.7%    |
| WDC WD10EZEX-00KUWA0 1TB            | 1        | 0.7%    |
| WDC WD10EZEX-00BN5A0 1TB            | 1        | 0.7%    |
| WDC WD1003FZEX-00MK2A0 1TB          | 1        | 0.7%    |
| WDC WD1001FALS-41Y6A1 1TB           | 1        | 0.7%    |
| Toshiba MK2552GSX 250GB             | 1        | 0.7%    |
| Toshiba HDWD105 500GB               | 1        | 0.7%    |
| Toshiba DT01ACA300 3TB              | 1        | 0.7%    |
| Toshiba DT01ACA100 1TB              | 1        | 0.7%    |
| Team L5 LITE SSD 120GB              | 1        | 0.7%    |
| SPCC Solid State Disk 120GB         | 1        | 0.7%    |
| SK Hynix PC601 NVMe 256GB           | 1        | 0.7%    |
| SK Hynix NVMe SSD Drive 256GB       | 1        | 0.7%    |
| Silicon Motion NVMe SSD Drive 128GB | 1        | 0.7%    |
| Seagate ST98823AS 80GB              | 1        | 0.7%    |
| Seagate ST9500325AS 500GB           | 1        | 0.7%    |
| Seagate ST9250410AS 250GB           | 1        | 0.7%    |
| Seagate ST500NM0011 500GB           | 1        | 0.7%    |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 0.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 27       | 37     | 39.13%  |
| WDC                 | 20       | 31     | 28.99%  |
| Toshiba             | 11       | 11     | 15.94%  |
| Hitachi             | 5        | 6      | 7.25%   |
| Samsung Electronics | 3        | 4      | 4.35%   |
| Unknown             | 2        | 2      | 2.9%    |
| HGST                | 1        | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 12     | 17.78%  |
| Kingston            | 7        | 8      | 15.56%  |
| SanDisk             | 6        | 6      | 13.33%  |
| WDC                 | 4        | 4      | 8.89%   |
| Crucial             | 4        | 4      | 8.89%   |
| JMicron             | 3        | 3      | 6.67%   |
| LITEONIT            | 2        | 2      | 4.44%   |
| Fujitsu             | 2        | 2      | 4.44%   |
| China               | 2        | 5      | 4.44%   |
| Team                | 1        | 2      | 2.22%   |
| SPCC                | 1        | 1      | 2.22%   |
| PNY                 | 1        | 1      | 2.22%   |
| PLEXTOR             | 1        | 1      | 2.22%   |
| OCZ                 | 1        | 1      | 2.22%   |
| Intenso             | 1        | 1      | 2.22%   |
| FORESEE             | 1        | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 51       | 92     | 52.58%  |
| SSD  | 36       | 54     | 37.11%  |
| NVMe | 10       | 14     | 10.31%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 59       | 138    | 77.63%  |
| NVMe | 10       | 14     | 13.16%  |
| SAS  | 7        | 8      | 9.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 52       | 96     | 55.91%  |
| 0.51-1.0   | 26       | 33     | 27.96%  |
| 1.01-2.0   | 10       | 12     | 10.75%  |
| 3.01-4.0   | 3        | 3      | 3.23%   |
| 2.01-3.0   | 1        | 1      | 1.08%   |
| 4.01-10.0  | 1        | 1      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 21       | 30%     |
| 101-250        | 14       | 20%     |
| 501-1000       | 12       | 17.14%  |
| 1001-2000      | 10       | 14.29%  |
| 2001-3000      | 4        | 5.71%   |
| 51-100         | 3        | 4.29%   |
| Unknown        | 3        | 4.29%   |
| More than 3000 | 1        | 1.43%   |
| 21-50          | 1        | 1.43%   |
| 1-20           | 1        | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 17       | 23.94%  |
| 101-250        | 17       | 23.94%  |
| 1-20           | 13       | 18.31%  |
| 51-100         | 7        | 9.86%   |
| 251-500        | 6        | 8.45%   |
| 501-1000       | 5        | 7.04%   |
| Unknown        | 3        | 4.23%   |
| 1001-2000      | 2        | 2.82%   |
| More than 3000 | 1        | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| SanDisk SD6SF1M128G1022I 128GB SSD | 2        | 2      | 9.52%   |
| WDC WD5000AAKS-75V0A0 500GB        | 1        | 1      | 4.76%   |
| WDC WD2003FZEX-00Z4SA0 2TB         | 1        | 1      | 4.76%   |
| WDC WD10JUCX-63WPNY0 1TB           | 1        | 1      | 4.76%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 1      | 4.76%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 4.76%   |
| Seagate ST9250410AS 250GB          | 1        | 1      | 4.76%   |
| Seagate ST500NM0011 500GB          | 1        | 1      | 4.76%   |
| Seagate ST3500413AS 500GB          | 1        | 1      | 4.76%   |
| Seagate ST320LT007-9ZV142 320GB    | 1        | 1      | 4.76%   |
| Seagate ST31000528AS 1TB           | 1        | 1      | 4.76%   |
| Seagate ST250DM000-1BD141 250GB    | 1        | 1      | 4.76%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 4.76%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 4.76%   |
| SanDisk SSD PLUS 480GB             | 1        | 1      | 4.76%   |
| SanDisk SSD PLUS 1000GB            | 1        | 1      | 4.76%   |
| Samsung Electronics HM500JI 500GB  | 1        | 1      | 4.76%   |
| PLEXTOR PX-512M6Pro 512GB SSD      | 1        | 1      | 4.76%   |
| Hitachi HUA722020ALA331 2TB        | 1        | 1      | 4.76%   |
| A-DATA Technology SX7000NP 128GB   | 1        | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 36.84%  |
| WDC                 | 4        | 4      | 21.05%  |
| SanDisk             | 4        | 4      | 21.05%  |
| Samsung Electronics | 1        | 1      | 5.26%   |
| PLEXTOR             | 1        | 1      | 5.26%   |
| Hitachi             | 1        | 1      | 5.26%   |
| A-DATA Technology   | 1        | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 9      | 53.85%  |
| WDC                 | 4        | 4      | 30.77%  |
| Samsung Electronics | 1        | 1      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 15     | 64.71%  |
| SSD  | 5        | 5      | 29.41%  |
| NVMe | 1        | 1      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Intenso SSD SATAIII 512GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Intenso | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 43       | 95     | 51.19%  |
| Works    | 26       | 43     | 30.95%  |
| Malfunc  | 14       | 21     | 16.67%  |
| Failed   | 1        | 1      | 1.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 40       | 51.95%  |
| AMD                 | 22       | 28.57%  |
| Sandisk             | 3        | 3.9%    |
| Samsung Electronics | 3        | 3.9%    |
| SK Hynix            | 2        | 2.6%    |
| Nvidia              | 2        | 2.6%    |
| VIA Technologies    | 1        | 1.3%    |
| Silicon Motion      | 1        | 1.3%    |
| Phison Electronics  | 1        | 1.3%    |
| JMicron Technology  | 1        | 1.3%    |
| ASMedia Technology  | 1        | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 14       | 13.86%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 6.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7        | 6.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 5.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 4.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 4.95%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 4.95%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 3.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3        | 2.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.97%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.98%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.98%   |
| Nvidia MCP61 IDE                                                                        | 2        | 1.98%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 1.98%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 1.98%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.99%   |
| SK Hynix Non-Volatile memory controller                                                 | 1        | 0.99%   |
| SK Hynix BC511                                                                          | 1        | 0.99%   |
| Silicon Motion Non-Volatile memory controller                                           | 1        | 0.99%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.99%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.99%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 0.99%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.99%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.99%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.99%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1        | 0.99%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.99%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.99%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 0.99%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 0.99%   |
| AMD FCH SATA Controller [RAID mode]                                                     | 1        | 0.99%   |
| AMD FCH SATA Controller D                                                               | 1        | 0.99%   |
| AMD FCH RAID Controller                                                                 | 1        | 0.99%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 0.99%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 0.99%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 49       | 61.25%  |
| IDE  | 17       | 21.25%  |
| NVMe | 10       | 12.5%   |
| RAID | 4        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 41       | 63.08%  |
| AMD    | 24       | 36.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-7400 CPU @ 3.00GHz                | 3        | 4.62%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz             | 2        | 3.08%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz     | 2        | 3.08%   |
| Intel Pentium CPU G3260 @ 3.30GHz               | 2        | 3.08%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 2        | 3.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 2        | 3.08%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2        | 3.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 3.08%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 2        | 3.08%   |
| AMD Ryzen 7 1700X Eight-Core Processor          | 2        | 3.08%   |
| Intel Xeon CPU X5460 @ 3.16GHz                  | 1        | 1.54%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 1        | 1.54%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz     | 1        | 1.54%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz          | 1        | 1.54%   |
| Intel Pentium CPU G630 @ 2.70GHz                | 1        | 1.54%   |
| Intel Core M-5Y10c CPU @ 0.80GHz                | 1        | 1.54%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 1.54%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1        | 1.54%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 1.54%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1        | 1.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 1.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1.54%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 1.54%   |
| Intel Core i7 CPU 920 @ 2.67GHz                 | 1        | 1.54%   |
| Intel Core i5-9500T CPU @ 2.20GHz               | 1        | 1.54%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 1.54%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 1        | 1.54%   |
| Intel Core i5-4670S CPU @ 3.10GHz               | 1        | 1.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 1.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 1.54%   |
| Intel Core i3-9100F CPU @ 3.60GHz               | 1        | 1.54%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.54%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 1.54%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz            | 1        | 1.54%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor  | 1        | 1.54%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 1.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 1        | 1.54%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 1.54%   |
| AMD Ryzen 5 3600XT 6-Core Processor             | 1        | 1.54%   |
| AMD Ryzen 5 1600X Six-Core Processor            | 1        | 1.54%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 1        | 1.54%   |
| AMD Phenom II X4 965 Processor                  | 1        | 1.54%   |
| AMD Phenom 8400 Triple-Core Processor           | 1        | 1.54%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 1.54%   |
| AMD FX-8320 Eight-Core Processor                | 1        | 1.54%   |
| AMD FX-6300 Six-Core Processor                  | 1        | 1.54%   |
| AMD Athlon II X2 B26 Processor                  | 1        | 1.54%   |
| AMD Athlon II X2 270 Processor                  | 1        | 1.54%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+      | 1        | 1.54%   |
| AMD Athlon 64 Processor 3800+                   | 1        | 1.54%   |
| AMD A8-5600K APU with Radeon HD Graphics        | 1        | 1.54%   |
| AMD A4-5300B APU with Radeon HD Graphics        | 1        | 1.54%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.54%   |
| AMD A10-5700 APU with Radeon HD Graphics        | 1        | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 13       | 20%     |
| Intel Core i7           | 8        | 12.31%  |
| AMD Ryzen 7             | 5        | 7.69%   |
| Intel Xeon              | 4        | 6.15%   |
| Intel Core i3           | 4        | 6.15%   |
| Intel Pentium Dual-Core | 3        | 4.62%   |
| Intel Pentium           | 3        | 4.62%   |
| Intel Core 2 Duo        | 3        | 4.62%   |
| AMD Ryzen 5             | 3        | 4.62%   |
| AMD FX                  | 3        | 4.62%   |
| AMD Athlon II X2        | 2        | 3.08%   |
| AMD A10                 | 2        | 3.08%   |
| Intel Pentium Dual      | 1        | 1.54%   |
| Intel Core M            | 1        | 1.54%   |
| Intel Core 2 Quad       | 1        | 1.54%   |
| AMD Ryzen Threadripper  | 1        | 1.54%   |
| AMD Ryzen 9             | 1        | 1.54%   |
| AMD Ryzen 3             | 1        | 1.54%   |
| AMD Phenom II X4        | 1        | 1.54%   |
| AMD Phenom              | 1        | 1.54%   |
| AMD Athlon 64 X2        | 1        | 1.54%   |
| AMD Athlon 64           | 1        | 1.54%   |
| AMD A8                  | 1        | 1.54%   |
| AMD A4                  | 1        | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 26       | 40%     |
| 2      | 20       | 30.77%  |
| 8      | 7        | 10.77%  |
| 6      | 6        | 9.23%   |
| 12     | 2        | 3.08%   |
| 3      | 2        | 3.08%   |
| 1      | 2        | 3.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 98.46%  |
| 2      | 1        | 1.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 35       | 53.85%  |
| 2      | 30       | 46.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 65       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 44       | 65.67%  |
| 0x306c3    | 3        | 4.48%   |
| 0x206a7    | 3        | 4.48%   |
| 0x906e9    | 2        | 2.99%   |
| 0x306a9    | 2        | 2.99%   |
| 0x1067a    | 2        | 2.99%   |
| 0x08701021 | 2        | 2.99%   |
| 0x06000852 | 2        | 2.99%   |
| 0x906ed    | 1        | 1.49%   |
| 0x106a5    | 1        | 1.49%   |
| 0x0a201016 | 1        | 1.49%   |
| 0x0800820d | 1        | 1.49%   |
| 0x08001138 | 1        | 1.49%   |
| 0x0600111f | 1        | 1.49%   |
| 0x01000095 | 1        | 1.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 9        | 13.85%  |
| Haswell     | 9        | 13.85%  |
| Piledriver  | 6        | 9.23%   |
| Penryn      | 6        | 9.23%   |
| Zen         | 5        | 7.69%   |
| Skylake     | 4        | 6.15%   |
| SandyBridge | 4        | 6.15%   |
| K10         | 4        | 6.15%   |
| Zen 2       | 3        | 4.62%   |
| IvyBridge   | 3        | 4.62%   |
| Core        | 3        | 4.62%   |
| Zen+        | 2        | 3.08%   |
| K8 Hammer   | 2        | 3.08%   |
| Zen 3       | 1        | 1.54%   |
| Westmere    | 1        | 1.54%   |
| Steamroller | 1        | 1.54%   |
| Nehalem     | 1        | 1.54%   |
| Broadwell   | 1        | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 29       | 39.19%  |
| AMD    | 24       | 32.43%  |
| Intel  | 21       | 28.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 6.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 5.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 5.41%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 3        | 4.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 4.05%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 4.05%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 2        | 2.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 2.7%    |
| Intel HD Graphics 630                                                       | 2        | 2.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 2.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.7%    |
| AMD RS780L [Radeon 3000]                                                    | 2        | 2.7%    |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 2        | 2.7%    |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 2        | 2.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.35%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 1.35%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.35%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.35%   |
| Nvidia GT215 [GeForce GT 240]                                               | 1        | 1.35%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.35%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 1.35%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 1.35%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 1.35%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 1.35%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.35%   |
| Nvidia GF119 [GeForce 510]                                                  | 1        | 1.35%   |
| Nvidia GF110 [GeForce GTX 580]                                              | 1        | 1.35%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.35%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 1.35%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 1        | 1.35%   |
| Nvidia G86 [GeForce 8300 GS]                                                | 1        | 1.35%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 1.35%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 1.35%   |
| Intel HD Graphics 5300                                                      | 1        | 1.35%   |
| Intel HD Graphics 530                                                       | 1        | 1.35%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.35%   |
| AMD Trinity [Radeon HD 7660D]                                               | 1        | 1.35%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 1.35%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 1.35%   |
| AMD Renoir                                                                  | 1        | 1.35%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 1.35%   |
| AMD Juniper XT [Radeon HD 6770]                                             | 1        | 1.35%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 1        | 1.35%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 1.35%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 1.35%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 1.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 27       | 41.54%  |
| 1 x AMD      | 21       | 32.31%  |
| 1 x Intel    | 14       | 21.54%  |
| AMD + Nvidia | 2        | 3.08%   |
| Intel + AMD  | 1        | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 49       | 74.24%  |
| Proprietary | 15       | 22.73%  |
| Unknown     | 2        | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 58.82%  |
| 0.51-1.0   | 8        | 11.76%  |
| 3.01-4.0   | 7        | 10.29%  |
| 1.01-2.0   | 6        | 8.82%   |
| 7.01-8.0   | 4        | 5.88%   |
| 0.01-0.5   | 2        | 2.94%   |
| 5.01-6.0   | 1        | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 11       | 14.86%  |
| Dell                 | 8        | 10.81%  |
| Unknown              | 5        | 6.76%   |
| Philips              | 5        | 6.76%   |
| Goldstar             | 5        | 6.76%   |
| Hewlett-Packard      | 4        | 5.41%   |
| BenQ                 | 4        | 5.41%   |
| AOC                  | 4        | 5.41%   |
| Acer                 | 4        | 5.41%   |
| AUS                  | 3        | 4.05%   |
| Toshiba              | 2        | 2.7%    |
| Panasonic            | 2        | 2.7%    |
| NEC Computers        | 2        | 2.7%    |
| Ancor Communications | 2        | 2.7%    |
| ___                  | 1        | 1.35%   |
| Vizio                | 1        | 1.35%   |
| ViewSonic            | 1        | 1.35%   |
| STD                  | 1        | 1.35%   |
| Sony                 | 1        | 1.35%   |
| Sceptre              | 1        | 1.35%   |
| RIS                  | 1        | 1.35%   |
| Lenovo               | 1        | 1.35%   |
| Insignia             | 1        | 1.35%   |
| Iiyama               | 1        | 1.35%   |
| Eizo                 | 1        | 1.35%   |
| Ativa                | 1        | 1.35%   |
| AGO                  | 1        | 1.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 2        | 2.6%    |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2        | 2.6%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 2.6%    |
| Panasonic TV MEIA08F 1920x540                                         | 2        | 2.6%    |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 2        | 2.6%    |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 2        | 2.6%    |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                     | 2        | 2.6%    |
| AUS LCD Monitor VG245 1920x1080                                       | 2        | 2.6%    |
| Acer X223W ACR0011 1680x1050 473x296mm 22.0-inch                      | 2        | 2.6%    |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 1.3%    |
| Vizio E420VO VIZ0070 1920x1080 930x523mm 42.0-inch                    | 1        | 1.3%    |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1        | 1.3%    |
| Unknown PHILCO 9000 1360x768 1600x900mm 72.3-inch                     | 1        | 1.3%    |
| Unknown LCD Monitor SAMSUNG 3840x1080                                 | 1        | 1.3%    |
| Unknown LCD Monitor HRX 32H4030 1920x1080                             | 1        | 1.3%    |
| STD Monitor STD0001 1920x1080                                         | 1        | 1.3%    |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                   | 1        | 1.3%    |
| Sceptre LCD Monitor P30 2560x1080                                     | 1        | 1.3%    |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM064F 1920x1080 510x290mm 23.1-inch  | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 1        | 1.3%    |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch  | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SyncMaster                            | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM07BC 1360x768 700x390mm 31.5-inch  | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM06AC 1920x1080 890x500mm 40.2-inch | 1        | 1.3%    |
| Samsung Electronics LCD Monitor SAM03FE 1280x720                      | 1        | 1.3%    |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 1        | 1.3%    |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1        | 1.3%    |
| RIS photo24 RIS0902 1920x1080 521x293mm 23.5-inch                     | 1        | 1.3%    |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 1.3%    |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 1        | 1.3%    |
| Philips LCD Monitor PHL 234E5 1920x1080                               | 1        | 1.3%    |
| Philips LCD Monitor PHI32PFL3404 3200x1080                            | 1        | 1.3%    |
| Philips 190C PHL0849 1280x1024 380x300mm 19.1-inch                    | 1        | 1.3%    |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1        | 1.3%    |
| Lenovo L200pwD LEN1156 1680x1050 433x271mm 20.1-inch                  | 1        | 1.3%    |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch           | 1        | 1.3%    |
| Iiyama PL2790 IVM6616 1920x1080 598x336mm 27.0-inch                   | 1        | 1.3%    |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch           | 1        | 1.3%    |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch            | 1        | 1.3%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1        | 1.3%    |
| Goldstar L1742 GSM449B 1280x1024 340x270mm 17.1-inch                  | 1        | 1.3%    |
| Goldstar HDR WFHD GSM7749 2560x1080 798x334mm 34.1-inch               | 1        | 1.3%    |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1        | 1.3%    |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch                | 1        | 1.3%    |
| Eizo S1701 ENC1835 1280x1024 338x270mm 17.0-inch                      | 1        | 1.3%    |
| Dell SE2417HGX DELD0F7 1920x1080 521x293mm 23.5-inch                  | 1        | 1.3%    |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch                     | 1        | 1.3%    |
| Dell S2409W DELA039 1920x1080 530x300mm 24.0-inch                     | 1        | 1.3%    |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 1        | 1.3%    |
| Dell LCD Monitor P2417H                                               | 1        | 1.3%    |
| Dell E2318H DELF092 1920x1080 509x286mm 23.0-inch                     | 1        | 1.3%    |
| Dell E172FP DELA00A 1280x1024 338x270mm 17.0-inch                     | 1        | 1.3%    |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                     | 1        | 1.3%    |
| BenQ GL2580 BNQ78E5 1920x1080 544x303mm 24.5-inch                     | 1        | 1.3%    |
| BenQ G2320HDB BNQ7828 1920x1080 510x287mm 23.0-inch                   | 1        | 1.3%    |
| AUS LCD Monitor VG259 1920x1080                                       | 1        | 1.3%    |
| Ativa AT22HZR ATV0100 1920x1080 497x292mm 22.7-inch                   | 1        | 1.3%    |
| AOC LCD Monitor 2217 1680x1050                                        | 1        | 1.3%    |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch                         | 1        | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 37       | 50.68%  |
| 1680x1050 (WSXGA+) | 7        | 9.59%   |
| 1280x1024 (SXGA)   | 6        | 8.22%   |
| 1360x768           | 5        | 6.85%   |
| 1440x900 (WXGA+)   | 4        | 5.48%   |
| 1920x1200 (WUXGA)  | 3        | 4.11%   |
| 3840x2160 (4K)     | 2        | 2.74%   |
| 2560x1080          | 2        | 2.74%   |
| 1920x540           | 2        | 2.74%   |
| Unknown            | 2        | 2.74%   |
| 3840x1080          | 1        | 1.37%   |
| 3200x1080          | 1        | 1.37%   |
| 1280x720 (HD)      | 1        | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 20%     |
| 24      | 12       | 16%     |
| 27      | 10       | 13.33%  |
| 23      | 8        | 10.67%  |
| 22      | 5        | 6.67%   |
| 19      | 5        | 6.67%   |
| 21      | 4        | 5.33%   |
| 17      | 4        | 5.33%   |
| 31      | 3        | 4%      |
| 32      | 2        | 2.67%   |
| 72      | 1        | 1.33%   |
| 42      | 1        | 1.33%   |
| 40      | 1        | 1.33%   |
| 34      | 1        | 1.33%   |
| 25      | 1        | 1.33%   |
| 20      | 1        | 1.33%   |
| 12      | 1        | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 26       | 36.11%  |
| Unknown     | 15       | 20.83%  |
| 401-500     | 14       | 19.44%  |
| 601-700     | 4        | 5.56%   |
| 301-350     | 4        | 5.56%   |
| 701-800     | 3        | 4.17%   |
| 351-400     | 2        | 2.78%   |
| 801-900     | 1        | 1.39%   |
| 201-300     | 1        | 1.39%   |
| 1501-2000   | 1        | 1.39%   |
| 901-1000    | 1        | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 35       | 51.47%  |
| 16/10   | 11       | 16.18%  |
| Unknown | 11       | 16.18%  |
| 5/4     | 6        | 8.82%   |
| 32/9    | 2        | 2.94%   |
| 4/3     | 1        | 1.47%   |
| 3/2     | 1        | 1.47%   |
| 21/9    | 1        | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 20       | 27.03%  |
| Unknown        | 15       | 20.27%  |
| 301-350        | 10       | 13.51%  |
| 151-200        | 9        | 12.16%  |
| 351-500        | 6        | 8.11%   |
| 251-300        | 6        | 8.11%   |
| 141-150        | 4        | 5.41%   |
| 501-1000       | 2        | 2.7%    |
| More than 1000 | 1        | 1.35%   |
| 71-80          | 1        | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 41       | 62.12%  |
| Unknown | 15       | 22.73%  |
| 101-120 | 4        | 6.06%   |
| 1-50    | 3        | 4.55%   |
| 161-240 | 2        | 3.03%   |
| 121-160 | 1        | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 70.15%  |
| 2     | 16       | 23.88%  |
| 0     | 3        | 4.48%   |
| 3     | 1        | 1.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 46       | 40%     |
| Intel                           | 19       | 16.52%  |
| Ralink Technology               | 8        | 6.96%   |
| Qualcomm Atheros                | 6        | 5.22%   |
| Broadcom                        | 6        | 5.22%   |
| Qualcomm Atheros Communications | 3        | 2.61%   |
| Microsoft                       | 3        | 2.61%   |
| D-Link System                   | 3        | 2.61%   |
| Ralink                          | 2        | 1.74%   |
| OnePlus                         | 2        | 1.74%   |
| Nvidia                          | 2        | 1.74%   |
| Netgear                         | 2        | 1.74%   |
| MediaTek                        | 2        | 1.74%   |
| Broadcom Limited                | 2        | 1.74%   |
| ASUSTek Computer                | 2        | 1.74%   |
| TP-Link                         | 1        | 0.87%   |
| Samsung Electronics             | 1        | 0.87%   |
| Linksys                         | 1        | 0.87%   |
| ICS Advent                      | 1        | 0.87%   |
| Huawei Technologies             | 1        | 0.87%   |
| Gemtek                          | 1        | 0.87%   |
| D-Link                          | 1        | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 35       | 27.78%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 4        | 3.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4        | 3.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 3.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 4        | 3.17%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4        | 3.17%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 2.38%   |
| Intel I211 Gigabit Network Connection                                  | 3        | 2.38%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 2.38%   |
| OnePlus IN2017                                                         | 2        | 1.59%   |
| Nvidia MCP61 Ethernet                                                  | 2        | 1.59%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 2        | 1.59%   |
| Intel Ethernet Connection I217-LM                                      | 2        | 1.59%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2        | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 2        | 1.59%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]     | 2        | 1.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 0.79%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.79%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 0.79%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                        | 1        | 0.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.79%   |
| Realtek 802.11n WLAN Adapter                                           | 1        | 0.79%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 1        | 0.79%   |
| Ralink RT2500 Wireless 802.11bg                                        | 1        | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 0.79%   |
| Netgear WPN111 RangeMax Wireless USB 2.0 Adapter                       | 1        | 0.79%   |
| Netgear WG111T                                                         | 1        | 0.79%   |
| Microsoft Xbox360 Wireless Networking Adapter                          | 1        | 0.79%   |
| MediaTek WP7                                                           | 1        | 0.79%   |
| MediaTek vivo                                                          | 1        | 0.79%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 0.79%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]    | 1        | 0.79%   |
| Intel Wireless 7265                                                    | 1        | 0.79%   |
| Intel Wireless 3160                                                    | 1        | 0.79%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 0.79%   |
| Intel Ethernet Connection I217-V                                       | 1        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 0.79%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 0.79%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 0.79%   |
| ICS Advent USB 10/100 LAN                                              | 1        | 0.79%   |
| Huawei LTE Handset                                                     | 1        | 0.79%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                      | 1        | 0.79%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 0.79%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                         | 1        | 0.79%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1        | 0.79%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                  | 1        | 0.79%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1        | 0.79%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter             | 1        | 0.79%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 1        | 0.79%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 1        | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 13       | 25%     |
| Ralink Technology               | 8        | 15.38%  |
| Qualcomm Atheros                | 5        | 9.62%   |
| Intel                           | 4        | 7.69%   |
| Broadcom                        | 4        | 7.69%   |
| Qualcomm Atheros Communications | 3        | 5.77%   |
| Microsoft                       | 3        | 5.77%   |
| Ralink                          | 2        | 3.85%   |
| Netgear                         | 2        | 3.85%   |
| ASUSTek Computer                | 2        | 3.85%   |
| TP-Link                         | 1        | 1.92%   |
| Linksys                         | 1        | 1.92%   |
| Gemtek                          | 1        | 1.92%   |
| D-Link System                   | 1        | 1.92%   |
| D-Link                          | 1        | 1.92%   |
| Broadcom Limited                | 1        | 1.92%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 4        | 7.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4        | 7.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 4        | 7.55%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 7.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 4        | 7.55%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3        | 5.66%   |
| Microsoft Xbox 360 Wireless Adapter                                    | 2        | 3.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 2        | 3.77%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]     | 2        | 3.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 1.89%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                    | 1        | 1.89%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                        | 1        | 1.89%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 1.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.89%   |
| Realtek 802.11n WLAN Adapter                                           | 1        | 1.89%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 1        | 1.89%   |
| Ralink RT2500 Wireless 802.11bg                                        | 1        | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.89%   |
| Netgear WPN111 RangeMax Wireless USB 2.0 Adapter                       | 1        | 1.89%   |
| Netgear WG111T                                                         | 1        | 1.89%   |
| Microsoft Xbox360 Wireless Networking Adapter                          | 1        | 1.89%   |
| Linksys WUSB6300 802.11a/b/g/n/ac Wireless Adapter [Realtek RTL8812AU] | 1        | 1.89%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]    | 1        | 1.89%   |
| Intel Wireless 7265                                                    | 1        | 1.89%   |
| Intel Wireless 3160                                                    | 1        | 1.89%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 1.89%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                      | 1        | 1.89%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 1.89%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                         | 1        | 1.89%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter             | 1        | 1.89%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 1        | 1.89%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 1        | 1.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 41       | 58.57%  |
| Intel                 | 16       | 22.86%  |
| Qualcomm Atheros      | 2        | 2.86%   |
| Nvidia                | 2        | 2.86%   |
| MediaTek              | 2        | 2.86%   |
| D-Link System         | 2        | 2.86%   |
| Broadcom              | 2        | 2.86%   |
| Samsung Electronics   | 1        | 1.43%   |
| ICS Advent            | 1        | 1.43%   |
| Broadcom Limited      | 1        | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35       | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 5.71%   |
| Intel I211 Gigabit Network Connection                             | 3        | 4.29%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.29%   |
| Nvidia MCP61 Ethernet                                             | 2        | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.86%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2        | 2.86%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 1.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.43%   |
| MediaTek WP7                                                      | 1        | 1.43%   |
| MediaTek vivo                                                     | 1        | 1.43%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.43%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.43%   |
| ICS Advent USB 10/100 LAN                                         | 1        | 1.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.43%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1        | 1.43%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 63       | 56.25%  |
| WiFi     | 46       | 41.07%  |
| Unknown  | 3        | 2.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 48       | 61.54%  |
| WiFi     | 29       | 37.18%  |
| Unknown  | 1        | 1.28%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 66.15%  |
| 2     | 18       | 27.69%  |
| 3     | 2        | 3.08%   |
| 0     | 2        | 3.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 87.88%  |
| Yes  | 8        | 12.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 7        | 38.89%  |
| Intel                           | 4        | 22.22%  |
| Qualcomm Atheros Communications | 3        | 16.67%  |
| Realtek Semiconductor           | 1        | 5.56%   |
| IMC Networks                    | 1        | 5.56%   |
| Dell                            | 1        | 5.56%   |
| Apple                           | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7        | 38.89%  |
| Qualcomm Atheros  Bluetooth Device                  | 3        | 16.67%  |
| Intel Bluetooth wireless interface                  | 2        | 11.11%  |
| Realtek Bluetooth Radio                             | 1        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 5.56%   |
| Intel AX200 Bluetooth                               | 1        | 5.56%   |
| IMC Networks Bluetooth Device                       | 1        | 5.56%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1        | 5.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 40       | 38.1%   |
| AMD                    | 32       | 30.48%  |
| Nvidia                 | 26       | 24.76%  |
| C-Media Electronics    | 3        | 2.86%   |
| Yamaha                 | 1        | 0.95%   |
| Logitech               | 1        | 0.95%   |
| GYROCOM C&C            | 1        | 0.95%   |
| Generalplus Technology | 1        | 0.95%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 6.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 7        | 5.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 5.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 7        | 5.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 6        | 4.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 5        | 3.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 3.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 5        | 3.88%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 3.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4        | 3.1%    |
| AMD FCH Azalia Controller                                                         | 4        | 3.1%    |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 2.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 2.33%   |
| Intel 200 Series PCH HD Audio                                                     | 3        | 2.33%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 2.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 2.33%   |
| Nvidia MCP61 High Definition Audio                                                | 2        | 1.55%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.55%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2        | 1.55%   |
| Nvidia GF119 HDMI Audio Controller                                                | 2        | 1.55%   |
| Nvidia GF106 High Definition Audio Controller                                     | 2        | 1.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 1.55%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 2        | 1.55%   |
| C-Media Electronics CM108 Audio Controller                                        | 2        | 1.55%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 1.55%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 2        | 1.55%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 1.55%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.55%   |
| Yamaha Steinberg UR22mkII                                                         | 1        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 0.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 0.78%   |
| Nvidia High Definition Audio Controller                                           | 1        | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 0.78%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1        | 0.78%   |
| Nvidia GF110 High Definition Audio Controller                                     | 1        | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 0.78%   |
| Logitech G432 Gaming Headset                                                      | 1        | 0.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 0.78%   |
| Intel USB PnP Sound Device                                                        | 1        | 0.78%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 0.78%   |
| GYROCOM C&C NuForce ÂµDAC 2 HP                                                  | 1        | 0.78%   |
| Generalplus Technology USB Audio Device                                           | 1        | 0.78%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1        | 0.78%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 0.78%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1        | 0.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 10       | 31.25%  |
| Crucial             | 4        | 12.5%   |
| Corsair             | 4        | 12.5%   |
| SK Hynix            | 3        | 9.38%   |
| Kingston            | 3        | 9.38%   |
| Samsung Electronics | 2        | 6.25%   |
| G.Skill             | 2        | 6.25%   |
| Silicon Power       | 1        | 3.13%   |
| S                   | 1        | 3.13%   |
| Nanya Technology    | 1        | 3.13%   |
| Micron Technology   | 1        | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 2        | 6.06%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s   | 2        | 6.06%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1        | 3.03%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s               | 1        | 3.03%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 3.03%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                  | 1        | 3.03%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                       | 1        | 3.03%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 3.03%   |
| Unknown RAM Module 2GB DIMM                                | 1        | 3.03%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                | 1        | 3.03%   |
| Unknown RAM Module 2048MB DIMM DDR2                        | 1        | 3.03%   |
| SK Hynix RAM HYMP512U64CP8-Y5 1GB DIMM                     | 1        | 3.03%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 3.03%   |
| SK Hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s    | 1        | 3.03%   |
| Silicon Power RAM SP016GBLFU266B02 16GB DIMM DDR4 2667MT/s | 1        | 3.03%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s        | 1        | 3.03%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 3.03%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                        | 1        | 3.03%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s         | 1        | 3.03%   |
| Micron RAM 16JTF51264AZ-1G6K1 4GB DIMM DDR3 1600MT/s       | 1        | 3.03%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s        | 1        | 3.03%   |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s        | 1        | 3.03%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s      | 1        | 3.03%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s     | 1        | 3.03%   |
| G.Skill RAM F4-2400C15-8GIS 8GB DIMM DDR4 2400MT/s         | 1        | 3.03%   |
| Crucial RAM CT8G4DFS824A.C8FDD1 8GB DIMM DDR4 3200MT/s     | 1        | 3.03%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s      | 1        | 3.03%   |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s        | 1        | 3.03%   |
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s       | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s      | 1        | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 14       | 50%     |
| DDR4    | 8        | 28.57%  |
| DDR2    | 3        | 10.71%  |
| Unknown | 2        | 7.14%   |
| SDRAM   | 1        | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 28       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 12       | 40%     |
| 4096  | 9        | 30%     |
| 2048  | 5        | 16.67%  |
| 16384 | 2        | 6.67%   |
| 1024  | 2        | 6.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 33.33%  |
| 2400    | 3        | 10%     |
| Unknown | 3        | 10%     |
| 3600    | 2        | 6.67%   |
| 3200    | 2        | 6.67%   |
| 1333    | 2        | 6.67%   |
| 3466    | 1        | 3.33%   |
| 2667    | 1        | 3.33%   |
| 2666    | 1        | 3.33%   |
| 2133    | 1        | 3.33%   |
| 1866    | 1        | 3.33%   |
| 1067    | 1        | 3.33%   |
| 800     | 1        | 3.33%   |
| 400     | 1        | 3.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| HP OfficeJet Pro 7720 series | 1        | 100%    |

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
| Logitech            | 3        | 23.08%  |
| Microdia            | 2        | 15.38%  |
| Creative Technology | 2        | 15.38%  |
| Teslong Camera      | 1        | 7.69%   |
| Razer USA           | 1        | 7.69%   |
| LG Electronics      | 1        | 7.69%   |
| Jieli Technology    | 1        | 7.69%   |
| IMC Networks        | 1        | 7.69%   |
| Apple               | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Creative Live! Cam Sync HD [VF0770]                   | 2        | 15.38%  |
| Teslong Camera                                        | 1        | 7.69%   |
| Razer USA Gaming Webcam [Kiyo]                        | 1        | 7.69%   |
| Microdia Webcam Vitade AF                             | 1        | 7.69%   |
| Microdia PC Microscope camera                         | 1        | 7.69%   |
| Logitech Webcam C270                                  | 1        | 7.69%   |
| Logitech HD Webcam C615                               | 1        | 7.69%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 7.69%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 7.69%   |
| Jieli USB PHY 2.0                                     | 1        | 7.69%   |
| IMC Networks XHC Camera                               | 1        | 7.69%   |
| Apple iPhone 5/5C/5S/6/SE                             | 1        | 7.69%   |

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

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 50       | 75.76%  |
| 1     | 14       | 21.21%  |
| 2     | 2        | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 10       | 55.56%  |
| Graphics card            | 3        | 16.67%  |
| Storage/raid             | 1        | 5.56%   |
| Net/ethernet             | 1        | 5.56%   |
| Multimedia controller    | 1        | 5.56%   |
| Communication controller | 1        | 5.56%   |
| Camera                   | 1        | 5.56%   |

