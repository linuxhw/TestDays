Parrot 5.0 - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Parrot 5.0.

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

Total: 36

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550-PLUS         | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS         | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| ASUSTek       | H110M-K                 | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| ASUSTek       | H110M-K                 | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| Gigabyte      | H61M-USB3H              | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Lenovo        | 31900058 STD            | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF           | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| MSI           | G31M3-L V2              | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| HP            | 1495                    | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | PRIME H310M-D R2.0      | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                    | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                  | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | B350 TOMAHAWK           | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| ECS           | Nettle2                 | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                    | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| Lenovo        | SHARKBAY 31900058 STD   | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD   | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                  | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3              | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| ASUSTek       | H170M-E D3              | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| ASRock        | Z87M Extreme4           | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | B85M-E                  | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                  | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Dell          | 0GXM1W A02              | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| SLIMBOOK      | ONE-AMD-M4              | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Unknown       | Unknown                 | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Dell          | 04YP6J A01              | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01              | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF            | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF            | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.0-12parrot1-amd64   | 10       | 38.46%  |
| 5.14.0-9parrot1-amd64    | 9        | 34.62%  |
| 5.15.0-15parrot1-amd64   | 4        | 15.38%  |
| 5.18.0-1parrot1-amd64    | 1        | 3.85%   |
| 5.16.0-12parrot1-686-pae | 1        | 3.85%   |
| 5.14.0-2parrot1-amd64    | 1        | 3.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16.0  | 11       | 44%     |
| 5.14.0  | 9        | 36%     |
| 5.15.0  | 4        | 16%     |
| 5.18.0  | 1        | 4%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 11       | 44%     |
| 5.14    | 9        | 36%     |
| 5.15    | 4        | 16%     |
| 5.18    | 1        | 4%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 22       | 95.65%  |
| i686   | 1        | 4.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 17       | 73.91%  |
| XFCE    | 2        | 8.7%    |
| KDE5    | 2        | 8.7%    |
| GNOME   | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 21       | 91.3%   |
| Wayland | 2        | 8.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 13       | 56.52%  |
| Unknown | 8        | 34.78%  |
| SDDM    | 1        | 4.35%   |
| GDM     | 1        | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 47.83%  |
| pt_BR | 3        | 13.04%  |
| en_IN | 2        | 8.7%    |
| ru_RU | 1        | 4.35%   |
| pl_PL | 1        | 4.35%   |
| fr_FR | 1        | 4.35%   |
| es_ES | 1        | 4.35%   |
| en_GB | 1        | 4.35%   |
| en_DK | 1        | 4.35%   |
| cs_CZ | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 15       | 65.22%  |
| EFI  | 8        | 34.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 19       | 82.61%  |
| Ext4    | 3        | 13.04%  |
| Overlay | 1        | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 11       | 47.83%  |
| Unknown | 9        | 39.13%  |
| MBR     | 3        | 13.04%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 86.96%  |
| Yes       | 3        | 13.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 60.87%  |
| Yes       | 9        | 39.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 6        | 26.09%  |
| Hewlett-Packard     | 3        | 13.04%  |
| Gigabyte Technology | 3        | 13.04%  |
| MSI                 | 2        | 8.7%    |
| Lenovo              | 2        | 8.7%    |
| Dell                | 2        | 8.7%    |
| SLIMBOOK            | 1        | 4.35%   |
| ECS                 | 1        | 4.35%   |
| Daewoo Lucoms       | 1        | 4.35%   |
| ASRock              | 1        | 4.35%   |
| Unknown             | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| HP ProDesk 600 G1 SFF        | 2        | 8.7%    |
| SLIMBOOK ONE-AMD-M4          | 1        | 4.35%   |
| MSI MS-7A34                  | 1        | 4.35%   |
| MSI MS-7529                  | 1        | 4.35%   |
| Lenovo H535 10117            | 1        | 4.35%   |
| Lenovo H530 10130            | 1        | 4.35%   |
| HP Compaq 8200 Elite SFF PC  | 1        | 4.35%   |
| Gigabyte H61M-USB3H          | 1        | 4.35%   |
| Gigabyte B450M DS3H          | 1        | 4.35%   |
| Gigabyte A320M-S2H           | 1        | 4.35%   |
| ECS GV460AA-ABA a6217c       | 1        | 4.35%   |
| Dell OptiPlex 7010           | 1        | 4.35%   |
| Dell OptiPlex 3020           | 1        | 4.35%   |
| Daewoo Lucoms OEM            | 1        | 4.35%   |
| ASUS ROG CROSSHAIR VIII HERO | 1        | 4.35%   |
| ASUS PRIME H310M-D R2.0      | 1        | 4.35%   |
| ASUS PRIME B550-PLUS         | 1        | 4.35%   |
| ASUS H170M-E D3              | 1        | 4.35%   |
| ASUS H110M-K                 | 1        | 4.35%   |
| ASUS Basic 3221BM            | 1        | 4.35%   |
| ASRock Z87M Extreme4         | 1        | 4.35%   |
| Unknown                      | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP ProDesk          | 2        | 8.7%    |
| Dell OptiPlex       | 2        | 8.7%    |
| ASUS PRIME          | 2        | 8.7%    |
| SLIMBOOK ONE-AMD-M4 | 1        | 4.35%   |
| MSI MS-7A34         | 1        | 4.35%   |
| MSI MS-7529         | 1        | 4.35%   |
| Lenovo H535         | 1        | 4.35%   |
| Lenovo H530         | 1        | 4.35%   |
| HP Compaq           | 1        | 4.35%   |
| Gigabyte H61M-USB3H | 1        | 4.35%   |
| Gigabyte B450M      | 1        | 4.35%   |
| Gigabyte A320M-S2H  | 1        | 4.35%   |
| ECS GV460AA-ABA     | 1        | 4.35%   |
| Daewoo Lucoms OEM   | 1        | 4.35%   |
| ASUS ROG            | 1        | 4.35%   |
| ASUS H170M-E        | 1        | 4.35%   |
| ASUS H110M-K        | 1        | 4.35%   |
| ASUS Basic          | 1        | 4.35%   |
| ASRock Z87M         | 1        | 4.35%   |
| Unknown             | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 7        | 30.43%  |
| 2021 | 2        | 8.7%    |
| 2018 | 2        | 8.7%    |
| 2017 | 2        | 8.7%    |
| 2015 | 2        | 8.7%    |
| 2020 | 1        | 4.35%   |
| 2019 | 1        | 4.35%   |
| 2016 | 1        | 4.35%   |
| 2012 | 1        | 4.35%   |
| 2011 | 1        | 4.35%   |
| 2010 | 1        | 4.35%   |
| 2009 | 1        | 4.35%   |
| 2007 | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 23       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 7        | 29.17%  |
| 32.01-64.0 | 5        | 20.83%  |
| 8.01-16.0  | 5        | 20.83%  |
| 3.01-4.0   | 3        | 12.5%   |
| 16.01-24.0 | 3        | 12.5%   |
| 1.01-2.0   | 1        | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 9        | 37.5%   |
| 1.01-2.0   | 6        | 25%     |
| 4.01-8.0   | 3        | 12.5%   |
| 3.01-4.0   | 3        | 12.5%   |
| 0.51-1.0   | 2        | 8.33%   |
| 16.01-24.0 | 1        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 11       | 47.83%  |
| 1      | 8        | 34.78%  |
| 6      | 1        | 4.35%   |
| 5      | 1        | 4.35%   |
| 4      | 1        | 4.35%   |
| 3      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 75%     |
| Yes       | 6        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 23       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 78.26%  |
| No        | 5        | 21.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 82.61%  |
| Yes       | 4        | 17.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 5        | 20.83%  |
| Brazil      | 3        | 12.5%   |
| Netherlands | 2        | 8.33%   |
| India       | 2        | 8.33%   |
| UK          | 1        | 4.17%   |
| Spain       | 1        | 4.17%   |
| Russia      | 1        | 4.17%   |
| Romania     | 1        | 4.17%   |
| Morocco     | 1        | 4.17%   |
| Mongolia    | 1        | 4.17%   |
| France      | 1        | 4.17%   |
| Egypt       | 1        | 4.17%   |
| Denmark     | 1        | 4.17%   |
| Czechia     | 1        | 4.17%   |
| Canada      | 1        | 4.17%   |
| Austria     | 1        | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Vienna               | 1        | 4.17%   |
| Viby J               | 1        | 4.17%   |
| Vapi                 | 1        | 4.17%   |
| Ulan Bator           | 1        | 4.17%   |
| Uherské Hradiště  | 1        | 4.17%   |
| Tangier              | 1        | 4.17%   |
| Springfield          | 1        | 4.17%   |
| Sao Paulo            | 1        | 4.17%   |
| Sao Joao de Meriti   | 1        | 4.17%   |
| Santa Maria          | 1        | 4.17%   |
| Point Pleasant Beach | 1        | 4.17%   |
| Montreal             | 1        | 4.17%   |
| Milton               | 1        | 4.17%   |
| Long Eaton           | 1        | 4.17%   |
| Lille                | 1        | 4.17%   |
| Krasnogorsk          | 1        | 4.17%   |
| Iasi                 | 1        | 4.17%   |
| Guadalajara          | 1        | 4.17%   |
| Darien               | 1        | 4.17%   |
| D'Iberville          | 1        | 4.17%   |
| Bussum               | 1        | 4.17%   |
| Beri Khas            | 1        | 4.17%   |
| Amsterdam            | 1        | 4.17%   |
| Alexandria           | 1        | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 15     | 28.57%  |
| WDC                 | 9        | 11     | 21.43%  |
| Samsung Electronics | 6        | 12     | 14.29%  |
| Toshiba             | 4        | 4      | 9.52%   |
| SanDisk             | 2        | 5      | 4.76%   |
| Kingston            | 2        | 2      | 4.76%   |
| Unknown             | 1        | 1      | 2.38%   |
| SPCC                | 1        | 1      | 2.38%   |
| Silicon Motion      | 1        | 1      | 2.38%   |
| PNY                 | 1        | 1      | 2.38%   |
| Plextor             | 1        | 1      | 2.38%   |
| China               | 1        | 2      | 2.38%   |
| A-DATA Technology   | 1        | 1      | 2.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA200 2TB              | 2        | 4.17%   |
| Seagate ST250DM000-1BD141 250GB     | 2        | 4.17%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1        | 2.08%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 2.08%   |
| WDC WDBRPG5000ANC-WRSN 500GB        | 1        | 2.08%   |
| WDC WD5000AADS-00S9B0 500GB         | 1        | 2.08%   |
| WDC WD20EZAZ-00GGJB0 2TB            | 1        | 2.08%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 2.08%   |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 2.08%   |
| WDC WD10EZRX-00L4HB0 1TB            | 1        | 2.08%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 2.08%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 2.08%   |
| Unknown 256GB PCS 2.5" S            | 1        | 2.08%   |
| Toshiba HDWD105 500GB               | 1        | 2.08%   |
| Toshiba DT01ACA050 500GB            | 1        | 2.08%   |
| SPCC Solid State Disk 240GB         | 1        | 2.08%   |
| Silicon Motion NVMe SSD Drive 128GB | 1        | 2.08%   |
| Seagate ST9500325AS 500GB           | 1        | 2.08%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 2.08%   |
| Seagate ST500LM000-SSHD-8GB         | 1        | 2.08%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 2.08%   |
| Seagate ST3500312CS 500GB           | 1        | 2.08%   |
| Seagate ST3320418AS 320GB           | 1        | 2.08%   |
| Seagate ST31000528AS 1TB            | 1        | 2.08%   |
| Seagate ST2000NM0011 2TB            | 1        | 2.08%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1        | 2.08%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 2.08%   |
| Seagate ST1000DM003-1SB10C 1TB      | 1        | 2.08%   |
| Seagate BUP Slim SL 1TB             | 1        | 2.08%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 1        | 2.08%   |
| SanDisk NVMe SSD Drive 250GB        | 1        | 2.08%   |
| Samsung SSD 970 EVO Plus 1TB        | 1        | 2.08%   |
| Samsung SSD 860 EVO 500GB           | 1        | 2.08%   |
| Samsung SSD 860 EVO 250GB           | 1        | 2.08%   |
| Samsung SSD 850 EVO 250GB           | 1        | 2.08%   |
| Samsung SSD 840 Series 250GB        | 1        | 2.08%   |
| Samsung SSD 840 EVO 120GB           | 1        | 2.08%   |
| Samsung MZVLB1T0HBLR-000L2 1TB      | 1        | 2.08%   |
| Samsung HM500JI 500GB               | 1        | 2.08%   |
| Samsung HD161GJ 160GB               | 1        | 2.08%   |
| PNY CS900 120GB SSD                 | 1        | 2.08%   |
| Plextor PX-512M6Pro 512GB SSD       | 1        | 2.08%   |
| Kingston SA400S37480G 480GB SSD     | 1        | 2.08%   |
| Kingston SA400S37240G 240GB SSD     | 1        | 2.08%   |
| China SATA SSD 256GB                | 1        | 2.08%   |
| A-DATA SX7000NP 128GB               | 1        | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 15     | 50%     |
| WDC                 | 6        | 8      | 25%     |
| Toshiba             | 4        | 4      | 16.67%  |
| Samsung Electronics | 2        | 2      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 8      | 28.57%  |
| WDC                 | 2        | 2      | 14.29%  |
| Kingston            | 2        | 2      | 14.29%  |
| Unknown             | 1        | 1      | 7.14%   |
| SPCC                | 1        | 1      | 7.14%   |
| SanDisk             | 1        | 1      | 7.14%   |
| PNY                 | 1        | 1      | 7.14%   |
| Plextor             | 1        | 1      | 7.14%   |
| China               | 1        | 2      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 29     | 51.43%  |
| SSD  | 13       | 19     | 37.14%  |
| NVMe | 4        | 9      | 11.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 21       | 47     | 80.77%  |
| NVMe | 4        | 9      | 15.38%  |
| SAS  | 1        | 1      | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 31     | 60%     |
| 0.51-1.0   | 7        | 9      | 23.33%  |
| 1.01-2.0   | 5        | 8      | 16.67%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 6        | 26.09%  |
| 501-1000   | 5        | 21.74%  |
| 101-250    | 4        | 17.39%  |
| 1001-2000  | 3        | 13.04%  |
| Unknown    | 2        | 8.7%    |
| 21-50      | 1        | 4.35%   |
| 2001-3000  | 1        | 4.35%   |
| 51-100     | 1        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 8        | 32%     |
| 51-100    | 5        | 20%     |
| 101-250   | 4        | 16%     |
| 251-500   | 2        | 8%      |
| 501-1000  | 2        | 8%      |
| Unknown   | 2        | 8%      |
| 1001-2000 | 1        | 4%      |
| 1-20      | 1        | 4%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD2003FZEX-00Z4SA0 2TB         | 1        | 1      | 11.11%  |
| Seagate ST9500325AS 500GB          | 1        | 1      | 11.11%  |
| Seagate ST3320418AS 320GB          | 1        | 1      | 11.11%  |
| Seagate ST250DM000-1BD141 250GB    | 1        | 1      | 11.11%  |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 11.11%  |
| SanDisk SD6SF1M128G1022I 128GB SSD | 1        | 1      | 11.11%  |
| Samsung Electronics HM500JI 500GB  | 1        | 1      | 11.11%  |
| Plextor PX-512M6Pro 512GB SSD      | 1        | 1      | 11.11%  |
| A-DATA Technology SX7000NP 128GB   | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 4      | 37.5%   |
| WDC                 | 1        | 1      | 12.5%   |
| SanDisk             | 1        | 1      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Plextor             | 1        | 1      | 12.5%   |
| A-DATA Technology   | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 4      | 60%     |
| WDC                 | 1        | 1      | 20%     |
| Samsung Electronics | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 6      | 57.14%  |
| SSD  | 2        | 2      | 28.57%  |
| NVMe | 1        | 1      | 14.29%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 13       | 19     | 44.83%  |
| Detected | 11       | 28     | 37.93%  |
| Malfunc  | 4        | 9      | 13.79%  |
| Failed   | 1        | 1      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 15       | 55.56%  |
| AMD                 | 7        | 25.93%  |
| SanDisk             | 2        | 7.41%   |
| Silicon Motion      | 1        | 3.7%    |
| Samsung Electronics | 1        | 3.7%    |
| Nvidia              | 1        | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 18.18%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 15.15%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 6.06%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 6.06%   |
| Silicon Motion Non-Volatile memory controller                                           | 1        | 3.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 3.03%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 3.03%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 3.03%   |
| Nvidia MCP61 IDE                                                                        | 1        | 3.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1        | 3.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 3.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 3.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 3.03%   |
| AMD FCH SATA Controller D                                                               | 1        | 3.03%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 3.03%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 18       | 66.67%  |
| IDE  | 5        | 18.52%  |
| NVMe | 4        | 14.81%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 65.22%  |
| AMD    | 8        | 34.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 8.7%    |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 4.35%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 4.35%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 4.35%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 4.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1        | 4.35%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 4.35%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 4.35%   |
| Intel Core i5-4670S CPU @ 3.10GHz           | 1        | 4.35%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 4.35%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1        | 4.35%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 4.35%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1        | 4.35%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 4.35%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 4.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 1        | 4.35%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 1        | 4.35%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 1        | 4.35%   |
| AMD Ryzen 5 1500X Quad-Core Processor       | 1        | 4.35%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 4.35%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+  | 1        | 4.35%   |
| AMD A8-5500 APU with Radeon HD Graphics     | 1        | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i3      | 5        | 21.74%  |
| Intel Core i5      | 3        | 13.04%  |
| AMD Ryzen 5        | 3        | 13.04%  |
| Intel Pentium      | 2        | 8.7%    |
| Intel Core i7      | 2        | 8.7%    |
| Intel Xeon         | 1        | 4.35%   |
| Intel Pentium Dual | 1        | 4.35%   |
| Intel Core 2 Duo   | 1        | 4.35%   |
| AMD Ryzen 9        | 1        | 4.35%   |
| AMD Ryzen 7        | 1        | 4.35%   |
| AMD Ryzen 3        | 1        | 4.35%   |
| AMD Athlon 64 X2   | 1        | 4.35%   |
| AMD A8             | 1        | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 43.48%  |
| 4      | 9        | 39.13%  |
| 6      | 2        | 8.7%    |
| 12     | 1        | 4.35%   |
| 8      | 1        | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 52.17%  |
| 2      | 11       | 47.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 23       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 60.87%  |
| 0x206a7    | 2        | 8.7%    |
| 0x08001138 | 2        | 8.7%    |
| 0x906e9    | 1        | 4.35%   |
| 0x306c3    | 1        | 4.35%   |
| 0x1067a    | 1        | 4.35%   |
| 0x08701021 | 1        | 4.35%   |
| 0x06001119 | 1        | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 6        | 26.09%  |
| KabyLake    | 4        | 17.39%  |
| Zen 2       | 3        | 13.04%  |
| Zen         | 3        | 13.04%  |
| SandyBridge | 3        | 13.04%  |
| Piledriver  | 1        | 4.35%   |
| Penryn      | 1        | 4.35%   |
| K8 Hammer   | 1        | 4.35%   |
| Core        | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 50%     |
| Nvidia | 7        | 25%     |
| AMD    | 7        | 25%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 10.71%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 10.71%  |
| Intel HD Graphics 630                                                       | 2        | 7.14%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 7.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 7.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 3.57%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 3.57%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.57%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 3.57%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 3.57%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 3.57%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 3.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1        | 3.57%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 3.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 3.57%   |
| AMD Trinity [Radeon HD 7560D]                                               | 1        | 3.57%   |
| AMD Renoir                                                                  | 1        | 3.57%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 3.57%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 3.57%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 9        | 39.13%  |
| 1 x Nvidia  | 7        | 30.43%  |
| 1 x AMD     | 6        | 26.09%  |
| Intel + AMD | 1        | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 19       | 79.17%  |
| Proprietary | 4        | 16.67%  |
| Unknown     | 1        | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 58.33%  |
| 1.01-2.0   | 4        | 16.67%  |
| 3.01-4.0   | 2        | 8.33%   |
| 0.51-1.0   | 2        | 8.33%   |
| 7.01-8.0   | 1        | 4.17%   |
| 0.01-0.5   | 1        | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 3        | 12.5%   |
| AOC                 | 3        | 12.5%   |
| Acer                | 3        | 12.5%   |
| Samsung Electronics | 2        | 8.33%   |
| Dell                | 2        | 8.33%   |
| BenQ                | 2        | 8.33%   |
| Vizio               | 1        | 4.17%   |
| Unknown             | 1        | 4.17%   |
| Toshiba             | 1        | 4.17%   |
| STD                 | 1        | 4.17%   |
| Plain Tree Systems  | 1        | 4.17%   |
| Philips             | 1        | 4.17%   |
| NEC Computers       | 1        | 4.17%   |
| Lenovo              | 1        | 4.17%   |
| Ativa               | 1        | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch            | 1        | 3.85%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                | 1        | 3.85%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                     | 1        | 3.85%   |
| STD LED STD0001 2560x1440 330x220mm 15.6-inch                        | 1        | 3.85%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch | 1        | 3.85%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1        | 3.85%   |
| Plain Tree Systems LCD Monitor PTS0899 1680x1050 474x296mm 22.0-inch | 1        | 3.85%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch             | 1        | 3.85%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch          | 1        | 3.85%   |
| Lenovo LCD Monitor LEN1144 1920x1200 520x320mm 24.0-inch             | 1        | 3.85%   |
| Lenovo L200pwD LEN1156 1680x1050 430x270mm 20.0-inch                 | 1        | 3.85%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 1        | 3.85%   |
| Goldstar L1742 GSM449B 1280x1024 338x270mm 17.0-inch                 | 1        | 3.85%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                | 1        | 3.85%   |
| Dell P2412H DELA07D 1920x1080 531x299mm 24.0-inch                    | 1        | 3.85%   |
| Dell LCD Monitor P2417H                                              | 1        | 3.85%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                    | 1        | 3.85%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                    | 1        | 3.85%   |
| Ativa AT22HZR ATV0100 1920x1080 497x292mm 22.7-inch                  | 1        | 3.85%   |
| AOC LCD Monitor 2470W 1920x1080                                      | 1        | 3.85%   |
| AOC LCD Monitor 2217 1680x1050                                       | 1        | 3.85%   |
| AOC 2470W AOC2470 1920x1080 520x290mm 23.4-inch                      | 1        | 3.85%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                      | 1        | 3.85%   |
| Acer X223W ACR0011 1680x1050 473x296mm 22.0-inch                     | 1        | 3.85%   |
| Acer ET221Q ACR056B 1920x1080 477x268mm 21.5-inch                    | 1        | 3.85%   |
| Acer CB272U ACR081D 2560x1440 597x336mm 27.0-inch                    | 1        | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 45.83%  |
| 1680x1050 (WSXGA+) | 5        | 20.83%  |
| 2560x1440 (QHD)    | 2        | 8.33%   |
| 1280x1024 (SXGA)   | 2        | 8.33%   |
| 3840x2160 (4K)     | 1        | 4.17%   |
| 3840x1080          | 1        | 4.17%   |
| 1920x1200 (WUXGA)  | 1        | 4.17%   |
| Unknown            | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 4        | 16.67%  |
| 22      | 4        | 16.67%  |
| 24      | 3        | 12.5%   |
| 23      | 3        | 12.5%   |
| Unknown | 3        | 12.5%   |
| 21      | 2        | 8.33%   |
| 17      | 2        | 8.33%   |
| 41      | 1        | 4.17%   |
| 32      | 1        | 4.17%   |
| 20      | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 39.13%  |
| 401-500     | 7        | 30.43%  |
| Unknown     | 3        | 13.04%  |
| 301-350     | 2        | 8.7%    |
| 701-800     | 1        | 4.35%   |
| 901-1000    | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 13       | 56.52%  |
| 16/10   | 5        | 21.74%  |
| Unknown | 3        | 13.04%  |
| 5/4     | 2        | 8.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 40%     |
| 301-350        | 4        | 16%     |
| Unknown        | 3        | 12%     |
| 251-300        | 2        | 8%      |
| 151-200        | 2        | 8%      |
| 141-150        | 2        | 8%      |
| 351-500        | 1        | 4%      |
| 501-1000       | 1        | 4%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 68.18%  |
| 101-120 | 3        | 13.64%  |
| Unknown | 3        | 13.64%  |
| 161-240 | 1        | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 72%     |
| 2     | 4        | 16%     |
| 0     | 2        | 8%      |
| 3     | 1        | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 19       | 40.43%  |
| Intel                         | 7        | 14.89%  |
| Qualcomm Atheros              | 3        | 6.38%   |
| TP-Link                       | 2        | 4.26%   |
| Samsung Electronics           | 2        | 4.26%   |
| Ralink Technology             | 2        | 4.26%   |
| Broadcom                      | 2        | 4.26%   |
| vivo                          | 1        | 2.13%   |
| Realtek                       | 1        | 2.13%   |
| OnePlus Technology (Shenzhen) | 1        | 2.13%   |
| Nvidia                        | 1        | 2.13%   |
| Microsoft                     | 1        | 2.13%   |
| MediaTek                      | 1        | 2.13%   |
| ICS Advent                    | 1        | 2.13%   |
| Gemtek                        | 1        | 2.13%   |
| D-Link System                 | 1        | 2.13%   |
| ASUSTek Computer              | 1        | 2.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 15       | 28.85%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 5        | 9.62%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 3.85%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 2        | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 3.85%   |
| Intel Ethernet Connection I217-LM                                    | 2        | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2        | 3.85%   |
| vivo 1806                                                            | 1        | 1.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1        | 1.92%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                    | 1        | 1.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 1        | 1.92%   |
| Realtek 802.11n NIC                                                  | 1        | 1.92%   |
| Ralink RT5372 Wireless Adapter                                       | 1        | 1.92%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 1.92%   |
| OnePlus (Shenzhen) EB2103                                            | 1        | 1.92%   |
| Nvidia MCP61 Ethernet                                                | 1        | 1.92%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 1.92%   |
| MediaTek TECNO SPARK 6 Go                                            | 1        | 1.92%   |
| Intel Wi-Fi 6 AX200                                                  | 1        | 1.92%   |
| Intel I211 Gigabit Network Connection                                | 1        | 1.92%   |
| Intel Ethernet Connection I217-V                                     | 1        | 1.92%   |
| ICS Advent USB 10/100 LAN                                            | 1        | 1.92%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                    | 1        | 1.92%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 1.92%   |
| Broadcom Network controller                                          | 1        | 1.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 1.92%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]   | 1        | 1.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 31.82%  |
| Qualcomm Atheros      | 3        | 13.64%  |
| TP-Link               | 2        | 9.09%   |
| Ralink Technology     | 2        | 9.09%   |
| Broadcom              | 2        | 9.09%   |
| Realtek               | 1        | 4.55%   |
| Microsoft             | 1        | 4.55%   |
| Intel                 | 1        | 4.55%   |
| Gemtek                | 1        | 4.55%   |
| D-Link System         | 1        | 4.55%   |
| ASUSTek Computer      | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 5        | 22.73%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 9.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 9.09%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1        | 4.55%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 4.55%   |
| Realtek 802.11n NIC                                                  | 1        | 4.55%   |
| Ralink RT5372 Wireless Adapter                                       | 1        | 4.55%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 4.55%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 1        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                  | 1        | 4.55%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                    | 1        | 4.55%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 1        | 4.55%   |
| Broadcom Network controller                                          | 1        | 4.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 4.55%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]   | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 58.62%  |
| Intel                 | 6        | 20.69%  |
| Samsung Electronics   | 2        | 6.9%    |
| vivo                  | 1        | 3.45%   |
| Nvidia                | 1        | 3.45%   |
| MediaTek              | 1        | 3.45%   |
| ICS Advent            | 1        | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15       | 51.72%  |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 6.9%    |
| Intel Ethernet Connection I217-LM                                 | 2        | 6.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 6.9%    |
| vivo 1806                                                         | 1        | 3.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 3.45%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.45%   |
| MediaTek TECNO SPARK 6 Go                                         | 1        | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.45%   |
| Intel Ethernet Connection I217-V                                  | 1        | 3.45%   |
| ICS Advent USB 10/100 LAN                                         | 1        | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 54.76%  |
| WiFi     | 18       | 42.86%  |
| Unknown  | 1        | 2.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 52.38%  |
| WiFi     | 10       | 47.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 65.22%  |
| 2     | 8        | 34.78%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 86.96%  |
| Yes  | 3        | 13.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Toshiba                         | 1        | 25%     |
| Qualcomm Atheros Communications | 1        | 25%     |
| Intel                           | 1        | 25%     |
| Cambridge Silicon Radio         | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Toshiba Atheros AR3012 Bluetooth                    | 1        | 25%     |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 25%     |
| Intel AX200 Bluetooth                               | 1        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 15       | 44.12%  |
| AMD                    | 9        | 26.47%  |
| Nvidia                 | 7        | 20.59%  |
| SteelSeries ApS        | 1        | 2.94%   |
| Generalplus Technology | 1        | 2.94%   |
| C-Media Electronics    | 1        | 2.94%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6        | 13.04%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 13.04%  |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 4.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 4.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 4.35%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 4.35%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 4.35%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 4.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 4.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 4.35%   |
| SteelSeries ApS SteelSeries GameDAC                                               | 1        | 2.17%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 2.17%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 2.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 2.17%   |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 2.17%   |
| Nvidia GF106 High Definition Audio Controller                                     | 1        | 2.17%   |
| Intel USB PnP Sound Device                                                        | 1        | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1        | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 2.17%   |
| Intel 200 Series PCH HD Audio                                                     | 1        | 2.17%   |
| Generalplus Technology IMYB 7.1 Channel                                           | 1        | 2.17%   |
| C-Media Electronics Audio Adapter                                                 | 1        | 2.17%   |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 2.17%   |
| AMD FCH Azalia Controller                                                         | 1        | 2.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 5        | 31.25%  |
| Samsung Electronics | 2        | 12.5%   |
| Kingston            | 2        | 12.5%   |
| Crucial             | 2        | 12.5%   |
| SK hynix            | 1        | 6.25%   |
| Silicon Power       | 1        | 6.25%   |
| G.Skill             | 1        | 6.25%   |
| Corsair             | 1        | 6.25%   |
| A-DATA Technology   | 1        | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 1        | 5.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 5.88%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                  | 1        | 5.88%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 5.88%   |
| Unknown RAM Module 2GB DIMM                                | 1        | 5.88%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                     | 1        | 5.88%   |
| Silicon Power RAM SP016GBLFU266B02 16GB DIMM DDR4 2667MT/s | 1        | 5.88%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s        | 1        | 5.88%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s        | 1        | 5.88%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 5.88%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s        | 1        | 5.88%   |
| Kingston RAM 9905678-005.A00G 8GB DIMM DDR4 2400MT/s       | 1        | 5.88%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s     | 1        | 5.88%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s  | 1        | 5.88%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s   | 1        | 5.88%   |
| Corsair RAM CM4X8GF2400Z16K4 8GB DIMM DDR4 2400MT/s        | 1        | 5.88%   |
| A-DATA RAM DDR4 3000 8192MB DIMM DDR4 3600MT/s             | 1        | 5.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 6        | 40%     |
| DDR3    | 6        | 40%     |
| SDRAM   | 2        | 13.33%  |
| Unknown | 1        | 6.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 13       | 92.86%  |
| SODIMM | 1        | 7.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 4        | 25%     |
| 8192  | 4        | 25%     |
| 4096  | 4        | 25%     |
| 2048  | 3        | 18.75%  |
| 1024  | 1        | 6.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 3        | 20%     |
| 3600    | 2        | 13.33%  |
| 2667    | 2        | 13.33%  |
| 2400    | 2        | 13.33%  |
| Unknown | 2        | 13.33%  |
| 2200    | 1        | 6.67%   |
| 2133    | 1        | 6.67%   |
| 1333    | 1        | 6.67%   |
| 1067    | 1        | 6.67%   |

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
| Logitech            | 2        | 33.33%  |
| Teslong Camera      | 1        | 16.67%  |
| Jieli Technology    | 1        | 16.67%  |
| IMC Networks        | 1        | 16.67%  |
| Creative Technology | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Teslong Camera                      | 1        | 16.67%  |
| Logitech HD Webcam C615             | 1        | 16.67%  |
| Logitech C922 Pro Stream Webcam     | 1        | 16.67%  |
| Jieli USB PHY 2.0                   | 1        | 16.67%  |
| IMC Networks XHC Camera             | 1        | 16.67%  |
| Creative Live! Cam Sync HD [VF0770] | 1        | 16.67%  |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 15       | 62.5%   |
| 1     | 8        | 33.33%  |
| 2     | 1        | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 5        | 50%     |
| Graphics card            | 3        | 30%     |
| Multimedia controller    | 1        | 10%     |
| Communication controller | 1        | 10%     |

