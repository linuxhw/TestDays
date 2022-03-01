Parrot 4.11 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor    | Model                   | Probe                                                      | Date         |
|-----------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | Benicia                 | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek   | ROG STRIX B450-F GAMING | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| ASUSTek   | M5A99X EVO              | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Alienware | 0PGRP5 A02              | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock    | Z87 Killer              | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Acer      | Aspire TC-780           | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Dell      | 0T2HR0 A00              | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek   | P8H67-M PRO             | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte  | A320M-S2H-CF            | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Gigabyte  | A320M-S2H-CF            | [6647d75cdb](https://linux-hardware.org/?probe=6647d75cdb) | Aug 20, 2021 |
| Gigabyte  | A320M-S2H-CF            | [5363cc3efd](https://linux-hardware.org/?probe=5363cc3efd) | Aug 12, 2021 |
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


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.14.0-9parrot1-amd64 | 4        | 25%     |
| 5.10.0-6parrot1-amd64 | 4        | 25%     |
| 5.10.0-8parrot1-amd64 | 3        | 18.75%  |
| 5.10.0-3parrot1-amd64 | 2        | 12.5%   |
| 5.7.0-2parrot2-amd64  | 1        | 6.25%   |
| 5.14.0-2parrot1-amd64 | 1        | 6.25%   |
| 5.10.0-5parrot1-amd64 | 1        | 6.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 10       | 62.5%   |
| 5.14.0  | 5        | 31.25%  |
| 5.7.0   | 1        | 6.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 62.5%   |
| 5.14    | 5        | 31.25%  |
| 5.7     | 1        | 6.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 16       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 7        | 41.18%  |
| KDE5    | 6        | 35.29%  |
| XFCE    | 2        | 11.76%  |
| KDE     | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 16       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 7        | 41.18%  |
| Unknown | 7        | 41.18%  |
| TDM     | 3        | 17.65%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 9        | 56.25%  |
| ru_UA | 1        | 6.25%   |
| ru_RU | 1        | 6.25%   |
| pt_BR | 1        | 6.25%   |
| pl_PL | 1        | 6.25%   |
| fr_FR | 1        | 6.25%   |
| en_AU | 1        | 6.25%   |
| an_ES | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11       | 64.71%  |
| EFI  | 6        | 35.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 13       | 81.25%  |
| Ext4  | 3        | 18.75%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 8        | 47.06%  |
| Unknown | 8        | 47.06%  |
| MBR     | 1        | 5.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 82.35%  |
| Yes       | 3        | 17.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 56.25%  |
| Yes       | 7        | 43.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 6        | 37.5%   |
| Dell                | 3        | 18.75%  |
| Acer                | 2        | 12.5%   |
| ZOTAC               | 1        | 6.25%   |
| Hewlett-Packard     | 1        | 6.25%   |
| Gigabyte Technology | 1        | 6.25%   |
| ASRock              | 1        | 6.25%   |
| Alienware           | 1        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| HP Compaq Pro 6305 MT        | 1        | 6.25%   |
| Gigabyte A320M-S2H           | 1        | 6.25%   |
| Dell XPS 8930                | 1        | 6.25%   |
| Dell OptiPlex 7070           | 1        | 6.25%   |
| Dell OptiPlex 3010           | 1        | 6.25%   |
| ASUS ROG STRIX B450-F GAMING | 1        | 6.25%   |
| ASUS PRIME X399-A            | 1        | 6.25%   |
| ASUS P8H67-M PRO             | 1        | 6.25%   |
| ASUS M5A99X EVO              | 1        | 6.25%   |
| ASUS M5A78L-M/USB3           | 1        | 6.25%   |
| ASUS KJ250AA-ABE a6336.es    | 1        | 6.25%   |
| ASRock Z87 Killer            | 1        | 6.25%   |
| Alienware X51 R2             | 1        | 6.25%   |
| Acer Predator PO3-600        | 1        | 6.25%   |
| Acer Aspire TC-780           | 1        | 6.25%   |
| Unknown                      | 1        | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 2        | 12.5%   |
| HP Compaq          | 1        | 6.25%   |
| Gigabyte A320M-S2H | 1        | 6.25%   |
| Dell XPS           | 1        | 6.25%   |
| ASUS ROG           | 1        | 6.25%   |
| ASUS PRIME         | 1        | 6.25%   |
| ASUS P8H67-M       | 1        | 6.25%   |
| ASUS M5A99X        | 1        | 6.25%   |
| ASUS M5A78L-M      | 1        | 6.25%   |
| ASUS KJ250AA-ABE   | 1        | 6.25%   |
| ASRock Z87         | 1        | 6.25%   |
| Alienware X51      | 1        | 6.25%   |
| Acer Predator      | 1        | 6.25%   |
| Acer Aspire        | 1        | 6.25%   |
| Unknown            | 1        | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 3        | 18.75%  |
| 2019 | 2        | 12.5%   |
| 2017 | 2        | 12.5%   |
| 2016 | 2        | 12.5%   |
| 2013 | 2        | 12.5%   |
| 2020 | 1        | 6.25%   |
| 2018 | 1        | 6.25%   |
| 2014 | 1        | 6.25%   |
| 2012 | 1        | 6.25%   |
| 2007 | 1        | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 16       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 16       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 5        | 31.25%  |
| 4.01-8.0   | 4        | 25%     |
| 8.01-16.0  | 3        | 18.75%  |
| 3.01-4.0   | 2        | 12.5%   |
| 32.01-64.0 | 1        | 6.25%   |
| 24.01-32.0 | 1        | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 7        | 43.75%  |
| 4.01-8.0  | 3        | 18.75%  |
| 2.01-3.0  | 3        | 18.75%  |
| 3.01-4.0  | 1        | 6.25%   |
| 8.01-16.0 | 1        | 6.25%   |
| 0.51-1.0  | 1        | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 6        | 37.5%   |
| 3      | 5        | 31.25%  |
| 4      | 2        | 12.5%   |
| 1      | 2        | 12.5%   |
| 5      | 1        | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 70.59%  |
| Yes       | 5        | 29.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 76.47%  |
| No        | 4        | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 56.25%  |
| Yes       | 7        | 43.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 8        | 50%     |
| Ukraine   | 1        | 6.25%   |
| Spain     | 1        | 6.25%   |
| Russia    | 1        | 6.25%   |
| Poland    | 1        | 6.25%   |
| Germany   | 1        | 6.25%   |
| France    | 1        | 6.25%   |
| Brazil    | 1        | 6.25%   |
| Australia | 1        | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Eugene       | 2        | 11.76%  |
| Warsaw       | 1        | 5.88%   |
| Ternopil     | 1        | 5.88%   |
| SÃ£o Paulo | 1        | 5.88%   |
| Saint Paul   | 1        | 5.88%   |
| Portsmouth   | 1        | 5.88%   |
| Orange Park  | 1        | 5.88%   |
| Offenbach    | 1        | 5.88%   |
| Melbourne    | 1        | 5.88%   |
| Lyon         | 1        | 5.88%   |
| Los Angeles  | 1        | 5.88%   |
| Lafayette    | 1        | 5.88%   |
| Khabarovsk   | 1        | 5.88%   |
| Dudenhofen   | 1        | 5.88%   |
| Brunswick    | 1        | 5.88%   |
| Barcelona    | 1        | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 15     | 24.32%  |
| WDC                 | 4        | 5      | 10.81%  |
| Samsung Electronics | 4        | 5      | 10.81%  |
| Crucial             | 3        | 3      | 8.11%   |
| Unknown             | 2        | 2      | 5.41%   |
| Toshiba             | 2        | 2      | 5.41%   |
| SK Hynix            | 2        | 2      | 5.41%   |
| SanDisk             | 2        | 2      | 5.41%   |
| Hitachi             | 2        | 3      | 5.41%   |
| SPCC                | 1        | 1      | 2.7%    |
| Phison              | 1        | 1      | 2.7%    |
| LITEONIT            | 1        | 1      | 2.7%    |
| Intenso             | 1        | 1      | 2.7%    |
| HGST                | 1        | 1      | 2.7%    |
| FORESEE             | 1        | 1      | 2.7%    |
| China               | 1        | 2      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown SD/MMC/MS PRO 64GB          | 2        | 4.65%   |
| Seagate Expansion+ 2TB              | 2        | 4.65%   |
| WDC WDBNCE0010PNC 1TB SSD           | 1        | 2.33%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1        | 2.33%   |
| WDC WD3200LPVX-60V0TT0 320GB        | 1        | 2.33%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 2.33%   |
| Toshiba MK2552GSX 250GB             | 1        | 2.33%   |
| Toshiba DT01ACA100 1TB              | 1        | 2.33%   |
| SPCC Solid State Disk 120GB         | 1        | 2.33%   |
| SK Hynix PC601 NVMe 256GB           | 1        | 2.33%   |
| SK Hynix NVMe SSD Drive 256GB       | 1        | 2.33%   |
| Seagate ST98823AS 80GB              | 1        | 2.33%   |
| Seagate ST9250410AS 250GB           | 1        | 2.33%   |
| Seagate ST500NM0011 500GB           | 1        | 2.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 2.33%   |
| Seagate ST500DM002-1SB10A 500GB     | 1        | 2.33%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 2.33%   |
| Seagate ST3500413AS 500GB           | 1        | 2.33%   |
| Seagate ST31000528AS 1TB            | 1        | 2.33%   |
| Seagate ST250DM000-1BD141 250GB     | 1        | 2.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1        | 2.33%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 2.33%   |
| SanDisk SSD PLUS 1000GB             | 1        | 2.33%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 1        | 2.33%   |
| Samsung SSD SM841N 2.5 7mm 256GB    | 1        | 2.33%   |
| Samsung SSD 970 EVO 500GB           | 1        | 2.33%   |
| Samsung SSD 860 EVO 250GB           | 1        | 2.33%   |
| Samsung SSD 840 Series 250GB        | 1        | 2.33%   |
| Samsung NVMe SSD Drive 1TB          | 1        | 2.33%   |
| Phison NVMe SSD Drive 1TB           | 1        | 2.33%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB   | 1        | 2.33%   |
| Intenso SSD SATAIII 480GB           | 1        | 2.33%   |
| Hitachi HTS547564A9E384 640GB       | 1        | 2.33%   |
| Hitachi HTS545050B9A300 500GB       | 1        | 2.33%   |
| Hitachi HDT721010SLA360 1TB         | 1        | 2.33%   |
| HGST HTS541010A9E680 1TB            | 1        | 2.33%   |
| FORESEE 60GB SSD                    | 1        | 2.33%   |
| Crucial CT256MX100SSD1 256GB        | 1        | 2.33%   |
| Crucial CT240BX300SSD1 240GB        | 1        | 2.33%   |
| Crucial CT1000BX500SSD1 1TB         | 1        | 2.33%   |
| China SATA SSD 256GB                | 1        | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 15     | 47.37%  |
| WDC     | 3        | 4      | 15.79%  |
| Unknown | 2        | 2      | 10.53%  |
| Toshiba | 2        | 2      | 10.53%  |
| Hitachi | 2        | 3      | 10.53%  |
| HGST    | 1        | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 3        | 3      | 23.08%  |
| SanDisk             | 2        | 2      | 15.38%  |
| Samsung Electronics | 2        | 3      | 15.38%  |
| WDC                 | 1        | 1      | 7.69%   |
| SPCC                | 1        | 1      | 7.69%   |
| LITEONIT            | 1        | 1      | 7.69%   |
| Intenso             | 1        | 1      | 7.69%   |
| FORESEE             | 1        | 1      | 7.69%   |
| China               | 1        | 2      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 27     | 46.43%  |
| SSD  | 10       | 15     | 35.71%  |
| NVMe | 5        | 5      | 17.86%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 38     | 63.64%  |
| NVMe | 5        | 5      | 22.73%  |
| SAS  | 3        | 4      | 13.64%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 13       | 27     | 50%     |
| 0.51-1.0   | 10       | 11     | 38.46%  |
| 1.01-2.0   | 2        | 3      | 7.69%   |
| 3.01-4.0   | 1        | 1      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 4        | 22.22%  |
| 1001-2000  | 4        | 22.22%  |
| 101-250    | 3        | 16.67%  |
| 2001-3000  | 2        | 11.11%  |
| 501-1000   | 2        | 11.11%  |
| Unknown    | 2        | 11.11%  |
| 51-100     | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 101-250  | 5        | 27.78%  |
| 21-50    | 4        | 22.22%  |
| 51-100   | 3        | 16.67%  |
| 251-500  | 2        | 11.11%  |
| Unknown  | 2        | 11.11%  |
| 1-20     | 1        | 5.56%   |
| 501-1000 | 1        | 5.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST9250410AS 250GB          | 1        | 1      | 14.29%  |
| Seagate ST500NM0011 500GB          | 1        | 1      | 14.29%  |
| Seagate ST3500413AS 500GB          | 1        | 1      | 14.29%  |
| Seagate ST31000528AS 1TB           | 1        | 1      | 14.29%  |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 14.29%  |
| SanDisk SSD PLUS 1000GB            | 1        | 1      | 14.29%  |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 66.67%  |
| SanDisk | 2        | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 5      | 66.67%  |
| SSD  | 2        | 2      | 33.33%  |

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
| Detected | 10       | 24     | 38.46%  |
| Works    | 9        | 15     | 34.62%  |
| Malfunc  | 6        | 7      | 23.08%  |
| Failed   | 1        | 1      | 3.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 10       | 43.48%  |
| AMD                 | 6        | 26.09%  |
| SK Hynix            | 2        | 8.7%    |
| Samsung Electronics | 2        | 8.7%    |
| VIA Technologies    | 1        | 4.35%   |
| Phison Electronics  | 1        | 4.35%   |
| JMicron Technology  | 1        | 4.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 11.11%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 7.41%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 7.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 7.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 7.41%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 3.7%    |
| SK Hynix Non-Volatile memory controller                                                 | 1        | 3.7%    |
| SK Hynix BC511                                                                          | 1        | 3.7%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 3.7%    |
| JMicron JMB362 SATA Controller                                                          | 1        | 3.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 3.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 3.7%    |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 3.7%    |
| AMD FCH SATA Controller D                                                               | 1        | 3.7%    |
| AMD FCH RAID Controller                                                                 | 1        | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 12       | 54.55%  |
| NVMe | 5        | 22.73%  |
| RAID | 3        | 13.64%  |
| IDE  | 2        | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 10       | 62.5%   |
| AMD    | 6        | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz            | 1        | 6.25%   |
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1        | 6.25%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 6.25%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 6.25%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 6.25%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1        | 6.25%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 6.25%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 6.25%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 6.25%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 1        | 6.25%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 6.25%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 6.25%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 6.25%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 6.25%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 6.25%   |
| AMD A4-5300B APU with Radeon HD Graphics       | 1        | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 4        | 25%     |
| Intel Core i7          | 3        | 18.75%  |
| AMD FX                 | 2        | 12.5%   |
| Intel Xeon             | 1        | 6.25%   |
| Intel Core M           | 1        | 6.25%   |
| Intel Core 2 Quad      | 1        | 6.25%   |
| AMD Ryzen Threadripper | 1        | 6.25%   |
| AMD Ryzen 5            | 1        | 6.25%   |
| AMD Ryzen 3            | 1        | 6.25%   |
| AMD A4                 | 1        | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 8        | 50%     |
| 6      | 4        | 25%     |
| 12     | 1        | 6.25%   |
| 3      | 1        | 6.25%   |
| 2      | 1        | 6.25%   |
| 1      | 1        | 6.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 62.5%   |
| 1      | 6        | 37.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 16       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 47.06%  |
| 0x06000852 | 2        | 11.76%  |
| 0x906ed    | 1        | 5.88%   |
| 0x906e9    | 1        | 5.88%   |
| 0x306c3    | 1        | 5.88%   |
| 0x306a9    | 1        | 5.88%   |
| 0x206a7    | 1        | 5.88%   |
| 0x0a201016 | 1        | 5.88%   |
| 0x0600111f | 1        | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 4        | 25%     |
| Piledriver  | 3        | 18.75%  |
| Zen         | 2        | 12.5%   |
| Haswell     | 2        | 12.5%   |
| Zen 3       | 1        | 6.25%   |
| SandyBridge | 1        | 6.25%   |
| IvyBridge   | 1        | 6.25%   |
| Core        | 1        | 6.25%   |
| Broadwell   | 1        | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 8        | 42.11%  |
| AMD    | 6        | 31.58%  |
| Intel  | 5        | 26.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 10.53%  |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 5.26%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 5.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 5.26%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 5.26%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 5.26%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 5.26%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 5.26%   |
| Nvidia G86 [GeForce 8300 GS]                                                | 1        | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 5.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 5.26%   |
| Intel HD Graphics 5300                                                      | 1        | 5.26%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 5.26%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 5.26%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 5.26%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 5.26%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 5.26%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 5.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 7        | 43.75%  |
| 1 x AMD      | 4        | 25%     |
| 1 x Intel    | 3        | 18.75%  |
| Intel + AMD  | 1        | 6.25%   |
| AMD + Nvidia | 1        | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 10       | 62.5%   |
| Proprietary | 6        | 37.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 41.18%  |
| 3.01-4.0   | 3        | 17.65%  |
| 1.01-2.0   | 3        | 17.65%  |
| 7.01-8.0   | 2        | 11.76%  |
| 0.51-1.0   | 1        | 5.88%   |
| 0.01-0.5   | 1        | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Dell            | 3        | 16.67%  |
| Hewlett-Packard | 2        | 11.11%  |
| Goldstar        | 2        | 11.11%  |
| AOC             | 2        | 11.11%  |
| Vizio           | 1        | 5.56%   |
| Toshiba         | 1        | 5.56%   |
| Sony            | 1        | 5.56%   |
| Sceptre         | 1        | 5.56%   |
| Philips         | 1        | 5.56%   |
| NEC Computers   | 1        | 5.56%   |
| Insignia        | 1        | 5.56%   |
| AUS             | 1        | 5.56%   |
| Acer            | 1        | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch          | 1        | 5.56%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch            | 1        | 5.56%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch         | 1        | 5.56%   |
| Sceptre LCD Monitor P30 2560x1080                           | 1        | 5.56%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch     | 1        | 5.56%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch | 1        | 5.56%   |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch | 1        | 5.56%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch | 1        | 5.56%   |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch  | 1        | 5.56%   |
| Goldstar HDR WFHD GSM7749 2560x1080 798x334mm 34.1-inch     | 1        | 5.56%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch      | 1        | 5.56%   |
| Dell SE2417HGX DELD0F7 1920x1080 521x293mm 23.5-inch        | 1        | 5.56%   |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch           | 1        | 5.56%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch           | 1        | 5.56%   |
| AUS LCD Monitor VG259 1920x1080                             | 1        | 5.56%   |
| AOC LCD Monitor 2217 1680x1050                              | 1        | 5.56%   |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch               | 1        | 5.56%   |
| Acer VG240Y S ACR0750 1920x1080 530x300mm 24.0-inch         | 1        | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 9        | 52.94%  |
| 2560x1080          | 2        | 11.76%  |
| 1680x1050 (WSXGA+) | 2        | 11.76%  |
| 1920x1200 (WUXGA)  | 1        | 5.88%   |
| 1440x900 (WXGA+)   | 1        | 5.88%   |
| 1360x768           | 1        | 5.88%   |
| 1280x1024 (SXGA)   | 1        | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 27.78%  |
| Unknown | 3        | 16.67%  |
| 23      | 2        | 11.11%  |
| 42      | 1        | 5.56%   |
| 34      | 1        | 5.56%   |
| 32      | 1        | 5.56%   |
| 31      | 1        | 5.56%   |
| 27      | 1        | 5.56%   |
| 22      | 1        | 5.56%   |
| 19      | 1        | 5.56%   |
| 17      | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 41.18%  |
| Unknown     | 3        | 17.65%  |
| 701-800     | 2        | 11.76%  |
| 401-500     | 2        | 11.76%  |
| 601-700     | 1        | 5.88%   |
| 301-350     | 1        | 5.88%   |
| 901-1000    | 1        | 5.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 8        | 50%     |
| 16/10   | 3        | 18.75%  |
| Unknown | 3        | 18.75%  |
| 5/4     | 1        | 6.25%   |
| 21/9    | 1        | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 35.29%  |
| 351-500        | 3        | 17.65%  |
| Unknown        | 3        | 17.65%  |
| 301-350        | 1        | 5.88%   |
| 251-300        | 1        | 5.88%   |
| 151-200        | 1        | 5.88%   |
| 141-150        | 1        | 5.88%   |
| 501-1000       | 1        | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 71.43%  |
| Unknown | 3        | 21.43%  |
| 1-50    | 1        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 62.5%   |
| 2     | 5        | 31.25%  |
| 0     | 1        | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 12       | 42.86%  |
| Intel                           | 5        | 17.86%  |
| Qualcomm Atheros Communications | 2        | 7.14%   |
| Qualcomm Atheros                | 2        | 7.14%   |
| Broadcom Limited                | 2        | 7.14%   |
| Ralink Technology               | 1        | 3.57%   |
| Ralink                          | 1        | 3.57%   |
| Microsoft                       | 1        | 3.57%   |
| D-Link System                   | 1        | 3.57%   |
| Broadcom                        | 1        | 3.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 10       | 33.33%  |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 6.67%   |
| Intel I211 Gigabit Network Connection                                | 2        | 6.67%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 3.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1        | 3.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 3.33%   |
| Ralink RT2500 Wireless 802.11bg                                      | 1        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 3.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 3.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1        | 3.33%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 3.33%   |
| Intel Wireless 7265                                                  | 1        | 3.33%   |
| Intel Wireless 3160                                                  | 1        | 3.33%   |
| Intel Ethernet Connection (7) I219-LM                                | 1        | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 3.33%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 3.33%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe             | 1        | 3.33%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1        | 3.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 3.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 23.08%  |
| Qualcomm Atheros Communications | 2        | 15.38%  |
| Realtek Semiconductor           | 1        | 7.69%   |
| Ralink Technology               | 1        | 7.69%   |
| Ralink                          | 1        | 7.69%   |
| Qualcomm Atheros                | 1        | 7.69%   |
| Microsoft                       | 1        | 7.69%   |
| D-Link System                   | 1        | 7.69%   |
| Broadcom Limited                | 1        | 7.69%   |
| Broadcom                        | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 15.38%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 7.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 7.69%   |
| Ralink RT2500 Wireless 802.11bg                                      | 1        | 7.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 7.69%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 7.69%   |
| Intel Wireless 7265                                                  | 1        | 7.69%   |
| Intel Wireless 3160                                                  | 1        | 7.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 7.69%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 7.69%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1        | 7.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 64.71%  |
| Intel                 | 3        | 17.65%  |
| Qualcomm Atheros      | 2        | 11.76%  |
| Broadcom Limited      | 1        | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 58.82%  |
| Intel I211 Gigabit Network Connection                             | 2        | 11.76%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 5.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 5.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 5.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 5.88%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 55.17%  |
| WiFi     | 13       | 44.83%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 61.9%   |
| WiFi     | 8        | 38.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 50%     |
| 2     | 7        | 43.75%  |
| 3     | 1        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12       | 75%     |
| Yes  | 4        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 42.86%  |
| Realtek Semiconductor           | 1        | 14.29%  |
| Qualcomm Atheros Communications | 1        | 14.29%  |
| Dell                            | 1        | 14.29%  |
| Cambridge Silicon Radio         | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 2        | 28.57%  |
| Realtek Bluetooth Radio                             | 1        | 14.29%  |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 14.29%  |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 10       | 37.04%  |
| AMD                 | 10       | 37.04%  |
| Nvidia              | 6        | 22.22%  |
| C-Media Electronics | 1        | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH cAVS                                                        | 2        | 6.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 6.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 6.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 6.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 3.23%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 3.23%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 3.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 3.23%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 3.23%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 3.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 3.23%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 3.23%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 3.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 3.23%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1        | 3.23%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 3.23%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1        | 3.23%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 3.23%   |
| AMD FCH Azalia Controller                                                         | 1        | 3.23%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 3.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 3.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 3.23%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 3.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 2        | 22.22%  |
| Crucial          | 2        | 22.22%  |
| Corsair          | 2        | 22.22%  |
| S                | 1        | 11.11%  |
| Nanya Technology | 1        | 11.11%  |
| Kingston         | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 10%     |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 10%     |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 10%     |
| S RAM Module 2GB DIMM DDR3 1600MT/s                      | 1        | 10%     |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s       | 1        | 10%     |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s      | 1        | 10%     |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s    | 1        | 10%     |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1        | 10%     |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s      | 1        | 10%     |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 5        | 55.56%  |
| DDR4    | 3        | 33.33%  |
| Unknown | 1        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 9        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 6        | 60%     |
| 4096 | 3        | 30%     |
| 2048 | 1        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 55.56%  |
| 3600  | 1        | 11.11%  |
| 2666  | 1        | 11.11%  |
| 2400  | 1        | 11.11%  |
| 1333  | 1        | 11.11%  |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Microdia | 1        | 50%     |
| Logitech | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia PC Microscope camera | 1        | 50%     |
| Logitech HD Webcam C615       | 1        | 50%     |

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
| 0     | 14       | 87.5%   |
| 1     | 2        | 12.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Storage/raid | 1        | 50%     |
| Net/wireless | 1        | 50%     |

