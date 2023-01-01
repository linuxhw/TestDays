Parrot 4.11 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 26

| Vendor    | Model                   | Probe                                                      | Date         |
|-----------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | PRIME B450M-K           | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| Gigabyte  | H110M-H DDR3-CF         | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| ASUSTek   | B85M-E                  | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| Wistron   | JIG31B3                 | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek   | F2A85-M                 | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek   | F2A85-M                 | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| MSI       | G31M3-L V2              | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| ASUSTek   | Benicia                 | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek   | ROG STRIX B450-F GAMING | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| ASUSTek   | M5A99X EVO              | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Alienware | 0PGRP5 A02              | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock    | Z87 Killer              | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Acer      | Aspire TC-780           | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Dell      | 0T2HR0 A00              | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek   | P8H67-M PRO             | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte  | A320M-S2H-CF            | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Gigabyte  | A320M-S2H-CF            | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| ZOTAC     | Unknown                 | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC     | Unknown                 | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| HP        | 1850                    | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell      | 0T10XW A02              | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| HP        | 1850                    | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| Dell      | 0C1R19 A02              | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| ASUSTek   | PRIME X399-A            | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer      | Predator PO3-600 V:1.1  | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| ASUSTek   | M5A78L-M/USB3           | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.0-6parrot1-amd64  | 6        | 27.27%  |
| 5.14.0-9parrot1-amd64  | 4        | 18.18%  |
| 5.10.0-8parrot1-amd64  | 3        | 13.64%  |
| 5.15.0-15parrot1-amd64 | 2        | 9.09%   |
| 5.10.0-3parrot1-amd64  | 2        | 9.09%   |
| 6.0.0-2parrot1-amd64   | 1        | 4.55%   |
| 5.7.0-2parrot2-amd64   | 1        | 4.55%   |
| 5.16.0-12parrot1-amd64 | 1        | 4.55%   |
| 5.14.0-2parrot1-amd64  | 1        | 4.55%   |
| 5.10.0-5parrot1-amd64  | 1        | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 12       | 54.55%  |
| 5.14.0  | 5        | 22.73%  |
| 5.15.0  | 2        | 9.09%   |
| 6.0.0   | 1        | 4.55%   |
| 5.7.0   | 1        | 4.55%   |
| 5.16.0  | 1        | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 12       | 54.55%  |
| 5.14    | 5        | 22.73%  |
| 5.15    | 2        | 9.09%   |
| 6.0     | 1        | 4.55%   |
| 5.7     | 1        | 4.55%   |
| 5.16    | 1        | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 22       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 12       | 52.17%  |
| KDE5    | 7        | 30.43%  |
| XFCE    | 2        | 8.7%    |
| KDE     | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 22       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 11       | 47.83%  |
| Unknown | 8        | 34.78%  |
| TDM     | 3        | 13.04%  |
| SDDM    | 1        | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 50%     |
| ru_RU | 2        | 9.09%   |
| pt_BR | 2        | 9.09%   |
| ru_UA | 1        | 4.55%   |
| pl_PL | 1        | 4.55%   |
| fr_FR | 1        | 4.55%   |
| en_AU | 1        | 4.55%   |
| de_DE | 1        | 4.55%   |
| cs_CZ | 1        | 4.55%   |
| an_ES | 1        | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 16       | 69.57%  |
| EFI  | 7        | 30.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 16       | 72.73%  |
| Ext4    | 4        | 18.18%  |
| Xfs     | 1        | 4.55%   |
| Overlay | 1        | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 10       | 43.48%  |
| Unknown | 10       | 43.48%  |
| MBR     | 3        | 13.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 78.26%  |
| Yes       | 5        | 21.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 54.55%  |
| No        | 10       | 45.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 40.91%  |
| Dell                | 3        | 13.64%  |
| Gigabyte Technology | 2        | 9.09%   |
| Acer                | 2        | 9.09%   |
| ZOTAC               | 1        | 4.55%   |
| Wistron             | 1        | 4.55%   |
| MSI                 | 1        | 4.55%   |
| Hewlett-Packard     | 1        | 4.55%   |
| ASRock              | 1        | 4.55%   |
| Alienware           | 1        | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Wistron FMVDD2A0H0           | 1        | 4.55%   |
| MSI MS-7529                  | 1        | 4.55%   |
| HP Compaq Pro 6305 MT        | 1        | 4.55%   |
| Gigabyte H110M-H DDR3        | 1        | 4.55%   |
| Gigabyte A320M-S2H           | 1        | 4.55%   |
| Dell XPS 8930                | 1        | 4.55%   |
| Dell OptiPlex 7070           | 1        | 4.55%   |
| Dell OptiPlex 3010           | 1        | 4.55%   |
| ASUS ROG STRIX B450-F GAMING | 1        | 4.55%   |
| ASUS PRIME X399-A            | 1        | 4.55%   |
| ASUS PRIME B450M-K           | 1        | 4.55%   |
| ASUS P8H67-M PRO             | 1        | 4.55%   |
| ASUS M5A99X EVO              | 1        | 4.55%   |
| ASUS M5A78L-M/USB3           | 1        | 4.55%   |
| ASUS KJ250AA-ABE a6336.es    | 1        | 4.55%   |
| ASUS F2A85-M                 | 1        | 4.55%   |
| ASUS Basic 3221BM            | 1        | 4.55%   |
| ASRock Z87 Killer            | 1        | 4.55%   |
| Alienware X51 R2             | 1        | 4.55%   |
| Acer Predator PO3-600        | 1        | 4.55%   |
| Acer Aspire TC-780           | 1        | 4.55%   |
| Unknown                      | 1        | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 2        | 9.09%   |
| ASUS PRIME         | 2        | 9.09%   |
| Wistron FMVDD2A0H0 | 1        | 4.55%   |
| MSI MS-7529        | 1        | 4.55%   |
| HP Compaq          | 1        | 4.55%   |
| Gigabyte H110M-H   | 1        | 4.55%   |
| Gigabyte A320M-S2H | 1        | 4.55%   |
| Dell XPS           | 1        | 4.55%   |
| ASUS ROG           | 1        | 4.55%   |
| ASUS P8H67-M       | 1        | 4.55%   |
| ASUS M5A99X        | 1        | 4.55%   |
| ASUS M5A78L-M      | 1        | 4.55%   |
| ASUS KJ250AA-ABE   | 1        | 4.55%   |
| ASUS F2A85-M       | 1        | 4.55%   |
| ASUS Basic         | 1        | 4.55%   |
| ASRock Z87         | 1        | 4.55%   |
| Alienware X51      | 1        | 4.55%   |
| Acer Predator      | 1        | 4.55%   |
| Acer Aspire        | 1        | 4.55%   |
| Unknown            | 1        | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 3        | 13.64%  |
| 2011 | 3        | 13.64%  |
| 2019 | 2        | 9.09%   |
| 2018 | 2        | 9.09%   |
| 2017 | 2        | 9.09%   |
| 2013 | 2        | 9.09%   |
| 2012 | 2        | 9.09%   |
| 2020 | 1        | 4.55%   |
| 2015 | 1        | 4.55%   |
| 2014 | 1        | 4.55%   |
| 2010 | 1        | 4.55%   |
| 2009 | 1        | 4.55%   |
| 2007 | 1        | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 22       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 22       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 6        | 27.27%  |
| 4.01-8.0   | 5        | 22.73%  |
| 8.01-16.0  | 5        | 22.73%  |
| 3.01-4.0   | 2        | 9.09%   |
| 1.01-2.0   | 2        | 9.09%   |
| 32.01-64.0 | 1        | 4.55%   |
| 24.01-32.0 | 1        | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 10       | 45.45%  |
| 4.01-8.0  | 4        | 18.18%  |
| 2.01-3.0  | 4        | 18.18%  |
| 0.51-1.0  | 2        | 9.09%   |
| 3.01-4.0  | 1        | 4.55%   |
| 8.01-16.0 | 1        | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 34.78%  |
| 3      | 6        | 26.09%  |
| 1      | 5        | 21.74%  |
| 4      | 3        | 13.04%  |
| 5      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 65.22%  |
| Yes       | 8        | 34.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 65.22%  |
| No        | 8        | 34.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 63.64%  |
| Yes       | 8        | 36.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 8        | 36.36%  |
| Brazil    | 3        | 13.64%  |
| Russia    | 2        | 9.09%   |
| Germany   | 2        | 9.09%   |
| Vietnam   | 1        | 4.55%   |
| Ukraine   | 1        | 4.55%   |
| Spain     | 1        | 4.55%   |
| Poland    | 1        | 4.55%   |
| France    | 1        | 4.55%   |
| Czechia   | 1        | 4.55%   |
| Australia | 1        | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Eugene              | 2        | 8.7%    |
| Warsaw              | 1        | 4.35%   |
| Uherské Hradiště | 1        | 4.35%   |
| Sydney              | 1        | 4.35%   |
| Sao Paulo           | 1        | 4.35%   |
| Santa Maria         | 1        | 4.35%   |
| Saint Paul          | 1        | 4.35%   |
| Portsmouth          | 1        | 4.35%   |
| Orange Park         | 1        | 4.35%   |
| Nam Định         | 1        | 4.35%   |
| Melbourne           | 1        | 4.35%   |
| Machado             | 1        | 4.35%   |
| Lyon                | 1        | 4.35%   |
| Los Angeles         | 1        | 4.35%   |
| Lafayette           | 1        | 4.35%   |
| Kyiv                | 1        | 4.35%   |
| Khabarovsk          | 1        | 4.35%   |
| Kazan’            | 1        | 4.35%   |
| Hanau               | 1        | 4.35%   |
| Braunschweig        | 1        | 4.35%   |
| Berlin              | 1        | 4.35%   |
| Barcelona           | 1        | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 17     | 22.45%  |
| Samsung Electronics | 8        | 10     | 16.33%  |
| WDC                 | 6        | 6      | 12.24%  |
| Hitachi             | 3        | 4      | 6.12%   |
| Crucial             | 3        | 3      | 6.12%   |
| Unknown             | 2        | 2      | 4.08%   |
| Toshiba             | 2        | 2      | 4.08%   |
| SK hynix            | 2        | 2      | 4.08%   |
| SanDisk             | 2        | 2      | 4.08%   |
| Kingston            | 2        | 2      | 4.08%   |
| SPCC                | 1        | 1      | 2.04%   |
| Phison              | 1        | 1      | 2.04%   |
| LITEONIT            | 1        | 1      | 2.04%   |
| Intenso             | 1        | 1      | 2.04%   |
| HGST                | 1        | 1      | 2.04%   |
| FORESEE             | 1        | 1      | 2.04%   |
| China               | 1        | 2      | 2.04%   |
| AMD                 | 1        | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Unknown SD/MMC/MS PRO 64GB            | 2        | 3.57%   |
| Seagate Expansion 4TB                 | 2        | 3.57%   |
| WDC WDBNCE0010PNC 1TB SSD             | 1        | 1.79%   |
| WDC WD5000AADS-00S9B0 500GB           | 1        | 1.79%   |
| WDC WD5000AACS-00ZUB0 500GB           | 1        | 1.79%   |
| WDC WD3200LPVX-60V0TT0 320GB          | 1        | 1.79%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1        | 1.79%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 1.79%   |
| Toshiba MK2552GSX 250GB               | 1        | 1.79%   |
| Toshiba DT01ACA100 1TB                | 1        | 1.79%   |
| SPCC Solid State Disk 120GB           | 1        | 1.79%   |
| SK hynix PC601 NVMe 256GB             | 1        | 1.79%   |
| SK hynix NVMe SSD Drive 256GB         | 1        | 1.79%   |
| Seagate ST98823AS 80GB                | 1        | 1.79%   |
| Seagate ST9250410AS 250GB             | 1        | 1.79%   |
| Seagate ST500NM0011 500GB             | 1        | 1.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1        | 1.79%   |
| Seagate ST500LM000-SSHD-8GB           | 1        | 1.79%   |
| Seagate ST500DM002-1SB10A 500GB       | 1        | 1.79%   |
| Seagate ST4000DM004-2CV104 4TB        | 1        | 1.79%   |
| Seagate ST3500413AS 500GB             | 1        | 1.79%   |
| Seagate ST3250824AS 250GB             | 1        | 1.79%   |
| Seagate ST31000528AS 1TB              | 1        | 1.79%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1.79%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1        | 1.79%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 1.79%   |
| SanDisk SSD PLUS 1000GB               | 1        | 1.79%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 1        | 1.79%   |
| Samsung SSD SM841N 2.5 7mm 256GB      | 1        | 1.79%   |
| Samsung SSD 970 EVO 500GB             | 1        | 1.79%   |
| Samsung SSD 860 EVO 500GB             | 1        | 1.79%   |
| Samsung SSD 860 EVO 250GB             | 1        | 1.79%   |
| Samsung SSD 840 Series 250GB          | 1        | 1.79%   |
| Samsung NVMe SSD Drive 1TB            | 1        | 1.79%   |
| Samsung HD502HI 500GB                 | 1        | 1.79%   |
| Samsung HD253GJ 250GB                 | 1        | 1.79%   |
| Samsung HD161GJ 160GB                 | 1        | 1.79%   |
| Samsung HD154UI 1TB                   | 1        | 1.79%   |
| Phison NVMe SSD Drive 1TB             | 1        | 1.79%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD | 1        | 1.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 17     | 40.74%  |
| WDC                 | 5        | 5      | 18.52%  |
| Samsung Electronics | 3        | 4      | 11.11%  |
| Hitachi             | 3        | 4      | 11.11%  |
| Unknown             | 2        | 2      | 7.41%   |
| Toshiba             | 2        | 2      | 7.41%   |
| HGST                | 1        | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 17.65%  |
| Crucial             | 3        | 3      | 17.65%  |
| SanDisk             | 2        | 2      | 11.76%  |
| Kingston            | 2        | 2      | 11.76%  |
| WDC                 | 1        | 1      | 5.88%   |
| SPCC                | 1        | 1      | 5.88%   |
| LITEONIT            | 1        | 1      | 5.88%   |
| Intenso             | 1        | 1      | 5.88%   |
| FORESEE             | 1        | 1      | 5.88%   |
| China               | 1        | 2      | 5.88%   |
| AMD                 | 1        | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 35     | 48.65%  |
| SSD  | 14       | 19     | 37.84%  |
| NVMe | 5        | 5      | 13.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 20       | 50     | 71.43%  |
| NVMe | 5        | 5      | 17.86%  |
| SAS  | 3        | 4      | 10.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 19       | 37     | 52.78%  |
| 0.51-1.0   | 12       | 12     | 33.33%  |
| 3.01-4.0   | 3        | 3      | 8.33%   |
| 1.01-2.0   | 2        | 2      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 6        | 25%     |
| 101-250    | 6        | 25%     |
| 1001-2000  | 5        | 20.83%  |
| 2001-3000  | 2        | 8.33%   |
| 501-1000   | 2        | 8.33%   |
| Unknown    | 2        | 8.33%   |
| 51-100     | 1        | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 7        | 29.17%  |
| 21-50     | 5        | 20.83%  |
| 1-20      | 3        | 12.5%   |
| 51-100    | 3        | 12.5%   |
| 251-500   | 2        | 8.33%   |
| Unknown   | 2        | 8.33%   |
| 1001-2000 | 1        | 4.17%   |
| 501-1000  | 1        | 4.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB        | 1        | 1      | 8.33%   |
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 1      | 8.33%   |
| Seagate ST9250410AS 250GB          | 1        | 1      | 8.33%   |
| Seagate ST500NM0011 500GB          | 1        | 1      | 8.33%   |
| Seagate ST3500413AS 500GB          | 1        | 1      | 8.33%   |
| Seagate ST3250824AS 250GB          | 1        | 1      | 8.33%   |
| Seagate ST31000528AS 1TB           | 1        | 1      | 8.33%   |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 8.33%   |
| SanDisk SSD PLUS 1000GB            | 1        | 1      | 8.33%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1        | 1      | 8.33%   |
| Samsung Electronics HD154UI 1TB    | 1        | 1      | 8.33%   |
| Hitachi HUA722020ALA331 2TB        | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 45.45%  |
| WDC                 | 2        | 2      | 18.18%  |
| SanDisk             | 2        | 2      | 18.18%  |
| Samsung Electronics | 1        | 1      | 9.09%   |
| Hitachi             | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 55.56%  |
| WDC                 | 2        | 2      | 22.22%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 10     | 77.78%  |
| SSD  | 2        | 2      | 22.22%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Intenso SSD SATAIII 128GB | 1        | 1      | 100%    |

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
| Works    | 13       | 20     | 37.14%  |
| Detected | 12       | 26     | 34.29%  |
| Malfunc  | 9        | 12     | 25.71%  |
| Failed   | 1        | 1      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 14       | 48.28%  |
| AMD                 | 8        | 27.59%  |
| SK hynix            | 2        | 6.9%    |
| Samsung Electronics | 2        | 6.9%    |
| VIA Technologies    | 1        | 3.45%   |
| Phison Electronics  | 1        | 3.45%   |
| JMicron Technology  | 1        | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 13.89%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 5.56%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 5.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 5.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 5.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 5.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 5.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 5.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 5.56%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 2.78%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 2.78%   |
| SK hynix BC511                                                                          | 1        | 2.78%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 2.78%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 2.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 2.78%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 2.78%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 2.78%   |
| AMD FCH SATA Controller D                                                               | 1        | 2.78%   |
| AMD FCH RAID Controller                                                                 | 1        | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 57.14%  |
| NVMe | 5        | 17.86%  |
| IDE  | 4        | 14.29%  |
| RAID | 3        | 10.71%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 63.64%  |
| AMD    | 8        | 36.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz            | 1        | 4.55%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 4.55%   |
| Intel Pentium CPU G3260 @ 3.30GHz              | 1        | 4.55%   |
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1        | 4.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 4.55%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 4.55%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 4.55%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1        | 4.55%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 4.55%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 4.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 4.55%   |
| Intel Core i3-7100 CPU @ 3.90GHz               | 1        | 4.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 4.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 4.55%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 4.55%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 4.55%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 1        | 4.55%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 4.55%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 4.55%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 4.55%   |
| AMD A8-5600K APU with Radeon HD Graphics       | 1        | 4.55%   |
| AMD A4-5300B APU with Radeon HD Graphics       | 1        | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 4        | 18.18%  |
| Intel Core i7          | 3        | 13.64%  |
| AMD Ryzen 5            | 2        | 9.09%   |
| AMD FX                 | 2        | 9.09%   |
| Intel Xeon             | 1        | 4.55%   |
| Intel Pentium Dual     | 1        | 4.55%   |
| Intel Pentium          | 1        | 4.55%   |
| Intel Core M           | 1        | 4.55%   |
| Intel Core i3          | 1        | 4.55%   |
| Intel Core 2 Quad      | 1        | 4.55%   |
| Intel Core 2 Duo       | 1        | 4.55%   |
| AMD Ryzen Threadripper | 1        | 4.55%   |
| AMD Ryzen 3            | 1        | 4.55%   |
| AMD A8                 | 1        | 4.55%   |
| AMD A4                 | 1        | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 40.91%  |
| 2      | 6        | 27.27%  |
| 6      | 4        | 18.18%  |
| 12     | 1        | 4.55%   |
| 3      | 1        | 4.55%   |
| 1      | 1        | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 59.09%  |
| 1      | 9        | 40.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 22       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 43.48%  |
| 0x906e9    | 2        | 8.7%    |
| 0x306c3    | 2        | 8.7%    |
| 0x06000852 | 2        | 8.7%    |
| 0x906ed    | 1        | 4.35%   |
| 0x306a9    | 1        | 4.35%   |
| 0x206a7    | 1        | 4.35%   |
| 0x1067a    | 1        | 4.35%   |
| 0x0a201016 | 1        | 4.35%   |
| 0x08108109 | 1        | 4.35%   |
| 0x0600111f | 1        | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 5        | 22.73%  |
| Piledriver  | 4        | 18.18%  |
| Haswell     | 3        | 13.64%  |
| Zen         | 2        | 9.09%   |
| Core        | 2        | 9.09%   |
| Zen+        | 1        | 4.55%   |
| Zen 3       | 1        | 4.55%   |
| SandyBridge | 1        | 4.55%   |
| Penryn      | 1        | 4.55%   |
| IvyBridge   | 1        | 4.55%   |
| Broadwell   | 1        | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 10       | 40%     |
| AMD    | 8        | 32%     |
| Intel  | 7        | 28%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 8%      |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 8%      |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 4%      |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 4%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 4%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 4%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 4%      |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 4%      |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 4%      |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 4%      |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 4%      |
| Nvidia G86 [GeForce 8300 GS]                                                | 1        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 4%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 4%      |
| Intel HD Graphics 5300                                                      | 1        | 4%      |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 4%      |
| AMD RS780L [Radeon 3000]                                                    | 1        | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 4%      |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 4%      |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 4%      |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 4%      |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 4%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 9        | 40.91%  |
| 1 x AMD      | 6        | 27.27%  |
| 1 x Intel    | 5        | 22.73%  |
| Intel + AMD  | 1        | 4.55%   |
| AMD + Nvidia | 1        | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 16       | 72.73%  |
| Proprietary | 6        | 27.27%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 43.48%  |
| 1.01-2.0   | 4        | 17.39%  |
| 3.01-4.0   | 3        | 13.04%  |
| 7.01-8.0   | 2        | 8.7%    |
| 0.51-1.0   | 2        | 8.7%    |
| 5.01-6.0   | 1        | 4.35%   |
| 0.01-0.5   | 1        | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 5        | 20%     |
| Goldstar            | 3        | 12%     |
| Hewlett-Packard     | 2        | 8%      |
| BenQ                | 2        | 8%      |
| AOC                 | 2        | 8%      |
| Acer                | 2        | 8%      |
| Vizio               | 1        | 4%      |
| Toshiba             | 1        | 4%      |
| Sony                | 1        | 4%      |
| Sceptre             | 1        | 4%      |
| Samsung Electronics | 1        | 4%      |
| Philips             | 1        | 4%      |
| NEC Computers       | 1        | 4%      |
| Insignia            | 1        | 4%      |
| AUS                 | 1        | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch          | 1        | 4%      |
| Toshiba TV TSB0105 1920x540 708x398mm 32.0-inch             | 1        | 4%      |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch         | 1        | 4%      |
| Sceptre LCD Monitor P30 2560x1080                           | 1        | 4%      |
| Samsung Electronics LCD Monitor SAM03FE 1280x720            | 1        | 4%      |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch     | 1        | 4%      |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch | 1        | 4%      |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch | 1        | 4%      |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch | 1        | 4%      |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch  | 1        | 4%      |
| Goldstar L1742 GSM449B 1280x1024 338x270mm 17.0-inch        | 1        | 4%      |
| Goldstar HDR WFHD GSM7749 2560x1080 798x334mm 34.1-inch     | 1        | 4%      |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch      | 1        | 4%      |
| Dell SE2417HGX DELD0F7 1920x1080 521x293mm 23.5-inch        | 1        | 4%      |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch           | 1        | 4%      |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch           | 1        | 4%      |
| Dell E2318H DELF092 1920x1080 509x286mm 23.0-inch           | 1        | 4%      |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch           | 1        | 4%      |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch           | 1        | 4%      |
| BenQ E2200HD BNQ790B 1920x1080 476x268mm 21.5-inch          | 1        | 4%      |
| AUS LCD Monitor VG259 1920x1080                             | 1        | 4%      |
| AOC LCD Monitor 2217 1680x1050                              | 1        | 4%      |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch               | 1        | 4%      |
| Acer VG240Y S ACR0750 1920x1080 527x296mm 23.8-inch         | 1        | 4%      |
| Acer ED242QR ACR0629 1920x1080 531x299mm 24.0-inch          | 1        | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 13       | 54.17%  |
| 1280x1024 (SXGA)   | 3        | 12.5%   |
| 2560x1080          | 2        | 8.33%   |
| 1680x1050 (WSXGA+) | 2        | 8.33%   |
| 1920x1200 (WUXGA)  | 1        | 4.17%   |
| 1440x900 (WXGA+)   | 1        | 4.17%   |
| 1360x768           | 1        | 4.17%   |
| 1280x720 (HD)      | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 24%     |
| Unknown | 4        | 16%     |
| 23      | 3        | 12%     |
| 27      | 2        | 8%      |
| 19      | 2        | 8%      |
| 17      | 2        | 8%      |
| 42      | 1        | 4%      |
| 34      | 1        | 4%      |
| 32      | 1        | 4%      |
| 31      | 1        | 4%      |
| 22      | 1        | 4%      |
| 21      | 1        | 4%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 41.67%  |
| Unknown     | 4        | 16.67%  |
| 401-500     | 3        | 12.5%   |
| 701-800     | 2        | 8.33%   |
| 301-350     | 2        | 8.33%   |
| 601-700     | 1        | 4.17%   |
| 351-400     | 1        | 4.17%   |
| 901-1000    | 1        | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 56.52%  |
| 5/4     | 3        | 13.04%  |
| 16/10   | 3        | 13.04%  |
| Unknown | 3        | 13.04%  |
| 21/9    | 1        | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 33.33%  |
| Unknown        | 4        | 16.67%  |
| 351-500        | 3        | 12.5%   |
| 151-200        | 3        | 12.5%   |
| 301-350        | 2        | 8.33%   |
| 141-150        | 2        | 8.33%   |
| 251-300        | 1        | 4.17%   |
| 501-1000       | 1        | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 71.43%  |
| Unknown | 4        | 19.05%  |
| 1-50    | 1        | 4.76%   |
| 101-120 | 1        | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 68.18%  |
| 2     | 6        | 27.27%  |
| 0     | 1        | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 17       | 45.95%  |
| Intel                           | 5        | 13.51%  |
| Ralink                          | 2        | 5.41%   |
| Qualcomm Atheros Communications | 2        | 5.41%   |
| Qualcomm Atheros                | 2        | 5.41%   |
| Broadcom Limited                | 2        | 5.41%   |
| Broadcom                        | 2        | 5.41%   |
| Ralink Technology               | 1        | 2.7%    |
| OnePlus Technology (Shenzhen)   | 1        | 2.7%    |
| Microsoft                       | 1        | 2.7%    |
| D-Link System                   | 1        | 2.7%    |
| D-Link                          | 1        | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 14       | 35.9%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 5.13%   |
| Intel I211 Gigabit Network Connection                                | 2        | 5.13%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 1        | 2.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1        | 2.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 2.56%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1        | 2.56%   |
| Ralink RT2500 Wireless 802.11bg                                      | 1        | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 2.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 2.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1        | 2.56%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:3BB6B401                           | 1        | 2.56%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 2.56%   |
| Intel Wireless 7265                                                  | 1        | 2.56%   |
| Intel Wireless 3160                                                  | 1        | 2.56%   |
| Intel Ethernet Connection (7) I219-LM                                | 1        | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 2.56%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 2.56%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 1        | 2.56%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                | 1        | 2.56%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe             | 1        | 2.56%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1        | 2.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 20%     |
| Ralink                          | 2        | 13.33%  |
| Qualcomm Atheros Communications | 2        | 13.33%  |
| Realtek Semiconductor           | 1        | 6.67%   |
| Ralink Technology               | 1        | 6.67%   |
| Qualcomm Atheros                | 1        | 6.67%   |
| Microsoft                       | 1        | 6.67%   |
| D-Link System                   | 1        | 6.67%   |
| D-Link                          | 1        | 6.67%   |
| Broadcom Limited                | 1        | 6.67%   |
| Broadcom                        | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 13.33%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 6.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 6.67%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1        | 6.67%   |
| Ralink RT2500 Wireless 802.11bg                                      | 1        | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 6.67%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 6.67%   |
| Intel Wireless 7265                                                  | 1        | 6.67%   |
| Intel Wireless 3160                                                  | 1        | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 6.67%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 6.67%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 1        | 6.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1        | 6.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 69.57%  |
| Intel                 | 3        | 13.04%  |
| Qualcomm Atheros      | 2        | 8.7%    |
| Broadcom Limited      | 1        | 4.35%   |
| Broadcom              | 1        | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14       | 60.87%  |
| Intel I211 Gigabit Network Connection                             | 2        | 8.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 4.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 4.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 4.35%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1        | 4.35%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 57.89%  |
| WiFi     | 15       | 39.47%  |
| Unknown  | 1        | 2.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 65.38%  |
| WiFi     | 9        | 34.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 59.09%  |
| 2     | 8        | 36.36%  |
| 3     | 1        | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 77.27%  |
| Yes  | 5        | 22.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 37.5%   |
| Cambridge Silicon Radio         | 2        | 25%     |
| Realtek Semiconductor           | 1        | 12.5%   |
| Qualcomm Atheros Communications | 1        | 12.5%   |
| Dell                            | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 2        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 25%     |
| Realtek Bluetooth Radio                             | 1        | 12.5%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 12.5%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 12.5%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 14       | 38.89%  |
| AMD                 | 12       | 33.33%  |
| Nvidia              | 8        | 22.22%  |
| GYROCOM C&C         | 1        | 2.78%   |
| C-Media Electronics | 1        | 2.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 7.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3        | 7.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 4.88%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 4.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 4.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 4.88%   |
| AMD FCH Azalia Controller                                                         | 2        | 4.88%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 4.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 2.44%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 2.44%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 2.44%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 2.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 2.44%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 2.44%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1        | 2.44%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 2.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 2.44%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 2.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 2.44%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 2.44%   |
| GYROCOM C&C NuForce ÂµDAC 2 HP                                                  | 1        | 2.44%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1        | 2.44%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 2.44%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1        | 2.44%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 2.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 2.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 2.44%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Kingston         | 3        | 23.08%  |
| Unknown          | 2        | 15.38%  |
| Crucial          | 2        | 15.38%  |
| Corsair          | 2        | 15.38%  |
| SK hynix         | 1        | 7.69%   |
| S                | 1        | 7.69%   |
| Nanya Technology | 1        | 7.69%   |
| AMD              | 1        | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 7.14%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 7.14%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 7.14%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s    | 1        | 7.14%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                    | 1        | 7.14%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s     | 1        | 7.14%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s | 1        | 7.14%   |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s    | 1        | 7.14%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s  | 1        | 7.14%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s  | 1        | 7.14%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s  | 1        | 7.14%   |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s    | 1        | 7.14%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 1        | 7.14%   |
| AMD RAM R9S416G3000U2S 16GB DIMM DDR4 3000MT/s         | 1        | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 53.85%  |
| DDR4    | 4        | 30.77%  |
| DDR2    | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 13       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 7        | 50%     |
| 4096  | 4        | 28.57%  |
| 16384 | 1        | 7.14%   |
| 2048  | 1        | 7.14%   |
| 1024  | 1        | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 6        | 46.15%  |
| 3600  | 1        | 7.69%   |
| 3000  | 1        | 7.69%   |
| 2666  | 1        | 7.69%   |
| 2400  | 1        | 7.69%   |
| 1867  | 1        | 7.69%   |
| 1333  | 1        | 7.69%   |
| 800   | 1        | 7.69%   |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Microdia            | 1        | 33.33%  |
| Logitech            | 1        | 33.33%  |
| Creative Technology | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Microdia PC Microscope camera       | 1        | 33.33%  |
| Logitech HD Webcam C615             | 1        | 33.33%  |
| Creative Live! Cam Sync HD [VF0770] | 1        | 33.33%  |

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
| 0     | 18       | 81.82%  |
| 1     | 4        | 18.18%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 2        | 50%     |
| Storage/raid | 1        | 25%     |
| Net/ethernet | 1        | 25%     |

