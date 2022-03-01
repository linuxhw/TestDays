Parrot 5.0 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Parrot 5.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot_5.0/Desktop/README.md) and [notebooks](/Dist/Parrot_5.0/Notebook/README.md).

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

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Chuwi     | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| SLIMBOOK  | ONE-AMD-M4                  | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung   | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell      | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba   | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer      | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi     | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer      | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| HP        | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP        | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple     | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple     | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| SLIMBOOK  | ONE-AMD-M4                  | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell      | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo    | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| Acer      | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo    | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell      | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| Lenovo    | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo    | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Dell      | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell      | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte  | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| Lenovo    | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo    | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell      | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| Acer      | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP        | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| HP        | Pavilion g7                 | Notebook    | [d27bb0d31e](https://linux-hardware.org/?probe=d27bb0d31e) | Oct 31, 2021 |
| Lenovo    | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo    | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| HP        | Pavilion g7                 | Notebook    | [b386e97faa](https://linux-hardware.org/?probe=b386e97faa) | Oct 25, 2021 |
| Dell      | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell      | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| HP        | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| HP        | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP        | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP        | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Gigabyte  | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP        | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64  | 23        | 71.88%  |
| 5.14.0-2parrot1-amd64  | 7         | 21.88%  |
| 5.15.0-5parrot1-amd64  | 1         | 3.13%   |
| 5.15.0-15parrot1-amd64 | 1         | 3.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 28        | 93.33%  |
| 5.15.0  | 2         | 6.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 28        | 93.33%  |
| 5.15    | 2         | 6.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 29        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| MATE    | 19        | 65.52%  |
| KDE5    | 6         | 20.69%  |
| XFCE    | 1         | 3.45%   |
| KDE     | 1         | 3.45%   |
| GNOME   | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 28        | 96.55%  |
| Wayland | 1         | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 17        | 58.62%  |
| LightDM | 12        | 41.38%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 14        | 48.28%  |
| en_IN | 3         | 10.34%  |
| es_ES | 2         | 6.9%    |
| en_GB | 2         | 6.9%    |
| ru_RU | 1         | 3.45%   |
| pt_BR | 1         | 3.45%   |
| fr_FR | 1         | 3.45%   |
| es_MX | 1         | 3.45%   |
| en_ZA | 1         | 3.45%   |
| en_DK | 1         | 3.45%   |
| de_DE | 1         | 3.45%   |
| cs_CZ | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 21        | 72.41%  |
| EFI  | 8         | 27.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 25        | 86.21%  |
| Ext4    | 3         | 10.34%  |
| Overlay | 1         | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 17        | 58.62%  |
| MBR     | 6         | 20.69%  |
| GPT     | 6         | 20.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 28        | 96.55%  |
| Yes       | 1         | 3.45%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 23        | 79.31%  |
| Yes       | 6         | 20.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 6         | 20.69%  |
| Dell                | 6         | 20.69%  |
| Hewlett-Packard     | 5         | 17.24%  |
| Acer                | 4         | 13.79%  |
| Toshiba             | 1         | 3.45%   |
| SLIMBOOK            | 1         | 3.45%   |
| Samsung Electronics | 1         | 3.45%   |
| Microsoft           | 1         | 3.45%   |
| Gigabyte Technology | 1         | 3.45%   |
| Chuwi               | 1         | 3.45%   |
| ASUSTek Computer    | 1         | 3.45%   |
| Apple               | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba Satellite C75D-B                    | 1         | 3.45%   |
| SLIMBOOK ONE-AMD-M4                         | 1         | 3.45%   |
| Samsung 550P5C/550P7C                       | 1         | 3.45%   |
| Microsoft Surface Book                      | 1         | 3.45%   |
| Lenovo Yoga C930-13IKB 81C4                 | 1         | 3.45%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 3.45%   |
| Lenovo ThinkPad T480 20L6SCYP00             | 1         | 3.45%   |
| Lenovo ThinkPad E14 20RA0016GE              | 1         | 3.45%   |
| Lenovo IdeaPad Y580                         | 1         | 3.45%   |
| Lenovo B50-80 80EW                          | 1         | 3.45%   |
| HP ProBook 4535s                            | 1         | 3.45%   |
| HP Pavilion g7                              | 1         | 3.45%   |
| HP Notebook                                 | 1         | 3.45%   |
| HP Laptop 15q-dy0xxx                        | 1         | 3.45%   |
| HP EliteBook 840 G3                         | 1         | 3.45%   |
| Gigabyte A320M-S2H                          | 1         | 3.45%   |
| Dell OptiPlex 7010                          | 1         | 3.45%   |
| Dell OptiPlex 3020                          | 1         | 3.45%   |
| Dell Latitude E7450                         | 1         | 3.45%   |
| Dell Latitude E6410                         | 1         | 3.45%   |
| Dell Latitude 7480                          | 1         | 3.45%   |
| Dell Inspiron N5110                         | 1         | 3.45%   |
| Chuwi GemiBook                              | 1         | 3.45%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR        | 1         | 3.45%   |
| Apple MacBook7,1                            | 1         | 3.45%   |
| Acer TravelMate 5720                        | 1         | 3.45%   |
| Acer Nitro AN517-41                         | 1         | 3.45%   |
| Acer Nitro AN515-54                         | 1         | 3.45%   |
| Acer Aspire A315-21                         | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 3         | 10.34%  |
| Dell Latitude       | 3         | 10.34%  |
| Dell OptiPlex       | 2         | 6.9%    |
| Acer Nitro          | 2         | 6.9%    |
| Toshiba Satellite   | 1         | 3.45%   |
| SLIMBOOK ONE-AMD-M4 | 1         | 3.45%   |
| Samsung 550P5C      | 1         | 3.45%   |
| Microsoft Surface   | 1         | 3.45%   |
| Lenovo Yoga         | 1         | 3.45%   |
| Lenovo IdeaPad      | 1         | 3.45%   |
| Lenovo B50-80       | 1         | 3.45%   |
| HP ProBook          | 1         | 3.45%   |
| HP Pavilion         | 1         | 3.45%   |
| HP Notebook         | 1         | 3.45%   |
| HP Laptop           | 1         | 3.45%   |
| HP EliteBook        | 1         | 3.45%   |
| Gigabyte A320M-S2H  | 1         | 3.45%   |
| Dell Inspiron       | 1         | 3.45%   |
| Chuwi GemiBook      | 1         | 3.45%   |
| ASUS VivoBook       | 1         | 3.45%   |
| Apple MacBook7      | 1         | 3.45%   |
| Acer TravelMate     | 1         | 3.45%   |
| Acer Aspire         | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 4         | 13.79%  |
| 2018 | 4         | 13.79%  |
| 2017 | 3         | 10.34%  |
| 2012 | 3         | 10.34%  |
| 2011 | 3         | 10.34%  |
| 2019 | 2         | 6.9%    |
| 2016 | 2         | 6.9%    |
| 2014 | 2         | 6.9%    |
| 2010 | 2         | 6.9%    |
| 2020 | 1         | 3.45%   |
| 2015 | 1         | 3.45%   |
| 2013 | 1         | 3.45%   |
| 2007 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 23        | 79.31%  |
| Desktop     | 4         | 13.79%  |
| Tablet      | 1         | 3.45%   |
| Convertible | 1         | 3.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 29        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 29        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 8         | 27.59%  |
| 4.01-8.0   | 7         | 24.14%  |
| 8.01-16.0  | 6         | 20.69%  |
| 32.01-64.0 | 4         | 13.79%  |
| 16.01-24.0 | 4         | 13.79%  |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 15        | 51.72%  |
| 1.01-2.0  | 8         | 27.59%  |
| 4.01-8.0  | 2         | 6.9%    |
| 8.01-16.0 | 2         | 6.9%    |
| 3.01-4.0  | 1         | 3.45%   |
| 0.51-1.0  | 1         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 19        | 65.52%  |
| 2      | 10        | 34.48%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 17        | 58.62%  |
| Yes       | 12        | 41.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 86.21%  |
| No        | 4         | 13.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 96.55%  |
| No        | 1         | 3.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 75.86%  |
| No        | 7         | 24.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 11        | 37.93%  |
| India        | 3         | 10.34%  |
| UK           | 2         | 6.9%    |
| Spain        | 2         | 6.9%    |
| Denmark      | 2         | 6.9%    |
| South Africa | 1         | 3.45%   |
| Russia       | 1         | 3.45%   |
| Netherlands  | 1         | 3.45%   |
| Mexico       | 1         | 3.45%   |
| Germany      | 1         | 3.45%   |
| France       | 1         | 3.45%   |
| Czechia      | 1         | 3.45%   |
| Brazil       | 1         | 3.45%   |
| Algeria      | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Viby J               | 1         | 3.45%   |
| St Petersburg        | 1         | 3.45%   |
| Spotsylvania         | 1         | 3.45%   |
| Skive                | 1         | 3.45%   |
| Seattle              | 1         | 3.45%   |
| SÃ£o Paulo         | 1         | 3.45%   |
| Saint Clair          | 1         | 3.45%   |
| Ruskin               | 1         | 3.45%   |
| Pretoria             | 1         | 3.45%   |
| Prague               | 1         | 3.45%   |
| Pittsburgh           | 1         | 3.45%   |
| Phoenix              | 1         | 3.45%   |
| Newark               | 1         | 3.45%   |
| Mt. Pleasant         | 1         | 3.45%   |
| Mostoles             | 1         | 3.45%   |
| MazatlÃ¡n          | 1         | 3.45%   |
| Mangalagiri          | 1         | 3.45%   |
| Los Angeles          | 1         | 3.45%   |
| Grand Junction       | 1         | 3.45%   |
| Cannes               | 1         | 3.45%   |
| Camden               | 1         | 3.45%   |
| Bristol              | 1         | 3.45%   |
| Birmingham           | 1         | 3.45%   |
| Berlin               | 1         | 3.45%   |
| Beri Khas            | 1         | 3.45%   |
| Bengaluru            | 1         | 3.45%   |
| Amsterdam            | 1         | 3.45%   |
| Algiers              | 1         | 3.45%   |
| AlcalÃ¡ de Henares | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 5      | 13.51%  |
| Samsung Electronics | 5         | 5      | 13.51%  |
| WDC                 | 4         | 5      | 10.81%  |
| Seagate             | 4         | 4      | 10.81%  |
| Sandisk             | 4         | 5      | 10.81%  |
| Kingston            | 2         | 2      | 5.41%   |
| China               | 2         | 3      | 5.41%   |
| Team                | 1         | 1      | 2.7%    |
| PNY                 | 1         | 1      | 2.7%    |
| Netac               | 1         | 2      | 2.7%    |
| KingSpec            | 1         | 1      | 2.7%    |
| Intenso             | 1         | 2      | 2.7%    |
| HUAWEI              | 1         | 1      | 2.7%    |
| Hitachi             | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |
| BHT                 | 1         | 1      | 2.7%    |
| ASMedia             | 1         | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB               | 3         | 7.89%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 2.63%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 2.63%   |
| WDC WD10EARS-00Y5B1 1TB              | 1         | 2.63%   |
| WDC PC SN720 SDAPNTW-512G-1101 512GB | 1         | 2.63%   |
| Toshiba MQ01ABD075 752GB             | 1         | 2.63%   |
| Toshiba MK2555GSXF 250GB             | 1         | 2.63%   |
| Team TM8PS7512G 512GB SSD            | 1         | 2.63%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 2.63%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 2.63%   |
| Seagate ST250DM000-1BD141 250GB      | 1         | 2.63%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 2.63%   |
| SanDisk SDSSDH3 2T00 2TB             | 1         | 2.63%   |
| Sandisk NVMe SSD Drive 256GB         | 1         | 2.63%   |
| Sandisk NVMe SSD Drive 250GB         | 1         | 2.63%   |
| Sandisk NVMe SSD Drive 1TB           | 1         | 2.63%   |
| Sandisk NVMe SSD Drive 1024GB        | 1         | 2.63%   |
| Samsung SSD 850 EVO 250GB            | 1         | 2.63%   |
| Samsung NVMe SSD Drive 1024GB        | 1         | 2.63%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 1         | 2.63%   |
| Samsung MZMPC032HBCD-000L1 32GB SSD  | 1         | 2.63%   |
| Samsung MZFLV128HCGR-000MV 128GB     | 1         | 2.63%   |
| PNY CS900 240GB SSD                  | 1         | 2.63%   |
| Netac S535N8/256 256GB SSD           | 1         | 2.63%   |
| Kingston SV300S37A120G 120GB SSD     | 1         | 2.63%   |
| Kingston SKC600512G 512GB SSD        | 1         | 2.63%   |
| KingSpec NT-1TB                      | 1         | 2.63%   |
| Intenso SSD SATAIII 480GB            | 1         | 2.63%   |
| HUAWEI SD Storage 2GB                | 1         | 2.63%   |
| Hitachi HTS542525K9SA00 250GB        | 1         | 2.63%   |
| HGST HTS541010A9E680 1TB             | 1         | 2.63%   |
| Crucial CT250MX500SSD1 250GB         | 1         | 2.63%   |
| China SATA SSD 256GB                 | 1         | 2.63%   |
| China SATA SSD 240GB                 | 1         | 2.63%   |
| BHT WR202HH032G E70290F5 32GB SSD    | 1         | 2.63%   |
| ASMedia USB 3.0 Device 2TB           | 1         | 2.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 35.71%  |
| Seagate | 4         | 4      | 28.57%  |
| WDC     | 2         | 3      | 14.29%  |
| Hitachi | 1         | 1      | 7.14%   |
| HGST    | 1         | 1      | 7.14%   |
| ASMedia | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 13.33%  |
| Kingston            | 2         | 2      | 13.33%  |
| China               | 2         | 3      | 13.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| Team                | 1         | 1      | 6.67%   |
| SanDisk             | 1         | 1      | 6.67%   |
| PNY                 | 1         | 1      | 6.67%   |
| Netac               | 1         | 2      | 6.67%   |
| KingSpec            | 1         | 1      | 6.67%   |
| Intenso             | 1         | 2      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |
| BHT                 | 1         | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 14        | 18     | 40%     |
| HDD     | 13        | 15     | 37.14%  |
| NVMe    | 7         | 8      | 20%     |
| Unknown | 1         | 1      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 24        | 32     | 72.73%  |
| NVMe | 7         | 8      | 21.21%  |
| SAS  | 2         | 2      | 6.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 19     | 51.85%  |
| 0.51-1.0   | 9         | 10     | 33.33%  |
| 1.01-2.0   | 4         | 4      | 14.81%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 501-1000   | 9         | 31.03%  |
| 101-250    | 7         | 24.14%  |
| 1001-2000  | 6         | 20.69%  |
| 251-500    | 2         | 6.9%    |
| 2001-3000  | 2         | 6.9%    |
| 1-20       | 1         | 3.45%   |
| 51-100     | 1         | 3.45%   |
| Unknown    | 1         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 21-50    | 10        | 33.33%  |
| 51-100   | 7         | 23.33%  |
| 101-250  | 5         | 16.67%  |
| 1-20     | 3         | 10%     |
| 251-500  | 2         | 6.67%   |
| 501-1000 | 2         | 6.67%   |
| Unknown  | 1         | 3.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST250DM000-1BD141 250GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 18        | 28     | 60%     |
| Works    | 11        | 13     | 36.67%  |
| Malfunc  | 1         | 1      | 3.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 16        | 50%     |
| AMD                 | 8         | 25%     |
| Sandisk             | 4         | 12.5%   |
| Samsung Electronics | 3         | 9.38%   |
| Nvidia              | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 22.22%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 11.11%  |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 3         | 8.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 5.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 5.56%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 2.78%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 2.78%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 2.78%   |
| Nvidia MCP89 SATA Controller                                                   | 1         | 2.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 2.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 2.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1         | 2.78%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 1         | 2.78%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 1         | 2.78%   |
| AMD FCH SATA Controller D                                                      | 1         | 2.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 19        | 57.58%  |
| NVMe | 7         | 21.21%  |
| RAID | 4         | 12.12%  |
| IDE  | 3         | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 21        | 72.41%  |
| AMD    | 8         | 27.59%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Pentium CPU G630 @ 2.70GHz             | 1         | 3.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz            | 1         | 3.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 3.45%   |
| Intel Core i7-6600U CPU @ 2.60GHz            | 1         | 3.45%   |
| Intel Core i7-5600U CPU @ 2.60GHz            | 1         | 3.45%   |
| Intel Core i7-3630QM CPU @ 2.40GHz           | 1         | 3.45%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 1         | 3.45%   |
| Intel Core i7-10850H CPU @ 2.70GHz           | 1         | 3.45%   |
| Intel Core i5-9300H CPU @ 2.40GHz            | 1         | 3.45%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 1         | 3.45%   |
| Intel Core i5-6300U CPU @ 2.40GHz            | 1         | 3.45%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 1         | 3.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 3.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 1         | 3.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 1         | 3.45%   |
| Intel Core i3-7100U CPU @ 2.40GHz            | 1         | 3.45%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 1         | 3.45%   |
| Intel Core i3-4130 CPU @ 3.40GHz             | 1         | 3.45%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz         | 1         | 3.45%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz         | 1         | 3.45%   |
| Intel Celeron J4125 CPU @ 2.00GHz            | 1         | 3.45%   |
| AMD Ryzen 7 5800H with Radeon Graphics       | 1         | 3.45%   |
| AMD Ryzen 7 4800H with Radeon Graphics       | 1         | 3.45%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics  | 1         | 3.45%   |
| AMD E2-7110 APU with AMD Radeon R2 Graphics  | 1         | 3.45%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G | 1         | 3.45%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 1         | 3.45%   |
| AMD A6-3420M APU with Radeon HD Graphics     | 1         | 3.45%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 7         | 24.14%  |
| Intel Core i5    | 7         | 24.14%  |
| Intel Core i3    | 3         | 10.34%  |
| Intel Core 2 Duo | 2         | 6.9%    |
| AMD Ryzen 7      | 2         | 6.9%    |
| AMD A6           | 2         | 6.9%    |
| Other            | 1         | 3.45%   |
| Intel Pentium    | 1         | 3.45%   |
| Intel Celeron    | 1         | 3.45%   |
| AMD Ryzen 3      | 1         | 3.45%   |
| AMD E2           | 1         | 3.45%   |
| AMD A4           | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 15        | 51.72%  |
| 4      | 11        | 37.93%  |
| 8      | 2         | 6.9%    |
| 6      | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 29        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 18        | 62.07%  |
| 1      | 11        | 37.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 29        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 51.72%  |
| 0x806e9    | 2         | 6.9%    |
| 0x406e3    | 2         | 6.9%    |
| 0x206a7    | 2         | 6.9%    |
| 0x07030105 | 2         | 6.9%    |
| 0xa0652    | 1         | 3.45%   |
| 0x906ed    | 1         | 3.45%   |
| 0x806ea    | 1         | 3.45%   |
| 0x706a8    | 1         | 3.45%   |
| 0x306a9    | 1         | 3.45%   |
| 0x03000027 | 1         | 3.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 20.69%  |
| SandyBridge   | 3         | 10.34%  |
| Skylake       | 2         | 6.9%    |
| Puma          | 2         | 6.9%    |
| Penryn        | 2         | 6.9%    |
| IvyBridge     | 2         | 6.9%    |
| Excavator     | 2         | 6.9%    |
| Broadwell     | 2         | 6.9%    |
| Zen 3         | 1         | 3.45%   |
| Zen 2         | 1         | 3.45%   |
| Zen           | 1         | 3.45%   |
| Westmere      | 1         | 3.45%   |
| K10 Llano     | 1         | 3.45%   |
| Haswell       | 1         | 3.45%   |
| Goldmont plus | 1         | 3.45%   |
| CometLake     | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 57.14%  |
| AMD    | 8         | 22.86%  |
| Nvidia | 7         | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 8.11%   |
| Intel UHD Graphics 620                                                    | 2         | 5.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 5.41%   |
| Intel HD Graphics 620                                                     | 2         | 5.41%   |
| Intel HD Graphics 5500                                                    | 2         | 5.41%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 5.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 5.41%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 2         | 5.41%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 2.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 2.7%    |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 2.7%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1         | 2.7%    |
| Nvidia GK107M [GeForce GTX 660M]                                          | 1         | 2.7%    |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 2.7%    |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 1         | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 2.7%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 2.7%    |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 2.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 2.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 1         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 2.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1         | 2.7%    |
| AMD Sumo [Radeon HD 6520G]                                                | 1         | 2.7%    |
| AMD Renoir                                                                | 1         | 2.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 1         | 2.7%    |
| AMD Mullins [Radeon R3 Graphics]                                          | 1         | 2.7%    |
| AMD Cezanne                                                               | 1         | 2.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 51.72%  |
| 1 x AMD        | 5         | 17.24%  |
| Intel + Nvidia | 4         | 13.79%  |
| 1 x Nvidia     | 2         | 6.9%    |
| 2 x AMD        | 1         | 3.45%   |
| Intel + AMD    | 1         | 3.45%   |
| AMD + Nvidia   | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 27        | 90%     |
| Proprietary | 2         | 6.67%   |
| Unknown     | 1         | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 24        | 80%     |
| 1.01-2.0   | 2         | 6.67%   |
| 0.01-0.5   | 2         | 6.67%   |
| 3.01-4.0   | 1         | 3.33%   |
| 0.51-1.0   | 1         | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 5         | 16.13%  |
| AU Optronics            | 5         | 16.13%  |
| LG Display              | 4         | 12.9%   |
| BOE                     | 4         | 12.9%   |
| Chi Mei Optoelectronics | 3         | 9.68%   |
| Samsung Electronics     | 2         | 6.45%   |
| Unknown (AAA)           | 1         | 3.23%   |
| STD                     | 1         | 3.23%   |
| Panasonic               | 1         | 3.23%   |
| Lenovo                  | 1         | 3.23%   |
| CSO                     | 1         | 3.23%   |
| Apple                   | 1         | 3.23%   |
| AOC                     | 1         | 3.23%   |
| Acer                    | 1         | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch                 | 1         | 3.13%   |
| STD Monitor STD0001 1920x1080                                            | 1         | 3.13%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch        | 1         | 3.13%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch     | 1         | 3.13%   |
| Panasonic VVX10T025J00 MEI96A2 2560x1600 223x125mm 10.1-inch             | 1         | 3.13%   |
| LG Display LCD Monitor LGD05BC 3840x2160 309x174mm 14.0-inch             | 1         | 3.13%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch             | 1         | 3.13%   |
| LG Display LCD Monitor LGD0257 1440x900 304x190mm 14.1-inch              | 1         | 3.13%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch             | 1         | 3.13%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch               | 1         | 3.13%   |
| Lenovo L200pwD LEN1156 1680x1050 433x271mm 20.1-inch                     | 1         | 3.13%   |
| CSO LCD Monitor CSO1500 3840x2160 344x194mm 15.5-inch                    | 1         | 3.13%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch         | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1736 1600x900 382x214mm 17.2-inch          | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 3.13%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch          | 1         | 3.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 1         | 3.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 1         | 3.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 1         | 3.13%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                    | 1         | 3.13%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 1         | 3.13%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 3.13%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch            | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 1         | 3.13%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 1         | 3.13%   |
| Apple Color LCD APP9CC0 1280x800 261x163mm 12.1-inch                     | 1         | 3.13%   |
| AOC LCD Monitor 2217 1680x1050                                           | 1         | 3.13%   |
| Acer X223W ACR0011 1680x1050 473x296mm 22.0-inch                         | 1         | 3.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 11        | 35.48%  |
| 1366x768 (WXGA)    | 7         | 22.58%  |
| 3840x2160 (4K)     | 3         | 9.68%   |
| 1680x1050 (WSXGA+) | 3         | 9.68%   |
| 1600x900 (HD+)     | 3         | 9.68%   |
| 1280x800 (WXGA)    | 2         | 6.45%   |
| 2160x1440          | 1         | 3.23%   |
| 1440x900 (WXGA+)   | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 9         | 28.13%  |
| 17      | 5         | 15.63%  |
| 13      | 5         | 15.63%  |
| 14      | 4         | 12.5%   |
| 40      | 1         | 3.13%   |
| 27      | 1         | 3.13%   |
| 24      | 1         | 3.13%   |
| 23      | 1         | 3.13%   |
| 22      | 1         | 3.13%   |
| 21      | 1         | 3.13%   |
| 20      | 1         | 3.13%   |
| 12      | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 53.13%  |
| 351-400     | 5         | 15.63%  |
| 501-600     | 3         | 9.38%   |
| 401-500     | 3         | 9.38%   |
| 201-300     | 2         | 6.25%   |
| 801-900     | 1         | 3.13%   |
| Unknown     | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 22        | 75.86%  |
| 16/10   | 5         | 17.24%  |
| 3/2     | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 9         | 28.13%  |
| 81-90          | 8         | 25%     |
| 121-130        | 4         | 12.5%   |
| 201-250        | 3         | 9.38%   |
| 71-80          | 1         | 3.13%   |
| 61-70          | 1         | 3.13%   |
| 301-350        | 1         | 3.13%   |
| 251-300        | 1         | 3.13%   |
| 151-200        | 1         | 3.13%   |
| 131-140        | 1         | 3.13%   |
| 501-1000       | 1         | 3.13%   |
| Unknown        | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 10        | 32.26%  |
| 121-160       | 9         | 29.03%  |
| 51-100        | 6         | 19.35%  |
| More than 240 | 3         | 9.68%   |
| 1-50          | 1         | 3.23%   |
| 161-240       | 1         | 3.23%   |
| Unknown       | 1         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 25        | 83.33%  |
| 2     | 4         | 13.33%  |
| 0     | 1         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 17        | 32.08%  |
| Intel                           | 16        | 30.19%  |
| Qualcomm Atheros                | 5         | 9.43%   |
| Broadcom                        | 4         | 7.55%   |
| MediaTek                        | 2         | 3.77%   |
| Samsung Electronics             | 1         | 1.89%   |
| Qualcomm Atheros Communications | 1         | 1.89%   |
| Nvidia                          | 1         | 1.89%   |
| NetGear                         | 1         | 1.89%   |
| Marvell Technology Group        | 1         | 1.89%   |
| Linksys                         | 1         | 1.89%   |
| ICS Advent                      | 1         | 1.89%   |
| Huawei Technologies             | 1         | 1.89%   |
| D-Link System                   | 1         | 1.89%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 9         | 14.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 6.56%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.28%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 3.28%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 3.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 1.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.64%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.64%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.64%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.64%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 1.64%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 1.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.64%   |
| Nvidia MCP89 Ethernet                                                   | 1         | 1.64%   |
| NetGear A6210                                                           | 1         | 1.64%   |
| MediaTek vivo                                                           | 1         | 1.64%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.64%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.64%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 1.64%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.64%   |
| Intel Wireless 8260                                                     | 1         | 1.64%   |
| Intel Wireless 3165                                                     | 1         | 1.64%   |
| Intel Wireless 3160                                                     | 1         | 1.64%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 1.64%   |
| Intel Ethernet Connection (3) I218-LM                                   | 1         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.64%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.64%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.64%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.64%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 1         | 1.64%   |
| Intel 82577LM Gigabit Network Connection                                | 1         | 1.64%   |
| ICS Advent 10/100M LAN                                                  | 1         | 1.64%   |
| Huawei Broadband stick                                                  | 1         | 1.64%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1         | 1.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 1         | 1.64%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.64%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 42.42%  |
| Realtek Semiconductor           | 6         | 18.18%  |
| Qualcomm Atheros                | 4         | 12.12%  |
| Broadcom                        | 3         | 9.09%   |
| Qualcomm Atheros Communications | 1         | 3.03%   |
| NetGear                         | 1         | 3.03%   |
| MEDIATEK                        | 1         | 3.03%   |
| Marvell Technology Group        | 1         | 3.03%   |
| Linksys                         | 1         | 3.03%   |
| D-Link System                   | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 2         | 6.06%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 6.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 3.03%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 3.03%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 3.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 3.03%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 3.03%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.03%   |
| NetGear A6210                                                           | 1         | 3.03%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 3.03%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 3.03%   |
| Linksys WUSB54G v2 802.11g Adapter [Intersil ISL3887]                   | 1         | 3.03%   |
| Intel Wireless-AC 9260                                                  | 1         | 3.03%   |
| Intel Wireless 8260                                                     | 1         | 3.03%   |
| Intel Wireless 3165                                                     | 1         | 3.03%   |
| Intel Wireless 3160                                                     | 1         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 3.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 3.03%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 3.03%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 3.03%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 3.03%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 3.03%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1         | 3.03%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 15        | 55.56%  |
| Intel                 | 6         | 22.22%  |
| Samsung Electronics   | 1         | 3.7%    |
| Qualcomm Atheros      | 1         | 3.7%    |
| Nvidia                | 1         | 3.7%    |
| MediaTek              | 1         | 3.7%    |
| ICS Advent            | 1         | 3.7%    |
| Broadcom              | 1         | 3.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 14.81%  |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 7.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 3.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 3.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 3.7%    |
| Nvidia MCP89 Ethernet                                             | 1         | 3.7%    |
| MediaTek vivo                                                     | 1         | 3.7%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 3.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 3.7%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.7%    |
| ICS Advent 10/100M LAN                                            | 1         | 3.7%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 28        | 52.83%  |
| Ethernet | 24        | 45.28%  |
| Modem    | 1         | 1.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 55%     |
| Ethernet | 18        | 45%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 19        | 65.52%  |
| 1     | 9         | 31.03%  |
| 3     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 19        | 65.52%  |
| Yes  | 10        | 34.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 54.55%  |
| Qualcomm Atheros Communications | 2         | 9.09%   |
| Lite-On Technology              | 2         | 9.09%   |
| Toshiba                         | 1         | 4.55%   |
| Realtek Semiconductor           | 1         | 4.55%   |
| Marvell Semiconductor           | 1         | 4.55%   |
| IMC Networks                    | 1         | 4.55%   |
| Foxconn / Hon Hai               | 1         | 4.55%   |
| Apple                           | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Bluetooth Device                        | 4         | 18.18%  |
| Intel Bluetooth wireless interface            | 2         | 9.09%   |
| Intel AX201 Bluetooth                         | 2         | 9.09%   |
| Intel AX200 Bluetooth                         | 2         | 9.09%   |
| Toshiba BCM43142A0                            | 1         | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                | 1         | 4.55%   |
| Qualcomm Atheros  Bluetooth Device            | 1         | 4.55%   |
| Qualcomm Atheros AR3011 Bluetooth             | 1         | 4.55%   |
| Marvell Bluetooth and Wireless LAN Composite  | 1         | 4.55%   |
| Lite-On Wireless_Device                       | 1         | 4.55%   |
| Lite-On Bluetooth Device                      | 1         | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter      | 1         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver | 1         | 4.55%   |
| IMC Networks Bluetooth Radio                  | 1         | 4.55%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth | 1         | 4.55%   |
| Apple Bluetooth Host Controller               | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 20        | 60.61%  |
| AMD    | 8         | 24.24%  |
| Nvidia | 5         | 15.15%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 14.29%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 7.14%   |
| AMD FCH Azalia Controller                                                  | 3         | 7.14%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 7.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 4.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 4.76%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 4.76%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 4.76%   |
| AMD High Definition Audio Controller                                       | 2         | 4.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 4.76%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 2.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 2.38%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.38%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 2.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 2.38%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 43.75%  |
| Micron Technology   | 3         | 18.75%  |
| Unknown (ABCD)      | 1         | 6.25%   |
| Unknown             | 1         | 6.25%   |
| SK Hynix            | 1         | 6.25%   |
| Ramaxel Technology  | 1         | 6.25%   |
| Kingston            | 1         | 6.25%   |
| Crucial             | 1         | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 12.5%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                        | 1         | 6.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 6.25%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 6.25%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 6.25%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 6.25%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 6.25%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 6.25%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 6.25%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 6.25%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 1         | 6.25%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 6.25%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 6.25%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 1         | 6.25%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR3   | 6         | 50%     |
| DDR4   | 4         | 33.33%  |
| LPDDR4 | 1         | 8.33%   |
| LPDDR3 | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 10        | 83.33%  |
| Row Of Chips | 1         | 8.33%   |
| DIMM         | 1         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 8         | 61.54%  |
| 8192  | 3         | 23.08%  |
| 32768 | 1         | 7.69%   |
| 2048  | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 5         | 33.33%  |
| 2667  | 3         | 20%     |
| 1334  | 2         | 13.33%  |
| 3266  | 1         | 6.67%   |
| 3200  | 1         | 6.67%   |
| 2400  | 1         | 6.67%   |
| 1867  | 1         | 6.67%   |
| 1067  | 1         | 6.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 5         | 17.86%  |
| Microdia                               | 4         | 14.29%  |
| Quanta                                 | 3         | 10.71%  |
| IMC Networks                           | 3         | 10.71%  |
| Apple                                  | 3         | 10.71%  |
| Acer                                   | 3         | 10.71%  |
| Sunplus Innovation Technology          | 2         | 7.14%   |
| Teslong Camera                         | 1         | 3.57%   |
| Suyin                                  | 1         | 3.57%   |
| Silicon Motion                         | 1         | 3.57%   |
| Ricoh                                  | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 2         | 7.14%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 7.14%   |
| Teslong Camera                                      | 1         | 3.57%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 3.57%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 3.57%   |
| Ricoh HD Webcam                                     | 1         | 3.57%   |
| Quanta VGA WebCam                                   | 1         | 3.57%   |
| Quanta HP TrueVision HD Camera                      | 1         | 3.57%   |
| Quanta HD User Facing                               | 1         | 3.57%   |
| Microdia Webcam Vitade AF                           | 1         | 3.57%   |
| Microdia PC Microscope camera                       | 1         | 3.57%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 3.57%   |
| Microdia HP Integrated Webcam                       | 1         | 3.57%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 3.57%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 3.57%   |
| IMC Networks Integrated Camera                      | 1         | 3.57%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 3.57%   |
| Chicony Integrated HP HD Webcam                     | 1         | 3.57%   |
| Chicony Integrated Camera                           | 1         | 3.57%   |
| Chicony HP TrueVision HD                            | 1         | 3.57%   |
| Chicony HD User Facing                              | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 1         | 3.57%   |
| Apple Built-in iSight                               | 1         | 3.57%   |
| Acer SunplusIT Integrated Camera                    | 1         | 3.57%   |
| Acer Lenovo EasyCamera                              | 1         | 3.57%   |
| Acer Integrated Camera                              | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| Synaptics        | 3         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 16.67%  |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 16.67%  |
| Synaptics  WBDI                                   | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Broadcom 5880                                  | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 14        | 46.67%  |
| 0     | 13        | 43.33%  |
| 2     | 3         | 10%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 6         | 33.33%  |
| Net/wireless          | 5         | 27.78%  |
| Multimedia controller | 3         | 16.67%  |
| Graphics card         | 2         | 11.11%  |
| Chipcard              | 2         | 11.11%  |

