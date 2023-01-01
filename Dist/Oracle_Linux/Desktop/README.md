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

Total: 16

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | PRIME B560M-A AC            | [d4cc718e46](https://linux-hardware.org/?probe=d4cc718e46) | Nov 29, 2022 |
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
| Oracle Linux 8.3 | 6        | 40%     |
| Oracle Linux 8.6 | 4        | 26.67%  |
| Oracle Linux 9.0 | 1        | 6.67%   |
| Oracle Linux 8.7 | 1        | 6.67%   |
| Oracle Linux 8.4 | 1        | 6.67%   |
| Oracle Linux 7.7 | 1        | 6.67%   |
| Oracle Linux 7.4 | 1        | 6.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Oracle Linux | 15       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Desktops | Percent |
|-----------------------------------|----------|---------|
| 5.4.17-2036.102.0.2.el8uek.x86_64 | 2        | 12.5%   |
| 5.4.17-2036.101.2.el8uek.x86_64   | 2        | 12.5%   |
| 5.4.17-2136.313.6.el8uek.x86_64   | 1        | 6.25%   |
| 5.4.17-2136.310.7.1.el8uek.x86_64 | 1        | 6.25%   |
| 5.4.17-2136.308.9.el8uek.x86_64   | 1        | 6.25%   |
| 5.4.17-2136.307.3.1.el8uek.x86_64 | 1        | 6.25%   |
| 5.4.17-2102.202.5.el8uek.x86_64   | 1        | 6.25%   |
| 5.4.17-2102.200.13.el8uek.x86_64  | 1        | 6.25%   |
| 5.4.17-2036.100.6.1.el8uek.x86_64 | 1        | 6.25%   |
| 5.4.11-1.el7.elrepo.x86_64        | 1        | 6.25%   |
| 5.15.0-2.52.3.el9uek.x86_64       | 1        | 6.25%   |
| 4.18.0-372.16.1.0.2.el8_6.x86_64  | 1        | 6.25%   |
| 4.18.0-240.15.1.el8_3.x86_64      | 1        | 6.25%   |
| 3.10.0-693.11.6.el7.x86_64        | 1        | 6.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.17  | 10       | 66.67%  |
| 4.18.0  | 2        | 13.33%  |
| 5.4.11  | 1        | 6.67%   |
| 5.15.0  | 1        | 6.67%   |
| 3.10.0  | 1        | 6.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 11       | 73.33%  |
| 4.18    | 2        | 13.33%  |
| 5.15    | 1        | 6.67%   |
| 3.10    | 1        | 6.67%   |

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


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 11       | 73.33%  |
| Unknown       | 3        | 20%     |
| GNOME Classic | 1        | 6.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 9        | 60%     |
| X11     | 4        | 26.67%  |
| Unknown | 2        | 13.33%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 73.33%  |
| GDM     | 3        | 20%     |
| TDM     | 1        | 6.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 7        | 46.67%  |
| ru_RU      | 1        | 6.67%   |
| pl_PL      | 1        | 6.67%   |
| it_IT      | 1        | 6.67%   |
| en_US.UTF8 | 1        | 6.67%   |
| en_IN      | 1        | 6.67%   |
| en_GB      | 1        | 6.67%   |
| de_DE      | 1        | 6.67%   |
| Unknown    | 1        | 6.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 8        | 53.33%  |
| BIOS | 7        | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Xfs  | 12       | 80%     |
| Ext4 | 2        | 13.33%  |
| Zfs  | 1        | 6.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 9        | 60%     |
| MBR     | 3        | 20%     |
| GPT     | 3        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 93.33%  |
| Yes       | 1        | 6.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 5        | 33.33%  |
| ASUSTek Computer    | 4        | 26.67%  |
| Gigabyte Technology | 3        | 20%     |
| MSI                 | 1        | 6.67%   |
| Hewlett-Packard     | 1        | 6.67%   |
| Foxconn             | 1        | 6.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7758                      | 1        | 6.67%   |
| HP Z820 Workstation              | 1        | 6.67%   |
| Gigabyte Z490 AORUS ELITE AC     | 1        | 6.67%   |
| Gigabyte X99-Designare EX-CF     | 1        | 6.67%   |
| Gigabyte X470 AORUS ULTRA GAMING | 1        | 6.67%   |
| Foxconn p6-2400el                | 1        | 6.67%   |
| Dell PowerEdge FC630             | 1        | 6.67%   |
| Dell OptiPlex 980                | 1        | 6.67%   |
| Dell OptiPlex 7090               | 1        | 6.67%   |
| Dell OptiPlex 7060               | 1        | 6.67%   |
| Dell OptiPlex 5000               | 1        | 6.67%   |
| ASUS PRIME B560M-A AC            | 1        | 6.67%   |
| ASUS P8H67                       | 1        | 6.67%   |
| ASUS G11CD                       | 1        | 6.67%   |
| ASUS All Series                  | 1        | 6.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 4        | 26.67%  |
| MSI MS-7758            | 1        | 6.67%   |
| HP Z820                | 1        | 6.67%   |
| Gigabyte Z490          | 1        | 6.67%   |
| Gigabyte X99-Designare | 1        | 6.67%   |
| Gigabyte X470          | 1        | 6.67%   |
| Foxconn p6-2400el      | 1        | 6.67%   |
| Dell PowerEdge         | 1        | 6.67%   |
| ASUS PRIME             | 1        | 6.67%   |
| ASUS P8H67             | 1        | 6.67%   |
| ASUS G11CD             | 1        | 6.67%   |
| ASUS All               | 1        | 6.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 3        | 20%     |
| 2012 | 3        | 20%     |
| 2021 | 2        | 13.33%  |
| 2016 | 2        | 13.33%  |
| 2010 | 2        | 13.33%  |
| 2022 | 1        | 6.67%   |
| 2020 | 1        | 6.67%   |
| 2013 | 1        | 6.67%   |

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


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 4        | 26.67%  |
| 64.01-256.0     | 3        | 20%     |
| 4.01-8.0        | 2        | 13.33%  |
| 32.01-64.0      | 2        | 13.33%  |
| More than 256.0 | 1        | 6.67%   |
| 24.01-32.0      | 1        | 6.67%   |
| 16.01-24.0      | 1        | 6.67%   |
| 1.01-2.0        | 1        | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 5        | 31.25%  |
| 2.01-3.0   | 4        | 25%     |
| 3.01-4.0   | 2        | 12.5%   |
| 1.01-2.0   | 2        | 12.5%   |
| 16.01-24.0 | 1        | 6.25%   |
| 8.01-16.0  | 1        | 6.25%   |
| 0.01-0.5   | 1        | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 46.67%  |
| 2      | 3        | 20%     |
| 3      | 2        | 13.33%  |
| 6      | 1        | 6.67%   |
| 5      | 1        | 6.67%   |
| 4      | 1        | 6.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 60%     |
| Yes       | 6        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 93.33%  |
| No        | 1        | 6.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 60%     |
| Yes       | 6        | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 60%     |
| Yes       | 6        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 3        | 20%     |
| Germany   | 3        | 20%     |
| Russia    | 2        | 13.33%  |
| UK        | 1        | 6.67%   |
| Romania   | 1        | 6.67%   |
| Poland    | 1        | 6.67%   |
| Italy     | 1        | 6.67%   |
| India     | 1        | 6.67%   |
| Bolivia   | 1        | 6.67%   |
| Australia | 1        | 6.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Weaverville     | 1        | 6.25%   |
| Warsaw          | 1        | 6.25%   |
| Veliky Novgorod | 1        | 6.25%   |
| Santa Cruz      | 1        | 6.25%   |
| Riverside       | 1        | 6.25%   |
| Reading         | 1        | 6.25%   |
| Parker          | 1        | 6.25%   |
| Neunkirchen     | 1        | 6.25%   |
| Moscow          | 1        | 6.25%   |
| Langgons        | 1        | 6.25%   |
| Bucharest       | 1        | 6.25%   |
| Berlin          | 1        | 6.25%   |
| Bengaluru       | 1        | 6.25%   |
| Asheville       | 1        | 6.25%   |
| Albairate       | 1        | 6.25%   |
| Adelaide        | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 7        | 45     | 29.17%  |
| Samsung Electronics | 4        | 5      | 16.67%  |
| WDC                 | 2        | 2      | 8.33%   |
| Toshiba             | 2        | 2      | 8.33%   |
| Kingston            | 2        | 3      | 8.33%   |
| Crucial             | 2        | 2      | 8.33%   |
| SK hynix            | 1        | 1      | 4.17%   |
| SanDisk             | 1        | 3      | 4.17%   |
| Phison Electronics  | 1        | 1      | 4.17%   |
| Phison              | 1        | 1      | 4.17%   |
| Hewlett-Packard     | 1        | 1      | 4.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB   | 2        | 6.9%    |
| Kingston SA400S37240G 240GB SSD  | 2        | 6.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD | 1        | 3.45%   |
| WDC WD10EZEX-60M2NA0 1TB         | 1        | 3.45%   |
| Toshiba NVMe SSD Drive 512GB     | 1        | 3.45%   |
| Toshiba MG04ACA200E 2TB          | 1        | 3.45%   |
| SK hynix PC801 NVMe 512GB        | 1        | 3.45%   |
| Seagate ST8000VN004-2M2101 8TB   | 1        | 3.45%   |
| Seagate ST3750528AS 752GB        | 1        | 3.45%   |
| Seagate ST3500414CS 500GB        | 1        | 3.45%   |
| Seagate ST2000NX0253 2TB         | 1        | 3.45%   |
| Seagate ST2000DM001-1ER164 2TB   | 1        | 3.45%   |
| Seagate ST1000NX0423 1TB         | 1        | 3.45%   |
| Seagate ST1000LM010-9YH146 1TB   | 1        | 3.45%   |
| SanDisk SSD PLUS 2000GB          | 1        | 3.45%   |
| SanDisk SDSSDH32000G 2TB         | 1        | 3.45%   |
| Samsung SSD PM830 2.5 7mm 256GB  | 1        | 3.45%   |
| Samsung SSD 960 EVO 250GB        | 1        | 3.45%   |
| Samsung SSD 860 EVO 250GB        | 1        | 3.45%   |
| Samsung SSD 850 EVO 2TB          | 1        | 3.45%   |
| Samsung HD502IJ 500GB            | 1        | 3.45%   |
| Phison NVMe SSD Drive 1TB        | 1        | 3.45%   |
| Phison E12 NVMe Controller 1TB   | 1        | 3.45%   |
| Kingston SUV400S37240G 240GB SSD | 1        | 3.45%   |
| HP SSD S700 120GB                | 1        | 3.45%   |
| Crucial CT500MX500SSD1 500GB     | 1        | 3.45%   |
| Crucial CT2050MX300SSD1 2TB      | 1        | 3.45%   |

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
| Samsung Electronics | 3        | 3      | 30%     |
| Kingston            | 2        | 3      | 20%     |
| Crucial             | 2        | 2      | 20%     |
| WDC                 | 1        | 1      | 10%     |
| SanDisk             | 1        | 3      | 10%     |
| Hewlett-Packard     | 1        | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 48     | 40.91%  |
| SSD  | 8        | 13     | 36.36%  |
| NVMe | 5        | 5      | 22.73%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 61     | 73.68%  |
| NVMe | 5        | 5      | 26.32%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 8        | 10     | 44.44%  |
| 1.01-2.0   | 6        | 44     | 33.33%  |
| 0.51-1.0   | 3        | 5      | 16.67%  |
| 4.01-10.0  | 1        | 2      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 4        | 26.67%  |
| 101-250        | 3        | 20%     |
| 1001-2000      | 3        | 20%     |
| More than 3000 | 1        | 6.67%   |
| 21-50          | 1        | 6.67%   |
| 2001-3000      | 1        | 6.67%   |
| 501-1000       | 1        | 6.67%   |
| Unknown        | 1        | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 5        | 33.33%  |
| 101-250        | 5        | 33.33%  |
| 1-20           | 3        | 20%     |
| More than 3000 | 1        | 6.67%   |
| Unknown        | 1        | 6.67%   |

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
| Detected | 9        | 23     | 60%     |
| Works    | 5        | 42     | 33.33%  |
| Malfunc  | 1        | 1      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 14       | 60.87%  |
| Phison Electronics           | 2        | 8.7%    |
| Broadcom / LSI               | 2        | 8.7%    |
| VIA Technologies             | 1        | 4.35%   |
| Toshiba America Info Systems | 1        | 4.35%   |
| SK hynix                     | 1        | 4.35%   |
| Samsung Electronics          | 1        | 4.35%   |
| AMD                          | 1        | 4.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Phison E12 NVMe Controller                                                              | 2        | 6.9%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 6.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 6.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 6.9%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 3.45%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 1        | 3.45%   |
| SK hynix Non-Volatile memory controller                                                 | 1        | 3.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 3.45%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 3.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 3.45%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 3.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 3.45%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 3.45%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 3.45%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 1        | 3.45%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 3.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 3.45%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 3.45%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                            | 1        | 3.45%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1        | 3.45%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 12       | 52.17%  |
| NVMe | 5        | 21.74%  |
| RAID | 3        | 13.04%  |
| IDE  | 2        | 8.7%    |
| SAS  | 1        | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 93.33%  |
| AMD    | 1        | 6.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 6.67%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz    | 1        | 6.67%   |
| Intel Pentium CPU G2020 @ 2.90GHz      | 1        | 6.67%   |
| Intel Core i9-10900K CPU @ 3.70GHz     | 1        | 6.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 1        | 6.67%   |
| Intel Core i7-6800K CPU @ 3.40GHz      | 1        | 6.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 1        | 6.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz       | 1        | 6.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 1        | 6.67%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 6.67%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 1        | 6.67%   |
| Intel Core i5-10500 CPU @ 3.10GHz      | 1        | 6.67%   |
| Intel Core i3 CPU 550 @ 3.20GHz        | 1        | 6.67%   |
| Intel 12th Gen Core i7-12700           | 1        | 6.67%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 1        | 6.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| Intel Core i7 | 6        | 40%     |
| Intel Xeon    | 2        | 13.33%  |
| Intel Core i5 | 2        | 13.33%  |
| Other         | 1        | 6.67%   |
| Intel Pentium | 1        | 6.67%   |
| Intel Core i9 | 1        | 6.67%   |
| Intel Core i3 | 1        | 6.67%   |
| AMD Ryzen 7   | 1        | 6.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 4        | 26.67%  |
| 6      | 3        | 20%     |
| 16     | 2        | 13.33%  |
| 8      | 2        | 13.33%  |
| 2      | 2        | 13.33%  |
| 12     | 1        | 6.67%   |
| 10     | 1        | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 86.67%  |
| 2      | 2        | 13.33%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 13       | 86.67%  |
| 1      | 2        | 13.33%  |

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
| 0xa0655    | 2        | 13.33%  |
| 0x306a9    | 2        | 13.33%  |
| Unknown    | 2        | 13.33%  |
| 0xa0653    | 1        | 6.67%   |
| 0x906ea    | 1        | 6.67%   |
| 0x506e3    | 1        | 6.67%   |
| 0x406f1    | 1        | 6.67%   |
| 0x306e4    | 1        | 6.67%   |
| 0x306c3    | 1        | 6.67%   |
| 0x206a7    | 1        | 6.67%   |
| 0x20655    | 1        | 6.67%   |
| 0x0800820d | 1        | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| IvyBridge   | 3        | 20%     |
| CometLake   | 3        | 20%     |
| Broadwell   | 2        | 13.33%  |
| Zen+        | 1        | 6.67%   |
| Westmere    | 1        | 6.67%   |
| Skylake     | 1        | 6.67%   |
| SandyBridge | 1        | 6.67%   |
| KabyLake    | 1        | 6.67%   |
| Haswell     | 1        | 6.67%   |
| Unknown     | 1        | 6.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 8        | 44.44%  |
| Intel                      | 8        | 44.44%  |
| Matrox Electronics Systems | 1        | 5.56%   |
| AMD                        | 1        | 5.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 16.67%  |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 5.56%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 5.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 5.56%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 5.56%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 5.56%   |
| Nvidia GK110GL [Quadro K6000]                                               | 1        | 5.56%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 1        | 5.56%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 5.56%   |
| Matrox Electronics Systems G200eR2                                          | 1        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 5.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 5.56%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 5.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 5.56%   |
| Intel AlderLake-S GT1                                                       | 1        | 5.56%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 1        | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 7        | 46.67%  |
| 1 x Intel      | 5        | 33.33%  |
| 1 x Matrox     | 1        | 6.67%   |
| Intel + Nvidia | 1        | 6.67%   |
| 1 x AMD        | 1        | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 11       | 73.33%  |
| Proprietary | 2        | 13.33%  |
| Unknown     | 2        | 13.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 53.33%  |
| 3.01-4.0   | 3        | 20%     |
| 1.01-2.0   | 2        | 13.33%  |
| 5.01-6.0   | 1        | 6.67%   |
| 8.01-16.0  | 1        | 6.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 28.57%  |
| Dell                | 3        | 21.43%  |
| Hewlett-Packard     | 2        | 14.29%  |
| Viotek              | 1        | 7.14%   |
| SAC                 | 1        | 7.14%   |
| Goldstar            | 1        | 7.14%   |
| Eizo                | 1        | 7.14%   |
| BenQ                | 1        | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Viotek SUW49C VTK4900 3840x1080 1196x336mm 48.9-inch                | 1        | 6.25%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch | 1        | 6.25%   |
| Samsung Electronics S27D391 SAM0B89 1920x1080 600x340mm 27.2-inch   | 1        | 6.25%   |
| Samsung Electronics S27D391 SAM0B88 1920x1080 598x336mm 27.0-inch   | 1        | 6.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch   | 1        | 6.25%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch   | 1        | 6.25%   |
| Samsung Electronics LCD Monitor S24C650                             | 1        | 6.25%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch               | 1        | 6.25%   |
| Hewlett-Packard Z24i HWP309E 1920x1200 518x324mm 24.1-inch          | 1        | 6.25%   |
| Hewlett-Packard E273q HPN3474 2560x1440 597x336mm 27.0-inch         | 1        | 6.25%   |
| Goldstar E2240 GSM57A3 1920x1080 480x270mm 21.7-inch                | 1        | 6.25%   |
| Eizo EV2460 ENC3129 1920x1080 528x297mm 23.9-inch                   | 1        | 6.25%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                   | 1        | 6.25%   |
| Dell LCD Monitor U2415 3840x1200                                    | 1        | 6.25%   |
| Dell IDRAC DEL0001 1280x1024                                        | 1        | 6.25%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                   | 1        | 6.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 7        | 50%     |
| 3840x1200         | 1        | 7.14%   |
| 3840x1080         | 1        | 7.14%   |
| 2560x1440 (QHD)   | 1        | 7.14%   |
| 1920x1200 (WUXGA) | 1        | 7.14%   |
| 1360x768          | 1        | 7.14%   |
| 1280x1024 (SXGA)  | 1        | 7.14%   |
| Unknown           | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 3        | 21.43%  |
| 21      | 3        | 21.43%  |
| 27      | 2        | 14.29%  |
| 23      | 2        | 14.29%  |
| Unknown | 2        | 14.29%  |
| 48      | 1        | 7.14%   |
| 18      | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 50%     |
| 401-500     | 4        | 28.57%  |
| Unknown     | 2        | 14.29%  |
| 1001-1500   | 1        | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 9        | 69.23%  |
| 5/4     | 1        | 7.69%   |
| 32/9    | 1        | 7.69%   |
| 16/10   | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 46.15%  |
| 301-350        | 2        | 15.38%  |
| Unknown        | 2        | 15.38%  |
| 251-300        | 1        | 7.69%   |
| 141-150        | 1        | 7.69%   |
| 501-1000       | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 8        | 57.14%  |
| 101-120 | 4        | 28.57%  |
| Unknown | 2        | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 73.33%  |
| 2     | 3        | 20%     |
| 0     | 1        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 47.37%  |
| Realtek Semiconductor | 6        | 31.58%  |
| Broadcom              | 2        | 10.53%  |
| Qualcomm Atheros      | 1        | 5.26%   |
| QLogic                | 1        | 5.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 16.67%  |
| Intel Wireless 8260                                               | 2        | 8.33%   |
| Intel I211 Gigabit Network Connection                             | 2        | 8.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 4.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 4.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 4.17%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1        | 4.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1        | 4.17%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 4.17%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4.17%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 4.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 4.17%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 4.17%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1        | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 4.17%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 4.17%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 4.17%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 4.17%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 66.67%  |
| Realtek Semiconductor | 1        | 16.67%  |
| Qualcomm Atheros      | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wireless 8260                                            | 2        | 33.33%  |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 16.67%  |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 16.67%  |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1        | 16.67%  |
| Intel Comet Lake PCH CNVi WiFi                                 | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 50%     |
| Realtek Semiconductor | 5        | 31.25%  |
| Broadcom              | 2        | 12.5%   |
| QLogic                | 1        | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 22.22%  |
| Intel I211 Gigabit Network Connection                             | 2        | 11.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 5.56%   |
| QLogic FastLinQ QL41000 Series 10/25/40/50GbE Controller          | 1        | 5.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 5.56%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 5.56%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 5.56%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 5.56%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 5.56%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 5.56%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 5.56%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                | 1        | 5.56%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1        | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 70%     |
| WiFi     | 6        | 30%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 86.67%  |
| WiFi     | 2        | 13.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 7        | 46.67%  |
| 2     | 6        | 40%     |
| 4     | 1        | 6.67%   |
| 3     | 1        | 6.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 86.67%  |
| Yes  | 2        | 13.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 4        | 57.14%  |
| IMC Networks     | 1        | 14.29%  |
| Broadcom         | 1        | 14.29%  |
| ASUSTek Computer | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface             | 2        | 28.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2        | 28.57%  |
| IMC Networks Bluetooth Radio                   | 1        | 14.29%  |
| Broadcom BCM20702A0 Bluetooth 4.0              | 1        | 14.29%  |
| ASUS Broadcom BCM20702A0 Bluetooth             | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Intel     | 12       | 54.55%  |
| Nvidia    | 7        | 31.82%  |
| AMD       | 2        | 9.09%   |
| GN Netcom | 1        | 4.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Audio device                                                         | 2        | 8.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 8.7%    |
| Nvidia TU116 High Definition Audio Controller                              | 1        | 4.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 4.35%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 4.35%   |
| Nvidia GM204 High Definition Audio Controller                              | 1        | 4.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 4.35%   |
| Nvidia GK110 High Definition Audio Controller                              | 1        | 4.35%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 4.35%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 4.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 4.35%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1        | 4.35%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 4.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 4.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 4.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 4.35%   |
| GN Netcom Jabra EVOLVE LINK                                                | 1        | 4.35%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 4.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 4.35%   |

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
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s        | 1        | 11.11%  |
| Micron RAM 8ATF1G64AZ-2G3E1 8GB DIMM DDR4 2400MT/s        | 1        | 11.11%  |
| Micron RAM 8ATF1G64AZ-2G3B1 8GB DIMM DDR4 2448MT/s        | 1        | 11.11%  |
| Micron RAM 4ATF1G64AZ-3G2F1 8GB DIMM DDR4 3200MT/s        | 1        | 11.11%  |
| Micron RAM 18ASF2G72PDZ-2G3B1 16GB DIMM DDR4 2400MT/s     | 1        | 11.11%  |
| Kingston RAM KTW149-ELF 1GB DIMM DDR3 1333MT/s            | 1        | 11.11%  |
| Kingston RAM 9905471-006.A00LF 4096MB DIMM DDR3 1333MT/s  | 1        | 11.11%  |
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
| 2400  | 2        | 28.57%  |
| 1333  | 2        | 28.57%  |
| 3466  | 1        | 14.29%  |
| 3200  | 1        | 14.29%  |
| 2448  | 1        | 14.29%  |

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
| 0     | 10       | 66.67%  |
| 2     | 3        | 20%     |
| 1     | 2        | 13.33%  |

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

