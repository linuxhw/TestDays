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

Total: 15

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell     | 0DC48C A02                  | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| ASUSTek  | H81M-A                      | [a37e952875](https://linux-hardware.org/?probe=a37e952875) | Sep 04, 2022 |
| Dell     | 073Y7Y A00                  | [3bed97b23e](https://linux-hardware.org/?probe=3bed97b23e) | Jul 21, 2022 |
| MSI      | Z77A-G43                    | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| ASUSTek  | P8H67                       | [b194dad4cf](https://linux-hardware.org/?probe=b194dad4cf) | Jun 25, 2022 |
| Dell     | 0C522T A03                  | [3dc84dc8ff](https://linux-hardware.org/?probe=3dc84dc8ff) | Mar 24, 2022 |
| Gigabyte | Z490 AORUS ELITE AC         | [978ae6f2cb](https://linux-hardware.org/?probe=978ae6f2cb) | May 02, 2021 |
| Gigabyte | X99-Designare EX-CF         | [5195396549](https://linux-hardware.org/?probe=5195396549) | Mar 06, 2021 |
| ASUSTek  | G11CD                       | [13961e12a8](https://linux-hardware.org/?probe=13961e12a8) | Feb 01, 2021 |
| HP       | 158B                        | [5e6b9531d7](https://linux-hardware.org/?probe=5e6b9531d7) | Feb 01, 2021 |
| Dell     | PowerEdge FC630             | [bcd33a41f0](https://linux-hardware.org/?probe=bcd33a41f0) | Jan 25, 2021 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | [71628a95b6](https://linux-hardware.org/?probe=71628a95b6) | Jan 13, 2021 |
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
| Oracle Linux 8.3 | 6        | 42.86%  |
| Oracle Linux 8.6 | 4        | 28.57%  |
| Oracle Linux 9.0 | 1        | 7.14%   |
| Oracle Linux 8.4 | 1        | 7.14%   |
| Oracle Linux 7.7 | 1        | 7.14%   |
| Oracle Linux 7.4 | 1        | 7.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Oracle Linux | 14       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Desktops | Percent |
|-----------------------------------|----------|---------|
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2        | 13.33%  |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2        | 13.33%  |
| 5.4.17-2136.310.7.1.el8uek.x86_64 | 1        | 6.67%   |
| 5.4.17-2136.308.9.el8uek.x86_64   | 1        | 6.67%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64 | 1        | 6.67%   |
| 5.4.17-2102.202.5.el8uek.x86_64   | 1        | 6.67%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 1        | 6.67%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64 | 1        | 6.67%   |
| 5.4.11-1.el7.elrepo.x86_64        | 1        | 6.67%   |
| 5.15.0-2.52.3.el9uek.x86_64       | 1        | 6.67%   |
| 4.18.0-372.16.1.0.2.el8_6.x86_64  | 1        | 6.67%   |
| 4.18.0-240.15.1.el8_3.x86_64      | 1        | 6.67%   |
| 3.10.0-693.11.6.el7.x86_64        | 1        | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.17  | 9        | 64.29%  |
| 4.18.0  | 2        | 14.29%  |
| 5.4.11  | 1        | 7.14%   |
| 5.15.0  | 1        | 7.14%   |
| 3.10.0  | 1        | 7.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 10       | 71.43%  |
| 4.18    | 2        | 14.29%  |
| 5.15    | 1        | 7.14%   |
| 3.10    | 1        | 7.14%   |

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


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 10       | 71.43%  |
| Unknown       | 3        | 21.43%  |
| GNOME Classic | 1        | 7.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 8        | 57.14%  |
| X11     | 4        | 28.57%  |
| Unknown | 2        | 14.29%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 71.43%  |
| GDM     | 3        | 21.43%  |
| TDM     | 1        | 7.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 6        | 42.86%  |
| ru_RU      | 1        | 7.14%   |
| pl_PL      | 1        | 7.14%   |
| it_IT      | 1        | 7.14%   |
| en_US.UTF8 | 1        | 7.14%   |
| en_IN      | 1        | 7.14%   |
| en_GB      | 1        | 7.14%   |
| de_DE      | 1        | 7.14%   |
| Unknown    | 1        | 7.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 7        | 50%     |
| EFI  | 7        | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 12       | 85.71%  |
| Ext4 | 2        | 14.29%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 57.14%  |
| MBR     | 3        | 21.43%  |
| GPT     | 3        | 21.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 92.86%  |
| Yes       | 1        | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 5        | 35.71%  |
| Gigabyte Technology | 3        | 21.43%  |
| ASUSTek Computer    | 3        | 21.43%  |
| MSI                 | 1        | 7.14%   |
| Hewlett-Packard     | 1        | 7.14%   |
| Foxconn             | 1        | 7.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7758                      | 1        | 7.14%   |
| HP Z820 Workstation              | 1        | 7.14%   |
| Gigabyte Z490 AORUS ELITE AC     | 1        | 7.14%   |
| Gigabyte X99-Designare EX-CF     | 1        | 7.14%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 7.14%   |
| Foxconn p6-2400el                | 1        | 7.14%   |
| Dell PowerEdge FC630             | 1        | 7.14%   |
| Dell OptiPlex 980                | 1        | 7.14%   |
| Dell OptiPlex 7090               | 1        | 7.14%   |
| Dell OptiPlex 7060               | 1        | 7.14%   |
| Dell OptiPlex 5000               | 1        | 7.14%   |
| ASUS P8H67                       | 1        | 7.14%   |
| ASUS G11CD                       | 1        | 7.14%   |
| ASUS All Series                  | 1        | 7.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 4        | 28.57%  |
| MSI MS-7758            | 1        | 7.14%   |
| HP Z820                | 1        | 7.14%   |
| Gigabyte Z490          | 1        | 7.14%   |
| Gigabyte X99-Designare | 1        | 7.14%   |
| Gigabyte X470          | 1        | 7.14%   |
| Foxconn p6-2400el      | 1        | 7.14%   |
| Dell PowerEdge         | 1        | 7.14%   |
| ASUS P8H67             | 1        | 7.14%   |
| ASUS G11CD             | 1        | 7.14%   |
| ASUS All               | 1        | 7.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 3        | 21.43%  |
| 2012 | 3        | 21.43%  |
| 2016 | 2        | 14.29%  |
| 2010 | 2        | 14.29%  |
| 2022 | 1        | 7.14%   |
| 2021 | 1        | 7.14%   |
| 2020 | 1        | 7.14%   |
| 2013 | 1        | 7.14%   |

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


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 4        | 28.57%  |
| 4.01-8.0        | 2        | 14.29%  |
| 32.01-64.0      | 2        | 14.29%  |
| 64.01-256.0     | 2        | 14.29%  |
| More than 256.0 | 1        | 7.14%   |
| 24.01-32.0      | 1        | 7.14%   |
| 16.01-24.0      | 1        | 7.14%   |
| 1.01-2.0        | 1        | 7.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 4        | 26.67%  |
| 2.01-3.0   | 4        | 26.67%  |
| 3.01-4.0   | 2        | 13.33%  |
| 1.01-2.0   | 2        | 13.33%  |
| 16.01-24.0 | 1        | 6.67%   |
| 8.01-16.0  | 1        | 6.67%   |
| 0.01-0.5   | 1        | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 50%     |
| 2      | 3        | 21.43%  |
| 3      | 2        | 14.29%  |
| 5      | 1        | 7.14%   |
| 4      | 1        | 7.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 8        | 57.14%  |
| Yes       | 6        | 42.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 92.86%  |
| No        | 1        | 7.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 64.29%  |
| Yes       | 5        | 35.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 64.29%  |
| Yes       | 5        | 35.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Germany   | 3        | 21.43%  |
| USA       | 2        | 14.29%  |
| Russia    | 2        | 14.29%  |
| UK        | 1        | 7.14%   |
| Romania   | 1        | 7.14%   |
| Poland    | 1        | 7.14%   |
| Italy     | 1        | 7.14%   |
| India     | 1        | 7.14%   |
| Bolivia   | 1        | 7.14%   |
| Australia | 1        | 7.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Weaverville     | 1        | 6.67%   |
| Warsaw          | 1        | 6.67%   |
| Veliky Novgorod | 1        | 6.67%   |
| Santa Cruz      | 1        | 6.67%   |
| Riverside       | 1        | 6.67%   |
| Reading         | 1        | 6.67%   |
| Neunkirchen     | 1        | 6.67%   |
| Moscow          | 1        | 6.67%   |
| Langgons        | 1        | 6.67%   |
| Bucharest       | 1        | 6.67%   |
| Berlin          | 1        | 6.67%   |
| Bengaluru       | 1        | 6.67%   |
| Asheville       | 1        | 6.67%   |
| Albairate       | 1        | 6.67%   |
| Adelaide        | 1        | 6.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 45     | 35%     |
| Samsung Electronics | 3        | 4      | 15%     |
| WDC                 | 2        | 2      | 10%     |
| Toshiba             | 2        | 2      | 10%     |
| Kingston            | 2        | 3      | 10%     |
| SK hynix            | 1        | 1      | 5%      |
| Phison              | 1        | 1      | 5%      |
| Hewlett-Packard     | 1        | 1      | 5%      |
| Crucial             | 1        | 1      | 5%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB   | 2        | 8.33%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 8.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 4.17%   |
| WDC WD10EZEX-60M2NA0 1TB         | 1        | 4.17%   |
| Toshiba NVMe SSD Drive 512GB     | 1        | 4.17%   |
| Toshiba MG04ACA200E 2TB          | 1        | 4.17%   |
| SK hynix PC801 NVMe 512GB        | 1        | 4.17%   |
| Seagate ST8000VN004-2M2101 8TB   | 1        | 4.17%   |
| Seagate ST3750528AS 752GB        | 1        | 4.17%   |
| Seagate ST3500414CS 500GB        | 1        | 4.17%   |
| Seagate ST2000NX0253 2TB         | 1        | 4.17%   |
| Seagate ST2000DM001-1ER164 2TB   | 1        | 4.17%   |
| Seagate ST1000NX0423 1TB         | 1        | 4.17%   |
| Seagate ST1000LM010-9YH146 1TB   | 1        | 4.17%   |
| Samsung SSD PM830 2.5 7mm 256GB  | 1        | 4.17%   |
| Samsung SSD 960 EVO 250GB        | 1        | 4.17%   |
| Samsung SSD 860 EVO 250GB        | 1        | 4.17%   |
| Samsung HD502IJ 500GB            | 1        | 4.17%   |
| Phison NVMe SSD Drive 1TB        | 1        | 4.17%   |
| Kingston SUV400S37240G 240GB SSD | 1        | 4.17%   |
| HP SSD S700 120GB                | 1        | 4.17%   |
| Crucial CT500MX500SSD1 500GB     | 1        | 4.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 45     | 70%     |
| WDC                 | 1        | 1      | 10%     |
| Toshiba             | 1        | 1      | 10%     |
| Samsung Electronics | 1        | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 28.57%  |
| Kingston            | 2        | 3      | 28.57%  |
| WDC                 | 1        | 1      | 14.29%  |
| Hewlett-Packard     | 1        | 1      | 14.29%  |
| Crucial             | 1        | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 48     | 45%     |
| SSD  | 7        | 8      | 35%     |
| NVMe | 4        | 4      | 20%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 13       | 56     | 76.47%  |
| NVMe | 4        | 4      | 23.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 8        | 10     | 47.06%  |
| 1.01-2.0   | 5        | 39     | 29.41%  |
| 0.51-1.0   | 3        | 5      | 17.65%  |
| 4.01-10.0  | 1        | 2      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 4        | 28.57%  |
| 101-250        | 3        | 21.43%  |
| 1001-2000      | 2        | 14.29%  |
| More than 3000 | 1        | 7.14%   |
| 21-50          | 1        | 7.14%   |
| 2001-3000      | 1        | 7.14%   |
| 501-1000       | 1        | 7.14%   |
| Unknown        | 1        | 7.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 5        | 35.71%  |
| 101-250        | 4        | 28.57%  |
| 1-20           | 3        | 21.43%  |
| More than 3000 | 1        | 7.14%   |
| Unknown        | 1        | 7.14%   |

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
| Detected | 8        | 17     | 57.14%  |
| Works    | 5        | 42     | 35.71%  |
| Malfunc  | 1        | 1      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 13       | 61.9%   |
| Broadcom / LSI               | 2        | 9.52%   |
| VIA Technologies             | 1        | 4.76%   |
| Toshiba America Info Systems | 1        | 4.76%   |
| SK hynix                     | 1        | 4.76%   |
| Samsung Electronics          | 1        | 4.76%   |
| Phison Electronics           | 1        | 4.76%   |
| AMD                          | 1        | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 7.41%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 7.41%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 3.7%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1        | 3.7%    |
| SK hynix Non-Volatile memory controller                                                 | 1        | 3.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 3.7%    |
| Phison E12 NVMe Controller                                                              | 1        | 3.7%    |
| Intel SATA Controller [RAID mode]                                                       | 1        | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 3.7%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 3.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 3.7%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 3.7%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 3.7%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 3.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 3.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 3.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 3.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1        | 3.7%    |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 3.7%    |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 1        | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1        | 3.7%    |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 52.38%  |
| NVMe | 4        | 19.05%  |
| RAID | 3        | 14.29%  |
| IDE  | 2        | 9.52%   |
| SAS  | 1        | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 92.86%  |
| AMD    | 1        | 7.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 7.14%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 1        | 7.14%   |
| Intel Pentium CPU G2020 @ 2.90GHz      | 1        | 7.14%   |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 7.14%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 7.14%   |
| Intel Core i7-6800K CPU @ 3.40GHz      | 1        | 7.14%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 7.14%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 7.14%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 7.14%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 7.14%   |
| Intel Core i5-10500 CPU @ 3.10GHz      | 1        | 7.14%   |
| Intel Core i3 CPU 550 @ 3.20GHz        | 1        | 7.14%   |
| Intel 12th Gen Core i7-12700           | 1        | 7.14%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 1        | 7.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i7 | 5        | 35.71%  |
| Intel Xeon    | 2        | 14.29%  |
| Intel Core i5 | 2        | 14.29%  |
| Other         | 1        | 7.14%   |
| Intel Pentium | 1        | 7.14%   |
| Intel Core i9 | 1        | 7.14%   |
| Intel Core i3 | 1        | 7.14%   |
| AMD Ryzen 7   | 1        | 7.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 4        | 28.57%  |
| 6      | 3        | 21.43%  |
| 16     | 2        | 14.29%  |
| 2      | 2        | 14.29%  |
| 12     | 1        | 7.14%   |
| 10     | 1        | 7.14%   |
| 8      | 1        | 7.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 85.71%  |
| 2      | 2        | 14.29%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 85.71%  |
| 1      | 2        | 14.29%  |

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
| 0x306a9    | 2        | 14.29%  |
| Unknown    | 2        | 14.29%  |
| 0xa0655    | 1        | 7.14%   |
| 0xa0653    | 1        | 7.14%   |
| 0x906ea    | 1        | 7.14%   |
| 0x506e3    | 1        | 7.14%   |
| 0x406f1    | 1        | 7.14%   |
| 0x306e4    | 1        | 7.14%   |
| 0x306c3    | 1        | 7.14%   |
| 0x206a7    | 1        | 7.14%   |
| 0x20655    | 1        | 7.14%   |
| 0x0800820d | 1        | 7.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 3        | 21.43%  |
| CometLake   | 2        | 14.29%  |
| Broadwell   | 2        | 14.29%  |
| Zen+        | 1        | 7.14%   |
| Westmere    | 1        | 7.14%   |
| Skylake     | 1        | 7.14%   |
| SandyBridge | 1        | 7.14%   |
| KabyLake    | 1        | 7.14%   |
| Haswell     | 1        | 7.14%   |
| Unknown     | 1        | 7.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 7        | 43.75%  |
| Intel                      | 7        | 43.75%  |
| Matrox Electronics Systems | 1        | 6.25%   |
| AMD                        | 1        | 6.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 12.5%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 6.25%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 6.25%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 6.25%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 6.25%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 6.25%   |
| Nvidia GK110GL [Quadro K6000]                                               | 1        | 6.25%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 6.25%   |
| Matrox Electronics Systems G200eR2                                          | 1        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 6.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 6.25%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 6.25%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 6.25%   |
| Intel AlderLake-S GT1                                                       | 1        | 6.25%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 1        | 6.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 7        | 50%     |
| 1 x Intel  | 5        | 35.71%  |
| 1 x Matrox | 1        | 7.14%   |
| 1 x AMD    | 1        | 7.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 11       | 78.57%  |
| Unknown     | 2        | 14.29%  |
| Proprietary | 1        | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 50%     |
| 3.01-4.0   | 3        | 21.43%  |
| 1.01-2.0   | 2        | 14.29%  |
| 5.01-6.0   | 1        | 7.14%   |
| 8.01-16.0  | 1        | 7.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 30.77%  |
| Dell                | 3        | 23.08%  |
| Hewlett-Packard     | 2        | 15.38%  |
| SAC                 | 1        | 7.69%   |
| Goldstar            | 1        | 7.69%   |
| Eizo                | 1        | 7.69%   |
| BenQ                | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch | 1        | 6.67%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 600x340mm 27.2-inch   | 1        | 6.67%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch   | 1        | 6.67%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch   | 1        | 6.67%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch   | 1        | 6.67%   |
| Samsung Electronics LCD Monitor S24C650                             | 1        | 6.67%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch               | 1        | 6.67%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch          | 1        | 6.67%   |
| Hewlett-Packard E273q HPN3474 2560x1440 600x340mm 27.2-inch         | 1        | 6.67%   |
| Goldstar E2240 GSM57A3 1920x1080 477x268mm 21.5-inch                | 1        | 6.67%   |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                   | 1        | 6.67%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                   | 1        | 6.67%   |
| Dell LCD Monitor U2415 3840x1200                                    | 1        | 6.67%   |
| Dell IDRAC DEL0001 1280x1024                                        | 1        | 6.67%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                   | 1        | 6.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 7        | 53.85%  |
| 3840x1200         | 1        | 7.69%   |
| 2560x1440 (QHD)   | 1        | 7.69%   |
| 1920x1200 (WUXGA) | 1        | 7.69%   |
| 1360x768          | 1        | 7.69%   |
| 1280x1024 (SXGA)  | 1        | 7.69%   |
| Unknown           | 1        | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 3        | 23.08%  |
| 21      | 3        | 23.08%  |
| 27      | 2        | 15.38%  |
| 23      | 2        | 15.38%  |
| Unknown | 2        | 15.38%  |
| 18      | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 53.85%  |
| 401-500     | 4        | 30.77%  |
| Unknown     | 2        | 15.38%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 9        | 75%     |
| 5/4     | 1        | 8.33%   |
| 16/10   | 1        | 8.33%   |
| Unknown | 1        | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 50%     |
| 301-350        | 2        | 16.67%  |
| Unknown        | 2        | 16.67%  |
| 251-300        | 1        | 8.33%   |
| 141-150        | 1        | 8.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 7        | 53.85%  |
| 101-120 | 4        | 30.77%  |
| Unknown | 2        | 15.38%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 71.43%  |
| 2     | 3        | 21.43%  |
| 0     | 1        | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 44.44%  |
| Realtek Semiconductor | 6        | 33.33%  |
| Broadcom              | 2        | 11.11%  |
| Qualcomm Atheros      | 1        | 5.56%   |
| QLogic                | 1        | 5.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 18.18%  |
| Intel Wireless 8260                                               | 2        | 9.09%   |
| Intel I211 Gigabit Network Connection                             | 2        | 9.09%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 4.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 4.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 4.55%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1        | 4.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 4.55%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4.55%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 4.55%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 4.55%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4.55%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 4.55%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 4.55%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 4.55%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 4.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 60%     |
| Realtek Semiconductor | 1        | 20%     |
| Qualcomm Atheros      | 1        | 20%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wireless 8260                                            | 2        | 40%     |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 20%     |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 20%     |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 20%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 46.67%  |
| Realtek Semiconductor | 5        | 33.33%  |
| Broadcom              | 2        | 13.33%  |
| QLogic                | 1        | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 23.53%  |
| Intel I211 Gigabit Network Connection                             | 2        | 11.76%  |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 5.88%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1        | 5.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 5.88%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 5.88%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 5.88%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 5.88%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 5.88%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 5.88%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 5.88%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 5.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 72.22%  |
| WiFi     | 5        | 27.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 85.71%  |
| WiFi     | 2        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 7        | 50%     |
| 2     | 5        | 35.71%  |
| 4     | 1        | 7.14%   |
| 3     | 1        | 7.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 92.86%  |
| Yes  | 1        | 7.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 3        | 50%     |
| IMC Networks     | 1        | 16.67%  |
| Broadcom         | 1        | 16.67%  |
| ASUSTek Computer | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface             | 2        | 33.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 1        | 16.67%  |
| IMC Networks Bluetooth Radio                   | 1        | 16.67%  |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1        | 16.67%  |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 11       | 57.89%  |
| Nvidia | 6        | 31.58%  |
| AMD    | 2        | 10.53%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 10%     |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 5%      |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 5%      |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 5%      |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 5%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 5%      |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 5%      |
| Intel Comet Lake PCH cAVS                                                  | 1        | 5%      |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 5%      |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 5%      |
| Intel Audio device                                                         | 1        | 5%      |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 5%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 5%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 5%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 5%      |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 5%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 5%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Micron Technology | 3        | 50%     |
| Kingston          | 2        | 33.33%  |
| Crucial           | 1        | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2400MT/s        | 1        | 11.11%  |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s        | 1        | 11.11%  |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2400MT/s        | 1        | 11.11%  |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s        | 1        | 11.11%  |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s     | 1        | 11.11%  |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s            | 1        | 11.11%  |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 11.11%  |
| Kingston RAM 9905403-892.A00LF 8GB DIMM DDR3 1333MT/s     | 1        | 11.11%  |
| Crucial RAM BLE8G4D34AEEAK.K8FB 8192MB DIMM DDR4 3466MT/s | 1        | 11.11%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 4        | 66.67%  |
| DDR3 | 2        | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 6        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 4        | 57.14%  |
| 16384 | 1        | 14.29%  |
| 4096  | 1        | 14.29%  |
| 1024  | 1        | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 2        | 33.33%  |
| 1333  | 2        | 33.33%  |
| 3466  | 1        | 16.67%  |
| 3200  | 1        | 16.67%  |

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
| Microdia | 1        | 50%     |
| Logitech | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Microdia Webcam Vitade AF | 1        | 50%     |
| Logitech Webcam C270      | 1        | 50%     |

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
| 0     | 9        | 64.29%  |
| 2     | 3        | 21.43%  |
| 1     | 2        | 14.29%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unassigned class         | 2        | 28.57%  |
| Graphics card            | 2        | 28.57%  |
| Net/wireless             | 1        | 14.29%  |
| Communication controller | 1        | 14.29%  |
| Bluetooth                | 1        | 14.29%  |

