Slackware 15.0 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

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

| Vendor  | Model             | Probe                                                      | Date         |
|---------|-------------------|------------------------------------------------------------|--------------|
| Biostar | X470GTA           | [8d400b49f8](https://linux-hardware.org/?probe=8d400b49f8) | Feb 13, 2022 |
| MSI     | G31TM-P21         | [dda6a57223](https://linux-hardware.org/?probe=dda6a57223) | Feb 07, 2022 |
| HP      | 212B              | [353b0dde99](https://linux-hardware.org/?probe=353b0dde99) | Jan 29, 2022 |
| MSI     | B450 TOMAHAWK MAX | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| MSI     | G31TM-P21         | [25d668ee95](https://linux-hardware.org/?probe=25d668ee95) | Jan 10, 2022 |
| MSI     | H61M-P31          | [58651bba67](https://linux-hardware.org/?probe=58651bba67) | Dec 07, 2021 |
| MSI     | B450M-A PRO MAX   | [b7df25ba5d](https://linux-hardware.org/?probe=b7df25ba5d) | Oct 25, 2021 |
| ASUSTek | SABERTOOTH X99    | [64e5ee1691](https://linux-hardware.org/?probe=64e5ee1691) | Oct 13, 2021 |
| MSI     | B450M-A PRO MAX   | [17d37c5316](https://linux-hardware.org/?probe=17d37c5316) | Oct 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Desktops | Percent |
|----------------|----------|---------|
| 5.15.6         | 1        | 14.29%  |
| 5.15.19        | 1        | 14.29%  |
| 5.15.14        | 1        | 14.29%  |
| 5.14.15-Unraid | 1        | 14.29%  |
| 5.14.15        | 1        | 14.29%  |
| 5.14.11        | 1        | 14.29%  |
| 5.13.12        | 1        | 14.29%  |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.15 | 2        | 28.57%  |
| 5.15.6  | 1        | 14.29%  |
| 5.15.19 | 1        | 14.29%  |
| 5.15.14 | 1        | 14.29%  |
| 5.14.11 | 1        | 14.29%  |
| 5.13.12 | 1        | 14.29%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 3        | 42.86%  |
| 5.14    | 3        | 42.86%  |
| 5.13    | 1        | 14.29%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 7        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 5        | 62.5%   |
| Unknown | 2        | 25%     |
| XFCE    | 1        | 12.5%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 5        | 62.5%   |
| Tty     | 2        | 25%     |
| Unknown | 1        | 12.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 5        | 71.43%  |
| Unknown | 2        | 28.57%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 5        | 71.43%  |
| en_US.ASCII | 1        | 14.29%  |
| Unknown     | 1        | 14.29%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 4        | 57.14%  |
| EFI  | 3        | 42.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 5        | 71.43%  |
| F2fs  | 1        | 14.29%  |
| Btrfs | 1        | 14.29%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 6        | 75%     |
| MBR     | 1        | 12.5%   |
| Unknown | 1        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4        | 57.14%  |
| No        | 3        | 42.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 71.43%  |
| Yes       | 2        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| MSI              | 4        | 57.14%  |
| Hewlett-Packard  | 1        | 14.29%  |
| Biostar          | 1        | 14.29%  |
| ASUSTek Computer | 1        | 14.29%  |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI MS-7C52         | 1        | 14.29%  |
| MSI MS-7C02         | 1        | 14.29%  |
| MSI MS-7788         | 1        | 14.29%  |
| MSI MS-7529         | 1        | 14.29%  |
| HP Z440 Workstation | 1        | 14.29%  |
| Biostar X470GTA     | 1        | 14.29%  |
| ASUS All Series     | 1        | 14.29%  |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| MSI MS-7C52     | 1        | 14.29%  |
| MSI MS-7C02     | 1        | 14.29%  |
| MSI MS-7788     | 1        | 14.29%  |
| MSI MS-7529     | 1        | 14.29%  |
| HP Z440         | 1        | 14.29%  |
| Biostar X470GTA | 1        | 14.29%  |
| ASUS All        | 1        | 14.29%  |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 2        | 28.57%  |
| 2020 | 1        | 14.29%  |
| 2016 | 1        | 14.29%  |
| 2015 | 1        | 14.29%  |
| 2011 | 1        | 14.29%  |
| 2009 | 1        | 14.29%  |

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
| 32.01-64.0  | 2        | 28.57%  |
| 64.01-256.0 | 2        | 28.57%  |
| 4.01-8.0    | 1        | 14.29%  |
| 3.01-4.0    | 1        | 14.29%  |
| 16.01-24.0  | 1        | 14.29%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 4        | 50%     |
| 0.51-1.0   | 2        | 25%     |
| 32.01-64.0 | 1        | 12.5%   |
| 1.01-2.0   | 1        | 12.5%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 3        | 42.86%  |
| 4      | 2        | 28.57%  |
| 6      | 1        | 14.29%  |
| 1      | 1        | 14.29%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4        | 57.14%  |
| No        | 3        | 42.86%  |

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
| No        | 4        | 57.14%  |
| Yes       | 3        | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 71.43%  |
| Yes       | 2        | 28.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 2        | 28.57%  |
| UK           | 1        | 14.29%  |
| South Africa | 1        | 14.29%  |
| Japan        | 1        | 14.29%  |
| Italy        | 1        | 14.29%  |
| Brazil       | 1        | 14.29%  |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Verona       | 1        | 14.29%  |
| Porto Alegre | 1        | 14.29%  |
| Musashino    | 1        | 14.29%  |
| Milwaukee    | 1        | 14.29%  |
| Mead         | 1        | 14.29%  |
| Cape Town    | 1        | 14.29%  |
| Belfast      | 1        | 14.29%  |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 21.05%  |
| Samsung Electronics | 4        | 5      | 21.05%  |
| WDC                 | 2        | 4      | 10.53%  |
| Toshiba             | 2        | 4      | 10.53%  |
| Hitachi             | 2        | 2      | 10.53%  |
| Patriot             | 1        | 1      | 5.26%   |
| Intenso             | 1        | 1      | 5.26%   |
| HGST                | 1        | 1      | 5.26%   |
| Gigabyte Technology | 1        | 1      | 5.26%   |
| Crucial             | 1        | 1      | 5.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WD5000AAKX-22ERMA0 500GB         | 1        | 4.55%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1        | 4.55%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1        | 4.55%   |
| Toshiba HDWD240 4TB                  | 1        | 4.55%   |
| Toshiba DT01ACA300 3TB               | 1        | 4.55%   |
| Seagate ST380011A 80GB               | 1        | 4.55%   |
| Seagate ST3000VX006-1HH166 3TB       | 1        | 4.55%   |
| Seagate ST2000DM008-2FR102 2TB       | 1        | 4.55%   |
| Seagate ST1000DM003-1SB102 1TB       | 1        | 4.55%   |
| Seagate Expansion Desk 8TB           | 1        | 4.55%   |
| Samsung SSD 970 EVO Plus 1TB         | 1        | 4.55%   |
| Samsung SSD 860 EVO 500GB            | 1        | 4.55%   |
| Samsung SSD 860 500GB                | 1        | 4.55%   |
| Samsung SSD 840 Series 250GB         | 1        | 4.55%   |
| Samsung MZHPV512HDGL-00000 512GB SSD | 1        | 4.55%   |
| Patriot Burst Elite 120GB SSD        | 1        | 4.55%   |
| Intenso SSD SATAIII 480GB            | 1        | 4.55%   |
| Hitachi HUA723030ALA640 3TB          | 1        | 4.55%   |
| Hitachi HDS721016CLA382 160GB        | 1        | 4.55%   |
| HGST HUH728080ALE600 8TB             | 1        | 4.55%   |
| Gigabyte GP-ASM2NE6100TTTD 1TB       | 1        | 4.55%   |
| Crucial CT500MX500SSD1 500GB         | 1        | 4.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 36.36%  |
| WDC     | 2        | 4      | 18.18%  |
| Toshiba | 2        | 4      | 18.18%  |
| Hitachi | 2        | 2      | 18.18%  |
| HGST    | 1        | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 50%     |
| Patriot             | 1        | 1      | 16.67%  |
| Intenso             | 1        | 1      | 16.67%  |
| Crucial             | 1        | 1      | 16.67%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 16     | 46.15%  |
| SSD  | 5        | 7      | 38.46%  |
| NVMe | 2        | 2      | 15.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 7        | 22     | 70%     |
| NVMe | 2        | 2      | 20%     |
| SAS  | 1        | 1      | 10%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 7        | 9      | 43.75%  |
| 1.01-2.0   | 3        | 4      | 18.75%  |
| 4.01-10.0  | 2        | 2      | 12.5%   |
| 0.51-1.0   | 2        | 2      | 12.5%   |
| 3.01-4.0   | 1        | 1      | 6.25%   |
| 2.01-3.0   | 1        | 5      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 2        | 25%     |
| More than 3000 | 1        | 12.5%   |
| 2001-3000      | 1        | 12.5%   |
| 101-250        | 1        | 12.5%   |
| 501-1000       | 1        | 12.5%   |
| 51-100         | 1        | 12.5%   |
| Unknown        | 1        | 12.5%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 2        | 28.57%  |
| More than 3000 | 1        | 14.29%  |
| 21-50          | 1        | 14.29%  |
| 101-250        | 1        | 14.29%  |
| 501-1000       | 1        | 14.29%  |
| Unknown        | 1        | 14.29%  |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD5000AAKX-22ERMA0 500GB   | 1        | 1      | 16.67%  |
| WDC WD20EFRX-68EUZN0 2TB       | 1        | 2      | 16.67%  |
| Seagate ST380011A 80GB         | 1        | 1      | 16.67%  |
| Seagate ST3000VX006-1HH166 3TB | 1        | 1      | 16.67%  |
| Hitachi HUA723030ALA640 3TB    | 1        | 1      | 16.67%  |
| Hitachi HDS721016CLA382 160GB  | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 3      | 33.33%  |
| Seagate | 2        | 2      | 33.33%  |
| Hitachi | 2        | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 3      | 33.33%  |
| Seagate | 2        | 2      | 33.33%  |
| Hitachi | 2        | 2      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 7      | 100%    |

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
| Works    | 5        | 14     | 45.45%  |
| Malfunc  | 4        | 7      | 36.36%  |
| Detected | 2        | 4      | 18.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 4        | 36.36%  |
| AMD                 | 3        | 27.27%  |
| Samsung Electronics | 2        | 18.18%  |
| Phison Electronics  | 1        | 9.09%   |
| Adaptec             | 1        | 9.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 17.65%  |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 11.76%  |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 11.76%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 2        | 11.76%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 5.88%   |
| Samsung Electronics SATA controller                                                     | 1        | 5.88%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 5.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 5.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 5.88%   |
| Adaptec SCSI storage controller                                                         | 1        | 5.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 5        | 50%     |
| NVMe | 2        | 20%     |
| IDE  | 2        | 20%     |
| SCSI | 1        | 10%     |

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


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz  | 1        | 14.29%  |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz  | 1        | 14.29%  |
| Intel Core i5-3330 CPU @ 3.00GHz     | 1        | 14.29%  |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz | 1        | 14.29%  |
| AMD Ryzen 9 5950X 16-Core Processor  | 1        | 14.29%  |
| AMD Ryzen 7 3800X 8-Core Processor   | 1        | 14.29%  |
| AMD Ryzen 7 3700X 8-Core Processor   | 1        | 14.29%  |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Xeon       | 2        | 28.57%  |
| AMD Ryzen 7      | 2        | 28.57%  |
| Intel Core i5    | 1        | 14.29%  |
| Intel Core 2 Duo | 1        | 14.29%  |
| AMD Ryzen 9      | 1        | 14.29%  |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 8      | 2        | 28.57%  |
| 16     | 1        | 14.29%  |
| 14     | 1        | 14.29%  |
| 10     | 1        | 14.29%  |
| 4      | 1        | 14.29%  |
| 2      | 1        | 14.29%  |

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
| 2      | 5        | 71.43%  |
| 1      | 2        | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 7        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306f2    | 2        | 28.57%  |
| 0x306a9    | 1        | 14.29%  |
| 0x1067a    | 1        | 14.29%  |
| 0x0a201016 | 1        | 14.29%  |
| 0x08701021 | 1        | 14.29%  |
| Unknown    | 1        | 14.29%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Zen 2     | 2        | 28.57%  |
| Haswell   | 2        | 28.57%  |
| Zen 3     | 1        | 14.29%  |
| Penryn    | 1        | 14.29%  |
| IvyBridge | 1        | 14.29%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 5        | 62.5%   |
| Intel  | 2        | 25%     |
| Nvidia | 1        | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                   | 2        | 25%     |
| Nvidia GF108 [GeForce GT 630]                                    | 1        | 12.5%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 12.5%   |
| Intel 82G33/G31 Express Integrated Graphics Controller           | 1        | 12.5%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                   | 1        | 12.5%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 1        | 12.5%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                 | 1        | 12.5%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 5        | 71.43%  |
| Intel + Nvidia | 1        | 14.29%  |
| 1 x Intel      | 1        | 14.29%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Desktops | Percent |
|--------|----------|---------|
| Free   | 7        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 42.86%  |
| 8.01-16.0  | 2        | 28.57%  |
| 7.01-8.0   | 1        | 14.29%  |
| 0.51-1.0   | 1        | 14.29%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Ancor Communications | 3        | 33.33%  |
| Samsung Electronics  | 2        | 22.22%  |
| Wacom                | 1        | 11.11%  |
| Lenovo               | 1        | 11.11%  |
| IOD                  | 1        | 11.11%  |
| Acer                 | 1        | 11.11%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Wacom Cintiq 22HDT WAC1037 1920x1080 476x268mm 21.5-inch              | 1        | 11.11%  |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch  | 1        | 11.11%  |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 11.11%  |
| Lenovo LEN L1700pC LEN24C9 1280x1024 338x270mm 17.0-inch              | 1        | 11.11%  |
| IOD LCD-GL211X IOD151D 1920x1080 458x258mm 20.7-inch                  | 1        | 11.11%  |
| Ancor Communications ROG PG348Q ACI3433 3440x1440 797x333mm 34.0-inch | 1        | 11.11%  |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 11.11%  |
| Ancor Communications ASUS MG28U ACI28A7 3840x2160 621x341mm 27.9-inch | 1        | 11.11%  |
| Acer AL1714 ACRAD18 1280x1024 338x270mm 17.0-inch                     | 1        | 11.11%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 4        | 44.44%  |
| 1280x1024 (SXGA) | 2        | 22.22%  |
| 3840x2160 (4K)   | 1        | 11.11%  |
| 3440x1440        | 1        | 11.11%  |
| 1600x1200        | 1        | 11.11%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 3        | 33.33%  |
| 20     | 2        | 22.22%  |
| 17     | 2        | 22.22%  |
| 34     | 1        | 11.11%  |
| 27     | 1        | 11.11%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 4        | 50%     |
| 301-350     | 2        | 25%     |
| 701-800     | 1        | 12.5%   |
| 601-700     | 1        | 12.5%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 4        | 50%     |
| 5/4   | 2        | 25%     |
| 4/3   | 1        | 12.5%   |
| 21/9  | 1        | 12.5%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2        | 25%     |
| 151-200        | 2        | 25%     |
| 141-150        | 2        | 25%     |
| 351-500        | 1        | 12.5%   |
| 301-350        | 1        | 12.5%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 5        | 55.56%  |
| 51-100  | 3        | 33.33%  |
| 121-160 | 1        | 11.11%  |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 55.56%  |
| Intel                 | 2        | 22.22%  |
| Ralink                | 1        | 11.11%  |
| Qualcomm Atheros      | 1        | 11.11%  |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 30%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 20%     |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 10%     |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1        | 10%     |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 10%     |
| Intel Ethernet Connection (2) I218-V                              | 1        | 10%     |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 10%     |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 33.33%  |
| Ralink                | 1        | 33.33%  |
| Qualcomm Atheros      | 1        | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 33.33%  |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1        | 33.33%  |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 71.43%  |
| Intel                 | 2        | 28.57%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 42.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 28.57%  |
| Intel Ethernet Connection (2) I218-V                              | 1        | 14.29%  |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 14.29%  |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 7        | 70%     |
| WiFi     | 3        | 30%     |

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
| 1     | 4        | 57.14%  |
| 2     | 3        | 42.86%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 7        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 2        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| AMD              | 5        | 45.45%  |
| Intel            | 2        | 18.18%  |
| Creative Labs    | 2        | 18.18%  |
| Nvidia           | 1        | 9.09%   |
| ASUSTek Computer | 1        | 9.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 21.43%  |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 2        | 14.29%  |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 7.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 7.14%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1        | 7.14%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 7.14%   |
| ASUSTek Computer XONAR SOUND CARD                                          | 1        | 7.14%   |
| AMD Navi 10 HDMI Audio                                                     | 1        | 7.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 7.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 7.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 28.57%  |
| Unknown             | 1        | 14.29%  |
| Team                | 1        | 14.29%  |
| Strontium           | 1        | 14.29%  |
| G.Skill             | 1        | 14.29%  |
| A-DATA Technology   | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                      | 1        | 12.5%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s       | 1        | 12.5%   |
| Strontium RAM SRT4G86U1-P9H 4096MB DIMM DDR3 1333MT/s     | 1        | 12.5%   |
| Samsung RAM M393A2G40DB0-CPB 16GB RIMM DDR4 2133MT/s      | 1        | 12.5%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s       | 1        | 12.5%   |
| Samsung RAM M393A1G43EB1-CRC 8GB DIMM DDR4 2400MT/s       | 1        | 12.5%   |
| G.Skill RAM F4-3200C16-16GTZSW 16384MB DIMM DDR4 3200MT/s | 1        | 12.5%   |
| A-DATA RAM Module 4096MB DIMM DDR3 1333MT/s               | 1        | 12.5%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 4        | 66.67%  |
| SDRAM | 1        | 16.67%  |
| DDR3  | 1        | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 5        | 83.33%  |
| RIMM | 1        | 16.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 2        | 33.33%  |
| 32768 | 1        | 16.67%  |
| 8192  | 1        | 16.67%  |
| 4096  | 1        | 16.67%  |
| 2048  | 1        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 2        | 33.33%  |
| 2400    | 1        | 16.67%  |
| 2133    | 1        | 16.67%  |
| 1333    | 1        | 16.67%  |
| Unknown | 1        | 16.67%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| QinHeng Electronics | 1        | 33.33%  |
| Hewlett-Packard     | 1        | 33.33%  |
| Dell                | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| QinHeng CH340S               | 1        | 33.33%  |
| HP OfficeJet Pro 9010 series | 1        | 33.33%  |
| Dell 2330d Laser Printer     | 1        | 33.33%  |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 2        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech QuickCam Pro 9000      | 1        | 50%     |
| Logitech C922 Pro Stream Webcam | 1        | 50%     |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3        | 42.86%  |
| 0     | 3        | 42.86%  |
| 3     | 1        | 14.29%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 2        | 33.33%  |
| Sound                    | 1        | 16.67%  |
| Graphics card            | 1        | 16.67%  |
| Communication controller | 1        | 16.67%  |
| Chipcard                 | 1        | 16.67%  |

