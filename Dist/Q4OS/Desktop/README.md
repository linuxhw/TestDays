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

Total: 15

| Vendor        | Model           | Probe                                                      | Date         |
|---------------|-----------------|------------------------------------------------------------|--------------|
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
| Q4OS 4 | 8        | 61.54%  |
| Q4OS 3 | 5        | 38.46%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Q4OS | 13       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.10.0-19-amd64   | 4        | 30.77%  |
| 6.0.0-1-amd64     | 1        | 7.69%   |
| 5.10.0-9-686-pae  | 1        | 7.69%   |
| 5.10.0-14-amd64   | 1        | 7.69%   |
| 5.10.0-10-686-pae | 1        | 7.69%   |
| 4.19.0-6-amd64    | 1        | 7.69%   |
| 4.19.0-21-amd64   | 1        | 7.69%   |
| 4.19.0-17-686-pae | 1        | 7.69%   |
| 4.19.0-16-amd64   | 1        | 7.69%   |
| 4.19.0-16-686     | 1        | 7.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 7        | 53.85%  |
| 4.19.0  | 5        | 38.46%  |
| 6.0.0   | 1        | 7.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 7        | 53.85%  |
| 4.19    | 5        | 38.46%  |
| 6.0     | 1        | 7.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 9        | 69.23%  |
| i686   | 4        | 30.77%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Trinity | 10       | 76.92%  |
| KDE5    | 2        | 15.38%  |
| LXDE    | 1        | 7.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 13       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 10       | 76.92%  |
| SDDM    | 2        | 15.38%  |
| LightDM | 1        | 7.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| it_IT | 3        | 23.08%  |
| en_US | 2        | 15.38%  |
| sk_SK | 1        | 7.69%   |
| pt_BR | 1        | 7.69%   |
| fr_FR | 1        | 7.69%   |
| es_AR | 1        | 7.69%   |
| en_ZA | 1        | 7.69%   |
| en_IE | 1        | 7.69%   |
| de_DE | 1        | 7.69%   |
| bg_BG | 1        | 7.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 10       | 76.92%  |
| EFI  | 3        | 23.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 13       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 7        | 53.85%  |
| MBR  | 6        | 46.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 92.31%  |
| Yes       | 1        | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 53.85%  |
| Yes       | 6        | 46.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASRock                      | 4        | 30.77%  |
| MSI                         | 3        | 23.08%  |
| Gigabyte Technology         | 2        | 15.38%  |
| TECO Electric and Machinery | 1        | 7.69%   |
| Foxconn                     | 1        | 7.69%   |
| Compaq                      | 1        | 7.69%   |
| BESSTAR Tech                | 1        | 7.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| TECO Electric and Machinery FUTRO S400 | 1        | 7.69%   |
| MSI MS-7C56                            | 1        | 7.69%   |
| MSI MS-7597                            | 1        | 7.69%   |
| MSI MS-7592                            | 1        | 7.69%   |
| Gigabyte XP-M5S661GX                   | 1        | 7.69%   |
| Gigabyte AB350-Gaming                  | 1        | 7.69%   |
| Foxconn Pro 3400 Series MT             | 1        | 7.69%   |
| Compaq Evo D510 SFF                    | 1        | 7.69%   |
| BESSTAR Tech UM250                     | 1        | 7.69%   |
| ASRock J3455B-ITX                      | 1        | 7.69%   |
| ASRock H61M-HVS                        | 1        | 7.69%   |
| ASRock G41M-VS3                        | 1        | 7.69%   |
| ASRock B450M Pro4                      | 1        | 7.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| TECO Electric and Machinery FUTRO | 1        | 7.69%   |
| MSI MS-7C56                       | 1        | 7.69%   |
| MSI MS-7597                       | 1        | 7.69%   |
| MSI MS-7592                       | 1        | 7.69%   |
| Gigabyte XP-M5S661GX              | 1        | 7.69%   |
| Gigabyte AB350-Gaming             | 1        | 7.69%   |
| Foxconn Pro                       | 1        | 7.69%   |
| Compaq Evo                        | 1        | 7.69%   |
| BESSTAR Tech UM250                | 1        | 7.69%   |
| ASRock J3455B-ITX                 | 1        | 7.69%   |
| ASRock H61M-HVS                   | 1        | 7.69%   |
| ASRock G41M-VS3                   | 1        | 7.69%   |
| ASRock B450M                      | 1        | 7.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 3        | 23.08%  |
| 2021 | 1        | 7.69%   |
| 2020 | 1        | 7.69%   |
| 2018 | 1        | 7.69%   |
| 2017 | 1        | 7.69%   |
| 2016 | 1        | 7.69%   |
| 2010 | 1        | 7.69%   |
| 2009 | 1        | 7.69%   |
| 2008 | 1        | 7.69%   |
| 2005 | 1        | 7.69%   |
| 2002 | 1        | 7.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 13       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 13       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 2        | 15.38%  |
| 2.01-3.0    | 2        | 15.38%  |
| 16.01-24.0  | 2        | 15.38%  |
| 4.01-8.0    | 1        | 7.69%   |
| 32.01-64.0  | 1        | 7.69%   |
| 64.01-256.0 | 1        | 7.69%   |
| 1.01-2.0    | 1        | 7.69%   |
| 8.01-16.0   | 1        | 7.69%   |
| 0.51-1.0    | 1        | 7.69%   |
| 0.01-0.5    | 1        | 7.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 4        | 30.77%  |
| 0.51-1.0  | 4        | 30.77%  |
| 4.01-8.0  | 1        | 7.69%   |
| 3.01-4.0  | 1        | 7.69%   |
| 1.01-2.0  | 1        | 7.69%   |
| 8.01-16.0 | 1        | 7.69%   |
| 0.01-0.5  | 1        | 7.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 61.54%  |
| 3      | 3        | 23.08%  |
| 2      | 2        | 15.38%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 53.85%  |
| Yes       | 6        | 46.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 76.92%  |
| Yes       | 3        | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 84.62%  |
| Yes       | 2        | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Italy        | 3        | 23.08%  |
| USA          | 1        | 7.69%   |
| South Africa | 1        | 7.69%   |
| Slovakia     | 1        | 7.69%   |
| Netherlands  | 1        | 7.69%   |
| Germany      | 1        | 7.69%   |
| France       | 1        | 7.69%   |
| Bulgaria     | 1        | 7.69%   |
| Brazil       | 1        | 7.69%   |
| Belgium      | 1        | 7.69%   |
| Argentina    | 1        | 7.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Bologna          | 2        | 15.38%  |
| The Hague        | 1        | 7.69%   |
| Sofia            | 1        | 7.69%   |
| Rostock          | 1        | 7.69%   |
| Rome             | 1        | 7.69%   |
| Posadas          | 1        | 7.69%   |
| Johannesburg     | 1        | 7.69%   |
| Guarulhos        | 1        | 7.69%   |
| Grand Junction   | 1        | 7.69%   |
| Brussels         | 1        | 7.69%   |
| Bratislava       | 1        | 7.69%   |
| Boulogne-sur-Mer | 1        | 7.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 27.78%  |
| WDC                 | 4        | 4      | 22.22%  |
| Samsung Electronics | 2        | 2      | 11.11%  |
| Unknown (CF)        | 1        | 1      | 5.56%   |
| SanDisk             | 1        | 1      | 5.56%   |
| Maxtor              | 1        | 1      | 5.56%   |
| Kingston            | 1        | 1      | 5.56%   |
| Crucial             | 1        | 2      | 5.56%   |
| China               | 1        | 2      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WDS500G2B0B-00YS70 500GB SSD  | 1        | 4.76%   |
| WDC WD400BD-23JMC0 40GB           | 1        | 4.76%   |
| WDC WD1600AAJS-00L7A0 160GB       | 1        | 4.76%   |
| WDC WD10EFRX-68JCSN0 1TB          | 1        | 4.76%   |
| Unknown (CF) Card 16GB SSD        | 1        | 4.76%   |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 4.76%   |
| Seagate ST3500413AS 500GB         | 1        | 4.76%   |
| Seagate ST3160815AS 160GB         | 1        | 4.76%   |
| Seagate ST3160812AS 160GB         | 1        | 4.76%   |
| Seagate ST310211A 10GB            | 1        | 4.76%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 4.76%   |
| SanDisk SDSSDA120G 120GB          | 1        | 4.76%   |
| Samsung SSD 860 EVO 250GB         | 1        | 4.76%   |
| Samsung HD081GJ 80GB              | 1        | 4.76%   |
| Maxtor 6Y080L0 81GB               | 1        | 4.76%   |
| Kingston OM8P0S3512F-00 512GB SSD | 1        | 4.76%   |
| Crucial CT500P2SSD8 500GB         | 1        | 4.76%   |
| Crucial CT120BX500SSD1 120GB      | 1        | 4.76%   |
| China SSD 256GB                   | 1        | 4.76%   |
| China SSD 120GB                   | 1        | 4.76%   |
| A-DATA SX8200PNP 512GB            | 1        | 4.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 50%     |
| WDC                 | 3        | 3      | 30%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Maxtor              | 1        | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 14.29%  |
| Unknown (CF)        | 1        | 1      | 14.29%  |
| SanDisk             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| Kingston            | 1        | 1      | 14.29%  |
| Crucial             | 1        | 1      | 14.29%  |
| China               | 1        | 2      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 11     | 50%     |
| SSD  | 6        | 8      | 37.5%   |
| NVMe | 2        | 2      | 12.5%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 12       | 19     | 85.71%  |
| NVMe | 2        | 2      | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 10       | 15     | 71.43%  |
| 0.51-1.0   | 3        | 3      | 21.43%  |
| 4.01-10.0  | 1        | 1      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 3        | 23.08%  |
| 1001-2000      | 2        | 15.38%  |
| 1-20           | 2        | 15.38%  |
| 51-100         | 2        | 15.38%  |
| More than 3000 | 1        | 7.69%   |
| 21-50          | 1        | 7.69%   |
| 101-250        | 1        | 7.69%   |
| 501-1000       | 1        | 7.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 7        | 53.85%  |
| 101-250        | 2        | 15.38%  |
| More than 3000 | 1        | 7.69%   |
| 21-50          | 1        | 7.69%   |
| 501-1000       | 1        | 7.69%   |
| 51-100         | 1        | 7.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| WDC WD400BD-23JMC0 40GB | 1        | 1      | 50%     |
| Maxtor 6Y080L0 81GB     | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 50%     |
| Maxtor | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 50%     |
| Maxtor | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 100%    |

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
| Works   | 12       | 19     | 85.71%  |
| Malfunc | 2        | 2      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 6        | 40%     |
| AMD                              | 4        | 26.67%  |
| Silicon Integrated Systems [SiS] | 2        | 13.33%  |
| Nvidia                           | 1        | 6.67%   |
| Micron/Crucial Technology        | 1        | 6.67%   |
| ADATA Technology                 | 1        | 6.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 4        | 18.18%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                          | 2        | 9.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 9.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2        | 9.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 9.09%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]     | 1        | 4.55%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 4.55%   |
| Nvidia MCP61 IDE                                                              | 1        | 4.55%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1        | 4.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1        | 4.55%   |
| Intel 82801DB (ICH4) IDE Controller                                           | 1        | 4.55%   |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 4.55%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 4.55%   |
| AMD 300 Series Chipset SATA Controller                                        | 1        | 4.55%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1        | 4.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 7        | 43.75%  |
| IDE  | 6        | 37.5%   |
| NVMe | 2        | 12.5%   |
| RAID | 1        | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 53.85%  |
| AMD    | 6        | 46.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 7.69%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 7.69%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1        | 7.69%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1        | 7.69%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 7.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 7.69%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 7.69%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 7.69%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1        | 7.69%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1        | 7.69%   |
| AMD Athlon Processor                            | 1        | 7.69%   |
| AMD Athlon II X2 250 Processor                  | 1        | 7.69%   |
| AMD Athlon 200GE with Radeon Vega Graphics      | 1        | 7.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium Dual-Core | 2        | 15.38%  |
| Intel Pentium 4         | 2        | 15.38%  |
| AMD Ryzen 7             | 2        | 15.38%  |
| AMD Athlon              | 2        | 15.38%  |
| Intel Core i7           | 1        | 7.69%   |
| Intel Core i5           | 1        | 7.69%   |
| Intel Celeron           | 1        | 7.69%   |
| AMD Ryzen 5 PRO         | 1        | 7.69%   |
| AMD Athlon II X2        | 1        | 7.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 4        | 30.77%  |
| 2      | 4        | 30.77%  |
| 1      | 3        | 23.08%  |
| 8      | 2        | 15.38%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 53.85%  |
| 2      | 6        | 46.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 11       | 84.62%  |
| 32-bit         | 2        | 15.38%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 2        | 15.38%  |
| 0x1067a    | 2        | 15.38%  |
| 0x0810100b | 2        | 15.38%  |
| Unknown    | 2        | 15.38%  |
| 0xf49      | 1        | 7.69%   |
| 0xf27      | 1        | 7.69%   |
| 0x08701013 | 1        | 7.69%   |
| 0x0800820d | 1        | 7.69%   |
| 0x010000c8 | 1        | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen         | 2        | 15.38%  |
| SandyBridge | 2        | 15.38%  |
| Penryn      | 2        | 15.38%  |
| NetBurst    | 2        | 15.38%  |
| Zen+        | 1        | 7.69%   |
| Zen 2       | 1        | 7.69%   |
| K6          | 1        | 7.69%   |
| K10         | 1        | 7.69%   |
| Goldmont    | 1        | 7.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 5        | 38.46%  |
| Nvidia                           | 4        | 30.77%  |
| Silicon Integrated Systems [SiS] | 2        | 15.38%  |
| AMD                              | 2        | 15.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2        | 15.38%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2        | 15.38%  |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2        | 15.38%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1        | 7.69%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1        | 7.69%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1        | 7.69%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1        | 7.69%   |
| Intel HD Graphics 500                                                                      | 1        | 7.69%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1        | 7.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 1        | 7.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 5        | 38.46%  |
| 1 x Nvidia | 4        | 30.77%  |
| 1 x SiS    | 2        | 15.38%  |
| 1 x AMD    | 2        | 15.38%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 69.23%  |
| Proprietary | 2        | 15.38%  |
| Unknown     | 2        | 15.38%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 53.85%  |
| 1.01-2.0   | 2        | 15.38%  |
| 0.01-0.5   | 2        | 15.38%  |
| 3.01-4.0   | 1        | 7.69%   |
| 0.51-1.0   | 1        | 7.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Philips             | 3        | 23.08%  |
| Samsung Electronics | 2        | 15.38%  |
| ViewSonic           | 1        | 7.69%   |
| VIE                 | 1        | 7.69%   |
| Orion               | 1        | 7.69%   |
| Iiyama              | 1        | 7.69%   |
| Hewlett-Packard     | 1        | 7.69%   |
| Goldstar            | 1        | 7.69%   |
| AOC                 | 1        | 7.69%   |
| Acer                | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3        | 23.08%  |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1        | 7.69%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1        | 7.69%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1        | 7.69%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1        | 7.69%   |
| Orion ORION ORN120A 1920x540                                            | 1        | 7.69%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1        | 7.69%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1        | 7.69%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1        | 7.69%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                        | 1        | 7.69%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                      | 1        | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 46.15%  |
| 1600x900 (HD+)     | 2        | 15.38%  |
| 3840x2160 (4K)     | 1        | 7.69%   |
| 1920x540           | 1        | 7.69%   |
| 1920x1200 (WUXGA)  | 1        | 7.69%   |
| 1680x1050 (WSXGA+) | 1        | 7.69%   |
| 1366x768 (WXGA)    | 1        | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 38.46%  |
| 31      | 1        | 7.69%   |
| 23      | 1        | 7.69%   |
| 22      | 1        | 7.69%   |
| 21      | 1        | 7.69%   |
| 20      | 1        | 7.69%   |
| 19      | 1        | 7.69%   |
| 15      | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 46.15%  |
| 401-500     | 4        | 30.77%  |
| 601-700     | 1        | 7.69%   |
| 301-350     | 1        | 7.69%   |
| Unknown     | 1        | 7.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 8        | 66.67%  |
| 16/10 | 3        | 25%     |
| 32/9  | 1        | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 46.15%  |
| 251-300        | 2        | 15.38%  |
| 151-200        | 2        | 15.38%  |
| 351-500        | 1        | 7.69%   |
| 101-110        | 1        | 7.69%   |
| Unknown        | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 9        | 69.23%  |
| 101-120 | 2        | 15.38%  |
| 121-160 | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 92.31%  |
| 3     | 1        | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 11       | 64.71%  |
| Intel                            | 2        | 11.76%  |
| Silicon Integrated Systems [SiS] | 1        | 5.88%   |
| Qualcomm Atheros                 | 1        | 5.88%   |
| IBM                              | 1        | 5.88%   |
| Guillemot                        | 1        | 5.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 7        | 38.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 2        | 11.11%  |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                 | 1        | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 1        | 5.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                | 1        | 5.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1        | 5.56%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 5.56%   |
| Intel Wi-Fi 6 AX200                                                       | 1        | 5.56%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                        | 1        | 5.56%   |
| IBM Winnipeg PCI-X Host Bridge                                            | 1        | 5.56%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 5.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Qualcomm Atheros | 1        | 33.33%  |
| Intel            | 1        | 33.33%  |
| Guillemot        | 1        | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 33.33%  |
| Intel Wi-Fi 6 AX200                                                       | 1        | 33.33%  |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 11       | 78.57%  |
| Silicon Integrated Systems [SiS] | 1        | 7.14%   |
| Qualcomm Atheros                 | 1        | 7.14%   |
| Intel                            | 1        | 7.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 14.29%  |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 7.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 7.14%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 7.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 7.14%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1        | 7.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 76.47%  |
| WiFi     | 3        | 17.65%  |
| Unknown  | 1        | 5.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 91.67%  |
| WiFi     | 1        | 8.33%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 76.92%  |
| 2     | 2        | 15.38%  |
| 3     | 1        | 7.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12       | 92.31%  |
| Yes  | 1        | 7.69%   |

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
| Intel                            | 6        | 40%     |
| Nvidia                           | 4        | 26.67%  |
| AMD                              | 4        | 26.67%  |
| Silicon Integrated Systems [SiS] | 1        | 6.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 11.76%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 11.76%  |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 11.76%  |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 11.76%  |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 5.88%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 5.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 5.88%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 5.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 5.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 5.88%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 5.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 5.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 5.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 5        | 38.46%  |
| Kingston          | 2        | 15.38%  |
| Transcend         | 1        | 7.69%   |
| Teikon            | 1        | 7.69%   |
| Team              | 1        | 7.69%   |
| SK hynix          | 1        | 7.69%   |
| Crucial           | 1        | 7.69%   |
| A-DATA Technology | 1        | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1        | 7.69%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 7.69%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                | 1        | 7.69%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s            | 1        | 7.69%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 7.69%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s              | 1        | 7.69%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s     | 1        | 7.69%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s      | 1        | 7.69%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s  | 1        | 7.69%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s   | 1        | 7.69%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s  | 1        | 7.69%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s | 1        | 7.69%   |
| A-DATA RAM Module 4GB DIMM DDR4 2666MT/s                 | 1        | 7.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| SDRAM   | 4        | 30.77%  |
| DDR4    | 4        | 30.77%  |
| DDR3    | 3        | 23.08%  |
| Unknown | 2        | 15.38%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 11       | 84.62%  |
| SODIMM | 2        | 15.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 3        | 23.08%  |
| 2048  | 3        | 23.08%  |
| 4096  | 2        | 15.38%  |
| 512   | 2        | 15.38%  |
| 32768 | 1        | 7.69%   |
| 16384 | 1        | 7.69%   |
| 1024  | 1        | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 2        | 15.38%  |
| 1600    | 2        | 15.38%  |
| Unknown | 2        | 15.38%  |
| 3600    | 1        | 7.69%   |
| 2666    | 1        | 7.69%   |
| 1333    | 1        | 7.69%   |
| 1066    | 1        | 7.69%   |
| 800     | 1        | 7.69%   |
| 400     | 1        | 7.69%   |
| 266     | 1        | 7.69%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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
| 0     | 11       | 84.62%  |
| 2     | 1        | 7.69%   |
| 1     | 1        | 7.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 2        | 66.67%  |
| Network       | 1        | 33.33%  |

