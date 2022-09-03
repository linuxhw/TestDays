Kaisen - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Kaisen.

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

Total: 24

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek | N76VB                       | [e488dd7682](https://linux-hardware.org/?probe=e488dd7682) | Aug 27, 2022 |
| MSI     | Vector GP76 12UH            | [7ac84940b8](https://linux-hardware.org/?probe=7ac84940b8) | Jul 24, 2022 |
| Acer    | Aspire One 753              | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| Dell    | Latitude 3540               | [e4dd2ae509](https://linux-hardware.org/?probe=e4dd2ae509) | May 06, 2022 |
| Dell    | Inspiron 14 5401            | [d357bf876a](https://linux-hardware.org/?probe=d357bf876a) | Apr 02, 2022 |
| Lenovo  | IdeaPad 5 15ARE05 81YQ      | [c9d1e057c3](https://linux-hardware.org/?probe=c9d1e057c3) | Jan 03, 2022 |
| HP      | EliteBook 840 G1            | [f04d152dbc](https://linux-hardware.org/?probe=f04d152dbc) | Dec 10, 2021 |
| Lenovo  | ThinkPad T520 4243E51       | [dbee2d500a](https://linux-hardware.org/?probe=dbee2d500a) | Nov 29, 2021 |
| HP      | Pavilion 15                 | [15e92e7427](https://linux-hardware.org/?probe=15e92e7427) | Sep 25, 2021 |
| Lenovo  | ThinkPad T450 20BV003SMS    | [352b2b53b8](https://linux-hardware.org/?probe=352b2b53b8) | Sep 14, 2021 |
| Lenovo  | ThinkPad T430 23427YU       | [9f7679f7be](https://linux-hardware.org/?probe=9f7679f7be) | Sep 06, 2021 |
| Lenovo  | ThinkPad T15 Gen 2i 20W4... | [7a6c5d1f4b](https://linux-hardware.org/?probe=7a6c5d1f4b) | Aug 16, 2021 |
| HP      | ProBook 650 G2              | [8bd4184e25](https://linux-hardware.org/?probe=8bd4184e25) | Aug 15, 2021 |
| HP      | ProBook 650 G2              | [9fef85ae5d](https://linux-hardware.org/?probe=9fef85ae5d) | Aug 11, 2021 |
| HP      | Pavilion g7                 | [2aba1a12dd](https://linux-hardware.org/?probe=2aba1a12dd) | Jul 21, 2021 |
| HP      | Pavilion g7                 | [a4cbb8c698](https://linux-hardware.org/?probe=a4cbb8c698) | Jul 15, 2021 |
| HP      | Pavilion g7                 | [3a0142c412](https://linux-hardware.org/?probe=3a0142c412) | Jul 13, 2021 |
| HP      | EliteBook 840 G2            | [aa55e0ae92](https://linux-hardware.org/?probe=aa55e0ae92) | Apr 30, 2021 |
| HP      | ProBook 645 G1              | [501e0bc33f](https://linux-hardware.org/?probe=501e0bc33f) | Apr 15, 2021 |
| Lenovo  | Legion Y530-15ICH 81FV      | [871a04a1f3](https://linux-hardware.org/?probe=871a04a1f3) | Oct 27, 2020 |
| HP      | EliteBook 840 G2            | [d3d44f4bdf](https://linux-hardware.org/?probe=d3d44f4bdf) | Oct 22, 2020 |
| Lenovo  | Legion Y530-15ICH 81FV      | [51bd9bdbb7](https://linux-hardware.org/?probe=51bd9bdbb7) | Oct 08, 2020 |
| Apple   | MacBookPro9,2               | [65031a9a6d](https://linux-hardware.org/?probe=65031a9a6d) | May 29, 2020 |
| Apple   | MacBookPro9,2               | [7ad10f260f](https://linux-hardware.org/?probe=7ad10f260f) | May 18, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Kaisen 1.8 | 7         | 36.84%  |
| Kaisen 2.0 | 4         | 21.05%  |
| Kaisen 1.4 | 3         | 15.79%  |
| Kaisen 2.1 | 2         | 10.53%  |
| Kaisen 1.6 | 2         | 10.53%  |
| Kaisen 1.0 | 1         | 5.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Kaisen | 19        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.10.0-kaisen5-amd64 | 5         | 26.32%  |
| 5.15.0-kaisen1-amd64 | 4         | 21.05%  |
| 5.8.0-kaisen2-amd64  | 2         | 10.53%  |
| 5.17.0-kaisen1-amd64 | 2         | 10.53%  |
| 5.10.0-kaisen3-amd64 | 2         | 10.53%  |
| 5.9.0-kaisen2-amd64  | 1         | 5.26%   |
| 5.5.0-kaisen1-amd64  | 1         | 5.26%   |
| 5.16.0-kaisen1-amd64 | 1         | 5.26%   |
| 5.14.0-kaisen1-amd64 | 1         | 5.26%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 7         | 36.84%  |
| 5.15.0  | 4         | 21.05%  |
| 5.8.0   | 2         | 10.53%  |
| 5.17.0  | 2         | 10.53%  |
| 5.9.0   | 1         | 5.26%   |
| 5.5.0   | 1         | 5.26%   |
| 5.16.0  | 1         | 5.26%   |
| 5.14.0  | 1         | 5.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 7         | 36.84%  |
| 5.15    | 4         | 21.05%  |
| 5.8     | 2         | 10.53%  |
| 5.17    | 2         | 10.53%  |
| 5.9     | 1         | 5.26%   |
| 5.5     | 1         | 5.26%   |
| 5.16    | 1         | 5.26%   |
| 5.14    | 1         | 5.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 19        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 12        | 63.16%  |
| KDE5    | 4         | 21.05%  |
| XFCE    | 1         | 5.26%   |
| LXDE    | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 19        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 11        | 57.89%  |
| TDM     | 6         | 31.58%  |
| SDDM    | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| fr_FR   | 8         | 42.11%  |
| en_US   | 8         | 42.11%  |
| nl_NL   | 1         | 5.26%   |
| de_CH   | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 13        | 68.42%  |
| BIOS | 6         | 31.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 9         | 47.37%  |
| Overlay | 5         | 26.32%  |
| Ext4    | 5         | 26.32%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 13        | 68.42%  |
| MBR  | 6         | 31.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 68.42%  |
| Yes       | 6         | 31.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 12        | 63.16%  |
| Yes       | 7         | 36.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 7         | 36.84%  |
| Lenovo           | 6         | 31.58%  |
| Dell             | 2         | 10.53%  |
| MSI              | 1         | 5.26%   |
| ASUSTek Computer | 1         | 5.26%   |
| Apple            | 1         | 5.26%   |
| Acer             | 1         | 5.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP EliteBook 840 G2                   | 2         | 10.53%  |
| MSI Vector GP76 12UH                  | 1         | 5.26%   |
| Lenovo ThinkPad T520 4243E51          | 1         | 5.26%   |
| Lenovo ThinkPad T450 20BV003SMS       | 1         | 5.26%   |
| Lenovo ThinkPad T430 23427YU          | 1         | 5.26%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW | 1         | 5.26%   |
| Lenovo Legion Y530-15ICH 81FV         | 1         | 5.26%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 1         | 5.26%   |
| HP ProBook 650 G2                     | 1         | 5.26%   |
| HP ProBook 645 G1                     | 1         | 5.26%   |
| HP Pavilion g7                        | 1         | 5.26%   |
| HP Pavilion 15                        | 1         | 5.26%   |
| HP EliteBook 840 G1                   | 1         | 5.26%   |
| Dell Latitude 3540                    | 1         | 5.26%   |
| Dell Inspiron 14 5401                 | 1         | 5.26%   |
| ASUS N76VB                            | 1         | 5.26%   |
| Apple MacBookPro9,2                   | 1         | 5.26%   |
| Acer Aspire One 753                   | 1         | 5.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 4         | 21.05%  |
| HP EliteBook      | 3         | 15.79%  |
| HP ProBook        | 2         | 10.53%  |
| HP Pavilion       | 2         | 10.53%  |
| MSI Vector        | 1         | 5.26%   |
| Lenovo Legion     | 1         | 5.26%   |
| Lenovo IdeaPad    | 1         | 5.26%   |
| Dell Latitude     | 1         | 5.26%   |
| Dell Inspiron     | 1         | 5.26%   |
| ASUS N76VB        | 1         | 5.26%   |
| Apple MacBookPro9 | 1         | 5.26%   |
| Acer Aspire       | 1         | 5.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 4         | 21.05%  |
| 2015 | 3         | 15.79%  |
| 2020 | 2         | 10.53%  |
| 2012 | 2         | 10.53%  |
| 2011 | 2         | 10.53%  |
| 2022 | 1         | 5.26%   |
| 2021 | 1         | 5.26%   |
| 2018 | 1         | 5.26%   |
| 2016 | 1         | 5.26%   |
| 2014 | 1         | 5.26%   |
| 2010 | 1         | 5.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 19        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 19        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 6         | 31.58%  |
| 8.01-16.0  | 5         | 26.32%  |
| 16.01-24.0 | 4         | 21.05%  |
| 32.01-64.0 | 2         | 10.53%  |
| 3.01-4.0   | 2         | 10.53%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 8         | 42.11%  |
| 2.01-3.0  | 5         | 26.32%  |
| 3.01-4.0  | 3         | 15.79%  |
| 4.01-8.0  | 1         | 5.26%   |
| 8.01-16.0 | 1         | 5.26%   |
| 0.51-1.0  | 1         | 5.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 12        | 63.16%  |
| 2      | 7         | 36.84%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11        | 57.89%  |
| Yes       | 8         | 42.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 94.74%  |
| No        | 1         | 5.26%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 78.95%  |
| No        | 4         | 21.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| France      | 9         | 47.37%  |
| USA         | 4         | 21.05%  |
| Switzerland | 1         | 5.26%   |
| Slovakia    | 1         | 5.26%   |
| Netherlands | 1         | 5.26%   |
| India       | 1         | 5.26%   |
| Belgium     | 1         | 5.26%   |
| Australia   | 1         | 5.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Toulouse           | 2         | 10.53%  |
| Paris              | 2         | 10.53%  |
| Meulan-en-Yvelines | 2         | 10.53%  |
| Villejuif          | 1         | 5.26%   |
| Valencia           | 1         | 5.26%   |
| Tresses            | 1         | 5.26%   |
| Short Hills        | 1         | 5.26%   |
| Pinckney           | 1         | 5.26%   |
| Perth              | 1         | 5.26%   |
| Nitra              | 1         | 5.26%   |
| Nieuw-Vossemeer    | 1         | 5.26%   |
| Mechanicsburg      | 1         | 5.26%   |
| Malappuram         | 1         | 5.26%   |
| Gavere             | 1         | 5.26%   |
| Dijon              | 1         | 5.26%   |
| Bern               | 1         | 5.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 20%     |
| Seagate             | 4         | 4      | 16%     |
| HGST                | 3         | 3      | 12%     |
| WDC                 | 2         | 2      | 8%      |
| Toshiba             | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| Micron Technology   | 1         | 1      | 4%      |
| MARSHAL             | 1         | 1      | 4%      |
| LITEONIT            | 1         | 1      | 4%      |
| KIOXIA              | 1         | 1      | 4%      |
| JMicron Technology  | 1         | 1      | 4%      |
| Intel               | 1         | 1      | 4%      |
| Hitachi             | 1         | 1      | 4%      |
| Crucial             | 1         | 1      | 4%      |
| Corsair             | 1         | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST500LM021-1KJ152 500GB           | 2         | 8%      |
| HGST HTS541010A9E680 1TB                  | 2         | 8%      |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 4%      |
| WDC WD3200BPVT-22ZEST0 320GB              | 1         | 4%      |
| Toshiba KXG6AZNV1T02 1TB                  | 1         | 4%      |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 4%      |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 4%      |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 4%      |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 4%      |
| Samsung SSD 850 PRO 256GB                 | 1         | 4%      |
| Samsung SSD 750 EVO 250GB                 | 1         | 4%      |
| Samsung MZMPA024HMCD-000L1 24GB SSD       | 1         | 4%      |
| Samsung MZ7LN256HCHP-000L7 256GB SSD      | 1         | 4%      |
| Micron 2450_MTFDKBA1T0TFK 1TB             | 1         | 4%      |
| MARSHAL MAL2500SA-T54L 500GB              | 1         | 4%      |
| LITEONIT LMT-64M6M mSATA 64GB SSD         | 1         | 4%      |
| KIOXIA KBG40ZNS512G NVMe 512GB            | 1         | 4%      |
| JMicron Generic 160GB                     | 1         | 4%      |
| Intel SSDSC2BX480G4 480GB                 | 1         | 4%      |
| Hitachi HTS545050A7E380 500GB             | 1         | 4%      |
| HGST HTS725050A7E630 500GB                | 1         | 4%      |
| Crucial CT1000MX500SSD1 1TB               | 1         | 4%      |
| Corsair Force MP300 240GB                 | 1         | 4%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 40%     |
| HGST    | 3         | 3      | 30%     |
| WDC     | 1         | 1      | 10%     |
| MARSHAL | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 44.44%  |
| WDC                 | 1         | 1      | 11.11%  |
| LITEONIT            | 1         | 1      | 11.11%  |
| JMicron Technology  | 1         | 1      | 11.11%  |
| Intel               | 1         | 1      | 11.11%  |
| Crucial             | 1         | 1      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 43.48%  |
| SSD  | 8         | 9      | 34.78%  |
| NVMe | 5         | 6      | 21.74%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 18     | 72.73%  |
| NVMe | 5         | 6      | 22.73%  |
| SAS  | 1         | 1      | 4.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 15     | 76.47%  |
| 0.51-1.0   | 4         | 4      | 23.53%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 6         | 31.58%  |
| 501-1000   | 3         | 15.79%  |
| 51-100     | 3         | 15.79%  |
| 101-250    | 2         | 10.53%  |
| 1-20       | 2         | 10.53%  |
| Unknown    | 2         | 10.53%  |
| 21-50      | 1         | 5.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 10        | 52.63%  |
| 101-250  | 4         | 21.05%  |
| 21-50    | 2         | 10.53%  |
| Unknown  | 2         | 10.53%  |
| 501-1000 | 1         | 5.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB | 2         | 2      | 28.57%  |
| WDC WD3200BPVT-22ZEST0 320GB    | 1         | 1      | 14.29%  |
| Seagate ST500LM000-1EJ162 500GB | 1         | 1      | 14.29%  |
| MARSHAL MAL2500SA-T54L 500GB    | 1         | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB   | 1         | 1      | 14.29%  |
| HGST HTS725050A7E630 500GB      | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 42.86%  |
| WDC     | 1         | 1      | 14.29%  |
| MARSHAL | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 42.86%  |
| WDC     | 1         | 1      | 14.29%  |
| MARSHAL | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 11        | 16     | 55%     |
| Malfunc  | 7         | 7      | 35%     |
| Detected | 1         | 1      | 5%      |
| Failed   | 1         | 1      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 12        | 54.55%  |
| AMD                          | 4         | 18.18%  |
| Toshiba America Info Systems | 1         | 4.55%   |
| SK hynix                     | 1         | 4.55%   |
| Samsung Electronics          | 1         | 4.55%   |
| Phison Electronics           | 1         | 4.55%   |
| Micron Technology            | 1         | 4.55%   |
| KIOXIA                       | 1         | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 4         | 17.39%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 13.04%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 13.04%  |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 4.35%   |
| SK hynix BC511                                                               | 1         | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 4.35%   |
| Phison NVMe Storage Controller                                               | 1         | 4.35%   |
| Micron Non-Volatile memory controller                                        | 1         | 4.35%   |
| KIOXIA NVMe SSD Controller BG4                                               | 1         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 1         | 4.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 4.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 4.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 4.35%   |
| AMD FCH IDE Controller                                                       | 1         | 4.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 15        | 68.18%  |
| NVMe | 5         | 22.73%  |
| RAID | 1         | 4.55%   |
| IDE  | 1         | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 78.95%  |
| AMD    | 4         | 21.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz         | 2         | 10.53%  |
| Intel Core i7-8750H CPU @ 2.20GHz         | 1         | 5.26%   |
| Intel Core i7-3740QM CPU @ 2.70GHz        | 1         | 5.26%   |
| Intel Core i7-3630QM CPU @ 2.40GHz        | 1         | 5.26%   |
| Intel Core i7-2620M CPU @ 2.70GHz         | 1         | 5.26%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz        | 1         | 5.26%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 1         | 5.26%   |
| Intel Core i5-5200U CPU @ 2.20GHz         | 1         | 5.26%   |
| Intel Core i5-4300U CPU @ 1.90GHz         | 1         | 5.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz         | 1         | 5.26%   |
| Intel Core i5-3210M CPU @ 2.50GHz         | 1         | 5.26%   |
| Intel Celeron CPU U3600 @ 1.20GHz         | 1         | 5.26%   |
| Intel 12th Gen Core i7-12700H             | 1         | 5.26%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz   | 1         | 5.26%   |
| AMD Ryzen 7 4800U with Radeon Graphics    | 1         | 5.26%   |
| AMD A6-5350M APU with Radeon HD Graphics  | 1         | 5.26%   |
| AMD A6-4400M APU with Radeon HD Graphics  | 1         | 5.26%   |
| AMD A10-5745M APU with Radeon HD Graphics | 1         | 5.26%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 7         | 36.84%  |
| Intel Core i7 | 5         | 26.32%  |
| Other         | 2         | 10.53%  |
| AMD A6        | 2         | 10.53%  |
| Intel Celeron | 1         | 5.26%   |
| AMD Ryzen 7   | 1         | 5.26%   |
| AMD A10       | 1         | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 10        | 52.63%  |
| 4      | 4         | 21.05%  |
| 1      | 2         | 10.53%  |
| 14     | 1         | 5.26%   |
| 8      | 1         | 5.26%   |
| 6      | 1         | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 94.74%  |
| 1      | 1         | 5.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 19        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306d4    | 3         | 15.79%  |
| 0x306a9    | 3         | 15.79%  |
| 0x906ea    | 1         | 5.26%   |
| 0x906a3    | 1         | 5.26%   |
| 0x806c1    | 1         | 5.26%   |
| 0x706e5    | 1         | 5.26%   |
| 0x406e3    | 1         | 5.26%   |
| 0x40651    | 1         | 5.26%   |
| 0x206a7    | 1         | 5.26%   |
| 0x20655    | 1         | 5.26%   |
| 0x08600106 | 1         | 5.26%   |
| 0x0600111f | 1         | 5.26%   |
| 0x06001119 | 1         | 5.26%   |
| 0x06001116 | 1         | 5.26%   |
| Unknown    | 1         | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Piledriver       | 3         | 15.79%  |
| IvyBridge        | 3         | 15.79%  |
| Broadwell        | 3         | 15.79%  |
| Haswell          | 2         | 10.53%  |
| Zen 2            | 1         | 5.26%   |
| Westmere         | 1         | 5.26%   |
| TigerLake        | 1         | 5.26%   |
| Skylake          | 1         | 5.26%   |
| SandyBridge      | 1         | 5.26%   |
| KabyLake         | 1         | 5.26%   |
| IceLake          | 1         | 5.26%   |
| Alderlake Hybrid | 1         | 5.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 62.5%   |
| AMD    | 5         | 20.83%  |
| Nvidia | 4         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                    | 3         | 12.5%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 12.5%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 8.33%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 4.17%   |
| Nvidia GK107M [GeForce GT 740M]                                           | 1         | 4.17%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 4.17%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                  | 1         | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 4.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 4.17%   |
| Intel Iris Plus Graphics G7                                               | 1         | 4.17%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 4.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 4.17%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 1         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 4.17%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                | 1         | 4.17%   |
| AMD Trinity 2 [Radeon HD 7520G]                                           | 1         | 4.17%   |
| AMD Richland [Radeon HD 8610G]                                            | 1         | 4.17%   |
| AMD Richland [Radeon HD 8450G]                                            | 1         | 4.17%   |
| AMD Renoir                                                                | 1         | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 10        | 52.63%  |
| Intel + Nvidia | 4         | 21.05%  |
| 1 x AMD        | 4         | 21.05%  |
| Intel + AMD    | 1         | 5.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 17        | 89.47%  |
| Proprietary | 2         | 10.53%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 63.16%  |
| 0.51-1.0   | 3         | 15.79%  |
| 0.01-0.5   | 2         | 10.53%  |
| 7.01-8.0   | 1         | 5.26%   |
| 1.01-2.0   | 1         | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 5         | 21.74%  |
| Chimei Innolux          | 5         | 21.74%  |
| AU Optronics            | 3         | 13.04%  |
| Chi Mei Optoelectronics | 2         | 8.7%    |
| Acer                    | 2         | 8.7%    |
| Sharp                   | 1         | 4.35%   |
| Lenovo                  | 1         | 4.35%   |
| Iiyama                  | 1         | 4.35%   |
| Dell                    | 1         | 4.35%   |
| BOE                     | 1         | 4.35%   |
| Apple                   | 1         | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch               | 2         | 8.7%    |
| Sharp LQ173M1JW08 SHP1544 1920x1080 382x215mm 17.3-inch                   | 1         | 4.35%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch              | 1         | 4.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 4.35%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch               | 1         | 4.35%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 1         | 4.35%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                      | 1         | 4.35%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                           | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch           | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 1         | 4.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 4.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 4.35%   |
| BOE LCD Monitor BOE09DC 1920x1080 344x194mm 15.5-inch                     | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO453D 1920x1080 309x174mm 14.0-inch            | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 1         | 4.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 1         | 4.35%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                    | 1         | 4.35%   |
| Acer K202HQL ACR03E0 1366x768 434x236mm 19.4-inch                         | 1         | 4.35%   |
| Acer B193W ACR001E 1440x900 408x255mm 18.9-inch                           | 1         | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 9         | 42.86%  |
| 1366x768 (WXGA)  | 7         | 33.33%  |
| 1600x900 (HD+)   | 2         | 9.52%   |
| 1440x900 (WXGA+) | 2         | 9.52%   |
| 1280x800 (WXGA)  | 1         | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 7         | 30.43%  |
| 14     | 5         | 21.74%  |
| 17     | 3         | 13.04%  |
| 13     | 3         | 13.04%  |
| 19     | 2         | 8.7%    |
| 27     | 1         | 4.35%   |
| 18     | 1         | 4.35%   |
| 11     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 60.87%  |
| 401-500     | 3         | 13.04%  |
| 351-400     | 3         | 13.04%  |
| 201-300     | 2         | 8.7%    |
| 501-600     | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 85.71%  |
| 16/10 | 3         | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 34.78%  |
| 101-110        | 7         | 30.43%  |
| 151-200        | 3         | 13.04%  |
| 121-130        | 3         | 13.04%  |
| 51-60          | 1         | 4.35%   |
| 301-350        | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 11        | 47.83%  |
| 101-120 | 7         | 30.43%  |
| 51-100  | 5         | 21.74%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 15        | 78.95%  |
| 2     | 4         | 21.05%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 39.29%  |
| Realtek Semiconductor | 6         | 21.43%  |
| Qualcomm Atheros      | 6         | 21.43%  |
| Broadcom              | 2         | 7.14%   |
| Sierra Wireless       | 1         | 3.57%   |
| Lenovo                | 1         | 3.57%   |
| ASUSTek Computer      | 1         | 3.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 7.5%    |
| Intel Wireless 7265                                               | 3         | 7.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 7.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 5%      |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5%      |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 2.5%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 2.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.5%    |
| Realtek 802.11ac NIC                                              | 1         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 2.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 2.5%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 2.5%    |
| Lenovo USB-C Dock Ethernet                                        | 1         | 2.5%    |
| Intel Wireless 8260                                               | 1         | 2.5%    |
| Intel Wireless 7260                                               | 1         | 2.5%    |
| Intel Wi-Fi 6 AX201                                               | 1         | 2.5%    |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.5%    |
| Intel Ethernet Connection I219-V                                  | 1         | 2.5%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.5%    |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 2.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 2.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 2.5%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 2.5%    |
| ASUS 802.11ac NIC                                                 | 1         | 2.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 52.38%  |
| Qualcomm Atheros      | 5         | 23.81%  |
| Realtek Semiconductor | 2         | 9.52%   |
| Broadcom              | 2         | 9.52%   |
| ASUSTek Computer      | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                        | 3         | 14.29%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 3         | 14.29%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2         | 9.52%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 4.76%   |
| Realtek 802.11ac NIC                                       | 1         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 4.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 4.76%   |
| Intel Wireless 8260                                        | 1         | 4.76%   |
| Intel Wireless 7260                                        | 1         | 4.76%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 4.76%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 4.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                           | 1         | 4.76%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 1         | 4.76%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 4.76%   |
| ASUS 802.11ac NIC                                          | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 8         | 42.11%  |
| Realtek Semiconductor | 6         | 31.58%  |
| Qualcomm Atheros      | 2         | 10.53%  |
| Sierra Wireless       | 1         | 5.26%   |
| Lenovo                | 1         | 5.26%   |
| Broadcom              | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 15.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 10.53%  |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 10.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 10.53%  |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 5.26%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 5.26%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 5.26%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 5.26%   |
| Intel Ethernet Connection I219-V                                  | 1         | 5.26%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.26%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 5.26%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 5.26%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 51.35%  |
| Ethernet | 18        | 48.65%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 11        | 55%     |
| Ethernet | 9         | 45%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 17        | 89.47%  |
| 1     | 2         | 10.53%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12        | 63.16%  |
| Yes  | 7         | 36.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7         | 46.67%  |
| Qualcomm Atheros Communications | 3         | 20%     |
| IMC Networks                    | 1         | 6.67%   |
| Foxconn / Hon Hai               | 1         | 6.67%   |
| Cambridge Silicon Radio         | 1         | 6.67%   |
| Broadcom                        | 1         | 6.67%   |
| Apple                           | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 26.67%  |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 13.33%  |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 6.67%   |
| Intel Bluetooth Device                              | 1         | 6.67%   |
| Intel AX201 Bluetooth                               | 1         | 6.67%   |
| Intel AX200 Bluetooth                               | 1         | 6.67%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 6.67%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.67%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 6.67%   |
| Apple Bluetooth USB Host Controller                 | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 15        | 57.69%  |
| Nvidia      | 4         | 15.38%  |
| AMD         | 4         | 15.38%  |
| Roland      | 1         | 3.85%   |
| Plantronics | 1         | 3.85%   |
| Lenovo      | 1         | 3.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 8.82%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 8.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 8.82%   |
| AMD Trinity HDMI Audio Controller                                          | 3         | 8.82%   |
| AMD FCH Azalia Controller                                                  | 3         | 8.82%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 5.88%   |
| Roland QUAD-CAPTURE                                                        | 1         | 2.94%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 2.94%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.94%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 2.94%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 2.94%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 2.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 25%     |
| Samsung Electronics | 5         | 20.83%  |
| Crucial             | 5         | 20.83%  |
| Micron Technology   | 2         | 8.33%   |
| A-DATA Technology   | 2         | 8.33%   |
| Ramaxel Technology  | 1         | 4.17%   |
| Kingston            | 1         | 4.17%   |
| Elpida              | 1         | 4.17%   |
| Apacer              | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 2         | 7.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 3.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 3.85%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.85%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 3.85%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 3.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 3.85%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 3.85%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 1         | 3.85%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 3.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 3.85%   |
| Ramaxel RAM RMSA3260MD78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 3.85%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 3.85%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16384MB SODIMM DDR4 3200MT/s     | 1         | 3.85%   |
| Kingston RAM ASU16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 3.85%   |
| Elpida RAM EBJ81UG8EFU0-GN-F 8GB SODIMM DDR3 1600MT/s        | 1         | 3.85%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s       | 1         | 3.85%   |
| Crucial RAM CT102464BF160B.Y16 8GB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2667MT/s    | 1         | 3.85%   |
| Apacer RAM 78.A2GC8.CY00C 2GB SODIMM DDR3 800MT/s            | 1         | 3.85%   |
| Apacer RAM 78.A2GC8.9L00C 2GB SODIMM DDR3 800MT/s            | 1         | 3.85%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 3.85%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s         | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR3 | 13        | 68.42%  |
| DDR4 | 6         | 31.58%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 94.74%  |
| Row Of Chips | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 11        | 55%     |
| 4096  | 6         | 30%     |
| 16384 | 2         | 10%     |
| 2048  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 11        | 57.89%  |
| 3200  | 3         | 15.79%  |
| 2667  | 2         | 10.53%  |
| 2133  | 1         | 5.26%   |
| 1334  | 1         | 5.26%   |
| 800   | 1         | 5.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M2070 Series | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 33.33%  |
| Acer                                   | 3         | 16.67%  |
| Cheng Uei Precision Industry (Foxlink) | 2         | 11.11%  |
| Suyin                                  | 1         | 5.56%   |
| Sunplus Innovation Technology          | 1         | 5.56%   |
| Realtek Semiconductor                  | 1         | 5.56%   |
| Microdia                               | 1         | 5.56%   |
| Lite-On Technology                     | 1         | 5.56%   |
| IMC Networks                           | 1         | 5.56%   |
| Apple                                  | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 2         | 11.11%  |
| Chicony HP HD Webcam                                | 2         | 11.11%  |
| Acer Integrated Camera                              | 2         | 11.11%  |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 5.56%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 5.56%   |
| Realtek Integrated_Webcam_HD                        | 1         | 5.56%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 5.56%   |
| Lite-On HP HD Webcam                                | 1         | 5.56%   |
| IMC Networks Integrated Camera                      | 1         | 5.56%   |
| Chicony HP Truevision HD                            | 1         | 5.56%   |
| Chicony HP HD Camera                                | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 5.56%   |
| Apple FaceTime HD Camera                            | 1         | 5.56%   |
| Acer HD Webcam                                      | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 83.33%  |
| Shenzhen Goodix Technology | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 4         | 66.67%  |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device          | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 10        | 52.63%  |
| 1     | 6         | 31.58%  |
| 2     | 2         | 10.53%  |
| 3     | 1         | 5.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 6         | 60%     |
| Net/wireless       | 1         | 10%     |
| Chipcard           | 1         | 10%     |
| Card reader        | 1         | 10%     |
| Camera             | 1         | 10%     |

