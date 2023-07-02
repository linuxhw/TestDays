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

Total: 21

| Vendor        | Model                | Probe                                                      | Date         |
|---------------|----------------------|------------------------------------------------------------|--------------|
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
| Q4OS 4 | 12       | 70.59%  |
| Q4OS 3 | 5        | 29.41%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| Q4OS | 17       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.10.0-19-amd64   | 4        | 22.22%  |
| 6.0.0-1-amd64     | 1        | 5.56%   |
| 5.10.0-9-686-pae  | 1        | 5.56%   |
| 5.10.0-23-686-pae | 1        | 5.56%   |
| 5.10.0-21-amd64   | 1        | 5.56%   |
| 5.10.0-21-686-pae | 1        | 5.56%   |
| 5.10.0-20-amd64   | 1        | 5.56%   |
| 5.10.0-20-686-pae | 1        | 5.56%   |
| 5.10.0-14-amd64   | 1        | 5.56%   |
| 5.10.0-10-686-pae | 1        | 5.56%   |
| 4.19.0-6-amd64    | 1        | 5.56%   |
| 4.19.0-21-amd64   | 1        | 5.56%   |
| 4.19.0-17-686-pae | 1        | 5.56%   |
| 4.19.0-16-amd64   | 1        | 5.56%   |
| 4.19.0-16-686     | 1        | 5.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.0  | 11       | 64.71%  |
| 4.19.0  | 5        | 29.41%  |
| 6.0.0   | 1        | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 11       | 64.71%  |
| 4.19    | 5        | 29.41%  |
| 6.0     | 1        | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 10       | 58.82%  |
| i686   | 7        | 41.18%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Trinity | 13       | 72.22%  |
| KDE5    | 3        | 16.67%  |
| LXDE    | 1        | 5.56%   |
| Budgie  | 1        | 5.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 17       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| TDM     | 13       | 76.47%  |
| SDDM    | 3        | 17.65%  |
| LightDM | 1        | 5.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| it_IT | 4        | 23.53%  |
| en_US | 2        | 11.76%  |
| sk_SK | 1        | 5.88%   |
| pt_BR | 1        | 5.88%   |
| hu_HU | 1        | 5.88%   |
| fr_FR | 1        | 5.88%   |
| es_PE | 1        | 5.88%   |
| es_ES | 1        | 5.88%   |
| es_AR | 1        | 5.88%   |
| en_ZA | 1        | 5.88%   |
| en_IE | 1        | 5.88%   |
| de_DE | 1        | 5.88%   |
| bg_BG | 1        | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 13       | 76.47%  |
| EFI  | 4        | 23.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ext4 | 17       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 9        | 52.94%  |
| GPT  | 8        | 47.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 94.12%  |
| Yes       | 1        | 5.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 64.71%  |
| Yes       | 6        | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASRock                      | 4        | 23.53%  |
| MSI                         | 3        | 17.65%  |
| Gigabyte Technology         | 2        | 11.76%  |
| VXL                         | 1        | 5.88%   |
| TECO Electric and Machinery | 1        | 5.88%   |
| Intel                       | 1        | 5.88%   |
| Hewlett-Packard             | 1        | 5.88%   |
| Foxconn                     | 1        | 5.88%   |
| Compaq                      | 1        | 5.88%   |
| BESSTAR Tech                | 1        | 5.88%   |
| ASUSTek Computer            | 1        | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| VXL TC7500D Series                     | 1        | 5.88%   |
| TECO Electric and Machinery FUTRO S400 | 1        | 5.88%   |
| MSI MS-7C56                            | 1        | 5.88%   |
| MSI MS-7597                            | 1        | 5.88%   |
| MSI MS-7592                            | 1        | 5.88%   |
| Intel D845GRG AAA84341-206             | 1        | 5.88%   |
| HP Compaq Pro 6305 SFF                 | 1        | 5.88%   |
| Gigabyte XP-M5S661GX                   | 1        | 5.88%   |
| Gigabyte AB350-Gaming                  | 1        | 5.88%   |
| Foxconn Pro 3400 Series MT             | 1        | 5.88%   |
| Compaq Evo D510 SFF                    | 1        | 5.88%   |
| BESSTAR Tech UM250                     | 1        | 5.88%   |
| ASUS ET1602                            | 1        | 5.88%   |
| ASRock J3455B-ITX                      | 1        | 5.88%   |
| ASRock H61M-HVS                        | 1        | 5.88%   |
| ASRock G41M-VS3                        | 1        | 5.88%   |
| ASRock B450M Pro4                      | 1        | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| VXL TC7500D                       | 1        | 5.88%   |
| TECO Electric and Machinery FUTRO | 1        | 5.88%   |
| MSI MS-7C56                       | 1        | 5.88%   |
| MSI MS-7597                       | 1        | 5.88%   |
| MSI MS-7592                       | 1        | 5.88%   |
| Intel D845GRG                     | 1        | 5.88%   |
| HP Compaq                         | 1        | 5.88%   |
| Gigabyte XP-M5S661GX              | 1        | 5.88%   |
| Gigabyte AB350-Gaming             | 1        | 5.88%   |
| Foxconn Pro                       | 1        | 5.88%   |
| Compaq Evo                        | 1        | 5.88%   |
| BESSTAR Tech UM250                | 1        | 5.88%   |
| ASUS ET1602                       | 1        | 5.88%   |
| ASRock J3455B-ITX                 | 1        | 5.88%   |
| ASRock H61M-HVS                   | 1        | 5.88%   |
| ASRock G41M-VS3                   | 1        | 5.88%   |
| ASRock B450M                      | 1        | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2011 | 3        | 17.65%  |
| 2009 | 2        | 11.76%  |
| 2002 | 2        | 11.76%  |
| 2021 | 1        | 5.88%   |
| 2020 | 1        | 5.88%   |
| 2018 | 1        | 5.88%   |
| 2017 | 1        | 5.88%   |
| 2016 | 1        | 5.88%   |
| 2013 | 1        | 5.88%   |
| 2012 | 1        | 5.88%   |
| 2010 | 1        | 5.88%   |
| 2008 | 1        | 5.88%   |
| 2005 | 1        | 5.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 17       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 17       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 2.01-3.0    | 4        | 23.53%  |
| 3.01-4.0    | 3        | 17.65%  |
| 16.01-24.0  | 2        | 11.76%  |
| 1.01-2.0    | 2        | 11.76%  |
| 4.01-8.0    | 1        | 5.88%   |
| 32.01-64.0  | 1        | 5.88%   |
| 64.01-256.0 | 1        | 5.88%   |
| 8.01-16.0   | 1        | 5.88%   |
| 0.51-1.0    | 1        | 5.88%   |
| 0.01-0.5    | 1        | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 0.51-1.0  | 7        | 36.84%  |
| 2.01-3.0  | 5        | 26.32%  |
| 1.01-2.0  | 3        | 15.79%  |
| 4.01-8.0  | 1        | 5.26%   |
| 3.01-4.0  | 1        | 5.26%   |
| 8.01-16.0 | 1        | 5.26%   |
| 0.01-0.5  | 1        | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 12       | 66.67%  |
| 3      | 3        | 16.67%  |
| 2      | 3        | 16.67%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 61.11%  |
| Yes       | 7        | 38.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 64.71%  |
| Yes       | 6        | 35.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 15       | 88.24%  |
| Yes       | 2        | 11.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Italy        | 4        | 23.53%  |
| Venezuela    | 1        | 5.88%   |
| USA          | 1        | 5.88%   |
| South Africa | 1        | 5.88%   |
| Slovakia     | 1        | 5.88%   |
| Peru         | 1        | 5.88%   |
| Netherlands  | 1        | 5.88%   |
| Hungary      | 1        | 5.88%   |
| Germany      | 1        | 5.88%   |
| France       | 1        | 5.88%   |
| Bulgaria     | 1        | 5.88%   |
| Brazil       | 1        | 5.88%   |
| Belgium      | 1        | 5.88%   |
| Argentina    | 1        | 5.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Bologna              | 2        | 11.76%  |
| Toalmas              | 1        | 5.88%   |
| The Hague            | 1        | 5.88%   |
| Sofia                | 1        | 5.88%   |
| Savona               | 1        | 5.88%   |
| San Carlos del Zulia | 1        | 5.88%   |
| Rostock              | 1        | 5.88%   |
| Rome                 | 1        | 5.88%   |
| Posadas              | 1        | 5.88%   |
| Lima                 | 1        | 5.88%   |
| Johannesburg         | 1        | 5.88%   |
| Guarulhos            | 1        | 5.88%   |
| Grand Junction       | 1        | 5.88%   |
| Brussels             | 1        | 5.88%   |
| Bratislava           | 1        | 5.88%   |
| Boulogne-sur-Mer     | 1        | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 6      | 26.09%  |
| Seagate             | 6        | 8      | 26.09%  |
| Samsung Electronics | 2        | 2      | 8.7%    |
| Unknown (CF)        | 1        | 1      | 4.35%   |
| Transcend           | 1        | 1      | 4.35%   |
| SanDisk             | 1        | 1      | 4.35%   |
| Maxtor              | 1        | 1      | 4.35%   |
| Kingston            | 1        | 1      | 4.35%   |
| IBM/Hitachi         | 1        | 2      | 4.35%   |
| Crucial             | 1        | 2      | 4.35%   |
| China               | 1        | 2      | 4.35%   |
| A-DATA Technology   | 1        | 1      | 4.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| WDC WDS500G2B0B-00YS70 500GB SSD  | 1        | 3.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1        | 3.85%   |
| WDC WD400BD-23JMC0 40GB           | 1        | 3.85%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1        | 3.85%   |
| WDC WD1600AAJS-00L7A0 160GB       | 1        | 3.85%   |
| WDC WD10EFRX-68JCSN0 1TB          | 1        | 3.85%   |
| Unknown (CF) Card 16GB SSD        | 1        | 3.85%   |
| Transcend TS32GHSD370 32GB SSD    | 1        | 3.85%   |
| Seagate ST8000DM004-2CX188 8TB    | 1        | 3.85%   |
| Seagate ST3500413AS 500GB         | 1        | 3.85%   |
| Seagate ST3320820SCE 320GB        | 1        | 3.85%   |
| Seagate ST3160815AS 160GB         | 1        | 3.85%   |
| Seagate ST3160812AS 160GB         | 1        | 3.85%   |
| Seagate ST310211A 10GB            | 1        | 3.85%   |
| Seagate ST1000DM003-1ER162 1TB    | 1        | 3.85%   |
| SanDisk SDSSDA120G 120GB          | 1        | 3.85%   |
| Samsung SSD 860 EVO 250GB         | 1        | 3.85%   |
| Samsung HD081GJ 80GB              | 1        | 3.85%   |
| Maxtor 6Y080L0 82GB               | 1        | 3.85%   |
| Kingston OM8P0S3512F-00 512GB SSD | 1        | 3.85%   |
| IBM/Hitachi IC35L090AVV207-0 80GB | 1        | 3.85%   |
| Crucial CT500P2SSD8 500GB         | 1        | 3.85%   |
| Crucial CT120BX500SSD1 120GB      | 1        | 3.85%   |
| China SSD 256GB                   | 1        | 3.85%   |
| China SSD 120GB                   | 1        | 3.85%   |
| A-DATA SX8200PNP 512GB            | 1        | 3.85%   |

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
| WDC                 | 2        | 2      | 22.22%  |
| Unknown (CF)        | 1        | 1      | 11.11%  |
| Transcend           | 1        | 1      | 11.11%  |
| SanDisk             | 1        | 1      | 11.11%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| Kingston            | 1        | 1      | 11.11%  |
| Crucial             | 1        | 1      | 11.11%  |
| China               | 1        | 2      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 16     | 50%     |
| SSD  | 8        | 10     | 40%     |
| NVMe | 2        | 2      | 10%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 16       | 26     | 88.89%  |
| NVMe | 2        | 2      | 11.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 14       | 22     | 77.78%  |
| 0.51-1.0   | 3        | 3      | 16.67%  |
| 4.01-10.0  | 1        | 1      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 4        | 22.22%  |
| 101-250        | 3        | 16.67%  |
| 51-100         | 3        | 16.67%  |
| 21-50          | 2        | 11.11%  |
| 1001-2000      | 2        | 11.11%  |
| 1-20           | 2        | 11.11%  |
| More than 3000 | 1        | 5.56%   |
| 501-1000       | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 11       | 61.11%  |
| 21-50          | 2        | 11.11%  |
| 101-250        | 2        | 11.11%  |
| More than 3000 | 1        | 5.56%   |
| 501-1000       | 1        | 5.56%   |
| 51-100         | 1        | 5.56%   |

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
| Works   | 13       | 20     | 72.22%  |
| Malfunc | 5        | 8      | 27.78%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 8        | 40%     |
| AMD                              | 5        | 25%     |
| Silicon Integrated Systems [SiS] | 2        | 10%     |
| VIA Technologies                 | 1        | 5%      |
| Nvidia                           | 1        | 5%      |
| Micron/Crucial Technology        | 1        | 5%      |
| ASMedia Technology               | 1        | 5%      |
| ADATA Technology                 | 1        | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 5        | 18.52%  |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                          | 2        | 7.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 7.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2        | 7.41%   |
| Intel 82801DB (ICH4) IDE Controller                                           | 2        | 7.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 2        | 7.41%   |
| VIA VX900 Series Serial-ATA Controller                                        | 1        | 3.7%    |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]     | 1        | 3.7%    |
| Nvidia MCP61 SATA Controller                                                  | 1        | 3.7%    |
| Nvidia MCP61 IDE                                                              | 1        | 3.7%    |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1        | 3.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1        | 3.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 1        | 3.7%    |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 3.7%    |
| AMD 500 Series Chipset SATA Controller                                        | 1        | 3.7%    |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 3.7%    |
| AMD 300 Series Chipset SATA Controller                                        | 1        | 3.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1        | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 9        | 42.86%  |
| SATA | 9        | 42.86%  |
| NVMe | 2        | 9.52%   |
| RAID | 1        | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 9        | 52.94%  |
| AMD          | 7        | 41.18%  |
| CentaurHauls | 1        | 5.88%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz     | 1        | 5.88%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 5.88%   |
| Intel Pentium 4 CPU 3.00GHz                     | 1        | 5.88%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1        | 5.88%   |
| Intel Pentium 4 CPU 1.80GHz                     | 1        | 5.88%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 1        | 5.88%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 5.88%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1        | 5.88%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 1        | 5.88%   |
| CentaurHauls VIA Eden X2 U4200 @ 1.0+ GHz       | 1        | 5.88%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 5.88%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1        | 5.88%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1        | 5.88%   |
| AMD Athlon Processor                            | 1        | 5.88%   |
| AMD Athlon II X2 250 Processor                  | 1        | 5.88%   |
| AMD Athlon 200GE with Radeon Vega Graphics      | 1        | 5.88%   |
| AMD A4-5300B APU with Radeon HD Graphics        | 1        | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium 4         | 3        | 17.65%  |
| Intel Pentium Dual-Core | 2        | 11.76%  |
| AMD Ryzen 7             | 2        | 11.76%  |
| AMD Athlon              | 2        | 11.76%  |
| Intel Core i7           | 1        | 5.88%   |
| Intel Core i5           | 1        | 5.88%   |
| Intel Celeron           | 1        | 5.88%   |
| Intel Atom              | 1        | 5.88%   |
| CentaurHauls VIA Eden   | 1        | 5.88%   |
| AMD Ryzen 5 PRO         | 1        | 5.88%   |
| AMD Athlon II X2        | 1        | 5.88%   |
| AMD A4                  | 1        | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 6        | 35.29%  |
| 2      | 5        | 29.41%  |
| 4      | 4        | 23.53%  |
| 8      | 2        | 11.76%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 52.94%  |
| 2      | 8        | 47.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 13       | 76.47%  |
| 32-bit         | 4        | 23.53%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3        | 17.65%  |
| 0x206a7    | 2        | 11.76%  |
| 0x1067a    | 2        | 11.76%  |
| 0x0810100b | 2        | 11.76%  |
| 0xf49      | 1        | 5.88%   |
| 0xf27      | 1        | 5.88%   |
| 0xf12      | 1        | 5.88%   |
| 0x106c2    | 1        | 5.88%   |
| 0x08701013 | 1        | 5.88%   |
| 0x0800820d | 1        | 5.88%   |
| 0x0600111f | 1        | 5.88%   |
| 0x010000c8 | 1        | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| NetBurst    | 3        | 17.65%  |
| Zen         | 2        | 11.76%  |
| SandyBridge | 2        | 11.76%  |
| Penryn      | 2        | 11.76%  |
| Zen+        | 1        | 5.88%   |
| Zen 2       | 1        | 5.88%   |
| Piledriver  | 1        | 5.88%   |
| K6          | 1        | 5.88%   |
| K10         | 1        | 5.88%   |
| Goldmont    | 1        | 5.88%   |
| Bonnell     | 1        | 5.88%   |
| Unknown     | 1        | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 7        | 41.18%  |
| Nvidia                           | 4        | 23.53%  |
| AMD                              | 3        | 17.65%  |
| Silicon Integrated Systems [SiS] | 2        | 11.76%  |
| VIA Technologies                 | 1        | 5.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------|----------|---------|
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2        | 11.11%  |
| Intel 82845G/GL[Brookdale-G]/GE Chipset Integrated Graphics Device                         | 2        | 11.11%  |
| Intel 4 Series Chipset Integrated Graphics Controller                                      | 2        | 11.11%  |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2        | 11.11%  |
| VIA Technologies VX900 Graphics [Chrome9 HD]                                               | 1        | 5.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                         | 1        | 5.56%   |
| Nvidia GM206 [GeForce GTX 960]                                                             | 1        | 5.56%   |
| Nvidia GK208B [GeForce GT 710]                                                             | 1        | 5.56%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                    | 1        | 5.56%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 1        | 5.56%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 1        | 5.56%   |
| Intel HD Graphics 500                                                                      | 1        | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 1        | 5.56%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                            | 1        | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 7        | 41.18%  |
| 1 x Nvidia | 4        | 23.53%  |
| 1 x AMD    | 3        | 17.65%  |
| 1 x SiS    | 2        | 11.76%  |
| 1 x VIA    | 1        | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 70.59%  |
| Unknown     | 3        | 17.65%  |
| Proprietary | 2        | 11.76%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 10       | 58.82%  |
| 1.01-2.0   | 2        | 11.76%  |
| 0.51-1.0   | 2        | 11.76%  |
| 0.01-0.5   | 2        | 11.76%  |
| 3.01-4.0   | 1        | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Philips             | 3        | 21.43%  |
| Samsung Electronics | 2        | 14.29%  |
| ViewSonic           | 1        | 7.14%   |
| VIE                 | 1        | 7.14%   |
| Orion               | 1        | 7.14%   |
| Iiyama              | 1        | 7.14%   |
| Hewlett-Packard     | 1        | 7.14%   |
| Goldstar            | 1        | 7.14%   |
| Dell                | 1        | 7.14%   |
| AOC                 | 1        | 7.14%   |
| Acer                | 1        | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 3        | 21.43%  |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch               | 1        | 7.14%   |
| VIE S20W VIE2080 1600x900 440x250mm 19.9-inch                           | 1        | 7.14%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1        | 7.14%   |
| Samsung Electronics S24B20/S24B30 SAM09ED 1920x1080 521x293mm 23.5-inch | 1        | 7.14%   |
| Orion ORION ORN120A 1920x540                                            | 1        | 7.14%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                  | 1        | 7.14%   |
| Hewlett-Packard 2009 HWP2827 1600x900 440x250mm 19.9-inch               | 1        | 7.14%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                    | 1        | 7.14%   |
| Dell 1704FPV DEL3015 1280x1024 338x270mm 17.0-inch                      | 1        | 7.14%   |
| AOC 2460G5 AOC246A 1920x1080 531x299mm 24.0-inch                        | 1        | 7.14%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                      | 1        | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 42.86%  |
| 1600x900 (HD+)     | 2        | 14.29%  |
| 3840x2160 (4K)     | 1        | 7.14%   |
| 1920x540           | 1        | 7.14%   |
| 1920x1200 (WUXGA)  | 1        | 7.14%   |
| 1680x1050 (WSXGA+) | 1        | 7.14%   |
| 1366x768 (WXGA)    | 1        | 7.14%   |
| 1280x1024 (SXGA)   | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 5        | 35.71%  |
| 31      | 1        | 7.14%   |
| 23      | 1        | 7.14%   |
| 22      | 1        | 7.14%   |
| 21      | 1        | 7.14%   |
| 20      | 1        | 7.14%   |
| 19      | 1        | 7.14%   |
| 17      | 1        | 7.14%   |
| 15      | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 42.86%  |
| 401-500     | 4        | 28.57%  |
| 301-350     | 2        | 14.29%  |
| 601-700     | 1        | 7.14%   |
| Unknown     | 1        | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 8        | 61.54%  |
| 16/10 | 3        | 23.08%  |
| 5/4   | 1        | 7.69%   |
| 32/9  | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 6        | 42.86%  |
| 251-300        | 2        | 14.29%  |
| 151-200        | 2        | 14.29%  |
| 351-500        | 1        | 7.14%   |
| 141-150        | 1        | 7.14%   |
| 101-110        | 1        | 7.14%   |
| Unknown        | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 71.43%  |
| 101-120 | 2        | 14.29%  |
| 121-160 | 1        | 7.14%   |
| Unknown | 1        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 88.24%  |
| 3     | 1        | 5.88%   |
| 0     | 1        | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 14       | 60.87%  |
| Intel                            | 3        | 13.04%  |
| Silicon Integrated Systems [SiS] | 1        | 4.35%   |
| Ralink                           | 1        | 4.35%   |
| Qualcomm Atheros                 | 1        | 4.35%   |
| IBM                              | 1        | 4.35%   |
| Guillemot                        | 1        | 4.35%   |
| Broadcom Limited                 | 1        | 4.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 9        | 36%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 2        | 8%      |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                 | 1        | 4%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 4%      |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 4%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 1        | 4%      |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                | 1        | 4%      |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 4%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                | 1        | 4%      |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 4%      |
| Intel Wi-Fi 6 AX200                                                       | 1        | 4%      |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                        | 1        | 4%      |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                        | 1        | 4%      |
| IBM Winnipeg PCI-X Host Bridge                                            | 1        | 4%      |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 4%      |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 4%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 2        | 33.33%  |
| Ralink                | 1        | 16.67%  |
| Qualcomm Atheros      | 1        | 16.67%  |
| Intel                 | 1        | 16.67%  |
| Guillemot             | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CU 802.11n WLAN Adapter                                    | 1        | 16.67%  |
| Realtek RTL8188EE Wireless Network Adapter                                | 1        | 16.67%  |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                 | 1        | 16.67%  |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]       | 1        | 16.67%  |
| Intel Wi-Fi 6 AX200                                                       | 1        | 16.67%  |
| Guillemot Hercules HWNUp-150 802.11n Wireless N Pico [Realtek RTL8188CUS] | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 13       | 72.22%  |
| Intel                            | 2        | 11.11%  |
| Silicon Integrated Systems [SiS] | 1        | 5.56%   |
| Qualcomm Atheros                 | 1        | 5.56%   |
| Broadcom Limited                 | 1        | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 11.11%  |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1        | 5.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 5.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 5.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 5.56%   |
| Intel 82801DB PRO/100 VM (LOM) Ethernet Controller                | 1        | 5.56%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                | 1        | 5.56%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1        | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 70.83%  |
| WiFi     | 6        | 25%     |
| Unknown  | 1        | 4.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 13       | 81.25%  |
| WiFi     | 3        | 18.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 12       | 70.59%  |
| 2     | 4        | 23.53%  |
| 3     | 1        | 5.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 88.24%  |
| Yes  | 2        | 11.76%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 1        | 50%     |
| Cambridge Silicon Radio | 1        | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 1        | 50%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 8        | 42.11%  |
| AMD                              | 5        | 26.32%  |
| Nvidia                           | 4        | 21.05%  |
| VIA Technologies                 | 1        | 5.26%   |
| Silicon Integrated Systems [SiS] | 1        | 5.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 13.04%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2        | 8.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 8.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 8.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 8.7%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1        | 4.35%   |
| VIA Technologies High Definition Audio Controller                          | 1        | 4.35%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1        | 4.35%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 4.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 4.35%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 4.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1        | 4.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1        | 4.35%   |
| AMD Trinity HDMI Audio Controller                                          | 1        | 4.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1        | 4.35%   |
| AMD FCH Azalia Controller                                                  | 1        | 4.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 4.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 6        | 33.33%  |
| SK hynix          | 2        | 11.11%  |
| Kingston          | 2        | 11.11%  |
| Transcend         | 1        | 5.56%   |
| Teikon            | 1        | 5.56%   |
| Team              | 1        | 5.56%   |
| S                 | 1        | 5.56%   |
| M                 | 1        | 5.56%   |
| Crucial           | 1        | 5.56%   |
| A-DATA Technology | 1        | 5.56%   |
| Unknown           | 1        | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 512MB DIMM 400MT/s                    | 1        | 5.56%   |
| Unknown RAM Module 512MB DIMM                            | 1        | 5.56%   |
| Unknown RAM Module 2GB DIMM SDRAM 800MT/s                | 1        | 5.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM 1066MT/s            | 1        | 5.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 1        | 5.56%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                 | 1        | 5.56%   |
| Transcend RAM Module 1GB DIMM SDRAM 266MT/s              | 1        | 5.56%   |
| Teikon RAM TMT41GU6AFR8C-PBHJ 8GB DIMM DDR3 1333MT/s     | 1        | 5.56%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s       | 1        | 5.56%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM 1600MT/s          | 1        | 5.56%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM 1334MT/s     | 1        | 5.56%   |
| S RAM Module 2GB DIMM DDR3 1333MT/s                      | 1        | 5.56%   |
| M RAM Module 1GB DIMM DDR3 1333MT/s                      | 1        | 5.56%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s   | 1        | 5.56%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s  | 1        | 5.56%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s | 1        | 5.56%   |
| A-DATA RAM Module 4GB DIMM DDR4 2666MT/s                 | 1        | 5.56%   |
| Unknown                                                  | 1        | 5.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 5        | 29.41%  |
| SDRAM   | 4        | 23.53%  |
| DDR4    | 4        | 23.53%  |
| Unknown | 2        | 11.76%  |
| DDR2    | 1        | 5.88%   |
| DDR     | 1        | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 14       | 82.35%  |
| SODIMM | 3        | 17.65%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 5        | 27.78%  |
| 1024  | 4        | 22.22%  |
| 8192  | 3        | 16.67%  |
| 4096  | 2        | 11.11%  |
| 512   | 2        | 11.11%  |
| 32768 | 1        | 5.56%   |
| 16384 | 1        | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 2        | 11.76%  |
| 1600    | 2        | 11.76%  |
| 1333    | 2        | 11.76%  |
| 266     | 2        | 11.76%  |
| Unknown | 2        | 11.76%  |
| 3600    | 1        | 5.88%   |
| 2666    | 1        | 5.88%   |
| 1334    | 1        | 5.88%   |
| 1066    | 1        | 5.88%   |
| 800     | 1        | 5.88%   |
| 533     | 1        | 5.88%   |
| 400     | 1        | 5.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Brother HL-1110 series | 1        | 100%    |

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
| KYE Systems (Mouse Systems) | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| KYE Systems (Mouse Systems) ASUS USB2.0 Webcam | 1        | 100%    |

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
| 0     | 14       | 82.35%  |
| 1     | 2        | 11.76%  |
| 2     | 1        | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 3        | 75%     |
| Network       | 1        | 25%     |

