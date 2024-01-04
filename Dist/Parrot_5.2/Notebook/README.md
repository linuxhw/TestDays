Parrot 5.2 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Parrot 5.2.

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

Total: 33

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba   | PORTEGE R930                | [e341599417](https://linux-hardware.org/?probe=e341599417) | Dec 14, 2023 |
| ASUSTek   | Zenbook UM3402YAR_UM3402... | [da3ab01b3a](https://linux-hardware.org/?probe=da3ab01b3a) | Aug 25, 2023 |
| HP        | Laptop 15-dy2xxx            | [ea4a5ccb1a](https://linux-hardware.org/?probe=ea4a5ccb1a) | Jun 29, 2023 |
| Lenovo    | ThinkPad L520 78595GJ       | [52faa96ad0](https://linux-hardware.org/?probe=52faa96ad0) | Jun 17, 2023 |
| Lenovo    | ThinkPad X230 2325UYW       | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| Dell      | Latitude 7280               | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell      | Vostro 1550                 | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| HP        | ProBook 4540s               | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| HP        | ProBook 4540s               | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| Lenovo    | ThinkPad L15 Gen 3 21C3C... | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Lenovo    | ThinkPad E460 20ETA05KAU    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| Gigabyte  | AORUS 15P KD                | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Lenovo    | ThinkPad P14s Gen 3 21AK... | [04c16989b3](https://linux-hardware.org/?probe=04c16989b3) | Apr 06, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop X712... | [b307524661](https://linux-hardware.org/?probe=b307524661) | Apr 06, 2023 |
| Acer      | Extensa 215-54              | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| Google    | Lillipup                    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Lenovo    | Legion 5 15ACH6 82JW        | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek   | X510UAR                     | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP        | ZBook Firefly 14 inch G9... | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo    | ThinkPad P15v Gen 3 21D8... | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI       | Katana GF66 12UC            | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Lenovo    | IdeaPad 5 15IAL7 82SF       | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo    | IdeaPad 5 15IAL7 82SF       | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP        | ZBook Firefly 15.6 inch ... | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer      | Aspire E5-575               | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo    | Legion 5 15ACH6 82JW        | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo    | Legion 5 15ACH6 82JW        | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP        | Pavilion 15                 | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| Lenovo    | ThinkPad E15 Gen 4 21ED0... | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Dell      | Inspiron 3421               | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware | 17 R5                       | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware | 17 R5                       | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| Google    | Robo360                     | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 6.0.0-12parrot1-amd64 | 25        | 96.15%  |
| 6.1.0-0.deb11.5-amd64 | 1         | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.0   | 25        | 96.15%  |
| 6.1.0   | 1         | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 25        | 96.15%  |
| 6.1     | 1         | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 26        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MATE | 24        | 92.31%  |
| KDE5 | 2         | 7.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 26        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 20        | 76.92%  |
| Unknown | 5         | 19.23%  |
| SDDM    | 1         | 3.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 15        | 57.69%  |
| en_IN | 2         | 7.69%   |
| en_AU | 2         | 7.69%   |
| tr_TR | 1         | 3.85%   |
| es_ES | 1         | 3.85%   |
| es_AR | 1         | 3.85%   |
| en_ZM | 1         | 3.85%   |
| en_GB | 1         | 3.85%   |
| de_DE | 1         | 3.85%   |
| cs_CZ | 1         | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 17        | 65.38%  |
| BIOS | 9         | 34.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 23        | 88.46%  |
| Xfs     | 1         | 3.85%   |
| Overlay | 1         | 3.85%   |
| Ext4    | 1         | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 18        | 69.23%  |
| Unknown | 5         | 19.23%  |
| MBR     | 3         | 11.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 92.31%  |
| Yes       | 2         | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 57.69%  |
| Yes       | 11        | 42.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 9         | 34.62%  |
| Hewlett-Packard     | 4         | 15.38%  |
| Dell                | 3         | 11.54%  |
| ASUSTek Computer    | 3         | 11.54%  |
| Acer                | 2         | 7.69%   |
| Toshiba             | 1         | 3.85%   |
| MSI                 | 1         | 3.85%   |
| Google              | 1         | 3.85%   |
| Gigabyte Technology | 1         | 3.85%   |
| Alienware           | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba PORTEGE R930                                | 1         | 3.85%   |
| MSI Katana GF66 12UC                                | 1         | 3.85%   |
| Lenovo ThinkPad X230 2325UYW                        | 1         | 3.85%   |
| Lenovo ThinkPad P15v Gen 3 21D8CTO1WW               | 1         | 3.85%   |
| Lenovo ThinkPad P14s Gen 3 21AKCTO1WW               | 1         | 3.85%   |
| Lenovo ThinkPad L520 78595GJ                        | 1         | 3.85%   |
| Lenovo ThinkPad L15 Gen 3 21C3CTO1WW                | 1         | 3.85%   |
| Lenovo ThinkPad E460 20ETA05KAU                     | 1         | 3.85%   |
| Lenovo ThinkPad E15 Gen 4 21ED003YUS                | 1         | 3.85%   |
| Lenovo Legion 5 15ACH6 82JW                         | 1         | 3.85%   |
| Lenovo IdeaPad 5 15IAL7 82SF                        | 1         | 3.85%   |
| HP ZBook Firefly 15.6 inch G8 Mobile Workstation PC | 1         | 3.85%   |
| HP ZBook Firefly 14 inch G9 Mobile Workstation PC   | 1         | 3.85%   |
| HP ProBook 4540s                                    | 1         | 3.85%   |
| HP Pavilion 15                                      | 1         | 3.85%   |
| Google Lillipup                                     | 1         | 3.85%   |
| Gigabyte AORUS 15P KD                               | 1         | 3.85%   |
| Dell Vostro 1550                                    | 1         | 3.85%   |
| Dell Latitude 7280                                  | 1         | 3.85%   |
| Dell Inspiron 3421                                  | 1         | 3.85%   |
| ASUS Zenbook UM3402YAR_UM3402YA                     | 1         | 3.85%   |
| ASUS X510UAR                                        | 1         | 3.85%   |
| ASUS VivoBook_ASUSLaptop X712DA_M712DA              | 1         | 3.85%   |
| Alienware 17 R5                                     | 1         | 3.85%   |
| Acer Extensa 215-54                                 | 1         | 3.85%   |
| Acer Aspire E5-575                                  | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 7         | 26.92%  |
| HP ZBook        | 2         | 7.69%   |
| Toshiba PORTEGE | 1         | 3.85%   |
| MSI Katana      | 1         | 3.85%   |
| Lenovo Legion   | 1         | 3.85%   |
| Lenovo IdeaPad  | 1         | 3.85%   |
| HP ProBook      | 1         | 3.85%   |
| HP Pavilion     | 1         | 3.85%   |
| Google Lillipup | 1         | 3.85%   |
| Gigabyte AORUS  | 1         | 3.85%   |
| Dell Vostro     | 1         | 3.85%   |
| Dell Latitude   | 1         | 3.85%   |
| Dell Inspiron   | 1         | 3.85%   |
| ASUS Zenbook    | 1         | 3.85%   |
| ASUS X510UAR    | 1         | 3.85%   |
| ASUS VivoBook   | 1         | 3.85%   |
| Alienware 17    | 1         | 3.85%   |
| Acer Extensa    | 1         | 3.85%   |
| Acer Aspire     | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 8         | 30.77%  |
| 2012 | 4         | 15.38%  |
| 2021 | 3         | 11.54%  |
| 2016 | 2         | 7.69%   |
| 2023 | 1         | 3.85%   |
| 2020 | 1         | 3.85%   |
| 2019 | 1         | 3.85%   |
| 2018 | 1         | 3.85%   |
| 2017 | 1         | 3.85%   |
| 2015 | 1         | 3.85%   |
| 2014 | 1         | 3.85%   |
| 2013 | 1         | 3.85%   |
| 2011 | 1         | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 26        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 26        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 96.15%  |
| Yes  | 1         | 3.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 7         | 26.92%  |
| 16.01-24.0  | 6         | 23.08%  |
| 32.01-64.0  | 4         | 15.38%  |
| 8.01-16.0   | 4         | 15.38%  |
| 3.01-4.0    | 3         | 11.54%  |
| 64.01-256.0 | 1         | 3.85%   |
| 1.01-2.0    | 1         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 11        | 42.31%  |
| 4.01-8.0  | 7         | 26.92%  |
| 1.01-2.0  | 4         | 15.38%  |
| 3.01-4.0  | 2         | 7.69%   |
| 8.01-16.0 | 1         | 3.85%   |
| 0.51-1.0  | 1         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 69.23%  |
| 2      | 8         | 30.77%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 76.92%  |
| Yes       | 6         | 23.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 84.62%  |
| No        | 4         | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 76.92%  |
| No        | 6         | 23.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| USA       | 9         | 34.62%  |
| India     | 2         | 7.69%   |
| Germany   | 2         | 7.69%   |
| Australia | 2         | 7.69%   |
| Zambia    | 1         | 3.85%   |
| UK        | 1         | 3.85%   |
| Turkey    | 1         | 3.85%   |
| Spain     | 1         | 3.85%   |
| Pakistan  | 1         | 3.85%   |
| Namibia   | 1         | 3.85%   |
| Mongolia  | 1         | 3.85%   |
| Czechia   | 1         | 3.85%   |
| Canada    | 1         | 3.85%   |
| Brazil    | 1         | 3.85%   |
| Argentina | 1         | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Windhoek     | 1         | 3.85%   |
| Ulan Bator   | 1         | 3.85%   |
| Tecumseh     | 1         | 3.85%   |
| Sydney       | 1         | 3.85%   |
| Spruce Grove | 1         | 3.85%   |
| Simpsonville | 1         | 3.85%   |
| Shelton      | 1         | 3.85%   |
| Seattle      | 1         | 3.85%   |
| Reading      | 1         | 3.85%   |
| Rawalpindi   | 1         | 3.85%   |
| Prague       | 1         | 3.85%   |
| Mercedes     | 1         | 3.85%   |
| Lusaka       | 1         | 3.85%   |
| León        | 1         | 3.85%   |
| Leland       | 1         | 3.85%   |
| Houston      | 1         | 3.85%   |
| Hamburg      | 1         | 3.85%   |
| Geneva       | 1         | 3.85%   |
| Fortaleza    | 1         | 3.85%   |
| Delhi        | 1         | 3.85%   |
| Canberra     | 1         | 3.85%   |
| Bursa        | 1         | 3.85%   |
| Brent        | 1         | 3.85%   |
| Bettingen    | 1         | 3.85%   |
| Bankura      | 1         | 3.85%   |
| Andover      | 1         | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 7         | 9      | 20%     |
| Seagate                     | 4         | 4      | 11.43%  |
| Kingston                    | 4         | 4      | 11.43%  |
| Micron Technology           | 3         | 3      | 8.57%   |
| Toshiba                     | 2         | 2      | 5.71%   |
| SanDisk                     | 2         | 2      | 5.71%   |
| KIOXIA                      | 2         | 2      | 5.71%   |
| WDC                         | 1         | 1      | 2.86%   |
| Unknown (583)               | 1         | 1      | 2.86%   |
| Unknown                     | 1         | 1      | 2.86%   |
| SK hynix                    | 1         | 1      | 2.86%   |
| Phison                      | 1         | 1      | 2.86%   |
| Lexar                       | 1         | 1      | 2.86%   |
| Kingston Technology Company | 1         | 1      | 2.86%   |
| KingFast                    | 1         | 1      | 2.86%   |
| HGST                        | 1         | 1      | 2.86%   |
| Hewlett-Packard             | 1         | 1      | 2.86%   |
| Apacer                      | 1         | 1      | 2.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 5.71%   |
| WDC WD6400BPVT-60HXZT3 640GB            | 1         | 2.86%   |
| Unknown HBG4a2  32GB                    | 1         | 2.86%   |
| Unknown (583) Disk 2TB                  | 1         | 2.86%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 2.86%   |
| Toshiba MK3261GSYN 320GB                | 1         | 2.86%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB    | 1         | 2.86%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2.86%   |
| Seagate BUP Slim BK 1TB                 | 1         | 2.86%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD     | 1         | 2.86%   |
| SanDisk NVMe SSD Drive 1TB              | 1         | 2.86%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 2.86%   |
| Samsung SSD 970 EVO 1TB                 | 1         | 2.86%   |
| Samsung MZVLQ256HBJD-00BH1 256GB        | 1         | 2.86%   |
| Samsung MZVL2512HCJQ-00BL7 512GB        | 1         | 2.86%   |
| Samsung MZVL2512HCJQ-00B00 512GB        | 1         | 2.86%   |
| Samsung MZAL4512HBLU-00BL2 512GB        | 1         | 2.86%   |
| Samsung MZ7TY256HDHP-000L7 256GB SSD    | 1         | 2.86%   |
| Phison Dash Pro 2TB                     | 1         | 2.86%   |
| Micron MTFDKCD1T0TFK 1024GB             | 1         | 2.86%   |
| Micron 2450_MTFDKBA1T0TFK 1TB           | 1         | 2.86%   |
| Micron 2400_MTFDKBA512QFM 512GB         | 1         | 2.86%   |
| Lexar SSD NS100 512GB                   | 1         | 2.86%   |
| KIOXIA KXG60ZNV1T02 1TB                 | 1         | 2.86%   |
| KIOXIA KBG5AZNT512G LA 512GB            | 1         | 2.86%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB | 1         | 2.86%   |
| Kingston SNVS500G 500GB                 | 1         | 2.86%   |
| Kingston SNV2S500G 500GB                | 1         | 2.86%   |
| Kingston OM8PCP3512F-AB 512GB           | 1         | 2.86%   |
| Kingston A400 960G SSD                  | 1         | 2.86%   |
| KingFast Disk 256GB SSD                 | 1         | 2.86%   |
| HGST HTS721010A9E630 1TB                | 1         | 2.86%   |
| HP SSD S700 Pro 1TB                     | 1         | 2.86%   |
| Apacer AS350 256GB SSD                  | 1         | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| Toshiba | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Lexar               | 1         | 1      | 14.29%  |
| Kingston            | 1         | 1      | 14.29%  |
| KingFast            | 1         | 1      | 14.29%  |
| Hewlett-Packard     | 1         | 1      | 14.29%  |
| Apacer              | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 16        | 21     | 50%     |
| HDD  | 8         | 8      | 25%     |
| SSD  | 7         | 7      | 21.88%  |
| MMC  | 1         | 1      | 3.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 16        | 20     | 50%     |
| SATA | 12        | 13     | 37.5%   |
| SAS  | 3         | 3      | 9.38%   |
| MMC  | 1         | 1      | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 7         | 7      | 50%     |
| 0.01-0.5   | 7         | 8      | 50%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 7         | 26.92%  |
| 251-500        | 5         | 19.23%  |
| 1001-2000      | 5         | 19.23%  |
| 101-250        | 3         | 11.54%  |
| Unknown        | 3         | 11.54%  |
| 1-20           | 2         | 7.69%   |
| More than 3000 | 1         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 11        | 42.31%  |
| 51-100    | 4         | 15.38%  |
| 1-20      | 3         | 11.54%  |
| Unknown   | 3         | 11.54%  |
| 101-250   | 2         | 7.69%   |
| 2001-3000 | 1         | 3.85%   |
| 501-1000  | 1         | 3.85%   |
| 0         | 1         | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 33.33%  |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 33.33%  |
| Hewlett-Packard SSD S700 Pro 1TB    | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| Toshiba         | 1         | 1      | 33.33%  |
| Seagate         | 1         | 1      | 33.33%  |
| Hewlett-Packard | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Works    | 19        | 24     | 61.29%  |
| Detected | 9         | 10     | 29.03%  |
| Malfunc  | 3         | 3      | 9.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 16        | 44.44%  |
| Samsung Electronics          | 6         | 16.67%  |
| Kingston Technology Company  | 4         | 11.11%  |
| Micron Technology            | 3         | 8.33%   |
| AMD                          | 2         | 5.56%   |
| Toshiba America Info Systems | 1         | 2.78%   |
| SK hynix                     | 1         | 2.78%   |
| SanDisk                      | 1         | 2.78%   |
| Phison Electronics           | 1         | 2.78%   |
| KIOXIA                       | 1         | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 4         | 10.53%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 10.53%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 5.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 5.26%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 2         | 5.26%   |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 5.26%   |
| Intel Alder Lake-P SATA AHCI Controller                                      | 2         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 5.26%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 5.26%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 2.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 1         | 2.63%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD      | 1         | 2.63%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                | 1         | 2.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 1         | 2.63%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 2.63%   |
| Micron 2400 NVMe SSD (DRAM-less)                                             | 1         | 2.63%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                   | 1         | 2.63%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                | 1         | 2.63%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 2.63%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                       | 1         | 2.63%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                       | 1         | 2.63%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 2.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 2.63%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]              | 1         | 2.63%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]              | 1         | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 16        | 45.71%  |
| SATA | 16        | 45.71%  |
| RAID | 2         | 5.71%   |
| IDE  | 1         | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 84.62%  |
| AMD    | 4         | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                 | 2         | 7.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 3.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 3.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 3.85%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 3.85%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 3.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 3.85%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 3.85%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 3.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 3.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 3.85%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 3.85%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 3.85%   |
| Intel 12th Gen Core i7-1265U                  | 1         | 3.85%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 3.85%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 3.85%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 3.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 3.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 3.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.85%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 3.85%   |
| AMD Ryzen 7 7730U with Radeon Graphics        | 1         | 3.85%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 3.85%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 3.85%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Other         | 10        | 38.46%  |
| Intel Core i5 | 5         | 19.23%  |
| Intel Core i3 | 5         | 19.23%  |
| AMD Ryzen 7   | 3         | 11.54%  |
| Intel Core i7 | 2         | 7.69%   |
| AMD Ryzen 5   | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 11        | 42.31%  |
| 4      | 4         | 15.38%  |
| 10     | 3         | 11.54%  |
| 8      | 3         | 11.54%  |
| 14     | 2         | 7.69%   |
| 6      | 2         | 7.69%   |
| 12     | 1         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 26        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 20        | 76.92%  |
| 1      | 6         | 23.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 26        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 26.92%  |
| 0x906a4    | 3         | 11.54%  |
| 0x906a3    | 3         | 11.54%  |
| 0x306a9    | 3         | 11.54%  |
| 0x806c1    | 2         | 7.69%   |
| 0x0a50000c | 2         | 7.69%   |
| 0x906ea    | 1         | 3.85%   |
| 0x806ea    | 1         | 3.85%   |
| 0x806e9    | 1         | 3.85%   |
| 0x806d1    | 1         | 3.85%   |
| 0x406e3    | 1         | 3.85%   |
| 0x08108102 | 1         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Alderlake Hybrid | 6         | 23.08%  |
| IvyBridge        | 4         | 15.38%  |
| Zen 3            | 3         | 11.54%  |
| TigerLake        | 3         | 11.54%  |
| SandyBridge      | 3         | 11.54%  |
| KabyLake         | 3         | 11.54%  |
| Skylake          | 2         | 7.69%   |
| Zen+             | 1         | 3.85%   |
| Icelake          | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 62.86%  |
| Nvidia | 7         | 20%     |
| AMD    | 6         | 17.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 11.43%  |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 3         | 8.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 8.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 5.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 5.71%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 5.71%   |
| AMD Barcelo                                                                           | 2         | 5.71%   |
| Nvidia TU117GLM [T600 Laptop GPU]                                                     | 1         | 2.86%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                     | 1         | 2.86%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 2.86%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                              | 1         | 2.86%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 2.86%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                           | 1         | 2.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 2.86%   |
| Intel UHD Graphics 620                                                                | 1         | 2.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 2.86%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 1         | 2.86%   |
| Intel HD Graphics 620                                                                 | 1         | 2.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 2.86%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 1         | 2.86%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 2.86%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 1         | 2.86%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 50%     |
| Intel + Nvidia | 5         | 19.23%  |
| Intel + AMD    | 3         | 11.54%  |
| 1 x AMD        | 3         | 11.54%  |
| 1 x Nvidia     | 2         | 7.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 25        | 96.15%  |
| Proprietary | 1         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 61.54%  |
| 3.01-4.0   | 5         | 19.23%  |
| 0.51-1.0   | 2         | 7.69%   |
| 7.01-8.0   | 1         | 3.85%   |
| 5.01-6.0   | 1         | 3.85%   |
| 1.01-2.0   | 1         | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| LG Display           | 7         | 25%     |
| AU Optronics         | 5         | 17.86%  |
| BOE                  | 4         | 14.29%  |
| Chimei Innolux       | 3         | 10.71%  |
| Samsung Electronics  | 2         | 7.14%   |
| VIZ                  | 1         | 3.57%   |
| Sharp                | 1         | 3.57%   |
| Pixio                | 1         | 3.57%   |
| Element              | 1         | 3.57%   |
| Dell                 | 1         | 3.57%   |
| CSO                  | 1         | 3.57%   |
| BOE Technology Group | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 2         | 7.14%   |
| VIZ LCD Monitor VA19L HDTV10T                                         | 1         | 3.57%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch  | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 3.57%   |
| Pixio SFP24DFI FLAT WAM2380 1920x1080 527x296mm 23.8-inch             | 1         | 3.57%   |
| LG Display LCD Monitor LGD06E4 1920x1080 344x194mm 15.5-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD0505 1366x768 344x194mm 15.5-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch           | 1         | 3.57%   |
| Element ELEFW195 ELE3553 1920x1080 708x398mm 32.0-inch                | 1         | 3.57%   |
| Dell P2314T DEL409E 1920x1080 509x286mm 23.0-inch                     | 1         | 3.57%   |
| CSO LCD Monitor CSO1506 1920x1080 344x194mm 15.5-inch                 | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch       | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15AA 1366x768 344x194mm 15.5-inch       | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 1         | 3.57%   |
| BOE Technology Group LCD Monitor 3200x1080                            | 1         | 3.57%   |
| BOE LCD Monitor BOE0AB0 1920x1080 344x194mm 15.5-inch                 | 1         | 3.57%   |
| BOE LCD Monitor BOE0A64 1920x1080 344x194mm 15.5-inch                 | 1         | 3.57%   |
| AU Optronics LCD Monitor AUOE3A0 3840x2400 301x188mm 14.0-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO662D 1920x1080 293x165mm 13.2-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO5A99 1920x1200 301x188mm 14.0-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO1496 2560x1440 382x214mm 17.2-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 12        | 42.86%  |
| 1366x768 (WXGA)   | 8         | 28.57%  |
| 3840x2400         | 1         | 3.57%   |
| 3840x2160 (4K)    | 1         | 3.57%   |
| 3200x1080         | 1         | 3.57%   |
| 2880x1800         | 1         | 3.57%   |
| 2560x1440 (QHD)   | 1         | 3.57%   |
| 1920x1200 (WUXGA) | 1         | 3.57%   |
| 1600x900 (HD+)    | 1         | 3.57%   |
| Unknown           | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 14        | 51.85%  |
| 14      | 4         | 14.81%  |
| 17      | 2         | 7.41%   |
| 12      | 2         | 7.41%   |
| 32      | 1         | 3.7%    |
| 27      | 1         | 3.7%    |
| 23      | 1         | 3.7%    |
| 13      | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 18        | 66.67%  |
| 201-300     | 3         | 11.11%  |
| 501-600     | 2         | 7.41%   |
| 351-400     | 2         | 7.41%   |
| 701-800     | 1         | 3.7%    |
| Unknown     | 1         | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 21        | 84%     |
| 16/10   | 3         | 12%     |
| Unknown | 1         | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 14        | 51.85%  |
| 81-90          | 4         | 14.81%  |
| 61-70          | 2         | 7.41%   |
| 121-130        | 2         | 7.41%   |
| 71-80          | 1         | 3.7%    |
| 351-500        | 1         | 3.7%    |
| 301-350        | 1         | 3.7%    |
| 201-250        | 1         | 3.7%    |
| Unknown        | 1         | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 11        | 40.74%  |
| 101-120       | 7         | 25.93%  |
| 161-240       | 4         | 14.81%  |
| More than 240 | 2         | 7.41%   |
| 51-100        | 2         | 7.41%   |
| Unknown       | 1         | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 23        | 88.46%  |
| 2     | 3         | 11.54%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 36.36%  |
| Realtek Semiconductor | 13        | 29.55%  |
| Qualcomm Atheros      | 4         | 9.09%   |
| OPPO Electronics      | 3         | 6.82%   |
| MediaTek              | 2         | 4.55%   |
| Xiaomi                | 1         | 2.27%   |
| Ralink                | 1         | 2.27%   |
| Qualcomm              | 1         | 2.27%   |
| Mercucys              | 1         | 2.27%   |
| Google                | 1         | 2.27%   |
| Broadcom Limited      | 1         | 2.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 7         | 12.96%  |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 6         | 11.11%  |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 5.56%   |
| Intel Ethernet Connection (16) I219-V                                                         | 3         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2         | 3.7%    |
| OPPO RMX3710                                                                                  | 2         | 3.7%    |
| Intel Wireless 8265 / 8275                                                                    | 2         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 2         | 3.7%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                          | 1         | 1.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 1.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 1.85%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 1.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 1.85%   |
| Qualcomm CAPE-MTP _SN:14677F87                                                                | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 1.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 1.85%   |
| OPPO SM8350-IDP _SN:27BAACC8                                                                  | 1         | 1.85%   |
| Mercucys 802.11n NIC                                                                          | 1         | 1.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 1.85%   |
| Intel Wireless 8260                                                                           | 1         | 1.85%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 1.85%   |
| Intel Ethernet Connection I219-V                                                              | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                                                         | 1         | 1.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 1.85%   |
| Intel Centrino Advanced-N 6235                                                                | 1         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 1         | 1.85%   |
| Google Pixel 7 Pro                                                                            | 1         | 1.85%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 55.17%  |
| Realtek Semiconductor | 4         | 13.79%  |
| Qualcomm Atheros      | 4         | 13.79%  |
| MediaTek              | 2         | 6.9%    |
| Ralink                | 1         | 3.45%   |
| Mercucys              | 1         | 3.45%   |
| Broadcom Limited      | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 6         | 20.69%  |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 10.34%  |
| Intel Wireless 8265 / 8275                                                                    | 2         | 6.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 3.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 3.45%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 3.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 3.45%   |
| Mercucys 802.11n NIC                                                                          | 1         | 3.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 3.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 3.45%   |
| Intel Wireless 8260                                                                           | 1         | 3.45%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 3.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 3.45%   |
| Intel Centrino Advanced-N 6235                                                                | 1         | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 1         | 3.45%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 11        | 44%     |
| Intel                 | 7         | 28%     |
| OPPO Electronics      | 3         | 12%     |
| Xiaomi                | 1         | 4%      |
| Qualcomm Atheros      | 1         | 4%      |
| Qualcomm              | 1         | 4%      |
| Google                | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 28%     |
| Intel Ethernet Connection (16) I219-V                             | 3         | 12%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 8%      |
| OPPO RMX3710                                                      | 2         | 8%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 8%      |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 4%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 4%      |
| Qualcomm CAPE-MTP _SN:14677F87                                    | 1         | 4%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 4%      |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 1         | 4%      |
| Intel Ethernet Connection I219-V                                  | 1         | 4%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4%      |
| Google Pixel 7 Pro                                                | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 54.17%  |
| Ethernet | 22        | 45.83%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 62.5%   |
| Ethernet | 9         | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 69.23%  |
| 1     | 8         | 30.77%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 80.77%  |
| Yes  | 5         | 19.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 55%     |
| Qualcomm Atheros Communications | 2         | 10%     |
| IMC Networks                    | 2         | 10%     |
| Realtek Semiconductor           | 1         | 5%      |
| Ralink                          | 1         | 5%      |
| Lite-On Technology              | 1         | 5%      |
| Foxconn / Hon Hai               | 1         | 5%      |
| Broadcom                        | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                         | 5         | 25%     |
| Intel Bluetooth wireless interface             | 3         | 15%     |
| Realtek Bluetooth Radio                        | 1         | 5%      |
| Ralink RT3290 Bluetooth                        | 1         | 5%      |
| Qualcomm Atheros  Bluetooth Device             | 1         | 5%      |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 5%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 5%      |
| Intel AX200 Bluetooth                          | 1         | 5%      |
| IMC Networks Wireless_Device                   | 1         | 5%      |
| IMC Networks Bluetooth Radio                   | 1         | 5%      |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 5%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 75.86%  |
| AMD    | 4         | 13.79%  |
| Nvidia | 3         | 10.34%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 18.75%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 15.63%  |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 12.5%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 12.5%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 9.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 6.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 6.25%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 3.13%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 3.13%   |
| Nvidia Audio device                                                        | 1         | 3.13%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 32.14%  |
| SK hynix            | 7         | 25%     |
| Micron Technology   | 5         | 17.86%  |
| Crucial             | 2         | 7.14%   |
| Smart               | 1         | 3.57%   |
| Kingston            | 1         | 3.57%   |
| fef5                | 1         | 3.57%   |
| Elpida              | 1         | 3.57%   |
| A-DATA Technology   | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s        | 1         | 3.45%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                | 1         | 3.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 3.45%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s       | 1         | 3.45%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 3.45%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 3.45%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 1         | 3.45%   |
| Samsung RAM Module 1GB Row Of Chips LPDDR4 3733MT/s          | 1         | 3.45%   |
| Samsung RAM Module 16GB SODIMM 4800MT/s                      | 1         | 3.45%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 1         | 3.45%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s        | 1         | 3.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 3.45%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 3.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 3.45%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 3.45%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s       | 1         | 3.45%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s              | 1         | 3.45%   |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s       | 1         | 3.45%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s | 1         | 3.45%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s        | 1         | 3.45%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s        | 1         | 3.45%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s       | 1         | 3.45%   |
| Kingston RAM 9905428-086.A00LF 4GB SODIMM DDR3 1600MT/s      | 1         | 3.45%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                        | 1         | 3.45%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s        | 1         | 3.45%   |
| Crucial RAM CT8G4SFS832A.M8FRS 8GB SODIMM DDR4 3200MT/s      | 1         | 3.45%   |
| Crucial RAM CT32G4SFD832A.C16FF 32GB SODIMM DDR4 3200MT/s    | 1         | 3.45%   |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 13        | 56.52%  |
| DDR3    | 4         | 17.39%  |
| LPDDR4  | 3         | 13.04%  |
| Unknown | 2         | 8.7%    |
| DDR5    | 1         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 86.36%  |
| Row Of Chips | 2         | 9.09%   |
| Unknown      | 1         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 9         | 34.62%  |
| 4096  | 6         | 23.08%  |
| 16384 | 5         | 19.23%  |
| 32768 | 3         | 11.54%  |
| 1024  | 2         | 7.69%   |
| 2048  | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 9         | 36%     |
| 2667  | 5         | 20%     |
| 1600  | 4         | 16%     |
| 4800  | 2         | 8%      |
| 4266  | 1         | 4%      |
| 3733  | 1         | 4%      |
| 2400  | 1         | 4%      |
| 2133  | 1         | 4%      |
| 1334  | 1         | 4%      |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 7         | 26.92%  |
| IMC Networks                  | 4         | 15.38%  |
| Sunplus Innovation Technology | 3         | 11.54%  |
| Realtek Semiconductor         | 3         | 11.54%  |
| Bison Electronics             | 2         | 7.69%   |
| Tobii Technology AB           | 1         | 3.85%   |
| Syntek                        | 1         | 3.85%   |
| Sonix Technology              | 1         | 3.85%   |
| Quanta                        | 1         | 3.85%   |
| Primax Electronics            | 1         | 3.85%   |
| Microdia                      | 1         | 3.85%   |
| 8SSC21D67422V1SR28902JL       | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                             | 4         | 15.38%  |
| IMC Networks USB2.0 HD UVC WebCam                                     | 2         | 7.69%   |
| Tobii AB Eyechip                                                      | 1         | 3.85%   |
| Syntek Integrated Camera                                              | 1         | 3.85%   |
| Sunplus TOSHIBA Web Camera - HD                                       | 1         | 3.85%   |
| Sunplus Laptop Integrated Webcam FHD                                  | 1         | 3.85%   |
| Sunplus Integrated_Webcam_HD                                          | 1         | 3.85%   |
| Sonix USB2.0 FHD UVC WebCam                                           | 1         | 3.85%   |
| Realtek Integrated Webcam_HD                                          | 1         | 3.85%   |
| Realtek Integrated Webcam HD                                          | 1         | 3.85%   |
| Realtek HD WebCam                                                     | 1         | 3.85%   |
| Quanta HD User Facing                                                 | 1         | 3.85%   |
| Primax HP HD Webcam [Fixed]                                           | 1         | 3.85%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 3.85%   |
| IMC Networks VGA UVC WebCam                                           | 1         | 3.85%   |
| IMC Networks Integrated Camera                                        | 1         | 3.85%   |
| Chicony HP Truevision HD                                              | 1         | 3.85%   |
| Chicony HP HD Camera                                                  | 1         | 3.85%   |
| Chicony HP 5MP Camera                                                 | 1         | 3.85%   |
| Bison Integrated Camera                                               | 1         | 3.85%   |
| Bison HD Webcam                                                       | 1         | 3.85%   |
| 8SSC21D67422V1SR28902JL Integrated RGB Camera                         | 1         | 3.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Synaptics | 4         | 66.67%  |
| Upek      | 1         | 16.67%  |
| AuthenTec | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 33.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 16.67%  |
| Synaptics UWP WBDI Device                                | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 16.67%  |
| AuthenTec Fingerprint Sensor                             | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Upek        | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 14        | 53.85%  |
| 1     | 10        | 38.46%  |
| 2     | 2         | 7.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 6         | 42.86%  |
| Net/wireless       | 3         | 21.43%  |
| Net/ethernet       | 2         | 14.29%  |
| Chipcard           | 2         | 14.29%  |
| Bluetooth          | 1         | 7.14%   |

