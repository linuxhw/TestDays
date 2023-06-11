Q4OS - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for Q4OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 19

| Vendor        | Model           | Probe                                                      | Date         |
|---------------|-----------------|------------------------------------------------------------|--------------|
| ASUSTek       | ET1602          | [637fb8c9ce](https://linux-hardware.org/?probe=637fb8c9ce) | Apr 22, 2023 |
| HP            | 1850            | [162ec03859](https://linux-hardware.org/?probe=162ec03859) | Apr 02, 2023 |
| HP            | 1850            | [ccad003ff4](https://linux-hardware.org/?probe=ccad003ff4) | Jan 20, 2023 |
| VXL           | M6V90AI-VL      | [1ad8dbaae1](https://linux-hardware.org/?probe=1ad8dbaae1) | Jan 08, 2023 |
| MSI           | G41M4           | [b651925b13](https://linux-hardware.org/?probe=b651925b13) | Dec 21, 2022 |
| ASRock        | J3455B-ITX      | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| ASRock        | B450M Pro4      | [97e52df467](https://linux-hardware.org/?probe=97e52df467) | Nov 05, 2022 |
| BESSTAR Te... | UM250 V1.0      | [67369107e1](https://linux-hardware.org/?probe=67369107e1) | Nov 05, 2022 |
| ASRock        | J3455B-ITX      | [deda12dd1f](https://linux-hardware.org/?probe=deda12dd1f) | Nov 05, 2022 |
| Gigabyte      | AB350-Gaming-CF | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| Foxconn       | 2ABF            | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
| ASRock        | H61M-HVS        | [a9ee15a4d2](https://linux-hardware.org/?probe=a9ee15a4d2) | May 13, 2022 |
| Compaq        | 07E4h           | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| Gigabyte      | XP-M5S661GX     | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| TECO Elect... | TR53A0          | [4ab721c7f7](https://linux-hardware.org/?probe=4ab721c7f7) | Aug 19, 2021 |
| MSI           | B550-A PRO      | [546cf15192](https://linux-hardware.org/?probe=546cf15192) | Jun 16, 2021 |
| MSI           | GF615M-P33 V2   | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| ASRock        | G41M-VS3        | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3        | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Q4OS 4 | 11       | 68.75%  |
| Q4OS 3 | 5        | 31.25%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Q4OS | 16       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.10.0-19-amd64   | 4        | 23.53%  |
| 6.0.0-1-amd64     | 1        | 5.88%   |
| 5.10.0-9-686-pae  | 1        | 5.88%   |
| 5.10.0-21-amd64   | 1        | 5.88%   |
| 5.10.0-21-686-pae | 1        | 5.88%   |
| 5.10.0-20-amd64   | 1        | 5.88%   |
| 5.10.0-20-686-pae | 1        | 5.88%   |
| 5.10.0-14-amd64   | 1        | 5.88%   |
| 5.10.0-10-686-pae | 1        | 5.88%   |
| 4.19.0-6-amd64    | 1        | 5.88%   |
| 4.19.0-21-amd64   | 1        | 5.88%   |
| 4.19.0-17-686-pae | 1        | 5.88%   |
| 4.19.0-16-amd64   | 1        | 5.88%   |
| 4.19.0-16-686     | 1        | 5.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 10       | 62.5%   |
| 4.19.0  | 5        | 31.25%  |
| 6.0.0   | 1        | 6.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 62.5%   |
| 4.19    | 5        | 31.25%  |
| 6.0     | 1        | 6.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 10       | 62.5%   |
| i686   | 6        | 37.5%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Trinity | 12       | 70.59%  |
| KDE5    | 3        | 17.65%  |
| LXDE    | 1        | 5.88%   |
| Budgie  | 1        | 5.88%   |

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
| TDM     | 12       | 75%     |
| SDDM    | 3        | 18.75%  |
| LightDM | 1        | 6.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| it_IT | 4        | 25%     |
| en_US | 2        | 12.5%   |
| sk_SK | 1        | 6.25%   |
| pt_BR | 1        | 6.25%   |
| hu_HU | 1        | 6.25%   |
| fr_FR | 1        | 6.25%   |
| es_PE | 1        | 6.25%   |
| es_AR | 1        | 6.25%   |
| en_ZA | 1        | 6.25%   |
| en_IE | 1        | 6.25%   |
| de_DE | 1        | 6.25%   |
| bg_BG | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 12       | 75%     |
| EFI  | 4        | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 16       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 8        | 50%     |
| GPT  | 8        | 50%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 93.75%  |
| Yes       | 1        | 6.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 62.5%   |
| Yes       | 6        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASRock                      | 4        | 25%     |
| MSI                         | 3        | 18.75%  |
| Gigabyte Technology         | 2        | 12.5%   |
| VXL                         | 1        | 6.25%   |
| TECO Electric and Machinery | 1        | 6.25%   |
| Hewlett-Packard             | 1        | 6.25%   |
| Foxconn                     | 1        | 6.25%   |
| Compaq                      | 1        | 6.25%   |
| BESSTAR Tech                | 1        | 6.25%   |
| ASUSTek Computer            | 1        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| VXL TC7500D Series                     | 1        | 6.25%   |
| TECO Electric and Machinery FUTRO S400 | 1        | 6.25%   |
| MSI MS-7C56                            | 1        | 6.25%   |
| MSI MS-7597                            | 1        | 6.25%   |
| MSI MS-7592                            | 1        | 6.25%   |
| HP Compaq Pro 6305 SFF                 | 1        | 6.25%   |
| Gigabyte XP-M5S661GX                   | 1        | 6.25%   |
| Gigabyte AB350-Gaming                  | 1        | 6.25%   |
| Foxconn Pro 3400 Series MT             | 1        | 6.25%   |
| Compaq Evo D510 SFF                    | 1        | 6.25%   |
| BESSTAR Tech UM250                     | 1        | 6.25%   |
| ASUS ET1602                            | 1        | 6.25%   |
| ASRock J3455B-ITX                      | 1        | 6.25%   |
| ASRock H61M-HVS                        | 1        | 6.25%   |
| ASRock G41M-VS3                        | 1        | 6.25%   |
| ASRock B450M Pro4                      | 1        | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| VXL TC7500D                       | 1        | 6.25%   |
| TECO Electric and Machinery FUTRO | 1        | 6.25%   |
| MSI MS-7C56                       | 1        | 6.25%   |
| MSI MS-7597                       | 1        | 6.25%   |
| MSI MS-7592                       | 1        | 6.25%   |
| HP Compaq                         | 1        | 6.25%   |
| Gigabyte XP-M5S661GX              | 1        | 6.25%   |
| Gigabyte AB350-Gaming             | 1        | 6.25%   |
| Foxconn Pro                       | 1        | 6.25%   |
| Compaq Evo                        | 1        | 6.25%   |
| BESSTAR Tech UM250                | 1        | 6.25%   |
| ASUS ET1602                       | 1        | 6.25%   |
| ASRock J3455B-ITX                 | 1        | 6.25%   |
| ASRock H61M-HVS                   | 1        | 6.25%   |
| ASRock G41M-VS3                   | 1        | 6.25%   |
| ASRock B450M                      | 1        | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 3        | 18.75%  |
| 2009 | 2        | 12.5%   |
| 2021 | 1        | 6.25%   |
| 2020 | 1        | 6.25%   |
| 2018 | 1        | 6.25%   |
| 2017 | 1        | 6.25%   |
| 2016 | 1        | 6.25%   |
| 2013 | 1        | 6.25%   |
| 2012 | 1        | 6.25%   |
| 2010 | 1        | 6.25%   |
| 2008 | 1        | 6.25%   |
| 2005 | 1        | 6.25%   |
| 2002 | 1        | 6.25%   |

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


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 3        | 18.75%  |
| 2.01-3.0    | 3        | 18.75%  |
| 16.01-24.0  | 2        | 12.5%   |
| 1.01-2.0    | 2        | 12.5%   |
| 4.01-8.0    | 1        | 6.25%   |
| 32.01-64.0  | 1        | 6.25%   |
| 64.01-256.0 | 1        | 6.25%   |
| 8.01-16.0   | 1        | 6.25%   |
| 0.51-1.0    | 1        | 6.25%   |
| 0.01-0.5    | 1        | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 6        | 35.29%  |
| 2.01-3.0  | 5        | 29.41%  |
| 1.01-2.0  | 2        | 11.76%  |
| 4.01-8.0  | 1        | 5.88%   |
| 3.01-4.0  | 1        | 5.88%   |
| 8.01-16.0 | 1        | 5.88%   |
| 0.01-0.5  | 1        | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 64.71%  |
| 3      | 3        | 17.65%  |
| 2      | 3        | 17.65%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 58.82%  |
| Yes       | 7        | 41.18%  |

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
| No        | 10       | 62.5%   |
| Yes       | 6        | 37.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 87.5%   |
| Yes       | 2        | 12.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Italy        | 4        | 25%     |
| USA          | 1        | 6.25%   |
| South Africa | 1        | 6.25%   |
| Slovakia     | 1        | 6.25%   |
| Peru         | 1        | 6.25%   |
| Netherlands  | 1        | 6.25%   |
| Hungary      | 1        | 6.25%   |
| Germany      | 1        | 6.25%   |
| France       | 1        | 6.25%   |
| Bulgaria     | 1        | 6.25%   |
| Brazil       | 1        | 6.25%   |
| Belgium      | 1        | 6.25%   |
| Argentina    | 1        | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Bologna          | 2        | 12.5%   |
| Toalmas          | 1        | 6.25%   |
| The Hague        | 1        | 6.25%   |
| Sofia            | 1        | 6.25%   |
| Savona           | 1        | 6.25%   |
| Rostock          | 1        | 6.25%   |
| Rome             | 1        | 6.25%   |
| Posadas          | 1        | 6.25%   |
| Lima             | 1        | 6.25%   |
| Johannesburg     | 1        | 6.25%   |
| Guarulhos        | 1        | 6.25%   |
| Grand Junction   | 1        | 6.25%   |
| Brussels         | 1        | 6.25%   |
| Bratislava       | 1        | 6.25%   |
| Boulogne-sur-Mer | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 27.27%  |
| Seagate             | 6        | 8      | 27.27%  |
| Samsung Electronics | 2        | 2      | 9.09%   |
| Unknown (CF)        | 1        | 1      | 4.55%   |
| Transcend           | 1        | 1      | 4.55%   |
| SanDisk             | 1        | 1      | 4.55%   |
| Maxtor              | 1        | 1      | 4.55%   |
| Kingston            | 1        | 1      | 4.55%   |
| Crucial             | 1        | 2      | 4.55%   |
| China               | 1        | 2      | 4.55%   |
| A-DATA Technology   | 1        | 1      | 4.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WDS500G2B0B-00YS70 500GB SSD  | 1        | 4%      |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 4%      |
| WDC WD400BD-23JMC0 40GB           | 1        | 4%      |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 4%      |
| WDC WD1600AAJS-00L7A0 160GB       | 1        | 4%      |
| WDC WD10EFRX-68JCSN0 1TB          | 1        | 4%      |
| Unknown (CF) Card 16GB SSD        | 1        | 4%      |
| Transcend TS32GHSD370 32GB SSD    | 1        | 4%      |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 4%      |
| Seagate ST3500413AS 500GB         | 1        | 4%      |
| Seagate ST3320820SCE 320GB        | 1        | 4%      |
| Seagate ST3160815AS 160GB         | 1        | 4%      |
| Seagate ST3160812AS 160GB         | 1        | 4%      |
| Seagate ST310211A 10GB            | 1        | 4%      |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 4%      |
| SanDisk SDSSDA120G 120GB          | 1        | 4%      |
| Samsung SSD 860 EVO 250GB         | 1        | 4%      |
| Samsung HD081GJ 80GB              | 1        | 4%      |
| Maxtor 6Y080L0 82GB               | 1        | 4%      |
| Kingston OM8P0S3512F-00 512GB SSD | 1        | 4%      |
| Crucial CT500P2SSD8 500GB         | 1        | 4%      |
| Crucial CT120BX500SSD1 120GB      | 1        | 4%      |
| China SSD 256GB                   | 1        | 4%      |
| China SSD 120GB                   | 1        | 4%      |
| A-DATA SX8200PNP 512GB            | 1        | 4%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 8      | 50%     |
| WDC                 | 4        | 4      | 33.33%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Maxtor              | 1        | 1      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 22.22%  |
| Unknown (CF)        | 1        | 1      | 11.11%  |
| Transcend           | 1        | 1      | 11.11%  |
| SanDisk             | 1        | 1      | 11.11%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| Kingston            | 1        | 1      | 11.11%  |
| Crucial             | 1        | 1      | 11.11%  |
| China               | 1        | 2      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 14     | 47.37%  |
| SSD  | 8        | 10     | 42.11%  |
| NVMe | 2        | 2      | 10.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 15       | 24     | 88.24%  |
| NVMe | 2        | 2      | 11.76%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 13       | 20     | 76.47%  |
| 0.51-1.0   | 3        | 3      | 17.65%  |
| 4.01-10.0  | 1        | 1      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 4        | 23.53%  |
| 101-250        | 3        | 17.65%  |
| 21-50          | 2        | 11.76%  |
| 1001-2000      | 2        | 11.76%  |
| 1-20           | 2        | 11.76%  |
| 51-100         | 2        | 11.76%  |
| More than 3000 | 1        | 5.88%   |
| 501-1000       | 1        | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 10       | 58.82%  |
| 21-50          | 2        | 11.76%  |
| 101-250        | 2        | 11.76%  |
| More than 3000 | 1        | 5.88%   |
| 501-1000       | 1        | 5.88%   |
| 51-100         | 1        | 5.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD | 1        | 1      | 20%     |
| WDC WD400BD-23JMC0 40GB          | 1        | 1      | 20%     |
| WDC WD1600AAJS-75M0A0 160GB      | 1        | 1      | 20%     |
| Seagate ST3320820SCE 320GB       | 1        | 2      | 20%     |
| Maxtor 6Y080L0 82GB              | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 3      | 60%     |
| Seagate | 1        | 2      | 20%     |
| Maxtor  | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 50%     |
| Seagate | 1        | 2      | 25%     |
| Maxtor  | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 5      | 75%     |
| SSD  | 1        | 1      | 25%     |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 13       | 20     | 76.47%  |
| Malfunc | 4        | 6      | 23.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 7        | 36.84%  |
| AMD                              | 5        | 26.32%  |
| Silicon Integrated Systems [SiS] | 2        | 10.53%  |
| VIA Technologies                 | 1        | 5.26%   |
| Nvidia                           | 1        | 5.26%   |
| Micron/Crucial Technology        | 1        | 5.26%   |
| ASMedia Technology               | 1        | 5.26%   |
| ADATA Technology                 | 1        | 5.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 5        | 19.23%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                          | 2        | 7.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 7.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 7.69%   |
| VIA VX900 Series Serial-ATA Controller                                        | 1        | 3.85%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]     | 1        | 3.85%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 3.85%   |
| Nvidia MCP61 IDE                                                              | 1        | 3.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1        | 3.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1        | 3.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 1        | 3.85%   |
| Intel 82801DB (ICH4) IDE Controller                                           | 1        | 3.85%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 3.85%   |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 3.85%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 3.85%   |
| AMD 300 Series Chipset SATA Controller                                        | 1        | 3.85%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1        | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 9        | 45%     |
| IDE  | 8        | 40%     |
| NVMe | 2        | 10%     |
| RAID | 1        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 8        | 50%     |
| AMD          | 7        | 43.75%  |
| CentaurHauls | 1        | 6.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 6.25%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 6.25%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1        | 6.25%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1        | 6.25%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 6.25%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 6.25%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 6.25%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1        | 6.25%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz       | 1        | 6.25%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 6.25%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1        | 6.25%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1        | 6.25%   |
| AMD Athlon Processor                            | 1        | 6.25%   |
| AMD Athlon II X2 250 Processor                  | 1        | 6.25%   |
| AMD Athlon 200GE with Radeon Vega Graphics      | 1        | 6.25%   |
| AMD A4-5300B APU with Radeon HD Graphics        | 1        | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium Dual-Core | 2        | 12.5%   |
| Intel Pentium 4         | 2        | 12.5%   |
| AMD Ryzen 7             | 2        | 12.5%   |
| AMD Athlon              | 2        | 12.5%   |
| Intel Core i7           | 1        | 6.25%   |
| Intel Core i5           | 1        | 6.25%   |
| Intel Celeron           | 1        | 6.25%   |
| Intel Atom              | 1        | 6.25%   |
| CentaurHauls VIA Eden   | 1        | 6.25%   |
| AMD Ryzen 5 PRO         | 1        | 6.25%   |
| AMD Athlon II X2        | 1        | 6.25%   |
| AMD A4                  | 1        | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 31.25%  |
| 1      | 5        | 31.25%  |
| 4      | 4        | 25%     |
| 8      | 2        | 12.5%   |

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
| 2      | 8        | 50%     |
| 1      | 8        | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 13       | 81.25%  |
| 32-bit         | 3        | 18.75%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 18.75%  |
| 0x206a7    | 2        | 12.5%   |
| 0x1067a    | 2        | 12.5%   |
| 0x0810100b | 2        | 12.5%   |
| 0xf49      | 1        | 6.25%   |
| 0xf27      | 1        | 6.25%   |
| 0x106c2    | 1        | 6.25%   |
| 0x08701013 | 1        | 6.25%   |
| 0x0800820d | 1        | 6.25%   |
| 0x0600111f | 1        | 6.25%   |
| 0x010000c8 | 1        | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen         | 2        | 12.5%   |
| SandyBridge | 2        | 12.5%   |
| Penryn      | 2        | 12.5%   |
| NetBurst    | 2        | 12.5%   |
| Zen+        | 1        | 6.25%   |
| Zen 2       | 1        | 6.25%   |
| Piledriver  | 1        | 6.25%   |
| K6          | 1        | 6.25%   |
| K10         | 1        | 6.25%   |
| Goldmont    | 1        | 6.25%   |
| Bonnell     | 1        | 6.25%   |
| Unknown     | 1        | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 6        | 37.5%   |
| Nvidia                           | 4        | 25%     |
| AMD                              | 3        | 18.75%  |
| Silicon Integrated Systems [SiS] | 2        | 12.5%   |
| VIA Technologies                 | 1        | 6.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2        | 11.76%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2        | 11.76%  |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2        | 11.76%  |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1        | 5.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1        | 5.88%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1        | 5.88%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1        | 5.88%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1        | 5.88%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 1        | 5.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 1        | 5.88%   |
| Intel HD Graphics 500                                                                      | 1        | 5.88%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1        | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 1        | 5.88%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                            | 1        | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 6        | 37.5%   |
| 1 x Nvidia | 4        | 25%     |
| 1 x AMD    | 3        | 18.75%  |
| 1 x SiS    | 2        | 12.5%   |
| 1 x VIA    | 1        | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 11       | 68.75%  |
| Unknown     | 3        | 18.75%  |
| Proprietary | 2        | 12.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 56.25%  |
| 1.01-2.0   | 2        | 12.5%   |
| 0.51-1.0   | 2        | 12.5%   |
| 0.01-0.5   | 2        | 12.5%   |
| 3.01-4.0   | 1        | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Philips             | 3        | 21.43%  |
| Samsung Electronics | 2        | 14.29%  |
| ViewSonic           | 1        | 7.14%   |
| VIE                 | 1        | 7.14%   |
| Orion               | 1        | 7.14%   |
| Iiyama              | 1        | 7.14%   |
| Hewlett-Packard     | 1        | 7.14%   |
| Goldstar            | 1        | 7.14%   |
| Dell                | 1        | 7.14%   |
| AOC                 | 1        | 7.14%   |
| Acer                | 1        | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3        | 21.43%  |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1        | 7.14%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1        | 7.14%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1        | 7.14%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1        | 7.14%   |
| Orion ORION ORN120A 1920x540                                            | 1        | 7.14%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1        | 7.14%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1        | 7.14%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1        | 7.14%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                      | 1        | 7.14%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                        | 1        | 7.14%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                      | 1        | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 42.86%  |
| 1600x900 (HD+)     | 2        | 14.29%  |
| 3840x2160 (4K)     | 1        | 7.14%   |
| 1920x540           | 1        | 7.14%   |
| 1920x1200 (WUXGA)  | 1        | 7.14%   |
| 1680x1050 (WSXGA+) | 1        | 7.14%   |
| 1366x768 (WXGA)    | 1        | 7.14%   |
| 1280x1024 (SXGA)   | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 35.71%  |
| 31      | 1        | 7.14%   |
| 23      | 1        | 7.14%   |
| 22      | 1        | 7.14%   |
| 21      | 1        | 7.14%   |
| 20      | 1        | 7.14%   |
| 19      | 1        | 7.14%   |
| 17      | 1        | 7.14%   |
| 15      | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 42.86%  |
| 401-500     | 4        | 28.57%  |
| 301-350     | 2        | 14.29%  |
| 601-700     | 1        | 7.14%   |
| Unknown     | 1        | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 8        | 61.54%  |
| 16/10 | 3        | 23.08%  |
| 5/4   | 1        | 7.69%   |
| 32/9  | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 42.86%  |
| 251-300        | 2        | 14.29%  |
| 151-200        | 2        | 14.29%  |
| 351-500        | 1        | 7.14%   |
| 141-150        | 1        | 7.14%   |
| 101-110        | 1        | 7.14%   |
| Unknown        | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 71.43%  |
| 101-120 | 2        | 14.29%  |
| 121-160 | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 87.5%   |
| 3     | 1        | 6.25%   |
| 0     | 1        | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 14       | 63.64%  |
| Intel                            | 2        | 9.09%   |
| Silicon Integrated Systems [SiS] | 1        | 4.55%   |
| Ralink                           | 1        | 4.55%   |
| Qualcomm Atheros                 | 1        | 4.55%   |
| IBM                              | 1        | 4.55%   |
| Guillemot                        | 1        | 4.55%   |
| Broadcom Limited                 | 1        | 4.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 9        | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 2        | 8.33%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                 | 1        | 4.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 4.17%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 4.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 1        | 4.17%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                | 1        | 4.17%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 4.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1        | 4.17%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 4.17%   |
| Intel Wi-Fi 6 AX200                                                       | 1        | 4.17%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                        | 1        | 4.17%   |
| IBM Winnipeg PCI-X Host Bridge                                            | 1        | 4.17%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 4.17%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 33.33%  |
| Ralink                | 1        | 16.67%  |
| Qualcomm Atheros      | 1        | 16.67%  |
| Intel                 | 1        | 16.67%  |
| Guillemot             | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 16.67%  |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 16.67%  |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 16.67%  |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 16.67%  |
| Intel Wi-Fi 6 AX200                                                       | 1        | 16.67%  |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 13       | 76.47%  |
| Silicon Integrated Systems [SiS] | 1        | 5.88%   |
| Qualcomm Atheros                 | 1        | 5.88%   |
| Intel                            | 1        | 5.88%   |
| Broadcom Limited                 | 1        | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 52.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 11.76%  |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 5.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 5.88%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 5.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 5.88%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1        | 5.88%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 69.57%  |
| WiFi     | 6        | 26.09%  |
| Unknown  | 1        | 4.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 80%     |
| WiFi     | 3        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 68.75%  |
| 2     | 4        | 25%     |
| 3     | 1        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 87.5%   |
| Yes  | 2        | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 1        | 50%     |
| Cambridge Silicon Radio | 1        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 1        | 50%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 7        | 38.89%  |
| AMD                              | 5        | 27.78%  |
| Nvidia                           | 4        | 22.22%  |
| VIA Technologies                 | 1        | 5.56%   |
| Silicon Integrated Systems [SiS] | 1        | 5.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 13.64%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 9.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 9.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 9.09%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 4.55%   |
| VIA Technologies High Definition Audio Controller                          | 1        | 4.55%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 4.55%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 4.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 4.55%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 4.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 4.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 4.55%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 4.55%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 4.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 4.55%   |
| AMD FCH Azalia Controller                                                  | 1        | 4.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 4.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 6        | 35.29%  |
| SK hynix          | 2        | 11.76%  |
| Kingston          | 2        | 11.76%  |
| Transcend         | 1        | 5.88%   |
| Teikon            | 1        | 5.88%   |
| Team              | 1        | 5.88%   |
| S                 | 1        | 5.88%   |
| M                 | 1        | 5.88%   |
| Crucial           | 1        | 5.88%   |
| A-DATA Technology | 1        | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1        | 5.88%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 5.88%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                | 1        | 5.88%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s            | 1        | 5.88%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 5.88%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                 | 1        | 5.88%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s              | 1        | 5.88%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s     | 1        | 5.88%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s       | 1        | 5.88%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM 1600MT/s          | 1        | 5.88%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM 1334MT/s     | 1        | 5.88%   |
| S RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 5.88%   |
| M RAM Module 1GB DIMM DDR3 1333MT/s                      | 1        | 5.88%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s   | 1        | 5.88%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s  | 1        | 5.88%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s | 1        | 5.88%   |
| A-DATA RAM Module 4GB DIMM DDR4 2666MT/s                 | 1        | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 5        | 31.25%  |
| SDRAM   | 4        | 25%     |
| DDR4    | 4        | 25%     |
| Unknown | 2        | 12.5%   |
| DDR2    | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 13       | 81.25%  |
| SODIMM | 3        | 18.75%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 5        | 29.41%  |
| 8192  | 3        | 17.65%  |
| 1024  | 3        | 17.65%  |
| 4096  | 2        | 11.76%  |
| 512   | 2        | 11.76%  |
| 32768 | 1        | 5.88%   |
| 16384 | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 2        | 12.5%   |
| 1600    | 2        | 12.5%   |
| 1333    | 2        | 12.5%   |
| Unknown | 2        | 12.5%   |
| 3600    | 1        | 6.25%   |
| 2666    | 1        | 6.25%   |
| 1334    | 1        | 6.25%   |
| 1066    | 1        | 6.25%   |
| 800     | 1        | 6.25%   |
| 533     | 1        | 6.25%   |
| 400     | 1        | 6.25%   |
| 266     | 1        | 6.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Brother HL-1110 series | 1        | 100%    |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| KYE Systems (Mouse Systems) | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam | 1        | 100%    |

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
| 0     | 13       | 81.25%  |
| 1     | 2        | 12.5%   |
| 2     | 1        | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 3        | 75%     |
| Network       | 1        | 25%     |

