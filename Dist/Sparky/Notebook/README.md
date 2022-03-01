Sparky - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Sparky.

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

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | 1000HE                      | [5dd6246e59](https://linux-hardware.org/?probe=5dd6246e59) | Feb 08, 2022 |
| ASUSTek   | S101                        | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| HP        | EliteBook 8770w             | [9a2052fc8c](https://linux-hardware.org/?probe=9a2052fc8c) | Nov 25, 2021 |
| HP        | Pavilion g7                 | [6cebc99fe6](https://linux-hardware.org/?probe=6cebc99fe6) | Nov 22, 2021 |
| Dell      | Inspiron N5010              | [df5e66431b](https://linux-hardware.org/?probe=df5e66431b) | Nov 20, 2021 |
| HP        | EliteBook Folio 9480m       | [dae2e04d45](https://linux-hardware.org/?probe=dae2e04d45) | Oct 04, 2021 |
| Google    | Banon                       | [764debedcd](https://linux-hardware.org/?probe=764debedcd) | Sep 25, 2021 |
| Lenovo    | ThinkPad E15 20RES0GF00     | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Apple     | MacBook1,1                  | [cc415ab6c7](https://linux-hardware.org/?probe=cc415ab6c7) | Mar 15, 2021 |
| Samsung   | NC10                        | [b5909af616](https://linux-hardware.org/?probe=b5909af616) | Mar 11, 2021 |
| Samsung   | NC10                        | [3b8de5559e](https://linux-hardware.org/?probe=3b8de5559e) | Feb 27, 2021 |
| Lenovo    | ThinkPad T61 7659AB7        | [43f03346c5](https://linux-hardware.org/?probe=43f03346c5) | Feb 19, 2021 |
| Beelink   | BT3 PRO                     | [8dbfa4dacd](https://linux-hardware.org/?probe=8dbfa4dacd) | Jan 06, 2021 |
| Beelink   | BT3 PRO                     | [d85a392e02](https://linux-hardware.org/?probe=d85a392e02) | Jan 06, 2021 |
| Samsung   | NC10                        | [8c878860a7](https://linux-hardware.org/?probe=8c878860a7) | Jan 03, 2021 |
| Dell      | Inspiron 5720               | [d360a61780](https://linux-hardware.org/?probe=d360a61780) | Dec 08, 2020 |
| eMachines | E525                        | [0c11b6b4dc](https://linux-hardware.org/?probe=0c11b6b4dc) | Nov 25, 2020 |
| Lenovo    | IdeaPad S206 20154          | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Dell      | Inspiron 5720               | [787263a0c6](https://linux-hardware.org/?probe=787263a0c6) | Oct 10, 2020 |
| HP        | Laptop 17z-ca100            | [2217d0703c](https://linux-hardware.org/?probe=2217d0703c) | Oct 05, 2020 |
| HP        | Laptop 17z-ca100            | [1927ffc179](https://linux-hardware.org/?probe=1927ffc179) | Oct 05, 2020 |
| Apple     | MacBook1,1                  | [73b04f9de4](https://linux-hardware.org/?probe=73b04f9de4) | Aug 26, 2020 |
| Acer      | Aspire 5742G                | [a90fb35c67](https://linux-hardware.org/?probe=a90fb35c67) | May 01, 2020 |
| Lenovo    | ThinkPad T60 2007FUG        | [d552e50d7e](https://linux-hardware.org/?probe=d552e50d7e) | Mar 12, 2020 |
| Dell      | Latitude XT3                | [0944e88882](https://linux-hardware.org/?probe=0944e88882) | Mar 09, 2020 |
| Dell      | Inspiron 5770               | [a3dd71465d](https://linux-hardware.org/?probe=a3dd71465d) | Jan 06, 2020 |
| HP        | Pavilion dv9000 (GA359UA... | [db4a924be0](https://linux-hardware.org/?probe=db4a924be0) | Sep 07, 2019 |
| HP        | Pavilion dv9000 (GA359UA... | [622123c1e6](https://linux-hardware.org/?probe=622123c1e6) | Sep 07, 2019 |
| HP        | Pavilion dv9000 (GA359UA... | [6f024c0dd0](https://linux-hardware.org/?probe=6f024c0dd0) | Sep 03, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.10.0-9-amd64      | 2         | 8.33%   |
| 5.10.0-8-amd64      | 2         | 8.33%   |
| 5.10.0-11-686       | 2         | 8.33%   |
| 4.19.0-8-amd64      | 2         | 8.33%   |
| 4.19.0-13-686       | 2         | 8.33%   |
| 4.19.0-12-amd64     | 2         | 8.33%   |
| 5.9.0-4-amd64       | 1         | 4.17%   |
| 5.8.13-sparky-amd64 | 1         | 4.17%   |
| 5.8.0-2-amd64       | 1         | 4.17%   |
| 5.5.0-2-amd64       | 1         | 4.17%   |
| 5.4.7-sparky-amd64  | 1         | 4.17%   |
| 5.2.0-2-amd64       | 1         | 4.17%   |
| 5.14.0-4-amd64      | 1         | 4.17%   |
| 5.10.4-sparky-amd64 | 1         | 4.17%   |
| 5.10.0-6-amd64      | 1         | 4.17%   |
| 5.10.0-3-amd64      | 1         | 4.17%   |
| 4.19.0-14-686       | 1         | 4.17%   |
| 4.19.0-10-686       | 1         | 4.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 8         | 36.36%  |
| 4.19.0  | 6         | 27.27%  |
| 5.9.0   | 1         | 4.55%   |
| 5.8.13  | 1         | 4.55%   |
| 5.8.0   | 1         | 4.55%   |
| 5.5.0   | 1         | 4.55%   |
| 5.4.7   | 1         | 4.55%   |
| 5.2.0   | 1         | 4.55%   |
| 5.14.0  | 1         | 4.55%   |
| 5.10.4  | 1         | 4.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 9         | 40.91%  |
| 4.19    | 6         | 27.27%  |
| 5.8     | 2         | 9.09%   |
| 5.9     | 1         | 4.55%   |
| 5.5     | 1         | 4.55%   |
| 5.4     | 1         | 4.55%   |
| 5.2     | 1         | 4.55%   |
| 5.14    | 1         | 4.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 17        | 80.95%  |
| i686   | 4         | 19.05%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LXQt    | 7         | 31.82%  |
| XFCE    | 6         | 27.27%  |
| Unknown | 6         | 27.27%  |
| MATE    | 1         | 4.55%   |
| KDE5    | 1         | 4.55%   |
| GNOME   | 1         | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 19        | 86.36%  |
| Tty  | 3         | 13.64%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 6         | 28.57%  |
| Unknown | 5         | 23.81%  |
| SDDM    | 4         | 19.05%  |
| LightDM | 4         | 19.05%  |
| XDM     | 1         | 4.76%   |
| GDM     | 1         | 4.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 8         | 38.1%   |
| pl_PL   | 3         | 14.29%  |
| en_GB   | 3         | 14.29%  |
| Unknown | 2         | 9.52%   |
| ja_JP   | 1         | 4.76%   |
| es_CL   | 1         | 4.76%   |
| en_PH   | 1         | 4.76%   |
| en_CA   | 1         | 4.76%   |
| de_DE   | 1         | 4.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 15        | 71.43%  |
| EFI  | 6         | 28.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 18        | 85.71%  |
| Overlay | 2         | 9.52%   |
| Btrfs   | 1         | 4.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 10        | 47.62%  |
| Unknown | 6         | 28.57%  |
| GPT     | 5         | 23.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 85.71%  |
| Yes       | 3         | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14        | 66.67%  |
| Yes       | 7         | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 23.81%  |
| Lenovo              | 4         | 19.05%  |
| Dell                | 4         | 19.05%  |
| ASUSTek Computer    | 2         | 9.52%   |
| Samsung Electronics | 1         | 4.76%   |
| Google              | 1         | 4.76%   |
| eMachines           | 1         | 4.76%   |
| Beelink             | 1         | 4.76%   |
| Apple               | 1         | 4.76%   |
| Acer                | 1         | 4.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Samsung NC10                     | 1         | 4.76%   |
| Lenovo ThinkPad T61 7659AB7      | 1         | 4.76%   |
| Lenovo ThinkPad T60 2007FUG      | 1         | 4.76%   |
| Lenovo ThinkPad E15 20RES0GF00   | 1         | 4.76%   |
| Lenovo IdeaPad S206 20154        | 1         | 4.76%   |
| HP Pavilion g7                   | 1         | 4.76%   |
| HP Pavilion dv9000 (GA359UA#ABA) | 1         | 4.76%   |
| HP Laptop 17z-ca100              | 1         | 4.76%   |
| HP EliteBook Folio 9480m         | 1         | 4.76%   |
| HP EliteBook 8770w               | 1         | 4.76%   |
| Google Banon                     | 1         | 4.76%   |
| eMachines E525                   | 1         | 4.76%   |
| Dell Latitude XT3                | 1         | 4.76%   |
| Dell Inspiron N5010              | 1         | 4.76%   |
| Dell Inspiron 5770               | 1         | 4.76%   |
| Dell Inspiron 5720               | 1         | 4.76%   |
| Beelink BT3 PRO                  | 1         | 4.76%   |
| ASUS S101                        | 1         | 4.76%   |
| ASUS 1000HE                      | 1         | 4.76%   |
| Apple MacBook1,1                 | 1         | 4.76%   |
| Acer Aspire 5742G                | 1         | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo ThinkPad | 3         | 14.29%  |
| Dell Inspiron   | 3         | 14.29%  |
| HP Pavilion     | 2         | 9.52%   |
| HP EliteBook    | 2         | 9.52%   |
| Samsung NC10    | 1         | 4.76%   |
| Lenovo IdeaPad  | 1         | 4.76%   |
| HP Laptop       | 1         | 4.76%   |
| Google Banon    | 1         | 4.76%   |
| eMachines E525  | 1         | 4.76%   |
| Dell Latitude   | 1         | 4.76%   |
| Beelink BT3     | 1         | 4.76%   |
| ASUS S101       | 1         | 4.76%   |
| ASUS 1000HE     | 1         | 4.76%   |
| Apple MacBook1  | 1         | 4.76%   |
| Acer Aspire     | 1         | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 3         | 14.29%  |
| 2009 | 3         | 14.29%  |
| 2011 | 2         | 9.52%   |
| 2010 | 2         | 9.52%   |
| 2008 | 2         | 9.52%   |
| 2006 | 2         | 9.52%   |
| 2021 | 1         | 4.76%   |
| 2020 | 1         | 4.76%   |
| 2019 | 1         | 4.76%   |
| 2018 | 1         | 4.76%   |
| 2017 | 1         | 4.76%   |
| 2014 | 1         | 4.76%   |
| 2007 | 1         | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 21        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 21        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 95.24%  |
| Yes  | 1         | 4.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 7         | 33.33%  |
| 4.01-8.0   | 4         | 19.05%  |
| 2.01-3.0   | 4         | 19.05%  |
| 1.01-2.0   | 2         | 9.52%   |
| 32.01-64.0 | 1         | 4.76%   |
| 24.01-32.0 | 1         | 4.76%   |
| 16.01-24.0 | 1         | 4.76%   |
| 0.51-1.0   | 1         | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 8         | 36.36%  |
| 1.01-2.0 | 6         | 27.27%  |
| 4.01-8.0 | 2         | 9.09%   |
| 3.01-4.0 | 2         | 9.09%   |
| 2.01-3.0 | 2         | 9.09%   |
| 0.01-0.5 | 2         | 9.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 16        | 76.19%  |
| 2      | 3         | 14.29%  |
| 5      | 1         | 4.76%   |
| 4      | 1         | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11        | 52.38%  |
| Yes       | 10        | 47.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 90.48%  |
| No        | 2         | 9.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 90.48%  |
| No        | 2         | 9.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12        | 57.14%  |
| No        | 9         | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 8         | 38.1%   |
| UK          | 3         | 14.29%  |
| Poland      | 3         | 14.29%  |
| Germany     | 2         | 9.52%   |
| Canada      | 2         | 9.52%   |
| Philippines | 1         | 4.76%   |
| Japan       | 1         | 4.76%   |
| Chile       | 1         | 4.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Wroclaw               | 1         | 4.35%   |
| Wenatchee             | 1         | 4.35%   |
| Tucson                | 1         | 4.35%   |
| Takahama              | 1         | 4.35%   |
| Spokane               | 1         | 4.35%   |
| San Antonio           | 1         | 4.35%   |
| Saint-Basile-le-Grand | 1         | 4.35%   |
| Pompano Beach         | 1         | 4.35%   |
| Pasig                 | 1         | 4.35%   |
| Paisley               | 1         | 4.35%   |
| Nasielsk              | 1         | 4.35%   |
| Montreal              | 1         | 4.35%   |
| Mannheim              | 1         | 4.35%   |
| Leipzig               | 1         | 4.35%   |
| La Florida            | 1         | 4.35%   |
| KoЕ‚o              | 1         | 4.35%   |
| Houston               | 1         | 4.35%   |
| Glasgow               | 1         | 4.35%   |
| East Wenatchee        | 1         | 4.35%   |
| Dunoon                | 1         | 4.35%   |
| Chicago               | 1         | 4.35%   |
| Birmingham            | 1         | 4.35%   |
| Barnsley              | 1         | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 8      | 19.23%  |
| Samsung Electronics | 4         | 4      | 15.38%  |
| Hitachi             | 4         | 5      | 15.38%  |
| WDC                 | 3         | 5      | 11.54%  |
| Unknown             | 2         | 2      | 7.69%   |
| GOODRAM             | 2         | 3      | 7.69%   |
| SPCC                | 1         | 2      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 2      | 3.85%   |
| ASUS-JM             | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Hitachi HTS545025B9A300 250GB            | 2         | 7.14%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 3.57%   |
| WDC WD3200BPVT-75ZEST0 320GB             | 1         | 3.57%   |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 3.57%   |
| Unknown MMC Card  64GB                   | 1         | 3.57%   |
| Unknown HBG4a2  32GB                     | 1         | 3.57%   |
| SPCC Solid State Disk 256GB              | 1         | 3.57%   |
| Seagate ST9500325AS 500GB                | 1         | 3.57%   |
| Seagate ST9160310AS 160GB                | 1         | 3.57%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 3.57%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 3.57%   |
| Seagate Backup+ Hub BK 8TB               | 1         | 3.57%   |
| Seagate Backup+ Desk 3TB                 | 1         | 3.57%   |
| Samsung SSD 840 Series 120GB             | 1         | 3.57%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB   | 1         | 3.57%   |
| Samsung MZALQ512HALU-000L1 512GB         | 1         | 3.57%   |
| Samsung MZ7TD128HAFV-000L1 128GB SSD     | 1         | 3.57%   |
| Micron MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 3.57%   |
| Intel SSDMAEXC024G3H 24GB                | 1         | 3.57%   |
| Hitachi HTS545025B9SA02 250GB            | 1         | 3.57%   |
| Hitachi HTS541080G9SA00 80GB             | 1         | 3.57%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1         | 3.57%   |
| GOODRAM SSDPR-CL100-240-G3 240GB         | 1         | 3.57%   |
| GOODRAM IR-SSDPR-S25A-120 120GB          | 1         | 3.57%   |
| Fujitsu MHW2120BH 120GB                  | 1         | 3.57%   |
| ASUS-JM S41 SSD 16GB                     | 1         | 3.57%   |
| A-DATA SX8200NP 480GB                    | 1         | 3.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 7      | 38.46%  |
| Hitachi | 4         | 5      | 30.77%  |
| WDC     | 3         | 5      | 23.08%  |
| Fujitsu | 1         | 2      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 25%     |
| GOODRAM             | 2         | 3      | 25%     |
| SPCC                | 1         | 2      | 12.5%   |
| Micron Technology   | 1         | 1      | 12.5%   |
| Intel               | 1         | 1      | 12.5%   |
| ASUS-JM             | 1         | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 13        | 19     | 50%     |
| SSD     | 7         | 10     | 26.92%  |
| NVMe    | 3         | 3      | 11.54%  |
| MMC     | 2         | 2      | 7.69%   |
| Unknown | 1         | 1      | 3.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 17        | 26     | 73.91%  |
| NVMe | 3         | 3      | 13.04%  |
| MMC  | 2         | 2      | 8.7%    |
| SAS  | 1         | 4      | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 16        | 24     | 84.21%  |
| 0.51-1.0   | 2         | 2      | 10.53%  |
| 4.01-10.0  | 1         | 3      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 9         | 42.86%  |
| 1-20           | 3         | 14.29%  |
| 251-500        | 2         | 9.52%   |
| 21-50          | 2         | 9.52%   |
| 501-1000       | 2         | 9.52%   |
| More than 3000 | 1         | 4.76%   |
| 1001-2000      | 1         | 4.76%   |
| Unknown        | 1         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 11        | 50%     |
| 51-100         | 3         | 13.64%  |
| 21-50          | 2         | 9.09%   |
| 101-250        | 2         | 9.09%   |
| More than 3000 | 1         | 4.55%   |
| 1001-2000      | 1         | 4.55%   |
| 501-1000       | 1         | 4.55%   |
| Unknown        | 1         | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 1      | 25%     |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 25%     |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 25%     |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 2         | 2      | 50%     |
| Seagate           | 1         | 1      | 25%     |
| Micron Technology | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| SSD  | 1         | 1      | 25%     |

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
| Works    | 10        | 17     | 45.45%  |
| Detected | 8         | 14     | 36.36%  |
| Malfunc  | 4         | 4      | 18.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 16        | 72.73%  |
| Samsung Electronics | 2         | 9.09%   |
| Silicon Motion      | 1         | 4.55%   |
| Nvidia              | 1         | 4.55%   |
| JMicron Technology  | 1         | 4.55%   |
| AMD                 | 1         | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 11.54%  |
| Samsung NVMe SSD Controller 980                                              | 2         | 7.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 2         | 7.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 2         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 2         | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 7.69%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                | 1         | 3.85%   |
| Nvidia MCP51 Serial ATA Controller                                           | 1         | 3.85%   |
| Nvidia MCP51 IDE                                                             | 1         | 3.85%   |
| JMicron JMB360 AHCI Controller                                               | 1         | 3.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 1         | 3.85%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 3.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 3.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 3.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 3.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 14        | 58.33%  |
| IDE  | 7         | 29.17%  |
| NVMe | 3         | 12.5%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 85.71%  |
| AMD    | 3         | 14.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                 | 2         | 9.52%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 1         | 4.76%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 4.76%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 4.76%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 4.76%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 1         | 4.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 4.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 4.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 4.76%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 1         | 4.76%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 1         | 4.76%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 4.76%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 1         | 4.76%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 4.76%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 1         | 4.76%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1         | 4.76%   |
| Intel Atom CPU N280 @ 1.66GHz                 | 1         | 4.76%   |
| AMD Turion 64 X2 Mobile Technology TL-64      | 1         | 4.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1         | 4.76%   |
| AMD C-50 Processor                            | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 4         | 19.05%  |
| Intel Atom              | 4         | 19.05%  |
| Intel Core i7           | 3         | 14.29%  |
| Intel Celeron           | 2         | 9.52%   |
| Intel Pentium           | 1         | 4.76%   |
| Intel Genuine           | 1         | 4.76%   |
| Intel Core i3           | 1         | 4.76%   |
| Intel Core 2 Duo        | 1         | 4.76%   |
| Intel Core 2            | 1         | 4.76%   |
| AMD Turion 64 X2 Mobile | 1         | 4.76%   |
| AMD Ryzen 5             | 1         | 4.76%   |
| AMD C-50                | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 10        | 47.62%  |
| 4      | 7         | 33.33%  |
| 1      | 4         | 19.05%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 12        | 57.14%  |
| 1      | 9         | 42.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 17        | 80.95%  |
| 32-bit         | 4         | 19.05%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4         | 19.05%  |
| 0x406c4    | 2         | 9.52%   |
| 0x306a9    | 2         | 9.52%   |
| 0x206a7    | 2         | 9.52%   |
| 0x20655    | 2         | 9.52%   |
| 0x106c2    | 2         | 9.52%   |
| 0x806ec    | 1         | 4.76%   |
| 0x806ea    | 1         | 4.76%   |
| 0x6f2      | 1         | 4.76%   |
| 0x40651    | 1         | 4.76%   |
| 0x1067a    | 1         | 4.76%   |
| 0x08108109 | 1         | 4.76%   |
| 0x05000029 | 1         | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Bonnell     | 3         | 14.29%  |
| Westmere    | 2         | 9.52%   |
| Silvermont  | 2         | 9.52%   |
| SandyBridge | 2         | 9.52%   |
| KabyLake    | 2         | 9.52%   |
| IvyBridge   | 2         | 9.52%   |
| Core        | 2         | 9.52%   |
| Zen+        | 1         | 4.76%   |
| Penryn      | 1         | 4.76%   |
| P6          | 1         | 4.76%   |
| K8 Hammer   | 1         | 4.76%   |
| Haswell     | 1         | 4.76%   |
| Bobcat      | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 71.43%  |
| Nvidia | 3         | 14.29%  |
| AMD    | 3         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 15.38%  |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 11.54%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 7.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 7.69%   |
| Nvidia GK104GLM [Quadro K3000M]                                                          | 1         | 3.85%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 3.85%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 3.85%   |
| Intel UHD Graphics 620                                                                   | 1         | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 3.85%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 3.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 3.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 3.85%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 3.85%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 3.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| 1 x Intel  | 15        | 71.43%  |
| 1 x Nvidia | 3         | 14.29%  |
| 1 x AMD    | 3         | 14.29%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 20        | 95.24%  |
| Proprietary | 1         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 76.19%  |
| 1.01-2.0   | 2         | 9.52%   |
| 0.01-0.5   | 2         | 9.52%   |
| 0.51-1.0   | 1         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 5         | 23.81%  |
| AU Optronics        | 3         | 14.29%  |
| Lenovo              | 2         | 9.52%   |
| CPT                 | 2         | 9.52%   |
| Chimei Innolux      | 2         | 9.52%   |
| Samsung Electronics | 1         | 4.76%   |
| LG Philips          | 1         | 4.76%   |
| Insignia            | 1         | 4.76%   |
| Hitachi             | 1         | 4.76%   |
| HannStar            | 1         | 4.76%   |
| BOE                 | 1         | 4.76%   |
| Apple               | 1         | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 1         | 4.76%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch          | 1         | 4.76%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 4.76%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch         | 1         | 4.76%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch          | 1         | 4.76%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 4.76%   |
| LG Display LCD Monitor LGD01C5 1366x768 293x165mm 13.2-inch          | 1         | 4.76%   |
| Lenovo LCD Monitor LEN4033 1440x900 303x190mm 14.1-inch              | 1         | 4.76%   |
| Lenovo LCD Monitor LEN4022 1400x1050 287x215mm 14.1-inch             | 1         | 4.76%   |
| Insignia NS-32D312NA15 BBY0032 1680x1050 640x384mm 29.4-inch         | 1         | 4.76%   |
| Hitachi HDMI    HEC0088 1920x1080 1100x560mm 48.6-inch               | 1         | 4.76%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch             | 1         | 4.76%   |
| CPT LCD Monitor CPT04CE 1024x600 222x130mm 10.1-inch                 | 1         | 4.76%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                 | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x174mm 14.0-inch      | 1         | 4.76%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch        | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 1         | 4.76%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 1         | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 5         | 23.81%  |
| 1366x768 (WXGA)  | 4         | 19.05%  |
| 1600x900 (HD+)   | 3         | 14.29%  |
| 1024x600         | 3         | 14.29%  |
| 1920x540         | 2         | 9.52%   |
| 1440x900 (WXGA+) | 2         | 9.52%   |
| 1400x1050        | 1         | 4.76%   |
| 1280x800 (WXGA)  | 1         | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 17     | 6         | 28.57%  |
| 15     | 5         | 23.81%  |
| 14     | 3         | 14.29%  |
| 10     | 3         | 14.29%  |
| 48     | 2         | 9.52%   |
| 13     | 2         | 9.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 7         | 33.33%  |
| 351-400     | 6         | 28.57%  |
| 201-300     | 6         | 28.57%  |
| 1001-1500   | 2         | 9.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 15        | 71.43%  |
| 16/10 | 3         | 14.29%  |
| 1.96  | 2         | 9.52%   |
| 4/3   | 1         | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 121-130        | 5         | 23.81%  |
| 101-110        | 5         | 23.81%  |
| 41-50          | 3         | 14.29%  |
| 81-90          | 2         | 9.52%   |
| 71-80          | 2         | 9.52%   |
| 501-1000       | 2         | 9.52%   |
| 131-140        | 1         | 4.76%   |
| 91-100         | 1         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 10        | 47.62%  |
| 121-160 | 8         | 38.1%   |
| 1-50    | 2         | 9.52%   |
| 51-100  | 1         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 9         | 29.03%  |
| Realtek Semiconductor    | 7         | 22.58%  |
| Qualcomm Atheros         | 7         | 22.58%  |
| Marvell Technology Group | 2         | 6.45%   |
| Broadcom Limited         | 2         | 6.45%   |
| TP-Link                  | 1         | 3.23%   |
| Ralink                   | 1         | 3.23%   |
| Nvidia                   | 1         | 3.23%   |
| Broadcom                 | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 10.26%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 3         | 7.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 5.13%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 5.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 5.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 5.13%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 2.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 2.56%   |
| Nvidia MCP51 Ethernet Controller                                        | 1         | 2.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 2.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 2.56%   |
| Intel Wireless 7265                                                     | 1         | 2.56%   |
| Intel Wireless 7260                                                     | 1         | 2.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 2.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 2.56%   |
| Intel Ethernet Connection I218-LM                                       | 1         | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 2.56%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 2.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 2.56%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.56%   |
| Intel 82573L Gigabit Ethernet Controller                                | 1         | 2.56%   |
| Intel 82566MM Gigabit Network Connection                                | 1         | 2.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 1         | 2.56%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 2.56%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 2.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 45%     |
| Qualcomm Atheros      | 6         | 30%     |
| Broadcom Limited      | 2         | 10%     |
| TP-Link               | 1         | 5%      |
| Realtek Semiconductor | 1         | 5%      |
| Ralink                | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 10%     |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 10%     |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 5%      |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 5%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 5%      |
| Intel Wireless 7265                                                     | 1         | 5%      |
| Intel Wireless 7260                                                     | 1         | 5%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 5%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 5%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 5%      |
| Intel Centrino Wireless-N 2230                                          | 1         | 5%      |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 5%      |
| Intel Centrino Ultimate-N 6300                                          | 1         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 5%      |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 5%      |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 7         | 36.84%  |
| Intel                    | 5         | 26.32%  |
| Qualcomm Atheros         | 3         | 15.79%  |
| Marvell Technology Group | 2         | 10.53%  |
| Nvidia                   | 1         | 5.26%   |
| Broadcom                 | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 21.05%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 15.79%  |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 10.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 10.53%  |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 5.26%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 5.26%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 5.26%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 5.26%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.26%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 5.26%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 5.26%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 50%     |
| Ethernet | 19        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 64%     |
| Ethernet | 9         | 36%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 17        | 80.95%  |
| 1     | 4         | 19.05%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 86.36%  |
| Yes  | 3         | 13.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4         | 33.33%  |
| Broadcom                        | 3         | 25%     |
| Realtek Semiconductor           | 1         | 8.33%   |
| Qualcomm Atheros Communications | 1         | 8.33%   |
| Dell                            | 1         | 8.33%   |
| ASUSTek Computer                | 1         | 8.33%   |
| Apple                           | 1         | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 2         | 16.67%  |
| Realtek  Bluetooth 4.2 Adapter                   | 1         | 8.33%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 8.33%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 8.33%   |
| Intel AX201 Bluetooth                            | 1         | 8.33%   |
| Dell Wireless 365 Bluetooth                      | 1         | 8.33%   |
| Broadcom HP Portable SoftSailing                 | 1         | 8.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller] | 1         | 8.33%   |
| Broadcom BCM2045 Bluetooth                       | 1         | 8.33%   |
| ASUS Broadcom Bluetooth 2.1                      | 1         | 8.33%   |
| Apple Bluetooth HCI                              | 1         | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 17        | 77.27%  |
| Nvidia | 3         | 13.64%  |
| AMD    | 2         | 9.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 20%     |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 8%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 8%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 8%      |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 4%      |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 4%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 4%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 4%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 4%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 4%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 4%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 4%      |
| Intel 8 Series HD Audio Controller                                                                | 1         | 4%      |
| AMD Wrestler HDMI Audio                                                                           | 1         | 4%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 4%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 22.22%  |
| Unknown             | 3         | 16.67%  |
| SK Hynix            | 3         | 16.67%  |
| Nanya Technology    | 2         | 11.11%  |
| Micron Technology   | 2         | 11.11%  |
| Kingston            | 1         | 5.56%   |
| GOODRAM             | 1         | 5.56%   |
| G.Skill             | 1         | 5.56%   |
| Corsair             | 1         | 5.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                         | 1         | 5%      |
| Unknown RAM Module 2048MB SODIMM 800MT/s                    | 1         | 5%      |
| Unknown RAM Module 1024MB SODIMM DDR2                       | 1         | 5%      |
| Unknown RAM Module 1024MB SODIMM 800MT/s                    | 1         | 5%      |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                | 1         | 5%      |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 5%      |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 1         | 5%      |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 1         | 5%      |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s       | 1         | 5%      |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s       | 1         | 5%      |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s       | 1         | 5%      |
| Samsung RAM K4E8E324EB-EGCF 2048MB LPDDR3 1600MT/s          | 1         | 5%      |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s        | 1         | 5%      |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 1         | 5%      |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s       | 1         | 5%      |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s      | 1         | 5%      |
| Kingston RAM ACR128X64D3S1333C9 1024MB SODIMM DDR3 1333MT/s | 1         | 5%      |
| GOODRAM RAM GR1600S3V64L11/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 5%      |
| G.Skill RAM F4-2400C16-16GRS 16GB SODIMM DDR4 2667MT/s      | 1         | 5%      |
| Corsair RAM CMSA4GX3M1A1333C9 4GB SODIMM DDR3 1333MT/s      | 1         | 5%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 9         | 56.25%  |
| SDRAM   | 2         | 12.5%   |
| DDR4    | 2         | 12.5%   |
| LPDDR3  | 1         | 6.25%   |
| DDR2    | 1         | 6.25%   |
| Unknown | 1         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SODIMM  | 14        | 93.33%  |
| Unknown | 1         | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 6         | 31.58%  |
| 4096  | 5         | 26.32%  |
| 8192  | 3         | 15.79%  |
| 1024  | 3         | 15.79%  |
| 16384 | 2         | 10.53%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 6         | 35.29%  |
| 2667    | 2         | 11.76%  |
| 1334    | 2         | 11.76%  |
| 1333    | 2         | 11.76%  |
| Unknown | 2         | 11.76%  |
| 4199    | 1         | 5.88%   |
| 1066    | 1         | 5.88%   |
| 800     | 1         | 5.88%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 7         | 43.75%  |
| Microdia                      | 3         | 18.75%  |
| Sunplus Innovation Technology | 2         | 12.5%   |
| Z-Star Microelectronics       | 1         | 6.25%   |
| Suyin                         | 1         | 6.25%   |
| Microsoft                     | 1         | 6.25%   |
| Acer                          | 1         | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Namuga 1.3M Webcam                                   | 1         | 6.25%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 6.25%   |
| Sunplus Integrated Webcam                                   | 1         | 6.25%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 6.25%   |
| Microsoft LifeCam Cinema                                    | 1         | 6.25%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 6.25%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 6.25%   |
| Microdia Laptop_Integrated_Webcam_1.3M                      | 1         | 6.25%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 6.25%   |
| Chicony HP TrueVision HD Camera                             | 1         | 6.25%   |
| Chicony HP Integrated Webcam                                | 1         | 6.25%   |
| Chicony HP HD Webcam                                        | 1         | 6.25%   |
| Chicony HD WebCam                                           | 1         | 6.25%   |
| Chicony Asus Integrated 0.3M UVC Webcam                     | 1         | 6.25%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 6.25%   |
| Acer Lenovo EasyCamera                                      | 1         | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 1         | 50%     |
| STMicroelectronics | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Validity Sensors VFS491               | 1         | 50%     |
| STMicroelectronics Fingerprint Reader | 1         | 50%     |

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


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 15        | 71.43%  |
| 1     | 4         | 19.05%  |
| 2     | 2         | 9.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 2         | 25%     |
| Multimedia controller | 2         | 25%     |
| Fingerprint reader    | 2         | 25%     |
| Graphics card         | 1         | 12.5%   |
| Chipcard              | 1         | 12.5%   |

