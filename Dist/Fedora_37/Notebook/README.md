Fedora 37 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 37.

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

Total: 10

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI        | HVY-WXX9                    | [d574f5da9b](https://linux-hardware.org/?probe=d574f5da9b) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7326474aae](https://linux-hardware.org/?probe=7326474aae) | Sep 13, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| HP            | EliteBook 820 G1            | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| Samsung       | 270E5G/270E5U               | [d1f2245fb4](https://linux-hardware.org/?probe=d1f2245fb4) | Jul 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HP            | Laptop 14-dq2xxx            | [2477951c04](https://linux-hardware.org/?probe=2477951c04) | Apr 15, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                             | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| 5.19.7-300.fc37.x86_64                              | 3         | 30%     |
| 5.18.0-0.rc2.23.fc37.x86_64                         | 2         | 20%     |
| 5.19.8-300.fc37.x86_64                              | 1         | 10%     |
| 5.19.4-300.fc37.x86_64                              | 1         | 10%     |
| 5.19.0-xm2.0.fc37.x86_64                            | 1         | 10%     |
| 5.19.0-65.fc37.x86_64                               | 1         | 10%     |
| 5.19.0-0.rc6.20220714git4a57a8400075.49.fc37.x86_64 | 1         | 10%     |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.7  | 3         | 30%     |
| 5.19.0  | 3         | 30%     |
| 5.18.0  | 2         | 20%     |
| 5.19.8  | 1         | 10%     |
| 5.19.4  | 1         | 10%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 8         | 80%     |
| 5.18    | 2         | 20%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 10        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| GNOME | 9         | 90%     |
| XFCE  | 1         | 10%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 9         | 90%     |
| X11     | 1         | 10%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 6         | 60%     |
| GDM     | 3         | 30%     |
| LightDM | 1         | 10%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 5         | 50%     |
| ro_RO | 1         | 10%     |
| pt_BR | 1         | 10%     |
| es_ES | 1         | 10%     |
| es_AR | 1         | 10%     |
| en_GB | 1         | 10%     |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 6         | 60%     |
| BIOS | 4         | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 8         | 80%     |
| Ext4  | 2         | 20%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 6         | 60%     |
| GPT     | 3         | 30%     |
| MBR     | 1         | 10%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 9         | 90%     |
| Yes       | 1         | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 8         | 80%     |
| Yes       | 2         | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 2         | 20%     |
| HUAWEI              | 2         | 20%     |
| Hewlett-Packard     | 2         | 20%     |
| TUXEDO              | 1         | 10%     |
| Samsung Electronics | 1         | 10%     |
| AXDIA International | 1         | 10%     |
| ASUSTek Computer    | 1         | 10%     |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HUAWEI HVY-WXX9                          | 2         | 20%     |
| TUXEDO InfinityBook S 15/17 Gen7         | 1         | 10%     |
| Samsung 270E5G/270E5U                    | 1         | 10%     |
| Lenovo ThinkPad W510 4391F66             | 1         | 10%     |
| Lenovo Legion 5 Pro 16ITH6H 82JD         | 1         | 10%     |
| HP Laptop 14-dq2xxx                      | 1         | 10%     |
| HP EliteBook 820 G1                      | 1         | 10%     |
| AXDIA International WINPAD V10           | 1         | 10%     |
| ASUS ASUS TUF Gaming F15 FX506LI_FX506LI | 1         | 10%     |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| HUAWEI HVY-WXX9            | 2         | 20%     |
| TUXEDO InfinityBook        | 1         | 10%     |
| Samsung 270E5G             | 1         | 10%     |
| Lenovo ThinkPad            | 1         | 10%     |
| Lenovo Legion              | 1         | 10%     |
| HP Laptop                  | 1         | 10%     |
| HP EliteBook               | 1         | 10%     |
| AXDIA International WINPAD | 1         | 10%     |
| ASUS ASUS                  | 1         | 10%     |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 2         | 20%     |
| 2021 | 2         | 20%     |
| 2020 | 2         | 20%     |
| 2013 | 2         | 20%     |
| 2014 | 1         | 10%     |
| 2010 | 1         | 10%     |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 10        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 10        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 10        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 5         | 50%     |
| 8.01-16.0  | 3         | 30%     |
| 4.01-8.0   | 1         | 10%     |
| 1.01-2.0   | 1         | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 3         | 30%     |
| 8.01-16.0 | 3         | 30%     |
| 4.01-8.0  | 2         | 20%     |
| 3.01-4.0  | 1         | 10%     |
| 1.01-2.0  | 1         | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 9         | 90%     |
| 2      | 1         | 10%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 8         | 80%     |
| Yes       | 2         | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6         | 60%     |
| No        | 4         | 40%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9         | 90%     |
| No        | 1         | 10%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8         | 80%     |
| No        | 2         | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| USA       | 2         | 20%     |
| Spain     | 1         | 10%     |
| Poland    | 1         | 10%     |
| Norway    | 1         | 10%     |
| Moldova   | 1         | 10%     |
| Mexico    | 1         | 10%     |
| Brazil    | 1         | 10%     |
| Austria   | 1         | 10%     |
| Argentina | 1         | 10%     |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Warsaw             | 1         | 10%     |
| Valencia           | 1         | 10%     |
| Sao Paulo          | 1         | 10%     |
| San Andres Cholula | 1         | 10%     |
| Rosario            | 1         | 10%     |
| Queens             | 1         | 10%     |
| Oslo               | 1         | 10%     |
| New York           | 1         | 10%     |
| Matzendorf         | 1         | 10%     |
| Bălţi            | 1         | 10%     |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 4         | 4      | 40%     |
| Kingston                    | 2         | 2      | 20%     |
| YMTC                        | 1         | 1      | 10%     |
| Yangtze Memory Technologies | 1         | 1      | 10%     |
| Unknown                     | 1         | 2      | 10%     |
| Micron Technology           | 1         | 1      | 10%     |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB               | 2         | 18.18%  |
| YMTC PC005 512GB                         | 1         | 9.09%   |
| Yangtze Memory NVMe SSD Drive 512GB      | 1         | 9.09%   |
| Unknown SL64G  64GB                      | 1         | 9.09%   |
| Unknown 032GE4  32GB                     | 1         | 9.09%   |
| Samsung SSD 840 Series 250GB             | 1         | 9.09%   |
| Samsung NVMe SSD Drive 1024GB            | 1         | 9.09%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 9.09%   |
| Kingston SUV400S37240G 240GB SSD         | 1         | 9.09%   |
| Kingston OM8PCP3512F-AB 512GB            | 1         | 9.09%   |

HDD Vendor
----------

Hard disk drive vendors

Zero info for selected period =(

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 33.33%  |
| Micron Technology   | 1         | 1      | 33.33%  |
| Kingston            | 1         | 1      | 33.33%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 6         | 6      | 60%     |
| SSD  | 3         | 3      | 30%     |
| MMC  | 1         | 2      | 10%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 6         | 6      | 60%     |
| SATA | 3         | 3      | 30%     |
| MMC  | 1         | 2      | 10%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3         | 3      | 100%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 3         | 30%     |
| 501-1000   | 3         | 30%     |
| 101-250    | 2         | 20%     |
| 21-50      | 1         | 10%     |
| 1001-2000  | 1         | 10%     |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 101-250  | 3         | 30%     |
| 1-20     | 3         | 30%     |
| 501-1000 | 2         | 20%     |
| 51-100   | 2         | 20%     |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Micron Technology | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 100%    |

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
| Detected | 7         | 8      | 70%     |
| Works    | 2         | 2      | 20%     |
| Malfunc  | 1         | 1      | 10%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 7         | 53.85%  |
| Samsung Electronics         | 3         | 23.08%  |
| Yangtze Memory Technologies | 2         | 15.38%  |
| Kingston Technology Company | 1         | 7.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Yangtze Memory Non-Volatile memory controller                    | 2         | 15.38%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                   | 2         | 15.38%  |
| Intel Volume Management Device NVMe RAID Controller              | 2         | 15.38%  |
| Samsung NVMe SSD Controller 980                                  | 1         | 7.69%   |
| Kingston Company Company Non-Volatile memory controller          | 1         | 7.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                     | 1         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode] | 1         | 7.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller             | 1         | 7.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller   | 1         | 7.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller             | 1         | 7.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 6         | 46.15%  |
| SATA | 5         | 38.46%  |
| RAID | 2         | 15.38%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 8         | 80%     |
| AMD    | 2         | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 20%     |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 1         | 10%     |
| Intel Core i5-4310U CPU @ 2.00GHz       | 1         | 10%     |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 10%     |
| Intel Core i5-10300H CPU @ 2.50GHz      | 1         | 10%     |
| Intel Atom CPU Z3735F @ 1.33GHz         | 1         | 10%     |
| Intel 12th Gen Core i5-1240P            | 1         | 10%     |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 10%     |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz | 1         | 10%     |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Other         | 3         | 30%     |
| Intel Core i5 | 3         | 30%     |
| AMD Ryzen 5   | 2         | 20%     |
| Intel Core i7 | 1         | 10%     |
| Intel Atom    | 1         | 10%     |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 4         | 40%     |
| 6      | 2         | 20%     |
| 2      | 2         | 20%     |
| 12     | 1         | 10%     |
| 8      | 1         | 10%     |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 10        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 9         | 90%     |
| 1      | 1         | 10%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x08600106 | 2         | 20%     |
| Unknown    | 2         | 20%     |
| 0xa0652    | 1         | 10%     |
| 0x906a3    | 1         | 10%     |
| 0x806d1    | 1         | 10%     |
| 0x40651    | 1         | 10%     |
| 0x306a9    | 1         | 10%     |
| 0x30678    | 1         | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Zen 2            | 2         | 20%     |
| TigerLake        | 1         | 10%     |
| Silvermont       | 1         | 10%     |
| Nehalem          | 1         | 10%     |
| IvyBridge        | 1         | 10%     |
| Icelake          | 1         | 10%     |
| Haswell          | 1         | 10%     |
| CometLake        | 1         | 10%     |
| Alderlake Hybrid | 1         | 10%     |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 7         | 53.85%  |
| Nvidia | 4         | 30.77%  |
| AMD    | 2         | 15.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                           | 2         | 15.38%  |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                           | 1         | 7.69%   |
| Nvidia GT216GLM [Quadro FX 880M]                                     | 1         | 7.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M] | 1         | 7.69%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                      | 1         | 7.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                 | 1         | 7.69%   |
| Intel Tiger Lake UHD Graphics                                        | 1         | 7.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                     | 1         | 7.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                 | 1         | 7.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display         | 1         | 7.69%   |
| Intel Alder Lake-P Integrated Graphics Controller                    | 1         | 7.69%   |
| Intel 3rd Gen Core processor Graphics Controller                     | 1         | 7.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 4         | 40%     |
| Intel + Nvidia | 3         | 30%     |
| 1 x AMD        | 2         | 20%     |
| 1 x Nvidia     | 1         | 10%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 9         | 90%     |
| Proprietary | 1         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 60%     |
| 0.01-0.5   | 2         | 20%     |
| 3.01-4.0   | 1         | 10%     |
| 1.01-2.0   | 1         | 10%     |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 4         | 40%     |
| PANDA                   | 1         | 10%     |
| Lenovo                  | 1         | 10%     |
| Hewlett-Packard         | 1         | 10%     |
| CSO                     | 1         | 10%     |
| Chimei Innolux          | 1         | 10%     |
| Chi Mei Optoelectronics | 1         | 10%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 2         | 18.18%  |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                  | 1         | 9.09%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 1         | 9.09%   |
| Hewlett-Packard E271i HWP3106 1920x1080 600x340mm 27.2-inch              | 1         | 9.09%   |
| CSO LCD Monitor CSO1606 2560x1600 345x215mm 16.0-inch                    | 1         | 9.09%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 1         | 9.09%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch         | 1         | 9.09%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch | 1         | 9.09%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                    | 1         | 9.09%   |
| BOE LCD Monitor BOE05F5 1366x768 277x156mm 12.5-inch                     | 1         | 9.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 6         | 60%     |
| 1366x768 (WXGA) | 2         | 20%     |
| 2560x1600       | 1         | 10%     |
| 1600x900 (HD+)  | 1         | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 5         | 45.45%  |
| 16     | 3         | 27.27%  |
| 27     | 1         | 9.09%   |
| 13     | 1         | 9.09%   |
| 12     | 1         | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 6         | 60%     |
| 351-400     | 2         | 20%     |
| 501-600     | 1         | 10%     |
| 201-300     | 1         | 10%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 8         | 88.89%  |
| 16/10 | 1         | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 63.64%  |
| 81-90          | 1         | 9.09%   |
| 61-70          | 1         | 9.09%   |
| 301-350        | 1         | 9.09%   |
| 111-120        | 1         | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 6         | 60%     |
| 51-100  | 2         | 20%     |
| 161-240 | 1         | 10%     |
| 101-120 | 1         | 10%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 7         | 70%     |
| 2     | 2         | 20%     |
| 0     | 1         | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 7         | 50%     |
| Realtek Semiconductor | 5         | 35.71%  |
| Qualcomm Atheros      | 1         | 7.14%   |
| Hewlett-Packard       | 1         | 7.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 17.65%  |
| Intel Wi-Fi 6 AX200                                               | 3         | 17.65%  |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 5.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 5.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 5.88%   |
| Intel Wireless 7260                                               | 1         | 5.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 5.88%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.88%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 5.88%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 5.88%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 5.88%   |
| HP lt4112 Gobi 4G Module Network Device                           | 1         | 5.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 7         | 63.64%  |
| Realtek Semiconductor | 2         | 18.18%  |
| Qualcomm Atheros      | 1         | 9.09%   |
| Hewlett-Packard       | 1         | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 3         | 27.27%  |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 1         | 9.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 9.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 9.09%   |
| Intel Wireless 7260                                        | 1         | 9.09%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 9.09%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 9.09%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 9.09%   |
| HP lt4112 Gobi 4G Module Network Device                    | 1         | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 4         | 66.67%  |
| Intel                 | 2         | 33.33%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 16.67%  |
| Intel Ethernet Connection I218-LM                                 | 1         | 16.67%  |
| Intel 82577LM Gigabit Network Connection                          | 1         | 16.67%  |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9         | 60%     |
| Ethernet | 6         | 40%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7         | 70%     |
| Ethernet | 3         | 30%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6         | 60%     |
| 1     | 3         | 30%     |
| 0     | 1         | 10%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 8         | 80%     |
| Yes  | 2         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 6         | 75%     |
| Realtek Semiconductor           | 1         | 12.5%   |
| Qualcomm Atheros Communications | 1         | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                 | 3         | 37.5%   |
| Intel AX201 Bluetooth                 | 2         | 25%     |
| Realtek Bluetooth Radio               | 1         | 12.5%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0 | 1         | 12.5%   |
| Intel Bluetooth wireless interface    | 1         | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 7         | 58.33%  |
| Nvidia | 3         | 25%     |
| AMD    | 2         | 16.67%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 15.38%  |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1         | 7.69%   |
| Nvidia GT216 HDMI Audio Controller                                  | 1         | 7.69%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 7.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 7.69%   |
| Intel Tiger Lake-H HD Audio Controller                              | 1         | 7.69%   |
| Intel Haswell-ULT HD Audio Controller                               | 1         | 7.69%   |
| Intel Comet Lake PCH cAVS                                           | 1         | 7.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller             | 1         | 7.69%   |
| Intel 8 Series HD Audio Controller                                  | 1         | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 7.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 1         | 7.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 33.33%  |
| Unknown             | 1         | 16.67%  |
| Micron Technology   | 1         | 16.67%  |
| Kingston            | 1         | 16.67%  |
| A-DATA Technology   | 1         | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                | 1         | 16.67%  |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s   | 1         | 16.67%  |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 16.67%  |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s | 1         | 16.67%  |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s    | 1         | 16.67%  |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s       | 1         | 16.67%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR4 | 2         | 50%     |
| DDR3 | 2         | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3         | 75%     |
| Row Of Chips | 1         | 25%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 3         | 75%     |
| 2048 | 1         | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 2         | 33.33%  |
| 2667  | 2         | 33.33%  |
| 1600  | 1         | 16.67%  |
| 1333  | 1         | 16.67%  |

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
| Chicony Electronics                    | 2         | 25%     |
| Silicon Motion                         | 1         | 12.5%   |
| Quanta                                 | 1         | 12.5%   |
| Lenovo                                 | 1         | 12.5%   |
| IMC Networks                           | 1         | 12.5%   |
| Goodong Industry                       | 1         | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Silicon Motion WebCam SC-10HDD12636N             | 1         | 12.5%   |
| Quanta HP TrueVision HD Camera                   | 1         | 12.5%   |
| Lenovo Integrated Webcam [R5U877]                | 1         | 12.5%   |
| IMC Networks HD Camera                           | 1         | 12.5%   |
| Goodong Industry USB2.0 HD UVC WebCam            | 1         | 12.5%   |
| Chicony USB2.0 Camera                            | 1         | 12.5%   |
| Chicony HP HD Webcam                             | 1         | 12.5%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 12.5%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 50%     |
| Validity Sensors           | 1         | 25%     |
| Elan Microelectronics      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device        | 2         | 50%     |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 25%     |
| Elan ELAN:ARM-M4                           | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Lenovo | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5         | 50%     |
| 0     | 4         | 40%     |
| 2     | 1         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 4         | 57.14%  |
| Graphics card      | 2         | 28.57%  |
| Net/wireless       | 1         | 14.29%  |

