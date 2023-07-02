RHEL 9 - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for RHEL 9.

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

Total: 25

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI        | Z270-A PRO                  | [0d8b3d7c32](https://linux-hardware.org/?probe=0d8b3d7c32) | Jun 20, 2023 |
| Dell       | 07T4MC A02                  | [ad310dd147](https://linux-hardware.org/?probe=ad310dd147) | Jun 09, 2023 |
| Dell       | 0HHV7N A00                  | [a3a157f327](https://linux-hardware.org/?probe=a3a157f327) | May 21, 2023 |
| MSI        | MAG X570S TOMAHAWK MAX W... | [2afc4ee693](https://linux-hardware.org/?probe=2afc4ee693) | May 18, 2023 |
| ASUSTek    | TUF Gaming X570-PLUS        | [b1ea93c5fa](https://linux-hardware.org/?probe=b1ea93c5fa) | May 09, 2023 |
| Gigabyte   | B550M AORUS PRO-P           | [18c5e3c7c3](https://linux-hardware.org/?probe=18c5e3c7c3) | Apr 10, 2023 |
| MSI        | B450M MORTAR MAX            | [0077b88576](https://linux-hardware.org/?probe=0077b88576) | Apr 06, 2023 |
| Gigabyte   | X670E AORUS MASTER          | [68731ac4ec](https://linux-hardware.org/?probe=68731ac4ec) | Mar 31, 2023 |
| ASUSTek    | PRIME Z690-P WIFI           | [898059efa5](https://linux-hardware.org/?probe=898059efa5) | Mar 28, 2023 |
| MSI        | B450M MORTAR MAX            | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| ASUSTek    | PRIME Z690-P WIFI           | [1821e3657a](https://linux-hardware.org/?probe=1821e3657a) | Mar 26, 2023 |
| MSI        | B450M MORTAR MAX            | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| MSI        | B450M MORTAR MAX            | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| Gigabyte   | H510M H                     | [861b7c5aa7](https://linux-hardware.org/?probe=861b7c5aa7) | Feb 02, 2023 |
| ASUSTek    | PRIME Z590-A                | [f328fab9f1](https://linux-hardware.org/?probe=f328fab9f1) | Jan 27, 2023 |
| Hardkernel | ODROID-H3                   | [98f5768c61](https://linux-hardware.org/?probe=98f5768c61) | Jan 22, 2023 |
| Unknown    | Unknown                     | [9d66e8f05d](https://linux-hardware.org/?probe=9d66e8f05d) | Dec 25, 2022 |
| MSI        | B550M PRO-VDH WIFI          | [af5361313b](https://linux-hardware.org/?probe=af5361313b) | Nov 17, 2022 |
| MSI        | B550M PRO-VDH WIFI          | [2d830dc96d](https://linux-hardware.org/?probe=2d830dc96d) | Nov 11, 2022 |
| Acer       | Aspire XC-330               | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Unknown    | Unknown                     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Intel      | H81                         | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Unknown    | Unknown                     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown    | Unknown                     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| ASRock     | Z370 Professional Gaming... | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64  | 5        | 25%     |
| 5.14.0-70.17.1.el9_0.x86_64  | 3        | 15%     |
| 5.14.0-284.11.1.el9_2.x86_64 | 3        | 15%     |
| 5.14.0-162.22.2.el9_1.x86_64 | 3        | 15%     |
| 5.14.0-70.22.1.el9_0.x86_64  | 2        | 10%     |
| 5.14.0-162.12.1.el9_1.x86_64 | 2        | 10%     |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 5%      |
| 5.14.0-162.23.1.el9_1.x86_64 | 1        | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 19       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 19       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 19       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 17       | 89.47%  |
| GNOME Classic | 1        | 5.26%   |
| Unknown       | 1        | 5.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 12       | 63.16%  |
| X11     | 6        | 31.58%  |
| Tty     | 1        | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 52.63%  |
| GDM     | 8        | 42.11%  |
| SDDM    | 1        | 5.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 10       | 52.63%  |
| en_IN | 2        | 10.53%  |
| en_GB | 2        | 10.53%  |
| ru_RU | 1        | 5.26%   |
| ja_JP | 1        | 5.26%   |
| es_ES | 1        | 5.26%   |
| en_NZ | 1        | 5.26%   |
| en_CA | 1        | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 16       | 84.21%  |
| BIOS | 3        | 15.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 18       | 94.74%  |
| Ext4 | 1        | 5.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 11       | 57.89%  |
| Unknown | 8        | 42.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 68.42%  |
| Yes       | 6        | 31.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 84.21%  |
| Yes       | 3        | 15.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 4        | 21.05%  |
| Gigabyte Technology | 3        | 15.79%  |
| ASUSTek Computer    | 3        | 15.79%  |
| Unknown             | 3        | 15.79%  |
| Dell                | 2        | 10.53%  |
| Intel               | 1        | 5.26%   |
| Hardkernel          | 1        | 5.26%   |
| ASRock              | 1        | 5.26%   |
| Acer                | 1        | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 3        | 15.79%  |
| MSI MS-7D54                        | 1        | 5.26%   |
| MSI MS-7C95                        | 1        | 5.26%   |
| MSI MS-7B89                        | 1        | 5.26%   |
| MSI MS-7A71                        | 1        | 5.26%   |
| Intel H81                          | 1        | 5.26%   |
| Hardkernel ODROID-H3               | 1        | 5.26%   |
| Gigabyte X670E AORUS MASTER        | 1        | 5.26%   |
| Gigabyte H510M H                   | 1        | 5.26%   |
| Gigabyte B550M AORUS PRO-P         | 1        | 5.26%   |
| Dell Precision Tower 5810          | 1        | 5.26%   |
| Dell PowerEdge T30                 | 1        | 5.26%   |
| ASUS TUF Gaming X570-PLUS          | 1        | 5.26%   |
| ASUS PRIME Z690-P WIFI             | 1        | 5.26%   |
| ASUS PRIME Z590-A                  | 1        | 5.26%   |
| ASRock Z370 Professional Gaming i7 | 1        | 5.26%   |
| Acer Aspire XC-330                 | 1        | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 3        | 15.79%  |
| ASUS PRIME           | 2        | 10.53%  |
| MSI MS-7D54          | 1        | 5.26%   |
| MSI MS-7C95          | 1        | 5.26%   |
| MSI MS-7B89          | 1        | 5.26%   |
| MSI MS-7A71          | 1        | 5.26%   |
| Intel H81            | 1        | 5.26%   |
| Hardkernel ODROID-H3 | 1        | 5.26%   |
| Gigabyte X670E       | 1        | 5.26%   |
| Gigabyte H510M       | 1        | 5.26%   |
| Gigabyte B550M       | 1        | 5.26%   |
| Dell Precision       | 1        | 5.26%   |
| Dell PowerEdge       | 1        | 5.26%   |
| ASUS TUF             | 1        | 5.26%   |
| ASRock Z370          | 1        | 5.26%   |
| Acer Aspire          | 1        | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 4        | 21.05%  |
| 2022 | 3        | 15.79%  |
| 2019 | 3        | 15.79%  |
| 2017 | 3        | 15.79%  |
| 2020 | 2        | 10.53%  |
| 2016 | 2        | 10.53%  |
| 2023 | 1        | 5.26%   |
| 2018 | 1        | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 19       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 18       | 94.74%  |
| Enabled  | 1        | 5.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 6        | 31.58%  |
| 8.01-16.0   | 6        | 31.58%  |
| 4.01-8.0    | 3        | 15.79%  |
| 64.01-256.0 | 2        | 10.53%  |
| 3.01-4.0    | 1        | 5.26%   |
| 24.01-32.0  | 1        | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 7        | 35%     |
| 3.01-4.0  | 6        | 30%     |
| 4.01-8.0  | 3        | 15%     |
| 1.01-2.0  | 3        | 15%     |
| 8.01-16.0 | 1        | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 6        | 31.58%  |
| 1      | 5        | 26.32%  |
| 5      | 3        | 15.79%  |
| 3      | 3        | 15.79%  |
| 14     | 1        | 5.26%   |
| 4      | 1        | 5.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 78.95%  |
| Yes       | 4        | 21.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 11       | 57.89%  |
| No        | 8        | 42.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 52.63%  |
| No        | 9        | 47.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 5        | 26.32%  |
| India       | 4        | 21.05%  |
| Canada      | 3        | 15.79%  |
| UK          | 2        | 10.53%  |
| Spain       | 1        | 5.26%   |
| Russia      | 1        | 5.26%   |
| New Zealand | 1        | 5.26%   |
| Japan       | 1        | 5.26%   |
| Germany     | 1        | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Wildomar     | 1        | 5.26%   |
| Wellington   | 1        | 5.26%   |
| Valencia     | 1        | 5.26%   |
| Tokyo        | 1        | 5.26%   |
| Sutton       | 1        | 5.26%   |
| Stavropol    | 1        | 5.26%   |
| Sainte-Marie | 1        | 5.26%   |
| Pforzheim    | 1        | 5.26%   |
| Oldham       | 1        | 5.26%   |
| Lansing      | 1        | 5.26%   |
| Kochi        | 1        | 5.26%   |
| Ghaziabad    | 1        | 5.26%   |
| Ernakulam    | 1        | 5.26%   |
| East Peoria  | 1        | 5.26%   |
| Cherry Hill  | 1        | 5.26%   |
| Canton       | 1        | 5.26%   |
| Bengaluru    | 1        | 5.26%   |
| Beeton       | 1        | 5.26%   |
| Alliston     | 1        | 5.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 8        | 15     | 17.78%  |
| Seagate                   | 7        | 10     | 15.56%  |
| Samsung Electronics       | 7        | 10     | 15.56%  |
| SanDisk                   | 3        | 3      | 6.67%   |
| Phison                    | 2        | 2      | 4.44%   |
| Crucial                   | 2        | 3      | 4.44%   |
| China                     | 2        | 2      | 4.44%   |
| XUM                       | 1        | 1      | 2.22%   |
| Unknown                   | 1        | 1      | 2.22%   |
| Toshiba                   | 1        | 1      | 2.22%   |
| SABRENT                   | 1        | 1      | 2.22%   |
| PNY                       | 1        | 1      | 2.22%   |
| Micron/Crucial Technology | 1        | 2      | 2.22%   |
| Kingston                  | 1        | 1      | 2.22%   |
| KingSpec                  | 1        | 1      | 2.22%   |
| Intel                     | 1        | 1      | 2.22%   |
| Hitachi                   | 1        | 1      | 2.22%   |
| HGST                      | 1        | 1      | 2.22%   |
| Gigabyte Technology       | 1        | 1      | 2.22%   |
| Fantom                    | 1        | 1      | 2.22%   |
| ADATA Technology          | 1        | 1      | 2.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| XUM HX256GSSDSATA3 256GB                            | 1        | 1.82%   |
| WDC WDBA3V5000ANC-WRSN 500GB                        | 1        | 1.82%   |
| WDC WD80EFAX-68KNBN0 8TB                            | 1        | 1.82%   |
| WDC WD5000AVCS-632DY1 500GB                         | 1        | 1.82%   |
| WDC WD50 00LPVX-22V0TT0 500GB                       | 1        | 1.82%   |
| WDC WD40EFRX-68N32N0 4TB                            | 1        | 1.82%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1        | 1.82%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 1        | 1.82%   |
| WDC WD141KFGX-68FH9N0 14TB                          | 1        | 1.82%   |
| WDC WD140EFGX-68B0GN0 14TB                          | 1        | 1.82%   |
| WDC WD10SPSX-00A6WT0 1TB                            | 1        | 1.82%   |
| WDC WD10JPLX-00MBPT0 1TB                            | 1        | 1.82%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1        | 1.82%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 1        | 1.82%   |
| WDC WD100EFAX-68LHPN0 10TB                          | 1        | 1.82%   |
| Unknown SD/MMC/MS PRO 250GB                         | 1        | 1.82%   |
| Toshiba MK3261GSYN 320GB                            | 1        | 1.82%   |
| Seagate ST9250315AS 250GB                           | 1        | 1.82%   |
| Seagate ST6000DM003-2CY186 6TB                      | 1        | 1.82%   |
| Seagate ST4000DM000-2AE166 4TB                      | 1        | 1.82%   |
| Seagate ST3500312CS 500GB                           | 1        | 1.82%   |
| Seagate ST31000528AS 1TB                            | 1        | 1.82%   |
| Seagate ST3000VN000-1HJ166 3TB                      | 1        | 1.82%   |
| Seagate ST18000NM000J-2TV103 18TB                   | 1        | 1.82%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1        | 1.82%   |
| Sandisk WD Blue SN570 500GB                         | 1        | 1.82%   |
| SanDisk SSD PLUS 480GB                              | 1        | 1.82%   |
| SanDisk SDSSDHII480G 480GB                          | 1        | 1.82%   |
| Samsung SSD PM851a 2.5 7mm 1024GB                   | 1        | 1.82%   |
| Samsung SSD 970 EVO Plus 500GB                      | 1        | 1.82%   |
| Samsung SSD 970 EVO Plus 1TB                        | 1        | 1.82%   |
| Samsung SSD 870 EVO 500GB                           | 1        | 1.82%   |
| Samsung SSD 860 EVO 4TB                             | 1        | 1.82%   |
| Samsung SSD 850 EVO 250GB                           | 1        | 1.82%   |
| Samsung SSD 840 EVO 120GB                           | 1        | 1.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 1        | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 1        | 1.82%   |
| SABRENT Disk 1TB                                    | 1        | 1.82%   |
| PNY CS900 1TB SSD                                   | 1        | 1.82%   |
| Phison Sabrent Rocket Q4 2TB                        | 1        | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 14     | 36.84%  |
| Seagate | 7        | 10     | 36.84%  |
| Unknown | 1        | 1      | 5.26%   |
| Toshiba | 1        | 1      | 5.26%   |
| Hitachi | 1        | 1      | 5.26%   |
| HGST    | 1        | 1      | 5.26%   |
| Fantom  | 1        | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 26.67%  |
| SanDisk             | 2        | 2      | 13.33%  |
| Crucial             | 2        | 2      | 13.33%  |
| China               | 2        | 2      | 13.33%  |
| XUM                 | 1        | 1      | 6.67%   |
| PNY                 | 1        | 1      | 6.67%   |
| Kingston            | 1        | 1      | 6.67%   |
| KingSpec            | 1        | 1      | 6.67%   |
| Gigabyte Technology | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 13       | 16     | 35.14%  |
| NVMe | 12       | 15     | 32.43%  |
| HDD  | 12       | 29     | 32.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 17       | 42     | 53.13%  |
| NVMe | 12       | 14     | 37.5%   |
| SAS  | 3        | 4      | 9.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 18     | 42.86%  |
| 0.51-1.0   | 7        | 9      | 25%     |
| 3.01-4.0   | 2        | 4      | 7.14%   |
| 10.01-20.0 | 2        | 4      | 7.14%   |
| 1.01-2.0   | 2        | 3      | 7.14%   |
| 4.01-10.0  | 2        | 5      | 7.14%   |
| 2.01-3.0   | 1        | 2      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 36.84%  |
| 251-500        | 6        | 31.58%  |
| 501-1000       | 3        | 15.79%  |
| 1001-2000      | 2        | 10.53%  |
| More than 3000 | 1        | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 9        | 47.37%  |
| 21-50          | 4        | 21.05%  |
| 251-500        | 2        | 10.53%  |
| 51-100         | 2        | 10.53%  |
| More than 3000 | 1        | 5.26%   |
| 101-250        | 1        | 5.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD50 00LPVX-22V0TT0 500GB  | 1        | 1      | 33.33%  |
| Seagate ST1000DM010-2EP102 1TB | 1        | 1      | 33.33%  |
| Crucial CT1000BX500SSD1 1TB    | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |
| Crucial | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 50%     |
| HDD  | 1        | 2      | 50%     |

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
| Detected | 10       | 28     | 45.45%  |
| Works    | 10       | 29     | 45.45%  |
| Malfunc  | 2        | 3      | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 13       | 39.39%  |
| AMD                       | 7        | 21.21%  |
| Samsung Electronics       | 4        | 12.12%  |
| SanDisk                   | 2        | 6.06%   |
| Phison Electronics        | 2        | 6.06%   |
| Micron/Crucial Technology | 2        | 6.06%   |
| Broadcom / LSI            | 1        | 3.03%   |
| ASMedia Technology        | 1        | 3.03%   |
| ADATA Technology          | 1        | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 4        | 11.43%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 8.57%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2        | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 5.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 5.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 5.71%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 5.71%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 2.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 2.86%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 2.86%   |
| Phison E12 NVMe Controller                                                     | 1        | 2.86%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1        | 2.86%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 2.86%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1        | 2.86%   |
| Intel SSD 660P Series                                                          | 1        | 2.86%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 2.86%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 2.86%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 2.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.86%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                            | 1        | 2.86%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 2.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.86%   |
| ADATA ADATA XPG GAMMIXS1 1L Media                                              | 1        | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 54.55%  |
| NVMe | 12       | 36.36%  |
| RAID | 2        | 6.06%   |
| SAS  | 1        | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 12       | 63.16%  |
| AMD    | 7        | 36.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor            | 2        | 10.53%  |
| Intel Xeon CPU E5-1607 v4 @ 3.10GHz          | 1        | 5.26%   |
| Intel Xeon CPU E3-1225 v5 @ 3.30GHz          | 1        | 5.26%   |
| Intel Pentium Silver N6005 @ 2.00GHz         | 1        | 5.26%   |
| Intel Core i7-8700K CPU @ 3.70GHz            | 1        | 5.26%   |
| Intel Core i7-7700K CPU @ 4.20GHz            | 1        | 5.26%   |
| Intel Core i5-3570 CPU @ 3.40GHz             | 1        | 5.26%   |
| Intel Core i5-3470S CPU @ 2.90GHz            | 1        | 5.26%   |
| Intel Core i3-4130 CPU @ 3.40GHz             | 1        | 5.26%   |
| Intel Celeron N5105 @ 2.00GHz                | 1        | 5.26%   |
| Intel 13th Gen Core i5-13600K                | 1        | 5.26%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz      | 1        | 5.26%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz      | 1        | 5.26%   |
| AMD Ryzen 9 7900X 12-Core Processor          | 1        | 5.26%   |
| AMD Ryzen 9 5900X 12-Core Processor          | 1        | 5.26%   |
| AMD Ryzen 9 3900X 12-Core Processor          | 1        | 5.26%   |
| AMD Ryzen 5 5600G with Radeon Graphics       | 1        | 5.26%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G | 1        | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Other                | 3        | 15.79%  |
| AMD Ryzen 9          | 3        | 15.79%  |
| AMD Ryzen 5          | 3        | 15.79%  |
| Intel Xeon           | 2        | 10.53%  |
| Intel Core i7        | 2        | 10.53%  |
| Intel Core i5        | 2        | 10.53%  |
| Intel Pentium Silver | 1        | 5.26%   |
| Intel Core i3        | 1        | 5.26%   |
| Intel Celeron        | 1        | 5.26%   |
| AMD A4               | 1        | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 36.84%  |
| 6      | 4        | 21.05%  |
| 12     | 3        | 15.79%  |
| 8      | 2        | 10.53%  |
| 2      | 2        | 10.53%  |
| 14     | 1        | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 63.16%  |
| 1      | 7        | 36.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 19       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 3        | 15.79%  |
| 0xa0671    | 2        | 10.53%  |
| 0x906c0    | 2        | 10.53%  |
| 0x306a9    | 2        | 10.53%  |
| 0xb0671    | 1        | 5.26%   |
| 0x906ea    | 1        | 5.26%   |
| 0x906e9    | 1        | 5.26%   |
| 0x506e3    | 1        | 5.26%   |
| 0x406f1    | 1        | 5.26%   |
| 0x306c3    | 1        | 5.26%   |
| 0x0a601203 | 1        | 5.26%   |
| 0x0a50000c | 1        | 5.26%   |
| 0x0a20120a | 1        | 5.26%   |
| 0x06006705 | 1        | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 3        | 15.79%  |
| Zen 3            | 2        | 10.53%  |
| Tremont          | 2        | 10.53%  |
| KabyLake         | 2        | 10.53%  |
| IvyBridge        | 2        | 10.53%  |
| Icelake          | 2        | 10.53%  |
| Skylake          | 1        | 5.26%   |
| Haswell          | 1        | 5.26%   |
| Excavator        | 1        | 5.26%   |
| Broadwell        | 1        | 5.26%   |
| Alderlake Hybrid | 1        | 5.26%   |
| Unknown          | 1        | 5.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 7        | 33.33%  |
| Intel  | 7        | 33.33%  |
| AMD    | 7        | 33.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel JasperLake [UHD Graphics]                                           | 2        | 8.7%    |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                            | 2        | 8.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 2        | 8.7%    |
| Nvidia TU117GL [T400 4GB]                                                 | 1        | 4.35%   |
| Nvidia GT218 [GeForce G210]                                               | 1        | 4.35%   |
| Nvidia GP104 [GeForce GTX 1070]                                           | 1        | 4.35%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                        | 1        | 4.35%   |
| Nvidia GM206GL [Quadro M2000]                                             | 1        | 4.35%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 4.35%   |
| Nvidia GA106 [Geforce RTX 3050]                                           | 1        | 4.35%   |
| Nvidia G92 [GeForce 9800 GT]                                              | 1        | 4.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 4.35%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 1        | 4.35%   |
| Intel HD Graphics P530                                                    | 1        | 4.35%   |
| Intel HD Graphics 630                                                     | 1        | 4.35%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 4.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1        | 4.35%   |
| AMD Raphael                                                               | 1        | 4.35%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 1        | 4.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 1        | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 6        | 31.58%  |
| 1 x Intel   | 5        | 26.32%  |
| 1 x AMD     | 5        | 26.32%  |
| 2 x Nvidia  | 1        | 5.26%   |
| 2 x AMD     | 1        | 5.26%   |
| Intel + AMD | 1        | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 16       | 84.21%  |
| Proprietary | 2        | 10.53%  |
| Unknown     | 1        | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 6        | 31.58%  |
| Unknown    | 5        | 26.32%  |
| 3.01-4.0   | 3        | 15.79%  |
| 0.01-0.5   | 2        | 10.53%  |
| 1.01-2.0   | 1        | 5.26%   |
| 8.01-16.0  | 1        | 5.26%   |
| 0.51-1.0   | 1        | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 4        | 21.05%  |
| Samsung Electronics | 3        | 15.79%  |
| Acer                | 2        | 10.53%  |
| STD                 | 1        | 5.26%   |
| Sony                | 1        | 5.26%   |
| Philips             | 1        | 5.26%   |
| Panasonic           | 1        | 5.26%   |
| OUT                 | 1        | 5.26%   |
| Haier               | 1        | 5.26%   |
| Goldstar            | 1        | 5.26%   |
| Deco Gear           | 1        | 5.26%   |
| BenQ                | 1        | 5.26%   |
| AOC                 | 1        | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                     | 2        | 9.52%   |
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                          | 1        | 4.76%   |
| Sony TV SNYD703 1360x768                                               | 1        | 4.76%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1        | 4.76%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1        | 4.76%   |
| Samsung Electronics SMS23A550H SAM07CA 1920x1080 509x286mm 23.0-inch   | 1        | 4.76%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1        | 4.76%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1        | 4.76%   |
| Philips PHL 322E1 PHLC20F 1920x1080 700x390mm 31.5-inch                | 1        | 4.76%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 1        | 4.76%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1        | 4.76%   |
| Haier LED39C800F HAI17FC 1920x1080 1150x650mm 52.0-inch                | 1        | 4.76%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                  | 1        | 4.76%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                     | 1        | 4.76%   |
| Dell S2318HN/NX DELD0BF 1920x1080 509x286mm 23.0-inch                  | 1        | 4.76%   |
| Dell S2009W DELA045 1600x900 443x249mm 20.0-inch                       | 1        | 4.76%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                      | 1        | 4.76%   |
| Deco Gear DGVIEW220 DGVFFFF 3440x1440 819x346mm 35.0-inch              | 1        | 4.76%   |
| BenQ GW2255 BNQ78CD 1920x1080 477x268mm 21.5-inch                      | 1        | 4.76%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 1        | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 50%     |
| 3840x2160 (4K)     | 3        | 15%     |
| 1680x1050 (WSXGA+) | 2        | 10%     |
| 3440x1440          | 1        | 5%      |
| 2560x1440 (QHD)    | 1        | 5%      |
| 1600x900 (HD+)     | 1        | 5%      |
| 1280x768           | 1        | 5%      |
| 1280x1024 (SXGA)   | 1        | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 4        | 20%     |
| 23     | 3        | 15%     |
| 31     | 2        | 10%     |
| 27     | 2        | 10%     |
| 84     | 1        | 5%      |
| 72     | 1        | 5%      |
| 64     | 1        | 5%      |
| 52     | 1        | 5%      |
| 35     | 1        | 5%      |
| 33     | 1        | 5%      |
| 20     | 1        | 5%      |
| 19     | 1        | 5%      |
| 16     | 1        | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 5        | 25%     |
| 401-500     | 5        | 25%     |
| 601-700     | 2        | 10%     |
| 1501-2000   | 2        | 10%     |
| 1001-1500   | 2        | 10%     |
| 801-900     | 1        | 5%      |
| 701-800     | 1        | 5%      |
| 351-400     | 1        | 5%      |
| 301-350     | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 14       | 77.78%  |
| 5/4   | 1        | 5.56%   |
| 4/3   | 1        | 5.56%   |
| 21/9  | 1        | 5.56%   |
| 16/10 | 1        | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 26.32%  |
| More than 1000 | 4        | 21.05%  |
| 351-500        | 4        | 21.05%  |
| 151-200        | 3        | 15.79%  |
| 301-350        | 2        | 10.53%  |
| 131-140        | 1        | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 12       | 66.67%  |
| 101-120 | 4        | 22.22%  |
| 1-50    | 2        | 11.11%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 73.68%  |
| 2     | 2        | 10.53%  |
| 0     | 2        | 10.53%  |
| 3     | 1        | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 50%     |
| Intel                 | 11       | 42.31%  |
| ASUSTek Computer      | 1        | 3.85%   |
| Aquantia              | 1        | 3.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 17.14%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 11.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 8.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3        | 8.57%   |
| Intel Ethernet Controller I225-V                                  | 3        | 8.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 8.57%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 5.71%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 2.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 2.86%   |
| Realtek 802.11n WLAN Adapter                                      | 1        | 2.86%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1        | 2.86%   |
| Intel I211 Gigabit Network Connection                             | 1        | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 2.86%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]               | 1        | 2.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 66.67%  |
| Realtek Semiconductor | 3        | 25%     |
| ASUSTek Computer      | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz              | 3        | 25%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]    | 3        | 25%     |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter          | 1        | 8.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter | 1        | 8.33%   |
| Realtek 802.11n WLAN Adapter                        | 1        | 8.33%   |
| Intel Wi-Fi 6 AX201 160MHz                          | 1        | 8.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                    | 1        | 8.33%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU] | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 61.9%   |
| Intel                 | 7        | 33.33%  |
| Aquantia              | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 26.09%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 17.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 13.04%  |
| Intel Ethernet Controller I225-V                                  | 3        | 13.04%  |
| Intel 82574L Gigabit Network Connection                           | 2        | 8.7%    |
| Intel I211 Gigabit Network Connection                             | 1        | 4.35%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 4.35%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 4.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 4.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 63.33%  |
| WiFi     | 11       | 36.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 80.95%  |
| WiFi     | 4        | 19.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 47.37%  |
| 2     | 7        | 36.84%  |
| 4     | 2        | 10.53%  |
| 3     | 1        | 5.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 68.42%  |
| Yes  | 6        | 31.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 8        | 72.73%  |
| Cambridge Silicon Radio    | 2        | 18.18%  |
| Integrated System Solution | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 27.27%  |
| Intel AX210 Bluetooth                                 | 3        | 27.27%  |
| Intel AX201 Bluetooth                                 | 2        | 18.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 18.18%  |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 12       | 38.71%  |
| AMD                                          | 8        | 25.81%  |
| Nvidia                                       | 6        | 19.35%  |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 3.23%   |
| Texas Instruments                            | 1        | 3.23%   |
| Micro Star International                     | 1        | 3.23%   |
| Logitech                                     | 1        | 3.23%   |
| Blue Microphones                             | 1        | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 7.69%   |
| Nvidia GP104 High Definition Audio Controller                              | 2        | 5.13%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 5.13%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 5.13%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 5.13%   |
| AMD Navi 10 HDMI Audio                                                     | 2        | 5.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 5.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 5.13%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1        | 2.56%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 2.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 2.56%   |
| Nvidia High Definition Audio Controller                                    | 1        | 2.56%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 2.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.56%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 2.56%   |
| Micro Star International USB Audio                                         | 1        | 2.56%   |
| Logitech Headset H340                                                      | 1        | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.56%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 2.56%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 2.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.56%   |
| Blue Microphones Yeti Nano                                                 | 1        | 2.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2.56%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1        | 2.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 2.56%   |
| AMD High Definition Audio Controller                                       | 1        | 2.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 2.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 3        | 27.27%  |
| SK hynix            | 2        | 18.18%  |
| Unknown             | 1        | 9.09%   |
| Team                | 1        | 9.09%   |
| Samsung Electronics | 1        | 9.09%   |
| Kingston            | 1        | 9.09%   |
| Crucial             | 1        | 9.09%   |
| Corsair             | 1        | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 1        | 9.09%   |
| Team RAM TEAMGROUP-ED4-2400 16GB DIMM DDR4 2400MT/s      | 1        | 9.09%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s    | 1        | 9.09%   |
| SK hynix RAM HMA81GU7AFR8N-UH 8GB DIMM DDR4 2400MT/s     | 1        | 9.09%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s      | 1        | 9.09%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 1        | 9.09%   |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM DDR5 6400MT/s     | 1        | 9.09%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 9.09%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 1        | 9.09%   |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s     | 1        | 9.09%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 1        | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 6        | 60%     |
| DDR3   | 2        | 20%     |
| LPDDR4 | 1        | 10%     |
| DDR5   | 1        | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 8        | 80%     |
| SODIMM       | 1        | 10%     |
| Row Of Chips | 1        | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 5        | 45.45%  |
| 8192  | 5        | 45.45%  |
| 4096  | 1        | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 4        | 40%     |
| 2400  | 2        | 20%     |
| 6400  | 1        | 10%     |
| 2933  | 1        | 10%     |
| 1867  | 1        | 10%     |
| 1333  | 1        | 10%     |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 2        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson XP-4100 Series | 1        | 50%     |
| Seiko Epson WF-3520 Series | 1        | 50%     |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| vivo                  | 1        | 20%     |
| Realtek Semiconductor | 1        | 20%     |
| Microdia              | 1        | 20%     |
| Logitech              | 1        | 20%     |
| IMC Networks          | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| vivo V2023                          | 1        | 20%     |
| Realtek FULL HD 1080P Webcam        | 1        | 20%     |
| Microdia REDRAGON Live Camera Audio | 1        | 20%     |
| Logitech Webcam C250                | 1        | 20%     |
| IMC Networks XHC Camera             | 1        | 20%     |

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
| 0     | 16       | 84.21%  |
| 1     | 2        | 10.53%  |
| 2     | 1        | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 1        | 33.33%  |
| Net/wireless     | 1        | 33.33%  |
| Graphics card    | 1        | 33.33%  |

