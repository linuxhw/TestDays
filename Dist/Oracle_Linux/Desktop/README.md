Oracle Linux - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Oracle Linux.

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

Total: 11

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | 0C522T A03                  | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Gigabyte | Z490 AORUS ELITE AC         | [978ae6f2cb](https://linux-hardware.org/?probe=978ae6f2cb) | May 02, 2021 |
| Gigabyte | X99-Designare EX-CF         | [5195396549](https://linux-hardware.org/?probe=5195396549) | Mar 06, 2021 |
| ASUSTek  | G11CD                       | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP       | 158B                        | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell     | Board                       | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
| ASUSTek  | G11CD                       | [79f24a0a82](https://linux-hardware.org/?probe=79f24a0a82) | Dec 31, 2020 |
| Foxconn  | 2ADA                        | [809e03aea5](https://linux-hardware.org/?probe=809e03aea5) | Dec 24, 2020 |
| ASUSTek  | G11CD                       | [d9d0f8fdf2](https://linux-hardware.org/?probe=d9d0f8fdf2) | Dec 20, 2020 |
| Dell     | 0C96W1 A01                  | [b5c14107bb](https://linux-hardware.org/?probe=b5c14107bb) | Feb 12, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Oracle Linux 8.3 | 6        | 66.67%  |
| Oracle Linux 8.4 | 1        | 11.11%  |
| Oracle Linux 7.7 | 1        | 11.11%  |
| Oracle Linux 7.4 | 1        | 11.11%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Oracle Linux | 9        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Desktops | Percent |
|-----------------------------------|----------|---------|
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2        | 20%     |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2        | 20%     |
| 5.4.17-2102.202.5.el8uek.x86_64   | 1        | 10%     |
| 5.4.17-2102.200.13.el8uek.x86_64  | 1        | 10%     |
| 5.4.17-2036.100.6.1.el8uek.x86_64 | 1        | 10%     |
| 5.4.11-1.el7.elrepo.x86_64        | 1        | 10%     |
| 4.18.0-240.15.1.el8_3.x86_64      | 1        | 10%     |
| 3.10.0-693.11.6.el7.x86_64        | 1        | 10%     |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.17  | 6        | 66.67%  |
| 5.4.11  | 1        | 11.11%  |
| 4.18.0  | 1        | 11.11%  |
| 3.10.0  | 1        | 11.11%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 7        | 77.78%  |
| 4.18    | 1        | 11.11%  |
| 3.10    | 1        | 11.11%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 9        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 5        | 55.56%  |
| Unknown       | 3        | 33.33%  |
| GNOME Classic | 1        | 11.11%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 5        | 55.56%  |
| X11     | 2        | 22.22%  |
| Unknown | 2        | 22.22%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 88.89%  |
| TDM     | 1        | 11.11%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 3        | 33.33%  |
| it_IT      | 1        | 11.11%  |
| en_US.UTF8 | 1        | 11.11%  |
| en_IN      | 1        | 11.11%  |
| en_GB      | 1        | 11.11%  |
| de_DE      | 1        | 11.11%  |
| Unknown    | 1        | 11.11%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 5        | 55.56%  |
| EFI  | 4        | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 7        | 77.78%  |
| Ext4 | 2        | 22.22%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 6        | 66.67%  |
| MBR     | 2        | 22.22%  |
| GPT     | 1        | 11.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 88.89%  |
| Yes       | 1        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 3        | 33.33%  |
| Dell                | 3        | 33.33%  |
| Hewlett-Packard     | 1        | 11.11%  |
| Foxconn             | 1        | 11.11%  |
| ASUSTek Computer    | 1        | 11.11%  |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| HP Z820 Workstation              | 1        | 11.11%  |
| Gigabyte Z490 AORUS ELITE AC     | 1        | 11.11%  |
| Gigabyte X99-Designare EX-CF     | 1        | 11.11%  |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 11.11%  |
| Foxconn p6-2400el                | 1        | 11.11%  |
| Dell PowerEdge FC630             | 1        | 11.11%  |
| Dell OptiPlex 980                | 1        | 11.11%  |
| Dell OptiPlex 7060               | 1        | 11.11%  |
| ASUS G11CD                       | 1        | 11.11%  |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 2        | 22.22%  |
| HP Z820                | 1        | 11.11%  |
| Gigabyte Z490          | 1        | 11.11%  |
| Gigabyte X99-Designare | 1        | 11.11%  |
| Gigabyte X470          | 1        | 11.11%  |
| Foxconn p6-2400el      | 1        | 11.11%  |
| Dell PowerEdge         | 1        | 11.11%  |
| ASUS G11CD             | 1        | 11.11%  |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 3        | 33.33%  |
| 2012 | 2        | 22.22%  |
| 2020 | 1        | 11.11%  |
| 2019 | 1        | 11.11%  |
| 2016 | 1        | 11.11%  |
| 2010 | 1        | 11.11%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 9        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 9        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 9        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 64.01-256.0     | 2        | 22.22%  |
| 8.01-16.0       | 2        | 22.22%  |
| More than 256.0 | 1        | 11.11%  |
| 4.01-8.0        | 1        | 11.11%  |
| 32.01-64.0      | 1        | 11.11%  |
| 16.01-24.0      | 1        | 11.11%  |
| 1.01-2.0        | 1        | 11.11%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 3        | 30%     |
| 2.01-3.0   | 2        | 20%     |
| 3.01-4.0   | 1        | 10%     |
| 16.01-24.0 | 1        | 10%     |
| 1.01-2.0   | 1        | 10%     |
| 8.01-16.0  | 1        | 10%     |
| 0.01-0.5   | 1        | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 4        | 44.44%  |
| 3      | 2        | 22.22%  |
| 2      | 2        | 22.22%  |
| 5      | 1        | 11.11%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 5        | 55.56%  |
| No        | 4        | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 8        | 88.89%  |
| No        | 1        | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 6        | 66.67%  |
| Yes       | 3        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 5        | 55.56%  |
| Yes       | 4        | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Germany | 3        | 33.33%  |
| USA     | 1        | 11.11%  |
| UK      | 1        | 11.11%  |
| Russia  | 1        | 11.11%  |
| Romania | 1        | 11.11%  |
| Italy   | 1        | 11.11%  |
| India   | 1        | 11.11%  |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Rheinstetten  | 1        | 11.11%  |
| Reading       | 1        | 11.11%  |
| Moscow        | 1        | 11.11%  |
| Milan         | 1        | 11.11%  |
| Dietmannsried | 1        | 11.11%  |
| Bucharest     | 1        | 11.11%  |
| Berlin        | 1        | 11.11%  |
| Bengaluru     | 1        | 11.11%  |
| Asheville     | 1        | 11.11%  |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 42     | 38.46%  |
| WDC                 | 2        | 2      | 15.38%  |
| Samsung Electronics | 2        | 3      | 15.38%  |
| Toshiba             | 1        | 1      | 7.69%   |
| Phison              | 1        | 1      | 7.69%   |
| Hewlett-Packard     | 1        | 1      | 7.69%   |
| Crucial             | 1        | 1      | 7.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB   | 2        | 13.33%  |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 6.67%   |
| WDC WD10EZEX-60M2NA0 1TB         | 1        | 6.67%   |
| Toshiba NVMe SSD Drive 512GB     | 1        | 6.67%   |
| Seagate ST8000VN004-2M2101 8TB   | 1        | 6.67%   |
| Seagate ST3500414CS 500GB        | 1        | 6.67%   |
| Seagate ST2000NX0253 2TB         | 1        | 6.67%   |
| Seagate ST1000NX0423 1TB         | 1        | 6.67%   |
| Samsung SSD PM830 2.5 7mm 256GB  | 1        | 6.67%   |
| Samsung SSD 960 EVO 250GB        | 1        | 6.67%   |
| Samsung HD502IJ 500GB            | 1        | 6.67%   |
| Phison NVMe SSD Drive 1TB        | 1        | 6.67%   |
| HP SSD S700 120GB                | 1        | 6.67%   |
| Crucial CT500MX500SSD1 500GB     | 1        | 6.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 42     | 71.43%  |
| WDC                 | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |
| Hewlett-Packard     | 1        | 1      | 25%     |
| Crucial             | 1        | 1      | 25%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 44     | 46.15%  |
| SSD  | 4        | 4      | 30.77%  |
| NVMe | 3        | 3      | 23.08%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 9        | 48     | 75%     |
| NVMe | 3        | 3      | 25%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 5        | 6      | 45.45%  |
| 1.01-2.0   | 3        | 37     | 27.27%  |
| 0.51-1.0   | 2        | 3      | 18.18%  |
| 4.01-10.0  | 1        | 2      | 9.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 3        | 33.33%  |
| More than 3000 | 1        | 11.11%  |
| 21-50          | 1        | 11.11%  |
| 2001-3000      | 1        | 11.11%  |
| 1001-2000      | 1        | 11.11%  |
| 501-1000       | 1        | 11.11%  |
| Unknown        | 1        | 11.11%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 3        | 33.33%  |
| 101-250        | 2        | 22.22%  |
| 1-20           | 2        | 22.22%  |
| More than 3000 | 1        | 11.11%  |
| Unknown        | 1        | 11.11%  |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| Hewlett-Packard SSD S700 120GB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| Hewlett-Packard | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 1        | 1      | 100%    |

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
| Detected | 6        | 11     | 66.67%  |
| Works    | 2        | 39     | 22.22%  |
| Malfunc  | 1        | 1      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 8        | 57.14%  |
| Broadcom / LSI               | 2        | 14.29%  |
| Toshiba America Info Systems | 1        | 7.14%   |
| Samsung Electronics          | 1        | 7.14%   |
| Phison Electronics           | 1        | 7.14%   |
| AMD                          | 1        | 7.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2        | 10.53%  |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2        | 10.53%  |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1        | 5.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1        | 5.26%   |
| Phison E12 NVMe Controller                                                       | 1        | 5.26%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 5.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1        | 5.26%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1        | 5.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 5.26%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 1        | 5.26%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 1        | 5.26%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 1        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1        | 5.26%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 1        | 5.26%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 1        | 5.26%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 1        | 5.26%   |
| AMD 400 Series Chipset SATA Controller                                           | 1        | 5.26%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 7        | 46.67%  |
| RAID | 3        | 20%     |
| NVMe | 3        | 20%     |
| SAS  | 1        | 6.67%   |
| IDE  | 1        | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 8        | 88.89%  |
| AMD    | 1        | 11.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 11.11%  |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 1        | 11.11%  |
| Intel Pentium CPU G2020 @ 2.90GHz      | 1        | 11.11%  |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 11.11%  |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 11.11%  |
| Intel Core i7-6800K CPU @ 3.40GHz      | 1        | 11.11%  |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 11.11%  |
| Intel Core i3 CPU 550 @ 3.20GHz        | 1        | 11.11%  |
| AMD Ryzen 7 2700X Eight-Core Processor | 1        | 11.11%  |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i7 | 3        | 33.33%  |
| Intel Xeon    | 2        | 22.22%  |
| Intel Pentium | 1        | 11.11%  |
| Intel Core i9 | 1        | 11.11%  |
| Intel Core i3 | 1        | 11.11%  |
| AMD Ryzen 7   | 1        | 11.11%  |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 16     | 2        | 22.22%  |
| 6      | 2        | 22.22%  |
| 2      | 2        | 22.22%  |
| 10     | 1        | 11.11%  |
| 8      | 1        | 11.11%  |
| 4      | 1        | 11.11%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 77.78%  |
| 2      | 2        | 22.22%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 8        | 88.89%  |
| 1      | 1        | 11.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 9        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0xa0655    | 1        | 11.11%  |
| 0x906ea    | 1        | 11.11%  |
| 0x506e3    | 1        | 11.11%  |
| 0x406f1    | 1        | 11.11%  |
| 0x306e4    | 1        | 11.11%  |
| 0x306a9    | 1        | 11.11%  |
| 0x20655    | 1        | 11.11%  |
| 0x0800820d | 1        | 11.11%  |
| Unknown    | 1        | 11.11%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| IvyBridge | 2        | 22.22%  |
| Broadwell | 2        | 22.22%  |
| Zen+      | 1        | 11.11%  |
| Westmere  | 1        | 11.11%  |
| Skylake   | 1        | 11.11%  |
| KabyLake  | 1        | 11.11%  |
| CometLake | 1        | 11.11%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 5        | 50%     |
| Intel                      | 4        | 40%     |
| Matrox Electronics Systems | 1        | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Nvidia TU116 [GeForce GTX 1650 SUPER]                            | 1        | 10%     |
| Nvidia GP107 [GeForce GTX 1050]                                  | 1        | 10%     |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 1        | 10%     |
| Nvidia GM204 [GeForce GTX 980]                                   | 1        | 10%     |
| Nvidia GK110GL [Quadro K6000]                                    | 1        | 10%     |
| Matrox Electronics Systems G200eR2                               | 1        | 10%     |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller | 1        | 10%     |
| Intel Core Processor Integrated Graphics Controller              | 1        | 10%     |
| Intel CometLake-S GT2 [UHD Graphics 630]                         | 1        | 10%     |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                        | 1        | 10%     |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 5        | 55.56%  |
| 1 x Intel  | 3        | 33.33%  |
| 1 x Matrox | 1        | 11.11%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 8        | 88.89%  |
| Proprietary | 1        | 11.11%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 44.44%  |
| 3.01-4.0   | 2        | 22.22%  |
| 5.01-6.0   | 1        | 11.11%  |
| 1.01-2.0   | 1        | 11.11%  |
| 8.01-16.0  | 1        | 11.11%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 22.22%  |
| Hewlett-Packard     | 2        | 22.22%  |
| Dell                | 2        | 22.22%  |
| Goldstar            | 1        | 11.11%  |
| Eizo                | 1        | 11.11%  |
| BenQ                | 1        | 11.11%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch | 1        | 11.11%  |
| Samsung Electronics LCD Monitor S24C650                             | 1        | 11.11%  |
| Hewlett-Packard Z24i HWP309E 1920x1200 520x320mm 24.0-inch          | 1        | 11.11%  |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch         | 1        | 11.11%  |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                | 1        | 11.11%  |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                   | 1        | 11.11%  |
| Dell LCD Monitor U2415 3840x1200                                    | 1        | 11.11%  |
| Dell IDRAC DEL0001 1280x1024                                        | 1        | 11.11%  |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                   | 1        | 11.11%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 3        | 33.33%  |
| 3840x1200         | 1        | 11.11%  |
| 2560x1440 (QHD)   | 1        | 11.11%  |
| 1920x1200 (WUXGA) | 1        | 11.11%  |
| 1360x768          | 1        | 11.11%  |
| 1280x1024 (SXGA)  | 1        | 11.11%  |
| Unknown           | 1        | 11.11%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 2        | 25%     |
| Unknown | 2        | 25%     |
| 27      | 1        | 12.5%   |
| 23      | 1        | 12.5%   |
| 21      | 1        | 12.5%   |
| 18      | 1        | 12.5%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 4        | 50%     |
| 401-500     | 2        | 25%     |
| Unknown     | 2        | 25%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 5        | 62.5%   |
| 5/4     | 1        | 12.5%   |
| 16/10   | 1        | 12.5%   |
| Unknown | 1        | 12.5%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 37.5%   |
| Unknown        | 2        | 25%     |
| 301-350        | 1        | 12.5%   |
| 251-300        | 1        | 12.5%   |
| 141-150        | 1        | 12.5%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4        | 50%     |
| 101-120 | 2        | 25%     |
| Unknown | 2        | 25%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 88.89%  |
| 2     | 1        | 11.11%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 60%     |
| Realtek Semiconductor | 3        | 30%     |
| Broadcom              | 1        | 10%     |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                             | 2        | 15.38%  |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 7.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 7.69%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1        | 7.69%   |
| Intel Wireless 8260                                               | 1        | 7.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 7.69%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 7.69%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 7.69%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 7.69%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 7.69%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 7.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2        | 66.67%  |
| Realtek Semiconductor | 1        | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter | 1        | 33.33%  |
| Intel Wireless 8260                                      | 1        | 33.33%  |
| Intel Comet Lake PCH CNVi WiFi                           | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 62.5%   |
| Realtek Semiconductor | 2        | 25%     |
| Broadcom              | 1        | 12.5%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                             | 2        | 20%     |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 10%     |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1        | 10%     |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 10%     |
| Intel Ethernet Connection (2) I218-V                              | 1        | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 10%     |
| Intel 82578DM Gigabit Network Connection                          | 1        | 10%     |
| Intel 82574L Gigabit Network Connection                           | 1        | 10%     |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 10%     |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 8        | 72.73%  |
| WiFi     | 3        | 27.27%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 8        | 88.89%  |
| WiFi     | 1        | 11.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5        | 55.56%  |
| 2     | 3        | 33.33%  |
| 3     | 1        | 11.11%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 9        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 2        | 40%     |
| IMC Networks     | 1        | 20%     |
| Broadcom         | 1        | 20%     |
| ASUSTek Computer | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface             | 1        | 20%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 20%     |
| IMC Networks Bluetooth Radio                   | 1        | 20%     |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1        | 20%     |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 6        | 50%     |
| Nvidia | 5        | 41.67%  |
| AMD    | 1        | 8.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 High Definition Audio Controller                              | 1        | 8.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 8.33%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 8.33%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 8.33%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 8.33%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 8.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 8.33%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 8.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 8.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 8.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 8.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Micron Technology | 1        | 33.33%  |
| Kingston          | 1        | 33.33%  |
| Crucial           | 1        | 33.33%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s     | 1        | 33.33%  |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s            | 1        | 33.33%  |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s | 1        | 33.33%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 2        | 66.67%  |
| DDR3 | 1        | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 3        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 1        | 33.33%  |
| 8192  | 1        | 33.33%  |
| 1024  | 1        | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3466  | 1        | 33.33%  |
| 2400  | 1        | 33.33%  |
| 1333  | 1        | 33.33%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Samsung ML-1660 Series | 1        | 100%    |

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
| Microdia | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Microdia Webcam Vitade AF | 1        | 100%    |

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
| 0     | 6        | 66.67%  |
| 2     | 3        | 33.33%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 2        | 40%     |
| Net/wireless             | 1        | 20%     |
| Communication controller | 1        | 20%     |
| Bluetooth                | 1        | 20%     |

