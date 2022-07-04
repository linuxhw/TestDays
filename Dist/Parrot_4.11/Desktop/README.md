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

Total: 24

| Vendor    | Model                   | Probe                                                      | Date         |
|-----------|-------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-6parrot1-amd64  | 5        | 25%     |
| 5.14.0-9parrot1-amd64  | 4        | 20%     |
| 5.10.0-8parrot1-amd64  | 3        | 15%     |
| 5.15.0-15parrot1-amd64 | 2        | 10%     |
| 5.10.0-3parrot1-amd64  | 2        | 10%     |
| 5.7.0-2parrot2-amd64   | 1        | 5%      |
| 5.16.0-12parrot1-amd64 | 1        | 5%      |
| 5.14.0-2parrot1-amd64  | 1        | 5%      |
| 5.10.0-5parrot1-amd64  | 1        | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 11       | 55%     |
| 5.14.0  | 5        | 25%     |
| 5.15.0  | 2        | 10%     |
| 5.7.0   | 1        | 5%      |
| 5.16.0  | 1        | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 11       | 55%     |
| 5.14    | 5        | 25%     |
| 5.15    | 2        | 10%     |
| 5.7     | 1        | 5%      |
| 5.16    | 1        | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 20       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 10       | 47.62%  |
| KDE5    | 7        | 33.33%  |
| XFCE    | 2        | 9.52%   |
| KDE     | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 20       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 9        | 42.86%  |
| Unknown | 8        | 38.1%   |
| TDM     | 3        | 14.29%  |
| SDDM    | 1        | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 10       | 50%     |
| pt_BR | 2        | 10%     |
| ru_UA | 1        | 5%      |
| ru_RU | 1        | 5%      |
| pl_PL | 1        | 5%      |
| fr_FR | 1        | 5%      |
| en_AU | 1        | 5%      |
| de_DE | 1        | 5%      |
| cs_CZ | 1        | 5%      |
| an_ES | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 15       | 71.43%  |
| EFI  | 6        | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 16       | 80%     |
| Ext4  | 4        | 20%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 47.62%  |
| GPT     | 9        | 42.86%  |
| MBR     | 2        | 9.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 76.19%  |
| Yes       | 5        | 23.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 50%     |
| No        | 10       | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 40%     |
| Dell                | 3        | 15%     |
| Acer                | 2        | 10%     |
| ZOTAC               | 1        | 5%      |
| Wistron             | 1        | 5%      |
| MSI                 | 1        | 5%      |
| Hewlett-Packard     | 1        | 5%      |
| Gigabyte Technology | 1        | 5%      |
| ASRock              | 1        | 5%      |
| Alienware           | 1        | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Wistron FMVDD2A0H0           | 1        | 5%      |
| MSI MS-7529                  | 1        | 5%      |
| HP Compaq Pro 6305 MT        | 1        | 5%      |
| Gigabyte A320M-S2H           | 1        | 5%      |
| Dell XPS 8930                | 1        | 5%      |
| Dell OptiPlex 7070           | 1        | 5%      |
| Dell OptiPlex 3010           | 1        | 5%      |
| ASUS ROG STRIX B450-F GAMING | 1        | 5%      |
| ASUS PRIME X399-A            | 1        | 5%      |
| ASUS P8H67-M PRO             | 1        | 5%      |
| ASUS M5A99X EVO              | 1        | 5%      |
| ASUS M5A78L-M/USB3           | 1        | 5%      |
| ASUS KJ250AA-ABE a6336.es    | 1        | 5%      |
| ASUS F2A85-M                 | 1        | 5%      |
| ASUS Basic 3221BM            | 1        | 5%      |
| ASRock Z87 Killer            | 1        | 5%      |
| Alienware X51 R2             | 1        | 5%      |
| Acer Predator PO3-600        | 1        | 5%      |
| Acer Aspire TC-780           | 1        | 5%      |
| Unknown                      | 1        | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 2        | 10%     |
| Wistron FMVDD2A0H0 | 1        | 5%      |
| MSI MS-7529        | 1        | 5%      |
| HP Compaq          | 1        | 5%      |
| Gigabyte A320M-S2H | 1        | 5%      |
| Dell XPS           | 1        | 5%      |
| ASUS ROG           | 1        | 5%      |
| ASUS PRIME         | 1        | 5%      |
| ASUS P8H67-M       | 1        | 5%      |
| ASUS M5A99X        | 1        | 5%      |
| ASUS M5A78L-M      | 1        | 5%      |
| ASUS KJ250AA-ABE   | 1        | 5%      |
| ASUS F2A85-M       | 1        | 5%      |
| ASUS Basic         | 1        | 5%      |
| ASRock Z87         | 1        | 5%      |
| Alienware X51      | 1        | 5%      |
| Acer Predator      | 1        | 5%      |
| Acer Aspire        | 1        | 5%      |
| Unknown            | 1        | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 3        | 15%     |
| 2019 | 2        | 10%     |
| 2017 | 2        | 10%     |
| 2016 | 2        | 10%     |
| 2013 | 2        | 10%     |
| 2012 | 2        | 10%     |
| 2020 | 1        | 5%      |
| 2018 | 1        | 5%      |
| 2015 | 1        | 5%      |
| 2014 | 1        | 5%      |
| 2010 | 1        | 5%      |
| 2009 | 1        | 5%      |
| 2007 | 1        | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 20       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 20       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 5        | 25%     |
| 16.01-24.0 | 5        | 25%     |
| 8.01-16.0  | 4        | 20%     |
| 3.01-4.0   | 2        | 10%     |
| 1.01-2.0   | 2        | 10%     |
| 32.01-64.0 | 1        | 5%      |
| 24.01-32.0 | 1        | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 9        | 45%     |
| 4.01-8.0  | 4        | 20%     |
| 2.01-3.0  | 3        | 15%     |
| 0.51-1.0  | 2        | 10%     |
| 3.01-4.0  | 1        | 5%      |
| 8.01-16.0 | 1        | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 38.1%   |
| 3      | 6        | 28.57%  |
| 1      | 4        | 19.05%  |
| 4      | 2        | 9.52%   |
| 5      | 1        | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 70%     |
| Yes       | 6        | 30%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 71.43%  |
| No        | 6        | 28.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 60%     |
| Yes       | 8        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 8        | 40%     |
| Germany   | 2        | 10%     |
| Brazil    | 2        | 10%     |
| Vietnam   | 1        | 5%      |
| Ukraine   | 1        | 5%      |
| Spain     | 1        | 5%      |
| Russia    | 1        | 5%      |
| Poland    | 1        | 5%      |
| France    | 1        | 5%      |
| Czechia   | 1        | 5%      |
| Australia | 1        | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Eugene              | 2        | 9.52%   |
| Warsaw              | 1        | 4.76%   |
| Uherské Hradiště | 1        | 4.76%   |
| Sydney              | 1        | 4.76%   |
| Sao Paulo           | 1        | 4.76%   |
| Santa Maria         | 1        | 4.76%   |
| Saint Paul          | 1        | 4.76%   |
| Portsmouth          | 1        | 4.76%   |
| Orange Park         | 1        | 4.76%   |
| Nam Định         | 1        | 4.76%   |
| Melbourne           | 1        | 4.76%   |
| Lyon                | 1        | 4.76%   |
| Los Angeles         | 1        | 4.76%   |
| Lafayette           | 1        | 4.76%   |
| Kyiv                | 1        | 4.76%   |
| Khabarovsk          | 1        | 4.76%   |
| Hanau               | 1        | 4.76%   |
| Braunschweig        | 1        | 4.76%   |
| Berlin              | 1        | 4.76%   |
| Barcelona           | 1        | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 16     | 22.73%  |
| Samsung Electronics | 7        | 9      | 15.91%  |
| WDC                 | 5        | 5      | 11.36%  |
| Hitachi             | 3        | 4      | 6.82%   |
| Crucial             | 3        | 3      | 6.82%   |
| Unknown             | 2        | 2      | 4.55%   |
| Toshiba             | 2        | 2      | 4.55%   |
| SK hynix            | 2        | 2      | 4.55%   |
| SanDisk             | 2        | 2      | 4.55%   |
| SPCC                | 1        | 1      | 2.27%   |
| Phison              | 1        | 1      | 2.27%   |
| LITEONIT            | 1        | 1      | 2.27%   |
| Kingston            | 1        | 1      | 2.27%   |
| Intenso             | 1        | 1      | 2.27%   |
| HGST                | 1        | 1      | 2.27%   |
| FORESEE             | 1        | 1      | 2.27%   |
| China               | 1        | 2      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Unknown SD/MMC/MS PRO 128GB           | 2        | 3.92%   |
| Seagate Expansion 1TB                 | 2        | 3.92%   |
| WDC WDBNCE0010PNC 1TB SSD             | 1        | 1.96%   |
| WDC WD5000AACS-00ZUB0 500GB           | 1        | 1.96%   |
| WDC WD3200LPVX-60V0TT0 320GB          | 1        | 1.96%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1        | 1.96%   |
| WDC WD10EARS-00Y5B1 1TB               | 1        | 1.96%   |
| Toshiba MK2552GSX 250GB               | 1        | 1.96%   |
| Toshiba DT01ACA100 1TB                | 1        | 1.96%   |
| SPCC Solid State Disk 120GB           | 1        | 1.96%   |
| SK hynix PC601 NVMe 256GB             | 1        | 1.96%   |
| SK hynix NVMe SSD Drive 256GB         | 1        | 1.96%   |
| Seagate ST98823AS 80GB                | 1        | 1.96%   |
| Seagate ST9250410AS 250GB             | 1        | 1.96%   |
| Seagate ST500NM0011 500GB             | 1        | 1.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1        | 1.96%   |
| Seagate ST500LM000-SSHD-8GB           | 1        | 1.96%   |
| Seagate ST500DM002-1SB10A 500GB       | 1        | 1.96%   |
| Seagate ST4000DM004-2CV104 4TB        | 1        | 1.96%   |
| Seagate ST3500413AS 500GB             | 1        | 1.96%   |
| Seagate ST31000528AS 1TB              | 1        | 1.96%   |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1.96%   |
| Seagate ST2000LM003 HN-M201RAD 2TB    | 1        | 1.96%   |
| Seagate ST1000DM010-2EP102 1TB        | 1        | 1.96%   |
| SanDisk SSD PLUS 1000GB               | 1        | 1.96%   |
| SanDisk SD6SF1M128G1022I 128GB SSD    | 1        | 1.96%   |
| Samsung SSD SM841N 2.5 7mm 256GB      | 1        | 1.96%   |
| Samsung SSD 970 EVO 500GB             | 1        | 1.96%   |
| Samsung SSD 860 EVO 500GB             | 1        | 1.96%   |
| Samsung SSD 860 EVO 250GB             | 1        | 1.96%   |
| Samsung SSD 840 Series 250GB          | 1        | 1.96%   |
| Samsung NVMe SSD Drive 1TB            | 1        | 1.96%   |
| Samsung HD502HI 500GB                 | 1        | 1.96%   |
| Samsung HD253GJ 250GB                 | 1        | 1.96%   |
| Samsung HD161GJ 160GB                 | 1        | 1.96%   |
| Phison NVMe SSD Drive 1TB             | 1        | 1.96%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD | 1        | 1.96%   |
| Kingston SV300S37A 120G SSD           | 1        | 1.96%   |
| Intenso SSD SATAIII 480GB             | 1        | 1.96%   |
| Hitachi HUA722020ALA331 2TB           | 1        | 1.96%   |
| Hitachi HTS547564A9E384 640GB         | 1        | 1.96%   |
| Hitachi HTS545050B9A300 500GB         | 1        | 1.96%   |
| Hitachi HDT721010SLA360 1TB           | 1        | 1.96%   |
| HGST HTS541010A9E680 1TB              | 1        | 1.96%   |
| FORESEE 60GB SSD                      | 1        | 1.96%   |
| Crucial CT256MX100SSD1 256GB          | 1        | 1.96%   |
| Crucial CT240BX300SSD1 240GB          | 1        | 1.96%   |
| Crucial CT1000BX500SSD1 1TB           | 1        | 1.96%   |
| China SATA SSD 256GB                  | 1        | 1.96%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 10       | 16     | 41.67%  |
| WDC                 | 4        | 4      | 16.67%  |
| Hitachi             | 3        | 4      | 12.5%   |
| Unknown             | 2        | 2      | 8.33%   |
| Toshiba             | 2        | 2      | 8.33%   |
| Samsung Electronics | 2        | 3      | 8.33%   |
| HGST                | 1        | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 20%     |
| Crucial             | 3        | 3      | 20%     |
| SanDisk             | 2        | 2      | 13.33%  |
| WDC                 | 1        | 1      | 6.67%   |
| SPCC                | 1        | 1      | 6.67%   |
| LITEONIT            | 1        | 1      | 6.67%   |
| Kingston            | 1        | 1      | 6.67%   |
| Intenso             | 1        | 1      | 6.67%   |
| FORESEE             | 1        | 1      | 6.67%   |
| China               | 1        | 2      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 32     | 50%     |
| SSD  | 12       | 17     | 35.29%  |
| NVMe | 5        | 5      | 14.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 18       | 45     | 69.23%  |
| NVMe | 5        | 5      | 19.23%  |
| SAS  | 3        | 4      | 11.54%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 17       | 33     | 53.13%  |
| 0.51-1.0   | 12       | 13     | 37.5%   |
| 1.01-2.0   | 2        | 2      | 6.25%   |
| 3.01-4.0   | 1        | 1      | 3.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 6        | 27.27%  |
| 101-250    | 5        | 22.73%  |
| 1001-2000  | 4        | 18.18%  |
| 2001-3000  | 2        | 9.09%   |
| 501-1000   | 2        | 9.09%   |
| Unknown    | 2        | 9.09%   |
| 51-100     | 1        | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 101-250  | 7        | 31.82%  |
| 21-50    | 5        | 22.73%  |
| 51-100   | 3        | 13.64%  |
| 251-500  | 2        | 9.09%   |
| 1-20     | 2        | 9.09%   |
| Unknown  | 2        | 9.09%   |
| 501-1000 | 1        | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD10EZRX-00L4HB0 1TB           | 1        | 1      | 11.11%  |
| Seagate ST9250410AS 250GB          | 1        | 1      | 11.11%  |
| Seagate ST500NM0011 500GB          | 1        | 1      | 11.11%  |
| Seagate ST3500413AS 500GB          | 1        | 1      | 11.11%  |
| Seagate ST31000528AS 1TB           | 1        | 1      | 11.11%  |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 11.11%  |
| SanDisk SSD PLUS 1000GB            | 1        | 1      | 11.11%  |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1        | 1      | 11.11%  |
| Hitachi HUA722020ALA331 2TB        | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 50%     |
| SanDisk | 2        | 2      | 25%     |
| WDC     | 1        | 1      | 12.5%   |
| Hitachi | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 66.67%  |
| WDC     | 1        | 1      | 16.67%  |
| Hitachi | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 7      | 75%     |
| SSD  | 2        | 2      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Intenso SSD SATAIII 480GB | 1        | 1      | 100%    |

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
| Detected | 12       | 26     | 37.5%   |
| Works    | 11       | 18     | 34.38%  |
| Malfunc  | 8        | 9      | 25%     |
| Failed   | 1        | 1      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 13       | 48.15%  |
| AMD                 | 7        | 25.93%  |
| SK hynix            | 2        | 7.41%   |
| Samsung Electronics | 2        | 7.41%   |
| VIA Technologies    | 1        | 3.7%    |
| Phison Electronics  | 1        | 3.7%    |
| JMicron Technology  | 1        | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 12.12%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 6.06%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 6.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 6.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 6.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 6.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 2        | 6.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 6.06%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 3.03%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 3.03%   |
| SK hynix BC511                                                                          | 1        | 3.03%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 3.03%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 3.03%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 3.03%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 3.03%   |
| AMD FCH SATA Controller D                                                               | 1        | 3.03%   |
| AMD FCH RAID Controller                                                                 | 1        | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 15       | 57.69%  |
| NVMe | 5        | 19.23%  |
| IDE  | 4        | 15.38%  |
| RAID | 2        | 7.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 65%     |
| AMD    | 7        | 35%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz            | 1        | 5%      |
| Intel Pentium Dual CPU E2200 @ 2.20GHz         | 1        | 5%      |
| Intel Pentium CPU G3260 @ 3.30GHz              | 1        | 5%      |
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1        | 5%      |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 5%      |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 5%      |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 5%      |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1        | 5%      |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 5%      |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 5%      |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 5%      |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 5%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz           | 1        | 5%      |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 5%      |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 5%      |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 5%      |
| AMD FX-8320 Eight-Core Processor               | 1        | 5%      |
| AMD FX-6300 Six-Core Processor                 | 1        | 5%      |
| AMD A8-5600K APU with Radeon HD Graphics       | 1        | 5%      |
| AMD A4-5300B APU with Radeon HD Graphics       | 1        | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 4        | 20%     |
| Intel Core i7          | 3        | 15%     |
| AMD FX                 | 2        | 10%     |
| Intel Xeon             | 1        | 5%      |
| Intel Pentium Dual     | 1        | 5%      |
| Intel Pentium          | 1        | 5%      |
| Intel Core M           | 1        | 5%      |
| Intel Core 2 Quad      | 1        | 5%      |
| Intel Core 2 Duo       | 1        | 5%      |
| AMD Ryzen Threadripper | 1        | 5%      |
| AMD Ryzen 5            | 1        | 5%      |
| AMD Ryzen 3            | 1        | 5%      |
| AMD A8                 | 1        | 5%      |
| AMD A4                 | 1        | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 8        | 40%     |
| 2      | 5        | 25%     |
| 6      | 4        | 20%     |
| 12     | 1        | 5%      |
| 3      | 1        | 5%      |
| 1      | 1        | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 11       | 55%     |
| 1      | 9        | 45%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 20       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 47.62%  |
| 0x306c3    | 2        | 9.52%   |
| 0x06000852 | 2        | 9.52%   |
| 0x906ed    | 1        | 4.76%   |
| 0x906e9    | 1        | 4.76%   |
| 0x306a9    | 1        | 4.76%   |
| 0x206a7    | 1        | 4.76%   |
| 0x1067a    | 1        | 4.76%   |
| 0x0a201016 | 1        | 4.76%   |
| 0x0600111f | 1        | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Piledriver  | 4        | 20%     |
| KabyLake    | 4        | 20%     |
| Haswell     | 3        | 15%     |
| Zen         | 2        | 10%     |
| Core        | 2        | 10%     |
| Zen 3       | 1        | 5%      |
| SandyBridge | 1        | 5%      |
| Penryn      | 1        | 5%      |
| IvyBridge   | 1        | 5%      |
| Broadwell   | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 9        | 39.13%  |
| Intel  | 7        | 30.43%  |
| AMD    | 7        | 30.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 8.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 8.7%    |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 4.35%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 4.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 4.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 4.35%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 4.35%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 4.35%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 4.35%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 4.35%   |
| Nvidia G86 [GeForce 8300 GS]                                                | 1        | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 4.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 4.35%   |
| Intel HD Graphics 5300                                                      | 1        | 4.35%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 4.35%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 4.35%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 1        | 4.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 4.35%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 4.35%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 4.35%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 8        | 40%     |
| 1 x Intel    | 5        | 25%     |
| 1 x AMD      | 5        | 25%     |
| Intel + AMD  | 1        | 5%      |
| AMD + Nvidia | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 14       | 70%     |
| Proprietary | 6        | 30%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 47.62%  |
| 3.01-4.0   | 3        | 14.29%  |
| 1.01-2.0   | 3        | 14.29%  |
| 7.01-8.0   | 2        | 9.52%   |
| 0.51-1.0   | 2        | 9.52%   |
| 0.01-0.5   | 1        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 5        | 21.74%  |
| Goldstar            | 3        | 13.04%  |
| Hewlett-Packard     | 2        | 8.7%    |
| AOC                 | 2        | 8.7%    |
| Vizio               | 1        | 4.35%   |
| Toshiba             | 1        | 4.35%   |
| Sony                | 1        | 4.35%   |
| Sceptre             | 1        | 4.35%   |
| Samsung Electronics | 1        | 4.35%   |
| Philips             | 1        | 4.35%   |
| NEC Computers       | 1        | 4.35%   |
| Insignia            | 1        | 4.35%   |
| BenQ                | 1        | 4.35%   |
| AUS                 | 1        | 4.35%   |
| Acer                | 1        | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch          | 1        | 4.35%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch            | 1        | 4.35%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch         | 1        | 4.35%   |
| Sceptre LCD Monitor P30 2560x1080                           | 1        | 4.35%   |
| Samsung Electronics LCD Monitor SAM03FE 1280x720            | 1        | 4.35%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch     | 1        | 4.35%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch | 1        | 4.35%   |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch | 1        | 4.35%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch | 1        | 4.35%   |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch  | 1        | 4.35%   |
| Goldstar L1742 GSM449B 1280x1024 338x270mm 17.0-inch        | 1        | 4.35%   |
| Goldstar HDR WFHD GSM7749 2560x1080 798x334mm 34.1-inch     | 1        | 4.35%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch      | 1        | 4.35%   |
| Dell SE2417HGX DELD0F7 1920x1080 521x293mm 23.5-inch        | 1        | 4.35%   |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch           | 1        | 4.35%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch           | 1        | 4.35%   |
| Dell E2318H DELF092 1920x1080 509x286mm 23.0-inch           | 1        | 4.35%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch           | 1        | 4.35%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch           | 1        | 4.35%   |
| AUS LCD Monitor VG259 1920x1080                             | 1        | 4.35%   |
| AOC LCD Monitor 2217 1680x1050                              | 1        | 4.35%   |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch               | 1        | 4.35%   |
| Acer VG240Y S ACR0750 1920x1080 527x296mm 23.8-inch         | 1        | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 50%     |
| 1280x1024 (SXGA)   | 3        | 13.64%  |
| 2560x1080          | 2        | 9.09%   |
| 1680x1050 (WSXGA+) | 2        | 9.09%   |
| 1920x1200 (WUXGA)  | 1        | 4.55%   |
| 1440x900 (WXGA+)   | 1        | 4.55%   |
| 1360x768           | 1        | 4.55%   |
| 1280x720 (HD)      | 1        | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 21.74%  |
| Unknown | 4        | 17.39%  |
| 23      | 3        | 13.04%  |
| 27      | 2        | 8.7%    |
| 19      | 2        | 8.7%    |
| 17      | 2        | 8.7%    |
| 42      | 1        | 4.35%   |
| 34      | 1        | 4.35%   |
| 32      | 1        | 4.35%   |
| 31      | 1        | 4.35%   |
| 22      | 1        | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 40.91%  |
| Unknown     | 4        | 18.18%  |
| 701-800     | 2        | 9.09%   |
| 401-500     | 2        | 9.09%   |
| 301-350     | 2        | 9.09%   |
| 601-700     | 1        | 4.55%   |
| 351-400     | 1        | 4.55%   |
| 901-1000    | 1        | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 11       | 52.38%  |
| 5/4     | 3        | 14.29%  |
| 16/10   | 3        | 14.29%  |
| Unknown | 3        | 14.29%  |
| 21/9    | 1        | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 31.82%  |
| Unknown        | 4        | 18.18%  |
| 351-500        | 3        | 13.64%  |
| 301-350        | 2        | 9.09%   |
| 151-200        | 2        | 9.09%   |
| 141-150        | 2        | 9.09%   |
| 251-300        | 1        | 4.55%   |
| 501-1000       | 1        | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 73.68%  |
| Unknown | 4        | 21.05%  |
| 1-50    | 1        | 5.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 65%     |
| 2     | 6        | 30%     |
| 0     | 1        | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 15       | 42.86%  |
| Intel                           | 5        | 14.29%  |
| Ralink                          | 2        | 5.71%   |
| Qualcomm Atheros Communications | 2        | 5.71%   |
| Qualcomm Atheros                | 2        | 5.71%   |
| Broadcom Limited                | 2        | 5.71%   |
| Broadcom                        | 2        | 5.71%   |
| Ralink Technology               | 1        | 2.86%   |
| OnePlus Technology (Shenzhen)   | 1        | 2.86%   |
| Microsoft                       | 1        | 2.86%   |
| D-Link System                   | 1        | 2.86%   |
| D-Link                          | 1        | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 12       | 32.43%  |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 5.41%   |
| Intel I211 Gigabit Network Connection                                | 2        | 5.41%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 1        | 2.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1        | 2.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 2.7%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1        | 2.7%    |
| Ralink RT2500 Wireless 802.11bg                                      | 1        | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 2.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 2.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1        | 2.7%    |
| OnePlus (Shenzhen) EB2103                                            | 1        | 2.7%    |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 2.7%    |
| Intel Wireless 7265                                                  | 1        | 2.7%    |
| Intel Wireless 3160                                                  | 1        | 2.7%    |
| Intel Ethernet Connection (7) I219-LM                                | 1        | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 2.7%    |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 2.7%    |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                       | 1        | 2.7%    |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                | 1        | 2.7%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe             | 1        | 2.7%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1        | 2.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 2.7%    |

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
| Realtek Semiconductor | 14       | 66.67%  |
| Intel                 | 3        | 14.29%  |
| Qualcomm Atheros      | 2        | 9.52%   |
| Broadcom Limited      | 1        | 4.76%   |
| Broadcom              | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 57.14%  |
| Intel I211 Gigabit Network Connection                             | 2        | 9.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 4.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 4.76%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 4.76%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1        | 4.76%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 55.56%  |
| WiFi     | 15       | 41.67%  |
| Unknown  | 1        | 2.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 62.5%   |
| WiFi     | 9        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 55%     |
| 2     | 8        | 40%     |
| 3     | 1        | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 75%     |
| Yes  | 5        | 25%     |

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
| Intel               | 13       | 39.39%  |
| AMD                 | 11       | 33.33%  |
| Nvidia              | 7        | 21.21%  |
| GYROCOM C&C         | 1        | 3.03%   |
| C-Media Electronics | 1        | 3.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 7.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3        | 7.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 5.26%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 5.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 5.26%   |
| AMD FCH Azalia Controller                                                         | 2        | 5.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 2.63%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 2.63%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 2.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 2.63%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 2.63%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1        | 2.63%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 2.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 2.63%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 2.63%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 2.63%   |
| GYROCOM C&C NuForce ÂµDAC 2 HP                                                  | 1        | 2.63%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1        | 2.63%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 2.63%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1        | 2.63%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 2.63%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 2.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 2.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 2.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 2.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 2        | 18.18%  |
| Kingston         | 2        | 18.18%  |
| Crucial          | 2        | 18.18%  |
| Corsair          | 2        | 18.18%  |
| SK hynix         | 1        | 9.09%   |
| S                | 1        | 9.09%   |
| Nanya Technology | 1        | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 8.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 8.33%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 8.33%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s      | 1        | 8.33%   |
| S RAM Module 2GB DIMM DDR3 1600MT/s                      | 1        | 8.33%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s       | 1        | 8.33%   |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s      | 1        | 8.33%   |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s | 1        | 8.33%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s    | 1        | 8.33%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1        | 8.33%   |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s      | 1        | 8.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 1        | 8.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 54.55%  |
| DDR4    | 3        | 27.27%  |
| DDR2    | 1        | 9.09%   |
| Unknown | 1        | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 11       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 6        | 50%     |
| 4096 | 4        | 33.33%  |
| 2048 | 1        | 8.33%   |
| 1024 | 1        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 6        | 54.55%  |
| 3600  | 1        | 9.09%   |
| 2666  | 1        | 9.09%   |
| 2400  | 1        | 9.09%   |
| 1333  | 1        | 9.09%   |
| 800   | 1        | 9.09%   |

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
| 0     | 16       | 80%     |
| 1     | 4        | 20%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 2        | 50%     |
| Storage/raid | 1        | 25%     |
| Net/ethernet | 1        | 25%     |

