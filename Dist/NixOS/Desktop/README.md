NixOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

| Vendor     | Model                   | Probe                                                      | Date         |
|------------|-------------------------|------------------------------------------------------------|--------------|
| MSI        | X399 SLI PLUS           | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI  | [051ac4ce21](https://linux-hardware.org/?probe=051ac4ce21) | Jan 13, 2022 |
| MSI        | MAG X570 TOMAHAWK WIFI  | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| ASUSTek    | Z170-P                  | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Gigabyte   | X570 AORUS ELITE        | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek    | PRIME Z390-A            | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Gigabyte   | H97M-D3H                | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| MSI        | X399 SLI PLUS           | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASRock     | X570 Taichi             | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock     | X570 Taichi             | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek    | SABERTOOTH X99          | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI        | X570-A PRO              | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock     | B450 Gaming-ITX/ac      | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock     | B450 Gaming-ITX/ac      | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock     | B450 Gaming-ITX/ac      | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| ASUSTek    | Pro WS W480-ACE         | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek    | ROG STRIX B550-I GAMING | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI        | MPG X570 GAMING PLUS    | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| HARDKERNEL | ODROID-H2               | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| ASUSTek    | TUF GAMING X570-PLUS    | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| MSI        | MAG B550M BAZOOKA       | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek    | PRIME Z270-K            | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP         | 8055                    | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP         | 8055                    | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| ASRock     | TRX40 Creator           | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.8.1-zen1             | 2        | 9.52%   |
| 5.8.10                 | 1        | 4.76%   |
| 5.7.19                 | 1        | 4.76%   |
| 5.4.94                 | 1        | 4.76%   |
| 5.4.72                 | 1        | 4.76%   |
| 5.4.69                 | 1        | 4.76%   |
| 5.4.50                 | 1        | 4.76%   |
| 5.4.47                 | 1        | 4.76%   |
| 5.15.7                 | 1        | 4.76%   |
| 5.15.18                | 1        | 4.76%   |
| 5.14.16-lqx1           | 1        | 4.76%   |
| 5.13.2                 | 1        | 4.76%   |
| 5.12.15                | 1        | 4.76%   |
| 5.11.16-zen1           | 1        | 4.76%   |
| 5.11.16-xanmod1-cacule | 1        | 4.76%   |
| 5.10.62                | 1        | 4.76%   |
| 5.10.52                | 1        | 4.76%   |
| 5.10.43                | 1        | 4.76%   |
| 5.10.35                | 1        | 4.76%   |
| 5.10.17                | 1        | 4.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.8.1   | 2        | 9.52%   |
| 5.11.16 | 2        | 9.52%   |
| 5.8.10  | 1        | 4.76%   |
| 5.7.19  | 1        | 4.76%   |
| 5.4.94  | 1        | 4.76%   |
| 5.4.72  | 1        | 4.76%   |
| 5.4.69  | 1        | 4.76%   |
| 5.4.50  | 1        | 4.76%   |
| 5.4.47  | 1        | 4.76%   |
| 5.15.7  | 1        | 4.76%   |
| 5.15.18 | 1        | 4.76%   |
| 5.14.16 | 1        | 4.76%   |
| 5.13.2  | 1        | 4.76%   |
| 5.12.15 | 1        | 4.76%   |
| 5.10.62 | 1        | 4.76%   |
| 5.10.52 | 1        | 4.76%   |
| 5.10.43 | 1        | 4.76%   |
| 5.10.35 | 1        | 4.76%   |
| 5.10.17 | 1        | 4.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 5        | 23.81%  |
| 5.10    | 5        | 23.81%  |
| 5.8     | 3        | 14.29%  |
| 5.15    | 2        | 9.52%   |
| 5.11    | 2        | 9.52%   |
| 5.7     | 1        | 4.76%   |
| 5.14    | 1        | 4.76%   |
| 5.13    | 1        | 4.76%   |
| 5.12    | 1        | 4.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 20       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 85%     |
| KDE     | 2        | 10%     |
| GNOME   | 1        | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 85%     |
| X11     | 3        | 15%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 19       | 95%     |
| SDDM    | 1        | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 65%     |
| en_US   | 5        | 25%     |
| pt_BR   | 1        | 5%      |
| en_DK   | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 15       | 71.43%  |
| BIOS | 6        | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 9        | 45%     |
| Xfs     | 3        | 15%     |
| Tmpfs   | 2        | 10%     |
| Btrfs   | 2        | 10%     |
| Unknown | 2        | 10%     |
| Zfs     | 1        | 5%      |
| Ext2    | 1        | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 19       | 95%     |
| Unknown | 1        | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 65%     |
| Yes       | 7        | 35%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 65%     |
| No        | 7        | 35%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 40%     |
| MSI                 | 5        | 25%     |
| ASRock              | 3        | 15%     |
| Gigabyte Technology | 2        | 10%     |
| Hewlett-Packard     | 1        | 5%      |
| HARDKERNEL          | 1        | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| MSI MS-7C37                  | 2        | 10%     |
| MSI MS-7C95                  | 1        | 5%      |
| MSI MS-7C84                  | 1        | 5%      |
| MSI MS-7B09                  | 1        | 5%      |
| HP EliteDesk 800 G2 DM 35W   | 1        | 5%      |
| HARDKERNEL ODROID-H2         | 1        | 5%      |
| Gigabyte X570 AORUS ELITE    | 1        | 5%      |
| Gigabyte H97M-D3H            | 1        | 5%      |
| ASUS Z170-P                  | 1        | 5%      |
| ASUS TUF GAMING X570-PLUS    | 1        | 5%      |
| ASUS ROG STRIX B550-I GAMING | 1        | 5%      |
| ASUS ROG STRIX B550-F GAMING | 1        | 5%      |
| ASUS Pro WS W480-ACE         | 1        | 5%      |
| ASUS PRIME Z390-A            | 1        | 5%      |
| ASUS PRIME Z270-K            | 1        | 5%      |
| ASUS All Series              | 1        | 5%      |
| ASRock X570 Taichi           | 1        | 5%      |
| ASRock TRX40 Creator         | 1        | 5%      |
| ASRock B450 Gaming-ITX/ac    | 1        | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| MSI MS-7C37          | 2        | 10%     |
| ASUS ROG             | 2        | 10%     |
| ASUS PRIME           | 2        | 10%     |
| MSI MS-7C95          | 1        | 5%      |
| MSI MS-7C84          | 1        | 5%      |
| MSI MS-7B09          | 1        | 5%      |
| HP EliteDesk         | 1        | 5%      |
| HARDKERNEL ODROID-H2 | 1        | 5%      |
| Gigabyte X570        | 1        | 5%      |
| Gigabyte H97M-D3H    | 1        | 5%      |
| ASUS Z170-P          | 1        | 5%      |
| ASUS TUF             | 1        | 5%      |
| ASUS Pro             | 1        | 5%      |
| ASUS All             | 1        | 5%      |
| ASRock X570          | 1        | 5%      |
| ASRock TRX40         | 1        | 5%      |
| ASRock B450          | 1        | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 6        | 30%     |
| 2019 | 6        | 30%     |
| 2018 | 2        | 10%     |
| 2016 | 2        | 10%     |
| 2015 | 2        | 10%     |
| 2017 | 1        | 5%      |
| 2014 | 1        | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 20       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 20       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 8        | 40%     |
| 32.01-64.0  | 5        | 25%     |
| 16.01-24.0  | 3        | 15%     |
| 4.01-8.0    | 2        | 10%     |
| 24.01-32.0  | 1        | 5%      |
| 8.01-16.0   | 1        | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 5        | 25%     |
| 8.01-16.0  | 5        | 25%     |
| 32.01-64.0 | 4        | 20%     |
| 3.01-4.0   | 2        | 10%     |
| 1.01-2.0   | 2        | 10%     |
| 24.01-32.0 | 1        | 5%      |
| 16.01-24.0 | 1        | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 7        | 33.33%  |
| 3      | 5        | 23.81%  |
| 1      | 4        | 19.05%  |
| 6      | 3        | 14.29%  |
| 5      | 1        | 4.76%   |
| 0      | 1        | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 85%     |
| Yes       | 3        | 15%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 60%     |
| Yes       | 8        | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 60%     |
| Yes       | 8        | 40%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Germany     | 5        | 25%     |
| USA         | 3        | 15%     |
| Russia      | 2        | 10%     |
| Austria     | 2        | 10%     |
| Ukraine     | 1        | 5%      |
| Serbia      | 1        | 5%      |
| Poland      | 1        | 5%      |
| New Zealand | 1        | 5%      |
| Netherlands | 1        | 5%      |
| Hungary     | 1        | 5%      |
| Denmark     | 1        | 5%      |
| Brazil      | 1        | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Vienna            | 2        | 9.52%   |
| Bensheim          | 2        | 9.52%   |
| Wellington        | 1        | 4.76%   |
| Srednyaya Akhtuba | 1        | 4.76%   |
| San Gabriel       | 1        | 4.76%   |
| Redwood City      | 1        | 4.76%   |
| Ramenskoye        | 1        | 4.76%   |
| Osasco            | 1        | 4.76%   |
| Numansdorp        | 1        | 4.76%   |
| Melrose           | 1        | 4.76%   |
| Kuybyshev         | 1        | 4.76%   |
| Kharkiv           | 1        | 4.76%   |
| Karlsruhe         | 1        | 4.76%   |
| Gdansk            | 1        | 4.76%   |
| Frankfurt am Main | 1        | 4.76%   |
| Esbjerg           | 1        | 4.76%   |
| Elsenfeld         | 1        | 4.76%   |
| Budapest          | 1        | 4.76%   |
| Belgrade          | 1        | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 21     | 29.73%  |
| Seagate             | 5        | 5      | 13.51%  |
| SanDisk             | 4        | 8      | 10.81%  |
| Intel               | 4        | 6      | 10.81%  |
| WDC                 | 3        | 7      | 8.11%   |
| Kingston            | 3        | 3      | 8.11%   |
| Toshiba             | 2        | 2      | 5.41%   |
| Crucial             | 2        | 2      | 5.41%   |
| PLEXTOR             | 1        | 1      | 2.7%    |
| HGST                | 1        | 3      | 2.7%    |
| ASMT                | 1        | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST3000DM001-1ER166 3TB     | 2        | 4.08%   |
| Samsung SSD 970 EVO Plus 2TB       | 2        | 4.08%   |
| Samsung SSD 970 EVO 500GB          | 2        | 4.08%   |
| Samsung SSD 860 QVO 1TB            | 2        | 4.08%   |
| Samsung SSD 860 EVO 2TB            | 2        | 4.08%   |
| Samsung SSD 860 EVO 1TB            | 2        | 4.08%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1        | 2.04%   |
| WDC WD40EFRX-68N32N0 4TB           | 1        | 2.04%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1        | 2.04%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 2.04%   |
| Toshiba TR150 960GB SSD            | 1        | 2.04%   |
| Toshiba HDWL120 2TB                | 1        | 2.04%   |
| Seagate ST3000VX010-2H916L 3TB     | 1        | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 2.04%   |
| Seagate ST1000DM003-1CH162 1TB     | 1        | 2.04%   |
| SanDisk Ultra II 960GB SSD         | 1        | 2.04%   |
| SanDisk SSD PLUS 240GB             | 1        | 2.04%   |
| SanDisk SSD PLUS 240 GB            | 1        | 2.04%   |
| SanDisk SSD PLUS 120 GB            | 1        | 2.04%   |
| SanDisk SDSSDHII240G 240GB         | 1        | 2.04%   |
| SanDisk SDSSDA240G 240GB           | 1        | 2.04%   |
| Sandisk NVMe SSD Drive 1TB         | 1        | 2.04%   |
| Samsung SSD 980 PRO 1TB            | 1        | 2.04%   |
| Samsung SSD 970 PRO 512GB          | 1        | 2.04%   |
| Samsung SSD 970 EVO Plus 1TB       | 1        | 2.04%   |
| Samsung SSD 970 EVO 1TB            | 1        | 2.04%   |
| Samsung SSD 960 EVO 1TB            | 1        | 2.04%   |
| Samsung SSD 850 EVO 250GB          | 1        | 2.04%   |
| Samsung SSD 850 EVO 120GB          | 1        | 2.04%   |
| Samsung NVMe SSD Drive 500GB       | 1        | 2.04%   |
| Samsung NVMe SSD Drive 1TB         | 1        | 2.04%   |
| PLEXTOR PX-512M9PeY 512GB          | 1        | 2.04%   |
| Kingston SVP200S37A60G 64GB SSD    | 1        | 2.04%   |
| Kingston SUV300S37A240G 240GB SSD  | 1        | 2.04%   |
| Kingston SA400S37960G 960GB SSD    | 1        | 2.04%   |
| Intel SSDSC2CT180A3 180GB          | 1        | 2.04%   |
| Intel SSDSC2BW240A4 240GB          | 1        | 2.04%   |
| Intel SSDSC2BW120A4 120GB          | 1        | 2.04%   |
| Intel SSDSA2BW160G3H 160GB         | 1        | 2.04%   |
| HGST HTS721010A9E630 1TB           | 1        | 2.04%   |
| Crucial CT525MX300SSD1 528GB       | 1        | 2.04%   |
| Crucial CT1000MX500SSD1 1TB        | 1        | 2.04%   |
| ASMT 2115 128GB                    | 1        | 2.04%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 5      | 45.45%  |
| WDC     | 3        | 5      | 27.27%  |
| Toshiba | 1        | 1      | 9.09%   |
| HGST    | 1        | 3      | 9.09%   |
| ASMT    | 1        | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 8      | 26.32%  |
| Intel               | 4        | 6      | 21.05%  |
| SanDisk             | 3        | 6      | 15.79%  |
| Kingston            | 3        | 3      | 15.79%  |
| Crucial             | 2        | 2      | 10.53%  |
| WDC                 | 1        | 2      | 5.26%   |
| Toshiba             | 1        | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 15       | 28     | 45.45%  |
| NVMe | 10       | 16     | 30.3%   |
| HDD  | 8        | 15     | 24.24%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 18       | 42     | 62.07%  |
| NVMe | 10       | 16     | 34.48%  |
| SAS  | 1        | 1      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 11       | 16     | 39.29%  |
| 0.01-0.5   | 10       | 19     | 35.71%  |
| 2.01-3.0   | 3        | 3      | 10.71%  |
| 1.01-2.0   | 3        | 3      | 10.71%  |
| 3.01-4.0   | 1        | 2      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 75%     |
| 501-1000   | 2        | 10%     |
| 2001-3000  | 1        | 5%      |
| 101-250    | 1        | 5%      |
| 1-20       | 1        | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| Unknown  | 15       | 75%     |
| 1-20     | 2        | 10%     |
| 251-500  | 1        | 5%      |
| 101-250  | 1        | 5%      |
| 501-1000 | 1        | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 970 EVO 1TB | 1        | 1      | 33.33%  |
| Intel SSDSC2BW240A4 240GB           | 1        | 1      | 33.33%  |
| ASMT 2115 128GB                     | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 33.33%  |
| Intel               | 1        | 1      | 33.33%  |
| ASMT                | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| ASMT   | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 1        | 1      | 33.33%  |
| SSD  | 1        | 1      | 33.33%  |
| HDD  | 1        | 1      | 33.33%  |

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
| Works    | 18       | 51     | 81.82%  |
| Detected | 2        | 5      | 9.09%   |
| Malfunc  | 2        | 3      | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 12       | 36.36%  |
| Samsung Electronics         | 8        | 24.24%  |
| Intel                       | 8        | 24.24%  |
| ASMedia Technology          | 2        | 6.06%   |
| Sandisk                     | 1        | 3.03%   |
| Lite-On Technology          | 1        | 3.03%   |
| Kingston Technology Company | 1        | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 8        | 22.86%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 7        | 20%     |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                      | 3        | 8.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 2        | 5.71%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 2        | 5.71%   |
| Sandisk WD Blue SN550 NVMe SSD                                                | 1        | 2.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1        | 2.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 2.86%   |
| Lite-On Non-Volatile memory controller                                        | 1        | 2.86%   |
| Kingston Company A2000 NVMe SSD                                               | 1        | 2.86%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1        | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1        | 2.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 1        | 2.86%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 1        | 2.86%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                     | 1        | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1        | 2.86%   |
| AMD X399 Series Chipset SATA Controller                                       | 1        | 2.86%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 64.52%  |
| NVMe | 11       | 35.48%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 12       | 60%     |
| Intel  | 8        | 40%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 3800X 8-Core Processor             | 2        | 10%     |
| AMD Ryzen 5 3600X 6-Core Processor             | 2        | 10%     |
| AMD Ryzen 5 3600 6-Core Processor              | 2        | 10%     |
| Intel Xeon W-1290P CPU @ 3.70GHz               | 1        | 5%      |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 5%      |
| Intel Core i7-6850K CPU @ 3.60GHz              | 1        | 5%      |
| Intel Core i7-4790 CPU @ 3.60GHz               | 1        | 5%      |
| Intel Core i5-7600K CPU @ 3.80GHz              | 1        | 5%      |
| Intel Core i5-6500T CPU @ 2.50GHz              | 1        | 5%      |
| Intel Core i3-6100 CPU @ 3.70GHz               | 1        | 5%      |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1        | 5%      |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 1        | 5%      |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 5%      |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 5%      |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 5%      |
| AMD Ryzen 7 3700X 8-Core Processor             | 1        | 5%      |
| AMD Ryzen 5 5600X 6-Core Processor             | 1        | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 5            | 5        | 25%     |
| Intel Core i7          | 3        | 15%     |
| AMD Ryzen 7            | 3        | 15%     |
| Intel Core i5          | 2        | 10%     |
| AMD Ryzen Threadripper | 2        | 10%     |
| AMD Ryzen 9            | 2        | 10%     |
| Intel Xeon             | 1        | 5%      |
| Intel Core i3          | 1        | 5%      |
| Intel Celeron          | 1        | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 6      | 7        | 35%     |
| 4      | 4        | 20%     |
| 8      | 3        | 15%     |
| 12     | 2        | 10%     |
| 32     | 1        | 5%      |
| 16     | 1        | 5%      |
| 10     | 1        | 5%      |
| 2      | 1        | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 20       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 17       | 85%     |
| 1      | 3        | 15%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 20       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x08701021 | 5        | 23.81%  |
| Unknown    | 4        | 19.05%  |
| 0x506e3    | 2        | 9.52%   |
| 0x08701013 | 2        | 9.52%   |
| 0x906ea    | 1        | 4.76%   |
| 0x906e9    | 1        | 4.76%   |
| 0x406f1    | 1        | 4.76%   |
| 0x306c3    | 1        | 4.76%   |
| 0x0a201204 | 1        | 4.76%   |
| 0x0a201009 | 1        | 4.76%   |
| 0x08301025 | 1        | 4.76%   |
| 0x08001137 | 1        | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 9        | 45%     |
| Zen 3         | 2        | 10%     |
| Skylake       | 2        | 10%     |
| KabyLake      | 2        | 10%     |
| Zen           | 1        | 5%      |
| Haswell       | 1        | 5%      |
| Goldmont plus | 1        | 5%      |
| CometLake     | 1        | 5%      |
| Broadwell     | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 12       | 50%     |
| Intel  | 6        | 25%     |
| AMD    | 6        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT] | 5        | 20.83%  |
| Nvidia GP106 [GeForce GTX 1060 6GB]                     | 2        | 8.33%   |
| Nvidia GK104 [GeForce GTX 760]                          | 2        | 8.33%   |
| Intel HD Graphics 530                                   | 2        | 8.33%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                      | 1        | 4.17%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                   | 1        | 4.17%   |
| Nvidia TU106 [GeForce RTX 2070]                         | 1        | 4.17%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                   | 1        | 4.17%   |
| Nvidia GP104 [GeForce GTX 1080]                         | 1        | 4.17%   |
| Nvidia GP104 [GeForce GTX 1070]                         | 1        | 4.17%   |
| Nvidia GM206 [GeForce GTX 960]                          | 1        | 4.17%   |
| Nvidia GM204 [GeForce GTX 970]                          | 1        | 4.17%   |
| Intel UHD P630 Graphics                                 | 1        | 4.17%   |
| Intel HD Graphics 630                                   | 1        | 4.17%   |
| Intel GeminiLake [UHD Graphics 600]                     | 1        | 4.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]               | 1        | 4.17%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 9        | 45%     |
| 1 x Intel      | 4        | 20%     |
| 1 x AMD        | 4        | 20%     |
| AMD + Nvidia   | 2        | 10%     |
| Intel + Nvidia | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 10       | 50%     |
| Proprietary | 9        | 45%     |
| Unknown     | 1        | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 80.95%  |
| 7.01-8.0   | 4        | 19.05%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 7        | 36.84%  |
| Goldstar             | 5        | 26.32%  |
| Acer                 | 2        | 10.53%  |
| Unknown (AAA)        | 1        | 5.26%   |
| HVR                  | 1        | 5.26%   |
| BenQ                 | 1        | 5.26%   |
| AOC                  | 1        | 5.26%   |
| Ancor Communications | 1        | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2        | 9.52%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2        | 9.52%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1        | 4.76%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                        | 1        | 4.76%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch              | 1        | 4.76%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1        | 4.76%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1        | 4.76%   |
| Goldstar HDR 4K GSM7750 3840x2160 697x392mm 31.5-inch                 | 1        | 4.76%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 1        | 4.76%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 1        | 4.76%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                     | 1        | 4.76%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                      | 1        | 4.76%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                      | 1        | 4.76%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 1        | 4.76%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                     | 1        | 4.76%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                     | 1        | 4.76%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                       | 1        | 4.76%   |
| AOC 2280W AOC2280 1920x1080 477x268mm 21.5-inch                       | 1        | 4.76%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 1        | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 1920x1080 (FHD) | 6        | 35.29%  |
| 3840x2160 (4K)  | 5        | 29.41%  |
| 2560x1080       | 3        | 17.65%  |
| 2560x1440 (QHD) | 2        | 11.76%  |
| 2160x1200       | 1        | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 27.78%  |
| 23      | 5        | 27.78%  |
| 34      | 3        | 16.67%  |
| 24      | 2        | 11.11%  |
| 31      | 1        | 5.56%   |
| 21      | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 62.5%   |
| 701-800     | 3        | 18.75%  |
| 601-700     | 1        | 6.25%   |
| 401-500     | 1        | 6.25%   |
| Unknown     | 1        | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 11       | 73.33%  |
| 21/9  | 3        | 20%     |
| 16/10 | 1        | 6.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 36.84%  |
| 301-350        | 5        | 26.32%  |
| 351-500        | 4        | 21.05%  |
| 251-300        | 1        | 5.26%   |
| 151-200        | 1        | 5.26%   |
| Unknown        | 1        | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 9        | 50%     |
| 161-240 | 4        | 22.22%  |
| 101-120 | 3        | 16.67%  |
| 121-160 | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 45%     |
| 0     | 6        | 30%     |
| 2     | 3        | 15%     |
| 3     | 2        | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 40.63%  |
| Intel                 | 13       | 40.63%  |
| Aquantia              | 2        | 6.25%   |
| TP-Link               | 1        | 3.13%   |
| Texas Instruments     | 1        | 3.13%   |
| Oculus VR             | 1        | 3.13%   |
| Microsoft             | 1        | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 28.57%  |
| Intel Wi-Fi 6 AX200                                               | 5        | 14.29%  |
| Intel I211 Gigabit Network Connection                             | 4        | 11.43%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 5.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 2.86%   |
| Texas Instruments CC2538 USB CDC                                  | 1        | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.86%   |
| Oculus VR Rift S                                                  | 1        | 2.86%   |
| Microsoft Xbox 360 Wireless Adapter                               | 1        | 2.86%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.86%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 2.86%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.86%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.86%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.86%   |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 2.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Intel     | 6        | 75%     |
| TP-Link   | 1        | 12.5%   |
| Microsoft | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 5        | 62.5%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1        | 12.5%   |
| Microsoft Xbox 360 Wireless Adapter                        | 1        | 12.5%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 13       | 52%     |
| Intel                 | 10       | 40%     |
| Aquantia              | 2        | 8%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 40%     |
| Intel I211 Gigabit Network Connection                             | 4        | 16%     |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 8%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 4%      |
| Intel Ethernet Controller I225-V                                  | 1        | 4%      |
| Intel Ethernet Controller I225-LM                                 | 1        | 4%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4%      |
| Intel Ethernet Connection (2) I219-V                              | 1        | 4%      |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 4%      |
| Intel Ethernet Connection (2) I218-V                              | 1        | 4%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 4%      |
| Aquantia 5G USB Ethernet Adapter                                  | 1        | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 66.67%  |
| WiFi     | 8        | 26.67%  |
| Modem    | 2        | 6.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 80.95%  |
| WiFi     | 4        | 19.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11       | 55%     |
| 2     | 7        | 35%     |
| 3     | 1        | 5%      |
| 0     | 1        | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 70%     |
| Yes  | 6        | 30%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 4        | 44.44%  |
| Cambridge Silicon Radio  | 2        | 22.22%  |
| ASUSTek Computer         | 2        | 22.22%  |
| HTC (High Tech Computer) | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 3        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 22.22%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 11.11%  |
| HTC (High Tech Computer) BCM920703 Bluetooth 4.1    | 1        | 11.11%  |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 11.11%  |
| ASUS ASUS USB-BT500                                 | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 12       | 30.77%  |
| AMD                        | 12       | 30.77%  |
| Intel                      | 8        | 20.51%  |
| Unknown                    | 1        | 2.56%   |
| Thomann                    | 1        | 2.56%   |
| PreSonus Audio Electronics | 1        | 2.56%   |
| GYROCOM C&C                | 1        | 2.56%   |
| Creative Technology        | 1        | 2.56%   |
| Creative Labs              | 1        | 2.56%   |
| C-Media Electronics        | 1        | 2.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                        | 11       | 24.44%  |
| AMD Navi 10 HDMI Audio                                          | 5        | 11.11%  |
| Nvidia TU116 High Definition Audio Controller                   | 2        | 4.44%   |
| Nvidia TU106 High Definition Audio Controller                   | 2        | 4.44%   |
| Nvidia GP106 High Definition Audio Controller                   | 2        | 4.44%   |
| Nvidia GP104 High Definition Audio Controller                   | 2        | 4.44%   |
| Nvidia GK104 HDMI Audio Controller                              | 2        | 4.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller | 2        | 4.44%   |
| Unknown USB Audio                                               | 1        | 2.22%   |
| Thomann SC450USB                                                | 1        | 2.22%   |
| PreSonus Audio Electronics AudioBox                             | 1        | 2.22%   |
| Nvidia GM206 High Definition Audio Controller                   | 1        | 2.22%   |
| Nvidia GM204 High Definition Audio Controller                   | 1        | 2.22%   |
| Intel Comet Lake PCH cAVS                                       | 1        | 2.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio    | 1        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                      | 1        | 2.22%   |
| Intel C610/X99 series chipset HD Audio Controller               | 1        | 2.22%   |
| Intel 9 Series Chipset Family HD Audio Controller               | 1        | 2.22%   |
| Intel 200 Series PCH HD Audio                                   | 1        | 2.22%   |
| GYROCOM C&C DigiHug USB Audio                                   | 1        | 2.22%   |
| Creative Technology Sound BlasterX G1                           | 1        | 2.22%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]      | 1        | 2.22%   |
| C-Media Electronics USB Advanced Audio Device                   | 1        | 2.22%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                      | 1        | 2.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller             | 1        | 2.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 7        | 33.33%  |
| Corsair             | 7        | 33.33%  |
| G.Skill             | 2        | 9.52%   |
| Crucial             | 2        | 9.52%   |
| Unknown (ABCD)      | 1        | 4.76%   |
| Strontium           | 1        | 4.76%   |
| Samsung Electronics | 1        | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 2        | 8.33%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 2        | 8.33%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s          | 2        | 8.33%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 2        | 8.33%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s       | 2        | 8.33%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 4.17%   |
| Strontium RAM SRT8G86U1-P9H 8GB DIMM DDR3 1600MT/s           | 1        | 4.17%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s               | 1        | 4.17%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s         | 1        | 4.17%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 1        | 4.17%   |
| Kingston RAM KHX2400C15D4/8G 8GB DIMM DDR4 2400MT/s          | 1        | 4.17%   |
| Kingston RAM 9965745-021.A00G 32GB DIMM DDR4 2933MT/s        | 1        | 4.17%   |
| Crucial RAM BLS16G4D32AESE.M16FE 16GB DIMM DDR4 3733MT/s     | 1        | 4.17%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16384MB DIMM DDR4 3200MT/s  | 1        | 4.17%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s        | 1        | 4.17%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s        | 1        | 4.17%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 1        | 4.17%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s        | 1        | 4.17%   |
| Corsair RAM CMD64GX4M4A2666C15 16384MB DIMM DDR4 2133MT/s    | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Desktops | Percent |
|--------|----------|---------|
| DDR4   | 17       | 89.47%  |
| LPDDR4 | 1        | 5.26%   |
| DDR3   | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 18       | 94.74%  |
| SODIMM | 1        | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 9        | 42.86%  |
| 8192  | 7        | 33.33%  |
| 32768 | 4        | 19.05%  |
| 4096  | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 8        | 34.78%  |
| 3600  | 3        | 13.04%  |
| 3334  | 2        | 8.7%    |
| 2400  | 2        | 8.7%    |
| 2133  | 2        | 8.7%    |
| 3733  | 1        | 4.35%   |
| 3533  | 1        | 4.35%   |
| 3400  | 1        | 4.35%   |
| 3266  | 1        | 4.35%   |
| 2933  | 1        | 4.35%   |
| 1600  | 1        | 4.35%   |

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


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| MacroSilicon | 2        | 33.33%  |
| Logitech     | 2        | 33.33%  |
| Microdia     | 1        | 16.67%  |
| Apple        | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| MacroSilicon USB Video    | 2        | 33.33%  |
| Microdia Camera           | 1        | 16.67%  |
| Logitech Webcam C270      | 1        | 16.67%  |
| Logitech C930c            | 1        | 16.67%  |
| Apple iPhone 5/5C/5S/6/SE | 1        | 16.67%  |

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
| 0     | 15       | 75%     |
| 1     | 4        | 20%     |
| 2     | 1        | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 2        | 40%     |
| Net/wireless     | 1        | 20%     |
| Graphics card    | 1        | 20%     |
| Camera           | 1        | 20%     |

