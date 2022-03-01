Q4OS - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Q4OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Q4OS/Desktop/README.md) and [notebooks](/Dist/Q4OS/Notebook/README.md).

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

| Vendor        | Model                   | Form-Factor | Probe                                                      | Date         |
|---------------|-------------------------|-------------|------------------------------------------------------------|--------------|
| Visual Lan... | Premier 10              | Notebook    | [64450e11a3](https://linux-hardware.org/?probe=64450e11a3) | Feb 04, 2022 |
| HP            | Presario CQ56           | Notebook    | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | Presario CQ56           | Notebook    | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Compaq        | 07E4h                   | Desktop     | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| MSI           | U210                    | Notebook    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Toshiba       | Satellite C660          | Notebook    | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660          | Notebook    | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| ASUSTek       | T12Eg                   | Notebook    | [115e8b584f](https://linux-hardware.org/?probe=115e8b584f) | Dec 11, 2021 |
| Toshiba       | Satellite C660          | Notebook    | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660          | Notebook    | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Gigabyte      | XP-M5S661GX             | Desktop     | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| Phoenix/Si... | M720SR                  | Notebook    | [f92c7e8c3e](https://linux-hardware.org/?probe=f92c7e8c3e) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx       | Notebook    | [cfa6202518](https://linux-hardware.org/?probe=cfa6202518) | Sep 14, 2021 |
| HP            | Laptop 15s-fq2xxx       | Notebook    | [726c3230ef](https://linux-hardware.org/?probe=726c3230ef) | Sep 14, 2021 |
| Chuwi         | GemiBook Pro            | Notebook    | [ebe8d67a10](https://linux-hardware.org/?probe=ebe8d67a10) | Sep 04, 2021 |
| TECO Elect... | TR53A0                  | Desktop     | [4ab721c7f7](https://linux-hardware.org/?probe=4ab721c7f7) | Aug 19, 2021 |
| HP            | ProBook 450 G2          | Notebook    | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| JVC           | J3N                     | Notebook    | [f8da57e850](https://linux-hardware.org/?probe=f8da57e850) | Jul 09, 2021 |
| MSI           | B550-A PRO              | Desktop     | [546cf15192](https://linux-hardware.org/?probe=546cf15192) | Jun 16, 2021 |
| MSI           | GF615M-P33 V2           | Desktop     | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| HP            | ProBook 6550b           | Notebook    | [b192718656](https://linux-hardware.org/?probe=b192718656) | Mar 13, 2021 |
| HP            | 2000                    | Notebook    | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| ASRock        | G41M-VS3                | Desktop     | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3                | Desktop     | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |
| ASUSTek       | A6JC                    | Notebook    | [b04f51dd1c](https://linux-hardware.org/?probe=b04f51dd1c) | Jan 29, 2021 |
| ASUSTek       | A6JC                    | Notebook    | [097dd7f151](https://linux-hardware.org/?probe=097dd7f151) | Jan 29, 2021 |
| Lenovo        | ThinkPad 11e 20DAS0PS00 | Notebook    | [2d618b7420](https://linux-hardware.org/?probe=2d618b7420) | Dec 14, 2020 |
| Packard Be... | EasyNote LM81           | Notebook    | [d6b0c23c18](https://linux-hardware.org/?probe=d6b0c23c18) | Nov 23, 2020 |
| Qilive        | QW19141AMSP             | Notebook    | [b8f3486ae1](https://linux-hardware.org/?probe=b8f3486ae1) | Aug 27, 2020 |
| HP            | OmniBook PC             | Notebook    | [5e33febbc1](https://linux-hardware.org/?probe=5e33febbc1) | Jul 10, 2020 |
| Unknown       | MEDION                  | Notebook    | [6a06a14f6a](https://linux-hardware.org/?probe=6a06a14f6a) | May 07, 2020 |
| TrekStor      | SurfTab wintron 7.0     | Tablet      | [464706154e](https://linux-hardware.org/?probe=464706154e) | Jun 26, 2019 |
| TrekStor      | SurfTab wintron 7.0     | Tablet      | [db63ea2d00](https://linux-hardware.org/?probe=db63ea2d00) | Jun 19, 2019 |
| TrekStor      | SurfTab wintron 7.0     | Tablet      | [9e530b2e21](https://linux-hardware.org/?probe=9e530b2e21) | Jun 18, 2019 |
| Philco        | 14I                     | Notebook    | [bf4c449b31](https://linux-hardware.org/?probe=bf4c449b31) | Apr 14, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 4.19.0-17-amd64        | 4         | 14.29%  |
| 5.10.0-8-amd64         | 2         | 7.14%   |
| 5.10.0-10-686-pae      | 2         | 7.14%   |
| 5.9.0-5-amd64          | 1         | 3.57%   |
| 5.6.0-1-amd64          | 1         | 3.57%   |
| 5.10.0-9-amd64         | 1         | 3.57%   |
| 5.10.0-9-686-pae       | 1         | 3.57%   |
| 5.10.0-8-686-pae       | 1         | 3.57%   |
| 5.10.0-11-686-pae      | 1         | 3.57%   |
| 4.9.0-9-686-pae        | 1         | 3.57%   |
| 4.9.0-8-amd64          | 1         | 3.57%   |
| 4.9.0-14-686-pae       | 1         | 3.57%   |
| 4.9.0-12-686-pae       | 1         | 3.57%   |
| 4.19.0-6-amd64         | 1         | 3.57%   |
| 4.19.0-17-686-pae      | 1         | 3.57%   |
| 4.19.0-17-686          | 1         | 3.57%   |
| 4.19.0-16-amd64        | 1         | 3.57%   |
| 4.19.0-16-686          | 1         | 3.57%   |
| 4.19.0-14-amd64        | 1         | 3.57%   |
| 4.19.0-13-amd64        | 1         | 3.57%   |
| 4.19.0-12-amd64        | 1         | 3.57%   |
| 4.19.0-10-amd64        | 1         | 3.57%   |
| 4.19.0-0.bpo.5-686-pae | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.0  | 14        | 50%     |
| 5.10.0  | 8         | 28.57%  |
| 4.9.0   | 4         | 14.29%  |
| 5.9.0   | 1         | 3.57%   |
| 5.6.0   | 1         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 14        | 50%     |
| 5.10    | 8         | 28.57%  |
| 4.9     | 4         | 14.29%  |
| 5.9     | 1         | 3.57%   |
| 5.6     | 1         | 3.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 16        | 57.14%  |
| i686   | 12        | 42.86%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Trinity | 16        | 57.14%  |
| KDE5    | 11        | 39.29%  |
| KDE     | 1         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 27        | 96.43%  |
| Tty  | 1         | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| TDM  | 16        | 57.14%  |
| SDDM | 12        | 42.86%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 11        | 39.29%  |
| Unknown | 3         | 10.71%  |
| fr_FR   | 2         | 7.14%   |
| es_ES   | 2         | 7.14%   |
| en_GB   | 2         | 7.14%   |
| de_DE   | 2         | 7.14%   |
| sl_SI   | 1         | 3.57%   |
| pl_PL   | 1         | 3.57%   |
| es_VE   | 1         | 3.57%   |
| es_AR   | 1         | 3.57%   |
| en_ZA   | 1         | 3.57%   |
| C       | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 18        | 64.29%  |
| EFI  | 10        | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 25        | 89.29%  |
| Overlay | 3         | 10.71%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 17        | 60.71%  |
| GPT     | 10        | 35.71%  |
| Unknown | 1         | 3.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 85.71%  |
| Yes       | 4         | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 16        | 57.14%  |
| Yes       | 12        | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 6         | 21.43%  |
| MSI                         | 3         | 10.71%  |
| TrekStor                    | 2         | 7.14%   |
| Toshiba                     | 2         | 7.14%   |
| ASUSTek Computer            | 2         | 7.14%   |
| Visual Land                 | 1         | 3.57%   |
| TECO Electric and Machinery | 1         | 3.57%   |
| Qilive                      | 1         | 3.57%   |
| Phoenix/SiS                 | 1         | 3.57%   |
| Philco                      | 1         | 3.57%   |
| Packard Bell                | 1         | 3.57%   |
| Lenovo                      | 1         | 3.57%   |
| JVC                         | 1         | 3.57%   |
| Gigabyte Technology         | 1         | 3.57%   |
| Compaq                      | 1         | 3.57%   |
| Chuwi                       | 1         | 3.57%   |
| ASRock                      | 1         | 3.57%   |
| Unknown                     | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| TrekStor SurfTab wintron 7.0           | 2         | 7.14%   |
| Toshiba Satellite C660                 | 2         | 7.14%   |
| Visual Land Premier 10                 | 1         | 3.57%   |
| TECO Electric and Machinery FUTRO S400 | 1         | 3.57%   |
| Qilive QW19141AMSP                     | 1         | 3.57%   |
| Phoenix/SiS M720SR                     | 1         | 3.57%   |
| Philco 14I                             | 1         | 3.57%   |
| Packard Bell EasyNote LM81             | 1         | 3.57%   |
| MSI U210                               | 1         | 3.57%   |
| MSI MS-7C56                            | 1         | 3.57%   |
| MSI MS-7597                            | 1         | 3.57%   |
| Lenovo ThinkPad 11e 20DAS0PS00         | 1         | 3.57%   |
| JVC J3N                                | 1         | 3.57%   |
| HP ProBook 6550b                       | 1         | 3.57%   |
| HP ProBook 450 G2                      | 1         | 3.57%   |
| HP Presario CQ56                       | 1         | 3.57%   |
| HP OmniBook PC                         | 1         | 3.57%   |
| HP Laptop 15s-fq2xxx                   | 1         | 3.57%   |
| HP 2000                                | 1         | 3.57%   |
| Gigabyte XP-M5S661GX                   | 1         | 3.57%   |
| Compaq Evo D510 SFF                    | 1         | 3.57%   |
| Chuwi GemiBook Pro                     | 1         | 3.57%   |
| ASUS T12Eg                             | 1         | 3.57%   |
| ASUS A6JC                              | 1         | 3.57%   |
| ASRock G41M-VS3                        | 1         | 3.57%   |
| Unknown                                | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| TrekStor SurfTab                  | 2         | 7.14%   |
| Toshiba Satellite                 | 2         | 7.14%   |
| HP ProBook                        | 2         | 7.14%   |
| Visual Land Premier               | 1         | 3.57%   |
| TECO Electric and Machinery FUTRO | 1         | 3.57%   |
| Qilive QW19141AMSP                | 1         | 3.57%   |
| Phoenix/SiS M720SR                | 1         | 3.57%   |
| Philco 14I                        | 1         | 3.57%   |
| Packard Bell EasyNote             | 1         | 3.57%   |
| MSI U210                          | 1         | 3.57%   |
| MSI MS-7C56                       | 1         | 3.57%   |
| MSI MS-7597                       | 1         | 3.57%   |
| Lenovo ThinkPad                   | 1         | 3.57%   |
| JVC J3N                           | 1         | 3.57%   |
| HP Presario                       | 1         | 3.57%   |
| HP OmniBook                       | 1         | 3.57%   |
| HP Laptop                         | 1         | 3.57%   |
| HP 2000                           | 1         | 3.57%   |
| Gigabyte XP-M5S661GX              | 1         | 3.57%   |
| Compaq Evo                        | 1         | 3.57%   |
| Chuwi GemiBook                    | 1         | 3.57%   |
| ASUS T12Eg                        | 1         | 3.57%   |
| ASUS A6JC                         | 1         | 3.57%   |
| ASRock G41M-VS3                   | 1         | 3.57%   |
| Unknown                           | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2010    | 6         | 21.43%  |
| 2020    | 3         | 10.71%  |
| 2015    | 3         | 10.71%  |
| 2014    | 2         | 7.14%   |
| 2011    | 2         | 7.14%   |
| Unknown | 2         | 7.14%   |
| 2019    | 1         | 3.57%   |
| 2017    | 1         | 3.57%   |
| 2012    | 1         | 3.57%   |
| 2009    | 1         | 3.57%   |
| 2008    | 1         | 3.57%   |
| 2007    | 1         | 3.57%   |
| 2006    | 1         | 3.57%   |
| 2005    | 1         | 3.57%   |
| 2004    | 1         | 3.57%   |
| 2002    | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 20        | 71.43%  |
| Desktop  | 6         | 21.43%  |
| Tablet   | 2         | 7.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 28        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 6         | 21.43%  |
| 0.51-1.0    | 6         | 21.43%  |
| 1.01-2.0    | 5         | 17.86%  |
| 2.01-3.0    | 4         | 14.29%  |
| 4.01-8.0    | 3         | 10.71%  |
| 0.01-0.5    | 2         | 7.14%   |
| 64.01-256.0 | 1         | 3.57%   |
| 16.01-24.0  | 1         | 3.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 10        | 35.71%  |
| 0.51-1.0  | 9         | 32.14%  |
| 0.01-0.5  | 5         | 17.86%  |
| 2.01-3.0  | 2         | 7.14%   |
| 3.01-4.0  | 1         | 3.57%   |
| 8.01-16.0 | 1         | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 23        | 82.14%  |
| 3      | 3         | 10.71%  |
| 2      | 2         | 7.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 50%     |
| No        | 14        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 85.71%  |
| No        | 4         | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 64.29%  |
| No        | 10        | 35.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 64.29%  |
| Yes       | 10        | 35.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 4         | 14.29%  |
| Kenya        | 3         | 10.71%  |
| UK           | 2         | 7.14%   |
| Switzerland  | 2         | 7.14%   |
| Spain        | 2         | 7.14%   |
| Poland       | 2         | 7.14%   |
| Germany      | 2         | 7.14%   |
| France       | 2         | 7.14%   |
| Venezuela    | 1         | 3.57%   |
| South Africa | 1         | 3.57%   |
| Slovenia     | 1         | 3.57%   |
| Qatar        | 1         | 3.57%   |
| Netherlands  | 1         | 3.57%   |
| Italy        | 1         | 3.57%   |
| Brazil       | 1         | 3.57%   |
| Belarus      | 1         | 3.57%   |
| Argentina    | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Nairobi          | 3         | 10.71%  |
| Zurich           | 2         | 7.14%   |
| Swindon          | 2         | 7.14%   |
| Rostock          | 2         | 7.14%   |
| Wygledy          | 1         | 3.57%   |
| Tellico Plains   | 1         | 3.57%   |
| Someren          | 1         | 3.57%   |
| Posadas          | 1         | 3.57%   |
| Moirans          | 1         | 3.57%   |
| Mogilev          | 1         | 3.57%   |
| Mestre           | 1         | 3.57%   |
| Mesa             | 1         | 3.57%   |
| Londrina         | 1         | 3.57%   |
| Ljubljana        | 1         | 3.57%   |
| Las Vegas        | 1         | 3.57%   |
| Katowice         | 1         | 3.57%   |
| Johannesburg     | 1         | 3.57%   |
| Grand Junction   | 1         | 3.57%   |
| GijГіn         | 1         | 3.57%   |
| Doha             | 1         | 3.57%   |
| Boulogne-sur-Mer | 1         | 3.57%   |
| Barcelona        | 1         | 3.57%   |
| Agua Salada      | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 19.35%  |
| Unknown             | 5         | 5      | 16.13%  |
| Seagate             | 5         | 6      | 16.13%  |
| SanDisk             | 3         | 3      | 9.68%   |
| Samsung Electronics | 3         | 3      | 9.68%   |
| Hitachi             | 3         | 3      | 9.68%   |
| Unknown (CF)        | 1         | 1      | 3.23%   |
| Toshiba             | 1         | 1      | 3.23%   |
| MAXTOR              | 1         | 1      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown NCard  16GB                  | 2         | 6.25%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 3.13%   |
| WDC WD400BD-23JMC0 40GB              | 1         | 3.13%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 3.13%   |
| WDC WD2500BEVT-60A23T0 250GB         | 1         | 3.13%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 3.13%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 3.13%   |
| Unknown USDU1  32GB                  | 1         | 3.13%   |
| Unknown SLD64G  64GB                 | 1         | 3.13%   |
| Unknown 064G38  64GB                 | 1         | 3.13%   |
| Unknown (CF) Card 8GB SSD            | 1         | 3.13%   |
| Toshiba MK8025GAS 80GB               | 1         | 3.13%   |
| Seagate ST9120822AS 120GB            | 1         | 3.13%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 3.13%   |
| Seagate ST3160815AS 160GB            | 1         | 3.13%   |
| Seagate ST3160812AS 160GB            | 1         | 3.13%   |
| Seagate ST310211A 10GB               | 1         | 3.13%   |
| Seagate Backup+ SL 1TB               | 1         | 3.13%   |
| SanDisk SDSSDA120G 120GB             | 1         | 3.13%   |
| SanDisk SDCFX-032G SSD               | 1         | 3.13%   |
| SanDisk SD8SN8U1T001122 1024GB SSD   | 1         | 3.13%   |
| Samsung SSD 850 EVO 250GB            | 1         | 3.13%   |
| Samsung HD081GJ 80GB                 | 1         | 3.13%   |
| Samsung AWMB3R  16GB                 | 1         | 3.13%   |
| MAXTOR 6Y080L0 81GB                  | 1         | 3.13%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 3.13%   |
| Hitachi HTS545032B9A300 320GB        | 1         | 3.13%   |
| Hitachi HTS543225L9SA00 250GB        | 1         | 3.13%   |
| Hitachi DK23CA-20 20GB               | 1         | 3.13%   |
| HGST HTS541075A9E680 752GB           | 1         | 3.13%   |
| Fujitsu MHY2080BH 80GB               | 1         | 3.13%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 25%     |
| Seagate             | 4         | 5      | 25%     |
| Hitachi             | 3         | 3      | 18.75%  |
| Toshiba             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| MAXTOR              | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Unknown (CF)        | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Kingston            | 1         | 1      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 14        | 17     | 50%     |
| MMC     | 6         | 6      | 21.43%  |
| SSD     | 6         | 7      | 21.43%  |
| NVMe    | 1         | 1      | 3.57%   |
| Unknown | 1         | 1      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 19        | 24     | 70.37%  |
| MMC  | 6         | 6      | 22.22%  |
| SAS  | 1         | 1      | 3.7%    |
| NVMe | 1         | 1      | 3.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 21     | 85%     |
| 1.01-2.0   | 1         | 1      | 5%      |
| 4.01-10.0  | 1         | 1      | 5%      |
| 0.51-1.0   | 1         | 1      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 9         | 32.14%  |
| 51-100         | 6         | 21.43%  |
| 21-50          | 4         | 14.29%  |
| 251-500        | 3         | 10.71%  |
| 101-250        | 2         | 7.14%   |
| More than 3000 | 1         | 3.57%   |
| 1001-2000      | 1         | 3.57%   |
| 501-1000       | 1         | 3.57%   |
| Unknown        | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 21        | 75%     |
| 21-50          | 3         | 10.71%  |
| More than 3000 | 1         | 3.57%   |
| 251-500        | 1         | 3.57%   |
| 501-1000       | 1         | 3.57%   |
| Unknown        | 1         | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD400BD-23JMC0 40GB       | 1         | 1      | 11.11%  |
| WDC WD2500BEVT-60A23T0 250GB  | 1         | 1      | 11.11%  |
| Seagate ST9120822AS 120GB     | 1         | 1      | 11.11%  |
| MAXTOR 6Y080L0 81GB           | 1         | 1      | 11.11%  |
| Hitachi HTS545032B9A300 320GB | 1         | 1      | 11.11%  |
| Hitachi HTS543225L9SA00 250GB | 1         | 1      | 11.11%  |
| Hitachi DK23CA-20 20GB        | 1         | 1      | 11.11%  |
| HGST HTS541075A9E680 752GB    | 1         | 1      | 11.11%  |
| Fujitsu MHY2080BH 80GB        | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 33.33%  |
| WDC     | 2         | 2      | 22.22%  |
| Seagate | 1         | 1      | 11.11%  |
| MAXTOR  | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |
| Fujitsu | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 3         | 3      | 33.33%  |
| WDC     | 2         | 2      | 22.22%  |
| Seagate | 1         | 1      | 11.11%  |
| MAXTOR  | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |
| Fujitsu | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 100%    |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 11        | 15     | 40.74%  |
| Malfunc  | 9         | 9      | 33.33%  |
| Detected | 7         | 8      | 25.93%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 14        | 56%     |
| AMD                              | 6         | 24%     |
| Silicon Integrated Systems [SiS] | 3         | 12%     |
| Sandisk                          | 1         | 4%      |
| Nvidia                           | 1         | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 3         | 9.38%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 3         | 9.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 2         | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 6.25%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 1         | 3.13%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]    | 1         | 3.13%   |
| Sandisk WD Blue SN550 NVMe SSD                                               | 1         | 3.13%   |
| Nvidia MCP61 SATA Controller                                                 | 1         | 3.13%   |
| Nvidia MCP61 IDE                                                             | 1         | 3.13%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 3.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                            | 1         | 3.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 3.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 3.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 1         | 3.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 3.13%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 1         | 3.13%   |
| Intel 82801DB (ICH4) IDE Controller                                          | 1         | 3.13%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                | 1         | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 3.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 3.13%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                     | 1         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                             | 1         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 3.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 1         | 3.13%   |
| AMD SB600 Non-Raid-5 SATA                                                    | 1         | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 13        | 48.15%  |
| IDE  | 11        | 40.74%  |
| RAID | 2         | 7.41%   |
| NVMe | 1         | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 71.43%  |
| AMD    | 8         | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU Z3735G @ 1.33GHz               | 3         | 10.71%  |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 7.14%   |
| Intel Pentium M processor 1000MHz             | 1         | 3.57%   |
| Intel Pentium III (Coppermine)                | 1         | 3.57%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 3.57%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 3.57%   |
| Intel Pentium 4 CPU 3.00GHz                   | 1         | 3.57%   |
| Intel Pentium 4 CPU 2.00GHz                   | 1         | 3.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.57%   |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 1         | 3.57%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 1         | 3.57%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 1         | 3.57%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 1         | 3.57%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 3.57%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 1         | 3.57%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 1         | 3.57%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 3.57%   |
| AMD V120 Processor                            | 1         | 3.57%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 1         | 3.57%   |
| AMD E-300 APU with Radeon HD Graphics         | 1         | 3.57%   |
| AMD C-70 APU with Radeon HD Graphics          | 1         | 3.57%   |
| AMD Athlon Processor                          | 1         | 3.57%   |
| AMD Athlon Neo Processor MV-40                | 1         | 3.57%   |
| AMD Athlon II X2 250 Processor                | 1         | 3.57%   |
| AMD A4-9120e RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 4         | 14.29%  |
| Intel Pentium Dual-Core | 2         | 7.14%   |
| Intel Pentium 4         | 2         | 7.14%   |
| Intel Core i5           | 2         | 7.14%   |
| Intel Core i3           | 2         | 7.14%   |
| Intel Core 2 Duo        | 2         | 7.14%   |
| Intel Celeron           | 2         | 7.14%   |
| Other                   | 1         | 3.57%   |
| Intel Pentium M         | 1         | 3.57%   |
| Intel Pentium III       | 1         | 3.57%   |
| Intel Core 2            | 1         | 3.57%   |
| AMD V120                | 1         | 3.57%   |
| AMD Ryzen 7             | 1         | 3.57%   |
| AMD E                   | 1         | 3.57%   |
| AMD C-70                | 1         | 3.57%   |
| AMD Athlon Neo          | 1         | 3.57%   |
| AMD Athlon II X2        | 1         | 3.57%   |
| AMD Athlon              | 1         | 3.57%   |
| AMD A4                  | 1         | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 13        | 46.43%  |
| 4      | 7         | 25%     |
| 1      | 7         | 25%     |
| 8      | 1         | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 75%     |
| 2      | 7         | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24        | 85.71%  |
| 32-bit         | 4         | 14.29%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x30678    | 4         | 14.29%  |
| Unknown    | 3         | 10.71%  |
| 0x6fd      | 2         | 7.14%   |
| 0x206a7    | 2         | 7.14%   |
| 0x1067a    | 2         | 7.14%   |
| 0x010000c8 | 2         | 7.14%   |
| 0xf49      | 1         | 3.57%   |
| 0xf27      | 1         | 3.57%   |
| 0x806c1    | 1         | 3.57%   |
| 0x706a8    | 1         | 3.57%   |
| 0x6f6      | 1         | 3.57%   |
| 0x695      | 1         | 3.57%   |
| 0x68a      | 1         | 3.57%   |
| 0x40651    | 1         | 3.57%   |
| 0x20655    | 1         | 3.57%   |
| 0x0800820d | 1         | 3.57%   |
| 0x06006705 | 1         | 3.57%   |
| 0x05000119 | 1         | 3.57%   |
| 0x0500010d | 1         | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 5         | 17.86%  |
| Core          | 3         | 10.71%  |
| SandyBridge   | 2         | 7.14%   |
| Penryn        | 2         | 7.14%   |
| P6            | 2         | 7.14%   |
| NetBurst      | 2         | 7.14%   |
| K10           | 2         | 7.14%   |
| Bobcat        | 2         | 7.14%   |
| Zen+          | 1         | 3.57%   |
| Westmere      | 1         | 3.57%   |
| TigerLake     | 1         | 3.57%   |
| K8 Hammer     | 1         | 3.57%   |
| K6            | 1         | 3.57%   |
| Haswell       | 1         | 3.57%   |
| Goldmont plus | 1         | 3.57%   |
| Excavator     | 1         | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 15        | 51.72%  |
| AMD                              | 7         | 24.14%  |
| Silicon Integrated Systems [SiS] | 3         | 10.34%  |
| Nvidia                           | 3         | 10.34%  |
| S3 Graphics                      | 1         | 3.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 4         | 13.33%  |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2         | 6.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 2         | 6.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 1         | 3.33%   |
| S3 Graphics 86C270-294 [SavageIX-MV]                                                       | 1         | 3.33%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1         | 3.33%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                              | 1         | 3.33%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1         | 3.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 1         | 3.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 1         | 3.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 1         | 3.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 1         | 3.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 1         | 3.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 1         | 3.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 1         | 3.33%   |
| Intel 82852/855GM Integrated Graphics Device                                               | 1         | 3.33%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 1         | 3.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 1         | 3.33%   |
| AMD Wrestler [Radeon HD 7290]                                                              | 1         | 3.33%   |
| AMD Wrestler [Radeon HD 6310]                                                              | 1         | 3.33%   |
| AMD Topaz PRO [Radeon R5 M255]                                                             | 1         | 3.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 1         | 3.33%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                               | 1         | 3.33%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 1         | 3.33%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 1         | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 13        | 46.43%  |
| 1 x AMD         | 6         | 21.43%  |
| 1 x SiS         | 3         | 10.71%  |
| 1 x Nvidia      | 3         | 10.71%  |
| Other           | 1         | 3.57%   |
| 1 x S3 Graphics | 1         | 3.57%   |
| Intel + AMD     | 1         | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 22        | 78.57%  |
| Unknown     | 4         | 14.29%  |
| Proprietary | 2         | 7.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 60.71%  |
| 0.01-0.5   | 8         | 28.57%  |
| 1.01-2.0   | 3         | 10.71%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 20.83%  |
| Samsung Electronics | 4         | 16.67%  |
| LG Display          | 3         | 12.5%   |
| Chimei Innolux      | 3         | 12.5%   |
| Hewlett-Packard     | 2         | 8.33%   |
| ViewSonic           | 1         | 4.17%   |
| VIE                 | 1         | 4.17%   |
| Orion               | 1         | 4.17%   |
| HannStar            | 1         | 4.17%   |
| Goldstar            | 1         | 4.17%   |
| CPT                 | 1         | 4.17%   |
| BOE                 | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 8.33%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1         | 4.17%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1         | 4.17%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch    | 1         | 4.17%   |
| Samsung Electronics LCD Monitor SAM069B 1920x1080 1020x570mm 46.0-inch  | 1         | 4.17%   |
| Orion ORION ORN120A 1920x540                                            | 1         | 4.17%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch             | 1         | 4.17%   |
| Hewlett-Packard Z24i HWP3100 1920x1200 518x324mm 24.1-inch              | 1         | 4.17%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch               | 1         | 4.17%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                | 1         | 4.17%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1         | 4.17%   |
| CPT LCD Monitor CPT13B1 1280x800 330x210mm 15.4-inch                    | 1         | 4.17%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch        | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch         | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 4.17%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                    | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch          | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO315D 1920x1080 256x144mm 11.6-inch          | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch           | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch           | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 7         | 29.17%  |
| 1920x1080 (FHD)    | 5         | 20.83%  |
| 1600x900 (HD+)     | 5         | 20.83%  |
| 1280x800 (WXGA)    | 2         | 8.33%   |
| 3840x2160 (4K)     | 1         | 4.17%   |
| 2160x1440          | 1         | 4.17%   |
| 1920x540           | 1         | 4.17%   |
| 1920x1200 (WUXGA)  | 1         | 4.17%   |
| 1680x1050 (WSXGA+) | 1         | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 8         | 33.33%  |
| 13      | 2         | 8.33%   |
| 11      | 2         | 8.33%   |
| 46      | 1         | 4.17%   |
| 31      | 1         | 4.17%   |
| 24      | 1         | 4.17%   |
| 23      | 1         | 4.17%   |
| 22      | 1         | 4.17%   |
| 20      | 1         | 4.17%   |
| 19      | 1         | 4.17%   |
| 18      | 1         | 4.17%   |
| 17      | 1         | 4.17%   |
| 14      | 1         | 4.17%   |
| 12      | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 41.67%  |
| 201-300     | 4         | 16.67%  |
| 401-500     | 3         | 12.5%   |
| 501-600     | 2         | 8.33%   |
| 351-400     | 2         | 8.33%   |
| 601-700     | 1         | 4.17%   |
| 1001-1500   | 1         | 4.17%   |
| Unknown     | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 72.73%  |
| 16/10 | 4         | 18.18%  |
| 32/9  | 1         | 4.55%   |
| 3/2   | 1         | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 33.33%  |
| 81-90          | 3         | 12.5%   |
| 51-60          | 2         | 8.33%   |
| 201-250        | 2         | 8.33%   |
| 151-200        | 2         | 8.33%   |
| 61-70          | 1         | 4.17%   |
| 351-500        | 1         | 4.17%   |
| 251-300        | 1         | 4.17%   |
| 141-150        | 1         | 4.17%   |
| 121-130        | 1         | 4.17%   |
| 501-1000       | 1         | 4.17%   |
| Unknown        | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 8         | 33.33%  |
| 51-100  | 7         | 29.17%  |
| 121-160 | 5         | 20.83%  |
| 161-240 | 2         | 8.33%   |
| 1-50    | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 24        | 85.71%  |
| 0     | 2         | 7.14%   |
| 3     | 1         | 3.57%   |
| 2     | 1         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 17        | 39.53%  |
| Qualcomm Atheros                 | 7         | 16.28%  |
| Intel                            | 7         | 16.28%  |
| Silicon Integrated Systems [SiS] | 2         | 4.65%   |
| Samsung Electronics              | 2         | 4.65%   |
| Broadcom                         | 2         | 4.65%   |
| Xiaomi                           | 1         | 2.33%   |
| Motorola PCS                     | 1         | 2.33%   |
| LG Electronics                   | 1         | 2.33%   |
| JMicron Technology               | 1         | 2.33%   |
| IBM                              | 1         | 2.33%   |
| Accton Technology                | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 6         | 13.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 6.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 6.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 2         | 4.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 2         | 4.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 4.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 2.17%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 1         | 2.17%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.17%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 2.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 2.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 2.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.17%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 2.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.17%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 2.17%   |
| Motorola PCS motorola edge                                              | 1         | 2.17%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)                     | 1         | 2.17%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 1         | 2.17%   |
| Intel Wireless 3165                                                     | 1         | 2.17%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 2.17%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 2.17%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 1         | 2.17%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                      | 1         | 2.17%   |
| Intel 82577LC Gigabit Network Connection                                | 1         | 2.17%   |
| IBM Winnipeg PCI-X Host Bridge                                          | 1         | 2.17%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 2.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 2.17%   |
| Accton EN-1216 Ethernet Adapter                                         | 1         | 2.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 7         | 38.89%  |
| Realtek Semiconductor | 5         | 27.78%  |
| Intel                 | 5         | 27.78%  |
| Broadcom              | 1         | 5.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 16.67%  |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 11.11%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 5.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 5.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 5.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 5.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 5.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 5.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 5.56%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 5.56%   |
| Intel Wireless 3165                                                     | 1         | 5.56%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 5.56%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 5.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 5.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 13        | 50%     |
| Silicon Integrated Systems [SiS] | 2         | 7.69%   |
| Samsung Electronics              | 2         | 7.69%   |
| Intel                            | 2         | 7.69%   |
| Xiaomi                           | 1         | 3.85%   |
| Qualcomm Atheros                 | 1         | 3.85%   |
| Motorola PCS                     | 1         | 3.85%   |
| LG Electronics                   | 1         | 3.85%   |
| JMicron Technology               | 1         | 3.85%   |
| Broadcom                         | 1         | 3.85%   |
| Accton Technology                | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6         | 23.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 11.54%  |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 7.69%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2         | 7.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 3.85%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 3.85%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 3.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 3.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.85%   |
| Motorola PCS motorola edge                                        | 1         | 3.85%   |
| LG LM-X420xxx/G2 Android Phone (USB tethering mode)               | 1         | 3.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 3.85%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1         | 3.85%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 3.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.85%   |
| Accton EN-1216 Ethernet Adapter                                   | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 24        | 54.55%  |
| WiFi     | 18        | 40.91%  |
| Modem    | 1         | 2.27%   |
| Unknown  | 1         | 2.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 20        | 52.63%  |
| WiFi     | 18        | 47.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 13        | 46.43%  |
| 1     | 11        | 39.29%  |
| 0     | 4         | 14.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 96.43%  |
| Yes  | 1         | 3.57%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 3         | 30%     |
| Realtek Semiconductor           | 2         | 20%     |
| Intel                           | 2         | 20%     |
| Hewlett-Packard                 | 1         | 10%     |
| Cambridge Silicon Radio         | 1         | 10%     |
| ASUSTek Computer                | 1         | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 30%     |
| Realtek Bluetooth Radio                             | 2         | 20%     |
| Intel Bluetooth wireless interface                  | 1         | 10%     |
| Intel AX200 Bluetooth                               | 1         | 10%     |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 10%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 10%     |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 13        | 52%     |
| AMD                              | 7         | 28%     |
| Silicon Integrated Systems [SiS] | 2         | 8%      |
| Nvidia                           | 2         | 8%      |
| ESS Technology                   | 1         | 4%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 9.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 6.45%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 6.45%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 6.45%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1         | 3.23%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 3.23%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 3.23%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 3.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 3.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 3.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 3.23%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 3.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 3.23%   |
| ESS Technology ES1988 Allegro-1                                            | 1         | 3.23%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 3.23%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 3.23%   |
| AMD RS690 HDMI Audio [Radeon Xpress 1200 Series]                           | 1         | 3.23%   |
| AMD High Definition Audio Controller                                       | 1         | 3.23%   |
| AMD FCH Azalia Controller                                                  | 1         | 3.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 3.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 3.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 13        | 48.15%  |
| Samsung Electronics | 4         | 14.81%  |
| SK Hynix            | 3         | 11.11%  |
| Kingston            | 2         | 7.41%   |
| Unknown (ABCD)      | 1         | 3.7%    |
| Transcend           | 1         | 3.7%    |
| Team                | 1         | 3.7%    |
| Elpida              | 1         | 3.7%    |
| A-DATA Technology   | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 6.9%    |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 2         | 6.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 6.9%    |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 3.45%   |
| Unknown RAM Module 512MB DIMM 400MT/s                            | 1         | 3.45%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 3.45%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 3.45%   |
| Unknown RAM Module 256MB SODIMM SDRAM                            | 1         | 3.45%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 3.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s                    | 1         | 3.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 3.45%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 3.45%   |
| Unknown RAM Module 1GB DIMM DDR3 1333MT/s                        | 1         | 3.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 3.45%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                      | 1         | 3.45%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 3.45%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 3.45%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 800MT/s         | 1         | 3.45%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2400MT/s        | 1         | 3.45%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s         | 1         | 3.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 3.45%   |
| Kingston RAM HP32D4S2S1ME-4 4GB SODIMM DDR4 3200MT/s             | 1         | 3.45%   |
| Kingston RAM 99U5428-041.A01G 4096MB SODIMM DDR3 1067MT/s        | 1         | 3.45%   |
| Elpida RAM EBJ10UE8BDS0-AE-F 1GB SODIMM 1067MT/s                 | 1         | 3.45%   |
| A-DATA RAM AM1U16BC2P1-B1AH 2GB SODIMM DDR3 4199MT/s             | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 10        | 38.46%  |
| SDRAM   | 6         | 23.08%  |
| DDR4    | 3         | 11.54%  |
| DDR2    | 3         | 11.54%  |
| Unknown | 2         | 7.69%   |
| LPDDR4  | 1         | 3.85%   |
| DRAM    | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 17        | 65.38%  |
| DIMM   | 9         | 34.62%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 9         | 32.14%  |
| 4096  | 8         | 28.57%  |
| 1024  | 6         | 21.43%  |
| 512   | 3         | 10.71%  |
| 16384 | 1         | 3.57%   |
| 256   | 1         | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7         | 25.93%  |
| 1333    | 4         | 14.81%  |
| 1334    | 3         | 11.11%  |
| 2400    | 2         | 7.41%   |
| 1600    | 2         | 7.41%   |
| 1067    | 2         | 7.41%   |
| 4199    | 1         | 3.7%    |
| 3600    | 1         | 3.7%    |
| 3200    | 1         | 3.7%    |
| 1066    | 1         | 3.7%    |
| 800     | 1         | 3.7%    |
| 400     | 1         | 3.7%    |
| 266     | 1         | 3.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Brother HL-1110 series | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2         | 22.22%  |
| Suyin                                  | 1         | 11.11%  |
| Silicon Motion                         | 1         | 11.11%  |
| Microdia                               | 1         | 11.11%  |
| IMC Networks                           | 1         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) | 1         | 11.11%  |
| Alcor Micro                            | 1         | 11.11%  |
| Acer                                   | 1         | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 11.11%  |
| Silicon Motion 300k Pixel Camera                            | 1         | 11.11%  |
| Microdia Webcam Vitade AF                                   | 1         | 11.11%  |
| IMC Networks HP TrueVision HD Camera                        | 1         | 11.11%  |
| Chicony Integrated Camera                                   | 1         | 11.11%  |
| Chicony HP HD Webcam                                        | 1         | 11.11%  |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 1         | 11.11%  |
| Alcor Micro USB 2.0 Camera                                  | 1         | 11.11%  |
| Acer USB Camera                                             | 1         | 11.11%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 50%     |
| Validity Sensors VFS451 Fingerprint Reader | 1         | 50%     |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 21        | 75%     |
| 1     | 4         | 14.29%  |
| 2     | 3         | 10.71%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 5         | 50%     |
| Fingerprint reader       | 2         | 20%     |
| Network                  | 1         | 10%     |
| Flash memory             | 1         | 10%     |
| Communication controller | 1         | 10%     |

