CentOS 9 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for CentOS 9.

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

Total: 15

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Colorful T... | CVN Z590 GAMING PRO V20     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| Dell          | 0NKW6Y A02                  | [f20d5b9289](https://linux-hardware.org/?probe=f20d5b9289) | Dec 07, 2022 |
| MSI           | X470 GAMING PRO             | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e840ded8c0](https://linux-hardware.org/?probe=e840ded8c0) | Nov 09, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| Intel         | D34010WYK H14771-303        | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| ASUSTek       | H81M-K                      | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| ASUSTek       | H81M-K                      | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| NCR           | Pocono BIOS.6.0             | [ae030a0cda](https://linux-hardware.org/?probe=ae030a0cda) | Jul 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [c45dba9246](https://linux-hardware.org/?probe=c45dba9246) | Jun 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [3d36beed4b](https://linux-hardware.org/?probe=3d36beed4b) | Jun 25, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.14.0-202.el9.x86_64          | 2        | 16.67%  |
| 5.17.2-lqx3.0.el9.x86_64       | 1        | 8.33%   |
| 5.14.0-86.el9.x86_64           | 1        | 8.33%   |
| 5.14.0-302.el9.x86_64          | 1        | 8.33%   |
| 5.14.0-267.el9.x86_64          | 1        | 8.33%   |
| 5.14.0-214.el9.x86_64          | 1        | 8.33%   |
| 5.14.0-183.el9.x86_64          | 1        | 8.33%   |
| 5.14.0-134.el9.x86_64          | 1        | 8.33%   |
| 5.14.0-130.rt21.130.el9.x86_64 | 1        | 8.33%   |
| 5.14.0-115.el9.x86_64          | 1        | 8.33%   |
| 5.14.0-109.el9.x86_64          | 1        | 8.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14.0  | 9        | 90%     |
| 5.17.2  | 1        | 10%     |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.14    | 9        | 90%     |
| 5.17    | 1        | 10%     |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 10       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 8        | 80%     |
| KDE5          | 1        | 10%     |
| GNOME Classic | 1        | 10%     |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 6        | 54.55%  |
| Wayland | 5        | 45.45%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 63.64%  |
| GDM     | 3        | 27.27%  |
| SDDM    | 1        | 9.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 6        | 60%     |
| zh_CN | 1        | 10%     |
| ru_UA | 1        | 10%     |
| ja_JP | 1        | 10%     |
| it_IT | 1        | 10%     |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 6        | 60%     |
| BIOS | 4        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 9        | 90%     |
| Ext4 | 1        | 10%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 58.33%  |
| GPT     | 4        | 33.33%  |
| MBR     | 1        | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 81.82%  |
| Yes       | 2        | 18.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 75%     |
| Yes       | 3        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4        | 40%     |
| Gigabyte Technology | 2        | 20%     |
| MSI                 | 1        | 10%     |
| Intel               | 1        | 10%     |
| Dell                | 1        | 10%     |
| Colorful Technology | 1        | 10%     |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| MSI MS-7B79                       | 1        | 10%     |
| Intel D34010WYK H14771-303        | 1        | 10%     |
| Gigabyte X99-UD4-CF               | 1        | 10%     |
| Gigabyte 970A-DS3P                | 1        | 10%     |
| Dell OptiPlex 790                 | 1        | 10%     |
| Colorful CVN Z590 GAMING PRO      | 1        | 10%     |
| ASUS TUF Gaming X570-PLUS         | 1        | 10%     |
| ASUS ROG STRIX B560-G GAMING WIFI | 1        | 10%     |
| ASUS PRIME H670-PLUS D4           | 1        | 10%     |
| ASUS All Series                   | 1        | 10%     |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| MSI MS-7B79         | 1        | 10%     |
| Intel D34010WYK     | 1        | 10%     |
| Gigabyte X99-UD4-CF | 1        | 10%     |
| Gigabyte 970A-DS3P  | 1        | 10%     |
| Dell OptiPlex       | 1        | 10%     |
| Colorful CVN        | 1        | 10%     |
| ASUS TUF            | 1        | 10%     |
| ASUS ROG            | 1        | 10%     |
| ASUS PRIME          | 1        | 10%     |
| ASUS All            | 1        | 10%     |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 3        | 30%     |
| 2013 | 3        | 30%     |
| 2019 | 1        | 10%     |
| 2018 | 1        | 10%     |
| 2014 | 1        | 10%     |
| 2012 | 1        | 10%     |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 10       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 10       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 10       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 3        | 30%     |
| 32.01-64.0  | 2        | 20%     |
| 64.01-256.0 | 2        | 20%     |
| 16.01-24.0  | 2        | 20%     |
| 8.01-16.0   | 1        | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 3.01-4.0  | 4        | 33.33%  |
| 2.01-3.0  | 4        | 33.33%  |
| 8.01-16.0 | 2        | 16.67%  |
| 4.01-8.0  | 1        | 8.33%   |
| 1.01-2.0  | 1        | 8.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 4      | 4        | 40%     |
| 2      | 3        | 30%     |
| 3      | 2        | 20%     |
| 1      | 1        | 10%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 90%     |
| Yes       | 1        | 10%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 60%     |
| No        | 4        | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6        | 60%     |
| No        | 4        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| USA      | 3        | 30%     |
| Bulgaria | 3        | 30%     |
| Ukraine  | 1        | 10%     |
| Japan    | 1        | 10%     |
| Italy    | 1        | 10%     |
| China    | 1        | 10%     |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Sofia          | 2        | 20%     |
| Wuhan          | 1        | 10%     |
| Tomah          | 1        | 10%     |
| Rome           | 1        | 10%     |
| Portland       | 1        | 10%     |
| Okazaki        | 1        | 10%     |
| New Cumberland | 1        | 10%     |
| Kyiv           | 1        | 10%     |
| Burgas         | 1        | 10%     |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 7      | 20.83%  |
| Seagate             | 4        | 6      | 16.67%  |
| Samsung Electronics | 3        | 4      | 12.5%   |
| Toshiba             | 2        | 3      | 8.33%   |
| WD MediaMax         | 1        | 1      | 4.17%   |
| Team                | 1        | 2      | 4.17%   |
| SanDisk             | 1        | 6      | 4.17%   |
| Plextor             | 1        | 1      | 4.17%   |
| Phison              | 1        | 1      | 4.17%   |
| Kingston            | 1        | 1      | 4.17%   |
| Intel               | 1        | 1      | 4.17%   |
| Gigabyte Technology | 1        | 2      | 4.17%   |
| Crucial             | 1        | 6      | 4.17%   |
| A-DATA Technology   | 1        | 1      | 4.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| WDC WDS250G2B0A-00SM50 250GB SSD           | 1        | 3.7%    |
| WDC WD3200AAKX-753CA1 320GB                | 1        | 3.7%    |
| WDC WD2500AAJS-60M0A0 250GB                | 1        | 3.7%    |
| WDC WD22EJRX-89BEMY0 2TB                   | 1        | 3.7%    |
| WDC WD10EZEX-60M2NA0 1TB                   | 1        | 3.7%    |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 3.7%    |
| WD MediaMax WL750GSA6472 752GB             | 1        | 3.7%    |
| Toshiba MK2561GSYN 250GB                   | 1        | 3.7%    |
| Toshiba DT01ACA100 1TB                     | 1        | 3.7%    |
| Team T253X1480G 480GB SSD                  | 1        | 3.7%    |
| Seagate ST3500413AS 500GB                  | 1        | 3.7%    |
| Seagate ST3250820AS 250GB                  | 1        | 3.7%    |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 3.7%    |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 3.7%    |
| Seagate FireCuda 520 SSD ZP1000GM30002 1TB | 1        | 3.7%    |
| Sandisk WD_BLACK SN770 1TB                 | 1        | 3.7%    |
| SanDisk SDSSDH3 1T00 1TB                   | 1        | 3.7%    |
| Samsung SSD 870 QVO 2TB                    | 1        | 3.7%    |
| Samsung SSD 870 EVO 250GB                  | 1        | 3.7%    |
| Samsung MZ7LN256HAJQ-00000 256GB SSD       | 1        | 3.7%    |
| Plextor PX-256M8VC 256GB SSD               | 1        | 3.7%    |
| Phison NVMe SSD Drive 1024GB               | 1        | 3.7%    |
| Kingston SHFS37A480G 480GB SSD             | 1        | 3.7%    |
| Intel NVMe SSD Drive 1024GB                | 1        | 3.7%    |
| Gigabyte GP-GSTFS31960GNTD-V 960GB SSD     | 1        | 3.7%    |
| Crucial CT525MX300SSD1 528GB               | 1        | 3.7%    |
| A-DATA SP310 32GB SSD                      | 1        | 3.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 4        | 6      | 40%     |
| Seagate     | 3        | 4      | 30%     |
| Toshiba     | 2        | 3      | 20%     |
| WD MediaMax | 1        | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 4      | 27.27%  |
| WDC                 | 1        | 1      | 9.09%   |
| Team                | 1        | 2      | 9.09%   |
| SanDisk             | 1        | 3      | 9.09%   |
| Plextor             | 1        | 1      | 9.09%   |
| Kingston            | 1        | 1      | 9.09%   |
| Gigabyte Technology | 1        | 2      | 9.09%   |
| Crucial             | 1        | 6      | 9.09%   |
| A-DATA Technology   | 1        | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 8        | 21     | 47.06%  |
| HDD  | 5        | 14     | 29.41%  |
| NVMe | 4        | 7      | 23.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 10       | 35     | 71.43%  |
| NVMe | 4        | 7      | 28.57%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 8        | 14     | 50%     |
| 0.51-1.0   | 6        | 18     | 37.5%   |
| 1.01-2.0   | 2        | 3      | 12.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 5        | 45.45%  |
| 101-250        | 2        | 18.18%  |
| More than 3000 | 1        | 9.09%   |
| 21-50          | 1        | 9.09%   |
| 2001-3000      | 1        | 9.09%   |
| 501-1000       | 1        | 9.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 4        | 40%     |
| 501-1000       | 2        | 20%     |
| More than 3000 | 1        | 10%     |
| 251-500        | 1        | 10%     |
| 21-50          | 1        | 10%     |
| 51-100         | 1        | 10%     |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC WD10EZEX-60M2NA0 1TB  | 1        | 1      | 33.33%  |
| Toshiba MK2561GSYN 250GB  | 1        | 1      | 33.33%  |
| Seagate ST3250820AS 250GB | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 100%    |

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
| Detected | 8        | 25     | 57.14%  |
| Works    | 4        | 14     | 28.57%  |
| Malfunc  | 2        | 3      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 8        | 53.33%  |
| AMD                | 3        | 20%     |
| Silicon Image      | 1        | 6.67%   |
| Seagate Technology | 1        | 6.67%   |
| SanDisk            | 1        | 6.67%   |
| Phison Electronics | 1        | 6.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 12.5%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 2        | 12.5%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 6.25%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 6.25%   |
| SanDisk WD Black SN770 NVMe SSD                                                | 1        | 6.25%   |
| Phison E12 NVMe Controller                                                     | 1        | 6.25%   |
| Intel SATA Controller [RAID mode]                                              | 1        | 6.25%   |
| Intel Non-Volatile memory controller                                           | 1        | 6.25%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 6.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 6.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 6.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 6.25%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 6.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 9        | 60%     |
| NVMe | 4        | 26.67%  |
| RAID | 2        | 13.33%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 70%     |
| AMD    | 3        | 30%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i7-5930K CPU @ 3.50GHz      | 1        | 10%     |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 10%     |
| Intel Core i5-2400S CPU @ 2.50GHz      | 1        | 10%     |
| Intel Core i5-10400F CPU @ 2.90GHz     | 1        | 10%     |
| Intel Core i3-4010U CPU @ 1.70GHz      | 1        | 10%     |
| Intel 12th Gen Core i5-12600K          | 1        | 10%     |
| Intel 11th Gen Core i5-11400 @ 2.60GHz | 1        | 10%     |
| AMD Ryzen 9 5950X 16-Core Processor    | 1        | 10%     |
| AMD Ryzen 5 3600 6-Core Processor      | 1        | 10%     |
| AMD FX-8120 Eight-Core Processor       | 1        | 10%     |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i5 | 3        | 30%     |
| Other         | 2        | 20%     |
| Intel Core i7 | 1        | 10%     |
| Intel Core i3 | 1        | 10%     |
| AMD Ryzen 9   | 1        | 10%     |
| AMD Ryzen 5   | 1        | 10%     |
| AMD FX        | 1        | 10%     |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 4        | 40%     |
| 4      | 3        | 30%     |
| 16     | 1        | 10%     |
| 10     | 1        | 10%     |
| 2      | 1        | 10%     |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 10       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 80%     |
| 1      | 2        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 10       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0671    | 1        | 10%     |
| 0xa0653    | 1        | 10%     |
| 0x90672    | 1        | 10%     |
| 0x40651    | 1        | 10%     |
| 0x306f2    | 1        | 10%     |
| 0x306c3    | 1        | 10%     |
| 0x206a7    | 1        | 10%     |
| 0x0a201016 | 1        | 10%     |
| 0x08701013 | 1        | 10%     |
| 0x0600063d | 1        | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 3        | 30%     |
| Zen 3            | 1        | 10%     |
| Zen 2            | 1        | 10%     |
| SandyBridge      | 1        | 10%     |
| Icelake          | 1        | 10%     |
| CometLake        | 1        | 10%     |
| Bulldozer        | 1        | 10%     |
| Alderlake Hybrid | 1        | 10%     |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 4        | 40%     |
| Intel  | 3        | 30%     |
| AMD    | 3        | 30%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia TU117 [GeForce GTX 1650]                                           | 1        | 8.33%   |
| Nvidia TU116 [GeForce GTX 1660]                                           | 1        | 8.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1        | 8.33%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                         | 1        | 8.33%   |
| Nvidia GK208B [GeForce GT 730]                                            | 1        | 8.33%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                 | 1        | 8.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1        | 8.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 8.33%   |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                     | 1        | 8.33%   |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                 | 1        | 8.33%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 1        | 8.33%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 1        | 8.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 4        | 40%     |
| 1 x Intel  | 3        | 30%     |
| 1 x AMD    | 2        | 20%     |
| 2 x AMD    | 1        | 10%     |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 7        | 63.64%  |
| Proprietary | 3        | 27.27%  |
| Unknown     | 1        | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 33.33%  |
| 5.01-6.0   | 3        | 25%     |
| 3.01-4.0   | 2        | 16.67%  |
| 1.01-2.0   | 1        | 8.33%   |
| 8.01-16.0  | 1        | 8.33%   |
| 0.01-0.5   | 1        | 8.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 33.33%  |
| Goldstar            | 2        | 16.67%  |
| LG Electronics      | 1        | 8.33%   |
| Iiyama              | 1        | 8.33%   |
| Dell                | 1        | 8.33%   |
| BenQ                | 1        | 8.33%   |
| AOC                 | 1        | 8.33%   |
| Acer                | 1        | 8.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch       | 1        | 8.33%   |
| Samsung Electronics SyncMaster SAM05EB 1920x1080 597x336mm 27.0-inch    | 1        | 8.33%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch      | 1        | 8.33%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1        | 8.33%   |
| LG Electronics LCD Monitor LG FULL HD                                   | 1        | 8.33%   |
| Iiyama PL2888H IVM7106 1920x1080 621x341mm 27.9-inch                    | 1        | 8.33%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                    | 1        | 8.33%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                   | 1        | 8.33%   |
| Dell 2408WFP DELA029 1920x1200 519x324mm 24.1-inch                      | 1        | 8.33%   |
| BenQ ZOWIE XL LCD BNQ7F83 1920x1080 544x303mm 24.5-inch                 | 1        | 8.33%   |
| AOC LCD Monitor 24G1WG4 3840x1080                                       | 1        | 8.33%   |
| Acer H236HL ACR0318 1920x1080 509x286mm 23.0-inch                       | 1        | 8.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 7        | 58.33%  |
| 3840x2160 (4K)    | 2        | 16.67%  |
| 3840x1080         | 1        | 8.33%   |
| 1920x1200 (WUXGA) | 1        | 8.33%   |
| Unknown           | 1        | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 3        | 27.27%  |
| 21      | 3        | 27.27%  |
| 24      | 2        | 18.18%  |
| 84      | 1        | 9.09%   |
| 23      | 1        | 9.09%   |
| Unknown | 1        | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 4        | 36.36%  |
| 401-500     | 3        | 27.27%  |
| 601-700     | 2        | 18.18%  |
| 1501-2000   | 1        | 9.09%   |
| Unknown     | 1        | 9.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 8        | 80%     |
| 16/10   | 1        | 10%     |
| Unknown | 1        | 10%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 3        | 27.27%  |
| 201-250        | 3        | 27.27%  |
| 251-300        | 2        | 18.18%  |
| More than 1000 | 1        | 9.09%   |
| 151-200        | 1        | 9.09%   |
| Unknown        | 1        | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 5        | 50%     |
| 101-120 | 3        | 30%     |
| 121-160 | 1        | 10%     |
| Unknown | 1        | 10%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 72.73%  |
| 2     | 2        | 18.18%  |
| 0     | 1        | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 38.89%  |
| Realtek Semiconductor | 6        | 33.33%  |
| Qualcomm Atheros      | 2        | 11.11%  |
| U-Blox                | 1        | 5.56%   |
| TP-Link               | 1        | 5.56%   |
| Ceton Technologies    | 1        | 5.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 20%     |
| Intel Ethernet Controller I225-V                                  | 2        | 10%     |
| U-Blox [u-blox 8]                                                 | 1        | 5%      |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 5%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 5%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 5%      |
| Intel Wireless-AC 9260                                            | 1        | 5%      |
| Intel Wireless 7260                                               | 1        | 5%      |
| Intel Wi-Fi 6 AX200                                               | 1        | 5%      |
| Intel Ethernet Connection I218-V                                  | 1        | 5%      |
| Intel Ethernet Connection (2) I218-V                              | 1        | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 5%      |
| Intel 82574L Gigabit Network Connection                           | 1        | 5%      |
| Ceton InfiniTV Network                                            | 1        | 5%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 42.86%  |
| Qualcomm Atheros      | 2        | 28.57%  |
| TP-Link               | 1        | 14.29%  |
| Realtek Semiconductor | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 14.29%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1        | 14.29%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 14.29%  |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 1        | 14.29%  |
| Intel Wireless-AC 9260                                     | 1        | 14.29%  |
| Intel Wireless 7260                                        | 1        | 14.29%  |
| Intel Wi-Fi 6 AX200                                        | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 50%     |
| Realtek Semiconductor | 5        | 41.67%  |
| Ceton Technologies    | 1        | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 33.33%  |
| Intel Ethernet Controller I225-V                                  | 2        | 16.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 8.33%   |
| Intel Ethernet Connection I218-V                                  | 1        | 8.33%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 8.33%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 8.33%   |
| Ceton InfiniTV Network                                            | 1        | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 58.82%  |
| WiFi     | 6        | 35.29%  |
| Modem    | 1        | 5.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5        | 50%     |
| 2     | 4        | 40%     |
| 3     | 1        | 10%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 8        | 80%     |
| Yes  | 2        | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 3        | 50%     |
| Qualcomm Atheros Communications | 1        | 16.67%  |
| Cambridge Silicon Radio         | 1        | 16.67%  |
| ASUSTek Computer                | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9462 Bluetooth                   | 1        | 16.67%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 16.67%  |
| Intel Bluetooth wireless interface                  | 1        | 16.67%  |
| Intel AX200 Bluetooth                               | 1        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 16.67%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Intel           | 7        | 43.75%  |
| Nvidia          | 4        | 25%     |
| AMD             | 4        | 25%     |
| SteelSeries ApS | 1        | 6.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 High Definition Audio Controller                              | 2        | 10.53%  |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 10.53%  |
| SteelSeries ApS SteelSeries GameDAC                                        | 1        | 5.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 5.26%   |
| Nvidia GM200 High Definition Audio                                         | 1        | 5.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 5.26%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 5.26%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 5.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1        | 5.26%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 5.26%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 5.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 5.26%   |
| Intel 8 Series HD Audio Controller                                         | 1        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 5.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 5.26%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 5.26%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 5.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Team                | 1        | 20%     |
| Samsung Electronics | 1        | 20%     |
| G.Skill             | 1        | 20%     |
| Crucial             | 1        | 20%     |
| Corsair             | 1        | 20%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s       | 1        | 20%     |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s      | 1        | 20%     |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s    | 1        | 20%     |
| Crucial RAM CT16G4DFD824A.C16FBD 16GB DIMM DDR4 2933MT/s | 1        | 20%     |
| Corsair RAM CMK128GX4M8A2666C16 16GB DIMM DDR4 2133MT/s  | 1        | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 3        | 60%     |
| DDR3 | 2        | 40%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 5        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 2        | 40%     |
| 8192  | 2        | 40%     |
| 32768 | 1        | 20%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 1        | 20%     |
| 2933  | 1        | 20%     |
| 2133  | 1        | 20%     |
| 1800  | 1        | 20%     |
| 1600  | 1        | 20%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 2        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Sunplus Canyon CNS-CWC5 Webcam | 2        | 100%    |

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
| 1     | 6        | 50%     |
| 0     | 5        | 41.67%  |
| 2     | 1        | 8.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Net/wireless     | 3        | 37.5%   |
| Unassigned class | 1        | 12.5%   |
| Storage/ata      | 1        | 12.5%   |
| Graphics card    | 1        | 12.5%   |
| Dvb card         | 1        | 12.5%   |
| Bluetooth        | 1        | 12.5%   |

