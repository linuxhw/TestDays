Elementary 7 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Elementary 7.

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

Total: 44

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | 1998                        | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| HP        | 8055                        | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| ASRock    | B660M-C                     | [849fc5d462](https://linux-hardware.org/?probe=849fc5d462) | Apr 25, 2023 |
| Gigabyte  | H410M H V3                  | [8fd18554d1](https://linux-hardware.org/?probe=8fd18554d1) | Apr 24, 2023 |
| MACHINIST | E5-MR9A PRO V1.1            | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| ASUSTek   | PRIME Z390-A                | [50a18b5e94](https://linux-hardware.org/?probe=50a18b5e94) | Apr 19, 2023 |
| Foxconn   | A76GMV                      | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn   | A76GMV                      | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| ASUSTek   | PRIME Z390-A                | [e311d21def](https://linux-hardware.org/?probe=e311d21def) | Apr 13, 2023 |
| Lenovo    | 36F7 SDK0J40700 WIN 3258... | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| Gigabyte  | Z270-Gaming K3              | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| MSI       | B450M PRO-M2 MAX            | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI       | B450M PRO-M2 MAX            | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| Unknown   | Unknown                     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| AZW       | U59                         | [7674bb8dc9](https://linux-hardware.org/?probe=7674bb8dc9) | Mar 27, 2023 |
| ASUSTek   | M4A785TD-V EVO              | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| HP        | 805A                        | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP        | 3033h                       | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP        | 3033h                       | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| MSI       | B450 TOMAHAWK MAX           | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| MSI       | B365M PRO-VH                | [023f42d6d1](https://linux-hardware.org/?probe=023f42d6d1) | Mar 12, 2023 |
| Inventec  | Z CLASS A02                 | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| ASUSTek   | BT6130                      | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| Unknown   | Unknown                     | [1c5f8fef49](https://linux-hardware.org/?probe=1c5f8fef49) | Feb 28, 2023 |
| ASUSTek   | ROG STRIX Z690-A GAMING ... | [216ad20179](https://linux-hardware.org/?probe=216ad20179) | Feb 28, 2023 |
| Acer      | Predator G3620              | [72f3382b60](https://linux-hardware.org/?probe=72f3382b60) | Feb 27, 2023 |
| Gigabyte  | Z77X-UD5H                   | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte  | Z77X-UD5H                   | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell      | 07PR60 A01                  | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| ASUSTek   | TUF X470-PLUS GAMING        | [ce9dda227f](https://linux-hardware.org/?probe=ce9dda227f) | Feb 25, 2023 |
| Gigabyte  | B550 AORUS ELITE            | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| ASUSTek   | TUF X470-PLUS GAMING        | [76ab936a75](https://linux-hardware.org/?probe=76ab936a75) | Feb 16, 2023 |
| ASUSTek   | H110M-A/M.2                 | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek   | H110M-A/M.2                 | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Foxconn   | 2ADA                        | [e0f89bbca1](https://linux-hardware.org/?probe=e0f89bbca1) | Feb 16, 2023 |
| HP        | 805D                        | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| MSI       | B85-G43 GAMING              | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| ASUSTek   | TUF X470-PLUS GAMING        | [f0899499e5](https://linux-hardware.org/?probe=f0899499e5) | Feb 13, 2023 |
| ASUSTek   | H110M-A/M.2                 | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| ASUSTek   | H110M-A/M.2                 | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| Gigabyte  | F2A88XM-DS2                 | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| ASUSTek   | P7P55 LX                    | [3786e7a211](https://linux-hardware.org/?probe=3786e7a211) | Feb 04, 2023 |
| ASUSTek   | Z170 PRO GAMING             | [c2a4529e33](https://linux-hardware.org/?probe=c2a4529e33) | Jan 30, 2023 |
| Unknown   | HX90                        | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.19.0-32-generic | 9        | 26.47%  |
| 5.19.0-35-generic | 6        | 17.65%  |
| 5.15.0-58-generic | 6        | 17.65%  |
| 5.19.0-38-generic | 5        | 14.71%  |
| 5.15.0-60-generic | 4        | 11.76%  |
| 5.19.0-40-generic | 2        | 5.88%   |
| 5.19.0-41-generic | 1        | 2.94%   |
| 5.15.0-56-generic | 1        | 2.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19.0  | 22       | 66.67%  |
| 5.15.0  | 11       | 33.33%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.19    | 22       | 66.67%  |
| 5.15    | 11       | 33.33%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 33       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 33       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 33       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 87.88%  |
| LightDM | 4        | 12.12%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 12       | 36.36%  |
| de_DE | 4        | 12.12%  |
| es_ES | 3        | 9.09%   |
| ru_RU | 2        | 6.06%   |
| pt_BR | 2        | 6.06%   |
| it_IT | 2        | 6.06%   |
| pt_PT | 1        | 3.03%   |
| pl_PL | 1        | 3.03%   |
| ja_JP | 1        | 3.03%   |
| fr_FR | 1        | 3.03%   |
| fi_FI | 1        | 3.03%   |
| en_CA | 1        | 3.03%   |
| en_AU | 1        | 3.03%   |
| cs_CZ | 1        | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 30       | 90.91%  |
| EFI  | 3        | 9.09%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 30       | 90.91%  |
| Btrfs | 2        | 6.06%   |
| Xfs   | 1        | 3.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 87.88%  |
| GPT     | 4        | 12.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 96.97%  |
| Yes       | 1        | 3.03%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 27.27%  |
| Hewlett-Packard     | 5        | 15.15%  |
| Gigabyte Technology | 5        | 15.15%  |
| MSI                 | 4        | 12.12%  |
| Foxconn             | 2        | 6.06%   |
| Unknown             | 2        | 6.06%   |
| MACHINIST           | 1        | 3.03%   |
| Inventec            | 1        | 3.03%   |
| Dell                | 1        | 3.03%   |
| AZW                 | 1        | 3.03%   |
| ASRock              | 1        | 3.03%   |
| Acer                | 1        | 3.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS H110M-A/M.2                     | 2        | 6.06%   |
| Unknown                              | 2        | 6.06%   |
| MSI MS-7C31                          | 1        | 3.03%   |
| MSI MS-7C02                          | 1        | 3.03%   |
| MSI MS-7B84                          | 1        | 3.03%   |
| MSI MS-7816                          | 1        | 3.03%   |
| MACHINIST E5-MR9A PRO V1.1           | 1        | 3.03%   |
| Inventec Z CLASS                     | 1        | 3.03%   |
| HP ProDesk 600 G2 SFF                | 1        | 3.03%   |
| HP EliteDesk 800 G2 DM 35W           | 1        | 3.03%   |
| HP EliteDesk 705 G2 MT               | 1        | 3.03%   |
| HP Compaq dc7900 Ultra-Slim Desktop  | 1        | 3.03%   |
| HP 1998                              | 1        | 3.03%   |
| Gigabyte Z77X-UD5H                   | 1        | 3.03%   |
| Gigabyte Z270-Gaming K3              | 1        | 3.03%   |
| Gigabyte H410M H V3                  | 1        | 3.03%   |
| Gigabyte F2A88XM-DS2                 | 1        | 3.03%   |
| Gigabyte B550 AORUS ELITE            | 1        | 3.03%   |
| Foxconn A76GMV                       | 1        | 3.03%   |
| Foxconn 400-034                      | 1        | 3.03%   |
| Dell Inspiron 5675                   | 1        | 3.03%   |
| AZW U59                              | 1        | 3.03%   |
| ASUS Z170 PRO GAMING                 | 1        | 3.03%   |
| ASUS TUF X470-PLUS GAMING            | 1        | 3.03%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4 | 1        | 3.03%   |
| ASUS PRIME Z390-A                    | 1        | 3.03%   |
| ASUS P7P55 LX                        | 1        | 3.03%   |
| ASUS M4A785TD-V EVO                  | 1        | 3.03%   |
| ASUS BT6130-8                        | 1        | 3.03%   |
| ASRock B660M-C                       | 1        | 3.03%   |
| Acer Predator G3620                  | 1        | 3.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP EliteDesk         | 2        | 6.06%   |
| ASUS H110M-A         | 2        | 6.06%   |
| Unknown              | 2        | 6.06%   |
| MSI MS-7C31          | 1        | 3.03%   |
| MSI MS-7C02          | 1        | 3.03%   |
| MSI MS-7B84          | 1        | 3.03%   |
| MSI MS-7816          | 1        | 3.03%   |
| MACHINIST E5-MR9A    | 1        | 3.03%   |
| Inventec Z           | 1        | 3.03%   |
| HP ProDesk           | 1        | 3.03%   |
| HP Compaq            | 1        | 3.03%   |
| HP 1998              | 1        | 3.03%   |
| Gigabyte Z77X-UD5H   | 1        | 3.03%   |
| Gigabyte Z270-Gaming | 1        | 3.03%   |
| Gigabyte H410M       | 1        | 3.03%   |
| Gigabyte F2A88XM-DS2 | 1        | 3.03%   |
| Gigabyte B550        | 1        | 3.03%   |
| Foxconn A76GMV       | 1        | 3.03%   |
| Foxconn 400-034      | 1        | 3.03%   |
| Dell Inspiron        | 1        | 3.03%   |
| AZW U59              | 1        | 3.03%   |
| ASUS Z170            | 1        | 3.03%   |
| ASUS TUF             | 1        | 3.03%   |
| ASUS ROG             | 1        | 3.03%   |
| ASUS PRIME           | 1        | 3.03%   |
| ASUS P7P55           | 1        | 3.03%   |
| ASUS M4A785TD-V      | 1        | 3.03%   |
| ASUS BT6130-8        | 1        | 3.03%   |
| ASRock B660M-C       | 1        | 3.03%   |
| Acer Predator        | 1        | 3.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 5        | 15.15%  |
| 2021 | 4        | 12.12%  |
| 2016 | 4        | 12.12%  |
| 2012 | 4        | 12.12%  |
| 2015 | 3        | 9.09%   |
| 2020 | 2        | 6.06%   |
| 2018 | 2        | 6.06%   |
| 2009 | 2        | 6.06%   |
| 2008 | 2        | 6.06%   |
| 2023 | 1        | 3.03%   |
| 2022 | 1        | 3.03%   |
| 2019 | 1        | 3.03%   |
| 2017 | 1        | 3.03%   |
| 2010 | 1        | 3.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 33       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 33       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 33       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 9        | 27.27%  |
| 16.01-24.0  | 9        | 27.27%  |
| 8.01-16.0   | 6        | 18.18%  |
| 32.01-64.0  | 4        | 12.12%  |
| 3.01-4.0    | 4        | 12.12%  |
| 64.01-256.0 | 1        | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 2.01-3.0  | 18       | 54.55%  |
| 3.01-4.0  | 6        | 18.18%  |
| 1.01-2.0  | 6        | 18.18%  |
| 4.01-8.0  | 2        | 6.06%   |
| 8.01-16.0 | 1        | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 39.39%  |
| 2      | 12       | 36.36%  |
| 3      | 4        | 12.12%  |
| 5      | 2        | 6.06%   |
| 4      | 2        | 6.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 66.67%  |
| Yes       | 11       | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 33       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 54.55%  |
| Yes       | 15       | 45.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 51.52%  |
| Yes       | 16       | 48.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 6        | 18.18%  |
| Germany     | 6        | 18.18%  |
| Spain       | 3        | 9.09%   |
| Brazil      | 3        | 9.09%   |
| Russia      | 2        | 6.06%   |
| Italy       | 2        | 6.06%   |
| Portugal    | 1        | 3.03%   |
| Netherlands | 1        | 3.03%   |
| Japan       | 1        | 3.03%   |
| India       | 1        | 3.03%   |
| Greece      | 1        | 3.03%   |
| France      | 1        | 3.03%   |
| Finland     | 1        | 3.03%   |
| Czechia     | 1        | 3.03%   |
| Chile       | 1        | 3.03%   |
| Canada      | 1        | 3.03%   |
| Australia   | 1        | 3.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Tucson             | 1        | 2.94%   |
| Tremblay-en-France | 1        | 2.94%   |
| Stuttgart          | 1        | 2.94%   |
| Sao Paulo          | 1        | 2.94%   |
| Santiago           | 1        | 2.94%   |
| San Marcos         | 1        | 2.94%   |
| Salt Lake City     | 1        | 2.94%   |
| Radeburg           | 1        | 2.94%   |
| Prague             | 1        | 2.94%   |
| Osaka              | 1        | 2.94%   |
| Niederaichbach     | 1        | 2.94%   |
| New York           | 1        | 2.94%   |
| Munich             | 1        | 2.94%   |
| Moscow             | 1        | 2.94%   |
| Monsummano Terme   | 1        | 2.94%   |
| Mombello di Torino | 1        | 2.94%   |
| Melbourne          | 1        | 2.94%   |
| Madrid             | 1        | 2.94%   |
| Lousada            | 1        | 2.94%   |
| Los Montesinos     | 1        | 2.94%   |
| Las Vegas          | 1        | 2.94%   |
| Lagerdorf          | 1        | 2.94%   |
| Laberweinting      | 1        | 2.94%   |
| Juazeiro do Norte  | 1        | 2.94%   |
| Irvine             | 1        | 2.94%   |
| Imperatriz         | 1        | 2.94%   |
| Helsinki           | 1        | 2.94%   |
| Hamm               | 1        | 2.94%   |
| Cheboksary         | 1        | 2.94%   |
| Catarroja          | 1        | 2.94%   |
| Brampton           | 1        | 2.94%   |
| Athens             | 1        | 2.94%   |
| Amsterdam          | 1        | 2.94%   |
| Ahmedabad          | 1        | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 10       | 10     | 16.95%  |
| Seagate                     | 8        | 10     | 13.56%  |
| Samsung Electronics         | 7        | 11     | 11.86%  |
| Kingston                    | 4        | 4      | 6.78%   |
| Sandisk                     | 3        | 3      | 5.08%   |
| Toshiba                     | 2        | 2      | 3.39%   |
| Team                        | 2        | 3      | 3.39%   |
| Netac                       | 2        | 3      | 3.39%   |
| Micron/Crucial Technology   | 2        | 2      | 3.39%   |
| Hitachi                     | 2        | 2      | 3.39%   |
| China                       | 2        | 2      | 3.39%   |
| Yeestor                     | 1        | 1      | 1.69%   |
| Silicon Motion              | 1        | 1      | 1.69%   |
| SD                          | 1        | 1      | 1.69%   |
| PNY                         | 1        | 1      | 1.69%   |
| NGFF                        | 1        | 1      | 1.69%   |
| MAXIO Technology (Hangzhou) | 1        | 1      | 1.69%   |
| LITEONIT                    | 1        | 1      | 1.69%   |
| KingDian                    | 1        | 2      | 1.69%   |
| Intenso                     | 1        | 1      | 1.69%   |
| HS-SSD-E100                 | 1        | 2      | 1.69%   |
| Crucial                     | 1        | 1      | 1.69%   |
| Corsair                     | 1        | 1      | 1.69%   |
| Apacer                      | 1        | 1      | 1.69%   |
| A-DATA Technology           | 1        | 1      | 1.69%   |
| Unknown                     | 1        | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| WDC WD10EZEX-60WN4A0 1TB                               | 3        | 4.55%   |
| Kingston SA400S37240G 240GB SSD                        | 3        | 4.55%   |
| Samsung SSD 850 EVO 250GB                              | 2        | 3.03%   |
| Yeestor 512GB                                          | 1        | 1.52%   |
| WDC WDS480G2G0C-00AJM0 480GB                           | 1        | 1.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                       | 1        | 1.52%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                         | 1        | 1.52%   |
| WDC WD2500JB-55GVA0 250GB                              | 1        | 1.52%   |
| WDC WD10EZEX-60ZF5A0 1TB                               | 1        | 1.52%   |
| WDC WD10EZEX-00BN5A0 1TB                               | 1        | 1.52%   |
| WDC WD10EZEX-00BBHA0 1TB                               | 1        | 1.52%   |
| Toshiba MQ01ABD100 1TB                                 | 1        | 1.52%   |
| Toshiba DT01ACA100 1TB                                 | 1        | 1.52%   |
| Team T253X2001T 1024GB SSD                             | 1        | 1.52%   |
| Team T253X1480G 480GB SSD                              | 1        | 1.52%   |
| Team L3 SSD 240GB                                      | 1        | 1.52%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 1        | 1.52%   |
| Seagate ST9500325AS 500GB                              | 1        | 1.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB                    | 1        | 1.52%   |
| Seagate ST4000DM004-2CV104 4TB                         | 1        | 1.52%   |
| Seagate ST31000528AS 1TB                               | 1        | 1.52%   |
| Seagate ST2000DM008-2FR102 2TB                         | 1        | 1.52%   |
| Seagate ST1000DM003-9YN162 1TB                         | 1        | 1.52%   |
| Seagate ST1000DM003-1ER162 1TB                         | 1        | 1.52%   |
| Seagate M3 1TB                                         | 1        | 1.52%   |
| Seagate BarraCuda Q1 SSD ZA960CV10001 960GB            | 1        | 1.52%   |
| Seagate BarraCuda 120 SSD ZA500CM10003 500GB           | 1        | 1.52%   |
| SD Ultra 3D 1TB                                        | 1        | 1.52%   |
| Sandisk WD_BLACK SN750 SE 500GB                        | 1        | 1.52%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                  | 1        | 1.52%   |
| SanDisk SD7TB3Q-256G-1006 256GB SSD                    | 1        | 1.52%   |
| Samsung SSD 870 EVO 250GB                              | 1        | 1.52%   |
| Samsung SSD 860 EVO 1TB                                | 1        | 1.52%   |
| Samsung SSD 850 EVO M.2 250GB                          | 1        | 1.52%   |
| Samsung SSD 840 Series 120GB                           | 1        | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB      | 1        | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB    | 1        | 1.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB     | 1        | 1.52%   |
| Samsung HD502HJ 500GB                                  | 1        | 1.52%   |
| PNY CS900 480GB SSD                                    | 1        | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 7      | 36.84%  |
| Seagate             | 7        | 7      | 36.84%  |
| Toshiba             | 2        | 2      | 10.53%  |
| Hitachi             | 2        | 2      | 10.53%  |
| Samsung Electronics | 1        | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 7      | 17.24%  |
| Kingston            | 4        | 4      | 13.79%  |
| WDC                 | 2        | 2      | 6.9%    |
| Team                | 2        | 3      | 6.9%    |
| Seagate             | 2        | 2      | 6.9%    |
| China               | 2        | 2      | 6.9%    |
| SanDisk             | 1        | 1      | 3.45%   |
| PNY                 | 1        | 1      | 3.45%   |
| NGFF                | 1        | 1      | 3.45%   |
| Netac               | 1        | 1      | 3.45%   |
| LITEONIT            | 1        | 1      | 3.45%   |
| KingDian            | 1        | 2      | 3.45%   |
| Intenso             | 1        | 1      | 3.45%   |
| HS-SSD-E100         | 1        | 1      | 3.45%   |
| Crucial             | 1        | 1      | 3.45%   |
| Corsair             | 1        | 1      | 3.45%   |
| Apacer              | 1        | 1      | 3.45%   |
| A-DATA Technology   | 1        | 1      | 3.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| SSD     | 26       | 33     | 47.27%  |
| HDD     | 15       | 19     | 27.27%  |
| NVMe    | 8        | 10     | 14.55%  |
| Unknown | 6        | 7      | 10.91%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 32       | 57     | 76.19%  |
| NVMe | 8        | 10     | 19.05%  |
| SAS  | 2        | 2      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 31     | 61.54%  |
| 0.51-1.0   | 12       | 18     | 30.77%  |
| 1.01-2.0   | 2        | 2      | 5.13%   |
| 3.01-4.0   | 1        | 1      | 2.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 16       | 48.48%  |
| 501-1000   | 9        | 27.27%  |
| 251-500    | 5        | 15.15%  |
| 21-50      | 1        | 3.03%   |
| 2001-3000  | 1        | 3.03%   |
| 51-100     | 1        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 13       | 39.39%  |
| 21-50     | 10       | 30.3%   |
| 51-100    | 5        | 15.15%  |
| 101-250   | 3        | 9.09%   |
| 251-500   | 1        | 3.03%   |
| 1001-2000 | 1        | 3.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| Hitachi HTS725050A7E630 500GB | 1        | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 1        | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 1        | 1      | 100%    |

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
| Detected | 30       | 64     | 85.71%  |
| Works    | 4        | 4      | 11.43%  |
| Malfunc  | 1        | 1      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 22       | 47.83%  |
| AMD                         | 11       | 23.91%  |
| SanDisk                     | 3        | 6.52%   |
| Samsung Electronics         | 2        | 4.35%   |
| Micron/Crucial Technology   | 2        | 4.35%   |
| Marvell Technology Group    | 2        | 4.35%   |
| ASMedia Technology          | 2        | 4.35%   |
| Silicon Motion              | 1        | 2.17%   |
| MAXIO Technology (Hangzhou) | 1        | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 12.73%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 9.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 5.45%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 5.45%   |
| SanDisk Non-Volatile memory controller                                         | 2        | 3.64%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2        | 3.64%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 3.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 3.64%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 3.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2        | 3.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 3.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1        | 1.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 1.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 1.82%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 1.82%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1        | 1.82%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.82%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                        | 1        | 1.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 1.82%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 1.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.82%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 1.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 1.82%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 1        | 1.82%   |
| AMD X370 Series Chipset SATA Controller                                        | 1        | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 1.82%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 1.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 33       | 73.33%  |
| NVMe | 8        | 17.78%  |
| IDE  | 3        | 6.67%   |
| RAID | 1        | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 22       | 66.67%  |
| AMD    | 11       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz           | 1        | 3.03%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1        | 3.03%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 1        | 3.03%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1        | 3.03%   |
| Intel Core i7-6700T CPU @ 2.80GHz             | 1        | 3.03%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 3.03%   |
| Intel Core i7-3770S CPU @ 3.10GHz             | 1        | 3.03%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1        | 3.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1        | 3.03%   |
| Intel Core i5-7500T CPU @ 2.70GHz             | 1        | 3.03%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 1        | 3.03%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1        | 3.03%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1        | 3.03%   |
| Intel Core i5 CPU 760 @ 2.80GHz               | 1        | 3.03%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 1        | 3.03%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 1        | 3.03%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 1        | 3.03%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1        | 3.03%   |
| Intel Celeron N5105 @ 2.00GHz                 | 1        | 3.03%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1        | 3.03%   |
| Intel 12th Gen Core i7-12700K                 | 1        | 3.03%   |
| Intel 12th Gen Core i7-12700F                 | 1        | 3.03%   |
| AMD Sempron 145 Processor                     | 1        | 3.03%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 1        | 3.03%   |
| AMD Ryzen 7 1700X Eight-Core Processor        | 1        | 3.03%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics    | 1        | 3.03%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1        | 3.03%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 1        | 3.03%   |
| AMD PRO A6-8550B R5, 6 Compute Cores 2C+4G    | 1        | 3.03%   |
| AMD Phenom II X6 1055T Processor              | 1        | 3.03%   |
| AMD G-T56N Processor                          | 1        | 3.03%   |
| AMD Athlon 3000G with Radeon Vega Graphics    | 1        | 3.03%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 1        | 3.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i7    | 6        | 18.18%  |
| Intel Core i5    | 5        | 15.15%  |
| Other            | 3        | 9.09%   |
| Intel Core i3    | 3        | 9.09%   |
| Intel Celeron    | 2        | 6.06%   |
| AMD Ryzen 5      | 2        | 6.06%   |
| Intel Xeon       | 1        | 3.03%   |
| Intel Pentium    | 1        | 3.03%   |
| Intel Core i9    | 1        | 3.03%   |
| Intel Core 2 Duo | 1        | 3.03%   |
| AMD Sempron      | 1        | 3.03%   |
| AMD Ryzen 9      | 1        | 3.03%   |
| AMD Ryzen 7      | 1        | 3.03%   |
| AMD Ryzen 5 PRO  | 1        | 3.03%   |
| AMD Phenom II X6 | 1        | 3.03%   |
| AMD G            | 1        | 3.03%   |
| AMD Athlon       | 1        | 3.03%   |
| AMD A8           | 1        | 3.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 13       | 39.39%  |
| 2      | 6        | 18.18%  |
| 6      | 5        | 15.15%  |
| 12     | 3        | 9.09%   |
| 8      | 3        | 9.09%   |
| 1      | 3        | 9.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 33       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 21       | 63.64%  |
| 1      | 12       | 36.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 33       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 28       | 84.85%  |
| 0x906e9    | 1        | 3.03%   |
| 0x906c0    | 1        | 3.03%   |
| 0x306a9    | 1        | 3.03%   |
| 0x08108109 | 1        | 3.03%   |
| 0x010000c8 | 1        | 3.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Skylake       | 4        | 12.12%  |
| KabyLake      | 4        | 12.12%  |
| IvyBridge     | 4        | 12.12%  |
| Haswell       | 3        | 9.09%   |
| Zen+          | 2        | 6.06%   |
| Zen 2         | 2        | 6.06%   |
| Steamroller   | 2        | 6.06%   |
| K10           | 2        | 6.06%   |
| Unknown       | 2        | 6.06%   |
| Zen 3         | 1        | 3.03%   |
| Zen           | 1        | 3.03%   |
| Tremont       | 1        | 3.03%   |
| Penryn        | 1        | 3.03%   |
| Nehalem       | 1        | 3.03%   |
| Goldmont plus | 1        | 3.03%   |
| CometLake     | 1        | 3.03%   |
| Bobcat        | 1        | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 13       | 38.24%  |
| Nvidia | 11       | 32.35%  |
| Intel  | 10       | 29.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GK107 [GeForce GT 640]                                               | 2        | 5.71%   |
| Intel HD Graphics 530                                                       | 2        | 5.71%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 5.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 5.71%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 2.86%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.86%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.86%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 1        | 2.86%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 2.86%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 2.86%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 2.86%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 2.86%   |
| Nvidia GA103 [GeForce RTX 3060 Ti]                                          | 1        | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.86%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 2.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 2.86%   |
| Intel HD Graphics 630                                                       | 1        | 2.86%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 2.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.86%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2.86%   |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 2.86%   |
| AMD RS880 [Radeon HD 4200]                                                  | 1        | 2.86%   |
| AMD RS780L [Radeon 3000]                                                    | 1        | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 2.86%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 2.86%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 2.86%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 1        | 2.86%   |
| AMD Kaveri [Radeon R5 Graphics]                                             | 1        | 2.86%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 1        | 2.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 1        | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 12       | 36.36%  |
| 1 x Nvidia     | 10       | 30.3%   |
| 1 x Intel      | 9        | 27.27%  |
| 2 x AMD        | 1        | 3.03%   |
| Intel + Nvidia | 1        | 3.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 30       | 90.91%  |
| Proprietary | 3        | 9.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 87.88%  |
| 7.01-8.0   | 2        | 6.06%   |
| 0.51-1.0   | 1        | 3.03%   |
| 0.01-0.5   | 1        | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 6        | 16.67%  |
| Goldstar             | 6        | 16.67%  |
| Sceptre Tech         | 2        | 5.56%   |
| Philips              | 2        | 5.56%   |
| Hewlett-Packard      | 2        | 5.56%   |
| Dell                 | 2        | 5.56%   |
| Vizio                | 1        | 2.78%   |
| Sony                 | 1        | 2.78%   |
| NSL                  | 1        | 2.78%   |
| MYS                  | 1        | 2.78%   |
| MSI                  | 1        | 2.78%   |
| Kogan                | 1        | 2.78%   |
| Hitachi              | 1        | 2.78%   |
| HannStar             | 1        | 2.78%   |
| Fujitsu Siemens      | 1        | 2.78%   |
| Eizo                 | 1        | 2.78%   |
| CVT                  | 1        | 2.78%   |
| BenQ                 | 1        | 2.78%   |
| ASUSTek Computer     | 1        | 2.78%   |
| AOC                  | 1        | 2.78%   |
| Ancor Communications | 1        | 2.78%   |
| Acer                 | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 1        | 2.7%    |
| Sony TV SNY7A02 1360x768 708x398mm 32.0-inch                          | 1        | 2.7%    |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch        | 1        | 2.7%    |
| Sceptre Tech E248W-19203S SPT099D 1920x1080 443x249mm 20.0-inch       | 1        | 2.7%    |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch  | 1        | 2.7%    |
| Samsung Electronics SMB2030HD SAM0709 1600x900 443x249mm 20.0-inch    | 1        | 2.7%    |
| Samsung Electronics S27A950D SAM079F 1920x1080 598x336mm 27.0-inch    | 1        | 2.7%    |
| Samsung Electronics S24E450 SAM0C7F 1920x1080 521x293mm 23.5-inch     | 1        | 2.7%    |
| Samsung Electronics LS27AG55x SAM71E0 2560x1440 597x336mm 27.0-inch   | 1        | 2.7%    |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1        | 2.7%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1        | 2.7%    |
| Philips 220TS PHLC06B 1920x1080 477x268mm 21.5-inch                   | 1        | 2.7%    |
| NSL RGB-27QHD NSL2711 2560x1440 597x336mm 27.0-inch                   | 1        | 2.7%    |
| MYS LCD Monitor MYS1700 1280x1024 360x240mm 17.0-inch                 | 1        | 2.7%    |
| MSI G241 MSI3BA4 1920x1080 527x296mm 23.8-inch                        | 1        | 2.7%    |
| Kogan KAMN27QF7TA KGN0270 2560x1440 698x393mm 31.5-inch               | 1        | 2.7%    |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch               | 1        | 2.7%    |
| Hewlett-Packard VH240a HPN3499 1920x1080 527x296mm 23.8-inch          | 1        | 2.7%    |
| Hewlett-Packard E231 HWP3063 1920x1080 509x286mm 23.0-inch            | 1        | 2.7%    |
| HannStar HSG1074 HSP0019 1920x1080 543x305mm 24.5-inch                | 1        | 2.7%    |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch              | 1        | 2.7%    |
| Goldstar HDR WFHD GSM5BA0 2560x1080 798x334mm 34.1-inch               | 1        | 2.7%    |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1        | 2.7%    |
| Goldstar E2260 GSM57E0 1920x1080 477x268mm 21.5-inch                  | 1        | 2.7%    |
| Goldstar 27MP35 GSM5A86 1920x1080 598x337mm 27.0-inch                 | 1        | 2.7%    |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 1        | 2.7%    |
| Fujitsu Siemens B27T-7 LED FUS083D 1920x1080 598x336mm 27.0-inch      | 1        | 2.7%    |
| Eizo LCD Monitor EV2456 1920x1200                                     | 1        | 2.7%    |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                      | 1        | 2.7%    |
| Dell LCD Monitor LNK0001 1920x1080 256x192mm 12.6-inch                | 1        | 2.7%    |
| Dell E1914H DELD03A 1366x768 410x230mm 18.5-inch                      | 1        | 2.7%    |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                      | 1        | 2.7%    |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                     | 1        | 2.7%    |
| ASUSTek Computer VG279Q1A AUS2725 1920x1080 597x336mm 27.0-inch       | 1        | 2.7%    |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 1        | 2.7%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 1        | 2.7%    |
| Acer P166HQL ACR0276 1366x768 344x194mm 15.5-inch                     | 1        | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 21       | 58.33%  |
| 2560x1440 (QHD)   | 6        | 16.67%  |
| 1920x1200 (WUXGA) | 2        | 5.56%   |
| 1366x768 (WXGA)   | 2        | 5.56%   |
| 3840x2160 (4K)    | 1        | 2.78%   |
| 2560x1080         | 1        | 2.78%   |
| 1600x900 (HD+)    | 1        | 2.78%   |
| 1360x768          | 1        | 2.78%   |
| 1280x1024 (SXGA)  | 1        | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 18.92%  |
| 24      | 7        | 18.92%  |
| 21      | 5        | 13.51%  |
| 23      | 4        | 10.81%  |
| 31      | 3        | 8.11%   |
| 18      | 2        | 5.41%   |
| 84      | 1        | 2.7%    |
| 42      | 1        | 2.7%    |
| 34      | 1        | 2.7%    |
| 32      | 1        | 2.7%    |
| 26      | 1        | 2.7%    |
| 20      | 1        | 2.7%    |
| 17      | 1        | 2.7%    |
| 14      | 1        | 2.7%    |
| Unknown | 1        | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 17       | 48.57%  |
| 401-500     | 8        | 22.86%  |
| 601-700     | 3        | 8.57%   |
| 701-800     | 2        | 5.71%   |
| 351-400     | 1        | 2.86%   |
| 201-300     | 1        | 2.86%   |
| 1501-2000   | 1        | 2.86%   |
| 901-1000    | 1        | 2.86%   |
| Unknown     | 1        | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 82.86%  |
| 16/10   | 2        | 5.71%   |
| 4/3     | 1        | 2.86%   |
| 3/2     | 1        | 2.86%   |
| 21/9    | 1        | 2.86%   |
| Unknown | 1        | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 30.56%  |
| 301-350        | 7        | 19.44%  |
| 351-500        | 5        | 13.89%  |
| 251-300        | 3        | 8.33%   |
| 151-200        | 3        | 8.33%   |
| 141-150        | 2        | 5.56%   |
| More than 1000 | 1        | 2.78%   |
| 131-140        | 1        | 2.78%   |
| 101-110        | 1        | 2.78%   |
| 501-1000       | 1        | 2.78%   |
| Unknown        | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 69.7%   |
| 101-120 | 7        | 21.21%  |
| 1-50    | 1        | 3.03%   |
| 121-160 | 1        | 3.03%   |
| Unknown | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 84.85%  |
| 2     | 5        | 15.15%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 17       | 36.96%  |
| Realtek Semiconductor    | 16       | 34.78%  |
| Qualcomm Atheros         | 4        | 8.7%    |
| Xiaomi                   | 1        | 2.17%   |
| TP-Link                  | 1        | 2.17%   |
| Samsung Electronics      | 1        | 2.17%   |
| Ralink                   | 1        | 2.17%   |
| MediaTek                 | 1        | 2.17%   |
| Marvell Technology Group | 1        | 2.17%   |
| Linksys                  | 1        | 2.17%   |
| Broadcom                 | 1        | 2.17%   |
| ASUSTek Computer         | 1        | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14       | 26.42%  |
| Intel Ethernet Controller I225-V                                  | 3        | 5.66%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 5.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 3.77%   |
| Intel Wireless 3165                                               | 2        | 3.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 3.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 3.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 3.77%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 3.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.89%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 1.89%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.89%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1        | 1.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 1.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.89%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 1.89%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless               | 1        | 1.89%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235]     | 1        | 1.89%   |
| Intel Wireless 8260                                               | 1        | 1.89%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.89%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.89%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 1.89%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 1.89%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.89%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 1.89%   |
| ASUS 802.11ac WLAN Adapter                                        | 1        | 1.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 8        | 50%     |
| Realtek Semiconductor    | 2        | 12.5%   |
| Ralink                   | 1        | 6.25%   |
| Qualcomm Atheros         | 1        | 6.25%   |
| MediaTek                 | 1        | 6.25%   |
| Marvell Technology Group | 1        | 6.25%   |
| Linksys                  | 1        | 6.25%   |
| ASUSTek Computer         | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2        | 12.5%   |
| Intel Wireless 3165                                           | 2        | 12.5%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2        | 12.5%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 2        | 12.5%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1        | 6.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1        | 6.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 1        | 6.25%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless           | 1        | 6.25%   |
| Linksys AE1200 802.11bgn Wireless Adapter [Broadcom BCM43235] | 1        | 6.25%   |
| Intel Wireless 8260                                           | 1        | 6.25%   |
| Intel Wi-Fi 6 AX200                                           | 1        | 6.25%   |
| ASUS 802.11ac WLAN Adapter                                    | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 41.67%  |
| Intel                 | 15       | 41.67%  |
| Qualcomm Atheros      | 3        | 8.33%   |
| Xiaomi                | 1        | 2.78%   |
| TP-Link               | 1        | 2.78%   |
| Broadcom              | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14       | 38.89%  |
| Intel Ethernet Controller I225-V                                  | 3        | 8.33%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 8.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 5.56%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 5.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 2.78%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 2.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.78%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.78%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 2.78%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 2.78%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 2.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 33       | 67.35%  |
| WiFi     | 15       | 30.61%  |
| Modem    | 1        | 2.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 78.79%  |
| WiFi     | 7        | 21.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 60.61%  |
| 2     | 12       | 36.36%  |
| 3     | 1        | 3.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 57.58%  |
| Yes  | 14       | 42.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 8        | 50%     |
| Cambridge Silicon Radio         | 4        | 25%     |
| Qualcomm Atheros Communications | 1        | 6.25%   |
| MediaTek                        | 1        | 6.25%   |
| Broadcom                        | 1        | 6.25%   |
| ASUSTek Computer                | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 25%     |
| Intel Bluetooth wireless interface                  | 3        | 18.75%  |
| Intel AX210 Bluetooth                               | 2        | 12.5%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 6.25%   |
| MediaTek Wireless_Device                            | 1        | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 6.25%   |
| Intel AX201 Bluetooth                               | 1        | 6.25%   |
| Intel AX200 Bluetooth                               | 1        | 6.25%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1        | 6.25%   |
| ASUS ASUS USB-BT500                                 | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 22       | 36.67%  |
| AMD                      | 15       | 25%     |
| Nvidia                   | 11       | 18.33%  |
| Logitech                 | 3        | 5%      |
| C-Media Electronics      | 3        | 5%      |
| Razer USA                | 1        | 1.67%   |
| Nordic Semiconductor ASA | 1        | 1.67%   |
| KTMicro                  | 1        | 1.67%   |
| Goldvish                 | 1        | 1.67%   |
| Creative Labs            | 1        | 1.67%   |
| ASUSTek Computer         | 1        | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 5        | 7.35%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 3        | 4.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 3        | 4.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 3        | 4.41%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 2        | 2.94%   |
| Intel Alder Lake-S HD Audio Controller                                                          | 2        | 2.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 2        | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 2        | 2.94%   |
| Intel 200 Series PCH HD Audio                                                                   | 2        | 2.94%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 2        | 2.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                              | 2        | 2.94%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 2        | 2.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 2        | 2.94%   |
| AMD FCH Azalia Controller                                                                       | 2        | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 2        | 2.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 2        | 2.94%   |
| Razer USA Razer Barracuda X                                                                     | 1        | 1.47%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 1        | 1.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 1        | 1.47%   |
| Nvidia High Definition Audio Controller                                                         | 1        | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 1        | 1.47%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 1        | 1.47%   |
| Nvidia Audio device                                                                             | 1        | 1.47%   |
| Nordic Semiconductor ASA USB Composite Device                                                   | 1        | 1.47%   |
| Logitech [G533 Wireless Headset Dongle]                                                         | 1        | 1.47%   |
| Logitech Logi Z407                                                                              | 1        | 1.47%   |
| Logitech G432 Gaming Headset                                                                    | 1        | 1.47%   |
| KTMicro KT USB Audio                                                                            | 1        | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1        | 1.47%   |
| Intel Smart Sound Technology (SST) Audio Controller                                             | 1        | 1.47%   |
| Intel Jasper Lake HD Audio                                                                      | 1        | 1.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                    | 1        | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                                      | 1        | 1.47%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                             | 1        | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 1        | 1.47%   |
| Goldvish H210                                                                                   | 1        | 1.47%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.47%   |
| C-Media Electronics USB Microphone                                                              | 1        | 1.47%   |
| ASUSTek Computer USB Audio                                                                      | 1        | 1.47%   |
| AMD Wrestler HDMI Audio                                                                         | 1        | 1.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Kingston         | 2        | 28.57%  |
| Unknown (0x5846) | 1        | 14.29%  |
| CSX              | 1        | 14.29%  |
| Corsair          | 1        | 14.29%  |
| Apacer           | 1        | 14.29%  |
| Unknown          | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1        | 14.29%  |
| Kingston RAM HX426C16FB/4 4GB DIMM DDR4 2800MT/s              | 1        | 14.29%  |
| Kingston RAM ASU16D3LU1KBG/4G 4GB DIMM DDR3 3200MT/s          | 1        | 14.29%  |
| CSX RAM V01D3L82GB26826813 2GB DIMM 1066MT/s                  | 1        | 14.29%  |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s          | 1        | 14.29%  |
| Apacer RAM 78.CAGP7.C7Z0B 8GB DIMM DDR4 2400MT/s              | 1        | 14.29%  |
| Unknown                                                       | 1        | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 3        | 50%     |
| SDRAM   | 1        | 16.67%  |
| DDR3    | 1        | 16.67%  |
| Unknown | 1        | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 4        | 80%     |
| SODIMM | 1        | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 8192 | 3        | 50%     |
| 4096 | 2        | 33.33%  |
| 2048 | 1        | 16.67%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2800  | 2        | 28.57%  |
| 3200  | 1        | 14.29%  |
| 2667  | 1        | 14.29%  |
| 2400  | 1        | 14.29%  |
| 1066  | 1        | 14.29%  |
| 533   | 1        | 14.29%  |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 1        | 50%     |
| Canon               | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Samsung M2020 Series | 1        | 50%     |
| Canon MF4320-4350    | 1        | 50%     |

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
| Sunplus Innovation Technology | 1        | 33.33%  |
| Generalplus Technology        | 1        | 33.33%  |
| Apple                         | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Sunplus FHD Camera Microphone   | 1        | 33.33%  |
| Generalplus WEB CAM             | 1        | 33.33%  |
| Apple iPhone 5/5C/5S/6/SE/7/8/X | 1        | 33.33%  |

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
| 0     | 26       | 78.79%  |
| 1     | 7        | 21.21%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 4        | 57.14%  |
| Net/ethernet          | 1        | 14.29%  |
| Multimedia controller | 1        | 14.29%  |
| Graphics card         | 1        | 14.29%  |

