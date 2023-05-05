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

Total: 27

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| 6.0.0-12parrot1-amd64 | 20        | 95.24%  |
| 6.1.0-0.deb11.5-amd64 | 1         | 4.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.0   | 20        | 95.24%  |
| 6.1.0   | 1         | 4.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 20        | 95.24%  |
| 6.1     | 1         | 4.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 21        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MATE | 19        | 90.48%  |
| KDE5 | 2         | 9.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 21        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 17        | 80.95%  |
| Unknown | 3         | 14.29%  |
| SDDM    | 1         | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 11        | 52.38%  |
| en_IN | 2         | 9.52%   |
| en_AU | 2         | 9.52%   |
| tr_TR | 1         | 4.76%   |
| es_ES | 1         | 4.76%   |
| es_AR | 1         | 4.76%   |
| en_GB | 1         | 4.76%   |
| de_DE | 1         | 4.76%   |
| cs_CZ | 1         | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 16        | 76.19%  |
| BIOS | 5         | 23.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 19        | 90.48%  |
| Xfs   | 1         | 4.76%   |
| Ext4  | 1         | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 17        | 80.95%  |
| Unknown | 3         | 14.29%  |
| MBR     | 1         | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 90.48%  |
| Yes       | 2         | 9.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11        | 52.38%  |
| Yes       | 10        | 47.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 7         | 33.33%  |
| Hewlett-Packard     | 4         | 19.05%  |
| Dell                | 2         | 9.52%   |
| ASUSTek Computer    | 2         | 9.52%   |
| Acer                | 2         | 9.52%   |
| MSI                 | 1         | 4.76%   |
| Google              | 1         | 4.76%   |
| Gigabyte Technology | 1         | 4.76%   |
| Alienware           | 1         | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| MSI Katana GF66 12UC                                | 1         | 4.76%   |
| Lenovo ThinkPad P15v Gen 3 21D8CTO1WW               | 1         | 4.76%   |
| Lenovo ThinkPad P14s Gen 3 21AKCTO1WW               | 1         | 4.76%   |
| Lenovo ThinkPad L15 Gen 3 21C3CTO1WW                | 1         | 4.76%   |
| Lenovo ThinkPad E460 20ETA05KAU                     | 1         | 4.76%   |
| Lenovo ThinkPad E15 Gen 4 21ED003YUS                | 1         | 4.76%   |
| Lenovo Legion 5 15ACH6 82JW                         | 1         | 4.76%   |
| Lenovo IdeaPad 5 15IAL7 82SF                        | 1         | 4.76%   |
| HP ZBook Firefly 15.6 inch G8 Mobile Workstation PC | 1         | 4.76%   |
| HP ZBook Firefly 14 inch G9 Mobile Workstation PC   | 1         | 4.76%   |
| HP ProBook 4540s                                    | 1         | 4.76%   |
| HP Pavilion 15                                      | 1         | 4.76%   |
| Google Lillipup                                     | 1         | 4.76%   |
| Gigabyte AORUS 15P KD                               | 1         | 4.76%   |
| Dell Vostro 1550                                    | 1         | 4.76%   |
| Dell Inspiron 3421                                  | 1         | 4.76%   |
| ASUS X510UAR                                        | 1         | 4.76%   |
| ASUS VivoBook_ASUSLaptop X712DA_M712DA              | 1         | 4.76%   |
| Alienware 17 R5                                     | 1         | 4.76%   |
| Acer Extensa 215-54                                 | 1         | 4.76%   |
| Acer Aspire E5-575                                  | 1         | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 5         | 23.81%  |
| HP ZBook        | 2         | 9.52%   |
| MSI Katana      | 1         | 4.76%   |
| Lenovo Legion   | 1         | 4.76%   |
| Lenovo IdeaPad  | 1         | 4.76%   |
| HP ProBook      | 1         | 4.76%   |
| HP Pavilion     | 1         | 4.76%   |
| Google Lillipup | 1         | 4.76%   |
| Gigabyte AORUS  | 1         | 4.76%   |
| Dell Vostro     | 1         | 4.76%   |
| Dell Inspiron   | 1         | 4.76%   |
| ASUS X510UAR    | 1         | 4.76%   |
| ASUS VivoBook   | 1         | 4.76%   |
| Alienware 17    | 1         | 4.76%   |
| Acer Extensa    | 1         | 4.76%   |
| Acer Aspire     | 1         | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 7         | 33.33%  |
| 2021 | 3         | 14.29%  |
| 2012 | 2         | 9.52%   |
| 2023 | 1         | 4.76%   |
| 2020 | 1         | 4.76%   |
| 2019 | 1         | 4.76%   |
| 2018 | 1         | 4.76%   |
| 2017 | 1         | 4.76%   |
| 2016 | 1         | 4.76%   |
| 2015 | 1         | 4.76%   |
| 2014 | 1         | 4.76%   |
| 2013 | 1         | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 21        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 21        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 95.24%  |
| Yes  | 1         | 4.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 6         | 28.57%  |
| 32.01-64.0  | 4         | 19.05%  |
| 4.01-8.0    | 3         | 14.29%  |
| 3.01-4.0    | 3         | 14.29%  |
| 8.01-16.0   | 3         | 14.29%  |
| 64.01-256.0 | 1         | 4.76%   |
| 1.01-2.0    | 1         | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 11        | 52.38%  |
| 4.01-8.0  | 3         | 14.29%  |
| 1.01-2.0  | 3         | 14.29%  |
| 3.01-4.0  | 2         | 9.52%   |
| 8.01-16.0 | 1         | 4.76%   |
| 0.51-1.0  | 1         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13        | 61.9%   |
| 2      | 8         | 38.1%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 80.95%  |
| Yes       | 4         | 19.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 80.95%  |
| No        | 4         | 19.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 76.19%  |
| No        | 5         | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| USA       | 8         | 38.1%   |
| India     | 2         | 9.52%   |
| Australia | 2         | 9.52%   |
| UK        | 1         | 4.76%   |
| Turkey    | 1         | 4.76%   |
| Spain     | 1         | 4.76%   |
| Namibia   | 1         | 4.76%   |
| Mongolia  | 1         | 4.76%   |
| Germany   | 1         | 4.76%   |
| Czechia   | 1         | 4.76%   |
| Brazil    | 1         | 4.76%   |
| Argentina | 1         | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City       | Notebooks | Percent |
|------------|-----------|---------|
| Windhoek   | 1         | 4.76%   |
| Ulan Bator | 1         | 4.76%   |
| Topeka     | 1         | 4.76%   |
| Sydney     | 1         | 4.76%   |
| Seattle    | 1         | 4.76%   |
| Reading    | 1         | 4.76%   |
| Orallo     | 1         | 4.76%   |
| Nezvestice | 1         | 4.76%   |
| Mercedes   | 1         | 4.76%   |
| London     | 1         | 4.76%   |
| Leland     | 1         | 4.76%   |
| Houston    | 1         | 4.76%   |
| Holsthum   | 1         | 4.76%   |
| Greenville | 1         | 4.76%   |
| Geneva     | 1         | 4.76%   |
| Fortaleza  | 1         | 4.76%   |
| Delhi      | 1         | 4.76%   |
| Canberra   | 1         | 4.76%   |
| Bursa      | 1         | 4.76%   |
| Bankura    | 1         | 4.76%   |
| Andover    | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 7         | 9      | 24.14%  |
| Seagate                     | 4         | 4      | 13.79%  |
| Kingston                    | 4         | 4      | 13.79%  |
| Micron Technology           | 2         | 2      | 6.9%    |
| KIOXIA                      | 2         | 2      | 6.9%    |
| Unknown (583)               | 1         | 1      | 3.45%   |
| Unknown                     | 1         | 1      | 3.45%   |
| Toshiba                     | 1         | 1      | 3.45%   |
| SK hynix                    | 1         | 1      | 3.45%   |
| SanDisk                     | 1         | 1      | 3.45%   |
| Phison                      | 1         | 1      | 3.45%   |
| Kingston Technology Company | 1         | 1      | 3.45%   |
| HGST                        | 1         | 1      | 3.45%   |
| Hewlett-Packard             | 1         | 1      | 3.45%   |
| Apacer                      | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 6.9%    |
| Unknown HBG4a2  32GB                    | 1         | 3.45%   |
| Unknown (583) Disk 2TB                  | 1         | 3.45%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 3.45%   |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB | 1         | 3.45%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 3.45%   |
| Seagate BUP Slim BK 1TB                 | 1         | 3.45%   |
| SanDisk NVMe SSD Drive 1TB              | 1         | 3.45%   |
| Samsung SSD 970 EVO Plus 1TB            | 1         | 3.45%   |
| Samsung SSD 970 EVO 1TB                 | 1         | 3.45%   |
| Samsung MZVLQ256HBJD-00BH1 256GB        | 1         | 3.45%   |
| Samsung MZVL2512HCJQ-00BL7 512GB        | 1         | 3.45%   |
| Samsung MZVL2512HCJQ-00B00 512GB        | 1         | 3.45%   |
| Samsung MZAL4512HBLU-00BL2 512GB        | 1         | 3.45%   |
| Samsung MZ7TY256HDHP-000L7 256GB SSD    | 1         | 3.45%   |
| Phison Dash Pro 2TB                     | 1         | 3.45%   |
| Micron MTFDKCD1T0TFK 1TB                | 1         | 3.45%   |
| Micron 2450_MTFDKBA1T0TFK 1TB           | 1         | 3.45%   |
| KIOXIA KXG60ZNV1T02 1TB                 | 1         | 3.45%   |
| KIOXIA KBG5AZNT512G LA 512GB            | 1         | 3.45%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB | 1         | 3.45%   |
| Kingston SNVS500G 500GB                 | 1         | 3.45%   |
| Kingston SNV2S500G 500GB                | 1         | 3.45%   |
| Kingston OM8PCP3512F-AB 512GB           | 1         | 3.45%   |
| Kingston A400 960G SSD                  | 1         | 3.45%   |
| HGST HTS721010A9E630 1TB                | 1         | 3.45%   |
| HP SSD S700 Pro 1TB                     | 1         | 3.45%   |
| Apacer AS350 256GB SSD                  | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 66.67%  |
| Toshiba | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 25%     |
| Kingston            | 1         | 1      | 25%     |
| Hewlett-Packard     | 1         | 1      | 25%     |
| Apacer              | 1         | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 20     | 57.69%  |
| HDD  | 6         | 6      | 23.08%  |
| SSD  | 4         | 4      | 15.38%  |
| MMC  | 1         | 1      | 3.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 15        | 19     | 57.69%  |
| SATA | 8         | 9      | 30.77%  |
| SAS  | 2         | 2      | 7.69%   |
| MMC  | 1         | 1      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 5         | 5      | 55.56%  |
| 0.01-0.5   | 4         | 5      | 44.44%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 5         | 23.81%  |
| 251-500        | 4         | 19.05%  |
| 1001-2000      | 4         | 19.05%  |
| 101-250        | 3         | 14.29%  |
| Unknown        | 3         | 14.29%  |
| More than 3000 | 1         | 4.76%   |
| 1-20           | 1         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 21-50     | 10        | 47.62%  |
| 51-100    | 3         | 14.29%  |
| Unknown   | 3         | 14.29%  |
| 1-20      | 2         | 9.52%   |
| 2001-3000 | 1         | 4.76%   |
| 101-250   | 1         | 4.76%   |
| 0         | 1         | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 50%     |
| Hewlett-Packard SSD S700 Pro 1TB    | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 1         | 1      | 50%     |
| Hewlett-Packard | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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
| Works    | 16        | 21     | 64%     |
| Detected | 7         | 8      | 28%     |
| Malfunc  | 2         | 2      | 8%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 12        | 38.71%  |
| Samsung Electronics          | 6         | 19.35%  |
| Kingston Technology Company  | 4         | 12.9%   |
| Micron Technology            | 2         | 6.45%   |
| AMD                          | 2         | 6.45%   |
| Toshiba America Info Systems | 1         | 3.23%   |
| SK hynix                     | 1         | 3.23%   |
| SanDisk                      | 1         | 3.23%   |
| Phison Electronics           | 1         | 3.23%   |
| KIOXIA                       | 1         | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 9.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 9.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 6.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 6.25%   |
| Micron NVMe Storage Controller                                               | 2         | 6.25%   |
| Kingston Company Company Non-Volatile memory controller                      | 2         | 6.25%   |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 6.25%   |
| Intel Alder Lake-P SATA AHCI Controller                                      | 2         | 6.25%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 6.25%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 3.13%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 3.13%   |
| SanDisk WD Black SN770 NVMe SSD                                              | 1         | 3.13%   |
| Samsung NVMe SSD Controller PM9B1                                            | 1         | 3.13%   |
| Samsung NVMe SSD Controller 980                                              | 1         | 3.13%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 3.13%   |
| KIOXIA Non-Volatile memory controller                                        | 1         | 3.13%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 3.13%   |
| Kingston Company NVMe Controller                                             | 1         | 3.13%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 3.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 15        | 50%     |
| SATA | 13        | 43.33%  |
| RAID | 2         | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 85.71%  |
| AMD    | 3         | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-12700H                 | 2         | 9.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 4.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 4.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 4.76%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 4.76%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 4.76%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 4.76%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 4.76%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 4.76%   |
| Intel 12th Gen Core i7-1265U                  | 1         | 4.76%   |
| Intel 12th Gen Core i7-1260P                  | 1         | 4.76%   |
| Intel 12th Gen Core i7-1255U                  | 1         | 4.76%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 4.76%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 4.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 4.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 4.76%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 1         | 4.76%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 1         | 4.76%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 4.76%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Other         | 10        | 47.62%  |
| Intel Core i3 | 4         | 19.05%  |
| Intel Core i7 | 2         | 9.52%   |
| Intel Core i5 | 2         | 9.52%   |
| AMD Ryzen 7   | 2         | 9.52%   |
| AMD Ryzen 5   | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 7         | 33.33%  |
| 4      | 4         | 19.05%  |
| 10     | 3         | 14.29%  |
| 14     | 2         | 9.52%   |
| 8      | 2         | 9.52%   |
| 6      | 2         | 9.52%   |
| 12     | 1         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 71.43%  |
| 1      | 6         | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 21        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 19.05%  |
| 0x906a4    | 3         | 14.29%  |
| 0x906a3    | 3         | 14.29%  |
| 0x806c1    | 2         | 9.52%   |
| 0x306a9    | 2         | 9.52%   |
| 0x0a50000c | 2         | 9.52%   |
| 0x906ea    | 1         | 4.76%   |
| 0x806ea    | 1         | 4.76%   |
| 0x806d1    | 1         | 4.76%   |
| 0x406e3    | 1         | 4.76%   |
| 0x08108102 | 1         | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Alderlake Hybrid | 6         | 28.57%  |
| TigerLake        | 3         | 14.29%  |
| Zen 3            | 2         | 9.52%   |
| Skylake          | 2         | 9.52%   |
| SandyBridge      | 2         | 9.52%   |
| KabyLake         | 2         | 9.52%   |
| IvyBridge        | 2         | 9.52%   |
| Zen+             | 1         | 4.76%   |
| Icelake          | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 60%     |
| Nvidia | 7         | 23.33%  |
| AMD    | 5         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 3         | 10%     |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 3         | 10%     |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 2         | 6.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 6.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 2         | 6.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 6.67%   |
| Nvidia TU117GLM [T600 Laptop GPU]                                                     | 1         | 3.33%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                     | 1         | 3.33%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                  | 1         | 3.33%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                              | 1         | 3.33%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 3.33%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                           | 1         | 3.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 1         | 3.33%   |
| Intel UHD Graphics 620                                                                | 1         | 3.33%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 3.33%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 1         | 3.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 3.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 3.33%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 1         | 3.33%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 1         | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 1         | 3.33%   |
| AMD Barcelo                                                                           | 1         | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 9         | 42.86%  |
| Intel + Nvidia | 5         | 23.81%  |
| Intel + AMD    | 3         | 14.29%  |
| 1 x Nvidia     | 2         | 9.52%   |
| 1 x AMD        | 2         | 9.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 20        | 95.24%  |
| Proprietary | 1         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 52.38%  |
| 3.01-4.0   | 5         | 23.81%  |
| 0.51-1.0   | 2         | 9.52%   |
| 7.01-8.0   | 1         | 4.76%   |
| 5.01-6.0   | 1         | 4.76%   |
| 1.01-2.0   | 1         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| LG Display           | 5         | 20.83%  |
| BOE                  | 4         | 16.67%  |
| AU Optronics         | 4         | 16.67%  |
| Chimei Innolux       | 3         | 12.5%   |
| VIZ                  | 1         | 4.17%   |
| Sharp                | 1         | 4.17%   |
| Samsung Electronics  | 1         | 4.17%   |
| Pixio                | 1         | 4.17%   |
| Element              | 1         | 4.17%   |
| Dell                 | 1         | 4.17%   |
| CSO                  | 1         | 4.17%   |
| BOE Technology Group | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                | 2         | 8.33%   |
| VIZ LCD Monitor VA19L HDTV10T                                        | 1         | 4.17%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch              | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch | 1         | 4.17%   |
| Pixio EULCD-2400DFE WAM2380 1920x1080 530x290mm 23.8-inch            | 1         | 4.17%   |
| LG Display LCD Monitor LGD06E4 1920x1080 344x194mm 15.5-inch         | 1         | 4.17%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 1         | 4.17%   |
| LG Display LCD Monitor LGD0505 1366x768 344x194mm 15.5-inch          | 1         | 4.17%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch          | 1         | 4.17%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch          | 1         | 4.17%   |
| Element ELEFW328C ELE3553 1360x768 640x384mm 29.4-inch               | 1         | 4.17%   |
| Dell P2314T DEL409E 1920x1080 509x286mm 23.0-inch                    | 1         | 4.17%   |
| CSO LCD Monitor CSO1506 1920x1080 344x194mm 15.5-inch                | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch      | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15AA 1366x768 344x194mm 15.5-inch      | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 1         | 4.17%   |
| BOE Technology Group LCD Monitor 3200x1080                           | 1         | 4.17%   |
| BOE LCD Monitor BOE0AB0 1920x1080 344x194mm 15.5-inch                | 1         | 4.17%   |
| BOE LCD Monitor BOE0A64 1920x1080 344x194mm 15.5-inch                | 1         | 4.17%   |
| AU Optronics LCD Monitor AUOE3A0 3840x2400 301x188mm 14.0-inch       | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO662D 1920x1080 293x165mm 13.2-inch       | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO5A99 1920x1200 301x188mm 14.0-inch       | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO1496 2560x1440 382x214mm 17.2-inch       | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 12        | 50%     |
| 1366x768 (WXGA)   | 5         | 20.83%  |
| 3840x2400         | 1         | 4.17%   |
| 3840x2160 (4K)    | 1         | 4.17%   |
| 3200x1080         | 1         | 4.17%   |
| 2560x1440 (QHD)   | 1         | 4.17%   |
| 1920x1200 (WUXGA) | 1         | 4.17%   |
| 1600x900 (HD+)    | 1         | 4.17%   |
| Unknown           | 1         | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 13        | 56.52%  |
| 14      | 3         | 13.04%  |
| 17      | 2         | 8.7%    |
| 32      | 1         | 4.35%   |
| 27      | 1         | 4.35%   |
| 23      | 1         | 4.35%   |
| 13      | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 69.57%  |
| 501-600     | 2         | 8.7%    |
| 351-400     | 2         | 8.7%    |
| 701-800     | 1         | 4.35%   |
| 201-300     | 1         | 4.35%   |
| Unknown     | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 18        | 85.71%  |
| 16/10   | 2         | 9.52%   |
| Unknown | 1         | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 56.52%  |
| 81-90          | 3         | 13.04%  |
| 121-130        | 2         | 8.7%    |
| 71-80          | 1         | 4.35%   |
| 351-500        | 1         | 4.35%   |
| 301-350        | 1         | 4.35%   |
| 201-250        | 1         | 4.35%   |
| Unknown        | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 9         | 39.13%  |
| 101-120       | 6         | 26.09%  |
| 161-240       | 4         | 17.39%  |
| 51-100        | 2         | 8.7%    |
| More than 240 | 1         | 4.35%   |
| Unknown       | 1         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 18        | 85.71%  |
| 2     | 3         | 14.29%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 12        | 33.33%  |
| Intel                 | 12        | 33.33%  |
| Qualcomm Atheros      | 4         | 11.11%  |
| Xiaomi                | 1         | 2.78%   |
| Ralink                | 1         | 2.78%   |
| Qualcomm              | 1         | 2.78%   |
| OPPO Electronics      | 1         | 2.78%   |
| Mercucys              | 1         | 2.78%   |
| MediaTek              | 1         | 2.78%   |
| Google                | 1         | 2.78%   |
| Broadcom Limited      | 1         | 2.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                             | 6         | 13.95%  |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 6         | 13.95%  |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 6.98%   |
| Intel Ethernet Connection (16) I219-V                                                         | 3         | 6.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 2         | 4.65%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                          | 1         | 2.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 2.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 1         | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 1         | 2.33%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 2.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 2.33%   |
| Qualcomm SM7250-PICASSO _SN:6897A937                                                          | 1         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 2.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                     | 1         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 2.33%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                                                          | 1         | 2.33%   |
| Mercucys 802.11n NIC                                                                          | 1         | 2.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 2.33%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 2.33%   |
| Intel Wireless 8260                                                                           | 1         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 2.33%   |
| Intel Ethernet Connection I219-V                                                              | 1         | 2.33%   |
| Google Pixel 7                                                                                | 1         | 2.33%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 50%     |
| Realtek Semiconductor | 4         | 16.67%  |
| Qualcomm Atheros      | 4         | 16.67%  |
| Ralink                | 1         | 4.17%   |
| Mercucys              | 1         | 4.17%   |
| MediaTek              | 1         | 4.17%   |
| Broadcom Limited      | 1         | 4.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 6         | 25%     |
| Intel Wi-Fi 6 AX201                                                                           | 3         | 12.5%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 4.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 1         | 4.17%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 4.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 4.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 1         | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 1         | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 1         | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 4.17%   |
| Mercucys 802.11n NIC                                                                          | 1         | 4.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 1         | 4.17%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 4.17%   |
| Intel Wireless 8260                                                                           | 1         | 4.17%   |
| Intel Wi-Fi 6 AX200                                                                           | 1         | 4.17%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 4.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 10        | 52.63%  |
| Intel                 | 4         | 21.05%  |
| Xiaomi                | 1         | 5.26%   |
| Qualcomm Atheros      | 1         | 5.26%   |
| Qualcomm              | 1         | 5.26%   |
| OPPO Electronics      | 1         | 5.26%   |
| Google                | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 31.58%  |
| Intel Ethernet Connection (16) I219-V                             | 3         | 15.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 10.53%  |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 5.26%   |
| Qualcomm SM7250-PICASSO _SN:6897A937                              | 1         | 5.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 5.26%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1         | 5.26%   |
| Intel Ethernet Connection I219-V                                  | 1         | 5.26%   |
| Google Pixel 7                                                    | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 56.76%  |
| Ethernet | 16        | 43.24%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 10        | 52.63%  |
| Ethernet | 9         | 47.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 14        | 66.67%  |
| 1     | 7         | 33.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 16        | 76.19%  |
| Yes  | 5         | 23.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 56.25%  |
| Qualcomm Atheros Communications | 2         | 12.5%   |
| Realtek Semiconductor           | 1         | 6.25%   |
| Ralink                          | 1         | 6.25%   |
| Lite-On Technology              | 1         | 6.25%   |
| IMC Networks                    | 1         | 6.25%   |
| Foxconn / Hon Hai               | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                          | 4         | 25%     |
| Intel Bluetooth wireless interface             | 2         | 12.5%   |
| Realtek Bluetooth Radio                        | 1         | 6.25%   |
| Ralink RT3290 Bluetooth                        | 1         | 6.25%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 6.25%   |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 6.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 6.25%   |
| Intel Bluetooth Device                         | 1         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1         | 6.25%   |
| Intel AX200 Bluetooth                          | 1         | 6.25%   |
| IMC Networks Bluetooth Radio                   | 1         | 6.25%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 75%     |
| Nvidia | 3         | 12.5%   |
| AMD    | 3         | 12.5%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 23.08%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 11.54%  |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 11.54%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 11.54%  |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 11.54%  |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 3.85%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 3.85%   |
| Nvidia Audio device                                                        | 1         | 3.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 3.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 3.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 3.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 33.33%  |
| SK hynix            | 6         | 25%     |
| Micron Technology   | 5         | 20.83%  |
| Crucial             | 2         | 8.33%   |
| Smart               | 1         | 4.17%   |
| fef5                | 1         | 4.17%   |
| A-DATA Technology   | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s        | 1         | 4%      |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                | 1         | 4%      |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 4%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 4%      |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s       | 1         | 4%      |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 4%      |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 4%      |
| Samsung RAM Module 1GB Row Of Chips LPDDR4 3733MT/s          | 1         | 4%      |
| Samsung RAM Module 16GB SODIMM 4800MT/s                      | 1         | 4%      |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 4%      |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s        | 1         | 4%      |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 4%      |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 4%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 4%      |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 4%      |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s              | 1         | 4%      |
| Micron RAM MT40A1G16RC-062E:B 8GB SODIMM DDR4 3200MT/s       | 1         | 4%      |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s | 1         | 4%      |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s        | 1         | 4%      |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s        | 1         | 4%      |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s       | 1         | 4%      |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                        | 1         | 4%      |
| Crucial RAM CT8G4SFS832A.M8FRS 8GB SODIMM DDR4 3200MT/s      | 1         | 4%      |
| Crucial RAM CT32G4SFD832A.C16FF 32GB SODIMM DDR4 3200MT/s    | 1         | 4%      |
| A-DATA RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 12        | 60%     |
| DDR3    | 3         | 15%     |
| LPDDR4  | 2         | 10%     |
| Unknown | 2         | 10%     |
| DDR5    | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 16        | 84.21%  |
| Row Of Chips | 2         | 10.53%  |
| Unknown      | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 33.33%  |
| 16384 | 5         | 23.81%  |
| 4096  | 5         | 23.81%  |
| 32768 | 2         | 9.52%   |
| 1024  | 2         | 9.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 8         | 38.1%   |
| 2667  | 4         | 19.05%  |
| 1600  | 3         | 14.29%  |
| 4800  | 2         | 9.52%   |
| 2400  | 2         | 9.52%   |
| 3733  | 1         | 4.76%   |
| 2133  | 1         | 4.76%   |

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
| Chicony Electronics           | 6         | 27.27%  |
| IMC Networks                  | 4         | 18.18%  |
| Sunplus Innovation Technology | 2         | 9.09%   |
| Realtek Semiconductor         | 2         | 9.09%   |
| Tobii Technology AB           | 1         | 4.55%   |
| Syntek                        | 1         | 4.55%   |
| Quanta                        | 1         | 4.55%   |
| Primax Electronics            | 1         | 4.55%   |
| Microdia                      | 1         | 4.55%   |
| Luxvisions Innotech Limited   | 1         | 4.55%   |
| Bison Electronics             | 1         | 4.55%   |
| Acer                          | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                             | 3         | 13.64%  |
| IMC Networks USB2.0 HD UVC WebCam                                     | 2         | 9.09%   |
| Tobii AB Eyechip                                                      | 1         | 4.55%   |
| Syntek Integrated Camera                                              | 1         | 4.55%   |
| Sunplus Laptop Integrated Webcam FHD                                  | 1         | 4.55%   |
| Sunplus FHD Camera Microphone                                         | 1         | 4.55%   |
| Realtek Integrated Webcam HD                                          | 1         | 4.55%   |
| Realtek HD WebCam                                                     | 1         | 4.55%   |
| Quanta HD User Facing                                                 | 1         | 4.55%   |
| Primax HP HD Webcam [Fixed]                                           | 1         | 4.55%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 4.55%   |
| Luxvisions Innotech Limited Integrated RGB Camera                     | 1         | 4.55%   |
| IMC Networks VGA UVC WebCam                                           | 1         | 4.55%   |
| IMC Networks Integrated Camera                                        | 1         | 4.55%   |
| Chicony HP Truevision HD                                              | 1         | 4.55%   |
| Chicony HP HD Camera                                                  | 1         | 4.55%   |
| Chicony HP 5MP Camera                                                 | 1         | 4.55%   |
| Bison HD Webcam                                                       | 1         | 4.55%   |
| Acer Integrated Camera                                                | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Synaptics | 4         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 50%     |
| Synaptics UWP WBDI Device                                | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 12        | 57.14%  |
| 1     | 7         | 33.33%  |
| 2     | 2         | 9.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 4         | 36.36%  |
| Net/wireless       | 3         | 27.27%  |
| Net/ethernet       | 2         | 18.18%  |
| Chipcard           | 1         | 9.09%   |
| Bluetooth          | 1         | 9.09%   |

