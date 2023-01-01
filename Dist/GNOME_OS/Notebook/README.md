GNOME OS - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for GNOME OS.

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

Total: 35

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Apple   | MacBookPro8,1               | [1b5ab725ab](https://linux-hardware.org/?probe=1b5ab725ab) | Nov 09, 2022 |
| Lenovo  | IdeaPad 330-15AST 81D6      | [abbb3295c8](https://linux-hardware.org/?probe=abbb3295c8) | Oct 14, 2022 |
| Lenovo  | IdeaPad 330-15AST 81D6      | [f19e981e03](https://linux-hardware.org/?probe=f19e981e03) | Oct 14, 2022 |
| Dell    | Inspiron 3584               | [626c79c116](https://linux-hardware.org/?probe=626c79c116) | Sep 24, 2022 |
| HP      | Pavilion 15                 | [56a10ce74c](https://linux-hardware.org/?probe=56a10ce74c) | Sep 21, 2022 |
| ASUSTek | GL553VE                     | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| ASUSTek | GL553VE                     | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| Acer    | Aspire A515-51G             | [4856a5fefb](https://linux-hardware.org/?probe=4856a5fefb) | Jul 22, 2022 |
| Lenovo  | Yoga Slim 7 14ARE05 82A2    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| Apple   | MacBookPro10,1              | [1bbdbe7117](https://linux-hardware.org/?probe=1bbdbe7117) | Apr 04, 2022 |
| Acer    | Iconia W700                 | [604cdabab4](https://linux-hardware.org/?probe=604cdabab4) | Mar 23, 2022 |
| Lenovo  | ThinkPad Edge E531 68851... | [54269ad944](https://linux-hardware.org/?probe=54269ad944) | Feb 18, 2022 |
| Gateway | NE71B                       | [ac3dc96ccf](https://linux-hardware.org/?probe=ac3dc96ccf) | Feb 02, 2022 |
| HP      | Laptop 14-dk1xxx            | [c604eec754](https://linux-hardware.org/?probe=c604eec754) | Jan 27, 2022 |
| Chuwi   | HeroBook                    | [67990dbe7f](https://linux-hardware.org/?probe=67990dbe7f) | Jan 19, 2022 |
| Lenovo  | Yoga Slim 7 14ARE05 82A2    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| ASUSTek | X555LD                      | [2560d8b5a0](https://linux-hardware.org/?probe=2560d8b5a0) | Sep 27, 2021 |
| Lenovo  | IdeaPad S340-14API 81NB     | [c248e4551a](https://linux-hardware.org/?probe=c248e4551a) | Sep 25, 2021 |
| HP      | Pavilion Notebook           | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| Lenovo  | IdeaPad S145-15IWL 81S9     | [35c20c8cde](https://linux-hardware.org/?probe=35c20c8cde) | Aug 30, 2021 |
| HP      | Pavilion Gaming Laptop 1... | [5a54384297](https://linux-hardware.org/?probe=5a54384297) | Aug 11, 2021 |
| HP      | ProBook 430 G3              | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP      | ProBook 430 G3              | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Toshiba | Satellite C55-A-1F5         | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba | Satellite C55-A-1F5         | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| HP      | Pavilion 17                 | [220bf859f8](https://linux-hardware.org/?probe=220bf859f8) | Mar 28, 2021 |
| HP      | Pavilion 17                 | [a5a6941b23](https://linux-hardware.org/?probe=a5a6941b23) | Mar 28, 2021 |
| Dell    | Latitude 7490               | [ce86510d2b](https://linux-hardware.org/?probe=ce86510d2b) | Mar 28, 2021 |
| Dell    | Inspiron 3542               | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| Unknown | Unknown                     | [1c5ed732c5](https://linux-hardware.org/?probe=1c5ed732c5) | Mar 01, 2021 |
| Dell    | Precision M6800             | [95fa029c09](https://linux-hardware.org/?probe=95fa029c09) | Jan 14, 2021 |
| Dell    | Inspiron 5566               | [a3fd17119a](https://linux-hardware.org/?probe=a3fd17119a) | Nov 03, 2020 |
| HP      | Pavilion 17                 | [edc8ed595b](https://linux-hardware.org/?probe=edc8ed595b) | Oct 12, 2020 |
| ASUSTek | E202SA                      | [a226259559](https://linux-hardware.org/?probe=a226259559) | Sep 24, 2020 |
| Acer    | ChiefRiver Platform         | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME OS Nightly | 19        | 70.37%  |
| GNOME OS 3.38    | 4         | 14.81%  |
| GNOME OS 43      | 1         | 3.7%    |
| GNOME OS 42      | 1         | 3.7%    |
| GNOME OS 41      | 1         | 3.7%    |
| GNOME OS 40      | 1         | 3.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| GNOME OS | 27        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.18 | 7         | 25%     |
| 5.7.14  | 5         | 17.86%  |
| 5.11.2  | 3         | 10.71%  |
| 5.18.19 | 2         | 7.14%   |
| 5.13.9  | 2         | 7.14%   |
| 5.13.8  | 2         | 7.14%   |
| 5.11.10 | 2         | 7.14%   |
| 5.19.16 | 1         | 3.57%   |
| 5.18.16 | 1         | 3.57%   |
| 5.18.10 | 1         | 3.57%   |
| 5.14.4  | 1         | 3.57%   |
| 5.14.11 | 1         | 3.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.18 | 7         | 25%     |
| 5.7.14  | 5         | 17.86%  |
| 5.11.2  | 3         | 10.71%  |
| 5.18.19 | 2         | 7.14%   |
| 5.13.9  | 2         | 7.14%   |
| 5.13.8  | 2         | 7.14%   |
| 5.11.10 | 2         | 7.14%   |
| 5.19.16 | 1         | 3.57%   |
| 5.18.16 | 1         | 3.57%   |
| 5.18.10 | 1         | 3.57%   |
| 5.14.4  | 1         | 3.57%   |
| 5.14.11 | 1         | 3.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 8         | 29.63%  |
| 5.7     | 5         | 18.52%  |
| 5.11    | 5         | 18.52%  |
| 5.18    | 4         | 14.81%  |
| 5.13    | 4         | 14.81%  |
| 5.19    | 1         | 3.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 27        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 27        | 96.43%  |
| Unknown | 1         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 27        | 96.43%  |
| Unknown | 1         | 3.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 13        | 48.15%  |
| ru_RU | 4         | 14.81%  |
| fr_FR | 3         | 11.11%  |
| sv_SE | 1         | 3.7%    |
| sk_SK | 1         | 3.7%    |
| pt_BR | 1         | 3.7%    |
| nl_NL | 1         | 3.7%    |
| it_IT | 1         | 3.7%    |
| hu_HU | 1         | 3.7%    |
| es_ES | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 26        | 96.3%   |
| BIOS | 1         | 3.7%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ext4 | 27        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 96.43%  |
| GPT     | 1         | 3.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 27        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Hewlett-Packard  | 7         | 25.93%  |
| Dell             | 5         | 18.52%  |
| Lenovo           | 4         | 14.81%  |
| ASUSTek Computer | 3         | 11.11%  |
| Acer             | 3         | 11.11%  |
| Apple            | 2         | 7.41%   |
| Toshiba          | 1         | 3.7%    |
| Gateway          | 1         | 3.7%    |
| Chuwi            | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Pavilion 17                      | 2         | 7.41%   |
| Toshiba Satellite C55-A-1F5         | 1         | 3.7%    |
| Lenovo Yoga Slim 7 14ARE05 82A2     | 1         | 3.7%    |
| Lenovo ThinkPad Edge E531 68851P6   | 1         | 3.7%    |
| Lenovo IdeaPad S340-14API 81NB      | 1         | 3.7%    |
| Lenovo IdeaPad S145-15IWL 81S9      | 1         | 3.7%    |
| HP ProBook 430 G3                   | 1         | 3.7%    |
| HP Pavilion Notebook                | 1         | 3.7%    |
| HP Pavilion Gaming Laptop 15-ec0xxx | 1         | 3.7%    |
| HP Pavilion 15                      | 1         | 3.7%    |
| HP Laptop 14-dk1xxx                 | 1         | 3.7%    |
| Gateway NE71B                       | 1         | 3.7%    |
| Dell Precision M6800                | 1         | 3.7%    |
| Dell Latitude 7490                  | 1         | 3.7%    |
| Dell Inspiron 5566                  | 1         | 3.7%    |
| Dell Inspiron 3584                  | 1         | 3.7%    |
| Dell Inspiron 3542                  | 1         | 3.7%    |
| Chuwi HeroBook                      | 1         | 3.7%    |
| ASUS X555LD                         | 1         | 3.7%    |
| ASUS GL553VE                        | 1         | 3.7%    |
| ASUS E202SA                         | 1         | 3.7%    |
| Apple MacBookPro8,1                 | 1         | 3.7%    |
| Apple MacBookPro10,1                | 1         | 3.7%    |
| Acer Iconia W700                    | 1         | 3.7%    |
| Acer ChiefRiver Platform            | 1         | 3.7%    |
| Acer Aspire A515-51G                | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 5         | 18.52%  |
| Dell Inspiron      | 3         | 11.11%  |
| Lenovo IdeaPad     | 2         | 7.41%   |
| Toshiba Satellite  | 1         | 3.7%    |
| Lenovo Yoga        | 1         | 3.7%    |
| Lenovo ThinkPad    | 1         | 3.7%    |
| HP ProBook         | 1         | 3.7%    |
| HP Laptop          | 1         | 3.7%    |
| Gateway NE71B      | 1         | 3.7%    |
| Dell Precision     | 1         | 3.7%    |
| Dell Latitude      | 1         | 3.7%    |
| Chuwi HeroBook     | 1         | 3.7%    |
| ASUS X555LD        | 1         | 3.7%    |
| ASUS GL553VE       | 1         | 3.7%    |
| ASUS E202SA        | 1         | 3.7%    |
| Apple MacBookPro8  | 1         | 3.7%    |
| Apple MacBookPro10 | 1         | 3.7%    |
| Acer Iconia        | 1         | 3.7%    |
| Acer ChiefRiver    | 1         | 3.7%    |
| Acer Aspire        | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 6         | 22.22%  |
| 2013 | 6         | 22.22%  |
| 2017 | 3         | 11.11%  |
| 2015 | 3         | 11.11%  |
| 2014 | 3         | 11.11%  |
| 2012 | 2         | 7.41%   |
| 2020 | 1         | 3.7%    |
| 2018 | 1         | 3.7%    |
| 2016 | 1         | 3.7%    |
| 2011 | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 27        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 27        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 14        | 51.85%  |
| 3.01-4.0   | 6         | 22.22%  |
| 8.01-16.0  | 5         | 18.52%  |
| 16.01-24.0 | 1         | 3.7%    |
| 1.01-2.0   | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 20        | 74.07%  |
| 2.01-3.0 | 3         | 11.11%  |
| 4.01-8.0 | 2         | 7.41%   |
| 0.51-1.0 | 2         | 7.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 92.59%  |
| 2      | 2         | 7.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 70.37%  |
| Yes       | 8         | 29.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 85.19%  |
| No        | 4         | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 85.19%  |
| No        | 4         | 14.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 5         | 18.52%  |
| France      | 3         | 11.11%  |
| Ukraine     | 2         | 7.41%   |
| Brazil      | 2         | 7.41%   |
| UAE         | 1         | 3.7%    |
| Sweden      | 1         | 3.7%    |
| Slovakia    | 1         | 3.7%    |
| Serbia      | 1         | 3.7%    |
| Russia      | 1         | 3.7%    |
| Netherlands | 1         | 3.7%    |
| Latvia      | 1         | 3.7%    |
| Italy       | 1         | 3.7%    |
| Iraq        | 1         | 3.7%    |
| India       | 1         | 3.7%    |
| Greece      | 1         | 3.7%    |
| Finland     | 1         | 3.7%    |
| El Salvador | 1         | 3.7%    |
| Chile       | 1         | 3.7%    |
| Canada      | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Västerås        | 1         | 3.7%    |
| Vancouver         | 1         | 3.7%    |
| Uruguaiana        | 1         | 3.7%    |
| Talence           | 1         | 3.7%    |
| Skydra            | 1         | 3.7%    |
| Santiago          | 1         | 3.7%    |
| San Salvador      | 1         | 3.7%    |
| Riga              | 1         | 3.7%    |
| Pori              | 1         | 3.7%    |
| Parempuyre        | 1         | 3.7%    |
| Novi Sad          | 1         | 3.7%    |
| Millers Creek     | 1         | 3.7%    |
| Milan             | 1         | 3.7%    |
| Mariupol          | 1         | 3.7%    |
| Levis             | 1         | 3.7%    |
| Lelystad          | 1         | 3.7%    |
| Lehighton         | 1         | 3.7%    |
| Kyiv              | 1         | 3.7%    |
| Krasnoyarsk       | 1         | 3.7%    |
| Juazeiro do Norte | 1         | 3.7%    |
| Hyderabad         | 1         | 3.7%    |
| Gig Harbor        | 1         | 3.7%    |
| Castelnau-le-Lez  | 1         | 3.7%    |
| Bratislava        | 1         | 3.7%    |
| Belton            | 1         | 3.7%    |
| Baghdad           | 1         | 3.7%    |
| Abu Dhabi         | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 17.24%  |
| Seagate             | 3         | 3      | 10.34%  |
| HGST                | 3         | 3      | 10.34%  |
| Toshiba             | 2         | 2      | 6.9%    |
| SanDisk             | 2         | 2      | 6.9%    |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Micron Technology   | 2         | 2      | 6.9%    |
| Kingston            | 2         | 2      | 6.9%    |
| Transcend           | 1         | 1      | 3.45%   |
| SSSTC               | 1         | 1      | 3.45%   |
| SK hynix            | 1         | 2      | 3.45%   |
| Patriot             | 1         | 1      | 3.45%   |
| Intel               | 1         | 1      | 3.45%   |
| HECTRON             | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| Apple               | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| HGST HTS541010A9E680 1TB                  | 2         | 6.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 3.33%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 3.33%   |
| WDC WD5000LPVX-08V0TT5 500GB              | 1         | 3.33%   |
| WDC WD3200LPVX-08V0TT5 320GB              | 1         | 3.33%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 3.33%   |
| Transcend TS64GMTS400 64GB SSD            | 1         | 3.33%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 3.33%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 3.33%   |
| SSSTC CVB-8D128-HP 128GB                  | 1         | 3.33%   |
| SK hynix SKHynix_HFS512GD9TNG-L3A0B 512GB | 1         | 3.33%   |
| SK hynix NVMe SSD Drive 512GB             | 1         | 3.33%   |
| Seagate ST9500325AS 500GB                 | 1         | 3.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 3.33%   |
| SanDisk X300 MSATA 128GB SSD              | 1         | 3.33%   |
| SanDisk SD8SN8U512G1002 512GB SSD         | 1         | 3.33%   |
| Samsung SSD 860 EVO 500GB                 | 1         | 3.33%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB    | 1         | 3.33%   |
| Patriot Burst Elite 120GB SSD             | 1         | 3.33%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD       | 1         | 3.33%   |
| Micron 1100_MTFDDAK256TBN 256GB SSD       | 1         | 3.33%   |
| Kingston SHFS37A120G 120GB SSD            | 1         | 3.33%   |
| Kingston SA400S37120G 120GB SSD           | 1         | 3.33%   |
| Intel SSDSCKKF256G8 SATA 256GB            | 1         | 3.33%   |
| HGST HTS541010A7E630 1TB                  | 1         | 3.33%   |
| HECTRON HECX1-60G                         | 1         | 3.33%   |
| Crucial CT240BX500SSD1 240GB              | 1         | 3.33%   |
| Apple SSD SM768E 752GB                    | 1         | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 33.33%  |
| Seagate | 3         | 3      | 25%     |
| HGST    | 3         | 3      | 25%     |
| Toshiba | 2         | 2      | 16.67%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 2         | 2      | 14.29%  |
| Micron Technology   | 2         | 2      | 14.29%  |
| Kingston            | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Transcend           | 1         | 1      | 7.14%   |
| SSSTC               | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Patriot             | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| Apple               | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 14        | 14     | 48.28%  |
| HDD     | 12        | 12     | 41.38%  |
| NVMe    | 2         | 3      | 6.9%    |
| Unknown | 1         | 1      | 3.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 27     | 92.59%  |
| NVMe | 2         | 3      | 7.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 18     | 68%     |
| 0.51-1.0   | 8         | 8      | 32%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 40.74%  |
| 251-500    | 8         | 29.63%  |
| 501-1000   | 6         | 22.22%  |
| 51-100     | 2         | 7.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 24        | 88.89%  |
| 21-50   | 3         | 11.11%  |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 27        | 29     | 96.43%  |
| Works    | 1         | 1      | 3.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 19        | 70.37%  |
| AMD                 | 6         | 22.22%  |
| SK hynix            | 1         | 3.7%    |
| Samsung Electronics | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 21.43%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 17.86%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 17.86%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 10.71%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 7.14%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 3.57%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 3.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 3.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 3.57%   |
| AMD FCH IDE Controller                                                           | 1         | 3.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 25        | 89.29%  |
| NVMe | 2         | 7.14%   |
| IDE  | 1         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 70.37%  |
| AMD    | 8         | 29.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 7.41%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 7.41%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 3.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 3.7%    |
| Intel Core i7-3820QM CPU @ 2.70GHz            | 1         | 3.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 3.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 3.7%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 3.7%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 3.7%    |
| Intel Core i5-2415M CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 3.7%    |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 3.7%    |
| Intel Core i3-2375M CPU @ 1.50GHz             | 1         | 3.7%    |
| Intel Celeron CPU N3050 @ 1.60GHz             | 1         | 3.7%    |
| Intel Celeron 2957U @ 1.40GHz                 | 1         | 3.7%    |
| Intel Atom x5-E8000 CPU @ 1.04GHz             | 1         | 3.7%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 1         | 3.7%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 1         | 3.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 3.7%    |
| AMD E1-1200 APU with Radeon HD Graphics       | 1         | 3.7%    |
| AMD Athlon Silver 3050U with Radeon Graphics  | 1         | 3.7%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 1         | 3.7%    |
| AMD A8-5550M APU with Radeon HD Graphics      | 1         | 3.7%    |
| AMD A10-5745M APU with Radeon HD Graphics     | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model         | Notebooks | Percent |
|---------------|-----------|---------|
| Intel Core i3 | 7         | 25.93%  |
| Intel Core i5 | 6         | 22.22%  |
| Intel Core i7 | 3         | 11.11%  |
| Intel Celeron | 2         | 7.41%   |
| AMD Ryzen 5   | 2         | 7.41%   |
| AMD A8        | 2         | 7.41%   |
| Intel Atom    | 1         | 3.7%    |
| AMD Ryzen 7   | 1         | 3.7%    |
| AMD E1        | 1         | 3.7%    |
| AMD Athlon    | 1         | 3.7%    |
| AMD A10       | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 18        | 66.67%  |
| 4      | 8         | 29.63%  |
| 8      | 1         | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 20        | 74.07%  |
| 1      | 7         | 25.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 27        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 4         | 14.81%  |
| 0x406e3    | 3         | 11.11%  |
| 0x40651    | 3         | 11.11%  |
| 0x08108109 | 3         | 11.11%  |
| 0x206a7    | 2         | 7.41%   |
| 0x06001119 | 2         | 7.41%   |
| 0x806ec    | 1         | 3.7%    |
| 0x806ea    | 1         | 3.7%    |
| 0x806e9    | 1         | 3.7%    |
| 0x406c4    | 1         | 3.7%    |
| 0x406c3    | 1         | 3.7%    |
| 0x306c3    | 1         | 3.7%    |
| 0x08600106 | 1         | 3.7%    |
| 0x07030105 | 1         | 3.7%    |
| 0x0500010d | 1         | 3.7%    |
| Unknown    | 1         | 3.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 4         | 14.81%  |
| IvyBridge   | 4         | 14.81%  |
| Haswell     | 4         | 14.81%  |
| Zen+        | 3         | 11.11%  |
| Skylake     | 3         | 11.11%  |
| Silvermont  | 2         | 7.41%   |
| SandyBridge | 2         | 7.41%   |
| Piledriver  | 2         | 7.41%   |
| Zen 2       | 1         | 3.7%    |
| Puma        | 1         | 3.7%    |
| Bobcat      | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 52.78%  |
| AMD    | 9         | 25%     |
| Nvidia | 8         | 22.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 10.53%  |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 7.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 7.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 7.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 5.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 5.26%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 2.63%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 2.63%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 2.63%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 2.63%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 2.63%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 2.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 2.63%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 2.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 2.63%   |
| Intel UHD Graphics 620                                                                   | 1         | 2.63%   |
| Intel HD Graphics 630                                                                    | 1         | 2.63%   |
| Intel HD Graphics 620                                                                    | 1         | 2.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 2.63%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 2.63%   |
| AMD Saturn XT [FirePro M6100]                                                            | 1         | 2.63%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 2.63%   |
| AMD Richland [Radeon HD 8550G]                                                           | 1         | 2.63%   |
| AMD Renoir                                                                               | 1         | 2.63%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 11        | 40.74%  |
| Intel + Nvidia | 7         | 25.93%  |
| 1 x AMD        | 5         | 18.52%  |
| 2 x AMD        | 2         | 7.41%   |
| Intel + AMD    | 1         | 3.7%    |
| AMD + Nvidia   | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver | Notebooks | Percent |
|--------|-----------|---------|
| Free   | 27        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 44.44%  |
| 0.51-1.0   | 6         | 22.22%  |
| 1.01-2.0   | 5         | 18.52%  |
| 0.01-0.5   | 3         | 11.11%  |
| 2.01-3.0   | 1         | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 7         | 25%     |
| LG Display          | 6         | 21.43%  |
| BOE                 | 5         | 17.86%  |
| Chimei Innolux      | 4         | 14.29%  |
| Samsung Electronics | 2         | 7.14%   |
| Apple               | 2         | 7.14%   |
| InfoVision          | 1         | 3.57%   |
| Dell                | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch | 1         | 3.57%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 1         | 3.57%   |
| LG Display LCD Monitor LGD04B3 1920x1080 345x194mm 15.6-inch         | 1         | 3.57%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch         | 1         | 3.57%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 1         | 3.57%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                    | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15D6 1920x1080 344x193mm 15.5-inch     | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch     | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch      | 1         | 3.57%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 1         | 3.57%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 1         | 3.57%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 1         | 3.57%   |
| BOE LCD Monitor BOE065F 1920x1080 344x194mm 15.5-inch                | 1         | 3.57%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                 | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO305D 1920x1080 256x144mm 11.6-inch       | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO233C 1366x768 309x173mm 13.9-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO223D 1920x1080 309x174mm 14.0-inch       | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO162C 1366x768 293x164mm 13.2-inch        | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch        | 1         | 3.57%   |
| Apple Color LCD APPA00E 2880x1800 331x207mm 15.4-inch                | 1         | 3.57%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 12        | 42.86%  |
| 1366x768 (WXGA) | 10        | 35.71%  |
| 1600x900 (HD+)  | 3         | 10.71%  |
| 2880x1800       | 1         | 3.57%   |
| 2560x1440 (QHD) | 1         | 3.57%   |
| 1280x800 (WXGA) | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 42.86%  |
| 14     | 5         | 17.86%  |
| 17     | 4         | 14.29%  |
| 13     | 4         | 14.29%  |
| 11     | 2         | 7.14%   |
| 24     | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 19        | 67.86%  |
| 351-400     | 4         | 14.29%  |
| 201-300     | 4         | 14.29%  |
| 501-600     | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 92.59%  |
| 16/10 | 2         | 7.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 42.86%  |
| 81-90          | 8         | 28.57%  |
| 121-130        | 4         | 14.29%  |
| 51-60          | 2         | 7.14%   |
| 71-80          | 1         | 3.57%   |
| 201-250        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 13        | 46.43%  |
| 101-120 | 11        | 39.29%  |
| 161-240 | 2         | 7.14%   |
| 51-100  | 2         | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 26        | 96.3%   |
| 2     | 1         | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 39.53%  |
| Qualcomm Atheros      | 10        | 23.26%  |
| Intel                 | 7         | 16.28%  |
| Broadcom              | 4         | 9.3%    |
| Broadcom Limited      | 3         | 6.98%   |
| TP-Link               | 1         | 2.33%   |
| Google                | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 15.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 13.46%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 5.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 5.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 3.85%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.92%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.92%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 1.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.92%   |
| Intel Wireless 7265                                               | 1         | 1.92%   |
| Intel Wireless 3165                                               | 1         | 1.92%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.92%   |
| Intel Centrino Wireless-N 105                                     | 1         | 1.92%   |
| Google Pixel 6a                                                   | 1         | 1.92%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.92%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 1         | 1.92%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                            | 1         | 1.92%   |
| Broadcom Limited BCM43142 802.11b/g/n                             | 1         | 1.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 1.92%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 9         | 33.33%  |
| Realtek Semiconductor | 7         | 25.93%  |
| Intel                 | 5         | 18.52%  |
| Broadcom Limited      | 3         | 11.11%  |
| Broadcom              | 3         | 11.11%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 3         | 11.11%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 3         | 11.11%  |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 7.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 7.41%   |
| Broadcom BCM43142 802.11b/g/n                              | 2         | 7.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 3.7%    |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.7%    |
| Realtek 802.11n WLAN Adapter                               | 1         | 3.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 3.7%    |
| Intel Wireless 7265                                        | 1         | 3.7%    |
| Intel Wireless 3165                                        | 1         | 3.7%    |
| Intel Wi-Fi 6 AX200                                        | 1         | 3.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.7%    |
| Intel Centrino Wireless-N 105                              | 1         | 3.7%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter | 1         | 3.7%    |
| Broadcom Limited BCM4331 802.11a/b/g/n                     | 1         | 3.7%    |
| Broadcom Limited BCM43142 802.11b/g/n                      | 1         | 3.7%    |
| Broadcom BCM4331 802.11a/b/g/n                             | 1         | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 66.67%  |
| Qualcomm Atheros      | 2         | 8.33%   |
| Intel                 | 2         | 8.33%   |
| Broadcom              | 2         | 8.33%   |
| TP-Link               | 1         | 4.17%   |
| Google                | 1         | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 32%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 28%     |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 4%      |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 4%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 4%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 4%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 4%      |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4%      |
| Google Pixel 6a                                                   | 1         | 4%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 4%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 4%      |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 54%     |
| Ethernet | 23        | 46%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 15        | 55.56%  |
| WiFi     | 12        | 44.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 74.07%  |
| 1     | 5         | 18.52%  |
| 3     | 1         | 3.7%    |
| 0     | 1         | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 71.43%  |
| Yes  | 8         | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 5         | 21.74%  |
| Qualcomm Atheros Communications | 5         | 21.74%  |
| Lite-On Technology              | 4         | 17.39%  |
| Intel                           | 4         | 17.39%  |
| Apple                           | 2         | 8.7%    |
| Toshiba                         | 1         | 4.35%   |
| Dell                            | 1         | 4.35%   |
| Broadcom                        | 1         | 4.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device           | 4         | 17.39%  |
| Realtek Bluetooth Radio                      | 3         | 13.04%  |
| Intel Bluetooth wireless interface           | 3         | 13.04%  |
| Lite-On Broadcom BCM43142A0 Bluetooth Device | 2         | 8.7%    |
| Apple Bluetooth Host Controller              | 2         | 8.7%    |
| Toshiba Bluetooth Device                     | 1         | 4.35%   |
| Realtek RTL8821A Bluetooth                   | 1         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter               | 1         | 4.35%   |
| Qualcomm Atheros AR9462 Bluetooth            | 1         | 4.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth   | 1         | 4.35%   |
| Lite-On Bluetooth Device                     | 1         | 4.35%   |
| Intel AX200 Bluetooth                        | 1         | 4.35%   |
| Dell Broadcom BCM20702A0 Bluetooth           | 1         | 4.35%   |
| Broadcom BCM43142A0 Bluetooth Device         | 1         | 4.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 19        | 59.38%  |
| AMD                 | 9         | 28.13%  |
| Nvidia              | 3         | 9.38%   |
| Huawei Technologies | 1         | 3.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 11.63%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 11.63%  |
| AMD FCH Azalia Controller                                                                         | 4         | 9.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 9.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 6.98%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 6.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 4.65%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 4.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 4.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.33%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 2.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.33%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.33%   |
| Huawei Technologies USB-C HEADSET                                                                 | 1         | 2.33%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 2.33%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 2.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 2.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Micron Technology | 1         | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM MT53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 4266MT/s | 1         | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| LPDDR4 | 1         | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Row Of Chips | 1         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 1         | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 4266  | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 23.08%  |
| Realtek Semiconductor                  | 5         | 19.23%  |
| Suyin                                  | 3         | 11.54%  |
| Sunplus Innovation Technology          | 2         | 7.69%   |
| Microdia                               | 2         | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.69%   |
| Apple                                  | 2         | 7.69%   |
| Syntek                                 | 1         | 3.85%   |
| Quanta                                 | 1         | 3.85%   |
| Logitech                               | 1         | 3.85%   |
| IMC Networks                           | 1         | 3.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Suyin HP Truevision HD                           | 3         | 11.11%  |
| Realtek USB Camera                               | 2         | 7.41%   |
| Chicony Integrated Camera                        | 2         | 7.41%   |
| Syntek Integrated Camera                         | 1         | 3.7%    |
| Sunplus Integrated_Webcam_HD                     | 1         | 3.7%    |
| Sunplus HD WebCam                                | 1         | 3.7%    |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 3.7%    |
| Realtek Integrated_Webcam_HD                     | 1         | 3.7%    |
| Realtek Integrated Camera                        | 1         | 3.7%    |
| Quanta HD Webcam                                 | 1         | 3.7%    |
| Microdia Integrated_Webcam_HD                    | 1         | 3.7%    |
| Microdia Integrated Webcam HD                    | 1         | 3.7%    |
| Logitech Webcam C270                             | 1         | 3.7%    |
| IMC Networks HP TrueVision HD Camera             | 1         | 3.7%    |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 3.7%    |
| Chicony TOSHIBA Web Camera - HD                  | 1         | 3.7%    |
| Chicony HP HD Camera                             | 1         | 3.7%    |
| Chicony HD WebCam                                | 1         | 3.7%    |
| Chicony 5M Cam                                   | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 1         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 1         | 3.7%    |
| Apple FaceTime HD Camera (Built-in)              | 1         | 3.7%    |
| Apple FaceTime HD Camera                         | 1         | 3.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader | 1         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 9         | 33.33%  |
| 1     | 9         | 33.33%  |
| 3     | 5         | 18.52%  |
| 4     | 3         | 11.11%  |
| 0     | 1         | 3.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 17        | 30.91%  |
| Net/wireless             | 14        | 25.45%  |
| Graphics card            | 5         | 9.09%   |
| Card reader              | 5         | 9.09%   |
| Multimedia controller    | 4         | 7.27%   |
| Bluetooth                | 4         | 7.27%   |
| Net/ethernet             | 3         | 5.45%   |
| Storage/ide              | 1         | 1.82%   |
| Fingerprint reader       | 1         | 1.82%   |
| Chipcard                 | 1         | 1.82%   |

