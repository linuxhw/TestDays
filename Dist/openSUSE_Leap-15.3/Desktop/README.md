openSUSE Leap-15.3 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=opensuse-leap-15.3

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

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | M4A78T-E                    | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | [58f9ca6247](https://linux-hardware.org/?probe=58f9ca6247) | Sep 22, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | [db9ccd461b](https://linux-hardware.org/?probe=db9ccd461b) | Sep 22, 2021 |
| VS Company | G31T-M                      | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| ASUSTek    | AM1M-A/BR                   | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| Alienware  | 0PGRP5 A02                  | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Alienware  | 0PGRP5 A02                  | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| MSI        | X370 GAMING PRO             | [629a45e23d](https://linux-hardware.org/?probe=629a45e23d) | Sep 12, 2021 |
| HP         | 8056                        | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| Intel      | DG41WV AAE90316-104         | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| Gigabyte   | B550 AORUS PRO AC           | [be3b65a81d](https://linux-hardware.org/?probe=be3b65a81d) | Aug 29, 2021 |
| ASRock     | B450M Pro4                  | [a13b05f65f](https://linux-hardware.org/?probe=a13b05f65f) | Aug 27, 2021 |
| ASUSTek    | PRIME H310M-A               | [a22aa3c48c](https://linux-hardware.org/?probe=a22aa3c48c) | Aug 01, 2021 |
| MSI        | B85M-E45                    | [0e20d4cea9](https://linux-hardware.org/?probe=0e20d4cea9) | Jul 30, 2021 |
| Gigabyte   | B250M-DS3H-CF               | [acbcbe74d7](https://linux-hardware.org/?probe=acbcbe74d7) | Jul 22, 2021 |
| HP         | 8433 11                     | [b079ccb608](https://linux-hardware.org/?probe=b079ccb608) | Jul 15, 2021 |
| MSI        | D2415 S26361-D2415-A21      | [b49400f636](https://linux-hardware.org/?probe=b49400f636) | Jul 11, 2021 |
| MSI        | B350 TOMAHAWK               | [27a6ac997b](https://linux-hardware.org/?probe=27a6ac997b) | Jul 03, 2021 |
| ASRock     | X570M Pro4                  | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| HP         | 0A68h                       | [36cfa6a366](https://linux-hardware.org/?probe=36cfa6a366) | Jun 27, 2021 |
| ASUSTek    | TUF B450-PRO GAMING         | [dfc2f82575](https://linux-hardware.org/?probe=dfc2f82575) | Jun 26, 2021 |
| ASRock     | X570 Steel Legend           | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI        | MEG X570 GODLIKE            | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| HP         | 2AA2                        | [65e7cd2d3e](https://linux-hardware.org/?probe=65e7cd2d3e) | Jun 02, 2021 |
| ASUSTek    | P8H61-M LE/USB3             | [fca0fd3336](https://linux-hardware.org/?probe=fca0fd3336) | Jan 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.3.18-59.19-default    | 8        | 34.78%  |
| 5.3.18-59.5-default     | 4        | 17.39%  |
| 5.3.18-59.10-default    | 3        | 13.04%  |
| 5.3.18-57-default       | 3        | 13.04%  |
| 5.3.18-lp152.57-default | 1        | 4.35%   |
| 5.3.18-59.24-preempt    | 1        | 4.35%   |
| 5.3.18-59.19-preempt    | 1        | 4.35%   |
| 5.3.18-59.16-default    | 1        | 4.35%   |
| 5.3.18-59.13-default    | 1        | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3.18  | 23       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.3     | 23       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 23       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE        | 9        | 39.13%  |
| KDE5       | 8        | 34.78%  |
| Unknown    | 3        | 13.04%  |
| XFCE       | 2        | 8.7%    |
| X-Cinnamon | 1        | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 20       | 86.96%  |
| Tty  | 3        | 13.04%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 15       | 65.22%  |
| LightDM | 6        | 26.09%  |
| SDDM    | 2        | 8.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 7        | 30.43%  |
| de_DE   | 5        | 21.74%  |
| pt_BR   | 3        | 13.04%  |
| POSIX   | 2        | 8.7%    |
| nl_BE   | 1        | 4.35%   |
| hr_HR   | 1        | 4.35%   |
| es_MX   | 1        | 4.35%   |
| en_GB   | 1        | 4.35%   |
| en_AU   | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 15       | 65.22%  |
| EFI  | 8        | 34.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 14       | 60.87%  |
| Ext4  | 7        | 30.43%  |
| Xfs   | 2        | 8.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 56.52%  |
| GPT     | 9        | 39.13%  |
| MBR     | 1        | 4.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 95.65%  |
| Yes       | 1        | 4.35%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 82.61%  |
| Yes       | 4        | 17.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 5        | 21.74%  |
| ASUSTek Computer    | 5        | 21.74%  |
| Hewlett-Packard     | 4        | 17.39%  |
| ASRock              | 3        | 13.04%  |
| Gigabyte Technology | 2        | 8.7%    |
| VS Company          | 1        | 4.35%   |
| Lenovo              | 1        | 4.35%   |
| Intel               | 1        | 4.35%   |
| Alienware           | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| VS Company VS-G31T-M                         | 1        | 4.35%   |
| MSI MS-7C34                                  | 1        | 4.35%   |
| MSI MS-7A34                                  | 1        | 4.35%   |
| MSI MS-7A33                                  | 1        | 4.35%   |
| MSI MS-7817                                  | 1        | 4.35%   |
| MSI ESPRIMO P1510                            | 1        | 4.35%   |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1        | 4.35%   |
| Intel DG41WV AAE90316-104                    | 1        | 4.35%   |
| HP xw4400 Workstation                        | 1        | 4.35%   |
| HP Pavilion Gaming Desktop 690-00xx          | 1        | 4.35%   |
| HP EliteDesk 800 G2 DM 65W                   | 1        | 4.35%   |
| HP 200-5120br                                | 1        | 4.35%   |
| Gigabyte B550 AORUS PRO AC                   | 1        | 4.35%   |
| Gigabyte B250M-DS3H                          | 1        | 4.35%   |
| ASUS TUF B450-PRO GAMING                     | 1        | 4.35%   |
| ASUS PRIME H310M-A                           | 1        | 4.35%   |
| ASUS P8H61-M LE/USB3                         | 1        | 4.35%   |
| ASUS M4A78T-E                                | 1        | 4.35%   |
| ASUS All Series                              | 1        | 4.35%   |
| ASRock X570M Pro4                            | 1        | 4.35%   |
| ASRock X570 Steel Legend                     | 1        | 4.35%   |
| ASRock B450M Pro4                            | 1        | 4.35%   |
| Alienware X51 R2                             | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| VS Company VS-G31T-M | 1        | 4.35%   |
| MSI MS-7C34          | 1        | 4.35%   |
| MSI MS-7A34          | 1        | 4.35%   |
| MSI MS-7A33          | 1        | 4.35%   |
| MSI MS-7817          | 1        | 4.35%   |
| MSI ESPRIMO          | 1        | 4.35%   |
| Lenovo IdeaCentre    | 1        | 4.35%   |
| Intel DG41WV         | 1        | 4.35%   |
| HP xw4400            | 1        | 4.35%   |
| HP Pavilion          | 1        | 4.35%   |
| HP EliteDesk         | 1        | 4.35%   |
| HP 200-5120br        | 1        | 4.35%   |
| Gigabyte B550        | 1        | 4.35%   |
| Gigabyte B250M-DS3H  | 1        | 4.35%   |
| ASUS TUF             | 1        | 4.35%   |
| ASUS PRIME           | 1        | 4.35%   |
| ASUS P8H61-M         | 1        | 4.35%   |
| ASUS M4A78T-E        | 1        | 4.35%   |
| ASUS All             | 1        | 4.35%   |
| ASRock X570M         | 1        | 4.35%   |
| ASRock X570          | 1        | 4.35%   |
| ASRock B450M         | 1        | 4.35%   |
| Alienware X51        | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2010 | 5        | 21.74%  |
| 2018 | 4        | 17.39%  |
| 2021 | 3        | 13.04%  |
| 2020 | 3        | 13.04%  |
| 2019 | 2        | 8.7%    |
| 2016 | 2        | 8.7%    |
| 2017 | 1        | 4.35%   |
| 2015 | 1        | 4.35%   |
| 2011 | 1        | 4.35%   |
| 2009 | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 23       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 8        | 34.78%  |
| 8.01-16.0   | 5        | 21.74%  |
| 64.01-256.0 | 4        | 17.39%  |
| 3.01-4.0    | 3        | 13.04%  |
| 4.01-8.0    | 2        | 8.7%    |
| 32.01-64.0  | 1        | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 11       | 47.83%  |
| 4.01-8.0  | 5        | 21.74%  |
| 3.01-4.0  | 3        | 13.04%  |
| 2.01-3.0  | 2        | 8.7%    |
| 8.01-16.0 | 1        | 4.35%   |
| 0.51-1.0  | 1        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 43.48%  |
| 3      | 6        | 26.09%  |
| 2      | 4        | 17.39%  |
| 4      | 2        | 8.7%    |
| 6      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 60.87%  |
| No        | 9        | 39.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 95.65%  |
| No        | 1        | 4.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 69.57%  |
| No        | 7        | 30.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 60.87%  |
| Yes       | 9        | 39.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| Germany    | 5        | 21.74%  |
| Brazil     | 4        | 17.39%  |
| USA        | 3        | 13.04%  |
| Mexico     | 2        | 8.7%    |
| Japan      | 2        | 8.7%    |
| Australia  | 2        | 8.7%    |
| Slovakia   | 1        | 4.35%   |
| Russia     | 1        | 4.35%   |
| Luxembourg | 1        | 4.35%   |
| Croatia    | 1        | 4.35%   |
| Belgium    | 1        | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Tokyo                 | 2        | 8.7%    |
| Três Lagoas          | 1        | 4.35%   |
| São Paulo            | 1        | 4.35%   |
| Stupava               | 1        | 4.35%   |
| Stabroek              | 1        | 4.35%   |
| San Luis Potos?� City | 1        | 4.35%   |
| Recife                | 1        | 4.35%   |
| Oregon                | 1        | 4.35%   |
| Nordenham             | 1        | 4.35%   |
| Munich                | 1        | 4.35%   |
| Melbourne             | 1        | 4.35%   |
| McDonough             | 1        | 4.35%   |
| Luxembourg            | 1        | 4.35%   |
| Lomonosov             | 1        | 4.35%   |
| Heinsberg             | 1        | 4.35%   |
| Federal Way           | 1        | 4.35%   |
| Ebhausen              | 1        | 4.35%   |
| Chapec??              | 1        | 4.35%   |
| Canc??n               | 1        | 4.35%   |
| Busevec               | 1        | 4.35%   |
| Brisbane              | 1        | 4.35%   |
| Braunschweig          | 1        | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 15     | 27.91%  |
| Samsung Electronics | 8        | 10     | 18.6%   |
| Seagate             | 7        | 9      | 16.28%  |
| Intel               | 3        | 3      | 6.98%   |
| A-DATA Technology   | 3        | 3      | 6.98%   |
| SanDisk             | 2        | 2      | 4.65%   |
| Hitachi             | 2        | 2      | 4.65%   |
| Unknown             | 1        | 1      | 2.33%   |
| Toshiba             | 1        | 1      | 2.33%   |
| TO Exter            | 1        | 1      | 2.33%   |
| Phison              | 1        | 1      | 2.33%   |
| HGST HTS            | 1        | 1      | 2.33%   |
| Crucial             | 1        | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST3750528AS 752GB            | 2        | 4%      |
| Seagate ST2000DM006-2DM164 2TB       | 2        | 4%      |
| Samsung SSD 860 EVO 250GB            | 2        | 4%      |
| Samsung SSD 850 EVO 500GB            | 2        | 4%      |
| WDC WDS500G1X0E-00AFY0 500GB         | 1        | 2%      |
| WDC WDS250G1B0C-00S6U0 250GB         | 1        | 2%      |
| WDC WD7500AALX-009BA0 752GB          | 1        | 2%      |
| WDC WD5000AAVS-00ZTB0 500GB          | 1        | 2%      |
| WDC WD50 00LPCX-00VHAT0 500GB        | 1        | 2%      |
| WDC WD3200AAKS-00B3A0 320GB          | 1        | 2%      |
| WDC WD2500AAJS-00VTA0 250GB          | 1        | 2%      |
| WDC WD2005FBYZ-01YCBB2 2TB           | 1        | 2%      |
| WDC WD10EZEX-75M2NA0 1TB             | 1        | 2%      |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 2%      |
| WDC WD10EZEX-00KUWA0 1TB             | 1        | 2%      |
| WDC WD10EZEX-00BN5A0 1TB             | 1        | 2%      |
| WDC WD10EACS-00D6B1 1TB              | 1        | 2%      |
| WDC WD1003FZEX-00K3CA0 1TB           | 1        | 2%      |
| WDC WD1001FALS-00E3A0 1TB            | 1        | 2%      |
| Unknown 128GB SATA FLASH DRIVE       | 1        | 2%      |
| Toshiba HDWD130 3TB                  | 1        | 2%      |
| TO Exter nal USB 3.0 4TB             | 1        | 2%      |
| Seagate ST500LM0 12 HN-M500MBB 500GB | 1        | 2%      |
| Seagate ST3750630AS 752GB            | 1        | 2%      |
| Seagate ST3160812AS 160GB            | 1        | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1        | 2%      |
| Seagate ST1000DM010-2EP102 1TB       | 1        | 2%      |
| SanDisk SD7SB6S256G1001 256GB SSD    | 1        | 2%      |
| SanDisk SD7SB3Q-256G-1006 256GB SSD  | 1        | 2%      |
| Samsung SSD 980 PRO 1TB              | 1        | 2%      |
| Samsung SSD 870 QVO 1TB              | 1        | 2%      |
| Samsung SSD 850 EVO 250GB            | 1        | 2%      |
| Samsung SSD 840 Series 120GB         | 1        | 2%      |
| Samsung MZVPV512HDGL-000H1 512GB     | 1        | 2%      |
| Samsung HD401LJ 400GB                | 1        | 2%      |
| Phison Viper M.2 VPN100 512GB        | 1        | 2%      |
| Intel SSDSC2BW240A4 240GB            | 1        | 2%      |
| Intel SSDSC2BB012T7O 1TB             | 1        | 2%      |
| Intel NVMe SSD Drive 512GB           | 1        | 2%      |
| Hitachi HDS725050KLA360 500GB        | 1        | 2%      |
| Hitachi HDS721010CLA332 1TB          | 1        | 2%      |
| HGST HTS 545050A7E380 500GB          | 1        | 2%      |
| Crucial CT1000P1SSD8 1TB             | 1        | 2%      |
| A-DATA SU800 256GB SSD               | 1        | 2%      |
| A-DATA SU650 2TB SSD                 | 1        | 2%      |
| A-DATA SSD 32GB                      | 1        | 2%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 13     | 45.45%  |
| Seagate             | 7        | 9      | 31.82%  |
| Hitachi             | 2        | 2      | 9.09%   |
| Toshiba             | 1        | 1      | 4.55%   |
| TO Exter            | 1        | 1      | 4.55%   |
| Samsung Electronics | 1        | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 7      | 41.67%  |
| A-DATA Technology   | 3        | 3      | 25%     |
| SanDisk             | 2        | 2      | 16.67%  |
| Intel               | 2        | 2      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 16       | 27     | 45.71%  |
| SSD     | 12       | 14     | 34.29%  |
| NVMe    | 6        | 7      | 17.14%  |
| Unknown | 1        | 2      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 39     | 73.33%  |
| NVMe | 6        | 7      | 20%     |
| SAS  | 2        | 4      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 15       | 16     | 44.12%  |
| 0.01-0.5   | 13       | 19     | 38.24%  |
| 1.01-2.0   | 4        | 4      | 11.76%  |
| 3.01-4.0   | 1        | 1      | 2.94%   |
| 2.01-3.0   | 1        | 1      | 2.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 6        | 26.09%  |
| 2001-3000      | 4        | 17.39%  |
| 1001-2000      | 4        | 17.39%  |
| 501-1000       | 4        | 17.39%  |
| More than 3000 | 3        | 13.04%  |
| 1-20           | 1        | 4.35%   |
| Unknown        | 1        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 251-500   | 6        | 26.09%  |
| 101-250   | 4        | 17.39%  |
| 1001-2000 | 3        | 13.04%  |
| 501-1000  | 3        | 13.04%  |
| 51-100    | 3        | 13.04%  |
| 1-20      | 2        | 8.7%    |
| 2001-3000 | 1        | 4.35%   |
| Unknown   | 1        | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                    | Desktops | Drives | Percent |
|--------------------------|----------|--------|---------|
| Crucial CT1000P1SSD8 1TB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Crucial | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 1        | 1      | 100%    |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 13       | 30     | 54.17%  |
| Works    | 10       | 19     | 41.67%  |
| Malfunc  | 1        | 1      | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 13       | 40.63%  |
| AMD                       | 11       | 34.38%  |
| Sandisk                   | 2        | 6.25%   |
| Samsung Electronics       | 2        | 6.25%   |
| Silicon Image             | 1        | 3.13%   |
| Phison Electronics        | 1        | 3.13%   |
| Micron/Crucial Technology | 1        | 3.13%   |
| ASMedia Technology        | 1        | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9        | 21.95%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 4.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 4.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 4.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 2        | 4.88%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 4.88%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1        | 2.44%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1        | 2.44%   |
| Sandisk WD Black SN850                                                                  | 1        | 2.44%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1        | 2.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 2.44%   |
| Phison E12 NVMe Controller                                                              | 1        | 2.44%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1        | 2.44%   |
| Intel SSD 660P Series                                                                   | 1        | 2.44%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 2.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 2.44%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 2.44%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                            | 1        | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 2.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 2.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.44%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 2.44%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 2.44%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 1        | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 2.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 56.25%  |
| NVMe | 6        | 18.75%  |
| IDE  | 5        | 15.63%  |
| RAID | 3        | 9.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 12       | 52.17%  |
| AMD    | 11       | 47.83%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 8.7%    |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2        | 8.7%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 4.35%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1        | 4.35%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 4.35%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 4.35%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 4.35%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 4.35%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 4.35%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 4.35%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 4.35%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1        | 4.35%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1        | 4.35%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 1        | 4.35%   |
| AMD Sempron 2650 APU with Radeon R3         | 1        | 4.35%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 1        | 4.35%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 1        | 4.35%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1        | 4.35%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 1        | 4.35%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 4.35%   |
| AMD Phenom II X4 B50 Processor              | 1        | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 9             | 4        | 17.39%  |
| Intel Core i7           | 3        | 13.04%  |
| Intel Core i5           | 3        | 13.04%  |
| AMD Ryzen 7             | 3        | 13.04%  |
| AMD Ryzen 5             | 2        | 8.7%    |
| Intel Pentium Dual-Core | 1        | 4.35%   |
| Intel Pentium           | 1        | 4.35%   |
| Intel Core i3           | 1        | 4.35%   |
| Intel Core 2 Quad       | 1        | 4.35%   |
| Intel Core 2 Duo        | 1        | 4.35%   |
| Intel Core 2            | 1        | 4.35%   |
| AMD Sempron             | 1        | 4.35%   |
| AMD Phenom II X4        | 1        | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 9        | 39.13%  |
| 2      | 5        | 21.74%  |
| 8      | 3        | 13.04%  |
| 16     | 2        | 8.7%    |
| 12     | 2        | 8.7%    |
| 6      | 2        | 8.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 52.17%  |
| 1      | 11       | 47.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 23       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 12       | 52.17%  |
| 0x0a201009 | 2        | 8.7%    |
| 0x08001137 | 2        | 8.7%    |
| 0x906e9    | 1        | 4.35%   |
| 0x306c3    | 1        | 4.35%   |
| 0x206a7    | 1        | 4.35%   |
| 0x1067a    | 1        | 4.35%   |
| 0x10677    | 1        | 4.35%   |
| 0x0a201016 | 1        | 4.35%   |
| 0x08701021 | 1        | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen         | 4        | 17.39%  |
| Zen 3       | 3        | 13.04%  |
| Penryn      | 3        | 13.04%  |
| Zen 2       | 2        | 8.7%    |
| Skylake     | 2        | 8.7%    |
| KabyLake    | 2        | 8.7%    |
| Haswell     | 2        | 8.7%    |
| SandyBridge | 1        | 4.35%   |
| Nehalem     | 1        | 4.35%   |
| K10         | 1        | 4.35%   |
| Jaguar      | 1        | 4.35%   |
| Core        | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 11       | 45.83%  |
| Intel  | 7        | 29.17%  |
| AMD    | 6        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 8.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 8.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2        | 8.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 4.17%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 4.17%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 4.17%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 4.17%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 4.17%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 4.17%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1        | 4.17%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 4.17%   |
| Intel HD Graphics 630                                                       | 1        | 4.17%   |
| Intel HD Graphics 530                                                       | 1        | 4.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 4.17%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 4.17%   |
| AMD RV610 [Radeon HD 2400 PRO]                                              | 1        | 4.17%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 4.17%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 4.17%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                     | 1        | 4.17%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 11       | 47.83%  |
| 1 x Intel  | 6        | 26.09%  |
| 1 x AMD    | 6        | 26.09%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 15       | 65.22%  |
| Proprietary | 7        | 30.43%  |
| Unknown     | 1        | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 65.22%  |
| 3.01-4.0   | 2        | 8.7%    |
| 16.01-24.0 | 2        | 8.7%    |
| 8.01-16.0  | 2        | 8.7%    |
| 5.01-6.0   | 1        | 4.35%   |
| 0.51-1.0   | 1        | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 4        | 16.67%  |
| Dell                 | 4        | 16.67%  |
| Samsung Electronics  | 3        | 12.5%   |
| Acer                 | 3        | 12.5%   |
| LG Electronics       | 2        | 8.33%   |
| Hewlett-Packard      | 2        | 8.33%   |
| BenQ                 | 2        | 8.33%   |
| Philips              | 1        | 4.17%   |
| Denver               | 1        | 4.17%   |
| AOC                  | 1        | 4.17%   |
| Ancor Communications | 1        | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch  | 1        | 4%      |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1        | 4%      |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1        | 4%      |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                     | 1        | 4%      |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1        | 4%      |
| LG Electronics LCD Monitor LG TV SSCR 3840x2160                       | 1        | 4%      |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1        | 4%      |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 1        | 4%      |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch           | 1        | 4%      |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                 | 1        | 4%      |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                  | 1        | 4%      |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                  | 1        | 4%      |
| Denver UWQHD-100-V2 LHC3500 3440x1440 798x342mm 34.2-inch             | 1        | 4%      |
| Dell UZ2315H DELF055 1920x1080 509x286mm 23.0-inch                    | 1        | 4%      |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 1        | 4%      |
| Dell P2219H DELA114 1920x1080 476x267mm 21.5-inch                     | 1        | 4%      |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                    | 1        | 4%      |
| BenQ SW2700 BNQ7F47 2560x1440 596x335mm 26.9-inch                     | 1        | 4%      |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                     | 1        | 4%      |
| AOC LCD Monitor 28E850 640x480                                        | 1        | 4%      |
| Ancor Communications ASUS VN248 ACI24C4 1920x1080 530x300mm 24.0-inch | 1        | 4%      |
| Acer X163W ACR0015 1366x768 344x193mm 15.5-inch                       | 1        | 4%      |
| Acer V203H ACR0102 1600x900 443x249mm 20.0-inch                       | 1        | 4%      |
| Acer V203H ACR00C7 1600x900 443x249mm 20.0-inch                       | 1        | 4%      |
| Acer GD245HQ ACR0125 1920x1080 520x290mm 23.4-inch                    | 1        | 4%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 9        | 42.86%  |
| 2560x1440 (QHD)    | 2        | 9.52%   |
| 2560x1080          | 2        | 9.52%   |
| 640x480            | 1        | 4.76%   |
| 3840x2160 (4K)     | 1        | 4.76%   |
| 3440x1440          | 1        | 4.76%   |
| 1680x1050 (WSXGA+) | 1        | 4.76%   |
| 1600x900 (HD+)     | 1        | 4.76%   |
| 1366x768 (WXGA)    | 1        | 4.76%   |
| 1280x1024 (SXGA)   | 1        | 4.76%   |
| 1024x768 (XGA)     | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 4        | 18.18%  |
| 21      | 3        | 13.64%  |
| Unknown | 3        | 13.64%  |
| 34      | 2        | 9.09%   |
| 24      | 2        | 9.09%   |
| 23      | 2        | 9.09%   |
| 15      | 2        | 9.09%   |
| 22      | 1        | 4.55%   |
| 20      | 1        | 4.55%   |
| 18      | 1        | 4.55%   |
| 17      | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 36.36%  |
| 401-500     | 6        | 27.27%  |
| 301-350     | 3        | 13.64%  |
| Unknown     | 3        | 13.64%  |
| 701-800     | 2        | 9.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 61.9%   |
| Unknown | 3        | 14.29%  |
| 21/9    | 2        | 9.52%   |
| 5/4     | 1        | 4.76%   |
| 4/3     | 1        | 4.76%   |
| 16/10   | 1        | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 31.82%  |
| 301-350        | 4        | 18.18%  |
| Unknown        | 3        | 13.64%  |
| 351-500        | 2        | 9.09%   |
| 151-200        | 2        | 9.09%   |
| 141-150        | 2        | 9.09%   |
| 101-110        | 2        | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 54.55%  |
| 101-120 | 7        | 31.82%  |
| Unknown | 3        | 13.64%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 73.91%  |
| 2     | 4        | 17.39%  |
| 0     | 2        | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 51.52%  |
| Intel                 | 8        | 24.24%  |
| Ralink                | 3        | 9.09%   |
| Qualcomm Atheros      | 2        | 6.06%   |
| Samsung Electronics   | 1        | 3.03%   |
| Broadcom Limited      | 1        | 3.03%   |
| AVM                   | 1        | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 32.5%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 7.5%    |
| Intel I211 Gigabit Network Connection                             | 2        | 5%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 2.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1        | 2.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.5%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 2.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 2.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 2.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 2.5%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 1        | 2.5%    |
| Ralink RT2561/RT61 802.11g PCI                                    | 1        | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 2.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 2.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 2.5%    |
| Intel Wireless-AC 9260                                            | 1        | 2.5%    |
| Intel Wireless 8260                                               | 1        | 2.5%    |
| Intel Wireless 7260                                               | 1        | 2.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.5%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1        | 2.5%    |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                              | 1        | 2.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 43.75%  |
| Realtek Semiconductor | 3        | 18.75%  |
| Ralink                | 3        | 18.75%  |
| Qualcomm Atheros      | 1        | 6.25%   |
| Broadcom Limited      | 1        | 6.25%   |
| AVM                   | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 3        | 18.75%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 6.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1        | 6.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1        | 6.25%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                  | 1        | 6.25%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                       | 1        | 6.25%   |
| Ralink RT2561/RT61 802.11g PCI                             | 1        | 6.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1        | 6.25%   |
| Intel Wireless-AC 9260                                     | 1        | 6.25%   |
| Intel Wireless 8260                                        | 1        | 6.25%   |
| Intel Wireless 7260                                        | 1        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 6.25%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1        | 6.25%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                       | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 73.91%  |
| Intel                 | 3        | 13.04%  |
| Qualcomm Atheros      | 2        | 8.7%    |
| Samsung Electronics   | 1        | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13       | 54.17%  |
| Intel I211 Gigabit Network Connection                             | 2        | 8.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4.17%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 4.17%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 4.17%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 4.17%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 4.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 4.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 57.89%  |
| WiFi     | 16       | 42.11%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 60.61%  |
| WiFi     | 13       | 39.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 12       | 52.17%  |
| 1     | 9        | 39.13%  |
| 3     | 2        | 8.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 86.96%  |
| Yes  | 3        | 13.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 55.56%  |
| Realtek Semiconductor           | 1        | 11.11%  |
| Qualcomm Atheros Communications | 1        | 11.11%  |
| Dell                            | 1        | 11.11%  |
| Cambridge Silicon Radio         | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 22.22%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 11.11%  |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 11.11%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 11.11%  |
| Intel Bluetooth wireless interface                  | 1        | 11.11%  |
| Intel Bluetooth Device                              | 1        | 11.11%  |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| AMD                       | 14       | 35%     |
| Intel                     | 12       | 30%     |
| Nvidia                    | 11       | 27.5%   |
| Texas Instruments         | 1        | 2.5%    |
| Sennheiser Communications | 1        | 2.5%    |
| C-Media Electronics       | 1        | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 11.11%  |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 8.89%   |
| Nvidia GA102 High Definition Audio Controller                              | 3        | 6.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 6.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 4.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 4.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 4.44%   |
| Texas Instruments PCM2900C Audio CODEC                                     | 1        | 2.22%   |
| Sennheiser Communications Sennheiser 3D G4ME1                              | 1        | 2.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 2.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 2.22%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 2.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.22%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 2.22%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 2.22%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 2.22%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.22%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 2.22%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1        | 2.22%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1        | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.22%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1        | 2.22%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1        | 2.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 2.22%   |
| AMD Kabini HDMI/DP Audio                                                   | 1        | 2.22%   |
| AMD FCH Azalia Controller                                                  | 1        | 2.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 4        | 33.33%  |
| G.Skill             | 3        | 25%     |
| Crucial             | 2        | 16.67%  |
| Unknown             | 1        | 8.33%   |
| Samsung Electronics | 1        | 8.33%   |
| GeIL                | 1        | 8.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s    | 2        | 16.67%  |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s              | 1        | 8.33%   |
| Samsung RAM M471B5673FH0-CH9 2048MB DIMM SDRAM 4199MT/s   | 1        | 8.33%   |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s | 1        | 8.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s         | 1        | 8.33%   |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM DDR3 1600MT/s        | 1        | 8.33%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s    | 1        | 8.33%   |
| G.Skill RAM F4-2666C19-16GIS 16384MB DIMM DDR4 2667MT/s   | 1        | 8.33%   |
| G.Skill RAM F4-2400C15-8GNT 8192MB DIMM DDR4 2400MT/s     | 1        | 8.33%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s     | 1        | 8.33%   |
| Crucial RAM BL32G32C16U4R.M16FB1 32GB DIMM DDR4 3200MT/s  | 1        | 8.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 8        | 80%     |
| SDRAM | 1        | 10%     |
| DDR3  | 1        | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 10       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 40%     |
| 32768 | 3        | 30%     |
| 16384 | 2        | 20%     |
| 2048  | 1        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 3        | 27.27%  |
| 3200  | 2        | 18.18%  |
| 4199  | 1        | 9.09%   |
| 2933  | 1        | 9.09%   |
| 2667  | 1        | 9.09%   |
| 2400  | 1        | 9.09%   |
| 1600  | 1        | 9.09%   |
| 800   | 1        | 9.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 2        | 33.33%  |
| Samsung Electronics | 1        | 16.67%  |
| Kyocera             | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |
| Canon               | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Samsung SCX-4200 series   | 1        | 16.67%  |
| Kyocera FS-1030D printer  | 1        | 16.67%  |
| HP ENVY 4500 series       | 1        | 16.67%  |
| Canon LiDE 300            | 1        | 16.67%  |
| Brother Printer           | 1        | 16.67%  |
| Brother HL-L3210CW series | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1        | 50%     |
| Canon CanoScan LiDE 210       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 3        | 75%     |
| Chicony Electronics | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech B525 HD Webcam | 2        | 50%     |
| Logitech Webcam C250    | 1        | 25%     |
| Chicony HP Webcam       | 1        | 25%     |

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
| 0     | 22       | 95.65%  |
| 1     | 1        | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 1        | 100%    |

