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

| Vendor    | Model                  | Probe                                                      | Date         |
|-----------|------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | M5A99X EVO             | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Alienware | 0PGRP5 A02             | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock    | Z87 Killer             | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Acer      | Aspire TC-780          | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Dell      | 0T2HR0 A00             | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek   | P8H67-M PRO            | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte  | A320M-S2H-CF           | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Gigabyte  | A320M-S2H-CF           | [6647d75cdb](https://linux-hardware.org/?probe=6647d75cdb) | Aug 20, 2021 |
| Gigabyte  | A320M-S2H-CF           | [5363cc3efd](https://linux-hardware.org/?probe=5363cc3efd) | Aug 12, 2021 |
| Gigabyte  | A320M-S2H-CF           | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| ZOTAC     | Unknown                | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC     | Unknown                | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| HP        | 1850                   | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell      | 0T10XW A02             | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| HP        | 1850                   | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| Dell      | 0C1R19 A02             | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| ASUSTek   | PRIME X399-A           | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer      | Predator PO3-600 V:1.1 | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| ASUSTek   | M5A78L-M/USB3          | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Desktops | Percent |
|-----------------------|----------|---------|
| 5.10.0-6parrot1-amd64 | 4        | 28.57%  |
| 5.10.0-8parrot1-amd64 | 3        | 21.43%  |
| 5.14.0-9parrot1-amd64 | 2        | 14.29%  |
| 5.10.0-3parrot1-amd64 | 2        | 14.29%  |
| 5.7.0-2parrot2-amd64  | 1        | 7.14%   |
| 5.14.0-2parrot1-amd64 | 1        | 7.14%   |
| 5.10.0-5parrot1-amd64 | 1        | 7.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 10       | 71.43%  |
| 5.14.0  | 3        | 21.43%  |
| 5.7.0   | 1        | 7.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 10       | 71.43%  |
| 5.14    | 3        | 21.43%  |
| 5.7     | 1        | 7.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 14       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 6        | 40%     |
| KDE5    | 5        | 33.33%  |
| XFCE    | 2        | 13.33%  |
| KDE     | 1        | 6.67%   |
| Unknown | 1        | 6.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 14       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 6        | 40%     |
| Unknown | 6        | 40%     |
| TDM     | 3        | 20%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 8        | 57.14%  |
| ru_UA | 1        | 7.14%   |
| ru_RU | 1        | 7.14%   |
| pt_BR | 1        | 7.14%   |
| pl_PL | 1        | 7.14%   |
| fr_FR | 1        | 7.14%   |
| en_AU | 1        | 7.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 10       | 66.67%  |
| EFI  | 5        | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Btrfs | 12       | 85.71%  |
| Ext4  | 2        | 14.29%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 7        | 46.67%  |
| Unknown | 7        | 46.67%  |
| MBR     | 1        | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 80%     |
| Yes       | 3        | 20%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 57.14%  |
| Yes       | 6        | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4        | 28.57%  |
| Dell                | 3        | 21.43%  |
| Acer                | 2        | 14.29%  |
| ZOTAC               | 1        | 7.14%   |
| Hewlett-Packard     | 1        | 7.14%   |
| Gigabyte Technology | 1        | 7.14%   |
| ASRock              | 1        | 7.14%   |
| Alienware           | 1        | 7.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| HP Compaq Pro 6305 MT | 1        | 7.14%   |
| Gigabyte A320M-S2H    | 1        | 7.14%   |
| Dell XPS 8930         | 1        | 7.14%   |
| Dell OptiPlex 7070    | 1        | 7.14%   |
| Dell OptiPlex 3010    | 1        | 7.14%   |
| ASUS PRIME X399-A     | 1        | 7.14%   |
| ASUS P8H67-M PRO      | 1        | 7.14%   |
| ASUS M5A99X EVO       | 1        | 7.14%   |
| ASUS M5A78L-M/USB3    | 1        | 7.14%   |
| ASRock Z87 Killer     | 1        | 7.14%   |
| Alienware X51 R2      | 1        | 7.14%   |
| Acer Predator PO3-600 | 1        | 7.14%   |
| Acer Aspire TC-780    | 1        | 7.14%   |
| Unknown               | 1        | 7.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Dell OptiPlex      | 2        | 14.29%  |
| HP Compaq          | 1        | 7.14%   |
| Gigabyte A320M-S2H | 1        | 7.14%   |
| Dell XPS           | 1        | 7.14%   |
| ASUS PRIME         | 1        | 7.14%   |
| ASUS P8H67-M       | 1        | 7.14%   |
| ASUS M5A99X        | 1        | 7.14%   |
| ASUS M5A78L-M      | 1        | 7.14%   |
| ASRock Z87         | 1        | 7.14%   |
| Alienware X51      | 1        | 7.14%   |
| Acer Predator      | 1        | 7.14%   |
| Acer Aspire        | 1        | 7.14%   |
| Unknown            | 1        | 7.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 3        | 21.43%  |
| 2013 | 3        | 21.43%  |
| 2020 | 2        | 14.29%  |
| 2017 | 2        | 14.29%  |
| 2018 | 1        | 7.14%   |
| 2016 | 1        | 7.14%   |
| 2015 | 1        | 7.14%   |
| 2014 | 1        | 7.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 14       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 14       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 4        | 28.57%  |
| 16.01-24.0 | 4        | 28.57%  |
| 8.01-16.0  | 3        | 21.43%  |
| 32.01-64.0 | 1        | 7.14%   |
| 3.01-4.0   | 1        | 7.14%   |
| 24.01-32.0 | 1        | 7.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 6        | 42.86%  |
| 4.01-8.0  | 3        | 21.43%  |
| 2.01-3.0  | 3        | 21.43%  |
| 8.01-16.0 | 1        | 7.14%   |
| 0.51-1.0  | 1        | 7.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 6        | 42.86%  |
| 3      | 4        | 28.57%  |
| 4      | 2        | 14.29%  |
| 5      | 1        | 7.14%   |
| 1      | 1        | 7.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 73.33%  |
| Yes       | 4        | 26.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 11       | 73.33%  |
| No        | 4        | 26.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 7        | 50%     |
| No        | 7        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 7        | 50%     |
| Ukraine   | 1        | 7.14%   |
| Russia    | 1        | 7.14%   |
| Poland    | 1        | 7.14%   |
| Germany   | 1        | 7.14%   |
| France    | 1        | 7.14%   |
| Brazil    | 1        | 7.14%   |
| Australia | 1        | 7.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| Eugene      | 2        | 13.33%  |
| Warsaw      | 1        | 6.67%   |
| Ternopil    | 1        | 6.67%   |
| S??o Paulo  | 1        | 6.67%   |
| Saint Paul  | 1        | 6.67%   |
| Portsmouth  | 1        | 6.67%   |
| Offenbach   | 1        | 6.67%   |
| Melbourne   | 1        | 6.67%   |
| Lyon        | 1        | 6.67%   |
| Los Angeles | 1        | 6.67%   |
| Lafayette   | 1        | 6.67%   |
| Khabarovsk  | 1        | 6.67%   |
| Dudenhofen  | 1        | 6.67%   |
| Brunswick   | 1        | 6.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 14     | 24.24%  |
| WDC                 | 3        | 4      | 9.09%   |
| Samsung Electronics | 3        | 4      | 9.09%   |
| Crucial             | 3        | 3      | 9.09%   |
| Unknown             | 2        | 2      | 6.06%   |
| Toshiba             | 2        | 2      | 6.06%   |
| SK Hynix            | 2        | 2      | 6.06%   |
| SanDisk             | 2        | 2      | 6.06%   |
| Hitachi             | 2        | 3      | 6.06%   |
| SPCC                | 1        | 1      | 3.03%   |
| Phison              | 1        | 1      | 3.03%   |
| LITEONIT            | 1        | 1      | 3.03%   |
| Intenso             | 1        | 1      | 3.03%   |
| FORESEE             | 1        | 1      | 3.03%   |
| China               | 1        | 2      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown SD/MMC/MS PRO 7GB           | 2        | 5.13%   |
| Seagate Expansion 1TB               | 2        | 5.13%   |
| WDC WDBNCE0010PNC 1TB SSD           | 1        | 2.56%   |
| WDC WD3200LPVX-60V0TT0 320GB        | 1        | 2.56%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 2.56%   |
| Toshiba MK2552GSX 250GB             | 1        | 2.56%   |
| Toshiba DT01ACA100 1TB              | 1        | 2.56%   |
| SPCC Solid State Disk 120GB         | 1        | 2.56%   |
| SK Hynix PC601 NVMe 256GB           | 1        | 2.56%   |
| SK Hynix NVMe SSD Drive 256GB       | 1        | 2.56%   |
| Seagate ST9250410AS 250GB           | 1        | 2.56%   |
| Seagate ST500NM0011 500GB           | 1        | 2.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 2.56%   |
| Seagate ST500DM002-1SB10A 500GB     | 1        | 2.56%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 2.56%   |
| Seagate ST3500413AS 500GB           | 1        | 2.56%   |
| Seagate ST31000528AS 1TB            | 1        | 2.56%   |
| Seagate ST250DM000-1BD141 250GB     | 1        | 2.56%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1        | 2.56%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 2.56%   |
| SanDisk SSD PLUS 1000GB             | 1        | 2.56%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 1        | 2.56%   |
| Samsung SSD SM841N 2.5 7mm 256GB    | 1        | 2.56%   |
| Samsung SSD 860 EVO 250GB           | 1        | 2.56%   |
| Samsung SSD 840 Series 250GB        | 1        | 2.56%   |
| Samsung NVMe SSD Drive 1TB          | 1        | 2.56%   |
| Phison NVMe SSD Drive 1TB           | 1        | 2.56%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB   | 1        | 2.56%   |
| Intenso SSD SATAIII 128GB           | 1        | 2.56%   |
| Hitachi HTS547564A9E384 640GB       | 1        | 2.56%   |
| Hitachi HTS545050B9A300 500GB       | 1        | 2.56%   |
| Hitachi HDT721010SLA360 1TB         | 1        | 2.56%   |
| FORESEE 60GB SSD                    | 1        | 2.56%   |
| Crucial CT256MX100SSD1 256GB        | 1        | 2.56%   |
| Crucial CT240BX300SSD1 240GB        | 1        | 2.56%   |
| Crucial CT1000BX500SSD1 1TB         | 1        | 2.56%   |
| China SATA SSD 256GB                | 1        | 2.56%   |

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
| HDD  | 12       | 24     | 46.15%  |
| SSD  | 10       | 15     | 38.46%  |
| NVMe | 4        | 4      | 15.38%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 13       | 35     | 65%     |
| NVMe | 4        | 4      | 20%     |
| SAS  | 3        | 4      | 15%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 25     | 50%     |
| 0.51-1.0   | 10       | 12     | 41.67%  |
| 3.01-4.0   | 1        | 1      | 4.17%   |
| 1.01-2.0   | 1        | 1      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 3        | 18.75%  |
| 101-250    | 3        | 18.75%  |
| 1001-2000  | 3        | 18.75%  |
| 2001-3000  | 2        | 12.5%   |
| 501-1000   | 2        | 12.5%   |
| Unknown    | 2        | 12.5%   |
| 51-100     | 1        | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 21-50    | 4        | 25%     |
| 101-250  | 4        | 25%     |
| 251-500  | 2        | 12.5%   |
| 51-100   | 2        | 12.5%   |
| Unknown  | 2        | 12.5%   |
| 1-20     | 1        | 6.25%   |
| 501-1000 | 1        | 6.25%   |

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
| Intenso SSD SATAIII 128GB | 1        | 1      | 100%    |

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
| Detected | 9        | 21     | 37.5%   |
| Works    | 8        | 14     | 33.33%  |
| Malfunc  | 6        | 7      | 25%     |
| Failed   | 1        | 1      | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 9        | 45%     |
| AMD                 | 5        | 25%     |
| SK Hynix            | 2        | 10%     |
| VIA Technologies    | 1        | 5%      |
| Samsung Electronics | 1        | 5%      |
| Phison Electronics  | 1        | 5%      |
| JMicron Technology  | 1        | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 3        | 12.5%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 8.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 8.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 8.33%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 4.17%   |
| SK Hynix Non-Volatile memory controller                                                 | 1        | 4.17%   |
| SK Hynix BC511                                                                          | 1        | 4.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 4.17%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 4.17%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 4.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 4.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 4.17%   |
| AMD X399 Series Chipset SATA Controller                                                 | 1        | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1        | 4.17%   |
| AMD FCH SATA Controller D                                                               | 1        | 4.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 57.89%  |
| NVMe | 4        | 21.05%  |
| RAID | 2        | 10.53%  |
| IDE  | 2        | 10.53%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 64.29%  |
| AMD    | 5        | 35.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz            | 1        | 7.14%   |
| Intel Core M-5Y10c CPU @ 0.80GHz               | 1        | 7.14%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 7.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 7.14%   |
| Intel Core i7-2600 CPU @ 3.40GHz               | 1        | 7.14%   |
| Intel Core i5-9500T CPU @ 2.20GHz              | 1        | 7.14%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 7.14%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 7.14%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1        | 7.14%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 7.14%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 1        | 7.14%   |
| AMD FX-8320 Eight-Core Processor               | 1        | 7.14%   |
| AMD FX-6300 Six-Core Processor                 | 1        | 7.14%   |
| AMD A4-5300B APU with Radeon HD Graphics       | 1        | 7.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 4        | 28.57%  |
| Intel Core i7          | 3        | 21.43%  |
| AMD FX                 | 2        | 14.29%  |
| Intel Xeon             | 1        | 7.14%   |
| Intel Core M           | 1        | 7.14%   |
| AMD Ryzen Threadripper | 1        | 7.14%   |
| AMD Ryzen 3            | 1        | 7.14%   |
| AMD A4                 | 1        | 7.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 50%     |
| 6      | 3        | 21.43%  |
| 12     | 1        | 7.14%   |
| 3      | 1        | 7.14%   |
| 2      | 1        | 7.14%   |
| 1      | 1        | 7.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 64.29%  |
| 1      | 5        | 35.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 14       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 46.67%  |
| 0x06000852 | 2        | 13.33%  |
| 0x906ed    | 1        | 6.67%   |
| 0x906e9    | 1        | 6.67%   |
| 0x306c3    | 1        | 6.67%   |
| 0x306a9    | 1        | 6.67%   |
| 0x206a7    | 1        | 6.67%   |
| 0x0600111f | 1        | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 4        | 28.57%  |
| Piledriver  | 3        | 21.43%  |
| Zen         | 2        | 14.29%  |
| Haswell     | 2        | 14.29%  |
| SandyBridge | 1        | 7.14%   |
| IvyBridge   | 1        | 7.14%   |
| Broadwell   | 1        | 7.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 6        | 35.29%  |
| AMD    | 6        | 35.29%  |
| Intel  | 5        | 29.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 11.76%  |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 5.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 5.88%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 5.88%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 5.88%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 5.88%   |
| Nvidia G86 [GeForce 8300 GS]                                                | 1        | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 5.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 5.88%   |
| Intel HD Graphics 5300                                                      | 1        | 5.88%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 1        | 5.88%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 5.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 5.88%   |
| AMD Curacao XT / Trinidad XT [Radeon R7 370 / R9 270X/370X]                 | 1        | 5.88%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 5.88%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 5.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| 1 x Nvidia   | 5        | 35.71%  |
| 1 x AMD      | 4        | 28.57%  |
| 1 x Intel    | 3        | 21.43%  |
| Intel + AMD  | 1        | 7.14%   |
| AMD + Nvidia | 1        | 7.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 9        | 64.29%  |
| Proprietary | 5        | 35.71%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 6        | 40%     |
| 3.01-4.0   | 3        | 20%     |
| 1.01-2.0   | 3        | 20%     |
| 7.01-8.0   | 1        | 6.67%   |
| 0.51-1.0   | 1        | 6.67%   |
| 0.01-0.5   | 1        | 6.67%   |

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
| 1     | 9        | 64.29%  |
| 2     | 5        | 35.71%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 11       | 45.83%  |
| Intel                           | 4        | 16.67%  |
| Qualcomm Atheros Communications | 2        | 8.33%   |
| Qualcomm Atheros                | 2        | 8.33%   |
| Broadcom Limited                | 2        | 8.33%   |
| Ralink Technology               | 1        | 4.17%   |
| Microsoft                       | 1        | 4.17%   |
| D-Link System                   | 1        | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 9        | 34.62%  |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 7.69%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 3.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                | 1        | 3.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 3.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 1        | 3.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller            | 1        | 3.85%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 3.85%   |
| Intel Wireless 7265                                                  | 1        | 3.85%   |
| Intel Wireless 3160                                                  | 1        | 3.85%   |
| Intel I211 Gigabit Network Connection                                | 1        | 3.85%   |
| Intel Ethernet Connection (7) I219-LM                                | 1        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 3.85%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 3.85%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe             | 1        | 3.85%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1        | 3.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 27.27%  |
| Qualcomm Atheros Communications | 2        | 18.18%  |
| Realtek Semiconductor           | 1        | 9.09%   |
| Ralink Technology               | 1        | 9.09%   |
| Qualcomm Atheros                | 1        | 9.09%   |
| Microsoft                       | 1        | 9.09%   |
| D-Link System                   | 1        | 9.09%   |
| Broadcom Limited                | 1        | 9.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 18.18%  |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 9.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 9.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 9.09%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 9.09%   |
| Intel Wireless 7265                                                  | 1        | 9.09%   |
| Intel Wireless 3160                                                  | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1        | 9.09%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 9.09%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter           | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 66.67%  |
| Qualcomm Atheros      | 2        | 13.33%  |
| Intel                 | 2        | 13.33%  |
| Broadcom Limited      | 1        | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 60%     |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 6.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 6.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 6.67%   |
| Intel I211 Gigabit Network Connection                             | 1        | 6.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 6.67%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 56%     |
| WiFi     | 11       | 44%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 64.71%  |
| WiFi     | 6        | 35.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 57.14%  |
| 2     | 5        | 35.71%  |
| 3     | 1        | 7.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 71.43%  |
| Yes  | 4        | 28.57%  |

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
| Intel Bluetooth wireless interface                  | 2        | 28.57%  |
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
| Intel               | 9        | 37.5%   |
| AMD                 | 9        | 37.5%   |
| Nvidia              | 5        | 20.83%  |
| C-Media Electronics | 1        | 4.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH cAVS                                                        | 2        | 7.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 7.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 7.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 7.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 3.57%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 3.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 3.57%   |
| Nvidia GK104 HDMI Audio Controller                                                | 1        | 3.57%   |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 3.57%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 3.57%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 3.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 3.57%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                               | 1        | 3.57%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 3.57%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 1        | 3.57%   |
| AMD FCH Azalia Controller                                                         | 1        | 3.57%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 1        | 3.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1        | 3.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 1        | 3.57%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 3.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 2        | 25%     |
| Crucial          | 2        | 25%     |
| S                | 1        | 12.5%   |
| Nanya Technology | 1        | 12.5%   |
| Kingston         | 1        | 12.5%   |
| Corsair          | 1        | 12.5%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 11.11%  |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 11.11%  |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 1        | 11.11%  |
| S RAM Module 2GB DIMM DDR3 1600MT/s                      | 1        | 11.11%  |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s       | 1        | 11.11%  |
| Kingston RAM ACR24D4U7S8MB-8 8GB DIMM DDR4 2400MT/s      | 1        | 11.11%  |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s    | 1        | 11.11%  |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s | 1        | 11.11%  |
| Corsair RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s      | 1        | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 5        | 62.5%   |
| DDR4    | 2        | 25%     |
| Unknown | 1        | 12.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 8        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 5        | 55.56%  |
| 4096 | 3        | 33.33%  |
| 2048 | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 62.5%   |
| 2666  | 1        | 12.5%   |
| 2400  | 1        | 12.5%   |
| 1333  | 1        | 12.5%   |

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
| 0     | 13       | 92.86%  |
| 1     | 1        | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Desktops | Percent |
|--------------|----------|---------|
| Net/wireless | 1        | 100%    |

