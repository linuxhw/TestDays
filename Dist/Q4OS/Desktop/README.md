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

Total: 23

| Vendor        | Model                | Probe                                                      | Date         |
|---------------|----------------------|------------------------------------------------------------|--------------|
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
| Q4OS 4 | 13       | 68.42%  |
| Q4OS 3 | 5        | 26.32%  |
| Q4OS 5 | 1        | 5.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Q4OS | 19       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.10.0-19-amd64   | 4        | 20%     |
| 6.1.0-10-amd64    | 1        | 5%      |
| 6.0.0-1-amd64     | 1        | 5%      |
| 5.10.0-9-686-pae  | 1        | 5%      |
| 5.10.0-25-amd64   | 1        | 5%      |
| 5.10.0-23-686-pae | 1        | 5%      |
| 5.10.0-21-amd64   | 1        | 5%      |
| 5.10.0-21-686-pae | 1        | 5%      |
| 5.10.0-20-amd64   | 1        | 5%      |
| 5.10.0-20-686-pae | 1        | 5%      |
| 5.10.0-14-amd64   | 1        | 5%      |
| 5.10.0-10-686-pae | 1        | 5%      |
| 4.19.0-6-amd64    | 1        | 5%      |
| 4.19.0-21-amd64   | 1        | 5%      |
| 4.19.0-17-686-pae | 1        | 5%      |
| 4.19.0-16-amd64   | 1        | 5%      |
| 4.19.0-16-686     | 1        | 5%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 12       | 63.16%  |
| 4.19.0  | 5        | 26.32%  |
| 6.1.0   | 1        | 5.26%   |
| 6.0.0   | 1        | 5.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 12       | 63.16%  |
| 4.19    | 5        | 26.32%  |
| 6.1     | 1        | 5.26%   |
| 6.0     | 1        | 5.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 12       | 63.16%  |
| i686   | 7        | 36.84%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Trinity | 13       | 65%     |
| KDE5    | 5        | 25%     |
| LXDE    | 1        | 5%      |
| Budgie  | 1        | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 19       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 13       | 68.42%  |
| SDDM    | 5        | 26.32%  |
| LightDM | 1        | 5.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| it_IT | 4        | 21.05%  |
| de_DE | 3        | 15.79%  |
| en_US | 2        | 10.53%  |
| sk_SK | 1        | 5.26%   |
| pt_BR | 1        | 5.26%   |
| hu_HU | 1        | 5.26%   |
| fr_FR | 1        | 5.26%   |
| es_PE | 1        | 5.26%   |
| es_ES | 1        | 5.26%   |
| es_AR | 1        | 5.26%   |
| en_ZA | 1        | 5.26%   |
| en_IE | 1        | 5.26%   |
| bg_BG | 1        | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 14       | 73.68%  |
| EFI  | 5        | 26.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 19       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 10       | 52.63%  |
| GPT  | 9        | 47.37%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 94.74%  |
| Yes       | 1        | 5.26%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 63.16%  |
| Yes       | 7        | 36.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Gigabyte Technology         | 4        | 21.05%  |
| ASRock                      | 4        | 21.05%  |
| MSI                         | 3        | 15.79%  |
| VXL                         | 1        | 5.26%   |
| TECO Electric and Machinery | 1        | 5.26%   |
| Intel                       | 1        | 5.26%   |
| Hewlett-Packard             | 1        | 5.26%   |
| Foxconn                     | 1        | 5.26%   |
| Compaq                      | 1        | 5.26%   |
| BESSTAR Tech                | 1        | 5.26%   |
| ASUSTek Computer            | 1        | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| VXL TC7500D Series                     | 1        | 5.26%   |
| TECO Electric and Machinery FUTRO S400 | 1        | 5.26%   |
| MSI MS-7C56                            | 1        | 5.26%   |
| MSI MS-7597                            | 1        | 5.26%   |
| MSI MS-7592                            | 1        | 5.26%   |
| Intel D845GRG AAA84341-206             | 1        | 5.26%   |
| HP Compaq Pro 6305 SFF                 | 1        | 5.26%   |
| Gigabyte Z690 GAMING X DDR4            | 1        | 5.26%   |
| Gigabyte XP-M5S661GX                   | 1        | 5.26%   |
| Gigabyte H55M-USB3                     | 1        | 5.26%   |
| Gigabyte AB350-Gaming                  | 1        | 5.26%   |
| Foxconn Pro 3400 Series MT             | 1        | 5.26%   |
| Compaq Evo D510 SFF                    | 1        | 5.26%   |
| BESSTAR Tech UM250                     | 1        | 5.26%   |
| ASUS ET1602                            | 1        | 5.26%   |
| ASRock J3455B-ITX                      | 1        | 5.26%   |
| ASRock H61M-HVS                        | 1        | 5.26%   |
| ASRock G41M-VS3                        | 1        | 5.26%   |
| ASRock B450M Pro4                      | 1        | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| VXL TC7500D                       | 1        | 5.26%   |
| TECO Electric and Machinery FUTRO | 1        | 5.26%   |
| MSI MS-7C56                       | 1        | 5.26%   |
| MSI MS-7597                       | 1        | 5.26%   |
| MSI MS-7592                       | 1        | 5.26%   |
| Intel D845GRG                     | 1        | 5.26%   |
| HP Compaq                         | 1        | 5.26%   |
| Gigabyte Z690                     | 1        | 5.26%   |
| Gigabyte XP-M5S661GX              | 1        | 5.26%   |
| Gigabyte H55M-USB3                | 1        | 5.26%   |
| Gigabyte AB350-Gaming             | 1        | 5.26%   |
| Foxconn Pro                       | 1        | 5.26%   |
| Compaq Evo                        | 1        | 5.26%   |
| BESSTAR Tech UM250                | 1        | 5.26%   |
| ASUS ET1602                       | 1        | 5.26%   |
| ASRock J3455B-ITX                 | 1        | 5.26%   |
| ASRock H61M-HVS                   | 1        | 5.26%   |
| ASRock G41M-VS3                   | 1        | 5.26%   |
| ASRock B450M                      | 1        | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 3        | 15.79%  |
| 2012 | 2        | 10.53%  |
| 2010 | 2        | 10.53%  |
| 2009 | 2        | 10.53%  |
| 2002 | 2        | 10.53%  |
| 2021 | 1        | 5.26%   |
| 2020 | 1        | 5.26%   |
| 2018 | 1        | 5.26%   |
| 2017 | 1        | 5.26%   |
| 2016 | 1        | 5.26%   |
| 2013 | 1        | 5.26%   |
| 2008 | 1        | 5.26%   |
| 2005 | 1        | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 19       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 19       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 19       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 4        | 21.05%  |
| 3.01-4.0    | 3        | 15.79%  |
| 16.01-24.0  | 3        | 15.79%  |
| 64.01-256.0 | 2        | 10.53%  |
| 1.01-2.0    | 2        | 10.53%  |
| 4.01-8.0    | 1        | 5.26%   |
| 32.01-64.0  | 1        | 5.26%   |
| 8.01-16.0   | 1        | 5.26%   |
| 0.51-1.0    | 1        | 5.26%   |
| 0.01-0.5    | 1        | 5.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 7        | 33.33%  |
| 2.01-3.0  | 5        | 23.81%  |
| 4.01-8.0  | 3        | 14.29%  |
| 1.01-2.0  | 3        | 14.29%  |
| 3.01-4.0  | 1        | 4.76%   |
| 8.01-16.0 | 1        | 4.76%   |
| 0.01-0.5  | 1        | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 60%     |
| 3      | 5        | 25%     |
| 2      | 3        | 15%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 55%     |
| Yes       | 9        | 45%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 12       | 63.16%  |
| Yes       | 7        | 36.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 84.21%  |
| Yes       | 3        | 15.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Italy        | 4        | 21.05%  |
| Germany      | 3        | 15.79%  |
| Venezuela    | 1        | 5.26%   |
| USA          | 1        | 5.26%   |
| South Africa | 1        | 5.26%   |
| Slovakia     | 1        | 5.26%   |
| Peru         | 1        | 5.26%   |
| Netherlands  | 1        | 5.26%   |
| Hungary      | 1        | 5.26%   |
| France       | 1        | 5.26%   |
| Bulgaria     | 1        | 5.26%   |
| Brazil       | 1        | 5.26%   |
| Belgium      | 1        | 5.26%   |
| Argentina    | 1        | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Bologna              | 2        | 10.53%  |
| Toalmas              | 1        | 5.26%   |
| The Hague            | 1        | 5.26%   |
| Solingen             | 1        | 5.26%   |
| Sofia                | 1        | 5.26%   |
| Savona               | 1        | 5.26%   |
| San Carlos del Zulia | 1        | 5.26%   |
| Rostock              | 1        | 5.26%   |
| Rome                 | 1        | 5.26%   |
| Posadas              | 1        | 5.26%   |
| Osnabrück           | 1        | 5.26%   |
| Lima                 | 1        | 5.26%   |
| Johannesburg         | 1        | 5.26%   |
| Guarulhos            | 1        | 5.26%   |
| Grand Junction       | 1        | 5.26%   |
| Brussels             | 1        | 5.26%   |
| Bratislava           | 1        | 5.26%   |
| Boulogne-sur-Mer     | 1        | 5.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 23.08%  |
| Seagate             | 6        | 8      | 23.08%  |
| SanDisk             | 3        | 5      | 11.54%  |
| Samsung Electronics | 3        | 4      | 11.54%  |
| Unknown (CF)        | 1        | 1      | 3.85%   |
| Transcend           | 1        | 1      | 3.85%   |
| Maxtor              | 1        | 1      | 3.85%   |
| Kingston            | 1        | 1      | 3.85%   |
| IBM/Hitachi         | 1        | 2      | 3.85%   |
| Crucial             | 1        | 2      | 3.85%   |
| China               | 1        | 2      | 3.85%   |
| A-DATA Technology   | 1        | 1      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WDS500G2B0B-00YS70 500GB SSD  | 1        | 3.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 3.23%   |
| WDC WD400BD-23JMC0 40GB           | 1        | 3.23%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 3.23%   |
| WDC WD1600AAJS-00L7A0 160GB       | 1        | 3.23%   |
| WDC WD10EFRX-68JCSN0 1TB          | 1        | 3.23%   |
| Unknown (CF) Card 16GB SSD        | 1        | 3.23%   |
| Transcend TS32GHSD370 32GB SSD    | 1        | 3.23%   |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 3.23%   |
| Seagate ST3500413AS 500GB         | 1        | 3.23%   |
| Seagate ST3320820SCE 320GB        | 1        | 3.23%   |
| Seagate ST3160815AS 160GB         | 1        | 3.23%   |
| Seagate ST3160812AS 160GB         | 1        | 3.23%   |
| Seagate ST310211A 10GB            | 1        | 3.23%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 3.23%   |
| SanDisk SSD PLUS 480GB            | 1        | 3.23%   |
| SanDisk SSD PLUS 240GB            | 1        | 3.23%   |
| SanDisk SDSSDA120G 120GB          | 1        | 3.23%   |
| SanDisk Extreme Pro 1TB           | 1        | 3.23%   |
| Samsung SSD 980 PRO 2TB           | 1        | 3.23%   |
| Samsung SSD 860 EVO 250GB         | 1        | 3.23%   |
| Samsung SSD 850 PRO 2TB           | 1        | 3.23%   |
| Samsung HD081GJ 80GB              | 1        | 3.23%   |
| Maxtor 6Y080L0 82GB               | 1        | 3.23%   |
| Kingston OM8P0S3512F-00 512GB SSD | 1        | 3.23%   |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1        | 3.23%   |
| Crucial CT500P2SSD8 500GB         | 1        | 3.23%   |
| Crucial CT120BX500SSD1 120GB      | 1        | 3.23%   |
| China SSD 256GB                   | 1        | 3.23%   |
| China SSD 120GB                   | 1        | 3.23%   |
| A-DATA SX8200PNP 512GB            | 1        | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 8      | 46.15%  |
| WDC                 | 4        | 4      | 30.77%  |
| Samsung Electronics | 1        | 1      | 7.69%   |
| Maxtor              | 1        | 1      | 7.69%   |
| IBM/Hitachi         | 1        | 2      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 18.18%  |
| SanDisk             | 2        | 4      | 18.18%  |
| Samsung Electronics | 2        | 2      | 18.18%  |
| Unknown (CF)        | 1        | 1      | 9.09%   |
| Transcend           | 1        | 1      | 9.09%   |
| Kingston            | 1        | 1      | 9.09%   |
| Crucial             | 1        | 1      | 9.09%   |
| China               | 1        | 2      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 10       | 14     | 43.48%  |
| HDD  | 10       | 16     | 43.48%  |
| NVMe | 3        | 4      | 13.04%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 18       | 30     | 85.71%  |
| NVMe | 3        | 4      | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 25     | 75%     |
| 0.51-1.0   | 3        | 3      | 15%     |
| 1.01-2.0   | 1        | 1      | 5%      |
| 4.01-10.0  | 1        | 1      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 4        | 20%     |
| 101-250        | 3        | 15%     |
| 501-1000       | 3        | 15%     |
| 51-100         | 3        | 15%     |
| 21-50          | 2        | 10%     |
| 1001-2000      | 2        | 10%     |
| 1-20           | 2        | 10%     |
| More than 3000 | 1        | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 11       | 55%     |
| 21-50          | 2        | 10%     |
| 101-250        | 2        | 10%     |
| 51-100         | 2        | 10%     |
| More than 3000 | 1        | 5%      |
| 251-500        | 1        | 5%      |
| 501-1000       | 1        | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 1      | 16.67%  |
| WDC WD400BD-23JMC0 40GB           | 1        | 1      | 16.67%  |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 1      | 16.67%  |
| Seagate ST3320820SCE 320GB        | 1        | 2      | 16.67%  |
| Maxtor 6Y080L0 82GB               | 1        | 1      | 16.67%  |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1        | 2      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 3        | 3      | 50%     |
| Seagate     | 1        | 2      | 16.67%  |
| Maxtor      | 1        | 1      | 16.67%  |
| IBM/Hitachi | 1        | 2      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 2        | 2      | 40%     |
| Seagate     | 1        | 2      | 20%     |
| Maxtor      | 1        | 1      | 20%     |
| IBM/Hitachi | 1        | 2      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 7      | 80%     |
| SSD  | 1        | 1      | 20%     |

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
| Works   | 15       | 26     | 75%     |
| Malfunc | 5        | 8      | 25%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 10       | 40%     |
| AMD                              | 5        | 20%     |
| Silicon Integrated Systems [SiS] | 2        | 8%      |
| VIA Technologies                 | 1        | 4%      |
| SanDisk                          | 1        | 4%      |
| Samsung Electronics              | 1        | 4%      |
| Nvidia                           | 1        | 4%      |
| Micron/Crucial Technology        | 1        | 4%      |
| JMicron Technology               | 1        | 4%      |
| ASMedia Technology               | 1        | 4%      |
| ADATA Technology                 | 1        | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 5        | 15.63%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                          | 2        | 6.25%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 6.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2        | 6.25%   |
| Intel 82801DB (ICH4) IDE Controller                                           | 2        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 6.25%   |
| VIA VX900 Series Serial-ATA Controller                                        | 1        | 3.13%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]     | 1        | 3.13%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1        | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1        | 3.13%   |
| Nvidia MCP61 SATA Controller                                                  | 1        | 3.13%   |
| Nvidia MCP61 IDE                                                              | 1        | 3.13%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1        | 3.13%   |
| JMicron JMB363 SATA/IDE Controller                                            | 1        | 3.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1        | 3.13%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 1        | 3.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 1        | 3.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1        | 3.13%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 3.13%   |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 3.13%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 3.13%   |
| AMD 300 Series Chipset SATA Controller                                        | 1        | 3.13%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1        | 3.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 44%     |
| IDE  | 10       | 40%     |
| NVMe | 3        | 12%     |
| RAID | 1        | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 11       | 57.89%  |
| AMD          | 7        | 36.84%  |
| CentaurHauls | 1        | 5.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 5.26%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 5.26%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1        | 5.26%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1        | 5.26%   |
| Intel Pentium 4 CPU 1.80GHz                     | 1        | 5.26%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 5.26%   |
| Intel Core i7 CPU 860 @ 2.80GHz                 | 1        | 5.26%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 5.26%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 5.26%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1        | 5.26%   |
| Intel 13th Gen Core i7-13700K                   | 1        | 5.26%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz       | 1        | 5.26%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 5.26%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1        | 5.26%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1        | 5.26%   |
| AMD Athlon Processor                            | 1        | 5.26%   |
| AMD Athlon II X2 250 Processor                  | 1        | 5.26%   |
| AMD Athlon 200GE with Radeon Vega Graphics      | 1        | 5.26%   |
| AMD A4-5300B APU with Radeon HD Graphics        | 1        | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium 4         | 3        | 15.79%  |
| Intel Pentium Dual-Core | 2        | 10.53%  |
| Intel Core i7           | 2        | 10.53%  |
| AMD Ryzen 7             | 2        | 10.53%  |
| AMD Athlon              | 2        | 10.53%  |
| Other                   | 1        | 5.26%   |
| Intel Core i5           | 1        | 5.26%   |
| Intel Celeron           | 1        | 5.26%   |
| Intel Atom              | 1        | 5.26%   |
| CentaurHauls VIA Eden   | 1        | 5.26%   |
| AMD Ryzen 5 PRO         | 1        | 5.26%   |
| AMD Athlon II X2        | 1        | 5.26%   |
| AMD A4                  | 1        | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 31.58%  |
| 4      | 5        | 26.32%  |
| 2      | 5        | 26.32%  |
| 8      | 2        | 10.53%  |
| 16     | 1        | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 10       | 52.63%  |
| 1      | 9        | 47.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 15       | 78.95%  |
| 32-bit         | 4        | 21.05%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 21.05%  |
| 0x206a7    | 2        | 10.53%  |
| 0x1067a    | 2        | 10.53%  |
| 0x0810100b | 2        | 10.53%  |
| 0xf49      | 1        | 5.26%   |
| 0xf27      | 1        | 5.26%   |
| 0xf12      | 1        | 5.26%   |
| 0xb0671    | 1        | 5.26%   |
| 0x106c2    | 1        | 5.26%   |
| 0x08701013 | 1        | 5.26%   |
| 0x0800820d | 1        | 5.26%   |
| 0x0600111f | 1        | 5.26%   |
| 0x010000c8 | 1        | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| NetBurst         | 3        | 15.79%  |
| Zen              | 2        | 10.53%  |
| SandyBridge      | 2        | 10.53%  |
| Penryn           | 2        | 10.53%  |
| Zen+             | 1        | 5.26%   |
| Zen 2            | 1        | 5.26%   |
| Piledriver       | 1        | 5.26%   |
| Nehalem          | 1        | 5.26%   |
| K6               | 1        | 5.26%   |
| K10              | 1        | 5.26%   |
| Goldmont         | 1        | 5.26%   |
| Bonnell          | 1        | 5.26%   |
| Alderlake Hybrid | 1        | 5.26%   |
| Unknown          | 1        | 5.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 8        | 40%     |
| Nvidia                           | 6        | 30%     |
| AMD                              | 3        | 15%     |
| Silicon Integrated Systems [SiS] | 2        | 10%     |
| VIA Technologies                 | 1        | 5%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2        | 9.52%   |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 2        | 9.52%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2        | 9.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2        | 9.52%   |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1        | 4.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1        | 4.76%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1        | 4.76%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1        | 4.76%   |
| Nvidia GK107 [GeForce GT 640]                                                              | 1        | 4.76%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1        | 4.76%   |
| Nvidia AD103 [GeForce RTX 4080]                                                            | 1        | 4.76%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                                 | 1        | 4.76%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 1        | 4.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 1        | 4.76%   |
| Intel HD Graphics 500                                                                      | 1        | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 1        | 4.76%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                            | 1        | 4.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 7        | 36.84%  |
| 1 x Nvidia     | 5        | 26.32%  |
| 1 x AMD        | 3        | 15.79%  |
| 1 x SiS        | 2        | 10.53%  |
| 1 x VIA        | 1        | 5.26%   |
| Intel + Nvidia | 1        | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 63.16%  |
| Proprietary | 4        | 21.05%  |
| Unknown     | 3        | 15.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 57.89%  |
| 0.51-1.0   | 3        | 15.79%  |
| 1.01-2.0   | 2        | 10.53%  |
| 0.01-0.5   | 2        | 10.53%  |
| 3.01-4.0   | 1        | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 3        | 18.75%  |
| Philips             | 3        | 18.75%  |
| Dell                | 2        | 12.5%   |
| ViewSonic           | 1        | 6.25%   |
| VIE                 | 1        | 6.25%   |
| Orion               | 1        | 6.25%   |
| Iiyama              | 1        | 6.25%   |
| Hewlett-Packard     | 1        | 6.25%   |
| Goldstar            | 1        | 6.25%   |
| AOC                 | 1        | 6.25%   |
| Acer                | 1        | 6.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3        | 18.75%  |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1        | 6.25%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1        | 6.25%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch       | 1        | 6.25%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1        | 6.25%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1        | 6.25%   |
| Orion ORION ORN120A 1920x540                                            | 1        | 6.25%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1        | 6.25%   |
| Hewlett-Packard 2009 HWP2827 1600x900 443x250mm 20.0-inch               | 1        | 6.25%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1        | 6.25%   |
| Dell DELL2407WFPHC DELA025 1920x1200 520x330mm 24.2-inch                | 1        | 6.25%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                      | 1        | 6.25%   |
| AOC G2460 AOC246A 1920x1080 531x299mm 24.0-inch                         | 1        | 6.25%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                      | 1        | 6.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 37.5%   |
| 3840x2160 (4K)     | 2        | 12.5%   |
| 1920x1200 (WUXGA)  | 2        | 12.5%   |
| 1600x900 (HD+)     | 2        | 12.5%   |
| 1920x540           | 1        | 6.25%   |
| 1680x1050 (WSXGA+) | 1        | 6.25%   |
| 1366x768 (WXGA)    | 1        | 6.25%   |
| 1280x1024 (SXGA)   | 1        | 6.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 6        | 37.5%   |
| 31      | 1        | 6.25%   |
| 27      | 1        | 6.25%   |
| 23      | 1        | 6.25%   |
| 22      | 1        | 6.25%   |
| 21      | 1        | 6.25%   |
| 20      | 1        | 6.25%   |
| 19      | 1        | 6.25%   |
| 17      | 1        | 6.25%   |
| 15      | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 7        | 43.75%  |
| 401-500     | 4        | 25%     |
| 601-700     | 2        | 12.5%   |
| 301-350     | 2        | 12.5%   |
| Unknown     | 1        | 6.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 9        | 60%     |
| 16/10 | 4        | 26.67%  |
| 5/4   | 1        | 6.67%   |
| 32/9  | 1        | 6.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 37.5%   |
| 251-300        | 3        | 18.75%  |
| 151-200        | 2        | 12.5%   |
| 351-500        | 1        | 6.25%   |
| 301-350        | 1        | 6.25%   |
| 141-150        | 1        | 6.25%   |
| 101-110        | 1        | 6.25%   |
| Unknown        | 1        | 6.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 68.75%  |
| 121-160 | 2        | 12.5%   |
| 101-120 | 2        | 12.5%   |
| Unknown | 1        | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 17       | 89.47%  |
| 3     | 1        | 5.26%   |
| 0     | 1        | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 16       | 61.54%  |
| Intel                            | 4        | 15.38%  |
| Silicon Integrated Systems [SiS] | 1        | 3.85%   |
| Ralink                           | 1        | 3.85%   |
| Qualcomm Atheros                 | 1        | 3.85%   |
| IBM                              | 1        | 3.85%   |
| Guillemot                        | 1        | 3.85%   |
| Broadcom Limited                 | 1        | 3.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 10       | 35.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 2        | 7.14%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                 | 1        | 3.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 3.57%   |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 1        | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                         | 1        | 3.57%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                | 1        | 3.57%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 3.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1        | 3.57%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 3.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 1        | 3.57%   |
| Intel Wi-Fi 6 AX200                                                       | 1        | 3.57%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                        | 1        | 3.57%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                        | 1        | 3.57%   |
| IBM Winnipeg PCI-X Host Bridge                                            | 1        | 3.57%   |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 3.57%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 3.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 28.57%  |
| Intel                 | 2        | 28.57%  |
| Ralink                | 1        | 14.29%  |
| Qualcomm Atheros      | 1        | 14.29%  |
| Guillemot             | 1        | 14.29%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 14.29%  |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 14.29%  |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 14.29%  |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 14.29%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                    | 1        | 14.29%  |
| Intel Wi-Fi 6 AX200                                                       | 1        | 14.29%  |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 14.29%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 15       | 75%     |
| Intel                            | 2        | 10%     |
| Silicon Integrated Systems [SiS] | 1        | 5%      |
| Qualcomm Atheros                 | 1        | 5%      |
| Broadcom Limited                 | 1        | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10       | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 10%     |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 5%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 5%      |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 5%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 5%      |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1        | 5%      |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1        | 5%      |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 70.37%  |
| WiFi     | 7        | 25.93%  |
| Unknown  | 1        | 3.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 15       | 83.33%  |
| WiFi     | 3        | 16.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 13       | 68.42%  |
| 2     | 5        | 26.32%  |
| 3     | 1        | 5.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 89.47%  |
| Yes  | 2        | 10.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 66.67%  |
| Cambridge Silicon Radio | 1        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX210 Bluetooth                               | 1        | 33.33%  |
| Intel AX200 Bluetooth                               | 1        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 10       | 40%     |
| Nvidia                           | 6        | 24%     |
| AMD                              | 5        | 20%     |
| VIA Technologies                 | 1        | 4%      |
| Silicon Integrated Systems [SiS] | 1        | 4%      |
| Shenzhen Rapoo Technology        | 1        | 4%      |
| Logitech                         | 1        | 4%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 10.34%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2        | 6.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 6.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 6.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 6.9%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 3.45%   |
| VIA Technologies High Definition Audio Controller                          | 1        | 3.45%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 3.45%   |
| Shenzhen Rapoo Technology Wireless Audio                                   | 1        | 3.45%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 3.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 3.45%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 3.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 3.45%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 3.45%   |
| Nvidia Audio device                                                        | 1        | 3.45%   |
| Logitech PRO X                                                             | 1        | 3.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 3.45%   |
| Intel Alder Lake-S HD Audio Controller                                     | 1        | 3.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 3.45%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 3.45%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 3.45%   |
| AMD FCH Azalia Controller                                                  | 1        | 3.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 7        | 35%     |
| SK hynix          | 2        | 10%     |
| Kingston          | 2        | 10%     |
| Transcend         | 1        | 5%      |
| Teikon            | 1        | 5%      |
| Team              | 1        | 5%      |
| S                 | 1        | 5%      |
| M                 | 1        | 5%      |
| G.Skill           | 1        | 5%      |
| Crucial           | 1        | 5%      |
| A-DATA Technology | 1        | 5%      |
| Unknown           | 1        | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1        | 5%      |
| Unknown RAM Module 512MB DIMM                            | 1        | 5%      |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 1        | 5%      |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                | 1        | 5%      |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s            | 1        | 5%      |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 5%      |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                 | 1        | 5%      |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s              | 1        | 5%      |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s     | 1        | 5%      |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s       | 1        | 5%      |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s     | 1        | 5%      |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s   | 1        | 5%      |
| S RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 5%      |
| M RAM Module 1GB DIMM DDR3 1333MT/s                      | 1        | 5%      |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s   | 1        | 5%      |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s  | 1        | 5%      |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s     | 1        | 5%      |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s | 1        | 5%      |
| A-DATA RAM Module 4GB DIMM DDR4 2666MT/s                 | 1        | 5%      |
| Unknown                                                  | 1        | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 5        | 26.32%  |
| DDR3    | 5        | 26.32%  |
| SDRAM   | 4        | 21.05%  |
| Unknown | 3        | 15.79%  |
| DDR2    | 1        | 5.26%   |
| DDR     | 1        | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 84.21%  |
| SODIMM | 3        | 15.79%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 5        | 25%     |
| 1024  | 4        | 20%     |
| 8192  | 3        | 15%     |
| 4096  | 3        | 15%     |
| 16384 | 2        | 10%     |
| 512   | 2        | 10%     |
| 32768 | 1        | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 3        | 15.79%  |
| 3600    | 2        | 10.53%  |
| 2667    | 2        | 10.53%  |
| 1600    | 2        | 10.53%  |
| 266     | 2        | 10.53%  |
| Unknown | 2        | 10.53%  |
| 2666    | 1        | 5.26%   |
| 1334    | 1        | 5.26%   |
| 1066    | 1        | 5.26%   |
| 800     | 1        | 5.26%   |
| 533     | 1        | 5.26%   |
| 400     | 1        | 5.26%   |

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
| Logitech                    | 1        | 50%     |
| KYE Systems (Mouse Systems) | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech HD Webcam C525                        | 1        | 50%     |
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam | 1        | 50%     |

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
| 0     | 16       | 84.21%  |
| 1     | 2        | 10.53%  |
| 2     | 1        | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 3        | 75%     |
| Network       | 1        | 25%     |

