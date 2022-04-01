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

Total: 15

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | ThinkPad X230 2325P38       | [1a0cab737b](https://linux-hardware.org/?probe=1a0cab737b) | Mar 10, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401IV... | [0b0c1aca1b](https://linux-hardware.org/?probe=0b0c1aca1b) | Mar 10, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| Framework | Laptop                      | [ae37705198](https://linux-hardware.org/?probe=ae37705198) | Mar 10, 2022 |
| Lenovo    | ThinkPad Edge E530c 3366... | [8ce0419468](https://linux-hardware.org/?probe=8ce0419468) | Feb 13, 2022 |
| Dynabook  | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| HP        | Laptop 15-bs1xx             | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| System76  | Oryx Pro                    | [3cd05d02a8](https://linux-hardware.org/?probe=3cd05d02a8) | Oct 27, 2021 |
| MSI       | Modern 14 B11MO             | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| MSI       | Modern 14 B11MO             | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Dell      | Inspiron 15-3552            | [f76339b0af](https://linux-hardware.org/?probe=f76339b0af) | Aug 31, 2021 |
| HP        | 245 G7 Notebook PC          | [c0806e4955](https://linux-hardware.org/?probe=c0806e4955) | Aug 23, 2021 |
| HP        | 245 G7 Notebook PC          | [c409287d23](https://linux-hardware.org/?probe=c409287d23) | Aug 23, 2021 |
| HP        | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| Dell      | Vostro 3500                 | [53a1179121](https://linux-hardware.org/?probe=53a1179121) | Aug 12, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version     | Notebooks | Percent |
|-------------|-----------|---------|
| 5.15.19     | 3         | 21.43%  |
| 5.16.9-joe1 | 1         | 7.14%   |
| 5.16.12     | 1         | 7.14%   |
| 5.15.1      | 1         | 7.14%   |
| 5.14.9      | 1         | 7.14%   |
| 5.14.8      | 1         | 7.14%   |
| 5.14.10     | 1         | 7.14%   |
| 5.14.0      | 1         | 7.14%   |
| 5.13.8      | 1         | 7.14%   |
| 5.13.5      | 1         | 7.14%   |
| 5.13.11     | 1         | 7.14%   |
| 5.10.91     | 1         | 7.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.19 | 3         | 21.43%  |
| 5.16.9  | 1         | 7.14%   |
| 5.16.12 | 1         | 7.14%   |
| 5.15.1  | 1         | 7.14%   |
| 5.14.9  | 1         | 7.14%   |
| 5.14.8  | 1         | 7.14%   |
| 5.14.10 | 1         | 7.14%   |
| 5.14.0  | 1         | 7.14%   |
| 5.13.8  | 1         | 7.14%   |
| 5.13.5  | 1         | 7.14%   |
| 5.13.11 | 1         | 7.14%   |
| 5.10.91 | 1         | 7.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 4         | 30.77%  |
| 5.14    | 3         | 23.08%  |
| 5.13    | 3         | 23.08%  |
| 5.16    | 2         | 15.38%  |
| 5.10    | 1         | 7.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 13        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 6         | 46.15%  |
| XFCE    | 3         | 23.08%  |
| Unknown | 3         | 23.08%  |
| KDE     | 1         | 7.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 8         | 57.14%  |
| Tty     | 5         | 35.71%  |
| Wayland | 1         | 7.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 6         | 46.15%  |
| Unknown | 5         | 38.46%  |
| XDM     | 2         | 15.38%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 12        | 92.31%  |
| pt_BR | 1         | 7.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 8         | 61.54%  |
| BIOS | 5         | 38.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Ext4  | 12        | 92.31%  |
| Btrfs | 1         | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 9         | 69.23%  |
| MBR     | 2         | 15.38%  |
| Unknown | 2         | 15.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 12        | 85.71%  |
| Yes       | 2         | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 10        | 76.92%  |
| Yes       | 3         | 23.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 4         | 30.77%  |
| Lenovo           | 2         | 15.38%  |
| Dell             | 2         | 15.38%  |
| System76         | 1         | 7.69%   |
| MSI              | 1         | 7.69%   |
| Framework        | 1         | 7.69%   |
| Dynabook         | 1         | 7.69%   |
| ASUSTek Computer | 1         | 7.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| System76 Oryx Pro                     | 1         | 7.69%   |
| MSI Modern 14 B11MO                   | 1         | 7.69%   |
| Lenovo ThinkPad X230 2325P38          | 1         | 7.69%   |
| Lenovo ThinkPad Edge E530c 336669G    | 1         | 7.69%   |
| HP Pavilion Gaming Laptop 16-a0xxx    | 1         | 7.69%   |
| HP Laptop 15-bs1xx                    | 1         | 7.69%   |
| HP EliteBook 840 G5                   | 1         | 7.69%   |
| HP 245 G7 Notebook PC                 | 1         | 7.69%   |
| Framework Laptop                      | 1         | 7.69%   |
| Dynabook P1-C7MP-BL                   | 1         | 7.69%   |
| Dell Vostro 3500                      | 1         | 7.69%   |
| Dell Inspiron 15-3552                 | 1         | 7.69%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 1         | 7.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 2         | 15.38%  |
| System76 Oryx       | 1         | 7.69%   |
| MSI Modern          | 1         | 7.69%   |
| HP Pavilion         | 1         | 7.69%   |
| HP Laptop           | 1         | 7.69%   |
| HP EliteBook        | 1         | 7.69%   |
| HP 245              | 1         | 7.69%   |
| Framework Laptop    | 1         | 7.69%   |
| Dynabook P1-C7MP-BL | 1         | 7.69%   |
| Dell Vostro         | 1         | 7.69%   |
| Dell Inspiron       | 1         | 7.69%   |
| ASUS ROG            | 1         | 7.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 3         | 23.08%  |
| 2020 | 3         | 23.08%  |
| 2012 | 2         | 15.38%  |
| 2019 | 1         | 7.69%   |
| 2018 | 1         | 7.69%   |
| 2017 | 1         | 7.69%   |
| 2015 | 1         | 7.69%   |
| 2010 | 1         | 7.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 13        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 13        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 11        | 84.62%  |
| Yes  | 2         | 15.38%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 4         | 30.77%  |
| 16.01-24.0 | 3         | 23.08%  |
| 8.01-16.0  | 3         | 23.08%  |
| 4.01-8.0   | 2         | 15.38%  |
| 32.01-64.0 | 1         | 7.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 5         | 35.71%  |
| 4.01-8.0 | 4         | 28.57%  |
| 2.01-3.0 | 3         | 21.43%  |
| 0.51-1.0 | 1         | 7.14%   |
| 0.01-0.5 | 1         | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 11        | 84.62%  |
| 2      | 2         | 15.38%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 9         | 69.23%  |
| Yes       | 4         | 30.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9         | 69.23%  |
| No        | 4         | 30.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 92.31%  |
| No        | 1         | 7.69%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 5         | 38.46%  |
| South Africa | 2         | 15.38%  |
| Sweden       | 1         | 7.69%   |
| Spain        | 1         | 7.69%   |
| Serbia       | 1         | 7.69%   |
| Mexico       | 1         | 7.69%   |
| Japan        | 1         | 7.69%   |
| Brazil       | 1         | 7.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| SkÃ¶vde    | 1         | 7.69%   |
| Reno         | 1         | 7.69%   |
| Plainwell    | 1         | 7.69%   |
| Musashino    | 1         | 7.69%   |
| Mexico City  | 1         | 7.69%   |
| McKinney     | 1         | 7.69%   |
| League City  | 1         | 7.69%   |
| Johannesburg | 1         | 7.69%   |
| Fortaleza    | 1         | 7.69%   |
| Cape Town    | 1         | 7.69%   |
| Belgrade     | 1         | 7.69%   |
| Algeciras    | 1         | 7.69%   |
| Abingdon     | 1         | 7.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 33.33%  |
| WDC                 | 4         | 4      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| SanDisk             | 1         | 1      | 6.67%   |
| Kingston            | 1         | 1      | 6.67%   |
| Hewlett-Packard     | 1         | 2      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 13.33%  |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 6.67%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB   | 1         | 6.67%   |
| Toshiba MQ04ABF100 1TB               | 1         | 6.67%   |
| Toshiba MQ01ABF050 500GB             | 1         | 6.67%   |
| SanDisk SDSSDA240G 240GB             | 1         | 6.67%   |
| Samsung SSD 980 PRO 500GB            | 1         | 6.67%   |
| Samsung NVMe SSD Drive 256GB         | 1         | 6.67%   |
| Samsung MZVLQ512HALU-000H1 512GB     | 1         | 6.67%   |
| Samsung MZVKW512HMJP-000H1 512GB     | 1         | 6.67%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD | 1         | 6.67%   |
| Kingston SUV400S37240G 240GB SSD     | 1         | 6.67%   |
| HP SSD EX950 2TB                     | 1         | 6.67%   |
| Crucial CT500P2SSD8 500GB            | 1         | 6.67%   |

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


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Kingston            | 1         | 1      | 33.33%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 7         | 8      | 46.67%  |
| HDD  | 5         | 5      | 33.33%  |
| SSD  | 3         | 3      | 20%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 8         | 8      | 53.33%  |
| NVMe | 7         | 8      | 46.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 4         | 4      | 50%     |
| 0.01-0.5   | 4         | 4      | 50%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 5         | 38.46%  |
| 501-1000   | 4         | 30.77%  |
| 101-250    | 2         | 15.38%  |
| 1001-2000  | 2         | 15.38%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 101-250 | 4         | 30.77%  |
| 251-500 | 3         | 23.08%  |
| 21-50   | 3         | 23.08%  |
| 1-20    | 2         | 15.38%  |
| 51-100  | 1         | 7.69%   |

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
| Works    | 11        | 13     | 84.62%  |
| Detected | 2         | 3      | 15.38%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 7         | 43.75%  |
| Samsung Electronics       | 4         | 25%     |
| AMD                       | 2         | 12.5%   |
| Sandisk                   | 1         | 6.25%   |
| Micron/Crucial Technology | 1         | 6.25%   |
| Biwin Storage Technology  | 1         | 6.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980                                                  | 2         | 12.5%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 12.5%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 12.5%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 12.5%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 6.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 6.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 6.25%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 6.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 6.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 6.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 6.25%   |
| Biwin Storage Non-Volatile memory controller                                     | 1         | 6.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 7         | 43.75%  |
| SATA | 7         | 43.75%  |
| RAID | 2         | 12.5%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 11        | 84.62%  |
| AMD    | 2         | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 7.69%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 7.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 7.69%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 7.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 7.69%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 7.69%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 7.69%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 7.69%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 1         | 7.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 7.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 7.69%   |
| AMD Ryzen 9 4900HS with Radeon Graphics       | 1         | 7.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 7.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Other         | 3         | 23.08%  |
| Intel Core i7 | 3         | 23.08%  |
| Intel Core i5 | 3         | 23.08%  |
| Intel Core i3 | 1         | 7.69%   |
| Intel Celeron | 1         | 7.69%   |
| AMD Ryzen 9   | 1         | 7.69%   |
| AMD Ryzen 5   | 1         | 7.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 5         | 38.46%  |
| 2      | 5         | 38.46%  |
| 8      | 3         | 23.08%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 92.31%  |
| 1      | 1         | 7.69%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 13        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3         | 23.08%  |
| 0x806c1    | 2         | 15.38%  |
| 0x306a9    | 2         | 15.38%  |
| 0xa0652    | 1         | 7.69%   |
| 0x806ea    | 1         | 7.69%   |
| 0x806d1    | 1         | 7.69%   |
| 0x406c4    | 1         | 7.69%   |
| 0x306d4    | 1         | 7.69%   |
| 0x08108109 | 1         | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| TigerLake  | 2         | 15.38%  |
| KabyLake   | 2         | 15.38%  |
| IvyBridge  | 2         | 15.38%  |
| Zen+       | 1         | 7.69%   |
| Zen 2      | 1         | 7.69%   |
| Westmere   | 1         | 7.69%   |
| Silvermont | 1         | 7.69%   |
| Icelake    | 1         | 7.69%   |
| CometLake  | 1         | 7.69%   |
| Broadwell  | 1         | 7.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 11        | 64.71%  |
| Nvidia | 4         | 23.53%  |
| AMD    | 2         | 11.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 11.76%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 11.76%  |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 5.88%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 5.88%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 5.88%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 5.88%   |
| Intel UHD Graphics 620                                                                   | 1         | 5.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 5.88%   |
| Intel HD Graphics 5500                                                                   | 1         | 5.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 5.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 5.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 5.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 5.88%   |
| AMD Renoir                                                                               | 1         | 5.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 8         | 61.54%  |
| Intel + Nvidia | 3         | 23.08%  |
| AMD + Nvidia   | 1         | 7.69%   |
| 1 x AMD        | 1         | 7.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 12        | 92.31%  |
| Proprietary | 1         | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 76.92%  |
| 7.01-8.0   | 1         | 7.69%   |
| 1.01-2.0   | 1         | 7.69%   |
| 0.01-0.5   | 1         | 7.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 5         | 31.25%  |
| LG Display          | 3         | 18.75%  |
| Sony                | 1         | 6.25%   |
| Sharp               | 1         | 6.25%   |
| Samsung Electronics | 1         | 6.25%   |
| PANDA               | 1         | 6.25%   |
| Hewlett-Packard     | 1         | 6.25%   |
| Dell                | 1         | 6.25%   |
| Chimei Innolux      | 1         | 6.25%   |
| AU Optronics        | 1         | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sony TV SNY8102 1360x768 1600x900mm 72.3-inch                        | 1         | 6.25%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 6.25%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 1         | 6.25%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 6.25%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 1         | 6.25%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch         | 1         | 6.25%   |
| LG Display LCD Monitor LGD028A 1366x768 344x194mm 15.5-inch          | 1         | 6.25%   |
| Hewlett-Packard 27m HPN3579 1920x1080 598x336mm 27.0-inch            | 1         | 6.25%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                     | 1         | 6.25%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 1         | 6.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 1         | 6.25%   |
| BOE LCD Monitor BOE08F6 1920x1080 355x200mm 16.0-inch                | 1         | 6.25%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 1         | 6.25%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 1         | 6.25%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 6.25%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 1         | 6.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 6         | 42.86%  |
| 1366x768 (WXGA) | 6         | 42.86%  |
| 2256x1504       | 1         | 7.14%   |
| 1360x768        | 1         | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 6         | 37.5%   |
| 14     | 3         | 18.75%  |
| 13     | 2         | 12.5%   |
| 72     | 1         | 6.25%   |
| 27     | 1         | 6.25%   |
| 24     | 1         | 6.25%   |
| 16     | 1         | 6.25%   |
| 12     | 1         | 6.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 62.5%   |
| 501-600     | 2         | 12.5%   |
| 201-300     | 2         | 12.5%   |
| 351-400     | 1         | 6.25%   |
| 1501-2000   | 1         | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 12        | 85.71%  |
| 3/2   | 1         | 7.14%   |
| 16/10 | 1         | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7         | 43.75%  |
| 81-90          | 5         | 31.25%  |
| More than 1000 | 1         | 6.25%   |
| 61-70          | 1         | 6.25%   |
| 301-350        | 1         | 6.25%   |
| 251-300        | 1         | 6.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 7         | 43.75%  |
| 101-120 | 5         | 31.25%  |
| 51-100  | 2         | 12.5%   |
| 1-50    | 1         | 6.25%   |
| 161-240 | 1         | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 10        | 76.92%  |
| 2     | 3         | 23.08%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 50%     |
| Realtek Semiconductor | 7         | 38.89%  |
| Ralink Technology     | 1         | 5.56%   |
| Broadcom Limited      | 1         | 5.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 31.82%  |
| Intel Wi-Fi 6 AX200                                               | 2         | 9.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 4.55%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 4.55%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 4.55%   |
| Intel Wireless 8265 / 8275                                        | 1         | 4.55%   |
| Intel Wireless 3165                                               | 1         | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 4.55%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 4.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 4.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 4.55%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                           | 1         | 4.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 69.23%  |
| Realtek Semiconductor | 2         | 15.38%  |
| Ralink Technology     | 1         | 7.69%   |
| Broadcom Limited      | 1         | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                      | 2         | 15.38%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter | 1         | 7.69%   |
| Realtek RTL8723DE Wireless Network Adapter               | 1         | 7.69%   |
| Ralink MT7601U Wireless Adapter                          | 1         | 7.69%   |
| Intel Wireless 8265 / 8275                               | 1         | 7.69%   |
| Intel Wireless 3165                                      | 1         | 7.69%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                   | 1         | 7.69%   |
| Intel Wi-Fi 6 AX201                                      | 1         | 7.69%   |
| Intel Tiger Lake PCH CNVi WiFi                           | 1         | 7.69%   |
| Intel Comet Lake PCH CNVi WiFi                           | 1         | 7.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]             | 1         | 7.69%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                  | 1         | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 7         | 77.78%  |
| Intel                 | 2         | 22.22%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 77.78%  |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 11.11%  |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 13        | 59.09%  |
| Ethernet | 9         | 40.91%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 11        | 73.33%  |
| Ethernet | 4         | 26.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 8         | 61.54%  |
| 1     | 5         | 38.46%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12        | 92.31%  |
| Yes  | 1         | 7.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 8         | 66.67%  |
| Realtek Semiconductor | 2         | 16.67%  |
| Broadcom              | 2         | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                      | 3         | 25%     |
| Realtek  Bluetooth 4.2 Adapter             | 2         | 16.67%  |
| Intel Bluetooth wireless interface         | 2         | 16.67%  |
| Intel AX200 Bluetooth                      | 2         | 16.67%  |
| Intel AX210 Bluetooth                      | 1         | 8.33%   |
| Broadcom BCM20702A0                        | 1         | 8.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad] | 1         | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 11        | 61.11%  |
| Nvidia              | 4         | 22.22%  |
| AMD                 | 2         | 11.11%  |
| C-Media Electronics | 1         | 5.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 9.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 9.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 9.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 4.76%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 4.76%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 4.76%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 4.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 4.76%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 4.76%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 4.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 4.76%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 4.76%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 4.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 4.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 4.76%   |
| C-Media Electronics CM6631A Audio Processor                                                       | 1         | 4.76%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 4.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 4.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Kingston            | 3         | 23.08%  |
| SK Hynix            | 2         | 15.38%  |
| Samsung Electronics | 2         | 15.38%  |
| Micron Technology   | 2         | 15.38%  |
| Neo Forza           | 1         | 7.69%   |
| Essencore Limited   | 1         | 7.69%   |
| Crucial             | 1         | 7.69%   |
| A-DATA Technology   | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s               | 1         | 7.14%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s            | 1         | 7.14%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                | 1         | 7.14%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                | 1         | 7.14%   |
| Neo Forza RAM NMSO480E82-3200E 8GB SODIMM DDR4 3200MT/s              | 1         | 7.14%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                 | 1         | 7.14%   |
| Micron RAM 16KTF51264HZ-1G4 4096MB SODIMM DDR3 701MT/s               | 1         | 7.14%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                     | 1         | 7.14%   |
| Kingston RAM 9905712-007.A00G 16384MB SODIMM DDR4 2400MT/s           | 1         | 7.14%   |
| Kingston RAM 9905711-032.A00G 8GB SODIMM DDR4 2667MT/s               | 1         | 7.14%   |
| Kingston RAM 9905703-011.A00G 16GB SODIMM DDR4 2400MT/s              | 1         | 7.14%   |
| Essencore Limited RAM KD4AGSA8M-26N1900 16384MB SODIMM DDR4 2667MT/s | 1         | 7.14%   |
| Crucial RAM BL8G32C16S4B.8FE 8GB SODIMM DDR4 2667MT/s                | 1         | 7.14%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4096MB SODIMM DDR3 1600MT/s              | 1         | 7.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR4 | 7         | 63.64%  |
| DDR3 | 4         | 36.36%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 11        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 6         | 50%     |
| 8192  | 4         | 33.33%  |
| 16384 | 2         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 4         | 33.33%  |
| 3200  | 3         | 25%     |
| 2667  | 3         | 25%     |
| 2400  | 1         | 8.33%   |
| 701   | 1         | 8.33%   |

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
| Chicony Electronics                    | 4         | 30.77%  |
| Acer                                   | 3         | 23.08%  |
| Microdia                               | 2         | 15.38%  |
| Samsung Electronics                    | 1         | 7.69%   |
| Realtek Semiconductor                  | 1         | 7.69%   |
| Quanta                                 | 1         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 7.69%   |
| Realtek Laptop Camera                                          | 1         | 7.69%   |
| Quanta HP Webcam                                               | 1         | 7.69%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 7.69%   |
| Microdia Integrated Webcam                                     | 1         | 7.69%   |
| Chicony Web Camera - FHD                                       | 1         | 7.69%   |
| Chicony Integrated Camera [ThinkPad]                           | 1         | 7.69%   |
| Chicony HP TrueVision HD Camera                                | 1         | 7.69%   |
| Chicony HP HD Camera                                           | 1         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 7.69%   |
| Acer ThinkPad Integrated Camera                                | 1         | 7.69%   |
| Acer HD Webcam                                                 | 1         | 7.69%   |
| Acer BisonCam,NB Pro                                           | 1         | 7.69%   |

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
| 0     | 9         | 69.23%  |
| 1     | 4         | 30.77%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 2         | 50%     |
| Multimedia controller | 1         | 25%     |
| Bluetooth             | 1         | 25%     |

