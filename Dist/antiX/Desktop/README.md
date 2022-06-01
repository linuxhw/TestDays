antiX - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for antiX.

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

Total: 10

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Gigabyte | F2A85XM-D3H              | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| Gigabyte | 945GCMX-S2               | [54149177a7](https://linux-hardware.org/?probe=54149177a7) | Feb 12, 2022 |
| Unknown  | NF-CK804                 | [dc6287d017](https://linux-hardware.org/?probe=dc6287d017) | Jan 05, 2022 |
| ASUSTek  | A8R-MVP                  | [43a7b44e3f](https://linux-hardware.org/?probe=43a7b44e3f) | Mar 27, 2021 |
| ASUSTek  | M2N-MX SE Plus           | [a8985150bd](https://linux-hardware.org/?probe=a8985150bd) | Feb 08, 2021 |
| ASRock   | H81M-ITX                 | [7b2d6774c8](https://linux-hardware.org/?probe=7b2d6774c8) | Feb 05, 2021 |
| HP       | 3641h                    | [f918637d53](https://linux-hardware.org/?probe=f918637d53) | Jul 29, 2020 |
| Unknown  | Unknown                  | [7653370d96](https://linux-hardware.org/?probe=7653370d96) | Dec 16, 2019 |
| ASUSTek  | P5KPL/1600               | [8ba4b22f71](https://linux-hardware.org/?probe=8ba4b22f71) | Oct 22, 2019 |
| Lenovo   | ThinkCentre M91p 4480B9U | [e68917ee9f](https://linux-hardware.org/?probe=e68917ee9f) | Nov 04, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| antiX 19.2     | 2        | 25%     |
| antiX 17.4.1   | 2        | 25%     |
| antiX 21-runit | 1        | 12.5%   |
| antiX 21       | 1        | 12.5%   |
| antiX 17.1     | 1        | 12.5%   |
| antiX 15       | 1        | 12.5%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| antiX | 8        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 4.9.160-antix.2-486-smp     | 2        | 25%     |
| 5.10.88-antix.1-amd64-smp   | 1        | 12.5%   |
| 5.10.57-antix.1-amd64-smp   | 1        | 12.5%   |
| 4.9.87-antix.1-amd64-smp    | 1        | 12.5%   |
| 4.9.212-antix.1-amd64-smp   | 1        | 12.5%   |
| 4.9.212-antix.1-486-smp     | 1        | 12.5%   |
| 4.9.0-279-antix.1-amd64-smp | 1        | 12.5%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9.212 | 2        | 25%     |
| 4.9.160 | 2        | 25%     |
| 5.10.88 | 1        | 12.5%   |
| 5.10.57 | 1        | 12.5%   |
| 4.9.87  | 1        | 12.5%   |
| 4.9.0   | 1        | 12.5%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 6        | 75%     |
| 5.10    | 2        | 25%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 5        | 62.5%   |
| i686   | 3        | 37.5%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Unknown      | 5        | 62.5%   |
| XFCE         | 1        | 12.5%   |
| icewm        | 1        | 12.5%   |
| herbstluftwm | 1        | 12.5%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 7        | 87.5%   |
| Tty  | 1        | 12.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 5        | 62.5%   |
| Unknown | 2        | 25%     |
| LightDM | 1        | 12.5%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 3        | 37.5%   |
| Unknown | 3        | 37.5%   |
| sk_SK   | 1        | 12.5%   |
| pl_PL   | 1        | 12.5%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 8        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 7        | 87.5%   |
| Overlay | 1        | 12.5%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 7        | 87.5%   |
| Unknown | 1        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 62.5%   |
| Yes       | 3        | 37.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 75%     |
| Yes       | 2        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 2        | 25%     |
| ASUSTek Computer    | 2        | 25%     |
| Unknown             | 2        | 25%     |
| Lenovo              | 1        | 12.5%   |
| Hewlett-Packard     | 1        | 12.5%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 2        | 25%     |
| Lenovo ThinkCentre M91p 4480B9U | 1        | 12.5%   |
| HP t5740                        | 1        | 12.5%   |
| Gigabyte F2A85XM-D3H            | 1        | 12.5%   |
| Gigabyte 945GCMX-S2             | 1        | 12.5%   |
| ASUS P5KPL/1600                 | 1        | 12.5%   |
| ASUS A8R-MVP                    | 1        | 12.5%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 2        | 25%     |
| Lenovo ThinkCentre   | 1        | 12.5%   |
| HP t5740             | 1        | 12.5%   |
| Gigabyte F2A85XM-D3H | 1        | 12.5%   |
| Gigabyte 945GCMX-S2  | 1        | 12.5%   |
| ASUS P5KPL           | 1        | 12.5%   |
| ASUS A8R-MVP         | 1        | 12.5%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2008    | 2        | 25%     |
| 2012    | 1        | 12.5%   |
| 2011    | 1        | 12.5%   |
| 2009    | 1        | 12.5%   |
| 2007    | 1        | 12.5%   |
| 2005    | 1        | 12.5%   |
| Unknown | 1        | 12.5%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 8        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 8        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 8        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 2        | 25%     |
| 4.01-8.0   | 1        | 12.5%   |
| 3.01-4.0   | 1        | 12.5%   |
| 16.01-24.0 | 1        | 12.5%   |
| 1.01-2.0   | 1        | 12.5%   |
| 0.51-1.0   | 1        | 12.5%   |
| 0.01-0.5   | 1        | 12.5%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 4        | 50%     |
| 1.01-2.0 | 2        | 25%     |
| 4.01-8.0 | 1        | 12.5%   |
| 0.51-1.0 | 1        | 12.5%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 5        | 62.5%   |
| 3      | 2        | 25%     |
| 2      | 1        | 12.5%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 5        | 62.5%   |
| No        | 3        | 37.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 8        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 87.5%   |
| Yes       | 1        | 12.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 100%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| USA      | 2        | 25%     |
| Slovakia | 1        | 12.5%   |
| Russia   | 1        | 12.5%   |
| Poland   | 1        | 12.5%   |
| Greece   | 1        | 12.5%   |
| Germany  | 1        | 12.5%   |
| France   | 1        | 12.5%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zagnansk          | 1        | 12.5%   |
| Violes            | 1        | 12.5%   |
| Mason             | 1        | 12.5%   |
| Kazan’          | 1        | 12.5%   |
| Heraklion         | 1        | 12.5%   |
| Frankfurt am Main | 1        | 12.5%   |
| Bratislava        | 1        | 12.5%   |
| Boulder           | 1        | 12.5%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 27.27%  |
| Samsung Electronics | 3        | 4      | 27.27%  |
| WDC                 | 2        | 2      | 18.18%  |
| Unknown             | 1        | 1      | 9.09%   |
| SanDisk             | 1        | 1      | 9.09%   |
| Hitachi             | 1        | 2      | 9.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| WDC WD205BA 21GB                | 1        | 8.33%   |
| WDC WD1600AAJS-00PSA0 160GB     | 1        | 8.33%   |
| Unknown 2GB ATA Flash Disk      | 1        | 8.33%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 8.33%   |
| Seagate ST3320620AS 320GB       | 1        | 8.33%   |
| Seagate ST3320413CS 320GB       | 1        | 8.33%   |
| SanDisk sandisk120 120GB SSD    | 1        | 8.33%   |
| Samsung SSD 850 EVO 120GB       | 1        | 8.33%   |
| Samsung HD250HJ 250GB           | 1        | 8.33%   |
| Samsung HD160JJ 160GB           | 1        | 8.33%   |
| Samsung HD080HJ 80GB            | 1        | 8.33%   |
| Hitachi HTS723232A7A364 320GB   | 1        | 8.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 33.33%  |
| WDC                 | 2        | 2      | 22.22%  |
| Samsung Electronics | 2        | 3      | 22.22%  |
| Unknown             | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 2      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 11     | 77.78%  |
| SSD  | 2        | 2      | 22.22%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 8        | 13     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 8        | 13     | 100%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 4        | 50%     |
| 21-50      | 2        | 25%     |
| 1-20       | 1        | 12.5%   |
| 51-100     | 1        | 12.5%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 6        | 75%     |
| 21-50   | 1        | 12.5%   |
| 101-250 | 1        | 12.5%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD205BA 21GB                | 1        | 1      | 20%     |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 20%     |
| Seagate ST3320620AS 320GB       | 1        | 1      | 20%     |
| Seagate ST3320413CS 320GB       | 1        | 1      | 20%     |
| SanDisk sandisk120 120GB SSD    | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 60%     |
| WDC     | 1        | 1      | 20%     |
| SanDisk | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 75%     |
| WDC     | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 4      | 80%     |
| SSD  | 1        | 1      | 20%     |

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
| Malfunc  | 5        | 5      | 55.56%  |
| Works    | 3        | 6      | 33.33%  |
| Detected | 1        | 2      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 5        | 55.56%  |
| ULi Electronics    | 1        | 11.11%  |
| Nvidia             | 1        | 11.11%  |
| ASMedia Technology | 1        | 11.11%  |
| AMD                | 1        | 11.11%  |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 15.38%  |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2        | 15.38%  |
| ULi ULi M5288 SATA                                                            | 1        | 7.69%   |
| ULi M5229 IDE                                                                 | 1        | 7.69%   |
| Nvidia CK804 Serial ATA Controller                                            | 1        | 7.69%   |
| Nvidia CK804 IDE                                                              | 1        | 7.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]          | 1        | 7.69%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 1        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1        | 7.69%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1        | 7.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 6        | 60%     |
| SATA | 4        | 40%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 5        | 62.5%   |
| AMD    | 3        | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Xeon CPU L5410 @ 2.33GHz             | 1        | 12.5%   |
| Intel Pentium II (Deschutes)               | 1        | 12.5%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz     | 1        | 12.5%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 1        | 12.5%   |
| Intel Atom CPU N280 @ 1.66GHz              | 1        | 12.5%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+ | 1        | 12.5%   |
| AMD Athlon 64 Processor 3200+              | 1        | 12.5%   |
| AMD A6-5400K APU with Radeon HD Graphics   | 1        | 12.5%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Xeon         | 1        | 12.5%   |
| Intel Pentium Dual | 1        | 12.5%   |
| Intel Pentium      | 1        | 12.5%   |
| Intel Core i5      | 1        | 12.5%   |
| Intel Atom         | 1        | 12.5%   |
| AMD Athlon 64 X2   | 1        | 12.5%   |
| AMD Athlon 64      | 1        | 12.5%   |
| AMD A6             | 1        | 12.5%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4        | 50%     |
| 4      | 2        | 25%     |
| 2      | 2        | 25%     |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 75%     |
| 2      | 2        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 6        | 75%     |
| 32-bit         | 2        | 25%     |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2        | 25%     |
| 0x6fd      | 1        | 12.5%   |
| 0x652      | 1        | 12.5%   |
| 0x206a7    | 1        | 12.5%   |
| 0x106c2    | 1        | 12.5%   |
| 0x10676    | 1        | 12.5%   |
| 0x06001116 | 1        | 12.5%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| K8 Hammer   | 2        | 25%     |
| SandyBridge | 1        | 12.5%   |
| Piledriver  | 1        | 12.5%   |
| Penryn      | 1        | 12.5%   |
| Core        | 1        | 12.5%   |
| Bonnell     | 1        | 12.5%   |
| Unknown     | 1        | 12.5%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 3        | 37.5%   |
| AMD    | 3        | 37.5%   |
| Nvidia | 2        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GF108 [GeForce GT 630]                                             | 1        | 10%     |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                       | 1        | 10%     |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1        | 10%     |
| Intel 82945G/GZ Integrated Graphics Controller                            | 1        | 10%     |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 10%     |
| AMD RV516 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 10%     |
| AMD RV516 [Radeon X1300/X1550 Series]                                     | 1        | 10%     |
| AMD RV515 [Radeon X1300/X1550]                                            | 1        | 10%     |
| AMD RV515 [Radeon X1300/X1550 Series] (Secondary)                         | 1        | 10%     |
| AMD Rage 3 [3D Rage PRO AGP 2X]                                           | 1        | 10%     |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 3        | 37.5%   |
| 2 x AMD    | 2        | 25%     |
| 1 x Nvidia | 2        | 25%     |
| 1 x AMD    | 1        | 12.5%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 5        | 62.5%   |
| Unknown     | 2        | 25%     |
| Proprietary | 1        | 12.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 3        | 37.5%   |
| Unknown    | 3        | 37.5%   |
| 1.01-2.0   | 2        | 25%     |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Acer                | 3        | 60%     |
| Vizio               | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio E28h-C1 VIZ1002 1360x768 610x350mm 27.7-inch                   | 1        | 20%     |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch | 1        | 20%     |
| Acer VG220Q ACR06D8 1920x1080 476x268mm 21.5-inch                    | 1        | 20%     |
| Acer V243H ACR00A3 1920x1080 531x298mm 24.0-inch                     | 1        | 20%     |
| Acer S271HL ACR02CA 1920x1080 598x336mm 27.0-inch                    | 1        | 20%     |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 3        | 60%     |
| 1600x1200       | 1        | 20%     |
| 1366x768 (WXGA) | 1        | 20%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 2        | 40%     |
| 38     | 1        | 20%     |
| 27     | 1        | 20%     |
| 24     | 1        | 20%     |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 2        | 40%     |
| 401-500     | 2        | 40%     |
| 801-900     | 1        | 20%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 4        | 80%     |
| 4/3   | 1        | 20%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 60%     |
| 301-350        | 1        | 20%     |
| 501-1000       | 1        | 20%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 3        | 60%     |
| 1-50    | 1        | 20%     |
| 101-120 | 1        | 20%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5        | 62.5%   |
| 0     | 3        | 37.5%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 5        | 45.45%  |
| Qualcomm Atheros Communications | 1        | 9.09%   |
| Nvidia                          | 1        | 9.09%   |
| Marvell Technology Group        | 1        | 9.09%   |
| LSI                             | 1        | 9.09%   |
| Intel                           | 1        | 9.09%   |
| Broadcom                        | 1        | 9.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 2        | 18.18%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 9.09%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1        | 9.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 9.09%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 9.09%   |
| Nvidia CK804 Ethernet Controller                                              | 1        | 9.09%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 9.09%   |
| LSI 56k WinModem                                                              | 1        | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 9.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1        | 9.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Qualcomm Atheros Communications | 1        | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1        | 100%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 5        | 55.56%  |
| Nvidia                   | 1        | 11.11%  |
| Marvell Technology Group | 1        | 11.11%  |
| Intel                    | 1        | 11.11%  |
| Broadcom                 | 1        | 11.11%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 22.22%  |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 11.11%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1        | 11.11%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 11.11%  |
| Nvidia CK804 Ethernet Controller                                  | 1        | 11.11%  |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 11.11%  |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 11.11%  |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 8        | 80%     |
| Modem    | 1        | 10%     |
| WiFi     | 1        | 10%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 7        | 87.5%   |
| WiFi     | 1        | 12.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 7        | 87.5%   |
| 2     | 1        | 12.5%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 8        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

Zero info for selected period =(

Bluetooth Model
---------------

Controller models

Zero info for selected period =(

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Intel           | 3        | 30%     |
| Nvidia          | 2        | 20%     |
| Creative Labs   | 2        | 20%     |
| ULi Electronics | 1        | 10%     |
| Ensoniq         | 1        | 10%     |
| AMD             | 1        | 10%     |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| ULi Electronics HD Audio Controller                                        | 1        | 10%     |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 10%     |
| Nvidia CK804 AC'97 Audio Controller                                        | 1        | 10%     |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 10%     |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 10%     |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 10%     |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 1        | 10%     |
| Creative Labs EMU20k1 [Sound Blaster X-Fi Series]                          | 1        | 10%     |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 10%     |
| AMD FCH Azalia Controller                                                  | 1        | 10%     |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 4        | 50%     |
| Kingston            | 2        | 25%     |
| Samsung Electronics | 1        | 12.5%   |
| Patriot             | 1        | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM DDR 400MT/s             | 1        | 12.5%   |
| Unknown RAM Module 512MB DIMM                         | 1        | 12.5%   |
| Unknown RAM Module 1GB DIMM 667MT/s                   | 1        | 12.5%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s           | 1        | 12.5%   |
| Samsung RAM M378B5673FH0 2GB DIMM DDR3 667MT/s        | 1        | 12.5%   |
| Patriot RAM PSD34G1600L2S 4GB SODIMM DDR3 1600MT/s    | 1        | 12.5%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s | 1        | 12.5%   |
| Kingston RAM 99U5402-060.A 2GB DIMM DDR3 1333MT/s     | 1        | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 3        | 42.86%  |
| Unknown | 2        | 28.57%  |
| DDR2    | 1        | 14.29%  |
| DDR     | 1        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 6        | 85.71%  |
| SODIMM | 1        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 4096 | 2        | 28.57%  |
| 1024 | 2        | 28.57%  |
| 512  | 2        | 28.57%  |
| 2048 | 1        | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 667     | 3        | 37.5%   |
| 1600    | 2        | 25%     |
| 1333    | 1        | 12.5%   |
| 400     | 1        | 12.5%   |
| Unknown | 1        | 12.5%   |

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
| 0     | 6        | 75%     |
| 2     | 2        | 25%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 2        | 50%     |
| Modem                    | 1        | 25%     |
| Communication controller | 1        | 25%     |

