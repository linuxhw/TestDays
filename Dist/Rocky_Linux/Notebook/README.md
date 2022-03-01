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

| Vendor  | Model                       | Probe                                                      | Date         |
|---------|-----------------------------|------------------------------------------------------------|--------------|
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

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 20%     |
| 4.18.0-305.el8.x86_64        | 2         | 13.33%  |
| 4.18.0-305.3.1.el8_4.x86_64  | 2         | 13.33%  |
| 4.18.0-305.25.1.el8_4.x86_64 | 2         | 13.33%  |
| 4.18.0-305.10.2.el8_4.x86_64 | 2         | 13.33%  |
| 5.4.157-1.el8.elrepo.x86_64  | 1         | 6.67%   |
| 4.18.0-348.el8.0.2.x86_64    | 1         | 6.67%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 1         | 6.67%   |
| 4.18.0-240.22.1.el8.x86_64   | 1         | 6.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 14        | 93.33%  |
| 5.4.157 | 1         | 6.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 14        | 93.33%  |
| 5.4     | 1         | 6.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 15        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 10        | 66.67%  |
| XFCE          | 1         | 6.67%   |
| X-Cinnamon    | 1         | 6.67%   |
| MATE          | 1         | 6.67%   |
| KDE5          | 1         | 6.67%   |
| GNOME Classic | 1         | 6.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 8         | 53.33%  |
| Wayland | 7         | 46.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 9         | 60%     |
| GDM     | 3         | 20%     |
| LightDM | 2         | 13.33%  |
| SDDM    | 1         | 6.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 11        | 73.33%  |
| de_DE | 2         | 13.33%  |
| it_IT | 1         | 6.67%   |
| en_ZA | 1         | 6.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 10        | 66.67%  |
| BIOS | 5         | 33.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 10        | 66.67%  |
| Ext4 | 5         | 33.33%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 11        | 73.33%  |
| GPT     | 4         | 26.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 15        | 100%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 13        | 86.67%  |
| Yes       | 2         | 13.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 9         | 60%     |
| Toshiba          | 2         | 13.33%  |
| Hewlett-Packard  | 2         | 13.33%  |
| ASUSTek Computer | 1         | 6.67%   |
| Acer             | 1         | 6.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Toshiba TECRA W50-A                      | 1         | 6.67%   |
| Toshiba Satellite E45-B                  | 1         | 6.67%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 6.67%   |
| Lenovo ThinkPad W500 406132G             | 1         | 6.67%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 6.67%   |
| Lenovo Legion Y7000 2020H 81Y7           | 1         | 6.67%   |
| Lenovo Legion 5 15ARH05H 82B1            | 1         | 6.67%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 6.67%   |
| Lenovo IdeaPad Y410P 20216               | 1         | 6.67%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS      | 1         | 6.67%   |
| Lenovo IdeaPad 500S-14ISK 80Q3           | 1         | 6.67%   |
| HP ZBook 15 G3                           | 1         | 6.67%   |
| HP Laptop 17-ca1xxx                      | 1         | 6.67%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 1         | 6.67%   |
| Acer Aspire VN7-591G                     | 1         | 6.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 4         | 26.67%  |
| Lenovo ThinkPad   | 3         | 20%     |
| Lenovo Legion     | 2         | 13.33%  |
| Toshiba TECRA     | 1         | 6.67%   |
| Toshiba Satellite | 1         | 6.67%   |
| HP ZBook          | 1         | 6.67%   |
| HP Laptop         | 1         | 6.67%   |
| ASUS ASUS         | 1         | 6.67%   |
| Acer Aspire       | 1         | 6.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 3         | 20%     |
| 2014 | 3         | 20%     |
| 2019 | 2         | 13.33%  |
| 2016 | 2         | 13.33%  |
| 2018 | 1         | 6.67%   |
| 2015 | 1         | 6.67%   |
| 2013 | 1         | 6.67%   |
| 2011 | 1         | 6.67%   |
| 2009 | 1         | 6.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 15        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 15        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 15        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 4         | 26.67%  |
| 8.01-16.0  | 4         | 26.67%  |
| 32.01-64.0 | 3         | 20%     |
| 16.01-24.0 | 3         | 20%     |
| 3.01-4.0   | 1         | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 3.01-4.0  | 5         | 33.33%  |
| 4.01-8.0  | 3         | 20%     |
| 2.01-3.0  | 3         | 20%     |
| 1.01-2.0  | 3         | 20%     |
| 8.01-16.0 | 1         | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 8         | 53.33%  |
| 2      | 4         | 26.67%  |
| 3      | 3         | 20%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 12        | 80%     |
| Yes       | 3         | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 93.33%  |
| No        | 1         | 6.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 93.33%  |
| No        | 1         | 6.67%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 5         | 33.33%  |
| Germany      | 2         | 13.33%  |
| South Africa | 1         | 6.67%   |
| Poland       | 1         | 6.67%   |
| Malaysia     | 1         | 6.67%   |
| Kazakhstan   | 1         | 6.67%   |
| Italy        | 1         | 6.67%   |
| Czechia      | 1         | 6.67%   |
| China        | 1         | 6.67%   |
| Belgium      | 1         | 6.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Xi'an            | 1         | 6.67%   |
| Weinheim         | 1         | 6.67%   |
| Scarborough      | 1         | 6.67%   |
| San Ramon        | 1         | 6.67%   |
| Pretoria         | 1         | 6.67%   |
| Prague           | 1         | 6.67%   |
| Nur-Sultan       | 1         | 6.67%   |
| Nowy Wisnicz     | 1         | 6.67%   |
| Kuala Terengganu | 1         | 6.67%   |
| Jette            | 1         | 6.67%   |
| Houston          | 1         | 6.67%   |
| Forest           | 1         | 6.67%   |
| Contrada Tenna   | 1         | 6.67%   |
| Berlin           | 1         | 6.67%   |
| Ashburn          | 1         | 6.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 7         | 9      | 25.93%  |
| WDC                     | 2         | 2      | 7.41%   |
| Unknown                 | 2         | 2      | 7.41%   |
| Toshiba                 | 2         | 2      | 7.41%   |
| Kingston                | 2         | 2      | 7.41%   |
| Union Memory (Shenzhen) | 1         | 1      | 3.7%    |
| UMIS                    | 1         | 2      | 3.7%    |
| StoreJet                | 1         | 1      | 3.7%    |
| Seagate                 | 1         | 1      | 3.7%    |
| LITEONIT                | 1         | 1      | 3.7%    |
| LITEON                  | 1         | 1      | 3.7%    |
| Intel                   | 1         | 1      | 3.7%    |
| Hitachi                 | 1         | 1      | 3.7%    |
| Fujitsu                 | 1         | 1      | 3.7%    |
| Dogfish                 | 1         | 1      | 3.7%    |
| AGI                     | 1         | 1      | 3.7%    |
| A-DATA Technology       | 1         | 1      | 3.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| WDC WD10SPCX-24HWST1 1TB                     | 1         | 3.57%   |
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 3.57%   |
| Unknown SD/MMC/MS PRO 64GB                   | 1         | 3.57%   |
| Unknown MMC Card  64GB                       | 1         | 3.57%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 3.57%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 3.57%   |
| Toshiba THNSNJ512GACU 512GB SSD              | 1         | 3.57%   |
| Toshiba THNSNJ128G8NU 128GB SSD              | 1         | 3.57%   |
| StoreJet Disk 4TB                            | 1         | 3.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 3.57%   |
| Samsung SSD 970 EVO 500GB                    | 1         | 3.57%   |
| Samsung SSD 870 QVO 2TB                      | 1         | 3.57%   |
| Samsung SSD 870 EVO 1TB                      | 1         | 3.57%   |
| Samsung SSD 860 QVO 4TB                      | 1         | 3.57%   |
| Samsung SSD 860 EVO 500GB                    | 1         | 3.57%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB       | 1         | 3.57%   |
| Samsung MZVLB512HBJQ-000L2 512GB             | 1         | 3.57%   |
| Samsung MZNLN512HAJQ-000H1 512GB SSD         | 1         | 3.57%   |
| LITEONIT LSS-24L6G 24GB SSD                  | 1         | 3.57%   |
| LITEON CV1-DB256 256GB SSD                   | 1         | 3.57%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 3.57%   |
| Kingston NVMe SSD Drive 512GB                | 1         | 3.57%   |
| Intel NVMe SSD Drive 512GB                   | 1         | 3.57%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 3.57%   |
| Fujitsu MHV2080BH 80GB                       | 1         | 3.57%   |
| Dogfish SSD 2TB                              | 1         | 3.57%   |
| AGI AGI960G18AI238 960GB                     | 1         | 3.57%   |
| A-DATA SWORDFISH 1TB                         | 1         | 3.57%   |

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
| SSD     | 8         | 12     | 38.1%   |
| NVMe    | 6         | 9      | 28.57%  |
| HDD     | 5         | 7      | 23.81%  |
| MMC     | 1         | 1      | 4.76%   |
| Unknown | 1         | 1      | 4.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 11        | 17     | 52.38%  |
| NVMe | 6         | 9      | 28.57%  |
| SAS  | 3         | 3      | 14.29%  |
| MMC  | 1         | 1      | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 6         | 6      | 37.5%   |
| 0.01-0.5   | 6         | 8      | 37.5%   |
| 3.01-4.0   | 2         | 3      | 12.5%   |
| 1.01-2.0   | 2         | 2      | 12.5%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 5         | 33.33%  |
| 101-250        | 4         | 26.67%  |
| 501-1000       | 2         | 13.33%  |
| More than 3000 | 1         | 6.67%   |
| 2001-3000      | 1         | 6.67%   |
| 1001-2000      | 1         | 6.67%   |
| 51-100         | 1         | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 6         | 40%     |
| 21-50     | 3         | 20%     |
| 101-250   | 2         | 13.33%  |
| 251-500   | 1         | 6.67%   |
| 1001-2000 | 1         | 6.67%   |
| 501-1000  | 1         | 6.67%   |
| 51-100    | 1         | 6.67%   |

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
| Detected | 11        | 20     | 68.75%  |
| Works    | 5         | 10     | 31.25%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 12        | 60%     |
| AMD                         | 3         | 15%     |
| Samsung Electronics         | 2         | 10%     |
| Union Memory (Shenzhen)     | 1         | 5%      |
| Realtek Semiconductor       | 1         | 5%      |
| Kingston Technology Company | 1         | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 13.04%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 3         | 13.04%  |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 4.35%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 4.35%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 4.35%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 4.35%   |
| Intel SSD 660P Series                                                                  | 1         | 4.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 4.35%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 4.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 1         | 4.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 4.35%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 4.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 4.35%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 4.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 4.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 12        | 57.14%  |
| NVMe | 6         | 28.57%  |
| IDE  | 3         | 14.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 11        | 73.33%  |
| AMD    | 4         | 26.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 13.33%  |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 6.67%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 6.67%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 6.67%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 6.67%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 6.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 6.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 6.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 6.67%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 1         | 6.67%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 1         | 6.67%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 1         | 6.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 6.67%   |
| AMD A9-9420e RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 6.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 8         | 53.33%  |
| Intel Core i5    | 2         | 13.33%  |
| AMD Ryzen 5      | 2         | 13.33%  |
| Other            | 1         | 6.67%   |
| Intel Core 2 Duo | 1         | 6.67%   |
| AMD Ryzen 7      | 1         | 6.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 7         | 46.67%  |
| 2      | 5         | 33.33%  |
| 6      | 2         | 13.33%  |
| 8      | 1         | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 15        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 80%     |
| 1      | 3         | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 15        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306c3    | 4         | 26.67%  |
| 0x506e3    | 2         | 13.33%  |
| 0x08600104 | 2         | 13.33%  |
| 0xa0652    | 1         | 6.67%   |
| 0x406e3    | 1         | 6.67%   |
| 0x40651    | 1         | 6.67%   |
| 0x206a7    | 1         | 6.67%   |
| 0x10676    | 1         | 6.67%   |
| 0x08108102 | 1         | 6.67%   |
| 0x06006705 | 1         | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Haswell     | 5         | 33.33%  |
| Skylake     | 3         | 20%     |
| Zen 2       | 2         | 13.33%  |
| Zen+        | 1         | 6.67%   |
| SandyBridge | 1         | 6.67%   |
| Penryn      | 1         | 6.67%   |
| Excavator   | 1         | 6.67%   |
| CometLake   | 1         | 6.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Nvidia | 11        | 45.83%  |
| Intel  | 9         | 37.5%   |
| AMD    | 4         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 12.5%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 8.33%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 2         | 8.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 4.17%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 4.17%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 4.17%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 4.17%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 4.17%   |
| Nvidia GK107M [GeForce GT 755M]                                           | 1         | 4.17%   |
| Nvidia GF119M [Quadro NVS 4200M]                                          | 1         | 4.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 4.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 4.17%   |
| Intel HD Graphics 530                                                     | 1         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 4.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 4.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 4.17%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                   | 1         | 4.17%   |
| AMD Renoir                                                                | 1         | 4.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 7         | 46.67%  |
| 1 x Nvidia     | 3         | 20%     |
| 1 x AMD        | 2         | 13.33%  |
| Intel + AMD    | 1         | 6.67%   |
| 1 x Intel      | 1         | 6.67%   |
| AMD + Nvidia   | 1         | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 9         | 60%     |
| Proprietary | 6         | 40%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5         | 33.33%  |
| 1.01-2.0   | 3         | 20%     |
| 0.01-0.5   | 3         | 20%     |
| 5.01-6.0   | 2         | 13.33%  |
| 3.01-4.0   | 2         | 13.33%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 4         | 17.39%  |
| AU Optronics        | 4         | 17.39%  |
| Goldstar            | 3         | 13.04%  |
| Philips             | 2         | 8.7%    |
| Dell                | 2         | 8.7%    |
| Chimei Innolux      | 2         | 8.7%    |
| Samsung Electronics | 1         | 4.35%   |
| PANDA               | 1         | 4.35%   |
| Panasonic           | 1         | 4.35%   |
| Lenovo              | 1         | 4.35%   |
| BOE                 | 1         | 4.35%   |
| AOC                 | 1         | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 4.17%   |
| Philips PHL 272S4L PHL08E4 1920x1080 600x340mm 27.2-inch              | 1         | 4.17%   |
| Philips PHL 271S7Q PHL090A 1920x1080 600x340mm 27.2-inch              | 1         | 4.17%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 4.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 4.17%   |
| Panasonic VVX10T025J00 MEI96A2 2560x1600 223x125mm 10.1-inch          | 1         | 4.17%   |
| LG Display LCD Monitor LGD04D5 1920x1080 344x194mm 15.5-inch          | 1         | 4.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 1         | 4.17%   |
| LG Display LCD Monitor LGD0406 1920x1080 309x175mm 14.0-inch          | 1         | 4.17%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 4.17%   |
| Lenovo LCD Monitor LEN4055 1920x1200 331x207mm 15.4-inch              | 1         | 4.17%   |
| Goldstar LG UltraFine GSM5B11                                         | 1         | 4.17%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 1         | 4.17%   |
| Goldstar 32ML600 GSM772D 1920x1080 480x270mm 21.7-inch                | 1         | 4.17%   |
| Dell S2740L DELA08E 1920x1080 598x336mm 27.0-inch                     | 1         | 4.17%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                     | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 1         | 4.17%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 1         | 4.17%   |
| AU Optronics LCD Monitor AUOB78D 1920x1080 344x193mm 15.5-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO203E 1600x900 309x174mm 14.0-inch         | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 1         | 4.17%   |
| AOC 2279WH AOC2279 1920x1080 477x268mm 21.5-inch                      | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 11        | 61.11%  |
| 1600x900 (HD+)    | 2         | 11.11%  |
| 3840x2160 (4K)    | 1         | 5.56%   |
| 2560x1440 (QHD)   | 1         | 5.56%   |
| 2560x1080         | 1         | 5.56%   |
| 1920x1200 (WUXGA) | 1         | 5.56%   |
| Unknown           | 1         | 5.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 8         | 34.78%  |
| 27     | 4         | 17.39%  |
| 14     | 4         | 17.39%  |
| 21     | 3         | 13.04%  |
| 17     | 2         | 8.7%    |
| 34     | 1         | 4.35%   |
| 13     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 56.52%  |
| 501-600     | 4         | 17.39%  |
| 401-500     | 3         | 13.04%  |
| 351-400     | 2         | 8.7%    |
| 701-800     | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 14        | 87.5%   |
| 21/9  | 1         | 6.25%   |
| 16/10 | 1         | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 8         | 34.78%  |
| 81-90          | 5         | 21.74%  |
| 301-350        | 4         | 17.39%  |
| 201-250        | 2         | 8.7%    |
| 121-130        | 2         | 8.7%    |
| 351-500        | 1         | 4.35%   |
| 151-200        | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 14        | 60.87%  |
| 101-120       | 4         | 17.39%  |
| 51-100        | 3         | 13.04%  |
| More than 240 | 1         | 4.35%   |
| 161-240       | 1         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 8         | 53.33%  |
| 2     | 5         | 33.33%  |
| 3     | 2         | 13.33%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 54.17%  |
| Realtek Semiconductor | 8         | 33.33%  |
| Qualcomm Atheros      | 2         | 8.33%   |
| Broadcom              | 1         | 4.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 26.67%  |
| Intel Wireless 7260                                               | 4         | 13.33%  |
| Intel Wireless 8260                                               | 2         | 6.67%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 6.67%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 3.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 3.33%   |
| Intel Wireless 7265                                               | 1         | 3.33%   |
| Intel Wireless 3160                                               | 1         | 3.33%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 3.33%   |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 3.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 3.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.33%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 3.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 86.67%  |
| Realtek Semiconductor | 1         | 6.67%   |
| Qualcomm Atheros      | 1         | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                        | 4         | 26.67%  |
| Intel Wireless 8260                                        | 2         | 13.33%  |
| Realtek RTL8723DE Wireless Network Adapter                 | 1         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 1         | 6.67%   |
| Intel Wireless 7265                                        | 1         | 6.67%   |
| Intel Wireless 3160                                        | 1         | 6.67%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 6.67%   |
| Intel Ultimate N WiFi Link 5300                            | 1         | 6.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 6.67%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 6.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 1         | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 8         | 53.33%  |
| Intel                 | 5         | 33.33%  |
| Qualcomm Atheros      | 1         | 6.67%   |
| Broadcom              | 1         | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 53.33%  |
| Intel Ethernet Connection I217-LM                                 | 2         | 13.33%  |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 6.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 6.67%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 6.67%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 6.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 51.72%  |
| Ethernet | 14        | 48.28%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 12        | 50%     |
| Ethernet | 12        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 13        | 86.67%  |
| 3     | 1         | 6.67%   |
| 1     | 1         | 6.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 9         | 60%     |
| Yes  | 6         | 40%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 78.57%  |
| Realtek Semiconductor           | 1         | 7.14%   |
| Qualcomm Atheros Communications | 1         | 7.14%   |
| Broadcom                        | 1         | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 7         | 50%     |
| Intel Bluetooth Device                             | 2         | 14.29%  |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                 | 1         | 7.14%   |
| Intel AX201 Bluetooth                              | 1         | 7.14%   |
| Intel AX200 Bluetooth                              | 1         | 7.14%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 11        | 40.74%  |
| Nvidia              | 8         | 29.63%  |
| AMD                 | 4         | 14.81%  |
| Logitech            | 2         | 7.41%   |
| Conexant Systems    | 1         | 3.7%    |
| C-Media Electronics | 1         | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 11.76%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 8.82%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 8.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 5.88%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 5.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 5.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 2.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 2.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 2.94%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 2.94%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1         | 2.94%   |
| Logitech Stereo H650e                                                      | 1         | 2.94%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.94%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.94%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 2.94%   |
| Conexant Systems HP Dock Audio                                             | 1         | 2.94%   |
| C-Media Electronics USB Advanced Audio Device                              | 1         | 2.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.94%   |
| AMD High Definition Audio Controller                                       | 1         | 2.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| SK Hynix            | 1         | 25%     |
| Crucial             | 1         | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s  | 1         | 25%     |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s      | 1         | 25%     |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 25%     |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s | 1         | 25%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| DDR4 | 2         | 50%     |
| DDR3 | 2         | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 4         | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 3         | 75%     |
| 16384 | 1         | 25%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 2         | 50%     |
| 3200  | 1         | 25%     |
| 1600  | 1         | 25%     |

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
| Chicony Electronics   | 5         | 33.33%  |
| Syntek                | 3         | 20%     |
| IMC Networks          | 2         | 13.33%  |
| Realtek Semiconductor | 1         | 6.67%   |
| Quanta                | 1         | 6.67%   |
| Logitech              | 1         | 6.67%   |
| Lenovo                | 1         | 6.67%   |
| Intel                 | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Integrated Camera              | 3         | 20%     |
| Syntek Lenovo EasyCamera               | 2         | 13.33%  |
| Syntek Integrated Camera               | 1         | 6.67%   |
| Realtek EasyCamera                     | 1         | 6.67%   |
| Quanta HP Webcam                       | 1         | 6.67%   |
| Logitech BRIO Ultra HD Webcam          | 1         | 6.67%   |
| Lenovo UVC Camera                      | 1         | 6.67%   |
| Intel RealSense 3D Camera (Front F200) | 1         | 6.67%   |
| IMC Networks USB2.0 HD UVC WebCam      | 1         | 6.67%   |
| IMC Networks TOSHIBA Web Camera - HD   | 1         | 6.67%   |
| Chicony HP HD Camera                   | 1         | 6.67%   |
| Chicony HD WebCam                      | 1         | 6.67%   |

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


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| O2 Micro | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 8         | 53.33%  |
| 1     | 6         | 40%     |
| 2     | 1         | 6.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 4         | 50%     |
| Multimedia controller | 1         | 12.5%   |
| Graphics card         | 1         | 12.5%   |
| Chipcard              | 1         | 12.5%   |
| Card reader           | 1         | 12.5%   |

