Trisquel - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Trisquel.

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

Total: 31

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | Victus by Laptop 16-e0xx... | [855f5edce0](https://linux-hardware.org/?probe=855f5edce0) | Sep 08, 2023 |
| Dell      | Latitude E6400              | [65c390fe0e](https://linux-hardware.org/?probe=65c390fe0e) | Aug 12, 2023 |
| Dell      | XPS 15 9510                 | [8375e909e7](https://linux-hardware.org/?probe=8375e909e7) | Jul 30, 2023 |
| Lenovo    | ThinkPad X200 7458C23       | [3f09abaa12](https://linux-hardware.org/?probe=3f09abaa12) | Jul 24, 2023 |
| Dell      | XPS 15 9510                 | [154b34b737](https://linux-hardware.org/?probe=154b34b737) | Jul 18, 2023 |
| Lenovo    | G505s 20255                 | [4ec56be6a5](https://linux-hardware.org/?probe=4ec56be6a5) | Jul 03, 2023 |
| Lenovo    | G505s 20255                 | [2940c0be7d](https://linux-hardware.org/?probe=2940c0be7d) | Jul 01, 2023 |
| Toshiba   | NB510                       | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP        | Stream Laptop 11-y0XX       | [4f777df0e8](https://linux-hardware.org/?probe=4f777df0e8) | Apr 29, 2023 |
| Itautec   | Infoway                     | [c046d6e093](https://linux-hardware.org/?probe=c046d6e093) | Apr 16, 2023 |
| Acer      | Nitro AN517-54              | [185c4824b7](https://linux-hardware.org/?probe=185c4824b7) | Apr 07, 2023 |
| Dell      | Inspiron 15-3567            | [e94792b948](https://linux-hardware.org/?probe=e94792b948) | Dec 13, 2022 |
| Dell      | Inspiron 1545               | [5b13c289e1](https://linux-hardware.org/?probe=5b13c289e1) | Nov 26, 2022 |
| Libiquity | Taurinus X200               | [75c0f41e26](https://linux-hardware.org/?probe=75c0f41e26) | Nov 09, 2022 |
| Lenovo    | ThinkPad T430 2347G2U       | [ab06dd40c4](https://linux-hardware.org/?probe=ab06dd40c4) | Oct 03, 2022 |
| Lenovo    | ThinkPad T430 2347G2U       | [5b08d764b4](https://linux-hardware.org/?probe=5b08d764b4) | Sep 27, 2022 |
| Lenovo    | G505s 20255                 | [a9e525c695](https://linux-hardware.org/?probe=a9e525c695) | Sep 16, 2022 |
| Timi      | TM1709                      | [2fb5436031](https://linux-hardware.org/?probe=2fb5436031) | Sep 04, 2022 |
| Lenovo    | ThinkPad T430 2347G2U       | [8d7c5df586](https://linux-hardware.org/?probe=8d7c5df586) | Sep 03, 2022 |
| ASUSTek   | K55A                        | [5d11054a36](https://linux-hardware.org/?probe=5d11054a36) | Aug 28, 2022 |
| Lenovo    | ThinkPad T420 4177QKU       | [a18ab36f34](https://linux-hardware.org/?probe=a18ab36f34) | Aug 17, 2022 |
| Lenovo    | ThinkPad T430 2347G2U       | [f6abe5392b](https://linux-hardware.org/?probe=f6abe5392b) | Aug 03, 2022 |
| Lenovo    | ThinkPad T430 2347G2U       | [b25d6bf66c](https://linux-hardware.org/?probe=b25d6bf66c) | Jul 27, 2022 |
| Lenovo    | ThinkPad T420 4177QKU       | [215758ad8a](https://linux-hardware.org/?probe=215758ad8a) | Apr 30, 2022 |
| Dell      | XPS 13 9360                 | [1126937638](https://linux-hardware.org/?probe=1126937638) | Apr 28, 2022 |
| Toshiba   | Satellite C800D             | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Samsung   | N130                        | [1a88380af6](https://linux-hardware.org/?probe=1a88380af6) | Nov 27, 2021 |
| ASUSTek   | U56E                        | [99bd7dbfdf](https://linux-hardware.org/?probe=99bd7dbfdf) | Sep 09, 2021 |
| Lenovo    | ThinkPad X200 7455FNG       | [6fcadf1396](https://linux-hardware.org/?probe=6fcadf1396) | Mar 20, 2021 |
| Acer      | TravelMate B115-M           | [62239072f1](https://linux-hardware.org/?probe=62239072f1) | Nov 26, 2019 |
| GPD       | MicroPC                     | [8fc0176f69](https://linux-hardware.org/?probe=8fc0176f69) | Sep 28, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Trisquel 10.0.1 | 10        | 40%     |
| Trisquel 11.0   | 8         | 32%     |
| Trisquel 9.0    | 3         | 12%     |
| Trisquel 8.0    | 2         | 8%      |
| Trisquel 10.0   | 2         | 8%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Trisquel | 25        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.4.0-96-generic     | 3         | 11.11%  |
| 5.4.0-122-generic    | 3         | 11.11%  |
| 5.4.0-125-generic    | 2         | 7.41%   |
| 5.15.0-78-generic    | 2         | 7.41%   |
| 5.15.0-76-generic    | 2         | 7.41%   |
| 5.15.0-69-generic    | 2         | 7.41%   |
| 6.0.12-x64v1-xanmod1 | 1         | 3.7%    |
| 5.4.0-159-generic    | 1         | 3.7%    |
| 5.4.0-132-generic    | 1         | 3.7%    |
| 5.4.0-131-generic    | 1         | 3.7%    |
| 5.4.0-126-generic    | 1         | 3.7%    |
| 5.4.0-113-generic    | 1         | 3.7%    |
| 5.3.13-gnu           | 1         | 3.7%    |
| 5.3.1-gnu            | 1         | 3.7%    |
| 5.15.0-73-generic    | 1         | 3.7%    |
| 5.15.0-67-generic    | 1         | 3.7%    |
| 4.15.0-161-generic   | 1         | 3.7%    |
| 4.15.0-156-generic   | 1         | 3.7%    |
| 4.15.0-136-generic   | 1         | 3.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 11        | 44%     |
| 5.15.0  | 8         | 32%     |
| 4.15.0  | 3         | 12%     |
| 6.0.12  | 1         | 4%      |
| 5.3.13  | 1         | 4%      |
| 5.3.1   | 1         | 4%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 11        | 44%     |
| 5.15    | 8         | 32%     |
| 4.15    | 3         | 12%     |
| 5.3     | 2         | 8%      |
| 6.0     | 1         | 4%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 24        | 96%     |
| i686   | 1         | 4%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 18        | 72%     |
| LXDE    | 3         | 12%     |
| KDE5    | 1         | 4%      |
| GNOME   | 1         | 4%      |
| dwm     | 1         | 4%      |
| Unknown | 1         | 4%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 24        | 96%     |
| Wayland | 1         | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 16        | 64%     |
| Unknown | 4         | 16%     |
| TDM     | 3         | 12%     |
| SDDM    | 1         | 4%      |
| GDM     | 1         | 4%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 13        | 52%     |
| ru_RU   | 3         | 12%     |
| C       | 2         | 8%      |
| Unknown | 2         | 8%      |
| ru_UA   | 1         | 4%      |
| pt_BR   | 1         | 4%      |
| es_MX   | 1         | 4%      |
| es_ES   | 1         | 4%      |
| de_DE   | 1         | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 13        | 52%     |
| BIOS | 12        | 48%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 23        | 92%     |
| Overlay | 2         | 8%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 18        | 72%     |
| Unknown | 5         | 20%     |
| MBR     | 2         | 8%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 80.77%  |
| Yes       | 5         | 19.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 88%     |
| Yes       | 3         | 12%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 24%     |
| Dell                | 6         | 24%     |
| Toshiba             | 2         | 8%      |
| Hewlett-Packard     | 2         | 8%      |
| ASUSTek Computer    | 2         | 8%      |
| Acer                | 2         | 8%      |
| Timi                | 1         | 4%      |
| Samsung Electronics | 1         | 4%      |
| Libiquity           | 1         | 4%      |
| Itautec             | 1         | 4%      |
| GPD                 | 1         | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad T420 4177QKU | 2         | 8%      |
| Dell XPS 15 9510             | 2         | 8%      |
| Toshiba Satellite C800D      | 1         | 4%      |
| Toshiba NB510                | 1         | 4%      |
| Timi TM1709                  | 1         | 4%      |
| Samsung N130                 | 1         | 4%      |
| Libiquity Taurinus X200      | 1         | 4%      |
| Lenovo ThinkPad X200 7458C23 | 1         | 4%      |
| Lenovo ThinkPad X200 7455FNG | 1         | 4%      |
| Lenovo ThinkPad T430 2347G2U | 1         | 4%      |
| Lenovo G505s 20255           | 1         | 4%      |
| Itautec Infoway              | 1         | 4%      |
| HP Victus by Laptop 16-e0xxx | 1         | 4%      |
| HP Stream Laptop 11-y0XX     | 1         | 4%      |
| GPD MicroPC                  | 1         | 4%      |
| Dell XPS 13 9360             | 1         | 4%      |
| Dell Latitude E6400          | 1         | 4%      |
| Dell Inspiron 1545           | 1         | 4%      |
| Dell Inspiron 15-3567        | 1         | 4%      |
| ASUS U56E                    | 1         | 4%      |
| ASUS K55A                    | 1         | 4%      |
| Acer TravelMate B115-M       | 1         | 4%      |
| Acer Nitro AN517-54          | 1         | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 20%     |
| Dell XPS           | 3         | 12%     |
| Dell Inspiron      | 2         | 8%      |
| Toshiba Satellite  | 1         | 4%      |
| Toshiba NB510      | 1         | 4%      |
| Timi TM1709        | 1         | 4%      |
| Samsung N130       | 1         | 4%      |
| Libiquity Taurinus | 1         | 4%      |
| Lenovo G505s       | 1         | 4%      |
| Itautec Infoway    | 1         | 4%      |
| HP Victus          | 1         | 4%      |
| HP Stream          | 1         | 4%      |
| GPD MicroPC        | 1         | 4%      |
| Dell Latitude      | 1         | 4%      |
| ASUS U56E          | 1         | 4%      |
| ASUS K55A          | 1         | 4%      |
| Acer TravelMate    | 1         | 4%      |
| Acer Nitro         | 1         | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2008 | 5         | 20%     |
| 2021 | 4         | 16%     |
| 2012 | 4         | 16%     |
| 2016 | 3         | 12%     |
| 2011 | 3         | 12%     |
| 2019 | 1         | 4%      |
| 2018 | 1         | 4%      |
| 2015 | 1         | 4%      |
| 2014 | 1         | 4%      |
| 2013 | 1         | 4%      |
| 2009 | 1         | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 25        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 25        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 84%     |
| Yes  | 4         | 16%     |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 12        | 48%     |
| 1.01-2.0   | 4         | 16%     |
| 3.01-4.0   | 3         | 12%     |
| 16.01-24.0 | 3         | 12%     |
| 8.01-16.0  | 3         | 12%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 18        | 69.23%  |
| 0.51-1.0  | 3         | 11.54%  |
| 4.01-8.0  | 1         | 3.85%   |
| 3.01-4.0  | 1         | 3.85%   |
| 2.01-3.0  | 1         | 3.85%   |
| 8.01-16.0 | 1         | 3.85%   |
| 0.01-0.5  | 1         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 65.38%  |
| 2      | 6         | 23.08%  |
| 4      | 1         | 3.85%   |
| 3      | 1         | 3.85%   |
| 0      | 1         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14        | 56%     |
| Yes       | 11        | 44%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 92%     |
| No        | 2         | 8%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 60%     |
| No        | 10        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 10        | 40%     |
| Russia      | 2         | 8%      |
| Germany     | 2         | 8%      |
| France      | 2         | 8%      |
| China       | 2         | 8%      |
| Brazil      | 2         | 8%      |
| Spain       | 1         | 4%      |
| Netherlands | 1         | 4%      |
| Mexico      | 1         | 4%      |
| Indonesia   | 1         | 4%      |
| Belarus     | 1         | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lincoln           | 3         | 12%     |
| Malvern           | 2         | 8%      |
| Wylie             | 1         | 4%      |
| Wiesbaden         | 1         | 4%      |
| Vitebsk           | 1         | 4%      |
| St Petersburg     | 1         | 4%      |
| Shenzhen          | 1         | 4%      |
| Sabadell          | 1         | 4%      |
| Pinangsia         | 1         | 4%      |
| Paris             | 1         | 4%      |
| Omaha             | 1         | 4%      |
| Moscow            | 1         | 4%      |
| Missoula          | 1         | 4%      |
| Lüdenscheid      | 1         | 4%      |
| Fayetteville      | 1         | 4%      |
| Ciudad del Carmen | 1         | 4%      |
| Chengdu           | 1         | 4%      |
| Cerons            | 1         | 4%      |
| Blumenau          | 1         | 4%      |
| Amsterdam         | 1         | 4%      |
| Americana         | 1         | 4%      |
| Acworth           | 1         | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 23.33%  |
| WDC                 | 3         | 3      | 10%     |
| Toshiba             | 3         | 3      | 10%     |
| SanDisk             | 3         | 3      | 10%     |
| SK hynix            | 2         | 2      | 6.67%   |
| Seagate             | 2         | 8      | 6.67%   |
| HGST HTS            | 2         | 4      | 6.67%   |
| Crucial             | 2         | 2      | 6.67%   |
| Transcend           | 1         | 1      | 3.33%   |
| Qumo                | 1         | 1      | 3.33%   |
| Plextor             | 1         | 1      | 3.33%   |
| Hitachi             | 1         | 1      | 3.33%   |
| China               | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| SK hynix PC711 NVMe 512GB            | 2         | 6.25%   |
| Seagate ST4000NM 0033-9ZM170 4TB     | 2         | 6.25%   |
| HGST HTS 721010A9E630 1TB            | 2         | 6.25%   |
| WDC WD6400BPVT-80HXZT3 640GB         | 1         | 3.13%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 3.13%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB | 1         | 3.13%   |
| Transcend TS256GMTS430S 256GB SSD    | 1         | 3.13%   |
| Toshiba THNSN5256GPUK NVMe 256GB     | 1         | 3.13%   |
| Toshiba MK3275GSX 320GB              | 1         | 3.13%   |
| Toshiba HDWL110 1TB                  | 1         | 3.13%   |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 3.13%   |
| Sandisk WD Blue SN570 1TB            | 1         | 3.13%   |
| SanDisk SSD PLUS 240GB               | 1         | 3.13%   |
| SanDisk DF4032  32GB                 | 1         | 3.13%   |
| Samsung SSD 860 EVO 250GB            | 1         | 3.13%   |
| Samsung SSD 840 PRO Series 256GB     | 1         | 3.13%   |
| Samsung SSD 840 EVO 120GB            | 1         | 3.13%   |
| Samsung MZVLQ512HBLU-00BTW 512GB     | 1         | 3.13%   |
| Samsung MZNLN128HAHQ-00000 128GB SSD | 1         | 3.13%   |
| Samsung HM251JI 250GB                | 1         | 3.13%   |
| Samsung HM160HI 160GB                | 1         | 3.13%   |
| Qumo SSD 120GB                       | 1         | 3.13%   |
| Plextor PX-512M5Pro 512GB SSD        | 1         | 3.13%   |
| Hitachi HTS547575A9E384 752GB        | 1         | 3.13%   |
| Crucial CT250BX100SSD1 250GB         | 1         | 3.13%   |
| Crucial CT240BX200SSD1 240GB         | 1         | 3.13%   |
| China 240GB SSD                      | 1         | 3.13%   |
| A-DATA SU650 120GB SSD               | 1         | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 18.18%  |
| Toshiba             | 2         | 2      | 18.18%  |
| Seagate             | 2         | 8      | 18.18%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| HGST HTS            | 2         | 4      | 18.18%  |
| Hitachi             | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 33.33%  |
| Crucial             | 2         | 2      | 16.67%  |
| Transcend           | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| Qumo                | 1         | 1      | 8.33%   |
| Plextor             | 1         | 1      | 8.33%   |
| China               | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 11        | 12     | 44%     |
| HDD  | 8         | 19     | 32%     |
| NVMe | 5         | 6      | 20%     |
| MMC  | 1         | 1      | 4%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18        | 23     | 69.23%  |
| NVMe | 5         | 6      | 19.23%  |
| SAS  | 2         | 8      | 7.69%   |
| MMC  | 1         | 1      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 18     | 68.18%  |
| 0.51-1.0   | 5         | 9      | 22.73%  |
| 3.01-4.0   | 2         | 4      | 9.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 12        | 48%     |
| 251-500        | 4         | 16%     |
| More than 3000 | 2         | 8%      |
| 21-50          | 2         | 8%      |
| 501-1000       | 2         | 8%      |
| 51-100         | 2         | 8%      |
| 1-20           | 1         | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 11        | 42.31%  |
| 21-50          | 5         | 19.23%  |
| 101-250        | 5         | 19.23%  |
| 2001-3000      | 2         | 7.69%   |
| 51-100         | 2         | 7.69%   |
| More than 3000 | 1         | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| HGST HTS 721010A9E630 1TB       | 2         | 4      | 33.33%  |
| WDC WD3200BEVT-75ZCT2 320GB     | 1         | 1      | 16.67%  |
| Toshiba MK3275GSX 320GB         | 1         | 1      | 16.67%  |
| Seagate ST320LT007-9ZV142 320GB | 1         | 3      | 16.67%  |
| Crucial CT240BX200SSD1 240GB    | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| HGST HTS | 2         | 4      | 33.33%  |
| WDC      | 1         | 1      | 16.67%  |
| Toshiba  | 1         | 1      | 16.67%  |
| Seagate  | 1         | 3      | 16.67%  |
| Crucial  | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| HGST HTS | 2         | 4      | 40%     |
| WDC      | 1         | 1      | 20%     |
| Toshiba  | 1         | 1      | 20%     |
| Seagate  | 1         | 3      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 9      | 80%     |
| SSD  | 1         | 1      | 20%     |

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
| Works    | 15        | 22     | 57.69%  |
| Detected | 6         | 6      | 23.08%  |
| Malfunc  | 5         | 10     | 19.23%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 18        | 69.23%  |
| SK hynix                     | 2         | 7.69%   |
| SanDisk                      | 2         | 7.69%   |
| AMD                          | 2         | 7.69%   |
| Toshiba America Info Systems | 1         | 3.85%   |
| Samsung Electronics          | 1         | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 5         | 17.86%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 10.71%  |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 2         | 7.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 7.14%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 7.14%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                         | 1         | 3.57%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                        | 1         | 3.57%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 1         | 3.57%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 1         | 3.57%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 3.57%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 1         | 3.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 3.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 3.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 3.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 3.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 3.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 1         | 3.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 70.37%  |
| NVMe | 5         | 18.52%  |
| IDE  | 2         | 7.41%   |
| RAID | 1         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 88%     |
| AMD    | 3         | 12%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-2410M CPU @ 2.30GHz        | 2         | 8%      |
| Intel 11th Gen Core i7-11800H @ 2.30GHz  | 2         | 8%      |
| Intel Pentium Dual CPU T3400 @ 2.16GHz   | 1         | 4%      |
| Intel Pentium CPU N3530 @ 2.16GHz        | 1         | 4%      |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 4%      |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 4%      |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 4%      |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 4%      |
| Intel Core i5-2430M CPU @ 2.40GHz        | 1         | 4%      |
| Intel Core i3-6006U CPU @ 2.00GHz        | 1         | 4%      |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz     | 1         | 4%      |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz     | 1         | 4%      |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 1         | 4%      |
| Intel Core 2 CPU P8700 @ 2.53GHz         | 1         | 4%      |
| Intel Core 2 CPU P8600 @ 2.40GHz         | 1         | 4%      |
| Intel Celeron N4100 CPU @ 1.10GHz        | 1         | 4%      |
| Intel Celeron CPU N3060 @ 1.60GHz        | 1         | 4%      |
| Intel Atom CPU N270 @ 1.60GHz            | 1         | 4%      |
| Intel Atom CPU N2600 @ 1.60GHz           | 1         | 4%      |
| Intel 11th Gen Core i5-11400H @ 2.70GHz  | 1         | 4%      |
| AMD Ryzen 7 5800H with Radeon Graphics   | 1         | 4%      |
| AMD E1-1200 APU with Radeon HD Graphics  | 1         | 4%      |
| AMD A8-5550M APU with Radeon HD Graphics | 1         | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 7         | 28%     |
| Other              | 3         | 12%     |
| Intel Core 2 Duo   | 3         | 12%     |
| Intel Core 2       | 2         | 8%      |
| Intel Celeron      | 2         | 8%      |
| Intel Atom         | 2         | 8%      |
| Intel Pentium Dual | 1         | 4%      |
| Intel Pentium      | 1         | 4%      |
| Intel Core i3      | 1         | 4%      |
| AMD Ryzen 7        | 1         | 4%      |
| AMD E1             | 1         | 4%      |
| AMD A8             | 1         | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 17        | 68%     |
| 8      | 3         | 12%     |
| 4      | 3         | 12%     |
| 6      | 1         | 4%      |
| 1      | 1         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 15        | 60%     |
| 1      | 10        | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24        | 96%     |
| 32-bit         | 1         | 4%      |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x1067a    | 4         | 16%     |
| Unknown    | 4         | 16%     |
| 0x206a7    | 3         | 12%     |
| 0x806d1    | 2         | 8%      |
| 0x806ea    | 1         | 4%      |
| 0x806e9    | 1         | 4%      |
| 0x706a1    | 1         | 4%      |
| 0x406e3    | 1         | 4%      |
| 0x406c4    | 1         | 4%      |
| 0x306a9    | 1         | 4%      |
| 0x30678    | 1         | 4%      |
| 0x106c2    | 1         | 4%      |
| 0x10676    | 1         | 4%      |
| 0x0a50000c | 1         | 4%      |
| 0x06001119 | 1         | 4%      |
| 0x0500010d | 1         | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Penryn        | 5         | 20%     |
| SandyBridge   | 3         | 12%     |
| Silvermont    | 2         | 8%      |
| KabyLake      | 2         | 8%      |
| IvyBridge     | 2         | 8%      |
| Icelake       | 2         | 8%      |
| Bonnell       | 2         | 8%      |
| Zen 3         | 1         | 4%      |
| Skylake       | 1         | 4%      |
| Piledriver    | 1         | 4%      |
| Goldmont plus | 1         | 4%      |
| Core          | 1         | 4%      |
| Bobcat        | 1         | 4%      |
| Unknown       | 1         | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 73.33%  |
| Nvidia | 5         | 16.67%  |
| AMD    | 3         | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 15.63%  |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 9.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 9.38%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 6.25%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 6.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 6.25%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 3.13%   |
| Intel UHD Graphics 620                                                                   | 1         | 3.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 3.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 3.13%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 3.13%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 3.13%   |
| Intel HD Graphics 620                                                                    | 1         | 3.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 3.13%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 3.13%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 3.13%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 3.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1         | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 72%     |
| Intel + Nvidia | 4         | 16%     |
| 1 x AMD        | 2         | 8%      |
| AMD + Nvidia   | 1         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 23        | 92%     |
| Unknown | 2         | 8%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 76%     |
| 1.01-2.0   | 3         | 12%     |
| 5.01-6.0   | 1         | 4%      |
| 3.01-4.0   | 1         | 4%      |
| 0.01-0.5   | 1         | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 6         | 26.09%  |
| LG Display              | 4         | 17.39%  |
| Lenovo                  | 3         | 13.04%  |
| AU Optronics            | 3         | 13.04%  |
| BOE                     | 2         | 8.7%    |
| Sharp                   | 1         | 4.35%   |
| Gateway                 | 1         | 4.35%   |
| CPT                     | 1         | 4.35%   |
| Chimei Innolux          | 1         | 4.35%   |
| Chi Mei Optoelectronics | 1         | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch    | 2         | 8.7%    |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch              | 2         | 8.7%    |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch                  | 2         | 8.7%    |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch     | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC374E 1024x600 223x125mm 10.1-inch     | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 1         | 4.35%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 1         | 4.35%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 4.35%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 1         | 4.35%   |
| Gateway FPD1976W GWY0785 1440x900 410x257mm 19.1-inch                    | 1         | 4.35%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                     | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 1         | 4.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 1         | 4.35%   |
| BOE LCD Monitor BOE07C5 1920x1080 344x194mm 15.5-inch                    | 1         | 4.35%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch           | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO215C 1366x768 256x144mm 11.6-inch            | 1         | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 10        | 45.45%  |
| 1280x800 (WXGA)  | 4         | 18.18%  |
| 1920x1080 (FHD)  | 3         | 13.64%  |
| 3456x2160        | 2         | 9.09%   |
| 1600x900 (HD+)   | 2         | 9.09%   |
| 1440x900 (WXGA+) | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 10        | 43.48%  |
| 14     | 4         | 17.39%  |
| 12     | 3         | 13.04%  |
| 17     | 2         | 8.7%    |
| 11     | 2         | 8.7%    |
| 19     | 1         | 4.35%   |
| 13     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 56.52%  |
| 201-300     | 6         | 26.09%  |
| 351-400     | 3         | 13.04%  |
| 401-500     | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 15        | 68.18%  |
| 16/10 | 6         | 27.27%  |
| 3/2   | 1         | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 10        | 43.48%  |
| 81-90          | 4         | 17.39%  |
| 61-70          | 3         | 13.04%  |
| 51-60          | 2         | 8.7%    |
| 71-80          | 1         | 4.35%   |
| 151-200        | 1         | 4.35%   |
| 131-140        | 1         | 4.35%   |
| 121-130        | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 9         | 40.91%  |
| 101-120       | 7         | 31.82%  |
| 51-100        | 3         | 13.64%  |
| More than 240 | 2         | 9.09%   |
| 161-240       | 1         | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 22        | 88%     |
| 0     | 2         | 8%      |
| 2     | 1         | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 30.43%  |
| Qualcomm Atheros                | 13        | 28.26%  |
| Realtek Semiconductor           | 11        | 23.91%  |
| Qualcomm Atheros Communications | 4         | 8.7%    |
| Marvell Technology Group        | 2         | 4.35%   |
| Samsung Electronics             | 1         | 2.17%   |
| Microsoft                       | 1         | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 9.26%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 7.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4         | 7.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.56%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 5.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 3.7%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 3.7%    |
| Samsung HSPA Modem                                                | 1         | 1.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 1.85%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 1.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.85%   |
| Microsoft Ethernet Adapter                                        | 1         | 1.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.85%   |
| Intel Wireless 7265                                               | 1         | 1.85%   |
| Intel Wireless 3165                                               | 1         | 1.85%   |
| Intel WiFi Link 5100                                              | 1         | 1.85%   |
| Intel Centrino Wireless-N 6150                                    | 1         | 1.85%   |
| Intel Centrino Wireless-N + WiMAX 6150                            | 1         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 1.85%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 11        | 37.93%  |
| Intel                           | 10        | 34.48%  |
| Realtek Semiconductor           | 4         | 13.79%  |
| Qualcomm Atheros Communications | 4         | 13.79%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9271 802.11n                                | 4         | 13.33%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 4         | 13.33%  |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 10%     |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 6.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 6.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 3.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 3.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 3.33%   |
| Intel Wireless 7265                                            | 1         | 3.33%   |
| Intel Wireless 3165                                            | 1         | 3.33%   |
| Intel WiFi Link 5100                                           | 1         | 3.33%   |
| Intel Centrino Wireless-N 6150                                 | 1         | 3.33%   |
| Intel Centrino Wireless-N + WiMAX 6150                         | 1         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 9         | 39.13%  |
| Intel                    | 7         | 30.43%  |
| Qualcomm Atheros         | 4         | 17.39%  |
| Marvell Technology Group | 2         | 8.7%    |
| Microsoft                | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 21.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 13.04%  |
| Intel 82567LM Gigabit Network Connection                          | 3         | 13.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 8.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 4.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 4.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 4.35%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 4.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 4.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 4.35%   |
| Microsoft Ethernet Adapter                                        | 1         | 4.35%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 4.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 4.35%   |
| Intel 82567LF Gigabit Network Connection                          | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 51.02%  |
| Ethernet | 23        | 46.94%  |
| Modem    | 1         | 2.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 64%     |
| Ethernet | 9         | 36%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 80%     |
| 1     | 5         | 20%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 76%     |
| Yes  | 6         | 24%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5         | 31.25%  |
| Qualcomm Atheros Communications | 3         | 18.75%  |
| Broadcom                        | 3         | 18.75%  |
| Toshiba                         | 2         | 12.5%   |
| Realtek Semiconductor           | 2         | 12.5%   |
| Foxconn / Hon Hai               | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                              | 3         | 18.75%  |
| Realtek Bluetooth Radio                            | 2         | 12.5%   |
| Qualcomm Atheros  Bluetooth Device                 | 2         | 12.5%   |
| Intel Bluetooth wireless interface                 | 2         | 12.5%   |
| Toshiba RT Bluetooth Radio                         | 1         | 6.25%   |
| Toshiba Bluetooth Device                           | 1         | 6.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 1         | 6.25%   |
| Foxconn / Hon Hai Bluetooth Device                 | 1         | 6.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                  | 1         | 6.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 1         | 6.25%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 78.57%  |
| AMD                   | 3         | 10.71%  |
| Nvidia                | 2         | 7.14%   |
| Realtek Semiconductor | 1         | 3.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 17.24%  |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 10.34%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 10.34%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 10.34%  |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 6.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 6.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 6.9%    |
| AMD FCH Azalia Controller                                                                         | 2         | 6.9%    |
| Realtek Semiconductor USB Audio                                                                   | 1         | 3.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 3.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 3.45%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 36.84%  |
| SK hynix            | 3         | 15.79%  |
| Micron Technology   | 3         | 15.79%  |
| Kingston            | 2         | 10.53%  |
| Ramaxel Technology  | 1         | 5.26%   |
| Qimonda             | 1         | 5.26%   |
| Crucial             | 1         | 5.26%   |
| A-DATA Technology   | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 10.53%  |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 10.53%  |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s        | 1         | 5.26%   |
| SK hynix RAM HMT41GS6AFR8A-H9 8192MB SODIMM DDR3 1333MT/s      | 1         | 5.26%   |
| SK hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s         | 1         | 5.26%   |
| Samsung RAM Module 2GB Row Of Chips DDR3 1600MT/s              | 1         | 5.26%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s          | 1         | 5.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 5.26%   |
| Ramaxel RAM RMT3170ME68F9F1600 4096MB SODIMM DDR3 1600MT/s     | 1         | 5.26%   |
| Qimonda RAM 64T512022EDL2.5A 4096MB SODIMM DDR 800MT/s         | 1         | 5.26%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 5.26%   |
| Micron RAM H6451U64F7066G 4096MB SODIMM DDR3 1067MT/s          | 1         | 5.26%   |
| Micron RAM 4ATF51264HZ-2G3H1R 4GB SODIMM DDR4 2400MT/s         | 1         | 5.26%   |
| Kingston RAM ASU1600S11-4G-EDEG 4GB SODIMM DDR3 1600MT/s       | 1         | 5.26%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s         | 1         | 5.26%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s        | 1         | 5.26%   |
| A-DATA RAM Module 4096MB SODIMM DDR4 2400MT/s                  | 1         | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 7         | 43.75%  |
| DDR4   | 6         | 37.5%   |
| LPDDR3 | 1         | 6.25%   |
| DDR2   | 1         | 6.25%   |
| DDR    | 1         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 13        | 86.67%  |
| Row Of Chips | 2         | 13.33%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 8         | 44.44%  |
| 8192 | 7         | 38.89%  |
| 2048 | 3         | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 5         | 29.41%  |
| 3200  | 4         | 23.53%  |
| 2400  | 2         | 11.76%  |
| 1867  | 1         | 5.88%   |
| 1334  | 1         | 5.88%   |
| 1333  | 1         | 5.88%   |
| 1067  | 1         | 5.88%   |
| 975   | 1         | 5.88%   |
| 800   | 1         | 5.88%   |

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
| Chicony Electronics                    | 5         | 25%     |
| Microdia                               | 3         | 15%     |
| Lenovo                                 | 3         | 15%     |
| Sunplus Innovation Technology          | 2         | 10%     |
| Z-Star Microelectronics                | 1         | 5%      |
| Realtek Semiconductor                  | 1         | 5%      |
| Quanta                                 | 1         | 5%      |
| Importek                               | 1         | 5%      |
| IMC Networks                           | 1         | 5%      |
| GoPro                                  | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Webcam                                     | 3         | 15%     |
| Z-Star Webcam                                                | 1         | 5%      |
| Sunplus HD WebCam                                            | 1         | 5%      |
| Sunplus Asus Webcam                                          | 1         | 5%      |
| Realtek Lenovo EasyCamera                                    | 1         | 5%      |
| Quanta HD User Facing                                        | 1         | 5%      |
| Microdia Integrated_Webcam_HD                                | 1         | 5%      |
| Microdia Integrated_Webcam_1.3M                              | 1         | 5%      |
| Microdia Integrated Webcam HD                                | 1         | 5%      |
| Importek TOSHIBA Web Camera                                  | 1         | 5%      |
| IMC Networks UVC VGA Webcam                                  | 1         | 5%      |
| GoPro HERO4 Black                                            | 1         | 5%      |
| Chicony TOSHIBA Web Camera                                   | 1         | 5%      |
| Chicony Thinkpad T430 camera                                 | 1         | 5%      |
| Chicony integrated camera                                    | 1         | 5%      |
| Chicony HP Wide Vision HD Camera                             | 1         | 5%      |
| Chicony HP Webcam                                            | 1         | 5%      |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| AuthenTec | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| AuthenTec AES2810 | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Upek     | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 60%     |
| 1     | 9         | 36%     |
| 2     | 1         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 4         | 40%     |
| Chipcard              | 2         | 20%     |
| Net/wireless          | 1         | 10%     |
| Multimedia controller | 1         | 10%     |
| Fingerprint reader    | 1         | 10%     |
| Bluetooth             | 1         | 10%     |

