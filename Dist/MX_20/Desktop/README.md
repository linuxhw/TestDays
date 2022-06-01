MX 20 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MX 20.

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

Total: 23

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | PRIME H510M-A               | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| IBM      | 8183B2U                     | [d070680dfb](https://linux-hardware.org/?probe=d070680dfb) | Jan 14, 2022 |
| Gigabyte | F2A88X-UP4                  | [52e09bab91](https://linux-hardware.org/?probe=52e09bab91) | Jan 02, 2022 |
| Dell     | 00F82W A01                  | [08e803937e](https://linux-hardware.org/?probe=08e803937e) | Oct 18, 2021 |
| HP       | 21D0                        | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| ASRock   | H470M-ITX/ac                | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| ASRock   | H170M Pro4                  | [f291edbc4a](https://linux-hardware.org/?probe=f291edbc4a) | Jul 18, 2021 |
| Gigabyte | H110M-S2H-CF                | [192043ebbd](https://linux-hardware.org/?probe=192043ebbd) | Jul 12, 2021 |
| Dell     | 00F82W A01                  | [b85b636b73](https://linux-hardware.org/?probe=b85b636b73) | Jun 26, 2021 |
| ASUSTek  | TUF B450M-PRO GAMING        | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| MSI      | B450-A PRO MAX              | [506efba999](https://linux-hardware.org/?probe=506efba999) | May 02, 2021 |
| ASRock   | B560M Pro4                  | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| ASUSTek  | P5K-E                       | [f0c435ead1](https://linux-hardware.org/?probe=f0c435ead1) | Apr 01, 2021 |
| Dell     | 0XR1GT A00                  | [04145c0b36](https://linux-hardware.org/?probe=04145c0b36) | Mar 29, 2021 |
| ASUSTek  | TUF B450M-PRO GAMING        | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI      | MS-7210 100                 | [e8723eb58b](https://linux-hardware.org/?probe=e8723eb58b) | Mar 17, 2021 |
| MSI      | MAG B550M MORTAR WIFI       | [4789c5df48](https://linux-hardware.org/?probe=4789c5df48) | Feb 06, 2021 |
| HP       | 1905                        | [03a91e7ecc](https://linux-hardware.org/?probe=03a91e7ecc) | Nov 27, 2020 |
| ASUSTek  | Z97-E                       | [42c2810369](https://linux-hardware.org/?probe=42c2810369) | Apr 03, 2020 |
| MSI      | 760GM-P23                   | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| Gigabyte | Z390 GAMING X-CF            | [104b035076](https://linux-hardware.org/?probe=104b035076) | Apr 01, 2020 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | [1243c4a0d9](https://linux-hardware.org/?probe=1243c4a0d9) | Mar 24, 2020 |
| HP       | 1790                        | [68a167efd3](https://linux-hardware.org/?probe=68a167efd3) | Mar 24, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 4.19.0-6-amd64             | 4        | 17.39%  |
| 4.19.0-17-amd64            | 3        | 13.04%  |
| 5.8.0-3-amd64              | 2        | 8.7%    |
| 4.19.0-16-amd64            | 2        | 8.7%    |
| 5.6.0-2-amd64              | 1        | 4.35%   |
| 5.5.0-9.1-liquorix-amd64   | 1        | 4.35%   |
| 5.5.0-5.1-liquorix-amd64   | 1        | 4.35%   |
| 5.15.0-1mx-amd64           | 1        | 4.35%   |
| 5.11.0-16.1-liquorix-amd64 | 1        | 4.35%   |
| 5.10.0-8mx-amd64           | 1        | 4.35%   |
| 5.10.0-5mx-amd64           | 1        | 4.35%   |
| 5.10.0-4mx-amd64           | 1        | 4.35%   |
| 4.19.0-9-686-pae           | 1        | 4.35%   |
| 4.19.0-18-amd64            | 1        | 4.35%   |
| 4.19.0-14-amd64            | 1        | 4.35%   |
| 4.19.0-12-amd64            | 1        | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 13       | 56.52%  |
| 5.10.0  | 3        | 13.04%  |
| 5.8.0   | 2        | 8.7%    |
| 5.5.0   | 2        | 8.7%    |
| 5.6.0   | 1        | 4.35%   |
| 5.15.0  | 1        | 4.35%   |
| 5.11.0  | 1        | 4.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 13       | 56.52%  |
| 5.10    | 3        | 13.04%  |
| 5.8     | 2        | 8.7%    |
| 5.5     | 2        | 8.7%    |
| 5.6     | 1        | 4.35%   |
| 5.15    | 1        | 4.35%   |
| 5.11    | 1        | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 20       | 95.24%  |
| i686   | 1        | 4.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| XFCE | 16       | 76.19%  |
| KDE5 | 4        | 19.05%  |
| MATE | 1        | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 21       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 19       | 90.48%  |
| SDDM    | 2        | 9.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 63.64%  |
| en_US   | 4        | 18.18%  |
| es_ES   | 3        | 13.64%  |
| ru_RU   | 1        | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 11       | 52.38%  |
| EFI  | 10       | 47.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 21       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 13       | 61.9%   |
| MBR  | 8        | 38.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 59.09%  |
| Yes       | 9        | 40.91%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 57.14%  |
| No        | 9        | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 4        | 19.05%  |
| Gigabyte Technology | 4        | 19.05%  |
| ASUSTek Computer    | 4        | 19.05%  |
| Hewlett-Packard     | 3        | 14.29%  |
| ASRock              | 3        | 14.29%  |
| Dell                | 2        | 9.52%   |
| IBM                 | 1        | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7C94                      | 1        | 4.76%   |
| MSI MS-7B86                      | 1        | 4.76%   |
| MSI MS-7641                      | 1        | 4.76%   |
| MSI GEG                          | 1        | 4.76%   |
| IBM 8183B2U                      | 1        | 4.76%   |
| HP Z230 Tower Workstation        | 1        | 4.76%   |
| HP Z220 CMT Workstation          | 1        | 4.76%   |
| HP ProDesk 600 G1 DM             | 1        | 4.76%   |
| Gigabyte Z390 GAMING X           | 1        | 4.76%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 4.76%   |
| Gigabyte H110M-S2H               | 1        | 4.76%   |
| Gigabyte F2A88X-UP4              | 1        | 4.76%   |
| Dell OptiPlex 9010               | 1        | 4.76%   |
| Dell Inspiron 660                | 1        | 4.76%   |
| ASUS TUF B450M-PRO GAMING        | 1        | 4.76%   |
| ASUS PRIME H510M-A               | 1        | 4.76%   |
| ASUS P5K-E                       | 1        | 4.76%   |
| ASUS All Series                  | 1        | 4.76%   |
| ASRock H470M-ITX/ac              | 1        | 4.76%   |
| ASRock H170M Pro4                | 1        | 4.76%   |
| ASRock B560M Pro4                | 1        | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI MS-7C94         | 1        | 4.76%   |
| MSI MS-7B86         | 1        | 4.76%   |
| MSI MS-7641         | 1        | 4.76%   |
| MSI GEG             | 1        | 4.76%   |
| IBM 8183B2U         | 1        | 4.76%   |
| HP Z230             | 1        | 4.76%   |
| HP Z220             | 1        | 4.76%   |
| HP ProDesk          | 1        | 4.76%   |
| Gigabyte Z390       | 1        | 4.76%   |
| Gigabyte X470       | 1        | 4.76%   |
| Gigabyte H110M-S2H  | 1        | 4.76%   |
| Gigabyte F2A88X-UP4 | 1        | 4.76%   |
| Dell OptiPlex       | 1        | 4.76%   |
| Dell Inspiron       | 1        | 4.76%   |
| ASUS TUF            | 1        | 4.76%   |
| ASUS PRIME          | 1        | 4.76%   |
| ASUS P5K-E          | 1        | 4.76%   |
| ASUS All            | 1        | 4.76%   |
| ASRock H470M-ITX    | 1        | 4.76%   |
| ASRock H170M        | 1        | 4.76%   |
| ASRock B560M        | 1        | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2014 | 3        | 14.29%  |
| 2021 | 2        | 9.52%   |
| 2020 | 2        | 9.52%   |
| 2019 | 2        | 9.52%   |
| 2018 | 2        | 9.52%   |
| 2013 | 2        | 9.52%   |
| 2012 | 2        | 9.52%   |
| 2016 | 1        | 4.76%   |
| 2015 | 1        | 4.76%   |
| 2011 | 1        | 4.76%   |
| 2007 | 1        | 4.76%   |
| 2006 | 1        | 4.76%   |
| 2005 | 1        | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 21       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 21       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 8        | 38.1%   |
| 8.01-16.0  | 5        | 23.81%  |
| 32.01-64.0 | 3        | 14.29%  |
| 24.01-32.0 | 2        | 9.52%   |
| 4.01-8.0   | 1        | 4.76%   |
| 3.01-4.0   | 1        | 4.76%   |
| 1.01-2.0   | 1        | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 7        | 31.82%  |
| 4.01-8.0  | 6        | 27.27%  |
| 3.01-4.0  | 3        | 13.64%  |
| 2.01-3.0  | 3        | 13.64%  |
| 0.51-1.0  | 2        | 9.09%   |
| 8.01-16.0 | 1        | 4.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 40.91%  |
| 3      | 5        | 22.73%  |
| 1      | 5        | 22.73%  |
| 5      | 2        | 9.09%   |
| 4      | 1        | 4.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 52.38%  |
| Yes       | 10       | 47.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 52.38%  |
| Yes       | 10       | 47.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 76.19%  |
| Yes       | 5        | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 33.33%  |
| Spain       | 3        | 14.29%  |
| Sweden      | 2        | 9.52%   |
| Russia      | 2        | 9.52%   |
| Serbia      | 1        | 4.76%   |
| Philippines | 1        | 4.76%   |
| Italy       | 1        | 4.76%   |
| Indonesia   | 1        | 4.76%   |
| Finland     | 1        | 4.76%   |
| Denmark     | 1        | 4.76%   |
| Canada      | 1        | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Tacoma                   | 1        | 4.55%   |
| Stockholm                | 1        | 4.55%   |
| Södertälje             | 1        | 4.55%   |
| Sibulan                  | 1        | 4.55%   |
| Podolsk                  | 1        | 4.55%   |
| Omsk                     | 1        | 4.55%   |
| Novi Knezevac            | 1        | 4.55%   |
| Mount Pocono             | 1        | 4.55%   |
| Mechanicsburg            | 1        | 4.55%   |
| Manado                   | 1        | 4.55%   |
| Madrid                   | 1        | 4.55%   |
| La Puebla                | 1        | 4.55%   |
| Huntsville               | 1        | 4.55%   |
| Franklin                 | 1        | 4.55%   |
| Fanny Bay                | 1        | 4.55%   |
| Espoo                    | 1        | 4.55%   |
| Chesapeake               | 1        | 4.55%   |
| Barcelona                | 1        | 4.55%   |
| Bacolod City             | 1        | 4.55%   |
| Ashburn                  | 1        | 4.55%   |
| Albertslund Municipality | 1        | 4.55%   |
| Albavilla                | 1        | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 12     | 22.73%  |
| Seagate             | 9        | 12     | 20.45%  |
| Samsung Electronics | 6        | 9      | 13.64%  |
| Kingston            | 4        | 4      | 9.09%   |
| A-DATA Technology   | 3        | 3      | 6.82%   |
| SanDisk             | 2        | 2      | 4.55%   |
| Hitachi             | 2        | 3      | 4.55%   |
| WDC WDS1            | 1        | 1      | 2.27%   |
| Toshiba             | 1        | 2      | 2.27%   |
| SPCC                | 1        | 1      | 2.27%   |
| PNY                 | 1        | 1      | 2.27%   |
| Intel               | 1        | 1      | 2.27%   |
| GOODRAM             | 1        | 1      | 2.27%   |
| Gigabyte Technology | 1        | 1      | 2.27%   |
| Crucial             | 1        | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WD1002FAEX-00Z3A0 1TB         | 2        | 4.08%   |
| Seagate ST2000DM008-2FR102 2TB    | 2        | 4.08%   |
| WDC WDS500G2B0A 500GB SSD         | 1        | 2.04%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD  | 1        | 2.04%   |
| WDC WDS250G2B0A-00SM50 250GB SSD  | 1        | 2.04%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 1        | 2.04%   |
| WDC WDS1 20G2G0A-00JH30 120GB SSD | 1        | 2.04%   |
| WDC WD800JD-00MSA1 80GB           | 1        | 2.04%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 2.04%   |
| WDC WD3200AAJS-00L7A0 320GB       | 1        | 2.04%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 1        | 2.04%   |
| WDC WD10EADS-65M2B0 1TB           | 1        | 2.04%   |
| Toshiba DT01ACA050 500GB          | 1        | 2.04%   |
| SPCC Solid State Disk 512GB       | 1        | 2.04%   |
| Seagate ST4000DM004-2CV104 4TB    | 1        | 2.04%   |
| Seagate ST3750330NS 752GB         | 1        | 2.04%   |
| Seagate ST3500830AS 500GB         | 1        | 2.04%   |
| Seagate ST3320620AS 320GB         | 1        | 2.04%   |
| Seagate ST31500341AS 1TB          | 1        | 2.04%   |
| Seagate ST2000DX001-1CM164 2TB    | 1        | 2.04%   |
| Seagate ST2000DM001-1CH164 2TB    | 1        | 2.04%   |
| Seagate Backup+ Desk 5TB          | 1        | 2.04%   |
| SanDisk SSD PLUS 1000GB           | 1        | 2.04%   |
| SanDisk SSD G5 BICS4 500GB        | 1        | 2.04%   |
| Samsung SSD 970 EVO Plus 500GB    | 1        | 2.04%   |
| Samsung SSD 870 EVO 500GB         | 1        | 2.04%   |
| Samsung SSD 860 QVO 1TB           | 1        | 2.04%   |
| Samsung SSD 860 EVO M.2 250GB     | 1        | 2.04%   |
| Samsung SSD 860 EVO 500GB         | 1        | 2.04%   |
| Samsung SSD 860 EVO 250GB         | 1        | 2.04%   |
| Samsung SSD 860 EVO 1TB           | 1        | 2.04%   |
| Samsung SSD 850 EVO 250GB         | 1        | 2.04%   |
| Samsung SSD 830 Series 128GB      | 1        | 2.04%   |
| PNY CS900 480GB SSD               | 1        | 2.04%   |
| Kingston SKC400S37128G 128GB SSD  | 1        | 2.04%   |
| Kingston SH103S3120G 120GB SSD    | 1        | 2.04%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 2.04%   |
| Kingston SA2000M81000G 1TB        | 1        | 2.04%   |
| Intel SSDSCKHF240A4L 240GB        | 1        | 2.04%   |
| Hitachi HUA723030ALA641 3TB       | 1        | 2.04%   |
| Hitachi HDS728080PLA380 80GB      | 1        | 2.04%   |
| GOODRAM IR-SSDPR-S25A-240 240GB   | 1        | 2.04%   |
| Gigabyte GP-GSTFS31120GNTD 120GB  | 1        | 2.04%   |
| Crucial CT500BX100SSD1 500GB      | 1        | 2.04%   |
| A-DATA SX8200PNP 512GB            | 1        | 2.04%   |
| A-DATA SU800 256GB SSD            | 1        | 2.04%   |
| A-DATA SU630 480GB SSD            | 1        | 2.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 9        | 11     | 50%     |
| WDC     | 6        | 7      | 33.33%  |
| Hitachi | 2        | 3      | 11.11%  |
| Toshiba | 1        | 2      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 8      | 25%     |
| WDC                 | 4        | 5      | 16.67%  |
| Kingston            | 3        | 3      | 12.5%   |
| SanDisk             | 2        | 2      | 8.33%   |
| A-DATA Technology   | 2        | 2      | 8.33%   |
| WDC WDS1            | 1        | 1      | 4.17%   |
| SPCC                | 1        | 1      | 4.17%   |
| PNY                 | 1        | 1      | 4.17%   |
| Intel               | 1        | 1      | 4.17%   |
| GOODRAM             | 1        | 1      | 4.17%   |
| Gigabyte Technology | 1        | 1      | 4.17%   |
| Crucial             | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 18       | 27     | 51.43%  |
| HDD     | 14       | 23     | 40%     |
| NVMe    | 2        | 3      | 5.71%   |
| Unknown | 1        | 1      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 21       | 49     | 84%     |
| SAS  | 2        | 2      | 8%      |
| NVMe | 2        | 3      | 8%      |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 31     | 54.55%  |
| 0.51-1.0   | 8        | 9      | 24.24%  |
| 1.01-2.0   | 5        | 6      | 15.15%  |
| 3.01-4.0   | 1        | 2      | 3.03%   |
| 2.01-3.0   | 1        | 2      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 5        | 23.81%  |
| 101-250        | 4        | 19.05%  |
| More than 3000 | 3        | 14.29%  |
| 1001-2000      | 3        | 14.29%  |
| 51-100         | 3        | 14.29%  |
| 501-1000       | 2        | 9.52%   |
| 2001-3000      | 1        | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 5        | 23.81%  |
| 251-500        | 3        | 14.29%  |
| 101-250        | 3        | 14.29%  |
| 501-1000       | 3        | 14.29%  |
| More than 3000 | 2        | 9.52%   |
| 21-50          | 2        | 9.52%   |
| 51-100         | 2        | 9.52%   |
| 2001-3000      | 1        | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| SPCC Solid State Disk 512GB | 1        | 1      | 33.33%  |
| Seagate ST3750330NS 752GB   | 1        | 1      | 33.33%  |
| Seagate ST31500341AS 1TB    | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| SPCC    | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Works    | 21       | 50     | 84%     |
| Malfunc  | 3        | 3      | 12%     |
| Detected | 1        | 1      | 4%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 15       | 60%     |
| AMD                         | 6        | 24%     |
| Samsung Electronics         | 1        | 4%      |
| Kingston Technology Company | 1        | 4%      |
| JMicron Technology          | 1        | 4%      |
| ADATA Technology            | 1        | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 10.34%  |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 10.34%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 6.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 6.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 6.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 6.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 3.45%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 3.45%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 3.45%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 3.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 3.45%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 3.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 3.45%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 3.45%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]           | 1        | 3.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 3.45%   |
| Intel 82801EB (ICH5) SATA Controller                                           | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 3.45%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 3.45%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 72%     |
| IDE  | 4        | 16%     |
| NVMe | 2        | 8%      |
| RAID | 1        | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 71.43%  |
| AMD    | 6        | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz             | 1        | 4.76%   |
| Intel Pentium D CPU 3.40GHz                     | 1        | 4.76%   |
| Intel Pentium CPU G3240T @ 2.70GHz              | 1        | 4.76%   |
| Intel Pentium 4 CPU 3.20GHz                     | 1        | 4.76%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 1        | 4.76%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 4.76%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1        | 4.76%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1        | 4.76%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 1        | 4.76%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 1        | 4.76%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 4.76%   |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1        | 4.76%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz            | 1        | 4.76%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1        | 4.76%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz          | 1        | 4.76%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 4.76%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 4.76%   |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 4.76%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 4.76%   |
| AMD Athlon II X2 270 Processor                  | 1        | 4.76%   |
| AMD A10-7850K Radeon R7, 12 Compute Cores 4C+8G | 1        | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 6        | 28.57%  |
| AMD Ryzen 5      | 3        | 14.29%  |
| Other            | 2        | 9.52%   |
| Intel Core i7    | 2        | 9.52%   |
| Intel Xeon       | 1        | 4.76%   |
| Intel Pentium D  | 1        | 4.76%   |
| Intel Pentium 4  | 1        | 4.76%   |
| Intel Pentium    | 1        | 4.76%   |
| Intel Core 2 Duo | 1        | 4.76%   |
| AMD Ryzen 7      | 1        | 4.76%   |
| AMD Athlon II X2 | 1        | 4.76%   |
| AMD A10          | 1        | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 33.33%  |
| 6      | 5        | 23.81%  |
| 2      | 5        | 23.81%  |
| 8      | 3        | 14.29%  |
| 1      | 1        | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 21       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 52.38%  |
| 2      | 10       | 47.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 20       | 95.24%  |
| 32-bit         | 1        | 4.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 3        | 14.29%  |
| 0x306a9    | 3        | 14.29%  |
| 0xa0671    | 2        | 9.52%   |
| 0x08701021 | 2        | 9.52%   |
| Unknown    | 2        | 9.52%   |
| 0xf64      | 1        | 4.76%   |
| 0xf29      | 1        | 4.76%   |
| 0xa0653    | 1        | 4.76%   |
| 0x906ed    | 1        | 4.76%   |
| 0x6fb      | 1        | 4.76%   |
| 0x506e3    | 1        | 4.76%   |
| 0x0800820d | 1        | 4.76%   |
| 0x0800820b | 1        | 4.76%   |
| 0x010000c8 | 1        | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 3        | 14.29%  |
| Haswell     | 3        | 14.29%  |
| Zen+        | 2        | 9.52%   |
| Zen 2       | 2        | 9.52%   |
| NetBurst    | 2        | 9.52%   |
| KabyLake    | 2        | 9.52%   |
| Steamroller | 1        | 4.76%   |
| Skylake     | 1        | 4.76%   |
| K10         | 1        | 4.76%   |
| Icelake     | 1        | 4.76%   |
| Core        | 1        | 4.76%   |
| CometLake   | 1        | 4.76%   |
| Unknown     | 1        | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 12       | 50%     |
| Intel  | 7        | 29.17%  |
| AMD    | 5        | 20.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 8.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 4.17%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 4.17%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 4.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 4.17%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 4.17%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 4.17%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 4.17%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 4.17%   |
| Nvidia GK107GL [Quadro K600]                                                | 1        | 4.17%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 4.17%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                           | 1        | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 4.17%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 4.17%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 4.17%   |
| Intel HD Graphics 630                                                       | 1        | 4.17%   |
| Intel 82865G Integrated Graphics Controller                                 | 1        | 4.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 4.17%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 4.17%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 4.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 11       | 52.38%  |
| 1 x Intel      | 4        | 19.05%  |
| 1 x AMD        | 4        | 19.05%  |
| Intel + Nvidia | 1        | 4.76%   |
| Intel + AMD    | 1        | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 57.14%  |
| Proprietary | 9        | 42.86%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 28.57%  |
| 0.51-1.0   | 5        | 23.81%  |
| 3.01-4.0   | 4        | 19.05%  |
| 5.01-6.0   | 3        | 14.29%  |
| 1.01-2.0   | 2        | 9.52%   |
| 7.01-8.0   | 1        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 14.81%  |
| Goldstar            | 4        | 14.81%  |
| Acer                | 4        | 14.81%  |
| Hewlett-Packard     | 2        | 7.41%   |
| Dell                | 2        | 7.41%   |
| ASUSTek Computer    | 2        | 7.41%   |
| ViewSonic           | 1        | 3.7%    |
| Videoseven          | 1        | 3.7%    |
| Vestel Elektronik   | 1        | 3.7%    |
| Sony                | 1        | 3.7%    |
| RIS                 | 1        | 3.7%    |
| Philips             | 1        | 3.7%    |
| Lenovo              | 1        | 3.7%    |
| Iiyama              | 1        | 3.7%    |
| BenQ                | 1        | 3.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                | 1        | 3.7%    |
| Videoseven D19W12C IGM19C1 1440x900 408x255mm 18.9-inch               | 1        | 3.7%    |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 1        | 3.7%    |
| Sony TV SNY0801 1360x768                                              | 1        | 3.7%    |
| Samsung Electronics SyncMaster SAM0420 1680x1050 474x296mm 22.0-inch  | 1        | 3.7%    |
| Samsung Electronics LCD Monitor SAM0D3B 3840x2160 890x500mm 40.2-inch | 1        | 3.7%    |
| Samsung Electronics C27JG5x SAM0F57 2560x1440 600x340mm 27.2-inch     | 1        | 3.7%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1        | 3.7%    |
| RIS photo19 RIS0839 1366x768 410x230mm 18.5-inch                      | 1        | 3.7%    |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 1        | 3.7%    |
| Lenovo LEN L192p LEN24CB 1280x1024 376x301mm 19.0-inch                | 1        | 3.7%    |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                  | 1        | 3.7%    |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch            | 1        | 3.7%    |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 1        | 3.7%    |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 1        | 3.7%    |
| Goldstar L1715S GSM436F 1280x1024 338x270mm 17.0-inch                 | 1        | 3.7%    |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1        | 3.7%    |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                   | 1        | 3.7%    |
| Dell ST2220L DELA063 1920x1080 477x268mm 21.5-inch                    | 1        | 3.7%    |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                     | 1        | 3.7%    |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                     | 1        | 3.7%    |
| ASUSTek Computer VP28U AUS28B1 3840x2160 620x340mm 27.8-inch          | 1        | 3.7%    |
| ASUSTek Computer VG279QL1A AUS2702 1920x1080 598x336mm 27.0-inch      | 1        | 3.7%    |
| Acer X34 P ACR054F 3440x1440 800x340mm 34.2-inch                      | 1        | 3.7%    |
| Acer S230HL ACR0280 1920x1080 509x286mm 23.0-inch                     | 1        | 3.7%    |
| Acer R240HY ACR046F 1920x1080 527x296mm 23.8-inch                     | 1        | 3.7%    |
| Acer G227HQL ACR03DE 1920x1080 476x267mm 21.5-inch                    | 1        | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 48%     |
| 3840x2160 (4K)     | 3        | 12%     |
| 2560x1440 (QHD)    | 2        | 8%      |
| 1360x768           | 2        | 8%      |
| 1280x1024 (SXGA)   | 2        | 8%      |
| 3440x1440          | 1        | 4%      |
| 1680x1050 (WSXGA+) | 1        | 4%      |
| 1440x900 (WXGA+)   | 1        | 4%      |
| 1024x768 (XGA)     | 1        | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 7        | 25.93%  |
| 21     | 5        | 18.52%  |
| 23     | 3        | 11.11%  |
| 84     | 2        | 7.41%   |
| 24     | 2        | 7.41%   |
| 18     | 2        | 7.41%   |
| 72     | 1        | 3.7%    |
| 34     | 1        | 3.7%    |
| 22     | 1        | 3.7%    |
| 20     | 1        | 3.7%    |
| 17     | 1        | 3.7%    |
| 15     | 1        | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 36%     |
| 401-500     | 8        | 32%     |
| 1501-2000   | 3        | 12%     |
| 301-350     | 2        | 8%      |
| 701-800     | 1        | 4%      |
| 601-700     | 1        | 4%      |
| 351-400     | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 19       | 76%     |
| 5/4   | 2        | 8%      |
| 16/10 | 2        | 8%      |
| 4/3   | 1        | 4%      |
| 21/9  | 1        | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 34.62%  |
| 301-350        | 7        | 26.92%  |
| More than 1000 | 3        | 11.54%  |
| 151-200        | 3        | 11.54%  |
| 141-150        | 2        | 7.69%   |
| 351-500        | 1        | 3.85%   |
| 101-110        | 1        | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 13       | 56.52%  |
| 101-120 | 8        | 34.78%  |
| 1-50    | 1        | 4.35%   |
| 121-160 | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 76.19%  |
| 2     | 5        | 23.81%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 13       | 40.63%  |
| Realtek Semiconductor    | 11       | 34.38%  |
| TP-Link                  | 2        | 6.25%   |
| Ralink Technology        | 2        | 6.25%   |
| U-Blox                   | 1        | 3.13%   |
| Qualcomm Atheros         | 1        | 3.13%   |
| NetGear                  | 1        | 3.13%   |
| Marvell Technology Group | 1        | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 6        | 17.65%  |
| Realtek RTL8125 2.5GbE Controller                                                             | 2        | 5.88%   |
| Intel Ethernet Connection I217-LM                                                             | 2        | 5.88%   |
| Intel Ethernet Connection (11) I219-V                                                         | 2        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2        | 5.88%   |
| U-Blox [u-blox 8]                                                                             | 1        | 2.94%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 1        | 2.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 2.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 2.94%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                               | 1        | 2.94%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 2.94%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 2.94%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 2.94%   |
| NetGear A6210                                                                                 | 1        | 2.94%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 2.94%   |
| Intel Wireless 8260                                                                           | 1        | 2.94%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 2.94%   |
| Intel I211 Gigabit Network Connection                                                         | 1        | 2.94%   |
| Intel Ethernet Connection (7) I219-V                                                          | 1        | 2.94%   |
| Intel Ethernet Connection (2) I219-V                                                          | 1        | 2.94%   |
| Intel Ethernet Connection (2) I218-V                                                          | 1        | 2.94%   |
| Intel Ethernet Connection (14) I219-V                                                         | 1        | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 2.94%   |
| Intel 82562EZ 10/100 Ethernet Controller                                                      | 1        | 2.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 27.27%  |
| TP-Link               | 2        | 18.18%  |
| Realtek Semiconductor | 2        | 18.18%  |
| Ralink Technology     | 2        | 18.18%  |
| Qualcomm Atheros      | 1        | 9.09%   |
| NetGear               | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| TP-Link TL-WN821N Version 5 RTL8192EU                                                         | 1        | 9.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 1        | 9.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 9.09%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 9.09%   |
| Ralink RT5372 Wireless Adapter                                                                | 1        | 9.09%   |
| Ralink MT7601U Wireless Adapter                                                               | 1        | 9.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1        | 9.09%   |
| NetGear A6210                                                                                 | 1        | 9.09%   |
| Intel Wireless 8260                                                                           | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                                                           | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 12       | 54.55%  |
| Realtek Semiconductor    | 9        | 40.91%  |
| Marvell Technology Group | 1        | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 27.27%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 9.09%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 9.09%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 9.09%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 4.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 4.55%   |
| Intel I211 Gigabit Network Connection                             | 1        | 4.55%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4.55%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 4.55%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4.55%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 4.55%   |
| Intel 82562EZ 10/100 Ethernet Controller                          | 1        | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 65.63%  |
| WiFi     | 10       | 31.25%  |
| Modem    | 1        | 3.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 66.67%  |
| WiFi     | 7        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 80.95%  |
| 2     | 3        | 14.29%  |
| 3     | 1        | 4.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 95.45%  |
| Yes  | 1        | 4.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 60%     |
| Realtek Semiconductor   | 1        | 20%     |
| Cambridge Silicon Radio | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Radio                             | 1        | 20%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 20%     |
| Intel Bluetooth wireless interface                  | 1        | 20%     |
| Intel AX200 Bluetooth                               | 1        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 14       | 35.9%   |
| Nvidia              | 12       | 30.77%  |
| AMD                 | 7        | 17.95%  |
| Focusrite-Novation  | 2        | 5.13%   |
| Texas Instruments   | 1        | 2.56%   |
| Kingston Technology | 1        | 2.56%   |
| JMTek               | 1        | 2.56%   |
| Creative Labs       | 1        | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 3        | 6.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 2        | 4.65%   |
| Nvidia GK107 HDMI Audio Controller                                  | 2        | 4.65%   |
| Intel Tiger Lake-H HD Audio Controller                              | 2        | 4.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 2        | 4.65%   |
| AMD Starship/Matisse HD Audio Controller                            | 2        | 4.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 2        | 4.65%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]        | 2        | 4.65%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                   | 1        | 2.33%   |
| Nvidia TU116 High Definition Audio Controller                       | 1        | 2.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1        | 2.33%   |
| Nvidia GT216 HDMI Audio Controller                                  | 1        | 2.33%   |
| Nvidia GP107GL High Definition Audio Controller                     | 1        | 2.33%   |
| Nvidia GP106 High Definition Audio Controller                       | 1        | 2.33%   |
| Nvidia GP104 High Definition Audio Controller                       | 1        | 2.33%   |
| Nvidia GM204 High Definition Audio Controller                       | 1        | 2.33%   |
| Nvidia GF119 HDMI Audio Controller                                  | 1        | 2.33%   |
| Kingston Technology HyperX 7.1 Audio                                | 1        | 2.33%   |
| JMTek Widget C                                                      | 1        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1        | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 1        | 2.33%   |
| Intel Comet Lake PCH cAVS                                           | 1        | 2.33%   |
| Intel Cannon Lake PCH cAVS                                          | 1        | 2.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                   | 1        | 2.33%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                | 1        | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1        | 2.33%   |
| Focusrite-Novation Scarlett Solo USB                                | 1        | 2.33%   |
| Focusrite-Novation Scarlett 2i4 USB                                 | 1        | 2.33%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]          | 1        | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1        | 2.33%   |
| AMD Navi 10 HDMI Audio                                              | 1        | 2.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                 | 1        | 2.33%   |
| AMD FCH Azalia Controller                                           | 1        | 2.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1        | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 6        | 24%     |
| Unknown                      | 4        | 16%     |
| SK Hynix                     | 3        | 12%     |
| Samsung Electronics          | 2        | 8%      |
| Kingston                     | 2        | 8%      |
| G.Skill                      | 2        | 8%      |
| Crucial                      | 2        | 8%      |
| PNY                          | 1        | 4%      |
| Patriot Memory (PDP Systems) | 1        | 4%      |
| Nanya Technology             | 1        | 4%      |
| Micron Technology            | 1        | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s              | 2        | 7.14%   |
| Unknown RAM Module 8192MB DIMM DDR4 2133MT/s                         | 1        | 3.57%   |
| Unknown RAM Module 512MB DIMM SDRAM                                  | 1        | 3.57%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                           | 1        | 3.57%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                 | 1        | 3.57%   |
| Unknown RAM Module 1024MB DIMM DDR                                   | 1        | 3.57%   |
| SK Hynix RAM HMT351U7EFR8C-PB 4096MB DIMM DDR3 1600MT/s              | 1        | 3.57%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s                 | 1        | 3.57%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s             | 1        | 3.57%   |
| Samsung RAM M391B5273DH0-YK0 4GB DIMM DDR3 1600MT/s                  | 1        | 3.57%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s                 | 1        | 3.57%   |
| Patriot Memory (PDP Systems) RAM PSD48G320081 8GB DIMM DDR4 3200MT/s | 1        | 3.57%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4096MB DIMM DDR3 1600MT/s                | 1        | 3.57%   |
| Micron RAM 16JTF51264AZ-1G6M1 4GB DIMM DDR3 1600MT/s                 | 1        | 3.57%   |
| Kingston RAM KHX2133C13D4/8GX 8192MB DIMM DDR4 2133MT/s              | 1        | 3.57%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1600MT/s                | 1        | 3.57%   |
| G.Skill RAM F4-3000C15-8GTZR 8192MB DIMM DDR4 3000MT/s               | 1        | 3.57%   |
| G.Skill RAM F3-2400C10-8G 8192MB DIMM DDR3 1333MT/s                  | 1        | 3.57%   |
| Crucial RAM CT8G4DFS824A.M8FE 8192MB DIMM DDR4 2933MT/s              | 1        | 3.57%   |
| Crucial RAM CT51264BA160B.C16F 4096MB DIMM DDR3 1600MT/s             | 1        | 3.57%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s                | 1        | 3.57%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s                | 1        | 3.57%   |
| Corsair RAM CMK8GX4M2A2133C13 4GB DIMM DDR4 2933MT/s                 | 1        | 3.57%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s               | 1        | 3.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                | 1        | 3.57%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s                | 1        | 3.57%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s                | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 10       | 47.62%  |
| DDR3  | 8        | 38.1%   |
| DDR   | 2        | 9.52%   |
| SDRAM | 1        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 95.24%  |
| SODIMM | 1        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 11       | 47.83%  |
| 4096  | 6        | 26.09%  |
| 16384 | 2        | 8.7%    |
| 1024  | 2        | 8.7%    |
| 2048  | 1        | 4.35%   |
| 512   | 1        | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 25%     |
| 3200    | 2        | 8.33%   |
| 3000    | 2        | 8.33%   |
| 2933    | 2        | 8.33%   |
| 2133    | 2        | 8.33%   |
| 1800    | 2        | 8.33%   |
| Unknown | 2        | 8.33%   |
| 3600    | 1        | 4.17%   |
| 3466    | 1        | 4.17%   |
| 3266    | 1        | 4.17%   |
| 3100    | 1        | 4.17%   |
| 1333    | 1        | 4.17%   |
| 667     | 1        | 4.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Lexmark International | 1        | 50%     |
| Brother Industries    | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Lexmark International CS417dn | 1        | 50%     |
| Brother DCP-L2540DW           | 1        | 50%     |

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


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Sunplus Technology | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Sunplus SPCA1527A/SPCA1528 SD card camera (webcam mode) | 1        | 100%    |

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
| 0     | 20       | 95.24%  |
| 1     | 1        | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 1        | 100%    |

