Q4OS - Tested Hardware & Statistics (Desktops)
----------------------------------------------

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

| Vendor        | Model         | Probe                                                      | Date         |
|---------------|---------------|------------------------------------------------------------|--------------|
| Compaq        | 07E4h         | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| Gigabyte      | XP-M5S661GX   | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| TECO Elect... | TR53A0        | [4ab721c7f7](https://linux-hardware.org/?probe=4ab721c7f7) | Aug 19, 2021 |
| MSI           | B550-A PRO    | [546cf15192](https://linux-hardware.org/?probe=546cf15192) | Jun 16, 2021 |
| MSI           | GF615M-P33 V2 | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| ASRock        | G41M-VS3      | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3      | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.10.0-9-686-pae  | 1        | 16.67%  |
| 5.10.0-10-686-pae | 1        | 16.67%  |
| 4.19.0-6-amd64    | 1        | 16.67%  |
| 4.19.0-17-686-pae | 1        | 16.67%  |
| 4.19.0-16-amd64   | 1        | 16.67%  |
| 4.19.0-16-686     | 1        | 16.67%  |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19.0  | 4        | 66.67%  |
| 5.10.0  | 2        | 33.33%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.19    | 4        | 66.67%  |
| 5.10    | 2        | 33.33%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| i686   | 4        | 66.67%  |
| x86_64 | 2        | 33.33%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| trinity | 5        | 83.33%  |
| KDE5    | 1        | 16.67%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 6        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| TDM  | 5        | 83.33%  |
| SDDM | 1        | 16.67%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 2        | 33.33%  |
| fr_FR | 1        | 16.67%  |
| es_AR | 1        | 16.67%  |
| en_ZA | 1        | 16.67%  |
| de_DE | 1        | 16.67%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 5        | 83.33%  |
| EFI  | 1        | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 6        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 5        | 83.33%  |
| GPT  | 1        | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 83.33%  |
| Yes       | 1        | 16.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3        | 50%     |
| No        | 3        | 50%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| MSI                         | 2        | 33.33%  |
| TECO Electric and Machinery | 1        | 16.67%  |
| Gigabyte Technology         | 1        | 16.67%  |
| Compaq                      | 1        | 16.67%  |
| ASRock                      | 1        | 16.67%  |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| TECO Electric and Machinery FUTRO S400 | 1        | 16.67%  |
| MSI MS-7C56                            | 1        | 16.67%  |
| MSI MS-7597                            | 1        | 16.67%  |
| Gigabyte XP-M5S661GX                   | 1        | 16.67%  |
| Compaq Evo D510 SFF                    | 1        | 16.67%  |
| ASRock G41M-VS3                        | 1        | 16.67%  |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| TECO Electric and Machinery FUTRO | 1        | 16.67%  |
| MSI MS-7C56                       | 1        | 16.67%  |
| MSI MS-7597                       | 1        | 16.67%  |
| Gigabyte XP-M5S661GX              | 1        | 16.67%  |
| Compaq Evo                        | 1        | 16.67%  |
| ASRock G41M-VS3                   | 1        | 16.67%  |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 1        | 16.67%  |
| 2011 | 1        | 16.67%  |
| 2010 | 1        | 16.67%  |
| 2008 | 1        | 16.67%  |
| 2005 | 1        | 16.67%  |
| 2002 | 1        | 16.67%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 6        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 6        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 6        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 2        | 33.33%  |
| 64.01-256.0 | 1        | 16.67%  |
| 1.01-2.0    | 1        | 16.67%  |
| 0.51-1.0    | 1        | 16.67%  |
| 0.01-0.5    | 1        | 16.67%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 4        | 66.67%  |
| 8.01-16.0 | 1        | 16.67%  |
| 0.01-0.5  | 1        | 16.67%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 3        | 50%     |
| 3      | 2        | 33.33%  |
| 2      | 1        | 16.67%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4        | 66.67%  |
| Yes       | 2        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 83.33%  |
| Yes       | 1        | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 83.33%  |
| Yes       | 1        | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1        | 16.67%  |
| South Africa | 1        | 16.67%  |
| Netherlands  | 1        | 16.67%  |
| Germany      | 1        | 16.67%  |
| France       | 1        | 16.67%  |
| Argentina    | 1        | 16.67%  |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Someren          | 1        | 16.67%  |
| Rostock          | 1        | 16.67%  |
| Posadas          | 1        | 16.67%  |
| Johannesburg     | 1        | 16.67%  |
| Grand Junction   | 1        | 16.67%  |
| Boulogne-sur-Mer | 1        | 16.67%  |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 30%     |
| Seagate             | 3        | 4      | 30%     |
| Unknown (CF)        | 1        | 1      | 10%     |
| SanDisk             | 1        | 1      | 10%     |
| Samsung Electronics | 1        | 1      | 10%     |
| MAXTOR              | 1        | 1      | 10%     |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| WDC WDS500G2B0B-00YS70 500GB SSD | 1        | 9.09%   |
| WDC WD400BD-23JMC0 40GB          | 1        | 9.09%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1        | 9.09%   |
| Unknown (CF) Card 8GB SSD        | 1        | 9.09%   |
| Seagate ST8000DM004-2CX188 8TB   | 1        | 9.09%   |
| Seagate ST3160815AS 160GB        | 1        | 9.09%   |
| Seagate ST3160812AS 160GB        | 1        | 9.09%   |
| Seagate ST310211A 10GB           | 1        | 9.09%   |
| SanDisk SDSSDA120G 120GB         | 1        | 9.09%   |
| Samsung HD081GJ 80GB             | 1        | 9.09%   |
| MAXTOR 6Y080L0 81GB              | 1        | 9.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 4      | 42.86%  |
| WDC                 | 2        | 2      | 28.57%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| MAXTOR              | 1        | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor       | Desktops | Drives | Percent |
|--------------|----------|--------|---------|
| WDC          | 1        | 1      | 33.33%  |
| Unknown (CF) | 1        | 1      | 33.33%  |
| SanDisk      | 1        | 1      | 33.33%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 8      | 71.43%  |
| SSD  | 2        | 3      | 28.57%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 6        | 11     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 6        | 10     | 85.71%  |
| 4.01-10.0  | 1        | 1      | 14.29%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 2        | 33.33%  |
| 51-100         | 2        | 33.33%  |
| More than 3000 | 1        | 16.67%  |
| 21-50          | 1        | 16.67%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 4        | 66.67%  |
| More than 3000 | 1        | 16.67%  |
| 21-50          | 1        | 16.67%  |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| WDC WD400BD-23JMC0 40GB | 1        | 1      | 50%     |
| MAXTOR 6Y080L0 81GB     | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 50%     |
| MAXTOR | 1        | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 50%     |
| MAXTOR | 1        | 1      | 50%     |

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
| Works   | 5        | 9      | 71.43%  |
| Malfunc | 2        | 2      | 28.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] | 2        | 33.33%  |
| Intel                            | 2        | 33.33%  |
| Nvidia                           | 1        | 16.67%  |
| AMD                              | 1        | 16.67%  |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 5513 IDE Controller                      | 2        | 20%     |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS] | 1        | 10%     |
| Nvidia MCP61 SATA Controller                                              | 1        | 10%     |
| Nvidia MCP61 IDE                                                          | 1        | 10%     |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                         | 1        | 10%     |
| Intel 82801G (ICH7 Family) IDE Controller                                 | 1        | 10%     |
| Intel 82801DB (ICH4) IDE Controller                                       | 1        | 10%     |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                  | 1        | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                       | 1        | 10%     |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 5        | 71.43%  |
| RAID | 1        | 14.29%  |
| SATA | 1        | 14.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 3        | 50%     |
| AMD    | 3        | 50%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 16.67%  |
| Intel Pentium 4 CPU 3.00GHz                 | 1        | 16.67%  |
| Intel Pentium 4 CPU 2.00GHz                 | 1        | 16.67%  |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 16.67%  |
| AMD Athlon Processor                        | 1        | 16.67%  |
| AMD Athlon II X2 250 Processor              | 1        | 16.67%  |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium 4         | 2        | 33.33%  |
| Intel Pentium Dual-Core | 1        | 16.67%  |
| AMD Ryzen 7             | 1        | 16.67%  |
| AMD Athlon II X2        | 1        | 16.67%  |
| AMD Athlon              | 1        | 16.67%  |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3        | 50%     |
| 2      | 2        | 33.33%  |
| 8      | 1        | 16.67%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4        | 66.67%  |
| 2      | 2        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4        | 66.67%  |
| 32-bit         | 2        | 33.33%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xf49      | 1        | 16.67%  |
| 0xf27      | 1        | 16.67%  |
| 0x1067a    | 1        | 16.67%  |
| 0x0800820d | 1        | 16.67%  |
| 0x010000c8 | 1        | 16.67%  |
| Unknown    | 1        | 16.67%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| NetBurst | 2        | 33.33%  |
| Zen+     | 1        | 16.67%  |
| Penryn   | 1        | 16.67%  |
| K6       | 1        | 16.67%  |
| K10      | 1        | 16.67%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] | 2        | 33.33%  |
| Nvidia                           | 2        | 33.33%  |
| Intel                            | 2        | 33.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2        | 33.33%  |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1        | 16.67%  |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1        | 16.67%  |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1        | 16.67%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 1        | 16.67%  |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x SiS    | 2        | 33.33%  |
| 1 x Nvidia | 2        | 33.33%  |
| 1 x Intel  | 2        | 33.33%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3        | 50%     |
| Unknown     | 2        | 33.33%  |
| Proprietary | 1        | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 66.67%  |
| 1.01-2.0   | 1        | 16.67%  |
| 0.01-0.5   | 1        | 16.67%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| ViewSonic           | 1        | 16.67%  |
| VIE                 | 1        | 16.67%  |
| Samsung Electronics | 1        | 16.67%  |
| Orion               | 1        | 16.67%  |
| Hewlett-Packard     | 1        | 16.67%  |
| Goldstar            | 1        | 16.67%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1        | 16.67%  |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1        | 16.67%  |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1        | 16.67%  |
| Orion ORION ORN120A 1920x540                                            | 1        | 16.67%  |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch               | 1        | 16.67%  |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1        | 16.67%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1600x900 (HD+)     | 2        | 33.33%  |
| 3840x2160 (4K)     | 1        | 16.67%  |
| 1920x540           | 1        | 16.67%  |
| 1920x1080 (FHD)    | 1        | 16.67%  |
| 1680x1050 (WSXGA+) | 1        | 16.67%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 31      | 1        | 16.67%  |
| 23      | 1        | 16.67%  |
| 22      | 1        | 16.67%  |
| 20      | 1        | 16.67%  |
| 19      | 1        | 16.67%  |
| Unknown | 1        | 16.67%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 3        | 50%     |
| 601-700     | 1        | 16.67%  |
| 501-600     | 1        | 16.67%  |
| Unknown     | 1        | 16.67%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 3        | 60%     |
| 32/9  | 1        | 20%     |
| 16/10 | 1        | 20%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2        | 33.33%  |
| 151-200        | 2        | 33.33%  |
| 351-500        | 1        | 16.67%  |
| Unknown        | 1        | 16.67%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4        | 66.67%  |
| 121-160 | 1        | 16.67%  |
| Unknown | 1        | 16.67%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5        | 83.33%  |
| 3     | 1        | 16.67%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 4        | 50%     |
| Silicon Integrated Systems [SiS] | 1        | 12.5%   |
| Qualcomm Atheros                 | 1        | 12.5%   |
| Intel                            | 1        | 12.5%   |
| IBM                              | 1        | 12.5%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 2        | 22.22%  |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet           | 1        | 11.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 1        | 11.11%  |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                          | 1        | 11.11%  |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                          | 1        | 11.11%  |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg] | 1        | 11.11%  |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                  | 1        | 11.11%  |
| IBM Winnipeg PCI-X Host Bridge                                      | 1        | 11.11%  |

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
| Realtek Semiconductor            | 4        | 57.14%  |
| Silicon Integrated Systems [SiS] | 1        | 14.29%  |
| Qualcomm Atheros                 | 1        | 14.29%  |
| Intel                            | 1        | 14.29%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2        | 28.57%  |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 14.29%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 14.29%  |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 14.29%  |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 14.29%  |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1        | 14.29%  |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 6        | 75%     |
| WiFi     | 1        | 12.5%   |
| Unknown  | 1        | 12.5%   |

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
| 1     | 4        | 66.67%  |
| 2     | 2        | 33.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 5        | 83.33%  |
| Yes  | 1        | 16.67%  |

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
| Nvidia                           | 2        | 33.33%  |
| Intel                            | 2        | 33.33%  |
| Silicon Integrated Systems [SiS] | 1        | 16.67%  |
| AMD                              | 1        | 16.67%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller   | 1        | 16.67%  |
| Nvidia MCP61 High Definition Audio                                | 1        | 16.67%  |
| Nvidia GM206 High Definition Audio Controller                     | 1        | 16.67%  |
| Intel NM10/ICH7 Family High Definition Audio Controller           | 1        | 16.67%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller | 1        | 16.67%  |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller               | 1        | 16.67%  |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Unknown   | 4        | 66.67%  |
| Transcend | 1        | 16.67%  |
| Team      | 1        | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 400MT/s              | 1        | 16.67%  |
| Unknown RAM Module 512MB DIMM                      | 1        | 16.67%  |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s      | 1        | 16.67%  |
| Unknown RAM Module 2048MB DIMM SDRAM               | 1        | 16.67%  |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s        | 1        | 16.67%  |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s | 1        | 16.67%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| SDRAM   | 3        | 50%     |
| Unknown | 2        | 33.33%  |
| DDR4    | 1        | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 6        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 2        | 33.33%  |
| 512   | 2        | 33.33%  |
| 16384 | 1        | 16.67%  |
| 1024  | 1        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2        | 33.33%  |
| 3600    | 1        | 16.67%  |
| 1066    | 1        | 16.67%  |
| 400     | 1        | 16.67%  |
| 266     | 1        | 16.67%  |

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
| 0     | 4        | 66.67%  |
| 2     | 1        | 16.67%  |
| 1     | 1        | 16.67%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 2        | 66.67%  |
| Network       | 1        | 33.33%  |

