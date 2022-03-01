Slackware 15.0 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Slackware 15.0.

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

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo   | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dynabook | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| HP       | Laptop 15-bs1xx             | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76 | Oryx Pro                    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI      | Modern 14 B11MO             | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI      | Modern 14 B11MO             | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell     | Inspiron 15-3552            | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP       | 245 G7 Notebook PC          | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP       | 245 G7 Notebook PC          | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP       | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell     | Vostro 3500                 | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.19 | 1         | 10%     |
| 5.15.1  | 1         | 10%     |
| 5.14.9  | 1         | 10%     |
| 5.14.8  | 1         | 10%     |
| 5.14.10 | 1         | 10%     |
| 5.14.0  | 1         | 10%     |
| 5.13.8  | 1         | 10%     |
| 5.13.5  | 1         | 10%     |
| 5.13.11 | 1         | 10%     |
| 5.10.91 | 1         | 10%     |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.19 | 1         | 10%     |
| 5.15.1  | 1         | 10%     |
| 5.14.9  | 1         | 10%     |
| 5.14.8  | 1         | 10%     |
| 5.14.10 | 1         | 10%     |
| 5.14.0  | 1         | 10%     |
| 5.13.8  | 1         | 10%     |
| 5.13.5  | 1         | 10%     |
| 5.13.11 | 1         | 10%     |
| 5.10.91 | 1         | 10%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 3         | 33.33%  |
| 5.13    | 3         | 33.33%  |
| 5.15    | 2         | 22.22%  |
| 5.10    | 1         | 11.11%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 9         | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 4         | 44.44%  |
| XFCE    | 3         | 33.33%  |
| KDE     | 1         | 11.11%  |
| Unknown | 1         | 11.11%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 6         | 60%     |
| Tty  | 4         | 40%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 4         | 44.44%  |
| Unknown | 4         | 44.44%  |
| XDM     | 1         | 11.11%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 8         | 88.89%  |
| pt_BR | 1         | 11.11%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 6         | 66.67%  |
| BIOS | 3         | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 9         | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 5         | 55.56%  |
| MBR     | 2         | 22.22%  |
| Unknown | 2         | 22.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 8         | 80%     |
| Yes       | 2         | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6         | 66.67%  |
| Yes       | 3         | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 33.33%  |
| Dell            | 2         | 22.22%  |
| System76        | 1         | 11.11%  |
| MSI             | 1         | 11.11%  |
| Lenovo          | 1         | 11.11%  |
| Dynabook        | 1         | 11.11%  |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| System76 Oryx Pro                  | 1         | 11.11%  |
| MSI Modern 14 B11MO                | 1         | 11.11%  |
| Lenovo ThinkPad Edge E530c 336669G | 1         | 11.11%  |
| HP Laptop 15-bs1xx                 | 1         | 11.11%  |
| HP EliteBook 840 G5                | 1         | 11.11%  |
| HP 245 G7 Notebook PC              | 1         | 11.11%  |
| Dynabook P1-C7MP-BL                | 1         | 11.11%  |
| Dell Vostro 3500                   | 1         | 11.11%  |
| Dell Inspiron 15-3552              | 1         | 11.11%  |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| System76 Oryx       | 1         | 11.11%  |
| MSI Modern          | 1         | 11.11%  |
| Lenovo ThinkPad     | 1         | 11.11%  |
| HP Laptop           | 1         | 11.11%  |
| HP EliteBook        | 1         | 11.11%  |
| HP 245              | 1         | 11.11%  |
| Dynabook P1-C7MP-BL | 1         | 11.11%  |
| Dell Vostro         | 1         | 11.11%  |
| Dell Inspiron       | 1         | 11.11%  |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 2         | 22.22%  |
| 2020 | 1         | 11.11%  |
| 2019 | 1         | 11.11%  |
| 2018 | 1         | 11.11%  |
| 2017 | 1         | 11.11%  |
| 2015 | 1         | 11.11%  |
| 2012 | 1         | 11.11%  |
| 2010 | 1         | 11.11%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 9         | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 9         | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 8         | 88.89%  |
| Yes  | 1         | 11.11%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 4         | 44.44%  |
| 16.01-24.0 | 2         | 22.22%  |
| 4.01-8.0   | 1         | 11.11%  |
| 32.01-64.0 | 1         | 11.11%  |
| 8.01-16.0  | 1         | 11.11%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 4         | 40%     |
| 2.01-3.0 | 3         | 30%     |
| 4.01-8.0 | 1         | 10%     |
| 0.51-1.0 | 1         | 10%     |
| 0.01-0.5 | 1         | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 8         | 88.89%  |
| 2      | 1         | 11.11%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5         | 55.56%  |
| Yes       | 4         | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7         | 77.78%  |
| No        | 2         | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9         | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8         | 88.89%  |
| No        | 1         | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 2         | 22.22%  |
| South Africa | 2         | 22.22%  |
| Sweden       | 1         | 11.11%  |
| Serbia       | 1         | 11.11%  |
| Mexico       | 1         | 11.11%  |
| Japan        | 1         | 11.11%  |
| Brazil       | 1         | 11.11%  |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| SkÃ¶vde    | 1         | 11.11%  |
| Musashino    | 1         | 11.11%  |
| Mexico City  | 1         | 11.11%  |
| McKinney     | 1         | 11.11%  |
| League City  | 1         | 11.11%  |
| Johannesburg | 1         | 11.11%  |
| Fortaleza    | 1         | 11.11%  |
| Cape Town    | 1         | 11.11%  |
| Belgrade     | 1         | 11.11%  |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 30%     |
| Samsung Electronics | 3         | 3      | 30%     |
| Toshiba             | 2         | 2      | 20%     |
| SanDisk             | 1         | 1      | 10%     |
| Hewlett-Packard     | 1         | 2      | 10%     |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB               | 2         | 20%     |
| WDC WD10JPVT-08A1YT2 1TB               | 1         | 10%     |
| Toshiba MQ04ABF100 1TB                 | 1         | 10%     |
| Toshiba MQ01ABF050 500GB               | 1         | 10%     |
| SanDisk SDSSDA240G 240GB               | 1         | 10%     |
| Samsung SSD 980 PRO 500GB              | 1         | 10%     |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 1         | 10%     |
| Samsung MZVKW512HMJP-000H1 512GB       | 1         | 10%     |
| HP SSD EX950 2TB                       | 1         | 10%     |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Toshiba | 2         | 2      | 40%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 50%     |
| NVMe | 4         | 5      | 40%     |
| SSD  | 1         | 1      | 10%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6         | 6      | 60%     |
| NVMe | 4         | 5      | 40%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 4         | 4      | 66.67%  |
| 0.01-0.5   | 2         | 2      | 33.33%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 4         | 44.44%  |
| 1001-2000  | 2         | 22.22%  |
| 501-1000   | 2         | 22.22%  |
| 101-250    | 1         | 11.11%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 101-250 | 4         | 44.44%  |
| 251-500 | 2         | 22.22%  |
| 1-20    | 2         | 22.22%  |
| 21-50   | 1         | 11.11%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 7         | 8      | 77.78%  |
| Detected | 2         | 3      | 22.22%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 5         | 50%     |
| Samsung Electronics      | 3         | 30%     |
| Biwin Storage Technology | 1         | 10%     |
| AMD                      | 1         | 10%     |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 10%     |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 10%     |
| Samsung NVMe SSD Controller 980                                                  | 1         | 10%     |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 10%     |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 10%     |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1         | 10%     |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 10%     |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 10%     |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 10%     |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5         | 50%     |
| NVMe | 4         | 40%     |
| RAID | 1         | 10%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 8         | 88.89%  |
| AMD    | 1         | 11.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 11.11%  |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 11.11%  |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 11.11%  |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 11.11%  |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 11.11%  |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 11.11%  |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 11.11%  |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 11.11%  |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 11.11%  |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Other         | 2         | 22.22%  |
| Intel Core i7 | 2         | 22.22%  |
| Intel Core i5 | 2         | 22.22%  |
| Intel Core i3 | 1         | 11.11%  |
| Intel Celeron | 1         | 11.11%  |
| AMD Ryzen 5   | 1         | 11.11%  |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 4         | 44.44%  |
| 2      | 4         | 44.44%  |
| 8      | 1         | 11.11%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 9         | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 8         | 88.89%  |
| 1      | 1         | 11.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 9         | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2         | 22.22%  |
| 0x806ea    | 1         | 11.11%  |
| 0x806d1    | 1         | 11.11%  |
| 0x806c1    | 1         | 11.11%  |
| 0x406c4    | 1         | 11.11%  |
| 0x306d4    | 1         | 11.11%  |
| 0x306a9    | 1         | 11.11%  |
| 0x08108109 | 1         | 11.11%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KabyLake   | 2         | 22.22%  |
| Zen+       | 1         | 11.11%  |
| Westmere   | 1         | 11.11%  |
| TigerLake  | 1         | 11.11%  |
| Silvermont | 1         | 11.11%  |
| IvyBridge  | 1         | 11.11%  |
| Icelake    | 1         | 11.11%  |
| Broadwell  | 1         | 11.11%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 8         | 72.73%  |
| Nvidia | 2         | 18.18%  |
| AMD    | 1         | 9.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 9.09%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 9.09%   |
| Intel UHD Graphics 620                                                                   | 1         | 9.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 9.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 9.09%   |
| Intel HD Graphics 5500                                                                   | 1         | 9.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 9.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 9.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 9.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 9.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 9.09%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 6         | 66.67%  |
| Intel + Nvidia | 2         | 22.22%  |
| 1 x AMD        | 1         | 11.11%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 9         | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 7         | 77.78%  |
| 7.01-8.0   | 1         | 11.11%  |
| 1.01-2.0   | 1         | 11.11%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 3         | 27.27%  |
| BOE                 | 3         | 27.27%  |
| Sony                | 1         | 9.09%   |
| Sharp               | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |
| Hewlett-Packard     | 1         | 9.09%   |
| Chimei Innolux      | 1         | 9.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                        | 1         | 9.09%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 9.09%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 9.09%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 9.09%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 9.09%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 9.09%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch            | 1         | 9.09%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 1         | 9.09%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 1         | 9.09%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 1         | 9.09%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 9.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 5         | 50%     |
| 1920x1080 (FHD) | 4         | 40%     |
| 1360x768        | 1         | 10%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 6         | 54.55%  |
| 14     | 2         | 18.18%  |
| 72     | 1         | 9.09%   |
| 27     | 1         | 9.09%   |
| 13     | 1         | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 81.82%  |
| 501-600     | 1         | 9.09%   |
| 1501-2000   | 1         | 9.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 9         | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 6         | 54.55%  |
| 81-90          | 3         | 27.27%  |
| More than 1000 | 1         | 9.09%   |
| 301-350        | 1         | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 5         | 45.45%  |
| 121-160 | 4         | 36.36%  |
| 1-50    | 1         | 9.09%   |
| 51-100  | 1         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 7         | 77.78%  |
| 2     | 2         | 22.22%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 6         | 46.15%  |
| Intel                 | 5         | 38.46%  |
| Ralink Technology     | 1         | 7.69%   |
| Broadcom Limited      | 1         | 7.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 37.5%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 6.25%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 6.25%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 6.25%   |
| Intel Wireless 8265 / 8275                                        | 1         | 6.25%   |
| Intel Wireless 3165                                               | 1         | 6.25%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 6.25%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 6.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 6.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 6.25%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 1         | 6.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5         | 55.56%  |
| Realtek Semiconductor | 2         | 22.22%  |
| Ralink Technology     | 1         | 11.11%  |
| Broadcom Limited      | 1         | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 1         | 11.11%  |
| Realtek RTL8723DE Wireless Network Adapter               | 1         | 11.11%  |
| Ralink MT7601U Wireless Adapter                          | 1         | 11.11%  |
| Intel Wireless 8265 / 8275                               | 1         | 11.11%  |
| Intel Wireless 3165                                      | 1         | 11.11%  |
| Intel Wi-Fi 6 AX201                                      | 1         | 11.11%  |
| Intel Wi-Fi 6 AX200                                      | 1         | 11.11%  |
| Intel Tiger Lake PCH CNVi WiFi                           | 1         | 11.11%  |
| Broadcom Limited BCM43228 802.11a/b/g/n                  | 1         | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 6         | 85.71%  |
| Intel                 | 1         | 14.29%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 85.71%  |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 14.29%  |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9         | 56.25%  |
| Ethernet | 7         | 43.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7         | 63.64%  |
| Ethernet | 4         | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6         | 66.67%  |
| 1     | 3         | 33.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 8         | 88.89%  |
| Yes  | 1         | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 5         | 62.5%   |
| Realtek Semiconductor | 2         | 25%     |
| Broadcom              | 1         | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Realtek  Bluetooth 4.2 Adapter     | 2         | 25%     |
| Intel AX201 Bluetooth              | 2         | 25%     |
| Intel Bluetooth wireless interface | 1         | 12.5%   |
| Intel Bluetooth Device             | 1         | 12.5%   |
| Intel AX200 Bluetooth              | 1         | 12.5%   |
| Broadcom BCM20702A0                | 1         | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 8         | 72.73%  |
| Nvidia | 2         | 18.18%  |
| AMD    | 1         | 9.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia High Definition Audio Controller                                                           | 1         | 7.69%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 7.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 7.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 7.69%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 7.69%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 7.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 7.69%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 7.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 7.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 7.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 7.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 7.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 7.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Kingston            | 3         | 37.5%   |
| SK Hynix            | 1         | 12.5%   |
| Samsung Electronics | 1         | 12.5%   |
| Neo Forza           | 1         | 12.5%   |
| Essencore Limited   | 1         | 12.5%   |
| A-DATA Technology   | 1         | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s               | 1         | 11.11%  |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 11.11%  |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 11.11%  |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 11.11%  |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 11.11%  |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s               | 1         | 11.11%  |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 11.11%  |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 11.11%  |
| A-DATA RAM AO1L16BC4R1-BX7S 4096MB SODIMM DDR3 1600MT/s              | 1         | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR4 | 4         | 57.14%  |
| DDR3 | 3         | 42.86%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 7         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 4         | 50%     |
| 16384 | 2         | 25%     |
| 8192  | 2         | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 3         | 42.86%  |
| 2667  | 2         | 28.57%  |
| 3200  | 1         | 14.29%  |
| 2400  | 1         | 14.29%  |

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
| Chicony Electronics                    | 3         | 30%     |
| Microdia                               | 2         | 20%     |
| Acer                                   | 2         | 20%     |
| Samsung Electronics                    | 1         | 10%     |
| Quanta                                 | 1         | 10%     |
| Cheng Uei Precision Industry (Foxlink) | 1         | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung Galaxy A5 (MTP)                                        | 1         | 10%     |
| Quanta HP Webcam                                               | 1         | 10%     |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 10%     |
| Microdia Integrated Webcam                                     | 1         | 10%     |
| Chicony Web Camera - FHD                                       | 1         | 10%     |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 10%     |
| Chicony HP HD Camera                                           | 1         | 10%     |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 10%     |
| Acer HD Webcam                                                 | 1         | 10%     |
| Acer BisonCam,NB Pro                                           | 1         | 10%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Synaptics        | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS300 Fingerprint Reader | 1         | 50%     |
| Unknown                                    | 1         | 50%     |

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
| 0     | 6         | 66.67%  |
| 1     | 3         | 33.33%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 2         | 66.67%  |
| Bluetooth          | 1         | 33.33%  |

