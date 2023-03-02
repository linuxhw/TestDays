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

Total: 29

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo  | ThinkPad T431s 20AA000MU... | [68779350fd](https://linux-hardware.org/?probe=68779350fd) | Feb 24, 2023 |
| Lenovo  | ThinkPad L470 20J4CTO1WW    | [7d55f655bb](https://linux-hardware.org/?probe=7d55f655bb) | Feb 15, 2023 |
| Dell    | G3 3500                     | [9a574c1075](https://linux-hardware.org/?probe=9a574c1075) | Oct 04, 2022 |
| Samsung | 370E4K                      | [1a297b75f9](https://linux-hardware.org/?probe=1a297b75f9) | Sep 18, 2022 |
| Dell    | Inspiron 15 7000 Gaming     | [edc0c871cb](https://linux-hardware.org/?probe=edc0c871cb) | Sep 17, 2022 |
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
| Kaisen 1.8 | 7         | 29.17%  |
| Kaisen 2.1 | 5         | 20.83%  |
| Kaisen 2.0 | 5         | 20.83%  |
| Kaisen 1.4 | 3         | 12.5%   |
| Kaisen 1.6 | 2         | 8.33%   |
| Kaisen 2.2 | 1         | 4.17%   |
| Kaisen 1.0 | 1         | 4.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Kaisen | 24        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-kaisen1-amd64 | 5         | 20.83%  |
| 5.10.0-kaisen5-amd64 | 5         | 20.83%  |
| 5.17.0-kaisen1-amd64 | 4         | 16.67%  |
| 5.8.0-kaisen2-amd64  | 2         | 8.33%   |
| 5.10.0-kaisen3-amd64 | 2         | 8.33%   |
| 6.0.0-1kaisen-amd64  | 1         | 4.17%   |
| 5.9.0-kaisen2-amd64  | 1         | 4.17%   |
| 5.5.0-kaisen1-amd64  | 1         | 4.17%   |
| 5.19.0-kaisen1-amd64 | 1         | 4.17%   |
| 5.16.0-kaisen1-amd64 | 1         | 4.17%   |
| 5.14.0-kaisen1-amd64 | 1         | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 7         | 29.17%  |
| 5.15.0  | 5         | 20.83%  |
| 5.17.0  | 4         | 16.67%  |
| 5.8.0   | 2         | 8.33%   |
| 6.0.0   | 1         | 4.17%   |
| 5.9.0   | 1         | 4.17%   |
| 5.5.0   | 1         | 4.17%   |
| 5.19.0  | 1         | 4.17%   |
| 5.16.0  | 1         | 4.17%   |
| 5.14.0  | 1         | 4.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 7         | 29.17%  |
| 5.15    | 5         | 20.83%  |
| 5.17    | 4         | 16.67%  |
| 5.8     | 2         | 8.33%   |
| 6.0     | 1         | 4.17%   |
| 5.9     | 1         | 4.17%   |
| 5.5     | 1         | 4.17%   |
| 5.19    | 1         | 4.17%   |
| 5.16    | 1         | 4.17%   |
| 5.14    | 1         | 4.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 24        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 14        | 58.33%  |
| KDE5    | 5         | 20.83%  |
| XFCE    | 2         | 8.33%   |
| LXQt    | 1         | 4.17%   |
| LXDE    | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 24        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 16        | 66.67%  |
| TDM     | 6         | 25%     |
| SDDM    | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 10        | 41.67%  |
| fr_FR   | 8         | 33.33%  |
| pt_BR   | 3         | 12.5%   |
| nl_NL   | 1         | 4.17%   |
| de_CH   | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 16        | 66.67%  |
| BIOS | 8         | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 13        | 54.17%  |
| Overlay | 6         | 25%     |
| Ext4    | 5         | 20.83%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 16        | 66.67%  |
| MBR  | 8         | 33.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 66.67%  |
| Yes       | 8         | 33.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 70.83%  |
| Yes       | 7         | 29.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 8         | 33.33%  |
| Hewlett-Packard     | 7         | 29.17%  |
| Dell                | 4         | 16.67%  |
| Samsung Electronics | 1         | 4.17%   |
| MSI                 | 1         | 4.17%   |
| ASUSTek Computer    | 1         | 4.17%   |
| Apple               | 1         | 4.17%   |
| Acer                | 1         | 4.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP EliteBook 840 G2                   | 2         | 8.33%   |
| Samsung 370E4K                        | 1         | 4.17%   |
| MSI Vector GP76 12UH                  | 1         | 4.17%   |
| Lenovo ThinkPad T520 4243E51          | 1         | 4.17%   |
| Lenovo ThinkPad T450 20BV003SMS       | 1         | 4.17%   |
| Lenovo ThinkPad T431s 20AA000MUS      | 1         | 4.17%   |
| Lenovo ThinkPad T430 23427YU          | 1         | 4.17%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW | 1         | 4.17%   |
| Lenovo ThinkPad L470 20J4CTO1WW       | 1         | 4.17%   |
| Lenovo Legion Y530-15ICH 81FV         | 1         | 4.17%   |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 1         | 4.17%   |
| HP ProBook 650 G2                     | 1         | 4.17%   |
| HP ProBook 645 G1                     | 1         | 4.17%   |
| HP Pavilion g7                        | 1         | 4.17%   |
| HP Pavilion 15                        | 1         | 4.17%   |
| HP EliteBook 840 G1                   | 1         | 4.17%   |
| Dell Latitude 3540                    | 1         | 4.17%   |
| Dell Inspiron 15 7000 Gaming          | 1         | 4.17%   |
| Dell Inspiron 14 5401                 | 1         | 4.17%   |
| Dell G3 3500                          | 1         | 4.17%   |
| ASUS N76VB                            | 1         | 4.17%   |
| Apple MacBookPro9,2                   | 1         | 4.17%   |
| Acer Aspire One 753                   | 1         | 4.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 6         | 25%     |
| HP EliteBook      | 3         | 12.5%   |
| HP ProBook        | 2         | 8.33%   |
| HP Pavilion       | 2         | 8.33%   |
| Dell Inspiron     | 2         | 8.33%   |
| Samsung 370E4K    | 1         | 4.17%   |
| MSI Vector        | 1         | 4.17%   |
| Lenovo Legion     | 1         | 4.17%   |
| Lenovo IdeaPad    | 1         | 4.17%   |
| Dell Latitude     | 1         | 4.17%   |
| Dell G3           | 1         | 4.17%   |
| ASUS N76VB        | 1         | 4.17%   |
| Apple MacBookPro9 | 1         | 4.17%   |
| Acer Aspire       | 1         | 4.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 5         | 20.83%  |
| 2015 | 4         | 16.67%  |
| 2020 | 3         | 12.5%   |
| 2017 | 2         | 8.33%   |
| 2012 | 2         | 8.33%   |
| 2011 | 2         | 8.33%   |
| 2022 | 1         | 4.17%   |
| 2021 | 1         | 4.17%   |
| 2018 | 1         | 4.17%   |
| 2016 | 1         | 4.17%   |
| 2014 | 1         | 4.17%   |
| 2010 | 1         | 4.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 24        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 24        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 24        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 7         | 29.17%  |
| 8.01-16.0  | 7         | 29.17%  |
| 16.01-24.0 | 5         | 20.83%  |
| 32.01-64.0 | 3         | 12.5%   |
| 3.01-4.0   | 2         | 8.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 10        | 41.67%  |
| 2.01-3.0  | 6         | 25%     |
| 3.01-4.0  | 4         | 16.67%  |
| 8.01-16.0 | 2         | 8.33%   |
| 4.01-8.0  | 1         | 4.17%   |
| 0.51-1.0  | 1         | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 58.33%  |
| 2      | 10        | 41.67%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16        | 66.67%  |
| Yes       | 8         | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 95.83%  |
| No        | 1         | 4.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 79.17%  |
| No        | 5         | 20.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| France      | 9         | 37.5%   |
| USA         | 5         | 20.83%  |
| Brazil      | 4         | 16.67%  |
| Switzerland | 1         | 4.17%   |
| Slovakia    | 1         | 4.17%   |
| Netherlands | 1         | 4.17%   |
| India       | 1         | 4.17%   |
| Belgium     | 1         | 4.17%   |
| Australia   | 1         | 4.17%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Toulouse           | 2         | 8.33%   |
| Paris              | 2         | 8.33%   |
| Meulan-en-Yvelines | 2         | 8.33%   |
| Villejuif          | 1         | 4.17%   |
| Valencia           | 1         | 4.17%   |
| Tresses            | 1         | 4.17%   |
| Short Hills        | 1         | 4.17%   |
| Sao Paulo          | 1         | 4.17%   |
| Rio de Janeiro     | 1         | 4.17%   |
| Pinckney           | 1         | 4.17%   |
| Perth              | 1         | 4.17%   |
| Nitra              | 1         | 4.17%   |
| Nieuw-Vossemeer    | 1         | 4.17%   |
| Mechanicsburg      | 1         | 4.17%   |
| Malappuram         | 1         | 4.17%   |
| Maceió            | 1         | 4.17%   |
| Las Vegas          | 1         | 4.17%   |
| Joaima             | 1         | 4.17%   |
| Gavere             | 1         | 4.17%   |
| Dijon              | 1         | 4.17%   |
| Bern               | 1         | 4.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 5         | 5      | 15.15%  |
| Seagate                     | 4         | 4      | 12.12%  |
| WDC                         | 3         | 3      | 9.09%   |
| HGST                        | 3         | 3      | 9.09%   |
| Toshiba                     | 2         | 2      | 6.06%   |
| Kingston                    | 2         | 2      | 6.06%   |
| TCSUNBOW                    | 1         | 1      | 3.03%   |
| SK hynix                    | 1         | 1      | 3.03%   |
| SanDisk                     | 1         | 1      | 3.03%   |
| Micron Technology           | 1         | 1      | 3.03%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 3.03%   |
| MARSHAL                     | 1         | 1      | 3.03%   |
| LITEONIT                    | 1         | 1      | 3.03%   |
| LITEON                      | 1         | 1      | 3.03%   |
| KIOXIA                      | 1         | 1      | 3.03%   |
| JMicron Technology          | 1         | 1      | 3.03%   |
| Intel                       | 1         | 1      | 3.03%   |
| Hitachi                     | 1         | 1      | 3.03%   |
| Crucial                     | 1         | 1      | 3.03%   |
| Corsair                     | 1         | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST500LM021-1KJ152 500GB           | 2         | 6.06%   |
| HGST HTS541010A9E680 1TB                  | 2         | 6.06%   |
| WDC WDS500G2B0A-00SM50 500GB SSD          | 1         | 3.03%   |
| WDC WD3200BPVT-22ZEST0 320GB              | 1         | 3.03%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 3.03%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 3.03%   |
| Toshiba KXG6AZNV1T02 1TB                  | 1         | 3.03%   |
| TCSUNBOW N4 120GB SSD                     | 1         | 3.03%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 3.03%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 3.03%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 3.03%   |
| SanDisk SSD PLUS 120 GB                   | 1         | 3.03%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 3.03%   |
| Samsung SSD 850 PRO 256GB                 | 1         | 3.03%   |
| Samsung SSD 750 EVO 250GB                 | 1         | 3.03%   |
| Samsung MZMPA024HMCD-000L1 24GB SSD       | 1         | 3.03%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD      | 1         | 3.03%   |
| Micron 2450_MTFDKBA1T0TFK 1TB             | 1         | 3.03%   |
| MAXIO (Hangzhou) NVMe SSD Drive 512GB     | 1         | 3.03%   |
| MARSHAL MAL2500SA-T54L 500GB              | 1         | 3.03%   |
| LITEONIT LMT-64M6M mSATA 64GB SSD         | 1         | 3.03%   |
| LITEON CV3-8D256-11 SATA 256GB SSD        | 1         | 3.03%   |
| KIOXIA KBG40ZNS512G NVMe 512GB            | 1         | 3.03%   |
| Kingston SV300S37A240G 240GB SSD          | 1         | 3.03%   |
| Kingston SNVS1000GB 1TB                   | 1         | 3.03%   |
| JMicron Generic 200GB                     | 1         | 3.03%   |
| Intel SSDSC2BX480G4 480GB                 | 1         | 3.03%   |
| Hitachi HTS545050A7E380 500GB             | 1         | 3.03%   |
| HGST HTS725050A7E630 500GB                | 1         | 3.03%   |
| Crucial CT1000MX500SSD1 1TB               | 1         | 3.03%   |
| Corsair Force MP300 240GB                 | 1         | 3.03%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 4         | 4      | 30.77%  |
| HGST               | 3         | 3      | 23.08%  |
| WDC                | 2         | 2      | 15.38%  |
| Toshiba            | 1         | 1      | 7.69%   |
| MARSHAL            | 1         | 1      | 7.69%   |
| JMicron Technology | 1         | 1      | 7.69%   |
| Hitachi            | 1         | 1      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 33.33%  |
| WDC                 | 1         | 1      | 8.33%   |
| TCSUNBOW            | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| LITEONIT            | 1         | 1      | 8.33%   |
| LITEON              | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 13     | 40%     |
| SSD  | 11        | 12     | 36.67%  |
| NVMe | 7         | 8      | 23.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 24     | 71.43%  |
| NVMe | 7         | 8      | 25%     |
| SAS  | 1         | 1      | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 20     | 77.27%  |
| 0.51-1.0   | 5         | 5      | 22.73%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 6         | 25%     |
| 101-250    | 4         | 16.67%  |
| 501-1000   | 4         | 16.67%  |
| 1-20       | 3         | 12.5%   |
| 51-100     | 3         | 12.5%   |
| Unknown    | 2         | 8.33%   |
| 21-50      | 1         | 4.17%   |
| 1001-2000  | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 13        | 54.17%  |
| 101-250  | 4         | 16.67%  |
| 21-50    | 3         | 12.5%   |
| Unknown  | 2         | 8.33%   |
| 501-1000 | 1         | 4.17%   |
| 51-100   | 1         | 4.17%   |

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
| Works    | 16        | 23     | 61.54%  |
| Malfunc  | 7         | 7      | 26.92%  |
| Detected | 2         | 2      | 7.69%   |
| Failed   | 1         | 1      | 3.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 17        | 58.62%  |
| AMD                          | 4         | 13.79%  |
| Toshiba America Info Systems | 1         | 3.45%   |
| SK hynix                     | 1         | 3.45%   |
| Samsung Electronics          | 1         | 3.45%   |
| Phison Electronics           | 1         | 3.45%   |
| Micron Technology            | 1         | 3.45%   |
| MAXIO Technology (Hangzhou)  | 1         | 3.45%   |
| KIOXIA                       | 1         | 3.45%   |
| Kingston Technology Company  | 1         | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 4         | 13.33%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 13.33%  |
| AMD FCH SATA Controller [AHCI mode]                                          | 4         | 13.33%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 6.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 3.33%   |
| SK hynix BC511                                                               | 1         | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 3.33%   |
| Phison NVMe Storage Controller                                               | 1         | 3.33%   |
| Micron Non-Volatile memory controller                                        | 1         | 3.33%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                 | 1         | 3.33%   |
| KIOXIA NVMe SSD Controller BG4                                               | 1         | 3.33%   |
| Kingston Company Company Non-Volatile memory controller                      | 1         | 3.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 3.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 3.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 1         | 3.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 3.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 3.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 1         | 3.33%   |
| AMD FCH IDE Controller                                                       | 1         | 3.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 20        | 68.97%  |
| NVMe | 7         | 24.14%  |
| RAID | 1         | 3.45%   |
| IDE  | 1         | 3.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 83.33%  |
| AMD    | 4         | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz         | 2         | 8.33%   |
| Intel Core i5-5200U CPU @ 2.20GHz         | 2         | 8.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz         | 1         | 4.17%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz        | 1         | 4.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz         | 1         | 4.17%   |
| Intel Core i7-3740QM CPU @ 2.70GHz        | 1         | 4.17%   |
| Intel Core i7-3630QM CPU @ 2.40GHz        | 1         | 4.17%   |
| Intel Core i7-2620M CPU @ 2.70GHz         | 1         | 4.17%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz        | 1         | 4.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 1         | 4.17%   |
| Intel Core i5-4300U CPU @ 1.90GHz         | 1         | 4.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz         | 1         | 4.17%   |
| Intel Core i5-3437U CPU @ 1.90GHz         | 1         | 4.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz         | 1         | 4.17%   |
| Intel Core i5-10300H CPU @ 2.50GHz        | 1         | 4.17%   |
| Intel Celeron CPU U3600 @ 1.20GHz         | 1         | 4.17%   |
| Intel 12th Gen Core i7-12700H             | 1         | 4.17%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz   | 1         | 4.17%   |
| AMD Ryzen 7 4800U with Radeon Graphics    | 1         | 4.17%   |
| AMD A6-5350M APU with Radeon HD Graphics  | 1         | 4.17%   |
| AMD A6-4400M APU with Radeon HD Graphics  | 1         | 4.17%   |
| AMD A10-5745M APU with Radeon HD Graphics | 1         | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i5 | 10        | 41.67%  |
| Intel Core i7 | 7         | 29.17%  |
| Other         | 2         | 8.33%   |
| AMD A6        | 2         | 8.33%   |
| Intel Celeron | 1         | 4.17%   |
| AMD Ryzen 7   | 1         | 4.17%   |
| AMD A10       | 1         | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 54.17%  |
| 4      | 6         | 25%     |
| 1      | 2         | 8.33%   |
| 14     | 1         | 4.17%   |
| 8      | 1         | 4.17%   |
| 6      | 1         | 4.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 24        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 23        | 95.83%  |
| 1      | 1         | 4.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 24        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306d4    | 4         | 16.67%  |
| 0x306a9    | 4         | 16.67%  |
| 0xa0652    | 1         | 4.17%   |
| 0x906ea    | 1         | 4.17%   |
| 0x906e9    | 1         | 4.17%   |
| 0x906a3    | 1         | 4.17%   |
| 0x806e9    | 1         | 4.17%   |
| 0x806c1    | 1         | 4.17%   |
| 0x706e5    | 1         | 4.17%   |
| 0x406e3    | 1         | 4.17%   |
| 0x40651    | 1         | 4.17%   |
| 0x206a7    | 1         | 4.17%   |
| 0x20655    | 1         | 4.17%   |
| 0x08600106 | 1         | 4.17%   |
| 0x0600111f | 1         | 4.17%   |
| 0x06001119 | 1         | 4.17%   |
| 0x06001116 | 1         | 4.17%   |
| Unknown    | 1         | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| IvyBridge        | 4         | 16.67%  |
| Broadwell        | 4         | 16.67%  |
| Piledriver       | 3         | 12.5%   |
| KabyLake         | 3         | 12.5%   |
| Haswell          | 2         | 8.33%   |
| Zen 2            | 1         | 4.17%   |
| Westmere         | 1         | 4.17%   |
| TigerLake        | 1         | 4.17%   |
| Skylake          | 1         | 4.17%   |
| SandyBridge      | 1         | 4.17%   |
| IceLake          | 1         | 4.17%   |
| CometLake        | 1         | 4.17%   |
| Alderlake Hybrid | 1         | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 64.52%  |
| AMD    | 6         | 19.35%  |
| Nvidia | 5         | 16.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                        | 4         | 12.9%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 12.9%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 6.45%   |
| Nvidia TU117M                                                                 | 1         | 3.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 3.23%   |
| Nvidia GK107M [GeForce GT 740M]                                               | 1         | 3.23%   |
| Nvidia GF119M [Quadro NVS 4200M]                                              | 1         | 3.23%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                      | 1         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 3.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 3.23%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 3.23%   |
| Intel HD Graphics 630                                                         | 1         | 3.23%   |
| Intel HD Graphics 620                                                         | 1         | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 3.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 3.23%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 1         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 3.23%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                    | 1         | 3.23%   |
| AMD Trinity 2 [Radeon HD 7520G]                                               | 1         | 3.23%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 3.23%   |
| AMD Richland [Radeon HD 8610G]                                                | 1         | 3.23%   |
| AMD Richland [Radeon HD 8450G]                                                | 1         | 3.23%   |
| AMD Renoir                                                                    | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 54.17%  |
| Intel + Nvidia | 5         | 20.83%  |
| 1 x AMD        | 4         | 16.67%  |
| Intel + AMD    | 2         | 8.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 22        | 91.67%  |
| Proprietary | 2         | 8.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 62.5%   |
| 0.51-1.0   | 3         | 12.5%   |
| 1.01-2.0   | 2         | 8.33%   |
| 0.01-0.5   | 2         | 8.33%   |
| 7.01-8.0   | 1         | 4.17%   |
| 3.01-4.0   | 1         | 4.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 6         | 20%     |
| LG Display              | 5         | 16.67%  |
| AU Optronics            | 4         | 13.33%  |
| BOE                     | 3         | 10%     |
| Chi Mei Optoelectronics | 2         | 6.67%   |
| Acer                    | 2         | 6.67%   |
| Sharp                   | 1         | 3.33%   |
| Samsung Electronics     | 1         | 3.33%   |
| PANDA                   | 1         | 3.33%   |
| Lenovo                  | 1         | 3.33%   |
| Iiyama                  | 1         | 3.33%   |
| Goldstar                | 1         | 3.33%   |
| Dell                    | 1         | 3.33%   |
| Apple                   | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch               | 2         | 6.67%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 2         | 6.67%   |
| Sharp LQ173M1JW08 SHP1544 1920x1080 382x215mm 17.3-inch                   | 1         | 3.33%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch     | 1         | 3.33%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                   | 1         | 3.33%   |
| LG Display LCD Monitor LGD40BA 1920x1080 344x194mm 15.5-inch              | 1         | 3.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 3.33%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch               | 1         | 3.33%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 1         | 3.33%   |
| Iiyama PL2773H IVM660A 1920x1080 600x340mm 27.2-inch                      | 1         | 3.33%   |
| Goldstar E1960 GSM4BE5 1360x768 406x229mm 18.4-inch                       | 1         | 3.33%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                           | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch           | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x174mm 14.0-inch           | 1         | 3.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 3.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch  | 1         | 3.33%   |
| BOE LCD Monitor BOE09DC 1920x1080 344x194mm 15.5-inch                     | 1         | 3.33%   |
| BOE LCD Monitor BOE06B3 1920x1080                                         | 1         | 3.33%   |
| BOE LCD Monitor BOE05FE 1366x768 309x173mm 13.9-inch                      | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO453D 1920x1080 309x174mm 14.0-inch            | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch             | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 1         | 3.33%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                    | 1         | 3.33%   |
| Acer K202HQL ACR03E0 1600x900 432x240mm 19.5-inch                         | 1         | 3.33%   |
| Acer B193W ACR001E 1440x900 408x255mm 18.9-inch                           | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 12        | 44.44%  |
| 1366x768 (WXGA)  | 8         | 29.63%  |
| 1600x900 (HD+)   | 3         | 11.11%  |
| 1440x900 (WXGA+) | 2         | 7.41%   |
| 1360x768         | 1         | 3.7%    |
| 1280x800 (WXGA)  | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 30%     |
| 14     | 6         | 20%     |
| 13     | 5         | 16.67%  |
| 17     | 3         | 10%     |
| 19     | 2         | 6.67%   |
| 18     | 2         | 6.67%   |
| 27     | 1         | 3.33%   |
| 21     | 1         | 3.33%   |
| 11     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 63.33%  |
| 401-500     | 5         | 16.67%  |
| 351-400     | 3         | 10%     |
| 201-300     | 2         | 6.67%   |
| 501-600     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 23        | 88.46%  |
| 16/10 | 3         | 11.54%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 36.67%  |
| 101-110        | 9         | 30%     |
| 151-200        | 3         | 10%     |
| 121-130        | 3         | 10%     |
| 51-60          | 1         | 3.33%   |
| 301-350        | 1         | 3.33%   |
| 201-250        | 1         | 3.33%   |
| 141-150        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 14        | 46.67%  |
| 101-120 | 10        | 33.33%  |
| 51-100  | 6         | 20%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 18        | 75%     |
| 2     | 6         | 25%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 37.84%  |
| Realtek Semiconductor | 9         | 24.32%  |
| Qualcomm Atheros      | 8         | 21.62%  |
| Broadcom              | 2         | 5.41%   |
| TP-Link               | 1         | 2.7%    |
| Sierra Wireless       | 1         | 2.7%    |
| Lenovo                | 1         | 2.7%    |
| ASUSTek Computer      | 1         | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 9.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.88%   |
| Intel Wireless 7265                                               | 3         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 3.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 3.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 3.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 1.96%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.96%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.96%   |
| Realtek 802.11ac NIC                                              | 1         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.96%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 1.96%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.96%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.96%   |
| Intel Wireless 8260                                               | 1         | 1.96%   |
| Intel Wireless 7260                                               | 1         | 1.96%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.96%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.96%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.96%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.96%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 1.96%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 1.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 1.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 1.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 1         | 1.96%   |
| ASUS 802.11ac NIC                                                 | 1         | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 50%     |
| Qualcomm Atheros      | 7         | 25%     |
| Realtek Semiconductor | 2         | 7.14%   |
| Broadcom              | 2         | 7.14%   |
| TP-Link               | 1         | 3.57%   |
| Sierra Wireless       | 1         | 3.57%   |
| ASUSTek Computer      | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                        | 3         | 10.71%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 3         | 10.71%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 7.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 2         | 7.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2         | 7.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 3.57%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 3.57%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.57%   |
| Realtek 802.11ac NIC                                       | 1         | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 3.57%   |
| Intel Wireless 8265 / 8275                                 | 1         | 3.57%   |
| Intel Wireless 8260                                        | 1         | 3.57%   |
| Intel Wireless 7260                                        | 1         | 3.57%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.57%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 3.57%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 3.57%   |
| Intel Centrino Advanced-N 6235                             | 1         | 3.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                           | 1         | 3.57%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 1         | 3.57%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 1         | 3.57%   |
| ASUS 802.11ac NIC                                          | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 43.48%  |
| Realtek Semiconductor | 9         | 39.13%  |
| Qualcomm Atheros      | 2         | 8.7%    |
| Lenovo                | 1         | 4.35%   |
| Broadcom              | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 21.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 13.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 13.04%  |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 8.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 4.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 4.35%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 4.35%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 4.35%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.35%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.35%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 4.35%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 4.35%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 4.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 51.06%  |
| Ethernet | 23        | 48.94%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 57.69%  |
| Ethernet | 11        | 42.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 22        | 91.67%  |
| 1     | 2         | 8.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 16        | 66.67%  |
| Yes  | 8         | 33.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 47.37%  |
| Qualcomm Atheros Communications | 5         | 26.32%  |
| IMC Networks                    | 1         | 5.26%   |
| Foxconn / Hon Hai               | 1         | 5.26%   |
| Cambridge Silicon Radio         | 1         | 5.26%   |
| Broadcom                        | 1         | 5.26%   |
| Apple                           | 1         | 5.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 26.32%  |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 15.79%  |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 5.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 5.26%   |
| Intel Bluetooth Device                              | 1         | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 5.26%   |
| Intel AX201 Bluetooth                               | 1         | 5.26%   |
| Intel AX200 Bluetooth                               | 1         | 5.26%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 5.26%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5.26%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 5.26%   |
| Apple Bluetooth USB Host Controller                 | 1         | 5.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 20        | 62.5%   |
| Nvidia      | 5         | 15.63%  |
| AMD         | 4         | 12.5%   |
| Roland      | 1         | 3.13%   |
| Plantronics | 1         | 3.13%   |
| Lenovo      | 1         | 3.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 9.76%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 9.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 9.76%   |
| AMD Trinity HDMI Audio Controller                                          | 3         | 7.32%   |
| AMD FCH Azalia Controller                                                  | 3         | 7.32%   |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 4.88%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 4.88%   |
| Roland QUAD-CAPTURE                                                        | 1         | 2.44%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 2.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 2.44%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.44%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 2.44%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 2.44%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 2.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.44%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.44%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.44%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.44%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.44%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 2.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 7         | 23.33%  |
| Samsung Electronics | 7         | 23.33%  |
| Crucial             | 5         | 16.67%  |
| Micron Technology   | 2         | 6.67%   |
| Kingston            | 2         | 6.67%   |
| A-DATA Technology   | 2         | 6.67%   |
| Ramaxel Technology  | 1         | 3.33%   |
| Elpida              | 1         | 3.33%   |
| Corsair             | 1         | 3.33%   |
| Apacer              | 1         | 3.33%   |
| 8A020000802C        | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 2         | 6.06%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s   | 2         | 6.06%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.03%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 3.03%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 3.03%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.03%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 3.03%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 3.03%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 3.03%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 3.03%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 3.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 3.03%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 3.03%   |
| Samsung RAM M471B5173BH0-YK0 4GB Chip DDR3 1600MT/s          | 1         | 3.03%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s     | 1         | 3.03%   |
| Samsung RAM 456789ABCDEFGHIJKL 4GB SODIMM DDR3 1600MT/s      | 1         | 3.03%   |
| Ramaxel RAM RMSA3260MD78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 1         | 3.03%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 3.03%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 1         | 3.03%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s         | 1         | 3.03%   |
| Kingston RAM ASU16D3LS1KBG/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 3.03%   |
| Elpida RAM EBJ81UG8EFU0-GN-F 8GB SODIMM DDR3 1600MT/s        | 1         | 3.03%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s       | 1         | 3.03%   |
| Crucial RAM CT102464BF160B.Y16 8GB SODIMM DDR3 1600MT/s      | 1         | 3.03%   |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2667MT/s    | 1         | 3.03%   |
| Corsair RAM CMSX16GX4M1A2400C16 16GB SODIMM DDR4 2400MT/s    | 1         | 3.03%   |
| Apacer RAM 78.A2GC8.CY00C 2GB SODIMM DDR3 800MT/s            | 1         | 3.03%   |
| Apacer RAM 78.A2GC8.9L00C 2GB SODIMM DDR3 800MT/s            | 1         | 3.03%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 3.03%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s         | 1         | 3.03%   |
| 8A020000802C RAM DDR4 16GB 2400MHz 16GB SODIMM DDR4 2400MT/s | 1         | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR3 | 15        | 62.5%   |
| DDR4 | 9         | 37.5%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 92%     |
| Row Of Chips | 1         | 4%      |
| Chip         | 1         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 14        | 53.85%  |
| 4096  | 7         | 26.92%  |
| 16384 | 4         | 15.38%  |
| 2048  | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 13        | 54.17%  |
| 3200  | 4         | 16.67%  |
| 2667  | 3         | 12.5%   |
| 2400  | 1         | 4.17%   |
| 2133  | 1         | 4.17%   |
| 1334  | 1         | 4.17%   |
| 800   | 1         | 4.17%   |

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
| Chicony Electronics                    | 6         | 26.09%  |
| Acer                                   | 4         | 17.39%  |
| Sunplus Innovation Technology          | 2         | 8.7%    |
| Realtek Semiconductor                  | 2         | 8.7%    |
| Microdia                               | 2         | 8.7%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8.7%    |
| Suyin                                  | 1         | 4.35%   |
| Silicon Motion                         | 1         | 4.35%   |
| Lite-On Technology                     | 1         | 4.35%   |
| IMC Networks                           | 1         | 4.35%   |
| Apple                                  | 1         | 4.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Acer Integrated Camera                              | 3         | 13.04%  |
| Chicony Integrated Camera                           | 2         | 8.7%    |
| Chicony HP HD Webcam                                | 2         | 8.7%    |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 1         | 4.35%   |
| Sunplus Integrated Webcam                           | 1         | 4.35%   |
| Sunplus Asus Webcam                                 | 1         | 4.35%   |
| Silicon Motion ATIV VGA Camera                      | 1         | 4.35%   |
| Realtek Integrated_Webcam_HD                        | 1         | 4.35%   |
| Realtek Integrated Camera                           | 1         | 4.35%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 4.35%   |
| Microdia Integrated_Webcam_HD                       | 1         | 4.35%   |
| Lite-On HP HD Webcam                                | 1         | 4.35%   |
| IMC Networks Integrated Camera                      | 1         | 4.35%   |
| Chicony HP Truevision HD                            | 1         | 4.35%   |
| Chicony HP HD Camera                                | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 4.35%   |
| Apple FaceTime HD Camera                            | 1         | 4.35%   |
| Acer HD Webcam                                      | 1         | 4.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 71.43%  |
| Shenzhen Goodix Technology | 2         | 28.57%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 4         | 57.14%  |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device          | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader           | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Upek        | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 11        | 45.83%  |
| 1     | 10        | 41.67%  |
| 2     | 2         | 8.33%   |
| 3     | 1         | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 7         | 53.85%  |
| Net/wireless       | 2         | 15.38%  |
| Chipcard           | 2         | 15.38%  |
| Card reader        | 1         | 7.69%   |
| Camera             | 1         | 7.69%   |

