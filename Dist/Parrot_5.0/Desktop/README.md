Parrot 5.0 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Parrot 5.0.

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

Total: 20

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| ECS           | Nettle2                 | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                    | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| Lenovo        | SHARKBAY 31900058 STD   | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD   | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                  | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3              | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| ASUSTek       | H170M-E D3              | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| ASRock        | Z87M Extreme4           | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | B85M-E                  | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                  | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Dell          | 0GXM1W A02              | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | 04YP6J A01              | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01              | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF            | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF            | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.14.0-9parrot1-amd64  | 8        | 57.14%  |
| 5.15.0-15parrot1-amd64 | 4        | 28.57%  |
| 5.16.0-12parrot1-amd64 | 1        | 7.14%   |
| 5.14.0-2parrot1-amd64  | 1        | 7.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 8        | 61.54%  |
| 5.15.0  | 4        | 30.77%  |
| 5.16.0  | 1        | 7.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 8        | 61.54%  |
| 5.15    | 4        | 30.77%  |
| 5.16    | 1        | 7.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 12       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 6        | 50%     |
| XFCE    | 2        | 16.67%  |
| KDE5    | 2        | 16.67%  |
| GNOME   | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 10       | 83.33%  |
| Wayland | 2        | 16.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 6        | 50%     |
| Unknown | 5        | 41.67%  |
| GDM     | 1        | 8.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 5        | 41.67%  |
| en_IN | 2        | 16.67%  |
| ru_RU | 1        | 8.33%   |
| pt_BR | 1        | 8.33%   |
| pl_PL | 1        | 8.33%   |
| en_DK | 1        | 8.33%   |
| cs_CZ | 1        | 8.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 9        | 75%     |
| EFI  | 3        | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 9        | 75%     |
| Ext4    | 2        | 16.67%  |
| Overlay | 1        | 8.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 5        | 41.67%  |
| Unknown | 5        | 41.67%  |
| MBR     | 2        | 16.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 91.67%  |
| Yes       | 1        | 8.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 58.33%  |
| Yes       | 5        | 41.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 3        | 25%     |
| Dell                | 2        | 16.67%  |
| SLIMBOOK            | 1        | 8.33%   |
| Lenovo              | 1        | 8.33%   |
| Hewlett-Packard     | 1        | 8.33%   |
| Gigabyte Technology | 1        | 8.33%   |
| ECS                 | 1        | 8.33%   |
| Daewoo Lucoms       | 1        | 8.33%   |
| ASRock              | 1        | 8.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| SLIMBOOK ONE-AMD-M4          | 1        | 8.33%   |
| Lenovo H530 10130            | 1        | 8.33%   |
| HP ProDesk 600 G1 SFF        | 1        | 8.33%   |
| Gigabyte A320M-S2H           | 1        | 8.33%   |
| ECS GV460AA-ABA a6217c       | 1        | 8.33%   |
| Dell OptiPlex 7010           | 1        | 8.33%   |
| Dell OptiPlex 3020           | 1        | 8.33%   |
| Daewoo Lucoms OEM            | 1        | 8.33%   |
| ASUS ROG CROSSHAIR VIII HERO | 1        | 8.33%   |
| ASUS H170M-E D3              | 1        | 8.33%   |
| ASUS Basic 3221BM            | 1        | 8.33%   |
| ASRock Z87M Extreme4         | 1        | 8.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 2        | 16.67%  |
| SLIMBOOK ONE-AMD-M4 | 1        | 8.33%   |
| Lenovo H530         | 1        | 8.33%   |
| HP ProDesk          | 1        | 8.33%   |
| Gigabyte A320M-S2H  | 1        | 8.33%   |
| ECS GV460AA-ABA     | 1        | 8.33%   |
| Daewoo Lucoms OEM   | 1        | 8.33%   |
| ASUS ROG            | 1        | 8.33%   |
| ASUS H170M-E        | 1        | 8.33%   |
| ASUS Basic          | 1        | 8.33%   |
| ASRock Z87M         | 1        | 8.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 4        | 33.33%  |
| 2021 | 2        | 16.67%  |
| 2015 | 2        | 16.67%  |
| 2017 | 1        | 8.33%   |
| 2012 | 1        | 8.33%   |
| 2010 | 1        | 8.33%   |
| 2007 | 1        | 8.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 12       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 12       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 4        | 30.77%  |
| 8.01-16.0  | 4        | 30.77%  |
| 3.01-4.0   | 3        | 23.08%  |
| 32.01-64.0 | 2        | 15.38%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 5        | 38.46%  |
| 2.01-3.0   | 4        | 30.77%  |
| 4.01-8.0   | 1        | 7.69%   |
| 3.01-4.0   | 1        | 7.69%   |
| 16.01-24.0 | 1        | 7.69%   |
| 0.51-1.0   | 1        | 7.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 5        | 41.67%  |
| 1      | 4        | 33.33%  |
| 6      | 1        | 8.33%   |
| 5      | 1        | 8.33%   |
| 3      | 1        | 8.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 83.33%  |
| Yes       | 2        | 16.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 9        | 75%     |
| No        | 3        | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 83.33%  |
| Yes       | 2        | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 2        | 15.38%  |
| Netherlands | 2        | 15.38%  |
| India       | 2        | 15.38%  |
| Russia      | 1        | 7.69%   |
| Romania     | 1        | 7.69%   |
| Morocco     | 1        | 7.69%   |
| Denmark     | 1        | 7.69%   |
| Czechia     | 1        | 7.69%   |
| Brazil      | 1        | 7.69%   |
| Austria     | 1        | 7.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Vienna              | 1        | 7.69%   |
| Viby J              | 1        | 7.69%   |
| Vapi                | 1        | 7.69%   |
| Uherské Hradiště | 1        | 7.69%   |
| Tangier             | 1        | 7.69%   |
| Sao Paulo           | 1        | 7.69%   |
| Newark              | 1        | 7.69%   |
| Milton              | 1        | 7.69%   |
| Krasnogorsk         | 1        | 7.69%   |
| Iasi                | 1        | 7.69%   |
| Bussum              | 1        | 7.69%   |
| Beri Khas           | 1        | 7.69%   |
| Amsterdam           | 1        | 7.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 9      | 32%     |
| WDC                 | 5        | 6      | 20%     |
| Samsung Electronics | 4        | 8      | 16%     |
| Toshiba             | 2        | 2      | 8%      |
| SanDisk             | 2        | 3      | 8%      |
| Silicon Motion      | 1        | 1      | 4%      |
| PLEXTOR             | 1        | 1      | 4%      |
| China               | 1        | 2      | 4%      |
| A-DATA Technology   | 1        | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA200 2TB              | 2        | 6.9%    |
| Seagate ST250DM000-1BD141 250GB     | 2        | 6.9%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 3.45%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 3.45%   |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 3.45%   |
| WDC WD10EZRX-00L4HB0 1TB            | 1        | 3.45%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 3.45%   |
| Silicon Motion NVMe SSD Drive 128GB | 1        | 3.45%   |
| Seagate ST9500325AS 500GB           | 1        | 3.45%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 3.45%   |
| Seagate ST500LM000-SSHD-8GB         | 1        | 3.45%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 3.45%   |
| Seagate ST3500312CS 500GB           | 1        | 3.45%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1        | 3.45%   |
| Seagate ST1000DM003-1SB10C 1TB      | 1        | 3.45%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 1        | 3.45%   |
| Sandisk NVMe SSD Drive 250GB        | 1        | 3.45%   |
| Samsung SSD 970 EVO Plus 1TB        | 1        | 3.45%   |
| Samsung SSD 860 EVO 500GB           | 1        | 3.45%   |
| Samsung SSD 860 EVO 250GB           | 1        | 3.45%   |
| Samsung SSD 850 EVO 250GB           | 1        | 3.45%   |
| Samsung SSD 840 Series 250GB        | 1        | 3.45%   |
| Samsung MZVLB1T0HBLR-000L2 1TB      | 1        | 3.45%   |
| Samsung HM500JI 500GB               | 1        | 3.45%   |
| PLEXTOR PX-512M6Pro 512GB SSD       | 1        | 3.45%   |
| China SATA SSD 256GB                | 1        | 3.45%   |
| A-DATA SX7000NP 128GB               | 1        | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 9      | 53.33%  |
| WDC                 | 4        | 5      | 26.67%  |
| Toshiba             | 2        | 2      | 13.33%  |
| Samsung Electronics | 1        | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 5      | 42.86%  |
| WDC                 | 1        | 1      | 14.29%  |
| SanDisk             | 1        | 1      | 14.29%  |
| PLEXTOR             | 1        | 1      | 14.29%  |
| China               | 1        | 2      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 17     | 52.63%  |
| SSD  | 6        | 10     | 31.58%  |
| NVMe | 3        | 6      | 15.79%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 11       | 27     | 78.57%  |
| NVMe | 3        | 6      | 21.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 9        | 17     | 56.25%  |
| 0.51-1.0   | 4        | 6      | 25%     |
| 1.01-2.0   | 3        | 4      | 18.75%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 3        | 25%     |
| 501-1000   | 3        | 25%     |
| 101-250    | 2        | 16.67%  |
| 1001-2000  | 2        | 16.67%  |
| 2001-3000  | 1        | 8.33%   |
| 51-100     | 1        | 8.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 4        | 28.57%  |
| 51-100    | 3        | 21.43%  |
| 101-250   | 2        | 14.29%  |
| 501-1000  | 2        | 14.29%  |
| 251-500   | 1        | 7.14%   |
| 1001-2000 | 1        | 7.14%   |
| 1-20      | 1        | 7.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD2003FZEX-00Z4SA0 2TB         | 1        | 1      | 12.5%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 12.5%   |
| Seagate ST250DM000-1BD141 250GB    | 1        | 1      | 12.5%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 12.5%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1        | 1      | 12.5%   |
| Samsung Electronics HM500JI 500GB  | 1        | 1      | 12.5%   |
| PLEXTOR PX-512M6Pro 512GB SSD      | 1        | 1      | 12.5%   |
| A-DATA Technology SX7000NP 128GB   | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 3      | 28.57%  |
| WDC                 | 1        | 1      | 14.29%  |
| SanDisk             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| PLEXTOR             | 1        | 1      | 14.29%  |
| A-DATA Technology   | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2        | 3      | 50%     |
| WDC                 | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 5      | 50%     |
| SSD  | 2        | 2      | 33.33%  |
| NVMe | 1        | 1      | 16.67%  |

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
| Detected | 6        | 14     | 40%     |
| Works    | 6        | 11     | 40%     |
| Malfunc  | 3        | 8      | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 8        | 53.33%  |
| AMD                 | 3        | 20%     |
| Silicon Motion      | 1        | 6.67%   |
| Sandisk             | 1        | 6.67%   |
| Samsung Electronics | 1        | 6.67%   |
| Nvidia              | 1        | 6.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5        | 29.41%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 17.65%  |
| Silicon Motion Non-Volatile memory controller                                  | 1        | 5.88%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1        | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 5.88%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 5.88%   |
| Nvidia MCP61 IDE                                                               | 1        | 5.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 5.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 5.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 5.88%   |
| AMD FCH SATA Controller D                                                      | 1        | 5.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 10       | 66.67%  |
| NVMe | 3        | 20%     |
| IDE  | 2        | 13.33%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 8        | 66.67%  |
| AMD    | 4        | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 16.67%  |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 8.33%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 8.33%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 8.33%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 8.33%   |
| Intel Core i5-4670S CPU @ 3.10GHz           | 1        | 8.33%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 8.33%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 8.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 1        | 8.33%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 8.33%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+  | 1        | 8.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Pentium    | 2        | 16.67%  |
| Intel Core i5    | 2        | 16.67%  |
| Intel Core i3    | 2        | 16.67%  |
| Intel Xeon       | 1        | 8.33%   |
| Intel Core 2 Duo | 1        | 8.33%   |
| AMD Ryzen 9      | 1        | 8.33%   |
| AMD Ryzen 7      | 1        | 8.33%   |
| AMD Ryzen 3      | 1        | 8.33%   |
| AMD Athlon 64 X2 | 1        | 8.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 6        | 50%     |
| 4      | 4        | 33.33%  |
| 12     | 1        | 8.33%   |
| 8      | 1        | 8.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 66.67%  |
| 2      | 4        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 12       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 66.67%  |
| 0x306c3    | 1        | 8.33%   |
| 0x206a7    | 1        | 8.33%   |
| 0x1067a    | 1        | 8.33%   |
| 0x08701021 | 1        | 8.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 5        | 41.67%  |
| Zen 2       | 2        | 16.67%  |
| Zen         | 1        | 8.33%   |
| SandyBridge | 1        | 8.33%   |
| Penryn      | 1        | 8.33%   |
| KabyLake    | 1        | 8.33%   |
| K8 Hammer   | 1        | 8.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 8        | 50%     |
| Nvidia | 5        | 31.25%  |
| AMD    | 3        | 18.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 12.5%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 12.5%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 6.25%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 6.25%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 6.25%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 6.25%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 6.25%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 6.25%   |
| Intel HD Graphics 630                                                       | 1        | 6.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 6.25%   |
| AMD Renoir                                                                  | 1        | 6.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 6.25%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 6.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 5        | 41.67%  |
| 1 x Intel  | 4        | 33.33%  |
| 1 x AMD    | 3        | 25%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 69.23%  |
| Proprietary | 3        | 23.08%  |
| Unknown     | 1        | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 61.54%  |
| 1.01-2.0   | 2        | 15.38%  |
| 7.01-8.0   | 1        | 7.69%   |
| 3.01-4.0   | 1        | 7.69%   |
| 0.01-0.5   | 1        | 7.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 1        | 8.33%   |
| Toshiba             | 1        | 8.33%   |
| STD                 | 1        | 8.33%   |
| Samsung Electronics | 1        | 8.33%   |
| Philips             | 1        | 8.33%   |
| NEC Computers       | 1        | 8.33%   |
| Lenovo              | 1        | 8.33%   |
| Dell                | 1        | 8.33%   |
| BenQ                | 1        | 8.33%   |
| Ativa               | 1        | 8.33%   |
| AOC                 | 1        | 8.33%   |
| Acer                | 1        | 8.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor SAMSUNG 3840x1080                                | 1        | 7.69%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                     | 1        | 7.69%   |
| STD Monitor STD0001 1920x1080                                        | 1        | 7.69%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch | 1        | 7.69%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch             | 1        | 7.69%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch          | 1        | 7.69%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch           | 1        | 7.69%   |
| Lenovo L200pwD LEN1156 1680x1050 433x271mm 20.1-inch                 | 1        | 7.69%   |
| Dell LCD Monitor P2417H                                              | 1        | 7.69%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                    | 1        | 7.69%   |
| Ativa AT22HZR ATV0100 1920x1080 497x292mm 22.7-inch                  | 1        | 7.69%   |
| AOC LCD Monitor 2217 1680x1050                                       | 1        | 7.69%   |
| Acer X223W ACR0011 1680x1050 473x296mm 22.0-inch                     | 1        | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 46.15%  |
| 1680x1050 (WSXGA+) | 4        | 30.77%  |
| 3840x1080          | 1        | 7.69%   |
| 1920x1200 (WUXGA)  | 1        | 7.69%   |
| Unknown            | 1        | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 22      | 3        | 25%     |
| 27      | 2        | 16.67%  |
| 24      | 2        | 16.67%  |
| Unknown | 2        | 16.67%  |
| 32      | 1        | 8.33%   |
| 23      | 1        | 8.33%   |
| 20      | 1        | 8.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 5        | 41.67%  |
| 401-500     | 4        | 33.33%  |
| Unknown     | 2        | 16.67%  |
| 701-800     | 1        | 8.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 5        | 45.45%  |
| 16/10   | 4        | 36.36%  |
| Unknown | 2        | 18.18%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 4        | 33.33%  |
| 301-350        | 2        | 16.67%  |
| 251-300        | 2        | 16.67%  |
| Unknown        | 2        | 16.67%  |
| 351-500        | 1        | 8.33%   |
| 151-200        | 1        | 8.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 8        | 80%     |
| Unknown | 2        | 20%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 61.54%  |
| 2     | 3        | 23.08%  |
| 0     | 2        | 15.38%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 10       | 35.71%  |
| Intel                         | 5        | 17.86%  |
| MediaTek                      | 2        | 7.14%   |
| TP-Link                       | 1        | 3.57%   |
| Samsung Electronics           | 1        | 3.57%   |
| Qualcomm Atheros              | 1        | 3.57%   |
| OnePlus Technology (Shenzhen) | 1        | 3.57%   |
| Nvidia                        | 1        | 3.57%   |
| Microsoft                     | 1        | 3.57%   |
| ICS Advent                    | 1        | 3.57%   |
| Gemtek                        | 1        | 3.57%   |
| D-Link System                 | 1        | 3.57%   |
| Broadcom                      | 1        | 3.57%   |
| ASUSTek Computer              | 1        | 3.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 7        | 24.14%  |
| Realtek 802.11n                                                      | 3        | 10.34%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1        | 3.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 1        | 3.45%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1        | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 3.45%   |
| OnePlus (Shenzhen) AC2001                                            | 1        | 3.45%   |
| Nvidia MCP61 Ethernet                                                | 1        | 3.45%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 3.45%   |
| MediaTek vivo                                                        | 1        | 3.45%   |
| MediaTek Infinix HOT 10 Play                                         | 1        | 3.45%   |
| Intel Wi-Fi 6 AX200                                                  | 1        | 3.45%   |
| Intel I211 Gigabit Network Connection                                | 1        | 3.45%   |
| Intel Ethernet Connection I217-V                                     | 1        | 3.45%   |
| Intel Ethernet Connection I217-LM                                    | 1        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 1        | 3.45%   |
| ICS Advent USB 10/100 LAN                                            | 1        | 3.45%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                    | 1        | 3.45%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 3.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 3.45%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]   | 1        | 3.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 3        | 27.27%  |
| TP-Link               | 1        | 9.09%   |
| Qualcomm Atheros      | 1        | 9.09%   |
| Microsoft             | 1        | 9.09%   |
| Intel                 | 1        | 9.09%   |
| Gemtek                | 1        | 9.09%   |
| D-Link System         | 1        | 9.09%   |
| Broadcom              | 1        | 9.09%   |
| ASUSTek Computer      | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek 802.11n                                                      | 3        | 27.27%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1        | 9.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 9.09%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 9.09%   |
| Intel Wi-Fi 6 AX200                                                  | 1        | 9.09%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                    | 1        | 9.09%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 9.09%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 9.09%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]   | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 47.06%  |
| Intel                 | 4        | 23.53%  |
| MediaTek              | 2        | 11.76%  |
| Samsung Electronics   | 1        | 5.88%   |
| Nvidia                | 1        | 5.88%   |
| ICS Advent            | 1        | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7        | 41.18%  |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 5.88%   |
| Nvidia MCP61 Ethernet                                             | 1        | 5.88%   |
| MediaTek vivo                                                     | 1        | 5.88%   |
| MediaTek Infinix HOT 10 Play                                      | 1        | 5.88%   |
| Intel I211 Gigabit Network Connection                             | 1        | 5.88%   |
| Intel Ethernet Connection I217-V                                  | 1        | 5.88%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 5.88%   |
| ICS Advent USB 10/100 LAN                                         | 1        | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 54.55%  |
| WiFi     | 9        | 40.91%  |
| Unknown  | 1        | 4.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 9        | 69.23%  |
| WiFi     | 4        | 30.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 66.67%  |
| 2     | 4        | 33.33%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 83.33%  |
| Yes  | 2        | 16.67%  |

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


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 8        | 47.06%  |
| Nvidia | 5        | 29.41%  |
| AMD    | 4        | 23.53%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 5        | 20%     |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 5        | 20%     |
| AMD Family 17h/19h HD Audio Controller                                  | 2        | 8%      |
| Nvidia MCP61 High Definition Audio                                      | 1        | 4%      |
| Nvidia GP107GL High Definition Audio Controller                         | 1        | 4%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 1        | 4%      |
| Nvidia GK208 HDMI/DP Audio Controller                                   | 1        | 4%      |
| Nvidia GF106 High Definition Audio Controller                           | 1        | 4%      |
| Intel USB PnP Sound Device                                              | 1        | 4%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1        | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 1        | 4%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 1        | 4%      |
| AMD Starship/Matisse HD Audio Controller                                | 1        | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                      | 1        | 4%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1        | 4%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 1        | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 4        | 44.44%  |
| SK Hynix            | 1        | 11.11%  |
| Samsung Electronics | 1        | 11.11%  |
| Kingston            | 1        | 11.11%  |
| G.Skill             | 1        | 11.11%  |
| Crucial             | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 11.11%  |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                 | 1        | 11.11%  |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 11.11%  |
| Unknown RAM Module 2GB DIMM                               | 1        | 11.11%  |
| SK Hynix RAM HYMP512U64CP8-Y5 1GB DIMM                    | 1        | 11.11%  |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 11.11%  |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 1867MT/s    | 1        | 11.11%  |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s | 1        | 11.11%  |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s  | 1        | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 4        | 57.14%  |
| SDRAM   | 1        | 14.29%  |
| DDR4    | 1        | 14.29%  |
| Unknown | 1        | 14.29%  |

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
| 8192  | 2        | 25%     |
| 4096  | 2        | 25%     |
| 2048  | 2        | 25%     |
| 16384 | 1        | 12.5%   |
| 1024  | 1        | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 2        | 28.57%  |
| Unknown | 2        | 28.57%  |
| 3600    | 1        | 14.29%  |
| 2133    | 1        | 14.29%  |
| 1067    | 1        | 14.29%  |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Teslong Camera      | 1        | 33.33%  |
| IMC Networks        | 1        | 33.33%  |
| Creative Technology | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Teslong Camera                      | 1        | 33.33%  |
| IMC Networks XHC Camera             | 1        | 33.33%  |
| Creative Live! Cam Sync HD [VF0770] | 1        | 33.33%  |

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
| 0     | 7        | 53.85%  |
| 1     | 5        | 38.46%  |
| 2     | 1        | 7.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 3        | 42.86%  |
| Graphics card            | 2        | 28.57%  |
| Multimedia controller    | 1        | 14.29%  |
| Communication controller | 1        | 14.29%  |

