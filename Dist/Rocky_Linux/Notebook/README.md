Rocky Linux - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
| Dell    | Latitude 5500               | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 2a 20X... | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Dell    | Latitude 5500               | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 2a 20X... | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo  | ThinkPad T14s Gen 2a 20X... | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Lenovo  | Legion Y7000 2020H 81Y7     | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo  | Legion Y7000 2020H 81Y7     | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| Lenovo  | IdeaPad Y700-15ISK 80NV     | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| HP      | ZBook 15 G3                 | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Lenovo  | Legion 5 15ARH05H 82B1      | [90821cb3a5](https://linux-hardware.org/?probe=90821cb3a5) | Jan 03, 2022 |
| Lenovo  | IdeaPad 500S-14ISK 80Q3     | [6ea0cdba08](https://linux-hardware.org/?probe=6ea0cdba08) | Nov 27, 2021 |
| Lenovo  | ThinkPad W540 20BGCTO1WW    | [25055cdc26](https://linux-hardware.org/?probe=25055cdc26) | Nov 23, 2021 |
| HP      | Laptop 17-ca1xxx            | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| Toshiba | TECRA W50-A                 | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Lenovo  | ThinkPad T420 42365H1       | [3430adab89](https://linux-hardware.org/?probe=3430adab89) | Aug 25, 2021 |
| Lenovo  | ThinkPad T420 42365H1       | [6a306e2253](https://linux-hardware.org/?probe=6a306e2253) | Aug 16, 2021 |
| Lenovo  | ThinkPad W500 406132G       | [e79080e90d](https://linux-hardware.org/?probe=e79080e90d) | Aug 08, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [860ec3c89d](https://linux-hardware.org/?probe=860ec3c89d) | Aug 08, 2021 |
| Lenovo  | IdeaPad Y410P 20216         | [b2df1c0e6d](https://linux-hardware.org/?probe=b2df1c0e6d) | Aug 08, 2021 |
| Lenovo  | IdeaPad Y410P 20216         | [3fc207c5b9](https://linux-hardware.org/?probe=3fc207c5b9) | Aug 07, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [2a4bd5cb12](https://linux-hardware.org/?probe=2a4bd5cb12) | Jul 11, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [09738de946](https://linux-hardware.org/?probe=09738de946) | Jul 04, 2021 |
| Lenovo  | IdeaPad Slim 1-14AST-05 ... | [741cab87e1](https://linux-hardware.org/?probe=741cab87e1) | Jun 29, 2021 |
| ASUSTek | ASUS TUF Gaming A15 FA50... | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Toshiba | Satellite E45-B             | [84683df1f0](https://linux-hardware.org/?probe=84683df1f0) | Jun 12, 2021 |
| Acer    | Aspire VN7-591G             | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Rocky Linux 8.5 | 8         | 47.06%  |
| Rocky Linux 8.4 | 8         | 47.06%  |
| Rocky Linux 8.3 | 1         | 5.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 17        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 17.65%  |
| 4.18.0-348.12.2.el8_5.x86_64 | 2         | 11.76%  |
| 4.18.0-305.el8.x86_64        | 2         | 11.76%  |
| 4.18.0-305.3.1.el8_4.x86_64  | 2         | 11.76%  |
| 4.18.0-305.25.1.el8_4.x86_64 | 2         | 11.76%  |
| 4.18.0-305.10.2.el8_4.x86_64 | 2         | 11.76%  |
| 5.4.157-1.el8.elrepo.x86_64  | 1         | 5.88%   |
| 4.18.0-348.el8.0.2.x86_64    | 1         | 5.88%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 5.88%   |
| 4.18.0-240.22.1.el8.x86_64   | 1         | 5.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 16        | 94.12%  |
| 5.4.157 | 1         | 5.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 16        | 94.12%  |
| 5.4     | 1         | 5.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 17        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 12        | 70.59%  |
| XFCE          | 1         | 5.88%   |
| X-Cinnamon    | 1         | 5.88%   |
| MATE          | 1         | 5.88%   |
| KDE5          | 1         | 5.88%   |
| GNOME Classic | 1         | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 9         | 52.94%  |
| X11     | 8         | 47.06%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 10        | 58.82%  |
| GDM     | 4         | 23.53%  |
| LightDM | 2         | 11.76%  |
| SDDM    | 1         | 5.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 13        | 76.47%  |
| de_DE | 2         | 11.76%  |
| it_IT | 1         | 5.88%   |
| en_ZA | 1         | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 12        | 70.59%  |
| BIOS | 5         | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 12        | 70.59%  |
| Ext4 | 5         | 29.41%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 12        | 70.59%  |
| GPT     | 5         | 29.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 88.24%  |
| Yes       | 2         | 11.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 10        | 58.82%  |
| Toshiba          | 2         | 11.76%  |
| Hewlett-Packard  | 2         | 11.76%  |
| Dell             | 1         | 5.88%   |
| ASUSTek Computer | 1         | 5.88%   |
| Acer             | 1         | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                      | 1         | 5.88%   |
| Toshiba Satellite E45-B                  | 1         | 5.88%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 5.88%   |
| Lenovo ThinkPad W500 406132G             | 1         | 5.88%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 5.88%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 5.88%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 5.88%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 5.88%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 5.88%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 5.88%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 5.88%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 5.88%   |
| HP ZBook 15 G3                           | 1         | 5.88%   |
| HP Laptop 17-ca1xxx                      | 1         | 5.88%   |
| Dell Latitude 5500                       | 1         | 5.88%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 5.88%   |
| Acer Aspire VN7-591G                     | 1         | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 4         | 23.53%  |
| Lenovo IdeaPad    | 4         | 23.53%  |
| Lenovo Legion     | 2         | 11.76%  |
| Toshiba TECRA     | 1         | 5.88%   |
| Toshiba Satellite | 1         | 5.88%   |
| HP ZBook          | 1         | 5.88%   |
| HP Laptop         | 1         | 5.88%   |
| Dell Latitude     | 1         | 5.88%   |
| ASUS ASUS         | 1         | 5.88%   |
| Acer Aspire       | 1         | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 3         | 17.65%  |
| 2019 | 3         | 17.65%  |
| 2014 | 3         | 17.65%  |
| 2016 | 2         | 11.76%  |
| 2022 | 1         | 5.88%   |
| 2018 | 1         | 5.88%   |
| 2015 | 1         | 5.88%   |
| 2013 | 1         | 5.88%   |
| 2011 | 1         | 5.88%   |
| 2009 | 1         | 5.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 17        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 17        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 5         | 29.41%  |
| 4.01-8.0   | 4         | 23.53%  |
| 16.01-24.0 | 4         | 23.53%  |
| 32.01-64.0 | 3         | 17.65%  |
| 3.01-4.0   | 1         | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 6         | 35.29%  |
| 2.01-3.0  | 4         | 23.53%  |
| 4.01-8.0  | 3         | 17.65%  |
| 1.01-2.0  | 3         | 17.65%  |
| 8.01-16.0 | 1         | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 10        | 58.82%  |
| 2      | 4         | 23.53%  |
| 3      | 3         | 17.65%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 88.24%  |
| Yes       | 2         | 11.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 94.12%  |
| No        | 1         | 5.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 94.12%  |
| No        | 1         | 5.88%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 5         | 29.41%  |
| Germany      | 2         | 11.76%  |
| Belgium      | 2         | 11.76%  |
| South Africa | 1         | 5.88%   |
| Slovakia     | 1         | 5.88%   |
| Poland       | 1         | 5.88%   |
| Malaysia     | 1         | 5.88%   |
| Kazakhstan   | 1         | 5.88%   |
| Italy        | 1         | 5.88%   |
| Czechia      | 1         | 5.88%   |
| China        | 1         | 5.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Žilina          | 1         | 5.88%   |
| Xi'an            | 1         | 5.88%   |
| Weinheim         | 1         | 5.88%   |
| Scarborough      | 1         | 5.88%   |
| San Ramon        | 1         | 5.88%   |
| Pretoria         | 1         | 5.88%   |
| Prague           | 1         | 5.88%   |
| Ottignies        | 1         | 5.88%   |
| Nur-Sultan       | 1         | 5.88%   |
| Nowy Wisnicz     | 1         | 5.88%   |
| Kuala Terengganu | 1         | 5.88%   |
| Jette            | 1         | 5.88%   |
| Houston          | 1         | 5.88%   |
| Forest           | 1         | 5.88%   |
| Contrada Tenna   | 1         | 5.88%   |
| Berlin           | 1         | 5.88%   |
| Ashburn          | 1         | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 8         | 10     | 27.59%  |
| WDC                     | 2         | 2      | 6.9%    |
| Unknown                 | 2         | 2      | 6.9%    |
| Toshiba                 | 2         | 2      | 6.9%    |
| Kingston                | 2         | 2      | 6.9%    |
| Union Memory (Shenzhen) | 1         | 1      | 3.45%   |
| UMIS                    | 1         | 2      | 3.45%   |
| StoreJet                | 1         | 1      | 3.45%   |
| SK Hynix                | 1         | 2      | 3.45%   |
| Seagate                 | 1         | 1      | 3.45%   |
| LITEONIT                | 1         | 1      | 3.45%   |
| LITEON                  | 1         | 1      | 3.45%   |
| Intel                   | 1         | 1      | 3.45%   |
| Hitachi                 | 1         | 1      | 3.45%   |
| Fujitsu                 | 1         | 1      | 3.45%   |
| Dogfish                 | 1         | 1      | 3.45%   |
| AGI                     | 1         | 1      | 3.45%   |
| A-DATA Technology       | 1         | 1      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 3.23%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 3.23%   |
| Unknown SD/MMC/MS PRO 32GB                   | 1         | 3.23%   |
| Unknown MMC Card  64GB                       | 1         | 3.23%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 3.23%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 3.23%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 3.23%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 3.23%   |
| StoreJet Disk 2TB                            | 1         | 3.23%   |
| SK Hynix NVMe SSD Drive 512GB                | 1         | 3.23%   |
| SK Hynix BC511 NVMe 512GB                    | 1         | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 3.23%   |
| Samsung SSD 970 EVO 500GB                    | 1         | 3.23%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 3.23%   |
| Samsung SSD 870 EVO 1TB                      | 1         | 3.23%   |
| Samsung SSD 860 QVO 4TB                      | 1         | 3.23%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 3.23%   |
| Samsung NVMe SSD Drive 256GB                 | 1         | 3.23%   |
| Samsung MZVLB512HBJQ-000L7 512GB             | 1         | 3.23%   |
| Samsung MZVLB512HBJQ-000L2 512GB             | 1         | 3.23%   |
| Samsung MZNLN512HAJQ-000H1 512GB SSD         | 1         | 3.23%   |
| LITEONIT LSS-24L6G 24GB SSD                  | 1         | 3.23%   |
| LITEON CV1-DB256 256GB SSD                   | 1         | 3.23%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 3.23%   |
| Kingston NVMe SSD Drive 512GB                | 1         | 3.23%   |
| Intel NVMe SSD Drive 512GB                   | 1         | 3.23%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 3.23%   |
| Fujitsu MHV2080BH 80GB                       | 1         | 3.23%   |
| Dogfish SSD 2TB                              | 1         | 3.23%   |
| AGI AGI960G18AI238 960GB                     | 1         | 3.23%   |
| A-DATA SWORDFISH 1TB                         | 1         | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 2         | 2      | 28.57%  |
| Unknown  | 1         | 1      | 14.29%  |
| StoreJet | 1         | 1      | 14.29%  |
| Seagate  | 1         | 1      | 14.29%  |
| Hitachi  | 1         | 1      | 14.29%  |
| Fujitsu  | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 45.45%  |
| Toshiba             | 2         | 2      | 18.18%  |
| LITEONIT            | 1         | 1      | 9.09%   |
| LITEON              | 1         | 1      | 9.09%   |
| Kingston            | 1         | 1      | 9.09%   |
| Dogfish             | 1         | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 8         | 12     | 34.78%  |
| SSD     | 8         | 12     | 34.78%  |
| HDD     | 5         | 7      | 21.74%  |
| MMC     | 1         | 1      | 4.35%   |
| Unknown | 1         | 1      | 4.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 11        | 17     | 47.83%  |
| NVMe | 8         | 12     | 34.78%  |
| SAS  | 3         | 3      | 13.04%  |
| MMC  | 1         | 1      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 6         | 6      | 37.5%   |
| 0.01-0.5   | 6         | 8      | 37.5%   |
| 1.01-2.0   | 3         | 3      | 18.75%  |
| 3.01-4.0   | 1         | 2      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 7         | 41.18%  |
| 101-250        | 4         | 23.53%  |
| 501-1000       | 2         | 11.76%  |
| More than 3000 | 1         | 5.88%   |
| 2001-3000      | 1         | 5.88%   |
| 1001-2000      | 1         | 5.88%   |
| 51-100         | 1         | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 7         | 41.18%  |
| 21-50     | 3         | 17.65%  |
| 101-250   | 3         | 17.65%  |
| 251-500   | 1         | 5.88%   |
| 1001-2000 | 1         | 5.88%   |
| 501-1000  | 1         | 5.88%   |
| 51-100    | 1         | 5.88%   |

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
| Detected | 12        | 21     | 63.16%  |
| Works    | 7         | 12     | 36.84%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 12        | 54.55%  |
| Samsung Electronics         | 3         | 13.64%  |
| AMD                         | 3         | 13.64%  |
| Union Memory (Shenzhen)     | 1         | 4.55%   |
| SK Hynix                    | 1         | 4.55%   |
| Realtek Semiconductor       | 1         | 4.55%   |
| Kingston Technology Company | 1         | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 12%     |
| AMD FCH SATA Controller [AHCI mode]                                                    | 3         | 12%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 8%      |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 4%      |
| SK Hynix BC511                                                                         | 1         | 4%      |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 4%      |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 4%      |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 4%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 4%      |
| Intel SSD 660P Series                                                                  | 1         | 4%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 4%      |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 4%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 4%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 4%      |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 4%      |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 4%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 4%      |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 4%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 4%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 12        | 52.17%  |
| NVMe | 8         | 34.78%  |
| IDE  | 3         | 13.04%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 12        | 70.59%  |
| AMD    | 5         | 29.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 11.76%  |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 5.88%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 5.88%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 5.88%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 5.88%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 5.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 5.88%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 5.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 5.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 5.88%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 5.88%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 5.88%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics    | 1         | 5.88%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 5.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 5.88%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 8         | 47.06%  |
| Intel Core i5    | 3         | 17.65%  |
| AMD Ryzen 5      | 2         | 11.76%  |
| Other            | 1         | 5.88%   |
| Intel Core 2 Duo | 1         | 5.88%   |
| AMD Ryzen 7      | 1         | 5.88%   |
| AMD Ryzen 5 PRO  | 1         | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 8         | 47.06%  |
| 2      | 5         | 29.41%  |
| 6      | 3         | 17.65%  |
| 8      | 1         | 5.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 14        | 82.35%  |
| 1      | 3         | 17.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 17        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306c3    | 4         | 23.53%  |
| 0x506e3    | 2         | 11.76%  |
| 0x08600104 | 2         | 11.76%  |
| 0xa0652    | 1         | 5.88%   |
| 0x806ec    | 1         | 5.88%   |
| 0x406e3    | 1         | 5.88%   |
| 0x40651    | 1         | 5.88%   |
| 0x206a7    | 1         | 5.88%   |
| 0x10676    | 1         | 5.88%   |
| 0x0a50000c | 1         | 5.88%   |
| 0x08108102 | 1         | 5.88%   |
| 0x06006705 | 1         | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Haswell     | 5         | 29.41%  |
| Skylake     | 3         | 17.65%  |
| Zen 2       | 2         | 11.76%  |
| Zen+        | 1         | 5.88%   |
| Zen 3       | 1         | 5.88%   |
| SandyBridge | 1         | 5.88%   |
| Penryn      | 1         | 5.88%   |
| KabyLake    | 1         | 5.88%   |
| Excavator   | 1         | 5.88%   |
| CometLake   | 1         | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Nvidia | 11        | 42.31%  |
| Intel  | 10        | 38.46%  |
| AMD    | 5         | 19.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 11.54%  |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 7.69%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 2         | 7.69%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 3.85%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 3.85%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 3.85%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 3.85%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 3.85%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 3.85%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 3.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 3.85%   |
| Intel HD Graphics 530                                                     | 1         | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 3.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 3.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 3.85%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                   | 1         | 3.85%   |
| AMD Renoir                                                                | 1         | 3.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 3.85%   |
| AMD Cezanne                                                               | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 7         | 41.18%  |
| 1 x Nvidia     | 3         | 17.65%  |
| 1 x AMD        | 3         | 17.65%  |
| 1 x Intel      | 2         | 11.76%  |
| Intel + AMD    | 1         | 5.88%   |
| AMD + Nvidia   | 1         | 5.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 11        | 64.71%  |
| Proprietary | 6         | 35.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6         | 35.29%  |
| 1.01-2.0   | 3         | 17.65%  |
| 0.01-0.5   | 3         | 17.65%  |
| 5.01-6.0   | 2         | 11.76%  |
| 3.01-4.0   | 2         | 11.76%  |
| 0.51-1.0   | 1         | 5.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 17.86%  |
| LG Display          | 4         | 14.29%  |
| Dell                | 4         | 14.29%  |
| Goldstar            | 3         | 10.71%  |
| BOE                 | 3         | 10.71%  |
| Philips             | 2         | 7.14%   |
| Chimei Innolux      | 2         | 7.14%   |
| Samsung Electronics | 1         | 3.57%   |
| PANDA               | 1         | 3.57%   |
| Panasonic           | 1         | 3.57%   |
| Lenovo              | 1         | 3.57%   |
| AOC                 | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 3.33%   |
| Philips PHL 272S4L PHL08E4 1920x1080 600x340mm 27.2-inch              | 1         | 3.33%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 3.33%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 3.33%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 3.33%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 3.33%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 3.33%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 3.33%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 1         | 3.33%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 3.33%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                     | 1         | 3.33%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 3.33%   |
| Dell S2421HS DEL41F4 1920x1080 530x300mm 24.0-inch                    | 1         | 3.33%   |
| Dell P2715Q DEL40BD 3840x2160 597x336mm 27.0-inch                     | 1         | 3.33%   |
| Dell E2210 DELD036 1680x1050 473x296mm 22.0-inch                      | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 3.33%   |
| BOE LCD Monitor BOE0932 1920x1080 309x174mm 14.0-inch                 | 1         | 3.33%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 3.33%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                 | 1         | 3.33%   |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO203E 1600x900 309x174mm 14.0-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 1         | 3.33%   |
| AOC 2279WH AOC2279 1920x1080 477x268mm 21.5-inch                      | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 13        | 59.09%  |
| 1600x900 (HD+)     | 2         | 9.09%   |
| 3840x2160 (4K)     | 1         | 4.55%   |
| 3440x1440          | 1         | 4.55%   |
| 2560x1440 (QHD)    | 1         | 4.55%   |
| 2560x1080          | 1         | 4.55%   |
| 1920x1200 (WUXGA)  | 1         | 4.55%   |
| 1680x1050 (WSXGA+) | 1         | 4.55%   |
| Unknown            | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 9         | 32.14%  |
| 14     | 5         | 17.86%  |
| 27     | 4         | 14.29%  |
| 21     | 3         | 10.71%  |
| 34     | 2         | 7.14%   |
| 17     | 2         | 7.14%   |
| 24     | 1         | 3.57%   |
| 22     | 1         | 3.57%   |
| 13     | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 15        | 53.57%  |
| 501-600     | 5         | 17.86%  |
| 401-500     | 4         | 14.29%  |
| 701-800     | 2         | 7.14%   |
| 351-400     | 2         | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 16        | 80%     |
| 21/9  | 2         | 10%     |
| 16/10 | 2         | 10%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 33.33%  |
| 81-90          | 6         | 22.22%  |
| 301-350        | 4         | 14.81%  |
| 201-250        | 3         | 11.11%  |
| 351-500        | 2         | 7.41%   |
| 121-130        | 2         | 7.41%   |
| 151-200        | 1         | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 16        | 59.26%  |
| 101-120       | 5         | 18.52%  |
| 51-100        | 4         | 14.81%  |
| More than 240 | 1         | 3.7%    |
| 161-240       | 1         | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 8         | 47.06%  |
| 2     | 6         | 35.29%  |
| 3     | 2         | 11.76%  |
| 4     | 1         | 5.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 51.85%  |
| Realtek Semiconductor | 9         | 33.33%  |
| Qualcomm Atheros      | 2         | 7.41%   |
| MEDIATEK              | 1         | 3.7%    |
| Broadcom              | 1         | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 25.71%  |
| Intel Wireless 7260                                               | 4         | 11.43%  |
| Intel Wireless 8260                                               | 2         | 5.71%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 5.71%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 2.86%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 2.86%   |
| Intel Wireless 7265                                               | 1         | 2.86%   |
| Intel Wireless 3160                                               | 1         | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 2.86%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 2.86%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.86%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 2.86%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 2.86%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.86%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.86%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 82.35%  |
| Realtek Semiconductor | 1         | 5.88%   |
| Qualcomm Atheros      | 1         | 5.88%   |
| MEDIATEK              | 1         | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                           | 4         | 23.53%  |
| Intel Wireless 8260                                           | 2         | 11.76%  |
| Realtek RTL8723DE Wireless Network Adapter                    | 1         | 5.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 1         | 5.88%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 5.88%   |
| Intel Wireless 7265                                           | 1         | 5.88%   |
| Intel Wireless 3160                                           | 1         | 5.88%   |
| Intel Wi-Fi 6 AX200                                           | 1         | 5.88%   |
| Intel Ultimate N WiFi Link 5300                               | 1         | 5.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 5.88%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 1         | 5.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 1         | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 9         | 52.94%  |
| Intel                 | 6         | 35.29%  |
| Qualcomm Atheros      | 1         | 5.88%   |
| Broadcom              | 1         | 5.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 50%     |
| Intel Ethernet Connection I217-LM                                 | 2         | 11.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 5.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 5.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 5.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 5.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 5.56%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 51.52%  |
| Ethernet | 16        | 48.48%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 13        | 50%     |
| Ethernet | 13        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 15        | 88.24%  |
| 3     | 1         | 5.88%   |
| 1     | 1         | 5.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 11        | 64.71%  |
| Yes  | 6         | 35.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 75%     |
| Realtek Semiconductor           | 1         | 6.25%   |
| Qualcomm Atheros Communications | 1         | 6.25%   |
| Foxconn / Hon Hai               | 1         | 6.25%   |
| Broadcom                        | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 9         | 56.25%  |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 1         | 6.25%   |
| Intel AX201 Bluetooth                              | 1         | 6.25%   |
| Intel AX200 Bluetooth                              | 1         | 6.25%   |
| Foxconn / Hon Hai Wireless_Device                  | 1         | 6.25%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 12        | 41.38%  |
| Nvidia              | 8         | 27.59%  |
| AMD                 | 5         | 17.24%  |
| Logitech            | 2         | 6.9%    |
| Conexant Systems    | 1         | 3.45%   |
| C-Media Electronics | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 10.81%  |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 10.81%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 8.11%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 5.41%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 5.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 5.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 5.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 2.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.7%    |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 2.7%    |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 2.7%    |
| Logitech Stereo H650e                                                      | 1         | 2.7%    |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.7%    |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.7%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.7%    |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.7%    |
| Conexant Systems HP Dock Audio                                             | 1         | 2.7%    |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.7%    |
| AMD High Definition Audio Controller                                       | 1         | 2.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 50%     |
| SK Hynix            | 2         | 33.33%  |
| Crucial             | 1         | 16.67%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 16.67%  |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s | 1         | 16.67%  |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 16.67%  |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 16.67%  |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s  | 1         | 16.67%  |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s | 1         | 16.67%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 3         | 50%     |
| DDR3   | 2         | 33.33%  |
| LPDDR4 | 1         | 16.67%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 6         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 4         | 66.67%  |
| 16384 | 2         | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 3         | 50%     |
| 4266  | 1         | 16.67%  |
| 3200  | 1         | 16.67%  |
| 1600  | 1         | 16.67%  |

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


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 6         | 35.29%  |
| Syntek                | 3         | 17.65%  |
| Realtek Semiconductor | 2         | 11.76%  |
| IMC Networks          | 2         | 11.76%  |
| Quanta                | 1         | 5.88%   |
| Logitech              | 1         | 5.88%   |
| Lenovo                | 1         | 5.88%   |
| Intel                 | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Integrated Camera              | 4         | 23.53%  |
| Syntek Lenovo EasyCamera               | 2         | 11.76%  |
| Syntek Integrated Camera               | 1         | 5.88%   |
| Realtek Integrated_Webcam_HD           | 1         | 5.88%   |
| Realtek EasyCamera                     | 1         | 5.88%   |
| Quanta HP Webcam                       | 1         | 5.88%   |
| Logitech BRIO                          | 1         | 5.88%   |
| Lenovo UVC Camera                      | 1         | 5.88%   |
| Intel RealSense 3D Camera (Front F200) | 1         | 5.88%   |
| IMC Networks USB2.0 HD UVC WebCam      | 1         | 5.88%   |
| IMC Networks TOSHIBA Web Camera - HD   | 1         | 5.88%   |
| Chicony HP HD Camera                   | 1         | 5.88%   |
| Chicony HD WebCam                      | 1         | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 75%     |
| AuthenTec        | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader   | 1         | 25%     |
| Validity Sensors VFS Fingerprint sensor      | 1         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 25%     |
| AuthenTec AES2810                            | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 33.33%  |
| Broadcom 58200                       | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader  | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 8         | 47.06%  |
| 1     | 7         | 41.18%  |
| 2     | 2         | 11.76%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 36.36%  |
| Chipcard              | 2         | 18.18%  |
| Net/wireless          | 1         | 9.09%   |
| Net/ethernet          | 1         | 9.09%   |
| Multimedia controller | 1         | 9.09%   |
| Graphics card         | 1         | 9.09%   |
| Card reader           | 1         | 9.09%   |

