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

Total: 20

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.14.0-162.6.1.el9_1.x86_64  | 5        | 33.33%  |
| 5.14.0-70.17.1.el9_0.x86_64  | 3        | 20%     |
| 5.14.0-162.22.2.el9_1.x86_64 | 3        | 20%     |
| 5.14.0-70.22.1.el9_0.x86_64  | 2        | 13.33%  |
| 5.14.0-70.5.1.el9_0.x86_64   | 1        | 6.67%   |
| 5.14.0-162.12.1.el9_1.x86_64 | 1        | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 14       | 100%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 14       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 14       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 12       | 85.71%  |
| GNOME Classic | 1        | 7.14%   |
| Unknown       | 1        | 7.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 9        | 64.29%  |
| X11     | 4        | 28.57%  |
| Tty     | 1        | 7.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 57.14%  |
| GDM     | 5        | 35.71%  |
| SDDM    | 1        | 7.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 8        | 57.14%  |
| en_IN | 2        | 14.29%  |
| en_GB | 2        | 14.29%  |
| ru_RU | 1        | 7.14%   |
| ja_JP | 1        | 7.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 11       | 78.57%  |
| BIOS | 3        | 21.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 13       | 92.86%  |
| Ext4 | 1        | 7.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 8        | 57.14%  |
| Unknown | 6        | 42.86%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 71.43%  |
| Yes       | 4        | 28.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 92.86%  |
| Yes       | 1        | 7.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 3        | 21.43%  |
| Unknown             | 3        | 21.43%  |
| MSI                 | 2        | 14.29%  |
| ASUSTek Computer    | 2        | 14.29%  |
| Intel               | 1        | 7.14%   |
| Hardkernel          | 1        | 7.14%   |
| ASRock              | 1        | 7.14%   |
| Acer                | 1        | 7.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 3        | 21.43%  |
| MSI MS-7C95                        | 1        | 7.14%   |
| MSI MS-7B89                        | 1        | 7.14%   |
| Intel H81                          | 1        | 7.14%   |
| Hardkernel ODROID-H3               | 1        | 7.14%   |
| Gigabyte X670E AORUS MASTER        | 1        | 7.14%   |
| Gigabyte H510M H                   | 1        | 7.14%   |
| Gigabyte B550M AORUS PRO-P         | 1        | 7.14%   |
| ASUS PRIME Z690-P WIFI             | 1        | 7.14%   |
| ASUS PRIME Z590-A                  | 1        | 7.14%   |
| ASRock Z370 Professional Gaming i7 | 1        | 7.14%   |
| Acer Aspire XC-330                 | 1        | 7.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 3        | 21.43%  |
| ASUS PRIME           | 2        | 14.29%  |
| MSI MS-7C95          | 1        | 7.14%   |
| MSI MS-7B89          | 1        | 7.14%   |
| Intel H81            | 1        | 7.14%   |
| Hardkernel ODROID-H3 | 1        | 7.14%   |
| Gigabyte X670E       | 1        | 7.14%   |
| Gigabyte H510M       | 1        | 7.14%   |
| Gigabyte B550M       | 1        | 7.14%   |
| ASRock Z370          | 1        | 7.14%   |
| Acer Aspire          | 1        | 7.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 3        | 21.43%  |
| 2021 | 3        | 21.43%  |
| 2020 | 2        | 14.29%  |
| 2019 | 2        | 14.29%  |
| 2017 | 2        | 14.29%  |
| 2023 | 1        | 7.14%   |
| 2018 | 1        | 7.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 14       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 13       | 92.86%  |
| Enabled  | 1        | 7.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 5        | 35.71%  |
| 4.01-8.0    | 3        | 21.43%  |
| 32.01-64.0  | 3        | 21.43%  |
| 64.01-256.0 | 2        | 14.29%  |
| 3.01-4.0    | 1        | 7.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 2.01-3.0 | 7        | 46.67%  |
| 3.01-4.0 | 3        | 20%     |
| 1.01-2.0 | 3        | 20%     |
| 4.01-8.0 | 2        | 13.33%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 35.71%  |
| 1      | 4        | 28.57%  |
| 5      | 2        | 14.29%  |
| 3      | 2        | 14.29%  |
| 4      | 1        | 7.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 85.71%  |
| Yes       | 2        | 14.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 71.43%  |
| No        | 4        | 28.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 64.29%  |
| No        | 5        | 35.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| India   | 4        | 28.57%  |
| USA     | 3        | 21.43%  |
| UK      | 2        | 14.29%  |
| Canada  | 2        | 14.29%  |
| Russia  | 1        | 7.14%   |
| Japan   | 1        | 7.14%   |
| Germany | 1        | 7.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Sutton       | 1        | 7.14%   |
| Stavropol    | 1        | 7.14%   |
| Sainte-Marie | 1        | 7.14%   |
| Pforzheim    | 1        | 7.14%   |
| Oldham       | 1        | 7.14%   |
| Morton       | 1        | 7.14%   |
| Kochi        | 1        | 7.14%   |
| Ghaziabad    | 1        | 7.14%   |
| Ernakulam    | 1        | 7.14%   |
| Chuorinkan   | 1        | 7.14%   |
| Cherry Hill  | 1        | 7.14%   |
| Canton       | 1        | 7.14%   |
| Bengaluru    | 1        | 7.14%   |
| Beeton       | 1        | 7.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 6        | 8      | 20%     |
| Samsung Electronics       | 5        | 6      | 16.67%  |
| Seagate                   | 4        | 5      | 13.33%  |
| SanDisk                   | 2        | 2      | 6.67%   |
| Phison                    | 2        | 2      | 6.67%   |
| China                     | 2        | 2      | 6.67%   |
| XUM                       | 1        | 1      | 3.33%   |
| Unknown                   | 1        | 1      | 3.33%   |
| PNY                       | 1        | 1      | 3.33%   |
| Micron/Crucial Technology | 1        | 2      | 3.33%   |
| Kingston                  | 1        | 1      | 3.33%   |
| KingSpec                  | 1        | 1      | 3.33%   |
| Hitachi                   | 1        | 1      | 3.33%   |
| Gigabyte Technology       | 1        | 1      | 3.33%   |
| ADATA Technology          | 1        | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| XUM HX256GSSDSATA3 256GB                           | 1        | 3.13%   |
| WDC WDBA3V5000ANC-WRSN 500GB                       | 1        | 3.13%   |
| WDC WD5000AVCS-632DY1 500GB                        | 1        | 3.13%   |
| WDC WD20EZRZ-00Z5HB0 2TB                           | 1        | 3.13%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 1        | 3.13%   |
| WDC WD10SPSX-00A6WT0 1TB                           | 1        | 3.13%   |
| WDC WD10JPLX-00MBPT0 1TB                           | 1        | 3.13%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1        | 3.13%   |
| WDC WD10EZEX-00BBHA0 1TB                           | 1        | 3.13%   |
| Unknown SD/MMC/MS PRO 249GB                        | 1        | 3.13%   |
| Seagate ST9250315AS 250GB                          | 1        | 3.13%   |
| Seagate ST3500312CS 500GB                          | 1        | 3.13%   |
| Seagate ST31000528AS 1TB                           | 1        | 3.13%   |
| Seagate ST18000NM000J-2TV103 18TB                  | 1        | 3.13%   |
| Sandisk WD Blue SN570 500GB                        | 1        | 3.13%   |
| SanDisk SDSSDHII480G 480GB                         | 1        | 3.13%   |
| Samsung SSD 970 EVO Plus 500GB                     | 1        | 3.13%   |
| Samsung SSD 970 EVO Plus 1TB                       | 1        | 3.13%   |
| Samsung SSD 860 EVO 4TB                            | 1        | 3.13%   |
| Samsung SSD 840 EVO 120GB                          | 1        | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 1        | 3.13%   |
| PNY CS900 1TB SSD                                  | 1        | 3.13%   |
| Phison Sabrent Rocket Q4 4TB                       | 1        | 3.13%   |
| Phison NVMe SSD Drive 512GB                        | 1        | 3.13%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 1        | 3.13%   |
| Kingston SA400S37240G 240GB SSD                    | 1        | 3.13%   |
| KingSpec P4-120 120GB SSD                          | 1        | 3.13%   |
| Hitachi HDS721616PLA380 160GB                      | 1        | 3.13%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD               | 1        | 3.13%   |
| China SSD 512GB                                    | 1        | 3.13%   |
| China SSD 256GB                                    | 1        | 3.13%   |
| ADATA XPG GAMMIX S5 1024GB                         | 1        | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 7      | 45.45%  |
| Seagate | 4        | 5      | 36.36%  |
| Unknown | 1        | 1      | 9.09%   |
| Hitachi | 1        | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 20%     |
| China               | 2        | 2      | 20%     |
| XUM                 | 1        | 1      | 10%     |
| SanDisk             | 1        | 1      | 10%     |
| PNY                 | 1        | 1      | 10%     |
| Kingston            | 1        | 1      | 10%     |
| KingSpec            | 1        | 1      | 10%     |
| Gigabyte Technology | 1        | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 9        | 11     | 34.62%  |
| SSD  | 9        | 10     | 34.62%  |
| HDD  | 8        | 14     | 30.77%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 12       | 23     | 54.55%  |
| NVMe | 9        | 11     | 40.91%  |
| SAS  | 1        | 1      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 8        | 12     | 50%     |
| 0.51-1.0   | 5        | 7      | 31.25%  |
| 3.01-4.0   | 1        | 1      | 6.25%   |
| 10.01-20.0 | 1        | 2      | 6.25%   |
| 1.01-2.0   | 1        | 2      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 6        | 42.86%  |
| 251-500    | 4        | 28.57%  |
| 1001-2000  | 2        | 14.29%  |
| 501-1000   | 2        | 14.29%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 8        | 57.14%  |
| 21-50   | 4        | 28.57%  |
| 251-500 | 1        | 7.14%   |
| 51-100  | 1        | 7.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 7        | 23     | 50%     |
| Works    | 7        | 12     | 50%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 9        | 37.5%   |
| AMD                       | 5        | 20.83%  |
| Samsung Electronics       | 3        | 12.5%   |
| SanDisk                   | 2        | 8.33%   |
| Phison Electronics        | 2        | 8.33%   |
| Micron/Crucial Technology | 1        | 4.17%   |
| ASMedia Technology        | 1        | 4.17%   |
| ADATA Technology          | 1        | 4.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2        | 8%      |
| Intel Jasper Lake SATA AHCI Controller                                         | 2        | 8%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 8%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 8%      |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 8%      |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 8%      |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 4%      |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 4%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 4%      |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 4%      |
| Phison E12 NVMe Controller                                                     | 1        | 4%      |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 4%      |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1        | 4%      |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 4%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 4%      |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 4%      |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 4%      |
| ADATA ADATA XPG GAMMIXS1 1L Media                                              | 1        | 4%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 14       | 58.33%  |
| NVMe | 9        | 37.5%   |
| RAID | 1        | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 64.29%  |
| AMD    | 5        | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor            | 2        | 14.29%  |
| Intel Pentium Silver N6005 @ 2.00GHz         | 1        | 7.14%   |
| Intel Core i7-8700K CPU @ 3.70GHz            | 1        | 7.14%   |
| Intel Core i5-3570 CPU @ 3.40GHz             | 1        | 7.14%   |
| Intel Core i5-3470S CPU @ 2.90GHz            | 1        | 7.14%   |
| Intel Core i3-4130 CPU @ 3.40GHz             | 1        | 7.14%   |
| Intel Celeron N5105 @ 2.00GHz                | 1        | 7.14%   |
| Intel 13th Gen Core i5-13600K                | 1        | 7.14%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz      | 1        | 7.14%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz      | 1        | 7.14%   |
| AMD Ryzen 9 7900X 12-Core Processor          | 1        | 7.14%   |
| AMD Ryzen 5 5600G with Radeon Graphics       | 1        | 7.14%   |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G | 1        | 7.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Other                | 3        | 21.43%  |
| AMD Ryzen 5          | 3        | 21.43%  |
| Intel Core i5        | 2        | 14.29%  |
| Intel Pentium Silver | 1        | 7.14%   |
| Intel Core i7        | 1        | 7.14%   |
| Intel Core i3        | 1        | 7.14%   |
| Intel Celeron        | 1        | 7.14%   |
| AMD Ryzen 9          | 1        | 7.14%   |
| AMD A4               | 1        | 7.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 4        | 28.57%  |
| 4      | 4        | 28.57%  |
| 8      | 2        | 14.29%  |
| 2      | 2        | 14.29%  |
| 14     | 1        | 7.14%   |
| 12     | 1        | 7.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 64.29%  |
| 1      | 5        | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 14       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0671    | 2        | 14.29%  |
| 0x906c0    | 2        | 14.29%  |
| 0x306a9    | 2        | 14.29%  |
| 0x08701021 | 2        | 14.29%  |
| 0xb0671    | 1        | 7.14%   |
| 0x906ea    | 1        | 7.14%   |
| 0x306c3    | 1        | 7.14%   |
| 0x0a601203 | 1        | 7.14%   |
| 0x0a50000c | 1        | 7.14%   |
| 0x06006705 | 1        | 7.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 2        | 14.29%  |
| Tremont          | 2        | 14.29%  |
| IvyBridge        | 2        | 14.29%  |
| Icelake          | 2        | 14.29%  |
| Zen 3            | 1        | 7.14%   |
| KabyLake         | 1        | 7.14%   |
| Haswell          | 1        | 7.14%   |
| Excavator        | 1        | 7.14%   |
| Alderlake Hybrid | 1        | 7.14%   |
| Unknown          | 1        | 7.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 5        | 35.71%  |
| Intel  | 5        | 35.71%  |
| AMD    | 4        | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel JasperLake [UHD Graphics]                                           | 2        | 12.5%   |
| Nvidia TU117GL [T400 4GB]                                                 | 1        | 6.25%   |
| Nvidia GT218 [GeForce G210]                                               | 1        | 6.25%   |
| Nvidia GP104 [GeForce GTX 1070]                                           | 1        | 6.25%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 6.25%   |
| Nvidia GA106 [Geforce RTX 3050]                                           | 1        | 6.25%   |
| Nvidia G92 [GeForce 9800 GT]                                              | 1        | 6.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 6.25%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                 | 1        | 6.25%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 6.25%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1        | 6.25%   |
| AMD Raphael                                                               | 1        | 6.25%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 1        | 6.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 1        | 6.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 1        | 6.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 5        | 35.71%  |
| 1 x Nvidia | 4        | 28.57%  |
| 1 x AMD    | 3        | 21.43%  |
| 2 x Nvidia | 1        | 7.14%   |
| 2 x AMD    | 1        | 7.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 85.71%  |
| Proprietary | 1        | 7.14%   |
| Unknown     | 1        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 35.71%  |
| 7.01-8.0   | 2        | 14.29%  |
| 3.01-4.0   | 2        | 14.29%  |
| 0.01-0.5   | 2        | 14.29%  |
| 1.01-2.0   | 1        | 7.14%   |
| 8.01-16.0  | 1        | 7.14%   |
| 0.51-1.0   | 1        | 7.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 3        | 23.08%  |
| Samsung Electronics | 2        | 15.38%  |
| STD                 | 1        | 7.69%   |
| Sony                | 1        | 7.69%   |
| OUT                 | 1        | 7.69%   |
| Haier               | 1        | 7.69%   |
| Goldstar            | 1        | 7.69%   |
| Deco Gear           | 1        | 7.69%   |
| BenQ                | 1        | 7.69%   |
| Acer                | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| STD LED STD0110 1920x1080 480x260mm 21.5-inch                          | 1        | 6.67%   |
| Sony TV SNYD703 1360x768                                               | 1        | 6.67%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch   | 1        | 6.67%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch   | 1        | 6.67%   |
| Samsung Electronics S27C500 SAM0AF2 1920x1080 598x336mm 27.0-inch      | 1        | 6.67%   |
| Samsung Electronics LCD Monitor SAM0C04 3840x2160 1420x800mm 64.2-inch | 1        | 6.67%   |
| OUT Analog OUT0096 1280x800 341x256mm 16.8-inch                        | 1        | 6.67%   |
| Haier LED39C800F HAI17FC 1920x1080 1150x650mm 52.0-inch                | 1        | 6.67%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                  | 1        | 6.67%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                     | 1        | 6.67%   |
| Dell S2009W DELA045 1600x900 443x249mm 20.0-inch                       | 1        | 6.67%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                      | 1        | 6.67%   |
| Deco Gear DGVIEW220 DGVFFFF 3440x1440 819x346mm 35.0-inch              | 1        | 6.67%   |
| BenQ GW2255 BNQ78CD 1920x1080 477x268mm 21.5-inch                      | 1        | 6.67%   |
| Acer ED322QR ACR06DD 1920x1080 700x390mm 31.5-inch                     | 1        | 6.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 7        | 46.67%  |
| 3840x2160 (4K)     | 2        | 13.33%  |
| 1680x1050 (WSXGA+) | 2        | 13.33%  |
| 3440x1440          | 1        | 6.67%   |
| 1600x900 (HD+)     | 1        | 6.67%   |
| 1280x768           | 1        | 6.67%   |
| 1280x1024 (SXGA)   | 1        | 6.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 4        | 26.67%  |
| 27     | 2        | 13.33%  |
| 72     | 1        | 6.67%   |
| 64     | 1        | 6.67%   |
| 52     | 1        | 6.67%   |
| 35     | 1        | 6.67%   |
| 31     | 1        | 6.67%   |
| 23     | 1        | 6.67%   |
| 20     | 1        | 6.67%   |
| 19     | 1        | 6.67%   |
| 16     | 1        | 6.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 5        | 33.33%  |
| 501-600     | 3        | 20%     |
| 1001-1500   | 2        | 13.33%  |
| 801-900     | 1        | 6.67%   |
| 601-700     | 1        | 6.67%   |
| 351-400     | 1        | 6.67%   |
| 301-350     | 1        | 6.67%   |
| 1501-2000   | 1        | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 9        | 69.23%  |
| 5/4   | 1        | 7.69%   |
| 4/3   | 1        | 7.69%   |
| 21/9  | 1        | 7.69%   |
| 16/10 | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| More than 1000 | 3        | 21.43%  |
| 201-250        | 3        | 21.43%  |
| 151-200        | 3        | 21.43%  |
| 351-500        | 2        | 14.29%  |
| 301-350        | 2        | 14.29%  |
| 131-140        | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 7        | 53.85%  |
| 101-120 | 4        | 30.77%  |
| 1-50    | 2        | 15.38%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 71.43%  |
| 0     | 2        | 14.29%  |
| 3     | 1        | 7.14%   |
| 2     | 1        | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 50%     |
| Intel                 | 8        | 40%     |
| ASUSTek Computer      | 1        | 5%      |
| Aquantia              | 1        | 5%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 13.79%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 10.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 10.34%  |
| Intel Ethernet Controller I225-V                                  | 3        | 10.34%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 10.34%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 6.9%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 6.9%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 3.45%   |
| Realtek 802.11n WLAN Adapter                                      | 1        | 3.45%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1        | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.45%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.45%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 3.45%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU]               | 1        | 3.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 63.64%  |
| Realtek Semiconductor | 3        | 27.27%  |
| ASUSTek Computer      | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]    | 3        | 27.27%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz              | 2        | 18.18%  |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter          | 1        | 9.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter | 1        | 9.09%   |
| Realtek 802.11n WLAN Adapter                        | 1        | 9.09%   |
| Intel Wi-Fi 6 AX201 160MHz                          | 1        | 9.09%   |
| Intel Alder Lake-S PCH CNVi WiFi                    | 1        | 9.09%   |
| ASUS WL-167G v3 802.11n Adapter [Realtek RTL8188SU] | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 62.5%   |
| Intel                 | 5        | 31.25%  |
| Aquantia              | 1        | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 22.22%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 16.67%  |
| Intel Ethernet Controller I225-V                                  | 3        | 16.67%  |
| Intel 82574L Gigabit Network Connection                           | 2        | 11.11%  |
| Intel I211 Gigabit Network Connection                             | 1        | 5.56%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 5.56%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 58.33%  |
| WiFi     | 10       | 41.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 75%     |
| WiFi     | 4        | 25%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 6        | 42.86%  |
| 1     | 5        | 35.71%  |
| 4     | 2        | 14.29%  |
| 3     | 1        | 7.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 71.43%  |
| Yes  | 4        | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 7        | 70%     |
| Cambridge Silicon Radio    | 2        | 20%     |
| Integrated System Solution | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 30%     |
| Intel AX210 Bluetooth                                 | 2        | 20%     |
| Intel AX201 Bluetooth                                 | 2        | 20%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 2        | 20%     |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 9        | 40.91%  |
| AMD                                          | 5        | 22.73%  |
| Nvidia                                       | 4        | 18.18%  |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 4.55%   |
| Texas Instruments                            | 1        | 4.55%   |
| Logitech                                     | 1        | 4.55%   |
| Blue Microphones                             | 1        | 4.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 6.9%    |
| Intel Jasper Lake HD Audio                                                 | 2        | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 6.9%    |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 6.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 6.9%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1        | 3.45%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 3.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 3.45%   |
| Nvidia High Definition Audio Controller                                    | 1        | 3.45%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 3.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 3.45%   |
| Nvidia GA106 High Definition Audio Controller                              | 1        | 3.45%   |
| Logitech Headset H340                                                      | 1        | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 3.45%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 3.45%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 3.45%   |
| Blue Microphones Yeti Nano                                                 | 1        | 3.45%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 3.45%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1        | 3.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 3.45%   |
| AMD High Definition Audio Controller                                       | 1        | 3.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 3.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 2        | 28.57%  |
| Unknown             | 1        | 14.29%  |
| SK hynix            | 1        | 14.29%  |
| Samsung Electronics | 1        | 14.29%  |
| Kingston            | 1        | 14.29%  |
| Crucial             | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s             | 1        | 14.29%  |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s | 1        | 14.29%  |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s   | 1        | 14.29%  |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 1        | 14.29%  |
| G.Skill RAM F5-6000J3636F16G 16GB DIMM 6400MT/s       | 1        | 14.29%  |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s  | 1        | 14.29%  |
| Crucial RAM CT8G4S24AM.M8FJ 8GB SODIMM DDR4 2400MT/s  | 1        | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 3        | 42.86%  |
| DDR3   | 2        | 28.57%  |
| LPDDR4 | 1        | 14.29%  |
| DDR5   | 1        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 5        | 71.43%  |
| SODIMM       | 1        | 14.29%  |
| Row Of Chips | 1        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 3        | 42.86%  |
| 8192  | 3        | 42.86%  |
| 4096  | 1        | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 2        | 28.57%  |
| 6400  | 1        | 14.29%  |
| 2933  | 1        | 14.29%  |
| 2400  | 1        | 14.29%  |
| 1867  | 1        | 14.29%  |
| 1333  | 1        | 14.29%  |

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


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| vivo V2023              | 1        | 20%     |
| Realtek Full HD webcam  | 1        | 20%     |
| Microdia USB 2.0 Camera | 1        | 20%     |
| Logitech Webcam C250    | 1        | 20%     |
| IMC Networks XHC Camera | 1        | 20%     |

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
| 0     | 12       | 85.71%  |
| 2     | 1        | 7.14%   |
| 1     | 1        | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 1        | 50%     |
| Graphics card | 1        | 50%     |

