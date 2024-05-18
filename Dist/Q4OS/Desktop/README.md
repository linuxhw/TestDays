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

Total: 26

| Vendor        | Model                | Probe                                                      | Date         |
|---------------|----------------------|------------------------------------------------------------|--------------|
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
| Q4OS 4 | 14       | 63.64%  |
| Q4OS 3 | 5        | 22.73%  |
| Q4OS 5 | 3        | 13.64%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Q4OS | 22       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.10.0-19-amd64   | 4        | 17.39%  |
| 6.1.0-21-amd64    | 1        | 4.35%   |
| 6.1.0-21-686-pae  | 1        | 4.35%   |
| 6.1.0-10-amd64    | 1        | 4.35%   |
| 6.0.0-1-amd64     | 1        | 4.35%   |
| 5.10.0-9-686-pae  | 1        | 4.35%   |
| 5.10.0-28-amd64   | 1        | 4.35%   |
| 5.10.0-25-amd64   | 1        | 4.35%   |
| 5.10.0-23-686-pae | 1        | 4.35%   |
| 5.10.0-21-amd64   | 1        | 4.35%   |
| 5.10.0-21-686-pae | 1        | 4.35%   |
| 5.10.0-20-amd64   | 1        | 4.35%   |
| 5.10.0-20-686-pae | 1        | 4.35%   |
| 5.10.0-14-amd64   | 1        | 4.35%   |
| 5.10.0-10-686-pae | 1        | 4.35%   |
| 4.19.0-6-amd64    | 1        | 4.35%   |
| 4.19.0-21-amd64   | 1        | 4.35%   |
| 4.19.0-17-686-pae | 1        | 4.35%   |
| 4.19.0-16-amd64   | 1        | 4.35%   |
| 4.19.0-16-686     | 1        | 4.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 13       | 59.09%  |
| 4.19.0  | 5        | 22.73%  |
| 6.1.0   | 3        | 13.64%  |
| 6.0.0   | 1        | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 13       | 59.09%  |
| 4.19    | 5        | 22.73%  |
| 6.1     | 3        | 13.64%  |
| 6.0     | 1        | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 14       | 63.64%  |
| i686   | 8        | 36.36%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Trinity | 13       | 56.52%  |
| KDE5    | 7        | 30.43%  |
| XFCE    | 1        | 4.35%   |
| LXDE    | 1        | 4.35%   |
| Budgie  | 1        | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 22       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 13       | 59.09%  |
| SDDM    | 7        | 31.82%  |
| LightDM | 2        | 9.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| it_IT | 4        | 18.18%  |
| de_DE | 3        | 13.64%  |
| pt_BR | 2        | 9.09%   |
| es_ES | 2        | 9.09%   |
| en_US | 2        | 9.09%   |
| sk_SK | 1        | 4.55%   |
| hu_HU | 1        | 4.55%   |
| fr_FR | 1        | 4.55%   |
| fr_CA | 1        | 4.55%   |
| es_PE | 1        | 4.55%   |
| es_AR | 1        | 4.55%   |
| en_ZA | 1        | 4.55%   |
| en_IE | 1        | 4.55%   |
| bg_BG | 1        | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 17       | 77.27%  |
| EFI  | 5        | 22.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Desktops | Percent |
|-------|----------|---------|
| Ext4  | 21       | 95.45%  |
| Btrfs | 1        | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 13       | 59.09%  |
| GPT  | 9        | 40.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 90.91%  |
| Yes       | 2        | 9.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 68.18%  |
| Yes       | 7        | 31.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Gigabyte Technology         | 4        | 18.18%  |
| ASRock                      | 4        | 18.18%  |
| MSI                         | 3        | 13.64%  |
| Unknown                     | 2        | 9.09%   |
| VXL                         | 1        | 4.55%   |
| TECO Electric and Machinery | 1        | 4.55%   |
| Medion                      | 1        | 4.55%   |
| Intel                       | 1        | 4.55%   |
| Hewlett-Packard             | 1        | 4.55%   |
| Foxconn                     | 1        | 4.55%   |
| Compaq                      | 1        | 4.55%   |
| BESSTAR Tech                | 1        | 4.55%   |
| ASUSTek Computer            | 1        | 4.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 2        | 9.09%   |
| VXL TC7500D Series                     | 1        | 4.55%   |
| TECO Electric and Machinery FUTRO S400 | 1        | 4.55%   |
| MSI MS-7C56                            | 1        | 4.55%   |
| MSI MS-7597                            | 1        | 4.55%   |
| MSI MS-7592                            | 1        | 4.55%   |
| Medion P961x                           | 1        | 4.55%   |
| Intel D845GRG AAA84341-206             | 1        | 4.55%   |
| HP Compaq Pro 6305 SFF                 | 1        | 4.55%   |
| Gigabyte Z690 GAMING X DDR4            | 1        | 4.55%   |
| Gigabyte XP-M5S661GX                   | 1        | 4.55%   |
| Gigabyte H55M-USB3                     | 1        | 4.55%   |
| Gigabyte AB350-Gaming                  | 1        | 4.55%   |
| Foxconn Pro 3400 Series MT             | 1        | 4.55%   |
| Compaq Evo D510 SFF                    | 1        | 4.55%   |
| BESSTAR Tech UM250                     | 1        | 4.55%   |
| ASUS ET1602                            | 1        | 4.55%   |
| ASRock J3455B-ITX                      | 1        | 4.55%   |
| ASRock H61M-HVS                        | 1        | 4.55%   |
| ASRock G41M-VS3                        | 1        | 4.55%   |
| ASRock B450M Pro4                      | 1        | 4.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 2        | 9.09%   |
| VXL TC7500D                       | 1        | 4.55%   |
| TECO Electric and Machinery FUTRO | 1        | 4.55%   |
| MSI MS-7C56                       | 1        | 4.55%   |
| MSI MS-7597                       | 1        | 4.55%   |
| MSI MS-7592                       | 1        | 4.55%   |
| Medion P961x                      | 1        | 4.55%   |
| Intel D845GRG                     | 1        | 4.55%   |
| HP Compaq                         | 1        | 4.55%   |
| Gigabyte Z690                     | 1        | 4.55%   |
| Gigabyte XP-M5S661GX              | 1        | 4.55%   |
| Gigabyte H55M-USB3                | 1        | 4.55%   |
| Gigabyte AB350-Gaming             | 1        | 4.55%   |
| Foxconn Pro                       | 1        | 4.55%   |
| Compaq Evo                        | 1        | 4.55%   |
| BESSTAR Tech UM250                | 1        | 4.55%   |
| ASUS ET1602                       | 1        | 4.55%   |
| ASRock J3455B-ITX                 | 1        | 4.55%   |
| ASRock H61M-HVS                   | 1        | 4.55%   |
| ASRock G41M-VS3                   | 1        | 4.55%   |
| ASRock B450M                      | 1        | 4.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 3        | 13.64%  |
| 2010 | 3        | 13.64%  |
| 2009 | 3        | 13.64%  |
| 2013 | 2        | 9.09%   |
| 2012 | 2        | 9.09%   |
| 2002 | 2        | 9.09%   |
| 2021 | 1        | 4.55%   |
| 2020 | 1        | 4.55%   |
| 2018 | 1        | 4.55%   |
| 2017 | 1        | 4.55%   |
| 2016 | 1        | 4.55%   |
| 2008 | 1        | 4.55%   |
| 2005 | 1        | 4.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 22       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 22       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 22       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 5        | 22.73%  |
| 3.01-4.0    | 4        | 18.18%  |
| 16.01-24.0  | 3        | 13.64%  |
| 1.01-2.0    | 3        | 13.64%  |
| 64.01-256.0 | 2        | 9.09%   |
| 4.01-8.0    | 1        | 4.55%   |
| 32.01-64.0  | 1        | 4.55%   |
| 8.01-16.0   | 1        | 4.55%   |
| 0.51-1.0    | 1        | 4.55%   |
| 0.01-0.5    | 1        | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 8        | 33.33%  |
| 2.01-3.0  | 5        | 20.83%  |
| 1.01-2.0  | 5        | 20.83%  |
| 4.01-8.0  | 3        | 12.5%   |
| 3.01-4.0  | 1        | 4.17%   |
| 8.01-16.0 | 1        | 4.17%   |
| 0.01-0.5  | 1        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 60.87%  |
| 3      | 6        | 26.09%  |
| 2      | 3        | 13.04%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 56.52%  |
| Yes       | 10       | 43.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 63.64%  |
| Yes       | 8        | 36.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 81.82%  |
| Yes       | 4        | 18.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Italy        | 4        | 18.18%  |
| Germany      | 3        | 13.64%  |
| Brazil       | 2        | 9.09%   |
| Venezuela    | 1        | 4.55%   |
| USA          | 1        | 4.55%   |
| Spain        | 1        | 4.55%   |
| South Africa | 1        | 4.55%   |
| Slovakia     | 1        | 4.55%   |
| Peru         | 1        | 4.55%   |
| Netherlands  | 1        | 4.55%   |
| Hungary      | 1        | 4.55%   |
| France       | 1        | 4.55%   |
| Canada       | 1        | 4.55%   |
| Bulgaria     | 1        | 4.55%   |
| Belgium      | 1        | 4.55%   |
| Argentina    | 1        | 4.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Bologna              | 2        | 9.09%   |
| Toalmas              | 1        | 4.55%   |
| The Hague            | 1        | 4.55%   |
| Solingen             | 1        | 4.55%   |
| Sofia                | 1        | 4.55%   |
| Savona               | 1        | 4.55%   |
| Sao Pedro da Aldeia  | 1        | 4.55%   |
| San Carlos del Zulia | 1        | 4.55%   |
| Rostock              | 1        | 4.55%   |
| Rome                 | 1        | 4.55%   |
| Posadas              | 1        | 4.55%   |
| Osnabrück           | 1        | 4.55%   |
| Montreal             | 1        | 4.55%   |
| Lima                 | 1        | 4.55%   |
| Johannesburg         | 1        | 4.55%   |
| Guarulhos            | 1        | 4.55%   |
| Grand Junction       | 1        | 4.55%   |
| Canet d'En Berenguer | 1        | 4.55%   |
| Brussels             | 1        | 4.55%   |
| Bratislava           | 1        | 4.55%   |
| Boulogne-sur-Mer     | 1        | 4.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 26.67%  |
| Seagate             | 6        | 8      | 20%     |
| SanDisk             | 3        | 5      | 10%     |
| Samsung Electronics | 3        | 4      | 10%     |
| China               | 3        | 4      | 10%     |
| Unknown (CF)        | 1        | 1      | 3.33%   |
| Transcend           | 1        | 1      | 3.33%   |
| Maxtor              | 1        | 1      | 3.33%   |
| Kingston            | 1        | 1      | 3.33%   |
| IBM/Hitachi         | 1        | 2      | 3.33%   |
| Crucial             | 1        | 2      | 3.33%   |
| A-DATA Technology   | 1        | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WDS500G2B0B-00YS70 500GB SSD  | 1        | 2.86%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 2.86%   |
| WDC WD800BD-22MRA1 80GB           | 1        | 2.86%   |
| WDC WD400BD-23JMC0 40GB           | 1        | 2.86%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 2.86%   |
| WDC WD1600AAJS-00L7A0 160GB       | 1        | 2.86%   |
| WDC WD10EFRX-68JCSN0 1TB          | 1        | 2.86%   |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 2.86%   |
| Unknown (CF) CARD 16GB            | 1        | 2.86%   |
| Transcend TS32GHSD370 32GB SSD    | 1        | 2.86%   |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 2.86%   |
| Seagate ST3500413AS 500GB         | 1        | 2.86%   |
| Seagate ST3320820SCE 320GB        | 1        | 2.86%   |
| Seagate ST3160815AS 160GB         | 1        | 2.86%   |
| Seagate ST3160812AS 160GB         | 1        | 2.86%   |
| Seagate ST310211A 10GB            | 1        | 2.86%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 2.86%   |
| SanDisk SSD PLUS 480GB            | 1        | 2.86%   |
| SanDisk SSD PLUS 240GB            | 1        | 2.86%   |
| SanDisk SDSSDA120G 120GB          | 1        | 2.86%   |
| SanDisk Extreme Pro 1TB           | 1        | 2.86%   |
| Samsung SSD 980 PRO 2TB           | 1        | 2.86%   |
| Samsung SSD 860 EVO 250GB         | 1        | 2.86%   |
| Samsung SSD 850 PRO 2TB           | 1        | 2.86%   |
| Samsung HD081GJ 80GB              | 1        | 2.86%   |
| Maxtor 6Y080L0 82GB               | 1        | 2.86%   |
| Kingston OM8P0S3512F-00 512GB SSD | 1        | 2.86%   |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1        | 2.86%   |
| Crucial CT500P2SSD8 500GB         | 1        | 2.86%   |
| Crucial CT120BX500SSD1 120GB      | 1        | 2.86%   |
| China SSD 64GB                    | 1        | 2.86%   |
| China SSD 256GB                   | 1        | 2.86%   |
| China SSD 120GB                   | 1        | 2.86%   |
| China PATA SSD 64GB               | 1        | 2.86%   |
| A-DATA SX8200PNP 512GB            | 1        | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 37.5%   |
| Seagate             | 6        | 8      | 37.5%   |
| Unknown (CF)        | 1        | 1      | 6.25%   |
| Samsung Electronics | 1        | 1      | 6.25%   |
| Maxtor              | 1        | 1      | 6.25%   |
| IBM/Hitachi         | 1        | 2      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| China               | 3        | 4      | 25%     |
| WDC                 | 2        | 2      | 16.67%  |
| SanDisk             | 2        | 4      | 16.67%  |
| Samsung Electronics | 2        | 2      | 16.67%  |
| Transcend           | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Crucial             | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 13       | 19     | 48.15%  |
| SSD  | 11       | 15     | 40.74%  |
| NVMe | 3        | 4      | 11.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 21       | 34     | 87.5%   |
| NVMe | 3        | 4      | 12.5%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 18       | 28     | 75%     |
| 0.51-1.0   | 4        | 4      | 16.67%  |
| 1.01-2.0   | 1        | 1      | 4.17%   |
| 4.01-10.0  | 1        | 1      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 4        | 17.39%  |
| 101-250        | 4        | 17.39%  |
| 51-100         | 4        | 17.39%  |
| 21-50          | 3        | 13.04%  |
| 501-1000       | 3        | 13.04%  |
| 1001-2000      | 2        | 8.7%    |
| 1-20           | 2        | 8.7%    |
| More than 3000 | 1        | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 14       | 60.87%  |
| 21-50          | 2        | 8.7%    |
| 101-250        | 2        | 8.7%    |
| 51-100         | 2        | 8.7%    |
| More than 3000 | 1        | 4.35%   |
| 251-500        | 1        | 4.35%   |
| 501-1000       | 1        | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 14.29%  |
| WDC WD400BD-23JMC0 40GB           | 1        | 1      | 14.29%  |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 1      | 14.29%  |
| WDC WD10EARS-00Y5B1 1TB           | 1        | 1      | 14.29%  |
| Seagate ST3320820SCE 320GB        | 1        | 2      | 14.29%  |
| Maxtor 6Y080L0 82GB               | 1        | 1      | 14.29%  |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1        | 2      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 4        | 4      | 57.14%  |
| Seagate     | 1        | 2      | 14.29%  |
| Maxtor      | 1        | 1      | 14.29%  |
| IBM/Hitachi | 1        | 2      | 14.29%  |

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
| HDD  | 5        | 8      | 83.33%  |
| SSD  | 1        | 1      | 16.67%  |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 18       | 29     | 75%     |
| Malfunc | 6        | 9      | 25%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 13       | 46.43%  |
| AMD                              | 5        | 17.86%  |
| Silicon Integrated Systems [SiS] | 2        | 7.14%   |
| VIA Technologies                 | 1        | 3.57%   |
| SanDisk                          | 1        | 3.57%   |
| Samsung Electronics              | 1        | 3.57%   |
| Nvidia                           | 1        | 3.57%   |
| Micron/Crucial Technology        | 1        | 3.57%   |
| JMicron Technology               | 1        | 3.57%   |
| ASMedia Technology               | 1        | 3.57%   |
| ADATA Technology                 | 1        | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 5        | 13.89%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 3        | 8.33%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 3        | 8.33%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                          | 2        | 5.56%   |
| Intel 82801DB (ICH4) IDE Controller                                           | 2        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 5.56%   |
| VIA VX900 Series Serial-ATA Controller                                        | 1        | 2.78%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]     | 1        | 2.78%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                   | 1        | 2.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 2.78%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 2.78%   |
| Nvidia MCP61 IDE                                                              | 1        | 2.78%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1        | 2.78%   |
| JMicron JMB363 SATA/IDE Controller                                            | 1        | 2.78%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                    | 1        | 2.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1        | 2.78%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 1        | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 1        | 2.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 1        | 2.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1        | 2.78%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                 | 1        | 2.78%   |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 2.78%   |
| AMD 300 Series Chipset SATA Controller                                        | 1        | 2.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1        | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 12       | 42.86%  |
| SATA | 12       | 42.86%  |
| NVMe | 3        | 10.71%  |
| RAID | 1        | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 14       | 63.64%  |
| AMD          | 7        | 31.82%  |
| CentaurHauls | 1        | 4.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 4.55%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 4.55%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1        | 4.55%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1        | 4.55%   |
| Intel Pentium 4 CPU 1.80GHz                     | 1        | 4.55%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 4.55%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 4.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 4.55%   |
| Intel Core 2 Duo CPU T9300 @ 2.50GHz            | 1        | 4.55%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 4.55%   |
| Intel Atom CPU Z530 @ 1.60GHz                   | 1        | 4.55%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1        | 4.55%   |
| Intel Atom CPU 330 @ 1.60GHz                    | 1        | 4.55%   |
| Intel 13th Gen Core i7-13700K                   | 1        | 4.55%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz       | 1        | 4.55%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 4.55%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1        | 4.55%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1        | 4.55%   |
| AMD Athlon Processor                            | 1        | 4.55%   |
| AMD Athlon II X2 250 Processor                  | 1        | 4.55%   |
| AMD Athlon 200GE with Radeon Vega Graphics      | 1        | 4.55%   |
| AMD A4-5300B APU with Radeon HD Graphics        | 1        | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium 4         | 3        | 13.64%  |
| Intel Atom              | 3        | 13.64%  |
| Intel Pentium Dual-Core | 2        | 9.09%   |
| Intel Core i7           | 2        | 9.09%   |
| AMD Ryzen 7             | 2        | 9.09%   |
| AMD Athlon              | 2        | 9.09%   |
| Other                   | 1        | 4.55%   |
| Intel Core i5           | 1        | 4.55%   |
| Intel Core 2 Duo        | 1        | 4.55%   |
| Intel Celeron           | 1        | 4.55%   |
| CentaurHauls VIA Eden   | 1        | 4.55%   |
| AMD Ryzen 5 PRO         | 1        | 4.55%   |
| AMD Athlon II X2        | 1        | 4.55%   |
| AMD A4                  | 1        | 4.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 7        | 31.82%  |
| 1      | 7        | 31.82%  |
| 4      | 5        | 22.73%  |
| 8      | 2        | 9.09%   |
| 16     | 1        | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 11       | 50%     |
| 1      | 11       | 50%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 17       | 77.27%  |
| 32-bit         | 5        | 22.73%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 18.18%  |
| 0x106c2    | 3        | 13.64%  |
| 0x206a7    | 2        | 9.09%   |
| 0x1067a    | 2        | 9.09%   |
| 0x0810100b | 2        | 9.09%   |
| 0xf49      | 1        | 4.55%   |
| 0xf27      | 1        | 4.55%   |
| 0xf12      | 1        | 4.55%   |
| 0xb0671    | 1        | 4.55%   |
| 0x10676    | 1        | 4.55%   |
| 0x08701013 | 1        | 4.55%   |
| 0x0800820d | 1        | 4.55%   |
| 0x0600111f | 1        | 4.55%   |
| 0x010000c8 | 1        | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 3        | 13.64%  |
| NetBurst         | 3        | 13.64%  |
| Bonnell          | 3        | 13.64%  |
| Zen              | 2        | 9.09%   |
| SandyBridge      | 2        | 9.09%   |
| Zen+             | 1        | 4.55%   |
| Zen 2            | 1        | 4.55%   |
| Piledriver       | 1        | 4.55%   |
| Nehalem          | 1        | 4.55%   |
| K6               | 1        | 4.55%   |
| K10              | 1        | 4.55%   |
| Goldmont         | 1        | 4.55%   |
| Alderlake Hybrid | 1        | 4.55%   |
| Unknown          | 1        | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 10       | 43.48%  |
| Nvidia                           | 7        | 30.43%  |
| AMD                              | 3        | 13.04%  |
| Silicon Integrated Systems [SiS] | 2        | 8.7%    |
| VIA Technologies                 | 1        | 4.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2        | 8.33%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 2        | 8.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2        | 8.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2        | 8.33%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1        | 4.17%   |
| Nvidia GT216M [GeForce GT 330M]                                                            | 1        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1        | 4.17%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1        | 4.17%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1        | 4.17%   |
| Nvidia GK107 [GeForce GT 640]                                                              | 1        | 4.17%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1        | 4.17%   |
| Nvidia AD103 [GeForce RTX 4080]                                                            | 1        | 4.17%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 1        | 4.17%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                                 | 1        | 4.17%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 1        | 4.17%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 1        | 4.17%   |
| Intel HD Graphics 500                                                                      | 1        | 4.17%   |
| Intel 82945G/GZ Integrated Graphics Controller                                             | 1        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 1        | 4.17%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                            | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 9        | 40.91%  |
| 1 x Nvidia     | 6        | 27.27%  |
| 1 x AMD        | 3        | 13.64%  |
| 1 x SiS        | 2        | 9.09%   |
| 1 x VIA        | 1        | 4.55%   |
| Intel + Nvidia | 1        | 4.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 14       | 63.64%  |
| Proprietary | 4        | 18.18%  |
| Unknown     | 4        | 18.18%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 59.09%  |
| 0.51-1.0   | 3        | 13.64%  |
| 0.01-0.5   | 3        | 13.64%  |
| 1.01-2.0   | 2        | 9.09%   |
| 3.01-4.0   | 1        | 4.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 16.67%  |
| Philips             | 3        | 16.67%  |
| Dell                | 2        | 11.11%  |
| AOC                 | 2        | 11.11%  |
| ViewSonic           | 1        | 5.56%   |
| VIE                 | 1        | 5.56%   |
| Orion               | 1        | 5.56%   |
| Medion              | 1        | 5.56%   |
| Iiyama              | 1        | 5.56%   |
| Hewlett-Packard     | 1        | 5.56%   |
| Goldstar            | 1        | 5.56%   |
| Acer                | 1        | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3        | 16.67%  |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1        | 5.56%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1        | 5.56%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 1        | 5.56%   |
| Samsung Electronics SMB1630N SAM0630 1360x768 344x194mm 15.5-inch       | 1        | 5.56%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1        | 5.56%   |
| Orion ORION ORN120A 1920x540                                            | 1        | 5.56%   |
| Medion Medion23.6 PC MEDB603 1920x1080 477x268mm 21.5-inch              | 1        | 5.56%   |
| Iiyama PLE2400WS IVM5601 1920x1200                                      | 1        | 5.56%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch               | 1        | 5.56%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1        | 5.56%   |
| Dell DELL2407WFPHC DELA025 1920x1200 520x330mm 24.2-inch                | 1        | 5.56%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                      | 1        | 5.56%   |
| AOC 2460 AOC246A 1920x1080 531x299mm 24.0-inch                          | 1        | 5.56%   |
| AOC 1670W AOC1670 1366x768 344x194mm 15.5-inch                          | 1        | 5.56%   |
| Acer K222HQL ACR03E1 1920x1080 480x270mm 21.7-inch                      | 1        | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 7        | 38.89%  |
| 3840x2160 (4K)     | 2        | 11.11%  |
| 1920x1200 (WUXGA)  | 2        | 11.11%  |
| 1600x900 (HD+)     | 2        | 11.11%  |
| 1366x768 (WXGA)    | 2        | 11.11%  |
| 1920x540           | 1        | 5.56%   |
| 1680x1050 (WSXGA+) | 1        | 5.56%   |
| 1280x1024 (SXGA)   | 1        | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 33.33%  |
| 21      | 2        | 11.11%  |
| 15      | 2        | 11.11%  |
| 31      | 1        | 5.56%   |
| 27      | 1        | 5.56%   |
| 23      | 1        | 5.56%   |
| 22      | 1        | 5.56%   |
| 20      | 1        | 5.56%   |
| 19      | 1        | 5.56%   |
| 17      | 1        | 5.56%   |
| Unknown | 1        | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 38.89%  |
| 401-500     | 5        | 27.78%  |
| 301-350     | 3        | 16.67%  |
| 601-700     | 2        | 11.11%  |
| Unknown     | 1        | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 11       | 64.71%  |
| 16/10 | 4        | 23.53%  |
| 5/4   | 1        | 5.88%   |
| 32/9  | 1        | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 38.89%  |
| 251-300        | 3        | 16.67%  |
| 151-200        | 2        | 11.11%  |
| 101-110        | 2        | 11.11%  |
| 351-500        | 1        | 5.56%   |
| 301-350        | 1        | 5.56%   |
| 141-150        | 1        | 5.56%   |
| Unknown        | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 61.11%  |
| 101-120 | 4        | 22.22%  |
| 121-160 | 2        | 11.11%  |
| Unknown | 1        | 5.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 86.36%  |
| 0     | 2        | 9.09%   |
| 3     | 1        | 4.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 19       | 65.52%  |
| Intel                            | 4        | 13.79%  |
| Silicon Integrated Systems [SiS] | 1        | 3.45%   |
| Ralink                           | 1        | 3.45%   |
| Qualcomm Atheros                 | 1        | 3.45%   |
| IBM                              | 1        | 3.45%   |
| Guillemot                        | 1        | 3.45%   |
| Broadcom Limited                 | 1        | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller    | 12       | 37.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 3        | 9.38%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                 | 1        | 3.13%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 3.13%   |
| Realtek RTL8191SEvB Wireless LAN Controller                               | 1        | 3.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 1        | 3.13%   |
| Realtek RTL8125 2.5GbE Controller                                         | 1        | 3.13%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                | 1        | 3.13%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 3.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1        | 3.13%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 3.13%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                 | 1        | 3.13%   |
| Intel Wi-Fi 6 AX200                                                       | 1        | 3.13%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                        | 1        | 3.13%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                        | 1        | 3.13%   |
| IBM Winnipeg PCI-X Host Bridge                                            | 1        | 3.13%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 3.13%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 3.13%   |

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
| Realtek Semiconductor            | 18       | 78.26%  |
| Intel                            | 2        | 8.7%    |
| Silicon Integrated Systems [SiS] | 1        | 4.35%   |
| Qualcomm Atheros                 | 1        | 4.35%   |
| Broadcom Limited                 | 1        | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 12       | 52.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3        | 13.04%  |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1        | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1        | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 4.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 1        | 4.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 4.35%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                     | 1        | 4.35%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                     | 1        | 4.35%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1        | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 70.97%  |
| WiFi     | 8        | 25.81%  |
| Unknown  | 1        | 3.23%   |

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
| 1     | 15       | 68.18%  |
| 2     | 6        | 27.27%  |
| 3     | 1        | 4.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 20       | 90.91%  |
| Yes  | 2        | 9.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 50%     |
| IMC Networks            | 1        | 25%     |
| Cambridge Silicon Radio | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX210 Bluetooth                               | 1        | 25%     |
| Intel AX200 Bluetooth                               | 1        | 25%     |
| IMC Networks Bluetooth Module                       | 1        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 13       | 44.83%  |
| Nvidia                           | 7        | 24.14%  |
| AMD                              | 5        | 17.24%  |
| VIA Technologies                 | 1        | 3.45%   |
| Silicon Integrated Systems [SiS] | 1        | 3.45%   |
| Shenzhen Rapoo Technology        | 1        | 3.45%   |
| Logitech                         | 1        | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 12.12%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2        | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 6.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 6.06%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 6.06%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 3.03%   |
| VIA Technologies High Definition Audio Controller                          | 1        | 3.03%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 3.03%   |
| Shenzhen Rapoo Technology Wireless Audio                                   | 1        | 3.03%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 3.03%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1        | 3.03%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 3.03%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 3.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 3.03%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 3.03%   |
| Nvidia Audio device                                                        | 1        | 3.03%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1        | 3.03%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1        | 3.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 3.03%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 3.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 3.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 3.03%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 3.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 3.03%   |
| AMD FCH Azalia Controller                                                  | 1        | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 3.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 9        | 39.13%  |
| SK hynix          | 3        | 13.04%  |
| Kingston          | 2        | 8.7%    |
| Transcend         | 1        | 4.35%   |
| Teikon            | 1        | 4.35%   |
| Team              | 1        | 4.35%   |
| S                 | 1        | 4.35%   |
| M                 | 1        | 4.35%   |
| G.Skill           | 1        | 4.35%   |
| Crucial           | 1        | 4.35%   |
| A-DATA Technology | 1        | 4.35%   |
| Unknown           | 1        | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 400MT/s                       | 1        | 4.35%   |
| Unknown RAM Module 512MB DIMM                               | 1        | 4.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 1        | 4.35%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1        | 4.35%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                   | 1        | 4.35%   |
| Unknown RAM Module 2GB DIMM SDRAM                           | 1        | 4.35%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s               | 1        | 4.35%   |
| Unknown RAM Module 2048MB DIMM SDRAM                        | 1        | 4.35%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                    | 1        | 4.35%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s                 | 1        | 4.35%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s        | 1        | 4.35%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s         | 1        | 4.35%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM 1600MT/s             | 1        | 4.35%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s      | 1        | 4.35%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM 1067MT/s           | 1        | 4.35%   |
| S RAM Module 2GB DIMM DDR3 1333MT/s                         | 1        | 4.35%   |
| M RAM Module 1GB DIMM DDR3 1333MT/s                         | 1        | 4.35%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s      | 1        | 4.35%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s     | 1        | 4.35%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 1        | 4.35%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16384MB DIMM DDR4 2667MT/s | 1        | 4.35%   |
| A-DATA RAM Module 4GB DIMM DDR4 2666MT/s                    | 1        | 4.35%   |
| Unknown                                                     | 1        | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 6        | 27.27%  |
| SDRAM   | 5        | 22.73%  |
| DDR4    | 5        | 22.73%  |
| Unknown | 3        | 13.64%  |
| DDR2    | 2        | 9.09%   |
| DDR     | 1        | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 17       | 77.27%  |
| SODIMM | 5        | 22.73%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 8        | 34.78%  |
| 1024  | 4        | 17.39%  |
| 8192  | 3        | 13.04%  |
| 4096  | 3        | 13.04%  |
| 16384 | 2        | 8.7%    |
| 512   | 2        | 8.7%    |
| 32768 | 1        | 4.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4        | 18.18%  |
| 1333    | 3        | 13.64%  |
| 3600    | 2        | 9.09%   |
| 2667    | 2        | 9.09%   |
| 1600    | 2        | 9.09%   |
| 266     | 2        | 9.09%   |
| 2666    | 1        | 4.55%   |
| 1334    | 1        | 4.55%   |
| 1067    | 1        | 4.55%   |
| 1066    | 1        | 4.55%   |
| 800     | 1        | 4.55%   |
| 533     | 1        | 4.55%   |
| 400     | 1        | 4.55%   |

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
| 0     | 17       | 77.27%  |
| 1     | 4        | 18.18%  |
| 2     | 1        | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Graphics card         | 4        | 66.67%  |
| Network               | 1        | 16.67%  |
| Multimedia controller | 1        | 16.67%  |

