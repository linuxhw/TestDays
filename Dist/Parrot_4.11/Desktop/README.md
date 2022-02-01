Parrot 4.11 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for Parrot 4.11.

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

| Vendor    | Model                   | Probe                                                      | Date         |
|-----------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | ROG STRIX B450-F GAMING | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| ASUSTek   | M5A99X EVO              | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Alienware | 0PGRP5 A02              | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock    | Z87 Killer              | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Acer      | Aspire TC-780           | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Dell      | 0T2HR0 A00              | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek   | P8H67-M PRO             | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte  | A320M-S2H-CF            | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Gigabyte  | A320M-S2H-CF            | [6647d75cdb](https://linux-hardware.org/?probe=6647d75cdb) | Aug 20, 2021 |
| Gigabyte  | A320M-S2H-CF            | [5363cc3efd](https://linux-hardware.org/?probe=5363cc3efd) | Aug 12, 2021 |
| Gigabyte  | A320M-S2H-CF            | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| ZOTAC     | Unknown                 | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC     | Unknown                 | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| HP        | 1850                    | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell      | 0T10XW A02              | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| HP        | 1850                    | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| Dell      | 0C1R19 A02              | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| ASUSTek   | PRIME X399-A            | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer      | Predator PO3-600 V:1.1  | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| ASUSTek   | M5A78L-M/USB3           | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.10.0-6parrot1-amd64 | 4        | 26.67%  |
| 5.14.0-9parrot1-amd64 | 3        | 20%     |
| 5.10.0-8parrot1-amd64 | 3        | 20%     |
| 5.10.0-3parrot1-amd64 | 2        | 13.33%  |
| 5.7.0-2parrot2-amd64  | 1        | 6.67%   |
| 5.14.0-2parrot1-amd64 | 1        | 6.67%   |
| 5.10.0-5parrot1-amd64 | 1        | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 10       | 66.67%  |
| 5.14.0  | 4        | 26.67%  |
| 5.7.0   | 1        | 6.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 66.67%  |
| 5.14    | 4        | 26.67%  |
| 5.7     | 1        | 6.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 15       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 7        | 43.75%  |
| KDE5    | 5        | 31.25%  |
| XFCE    | 2        | 12.5%   |
| KDE     | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 15       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 7        | 43.75%  |
| Unknown | 6        | 37.5%   |
| TDM     | 3        | 18.75%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 9        | 60%     |
| ru_UA | 1        | 6.67%   |
| ru_RU | 1        | 6.67%   |
| pt_BR | 1        | 6.67%   |
| pl_PL | 1        | 6.67%   |
| fr_FR | 1        | 6.67%   |
| en_AU | 1        | 6.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 10       | 62.5%   |
| EFI  | 6        | 37.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 13       | 86.67%  |
| Ext4  | 2        | 13.33%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 8        | 50%     |
| Unknown | 7        | 43.75%  |
| MBR     | 1        | 6.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 81.25%  |
| Yes       | 3        | 18.75%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 53.33%  |
| Yes       | 7        | 46.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 5        | 33.33%  |
| Dell                | 3        | 20%     |
| Acer                | 2        | 13.33%  |
| ZOTAC               | 1        | 6.67%   |
| Hewlett-Packard     | 1        | 6.67%   |
| Gigabyte Technology | 1        | 6.67%   |
| ASRock              | 1        | 6.67%   |
| Alienware           | 1        | 6.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| HP Compaq Pro 6305 MT        | 1        | 6.67%   |
| Gigabyte A320M-S2H           | 1        | 6.67%   |
| Dell XPS 8930                | 1        | 6.67%   |
| Dell OptiPlex 7070           | 1        | 6.67%   |
| Dell OptiPlex 3010           | 1        | 6.67%   |
| ASUS ROG STRIX B450-F GAMING | 1        | 6.67%   |
| ASUS PRIME X399-A            | 1        | 6.67%   |
| ASUS P8H67-M PRO             | 1        | 6.67%   |
| ASUS M5A99X EVO              | 1        | 6.67%   |
| ASUS M5A78L-M/USB3           | 1        | 6.67%   |
| ASRock Z87 Killer            | 1        | 6.67%   |
| Alienware X51 R2             | 1        | 6.67%   |
| Acer Predator PO3-600        | 1        | 6.67%   |
| Acer Aspire TC-780           | 1        | 6.67%   |
| Unknown                      | 1        | 6.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 2        | 13.33%  |
| HP Compaq          | 1        | 6.67%   |
| Gigabyte A320M-S2H | 1        | 6.67%   |
| Dell XPS           | 1        | 6.67%   |
| ASUS ROG           | 1        | 6.67%   |
| ASUS PRIME         | 1        | 6.67%   |
| ASUS P8H67-M       | 1        | 6.67%   |
| ASUS M5A99X        | 1        | 6.67%   |
| ASUS M5A78L-M      | 1        | 6.67%   |
| ASRock Z87         | 1        | 6.67%   |
| Alienware X51      | 1        | 6.67%   |
| Acer Predator      | 1        | 6.67%   |
| Acer Aspire        | 1        | 6.67%   |
| Unknown            | 1        | 6.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 3        | 20%     |
| 2019 | 2        | 13.33%  |
| 2017 | 2        | 13.33%  |
| 2016 | 2        | 13.33%  |
| 2013 | 2        | 13.33%  |
| 2020 | 1        | 6.67%   |
| 2018 | 1        | 6.67%   |
| 2014 | 1        | 6.67%   |
| 2012 | 1        | 6.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 15       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 15       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 5        | 33.33%  |
| 4.01-8.0   | 4        | 26.67%  |
| 8.01-16.0  | 3        | 20%     |
| 32.01-64.0 | 1        | 6.67%   |
| 3.01-4.0   | 1        | 6.67%   |
| 24.01-32.0 | 1        | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 6        | 40%     |
| 4.01-8.0  | 3        | 20%     |
| 2.01-3.0  | 3        | 20%     |
| 3.01-4.0  | 1        | 6.67%   |
| 8.01-16.0 | 1        | 6.67%   |
| 0.51-1.0  | 1        | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 6        | 40%     |
| 3      | 4        | 26.67%  |
| 4      | 2        | 13.33%  |
| 1      | 2        | 13.33%  |
| 5      | 1        | 6.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 75%     |
| Yes       | 4        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 15       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 75%     |
| No        | 4        | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 53.33%  |
| Yes       | 7        | 46.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 8        | 53.33%  |
| Ukraine   | 1        | 6.67%   |
| Russia    | 1        | 6.67%   |
| Poland    | 1        | 6.67%   |
| Germany   | 1        | 6.67%   |
| France    | 1        | 6.67%   |
| Brazil    | 1        | 6.67%   |
| Australia | 1        | 6.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| Eugene      | 2        | 12.5%   |
| Warsaw      | 1        | 6.25%   |
| Ternopil    | 1        | 6.25%   |
| S??o Paulo  | 1        | 6.25%   |
| Saint Paul  | 1        | 6.25%   |
| Portsmouth  | 1        | 6.25%   |
| Orange Park | 1        | 6.25%   |
| Offenbach   | 1        | 6.25%   |
| Melbourne   | 1        | 6.25%   |
| Lyon        | 1        | 6.25%   |
| Los Angeles | 1        | 6.25%   |
| Lafayette   | 1        | 6.25%   |
| Khabarovsk  | 1        | 6.25%   |
| Dudenhofen  | 1        | 6.25%   |
| Brunswick   | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 14     | 23.53%  |
| Samsung Electronics | 4        | 5      | 11.76%  |
| WDC                 | 3        | 4      | 8.82%   |
| Crucial             | 3        | 3      | 8.82%   |
| Unknown             | 2        | 2      | 5.88%   |
| Toshiba             | 2        | 2      | 5.88%   |
| SK Hynix            | 2        | 2      | 5.88%   |
| SanDisk             | 2        | 2      | 5.88%   |
| Hitachi             | 2        | 3      | 5.88%   |
| SPCC                | 1        | 1      | 2.94%   |
| Phison              | 1        | 1      | 2.94%   |
| LITEONIT            | 1        | 1      | 2.94%   |
| Intenso             | 1        | 1      | 2.94%   |
| FORESEE             | 1        | 1      | 2.94%   |
| China               | 1        | 2      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown SD/MMC/MS PRO 128GB         | 2        | 5%      |
| Seagate Expansion 1TB               | 2        | 5%      |
| WDC WDBNCE0010PNC 1TB SSD           | 1        | 2.5%    |
| WDC WD3200LPVX-60V0TT0 320GB        | 1        | 2.5%    |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 2.5%    |
| Toshiba MK2552GSX 250GB             | 1        | 2.5%    |
| Toshiba DT01ACA100 1TB              | 1        | 2.5%    |
| SPCC Solid State Disk 120GB         | 1        | 2.5%    |
| SK Hynix PC601 NVMe 256GB           | 1        | 2.5%    |
| SK Hynix NVMe SSD Drive 256GB       | 1        | 2.5%    |
| Seagate ST9250410AS 250GB           | 1        | 2.5%    |
| Seagate ST500NM0011 500GB           | 1        | 2.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 2.5%    |
| Seagate ST500DM002-1SB10A 500GB     | 1        | 2.5%    |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 2.5%    |
| Seagate ST3500413AS 500GB           | 1        | 2.5%    |
| Seagate ST31000528AS 1TB            | 1        | 2.5%    |
| Seagate ST250DM000-1BD141 250GB     | 1        | 2.5%    |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1        | 2.5%    |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 2.5%    |
| SanDisk SSD PLUS 1000GB             | 1        | 2.5%    |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 1        | 2.5%    |
| Samsung SSD SM841N 2.5 7mm 256GB    | 1        | 2.5%    |
| Samsung SSD 970 EVO 500GB           | 1        | 2.5%    |
| Samsung SSD 860 EVO 250GB           | 1        | 2.5%    |
| Samsung SSD 840 Series 250GB        | 1        | 2.5%    |
| Samsung NVMe SSD Drive 1TB          | 1        | 2.5%    |
| Phison NVMe SSD Drive 1TB           | 1        | 2.5%    |
| LITEONIT LCS-128M6S 2.5 7mm 128GB   | 1        | 2.5%    |
| Intenso SSD SATAIII 512GB           | 1        | 2.5%    |
| Hitachi HTS547564A9E384 640GB       | 1        | 2.5%    |
| Hitachi HTS545050B9A300 500GB       | 1        | 2.5%    |
| Hitachi HDT721010SLA360 1TB         | 1        | 2.5%    |
| FORESEE 60GB SSD                    | 1        | 2.5%    |
| Crucial CT256MX100SSD1 256GB        | 1        | 2.5%    |
| Crucial CT240BX300SSD1 240GB        | 1        | 2.5%    |
| Crucial CT1000BX500SSD1 1TB         | 1        | 2.5%    |
| China SATA SSD 256GB                | 1        | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 8        | 14     | 50%     |
| WDC     | 2        | 3      | 12.5%   |
| Unknown | 2        | 2      | 12.5%   |
| Toshiba | 2        | 2      | 12.5%   |
| Hitachi | 2        | 3      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 3        | 3      | 23.08%  |
| SanDisk             | 2        | 2      | 15.38%  |
| Samsung Electronics | 2        | 3      | 15.38%  |
| WDC                 | 1        | 1      | 7.69%   |
| SPCC                | 1        | 1      | 7.69%   |
| LITEONIT            | 1        | 1      | 7.69%   |
| Intenso             | 1        | 1      | 7.69%   |
| FORESEE             | 1        | 1      | 7.69%   |
| China               | 1        | 2      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 24     | 44.44%  |
| SSD  | 10       | 15     | 37.04%  |
| NVMe | 5        | 5      | 18.52%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 13       | 35     | 61.9%   |
| NVMe | 5        | 5      | 23.81%  |
| SAS  | 3        | 4      | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 24     | 50%     |
| 0.51-1.0   | 10       | 13     | 41.67%  |
| 3.01-4.0   | 1        | 1      | 4.17%   |
| 1.01-2.0   | 1        | 1      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 4        | 23.53%  |
| 101-250    | 3        | 17.65%  |
| 1001-2000  | 3        | 17.65%  |
| 2001-3000  | 2        | 11.76%  |
| 501-1000   | 2        | 11.76%  |
| Unknown    | 2        | 11.76%  |
| 51-100     | 1        | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 101-250  | 5        | 29.41%  |
| 21-50    | 4        | 23.53%  |
| 251-500  | 2        | 11.76%  |
| 51-100   | 2        | 11.76%  |
| Unknown  | 2        | 11.76%  |
| 1-20     | 1        | 5.88%   |
| 501-1000 | 1        | 5.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST9250410AS 250GB          | 1        | 1      | 14.29%  |
| Seagate ST500NM0011 500GB          | 1        | 1      | 14.29%  |
| Seagate ST3500413AS 500GB          | 1        | 1      | 14.29%  |
| Seagate ST31000528AS 1TB           | 1        | 1      | 14.29%  |
| Seagate ST1000DM010-2EP102 1TB     | 1        | 1      | 14.29%  |
| SanDisk SSD PLUS 1000GB            | 1        | 1      | 14.29%  |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 66.67%  |
| SanDisk | 2        | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 5      | 66.67%  |
| SSD  | 2        | 2      | 33.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Intenso SSD SATAIII 512GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Intenso | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 9        | 21     | 36%     |
| Works    | 9        | 15     | 36%     |
| Malfunc  | 6        | 7      | 24%     |
| Failed   | 1        | 1      | 4%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 9        | 40.91%  |
| AMD                 | 6        | 27.27%  |
| SK Hynix            | 2        | 9.09%   |
| Samsung Electronics | 2        | 9.09%   |
| VIA Technologies    | 1        | 4.55%   |
| Phison Electronics  | 1        | 4.55%   |
| JMicron Technology  | 1        | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 11.54%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 7.69%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 7.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 7.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 7.69%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 3.85%   |
| SK Hynix Non-Volatile memory controller                                                 | 1        | 3.85%   |
| SK Hynix BC511                                                                          | 1        | 3.85%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 3.85%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 3.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 3.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 3.85%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 3.85%   |
| AMD FCH SATA Controller D                                                               | 1        | 3.85%   |
| AMD FCH RAID Controller                                                                 | 1        | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 52.38%  |
| NVMe | 5        | 23.81%  |
| RAID | 3        | 14.29%  |
| IDE  | 2        | 9.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 60%     |
| AMD    | 6        | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz            | 1        | 6.67%   |
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1        | 6.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 6.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 6.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 6.67%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1        | 6.67%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 6.67%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 6.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 6.67%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 6.67%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 6.67%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 6.67%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 6.67%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 6.67%   |
| AMD A4-5300B APU with Radeon HD Graphics       | 1        | 6.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 4        | 26.67%  |
| Intel Core i7          | 3        | 20%     |
| AMD FX                 | 2        | 13.33%  |
| Intel Xeon             | 1        | 6.67%   |
| Intel Core M           | 1        | 6.67%   |
| AMD Ryzen Threadripper | 1        | 6.67%   |
| AMD Ryzen 5            | 1        | 6.67%   |
| AMD Ryzen 3            | 1        | 6.67%   |
| AMD A4                 | 1        | 6.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 46.67%  |
| 6      | 4        | 26.67%  |
| 12     | 1        | 6.67%   |
| 3      | 1        | 6.67%   |
| 2      | 1        | 6.67%   |
| 1      | 1        | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 66.67%  |
| 1      | 5        | 33.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 15       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 43.75%  |
| 0x06000852 | 2        | 12.5%   |
| 0x906ed    | 1        | 6.25%   |
| 0x906e9    | 1        | 6.25%   |
| 0x306c3    | 1        | 6.25%   |
| 0x306a9    | 1        | 6.25%   |
| 0x206a7    | 1        | 6.25%   |
| 0x0a201016 | 1        | 6.25%   |
| 0x0600111f | 1        | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 4        | 26.67%  |
| Piledriver  | 3        | 20%     |
| Zen         | 2        | 13.33%  |
| Haswell     | 2        | 13.33%  |
| Zen 3       | 1        | 6.67%   |
| SandyBridge | 1        | 6.67%   |
| IvyBridge   | 1        | 6.67%   |
| Broadwell   | 1        | 6.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 7        | 38.89%  |
| AMD    | 6        | 33.33%  |
| Intel  | 5        | 27.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 11.11%  |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 5.56%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 5.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 5.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 5.56%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 5.56%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 5.56%   |
| Nvidia G86 [GeForce 8300 GS]                                                | 1        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 5.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 5.56%   |
| Intel HD Graphics 5300                                                      | 1        | 5.56%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 5.56%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 5.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 5.56%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 5.56%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 5.56%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 6        | 40%     |
| 1 x AMD      | 4        | 26.67%  |
| 1 x Intel    | 3        | 20%     |
| Intel + AMD  | 1        | 6.67%   |
| AMD + Nvidia | 1        | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 60%     |
| Proprietary | 6        | 40%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 37.5%   |
| 3.01-4.0   | 3        | 18.75%  |
| 1.01-2.0   | 3        | 18.75%  |
| 7.01-8.0   | 2        | 12.5%   |
| 0.51-1.0   | 1        | 6.25%   |
| 0.01-0.5   | 1        | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Dell            | 3        | 16.67%  |
| Hewlett-Packard | 2        | 11.11%  |
| Goldstar        | 2        | 11.11%  |
| AOC             | 2        | 11.11%  |
| Vizio           | 1        | 5.56%   |
| Toshiba         | 1        | 5.56%   |
| Sony            | 1        | 5.56%   |
| Sceptre         | 1        | 5.56%   |
| Philips         | 1        | 5.56%   |
| NEC Computers   | 1        | 5.56%   |
| Insignia        | 1        | 5.56%   |
| AUS             | 1        | 5.56%   |
| Acer            | 1        | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Vizio M320NV VIZ0070 1920x1080 700x390mm 31.5-inch          | 1        | 5.56%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch            | 1        | 5.56%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch         | 1        | 5.56%   |
| Sceptre LCD Monitor P30 2560x1080                           | 1        | 5.56%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch     | 1        | 5.56%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch | 1        | 5.56%   |
| Insignia NS-L32Q09-10A BBY3210 1360x768 697x392mm 31.5-inch | 1        | 5.56%   |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch | 1        | 5.56%   |
| Hewlett-Packard P224 HPN361C 1920x1080 480x270mm 21.7-inch  | 1        | 5.56%   |
| Goldstar HDR WFHD GSM7749 2560x1080 798x334mm 34.1-inch     | 1        | 5.56%   |
| Goldstar 24GM79G GSM5B39 1920x1080 531x298mm 24.0-inch      | 1        | 5.56%   |
| Dell SE2417HGX DELD0F7 1920x1080 521x293mm 23.5-inch        | 1        | 5.56%   |
| Dell S2419H DELD0D2 1920x1080 527x296mm 23.8-inch           | 1        | 5.56%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch           | 1        | 5.56%   |
| AUS LCD Monitor VG259 1920x1080                             | 1        | 5.56%   |
| AOC LCD Monitor 2217 1680x1050                              | 1        | 5.56%   |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch               | 1        | 5.56%   |
| Acer VG240Y S ACR0750 1920x1080 530x300mm 24.0-inch         | 1        | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 9        | 52.94%  |
| 2560x1080          | 2        | 11.76%  |
| 1680x1050 (WSXGA+) | 2        | 11.76%  |
| 1920x1200 (WUXGA)  | 1        | 5.88%   |
| 1440x900 (WXGA+)   | 1        | 5.88%   |
| 1360x768           | 1        | 5.88%   |
| 1280x1024 (SXGA)   | 1        | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 27.78%  |
| Unknown | 3        | 16.67%  |
| 23      | 2        | 11.11%  |
| 42      | 1        | 5.56%   |
| 34      | 1        | 5.56%   |
| 32      | 1        | 5.56%   |
| 31      | 1        | 5.56%   |
| 27      | 1        | 5.56%   |
| 22      | 1        | 5.56%   |
| 19      | 1        | 5.56%   |
| 17      | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 41.18%  |
| Unknown     | 3        | 17.65%  |
| 701-800     | 2        | 11.76%  |
| 401-500     | 2        | 11.76%  |
| 601-700     | 1        | 5.88%   |
| 301-350     | 1        | 5.88%   |
| 901-1000    | 1        | 5.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 8        | 50%     |
| 16/10   | 3        | 18.75%  |
| Unknown | 3        | 18.75%  |
| 5/4     | 1        | 6.25%   |
| 21/9    | 1        | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 35.29%  |
| 351-500        | 3        | 17.65%  |
| Unknown        | 3        | 17.65%  |
| 301-350        | 1        | 5.88%   |
| 251-300        | 1        | 5.88%   |
| 151-200        | 1        | 5.88%   |
| 141-150        | 1        | 5.88%   |
| 501-1000       | 1        | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 71.43%  |
| Unknown | 3        | 21.43%  |
| 1-50    | 1        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 60%     |
| 2     | 5        | 33.33%  |
| 0     | 1        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 11       | 42.31%  |
| Intel                           | 5        | 19.23%  |
| Qualcomm Atheros Communications | 2        | 7.69%   |
| Qualcomm Atheros                | 2        | 7.69%   |
| Broadcom Limited                | 2        | 7.69%   |
| Ralink Technology               | 1        | 3.85%   |
| Microsoft                       | 1        | 3.85%   |
| D-Link System                   | 1        | 3.85%   |
| Broadcom                        | 1        | 3.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 9        | 32.14%  |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 7.14%   |
| Intel I211 Gigabit Network Connection                                | 2        | 7.14%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 3.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1        | 3.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 3.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 3.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1        | 3.57%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 3.57%   |
| Intel Wireless 7265                                                  | 1        | 3.57%   |
| Intel Wireless 3160                                                  | 1        | 3.57%   |
| Intel Ethernet Connection (7) I219-LM                                | 1        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 3.57%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 3.57%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe             | 1        | 3.57%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1        | 3.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 3.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 25%     |
| Qualcomm Atheros Communications | 2        | 16.67%  |
| Realtek Semiconductor           | 1        | 8.33%   |
| Ralink Technology               | 1        | 8.33%   |
| Qualcomm Atheros                | 1        | 8.33%   |
| Microsoft                       | 1        | 8.33%   |
| D-Link System                   | 1        | 8.33%   |
| Broadcom Limited                | 1        | 8.33%   |
| Broadcom                        | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 16.67%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 8.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 8.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 8.33%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 8.33%   |
| Intel Wireless 7265                                                  | 1        | 8.33%   |
| Intel Wireless 3160                                                  | 1        | 8.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 8.33%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 8.33%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1        | 8.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 62.5%   |
| Intel                 | 3        | 18.75%  |
| Qualcomm Atheros      | 2        | 12.5%   |
| Broadcom Limited      | 1        | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 56.25%  |
| Intel I211 Gigabit Network Connection                             | 2        | 12.5%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 6.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 6.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 6.25%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 6.25%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 55.56%  |
| WiFi     | 12       | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 63.16%  |
| WiFi     | 7        | 36.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 53.33%  |
| 2     | 6        | 40%     |
| 3     | 1        | 6.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 11       | 73.33%  |
| Yes  | 4        | 26.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 42.86%  |
| Realtek Semiconductor           | 1        | 14.29%  |
| Qualcomm Atheros Communications | 1        | 14.29%  |
| Dell                            | 1        | 14.29%  |
| Cambridge Silicon Radio         | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 2        | 28.57%  |
| Realtek Bluetooth Radio                             | 1        | 14.29%  |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 14.29%  |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| AMD                 | 10       | 38.46%  |
| Intel               | 9        | 34.62%  |
| Nvidia              | 6        | 23.08%  |
| C-Media Electronics | 1        | 3.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH cAVS                                                        | 2        | 6.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 6.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 6.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 6.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 3.33%   |
| Nvidia TU106 High Definition Audio Controller                                     | 1        | 3.33%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 3.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 3.33%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 3.33%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 3.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 3.33%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 3.33%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 3.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 3.33%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1        | 3.33%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 3.33%   |
| AMD Starship/Matisse HD Audio Controller                                          | 1        | 3.33%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 3.33%   |
| AMD FCH Azalia Controller                                                         | 1        | 3.33%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 1        | 3.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 3.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 3.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 2        | 22.22%  |
| Crucial          | 2        | 22.22%  |
| Corsair          | 2        | 22.22%  |
| S                | 1        | 11.11%  |
| Nanya Technology | 1        | 11.11%  |
| Kingston         | 1        | 11.11%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 10%     |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 10%     |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 10%     |
| S RAM Module 2GB DIMM DDR3 1600MT/s                      | 1        | 10%     |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s       | 1        | 10%     |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s      | 1        | 10%     |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s    | 1        | 10%     |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1        | 10%     |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s      | 1        | 10%     |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 1        | 10%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 5        | 55.56%  |
| DDR4    | 3        | 33.33%  |
| Unknown | 1        | 11.11%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 9        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 6        | 60%     |
| 4096 | 3        | 30%     |
| 2048 | 1        | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 55.56%  |
| 3600  | 1        | 11.11%  |
| 2666  | 1        | 11.11%  |
| 2400  | 1        | 11.11%  |
| 1333  | 1        | 11.11%  |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech HD Webcam C615 | 1        | 100%    |

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
| 0     | 13       | 86.67%  |
| 1     | 2        | 13.33%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Storage/raid | 1        | 50%     |
| Net/wireless | 1        | 50%     |

