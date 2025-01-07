Q4OS - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for Q4OS.

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

Total: 32

| Vendor        | Model                | Probe                                                      | Date         |
|---------------|----------------------|------------------------------------------------------------|--------------|
| Biostar       | H81MHV3              | [4018e1961c](https://linux-hardware.org/?probe=4018e1961c) | Jan 05, 2025 |
| ASRock        | 990FX Extreme4       | [597783d573](https://linux-hardware.org/?probe=597783d573) | Dec 25, 2024 |
| MSI           | B75IA-E33            | [8f135723bc](https://linux-hardware.org/?probe=8f135723bc) | Nov 16, 2024 |
| ASRock        | 990FX Extreme4       | [06e781c23c](https://linux-hardware.org/?probe=06e781c23c) | Nov 02, 2024 |
| ASRock        | 990FX Extreme4       | [b6ac399c00](https://linux-hardware.org/?probe=b6ac399c00) | Oct 13, 2024 |
| ASUSTek       | M3A79-T DELUXE       | [1777d7b016](https://linux-hardware.org/?probe=1777d7b016) | Sep 23, 2024 |
| Medion        | Cattle24 -1M         | [aa19188799](https://linux-hardware.org/?probe=aa19188799) | May 08, 2024 |
| Unknown       | HOTTAB               | [aadecb497e](https://linux-hardware.org/?probe=aadecb497e) | May 07, 2024 |
| Unknown       | Unknown              | [708780fb6c](https://linux-hardware.org/?probe=708780fb6c) | May 05, 2024 |
| Gigabyte      | H55M-USB3            | [9ebfdab7fa](https://linux-hardware.org/?probe=9ebfdab7fa) | Aug 31, 2023 |
| Gigabyte      | Z690 GAMING X DDR4   | [5a968533da](https://linux-hardware.org/?probe=5a968533da) | Jul 28, 2023 |
| Intel         | D845GRG AAA84341-206 | [1863434dc7](https://linux-hardware.org/?probe=1863434dc7) | Jul 01, 2023 |
| Intel         | D845GRG AAA84341-206 | [7734dda00e](https://linux-hardware.org/?probe=7734dda00e) | Jun 30, 2023 |
| ASUSTek       | ET1602               | [637fb8c9ce](https://linux-hardware.org/?probe=637fb8c9ce) | Apr 22, 2023 |
| HP            | 1850                 | [162ec03859](https://linux-hardware.org/?probe=162ec03859) | Apr 02, 2023 |
| HP            | 1850                 | [ccad003ff4](https://linux-hardware.org/?probe=ccad003ff4) | Jan 20, 2023 |
| VXL           | M6V90AI-VL           | [1ad8dbaae1](https://linux-hardware.org/?probe=1ad8dbaae1) | Jan 08, 2023 |
| MSI           | G41M4                | [b651925b13](https://linux-hardware.org/?probe=b651925b13) | Dec 21, 2022 |
| ASRock        | J3455B-ITX           | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| ASRock        | B450M Pro4           | [97e52df467](https://linux-hardware.org/?probe=97e52df467) | Nov 05, 2022 |
| BESSTAR Te... | UM250 V1.0           | [67369107e1](https://linux-hardware.org/?probe=67369107e1) | Nov 05, 2022 |
| ASRock        | J3455B-ITX           | [deda12dd1f](https://linux-hardware.org/?probe=deda12dd1f) | Nov 05, 2022 |
| Gigabyte      | AB350-Gaming-CF      | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| Foxconn       | 2ABF                 | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
| ASRock        | H61M-HVS             | [a9ee15a4d2](https://linux-hardware.org/?probe=a9ee15a4d2) | May 13, 2022 |
| Compaq        | 07E4h                | [535804dbc6](https://linux-hardware.org/?probe=535804dbc6) | Jan 05, 2022 |
| Gigabyte      | XP-M5S661GX          | [c452e6bdf7](https://linux-hardware.org/?probe=c452e6bdf7) | Nov 27, 2021 |
| TECO Elect... | TR53A0               | [4ab721c7f7](https://linux-hardware.org/?probe=4ab721c7f7) | Aug 19, 2021 |
| MSI           | B550-A PRO           | [546cf15192](https://linux-hardware.org/?probe=546cf15192) | Jun 16, 2021 |
| MSI           | GF615M-P33 V2        | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| ASRock        | G41M-VS3             | [75cb33cf5e](https://linux-hardware.org/?probe=75cb33cf5e) | Feb 25, 2021 |
| ASRock        | G41M-VS3             | [6a77858cd4](https://linux-hardware.org/?probe=6a77858cd4) | Feb 25, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Q4OS 4 | 14       | 53.85%  |
| Q4OS 5 | 7        | 26.92%  |
| Q4OS 3 | 5        | 19.23%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Q4OS | 26       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.10.0-19-amd64   | 4        | 14.29%  |
| 6.1.0-28-amd64    | 2        | 7.14%   |
| 6.1.0-27-amd64    | 1        | 3.57%   |
| 6.1.0-26-amd64    | 1        | 3.57%   |
| 6.1.0-25-amd64    | 1        | 3.57%   |
| 6.1.0-21-amd64    | 1        | 3.57%   |
| 6.1.0-21-686-pae  | 1        | 3.57%   |
| 6.1.0-10-amd64    | 1        | 3.57%   |
| 6.0.0-1-amd64     | 1        | 3.57%   |
| 5.10.0-9-686-pae  | 1        | 3.57%   |
| 5.10.0-28-amd64   | 1        | 3.57%   |
| 5.10.0-25-amd64   | 1        | 3.57%   |
| 5.10.0-23-686-pae | 1        | 3.57%   |
| 5.10.0-21-amd64   | 1        | 3.57%   |
| 5.10.0-21-686-pae | 1        | 3.57%   |
| 5.10.0-20-amd64   | 1        | 3.57%   |
| 5.10.0-20-686-pae | 1        | 3.57%   |
| 5.10.0-14-amd64   | 1        | 3.57%   |
| 5.10.0-10-686-pae | 1        | 3.57%   |
| 4.19.0-6-amd64    | 1        | 3.57%   |
| 4.19.0-21-amd64   | 1        | 3.57%   |
| 4.19.0-17-686-pae | 1        | 3.57%   |
| 4.19.0-16-amd64   | 1        | 3.57%   |
| 4.19.0-16-686     | 1        | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 13       | 50%     |
| 6.1.0   | 7        | 26.92%  |
| 4.19.0  | 5        | 19.23%  |
| 6.0.0   | 1        | 3.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 13       | 50%     |
| 6.1     | 7        | 26.92%  |
| 4.19    | 5        | 19.23%  |
| 6.0     | 1        | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 18       | 69.23%  |
| i686   | 8        | 30.77%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Trinity | 16       | 59.26%  |
| KDE5    | 8        | 29.63%  |
| XFCE    | 1        | 3.7%    |
| LXDE    | 1        | 3.7%    |
| Budgie  | 1        | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 26       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 16       | 61.54%  |
| SDDM    | 8        | 30.77%  |
| LightDM | 2        | 7.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| it_IT | 4        | 15.38%  |
| de_DE | 3        | 11.54%  |
| pt_BR | 2        | 7.69%   |
| ja_JP | 2        | 7.69%   |
| es_ES | 2        | 7.69%   |
| en_US | 2        | 7.69%   |
| sk_SK | 1        | 3.85%   |
| pl_PL | 1        | 3.85%   |
| hu_HU | 1        | 3.85%   |
| fr_FR | 1        | 3.85%   |
| fr_CA | 1        | 3.85%   |
| es_PE | 1        | 3.85%   |
| es_AR | 1        | 3.85%   |
| en_ZA | 1        | 3.85%   |
| en_IE | 1        | 3.85%   |
| de_AT | 1        | 3.85%   |
| bg_BG | 1        | 3.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 21       | 80.77%  |
| EFI  | 5        | 19.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 25       | 96.15%  |
| Btrfs | 1        | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 16       | 59.26%  |
| GPT  | 11       | 40.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 85.19%  |
| Yes       | 4        | 14.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 69.23%  |
| Yes       | 8        | 30.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASRock                      | 5        | 19.23%  |
| MSI                         | 4        | 15.38%  |
| Gigabyte Technology         | 4        | 15.38%  |
| ASUSTek Computer            | 2        | 7.69%   |
| Unknown                     | 2        | 7.69%   |
| VXL                         | 1        | 3.85%   |
| TECO Electric and Machinery | 1        | 3.85%   |
| Medion                      | 1        | 3.85%   |
| Intel                       | 1        | 3.85%   |
| Hewlett-Packard             | 1        | 3.85%   |
| Foxconn                     | 1        | 3.85%   |
| Compaq                      | 1        | 3.85%   |
| Biostar                     | 1        | 3.85%   |
| BESSTAR Tech                | 1        | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 2        | 7.69%   |
| VXL TC7500D Series                     | 1        | 3.85%   |
| TECO Electric and Machinery FUTRO S400 | 1        | 3.85%   |
| MSI MS-7C56                            | 1        | 3.85%   |
| MSI MS-7733                            | 1        | 3.85%   |
| MSI MS-7597                            | 1        | 3.85%   |
| MSI MS-7592                            | 1        | 3.85%   |
| Medion P961x                           | 1        | 3.85%   |
| Intel D845GRG AAA84341-206             | 1        | 3.85%   |
| HP Compaq Pro 6305 SFF                 | 1        | 3.85%   |
| Gigabyte Z690 GAMING X DDR4            | 1        | 3.85%   |
| Gigabyte XP-M5S661GX                   | 1        | 3.85%   |
| Gigabyte H55M-USB3                     | 1        | 3.85%   |
| Gigabyte AB350-Gaming                  | 1        | 3.85%   |
| Foxconn Pro 3400 Series MT             | 1        | 3.85%   |
| Compaq Evo D510 SFF                    | 1        | 3.85%   |
| Biostar H81MHV3                        | 1        | 3.85%   |
| BESSTAR Tech UM250                     | 1        | 3.85%   |
| ASUS M3A79-T DELUXE                    | 1        | 3.85%   |
| ASUS ET1602                            | 1        | 3.85%   |
| ASRock J3455B-ITX                      | 1        | 3.85%   |
| ASRock H61M-HVS                        | 1        | 3.85%   |
| ASRock G41M-VS3                        | 1        | 3.85%   |
| ASRock B450M Pro4                      | 1        | 3.85%   |
| ASRock 990FX Extreme4                  | 1        | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 2        | 7.69%   |
| VXL TC7500D                       | 1        | 3.85%   |
| TECO Electric and Machinery FUTRO | 1        | 3.85%   |
| MSI MS-7C56                       | 1        | 3.85%   |
| MSI MS-7733                       | 1        | 3.85%   |
| MSI MS-7597                       | 1        | 3.85%   |
| MSI MS-7592                       | 1        | 3.85%   |
| Medion P961x                      | 1        | 3.85%   |
| Intel D845GRG                     | 1        | 3.85%   |
| HP Compaq                         | 1        | 3.85%   |
| Gigabyte Z690                     | 1        | 3.85%   |
| Gigabyte XP-M5S661GX              | 1        | 3.85%   |
| Gigabyte H55M-USB3                | 1        | 3.85%   |
| Gigabyte AB350-Gaming             | 1        | 3.85%   |
| Foxconn Pro                       | 1        | 3.85%   |
| Compaq Evo                        | 1        | 3.85%   |
| Biostar H81MHV3                   | 1        | 3.85%   |
| BESSTAR Tech UM250                | 1        | 3.85%   |
| ASUS M3A79-T                      | 1        | 3.85%   |
| ASUS ET1602                       | 1        | 3.85%   |
| ASRock J3455B-ITX                 | 1        | 3.85%   |
| ASRock H61M-HVS                   | 1        | 3.85%   |
| ASRock G41M-VS3                   | 1        | 3.85%   |
| ASRock B450M                      | 1        | 3.85%   |
| ASRock 990FX                      | 1        | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 4        | 15.38%  |
| 2013 | 3        | 11.54%  |
| 2010 | 3        | 11.54%  |
| 2009 | 3        | 11.54%  |
| 2012 | 2        | 7.69%   |
| 2008 | 2        | 7.69%   |
| 2002 | 2        | 7.69%   |
| 2021 | 1        | 3.85%   |
| 2020 | 1        | 3.85%   |
| 2018 | 1        | 3.85%   |
| 2017 | 1        | 3.85%   |
| 2016 | 1        | 3.85%   |
| 2014 | 1        | 3.85%   |
| 2005 | 1        | 3.85%   |

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


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 5        | 19.23%  |
| 3.01-4.0    | 4        | 15.38%  |
| 16.01-24.0  | 4        | 15.38%  |
| 1.01-2.0    | 3        | 11.54%  |
| 8.01-16.0   | 3        | 11.54%  |
| 32.01-64.0  | 2        | 7.69%   |
| 64.01-256.0 | 2        | 7.69%   |
| 4.01-8.0    | 1        | 3.85%   |
| 0.51-1.0    | 1        | 3.85%   |
| 0.01-0.5    | 1        | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 9        | 32.14%  |
| 0.51-1.0  | 8        | 28.57%  |
| 2.01-3.0  | 5        | 17.86%  |
| 4.01-8.0  | 3        | 10.71%  |
| 3.01-4.0  | 1        | 3.57%   |
| 8.01-16.0 | 1        | 3.57%   |
| 0.01-0.5  | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 60.71%  |
| 3      | 6        | 21.43%  |
| 2      | 4        | 14.29%  |
| 4      | 1        | 3.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 59.26%  |
| Yes       | 11       | 40.74%  |

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
| No        | 17       | 65.38%  |
| Yes       | 9        | 34.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 81.48%  |
| Yes       | 5        | 18.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Italy        | 4        | 15.38%  |
| Germany      | 3        | 11.54%  |
| Japan        | 2        | 7.69%   |
| Brazil       | 2        | 7.69%   |
| Venezuela    | 1        | 3.85%   |
| USA          | 1        | 3.85%   |
| Spain        | 1        | 3.85%   |
| South Africa | 1        | 3.85%   |
| Slovakia     | 1        | 3.85%   |
| Poland       | 1        | 3.85%   |
| Peru         | 1        | 3.85%   |
| Netherlands  | 1        | 3.85%   |
| Hungary      | 1        | 3.85%   |
| France       | 1        | 3.85%   |
| Canada       | 1        | 3.85%   |
| Bulgaria     | 1        | 3.85%   |
| Belgium      | 1        | 3.85%   |
| Austria      | 1        | 3.85%   |
| Argentina    | 1        | 3.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Tokyo                | 2        | 7.69%   |
| Bologna              | 2        | 7.69%   |
| Vienna               | 1        | 3.85%   |
| Toalmas              | 1        | 3.85%   |
| The Hague            | 1        | 3.85%   |
| Solingen             | 1        | 3.85%   |
| Sofia                | 1        | 3.85%   |
| Savona               | 1        | 3.85%   |
| Sao Pedro da Aldeia  | 1        | 3.85%   |
| San Carlos del Zulia | 1        | 3.85%   |
| Rostock              | 1        | 3.85%   |
| Rome                 | 1        | 3.85%   |
| Posadas              | 1        | 3.85%   |
| Osnabrück           | 1        | 3.85%   |
| Montreal             | 1        | 3.85%   |
| Lima                 | 1        | 3.85%   |
| Katowice             | 1        | 3.85%   |
| Johannesburg         | 1        | 3.85%   |
| Guarulhos            | 1        | 3.85%   |
| Grand Junction       | 1        | 3.85%   |
| Canet d'En Berenguer | 1        | 3.85%   |
| Brussels             | 1        | 3.85%   |
| Bratislava           | 1        | 3.85%   |
| Boulogne-sur-Mer     | 1        | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 10     | 24.32%  |
| Seagate             | 6        | 8      | 16.22%  |
| SanDisk             | 3        | 5      | 8.11%   |
| Samsung Electronics | 3        | 4      | 8.11%   |
| China               | 3        | 4      | 8.11%   |
| SUNEAST             | 2        | 4      | 5.41%   |
| Kingston            | 2        | 3      | 5.41%   |
| Crucial             | 2        | 3      | 5.41%   |
| WDC WDS5            | 1        | 1      | 2.7%    |
| USB                 | 1        | 1      | 2.7%    |
| Unknown (CF)        | 1        | 1      | 2.7%    |
| Transcend           | 1        | 1      | 2.7%    |
| Maxtor              | 1        | 1      | 2.7%    |
| IBM/Hitachi         | 1        | 2      | 2.7%    |
| A-DATA Technology   | 1        | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| SUNEAST SE900 SSD 128GB           | 2        | 4.65%   |
| WDC WDS500G2B0B-00YS70 500GB SSD  | 1        | 2.33%   |
| WDC WDS5 00G2B0C-00PX 500GB SSD   | 1        | 2.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 2.33%   |
| WDC WD800BD-22MRA1 80GB           | 1        | 2.33%   |
| WDC WD400BD-23JMC0 40GB           | 1        | 2.33%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 2.33%   |
| WDC WD1600AAJS-00L7A0 160GB       | 1        | 2.33%   |
| WDC WD10EFRX-68JCSN0 1TB          | 1        | 2.33%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 2.33%   |
| WDC WD10EADS-00L5B1 1TB           | 1        | 2.33%   |
| USB 3.1 320GB                     | 1        | 2.33%   |
| Unknown (CF) Card 4GB             | 1        | 2.33%   |
| Transcend TS32GHSD370 32GB SSD    | 1        | 2.33%   |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 2.33%   |
| Seagate ST3500413AS 500GB         | 1        | 2.33%   |
| Seagate ST3320820SCE 320GB        | 1        | 2.33%   |
| Seagate ST3160815AS 160GB         | 1        | 2.33%   |
| Seagate ST3160812AS 160GB         | 1        | 2.33%   |
| Seagate ST310211A 10GB            | 1        | 2.33%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 2.33%   |
| SanDisk SSD PLUS 480GB            | 1        | 2.33%   |
| SanDisk SSD PLUS 240GB            | 1        | 2.33%   |
| SanDisk SDSSDA120G 120GB          | 1        | 2.33%   |
| SanDisk Extreme Pro 1TB           | 1        | 2.33%   |
| Samsung SSD 980 PRO 2TB           | 1        | 2.33%   |
| Samsung SSD 860 EVO 250GB         | 1        | 2.33%   |
| Samsung SSD 850 PRO 2TB           | 1        | 2.33%   |
| Samsung HD081GJ 80GB              | 1        | 2.33%   |
| Maxtor 6Y080L0 82GB               | 1        | 2.33%   |
| Kingston SA400S37240G 240GB SSD   | 1        | 2.33%   |
| Kingston SA400S37120G 120GB SSD   | 1        | 2.33%   |
| Kingston OM8P0S3512F-00 512GB SSD | 1        | 2.33%   |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1        | 2.33%   |
| Crucial CT500P2SSD8 500GB         | 1        | 2.33%   |
| Crucial CT120BX500SSD1 120GB      | 1        | 2.33%   |
| Crucial CT1024MX200SSD1 1TB       | 1        | 2.33%   |
| China SSD 64GB                    | 1        | 2.33%   |
| China SSD 256GB                   | 1        | 2.33%   |
| China SSD 120GB                   | 1        | 2.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 38.89%  |
| Seagate             | 6        | 8      | 33.33%  |
| USB                 | 1        | 1      | 5.56%   |
| Unknown (CF)        | 1        | 1      | 5.56%   |
| Samsung Electronics | 1        | 1      | 5.56%   |
| Maxtor              | 1        | 1      | 5.56%   |
| IBM/Hitachi         | 1        | 2      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| China               | 3        | 4      | 17.65%  |
| WDC                 | 2        | 2      | 11.76%  |
| SUNEAST             | 2        | 4      | 11.76%  |
| SanDisk             | 2        | 4      | 11.76%  |
| Samsung Electronics | 2        | 2      | 11.76%  |
| Kingston            | 2        | 3      | 11.76%  |
| Crucial             | 2        | 2      | 11.76%  |
| WDC WDS5            | 1        | 1      | 5.88%   |
| Transcend           | 1        | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 15       | 23     | 45.45%  |
| HDD  | 15       | 22     | 45.45%  |
| NVMe | 3        | 4      | 9.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 25       | 43     | 86.21%  |
| NVMe | 3        | 4      | 10.34%  |
| SAS  | 1        | 2      | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 36     | 72.41%  |
| 0.51-1.0   | 6        | 7      | 20.69%  |
| 1.01-2.0   | 1        | 1      | 3.45%   |
| 4.01-10.0  | 1        | 1      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 7        | 25.93%  |
| 51-100         | 5        | 18.52%  |
| 251-500        | 4        | 14.81%  |
| 21-50          | 3        | 11.11%  |
| 501-1000       | 3        | 11.11%  |
| 1001-2000      | 2        | 7.41%   |
| 1-20           | 2        | 7.41%   |
| More than 3000 | 1        | 3.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 17       | 62.96%  |
| 21-50          | 3        | 11.11%  |
| 101-250        | 2        | 7.41%   |
| 51-100         | 2        | 7.41%   |
| More than 3000 | 1        | 3.7%    |
| 251-500        | 1        | 3.7%    |
| 501-1000       | 1        | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 12.5%   |
| WDC WD400BD-23JMC0 40GB           | 1        | 1      | 12.5%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 1      | 12.5%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 12.5%   |
| Seagate ST3320820SCE 320GB        | 1        | 2      | 12.5%   |
| Maxtor 6Y080L0 82GB               | 1        | 1      | 12.5%   |
| Kingston SA400S37240G 240GB SSD   | 1        | 1      | 12.5%   |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1        | 2      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 4        | 4      | 50%     |
| Seagate     | 1        | 2      | 12.5%   |
| Maxtor      | 1        | 1      | 12.5%   |
| Kingston    | 1        | 1      | 12.5%   |
| IBM/Hitachi | 1        | 2      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 3        | 3      | 50%     |
| Seagate     | 1        | 2      | 16.67%  |
| Maxtor      | 1        | 1      | 16.67%  |
| IBM/Hitachi | 1        | 2      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 8      | 71.43%  |
| SSD  | 2        | 2      | 28.57%  |

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
| Works    | 22       | 37     | 73.33%  |
| Malfunc  | 7        | 10     | 23.33%  |
| Detected | 1        | 2      | 3.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 15       | 42.86%  |
| AMD                              | 7        | 20%     |
| VIA Technologies                 | 2        | 5.71%   |
| Silicon Integrated Systems [SiS] | 2        | 5.71%   |
| Marvell Technology Group         | 2        | 5.71%   |
| SanDisk                          | 1        | 2.86%   |
| Samsung Electronics              | 1        | 2.86%   |
| Nvidia                           | 1        | 2.86%   |
| Micron/Crucial Technology        | 1        | 2.86%   |
| JMicron Technology               | 1        | 2.86%   |
| ASMedia Technology               | 1        | 2.86%   |
| ADATA Technology                 | 1        | 2.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 5        | 11.11%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 6.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 6.67%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 2        | 4.44%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 2        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 4.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2        | 4.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 4.44%   |
| VIA VX900 Series Serial-ATA Controller                                         | 1        | 2.22%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 2.22%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]      | 1        | 2.22%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1        | 2.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 2.22%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 2.22%   |
| Nvidia MCP61 IDE                                                               | 1        | 2.22%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 2.22%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                   | 1        | 2.22%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 2.22%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 2.22%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                     | 1        | 2.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 2.22%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 1        | 2.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1        | 2.22%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 1        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 2.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 2.22%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 1        | 2.22%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 2.22%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.22%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 2.22%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 47.06%  |
| IDE  | 14       | 41.18%  |
| NVMe | 3        | 8.82%   |
| RAID | 1        | 2.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 16       | 61.54%  |
| AMD          | 9        | 34.62%  |
| CentaurHauls | 1        | 3.85%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Phenom II X6 1055T Processor                | 2        | 7.69%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 3.85%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 3.85%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1        | 3.85%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1        | 3.85%   |
| Intel Pentium 4 CPU 1.80GHz                     | 1        | 3.85%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 3.85%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 3.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 3.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 3.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 3.85%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz            | 1        | 3.85%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 3.85%   |
| Intel Atom CPU Z530 @ 1.60GHz                   | 1        | 3.85%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1        | 3.85%   |
| Intel Atom CPU 330 @ 1.60GHz                    | 1        | 3.85%   |
| Intel 13th Gen Core i7-13700K                   | 1        | 3.85%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz       | 1        | 3.85%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 3.85%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1        | 3.85%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1        | 3.85%   |
| AMD Athlon Processor                            | 1        | 3.85%   |
| AMD Athlon II X2 250 Processor                  | 1        | 3.85%   |
| AMD Athlon 200GE with Radeon Vega Graphics      | 1        | 3.85%   |
| AMD A4-5300B APU with Radeon HD Graphics        | 1        | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium 4         | 3        | 11.54%  |
| Intel Core i5           | 3        | 11.54%  |
| Intel Atom              | 3        | 11.54%  |
| Intel Pentium Dual-Core | 2        | 7.69%   |
| Intel Core i7           | 2        | 7.69%   |
| AMD Ryzen 7             | 2        | 7.69%   |
| AMD Phenom II X6        | 2        | 7.69%   |
| AMD Athlon              | 2        | 7.69%   |
| Other                   | 1        | 3.85%   |
| Intel Core 2 Duo        | 1        | 3.85%   |
| Intel Celeron           | 1        | 3.85%   |
| CentaurHauls VIA Eden   | 1        | 3.85%   |
| AMD Ryzen 5 PRO         | 1        | 3.85%   |
| AMD Athlon II X2        | 1        | 3.85%   |
| AMD A4                  | 1        | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 26.92%  |
| 2      | 7        | 26.92%  |
| 1      | 7        | 26.92%  |
| 8      | 2        | 7.69%   |
| 6      | 2        | 7.69%   |
| 16     | 1        | 3.85%   |

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
| 1      | 15       | 57.69%  |
| 2      | 11       | 42.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 21       | 80.77%  |
| 32-bit         | 5        | 19.23%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 15.38%  |
| 0x106c2    | 3        | 11.54%  |
| 0x206a7    | 2        | 7.69%   |
| 0x1067a    | 2        | 7.69%   |
| 0x0810100b | 2        | 7.69%   |
| 0x010000dc | 2        | 7.69%   |
| 0xf49      | 1        | 3.85%   |
| 0xf27      | 1        | 3.85%   |
| 0xf12      | 1        | 3.85%   |
| 0xb0671    | 1        | 3.85%   |
| 0x306c3    | 1        | 3.85%   |
| 0x306a9    | 1        | 3.85%   |
| 0x10676    | 1        | 3.85%   |
| 0x08701013 | 1        | 3.85%   |
| 0x0800820d | 1        | 3.85%   |
| 0x0600111f | 1        | 3.85%   |
| 0x010000c8 | 1        | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 3        | 11.54%  |
| NetBurst         | 3        | 11.54%  |
| K10              | 3        | 11.54%  |
| Bonnell          | 3        | 11.54%  |
| Zen              | 2        | 7.69%   |
| SandyBridge      | 2        | 7.69%   |
| Zen+             | 1        | 3.85%   |
| Zen 2            | 1        | 3.85%   |
| Piledriver       | 1        | 3.85%   |
| Nehalem          | 1        | 3.85%   |
| K6               | 1        | 3.85%   |
| IvyBridge        | 1        | 3.85%   |
| Haswell          | 1        | 3.85%   |
| Goldmont         | 1        | 3.85%   |
| Alderlake Hybrid | 1        | 3.85%   |
| Unknown          | 1        | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 11       | 39.29%  |
| Nvidia                           | 9        | 32.14%  |
| AMD                              | 5        | 17.86%  |
| Silicon Integrated Systems [SiS] | 2        | 7.14%   |
| VIA Technologies                 | 1        | 3.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2        | 6.67%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 2        | 6.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2        | 6.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2        | 6.67%   |
| AMD Juniper XT [Radeon HD 5770]                                                            | 2        | 6.67%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1        | 3.33%   |
| Nvidia GT216M [GeForce GT 330M]                                                            | 1        | 3.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1        | 3.33%   |
| Nvidia GP104 [GeForce GTX 1070]                                                            | 1        | 3.33%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1        | 3.33%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1        | 3.33%   |
| Nvidia GK107 [GeForce GT 640]                                                              | 1        | 3.33%   |
| Nvidia GK106 [GeForce GTX 660]                                                             | 1        | 3.33%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1        | 3.33%   |
| Nvidia AD103 [GeForce RTX 4080]                                                            | 1        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller                | 1        | 3.33%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 1        | 3.33%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                                 | 1        | 3.33%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 1        | 3.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 1        | 3.33%   |
| Intel HD Graphics 500                                                                      | 1        | 3.33%   |
| Intel 82945G/GZ Integrated Graphics Controller                                             | 1        | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 1        | 3.33%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                            | 1        | 3.33%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                                 | 1        | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 10       | 37.04%  |
| 1 x Nvidia     | 8        | 29.63%  |
| 1 x AMD        | 5        | 18.52%  |
| 1 x SiS        | 2        | 7.41%   |
| 1 x VIA        | 1        | 3.7%    |
| Intel + Nvidia | 1        | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 18       | 69.23%  |
| Proprietary | 4        | 15.38%  |
| Unknown     | 4        | 15.38%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 14       | 50%     |
| 0.51-1.0   | 5        | 17.86%  |
| 1.01-2.0   | 4        | 14.29%  |
| 0.01-0.5   | 3        | 10.71%  |
| 7.01-8.0   | 1        | 3.57%   |
| 3.01-4.0   | 1        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 4        | 18.18%  |
| Philips             | 3        | 13.64%  |
| NEC Computers       | 2        | 9.09%   |
| Dell                | 2        | 9.09%   |
| AOC                 | 2        | 9.09%   |
| ViewSonic           | 1        | 4.55%   |
| VIE                 | 1        | 4.55%   |
| Orion               | 1        | 4.55%   |
| Medion              | 1        | 4.55%   |
| Iiyama              | 1        | 4.55%   |
| Hewlett-Packard     | 1        | 4.55%   |
| Goldstar            | 1        | 4.55%   |
| Fujitsu Siemens     | 1        | 4.55%   |
| Acer                | 1        | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3        | 13.64%  |
| NEC Computers AS223WM NEC690A 1920x1080 476x267mm 21.5-inch             | 2        | 9.09%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1        | 4.55%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1        | 4.55%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 4.55%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1        | 4.55%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1        | 4.55%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch   | 1        | 4.55%   |
| Orion ORION ORN120A 1920x540                                            | 1        | 4.55%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch              | 1        | 4.55%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1        | 4.55%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch               | 1        | 4.55%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1        | 4.55%   |
| Fujitsu Siemens B22T-7 LED PG FUS082A 1920x1080 477x268mm 21.5-inch     | 1        | 4.55%   |
| Dell DELL2407WFPHC DELA025 1920x1200 520x330mm 24.2-inch                | 1        | 4.55%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                      | 1        | 4.55%   |
| AOC 2460G4 AOC246A 1920x1080 531x299mm 24.0-inch                        | 1        | 4.55%   |
| AOC 1670W AOC1670 1366x768 344x194mm 15.5-inch                          | 1        | 4.55%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                      | 1        | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 11       | 50%     |
| 3840x2160 (4K)     | 2        | 9.09%   |
| 1920x1200 (WUXGA)  | 2        | 9.09%   |
| 1600x900 (HD+)     | 2        | 9.09%   |
| 1366x768 (WXGA)    | 2        | 9.09%   |
| 1920x540           | 1        | 4.55%   |
| 1680x1050 (WSXGA+) | 1        | 4.55%   |
| 1280x1024 (SXGA)   | 1        | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 27.27%  |
| 21      | 5        | 22.73%  |
| 15      | 2        | 9.09%   |
| 54      | 1        | 4.55%   |
| 31      | 1        | 4.55%   |
| 27      | 1        | 4.55%   |
| 23      | 1        | 4.55%   |
| 22      | 1        | 4.55%   |
| 20      | 1        | 4.55%   |
| 19      | 1        | 4.55%   |
| 17      | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 8        | 36.36%  |
| 501-600     | 7        | 31.82%  |
| 301-350     | 3        | 13.64%  |
| 601-700     | 2        | 9.09%   |
| 1001-1500   | 1        | 4.55%   |
| Unknown     | 1        | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 15       | 71.43%  |
| 16/10 | 4        | 19.05%  |
| 5/4   | 1        | 4.76%   |
| 32/9  | 1        | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 36.36%  |
| 151-200        | 4        | 18.18%  |
| 251-300        | 3        | 13.64%  |
| 101-110        | 2        | 9.09%   |
| More than 1000 | 1        | 4.55%   |
| 351-500        | 1        | 4.55%   |
| 301-350        | 1        | 4.55%   |
| 141-150        | 1        | 4.55%   |
| Unknown        | 1        | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 50%     |
| 101-120 | 7        | 31.82%  |
| 121-160 | 2        | 9.09%   |
| 1-50    | 1        | 4.55%   |
| Unknown | 1        | 4.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 23       | 88.46%  |
| 0     | 2        | 7.69%   |
| 3     | 1        | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 21       | 61.76%  |
| Intel                            | 4        | 11.76%  |
| Silicon Integrated Systems [SiS] | 1        | 2.94%   |
| Ralink                           | 1        | 2.94%   |
| Qualcomm Atheros                 | 1        | 2.94%   |
| Marvell Technology Group         | 1        | 2.94%   |
| IBM                              | 1        | 2.94%   |
| Guillemot                        | 1        | 2.94%   |
| Google                           | 1        | 2.94%   |
| Broadcom Limited                 | 1        | 2.94%   |
| Broadcom                         | 1        | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller    | 14       | 37.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 3        | 8.11%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                 | 1        | 2.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 2.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1        | 2.7%    |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 1        | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                         | 1        | 2.7%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                | 1        | 2.7%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 2.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1        | 2.7%    |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 2.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                   | 1        | 2.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                 | 1        | 2.7%    |
| Intel Wi-Fi 6 AX200                                                       | 1        | 2.7%    |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                        | 1        | 2.7%    |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                        | 1        | 2.7%    |
| IBM Winnipeg PCI-X Host Bridge                                            | 1        | 2.7%    |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 2.7%    |
| Google Pixel 6                                                            | 1        | 2.7%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                           | 1        | 2.7%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 2.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 3        | 37.5%   |
| Intel                 | 2        | 25%     |
| Ralink                | 1        | 12.5%   |
| Qualcomm Atheros      | 1        | 12.5%   |
| Guillemot             | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 12.5%   |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1        | 12.5%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 12.5%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 12.5%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 12.5%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                 | 1        | 12.5%   |
| Intel Wi-Fi 6 AX200                                                       | 1        | 12.5%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 20       | 71.43%  |
| Intel                            | 2        | 7.14%   |
| Silicon Integrated Systems [SiS] | 1        | 3.57%   |
| Qualcomm Atheros                 | 1        | 3.57%   |
| Marvell Technology Group         | 1        | 3.57%   |
| Google                           | 1        | 3.57%   |
| Broadcom Limited                 | 1        | 3.57%   |
| Broadcom                         | 1        | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 14       | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 10.71%  |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1        | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 3.57%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1        | 3.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 3.57%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 1        | 3.57%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                     | 1        | 3.57%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                     | 1        | 3.57%   |
| Google Pixel 6                                                         | 1        | 3.57%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                        | 1        | 3.57%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1        | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 74.29%  |
| WiFi     | 8        | 22.86%  |
| Unknown  | 1        | 2.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 20       | 83.33%  |
| WiFi     | 4        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 73.08%  |
| 2     | 6        | 23.08%  |
| 3     | 1        | 3.85%   |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 40%     |
| Cambridge Silicon Radio | 2        | 40%     |
| IMC Networks            | 1        | 20%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 40%     |
| Intel AX210 Bluetooth                               | 1        | 20%     |
| Intel AX200 Bluetooth                               | 1        | 20%     |
| IMC Networks Bluetooth Module                       | 1        | 20%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 15       | 42.86%  |
| Nvidia                           | 9        | 25.71%  |
| AMD                              | 7        | 20%     |
| VIA Technologies                 | 1        | 2.86%   |
| Silicon Integrated Systems [SiS] | 1        | 2.86%   |
| Shenzhen Rapoo Technology        | 1        | 2.86%   |
| Logitech                         | 1        | 2.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 9.3%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2        | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 4.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 4.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 4.65%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                             | 2        | 4.65%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 2        | 4.65%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 2.33%   |
| VIA Technologies High Definition Audio Controller                          | 1        | 2.33%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 2.33%   |
| Shenzhen Rapoo Technology Wireless Audio                                   | 1        | 2.33%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 2.33%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 2.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 2.33%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 2.33%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 2.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 2.33%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 2.33%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1        | 2.33%   |
| Nvidia Audio device                                                        | 1        | 2.33%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.33%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1        | 2.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 2.33%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1        | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 2.33%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 2.33%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 2.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 2.33%   |
| AMD FCH Azalia Controller                                                  | 1        | 2.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 9        | 34.62%  |
| SK hynix          | 4        | 15.38%  |
| Kingston          | 3        | 11.54%  |
| Crucial           | 2        | 7.69%   |
| Transcend         | 1        | 3.85%   |
| Teikon            | 1        | 3.85%   |
| Team              | 1        | 3.85%   |
| S                 | 1        | 3.85%   |
| M                 | 1        | 3.85%   |
| G.Skill           | 1        | 3.85%   |
| A-DATA Technology | 1        | 3.85%   |
| Unknown           | 1        | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1        | 3.85%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 3.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 3.85%   |
| Unknown RAM Module 2GB SODIMM DDR2                       | 1        | 3.85%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                | 1        | 3.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 1        | 3.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s            | 1        | 3.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 3.85%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                 | 1        | 3.85%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s              | 1        | 3.85%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s     | 1        | 3.85%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s      | 1        | 3.85%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s     | 1        | 3.85%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM 1600MT/s          | 1        | 3.85%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s   | 1        | 3.85%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM 1067MT/s        | 1        | 3.85%   |
| S RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 3.85%   |
| M RAM Module 1GB DIMM DDR3 1333MT/s                      | 1        | 3.85%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 1        | 3.85%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s   | 1        | 3.85%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s  | 1        | 3.85%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 1        | 3.85%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s | 1        | 3.85%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s    | 1        | 3.85%   |
| A-DATA RAM Module 4GB DIMM DDR4 2666MT/s                 | 1        | 3.85%   |
| Unknown                                                  | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 9        | 36%     |
| SDRAM   | 5        | 20%     |
| DDR4    | 5        | 20%     |
| Unknown | 3        | 12%     |
| DDR2    | 2        | 8%      |
| DDR     | 1        | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 80%     |
| SODIMM | 5        | 20%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 8        | 30.77%  |
| 8192  | 6        | 23.08%  |
| 1024  | 4        | 15.38%  |
| 4096  | 3        | 11.54%  |
| 16384 | 2        | 7.69%   |
| 512   | 2        | 7.69%   |
| 32768 | 1        | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4        | 16%     |
| 1600    | 3        | 12%     |
| 1333    | 3        | 12%     |
| 3600    | 2        | 8%      |
| 2667    | 2        | 8%      |
| 266     | 2        | 8%      |
| 2666    | 1        | 4%      |
| 1867    | 1        | 4%      |
| 1800    | 1        | 4%      |
| 1334    | 1        | 4%      |
| 1067    | 1        | 4%      |
| 1066    | 1        | 4%      |
| 800     | 1        | 4%      |
| 533     | 1        | 4%      |
| 400     | 1        | 4%      |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Canon MF4100 series    | 1        | 50%     |
| Brother HL-1110 series | 1        | 50%     |

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


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 1        | 25%     |
| KYE Systems (Mouse Systems) | 1        | 25%     |
| eMPIA Technology            | 1        | 25%     |
| Alcor Micro                 | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech HD Webcam C525                        | 1        | 25%     |
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam | 1        | 25%     |
| eMPIA Lenovo EasyCamera                        | 1        | 25%     |
| Alcor Micro USB 2.0 PC Camera                  | 1        | 25%     |

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
| 0     | 21       | 80.77%  |
| 1     | 4        | 15.38%  |
| 2     | 1        | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 4        | 66.67%  |
| Network               | 1        | 16.67%  |
| Multimedia controller | 1        | 16.67%  |

