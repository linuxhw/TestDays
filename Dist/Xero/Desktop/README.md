Xero - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for Xero.

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

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | P5Q PRO TURBO            | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| ASUSTek  | TUF GAMING B550M-PLUS    | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| HP       | 1906                     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek  | TUF GAMING X570-PLUS     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| ASUSTek  | TUF B360M-PLUS GAMING/BR | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| ASRock   | X570 Taichi              | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASRock   | X570 Taichi              | [3e4f21099d](https://linux-hardware.org/?probe=3e4f21099d) | Dec 17, 2021 |
| ASUSTek  | TUF GAMING X570-PLUS     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek  | PRIME A320M-K            | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| ASUSTek  | TUF Z390-PLUS GAMING     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI      | Z370 GAMING PLUS         | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Dell     | 0XC7MM A01               | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| ASRock   | B450M Pro4               | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock   | X570 Taichi              | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| ASRock   | X570 Taichi              | [203afc45fd](https://linux-hardware.org/?probe=203afc45fd) | Aug 29, 2021 |
| Gigabyte | X570 AORUS MASTER        | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock   | X570 Taichi              | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer     | FIH57                    | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Desktops | Percent |
|-------------------------|----------|---------|
| 5.16.1-arch1-1          | 1        | 6.25%   |
| 5.15.9-AMD              | 1        | 6.25%   |
| 5.15.4-arch1-1          | 1        | 6.25%   |
| 5.15.3-zen1-1-zen       | 1        | 6.25%   |
| 5.15.13-AMD             | 1        | 6.25%   |
| 5.15.12-zen1-1-zen      | 1        | 6.25%   |
| 5.15.12-arch1-1-surface | 1        | 6.25%   |
| 5.15.11-arch2-1-surface | 1        | 6.25%   |
| 5.14.9-zen2-1-zen       | 1        | 6.25%   |
| 5.14.8-zen1-1-zen       | 1        | 6.25%   |
| 5.14.15-zen1-1-zen      | 1        | 6.25%   |
| 5.14.14-arch1-1         | 1        | 6.25%   |
| 5.13.4-zen1-1-zen       | 1        | 6.25%   |
| 5.13.13-AMD             | 1        | 6.25%   |
| 5.12.5-AMD              | 1        | 6.25%   |
| 5.11.16-zen1-1-zen      | 1        | 6.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.12 | 2        | 12.5%   |
| 5.16.1  | 1        | 6.25%   |
| 5.15.9  | 1        | 6.25%   |
| 5.15.4  | 1        | 6.25%   |
| 5.15.3  | 1        | 6.25%   |
| 5.15.13 | 1        | 6.25%   |
| 5.15.11 | 1        | 6.25%   |
| 5.14.9  | 1        | 6.25%   |
| 5.14.8  | 1        | 6.25%   |
| 5.14.15 | 1        | 6.25%   |
| 5.14.14 | 1        | 6.25%   |
| 5.13.4  | 1        | 6.25%   |
| 5.13.13 | 1        | 6.25%   |
| 5.12.5  | 1        | 6.25%   |
| 5.11.16 | 1        | 6.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 6        | 40%     |
| 5.14    | 4        | 26.67%  |
| 5.13    | 2        | 13.33%  |
| 5.16    | 1        | 6.67%   |
| 5.12    | 1        | 6.67%   |
| 5.11    | 1        | 6.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 13       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| KDE5 | 12       | 92.31%  |
| XFCE | 1        | 7.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 10       | 76.92%  |
| Tty     | 2        | 15.38%  |
| Wayland | 1        | 7.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 8        | 61.54%  |
| Unknown | 3        | 23.08%  |
| TDM     | 1        | 7.69%   |
| LightDM | 1        | 7.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 7        | 53.85%  |
| en_IN | 1        | 7.69%   |
| en_GB | 1        | 7.69%   |
| en_CA | 1        | 7.69%   |
| en_AU | 1        | 7.69%   |
| de_AT | 1        | 7.69%   |
| C     | 1        | 7.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 7        | 53.85%  |
| EFI  | 6        | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 9        | 69.23%  |
| Ext4    | 3        | 23.08%  |
| Overlay | 1        | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 6        | 46.15%  |
| MBR     | 4        | 30.77%  |
| Unknown | 3        | 23.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 84.62%  |
| Yes       | 2        | 15.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 53.85%  |
| Yes       | 6        | 46.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 6        | 46.15%  |
| ASRock              | 2        | 15.38%  |
| MSI                 | 1        | 7.69%   |
| Hewlett-Packard     | 1        | 7.69%   |
| Gigabyte Technology | 1        | 7.69%   |
| Dell                | 1        | 7.69%   |
| Acer                | 1        | 7.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| MSI MS-7B61                   | 1        | 7.69%   |
| HP Z230 SFF Workstation       | 1        | 7.69%   |
| Gigabyte X570 AORUS MASTER    | 1        | 7.69%   |
| Dell Precision T1500          | 1        | 7.69%   |
| ASUS TUF Z390-PLUS GAMING     | 1        | 7.69%   |
| ASUS TUF GAMING X570-PLUS     | 1        | 7.69%   |
| ASUS TUF GAMING B550M-PLUS    | 1        | 7.69%   |
| ASUS TUF B360M-PLUS GAMING/BR | 1        | 7.69%   |
| ASUS PRIME A320M-K            | 1        | 7.69%   |
| ASUS P5Q PRO TURBO            | 1        | 7.69%   |
| ASRock X570 Taichi            | 1        | 7.69%   |
| ASRock B450M Pro4             | 1        | 7.69%   |
| Acer Aspire X5950             | 1        | 7.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| ASUS TUF       | 4        | 30.77%  |
| MSI MS-7B61    | 1        | 7.69%   |
| HP Z230        | 1        | 7.69%   |
| Gigabyte X570  | 1        | 7.69%   |
| Dell Precision | 1        | 7.69%   |
| ASUS PRIME     | 1        | 7.69%   |
| ASUS P5Q       | 1        | 7.69%   |
| ASRock X570    | 1        | 7.69%   |
| ASRock B450M   | 1        | 7.69%   |
| Acer Aspire    | 1        | 7.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 3        | 23.08%  |
| 2018 | 3        | 23.08%  |
| 2017 | 2        | 15.38%  |
| 2010 | 2        | 15.38%  |
| 2020 | 1        | 7.69%   |
| 2013 | 1        | 7.69%   |
| 2009 | 1        | 7.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 13       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 13       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 5        | 38.46%  |
| 32.01-64.0 | 4        | 30.77%  |
| 8.01-16.0  | 3        | 23.08%  |
| 4.01-8.0   | 1        | 7.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 4.01-8.0  | 5        | 33.33%  |
| 2.01-3.0  | 5        | 33.33%  |
| 8.01-16.0 | 2        | 13.33%  |
| 0.01-0.5  | 2        | 13.33%  |
| 3.01-4.0  | 1        | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 5        | 38.46%  |
| 3      | 3        | 23.08%  |
| 2      | 3        | 23.08%  |
| 6      | 2        | 15.38%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 76.92%  |
| Yes       | 3        | 23.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 8        | 61.54%  |
| No        | 5        | 38.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 7        | 53.85%  |
| Yes       | 6        | 46.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 4        | 30.77%  |
| Spain     | 1        | 7.69%   |
| Portugal  | 1        | 7.69%   |
| Lebanon   | 1        | 7.69%   |
| Italy     | 1        | 7.69%   |
| India     | 1        | 7.69%   |
| Canada    | 1        | 7.69%   |
| Brazil    | 1        | 7.69%   |
| Austria   | 1        | 7.69%   |
| Australia | 1        | 7.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Zell am See    | 1        | 7.69%   |
| Springfield    | 1        | 7.69%   |
| Salt Lake City | 1        | 7.69%   |
| Passos         | 1        | 7.69%   |
| Montreal       | 1        | 7.69%   |
| Melbourne      | 1        | 7.69%   |
| Longview       | 1        | 7.69%   |
| Lisbon         | 1        | 7.69%   |
| Granollers     | 1        | 7.69%   |
| Ernakulam      | 1        | 7.69%   |
| Chicago        | 1        | 7.69%   |
| Beirut         | 1        | 7.69%   |
| Bari           | 1        | 7.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 4        | 5      | 15.38%  |
| Seagate                   | 4        | 12     | 15.38%  |
| Samsung Electronics       | 3        | 12     | 11.54%  |
| SanDisk                   | 2        | 2      | 7.69%   |
| Kingston                  | 2        | 3      | 7.69%   |
| HGST                      | 2        | 2      | 7.69%   |
| XPG                       | 1        | 1      | 3.85%   |
| PNY                       | 1        | 1      | 3.85%   |
| Phison                    | 1        | 1      | 3.85%   |
| Micron/Crucial Technology | 1        | 1      | 3.85%   |
| Intel                     | 1        | 1      | 3.85%   |
| Hitachi                   | 1        | 1      | 3.85%   |
| China                     | 1        | 1      | 3.85%   |
| A-DATA Technology         | 1        | 1      | 3.85%   |
| 2-Power                   | 1        | 1      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung SSD 970 EVO 1TB           | 2        | 6.06%   |
| Kingston SA400S37240G 240GB SSD   | 2        | 6.06%   |
| XPG GAMMIX S50 2TB                | 1        | 3.03%   |
| WDC WD800JD-00MSA1 80GB           | 1        | 3.03%   |
| WDC WD7500BPKT-75PK4T0 752GB      | 1        | 3.03%   |
| WDC WD2500BEVT-60ZCT1 250GB       | 1        | 3.03%   |
| WDC WD10EZEX-22MFCA0 1TB          | 1        | 3.03%   |
| WDC WD1002FAEX-00Z3A0 1TB         | 1        | 3.03%   |
| Seagate ST3500418AS 500GB         | 1        | 3.03%   |
| Seagate ST250DM000-1BD141 250GB   | 1        | 3.03%   |
| Seagate ST2000DX001-1CM164 2TB    | 1        | 3.03%   |
| Seagate ST2000DM008-2FR102 2TB    | 1        | 3.03%   |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 3.03%   |
| Seagate ST2000DM001-1ER164 2TB    | 1        | 3.03%   |
| Seagate ST1000LM048-2E7172 1TB    | 1        | 3.03%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 3.03%   |
| SanDisk SDSSDH31024G 1024GB       | 1        | 3.03%   |
| Sandisk NVMe SSD Drive 500GB      | 1        | 3.03%   |
| Samsung SSD 980 PRO 2TB           | 1        | 3.03%   |
| Samsung SSD 960 EVO 250GB         | 1        | 3.03%   |
| Samsung SSD 860 EVO 1TB           | 1        | 3.03%   |
| PNY CS900 500GB SSD               | 1        | 3.03%   |
| Phison NVMe SSD Drive 240GB       | 1        | 3.03%   |
| Micron/Crucial NVMe SSD Drive 1TB | 1        | 3.03%   |
| Intel SSDPEKNW010T8 1TB           | 1        | 3.03%   |
| Hitachi HTS725050A9A364 500GB     | 1        | 3.03%   |
| HGST HTS545050A7E680 500GB        | 1        | 3.03%   |
| HGST HTS541010A9E680 1TB          | 1        | 3.03%   |
| China SATA3 240GB SSD             | 1        | 3.03%   |
| A-DATA SX6000LNP 512GB            | 1        | 3.03%   |
| 2-Power SSD2042A 240GB            | 1        | 3.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 5      | 36.36%  |
| Seagate | 4        | 12     | 36.36%  |
| HGST    | 2        | 2      | 18.18%  |
| Hitachi | 1        | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 2        | 3      | 28.57%  |
| SanDisk             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 3      | 14.29%  |
| PNY                 | 1        | 1      | 14.29%  |
| China               | 1        | 1      | 14.29%  |
| 2-Power             | 1        | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 20     | 42.86%  |
| NVMe | 7        | 15     | 33.33%  |
| SSD  | 5        | 10     | 23.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 11       | 30     | 61.11%  |
| NVMe | 7        | 15     | 38.89%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 6        | 9      | 37.5%   |
| 0.01-0.5   | 6        | 14     | 37.5%   |
| 1.01-2.0   | 4        | 7      | 25%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 4        | 30.77%  |
| 1001-2000      | 3        | 23.08%  |
| 501-1000       | 2        | 15.38%  |
| 251-500        | 1        | 7.69%   |
| 2001-3000      | 1        | 7.69%   |
| 1-20           | 1        | 7.69%   |
| 51-100         | 1        | 7.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 101-250   | 5        | 33.33%  |
| 1001-2000 | 3        | 20%     |
| 251-500   | 2        | 13.33%  |
| 1-20      | 2        | 13.33%  |
| 51-100    | 2        | 13.33%  |
| 2001-3000 | 1        | 6.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD1002FAEX-00Z3A0 1TB      | 1        | 1      | 25%     |
| Seagate ST2000DM006-2DM164 2TB | 1        | 1      | 25%     |
| Hitachi HTS725050A9A364 500GB  | 1        | 1      | 25%     |
| China SATA3 240GB SSD          | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |
| Hitachi | 1        | 1      | 25%     |
| China   | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |
| Hitachi | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 75%     |
| SSD  | 1        | 1      | 25%     |

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
| Works    | 10       | 31     | 58.82%  |
| Malfunc  | 4        | 4      | 23.53%  |
| Detected | 3        | 10     | 17.65%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 8        | 36.36%  |
| AMD                       | 6        | 27.27%  |
| Samsung Electronics       | 3        | 13.64%  |
| Sandisk                   | 1        | 4.55%   |
| Realtek Semiconductor     | 1        | 4.55%   |
| Phison Electronics        | 1        | 4.55%   |
| Micron/Crucial Technology | 1        | 4.55%   |
| ADATA Technology          | 1        | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                            | 5        | 20%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                  | 2        | 8%      |
| Intel SATA Controller [RAID mode]                              | 2        | 8%      |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller | 2        | 8%      |
| Sandisk WD Blue SN550 NVMe SSD                                 | 1        | 4%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                  | 1        | 4%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                 | 1        | 4%      |
| Realtek Realtek Non-Volatile memory controller                 | 1        | 4%      |
| Phison E12 NVMe Controller                                     | 1        | 4%      |
| Micron/Crucial P1 NVMe PCIe SSD                                | 1        | 4%      |
| Intel SSD 660P Series                                          | 1        | 4%      |
| Intel Cannon Lake PCH SATA AHCI Controller                     | 1        | 4%      |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller              | 1        | 4%      |
| Intel 200 Series PCH SATA controller [AHCI mode]               | 1        | 4%      |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]       | 1        | 4%      |
| AMD FCH SATA Controller D                                      | 1        | 4%      |
| AMD 400 Series Chipset SATA Controller                         | 1        | 4%      |
| ADATA Non-Volatile memory controller                           | 1        | 4%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 55%     |
| NVMe | 7        | 35%     |
| RAID | 2        | 10%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 53.85%  |
| AMD    | 6        | 46.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Genuine CPU 0000 @ 2.10GHz           | 1        | 7.69%   |
| Intel Core i7 CPU 870 @ 2.93GHz            | 1        | 7.69%   |
| Intel Core i5-9600K CPU @ 3.70GHz          | 1        | 7.69%   |
| Intel Core i5-9400F CPU @ 2.90GHz          | 1        | 7.69%   |
| Intel Core i5-4670 CPU @ 3.40GHz           | 1        | 7.69%   |
| Intel Core i3 CPU 540 @ 3.07GHz            | 1        | 7.69%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz      | 1        | 7.69%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 1        | 7.69%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 1        | 7.69%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 1        | 7.69%   |
| AMD Ryzen 5 3600X 6-Core Processor         | 1        | 7.69%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 1        | 7.69%   |
| AMD Athlon 200GE with Radeon Vega Graphics | 1        | 7.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 3        | 23.08%  |
| AMD Ryzen 5       | 3        | 23.08%  |
| Intel Genuine     | 1        | 7.69%   |
| Intel Core i7     | 1        | 7.69%   |
| Intel Core i3     | 1        | 7.69%   |
| Intel Core 2 Quad | 1        | 7.69%   |
| AMD Ryzen 9       | 1        | 7.69%   |
| AMD Ryzen 7       | 1        | 7.69%   |
| AMD Athlon        | 1        | 7.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 5        | 38.46%  |
| 4      | 3        | 23.08%  |
| 8      | 2        | 15.38%  |
| 2      | 2        | 15.38%  |
| 12     | 1        | 7.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 69.23%  |
| 1      | 4        | 30.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 13       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 23.08%  |
| 0x0a201016 | 2        | 15.38%  |
| 0x906ed    | 1        | 7.69%   |
| 0x906ea    | 1        | 7.69%   |
| 0x306c3    | 1        | 7.69%   |
| 0x20655    | 1        | 7.69%   |
| 0x1067a    | 1        | 7.69%   |
| 0x08701021 | 1        | 7.69%   |
| 0x08701013 | 1        | 7.69%   |
| 0x0810100b | 1        | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KabyLake | 3        | 23.08%  |
| Zen 3    | 2        | 15.38%  |
| Zen 2    | 2        | 15.38%  |
| Zen+     | 1        | 7.69%   |
| Zen      | 1        | 7.69%   |
| Westmere | 1        | 7.69%   |
| Penryn   | 1        | 7.69%   |
| Nehalem  | 1        | 7.69%   |
| Haswell  | 1        | 7.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 7        | 53.85%  |
| AMD    | 5        | 38.46%  |
| Intel  | 1        | 7.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Nvidia GP104 [GeForce GTX 1080]                                  | 2        | 15.38%  |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]          | 2        | 15.38%  |
| Nvidia TU117 [GeForce GTX 1650]                                  | 1        | 7.69%   |
| Nvidia GP108 [GeForce GT 1030]                                   | 1        | 7.69%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                              | 1        | 7.69%   |
| Nvidia GK107 [GeForce GT 740]                                    | 1        | 7.69%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                   | 1        | 7.69%   |
| Intel Core Processor Integrated Graphics Controller              | 1        | 7.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series] | 1        | 7.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]          | 1        | 7.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                 | 1        | 7.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 7        | 53.85%  |
| 1 x AMD    | 5        | 38.46%  |
| 1 x Intel  | 1        | 7.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Proprietary | 6        | 46.15%  |
| Free        | 6        | 46.15%  |
| Unknown     | 1        | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 7.01-8.0   | 4        | 30.77%  |
| Unknown    | 4        | 30.77%  |
| 1.01-2.0   | 2        | 15.38%  |
| 5.01-6.0   | 1        | 7.69%   |
| 3.01-4.0   | 1        | 7.69%   |
| 8.01-16.0  | 1        | 7.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 3        | 18.75%  |
| Hewlett-Packard      | 2        | 12.5%   |
| Goldstar             | 2        | 12.5%   |
| AOC                  | 2        | 12.5%   |
| Kogan                | 1        | 6.25%   |
| KOC                  | 1        | 6.25%   |
| Idek Iiyama          | 1        | 6.25%   |
| Gigabyte Technology  | 1        | 6.25%   |
| ASUSTek Computer     | 1        | 6.25%   |
| Ancor Communications | 1        | 6.25%   |
| Acer                 | 1        | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch  | 1        | 5.88%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1        | 5.88%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1        | 5.88%   |
| Kogan KAMN34FXQULA KGN3400 3440x1440 797x334mm 34.0-inch              | 1        | 5.88%   |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch               | 1        | 5.88%   |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                             | 1        | 5.88%   |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch           | 1        | 5.88%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch             | 1        | 5.88%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 1        | 5.88%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 1        | 5.88%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 1        | 5.88%   |
| ASUSTek Computer VG279QM AUS278F 1920x1080 598x336mm 27.0-inch        | 1        | 5.88%   |
| AOC 27G2G4 AOC2702 1920x1080 600x340mm 27.2-inch                      | 1        | 5.88%   |
| AOC 2460G5 AOC246A 1920x1080 530x300mm 24.0-inch                      | 1        | 5.88%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 1        | 5.88%   |
| Acer S240HL ACR0289 1920x1080 530x300mm 24.0-inch                     | 1        | 5.88%   |
| Acer G215H ACR0109 1920x1080 477x268mm 21.5-inch                      | 1        | 5.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 6        | 40%     |
| 2560x1440 (QHD)  | 4        | 26.67%  |
| 3840x2160 (4K)   | 2        | 13.33%  |
| 3440x1440        | 2        | 13.33%  |
| 1280x1024 (SXGA) | 1        | 6.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 29.41%  |
| 21      | 3        | 17.65%  |
| 34      | 2        | 11.76%  |
| 24      | 2        | 11.76%  |
| 54      | 1        | 5.88%   |
| 31      | 1        | 5.88%   |
| 23      | 1        | 5.88%   |
| 18      | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 43.75%  |
| 401-500     | 3        | 18.75%  |
| 701-800     | 2        | 12.5%   |
| 601-700     | 1        | 6.25%   |
| 351-400     | 1        | 6.25%   |
| 1001-1500   | 1        | 6.25%   |
| Unknown     | 1        | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 9        | 69.23%  |
| 21/9    | 2        | 15.38%  |
| 5/4     | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 5        | 29.41%  |
| 201-250        | 5        | 29.41%  |
| 351-500        | 3        | 17.65%  |
| 151-200        | 2        | 11.76%  |
| More than 1000 | 1        | 5.88%   |
| Unknown        | 1        | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 5        | 38.46%  |
| 51-100  | 5        | 38.46%  |
| 1-50    | 1        | 7.69%   |
| 161-240 | 1        | 7.69%   |
| Unknown | 1        | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 8        | 57.14%  |
| 2     | 5        | 35.71%  |
| 0     | 1        | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 42.11%  |
| Realtek Semiconductor | 6        | 31.58%  |
| TP-Link               | 1        | 5.26%   |
| Qualcomm Atheros      | 1        | 5.26%   |
| Qualcomm              | 1        | 5.26%   |
| Microsoft             | 1        | 5.26%   |
| Broadcom              | 1        | 5.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 4        | 16.67%  |
| Intel Wi-Fi 6 AX200                                                 | 3        | 12.5%   |
| Realtek RTL8125 2.5GbE Controller                                   | 2        | 8.33%   |
| Intel I211 Gigabit Network Connection                               | 2        | 8.33%   |
| Intel Ethernet Connection (7) I219-V                                | 2        | 8.33%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 1        | 4.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 4.17%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 1        | 4.17%   |
| Qualcomm 8920FT CD-ROM                                              | 1        | 4.17%   |
| Microsoft Xbox 360 Wireless Adapter                                 | 1        | 4.17%   |
| Intel Wireless-AC 9260                                              | 1        | 4.17%   |
| Intel Ethernet Connection I217-LM                                   | 1        | 4.17%   |
| Intel Ethernet Connection (2) I219-V                                | 1        | 4.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 1        | 4.17%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                     | 1        | 4.17%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 4.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 5        | 55.56%  |
| TP-Link          | 1        | 11.11%  |
| Qualcomm Atheros | 1        | 11.11%  |
| Microsoft        | 1        | 11.11%  |
| Broadcom         | 1        | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 3        | 33.33%  |
| TP-Link Archer T2U PLUS [RTL8821AU]                                 | 1        | 11.11%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter                    | 1        | 11.11%  |
| Microsoft Xbox 360 Wireless Adapter                                 | 1        | 11.11%  |
| Intel Wireless-AC 9260                                              | 1        | 11.11%  |
| Intel Cannon Lake PCH CNVi WiFi                                     | 1        | 11.11%  |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1        | 11.11%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 6        | 40%     |
| Intel                 | 6        | 40%     |
| Qualcomm Atheros      | 1        | 6.67%   |
| Qualcomm              | 1        | 6.67%   |
| Broadcom              | 1        | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 26.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 13.33%  |
| Intel I211 Gigabit Network Connection                             | 2        | 13.33%  |
| Intel Ethernet Connection (7) I219-V                              | 2        | 13.33%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 6.67%   |
| Qualcomm 8920FT CD-ROM                                            | 1        | 6.67%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 6.67%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 6.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 61.9%   |
| WiFi     | 8        | 38.1%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10       | 66.67%  |
| WiFi     | 5        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 6        | 46.15%  |
| 1     | 6        | 46.15%  |
| 3     | 1        | 7.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12       | 85.71%  |
| Yes  | 2        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 5        | 83.33%  |
| Broadcom | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                    | 3        | 50%     |
| Intel Wireless-AC 9260 Bluetooth Adapter | 1        | 16.67%  |
| Intel Bluetooth Device                   | 1        | 16.67%  |
| Broadcom BCM20702A0 Bluetooth 4.0        | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Nvidia                 | 7        | 23.33%  |
| Intel                  | 7        | 23.33%  |
| AMD                    | 7        | 23.33%  |
| Razer USA              | 2        | 6.67%   |
| C-Media Electronics    | 2        | 6.67%   |
| Tenx Technology        | 1        | 3.33%   |
| Logitech               | 1        | 3.33%   |
| Hewlett-Packard        | 1        | 3.33%   |
| Generalplus Technology | 1        | 3.33%   |
| Corsair                | 1        | 3.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 4        | 11.43%  |
| Nvidia GP104 High Definition Audio Controller                       | 2        | 5.71%   |
| Intel Cannon Lake PCH cAVS                                          | 2        | 5.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio            | 2        | 5.71%   |
| AMD Navi 10 HDMI Audio                                              | 2        | 5.71%   |
| Tenx Technology USB AUDIO                                           | 1        | 2.86%   |
| Razer USA Razer Kraken X USB                                        | 1        | 2.86%   |
| Razer USA Razer Kraken Ultimate                                     | 1        | 2.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1        | 2.86%   |
| Nvidia GP108 High Definition Audio Controller                       | 1        | 2.86%   |
| Nvidia GP106 High Definition Audio Controller                       | 1        | 2.86%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1        | 2.86%   |
| Nvidia GA102 High Definition Audio Controller                       | 1        | 2.86%   |
| Logitech G633 Gaming Headset                                        | 1        | 2.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1        | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1        | 2.86%   |
| Intel 200 Series PCH HD Audio                                       | 1        | 2.86%   |
| Hewlett-Packard E240C                                               | 1        | 2.86%   |
| Generalplus Technology USB Audio Device                             | 1        | 2.86%   |
| Corsair HS60 PRO Surround USB Sound Adapter                         | 1        | 2.86%   |
| C-Media Electronics Schiit Modi Uber                                | 1        | 2.86%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                       | 1        | 2.86%   |
| C-Media Electronics Blue Snowball                                   | 1        | 2.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1        | 2.86%   |
| AMD Family 17h/19h HD Audio Controller                              | 1        | 2.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                 | 1        | 2.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]          | 1        | 2.86%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]              | 1        | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| G.Skill           | 3        | 27.27%  |
| Unknown           | 2        | 18.18%  |
| Crucial           | 2        | 18.18%  |
| Unifosa           | 1        | 9.09%   |
| Team              | 1        | 9.09%   |
| PNY               | 1        | 9.09%   |
| Micron Technology | 1        | 9.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 9.09%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1        | 9.09%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s        | 1        | 9.09%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s       | 1        | 9.09%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2400MT/s      | 1        | 9.09%   |
| Micron RAM 16KTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s      | 1        | 9.09%   |
| G.Skill RAM F4-3600C17-8GTZR 8GB DIMM DDR4 3600MT/s      | 1        | 9.09%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s   | 1        | 9.09%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 9.09%   |
| Crucial RAM CT4G4DFS824A.C8FHP 4096MB DIMM DDR4 2400MT/s | 1        | 9.09%   |
| Crucial RAM CT25664BD160B.C8FN 2GB DIMM DDR3 1333MT/s    | 1        | 9.09%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 6        | 66.67%  |
| DDR3 | 2        | 22.22%  |
| DDR2 | 1        | 11.11%  |

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


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 3        | 33.33%  |
| 8192  | 3        | 33.33%  |
| 2048  | 2        | 22.22%  |
| 4096  | 1        | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 2        | 22.22%  |
| 4400  | 1        | 11.11%  |
| 4133  | 1        | 11.11%  |
| 3600  | 1        | 11.11%  |
| 3067  | 1        | 11.11%  |
| 1600  | 1        | 11.11%  |
| 1333  | 1        | 11.11%  |
| 800   | 1        | 11.11%  |

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
| Chicony Electronics | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Chicony HP High Definition 1MP Webcam | 1        | 100%    |

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
| 0     | 10       | 76.92%  |
| 1     | 3        | 23.08%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Net/wireless  | 1        | 33.33%  |
| Graphics card | 1        | 33.33%  |
| Bluetooth     | 1        | 33.33%  |

