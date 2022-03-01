Q4OS - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Q4OS.

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

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| Visual Lan... | Premier 10              | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56           | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56           | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| MSI           | U210                    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660          | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660          | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                   | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660          | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660          | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Phoenix/Si... | M720SR                  | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx       | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx       | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro            | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| HP            | ProBook 450 G2          | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                     | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| HP            | ProBook 6550b           | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASUSTek       | A6JC                    | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                    | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00 | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81           | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP             | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC             | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Unknown       | MEDION                  | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| Philco        | 14I                     | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 4.19.0-17-amd64   | 4         | 20%     |
| 5.10.0-8-amd64    | 2         | 10%     |
| 5.9.0-5-amd64     | 1         | 5%      |
| 5.6.0-1-amd64     | 1         | 5%      |
| 5.10.0-9-amd64    | 1         | 5%      |
| 5.10.0-8-686-pae  | 1         | 5%      |
| 5.10.0-11-686-pae | 1         | 5%      |
| 5.10.0-10-686-pae | 1         | 5%      |
| 4.9.0-8-amd64     | 1         | 5%      |
| 4.9.0-14-686-pae  | 1         | 5%      |
| 4.9.0-12-686-pae  | 1         | 5%      |
| 4.19.0-17-686     | 1         | 5%      |
| 4.19.0-14-amd64   | 1         | 5%      |
| 4.19.0-13-amd64   | 1         | 5%      |
| 4.19.0-12-amd64   | 1         | 5%      |
| 4.19.0-10-amd64   | 1         | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19.0  | 9         | 45%     |
| 5.10.0  | 6         | 30%     |
| 4.9.0   | 3         | 15%     |
| 5.9.0   | 1         | 5%      |
| 5.6.0   | 1         | 5%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 9         | 45%     |
| 5.10    | 6         | 30%     |
| 4.9     | 3         | 15%     |
| 5.9     | 1         | 5%      |
| 5.6     | 1         | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 14        | 70%     |
| i686   | 6         | 30%     |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 10        | 50%     |
| trinity | 9         | 45%     |
| KDE     | 1         | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 19        | 95%     |
| Tty  | 1         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 11        | 55%     |
| TDM  | 9         | 45%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 9         | 45%     |
| es_ES   | 2         | 10%     |
| en_GB   | 2         | 10%     |
| sl_SI   | 1         | 5%      |
| pl_PL   | 1         | 5%      |
| fr_FR   | 1         | 5%      |
| es_VE   | 1         | 5%      |
| de_DE   | 1         | 5%      |
| C       | 1         | 5%      |
| Unknown | 1         | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 13        | 65%     |
| EFI  | 7         | 35%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 17        | 85%     |
| Overlay | 3         | 15%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 12        | 60%     |
| GPT     | 7         | 35%     |
| Unknown | 1         | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 85%     |
| Yes       | 3         | 15%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 65%     |
| Yes       | 7         | 35%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 6         | 30%     |
| Toshiba          | 2         | 10%     |
| ASUSTek Computer | 2         | 10%     |
| Visual Land      | 1         | 5%      |
| Qilive           | 1         | 5%      |
| Phoenix/SiS      | 1         | 5%      |
| Philco           | 1         | 5%      |
| Packard Bell     | 1         | 5%      |
| MSI              | 1         | 5%      |
| Lenovo           | 1         | 5%      |
| JVC              | 1         | 5%      |
| Chuwi            | 1         | 5%      |
| Unknown          | 1         | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Toshiba Satellite C660         | 2         | 10%     |
| Visual Land Premier 10         | 1         | 5%      |
| Qilive QW19141AMSP             | 1         | 5%      |
| Phoenix/SiS M720SR             | 1         | 5%      |
| Philco 14I                     | 1         | 5%      |
| Packard Bell EasyNote LM81     | 1         | 5%      |
| MSI U210                       | 1         | 5%      |
| Lenovo ThinkPad 11e 20DAS0PS00 | 1         | 5%      |
| JVC J3N                        | 1         | 5%      |
| HP ProBook 6550b               | 1         | 5%      |
| HP ProBook 450 G2              | 1         | 5%      |
| HP Presario CQ56               | 1         | 5%      |
| HP OmniBook PC                 | 1         | 5%      |
| HP Laptop 15s-fq2xxx           | 1         | 5%      |
| HP 2000                        | 1         | 5%      |
| Chuwi GemiBook Pro             | 1         | 5%      |
| ASUS T12Eg                     | 1         | 5%      |
| ASUS A6JC                      | 1         | 5%      |
| Unknown                        | 1         | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Toshiba Satellite     | 2         | 10%     |
| HP ProBook            | 2         | 10%     |
| Visual Land Premier   | 1         | 5%      |
| Qilive QW19141AMSP    | 1         | 5%      |
| Phoenix/SiS M720SR    | 1         | 5%      |
| Philco 14I            | 1         | 5%      |
| Packard Bell EasyNote | 1         | 5%      |
| MSI U210              | 1         | 5%      |
| Lenovo ThinkPad       | 1         | 5%      |
| JVC J3N               | 1         | 5%      |
| HP Presario           | 1         | 5%      |
| HP OmniBook           | 1         | 5%      |
| HP Laptop             | 1         | 5%      |
| HP 2000               | 1         | 5%      |
| Chuwi GemiBook        | 1         | 5%      |
| ASUS T12Eg            | 1         | 5%      |
| ASUS A6JC             | 1         | 5%      |
| Unknown               | 1         | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2010    | 5         | 25%     |
| 2020    | 2         | 10%     |
| 2014    | 2         | 10%     |
| Unknown | 2         | 10%     |
| 2019    | 1         | 5%      |
| 2017    | 1         | 5%      |
| 2015    | 1         | 5%      |
| 2012    | 1         | 5%      |
| 2011    | 1         | 5%      |
| 2009    | 1         | 5%      |
| 2007    | 1         | 5%      |
| 2006    | 1         | 5%      |
| 2004    | 1         | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 20        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 20        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 6         | 30%     |
| 1.01-2.0   | 4         | 20%     |
| 4.01-8.0   | 3         | 15%     |
| 0.51-1.0   | 3         | 15%     |
| 2.01-3.0   | 2         | 10%     |
| 16.01-24.0 | 1         | 5%      |
| 0.01-0.5   | 1         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 10        | 50%     |
| 0.51-1.0 | 5         | 25%     |
| 2.01-3.0 | 2         | 10%     |
| 0.01-0.5 | 2         | 10%     |
| 3.01-4.0 | 1         | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 90%     |
| 3      | 1         | 5%      |
| 2      | 1         | 5%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 60%     |
| No        | 8         | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 80%     |
| No        | 4         | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 85%     |
| No        | 3         | 15%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11        | 55%     |
| Yes       | 9         | 45%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| USA       | 3         | 15%     |
| Kenya     | 3         | 15%     |
| UK        | 2         | 10%     |
| Spain     | 2         | 10%     |
| Poland    | 2         | 10%     |
| Venezuela | 1         | 5%      |
| Slovenia  | 1         | 5%      |
| Qatar     | 1         | 5%      |
| Italy     | 1         | 5%      |
| Germany   | 1         | 5%      |
| France    | 1         | 5%      |
| Brazil    | 1         | 5%      |
| Belarus   | 1         | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Nairobi        | 3         | 15%     |
| Swindon        | 2         | 10%     |
| Wygledy        | 1         | 5%      |
| Tellico Plains | 1         | 5%      |
| Rostock        | 1         | 5%      |
| Moirans        | 1         | 5%      |
| Mogilev        | 1         | 5%      |
| Mestre         | 1         | 5%      |
| Mesa           | 1         | 5%      |
| Londrina       | 1         | 5%      |
| Ljubljana      | 1         | 5%      |
| Las Vegas      | 1         | 5%      |
| Katowice       | 1         | 5%      |
| GijГіn       | 1         | 5%      |
| Doha           | 1         | 5%      |
| Barcelona      | 1         | 5%      |
| Agua Salada    | 1         | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 15.79%  |
| Unknown             | 3         | 3      | 15.79%  |
| Hitachi             | 3         | 3      | 15.79%  |
| Seagate             | 2         | 2      | 10.53%  |
| SanDisk             | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Toshiba             | 1         | 1      | 5.26%   |
| Kingston            | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 5.26%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 5.26%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 5.26%   |
| Unknown USDU1  32GB                  | 1         | 5.26%   |
| Unknown SLD64G  64GB                 | 1         | 5.26%   |
| Unknown 064G38  64GB                 | 1         | 5.26%   |
| Toshiba MK8025GAS 80GB               | 1         | 5.26%   |
| Seagate ST9120822AS 120GB            | 1         | 5.26%   |
| Seagate Backup+ SL 1TB               | 1         | 5.26%   |
| SanDisk SDCFX-032G SSD               | 1         | 5.26%   |
| SanDisk SD8SN8U1T001122 1024GB SSD   | 1         | 5.26%   |
| Samsung SSD 850 EVO 250GB            | 1         | 5.26%   |
| Samsung AWMB3R  16GB                 | 1         | 5.26%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 5.26%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 5.26%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 5.26%   |
| Hitachi DK23CA-20 20GB               | 1         | 5.26%   |
| HGST HTS541075A9E680 752GB           | 1         | 5.26%   |
| Fujitsu MHY2080BH 80GB               | 1         | 5.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 33.33%  |
| WDC     | 2         | 2      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Seagate | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |
| Fujitsu | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Kingston            | 1         | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 9         | 9      | 47.37%  |
| MMC     | 4         | 4      | 21.05%  |
| SSD     | 4         | 4      | 21.05%  |
| NVMe    | 1         | 1      | 5.26%   |
| Unknown | 1         | 1      | 5.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 13     | 68.42%  |
| MMC  | 4         | 4      | 21.05%  |
| SAS  | 1         | 1      | 5.26%   |
| NVMe | 1         | 1      | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 11     | 84.62%  |
| 1.01-2.0   | 1         | 1      | 7.69%   |
| 0.51-1.0   | 1         | 1      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 5         | 25%     |
| 51-100     | 4         | 20%     |
| 251-500    | 3         | 15%     |
| 21-50      | 3         | 15%     |
| 101-250    | 2         | 10%     |
| 1001-2000  | 1         | 5%      |
| 501-1000   | 1         | 5%      |
| Unknown    | 1         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 15        | 75%     |
| 21-50    | 2         | 10%     |
| 251-500  | 1         | 5%      |
| 501-1000 | 1         | 5%      |
| Unknown  | 1         | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 14.29%  |
| Seagate ST9120822AS 120GB     | 1         | 1      | 14.29%  |
| Hitachi HTS545032B9A300 320GB | 1         | 1      | 14.29%  |
| Hitachi HTS543225L9SA00 250GB | 1         | 1      | 14.29%  |
| Hitachi DK23CA-20 20GB        | 1         | 1      | 14.29%  |
| HGST HTS541075A9E680 752GB    | 1         | 1      | 14.29%  |
| Fujitsu MHY2080BH 80GB        | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 42.86%  |
| WDC     | 1         | 1      | 14.29%  |
| Seagate | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |
| Fujitsu | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 42.86%  |
| WDC     | 1         | 1      | 14.29%  |
| Seagate | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |
| Fujitsu | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Malfunc  | 7         | 7      | 38.89%  |
| Works    | 6         | 6      | 33.33%  |
| Detected | 5         | 6      | 27.78%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 12        | 63.16%  |
| AMD                              | 5         | 26.32%  |
| Silicon Integrated Systems [SiS] | 1         | 5.26%   |
| Sandisk                          | 1         | 5.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 9.09%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 1         | 4.55%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 1         | 4.55%   |
| Sandisk WD Blue SN550 NVMe SSD                                               | 1         | 4.55%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 4.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 4.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 4.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 4.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 1         | 4.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 4.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 4.55%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 1         | 4.55%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                | 1         | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 4.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                             | 1         | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 1         | 4.55%   |
| AMD SB600 Non-Raid-5 SATA                                                    | 1         | 4.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 12        | 60%     |
| IDE  | 6         | 30%     |
| RAID | 1         | 5%      |
| NVMe | 1         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 75%     |
| AMD    | 5         | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 10%     |
| Intel Pentium M processor 1000MHz             | 1         | 5%      |
| Intel Pentium III (Coppermine)                | 1         | 5%      |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 5%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 5%      |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 1         | 5%      |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 5%      |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 1         | 5%      |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 5%      |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 5%      |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 5%      |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 1         | 5%      |
| Intel Atom CPU Z3735G @ 1.33GHz               | 1         | 5%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 5%      |
| AMD V120 Processor                            | 1         | 5%      |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 5%      |
| AMD C-70 APU with Radeon HD Graphics          | 1         | 5%      |
| AMD Athlon Neo Processor MV-40                | 1         | 5%      |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2         | 10%     |
| Intel Core i3           | 2         | 10%     |
| Intel Core 2 Duo        | 2         | 10%     |
| Intel Celeron           | 2         | 10%     |
| Intel Atom              | 2         | 10%     |
| Other                   | 1         | 5%      |
| Intel Pentium M         | 1         | 5%      |
| Intel Pentium III       | 1         | 5%      |
| Intel Pentium Dual-Core | 1         | 5%      |
| Intel Core 2            | 1         | 5%      |
| AMD V120                | 1         | 5%      |
| AMD E                   | 1         | 5%      |
| AMD C-70                | 1         | 5%      |
| AMD Athlon Neo          | 1         | 5%      |
| AMD A4                  | 1         | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 11        | 55%     |
| 4      | 5         | 25%     |
| 1      | 4         | 20%     |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 20        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 15        | 75%     |
| 2      | 5         | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 18        | 90%     |
| 32-bit         | 2         | 10%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x6fd      | 2         | 10%     |
| 0x30678    | 2         | 10%     |
| 0x206a7    | 2         | 10%     |
| Unknown    | 2         | 10%     |
| 0x806c1    | 1         | 5%      |
| 0x706a8    | 1         | 5%      |
| 0x6f6      | 1         | 5%      |
| 0x695      | 1         | 5%      |
| 0x68a      | 1         | 5%      |
| 0x40651    | 1         | 5%      |
| 0x20655    | 1         | 5%      |
| 0x1067a    | 1         | 5%      |
| 0x06006705 | 1         | 5%      |
| 0x05000119 | 1         | 5%      |
| 0x0500010d | 1         | 5%      |
| 0x010000c8 | 1         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 3         | 15%     |
| Core          | 3         | 15%     |
| SandyBridge   | 2         | 10%     |
| P6            | 2         | 10%     |
| Bobcat        | 2         | 10%     |
| Westmere      | 1         | 5%      |
| TigerLake     | 1         | 5%      |
| Penryn        | 1         | 5%      |
| K8 Hammer     | 1         | 5%      |
| K10           | 1         | 5%      |
| Haswell       | 1         | 5%      |
| Goldmont plus | 1         | 5%      |
| Excavator     | 1         | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 11        | 52.38%  |
| AMD                              | 7         | 33.33%  |
| Silicon Integrated Systems [SiS] | 1         | 4.76%   |
| S3 Graphics                      | 1         | 4.76%   |
| Nvidia                           | 1         | 4.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 9.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 9.09%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 4.55%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                     | 1         | 4.55%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 4.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 4.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 4.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 4.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 4.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 4.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 4.55%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 4.55%   |
| AMD Wrestler [Radeon HD 7290]                                                            | 1         | 4.55%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 4.55%   |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 1         | 4.55%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 4.55%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                             | 1         | 4.55%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 4.55%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1         | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 9         | 45%     |
| 1 x AMD         | 6         | 30%     |
| Other           | 1         | 5%      |
| 1 x SiS         | 1         | 5%      |
| 1 x S3 Graphics | 1         | 5%      |
| 1 x Nvidia      | 1         | 5%      |
| Intel + AMD     | 1         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 17        | 85%     |
| Unknown     | 2         | 10%     |
| Proprietary | 1         | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 60%     |
| 0.01-0.5   | 7         | 35%     |
| 1.01-2.0   | 1         | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 27.78%  |
| Samsung Electronics | 3         | 16.67%  |
| LG Display          | 3         | 16.67%  |
| Chimei Innolux      | 3         | 16.67%  |
| Hewlett-Packard     | 1         | 5.56%   |
| HannStar            | 1         | 5.56%   |
| CPT                 | 1         | 5.56%   |
| BOE                 | 1         | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 2         | 11.11%  |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch   | 1         | 5.56%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch   | 1         | 5.56%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch | 1         | 5.56%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch            | 1         | 5.56%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch             | 1         | 5.56%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch               | 1         | 5.56%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                   | 1         | 5.56%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch       | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch        | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 1         | 5.56%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                   | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch         | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch         | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch          | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch          | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch          | 1         | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 7         | 38.89%  |
| 1920x1080 (FHD)   | 4         | 22.22%  |
| 1600x900 (HD+)    | 3         | 16.67%  |
| 1280x800 (WXGA)   | 2         | 11.11%  |
| 2160x1440         | 1         | 5.56%   |
| 1920x1200 (WUXGA) | 1         | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 8         | 44.44%  |
| 13     | 2         | 11.11%  |
| 11     | 2         | 11.11%  |
| 46     | 1         | 5.56%   |
| 24     | 1         | 5.56%   |
| 18     | 1         | 5.56%   |
| 17     | 1         | 5.56%   |
| 14     | 1         | 5.56%   |
| 12     | 1         | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 55.56%  |
| 201-300     | 4         | 22.22%  |
| 351-400     | 2         | 11.11%  |
| 501-600     | 1         | 5.56%   |
| 1001-1500   | 1         | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 13        | 76.47%  |
| 16/10 | 3         | 17.65%  |
| 3/2   | 1         | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 44.44%  |
| 81-90          | 3         | 16.67%  |
| 51-60          | 2         | 11.11%  |
| 61-70          | 1         | 5.56%   |
| 251-300        | 1         | 5.56%   |
| 141-150        | 1         | 5.56%   |
| 121-130        | 1         | 5.56%   |
| 501-1000       | 1         | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 8         | 44.44%  |
| 121-160 | 4         | 22.22%  |
| 51-100  | 3         | 16.67%  |
| 161-240 | 2         | 11.11%  |
| 1-50    | 1         | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 18        | 90%     |
| 2     | 1         | 5%      |
| 0     | 1         | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 13        | 39.39%  |
| Qualcomm Atheros                 | 6         | 18.18%  |
| Intel                            | 6         | 18.18%  |
| Broadcom                         | 2         | 6.06%   |
| Xiaomi                           | 1         | 3.03%   |
| Silicon Integrated Systems [SiS] | 1         | 3.03%   |
| Motorola PCS                     | 1         | 3.03%   |
| LG Electronics                   | 1         | 3.03%   |
| JMicron Technology               | 1         | 3.03%   |
| Accton Technology                | 1         | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 4         | 11.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 8.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 8.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 5.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 2.86%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.86%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 2.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 2.86%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 1         | 2.86%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 2.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.86%   |
| Motorola PCS motorola edge                                              | 1         | 2.86%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 2.86%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 2.86%   |
| Intel Wireless 3165                                                     | 1         | 2.86%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 2.86%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2.86%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 1         | 2.86%   |
| Intel 82577LC Gigabit Network Connection                                | 1         | 2.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 2.86%   |
| Accton EN-1216 Ethernet Adapter                                         | 1         | 2.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 6         | 35.29%  |
| Realtek Semiconductor | 5         | 29.41%  |
| Intel                 | 5         | 29.41%  |
| Broadcom              | 1         | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 17.65%  |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 11.76%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 5.88%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 5.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 5.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 5.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 5.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 5.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 5.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 5.88%   |
| Intel Wireless 3165                                                     | 1         | 5.88%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 5.88%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 5.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 9         | 52.94%  |
| Xiaomi                           | 1         | 5.88%   |
| Silicon Integrated Systems [SiS] | 1         | 5.88%   |
| Motorola PCS                     | 1         | 5.88%   |
| LG Electronics                   | 1         | 5.88%   |
| JMicron Technology               | 1         | 5.88%   |
| Intel                            | 1         | 5.88%   |
| Broadcom                         | 1         | 5.88%   |
| Accton Technology                | 1         | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 23.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 17.65%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 5.88%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 5.88%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 5.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 5.88%   |
| Motorola PCS motorola edge                                        | 1         | 5.88%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 5.88%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 5.88%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 5.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 5.88%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 50%     |
| Ethernet | 16        | 47.06%  |
| Modem    | 1         | 2.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 54.84%  |
| Ethernet | 14        | 45.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 11        | 55%     |
| 1     | 7         | 35%     |
| 0     | 2         | 10%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 3         | 33.33%  |
| Realtek Semiconductor           | 2         | 22.22%  |
| Intel                           | 2         | 22.22%  |
| Hewlett-Packard                 | 1         | 11.11%  |
| ASUSTek Computer                | 1         | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth     | 3         | 33.33%  |
| Realtek Bluetooth Radio               | 2         | 22.22%  |
| Intel Bluetooth wireless interface    | 1         | 11.11%  |
| Intel AX200 Bluetooth                 | 1         | 11.11%  |
| HP Broadcom 2070 Bluetooth Combo      | 1         | 11.11%  |
| ASUS BT-183 Bluetooth 2.0+EDR adapter | 1         | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 11        | 57.89%  |
| AMD                              | 6         | 31.58%  |
| Silicon Integrated Systems [SiS] | 1         | 5.26%   |
| ESS Technology                   | 1         | 5.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 12%     |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 8%      |
| AMD Wrestler HDMI Audio                                                    | 2         | 8%      |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 4%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 4%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 4%      |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 4%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 4%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 4%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 4%      |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1         | 4%      |
| Intel 8 Series HD Audio Controller                                         | 1         | 4%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 4%      |
| ESS Technology ES1988 Allegro-1                                            | 1         | 4%      |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 4%      |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 4%      |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                           | 1         | 4%      |
| AMD High Definition Audio Controller                                       | 1         | 4%      |
| AMD FCH Azalia Controller                                                  | 1         | 4%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 7         | 36.84%  |
| Samsung Electronics | 4         | 21.05%  |
| SK Hynix            | 3         | 15.79%  |
| Kingston            | 2         | 10.53%  |
| Unknown (ABCD)      | 1         | 5.26%   |
| Elpida              | 1         | 5.26%   |
| A-DATA Technology   | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 9.52%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 9.52%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 4.76%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 4.76%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 4.76%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 4.76%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 4.76%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 4.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 4.76%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 4.76%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 4.76%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2400MT/s        | 1         | 4.76%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s         | 1         | 4.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 4.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 4.76%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 4.76%   |
| Kingston RAM 99U5428-041.A01G 4096MB SODIMM DDR3 1067MT/s        | 1         | 4.76%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM 1067MT/s                 | 1         | 4.76%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s             | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 8         | 44.44%  |
| SDRAM  | 3         | 16.67%  |
| DDR2   | 3         | 16.67%  |
| DDR4   | 2         | 11.11%  |
| LPDDR4 | 1         | 5.56%   |
| DRAM   | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 17        | 94.44%  |
| DIMM   | 1         | 5.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 8         | 40%     |
| 2048 | 7         | 35%     |
| 1024 | 3         | 15%     |
| 512  | 1         | 5%      |
| 256  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 5         | 26.32%  |
| 1334    | 3         | 15.79%  |
| 2400    | 2         | 10.53%  |
| 1600    | 2         | 10.53%  |
| 1333    | 2         | 10.53%  |
| 1067    | 2         | 10.53%  |
| 4199    | 1         | 5.26%   |
| 3200    | 1         | 5.26%   |
| 800     | 1         | 5.26%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2         | 22.22%  |
| Suyin                                  | 1         | 11.11%  |
| Silicon Motion                         | 1         | 11.11%  |
| Microdia                               | 1         | 11.11%  |
| IMC Networks                           | 1         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) | 1         | 11.11%  |
| Alcor Micro                            | 1         | 11.11%  |
| Acer                                   | 1         | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 11.11%  |
| Silicon Motion 300k Pixel Camera                            | 1         | 11.11%  |
| Microdia Webcam Vitade AF                                   | 1         | 11.11%  |
| IMC Networks HP TrueVision HD Camera                        | 1         | 11.11%  |
| Chicony Integrated Camera                                   | 1         | 11.11%  |
| Chicony HP HD Webcam                                        | 1         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 11.11%  |
| Alcor Micro USB 2.0 Camera                                  | 1         | 11.11%  |
| Acer USB Camera                                             | 1         | 11.11%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 50%     |
| Validity Sensors VFS451 Fingerprint Reader | 1         | 50%     |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 16        | 80%     |
| 2     | 2         | 10%     |
| 1     | 2         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 2         | 33.33%  |
| Fingerprint reader       | 2         | 33.33%  |
| Flash memory             | 1         | 16.67%  |
| Communication controller | 1         | 16.67%  |

