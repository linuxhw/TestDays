MX 21 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 38

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
| Intel    | DH55TC AAE70932-303      | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| MP       | MS-7848                  | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI      | MAG B550 TOMAHAWK        | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek  | P8H61/USB3 R2.0          | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| AOpen    | D1009 A1A4               | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell     | 0DR845                   | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| MSI      | B350 TOMAHAWK            | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI      | Z77A-G41                 | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell     | 0200DY A01               | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell     | 0DR845                   | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Gigabyte | H410M S2H V3             | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| ASUSTek  | SABERTOOTH X99           | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Intel    | V1.3                     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| ASUSTek  | SABERTOOTH X99           | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| Gigabyte | B550M S2H                | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock   | N3150M                   | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte | B550M S2H                | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Dell     | 0YXT71 A01               | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo   | 1046 NO DPK              | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte | Z390 UD                  | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| HP       | 3647h                    | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek  | P5GC-MX/MEDION/SI        | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI      | MS-7091                  | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI      | MS-7091                  | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek  | ROG Maximus XIII HERO    | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan   | X99-F8 V2.0              | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan   | X99-F8 V2.0              | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| MSI      | Z97 GAMING 5             | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| ASUSTek  | X99-DELUXE               | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| HP       | 0B4Ch D                  | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| Fujitsu  | D3221-A1 S26361-D3221-A1 | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| GALAX    | B550M                    | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo   | SHARKBAY NO DPK          | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo   | SHARKBAY NO DPK          | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| ASRock   | X570 Steel Legend        | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Gigabyte | X570 AORUS PRO           | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| Gigabyte | B550M DS3H               | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Gigabyte | A320M-S2H V2-CF          | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.10.0-13-amd64           | 5        | 16.13%  |
| 5.10.0-15-amd64           | 4        | 12.9%   |
| 5.14.0-4mx-amd64          | 3        | 9.68%   |
| 5.10.0-16-amd64           | 3        | 9.68%   |
| 5.16.0-5mx-amd64          | 2        | 6.45%   |
| 5.14.0-3mx-amd64          | 2        | 6.45%   |
| 5.10.0-9-amd64            | 2        | 6.45%   |
| 5.10.0-11-amd64           | 2        | 6.45%   |
| 5.16.0-rc5-hwmon-next+    | 1        | 3.23%   |
| 5.16.0-6mx-amd64          | 1        | 3.23%   |
| 5.15.0-2-amd64            | 1        | 3.23%   |
| 5.15.0-0.bpo.2-amd64      | 1        | 3.23%   |
| 5.14.0-2mx-amd64          | 1        | 3.23%   |
| 5.10.52-antix.1-amd64-smp | 1        | 3.23%   |
| 5.10.111-tkg-cfs          | 1        | 3.23%   |
| 5.10.0-10-amd64           | 1        | 3.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 17       | 54.84%  |
| 5.14.0   | 6        | 19.35%  |
| 5.16.0   | 4        | 12.9%   |
| 5.15.0   | 2        | 6.45%   |
| 5.10.52  | 1        | 3.23%   |
| 5.10.111 | 1        | 3.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 19       | 61.29%  |
| 5.14    | 6        | 19.35%  |
| 5.16    | 4        | 12.9%   |
| 5.15    | 2        | 6.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 31       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 23       | 74.19%  |
| KDE5             | 5        | 16.13%  |
| lightdm-xsession | 2        | 6.45%   |
| Unknown          | 1        | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 31       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 26       | 83.87%  |
| SDDM    | 5        | 16.13%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 14       | 45.16%  |
| de_DE | 8        | 25.81%  |
| en_GB | 2        | 6.45%   |
| de_CH | 2        | 6.45%   |
| sv_SE | 1        | 3.23%   |
| pl_PL | 1        | 3.23%   |
| hu_HU | 1        | 3.23%   |
| fr_FR | 1        | 3.23%   |
| es_MX | 1        | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 20       | 64.52%  |
| EFI  | 11       | 35.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 25       | 80.65%  |
| Overlay  | 3        | 9.68%   |
| Reiserfs | 1        | 3.23%   |
| Ext3     | 1        | 3.23%   |
| Btrfs    | 1        | 3.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 20       | 64.52%  |
| MBR  | 11       | 35.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 51.61%  |
| No        | 15       | 48.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 51.61%  |
| No        | 15       | 48.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 5        | 16.13%  |
| ASUSTek Computer    | 5        | 16.13%  |
| MSI                 | 4        | 12.9%   |
| Dell                | 4        | 12.9%   |
| Lenovo              | 2        | 6.45%   |
| Intel               | 2        | 6.45%   |
| Hewlett-Packard     | 2        | 6.45%   |
| ASRock              | 2        | 6.45%   |
| MP                  | 1        | 3.23%   |
| Huanan              | 1        | 3.23%   |
| GALAX               | 1        | 3.23%   |
| Fujitsu             | 1        | 3.23%   |
| AOpen               | 1        | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Dell OptiPlex 755                   | 2        | 6.45%   |
| ASUS All Series                     | 2        | 6.45%   |
| MSI MS-7C91                         | 1        | 3.23%   |
| MSI MS-7A34                         | 1        | 3.23%   |
| MSI MS-7917                         | 1        | 3.23%   |
| MSI MS-7758                         | 1        | 3.23%   |
| MP MS-7848                          | 1        | 3.23%   |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 3.23%   |
| Lenovo 10AAS1QB0B                   | 1        | 3.23%   |
| Intel V1.3                          | 1        | 3.23%   |
| Intel DH55TC AAE70932-303           | 1        | 3.23%   |
| Huanan X99-F8                       | 1        | 3.23%   |
| HP Z400 Workstation                 | 1        | 3.23%   |
| HP Compaq 8000 Elite CMT PC         | 1        | 3.23%   |
| Gigabyte Z390 UD                    | 1        | 3.23%   |
| Gigabyte X570 AORUS PRO             | 1        | 3.23%   |
| Gigabyte H410M S2H V3               | 1        | 3.23%   |
| Gigabyte B550M S2H                  | 1        | 3.23%   |
| Gigabyte B550M DS3H                 | 1        | 3.23%   |
| GALAX B550M                         | 1        | 3.23%   |
| Fujitsu ESPRIMO P720                | 1        | 3.23%   |
| Dell OptiPlex 780                   | 1        | 3.23%   |
| Dell OptiPlex 7010                  | 1        | 3.23%   |
| ASUS ROG Maximus XIII HERO          | 1        | 3.23%   |
| ASUS P8H61/USB3 R2.0                | 1        | 3.23%   |
| ASUS P5GC-MX/MEDION/SI              | 1        | 3.23%   |
| ASRock X570 Steel Legend            | 1        | 3.23%   |
| ASRock N3150M                       | 1        | 3.23%   |
| AOpen ESPRIMO Q900                  | 1        | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 4        | 12.9%   |
| Gigabyte B550M      | 2        | 6.45%   |
| ASUS All            | 2        | 6.45%   |
| MSI MS-7C91         | 1        | 3.23%   |
| MSI MS-7A34         | 1        | 3.23%   |
| MSI MS-7917         | 1        | 3.23%   |
| MSI MS-7758         | 1        | 3.23%   |
| MP MS-7848          | 1        | 3.23%   |
| Lenovo ThinkStation | 1        | 3.23%   |
| Lenovo 10AAS1QB0B   | 1        | 3.23%   |
| Intel V1.3          | 1        | 3.23%   |
| Intel DH55TC        | 1        | 3.23%   |
| Huanan X99-F8       | 1        | 3.23%   |
| HP Z400             | 1        | 3.23%   |
| HP Compaq           | 1        | 3.23%   |
| Gigabyte Z390       | 1        | 3.23%   |
| Gigabyte X570       | 1        | 3.23%   |
| Gigabyte H410M      | 1        | 3.23%   |
| GALAX B550M         | 1        | 3.23%   |
| Fujitsu ESPRIMO     | 1        | 3.23%   |
| ASUS ROG            | 1        | 3.23%   |
| ASUS P8H61          | 1        | 3.23%   |
| ASUS P5GC-MX        | 1        | 3.23%   |
| ASRock X570         | 1        | 3.23%   |
| ASRock N3150M       | 1        | 3.23%   |
| AOpen ESPRIMO       | 1        | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 6        | 19.35%  |
| 2014 | 3        | 9.68%   |
| 2007 | 3        | 9.68%   |
| 2021 | 2        | 6.45%   |
| 2019 | 2        | 6.45%   |
| 2018 | 2        | 6.45%   |
| 2016 | 2        | 6.45%   |
| 2013 | 2        | 6.45%   |
| 2012 | 2        | 6.45%   |
| 2010 | 2        | 6.45%   |
| 2009 | 2        | 6.45%   |
| 2017 | 1        | 3.23%   |
| 2015 | 1        | 3.23%   |
| 2011 | 1        | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 31       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 31       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 31       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 8        | 25.81%  |
| 8.01-16.0   | 7        | 22.58%  |
| 4.01-8.0    | 6        | 19.35%  |
| 3.01-4.0    | 5        | 16.13%  |
| 16.01-24.0  | 2        | 6.45%   |
| 24.01-32.0  | 1        | 3.23%   |
| 2.01-3.0    | 1        | 3.23%   |
| 64.01-256.0 | 1        | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 15       | 48.39%  |
| 2.01-3.0   | 5        | 16.13%  |
| 3.01-4.0   | 4        | 12.9%   |
| 8.01-16.0  | 3        | 9.68%   |
| 4.01-8.0   | 2        | 6.45%   |
| 16.01-24.0 | 1        | 3.23%   |
| 0.51-1.0   | 1        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 29.03%  |
| 3      | 8        | 25.81%  |
| 2      | 8        | 25.81%  |
| 4      | 3        | 9.68%   |
| 5      | 2        | 6.45%   |
| 8      | 1        | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 51.61%  |
| Yes       | 15       | 48.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 64.52%  |
| Yes       | 11       | 35.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 87.1%   |
| Yes       | 4        | 12.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 10       | 32.26%  |
| Germany     | 6        | 19.35%  |
| Switzerland | 2        | 6.45%   |
| India       | 2        | 6.45%   |
| UK          | 1        | 3.23%   |
| Sweden      | 1        | 3.23%   |
| Spain       | 1        | 3.23%   |
| Poland      | 1        | 3.23%   |
| Netherlands | 1        | 3.23%   |
| Mexico      | 1        | 3.23%   |
| Hungary     | 1        | 3.23%   |
| Greece      | 1        | 3.23%   |
| France      | 1        | 3.23%   |
| Estonia     | 1        | 3.23%   |
| Australia   | 1        | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Ettingen            | 2        | 6.45%   |
| Volos               | 1        | 3.23%   |
| Vilhelmina          | 1        | 3.23%   |
| Vasco da Gama       | 1        | 3.23%   |
| Vaidasoo            | 1        | 3.23%   |
| Stevens Point       | 1        | 3.23%   |
| Seelbach            | 1        | 3.23%   |
| San Diego           | 1        | 3.23%   |
| Rosporden           | 1        | 3.23%   |
| Rathenow            | 1        | 3.23%   |
| Puebla City         | 1        | 3.23%   |
| Portland            | 1        | 3.23%   |
| Pompano Beach       | 1        | 3.23%   |
| Pila                | 1        | 3.23%   |
| Piedmont            | 1        | 3.23%   |
| Normal              | 1        | 3.23%   |
| Milwaukee           | 1        | 3.23%   |
| Kamiah              | 1        | 3.23%   |
| Houston             | 1        | 3.23%   |
| Granadilla de Abona | 1        | 3.23%   |
| Gouda               | 1        | 3.23%   |
| Göttingen          | 1        | 3.23%   |
| Freital             | 1        | 3.23%   |
| Dieburg             | 1        | 3.23%   |
| Chingford           | 1        | 3.23%   |
| Budapest            | 1        | 3.23%   |
| Brisbane            | 1        | 3.23%   |
| Berlin              | 1        | 3.23%   |
| Bengaluru           | 1        | 3.23%   |
| Belmont             | 1        | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 14       | 27     | 23.33%  |
| Seagate             | 12       | 15     | 20%     |
| WDC                 | 9        | 13     | 15%     |
| Kingston            | 5        | 5      | 8.33%   |
| Toshiba             | 2        | 2      | 3.33%   |
| PNY                 | 2        | 3      | 3.33%   |
| Hitachi             | 2        | 2      | 3.33%   |
| GOODRAM             | 2        | 2      | 3.33%   |
| Crucial             | 2        | 2      | 3.33%   |
| Corsair             | 2        | 2      | 3.33%   |
| Transcend           | 1        | 1      | 1.67%   |
| SPCC                | 1        | 1      | 1.67%   |
| OCZ                 | 1        | 1      | 1.67%   |
| Micron Technology   | 1        | 1      | 1.67%   |
| Maxtor              | 1        | 1      | 1.67%   |
| Avant               | 1        | 1      | 1.67%   |
| Acer                | 1        | 1      | 1.67%   |
| A-DATA Technology   | 1        | 1      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB           | 3        | 3.95%   |
| Samsung SSD 850 EVO 250GB                | 3        | 3.95%   |
| Kingston SA400S37480G 480GB SSD          | 3        | 3.95%   |
| Toshiba DT01ACA100 1TB                   | 2        | 2.63%   |
| Samsung SSD 970 EVO Plus 1TB             | 2        | 2.63%   |
| Samsung SSD 850 EVO 1TB                  | 2        | 2.63%   |
| Corsair MP400 2TB                        | 2        | 2.63%   |
| WDC WDS500G2B0C-00PXH0 500GB             | 1        | 1.32%   |
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1.32%   |
| WDC WD60EZRZ-00RWYB1 6TB                 | 1        | 1.32%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 1        | 1.32%   |
| WDC WD5002AALX-00J37A0 500GB             | 1        | 1.32%   |
| WDC WD5000AVCS-632DY1 500GB              | 1        | 1.32%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1        | 1.32%   |
| WDC WD30EFRX-68AX9N0 3TB                 | 1        | 1.32%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 1.32%   |
| WDC WD10EVDS-63U8B1 1TB                  | 1        | 1.32%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1.32%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1.32%   |
| Transcend TS128GSSD370S 128GB            | 1        | 1.32%   |
| SPCC Solid State Disk 256GB              | 1        | 1.32%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1.32%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1.32%   |
| Seagate ST3500413AS 500GB                | 1        | 1.32%   |
| Seagate ST3360320AS 360GB                | 1        | 1.32%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1.32%   |
| Seagate ST3160815AS 160GB                | 1        | 1.32%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1.32%   |
| Seagate ST2000DL004 HD204UI 2TB          | 1        | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1.32%   |
| Seagate ST1000DM003-1CH162 1TB           | 1        | 1.32%   |
| Samsung SSD 980 PRO 1TB                  | 1        | 1.32%   |
| Samsung SSD 980 1TB                      | 1        | 1.32%   |
| Samsung SSD 970 PRO 512GB                | 1        | 1.32%   |
| Samsung SSD 870 QVO 2TB                  | 1        | 1.32%   |
| Samsung SSD 870 EVO 500GB                | 1        | 1.32%   |
| Samsung SSD 860 QVO 1TB                  | 1        | 1.32%   |
| Samsung SSD 860 EVO 500GB                | 1        | 1.32%   |
| Samsung SSD 860 EVO 500G                 | 1        | 1.32%   |
| Samsung SSD 860 EVO 250GB                | 1        | 1.32%   |
| Samsung SSD 850 EVO 500GB                | 1        | 1.32%   |
| Samsung SSD 840 Series 120GB             | 1        | 1.32%   |
| Samsung SSD 840 EVO 250GB                | 1        | 1.32%   |
| Samsung MZVPW256HEGL-00000 256GB         | 1        | 1.32%   |
| Samsung MZVLW256HEHP-000L2 256GB         | 1        | 1.32%   |
| Samsung MZVL21T0HCLR-00BL7 1TB           | 1        | 1.32%   |
| Samsung HD501LJ 500GB                    | 1        | 1.32%   |
| Samsung HD204UI 2TB                      | 1        | 1.32%   |
| Samsung HD103SI 1TB                      | 1        | 1.32%   |
| PNY CS900 250GB SSD                      | 1        | 1.32%   |
| PNY CS3030 1TB SSD                       | 1        | 1.32%   |
| PNY CS2130 2TB SSD                       | 1        | 1.32%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 1.32%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1        | 1.32%   |
| Maxtor 4K040H2 40GB                      | 1        | 1.32%   |
| Kingston SV300S37A240G 240GB SSD         | 1        | 1.32%   |
| Kingston SA400S37120G 120GB SSD          | 1        | 1.32%   |
| Hitachi HUA722010CLA330 1TB              | 1        | 1.32%   |
| Hitachi HDS721050CLA360 500GB            | 1        | 1.32%   |
| Goodram SSDPR-CL100-480-G3 480GB         | 1        | 1.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 15     | 44.44%  |
| WDC                 | 7        | 11     | 25.93%  |
| Samsung Electronics | 3        | 3      | 11.11%  |
| Toshiba             | 2        | 2      | 7.41%   |
| Hitachi             | 2        | 2      | 7.41%   |
| Maxtor              | 1        | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 15     | 39.29%  |
| Kingston            | 5        | 5      | 17.86%  |
| GOODRAM             | 2        | 2      | 7.14%   |
| WDC                 | 1        | 1      | 3.57%   |
| Transcend           | 1        | 1      | 3.57%   |
| SPCC                | 1        | 1      | 3.57%   |
| PNY                 | 1        | 1      | 3.57%   |
| OCZ                 | 1        | 1      | 3.57%   |
| Micron Technology   | 1        | 1      | 3.57%   |
| Crucial             | 1        | 1      | 3.57%   |
| Avant               | 1        | 1      | 3.57%   |
| Acer                | 1        | 1      | 3.57%   |
| A-DATA Technology   | 1        | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 23       | 34     | 40.35%  |
| SSD  | 22       | 32     | 38.6%   |
| NVMe | 12       | 15     | 21.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 30       | 64     | 69.77%  |
| NVMe | 12       | 15     | 27.91%  |
| SAS  | 1        | 2      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 24       | 37     | 52.17%  |
| 0.51-1.0   | 13       | 15     | 28.26%  |
| 1.01-2.0   | 5        | 8      | 10.87%  |
| 3.01-4.0   | 2        | 2      | 4.35%   |
| 2.01-3.0   | 1        | 1      | 2.17%   |
| 4.01-10.0  | 1        | 3      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 8        | 25.81%  |
| More than 3000 | 5        | 16.13%  |
| 101-250        | 5        | 16.13%  |
| 1001-2000      | 4        | 12.9%   |
| 501-1000       | 4        | 12.9%   |
| 2001-3000      | 2        | 6.45%   |
| 51-100         | 2        | 6.45%   |
| 1-20           | 1        | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 8        | 25%     |
| 101-250        | 5        | 15.63%  |
| 1-20           | 5        | 15.63%  |
| 51-100         | 5        | 15.63%  |
| 1001-2000      | 3        | 9.38%   |
| More than 3000 | 2        | 6.25%   |
| 251-500        | 2        | 6.25%   |
| 2001-3000      | 1        | 3.13%   |
| 501-1000       | 1        | 3.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 7.69%   |
| WDC WD10EADS-98M2B0 1TB                  | 1        | 1      | 7.69%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 7.69%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 7.69%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 7.69%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 7.69%   |
| Seagate ST320LT020-9YG142 320GB          | 1        | 1      | 7.69%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 7.69%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 7.69%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 7.69%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 7.69%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 7.69%   |
| Goodram SSDPR-CL100-480-G3 480GB         | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 38.46%  |
| WDC                 | 3        | 3      | 23.08%  |
| Samsung Electronics | 3        | 4      | 23.08%  |
| Maxtor              | 1        | 1      | 7.69%   |
| Goodram             | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 5      | 62.5%   |
| WDC     | 2        | 2      | 25%     |
| Maxtor  | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 8      | 58.33%  |
| SSD  | 5        | 6      | 41.67%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 26       | 65     | 66.67%  |
| Malfunc  | 12       | 14     | 30.77%  |
| Detected | 1        | 2      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 23       | 50%     |
| AMD                       | 8        | 17.39%  |
| Samsung Electronics       | 7        | 15.22%  |
| Phison Electronics        | 3        | 6.52%   |
| ASMedia Technology        | 3        | 6.52%   |
| SanDisk                   | 1        | 2.17%   |
| Micron/Crucial Technology | 1        | 2.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 4        | 6.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 6.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 5.08%   |
| Phison E12 NVMe Controller                                                              | 3        | 5.08%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 5.08%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 5.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 5.08%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 5.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 3.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 3.39%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 3.39%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 3.39%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 3.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 3.39%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 3.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 3.39%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 3.39%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.69%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 1.69%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 1.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 1.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 1.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1        | 1.69%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 1        | 1.69%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.69%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 25       | 54.35%  |
| NVMe | 12       | 26.09%  |
| IDE  | 7        | 15.22%  |
| RAID | 2        | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 23       | 74.19%  |
| AMD    | 8        | 25.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 3        | 9.68%   |
| Intel Core i7-5820K CPU @ 3.30GHz          | 2        | 6.45%   |
| Intel Core i5-3350P CPU @ 3.10GHz          | 2        | 6.45%   |
| Intel Xeon CPU W3565 @ 3.20GHz             | 1        | 3.23%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz        | 1        | 3.23%   |
| Intel Core i9-10850K CPU @ 3.60GHz         | 1        | 3.23%   |
| Intel Core i5-9600K CPU @ 3.70GHz          | 1        | 3.23%   |
| Intel Core i5-4690K CPU @ 3.50GHz          | 1        | 3.23%   |
| Intel Core i5-4570T CPU @ 2.90GHz          | 1        | 3.23%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 1        | 3.23%   |
| Intel Core i5 CPU M 520 @ 2.40GHz          | 1        | 3.23%   |
| Intel Core i3-4160 CPU @ 3.60GHz           | 1        | 3.23%   |
| Intel Core i3-4130 CPU @ 3.40GHz           | 1        | 3.23%   |
| Intel Core i3-2350M CPU @ 2.30GHz          | 1        | 3.23%   |
| Intel Core i3-10100 CPU @ 3.60GHz          | 1        | 3.23%   |
| Intel Core i3 CPU 550 @ 3.20GHz            | 1        | 3.23%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz       | 1        | 3.23%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz       | 1        | 3.23%   |
| Intel Celeron CPU N3150 @ 1.60GHz          | 1        | 3.23%   |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores | 1        | 3.23%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 1        | 3.23%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 1        | 3.23%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 1        | 3.23%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 1        | 3.23%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 1        | 3.23%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 1        | 3.23%   |
| AMD Ryzen 3 3100 4-Core Processor          | 1        | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 7        | 22.58%  |
| Intel Core i3          | 5        | 16.13%  |
| Intel Core 2 Duo       | 5        | 16.13%  |
| AMD Ryzen 5            | 3        | 9.68%   |
| Intel Xeon             | 2        | 6.45%   |
| Intel Core i7          | 2        | 6.45%   |
| AMD Ryzen 7            | 2        | 6.45%   |
| Intel Core i9          | 1        | 3.23%   |
| Intel Celeron          | 1        | 3.23%   |
| AMD Ryzen Threadripper | 1        | 3.23%   |
| AMD Ryzen 9            | 1        | 3.23%   |
| AMD Ryzen 3            | 1        | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 11       | 35.48%  |
| 4      | 8        | 25.81%  |
| 6      | 6        | 19.35%  |
| 12     | 3        | 9.68%   |
| 8      | 2        | 6.45%   |
| 10     | 1        | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 31       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 19       | 61.29%  |
| 1      | 12       | 38.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 31       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 5        | 16.13%  |
| 0x306a9    | 3        | 9.68%   |
| 0x1067a    | 3        | 9.68%   |
| 0x306f2    | 2        | 6.45%   |
| 0x306c3    | 2        | 6.45%   |
| 0x20655    | 2        | 6.45%   |
| 0x08701021 | 2        | 6.45%   |
| 0x0800820d | 2        | 6.45%   |
| 0xa0655    | 1        | 3.23%   |
| 0xa0653    | 1        | 3.23%   |
| 0x906ed    | 1        | 3.23%   |
| 0x6fd      | 1        | 3.23%   |
| 0x406c3    | 1        | 3.23%   |
| 0x206a7    | 1        | 3.23%   |
| 0x10676    | 1        | 3.23%   |
| 0x0a201016 | 1        | 3.23%   |
| 0x0a201009 | 1        | 3.23%   |
| 0x08301039 | 1        | 3.23%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 7        | 22.58%  |
| Penryn      | 4        | 12.9%   |
| Zen 3       | 3        | 9.68%   |
| Zen 2       | 3        | 9.68%   |
| IvyBridge   | 3        | 9.68%   |
| Zen+        | 2        | 6.45%   |
| Westmere    | 2        | 6.45%   |
| CometLake   | 2        | 6.45%   |
| Silvermont  | 1        | 3.23%   |
| SandyBridge | 1        | 3.23%   |
| Nehalem     | 1        | 3.23%   |
| KabyLake    | 1        | 3.23%   |
| Core        | 1        | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 12       | 35.29%  |
| Intel  | 12       | 35.29%  |
| AMD    | 10       | 29.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 8.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 5.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 5.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2        | 5.88%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 5.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 5.88%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 5.88%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 2.94%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 2.94%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 2.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 2.94%   |
| Nvidia GK208 [GeForce GT 635]                                                            | 1        | 2.94%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 2.94%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 2.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 2.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 2.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 2.94%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                                        | 1        | 2.94%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                                         | 1        | 2.94%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 2.94%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1        | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 2.94%   |
| AMD Cezanne                                                                              | 1        | 2.94%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                                 | 1        | 2.94%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 2.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 12       | 38.71%  |
| 1 x Intel   | 9        | 29.03%  |
| 1 x AMD     | 9        | 29.03%  |
| Intel + AMD | 1        | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 20       | 64.52%  |
| Proprietary | 10       | 32.26%  |
| Unknown     | 1        | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 11       | 35.48%  |
| 7.01-8.0   | 6        | 19.35%  |
| 3.01-4.0   | 5        | 16.13%  |
| 0.51-1.0   | 3        | 9.68%   |
| 1.01-2.0   | 2        | 6.45%   |
| 8.01-16.0  | 2        | 6.45%   |
| 0.01-0.5   | 2        | 6.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 4        | 11.11%  |
| Hewlett-Packard      | 4        | 11.11%  |
| Fujitsu Siemens      | 4        | 11.11%  |
| Dell                 | 4        | 11.11%  |
| Acer                 | 3        | 8.33%   |
| Medion               | 2        | 5.56%   |
| Goldstar             | 2        | 5.56%   |
| AOC                  | 2        | 5.56%   |
| Ancor Communications | 2        | 5.56%   |
| Vizio                | 1        | 2.78%   |
| Vestel Elektronik    | 1        | 2.78%   |
| SAC                  | 1        | 2.78%   |
| Philips              | 1        | 2.78%   |
| NEC Computers        | 1        | 2.78%   |
| Iiyama               | 1        | 2.78%   |
| Grundig              | 1        | 2.78%   |
| Gigabyte Technology  | 1        | 2.78%   |
| Eizo                 | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                  | 2        | 5.26%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch      | 2        | 5.26%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                    | 1        | 2.63%   |
| Vestel Elektronik 39FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 1        | 2.63%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 2.63%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch      | 1        | 2.63%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1        | 2.63%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch     | 1        | 2.63%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                 | 1        | 2.63%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 2.63%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch           | 1        | 2.63%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                 | 1        | 2.63%   |
| Hewlett-Packard X27q HPN3725 2560x1440 600x340mm 27.2-inch            | 1        | 2.63%   |
| Hewlett-Packard X27q HPN3724 2560x1440 600x340mm 27.2-inch            | 1        | 2.63%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 2.63%   |
| Hewlett-Packard w17e HWP26E0 1440x900 370x230mm 17.2-inch             | 1        | 2.63%   |
| Hewlett-Packard 27es HWP3325 1920x1080 600x340mm 27.2-inch            | 1        | 2.63%   |
| Grundig WUXGA GRU4448 1920x1080 1210x680mm 54.6-inch                  | 1        | 2.63%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 1        | 2.63%   |
| Goldstar E2350 GSM578F 1920x1080 510x290mm 23.1-inch                  | 1        | 2.63%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 800x330mm 34.1-inch      | 1        | 2.63%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 2.63%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch      | 1        | 2.63%   |
| Eizo EV2333W ENC2069 1920x1080 510x287mm 23.0-inch                    | 1        | 2.63%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                     | 1        | 2.63%   |
| Dell SR2320L DELF03A 1920x1080 510x290mm 23.1-inch                    | 1        | 2.63%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                    | 1        | 2.63%   |
| Dell E190S DELA04B 1280x1024 376x301mm 19.0-inch                      | 1        | 2.63%   |
| Dell 1908FP DEL4025 1280x1024 376x301mm 19.0-inch                     | 1        | 2.63%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 1        | 2.63%   |
| AOC L32W961 AOC3296 1360x768 700x390mm 31.5-inch                      | 1        | 2.63%   |
| Ancor Communications BE24A ACI24AB 1920x1200 520x320mm 24.0-inch      | 1        | 2.63%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 1        | 2.63%   |
| Acer S231HL ACR01A6 1920x1080 510x287mm 23.0-inch                     | 1        | 2.63%   |
| Acer K272HL ACR0523 1920x1080 598x336mm 27.0-inch                     | 1        | 2.63%   |
| Acer AL1717 ACRAD54 1280x1024 338x270mm 17.0-inch                     | 1        | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 34.29%  |
| 2560x1440 (QHD)    | 6        | 17.14%  |
| 1680x1050 (WSXGA+) | 4        | 11.43%  |
| 3840x2160 (4K)     | 3        | 8.57%   |
| 3440x1440          | 2        | 5.71%   |
| 1920x1200 (WUXGA)  | 2        | 5.71%   |
| 1280x1024 (SXGA)   | 2        | 5.71%   |
| 2560x1080          | 1        | 2.86%   |
| 1600x900 (HD+)     | 1        | 2.86%   |
| 1440x900 (WXGA+)   | 1        | 2.86%   |
| 1360x768           | 1        | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 20.59%  |
| 23      | 6        | 17.65%  |
| 31      | 4        | 11.76%  |
| 22      | 4        | 11.76%  |
| 34      | 3        | 8.82%   |
| 24      | 2        | 5.88%   |
| 84      | 1        | 2.94%   |
| 54      | 1        | 2.94%   |
| 26      | 1        | 2.94%   |
| 20      | 1        | 2.94%   |
| 19      | 1        | 2.94%   |
| 18      | 1        | 2.94%   |
| 17      | 1        | 2.94%   |
| Unknown | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 45.45%  |
| 401-500     | 6        | 18.18%  |
| 601-700     | 4        | 12.12%  |
| 701-800     | 3        | 9.09%   |
| 351-400     | 1        | 3.03%   |
| 301-350     | 1        | 3.03%   |
| 1501-2000   | 1        | 3.03%   |
| 1001-1500   | 1        | 3.03%   |
| Unknown     | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 21       | 63.64%  |
| 16/10 | 7        | 21.21%  |
| 21/9  | 3        | 9.09%   |
| 5/4   | 2        | 6.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 29.41%  |
| 351-500        | 7        | 20.59%  |
| 301-350        | 7        | 20.59%  |
| 251-300        | 3        | 8.82%   |
| 151-200        | 3        | 8.82%   |
| More than 1000 | 2        | 5.88%   |
| 141-150        | 1        | 2.94%   |
| Unknown        | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 25       | 78.13%  |
| 101-120 | 5        | 15.63%  |
| 1-50    | 1        | 3.13%   |
| Unknown | 1        | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 70.97%  |
| 2     | 6        | 19.35%  |
| 3     | 2        | 6.45%   |
| 0     | 1        | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 17       | 39.53%  |
| Intel                 | 15       | 34.88%  |
| TP-Link               | 2        | 4.65%   |
| Qualcomm Atheros      | 2        | 4.65%   |
| Broadcom              | 2        | 4.65%   |
| Ralink Technology     | 1        | 2.33%   |
| Edimax Technology     | 1        | 2.33%   |
| Broadcom Limited      | 1        | 2.33%   |
| AVM                   | 1        | 2.33%   |
| Aquantia              | 1        | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 26.09%  |
| Intel I211 Gigabit Network Connection                             | 3        | 6.52%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 4.35%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 4.35%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 4.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 2.17%   |
| TP-Link 802.11ac NIC                                              | 1        | 2.17%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 2.17%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 2.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1        | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.17%   |
| Realtek 802.11ac NIC                                              | 1        | 2.17%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 2.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.17%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 2.17%   |
| Intel Wireless 8260                                               | 1        | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.17%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.17%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.17%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.17%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.17%   |
| Edimax RTL8192S WLAN Adapter                                      | 1        | 2.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.17%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1        | 2.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 2.17%   |
| AVM FRITZ!WLAN AC 860                                             | 1        | 2.17%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.17%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 33.33%  |
| TP-Link               | 2        | 16.67%  |
| Ralink Technology     | 1        | 8.33%   |
| Intel                 | 1        | 8.33%   |
| Edimax Technology     | 1        | 8.33%   |
| Broadcom Limited      | 1        | 8.33%   |
| Broadcom              | 1        | 8.33%   |
| AVM                   | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 8.33%   |
| TP-Link 802.11ac NIC                                       | 1        | 8.33%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 8.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 8.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 1        | 8.33%   |
| Realtek 802.11ac NIC                                       | 1        | 8.33%   |
| Ralink MT7601U Wireless Adapter                            | 1        | 8.33%   |
| Intel Wireless 8260                                        | 1        | 8.33%   |
| Edimax RTL8192S WLAN Adapter                               | 1        | 8.33%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 8.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 8.33%   |
| AVM FRITZ!WLAN AC 860                                      | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 15       | 46.88%  |
| Realtek Semiconductor | 13       | 40.63%  |
| Qualcomm Atheros      | 2        | 6.25%   |
| Broadcom              | 1        | 3.13%   |
| Aquantia              | 1        | 3.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12       | 35.29%  |
| Intel I211 Gigabit Network Connection                             | 3        | 8.82%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 5.88%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 5.88%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 5.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.94%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.94%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.94%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.94%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.94%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 2.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.94%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 31       | 73.81%  |
| WiFi     | 11       | 26.19%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 69.7%   |
| WiFi     | 10       | 30.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 25       | 80.65%  |
| 2     | 5        | 16.13%  |
| 3     | 1        | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 67.74%  |
| Yes  | 10       | 32.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 2        | 50%     |
| Cambridge Silicon Radio | 1        | 25%     |
| Apple                   | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 1        | 25%     |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 25%     |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 25%     |
| Apple Bluetooth USB Host Controller                   | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 22       | 38.6%   |
| AMD                 | 12       | 21.05%  |
| Nvidia              | 10       | 17.54%  |
| C-Media Electronics | 3        | 5.26%   |
| ROCCAT              | 2        | 3.51%   |
| Creative Labs       | 2        | 3.51%   |
| Unknown             | 1        | 1.75%   |
| TerraTec Electronic | 1        | 1.75%   |
| Schiit Audio        | 1        | 1.75%   |
| Razer USA           | 1        | 1.75%   |
| JMTek               | 1        | 1.75%   |
| GN Netcom           | 1        | 1.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 High Definition Audio Controller                                                     | 4        | 6.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4        | 6.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 6.06%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3        | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 4.55%   |
| ROCCAT Khan AIMO                                                                                  | 2        | 3.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 3.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2        | 3.03%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 3.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 3.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 3.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 3.03%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2        | 3.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 3.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 3.03%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2        | 3.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 3.03%   |
| Unknown Realtek USB Audio Rear                                                                    | 1        | 1.52%   |
| Unknown Realtek USB Audio Front                                                                   | 1        | 1.52%   |
| TerraTec Electronic Aureon Dual USB                                                               | 1        | 1.52%   |
| Schiit Audio I'm Fulla Schiit                                                                     | 1        | 1.52%   |
| Razer USA Kraken Tournament Edition                                                               | 1        | 1.52%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 1.52%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 1.52%   |
| JMTek USB PnP Audio Device                                                                        | 1        | 1.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 1.52%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.52%   |
| Intel Audio device                                                                                | 1        | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.52%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 1.52%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 1.52%   |
| GN Netcom Jabra BIZ 2300                                                                          | 1        | 1.52%   |
| C-Media Electronics Blue Snowball                                                                 | 1        | 1.52%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1        | 1.52%   |
| C-Media Electronics Audio Adapter                                                                 | 1        | 1.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1        | 1.52%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 1        | 1.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1        | 1.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1        | 1.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 7        | 21.21%  |
| Kingston            | 5        | 15.15%  |
| G.Skill             | 5        | 15.15%  |
| Unknown             | 3        | 9.09%   |
| SK hynix            | 3        | 9.09%   |
| Samsung Electronics | 2        | 6.06%   |
| Nanya Technology    | 2        | 6.06%   |
| Micron Technology   | 2        | 6.06%   |
| Transcend           | 1        | 3.03%   |
| Crucial             | 1        | 3.03%   |
| A-DATA Technology   | 1        | 3.03%   |
| Unknown             | 1        | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s | 2        | 5.71%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 2        | 5.71%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1        | 2.86%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 2.86%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s               | 1        | 2.86%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s       | 1        | 2.86%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1        | 2.86%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s   | 1        | 2.86%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s   | 1        | 2.86%   |
| SK hynix RAM HMT125U6DFR8C-H9 2GB DIMM DDR3 1066MT/s   | 1        | 2.86%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s   | 1        | 2.86%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s   | 1        | 2.86%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR2 2048MT/s     | 1        | 2.86%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s     | 1        | 2.86%   |
| Micron RAM Module 8GB SODIMM DDR3 1333MT/s             | 1        | 2.86%   |
| Micron RAM Module 4GB SODIMM DDR3 1333MT/s             | 1        | 2.86%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s | 1        | 2.86%   |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s   | 1        | 2.86%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s    | 1        | 2.86%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 2.86%   |
| Kingston RAM 99U5471-033.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 2.86%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s  | 1        | 2.86%   |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s  | 1        | 2.86%   |
| G.Skill RAM F4-3600C19-16GSXWB 16GB DIMM DDR4 3600MT/s | 1        | 2.86%   |
| G.Skill RAM F3-2133C11-8GAR 8GB DIMM DDR3 2133MT/s     | 1        | 2.86%   |
| G.Skill RAM F3-12800CL9-4GBRL 4GB DIMM DDR3 1866MT/s   | 1        | 2.86%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1400MT/s   | 1        | 2.86%   |
| Crucial RAM BLS4G4D26BFSB.8FE 4GB DIMM DDR4 2667MT/s   | 1        | 2.86%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s  | 1        | 2.86%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s  | 1        | 2.86%   |
| Corsair RAM CM2X1024-6400 1024MB DIMM DDR2 800MT/s     | 1        | 2.86%   |
| A-DATA RAM Module 4GB DIMM DDR4 2666MT/s               | 1        | 2.86%   |
| Unknown                                                | 1        | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 14       | 46.67%  |
| DDR3  | 12       | 40%     |
| DDR2  | 3        | 10%     |
| SDRAM | 1        | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 28       | 93.33%  |
| SODIMM | 2        | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 13       | 40.63%  |
| 8192  | 6        | 18.75%  |
| 16384 | 5        | 15.63%  |
| 2048  | 5        | 15.63%  |
| 32768 | 2        | 6.25%   |
| 1024  | 1        | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 5        | 15.15%  |
| 3600    | 4        | 12.12%  |
| 2667    | 3        | 9.09%   |
| 2133    | 3        | 9.09%   |
| 1600    | 3        | 9.09%   |
| 3400    | 2        | 6.06%   |
| 2048    | 2        | 6.06%   |
| 3466    | 1        | 3.03%   |
| 3200    | 1        | 3.03%   |
| 2933    | 1        | 3.03%   |
| 2666    | 1        | 3.03%   |
| 1866    | 1        | 3.03%   |
| 1800    | 1        | 3.03%   |
| 1400    | 1        | 3.03%   |
| 1066    | 1        | 3.03%   |
| 800     | 1        | 3.03%   |
| 333     | 1        | 3.03%   |
| Unknown | 1        | 3.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model        | Desktops | Percent |
|--------------|----------|---------|
| Canon MF641C | 1        | 100%    |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Logitech               | 4        | 57.14%  |
| Microsoft              | 2        | 28.57%  |
| Generalplus Technology | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Microsoft LifeCam HD-3000 | 2        | 28.57%  |
| Logitech Webcam C930e     | 2        | 28.57%  |
| Logitech Webcam C270      | 2        | 28.57%  |
| Generalplus WEB CAM       | 1        | 14.29%  |

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
| 0     | 26       | 83.87%  |
| 1     | 5        | 16.13%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 60%     |
| Graphics card    | 2        | 40%     |

