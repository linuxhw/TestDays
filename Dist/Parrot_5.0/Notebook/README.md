Parrot 5.0 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Parrot 5.0.

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

Total: 48

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| MSI       | Modern 15 A5M               | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware | M14xR1                      | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP        | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ASUSTek   | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| MSI       | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| ASUSTek   | X75VC                       | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper    | EZbook                      | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple     | MacBookAir3,1               | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox   | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple     | MacBookPro11,4              | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell      | Inspiron 5570               | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| Dell      | Latitude XT2                | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Jumper    | EZbook                      | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple     | MacBookPro11,4              | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Jumper    | EZbook                      | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi     | GemiBook                    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Samsung   | 550P5C/550P7C               | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Toshiba   | Satellite C75D-B            | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer      | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi     | GemiBook                    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer      | Nitro AN515-54              | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| HP        | ProBook 4535s               | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP        | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple     | MacBook7,1                  | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple     | MacBook7,1                  | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Dell      | Inspiron N5110              | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo    | ThinkPad T480 20L6SCYP00    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| Acer      | Aspire A315-21              | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Dell      | Latitude 7480               | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| Lenovo    | ThinkPad E14 20RA0016GE     | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo    | IdeaPad Y580                | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo    | IdeaPad Y580                | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell      | Latitude E6410              | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| Acer      | TravelMate 5720             | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP        | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| HP        | Pavilion g7                 | [d27bb0d31e](https://linux-hardware.org/?probe=d27bb0d31e) | Oct 31, 2021 |
| Lenovo    | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo    | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| HP        | Pavilion g7                 | [b386e97faa](https://linux-hardware.org/?probe=b386e97faa) | Oct 25, 2021 |
| Dell      | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell      | Latitude E7450              | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| HP        | Laptop 15q-dy0xxx           | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| HP        | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP        | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP        | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| HP        | EliteBook 840 G3            | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64  | 20        | 57.14%  |
| 5.14.0-2parrot1-amd64  | 6         | 17.14%  |
| 5.16.0-12parrot1-amd64 | 5         | 14.29%  |
| 5.15.0-15parrot1-amd64 | 3         | 8.57%   |
| 5.15.0-5parrot1-amd64  | 1         | 2.86%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 25        | 73.53%  |
| 5.16.0  | 5         | 14.71%  |
| 5.15.0  | 4         | 11.76%  |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 25        | 73.53%  |
| 5.16    | 5         | 14.71%  |
| 5.15    | 4         | 11.76%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 34        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| MATE    | 21        | 61.76%  |
| KDE5    | 11        | 32.35%  |
| KDE     | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 34        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 52.94%  |
| LightDM | 16        | 47.06%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 17        | 50%     |
| en_GB | 5         | 14.71%  |
| ru_RU | 2         | 5.88%   |
| es_ES | 2         | 5.88%   |
| en_IN | 2         | 5.88%   |
| fr_FR | 1         | 2.94%   |
| es_MX | 1         | 2.94%   |
| en_ZA | 1         | 2.94%   |
| en_AU | 1         | 2.94%   |
| de_DE | 1         | 2.94%   |
| cs_CZ | 1         | 2.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 24        | 70.59%  |
| EFI  | 10        | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 30        | 88.24%  |
| Ext4    | 3         | 8.82%   |
| Overlay | 1         | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 18        | 52.94%  |
| GPT     | 9         | 26.47%  |
| MBR     | 7         | 20.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 30        | 88.24%  |
| Yes       | 4         | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 24        | 70.59%  |
| Yes       | 10        | 29.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 17.65%  |
| Dell                | 6         | 17.65%  |
| Lenovo              | 5         | 14.71%  |
| Acer                | 4         | 11.76%  |
| ASUSTek Computer    | 3         | 8.82%   |
| MSI                 | 2         | 5.88%   |
| Apple               | 2         | 5.88%   |
| Toshiba             | 1         | 2.94%   |
| Samsung Electronics | 1         | 2.94%   |
| Metabox             | 1         | 2.94%   |
| Jumper              | 1         | 2.94%   |
| Chuwi               | 1         | 2.94%   |
| Alienware           | 1         | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                           | 2         | 5.88%   |
| HP Notebook                                 | 2         | 5.88%   |
| Toshiba Satellite C75D-B                    | 1         | 2.94%   |
| Samsung 550P5C/550P7C                       | 1         | 2.94%   |
| Metabox Edge-Pro NS50MU                     | 1         | 2.94%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 2.94%   |
| Lenovo ThinkPad T480 20L6SCYP00             | 1         | 2.94%   |
| Lenovo ThinkPad E14 20RA0016GE              | 1         | 2.94%   |
| Lenovo IdeaPad Y580                         | 1         | 2.94%   |
| Lenovo B50-80 80EW                          | 1         | 2.94%   |
| Jumper EZbook                               | 1         | 2.94%   |
| HP ProBook 4535s                            | 1         | 2.94%   |
| HP Pavilion g7                              | 1         | 2.94%   |
| HP Laptop 15q-dy0xxx                        | 1         | 2.94%   |
| HP EliteBook 840 G3                         | 1         | 2.94%   |
| Dell Latitude XT2                           | 1         | 2.94%   |
| Dell Latitude E7450                         | 1         | 2.94%   |
| Dell Latitude E6410                         | 1         | 2.94%   |
| Dell Latitude 7480                          | 1         | 2.94%   |
| Dell Inspiron N5110                         | 1         | 2.94%   |
| Dell Inspiron 5570                          | 1         | 2.94%   |
| Chuwi GemiBook                              | 1         | 2.94%   |
| ASUS X75VC                                  | 1         | 2.94%   |
| ASUS X540SAA                                | 1         | 2.94%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR        | 1         | 2.94%   |
| Apple MacBookAir3,1                         | 1         | 2.94%   |
| Apple MacBook7,1                            | 1         | 2.94%   |
| Alienware M14xR1                            | 1         | 2.94%   |
| Acer TravelMate 5720                        | 1         | 2.94%   |
| Acer Nitro AN517-41                         | 1         | 2.94%   |
| Acer Nitro AN515-54                         | 1         | 2.94%   |
| Acer Aspire A315-21                         | 1         | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Latitude     | 4         | 11.76%  |
| Lenovo ThinkPad   | 3         | 8.82%   |
| MSI Modern        | 2         | 5.88%   |
| HP Notebook       | 2         | 5.88%   |
| Dell Inspiron     | 2         | 5.88%   |
| Acer Nitro        | 2         | 5.88%   |
| Toshiba Satellite | 1         | 2.94%   |
| Samsung 550P5C    | 1         | 2.94%   |
| Metabox Edge-Pro  | 1         | 2.94%   |
| Lenovo IdeaPad    | 1         | 2.94%   |
| Lenovo B50-80     | 1         | 2.94%   |
| Jumper EZbook     | 1         | 2.94%   |
| HP ProBook        | 1         | 2.94%   |
| HP Pavilion       | 1         | 2.94%   |
| HP Laptop         | 1         | 2.94%   |
| HP EliteBook      | 1         | 2.94%   |
| Chuwi GemiBook    | 1         | 2.94%   |
| ASUS X75VC        | 1         | 2.94%   |
| ASUS X540SAA      | 1         | 2.94%   |
| ASUS VivoBook     | 1         | 2.94%   |
| Apple MacBookAir3 | 1         | 2.94%   |
| Apple MacBook7    | 1         | 2.94%   |
| Alienware M14xR1  | 1         | 2.94%   |
| Acer TravelMate   | 1         | 2.94%   |
| Acer Aspire       | 1         | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 5         | 14.71%  |
| 2016 | 4         | 11.76%  |
| 2011 | 4         | 11.76%  |
| 2018 | 3         | 8.82%   |
| 2017 | 3         | 8.82%   |
| 2010 | 3         | 8.82%   |
| 2020 | 2         | 5.88%   |
| 2019 | 2         | 5.88%   |
| 2014 | 2         | 5.88%   |
| 2012 | 2         | 5.88%   |
| 2015 | 1         | 2.94%   |
| 2013 | 1         | 2.94%   |
| 2009 | 1         | 2.94%   |
| 2007 | 1         | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 34        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 34        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 9         | 26.47%  |
| 3.01-4.0    | 7         | 20.59%  |
| 8.01-16.0   | 7         | 20.59%  |
| 32.01-64.0  | 5         | 14.71%  |
| 16.01-24.0  | 3         | 8.82%   |
| 64.01-256.0 | 2         | 5.88%   |
| 1.01-2.0    | 1         | 2.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 14        | 41.18%  |
| 1.01-2.0  | 10        | 29.41%  |
| 4.01-8.0  | 5         | 14.71%  |
| 3.01-4.0  | 2         | 5.88%   |
| 8.01-16.0 | 2         | 5.88%   |
| 0.51-1.0  | 1         | 2.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 64.71%  |
| 2      | 11        | 32.35%  |
| 3      | 1         | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 61.76%  |
| Yes       | 13        | 38.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 85.29%  |
| No        | 5         | 14.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 85.29%  |
| No        | 5         | 14.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 12        | 35.29%  |
| UK           | 4         | 11.76%  |
| Spain        | 2         | 5.88%   |
| India        | 2         | 5.88%   |
| Denmark      | 2         | 5.88%   |
| South Africa | 1         | 2.94%   |
| Russia       | 1         | 2.94%   |
| Netherlands  | 1         | 2.94%   |
| Morocco      | 1         | 2.94%   |
| Mexico       | 1         | 2.94%   |
| Germany      | 1         | 2.94%   |
| Georgia      | 1         | 2.94%   |
| France       | 1         | 2.94%   |
| Czechia      | 1         | 2.94%   |
| Austria      | 1         | 2.94%   |
| Australia    | 1         | 2.94%   |
| Algeria      | 1         | 2.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Camden               | 2         | 5.88%   |
| Vienna               | 1         | 2.94%   |
| Ts'khinvali          | 1         | 2.94%   |
| Tangier              | 1         | 2.94%   |
| St Petersburg        | 1         | 2.94%   |
| Spotsylvania         | 1         | 2.94%   |
| Skive                | 1         | 2.94%   |
| Seattle              | 1         | 2.94%   |
| Saint Clair          | 1         | 2.94%   |
| Ruskin               | 1         | 2.94%   |
| Pretoria             | 1         | 2.94%   |
| Prague               | 1         | 2.94%   |
| Phoenix              | 1         | 2.94%   |
| Orofino              | 1         | 2.94%   |
| Mt. Pleasant         | 1         | 2.94%   |
| Mostoles             | 1         | 2.94%   |
| Melbourne            | 1         | 2.94%   |
| MazatlÃ¡n          | 1         | 2.94%   |
| Mangalagiri          | 1         | 2.94%   |
| Los Angeles          | 1         | 2.94%   |
| Islington            | 1         | 2.94%   |
| Houston              | 1         | 2.94%   |
| Dillon               | 1         | 2.94%   |
| Copenhagen           | 1         | 2.94%   |
| City of Saint Peters | 1         | 2.94%   |
| Cannes               | 1         | 2.94%   |
| Bristol              | 1         | 2.94%   |
| Birmingham           | 1         | 2.94%   |
| Berlin               | 1         | 2.94%   |
| Bengaluru            | 1         | 2.94%   |
| Amsterdam            | 1         | 2.94%   |
| Algiers              | 1         | 2.94%   |
| AlcalÃ¡ de Henares | 1         | 2.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 8      | 18.18%  |
| Kingston            | 6         | 6      | 13.64%  |
| Samsung Electronics | 4         | 4      | 9.09%   |
| Seagate             | 3         | 3      | 6.82%   |
| Sandisk             | 3         | 4      | 6.82%   |
| WDC                 | 2         | 2      | 4.55%   |
| Hitachi             | 2         | 2      | 4.55%   |
| Crucial             | 2         | 2      | 4.55%   |
| China               | 2         | 2      | 4.55%   |
| Unknown             | 1         | 2      | 2.27%   |
| Team                | 1         | 1      | 2.27%   |
| PNY                 | 1         | 1      | 2.27%   |
| Phison              | 1         | 1      | 2.27%   |
| Netac               | 1         | 1      | 2.27%   |
| KingSpec            | 1         | 1      | 2.27%   |
| Intenso             | 1         | 2      | 2.27%   |
| HUAWEI              | 1         | 1      | 2.27%   |
| HGST                | 1         | 1      | 2.27%   |
| BHT                 | 1         | 1      | 2.27%   |
| ASMedia             | 1         | 1      | 2.27%   |
| Apple               | 1         | 1      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                       | 3         | 6.52%   |
| Toshiba MQ01ABD075 752GB                     | 2         | 4.35%   |
| Kingston SV300S37A120G 120GB SSD             | 2         | 4.35%   |
| Kingston NVMe SSD Drive 512GB                | 2         | 4.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 1         | 2.17%   |
| WDC WD6400BPVT-75HXZT1 640GB                 | 1         | 2.17%   |
| Unknown SD  128GB                            | 1         | 2.17%   |
| Unknown ISOCOM  64GB                         | 1         | 2.17%   |
| Toshiba MQ01ACF050 500GB                     | 1         | 2.17%   |
| Toshiba MK2555GSXF 250GB                     | 1         | 2.17%   |
| Toshiba MK2533GSGF 250GB                     | 1         | 2.17%   |
| Team TM8PS7512G 512GB SSD                    | 1         | 2.17%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 2.17%   |
| Seagate ST2000LM003 HN-M201RAD 2TB           | 1         | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 2.17%   |
| SanDisk SDSSDH3 2T00 2TB                     | 1         | 2.17%   |
| Sandisk NVMe SSD Drive 256GB                 | 1         | 2.17%   |
| Sandisk NVMe SSD Drive 1TB                   | 1         | 2.17%   |
| Sandisk NVMe SSD Drive 1024GB                | 1         | 2.17%   |
| Samsung NVMe SSD Drive 1024GB                | 1         | 2.17%   |
| Samsung MZVLB1T0HBLR-000L7 1TB               | 1         | 2.17%   |
| Samsung MZNLN256HMHQ-000H1 256GB SSD         | 1         | 2.17%   |
| Samsung MZMPC032HBCD-000L1 32GB SSD          | 1         | 2.17%   |
| PNY CS900 240GB SSD                          | 1         | 2.17%   |
| Phison Metabox Performance 2TB PCIe NVME SSD | 1         | 2.17%   |
| Netac S535N8/256 256GB                       | 1         | 2.17%   |
| Kingston SKC600512G 512GB SSD                | 1         | 2.17%   |
| Kingston SA2000M81000G 1TB                   | 1         | 2.17%   |
| KingSpec NT-1TB SSD                          | 1         | 2.17%   |
| Intenso SSD SATAIII 512GB                    | 1         | 2.17%   |
| HUAWEI SD Storage 2GB                        | 1         | 2.17%   |
| Hitachi HTS542525K9SA00 250GB                | 1         | 2.17%   |
| Hitachi HTS542520K9SA00 200GB                | 1         | 2.17%   |
| HGST HTS541010A9E680 1TB                     | 1         | 2.17%   |
| Crucial CT500MX500SSD4 500GB                 | 1         | 2.17%   |
| Crucial CT250MX500SSD1 250GB                 | 1         | 2.17%   |
| China SSD 240GB                              | 1         | 2.17%   |
| China SATA SSD 240GB                         | 1         | 2.17%   |
| BHT WR202HH032G E70290F5 32GB SSD            | 1         | 2.17%   |
| ASMedia USB 3.0 Device 2TB                   | 1         | 2.17%   |
| Apple SSD TS064C 64GB                        | 1         | 2.17%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 8         | 8      | 50%     |
| Seagate | 3         | 3      | 18.75%  |
| Hitachi | 2         | 2      | 12.5%   |
| WDC     | 1         | 1      | 6.25%   |
| HGST    | 1         | 1      | 6.25%   |
| ASMedia | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 3         | 3      | 16.67%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| Crucial             | 2         | 2      | 11.11%  |
| China               | 2         | 2      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| Team                | 1         | 1      | 5.56%   |
| SanDisk             | 1         | 1      | 5.56%   |
| PNY                 | 1         | 1      | 5.56%   |
| Netac               | 1         | 1      | 5.56%   |
| KingSpec            | 1         | 1      | 5.56%   |
| Intenso             | 1         | 2      | 5.56%   |
| BHT                 | 1         | 1      | 5.56%   |
| Apple               | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 17        | 19     | 41.46%  |
| HDD     | 15        | 16     | 36.59%  |
| NVMe    | 7         | 9      | 17.07%  |
| MMC     | 1         | 2      | 2.44%   |
| Unknown | 1         | 1      | 2.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 34     | 73.68%  |
| NVMe | 7         | 9      | 18.42%  |
| SAS  | 2         | 2      | 5.26%   |
| MMC  | 1         | 2      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 19     | 53.13%  |
| 0.51-1.0   | 12        | 13     | 37.5%   |
| 1.01-2.0   | 3         | 3      | 9.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 9         | 26.47%  |
| 1001-2000  | 8         | 23.53%  |
| 501-1000   | 7         | 20.59%  |
| Unknown    | 4         | 11.76%  |
| 251-500    | 2         | 5.88%   |
| 2001-3000  | 2         | 5.88%   |
| 1-20       | 1         | 2.94%   |
| 51-100     | 1         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 21-50    | 11        | 32.35%  |
| 51-100   | 7         | 20.59%  |
| 251-500  | 4         | 11.76%  |
| Unknown  | 4         | 11.76%  |
| 101-250  | 3         | 8.82%   |
| 1-20     | 3         | 8.82%   |
| 501-1000 | 2         | 5.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 20        | 27     | 54.05%  |
| Works    | 16        | 19     | 43.24%  |
| Malfunc  | 1         | 1      | 2.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 21        | 56.76%  |
| AMD                         | 6         | 16.22%  |
| Kingston Technology Company | 3         | 8.11%   |
| Sandisk                     | 2         | 5.41%   |
| Samsung Electronics         | 2         | 5.41%   |
| Nvidia                      | 2         | 5.41%   |
| Phison Electronics          | 1         | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 14.29%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 14.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 7.14%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 4.76%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 4.76%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 4.76%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 4.76%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 2.38%   |
| Phison E12 NVMe Controller                                                       | 1         | 2.38%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 2.38%   |
| Nvidia MCP89 SATA Controller                                                     | 1         | 2.38%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 2.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.38%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 2.38%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 2.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 2.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 2.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1         | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 20        | 52.63%  |
| NVMe | 7         | 18.42%  |
| RAID | 6         | 15.79%  |
| IDE  | 5         | 13.16%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 76.47%  |
| AMD    | 8         | 23.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-2430M CPU @ 2.40GHz            | 2         | 5.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics       | 2         | 5.88%   |
| Intel Core i7-8650U CPU @ 1.90GHz            | 1         | 2.94%   |
| Intel Core i7-6600U CPU @ 2.60GHz            | 1         | 2.94%   |
| Intel Core i7-5600U CPU @ 2.60GHz            | 1         | 2.94%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 2.94%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 1         | 2.94%   |
| Intel Core i7-10850H CPU @ 2.70GHz           | 1         | 2.94%   |
| Intel Core i5-9300H CPU @ 2.40GHz            | 1         | 2.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 1         | 2.94%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 1         | 2.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 2.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 1         | 2.94%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 2.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 1         | 2.94%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 1         | 2.94%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 2.94%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 1         | 2.94%   |
| Intel Core 2 Duo CPU U9600 @ 1.60GHz         | 1         | 2.94%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz         | 1         | 2.94%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz         | 1         | 2.94%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz         | 1         | 2.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz            | 1         | 2.94%   |
| Intel Celeron CPU N3350 @ 1.10GHz            | 1         | 2.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 1         | 2.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 1         | 2.94%   |
| AMD Ryzen 7 5800H with Radeon Graphics       | 1         | 2.94%   |
| AMD E2-7110 APU with AMD Radeon R2 Graphics  | 1         | 2.94%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 2.94%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 1         | 2.94%   |
| AMD A6-3420M APU with Radeon HD Graphics     | 1         | 2.94%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 10        | 29.41%  |
| Intel Core i7    | 6         | 17.65%  |
| Intel Core 2 Duo | 4         | 11.76%  |
| Intel Celeron    | 3         | 8.82%   |
| AMD Ryzen 7      | 3         | 8.82%   |
| Other            | 2         | 5.88%   |
| Intel Core i3    | 2         | 5.88%   |
| AMD A6           | 2         | 5.88%   |
| AMD E2           | 1         | 2.94%   |
| AMD A4           | 1         | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 19        | 55.88%  |
| 4      | 11        | 32.35%  |
| 8      | 3         | 8.82%   |
| 6      | 1         | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 22        | 64.71%  |
| 1      | 12        | 35.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 34        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 50%     |
| 0x806e9    | 3         | 8.82%   |
| 0x306a9    | 2         | 5.88%   |
| 0x1067a    | 2         | 5.88%   |
| 0x07030105 | 2         | 5.88%   |
| 0xa0652    | 1         | 2.94%   |
| 0x906ed    | 1         | 2.94%   |
| 0x806ea    | 1         | 2.94%   |
| 0x706a8    | 1         | 2.94%   |
| 0x506c9    | 1         | 2.94%   |
| 0x406e3    | 1         | 2.94%   |
| 0x206a7    | 1         | 2.94%   |
| 0x03000027 | 1         | 2.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 7         | 20.59%  |
| Penryn        | 4         | 11.76%  |
| SandyBridge   | 3         | 8.82%   |
| IvyBridge     | 3         | 8.82%   |
| Puma          | 2         | 5.88%   |
| Excavator     | 2         | 5.88%   |
| Broadwell     | 2         | 5.88%   |
| Unknown       | 2         | 5.88%   |
| Zen 3         | 1         | 2.94%   |
| Westmere      | 1         | 2.94%   |
| TigerLake     | 1         | 2.94%   |
| Skylake       | 1         | 2.94%   |
| Silvermont    | 1         | 2.94%   |
| K10 Llano     | 1         | 2.94%   |
| Goldmont plus | 1         | 2.94%   |
| Goldmont      | 1         | 2.94%   |
| CometLake     | 1         | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 55.81%  |
| AMD    | 10        | 23.26%  |
| Nvidia | 9         | 20.93%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 3         | 6.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 6.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 6.67%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 4.44%   |
| Intel UHD Graphics 620                                                                   | 2         | 4.44%   |
| Intel HD Graphics 5500                                                                   | 2         | 4.44%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 4.44%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 4.44%   |
| AMD Lucienne                                                                             | 2         | 4.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 2.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 2.22%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 2.22%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 2.22%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 2.22%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 2.22%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 2.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 2.22%   |
| Intel HD Graphics 500                                                                    | 1         | 2.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 2.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2.22%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 2.22%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 2.22%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 1         | 2.22%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 2.22%   |
| AMD Cezanne                                                                              | 1         | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 47.06%  |
| Intel + Nvidia | 6         | 17.65%  |
| 1 x AMD        | 6         | 17.65%  |
| 1 x Nvidia     | 2         | 5.88%   |
| Intel + AMD    | 2         | 5.88%   |
| 2 x AMD        | 1         | 2.94%   |
| AMD + Nvidia   | 1         | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 33        | 97.06%  |
| Proprietary | 1         | 2.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 76.47%  |
| 1.01-2.0   | 3         | 8.82%   |
| 0.01-0.5   | 3         | 8.82%   |
| 3.01-4.0   | 1         | 2.94%   |
| 0.51-1.0   | 1         | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 26.32%  |
| BOE                     | 6         | 15.79%  |
| LG Display              | 5         | 13.16%  |
| Chimei Innolux          | 5         | 13.16%  |
| Chi Mei Optoelectronics | 3         | 7.89%   |
| Samsung Electronics     | 2         | 5.26%   |
| Apple                   | 2         | 5.26%   |
| Unknown (AAA)           | 1         | 2.63%   |
| ONN                     | 1         | 2.63%   |
| Lenovo                  | 1         | 2.63%   |
| Kogan                   | 1         | 2.63%   |
| CSO                     | 1         | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 2         | 5.26%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch                 | 1         | 2.63%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch        | 1         | 2.63%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch     | 1         | 2.63%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                     | 1         | 2.63%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch             | 1         | 2.63%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0292 1366x768 309x174mm 14.0-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch              | 1         | 2.63%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 1         | 2.63%   |
| Lenovo D27-30 LEN66B8 1920x1080 597x336mm 27.0-inch                      | 1         | 2.63%   |
| Kogan KAMN27F7TA KGN0270 1920x1080 600x330mm 27.0-inch                   | 1         | 2.63%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 2.63%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 2.63%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 1         | 2.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 1         | 2.63%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 1         | 2.63%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 2.63%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 2.63%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                     | 1         | 2.63%   |
| AU Optronics LCD Monitor AUOA114 1280x800 261x163mm 12.1-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch            | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 1         | 2.63%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.63%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 1         | 2.63%   |
| Apple Color LCD APP9CC0 1280x800 261x163mm 12.1-inch                     | 1         | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 13        | 38.24%  |
| 1366x768 (WXGA)  | 11        | 32.35%  |
| 1600x900 (HD+)   | 4         | 11.76%  |
| 1280x800 (WXGA)  | 3         | 8.82%   |
| 3840x2160 (4K)   | 1         | 2.94%   |
| 2160x1440        | 1         | 2.94%   |
| 1440x900 (WXGA+) | 1         | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 15        | 40.54%  |
| 17     | 5         | 13.51%  |
| 13     | 5         | 13.51%  |
| 14     | 4         | 10.81%  |
| 27     | 2         | 5.41%   |
| 12     | 2         | 5.41%   |
| 40     | 1         | 2.7%    |
| 31     | 1         | 2.7%    |
| 21     | 1         | 2.7%    |
| 11     | 1         | 2.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 62.16%  |
| 351-400     | 5         | 13.51%  |
| 201-300     | 4         | 10.81%  |
| 501-600     | 2         | 5.41%   |
| 801-900     | 1         | 2.7%    |
| 601-700     | 1         | 2.7%    |
| 401-500     | 1         | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 28        | 84.85%  |
| 16/10 | 4         | 12.12%  |
| 3/2   | 1         | 3.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 15        | 40.54%  |
| 81-90          | 8         | 21.62%  |
| 121-130        | 4         | 10.81%  |
| 61-70          | 2         | 5.41%   |
| 301-350        | 2         | 5.41%   |
| 71-80          | 1         | 2.7%    |
| 51-60          | 1         | 2.7%    |
| 351-500        | 1         | 2.7%    |
| 201-250        | 1         | 2.7%    |
| 131-140        | 1         | 2.7%    |
| 501-1000       | 1         | 2.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 15        | 40.54%  |
| 101-120       | 14        | 37.84%  |
| 51-100        | 5         | 13.51%  |
| More than 240 | 1         | 2.7%    |
| 1-50          | 1         | 2.7%    |
| 161-240       | 1         | 2.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 28        | 82.35%  |
| 2     | 5         | 14.71%  |
| 3     | 1         | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 19        | 31.67%  |
| Intel                 | 17        | 28.33%  |
| Qualcomm Atheros      | 8         | 13.33%  |
| Broadcom              | 5         | 8.33%   |
| MEDIATEK              | 3         | 5%      |
| Samsung Electronics   | 1         | 1.67%   |
| Ralink                | 1         | 1.67%   |
| Nvidia                | 1         | 1.67%   |
| NetGear               | 1         | 1.67%   |
| Linksys               | 1         | 1.67%   |
| Huawei Technologies   | 1         | 1.67%   |
| Broadcom Limited      | 1         | 1.67%   |
| ASIX Electronics      | 1         | 1.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 7         | 9.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 9.72%   |
| Intel Wireless 3165                                                     | 3         | 4.17%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2         | 2.78%   |
| Realtek 802.11ac NIC                                                    | 2         | 2.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 2.78%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                           | 2         | 2.78%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 2.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 2.78%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 1.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.39%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 1.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 1.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 1.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.39%   |
| Nvidia MCP89 Ethernet                                                   | 1         | 1.39%   |
| NetGear A6210                                                           | 1         | 1.39%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.39%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 1.39%   |
| Intel Wireless 8260                                                     | 1         | 1.39%   |
| Intel Wireless 3160                                                     | 1         | 1.39%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.39%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.39%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.39%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.39%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.39%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.39%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.39%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                                | 1         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                                | 1         | 1.39%   |
| Huawei Broadband stick                                                  | 1         | 1.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 1         | 1.39%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 1         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.39%   |
| ASIX AX88772A Fast Ethernet                                             | 1         | 1.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 39.02%  |
| Realtek Semiconductor | 9         | 21.95%  |
| Qualcomm Atheros      | 5         | 12.2%   |
| Broadcom              | 4         | 9.76%   |
| MEDIATEK              | 3         | 7.32%   |
| Ralink                | 1         | 2.44%   |
| NetGear               | 1         | 2.44%   |
| Linksys               | 1         | 2.44%   |
| Broadcom Limited      | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                                     | 3         | 7.32%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2         | 4.88%   |
| Realtek 802.11ac NIC                                                    | 2         | 4.88%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                           | 2         | 4.88%   |
| Intel Wireless 8265 / 8275                                              | 2         | 4.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 4.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.44%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.44%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 2.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 2.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.44%   |
| NetGear A6210                                                           | 1         | 2.44%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 2.44%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 2.44%   |
| Intel Wireless 8260                                                     | 1         | 2.44%   |
| Intel Wireless 3160                                                     | 1         | 2.44%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 2.44%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 2.44%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 2.44%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 2.44%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 2.44%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 2.44%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 2.44%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 1         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 55.17%  |
| Intel                 | 6         | 20.69%  |
| Qualcomm Atheros      | 3         | 10.34%  |
| Samsung Electronics   | 1         | 3.45%   |
| Nvidia                | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |
| ASIX Electronics      | 1         | 3.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 23.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 23.33%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 6.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 6.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 3.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 3.33%   |
| Nvidia MCP89 Ethernet                                             | 1         | 3.33%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.33%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.33%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.33%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 34        | 53.97%  |
| Ethernet | 28        | 44.44%  |
| Modem    | 1         | 1.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 63.64%  |
| Ethernet | 16        | 36.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 73.53%  |
| 1     | 8         | 23.53%  |
| 3     | 1         | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 76.47%  |
| Yes  | 8         | 23.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 44.83%  |
| Realtek Semiconductor           | 2         | 6.9%    |
| Qualcomm Atheros Communications | 2         | 6.9%    |
| MediaTek                        | 2         | 6.9%    |
| Lite-On Technology              | 2         | 6.9%    |
| IMC Networks                    | 2         | 6.9%    |
| Apple                           | 2         | 6.9%    |
| Toshiba                         | 1         | 3.45%   |
| Ralink                          | 1         | 3.45%   |
| Foxconn / Hon Hai               | 1         | 3.45%   |
| Broadcom                        | 1         | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 7         | 24.14%  |
| Intel AX201 Bluetooth                            | 3         | 10.34%  |
| MediaTek Wireless_Device                         | 2         | 6.9%    |
| Toshiba BCM43142A0                               | 1         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                   | 1         | 3.45%   |
| Realtek Bluetooth Radio                          | 1         | 3.45%   |
| Ralink RT3290 Bluetooth                          | 1         | 3.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 1         | 3.45%   |
| Qualcomm Atheros AR3011 Bluetooth                | 1         | 3.45%   |
| Lite-On Wireless_Device                          | 1         | 3.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 1         | 3.45%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 3.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 3.45%   |
| Intel AX200 Bluetooth                            | 1         | 3.45%   |
| IMC Networks Bluetooth Radio                     | 1         | 3.45%   |
| IMC Networks Bluetooth Device                    | 1         | 3.45%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth    | 1         | 3.45%   |
| Broadcom BCM20702A0                              | 1         | 3.45%   |
| Apple Bluetooth USB Host Controller              | 1         | 3.45%   |
| Apple Bluetooth Host Controller                  | 1         | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 63.16%  |
| AMD    | 8         | 21.05%  |
| Nvidia | 6         | 15.79%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 12.77%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 6.38%   |
| AMD FCH Azalia Controller                                                                         | 3         | 6.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 6.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 4.26%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 4.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 4.26%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 4.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 4.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 4.26%   |
| AMD High Definition Audio Controller                                                              | 2         | 4.26%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 4.26%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 2.13%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 2.13%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 2.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 2.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 2.13%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 2.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 30.43%  |
| Micron Technology   | 4         | 17.39%  |
| SK Hynix            | 3         | 13.04%  |
| Crucial             | 3         | 13.04%  |
| Unknown (ABCD)      | 2         | 8.7%    |
| Elpida              | 2         | 8.7%    |
| Ramaxel Technology  | 1         | 4.35%   |
| Kingston            | 1         | 4.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 8.33%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 8.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 8.33%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 4.17%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 4.17%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s           | 1         | 4.17%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 4.17%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 4.17%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 4.17%   |
| Samsung RAM M378B2873CZ0-CF7 1GB SODIMM DDR3 800MT/s                | 1         | 4.17%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 4.17%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s            | 1         | 4.17%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s                | 1         | 4.17%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 1         | 4.17%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s               | 1         | 4.17%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                | 1         | 4.17%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 1         | 4.17%   |
| Elpida RAM Module 1GB SODIMM DDR3 1067MT/s                          | 1         | 4.17%   |
| Crucial RAM CT8G4SFS8266.M8FD 8GB SODIMM DDR4 2667MT/s              | 1         | 4.17%   |
| Crucial RAM CT16G4SFD832A.M16FRS 16GB SODIMM DDR4 3200MT/s          | 1         | 4.17%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 8         | 47.06%  |
| DDR4   | 6         | 35.29%  |
| LPDDR4 | 3         | 17.65%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 16        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 10        | 50%     |
| 8192  | 4         | 20%     |
| 2048  | 2         | 10%     |
| 1024  | 2         | 10%     |
| 32768 | 1         | 5%      |
| 16384 | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 6         | 28.57%  |
| 2667  | 4         | 19.05%  |
| 2400  | 3         | 14.29%  |
| 1334  | 3         | 14.29%  |
| 3200  | 2         | 9.52%   |
| 3266  | 1         | 4.76%   |
| 1067  | 1         | 4.76%   |
| 800   | 1         | 4.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 20%     |
| Microdia                               | 5         | 14.29%  |
| Apple                                  | 4         | 11.43%  |
| Acer                                   | 4         | 11.43%  |
| Quanta                                 | 3         | 8.57%   |
| IMC Networks                           | 3         | 8.57%   |
| Sunplus Innovation Technology          | 2         | 5.71%   |
| Suyin                                  | 1         | 2.86%   |
| Silicon Motion                         | 1         | 2.86%   |
| Ricoh                                  | 1         | 2.86%   |
| Realtek Semiconductor                  | 1         | 2.86%   |
| Goertek Electronics                    | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.86%   |
| Alcor Micro                            | 1         | 2.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 2         | 5.71%   |
| Chicony HP TrueVision HD                            | 2         | 5.71%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 5.71%   |
| Acer HD Webcam                                      | 2         | 5.71%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 2.86%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 2.86%   |
| Ricoh HD Webcam                                     | 1         | 2.86%   |
| Realtek Integrated Webcam                           | 1         | 2.86%   |
| Quanta VGA WebCam                                   | 1         | 2.86%   |
| Quanta HP TrueVision HD Camera                      | 1         | 2.86%   |
| Quanta HD User Facing                               | 1         | 2.86%   |
| Microdia Webcam Vitade AF                           | 1         | 2.86%   |
| Microdia PC Microscope camera                       | 1         | 2.86%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 2.86%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 2.86%   |
| Microdia HP Integrated Webcam                       | 1         | 2.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 2.86%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 2.86%   |
| IMC Networks Integrated Camera                      | 1         | 2.86%   |
| Goertek USB2.0 VGA UVC WebCam                       | 1         | 2.86%   |
| Chicony USB2.0 Camera                               | 1         | 2.86%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 2.86%   |
| Chicony Integrated HP HD Webcam                     | 1         | 2.86%   |
| Chicony Integrated Camera                           | 1         | 2.86%   |
| Chicony HD User Facing                              | 1         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 2.86%   |
| Apple FaceTime Camera                               | 1         | 2.86%   |
| Apple Built-in iSight                               | 1         | 2.86%   |
| Alcor Micro USB 2.0 PC cam                          | 1         | 2.86%   |
| Acer SunplusIT Integrated Camera                    | 1         | 2.86%   |
| Acer Lenovo EasyCamera                              | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 60%     |
| Synaptics        | 2         | 40%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 75%     |
| OmniKey  | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| OmniKey CardMan Smart@Link                                                   | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 17        | 50%     |
| 1     | 14        | 41.18%  |
| 2     | 3         | 8.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 6         | 33.33%  |
| Fingerprint reader    | 5         | 27.78%  |
| Chipcard              | 3         | 16.67%  |
| Graphics card         | 2         | 11.11%  |
| Multimedia controller | 1         | 5.56%   |
| Bluetooth             | 1         | 5.56%   |

