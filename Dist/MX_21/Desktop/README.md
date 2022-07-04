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

Total: 32

| Vendor   | Model                    | Probe                                                      | Date         |
|----------|--------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-13-amd64           | 5        | 20%     |
| 5.14.0-4mx-amd64          | 3        | 12%     |
| 5.10.0-15-amd64           | 3        | 12%     |
| 5.14.0-3mx-amd64          | 2        | 8%      |
| 5.10.0-9-amd64            | 2        | 8%      |
| 5.10.0-11-amd64           | 2        | 8%      |
| 5.16.0-rc5-hwmon-next+    | 1        | 4%      |
| 5.16.0-5mx-amd64          | 1        | 4%      |
| 5.15.0-2-amd64            | 1        | 4%      |
| 5.15.0-0.bpo.2-amd64      | 1        | 4%      |
| 5.14.0-2mx-amd64          | 1        | 4%      |
| 5.10.52-antix.1-amd64-smp | 1        | 4%      |
| 5.10.111-tkg-cfs          | 1        | 4%      |
| 5.10.0-10-amd64           | 1        | 4%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 13       | 52%     |
| 5.14.0   | 6        | 24%     |
| 5.16.0   | 2        | 8%      |
| 5.15.0   | 2        | 8%      |
| 5.10.52  | 1        | 4%      |
| 5.10.111 | 1        | 4%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 15       | 60%     |
| 5.14    | 6        | 24%     |
| 5.16    | 2        | 8%      |
| 5.15    | 2        | 8%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 25       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| XFCE             | 17       | 68%     |
| KDE5             | 5        | 20%     |
| lightdm-xsession | 2        | 8%      |
| Unknown          | 1        | 4%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 25       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 20       | 80%     |
| SDDM    | 5        | 20%     |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 11       | 44%     |
| de_DE | 6        | 24%     |
| en_GB | 2        | 8%      |
| de_CH | 2        | 8%      |
| sv_SE | 1        | 4%      |
| pl_PL | 1        | 4%      |
| fr_FR | 1        | 4%      |
| es_MX | 1        | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 15       | 60%     |
| EFI  | 10       | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 20       | 80%     |
| Overlay  | 2        | 8%      |
| Reiserfs | 1        | 4%      |
| Ext3     | 1        | 4%      |
| Btrfs    | 1        | 4%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 18       | 72%     |
| MBR  | 7        | 28%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 56%     |
| No        | 11       | 44%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 13       | 52%     |
| No        | 12       | 48%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 5        | 20%     |
| ASUSTek Computer    | 4        | 16%     |
| MSI                 | 3        | 12%     |
| Dell                | 3        | 12%     |
| Lenovo              | 2        | 8%      |
| Hewlett-Packard     | 2        | 8%      |
| ASRock              | 2        | 8%      |
| Intel               | 1        | 4%      |
| Huanan              | 1        | 4%      |
| GALAX               | 1        | 4%      |
| Fujitsu             | 1        | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| ASUS All Series                     | 2        | 8%      |
| MSI MS-7A34                         | 1        | 4%      |
| MSI MS-7917                         | 1        | 4%      |
| MSI MS-7758                         | 1        | 4%      |
| Lenovo ThinkStation P620 30E0CTO1WW | 1        | 4%      |
| Lenovo 10AAS1QB0B                   | 1        | 4%      |
| Intel V1.3                          | 1        | 4%      |
| Huanan X99-F8                       | 1        | 4%      |
| HP Z400 Workstation                 | 1        | 4%      |
| HP Compaq 8000 Elite CMT PC         | 1        | 4%      |
| Gigabyte Z390 UD                    | 1        | 4%      |
| Gigabyte X570 AORUS PRO             | 1        | 4%      |
| Gigabyte H410M S2H V3               | 1        | 4%      |
| Gigabyte B550M S2H                  | 1        | 4%      |
| Gigabyte B550M DS3H                 | 1        | 4%      |
| GALAX B550M                         | 1        | 4%      |
| Fujitsu ESPRIMO P720                | 1        | 4%      |
| Dell OptiPlex 780                   | 1        | 4%      |
| Dell OptiPlex 755                   | 1        | 4%      |
| Dell OptiPlex 7010                  | 1        | 4%      |
| ASUS ROG Maximus XIII HERO          | 1        | 4%      |
| ASUS P5GC-MX/MEDION/SI              | 1        | 4%      |
| ASRock X570 Steel Legend            | 1        | 4%      |
| ASRock N3150M                       | 1        | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 3        | 12%     |
| Gigabyte B550M      | 2        | 8%      |
| ASUS All            | 2        | 8%      |
| MSI MS-7A34         | 1        | 4%      |
| MSI MS-7917         | 1        | 4%      |
| MSI MS-7758         | 1        | 4%      |
| Lenovo ThinkStation | 1        | 4%      |
| Lenovo 10AAS1QB0B   | 1        | 4%      |
| Intel V1.3          | 1        | 4%      |
| Huanan X99-F8       | 1        | 4%      |
| HP Z400             | 1        | 4%      |
| HP Compaq           | 1        | 4%      |
| Gigabyte Z390       | 1        | 4%      |
| Gigabyte X570       | 1        | 4%      |
| Gigabyte H410M      | 1        | 4%      |
| GALAX B550M         | 1        | 4%      |
| Fujitsu ESPRIMO     | 1        | 4%      |
| ASUS ROG            | 1        | 4%      |
| ASUS P5GC-MX        | 1        | 4%      |
| ASRock X570         | 1        | 4%      |
| ASRock N3150M       | 1        | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 5        | 20%     |
| 2021 | 2        | 8%      |
| 2019 | 2        | 8%      |
| 2018 | 2        | 8%      |
| 2016 | 2        | 8%      |
| 2014 | 2        | 8%      |
| 2013 | 2        | 8%      |
| 2009 | 2        | 8%      |
| 2007 | 2        | 8%      |
| 2017 | 1        | 4%      |
| 2015 | 1        | 4%      |
| 2012 | 1        | 4%      |
| 2010 | 1        | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 25       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 25       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 25       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 8        | 32%     |
| 4.01-8.0    | 5        | 20%     |
| 3.01-4.0    | 4        | 16%     |
| 8.01-16.0   | 4        | 16%     |
| 16.01-24.0  | 2        | 8%      |
| 2.01-3.0    | 1        | 4%      |
| 64.01-256.0 | 1        | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 12       | 48%     |
| 2.01-3.0   | 5        | 20%     |
| 3.01-4.0   | 3        | 12%     |
| 4.01-8.0   | 2        | 8%      |
| 8.01-16.0  | 2        | 8%      |
| 16.01-24.0 | 1        | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 7        | 28%     |
| 3      | 6        | 24%     |
| 1      | 6        | 24%     |
| 4      | 3        | 12%     |
| 5      | 2        | 8%      |
| 8      | 1        | 4%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 56%     |
| Yes       | 11       | 44%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 68%     |
| Yes       | 8        | 32%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 88%     |
| Yes       | 3        | 12%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 9        | 36%     |
| Germany     | 4        | 16%     |
| Switzerland | 2        | 8%      |
| UK          | 1        | 4%      |
| Sweden      | 1        | 4%      |
| Spain       | 1        | 4%      |
| Poland      | 1        | 4%      |
| Mexico      | 1        | 4%      |
| India       | 1        | 4%      |
| Greece      | 1        | 4%      |
| France      | 1        | 4%      |
| Estonia     | 1        | 4%      |
| Australia   | 1        | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Ettingen            | 2        | 8%      |
| Volos               | 1        | 4%      |
| Vilhelmina          | 1        | 4%      |
| Vaidasoo            | 1        | 4%      |
| Seelbach            | 1        | 4%      |
| San Diego           | 1        | 4%      |
| Rosporden           | 1        | 4%      |
| Puebla City         | 1        | 4%      |
| Portland            | 1        | 4%      |
| Pompano Beach       | 1        | 4%      |
| Pila                | 1        | 4%      |
| Piedmont            | 1        | 4%      |
| Normal              | 1        | 4%      |
| Milwaukee           | 1        | 4%      |
| Kamiah              | 1        | 4%      |
| Houston             | 1        | 4%      |
| Granadilla de Abona | 1        | 4%      |
| Göttingen          | 1        | 4%      |
| Freital             | 1        | 4%      |
| Dieburg             | 1        | 4%      |
| Chingford           | 1        | 4%      |
| Brisbane            | 1        | 4%      |
| Bengaluru           | 1        | 4%      |
| Belmont             | 1        | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 11       | 22     | 21.15%  |
| Seagate             | 9        | 12     | 17.31%  |
| WDC                 | 8        | 12     | 15.38%  |
| Kingston            | 5        | 5      | 9.62%   |
| PNY                 | 2        | 3      | 3.85%   |
| Hitachi             | 2        | 2      | 3.85%   |
| Goodram             | 2        | 2      | 3.85%   |
| Crucial             | 2        | 2      | 3.85%   |
| Corsair             | 2        | 2      | 3.85%   |
| Transcend           | 1        | 1      | 1.92%   |
| Toshiba             | 1        | 1      | 1.92%   |
| SPCC                | 1        | 1      | 1.92%   |
| OCZ                 | 1        | 1      | 1.92%   |
| Micron Technology   | 1        | 1      | 1.92%   |
| Maxtor              | 1        | 1      | 1.92%   |
| Avant               | 1        | 1      | 1.92%   |
| Acer                | 1        | 1      | 1.92%   |
| A-DATA Technology   | 1        | 1      | 1.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB           | 3        | 4.55%   |
| Kingston SA400S37480G 480GB SSD          | 3        | 4.55%   |
| Samsung SSD 970 EVO Plus 1TB             | 2        | 3.03%   |
| Samsung SSD 850 EVO 1TB                  | 2        | 3.03%   |
| Corsair MP400 2TB                        | 2        | 3.03%   |
| WDC WDS500G2B0C-00PXH0 500GB             | 1        | 1.52%   |
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1.52%   |
| WDC WD60EZRZ-00RWYB1 6TB                 | 1        | 1.52%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 1        | 1.52%   |
| WDC WD5002AALX-00J37A0 500GB             | 1        | 1.52%   |
| WDC WD5000AVCS-632DY1 500GB              | 1        | 1.52%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1        | 1.52%   |
| WDC WD30EFRX-68AX9N0 3TB                 | 1        | 1.52%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 1.52%   |
| WDC WD10EVDS-63U8B1 1TB                  | 1        | 1.52%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1.52%   |
| Transcend TS128GSSD370S 128GB            | 1        | 1.52%   |
| Toshiba DT01ACA100 1TB                   | 1        | 1.52%   |
| SPCC Solid State Disk 256GB              | 1        | 1.52%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1.52%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1.52%   |
| Seagate ST3500413AS 500GB                | 1        | 1.52%   |
| Seagate ST3360320AS 360GB                | 1        | 1.52%   |
| Seagate ST3160815AS 160GB                | 1        | 1.52%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB           | 1        | 1.52%   |
| Samsung SSD 980 PRO 1TB                  | 1        | 1.52%   |
| Samsung SSD 970 PRO 512GB                | 1        | 1.52%   |
| Samsung SSD 870 EVO 500GB                | 1        | 1.52%   |
| Samsung SSD 860 QVO 1TB                  | 1        | 1.52%   |
| Samsung SSD 860 EVO 500GB                | 1        | 1.52%   |
| Samsung SSD 860 EVO 500G                 | 1        | 1.52%   |
| Samsung SSD 860 EVO 250GB                | 1        | 1.52%   |
| Samsung SSD 850 EVO 500GB                | 1        | 1.52%   |
| Samsung SSD 850 EVO 250GB                | 1        | 1.52%   |
| Samsung SSD 840 Series 120GB             | 1        | 1.52%   |
| Samsung SSD 840 EVO 250GB                | 1        | 1.52%   |
| Samsung MZVPW256HEGL-00000 256GB         | 1        | 1.52%   |
| Samsung MZVLW256HEHP-000L2 256GB         | 1        | 1.52%   |
| Samsung MZVL21T0HCLR-00BL7 1TB           | 1        | 1.52%   |
| Samsung HD501LJ 500GB                    | 1        | 1.52%   |
| Samsung HD204UI 2TB                      | 1        | 1.52%   |
| PNY CS900 250GB SSD                      | 1        | 1.52%   |
| PNY CS3030 1TB SSD                       | 1        | 1.52%   |
| PNY CS2130 2TB SSD                       | 1        | 1.52%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 1.52%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1        | 1.52%   |
| Maxtor 4K040H2 40GB                      | 1        | 1.52%   |
| Kingston SV300S37A240G 240GB SSD         | 1        | 1.52%   |
| Kingston SA400S37120G 120GB SSD          | 1        | 1.52%   |
| Hitachi HUA722010CLA330 1TB              | 1        | 1.52%   |
| Hitachi HDS721050CLA360 500GB            | 1        | 1.52%   |
| Goodram SSDPR-CL100-480-G3 480GB         | 1        | 1.52%   |
| Goodram SSD 120GB                        | 1        | 1.52%   |
| Crucial CT500P2SSD8 500GB                | 1        | 1.52%   |
| Crucial CT120BX500SSD1 120GB             | 1        | 1.52%   |
| Avant 60GB Client SSD                    | 1        | 1.52%   |
| Acer SSD SA100 120GB                     | 1        | 1.52%   |
| A-DATA SP900 64GB SSD                    | 1        | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 12     | 42.86%  |
| WDC                 | 6        | 10     | 28.57%  |
| Samsung Electronics | 2        | 2      | 9.52%   |
| Hitachi             | 2        | 2      | 9.52%   |
| Toshiba             | 1        | 1      | 4.76%   |
| Maxtor              | 1        | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 12     | 32%     |
| Kingston            | 5        | 5      | 20%     |
| Goodram             | 2        | 2      | 8%      |
| WDC                 | 1        | 1      | 4%      |
| Transcend           | 1        | 1      | 4%      |
| SPCC                | 1        | 1      | 4%      |
| PNY                 | 1        | 1      | 4%      |
| OCZ                 | 1        | 1      | 4%      |
| Micron Technology   | 1        | 1      | 4%      |
| Crucial             | 1        | 1      | 4%      |
| Avant               | 1        | 1      | 4%      |
| Acer                | 1        | 1      | 4%      |
| A-DATA Technology   | 1        | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 19       | 29     | 40.43%  |
| HDD  | 17       | 28     | 36.17%  |
| NVMe | 11       | 14     | 23.4%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 55     | 66.67%  |
| NVMe | 11       | 14     | 30.56%  |
| SAS  | 1        | 2      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 34     | 55.26%  |
| 0.51-1.0   | 9        | 11     | 23.68%  |
| 1.01-2.0   | 4        | 6      | 10.53%  |
| 3.01-4.0   | 2        | 2      | 5.26%   |
| 2.01-3.0   | 1        | 1      | 2.63%   |
| 4.01-10.0  | 1        | 3      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 7        | 28%     |
| More than 3000 | 4        | 16%     |
| 101-250        | 4        | 16%     |
| 1001-2000      | 3        | 12%     |
| 501-1000       | 3        | 12%     |
| 2001-3000      | 2        | 8%      |
| 51-100         | 2        | 8%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 21-50          | 6        | 23.08%  |
| 51-100         | 5        | 19.23%  |
| 101-250        | 4        | 15.38%  |
| 1-20           | 4        | 15.38%  |
| 1001-2000      | 3        | 11.54%  |
| 251-500        | 2        | 7.69%   |
| More than 3000 | 1        | 3.85%   |
| 2001-3000      | 1        | 3.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WDS100T2B0A-00SM50 1TB SSD           | 1        | 1      | 9.09%   |
| WDC WD10EADS-00M2B0 1TB                  | 1        | 1      | 9.09%   |
| Seagate ST500LM021-1KJ152 500GB          | 1        | 1      | 9.09%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 9.09%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 9.09%   |
| Seagate ST250DM000-1BD141 250GB          | 1        | 1      | 9.09%   |
| Samsung Electronics SSD 850 EVO 500GB    | 1        | 1      | 9.09%   |
| Samsung Electronics SSD 850 EVO 1TB      | 1        | 2      | 9.09%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 9.09%   |
| Maxtor 4K040H2 40GB                      | 1        | 1      | 9.09%   |
| Goodram SSDPR-CL100-480-G3 480GB         | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 36.36%  |
| Samsung Electronics | 3        | 4      | 27.27%  |
| WDC                 | 2        | 2      | 18.18%  |
| Maxtor              | 1        | 1      | 9.09%   |
| Goodram             | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 4      | 66.67%  |
| WDC     | 1        | 1      | 16.67%  |
| Maxtor  | 1        | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 5        | 6      | 50%     |
| HDD  | 5        | 6      | 50%     |

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
| Works    | 22       | 57     | 66.67%  |
| Malfunc  | 10       | 12     | 30.3%   |
| Detected | 1        | 2      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 18       | 46.15%  |
| AMD                       | 7        | 17.95%  |
| Samsung Electronics       | 6        | 15.38%  |
| Phison Electronics        | 3        | 7.69%   |
| ASMedia Technology        | 3        | 7.69%   |
| SanDisk                   | 1        | 2.56%   |
| Micron/Crucial Technology | 1        | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 4        | 8.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 6.25%   |
| Phison E12 NVMe Controller                                                       | 3        | 6.25%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3        | 6.25%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3        | 6.25%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3        | 6.25%   |
| AMD 500 Series Chipset SATA Controller                                           | 3        | 6.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2        | 4.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2        | 4.17%   |
| Intel SATA Controller [RAID mode]                                                | 2        | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2        | 4.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2        | 4.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2        | 4.17%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1        | 2.08%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1        | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1        | 2.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 1        | 2.08%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1        | 2.08%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 1        | 2.08%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 2.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1        | 2.08%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1        | 2.08%   |
| Intel 4 Series Chipset PT IDER Controller                                        | 1        | 2.08%   |
| AMD 300 Series Chipset SATA Controller                                           | 1        | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 21       | 55.26%  |
| NVMe | 11       | 28.95%  |
| IDE  | 4        | 10.53%  |
| RAID | 2        | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 72%     |
| AMD    | 7        | 28%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core i7-5820K CPU @ 3.30GHz          | 2        | 8%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 2        | 8%      |
| Intel Xeon CPU W3565 @ 3.20GHz             | 1        | 4%      |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz        | 1        | 4%      |
| Intel Core i9-10850K CPU @ 3.60GHz         | 1        | 4%      |
| Intel Core i5-9600K CPU @ 3.70GHz          | 1        | 4%      |
| Intel Core i5-4690K CPU @ 3.50GHz          | 1        | 4%      |
| Intel Core i5-4570T CPU @ 2.90GHz          | 1        | 4%      |
| Intel Core i5-3470 CPU @ 3.20GHz           | 1        | 4%      |
| Intel Core i5-3350P CPU @ 3.10GHz          | 1        | 4%      |
| Intel Core i5 CPU M 520 @ 2.40GHz          | 1        | 4%      |
| Intel Core i3-4130 CPU @ 3.40GHz           | 1        | 4%      |
| Intel Core i3-10100 CPU @ 3.60GHz          | 1        | 4%      |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz       | 1        | 4%      |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz       | 1        | 4%      |
| Intel Celeron CPU N3150 @ 1.60GHz          | 1        | 4%      |
| AMD Ryzen Threadripper PRO 3945WX 12-Cores | 1        | 4%      |
| AMD Ryzen 9 3900X 12-Core Processor        | 1        | 4%      |
| AMD Ryzen 7 5800X 8-Core Processor         | 1        | 4%      |
| AMD Ryzen 7 2700X Eight-Core Processor     | 1        | 4%      |
| AMD Ryzen 5 5600X 6-Core Processor         | 1        | 4%      |
| AMD Ryzen 5 1600 Six-Core Processor        | 1        | 4%      |
| AMD Ryzen 3 3100 4-Core Processor          | 1        | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 6        | 24%     |
| Intel Core 2 Duo       | 4        | 16%     |
| Intel Xeon             | 2        | 8%      |
| Intel Core i7          | 2        | 8%      |
| Intel Core i3          | 2        | 8%      |
| AMD Ryzen 7            | 2        | 8%      |
| AMD Ryzen 5            | 2        | 8%      |
| Intel Core i9          | 1        | 4%      |
| Intel Celeron          | 1        | 4%      |
| AMD Ryzen Threadripper | 1        | 4%      |
| AMD Ryzen 9            | 1        | 4%      |
| AMD Ryzen 3            | 1        | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 7        | 28%     |
| 2      | 7        | 28%     |
| 6      | 5        | 20%     |
| 12     | 3        | 12%     |
| 8      | 2        | 8%      |
| 10     | 1        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 15       | 60%     |
| 1      | 10       | 40%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 25       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 4        | 16%     |
| 0x306f2    | 2        | 8%      |
| 0x306a9    | 2        | 8%      |
| 0x1067a    | 2        | 8%      |
| 0x08701021 | 2        | 8%      |
| 0x0800820d | 2        | 8%      |
| 0xa0655    | 1        | 4%      |
| 0xa0653    | 1        | 4%      |
| 0x906ed    | 1        | 4%      |
| 0x6fd      | 1        | 4%      |
| 0x406c3    | 1        | 4%      |
| 0x306c3    | 1        | 4%      |
| 0x20655    | 1        | 4%      |
| 0x10676    | 1        | 4%      |
| 0x0a201016 | 1        | 4%      |
| 0x0a201009 | 1        | 4%      |
| 0x08301039 | 1        | 4%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Haswell    | 6        | 24%     |
| Zen 2      | 3        | 12%     |
| Penryn     | 3        | 12%     |
| Zen+       | 2        | 8%      |
| Zen 3      | 2        | 8%      |
| IvyBridge  | 2        | 8%      |
| CometLake  | 2        | 8%      |
| Westmere   | 1        | 4%      |
| Silvermont | 1        | 4%      |
| Nehalem    | 1        | 4%      |
| KabyLake   | 1        | 4%      |
| Core       | 1        | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 11       | 39.29%  |
| Intel  | 9        | 32.14%  |
| AMD    | 8        | 28.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3        | 10.71%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 7.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 7.14%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2        | 7.14%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 3.57%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 3.57%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 3.57%   |
| Nvidia GK208 [GeForce GT 635]                                                            | 1        | 3.57%   |
| Nvidia G94GL [Quadro FX 1800]                                                            | 1        | 3.57%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1        | 3.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 3.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 3.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 3.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1        | 3.57%   |
| AMD RV610 [Radeon HD 2400 PRO/XT]                                                        | 1        | 3.57%   |
| AMD Lexa XT [Radeon PRO WX 3200]                                                         | 1        | 3.57%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 3.57%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                                       | 1        | 3.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1        | 3.57%   |
| AMD Cedar [Radeon HD 7350/8350 / R5 220]                                                 | 1        | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 11       | 44%     |
| 1 x AMD     | 7        | 28%     |
| 1 x Intel   | 6        | 24%     |
| Intel + AMD | 1        | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 15       | 60%     |
| Proprietary | 9        | 36%     |
| Unknown     | 1        | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 7        | 28%     |
| 7.01-8.0   | 6        | 24%     |
| 3.01-4.0   | 5        | 20%     |
| 8.01-16.0  | 2        | 8%      |
| 0.51-1.0   | 2        | 8%      |
| 0.01-0.5   | 2        | 8%      |
| 1.01-2.0   | 1        | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Hewlett-Packard      | 4        | 12.9%   |
| Dell                 | 4        | 12.9%   |
| Fujitsu Siemens      | 3        | 9.68%   |
| Samsung Electronics  | 2        | 6.45%   |
| Medion               | 2        | 6.45%   |
| Goldstar             | 2        | 6.45%   |
| AOC                  | 2        | 6.45%   |
| Ancor Communications | 2        | 6.45%   |
| Acer                 | 2        | 6.45%   |
| Vizio                | 1        | 3.23%   |
| SAC                  | 1        | 3.23%   |
| Philips              | 1        | 3.23%   |
| NEC Computers        | 1        | 3.23%   |
| Iiyama               | 1        | 3.23%   |
| Grundig              | 1        | 3.23%   |
| Gigabyte Technology  | 1        | 3.23%   |
| Eizo                 | 1        | 3.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                  | 2        | 6.06%   |
| Vizio M220MV VIZ0062 1920x1080 480x270mm 21.7-inch                    | 1        | 3.03%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 3.03%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch     | 1        | 3.03%   |
| SAC DP_FREESYNC SAC2700 2560x1440 597x336mm 27.0-inch                 | 1        | 3.03%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1        | 3.03%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch           | 1        | 3.03%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                 | 1        | 3.03%   |
| Hewlett-Packard X27q HPN3725 2560x1440 600x340mm 27.2-inch            | 1        | 3.03%   |
| Hewlett-Packard X27q HPN3724 2560x1440 600x340mm 27.2-inch            | 1        | 3.03%   |
| Hewlett-Packard w2207 HWP26A8 1680x1050 473x296mm 22.0-inch           | 1        | 3.03%   |
| Hewlett-Packard w17e HWP26E0 1440x900 370x230mm 17.2-inch             | 1        | 3.03%   |
| Hewlett-Packard 27es HWP3325 1920x1080 600x340mm 27.2-inch            | 1        | 3.03%   |
| Grundig WXGA GRU4448 1600x1200                                        | 1        | 3.03%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch              | 1        | 3.03%   |
| Goldstar E2350 GSM578F 1920x1080 510x290mm 23.1-inch                  | 1        | 3.03%   |
| Gigabyte Technology G34WQC GBT3400 3440x1440 797x334mm 34.0-inch      | 1        | 3.03%   |
| Fujitsu Siemens L24W-2 FUS077A 1920x1200 518x324mm 24.1-inch          | 1        | 3.03%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch      | 1        | 3.03%   |
| Fujitsu Siemens B22W-5 ECO FUS07C3 1680x1050 474x296mm 22.0-inch      | 1        | 3.03%   |
| Eizo EV2333W ENC2069 1920x1080 510x287mm 23.0-inch                    | 1        | 3.03%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                     | 1        | 3.03%   |
| Dell SR2320L DELF03A 1920x1080 510x290mm 23.1-inch                    | 1        | 3.03%   |
| Dell S3422DW DELD103 3440x1440 800x330mm 34.1-inch                    | 1        | 3.03%   |
| Dell E190S DELA04B 1280x1024 376x301mm 19.0-inch                      | 1        | 3.03%   |
| Dell 1908FP DEL4025 1280x1024 380x300mm 19.1-inch                     | 1        | 3.03%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 1        | 3.03%   |
| AOC L32W961 AOC3296 1360x768 700x390mm 31.5-inch                      | 1        | 3.03%   |
| Ancor Communications BE24A ACI24AB 1920x1200 520x320mm 24.0-inch      | 1        | 3.03%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 1        | 3.03%   |
| Acer K272HL ACR0523 1920x1080 598x336mm 27.0-inch                     | 1        | 3.03%   |
| Acer AL1717 ACRAD54 1280x1024 338x270mm 17.0-inch                     | 1        | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 33.33%  |
| 2560x1440 (QHD)    | 6        | 20%     |
| 1680x1050 (WSXGA+) | 3        | 10%     |
| 3840x2160 (4K)     | 2        | 6.67%   |
| 3440x1440          | 2        | 6.67%   |
| 1920x1200 (WUXGA)  | 2        | 6.67%   |
| 1280x1024 (SXGA)   | 2        | 6.67%   |
| 2560x1080          | 1        | 3.33%   |
| 1440x900 (WXGA+)   | 1        | 3.33%   |
| 1360x768           | 1        | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 7        | 24.14%  |
| 31      | 4        | 13.79%  |
| 23      | 4        | 13.79%  |
| 34      | 3        | 10.34%  |
| 22      | 3        | 10.34%  |
| 24      | 2        | 6.9%    |
| 54      | 1        | 3.45%   |
| 26      | 1        | 3.45%   |
| 19      | 1        | 3.45%   |
| 18      | 1        | 3.45%   |
| 17      | 1        | 3.45%   |
| Unknown | 1        | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 46.43%  |
| 601-700     | 4        | 14.29%  |
| 401-500     | 4        | 14.29%  |
| 701-800     | 3        | 10.71%  |
| 351-400     | 1        | 3.57%   |
| 301-350     | 1        | 3.57%   |
| 1001-1500   | 1        | 3.57%   |
| Unknown     | 1        | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 17       | 60.71%  |
| 16/10 | 6        | 21.43%  |
| 21/9  | 3        | 10.71%  |
| 5/4   | 2        | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 351-500        | 7        | 24.14%  |
| 301-350        | 7        | 24.14%  |
| 201-250        | 7        | 24.14%  |
| 251-300        | 3        | 10.34%  |
| 151-200        | 2        | 6.9%    |
| More than 1000 | 1        | 3.45%   |
| 141-150        | 1        | 3.45%   |
| Unknown        | 1        | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 20       | 74.07%  |
| 101-120 | 5        | 18.52%  |
| 1-50    | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 64%     |
| 2     | 6        | 24%     |
| 3     | 2        | 8%      |
| 0     | 1        | 4%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 12       | 36.36%  |
| Intel                 | 12       | 36.36%  |
| TP-Link               | 2        | 6.06%   |
| Qualcomm Atheros      | 2        | 6.06%   |
| Broadcom              | 2        | 6.06%   |
| Edimax Technology     | 1        | 3.03%   |
| Broadcom Limited      | 1        | 3.03%   |
| Aquantia              | 1        | 3.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 25.71%  |
| Intel I211 Gigabit Network Connection                             | 3        | 8.57%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 5.71%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 5.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 2.86%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 2.86%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1        | 2.86%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1        | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.86%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 2.86%   |
| Intel Wireless 8260                                               | 1        | 2.86%   |
| Intel Ethernet Controller I225-V                                  | 1        | 2.86%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.86%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.86%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.86%   |
| Edimax RTL8192S WLAN Adapter                                      | 1        | 2.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.86%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 1        | 2.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 2.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| TP-Link               | 2        | 25%     |
| Realtek Semiconductor | 2        | 25%     |
| Intel                 | 1        | 12.5%   |
| Edimax Technology     | 1        | 12.5%   |
| Broadcom Limited      | 1        | 12.5%   |
| Broadcom              | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 1        | 12.5%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1        | 12.5%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter        | 1        | 12.5%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter            | 1        | 12.5%   |
| Intel Wireless 8260                                        | 1        | 12.5%   |
| Edimax RTL8192S WLAN Adapter                               | 1        | 12.5%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 1        | 12.5%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 46.15%  |
| Realtek Semiconductor | 10       | 38.46%  |
| Qualcomm Atheros      | 2        | 7.69%   |
| Broadcom              | 1        | 3.85%   |
| Aquantia              | 1        | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 33.33%  |
| Intel I211 Gigabit Network Connection                             | 3        | 11.11%  |
| Intel Ethernet Connection (2) I218-V                              | 2        | 7.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 7.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 3.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.7%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 3.7%    |
| Intel Ethernet Controller I225-V                                  | 1        | 3.7%    |
| Intel Ethernet Connection I217-V                                  | 1        | 3.7%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 3.7%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.7%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 3.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 3.7%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 3.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 75.76%  |
| WiFi     | 8        | 24.24%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 18       | 69.23%  |
| WiFi     | 8        | 30.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 80%     |
| 2     | 4        | 16%     |
| 3     | 1        | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 64%     |
| Yes  | 9        | 36%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| ASUSTek Computer | 2        | 66.67%  |
| Apple            | 1        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 33.33%  |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 33.33%  |
| Apple Bluetooth USB Host Controller                   | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 17       | 36.17%  |
| AMD                 | 10       | 21.28%  |
| Nvidia              | 9        | 19.15%  |
| ROCCAT              | 2        | 4.26%   |
| Creative Labs       | 2        | 4.26%   |
| C-Media Electronics | 2        | 4.26%   |
| Unknown             | 1        | 2.13%   |
| TerraTec Electronic | 1        | 2.13%   |
| Schiit Audio        | 1        | 2.13%   |
| Razer USA           | 1        | 2.13%   |
| GN Netcom           | 1        | 2.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GP104 High Definition Audio Controller                                                     | 4        | 7.41%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 7.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 5.56%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3        | 5.56%   |
| ROCCAT Khan AIMO                                                                                  | 2        | 3.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 3.7%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2        | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 3.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2        | 3.7%    |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 2        | 3.7%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2        | 3.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 3.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 3.7%    |
| Unknown Realtek USB Audio Rear                                                                    | 1        | 1.85%   |
| Unknown Realtek USB Audio Front                                                                   | 1        | 1.85%   |
| TerraTec Electronic Aureon Dual USB                                                               | 1        | 1.85%   |
| Schiit Audio I'm Fulla Schiit                                                                     | 1        | 1.85%   |
| Razer USA Kraken Tournament Edition                                                               | 1        | 1.85%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1        | 1.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.85%   |
| Intel Audio device                                                                                | 1        | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 1.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 1.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 1.85%   |
| GN Netcom Jabra BIZ 2300                                                                          | 1        | 1.85%   |
| C-Media Electronics Blue Snowball                                                                 | 1        | 1.85%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1        | 1.85%   |
| AMD Hawaii HDMI Audio [Radeon R9 290/290X / 390/390X]                                             | 1        | 1.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 1        | 1.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 6        | 23.08%  |
| G.Skill             | 5        | 19.23%  |
| Kingston            | 4        | 15.38%  |
| Unknown             | 2        | 7.69%   |
| SK hynix            | 2        | 7.69%   |
| Samsung Electronics | 2        | 7.69%   |
| Nanya Technology    | 2        | 7.69%   |
| Micron Technology   | 1        | 3.85%   |
| Crucial             | 1        | 3.85%   |
| A-DATA Technology   | 1        | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 2        | 7.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 2        | 7.41%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 1        | 3.7%    |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                 | 1        | 3.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 3.7%    |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s     | 1        | 3.7%    |
| SK hynix RAM HMT125U6DFR8C-H9 2GB DIMM DDR3 1066MT/s     | 1        | 3.7%    |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s     | 1        | 3.7%    |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s     | 1        | 3.7%    |
| Nanya RAM NT2GT64U8HD0BY-AD 2GB DIMM DDR 2048MT/s        | 1        | 3.7%    |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s       | 1        | 3.7%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 3.7%    |
| Kingston RAM KHX3200C16D4/4GX 4GB DIMM DDR4 3600MT/s     | 1        | 3.7%    |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s      | 1        | 3.7%    |
| Kingston RAM 99U5471-033.A00LF 4096MB DIMM DDR3          | 1        | 3.7%    |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 3.7%    |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s    | 1        | 3.7%    |
| G.Skill RAM F4-3600C19-16GSXWB 16GB DIMM DDR4 3600MT/s   | 1        | 3.7%    |
| G.Skill RAM F3-2133C11-8GAR 8GB DIMM DDR3 2133MT/s       | 1        | 3.7%    |
| G.Skill RAM F3-12800CL9-4GBRL 4GB DIMM DDR3 1600MT/s     | 1        | 3.7%    |
| G.Skill RAM F3-10666CL9-4GBNT 4096MB DIMM DDR3 1400MT/s  | 1        | 3.7%    |
| Crucial RAM BLS4G4D26BFSB.8FE 4GB DIMM DDR4 2667MT/s     | 1        | 3.7%    |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 2667MT/s    | 1        | 3.7%    |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s | 1        | 3.7%    |
| A-DATA RAM Module 4GB DIMM DDR4 2666MT/s                 | 1        | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 13       | 54.17%  |
| DDR3  | 8        | 33.33%  |
| DDR2  | 2        | 8.33%   |
| SDRAM | 1        | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 23       | 95.83%  |
| SODIMM | 1        | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 10       | 41.67%  |
| 8192  | 5        | 20.83%  |
| 16384 | 4        | 16.67%  |
| 2048  | 3        | 12.5%   |
| 32768 | 2        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 4        | 15.38%  |
| 1600    | 4        | 15.38%  |
| 2133    | 3        | 11.54%  |
| 3400    | 2        | 7.69%   |
| 2667    | 2        | 7.69%   |
| 1333    | 2        | 7.69%   |
| 3466    | 1        | 3.85%   |
| 3200    | 1        | 3.85%   |
| 2933    | 1        | 3.85%   |
| 2666    | 1        | 3.85%   |
| 2048    | 1        | 3.85%   |
| 1400    | 1        | 3.85%   |
| 1066    | 1        | 3.85%   |
| 333     | 1        | 3.85%   |
| Unknown | 1        | 3.85%   |

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
| Logitech               | 3        | 50%     |
| Microsoft              | 2        | 33.33%  |
| Generalplus Technology | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Microsoft LifeCam HD-3000  | 2        | 33.33%  |
| Logitech Webcam C930e      | 2        | 33.33%  |
| Logitech Webcam C270       | 1        | 16.67%  |
| Generalplus GENERAL WEBCAM | 1        | 16.67%  |

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
| 0     | 22       | 88%     |
| 1     | 3        | 12%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Unassigned class | 3        | 100%    |

