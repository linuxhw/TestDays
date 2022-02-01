Gentoo 2.8 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Gentoo 2.8.

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

| Vendor   | Model                   | Probe                                                      | Date         |
|----------|-------------------------|------------------------------------------------------------|--------------|
| ASRock   | AB350M Pro4             | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Gigabyte | B450M S2H               | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Gigabyte | B450M S2H               | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| Gigabyte | Z490 UD                 | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| ASRock   | X370 Gaming X           | [e233d7c495](https://linux-hardware.org/?probe=e233d7c495) | Jan 09, 2022 |
| EVGA     | Z390 DARK               | [7672395a1c](https://linux-hardware.org/?probe=7672395a1c) | Dec 24, 2021 |
| ASUSTek  | P5LD2-Deluxe            | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4 | [b92f432637](https://linux-hardware.org/?probe=b92f432637) | Dec 07, 2021 |
| MSI      | MPG Z690 EDGE WIFI DDR4 | [d8f50aaa2e](https://linux-hardware.org/?probe=d8f50aaa2e) | Dec 07, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING    | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek  | TUF B450-PLUS GAMING    | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| ASRock   | H110M-HDV R3.0          | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| ASUSTek  | ROG STRIX X570-E GAMING | [e2c087b9c7](https://linux-hardware.org/?probe=e2c087b9c7) | Nov 21, 2021 |
| ASUSTek  | PRIME X570-P            | [eafa22145d](https://linux-hardware.org/?probe=eafa22145d) | Nov 15, 2021 |
| ASUSTek  | TUF GAMING B550-PLUS    | [2900821ed3](https://linux-hardware.org/?probe=2900821ed3) | Nov 14, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING | [4cfb74fb42](https://linux-hardware.org/?probe=4cfb74fb42) | Nov 14, 2021 |
| ASUSTek  | ROG ZENITH II EXTREME   | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| MSI      | H110M PRO-D             | [cb3dcdd186](https://linux-hardware.org/?probe=cb3dcdd186) | Nov 02, 2021 |
| MSI      | H110M PRO-D             | [b53420c26a](https://linux-hardware.org/?probe=b53420c26a) | Nov 02, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING | [161865edb0](https://linux-hardware.org/?probe=161865edb0) | Oct 30, 2021 |
| ASUSTek  | ROG STRIX B550-F GAMING | [a4806aa50f](https://linux-hardware.org/?probe=a4806aa50f) | Oct 30, 2021 |
| ASUSTek  | Z170-A                  | [aea7d9561e](https://linux-hardware.org/?probe=aea7d9561e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X           | [0f4ae74d8e](https://linux-hardware.org/?probe=0f4ae74d8e) | Oct 29, 2021 |
| ASRock   | X370 Gaming X           | [f3f75352e4](https://linux-hardware.org/?probe=f3f75352e4) | Oct 29, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO | [e9cc487951](https://linux-hardware.org/?probe=e9cc487951) | Oct 28, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO | [cb6d9e548b](https://linux-hardware.org/?probe=cb6d9e548b) | Oct 26, 2021 |
| Gigabyte | X570 AORUS MASTER       | [58e3f9c07f](https://linux-hardware.org/?probe=58e3f9c07f) | Oct 23, 2021 |
| ASUSTek  | ROG CROSSHAIR VIII HERO | [eb02a6d4d5](https://linux-hardware.org/?probe=eb02a6d4d5) | Oct 20, 2021 |
| ASRock   | X370 Killer SLI/ac      | [2e4c1c4527](https://linux-hardware.org/?probe=2e4c1c4527) | Oct 17, 2021 |
| Gigabyte | Z87X-UD3H-CF            | [9901023f19](https://linux-hardware.org/?probe=9901023f19) | Oct 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 5.15.10-gentoo               | 3        | 13.64%  |
| 5.14.12-gentoo               | 2        | 9.09%   |
| 6.0.0-Phaco-g8f10ff49057f    | 1        | 4.55%   |
| 5.16.2-gentoo                | 1        | 4.55%   |
| 5.15.6-gentoo                | 1        | 4.55%   |
| 5.15.4-gentoo-deimos         | 1        | 4.55%   |
| 5.15.2-gentoo20210917        | 1        | 4.55%   |
| 5.15.2-gentoo-x86_64         | 1        | 4.55%   |
| 5.15.16-gentoo-dist          | 1        | 4.55%   |
| 5.15.1-gentoo-x86_64         | 1        | 4.55%   |
| 5.15.0-gentoo-x86_64         | 1        | 4.55%   |
| 5.14.6                       | 1        | 4.55%   |
| 5.14.15-gentoo20210917       | 1        | 4.55%   |
| 5.14.14-gentoo-x86_64        | 1        | 4.55%   |
| 5.14.14-gentoo               | 1        | 4.55%   |
| 5.14.13-gentoo               | 1        | 4.55%   |
| 5.14.11-zen1                 | 1        | 4.55%   |
| 5.10.84-gentoo-112-overlayfs | 1        | 4.55%   |
| 5.10.74-gentoo-x86_64        | 1        | 4.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.10 | 3        | 13.64%  |
| 5.15.2  | 2        | 9.09%   |
| 5.14.14 | 2        | 9.09%   |
| 5.14.12 | 2        | 9.09%   |
| 6.0.0   | 1        | 4.55%   |
| 5.16.2  | 1        | 4.55%   |
| 5.15.6  | 1        | 4.55%   |
| 5.15.4  | 1        | 4.55%   |
| 5.15.16 | 1        | 4.55%   |
| 5.15.1  | 1        | 4.55%   |
| 5.15.0  | 1        | 4.55%   |
| 5.14.6  | 1        | 4.55%   |
| 5.14.15 | 1        | 4.55%   |
| 5.14.13 | 1        | 4.55%   |
| 5.14.11 | 1        | 4.55%   |
| 5.10.84 | 1        | 4.55%   |
| 5.10.74 | 1        | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 10       | 45.45%  |
| 5.14    | 8        | 36.36%  |
| 5.10    | 2        | 9.09%   |
| 6.0     | 1        | 4.55%   |
| 5.16    | 1        | 4.55%   |

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
| KDE5    | 10       | 47.62%  |
| GNOME   | 4        | 19.05%  |
| Unknown | 4        | 19.05%  |
| XFCE    | 2        | 9.52%   |
| LXQt    | 1        | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 10       | 47.62%  |
| Wayland | 5        | 23.81%  |
| Tty     | 5        | 23.81%  |
| Unknown | 1        | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 10       | 47.62%  |
| SDDM    | 8        | 38.1%   |
| GDM     | 3        | 14.29%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_GB   | 6        | 30%     |
| en_US   | 5        | 25%     |
| ru_RU   | 2        | 10%     |
| pl_PL   | 2        | 10%     |
| sl_SI   | 1        | 5%      |
| es_ES   | 1        | 5%      |
| el_GR   | 1        | 5%      |
| de_CH   | 1        | 5%      |
| Unknown | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 16       | 76.19%  |
| BIOS | 5        | 23.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 10       | 50%     |
| Btrfs | 7        | 35%     |
| F2fs  | 2        | 10%     |
| Zfs   | 1        | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 18       | 85.71%  |
| Unknown | 3        | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 10       | 50%     |
| No        | 10       | 50%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 60%     |
| Yes       | 8        | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 45%     |
| Gigabyte Technology | 4        | 20%     |
| ASRock              | 4        | 20%     |
| MSI                 | 2        | 10%     |
| EVGA                | 1        | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| MSI MS-7D31                  | 1        | 5%      |
| MSI MS-7996                  | 1        | 5%      |
| Gigabyte Z87X-UD3H           | 1        | 5%      |
| Gigabyte Z490 UD             | 1        | 5%      |
| Gigabyte X570 AORUS MASTER   | 1        | 5%      |
| Gigabyte B450M S2H           | 1        | 5%      |
| EVGA Z390 DARK               | 1        | 5%      |
| ASUS Z170-A                  | 1        | 5%      |
| ASUS TUF GAMING B550-PLUS    | 1        | 5%      |
| ASUS TUF B450-PLUS GAMING    | 1        | 5%      |
| ASUS ROG ZENITH II EXTREME   | 1        | 5%      |
| ASUS ROG STRIX X570-E GAMING | 1        | 5%      |
| ASUS ROG STRIX B550-F GAMING | 1        | 5%      |
| ASUS ROG CROSSHAIR VIII HERO | 1        | 5%      |
| ASUS PRIME X570-P            | 1        | 5%      |
| ASUS P5LD2-Deluxe            | 1        | 5%      |
| ASRock X370 Killer SLI/ac    | 1        | 5%      |
| ASRock X370 Gaming X         | 1        | 5%      |
| ASRock H110M-HDV R3.0        | 1        | 5%      |
| ASRock AB350M Pro4           | 1        | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS ROG           | 4        | 20%     |
| ASUS TUF           | 2        | 10%     |
| ASRock X370        | 2        | 10%     |
| MSI MS-7D31        | 1        | 5%      |
| MSI MS-7996        | 1        | 5%      |
| Gigabyte Z87X-UD3H | 1        | 5%      |
| Gigabyte Z490      | 1        | 5%      |
| Gigabyte X570      | 1        | 5%      |
| Gigabyte B450M     | 1        | 5%      |
| EVGA Z390          | 1        | 5%      |
| ASUS Z170-A        | 1        | 5%      |
| ASUS PRIME         | 1        | 5%      |
| ASUS P5LD2-Deluxe  | 1        | 5%      |
| ASRock H110M-HDV   | 1        | 5%      |
| ASRock AB350M      | 1        | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 4        | 20%     |
| 2019 | 4        | 20%     |
| 2017 | 3        | 15%     |
| 2021 | 2        | 10%     |
| 2018 | 2        | 10%     |
| 2016 | 2        | 10%     |
| 2015 | 1        | 5%      |
| 2013 | 1        | 5%      |
| 2005 | 1        | 5%      |

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
| Disabled | 19       | 95%     |
| Enabled  | 1        | 5%      |

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
| 32.01-64.0  | 8        | 40%     |
| 64.01-256.0 | 6        | 30%     |
| 16.01-24.0  | 3        | 15%     |
| 24.01-32.0  | 2        | 10%     |
| 2.01-3.0    | 1        | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 7        | 33.33%  |
| 1.01-2.0   | 3        | 14.29%  |
| 8.01-16.0  | 3        | 14.29%  |
| 3.01-4.0   | 2        | 9.52%   |
| 2.01-3.0   | 2        | 9.52%   |
| 16.01-24.0 | 2        | 9.52%   |
| 24.01-32.0 | 1        | 4.76%   |
| 0.51-1.0   | 1        | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 3      | 8        | 38.1%   |
| 4      | 4        | 19.05%  |
| 5      | 3        | 14.29%  |
| 1      | 3        | 14.29%  |
| 2      | 2        | 9.52%   |
| 7      | 1        | 4.76%   |

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
| Yes       | 19       | 95%     |
| No        | 1        | 5%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 55%     |
| Yes       | 9        | 45%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 57.14%  |
| No        | 9        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Poland      | 4        | 20%     |
| USA         | 3        | 15%     |
| Russia      | 3        | 15%     |
| UK          | 2        | 10%     |
| Switzerland | 1        | 5%      |
| Spain       | 1        | 5%      |
| Slovenia    | 1        | 5%      |
| Mexico      | 1        | 5%      |
| Greece      | 1        | 5%      |
| Germany     | 1        | 5%      |
| Czechia     | 1        | 5%      |
| Bangladesh  | 1        | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Swansea         | 2        | 10%     |
| Zurich          | 1        | 5%      |
| Vigo            | 1        | 5%      |
| Ufa             | 1        | 5%      |
| Rzesz??w        | 1        | 5%      |
| Redmond         | 1        | 5%      |
| Prague          | 1        | 5%      |
| Moscow          | 1        | 5%      |
| Monroe          | 1        | 5%      |
| Laziska Gorne   | 1        | 5%      |
| Kulmbach        | 1        | 5%      |
| Krakow          | 1        | 5%      |
| Ivan??na Gorica | 1        | 5%      |
| Glen Ellyn      | 1        | 5%      |
| Dhaka           | 1        | 5%      |
| Ciudad Ju??rez  | 1        | 5%      |
| Cieszyn         | 1        | 5%      |
| Blagoveshchensk | 1        | 5%      |
| Athens          | 1        | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 24     | 28%     |
| Samsung Electronics | 9        | 15     | 18%     |
| Seagate             | 5        | 8      | 10%     |
| Toshiba             | 3        | 3      | 6%      |
| Hitachi             | 3        | 4      | 6%      |
| SanDisk             | 2        | 2      | 4%      |
| Intel               | 2        | 2      | 4%      |
| Corsair             | 2        | 2      | 4%      |
| Team                | 1        | 2      | 2%      |
| PLEXTOR             | 1        | 1      | 2%      |
| Phison              | 1        | 1      | 2%      |
| OCZ-VERTEX          | 1        | 1      | 2%      |
| KIOXIA-EXCERIA      | 1        | 1      | 2%      |
| Kingston            | 1        | 1      | 2%      |
| Kingchuxing         | 1        | 2      | 2%      |
| GOODRAM             | 1        | 1      | 2%      |
| Crucial             | 1        | 2      | 2%      |
| A-DATA Technology   | 1        | 1      | 2%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| WDC WD30EFRX-68EUZN0 3TB                   | 2        | 3.28%   |
| Toshiba DT01ACA100 1TB                     | 2        | 3.28%   |
| WDC WDS500G2X0C-00L350 500GB               | 1        | 1.64%   |
| WDC WDS500G2B0B-00YS70 500GB SSD           | 1        | 1.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD           | 1        | 1.64%   |
| WDC WDS240G2G0A 240GB SSD                  | 1        | 1.64%   |
| WDC WD60EFRX-68L0BN1 6TB                   | 1        | 1.64%   |
| WDC WD5000AZLX-00JKKA0 500GB               | 1        | 1.64%   |
| WDC WD30EFRX-68AX9N0 3TB                   | 1        | 1.64%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1.64%   |
| WDC WD20EFRX-68EUZN0 2TB                   | 1        | 1.64%   |
| WDC WD10PURX-64E5EY0 1TB                   | 1        | 1.64%   |
| WDC WD10EZEX-60WN4A1 1TB                   | 1        | 1.64%   |
| WDC WD10EZEX-22M                           | 1        | 1.64%   |
| WDC WD10EZEX-08WN4A0 1TB                   | 1        | 1.64%   |
| WDC WD10EZEX-08M2NA0 1TB                   | 1        | 1.64%   |
| WDC WD10EARS-00MVWB0 1TB                   | 1        | 1.64%   |
| WDC WD10EADS-00L5B1 1TB                    | 1        | 1.64%   |
| WDC WD1002FBYS-18W8B0 1TB                  | 1        | 1.64%   |
| Toshiba THNSN5512GPUK NVMe 512GB           | 1        | 1.64%   |
| Team TM8FP2240G 240GB                      | 1        | 1.64%   |
| Seagate ST4000DM005-2DP166 4TB             | 1        | 1.64%   |
| Seagate ST4000DM004-2CV104 4TB             | 1        | 1.64%   |
| Seagate ST3500630AS 500GB                  | 1        | 1.64%   |
| Seagate ST3250318AS 250GB                  | 1        | 1.64%   |
| Seagate ST3160023AS 160GB                  | 1        | 1.64%   |
| Seagate ST2000DM001-1ER164 2TB             | 1        | 1.64%   |
| Seagate FireCuda 520 SSD ZP2000GM30002 2TB | 1        | 1.64%   |
| SanDisk SSD PLUS 1000GB                    | 1        | 1.64%   |
| SanDisk SDSSDHII480G 480GB                 | 1        | 1.64%   |
| Samsung SSD 980 1TB                        | 1        | 1.64%   |
| Samsung SSD 970 PRO 512GB                  | 1        | 1.64%   |
| Samsung SSD 970 EVO Plus 2TB               | 1        | 1.64%   |
| Samsung SSD 970 EVO Plus 250GB             | 1        | 1.64%   |
| Samsung SSD 970 EVO 500GB                  | 1        | 1.64%   |
| Samsung SSD 860 QVO 4TB                    | 1        | 1.64%   |
| Samsung SSD 860 PRO 1TB                    | 1        | 1.64%   |
| Samsung SSD 860 EVO 2TB                    | 1        | 1.64%   |
| Samsung SSD 840 PRO Series 128GB           | 1        | 1.64%   |
| Samsung Portable SSD T3 250GB              | 1        | 1.64%   |
| Samsung NVMe SSD Drive 512GB               | 1        | 1.64%   |
| Samsung NVMe SSD Drive 500GB               | 1        | 1.64%   |
| Samsung NVMe SSD Drive 1TB                 | 1        | 1.64%   |
| PLEXTOR PX-1TM9PG + 1TB                    | 1        | 1.64%   |
| Phison Sabrent Rocket 4.0 1TB              | 1        | 1.64%   |
| OCZ-VERTEX PLUS R2 128GB SSD               | 1        | 1.64%   |
| KIOXIA-EXCERIA PLUS G2 SSD 500GB           | 1        | 1.64%   |
| Kingston SHSS37A240G 240GB SSD             | 1        | 1.64%   |
| Kingchuxing 512GB                          | 1        | 1.64%   |
| Intel SSDSC2BB120G4 120GB                  | 1        | 1.64%   |
| Intel SSDPEKKW512G8 512GB                  | 1        | 1.64%   |
| Hitachi HUA721010KLA330 1TB                | 1        | 1.64%   |
| Hitachi HDS723020BLA642 2TB                | 1        | 1.64%   |
| Hitachi HDS722020ALA330 2TB                | 1        | 1.64%   |
| GOODRAM SSDPR_CX300_120 120GB              | 1        | 1.64%   |
| Crucial CT1000P1SSD8 1TB                   | 1        | 1.64%   |
| Corsair Force MP600 1TB                    | 1        | 1.64%   |
| Corsair Force 3 SSD 64GB                   | 1        | 1.64%   |
| A-DATA SX8200PNP 1TB                       | 1        | 1.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 12       | 20     | 57.14%  |
| Seagate | 4        | 7      | 19.05%  |
| Hitachi | 3        | 4      | 14.29%  |
| Toshiba | 2        | 2      | 9.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 6      | 33.33%  |
| WDC                 | 3        | 3      | 20%     |
| SanDisk             | 2        | 2      | 13.33%  |
| OCZ-VERTEX          | 1        | 1      | 6.67%   |
| Kingston            | 1        | 1      | 6.67%   |
| Intel               | 1        | 1      | 6.67%   |
| GOODRAM             | 1        | 1      | 6.67%   |
| Corsair             | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 14       | 16     | 34.15%  |
| HDD  | 14       | 33     | 34.15%  |
| NVMe | 13       | 24     | 31.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 19       | 49     | 59.38%  |
| NVMe | 13       | 24     | 40.63%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 10       | 14     | 33.33%  |
| 0.01-0.5   | 10       | 15     | 33.33%  |
| 1.01-2.0   | 5        | 8      | 16.67%  |
| 3.01-4.0   | 2        | 4      | 6.67%   |
| 2.01-3.0   | 2        | 5      | 6.67%   |
| 4.01-10.0  | 1        | 3      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 5        | 23.81%  |
| 251-500        | 4        | 19.05%  |
| 1001-2000      | 4        | 19.05%  |
| More than 3000 | 2        | 9.52%   |
| 1-20           | 2        | 9.52%   |
| 2001-3000      | 1        | 4.76%   |
| 101-250        | 1        | 4.76%   |
| 51-100         | 1        | 4.76%   |
| Unknown        | 1        | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 6        | 28.57%  |
| 1-20           | 3        | 14.29%  |
| 501-1000       | 3        | 14.29%  |
| More than 3000 | 2        | 9.52%   |
| 1001-2000      | 2        | 9.52%   |
| 51-100         | 2        | 9.52%   |
| 21-50          | 1        | 4.76%   |
| 101-250        | 1        | 4.76%   |
| Unknown        | 1        | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB    | 1        | 3      | 12.5%   |
| WDC WD30EFRX-68AX9N0 3TB    | 1        | 2      | 12.5%   |
| WDC WD20EZRX-00D8PB0 2TB    | 1        | 1      | 12.5%   |
| WDC WD1002FBYS-18W8B0 1TB   | 1        | 1      | 12.5%   |
| Seagate ST3160023AS 160GB   | 1        | 1      | 12.5%   |
| SanDisk SSD PLUS 1000GB     | 1        | 1      | 12.5%   |
| Hitachi HUA721010KLA330 1TB | 1        | 1      | 12.5%   |
| Hitachi HDS722020ALA330 2TB | 1        | 2      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 7      | 50%     |
| Hitachi | 2        | 3      | 25%     |
| Seagate | 1        | 1      | 12.5%   |
| SanDisk | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 7      | 57.14%  |
| Hitachi | 2        | 3      | 28.57%  |
| Seagate | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 11     | 83.33%  |
| SSD  | 1        | 1      | 16.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 18       | 52     | 64.29%  |
| Malfunc  | 6        | 12     | 21.43%  |
| Detected | 3        | 8      | 10.71%  |
| Failed   | 1        | 1      | 3.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| AMD                            | 12       | 28.57%  |
| Intel                          | 8        | 19.05%  |
| Samsung Electronics            | 6        | 14.29%  |
| Phison Electronics             | 3        | 7.14%   |
| ASMedia Technology             | 3        | 7.14%   |
| Toshiba America Info Systems   | 1        | 2.38%   |
| Solid State Storage Technology | 1        | 2.38%   |
| Silicon Motion                 | 1        | 2.38%   |
| Silicon Image                  | 1        | 2.38%   |
| Seagate Technology             | 1        | 2.38%   |
| Sandisk                        | 1        | 2.38%   |
| Micron/Crucial Technology      | 1        | 2.38%   |
| Marvell Technology Group       | 1        | 2.38%   |
| KIOXIA                         | 1        | 2.38%   |
| ADATA Technology               | 1        | 2.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10       | 20.83%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 10.42%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 6.25%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 6.25%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2        | 4.17%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 4.17%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 2        | 4.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 4.17%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1        | 2.08%   |
| Solid State Storage Non-Volatile memory controller                             | 1        | 2.08%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 2.08%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1        | 2.08%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 2.08%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 2.08%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 2.08%   |
| Phison E7 NVMe Controller                                                      | 1        | 2.08%   |
| Micron/Crucial NVMe Controller                                                 | 1        | 2.08%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 2.08%   |
| KIOXIA Non-Volatile memory controller                                          | 1        | 2.08%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1        | 2.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.08%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 2.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.08%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 2.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 19       | 55.88%  |
| NVMe | 13       | 38.24%  |
| RAID | 1        | 2.94%   |
| IDE  | 1        | 2.94%   |

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
| AMD Ryzen 9 3950X 16-Core Processor            | 3        | 15%     |
| AMD Ryzen 5 1600 Six-Core Processor            | 2        | 10%     |
| Intel Pentium 4 CPU 3.20GHz                    | 1        | 5%      |
| Intel Core i9-9900K CPU @ 3.60GHz              | 1        | 5%      |
| Intel Core i7-6700K CPU @ 4.00GHz              | 1        | 5%      |
| Intel Core i7-10700F CPU @ 2.90GHz             | 1        | 5%      |
| Intel Core i5-7400 CPU @ 3.00GHz               | 1        | 5%      |
| Intel Core i5-6400 CPU @ 2.70GHz               | 1        | 5%      |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 5%      |
| Intel 12th Gen Core i7-12700K                  | 1        | 5%      |
| AMD Ryzen Threadripper 3960X 24-Core Processor | 1        | 5%      |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 5%      |
| AMD Ryzen 9 3900X 12-Core Processor            | 1        | 5%      |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics     | 1        | 5%      |
| AMD Ryzen 7 1700X Eight-Core Processor         | 1        | 5%      |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 5%      |
| AMD Ryzen 5 2600 Six-Core Processor            | 1        | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| AMD Ryzen 9            | 5        | 25%     |
| AMD Ryzen 5            | 4        | 20%     |
| Intel Core i5          | 3        | 15%     |
| Intel Core i7          | 2        | 10%     |
| Other                  | 1        | 5%      |
| Intel Pentium 4        | 1        | 5%      |
| Intel Core i9          | 1        | 5%      |
| AMD Ryzen Threadripper | 1        | 5%      |
| AMD Ryzen 7 PRO        | 1        | 5%      |
| AMD Ryzen 7            | 1        | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 16     | 4        | 20%     |
| 8      | 4        | 20%     |
| 6      | 4        | 20%     |
| 4      | 4        | 20%     |
| 12     | 2        | 10%     |
| 24     | 1        | 5%      |
| 1      | 1        | 5%      |

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
| Unknown    | 4        | 20%     |
| 0x08701021 | 3        | 15%     |
| 0x08001138 | 3        | 15%     |
| 0xf43      | 1        | 5%      |
| 0xa0655    | 1        | 5%      |
| 0x906ed    | 1        | 5%      |
| 0x906e9    | 1        | 5%      |
| 0x90672    | 1        | 5%      |
| 0x506e3    | 1        | 5%      |
| 0x0a50000b | 1        | 5%      |
| 0x0a201016 | 1        | 5%      |
| 0x08301039 | 1        | 5%      |
| 0x0800820d | 1        | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 6        | 30%     |
| Zen              | 3        | 15%     |
| Zen 3            | 2        | 10%     |
| Skylake          | 2        | 10%     |
| KabyLake         | 2        | 10%     |
| Zen+             | 1        | 5%      |
| NetBurst         | 1        | 5%      |
| Haswell          | 1        | 5%      |
| CometLake        | 1        | 5%      |
| Alderlake Hybrid | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 11       | 47.83%  |
| Nvidia | 8        | 34.78%  |
| Intel  | 4        | 17.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]             | 5        | 20.83%  |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                      | 3        | 12.5%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                 | 2        | 8.33%   |
| Nvidia TU116 [GeForce GTX 1650]                                     | 1        | 4.17%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                           | 1        | 4.17%   |
| Nvidia GP108 [GeForce GT 1030]                                      | 1        | 4.17%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                  | 1        | 4.17%   |
| Nvidia GM206 [GeForce GTX 960]                                      | 1        | 4.17%   |
| Nvidia GM204 [GeForce GTX 970]                                      | 1        | 4.17%   |
| Intel HD Graphics 630                                               | 1        | 4.17%   |
| Intel HD Graphics 530                                               | 1        | 4.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                           | 1        | 4.17%   |
| Intel AlderLake-S GT1                                               | 1        | 4.17%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                      | 1        | 4.17%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                        | 1        | 4.17%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 4.17%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X] | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 8        | 40%     |
| 1 x Nvidia     | 5        | 25%     |
| 1 x Intel      | 2        | 10%     |
| AMD + Nvidia   | 2        | 10%     |
| Other          | 1        | 5%      |
| 2 x AMD        | 1        | 5%      |
| Intel + Nvidia | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 60%     |
| Proprietary | 6        | 30%     |
| Unknown     | 2        | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 8        | 38.1%   |
| 8.01-16.0  | 5        | 23.81%  |
| 3.01-4.0   | 4        | 19.05%  |
| 7.01-8.0   | 2        | 9.52%   |
| 1.01-2.0   | 1        | 4.76%   |
| 0.51-1.0   | 1        | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Hewlett-Packard         | 2        | 8%      |
| Goldstar                | 2        | 8%      |
| Dell                    | 2        | 8%      |
| BenQ                    | 2        | 8%      |
| AOC                     | 2        | 8%      |
| Acer                    | 2        | 8%      |
| Toshiba                 | 1        | 4%      |
| Samsung Electronics     | 1        | 4%      |
| NEC Computers           | 1        | 4%      |
| MStar                   | 1        | 4%      |
| Mi                      | 1        | 4%      |
| Lenovo                  | 1        | 4%      |
| Iiyama                  | 1        | 4%      |
| HannStar                | 1        | 4%      |
| Gigabyte Technology     | 1        | 4%      |
| Gateway                 | 1        | 4%      |
| Chi Mei Optoelectronics | 1        | 4%      |
| Belinea                 | 1        | 4%      |
| ASUSTek Computer        | 1        | 4%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Toshiba PA3552 TOS501C 1680x1050 433x270mm 20.1-inch                   | 1        | 3.57%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 1        | 3.57%   |
| NEC Computers EA274WMi NEC6960 2560x1440 597x336mm 27.0-inch           | 1        | 3.57%   |
| MStar DP MST2380 2560x1440 597x336mm 27.0-inch                         | 1        | 3.57%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                       | 1        | 3.57%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                   | 1        | 3.57%   |
| Iiyama PL2792Q IVM6630 2560x1440 597x336mm 27.0-inch                   | 1        | 3.57%   |
| Hewlett-Packard LV1561w HWP2837 1366x768 344x194mm 15.5-inch           | 1        | 3.57%   |
| Hewlett-Packard LP2475w HWP26F9 1920x1200 546x352mm 25.6-inch          | 1        | 3.57%   |
| Hewlett-Packard 22f HPN3541 1920x1080 476x268mm 21.5-inch              | 1        | 3.57%   |
| HannStar JC198D HSD0CC6 1280x1024 376x301mm 19.0-inch                  | 1        | 3.57%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch               | 1        | 3.57%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch               | 1        | 3.57%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 1        | 3.57%   |
| Gigabyte Technology AORUS AD27QD GBT2701 2560x1440 610x350mm 27.7-inch | 1        | 3.57%   |
| Gateway FPD1765 GWY06E9 1280x1024 338x270mm 17.0-inch                  | 1        | 3.57%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 1        | 3.57%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                      | 1        | 3.57%   |
| Dell S3221QS DELD107 3840x2160 697x392mm 31.5-inch                     | 1        | 3.57%   |
| Chi Mei Optoelectronics CMC 19AW CMO2198 1440x900 408x255mm 18.9-inch  | 1        | 3.57%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 1        | 3.57%   |
| BenQ E2200HD BNQ790C 1920x1080 477x268mm 21.5-inch                     | 1        | 3.57%   |
| Belinea Belinea101735 MAX06B2 1280x1024 338x270mm 17.0-inch            | 1        | 3.57%   |
| ASUSTek Computer VG27A AUS2723 2560x1440 597x336mm 27.0-inch           | 1        | 3.57%   |
| AOC 2437 AOC2437 1920x1080 521x293mm 23.5-inch                         | 1        | 3.57%   |
| AOC 2269WM AOC2269 1920x1080 480x270mm 21.7-inch                       | 1        | 3.57%   |
| Acer VG270U P ACR06CF 2560x1440 597x336mm 27.0-inch                    | 1        | 3.57%   |
| Acer K272HUL ACR03DD 2560x1440 597x336mm 27.0-inch                     | 1        | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 2560x1440 (QHD)    | 9        | 34.62%  |
| 1920x1080 (FHD)    | 5        | 19.23%  |
| 3840x2160 (4K)     | 2        | 7.69%   |
| 3440x1440          | 2        | 7.69%   |
| 1280x1024 (SXGA)   | 2        | 7.69%   |
| 3840x1080          | 1        | 3.85%   |
| 2560x1080          | 1        | 3.85%   |
| 1920x1200 (WUXGA)  | 1        | 3.85%   |
| 1680x1050 (WSXGA+) | 1        | 3.85%   |
| 1440x900 (WXGA+)   | 1        | 3.85%   |
| 1366x768 (WXGA)    | 1        | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 9        | 32.14%  |
| 34     | 3        | 10.71%  |
| 23     | 3        | 10.71%  |
| 25     | 2        | 7.14%   |
| 21     | 2        | 7.14%   |
| 19     | 2        | 7.14%   |
| 17     | 2        | 7.14%   |
| 49     | 1        | 3.57%   |
| 31     | 1        | 3.57%   |
| 24     | 1        | 3.57%   |
| 20     | 1        | 3.57%   |
| 15     | 1        | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 44%     |
| 401-500     | 4        | 16%     |
| 701-800     | 3        | 12%     |
| 301-350     | 3        | 12%     |
| 601-700     | 2        | 8%      |
| 351-400     | 1        | 4%      |
| 1001-1500   | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 15       | 62.5%   |
| 21/9  | 3        | 12.5%   |
| 16/10 | 3        | 12.5%   |
| 5/4   | 2        | 8.33%   |
| 32/9  | 1        | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 301-350        | 9        | 33.33%  |
| 201-250        | 5        | 18.52%  |
| 351-500        | 4        | 14.81%  |
| 151-200        | 3        | 11.11%  |
| 251-300        | 2        | 7.41%   |
| 141-150        | 2        | 7.41%   |
| 101-110        | 1        | 3.7%    |
| 501-1000       | 1        | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 12       | 52.17%  |
| 51-100  | 8        | 34.78%  |
| 1-50    | 1        | 4.35%   |
| 161-240 | 1        | 4.35%   |
| 121-160 | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 45%     |
| 2     | 8        | 40%     |
| 0     | 2        | 10%     |
| 3     | 1        | 5%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 11       | 37.93%  |
| Intel                    | 11       | 37.93%  |
| Aquantia                 | 2        | 6.9%    |
| Raspberry Pi             | 1        | 3.45%   |
| Ralink Technology        | 1        | 3.45%   |
| Qualcomm Atheros         | 1        | 3.45%   |
| Microsoft                | 1        | 3.45%   |
| Marvell Technology Group | 1        | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 16.22%  |
| Intel I211 Gigabit Network Connection                             | 5        | 13.51%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 10.81%  |
| Intel Wi-Fi 6 AX200                                               | 3        | 8.11%   |
| Intel Ethernet Controller I225-V                                  | 2        | 5.41%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 5.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 2.7%    |
| Raspberry Pi Pico                                                 | 1        | 2.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 2.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 2.7%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 1        | 2.7%    |
| Microsoft XBOX ACC                                                | 1        | 2.7%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 2.7%    |
| Intel Wireless-AC 9260                                            | 1        | 2.7%    |
| Intel I210 Gigabit Network Connection                             | 1        | 2.7%    |
| Intel Ethernet Connection I217-V                                  | 1        | 2.7%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.7%    |
| Intel Ethernet Connection (2) I219-V                              | 1        | 2.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1        | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 2.7%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 2.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 7        | 70%     |
| Ralink Technology | 1        | 10%     |
| Qualcomm Atheros  | 1        | 10%     |
| Microsoft         | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 3        | 27.27%  |
| Ralink RT2870/RT3070 Wireless Adapter                      | 1        | 9.09%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 9.09%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter | 1        | 9.09%   |
| Microsoft XBOX ACC                                         | 1        | 9.09%   |
| Intel Wireless-AC 9260                                     | 1        | 9.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 1        | 9.09%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1        | 9.09%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 1        | 9.09%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 11       | 45.83%  |
| Intel                    | 10       | 41.67%  |
| Aquantia                 | 2        | 8.33%   |
| Marvell Technology Group | 1        | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6        | 24%     |
| Intel I211 Gigabit Network Connection                             | 5        | 20%     |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 16%     |
| Intel Ethernet Controller I225-V                                  | 2        | 8%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 8%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 4%      |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 4%      |
| Intel I210 Gigabit Network Connection                             | 1        | 4%      |
| Intel Ethernet Connection I217-V                                  | 1        | 4%      |
| Intel Ethernet Connection (7) I219-V                              | 1        | 4%      |
| Intel Ethernet Connection (2) I219-V                              | 1        | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 65.52%  |
| WiFi     | 9        | 31.03%  |
| Modem    | 1        | 3.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 77.27%  |
| WiFi     | 5        | 22.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 45%     |
| 2     | 6        | 30%     |
| 3     | 4        | 20%     |
| 0     | 1        | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 75%     |
| Yes  | 5        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 8        | 66.67%  |
| Cambridge Silicon Radio | 2        | 16.67%  |
| Realtek Semiconductor   | 1        | 8.33%   |
| ASUSTek Computer        | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth Device                              | 5        | 41.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 16.67%  |
| Realtek Bluetooth Radio                             | 1        | 8.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 8.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 15       | 34.09%  |
| Nvidia                               | 8        | 18.18%  |
| Intel                                | 7        | 15.91%  |
| Thesycon Systemsoftware & Consulting | 2        | 4.55%   |
| Logitech                             | 2        | 4.55%   |
| C-Media Electronics                  | 2        | 4.55%   |
| ASUSTek Computer                     | 2        | 4.55%   |
| SteelSeries ApS                      | 1        | 2.27%   |
| SAVITECH                             | 1        | 2.27%   |
| RODE Microphones                     | 1        | 2.27%   |
| Creative Technology                  | 1        | 2.27%   |
| Creative Labs                        | 1        | 2.27%   |
| AudioQuest                           | 1        | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 7        | 12.96%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 5        | 9.26%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]               | 4        | 7.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 4        | 7.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 3        | 5.56%   |
| Thesycon Systemsoftware & Consulting E30                                | 2        | 3.7%    |
| Nvidia GP106 High Definition Audio Controller                           | 2        | 3.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]            | 2        | 3.7%    |
| SteelSeries ApS Arctis 7 wireless adapter                               | 1        | 1.85%   |
| SAVITECH SA9023 audio controller                                        | 1        | 1.85%   |
| RODE Microphones RODE VideoMic NTG                                      | 1        | 1.85%   |
| Nvidia TU116 High Definition Audio Controller                           | 1        | 1.85%   |
| Nvidia TU102 High Definition Audio Controller                           | 1        | 1.85%   |
| Nvidia GP108 High Definition Audio Controller                           | 1        | 1.85%   |
| Nvidia GP102 HDMI Audio Controller                                      | 1        | 1.85%   |
| Nvidia GM206 High Definition Audio Controller                           | 1        | 1.85%   |
| Nvidia GM204 High Definition Audio Controller                           | 1        | 1.85%   |
| Logitech Z-5 Speakers                                                   | 1        | 1.85%   |
| Logitech Yeti X                                                         | 1        | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                 | 1        | 1.85%   |
| Intel Comet Lake PCH cAVS                                               | 1        | 1.85%   |
| Intel Cannon Lake PCH cAVS                                              | 1        | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 1        | 1.85%   |
| Creative Technology Sound BlasterX G6                                   | 1        | 1.85%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]           | 1        | 1.85%   |
| C-Media Electronics USB Advanced Audio Device                           | 1        | 1.85%   |
| C-Media Electronics CM108 Audio Controller                              | 1        | 1.85%   |
| AudioQuest SDAC                                                         | 1        | 1.85%   |
| ASUSTek Computer Xonar U1 Audio Station                                 | 1        | 1.85%   |
| ASUSTek Computer USB Audio                                              | 1        | 1.85%   |
| AMD Renoir Radeon High Definition Audio Controller                      | 1        | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1        | 1.85%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                     | 1        | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 6        | 28.57%  |
| G.Skill             | 5        | 23.81%  |
| Kingston            | 4        | 19.05%  |
| Unknown             | 1        | 4.76%   |
| Team                | 1        | 4.76%   |
| Samsung Electronics | 1        | 4.76%   |
| Patriot             | 1        | 4.76%   |
| Corsair             | 1        | 4.76%   |
| A-DATA Technology   | 1        | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM SDRAM                         | 1        | 4.17%   |
| Unknown RAM Module 1GB DIMM SDRAM                           | 1        | 4.17%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s          | 1        | 4.17%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 2666MT/s        | 1        | 4.17%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s         | 1        | 4.17%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 1        | 4.17%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 1867MT/s      | 1        | 4.17%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s       | 1        | 4.17%   |
| Kingston RAM 9905625-062.A00G 8192MB DIMM DDR4 2133MT/s     | 1        | 4.17%   |
| G.Skill RAM F4-3600C17-16GTZR 16GB DIMM DDR4 3666MT/s       | 1        | 4.17%   |
| G.Skill RAM F4-3600C17-16GTZKW 16GB DIMM DDR4 3600MT/s      | 1        | 4.17%   |
| G.Skill RAM F4-3600C16-16GVKC 16384MB DIMM DDR4 3866MT/s    | 1        | 4.17%   |
| G.Skill RAM F4-3000C15-8GVRB 8GB DIMM DDR4 2133MT/s         | 1        | 4.17%   |
| G.Skill RAM F3-14900CL9-4GBSR 4GB DIMM DDR3 1800MT/s        | 1        | 4.17%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s       | 1        | 4.17%   |
| Crucial RAM CT8G4DFD824A.C16FBD1 8GB DIMM DDR4 2400MT/s     | 1        | 4.17%   |
| Crucial RAM CT16G4DFD8213.C16FAD 16GB DIMM DDR4 2133MT/s    | 1        | 4.17%   |
| Crucial RAM BLS4G4D26BFSE.8FE 4GB DIMM DDR4 2667MT/s        | 1        | 4.17%   |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4             | 1        | 4.17%   |
| Crucial RAM BL16G36C16U4RL.M8FB1 16GB DIMM DDR4 4000MT/s    | 1        | 4.17%   |
| Crucial RAM BL16G32C16U4B.M16FE1 16384MB DIMM DDR4 3200MT/s | 1        | 4.17%   |
| Crucial RAM BL16G32C16U4B.M16FE 16GB DIMM DDR4 3200MT/s     | 1        | 4.17%   |
| Corsair RAM CMK32GX4M2B3200C16 16384MB DIMM DDR4 3400MT/s   | 1        | 4.17%   |
| A-DATA RAM DDR4 3000 2OZ 16GB DIMM DDR4 3000MT/s            | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 16       | 88.89%  |
| SDRAM | 1        | 5.56%   |
| DDR3  | 1        | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 18       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 12       | 54.55%  |
| 8192  | 4        | 18.18%  |
| 32768 | 2        | 9.09%   |
| 4096  | 2        | 9.09%   |
| 1024  | 1        | 4.55%   |
| 512   | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 4        | 18.18%  |
| 2133    | 4        | 18.18%  |
| 3200    | 3        | 13.64%  |
| 4000    | 1        | 4.55%   |
| 3866    | 1        | 4.55%   |
| 3666    | 1        | 4.55%   |
| 3400    | 1        | 4.55%   |
| 3000    | 1        | 4.55%   |
| 2733    | 1        | 4.55%   |
| 2667    | 1        | 4.55%   |
| 2666    | 1        | 4.55%   |
| 2400    | 1        | 4.55%   |
| 1800    | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

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
| Logitech                      | 3        | 50%     |
| Sunplus Innovation Technology | 1        | 16.67%  |
| Generalplus Technology        | 1        | 16.67%  |
| Creative Technology           | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Sunplus Full HD webcam            | 1        | 16.67%  |
| Logitech Webcam C270              | 1        | 16.67%  |
| Logitech StreamCam                | 1        | 16.67%  |
| Logitech QuickCam Orbit/Sphere AF | 1        | 16.67%  |
| Generalplus GENERAL WEBCAM        | 1        | 16.67%  |
| Creative Live! Cam Sync 1080p     | 1        | 16.67%  |

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
| 0     | 15       | 71.43%  |
| 1     | 4        | 19.05%  |
| 4     | 1        | 4.76%   |
| 2     | 1        | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 4        | 44.44%  |
| Net/wireless             | 1        | 11.11%  |
| Modem                    | 1        | 11.11%  |
| Graphics card            | 1        | 11.11%  |
| Camera                   | 1        | 11.11%  |
| Bluetooth                | 1        | 11.11%  |

