CentOS 9 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 9.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MEG Z790 ACE                | [41d0e4fddd](https://linux-hardware.org/?probe=41d0e4fddd) | Oct 24, 2023 |
| ASUSTek       | P8H61/USB3                  | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| ASUSTek       | P8H61/USB3                  | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [993a10a30b](https://linux-hardware.org/?probe=993a10a30b) | Aug 01, 2023 |
| Gateway       | H61H2-AD V1.0               | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
| ASUSTek       | P8H61/USB3                  | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| ASUSTek       | P8H67-M LE                  | [a69366e2b7](https://linux-hardware.org/?probe=a69366e2b7) | May 29, 2023 |
| ASUSTek       | P8H67-M LE                  | [07202660b9](https://linux-hardware.org/?probe=07202660b9) | May 26, 2023 |
| Acer          | Predator G3-605             | [6f91022c83](https://linux-hardware.org/?probe=6f91022c83) | May 04, 2023 |
| Colorful T... | CVN Z590 GAMING PRO V20     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| Dell          | 0NKW6Y A02                  | [f20d5b9289](https://linux-hardware.org/?probe=f20d5b9289) | Dec 07, 2022 |
| MSI           | X470 GAMING PRO             | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e840ded8c0](https://linux-hardware.org/?probe=e840ded8c0) | Nov 09, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| Intel         | D34010WYK H14771-303        | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| ASUSTek       | H81M-K                      | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| ASUSTek       | H81M-K                      | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| NCR           | Pocono BIOS.6.0             | [ae030a0cda](https://linux-hardware.org/?probe=ae030a0cda) | Jul 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [c45dba9246](https://linux-hardware.org/?probe=c45dba9246) | Jun 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [3d36beed4b](https://linux-hardware.org/?probe=3d36beed4b) | Jun 25, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.14.0-202.el9.x86_64          | 2        | 9.52%   |
| 5.17.2-lqx3.0.el9.x86_64       | 1        | 4.76%   |
| 5.14.0-86.el9.x86_64           | 1        | 4.76%   |
| 5.14.0-375.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-362.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-352.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-344.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-340.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-325.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-319.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-316.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-305.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-302.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-267.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-214.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-183.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-134.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-130.rt21.130.el9.x86_64 | 1        | 4.76%   |
| 5.14.0-115.el9.x86_64          | 1        | 4.76%   |
| 5.14.0-109.el9.x86_64          | 1        | 4.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 16       | 94.12%  |
| 5.17.2  | 1        | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 16       | 94.12%  |
| 5.17    | 1        | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 17       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 13       | 76.47%  |
| KDE5          | 2        | 11.76%  |
| GNOME Classic | 2        | 11.76%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 9        | 50%     |
| Wayland | 9        | 50%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 61.11%  |
| GDM     | 6        | 33.33%  |
| SDDM    | 1        | 5.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 10       | 58.82%  |
| ja_JP | 2        | 11.76%  |
| zh_CN | 1        | 5.88%   |
| ru_UA | 1        | 5.88%   |
| it_IT | 1        | 5.88%   |
| en_AU | 1        | 5.88%   |
| de_DE | 1        | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 13       | 76.47%  |
| BIOS | 4        | 23.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 14       | 82.35%  |
| Ext4 | 3        | 17.65%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 57.89%  |
| GPT     | 7        | 36.84%  |
| MBR     | 1        | 5.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 83.33%  |
| Yes       | 3        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 68.42%  |
| Yes       | 6        | 31.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 47.06%  |
| MSI                 | 2        | 11.76%  |
| Gigabyte Technology | 2        | 11.76%  |
| Intel               | 1        | 5.88%   |
| Gateway             | 1        | 5.88%   |
| Dell                | 1        | 5.88%   |
| Colorful Technology | 1        | 5.88%   |
| Acer                | 1        | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS PRIME H670-PLUS D4           | 2        | 11.76%  |
| MSI MS-7D86                       | 1        | 5.88%   |
| MSI MS-7B79                       | 1        | 5.88%   |
| Intel D34010WYK H14771-303        | 1        | 5.88%   |
| Gigabyte X99-UD4-CF               | 1        | 5.88%   |
| Gigabyte 970A-DS3P                | 1        | 5.88%   |
| Gateway SX2865                    | 1        | 5.88%   |
| Dell OptiPlex 790                 | 1        | 5.88%   |
| Colorful CVN Z590 GAMING PRO      | 1        | 5.88%   |
| ASUS TUF Gaming X570-PLUS         | 1        | 5.88%   |
| ASUS ROG STRIX B560-G GAMING WIFI | 1        | 5.88%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 1        | 5.88%   |
| ASUS P8H67-M LE                   | 1        | 5.88%   |
| ASUS P8H61/USB3                   | 1        | 5.88%   |
| ASUS All Series                   | 1        | 5.88%   |
| Acer Predator G3-605              | 1        | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS ROG            | 2        | 11.76%  |
| ASUS PRIME          | 2        | 11.76%  |
| MSI MS-7D86         | 1        | 5.88%   |
| MSI MS-7B79         | 1        | 5.88%   |
| Intel D34010WYK     | 1        | 5.88%   |
| Gigabyte X99-UD4-CF | 1        | 5.88%   |
| Gigabyte 970A-DS3P  | 1        | 5.88%   |
| Gateway SX2865      | 1        | 5.88%   |
| Dell OptiPlex       | 1        | 5.88%   |
| Colorful CVN        | 1        | 5.88%   |
| ASUS TUF            | 1        | 5.88%   |
| ASUS P8H67-M        | 1        | 5.88%   |
| ASUS P8H61          | 1        | 5.88%   |
| ASUS All            | 1        | 5.88%   |
| Acer Predator       | 1        | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 5        | 29.41%  |
| 2021 | 4        | 23.53%  |
| 2011 | 3        | 17.65%  |
| 2023 | 1        | 5.88%   |
| 2020 | 1        | 5.88%   |
| 2019 | 1        | 5.88%   |
| 2018 | 1        | 5.88%   |
| 2014 | 1        | 5.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 17       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 16       | 94.12%  |
| Enabled  | 1        | 5.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 6        | 35.29%  |
| 64.01-256.0 | 4        | 23.53%  |
| 32.01-64.0  | 3        | 17.65%  |
| 16.01-24.0  | 2        | 11.76%  |
| 8.01-16.0   | 2        | 11.76%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 8        | 42.11%  |
| 3.01-4.0   | 6        | 31.58%  |
| 8.01-16.0  | 2        | 10.53%  |
| 4.01-8.0   | 1        | 5.26%   |
| 16.01-24.0 | 1        | 5.26%   |
| 1.01-2.0   | 1        | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 4      | 5        | 29.41%  |
| 3      | 4        | 23.53%  |
| 2      | 4        | 23.53%  |
| 1      | 3        | 17.65%  |
| 5      | 1        | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 76.47%  |
| Yes       | 4        | 23.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 58.82%  |
| No        | 7        | 41.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 52.94%  |
| No        | 8        | 47.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 4        | 23.53%  |
| Bulgaria    | 3        | 17.65%  |
| Japan       | 2        | 11.76%  |
| Ukraine     | 1        | 5.88%   |
| Puerto Rico | 1        | 5.88%   |
| Myanmar     | 1        | 5.88%   |
| Italy       | 1        | 5.88%   |
| Germany     | 1        | 5.88%   |
| China       | 1        | 5.88%   |
| Belarus     | 1        | 5.88%   |
| Australia   | 1        | 5.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sofia          | 2        | 10.53%  |
| Yangon         | 1        | 5.26%   |
| Wuhan          | 1        | 5.26%   |
| Vitebsk        | 1        | 5.26%   |
| Tomah          | 1        | 5.26%   |
| San Juan       | 1        | 5.26%   |
| Rome           | 1        | 5.26%   |
| Portland       | 1        | 5.26%   |
| Perth          | 1        | 5.26%   |
| Okazaki        | 1        | 5.26%   |
| New Cumberland | 1        | 5.26%   |
| Navapolatsk    | 1        | 5.26%   |
| Nagoya         | 1        | 5.26%   |
| Milpitas       | 1        | 5.26%   |
| Meieki         | 1        | 5.26%   |
| Kyiv           | 1        | 5.26%   |
| Dortmund       | 1        | 5.26%   |
| Burgas         | 1        | 5.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 14     | 23.68%  |
| Seagate             | 5        | 7      | 13.16%  |
| Samsung Electronics | 4        | 5      | 10.53%  |
| Sandisk             | 3        | 9      | 7.89%   |
| Kingston            | 3        | 5      | 7.89%   |
| Toshiba             | 2        | 3      | 5.26%   |
| Crucial             | 2        | 8      | 5.26%   |
| WD MediaMax         | 1        | 1      | 2.63%   |
| Team                | 1        | 2      | 2.63%   |
| Plextor             | 1        | 1      | 2.63%   |
| Phison Electronics  | 1        | 1      | 2.63%   |
| Phison              | 1        | 1      | 2.63%   |
| OCZ                 | 1        | 1      | 2.63%   |
| Intel               | 1        | 1      | 2.63%   |
| Hitachi             | 1        | 1      | 2.63%   |
| Gigabyte Technology | 1        | 2      | 2.63%   |
| A-DATA Technology   | 1        | 1      | 2.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Sandisk WD_BLACK SN770 1TB                 | 2        | 4.76%   |
| SanDisk SDSSDH3 1T00 1TB                   | 2        | 4.76%   |
| Crucial CT525MX300SSD1 528GB               | 2        | 4.76%   |
| WDC WDS250G2B0A-00SM50 250GB SSD           | 1        | 2.38%   |
| WDC WD6003FZBX-00K5WB0 6TB                 | 1        | 2.38%   |
| WDC WD5000BEVT-55A0RT0 500GB               | 1        | 2.38%   |
| WDC WD3200AAKX-753CA1 320GB                | 1        | 2.38%   |
| WDC WD2500AAJS-60M0A0 250GB                | 1        | 2.38%   |
| WDC WD22EJRX-89BEMY0 2TB                   | 1        | 2.38%   |
| WDC WD2003FZEX-00Z4SA0 2TB                 | 1        | 2.38%   |
| WDC WD10EZEX-60M2NA0 1TB                   | 1        | 2.38%   |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 2.38%   |
| WDC WD10EZEX-00BN5A0 1TB                   | 1        | 2.38%   |
| WD MediaMax WL750GSA6472 752GB             | 1        | 2.38%   |
| Toshiba MK2561GSYN 250GB                   | 1        | 2.38%   |
| Toshiba DT01ACA100 1TB                     | 1        | 2.38%   |
| Team T253X1480G 480GB SSD                  | 1        | 2.38%   |
| Seagate ST3500413AS 500GB                  | 1        | 2.38%   |
| Seagate ST3250820AS 250GB                  | 1        | 2.38%   |
| Seagate ST2000DL003-9VT166 2TB             | 1        | 2.38%   |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 2.38%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 2.38%   |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB | 1        | 2.38%   |
| Sandisk WD_BLACK SN850X 4000GB             | 1        | 2.38%   |
| Samsung SSD 870 QVO 2TB                    | 1        | 2.38%   |
| Samsung SSD 870 EVO 250GB                  | 1        | 2.38%   |
| Samsung SSD 860 PRO 2TB                    | 1        | 2.38%   |
| Samsung MZ7LN256HAJQ-00000 256GB SSD       | 1        | 2.38%   |
| Plextor PX-256M8VC 256GB SSD               | 1        | 2.38%   |
| Phison NVMe SSD Drive 1024GB               | 1        | 2.38%   |
| Phison E16 PCIe4 NVMe Controller 500GB     | 1        | 2.38%   |
| OCZ AGILITY3 64GB SSD                      | 1        | 2.38%   |
| Kingston SUV400S37480G 480GB SSD           | 1        | 2.38%   |
| Kingston SHFS37A480G 480GB SSD             | 1        | 2.38%   |
| Kingston RBU-SMS100S3128GA 128GB SSD       | 1        | 2.38%   |
| Intel NVMe SSD Drive 1024GB                | 1        | 2.38%   |
| Hitachi HDS723020BLA642 2TB                | 1        | 2.38%   |
| Gigabyte GP-GSTFS31960GNTD-V 960GB SSD     | 1        | 2.38%   |
| A-DATA SP310 32GB SSD                      | 1        | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 8        | 13     | 50%     |
| Seagate     | 4        | 5      | 25%     |
| Toshiba     | 2        | 3      | 12.5%   |
| WD MediaMax | 1        | 1      | 6.25%   |
| Hitachi     | 1        | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 5      | 23.53%  |
| Kingston            | 3        | 5      | 17.65%  |
| SanDisk             | 2        | 4      | 11.76%  |
| Crucial             | 2        | 8      | 11.76%  |
| WDC                 | 1        | 1      | 5.88%   |
| Team                | 1        | 2      | 5.88%   |
| Plextor             | 1        | 1      | 5.88%   |
| OCZ                 | 1        | 1      | 5.88%   |
| Gigabyte Technology | 1        | 2      | 5.88%   |
| A-DATA Technology   | 1        | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 13       | 30     | 43.33%  |
| HDD  | 10       | 23     | 33.33%  |
| NVMe | 7        | 10     | 23.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 16       | 53     | 69.57%  |
| NVMe | 7        | 10     | 30.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 11       | 20     | 44%     |
| 0.51-1.0   | 8        | 22     | 32%     |
| 1.01-2.0   | 5        | 9      | 20%     |
| 4.01-10.0  | 1        | 2      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 6        | 33.33%  |
| 101-250        | 4        | 22.22%  |
| More than 3000 | 2        | 11.11%  |
| 251-500        | 2        | 11.11%  |
| 21-50          | 1        | 5.56%   |
| 2001-3000      | 1        | 5.56%   |
| 501-1000       | 1        | 5.56%   |
| 51-100         | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 5        | 29.41%  |
| 51-100         | 4        | 23.53%  |
| 21-50          | 3        | 17.65%  |
| 501-1000       | 3        | 17.65%  |
| More than 3000 | 1        | 5.88%   |
| 251-500        | 1        | 5.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD10EZEX-60M2NA0 1TB  | 1        | 1      | 33.33%  |
| Toshiba MK2561GSYN 250GB  | 1        | 1      | 33.33%  |
| Seagate ST3250820AS 250GB | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 100%    |

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
| Detected | 12       | 38     | 57.14%  |
| Works    | 7        | 22     | 33.33%  |
| Malfunc  | 2        | 3      | 9.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 14       | 53.85%  |
| AMD                | 4        | 15.38%  |
| Sandisk            | 3        | 11.54%  |
| Phison Electronics | 2        | 7.69%   |
| Silicon Image      | 1        | 3.85%   |
| Seagate Technology | 1        | 3.85%   |
| ASMedia Technology | 1        | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4        | 14.81%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 11.11%  |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 2        | 7.41%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 7.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 7.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 7.41%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 3.7%    |
| Seagate FireCuda 520/IronWolf 525 SSD                                          | 1        | 3.7%    |
| Sandisk WD Black SN850X NVMe SSD                                               | 1        | 3.7%    |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 3.7%    |
| Phison E12 NVMe Controller                                                     | 1        | 3.7%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1        | 3.7%    |
| Intel SATA Controller [RAID mode]                                              | 1        | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 3.7%    |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 1        | 3.7%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 3.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 66.67%  |
| NVMe | 7        | 29.17%  |
| RAID | 1        | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 76.47%  |
| AMD    | 4        | 23.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel 12th Gen Core i5-12600K          | 2        | 11.76%  |
| Intel Core i7-5930K CPU @ 3.50GHz      | 1        | 5.88%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 5.88%   |
| Intel Core i5-4590 CPU @ 3.30GHz       | 1        | 5.88%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 5.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 1        | 5.88%   |
| Intel Core i5-2400S CPU @ 2.50GHz      | 1        | 5.88%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 5.88%   |
| Intel Core i3-4010U CPU @ 1.70GHz      | 1        | 5.88%   |
| Intel Core i3-2130 CPU @ 3.40GHz       | 1        | 5.88%   |
| Intel 13th Gen Core i9-13900K          | 1        | 5.88%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz | 1        | 5.88%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 1        | 5.88%   |
| AMD Ryzen 9 3950X 16-Core Processor    | 1        | 5.88%   |
| AMD Ryzen 5 3600 6-Core Processor      | 1        | 5.88%   |
| AMD FX-8120 Eight-Core Processor       | 1        | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i5 | 5        | 29.41%  |
| Other         | 4        | 23.53%  |
| Intel Core i7 | 2        | 11.76%  |
| Intel Core i3 | 2        | 11.76%  |
| AMD Ryzen 9   | 2        | 11.76%  |
| AMD Ryzen 5   | 1        | 5.88%   |
| AMD FX        | 1        | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 6        | 35.29%  |
| 6      | 4        | 23.53%  |
| 16     | 2        | 11.76%  |
| 10     | 2        | 11.76%  |
| 2      | 2        | 11.76%  |
| 24     | 1        | 5.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 70.59%  |
| 1      | 5        | 29.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 17       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 29.41%  |
| 0x306c3    | 2        | 11.76%  |
| 0xa0671    | 1        | 5.88%   |
| 0xa0653    | 1        | 5.88%   |
| 0x90672    | 1        | 5.88%   |
| 0x40651    | 1        | 5.88%   |
| 0x306f2    | 1        | 5.88%   |
| 0x206a7    | 1        | 5.88%   |
| 0x0a201016 | 1        | 5.88%   |
| 0x08701021 | 1        | 5.88%   |
| 0x08701013 | 1        | 5.88%   |
| 0x0600063d | 1        | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 4        | 23.53%  |
| SandyBridge      | 3        | 17.65%  |
| Alderlake Hybrid | 3        | 17.65%  |
| Zen 2            | 2        | 11.76%  |
| Zen 3            | 1        | 5.88%   |
| IvyBridge        | 1        | 5.88%   |
| Icelake          | 1        | 5.88%   |
| CometLake        | 1        | 5.88%   |
| Bulldozer        | 1        | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 8        | 44.44%  |
| Intel  | 5        | 27.78%  |
| AMD    | 5        | 27.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia TU117 [GeForce GTX 1650]                                           | 2        | 10%     |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2        | 10%     |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1        | 5%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1        | 5%      |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                 | 1        | 5%      |
| Nvidia GP108 [GeForce GT 1030]                                            | 1        | 5%      |
| Nvidia GM200 [GeForce GTX 980 Ti]                                         | 1        | 5%      |
| Nvidia GM107 [GeForce GTX 745]                                            | 1        | 5%      |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 5%      |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1        | 5%      |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                | 1        | 5%      |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1        | 5%      |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                     | 1        | 5%      |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                 | 1        | 5%      |
| AMD Park [Mobility Radeon HD 5430]                                        | 1        | 5%      |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 1        | 5%      |
| AMD Juniper XT [Radeon HD 6770]                                           | 1        | 5%      |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 1        | 5%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 8        | 47.06%  |
| 1 x Intel  | 4        | 23.53%  |
| 1 x AMD    | 4        | 23.53%  |
| 2 x AMD    | 1        | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 11       | 61.11%  |
| Proprietary | 6        | 33.33%  |
| Unknown     | 1        | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 31.58%  |
| 5.01-6.0   | 3        | 15.79%  |
| 3.01-4.0   | 3        | 15.79%  |
| 1.01-2.0   | 2        | 10.53%  |
| 8.01-16.0  | 2        | 10.53%  |
| 0.51-1.0   | 2        | 10.53%  |
| 0.01-0.5   | 1        | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 25%     |
| Goldstar            | 3        | 15%     |
| Dell                | 3        | 15%     |
| ViewSonic           | 2        | 10%     |
| Iiyama              | 2        | 10%     |
| LG Electronics      | 1        | 5%      |
| Hewlett-Packard     | 1        | 5%      |
| BenQ                | 1        | 5%      |
| AOC                 | 1        | 5%      |
| Acer                | 1        | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Iiyama PL2888H IVM7106 1920x1080 621x341mm 27.9-inch                    | 2        | 8.33%   |
| ViewSonic VX2453 Series VSC0C28 1920x1080 520x290mm 23.4-inch           | 1        | 4.17%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1        | 4.17%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1        | 4.17%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1        | 4.17%   |
| Samsung Electronics S27C450 SAM09D9 1920x1080 598x336mm 27.0-inch       | 1        | 4.17%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 4.17%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1        | 4.17%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch              | 1        | 4.17%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 1        | 4.17%   |
| Goldstar 27GL650F GSM5B70 1920x1080 531x298mm 24.0-inch                 | 1        | 4.17%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                   | 1        | 4.17%   |
| Dell U2720Q DEL41B0 3840x2160 597x336mm 27.0-inch                       | 1        | 4.17%   |
| Dell U2718Q DELA0E9 3840x2160 610x350mm 27.7-inch                       | 1        | 4.17%   |
| Dell U2520D DELA150 2560x1440 553x311mm 25.0-inch                       | 1        | 4.17%   |
| Dell U2520D DELA14E 2560x1440 553x311mm 25.0-inch                       | 1        | 4.17%   |
| Dell U2520D DELA14C 2560x1440 553x311mm 25.0-inch                       | 1        | 4.17%   |
| Dell P2418HT DEL4113 1920x1080 527x296mm 23.8-inch                      | 1        | 4.17%   |
| Dell 2408WFP DELA029 1920x1200 519x324mm 24.1-inch                      | 1        | 4.17%   |
| BenQ ZOWIE XL LCD BNQ7F83 1920x1080 544x303mm 24.5-inch                 | 1        | 4.17%   |
| AOC LCD Monitor 24G1WG4 3840x1080                                       | 1        | 4.17%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                       | 1        | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 13       | 61.9%   |
| 3840x2160 (4K)    | 4        | 19.05%  |
| 3840x1080         | 1        | 4.76%   |
| 2560x1440 (QHD)   | 1        | 4.76%   |
| 1920x1200 (WUXGA) | 1        | 4.76%   |
| Unknown           | 1        | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 33.33%  |
| 21      | 5        | 23.81%  |
| 24      | 3        | 14.29%  |
| 23      | 2        | 9.52%   |
| 84      | 1        | 4.76%   |
| 38      | 1        | 4.76%   |
| 25      | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 40%     |
| 401-500     | 5        | 25%     |
| 601-700     | 4        | 20%     |
| 801-900     | 1        | 5%      |
| 1501-2000   | 1        | 5%      |
| Unknown     | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 15       | 88.24%  |
| 16/10   | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 38.1%   |
| 301-350        | 7        | 33.33%  |
| 251-300        | 3        | 14.29%  |
| More than 1000 | 1        | 4.76%   |
| 501-1000       | 1        | 4.76%   |
| Unknown        | 1        | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 9        | 45%     |
| 101-120 | 7        | 35%     |
| 121-160 | 2        | 10%     |
| 161-240 | 1        | 5%      |
| Unknown | 1        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 66.67%  |
| 2     | 4        | 22.22%  |
| 4     | 1        | 5.56%   |
| 0     | 1        | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 11       | 36.67%  |
| Intel                 | 11       | 36.67%  |
| Qualcomm Atheros      | 3        | 10%     |
| U-Blox                | 1        | 3.33%   |
| TP-Link               | 1        | 3.33%   |
| DisplayLink           | 1        | 3.33%   |
| Ceton Technologies    | 1        | 3.33%   |
| Aquantia              | 1        | 3.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 6        | 17.14%  |
| Realtek RTL8125 2.5GbE Controller                                   | 3        | 8.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 5.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 5.71%   |
| Intel Wi-Fi 6 AX200                                                 | 2        | 5.71%   |
| Intel Ethernet Controller I225-V                                    | 2        | 5.71%   |
| U-Blox [u-blox 8]                                                   | 1        | 2.86%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1        | 2.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 1        | 2.86%   |
| Intel Wireless-AC 9260                                              | 1        | 2.86%   |
| Intel Wireless 7260                                                 | 1        | 2.86%   |
| Intel I211 Gigabit Network Connection                               | 1        | 2.86%   |
| Intel Ethernet Controller I226-V                                    | 1        | 2.86%   |
| Intel Ethernet Connection I218-V                                    | 1        | 2.86%   |
| Intel Ethernet Connection I217-V                                    | 1        | 2.86%   |
| Intel Ethernet Connection (2) I218-V                                | 1        | 2.86%   |
| Intel 82579V Gigabit Network Connection                             | 1        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 2.86%   |
| Intel 82574L Gigabit Network Connection                             | 1        | 2.86%   |
| Intel 700 Series Chipset Family Wi-Fi                               | 1        | 2.86%   |
| DisplayLink Plugable UD-6950PDZ                                     | 1        | 2.86%   |
| Ceton InfiniTV Network                                              | 1        | 2.86%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 45.45%  |
| Qualcomm Atheros      | 3        | 27.27%  |
| Realtek Semiconductor | 2        | 18.18%  |
| TP-Link               | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 2        | 18.18%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2        | 18.18%  |
| Intel Wi-Fi 6 AX200                                        | 2        | 18.18%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 9.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 9.09%   |
| Intel Wireless-AC 9260                                     | 1        | 9.09%   |
| Intel Wireless 7260                                        | 1        | 9.09%   |
| Intel 700 Series Chipset Family Wi-Fi                      | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 45.45%  |
| Realtek Semiconductor | 9        | 40.91%  |
| DisplayLink           | 1        | 4.55%   |
| Ceton Technologies    | 1        | 4.55%   |
| Aquantia              | 1        | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 6        | 26.09%  |
| Realtek RTL8125 2.5GbE Controller                                   | 3        | 13.04%  |
| Intel Ethernet Controller I225-V                                    | 2        | 8.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 1        | 4.35%   |
| Intel I211 Gigabit Network Connection                               | 1        | 4.35%   |
| Intel Ethernet Controller I226-V                                    | 1        | 4.35%   |
| Intel Ethernet Connection I218-V                                    | 1        | 4.35%   |
| Intel Ethernet Connection I217-V                                    | 1        | 4.35%   |
| Intel Ethernet Connection (2) I218-V                                | 1        | 4.35%   |
| Intel 82579V Gigabit Network Connection                             | 1        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 1        | 4.35%   |
| Intel 82574L Gigabit Network Connection                             | 1        | 4.35%   |
| DisplayLink Plugable UD-6950PDZ                                     | 1        | 4.35%   |
| Ceton InfiniTV Network                                              | 1        | 4.35%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 60.71%  |
| WiFi     | 10       | 35.71%  |
| Modem    | 1        | 3.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 88.89%  |
| WiFi     | 2        | 11.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 8        | 47.06%  |
| 1     | 6        | 35.29%  |
| 3     | 3        | 17.65%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 76.47%  |
| Yes  | 4        | 23.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 55.56%  |
| Qualcomm Atheros Communications | 1        | 11.11%  |
| Lite-On Technology              | 1        | 11.11%  |
| Cambridge Silicon Radio         | 1        | 11.11%  |
| ASUSTek Computer                | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 22.22%  |
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 11.11%  |
| Lite-On Bluetooth Device                            | 1        | 11.11%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 11.11%  |
| Intel Bluetooth wireless interface                  | 1        | 11.11%  |
| Intel Bluetooth Device                              | 1        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 11.11%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 13       | 39.39%  |
| Nvidia                   | 8        | 24.24%  |
| AMD                      | 7        | 21.21%  |
| SteelSeries ApS          | 3        | 9.09%   |
| Micro Star International | 1        | 3.03%   |
| Anlya.cn                 | 1        | 3.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 11.11%  |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 8.33%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 5.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2        | 5.56%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2        | 5.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 5.56%   |
| SteelSeries ApS SteelSeries Siberia 800                                    | 1        | 2.78%   |
| SteelSeries ApS SteelSeries GameDAC                                        | 1        | 2.78%   |
| SteelSeries ApS Arctis Nova Pro Wireless                                   | 1        | 2.78%   |
| Nvidia TU102 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 2.78%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 2.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1        | 2.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.78%   |
| Micro Star International USB Audio                                         | 1        | 2.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 2.78%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 2.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 2.78%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 2.78%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 2.78%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 1        | 2.78%   |
| Anlya.cn AB13X USB Audio                                                   | 1        | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 2.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 2.78%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 1        | 2.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 2.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 2.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 2        | 22.22%  |
| Corsair             | 2        | 22.22%  |
| Team                | 1        | 11.11%  |
| SK hynix            | 1        | 11.11%  |
| Samsung Electronics | 1        | 11.11%  |
| Kingston            | 1        | 11.11%  |
| Crucial             | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s       | 1        | 11.11%  |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 11.11%  |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s      | 1        | 11.11%  |
| Kingston RAM 99U5471-034.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 11.11%  |
| G.Skill RAM F5-5600J3036D32G 32GB DIMM DDR5 5600MT/s     | 1        | 11.11%  |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s    | 1        | 11.11%  |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s | 1        | 11.11%  |
| Corsair RAM CMK64GX4M2Z4000C18 32GB DIMM DDR4 4000MT/s   | 1        | 11.11%  |
| Corsair RAM CMK128GX4M8A2666C16 16GB DIMM DDR4 2133MT/s  | 1        | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 4        | 44.44%  |
| DDR3 | 4        | 44.44%  |
| DDR5 | 1        | 11.11%  |

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


| Size  | Desktops | Percent |
|-------|----------|---------|
| 32768 | 3        | 33.33%  |
| 16384 | 2        | 22.22%  |
| 8192  | 2        | 22.22%  |
| 4096  | 2        | 22.22%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 3        | 33.33%  |
| 5600  | 1        | 11.11%  |
| 4000  | 1        | 11.11%  |
| 3600  | 1        | 11.11%  |
| 2933  | 1        | 11.11%  |
| 2133  | 1        | 11.11%  |
| 1800  | 1        | 11.11%  |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 2        | 50%     |
| Logitech                      | 2        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Sunplus Full HD webcam          | 2        | 50%     |
| Logitech Webcam C270            | 1        | 25%     |
| Logitech C922 Pro Stream Webcam | 1        | 25%     |

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
| 0     | 12       | 63.16%  |
| 1     | 6        | 31.58%  |
| 2     | 1        | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 3        | 37.5%   |
| Unassigned class | 1        | 12.5%   |
| Storage/ata      | 1        | 12.5%   |
| Graphics card    | 1        | 12.5%   |
| Dvb card         | 1        | 12.5%   |
| Bluetooth        | 1        | 12.5%   |

