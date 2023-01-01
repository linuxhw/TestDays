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

Total: 41

| Vendor        | Model                   | Probe                                                      | Date         |
|---------------|-------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | H61M-S2PT               | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Gateway       | SX2855                  | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| ASUSTek       | H110M-K                 | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z   | [0539efedb2](https://linux-hardware.org/?probe=0539efedb2) | Jul 18, 2022 |
| ASUSTek       | H110M-K                 | [0e0a7a2fbc](https://linux-hardware.org/?probe=0e0a7a2fbc) | Jul 16, 2022 |
| ASUSTek       | PRIME B550-PLUS         | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS         | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| ASUSTek       | H110M-K                 | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| ASUSTek       | H110M-K                 | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| Gigabyte      | H61M-USB3H              | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Unknown       | TB-4000                 | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Lenovo        | 31900058 STD            | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF           | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| MSI           | G31M3-L V2              | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| HP            | 1495                    | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Unknown       | TB-4000                 | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
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
| Unknown       | TB-4000                 | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Unknown       | TB-4000                 | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Dell          | 0GXM1W A02              | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Unknown       | TB-4000                 | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
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
| 5.16.0-12parrot1-amd64   | 12       | 41.38%  |
| 5.14.0-9parrot1-amd64    | 9        | 31.03%  |
| 5.15.0-15parrot1-amd64   | 4        | 13.79%  |
| 5.18.0-1parrot1-amd64    | 2        | 6.9%    |
| 5.16.0-12parrot1-686-pae | 1        | 3.45%   |
| 5.14.0-2parrot1-amd64    | 1        | 3.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16.0  | 13       | 46.43%  |
| 5.14.0  | 9        | 32.14%  |
| 5.15.0  | 4        | 14.29%  |
| 5.18.0  | 2        | 7.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.16    | 13       | 46.43%  |
| 5.14    | 9        | 32.14%  |
| 5.15    | 4        | 14.29%  |
| 5.18    | 2        | 7.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 25       | 96.15%  |
| i686   | 1        | 3.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| MATE    | 19       | 70.37%  |
| KDE5    | 3        | 11.11%  |
| XFCE    | 2        | 7.41%   |
| Unknown | 2        | 7.41%   |
| GNOME   | 1        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 24       | 92.31%  |
| Wayland | 2        | 7.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 14       | 53.85%  |
| Unknown | 10       | 38.46%  |
| SDDM    | 1        | 3.85%   |
| GDM     | 1        | 3.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 14       | 53.85%  |
| pt_BR | 3        | 11.54%  |
| en_IN | 2        | 7.69%   |
| ru_RU | 1        | 3.85%   |
| pl_PL | 1        | 3.85%   |
| fr_FR | 1        | 3.85%   |
| es_ES | 1        | 3.85%   |
| en_GB | 1        | 3.85%   |
| en_DK | 1        | 3.85%   |
| cs_CZ | 1        | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 69.23%  |
| EFI  | 8        | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 22       | 84.62%  |
| Ext4    | 3        | 11.54%  |
| Overlay | 1        | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 44.44%  |
| GPT     | 11       | 40.74%  |
| MBR     | 4        | 14.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 88.46%  |
| Yes       | 3        | 11.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 61.54%  |
| Yes       | 10       | 38.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 7        | 26.92%  |
| Gigabyte Technology | 4        | 15.38%  |
| Hewlett-Packard     | 3        | 11.54%  |
| MSI                 | 2        | 7.69%   |
| Lenovo              | 2        | 7.69%   |
| Dell                | 2        | 7.69%   |
| Unknown             | 2        | 7.69%   |
| Gateway             | 1        | 3.85%   |
| ECS                 | 1        | 3.85%   |
| Daewoo Lucoms       | 1        | 3.85%   |
| ASRock              | 1        | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| HP ProDesk 600 G1 SFF        | 2        | 7.69%   |
| Unknown                      | 2        | 7.69%   |
| MSI MS-7A34                  | 1        | 3.85%   |
| MSI MS-7529                  | 1        | 3.85%   |
| Lenovo H535 10117            | 1        | 3.85%   |
| Lenovo H530 10130            | 1        | 3.85%   |
| HP Compaq 8200 Elite SFF PC  | 1        | 3.85%   |
| Gigabyte H61M-USB3H          | 1        | 3.85%   |
| Gigabyte H61M-S2PT           | 1        | 3.85%   |
| Gigabyte B450M DS3H          | 1        | 3.85%   |
| Gigabyte A320M-S2H           | 1        | 3.85%   |
| Gateway SX2855               | 1        | 3.85%   |
| ECS GV460AA-ABA a6217c       | 1        | 3.85%   |
| Dell OptiPlex 7010           | 1        | 3.85%   |
| Dell OptiPlex 3020           | 1        | 3.85%   |
| Daewoo Lucoms OEM            | 1        | 3.85%   |
| ASUS ROG CROSSHAIR VIII HERO | 1        | 3.85%   |
| ASUS PRIME H310M-D R2.0      | 1        | 3.85%   |
| ASUS PRIME B550-PLUS         | 1        | 3.85%   |
| ASUS H170M-E D3              | 1        | 3.85%   |
| ASUS H110M-K                 | 1        | 3.85%   |
| ASUS CROSSHAIR V FORMULA-Z   | 1        | 3.85%   |
| ASUS Basic 3221BM            | 1        | 3.85%   |
| ASRock Z87M Extreme4         | 1        | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP ProDesk          | 2        | 7.69%   |
| Dell OptiPlex       | 2        | 7.69%   |
| ASUS PRIME          | 2        | 7.69%   |
| Unknown             | 2        | 7.69%   |
| MSI MS-7A34         | 1        | 3.85%   |
| MSI MS-7529         | 1        | 3.85%   |
| Lenovo H535         | 1        | 3.85%   |
| Lenovo H530         | 1        | 3.85%   |
| HP Compaq           | 1        | 3.85%   |
| Gigabyte H61M-USB3H | 1        | 3.85%   |
| Gigabyte H61M-S2PT  | 1        | 3.85%   |
| Gigabyte B450M      | 1        | 3.85%   |
| Gigabyte A320M-S2H  | 1        | 3.85%   |
| Gateway SX2855      | 1        | 3.85%   |
| ECS GV460AA-ABA     | 1        | 3.85%   |
| Daewoo Lucoms OEM   | 1        | 3.85%   |
| ASUS ROG            | 1        | 3.85%   |
| ASUS H170M-E        | 1        | 3.85%   |
| ASUS H110M-K        | 1        | 3.85%   |
| ASUS CROSSHAIR      | 1        | 3.85%   |
| ASUS Basic          | 1        | 3.85%   |
| ASRock Z87M         | 1        | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 8        | 30.77%  |
| 2021 | 2        | 7.69%   |
| 2018 | 2        | 7.69%   |
| 2017 | 2        | 7.69%   |
| 2015 | 2        | 7.69%   |
| 2012 | 2        | 7.69%   |
| 2011 | 2        | 7.69%   |
| 2020 | 1        | 3.85%   |
| 2019 | 1        | 3.85%   |
| 2016 | 1        | 3.85%   |
| 2010 | 1        | 3.85%   |
| 2009 | 1        | 3.85%   |
| 2007 | 1        | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 26       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 26       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 8        | 29.63%  |
| 32.01-64.0 | 5        | 18.52%  |
| 8.01-16.0  | 5        | 18.52%  |
| 3.01-4.0   | 4        | 14.81%  |
| 16.01-24.0 | 4        | 14.81%  |
| 1.01-2.0   | 1        | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 10       | 35.71%  |
| 1.01-2.0   | 7        | 25%     |
| 3.01-4.0   | 4        | 14.29%  |
| 4.01-8.0   | 3        | 10.71%  |
| 0.51-1.0   | 3        | 10.71%  |
| 16.01-24.0 | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 46.15%  |
| 1      | 9        | 34.62%  |
| 4      | 2        | 7.69%   |
| 6      | 1        | 3.85%   |
| 5      | 1        | 3.85%   |
| 3      | 1        | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 80.77%  |
| Yes       | 5        | 19.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 26       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 20       | 76.92%  |
| No        | 6        | 23.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 84.62%  |
| Yes       | 4        | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 7        | 25.93%  |
| Brazil      | 3        | 11.11%  |
| Netherlands | 2        | 7.41%   |
| India       | 2        | 7.41%   |
| UK          | 1        | 3.7%    |
| Spain       | 1        | 3.7%    |
| Russia      | 1        | 3.7%    |
| Romania     | 1        | 3.7%    |
| Morocco     | 1        | 3.7%    |
| Mongolia    | 1        | 3.7%    |
| France      | 1        | 3.7%    |
| Egypt       | 1        | 3.7%    |
| Denmark     | 1        | 3.7%    |
| Czechia     | 1        | 3.7%    |
| Canada      | 1        | 3.7%    |
| Austria     | 1        | 3.7%    |
| Algeria     | 1        | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Vienna               | 1        | 3.7%    |
| Viby J               | 1        | 3.7%    |
| Vapi                 | 1        | 3.7%    |
| Ulan Bator           | 1        | 3.7%    |
| Uherské Hradiště  | 1        | 3.7%    |
| Tangier              | 1        | 3.7%    |
| Springfield          | 1        | 3.7%    |
| Sao Paulo            | 1        | 3.7%    |
| Sao Joao de Meriti   | 1        | 3.7%    |
| Santa Maria          | 1        | 3.7%    |
| Point Pleasant Beach | 1        | 3.7%    |
| Montreal             | 1        | 3.7%    |
| Milton               | 1        | 3.7%    |
| Long Eaton           | 1        | 3.7%    |
| Lille                | 1        | 3.7%    |
| Krasnogorsk          | 1        | 3.7%    |
| Iasi                 | 1        | 3.7%    |
| Hammam Dalaa         | 1        | 3.7%    |
| Guadalajara          | 1        | 3.7%    |
| Darien               | 1        | 3.7%    |
| D'Iberville          | 1        | 3.7%    |
| Cleveland            | 1        | 3.7%    |
| Bussum               | 1        | 3.7%    |
| Broadus              | 1        | 3.7%    |
| Beri Khas            | 1        | 3.7%    |
| Amsterdam            | 1        | 3.7%    |
| Alexandria           | 1        | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 20     | 29.79%  |
| WDC                 | 11       | 13     | 23.4%   |
| Samsung Electronics | 6        | 12     | 12.77%  |
| Toshiba             | 4        | 4      | 8.51%   |
| SanDisk             | 2        | 5      | 4.26%   |
| Kingston            | 2        | 3      | 4.26%   |
| Unknown             | 1        | 1      | 2.13%   |
| SPCC                | 1        | 1      | 2.13%   |
| Silicon Motion      | 1        | 1      | 2.13%   |
| PNY                 | 1        | 1      | 2.13%   |
| Plextor             | 1        | 1      | 2.13%   |
| China               | 1        | 2      | 2.13%   |
| Apacer              | 1        | 1      | 2.13%   |
| A-DATA Technology   | 1        | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| WDC WD5000AADS-00S9B0 500GB         | 2        | 3.64%   |
| Toshiba DT01ACA200 2TB              | 2        | 3.64%   |
| Seagate ST250DM000-1BD141 250GB     | 2        | 3.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 1        | 1.82%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1        | 1.82%   |
| WDC WDBRPG5000ANC-WRSN 500GB        | 1        | 1.82%   |
| WDC WD20EZAZ-00GGJB0 2TB            | 1        | 1.82%   |
| WDC WD2003FZEX-00Z4SA0 2TB          | 1        | 1.82%   |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 1.82%   |
| WDC WD10EZRX-00L4HB0 1TB            | 1        | 1.82%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1        | 1.82%   |
| WDC WD10EARS-00Y5B1 1TB             | 1        | 1.82%   |
| WDC WD10EADX-22TDHB0 1TB            | 1        | 1.82%   |
| Unknown 256GB PCS 2.5" S SSD        | 1        | 1.82%   |
| Toshiba HDWD105 500GB               | 1        | 1.82%   |
| Toshiba DT01ACA050 500GB            | 1        | 1.82%   |
| SPCC Solid State Disk 240GB         | 1        | 1.82%   |
| Silicon Motion NVMe SSD Drive 128GB | 1        | 1.82%   |
| Seagate ST9500325AS 500GB           | 1        | 1.82%   |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1.82%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 1.82%   |
| Seagate ST500LM000-SSHD-8GB         | 1        | 1.82%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1.82%   |
| Seagate ST3500514NS 500GB           | 1        | 1.82%   |
| Seagate ST3500312CS 500GB           | 1        | 1.82%   |
| Seagate ST3320418AS 320GB           | 1        | 1.82%   |
| Seagate ST3250310CS 250GB           | 1        | 1.82%   |
| Seagate ST3160215SCE 160GB          | 1        | 1.82%   |
| Seagate ST31000528AS 1TB            | 1        | 1.82%   |
| Seagate ST2000NM0011 2TB            | 1        | 1.82%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1        | 1.82%   |
| Seagate ST2000DM001-1ER164 2TB      | 1        | 1.82%   |
| Seagate ST1000DM003-1SB10C 1TB      | 1        | 1.82%   |
| Seagate BUP Slim SL 1TB             | 1        | 1.82%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 1        | 1.82%   |
| SanDisk NVMe SSD Drive 250GB        | 1        | 1.82%   |
| Samsung SSD 970 EVO Plus 1TB        | 1        | 1.82%   |
| Samsung SSD 860 EVO 500GB           | 1        | 1.82%   |
| Samsung SSD 860 EVO 250GB           | 1        | 1.82%   |
| Samsung SSD 850 EVO 250GB           | 1        | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 20     | 50%     |
| WDC                 | 8        | 10     | 28.57%  |
| Toshiba             | 4        | 4      | 14.29%  |
| Samsung Electronics | 2        | 2      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 8      | 26.67%  |
| WDC                 | 2        | 2      | 13.33%  |
| Kingston            | 2        | 3      | 13.33%  |
| Unknown             | 1        | 1      | 6.67%   |
| SPCC                | 1        | 1      | 6.67%   |
| SanDisk             | 1        | 1      | 6.67%   |
| PNY                 | 1        | 1      | 6.67%   |
| Plextor             | 1        | 1      | 6.67%   |
| China               | 1        | 2      | 6.67%   |
| Apacer              | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 36     | 53.85%  |
| SSD  | 14       | 21     | 35.9%   |
| NVMe | 4        | 9      | 10.26%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 56     | 82.76%  |
| NVMe | 4        | 9      | 13.79%  |
| SAS  | 1        | 1      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 20       | 39     | 60.61%  |
| 0.51-1.0   | 8        | 10     | 24.24%  |
| 1.01-2.0   | 5        | 8      | 15.15%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 501-1000   | 8        | 30.77%  |
| 251-500    | 6        | 23.08%  |
| 101-250    | 4        | 15.38%  |
| 1001-2000  | 3        | 11.54%  |
| Unknown    | 2        | 7.69%   |
| 21-50      | 1        | 3.85%   |
| 2001-3000  | 1        | 3.85%   |
| 51-100     | 1        | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 21-50     | 8        | 28.57%  |
| 51-100    | 6        | 21.43%  |
| 101-250   | 4        | 14.29%  |
| 251-500   | 3        | 10.71%  |
| 501-1000  | 3        | 10.71%  |
| Unknown   | 2        | 7.14%   |
| 1001-2000 | 1        | 3.57%   |
| 1-20      | 1        | 3.57%   |

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
| Detected | 14       | 36     | 42.42%  |
| Works    | 14       | 20     | 42.42%  |
| Malfunc  | 4        | 9      | 12.12%  |
| Failed   | 1        | 1      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 17       | 54.84%  |
| AMD                 | 8        | 25.81%  |
| SanDisk             | 2        | 6.45%   |
| Silicon Motion      | 1        | 3.23%   |
| Samsung Electronics | 1        | 3.23%   |
| Nvidia              | 1        | 3.23%   |
| ASMedia Technology  | 1        | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 6        | 15.38%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 12.82%  |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 7.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2        | 5.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 5.13%   |
| Silicon Motion Non-Volatile memory controller                                           | 1        | 2.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 2.56%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 2.56%   |
| Nvidia MCP61 SATA Controller                                                            | 1        | 2.56%   |
| Nvidia MCP61 IDE                                                                        | 1        | 2.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 1        | 2.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 2.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 2.56%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 2.56%   |
| AMD FCH SATA Controller D                                                               | 1        | 2.56%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 2.56%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 19       | 63.33%  |
| IDE  | 7        | 23.33%  |
| NVMe | 4        | 13.33%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 17       | 65.38%  |
| AMD    | 9        | 34.62%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 7.69%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 7.69%   |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz         | 1        | 3.85%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1        | 3.85%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 3.85%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1        | 3.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1        | 3.85%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 3.85%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 3.85%   |
| Intel Core i5-4670S CPU @ 3.10GHz           | 1        | 3.85%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 3.85%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 1        | 3.85%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 1        | 3.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 3.85%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1        | 3.85%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 3.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 1        | 3.85%   |
| AMD Ryzen 5 3500X 6-Core Processor          | 1        | 3.85%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 1        | 3.85%   |
| AMD Ryzen 5 1500X Quad-Core Processor       | 1        | 3.85%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 3.85%   |
| AMD FX-8350 Eight-Core Processor            | 1        | 3.85%   |
| AMD Athlon 64 X2 Dual Core Processor 4600+  | 1        | 3.85%   |
| AMD A8-5500 APU with Radeon HD Graphics     | 1        | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i3      | 7        | 26.92%  |
| Intel Core i5      | 3        | 11.54%  |
| AMD Ryzen 5        | 3        | 11.54%  |
| Intel Pentium      | 2        | 7.69%   |
| Intel Core i7      | 2        | 7.69%   |
| Intel Xeon         | 1        | 3.85%   |
| Intel Pentium Dual | 1        | 3.85%   |
| Intel Core 2 Duo   | 1        | 3.85%   |
| AMD Ryzen 9        | 1        | 3.85%   |
| AMD Ryzen 7        | 1        | 3.85%   |
| AMD Ryzen 3        | 1        | 3.85%   |
| AMD FX             | 1        | 3.85%   |
| AMD Athlon 64 X2   | 1        | 3.85%   |
| AMD A8             | 1        | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 12       | 46.15%  |
| 4      | 10       | 38.46%  |
| 6      | 2        | 7.69%   |
| 12     | 1        | 3.85%   |
| 8      | 1        | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 14       | 53.85%  |
| 1      | 12       | 46.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 26       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 61.54%  |
| 0x206a7    | 3        | 11.54%  |
| 0x08001138 | 2        | 7.69%   |
| 0x906e9    | 1        | 3.85%   |
| 0x306c3    | 1        | 3.85%   |
| 0x1067a    | 1        | 3.85%   |
| 0x08701021 | 1        | 3.85%   |
| 0x06001119 | 1        | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 6        | 23.08%  |
| SandyBridge | 5        | 19.23%  |
| KabyLake    | 4        | 15.38%  |
| Zen 2       | 3        | 11.54%  |
| Zen         | 3        | 11.54%  |
| Piledriver  | 2        | 7.69%   |
| Penryn      | 1        | 3.85%   |
| K8 Hammer   | 1        | 3.85%   |
| Core        | 1        | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 16       | 51.61%  |
| Nvidia | 8        | 25.81%  |
| AMD    | 7        | 22.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 16.13%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 9.68%   |
| Intel HD Graphics 630                                                       | 2        | 6.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 6.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 6.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 3.23%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 3.23%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 3.23%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 3.23%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1        | 3.23%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 3.23%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 3.23%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 1        | 3.23%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 3.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1        | 3.23%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 3.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 3.23%   |
| AMD Trinity [Radeon HD 7560D]                                               | 1        | 3.23%   |
| AMD Renoir                                                                  | 1        | 3.23%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 3.23%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 1        | 3.23%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 1        | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 11       | 42.31%  |
| 1 x Nvidia  | 8        | 30.77%  |
| 1 x AMD     | 6        | 23.08%  |
| Intel + AMD | 1        | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 22       | 81.48%  |
| Proprietary | 4        | 14.81%  |
| Unknown     | 1        | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 62.96%  |
| 1.01-2.0   | 4        | 14.81%  |
| 3.01-4.0   | 2        | 7.41%   |
| 0.51-1.0   | 2        | 7.41%   |
| 7.01-8.0   | 1        | 3.7%    |
| 0.01-0.5   | 1        | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 3        | 11.54%  |
| AOC                  | 3        | 11.54%  |
| Acer                 | 3        | 11.54%  |
| Toshiba              | 2        | 7.69%   |
| Samsung Electronics  | 2        | 7.69%   |
| Dell                 | 2        | 7.69%   |
| BenQ                 | 2        | 7.69%   |
| Vizio                | 1        | 3.85%   |
| Unknown              | 1        | 3.85%   |
| STD                  | 1        | 3.85%   |
| Plain Tree Systems   | 1        | 3.85%   |
| Philips              | 1        | 3.85%   |
| NEC Computers        | 1        | 3.85%   |
| Lenovo               | 1        | 3.85%   |
| Ativa                | 1        | 3.85%   |
| Ancor Communications | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 3.57%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                 | 1        | 3.57%   |
| Toshiba TV TSB0105 1920x540 708x398mm 32.0-inch                       | 1        | 3.57%   |
| Toshiba TSB-TV TSB0205 1920x1080 531x398mm 26.1-inch                  | 1        | 3.57%   |
| STD LCD Monitor STD0001 1920x1080                                     | 1        | 3.57%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch  | 1        | 3.57%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1        | 3.57%   |
| Plain Tree Systems Monitor PTS0899 1680x1050 474x296mm 22.0-inch      | 1        | 3.57%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 3.57%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 1        | 3.57%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 1        | 3.57%   |
| Lenovo L200pwD LEN1156 1680x1050 430x270mm 20.0-inch                  | 1        | 3.57%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1        | 3.57%   |
| Goldstar L1742 GSM449B 1280x1024 338x270mm 17.0-inch                  | 1        | 3.57%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                 | 1        | 3.57%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1        | 3.57%   |
| Dell LCD Monitor P2417H                                               | 1        | 3.57%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                     | 1        | 3.57%   |
| BenQ BL2405 BNQ8016 1920x1080 531x298mm 24.0-inch                     | 1        | 3.57%   |
| Ativa AT22HZR ATV0100 1920x1080 497x292mm 22.7-inch                   | 1        | 3.57%   |
| AOC LCD Monitor 2470W 1920x1080                                       | 1        | 3.57%   |
| AOC LCD Monitor 2217 1680x1050                                        | 1        | 3.57%   |
| AOC 2470W AOC2470 1920x1080 520x290mm 23.4-inch                       | 1        | 3.57%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 1        | 3.57%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 1        | 3.57%   |
| Acer X223W ACR0011 1680x1050 470x300mm 22.0-inch                      | 1        | 3.57%   |
| Acer ET221Q ACR056B 1920x1080 477x268mm 21.5-inch                     | 1        | 3.57%   |
| Acer CB272U ACR081D 2560x1440 597x336mm 27.0-inch                     | 1        | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 48%     |
| 1680x1050 (WSXGA+) | 5        | 20%     |
| 2560x1440 (QHD)    | 2        | 8%      |
| 1280x1024 (SXGA)   | 2        | 8%      |
| 3840x2160 (4K)     | 1        | 4%      |
| 3840x1080          | 1        | 4%      |
| 1920x1200 (WUXGA)  | 1        | 4%      |
| Unknown            | 1        | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 4        | 15.38%  |
| 22      | 4        | 15.38%  |
| 24      | 3        | 11.54%  |
| 23      | 3        | 11.54%  |
| 21      | 3        | 11.54%  |
| Unknown | 3        | 11.54%  |
| 17      | 2        | 7.69%   |
| 72      | 1        | 3.85%   |
| 41      | 1        | 3.85%   |
| 32      | 1        | 3.85%   |
| 20      | 1        | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 36%     |
| 401-500     | 8        | 32%     |
| Unknown     | 3        | 12%     |
| 301-350     | 2        | 8%      |
| 701-800     | 1        | 4%      |
| 1501-2000   | 1        | 4%      |
| 901-1000    | 1        | 4%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 14       | 58.33%  |
| 16/10   | 5        | 20.83%  |
| Unknown | 3        | 12.5%   |
| 5/4     | 2        | 8.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 40.74%  |
| 301-350        | 4        | 14.81%  |
| Unknown        | 3        | 11.11%  |
| 251-300        | 2        | 7.41%   |
| 151-200        | 2        | 7.41%   |
| 141-150        | 2        | 7.41%   |
| More than 1000 | 1        | 3.7%    |
| 351-500        | 1        | 3.7%    |
| 501-1000       | 1        | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 62.5%   |
| 101-120 | 4        | 16.67%  |
| Unknown | 3        | 12.5%   |
| 1-50    | 1        | 4.17%   |
| 161-240 | 1        | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 71.43%  |
| 2     | 5        | 17.86%  |
| 0     | 2        | 7.14%   |
| 3     | 1        | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Realtek Semiconductor         | 21       | 38.18%  |
| Intel                         | 9        | 16.36%  |
| TP-Link                       | 3        | 5.45%   |
| Samsung Electronics           | 3        | 5.45%   |
| Ralink Technology             | 3        | 5.45%   |
| Qualcomm Atheros              | 3        | 5.45%   |
| Microsoft                     | 2        | 3.64%   |
| Broadcom                      | 2        | 3.64%   |
| vivo                          | 1        | 1.82%   |
| OnePlus Technology (Shenzhen) | 1        | 1.82%   |
| Nvidia                        | 1        | 1.82%   |
| Mercucys                      | 1        | 1.82%   |
| MediaTek                      | 1        | 1.82%   |
| ICS Advent                    | 1        | 1.82%   |
| Gemtek                        | 1        | 1.82%   |
| D-Link System                 | 1        | 1.82%   |
| ASUSTek Computer              | 1        | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 16       | 26.67%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 5        | 8.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 3        | 5%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2        | 3.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2        | 3.33%   |
| Intel Ethernet Connection I217-LM                                       | 2        | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2        | 3.33%   |
| vivo 1806                                                               | 1        | 1.67%   |
| TP-Link Archer T4U ver.3                                                | 1        | 1.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 1.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1        | 1.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1        | 1.67%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 1.67%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 1.67%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 1.67%   |
| OnePlus (Shenzhen) SM8150-MTP _SN:3BB6B401                              | 1        | 1.67%   |
| Nvidia MCP61 Ethernet                                                   | 1        | 1.67%   |
| Microsoft Xbox360 Wireless N Networking Adapter [Atheros AR7010+AR9280] | 1        | 1.67%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 1.67%   |
| Mercucys 802.11n NIC                                                    | 1        | 1.67%   |
| MediaTek TECNO CAMON 18P                                                | 1        | 1.67%   |
| Intel Wi-Fi 6 AX200                                                     | 1        | 1.67%   |
| Intel I211 Gigabit Network Connection                                   | 1        | 1.67%   |
| Intel Ethernet Connection I217-V                                        | 1        | 1.67%   |
| Intel 82583V Gigabit Network Connection                                 | 1        | 1.67%   |
| Intel 82579V Gigabit Network Connection                                 | 1        | 1.67%   |
| ICS Advent USB 10/100 LAN                                               | 1        | 1.67%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                       | 1        | 1.67%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1        | 1.67%   |
| Broadcom Network controller                                             | 1        | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 1.67%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1        | 1.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 30.77%  |
| TP-Link               | 3        | 11.54%  |
| Ralink Technology     | 3        | 11.54%  |
| Qualcomm Atheros      | 3        | 11.54%  |
| Microsoft             | 2        | 7.69%   |
| Broadcom              | 2        | 7.69%   |
| Mercucys              | 1        | 3.85%   |
| Intel                 | 1        | 3.85%   |
| Gemtek                | 1        | 3.85%   |
| D-Link System         | 1        | 3.85%   |
| ASUSTek Computer      | 1        | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 5        | 19.23%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2        | 7.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2        | 7.69%   |
| TP-Link Archer T4U ver.3                                                | 1        | 3.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1        | 3.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1        | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1        | 3.85%   |
| Ralink RT5572 Wireless Adapter                                          | 1        | 3.85%   |
| Ralink RT5372 Wireless Adapter                                          | 1        | 3.85%   |
| Ralink MT7601U Wireless Adapter                                         | 1        | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1        | 3.85%   |
| Microsoft Xbox360 Wireless N Networking Adapter [Atheros AR7010+AR9280] | 1        | 3.85%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1        | 3.85%   |
| Mercucys 802.11n NIC                                                    | 1        | 3.85%   |
| Intel Wi-Fi 6 AX200                                                     | 1        | 3.85%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                       | 1        | 3.85%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1        | 3.85%   |
| Broadcom Network controller                                             | 1        | 3.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1        | 3.85%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 1        | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 18       | 54.55%  |
| Intel                 | 8        | 24.24%  |
| Samsung Electronics   | 3        | 9.09%   |
| vivo                  | 1        | 3.03%   |
| Nvidia                | 1        | 3.03%   |
| MediaTek              | 1        | 3.03%   |
| ICS Advent            | 1        | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16       | 48.48%  |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3        | 9.09%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 6.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 6.06%   |
| vivo 1806                                                         | 1        | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 3.03%   |
| Nvidia MCP61 Ethernet                                             | 1        | 3.03%   |
| MediaTek TECNO CAMON 18P                                          | 1        | 3.03%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.03%   |
| Intel Ethernet Connection I217-V                                  | 1        | 3.03%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 3.03%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 3.03%   |
| ICS Advent USB 10/100 LAN                                         | 1        | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 55.32%  |
| WiFi     | 20       | 42.55%  |
| Unknown  | 1        | 2.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 52.17%  |
| WiFi     | 11       | 47.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 65.38%  |
| 2     | 9        | 34.62%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 84.62%  |
| Yes  | 4        | 15.38%  |

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
| Intel                  | 17       | 44.74%  |
| AMD                    | 10       | 26.32%  |
| Nvidia                 | 8        | 21.05%  |
| SteelSeries ApS        | 1        | 2.63%   |
| Generalplus Technology | 1        | 2.63%   |
| C-Media Electronics    | 1        | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6        | 12%     |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 12%     |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4        | 8%      |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 4%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 4%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 4%      |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 4%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 4%      |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 4%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2        | 4%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 4%      |
| SteelSeries ApS SteelSeries GameDAC                                               | 1        | 2%      |
| Nvidia MCP61 High Definition Audio                                                | 1        | 2%      |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 2%      |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 2%      |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 1        | 2%      |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 2%      |
| Nvidia GF106 High Definition Audio Controller                                     | 1        | 2%      |
| Intel USB PnP Sound Device                                                        | 1        | 2%      |
| Intel Cannon Point-LP High Definition Audio Controller                            | 1        | 2%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 2%      |
| Intel 200 Series PCH HD Audio                                                     | 1        | 2%      |
| Generalplus Technology USB Audio Device                                           | 1        | 2%      |
| C-Media Electronics Audio Adapter                                                 | 1        | 2%      |
| AMD Trinity HDMI Audio Controller                                                 | 1        | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1        | 2%      |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 2%      |
| AMD FCH Azalia Controller                                                         | 1        | 2%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 5        | 29.41%  |
| Samsung Electronics | 2        | 11.76%  |
| Kingston            | 2        | 11.76%  |
| Crucial             | 2        | 11.76%  |
| Unifosa             | 1        | 5.88%   |
| SK hynix            | 1        | 5.88%   |
| Silicon Power       | 1        | 5.88%   |
| G.Skill             | 1        | 5.88%   |
| Corsair             | 1        | 5.88%   |
| A-DATA Technology   | 1        | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                  | 1        | 5.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                  | 1        | 5.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                  | 1        | 5.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                          | 1        | 5.56%   |
| Unknown RAM Module 2GB DIMM                                | 1        | 5.56%   |
| Unifosa RAM Module 2GB DIMM DDR3 1333MT/s                  | 1        | 5.56%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                     | 1        | 5.56%   |
| Silicon Power RAM SP016GBLFU266B02 16GB DIMM DDR4 2667MT/s | 1        | 5.56%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s        | 1        | 5.56%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s     | 1        | 5.56%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 5.56%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s        | 1        | 5.56%   |
| Kingston RAM 9905678-005.A00G 8GB DIMM DDR4 2400MT/s       | 1        | 5.56%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s     | 1        | 5.56%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s  | 1        | 5.56%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s      | 1        | 5.56%   |
| Corsair RAM CM4X8GF2400Z16K4 8GB DIMM DDR4 2400MT/s        | 1        | 5.56%   |
| A-DATA RAM DDR4 3000 16384MB DIMM DDR4 3600MT/s            | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 7        | 43.75%  |
| DDR4    | 6        | 37.5%   |
| SDRAM   | 2        | 12.5%   |
| Unknown | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 14       | 93.33%  |
| SODIMM | 1        | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 4        | 23.53%  |
| 8192  | 4        | 23.53%  |
| 4096  | 4        | 23.53%  |
| 2048  | 4        | 23.53%  |
| 1024  | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 3        | 18.75%  |
| 3600    | 2        | 12.5%   |
| 2667    | 2        | 12.5%   |
| 2400    | 2        | 12.5%   |
| 1333    | 2        | 12.5%   |
| Unknown | 2        | 12.5%   |
| 2200    | 1        | 6.25%   |
| 2133    | 1        | 6.25%   |
| 1067    | 1        | 6.25%   |

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
| 0     | 17       | 60.71%  |
| 1     | 9        | 32.14%  |
| 2     | 2        | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 6        | 54.55%  |
| Graphics card            | 3        | 27.27%  |
| Multimedia controller    | 1        | 9.09%   |
| Communication controller | 1        | 9.09%   |

