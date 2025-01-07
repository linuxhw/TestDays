Elementary 8 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Elementary 8.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI      | G31TM-P21                   | [7f868dd6f9](https://linux-hardware.org/?probe=7f868dd6f9) | Jan 06, 2025 |
| ASUSTek  | PRIME H310M-E R2.0          | [79752b904b](https://linux-hardware.org/?probe=79752b904b) | Jan 04, 2025 |
| Intel    | H61                         | [0f76193421](https://linux-hardware.org/?probe=0f76193421) | Jan 02, 2025 |
| MSI      | A88XM-E35 V2                | [d3df8a394a](https://linux-hardware.org/?probe=d3df8a394a) | Dec 30, 2024 |
| ASUSTek  | H110M-D                     | [a61b42dd42](https://linux-hardware.org/?probe=a61b42dd42) | Dec 29, 2024 |
| ASRock   | X570 Extreme4               | [65cad1da61](https://linux-hardware.org/?probe=65cad1da61) | Dec 26, 2024 |
| Gigabyte | B85M-HD3                    | [83d5947a2c](https://linux-hardware.org/?probe=83d5947a2c) | Dec 24, 2024 |
| Gigabyte | B560 DS3H AC-Y1             | [4e79bebde8](https://linux-hardware.org/?probe=4e79bebde8) | Dec 24, 2024 |
| Gigabyte | B360 AORUS GAMING 3 WIFI... | [89e8e5ad41](https://linux-hardware.org/?probe=89e8e5ad41) | Dec 24, 2024 |
| MSI      | PRO B760M-P DDR4            | [a649caaa82](https://linux-hardware.org/?probe=a649caaa82) | Dec 23, 2024 |
| MSI      | PRO B760-P WIFI DDR4        | [59c289d5b9](https://linux-hardware.org/?probe=59c289d5b9) | Dec 22, 2024 |
| Gigabyte | B560 DS3H AC-Y1             | [4c934647d2](https://linux-hardware.org/?probe=4c934647d2) | Dec 21, 2024 |
| Dell     | 00V62H A01                  | [8e8317c6a6](https://linux-hardware.org/?probe=8e8317c6a6) | Dec 19, 2024 |
| ASUSTek  | P8H67-M PRO                 | [987844d0b8](https://linux-hardware.org/?probe=987844d0b8) | Dec 17, 2024 |
| HP       | 8266                        | [ccd7d6b235](https://linux-hardware.org/?probe=ccd7d6b235) | Dec 17, 2024 |
| GEEKOM   | A8                          | [821fae98e5](https://linux-hardware.org/?probe=821fae98e5) | Dec 17, 2024 |
| HP       | 83E8                        | [77d40d025a](https://linux-hardware.org/?probe=77d40d025a) | Dec 16, 2024 |
| HP       | 8299                        | [44a762b74e](https://linux-hardware.org/?probe=44a762b74e) | Dec 14, 2024 |
| HP       | 8299                        | [f0c7982d81](https://linux-hardware.org/?probe=f0c7982d81) | Dec 14, 2024 |
| ASUSTek  | PRIME B450M-A               | [262a2aa975](https://linux-hardware.org/?probe=262a2aa975) | Dec 13, 2024 |
| Intel    | B75 V1.1                    | [d6aad9d651](https://linux-hardware.org/?probe=d6aad9d651) | Dec 03, 2024 |
| Dell     | 00V62H A01                  | [a12ee189e3](https://linux-hardware.org/?probe=a12ee189e3) | Dec 02, 2024 |
| Intel    | X99-P4 V5.11                | [b5079a1a8d](https://linux-hardware.org/?probe=b5079a1a8d) | Dec 02, 2024 |
| ASRock   | H310CM-HG4                  | [86f4d79f62](https://linux-hardware.org/?probe=86f4d79f62) | Dec 01, 2024 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 6.8.0-51-generic     | 8        | 38.1%   |
| 6.8.0-49-generic     | 7        | 33.33%  |
| 6.8.0-50-generic     | 5        | 23.81%  |
| 6.12.6-x64v3-xanmod1 | 1        | 4.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.8.0   | 20       | 95.24%  |
| 6.12.6  | 1        | 4.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.8     | 20       | 95.24%  |
| 6.12    | 1        | 4.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 21       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 21       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 20       | 95.24%  |
| Wayland | 1        | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 95.24%  |
| LightDM | 1        | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 5        | 23.81%  |
| de_DE | 4        | 19.05%  |
| es_ES | 3        | 14.29%  |
| ru_RU | 2        | 9.52%   |
| pt_BR | 2        | 9.52%   |
| fr_FR | 2        | 9.52%   |
| it_IT | 1        | 4.76%   |
| hu_HU | 1        | 4.76%   |
| fr_CA | 1        | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 21       | 100%    |

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


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 95.24%  |
| MBR     | 1        | 4.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI                 | 4        | 19.05%  |
| ASUSTek Computer    | 4        | 19.05%  |
| Intel               | 3        | 14.29%  |
| Hewlett-Packard     | 3        | 14.29%  |
| Gigabyte Technology | 3        | 14.29%  |
| ASRock              | 2        | 9.52%   |
| GEEKOM              | 1        | 4.76%   |
| Dell                | 1        | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| MSI MS-7E02                       | 1        | 4.76%   |
| MSI MS-7D98                       | 1        | 4.76%   |
| MSI MS-7721                       | 1        | 4.76%   |
| MSI MS-7529                       | 1        | 4.76%   |
| Intel X99-P4 V5.11                | 1        | 4.76%   |
| Intel H61                         | 1        | 4.76%   |
| Intel B75                         | 1        | 4.76%   |
| HP EliteDesk 800 G3 SFF           | 1        | 4.76%   |
| HP EliteDesk 705 G4 SFF           | 1        | 4.76%   |
| HP EliteDesk 705 G3 Desktop Mini  | 1        | 4.76%   |
| Gigabyte B85M-HD3                 | 1        | 4.76%   |
| Gigabyte B560 DS3H AC-Y1          | 1        | 4.76%   |
| Gigabyte B360 AORUS GAMING 3 WIFI | 1        | 4.76%   |
| GEEKOM A8                         | 1        | 4.76%   |
| Dell OptiPlex 9020                | 1        | 4.76%   |
| ASUS PRIME H310M-E R2.0           | 1        | 4.76%   |
| ASUS PRIME B450M-A                | 1        | 4.76%   |
| ASUS P8H67-M PRO                  | 1        | 4.76%   |
| ASUS H110M-D                      | 1        | 4.76%   |
| ASRock X570 Extreme4              | 1        | 4.76%   |
| ASRock H310CM-HG4                 | 1        | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| HP EliteDesk      | 3        | 14.29%  |
| ASUS PRIME        | 2        | 9.52%   |
| MSI MS-7E02       | 1        | 4.76%   |
| MSI MS-7D98       | 1        | 4.76%   |
| MSI MS-7721       | 1        | 4.76%   |
| MSI MS-7529       | 1        | 4.76%   |
| Intel X99-P4      | 1        | 4.76%   |
| Intel H61         | 1        | 4.76%   |
| Intel B75         | 1        | 4.76%   |
| Gigabyte B85M-HD3 | 1        | 4.76%   |
| Gigabyte B560     | 1        | 4.76%   |
| Gigabyte B360     | 1        | 4.76%   |
| GEEKOM A8         | 1        | 4.76%   |
| Dell OptiPlex     | 1        | 4.76%   |
| ASUS P8H67-M      | 1        | 4.76%   |
| ASUS H110M-D      | 1        | 4.76%   |
| ASRock X570       | 1        | 4.76%   |
| ASRock H310CM-HG4 | 1        | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 4        | 19.05%  |
| 2017 | 3        | 14.29%  |
| 2024 | 2        | 9.52%   |
| 2022 | 2        | 9.52%   |
| 2019 | 2        | 9.52%   |
| 2015 | 2        | 9.52%   |
| 2013 | 2        | 9.52%   |
| 2021 | 1        | 4.76%   |
| 2014 | 1        | 4.76%   |
| 2010 | 1        | 4.76%   |
| 2009 | 1        | 4.76%   |

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


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 8        | 38.1%   |
| 4.01-8.0    | 4        | 19.05%  |
| 32.01-64.0  | 3        | 14.29%  |
| 3.01-4.0    | 2        | 9.52%   |
| 8.01-16.0   | 2        | 9.52%   |
| 24.01-32.0  | 1        | 4.76%   |
| 64.01-256.0 | 1        | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 7        | 33.33%  |
| 2.01-3.0 | 6        | 28.57%  |
| 4.01-8.0 | 4        | 19.05%  |
| 3.01-4.0 | 4        | 19.05%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 52.38%  |
| 3      | 3        | 14.29%  |
| 2      | 3        | 14.29%  |
| 4      | 2        | 9.52%   |
| 7      | 1        | 4.76%   |
| 5      | 1        | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 71.43%  |
| Yes       | 6        | 28.57%  |

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
| Yes       | 14       | 66.67%  |
| No        | 7        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 57.14%  |
| Yes       | 9        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| USA     | 5        | 23.81%  |
| Spain   | 3        | 14.29%  |
| Germany | 3        | 14.29%  |
| Brazil  | 3        | 14.29%  |
| Russia  | 2        | 9.52%   |
| France  | 2        | 9.52%   |
| Italy   | 1        | 4.76%   |
| Hungary | 1        | 4.76%   |
| Canada  | 1        | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Tours           | 1        | 4.76%   |
| Shawinigan      | 1        | 4.76%   |
| Seveso          | 1        | 4.76%   |
| Sarmanovo       | 1        | 4.76%   |
| Roncador        | 1        | 4.76%   |
| Paris           | 1        | 4.76%   |
| Palma           | 1        | 4.76%   |
| Orekhovo-Zuyevo | 1        | 4.76%   |
| New York        | 1        | 4.76%   |
| Mezokovesd      | 1        | 4.76%   |
| Mannheim        | 1        | 4.76%   |
| Málaga         | 1        | 4.76%   |
| Ludwigsburg     | 1        | 4.76%   |
| Loerrach        | 1        | 4.76%   |
| Joao Pessoa     | 1        | 4.76%   |
| Huelva          | 1        | 4.76%   |
| Easthampton     | 1        | 4.76%   |
| Cary            | 1        | 4.76%   |
| Carbondale      | 1        | 4.76%   |
| Bristol         | 1        | 4.76%   |
| Alegrete        | 1        | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 5        | 5      | 11.9%   |
| Seagate                     | 5        | 6      | 11.9%   |
| Toshiba                     | 4        | 4      | 9.52%   |
| Samsung Electronics         | 3        | 4      | 7.14%   |
| Kingston                    | 3        | 4      | 7.14%   |
| Silicon Motion              | 2        | 2      | 4.76%   |
| XrayDisk                    | 1        | 1      | 2.38%   |
| Team                        | 1        | 1      | 2.38%   |
| Sandisk                     | 1        | 1      | 2.38%   |
| PRO Z                       | 1        | 2      | 2.38%   |
| PNY                         | 1        | 1      | 2.38%   |
| OCZ-VERTEX2                 | 1        | 1      | 2.38%   |
| Netac                       | 1        | 1      | 2.38%   |
| Micron/Crucial Technology   | 1        | 1      | 2.38%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 2.38%   |
| KIOXIA                      | 1        | 1      | 2.38%   |
| Kingston Technology Company | 1        | 1      | 2.38%   |
| JMicron Technology          | 1        | 1      | 2.38%   |
| HUSKY                       | 1        | 1      | 2.38%   |
| HS-SSD-E100                 | 1        | 1      | 2.38%   |
| GOODRAM                     | 1        | 1      | 2.38%   |
| Fanxiang                    | 1        | 1      | 2.38%   |
| Emtec                       | 1        | 1      | 2.38%   |
| Crucial                     | 1        | 1      | 2.38%   |
| China                       | 1        | 1      | 2.38%   |
| ADATA Technology            | 1        | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2        | 4.65%   |
| Kingston SA400S37240G 240GB SSD                       | 2        | 4.65%   |
| XrayDisk 512GB                                        | 1        | 2.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 1        | 2.33%   |
| WDC WD3200BPVT-00JJ5T0 320GB                          | 1        | 2.33%   |
| WDC WD20EZRX-00DC0B0 2TB                              | 1        | 2.33%   |
| WDC WD20EZRX-00D8PB0 2TB                              | 1        | 2.33%   |
| WDC WD10EARS-22Y5B1 1TB                               | 1        | 2.33%   |
| Toshiba MQ01ACF050 500GB                              | 1        | 2.33%   |
| Toshiba MQ01ABF032 320GB                              | 1        | 2.33%   |
| Toshiba KXG50ZNV512G 512GB                            | 1        | 2.33%   |
| Toshiba DT01ACA100 1TB                                | 1        | 2.33%   |
| Team T253256GB SSD                                    | 1        | 2.33%   |
| Seagate ST500LM000-1EJ162 500GB                       | 1        | 2.33%   |
| Seagate ST500DM002-1BD142 500GB                       | 1        | 2.33%   |
| Seagate ST4000DM004-2CV104 4TB                        | 1        | 2.33%   |
| Seagate ST1000LM048-2E7172 1TB                        | 1        | 2.33%   |
| Seagate ST1000DM010-2EP102 1TB                        | 1        | 2.33%   |
| Sandisk WD Blue SN570 2TB                             | 1        | 2.33%   |
| Samsung SSD 870 QVO 1TB                               | 1        | 2.33%   |
| Samsung SSD 850 EVO 120GB                             | 1        | 2.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 1        | 2.33%   |
| PRO Z Avolusion 8TB                                   | 1        | 2.33%   |
| PNY CS900 480GB SSD                                   | 1        | 2.33%   |
| OCZ-VERTEX2 3.5 120GB SSD                             | 1        | 2.33%   |
| Netac SSD 240GB                                       | 1        | 2.33%   |
| Micron/Crucial CT2000P3PSSD8 2TB                      | 1        | 2.33%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 1        | 2.33%   |
| KIOXIA EXCERIA PLUS G3 SSD 2TB                        | 1        | 2.33%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 1        | 2.33%   |
| Kingston SV300S37A240G 240GB SSD                      | 1        | 2.33%   |
| Kingston SA400S37120G 120GB SSD                       | 1        | 2.33%   |
| JMicron Generic 500GB                                 | 1        | 2.33%   |
| HUSKY SSD 128GB                                       | 1        | 2.33%   |
| HS-SSD-E100 512G                                      | 1        | 2.33%   |
| GOODRAM SSD 120GB                                     | 1        | 2.33%   |
| Fanxiang S101Q 512GB MX                               | 1        | 2.33%   |
| Emtec X160 512GB                                      | 1        | 2.33%   |
| Crucial CT480BX500SSD1 480GB                          | 1        | 2.33%   |
| China SSD 256GB                                       | 1        | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| Seagate            | 5        | 6      | 38.46%  |
| WDC                | 4        | 4      | 30.77%  |
| Toshiba            | 3        | 3      | 23.08%  |
| JMicron Technology | 1        | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 3        | 4      | 20%     |
| Samsung Electronics | 2        | 3      | 13.33%  |
| WDC                 | 1        | 1      | 6.67%   |
| Team                | 1        | 1      | 6.67%   |
| PNY                 | 1        | 1      | 6.67%   |
| OCZ-VERTEX2         | 1        | 1      | 6.67%   |
| Netac               | 1        | 1      | 6.67%   |
| HUSKY               | 1        | 1      | 6.67%   |
| GOODRAM             | 1        | 1      | 6.67%   |
| Emtec               | 1        | 1      | 6.67%   |
| Crucial             | 1        | 1      | 6.67%   |
| China               | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 13       | 17     | 35.14%  |
| HDD     | 11       | 14     | 29.73%  |
| NVMe    | 9        | 10     | 24.32%  |
| Unknown | 4        | 5      | 10.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 17       | 33     | 62.96%  |
| NVMe | 9        | 10     | 33.33%  |
| SAS  | 1        | 3      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 17       | 20     | 68%     |
| 0.51-1.0   | 5        | 8      | 20%     |
| 1.01-2.0   | 2        | 2      | 8%      |
| 3.01-4.0   | 1        | 1      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 9        | 42.86%  |
| 101-250    | 7        | 33.33%  |
| 501-1000   | 2        | 9.52%   |
| 21-50      | 1        | 4.76%   |
| 1001-2000  | 1        | 4.76%   |
| 51-100     | 1        | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 13       | 61.9%   |
| 21-50    | 6        | 28.57%  |
| 251-500  | 1        | 4.76%   |
| 501-1000 | 1        | 4.76%   |

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
| Detected | 20       | 45     | 95.24%  |
| Works    | 1        | 1      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 15       | 46.88%  |
| AMD                          | 5        | 15.63%  |
| Silicon Motion               | 2        | 6.25%   |
| VIA Technologies             | 1        | 3.13%   |
| Toshiba America Info Systems | 1        | 3.13%   |
| SanDisk                      | 1        | 3.13%   |
| Samsung Electronics          | 1        | 3.13%   |
| Micron/Crucial Technology    | 1        | 3.13%   |
| MAXIO Technology (Hangzhou)  | 1        | 3.13%   |
| KIOXIA                       | 1        | 3.13%   |
| Kingston Technology Company  | 1        | 3.13%   |
| ASMedia Technology           | 1        | 3.13%   |
| ADATA Technology             | 1        | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 14.29%  |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 8.57%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2        | 5.71%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2        | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 5.71%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 2.86%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1        | 2.86%   |
| SanDisk WD Blue SN570 NVMe SSD 2TB                                             | 1        | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 2.86%   |
| Micron/Crucial P3 Plus NVMe PCIe SSD (DRAM-less)                               | 1        | 2.86%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1        | 2.86%   |
| KIOXIA Exceria Plus G3 NVMe SSD (DRAM-less)                                    | 1        | 2.86%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1        | 2.86%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 2.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.86%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 2.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 2.86%   |
| Intel 500 Series Chipset Family SATA RAID Controller                           | 1        | 2.86%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 1        | 2.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.86%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 2.86%   |
| ADATA LEGEND 800 NVMe SSD (DRAM-less)                                          | 1        | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 17       | 56.67%  |
| NVMe | 9        | 30%     |
| RAID | 2        | 6.67%   |
| IDE  | 2        | 6.67%   |

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
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz             | 1        | 4.76%   |
| Intel Pentium CPU G4400 @ 3.30GHz               | 1        | 4.76%   |
| Intel Core i7-3770S CPU @ 3.10GHz               | 1        | 4.76%   |
| Intel Core i5-9400 CPU @ 2.90GHz                | 1        | 4.76%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 1        | 4.76%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1        | 4.76%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 1        | 4.76%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 4.76%   |
| Intel Core i5-4430 CPU @ 3.00GHz                | 1        | 4.76%   |
| Intel Core i5-3330 CPU @ 3.00GHz                | 1        | 4.76%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 1        | 4.76%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz            | 1        | 4.76%   |
| Intel 12th Gen Core i5-12600K                   | 1        | 4.76%   |
| Intel 12th Gen Core i5-12400F                   | 1        | 4.76%   |
| Intel 11th Gen Core i7-11700F @ 2.50GHz         | 1        | 4.76%   |
| AMD Ryzen 9 8945HS w/ Radeon 780M Graphics      | 1        | 4.76%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 1        | 4.76%   |
| AMD Ryzen 5 PRO 2400G with Radeon Vega Graphics | 1        | 4.76%   |
| AMD Ryzen 5 5500                                | 1        | 4.76%   |
| AMD PRO A10-8770E R7, 10 COMPUTE CORES 4C+6G    | 1        | 4.76%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G   | 1        | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i5    | 8        | 38.1%   |
| Other            | 3        | 14.29%  |
| AMD Ryzen 9      | 2        | 9.52%   |
| Intel Xeon       | 1        | 4.76%   |
| Intel Pentium    | 1        | 4.76%   |
| Intel Core i7    | 1        | 4.76%   |
| Intel Core 2 Duo | 1        | 4.76%   |
| AMD Ryzen 5 PRO  | 1        | 4.76%   |
| AMD Ryzen 5      | 1        | 4.76%   |
| AMD PRO A10      | 1        | 4.76%   |
| AMD A8           | 1        | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 33.33%  |
| 6      | 5        | 23.81%  |
| 2      | 4        | 19.05%  |
| 10     | 2        | 9.52%   |
| 8      | 2        | 9.52%   |
| 12     | 1        | 4.76%   |

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
| 2      | 11       | 52.38%  |
| 1      | 10       | 47.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 21       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 4        | 19.05%  |
| Unknown     | 4        | 19.05%  |
| Haswell     | 3        | 14.29%  |
| Zen 3       | 2        | 9.52%   |
| IvyBridge   | 2        | 9.52%   |
| Zen         | 1        | 4.76%   |
| Steamroller | 1        | 4.76%   |
| Skylake     | 1        | 4.76%   |
| SandyBridge | 1        | 4.76%   |
| Penryn      | 1        | 4.76%   |
| Excavator   | 1        | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 9        | 37.5%   |
| Intel  | 8        | 33.33%  |
| Nvidia | 7        | 29.17%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 8.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 8.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 8.33%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 4.17%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 4.17%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 4.17%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 4.17%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 4.17%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 4.17%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 4.17%   |
| Intel HD Graphics 630                                                       | 1        | 4.17%   |
| Intel HD Graphics 510                                                       | 1        | 4.17%   |
| Intel AlderLake-S GT1                                                       | 1        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 4.17%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 4.17%   |
| AMD Phoenix3                                                                | 1        | 4.17%   |
| AMD Navi 33 [Radeon RX 7600/7600 XT/7600M XT/7600S/7700S / PRO W7600]       | 1        | 4.17%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 4.17%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 4.17%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 7        | 33.33%  |
| 1 x Intel      | 6        | 28.57%  |
| 1 x Nvidia     | 5        | 23.81%  |
| Intel + Nvidia | 1        | 4.76%   |
| Intel + AMD    | 1        | 4.76%   |
| AMD + Nvidia   | 1        | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 18       | 85.71%  |
| Unknown     | 2        | 9.52%   |
| Proprietary | 1        | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 90.48%  |
| 8.01-16.0  | 1        | 4.76%   |
| 0.01-0.5   | 1        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 3        | 15%     |
| Philips              | 2        | 10%     |
| Goldstar             | 2        | 10%     |
| Dell                 | 2        | 10%     |
| ViewSonic            | 1        | 5%      |
| Sceptre Tech         | 1        | 5%      |
| Panasonic            | 1        | 5%      |
| Lenovo               | 1        | 5%      |
| KON                  | 1        | 5%      |
| Insignia             | 1        | 5%      |
| Iiyama               | 1        | 5%      |
| Hewlett-Packard      | 1        | 5%      |
| DENON                | 1        | 5%      |
| AOC                  | 1        | 5%      |
| Ancor Communications | 1        | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 2        | 9.52%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch          | 1        | 4.76%   |
| Sceptre Tech Sceptre O34 SPT8542 3440x1440 797x334mm 34.0-inch         | 1        | 4.76%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch   | 1        | 4.76%   |
| Samsung Electronics LCD Monitor SAM735B 3840x2160 1420x800mm 64.2-inch | 1        | 4.76%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch     | 1        | 4.76%   |
| Philips PHL 221B6Q PHL08DF 1920x1080 477x268mm 21.5-inch               | 1        | 4.76%   |
| Philips 236V4 PHLC0B3 1920x1080 510x287mm 23.0-inch                    | 1        | 4.76%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 1        | 4.76%   |
| Lenovo LEN L171p LEN24C9 1280x1024 338x270mm 17.0-inch                 | 1        | 4.76%   |
| KON TV_MONITOR KON0030 3840x2160 708x398mm 32.0-inch                   | 1        | 4.76%   |
| Insignia TV BBY3223 1920x1080 697x392mm 31.5-inch                      | 1        | 4.76%   |
| Iiyama PLG2888UH IVM710D 3840x2160 621x341mm 27.9-inch                 | 1        | 4.76%   |
| Hewlett-Packard S2231 HWP2906 1920x1080 477x268mm 21.5-inch            | 1        | 4.76%   |
| DENON AVR DON0070 3840x2160 708x398mm 32.0-inch                        | 1        | 4.76%   |
| Dell P2210 DEL404E 1680x1050 474x296mm 22.0-inch                       | 1        | 4.76%   |
| Dell P2210 DEL404D 1680x1050 474x296mm 22.0-inch                       | 1        | 4.76%   |
| Dell IN2020M DELF029 1600x900 443x249mm 20.0-inch                      | 1        | 4.76%   |
| AOC U2879G6 AOC2879 3840x2160 621x341mm 27.9-inch                      | 1        | 4.76%   |
| Ancor Communications ASUS VB191 ACI19B4 1280x1024 340x270mm 17.1-inch  | 1        | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 3840x2160 (4K)     | 6        | 30%     |
| 1920x1080 (FHD)    | 5        | 25%     |
| 2560x1080          | 2        | 10%     |
| 1680x1050 (WSXGA+) | 2        | 10%     |
| 3840x1080          | 1        | 5%      |
| 3440x1440          | 1        | 5%      |
| 1600x900 (HD+)     | 1        | 5%      |
| 1280x720 (HD)      | 1        | 5%      |
| 1280x1024 (SXGA)   | 1        | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 34     | 3        | 15%     |
| 32     | 2        | 10%     |
| 27     | 2        | 10%     |
| 23     | 2        | 10%     |
| 22     | 2        | 10%     |
| 21     | 2        | 10%     |
| 84     | 1        | 5%      |
| 64     | 1        | 5%      |
| 49     | 1        | 5%      |
| 31     | 1        | 5%      |
| 20     | 1        | 5%      |
| 19     | 1        | 5%      |
| 17     | 1        | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 701-800     | 5        | 25%     |
| 401-500     | 5        | 25%     |
| 601-700     | 3        | 15%     |
| 501-600     | 2        | 10%     |
| 1001-1500   | 2        | 10%     |
| 351-400     | 1        | 5%      |
| 301-350     | 1        | 5%      |
| 1501-2000   | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 12       | 60%     |
| 21/9  | 3        | 15%     |
| 5/4   | 2        | 10%     |
| 16/10 | 2        | 10%     |
| 32/9  | 1        | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 351-500        | 6        | 30%     |
| 201-250        | 5        | 25%     |
| 151-200        | 3        | 15%     |
| More than 1000 | 2        | 10%     |
| 301-350        | 2        | 10%     |
| 141-150        | 1        | 5%      |
| 501-1000       | 1        | 5%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 73.68%  |
| 101-120 | 3        | 15.79%  |
| 121-160 | 2        | 10.53%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 90.48%  |
| 2     | 2        | 9.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 16       | 51.61%  |
| Intel                           | 7        | 22.58%  |
| TP-Link                         | 2        | 6.45%   |
| Qualcomm Atheros Communications | 1        | 3.23%   |
| Qualcomm Atheros                | 1        | 3.23%   |
| MediaTek                        | 1        | 3.23%   |
| Edimax Technology               | 1        | 3.23%   |
| Broadcom                        | 1        | 3.23%   |
| Belkin Components               | 1        | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                  | Desktops | Percent |
|----------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                 | 13       | 36.11%  |
| Realtek RTL8125 2.5GbE Controller                                                      | 2        | 5.56%   |
| Intel Wireless 7265                                                                    | 2        | 5.56%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                    | 1        | 2.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                             | 1        | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                               | 1        | 2.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                             | 1        | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                  | 1        | 2.78%   |
| Realtek 802.11ac NIC                                                                   | 1        | 2.78%   |
| Qualcomm Atheros AR9271 802.11n                                                        | 1        | 2.78%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                       | 1        | 2.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                          | 1        | 2.78%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                      | 1        | 2.78%   |
| Intel I211 Gigabit Network Connection                                                  | 1        | 2.78%   |
| Intel I210 Gigabit Network Connection                                                  | 1        | 2.78%   |
| Intel Ethernet Connection I217-LM                                                      | 1        | 2.78%   |
| Intel Ethernet Connection (7) I219-V                                                   | 1        | 2.78%   |
| Intel Ethernet Connection (5) I219-LM                                                  | 1        | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                                        | 1        | 2.78%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                         | 1        | 2.78%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                                       | 1        | 2.78%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v2000 [Ralink RT3070] | 1        | 2.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 28.57%  |
| Realtek Semiconductor           | 3        | 21.43%  |
| TP-Link                         | 2        | 14.29%  |
| Qualcomm Atheros Communications | 1        | 7.14%   |
| Qualcomm Atheros                | 1        | 7.14%   |
| MediaTek                        | 1        | 7.14%   |
| Edimax Technology               | 1        | 7.14%   |
| Belkin Components               | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                  | Desktops | Percent |
|----------------------------------------------------------------------------------------|----------|---------|
| Intel Wireless 7265                                                                    | 2        | 14.29%  |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                    | 1        | 7.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                             | 1        | 7.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                               | 1        | 7.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                             | 1        | 7.14%   |
| Realtek 802.11ac NIC                                                                   | 1        | 7.14%   |
| Qualcomm Atheros AR9271 802.11n                                                        | 1        | 7.14%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                       | 1        | 7.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                          | 1        | 7.14%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                      | 1        | 7.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                                        | 1        | 7.14%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                         | 1        | 7.14%   |
| Belkin Components F6D4050 N150 Enhanced Wireless Network Adapter v2000 [Ralink RT3070] | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 76.19%  |
| Intel                 | 4        | 19.05%  |
| Broadcom              | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 13       | 59.09%  |
| Realtek RTL8125 2.5GbE Controller                                      | 2        | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 4.55%   |
| Intel I211 Gigabit Network Connection                                  | 1        | 4.55%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 4.55%   |
| Intel Ethernet Connection I217-LM                                      | 1        | 4.55%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 4.55%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 4.55%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1        | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 60%     |
| WiFi     | 14       | 40%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 52.17%  |
| WiFi     | 11       | 47.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 57.14%  |
| 2     | 9        | 42.86%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| Yes  | 12       | 57.14%  |
| No   | 9        | 42.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 44.44%  |
| IMC Networks            | 2        | 22.22%  |
| Cambridge Silicon Radio | 2        | 22.22%  |
| Unknown                 | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 2        | 22.22%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 22.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 11.11%  |
| Intel AX211 Bluetooth                               | 1        | 11.11%  |
| IMC Networks Wireless_Device                        | 1        | 11.11%  |
| IMC Networks Bluetooth Radio                        | 1        | 11.11%  |
| Unknown                                             | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 15       | 37.5%   |
| AMD                     | 9        | 22.5%   |
| Nvidia                  | 7        | 17.5%   |
| Creative Labs           | 2        | 5%      |
| Texas Instruments       | 1        | 2.5%    |
| Kingston Technology     | 1        | 2.5%    |
| Hewlett-Packard         | 1        | 2.5%    |
| GN Netcom               | 1        | 2.5%    |
| CMTECK                  | 1        | 2.5%    |
| Cambridge Silicon Radio | 1        | 2.5%    |
| C-Media Electronics     | 1        | 2.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 200 Series PCH HD Audio                                                                   | 3        | 6.12%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                      | 3        | 6.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 2        | 4.08%   |
| Intel Raptor Lake High Definition Audio Controller                                              | 2        | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2        | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 2        | 4.08%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 2        | 4.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 2        | 4.08%   |
| Texas Instruments PCM2901 Audio Codec                                                           | 1        | 2.04%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 1        | 2.04%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 2.04%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 1        | 2.04%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 2.04%   |
| Nvidia GF116 High Definition Audio Controller                                                   | 1        | 2.04%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 1        | 2.04%   |
| Nvidia GA106 High Definition Audio Controller                                                   | 1        | 2.04%   |
| Kingston Technology HyperX 7.1 Audio                                                            | 1        | 2.04%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 1        | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 1        | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                                      | 1        | 2.04%   |
| Intel C610/X99 series chipset HD Audio Controller                                               | 1        | 2.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 1        | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 1        | 2.04%   |
| Hewlett-Packard HyperX SoloCast                                                                 | 1        | 2.04%   |
| GN Netcom V20                                                                                   | 1        | 2.04%   |
| CMTECK CMTECK                                                                                   | 1        | 2.04%   |
| Cambridge Silicon Radio B25                                                                     | 1        | 2.04%   |
| C-Media Electronics Auna Mic CM900                                                              | 1        | 2.04%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 1        | 2.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 1        | 2.04%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                           | 1        | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 1        | 2.04%   |
| AMD Navi 31 HDMI/DP Audio                                                                       | 1        | 2.04%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 1        | 2.04%   |
| AMD Kaveri HDMI/DP Audio Controller                                                             | 1        | 2.04%   |
| AMD Kabini HDMI/DP Audio                                                                        | 1        | 2.04%   |
| AMD FCH Azalia Controller                                                                       | 1        | 2.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                | 1        | 2.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]               | 1        | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s | 1        | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| SDRAM | 1        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 1        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 2048 | 1        | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 800   | 1        | 100%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson XP-4100 Series | 1        | 100%    |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| WaveRider Communications | 1        | 25%     |
| USB 4K Camera            | 1        | 25%     |
| SunplusIT                | 1        | 25%     |
| Microdia                 | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| WaveRider USB 2.0 Camera       | 1        | 25%     |
| USB 4K Camera                  | 1        | 25%     |
| SunplusIT USB IR Camera        | 1        | 25%     |
| Microdia Streaming Camera W8GS | 1        | 25%     |

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
| 0     | 16       | 76.19%  |
| 1     | 5        | 23.81%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Graphics card    | 2        | 40%     |
| Unassigned class | 1        | 20%     |
| Storage/raid     | 1        | 20%     |
| Net/wireless     | 1        | 20%     |

