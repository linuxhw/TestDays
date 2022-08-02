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

Total: 8

| Vendor        | Model         | Probe                                                      | Date         |
|---------------|---------------|------------------------------------------------------------|--------------|
| ASRock        | H61M-HVS      | [a9ee15a4d2](https://linux-hardware.org/?probe=a9ee15a4d2) | May 13, 2022 |
| Compaq        | 07E4h         | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| Gigabyte      | XP-M5S661GX   | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| TECO Elect... | TR53A0        | [4ab721c7f7](https://linux-hardware.org/?probe=4ab721c7f7) | Aug 19, 2021 |
| MSI           | B550-A PRO    | [546cf15192](https://linux-hardware.org/?probe=546cf15192) | Jun 16, 2021 |
| MSI           | GF615M-P33 V2 | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| ASRock        | G41M-VS3      | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3      | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Q4OS 3 | 4        | 57.14%  |
| Q4OS 4 | 3        | 42.86%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Q4OS | 7        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.10.0-9-686-pae  | 1        | 14.29%  |
| 5.10.0-14-amd64   | 1        | 14.29%  |
| 5.10.0-10-686-pae | 1        | 14.29%  |
| 4.19.0-6-amd64    | 1        | 14.29%  |
| 4.19.0-17-686-pae | 1        | 14.29%  |
| 4.19.0-16-amd64   | 1        | 14.29%  |
| 4.19.0-16-686     | 1        | 14.29%  |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 4        | 57.14%  |
| 5.10.0  | 3        | 42.86%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 4        | 57.14%  |
| 5.10    | 3        | 42.86%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| i686   | 4        | 57.14%  |
| x86_64 | 3        | 42.86%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| trinity | 5        | 71.43%  |
| KDE5    | 2        | 28.57%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 7        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| TDM  | 5        | 71.43%  |
| SDDM | 2        | 28.57%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 2        | 28.57%  |
| pt_BR | 1        | 14.29%  |
| fr_FR | 1        | 14.29%  |
| es_AR | 1        | 14.29%  |
| en_ZA | 1        | 14.29%  |
| de_DE | 1        | 14.29%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 6        | 85.71%  |
| EFI  | 1        | 14.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 7        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 5        | 71.43%  |
| GPT  | 2        | 28.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 85.71%  |
| Yes       | 1        | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4        | 57.14%  |
| No        | 3        | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| MSI                         | 2        | 28.57%  |
| ASRock                      | 2        | 28.57%  |
| TECO Electric and Machinery | 1        | 14.29%  |
| Gigabyte Technology         | 1        | 14.29%  |
| Compaq                      | 1        | 14.29%  |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| TECO Electric and Machinery FUTRO S400 | 1        | 14.29%  |
| MSI MS-7C56                            | 1        | 14.29%  |
| MSI MS-7597                            | 1        | 14.29%  |
| Gigabyte XP-M5S661GX                   | 1        | 14.29%  |
| Compaq Evo D510 SFF                    | 1        | 14.29%  |
| ASRock H61M-HVS                        | 1        | 14.29%  |
| ASRock G41M-VS3                        | 1        | 14.29%  |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| TECO Electric and Machinery FUTRO | 1        | 14.29%  |
| MSI MS-7C56                       | 1        | 14.29%  |
| MSI MS-7597                       | 1        | 14.29%  |
| Gigabyte XP-M5S661GX              | 1        | 14.29%  |
| Compaq Evo                        | 1        | 14.29%  |
| ASRock H61M-HVS                   | 1        | 14.29%  |
| ASRock G41M-VS3                   | 1        | 14.29%  |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 2        | 28.57%  |
| 2020 | 1        | 14.29%  |
| 2010 | 1        | 14.29%  |
| 2008 | 1        | 14.29%  |
| 2005 | 1        | 14.29%  |
| 2002 | 1        | 14.29%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 7        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 7        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 7        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 2        | 28.57%  |
| 64.01-256.0 | 1        | 14.29%  |
| 16.01-24.0  | 1        | 14.29%  |
| 1.01-2.0    | 1        | 14.29%  |
| 0.51-1.0    | 1        | 14.29%  |
| 0.01-0.5    | 1        | 14.29%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 4        | 57.14%  |
| 2.01-3.0  | 1        | 14.29%  |
| 8.01-16.0 | 1        | 14.29%  |
| 0.01-0.5  | 1        | 14.29%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 3        | 42.86%  |
| 1      | 3        | 42.86%  |
| 2      | 1        | 14.29%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4        | 57.14%  |
| Yes       | 3        | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 85.71%  |
| Yes       | 1        | 14.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 85.71%  |
| Yes       | 1        | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1        | 14.29%  |
| South Africa | 1        | 14.29%  |
| Netherlands  | 1        | 14.29%  |
| Germany      | 1        | 14.29%  |
| France       | 1        | 14.29%  |
| Brazil       | 1        | 14.29%  |
| Argentina    | 1        | 14.29%  |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| The Hague        | 1        | 14.29%  |
| Rostock          | 1        | 14.29%  |
| Posadas          | 1        | 14.29%  |
| Johannesburg     | 1        | 14.29%  |
| Guarulhos        | 1        | 14.29%  |
| Grand Junction   | 1        | 14.29%  |
| Boulogne-sur-Mer | 1        | 14.29%  |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 33.33%  |
| WDC                 | 3        | 3      | 25%     |
| Unknown (CF)        | 1        | 1      | 8.33%   |
| SanDisk             | 1        | 1      | 8.33%   |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Maxtor              | 1        | 1      | 8.33%   |
| China               | 1        | 2      | 8.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 7.14%   |
| WDC WD400BD-23JMC0 40GB          | 1        | 7.14%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1        | 7.14%   |
| Unknown (CF) Card 16GB SSD       | 1        | 7.14%   |
| Seagate ST8000DM004-2CX188 8TB   | 1        | 7.14%   |
| Seagate ST3160815AS 160GB        | 1        | 7.14%   |
| Seagate ST3160812AS 160GB        | 1        | 7.14%   |
| Seagate ST310211A 10GB           | 1        | 7.14%   |
| Seagate ST1000DM003-1ER162 1TB   | 1        | 7.14%   |
| SanDisk SDSSDA120G 120GB         | 1        | 7.14%   |
| Samsung HD081GJ 80GB             | 1        | 7.14%   |
| Maxtor 6Y080L0 82GB              | 1        | 7.14%   |
| China SSD 256GB                  | 1        | 7.14%   |
| China SSD 120GB                  | 1        | 7.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 50%     |
| WDC                 | 2        | 2      | 25%     |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Maxtor              | 1        | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor       | Desktops | Drives | Percent |
|--------------|----------|--------|---------|
| WDC          | 1        | 1      | 25%     |
| Unknown (CF) | 1        | 1      | 25%     |
| SanDisk      | 1        | 1      | 25%     |
| China        | 1        | 2      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 9      | 66.67%  |
| SSD  | 3        | 5      | 33.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 7        | 14     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 7        | 12     | 77.78%  |
| 4.01-10.0  | 1        | 1      | 11.11%  |
| 0.51-1.0   | 1        | 1      | 11.11%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 2        | 28.57%  |
| 51-100         | 2        | 28.57%  |
| More than 3000 | 1        | 14.29%  |
| 21-50          | 1        | 14.29%  |
| 1001-2000      | 1        | 14.29%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 4        | 57.14%  |
| More than 3000 | 1        | 14.29%  |
| 21-50          | 1        | 14.29%  |
| 501-1000       | 1        | 14.29%  |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| WDC WD400BD-23JMC0 40GB | 1        | 1      | 50%     |
| Maxtor 6Y080L0 82GB     | 1        | 1      | 50%     |

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
| Works   | 6        | 12     | 75%     |
| Malfunc | 2        | 2      | 25%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3        | 42.86%  |
| Silicon Integrated Systems [SiS] | 2        | 28.57%  |
| Nvidia                           | 1        | 14.29%  |
| AMD                              | 1        | 14.29%  |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 5513 IDE Controller                          | 2        | 18.18%  |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]     | 1        | 9.09%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 9.09%   |
| Nvidia MCP61 IDE                                                              | 1        | 9.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1        | 9.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1        | 9.09%   |
| Intel 82801DB (ICH4) IDE Controller                                           | 1        | 9.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1        | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1        | 9.09%   |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 9.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 5        | 62.5%   |
| SATA | 2        | 25%     |
| RAID | 1        | 12.5%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 4        | 57.14%  |
| AMD    | 3        | 42.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 14.29%  |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 14.29%  |
| Intel Pentium 4 CPU 2.00GHz                 | 1        | 14.29%  |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 14.29%  |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 14.29%  |
| AMD Athlon Processor                        | 1        | 14.29%  |
| AMD Athlon II X2 250 Processor              | 1        | 14.29%  |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium 4         | 2        | 28.57%  |
| Intel Pentium Dual-Core | 1        | 14.29%  |
| Intel Core i7           | 1        | 14.29%  |
| AMD Ryzen 7             | 1        | 14.29%  |
| AMD Athlon II X2        | 1        | 14.29%  |
| AMD Athlon              | 1        | 14.29%  |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3        | 42.86%  |
| 2      | 2        | 28.57%  |
| 8      | 1        | 14.29%  |
| 4      | 1        | 14.29%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4        | 57.14%  |
| 2      | 3        | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 5        | 71.43%  |
| 32-bit         | 2        | 28.57%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xf49      | 1        | 14.29%  |
| 0xf27      | 1        | 14.29%  |
| 0x206a7    | 1        | 14.29%  |
| 0x1067a    | 1        | 14.29%  |
| 0x0800820d | 1        | 14.29%  |
| 0x010000c8 | 1        | 14.29%  |
| Unknown    | 1        | 14.29%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| NetBurst    | 2        | 28.57%  |
| Zen+        | 1        | 14.29%  |
| SandyBridge | 1        | 14.29%  |
| Penryn      | 1        | 14.29%  |
| K6          | 1        | 14.29%  |
| K10         | 1        | 14.29%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 3        | 42.86%  |
| Silicon Integrated Systems [SiS] | 2        | 28.57%  |
| Intel                            | 2        | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2        | 28.57%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1        | 14.29%  |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1        | 14.29%  |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1        | 14.29%  |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1        | 14.29%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 1        | 14.29%  |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 3        | 42.86%  |
| 1 x SiS    | 2        | 28.57%  |
| 1 x Intel  | 2        | 28.57%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3        | 42.86%  |
| Proprietary | 2        | 28.57%  |
| Unknown     | 2        | 28.57%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 57.14%  |
| 3.01-4.0   | 1        | 14.29%  |
| 1.01-2.0   | 1        | 14.29%  |
| 0.01-0.5   | 1        | 14.29%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 28.57%  |
| ViewSonic           | 1        | 14.29%  |
| VIE                 | 1        | 14.29%  |
| Orion               | 1        | 14.29%  |
| Hewlett-Packard     | 1        | 14.29%  |
| Goldstar            | 1        | 14.29%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1        | 14.29%  |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1        | 14.29%  |
| Samsung Electronics SMB1630N SAM0630 1366x768 340x190mm 15.3-inch       | 1        | 14.29%  |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1        | 14.29%  |
| Orion ORION ORN120A 1920x540                                            | 1        | 14.29%  |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1        | 14.29%  |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1        | 14.29%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1600x900 (HD+)     | 2        | 28.57%  |
| 3840x2160 (4K)     | 1        | 14.29%  |
| 1920x540           | 1        | 14.29%  |
| 1920x1080 (FHD)    | 1        | 14.29%  |
| 1680x1050 (WSXGA+) | 1        | 14.29%  |
| 1366x768 (WXGA)    | 1        | 14.29%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 31      | 1        | 14.29%  |
| 23      | 1        | 14.29%  |
| 22      | 1        | 14.29%  |
| 20      | 1        | 14.29%  |
| 19      | 1        | 14.29%  |
| 15      | 1        | 14.29%  |
| Unknown | 1        | 14.29%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 3        | 42.86%  |
| 601-700     | 1        | 14.29%  |
| 501-600     | 1        | 14.29%  |
| 301-350     | 1        | 14.29%  |
| Unknown     | 1        | 14.29%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 4        | 66.67%  |
| 32/9  | 1        | 16.67%  |
| 16/10 | 1        | 16.67%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2        | 28.57%  |
| 151-200        | 2        | 28.57%  |
| 351-500        | 1        | 14.29%  |
| 101-110        | 1        | 14.29%  |
| Unknown        | 1        | 14.29%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4        | 57.14%  |
| 121-160 | 1        | 14.29%  |
| 101-120 | 1        | 14.29%  |
| Unknown | 1        | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 6        | 85.71%  |
| 3     | 1        | 14.29%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 5        | 55.56%  |
| Silicon Integrated Systems [SiS] | 1        | 11.11%  |
| Qualcomm Atheros                 | 1        | 11.11%  |
| Intel                            | 1        | 11.11%  |
| IBM                              | 1        | 11.11%  |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 2        | 20%     |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet           | 1        | 10%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 10%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 1        | 10%     |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 10%     |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 10%     |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 10%     |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                  | 1        | 10%     |
| IBM Winnipeg PCI-X Host Bridge                                      | 1        | 10%     |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Qualcomm Atheros | 1        | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 100%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 5        | 62.5%   |
| Silicon Integrated Systems [SiS] | 1        | 12.5%   |
| Qualcomm Atheros                 | 1        | 12.5%   |
| Intel                            | 1        | 12.5%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2        | 25%     |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 12.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 12.5%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 12.5%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 12.5%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1        | 12.5%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 7        | 77.78%  |
| WiFi     | 1        | 11.11%  |
| Unknown  | 1        | 11.11%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 6        | 85.71%  |
| WiFi     | 1        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5        | 71.43%  |
| 2     | 2        | 28.57%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 6        | 85.71%  |
| Yes  | 1        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 1        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 3        | 37.5%   |
| Intel                            | 3        | 37.5%   |
| Silicon Integrated Systems [SiS] | 1        | 12.5%   |
| AMD                              | 1        | 12.5%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 12.5%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 12.5%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 12.5%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 12.5%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 12.5%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 12.5%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 12.5%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 12.5%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Unknown   | 4        | 57.14%  |
| Transcend | 1        | 14.29%  |
| Teikon    | 1        | 14.29%  |
| Team      | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 400MT/s                | 1        | 14.29%  |
| Unknown RAM Module 512MB DIMM                        | 1        | 14.29%  |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s        | 1        | 14.29%  |
| Unknown RAM Module 2048MB DIMM SDRAM                 | 1        | 14.29%  |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s          | 1        | 14.29%  |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s | 1        | 14.29%  |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s   | 1        | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| SDRAM   | 3        | 42.86%  |
| Unknown | 2        | 28.57%  |
| DDR4    | 1        | 14.29%  |
| DDR3    | 1        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 7        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 2        | 28.57%  |
| 512   | 2        | 28.57%  |
| 16384 | 1        | 14.29%  |
| 8192  | 1        | 14.29%  |
| 1024  | 1        | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2        | 28.57%  |
| 3600    | 1        | 14.29%  |
| 1333    | 1        | 14.29%  |
| 1066    | 1        | 14.29%  |
| 400     | 1        | 14.29%  |
| 266     | 1        | 14.29%  |

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
| 0     | 5        | 71.43%  |
| 2     | 1        | 14.29%  |
| 1     | 1        | 14.29%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 2        | 66.67%  |
| Network       | 1        | 33.33%  |

